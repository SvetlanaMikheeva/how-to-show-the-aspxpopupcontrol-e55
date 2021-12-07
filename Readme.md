<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128565301/13.1.4%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E55)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
# Popup Control for ASP.NET Web Forms - How to show the Popup Control
<!-- run online -->
**[[Run Online]](https://codecentral.devexpress.com/e55/)**
<!-- run online end -->
This example demonstrates how to show the Popup Control.

## Overview

Handle a client-side or server-side event and call one of the following methods to show the [ASPxPopupControl](https://docs.devexpress.com/AspNet/DevExpress.Web.ASPxPopupControl)'s pop-up window:

**[Show](https://docs.devexpress.com/AspNet/js-ASPxClientPopupControlBase.Show)** or **[ShowWindow](https://docs.devexpress.com/AspNet/js-ASPxClientPopupControl.ShowWindow(window))**  
Displays the default or specific pop-up window at a popup element with the specified index. Use the [PopupHorizontalAlign](https://docs.devexpress.com/AspNet/DevExpress.Web.ASPxPopupControl.PopupHorizontalAlign), [PopupHorizontalOffset](https://docs.devexpress.com/AspNet/DevExpress.Web.ASPxPopupControl.PopupHorizontalOffset), [PopupVerticalAlign](https://docs.devexpress.com/AspNet/DevExpress.Web.ASPxPopupControl.PopupVerticalAlign), and [PopupVerticalOffset](https://docs.devexpress.com/AspNet/DevExpress.Web.ASPxPopupControl.PopupVerticalAlign) properties to specify the window's position relative to the element.

**[ShowAtElement](https://docs.devexpress.com/AspNet/js-ASPxClientPopupControlBase.ShowAtElement(htmlElement))** or **[ShowWindowAtElement](https://docs.devexpress.com/AspNet/js-ASPxClientPopupControl.ShowWindowAtElement(window-htmlElement))**  
Displays the default or specific pop-up window over the specified HTML element.

**[ShowAtElementByID](https://docs.devexpress.com/AspNet/js-ASPxClientPopupControlBase.ShowAtElementByID(id))** or **[ShowWindowAtElementByID](https://docs.devexpress.com/AspNet/js-ASPxClientPopupControl.ShowWindowAtElementByID(window-id))**  
Displays the default or specific pop-up window over an HTML element with the specified identifier.

**[ShowAtPos](https://docs.devexpress.com/AspNet/js-ASPxClientPopupControlBase.ShowAtPos(x-y))** or **[ShowWindowAtPos](https://docs.devexpress.com/AspNet/js-ASPxClientPopupControl.ShowWindowAtPos(window-x-y))**  
Displays the default or specific pop-up window at the specified position.

<!-- default file list -->

## Files to look at

* [Default.aspx](./CS/WebSite/Default.aspx) (VB: [Default.aspx](./VB/WebSite/Default.aspx))
* [Default.aspx.cs](./CS/WebSite/Default.aspx.cs) (VB: [Default.aspx.vb](./VB/WebSite/Default.aspx.vb))

<!-- default file list end -->

## Documentation

- [How to: Show the Default Window](https://docs.devexpress.com/AspNet/115457/components/docking-and-popups/popup-control/popup-windows/default-window)
- [How to: Show and Hide Windows](https://docs.devexpress.com/AspNet/115458/components/docking-and-popups/popup-control/popup-windows/manipulating-windows)

## More Examples

- [Popup Control for ASP.NET Web Forms - How to show and hide a pop-up window on the server side](https://supportcenter.devexpress.com/internal/ticket/details/E499)
- [Popup Control for ASP.NET Web Forms - How to add buttons to a popup window](https://www.devexpress.com/Support/Center/p/E493)
