---
layout: fluid/cli_docs_base
category: cli
id: cli-cordova-emulate
page_name: ionic cordova emulate
command_name: ionic cordova emulate
title: ionic cordova emulate - Ionic CLI Documentation
header_sub_title: Ionic CLI
---


{% comment %}
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
DO NOT MODIFY THIS FILE DIRECTLY -- IT IS GENERATED FROM THE CLI REPO
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
{% endcomment %}


# `$ ionic cordova emulate`

Emulate an Ionic project on a simulator or emulator
## Synopsis

```bash
$ ionic cordova emulate [<platform>]
```
  
## Details

Like running `cordova emulate` directly, but also watches for changes in web assets and provides live-reload functionality with the `--livereload` option.

For Android and iOS, you can setup Remote Debugging on your emulator with browser development tools: **[https://docs.ionic.io/tools/developer/#remote-debugging](https://docs.ionic.io/tools/developer/#remote-debugging)**

Just like with `ionic cordova build`, you can pass additional options to the Cordova CLI using the `--` separator.


Input | Description
----- | ----------
`platform` | The platform to emulate (`android`, `ios`)


Option | Description
------ | ----------
`--list` | List all available Cordova targets
`--livereload`, `-l` | Spin up server to live-reload www files
`--consolelogs`, `-c` | Print out console logs to terminal
`--address` | Use specific address for the dev server
`--port`, `-p` | Use specific port for HTTP
`--livereload-port`, `-r` | Use specific port for live-reload
`--dev-logger-port` | Use specific port for dev server communication
`--prod` | Mark as a production build
`--aot` | Perform ahead-of-time compilation for this build
`--minifyjs` | Minify JS for this build
`--minifycss` | Minify CSS for this build
`--optimizejs` | Perform JS optimizations for this build
`--debug` | Mark as a debug build
`--release` | Mark as a release build
`--device` | Deploy Cordova build to a device
`--emulator` | Deploy Cordova build to an emulator
`--target` | Deploy Cordova build to a device (use `--list` to see all)
`--buildConfig` | Use the specified Cordova build configuration

## Examples

```bash
$ ionic cordova emulate 
$ ionic cordova emulate ios
$ ionic cordova emulate ios -lc
$ ionic cordova emulate android -lc --address=localhost
$ ionic cordova emulate android -lc -- -d
```
