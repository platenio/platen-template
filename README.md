# Platen Template

## Prerequisites

To do this, you will need to create a user account for both [GitHub][01] and [Netlify][02] if you
don't already have one; if you create a GitHub account first, you can use that to login to Netlify.

## Easy(ish) Mode

Click this button to copy this template and deploy it to netlify:

[![Deploy to Netlify][img-netlify-btn]][03]

## Manual Mode

1. Click [this link][04] to start the process for creating a new site from our template; this will
   give you your own copy to play with; give the project a name; if you don't want anyone else to
   see your work, select "Private" otherwise leave it to "Public" - ad a description if you want.
1. On the page that automatically opens when you use the template, press the `.` period key - this
   will launch an online code editor and you won't have to have anyting installed or setup locally;
   if you'd prefer to try things locally, see [local workflow](#local-workflow) below.
1. For now, there's nothing you _need_ to change, just leave this tab open.
1. Go to [Netlify][05] and login. From here, you're going to want to add your new project as a
   Netlify site - Netlify has a [blog on how to do so][06]; it will involve authorizing Netlify to
   access GitHub on your behalf and then walk you through adding the site. You won't have to do
   anything beyond the defaults for this to work immediately.

## Moving Forward

At this point, you're able to start editing and changing things. The first thing you might want to
do is change your site name; if you followed the blog above, it explains how to set a custom site
name instead of using the random string it gives you.

If you're using the hosted code editor on github, you'll want to open the `config.yaml` file and
change the `baseURL` value from `platen-template.netlify.app` to
`your-very-cool-site-name.netlify.app`. Once you've made that change and saved, you will see a
little icon with a 1 in a circle on the left of the browser window. Click that, then click the plus
sign for the file you just changed.

In the message box, type "Set site name" and hit enter.

Congrats! You've just edited your site for the first time!

You can write [markdown][07] for blog posts or site pages - everything in the `content` folder is
being rendered on your site. Look through that folder to see how things are used and structured
(more in depth guides on this later, ofc). You can edit any files you please and see the effect.

## Local Workflow

If you want a little more control and immediate feedback, instead of editing in the browser you can
edit locally, but it requires more steps.

### Installing Prereqs on Mac

Open up a terminal window. Then, in that terminal:

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew install git
brew install hugo
brew install golang
brew install --cask visual-studio-code
```

### Installing Prereqs on Windows

Open up a PowerShell terminal window with admin privileges (shift+right click to get the option to
open as admin). Then, in that terminal:

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))

choco install git hugo-extended vscode golang -y
# Strongly recommend closing your terminal at this point
# that way you're not running everything as admin, which can be dangerous!
```

### Getting a Preview Site Up

Assuming you've already followed all the steps above, you can use your newly available tools to
grab a copy of your site and spin it up on your computer:

```sh
# Make sure you're working from a folder you can remember.
# I like to create one like this:
mkdir ~/code
# Then move into it:
cd ~/code
# Make sure to specify your username and repo name here!
git clone https://github.com/username/repo-name.git
# Open your copy of the project in a code editor, like vscode
# Again, use your actual repo name here
code ./repo-name
# Step into your project
cd ./repo-name
# start the live server
hugo server --minify
```

Now that you have the repository open, you can spin up a local copy of your site and see your
changes as you make them!

<!-- Reference Link Definitions -->
[01]: https://github.com/join
[02]: https://app.netlify.com/signup
[03]: https://app.netlify.com/start/deploy?repository=https://github.com/platenio/platen-template
[04]: https://github.com/platenio/platen-template/generate
[05]: https://app.netlify.com/
[06]: https://netlify.com/blog/2016/10/27/a-step-by-step-guide-deploying-a-static-site-or-single-page-app/
[07]: https://www.markdownguide.org/getting-started/
[img-netlify-btn]: https://www.netlify.com/img/deploy/button.svg
