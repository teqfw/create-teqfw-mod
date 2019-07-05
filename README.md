# create-teqfw-mod

Template to create modules for TeqFW based web application using npm.

**ATTN**: *It is my own test package, not public ready. Please, use it but don't be offended.*



# Files structure for TeqFW module

TeqFW module has the following typical structure:

- **./doc/**: documentation files;
- **./pub/**: client side startup files;
- **./src/**: module sources;
- **./test/**: test scripts for `./src/`;
- **./index.js**: module's main script;
- **./LICENSE**: GPL-3.0 or your own choice;
- **./package.json**: `npm` module descriptor;
- **./README.md**: module overview;



# Create new module 

```
$ npm init teqfw-mod my-mod
$ cd my-mod
```  
  
  
    
# Place module sources to github

Create empty github repository `https://github.com/user/my-mod` (w/o LICENSE, README, .gitignore, etc).

```
$ cd my-mod
$ git init
$ git add .
$ git commit -m "Init TeqFW module."
$ git remote add origin git@github.com:user/my-mod.git
$ git push -u origin master
```