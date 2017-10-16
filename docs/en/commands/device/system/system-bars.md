# Get System Bars

Retrieve visibility and bounds information of the status and navigation bars
## Example Usage

```java
// Java
Map<String, String> systemBars = driver.getSystemBars();

```

```python
# Not supported
```

```javascript
// Not supported


// Not supported
```

```ruby
# Ruby
@driver.get_system_bars();

```

```php
# PHP
// TODO

```

```csharp
// C#
// TODO

```



## Support

### Appium Server

|Platform|Driver|Platform Versions|Appium Version|Driver Version|
|--------|----------------|------|--------------|--------------|
| iOS | [XCUITest](/docs/en/drivers/ios-xcuitest.md) | None | None | None |
|  | [UIAutomation](/docs/en/drivers/ios-uiautomation.md) | None | None | None |
| Android | [UiAutomator2](/docs/en/drivers/android-uiautomator2.md) | ?+ | 1.6.0+ | All |
|  | [UiAutomator](/docs/en/drivers/android-uiautomator.md) | 4.2+ | All | All |
| Mac | [Mac](/docs/en/drivers/mac.md) | None | None | None |
| Windows | [Windows](/docs/en/drivers/windows.md) | None | None | None |

### Appium Clients

|Language|Support|Documentation|
|--------|-------|-------------|
|[Java](https://github.com/appium/java-client/releases/latest)| All |  [appium.github.io](http://appium.github.io/java-client/io/appium/java_client/android/HasDeviceDetails.html#getSystemBars--)  |
|[Python](https://github.com/appium/python-client/releases/latest)| None |  |
|[Javascript (WebdriverIO)](http://webdriver.io/index.html)| None |  |
|[Javascript (WD)](https://github.com/admc/wd/releases/latest)| None |  |
|[Ruby](https://github.com/appium/ruby_lib/releases/latest)| All |  [www.rubydoc.info](http://www.rubydoc.info/github/appium/ruby_lib/Appium/Core/Device:get_system_bars)  |
|[PHP](https://github.com/appium/php-client/releases/latest)| None |  [github.com](https://github.com/appium/php-client/)  |
|[C#](https://github.com/appium/appium-dotnet-driver/releases/latest)| None |  [github.com](https://github.com/appium/appium-dotnet-driver/)  |

## HTTP API Specifications

### Endpoint

`GET /session/:session_id/appium/device/system_bars`

### URL Parameters

|name|description|
|----|-----------|
|session_id|ID of the session to route the command to|

### JSON Parameters

None

### Response

Information about visibility and bounds of status and navigation bar (`array<object>`)

## See Also

* [JSONWP Specification](https://github.com/appium/appium-base-driver/blob/master/lib/mjsonwp/routes.js#L418)