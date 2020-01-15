# setup-guide


## Services

The Registration page service
https://github.com/rapid-sensemaking-framework/rsf-http-register

The key noflo runtime environment
https://github.com/rapid-sensemaking-framework/noflo-rapid-sensemaking-server

The telegram bot service:
https://github.com/rapid-sensemaking-framework/rsf-telegram-bot

The twilio/texting bot service:
https://github.com/rapid-sensemaking-framework/rsf-twilio-bot

## Steps

a first step would be to git clone … those 4 repos

into a folder on the server

The general pattern for these things is this…
they reference a PORT environment variable that will need to be set to the correct values of the open ports

they have an `npm start` command which can be run from the root of each folder which boots the service

some of them also expect other environment variables to be set, which I will help with

some are already documented in the repos, some aren’t, so it will be a chance for me to improve the documentation as well.