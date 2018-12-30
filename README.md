
## Food Icons

Some food-related icons created using Inkscape and converted to 
a web usable CSS font (like fontawesome) using [![Font Custom](https://github.com/FontCustom/fontcustom)

### Usage

- Amend the icons in Inkscape if necessary
- Create webfont using Font Custom:

```sh
#!/bin/bash
/usr/local/bin/fontcustom compile ./icons
cp ./fontcustom/* ~/CHANGME
```

- Embed in web page 
```html
<link type="text/css" rel="stylesheet" href="/path/to/fontcustom/fontcustom.css" />

<i class="icon-timer"></i>

```

### License
Icons can be used in your projects unmodified. If you modify or improve them you are obliged to 
publicly share those improvements under this same GPL v2 license. 

