# node-red-contrib-lgtv

[![NPM version](https://badge.fury.io/js/node-red-contrib-lgtv.svg)](http://badge.fury.io/js/node-red-contrib-lgtv)
[![Dependency Status](https://img.shields.io/gemnasium/hobbyquaker/node-red-contrib-lgtv.svg?maxAge=2592000)](https://gemnasium.com/github.com/hobbyquaker/node-red-contrib-lgtv)
[![License][mit-badge]][mit-url]

> Node-RED Nodes to Control LG WebOS Smart TVs


## Known Issues

* After the first successful connect to your TV you have to open the config node and click update again (otherwise the
connection token received from the TV will not be saved and you have to awnser the prompt on your TV again after a
restart of Node-RED)
* The Channel Output Node doesn't work yet.


## Todo

* Fix Known Issues
* More Documentation
* Button and Mouse support (needs a "Specialized Socket")

Pull Requests welcome! :-)


## License

MIT (c) Sebastian Raff

[mit-badge]: https://img.shields.io/badge/License-MIT-blue.svg?style=flat
[mit-url]: LICENSE