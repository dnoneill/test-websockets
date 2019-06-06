---
layout: default
---
<script src="https://ncsu-libraries.github.io/iiif-annotation/dist/iiif-annotation.js"></script>

<div id="anno1" title="About">
This is an example of <a href="https://ncsu-libraries.github.io/iiif-annotation/"> a iiif-annotation library</a> equiped with websockets to allow for presentation. This is an example using a websocket to allow for transmitting. This is the reciever. It can be navigated but all the specialized controls are located here: <a href="http://intense-hamlet-45148.herokuapp.com">http://intense-hamlet-45148.herokuapp.com</a>. This functionality is fully customizable, please visit the JavaScript library website for more information.
</div>

<link rel="stylesheet" type="text/css" href="https://ncsu-libraries.github.io/iiif-annotation/dist/iiif-annotation.css">
<iiif-storyboard ws="wss://intense-hamlet-45148.herokuapp.com" annotationlist="https://dnoneill.github.io/annotate/annotations/0001-list.json" styling="tts: en; fullpage: true; hide_annocontrols: true; additionalinfo: anno1; startenddisplay: info;"></iiif-storyboard>

<style>
	#header_toolbar {
		display: none;
	}
	.annotation {
		height: 100vh;
		top: 0px!important;
		margin-left: 0px;
		font-size: 18px;
		max-height: 100%!important;
	}
	.seadragonboxfull {
		width: 90%;
		left: 10%;
	}
	@media only screen and (max-width: 600px) {
		.seadragonboxfull {
			width: 100%;
			left: 0%;
		}

	}
</style>
