---
title: "Bitcoin de uma vez por todas"
date: 2024-12-23
draft: false
description: "Bitcoin is freedom"
tags: ["crypto", "bitcoin", "web3"]
---
> "Transportai um punhado de terra todos os dias e fareis uma montanha." -  Confúcio
<script>
    window.onload = function() {
        var zenButton = document.getElementById('zen-mode-button');
        zenButton.click();
    };
</script>
<style>
		/* https://necolas.github.io/normalize.css/ */
		html{line-height:1.15;-ms-text-size-adjust:100%;-webkit-text-size-adjust:100%}body{margin:0}
		article,aside,footer,header,nav,section{display:block}h1{font-size:2em;margin:.67em 0}hr{box-sizing:content-box;height:0;overflow:visible}
		pre{font-family:monospace,monospace;font-size:1em}a{background-color:transparent;-webkit-text-decoration-skip:objects}
		b,strong{font-weight:bolder}small{font-size:80%}img{border-style:none}

		body {
			font-size: 15px;
			color: #32373F;
			word-wrap: break-word;
			line-height: 1.6em;
			background-color: #ffffff;
			font-family: 'Avenir Next', 'Avenir', 'Arial', sans-serif;
			padding-bottom: 0px;
			padding-top: 0px;
		}
        code {
            color: #ffc107; /* Texto amarelo vibrante */
            background-color: #334155; /* Fundo mais escuro para destaque */
            padding: 4px 6px; /* Espaçamento interno */
            border-radius: 6px; /* Cantos arredondados */
            font-family: Consolas, Monaco, 'Courier New', monospace; /* Fonte monoespaçada */
        }
		kbd {
			border: 1px solid rgb(220, 220, 220);
			box-shadow: inset 0 -1px 0 rgb(220, 220, 220);
			padding: 2px 4px;
			border-radius: 3px;
			background-color: rgb(243, 243, 243);
		}
		::-webkit-scrollbar {
			width: 7px;
			height: 7px;
		}
		::-webkit-scrollbar-corner {
			background: none;
		}
		::-webkit-scrollbar-track {
			border: none;
		}
		::-webkit-scrollbar-thumb {
			background: rgba(100, 100, 100, 0.3);
			border-radius: 5px;
		}
		::-webkit-scrollbar-track:hover {
			background: rgba(0, 0, 0, 0.1);
		}
		::-webkit-scrollbar-thumb:hover {
			background: rgba(100, 100, 100, 0.7);
		}



		/* Remove top padding and margin from first child so that top of rendered text is aligned to top of text editor text */

		#rendered-md > h1:first-child,
		#rendered-md > h2:first-child,
		#rendered-md > h3:first-child,
		#rendered-md > h4:first-child,
		#rendered-md > ul:first-child,
		#rendered-md > ol:first-child,
		#rendered-md > table:first-child,
		#rendered-md > blockquote:first-child,
		#rendered-md > img:first-child,
		#rendered-md > p:first-child {
			margin-top: 0;
			padding-top: 0;
		}

		p, h1, h2, h3, h4, h5, h6, ul, table {
			margin-top: .6em;
			margin-bottom: 1.35em;

			/*
				Adds support for RTL text in the note body. It automatically detects the direction using the content.
				Issue: https://github.com/laurent22/joplin/issues/3991
			*/
			unicode-bidi: plaintext;
		}

		h1, h2, h3, h4, h5, h6, ul, table {
			margin-bottom: 0.65em;
		}

		h1, h2, h3, h4, h5, h6 {
			line-height: 1.5em;
		}
		h1 {
			font-size: 1.5em;
			font-weight: bold;
			border-bottom: 1px solid #dddddd;
			padding-bottom: .3em;
		}
		h2 {
			font-size: 1.3em;
			font-weight: bold;
			padding-bottom: .1em; */
		}
		h3 {
			font-size: 1.1em;
			font-weight: bold;
		}
		h4, h5, h6 {
			font-size: 1em;
			font-weight: bold;
		}

		.exported-note-title {
			font-size: 2em;
			font-weight: bold;
			margin-bottom: 0.8em;
			line-height: 1.5em;
			padding-bottom: .35em;
			border-bottom: 1px solid #dddddd;
		}

		a {
			color: #155BDA;
		}
		ul, ol {
			padding-left: 0;
			margin-left: 1.7em;
		}
		li {
			margin-bottom: .4em;
		}
		li p {
			margin-top: 0.2em;
			margin-bottom: 0;
		}

		.resource-icon {
			display: inline-block;
			position: relative;
			top: 0.3em;
			text-decoration: none;
			width: 1.2em;
			height: 1.4em;
			margin-right: 0.4em;
			background-color:  #155BDA;
		}
    /* These icons are obtained from the wonderful ForkAwesome project by copying the src svgs
     * into the css classes below.
     * svgs are obtained from https://github.com/ForkAwesome/Fork-Awesome/tree/master/src/icons/svg
     * instead of the svg width, height property you must use a viewbox here, 0 0 1536 1792 is typically the actual size of the icon
     * each line begins with the pre-amble -webkit-mask: url("data:image/svg+xml;utf8,
     * and of course finishes with ");
     * to prevent artifacts it is also necessary to include -webkit-mask-repeat: no-repeat;
     * on the following line
     * */
		.fa-joplin {
			/* Awesome Font file */
			-webkit-mask: url("data:image/svg+xml;utf8,<svg viewBox='0 0 1536 1792' xmlns='http://www.w3.org/2000/svg'><path d='M373.834 128C168.227 128 0 296.223 0 501.834v788.336C0 1495.778 168.227 1664 373.834 1664h788.336c205.608 0 373.83-168.222 373.83-373.83V501.834C1536 296.224 1367.778 128 1162.17 128zm397.222 205.431h417.424a7.132 7.132 0 0 1 7.132 7.133v132.552c0 4.461-3.619 8.073-8.077 8.073h-57.23c-24.168 0-43.768 19.338-44.284 43.374v2.377h-.017v136.191h-.053l-.466 509.375c-5.02 77.667-39.222 149.056-96.324 201.046-60.28 54.834-141.948 85.017-229.962 85.017-12.45 0-25.208-.61-37.907-1.785-92.157-8.682-181.494-48.601-251.662-112.438-71.99-65.517-117.147-150.03-127.164-238-11.226-98.763 23.42-192.783 95.045-257.937 81.99-74.637 198.185-101.768 316.613-75.704 5.574 1.227 9.55 6.282 9.55 11.997v199.52c-.199 2.625-1.481 6.599-8.183 2.896-.663-.365-1.194-.511-1.653-.531-21.987-10.587-45.159-17.57-68.559-19.916-.38-.04-.757-.124-1.138-.163-.537-.048-1.034-.033-1.556-.075-4.13-.354-8.183-.517-12.203-.58-.87-.011-1.771-.127-2.641-.127-.486 0-.951.05-1.437.057-1.464.011-2.886.115-4.33.163-2.76.102-5.497.211-8.182.448-.273.024-.547.07-.835.097-25.509 2.4-47.864 11.104-65.012 25.47-.954.802-1.974 1.53-2.9 2.36a1.34 1.34 0 0 1-.168.146c-23.96 21.8-34.881 53.872-30.726 90.316 4.62 40.737 26.94 81.156 62.841 113.823 35.908 32.67 80.335 52.977 125.113 57.186 35.118 3.36 66.547-3.919 89.899-20.461a97.255 97.255 0 0 0 9.365-7.501c2.925-2.661 5.569-5.5 8.086-8.416.3-.348.672-.673.975-1.024 8.253-9.864 14.222-21.067 17.996-33.148.639-2.034 1.051-4.148 1.564-6.227.381-1.563.81-3.106 1.112-4.693.555-2.784.923-5.632 1.253-8.49.086-.709.183-1.414.237-2.128.492-4.893.693-9.858.55-14.91h.013V521.623c-2.01-22.626-20.78-40.434-43.928-40.434h-57.23a8.071 8.071 0 0 1-8.077-8.073V340.564a7.132 7.132 0 0 1 7.136-7.133z'/></svg>");
		}
		.fa-file-image {
			-webkit-mask: url("data:image/svg+xml;utf8,<svg viewBox='0 0 1536 1792' xmlns='http://www.w3.org/2000/svg'><path d='M1468 380c37 37 68 111 68 164v1152c0 53-43 96-96 96H96c-53 0-96-43-96-96V96C0 43 43 0 96 0h896c53 0 127 31 164 68zm-444-244v376h376c-6-17-15-34-22-41l-313-313c-7-7-24-16-41-22zm384 1528V640H992c-53 0-96-43-96-96V128H128v1536h1280zm-128-448v320H256v-192l192-192 128 128 384-384zm-832-192c-106 0-192-86-192-192s86-192 192-192 192 86 192 192-86 192-192 192z'/></svg>");
      -webkit-mask-repeat: no-repeat;
		}
		.fa-file-pdf {
			-webkit-mask: url("data:image/svg+xml;utf8,<svg viewBox='0 0 1536 1792' xmlns='http://www.w3.org/2000/svg'><path d='M1468 380c37 37 68 111 68 164v1152c0 53-43 96-96 96H96c-53 0-96-43-96-96V96C0 43 43 0 96 0h896c53 0 127 31 164 68zm-444-244v376h376c-6-17-15-34-22-41l-313-313c-7-7-24-16-41-22zm384 1528V640H992c-53 0-96-43-96-96V128H128v1536h1280zm-514-593c25 20 53 38 84 56 42-5 81-7 117-7 67 0 152 8 177 49 7 10 13 28 2 52-1 1-2 3-3 4v1c-3 18-18 38-71 38-64 0-161-29-245-73-139 15-285 46-392 83-103 176-182 262-242 262-10 0-19-2-28-7l-24-12c-3-1-4-3-6-5-5-5-9-16-6-36 10-46 64-123 188-188 8-5 18-2 23 6 1 1 2 3 2 4 31-51 67-116 107-197 45-90 80-178 104-262-32-109-42-221-24-287 7-25 22-40 42-40h22c15 0 27 5 35 15 12 14 15 36 9 68-1 3-2 6-4 8 1 3 1 5 1 8v30c-1 63-2 123-14 192 35 105 87 190 146 238zm-576 411c30-14 73-57 137-158-75 58-122 124-137 158zm398-920c-10 28-10 76-2 132 3-16 5-31 7-44 2-17 5-31 7-43 1-3 2-5 4-8-1-1-1-3-2-5-1-18-7-29-13-36 0 2-1 3-1 4zm-124 661c88-35 186-63 284-81-10-8-20-15-29-23-49-43-93-103-127-176-19 61-47 126-83 197-15 28-30 56-45 83zm646-16c-5-5-31-24-140-24 49 18 94 28 124 28 9 0 14 0 18-1 0-1-1-2-2-3z'/></svg>");
      -webkit-mask-repeat: no-repeat;
		}
		.fa-file-word {
			-webkit-mask: url("data:image/svg+xml;utf8,<svg viewBox='0 0 1536 1792' xmlns='http://www.w3.org/2000/svg'><path d='M1468 380c37 37 68 111 68 164v1152c0 53-43 96-96 96H96c-53 0-96-43-96-96V96C0 43 43 0 96 0h896c53 0 127 31 164 68zm-444-244v376h376c-6-17-15-34-22-41l-313-313c-7-7-24-16-41-22zm384 1528V640H992c-53 0-96-43-96-96V128H128v1536h1280zM233 768v107h70l164 661h159l128-485c5-15 8-30 10-46 1-8 2-16 2-24h4l3 24c3 14 4 30 9 46l128 485h159l164-661h70V768h-300v107h90l-99 438c-4 16-6 33-7 46l-2 21h-4c0-6-2-14-3-21-3-13-5-30-9-46L825 768H711l-144 545c-4 16-5 33-8 46l-4 21h-4l-2-21c-1-13-3-30-7-46l-99-438h90V768H233z'/></svg>");
      -webkit-mask-repeat: no-repeat;
		}
		.fa-file-powerpoint {
			-webkit-mask: url("data:image/svg+xml;utf8,<svg viewBox='0 0 1536 1792' xmlns='http://www.w3.org/2000/svg'><path d='M1468 380c37 37 68 111 68 164v1152c0 53-43 96-96 96H96c-53 0-96-43-96-96V96C0 43 43 0 96 0h896c53 0 127 31 164 68zm-444-244v376h376c-6-17-15-34-22-41l-313-313c-7-7-24-16-41-22zm384 1528V640H992c-53 0-96-43-96-96V128H128v1536h1280zm-992-234v106h327v-106h-93v-167h137c43 0 82-2 118-15 90-31 146-124 146-233s-54-193-137-228c-38-15-84-19-130-19H416v107h92v555h-92zm353-280H650V882h120c35 0 62 6 83 18 36 21 56 62 56 115 0 56-20 99-62 120-21 10-47 15-78 15z'/></svg>");
      -webkit-mask-repeat: no-repeat;
		}
		.fa-file-excel {
			-webkit-mask: url("data:image/svg+xml;utf8,<svg viewBox='0 0 1536 1792' xmlns='http://www.w3.org/2000/svg'><path d='M1468 380c37 37 68 111 68 164v1152c0 53-43 96-96 96H96c-53 0-96-43-96-96V96C0 43 43 0 96 0h896c53 0 127 31 164 68zm-444-244v376h376c-6-17-15-34-22-41l-313-313c-7-7-24-16-41-22zm384 1528V640H992c-53 0-96-43-96-96V128H128v1536h1280zm-979-234v106h281v-106h-75l103-161c12-19 18-34 21-34h2c1 4 3 7 5 10 4 8 10 14 17 24l107 161h-76v106h291v-106h-68l-192-273 195-282h67V768H828v107h74l-103 159c-12 19-21 34-21 33h-2c-1-4-3-7-5-10-4-7-9-14-17-23L648 875h76V768H434v107h68l189 272-194 283h-68z'/></svg>");
      -webkit-mask-repeat: no-repeat;
		}
		.fa-file-audio {
			-webkit-mask: url("data:image/svg+xml;utf8,<svg viewBox='0 0 1536 1792' xmlns='http://www.w3.org/2000/svg'><path d='M1468 380c37 37 68 111 68 164v1152c0 53-43 96-96 96H96c-53 0-96-43-96-96V96C0 43 43 0 96 0h896c53 0 127 31 164 68zm-444-244v376h376c-6-17-15-34-22-41l-313-313c-7-7-24-16-41-22zm384 1528V640H992c-53 0-96-43-96-96V128H128v1536h1280zM620 850c12 5 20 17 20 30v544c0 13-8 25-20 30-4 1-8 2-12 2-8 0-16-3-23-9l-166-167H288c-18 0-32-14-32-32v-192c0-18 14-32 32-32h131l166-167c10-9 23-12 35-7zm417 689c19 0 37-8 50-24 83-102 129-231 129-363s-46-261-129-363c-22-28-63-32-90-10-28 23-32 63-9 91 65 80 100 178 100 282s-35 202-100 282c-23 28-19 68 9 90 12 10 26 15 40 15zm-211-148c17 0 34-7 47-20 56-60 87-137 87-219s-31-159-87-219c-24-26-65-27-91-3-25 24-27 65-2 91 33 36 52 82 52 131s-19 95-52 131c-25 26-23 67 2 91 13 11 29 17 44 17z'/></svg>");
      -webkit-mask-repeat: no-repeat;
		}
		.fa-file-video {
			-webkit-mask: url("data:image/svg+xml;utf8,<svg viewBox='0 0 1536 1792' xmlns='http://www.w3.org/2000/svg'><path d='M1468 380c37 37 68 111 68 164v1152c0 53-43 96-96 96H96c-53 0-96-43-96-96V96C0 43 43 0 96 0h896c53 0 127 31 164 68zm-444-244v376h376c-6-17-15-34-22-41l-313-313c-7-7-24-16-41-22zm384 1528V640H992c-53 0-96-43-96-96V128H128v1536h1280zM768 768c70 0 128 58 128 128v384c0 70-58 128-128 128H384c-70 0-128-58-128-128V896c0-70 58-128 128-128h384zm492 2c12 5 20 17 20 30v576c0 13-8 25-20 30-4 1-8 2-12 2-8 0-17-3-23-9l-265-266v-90l265-266c6-6 15-9 23-9 4 0 8 1 12 2z'/></svg>");
      -webkit-mask-repeat: no-repeat;
		}
		.fa-file-archive {
			-webkit-mask: url("data:image/svg+xml;utf8,<svg viewBox='0 0 1536 1792' xmlns='http://www.w3.org/2000/svg'><path d='M640 384V256H512v128h128zm128 128V384H640v128h128zM640 640V512H512v128h128zm128 128V640H640v128h128zm700-388c37 37 68 111 68 164v1152c0 53-43 96-96 96H96c-53 0-96-43-96-96V96C0 43 43 0 96 0h896c53 0 127 31 164 68zm-444-244v376h376c-6-17-15-34-22-41l-313-313c-7-7-24-16-41-22zm384 1528V640H992c-53 0-96-43-96-96V128H768v128H640V128H128v1536h1280zM781 943c85 287 107 349 107 349 5 17 8 34 8 52 0 111-108 192-256 192s-256-81-256-192c0-18 3-35 8-52 0 0 21-62 120-396V768h128v128h79c29 0 54 19 62 47zm-141 465c71 0 128-29 128-64s-57-64-128-64-128 29-128 64 57 64 128 64z'/></svg>");
      -webkit-mask-repeat: no-repeat;
		}
		.fa-file-code {
			-webkit-mask: url("data:image/svg+xml;utf8,<svg viewBox='0 0 1536 1792' xmlns='http://www.w3.org/2000/svg'><path d='M1468 380c37 37 68 111 68 164v1152c0 53-43 96-96 96H96c-53 0-96-43-96-96V96C0 43 43 0 96 0h896c53 0 127 31 164 68zm-444-244v376h376c-6-17-15-34-22-41l-313-313c-7-7-24-16-41-22zm384 1528V640H992c-53 0-96-43-96-96V128H128v1536h1280zM480 768c11-14 31-17 45-6l51 38c14 11 17 31 6 45l-182 243 182 243c11 14 8 34-6 45l-51 38c-14 11-34 8-45-6l-226-301c-8-11-8-27 0-38zm802 301c8 11 8 27 0 38l-226 301c-11 14-31 17-45 6l-51-38c-14-11-17-31-6-45l182-243-182-243c-11-14-8-34 6-45l51-38c14-11 34-8 45 6zm-620 461c-18-3-29-20-26-37l138-831c3-18 20-29 37-26l63 10c18 3 29 20 26 37l-138 831c-3 18-20 29-37 26z'/></svg>");
      -webkit-mask-repeat: no-repeat;
		}
		.fa-file-alt, .fa-file-csv {
      /* fork-awesome doesn't have csv so we use the text icon */
			-webkit-mask: url("data:image/svg+xml;utf8,<svg viewBox='0 0 1536 1792' xmlns='http://www.w3.org/2000/svg'><path d='M1468 380c37 37 68 111 68 164v1152c0 53-43 96-96 96H96c-53 0-96-43-96-96V96C0 43 43 0 96 0h896c53 0 127 31 164 68zm-444-244v376h376c-6-17-15-34-22-41l-313-313c-7-7-24-16-41-22zm384 1528V640H992c-53 0-96-43-96-96V128H128v1536h1280zM384 800c0-18 14-32 32-32h704c18 0 32 14 32 32v64c0 18-14 32-32 32H416c-18 0-32-14-32-32v-64zm736 224c18 0 32 14 32 32v64c0 18-14 32-32 32H416c-18 0-32-14-32-32v-64c0-18 14-32 32-32h704zm0 256c18 0 32 14 32 32v64c0 18-14 32-32 32H416c-18 0-32-14-32-32v-64c0-18 14-32 32-32h704z'/></svg>");
      -webkit-mask-repeat: no-repeat;
		}
		.fa-file {
			-webkit-mask: url("data:image/svg+xml;utf8,<svg viewBox='0 0 1536 1792' xmlns='http://www.w3.org/2000/svg'><path d='M1468 380c37 37 68 111 68 164v1152c0 53-43 96-96 96H96c-53 0-96-43-96-96V96C0 43 43 0 96 0h896c53 0 127 31 164 68zm-444-244v376h376c-6-17-15-34-22-41l-313-313c-7-7-24-16-41-22zm384 1528V640H992c-53 0-96-43-96-96V128H128v1536h1280z'/></svg>");
      -webkit-mask-repeat: no-repeat;
		}
		blockquote {
			border-left: 4px solid rgb(220, 220, 220);
			padding-left: 1.2em;
			margin-left: 0;
			opacity: 0.7;
		}

		.jop-tinymce table,
		table {
			text-align: left;
			border-collapse: collapse;
			border: 1px solid rgb(220, 220, 220);
			background-color: #ffffff;
		}

		.jop-tinymce table td, .jop-tinymce table th,
		table td, th {
			text-align: left;
			padding: .5em 1em .5em 1em;
			font-size: 15;
			color: #32373F;
			font-family: 'Avenir Next', 'Avenir', 'Arial', sans-serif;
		}

		.jop-tinymce table td,
		table td {
			border: 1px solid rgb(220, 220, 220);
		}

		.jop-tinymce table th,
		table th {
			border: 1px solid rgb(220, 220, 220);
			border-bottom: 2px solid rgb(220, 220, 220);
			background-color: rgb(247, 247, 247);
		}

		.jop-tinymce table tr:nth-child(even),
		table tr:nth-child(even) {
			background-color: rgb(247, 247, 247);
		}

		.jop-tinymce table tr:hover,
		table tr:hover {
			background-color: #e5e5e5;
		}

		hr {
			border: none;
			border-bottom: 2px solid #dddddd;
		}
		img {
			max-width: 100%;
			height: auto;
		}

		.inline-code,
		.mce-content-body code {
			border: 1px solid rgb(220, 220, 220);
			background-color: rgb(243, 243, 243);
			padding-right: .2em;
			padding-left: .2em;
			border-radius: .25em;
			color: rgb(0,0,0);
			font-size: .9em;
		}

		.highlighted-keyword {
			background-color: #F3B717;
			color: black;
		}

		.not-loaded-resource img {
			width: 1.15em;
			height: 1.15em;
			background: white;
			padding: 2px !important;
			border-radius: 2px;
			box-shadow: 0 1px 3px #000000aa;
		}

		a.not-loaded-resource img {
			margin-right: .2em;
		}

		a.not-loaded-resource {
			display: flex;
			flex-direction: row;
			align-items: center;
		}

		.md-checkbox input[type=checkbox]:checked {
			opacity: 0.7;
		}

		.jop-tinymce ul.joplin-checklist .checked,
		.md-checkbox .checkbox-label-checked {
			opacity: 0.5;
		}

		.exported-note {
			padding: 1em;
		}

		.joplin-editable .joplin-source {
			display: none;
		}

		mark {
			background: #F7D26E;
			color: black;
		}

		/* =============================================== */
		/* For TinyMCE */
		/* =============================================== */

		.mce-content-body {
			/* Note: we give a bit more padding at the bottom, to allow scrolling past the end of the document */
			padding: 5px 10px 10em 0;
		}

		/*
		.mce-content-body code {
			background-color: transparent;
		}
		*/

		.mce-content-body [data-mce-selected=inline-boundary] {
			background-color: transparent;
		}

		.mce-content-body .joplin-editable {
			cursor: pointer !important;
		}

		.mce-content-body.mce-content-readonly {
			opacity: 0.5;
		}

		/* We need that to make sure click events have the A has a target */
		.katex a span {
			pointer-events: none;
		}

		.media-player {
			width: 100%;
			margin-top: 10px;
		}

		.media-player.media-pdf {
			min-height: 35rem;
			width: 100%;
			max-width: 1000px;
			margin: 0;
			border: 0;
			display: block;
		}

		/* Clear the CODE style if the element is within a joplin-editable block */
		.mce-content-body .joplin-editable code {
			border: none;
			background: none;
			padding: 0;
			color: inherit;
			font-size: inherit;
		}

		/* To make code blocks horizontally scrollable */
		/* https://github.com/laurent22/joplin/issues/5740 */
		pre.hljs {
			overflow-x: auto;
		}

		.joplin-table-wrapper{
			overflow-x: auto;
			overflow-y: hidden;
		}

		/* =============================================== */
		/* For TinyMCE */
		/* =============================================== */

		@media print {
			body {
				height: auto !important;
			}

			pre {
				white-space: pre-wrap;
			}

			.code, .inline-code {
				border: 1px solid #CBCBCB;
			}

			#joplin-container-content {
				/* The height of the content is set dynamically by JavaScript (in updateBodyHeight) to go
				  around various issues related to scrolling. However when printing we don't want this
				  fixed size as that would crop the content. So we set it to auto here. "important" is
				  needed to override the style set by JavaScript at the element-level. */
				height: auto !important;
			}
		}


				/*
					FOR THE MARKDOWN EDITOR
				*/

				/* Remove the indentation from the checkboxes at the root of the document
				  (otherwise they are too far right), but keep it for their children to allow
				  nested lists. Make sure this value matches the UL margin. */

				li.md-checkbox {
					list-style-type: none;
				}

				li.md-checkbox input[type=checkbox] {
					margin-left: -1.71em;
					margin-right: 0.7em;
				}

				ul.joplin-checklist {
					list-style:none;
				}

				/*
					FOR THE RICH TEXT EDITOR
				*/

				ul.joplin-checklist li::before {
					content:"\f14a";
					font-family:"Font Awesome 5 Free";
					background-size: 16px 16px;
					pointer-events: all;
					cursor: pointer;
					width: 1em;
					height: 1em;
					margin-left: -1.3em;
					position: absolute;
					color: #32373F;
				}

				.joplin-checklist li:not(.checked)::before {
					content:"\f0c8";
				}
.mermaid { width: 640px; }
pre.mermaid > svg { white-space: unset; }
.mermaid-export-graph {
					opacity: 0;
					height: 0;
					z-index: 1;
					position: relative;
				}
				.joplin-editable:hover .mermaid-export-graph,
				.joplin-editable .mermaid-export-graph:has(:focus-visible) {
					opacity: 1;
				}
				.mermaid-export-graph > button:hover {
					background-color: #CBDAF1 !important;
				}</style><h1 id="introdução">Introdução</h1>
                {{< typeit
  tag=h1
  speed=50
  breakLines=false
  loop=true
>}}
Desmitificando o Bitcoin.
Bitcoin é liberdade..
Bitcoin de uma vez por todas...{{< /typeit >}}

<p>Este artigo é para você que não sabe nada sobre Bitcoin e deseja entender melhor o tema. Também é ideal para iniciantes que buscam uma introdução simples, rápida e fácil de entender, mas que se sentem inseguros quanto à primeira compra. Ou ainda, para aqueles que querem se aprofundar no universo das criptomoedas, curiosos com o impacto revolucionário do Bitcoin na tecnologia moderna.</p>
<p>A insegurança vem da falta de conhecimento. Por isso, este artigo foi criado para fornecer os fundamentos essenciais sobre Bitcoin, ajudando você a comprar, armazenar e trocar BTCs com segurança. Além disso, esse artigo aborda boas práticas de segurança digital para proteger seus ativos e se proteger na internet.</p>
Esse artigo irá abordar:</p>
<ul>
<li>O que é Bitcoin?</li>
<li>O que é Satoshi?</li>
<li>Bitcoin é dinheiro?</li>
<li>O que é a chamada &quot;Blockchain&quot;?</li>
<li>Termos associados ao Bitcoin</li>
<li>Criptografia da coisa</li>
<li>O sistema em que vale a pena ser honesto</li>
<li>O que são as corretoras e como comprar BTC</li>
<li>Compreendendo ataques básicos de engenharia social e de hackers para se prevenir</li>
<li>O tópico mais importante, a &quot;Autocustódia&quot;</li>
<li>Prós e Contras</li>
<li>Finalização e ferramentas para aprender</li>
<li>Referências</li>
</ul>
<h1 id="o-que-é-bitcoin">O que é Bitcoin ?</h1>
    <p>Resumidamente, o Bitcoin é tanto uma moeda digital quanto um sistema de pagamento descentralizado, criado por uma pessoa ou grupo sob o pseudônimo &quot;Satoshi Nakamoto&quot;. Em 2008, Nakamoto publicou um documento conhecido como &quot;whitepaper&quot;, que detalha o funcionamento do <code>Bitcoin</code>.</p>
<p>Esse whitepaper apresentou uma proposta inovadora: um <code>sistema financeiro</code> que dispensa intermediários, como bancos, utilizando a tecnologia de blockchain para garantir segurança e transparência nas transações. O Bitcoin permite transações peer-to-peer, e sua principal característica é a <code>descentralização</code>, o que significa que nenhuma entidade ou governo controla a rede. Desde então, o Bitcoin se tornou a primeira e mais conhecida criptomoeda, servindo de base para o surgimento de inúmeras outras.</p>
<p>Link do whitepaper: <a data-from-md title='https://bitcoin.org/bitcoin.pdf' href='https://bitcoin.org/bitcoin.pdf'>https://bitcoin.org/bitcoin.pdf</a></p>
<p>Um sistema de pagamento eletrônico, baseado na criptografia e não na confiança.</p>
<p><img src="/_resources/dfd3c5fcc44f48c8b3e7d3c4863ed43c.png" alt="a2ecfe7947d9fc4306b9b232e556c322.png"></p>
<p>O gênio autointitulado <code>Satoshi Nakamoto</code> conseguiu criar um sistema revolucionário que transforma a maneira como lidamos com a honestidade e a confiança nas transações financeiras. Por meio de regras matemáticas complexas e criptografia avançada, Nakamoto desenvolveu o Bitcoin, uma forma de dinheiro digital que pode ser armazenada de maneira segura e offline, contanto que os usuários sigam rigorosamente os protocolos criptográficos estabelecidos. Dessa maneira, ele conseguiu com sucesso criar um <code>sistema onde vale a pena ser honesto</code>.</p>
<p>Este sistema não apenas permite transações sem a necessidade de intermediários, como bancos, mas também proporciona transparência e segurança, uma vez que todas as transações são registradas em um lugar público, chamado blockchain. Essa inovação oferece uma alternativa viável ao sistema financeiro tradicional, incentivando a honestidade, já que as regras são claras e imutáveis.</p>
<p>Além disso, os sistemas de criptografia não são novos; eles têm sido amplamente utilizados em contextos militares e de segurança para proteger informações sensíveis durante guerras e conflitos. Com a <code>evolução da tecnologia</code>, essas técnicas têm sido adaptadas e aplicadas em diversas áreas, incluindo a proteção de dados pessoais e transações online, mostrando que a criptografia é fundamental para a segurança na era digital.</p>
<h2 id="o-que-é-satoshi">O que é Satoshi?</h2>
<p>Satoshi, como apresentado anteriormente, é um pseudônimo que o criador do Bitcoin utilizou para aparecer publicamente. No entanto, &quot;Satoshi&quot; também se refere a unidade de fração de Bitcoin.</p>
<p>A unidade satoshi é a menor fração do Bitcoin (BTC) e foi nomeada em homenagem ao criador da criptomoeda, Satoshi Nakamoto. Um satoshi corresponde a 0.00000001 BTC, ou seja, 1 Bitcoin é equivalente a 100 milhões de satoshis.</p>
<p>Representação da unidade Satoshi:<br>
<img src="/_resources/4194321376254584908fd1f5527ec50b.png" alt="dffe48341b7e8c092eca023a00cb8fdb.png"></p>
<h1 id="bitcoin-é-dinheiro">Bitcoin é dinheiro?</h1>
<p>Por definição, dinheiro é qualquer item que atua como um meio de troca de valor em uma economia, armazena valor ou é geralmente aceito.</p>
<p>O que é Dinheiro?</p>
<p>Tradicionalmente, o dinheiro desempenha três funções principais:</p>
<ol>
<li>
<p><code>Meio de troca</code>: O dinheiro facilita transações, permitindo que as pessoas comprem e vendam bens e serviços sem a necessidade de uma troca direta.</p>
</li>
<li>
<p><code>Reserva de valor</code>: O dinheiro deve manter seu valor ao longo do tempo, permitindo que as pessoas economizem e planejem para o futuro. Isso significa que ele deve ser relativamente estável e confiável, para que os indivíduos possam ter confiança de que seu valor não se desvanecerá.</p>
</li>
<li>
<p><code>Unidade de conta</code>: O dinheiro fornece um padrão comum para medir o valor de bens e serviços, facilitando a comparação de preços e a contabilidade.</p>
</li>
</ol>
<p>A principal importância do Bitcoin (BTC) reside em sua função como reserva de valor. Diferente das moedas fiduciárias, o BTC é a única moeda digital cuja reserva de valor tende a aumentar ao longo do tempo, especialmente porque é imune à inflação, devido à sua oferta limitada de <code>21 milhões de unidades</code>.</p>
<p>Quem não é capaz de renunciar o presente pelo futuro, está fadado ao fracasso. Faça sua autocustódia corretamente, e tenha seu dinheiro multiplicado no futuro.</p>
<p>O valor de um BTC em 2009 valia US$ $0,0008.</p>
<p>No mesmo ano, o dólar estava cotado em R$ 2,307.</p>
<p>Ou seja, investir R$ 50 seria ter 27 mil BTCs na época. Caso a autocustódia tenha sido feita corretamente, e os BTCs tenham sido guardados, avaliando 1 BTC no valor de 60.000$, a pessoa teria aproximadamente: <code>1.851.132.150,00 dólares ou 1,85 bilhões de dólares</code> 😱.</p>
<p><img src="/_resources/143224bab2754e0e85945bb7881f8d48.gif" alt="uau.gif"></p>
<p>As moedas fiduciárias, por outro lado, são amplamente baseadas na capacidade produtiva da população de um país. Essa capacidade produtiva resulta da interação entre diferentes faixas etárias, onde uma base maior de jovens trabalha para sustentar uma população idosa crescente. Este modelo, aliado a políticas monetárias expansionistas, frequentemente leva à desvalorização do dinheiro fiduciário, uma vez que os governos podem imprimir mais moeda para cobrir déficits, resultando em inflação.</p>
<p><img src="/_resources/3e00a7d748f54e3eb07c2df432206817.png" alt="c53c6d92495cbd00e3ac1a192bc619a4.png"></p>
<hr>
<p>A inflação reduz o poder de compra das moedas fiduciárias ao longo do tempo. Isso significa que, embora o dinheiro possa ser usado para transações no presente, seu <code>valor real diminui</code>, prejudicando a capacidade de economizar e planejar o futuro.</p>
<p>Ou seja, mesmo apesar de existir a variação de curto prazo do BTC, é muito mais interessante armazenar em BTC que moedas FIAT, visto que, como mencionado anteriormente, o valor do BTC <code>só aumenta</code> com o passar dos anos.</p>
<p>O contraste entre Bitcoin e moedas fiduciárias é notável. Enquanto o BTC oferece uma alternativa que pode preservar valor ao longo do tempo, as moedas fiduciárias são suscetíveis a flutuações de valor provocadas por decisões políticas, crises econômicas e desvalorização monetária. À medida que o Bitcoin continua a ser adotado como uma forma legítima de reserva de valor, ele se destaca como uma solução para aqueles que buscam <code>proteção contra a inflação</code> das moedas tradicionais.</p>
<p>Em suma, o Bitcoin não é apenas uma nova forma de dinheiro digital, ele representa uma mudança de paradigma em como as pessoas pensam sobre valor, propriedade e segurança financeira.</p>
<p>Com sua capacidade de atuar como uma reserva de valor em um mundo onde a inflação e a desvalorização são realidades constantes, o BTC se torna uma maneira de &quot;contornar o sistema&quot;, evitando o financiamento de políticas corruptas, desvios de recursos e perseguições. Dessa forma, oferece uma <code>proteção real</code> para a sua família.</p>
<p>Compre BTC e proteja sua família, seu patrimônio e a sua liberdade!.</p>
<h1 id="o-que-é-blockchain">O que é Blockchain?</h1>
<p>Um dos tópicos mais importantes, é essencial compreender o que é a Blockchain para prosseguir nos entendimentos sobre BTC.</p>
<p>A Blockchain é um <code>banco de dados</code> que armazena todas as transações realizadas, de maneira descentralizada, ao redor do mundo.</p>
<p>Isso significa que todas as transações são públicas e armazenadas, é possível verificar as transações no <a data-from-md title='https://mempool.space/' href='https://mempool.space/'>Mempool</a>.</p>
<p>No entanto, mesmo apesar de as transações serem públicas, não é possível saber quem enviou, e quem recebeu o BTC. Ademais, <code>informações pessoais</code>, informações conhecidas como PII ou Personally Identifiable Information ( Dados que podem identificar uma pessoa ), <code>não existem na Blockchain</code>, fazendo com que a Blockchain seja transparente e, ao mesmo tempo, segura.</p>
<h2 id="o-que-é-hash">O que é Hash?</h2>
<p>Primeiramente, é de suma importância que o conceito e definição de Hash seja entendido, para podermos prosseguir. Veja, não é difícil, basta prestar um pouco de atenção na explicação e você entenderá tranquilamente.</p>
<p>Um hash é uma <code>impressão digital</code> que um dado ou informação gera para ser identificada de maneira única. Imagine que você tem um documento de texto, uma imagem, vídeo, ou algum arquivo: o hash transforma esse conteúdo em uma sequência de letras e números que representa o arquivo de maneira exclusiva.</p>
<p>É como se fosse um <code>número de identidade</code> ou um código de barras para aquele conteúdo específico. Se você mudar uma vírgula ou uma letra, o hash vai mudar completamente, mesmo que a mudança seja muito pequena. Isso acontece porque os hashes são projetados para serem extremamente sensíveis a qualquer alteração no conteúdo.</p>
<p><img src="/_resources/6fd51015259f49e08db9e47df6ff7fdf.png" alt="af1c595c405778b9e11fdd3abc11c6d3.png"></p>
<p>Existem vários tipos de funções de hash, variando em velocidade, segurança e comprimento do resultado. Sendo os principais:</p>
<ul>
<li>MD5 (Message Digest 5): Esse é um dos hashes mais antigos e populares, criado nos anos 90. Ele gera uma sequência de 32 caracteres. Porém, devido a falhas de segurança descobertas, o MD5 não é mais considerado seguro para aplicações sensíveis, como proteção de senhas ou validação de dados críticos. Ele é vulnerável a ataques de colisão ( será explicado mais a frente ).</li>
</ul>
<p>Exemplo de MD5:<br>
<code>698dc19d489c4e4db73e28a713eab07b</code>  equivale à palavra &quot;teste&quot;, isto é, após terem sido aplicado várias funções matemáticas, a palavra &quot;teste&quot; agora é referenciada com esse valor de 32 caracteres.</p>
<ul>
<li>SHA-1 (Secure Hash Algorithm 1): SHA-1 foi amplamente utilizado após o MD5, gerando um hash de 40 caracteres.</li>
</ul>
<p>Exemplo de SHA-1:<br>
<code>9dc628289966d144c1a5fa20dd60b1ca1b9de6ed</code> equivale a palavra &quot;teste&quot;. Ou seja, a palavra &quot;teste&quot; tem um código de barras, e o código de barras dele em SHA-1 é essa sequência de caracteres.</p>
<ul>
<li>SHA-256, SHA-512 e outros da família SHA-2: Estes são atualmente os mais recomendados para segurança. SHA-256 produz um hash de 64 caracteres, enquanto SHA-512 produz um hash de 128 caracteres Eles são muito mais seguros e são amplamente utilizados em criptografia moderna, como em blockchain e SSL/TLS.</li>
</ul>
<p>Exemplo de SHA-512:<br>
&quot;teste&quot; → <code>b123e9e19d217169b981a61188920f9d28638709a5132201684d792b9264271b7f09157ed4321b1c097f7a4abecfc0977d40a7ee599c845883bd1074ca23c4af</code></p>
<p>Ou seja, a impressão digital da palavra &quot;teste&quot;, usando o tipo SHA-512, é <code>b123e9e19d217169b981a61188920f9d28638709a5132201684d792b9264271b7f09157ed4321b1c097f7a4abecfc0977d40a7ee599c845883bd1074ca23c4af</code>.</p>
<p>Isso significa que essa palavra equivale a essa cadeia de caracteres misturada, depois de diversos cálculos matemáticos e funções serem aplicadas.</p>
<p>Os Hashes são usados em várias áreas, como segurança da informação e blockchain, para <code>verificar a integridade dos dados</code> e garantir que eles não foram alterados. Então, se duas pessoas tiverem o mesmo hash de um arquivo, podem ter certeza de que o conteúdo é exatamente o mesmo, sem precisar ver o arquivo em si.</p>
<p>Dessa forma, se você quiser mandar uma mensagem para alguém usando email ou alguma tecnologia, e quiser garantir que a mensagem não foi alterada ou corrompida no meio do caminho, basta comparar a hash no início e na chegada da mensagem, informando o hash para quem irá receber o arquivo/mensagem. Caso esses hashs sejam iguais, a mensagem permaneceu a mesma, assim, confirmando a não violação da integridade da mensagem.</p>
<p>Para entender a diferença, imagine que <code>quanto maior</code> o comprimento do hash (como em SHA-512), <code>mais seguro</code> é o hash, pois ele cria combinações únicas para uma quantidade muito maior de dados, o que torna muito difícil para um atacante encontrar duas entradas diferentes que resultem no mesmo hash (ataque de colisão).</p>
<p>Ataques de colisão são quando uma mesma palavra, frase, ou informação gera o mesmo hash, mas quanto maior a cadeia de caracteres, mais difícil de isso acontecer.</p>
<p>Existem sites que fazem essa geração para você, um exemplo com sha512:</p>
<p><img src="/_resources/74c87534c38e4626b21add5d55b99eb0.png" alt="8273bc8b0672af1260084b1613586345.png"></p>
<p><a data-from-md title='https://sha512.online/' href='https://sha512.online/'>https://sha512.online/</a></p>
<h2 id="continuação-da-explicação-sobre-blockchain">Continuação da explicação sobre Blockchain</h2>
<p><code>Blockchain</code> ou &quot;Cadeia de Blocos&quot;, como já dito anteriormente, é o lugar onde todas as transações são guardadas. E como elas são guardadas? Basicamente, as transações são organizadas em uma cadeia de blocos, ou seja, um bloco na frente do outro.</p>
<p>Um exemplo fictício para facilitar a compreensão é o seguinte: imagine a blockchain como um <code>conjunto de caixas empilhadas umas sobre as outras</code>. Se você remover uma dessas caixas, toda a estrutura acima dela desmorona. Sendo que cada caixa contém as seguintes informações:</p>
<p>A identificação dessas caixas empilhadas, ou blocos, é feita por meio de hashes, conforme explicado no capítulo anterior. Além disso, dentro de cada bloco, existem outras identificações, que também utilizam hashes como mecanismo.</p>
<p>Um exemplo mais simplificado é:<br>
<img src="/_resources/6c4e09deb207442ab0a0d35acaa640b7.png" alt="84e6bdef062a8a1e9e881178a69cd20e.png"></p>
<p>No whitepaper do bitcoin, a blockchain é mostrada da seguinte forma -&gt;<br>
<img src="/_resources/ac0b25ec7b724acd86158570f3c931f2.png" alt="c7148215662f659059968ad833fa7b71.png"></p>
<p>No <a data-from-md title='https://mempool.space/' href='https://mempool.space/'>Mempool</a>, as transações com criptomoedas são provisoriamente armazenadas, juntamente com os blocos respectivos.</p>
<p>Como um exemplo o Bloco de número 872041 no mempool<br>
<img src="/_resources/f6f77df0f49e4090be0c7674292fdac8.png" alt="11e3152db92ef4548f622ba3fae93bb2.png"></p>
<p>Nesse exemplo, o Bloco tem o seu hash, que é o seu identificador principal, começando nesse caso com vários números 0. A data e o horário, dentre outras informações.</p>
<p>A informação mais importante é as transações, ao descer nas informações do Bloco, é possível ver todas as transações registradas nesse bloco.</p>
<p><img src="/_resources/b39737864a2647959179c6274fc5f03e.png" alt="b663b9a8d96de8fe9d739d670c770366.png"></p>
<p>Com um total de 789 transações, esse bloco mostra quantos BTC saiu de um endereço X, e entrou em um endereço Y, sendo assim, não é possível identificar quem enviou nem quem recebeu.</p>
<p>Caso não queira se aprofundar na parte dos significados de cada valor existente dentro dos Blocos pule para <code>Transactions</code>.</p>
<p>Nesse contexto, os blocos ficam organizados da seguinte maneira -&gt;<br>
<img src="/_resources/2182f949817542139b87e8ac816581f1.png" alt="f9cd1ed3a15c6e18a1a426f9153b26cd.png"></p>
<h3 id="versão">Versão</h3>
<p>Serve para:</p>
<ul>
<li>Identificar a versão do protocolo usada para minerar o bloco.</li>
<li>Sinalizar suporte a mudanças no consenso ou atualizações na rede.</li>
<li>Garantir compatibilidade entre nós durante períodos de transição de regras.</li>
</ul>
<h3 id="previous-block-id-hash">Previous Block ID | Hash</h3>
<p>Identificador do bloco ( caixa ) anterior.</p>
<h3 id="merkle-root">Merkle Root</h3>
<p>É o hash formado juntando os hashes de todas as transações existentes nesse bloco. O identificador geral do Bloco.</p>
<p>A seguinte figura representa como o Root hash é criado.</p>
<p><img src="/_resources/a50bc9ee64fc4762822cf9734403ea1b.png" alt="e26258be8c29ab3b82c5fae22224d79c.png"></p>
<h3 id="timestamp-ou-time">Timestamp ou Time</h3>
<p>É uma <code>marcação do tempo</code>, data e hora atual da montagem do bloco em um formato específico.</p>
<ul>
<li>Gerado quando o minerador constrói o cabeçalho do bloco, antes de iniciar o cálculo do hash.</li>
<li>Atualizado, se necessário, durante o processo de mineração.</li>
<li>Validado pela rede para garantir consistência temporal e integridade.</li>
</ul>
<h3 id="nonce">Nonce</h3>
<p>Um valor de hash estipulado como objetivo a ser atingido.</p>
<ul>
<li>Permite que os mineradores ajustem os dados de entrada para calcular hashes diferentes.</li>
<li>Garante que o processo de mineração seja baseado em tentativa e erro, exigindo trabalho computacional significativo.</li>
<li>Está diretamente ligado ao mecanismo de segurança e consenso do Bitcoin, dificultando a manipulação ou o controle centralizado da rede.</li>
</ul>
<h3 id="transactions">Transactions</h3>
<p>As transações ficam dentro do Bloco, podendo haver várias.</p>
<p>Aqui é guardado o endereço da pessoa que está enviando e da pessoa que está recebendo. Ademais, a quantia que foi enviada e que foi recebida também é guardada.</p>
<p>Na imagem a seguir, o In diz respeito a quanto de dinheiro entrou, e o Out quanto de dinheiro ( BTC ) saiu.<br>
<img src="/_resources/b1e114070d154649a8725dd289e7008b.png" alt="98e0e9cdc9f267ba0e530c20474a088c.png"></p>
<p>Existem então 2 modelos, o modelo fiduciário padrão e o modelo novo proposto pelo Bitcoin:<br>
<img src="/_resources/e8af0bcb6c1f4ca1b31f5d2c1915c61e.png" alt="edf6964382fdf5cf92d4504cc190fa36.png"></p>
<p>Ao examinar essa imagem do Whitepaper do Bitcoin, observa-se que o modelo financeiro tradicional preserva as identidades e transações das partes envolvidas, restringindo o acesso público a essas informações. Nesse sistema, os bancos e o Estado centralizam e detêm <code>todos os dados dos usuários</code>, armazenando uma ampla variedade de informações, violando a sua privacidade.</p>
<p>Segundo o seguinte trecho retirado do whitepaper do Bitcoin: &quot;O público pode ver que alguém está enviando uma quantia para outra pessoa, mas sem informações que vinculem a transação a ninguém. Isso é semelhante ao nível de informação divulgado pelas bolsas de valores, onde o tempo e o tamanho das negociações individuais, a 'fita', são divulgadas, mas sem informar quem eram as partes.&quot;, Satoshi Nakamoto apresenta a blockchain como uma <code>solução inovadora</code>, explicando que, no modelo proposto, o público pode visualizar que uma pessoa enviou uma determinada quantia a outra, sem ter acesso a informações pessoais das partes envolvidas.</p>
<p>Isso significa que as <code>Identities ou Identidades</code> não estabelecem nenhuma correlação com terceiros envolvidos ( Bancos, empresas privadas, Estado ), restringindo-se apenas ao indivíduo.</p>
<p>Esse sistema promove um modelo de <code>privacidade verdadeiro</code>, eliminando o controle direto de bancos e governos sobre os dados financeiros e sociais dos indivíduos. Dessa forma, garante-se a proteção da família, do patrimônio e da liberdade individual!.</p>
<hr>
<h2 id="mineração-ou-mining">Mineração ou Mining</h2>
<p>A mineração é o processo de validação de transações. Os mineradores, ao redor do mundo, ganham recompensas em BTC por minerar. Isso significa que, após muitos cálculos matemáticos realizados, os <code>mineradores</code>, usando a capacidade tecnológica de suas CPUs e principalmente GPUs ( Placas de Vídeo ), de computadores, ganham BTC como recompensa ao <code>validar transações na blockchain</code> e compor blocos.</p>
<p><img src="/_resources/f0a34dd1de8b4c538b8249c77985a742.png" alt="bed2a8d0076765916408f78e687c2714.png"></p>
<p>As transações feitas na Blockchain, são processadas pelos mineradores, as maquinas que estão minerando, que são responsáveis por validar a sua transação, e a enviar para a Blockchain.</p>
<p>Depois de ela ser validada e aceita pelos <code>mineradores</code> na rede, ela fica registrada com a saída de BTCs da pessoa X que enviou, e o recebimento desse BTC pela pessoa Y.</p>
<p>Exemplo da mempool:</p>
<p><img src="/_resources/688f0b29d168498badd7913c9ba5354c.png" alt="f50ea017d56908652f08b3da7ef1b683.png"></p>
<p>Exemplo de transação realizado, e histórico salvo no Mempool ( Blockchain )</p>
<p><img src="/_resources/6c62a01237d44c9bac2b8eb2c001cdc3.png" alt="61dde8109a76ce4c24e8c2ac024b49b6.png"></p>
<p>Como pode ver no exemplo acima, as únicas informações presentes são do Endereço que enviou, o Endereço que recebeu, e a quantia que saiu e que chegou.</p>
<p>bc1ptwms..... enviou para -&gt; bc1pnm7.....</p>
<p>Assim, não é possível saber quem foi a pessoa que enviou, nem quem foi a pessoa que recebeu.</p>
<p>Os endereços são a identificação pública usada para receber e enviar BTCs.</p>
<hr>
<p>Além disso, existem as <code>Taxas de transação</code>, criadas como incentivo para a rede e os mineradores. Quando uma transação é realizada, há um gasto de energia e tecnologia, denominado &quot;Gas fee&quot;. Esse gasto transforma-se na &quot;Transaction Fee&quot; ou &quot;Taxa de transação&quot;, que é o valor pago para inserir essa transação na cadeia de blocos.</p>
<p>Esse valor varia e depende da quantidade de transações sendo feitas na blockchain e da priorização das transações. A pessoa que está transferindo a quantia pode escolher se seu envio será prioritário ou não, ou seja, se será processado mais rapidamente ou não, pagando as taxas mais altas disponíveis no momento.</p>
<p>A mineração de Bitcoin é muito cara, os custos de equipamento e eletricidade são muito caros, fazendo com que a mineração, especialmente no Brasil, se torne muito difícil de fazer para indivíduos isolados.</p>
<p>O componente principal a ser usado na mineração é a Placa de Vídeo, este componente possui a maior capacidade de processamento de informações e alta velocidade na realização de cálculos matemáticos, se comparado com os processadores.</p>
<h2 id="proof-of-work-ou-prova-de-trabalho">Proof of Work ou Prova de Trabalho</h2>
<p>Os mineradores de Bitcoin competem intensamente para adicionar novos blocos à blockchain, uma disputa que ocorre por meio da resolução de cálculos matemáticos altamente complexos. Esses cálculos envolvem a criação de <code>hashes</code>, que são sequências únicas de caracteres alfanuméricos, explicadas anteriormente.</p>
<p>Quando um minerador encontra uma prova de trabalho válida, a rede valida e adiciona um novo bloco, algo que acontece, em média, a cada 10 minutos.</p>
<p>Como incentivo, o minerador recebe uma <code>recompensa</code> em Bitcoin. Esse processo exige equipamentos especializados, muitas vezes caros, devido ao alto nível de dificuldade.</p>
<p>A dinâmica do sistema é baseada em tentativas e erros: quanto mais combinações um minerador testa, maior é a probabilidade de sucesso. O objetivo final é gerar um hash que satisfaça os critérios estabelecidos pelo protocolo do Bitcoin.</p>
<p>O primeiro minerador a alcançar esse objetivo recebe a recompensa, e o processo recomeça com a definição de um novo alvo pela rede, iniciando um novo ciclo competitivo.</p>
<h2 id="processo-de-transações-na-blockchain">Processo de transações na Blockchain</h2>
<p>O processo de validação de transações começa quando um usuário X ( &quot;Kaká&quot; ) assina uma transação, tornando ela válida, provando que quem assinou é o detentor do dinheiro a ser enviado. Só assina a transação quem está enviando o valor, quem recebe o dinheiro não assina, apenas recebe.</p>
<p><img src="/_resources/7fcca43a240543399f77ada2806233be.png" alt="0027770f36be492b909eda18f1431e1d.png"></p>
<p>Logo em seguida, essa transação é enviada para uma &quot;Sala de espera&quot;, que é o Mempool. Até que um Minerador insere essa transação dentro de um bloco que está sendo montado.</p>
<p>Então, a rede verifica e atualiza os registros, na medida que os mineradores vão inserindo a sua transação na Blockchain.</p>
<p>Depois, o usuário que vai receber a quantia recebe essa transação, e mais confirmações de outros mineradores vão chegando. O exemplo na figura é a &quot;Carol&quot;</p>
<h1 id="termos-associados-ao-bitcoin">Termos associados ao Bitcoin</h1>
<h2 id="halving">Halving</h2>
<p>O Bitcoin foi projetado para ter uma quantidade fixa, isto é, uma quantidade fixa de <code>21 milhões de unidades</code>. Dessa forma, o Halving é o evento, acontecimento, no qual a recompensa gerada pela mineração de BTC é reduzida pela metade.</p>
<p>Ele ocorre aproximadamente a cada quatro anos ou a cada 210.000 blocos minerados, e foi projetado para controlar a inflação.</p>
<p>Esse mecanismo diminui gradativamente a quantidade de novos Bitcoins, aumentando sua escassez e seu valor ao longo do tempo.</p>
<p>A seguir, uma figura de ilustração do Halving.<br>
<img src="/_resources/6c657e4feb3d4eeb92dcb263d040bcbd.png" alt="a7b34ed3939f4d8e65d51656eeda6a16.png"></p>
<p>No ano de 2009, a recompensa em BTC recebida por um minerador, era de 50 BTCs, uma quantia alta, compensando a mineração e os custos dela.</p>
<p>Como mostrado na figura, a cada 4 anos aproximadamente, a recompensa cai pela metade, aumentando consideravelmente a escassez.</p>
<h2 id="carteiras-ou-wallets">Carteiras ou Wallets</h2>
<p>Existem 2 tipos principais de Wallets ou Carteiras, esses tópicos serão melhores abordados na parte de Autocustódia.</p>
<h3 id="cold-wallets">Cold wallets</h3>
<p>Diz respeito a Wallets offline, similar a uma carteira normal, que você guarda dinheiro físico. Dessa maneria, você não confia o seu dinheiro a um terceiro, espera-se que você confie em você mesmo, certo?</p>
<p>Exemplos de Cold Wallets:</p>
<ul>
<li>Paper wallet
<ul>
<li>Essa Wallet é um papel, literalmente. Esse papel é onde você guarda suas senhas ( seed phrases ).</li>
</ul>
</li>
<li>Metal wallet
<ul>
<li>Um metal, que voce fura ou faz marcações para transformar essas marcações nas senhas que dão acesso ao seu dinheiro.</li>
</ul>
</li>
<li>Hardware Wallet
<ul>
<li>Wallet guardada em um hardware, um dispositivo eletrônico, Ex: Ledger Nano X, Trezor Model T, Ledger Nano S Plus.....</li>
</ul>
</li>
</ul>
<h3 id="hot-wallets">Hot wallets</h3>
<p>São Carteiras Online, isto é, está em algum lugar da internet, podendo ser acessada, e corre perigo de ser hackeada ou sofrer ataques, uma vez que depende de um terceiro para armazenar os BTCs.</p>
<p>Alguns exemplos são:</p>
<ul>
<li>Armazenar em corretoras</li>
<li>Armazenar em aplicativos</li>
<li>Armazenar em arquivos sem a devida segurança implementada</li>
<li>Deixar a custódia na mão de empresas terceiras ou governo</li>
</ul>
<h1 id="criptografia-da-coisa">Criptografia da coisa</h1>
<p>Agora que você compreendeu os conceitos básicos de funcionamento da blockchain, como o uso de hashes, vamos abordar a parte da criptografia envolvida no Bitcoin. Essa explicação será apresentada de forma simplificada, evitando aprofundamentos técnicos para manter o artigo acessível.</p>
<p>A organização do Bitcoin, desde a senha até os endereços, são da seguinte maneira:</p>
<p><code>Seed Phrase - Chave Privada - Chave Pública - Endereço Bitcoin</code></p>
<h2 id="seed-phrase">Seed Phrase</h2>
<p>A Seed Phrase é o que você usa para recuperar sua carteira, o que da acesso a todos os seus BTCs e a todas as Private Keys. Ou seja, ela dá acesso a todos os seus fundos de todos os endereços. Atuando como uma chave mestra.</p>
<p>Ela é um conjunto de <code>12 ou 24 palavras</code><br>
Exemplo:</p>
<p><img src="/_resources/bca8c23029e5437088f4aecea7473445.png" alt="6e0943f51d4ae73cb5d37b4f12dcf15f.png"></p>
<p>É importante lembrar que a ordem dos elementos é crucial, e qualquer diferença, mesmo que seja apenas uma letra, altera completamente a carteira e os hashes derivados, conforme explicado na seção sobre Hash.</p>
<p>Além disso, uma <code>passphrase</code> pode ser utilizada para reforçar significativamente a segurança das suas chaves. A palavra-passe funciona como uma senha adicional, que complementa a Seed Phrase. Ou seja, trata-se de uma senha criada por você, que, ao importar a carteira, deve ser fornecida com as seed phrases. Caso contrário, o acesso aos seus bitcoins será negado.</p>
<p>Ela pode ser qualquer palavra que você escolher e atuará como a 25ª palavra ou 13ª, dependendo do número de palavras da sua seed. É possível usar qualquer palavra ou frase até 50 caracteres. Vale lembrar que caso você esqueça a passphrase, <strong>não poderá recuperar sua carteira, portanto, a sua palavra-passe é tão importante quanto as seeds</strong>.</p>
<h2 id="chave-privada-private-key">Chave Privada | Private Key</h2>
<p>Cada Private Key é única e pode ser usada para derivar uma única chave pública, que por sua vez gera um endereço Bitcoin exclusivo.</p>
<p>Assim, uma Private Key concede <code>acesso total para movimentar os fundos associados a um endereço específico</code>. A chave privada é como uma senha que desbloqueia o cofre guardando seu dinheiro que está armazenado em um endereço específico. Com isso em mente, jamais perca sua Chave Privada, ou perderá seus fundos.</p>
<p><img src="/_resources/6b14822ae7b5412097edba5300adb78a.png" alt="3a9f975a61205e693f14f93021a97b11.png"></p>
<p>Exemplo fictício usando a ferramenta do <a data-from-md title='https://www.iancoleman.net/bip39/' href='https://www.iancoleman.net/bip39/'>Iancoleman</a></p>
<p><img src="/_resources/40b995a8c7a44d84ae0d2792d35d8c80.png" alt="c60c6d39a6b9547c7bbdcb848ddf0d21.png"></p>
<h2 id="chave-pública-public-key">Chave Pública | Public key</h2>
<p>Ela é usada para gerar os endereços Bitcoin e verificar assinaturas digitais sem revelar a private key. E é usada para gerar o endereço de Bitcoin.</p>
<h2 id="endereço-bitcoin">Endereço Bitcoin</h2>
<p>Um endereço Bitcoin é uma identificação única usada para receber fundos em uma carteira Bitcoin.</p>
<p>Pode ser compartilhada, e é o meio usado para <code>receber transações</code>.</p>
<p>Exemplo de endereço:<br>
<code>bc1qar0srrr7g0gs5r24fz7r4l8y3g9s6c3q5rgd4w</code></p>
<h2 id="funcionamento-geral">Funcionamento Geral</h2>
<p>Adicionalmente, existe antes da Chave Privada, uma Chave Privada Mestra, ou Parent Private Key, que serve como raiz para derivar todas as outras chaves.</p>
<p>Na imagem a seguir, representa essa derivação:<br>
<img src="/_resources/d3a59babb9b44f34a3394e7430c40b8f.png" alt="f13fede5e846f0a18f1220c078998ad7.png"></p>
<p>Outra imagem que representa essa derivação é:<br>
<img src="/_resources/cb42ffa0c2f9404fa644d982d3870353.png" alt="0e79883e52b8b2805b3a4c21a013bef3.png"></p>
<p>Referência do Bitcoin Black Pill de Renato Amoedo e Alan Schramm.</p>
<h3 id="parte-técnica-da-derivação-das-chaves">Parte Técnica da derivação das chaves</h3>
<p>Esta seção fornece um resumo técnico, detalhando os algoritmos empregados em cada etapa do processo. Você pode optar por pular esta parte e seguir diretamente para o próximo capítulo.</p>
<p>Sendo assim, as seed phrases, que são um conjunto de 12 ou 24 palavras, dão origem a uma Private Key, usando o algoritmo de criptografia HMAC-SHA512.</p>
<p>Para gerar a Public Key, a Elliptic curve cryptography (ECC) é utilizada na Private Key, para saber mais sobre, consulte <a data-from-md title='https://en.wikipedia.org/wiki/Elliptic-curve_cryptography' href='https://en.wikipedia.org/wiki/Elliptic-curve_cryptography'>ECC Cryptography</a>.</p>
<p>E para a Public Key virar o endereço, tem-se o seguinte:<br>
<img src="/_resources/1d2c7a4d225b49a4a2993d149f9eecff.png" alt="05dba69c27d68b8d145e65b9137b675a.png"></p>
<p>Primeiro, é aplicado o algoritmo SHA256, seguido pelo algoritmo RIPEMD160 no resultado do SHA256 (conforme explicado na seção de Hash). Em seguida, o resultado é codificado usando o formato Base58Check.</p>
<h1 id="o-sistema-onde-vale-a-pena-ser-honesto">O sistema onde vale a pena ser honesto</h1>
<p>Nesse sistema, como mencionado no capítulo anterior, precisa <code>obedecer regras</code> previamente estabelecidas usando criptografia.</p>
<p>Quanto mais poder computacional for investido no Bitcoin, <code>mais recursos</code> um invasor em potencial precisa ter para atacar o projeto. Isto é, bilhões e bilhões de dólares.</p>
<p>Sabendo que os mineradores ganham recompensas em BTC, essa recompensa monetária também faz com que eles sigam as regras.</p>
<p>Digamos que um minerador encontre um hash vencedor para um bloco. Se ele enviar a solução com o bloco, mas quebrar as regras, o resto da rede Bitcoin, que atua como supervisora, rejeitará o bloco desse minerador específico. Ele então <code>perderá todo o BTC que deveria ter ganho</code>. É essa ameaça de perder as recompensas que mantém os mineradores honestos. Valendo mais a pena financeiramente ser honesto do que desonesto.</p>
<p>Como visto no conceito de hash, apenas alterando um número ou letra, todo o bloco pode ser comprometido, assim os blocos incorretos são invalidados e revertidos.</p>
<p>Para quebrar essa regra e poder burlar o sistema, um minerador teria que ser capaz de obter mais de <code>50% do poder computacional da rede</code>, assim, controlando a maioria dos nós que ajudam a supervisionar a rede. No entanto, obter mais de 50% da rede, é muito dificil, já que os sistemas estão todos distribuídos pelo planeta, e o número de nodes confiavéis são muito grandes. Isso demandaria muito dinheiro, que tornaria <code>inviavél</code> o ataque. Cada vez em que são realizadas transações, e o BTC é minerado, mais dificil é realizar esse ataque.</p>
<p>Sendo assim, devido à dificuldade monetária e de recursos tecnologicos, a probabilidade desse ataque é quase nulo, garantindo a segurança do Bitcoin.</p>
<h1 id="o-que-são-as-corretoras-e-como-comprar-btc">O que são as corretoras e como comprar BTC</h1>
<p>As corretoras de Bitcoin, também chamadas de exchanges de criptomoedas, são plataformas digitais que permitem a <code>compra, venda e troca</code> de Bitcoin e outras criptomoedas. Elas atuam como intermediárias entre compradores e vendedores, facilitando transações e geralmente cobrando uma taxa por seus serviços. As principais funções dessas corretoras incluem:</p>
<p><strong>Compra e Venda de Criptomoedas</strong>: Permitem que os usuários comprem Bitcoin utilizando moeda fiduciária (como dólar, euro, real) ou troquem por outras criptomoedas.</p>
<p><strong>Armazenamento Temporário</strong>: Muitas exchanges oferecem carteiras digitais para armazenar temporariamente os Bitcoins dos usuários. No entanto, por questões de segurança, é recomendado transferir os Bitcoins para uma carteira pessoal após a compra.</p>
<p><strong>Conversão entre Criptomoedas</strong>: Facilitam a conversão entre diferentes criptomoedas, como trocar Bitcoin por Ethereum ou outras altcoins.</p>
<p>Alguns exemplos de corretoras são:</p>
<ul>
<li><strong>Binance</strong>: Uma das maiores exchanges globais.<br>
<img src="/_resources/6691ef2c83d0402b9374f3e9e85d44dd.png" alt="49d5220ff11fbdf5b9bd36e3825343b0.png"></li>
<li><strong>Coinbase</strong>: Muito conhecida e voltada para iniciantes, com uma interface amigável.<br>
<img src="/_resources/96d2ef70911b46b6acb163171983e699.png" alt="0ce1bd645811271e45771680b2c6363a.png"></li>
<li><strong>NovaDAX</strong>: Exchange Brasileira.<br>
<img src="/_resources/51c82663b2f34e1b8386b970edd77553.png" alt="93c1d188d8ce5c3cf17da60f6602dfbd.png"></li>
</ul>
<hr>
<p>Vale salientar que existem muitas outras corretoras, essas são apenas algumas.</p>
<p>Uma grande facilidade e funcionalidade do Bitcoin é sua capacidade de se transformar em qualquer moeda de qualquer país. Isso significa que, caso você queira transformar seu BTC em USD, você pode, assim como em outras diversas moedas fiduciárias (FIAT).</p>
<p>Para comprar BTCs, basta criar uma conta em uma das corretoras mencionadas, aguardar a aprovação da conta, depositar dinheiro na corretora e então realizar a compra.</p>
<p>Após realizar a compra de BTCs ou Satoshis, essa quantia ficará armazenada na corretora, nesse viés é importante que ela seja enviada para uma carteira fria. Essa parte será abordada posteriormente no artigo.</p>
<h1 id="compreendendo-ataques-de-engenharia-social-e-de-hackers-para-se-previnir">Compreendendo Ataques de Engenharia Social e de Hackers para se previnir</h1>
<h2 id="doxxing">Doxxing</h2>
<p>Doxxing é a prática de expor informações pessoais de alguém, como nome, endereço, e outros dados confidenciais, sem consentimento, geralmente com o intuito de assediar, intimidar ou prejudicar essa pessoa.</p>
<p>Isso pode torná-los alvos de golpes, chantagens e ataques diretos, onde golpistas tentam extorquir as vítimas sob ameaça de expor mais detalhes ou prejudicar sua reputação.</p>
<p>Entretanto, caso a autocustódia seja feita de maneira correta, mesmo o indivíduo sendo alvo de Doxxing, ele não poderá ser roubado. Nesse viés, é essencial manter a posse de criptomoedas em sigilo e de maneira correta, proteger informações pessoais e adotar boas práticas de segurança digital no cotidiano.</p>
<h2 id="não-divulge-seus-endereços-e-não-diga-que-possui-bitcoin">Não divulge seus endereços, e não diga que possui Bitcoin</h2>
<p>Evite compartilhar publicamente seus endereços de Bitcoin ou mencionar que possui essa criptomoeda. Divulgar essa informação pode atrair atenção, incluindo ataques virtuais e tentativas de fraude.</p>
<p>A posse de Bitcoin é algo que deve ser tratado com discrição para garantir a sua segurança e <code>proteger seus ativos</code>. Mantenha suas carteiras e informações financeiras privadas, e utilize medidas de segurança como autenticação em duas etapas e senhas fortes em todas as suas contas.</p>
<p>Vale lembrar que as transações na Blockchain são todas públicas, mas a única forma de saber quem é o dono de tal endereço, é por meio de associações. Lembre-se, é <code>praticamente impossível</code> saber quem é o dono de um endereço de BTC, ao menos que algo seja <code>vazado ou falado</code> por parte do indivíduo. Não entregue essa informação para um terceiro, muito menos em redes sociais!.</p>
<h2 id="ataques-de-pishing">Ataques de Pishing</h2>
<p>Phishing é um tipo de golpe digital no qual os atacantes tentam enganar as pessoas para que revelem <code>informações confidenciais, como senhas, números de cartão de crédito ou dados pessoais</code>. Normalmente, isso é feito por meio de e-mails, mensagens de texto ou sites falsos que se passam por empresas ou serviços conhecidos, como bancos ou redes sociais.</p>
<p>Aprender a se proteger desses ataques não só é importante para uma autocustódia bem feita, mas é importante para a segurança digital do indivíduo.</p>
<p>Os golpistas criam páginas e mensagens que parecem legítimas, imitando o visual e o endereço de sites confiáveis, ou enviam email, mensagens, SMS, se passando por outro indivíduo ou organização.</p>
<p>A google criou um site que simula Pishings na internet, é importante praticá-lo, em poucos minutos é possível concluir o quiz.</p>
<p><a data-from-md title='https://phishingquiz.withgoogle.com' href='https://phishingquiz.withgoogle.com'>Quiz</a><br>
<img src="/_resources/36eb0120ab3841e9b87fa5ece032328c.png" alt="f35759330c9d7f043425aa51733e052d.png"></p>
<p>São apenas 10 questões, nas quais você afirma se o recebido é um pishing ( golpe ) ou legítimo.</p>
<p><img src="/_resources/c29a9cd842f843de81318e509ba0419e.png" alt="1638130fc4690e5ff7cf45a2f3fcb83b.png"></p>
<p>É de suma importância treinar essas questões para não se tornar um alvo fácil para atacantes, e ter seus dados comprometidos!.</p>
<p><strong>Não entre em sites que não sejam confiáveis</strong></p>
<p>Evitar sites desconhecidos é essencial para manter a segurança online. Sempre verifique a URL com atenção e certifique-se de que o endereço corresponde ao site que você quer acessar.</p>
<p>Muitos golpes usam domínios parecidos, trocando letras, como “microsoft” por “mlcrosoft”, para enganar usuários, assim, é necessário ficar atento ao link que você recebeu, pois você pode acabar acessando um site de um atacante e não o site original.</p>
<p><strong>Não baixe anexos de qualquer fonte</strong></p>
<p>É muito comum receber anexos via email, ou mensagens, mas tenha MUITO cuidado ao executar arquivos recebidos em anexo, pois podem conter vírus e ataques mal indesejados, especialmente se aberto em um computador.</p>
<p><strong>Atente-se a ligações ou mensagens se passando por outra pessoa</strong></p>
<p>Atualmente, com o avanço de IAs e da tecnologia, é possível receber ligações com a voz de um parente ou similar, também é muito comum os ataques no qual o atacante envia mensagem se passando por um parente, familiar ou amigo, pedindo informações ou dinheiro.</p>
<p>Não dê brecha para esse tipo de ataque, fique esperto!.</p>
<p><strong>Evite salvar senhas ou contas em lugares inseguros</strong></p>
<p>Não salve senhas em navegador, além disso, não salve senhas em aplicativos terceiros ou de anotação, sempre é possível o terceiro sofrer um ataque Hacker. Ademais, você também pode ser atacado virtualmente.</p>
<p><strong>Não entregue contas a terceiros</strong></p>
<p>Adicionalmente, evite compartilhar conta com outras pessoas, essas contas podem ser hackeadas, mesmo que não seja por mal da outra pessoa, ela provavelmente não tem o mesmo conhecimento de proteção de dados que você aprendeu nesse artigo.</p>
<p>Recomende esse artigo para outras pessoas!.<br>
A salvação é individual, mas ao compartilhar, você cria oportunidade para que o outro se salve!.</p>
<h2 id="vazamentos-de-dados">Vazamentos de Dados</h2>
<p>Vazamentos de dados em empresas terceirizadas são incidentes em que informações pessoais dos usuários, como emails, senhas e até dados financeiros são expostas devido a <code>falhas de segurança</code> nos sistemas de uma organização parceira. Esse tipo de ocorrência pode ter várias origens, como brechas na infraestrutura digital, ataques cibernéticos sofisticados ou até mesmo erro humano, e coloca os usuários em risco de fraudes, tentativas de phishing e roubo de identidade.</p>
<p>Um dos impactos mais comuns desses vazamentos é o comprometimento de endereços de email. Ferramentas como o <a data-from-md title='haveibeenpwned.com' href='haveibeenpwned.com'>Have I Been Pwned</a> permitem que os usuários verifiquem se seus emails foram expostos em algum vazamento conhecido. O processo é simples: ao inserir o endereço de email, o site informa se aquele dado foi incluído em algum incidente de segurança. Em casos de exposição confirmada, recomenda-se a troca imediata das senhas e a ativação de autenticação em duas etapas para reforçar a segurança das contas.</p>
<p>Exemplo de email teste comprometido:</p>
<p><img src="/_resources/d4f89c1d4084494a953902b65ef1646b.png" alt="19758dab5300bf2a0b7d0da76ed72fec.png"></p>
<p>Vazamentos em que esse email está presente:<br>
<img src="/_resources/8904d06735ae43d19261fbcff1d944d6.png" alt="a9529955e2478b73d07652ae84edaa37.png"></p>
<p>Caso seu email não esteja em nenhum vazamento, o site retornará o seguinte:<br>
<img src="/_resources/7d5c8a26583e47a0913c1cb2089ec037.png" alt="ccdd6df57c3fd90a232022cc18bbb8ee.png"></p>
<p>Esses vazamentos evidenciam a importância de se adotar medidas preventivas e práticas de segurança, tanto por parte das empresas quanto dos próprios usuários.</p>
<p>Adote MFA nas suas contas, e use senhas fortes, jamais use senhas como &quot;123456&quot; ou &quot;senha&quot;.</p>
<p>Algumas recomendações de senha:</p>
<ul>
<li>Pelo menos 8 caracteres</li>
<li>Conter número</li>
<li>Conter Maiúsculas e minúsculas</li>
<li>Conter pelo menos um símbolo</li>
<li>Não reutilize senhas</li>
</ul>
<h2 id="roubos">Roubos</h2>
<p>Assim como os roubos virtuais, os roubos físicos também podem causar sérios prejuízos. Nunca deixe informações sensíveis, como senhas e endereços de e-mail, armazenadas em seu dispositivo eletrônico. Isso ajuda a proteger esses dados caso o aparelho caia nas mãos de criminosos.</p>
<h2 id="ataques-a-corretoras">Ataques a Corretoras</h2>
<p>Os casos de ataques a corretoras de criptomoedas, como Mt. Gox, ilustra claramente os riscos de deixar bitcoins e outros criptoativos armazenados em corretoras. Em 2014, a Mt. Gox, então uma das maiores corretoras de Bitcoin do mundo, foi alvo de um ataque que resultou na perda de cerca de <code>850.000 bitcoins</code>. O incidente expôs a vulnerabilidade da plataforma e culminou em sua falência, deixando milhares de investidores com prejuízos irreparáveis.</p>
<p>Esses casos reforçam a importância de manter criptoativos fora das corretoras sempre que possível. Deixar bitcoins em uma corretora significa confiar totalmente na segurança da empresa — e, como esses ataques demonstram, até mesmo grandes corretoras estão sujeitas a falhas que podem levar a prejuízos imensos. Para reduzir os riscos, a recomendação é transferir os criptoativos para carteiras pessoais seguras, como as carteiras frias (cold wallets), que mantêm os ativos offline, fora do alcance de hackers.</p>
<p>Depender da segurança de corretoras, especialmente em um setor ainda em desenvolvimento e repleto de ataques hackers acontecendo todo momento, pode representar um grande risco financeiro. A segurança digital é um processo contínuo e que ainda está em fase de implementação em muitas empresas. A maturidade nesse campo é algo que se desenvolve ao longo do tempo, à medida que práticas e tecnologias avançam. Jamais confie em terceiros!.</p>
<h1 id="a-autocustódia">A autocustódia</h1>
<p>Agora que você já sabe se proteger de inúmeros ataques, vem a parte mais importante, a autocustodia. Faça uma autocustódia ruim e seja roubado.</p>
<p>Nessa parte, o foco será em carteiras frias, de modo que você leitor termine de ler esse artigo sabendo fazer sua autocustódia corretamente de maneira offline e segura.</p>
<p>Devido ao custo associado as carteiras conhecidas como <strong>Hardware Wallet</strong>, o artigo não consta com a demonstração delas.</p>
<h2 id="conceitos-básicos">Conceitos Básicos</h2>
<p>No tópico de autocustódia, o mais importante é guardar de maneira segura suas Seed Phrases, isto é, aquelas 12 ou 24 palavras que dão acesso total a sua carteira.</p>
<p>Tendo isso em vista, existem algumas maneiras que você pode fazer a autocustódia, algumas delas serão abordadas aqui, lembrando que você pode diversificar e utilizar outras técnicas/conhecimentos para aumentar a segurança de sua carteira.</p>
<p>É importante destacar que os aplicativos e softwares de carteira podem gerar para você uma seed phrase (ou palavras de recuperação). Essas palavras são essenciais, pois funcionam como a chave mestra que permite acessar e recuperar sua carteira em qualquer dispositivo. Por isso, é crucial armazená-las com extremo cuidado e segurança.</p>
<p>Formas recomendadas de armazenamento das palavras de recuperação:</p>
<ul>
<li>
<p>Paper Wallet:</p>
<ul>
<li>Anote as palavras manualmente em papel, caderno ou outro meio físico.</li>
<li>Certifique-se de armazenar em um local seguro e protegido contra umidade, fogo ou extravio.</li>
<li>Você pode dividir as seed phrases e deixar em casas de parentes/familiares, como, por exemplo, deixar 4 palavras com um parente, 4 palavras com outro parente, e 4 palavras com um parente final, totalizando 12 palavras.</li>
</ul>
</li>
<li>
<p>Metal Wallet:</p>
<ul>
<li>Grave ou inscreva as palavras em um pedaço de metal (como aço inoxidável).</li>
<li>Essa abordagem é resistente a danos físicos, como fogo ou água, tornando-a uma opção extremamente durável.</li>
</ul>
</li>
<li>
<p>Hardware Wallet:</p>
<ul>
<li>Pode ser um Pendrive. Sempre encripte seus dados!</li>
<li>Utilize dispositivos dedicados, como hardware wallets, que podem armazenar suas palavras de forma digital e protegida.</li>
<li>Esse tipo de dispositivo oferece segurança adicional, com proteção contra ataques online.</li>
</ul>
</li>
</ul>
<p>Dicas de segurança adicionais:</p>
<ul>
<li>Evite armazenar as palavras digitalmente, como em fotos, notas no celular ou serviços em nuvem, pois esses meios estão sujeitos a acessos não autorizados.</li>
<li>Considere manter backups em locais separados para maior proteção.</li>
<li>Nunca compartilhe suas palavras de recuperação com ninguém, nem mesmo com serviços ou &quot;suporte técnico&quot; não confiáveis.</li>
</ul>
<p>Lembre-se: <strong>a segurança das palavras de recuperação é tão importante quanto a segurança do próprio dispositivo onde sua carteira está armazenada</strong>. Elas são a garantia de acesso aos seus ativos digitais em caso de perda ou falha do dispositivo original. <strong>É de suma importância salvar suas palavras de recuperação de maneiras diversas, caso algum backup seja perdido, ainda existem outros!</strong>.</p>
<h2 id="bluewallet-com-celular-velho">Bluewallet com celular velho</h2>
<p>Primeiramente, é importante compreender o que é a BlueWallet. Trata-se de uma carteira de criptomoedas de código aberto projetada para facilitar o gerenciamento de ativos digitais, como o Bitcoin. Como uma solução segura e confiável, a BlueWallet permite que os usuários enviem, recebam ou simplesmente visualizem seus saldos de maneira prática e intuitiva.</p>
<p><img src="/_resources/148e28624cdd453eb5f2bbb98d9fee49.png" alt="5b874bb5047e1a1367599f11796d965b.png"></p>
<p>Entre os principais recursos da BlueWallet, destaca-se a possibilidade de importar carteiras existentes, como aquelas geradas por outras plataformas ou dispositivos, bem como a opção de criar novas carteiras diretamente no aplicativo.</p>
<p><strong>Figura de demonstração de uma carteira dentro da bluewallet:</strong><br>
<img src="/_resources/14c0fc2a5bca4152b70a11ba8e302dd3.png" alt="c0c279b94640b5e6b3bd49c6d6dc5783.png"></p>
<p>A BlueWallet foi projetada para funcionar em dispositivos móveis, oferecendo uma interface amigável e suporte tanto para sistemas Android quanto iOS. Para instalar o aplicativo, os usuários podem fazer o download diretamente da Play Store (no caso do Android) ou da App Store (para iOS). Além disso, o APK oficial está disponível no <a data-from-md title='https://github.com/BlueWallet/BlueWallet' href='https://github.com/BlueWallet/BlueWallet'>repositório do GitHub da BlueWallet</a>, permitindo que os usuários revisem o código-fonte e instalem o aplicativo manualmente, caso prefiram.</p>
<hr>
<p>Diante disso, a recomendação é adquirir ou utilizar um celular antigo, recém-formatado, exclusivamente para o propósito de armazenar sua carteira de criptomoedas. Essa abordagem aumenta significativamente a segurança dos seus fundos digitais.</p>
<p><strong>Passo a passo simplificado</strong>:</p>
<ul>
<li>Primeiro, será necessário instalar a BlueWallet no celular. Você pode transferir o arquivo APK oficial para o dispositivo e instalá-lo manualmente ou fazer o download diretamente pela Play Store.</li>
<li>Após a instalação, abra o aplicativo e crie uma nova carteira de Bitcoin (BTC).</li>
</ul>
<p><strong>Cuidados importantes</strong>:</p>
<ul>
<li>Este celular deve ser exclusivamente dedicado ao armazenamento da carteira. NÃO use o dispositivo para qualquer outra finalidade.</li>
<li>Não instale aplicativos de terceiros, que podem introduzir vulnerabilidades.</li>
<li>Sempre que possível, mantenha o celular desconectado da internet, exceto nos momentos em que precisar sincronizar ou realizar transações.</li>
<li>Armazene o dispositivo em um local extremamente seguro e de sua total confiança, já que ele conterá sua carteira, a chave que possibilitará o envio e gerenciamento de seus bitcoins.</li>
</ul>
<h3 id="passo-a-passo-detalhado">Passo a passo detalhado</h3>
<p>Depois que você instalar a carteira bluewallet no seu celular velho, a primeira tela deve ser a seguinte:</p>
<p><img src="/_resources/08658dc89de84f469f235869cb953e9d.png" alt="d06f7a383b9c8fa977b6cbde99295111.png"></p>
<p>Nesse momento, não existe nenhuma carteira registrada, assim, clique em &quot;Add now&quot;.</p>
<p>Na proxima etapa, o aplicativo pedirá o nome da wallet, você pode colocar o nome que quiser. Ademais, se atente para escolher a opção &quot;Bitcoin&quot;.</p>
<p><img src="/_resources/efbb5b0650024a4f94e64d7a826b24d1.png" alt="c0b8fdcd67abe1188f4f8557eefaa1e1.png"></p>
<p>Na proxima parte, certifique-se que a opção &quot;Bip84&quot; está selecionada. Essa opção diz respeito ao tipo de carteira, sendo a bip84 mais segura e com taxas de transação menores.</p>
<p><img src="/_resources/78aa8c05410f4f3986f2eefbd4ed0137.png" alt="b668ed0955a36a4478de5ea1379eb3e2.png"></p>
<p>Nessa parte, você pode escolher criar ou importar sua carteira. Caso você já tenha uma carteira, basta clicar em importar wallet e colocar as suas &quot;Seed Phrases&quot; corretamente, e sua carteira será importada. Adicionalmente, também é possível adicionar uma private key de um endereço específico para ser importada.</p>
<hr>
<p>Assumindo que você não tem uma carteira, clique em &quot;Create&quot;.</p>
<p>A próxima seção mostra as &quot;Seed Phrases&quot; geradas pelo aplicativo, <strong>GUARDE com extremo cuidado</strong>, em um papel ou usando as outras formas já citadas no artigo, pois se houver a perda dessas palavras, <strong>todos os seus fundos serão perdidos</strong>.</p>
<p><img src="/_resources/91ea1c460f6d4d99b35b3b5ec2117a2e.png" alt="b8ca91c4ea7422df0562e7be491baec5.png"></p>
<p>Depois da carteira ter sido criada, ela aparecerá como uma CAIXA AZUL.</p>
<p><img src="/_resources/f83d0bf3ead14c50988c24cd327ce105.png" alt="1e3ea5a65ef9f9ad33776d13a9bf0c90.png"></p>
<p>Se a caixa tiver cor azul, significa que você tem acesso total a carteira, isto significa poder enviar fundos. Se a caixa for cinza, você só pode visualizar os fundos.</p>
<p><strong>PRONTO! Sua carteira foi criada! Fácil, não?</strong></p>
<p>Para enviar ou receber fundos, clique na caixa azul, e depois clique em &quot;Enviar&quot; ou &quot;Receber&quot;</p>
<p><img src="/_resources/9b147906aaa7440bb48965c32f854b84.png" alt="3c7cdc629d2e19b3aee40fff2c272f4f.png"></p>
<p><strong>Observações</strong>:</p>
<ul>
<li>Esse celular será responsável por fazer o envio de quantias, esse celular deve ser mantido guardado</li>
<li>Não leve esse celular para lugares públicos, mantenha-o em sua casa ou em um lugar seguro guardado</li>
<li>Ademais, o seu <code>celular principal</code> apenas irá conseguir <strong>VISUALIZAR</strong> os fundos, ele não poderá enviar BTC. Isso é uma medida de segurança.</li>
</ul>
<h4 id="visualizando-seus-fundos-no-celular-principal-carteira-watch-only">Visualizando seus fundos no celular principal | Carteira Watch-Only</h4>
<p>Como dito antes, o seu celular principal só poderá visualizar os fundos da sua carteira. Isso significa que o seu celular principal terá uma <code>Carteira Watch-Only</code>.</p>
<p>Como fazer isso?</p>
<p>Basta importar a chave &quot;XPUB&quot; da sua carteira. A chave xpub é a chave pública geral que permite visualizar os BTCs guardados em todos os endereços, isto é, visualizar o dinheiro da carteira toda.</p>
<p>No seu celular antigo/offline, entre na bluewallet, entre na carteira, clique nos &quot;3 pontinhos&quot; no canto superior direito da tela.</p>
<p><img src="/_resources/9b147906aaa7440bb48965c32f854b84.png" alt="3c7cdc629d2e19b3aee40fff2c272f4f.png"></p>
<p>Logo em seguida clique em &quot;Show wallet XPUB&quot;</p>
<p><img src="/_resources/16980028cc464d4e924ea3dafb21be77.png" alt="0fbac36871af456b7b1d0b60e7eb6fcf.png"></p>
<p><strong>Exemplo da XPUB</strong>:</p>
<p><img src="/_resources/8fe7af32857c45e5a545bdcab5027daf.png" alt="08814bb1bceb7524275de0e1b8759cd0.png"></p>
<p>Basta escanear o QRCode gerado ou copiar o valor e importar no seu celular principal, assim você terá uma carteira de apenas visualização ( Watch Only ).</p>
<p><strong>Exemplo de carteira Watch-Only</strong>:</p>
<p><img src="/_resources/81adbf697cea4a87b4fcefd8c5270c63.png" alt="536ea4395ced37e89c8193e03df02a0d.png"></p>
<h2 id="tails-electrum">Tails - Electrum</h2>
<p>Primeiramente, é fundamental compreender como funciona o sistema operacional <strong>Tails</strong>. O Tails é um sistema operacional focado em privacidade e segurança, projetado para não armazenar permanentemente nenhum dado ou atividade realizada nele. Ele é executado diretamente de um pendrive, garantindo que, ao reiniciar o sistema, <code>todas as informações temporárias sejam apagadas</code>.</p>
<p>Já a <strong>Electrum</strong> é uma carteira de criptomoedas leve e confiável, compatível com o Tails, que pode ser usada para gerenciar e assinar transações de forma segura.</p>
<h3 id="como-funciona">Como funciona</h3>
<ol>
<li>
<p><strong>Instalação do Tails:</strong></p>
<ul>
<li>Instale o sistema operacional Tails em um pendrive dedicado.</li>
<li>Configure o recurso de <strong>armazenamento permanente criptografado</strong>, protegido por uma senha, para salvar informações essenciais, como a carteira Electrum.</li>
</ul>
</li>
<li>
<p><strong>Configuração da carteira:</strong></p>
<ul>
<li>No Tails, instale a Electrum e configure-a com segurança, protegendo-a com uma senha forte.</li>
</ul>
</li>
<li>
<p><strong>Processo de transações:</strong></p>
<ul>
<li>Use a Electrum no celular para criar transações e exportar os dados necessários.</li>
<li>No Tails, importe esses dados para a Electrum, assine as transações offline, e depois exporte novamente para transmiti-las pela carteira no celular.</li>
</ul>
</li>
</ol>
<hr>
<ul>
<li>O Tails opera de forma isolada, não armazenando nenhum dado não autorizado e protegendo contra malware e ataques online.</li>
<li>O <strong>armazenamento permanente criptografado</strong> no Tails garante que apenas você tenha acesso às informações salvas.</li>
<li>Dividir o processo de transações entre o celular e o Tails adiciona uma camada extra de segurança, dificultando acessos não autorizados.</li>
</ul>
<h3 id="cuidados-importantes">Cuidados importantes</h3>
<ul>
<li>Certifique-se de que o pendrive usado para o Tails seja dedicado exclusivamente a esse propósito.</li>
<li>Nunca conecte o Tails à internet enquanto estiver assinando transações, para evitar possíveis vetores de ataque. Conecte-se a internet apenas para atualizar o saldo da carteira fria.</li>
<li>Proteja tanto o pendrive quanto as senhas envolvidas, armazenando-os em locais seguros e de confiança.</li>
</ul>
<p>Esse método combina privacidade e segurança, sendo uma excelente opção para usuários que desejam reforçar a proteção de seus ativos digitais. Porém, exige mais estudo e complexidade.</p>
<p>Dada a complexidade maior desse tipo de armazenamento, segue uma recomendação de um tutorial completo feito pelo canal Bitcoinheiros.</p>
<p><a data-from-md title='https://www.youtube.com/watch?v=abXkgXQ8BvI' href='https://www.youtube.com/watch?v=abXkgXQ8BvI'>Tutorial Completo do Bitcoinheiros</a></p>
<h2 id="assinando-transações">Assinando Transações</h2>
<p>De forma simples, assinar uma transação é o processo de confirmar e autenticar que você é o verdadeiro proprietário dos fundos envolvidos na transação. É uma maneira de provar que você possui a chave privada associada à carteira que detém os ativos, garantindo que somente você pode autorizar o envio do dinheiro.</p>
<p>Essa assinatura funciona como uma garantia criptográfica de que a transação é legítima e foi aprovada por quem realmente tem controle sobre os fundos, evitando fraudes ou acessos não autorizados.</p>
<p><strong>Quando você for enviar BTC para alguém, o processo não envolve enviar diretamente da sua carteira fria. Em vez disso, você utilizará uma outra carteira, como uma Watch-Only, para criar, preparar e enviar a transação. Após isso, a assinatura será realizada com sua carteira fria.</strong></p>
<p>Ou seja, em um exemplo fictício usando a BlueWallet, serão usados 2 celulares.</p>
<ol>
<li>Celular de Carteira Fria, que só conecta na internet para atualizar os fundos e assinar transações</li>
<li>Celular principal contendo Watch-Only, que fará o envio da quantia e usará a carteira fria para assinar a transação.</li>
</ol>
<p>No caso do Tails e Electrum:</p>
<ol>
<li>Carteira Fria no Pendrive dentro do tails irá assinar</li>
<li>Carteira Electrum no celular irá enviar a transação, e usar a carteira fria para assinar.</li>
</ol>
<h3 id="assinando-com-a-bluewallet-enviando-transação-com-cold-wallet-blue-wallet">Assinando com a Bluewallet | Enviando transação com Cold Wallet Blue Wallet</h3>
<p>Para esse procedimento, você precisará de:</p>
<ol>
<li>Carteira Fria em celular velho</li>
<li>Carteira Watch-Only em celular normal</li>
</ol>
<p><a data-from-md title='https://www.youtube.com/watch?v=BI0oo1BDNbg' href='https://www.youtube.com/watch?v=BI0oo1BDNbg'>Vídeo completo feito pela Bluewallet - 1 minuto</a></p>
<p>No celular contendo a Watch-Only, clicar em enviar e digitar a quantidade, taxa e endereço a ser enviado a quantia.</p>
<p><img src="/_resources/00d70c469ee54d028421c94421faca93.png" alt="d9b3fc9bf647fe9c65969c460a17ed09.png"></p>
<p>No celular velho, clicar em enviar, depois nos 3 pontinhos e clicar em &quot;Assinar uma transação&quot;</p>
<p><img src="/_resources/9b9386f11146481bb3ba9d16e79a45a7.png" alt="b896dda0cb2697da9fcab889798d7d58.png"></p>
<p>Imagem de demonstração da transação assinada no celular velho:</p>
<p><img src="/_resources/ae7a34879c654ac0b70a8767b2d6c873.png" alt="745a4573ffa3b2af65b3a082c42be1cc.png"></p>
<p>Agora, basta ler o QRCode da transação assinada do celular velho, usando o celular normal e proceder normalmente.</p>
<p><img src="/_resources/2f4697000a51476da4a4702cf13680ff.png" alt="4184318a5469660d9e8309763c12288a.png"></p>
<h3 id="assinando-com-o-tails-e-electrum-enviando-transação-com-carteira-electrum">Assinando com o Tails e Electrum | Enviando transação com Carteira Electrum</h3>
<p>Para esse procedimento, você precisará de:</p>
<ol>
<li>Carteira Fria no Tails</li>
<li>Carteira Quente Electrum no celular como Watch-Only</li>
</ol>
<p><a data-from-md title='https://www.youtube.com/watch?v=yGYYgBZTC_o' href='https://www.youtube.com/watch?v=yGYYgBZTC_o'>Tutorial Completo de como assinar</a></p>
<p>Etapas de envio da transação:</p>
<ol>
<li>Escanear QRCode de endereço usando Electrum do celular, ou digitar/colar o endereço de envio</li>
<li>Digitar quantia e escolher taxa</li>
<li>Carregar a transação e assinar na Carteira Fria Electrum dentro do Tails</li>
</ol>
<p>A primeira etapa é clicar em enviar, e colocar o endereço de envio.</p>
<p><img src="/_resources/bee81a9c45d146679af50d5f70d32ef3.png" alt="60dc7646084ad3707dba8ceef1dfe392.png"></p>
<p>Logo em seguida, depois de inserir a quantidade, insira a taxa de transação.</p>
<p><img src="/_resources/d0f128caf7ba4747a65f74ab613f69f0.png" alt="8d2003686f607a58596be90910ac9973.png"></p>
<p>Após finalizar, compartilhe a transação para sua Electrum dentro do Tails, carregue usando o QRCode ou texto.</p>
<p><img src="/_resources/4936b71c10524b7d969d9c9c846f57cf.png" alt="c9775a4b7b7f7d6b52c9272e28f8b039.png"></p>
<p>Dentro da Electrum do tails, procure a opção de &quot;Carregar transação&quot;, e selecione a forma de carregar conforme a facilidade.</p>
<p><img src="/_resources/d3b02250d54a403381fc76b1848bb342.png" alt="95e7544f30eb63ad41bf292bbd4a9e2b.png"></p>
<p>Agora, basta assinar a transação, clicando no botão &quot;assinar&quot;.</p>
<p><img src="/_resources/2852da5da35542b98c5af19e1aef449e.png" alt="5e0ecf916bc1a34640954d3e664ecd66.png"></p>
<p>Agora que a transação já está assinada, a transação pode ser exportada de volta para o celular.</p>
<p><img src="/_resources/450a733d720747b7b096808e9ba6156e.png" alt="e10bacff09999eb7170e77936243162f.png"></p>
<p>Basta carregar a nova transação assinada, escaneando o QRCode com o celular ( Carteira Quente ) e clicar em &quot;Transmitir&quot;, e sua transação será enviada para a Blockchain.</p>
<p><img src="/_resources/415bd2cf717a45a886962dba534f7015.png" alt="fe96c9acec7a18a4998559d6bf539667.png"></p>
<p><strong>Observações:</strong></p>
<ul>
<li>A carteira que assinou a transação está segura</li>
<li>Em algum momento é preciso deixar a carteira fria online, apenas para atualizar o saldo.</li>
</ul>
<p><strong>Agora você é capaz de criar uma carteira, fazer sua autocustódia e assinar transações! Parabéns!</strong></p>
<h2 id="segregação-de-endereços">Segregação de Endereços</h2>
<p>A segregação de endereços em Bitcoin refere-se à prática de utilizar diferentes tipos de endereços para finalidades específicas, a fim de melhorar a segurança, privacidade e eficiência no gerenciamento de ativos. Essa separação é importante, pois ajuda a organizar os fundos, reduzir riscos e otimizar transações.</p>
<p>Alguns exemplos fictícios são: Você pode ter um endereço exclusivo para receber doações em Bitcoin, garantindo que esses fundos sejam facilmente rastreados e separados das suas economias pessoais.</p>
<p>Além disso, você pode separar fundos para a família, você pode usar um endereço específico somente para economias ou despesas conjuntas. Isso ajuda a controlar melhor os recursos familiares, evitando misturar essas finanças com as suas próprias.</p>
<p>Esse tipo de segregação facilita o acompanhamento de entradas e saídas, garantindo que cada categoria de fundo seja mantida de forma organizada e segura.</p>
<p>Ou seja, segregar endereços é separar os endereços para cada função, um endereço X serve para armazenar dinheiro para um parente, enquanto um endereço Y serve somente para armazenar doações e o endereço Z serve para armazenar uma parte do salário.</p>
<h1 id="prós-e-contras">Prós e contras</h1>
<h2 id="prós">Prós:</h2>
<h3 id="imune-a-inflação">Imune a inflação</h3>
<p>Projetada para garantir a escassez e proteger o valor da moeda contra a inflação, os BTC tem sua quantia fixa, ou seja, não é possível produzir mais BTCs que o limite de 21 milhões de unidades, garantindo e preservando o seu valor.</p>
<h3 id="tende-a-valorizar">Tende a valorizar</h3>
<p>Como dito na descrição sobre o Halving, a cada ~4 anos a recompensa por BTC cai pela metade, aumentando o seu valor com o passar do tempo.</p>
<h3 id="protege-contra-perseguições-políticas">Protege contra perseguições políticas</h3>
<p>O Bitcoin é imune a perseguições políticas devido à sua descentralização e ao fato de não ser controlado por nenhuma entidade central. Essa característica permite que indivíduos realizem transações sem a necessidade de um intermediário, dificultando o bloqueio ou confisco de ativos por governos autoritários.</p>
<p>Além disso, o Bitcoin oferece um nível de anonimato. Embora as transações sejam registradas em uma blockchain pública, as identidades dos usuários não estão diretamente ligadas a suas carteiras. Isso ajuda a proteger aqueles que podem ser alvo de repressão por suas opiniões ou atividades.</p>
<p>A acessibilidade global do Bitcoin também contribui para sua resistência a perseguições políticas. Qualquer pessoa com acesso à internet pode usá-lo, permitindo que indivíduos em regimes opressivos preservem e transfiram seu valor sem interferência governamental.</p>
<p>Essas características tornam o Bitcoin uma ferramenta eficaz para evitar perseguições políticas e manter a autonomia financeira.</p>
<h3 id="protege-de-roubos-do-estado">Protege de &quot;roubos&quot; do estado</h3>
<p>No Brasil, no dia 16 de março de 1990, o governo anunciou o confisco de contas bancárias que continham valores superiores a 50 mil cruzados novos (moeda que estava em vigor na época). Essa medida resultou na apreensão de cerca de 80% dos saldos nas contas bancárias dos brasileiros, impactando diretamente a vida de milhões de pessoas.</p>
<p>Seja dinheiro em conta corrente, conta poupança ou em aplicações financeiras, as pessoas foram &quot;roubadas&quot; pelo Governo.</p>
<p>Caso sua reserva monetária seja feita usando BTC, e de maneira correta, você torna-se imune a esse tipo de acontecimento!.</p>
<h3 id="protege-de-congelamento-bancário">Protege de congelamento bancário</h3>
<p>Caso sua conta do banco seja bloqueada por algum motivo, isso faz com que você não consiga usar os fundos. Se armazenado em BTC, isso jamais irá acontecer.</p>
<h2 id="contras">Contras</h2>
<p>Vale lembrar que <strong>Bitcoin não é um investimento</strong>, Bitcoin é reserva de valor, proteção da familia, liberdade, patrimônio verdadeiro.</p>
<h3 id="volátil-no-curto-prazo">Volátil no curto prazo</h3>
<p>Um dos aspectos que pode ser categorizado como &quot;contra&quot; do Bitcoin, é sua alta volatilidade no curto prazo. Isso significa que o preço do Bitcoin pode subir ou cair significativamente em um curto período.</p>
<p>Fatores como decisões de governos sobre regulamentação, declarações de figuras públicas e mudanças no cenário econômico global podem desencadear oscilações significativas. Por essa razão, quem opta por comprar Bitcoin precisa estar preparado para lidar com essa incerteza e adotar uma visão de longo prazo para equilibrar os riscos associados. Mas lembre-se, a incerteza é somente no curto prazo, no longo prazo o valor do BTC só tende a aumentar.8</p>
<h3 id="taxas-de-transação">Taxas de transação</h3>
<p>Vale ressaltar que pagar as taxas não é uma questão grave. Para fazer envios de BTC, precisa-se pagar taxa de envio, essa taxa depende do período, mas em geral, ela não é alta.</p>
<h3 id="golpes-e-ataques-de-engenharia-social">Golpes e ataques de engenharia social</h3>
<p>Assim como golpes com objetivo de chegar a contas bancárias, cartões, etc. Existem golpes associados ao BTC, a maioria deles consiste em ataques de engenharia social, já abordados nesse artigo. Se você chegou até aqui, já tem uma boa base de como se proteger desse tipo de atacante!.</p>
<h3 id="como-tudo-na-vida-precisa-estudar">Como tudo na vida, precisa estudar</h3>
<p>Estudar definitivamente não é um ponto negativo, mas coloquei aqui porque muitas pessoas o veem assim. A verdade é que quem não acompanha o progresso da sociedade e da tecnologia acaba ficando para trás. Você ficará para trás?</p>
<h1 id="finalização-e-ferramentas-para-aprender">Finalização e ferramentas para aprender</h1>
<p>Caso você queira mexer mais com a criptografia do BTC, como private key, public key, gerar chaves para teste, manusear endereços e praticar o funcionamento, utilize a ferramenta do <a data-from-md title='https://iancoleman.io/bip39/' href='https://iancoleman.io/bip39/'>Iancoleman Bip 39</a>. Essa ferramenta pode ser baixada e executada de maneira local, para não utilizar nenhum tráfego na internet.</p>
<h1 id="fim-do-artigo">Fim do artigo</h1>
<p>Deseja me doar alguma quantia?<br>
Aqui está um endereço de BTC para que você possa fazer alguma doação:<br>
<code>bc1qpxm904737hkwp4fqpqc2x6q3yllgk3mu9lxwp9</code></p>
<h1 id="referências">Referências</h1>
<ul>
<li><a data-from-md title='https://ocp.news/economia/50-reais-em-btc-em-2009-teriam-valor-bilionario' href='https://ocp.news/economia/50-reais-em-btc-em-2009-teriam-valor-bilionario'>https://ocp.news/economia/50-reais-em-btc-em-2009-teriam-valor-bilionario</a></li>
<li><a data-from-md title='https://www.oreilly.com/library/view/mastering-bitcoin-2nd/9781491954379/ch04.html' href='https://www.oreilly.com/library/view/mastering-bitcoin-2nd/9781491954379/ch04.html'>https://www.oreilly.com/library/view/mastering-bitcoin-2nd/9781491954379/ch04.html</a></li>
<li><a data-from-md title='https://bitcoin.org/bitcoin.pdf' href='https://bitcoin.org/bitcoin.pdf'>https://bitcoin.org/bitcoin.pdf</a></li>
<li><a data-from-md title='https://blog.areabitcoin.com.br/transacao-de-bitcoin/' href='https://blog.areabitcoin.com.br/transacao-de-bitcoin/'>https://blog.areabitcoin.com.br/transacao-de-bitcoin/</a></li>
<li><a data-from-md title='https://www.bitcoin.com/get-started/how-bitcoin-transactions-work/' href='https://www.bitcoin.com/get-started/how-bitcoin-transactions-work/'>https://www.bitcoin.com/get-started/how-bitcoin-transactions-work/</a></li>
</ul>
</div></div>
					</body>
				</html>
