# Barebones automated installer
Automated WordPress and Barebones installation via CLI

Simply move the file to your /usr/local/bin directory, and run 'barebones name_of_the_project'. This will automatically download the latest version of WordPress and install Barebones and all its submodules.

Or:

```
git clone https://gist.github.com/ec4f6f3c3fb8540e2c3f.git
chmod +x ec4f6f3c3fb8540e2c3f/barebones
mv ec4f6f3c3fb8540e2c3f/barebones /usr/local/bin
rm -rf ec4f6f3c3fb8540e2c3f
```

And:

`barebones name_of_the_project`

(The admin password will be asked in order to install node modules)
