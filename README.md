# IBM SDK Manager docker base image for Linux or Mac

https://developer.ibm.com/customer-engagement/tutorials/getting-started-sdk-manager-mac-os-x-linux/

# Usage

- Run SDK Manager with 'cd /var/www/html/ibm_sdk_tools/sdkmanager && ./minstrument.sh'
- Login with your [IBMID](https://idaas.iam.ibm.com/). 
- SDK update command: `update -sdk cxa` or `update -sdk tealeaf` or `update -sdk da`
- Downloaded SDK are located in folder /var/www/html/ibm_sdk_tools/sdkmanager/ibm-sdk/node_modules.
- Or view it in browser [http://dockerhost:dockerport/ibm_sdk_tools/sdkmanager/ibm-sdk/node_modules](http://dockerhost:dockerport/ibm_sdk_tools/sdkmanager/ibm-sdk/node_modules).