# history

## 0.2.26

* `CHANGED` support require svg
* `CHANGED` add es3ify-loader 

## 0.2.25

* `CHANGED` build will parse jsx file

## 0.2.24

* `CHANGED` change webpack resolve extension, add '.jsx .ts'

## 0.2.23

* `CHANGED` remove definePlugin in chrome & saucelabs task

## 0.2.22

* `CHANGED` add sourcemap and happypack in chrome task

## 0.2.21

* `CHANGED` stop screenshot in saucelabs task

## 0.2.20

* `FIX` remove unist-util-select

## 0.2.19

* `FIX` remove remark

## 0.2.18

* `NEW` add new task `update` & `tnpm-update`

## 0.2.17

* `CHANGED` detect sauce.json locally

## 0.2.12

* `CHANGED` add concurrency(3) in saucelab test config

## 0.2.11

* `CHANGED` only use definePlugin in saucelabs

## 0.2.10

* `FIX` fix env defination bug

## 0.2.9

* `NEW` add es3 plugin 

## 0.2.8

* `CHANGED` make env production
* `NEW` add gulp task browsers

## 0.2.7

* `CHANGED` open sauce connent in karma & set username/accesskey

## 0.2.6

* `CHANGED` not open sauce connent in karma

## 0.2.5

* `FIX` add missing dependency
* `CHANGED` open webpack cache

## 0.2.4

* `CHANGED` remove happyPack & process bar (performance ?)
* `CHANGED` add tnpm-dep task

## 0.2.3

* `NEW` add autoprefix less plugin

## 0.2.2

* `CHANGED` Do not parse uxcore modules in babel-loader
* `CHANGED` sourceMap use SourceMapDevToolPlugin
* `NEW` add happyPack
* `NEW` open default browser when server start
* `NEW` add process bar of webpack building
* `NEW` add portInUse detect
* `NEW` show true ip in console

## 0.2.1

* `FIX` fix publish bug
* `FIX` auto detect git branch & npm source

## 0.2

* `CHANGED` babel-loader use `cacheDirectory`
* `CHANGED` webpack sourceMap use `cheap-module-eval-source-map`
* `CHANGED` babel-loader will not parse uxcore