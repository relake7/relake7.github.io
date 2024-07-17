<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>Time to Meet the Real Me </title><style>
/* cspell:disable-file */
/* webkit printing magic: print all background colors: black; */
html {
	-webkit-print-color-adjust: exact;
}
* {
	box-sizing: border-box;
	-webkit-print-color-adjust: exact;
}

html,
body {
	margin: 0;
	padding: 0;
}
@media only screen {
	body {
		margin: 2em auto;
		max-width: 900px;
		color: rgb(55, 53, 47);
	}
}

body {
	line-height: 1.5;
	white-space: pre-wrap;
}

a,
a.visited {
	color: inherit;
	text-decoration: underline;
}

.pdf-relative-link-path {
	font-size: 80%;
	color: #444;
}

h1,
h2,
h3 {
	letter-spacing: -0.01em;
	line-height: 1.2;
	font-weight: 600;
  color:white;
	margin-bottom: 0;
}

.page-title {
	font-size: 2.5rem;
	font-weight: 700;
	margin-top: 0;
	margin-bottom: 0.75em;
}

h1 {
	font-size: 1.875rem;
	margin-top: 1.875rem;
}

h2 {
	font-size: 1.5rem;
	margin-top: 1.5rem;
}

h3 {
	font-size: 1.25rem;
	margin-top: 1.25rem;
}

.source {
	border: 1px solid #ddd;
	border-radius: 3px;
	padding: 1.5em;
	word-break: break-all;
}

.callout {
	border-radius: 3px;
	padding: 1rem;
}

figure {
	margin: 1.25em 0;
	page-break-inside: avoid;
}

figcaption {
	opacity: 0.5;
	font-size: 85%;
	margin-top: 0.5em;
}

mark {
	background-color: transparent;
}

.indented {
	padding-left: 1.5em;
}

hr {
	background: transparent;
	display: block;
	width: 100%;
	height: 1px;
	visibility: visible;
	border: none;
	border-bottom: 1px solid rgba(55, 53, 47, 0.09);
}

img {
	max-width: 100%;
}

@media only print {
	img {
		max-height: 100vh;
		object-fit: contain;
	}
}

@page {
	margin: 1in;
}

.collection-content {
	font-size: 0.875rem;
}

.column-list {
	display: flex;
	justify-content: space-between;
}

.column {
	padding: 0 1em;
}

.column:first-child {
	padding-left: 0;
}

.column:last-child {
	padding-right: 0;
}

.table_of_contents-item {
	display: block;
	font-size: 0.875rem;
	line-height: 1.3;
	padding: 0.125rem;
}

.table_of_contents-indent-1 {
	margin-left: 1.5rem;
}

.table_of_contents-indent-2 {
	margin-left: 3rem;
}

.table_of_contents-indent-3 {
	margin-left: 4.5rem;
}

.table_of_contents-link {
	text-decoration: none;
	opacity: 0.7;
	border-bottom: 1px solid rgba(55, 53, 47, 0.18);
}

table,
th,
td {
	border: 1px solid rgba(55, 53, 47, 0.09);
	border-collapse: collapse;
}

table {
	border-left: none;
	border-right: none;
}

th,
td {
	font-weight: normal;
	padding: 0.25em 0.5em;
	line-height: 1.5;
	min-height: 1.5em;
	text-align: left;
}

th {
	color: rgba(55, 53, 47, 0.6);
}

ol,
ul {
	margin: 0;
	margin-block-start: 0.6em;
	margin-block-end: 0.6em;
}

li > ol:first-child,
li > ul:first-child {
	margin-block-start: 0.6em;
}

ul > li {
	list-style: disc;
}

ul.to-do-list {
	padding-inline-start: 0;
}

ul.to-do-list > li {
	list-style: none;
}

.to-do-children-checked {
	text-decoration: line-through;
	opacity: 0.375;
}

ul.toggle > li {
	list-style: none;
}

ul {
	padding-inline-start: 1.7em;
}

ul > li {
	padding-left: 0.1em;
}

ol {
	padding-inline-start: 1.6em;
}

ol > li {
	padding-left: 0.2em;
}

.mono ol {
	padding-inline-start: 2em;
}

.mono ol > li {
	text-indent: -0.4em;
}

.toggle {
	padding-inline-start: 0em;
	list-style-type: none;
}

/* Indent toggle children */
.toggle > li > details {
	padding-left: 1.7em;
}

.toggle > li > details > summary {
	margin-left: -1.1em;
}

.selected-value {
	display: inline-block;
	padding: 0 0.5em;
	background: rgba(206, 205, 202, 0.5);
	border-radius: 3px;
	margin-right: 0.5em;
	margin-top: 0.3em;
	margin-bottom: 0.3em;
	white-space: nowrap;
}

.collection-title {
	display: inline-block;
	margin-right: 1em;
}

.page-description {
    margin-bottom: 2em;
}

.simple-table {
	margin-top: 1em;
	font-size: 0.875rem;
	empty-cells: show;
}
.simple-table td {
	height: 29px;
	min-width: 120px;
}

.simple-table th {
	height: 29px;
	min-width: 120px;
}

.simple-table-header-color {
	background: rgb(247, 246, 243);
	color: black;
}
.simple-table-header {
	font-weight: 500;
}

time {
	opacity: 0.5;
}

.icon {
	display: inline-block;
	max-width: 1.2em;
	max-height: 1.2em;
	text-decoration: none;
	vertical-align: text-bottom;
	margin-right: 0.5em;
}

img.icon {
	border-radius: 3px;
}

.user-icon {
	width: 1.5em;
	height: 1.5em;
	border-radius: 100%;
	margin-right: 0.5rem;
}

.user-icon-inner {
	font-size: 0.8em;
}

.text-icon {
	border: 1px solid #000;
	text-align: center;
}

.page-cover-image {
	display: block;
	object-fit: cover;
	width: 100%;
	max-height: 30vh;
}

.page-header-icon {
	font-size: 3rem;
	margin-bottom: 1rem;
}

.page-header-icon-with-cover {
	margin-top: -0.72em;
	margin-left: 0.07em;
}

.page-header-icon img {
	border-radius: 3px;
}

.link-to-page {
	margin: 1em 0;
	padding: 0;
	border: none;
	font-weight: 500;
}

p > .user {
	opacity: 0.5;
}

td > .user,
td > time {
	white-space: nowrap;
}

input[type="checkbox"] {
	transform: scale(1.5);
	margin-right: 0.6em;
	vertical-align: middle;
}

p {
	margin-top: 0.5em;
	margin-bottom: 0.5em;
}

.image {
	border: none;
	margin: 1.5em 0;
	padding: 0;
	border-radius: 0;
	text-align: center;
}

.code,
code {
	background: rgba(135, 131, 120, 0.15);
	border-radius: 3px;
	padding: 0.2em 0.4em;
	border-radius: 3px;
	font-size: 85%;
	tab-size: 2;
}

code {
	color: #eb5757;
}

.code {
	padding: 1.5em 1em;
}

.code-wrap {
	white-space: pre-wrap;
	word-break: break-all;
}

.code > code {
	background: none;
	padding: 0;
	font-size: 100%;
	color: inherit;
}

blockquote {
	font-size: 1.25em;
	margin: 1em 0;
	padding-left: 1em;
	border-left: 3px solid rgb(55, 53, 47);
}

.bookmark {
	text-decoration: none;
	max-height: 8em;
	padding: 0;
	display: flex;
	width: 100%;
	align-items: stretch;
}

.bookmark-title {
	font-size: 0.85em;
	overflow: hidden;
	text-overflow: ellipsis;
	height: 1.75em;
	white-space: nowrap;
}

.bookmark-text {
	display: flex;
	flex-direction: column;
}

.bookmark-info {
	flex: 4 1 180px;
	padding: 12px 14px 14px;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
}

.bookmark-image {
	width: 33%;
	flex: 1 1 180px;
	display: block;
	position: relative;
	object-fit: cover;
	border-radius: 1px;
}

.bookmark-description {
	color: rgba(55, 53, 47, 0.6);
	font-size: 0.75em;
	overflow: hidden;
	max-height: 4.5em;
	word-break: break-word;
}

.bookmark-href {
	font-size: 0.75em;
	margin-top: 0.25em;
}

.sans { font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, ui-serif, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP'; }
.pdf:lang(zh-CN) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC'; }
.pdf:lang(zh-TW) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC'; }
.pdf:lang(ko-KR) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR'; }
.pdf .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK JP'; }
.pdf:lang(zh-CN) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK SC'; }
.pdf:lang(zh-TW) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK TC'; }
.pdf:lang(ko-KR) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK KR'; }
.pdf .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.highlight-default {
	color: rgba(55, 53, 47, 1);
}
.highlight-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.highlight-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.highlight-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.highlight-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.highlight-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.highlight-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.highlight-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.highlight-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.highlight-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.highlight-gray_background {
	background: rgba(241, 241, 239, 1);
}
.highlight-brown_background {
	background: rgba(244, 238, 238, 1);
}
.highlight-orange_background {
	background: rgba(251, 236, 221, 1);
}
.highlight-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.highlight-teal_background {
	background: rgba(237, 243, 236, 1);
}
.highlight-blue_background {
	background: rgba(231, 243, 248, 1);
}
.highlight-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.highlight-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.highlight-red_background {
	background: rgba(253, 235, 236, 1);
}
.block-color-default {
	color: inherit;
	fill: inherit;
}
.block-color-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.block-color-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.block-color-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.block-color-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.block-color-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.block-color-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.block-color-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.block-color-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.block-color-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.block-color-gray_background {
	background: rgba(241, 241, 239, 1);
}
.block-color-brown_background {
	background: rgba(244, 238, 238, 1);
}
.block-color-orange_background {
	background: rgba(251, 236, 221, 1);
}
.block-color-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.block-color-teal_background {
	background: rgba(237, 243, 236, 1);
}
.block-color-blue_background {
	background: rgba(231, 243, 248, 1);
}
.block-color-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.block-color-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.block-color-red_background {
	background: rgba(253, 235, 236, 1);
}
.select-value-color-uiBlue { background-color: rgba(35, 131, 226, .07); }
.select-value-color-pink { background-color: rgba(245, 224, 233, 1); }
.select-value-color-purple { background-color: rgba(232, 222, 238, 1); }
.select-value-color-green { background-color: rgba(219, 237, 219, 1); }
.select-value-color-gray { background-color: rgba(227, 226, 224, 1); }
.select-value-color-transparentGray { background-color: rgba(227, 226, 224, 0); }
.select-value-color-translucentGray { background-color: rgba(0, 0, 0, 0.06); }
.select-value-color-orange { background-color: rgba(250, 222, 201, 1); }
.select-value-color-brown { background-color: rgba(238, 224, 218, 1); }
.select-value-color-red { background-color: rgba(255, 226, 221, 1); }
.select-value-color-yellow { background-color: rgba(253, 236, 200, 1); }
.select-value-color-blue { background-color: rgba(211, 229, 239, 1); }
.select-value-color-pageGlass { background-color: undefined; }
.select-value-color-washGlass { background-color: undefined; }

.checkbox {
	display: inline-flex;
	vertical-align: text-bottom;
	width: 16;
	height: 16;
	background-size: 16px;
	margin-left: 2px;
	margin-right: 5px;
}

.checkbox-on {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%2358A9D7%22%2F%3E%0A%3Cpath%20d%3D%22M6.71429%2012.2852L14%204.9995L12.7143%203.71436L6.71429%209.71378L3.28571%206.2831L2%207.57092L6.71429%2012.2852Z%22%20fill%3D%22white%22%2F%3E%0A%3C%2Fsvg%3E");
}

.checkbox-off {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20x%3D%220.75%22%20y%3D%220.75%22%20width%3D%2214.5%22%20height%3D%2214.5%22%20fill%3D%22white%22%20stroke%3D%22%2336352F%22%20stroke-width%3D%221.5%22%2F%3E%0A%3C%2Fsvg%3E");
}
	
</style></head><body><article id="fe85a7bb-66bb-4624-babd-e7090c480afc" class="page sans"><header><img class="page-cover-image" src="https://images.unsplash.com/photo-1519577918463-484ce33e1ecb?ixlib=rb-4.0.3&amp;q=85&amp;fm=jpg&amp;crop=entropy&amp;cs=srgb" style="object-position:center 50%"/><div class="page-header-icon page-header-icon-with-cover"><img class="icon" src="https://www.notion.so/icons/search_green.svg"/></div><h1 class="page-title">Time to Meet the Real Me </h1><p class="page-description"></p></header><div class="page-body"><p id="a52ceb15-31d5-461d-9f2a-320abb4568e5" class="">
</p><p id="fe5ed25a-ecd4-459f-ba9a-24b071ec4406" class="">
</p><figure id="94000b90-0031-4a92-9759-77934aace490" class="image"><a href="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/Untitled.png"><img style="width:708px" src="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/Untitled.png"/></a></figure><p id="f8caf0b5-aa8f-4cc1-b775-9dd7a1022b7b" class="">
</p><h3 id="f48ba8b7-ba7e-4d26-bea2-39a0b87953e2" class=""><em><mark class="highlight-teal_background"><strong>있는 그대로 아름다운,</strong></mark></em></h3><h3 id="12514f37-ad9d-4683-962f-d0f4bd360892" class=""><em><mark class="highlight-teal_background"><strong>더 괜찮은 나와 너를 만나는 시간</strong></mark></em></h3><div id="bf6c1bbc-f19a-4d2d-a760-515b83954935" class="column-list"><div id="87803e45-2905-41b3-a71b-ad9f76db097a" style="width:50%" class="column"><figure id="8f0a084b-71bd-4a82-80af-397dca4266a1" class="image"><a href="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/Untitled%201.png"><img style="width:336px" src="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/Untitled%201.png"/></a></figure></div><div id="e1047fa7-1701-4c9d-a33c-6c7ba1c3f472" style="width:50%" class="column"><hr id="5fd67357-efd9-46cf-beeb-c396e659ee25"/><h3 id="1b7ca22d-604d-4b12-ad27-3bf61fd7b853" class="">Time to Meet the Real Me</h3><p id="49d7c2de-807d-4f5b-8f09-178e21f35d42" class="">우리 주변에는 별로인 사람들이 많아 보인다. 그러나 사실 그들을 오해하고 잘못 봤기 때문이라면? 우리는 종종 말이 비롯된 깊은 마음을 듣지 못하며, 좋은 마음을 좋은 말로 전하지 못해 서로를 오해하고, 나 자신조차도 부족한 사람이라 생각하곤 한다.  </p><p id="f566ccad-b01b-4365-a159-179aa5d5e530" class=""> <strong>Time to Meet the Real Me</strong>는 이러한 단절 속 진정한 나와 너를 발견하는 여정이다. 감정을 매개로 몸과 마음의 일렁임을 느껴보길 제안하며, 결국 <span style="border-bottom:0.05em solid">서로 다른 삶의 모습일 뿐 ‘우리는 모두 괜찮은 사람’이라는 메시지를 전한다. </span></p><p id="1b2d81d8-64c5-43c1-a7f9-d4b55986e0a0" class=""> 보이는 말과 상황 너머 보이지 않던 노력과 성품, 각자의 바람, 그리고 살아온 삶을 보게 될 때 우리는 더 괜찮은 나와 너로서 만나게 된다.</p></div></div><hr id="69a2a62c-d32e-4d4b-960b-495e4ccc2737"/><figure id="c54a4020-c490-4d80-984a-2b9d27e9c0ca" class="image" style="text-align:right"><a href="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/ci.png"><img style="width:72px" src="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/ci.png"/></a></figure><p id="12f3d5a0-f1ae-4b7b-b0cb-d48be509ac0e" class="">
</p><p id="80f8d9da-71d1-44de-8f26-258770ce9dce" class="">
</p><h2 id="2ece2560-5f82-458e-bca5-de1f8f8a4e55" class="block-color-teal_background">1. 나는  _____________ 입니다. </h2><hr id="6b0cfc65-2f0f-439e-9784-5a17904af870"/><figure id="3abf4730-ca88-4739-a62d-d28304ecaf3a" class="image"><a href="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/Untitled%202.png"><img style="width:708px" src="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/Untitled%202.png"/></a></figure><p id="5591718b-46b6-419e-83c9-100df8220e44" class=""><strong>&lt; 일상에서의 자기소개 &gt;</strong> </p><p id="8b73df6e-2258-46e4-9cfd-a0d93da8bd7f" class="">: </p><p id="82be53cc-8608-4ea2-801c-35e63faf91b0" class="">
</p><figure id="585e8af4-3120-49f5-944d-a31a9e954a8a" class="image"><a href="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/Untitled%203.png"><img style="width:708px" src="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/Untitled%203.png"/></a></figure><figure id="95737e15-f3e8-4250-98e9-b3b6be8c5d7f" class="image"><a href="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/Untitled%204.png"><img style="width:720px" src="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/Untitled%204.png"/></a></figure><p id="8d1ea5b3-95d0-4a96-8eb1-c90150d818ef" class="">
</p><p id="65c4c250-0a8b-44d0-8415-dea6b2adc960" class="">
</p><p id="ee5f7747-59b2-4d5f-9346-6368ba2130ab" class="">
</p><h2 id="684fc49a-a070-4e14-8e8d-8b298b1d9daa" class="block-color-teal_background">2. 말이 비롯된 깊은, 마음 </h2><hr id="fb61e160-bff1-4d53-b0f3-6817be90dccb"/><h3 id="1a781ff1-e8c9-4194-9368-aff4e506a734" class="block-color-teal_background">마음을 보고, 알아줘야 하는 이유  </h3><ol type="1" id="759462f6-a88c-4507-9eb4-e9954d5eda98" class="numbered-list" start="1"><li><strong>소통과 관계에서 왜 감정이 중요한가요?</strong><ol type="a" id="6adc7646-2b40-4610-84d4-8495c9c9a598" class="numbered-list" start="1"><li>(이미지 추가)</li></ol><figure class="block-color-default callout" style="white-space:pre-wrap;display:flex" id="70b0d8ef-ce79-4274-afb7-09505f331e1a"><div style="font-size:1.5em"><span class="icon">🗨️</span></div><div style="width:100%">감정은 몸의 언어라고 표현합니다. 어떤 자극이 왔을 때, 과거로부터 지금까지 내 몸에 축적된 기억–의식이든 무의식이든-을 아주 순식간에 휘돌아 나오면서 감정이 일어납니다.<p id="cd32a0fb-6e9f-4f2a-834f-2088c15acb48" class="">몸에 축적된 이 기억이 바로 지금-여기 내 삶 전체이며, 내 존재 자체라고 할 수 있습니다. 따라서 상대방이 내 감정을 알아주면, 내 인생 전체가 이해 받은 듯한 느낌이 들고, 반대로 감정을 무시하면 내 인생이 부정당하는 느낌을 갖게 됩니다.</p><p id="4280894d-a436-4304-a64c-0ce799113cdf" class="">좋은 소통과 좋은 관계는 서로 상대방을 있는 모습 그대로 존중해 줄 때, 즉 존재 자체로 인정해 줄 때 가능하게 됩니다.</p><p id="00beebea-75dc-45ed-bb4d-63b8de467c30" class="">내 감정이 존중받지 못하면 자꾸 방어적인 태도를 유지하게 되는데, 이는 마치 권투선수가 시합에서 자기를 보호하기 위해 가드를 올리고 있는 모습과 똑같습니다. 이 때는 상대방이 내게 어떤 말을 해도 제대로 알아듣지 못하는 것이 당연합니다.</p></div></figure></li></ol><ol type="1" id="4b9b63c6-e5ca-4591-bbeb-aa41b3f255f8" class="numbered-list" start="2"><li><strong>그럼 상대방과 잘 통하려면 어떻게 해야 하나요?</strong><figure class="block-color-default callout" style="white-space:pre-wrap;display:flex" id="aa949ee3-c15c-4e34-994d-da2c6969ba2d"><div style="font-size:1.5em"><span class="icon">🗨️</span></div><div style="width:100%">잘 통한다는 것은 서로가 가드를 내려놓고 대화하는 것이지요<p id="4f8e5798-0010-4b28-88e2-da13856b350f" class="">여기서 중요한 게 나만 가드를 내려놓으면 되는 것이 아니라, 상대방으로 하여금 가드를 스스로 내리게 하려는 노력과 실력이 필요합니다.</p><p id="870f30c9-5f94-460b-b076-bbd5027f0711" class="">이때 우리가 할 수 있는 것, 첫번째가 바로 Yes- 즉 상대방의 말과 감정을 그대로 수용해 주는 것입니다.</p><p id="edf0765e-4182-4c15-9f18-92c0401ed7e1" class="">이를 통해 바로 ‘당신은 괜찮은 사람’이라는 메시지를 분명하게 줍니다.</p></div></figure></li></ol><ol type="1" id="ed93cb9c-c714-46ff-80ce-ca7ac5e61d6d" class="numbered-list" start="3"><li><strong>그 사람이 (혹은 내가) 정말 괜찮은 사람일까요?</strong><figure class="block-color-default callout" style="white-space:pre-wrap;display:flex" id="90239662-1927-4692-b788-a11c7870d0fb"><div style="font-size:1.5em"><span class="icon">🗨️</span></div><div style="width:100%">누구에게나 이 세상에서 가장 중요한 사람이 자기 자신이기 때문에 사람들은 누구나 자신이 옳다고 믿습니다. 이에 따른 부작용이 ‘나는 맞고 당신은 틀리다’ 라는 시각을 갖는 것입니다.<p id="0ec68958-070f-4641-83f0-e3454da61d70" class="">이런 무의식적인 습관으로 인해 사람을 대할 때 판단하고, 평가하고, 비난하는 것에 익숙한데, 이런 습관에서 벗어나기 위해서는 긍정우선의 관점을 연습해야 합니다.</p><p id="871fcc4e-2788-4c95-8237-34314b094304" class="">상대방을 호기심으로 바라보면서 감정이 비롯된 그의 욕구, 행동의 기반이 되는 성품, 그동안의 노력 등을 찾아보십시오. 상대방은 분명히 괜찮은 사람으로 보이기 시작할 것입니다.</p><p id="c49137a1-b4ad-4fe0-9d8c-5192430dc66b" class="">인간이란 게 크게는 나나 너나 그렇게 다르지 않습니다. 누구든, 그도 나와 같이 그저 최선을 다해 발버둥 친 것뿐이거든요.</p></div></figure></li></ol><ol type="1" id="7169e34c-bf5b-42af-b761-2181b9d2e439" class="numbered-list" start="4"><li><strong>언제나 내가 상대방을 먼저 공감해주고 인정해야 한다는 말로 들리는데, 그럼 내 마음은요? 아무리 해도 이해가 안 되면요?</strong><figure class="block-color-default callout" style="white-space:pre-wrap;display:flex" id="e25601cb-d00f-4a3b-a4d8-81c499b1c0fe"><div style="font-size:1.5em"><span class="icon">🗨️</span></div><div style="width:100%">맞아요! 아무리 노력해도 상대방을 이해할 수가 없고, 내가 너무 힘들어서 상대방을 먼저 볼 수 없을 때도 있습니다.<p id="91b4abbf-64a7-47cf-b7ce-50b2c376e561" class="">이게 잘못된 것은 아닌데, 이런 때 보통 상대방 탓을 하기 쉽습니다. 이게 바로 소통과 관계의 최대 장애물입니다.</p><p id="726bb91a-411b-4687-a265-81b1029c896b" class="">그런 마음이 일어난 것이 누구의 잘잘못이 아닌 만큼, 상대방 탓하는 걸 멈춥니다. 자기 자신을 스스로 위로하며, 공감하고 인정함으로써 힘을 차린 다음 상대방으로 향하는 마음을 조금씩 키워나가야 합니다. 참 어렵죠?</p><p id="3525dc20-bc56-4b66-9894-3f13531747c7" class="">정말 답답하고 화가 나더라도 잠시 멈추면 상대방을 볼 수 있는 또 다른 힘이 생기는데, 이게 바로 스티븐 코비가 말하는 ‘인간의 천부적 재능’입니다.</p></div></figure></li></ol><ol type="1" id="5d1cef7f-2b4d-45ef-a998-0fc11829d179" class="numbered-list" start="5"><li><strong>그럼 어떻게 상대방을 보고, 어떻게 표현할 수 있나요?</strong><figure class="block-color-default callout" style="white-space:pre-wrap;display:flex" id="c3b99cd6-c70a-4848-8ec6-e83f25137eb7"><div style="font-size:1.5em"><span class="icon">🗨️</span></div><div style="width:100%">나 자신과 상대방에 대해 예민하게 잘 알아차리는 것이 중요한데, 어느 순간에도 잘 알아차릴 수 있도록 감수성훈련을 하는 것입니다.<p id="de173287-5a8f-4928-a300-660fb6e01c6c" class="">잘 알아차리면 언제든 적용할 수 있는 대화 방식, 이게 바로 Yes-And-Com 대화 모델입니다.</p><p id="b69f671e-6938-4414-9fff-a1f442b5bdf3" class="">Yes로 시작한다. – 상대방의 말에 맞장구 쳐주고, 요약하고, 감정을 알아주는 거로 시작합니다.</p><p id="5f3013c6-08cb-47da-a28f-6daf1713d154" class="">And는 인정하면서 상대방과 함께 합니다. 즉, 노력과 성품, 그리고 욕구를 알아줍니다.</p><p id="416e5ce4-51ff-461e-8b9b-8d9276c22736" class="">그리고 Communication 합니다. – 상대방과 연결하는 대화 후 질문이나 내 의견을 내는 대화입니다.</p><p id="dd805391-3fdb-480a-b3ab-c621e75ccc94" class="">내 답답하고 화나는 심정을 누르고 말하지 말라는 것이 아니라, 상대방을 먼저 Yes-And로 알아주고, 그 다음에 Com 하자는 얘기입니다.</p></div></figure></li></ol><ol type="1" id="4711f80f-5802-415e-acd3-be55d1450607" class="numbered-list" start="6"><li><strong>왜 감정을 다루나요? </strong><figure class="block-color-default callout" style="white-space:pre-wrap;display:flex" id="ad3ea333-cb32-42f6-ab75-ecc2b666f9be"><div style="font-size:1.5em"><span class="icon">🗨️</span></div><div style="width:100%">일단 내 탓, 남 탓하지 않는 삶이 되겠지요. 이것만 해도 관계가 엄청 좋아지지 않을까요?<p id="a079ff65-2ea2-41a0-9bbf-9a5a9f0dc0d4" class="">내가 너를 사랑하고 위하는 마음을 제대로 표현해서, 네가 그런 마음을 잘 알고 있다면, 너와 나의 마음이 잘 통하는 대화, 즉 시너지를 내는 대화가 비로소 이루어지는 거죠. 둘이 서로 손을 꼭 잡고 일한다면, 그게 바로 어떤 어려움도 헤쳐나갈 힘이 아닐까요?</p><p id="4425aeaa-9d21-4f80-bd79-b4cdd1bb9fe1" class="">좋아지는 것도 있지만, 잘못되지 않는 것도 큽니다. 한마디로 잘 싸우게 되는 거죠. 뭐든 관계에서 도망가지 않고, 다 꼭꼭 씹어서 소화할 힘이 생기지요. 그러니 그 관계가 얼마나 단단하고 위기에 강하겠어요.</p><p id="9faa42b3-0dcf-4ff2-a4c1-714ca587043e" class="">무엇보다도 개인의 성장을 스스로 지켜볼 수 있는 게 가장 신나는 일입니다. 매일 스스로를 미워하지 않고 매일 더 수용하며 사니까. 괜찮은 사람으로 살아가는 기분이 제법 훌륭하거든요.</p><p id="f71d355e-b354-4bd0-901e-9af8b707094b" class="">나도 괜찮은 사람이고 내가 만나는 너도 괜찮은 사람인데… 삶에 괜찮지 않은 일이 뭐가 있겠어요.</p></div></figure></li></ol><p id="22e923c2-6920-4eb5-8235-a7f7d3b057cd" class="">
</p><h3 id="f635c157-2a0f-4cff-b4e5-0791f8e1b9a5" class="block-color-teal_background">&lt;감수성 훈련&gt;으로 마음을 알아주는 대화를 해본 이들의 후기  </h3><figure id="4c5555be-5088-4a4a-8cbd-2eea866fd208" class="image"><a href="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/Untitled%205.png"><img style="width:768px" src="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/Untitled%205.png"/></a></figure><div id="44dd2791-c1cb-45dd-9757-f6257c5ea70b" class="column-list"><div id="7ccaa60a-ad94-49f4-96ad-1431eebf00d0" style="width:50%" class="column"><figure id="da2a6884-fa13-44f2-b773-2d65e915bf44" class="image"><a href="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/009.png"><img style="width:1080px" src="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/009.png"/></a></figure></div><div id="0fbc23ef-2c0b-4321-8a1f-4cb965dfd667" style="width:50%" class="column"><figure id="6acc0eca-9ba9-4be1-ac0c-6ccaa8207139" class="image"><a href="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/002.png"><img style="width:1080px" src="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/002.png"/></a></figure></div></div><div id="d9bbe67b-277d-4d53-91a6-8c56be94e775" class="column-list"><div id="a95a053e-77bd-4f6b-a62f-47b25e2b42ee" style="width:50%" class="column"><figure id="bab8686c-1c5a-423e-b3cd-ad25eac081c0" class="image"><a href="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/003.png"><img style="width:1080px" src="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/003.png"/></a></figure></div><div id="57a670d7-380e-4693-8dae-7a0f25bc77f3" style="width:50.000000000000014%" class="column"><figure id="e94dbdff-059f-4206-82ac-6002ca45ce76" class="image"><a href="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/004.png"><img style="width:1080px" src="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/004.png"/></a></figure></div></div><div id="6040c579-29f8-4053-ba21-0689fe93527b" class="column-list"><div id="29c7b8da-05c1-4cec-a699-e5fa52678e75" style="width:50%" class="column"><figure id="786e6ef1-2f0b-49dc-acef-762a2f0a1df2" class="image"><a href="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/006.png"><img style="width:1080px" src="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/006.png"/></a></figure></div><div id="8c2cbb63-27df-4c1a-ae86-32dfd05d7f53" style="width:50%" class="column"><figure id="564f3ea0-5473-40f7-a4d9-8b28860e04dc" class="image"><a href="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/005.png"><img style="width:1080px" src="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/005.png"/></a></figure></div></div><div id="9d6daae9-22c8-4682-95c4-bf8e174d4c7f" class="column-list"><div id="4465feff-b5d9-4d6a-97d5-3aeec6e61939" style="width:50%" class="column"><figure id="761b6c49-e5e7-47a5-a586-8bf62a49b936" class="image"><a href="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/007.png"><img style="width:708px" src="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/007.png"/></a></figure></div><div id="58f52ee0-4783-443c-bb83-c636a2196b37" style="width:50%" class="column"><figure id="45f14849-d73d-45bd-bff1-07950c93a2ee" class="image"><a href="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/008.png"><img style="width:708px" src="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/008.png"/></a></figure></div></div><p id="9cc6805a-9033-46c2-af6c-db5ef067ee4f" class="">
</p><p id="3904fd16-3470-49bc-ab42-5d114ce63bb4" class="">
</p><h2 id="5aa15a63-d2e5-43ee-bbba-9f2be4788596" class="block-color-teal_background">3. 지금 여기, 내 마음</h2><hr id="d54a164f-eb5d-47d2-87d4-2e8002414d66"/><h3 id="aabf8a23-c5ca-4fdb-8024-3d48fa96170d" class="block-color-teal_background">지금 내 마음은 어떤가요? </h3><figure id="253ab07d-efe7-4044-9e62-3faa2959d9b5" class="image"><a href="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/Untitled%206.png"><img style="width:768px" src="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/Untitled%206.png"/></a></figure><p id="722c56d1-3ddf-4f9a-9996-1975109d14f0" class="">
</p><figure id="7f9bc368-0070-4bfe-8a81-77f27e339489" class="image"><a href="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/%25EB%25AC%25B4%25EB%2593%259C%25EB%25AF%25B8%25ED%2584%25B000.jpg"><img style="width:708px" src="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/%25EB%25AC%25B4%25EB%2593%259C%25EB%25AF%25B8%25ED%2584%25B000.jpg"/></a><figcaption>내마음의 색깔은 무슨색인지, 어떤 의미인지 </figcaption></figure><p id="0cd9d2e7-1050-4d3b-b1d5-c1bcd16e109c" class="">→ 이 이미지 써도 되나? &lt;출처 : 감정의 발견&gt;</p><p id="07f5d33a-bf00-4a39-8b07-f90573b9dd95" class="">
</p><p id="cbbcec36-5712-436c-be1e-6a0249b93649" class="">
</p><blockquote id="f0b107f6-235c-4666-a338-468c9da4ab89" class="">아~ 그랬구나.<br/>이곳에선 감정들을 소개하고 있어. 맥락으로 , 뭐로, 뭐로….<br/>그 감정에 하나씩 푹 빠져보고, 내 몸과 마음은 어떻게 반응하는지 센서티브하게  살펴보길 바라! <br/>이 파트를 잘 감상하는 팁을 주자면!<br/></blockquote><div id="ace5f132-1624-4ff5-a6be-4db38b3fd2ab" class="column-list"><div id="3e8fdd9c-a32d-4051-bc71-d0ad0ed34929" style="width:50%" class="column"><h3 id="70cca814-61df-4807-a4e5-221cb41de88c" class="">1️⃣. 잘 표현해보기  </h3><hr id="5956293a-5a35-4a48-a19c-9c1ffb2116bf"/><figure class="block-color-default callout" style="white-space:pre-wrap;display:flex" id="cb76bfab-310c-4c92-bedc-e8a5fa3569fe"><div style="font-size:1.5em"><span class="icon">✨</span></div><div style="width:100%">내 감정을 내 것으로 표현하기. 네 감정을 네 것으로 표현하기. 저는 이랬어요. 당신은 어땠겠어요.  </div></figure><p id="cf9636af-251b-4adc-b055-b7bb91da6323" class="">
</p></div><div id="7a767e06-e0b9-4cd8-a65b-2b1f2b459186" style="width:50%" class="column"><h3 id="4eeacf6d-7ce8-471e-bef6-786befae8e44" class="">2️⃣. 잘 알아차려보기</h3><hr id="c689b218-e549-4b3d-82f8-29aaff6fc490"/><figure class="block-color-default callout" style="white-space:pre-wrap;display:flex" id="002b7ab3-a43c-446d-ab70-69cfd4fe8827"><div style="font-size:1.5em"><span class="icon">✨</span></div><div style="width:100%">그 감정이 들게 된 이유를 살펴보자. 왜 그럴까? 어떤 노력을 했기 때문에? 그런 노력을 하는 이 사람이 어떤 사람이라서? 어떤 성품과 미덕을 가지고 있지? 그런 이 사람이 정말 바라는 건 뭐였을까?  </div></figure></div></div><p id="ec972b4f-300e-43b7-a247-cf9171feb817" class="">
</p><h3 id="59f62797-b330-413a-a979-927c7fbccdd0" class="block-color-teal_background">The way to meet the real me</h3><div id="7d4d6735-12db-405d-a8c3-f3bd29cc1d2a" class="collection-content"><h4 class="collection-title">The way to meet the real me</h4><table class="collection-content"><thead><tr><th><span class="icon property-icon"><svg role="graphics-symbol" viewBox="0 0 16 16" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0" class="typesTitle"><path d="M0.637695 13.1914C1.0957 13.1914 1.32812 13 1.47852 12.5215L2.24414 10.3887H6.14746L6.90625 12.5215C7.05664 13 7.2959 13.1914 7.74707 13.1914C8.22559 13.1914 8.5332 12.9043 8.5332 12.4531C8.5332 12.2891 8.50586 12.1523 8.44434 11.9678L5.41602 3.79199C5.2041 3.21777 4.82129 2.9375 4.19922 2.9375C3.60449 2.9375 3.21484 3.21777 3.0166 3.78516L-0.0322266 12.002C-0.09375 12.1797 -0.121094 12.3232 -0.121094 12.4668C-0.121094 12.918 0.166016 13.1914 0.637695 13.1914ZM2.63379 9.12402L4.17871 4.68066H4.21973L5.76465 9.12402H2.63379ZM12.2793 13.2324C13.3115 13.2324 14.2891 12.6787 14.7129 11.8037H14.7402V12.5762C14.7471 12.9863 15.0273 13.2393 15.4238 13.2393C15.834 13.2393 16.1143 12.9795 16.1143 12.5215V8.00977C16.1143 6.49902 14.9658 5.52148 13.1543 5.52148C11.7666 5.52148 10.6592 6.08887 10.2695 6.99121C10.1943 7.15527 10.1533 7.3125 10.1533 7.46289C10.1533 7.81152 10.4062 8.04395 10.7686 8.04395C11.0215 8.04395 11.2129 7.94824 11.3496 7.73633C11.7529 6.99121 12.2861 6.65625 13.1064 6.65625C14.0977 6.65625 14.6992 7.20996 14.6992 8.1123V8.67285L12.5664 8.7959C10.7686 8.8916 9.77734 9.69824 9.77734 11.0107C9.77734 12.3369 10.8096 13.2324 12.2793 13.2324ZM12.6621 12.1387C11.8008 12.1387 11.2129 11.667 11.2129 10.9561C11.2129 10.2725 11.7598 9.82129 12.7578 9.75977L14.6992 9.62988V10.3203C14.6992 11.3457 13.7969 12.1387 12.6621 12.1387Z"></path></svg></span>이름</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/compose_gray.svg" style="width:14px;height:14px"/></span>정의</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/chat_gray.svg" style="width:14px;height:14px"/></span>표현</th></tr></thead><tbody><tr id="45d83647-e394-4223-8ca5-2c2ff36af1b3"><td class="cell-title"><a href="https://www.notion.so/Anxiety-45d83647e39442238ca52c2ff36af1b3?pvs=21">불안(Anxiety) </a></td><td class="cell-G]gx">이유 없이 막연히 나타나는 불쾌한 정서적 상태 또는 안도감이나 확신이 상실된 심리 상태</td><td class="cell-Dn\h"><span class="selected-value select-value-color-brown">걱정돼요</span><span class="selected-value select-value-color-brown">괴로워요</span><span class="selected-value select-value-color-purple">긴장돼요</span><span class="selected-value select-value-color-orange">두려워요</span><span class="selected-value select-value-color-blue">마음이 분주해요</span><span class="selected-value select-value-color-default">무기력해요</span><span class="selected-value select-value-color-pink">무서워요</span><span class="selected-value select-value-color-yellow">스트레스받아요</span><span class="selected-value select-value-color-gray">심각해요</span><span class="selected-value select-value-color-green">조급해요</span><span class="selected-value select-value-color-red">초조해요</span><span class="selected-value select-value-color-green">혼란스러워요</span></td></tr><tr id="b2f351c4-ca48-4a43-a223-30da89bde8a3"><td class="cell-title"><a href="https://www.notion.so/Joy-b2f351c4ca484a43a22330da89bde8a3?pvs=21">기쁨(Joy) </a></td><td class="cell-G]gx">욕구가 충족되었을 때의 흐뭇하고 흡족한 마음이나 느낌.</td><td class="cell-Dn\h"><span class="selected-value select-value-color-gray">감사해요</span><span class="selected-value select-value-color-green">감탄했어요</span><span class="selected-value select-value-color-pink">기뻐요</span><span class="selected-value select-value-color-red">들떠요</span><span class="selected-value select-value-color-yellow">만족해요</span><span class="selected-value select-value-color-purple">뿌듯해요</span><span class="selected-value select-value-color-pink">설레요</span><span class="selected-value select-value-color-blue">신나요</span><span class="selected-value select-value-color-yellow">유쾌해요</span><span class="selected-value select-value-color-orange">즐거워요</span><span class="selected-value select-value-color-brown">행복해요</span><span class="selected-value select-value-color-pink">황홀해요</span><span class="selected-value select-value-color-orange">흥분돼요</span><span class="selected-value select-value-color-yellow">희망적이에요</span></td></tr><tr id="31be8010-7b40-455b-925b-1d4458bb698a"><td class="cell-title"><a href="https://www.notion.so/Embarrassment-31be80107b40455b925b1d4458bb698a?pvs=21">당황(Embarrassment)</a></td><td class="cell-G]gx">예기치 않은 상황이나 사건으로 인해 어리둥절하고 당혹스러워 하는 상태</td><td class="cell-Dn\h"><span class="selected-value select-value-color-yellow">난감해요</span><span class="selected-value select-value-color-red">당황했어요</span><span class="selected-value select-value-color-pink">무안해요</span><span class="selected-value select-value-color-pink">민망해요</span><span class="selected-value select-value-color-purple">부끄러워요</span><span class="selected-value select-value-color-red">실수했어요</span><span class="selected-value select-value-color-blue">어색해요</span><span class="selected-value select-value-color-yellow">어찌할 바를 모르겠어요</span><span class="selected-value select-value-color-blue">얼굴이 빨개졌어요</span><span class="selected-value select-value-color-brown">창피해요</span></td></tr><tr id="8aca1ba6-c268-47ee-bb7b-bc216ef52fa8"><td class="cell-title"><a href="https://www.notion.so/Sadness-8aca1ba6c26847eebb7bbc216ef52fa8?pvs=21">슬픔(Sadness)</a></td><td class="cell-G]gx">상실, 실패, 또는 좌절로 인해 느끼는 실망감과 절망감</td><td class="cell-Dn\h"><span class="selected-value select-value-color-brown">고통스러워요</span><span class="selected-value select-value-color-gray">기운이 없어요</span><span class="selected-value select-value-color-default">눈물이 나요</span><span class="selected-value select-value-color-orange">마음이 아파요</span><span class="selected-value select-value-color-default">상실감이 커요</span><span class="selected-value select-value-color-gray">슬퍼요</span><span class="selected-value select-value-color-purple">우울해요</span><span class="selected-value select-value-color-brown">울적해요</span><span class="selected-value select-value-color-gray">절망스러워요</span><span class="selected-value select-value-color-brown">허전해요</span></td></tr><tr id="2872032c-5952-42a6-9118-c54a2653d3fa"><td class="cell-title"><a href="https://www.notion.so/Anger-2872032c595242a69118c54a2653d3fa?pvs=21">분노(Anger)</a></td><td class="cell-G]gx">부당한 대우나 좌절감에 대한 강한 감정적 반응으로, 짜증이나 화, 분노를 포함</td><td class="cell-Dn\h"><span class="selected-value select-value-color-red">못 참겠어요</span><span class="selected-value select-value-color-brown">미칠 것 같아요</span><span class="selected-value select-value-color-red">분노가 끓어요</span><span class="selected-value select-value-color-red">성질나요</span><span class="selected-value select-value-color-red">열받아요</span><span class="selected-value select-value-color-orange">짜증나요</span><span class="selected-value select-value-color-yellow">참을 수 없어요</span><span class="selected-value select-value-color-brown">폭발할 것 같아요</span><span class="selected-value select-value-color-orange">화가 나요</span><span class="selected-value select-value-color-red">화가 치밀어요</span></td></tr><tr id="9e7175aa-e331-4277-8fa0-cbf5ee0647da"><td class="cell-title"><a href="https://www.notion.so/Love-9e7175aae33142778fa0cbf5ee0647da?pvs=21">사랑(Love)</a></td><td class="cell-G]gx">깊은 애정과 관심, 그리고 헌신을 나타내는 복잡한 감정</td><td class="cell-Dn\h"><span class="selected-value select-value-color-purple">그리워요</span><span class="selected-value select-value-color-purple">마음을 나누고 싶어요</span><span class="selected-value select-value-color-red">보고 싶어요</span><span class="selected-value select-value-color-red">사랑해요</span><span class="selected-value select-value-color-blue">소중해요</span><span class="selected-value select-value-color-pink">아껴요</span><span class="selected-value select-value-color-green">존경해요</span><span class="selected-value select-value-color-pink">좋아해요</span><span class="selected-value select-value-color-pink">챙겨주고싶어요</span><span class="selected-value select-value-color-pink">함께 있고 싶어요</span></td></tr><tr id="09a90e1d-af99-4057-9b7d-15bdd76e6b7b"><td class="cell-title"><a href="https://www.notion.so/Desire-09a90e1daf9940579b7d15bdd76e6b7b?pvs=21">욕망(Desire)</a></td><td class="cell-G]gx">무언가를 강하게 원하거나 바라는 감정</td><td class="cell-Dn\h"><span class="selected-value select-value-color-red">갈구해요</span><span class="selected-value select-value-color-brown">갈망해요</span><span class="selected-value select-value-color-yellow">갖고 싶어요</span><span class="selected-value select-value-color-yellow">바래요</span><span class="selected-value select-value-color-yellow">소망해요</span><span class="selected-value select-value-color-red">열망해요</span><span class="selected-value select-value-color-purple">원해요</span><span class="selected-value select-value-color-pink">이루고 싶어요</span><span class="selected-value select-value-color-orange">탐나요</span><span class="selected-value select-value-color-brown">필요해요</span></td></tr><tr id="bc969b59-8ff3-47d8-a268-9cfb6dde5ccc"><td class="cell-title"><a href="https://www.notion.so/Peace-bc969b598ff347d8a2689cfb6dde5ccc?pvs=21">평온함(Peace)</a></td><td class="cell-G]gx">내적으로나 외적으로 안정감을 가지고, 분쟁이나 갈등이 없는 상태</td><td class="cell-Dn\h"><span class="selected-value select-value-color-brown">고요해요</span><span class="selected-value select-value-color-yellow">마음이 편해요</span><span class="selected-value select-value-color-blue">만족스러워요</span><span class="selected-value select-value-color-green">안정돼요</span><span class="selected-value select-value-color-green">조용해요</span><span class="selected-value select-value-color-green">차분해요</span><span class="selected-value select-value-color-green">편안해요</span><span class="selected-value select-value-color-blue">평온해요</span><span class="selected-value select-value-color-orange">평화로워요</span><span class="selected-value select-value-color-brown">행복해요</span></td></tr><tr id="563a2250-b527-4087-9704-718567254675"><td class="cell-title"><a href="https://www.notion.so/Compassion-563a2250b52740879704718567254675?pvs=21">연민(Compassion)</a></td><td class="cell-G]gx">타인의 고통을 인지하고 그 고통을 덜어주고자 하는 깊은 동정심</td><td class="cell-Dn\h"><span class="selected-value select-value-color-brown">걱정돼요</span><span class="selected-value select-value-color-brown">공감해요</span><span class="selected-value select-value-color-orange">도와주고 싶어요</span><span class="selected-value select-value-color-yellow">마음이 아려요</span><span class="selected-value select-value-color-orange">마음이 아파요</span><span class="selected-value select-value-color-orange">보살펴주고 싶어요</span><span class="selected-value select-value-color-yellow">안타까워요</span><span class="selected-value select-value-color-red">이해해요</span><span class="selected-value select-value-color-yellow">측은해요</span><span class="selected-value select-value-color-pink">함께 울고 싶어요</span></td></tr></tbody></table><br/><br/></div><p id="01a5a2c2-ada7-4147-ba6e-247acea3411f" class="">
</p><p id="5ad5f3cc-6606-493e-9e91-92b00b4e82cb" class="">
</p><h2 id="e2901289-513b-4e2f-a3ac-df544dd141b2" class="block-color-teal_background">4. 더 괜찮은 나를 발견하기!</h2><hr id="d0ba4a19-26c2-4185-94ee-e66eedbfab73"/><figure class="block-color-default callout" style="white-space:pre-wrap;display:flex" id="0e29d04c-9b44-499b-8024-accb0e74dda3"><div style="font-size:1.5em"><span class="icon">✨</span></div><div style="width:100%">나는 (_______________) 하고 (______________)해서 (____________)한 (______) 이다. </div></figure><p id="36f26063-c59b-4acf-85b4-14e6c8d948cc" class="">→ 뭔가 자신의 괜찮은 점을 발견할 수 있는 트랙이었으면 좋겠고, 그걸 귀엽고 의미있는 결과물로 가져갈 수 있으면 좋겠다! </p><ul id="33365d13-5095-47e3-a9b2-862d229af70e" class="bulleted-list"><li style="list-style-type:disc">EX) 행운의 부적 같이!  아님뭔가 인증샷이라도 찍을 수 있게 하거나.. </li></ul><p id="c05c1235-cde5-471d-94ef-f7530f4040be" class="">
</p><p id="7618f527-5086-43e9-ace4-57fe1689264d" class="">
</p><h2 id="a796ce2b-5232-4f0d-a745-1110b7d5f865" class="block-color-teal_background">5. 오늘 당신이 발견한 리얼미는 무엇이었나요? 나눠주세요. </h2><hr id="72781671-218c-4097-8856-361abf040c56"/><p id="689c23ba-254f-49b9-a89f-1977c91db2bc" class="">→ 여기엔 방명록 댓글창 추가하기. (사실 사진같은걸 올릴 수 있으면 더 좋을텐데 ㅠㅠㅠ까비) </p><p id="9d7cdf5d-f901-4437-8158-a6fa4b447fa5" class="">
</p><ul id="1011a61c-7314-4460-ab44-0bbfeb72beca" class="bulleted-list"><li style="list-style-type:disc">일단 감정을 불러일으키는 사진이 있다면? 이런거 모아서 전시했어야하는건데 ㅠㅠㅠㅠㅠㅠ 사람들한테 설문이라도 돌릴까보다 으휴. 아니면 이걸로 감정으로 찾고 표현하는…. 그런 모임을 만들어서 밋업을 할까. 아래는 예시 사진.. ! </li></ul><figure class="block-color-default callout" style="white-space:pre-wrap;display:flex" id="fc7caeef-6364-4d16-9510-9cec35fca737"><div style="font-size:1.5em"><span class="icon">💬</span></div><div style="width:100%">개인적으로 살면서 가장 큰 행복을 느꼈을 때를 공유해도 되나? <p id="ec10bd9e-ebae-4ccc-abe3-9ffd690bf8cc" class="">내가 우울증이랑 공황장애 가장 심했을 때가 있었는데, 그때 휴학하고 자취방에만 틀어박혀 있다가 제주도 가는 것을 시작으로 여행을 갔거든. 그렇게 세번째 여행이 도쿄였는데 도쿄에서 한 이만오천보쯤 걸었을 쯤 노을이 지는거야. 그때가 육교 위였거든. 2월이었고. 바람 맞으면서 든 생각이 ‘아 나 지금 이 순간 죽어도 여한이 없겠다.’ 이거였어. 근데 이게 뭔가 제일 큰 행복함? 같은 느낌. 왜냐면 지금 끝내도 난 웃을수있을것같아서.<br/>이런 걸 보면, 나는 ~(어떤 노력을 했었고) ~ (어떤 성품을 가진) ~(무얼 바라는) 사람이야. <br/></p><figure id="a4b56ed4-a155-44ba-8eff-4566eaf7857c" class="image"><a href="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/Untitled%207.png"><img style="width:4564px" src="Time%20to%20Meet%20the%20Real%20Me%20fe85a7bb66bb4624babde7090c480afc/Untitled%207.png"/></a></figure><p id="48943786-1d48-4c44-ad72-3b37fa41768f" class="">-우울함의 경계 끝에 기쁨을 느낀 2018년의 고한나-</p></div></figure><p id="e21719f1-65ef-4fd8-9eb4-e489ee6c0619" class="">
</p><p id="390d7319-2ade-486e-9aa4-bc11784b2f7e" class="">
</p><p id="fbf8a5f4-e3fd-4203-b0a8-d128ca7e3148" class="">
