# WatchIt

## Overview
"WatchIt" is a simple CLI tool developed in Go, designed to monitor filesystem events on Linux. Utilizing the `inotify` subsystem, it allows users to watch for changes in specified files or directories, such as modifications or deletions, and performs actions based on these triggers. This tool is particularly useful for developers who need to automate tasks based on file system events, such as auto-compiling code, running tests, or syncing files.

## Installation

Before installing "WatchIt," ensure you have Go installed on your system. You can download and install Go from [the official Go website](https://golang.org/dl/).

### Setting Up Your Go Environment
Create a new directory for your project and initialize a Go module:

```bash
mkdir watchit && cd watchit
go mod init watchit
