# Vapor_Intro

>This is the documentation for Vapor, a Web Framework for Swift that works on macOS and Ubuntu, and all of the packages that Vapor offers.

>Vapor is the most used web framework for Swift. It provides a beautifully expressive and easy to use foundation for your next website or API.

# Started

## Environmental settings

* Xcode
* Swift
* HomeBrew - [HomeBrew official link](https://brew.sh)
* Vapor

**How to install on macOS by [official docs link](https://docs.vapor.codes/2.0/getting-started/install-on-macos/)**

- - -

## First local host api

**ToolBox or templates by Command-line interface**

1. vapor new Hello --template=api
2. vapor build or vapor build --release
3. vapor run serve

**Make new project using SwiftPM**

Reference: [Manual Quickstart](https://docs.vapor.codes/2.0/getting-started/manual/)

### Test on localhost

Paste on browser: http://localhost:8080/hello

Response: "Hello world"

- - -

Deloy on Nginx: https://docs.vapor.codes/2.0/deploy/nginx/

## Run on Xcode

Generate xcode project - vapor xcode
**Tip: If you'd like to automatically open the Xcode project, use vapor xcode -y**

Reference: [Xcode](https://docs.vapor.codes/2.0/getting-started/xcode/)

# Vapor

## Folder structure

* Models
> The Models folder is a recommendation of where you can put your database and other models.

* Controllers
> The Controllers folder is a recommendation of where you can put your route controllers.

* Views
> The Views folder in Resources is where Vapor will look when you render views.
