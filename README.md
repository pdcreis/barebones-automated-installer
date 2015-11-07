# Barebones automated installer
Automated WordPress and Barebones installation via CLI

Simply move the file to your /usr/local/bin directory, and run 'barebones name_of_the_project'. This will automatically download the latest version of WordPress and install Barebones and all its submodules.

Or:

```
git clone https://github.com/pdcreis/barebones-automated-installer.git
chmod +x barebones-automated-installer/barebones
mv barebones-automated-installer/barebones /usr/local/bin
rm -rf barebones-automated-installer
```

And:

`barebones name_of_the_project`

(The admin password will be asked in order to install node modules)
