# Js-Google-Translate
GOOGLE TRANSLATE WITHOUT POWERED BY TEXT AND GOOGLE LOGO


<!DOCTYPE html>
<html lang="en-US">
<style>
.goog-te-banner-frame.skiptranslate {
        display: none !important;
    } 
    body {
        top: 0px !important; 
    }
    
    #google_translate_element {
  color: transparent;
}
#google_translate_element a {
  display: none;
}

div.goog-te-gadget {
  color: transparent !important;
}

</style>
<body>

<h1>My Web Page</h1>

<p>Hello everybody!</p>

<p>Translate this page:</p>

<div id="google_translate_element"></div>

<script type="text/javascript">
function googleTranslateElementInit() {
  new google.translate.TranslateElement({pageLanguage: 'en'}, 'google_translate_element');
}
</script>

<script type="text/javascript" src="//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>

<p>You can translate the content of this page by selecting a language in the select box.</p>

</body>
</html>
