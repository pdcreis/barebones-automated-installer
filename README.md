# WordPress and Barebones automated installer
Basic command-line tool to install the latest version of WordPress and [Barebones](https://github.com/benchmarkstudios/barebones) boilerplate theme (all its submodules are also installed).

### Tasks

* Downloads latest version of WordPress and renames the directory to the project name you've given
* Creates .gitignore file with basic 'ignorable' files/directories
* Removes pre-installed WordPress plugins and themes
* Installs Barebones (and renames it to the project name you've given) and all its submodules
* Installs npm dependencies

### Installation

```
git clone https://github.com/pdcreis/barebones-automated-installer.git
chmod +x barebones-automated-installer/barebones
mv barebones-automated-installer/barebones /usr/local/bin
rm -rf barebones-automated-installer
```

### Usage

Just run `barebones name_of_the_project`, enter your admin password when asked (in order to install node modules), and it's done. 
*The name_of_the_project will be used for your project directory such as the theme directory.*
