# FluentMobileElement.TagName Property 
 

Gets the fluent element's tag name

**Namespace:**&nbsp;<a href="#/MAQS_4/Appium_AUTOGENERATED/Magenic-MaqsFramework-BaseAppiumTest_Namespace">Magenic.MaqsFramework.BaseAppiumTest</a><br />**Assembly:**&nbsp;Magenic.MaqsFramework.BaseAppiumTest (in Magenic.MaqsFramework.BaseAppiumTest.dll) Version: 4.0.4.0 (4.0.4)

## Syntax

**C#**<br />
``` C#
public string TagName { get; }
```


#### Property Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a>

## Examples

**C#**<br />
``` C#
[TestMethod]
[TestCategory(TestCategories.Selenium)]
public void FluentElementTagName()
{
    Assert.AreEqual("input", this.InputBox.TagName);
}
```


## See Also


#### Reference
<a href="#/MAQS_4/Appium_AUTOGENERATED/FluentMobileElement_Class">FluentMobileElement Class</a><br /><a href="#/MAQS_4/Appium_AUTOGENERATED/Magenic-MaqsFramework-BaseAppiumTest_Namespace">Magenic.MaqsFramework.BaseAppiumTest Namespace</a><br />