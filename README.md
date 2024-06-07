# HW-CSS

This is a simple CSS that we use for our websites.

## Install

```
bower install healthwatch/hw-css --save
```

## Usage

```html
<link rel="stylesheet" href="bower_components/hw-css/css/hw.min.css"> <!-- for WWW -->
<link rel="stylesheet" href="bower_components/hw-css/css/grp.min.css"> <!-- for GRP -->
```

## Sample

See examples directory for samples.

## screenshot

![test](https://github.com/healthwatch/hw-css/blob/master/examples/test.png "Test")

## Contribute

First off, you need to install Ruby and SASS to be able to compile SASS files into CSS using Grunt. Install Ruby from their webite.

https://rubyinstaller.org/

Once Ruby is installed, install SASS gem

```
gem install sass
```
Install all the NPM packages needed to compile the project.

```
npm install
```

Next install Grunt CLI so we can run the grunt and watch the files changed.

```
\> npm install -g grunt
```

## Development

Run grun to listen the the file changes and automatically generate the minified and unminifed CSS into the css directory.

```
\> run-grant.bat
```

All contributions should go to a Pull request to be merged into the master branch. Thanks!
