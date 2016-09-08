Several iron-iconset-svg derived from popular webfonts.

[View demo and icon gallery](https://ilikerobots.github.io/webfonts-iconset-svg/components/webfonts-iconset-svg/)

# Set Up
````sh
bower install ilikerobots/webfonts-iconset-svg
````
# Use

Example loading entire icon set:
```html
    <link rel="import" href="../webfonts-iconset-svg/webfonts-iconset-svg.html">
```

Individual fonts may be loaded instead of the entire pack.  For example, to load only iconic icons
```html
    <link rel="import" href="../webfonts-iconset-svg/iconic.html">
```

The included webfonts are:


| Name                | Author             | License | Iconset Name  |
|---------------------|--------------------|---------|---------------|
| [FontAwesome](https://github.com/FortAwesome/Font-Awesome) | Dave Gandy | SIL | fontawesome  |
| [Fontelico](https://github.com/fontello/fontelico.font) | Fontello| SIL | fontelico  |
| [Entypo](https://github.com/danielbruce/entypo)  | Daniel Bruce | SIL | entypo  |
| [Typicons](https://github.com/stephenhutchings/typicons.font) | Stephen Hutchings  | SIL | typicons  |
| [Iconic](https://github.com/somerandomdude/Iconic) | PJ Onori   | SIL  | iconic  |
| [Modern Pictograms](http://thedesignoffice.org/project/modern-pictograms) | John Caserta | SIL | modern-pictograms  |
| Meteocons | [Alleso Atzeni](http://www.alessioatzeni.com/) | SIL | meteocons  |
| [MFG Labs](https://github.com/MfgLabs/mfglabs-iconset) | MFG Labs | SIL | mfg-labs  |
| [Maki](https://github.com/mapbox/maki) | Mapbox | BSD | maki  |
| [Zocial](https://github.com/smcllns/css-social-buttons) | Sam Collins | MIT | zocial  |
| [Brandico](https://github.com/fontello/brandico.font) | Fontello  | SIL | brandico  |
| [Elusive](https://github.com/reduxframework/elusive-iconfont) | Aristeides Stathopoulos | SIL | elusive  |
| [Linecons](http://designmodo.com/linecons-free/)  | Designmodo         | CC BY | linecons  |
| Web Symbols | [Just Be Nice Studio](http://www.justbenice.ru/)| SIL | web-symbols  |

Please ensure you are compliant with all applicable licenses when using any of the fonts above.


To use an icon from one of these sets, first prefix your `iron-icon` with the iconset name, followed by a colon, ":", and then the icon id.
Example using the github icon from the zocial font:

```html
    <iron-icon icon="zocial:github-circled"></iron-icon>
```


### Fontello

The fonts in these iconsets were generated with a modified Fontello. It is hoped these modifications can be 
included directly into Fontello so that custom iconsets can be easily generated from the web.


