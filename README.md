# jsonpatch
[![GitHub Action](https://img.shields.io/badge/GitHub-Action-blue)](https://github.com/features/actions)
[![Documentation](https://img.shields.io/badge/godoc-reference-5272B4.svg)](https://pkg.go.dev/github.com/snorwin/jsonpatch)
[![Test](https://img.shields.io/github/workflow/status/snorwin/jsonpatch/Test?label=tests&logo=github)](https://github.com/snorwin/jsonpatch/actions)
[![Go Report Card](https://goreportcard.com/badge/github.com/snorwin/jsonpatch)](https://goreportcard.com/report/github.com/snorwin/jsonpatch)
[![Coverage Status](https://coveralls.io/repos/github/snorwin/jsonpatch/badge.svg?branch=main)](https://coveralls.io/github/snorwin/jsonpatch?branch=main)
[![Releases](https://img.shields.io/github/v/release/snorwin/jsonpatch)](https://github.com/snorwin/jsonpatch/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

`jsonpatch` is a Go library to create JSON patches ([RFC6902](http://tools.ietf.org/html/rfc6902)) directly from arbitrary Go objects and facilitates the implementation of sophisticated custom (e.g. filtered, validated) patch creation.
