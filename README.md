# grunt-contrib-csslint [![Build Status](https://secure.travis-ci.org/gruntjs/grunt-contrib-csslint.png?branch=master)](http://travis-ci.org/gruntjs/grunt-contrib-csslint)

> Lint CSS files.



## Getting Started
This plugin requires Grunt `~0.4.0`

If you haven't used [Grunt](http://gruntjs.com/) before, be sure to check out the [Getting Started](http://gruntjs.com/getting-started) guide, as it explains how to create a [Gruntfile](http://gruntjs.com/sample-gruntfile) as well as install and use Grunt plugins. Once you're familiar with that process, you may install this plugin with this command:

```shell
npm install grunt-contrib-csslint --save-dev
```

Once the plugin has been installed, it may be enabled inside your Gruntfile with this line of JavaScript:

```js
grunt.loadNpmTasks('grunt-contrib-csslint');
```

*This plugin was designed to work with Grunt 0.4.x. If you're still using grunt v0.3.x it's strongly recommended that [you upgrade](http://gruntjs.com/upgrading-from-0.3-to-0.4), but in case you can't please use [v0.3.2](https://github.com/gruntjs/grunt-contrib-cssmin/tree/grunt-0.3-stable).*



## Csslint task
_Run this task with the `grunt csslint` command._

Task targets, files and options may be specified according to the grunt [Configuring tasks](http://gruntjs.com/configuring-tasks) guide.

Files are compressed with [clean-css](https://github.com/GoalSmashers/clean-css).

### Usage Examples

```js
cssmin: {
  compress: {
    files: {
      "path/to/output.css": ["path/to/input_one.css", "path/to/input_two.css"]
    }
  }
}
```


## Release History

 * 2013-02-17   v0.4.1   Update clean-css dependency to ~0.10.0
 * 2013-02-15   v0.4.0   First official release for Grunt 0.4.0.
 * 2013-01-23   v0.4.0rc7   Updating grunt/gruntplugin dependencies to rc7. Changing in-development grunt/gruntplugin dependency versions from tilde version ranges to specific versions.
 * 2013-01-09   v0.4.0rc5   Updating to work with grunt v0.4.0rc5. Switching to this.files api.
 * 2012-11-01   v0.3.2   Update clean-css dep.
 * 2012-10-12   v0.3.1   Rename grunt-contrib-lib dep to grunt-lib-contrib.
 * 2012-09-23   v0.3.0   Options no longer accepted from global config key.
 * 2012-09-10   v0.2.0   Refactored from grunt-contrib into individual repo.

---

Task submitted by [Tim Branyen](http://goingslowly.com/)

*This file was generated on Sun Mar 03 2013 18:11:41.*