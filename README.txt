Introduction
-----------
This codebase is starter theme code for Drupal 8, by the team at DevCollab.


Setting Up Gulp 
--------
Rename all instances of the theme's machine name devcollab_starter in file names and in files themselves with theme_name. 
You can do a search/replace on the theme folder in order to do this. 
Our usual convention for the theme's machine name is the org abbreviation and the year the site's slated to be launched, so for example org2019.


Setting Up Gulp 
--------

Steps detailed here: https://css-tricks.com/gulp-for-beginners/

  1. Initialize Node Package Manager - npm init
  This will generate a package-lock.json file, which *should* be committed in Git.

  2. If you have Gulp installed globally (see CSS Tricks for instructions), then save it locally to this project with: 
  npm install gulp --save-dev

  3. Type 
  npm i 
  to have npm install the dependencies for the project per package.json. You should be ready to compile now!


Gulp Tasks
--------

gulp sass - compiles sass into CSS

gulp clean:css - deletes compiled CSS

gulp watch - watches sass directories for changes and recompiles whenever you save a change
