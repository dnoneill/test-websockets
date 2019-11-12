---
layout: default
---
<script src="https://ncsu-libraries.github.io/iiif-annotation/dist/iiif-annotation.js"></script>

<div id="anno1" title="About">
This is an example of <a href="https://ncsu-libraries.github.io/iiif-annotation/"> a iiif-annotation library</a> equiped with websockets to allow for presentation. This is an example using a websocket to allow for transmitting. This is the reciever. It can be navigated but all the specialized controls are located here: <a href="http://intense-hamlet-45148.herokuapp.com">http://intense-hamlet-45148.herokuapp.com</a>. This functionality is fully customizable, please visit the JavaScript library website for more information.
</div>

<link rel="stylesheet" type="text/css" href="https://ncsu-libraries.github.io/iiif-annotation/dist/iiif-annotation.css">
<iiif-storyboard ws="https://intense-hamlet-45148.herokuapp.com" annotationlist='https://dnoneill.github.io/annotate/annotations/wh234bz9013-0001-list.json' styling='tagscolor: {"animals":"#fe0a1e","discarded_constellation":"#ffd46c","greek_mythology":"#f6f030","historical":"#82f937","zodiac":"#22c5fa"};activecolor: #ffffff;annoview: collapse;toggleoverlay: false;fullpage:true;additionalinfo: anno1; startenddisplay: info;'></iiif-storyboard>


<style>
	#header_toolbar {display: none!important;}
	.annotation {top: 0px!important}
</style>
