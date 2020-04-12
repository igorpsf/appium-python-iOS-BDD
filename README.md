### Install packages:
1. Selenium
2. Appium-Python-Client
3. Behave

### iOS (Real device) | Need to change all capabilities
desired_capabilities = {

    "platformName": "iOS",
    "platformVersion": "13.4",
    "deviceName": "iPhone Xs Max",
    "automationName": "XCUITest",
    "app": "/Users/igor/Desktop/Appium/UICatalog.app",
    "xcodeOrgId": "***",
    "xcodeSigningId":"iPhone Developer",
    "udid": "***",
    "updateWDABundleId": "***",

}

driver = webdriver.Remote('http://127.0.0.1:4723/wd/hub', desired_capabilities=desired_capabilities)