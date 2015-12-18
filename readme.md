# CSDKBase

This repo is the foundation for an Android integration of the Creative SDK as covered in [the Getting Started guide on creativesdk.adobe.com](https://creativesdk.adobe.com/docs/android/#/articles/gettingstarted/index.html).

## How to use

Just follow these steps:

1. [Download the Creative SDK for Android](https://creativesdk.adobe.com/downloads.html)
1. [Register a new app for the Creative SDK](https://creativesdk.adobe.com/myapps.html) (Note your Client ID and Secret. You will need them soon.)
1. `git clone` the repo
1. In your computer's Finder or File Browser, add the `creativesdk-repo` directory to the _top level of your app directory_  
    ![](https://github.com/ashryanbeats/CSDKBase/blob/screenshots/screenshots/add-creativesdk-repo.png)

1. Add a new Java class called `Keys` with this code:  

	```
	public class Keys {

	    public static final String CSDK_CLIENT_ID = "<YOUR_ID_HERE>";
	    public static final String CSDK_CLIENT_SECRET = "<YOU_SECRET_HERE>";

	}
	```

    1. Add your Client ID and Secret to the `Keys` class
    1. This class is gitignored so you can avoid exposing your keys in GitHub
1. Sync your Gradle files and run the app 


