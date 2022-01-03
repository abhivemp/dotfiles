# .files

dotfiles are like powerups. Makes you hell of a lot more productive. These are mine.

I've taken inspiration from a lot of developers on GitHub. Credits goes to:

*Holman for showing me the topical setup*

*webpro for showing me bootstraps*

#

I have a different setup. I have a Windows machine but I develop on Linux. I don't use a WSL though. Rather, I use Cygwin (git bash) because most of my files are on the Windows disk.

There weren't a lot of tutorials on configuring a dotfiles repo for Windows users that use git bash. Once I've learned enough, I can create a tutorial of some sort later on.

Feel free to fork this repo to adopt this for your own, should you have a similar configuration as me.

Issues and PRs are welcome 😁

# Key Points

1. I keep my dotfiles in my C:/ 

2. My bashrc and profile are in this repo and I symlink to the C:/

3. Everytime I make an update, I run my bootstrap script to update the symlinks and update bashrc. 

4. Please check the various commands by running `installer/bootstrap` 

# Install and Configure

1. I keep the dotfiles in my C: Drive. After forking, clone the repo to your location. 

2. cd to `installer/` and run the bootstrap `update` command. This will symlink your `.bashrc` and `.gitconfig`. Make sure you change those according to your setup



