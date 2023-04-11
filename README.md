# PureScript

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

This repository contains a collection of PureScript programs and scripts.

## Table of Contents
- [What is PureScript](#what-is-purescript)   
- [Installation](#installation)
  - [Installing PureScript](#installing-purescript)    
    - [Windows](#windows)
    - [Linux](#linux)
    - [macOS](#macOS)  
  - [Installing Repository](#installing-repository)  
- [Usage](#usage)
  - [Running PureScript Programs](#running-purescript-programs)
  - [Using Spago](#using-spago)
- [Contributing](#contributing)
- [License](#license)

## What is PureScript

PureScript is a strongly-typed functional programming language that compiles to JavaScript. It is inspired by Haskell and provides a simple and expressive syntax for writing functional code. PureScript's static type system helps catch many common programming errors at compile-time, making it a powerful language for building robust and maintainable applications.

PureScript is commonly used for frontend web development, where it can be used to build user interfaces with libraries like React or as a replacement for JavaScript in building server-side applications with Node.js. It is also used in other domains like data science, machine learning, and game development.

## Installation

### Installing PureScript

These are the general steps to install PureScript on different platforms. However, the exact steps may vary depending on the specific operating system and version you are using. It's always a good idea to refer to the official documentation for your platform to get more detailed installation instructions.

#### Windows

1. Download and install Node.js from the official Node.js website.
2. Open a command prompt or PowerShell window and run the following command to install PureScript globally:

```
npm install -g purescript
```

3. Once the installation is complete, you can use any text editor or IDE (Integrated Development Environment) to write and compile PureScript code.

#### Linux

1. Install Node.js using the package manager for your Linux distribution. For example, on Ubuntu, you can use the following command:

```
sudo apt-get install nodejs
```

2. Install PureScript globally using npm, the Node.js package manager:

```
npm install -g purescript
```

3. Once PureScript is installed, you can use any text editor or IDE to write and compile PureScript code.

#### macOS

1. Install Node.js using a package manager like Homebrew. Open a terminal and run the following command:

```
brew install node
```

2. Install PureScript globally using npm, the Node.js package manager:

```
npm install -g purescript
```

3. Once PureScript is installed, you can use any text editor or IDE to write and compile PureScript code.

### Installing Repository

You can download individual files, copy & paste code, or clone the repository

```
git clone https://github.com/YourUsername/PureScript.git
```
      
## Usage

### Running PureScript Programs

1. Clone the repository. If you have written your own programs, save the program with a `.purs` file extension.
2. Open a terminal or command prompt and navigate to the directory where the PureScript program is saved.
3. Run the following command to compile and run the PureScript program:

```
purs compile path/to/program.purs -o output
```
