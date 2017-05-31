# bterm

[![CircleCI](https://circleci.com/gh/bleenco/bterm/tree/master.svg?style=svg)](https://circleci.com/gh/bleenco/bterm/tree/master)
[![AppVeyor](https://ci.appveyor.com/api/projects/status/0dknthm6g9gq1nw2/branch/master?svg=true)](https://ci.appveyor.com/project/jkuri/bterm-l4yld/branch/master)


## Overview
Fully customisable cross-platform terminal.
Runs everywhere. MacOS, Linux or Windows.

## Download
To download wisit 
[http://bterm.bleenco.io](http://bterm.bleenco.io) click the right installer depending on
operating system you use.  

On initial run `~/.bterm.json` configuration file is created. If you need fix your font for example,
check this file and update your configuration to fit your needs.

## Configuration
When installation is successfully completed and you first run bterm you end up with black and white window.
But as mentioned **bterm** is completely customizable. 

1. Click the settings icon  bottom right corner. 
2. Click the first tab and you can choose the color theme that you like from the list
3. On second tab you can select font that you prefer. 
4. On third select the hot key to open urls inside **bterm**

When you selected  your  settings open .bterm.json file for further configuration. 

On Linux or MacOS  the .bterm.json is located in `~/.bterm.json`.
On Windows you can find it inside `C:\Users\user\.bterm.json`.

Inside **.bterm.json**, you can easily change font size, font color and other colors using standard 
html color codes.

## Usage 
In short you can use bterm just like you are used to use your old terminal. 
**Bterm** offers some nice features: 
* On bottom bar you can at all times see which directory are you in. 
* If you are inside the directory which is git repository you can see the name of the branch 
you are in  on the bottom bar. 

### Keyboard shortcuts 
Shortcuts in **bterm** are similar as you already know them for instance 
<code>ctrl + t </code> for new tab or <code>ctrl + n </code> for new window.
 
 ### Copy and Paste 
 * To copy select text first then right-click on it and select Copy
 * To paste right click and select Paste. 
 
 
### Hacking on bterm

```sh
git clone https://github.com/bleenco/bterm.git
npm install
npm start
```

To make a production build run

```sh
npm run dist
```

### Preview

<p align="center">
  <img src="https://cloud.githubusercontent.com/assets/1796022/24828975/69b690f4-1c69-11e7-9ba2-814a5742e86b.png">
</p>

### LICENCE

MIT

