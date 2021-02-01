<h1>Webserver</h1>
<h3>A NodeJS webserver with ReactJS and Bootstrap for controlling your sand table remotely</h3>

Designed by Ravi Dudhagra ([@rdudhagra](https://github.com/rdudhagra))

- [Installation Instructions](#installation-instructions)
  - [Prerequisites](#prerequisites)
  - [Building](#building)
  - [Running the webserver](#running-the-webserver)
  - [Running the webserver (development)](#running-the-webserver-development)
- [Downloading tracks](#downloading-tracks)
- [Screenshots](#screenshots)

# Installation Instructions

## Prerequisites
This project was developed with the following:
- `NodeJS v13.11.0`
- `NPM v6.14.5`

## Building
1. Download this folder to the directory of choice
2. In the same directory as `package.json`, run
   ```bash
   npm install # installs packages and dependencies
   ```
3. In the file `.env`, edit the parameters to match your setup

## Running the webserver
1. In the same directory as `package.json`, run
   ```bash
   npm run prod # compiles client and server files in production mode, and runs server
   ```
2. Visit `http://[ip address of machine]` in a web browser (runs on port 80)

If you want to run this webserver through systemd, the script `start.sh` should assist in this, assuming you're using NVM to manage Node versions.

## Running the webserver (development)
1. In the same directory as `package.json`, run
   ```bash
   npm start # compiles client files, compiles server files in memory, starts server with nodemon (restarts on file changes)
   ```
2. Visit `http://[ip address of machine]:3000` in a web browser (runs on port 3000)

# Downloading tracks
Any `.thr` file compatible with the Sisyphus table will work with this software. A collection of publicly available tracks can be found at the following links:
- https://github.com/Dithermaster/sisyphus
- https://github.com/SlightlyLoony/JSisyphus
- https://github.com/heropup/sisyphus
- http://thejuggler.net/sisyphus/
- https://github.com/ddkengr/Sisyphus-threads

# Screenshots

| | | |
| :---: | :---: | :---: |
| <img src="images/2020-09-08-16-35-02.png"> | <img src="images/2020-09-08-16-37-38.png"> | <img src="images/2020-09-08-16-35-49.png"> |
| <img src="images/2020-09-08-16-36-49.png"> | <img src="images/2020-09-08-16-36-36.png"> | <img src="images/2020-09-08-16-37-10.png"> |
| <img src="images/2020-09-08-16-37-21.png"> | <img src="images/2020-09-08-16-37-53.png"> | <img src="images/2020-09-08-16-38-06.png"> |