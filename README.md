# openwhisk-serverless

## Running

1. Access RHOAR with Serverless mission:

1. Select the *Serverless* mission and the *Openwhisk* booster

1. Follow the dialog

1. Unzip the archive

1. If you want to setup Openwhisk architecture to Openshift:
  * `./openwhisk-setup.sh`

1. Make your changes and deploy the function:
  * `./openwhisk-deploy <action_name> <file_name>`

1. The app is available in Openwhisk, to test the functionality:
  * `./openwhisk-test <action_name>`

