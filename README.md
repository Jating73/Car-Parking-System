# Car-Parking-System
It helps in management of parking system. It helps the user to know whether there is any empty slot available or not.
It helps to find out which car is parked in which slot just by providing either car number or slot number.

## Requirements

For development, you will only need Node.js installed in your environement.

### Node
- #### Node installation on Windows
  Just go on [official Node.js website](https://nodejs.org/) and download the installer.
  
- #### Node installation on Ubuntu
  You can install nodejs and npm easily with apt install, just run the following commands.
      $ sudo apt install nodejs
      $ sudo apt install npm

- #### Other Operating Systems
  You can find more information about the installation on the [official Node.js website](https://nodejs.org/) and the [official NPM website](https://npmjs.org/).

If the installation was successful, you should be able to run the following command.

    $ node --version
    v8.11.3

    $ npm --version
    6.1.0

## Changes required before running the file
- ### Put the slot size according to your prefrence instead of your_slot_size_here in .env_sample
- ### Need to rename the .env_sameple to .env

## Note-
  It will only make 10 request in 10 seconds to server. So if you want to configure it you can.

## Running the project

    $ npm start
