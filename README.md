# IONIC BARCODE SCANNER

### Project base for barcode scanning.

Getting Started
----------------------

Cloning the project
##### HTTPS
```
git clone https://github.com/IgorMing/ionic-BarcodeScanner.git
```
##### or SSH
```
git clone git@github.com:IgorMing/ionic-BarcodeScanner.git
```

After cloning the project
> Check if you have [bower](https://bower.io/#install-bower) installed.

```
bower install
```
*(This command  will install all project dependencies.)*

> If it shows 'Permission Denied' in the next steps, run the command: `sudo su`

Add the platforms you want (android, ios, blackberry)
```
ionic platform add [platform]
```

Build it!
```
ionic build [platform]
```

Connect some avd device, or play it in your real device

> You can list your disponible connected devices running: `adb devices`

Now, just run it!
```
ionic run [platform]
```

* For more information, visit the official websites [ionic](http://ionicframework.com/) and [cordova](https://cordova.apache.org/)
