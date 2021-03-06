# DisplayCDKPageData
Gives a link to CDK page in local server context, hydra context, HAR data and data layer. Shows debug parameters as easy to read json objects for given CDK hydra page in one click.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

### To install on chrome
1. Clone this repo to your chosen directory:
```
git clone http://langa@stash.cdk.com/scm/wh/displaycdkpagedata.git
```
2. Open: chrome://extensions
3. Choose: "Load unpacked extensions" (Button near the top left of the browser window)
4. Using the "select extension directory" popup, navigate to the directory with the repo. Then navigate to the "app/chrome" directory within the repo and press "select". DO NOT select froom the root directory or the extension wont work.
5. You should now have a working extension.

### To install on firefox
1. Clone this repo to your chosen directory:
2. Navigate to the app/firefox directory. 
3. Drag and drop the "DisplayCDKPageData.xpi" file into an open firefox tab. 
4. Accept permissions request.
5. You should now have a working extension.

### Be Aware:
This extension is meant to make the internal development process at CDK easier. It will not work on non CDK websites, nor will it work outside CDK network, so you will need to be logged into VPN if you are WFH.

Please make any pull requests or bug reports at my personal repo where bugfix and PR testing will occur before pushing to CDK repo and store: https://github.com/adamglang/DisplayCDKPageData/

