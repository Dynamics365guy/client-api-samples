# Xrm.Navigation.OpenUrl

Opens all the Urls including file Urls. It has the following values:

|Parameters|Description|Required|
|---------|-----------|---------|
|url| The url which you want to open.|Yes|
|OpenUrlOptions|It has the following parameters:<br/> - ***height***: Height of the window when the url is opened.<br/> - ***width***: Width of the window when the url is opened.|Optional|

## Example

```JavaScript
function OpenUrl()
{
	var url = "http://google.com";
  var openUrlOptions = {height: 400,width: 800, openInNewWindow:true
    };

    Xrm.Navigation.openUrl(url, openUrlOptions);
}
```
