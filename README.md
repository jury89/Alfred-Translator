Alfred-Translator
=================

Translate a phrase with Google translate and display output in alfred

If you are a Mac user, I’m sure you heard about <a href="http://www.alfredapp.com">Alfred</a>, it’s, as far as I know the best launcher. Alfred will speed up your work and make your mouse kind of useless.

Translator accept at least one mandatory parameter.<br>
First parameter: phrase or word you want to translate enclosed in double quotes;<br>
Second parameter (optional): target language (en, fr, de, hu, ...). "En" default;<br>
Third paramerer (optional): source language (auto, fr, de, it, ...). "Auto" default;<br>
Example:<br>
<ul>
    <li><strong>trans "hello world" es en</strong>   -----> hola mundo</li>
    <li><strong>trans "hello world" es</strong>      -----> hola mundo</li>
    <li><strong>trans "hola mundo"</strong>          -----> hello world</li>
</ul>