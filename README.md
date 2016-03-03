# openhab-seleniumjs
Right now, you are able to pull up a demo of the OpenHab UI through selenium only by running a shell script.
## Requirements
1. Please have NodeJS installed
2. Please follow the instructions here to make sure your system can run with Selenium: https://code.google.com/p/selenium/wiki/WebDriverJs

## To Run Tests on OpenHab Locally
1. Clone or download the ZIP of the repository
2. cd openhab-seleniumjs
3. ./testdriver.sh

## To Run Tests on My Raspberry Pi in Same Local Network
1. Clone or download ZIP of the respository
2. Make sure you have OpenHab 2 Offline Snapshot downloaded and unzipped from here https://openhab.ci.cloudbees.com/job/openHAB-Distribution/
2. cd openhav-seleniumjs/on-device-tests
3. Follow SSH steps here https://www.raspberrypi.org/documentation/remote-access/ssh/passwordless.md to add your key
4. ./testdriver.sh
