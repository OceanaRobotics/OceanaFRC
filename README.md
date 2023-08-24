# Oceana FRC Team 6128
This is a landing page for both new and existing FIRST Robotics Competition (FRC) members in the Oceana County Region.

# Description
GitHub is "hosting" our static website (powered by Jekyll). All of the files in this "remote repository" (i.e., a folder on GitHub's website) are responsible for producing what you see when you visit: `https://oceanarobotics.github.io/OceanaFRC/`.

# Purpose
- make new blogs to document our FIRST journey
- create a 'Book-of-Knowledge' for the team
- learn web development fundamentals
- discover important news updates for FIRST
- register for FIRST
- learn to build personal website
- and so much more!

# Usage
To get started using this static website-building platform, a few different softwares and dependencies are needed.

# Overview of Softwares & Dependencies:
1. Visual Studio Code - VS Code is an Integrated Development Environment (IDE) for programmers and software developers
2. ruby - interpreted object-oriented scripting language
3. ruby dk - Ruby's development kit, a compiler for Ruby extensions (for Windows)
4. rbenv - virtual Ruby development environment for MacOS
5. homebrew - package manager for macOS
6. git - GitHub content tracker (used to update website)
7. bundle - Ruby dependency manager (used to launch development server)
8. jekyll - static webpage generator
9. gem - RubyGems binary installer

# Packages & Software

## Windows 10
### Visual Studio Code
VS Code is a professional development environment. This will be installed in a Lab for the programming team. To get ahead of that Lab, please follow these steps:

Go to official Visual Studio Code website using your web browser.
- `https://code.visualstudio.com/`

Download the installer
- click <strong>Download for Windows</strong>

Run the installer
- double click downloaded file to run (usually in downloads folder)
- follow the Installation Wizard
- generally OK to accept default settings
- make a shortcut
- check add to PATH (if option is given)

Launch VS Code
- double click shortcut on Desktop to check it out

### Install Ruby
Ruby is an interpreted object-oriented scripting language.
- Download the RubyInstaller for Windows from official website: `https://rubyinstaller.org/downloads`
- Run the installer and check the box that says <strong>"Add Ruby Executables to your PATH"</strong>

### Install Development Kit (DevKit)
Jekyll (static website generator) may require extensions which can be compiled using DevKit
- Download the DevKit for your Ruby version and architecture: `https://rubynstaller.org/add-ons/devkit`
- Extract the DevKit to a permanent location (e.g., C:\DevKit)
- Open a command prompt, navigate to the DevKit directory, and run these commands:
- `ruby dk.rb init`
- `ruby dk.rb isntall`

### Install Jekyll and Bundler
With Ruby, we can install Jekyll and Bundler (a Ruby "gem" for managing gem depenencies)
- open a new command prompt
- run `gem install jekyll bundler`

### Install Git
Git is tool to interact with GitHub and GitHub's revision control system and funcationality.
- Download from official website: `https://git-scm.com/download/win`

### Using Jekyll
You can either [Clone Repository](#clone-repository) or [Create New Jekyll Site](#create-new-jekyll-site) from scratch. Instructions for using Jekyll appear below as they are similar for both Windows and macOS. Look for Clone Repository or Create New Jekyll Site.

## macOS

## Visual Studio Code
This will be installed in a Lab for the programming team. To get ahead of that Lab, follow those steps.

Go to official Visual Studio Code website using your web browser.
- `https://code.visualstudio.com/`

Download the macOS version
- click <strong>Download for macOS</strong>
- this will start a VS Code .dmg file download

Open the DMG file
- double click downloaded file to run (usually in downloads folder)

Drag and drop VS Code
- in the opened DMG window, find the Visual Studio Code applicaiton
- drag and drop into the Applications folder to install it

Launch VS Code
- launch from applications folder

### Install homebrew
Note: for future reference, be careful using `curl` command. Make sure you know what you are curl'ing.
- open Terminal (cmd+space > type Terminal > Enter)
- run the following command: `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

### Install Git
Git is tool to interact with GitHub and GitHub's revision control system and funcationality.
- run `brew install git`

### Install Ruby
Mac comes with Ruby, but the native Ruby is not useful for us. We need to install a different manager like <b>rbenv</b>.
- run `brew install rbenv`

Setup rbenv in your shell by running
- `rnenv init`

Install Ruby using rbenv
- rbenv install 2.7.4
- rbenv global 2.7.4

### Install Bunder and Jekyll
Once Ruby is installed using using rbenv, you can now install Bundler and Jekyll.
- run `gem install bundler jekyll`

### Using Jekyll
You can either clone an existing repository or create a new Jekyll site from scratch. Instructions for using Jekyll appear below as they are similar for both Windows and macOS. Look for Clone Repository or Create New Jekyll Site.

## ChromeOS
TBD - Talk with School Technology Directors

### Clone Repository

<a name="clone-repository"></a>

Cloning is GitHub's processes of copying a "remote repository" (i.e., files from GitHub's servers) for personal use with a "local repository" (i.e., files on your computer).
- Start by creating a directory (folder) where the project will live (e.g., C:\Users\YourUsername\Documents\MyNewFolder, or $/Users/YourUsername/Desktop/MyNewFolder).
- Right click to create the new folder, or using `mkdir` in command prompt
- navigate to `https://https://github.com/OceanaRobotics/OceanaFRC/` with your web browswer
- find and click the <strong>green code dropdown box</strong>

From here, there are options:
1. Clone from command line interface (CLI)
- copy the `https://github.com/OceanaRobotics/OceanaFRC.git` link
- open a new command prompt
- type `git clone https://github.com/OceanaRobotics/OceanaFRC.git`
- hit enter

2. Download & extract ZIP folder
- click Download ZIP
- extract ZIP contents in the newly created directory (MyNewFolder)
  
3. Open with GitHub Desktop
- ignore for now

### Create New Jekyll Site

<a name="create-new-jekyll-site"></a>

After installing Jekyll, you can create a new Jekyll website (instead of cloning) and start working on it.
- Choose or create a directory where you want to store your jekyll site (e.g., C:\Users\YourUsername\Documents\MyJekyllSite, or $/Users/YourUsername/Desktop/MyNewFolder)

Alternative way to create a directory from cmd or Terminal (folder):
- Windows: type `mkdir C:\Users\YourUsername\Documents\MyJekyllSite` > enter)
- macOS: type `mkdir /Users/YourUsername/Desktop/MyNewFolder`

Open a command prompt (Windows) or Terminal (macOS) and nagivate to the directory you just created
- run `jekyll new .`

#### Install Dependencies
Navigate to your Jekyll site's directory (folder) and install the required dependencies:
- Run `bundle install`

#### Start Bundle Server
If you are not hosting your Jekyll site on GitHub Pages (which is free to do), you can run your website locally! This is how to develop your website before launching it!
- run `bundle exec jekyll serve`
  
#### Access Your Website 
Jekyll framework is now running locally on your computer.
- open your browser
- visit `http://127.0.0.1:4000` (i.e., localhost on port 4000)

Note: if you want to do <strong>development for mobile</strong> (i.e., phone, or another device), you can! Follow these steps:
- connect your mobile device to the same network (WiFi or Ethernet) as your main device (laptop or desktop)

Find the IP address of your laptop or desktop (e.g., 192.168.x.x, 10.x.x.x)
- Windows: Control Panel > Network and Sharing Center > Click active connection (WiFi or Ethernet) > click Details > view IPv4 Address or Win + R > type `cmd` > enter > type `ipconfig` > enter > look for IPv4 for WiFi or Ethernet 
- macOS: System Preferences > Network > click active connection (WiFi or Ethernet) > view IP address (e.g., 192.168.x.x, 10.x.x.x) or command + space > typ `Terminal` > type `ipconfig getifaddr en0` and enter (NOTE: could be `en1` instead of `en0`)

Now, instead of running `bundle exec jekyll serve` which will serve at `http://127.0.0.1:4000` you enter this to serve for mobile:
- `bundle exec jekyll serve --host=YOUR_IP_ADDRESS` (e.g., `bundle exec jekyll serve --host=192.168.1.25`)

On your mobile:
- open a browser
- type `http://YOUR_IP_Address:4000/END_POINT/` (e.g., `http://192.168.1.25:4000/OceanaFRC/`)
- Note: case sensitivites and trailing `/`

You are now serving a development server on your main device that you are accessing from another device on the same network ("ad hoc").

## Hosting Jekyll Website
To host your website, you can use GitHub Pages. This requires you to make a GitHub account (or I will let you use the Team's account). Big ideas here:
- make a new repository on GitHub
- make a new branch in that repository called `gh-pages`
- make this the <strong>default branch</strong>

# Issues
Visit `https://jekyllrb.com/` or email `oceana.robots@gmail.com` with a description of the problem, and any errors or screenshots you have.
