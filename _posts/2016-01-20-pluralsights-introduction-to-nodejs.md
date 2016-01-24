---
layout: post
title: "Pluralsight's Introduction to Node.js"
date: 2016-01-20
---

Node.js = libuv /* evented IO library */ + V8 /* JavaScript engine */ + custom code

Multiple Node.js can be managed by `nvm`

Cloud9 IDE is sweet for editing project in the web.

Node convention `doSomething(input, callback)`, then callback receives `(error, results)`.

### Modules

Modules are loaded with `var os = require('os');`

`require('./blah');` for local files.

Module exports are done with `module.exports.blah = blah;`.

`npm` is package manager.

`npm install -g` global installation of a module.

### Events and streams

`EventEmitter`: `emitter.emit(event, [args])` -> `emitter.on(event, listener)`.

Streams are extensions of EventEmitter.

Stream is instance of ReadableStream, WritableStream or both.

ReadableStream can be piped to WritableStream.

### Work with local system

Node is ok to work with external processes.

`fs.watch()`.

There are sync versions for filesystem operations.

Buffers are to work with binary data.

### Web

Socket.IO is a sweet thing to get data stream from server.

### Testing

Mocha is similar to rspec.

### Scaling

`exec()` and `spawn()` are to start external processes.

`fork()` is to spawn a child module, then communication is message-based.

Something about node cluster module, seemed to be able to listen to the same port.

