# Lite YouTube Embed Module for the <a href="https://processwire.com/">Processwire CMS</a>

Adapted from Ryan Cramer's <a href="https://github.com/ryancramerdesign/TextformatterVideoEmbed">TextformatterVideoEmbed</a>, this module replaces plain YouTube links pasted in a CKEditor field with Paul Irish's blazing fast <a href="https://github.com/paulirish/lite-youtube-embed">Lite YouTube Embed</a> script:

So for example pasting the following links…

`https://youtu.be/z_DwA8We7pI`<br>
`https://www.youtube.com/watch?v=5UAFdL8N91U`<br>
`https://www.youtube.com/?v=ucmU2nbCVI8`<br>
 
…will convert them to:

`<lite-youtube videoid='z_DwA8We7pI'></lite-youtube>`<br>
`<lite-youtube videoid='5UAFdL8N91U'></lite-youtube>`<br>
`<lite-youtube videoid='ucmU2nbCVI8'></lite-youtube>`

**Note:** you need to include the <a href="https://github.com/paulirish/lite-youtube-embed/blob/master/readme.md">lite-youtube-embed stylesheet and script</a> yourself as this module will not do it for you.
