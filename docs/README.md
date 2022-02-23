# Store Maintenance Theme

This theme provides a basic layout for the /maintenance page from the app store-maintenance. It is a non-mandatory addition that allows quick development of a good looking maintenance page. You can however define this page in your native theme or via the CMS Pages in the Admin. 

Installing this theme alone will not bring you any benefits. Only make use of this, if you intend to use the [store maintenance app](https://github.com/vtex-apps/store-maintenance).

## How to use this

### Step 1: clone this app

Clone the repository in order to get started working

```shell
git clone git@github.com:vtex-apps/store-maintenance-theme.git
```


### Step 2: make it yours!
Rename the app and the vendor in the manifest. Make it yours.
```json
{
  "vendor": "mycompany",
  "name": "my-maintenance-theme",
}
```
### Step 3 - build your block structure

in the file store/blocks.json you find a working draft of a very basic maintenance page. Add blocks and content as needed. I recommend to add at least your logo to the header. 


### Step 4 -  Test the theme in a dev workspace.

Then time has come to upload all the changes you made in your local files to the platform. For that, use the `vtex link` command. 

If the process runs without any errors, the following message will be displayed: `App linked successfully`. Then, run the `vtex browse` command to open a browser window having your linked store in it.

This will enable you to see the applied changes in real time, through the account and workspace in which you are working.

### Step 5 - Release the Kraken!

Once your are happy, you can deploy and install the theme  towards your production workspaces.
