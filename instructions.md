### Using the CLI
npm install foundation-cli --global

### Installation
Run `npm install` to install all required modules.

### Install Third Party Plugins
Run `npm install --save package-name` to install the plugins.

### Import custom javascript libraries to the project
Add `import packagename from 'package_folder_name_node_modules';` to the src/js/app.js

### Paths to Sass libraries, which can then be loaded with @import
Add `- "node_modules/package_folder/sass_folder_name"`in the ./config.yml

### Import all SASS libraries for third party libraries installed by NPM/YARN
Add `@import 'node_modules/package_folder/sass_folder_name/sass_file.scss';` to the bottom of src/scss/app.scss

### Import all CSS libraries for third party libraries installed by NPM/YARN
Add `@import 'node_modules/package_folder/styles(without .css extensions)';` without .css extension to the bottom of src/scss/app.scss

### Create custom SASS file and Partials
Create `_custom_sass_file.scss` and place it in src/scss/ folder
Add `@import '_custom_sass_file';`to the src/scss/app.scss

### Run / Build
Run `foundation watch` or `npm start` to run Gulp.
To create compressed, production-ready assets, run `npm run build` or 'gulp --production'.


### Git Commands
git add .

git commit -m 'message'

git push -u origin master

git fetch origin

git reset --hard origin/master 

## Git Desktop Process

### Set-up

Download and install the GitHub Desktop App here:
https://desktop.github.com/


Go to File > Clone Repository

### For each new project

Select the foundation-ui-workflow repository


