
To contribute, please ensure that you have stable Node.js and npm installed.

Test if Gulp CLI is installed by running gulp --version. If the command isn't found, run npm install -g gulp. For more information about installing Gulp, see the Gulp's Getting Started.

If gulp is installed, follow the steps below.

Fork and clone the repo.
Run gulp, this will open Filmstock on your default browser
Now you can code, code and code!
Submit a pull request


run this: npm install --global gulp-cli


Below are the dependencies needed to run Filmstock:

gulp = require('gulp'),
    concat = require('gulp-concat'),
    uglify = require('gulp-uglify'),
    rename = require('gulp-rename'),
    sass = require('gulp-ruby-sass'),
    autoprefixer = require('gulp-autoprefixer'),
    browserSync = require('browser-sync').create();
