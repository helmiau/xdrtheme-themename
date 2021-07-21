
<h2 align="center">
Xdrem Mini GUI Custom Theme Template for Themer
</h2>

<h4 align="center">
This installer script template is useful for Xderm Mini theme creator.
</h4>

<p align="center">
<img src="https://user-images.githubusercontent.com/20932301/126515598-7665567b-72f0-4cb2-9949-6f6925001c7d.png" alt="ss" class="center">
</p>


### • How to xdrtheme-installer script work
**```xdrtheme-installer```** will clone your github repository and update local file by repo clone, which mean this script need **```wget```** and **```git```** packages.

Script features :
```
1. Install theme               : Installing theme by git clone.
2. Update theme                : Updating theme.
3. Uninstall theme             : Remove installed theme.
4. Reinstall theme             : Force reinstall theme by git clone.
5. Change login panel auth     : Change username and password login page.
6. Install login panel         : Install login panel, you need to login via login panel before you can configure Xderm Mini Gui.
7. Remove login panel          : Remove login panel, you don't need to login to configure Xderm Mini Gui.
```


### • How to use this template
1. Click [Use this template button](https://github.com/helmiau/xdrtheme-themename/generate) then give template/repo name by using format **```xdrtheme-your_theme_name```** without any space there. Change **your_theme_name** to your own theme name.
2. If you want to exclude file or folder from cloning, just write that file/folder name inside **```.gitignore```** file.
3. Fill **```xdrtheme-info```** with your theme information, such as : Theme name, Theme creator, Github username, Theme repository, and active branch which containing theme repository. I made an example below :

```
#--------------------------------------------------------
# Change "Theme_Name" with your theme name below, space allowed
#--------------------------------------------------------
THEMENAME=Theme_Name
#--------------------------------------------------------
# Change "Creator_Name" with  your name below, space allowed
#--------------------------------------------------------
CREATOR=Creator_Name
#--------------------------------------------------------
# Change "github_username_account" with  your github username below, No space allowed
#--------------------------------------------------------
GITUSER=github_username_account
#--------------------------------------------------------
# Change "github_repo_theme" with  your theme repository name below, No space allowed
#--------------------------------------------------------
GITREPO=github_repo_theme
#--------------------------------------------------------
# Change "main_master" with your active branch under theme repository, No space allowed
#--------------------------------------------------------
GITBRANCH=main_master
#--------------------------------------------------------
# Change Theme_Name with  theme version, No space allowed
# Example : v1.0 or v2.1-beta
#--------------------------------------------------------
THEMEVER=v1.0
#--------------------------------------------------------
```

4. Fill **```xdrtheme-update```** with files which will be attached when updating theme. I made an example below :

```
login.php
index.php
header.php
config.txt
```

5. After that, you should make your files and folders structure like this repo. You can replace login.php, header.php and other files with your own files, or You can add your files which is unavailable under this template.
6. Add installation section below to your README.md repository to keep your installer script up-to-update.

````
## Installation
Copy scripts below and run it via **```terminal```**
```
wget -O xdrtheme-installer https://raw.githubusercontent.com/helmiau/xdrtheme-themename/main/xdrtheme-installer && chmod +x xdrtheme-installer && ./xdrtheme-installer
```
````

Run command **```./xdrtheme-installer```** then follow the instructions.

** Important !!! Don't rename ```xdrtheme-info``` and ```xdrtheme-update```. Otherwise you will get an error when using this script.**

** You allowed to rename ```xdrtheme-installer``` only to other name you desired.** 

Note :
- You can see [squarepants96/xdrtheme-adminlte repo's](https://github.com/squarepants96/xdrtheme-adminlte) for sample.


### • Discussions, Issues, Bugs, Feature Request and Others
- Use [Discussions Section](https://github.com/helmiau/xdrtheme-themename/discussions) to discuss about this template, such as new feature request, or improvements.
- Use [Issues Section](https://github.com/helmiau/xdrtheme-themename/issues) if you want to report bug.
- This script is created by [helmiau a.k.a Helmi Amirudin](https://github.com/helmiau) from nothing, so if you need to help me by coding or fixing bug or you desire to give some donation. Please contact me at [My contact site](https://me.helmiau.my.id) or [Discussions Section](https://github.com/helmiau/xdrtheme-themename/discussions)


### • Credits
- [Allah Subhanahu wa Ta'ala](https://id.wikipedia.org/wiki/Allah) ~ Penguasa semesta, sang pemilik ilmu sekaligus sumbernya.
- [Helmi Amirudin](https://github.com/helmiau) ~ Main developer of this template
- [Ryan Fauzi](https://github.com/ryanfauzi1) ~ Developer Xderm Mini GUI
- [Agus Sriawan](https://www.facebook.com/agussriawan.id) ~ Kang bikin tema Blue Light XDERM-MINI
- [Adi Putra](https://github.com/Putra-0) ~ Kang bikin tema [Mejikuhibiniu RGB Theme](https://github.com/Putra-0/theme-xderm-putra)
- [Ardi Setiawan](https://github.com/squarepants96) ~ Kang tester dan creator tema [Admin LTE](https://github.com/squarepants96/xdrtheme-adminlte)

<br>
<h5 align="center">Copyright by <a href="https://me.helmiau.my.id">Helmi Amirudin</a> ® 2021 <br> Thank You ! 🤝</h3>
