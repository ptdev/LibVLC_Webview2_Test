# LibVLC_Webview2_Test

## Problem:

When using LibVLCSharp.WPF along with Webview2, Webview2 can't be used.

We get undefined error on 

`xmlns:wv2="clr-namespace:Microsoft.Web.WebView2.Wpf;assembly=Microsoft.Web.WebView2.Wpf"`

and on the `wv2:webview` control.

## Workarounds

- Removing the LibVLCSharp.WPF package.
- Setting the TargetFramework to `net9.0-windows7.0` instead of `net9.0-windows10.0.22621.0`
