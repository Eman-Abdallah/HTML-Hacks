## Most common font file formats:

# TrueType Fonts (TTF):
Extension: .ttf
Developed by Apple and Microsoft, TTF is one of the most common font formats. It offers good quality rendering and is widely supported by modern browsers.

# OpenType Fonts (OTF):
Extension: .otf
An extension of the TTF format, OTF is developed by Adobe and Microsoft. It supports more advanced typesetting features and is also widely supported by modern browsers.

# Web Open Font Format (WOFF):
Extension: .woff
A format specifically designed for use on the web, WOFF is supported by all modern browsers. It includes compression and additional metadata.

# Web Open Font Format 2 (WOFF2):
Extension: .woff2
An improved version of WOFF with better compression, leading to faster load times. It is supported by all modern browsers.

# Embedded OpenType Fonts (EOT):
Extension: .eot
Developed by Microsoft, EOT is used to embed fonts in web pages and is primarily supported by older versions of Internet Explorer.

# Scalable Vector Graphics Fonts (SVG):
Extension: .svg
SVG fonts use SVG's scalable vector graphics for rendering and are used for their ability to scale well at any size. However, they are not widely supported by modern browsers and are generally not recommended for use.

// @font-face {
    font-family: 'MyCustomFont';
    src: url('fonts/myfont.woff2') format('woff2'),
         url('fonts/myfont.woff') format('woff'),
         url('fonts/myfont.ttf') format('truetype'),
         url('fonts/myfont.eot') format('embedded-opentype'),
         url('fonts/myfont.svg#MyCustomFont') format('svg');
    font-weight: normal;
    font-style: normal;
}

body {
    font-family: 'MyCustomFont', sans-serif;
}
