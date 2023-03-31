# language-module-IMT
the package gives you an easy and lightweight script to localisate your site for unlimited languages

Requiment:
PHP server
GLOBAL variable $lng for store and resending with $_REQUEST the language name

How to use:
1 For change the list of enabled languages change the array $langs
2 For add not presented language you need:
2.1 add constant with the same name like language name
2.2 add new language name into array $langs
2.3 add new memeber into array $lang_title

How to start?
1 adupt your site  for to use the language name in variable $lng
2 edit lang_panel.php 
3 insert script into page where you need to see the language-panel
