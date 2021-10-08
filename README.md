# Custom Google Translate For Websites
- GOOGLE TRANSLATE FOR WEBSITES WITHOUT POWERED BY TEXT AND GOOGLE LOGO AND SELECT TAG CSS CUSTOMIZED

[![](https://data.jsdelivr.com/v1/package/gh/arunkumartdr/Customized-Google-Translate-for-Websites/badge)](https://www.jsdelivr.com/package/gh/arunkumartdr/Customized-Google-Translate-for-Websites)

[See Demo Here](https://arunkumartdr.github.io/Customized-Google-Translate-for-Websites)

![image](https://user-images.githubusercontent.com/31769796/136484356-0bfd4976-4b9b-4e27-bd8e-b1d60f2122b6.png)


Features:
- Powered By Google Logo Removed
- Responsive
- Minified CSS
- Select tag Design Customized

## HOW TO USE

Want to use this? Great!

First step: Add this script tag to you webpage

```sh
<script type="text/javascript" src="//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>
```

Second step: Initialize Translate with this code

```sh
<script type="text/javascript">
function googleTranslateElementInit() {
  new google.translate.TranslateElement({pageLanguage: 'en'}, 'google_translate_element');
}
</script>
```

Third step: Add this style tag to you webpage

```sh
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/arunkumartdr/Customized-Google-Translate-for-Websites@1.0.0/gtranslate.css">
```

Fourth step: Add Html tag and Some Content to your site

```sh
<div id="google_translate_element"></div>
```

Fifth step: Run the site in browser and test it

## License

MIT

**Free Software**
