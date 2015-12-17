# CSDKBase

This repo is the foundation for an Android integration of the Creative SDK as covered in [the Getting Started guide on creativesdk.adobe.com](https://creativesdk.adobe.com/docs/android/#/articles/gettingstarted/index.html).

## How to use

Just follow these steps:

1. [Download the Creative SDK for Android](https://creativesdk.adobe.com/downloads.html)
1. [Register a new app for the Creative SDK](https://creativesdk.adobe.com/myapps.html) (Note your Client ID and Secret. You will need them soon.)
1. `git clone` the repo
1. In your computer's Finder or File Browser, add the `creativesdk-repo` directory to the _top level of your app directory_
1. Add a new Java class called `Keys`
  1. See the section below for the code to put in the `Keys` class
  1. Add your Client ID and Secret to the `Keys` class
1. Sync your Gradle files and run the app 



## The `Keys` class

The content of the keys class should look like this:

```
public class Keys {

    public static final String CSDK_CLIENT_ID = "<YOUR_ID_HERE>";
    public static final String CSDK_CLIENT_SECRET = "<YOU_SECRET_HERE>";

}
```