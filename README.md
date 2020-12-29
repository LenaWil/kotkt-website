# kotkt-website
www.kotkt.nl

## Introduction

Welcome to the github repo of the website of the Knights of the Kitchen table. 
If you find any issues on the website, feel free to fix them and send a pull request, or open an issue right [here](https://github.com/esrg-knights/kotkt-website/issues)!

If you want to contribute to the website code, please make sure you are proficient with Git, [HTML/CSS](http://www.w3schools.com/css/) and/or the Hugo static-site generator.

## Legacy Code
The old code (pure HTML and CSS) is available under the `legacy/` folder.

## Hugo
The new site utilises Hugo to make everything more maintainable. It can be found under the `kotkt.nl/` folder.

Documentation: https://gohugo.io/

To run:
- `hugo server -D`

To build:
- `hugo`

In Windows, the relevant Execution Policy needs to be set to be able to run Hugo. In Powershell, this can be done using `Set-ExecutionPolicy RemoteSigned -scope Process`. The former Execution Policy is restored once this Powershell instance is closed.

NB: Make sure you are in the `kotkt.nl/` folder when attempting to run the `hugo` commands.
