CSSParse.net
============

Parses CSS strings into Unity3D `Color` objects.

So for example:

    using CSSParse

    Color c1 = Style.ParseCSSColor("red");
    Color c2 = Style.ParseCSSColor("lightblue");
    Color c3 = Style.ParseCSSColor("rgb(255,128,37)");
    Color c4 = Style.ParseCSSColor("rgba(128, 192, 168, 0.5)");
    Color c5 = Style.ParseCSSColor("#83F");
    Color c6 = Style.ParseCSSColor("#05BFA4");

Or in UnityScript:

    var c1 : Color = CSSParse.Style.ParseCSSColor("red");
    var c2 : Color = CSSParse.Style.ParseCSSColor("lightblue");
    var c3 : Color = CSSParse.Style.ParseCSSColor("rgb(255,128,37)");
    var c4 : Color = CSSParse.Style.ParseCSSColor("rgba(128, 192, 168, 0.5)");
    var c5 : Color = CSSParse.Style.ParseCSSColor("#83F");
    var c6 : Color = CSSParse.Style.ParseCSSColor("#05BFA4");

[Download here](https://github.com/greggman/cssparse.net/releases/download/v0.0.1/cssparse.net.dll) and drop into your `Plugins` folder.

