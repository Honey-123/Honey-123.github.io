 
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="en" lang="en">
<head>
<script id="versionArea" type="text/javascript">
//<![CDATA[
var version = {title: "TiddlyWiki", major: 2, minor: 8, revision: 1, date: new Date("June 23, 2013"), extensions: {}};

//]]>
</script>
<meta http-equiv="Content-Type" content="text/html;charset=utf-8" />
<meta name="copyright" content="
TiddlyWiki created by Jeremy Ruston, (jeremy [at] osmosoft [dot] com)

Copyright (c) Jeremy Ruston 2004-2007
Copyright (c) UnaMesa Association 2007-2012

Redistribution and use in source and binary forms, with or without modification,
are permitted provided that the following conditions are met:

Redistributions of source code must retain the above copyright notice, this
list of conditions and the following disclaimer.

Redistributions in binary form must reproduce the above copyright notice, this
list of conditions and the following disclaimer in the documentation and/or other
materials provided with the distribution.

Neither the name of the UnaMesa Association nor the names of its contributors may be
used to endorse or promote products derived from this software without specific
prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS 'AS IS' AND ANY
EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES
OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT
SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT,
INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED
TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR
BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN
ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH
DAMAGE.

" />
<!--PRE-HEAD-START-->
<!--{{{-->
<link href="/bags/honly-666_public/tiddlers.atom" rel="alternate"
	type="application/atom+xml" title="honly-666's public feed" />
<link rel="canonical" href="http://honly-666.tiddlyspace.com/" />
<!--}}}-->
<!--PRE-HEAD-END-->
<title>
别想的太多
做的太少 - a TiddlySpace
</title>
<style id="styleArea" type="text/css">
#saveTest {display:none;}
#messageArea {display:none;}
#copyright {display:none;}
#storeArea {display:none;}
#storeArea div {padding:0.5em; margin:1em 0em 0em 0em; border-color:#fff #666 #444 #ddd; border-style:solid; border-width:2px; overflow:auto;}
#shadowArea {display:none;}
#javascriptWarning {width:100%; text-align:center; font-weight:bold; background-color:#dd1100; color:#fff; padding:1em 0em;}

</style>
<!--POST-HEAD-START-->

<!--POST-HEAD-END-->
</head>
<body onload="main();" onunload="if(window.unload) unload();">
<!--PRE-BODY-START-->

<!--PRE-BODY-END-->
<div id="copyright">
Welcome to TiddlyWiki created by Jeremy Ruston; Copyright &copy; 2004-2007 Jeremy Ruston, Copyright &copy; 2007-2011 UnaMesa Association
</div>
<noscript>

<div id="javascriptWarning">
This page requires JavaScript to function properly.<br /><br />
If you do not use JavaScript you may still <a href="/tiddlers">browse
the content of this wiki</a>.
</div>

</noscript>
<div id="saveTest"></div>
<div id="backstageCloak"></div>
<div id="backstageButton"></div>
<div id="backstageArea"><div id="backstageToolbar"></div></div>
<div id="backstage">
	<div id="backstagePanel"></div>
</div>
<div id="contentWrapper"></div>
<div id="contentStash"></div>
<div id="shadowArea">
<div title="ColorPalette">
<pre>Background: #fff
Foreground: #000
PrimaryPale: #8cf
PrimaryLight: #18f
PrimaryMid: #04b
PrimaryDark: #014
SecondaryPale: #ffc
SecondaryLight: #fe8
SecondaryMid: #db4
SecondaryDark: #841
TertiaryPale: #eee
TertiaryLight: #ccc
TertiaryMid: #999
TertiaryDark: #666
Error: #f88
</pre>
</div>
<div title="EditTemplate">
<pre>&lt;!--{{{--&gt;
&lt;div class='toolbar' macro='toolbar [[ToolbarCommands::EditToolbar]]'&gt;&lt;/div&gt;
&lt;div class='title' macro='view title'&gt;&lt;/div&gt;
&lt;div class='editor' macro='edit title'&gt;&lt;/div&gt;
&lt;div macro='annotations'&gt;&lt;/div&gt;
&lt;div class='editor' macro='edit text'&gt;&lt;/div&gt;
&lt;div class='editor' macro='edit tags'&gt;&lt;/div&gt;&lt;div class='editorFooter'&gt;&lt;span macro='message views.editor.tagPrompt'&gt;&lt;/span&gt;&lt;span macro='tagChooser excludeLists'&gt;&lt;/span&gt;&lt;/div&gt;
&lt;!--}}}--&gt;
</pre>
</div>
<div title="GettingStarted">
<pre>To get started with this blank [[TiddlyWiki]], you'll need to modify the following tiddlers:
* [[SiteTitle]] &amp; [[SiteSubtitle]]: The title and subtitle of the site, as shown above (after saving, they will also appear in the browser title bar)
* [[MainMenu]]: The menu (usually on the left)
* [[DefaultTiddlers]]: Contains the names of the tiddlers that you want to appear when the TiddlyWiki is opened
You'll also need to enter your username for signing your edits: &lt;&lt;option txtUserName&gt;&gt;
</pre>
</div>
<div title="ImportTiddlers">
<pre>&lt;&lt;importTiddlers&gt;&gt;
</pre>
</div>
<div title="MarkupPreHead">
<pre>&lt;!--{{{--&gt;
&lt;link rel='alternate' type='application/rss+xml' title='RSS' href='index.xml' /&gt;
&lt;!--}}}--&gt;
</pre>
</div>
<div title="OptionsPanel">
<pre>These [[InterfaceOptions]] for customising [[TiddlyWiki]] are saved in your browser

Your username for signing your edits. Write it as a [[WikiWord]] (eg [[JoeBloggs]])

&lt;&lt;option txtUserName&gt;&gt;
&lt;&lt;option chkSaveBackups&gt;&gt; [[SaveBackups]]
&lt;&lt;option chkAutoSave&gt;&gt; [[AutoSave]]
&lt;&lt;option chkRegExpSearch&gt;&gt; [[RegExpSearch]]
&lt;&lt;option chkCaseSensitiveSearch&gt;&gt; [[CaseSensitiveSearch]]
&lt;&lt;option chkAnimate&gt;&gt; [[EnableAnimations]]

----
Also see [[AdvancedOptions]]
</pre>
</div>
<div title="PageTemplate">
<pre>&lt;!--{{{--&gt;
&lt;div class='header' role='banner' macro='gradient vert [[ColorPalette::PrimaryLight]] [[ColorPalette::PrimaryMid]]'&gt;
&lt;div class='headerShadow'&gt;
&lt;span class='siteTitle' refresh='content' tiddler='SiteTitle'&gt;&lt;/span&gt;&amp;nbsp;
&lt;span class='siteSubtitle' refresh='content' tiddler='SiteSubtitle'&gt;&lt;/span&gt;
&lt;/div&gt;
&lt;div class='headerForeground'&gt;
&lt;span class='siteTitle' refresh='content' tiddler='SiteTitle'&gt;&lt;/span&gt;&amp;nbsp;
&lt;span class='siteSubtitle' refresh='content' tiddler='SiteSubtitle'&gt;&lt;/span&gt;
&lt;/div&gt;
&lt;/div&gt;
&lt;div id='mainMenu' role='navigation' refresh='content' tiddler='MainMenu'&gt;&lt;/div&gt;
&lt;div id='sidebar'&gt;
&lt;div id='sidebarOptions' role='navigation' refresh='content' tiddler='SideBarOptions'&gt;&lt;/div&gt;
&lt;div id='sidebarTabs' role='complementary' refresh='content' force='true' tiddler='SideBarTabs'&gt;&lt;/div&gt;
&lt;/div&gt;
&lt;div id='displayArea' role='main'&gt;
&lt;div id='messageArea'&gt;&lt;/div&gt;
&lt;div id='tiddlerDisplay'&gt;&lt;/div&gt;
&lt;/div&gt;
&lt;!--}}}--&gt;
</pre>
</div>
<div title="StyleSheetColors">
<pre>/*{{{*/
body {background:[[ColorPalette::Background]]; color:[[ColorPalette::Foreground]];}

a {color:[[ColorPalette::PrimaryMid]];}
a:hover {background-color:[[ColorPalette::PrimaryMid]]; color:[[ColorPalette::Background]];}
a img {border:0;}

h1,h2,h3,h4,h5,h6 {color:[[ColorPalette::SecondaryDark]]; background:transparent;}
h1 {border-bottom:2px solid [[ColorPalette::TertiaryLight]];}
h2,h3 {border-bottom:1px solid [[ColorPalette::TertiaryLight]];}

.button {color:[[ColorPalette::PrimaryDark]]; border:1px solid [[ColorPalette::Background]];}
.button:hover {color:[[ColorPalette::PrimaryDark]]; background:[[ColorPalette::SecondaryLight]]; border-color:[[ColorPalette::SecondaryMid]];}
.button:active {color:[[ColorPalette::Background]]; background:[[ColorPalette::SecondaryMid]]; border:1px solid [[ColorPalette::SecondaryDark]];}

.header {background:[[ColorPalette::PrimaryMid]];}
.headerShadow {color:[[ColorPalette::Foreground]];}
.headerShadow a {font-weight:normal; color:[[ColorPalette::Foreground]];}
.headerForeground {color:[[ColorPalette::Background]];}
.headerForeground a {font-weight:normal; color:[[ColorPalette::PrimaryPale]];}

.tabSelected {color:[[ColorPalette::PrimaryDark]];
	background:[[ColorPalette::TertiaryPale]];
	border-left:1px solid [[ColorPalette::TertiaryLight]];
	border-top:1px solid [[ColorPalette::TertiaryLight]];
	border-right:1px solid [[ColorPalette::TertiaryLight]];
}
.tabUnselected {color:[[ColorPalette::Background]]; background:[[ColorPalette::TertiaryMid]];}
.tabContents {color:[[ColorPalette::PrimaryDark]]; background:[[ColorPalette::TertiaryPale]]; border:1px solid [[ColorPalette::TertiaryLight]];}
.tabContents .button {border:0;}

#sidebar {}
#sidebarOptions input {border:1px solid [[ColorPalette::PrimaryMid]];}
#sidebarOptions .sliderPanel {background:[[ColorPalette::PrimaryPale]];}
#sidebarOptions .sliderPanel a {border:none;color:[[ColorPalette::PrimaryMid]];}
#sidebarOptions .sliderPanel a:hover {color:[[ColorPalette::Background]]; background:[[ColorPalette::PrimaryMid]];}
#sidebarOptions .sliderPanel a:active {color:[[ColorPalette::PrimaryMid]]; background:[[ColorPalette::Background]];}

.wizard {background:[[ColorPalette::PrimaryPale]]; border:1px solid [[ColorPalette::PrimaryMid]];}
.wizard h1 {color:[[ColorPalette::PrimaryDark]]; border:none;}
.wizard h2 {color:[[ColorPalette::Foreground]]; border:none;}
.wizardStep {background:[[ColorPalette::Background]]; color:[[ColorPalette::Foreground]];
	border:1px solid [[ColorPalette::PrimaryMid]];}
.wizardStep.wizardStepDone {background:[[ColorPalette::TertiaryLight]];}
.wizardFooter {background:[[ColorPalette::PrimaryPale]];}
.wizardFooter .status {background:[[ColorPalette::PrimaryDark]]; color:[[ColorPalette::Background]];}
.wizard .button {color:[[ColorPalette::Foreground]]; background:[[ColorPalette::SecondaryLight]]; border: 1px solid;
	border-color:[[ColorPalette::SecondaryPale]] [[ColorPalette::SecondaryDark]] [[ColorPalette::SecondaryDark]] [[ColorPalette::SecondaryPale]];}
.wizard .button:hover {color:[[ColorPalette::Foreground]]; background:[[ColorPalette::Background]];}
.wizard .button:active {color:[[ColorPalette::Background]]; background:[[ColorPalette::Foreground]]; border: 1px solid;
	border-color:[[ColorPalette::PrimaryDark]] [[ColorPalette::PrimaryPale]] [[ColorPalette::PrimaryPale]] [[ColorPalette::PrimaryDark]];}

.wizard .notChanged {background:transparent;}
.wizard .changedLocally {background:#80ff80;}
.wizard .changedServer {background:#8080ff;}
.wizard .changedBoth {background:#ff8080;}
.wizard .notFound {background:#ffff80;}
.wizard .putToServer {background:#ff80ff;}
.wizard .gotFromServer {background:#80ffff;}

#messageArea {border:1px solid [[ColorPalette::SecondaryMid]]; background:[[ColorPalette::SecondaryLight]]; color:[[ColorPalette::Foreground]];}
#messageArea .button {color:[[ColorPalette::PrimaryMid]]; background:[[ColorPalette::SecondaryPale]]; border:none;}

.popupTiddler {background:[[ColorPalette::TertiaryPale]]; border:2px solid [[ColorPalette::TertiaryMid]];}

.popup {background:[[ColorPalette::TertiaryPale]]; color:[[ColorPalette::TertiaryDark]]; border-left:1px solid [[ColorPalette::TertiaryMid]]; border-top:1px solid [[ColorPalette::TertiaryMid]]; border-right:2px solid [[ColorPalette::TertiaryDark]]; border-bottom:2px solid [[ColorPalette::TertiaryDark]];}
.popup hr {color:[[ColorPalette::PrimaryDark]]; background:[[ColorPalette::PrimaryDark]]; border-bottom:1px;}
.popup li.disabled {color:[[ColorPalette::TertiaryMid]];}
.popup li a, .popup li a:visited {color:[[ColorPalette::Foreground]]; border: none;}
.popup li a:hover {background:[[ColorPalette::SecondaryLight]]; color:[[ColorPalette::Foreground]]; border: none;}
.popup li a:active {background:[[ColorPalette::SecondaryPale]]; color:[[ColorPalette::Foreground]]; border: none;}
.popupHighlight {background:[[ColorPalette::Background]]; color:[[ColorPalette::Foreground]];}
.listBreak div {border-bottom:1px solid [[ColorPalette::TertiaryDark]];}

.tiddler .defaultCommand {font-weight:bold;}

.shadow .title {color:[[ColorPalette::TertiaryDark]];}

.title {color:[[ColorPalette::SecondaryDark]];}
.subtitle {color:[[ColorPalette::TertiaryDark]];}

.toolbar {color:[[ColorPalette::PrimaryMid]];}
.toolbar a {color:[[ColorPalette::TertiaryLight]];}
.selected .toolbar a {color:[[ColorPalette::TertiaryMid]];}
.selected .toolbar a:hover {color:[[ColorPalette::Foreground]];}

.tagging, .tagged {border:1px solid [[ColorPalette::TertiaryPale]]; background-color:[[ColorPalette::TertiaryPale]];}
.selected .tagging, .selected .tagged {background-color:[[ColorPalette::TertiaryLight]]; border:1px solid [[ColorPalette::TertiaryMid]];}
.tagging .listTitle, .tagged .listTitle {color:[[ColorPalette::PrimaryDark]];}
.tagging .button, .tagged .button {border:none;}

.footer {color:[[ColorPalette::TertiaryLight]];}
.selected .footer {color:[[ColorPalette::TertiaryMid]];}

.error, .errorButton {color:[[ColorPalette::Foreground]]; background:[[ColorPalette::Error]];}
.warning {color:[[ColorPalette::Foreground]]; background:[[ColorPalette::SecondaryPale]];}
.lowlight {background:[[ColorPalette::TertiaryLight]];}

.zoomer {background:none; color:[[ColorPalette::TertiaryMid]]; border:3px solid [[ColorPalette::TertiaryMid]];}

.imageLink, #displayArea .imageLink {background:transparent;}

.annotation {background:[[ColorPalette::SecondaryLight]]; color:[[ColorPalette::Foreground]]; border:2px solid [[ColorPalette::SecondaryMid]];}

.viewer .listTitle {list-style-type:none; margin-left:-2em;}
.viewer .button {border:1px solid [[ColorPalette::SecondaryMid]];}
.viewer blockquote {border-left:3px solid [[ColorPalette::TertiaryDark]];}

.viewer table, table.twtable {border:2px solid [[ColorPalette::TertiaryDark]];}
.viewer th, .viewer thead td, .twtable th, .twtable thead td {background:[[ColorPalette::SecondaryMid]]; border:1px solid [[ColorPalette::TertiaryDark]]; color:[[ColorPalette::Background]];}
.viewer td, .viewer tr, .twtable td, .twtable tr {border:1px solid [[ColorPalette::TertiaryDark]];}

.viewer pre {border:1px solid [[ColorPalette::SecondaryLight]]; background:[[ColorPalette::SecondaryPale]];}
.viewer code {color:[[ColorPalette::SecondaryDark]];}
.viewer hr {border:0; border-top:dashed 1px [[ColorPalette::TertiaryDark]]; color:[[ColorPalette::TertiaryDark]];}

.highlight, .marked {background:[[ColorPalette::SecondaryLight]];}

.editor input {border:1px solid [[ColorPalette::PrimaryMid]];}
.editor textarea {border:1px solid [[ColorPalette::PrimaryMid]]; width:100%;}
.editorFooter {color:[[ColorPalette::TertiaryMid]];}
.readOnly {background:[[ColorPalette::TertiaryPale]];}

#backstageArea {background:[[ColorPalette::Foreground]]; color:[[ColorPalette::TertiaryMid]];}
#backstageArea a {background:[[ColorPalette::Foreground]]; color:[[ColorPalette::Background]]; border:none;}
#backstageArea a:hover {background:[[ColorPalette::SecondaryLight]]; color:[[ColorPalette::Foreground]]; }
#backstageArea a.backstageSelTab {background:[[ColorPalette::Background]]; color:[[ColorPalette::Foreground]];}
#backstageButton a {background:none; color:[[ColorPalette::Background]]; border:none;}
#backstageButton a:hover {background:[[ColorPalette::Foreground]]; color:[[ColorPalette::Background]]; border:none;}
#backstagePanel {background:[[ColorPalette::Background]]; border-color: [[ColorPalette::Background]] [[ColorPalette::TertiaryDark]] [[ColorPalette::TertiaryDark]] [[ColorPalette::TertiaryDark]];}
.backstagePanelFooter .button {border:none; color:[[ColorPalette::Background]];}
.backstagePanelFooter .button:hover {color:[[ColorPalette::Foreground]];}
#backstageCloak {background:[[ColorPalette::Foreground]]; opacity:0.6; filter:alpha(opacity=60);}
/*}}}*/
</pre>
</div>
<div title="StyleSheetLayout">
<pre>/*{{{*/
* html .tiddler {height:1%;}

body {font-size:.75em; font-family:arial,helvetica; margin:0; padding:0;}

h1,h2,h3,h4,h5,h6 {font-weight:bold; text-decoration:none;}
h1,h2,h3 {padding-bottom:1px; margin-top:1.2em;margin-bottom:0.3em;}
h4,h5,h6 {margin-top:1em;}
h1 {font-size:1.35em;}
h2 {font-size:1.25em;}
h3 {font-size:1.1em;}
h4 {font-size:1em;}
h5 {font-size:.9em;}

hr {height:1px;}

a {text-decoration:none;}

dt {font-weight:bold;}

ol {list-style-type:decimal;}
ol ol {list-style-type:lower-alpha;}
ol ol ol {list-style-type:lower-roman;}
ol ol ol ol {list-style-type:decimal;}
ol ol ol ol ol {list-style-type:lower-alpha;}
ol ol ol ol ol ol {list-style-type:lower-roman;}
ol ol ol ol ol ol ol {list-style-type:decimal;}

.txtOptionInput {width:11em;}

#contentWrapper .chkOptionInput {border:0;}

.externalLink {text-decoration:underline;}

.indent {margin-left:3em;}
.outdent {margin-left:3em; text-indent:-3em;}
code.escaped {white-space:nowrap;}

.tiddlyLinkExisting {font-weight:bold;}
.tiddlyLinkNonExisting {font-style:italic;}

/* the 'a' is required for IE, otherwise it renders the whole tiddler in bold */
a.tiddlyLinkNonExisting.shadow {font-weight:bold;}

#mainMenu .tiddlyLinkExisting,
	#mainMenu .tiddlyLinkNonExisting,
	#sidebarTabs .tiddlyLinkNonExisting {font-weight:normal; font-style:normal;}
#sidebarTabs .tiddlyLinkExisting {font-weight:bold; font-style:normal;}

.header {position:relative;}
.header a:hover {background:transparent;}
.headerShadow {position:relative; padding:4.5em 0 1em 1em; left:-1px; top:-1px;}
.headerForeground {position:absolute; padding:4.5em 0 1em 1em; left:0; top:0;}

.siteTitle {font-size:3em;}
.siteSubtitle {font-size:1.2em;}

#mainMenu {position:absolute; left:0; width:10em; text-align:right; line-height:1.6em; padding:1.5em 0.5em 0.5em 0.5em; font-size:1.1em;}

#sidebar {position:absolute; right:3px; width:16em; font-size:.9em;}
#sidebarOptions {padding-top:0.3em;}
#sidebarOptions a {margin:0 0.2em; padding:0.2em 0.3em; display:block;}
#sidebarOptions input {margin:0.4em 0.5em;}
#sidebarOptions .sliderPanel {margin-left:1em; padding:0.5em; font-size:.85em;}
#sidebarOptions .sliderPanel a {font-weight:bold; display:inline; padding:0;}
#sidebarOptions .sliderPanel input {margin:0 0 0.3em 0;}
#sidebarTabs .tabContents {width:15em; overflow:hidden;}

.wizard {padding:0.1em 1em 0 2em;}
.wizard h1 {font-size:2em; font-weight:bold; background:none; padding:0; margin:0.4em 0 0.2em;}
.wizard h2 {font-size:1.2em; font-weight:bold; background:none; padding:0; margin:0.4em 0 0.2em;}
.wizardStep {padding:1em 1em 1em 1em;}
.wizard .button {margin:0.5em 0 0; font-size:1.2em;}
.wizardFooter {padding:0.8em 0.4em 0.8em 0;}
.wizardFooter .status {padding:0 0.4em; margin-left:1em;}
.wizard .button {padding:0.1em 0.2em;}

#messageArea {position:fixed; top:2em; right:0; margin:0.5em; padding:0.5em; z-index:2000; _position:absolute;}
.messageToolbar {display:block; text-align:right; padding:0.2em;}
#messageArea a {text-decoration:underline;}

.tiddlerPopupButton {padding:0.2em;}
.popupTiddler {position: absolute; z-index:300; padding:1em; margin:0;}

.popup {position:absolute; z-index:300; font-size:.9em; padding:0; list-style:none; margin:0;}
.popup .popupMessage {padding:0.4em;}
.popup hr {display:block; height:1px; width:auto; padding:0; margin:0.2em 0;}
.popup li.disabled {padding:0.4em;}
.popup li a {display:block; padding:0.4em; font-weight:normal; cursor:pointer;}
.listBreak {font-size:1px; line-height:1px;}
.listBreak div {margin:2px 0;}

.tabset {padding:1em 0 0 0.5em;}
.tab {margin:0 0 0 0.25em; padding:2px;}
.tabContents {padding:0.5em;}
.tabContents ul, .tabContents ol {margin:0; padding:0;}
.txtMainTab .tabContents li {list-style:none;}
.tabContents li.listLink { margin-left:.75em;}

#contentWrapper {display:block;}
#splashScreen {display:none;}

#displayArea {margin:1em 17em 0 14em;}

.toolbar {text-align:right; font-size:.9em;}

.tiddler {padding:1em 1em 0;}

.missing .viewer,.missing .title {font-style:italic;}

.title {font-size:1.6em; font-weight:bold;}

.missing .subtitle {display:none;}
.subtitle {font-size:1.1em;}

.tiddler .button {padding:0.2em 0.4em;}

.tagging {margin:0.5em 0.5em 0.5em 0; float:left; display:none;}
.isTag .tagging {display:block;}
.tagged {margin:0.5em; float:right;}
.tagging, .tagged {font-size:0.9em; padding:0.25em;}
.tagging ul, .tagged ul {list-style:none; margin:0.25em; padding:0;}
.tagClear {clear:both;}

.footer {font-size:.9em;}
.footer li {display:inline;}

.annotation {padding:0.5em; margin:0.5em;}

* html .viewer pre {width:99%; padding:0 0 1em 0;}
.viewer {line-height:1.4em; padding-top:0.5em;}
.viewer .button {margin:0 0.25em; padding:0 0.25em;}
.viewer blockquote {line-height:1.5em; padding-left:0.8em;margin-left:2.5em;}
.viewer ul, .viewer ol {margin-left:0.5em; padding-left:1.5em;}

.viewer table, table.twtable {border-collapse:collapse; margin:0.8em 1.0em;}
.viewer th, .viewer td, .viewer tr,.viewer caption,.twtable th, .twtable td, .twtable tr,.twtable caption {padding:3px;}
table.listView {font-size:0.85em; margin:0.8em 1.0em;}
table.listView th, table.listView td, table.listView tr {padding:0 3px 0 3px;}

.viewer pre {padding:0.5em; margin-left:0.5em; font-size:1.2em; line-height:1.4em; overflow:auto;}
.viewer code {font-size:1.2em; line-height:1.4em;}

.editor {font-size:1.1em;}
.editor input, .editor textarea {display:block; width:100%; font:inherit;}
.editorFooter {padding:0.25em 0; font-size:.9em;}
.editorFooter .button {padding-top:0; padding-bottom:0;}

.fieldsetFix {border:0; padding:0; margin:1px 0px;}

.zoomer {font-size:1.1em; position:absolute; overflow:hidden;}
.zoomer div {padding:1em;}

* html #backstage {width:99%;}
* html #backstageArea {width:99%;}
#backstageArea {display:none; position:relative; overflow: hidden; z-index:150; padding:0.3em 0.5em;}
#backstageToolbar {position:relative;}
#backstageArea a {font-weight:bold; margin-left:0.5em; padding:0.3em 0.5em;}
#backstageButton {display:none; position:absolute; z-index:175; top:0; right:0;}
#backstageButton a {padding:0.1em 0.4em; margin:0.1em;}
#backstage {position:relative; width:100%; z-index:50;}
#backstagePanel {display:none; z-index:100; position:absolute; width:90%; margin-left:3em; padding:1em;}
.backstagePanelFooter {padding-top:0.2em; float:right;}
.backstagePanelFooter a {padding:0.2em 0.4em;}
#backstageCloak {display:none; z-index:20; position:absolute; width:100%; height:100px;}

.whenBackstage {display:none;}
.backstageVisible .whenBackstage {display:block;}
/*}}}*/
</pre>
</div>
<div title="StyleSheetLocale">
<pre>/***
StyleSheet for use when a translation requires any css style changes.
This StyleSheet can be used directly by languages such as Chinese, Japanese and Korean which need larger font sizes.
***/
/*{{{*/
body {font-size:0.8em;}
#sidebarOptions {font-size:1.05em;}
#sidebarOptions a {font-style:normal;}
#sidebarOptions .sliderPanel {font-size:0.95em;}
.subtitle {font-size:0.8em;}
.viewer table.listView {font-size:0.95em;}
/*}}}*/
</pre>
</div>
<div title="StyleSheetPrint">
<pre>/*{{{*/
@media print {
#mainMenu, #sidebar, #messageArea, .toolbar, #backstageButton, #backstageArea {display: none !important;}
#displayArea {margin: 1em 1em 0em;}
noscript {display:none;} /* Fixes a feature in Firefox 1.5.0.2 where print preview displays the noscript content */
}
/*}}}*/
</pre>
</div>
<div title="ViewTemplate">
<pre>&lt;!--{{{--&gt;
&lt;div class='toolbar' role='navigation' macro='toolbar [[ToolbarCommands::ViewToolbar]]'&gt;&lt;/div&gt;
&lt;div class='title' macro='view title'&gt;&lt;/div&gt;
&lt;div class='subtitle'&gt;&lt;span macro='view modifier link'&gt;&lt;/span&gt;, &lt;span macro='view modified date'&gt;&lt;/span&gt; (&lt;span macro='message views.wikified.createdPrompt'&gt;&lt;/span&gt; &lt;span macro='view created date'&gt;&lt;/span&gt;)&lt;/div&gt;
&lt;div class='tagging' macro='tagging'&gt;&lt;/div&gt;
&lt;div class='tagged' macro='tags'&gt;&lt;/div&gt;
&lt;div class='viewer' macro='view text wikified'&gt;&lt;/div&gt;
&lt;div class='tagClear'&gt;&lt;/div&gt;
&lt;!--}}}--&gt;
</pre>
</div>

</div>
<!--POST-SHADOWAREA-->
<div id="storeArea"><div title="RefreshTiddlerCommand" server.title="RefreshTiddlerCommand" server.page.revision="1521867" server.etag="&quot;system-plugins_public/RefreshTiddlerCommand/1521867:8e27a0d6a5aadae7361507eb7ae77f1860931b91&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-plugins_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-plugins_public" server.permissions="read" server.content-type="text/javascript" modified="20131111192330" created="20131111192330" tags="excludeLists excludeSearch systemConfig" _hash="02e0b362ad77cbb6e902b176a082430649e798ac">
<pre>/***
|''Name''|RefreshTiddlerCommand|
|''Version''|0.3.0|
***/
//{{{
(function($) {

var cmd = config.commands.refreshTiddler = {
	text: "refresh",
	locale: {
		refreshing: "Refreshing tiddler..."
	},
	tooltip: "refresh this tiddler to be the one on the server",
	handler: function(ev, src, title) {
		var tiddler = store.getTiddler(title);
		if(!tiddler) {
			tiddler = new Tiddler(title);
			merge(tiddler.fields, config.defaultCustomFields);
		}
		$(story.getTiddler(title)).find(".viewer").
			empty().text(cmd.locale.refreshing);
		var dirtyStatus = store.isDirty();
		story.loadMissingTiddler(title, {
			"server.workspace": tiddler.fields["server.recipe"]  ? "recipes/" + tiddler.fields["server.recipe"] :
				tiddler.fields["server.workspace"] || "bags/"+tiddler.fields["server.bag"],
			"server.host": tiddler.fields["server.host"],
			"server.type": tiddler.fields["server.type"]
		}, function() {
			store.setDirty(dirtyStatus);
		});
	}
};

})(jQuery);
//}}}</pre>
</div>
<div title="cancelTiddler" server.title="cancelTiddler" server.page.revision="1521931" server.etag="&quot;system-images_public/cancelTiddler/1521931:2197b56cefc661d1b09606e590f4c0679e116528&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-images_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-images_public" server.permissions="read" server.content-type="image/svg+xml" modified="20131111192332" created="20131111192332" tags="excludeLists excludeSearch" _hash="7ec49872e728041385751b4252f6baab334f44ce">
<pre>&lt;svg xmlns="http://www.w3.org/2000/svg" xmlns:xl="http://www.w3.org/1999/xlink" version="1.1" viewBox="72 648 70 70" 
width="30" height="30"&gt;
&lt;g stroke="none" stroke-opacity="1" stroke-dasharray="none" fill="none" fill-opacity="1"&gt;
	&lt;g&gt;
		&lt;path d="M 77.59005 669.34003 C 71.532745 681.90424 73.714462 697.4441 84.135193 707.86475 
		C 97.315445 721.0451 118.684715 721.0451 131.8649 707.86475 
		C 145.04515 694.68457 145.04515 673.31537 131.8649 660.13513 
		C 121.4441 649.7141 105.90419 647.53253 93.339905 653.5899 L 102.047455 662.2976 
		C 109.58637 660.2373 117.987976 662.16803 123.90997 668.08997 
		C 132.69673 676.8767 132.69673 691.12317 123.90997 699.90985 
		C 115.12313 708.6966 100.87699 708.6966 92.09012 699.90985 
		C 86.168266 693.98804 84.23744 685.58643 86.297653 678.04755 Z M 72 648 L 72 668.25 L 78.75 661.49957 
		L 99.00019 681.7502 L 105.750175 675.00006 L 85.50013 654.75012 L 92.249985 648 Z" fill="black"
		class="glyph"/&gt;
	&lt;/g&gt;
&lt;/g&gt;
&lt;/svg&gt;</pre>
</div>
<div title="spaceIcon" server.title="spaceIcon" server.page.revision="1521883" server.etag="&quot;system-info_public/spaceIcon/1521883:9e95de739c8fe879e5cfea371e3b24d5dc07d1c0&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-info_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-info_public" server.permissions="read" server.content-type="" modified="20131111192330" created="20131111192330" tags="excludeLists excludeSearch" _hash="ef5f983ca36b19ed82d51224aee1c85d8fecb0a5">
<pre>A [[SiteIcon|SiteIcon tiddler]]@glossary helps provide some identity to your space.  Ideally it'd be a square and a minimum of 48*48 pixels size.  You can upload your site icon using the uploader below.

&lt;&lt;binaryUploadPublic title:SiteIcon&gt;&gt;</pre>
</div>
<div title="学习资料" server.title="学习资料" server.page.revision="2579915" server.etag="&quot;honly-666_public/%E5%AD%A6%E4%B9%A0%E8%B5%84%E6%96%99/2579915:a2ee8167e506633053d7ccbc01653c1fd16ee995&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20161102044627" created="20161102044627" tags="信息获取" _hash="06323c353ad88a9c5cefe867622183fc7ffd6b3a">
<pre>[[搜索引擎从入门到精通]]</pre>
</div>
<div title="歌曲" server.title="歌曲" server.page.revision="2580033" server.etag="&quot;honly-666_public/%E6%AD%8C%E6%9B%B2/2580033:5c68d06db4cb57a44dbc7ad71bb45d907c941256&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20161102131715" created="20161102131715" tags="" _hash="7e113c9752955f54ba78301157527e562ec361fb">
<pre>一路风景 瑜你同行
http://y.qq.com/portal/player.html</pre>
</div>
<div title="privateIcon" server.title="privateIcon" server.page.revision="1521894" server.etag="&quot;tiddlyspace/privateIcon/1521894:4cbc9ed31c3e4c2a8c64dd8a122d9a21e76484ef&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/tiddlyspace" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="tiddlyspace" server.permissions="read" server.content-type="image/png" modified="20131111192334" created="20131111192334" tags="excludeLists excludeSearch" _hash="94eabb8c954332020ab12d027656ddc3adb98c63">
<pre>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</pre>
</div>
<div title="抒情流行乐" server.title="抒情流行乐" server.page.revision="2579928" server.etag="&quot;honly-666_public/%E6%8A%92%E6%83%85%E6%B5%81%E8%A1%8C%E4%B9%90/2579928:6c04d4f27aed170c94d2261c64ddc83c9bb386f2&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20161102045731" created="20161102045644" tags="KIMI" _hash="4e0ca0be71cfc723b5db415d7f7be620091f43df">
<pre>环城巴士 —— 乔任梁

http://www.mtv123.com/mp3/65889/372852.shtml</pre>
</div>
<div title="TiddlyFileImporter" server.title="TiddlyFileImporter" server.page.revision="1521907" server.etag="&quot;tiddlyspace/TiddlyFileImporter/1521907:98a8717cb9cdc9f047a3c0db06f2de19e97af1ea&quot;" modifier="None" creator="None" server.workspace="bags/tiddlyspace" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="tiddlyspace" server.permissions="read" server.content-type="text/javascript" modified="20131111192332" created="20131111192332" tags="excludeLists excludeSearch systemConfig" _hash="948bb64604a46205267e446af0f638c4e8fc3c8e">
<pre>/***
|''Name''|TiddlyFileImporter|
|''Version''|0.3.8|
|''Author''|Ben Gillies|
|''Type''|plugin|
|''Description''|Upload a TiddlyWiki file to TiddlyWeb, and import the tiddlers.|
!Usage
Upload a TiddlyWiki file to TiddlyWeb, and import the tiddlers.
!Requires
tiddlyweb
tiddlywebplugins.reflector
!Code
***/
//{{{
(function($){
if(!version.extensions.TiddlyFileImporter)
{ //# ensure that the plugin is only installed once
	version.extensions.TiddlyFileImporter = { installed: true };
}

config.macros.fileImport = {
	reflectorURI: '/reflector?csrf_token=%0',
	incorrectTypeError: 'Incorrect File Type. You must upload a TiddlyWiki',
	uploadLabel: 'Upload',
	uploadLabelPrompt: 'Import tiddlers from this TiddlyWiki',
	step1FileText: 'File:',
	step1PostText: 'In the next screen you will select the tiddlers to import.',
	step1Title: 'Step 1: Pick a TiddlyWiki to import',
	step1TypeChooser: 'Import From:',
	step3Html: ['&lt;input type="hidden" name="markList" /&gt;',
		'&lt;input type="hidden" checked="true" name="chkSync" /&gt;',
		'&lt;input type="hidden" name="chkSave" /&gt;',
		'&lt;input type="hidden" name="txtSaveTiddler" /&gt;'].join(),

	handler: function(place, macroName, params, wikifier, paramString) {
		var wizard = new Wizard();
		wizard.createWizard(place, 'Import a TiddlyWiki');
		this.restart(wizard);
	},

	restart: function(wizard) {
		var me = config.macros.fileImport;
		wizard.addStep(me.step1Title, ['&lt;input type="hidden" ',
			'name="markList" /&gt;'].join(""));
		var markList = wizard.getElement('markList');
		var uploadWrapper = document.createElement('div');
		markList.parentNode.insertBefore(uploadWrapper, markList);
		uploadWrapper.setAttribute('refresh', 'macro');
		uploadWrapper.getAttribute('macroName', 'fileImport');
		var iframeName = 'reflectorImporter' + Math.random().toString();
		me.createForm(uploadWrapper, wizard, iframeName);
		$(uploadWrapper).append('&lt;p&gt;' + me.step1PostText + '&lt;/p&gt;');
		wizard.setValue('serverType', 'tiddlyweb');
		wizard.setValue('adaptor', new config.adaptors.file());
		wizard.setValue('host', config.defaultCustomFields['server.host']);
		wizard.setValue('context', {});
		var iframe = $(['&lt;iframe name="' + iframeName + '" ',
			'style="display: none" /&gt;'].join("")).appendTo(uploadWrapper);
		var onSubmit = function(ev) {
			var uploadType = $('select[name=uploadtype]', wizard.formElem).val();
			if (uploadType == "file") {
				// set an onload ready to hijack the form
				me.setOnLoad(uploadWrapper, wizard, iframe[0]);
				wizard.importType = 'file';
				wizard.formElem.submit();
			} else {
				var csrf_token = config.extensions.tiddlyspace.getCSRFToken();
				$.ajax({
					url: "%0/reflector?csrf_token=%1".format(
						config.defaultCustomFields["server.host"], csrf_token),
					type: "POST",
					dataType: "text",
					data: {
						uri: $("input", ".importFrom", wizard.formElem).val()
					},
					success: function(data, txtStatus, xhr) {
						wizard.POSTResponse = data;
						me.importTiddlers(uploadWrapper, wizard);
					},
					error: function(xhr, txtStatus, error) {
						displayMessage(["There was an error fetching the ",
							'url: ', txtStatus].join(""));
						me.restart(wizard);
					}
				});
				return false;
			}
		};
		wizard.setButtons([{
			caption: me.uploadLabel,
			tooltip: me.uploadLabelPrompt,
			onClick: onSubmit
		}]);
		$(wizard.formElem).submit(function(ev) {
			onSubmit(ev);
			ev.preventDefault();
		});
	},

	createForm: function(place, wizard, iframeName) {
		var form = wizard.formElem;
		var me = config.macros.fileImport;
		form.action = me.reflectorURI.format(
			config.extensions.tiddlyspace.getCSRFToken());
		form.enctype = 'multipart/form-data';
		form.encoding = 'multipart/form-data';
		form.method = 'POST';
		form.target = iframeName;
		onSelectChange = function(e) {
			var changeTo = $(this).val();
			if (changeTo == "file") {
				$(".importFrom").html('%0 &lt;input type="file" name="file" /&gt;'.
					format(me.step1FileText));
			} else {
				$(".importFrom").html('URL: &lt;input type="text" name="uri" /&gt;'
					+ ' Do you want &lt;a target="_blank" href="http://faq.tiddlyspace.com/How%20do%20I%20include%2Fexclude%20spaces%3F"&gt;inclusion&lt;/a&gt; instead?');
			}
		};
		$(place).append('&lt;span&gt;%0&lt;/span&gt;'.format(me.step1TypeChooser)).
			append($(['&lt;select name="uploadtype"&gt;&lt;option value="file" selected="selected"&gt;file',
				'&lt;option value="uri"&gt;url&lt;/select&gt;'].join("")).change(onSelectChange)).
			append('&lt;div class="importFrom"&gt;%0&lt;input type="file" name="file" /&gt;&lt;/div&gt;'.
					format(me.step1FileText));
	},

	setOnLoad: function(place, wizard, iframe) {
		var me = config.macros.fileImport;
		var loadHandler = function() {
			me.importTiddlers.apply(this, [place, wizard, iframe]);
		};
		iframe.onload = loadHandler;
		completeReadyStateChanges = 0;
		iframe.onreadystatechange = function() {
			if (++(completeReadyStateChanges) == 5) {
				loadHandler();
			}
		};
	},

	importTiddlers: function(place, wizard, iframe) {
		var tmpStore = new TiddlyWiki();
		var POSTedWiki = "";
		if (wizard.importType == "file") {
			try {
				POSTedWiki= iframe.contentWindow
					.document.documentElement.innerHTML;
			} catch(e) {
				displayMessage(config.macros.fileImport.incorrectTypeError);
				config.macros.fileImport.restart(wizard);
				return;
			}
			// now we are done, so remove the iframe
			$(iframe).remove();
		} else {
			POSTedWiki = wizard.POSTResponse;
		}

		tmpStore.importTiddlyWiki(POSTedWiki);
		var newTiddlers = tmpStore.getTiddlers();
		var workspace = config.defaultCustomFields['server.workspace'];
		var context = {
			status: true,
			statusText: 'OK',
			httpStatus: 200,
			adaptor: wizard.getValue('adaptor'),
			tiddlers: newTiddlers
		};
		context.adaptor.store = tmpStore;
		wizard.setValue('context', context);
		wizard.setValue('workspace', workspace);
		wizard.setValue('inFileImport', true);
		config.macros.importTiddlers.onGetTiddlerList(context, wizard);
	}
};

var _onGetTiddler = config.macros.importTiddlers.onGetTiddler;
config.macros.importTiddlers.onGetTiddler = function(context, wizard) {
	if (wizard.getValue('inFileImport')) {
		var me = config.macros.importTiddlers;
		if(!context.status)
			displayMessage("Error in importTiddlers.onGetTiddler: " + context.statusText);
		var tiddler = context.tiddler;
		var fields = tiddler.fields;
		merge(fields, config.defaultCustomFields);
		fields["server.workspace"] = wizard.getValue('workspace');
		delete fields['server.permissions'];
		delete fields['server.bag'];
		fields['server.page.revision'] = 'false';
		delete fields['server.recipe'];
		fields.changecount = 1;
		store.suspendNotifications();
		store.saveTiddler(tiddler.title, tiddler.title, tiddler.text,
			tiddler.modifier, tiddler.modified, tiddler.tags, tiddler.fields,
			false, tiddler.created);
		store.resumeNotifications();
		var remainingImports = wizard.getValue("remainingImports")-1;
		wizard.setValue("remainingImports",remainingImports);
		if(remainingImports === 0) {
			if(context.isSynchronous) {
				store.notifyAll();
				refreshDisplay();
			}
			wizard.setButtons([
					{caption: me.doneLabel, tooltip: me.donePrompt, onClick: me.onClose}
				],me.statusDoneImport);
			autoSaveChanges();
		}
	} else {
		_onGetTiddler.apply(this, arguments);
	}
};

var _onCancel = config.macros.importTiddlers.onCancel;
config.macros.importTiddlers.onCancel = function(e)
{
	var wizard = new Wizard(this);
	if (!wizard.getValue('inFileImport')) {
		return _onCancel.apply(this, arguments);
	}
	var place = wizard.clear();
	config.macros.fileImport.restart(wizard);
	return false;
};

var _step3Html = config.macros.importTiddlers.step3Html;
var _onGetTiddlerList = config.macros.importTiddlers.onGetTiddlerList;
config.macros.importTiddlers.onGetTiddlerList = function(context, wizard) {
	var fileImport = config.macros.fileImport;
	var importTiddlers = config.macros.importTiddlers;
	if (wizard.getValue('inFileImport')) {
		importTiddlers.step3Html = fileImport.step3Html;
	} else {
		importTiddlers.step3Html = _step3Html;
	}
	_onGetTiddlerList.apply(this, arguments);
};
})(jQuery);
//}}}</pre>
</div>
<div title="第1次翻译作业——目录和图表" server.title="第1次翻译作业——目录和图表" server.page.revision="2579867" server.etag="&quot;honly-666_public/%E7%AC%AC1%E6%AC%A1%E7%BF%BB%E8%AF%91%E4%BD%9C%E4%B8%9A%E2%80%94%E2%80%94%E7%9B%AE%E5%BD%95%E5%92%8C%E5%9B%BE%E8%A1%A8/2579867:28dfd4d206f09f4664289276f4db07f7f7ee6367&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20161102042017" created="20160923144331" tags="14信管作业" _hash="24b495a0137459e0267e30dd6a54453c7653796c">
<pre>Figures
the four basic shapes for modeling the how using the MS-Visio workflow chart
这四个基本形状建模如何使用MS-Visio工作流图表
The "where" perspective——An organization chart using an MS-Visio organization chart template
从“where”的角度来看,一个组织图使用一个MS-Visio组织结构图模板
Cross-functional flow diagram using MS-Visio cross-flowchart templates
跨功能流程图使用MS-Visio cross-flowchart模板

Tables
Intermediary structures in e-commerce 
 电子商务中介机构
IT impact on trade processes
  IT对贸易过程的影响
IT impact on trade context            
IT对贸易环境的影响


</pre>
</div>
<div title="_reply" server.title="_reply" server.page.revision="1521889" server.etag="&quot;tiddlyspace/_reply/1521889:cd747d5099603c267cf78150e9abd49e77ac1bdf&quot;" modifier="bengillies" creator="bengillies" server.workspace="bags/tiddlyspace" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="tiddlyspace" server.permissions="read" server.content-type="text/html" modified="20131111192332" created="20131111192332" tags="excludeLists excludeMissing excludeSearch" _hash="01c7fff74dd8fd746394153d7c586fee665e4ce6">
<pre>&lt;!DOCTYPE html&gt;
&lt;html lang="en"&gt;
&lt;head&gt;
	&lt;meta charset="UTF-8"&gt;
	&lt;meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1"&gt;
	&lt;title&gt;Reply&lt;/title&gt;
	&lt;link rel="stylesheet" href="//tiddlyspace.com/bags/benspa_public/tiddlers/bootvelcro.css"&gt;
	&lt;style&gt;
		html,
		body {
			overflow: hidden;
			background-color: transparent;
		}

		#container {
			/* prevent a fouc if no images present */
			display: none;
		}

		.modal-header {
			border-bottom: none;
			padding: 5px 0 0;
			position: absolute;
			width: 100%;
			background-color: #e0e0e0;
			-webkit-border-radius: 6px 6px 0 0;
			-moz-border-radius: 6px 6px 0 0;
			border-radius: 6px 6px 0 0;
			cursor: move;
		}

		.form-actions {
			position: absolute;
			bottom: 0;
			box-sizing: border-box;
			-moz-box-sizing: border-box;
			width: 100%;
			margin: 0;
			border-radius: 0 0 6px 6px;
			background-color: #e0e0e0;
			border-top: 1px solid gray;
		}

		.form-actions input.btn {
			width: auto;
			float: right;
			margin: 0 0.2em;
		}

		.closeBtn {
			background-color: #DCE7F1 !important;
		}

		.primary {
			background-color: #09F !important;
		}

		h1 {
			margin-bottom: 9px;
			margin-top: 9px;
		}

		body {
			width: 100%;
			height: 100%;
			position: absolute;
		}

		.modal {
			margin: 10px;
			top: 0;
			left: 0;
			bottom: 0;
			width: 510px;
			position: absolute;
			box-shadow: #444 0px 0px 10px 2px;
			border-radius: 6px;
			background-color: white;
			border: 1px solid gray;
			background-color: #F0F4F8;
		}

		label em {
			cursor: pointer;
		}

		.modal-body {
			overflow: auto;
			position: absolute;
			top: 0;
			bottom: 0;
			left: 0;
			right: 0;
			margin: 65px 20px 67px;
			background-color: transparent;
		}

		.nav-tabs {
			padding-left: 1%;
			margin: 0;
			width: 99%;
			border-color: gray;
		}

		.nav-tabs &gt; li {
			cursor: pointer;
		}

		.nav-tabs &gt; li &gt; a {
			line-height: 2.4em;
			font-weight: bold;
			font-size: 100%;
		}

		.nav-tabs &gt; li.active &gt; a{
			background-color: #F0F4F8;
			border-color: gray;
			border-bottom-color: #F0F4F8;
		}

		.active {
			display: block;
		}

		input,
		textarea,
		select,
		.uneditable-input {
			color: #606060;
		}

		.imagePicker {
			-moz-box-shadow: inset 0 1px 3px rgba(0, 0, 0, 0.1);
			-webkit-box-shadow: inset 0 1px 3px rgba(0, 0, 0, 0.1);
			box-shadow: inset 0 1px 3px rgba(0, 0, 0, 0.1);
			border: 1px solid #CCC;
			height: 110px;
			overflow: auto;
			-webkit-border-radius: 3px;
			-moz-border-radius: 3px;
			border-radius: 3px;
			margin-left: 0;
		}

		.imagePicker img {
			margin: 5px;
			border: 2px solid transparent;
		}

		.imagePicker .current {
			border: 2px dotted #555;
		}

		label {
			font-weight: bold;
		}

		.form-actions label {
			float: left;
			margin-top: 0.75em;
		}

		fieldset input,
		fieldset textarea {
			width: 90%;
			border-color: gray;
		}

		@media all and (max-width: 550px) {
			.modal {
				width: 95%;
			}
		}

		#help {
			position: absolute;
			border: 0;
			right: 4px;
			top: 5px;
			text-indent: -9999px;
			color: transparent;
			height: 16px;
			width: 16px;
			background: none;
			background-image: url(/bags/common/tiddlers/help.png);
			background-repeat: no-repeat;
			background-color: white;
			z-index: 2;
			border-radius: 10px;
		}

		#help-info {
			padding: 0;
			border: 1px solid gray;
			width: 60%;
			height: 50px;
			color: #404040;
			background-color: white;
			position: absolute;
			top: 5px;
			right: 5px;
			z-index: 1;
			cursor: auto;
			border-radius: 5px;

		}

		#help-info p {
			padding: 10px 25px;
			margin-bottom: 0;
		}
	&lt;/style&gt;
&lt;/head&gt;
&lt;body&gt;
	&lt;div id="container"&gt;
		&lt;form action="#" class="modal"&gt;
			&lt;div class="modal-header"&gt;
				&lt;button id="help"&gt;help&lt;/button&gt;
				&lt;div id="help-info" style="display:none;"&gt;&lt;p&gt;
				Found something interesting? Write about it in your own space. &lt;a href="//docs.tiddlyspace.com/Reply to this Tiddler" target="_blank"&gt;Find out more&lt;/a&gt;
				&lt;/p&gt;&lt;/div&gt;
				&lt;ul class="nav nav-tabs" data-tabs="tabs"&gt;
					&lt;li class="active" data-tab-name="post"&gt;&lt;a href="#postForm"&gt;Reply&lt;/a&gt;&lt;/li&gt;
				&lt;/ul&gt;
			&lt;/div&gt;


			&lt;fieldset id="postForm" class="modal-body"&gt;
				&lt;label&gt;Title
					&lt;input type="text" name="title"&gt;
				&lt;/label&gt;
				&lt;input type="hidden" name="url"&gt;
				&lt;label&gt;Post
					&lt;textarea name="text" rows="8"&gt;&lt;/textarea&gt;
				&lt;/label&gt;
				&lt;label&gt;Tags
					&lt;input type="text" name="tags" value=""&gt;
				&lt;/label&gt;
			&lt;/fieldset&gt;


			&lt;div class="form-actions"&gt;
				&lt;label class="checkbox"&gt;
					&lt;input type="checkbox" name="private" val="private"&gt;
					keep private
				&lt;/label&gt;
				&lt;input type="submit" class="btn primary btn-large" value="Done"&gt;
				&lt;input type="button" class="btn btn-large closeBtn" value="Cancel"&gt;
			&lt;/div&gt;
		&lt;/form&gt;
	&lt;/div&gt;

	&lt;script type="text/javascript"
            src="/bags/common/tiddlers/jquery.js"&gt;&lt;/script&gt;
	&lt;script type="text/javascript" src="/bags/tiddlyspace/tiddlers/chrjs"&gt;&lt;/script&gt;
	&lt;script type="text/javascript" src="/bags/common/tiddlers/_reply.js"&gt;&lt;/script&gt;
&lt;/body&gt;
&lt;/html&gt;</pre>
</div>
<div title="_account" server.title="_account" server.page.revision="1521899" server.etag="&quot;tiddlyspace/_account/1521899:11b9e129ad03139840627c149b1e01667e7255d7&quot;" modifier="None" creator="None" server.workspace="bags/tiddlyspace" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="tiddlyspace" server.permissions="read" server.content-type="text/html" modified="20131111192332" created="20131111192332" tags="excludeLists excludeMissing excludeSearch" _hash="96201fdb51bfa585c117321c84d64d2fb9a3df71">
<pre>&lt;!DOCTYPE html&gt;
&lt;html&gt;
&lt;head&gt;
	&lt;meta http-equiv="Content-Type" content="text/html;charset=utf-8"&gt;
	&lt;title&gt;Account&lt;/title&gt;
	&lt;link href="/bags/common/tiddlers/profile.css" type='text/css' rel='stylesheet' &gt;
	&lt;link href="/bags/common/tiddlers/admin.css" type='text/css' rel='stylesheet' &gt;
	&lt;link href="/bags/common/tiddlers/jquery-ui.custom.css" type='text/css' rel='stylesheet' &gt;
&lt;/head&gt;
&lt;body&gt;

&lt;div id="container"&gt;
	&lt;div class="main section"&gt;
		&lt;a class="app" href="/"&gt;home&lt;/a&gt;
		&lt;div class="left"&gt;
		&lt;div id="siteiconArea"&gt;
		&lt;h2&gt;User Icon&lt;/h2&gt;
		&lt;div&gt;
			&lt;img id="siteicon" class="siteicon"&gt;
			&lt;form id="upload" method="POST" enctype="multipart/form-data"&gt;
				&lt;input type="hidden" name="title" value="SiteIcon" /&gt;
				&lt;input type="hidden" name="tags" value="excludeLists"&gt;
				&lt;input type="hidden" name="csrf_token" class="csrf" /&gt;
				&lt;input type="file" name="file" accept="image/*" /&gt;
				&lt;input type="submit" value="upload" /&gt;
			&lt;/form&gt;
			&lt;div id="dropzone"&gt;Drop file here
				&lt;img class="notloading" src="/bags/common/tiddlers/ajax-loader.gif" alt="submitting SiteIcon" /&gt;
			&lt;/div&gt;
		&lt;/div&gt;
		&lt;/div&gt;
		&lt;h2&gt;Find Space&lt;/h2&gt;
		&lt;form class="spaceSearch"&gt;
			&lt;input class="inputBox" type="text" placeholder="find space" /&gt;
			&lt;a href="http://docs.tiddlyspace.com/What%20is%20a%20Space%3F" class="help"
				title="What is a space?"&gt;What is a space?&lt;/a&gt;
			&lt;button&gt;view all&lt;/button&gt;
		&lt;/form&gt;
		&lt;div class='list-container'&gt;
			You are a member of the following spaces:
			&lt;ul class='ts-space-search'&gt;
			&lt;/ul&gt;
		&lt;/div&gt;
		&lt;h2&gt;Create New Space&lt;/h2&gt;
		&lt;form class="ts-spaces"&gt;
			&lt;input class="inputBox" type="text" name="spacename" placeholder="space name"&gt;&lt;span class="hostSuffix"&gt;.tiddlyspace.com&lt;/span&gt;
			&lt;input type="submit" value="Create Space" /&gt;
		&lt;/form&gt;
		&lt;/div&gt;
		&lt;div class="right"&gt;
		&lt;h2&gt;Change Password&lt;/h2&gt;
		&lt;form class="ts-password"&gt;
			&lt;input class="inputBox" placeholder="existing password" type="password" name="password"&gt;
			&lt;input class="inputBox" placeholder="new password" type="password" name="new_password"&gt;
			&lt;input class="inputBox" placeholder="new password"	type="password" name="new_password_confirm"&gt;
			&lt;input type="submit" value="Change password"&gt;
		&lt;/form&gt;
		&lt;h2&gt;OpenID&lt;/h2&gt;
		&lt;h3&gt;Why OpenID?&lt;/h3&gt;
		&lt;a href="http://openid.net/"&gt;&lt;img src="/bags/common/tiddlers/openid.png" alt="openid" &gt;&lt;/a&gt;&lt;br /&gt;
		Use just one username and password across hundreds of OpenID-enabled sites.&lt;br /&gt;
		It's an open standard.&lt;br /&gt;
		&lt;a href="http://openid.net/what/"&gt;learn more&lt;/a&gt;
		&lt;ul class="ts-identities"&gt;&lt;/ul&gt;
		&lt;form class="ts-openid" target="_top"&gt;
			&lt;div&gt;
				Add an openid:
			&lt;/div&gt;
			&lt;input class="inputBox" type="text" name="openid" placeholder="your openid" /&gt;
			&lt;input type="submit" value="Register" /&gt;
			&lt;a href="http://openid.net/get-an-openid/" class="help"
			title="What is an open id?"&gt;What is an open id?&lt;/a&gt;
		&lt;/form&gt;
		&lt;/div&gt;
		&lt;div class="clear"&gt;&lt;/div&gt;
	&lt;/div&gt;
&lt;/div&gt;
&lt;script src="/bags/common/tiddlers/backstage.js"&gt;&lt;/script&gt;
&lt;script src='/bags/common/tiddlers/jquery.js'&gt;&lt;/script&gt;
&lt;script src='/bags/tiddlyspace/tiddlers/chrjs'&gt;&lt;/script&gt;
&lt;script src='/bags/common/tiddlers/chrjs.space'&gt;&lt;/script&gt;
&lt;script src='/bags/common/tiddlers/chrjs.users'&gt;&lt;/script&gt;
&lt;script src='/bags/common/tiddlers/chrjs.identities'&gt;&lt;/script&gt;
&lt;script src="/bags/common/tiddlers/jquery-ui.custom.js"&gt;&lt;/script&gt;
&lt;script src='/bags/common/tiddlers/jquery-form.js'&gt;&lt;/script&gt;
&lt;script src="/bags/common/tiddlers/siteiconupload.js"&gt;&lt;/script&gt;
&lt;script src='/bags/common/tiddlers/ts.js'&gt;&lt;/script&gt;
&lt;script src="/status.js"&gt;&lt;/script&gt;
&lt;script type="text/javascript"&gt;
/*
 * jQuery UI Autocomplete HTML Extension
 *
 * Copyright 2010, Scott González (http://scottgonzalez.com)
 * Dual licensed under the MIT or GPL Version 2 licenses.
 *
 * http://github.com/scottgonzalez/jquery-ui-extensions
 */
(function( $ ) {

var proto = $.ui.autocomplete.prototype,
	initSource = proto._initSource;

function filter( array, term ) {
	var matcher = new RegExp( $.ui.autocomplete.escapeRegex(term), "i" );
	return $.grep( array, function(value) {
		return matcher.test( $( "&lt;div&gt;" ).html( value.label || value.value || value ).text() );
	});
}

$.extend( proto, {
	_initSource: function() {
		if ( this.options.html &amp;&amp; $.isArray(this.options.source) ) {
			this.source = function( request, response ) {
				response( filter( this.options.source, request.term ) );
			};
		} else {
			initSource.call( this );
		}
	},

	_renderItem: function( ul, item) {
		return $( "&lt;li&gt;&lt;/li&gt;" )
			.data( "item.autocomplete", item )
			.append( $( "&lt;a&gt;&lt;/a&gt;" )[ this.options.html ? "html" : "text" ]( item.label ) )
			.appendTo( ul );
	}
});

})( jQuery );

/***
_accounts application specific javascript
***/
var link;
ts.init(function(ts) {
	if(ts.user.anon) { // redirect to homepage when user not logged in
		window.location = ts.getHost();
	} else if(ts.user.name === ts.currentSpace){
		initSiteIconUpload(ts.user.name);
	} else {
		link = $("&lt;a /&gt;").attr("href", ts.getHost(ts.user.name) + "/_account").text("Change User Icon");
		$("#siteiconArea div").empty().append(link);
	}
	$(".hostSuffix").text("." + ts.getHost("").split("//")[1]);
	ts.getSpaces(function(spaces) {
		$("&lt;div class='info' /&gt;").text("You have " + spaces.length + " spaces.").insertBefore($(".spaceSearch")[0]);
		$("form.spaceSearch input").autocomplete({
			html: true,
			source: function(req, response) {
				ts.getSpaces(function(spaces) {
					var selected = [];
					for(var i = 0; i &lt; spaces.length; i++) {
						var space = spaces[i];
						if(space.name.indexOf(req.term) &gt; -1) {
							var host = ts.getHost(space.name) ;
							var img = host + "/SiteIcon";
							selected.push({
								value: space.name,
								label: '&lt;a href="' + host + '" target="_parent" class="autocompleteLink"&gt;&lt;img src="' + img + '" style="height:24px;width:auto;max-height:24px;max-width:24px;"/&gt;' + space.name + '&lt;/a&gt;'
							});
						}
					}
					response(selected);
				});
			},
			select: function(event, ui) {
				window.top.location = ts.getHost(ui.item.value);
			}
		});

		var $ul = $('.ts-space-search');
		$.each(spaces, function(i, space) {
			$ul.append($('&lt;li/&gt;').html($('&lt;a/&gt;').attr('href', space.uri)
				.text(space.name)));
		});

		$('form.spaceSearch button').click(function(ev) {
			$('.list-container').slideToggle('fast');
			ev.preventDefault();
			return false;
		});
	});
});

if(window != window.top) {
	$("html").addClass("iframeMode");
	$("a").live("click",function(ev) {
		$(ev.target).attr("target", "_parent");
	});
}
&lt;/script&gt;
&lt;!--[if lt IE 8]&gt;
&lt;script type="text/javascript" src="/bags/common/tiddlers/json2.js"&gt;&lt;/script&gt;
&lt;![endif]--&gt;
&lt;/body&gt;
&lt;/html&gt;</pre>
</div>
<div title="喜剧" server.title="喜剧" server.page.revision="2579930" server.etag="&quot;honly-666_public/%E5%96%9C%E5%89%A7/2579930:c174d0fb09e523c0fe45f79bac5f32541ad8f0fa&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20161102045955" created="20161102045955" tags="娱乐" _hash="8522a69c5b128f9062b05a77ae26c22607ce8501">
<pre>王牌斗王牌

http://www.360kan.com/m/gqbnZhH2RHH2SB.html</pre>
</div>
<div title="第3次翻译作业修改后的——方法和目标" server.title="第3次翻译作业修改后的——方法和目标" server.page.revision="2566069" server.etag="&quot;honly-666_public/%E7%AC%AC3%E6%AC%A1%E7%BF%BB%E8%AF%91%E4%BD%9C%E4%B8%9A%E4%BF%AE%E6%94%B9%E5%90%8E%E7%9A%84%E2%80%94%E2%80%94%E6%96%B9%E6%B3%95%E5%92%8C%E7%9B%AE%E6%A0%87/2566069:ab38c75b4424ce36cdc215cd256e38161fce3a2b&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="201609270509" created="20160923154304" tags="第二次的翻译——修改后的" _hash="2fd2ceb6e32bb919ec0957f7967195c72b7c81a4">
<pre>这本书的目的是为给读者提供一个充分理解信息管理的机会，在全面理解的基础上我们可以按照DavidKolb的观点，即知识可以有两个基本范围（抽象与具体，反思与实验），并且学习是一个在它们之间不断循环的过程。根据这些，我们的目标有：
一、抽象理解：这意味着要向读者解释一些基本的术语，这将在每一章节中从不同的视角对信息的概念进行解释，从哲学的概念和信息管理作为主要的方法两个方面来进行探讨。
二、实验：我们通过提供信息管理的方法和技术来挑战读者，并且在信息的管理中描述和应用这些概念。
三、具体的经验：我们向读者说明抽象哲学观念的适用性，利用有关信息管理的方法和技术来解决具体的日常问题。在这本书的实例中，读者必须通过所提供的实际例子和分配的任务来使用现有的软件工具分析具体问题。
四、反思：我们以一种批判性的思考方式来挑战读者在任务中阅读和尝试的东西。我们会引导他们发现他们将来会在学习生涯中遇到的挑战。来做这个挑战的一个好方法是通过小组的努力，因此安排一个可以讨论他们所阅读的和所做的通知平台对读者来说是明智的。这可以很容易地完成，读者在学习理解告知挑战的过程是第一步，也就是为了避免误导他人和对读者来说没有意义，于是可以通过电子手段共同创造实用的知识，谷歌在这方面就给读者提供了一个很好的机会。
 
通过读了这本书，读者会有以下几个收获

1.理解和识别不同的信息管理的方法和它们的优缺点，以及不同方法所带来的附加价值。
2.学会创造简单的商业和现实管理模型来具体说明企业管理和公共政策执行的信息需求。
3.理解的关键问题是翻译抽象信息需要相关的信息收集、信息加工处理和有代表性的程序。
4.理解一些在组织中的复杂的管理信息和使用信息系统所遇到的挑战是最重要的
5.开发反思和分析信息的能力来推出消息通知、信息管理和信息技术的使用。这些功能将在你的整个职业生涯都有价值,也将使你对未来批判性的诊断成为可能，还可以获得任何新的瞬态信息技术的机会。 因此我致力于讨论信息管理作为一个人与生俱来的能力,而不是它的支持性技术。
       这些经验教训、洞察力和技能对任何本科工商管理、公共管理、社会科学和经济学
层次的学生来说都是很关键的。不过这本书也可能在信息基础和信息传递方面为任何一个对此感兴趣的人服务。
</pre>
</div>
<div title="SpaceSettings" server.title="SpaceSettings" server.page.revision="1521882" server.etag="&quot;system-info_public/SpaceSettings/1521882:9320875c08449122883edf61550c8c38d0305594&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-info_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-info_public" server.permissions="read" server.content-type="" modified="20131111192330" created="20131111192330" tags="excludeLists excludeMissing excludeSearch" _hash="59d90cba2585970233eb03744888f06cec46918d">
<pre>!Upload an icon
&lt;&lt;tiddler spaceIcon&gt;&gt;
!Describe your space
If you haven't already done so, you should provide a brief decscription of yourself and what you're using this space for. To do this, just edit the [[SiteInfo]] tiddler (keeping the title the same of course).

!Change the title
&lt;&lt;tiddler spaceTitle&gt;&gt;
!Change the theme
&lt;&lt;tiddler colorScheme&gt;&gt;
!Change the menu
If you'd like to change the menu items along the top, you can edit the [[MainMenu]] tiddler.

!Change the default tiddlers
&lt;&lt;tiddler setDefaultTiddlers&gt;&gt;
!More Advanced customisations
If you know HTML and CSS, you can edit some or all of the following tiddlers to customise your space further:
* PageTemplate
* EditTemplate
* ViewTemplate
* StyleSheet</pre>
</div>
<div title="个人简介" server.title="个人简介" server.page.revision="2580043" server.etag="&quot;honly-666_public/%E4%B8%AA%E4%BA%BA%E7%AE%80%E4%BB%8B/2580043:406f6d196d067c91eea3b205e5e9f4a680a2e3df&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20161102133209" created="20161102131131" tags="" _hash="b64c685e3b493afe27cb5e777002621a0be779d3">
<pre>http://baike.so.com/doc/23637602-24191855.html</pre>
</div>
<div title="电影" server.title="电影" server.page.revision="2580028" server.etag="&quot;honly-666_public/%E7%94%B5%E5%BD%B1/2580028:93ebad65c76968f7a3030eba0335efe8af18fd54&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20161102131424" created="20161102131409" tags="" _hash="094b81ac922e2ad71d0b34cddaf6863299e46c69">
<pre>枪炮腰花
http://baike.so.com/doc/24049295-24631904.html</pre>
</div>
<div title="第1次翻译作业——目录和图[" server.title="第1次翻译作业——目录和图[" server.page.revision="2579877" server.etag="&quot;honly-666_public/%E7%AC%AC1%E6%AC%A1%E7%BF%BB%E8%AF%91%E4%BD%9C%E4%B8%9A%E2%80%94%E2%80%94%E7%9B%AE%E5%BD%95%E5%92%8C%E5%9B%BE%5B/2579877:ad651720a55540571f0e72891bca454d4706c9bf&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20161102042900" created="20161102042900" tags="" _hash="40c5dee8fef0a2819ac9ddad9f62d81c757c52bc">
<pre>Type the text for '第1次翻译作业——目录和图表]]</pre>
</div>
<div title="TiddlySpaceConfig" server.title="TiddlySpaceConfig" server.page.revision="1521905" server.etag="&quot;tiddlyspace/TiddlySpaceConfig/1521905:9ae989f324a88f5b30dfe02f45f22f019cc38ff2&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/tiddlyspace" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="tiddlyspace" server.permissions="read" server.content-type="text/javascript" modified="20131111192332" created="20131111192332" tags="excludeLists excludeSearch systemConfig" _hash="e74aa09eb3a15ff6e90b7de81e4d23168f8a51db">
<pre>/***
|''Name''|TiddlySpaceConfig|
|''Version''|0.7.7|
|''Description''|TiddlySpace configuration|
|''Status''|stable|
|''Source''|http://github.com/TiddlySpace/tiddlyspace/raw/master/src/plugins/TiddlySpaceConfig.js|
|''CoreVersion''|2.6.1|
|''Requires''|TiddlyWebConfig ServerSideSavingPlugin TiddlyFileImporter|
!Code
***/
//{{{
(function($) {

var tweb = config.extensions.tiddlyweb;

var recipe = config.defaultCustomFields["server.workspace"].split("recipes/")[1];
var currentSpace; // assigned later

var disabledTabs = [];

var coreBags = ["system", "tiddlyspace"];
var systemSpaces = ["plugins", "info", "images", "theme"];
systemSpaces = $.map(systemSpaces, function(item, i) {
	return "system-%0_public".format(item);
});

// hijack search macro to add custom attributes for mobile devices
var _search = config.macros.search.handler;
config.macros.search.handler = function(place, macroName, params) {
	_search.apply(this, arguments);
	$(".searchField:input", place).
		attr({ autocapitalize: "off", autocorrect: "off" });
};

// arg is either a container name or a tiddler object
// if fuzzy is truthy, space may be inferred from workspace (for new tiddlers)
// returns space object or false
var determineSpace = function(arg, fuzzy) {
	if(typeof arg == "string") { // container name
		var space = split(arg, "_", "r");
		return ["public", "private"].contains(space.type) ? space : false;
	} else if(arg) { // tiddler
		var container = determineContainer(arg, fuzzy);
		return container ? determineSpace(container.name, fuzzy) : false;
	} else {
		return false;
	}
};

// if fuzzy is truthy, container may be inferred from workspace for new tiddlers
// returns container object or false
var determineContainer = function(tiddler, fuzzy) { // TODO: expose?
	var bag = tiddler.fields["server.bag"];
	var recipe = tiddler.fields["server.recipe"]; // XXX: unused/irrelevant/redundant!?
	if(bag) {
		return { type: "bag", name: bag };
	} else if(recipe) {
		return { type: "recipe", name: recipe };
	} else if(fuzzy) { // new tiddler
		var workspace = tiddler.fields["server.workspace"];
		if(workspace) {
			var container = split(workspace, "/", "l");
			return ["bags", "recipes"].contains(container.type) ? container : false;
		} else {
			return false;
		}
	} else {
		return false;
	}
};

// hijack removeTiddlerCallback to restore tiddler from recipe cascade -- TODO: move into TiddlyWebWiki?
var sssp = config.extensions.ServerSideSavingPlugin;
var _removeTiddlerCallback = sssp.removeTiddlerCallback;
sssp.removeTiddlerCallback = function(context, userParams) {
	var title = context.tiddler.title;
	var recipe = context.tiddler.fields["server.recipe"];
	_removeTiddlerCallback.apply(this, arguments);
	if(recipe) {
		context.workspace = "recipes/" + recipe;
		var callback = function(context, userParams) {
			if(context.status) {
				var dirty = store.isDirty();
				store.saveTiddler(context.tiddler).clearChangeCount();
				store.setDirty(dirty);
			} else {
				store.notify(title, true);
			}
		};
		context.adaptor.getTiddler(title, context, null, callback);
	}
};

// splits a string once using delimiter
// mode "l" splits at the first, "r" at the last occurrence
// returns an object with members type and name
var split = function(str, sep, mode) {
	mode = mode == "r" ? "pop" : "shift"; // TODO: use +/-1 instead of "l"/"r"?
	var arr = str.split(sep);
	var type = arr.length &gt; 1 ? arr[mode]() : null;
	return { type: type, name: arr.join(sep) };
};

var plugin = config.extensions.tiddlyspace = {
	currentSpace: determineSpace(recipe),
	coreBags: coreBags.concat(systemSpaces),

	determineSpace: determineSpace,
	isValidSpaceName: function(name) {
		return name.match(/^[a-z][0-9a-z\-]*[0-9a-z]$/) ? true : false;
	},
	getCurrentBag: function(type) {
		return "%0_%1".format(currentSpace, type);
	},
	getCurrentWorkspace: function(type) {
		return "bags/" + this.getCurrentBag(type);
	},
	// returns the URL for a space's avatar (SiteIcon) based on a server_host
	// object and an optional space name
	// optional nocors argument prevents cross-domain URLs from being generated
	getAvatar: function(host, space, nocors) {
		if(space &amp;&amp; typeof space != "string") { // backwards compatibility -- XXX: deprecated
			space = space.name;
		}
		var subdomain = nocors ? currentSpace : space;
		host = host ? this.getHost(host, subdomain) : "";
		var bag = space ? "%0_public".format(space) : "tiddlyspace";
		return "%0/bags/%1/tiddlers/SiteIcon".format(host, bag);
	},
	// returns the URL based on a server_host object (scheme, host, port) and an
	// optional subdomain
	getHost: function(host, subdomain) {
		if(host === undefined) { // offline
			tweb.status.server_host = {}; // prevents exceptions further down the stack -- XXX: hacky workaround, breaks encapsulation
			return null;
		}
		subdomain = subdomain ? subdomain + "." : "";
		var url = "%0://%1%2".format(host.scheme, subdomain, host.host);
		var port = host.port;
		if(port &amp;&amp; !["80", "443"].contains(port)) {
			url += ":" + port;
		}
		return url;
	},
	disableTab: function(tabTiddler) {
		if(typeof(tabTiddler) == "string") {
			disabledTabs.push(tabTiddler);
		} else {
			for(var i = 0; i &lt; tabTiddler.length; i++) {
				plugin.disableTab(tabTiddler[i]);
			}
		}
	},
    checkSyncStatus: function(tiddler) {
		if(tiddler) {
			var title = typeof(tiddler) === "string" ? tiddler : tiddler.title;
			var el = story.getTiddler(title) || false;
			if(el) {
				refreshElements(el);
			}
		}
	},
	isDisabledTab: function(tabTitle) {
		var match = new RegExp("(?:\\[\\[([^\\]]+)\\]\\])", "mg").exec(tabTitle);
		var tabIdentifier = match ? match[1] : tabTitle;
		return disabledTabs.contains(tabIdentifier);
	},
	getCSRFToken: window.getCSRFToken || null // this may not have been processed yet
};

currentSpace = plugin.currentSpace.name;

tweb.serverPrefix = tweb.host.split("/")[3] || ""; // XXX: assumes root handler
tweb.getStatus(function(status) {
	var url = plugin.getHost(status.server_host);
	tweb.status.server_host.url = url;
	config.messages.tsVersion = status.version;
});

if(window.location.protocol == "file:") {
	// enable AutoSave by default
	config.options.chkAutoSave = config.options.chkAutoSave === undefined ?
		true : config.options.chkAutoSave;
} else {
	// set global read-only mode based on membership heuristics
	var indicator = store.getTiddler("SiteTitle") || tiddler;
	readOnly = !(recipe.split("_").pop() == "private" ||
		tweb.hasPermission("write", indicator));
	// replace TiddlyWiki's ImportTiddlers due to cross-domain restrictions
	if(config.macros.fileImport) {
		$.extend(config.macros.importTiddlers, config.macros.fileImport);
	}
}

// hijack saveChanges to ensure SystemSettings is private by default
var _saveChanges = saveChanges;
saveChanges = function(onlyIfDirty, tiddlers) {
	if(tiddlers &amp;&amp; tiddlers.length == 1 &amp;&amp;
			tiddlers[0] &amp;&amp; tiddlers[0].title == "SystemSettings") {
		var fields = tiddlers[0].fields;
		delete fields["server.recipe"];
		fields["server.bag"] = plugin.getCurrentBag("private");
		fields["server.workspace"] = plugin.getCurrentWorkspace("private");
	}
	return _saveChanges.apply(this, arguments);
};

// ensure backstage is always initialized
// required to circumvent TiddlyWiki's read-only based handling
config.macros.backstageInit = {
	init: function() {
		showBackstage = true;
	}
};

// disable evaluated macro parameters for security reasons
config.evaluateMacroParameters = "none";
var _parseParams = String.prototype.parseParams;
String.prototype.parseParams = function(defaultName, defaultValue, allowEval,
		noNames, cascadeDefaults) {
	if(config.evaluateMacroParameters == "none") {
		arguments[2] = false;
	}
	return _parseParams.apply(this, arguments);
};

var _tabsMacro = config.macros.tabs.handler;
config.macros.tabs.handler = function(place, macroName, params) {
	var newParams = [params[0]]; // keep cookie name
	for(var i = 1; i &lt; params.length; i += 3) {
		var tabTitle = params[i + 2];
		if(!plugin.isDisabledTab(tabTitle)){
			newParams = newParams.concat(params[i], params[i + 1], tabTitle);
		}
	}
	_tabsMacro.apply(this, [place, macroName, newParams]);
};

// disable ControlView for XHRs by default
$.ajaxSetup({
	beforeSend: function(xhr) {
		xhr.setRequestHeader("X-ControlView", "false");
	}
});
// TiddlyWeb adaptor currently still uses httpReq, which needs extra magic -- XXX: obsolete this!
var _httpReq = httpReq;
httpReq = function(type, url, callback, params, headers, data, contentType,
		username, password, allowCache) {
	headers = headers || {};
	headers["X-ControlView"] = "false";
	_httpReq.apply(this, arguments);
};

// register style sheet for backstage separately (important)
store.addNotification("StyleSheetBackstage", refreshStyles);

// option for default privacy setting
config.optionsDesc.chkPrivateMode = "Set your default privacy mode to private";
config.optionsSource.chkPrivateMode = "setting";
config.options.chkPrivateMode = config.options.chkPrivateMode || false;
saveSystemSetting("chkPrivateMode", true);
config.defaultCustomFields["server.workspace"] = plugin.
	getCurrentWorkspace(config.options.chkPrivateMode ? "private" : "public");

config.paramifiers.follow = {
	onstart: function(v) {
		if(!readOnly) {
			var bag = "%0_public".format(currentSpace);
			story.displayTiddler(null, v, DEFAULT_EDIT_TEMPLATE, null, null,
				"server.bag:%0 server.workspace:bags/%0".format(bag));
			story.setTiddlerTag(v, "follow", 1);
			story.focusTiddler(v, "text");
		}
	}
};

var fImport = config.macros.fileImport;
if(fImport) {
	fImport.uploadTo = "Upload to: ";
	var _createForm = config.macros.fileImport.createForm;
	config.macros.fileImport.createForm = function(place, wizard, iframeName) {
		var container = $("&lt;div /&gt;").text(fImport.uploadTo).appendTo(place);
		var select = $('&lt;select name="mode" /&gt;').appendTo(container)[0];
		$('&lt;option value="private" selected&gt;private&lt;/a&gt;').appendTo(select);
		$('&lt;option value="public"&gt;public&lt;/a&gt;').appendTo(select);
		wizard.setValue("importmode", select);
		_createForm.apply(this, [place, wizard, iframeName]);
	};

	var _onGet = config.macros.importTiddlers.onGetTiddler;
	config.macros.importTiddlers.onGetTiddler = function(context, wizard) {
		var type = $(wizard.getValue("importmode")).val();
		var ws =  plugin.getCurrentWorkspace(type);
		wizard.setValue("workspace", ws);
		_onGet.apply(this, [context, wizard]);
	};
}

config.extensions.ServerSideSavingPlugin.reportSuccess = function(msg, tiddler) {
	plugin.checkSyncStatus(tiddler);
	msg = config.extensions.ServerSideSavingPlugin.locale[msg];
	var link = "/" + encodeURIComponent(tiddler.title);
	displayMessage(msg.format([tiddler.title]), link);
};


})(jQuery);
//}}}</pre>
</div>
<div title="TiddlyWebAdaptor" server.title="TiddlyWebAdaptor" server.page.revision="1521858" server.etag="&quot;system/TiddlyWebAdaptor/1521858:bd4bfb12c93b532fdf446f657dbe4a9e83aac3d6&quot;" modifier="FND" creator="FND" server.workspace="bags/system" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system" server.permissions="read" server.content-type="text/javascript" modified="200811260000" created="200811260000" tags="excludeLists excludeSearch systemConfig" _hash="487ec1465c11e0798c029b3ed15a2f71ae51ce92">
<pre>/***
|''Name''|TiddlyWebAdaptor|
|''Description''|adaptor for interacting with TiddlyWeb|
|''Author:''|FND|
|''Contributors''|Chris Dent, Martin Budden|
|''Version''|1.4.10|
|''Status''|stable|
|''Source''|http://svn.tiddlywiki.org/Trunk/association/adaptors/TiddlyWebAdaptor.js|
|''CodeRepository''|http://svn.tiddlywiki.org/Trunk/association/|
|''License''|[[BSD|http://www.opensource.org/licenses/bsd-license.php]]|
|''CoreVersion''|2.5|
|''Keywords''|serverSide TiddlyWeb|
!Notes
This plugin includes [[jQuery JSON|http://code.google.com/p/jquery-json/]].
!To Do
* createWorkspace
* document custom/optional context attributes (e.g. filters, query, revision) and tiddler fields (e.g. server.title, origin)
!Code
***/
//{{{
(function($) {

var adaptor = config.adaptors.tiddlyweb = function() {};

adaptor.prototype = new AdaptorBase();
adaptor.serverType = "tiddlyweb";
adaptor.serverLabel = "TiddlyWeb";
adaptor.mimeType = "application/json";

adaptor.parsingErrorMessage = "Error parsing result from server";
adaptor.noBagErrorMessage = "no bag specified for tiddler";
adaptor.locationIDErrorMessage = "no bag or recipe specified for tiddler"; // TODO: rename

// retrieve current status (requires TiddlyWeb status plugin)
adaptor.prototype.getStatus = function(context, userParams, callback) {
	context = this.setContext(context, userParams, callback);
	var uriTemplate = "%0/status";
	var uri = uriTemplate.format([context.host]);
	var req = httpReq("GET", uri, adaptor.getStatusCallback, context,
		null, null, null, null, null, true);
	return typeof req == "string" ? req : true;
};

adaptor.getStatusCallback = function(status, context, responseText, uri, xhr) {
	context.status = responseText ? status : false;
	try {
		context.statusText = xhr.statusText;
	} catch(exc) { // offline (Firefox)
		context.status = false;
		context.statusText = null;
	}
	context.httpStatus = xhr.status;
	if(context.status) {
		context.serverStatus = $.evalJSON(responseText); // XXX: error handling!?
	}
	if(context.callback) {
		context.callback(context, context.userParams);
	}
};

// retrieve a list of workspaces
adaptor.prototype.getWorkspaceList = function(context, userParams, callback) {
	context = this.setContext(context, userParams, callback);
	context.workspaces = [];
	var uriTemplate = "%0/recipes"; // XXX: bags?
	var uri = uriTemplate.format([context.host]);
	var req = httpReq("GET", uri, adaptor.getWorkspaceListCallback,
		context, { accept: adaptor.mimeType }, null, null, null, null, true);
	return typeof req == "string" ? req : true;
};

adaptor.getWorkspaceListCallback = function(status, context, responseText, uri, xhr) {
	context.status = status;
	context.statusText = xhr.statusText;
	context.httpStatus = xhr.status;
	if(status) {
		try {
			var workspaces = $.evalJSON(responseText);
		} catch(ex) {
			context.status = false; // XXX: correct?
			context.statusText = exceptionText(ex, adaptor.parsingErrorMessage);
			if(context.callback) {
				context.callback(context, context.userParams);
			}
			return;
		}
		context.workspaces = workspaces.map(function(itm) { return { title: itm }; });
	}
	if(context.callback) {
		context.callback(context, context.userParams);
	}
};

// retrieve a list of tiddlers
adaptor.prototype.getTiddlerList = function(context, userParams, callback) {
	context = this.setContext(context, userParams, callback);
	var uriTemplate = "%0/%1/%2/tiddlers%3";
	var params = context.filters ? "?" + context.filters : "";
	if(context.format) {
		params = context.format + params;
	}
	var workspace = adaptor.resolveWorkspace(context.workspace);
	var uri = uriTemplate.format([context.host, workspace.type + "s",
		adaptor.normalizeTitle(workspace.name), params]);
	var req = httpReq("GET", uri, adaptor.getTiddlerListCallback,
		context, merge({ accept: adaptor.mimeType }, context.headers), null, null, null, null, true);
	return typeof req == "string" ? req : true;
};

adaptor.getTiddlerListCallback = function(status, context, responseText, uri, xhr) {
	context.status = status;
	context.statusText = xhr.statusText;
	context.httpStatus = xhr.status;
	if(status) {
		context.tiddlers = [];
		try {
			var tiddlers = $.evalJSON(responseText); //# NB: not actual tiddler instances
		} catch(ex) {
			context.status = false; // XXX: correct?
			context.statusText = exceptionText(ex, adaptor.parsingErrorMessage);
			if(context.callback) {
				context.callback(context, context.userParams);
			}
			return;
		}
		for(var i = 0; i &lt; tiddlers.length; i++) {
			var tiddler = adaptor.toTiddler(tiddlers[i], context.host);
			context.tiddlers.push(tiddler);
		}
	}
	if(context.callback) {
		context.callback(context, context.userParams);
	}
};

// perform global search
adaptor.prototype.getSearchResults = function(context, userParams, callback) {
	context = this.setContext(context, userParams, callback);
	var uriTemplate = "%0/search?q=%1%2";
	var filterString = context.filters ? ";" + context.filters : "";
	var uri = uriTemplate.format([context.host, context.query, filterString]); // XXX: parameters need escaping?
	var req = httpReq("GET", uri, adaptor.getSearchResultsCallback,
		context, { accept: adaptor.mimeType }, null, null, null, null, true);
	return typeof req == "string" ? req : true;
};

adaptor.getSearchResultsCallback = function(status, context, responseText, uri, xhr) {
	adaptor.getTiddlerListCallback(status, context, responseText, uri, xhr); // XXX: use apply?
};

// retrieve a particular tiddler's revisions
adaptor.prototype.getTiddlerRevisionList = function(title, limit, context, userParams, callback) {
	context = this.setContext(context, userParams, callback);
	var uriTemplate = "%0/%1/%2/tiddlers/%3/revisions";
	var workspace = adaptor.resolveWorkspace(context.workspace);
	var uri = uriTemplate.format([context.host, workspace.type + "s",
		adaptor.normalizeTitle(workspace.name), adaptor.normalizeTitle(title)]);
	var req = httpReq("GET", uri, adaptor.getTiddlerRevisionListCallback,
		context, merge({ accept: adaptor.mimeType }, context.headers), null, null, null, null, true);
	return typeof req == "string" ? req : true;
};

adaptor.getTiddlerRevisionListCallback = function(status, context, responseText, uri, xhr) {
	context.status = status;
	context.statusText = xhr.statusText;
	context.httpStatus = xhr.status;
	if(status) {
		context.revisions = [];
		try {
			var tiddlers = $.evalJSON(responseText); //# NB: not actual tiddler instances
		} catch(ex) {
			context.status = false; // XXX: correct?
			context.statusText = exceptionText(ex, adaptor.parsingErrorMessage);
			if(context.callback) {
				context.callback(context, context.userParams);
			}
			return;
		}
		for(var i = 0; i &lt; tiddlers.length; i++) {
			var tiddler = adaptor.toTiddler(tiddlers[i], context.host);
			context.revisions.push(tiddler);
		}
		var sortField = "server.page.revision";
		context.revisions.sort(function(a, b) {
			return a.fields[sortField] &lt; b.fields[sortField] ? 1 :
				(a.fields[sortField] == b.fields[sortField] ? 0 : -1);
		});
	}
	if(context.callback) {
		context.callback(context, context.userParams);
	}
};

// retrieve an individual tiddler revision -- XXX: breaks with standard arguments list -- XXX: convenience function; simply use getTiddler?
adaptor.prototype.getTiddlerRevision = function(title, revision, context, userParams, callback) {
	context = this.setContext(context, userParams, callback);
	context.revision = revision;
	return this.getTiddler(title, context, userParams, callback);
};

// retrieve an individual tiddler
//# context is an object with members host and workspace
//# callback is passed the new context and userParams
adaptor.prototype.getTiddler = function(title, context, userParams, callback) {
	context = this.setContext(context, userParams, callback);
	context.title = title;
	if(context.revision) {
		var uriTemplate = "%0/%1/%2/tiddlers/%3/revisions/%4";
	} else {
		uriTemplate = "%0/%1/%2/tiddlers/%3";
	}
	if(!context.tiddler) {
		context.tiddler = new Tiddler(title);
	}
	context.tiddler.fields["server.type"] = adaptor.serverType;
	context.tiddler.fields["server.host"] = AdaptorBase.minHostName(context.host);
	context.tiddler.fields["server.workspace"] = context.workspace;
	var workspace = adaptor.resolveWorkspace(context.workspace);
	var uri = uriTemplate.format([context.host, workspace.type + "s",
		adaptor.normalizeTitle(workspace.name), adaptor.normalizeTitle(title),
		context.revision]);
	var req = httpReq("GET", uri, adaptor.getTiddlerCallback, context,
		merge({ accept: adaptor.mimeType }, context.headers), null, null, null, null, true);
	return typeof req == "string" ? req : true;
};

adaptor.getTiddlerCallback = function(status, context, responseText, uri, xhr) {
	context.status = status;
	context.statusText = xhr.statusText;
	context.httpStatus = xhr.status;
	if(status) {
		try {
			var tid = $.evalJSON(responseText);
		} catch(ex) {
			context.status = false;
			context.statusText = exceptionText(ex, adaptor.parsingErrorMessage);
			if(context.callback) {
				context.callback(context, context.userParams);
			}
			return;
		}
		var tiddler = adaptor.toTiddler(tid, context.host);
		tiddler.title = context.tiddler.title;
		tiddler.fields["server.etag"] = xhr.getResponseHeader("Etag");
		// normally we'd assign context.tiddler = tiddler here - but we can't do
		// that because of IE, which triggers getTiddler in putTiddlerCallback,
		// and since ServerSideSavingPlugin foolishly relies on persistent
		// object references, we need to merge the data into the existing object
		$.extend(context.tiddler, tiddler);
	}
	if(context.callback) {
		context.callback(context, context.userParams);
	}
};

// retrieve tiddler chronicle (all revisions)
adaptor.prototype.getTiddlerChronicle = function(title, context, userParams, callback) {
	context = this.setContext(context, userParams, callback);
	context.title = title;
	var uriTemplate = "%0/%1/%2/tiddlers/%3/revisions?fat=1";
	var workspace = adaptor.resolveWorkspace(context.workspace);
	var uri = uriTemplate.format([context.host, workspace.type + "s",
		adaptor.normalizeTitle(workspace.name), adaptor.normalizeTitle(title)]);
	var req = httpReq("GET", uri, adaptor.getTiddlerChronicleCallback,
		context, { accept: adaptor.mimeType }, null, null, null, null, true);
	return typeof req == "string" ? req : true;
};

adaptor.getTiddlerChronicleCallback = function(status, context, responseText, uri, xhr) {
	context.status = status;
	context.statusText = xhr.statusText;
	context.httpStatus = xhr.status;
	if(status) {
		context.responseText = responseText;
	}
	if(context.callback) {
		context.callback(context, context.userParams);
	}
};

// store an individual tiddler
adaptor.prototype.putTiddler = function(tiddler, context, userParams, callback) {
	context = this.setContext(context, userParams, callback);
	context.title = tiddler.title;
	context.tiddler = tiddler;
	context.host = context.host || this.fullHostName(tiddler.fields["server.host"]);
	var uriTemplate = "%0/%1/%2/tiddlers/%3";
	try {
		context.workspace = context.workspace || tiddler.fields["server.workspace"];
		var workspace = adaptor.resolveWorkspace(context.workspace);
	} catch(ex) {
		return adaptor.locationIDErrorMessage;
	}
	var uri = uriTemplate.format([context.host, workspace.type + "s",
		adaptor.normalizeTitle(workspace.name),
		adaptor.normalizeTitle(tiddler.title)]);
	var etag = adaptor.generateETag(workspace, tiddler);
	var headers = etag ? { "If-Match": etag } : null;
	var payload = {
		type: tiddler.fields["server.content-type"] || null,
		text: tiddler.text,
		tags: tiddler.tags,
		fields: $.extend({}, tiddler.fields)
	};
	delete payload.fields.changecount;
	$.each(payload.fields, function(key, value) {
		if(key.indexOf("server.") == 0) {
			delete payload.fields[key];
		}
	});
	payload = $.toJSON(payload);
	var req = httpReq("PUT", uri, adaptor.putTiddlerCallback,
		context, headers, payload, adaptor.mimeType, null, null, true);
	return typeof req == "string" ? req : true;
};

adaptor.putTiddlerCallback = function(status, context, responseText, uri, xhr) {
	context.status = [204, 1223].contains(xhr.status);
	context.statusText = xhr.statusText;
	context.httpStatus = xhr.status;
	if(context.status) {
		var loc = xhr.getResponseHeader("Location");
		var etag = xhr.getResponseHeader("Etag");
		if(loc &amp;&amp; etag) {
			var bag = loc.split("/bags/").pop().split("/")[0];
			context.tiddler.fields["server.bag"] = bag;
			context.tiddler.fields["server.workspace"] = "bags/" + bag;
			var rev = etag.split("/").pop().split(/;|:/)[0];
			context.tiddler.fields["server.page.revision"] = rev;
			context.tiddler.fields["server.etag"] = etag;
			if(context.callback) {
				context.callback(context, context.userParams);
			}
		} else { // IE
			context.adaptor.getTiddler(context.tiddler.title, context,
				context.userParams, context.callback);
		}
	} else if(context.callback) {
		context.callback(context, context.userParams);
	}
};

// store a tiddler chronicle
adaptor.prototype.putTiddlerChronicle = function(revisions, context, userParams, callback) {
	context = this.setContext(context, userParams, callback);
	context.title = revisions[0].title;
	var headers = null;
	var uriTemplate = "%0/%1/%2/tiddlers/%3/revisions";
	var host = context.host || this.fullHostName(tiddler.fields["server.host"]);
	var workspace = adaptor.resolveWorkspace(context.workspace);
	var uri = uriTemplate.format([host, workspace.type + "s",
		adaptor.normalizeTitle(workspace.name),
		adaptor.normalizeTitle(context.title)]);
	if(workspace.type == "bag") { // generate ETag
		var etag = [adaptor.normalizeTitle(workspace.name),
			adaptor.normalizeTitle(context.title), 0].join("/"); //# zero-revision prevents overwriting existing contents
		headers = { "If-Match": '"' + etag + '"' };
	}
	var payload = $.toJSON(revisions);
	var req = httpReq("POST", uri, adaptor.putTiddlerChronicleCallback,
		context, headers, payload, adaptor.mimeType, null, null, true);
	return typeof req == "string" ? req : true;
};

adaptor.putTiddlerChronicleCallback = function(status, context, responseText, uri, xhr) {
	context.status = [204, 1223].contains(xhr.status);
	context.statusText = xhr.statusText;
	context.httpStatus = xhr.status;
	if(context.callback) {
		context.callback(context, context.userParams);
	}
};

// store a collection of tiddlers (import TiddlyWiki HTML store)
adaptor.prototype.putTiddlerStore = function(store, context, userParams, callback) {
	context = this.setContext(context, userParams, callback);
	var uriTemplate = "%0/%1/%2/tiddlers";
	var host = context.host;
	var workspace = adaptor.resolveWorkspace(context.workspace);
	var uri = uriTemplate.format([host, workspace.type + "s",
		adaptor.normalizeTitle(workspace.name)]);
	var req = httpReq("POST", uri, adaptor.putTiddlerStoreCallback,
		context, null, store, "text/x-tiddlywiki", null, null, true);
	return typeof req == "string" ? req : true;
};

adaptor.putTiddlerStoreCallback = function(status, context, responseText, uri, xhr) {
	context.status = [204, 1223].contains(xhr.status);
	context.statusText = xhr.statusText;
	context.httpStatus = xhr.status;
	if(context.callback) {
		context.callback(context, context.userParams);
	}
};

// rename an individual tiddler or move it to a different workspace -- TODO: make {from|to}.title optional
//# from and to are objects with members title and workspace (bag; optional),
//# representing source and target tiddler, respectively
adaptor.prototype.moveTiddler = function(from, to, context, userParams, callback) { // XXX: rename parameters (old/new)?
	var self = this;
	var newTiddler = store.getTiddler(from.title) || store.getTiddler(to.title); //# local rename might already have occurred
	var oldTiddler = $.extend(true, {}, newTiddler); //# required for eventual deletion
	oldTiddler.title = from.title; //# required for original tiddler's ETag
	var _getTiddlerChronicle = function(title, context, userParams, callback) {
		return self.getTiddlerChronicle(title, context, userParams, callback);
	};
	var _putTiddlerChronicle = function(context, userParams) {
		if(!context.status) {
			return callback(context, userParams);
		}
		var revisions = $.evalJSON(context.responseText); // XXX: error handling?
		// change current title while retaining previous location
		for(var i = 0; i &lt; revisions.length; i++) {
			delete revisions[i].revision;
			if(!revisions[i].fields.origin) { // NB: origin = "&lt;workspace&gt;/&lt;title&gt;"
				revisions[i].fields.origin = ["bags", revisions[i].bag, revisions[i].title].join("/");
			}
			revisions[i].title = to.title;
		}
		// add new revision
		var rev = $.extend({}, revisions[0]);
		$.each(newTiddler, function(i, item) {
			if(!$.isFunction(item)) {
				rev[i] = item;
			}
		});
		rev.title = to.title;
		rev.created = rev.created.convertToYYYYMMDDHHMM();
		rev.modified = new Date().convertToYYYYMMDDHHMM();
		delete rev.fields.changecount;
		revisions.unshift(rev);
		if(to.workspace) {
			context.workspace = to.workspace;
		} else if(context.workspace.substring(0, 4) != "bags") { // NB: target workspace must be a bag
			context.workspace = "bags/" + rev.bag;
		}
		var subCallback = function(context, userParams) {
			if(!context.status) {
				return callback(context, userParams);
			}
			context.adaptor.getTiddler(newTiddler.title, context, userParams, _deleteTiddler);
		};
		return self.putTiddlerChronicle(revisions, context, context.userParams, subCallback);
	};
	var _deleteTiddler = function(context, userParams) {
		if(!context.status) {
			return callback(context, userParams);
		}
		$.extend(true, newTiddler, context.tiddler);
		context.callback = null;
		return self.deleteTiddler(oldTiddler, context, context.userParams, callback);
	};
	callback = callback || function() {};
	context = this.setContext(context, userParams);
	context.host = context.host || oldTiddler.fields["server.host"];
	context.workspace = from.workspace || oldTiddler.fields["server.workspace"];
	return _getTiddlerChronicle(from.title, context, userParams, _putTiddlerChronicle);
};

// delete an individual tiddler
adaptor.prototype.deleteTiddler = function(tiddler, context, userParams, callback) {
	context = this.setContext(context, userParams, callback);
	context.title = tiddler.title; // XXX: not required!?
	var uriTemplate = "%0/bags/%1/tiddlers/%2";
	var host = context.host || this.fullHostName(tiddler.fields["server.host"]);
	var bag = tiddler.fields["server.bag"];
	if(!bag) {
		return adaptor.noBagErrorMessage;
	}
	var uri = uriTemplate.format([host, adaptor.normalizeTitle(bag),
		adaptor.normalizeTitle(tiddler.title)]);
	var etag = adaptor.generateETag({ type: "bag", name: bag }, tiddler);
	var headers = etag ? { "If-Match": etag } : null;
	var req = httpReq("DELETE", uri, adaptor.deleteTiddlerCallback, context, headers,
		null, null, null, null, true);
	return typeof req == "string" ? req : true;
};

adaptor.deleteTiddlerCallback = function(status, context, responseText, uri, xhr) {
	context.status = [204, 1223].contains(xhr.status);
	context.statusText = xhr.statusText;
	context.httpStatus = xhr.status;
	if(context.callback) {
		context.callback(context, context.userParams);
	}
};

// compare two revisions of a tiddler (requires TiddlyWeb differ plugin)
//# if context.rev1 is not specified, the latest revision will be used for comparison
//# if context.rev2 is not specified, the local revision will be sent for comparison
//# context.format is a string as determined by the TiddlyWeb differ plugin
adaptor.prototype.getTiddlerDiff = function(title, context, userParams, callback) {
	context = this.setContext(context, userParams, callback);
	context.title = title;

	var tiddler = store.getTiddler(title);
	try {
		var workspace = adaptor.resolveWorkspace(tiddler.fields["server.workspace"]);
	} catch(ex) {
		return adaptor.locationIDErrorMessage;
	}
	var tiddlerRef = [workspace.type + "s", workspace.name, tiddler.title].join("/");

	var rev1 = context.rev1 ? [tiddlerRef, context.rev1].join("/") : tiddlerRef;
	var rev2 = context.rev2 ? [tiddlerRef, context.rev2].join("/") : null;

	var uriTemplate = "%0/diff?rev1=%1";
	if(rev2) {
		uriTemplate += "&amp;rev2=%2";
	}
	if(context.format) {
		uriTemplate += "&amp;format=%3";
	}
	var host = context.host || this.fullHostName(tiddler.fields["server.host"]);
	var uri = uriTemplate.format([host, adaptor.normalizeTitle(rev1),
		adaptor.normalizeTitle(rev2), context.format]);

	if(rev2) {
		var req = httpReq("GET", uri, adaptor.getTiddlerDiffCallback, context, null,
			null, null, null, null, true);
	} else {
		var payload = {
			title: tiddler.title,
			text: tiddler.text,
			modifier: tiddler.modifier,
			tags: tiddler.tags,
			fields: $.extend({}, tiddler.fields)
		}; // XXX: missing attributes!?
		payload = $.toJSON(payload);
		req = httpReq("POST", uri, adaptor.getTiddlerDiffCallback, context,
			null, payload, adaptor.mimeType, null, null, true);
	}
	return typeof req == "string" ? req : true;
};

adaptor.getTiddlerDiffCallback = function(status, context, responseText, uri, xhr) {
	context.status = status;
	context.statusText = xhr.statusText;
	context.httpStatus = xhr.status;
	context.uri = uri;
	if(status) {
		context.diff = responseText;
	}
	if(context.callback) {
		context.callback(context, context.userParams);
	}
};

// generate tiddler information
adaptor.prototype.generateTiddlerInfo = function(tiddler) {
	var info = {};
	var uriTemplate = "%0/%1/%2/tiddlers/%3";
	var host = this.host || tiddler.fields["server.host"]; // XXX: this.host obsolete?
	host = this.fullHostName(host);
	var workspace = adaptor.resolveWorkspace(tiddler.fields["server.workspace"]);
	info.uri = uriTemplate.format([host, workspace.type + "s",
		adaptor.normalizeTitle(workspace.name),
		adaptor.normalizeTitle(tiddler.title)]);
	return info;
};

// create Tiddler instance from TiddlyWeb tiddler JSON
adaptor.toTiddler = function(json, host) {
	var created = Date.convertFromYYYYMMDDHHMM(json.created);
	var modified = Date.convertFromYYYYMMDDHHMM(json.modified);
	var fields = json.fields;
	fields["server.type"] = adaptor.serverType;
	fields["server.host"] = AdaptorBase.minHostName(host);
	fields["server.bag"] = json.bag;
	fields["server.title"] = json.title;
	if(json.recipe) {
		fields["server.recipe"] = json.recipe;
	}
	if(json.type &amp;&amp; json.type != "None") {
		fields["server.content-type"] = json.type;
	}
	fields["server.permissions"] = json.permissions.join(", ");
	fields["server.page.revision"] = json.revision;
	fields["server.workspace"] = "bags/" + json.bag;
	var tiddler = new Tiddler(json.title);
	tiddler.assign(tiddler.title, json.text, json.modifier, modified, json.tags,
		created, json.fields, json.creator);
	return tiddler;
};

adaptor.resolveWorkspace = function(workspace) {
	var components = workspace.split("/");
	return {
		type: components[0] == "bags" ? "bag" : "recipe",
		name: components[1] || components[0]
	};
};

adaptor.generateETag = function(workspace, tiddler) {
	var revision = tiddler.fields["server.page.revision"];
	var etag = revision == "false" ? null : tiddler.fields["server.etag"];
	if(!etag &amp;&amp; workspace.type == "bag") {
		if(typeof revision == "undefined") {
			revision = "0";
		} else if(revision == "false") {
			return null;
		}
		etag = [adaptor.normalizeTitle(workspace.name),
			adaptor.normalizeTitle(tiddler.title), revision].join("/");
		etag = '"' + etag + '"';
	}
	return etag;
};

adaptor.normalizeTitle = function(title) {
	return encodeURIComponent(title);
};

})(jQuery);


/*
 * jQuery JSON Plugin
 * version: 1.3
 * source: http://code.google.com/p/jquery-json/
 * license: MIT (http://www.opensource.org/licenses/mit-license.php)
 */
(function($){function toIntegersAtLease(n)
{return n&lt;10?'0'+n:n;}
Date.prototype.toJSON=function(date)
{return this.getUTCFullYear()+'-'+
toIntegersAtLease(this.getUTCMonth())+'-'+
toIntegersAtLease(this.getUTCDate());};var escapeable=/["\\\x00-\x1f\x7f-\x9f]/g;var meta={'\b':'\\b','\t':'\\t','\n':'\\n','\f':'\\f','\r':'\\r','"':'\\"','\\':'\\\\'};$.quoteString=function(string)
{if(escapeable.test(string))
{return'"'+string.replace(escapeable,function(a)
{var c=meta[a];if(typeof c==='string'){return c;}
c=a.charCodeAt();return'\\u00'+Math.floor(c/16).toString(16)+(c%16).toString(16);})+'"';}
return'"'+string+'"';};$.toJSON=function(o,compact)
{var type=typeof(o);if(type=="undefined")
return"undefined";else if(type=="number"||type=="boolean")
return o+"";else if(o===null)
return"null";if(type=="string")
{return $.quoteString(o);}
if(type=="object"&amp;&amp;typeof o.toJSON=="function")
return o.toJSON(compact);if(type!="function"&amp;&amp;typeof(o.length)=="number")
{var ret=[];for(var i=0;i&lt;o.length;i++){ret.push($.toJSON(o[i],compact));}
if(compact)
return"["+ret.join(",")+"]";else
return"["+ret.join(", ")+"]";}
if(type=="function"){throw new TypeError("Unable to convert object of type 'function' to json.");}
var ret=[];for(var k in o){var name;type=typeof(k);if(type=="number")
name='"'+k+'"';else if(type=="string")
name=$.quoteString(k);else
continue;var val=$.toJSON(o[k],compact);if(typeof(val)!="string"){continue;}
if(compact)
ret.push(name+":"+val);else
ret.push(name+": "+val);}
return"{"+ret.join(", ")+"}";};$.compactJSON=function(o)
{return $.toJSON(o,true);};$.evalJSON=function(src)
{return eval("("+src+")");};$.secureEvalJSON=function(src)
{var filtered=src;filtered=filtered.replace(/\\["\\\/bfnrtu]/g,'@');filtered=filtered.replace(/"[^"\\\n\r]*"|true|false|null|-?\d+(?:\.\d*)?(?:[eE][+\-]?\d+)?/g,']');filtered=filtered.replace(/(?:^|:|,)(?:\s*\[)+/g,'');if(/^[\],:{}\s]*$/.test(filtered))
return eval("("+src+")");else
throw new SyntaxError("Error parsing JSON, source is not valid.");};})(jQuery);
//}}}</pre>
</div>
<div title="SiteIcon" server.title="SiteIcon" server.page.revision="2563108" server.etag="&quot;honly-666_public/SiteIcon/2563108:9313fde00606e5c849162781a4e9df97dcc63742&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="image/jpeg" modified="20160922152113" created="20160906130631" tags="excludeLists" _hash="5762123d0160b4343f839231eb4fa35b2a501bef">
<pre>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</pre>
</div>
<div title="跨界喜剧王" server.title="跨界喜剧王" server.page.revision="2579933" server.etag="&quot;honly-666_public/%E8%B7%A8%E7%95%8C%E5%96%9C%E5%89%A7%E7%8E%8B/2579933:18699bab7b3b988ff5ea9f0aed37153c68e7de29&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20161102050232" created="20161102050232" tags="" _hash="fc3f66bc6fe96e7d61d66bffd4c6bdfb2b420e5e">
<pre>http://www.360kan.com/va/aMQpbnNw8ZEADT.html</pre>
</div>
<div title="StyleSheetTiddler" server.title="StyleSheetTiddler" server.page.revision="1521917" server.etag="&quot;system-theme_public/StyleSheetTiddler/1521917:229e060a7ff713be68f47de5f2b5624b6aefd07c&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-theme_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-theme_public" server.permissions="read" server.content-type="" modified="20131111192330" created="20131111192330" tags="excludeLists excludeSearch" _hash="1a28a9b1acf2996cdfbb522f52f0e56353d9f883">
<pre>/*{{{*/
.tiddler .originButton div {
	display: inline-block;
}

.tiddler .spaceSiteIcon .siteIcon {
	_display: inline; /* IE doesn't like inline-block */
}

.tiddler .originButton {
	display: block;
}

.selected .tagging,
.selected .tagging:hover {
	border: none;
	background: none;
}

.tagging {
	float: none;
	background: none;
	border: none;
}

.tagging li.listTitle {
	margin-left: 0px;
}
.tagging li {
	margin: 0 8px;
}

.tagging .tiddlyLink {
	-webkit-border-radius: 3px;
	-moz-border-radius: 3px;
	-o-border-radius: 3px;
	border-radius: 3px;
	padding: 1px 2px;
	line-height: 1.2em;
}

/* for following */
#popup .siteIcon {
	float: left;
	height: 25px;
}

.content {
	width: 100%; /* IE */
	font-size: 0.9em;
}

.editorHeading {
	height: 48px;
}

.heading {
	left: 0;
	margin-bottom: 40px;
	position: relative;
	top: 32px;
}

.followButton a {
	display: block;
	margin-top: -20px;
}

.tiddler .followPlaceHolder {
	display: block;
	position: absolute;
	top: 16px;
	right: 64px;
	_right: 138px; // add width of modifierIcon
}

.tiddler .followButton {
	position: relative;
	height: 24px;
	text-align: left;
	color: #fff;
	background: [[ColorPalette::PrimaryMid]];
	padding: 10px 0px 0px 10px;
	width: 38px;
	margin: -16px -8px 24px 0;
}

/* creates the larger triangle */
.followButton:before {
	content: "\00a0";
	display: block; /* reduce the damage in FF3.0 */
	position: relative;
	bottom: -20px;
	right: 0;
	width: 0;
	height: 0;
	border-width: 0 0 20px 20px;
	border-style: solid;
	border-color: transparent [[ColorPalette::PrimaryMid]];
}

.toolbar svg {
	height: 16px;
	width: 16px;
}

.toolbar svg .glyph {
	fill: #ccc;
}

.toolbar a:hover .glyph {
	fill: black;
}

.toolbar a:active .glyph {
	fill: [[ColorPalette::Background]];
}

.originButton,
.followPlaceHolder,
.tiddler .subtitle {
	cursor: pointer;
}

.editSpaceSiteIcon .originButton {
	cursor: auto;
}

.tiddler .subtitle:hover {
	font-weight: bold;
	background: none;
}

.originButton img,
.originButton svg {
	margin-left: 0px;
}

.modifierIcon {
	position: absolute;
	width: 74px;
	top: 0px;
	right: 0px;
	_right: 74px; /* in IE6 positioning works incorrectly so use -width instead */
	text-align: right;
}

.modifierIcon img,
.modifierIcon svg {
	margin-right: 8px;
}

.tiddler .viewer {
	padding-bottom: 16px;
	margin: 0 0 0 56px;
	line-height: 1.4em;
}

.viewer pre {
	margin-left: 0;
}

.siteIcon .label {
	color: [[ColorPalette::TertiaryDark]];
}

.tiddler .spaceSiteIcon {
	float: left;
	margin-right: 0;
	margin-top: 0;
	position: relative;
	display: block;
}

.tiddler .titleBar {
	display: block;
	margin-right: 136px;
	margin-left: 56px;
}

.followButton a {
	color: [[ColorPalette::Background]];
}

.tiddler {
	position: relative;
	padding: 0;
	margin-bottom: 3em;
	border-top: 3px solid [[ColorPalette::PrimaryMid]];
	background: #fff;
}

.tiddler .editor {
	padding: 0px 8px;
}

.tiddler .heading .title {
	position: relative;
	display: block;
	word-wrap: break-word;
	font-size: 32px;
	line-height: 32px;
}
.tiddler .heading .editor.title {
	font-size: 1.7em;
	line-height: normal;
}

.tiddler .headingClear {
	clear: both;
}

.tiddler .subtitle {
	font-style: italic;
	font-size: 0.9em;
	color: #a6a59e;
	margin-top: 0;
}

.toolbar {
	position: absolute;
	padding: 0;
	top: 8px;
	right: -8px;
}

.toolbar .moreCommand.highlight {
	background: none;
}

.tiddler .toolbar .button {
	border: none;
	display: inline;
	padding: 0px;
	margin-right: 16px;
}

.tiddler .toolbar a:hover {
	background: none;
}

.tiddler .tagged .listTitle {
	display: none;
}

.revButton {
	float: right;
}

/*! EditTemplate specific*/
.tiddler .privacySettings {
	text-align: center;
}
.tiddler .privacySettings .originButton {
	display: inline;
}

.editSpaceSiteIcon, .privacyEdit {
	float: left;
}

.editSpaceSiteIcon svg,
.editSpaceSiteIcon img,
.editSpaceSiteIcon .roundelLabel {
	float: left;
}

.tagTitle {
	position: absolute;
	text-align: center;
	width: 48px;
	top: 0px;
	left: -56px;
}

.editSpaceSiteIcon .originButton img,
.editSpaceSiteIcon .originButton svg {
	height: 16px;
	margin-left: 24px;
	margin-right: 32px;
	width: 16px;
}

.tagAnnotation {
	margin-top: 8px;
	padding-bottom: 8px;
}
.annotationsBox {
	margin-top: 8px;
}

.editorFooter {
	position: relative;
	padding: 0;
	margin-top: 16px;
	margin-left: 64px;
}

.tiddler .editorFooter .editor {
	padding-left: 0px;
}

.heading .editor input {
	width: 100%;
	font-size: 1.5em;
}

.spaceSiteIcon .externalImage .image a:hover,
.modifierIcon .externalImage .image a:hover {
	background: none;
}

div.toolbar {
	visibility:hidden;
	right:-16px;
}

.selected div.toolbar {
	visibility: visible;
}

.followButton a:hover {
	background: [[ColorPalette::PrimaryMid]];
	text-decoration: underline;
}

a.image:hover {
	background: transparent;
}

@media all and (max-device-width: 480px) {
	div.toolbar {
		visibility:visible;
	}
}
@media only screen and (device-width: 768px) {
	div.toolbar {
		visibility:visible;
	}
}
@media all and (max-width: 960px) {
	.tiddler .titleBar {
		margin-left: 36px;
		margin-right: 80px;
	}

	.tiddler .heading {
		margin-bottom: 48px;
	}

	.tiddler .heading .title {
		font-size: 32px;
		line-height: 32px;
	}

	.tiddler .modifierIcon img,
	.tiddler .modifierIcon svg,
	.tiddler .spaceSiteIcon .originButton img,
	.originButton svg {
		width: 32px;
		height: 32px;
		margin-left: 0px;
		margin-right: 0px;
	}

	.tiddler .followPlaceHolder {
		right: 48px;
	}

	.tiddler .followButton {
		width: 24px;
	}

	.tiddler .viewer {
		margin: 0px 0px 0px 36px;
		padding-top: 0;
	}

	br {
		line-height: 0.5em;
	}
}
/*}}}*/</pre>
</div>
<div title="FollowTiddlersBlackList" server.title="FollowTiddlersBlackList" server.page.revision="1521900" server.etag="&quot;tiddlyspace/FollowTiddlersBlackList/1521900:f0b2725f417228dc9a0fdba51144656a5da6a74a&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/tiddlyspace" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="tiddlyspace" server.permissions="read" server.content-type="" modified="20131111192334" created="20131111192334" tags="excludeLists excludeMissing excludeSearch" _hash="6fc8ab230a904a71d63a42d97dccd8e135c1ed1c">
<pre>ColorPalette
StyleSheet
SiteSubtitle
GettingStarted
SiteTitle
MainMenu
SiteIcon
DefaultTiddlers
ViewTemplate
PageTemplate
SideBarOptions
EditTemplate
SiteInfo
SideBarTabs
ToolbarCommands</pre>
</div>
<div title="spaceTitle" server.title="spaceTitle" server.page.revision="1521874" server.etag="&quot;system-info_public/spaceTitle/1521874:828ac7de75f6fa94209b42f468d9d2d2f08b2608&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-info_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-info_public" server.permissions="read" server.content-type="" modified="20131111192330" created="20131111192330" tags="excludeLists excludeSearch" _hash="fc6cbafbbf1009da659a70f1f400ca4db8ebc84d">
<pre>The title and subtitle of your space are visible to visitors and are also displayed in your browser's tabs. Click on the SiteTitle and SiteSubtitle tiddler links below to make changes.
* [[SiteTitle]]
* [[SiteSubtitle]]</pre>
</div>
<div title="SiteInfo" server.title="SiteInfo" server.page.revision="2560387" server.etag="&quot;honly-666_public/SiteInfo/2560387:a5a42e80a1d7797eeb1644fedeb2741a93ae7925&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20160918153937" created="20160906130608" tags="" _hash="3c5a3312d087f5c0cb3163b23787ca52c2dcb5c2">
<pre>Type the text for '图片'</pre>
</div>
<div title="第五次作业" server.title="第五次作业" server.page.revision="2584521" server.etag="&quot;honly-666_public/%E7%AC%AC%E4%BA%94%E6%AC%A1%E4%BD%9C%E4%B8%9A/2584521:4ac43cc9ce77218919f6cb373fa0e5fec088782d&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20161114054751" created="20161102140255" tags="比较知乎和百度" _hash="47689ee466b00c194a8f820d8c649f1d9cf54eaa">
<pre>比较知乎和百度:
 知乎是一个实名制的网络问答社区。 百度知道-是一个你不知道回答者的可信度，从而也降低了答案的可靠度。非实名，用户难以有的放矢地提问和回答，答案的效用和准确度极低。
     1.从积分制度来说：百度有而知乎无
    积分制度的存在对于百度知道来说是利弊都有，利大于弊。“利”在于其鼓励了用户去回答有积分悬赏或者悬赏值高的问题，“弊”是积分奖励少或者没有的问题不容易得到回答。 而知乎网是没有设置积分制度的也就规避了这种制度的“利和弊”。
     2.从对问题的控制来说：百度无而知乎有
百度知道依靠的是网民中的管理员，管理员对问题进行检举、修正分类、处理过期问题，而知乎网，发布一个问题之前，会出现要求用户先检索有无类似问题的对话框，且对于每个发布出来的问题，每位知乎网的用户都可以评论、举报。    
3.从对答案的控制来说：百度有而知乎更有优势
    百度知道中一旦最佳答案选择完毕，整个问题就定型了，及时未来有人有更优质的答案也没有办法作答。这使得百度知道对答案的控制显得生硬。而知乎网对于答案的控制措施仍然沿用了其对问题的控制措施。对于劣质回答可以举报，被举报次数达到一定数目的回答在人工处理之后会被“折叠”，不在默认显示该条答案内容；对于优质的问题进行实名赞同，靠票数将好回答顶上去。
   4.从对用户的控制来说：百度无而知乎有
作为问答类型的社区，百度知道几乎没有限制，任何网民都可以使用。但是百度知道的“企业知道”和“专家频道”提供的用户来源确实是有水准的，而知乎网从创建伊始就打出了“连接各行各业精英”的旗号，据此吸引而来的自然就是“精英用户”为主。    
总结：我们可以看出，除了积分制度之外，知乎网在UGC模式上胜出。未来百度知道这个庞然大物何时开始模仿知乎，我认为也只是一个时间的问题。用户可以将二者更好的结合起来，选择一个适合的网络问答平台来进行信息检索和收集。   



</pre>
</div>
<div title="DefaultTiddlers" server.title="DefaultTiddlers" server.page.revision="2576999" server.etag="&quot;honly-666_public/DefaultTiddlers/2576999:6422e0b0c97d0709d96e46b74f44bf8b18f7be2c&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20161026043922" created="20160906130629" tags="excludeLists" _hash="9469a0b9118a57912681783685584f53bce35b70">
<pre>[[GettingStarted]]</pre>
</div>
<div title="RevisionTemplate" server.title="RevisionTemplate" server.page.revision="1521915" server.etag="&quot;system-theme_public/RevisionTemplate/1521915:e2dccc28905242c7c73618650cfc3d6607acde9f&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-theme_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-theme_public" server.permissions="read" server.content-type="" modified="20131111192330" created="20131111192330" tags="excludeLists excludeMissing excludeSearch" _hash="b182c10523c4d9fe3f622b1529b70d43f5150701">
<pre>&lt;!--{{{--&gt;
&lt;div macro='slideRevision'&gt;&lt;/div&gt;
&lt;div class='heading'&gt;
	&lt;span class="titleBar"&gt;
		&lt;div class='title' macro='view title text'&gt;&lt;/div&gt;
	&lt;/span&gt;
	&lt;span class='modifierIcon'
		macro='view modifier SiteIcon label:no height:48 width:48 preserveAspectRatio:yes'&gt;
	&lt;/span&gt;
	&lt;div class='toolbar'
		macro='toolbar [[ToolbarCommands::RevisionToolbar]] icons:yes height:48 width:48 more:popup'&gt;
	&lt;/div&gt;
	&lt;div class='tagClear'&gt;&lt;/div&gt;
&lt;/div&gt;
&lt;div class='content'&gt;
	&lt;div class='viewer' macro='view text wikified'&gt;&lt;/div&gt;
&lt;/div&gt;
&lt;div class='tagInfo'&gt;
	&lt;div class='tidTags' macro='tags'&gt;&lt;/div&gt;
	&lt;div class='tagging' macro='tagging'&gt;&lt;/div&gt;
&lt;/div&gt;
&lt;!--}}}--&gt;</pre>
</div>
<div title="泽海之鲸" server.title="泽海之鲸" server.page.revision="2579872" server.etag="&quot;honly-666_public/%E6%B3%BD%E6%B5%B7%E4%B9%8B%E9%B2%B8/2579872:6278f7b4532b90cd13da318403c2397192c8185c&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20161102042241" created="20161030065241" tags="Bojeck" _hash="d498c107295211e6bb7c9abbaa7786445feda159">
<pre>Type the text for 'NewTiddler'http://static2.jiaju.com/malljiaju/goods/fb/1b/4e9159e7b9c1206a917c_b.jpg

习惯性好吃懒做 间接性踌躇满志</pre>
</div>
<div title="GettingStarted" server.title="GettingStarted" server.page.revision="2579873" server.etag="&quot;honly-666_public/GettingStarted/2579873:312ab000041dccb2cdf6505abed26ef5977689dd&quot;" modifier="honly-666" creator="osmosoft" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20161102042356" created="20131111192330" tags="excludeLists excludeMissing excludeSearch" _hash="c711b4962abe6ce6f32c7623cc264f836b1e8477">
<pre>&lt;html&gt;
&lt;body&gt;
&lt;div align="center"&gt;
&lt;h1&gt;&lt;marquee behavior=alternate&gt;
人生就像心电图 必须折腾起来
&lt;br&gt;&lt;img src="http://img.hb.aicdn.com/39dd09f421cdbd7fb5fae01ce5953cf513676940ca77-T3vq3X_fw658"height="400"width="500"&gt;&lt;/marquee&gt;&lt;/h1&gt;&lt;br&gt;

&lt;/marquee&gt;&lt;/h1&gt;&lt;br&gt;
&lt;/div&gt;&lt;div align="center"&gt;
&lt;h1&gt;&lt;font color="blue"face="宋体"size="20"&gt;&lt;/font&gt;&lt;br/&gt;&lt;h1&gt;

你永远不知到明天和意外哪个先来&lt;br/&gt;
想要做的事要抓紧做&lt;br/&gt;
没说出口的话要记得说&lt;br/&gt;
无论如何&lt;br/&gt;
都希望我喜欢的你们能平平安安的过完这一生&lt;br/&gt;&lt;/div&gt;
     
&lt;br&gt;&lt;img src="http://img.hb.aicdn.com/04774fded01448460b2647156bc213fd7de211e940a1-jz5bTp_fw658"height="400"width="600"&gt;


&lt;/div&gt;&lt;div align="center"&gt;

  &lt;p style="color:#DC143C;font-size:30px;font-family: "微软雅黑"";
 &lt;br&gt; 人生就像心电图&lt;/br&gt;
          &lt;br&gt;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;必须折腾起来！&lt;/br&gt;
  &lt;/p&gt;&lt;/marquee&gt;&lt;/h1&gt;&lt;br&gt;


&lt;a href="http:\\www.baidu.com"&gt;百度&lt;/a&gt;
 &lt;/body&gt;
&lt;/html&gt;
&lt;html&gt;
&lt;p fontsize:60px;&gt; &amp;copy版权所有    贵州财经大学   魏玉婷&lt;/p&gt;
&lt;/html&gt;</pre>
</div>
<div title="TiddlySpacePublishingCommands" server.title="TiddlySpacePublishingCommands" server.page.revision="1521868" server.etag="&quot;system-plugins_public/TiddlySpacePublishingCommands/1521868:edb203eff26eb90809a833f62701c58a9e23e81d&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-plugins_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-plugins_public" server.permissions="read" server.content-type="text/javascript" modified="20131111192330" created="20131111192330" tags="excludeLists excludeSearch systemConfig" _hash="d38da0ee80a7dc114a17466600f9430fa2a962bb">
<pre>/***
|''Name''|TiddlySpacePublishingCommands|
|''Version''|0.8.5|
|''Status''|@@beta@@|
|''Description''|toolbar commands for drafting and publishing|
|''Author''|Jon Robson|
|''Source''|http://github.com/TiddlySpace/tiddlyspace/raw/master/src/plugins/TiddlySpacePublishingCommands.js|
|''CoreVersion''|2.6.1|
|''Requires''|TiddlySpaceConfig TiddlySpaceFilters|
!Usage
Provides changeToPrivate, changeToPublic and saveDraft commands
Provides TiddlySpacePublisher macro.
{{{&lt;&lt;TiddlySpacePublisher type:private&gt;&gt;}}} make lots of private tiddlers public.
{{{&lt;&lt;TiddlySpacePublisher type:public&gt;&gt;}}} make lots of public tiddlers public.
!TODO
* add public argument?
!Code
***/
//{{{
(function($) {

var tiddlyspace = config.extensions.tiddlyspace;
var originMacro = config.macros.tiddlerOrigin;

tiddlyspace.getTiddlerStatusType = function(tiddler) {
	var isShadow = store.isShadowTiddler(tiddler.title);
	var exists = store.tiddlerExists(tiddler.title);
	if(isShadow &amp;&amp; !exists) {
		return "shadow";
	} else if(!exists) {
		return "missing";
	} else {
		var types = ["private", "public"];
		var type = "external";
		for(var i = 0; i &lt; types.length; i++) {
			var t = types[i];
			type = config.filterHelpers.is[t](tiddler) ? t : type;
		}
		if(config.filterHelpers.is.unsynced(tiddler)) {
			type = type == "private" ? "unsyncedPrivate" : "unsyncedPublic";
		}
		return type;
	}
};

var cmd = config.commands.publishTiddler = {
	text: "make public",
	tooltip: "Change this private tiddler into a public tiddler",
	errorMsg: "Error publishing %0: %1",

	isEnabled: function(tiddler) {
		return !readOnly &amp;&amp; config.filterHelpers.is["private"](tiddler);
	},
	handler: function(ev, src, title) {
		var tiddler = store.getTiddler(title);
		if(tiddler) {
			var newBag = cmd.toggleBag(tiddler.fields["server.bag"]);
			this.moveTiddler(tiddler, {
				title: tiddler.fields["publish.name"] || tiddler.title,
				fields: { "server.bag": newBag }
			});
		}
	},
	toggleBag: function(bag, to) {
		var newBag;
		if(typeof bag != typeof "") {
			var tiddler = bag;
			bag = tiddler.fields["server.bag"];
		}
		if(bag.indexOf("_private") &gt; -1) { // should make use of endsWith
			to = to ? to : "public";
			newBag = bag.replace("_private", "_" + to);
		} else {
			to = to ? to : "private";
			newBag = bag.replace("_public", "_" + to);
		}
		return newBag;
	},
	copyTiddler: function(title, newTitle, newBag, callback) {
		var original = store.getTiddler(title);
		newTitle = newTitle ? newTitle : title;
		var adaptor = original.getAdaptor();
		var publish = function(original, callback) {
			var tiddler = $.extend(new Tiddler(newTitle), original);
			tiddler.fields = $.extend({}, original.fields, {
				"server.bag": newBag,
				"server.workspace": "bags/%0".format(newBag),
				"server.page.revision": "false"
			});
			delete tiddler.fields["server.title"];
			tiddler.title = newTitle;
			adaptor.putTiddler(tiddler, null, null, callback);
		};
		publish(original, callback);
	},
	moveTiddler: function(tiddler, newTiddler, callback) {
			var info = {
			copyContext: {},
			deleteContext: {}
		};
		var _dirty = store.isDirty();
		var adaptor = tiddler.getAdaptor();
		var newTitle = newTiddler.title;
		var oldTitle = tiddler.title;
		delete tiddler.fields["server.workspace"];
		var oldBag = tiddler.fields["server.bag"];
		var newBag = newTiddler.fields["server.bag"];
		var newWorkspace = "bags/%0".format(newBag);
		cmd.copyTiddler(oldTitle, newTitle, newBag, function(ctx) {
				info.copyContext = ctx;
				var context = {
					tiddler: tiddler,
					workspace: newWorkspace
				};
				store.addTiddler(ctx.tiddler);
				tiddler.title = oldTitle; // for cases where a rename occurs
				if(ctx.status) { // only do if a success
					if(oldBag != newBag) {
						adaptor.deleteTiddler(tiddler, context, {}, function(ctx) {
							info.deleteContext = ctx;
							var el;
							if(tiddler) {
								tiddler.fields["server.workspace"] = newWorkspace;
								tiddler.fields["server.bag"] = newBag;
							}
							el = el ? el : story.refreshTiddler(oldTitle, null, true);
							if(oldTitle != newTitle) {
								store.deleteTiddler(oldTitle);
								store.notify(oldTitle, true);
							}
							if(el) {
								story.displayTiddler(el, newTitle);
							}
							if(oldTitle != newTitle) {
								story.closeTiddler(oldTitle);
							}
							if(callback) {
								callback(info);
							}
							store.setDirty(_dirty);
						});
					} else {
						if(callback) {
							callback(info);
						}
					}
					refreshDisplay();
				}
		});
	}
};

var changeToPrivate = config.commands.changeToPrivate = {
	text: "make private",
	tooltip: "turn this public tiddler into a private tiddler",
	isEnabled: function(tiddler) {
		return !readOnly &amp;&amp; config.filterHelpers.is["public"](tiddler);
	},
	handler: function(event, src, title) {
		var tiddler = store.getTiddler(title);
		var newBag = cmd.toggleBag(tiddler, "private");
		var newTiddler = { title: title, fields: { "server.bag": newBag }};
		cmd.moveTiddler(tiddler, newTiddler);
	}
};
config.commands.changeToPublic = cmd;

/* Save as draft command */
var saveDraftCmd = config.commands.saveDraft = {
	text: "save draft",
	tooltip: "Save as a private draft",
	isEnabled: function(tiddler) {
		return changeToPrivate.isEnabled(tiddler);
	},
	getDraftTitle: function(title) {
		var draftTitle;
		var draftNum = "";
		while(!draftTitle) {
			var suggestedTitle = "%0 [draft%1]".format(title, draftNum);
			if(store.getTiddler(suggestedTitle)) {
				draftNum = !draftNum ? 2 : draftNum + 1;
			} else {
				draftTitle = suggestedTitle;
			}
		}
		return draftTitle;
	},
	createDraftTiddler: function(title, gatheredFields) {
		var tiddler = store.getTiddler(title);
		var draftTitle = saveDraftCmd.getDraftTitle(title);
		var draftTiddler = new Tiddler(draftTitle);
		if(tiddler) {
			$.extend(true, draftTiddler, tiddler);
		} else {
			$.extend(draftTiddler.fields, config.defaultCustomFields);
		}
		for(var fieldName in gatheredFields) {
			if(TiddlyWiki.isStandardField(fieldName)) {
				draftTiddler[fieldName] = gatheredFields[fieldName];
			} else {
				draftTiddler.fields[fieldName] = gatheredFields[fieldName];
			}
		}
		var privateBag = tiddlyspace.getCurrentBag("private");
		var privateWorkspace = tiddlyspace.getCurrentWorkspace("private");
		draftTiddler.title = draftTitle;
		draftTiddler.fields["publish.name"] = title;
		draftTiddler.fields["server.workspace"] = privateWorkspace;
		draftTiddler.fields["server.bag"] = privateBag;
		draftTiddler.fields["server.title"] = draftTitle;
		draftTiddler.fields["server.page.revision"] = "false";
		delete draftTiddler.fields["server.etag"];
		return draftTiddler;
	},
	handler: function(ev, src, title) {
		var tiddler = store.getTiddler(title); // original tiddler
		var tidEl = story.getTiddler(title);
		var uiFields = {};
		story.gatherSaveFields(tidEl, uiFields);
		var tid = saveDraftCmd.createDraftTiddler(title, uiFields);
		tid = store.saveTiddler(tid.title, tid.title, tid.text, tid.modifier,
			new Date(), tid.tags, tid.fields);
		autoSaveChanges(null, [tid]);
		story.closeTiddler(title);
		story.displayTiddler(src, title);
		story.displayTiddler(src, tid.title);
	}
};

var macro = config.macros.TiddlySpacePublisher = {
	locale: {
		title: "Batch Publisher",
		changeStatusLabel: "Make %0",
		noTiddlersText: "No tiddlers to publish",
		changeStatusPrompt: "Make all the selected tiddlers %0.",
		description: "Change tiddlers from %0 to %1 in this space"
	},

	listViewTemplate: {
		columns: [
			{ name: "Selected", field: "Selected", rowName: "title", type: "Selector" },
			{ name: "Tiddler", field: "tiddler", title: "Tiddler", type: "Tiddler" },
			{ name: "Status", field: "status", title: "Status", type: "WikiText" }
		],
		rowClasses: []
	},

	changeStatus: function(tiddlers, status, callback) { // this is what is called when you click the publish button
		var publicBag;
		for(var i = 0; i &lt; tiddlers.length; i++) {
			var tiddler = tiddlers[i];
			var newTiddler = {
				title: tiddler.title,
				fields: { "server.bag": cmd.toggleBag(tiddler, status) }
			};
			cmd.moveTiddler(tiddler, newTiddler, callback);
		}
	},
	getMode: function(paramString) {
		var params = paramString.parseParams("anon")[0];
		var status = params.type ?
			(["public", "private"].contains(params.type[0]) ? params.type[0] : "private") :
			"private";
		var newStatus = status == "public" ? "private" : "public";
		return [status, newStatus];
	},
	handler: function(place, macroName, params, wikifier, paramString, tiddler) {
		var wizard = new Wizard();
		var locale = macro.locale;
		var status = macro.getMode(paramString);
		wizard.createWizard(place, locale.title);
		wizard.addStep(macro.locale.description.format(status[0], status[1]),
			'&lt;input type="hidden" name="markList" /&gt;');
		var markList = wizard.getElement("markList");
		var listWrapper = $("&lt;div /&gt;").addClass("batchPublisher").
			attr("refresh", "macro").attr("macroName", macroName).
			attr("params", paramString)[0];
		markList.parentNode.insertBefore(listWrapper, markList);
		$.data(listWrapper, "wizard", wizard);
		macro.refresh(listWrapper);
	},
	getCheckedTiddlers: function(listWrapper, titlesOnly) {
		var tiddlers = [];
		$(".chkOptionInput[rowName]:checked", listWrapper).each(function(i, el) {
			var title = $(el).attr("rowName");
			if(titlesOnly) {
				tiddlers.push(title);
			} else {
				tiddlers.push(store.getTiddler(title));
			}
		});
		return tiddlers;
	},
	refresh: function(listWrapper) {
		var checked = macro.getCheckedTiddlers(listWrapper, true);
		var paramString = $(listWrapper).empty().attr("params");
		var wizard = $.data(listWrapper, "wizard");
		var locale = macro.locale;
		var params = paramString.parseParams("anon")[0];
		var publishCandidates = [];
		var status = macro.getMode(paramString);
		var pubType = status[0];
		var newPubType = status[1];
		var tiddlers = params.filter ? store.filterTiddlers(params.filter[0]) :
			store.filterTiddlers("[is[%0]]".format(pubType));
		var enabled = [];
		for(var i = 0; i &lt; tiddlers.length; i++) {
			var tiddler = tiddlers[i];
			var title = tiddler.title;
			if(!tiddler.tags.contains("excludePublisher") &amp;&amp; title !== "SystemSettings") {
				publishCandidates.push({ title: title, tiddler: tiddler, status: pubType});
			}
			if(checked.contains(title)) {
				enabled.push("[rowname=%0]".format(title));
			}
		}

		if(publishCandidates.length === 0) {
			createTiddlyElement(listWrapper, "em", null, null, locale.noTiddlersText);
		} else {
			var listView = ListView.create(listWrapper, publishCandidates, macro.listViewTemplate);
			wizard.setValue("listView", listView);
			var btnHandler = function(ev) {
				var tiddlers = macro.getCheckedTiddlers(listWrapper);
				var callback = function(status) {
					$(".batchPublisher").each(function(i, el) {
						macro.refresh(el);
					});
				};
				macro.changeStatus(tiddlers, newPubType, callback);
			};
			wizard.setButtons([{
				caption: locale.changeStatusLabel.format(newPubType),
				tooltip: locale.changeStatusPrompt.format(newPubType),
				onClick: btnHandler
			}]);
			$(enabled.join(",")).attr("checked", true); // retain what was checked before
		}
	}
};

})(jQuery);
//}}}</pre>
</div>
<div title="TiddlySpaceTabs" server.title="TiddlySpaceTabs" server.page.revision="1521916" server.etag="&quot;system-theme_public/TiddlySpaceTabs/1521916:7f13925e4c6f7a4b0dea29ca7a6ffb404bfcd4a6&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-theme_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-theme_public" server.permissions="read" server.content-type="" modified="20131111192330" created="20131111192330" tags="excludeLists excludeSearch" _hash="7bc357188d6afd65d6724a670b0052c0488766a4">
<pre>!Spaces
&lt;&lt;groupBy server.bag&gt;&gt;

!Private
&lt;&lt;list filter [is[private]]&gt;&gt;

!Public
&lt;&lt;list filter [is[public]]&gt;&gt;

!Drafts
&lt;&lt;list filter [is[draft]]&gt;&gt;</pre>
</div>
<div title="TiddlySpaceBackstage" server.title="TiddlySpaceBackstage" server.page.revision="1521910" server.etag="&quot;tiddlyspace/TiddlySpaceBackstage/1521910:819c837d86dc673f416a4adb02c21acdbb82664c&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/tiddlyspace" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="tiddlyspace" server.permissions="read" server.content-type="text/javascript" modified="20131111192332" created="20131111192332" tags="excludeLists excludeSearch systemConfig" _hash="390091c823ffd5ec5008f2a8174c3caccfa6302b">
<pre>/***
|''Name''|TiddlySpaceBackstage|
|''Version''|0.8.0|
|''Description''|Provides a TiddlySpace version of the backstage and a homeLink macro|
|''Status''|@@beta@@|
|''Contributors''|Jon Lister, Jon Robson, Colm Britton|
|''Source''|http://github.com/TiddlySpace/tiddlyspace/raw/master/src/plugins/TiddlySpaceBackstage.js|
|''Requires''|TiddlySpaceConfig ImageMacroPlugin TiddlySpaceViewTypes|
!StyleSheet
.tiddler .error.annotation .button{
	display: inline-block;
}

#backstageArea {
	z-index: 49;
	color: white;
	background-color: black;
	background: -webkit-gradient(linear,left bottom,left top,color-stop(0, #222),color-stop(0.5, #333),color-stop(1, #555));
	background: -moz-linear-gradient(center bottom,#222 0%, #333 50%, #555 100%);
	filter: progid:DXImageTransform.Microsoft.gradient(startColorstr=#ff555555, endColorstr=#ff222222);
	-ms-filter: "progid:DXImageTransform.Microsoft.gradient(startColorstr=#ff555555, endColorstr=#ff222222)";
	height: 25px;
	padding: 0;
}

#backstageButton {
	overflow: hidden;
}

#backstageButton #backstageShow,
#backstageButton #backstageHide {
	margin: 0px;
	padding: 0px;
}

#backstageButton #backstageShow:hover,
#backstageButton #backstageHide:hover {
	background: none;
	color: none;
}

#backstageButton img,
#backstageButton svg {
	width: 24px;
	height: 24px;
}

#messageArea {
	top: 50px;
}

#backstageToolbar {
	position: relative;
}

#backstageArea a {
	padding: 0px;
	margin-left: 0px;
	color: white;
	background: none;
}

#backstageArea a:hover {
	background-color: white;
}

#backstage ol,
#backstage ul {
	padding: auto;
}

#backstageButton a {
	margin: 0;
}

.backstagePanelBody ul {
	padding: 5px;
	margin: 5px;
}

#backstage #backstagePanel {
	margin-left: 5%;
	padding: 0em;
	margin-right: 5%;
}

#backstageToolbar a {
	position: relative;
}

#backstageArea a.backstageSelTab,
#backstageToolbar .backstageTask {
	line-height: 25px;
	color: #767676;
}

.backstageTask .externalImage,
.backstageTask .image {
	display: inline;
}

#backstageToolbar a span {
	z-index: 2;
}

a.backstageTask {
	display: inline;
        margin-left: 1em !important;
}

.backstagePanelBody .button {
	display: inline-block;
	margin-right: 10px;
}

.backstagePanelBody {
	margin: 0 0 0 0.6em;
	padding: 0.4em 0.5em 1px 0.5em;
}

#backstage table {
	margin: auto;
}

#backstage .wizard table {
	border: 0px;
	margin: 0;
}

#backstage div  li.listLink {
	border: 0px;
	width: 78%;
	font-size: 0.7em;
}

#backstage div li.listTitle {
	font-weight: bold;
	text-decoration: underline;
	font-size: 1em;
	background: #ccc;
	width: 100%;
}

#backstage fieldset {
	border: solid 1px [[ColorPalette::Background]];
}

#backstage .viewer table,#backstage table.twtable {
	border: 0px;
}

#backstageToolbar img {
	padding: 0;
}

#backstage .wizard,
#backstage .wizardFooter {
	background: none;
}

.viewer td, .viewer tr, .twtable td, .twtable tr {
	border: 1px solid #eee;
}

#backstage .inlineList ul li {
	background-color: [[ColorPalette::Background]];
	border: solid 1px [[ColorPalette::TertiaryMid]];
	display: block;
	float: left;
	list-style: none;
	margin-right: 1em;
	padding: 0.5em;
}

.backstageClear, .inlineList form {
	clear: both;
	display: block;
	margin-top: 3em;
}

.tiddlyspaceMenu {
	text-align: center;
}

span.chunkyButton {
	display: inline-block;
	padding: 0;
	margin: 0;
	border: solid 2px #000;
	background-color: #04b;
}

span.chunkyButton a.button, span.chunkyButton a:active.button {
	white-space: nowrap;
	font-weight: bold;
	font-size: 1.8em;
	color: #fff;
	text-align: center;
	padding: 0.5em 0.5em;
	margin: 0;
	border-style: none;
	display: block;
}

span.chunkyButton:hover {
	background-color: #014;
}

span.chunkyButton a.button:hover {
	border-style: none;
	background: none;
	color: #fff;
}

#backstage .unpluggedSpaceTab .wizard,
.unpluggedSpaceTab .wizard {
	background: white;
	border: 2px solid #CCC;
	padding: 5px;
}

.syncKey .keyItem {
	border: 1px solid black;
	display: inline-block;
	margin: 0.2em;
	padding: 0.1em 0.1em 0.1em 0.1em;
}

.keyHeading {
	font-size: 2em;
	font-weight: bold;
	margin: 0.4em 0em -0.2em;
}

.unpluggedSpaceTab .putToServer,
.unpluggedSpaceTab .notChanged {
	display: none;
}

.tiddlyspaceMenu ul {
	margin: 0;
	padding: 0;
}

.tiddlyspaceMenu ul li {
	list-style: none;
}

.unsyncedChanges .unsyncedList {
	display: block;
}

.unsyncedList {
	display: none;
}
!Code
***/
//{{{
(function ($) {
    var name = "StyleSheet" + tiddler.title;
    config.shadowTiddlers[name] = "/*{{{*/\n%0\n/*}}}*/".
        format(store.getTiddlerText(tiddler.title + "##StyleSheet")); // this accesses the StyleSheet section of the current tiddler (the plugin that contains it)
    store.addNotification(name, refreshStyles);

    if (!config.extensions.tiddlyweb.status.tiddlyspace_version) { // unplugged
        config.extensions.tiddlyweb.status.tiddlyspace_version = "&lt;unknown&gt;";
        config.extensions.tiddlyweb.status.server_host = {
            url:config.extensions.tiddlyweb.host }; // TiddlySpaceLinkPlugin expects this
    }
    var disabled_tasks_for_nonmembers = ["tiddlers", "plugins", "batch", "sync"];

    var tweb = config.extensions.tiddlyweb;
    var tiddlyspace = config.extensions.tiddlyspace;
    var currentSpace = tiddlyspace.currentSpace.name;
    var imageMacro = config.macros.image;

    if (config.options.chkBackstage === undefined) {
        config.options.chkBackstage = false;
    }

// Set up Backstage
    config.tasks = {};
    config.tasks.status = {
        text:"status",
        tooltip:"TiddlySpace Info",
        content:"&lt;&lt;tiddler Backstage##Menu&gt;&gt;"
    };
    config.tasks.tiddlers = {
        text:"tiddlers",
        tooltip:"tiddlers control panel",
        content:"&lt;&lt;tiddler Backstage##BackstageTiddlers&gt;&gt;"
    };
    config.tasks.plugins = {
        text:"plugins",
        tooltip:"Manage installed plugins",
        content:"&lt;&lt;tiddler Backstage##Plugins&gt;&gt;"
    };
    config.tasks.batch = {
        text:"batch",
        tooltip:"Batch manage public/private tiddlers",
        content:"&lt;&lt;tiddler Backstage##BatchOps&gt;&gt;"
    };
    config.tasks.tweaks = {
        text:"tweaks",
        tooltip:"Tweak TiddlyWiki behaviors",
        content:"&lt;&lt;tiddler Backstage##Tweaks&gt;&gt;"
    };
    config.tasks.exportTiddlers = {
        text:"import/export",
        tooltip:"Import/export tiddlers from/to a TiddlyWiki",
        content:"&lt;&lt;tiddler Backstage##ImportExport&gt;&gt;"
    };
    config.tasks.sync = {
        text:"sync",
        tooltip:"Check Sync status",
        content:"&lt;&lt;tiddler Backstage##SpaceUnplugged&gt;&gt;"
    };

    if (window.location.protocol === "file:") {
        config.unplugged = true;
    }

    config.backstageTasks = ["status", "tiddlers", "plugins",
        "batch", "tweaks", "exportTiddlers", "sync"];

    config.messages.backstage.prompt = "";
// initialize state
    var _show = backstage.show;
    backstage.show = function () {
        // selectively hide backstage tasks and tabs based on user status
        var tasks = $("#backstageToolbar .backstageTask").show();
        var bs = backstage.tiddlyspace;
        if (!config.unplugged) {
            tweb.getUserInfo(function (user) {
                if (user.anon) {
                    jQuery.each(disabled_tasks_for_nonmembers, function (i, task) {
                        var taskIndex = config.backstageTasks.indexOf(task);
                        if (taskIndex !== -1) {
                            config.backstageTasks.splice(taskIndex, 1);
                        }
                    });
                    config.messages.memberStatus = bs.locale.loggedout;
                } else {
                    config.messages.memberStatus = readOnly ?
                        bs.locale.nonmember : bs.locale.member;
                }
            });
        } else {
            config.messages.memberStatus = bs.locale.unplugged;
        }

        // display backstage
        return _show.apply(this, arguments);
    };
    if (readOnly) {
        jQuery.each(disabled_tasks_for_nonmembers, function (i, task) {
            var taskIndex = config.backstageTasks.indexOf(task);
            if (taskIndex !== -1) {
                config.backstageTasks.splice(taskIndex, 1);
            }
        });
    }

    var tasks = config.tasks;
    var commonUrl = "/bags/common/tiddlers/%0";

    backstage.tiddlyspace = {
        locale:{
            member:"You are a member of this space.",
            nonmember:"You are not a member of this space.",
            loggedout:"You are currently logged out of TiddlySpace.",
            unplugged:"You are unplugged."
        },
        showButton:function () {
            var showBtn = $("#backstageShow")[0];
            var altText = $(showBtn).text();
            $(showBtn).empty();
            imageMacro.renderImage(showBtn, "backstage.svg",
                { altImage:commonUrl.format("backstage.png"), alt:altText});
        },
        hideButton:function () {
            var hideBtn = $("#backstageHide")[0];
            var altText = $(hideBtn).text();
            $(hideBtn).empty();
            imageMacro.renderImage(hideBtn, "close.svg",
                { altImage:commonUrl.format("close.png"), alt:altText, width:24, height:24 });
        }
    };

    var _init = backstage.init;
    backstage.init = function () {
        _init.apply(this, arguments);
        var init = function (user) {
            var bs = backstage.tiddlyspace;
            bs.showButton();
            bs.hideButton();
        };
        tweb.getUserInfo(init);
    };

    var home = config.macros.homeLink = {
        locale:{
            linkText:"your home space"
        },
        handler:function (place) {
            var container = $("&lt;span /&gt;").appendTo(place)[0];
            tweb.getUserInfo(function (user) {
                if (!user.anon &amp;&amp; user.name !== currentSpace) {
                    createSpaceLink(container, user.name, null, home.locale.linkText);
                }
            });
        }
    };

    config.macros.exportSpace = {
        handler:function (place, macroName, params) {
            var filename = params[0] ||
                "/tiddlers.wiki?download=%0.html".format(currentSpace);
            $('&lt;a class="button"&gt;download&lt;/a&gt;').// XXX: i18n
                attr("href", filename).appendTo(place);
        }
    };

}(jQuery));
//}}}</pre>
</div>
<div title="RevisionsCommandPlugin" server.title="RevisionsCommandPlugin" server.page.revision="1521856" server.etag="&quot;system/RevisionsCommandPlugin/1521856:1921bbe97343019f7e765148ba057ff96be3721f&quot;" modifier="FND" creator="FND" server.workspace="bags/system" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system" server.permissions="read" server.content-type="text/javascript" modified="20130924180405" created="20130924180405" tags="excludeLists excludeSearch systemConfig" _hash="d36d2c8a7f8dd9a59dd54e772114a415b2c22979">
<pre>/***
|''Name''|RevisionsCommandPlugin|
|''Description''|provides access to tiddler revisions|
|''Author''|FND|
|''Contributors''|Martin Budden|
|''Version''|0.3.3|
|''Status''|@@beta@@|
|''Source''|http://svn.tiddlywiki.org/Trunk/association/plugins/RevisionsCommandPlugin.js|
|''CodeRepository''|http://svn.tiddlywiki.org/Trunk/association/plugins/|
|''License''|[[BSD|http://www.opensource.org/licenses/bsd-license.php]]|
|''CoreVersion''|2.6.0|
|''Keywords''|serverSide|
!Usage
Extend [[ToolbarCommands]] with {{{revisions}}}.
!Revision History
!!v0.1 (2009-07-23)
* initial release (renamed from experimental ServerCommandsPlugin)
!!v0.2 (2010-03-04)
* suppressed wikification in diff view
!!v0.3 (2010-04-07)
* restored wikification in diff view
* added link to side-by-side diff view
!To Do
* strip server.* fields from revision tiddlers
* resolve naming conflicts
* i18n, l10n
* code sanitizing
* documentation
!Code
***/
//{{{
(function($) {

jQuery.twStylesheet(".diff { white-space: pre, font-family: monospace }",
	{ id: "diff" });

var cmd = config.commands.revisions = {
	type: "popup",
	hideShadow: true,
	text: "revisions",
	tooltip: "display tiddler revisions",
	revTooltip: "", // TODO: populate dynamically?
	loadLabel: "loading...",
	loadTooltip: "loading revision list",
	selectLabel: "select",
	selectTooltip: "select revision for comparison",
	selectedLabel: "selected",
	compareLabel: "compare",
	linkLabel: "side-by-side view",
	revSuffix: " [rev. #%0]",
	diffSuffix: " [diff: #%0 #%1]",
	dateFormat: "YYYY-0MM-0DD 0hh:0mm",
	listError: "revisions could not be retrieved",

	handlePopup: function(popup, title) {
		title = this.stripSuffix("rev", title);
		title = this.stripSuffix("diff", title);
		var tiddler = store.getTiddler(title);
		var type = _getField("server.type", tiddler);
		var adaptor = new config.adaptors[type]();
		var limit = null; // TODO: customizable
		var context = {
			host: _getField("server.host", tiddler),
			workspace: _getField("server.workspace", tiddler)
		};
		var loading = createTiddlyButton(popup, cmd.loadLabel, cmd.loadTooltip);
		var params = { popup: popup, loading: loading, origin: title };
		adaptor.getTiddlerRevisionList(title, limit, context, params, this.displayRevisions);
	},

	displayRevisions: function(context, userParams) {
		removeNode(userParams.loading);
		if(context.status) {
			var callback = function(ev) {
				var e = ev || window.event;
				var revision = resolveTarget(e).getAttribute("revision");
				context.adaptor.getTiddlerRevision(tiddler.title, revision, context,
					userParams, cmd.displayTiddlerRevision);
			};
			var table = createTiddlyElement(userParams.popup, "table");
			for(var i = 0; i &lt; context.revisions.length; i++) {
				var tiddler = context.revisions[i];
				var row = createTiddlyElement(table, "tr");
				var timestamp = tiddler.modified.formatString(cmd.dateFormat);
				var revision = tiddler.fields["server.page.revision"];
				var cell = createTiddlyElement(row, "td");
				createTiddlyButton(cell, timestamp, cmd.revTooltip, callback, null,
					null, null, { revision: revision });
				cell = createTiddlyElement(row, "td", null, null, tiddler.modifier);
				cell = createTiddlyElement(row, "td");
				createTiddlyButton(cell, cmd.selectLabel, cmd.selectTooltip,
					cmd.revisionSelected, null, null, null,
					{ index:i, revision: revision, col: 2 });
				cmd.context = context; // XXX: unsafe (singleton)!?
			}
		} else {
			$("&lt;li /&gt;").text(cmd.listError).appendTo(userParams.popup);
		}
	},

	revisionSelected: function(ev) {
		var e = ev || window.event;
		e.cancelBubble = true;
		if(e.stopPropagation) {
			e.stopPropagation();
		}
		var n = resolveTarget(e);
		var index = n.getAttribute("index");
		var col = n.getAttribute("col");
		while(!index || !col) {
			n = n.parentNode;
			index = n.getAttribute("index");
			col = n.getAttribute("col");
		}
		cmd.revision = n.getAttribute("revision");
		var table = n.parentNode.parentNode.parentNode;
		var rows = table.childNodes;
		for(var i = 0; i &lt; rows.length; i++) {
			var c = rows[i].childNodes[col].firstChild;
			if(i == index) {
				if(c.textContent) {
					c.textContent = cmd.selectedLabel;
				} else {
					c.text = cmd.selectedLabel;
				}
			} else {
				if(c.textContent) {
					c.textContent = cmd.compareLabel;
				} else {
					c.text = cmd.compareLabel;
				}
				c.onclick = cmd.compareSelected;
			}
		}
	},

	compareSelected: function(ev) {
		var e = ev || window.event;
		var n = resolveTarget(e);
		var context = cmd.context;
		context.rev1 = n.getAttribute("revision");
		context.rev2 = cmd.revision;
		context.tiddler = context.revisions[n.getAttribute("index")];
		context.format = "unified";
		context.adaptor.getTiddlerDiff(context.tiddler.title, context,
			context.userParams, cmd.displayTiddlerDiffs);
	},

	displayTiddlerDiffs: function(context, userParams) {
		var tiddler = context.tiddler;
		tiddler.title += cmd.diffSuffix.format([context.rev1, context.rev2]);
		tiddler.text = "{{diff{\n" + context.diff + "\n}}}";
		tiddler.tags = ["diff"];
		tiddler.fields.doNotSave = "true"; // XXX: correct?
		if(!store.getTiddler(tiddler.title)) {
			store.addTiddler(tiddler);
		}
		var src = story.getTiddler(userParams.origin);
		var tiddlerEl = story.displayTiddler(src, tiddler);
		var uri = context.uri.replace("format=unified", "format=horizontal");
		var link = $('&lt;a target="_blank" /&gt;').attr("href", uri).text(cmd.linkLabel);
		$(".viewer", tiddlerEl).prepend(link);
	},

	displayTiddlerRevision: function(context, userParams) {
		var tiddler = context.tiddler;
		tiddler.title += cmd.revSuffix.format([tiddler.fields["server.page.revision"]]);
		tiddler.fields.doNotSave = "true"; // XXX: correct?
		if(!store.getTiddler(tiddler.title)) {
			store.addTiddler(tiddler);
		}
		var src = story.getTiddler(userParams.origin);
		story.displayTiddler(src, tiddler);
	},

	stripSuffix: function(type, title) {
		var str = cmd[type + "Suffix"];
		var i = str.indexOf("%0");
		i = title.indexOf(str.substr(0, i));
		if(i != -1) {
			title = title.substr(0, i);
		}
		return title;
	}
};

var _getField = function(name, tiddler) {
	return tiddler.fields[name] || config.defaultCustomFields[name];
};

})(jQuery);
//}}}</pre>
</div>
<div title="TiddlySpaceSanitizer" server.title="TiddlySpaceSanitizer" server.page.revision="1521866" server.etag="&quot;system-plugins_public/TiddlySpaceSanitizer/1521866:eb4bbe09bed63796fff17e5d99d67c21d6a8d706&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-plugins_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-plugins_public" server.permissions="read" server.content-type="text/javascript" modified="20131111192330" created="20131111192330" tags="excludeLists excludeSearch systemConfig" _hash="4e7490026802a699cc23155cd88b09a2cce3fb87">
<pre>/***
|''Description''|Sanitisation for dynamically pulling tiddlers into your space and displaying them|
!Notes
Works both inside and outside TiddlyWiki. Uses the HTML Sanitizer provided by the Google Caja project
(see http://code.google.com/p/google-caja/wiki/JsHtmlSanitizer for more on this), which is licensed under
an Apache License (see http://www.apache.org/licenses/LICENSE-2.0).
!Code
***/
//{{{
(function($) {

var cleanURL = function(url) {
	var regexp = /^(?:http|https|mailto|ftp|irc|news):\/\//;
	return (regexp.test(url)) ? url : null;
};

$.sanitize = function(html) {
	return html_sanitize(html, cleanURL);
};

/*
 * HTML Sanitizer, provided by Google Caja
 */

/* Copyright Google Inc.
 * Licensed under the Apache Licence Version 2.0
 * Autogenerated at Tue May 17 17:39:24 BST 2011
 * @provides html4
 */var html4={};html4.atype={NONE:0,URI:1,URI_FRAGMENT:11,SCRIPT:2,STYLE:3,ID:4,IDREF:5,IDREFS:6,GLOBAL_NAME:7,LOCAL_NAME:8,CLASSES:9,FRAME_TARGET:10},html4.ATTRIBS={"*::class":9,"*::dir":0,"*::id":4,"*::lang":0,"*::onclick":2,"*::ondblclick":2,"*::onkeydown":2,"*::onkeypress":2,"*::onkeyup":2,"*::onload":2,"*::onmousedown":2,"*::onmousemove":2,"*::onmouseout":2,"*::onmouseover":2,"*::onmouseup":2,"*::style":3,"*::title":0,"a::accesskey":0,"a::coords":0,"a::href":1,"a::hreflang":0,"a::name":7,"a::onblur":2,"a::onfocus":2,"a::rel":0,"a::rev":0,"a::shape":0,"a::tabindex":0,"a::target":10,"a::type":0,"area::accesskey":0,"area::alt":0,"area::coords":0,"area::href":1,"area::nohref":0,"area::onblur":2,"area::onfocus":2,"area::shape":0,"area::tabindex":0,"area::target":10,"bdo::dir":0,"blockquote::cite":1,"br::clear":0,"button::accesskey":0,"button::disabled":0,"button::name":8,"button::onblur":2,"button::onfocus":2,"button::tabindex":0,"button::type":0,"button::value":0,"canvas::height":0,"canvas::width":0,"caption::align":0,"col::align":0,"col::char":0,"col::charoff":0,"col::span":0,"col::valign":0,"col::width":0,"colgroup::align":0,"colgroup::char":0,"colgroup::charoff":0,"colgroup::span":0,"colgroup::valign":0,"colgroup::width":0,"del::cite":1,"del::datetime":0,"dir::compact":0,"div::align":0,"dl::compact":0,"font::color":0,"font::face":0,"font::size":0,"form::accept":0,"form::action":1,"form::autocomplete":0,"form::enctype":0,"form::method":0,"form::name":7,"form::onreset":2,"form::onsubmit":2,"form::target":10,"h1::align":0,"h2::align":0,"h3::align":0,"h4::align":0,"h5::align":0,"h6::align":0,"hr::align":0,"hr::noshade":0,"hr::size":0,"hr::width":0,"iframe::align":0,"iframe::frameborder":0,"iframe::height":0,"iframe::marginheight":0,"iframe::marginwidth":0,"iframe::width":0,"img::align":0,"img::alt":0,"img::border":0,"img::height":0,"img::hspace":0,"img::ismap":0,"img::name":7,"img::src":1,"img::usemap":11,"img::vspace":0,"img::width":0,"input::accept":0,"input::accesskey":0,"input::align":0,"input::alt":0,"input::autocomplete":0,"input::checked":0,"input::disabled":0,"input::ismap":0,"input::maxlength":0,"input::name":8,"input::onblur":2,"input::onchange":2,"input::onfocus":2,"input::onselect":2,"input::readonly":0,"input::size":0,"input::src":1,"input::tabindex":0,"input::type":0,"input::usemap":11,"input::value":0,"ins::cite":1,"ins::datetime":0,"label::accesskey":0,"label::for":5,"label::onblur":2,"label::onfocus":2,"legend::accesskey":0,"legend::align":0,"li::type":0,"li::value":0,"map::name":7,"menu::compact":0,"ol::compact":0,"ol::start":0,"ol::type":0,"optgroup::disabled":0,"optgroup::label":0,"option::disabled":0,"option::label":0,"option::selected":0,"option::value":0,"p::align":0,"pre::width":0,"q::cite":1,"select::disabled":0,"select::multiple":0,"select::name":8,"select::onblur":2,"select::onchange":2,"select::onfocus":2,"select::size":0,"select::tabindex":0,"table::align":0,"table::bgcolor":0,"table::border":0,"table::cellpadding":0,"table::cellspacing":0,"table::frame":0,"table::rules":0,"table::summary":0,"table::width":0,"tbody::align":0,"tbody::char":0,"tbody::charoff":0,"tbody::valign":0,"td::abbr":0,"td::align":0,"td::axis":0,"td::bgcolor":0,"td::char":0,"td::charoff":0,"td::colspan":0,"td::headers":6,"td::height":0,"td::nowrap":0,"td::rowspan":0,"td::scope":0,"td::valign":0,"td::width":0,"textarea::accesskey":0,"textarea::cols":0,"textarea::disabled":0,"textarea::name":8,"textarea::onblur":2,"textarea::onchange":2,"textarea::onfocus":2,"textarea::onselect":2,"textarea::readonly":0,"textarea::rows":0,"textarea::tabindex":0,"tfoot::align":0,"tfoot::char":0,"tfoot::charoff":0,"tfoot::valign":0,"th::abbr":0,"th::align":0,"th::axis":0,"th::bgcolor":0,"th::char":0,"th::charoff":0,"th::colspan":0,"th::headers":6,"th::height":0,"th::nowrap":0,"th::rowspan":0,"th::scope":0,"th::valign":0,"th::width":0,"thead::align":0,"thead::char":0,"thead::charoff":0,"thead::valign":0,"tr::align":0,"tr::bgcolor":0,"tr::char":0,"tr::charoff":0,"tr::valign":0,"ul::compact":0,"ul::type":0},html4.eflags={OPTIONAL_ENDTAG:1,EMPTY:2,CDATA:4,RCDATA:8,UNSAFE:16,FOLDABLE:32,SCRIPT:64,STYLE:128},html4.ELEMENTS={a:0,abbr:0,acronym:0,address:0,applet:16,area:2,b:0,base:18,basefont:18,bdo:0,big:0,blockquote:0,body:49,br:2,button:0,canvas:0,caption:0,center:0,cite:0,code:0,col:2,colgroup:1,dd:1,del:0,dfn:0,dir:0,div:0,dl:0,dt:1,em:0,fieldset:0,font:0,form:0,frame:18,frameset:16,h1:0,h2:0,h3:0,h4:0,h5:0,h6:0,head:49,hr:2,html:49,i:0,iframe:4,img:2,input:2,ins:0,isindex:18,kbd:0,label:0,legend:0,li:1,link:18,map:0,menu:0,meta:18,nobr:0,noframes:20,noscript:20,object:16,ol:0,optgroup:0,option:1,p:1,param:18,pre:0,q:0,s:0,samp:0,script:84,select:0,small:0,span:0,strike:0,strong:0,style:148,sub:0,sup:0,table:0,tbody:1,td:1,textarea:8,tfoot:1,th:1,thead:1,title:24,tr:1,tt:0,u:0,ul:0,"var":0},html4.ueffects={NOT_LOADED:0,SAME_DOCUMENT:1,NEW_DOCUMENT:2},html4.URIEFFECTS={"a::href":2,"area::href":2,"blockquote::cite":0,"body::background":1,"del::cite":0,"form::action":2,"img::src":1,"input::src":1,"ins::cite":0,"q::cite":0},html4.ltypes={UNSANDBOXED:2,SANDBOXED:1,DATA:0},html4.LOADERTYPES={"a::href":2,"area::href":2,"blockquote::cite":2,"body::background":1,"del::cite":2,"form::action":2,"img::src":1,"input::src":1,"ins::cite":2,"q::cite":2};var html=function(a){function x(b,c,d){var e=[];w(function(b,e){for(var f=0;f&lt;e.length;f+=2){var g=e[f],h=e[f+1],i=null,j;if((j=b+"::"+g,a.ATTRIBS.hasOwnProperty(j))||(j="*::"+g,a.ATTRIBS.hasOwnProperty(j)))i=a.ATTRIBS[j];if(i!==null)switch(i){case a.atype.NONE:break;case a.atype.SCRIPT:case a.atype.STYLE:h=null;break;case a.atype.ID:case a.atype.IDREF:case a.atype.IDREFS:case a.atype.GLOBAL_NAME:case a.atype.LOCAL_NAME:case a.atype.CLASSES:h=d?d(h):h;break;case a.atype.URI:h=c&amp;&amp;c(h);break;case a.atype.URI_FRAGMENT:h&amp;&amp;"#"===h.charAt(0)?(h=d?d(h):h,h&amp;&amp;(h="#"+h)):h=null;break;default:h=null}else h=null;e[f+1]=h}return e})(b,e);return e.join("")}function w(b){var c,d;return v({startDoc:function(a){c=[],d=!1},startTag:function(e,f,g){if(!d){if(!a.ELEMENTS.hasOwnProperty(e))return;var h=a.ELEMENTS[e];if(h&amp;a.eflags.FOLDABLE)return;if(h&amp;a.eflags.UNSAFE){d=!(h&amp;a.eflags.EMPTY);return}f=b(e,f);if(f){h&amp;a.eflags.EMPTY||c.push(e),g.push("&lt;",e);for(var i=0,j=f.length;i&lt;j;i+=2){var k=f[i],l=f[i+1];l!==null&amp;&amp;l!==void 0&amp;&amp;g.push(" ",k,'="',r(l),'"')}g.push("&gt;")}}},endTag:function(b,e){if(d)d=!1;else{if(!a.ELEMENTS.hasOwnProperty(b))return;var f=a.ELEMENTS[b];if(!(f&amp;(a.eflags.UNSAFE|a.eflags.EMPTY|a.eflags.FOLDABLE))){var g;if(f&amp;a.eflags.OPTIONAL_ENDTAG)for(g=c.length;--g&gt;=0;){var h=c[g];if(h===b)break;if(!(a.ELEMENTS[h]&amp;a.eflags.OPTIONAL_ENDTAG))return}else for(g=c.length;--g&gt;=0;)if(c[g]===b)break;if(g&lt;0)return;for(var i=c.length;--i&gt;g;){var h=c[i];a.ELEMENTS[h]&amp;a.eflags.OPTIONAL_ENDTAG||e.push("&lt;/",h,"&gt;")}c.length=g,e.push("&lt;/",b,"&gt;")}}},pcdata:function(a,b){d||b.push(a)},rcdata:function(a,b){d||b.push(a)},cdata:function(a,b){d||b.push(a)},endDoc:function(a){for(var b=c.length;--b&gt;=0;)a.push("&lt;/",c[b],"&gt;");c.length=0}})}function v(c){return function(d,e){d=String(d);var f=null,g=!1,h=[],j=void 0,l=void 0,m=void 0;c.startDoc&amp;&amp;c.startDoc(e);while(d){var n=d.match(g?t:u);d=d.substring(n[0].length);if(g){if(n[1]){var o=b(n[1]),p;if(n[2]){var q=n[3];switch(q.charCodeAt(0)){case 34:case 39:q=q.substring(1,q.length-1)}p=k(i(q))}else p=o;h.push(o,p)}else if(n[4]){l!==void 0&amp;&amp;(m?c.startTag&amp;&amp;c.startTag(j,h,e):c.endTag&amp;&amp;c.endTag(j,e));if(m&amp;&amp;l&amp;(a.eflags.CDATA|a.eflags.RCDATA)){f===null?f=b(d):f=f.substring(f.length-d.length);var r=f.indexOf("&lt;/"+j);r&lt;0&amp;&amp;(r=d.length),l&amp;a.eflags.CDATA?c.cdata&amp;&amp;c.cdata(d.substring(0,r),e):c.rcdata&amp;&amp;c.rcdata(s(d.substring(0,r)),e),d=d.substring(r)}j=l=m=void 0,h.length=0,g=!1}}else if(n[1])c.pcdata&amp;&amp;c.pcdata(n[0],e);else if(n[3])m=!n[2],g=!0,j=b(n[3]),l=a.ELEMENTS.hasOwnProperty(j)?a.ELEMENTS[j]:void 0;else if(n[4])c.pcdata&amp;&amp;c.pcdata(n[4],e);else if(n[5]&amp;&amp;c.pcdata)switch(n[5]){case"&lt;":c.pcdata("&amp;lt;",e);break;case"&gt;":c.pcdata("&amp;gt;",e);break;default:c.pcdata("&amp;amp;",e)}}c.endDoc&amp;&amp;c.endDoc(e)}}function s(a){return a.replace(m,"&amp;amp;$1").replace(n,"&amp;lt;").replace(o,"&amp;gt;")}function r(a){return a.replace(l,"&amp;amp;").replace(n,"&amp;lt;").replace(o,"&amp;gt;").replace(p,"&amp;#34;").replace(q,"&amp;#61;")}function k(a){return a.replace(j,g)}function i(a){return a.replace(h,"")}function g(a,b){return f(b)}function f(a){a=b(a);if(c.hasOwnProperty(a))return c[a];var f=a.match(d);if(f)return String.fromCharCode(parseInt(f[1],10));if(!!(f=a.match(e)))return String.fromCharCode(parseInt(f[1],16));return""}var b;"script"==="SCRIPT".toLowerCase()?b=function(a){return a.toLowerCase()}:b=function(a){return a.replace(/[A-Z]/g,function(a){return String.fromCharCode(a.charCodeAt(0)|32)})};var c={lt:"&lt;",gt:"&gt;",amp:"&amp;",nbsp:"240",quot:'"',apos:"'"},d=/^#(\d+)$/,e=/^#x([0-9A-Fa-f]+)$/,h=/\0/g,j=/&amp;(#\d+|#x[0-9A-Fa-f]+|\w+);/g,l=/&amp;/g,m=/&amp;([^a-z#]|#(?:[^0-9x]|x(?:[^0-9a-f]|$)|$)|$)/gi,n=/&lt;/g,o=/&gt;/g,p=/\"/g,q=/\=/g,t=new RegExp("^\\s*(?:(?:([a-z][a-z-]*)(\\s*=\\s*(\"[^\"]*\"|'[^']*'|(?=[a-z][a-z-]*\\s*=)|[^&gt;\"'\\s]*))?)|(/?&gt;)|[\\s\\S][^a-z\\s&gt;]*)","i"),u=new RegExp("^(?:&amp;(\\#[0-9]+|\\#[x][0-9a-f]+|\\w+);|&lt;!--[\\s\\S]*?--&gt;|&lt;!\\w[^&gt;]*&gt;|&lt;\\?[^&gt;*]*&gt;|&lt;(/)?([a-z][a-z0-9]*)|([^&lt;&amp;&gt;]+)|([&lt;&amp;&gt;]))","i");return{escapeAttrib:r,makeHtmlSanitizer:w,makeSaxParser:v,normalizeRCData:s,sanitize:x,unescapeEntities:k}}(html4),html_sanitize=html.sanitize

// stop here if we're not in TiddlyWiki
// XXX: is this the correct way of checking for TiddlyWiki?
if (!window.TiddlyWiki || !window.store || !store instanceof TiddlyWiki) {
	return;
}

var tiddlyspace = config.extensions.tiddlyspace;

var _subWikify = Wikifier.prototype.subWikify;

var cleanedTitle = 'This section has been cleaned of any potentially harmful code';

var replaceFunctions = {
	html: function(w) {
		var sanitizedHTML, spanEl;
		this.lookaheadRegExp.lastIndex = w.matchStart;
		var lookaheadMatch = this.lookaheadRegExp.exec(w.source);
		if(lookaheadMatch &amp;&amp; lookaheadMatch.index == w.matchStart) {
			sanitizedHTML = $.sanitize(lookaheadMatch[1]);
			spanEl = createTiddlyElement(w.output, 'span', null, 'sanitized');
			spanEl.innerHTML = sanitizedHTML;
			spanEl.setAttribute('title', cleanedTitle);
			w.nextMatch = this.lookaheadRegExp.lastIndex;
		}
	},
	customFormat: function(w) {
		switch(w.matchText) {
			case '@@':
				var e = createTiddlyElement(w.output, 'span');
				var styles = config.formatterHelpers.inlineCssHelper(w);
				if (styles.length === 0) {
					e.className = 'marked';
				}
				w.subWikifyTerm(e, /(@@)/mg);
				break;
			case '{{':
				var lookaheadRegExp = /\{\{[\s]*([\w]+[\s\w]*)[\s]*\{(\n?)/mg;
				lookaheadRegExp.lastIndex = w.matchStart;
				var lookaheadMatch = lookaheadRegExp.exec(w.source);
				if(lookaheadMatch) {
					w.nextMatch = lookaheadRegExp.lastIndex;
					e = createTiddlyElement(w.output,lookaheadMatch[2] == "\n" ? "div" : "span",null,lookaheadMatch[1]);
					w.subWikifyTerm(e,/(\}\}\})/mg);
				}
				break;
		}
	}
};

Wikifier.prototype.subWikify = function(output, terminator) {
	var tid = this.tiddler,
		spaceName = tiddlyspace.currentSpace.name,
		tidSpace, recipeName, stripped;
	try {
		recipeName = tid.fields['server.recipe'] ||
			tid.fields['server.workspace'];
		tidSpace = tiddlyspace.resolveSpaceName(recipeName);
		if (tidSpace !== spaceName) {
			// external tiddler, so replace dangerous formatters
			stripped = stripHTML(tid, this.formatter);
		}
	} catch(e) {
		// do nothing. There's no tiddler, so assume it's safe (?!?!?)
	}

	_subWikify.apply(this, arguments);

	if (stripped) {
		// change back to the original function
		unstripHTML(stripped, this.formatter);
	}
};

// replace potentially unsafe formatters with versions that strip bad HTML/CSS
var stripHTML = function(tid, formatter) {
	var popped = {}, _handler;
	for (var i = 0; i &lt; formatter.formatters.length; i++) {
		var f = formatter.formatters[i];
		if (replaceFunctions[f.name]) {
			_handler = f.handler;
			popped[f.name] = _handler;
			f.handler = replaceFunctions[f.name];
		}
	};

	return popped;
};

// put the original formatters back where they belong
var unstripHTML = function(stripped, formatter) {
	for (var i = 0; i &lt; formatter.formatters.length; i++) {
		var f = formatter.formatters[i];
		if (stripped[f.name]) {
			f.handler = stripped[f.name];
		}
	};
};

})(jQuery);
//}}}</pre>
</div>
<div title="missingIcon" server.title="missingIcon" server.page.revision="1521928" server.etag="&quot;system-images_public/missingIcon/1521928:24f4cafbba356c58b22048899e2a41e610ab62e1&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-images_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-images_public" server.permissions="read" server.content-type="image/png" modified="20131111192332" created="20131111192332" tags="excludeLists excludeSearch" _hash="6d8a31e0f98c2550de88c48110ecdceccb686a1e">
<pre>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</pre>
</div>
<div title="MarkupPreHead" server.title="MarkupPreHead" server.page.revision="2564011" server.etag="&quot;honly-666_public/MarkupPreHead/2564011:44a6b567ceed0094b563b9befce1d70d42566ea0&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20160923145540" created="20160906130629" tags="excludeLists" _hash="f871971e387398a9c0b40d9091ec22955184a153">
<pre>&lt;!--{{{--&gt;
&lt;link href="/bags/honly-666_public/tiddlers.atom" rel="alternate"
	type="application/atom+xml" title="honly-666's public feed" /&gt;
&lt;link rel="canonical" href="http://honly-666.tiddlyspace.com/" /&gt;
&lt;lt;!--}}}--&gt;</pre>
</div>
<div title="黄景瑜" server.title="黄景瑜" server.page.revision="2580042" server.etag="&quot;honly-666_public/%E9%BB%84%E6%99%AF%E7%91%9C/2580042:35c5aec10821aad0963bbbfb9c864239fcd1bf72&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20161102133127" created="20161102050509" tags="我的爱豆——Johnny" _hash="6f346de39ccc38ebd5be9943c37a72fae4aa9f71">
<pre>[[个人简介]]    [[电影]]     [[综艺]]    [[歌曲]]</pre>
</div>
<div title="第六次作业" server.title="第六次作业" server.page.revision="2580058" server.etag="&quot;honly-666_public/%E7%AC%AC%E5%85%AD%E6%AC%A1%E4%BD%9C%E4%B8%9A/2580058:3158cd5b8e8c18f858b01b44b767ce57c81ae4af&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20161102140325" created="20161102140325" tags="" _hash="879474bbf33a069f2a711cbbef73ccc0f70ef026">
<pre>选两所国外的学校进入主页，将相关的学院介绍、人员、及主要研究方向列出来</pre>
</div>
<div title="privateAndPublicIcon" server.title="privateAndPublicIcon" server.page.revision="1521887" server.etag="&quot;tiddlyspace/privateAndPublicIcon/1521887:4c3fb704e62f9079da1a1a458991c083b3ee3559&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/tiddlyspace" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="tiddlyspace" server.permissions="read" server.content-type="image/png" modified="20131111192334" created="20131111192334" tags="excludeLists excludeSearch" _cache-max-age="43200" _hash="5ae36775b0926a779ae5f5ec4f20d07cd3609b39">
<pre>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</pre>
</div>
<div title="BinaryTiddlersPlugin" server.title="BinaryTiddlersPlugin" server.page.revision="1521855" server.etag="&quot;system/BinaryTiddlersPlugin/1521855:7d419617a453890c7e6c50b6defbf544cf7be99e&quot;" modifier="FND" creator="FND" server.workspace="bags/system" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system" server.permissions="read" server.content-type="text/javascript" modified="20130924180405" created="20130924180405" tags="excludeLists excludeSearch systemConfig" _hash="bb40914e9b2e79bd868d4c824ef8e42e617f4309">
<pre>/***
|''Name''|BinaryTiddlersPlugin|
|''Description''|renders base64-encoded binary tiddlers as images or links|
|''Author''|FND|
|''Version''|0.3.2|
|''Status''|@@beta@@|
|''Source''|http://svn.tiddlywiki.org/Trunk/association/plugins/BinaryTiddlersPlugin.js|
|''License''|[[BSD|http://www.opensource.org/licenses/bsd-license.php]]|
|''CoreVersion''|2.5|
!Code
***/
//{{{
(function($) {

"use strict";

var ctfield = "server.content-type";

var plugin = config.extensions.BinaryTiddlersPlugin = {
	isWikiText: function(tiddler) {
		var ctype = tiddler.fields[ctfield];
		if(ctype) {
			if (ctype === 'text/x-tiddlywiki') {
				return true;
			}
			return !this.isBinary(tiddler) &amp;&amp; !this.isTextual(ctype);
		} else {
			return true;
		}
	},
	// NB: pseudo-binaries are considered non-binary here
	isBinary: function(tiddler) {
		var ctype = tiddler.fields[ctfield];
		return ctype ? !this.isTextual(ctype) : false;
	},
	isTextual: function(ctype) {
		return ctype.indexOf("text/") === 0
			|| this.endsWith(ctype, "+xml")
			|| ctype === 'application/json'
			|| ctype === 'application/javascript';
	},
	endsWith: function(str, suffix) {
		return str.length &gt;= suffix.length &amp;&amp;
			str.substr(str.length - suffix.length) === suffix;
	},
	isLink: function(tiddler) {
		return this.isBinary(tiddler) &amp;&amp; tiddler.text.indexOf("&lt;html&gt;") !== -1;
	}
};

// Disable edit for linked tiddlers (for now)
// This will be changed to a GET then PUT
config.commands.editTiddler.isEnabled = function(tiddler) {
    var existingTest = config.commands.editTiddler.isEnabled;
    if (existingTest) {
        return existingTest &amp;&amp; !plugin.isLink(tiddler);
    } else {
        return !plugin.isLink(tiddler);
    }
};

// hijack text viewer to add special handling for binary tiddlers
var _view = config.macros.view.views.wikified;
config.macros.view.views.wikified = function(value, place, params, wikifier,
		paramString, tiddler) {
	var ctype = tiddler.fields["server.content-type"];
	if(params[0] === "text" &amp;&amp; ctype &amp;&amp; ctype !== 'text/x-tiddlywiki' &amp;&amp;
			!tiddler.tags.contains("systemConfig") &amp;&amp; !plugin.isLink(tiddler)) {
		var el;
		if(plugin.isBinary(tiddler)) {
			var uri = "data:%0;base64,%1".format([ctype, tiddler.text]); // TODO: fallback for legacy browsers
			if(ctype.indexOf("image/") === 0) {
				el = $("&lt;img /&gt;").attr("alt", tiddler.title).attr("src", uri);
			} else {
				el = $("&lt;a /&gt;").attr("href", uri).text(tiddler.title);
			}
		} else {
			el = $("&lt;pre /&gt;").text(tiddler.text);
		}
		el.appendTo(place);
	} else {
		_view.apply(this, arguments);
	}
};

// hijack edit macro to disable editing of binary tiddlers' body
var _editHandler = config.macros.edit.handler;
config.macros.edit.handler = function(place, macroName, params, wikifier,
		paramString, tiddler) {
	if(params[0] === "text" &amp;&amp; plugin.isBinary(tiddler)) {
		return false;
	} else {
		_editHandler.apply(this, arguments);
	}
};

// hijack autoLinkWikiWords to ignore binary tiddlers
var _autoLink = Tiddler.prototype.autoLinkWikiWords;
Tiddler.prototype.autoLinkWikiWords = function() {
	return plugin.isWikiText(this) ? _autoLink.apply(this, arguments) : false;
};

}(jQuery));
//}}}</pre>
</div>
<div title="ImageMacroPlugin" server.title="ImageMacroPlugin" server.page.revision="1521897" server.etag="&quot;tiddlyspace/ImageMacroPlugin/1521897:a2b06c62a190043fa25b482940fe3828a4f66b24&quot;" modifier="jon" creator="jon" server.workspace="bags/tiddlyspace" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="tiddlyspace" server.permissions="read" server.content-type="text/javascript" modified="20131111192334" created="20131111192334" tags="excludeLists excludeSearch systemConfig" _hash="3f1696962a1dff3028ea1a4307d8b95c3b3ceb65">
<pre>/***
|''Name''|ImageMacroPlugin|
|''Version''|0.9.4|
|''Description''|Allows the rendering of svg images in a TiddlyWiki|
|''Author''|Osmosoft|
|''License''|[[BSD|http://www.opensource.org/licenses/bsd-license.php]]|
|''Notes''|Currently only works in modern browsers (not IE)|
|''Requires''|BinaryTiddlersPlugin|
!Usage
{{{&lt;&lt;image SVG&gt;&gt;}}} will render the text of the tiddler with title SVG as an SVG image (but not in ie where it will fail silently)
!!Parameters
width/height: specify width/height parameters
link: make the image link to a given location
tiddlyLink: link to a tiddler

!Notes
Binary tiddlers in TiddlyWeb when passed through the wikifier will be shown as images.
eg. {{{&lt;&lt;view text wikified&gt;&gt;}}} on a binary tiddler will show the image.
{{{&lt;&lt;view fieldname image&gt;&gt;}}}
will render the value of the tiddler field 'fieldname' as an image. This field can contain a tid
{{{&lt;&lt;image SiteIcon&gt;&gt;}}}
will create an image tag where the tiddler has content type beginning image and not ending +xml
will attempt to create svg object in other scenarios
{{{&lt;&lt;image /photos/x.jpg&gt;&gt;}}}
will create an image tag with src /photos/x.jpg as long as there is not a tiddler called /photos/x.jpg in 
which case it will render that tiddler as an image. Note for the case of svg files it will attempt to render as an svg if possible via the image
tag. It doesn't embed the svg in the dom for security reasons as svg code can contain javascript.
!Code
***/
//{{{
(function($) {

var macro = config.macros.image = {
	shim: "/bags/common/tiddlers/shim",
	ieVersion: config.browser.isIE ? parseInt(config.browser.ieVersion[1], 10) : false,
	svgns: "http://www.w3.org/2000/svg",
	xlinkns: "http://www.w3.org/1999/xlink", 
	svgAvailable: document.implementation.hasFeature("http://www.w3.org/TR/SVG11/feature#BasicStructure", "1.1"),
	_fixPrefix: 1,
	_external_cache: {},
	_image_tag_cache: {},
	_image_dimensions: {},
	locale: {
		badImage: "This image cannot be displayed."
	},
	handler: function(place, macroName, params, wikifier, paramString, tiddler){
		var imageSource = params[0];
		// collect named arguments
		var args = macro.getArguments(paramString, params);
		this.renderImage(place, imageSource, args);
	},
	init: function() {
		var startupImages = store.getTaggedTiddlers("systemImage");
		var place = $("&lt;div /&gt;").attr("id", "systemImageArea").appendTo("body").hide()[0];
		for(var i = 0; i &lt; startupImages.length; i++) {
			var image = startupImages[i];
			macro.renderImage(place, image.title, { idPrefix: "" });
		}
		var data = new Image();
		data.onload = function() {
			// note ie 8 only supports data uris up to 32k so cannot be relied on
			macro.supportsDataUris = this.width != 1 || this.height != 1 ? false : true;
			macro.supportsDataUris = macro.ieVersion &amp;&amp; macro.ieVersion &lt; 9 ? false : macro.supportsDataUris;
		};
		data.onerror = data.onload;
		data.src = "data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///ywAAAAAAQABAAACAUwAOw==";
	},
	refreshImage: function(src) {
		var elements = macro._image_tag_cache[src] ? macro._image_tag_cache[src] : [];
		if(macro._image_dimensions[src]) {
			macro._image_dimensions[src] = false;
		}
		for(var i = 0; i &lt; elements.length; i++) {
			var el = $(elements[i]);
			var newSrc = "%0?nocache=%1".format(src, Math.random());
			el.attr("src", newSrc); // force reload
		}
	},
	isBinaryImageType: function(contentType) {
		return (contentType &amp;&amp; contentType.indexOf("image") === 0 &amp;&amp;
			contentType.indexOf("+xml") != contentType.length - 4) ? true : false;
	},
	isImageTiddler: function(tiddler) {
		return macro.isSVGTiddler(tiddler) || macro.isBinaryImageTiddler(tiddler);
	},
	isSVGTiddler: function(tiddler) {
		var type = tiddler ? tiddler.fields['server.content-type'] : false;
		return type == "image/svg+xml";
	},
	isBinaryImageTiddler: function(tiddler) {
		return macro.isBinaryImageType(tiddler.fields['server.content-type']);
	},
	renderImage: function(place, imageSource, options) {
		var imageTiddler = store.getTiddler(imageSource);
		var container;
		var classes = ["image"];
		if(options.link) {
			classes = classes.concat(["imageLink", "externalLink"]);
			container = $("&lt;a /&gt;").attr("href", options.link).appendTo(place)[0];
		} else if(options.tiddlyLink) {
			classes.push("imageLink");
			container = createTiddlyLink(place, options.tiddlyLink, false);
		} else {
			container = $("&lt;span /&gt;").appendTo(place)[0];
		}
		$(container).addClass(classes.join(" "));

		options = options ? options : {};
		if(imageTiddler &amp;&amp; macro.isBinaryImageTiddler(imageTiddler)) { // handle the case where we have an image url
			return macro._renderBinaryImageTiddler(container, imageTiddler, options);
		} else if(imageTiddler){ // handle the case where we have a tiddler
			return macro._renderSVGTiddler(container, imageTiddler, options);
		} else { // we have a string representing a url
			return macro._renderBinaryImageUrl(container, imageSource, options);
		}
	},
	_renderAlternateText: function(container, options) {
		var img;
		var src = options.src || "";
		if(options.width &amp;&amp; options.height) {
			img = $("&lt;img /&gt;").attr("src", src).addClass("svgImageText").attr("width", options.width).
				attr("height", options.height).appendTo(container);
		}
		var alt = options.alt;
		if(img &amp;&amp; alt) {
			img.attr("alt", alt).attr("title", alt);
		} else if(alt) {
			$(container).addClass("svgImageText").text(alt);
		}
		macro._image_tag_cache[src] = img;
	},
	_renderSVGTiddler: function(place, tiddler, options) {
		if(!options) {
			options = {};
		}
		merge(options, { tiddler: tiddler, fix: true});

		if(macro.svgAvailable) {
			this._importSVG(place, options); // display the svg
		} else if(options.altImage) {
			var image = options.altImage;
			delete options.altImage;
			this._renderBinaryImageUrl(place, image, options);
		} else {
			this._renderAlternateText(place, options); // instead of showing the image show the alternate text.
		}
	},
	_renderBinaryImageTiddler: function(place, tiddler, options) {
		var resourceURI;
		var fields = tiddler.fields;
		if(fields["server.type"] == "tiddlyweb") { // construct an accurate url for the resource
			resourceURI = "%0/%1/tiddlers/%2".format(config.defaultCustomFields["server.host"],
				fields["server.workspace"], encodeURI(fields["server.title"]));
		} else { // guess the url for the resource
			resourceURI = tiddler.title;
		}
		var ctype = fields["server.content-type"] || tiddler.type;
		var text = tiddler.text;
		if(macro.supportsDataUris &amp;&amp; ctype &amp;&amp; text.indexOf("&lt;html") == -1) {
			var uri = "data:%0;base64,%1".format(ctype, text);
			options.src = resourceURI;
			return macro._renderBinaryImageUrl(place, uri, options);
		} else if(options.src) {
			return macro._renderBinaryImageUrl(place, options.src, options);
		} else {
			return macro._renderBinaryImageUrl(place, resourceURI, options);
		}
	},
	_renderImageTag: function(container, src, width, height, options) {
		var img;
		img = $("&lt;img /&gt;").appendTo(container);
		if(height) {
			img.attr("height", height);
		}
		if(width) {
			img.attr("width", width);
		}
		if(macro.ieVersion &amp;&amp; macro.ieVersion &lt; 7 &amp;&amp; macro.shim &amp;&amp; options.ie6png) {
			$(img).css({width: userW, height: userH,
					filter: "progid:DXImageTransform.Microsoft.AlphaImageLoader(src='%0', sizingMethod='scale')".format(src)
				}).attr("src", macro.shim);
		} else {
			img.attr("src", src);
		}
		if(!macro._image_tag_cache[options.srcUrl]) {
			macro._image_tag_cache[options.srcUrl] = [];
		}
		img = $(img).addClass(options.imageClass)[0];
		macro._image_tag_cache[options.srcUrl].push(img);
		return img;
	},
	_getDimensions: function(realDimensions, reqDimensions, preserve) {
		var w = realDimensions.width;
		var h = realDimensions.height;
		var reqh = reqDimensions.height;
		var reqw = reqDimensions.width;
		var finalw = w, finalh = h;
		var ratiow = reqw / w, ratioh = reqh / h;
		var scaledw = ratioh * w;
		var scaledh = ratiow * h;
		if(!reqw &amp;&amp; reqh) {
			finalw = scaledw;
			finalh = reqh;
		} else if(reqw &amp;&amp; !reqh) {
			finalw = reqw;
			finalh = scaledh;
		} else if(reqh &amp;&amp; reqw) {
			var preserveWidth = w &gt; h ? true : false;
			if(preserve) {
				if(preserveWidth &amp;&amp; scaledh &lt; reqh) {
					finalh = scaledh;
					finalw = reqw;
				} else {
					finalh = reqh;
					finalw = scaledw;
				}
			} else {
				finalw = reqw;
				finalh = reqh;
			}
		}
		return { width: parseInt(finalw, 10), height: parseInt(finalh, 10) };
	},
	_renderBinaryImageUrl: function(container, src, options) {
		var srcUrl = options.src ? options.src : src;
		srcUrl = srcUrl.indexOf("/") === -1 ? "/%0".format(srcUrl) : srcUrl; // for IE. 
		var image_dimensions = macro._image_dimensions[srcUrl];
		var image = new Image(); // due to weird scaling issues where you use just a width or just a height
		var createImageTag = function(dimensions, error) {
			if(error) {
				var altImage = options.altImage;
				if(altImage) {
					delete options.altImage;
					macro._renderBinaryImageUrl(container, altImage, options);
				} else {
					options.src = src;
					macro._renderAlternateText(container, options);
				}
			} else {
				var dim = macro._getDimensions(dimensions, { 
					width: options.width, height: options.height }, options.preserveAspectRatio);
				options.srcUrl = srcUrl;
				macro._renderImageTag(container, src, dim.width, dim.height, options);
			}
		};

		if(!image_dimensions) {
			image.onload = function() {
				var dimensions = { width: image.width, height: image.height};
				macro._image_dimensions[srcUrl] = dimensions;
				createImageTag(dimensions);
			};
			image.onerror = function() {
				createImageTag(null, true);
			};
			image.src = src;
		} else {
			createImageTag(image_dimensions);
		}
	},
	_generateIdPrefix: function(){
		return "twsvgfix_" + (this._fixPrefix++).toString() + "_";
	},
	_fixSVG: function(childNodes, idPrefix) {
		var urlPattern = /url\(\#([^\)]*)\)*/ig;
		var fixes = [
		{ attr: "id", pattern: /^(.*)$/ig },
		{ attr: "href", namespace: macro.xlinkns, pattern: /^#(.*)$/ig }
		];
		var url_fixes = ["filter", "fill", "mask", "stroke", "style"];
		for(var i = 0; i &lt; url_fixes.length; i++) {
			fixes.push({ attr: url_fixes[i], pattern: urlPattern });
		}
		for(var t = 0; t &lt; childNodes.length; t++) {
			var node = childNodes[t];
			for(var a = 0; a &lt; fixes.length; a++) {
				var fix = fixes[a];
				var attr = fix.attr;
				var ns = fix.namespace || "";
				if(node.hasAttributeNS &amp;&amp; node.hasAttributeNS(ns, attr)) {
					var v = node.getAttributeNS(ns, attr);
					fix.pattern.lastIndex = 0;
					var match = fix.pattern.exec(v);
					if(match) {
						// Make sure replacement string doesn't contain any single dollar signs
						var toReplace = match[1];
						if(toReplace.indexOf(idPrefix) !== 0 &amp;&amp; toReplace.indexOf("twglobal_") !== 0) {
							var replacement = (idPrefix + toReplace).replace("$", "$$$$"); 
							v = v.replace(match[1], replacement);
						}
						node.setAttributeNS(ns, attr,v);
					}
				}
			}
			var children = node.childNodes;
			if(children.length &gt; 0) {
				this._fixSVG(children, idPrefix);
			}
		}
	},
	_importSVG: function(place, options){
		options = options ? options : {};
		var svgDoc, tiddlerText = options.tiddler.text;
		if (window.DOMParser) {
			svgDoc = new DOMParser().parseFromString(tiddlerText, "application/xml").documentElement;
			var idPrefix = options.idPrefix || this._generateIdPrefix();
			this._fixSVG([svgDoc], idPrefix);
			var el = document.importNode(svgDoc, true);
			var svgHolder = document.createElementNS(macro.svgns,"svg");
			var width = options.width;
			var height = options.height;
			if(width || height) {
				if(width &amp;&amp; height) { // set view box of containing svg element based on the svg viewbox and width and height.
					var viewBox = el.getAttribute("viewBox");
					var topLeft = "0 0";
					if(viewBox) {
						topLeft = viewBox.replace(/([0-9]*) +([0-9]*) +([0-9]*) +([0-9]*) */gi,"$1 $2");
					}
					svgHolder.setAttributeNS(macro.svgns, "viewBox", "0 0 %0 %1".format(width, height));
				} else {
					if(!width) {
						width = el.getAttribute("width");
					}
					if(!height) {
						height = el.getAttribute("height");
					}
				}
				svgHolder.setAttribute("width", width);
				svgHolder.setAttribute("height", height);

				el.setAttribute("width", "100%");
				el.setAttribute("height", "100%");
				svgHolder.setAttribute("class", "svgImage svgIcon %0".format(options.imageClass || ""));
				svgHolder.appendChild(el);
				place.appendChild(svgHolder);
			}
			else {
				var existing = el.className ? el.className.baseVal : "";
				el.setAttribute("class","svgImage %0".format(existing));
				place.appendChild(el);
			}
			// if a tiddler attribute is set this is read as a link
			$("[tiddler], [tiddlyLink]", place).attr("refresh", "link").click(function(ev) {
				var tiddler = $(ev.target).attr("tiddlyLink");
				if(tiddler) {
					story.displayTiddler(ev.target, tiddler);
				}
			});
		}
	},
	getArguments: function(paramString, params) {
		var args = paramString.parseParams("name", null, true, false, true)[0];
		var options = {};
		for(var id in args) {
			if(true) {
				var p = args[id];
				if(id == "def") {
					options[id] = p;
				} else {
					options[id] = p[0];
				}
			}
		}
		var width = isNaN(params[1]) ? false : parseInt(params[1], 10);
		var height = isNaN(params[2]) ? false : parseInt(params[2], 10);

		options.width = macro.lookupArgument(options, "width", width);
		options.height = macro.lookupArgument(options, "height", height);
		options.preserveAspectRatio = args.preserveAspectRatio &amp;&amp; 
			args.preserveAspectRatio[0] == "yes" ? true : false;
		options.tiddlyLink = macro.lookupArgument(options, "tiddlyLink", false);
		options.link = macro.lookupArgument(options, "link", false);
		return options;
	},
	lookupArgument: function(args, id, ifEmpty) {
		return args[id] ? args[id] : ifEmpty;
	}
};

// update views
var _oldwikifiedview = config.macros.view.views.wikified;
// update wikifier to check tiddler type before rendering
merge(config.macros.view.views, {
	wikified: function(value, place, params, wikifier, paramString, tiddler) {
		if(macro.isImageTiddler(tiddler) &amp;&amp; params[0] == "text") {
			var newplace = $("&lt;div /&gt;").addClass("wikifiedImage").appendTo(place)[0];
			macro.renderImage(newplace, tiddler.title, { alt: macro.locale.badImage });
		} else {
			_oldwikifiedview.apply(this, arguments);
		}
	},
	image: function(value, place, params, wikifier, paramString, tiddler) {
		// a field can point to another tiddler whereas text is the current tiddler.
		var title = params[0] == "text" ? tiddler.title : value;
		var args = macro.getArguments(paramString, params);
		macro.renderImage(place, title, args);
	}
});
config.shadowTiddlers.StyleSheetImageMacro = [".wikifiedImage svg, .wikifiedImage .image { width: 80%; }",
	".svgImageText { background-color:[[ColorPalette::Error]]; color:#ddd; display: inline-block; }",
	"span.svgImageText { display: inline-block; overflow: hidden; }"
].join("");
store.addNotification("StyleSheetImageMacro", refreshStyles);

})(jQuery);
//}}}</pre>
</div>
<div title="ColorPalette" server.title="ColorPalette" server.page.revision="2579000" server.etag="&quot;honly-666_public/ColorPalette/2579000:9ae5e3a2e6b9f966dd3cc79efcdc528c08460ef3&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20161030065513" created="20160906130629" tags="excludeLists excludeSearch" _hash="22f32bd6bf5bdbaa6935eeb2accf77033d9080d0">
<pre>/*{{{*/
Background: #000000
Foreground: #1d0622
PrimaryPale: #fdfafe
PrimaryLight: #87ceeb
PrimaryMid: #87ceeb
PrimaryDark: #524a53
SecondaryPale: #fafdfe
SecondaryLight: #c4e4ed
SecondaryMid: #489eb6
SecondaryDark: #4a5153
TertiaryPale: #fefcfa
TertiaryLight: #edd6c4
TertiaryMid: #b67a48
TertiaryDark: #534e4a
Error: #f88
ColorPaletteParameters: HSL([290|83], [0.67|0.53|0.43|0.06],[0.31|0.5|0.85|0.99])
/*}}}*/</pre>
</div>
<div title="colorScheme" server.title="colorScheme" server.page.revision="1521879" server.etag="&quot;system-info_public/colorScheme/1521879:f681d18398e0d38db2118e9870650b0d662bb29e&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-info_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-info_public" server.permissions="read" server.content-type="" modified="20131111192330" created="20131111192330" tags="excludeLists excludeSearch" _hash="bfe2408ed9b5cebf918768cae9c9e15bdb8f3309">
<pre>Unless you're delighted with the default theme you can make some quick changes by generating a new random color palette, hit this button to cycle through some alternatives.

&lt;&lt;RandomColorPaletteButton saturation_pale:0.67 saturation_light:0.53
saturation_mid:0.43 saturation_dark:0.06 pale:0.99 light:0.85 mid:0.5 dark:0.31&gt;&gt;

You can also change the look and feel completely by installing a new theme. To do this, find one you like in the @themes space, note down the name, and include it in this space by going to the space menu. You can reach the space menu by clicking on the blue and pink circle at the top-right of the page and chooshing "THIS SPACE". Here are a few to check out:
* @pip
* @caspian-ii
* @basalt
* @simplicity
* @cheesecake
* @jelly-doughnut

(//Note that if you are using a custom TiddlySpace install, these themes may not be present.//)</pre>
</div>
<div title="搜索引擎从入门到精通" server.title="搜索引擎从入门到精通" server.page.revision="2580038" server.etag="&quot;honly-666_public/%E6%90%9C%E7%B4%A2%E5%BC%95%E6%93%8E%E4%BB%8E%E5%85%A5%E9%97%A8%E5%88%B0%E7%B2%BE%E9%80%9A/2580038:3433cce4f5d44e465ea575e0e545070f7b8e4a59&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20161102132357" created="20161102044811" tags="" _hash="9a475f77cfda005d49d526d05efaa688a11ba02c">
<pre>


http://wenku.baidu.com/view/5bad4dd7240c844769eaeec8.html</pre>
</div>
<div title="close.svg" server.title="close.svg" server.page.revision="1521888" server.etag="&quot;tiddlyspace/close.svg/1521888:9d4be534872b27c079aa9127358874054bd64556&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/tiddlyspace" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="tiddlyspace" server.permissions="read" server.content-type="image/svg+xml" modified="20131111192334" created="20131111192334" tags="excludeLists excludeSearch" _hash="b21fe0ea0a8dba52788155f5ed2188b45210d076">
<pre>&lt;?xml version="1.0" encoding="UTF-8" standalone="no"?&gt;
&lt;!-- Created with Inkscape (http://www.inkscape.org/) --&gt;

&lt;svg
   xmlns:dc="http://purl.org/dc/elements/1.1/"
   xmlns:cc="http://creativecommons.org/ns#"
   xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
   xmlns:svg="http://www.w3.org/2000/svg"
   xmlns="http://www.w3.org/2000/svg"
   xmlns:xlink="http://www.w3.org/1999/xlink"
   version="1.1"
   width="14pt"
   height="14pt"
   viewBox="918 510 14 14"
   id="svg3070"&gt;
  &lt;metadata
     id="metadata3089"&gt;
    &lt;rdf:RDF&gt;
      &lt;cc:Work
         rdf:about=""&gt;
        &lt;dc:format&gt;image/svg+xml&lt;/dc:format&gt;
        &lt;dc:type
           rdf:resource="http://purl.org/dc/dcmitype/StillImage" /&gt;
        &lt;dc:title&gt;&lt;/dc:title&gt;
      &lt;/cc:Work&gt;
    &lt;/rdf:RDF&gt;
  &lt;/metadata&gt;
  &lt;defs
     id="defs3072"&gt;
    &lt;radialGradient
       cx="0"
       cy="0"
       r="1"
       id="Gradient"
       gradientUnits="userSpaceOnUse"&gt;
      &lt;stop
         id="stop3075"
         style="stop-color:#ffffff;stop-opacity:1"
         offset="0" /&gt;
      &lt;stop
         id="stop3077"
         style="stop-color:#2b2b2b;stop-opacity:1"
         offset="1" /&gt;
    &lt;/radialGradient&gt;
    &lt;radialGradient
       id="Obj_Gradient"
       xlink:href="#Gradient"
       gradientTransform="matrix(11.473944,0,0,11.473944,922.3752,513.7837)" /&gt;
  &lt;/defs&gt;
  &lt;g
     id="g3080"
     style="fill:none;stroke:none"&gt;
    &lt;g
       id="g3082"&gt;
      &lt;path
         d="m 929.6952,512.9018 c -2.5384,-2.53843 -6.654,-2.53843 -9.1924,0 -2.5384,2.5384 -2.5384,6.654 0,9.19238 2.5384,2.53839 6.654,2.53839 9.1924,0 2.5384,-2.53838 2.5384,-6.65398 0,-9.19238 m -4.5962,2.8407 2.07733,-2.07734 1.75547,1.75549 -2.0773,2.07735 2.0773,2.07732 -1.75547,1.75548 -2.07733,-2.07732 -2.07733,2.07732 -1.75547,-1.75548 2.0773,-2.07732 -2.0773,-2.07735 1.75547,-1.75549 z"
         id="path3084"
         style="fill:url(#Obj_Gradient)" /&gt;
      &lt;path
         d="m 927.61447,515.38354 a 4.51205,4.2590378 0 1 1 -9.0241,0 4.51205,4.2590378 0 1 1 9.0241,0 z"
         transform="matrix(1.0218069,0,0,1.0462046,-18.063694,-21.648443)"
         id="path2394"
         style="fill:#000000;fill-opacity:0;fill-rule:evenodd;stroke:none;stroke-width:5;marker:none;visibility:visible;display:inline;overflow:visible;enable-background:accumulate" /&gt;
    &lt;/g&gt;
  &lt;/g&gt;
&lt;/svg&gt;</pre>
</div>
<div title="publicIcon" server.title="publicIcon" server.page.revision="1521911" server.etag="&quot;tiddlyspace/publicIcon/1521911:e3cd202d6631d11490a2d60784d52e6f504a11a3&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/tiddlyspace" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="tiddlyspace" server.permissions="read" server.content-type="image/png" modified="20131111192334" created="20131111192334" tags="excludeLists excludeSearch" _cache-max-age="43200" _hash="8e44a24b6d966bfdda2a6cfeb9f141ac3a3892a5">
<pre>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</pre>
</div>
<div title="backstage.svg" server.title="backstage.svg" server.page.revision="1521885" server.etag="&quot;tiddlyspace/backstage.svg/1521885:e5d0376a68bc16e0cf8dc12ee5c2ea83a9af426e&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/tiddlyspace" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="tiddlyspace" server.permissions="read" server.content-type="image/svg+xml" modified="20131111192334" created="20131111192334" tags="excludeLists excludeSearch" _hash="c1cd42462c1b10a4e77a891408b9c2a24da3b2e6">
<pre>&lt;svg xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#" xmlns="http://www.w3.org/2000/svg" height="100%" width="100%" version="1.1" xmlns:cc="http://creativecommons.org/ns#" xmlns:dc="http://purl.org/dc/elements/1.1/" viewBox="0 0 40 40"&gt;&lt;metadata&gt;&lt;rdf:RDF&gt;&lt;cc:Work rdf:about=""&gt;&lt;dc:format&gt;image/svg+xml&lt;/dc:format&gt;&lt;dc:type rdf:resource="http://purl.org/dc/dcmitype/StillImage"/&gt;&lt;dc:title/&gt;&lt;/cc:Work&gt;&lt;/rdf:RDF&gt;&lt;/metadata&gt;&lt;defs&gt;&lt;linearGradient id="lG3826" x1="7.0996" gradientUnits="userSpaceOnUse" y1="18.829" gradientTransform="matrix(1.5858347,0,0,1.8078238,1098.1851,351.13716)" x2="1.5461" y2="-0.95166"&gt;&lt;stop stop-color="#000" offset="0"/&gt;&lt;stop stop-color="#9c9b99" offset="1"/&gt;&lt;/linearGradient&gt;&lt;linearGradient id="lG3828" y2="372.44" gradientUnits="userSpaceOnUse" y1="375.7" x2="1111.7" x1="1097.7"&gt;&lt;stop style="stop-color:#ac9393;" offset="0"/&gt;&lt;stop style="stop-color:#c8b7b7;" offset="1"/&gt;&lt;/linearGradient&gt;&lt;/defs&gt;&lt;g transform="translate(-1080.9375,-357.3329)"&gt;&lt;path style="stroke-width:0;stroke-miterlimit:4;fill:url(#lG3826);" d="m1080.9,357.32,39.996-0.0426-0.01,40.008c-15.507-25.519-15.36-25.95-39.988-39.965z"/&gt;&lt;path style="stroke-dashoffset:0;stroke:#7aa3be;stroke-linecap:round;stroke-miterlimit:4;stroke-width:1.49999988;fill:#c1e6fd;" d="m1091.9,363.55c6.5716-6.4925,16.576-7.3925,23.147-0.90003,6.5717,6.4925,6.5717,17.019,0,23.511-4.4424-8.6113-12.288-15.713-23.147-22.611z"/&gt;&lt;path style="stroke-dashoffset:0;stroke:#ce81b0;stroke-linecap:round;stroke-miterlimit:4;stroke-width:1.5;fill:#f4c4e2;" d="m1110.2,367.62c3.217,3.2168,3.217,8.4323,0,11.649-3.8194-4.2357-8.3307-8.1824-11.649-11.649,3.217-3.2168,8.4325-3.2168,11.649-0.00002z"/&gt;&lt;path style="stroke-linejoin:bevel;stroke:#000000;stroke-linecap:round;stroke-dasharray:none;stroke-miterlimit:4;stroke-width:0.80000001;fill:url(#lG3828);" d="m1081,357.34c18.79,6.4752,32.53,16.56,39.894,39.892-11.19-17.028-14.878-19.19-27.352-14.96,6.2984-12.098,3.9371-13.19-12.542-24.932z"/&gt;&lt;/g&gt;&lt;/svg&gt;</pre>
</div>
<div title="第3次翻译目标和方法" server.title="第3次翻译目标和方法" server.page.revision="2579922" server.etag="&quot;honly-666_public/%E7%AC%AC3%E6%AC%A1%E7%BF%BB%E8%AF%91%E7%9B%AE%E6%A0%87%E5%92%8C%E6%96%B9%E6%B3%95/2579922:138b0eb1828437dc69eddcc63517689786825f0f&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20161102045206" created="20160924142608" tags="special" _hash="be0dd40a56604b2998fa1d6cd6b48bb2bb2814ba">
<pre>这本书的目的是提供一个对信息管理的充分理解，在全面理解的基础上我们可以按照DavidKolb的观点，即知识可以有两个基础范围（抽象与具体，反思与实验），并且学习是一个在它们之间不断循环的过程。根据这些，我们的目标有：
一、抽象理解：这意味着要解释一些基本的术语，这将在每一章节中从不同的视角对信息的概念进行解释，从一个形而上的概念及其主要为信息管理方法含义的探讨。
二、实验：我们挑战读者，通过提供信息管理方法和技术在信息的管理中描述并应用这些概念。
三、具体的经验：我们演示抽象哲学观念的适用性及利用相关信息管理的方法和技术来解决具体的日常问题。在这本书的实例中，读者必须通过提供的实际例子和任务使用现有的软件工具分析具体问题。
四、反思：我们以一种批判性的思考方式来挑战读者在任务中阅读和尝试的东西。我们邀请他们发现他们将来学习生涯中的挑战。一个好的方法是通过小组的努力，因此，明智的读者会为了讨论他们所读的和所做的而安排一个通知平台。这可以很容易地完成，并且在学习理解通知挑战的过程中，避免误导和无意义是第一步，并且共同通过电子有以下几个收获手段创造语用知识，谷歌在这方面提供了很好的机会。
     通过读了这本书，读者会

1.理解和识别不同的信息管理的方法和它们的优缺点，以及不同方法所带来的附加价值。
2.学会创造简单的商业和现实管理模型来具体说明企业管理和公共政策执行的信息需求。
3.理解的关键问题是翻译抽象信息需要相关的信息收集、信息加工处理和有代表性的程序。
4.理解一些在组织中的复杂的管理信息和使用信息系统所遇到的挑战是最重要的
5.开发反思和分析信息的能力来推出消息通知、信息管理和信息技术的使用。这些功能将在你的整个职业生涯都有价值,也将使你对未来批判性的诊断成为可能，还可以获得任何新的瞬态信息技术的机会。 因此我致力于讨论信息管理作为一个人与生俱来的能力,而不是它的支持性技术。
       这些经验教训、洞察力和技能对任何本科工商管理、公共管理、社会科学和经济学
层次的学生来说都是很关键的。不过这本书也可能在信息基础和信息传递方面为任何一个对此感兴趣的人服务。


</pre>
</div>
<div title="editTiddlerReadOnly" server.title="editTiddlerReadOnly" server.page.revision="1521933" server.etag="&quot;system-images_public/editTiddlerReadOnly/1521933:e64a97f9aa2eaf681a4d210e04047aa20c9b767c&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-images_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-images_public" server.permissions="read" server.content-type="image/svg+xml" modified="20131111192332" created="20131111192332" tags="excludeLists excludeSearch" _hash="24d0766e948d10eb5e220d57a8c0d16a194ebe1f">
<pre>&lt;svg xmlns="http://www.w3.org/2000/svg" xmlns:xl="http://www.w3.org/1999/xlink" version="1.1" viewBox="506 234 68 36" width="30" height="30"&gt;&lt;metadata xmlns:dc="http://purl.org/dc/elements/1.1/"&gt;&lt;dc:date&gt;2010-09-16 14:51Z&lt;/dc:date&gt;&lt;!-- Produced by OmniGraffle Professional 5.2.3 --&gt;&lt;/metadata&gt;&lt;defs&gt;&lt;/defs&gt;&lt;g stroke="none" stroke-opacity="1" stroke-dasharray="none" fill="none" fill-opacity="1"&gt;&lt;rect width="1118" height="783"/&gt;&lt;g&gt;&lt;path d="M 538.68195 244.31807 C 540.43927 246.07547 540.43927 248.9247 538.68195 250.68204 C 536.92456 252.4394 534.07532 252.4394 532.318 250.68204 C 530.5606 248.9247 530.5606 246.07547 532.318 244.31807 C 534.07532 242.56075 536.92456 242.56075 538.68195 244.31807 M 511.12607 257.99356 C 511.26108 258.13019 511.39728 258.26608 511.53473 258.40121 C 527.2556 273.86606 552.74414 273.86606 568.46515 258.40121 C 568.60248 258.26617 568.73853 258.13037 568.87354 257.9938 C 568.8736 257.99374 568.8736 257.99371 568.8736 257.99362 C 568.87366 257.99371 568.87366 257.9938 568.87372 257.9939 C 570.72504 256.12051 572.35046 254.11153 573.74994 252 C 573.74994 251.99997 573.74994 251.99994 573.74994 251.99992 C 572.35046 249.8884 570.72504 247.87938 568.87372 246.00606 C 568.87366 246.00613 568.87366 246.00621 568.8736 246.00627 C 568.73865 245.86966 568.60254 245.73383 568.46515 245.5987 C 552.74414 230.13387 527.2556 230.13387 511.53473 245.5987 C 511.39728 245.73383 511.26108 245.86974 511.12613 246.00635 C 511.126 246.00624 511.126 246.00616 511.12595 246.00606 C 509.2748 247.87938 507.64954 249.88837 506.24994 251.9998 L 506.24994 251.99983 C 506.24994 251.9999 506.25 251.99992 506.25 251.99997 C 506.25 252 506.24994 252.00005 506.24994 252.00009 L 506.24994 252.00012 C 507.64954 254.11157 509.2748 256.12051 511.12595 257.9939 C 511.126 257.99377 511.126 257.99365 511.12607 257.99359 Z M 515.44916 252 C 515.8548 251.55469 516.27502 251.11778 516.71014 250.68985 C 522.16632 245.32257 529.06055 242.23206 536.17273 241.41824 C 534.6662 241.96199 533.2525 242.83762 532.04498 244.04512 C 527.65155 248.43852 527.65155 255.56163 532.04498 259.95502 C 533.2522 261.16226 534.6656 262.03778 536.17175 262.58154 C 529.05988 261.76761 522.16608 258.6771 516.71014 253.31009 C 516.2751 252.88219 515.85486 252.44528 515.44922 252 Z M 564.55054 251.99995 C 564.14502 252.44525 563.7248 252.88217 563.28973 253.31009 C 557.83368 258.67712 550.93988 261.76764 543.828 262.58157 C 545.33423 262.03781 546.74756 261.1623 547.9549 259.95502 C 552.34833 255.56163 552.34833 248.43852 547.9549 244.04512 C 546.74744 242.83765 545.33374 241.96202 543.82715 241.41824 C 550.9394 242.23206 557.83356 245.3226 563.28973 250.68985 C 563.7248 251.11775 564.14502 251.55467 564.55054 251.99995 Z M 568.8736 257.99362 C 570.7249 256.12033 572.35028 254.11139 573.74988 252.00002" fill="black" class="glyph"/&gt;&lt;/g&gt;&lt;/g&gt;&lt;/svg&gt;</pre>
</div>
<div title="第2次翻译作业——17、18" server.title="第2次翻译作业——17、18" server.page.revision="2579882" server.etag="&quot;honly-666_public/%E7%AC%AC2%E6%AC%A1%E7%BF%BB%E8%AF%91%E4%BD%9C%E4%B8%9A%E2%80%94%E2%80%9417%E3%80%8118/2579882:69b8bb9c7043c8c5b68a822a42559d497452f9ba&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20161102043540" created="20160923160512" tags="" _hash="37ca911ab9c09b620cf18774d56bd4719c46ab20">
<pre>特征码
一、HTML源码实例区分字体、颜色和大小
二、http替代了https
三、斜线在URL（用户需求语言）中的数目
四 、URL后缀：一些含有更多不良内容的编纂
五、垃圾邮件的程序员经常试图隐藏重定向，编纂功能或内容
六、脚本生成代码从用户操作HTML注入和跨站点脚本识别有一定块的HTML代码
七、关键词在“关键词”和“描述”的元标签数
八、没有ALT属性的图像
九、垃圾邮件的页面往往有一个以上的平均大小的字节
十、垃圾邮件页面往往有更多字节的代码大小相同
十一、垃圾邮件网页代码字符串往往更长
十二、元标签重定向模式
十三、垃圾邮件的网页图像比较少，因为制造商不重视它
十四、ALT属性可以用于堆砌关键词
十五、不太有效的启发式：大量的隐藏文本，使用重定向，脚本功能，动态函数，活动等

内容特征
一、页面中的单词数
二、页面标题中的单词数
三、单词的平均长度
四、锚文本量
五、可见含量分数
六、课压缩性
七、从全球流行的词绘制的页面的分数：垃圾邮件的网页被发现从一个集中的词汇，丢失的文章和连接很少在查询中发现
八、只包含标点符号的链接
九、只包含数字的链接
十、只包含一个统一建模语言的链接
十一、只包含一个空链的链接
十二、页面上的链接数与站点上的外链接平均数的关系
十三、与页面内容相比链接的百分比


语义层

语义学是研究迹象(符号)世界与事物世界之间的联系（赖德，2005）。
一则消息需要被接收者理解才是有意义的，这条消息要被接收者集成到知识才能成为信息。如果这则消息不可以被集成，那么它将不能被人们理解。太少的特征和深度将无法充分地告知接收者，因此这则消息将无法被接受者完全理解。相反，太多的特征和深度会淹没接受者，消息也将无法被理解。网页的语义属性只能在有限的程度上被自动评价。有一些方法，可以衡量一个网页的连贯性以及其他基于语言的特性。算法只能在一定程度上可以区分一个有用的网站是否为恶意创建的页面做一些推断。
       操作型定义1：信息浪费对接收者没有任何意义。
       操作型定义2：信息浪费有太多或太少的细节来为用户服务。
       操作型定义3：信息浪费的目的在于误导或向用户发送垃圾邮件。


</pre>
</div>
<div title="TiddlySpaceFollowingPlugin" server.title="TiddlySpaceFollowingPlugin" server.page.revision="1521864" server.etag="&quot;system-plugins_public/TiddlySpaceFollowingPlugin/1521864:ed483e3b4707d7d73319ed8618b65f031151b11c&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-plugins_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-plugins_public" server.permissions="read" server.content-type="text/javascript" modified="20131111192330" created="20131111192330" tags="excludeLists excludeSearch systemConfig" _hash="65a4f81f24d076e5c3fc66d2ff037c994c514bcd">
<pre>/***
|''Name''|TiddlySpaceFollowingPlugin|
|''Version''|0.7.1|
|''Description''|Provides a following macro|
|''Author''|Jon Robson|
|''Requires''|TiddlySpaceConfig TiddlySpaceTiddlerIconsPlugin ErrorHandler|
|''License''|[[BSD|http://www.opensource.org/licenses/bsd-license.php]]|
!Usage
Tag a tiddler with "follow" to express a list of followers.
Using the {{{&lt;&lt;followTiddlers X&gt;&gt;}}}
will reveal the number of tiddlers with name X in the set of spaces the *current* user viewing your space follows.
{{{&lt;&lt;following jon&gt;&gt;}}} will list all the users following Jon.
{{{&lt;&lt;followers jon&gt;&gt;}}} will list all the followers of jon.
{{{&lt;linkedTiddlers&gt;&gt;}}} will list all tiddlers across TiddlySpace linked to the current tiddler
{{{&lt;linkedTiddlers follow:yes&gt;&gt;}}} will list all tiddlers across TiddlySpace that come from your list of followers
adds spaceLink view type {{{&lt;&lt;view server.bag spaceLink&gt;&gt;}}} creates a link to the space described in server.bag
{{{&lt;&lt;view server.bag spaceLink title&gt;&gt;}}} makes a link to the tiddler with title expressed in the field title in space server.bag
If no name is given eg. {{{&lt;&lt;following&gt;&gt;}}} or {{{&lt;&lt;follow&gt;&gt;}}} it will default the current user.
!StyleSheet
.followTiddlersList li {
	list-style:none;
}

.followButton {
	width: 2em;
}

.followTiddlersList li .siteIcon {
	height:48px;
	width: 48px;
}

#sidebarTabs .followers li a,
.followers .siteIcon,
.followers .siteIcon div {
	display: inline;
}

.followTiddlersList li .externalImage, .followTiddlersList li .image {
	display: inline;
}

.scanResults li {
	list-style: none;
}
!Code
***/
//{{{
(function($) {
var LIMIT_FOLLOWING = 100;

var tweb = config.extensions.tiddlyweb;
var tiddlyspace = config.extensions.tiddlyspace;
var currentSpace = tiddlyspace.currentSpace.name;

var shadows = config.shadowTiddlers;
config.annotations.ScanTemplate = "This tiddler is the default template used in the display of tiddlers founding using the tsScan macro. To access attributes use the view macro e.g. {{{&lt;&lt;view title text&gt;&gt;}}}";
shadows.ScanTemplate = "&lt;&lt;view modifier SiteIcon width:24 height:24 spaceLink:yes label:no&gt;&gt; &lt;&lt;view title link&gt;&gt;";
shadows.FollowersTemplate = "&lt;&lt;view server.bag SiteIcon width:24 height:24 spaceLink:yes label:no&gt;&gt; &lt;&lt;view server.bag spaceLink&gt;&gt;";
shadows.FollowingTemplate = "&lt;&lt;view title SiteIcon width:24 height:24 spaceLink:yes label:no&gt;&gt; &lt;&lt;view title spaceLink&gt;&gt;";
shadows.FollowTiddlersBlackList = "";
shadows.FollowTiddlersHeading = "There are tiddlers in spaces you follow using the follow tag which use the title &lt;&lt;view title text&gt;&gt;";
shadows.FollowTiddlersTemplate = ["* &lt;&lt;view server.space SiteIcon width:24 height:24 spaceLink:yes label:no&gt;&gt; ",
	"&lt;&lt;view server.space spaceLink title external:no&gt;&gt; modified by &lt;&lt;view modifier spaceLink&gt;&gt; ",
	"in the &lt;&lt;view server.space spaceLink&gt;&gt; space (&lt;&lt;view modified date&gt;&gt; @ &lt;&lt;view modified date 0hh:0mm&gt;&gt;).\n"].join("");

var name = "StyleSheetFollowing";
shadows[name] = "/*{{{*/\n%0\n/*}}}*/".
	format(store.getTiddlerText(tiddler.title + "##StyleSheet"));
store.addNotification(name, refreshStyles);

// provide support for sucking in tiddlers from the server
tiddlyspace.displayServerTiddler = function(src, title, workspace, callback) {
	var adaptor = store.getTiddlers()[0].getAdaptor();
	var localTitle = tiddlyspace.getLocalTitle(title, workspace);
	var tiddler = new Tiddler(localTitle);
	tiddler.text = "Please wait while this tiddler is retrieved...";
	tiddler.fields.doNotSave = "true";
	store.addTiddler(tiddler);
	src = story.displayTiddler(src || null, tiddler.title);
	tweb.getStatus(function(status) {
		var context = {
			host: tweb.host, // TODO: inherit from source tiddler?
			workspace: workspace,
			headers: { "X-ControlView": "false" }
		};
		var getCallback = function(context, userParams) {
			var tiddler = context.tiddler;
			tiddler.title = localTitle;
			store.addTiddler(tiddler);
			story.refreshTiddler(localTitle, null, true); // overriding existing allows updating
			if(callback) {
				callback(src, tiddler);
			}
		};
		adaptor.getTiddler(title, context, null, getCallback);
	});
};

tiddlyspace.scroller = {
	runHandler: function(title, top, bottom, height) {
		var i;
		var handlers = tiddlyspace.scroller.handlers;
		var tidEl = story.getTiddler(title);
		if(tidEl) {
			var topEl = $(tidEl).offset().top + 20;
			if(top === false || (topEl &gt; top &amp;&amp; topEl &lt; bottom)) {
				var h = handlers[title];
				for(i = 0; i &lt; h.length; i++) {
					h[i]();
				}
				tiddlyspace.scroller.clearHandlers(title);
			}
		} else {
			tiddlyspace.scroller.clearHandlers(title);
		}
	},
	clearHandlers: function(title) {
		tiddlyspace.scroller.handlers[title] = [];
	},
	registerIsVisibleEvent: function(title, handler) {
		tiddlyspace.scroller.handlers[title] = tiddlyspace.scroller.handlers[title] || [];
		tiddlyspace.scroller.handlers[title].push(handler);
	},
	init: function() {
		this.handlers = {};
		this.interval = window.setInterval(function() {
			var top = $(window).scrollTop();
			var height = $(window).height();
			var bottom = top + height;
			var title;
			for(title in tiddlyspace.scroller.handlers) {
				if(title) {
					tiddlyspace.scroller.runHandler(title, top, bottom, height);
				}
			}
		}, 2000); // every 2 seconds check scroll position
	}
};
tiddlyspace.scroller.init();

var followMacro = config.macros.followTiddlers = {
	locale: {
		followListHeader: "Here are tiddlers from spaces you follow using the follow tag which use this title.",
		noTiddlersFromFollowers: "None of the spaces you follow contain a tiddler with this name.",
		errorMessage: "There was a problem retrieving tiddlers from the server. Please try again later."
	},
	init: function() {
		followMacro.lookup = {};
	},
	followTag: "follow",
	getHosts: function(callback) {
		tweb.getStatus(function(status) {
			callback(tweb.host, tiddlyspace.getHost(status.server_host, "%0"));
		});
	},
	getBlacklist: function() {
		return store.getTiddlerText("FollowTiddlersBlackList").split("\n");
	},
	handler: function(place, macroName, params, wikifier, paramString, tiddler) {
		var args = paramString.parseParams("anon")[0];
		var containingTiddler = story.findContainingTiddler(place).getAttribute('tiddler');
		var title = (args.anon &amp;&amp; args.anon[0]) || tiddler.fields["server.title"] || tiddler.title;
		var tid = store.getTiddler(title);
		var user = params[1] || false;
		if(tid) {
			followMacro.makeButton(place, {
				url: "/search?q=title:%22" + encodeURIComponent(title) + "%22",
				containingTiddler: containingTiddler,
				blacklisted: followMacro.getBlacklist(), title: title, user: user,
				consultFollowRelationship: (args.follow &amp;&amp;
					args.follow[0] === 'false') ? false : true });
		}
	},
	makeButton: function(place, options) { // this is essentially the same code in TiddlySpaceFollowingPlugin
		var title = options.title;
		var blacklisted = options.blacklisted;
		var tiddler = store.getTiddler(title);
		var btn = $('&lt;div class="followButton" /&gt;').addClass("notLoaded").appendTo(place)[0];
		if(blacklisted.contains(title)) {
			$(btn).remove();
			return;
		} else {
			var user = options.user;
			window.setTimeout(function() { // prevent multiple calls due to refresh
				tiddlyspace.scroller.registerIsVisibleEvent(options.containingTiddler, function() {
					var mkButton = function(followers, ignore) {
						if(!followers &amp;&amp; !ignore) {
							$(btn).remove();
						} else {
							$("&lt;a /&gt;").appendTo(btn);
							var scanOptions = { url: options.url,
								spaceField: options.spaceField || "bag", template: null, sort: "-modified",
								callback: function(tiddlers) {
									$(btn).removeClass("notLoaded");
									followMacro.constructInterface(btn, tiddlers);
								}
							};
							if(!ignore) {
								scanOptions.showBags = followMacro._getFollowerBags(followers);
							}
							scanOptions.hideBags = [tiddler.fields["server.bag"]];
							scanMacro.scan(null, scanOptions, user);
						}
					};
					if(options.consultFollowRelationship) {
						followMacro.getFollowers(mkButton);
					} else {
						mkButton([], true);
					}
				});
			}, 1000);
		}
	},
	constructInterface: function(container, tiddlers) {
		var txt = tiddlers.length;
		var className = txt &gt; 0 ? "hasReplies" : "noReplies";
		var el = $(story.findContainingTiddler(container));
		$(container).empty().addClass(className);
		var btn = $("&lt;a /&gt;").addClass("followedTiddlers").text(txt).
			click(function(ev) {
				followMacro.followingOnClick(ev);
			}).appendTo('&lt;div class="followedTiddlers" /&gt;').appendTo(container)[0];
		$.data(btn, "tiddlers", tiddlers);
	},
	followingOnClick: function(ev) {
		var target = ev.target;
		var locale = followMacro.locale;
		var el = $('&lt;div class="followTiddlersList" /&gt;')[0];
		var popup = Popup.create(target,"div");
		$(popup).addClass("taggedTiddlerList followList").click(function(ev) { // make it so only clicking on the document outside the popup removes the popup
			if(ev.target.parentNode != document) {
				ev.stopPropagation();
			}
		}).append(el);
		var tiddlers = $.data(target, "tiddlers") || [];
		scanMacro.template(el, tiddlers.slice(0,1), "FollowTiddlersHeading");
		scanMacro.template(el, tiddlers, "FollowTiddlersTemplate");
		if(tiddlers.length === 0) {
			$("&lt;li /&gt;").text(locale.noTiddlersFromFollowers).appendTo(el);
		}
		Popup.show();
		ev.stopPropagation();
		return popup;
	},
	_getFollowerBags: function(followers) { // XXX: private or not?
		return $.map(followers, function(name, i) {
			return name != currentSpace ? "%0_public".format(name) : null;
		});
	},
	getFollowers: function(callback, username) {
		// returns a list of spaces being followed by the existing space
		var followersCallback = function(user) {
			if(!user.anon) {
				scanMacro.scan(null, { 
					url: "/search?q=bag:%0_public tag:%1 _limit:%2".format(user.name, followMacro.followTag, LIMIT_FOLLOWING),
					spaceField: "title", template: null, cache: true,
					callback: function(tiddlers) {
						var followers = [];
						for(var i = 0; i &lt; tiddlers.length; i++) {
							followers.push(tiddlyspace.resolveSpaceName(tiddlers[i].title));
						}
						callback(followers);
					}
				});
			} else {
				callback(false);
			}
		};
		return !username ? tweb.getUserInfo(followersCallback) : followersCallback({ name: username });
	}
};

var scanMacro = config.macros.tsScan = {
	init: function () {
		this.scanned = {};
	},
	_tiddlerfy: function(jsontiddlers, options) {
		var tiddlers = [];
		var spaceField = options.spaceField || "bag"; // TODO: phase out use view types instead
		$.each(jsontiddlers, function(i, t) {
			var use = false;
			if(!options.showBags || (options.showBags &amp;&amp; options.showBags.contains(t.bag))) {
				use = true;
			}
			if(options.hideBags &amp;&amp; options.hideBags.contains(t.bag)) {
				use = false;
			}
			if(use) {
				var spaceName = t[spaceField];
				var tiddler = config.adaptors.tiddlyweb.toTiddler(t, tweb.host);
				tiddler.fields["server.space"] = tiddlyspace.resolveSpaceName(spaceName);
				tiddlers.push(tiddler);
			}
		});
		return tiddlers;
	},
	_scanCallback: function(place, jsontiddlers, options) {
		var locale = followersMacro.locale;
		var tiddlers = scanMacro._tiddlerfy(jsontiddlers, options);
		
		if(options.sort) {
			tiddlers = store.sortTiddlers(tiddlers, options.sort);
		}
		if(options.filter) {
			var _store = new TiddlyWiki();
			config.lastStore = _store;
			for(var i = 0; i &lt; tiddlers.length; i++) {
				var clone = tiddlers[i];
				clone.title = tiddlyspace.getLocalTitle(clone.title, clone.fields['server.workspace']);
				_store.addTiddler(clone);
			}
			tiddlers = _store.filterTiddlers(options.filter);
		}
		if(place) {
			$(place).empty();
			var list = $("&lt;ul /&gt;").appendTo(place)[0];
			scanMacro.template(list, tiddlers, options.template);
			if(tiddlers.length === 0) {
				$("&lt;li /&gt;").text(options.emptyMessage || locale.noone).appendTo(list);
				$(list).addClass("emptyList");
			}
		}
		if(options.callback) {
			options.callback(tiddlers);
		}
	},
	constructSearchUrl: function(host, options) {
		if(options.url) {
			return options.url;
		}
		var inputs = options.searchValues;
		var tag = options.tag;
		var searchField = options.searchField || "title";
		var searchQuery = [];
		for(var i = 0; i &lt; inputs.length; i++) {
			searchQuery.push('%0:"%1"'.format(searchField, inputs[i]));
		}
		var query = searchQuery.join(" OR ");
		query = tag ? "(%0) AND tag:%1".format(query, tag) : query;
		query = options.query ? "%0;%1;".format(query, options.query) : query;
		query = options.fat ? "%0&amp;fat=1".format(query) : query;
		return '%0/search?q=%1'.format(host, query);
	},
	scan: function(place, options) { // TODO: make use of list macro with url filter
		var locale = followersMacro.locale;
		options.template = options.template ? options.template : "ScanTemplate";
		followMacro.getHosts(function(host, tsHost) {
			$(place).text(followersMacro.locale.pleaseWait);
			options = options ? options: {};
			var url = scanMacro.constructSearchUrl(host, options);
			if(options.cache &amp;&amp; scanMacro.scanned[url]) {
				var tiddlers = scanMacro.scanned[url].tiddlers;
				var run = function(tiddlers) {
					scanMacro._scanCallback(place, tiddlers, options);
				};
				if(tiddlers) {
					run(tiddlers);
				} else {
					scanMacro.scanned[url].callbacks.push(run);
				}
			} else {
				var callback = function(tiddlers) {
					scanMacro._scanCallback(place, tiddlers, options);
				};
				if(scanMacro.scanned[url] &amp;&amp; scanMacro.scanned[url].callbacks) {
					scanMacro.scanned[url].callbacks.push(callback);
				} else {
					scanMacro.scanned[url] = {
						callbacks: [callback]
					};
				}
				ajaxReq({
					url: url,
					dataType: "json",
					success: function(tiddlers) {
						scanMacro.scanned[url].tiddlers = tiddlers;
						var callbacks = scanMacro.scanned[url].callbacks;
						while(callbacks.length &gt; 0) {
							callbacks.pop()(tiddlers);
						}
					},
					error: function(xhr) {
						$(place).empty();
						$("&lt;span /&gt;").addClass("annotation error").text(locale.error.format(xhr.status)).appendTo(place);
					}
				});
			}
		});
	},
	template: function(place, tiddlers, template) { // TODO: make use of list macro.
		for(var i = 0; i &lt; tiddlers.length; i++) {
			var tiddler = tiddlers[i];
			var item = $('&lt;li class="spaceName" /&gt;').appendTo(place)[0];
			var spaceName = tiddler.fields["server.space"] || "";
			var templateText = store.getTiddlerText(template).replace(/\$1/mg, spaceName);
			wikify(templateText, item, null, tiddler);
		}
	},
	getOptions: function(paramString, tiddler) {
		var args = paramString.parseParams("name", null, true, false, true)[0];
		var options = { query: false, sort: false, tag: false, template: false, showBags: args.show || false,
			hideBags: args.hide || false, filter: false, spaceField: "bag", searchField: "title", fat: false,
			emptyMessage: false };
		for(var name in args) {
			if(name != "name") {
				if(name == "fat") {
					options[name] = true;
				} else {
					options[name] = args[name][0];
				}
			}
		}
		// if user has set searchField to modifier, then use the modifiers value if available otherwise use searchValues.
		var searchField = options.searchField;
		var searchValues = args[searchField] ? args[searchField] : args.searchValues;
		// if neither of those were used use the first parameter
		var defaultValues = tiddler ? [ tiddler.title ] : [];
		options.searchValues = searchValues ? searchValues : ( args.name ? [args.name[0]] : defaultValues);
		return options;
	},
	handler: function(place, macroName, params, wikifier, paramString, tiddler) {
		var container = $("&lt;div /&gt;").addClass("scanResults resultsArea").appendTo(place)[0];
		var options = scanMacro.getOptions(paramString, tiddler);
		scanMacro.scan(container, options);
	}
};

var followersMacro = config.macros.followers = {
	locale: {
		loggedOut: "Please login to see the list of followers",
		noSupport: "We were unable to retrieve followers as your browser does not support following.",
		pleaseWait: "Please wait while we look this up...",
		error: "Error %0 occurred whilst retrieving data from server",
		noone: "None."
	},
	handler: function(place, macroName, params, wikifier, paramString, tiddler) {
		var locale = followersMacro.locale;
		var args = paramString.parseParams("name", null, true, false, true)[0];
		var username = args.name ? args.name[0] : false;
		var container = $('&lt;div class="followers" /&gt;').text(locale.pleaseWait).
			appendTo(place)[0];
		var followersCallback = function(user) {
			if(user.anon) {
				$("&lt;span /&gt;").text(locale.loggedOut).appendTo(container);
			} else {
				var options = scanMacro.getOptions(paramString);
				$.extend(options, {
					url: "/search?q=title:@%0 OR title:%0 tag:%1 _limit:%2".
						format(user.name, followMacro.followTag, LIMIT_FOLLOWING),
					spaceField: "bag",
					template: options.template ? options.template : "FollowersTemplate"
				});
				scanMacro.scan(container, options);
			}
		};
		return !username ? followersCallback({ name: currentSpace }) : followersCallback({ name: username });
	}
};

var followingMacro = config.macros.following = {
	locale: {
		pleaseWait: followersMacro.locale.pleaseWait,
		loggedOut: "Please login to see who you are following",
		noSupport: followersMacro.locale.noSupport,
		error: followersMacro.locale.error,
		noone: followersMacro.locale.noone
	},
	handler: function(place, macroName, params, wikifier, paramString, tiddler) {
		var locale = followingMacro.locale;
		var args = paramString.parseParams("name", null, true, false, true)[0];
		var fat = args.fat ? true : false;
		var username = args.name ? args.name[0] : false;
		var container = $('&lt;div class="following" /&gt;').text(locale.pleaseWait).
			appendTo(place)[0];
		var followingCallback = function(user) {
			if(user.anon) {
				$("&lt;span /&gt;").text(locale.loggedOut).appendTo(container);
			} else {
				var options = scanMacro.getOptions(paramString);
				$.extend(options, {
					url: "/search?q=bag:%0_public tag:%1 _limit:%2".format(user.name, followMacro.followTag, LIMIT_FOLLOWING),
					spaceField: "title",
					template: options.template ? options.template : "FollowingTemplate"
				});
				scanMacro.scan(container, options);
			}
		};
		return !username ? followingCallback({ name: currentSpace }) : followingCallback({ name: username });
	}
};

var linkedMacro = config.macros.linkedTiddlers = {
	handler: function(place, macroName, params, wikifier, paramString, tiddler) {
		var args = paramString.parseParams("anon")[0];
		var title = params[0] || tiddler.fields["server.title"] || tiddler.title;
		var tid = store.getTiddler(title);
		var containingTiddler = story.findContainingTiddler(place).getAttribute('tiddler');
		if(tid) {
			followMacro.makeButton(place, {
				spaceField: "recipe",
				url: "/bags/%0/tiddlers/%1/backlinks".format(tid.fields['server.bag'],
					encodeURIComponent(tid.title)),
				blacklisted: followMacro.getBlacklist(),
				title: title,
				containingTiddler: containingTiddler,
				user: params[1] || false,
				consultFollowRelationship: args.follow ? true : false });
		}
	}
};

if(config.options.chkFollowTiddlersIsLinkedTiddlers) {
	merge(config.macros.followTiddlers, config.macros.linkedTiddlers);
	config.shadowTiddlers.FollowTiddlersHeading = "These are the other tiddlers that link to this tiddler.";
}

})(jQuery);
//}}}</pre>
</div>
<div title="SystemSettings" server.title="SystemSettings" server.page.revision="2566025" server.etag="&quot;honly-666_private/SystemSettings/2566025:0f256158306e864c04d116614be607043a43df5f&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_private" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_private" server.permissions="read, write, create, delete" server.content-type="" modified="20160927050307" created="20160927050307" tags="excludeLists" _hash="1720b805c0408fb371f3e66ca349c2c80a668005">
<pre>chkPrivateMode: false</pre>
</div>
<div title="StyleSheetTiddlySpace" server.title="StyleSheetTiddlySpace" server.page.revision="1521919" server.etag="&quot;system-theme_public/StyleSheetTiddlySpace/1521919:362b6e006535214c98198a2770e67f94ed7c92c8&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-theme_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-theme_public" server.permissions="read" server.content-type="" modified="20131111192330" created="20131111192330" tags="excludeLists excludeSearch" _hash="3150bd9a2cb78777f61a7b6f6539c5fa646fd7ac">
<pre>/*{{{*/
body {
	font-size: 1em;
	font-family: helvetica, arial, sans-serif;
	background-color: #fff;
	color: [[ColorPalette::Foreground]];
}

body ul { margin: 0; }

#popup {
	background-color: [[ColorPalette::TertiaryPale]];
}

#popup.confirmationPopup, .followList {
	font-size: 0.8em;
	padding: 1em;
	border: solid 1px [[ColorPalette::SecondaryMid]];
	background-color: [[ColorPalette::SecondaryPale]];
}

.followList .listTitle {
	text-decoration: underline;
}

#popup .followTiddlersList a {
	display: inline;
	padding: 0;
}

#popup li a {
	color: [[ColorPalette::PrimaryMid]];
	font-weight: bold;
}

#popup li a:hover {
	color: [[ColorPalette::PrimaryPale]];
	background: [[ColorPalette::PrimaryMid]];
}

#popup li.listTitle {
	border-bottom: 1px solid #000;
	font-weight: bold;
	margin-bottom: 10px;
}

#popup.followList {
	margin-left: 50px;
	margin-top: -30px;
}

.followTiddlersList .label {
	display: block;
	left: 10px;
	top: 0px;
	line-height: 16px;
	position: relative;
}

#popup .followTiddlersList .siteIcon{
	height: auto;
}

#popup .followTiddlersList li{
	clear: both;
	display: block;
	height: 48px;
	margin-bottom: 8px;
	position: relative;
}

#popup .followTiddlersList a{
	display: inline;
}

#displayArea {
	margin: 0;
	top: 0px;
	left: 0px;
	width: 100%;
	position: relative;
}

.revisionCloak {
	position: absolute;
	position: fixed !important;
	height: 100%;
	width: 100%;
	top: 0;
	left: 0;
	border: 0;
	margin: 0;
	padding: 0;
	opacity: 0.5;
	filter: alpha(opacity=50);
	background-color: #000;
}

/* *** Header *** */
.header {
	position: relative;
	background-color: [[ColorPalette::PrimaryMid]];
	_width: 100%; /* ie 6 demands */
}

.headerForeground {
	background-color: [[ColorPalette::PrimaryMid]];
	float: left;
	margin: 24px 16px 0px 72px;
	padding: 0;
	position: relative;
	top: 0;
	_width: 70%; /*ie6: needed for the background to actually be transparent*/
	_background-color: transparent; /*ie6: needed to show the search box*/
}

.clearFloat {
	clear: both;
}

#contentWrapper {
	position: relative;
	padding-top: 1px;
	top: -1px;
}

#tiddlerDisplay {
	_position: relative; /* ie 6*/
}

.siteTitle {
	clear: both;
	display: block;
	font-size: 32px;
	font-weight: bold;
	line-height: 32px;
}

.siteSubtitle {
	display: block;
	font-size: 14px;
	height: 16px;
	margin-bottom: 8px;
}

#sidebarSearch {
	padding: 0;
	position: absolute;
	right: 80px;
	top: 8px;
	width: 176px;
}

#sidebarSearch .txtOptionInput {
	width: 100%;
	margin-top: 5px;
	_color: #bbb; /* ie6 danger */
}

#sidebarSearch .txtOptionInput:focus {
	color: #000;
}

#sidebarSearch .searchButton {
	display: none;
}

/* *** Menu Bar *** */

#mainMenu {
	position: static;
	text-align: left;
	margin-left: 72px;
	float: left;
	width: auto;
	padding: 0;
	font-size: 1em;
	line-height: normal;
}

#mainMenu a {
	color: #fff;
	padding: 8px;
	font-size: 0.9em;
	margin-right: 16px;
}

#mainMenu a:hover {
	background-color: [[ColorPalette::PrimaryMid]];
	color: [[ColorPalette::Background]]
}

#sidebarOptions {
	margin-right: 72px;
	float: right;
	font-size: 1.1em;
	line-height: 1.6em;
	min-height: 1em;
	padding-top: 0;
}

#sidebarOptions a {
	margin-right: 8px;
}

.confirmationPopup .button,
#sidebarOptions .button {
	cursor: pointer;
	line-height: 1.4em;
	text-align: center;
	margin-right: 8px;
	margin-left:-2px;
}

.confirmationPopup .button {
	font-size: 0.9em;
	padding: 2px;
}

#sidebarOptions .button {
	font-size: 0.7em;
	float: left;
	width: 80px;
	padding: 0px;
        color: #fff;
}

.confirmationPopup a.button,
#sidebarOptions a {
	border: none;
	margin: 0 0.2em;
	padding: 0.6em 0.25em;
	display: inline;
	color: #666;
}

.confirmationPopup a.button:hover,
#sidebarOptions a:hover {
	color: #000;
}

.confirmationPopup a.button:active,
#sidebarOptions a:active {
	border: solid 1px [[ColorPalette::PrimaryMid]];
	background-color: #fff;
	background: -webkit-gradient( linear, left bottom, left top, color-stop(0.1,rgb(200,200,200)), color-stop(1, rgb(100,100,100)));
	background: -moz-linear-gradient(center bottom , rgb(200,200,200) 10%,rgb(100,100,100) 100%) repeat scroll 0 0 transparent;
}
/* *** Sidebar *** */

#sidebar .wizard table {
	margin: 0px;
}

.tabContents .listTitle:first-child {
	margin-top: 0px;
}

#menuBar {
	background: [[ColorPalette::PrimaryLight]];
	left: 0;
	right: 0;
	position: relative;
	margin: 0;
	padding: 0.5em 0 0.5em 0;
	min-height: 1em;
	overflow: hidden;
	_width: 100%; /* for ie 6 */
}

#sidebarOptions a.button:hover {
	color: [[ColorPalette::PrimaryPale]];
    background: [[ColorPalette::PrimaryMid]];
}

#tiddlerDisplay, #searchResults {
	margin: 16px 448px 0 72px;
}

#sidebarTabs {
	position: absolute;
	right: 72px;
	width: 352px;
	top: 0;
}

#sidebarTabs .tabsetWrapper .tabset {
	width: 87px;
	border-top: 1px solid [[ColorPalette::PrimaryPale]];
	border-left: 1px solid [[ColorPalette::PrimaryPale]];
	border-bottom: 1px solid [[ColorPalette::PrimaryPale]];
	height: auto;
	float: left;
	word-wrap: break-word;
	top: 0;
	padding: 0;
}

#sidebarTabs .tabsetWrapper .tabContents {
	background-color: [[ColorPalette::PrimaryPale]];
	border: 3px solid [[ColorPalette::PrimaryMid]];
	width: 242px;
	_width: 238px;
	left: -3px;
	_left: -5px;
	position: relative;
	min-height: 34em;
	padding: 8px;
	font-size: 0.8em;
}

/* ---- Side style --- */

#sidebarTabs .tabsetWrapper .tabset .tab {
	font-size: 0.9em;
	padding: 0.7em 8px 0.5em;
	color: #fff;
	background: [[ColorPalette::PrimaryLight]];
	border: none;
	line-height: 16px;
	position: relative;
	display: block;
	margin: 0;
}

#sidebarTabs .tabsetWrapper .tabset .tabSelected {
	color: [[ColorPalette::PrimaryMid]];
	background: [[ColorPalette::PrimaryPale]];
	border-top: 3px solid [[ColorPalette::PrimaryMid]];
	border-bottom: 3px solid [[ColorPalette::PrimaryMid]];
	border-left: 3px solid [[ColorPalette::PrimaryMid]];
	z-index: 10;
	margin-top: -1px;
	font-weight: bold;
}

#sidebarTabs .tabContents li {
	border: none;
	margin-left: 0;
	word-wrap: break-word;
}

.tabContents .timeline {
	background: [[ColorPalette::PrimaryPale]];
	margin-bottom: 8px;
}

#sidebarTabs .timeline li.listTitle {
	color: #132E43;
	margin-left: 8px 0;
	padding: 0.3em 0.11em;
	font-size: 1em;
	border-bottom: none;
}

#sidebarTabs .tabContents li a {
	display: block;
	text-align: left;
	margin: 0 0 1px 0;
	padding: 0.3em 1em;
	background: [[ColorPalette::PrimaryPale]];
}

#sidebarTabs .tabsetWrapper .tabset a:hover,
#sidebarTabs .tabContents li a:hover {
	color: [[ColorPalette::PrimaryPale]];
	background: [[ColorPalette::PrimaryMid]];
}

/* Activity Stream */
#sidebarTabs .tabContents .activityStream .feedItem a {
	display: inline-block;
	padding: 0;
	background: none;
}

/* ---- Tagging box --- */
.tagInfo {
	border: 1px solid #cccccc;
	padding: 10px 15px;
	-moz-box-shadow: 0 2px 2px rgba(0, 0, 0, 0.2);
	box-shadow: 0 2px 2px rgba(0,0,0,0.2);
	color: [[ColorPalette::TertiaryMid]];
	background: -moz-linear-gradient(100% 100% 90deg, #f4f4f4, #e5e5e5);
	background: -webkit-gradient(linear, left top, right top, from(#e5e5e5), to(#f4f4f4));
	margin-top: 1em;
	font-size: 13px;
	margin: 0 0 0 56px;
}

.tagInfo ul {
	list-style: none;
	padding-left: 2.2em;
}

.tagInfo ul li {
	display: inline;
}

.tagInfo ul li.listTitle,
.tagInfo .tagging ul li.listTitle {
	color: [[ColorPalette::PrimaryMid]];
	font-size: 13px;
}

.tagInfo ul li a {
	border: none;
}

.tagInfo .tagging ul li {
	float: none;
	display: inline-block;
}

.tagInfo .tagging {
	padding: 0;
}

.viewRevision .toolbar {
	right: 48px;
	top: 8px;
}

.viewRevision .modifierIcon img,
.viewRevision .modifierIcon svg {
	margin-right: 8px;
}

.viewRevision .toolbar svg {
	width: 32px;
	height: 32px;
}

/* --- IE hacks from lattice --- */

/* ie hacks */
* html #menuBar {
	margin-bottom: 8px;
}
.toolbar .svgIconText {
	*display: inline;
}

div.tiddler .toolbar a {
	cursor: pointer;
	float: left\9;
	display: inline\9;
}

* html .toolbar {
	right: 8px;
}
* html .followButton a {
	margin-top: 0px;
	margin-right: 8px;
}
* html #tiddlerDisplay {
	margin-top: 0px;
}

/* for printing purposes */
@media print {
	#mainMenu,
	#sidebar,
	#messageArea,
	.toolbar,
	.followPlaceHolder,
	#backstageButton,
	#backstageArea,
	#sidebarTabs,
	#sidebarSearch .txtOptionInput,
	#sidebarOptions {
		display: none !important;
	}
	#displayArea {
		margin: 1em 1em 0em;
	}
	noscript {
		display:none; /* Fixes a feature in Firefox 1.5.0.2 where print preview displays the noscript content */
	}
	#tiddlerDisplay {
		margin: 16px 16px;
	}
}

@media all and (max-width: 960px){
	#tiddlerDisplay,
	#searchResults {
		margin: 16px 366px 0 16px;
	}

	#mainMenu {
		margin-left: 16px;
	}

	.headerForeground {
		margin-left: 16px;
	}

	#sidebarSearch {
		right: 16px;
	}

	#sidebarOptions {
		margin-right: 16px;
	}

	#sidebarTabs {
		right: 16px;
		width: 326px;
	}

	#sidebarTabs .tabsetWrapper .tabset {
		font-size: 0.9em;
		width: 77px;
	}

	#sidebarTabs .tabsetWrapper .tabContents {
		width: 226px;
		_width: 222px;
	}

	#sidebarTabs .tabContents li a {
		font-size: 0.9em;
	}
}
/*}}}*/
[[StyleSheetTiddler]]</pre>
</div>
<div title="TiddlySpaceCSRF" server.title="TiddlySpaceCSRF" server.page.revision="1521904" server.etag="&quot;tiddlyspace/TiddlySpaceCSRF/1521904:e8d81bd7002dffb014a07eb738fdadd549467f1a&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/tiddlyspace" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="tiddlyspace" server.permissions="read" server.content-type="text/javascript" modified="20131111192332" created="20131111192332" tags="excludeLists excludeSearch systemConfig" _hash="10b0276ddc805a9489b6449c972bb1dc00fb9cf0">
<pre>(function() {
var getCSRFToken = function(window) {
	// XXX: should not use RegEx - cf.
	// http://www.quirksmode.org/js/cookies.html
	// https://github.com/TiddlySpace/tiddlyspace/commit/5f4adbe009ed4bda3ce39058a3fb07de1420358d
	var regex = /^(?:.*; )?csrf_token=([^(;|$)]*)(?:;|$)/;
	var match = regex.exec(document.cookie);
	var csrf_token = null;
	if (match &amp;&amp; (match.length === 2)) {
		csrf_token = match[1];
	}

	return csrf_token;
};

if (typeof config !== 'undefined' &amp;&amp; config.extensions &amp;&amp;
		config.extensions.tiddlyspace &amp;&amp;
		config.extensions.tiddlyspace.getCSRFToken === null) {
	config.extensions.tiddlyspace.getCSRFToken = getCSRFToken;
} else {
	window.getCSRFToken = getCSRFToken;
}
})(window);</pre>
</div>
<div title="moreCommand" server.title="moreCommand" server.page.revision="1521923" server.etag="&quot;system-images_public/moreCommand/1521923:1753819bb12192b314344b28b321bc8050521c69&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-images_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-images_public" server.permissions="read" server.content-type="image/svg+xml" modified="20131111192332" created="20131111192332" tags="excludeLists excludeSearch" _hash="83f02e8680765ba08fd5764a7627f51cdd4b7f0d">
<pre>&lt;svg xmlns="http://www.w3.org/2000/svg" xmlns:xl="http://www.w3.org/1999/xlink" version="1.1" viewBox="434 218 68 68"
width="30" height="30"&gt;
&lt;g stroke="none" stroke-opacity="1" stroke-dasharray="none" fill="none" fill-opacity="1"&gt;
	&lt;g&gt;
		&lt;path d="M 478.39694 232.53705 L 478.39694 232.53705 
		C 477.1145 231.85132 475.77875 231.30147 474.41058 230.88734 L 474.41058 218.24994 L 461.58942 218.24994 
		L 461.58942 230.88734 C 460.22125 231.30147 458.8855 231.85132 457.60306 232.53705 L 448.66824 223.60214 
		L 439.6022 232.66814 L 448.53717 241.60304 C 447.8515 242.8854 447.30157 244.22116 446.88745 245.58936 
		L 434.25 245.58936 L 434.25 258.41052 L 446.88745 258.41052 
		C 447.30157 259.77869 447.8515 261.11447 448.53717 262.39688 L 439.6022 271.33173 L 448.66824 280.3978 
		L 457.60306 271.46283 C 458.8855 272.14862 460.22125 272.69846 461.58942 273.11252 L 461.58942 285.74988 
		L 474.41058 285.74988 L 474.41058 273.11252 C 475.77875 272.69846 477.1145 272.14862 478.39694 271.46283 
		L 487.33176 280.3978 L 496.39767 271.33173 L 487.46286 262.39688 
		C 488.14853 261.11447 488.69836 259.77869 489.11255 258.41052 L 501.74988 258.41052 L 501.74988 245.58936 
		L 489.11255 245.58936 C 488.69836 244.22116 488.14853 242.8854 487.46286 241.60304 L 496.39767 232.66814 
		L 487.33176 223.60214 Z M 475.3328 244.66714 C 479.3825 248.71698 479.3825 255.2829 475.3328 259.33273 
		C 471.28296 263.3826 464.71704 263.3826 460.66724 259.33273 
		C 456.61737 255.2829 456.61737 248.71698 460.66724 244.66714 
		C 464.71704 240.61734 471.28296 240.61734 475.3328 244.66714" fill="#111"
		class="glyph"/&gt;
	&lt;/g&gt;
&lt;/g&gt;
&lt;/svg&gt;</pre>
</div>
<div title="喜剧综艺" server.title="喜剧综艺" server.page.revision="2579931" server.etag="&quot;honly-666_public/%E5%96%9C%E5%89%A7%E7%BB%BC%E8%89%BA/2579931:fa330718ebdea797115d5ed8658740635395f0a3&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20161102050102" created="20161102050102" tags="happy" _hash="97f55d22d4069fce56e64bd7c768755600171f6a">
<pre>[[喜剧总动员]]   [[跨界喜剧王]]</pre>
</div>
<div title="贵州财经大学教务系统" server.title="贵州财经大学教务系统" server.page.revision="2579934" server.etag="&quot;honly-666_public/%E8%B4%B5%E5%B7%9E%E8%B4%A2%E7%BB%8F%E5%A4%A7%E5%AD%A6%E6%95%99%E5%8A%A1%E7%B3%BB%E7%BB%9F/2579934:57b5559cd8a53d85928ae81264ca6f8ca2e69374&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20161102050336" created="20161102050336" tags="" _hash="986e296c77f16cc97e1a13f809a8d8f0740f1ad3">
<pre>登录界面

http://jwc.gzife.edu.cn/</pre>
</div>
<div title="第四次作业" server.title="第四次作业" server.page.revision="2584520" server.etag="&quot;honly-666_public/%E7%AC%AC%E5%9B%9B%E6%AC%A1%E4%BD%9C%E4%B8%9A/2584520:e6fdb5ba1dc4ec7ff4afdd8cefc610bb362b3b32&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20161114054628" created="20161102140158" tags="" _hash="2039133104368d949e3c380789bc12ef033db3c3">
<pre>对Wikepage与Wiki-Toolkit进行比较

（1）功能：
1.特殊功能：
共同点：
    ①两者都是由Unicode支持的维基工具。
    ②都支持全文搜索，且都没有结构化数据。
不同点：
    ①Wikepage没有电子邮件通知、评论、类别、名称空间、页面重定向和冲突处理，而Wiki-Toolkit均有相关的插件。
    ②Wiki-Toolkit有从右到左的支持，而Wikepage不支持。

2.语法功能：
共同点：二者都有自己的自定义风格。
不同点：
     ①Wikepage没有一个HTML标记语言，而Wiki-Toolkit拥有全部。
     ②Wikepage没有数学公式、减价的支持、表情符号的支持、语法高亮显示、脚注、内部的评论、FAQ标签和内容包括。
     ③Wikepage有引用和提要聚合的功能。
（2）作用：
在统计数据方面的共同点：
     ①都是能显示最近的数据变化。
不同点：
     ①Wikepage没有想要的、孤立的页面，也没有最近的有课分析。而Wiki-Toolkit有想要的和鼓励的页面插件。
在输出方面的共同点：二者都有RSS提要。
不同点：

    ①Wikepage有CSS样式表、主题和皮肤还有Au-TO提要。而Wiki-Toolkit没有。
    ②Wikepage没有ATOM提要、缩写、原料出口、、HTML导出、XML导出和PDF导出，而Wiki-Toolkit有ATOM提要。

（3）系统需求：
相同点：两者都不能进行根访问。
不同点：①Wikepage 的操作系统与运行的平台没有关系，而Wiki-Toolkitd的操作系统可以任意的运行Perl。
     ②Wikepage的网络服务器是独立的，而Wiki-Toolkitd的网络服务器可以由任何CGI支持。
     ③Wikepage有一个或者n个其他系统需求，而Wiki-Toolkitd没有其它的系统需求。
总结：由二者的比较可以看出Wikepage适用的范围明显比Wiki-Toolkitd广很多，但是二者的功能作用都各有侧重。但是从系统需求来看，Wikepage拥有独立的网络服务器，可以供小群体和私人用户使用。
</pre>
</div>
<div title="SideBarOptions" server.title="SideBarOptions" server.page.revision="1521921" server.etag="&quot;system-theme_public/SideBarOptions/1521921:b765817e3b57420a2de1743ea8d0c9db2aa4a691&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-theme_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-theme_public" server.permissions="read" server.content-type="" modified="20131111192330" created="20131111192330" tags="excludeLists excludeSearch" _hash="6516f71685d10be266a599f46d8dcf1c658225d0">
<pre>&lt;&lt;closeAll&gt;&gt;&lt;&lt;permaview&gt;&gt;&lt;&lt;newTiddler&gt;&gt;</pre>
</div>
<div title="电影视频" server.title="电影视频" server.page.revision="2579929" server.etag="&quot;honly-666_public/%E7%94%B5%E5%BD%B1%E8%A7%86%E9%A2%91/2579929:a5c54a8d82f62bd20e70904b4f306ca2ad5e2d8f&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20161102045822" created="20161102045822" tags="" _hash="160133ad5c7ff3d2357adc69cf26f30b1d170392">
<pre>[[喜剧]]   [[惊悚]]</pre>
</div>
<div title="shadowIcon" server.title="shadowIcon" server.page.revision="1521926" server.etag="&quot;system-images_public/shadowIcon/1521926:e894dd94e1f885bb2227c9f35a06cf634459333b&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-images_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-images_public" server.permissions="read" server.content-type="image/png" modified="20131111192332" created="20131111192332" tags="excludeLists excludeSearch" _hash="754f7258625a19c375dcae5254d6a604c7686d8d">
<pre>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</pre>
</div>
<div title="ViewTemplate" server.title="ViewTemplate" server.page.revision="2564535" server.etag="&quot;honly-666_public/ViewTemplate/2564535:ed18c6148306b47f3a956de6b2c1a5256425baa2&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20160924143800" created="20160924143725" tags="excludeSearch" _hash="ec1a1160ffa63374af82a4b78819b7171ca9f254">
<pre>&lt;!--{{{--&gt;
&lt;div class='toolbar'
	macro='toolbar [[ToolbarCommands::ViewToolbar]] icons:yes height:16 width:16 more:popup'&gt;
&lt;/div&gt;
&lt;div class='heading'&gt;
	&lt;span class='spaceSiteIcon'
		macro='tiddlerOrigin label:no spaceLink:yes height:48 width:48 preserveAspectRatio:yes'&gt;
	&lt;/span&gt;
	&lt;span class="titleBar"&gt;
		&lt;div class='title' macro='view title text'&gt;&lt;/div&gt;
		&lt;span class="subtitle" macro='viewRevisions page:5'&gt;
			last modified on
			&lt;span macro="view modified date"&gt;&lt;/span&gt;
		&lt;/span&gt;
		&lt;div macro="view title replyLink"&gt;&lt;/div&gt;
	&lt;/span&gt;
	&lt;span class='followPlaceHolder' macro='followTiddlers'&gt;&lt;/span&gt;
	&lt;span class='modifierIcon'
		macro='view modifier SiteIcon label:no spaceLink:yes height:48 width:48 preserveAspectRatio:yes'&gt;
	&lt;/span&gt;
	&lt;div class='tagClear'&gt;&lt;/div&gt;
&lt;br&gt;&lt;img src="t01be7e79362a809ea5.jpg"height="400"width="500"&gt;&lt;/marquee&gt;&lt;/h1&gt;&lt;br&gt;

&lt;/div&gt;
&lt;div class='content'&gt;
	&lt;div class='viewer' macro='view text wikified'&gt;&lt;/div&gt;
&lt;/div&gt;
&lt;div class='tagInfo'&gt;
	&lt;div class='tidTags' macro='tags'&gt;&lt;/div&gt;
	&lt;div class='tagging' macro='tagging'&gt;&lt;/div&gt;
&lt;/div&gt;
&lt;!--}}}--&gt;</pre>
</div>
<div title="作业" server.title="作业" server.page.revision="2580054" server.etag="&quot;honly-666_public/%E4%BD%9C%E4%B8%9A/2580054:2d8ad43190656f14911b98c798891ef24a9cb177&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20161102140135" created="20161102042024" tags="" _hash="fa010533d51a6b0fdbe361144d65341d6ffd1208">
<pre>[[第1次翻译作业——目录和图表]]         [[第2次翻译作业——17、18]]              [[第3次翻译作业修改后的——方法和目标]]                  [[第3次翻译目标和方法]]      [[第四次作业]]        [[第五次作业]]       [[第六次作业]] </pre>
</div>
<div title="MainMenu" server.title="MainMenu" server.page.revision="2580035" server.etag="&quot;honly-666_public/MainMenu/2580035:92af185c1fdd4e42169273db350a71989030995d&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20161102132032" created="20160924143150" tags="常用" _hash="cdff7aa812cc143a8ed78f7d79a659479e917358">
<pre>[[首页]]    [[学习资料]]       [[作业]]    [[音乐  ]]   [[电影视频 ]]   [[ 喜剧综艺]]    [[贵州财经大学教务系统]]    [[黄景瑜]]
</pre>
</div>
<div title="editTiddler" server.title="editTiddler" server.page.revision="2564496" server.etag="&quot;honly-666_public/editTiddler/2564496:5121b4f1561ecc70e95b196643f0e2c7a779c7d9&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="image/svg+xml" modified="20160924141749" created="20160924141749" tags="excludeSearch" _hash="b22e71636c8fdc0c17ea8899b81b0688dcd2b15f">
<pre>&lt;svg xmlns="http://www.w3.org/2000/svg" xmlns:xl="http://file01.16sucai.com/d/file/2014-01-16/13898530095157.jpg" version="1.1" viewBox="301 225 48 52"
width="30" height="30"&gt;
&lt;g stroke="none" stroke-opacity="1" stroke-dasharray="none" fill="none" fill-opacity="1"&gt;
	&lt;g&gt;
		&lt;path d="M 333.00003 234 L 306 258.75003 L 301.5 270 L 312.75 265.50003 L 339.75 240.74998 Z M 337.5 229.50002 
		L 335.24988 231.75008 L 341.99997 238.50003 L 344.24997 236.24995 Z M 342 225.00003 L 339.74988 227.25009 
		L 346.5 234.00005 L 348.75 231.75003 Z M 301.5 273.9719 C 301.5 273.9719 309.59888 277.99927 317.70013 273.97183 
		C 325.80066 269.94437 341.99997 276.65686 341.99997 276.65686 L 341.99997 273.97195 
		C 341.99997 273.97195 325.80014 267.2594 317.70013 271.28687 C 309.6 275.31451 301.5 271.28683 301.5 271.28683 Z" 
		fill="#101010" class="glyph"/&gt;
	&lt;/g&gt;
&lt;/g&gt;
&lt;/svg&gt;</pre>
</div>
<div title="chrjs" server.title="chrjs" server.page.revision="1521886" server.etag="&quot;tiddlyspace/chrjs/1521886:f93fd243b49ff16263a881d4d875484aa5bd6aee&quot;" modifier="None" creator="None" server.workspace="bags/tiddlyspace" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="tiddlyspace" server.permissions="read" server.content-type="text/javascript" modified="20131111192332" created="20131111192332" tags="excludeLists excludeSearch systemConfig" _cache-max-age="43200" _hash="21f8cd31fb5331db45ab9f2cfbaeb97c6cdf38a9">
<pre>/***
https://raw.github.com/tiddlyweb/chrjs/master/main.js
***/
//{{{
// TiddlyWeb adaptor
// v0.14.3

/*jslint vars: true, unparam: true, nomen: true, white: true */
/*global jQuery */

var tiddlyweb = (function($) {

"use strict";

var tw = {
	routes: {
		// host is the TiddlyWeb instance's URI (including server_prefix)
		// placeholders "_type" &amp; "name" refer to the respective bag/recipe
		root     : "{host}/",
		bags     : "{host}/bags",
		bag      : "{host}/bags/{name}",
		recipes  : "{host}/recipes",
		recipe   : "{host}/recipes/{name}",
		tiddlers : "{host}/{_type}s/{name}/tiddlers",
		tiddler  : "{host}/{_type}s/{name}/tiddlers/{title}",
		revisions: "{host}/{_type}s/{name}/tiddlers/{title}/revisions",
		revision : "{host}/{_type}s/{name}/tiddlers/{title}/revisions/{revision}",
		search   : "{host}/search?q={query}"
	}
};

var convertTimestamp, supplant;

// host (optional) is the URI of the originating TiddlyWeb instance
tw.Resource = function(type, host) {
	if(arguments.length) { // initialization
		this._type = type;
		if(host !== false) {
			this.host = host !== undefined ? host.replace(/\/$/, "") : null;
		}
	}
};
$.extend(tw.Resource.prototype, {
	// retrieves resource from server
	// callback is passed resource, status, XHR (cf. jQuery.ajax success)
	// errback is passed XHR, error, exception, resource (cf. jQuery.ajax error)
	// filters is an optional filter string (e.g. "select=tag:foo;limit=5")
	get: function(callback, errback, filters) {
		var uri = this.route();
		if(filters) {
			var separator = uri.indexOf("?") === -1 ? "?" : ";";
			uri += separator + filters;
		}
		var self = this;
		return $.ajax({
			url: uri,
			type: "GET",
			dataType: "json",
			success: function(data, status, xhr) {
				var resource = self.parse(data);
				resource.etag = xhr.getResponseHeader("Etag");
				callback(resource, status, xhr);
			},
			error: function(xhr, error, exc) {
				errback(xhr, error, exc, self);
			}
		});
	},
	// sends resource to server
	// callback is passed data, status, XHR (cf. jQuery.ajax success)
	// errback is passed XHR, error, exception, resource (cf. jQuery.ajax error)
	put: function(callback, errback) {
		var self = this;
		var options = {
			url: this.route(),
			type: "PUT",
			contentType: "application/json",
			data: JSON.stringify(this.baseData()),
			success: function(data, status, xhr) {
				callback(self, status, xhr);
			},
			error: function(xhr, error, exc) {
				errback(xhr, error, exc, self);
			}
		};
		if(this.ajaxSetup) {
			this.ajaxSetup(options);
		}
		return $.ajax(options);
	},
	// deletes resource on server
	// callback is passed data, status, XHR (cf. jQuery.ajax success)
	// errback is passed XHR, error, exception, resource (cf. jQuery.ajax error)
	"delete": function(callback, errback) {
		var self = this;
		var options = {
			url: this.route(),
			type: "DELETE",
			success: function(data, status, xhr) {
				callback(self, status, xhr);
			},
			error: function(xhr, error, exc) {
				errback(xhr, error, exc, self);
			}
		};
		if(this.ajaxSetup) {
			this.ajaxSetup(options);
		}
		return $.ajax(options);
	},
	// returns an object carrying only the essential information of the resource
	baseData: function() {
		var data = {},
			self = this;
		$.each(this.data, function(i, item) {
			var value = self[item];
			if(value !== undefined) {
				data[item] = value;
			}
		});
		return data;
	},
	// returns corresponding instance from a raw object (if applicable)
	parse: function(data) {
		return data;
	},
	// list of accepted keys in serialization
	data: [],
	// returns resource's URI
	route: function() {
		return supplant(tw.routes[this._type], this);
	}
});

var Container = function(type, name, host) {
	if(arguments.length) { // initialization
		tw.Resource.apply(this, [type, host]);
		this.name = name;
		this.desc = "";
		this.policy = new tw.Policy({});
	}
};
Container.prototype = new tw.Resource();
$.extend(Container.prototype, {
	tiddlers: function() {
		return new tw.TiddlerCollection(this);
	},
	parse: function(data) {
		var type = tw._capitalize(this._type),
			container = new tw[type](this.name, this.host);
		data.policy = new tw.Policy(data.policy);
		return $.extend(container, data);
	},
	data: ["desc", "policy"]
});

// attribs is an object whose members are merged into the instance (e.g. query)
tw.Collection = function(type, host, attribs) {
	if(arguments.length) { // initialization
		tw.Resource.apply(this, [type, host]);
		$.extend(this, attribs);
	}
};
tw.Collection.prototype = new tw.Resource();

tw.TiddlerCollection = function(container, tiddler) {
	if(arguments.length) { // initialization
		tw.Collection.apply(this, [tiddler ? "revisions" : "tiddlers"]);
		this.container = container || null;
		this.tiddler = tiddler || null;
	}
};
tw.TiddlerCollection.prototype = new tw.Collection();
$.extend(tw.TiddlerCollection.prototype, {
	parse: function(data) {
		var container = this.container;
		return $.map(data, function(item, i) {
			var tiddler = new tw.Tiddler(item.title, container),
				bag = item.bag;
			tiddler = tw.Tiddler.prototype.parse.apply(tiddler, [item]);
			if(!tiddler.bag &amp;&amp; bag) { // XXX: bag always present!?
				tiddler.bag = new tw.Bag(bag, container.host);
			}
			if(!tiddler.recipe &amp;&amp; item.recipe) {
				tiddler.recipe = new tw.Recipe(item.recipe, container.host);
			}
			delete item.recipe;
			return $.extend(tiddler, item);
		});
	},
	route: function() {
		var params = this.container;
		if(this.tiddler) {
			var container = this.tiddler.bag || this.tiddler.recipe;
			params = {
				_type: container._type,
				host: container.host,
				name: container.name,
				title: this.tiddler.title
			};
		}
		return supplant(tw.routes[this._type], params);
	}
});

tw.Search = function(query, host) {
	tw.Collection.apply(this, ["search", host]);
	this.query = query;
};
tw.Search.prototype = new tw.Collection();
$.extend(tw.Search.prototype, {
	parse: function(data) {
		this.container = { // XXX: hacky
			_type: "bag",
			host: this.host
		};
		var tiddlers = tw.TiddlerCollection.prototype.parse.apply(this, arguments);
		delete this.container;
		return tiddlers;
	}
});

// title is the name of the tiddler
// container (optional) is an instance of either Bag or Recipe
// optionally accepts a single object representing tiddler attributes
tw.Tiddler = function(title, container) {
	tw.Resource.apply(this, ["tiddler", false]);
	this.title = title;
	this.bag = container &amp;&amp; container._type === "bag" ? container : null;
	this.recipe = container &amp;&amp; container._type === "recipe" ? container : null;
	var self = this;
	$.each(this.data, function(i, item) {
		self[item] = undefined; // exposes list of standard attributes for inspectability
	});
	if(title &amp;&amp; title.title) { // title is an object of tiddler attributes
		$.extend(this, title);
	}
};
tw.Tiddler.prototype = new tw.Resource();
$.extend(tw.Tiddler.prototype, {
	revisions: function() {
		return new tw.TiddlerCollection(this.bag || this.recipe, this);
	},
	route: function() {
		var container = this.bag || this.recipe;
		var params = $.extend({}, this, {
			host: container ? container.host : null,
			_type: this.bag ? "bag" : (this.recipe ? "recipe" : null),
			name: container ? container.name : null
		});
		return supplant(tw.routes[this._type], params);
	},
	parse: function(data) {
		var tiddler = new tw.Tiddler(this.title),
			container = this.bag || this.recipe;
		if(data.bag) {
			tiddler.bag = new tw.Bag(data.bag, container.host);
			delete data.bag;
		}
		delete data.recipe;
		tiddler.created = data.created ? convertTimestamp(data.created) : new Date();
		delete data.created;
		tiddler.modified = data.modified ? convertTimestamp(data.modified) : new Date();
		delete data.modified;
		if(this.recipe) {
			tiddler.recipe = this.recipe;
		}
		return $.extend(tiddler, data);
	},
	data: ["created", "creator", "modifier", "modified", "tags", "type", "text",
			"fields"],
	ajaxSetup: function(options) {
		var self = this;
		if(this.etag &amp;&amp; (options.type === "PUT" || options.type === "DELETE")) {
			options.beforeSend = function(xhr) {
				xhr.setRequestHeader("If-Match", self.etag);
			};
		}
		if(options.type === "PUT") {
			var callback = options.success;
			options.success = function(data, status, xhr) {
				var loc = xhr.getResponseHeader("Location"),
					etag = xhr.getResponseHeader("Etag");
				if(loc &amp;&amp; etag) {
					self.etag = etag;
					if(!self.bag) {
						var bag = loc.split("/bags/").pop().split("/")[0];
						self.bag = new tw.Bag(bag, self.recipe.host);
					}
					callback(self, status, xhr);
				} else { // IE
					self.get(callback, options.error);
				}
			};
		}
	}
});

tw.Revision = function(id, tiddler) {
	var container = tiddler.bag || tiddler.recipe;
	tw.Tiddler.apply(this, [tiddler.title, container]);
	this._type = "revision";
	this.revision = id;
};
tw.Revision.prototype = new tw.Tiddler();
$.extend(tw.Revision.prototype, {
	revisions: false,
	data: false,
	put: false,
	"delete": false
});

tw.Bag = function(name, host) {
	Container.apply(this, ["bag", name, host]);
};
tw.Bag.prototype = new Container();

tw.Recipe = function(name, host) {
	Container.apply(this, ["recipe", name, host]);
	this.recipe = [];
};
tw.Recipe.prototype = new Container();
$.extend(tw.Recipe.prototype, {
	data: ["recipe"].concat(Container.prototype.data)
});

tw.Policy = function(constraints) { // TODO: validation?
	var self = this;
	$.each(this.constraints, function(i, item) {
		self[item] = constraints[item];
	});
};
tw.Policy.prototype.constraints = ["read", "write", "create", "delete",
	"manage", "accept", "owner"];

/*
 * utilities
 */

tw._capitalize = function(str) {
	return str.charAt(0).toUpperCase() + str.slice(1);
};

// convert YYYYMMDDhhmmss timestamp to Date instance
convertTimestamp = function(t) {
	if (t.match(/^\d{12,17}$/)) {
		return new Date(Date.UTC(
			parseInt(t.substr(0, 4), 10),
			parseInt(t.substr(4, 2), 10) - 1,
			parseInt(t.substr(6, 2), 10),
			parseInt(t.substr(8, 2), 10),
			parseInt(t.substr(10, 2), 10),
			parseInt(t.substr(12, 2) || "0", 10),
			parseInt(t.substr(14, 3) || "0", 10)
		));
	} else {
		return new Date(Date.parse(t));
	}
};

// adapted from Crockford (http://javascript.crockford.com/remedial.html)
supplant = function(str, obj) {
	return str.replace(/{([^{}]*)}/g, function (a, b) {
		var r = obj[b];
		r = typeof r === "string" || typeof r === "number" ? r : a;
		return $.inArray(b, ["host", "query"]) !== -1 ? r : encodeURIComponent(r); // XXX: special-casing
	});
};

return tw;

}(jQuery));
//}}}</pre>
</div>
<div title="favicon.ico" server.title="favicon.ico" server.page.revision="1521895" server.etag="&quot;tiddlyspace/favicon.ico/1521895:c19c2ac7085de9626623c777e48ee91bf1be18ff&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/tiddlyspace" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="tiddlyspace" server.permissions="read" server.content-type="image/x-icon" modified="20131111192334" created="20131111192334" tags="excludeLists excludeSearch" _hash="d884f6069c2350d026d57c45dc100c1390bd6112">
<pre>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AP8zZgAAAGYA//8zAADMMwD/mTMAAGYzAP8zMwAAADMAzP8AAADMAADMmQAAAGYAAMwzAAAAAADuzAAA3QAAALvMAACqAAAAiMwAAHcAAABVmQAARAAAACKZAAARAADuAJkA3QAAALsAmQCqAAAAiACZAHcAAABVAJkARAAAACIAZgARAADuAABm3QAAALsAAGaqAAAAiAAAZncAAABVAABmRAAAACIAAGYRAAAA7u7uM93d3QC7u7szqqqqAIiIiDN3d3cAVVVVM0RERAAiIiIzERERAAAAADMBAQEBAQEBAQEBpXl5eXl5eXl5eXmlAQEBAQEBAQEBAQEBAQEBAQEBgHl5eXl5eXl5eXl5eXl5gAEBAQEBAQEBAQEBAQEB/Xp5eXlVT04qKioqTk9VeXl5ev0BAQEBAQEBAQEBAaV5eXlPKioqKioqKioqKioqT3l5eaUBAQEBAQEBAQGAeXlVTioqKioqKioqKioqKioqTlV5eYABAQEBAQEBgHl5VSoqKioqKioqKioqKioqKioqKlV5eYABAQEBAaV5eVUqKioqKioqKioqKioqKioqKioqKlV5eaUBAQEBeXlVKioqKioqKioqKioqKioqKioqKioqKlV5eQEBAXl5eU4qKioqKioqKjExMTExMSoqKioqKioqTnl5eQEBeXlPKioqKioqKjEyMjIyMjIyMjEqKioqKioqT3l5AXp5eSoqKioqKioxMjIxBwcHBzEyMjEqKioqKioqeXl6eXlVKioqKioqMTIxBwcHBwcHBwcxMjEqKioqKipVeXl5eU8qKioqKioyMgcHBwcHBwcHBwcyMioqKioqKk95eXl5TioqKioqMTIxBwcHBwcHBwcHBzEyMSoqKioqTnl5eXkqKioqKioxMgcHBwcHBwcHBwcHBzIxKioqKioqeXl5eSoqKioqKjEyBwcHBwcHBwcHBwcHMjEqKioqKip5eXl5KioqKioqMTIHBwcHBwcHBwcHBwcyMSoqKioqKnl5eXkqKioqKioxMgcHBwcHBwcHBwcHBzIxKioqKioqeXl5eU4qKioqKjEyMQcHBwcHBwcHBwcxMjEqKioqKk55eXl5TyoqKioqKjIyBwcHBwcHBwcHBzIyKioqKioqT3l5eXlVKioqKioqMTIxBwcHBwcHBwcxMjEqKioqKipVeXl6eXkqKioqKioqMTIyMQcHBwcxMjIxKioqKioqKnl5egF5eU8qKioqKioqMTIyMjIyMjIyMSoqKioqKipPeXkBAXl5eU4qKioqKioqKjExMTExMSoqKioqKioqTnl5eQEBAXl5VSoqKioqKioqKioqKioqKioqKioqKipVeXkBAQEB+nl5VSoqKioqKioqKioqKioqKioqKioqVXl5+gEBAQEBenl5VSoqKioqKioqKioqKioqKioqKlV5eXoBAQEBAQEBeXl5VU4qKioqKioqKioqKioqKk5VeXl5AQEBAQEBAQEBenl5eU8qKioqKioqKioqKipPeXl5egEBAQEBAQEBAQEB+nl5eXlVT04qKioqTk9VeXl5efoBAQEBAQEBAQEBAQEBAXl5eXl5eXl5eXl5eXl5eXkBAQEBAQEBAQEBAQEBAQEBAQF6eXl5eXl5eXl5eXoBAQEBAQEBAQEB/+AH//+AAf/+AAB//AAAP/gAAB/wAAAP4AAAB8AAAAPAAAADgAAAAYAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAgAAAAYAAAAHAAAADwAAAA+AAAAfwAAAP+AAAH/wAAD/+AAB//4AB///gB/8oAAAAIAAAAEAAAAABACAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQAAAAEAAAACAAAAAwAAAAMAAAADAAAABG1bSA61m3JXuqB4mbuhd8m9o3jqvaF4+b2hePm9o3jqu6F3ybqgeJm1m3JXbVtIDgAAAAQAAAADAAAAAwAAAAMAAAACAAAAAQAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEAAAACAAAAAwAAAAUAAAAGAAAACI98Wye0nXWavKF4876kev++pHr/vqR6/76kev++pHr/vqR6/76kev++pHr/vqR6/76kev+8oXjztJ11mo98WycAAAAIAAAABgAAAAUAAAADAAAAAgAAAAEAAAAAAAAAAAAAAAAAAAABAAAAAgAAAAQAAAAHAAAAChwcHBKulnGJvaN5+L6kev++pHr/y7GJ/9/Fnv/s1K7/9t25//rivv/64r7/9t25/+zUrv/fxZ7/y7GJ/76kev++pHr/vaN5+K6WcYkcHBwSAAAACgAAAAcAAAAEAAAAAgAAAAEAAAAAAAAAAAAAAAEAAAADAAAABwAAAAtuYkUst552z76kev++pHr+1LuS//Latf/85cD//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//zlwP/85cD/8tq1/9S7kv++pHr+vqR6/7eeds9uYkUsAAAACwAAAAcAAAADAAAAAQAAAAAAAAABAAAAAgAAAAQAAAAIi3hbNbqgd+a+pHr/xayD/+3Vr//85cD//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA/+3Vr//FrIP/vqR6/7qgd+aJdVg0AAAACAAAAAQAAAACAAAAAQAAAAEAAAACAAAABIl8WSW8oXjlvqR6/8yyiv/54Lz//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//ngvP/Msor/vqR6/7yheOWJfFklAAAABAAAAAIAAAABAAAAAAAAAAFfXz8Iu6F4zL6kev/Msor/+uK+//zlwP/85cD//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//rivv/Msor/vqR6/7uheMxfXz8IAAAAAQAAAAAAAAAAAAAAAbqid4K+pHr/xayD//ngvP/85cD//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//fgvP/FrIP/vqR6/7qid4IAAAABAAAAAAAAAAC3l28gvaN5+L6kev7t1a///OXA//zlwP/85cD//OXA//zlwP/85cD//OXA/+/Twv/Qq8f/u5HK/7OGzP+zhsz/u5HK/9Crx//v08L//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA/+3Vr/++pHr+vaN5+LeXbyAAAAAAAAAAALuheJa+pHr/1LuS//zlwP/85cD//OXA//zlwP/85cD//OXA//riwP/Pq8f/r4HM/6+Bzf+vgc3/r4HN/6+Bzf+vgc3/r4HN/6+BzP/Pq8f/+uLA//zlwP/85cD//OXA//zlwP/85cD//OXA/9S5kv++pHr/u6F4lgAAAACii3MLvKF4876kev/y2rX//OXA//zlwP/85cD//OXA//zlwP/64sD/w5vJ/6+Bzf+vg83/w5vc/9W06v/dwPD/3cDw/9W06v/Dm9z/r4PN/6+Bzf/Dm8n/+uLA//zlwP/85cD//OXA//zlwP/85cD/8tq1/76kev+8oXjzootzC72feFW+pHr/y7GJ//zlwP/85cD//OXA//zlwP/85cD//OXA/8+rx/+vgc3/tIfQ/9a16//hw/P/4cPz/+HD8//hw/P/4cPz/+HD8//Wtev/tIfQ/6+Bzf/Pq8f//OXA//zlwP/85cD//OXA//zlwP/85cD/y7GJ/76kev+9n3hVvaF4mL6kev/fxZ7//OXA//zlwP/85cD//OXA//zlwP/v08L/r4HM/6+Dzf/Wtev/4cPz/+HD8//hw/P/4cPz/+HD8//hw/P/4cPz/+HD8//Wtev/r4PN/6+BzP/v08L//OXA//zlwP/85cD//OXA//zlwP/fxZ7/vqR6/72heJi8oXfIvqR6/+zUrv/85cD//OXA//zlwP/85cD//OXA/9Crx/+vgc3/w5vc/+HD8//hw/P/4cPz/+HD8//hw/P/4cPz/+HD8//hw/P/4cPz/+HD8//Dm9z/r4HN/9Crx//85cD//OXA//zlwP/85cD//OXA/+zUrv++pHr/vKF3yL2jeOq+pHr/9t25//zlwP/85cD//OXA//zlwP/85cD/u5HK/6+Bzf/VtOr/4cPz/+HD8//hw/P/4cPz/+HD8//hw/P/4cPz/+HD8//hw/P/4cPz/9W06v+vgc3/u5HK//zlwP/85cD//OXA//zlwP/85cD/9t25/76kev+9o3jqvaF4+b6kev/64r7//OXA//zlwP/85cD//OXA//zlwP+zhsz/r4HN/93A8P/hw/P/4cPz/+HD8//hw/P/4cPz/+HD8//hw/P/4cPz/+HD8//hw/P/3cDw/6+Bzf+zhsz//OXA//zlwP/85cD//OXA//zlwP/64r7/vqR6/72hePm9oXj5vqR6//rivv/85cD//OXA//zlwP/85cD//OXA/7OGzP+vgc3/3cDw/+HD8//hw/P/4cPz/+HD8//hw/P/4cPz/+HD8//hw/P/4cPz/+HD8//dwPD/r4HN/7OGzP/85cD//OXA//zlwP/85cD//OXA//rivv++pHr/vaF4+b2jeOq+pHr/9t25//zlwP/85cD//OXA//zlwP/85cD/u5HK/6+Bzf/VtOr/4cPz/+HD8//hw/P/4cPz/+HD8//hw/P/4cPz/+HD8//hw/P/4cPz/9W06v+vgc3/u5HK//zlwP/85cD//OXA//zlwP/85cD/9t25/76kev+9o3jqvKF3yL6kev/s1K7//OXA//zlwP/85cD//OXA//zlwP/Qq8f/r4HN/8Ob3P/hw/P/4cPz/+HD8//hw/P/4cPz/+HD8//hw/P/4cPz/+HD8//hw/P/w5vc/6+Bzf/Qq8f//OXA//zlwP/85cD//OXA//zlwP/s1K7/vqR6/7yhd8i9oXiYvqR6/9/Fnv/85cD//OXA//zlwP/85cD//OXA/+/Twv+vgcz/r4PN/9a16//hw/P/4cPz/+HD8//hw/P/4cPz/+HD8//hw/P/4cPz/9a16/+vg83/r4HM/+/Twv/85cD//OXA//zlwP/85cD//OXA/9/Fnv++pHr/vaF4mL2feFW+pHr/y7GJ//zlwP/85cD//OXA//zlwP/85cD//OXA/8+rx/+vgc3/tIfQ/9a16//hw/P/4cPz/+HD8//hw/P/4cPz/+HD8//Wtev/tIfQ/6+Bzf/Pq8f//OXA//zlwP/85cD//OXA//zlwP/85cD/y7GJ/76kev+9n3hVootzC7yhePO+pHr/8tq1//zlwP/85cD//OXA//zlwP/85cD/+uLA/8Obyf+vgc3/r4PN/8Ob3P/VtOr/3cDw/93A8P/VtOr/w5vc/6+Dzf+vgc3/w5vJ//riwP/85cD//OXA//zlwP/85cD//OXA//Latf++pHr/vKF486KLcwsAAAAAu6N3l76kev/Uu5L//OXA//zlwP/85cD//OXA//zlwP/85cD/+uLA/8+rx/+vgcz/r4HN/6+Bzf+vgc3/r4HN/6+Bzf+vgc3/r4HM/8+rx//64sD//OXA//zlwP/85cD//OXA//zlwP/85cD/1LmS/76kev+7oXiWAAAAAAAAAAC3l28gvaN5+L6kev7t1a///OXA//zlwP/85cD//OXA//zlwP/85cD//OXA/+/Twv/Qq8f/u5HK/7OGzP+zhsz/u5HK/9Crx//v08L//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA/+3Vr/++pHr+vaN5+LeXbyAAAAAAAAAAAAAAAAC6oneCvqR6/8Wsg//54Lz//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//zlwP/34Lz/xayD/76kev+6oneCAAAAAAAAAAAAAAAAAAAAAH9/VQa8oHjLvqR6/8yyiv/64r7//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//zlwP/85cD/+uK+/8yyiv++pHr/vKB4y39/VQYAAAAAAAAAAAAAAAAAAAAAAAAAALKhbh67o3nkvqR6/8yyiv/54Lz//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//ngvP/Msor/vqR6/7ujeeSyoW4eAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAALqbdim7o3nkvqR6/8Wsg//t1a///OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//zlwP/t1a//xayD/76kev+7o3nkupt2KQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAALKhbh68oHjLvqR6/76kev7Uu5L/8tq1//zlwP/85cD//OXA//zlwP/85cD//OXA//zlwP/85cD//OXA//zlwP/y2rX/1LmS/76kev6+pHr/vKB4y7Khbh4AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAH9/VQa6oneCvaN5+L6kev++pHr/y7GJ/9/Fnv/s1K7/9t25//rivv/64r7/9t25/+zUrv/fxZ7/y7GJ/76kev++pHr/vaN5+Lqid4J/f1UGAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAC3l28gu6F4lryhePO+pHr/vqR6/76kev++pHr/vqR6/76kev++pHr/vqR6/76kev++pHr/vKF487uheJa3l28gAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAootzC72feFW9oXiYvKF3yL2jeOq9oXj5vaF4+b2jeOq8oXfIvaF4mL2feFWii3MLAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAP/gB///gAH//gAAf/wAAD/4AAAf8AAAD+AAAAfAAAADwAAAA4AAAAGAAAABAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAIAAAAGAAAABwAAAA8AAAAPgAAAH8AAAD/gAAB/8AAA//gAAf/+AAf//4Af/</pre>
</div>
<div title="BinaryUploadPlugin" server.title="BinaryUploadPlugin" server.page.revision="1521860" server.etag="&quot;system-plugins_public/BinaryUploadPlugin/1521860:985e872a66d48f284c47fb5cb05d4c37a1c74555&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-plugins_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-plugins_public" server.permissions="read" server.content-type="text/javascript" modified="20131111192330" created="20131111192330" tags="excludeLists excludeSearch systemConfig" _hash="fa2a79fa940254cf1cdd7980c85b5efd0eff0ce5">
<pre>/***
|''Name''|BinaryUploadPlugin|
|''Version''|0.3.16|
|''Author''|Ben Gillies and Jon Robson|
|''Type''|plugin|
|''Source''|http://github.com/TiddlySpace/tiddlyspace/raw/master/src/plugins/BinaryUploadPlugin.js|
|''Description''|Upload a binary file to TiddlyWeb|
|''CoreVersion''|2.6.1|
|''Requires''|TiddlySpaceConfig TiddlyWebConfig|
!Usage
{{{
&lt;&lt;binaryUpload bag:&lt;name&gt; edit:tags edit:title tags:&lt;default tags&gt; title:&lt;title&gt; &gt;&gt;
}}}
* {{{bag:&lt;name&gt;}}}: optional; if left out, the file will be saved to the current workspace
* {{{edit:tags}}}: specifies that you want to tag the file being uploaded
* {{{edit:title}}}: specifies that you want to set the title to something other than the filename
* {{{tags:&lt;default tags&gt;}}}: specifies a default set of tags to apply to the file (requires {{{edit:tags}}} to be set)
* {{{title:&lt;title&gt;}}}: predefines the title of the binary tiddler
!Requires
TiddlyWeb
tiddlywebplugins.form
!Code
***/
//{{{
(function($) {

var tiddlyspace = config.extensions.tiddlyspace;

var macro = config.macros.binaryUpload = {
	locale: {
		titleDefaultValue: "Please enter a title...",
		tagsDefaultValue: "Please enter some tags...",
		titlePrefix: "title: ",
		tagsPrefix: "tags: ",
		loadSuccess: 'Tiddler %0 successfully uploaded',
		loadError: "An error occurred when uploading the tiddler %0",
		uploadInProgress: "Please wait while the file is uploaded...",
		membersOnly: "Only members can upload."
	},
	renderInputFields: function(container, options) {
		var locale = macro.locale;
		var editableFields = options.edit;
		var includeFields = {
			tags:  editableFields &amp;&amp; editableFields.contains("tags") ? true : false,
			title: editableFields &amp;&amp; editableFields.contains("title") ? true : false
		};
		var fields = ["title", "tags"];
		for(var i = 0; i &lt; fields.length; i++) {
			var fieldName = fields[i];
			var userDefault = options[fieldName];
			var defaultValue = userDefault ? userDefault[0] : false;
			if(includeFields[fieldName] || defaultValue) {
				var localeDefault = locale["%0DefaultValue".format(fieldName)];
				var className = defaultValue ? "userInput" : "userInput notEdited";
				var inputEl;
				var val = defaultValue || localeDefault || "";
				var iContainer = $("&lt;div /&gt;").addClass("binaryUpload%0".format(fieldName)).
					appendTo(container);
				if(defaultValue &amp;&amp; !includeFields[fieldName]) {
					var label = locale["%0Prefix".format(fieldName)];
					$("&lt;span /&gt;").text(label).appendTo(iContainer);
					$("&lt;span /&gt;").addClass("disabledInput").text(val).appendTo(iContainer);
					inputEl = $("&lt;input /&gt;").attr("type", "hidden");
				} else {
					inputEl = $("&lt;input /&gt;").attr("type", "text");
				}
				inputEl.attr("name", fieldName).
					addClass("%0Edit".format(fieldName)).
					val(val).addClass(className).appendTo(iContainer);
			}
		}
	},
	getTiddlerName: function(fileName) {
		var fStart = fileName.lastIndexOf("\\");
		var fStart2 = fileName.lastIndexOf("/");
		fStart = fStart &lt; fStart2 ? fStart2 : fStart;
		fileName = fileName.substr(fStart+1);
		return fileName;
	},
	errorHandler: function(fileName) {
		displayMessage("upload of file %0 failed".format(fileName));
	},
	uploadFile: function(place, baseURL, workspace, options) {
		var pleaseWait = $(".uploadProgress", place);
		var iframeName = options.target;
		var form = $("form", place);
		var existingVal = $("input[name=title]", form).val();
		var fileName = existingVal || $('input:file', form).val();
		if(!fileName) {
			return false; // the user hasn't selected a file yet
		}
		fileName = macro.getTiddlerName(fileName);
		$("input[name=title]", place).val(fileName);
		// we need to go somewhere afterwards to ensure the onload event triggers
		var redirectTo = "/%0/tiddlers.txt?select=title:%1".
			format(workspace, fileName);
		var token = tiddlyspace ? tiddlyspace.getCSRFToken() : "";
		var action = "%0?csrf_token=%1&amp;redirect=%2"
			.format(baseURL, token, redirectTo);
		form[0].action = action; // dont use jquery to work with ie
		form[0].target = iframeName;
		// do not refactor following line... won't work in IE6 otherwise
		$(place).append($('&lt;iframe name="' + iframeName + '" id="' + iframeName + '"/&gt;').css('display','none'));
		macro.iFrameLoader(iframeName, function() {
			var content = document.getElementById(iframeName).contentWindow.document.documentElement;
			if($(content).text().indexOf(fileName) &gt; -1) {
				options.callback(place, fileName, workspace, baseURL);
			} else {
				macro.errorHandler(fileName);
			}
			form.show(1000);
			pleaseWait.hide(1000);
		});
		form.hide(1000);
		pleaseWait.show(1000);
		return true;
	},
	createUploadForm: function(place, options) {
		var locale = macro.locale;
		if(readOnly) {
			$('&lt;div class="annotation" /&gt;').text(locale.membersOnly).
				appendTo(place);
			return;
		}
		var bag = options.bag;
		options.callback = options.callback ? options.callback :
			function(place, fileName, workspace, baseurl) {
				macro.displayFile(place, fileName, workspace);
				displayMessage(locale.loadSuccess.format(fileName));
				$("input[type=text]", place).val("");
			};
		var defaults = config.defaultCustomFields;
		place = $("&lt;div /&gt;").addClass("container").appendTo(place)[0];
		var workspace = bag ? "bags/%0".format(bag) : config.defaultCustomFields["server.workspace"];
		var baseURL = defaults["server.host"];
		baseURL += (baseURL[baseURL.length - 1] !== "/") ? "/" : "";
		baseURL = "%0%1/tiddlers".format(baseURL, workspace);
		//create the upload form, complete with invisible iframe
		var iframeName = "binaryUploadiframe%0".format(Math.random());
		// do not refactor following line of code to work in IE6.
		var form = $('&lt;form action="%0" method="POST" enctype="multipart/form-data" /&gt;'.
					format(baseURL)).addClass("binaryUploadForm").
			appendTo(place)[0];
		macro.renderInputFields(form, options);
		$(form).
			append('&lt;div class="binaryUploadFile"&gt;&lt;input type="file" name="file" /&gt;&lt;/div&gt;').
			append('&lt;div class="binaryUploadSubmit"&gt;&lt;input type="submit" value="Upload" disabled /&gt;&lt;/div&gt;').
			submit(function(ev) {
				this.target = iframeName;
				options.target = iframeName;
				macro.uploadFile(place, baseURL, workspace, options);
			})
			.find('[type="file"]').bind('change', function() {
				$(form).find('[type="submit"]').prop('disabled', false);
			}).end();
		$('&lt;div /&gt;').addClass("uploadProgress").text(locale.uploadInProgress).hide().appendTo(place);
		$("input[name=file]", place).change(function(ev) {
			var target = $(ev.target);
			var fileName = target.val();
			var title = $("input[type=text][name=title]", place);
			if(!title.val()) {
				title.val(fileName);
			}
		});
	},
	handler: function(place, macroName, params, wikifier, paramString, tiddler) {
		params = paramString.parseParams(null, null, true);
		macro.createUploadForm(place, params[0]);
	},
	iFrameLoader: function(iframeName, callback) {
		var iframe = document.getElementById(iframeName); //jQuery doesn't seem to want to do this!?
		var locale = macro.locale;
		$(".userInput").addClass("notEdited"); // reset editing
		var finishedLoading = function() {
			callback();
		};
		var iFrameLoadHandler = function() {
			finishedLoading.apply();
			return;
		};

		iframe.onload = iFrameLoadHandler;
		//IE
		completeReadyStateChanges = 0;
		iframe.onreadystatechange = function() {
			if (++(completeReadyStateChanges) == 3) {
				iFrameLoadHandler();
			}
		};
	},
	displayFile: function(place, title, workspace) {
		var adaptor = store.getTiddlers()[0].getAdaptor();
		var context = {
			workspace: workspace,
			host: config.defaultCustomFields['server.host']
		};
		adaptor.getTiddler(title, context, null, function(context) {
			if(context.status) {
				store.addTiddler(context.tiddler);
				story.displayTiddler(place, title);
				var image = config.macros.image;
				if(image &amp;&amp; image.refreshImage) {
					image.refreshImage("/%0/tiddlers/%1".format(workspace, title));
					image.refreshImage(title);
					image.refreshImage("/%0".format(title));
					image.refreshImage("%0/%1/tiddlers/%2".format(config.extensions.tiddlyweb.host, workspace, title));
				}
			} else {
				displayMessage(macro.locale.loadError.format(title));
			}
		});
	}
};

if(tiddlyspace) {
	config.macros.binaryUploadPublic = {
		handler: function(place, macroName, params, wikifier, paramString, tiddler) {
			var options = paramString.parseParams(null, null, true)[0];
			var bag = tiddlyspace.getCurrentBag("public");
			options.bag = bag;
			macro.createUploadForm(place, options);
		}
	};
	config.messages.privacySetting = config.options.chkPrivateMode ?
		"private" : "public";
	config.macros.binaryUpload.defaultWorkspace = tiddlyspace.
		getCurrentWorkspace(config.messages.privacySetting);
}

})(jQuery);
//}}}</pre>
</div>
<div title="apps" server.title="apps" server.page.revision="1521891" server.etag="&quot;tiddlyspace/apps/1521891:e8f15909ef2b5c3885670d8f4bb206931dd5fa2f&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/tiddlyspace" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="tiddlyspace" server.permissions="read" server.content-type="text/html" modified="20131111192332" created="20131111192332" tags="excludeLists excludeSearch" _hash="901ce9fdbc458a92f3643134f0bd968fc1f69cb1">
<pre>&lt;!DOCTYPE html&gt;
&lt;html lang="en"&gt;
&lt;head&gt;
	&lt;meta charset="utf-8"/&gt;
	&lt;title&gt;TiddlySpace Apps&lt;/title&gt;
	&lt;link rel="stylesheet" href="/bags/common/tiddlers/reset.css" /&gt;
	&lt;link rel="stylesheet" href="/bags/common/tiddlers/appspage.css" /&gt;
	&lt;!--[if lt IE 7 ]&gt;
	&lt;link rel="stylesheet" href="/bags/common/tiddlers/appspageie6.css" /&gt;
	&lt;![endif]--&gt;
&lt;/head&gt;
&lt;body&gt;
	
	&lt;div id="wrapper"&gt;
		&lt;div id="TSbar"&gt;&lt;/div&gt;
		&lt;div id="main-content"&gt;
			&lt;div id="space-details"&gt;
				&lt;a href="/_space"&gt;&lt;img class="siteicon"&gt;&lt;/a&gt;
				&lt;div id="title-subtitle"&gt;
					&lt;h1 class="spaceaddress"&gt;
						&lt;span class="spaceName"&gt;&lt;/span&gt;&lt;span class="hostName"&gt;&lt;/span&gt;
					&lt;/h1&gt;
					&lt;p class="tagline"&gt;&lt;span class="subTitle"&gt;&lt;/span&gt;&lt;a class="managespaces" href="/_space"&gt;manage space&lt;/a&gt;&lt;/p&gt;
				&lt;/div&gt;
			&lt;/div&gt;
			&lt;div id="holder"&gt;
				&lt;div id="appswitcher-wrapper"&gt;
					&lt;div id="appswitcher"&gt;
						&lt;h2&gt;Your Apps&lt;/h2&gt;
						&lt;ul id="app-list"&gt;
							&lt;li class="htmlserialisation"&gt;
								&lt;a href="/tiddlers.html?select=tag:!excludeLists;sort=-modified"&gt;
									&lt;img src="/bags/common/tiddlers/browse_read_blue.png" alt="Icon for the HTML Serialisation" class="app-img" /&gt;
									BROWSE
								&lt;/a&gt;
							&lt;/li&gt;
							&lt;li class="tiddlywiki"&gt;
								&lt;a href="/tiddlers.wiki"&gt;
									&lt;img src="/bags/common/tiddlers/tiddlywiki2_blue.png" alt="Icon for TiddlyWiki" class="app-img" /&gt;
									TIDDLYWIKI
								&lt;/a&gt;
							&lt;/li&gt;
						&lt;/ul&gt;
						&lt;div id="addapp"&gt;
							&lt;button class="inactive"&gt;Add More!&lt;/button&gt;
						&lt;/div&gt;
					&lt;/div&gt;
					&lt;div id="app-desc"&gt;
						&lt;ul&gt;
							&lt;li class="htmlserialisationdesc"&gt;&lt;p&gt;an easy to understand HTML representation of your content.&lt;/p&gt;&lt;/li&gt;
							&lt;li class="tiddlywikidesc"&gt;&lt;p&gt;use TiddlyWiki to create, edit and organise your content.&lt;/p&gt;&lt;/li&gt;
						&lt;/ul&gt;
					&lt;/div&gt;
					&lt;div style="clear: both;"&gt;&lt;/div&gt;
				&lt;/div&gt;
			&lt;/div&gt;
		&lt;/div&gt;
		&lt;div id="footer"&gt;&lt;!-- ie doesn't support footer tag --&gt;
			&lt;div id="footer-content"&gt;
				&lt;div class="links"&gt;
					&lt;a href="http://blog.tiddlyspace.com"&gt;blog&lt;/a&gt;
					&lt;a href="http://featured.tiddlyspace.com"&gt;featured&lt;/a&gt;
					&lt;a href="http://docs.tiddlyspace.com"&gt;documentation&lt;/a&gt;
					&lt;a href="https://github.com/TiddlySpace/tiddlyspace"&gt;source&lt;/a&gt;
				&lt;/div&gt;
				&lt;p&gt;TiddlySpace 2011, created by &lt;a href="http://osmosoft.com"&gt;Osmosoft&lt;/a&gt;&lt;/p&gt;
			&lt;/div&gt;
		&lt;/div&gt;
	&lt;/div&gt;
	
	&lt;script type="text/javascript" src="/bags/common/tiddlers/backstage.js"&gt;&lt;/script&gt;
	&lt;script type="text/javascript" src="/bags/common/tiddlers/jquery.js"&gt;&lt;/script&gt;
	&lt;script type="text/javascript" src="/bags/tiddlyspace/tiddlers/chrjs"&gt;&lt;/script&gt;
	&lt;script type="text/javascript" src="/bags/common/tiddlers/chrjs-store.js"&gt;&lt;/script&gt;
	&lt;script type="text/javascript" src="/bags/common/tiddlers/jquery-json.js"&gt;&lt;/script&gt;
	&lt;script type="text/javascript" src="/bags/common/tiddlers/appspage.js"&gt;&lt;/script&gt;
&lt;/body&gt;
&lt;/html&gt;</pre>
</div>
<div title="PageTemplate" server.title="PageTemplate" server.page.revision="1521914" server.etag="&quot;system-theme_public/PageTemplate/1521914:530a5ee39812af7e4c7128914c31eb8f726660cd&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-theme_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-theme_public" server.permissions="read" server.content-type="" modified="20131111192330" created="20131111192330" tags="excludeLists excludeSearch" _hash="f7d57de5937a110a2d275d11eebcd4557fc34f25">
<pre>&lt;!--{{{--&gt;
&lt;div class='header'&gt;
	&lt;div id='sidebarSearch'&gt;
		&lt;span macro='search'&gt;&lt;/span&gt;
	&lt;/div&gt;
	&lt;div class='headerForeground'&gt;
		&lt;span class='siteTitle' refresh='content' tiddler='SiteTitle'&gt;&lt;/span&gt;
		&lt;span class='siteSubtitle' refresh='content' tiddler='SiteSubtitle'&gt;&lt;/span&gt;
	&lt;/div&gt;
	&lt;div class='clearFloat'&gt;&lt;/div&gt;
&lt;/div&gt;

&lt;div id='menuBar'&gt;
	&lt;div id='mainMenu' refresh='content' tiddler='MainMenu'&gt;&lt;/div&gt;
	&lt;div id='sidebarOptions' refresh='content' tiddler='SideBarOptions'&gt;&lt;/div&gt;
&lt;/div&gt;
&lt;div id='displayArea'&gt;
	&lt;div id='messageArea'&gt;&lt;/div&gt;
	&lt;div id='tiddlerDisplay'&gt;&lt;/div&gt;
	&lt;div id='sidebarTabs' refresh='content' force='true' tiddler='SideBarTabs'&gt;&lt;/div&gt;
&lt;/div&gt;
&lt;!--}}}--&gt;</pre>
</div>
<div title="首页" server.title="首页" server.page.revision="2579914" server.etag="&quot;honly-666_public/%E9%A6%96%E9%A1%B5/2579914:b8f3b38966ba76f993f85dc1f6ece1224fe9c0ba&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20161102044431" created="20161102044229" tags="" _hash="5dda853131b3c5192974d0c54f4565782fd6d578">
<pre>&lt;html&gt;
&lt;head&gt;
&lt;title&gt;泽海之鲸&lt;/title&gt;
&lt;/head&gt;

&lt;body&gt;
&lt;marquee&gt;&lt;div align="center"&gt;&lt;font color="red"face="楷体"size="6"&gt;“人生就像心电图，必须折腾起来！”&lt;/font&gt;&lt;br/&lt;div/&gt;&lt;/marquee&gt;&lt;br/&gt;
&lt;div align="center"&gt;&gt;&lt;img src="http://p0.so.qhmsg.com/t0183cba81fd2a593b0.gif"height="400" width="600"/&gt;&lt;/div&gt;
&lt;br/&gt;&lt;br/&gt;



&lt;/body&gt;




&lt;/html&gt;</pre>
</div>
<div title="TiddlySpaceInit" server.title="TiddlySpaceInit" server.page.revision="1521909" server.etag="&quot;tiddlyspace/TiddlySpaceInit/1521909:55cb4d39f45bdcda693c8574fa6e2f5146e7af55&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/tiddlyspace" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="tiddlyspace" server.permissions="read" server.content-type="text/javascript" modified="20131111192332" created="20131111192332" tags="excludeLists excludeSearch systemConfig" _hash="05e5325df4a93506529425c558842d5953dd6a44">
<pre>/***
|''Name''|TiddlySpaceInitialization|
|''Version''|0.7.3|
|''Description''|Initializes new TiddlySpaces the first time they are created|
|''Status''|@@beta@@|
|''Source''|http://github.com/TiddlySpace/tiddlyspace/blob/master/src/plugins/TiddlySpaceInit.js|
|''CoreVersion''|2.6.1|
|''Requires''|TiddlySpaceConfig RandomColorPalettePlugin chrjs ImageMacroPlugin|
!TODO
* robust error notification and recovery
!MarkupPreHead
&lt;!--{{{--&gt;
&lt;link href="/bags/%0_public/tiddlers.atom" rel="alternate"
	type="application/atom+xml" title="%0's public feed" /&gt;
&lt;link rel="canonical" href="%1/" /&gt;
&lt;!--}}}--&gt;
!Code
***/
//{{{
(function($) {

var versionField = "tiddlyspaceinit_version";
var markupPreHead = store.getTiddlerText(tiddler.title + "##MarkupPreHead", "");
var tiddlyspace = config.extensions.tiddlyspace;
var currentSpace = tiddlyspace.currentSpace;
var tweb = config.extensions.tiddlyweb;

var plugin = config.extensions.TiddlySpaceInit = {
	version: "0.6",
	SiteTitle: "%0",
	SiteSubtitle: "a TiddlySpace",
	flagTitle: "%0SetupFlag",
	flagWarning: "Please do not modify this tiddler; it was created " +
		"automatically upon space creation.",

	dispatch: function(ev) {
		var title = plugin.flagTitle.format([currentSpace.name]);
		config.annotations[title] = plugin.flagWarning;
		if(currentSpace.type != "private") {
			return;
		}
		var tiddlers = [];
		var tid = store.getTiddler(title);
		if(tid) {
			curVersion = parseFloat(tid.fields[versionField]);
			reqVersion = parseFloat(plugin.version);
			if(curVersion &lt; reqVersion) {
				plugin.update(curVersion, tid);
				tid.fields[versionField] = plugin.version;
				tid.incChangeCount();
				tid = store.saveTiddler(tid);
				tiddlers.push(tid);
			}
		} else { // first run
			tid = new Tiddler(title);
			tid.tags = ["excludeLists", "excludeSearch", "excludePublisher"];
			tid.fields = $.extend({}, config.defaultCustomFields);
			tid.fields[versionField] = plugin.version;
			tid.text = "@@%0@@".format([plugin.flagWarning]);
			tid = store.saveTiddler(tid);
			tiddlers = tiddlers.concat(plugin.firstRun(), tid);
		}
		autoSaveChanges(null, tiddlers);
	},
	update: function(curVersion, flagTiddler) {
		if(curVersion &lt; 0.2) {
			this.createAvatar();
		}
		if(curVersion &lt; 0.3) {
			flagTiddler.tags.pushUnique("excludePublisher"); // XXX: never persisted
		}
		if(curVersion &lt; 0.5) { // v0.4 was faulty
			this.setupMarkupPreHead();
		}
		if(curVersion &lt; 0.6) {
			this.purgeSystemSettings();
		}
	},
	pubTid: {
		tags: ["excludeLists", "excludeSearch"],
		fields: $.extend({}, config.defaultCustomFields, {
			"server.workspace": tiddlyspace.getCurrentWorkspace("public")
		})
	},
	makeTiddlerIfNot: function(tiddler) {
		if (!store.tiddlerExists(tiddler.title)) {
			$.extend(true, tiddler, plugin.pubTid);
			return [store.saveTiddler(tiddler)];
		} else {
			return [];
		}
	},
	firstRun: function() {
		var tiddlers = [];
		// generate Site*itle
		$.each(["SiteTitle", "SiteSubtitle"], function(i, item) {
			var tid = new Tiddler(item);
			tid.text = plugin[item].format([currentSpace.name]);
			tiddlers.push.apply(tiddlers,
				plugin.makeTiddlerIfNot(tid));
		});
		// generate public ColorPalette
		var tid = new Tiddler("ColorPalette");
		tid.text = config.macros.RandomColorPalette.generatePalette({
			saturation_pale: 0.67, saturation_light: 0.53,
			saturation_mid: 0.43, saturation_dark: 0.06,
			pale: 0.99, light: 0.85, mid: 0.5, dark: 0.31
		},
			false);
		tiddlers.push.apply(tiddlers, plugin.makeTiddlerIfNot(tid));
		this.createAvatar();
		this.setupMarkupPreHead();
		return tiddlers;
	},
	// remove _cookie slices (TiddlyWiki 2.6.2 beta 6 remnants)
	purgeSystemSettings: function() {
		var ss = store.getTiddler("SystemSettings");
		if(ss) {
			var lines = ss.text.split("\n");
			var persistentOptions = $.grep(lines, function(line, i) {
				return line.indexOf("_cookie:") == -1;
			});
			ss.text = persistentOptions.join("\n");
			ss = store.saveTiddler(ss);
			autoSaveChanges(null, [ss]);
		}
	},
	createAvatar: function() {
		var avatar = "SiteIcon";
		var host = tweb.host;
		var notify = function(xhr, error, exc) {
			displayMessage("ERROR: could not create avatar - " + // TODO: i18n
				"%0: %1".format([xhr.statusText, xhr.responseText]));
			// TODO: resolve!?
		};

		var pubBag = tiddlyspace.getCurrentBag("public");
		var tid = new tiddlyweb.Tiddler(avatar);
		tid.bag = new tiddlyweb.Bag(pubBag, host);

		var callback = function(data, status, xhr) {}; // avatar already exists; do nothing
		var errback = function(xhr, error, exc) {
			if(xhr.status != 404) {
				return;
			}
			// copy default avatar
			var _notify = function(tid, status, xhr) {
				displayMessage("created avatar"); // TODO: i18n
				var image = config.macros.image;
				if(image &amp;&amp; image.refreshImage) {
					var uri = "/%0/tiddlers/SiteIcon".
						format(tiddlyspace.getCurrentWorkspace("public"));
					image.refreshImage(uri);
					image.refreshImage("SiteIcon");
				}
			};
			var _callback = function(tid, status, xhr) {
				tid.title = avatar;
				tid.bag.name = pubBag;
				delete tid.etag;
				tid.put(_notify, notify); // TODO: add to current session document (via adaptor?)
			};
			tweb.getUserInfo(function(user) {
				var avatarTitle = currentSpace.name == user.name ?
					"defaultUserIcon" : "defaultSiteIcon";
				var tid = new tiddlyweb.Tiddler(avatarTitle);
				tid.bag = new tiddlyweb.Bag("common", host);
				tid.get(_callback, notify);
			});
		};
		tid.get(callback, errback);
	},
	savePublicTiddlerText: function(title, text, pubWorkspace) {
		var tid = new Tiddler(title);
		tid.text = text;
		tid.tags = ["excludeLists"];
		tid.fields = $.extend({}, config.defaultCustomFields);
		tid.fields["server.workspace"] = pubWorkspace;
		tid.fields["server.page.revision"] = "false";
		tid = store.saveTiddler(tid);
		autoSaveChanges(null, [tid]);
	},
	setupMarkupPreHead: function() {
		var pubWorkspace = tiddlyspace.getCurrentWorkspace("public");
		var existing = store.getTiddler("MarkupPreHead");
		if(!existing || existing.fields["server.workspace"] != pubWorkspace) {
			var context = this;
			tweb.getStatus(function(status) {
				var text = markupPreHead.format(currentSpace.name,
					tiddlyspace.getHost(status.server_host, currentSpace.name));
				context.savePublicTiddlerText("MarkupPreHead", text,
					pubWorkspace);
			});
		}
		// also set up DefaultTiddlers
		var title = "DefaultTiddlers";
		existing = store.getTiddler(title) || new Tiddler(title);
		if(existing.fields["server.workspace"] != pubWorkspace) {
			var text = existing.text || store.getShadowTiddlerText(title);
			this.savePublicTiddlerText(title, text, pubWorkspace);
		}
	}
};

$(document).bind("startup", plugin.dispatch);

})(jQuery);
//}}}</pre>
</div>
<div title="privateNotPublicIcon" server.title="privateNotPublicIcon" server.page.revision="1521893" server.etag="&quot;tiddlyspace/privateNotPublicIcon/1521893:b037432027b13d99c8e502ac05839304d472b07b&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/tiddlyspace" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="tiddlyspace" server.permissions="read" server.content-type="image/png" modified="20131111192334" created="20131111192334" tags="excludeLists excludeSearch" _hash="ec84c2619af08b1c361984baa4e8e871e8ce8946">
<pre>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</pre>
</div>
<div title="TiddlySpaceLinkPlugin" server.title="TiddlySpaceLinkPlugin" server.page.revision="1521865" server.etag="&quot;system-plugins_public/TiddlySpaceLinkPlugin/1521865:7163662f876e7bd0a3b4bae220905cf8e2752563&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-plugins_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-plugins_public" server.permissions="read" server.content-type="text/javascript" modified="20131111192330" created="20131111192330" tags="excludeLists excludeSearch systemConfig" _hash="b88cfa8ccd99b328c34b54aa9371c8f9ce02ffaf">
<pre>/***
|''Name:''|TiddlySpaceLinkPlugin|
|''Description:''|Formatter to reference other spaces from wikitext |
|''Author:''|PaulDowney (psd (at) osmosoft (dot) com) |
|''Source:''|http://github.com/TiddlySpace/tiddlyspace/raw/master/src/plugins/TiddlySpaceLinkPlugin.js|
|''Version:''|1.4.2|
|''License:''|[[BSD License|http://www.opensource.org/licenses/bsd-license.php]] |
|''Comments:''|Please make comments at http://groups.google.co.uk/group/TiddlyWikiDev |
|''~CoreVersion:''|2.4|
!!Documentation
This plugin provides wikitext formatters for referencing another [[space|Space]] on the same TiddlySpace server, as in the following examples:
&lt;&lt;&lt;
  {{{@space}}} -- @space 
  {{{~@space}}} -- ~@space 
  {{{Tiddler@space}}} -- Tiddler@space
  {{{[[Tiddler Title]]@space}}} -- [[Tiddler Title]]@space 
  {{{[[Link text|Tiddler Title]]@space}}} -- [[Link text|Tiddler Title]]@space
&lt;&lt;&lt;
Links to tiddlers with a title begining with an "@" remain as tiddlyLinks:
&lt;&lt;&lt;
  {{{[[@tiddler]]}}} -- [[@tiddler]]
&lt;&lt;&lt;
and these may be changed into a space link using {{{@@}}}:
&lt;&lt;&lt;
  {{{[[@@space]]}}} -- [[@@space]]
  {{{[[Link to an another space|@@space]]}}} -- [[Link to another space|@@space]]
  {{{[[@space|@@space]]}}} -- [[@space|@@space]]
&lt;&lt;&lt;
TiddlySpace includes the [[TiddlySpaceLinkPlugin]] which provides WikiText markup for linking to other spaces on the same server. For example @glossary is a link to the {{{glossary}}} space and [[Small Trusted Group]]@glossary a link to an individual tiddler in the @glossary space. Prefixing the link with a tilde escapes the link, for example {{{~@space}}}.
Email addresses, for example joe.bloggs@example.com and mary@had.a.little.lamb.org should be unaffected.
!!Features
The plugin provides external links decorated so that other plugins may be included to add features such as the ability to dynamically pull externally linked tiddlers into the current TiddlyWiki.
Wikitext linking to a space on another server, for example from a tiddler in a space on tiddlyspace.com to a tiddler or a space on example.com, isn't currently supported. 
!!Code
***/
//{{{
/*jslint onevar: false nomen: false plusplus: false */
/*global jQuery config createTiddlyText createExternalLink createTiddlyLink */

function createSpaceLink(place, spaceName, title, alt, isBag) {
	var link, a, currentSpaceName, label;
	try {
		if (spaceName === config.extensions.tiddlyspace.currentSpace.name) {
			title = title || spaceName;
			a = createTiddlyLink(place, title, false);
			jQuery(a).text(alt || title);
			return a;
		}
	} catch (ex1) {
		currentSpaceName = false;
	}

	a = jQuery("&lt;a /&gt;").addClass('tiddlySpaceLink externalLink').appendTo(place)[0];
	if(title) {
		jQuery(a).attr('tiddler', title);
	}
	if(isBag) {
		jQuery(a).attr('bag', spaceName);
	} else {
		jQuery(a).attr('tiddlyspace', spaceName);
	}

	config.extensions.tiddlyweb.getStatus(function(status) {
		link = status.server_host.url;
		if (title) {
			label = alt || title;
			link = link + "/" + encodeURIComponent(title);
		} else {
			label = alt || spaceName;
		}
		// assumes a http URI without user:pass@ prefix
		if(!isBag) {
			link = link.replace("http://", "http://" + spaceName.toLowerCase() + ".");
		} else {
			link += "/bags/" + spaceName + "/tiddlers.wiki";
		}
		jQuery(a).attr("href", link).text(label);
	});
	return a;
}

(function ($) {

	config.textPrimitives.spaceName = "[a-zA-Z][a-zA-Z0-9-]*[a-zA-Z0-9]";
	config.textPrimitives.spaceNameStrict = "[a-z][a-z0-9-]*";
	config.textPrimitives.bareTiddlerLetter = config.textPrimitives.anyLetterStrict;

	config.formatters.splice(0, 0, {
		name: "spacenameLink",
		match: config.textPrimitives.unWikiLink + "?" + config.textPrimitives.bareTiddlerLetter + "*@" + config.textPrimitives.spaceName + "\\.?.?",
		lookaheadRegExp: new RegExp(config.textPrimitives.unWikiLink + "?(" + config.textPrimitives.bareTiddlerLetter + "*)@(" + config.textPrimitives.spaceName + ")", "mg"),
		handler: function (w) {
			if (w.matchText.substr(w.matchText.length - 2, 1) === '.' &amp;&amp; w.matchText.substr(w.matchText.length - 1, 1).match(/[a-zA-Z]/)) {
				w.outputText(w.output, w.matchStart, w.nextMatch);
				return;
			}
			if (w.matchText.substr(0, 1) === config.textPrimitives.unWikiLink) {
				w.outputText(w.output, w.matchStart + 1, w.nextMatch);
				return;
			}
			this.lookaheadRegExp.lastIndex = w.matchStart;
			var lookaheadMatch = this.lookaheadRegExp.exec(w.source);
			if (lookaheadMatch &amp;&amp; lookaheadMatch.index === w.matchStart) {
				createSpaceLink(w.output, lookaheadMatch[2], lookaheadMatch[1]);
				w.nextMatch = this.lookaheadRegExp.lastIndex;
			}
		}
	},
	{
		name: "tiddlySpaceLink",
		match: "\\[\\[[^\\|\\]]*\\|*@@" + config.textPrimitives.spaceName + "\\]",
		lookaheadRegExp: new RegExp("\\[\\[(.*?)(?:\\|@@(.*?))?\\]\\]", "mg"),
		handler: function (w) {
			this.lookaheadRegExp.lastIndex = w.matchStart;
			var lookaheadMatch = this.lookaheadRegExp.exec(w.source);
			if (lookaheadMatch &amp;&amp; lookaheadMatch.index === w.matchStart) {
				var alt = lookaheadMatch[2] ? lookaheadMatch[1] : lookaheadMatch[1].replace(/^@@/, "");
				var space = lookaheadMatch[2] || alt;
				createSpaceLink(w.output, space, "", alt);
				w.nextMatch = this.lookaheadRegExp.lastIndex;
			}
		}
	},
	{
		name: "tiddlyLinkSpacenameLink",
		match: "\\[\\[[^\\[]*\\]\\]@",
		lookaheadRegExp: new RegExp("\\[\\[(.*?)(?:\\|(.*?))?\\]\\]@(" + config.textPrimitives.spaceName + ")", "mg"),
		handler: function (w) {
			this.lookaheadRegExp.lastIndex = w.matchStart;
			var lookaheadMatch = this.lookaheadRegExp.exec(w.source);
			if (lookaheadMatch &amp;&amp; lookaheadMatch.index === w.matchStart) {
				var title = lookaheadMatch[2] || lookaheadMatch[1];
				var alt = lookaheadMatch[1] || lookaheadMatch[2];
				createSpaceLink(w.output, lookaheadMatch[3], title, alt);
				w.nextMatch = this.lookaheadRegExp.lastIndex;
			}
		}
	});

	// ensure space links don't appear as missing links
	config.textPrimitives.brackettedLink = "\\[\\[([^\\]][^@\\]][^\\]]*)\\]\\](?=[^@])";
	config.textPrimitives.titledBrackettedLink = "\\[\\[([^\\[\\]\\|]+)\\|([^\\[\\]\\|]+)\\]\\](?=[^@])";

	// reevaluate derrived expressions ..
	config.textPrimitives.tiddlerForcedLinkRegExp = new RegExp("(?:" + config.textPrimitives.titledBrackettedLink + ")|(?:" +
		config.textPrimitives.brackettedLink + ")|(?:" +
		config.textPrimitives.urlPattern + ")","mg");
	config.textPrimitives.tiddlerAnyLinkRegExp = new RegExp("("+ config.textPrimitives.wikiLink + ")|(?:" +
		config.textPrimitives.titledBrackettedLink + ")|(?:" +
		config.textPrimitives.brackettedLink + ")|(?:" +
		config.textPrimitives.urlPattern + ")","mg");

	// treat space links in titledBracketedLink as external links
	var missingTiddlySpaceLink = new RegExp("^@@" + config.textPrimitives.spaceName + "$", "");
	var isExternalLink = config.formatterHelpers.isExternalLink;
	config.formatterHelpers.isExternalLink = function(link) {
		return missingTiddlySpaceLink.test(link) || isExternalLink(link);
	};

}(jQuery));
//}}}</pre>
</div>
<div title="音乐" server.title="音乐" server.page.revision="2579925" server.etag="&quot;honly-666_public/%E9%9F%B3%E4%B9%90/2579925:e64fed53824f5334337f867df9e5b4fcbe68dd5f&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20161102045446" created="20161102045438" tags="relex" _hash="fd5e1b6f58b2f898f65d13f395c879a9ca349427">
<pre>[[抒情流行乐]]</pre>
</div>
<div title="ToolbarCommands" server.title="ToolbarCommands" server.page.revision="1521884" server.etag="&quot;tiddlyspace/ToolbarCommands/1521884:40b0ca7af82398b899f2bba560c97891513bb383&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/tiddlyspace" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="tiddlyspace" server.permissions="read" server.content-type="" modified="20131111192334" created="20131111192334" tags="excludeLists excludeSearch" _hash="b4c48a116434073fe3dd125db8ac7616ac920c98">
<pre>|~ViewToolbar|+editTiddler +cloneTiddler &gt; fields refreshTiddler changeToPublic changeToPrivate revisions syncing permalink references jump closeOthers &lt; closeTiddler|
|~EditToolbar|+saveTiddler saveDraft -cancelTiddler deleteTiddler|
|~RevisionToolbar|&gt; fields revert|</pre>
</div>
<div title="unsyncedIcon" server.title="unsyncedIcon" server.page.revision="1521924" server.etag="&quot;system-images_public/unsyncedIcon/1521924:6c51a3cffdcd55c51718021fe5b7c11758593c76&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-images_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-images_public" server.permissions="read" server.content-type="image/png" modified="20131111192332" created="20131111192332" tags="excludeLists excludeSearch" _hash="f130b8a5de4a2cd9ab4d23a6fc3e9a8d83d1b7b3">
<pre>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</pre>
</div>
<div title="SiteSubtitle" server.title="SiteSubtitle" server.page.revision="2564087" server.etag="&quot;honly-666_public/SiteSubtitle/2564087:36fd16906f348260553c8fe478ce3ac1a860b51c&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20160923155818" created="20160923155818" tags="excludeLists excludeSearch" _hash="037a796b07f748584d280b286c6bd88ed85090cc">
<pre>a TiddlySpace</pre>
</div>
<div title="TiddlySpaceRevisionView" server.title="TiddlySpaceRevisionView" server.page.revision="1521859" server.etag="&quot;system-plugins_public/TiddlySpaceRevisionView/1521859:7acb4f882fb7a4f236a760e546849a9bc1807411&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-plugins_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-plugins_public" server.permissions="read" server.content-type="text/javascript" modified="20131111192330" created="20131111192330" tags="excludeLists excludeMissing excludeSearch systemConfig" _hash="be83cfafd902bff89908e6f74d71228655be3490">
<pre>/***
|''Name''|TiddlySpaceRevisionView|
|''Description''|Show tiddler revisions in a stack of cards view|
|''Author''|BenGillies|
|''Version''|0.2.0|
|''Status''|beta|
|''Source''|http://github.com/TiddlySpace/tiddlyspace|
|''CodeRepository''|http://github.com/TiddlySpace/tiddlyspace|
|''License''|[[BSD|http://www.opensource.org/licenses/bsd-license.php]]|
|''CoreVersion''|2.6.0|
|''Requires''|TiddlyWebAdaptor|
!Usage
The viewRevisions macro can be attached to any element, which should be passed
in as a parameter.

For example:

&amp;lt;&amp;lt;viewRevisions page:10 link:"&lt;&lt;view modified date&gt;&gt;"&amp;gt;&amp;gt;

would show the revisions "stack of cards" view, 10 at a time, when the modified
date is clicked.
!Code
***/
//{{{
(function($) {

var me = config.macros.viewRevisions = {
	revisionTemplate: "RevisionTemplate",
	revSuffix: " [rev. #%0]", // text to append to each tiddler title
	defaultPageSize: 5, // default number of revisions to show
	defaultLinkText: "View Revisions", // when there's nothing else to use
	offsetTop: 30, // in px
	offsetLeft: 10, // in px
	shiftDownDelay: 50, // in ms
	visibleSlideAmount: 20, // amount of revisions to show on left hand edge after sliding
	zIndex: 100, // default z-index
	handler: function(place, macroName, params, wikifier, paramString, tiddler) {
		params = paramString.parseParams(null, null, true)[0];
		var tiddlerElem = story.findContainingTiddler(place);

		var revButton;
		var pageSize = parseInt(params.page[0], 10) || me.defaultPageSize;
		var linkObj = params.link ? params.link[0] || me.defaultLinkText : false;
		if(linkObj) {
			revButton = $('&lt;span class="button openRevisions" /&gt;')
				.appendTo(place);
			wikify(linkObj, revButton[0], null, tiddler);
		} else {
			revButton = place;
		}

		$(revButton).click(function() {
			if (!$(tiddlerElem).hasClass("revisions")) {
				me.showRevisions(tiddlerElem, tiddler, pageSize);
			} else {
				me.closeRevisions(tiddlerElem);
			}
		});
	},

	// initialisation for revision view
	showRevisions: function(tiddlerElem, tiddler, pageSize) {
		var context = {
			host: tiddler.fields["server.host"],
			workspace: tiddler.fields["server.workspace"]
		};
		$(tiddlerElem).addClass("revisions").attr("revName", tiddler.title);
		// ensure toolbar commands deactivate RevisionsView
		$("a", ".toolbar", tiddlerElem).each(function(index, btn) {
			var _onclick = btn.onclick;
			btn.onclick = function(e) {
				me.closeRevisions(tiddlerElem);
				_onclick.apply(this, arguments);
			};
		});
		// ensure default action deactivates RevisionsView
		var _ondblclick = tiddlerElem.ondblclick;
		tiddlerElem.ondblclick = function(e) {
			me.closeRevisions(tiddlerElem);
			_ondblclick.apply(this, arguments);
		};
		var type = tiddler.fields["server.type"];
		var adaptor = new config.adaptors[type]();
		var userParams = {
			tiddlerElem: tiddlerElem,
			pageSize: pageSize,
			title: tiddler.title
		};
		me.createCloak(tiddlerElem);
		adaptor.getTiddlerRevisionList(tiddler.title, null, context, userParams,
				function(context, userParams) {
					// strip the current revision
					context.revisions.shift();
					me.expandStack(context, userParams);
				});
	},

	// fetch the actual revision and put it in the tiddler div
	showRevision: function(place, revision, callback) {
		var context = {
			host: revision.fields["server.host"],
			workspace: revision.fields["server.workspace"]
		};
		var userParams = {
			revElem: place
		};
		var type = revision.fields["server.type"];
		var adaptor = new config.adaptors[type]();
		var revNo = revision.fields["server.page.revision"];
		adaptor.getTiddlerRevision(revision.title, revNo, context, userParams,
			function(context, userParams) {
				var tiddler = context.tiddler;
				tiddler.title += me.revSuffix
					.format([$(place).attr("revision")]);
				tiddler.fields.doNotSave = true;
				if (store.getTiddler(tiddler.title)) {
					store.deleteTiddler(tiddler.title);
				}
				store.addTiddler(tiddler);

				//now, populate the existing div
				var revElem = userParams.revElem;
				$(revElem).attr("id", story.tiddlerId(tiddler.title));
				$(revElem).attr("refresh", "tiddler");
				var getTemplate = function() {
					var themeName = config.options.txtTheme;
					if (themeName) {
						return store.getTiddlerSlice(themeName,
							me.revisionTemplate) || me.revisionTemplate ||
							"ViewTemplate";
					} else {
						return (store.getTiddler(me.revisionTemplate)) ?
							me.revisionTemplate : "ViewTemplate";
					}
				};
				var template = getTemplate();
				story.refreshTiddler(tiddler.title, template, true);
				callback(tiddler);
			});
	},

	createCloak: function(promoteElem) {
		var el = $(promoteElem);
		// cache styles for resetting later
		el.data({
			top: el.css("top"),
			left: el.css("left"),
			zIndex: el.css("z-index")
		});

		$('&lt;div class="revisionCloak" /&gt;').css("z-index", me.zIndex)
			.click(function() {
				me.closeRevisions(promoteElem);
			})
			.appendTo(document.body);

		el.css("z-index", me.zIndex + 1);
	},

	// clean up, removing all evidence of revision view
	closeRevisions: function(promoteElem) {
		var el = $(promoteElem);
		// revert the original tiddler back to its previous state
		el.removeAttr("revName").removeClass("revisions").css({
			top: el.data("top"),
			left: el.data("left"),
			zIndex: el.data("zIndex")
		});

		// remove any revisions still in the store
		var revisions = $(".revisions");
		revisions.each(function(index, revision) {
			var revAttributes = revision.attributes;
			if ((revAttributes.revname) &amp;&amp;
					(revAttributes.revision)) {
				var revName = revAttributes.revname.value;
				var revNo = revAttributes.revision.value;
				var title = revName + me.revSuffix.format([revNo]);

				if (store.getTiddler(title)) {
					store.deleteTiddler(title);
				}
			}
		});

		// delete the previous revisions
		revisions.remove();

		// remove the cloak
		$(".revisionCloak").remove();
	},

	// calback from getting list of revisions
	expandStack: function(context, userParams) {
		var pageSize = userParams.pageSize;

		var from = userParams.from || 0;
		var tiddlerElem = userParams.tiddlerElem;

		userParams.defaultHeight = $(tiddlerElem).height();
		userParams.defaultWidth = $(tiddlerElem).width();
		if (from &lt; context.revisions.length) {
			me.displayNextRevision(tiddlerElem, userParams, context, from,
				from + pageSize - 1);
		}
	},

	// place the next div above and behind the previous one
	displayNextRevision: function(tiddlerElem, userParams, context, from, to) {
		var revision = context.revisions[from];
		var callback = function() {
			var revText = revBtn.getRevisionText(tiddlerElem, revision);
			tiddlerElem = me.createRevisionObject(tiddlerElem, context,
				userParams, revText);
			$(tiddlerElem)
				.attr("revision", (context.revisions.length - from));
			if ((from &lt; to) &amp;&amp; ((from + 1) &lt; context.revisions.length)){
				me.displayNextRevision(tiddlerElem, userParams, context,
					from + 1, to);
			} else if ((context.revisions.length - 1) &gt; to) {
				me.showMoreButton(tiddlerElem, context, userParams, to + 1);
			}
		};
		me.shiftVisibleDown(userParams.title, callback);
	},

	createRevisionObject: function(tiddlerElem, context, userParams, text) {
		var newPosition = me.calculatePosition(tiddlerElem, context);
		return $('&lt;div class="revisions tiddler" /&gt;')
			.css({
				position: "absolute",
				top: newPosition.top,
				left: newPosition.left,
				"z-index": me.zIndex + 1,
				height: userParams.defaultHeight,
				width: userParams.defaultWidth
			})
			.attr("revName", userParams.title)
			.append(text)
			.insertBefore(tiddlerElem);
	},

	// move the already present revisions down by 1 to fit the next one in
	shiftVisibleDown: function(title, callback) {
		var revisions = $("[revName='%0'].revisions".format([title]));
		var revisionCount = revisions.length;

		$(revisions).animate({top: "+=" + me.offsetTop},
				me.shiftDownDelay, function() {
					revisionCount -= 1;
					if ((callback) &amp;&amp; (!revisionCount)) {
						callback();
					}
				});
	},

	// where we put the new revision
	calculatePosition: function(elem, context) {
		var offset = $(elem).offset();
		var currentPosition = $(elem).position();
		var newPosition = {
			top: currentPosition.top - me.offsetTop
		};
		if ((context.restrictLeft) ||
				((offset.left - me.offsetLeft) &lt;
				$("#contentWrapper").offset().left)) {
			newPosition.left = $(elem).position().left;
			context.restrictLeft = true;
		} else {
			newPosition.left = currentPosition.left - me.offsetLeft;
		}
		return newPosition;
	},

	// equivalent of displayNextRevision, but for the more button
	showMoreButton: function(tiddlerElem, context, userParams, moreIndex) {
		userParams.from = moreIndex + 1;
		me.shiftVisibleDown(userParams.title, function() {
			var btn = me.createRevisionObject(tiddlerElem, context, userParams,
				"");

			var more = createTiddlyButton(btn[0], "more...", "show more revisions",
				function() {
					if ($(".viewRevision").length) {
						return;
					}
					userParams.tiddlerElem = btn[0];
					$(btn).text("")
						.append(revBtn
							.getRevisionText(btn[0], context.revisions[moreIndex]))
						.attr("revision", context.revisions.length - moreIndex);
					me.expandStack(context, userParams);
				});
			$(more).css("float", "right");
		});
	},

	stripRevFromTitle: function(revisionTitle) {
		return revisionTitle.split(/ ?\[rev\. #[0-9]+\]$/)[0];
	},

	onClickRevision: function(revElem, revision, callback) {
		// don't do anything if we are still loading
		if ($(".revisions").hasClass("loading")) {
			return null;
		}

		var origTitle = me.stripRevFromTitle(revision.title);
		if ($(revElem).hasClass("viewRevision")) {
			$(".revisions").addClass("loading");
			me.slideIn(revElem, revision, origTitle, function() {
				store.deleteTiddler(revision.title);
				revision.title = origTitle;
				$(revElem).text("").append(revBtn.getRevisionText(revElem,
						revision))
					.removeAttr("tags").removeAttr("tiddler")
					.removeAttr("refresh").removeAttr("template")
					.removeAttr("id");
				$(".revisions").removeClass("loading");
				if (callback) {
					callback();
				}
			});
			$(revElem).removeAttr("prevPos").removeClass("viewRevision");
		} else {
			var viewRevision = function() {
				var prevPos = $(revElem).position().left;
				$(revElem).addClass("viewRevision").attr("prevPos", prevPos);
				$(".revisions").addClass("loading");
				me.showRevision(revElem, revision, function(rev) {
					me.slideOut(revElem, rev, origTitle, function() {
						$(".revisions").removeClass("loading");
					});
				});
			};
			// make sure another revision isn't already out
			if ($(".viewRevision").length) {
				var newRevElem = $(".viewRevision")[0];
				var newRevision = store.getTiddler($(newRevElem)
					.attr("tiddler"));
				me.onClickRevision(newRevElem, newRevision, viewRevision);
			} else {
				viewRevision();
			}
		}
	},

	slideOut: function(revElem, revision, title, callback) {
		var leftMostPos = $("[revName='%0'].revisions".format([title]))
			.offset().left;
		var width = $(revElem).width();
		var originalLeftPos = $(story.getTiddler(title))
			.position().left;

		var slideAmount = leftMostPos + width - me.visibleSlideAmount;
		$("[revName='%0'].revisions:not(.viewRevision)".format([title]))
			.animate({left: "-=" + slideAmount}, 1000);
		$(revElem)
			.attr("baseHeight", $(revElem).css("height"))
			.css("height", "auto")
			.animate({left: originalLeftPos}, 1000, callback);
	},

	slideIn: function(revElem, revision, title, callback) {
		var slideAmount = $(revElem).offset().left -
			$(story.getTiddler(title)).offset().left;
		var origRevPos = $(revElem).attr("prevPos");

		$("[revName='%0'].revisions:not(.viewRevision)".format([title]))
			.animate({left: "+=" + slideAmount}, 1000);
		$(revElem).animate({left: origRevPos}, 1000, function() {
			$(revElem)
				.css("height", $(revElem).attr("baseHeight"))
				.removeAttr("baseHeight");
			callback();
		});
	}
};

var revBtn;
config.macros.slideRevision = revBtn = {
	btnText: "created by %0 at %1 on %2",
	handler: function(place, macroName, params, wikifier, paramString, tiddler) {
		var btn = revBtn.getRevisionText(place, tiddler);
		$(place).append(btn);
	},

	getRevisionText: function(place, revision) {
		var text = revBtn.btnText.format([revision.modifier,
			revision.modified.formatString("0hh:0mm"),
			revision.modified.formatString("0DD MMM YYYY")]);
		var btn = $('&lt;a href="javascript:;" class="button revButton" /&gt;')
			.text(text)
			.click(function() {
				var revElem = story.findContainingTiddler(this);
				me.onClickRevision(revElem, revision);
			});
		return btn;
	}
};

})(jQuery);
//}}}</pre>
</div>
<div title="StyleSheet" server.title="StyleSheet" server.page.revision="2566229" server.etag="&quot;honly-666_public/StyleSheet/2566229:cc2a22a1bf5106063833463d0cfc001a6e3d9e00&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20160927075524" created="20160924143428" tags="excludeSearch" _hash="3751be04aef94e6840e65a1447ccd9f1ae0b68be">
<pre>[[StyleSheetTiddlySpace]]
换颜色</pre>
</div>
<div title="喜剧总动员" server.title="喜剧总动员" server.page.revision="2579932" server.etag="&quot;honly-666_public/%E5%96%9C%E5%89%A7%E6%80%BB%E5%8A%A8%E5%91%98/2579932:5c22e429de54b20671d0c2f1068d493137479d43&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20161102050153" created="20161102050153" tags="" _hash="8a15299f1699e4e7b6ba6547aff3664e70338661">
<pre>http://www.360kan.com/va/ZsMnbXNw8ZQ5Ej.html</pre>
</div>
<div title="SiteTitle" server.title="SiteTitle" server.page.revision="2564009" server.etag="&quot;honly-666_public/SiteTitle/2564009:883bb3b07d1069112330ad9ebfe3f07e4bee1987&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20160923145518" created="20160906130629" tags="excludeLists excludeSearch" _hash="63200acfa4b86709c8ea4fc47f1f17036343e4d3">
<pre>别想的太多
做的太少</pre>
</div>
<div title="综艺" server.title="综艺" server.page.revision="2580030" server.etag="&quot;honly-666_public/%E7%BB%BC%E8%89%BA/2580030:8c230ba41cc022d3214edf9da49eee849c32ab1d&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20161102131533" created="20161102131533" tags="" _hash="7e5742246ccd4e6d161a62d6e23a5eda2bd0ebe4">
<pre>约吧，大明星！
http://baike.so.com/doc/23639304-24194215.html</pre>
</div>
<div title="TiddlySpaceToolbar" server.title="TiddlySpaceToolbar" server.page.revision="1521861" server.etag="&quot;system-plugins_public/TiddlySpaceToolbar/1521861:128a944e3c180c6f8f99800970773d06ddfa6bca&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-plugins_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-plugins_public" server.permissions="read" server.content-type="text/javascript" modified="20131111192330" created="20131111192330" tags="excludeLists excludeSearch systemConfig" _hash="f1d6038be5d1ecd8d107d604b0f0dce76bc901da">
<pre>/***
|''Name''|TiddlySpaceToolbar|
|''Description''|augments tiddler toolbar commands with SVG icons|
|''Author''|Osmosoft|
|''Version''|0.6.6|
|''Status''|@@beta@@|
|''Source''|http://github.com/TiddlySpace/tiddlyspace/raw/master/src/plugins/TiddlySpaceToolbar.js|
|''CodeRepository''|http://github.com/TiddlySpace/tiddlyspace|
|''License''|[[BSD|http://www.opensource.org/licenses/bsd-license.php]]|
|''CoreVersion''|2.5.0|
|''Requires''|ImageMacroPlugin|
|''Keywords''|toolbar icons SVG|
!Description
replaces tiddler toolbar commands with SVG icons if available
!Notes
requires [[ImageMacroPlugin|http://svn.tiddlywiki.org/Trunk/contributors/JonRobson/plugins/ImageMacroPlugin/plugins/ImageMacroPlugin.tid]]

SVG icons are drawn from tiddlers titled {{{&lt;command&gt;.svg}}}
In readonly mode a tiddler called {{{&lt;command&gt;ReadOnly.svg}}} will be used if it exists.
!TODO
* rename (IconToolbarPlugin?)
* support more than one more popup menu in the toolbar.
!Code
***/
//{{{
(function($) {

if(!config.macros.image) {
	throw "Missing dependency: ImageMacroPlugin";
}

var macro = config.macros.toolbar;

macro.icons = {
	cloneTiddler: "editTiddler"
};

var _handler = macro.handler;
macro.handler = function(place, macroName, params, wikifier,
		paramString, tiddler) {
	var toolbar = $(place);
	toolbar.attr({
		refresh: "macro",
		macroName: macroName
	}).data("args", arguments);
	var status = _handler.apply(this, arguments);
	if(tiddler.isReadOnly()) {
		toolbar.addClass("toolbarReadOnly");
	} else {
		toolbar.removeClass("toolbarReadOnly");
	}
	var parsedParams = paramString.parseParams("name")[0];
	if(parsedParams.icons &amp;&amp; parsedParams.icons == "yes") {
		this.augmentCommandButtons(place);
	}
	if(parsedParams.more &amp;&amp; parsedParams.more == "popup") {
		// note we must override the onclick event like in createTiddlyButton
		// otherwise the click event is the popup AND the slider
		$(".moreCommand", place).each(function(i, el) {
			el.onclick = macro.onClickMorePopUp;
		});
		// buttons that are after a less command should not be in more menu.
		$(".lessCommand ~ .button", place).appendTo(place);
		$(".lessCommand", place).remove();
	}
	return status;
};

macro.refresh = function(place, params) {
	var args = $(place).empty().data("args");
	this.handler.apply(this, args);
};

var imageMacro = config.macros.image;
macro.augmentCommandButtons = function(toolbar) {
	$(".button", toolbar).each(function(i, el) {
		var cmd = $(el).attr("commandname");
		cmd = cmd ? cmd : "moreCommand"; // XXX: special-casing of moreCommand due to ticket #1234
		var icon = store.tiddlerExists(cmd) ? cmd : macro.icons[cmd];
		var text = $(el).text();
		if(readOnly) {
			var readOnlyAlternative = "%0ReadOnly".format([icon]);
			if(store.tiddlerExists(readOnlyAlternative)) {
				icon = readOnlyAlternative;
			}
		}
		if(store.tiddlerExists(icon)) {
			$(el).css({display: "inline-block"}).empty();
			imageMacro.renderImage(el, icon, { alt: text });
		}
	});
};

// provide onClickMore to provide extra commands in a popup
macro.onClickMorePopUp = function(ev) {
	ev = ev || window.event;
	var sibling = this.nextSibling;
	if(sibling) {
		var commands = sibling.childNodes;
		var popup = Popup.create(this);
		$(popup).addClass("taggedTiddlerList");
		for(var i = 0; i &lt; commands.length; i++) {
			var li = createTiddlyElement(popup, "li", null);
			var oldCommand = commands[i];
			var command = oldCommand.cloneNode(true);
			command.onclick = oldCommand.onclick;
			li.appendChild(command);
		}
		Popup.show();
	}
	ev.cancelBubble = true;
	if(ev.stopPropagation) {
		ev.stopPropagation();
	}
	return false;
};

})(jQuery);
//}}}</pre>
</div>
<div title="honly-666SetupFlag" server.title="honly-666SetupFlag" server.page.revision="2580036" server.etag="&quot;honly-666_public/honly-666SetupFlag/2580036:87afeed08f8547eb7f64cc8852c5dfb540606e95&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20161102132052" created="20160923155818" tags="excludeLists excludePublisher excludeSearch" _hash="e606c5ef8ce0b27a28f7c6db14f8908446d8a817" tiddlyspaceinit_version="0.6">
<pre>@@Please do not modify this tiddler; it was created automatically upon space creation.@@
&lt;html&gt;

 &lt;body&gt;


&lt;embed src="http://img3.imgtn.bdimg.com/it/u=4132159228,3639712671&amp;fm=21&amp;gp=0.jpg
/multiPlayer.swf" type="application/x-shockwave-flash" width="400" height="300" wmode="opaque"&gt;&lt;/embed&gt;

&lt;div align="center"&gt;
&lt;h1&gt;&lt;marquee behavior=alternate&gt;
&lt;html&gt;

 &lt;body&gt;
</pre>
</div>
<div title="TiddlySpaceSearcher" server.title="TiddlySpaceSearcher" server.page.revision="1521908" server.etag="&quot;tiddlyspace/TiddlySpaceSearcher/1521908:d2076067be051d07f990cf4fdca7f31304659d5b&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/tiddlyspace" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="tiddlyspace" server.permissions="read" server.content-type="text/javascript" modified="20131111192332" created="20131111192332" tags="excludeLists excludeSearch systemConfig" _hash="e3762c200fa4b897f6e7bbb9e0e7d83f860a89a5">
<pre>/***
|''Name''|TiddlySpaceSearcher|
|''Version''|0.2.5|
|''Requires''|TiddlySpaceConfig TiddlySpaceFollowingPlugin|
***/
//{{{
(function($) {
var tiddlyspace = config.extensions.tiddlyspace;
var tsScan = config.macros.tsScan;

config.shadowTiddlers.SearchTemplate = "&lt;&lt;view server.bag SiteIcon label:no width:24 height:24 preserveAspectRatio:yes&gt;&gt; &lt;&lt;view server.bag spaceLink title external:no&gt;&gt; in space &lt;&lt;view server.bag spaceLink&gt;&gt;";
config.shadowTiddlers.StyleSheetSearch = [".resultsArea .siteIcon { display: inline; }",
	".searchForm {text-align: left;}"].join("\n");
store.addNotification("StyleSheetSearch", refreshStyles);

var search = config.macros.tsSearch = {
	locale: {
		advanced: "Advanced Options",
		header: "Search",
		resultsHeader: "Results (%0)",
		find: "find",
		noResults: "No tiddlers matched your search query",
		query: "QUERY: ",
		error: "please provide a search query or a tag, modifier or title!",
		titleAdvanced: "where the title is",
		modifierAdvanced: "where the last modifier is",
		spaceAdvanced: "only in the space: ",
		notspaceAdvanced: "but not in the spaces: ",
		tagsAdvanced: "with the tags: "
	},
	andConstructor: function(container, label, fieldname, negationMode) {
		var tags = $("&lt;div /&gt;").appendTo(container);
		$('&lt;span /&gt;').text(label).appendTo(tags);
		var id = "area" + Math.random();
		container = $("&lt;span /&gt;").attr("id", id).appendTo(tags)[0];
		function add(container) {
			var el = $('&lt;input type="text" /&gt;').attr("field", fieldname).appendTo(container);
			if(negationMode) {
				el.attr("negation", "true");
			}
		}
		add(container);
		var el = $("&lt;button /&gt;").text("AND").click(function(ev) {
			add($(ev.target).data("container"));
			ev.preventDefault();
		}).appendTo(tags);
		$(el).data("container", container);
	},
	fieldConstructor: function(container, label, field) {
		container = $("&lt;div /&gt;").appendTo(container)[0];
		$("&lt;span /&gt;").text(label).appendTo(container);
		$("&lt;input /&gt;").attr("text", "input").attr("field", field).appendTo(container);
	},
	advancedOptions: function(form) {
		var locale = search.locale;
		var container = $("&lt;div /&gt;").addClass("tsAdvancedOptions").appendTo(form)[0];
		$("&lt;h2/ &gt;").text(search.locale.advanced).appendTo(container);
		$("&lt;div /&gt;").addClass("separator").appendTo(container);
		search.fieldConstructor(container, locale.titleAdvanced, "title");
		search.fieldConstructor(container, locale.modifierAdvanced, "modifier");
		search.fieldConstructor(container, locale.spaceAdvanced, "space");
		search.andConstructor(container, locale.notspaceAdvanced, "space", true);
		search.andConstructor(container, locale.tagsAdvanced, "tag");
	},
	constructSearchQuery: function(form) {
		var data = [], select = [];
		var query = $("[name=q]", form).val();
		if(query) {
			data.push("q=%0".format(query));
		}

		// add tags, fields etc..
		$("[field]", form).each(function(i, el) {
			var val = $(el).val();
			var name = $(el).attr("field");
			var negate = $(el).attr("negation") == "true";
			if(val &amp;&amp; name) {
				val = encodeURIComponent(val);
				val = negate ? "!" + val : val;
				if(name == "space") {
					val += "_public";
					name = "bag";
				}
				if(negate) {
					select.push("select=%0:%1".format(name,val));
				} else {
					var prefix = data.length === 0 ? "q=" : "";
					data.push('%0%1:"%2"'.format(prefix, name, val));
				}
			}
		});
		var dataString = data.join(" ");
		if(dataString.length === 0 &amp;&amp; !query) {
			return false;
		}
		var selectStatement = select.join("&amp;");
		if(dataString.length &gt; 0 &amp;&amp; selectStatement.length &gt; 0) {
			dataString += "&amp;";
		}
		dataString += selectStatement;
		return "/search?%0".format(dataString);
	},
	constructForm: function(place) {
		var locale = search.locale;
		$("&lt;h1 /&gt;").text(locale.header).appendTo(place);
		var form = $("&lt;form /&gt;").appendTo(place)[0];
		$('&lt;input type="text" name="q" /&gt;').appendTo(form);
		$('&lt;input type="submit" /&gt;').val(locale.find).appendTo(form);
		search.advancedOptions(form);
		var query = $('&lt;h2 class="query"/&gt;').appendTo(place)[0];
		var results = $("&lt;div /&gt;").appendTo(place).addClass("resultsArea")[0];
		var lookup = function(url) {
			if(!url) {
				results.empty().addClass("error").text(locale.error);
				return;
			}
			config.extensions.tiddlyweb.getStatus(function(status) {
				$(query).text(locale.query);
				var href = status.server_host.url + url;
				$("&lt;a /&gt;").attr("href", href).text(href).appendTo(query);
				tsScan.scan(results, { url: url, emptyMessage: search.locale.noResults, cache: true,
					template: "SearchTemplate", sort: "title", callback: function(tiddlers) {
						$("&lt;h2 /&gt;").text(locale.resultsHeader.format(tiddlers.length)).prependTo(results);
					}
				});
			});
		};
		$(form).submit(function(ev) {
			ev.preventDefault();
			var url = search.constructSearchQuery(form);
			config.macros.tsSearch.lastSearch = url;
			lookup(url);
		});
		if(search.lastSearch) {
			lookup(search.lastSearch);
		}
		return form;
	},
	handler: function(place) {
		var container = $("&lt;div /&gt;").addClass("searchForm").appendTo(place)[0];
		search.constructForm(container);
	}
};

})(jQuery);
//}}}</pre>
</div>
<div title="Start writing" server.title="Start writing" server.page.revision="1521876" server.etag="&quot;system-info_public/Start%20writing/1521876:082fdf685d160894d20b5807797fee39fa4d07e1&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-info_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-info_public" server.permissions="read" server.content-type="" modified="20131111192330" created="20131111192330" tags="excludeLists excludeMissing excludeSearch" _hash="7d1a54121ab3a090a54dd263b3e45c3f7699f8ed">
<pre>Click the "new tiddler" button towards the top right of the screen to write something in your space. You'll need to give it a title, some content and, optionally, some tags that will help you identify it later.

!Stuck for ideas?
Not sure what to write about? Not sure what to keep in your space? Other people use ~TiddlySpace for almost anything. How about some of the following:

* [[Save interesting sites|http://bookmarks.tiddlyspace.com]], images or articles from around the web so that you can refer back to them.
* [[Record your family tree|http://familytree.tiddlyspace.com]], store notes on long lost relatives or ancestors and map their relationship to you.
* [[Make up a pocketbook|http://pocketbook.tiddlyspace.com]] to store some useful information in, then print it out, [[fold it up|http://www.pocketmod.com/]], and take it with you.
* [[Plan your holiday|http://the-web-is-your-oyster.tiddlyspace.com/]], record where you're planning to go, note down places of interest and refer back to it later.
* [[Create a mindmap|http://mindmaps.tiddlyspace.com/]] to visualise your inner thoughts and see how they relate to each other.
* [[Set up a questionnaire|http://questionnaire.tiddlyspace.com/]] and get all your friends to answer it.

If you don't like any of those ideas, you can still use this space directly to keep notes and link them together, make a todo list and keep track of everything you're doing, or any one of a hundred million other things.

Still stuck? Check out the @featured space for more suggestions.

You can also [[socialise with others|How to socialise]].</pre>
</div>
<div title="EditTemplate" server.title="EditTemplate" server.page.revision="2579007" server.etag="&quot;honly-666_public/EditTemplate/2579007:19c302650011e08e56a4690a75fad9ed7ef1194d&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_public" server.permissions="read, write, create, delete" server.content-type="" modified="20161030070208" created="20161030070155" tags="excludeSearch" _hash="7bb803a241092da630ce8f35962108d06c7b539b">
<pre>&lt;!--{{{--&gt;
&lt;div class='toolbar'
	macro='toolbar [[ToolbarCommands::EditToolbar]] icons:yes'&gt;
&lt;/div&gt;
&lt;div class='heading editorHeading'&gt;
	&lt;div class='editor title' macro='edit title'&gt;&lt;/div&gt;
	&lt;div class='tagClear'&gt;&lt;/div&gt;
&lt;/div&gt;
&lt;div class='annotationsBox' macro='annotations'&gt;
	&lt;div class='editSpaceSiteIcon'
		macro='tiddlerOrigin height:16 width:16 label:no interactive:no'&gt;
	&lt;/div&gt;
	&lt;div class="privacyEdit" macro='setPrivacy label:no interactive:no'&gt;&lt;/div&gt;
	&lt;div class='tagClear'&gt;&lt;/div&gt;
&lt;/div&gt;

&lt;div class='editor' macro='edit text'&gt;&lt;/div&gt;
&lt;div class='editorFooter'&gt;
	&lt;div class='tagTitle'&gt;tags&lt;/div&gt;
	&lt;div class='editor' macro='edit tags'&gt;&lt;/div&gt;
	&lt;div class='tagAnnotation'&gt;
		&lt;span macro='message views.editor.tagPrompt'&gt;&lt;/span&gt;
		&lt;span macro='tagChooser excludeLists'&gt;&lt;/span&gt;
	&lt;/div&gt;
&lt;/div&gt;
&lt;!--}}}--&gt;</pre>
</div>
<div title="TiddlySpaceFilters" server.title="TiddlySpaceFilters" server.page.revision="1521906" server.etag="&quot;tiddlyspace/TiddlySpaceFilters/1521906:7b6eb3a4ec1d11a759eddee9b9d2fe88174bddaa&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/tiddlyspace" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="tiddlyspace" server.permissions="read" server.content-type="text/javascript" modified="20131111192334" created="20131111192334" tags="excludeLists excludeSearch systemConfig" _hash="3b6e75a776f9a07498220fe23b305bc97b531afc">
<pre>/***
|''Name''|TiddlySpaceFilters|
|''Description''|provide TiddlySpace-specific filter extensions|
|''Author''|Jon Robson|
|''Version''|0.6.1|
|''Status''|@@beta@@|
|''CoreVersion''|2.6.2|
|''Requires''|TiddlySpaceConfig|
|''License''|[[BSD|http://www.opensource.org/licenses/bsd-license.php]]|
!Usage
{{{
&lt;&lt;tsList Private&gt;&gt;
&lt;&lt;tsList Public&gt;&gt;
&lt;&lt;tsList Draft&gt;&gt;
}}}
!Code
***/
//{{{
(function($) {

var tiddlyspace = config.extensions.tiddlyspace;
var privateBag = tiddlyspace.getCurrentBag("private");
var publicBag = tiddlyspace.getCurrentBag("public");

config.filterHelpers = {
	is: {
		"private": function(tiddler) {
			var bag = tiddler.fields["server.bag"];
			return bag == privateBag;
		},
		"public": function(tiddler) {
			var bag = tiddler.fields["server.bag"];
			return bag == publicBag;
		},
		draft: function(tiddler) {
			var fields = tiddler.fields;
			var bag = fields["server.bag"];
			return (privateBag == bag &amp;&amp; fields["publish.name"]) ? true : false;
		},
		local: function(tiddler) {
			return config.filterHelpers.is["public"](tiddler) ||
				config.filterHelpers.is["private"](tiddler);
		},
		unsynced: function(tiddler) {
			return tiddler ? tiddler.isTouched() : false;
		}
	}
};

config.filters.is = function(results, match) {
	var candidates = store.getTiddlers("title");
	var type = match[3];
	for (var i = 0; i &lt; candidates.length; i++) {
		var tiddler = candidates[i];
		var helper = config.filterHelpers.is[type];
		if(helper &amp;&amp; helper(tiddler)) {
			results.pushUnique(tiddler);
		}
	}
	return results;
};

})(jQuery);
//}}}</pre>
</div>
<div title="deleteTiddler" server.title="deleteTiddler" server.page.revision="1521929" server.etag="&quot;system-images_public/deleteTiddler/1521929:3b0e384c4070737dc9b41306bcb78dc09444981e&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-images_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-images_public" server.permissions="read" server.content-type="image/svg+xml" modified="20131111192332" created="20131111192332" tags="excludeLists excludeSearch" _hash="cdf65cc5eb8e6665817a04cc764cd8797947f799">
<pre>&lt;svg xmlns="http://www.w3.org/2000/svg" xmlns:xl="http://www.w3.org/1999/xlink" version="1.1" viewBox="450 366 38 57"
width="30" height="30"&gt;
	&lt;g stroke="none" stroke-opacity="1" stroke-dasharray="none" fill="none" fill-opacity="1"&gt;
		&lt;g&gt;
			&lt;path d="M 452.1094 421.2422 L 450 421.2422 L 450 423 L 487.9688 423 L 487.9688 421.2422 L 485.8595 421.2422 
			L 485.8595 377.29688 L 487.9688 377.29688 L 487.9688 375.53906 L 485.8595 375.53906 
			C 485.8595 375.53906 481.12463 371.59341 473.02023 370.52802 C 472.6824 368.9689 471.72098 366.75 468.9844 366.75 
			C 466.24783 366.75 465.28638 368.9689 464.94864 370.52802 
			C 456.84418 371.59341 452.1094 375.53906 452.1094 375.53906 L 450 375.53906 L 450 377.29688 L 452.1094 377.29688 
			Z M 467.12247 370.32086 L 467.12247 370.32086 C 467.3805 369.42395 467.90762 368.50781 468.9844 368.50781 
			C 470.0612 368.50781 470.5883 369.42395 470.84634 370.32086 
			C 470.24136 370.2848 469.62054 370.26562 468.9844 370.26562 
			C 468.34827 370.26562 467.72748 370.2848 467.12247 370.32086 Z M 454.21875 420.92804 L 454.21875 420.92804 
			C 455.46762 420.42087 456.32816 419.35281 456.32816 418.11716 L 456.32816 377.29688 L 458.4375 377.29688 
			L 458.4375 421.2422 L 454.21875 421.2422 Z M 460.5469 420.92804 L 460.5469 420.92804 
			C 461.79578 420.42087 462.65625 419.35281 462.65625 418.11716 L 462.65625 377.29688 L 464.76566 377.29688 
			L 464.76566 421.2422 L 460.5469 421.2422 Z M 466.87503 420.92804 L 466.87503 420.92804 
			C 468.1239 420.42087 468.9844 419.35281 468.9844 418.11716 L 468.9844 377.29688 L 471.09378 377.29688 
			L 471.09378 421.2422 L 466.87503 421.2422 Z M 473.2032 420.92804 L 473.2032 420.92804 
			C 474.45203 420.42087 475.31256 419.35281 475.31256 418.11716 L 475.31256 377.29688 L 477.4219 377.29688 
			L 477.4219 421.2422 L 473.2032 421.2422 Z M 479.5313 420.92804 L 479.5313 420.92804 
			C 480.78018 420.42087 481.64066 419.35281 481.64066 418.11716 L 481.64066 377.29688 L 483.75006 377.29688 
			L 483.75006 421.2422 L 479.5313 421.2422 Z" fill="black" class="glyph"/&gt;
		&lt;/g&gt;
	&lt;/g&gt;
&lt;/svg&gt;</pre>
</div>
<div title="RandomColorPalettePlugin" server.title="RandomColorPalettePlugin" server.page.revision="1521872" server.etag="&quot;system-plugins_public/RandomColorPalettePlugin/1521872:10b64b6d1ba94723e060d4d4a069aafa42b15644&quot;" modifier="jon" creator="jon" server.workspace="bags/system-plugins_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-plugins_public" server.permissions="read" server.content-type="text/javascript" modified="20131111192330" created="20131111192330" tags="excludeLists excludeSearch systemConfig" _hash="c5b359abab5a1446d12be89e6ea608d2d73e4822">
<pre>/***
|''Name''|RandomColorPalettePlugin|
|''Description''|Adds a random color palette to TiddlyWiki|
|''Author''|Jon Robson|
|''Version''|1.4.0|
|''Status''|stable|
|''Source''|https://github.com/jdlrobson/TiddlyWikiPlugins/raw/master/plugins/RandomColorPalettePlugin/RandomColorPalettePlugin.js|
|''License''|[[BSD|http://www.opensource.org/licenses/bsd-license.php]]|
!Usage
{{{
&lt;&lt;RandomColorPalette&gt;&gt;
}}}
Sets and saves a random color palette on execution

{{{
&lt;&lt;RandomColorPaletteButton&gt;&gt;
}}}
Creates a button, which when clicked will change the color palette
More information at http://macros.tiddlyspace.com/#%5B%5BRandomColorPaletteButton%20macro%5D%5D
!Code
***/
//{{{
RGB.prototype.toRGBString = function() {
	return "rgb(%0,%1,%2)".format(parseInt(this.r * 255, 10),
		parseInt(this.g * 255, 10), parseInt(this.b * 255, 10))
}
function HSL_TO_RGB(h, s, l) { // h (hue) between 0 and 360, s (saturation) &amp; l (lightness) between 0 and 1
	var c = l &lt;= 0.5 ? 2 * l * s : ( 2 - (2 * l)) * s;
	var h1 = h / 60;
	var x = c * (1 - Math.abs((h1 % 2) - 1)); 
	var r, g, b;
	if(typeof(h) == 'undefined') {
		r = 0;
		g = 0;
		b = 0;
	} else if(0 &lt;= h1 &amp;&amp; h1 &lt; 1) {
		r = c;
		g = x;
		b = 0;
	} else if(1 &lt;= h1 &amp;&amp; h1 &lt; 2) {
		r = x;
		g = c;
		b = 0;
	} else if(2 &lt;= h1 &amp;&amp; h1 &lt; 3) {
		r = 0;
		g = c;
		b = x;
	} else if(3 &lt;= h1 &amp;&amp; h1 &lt; 4) {
		r = 0;
		g = x;
		b = c;
	} else if(4 &lt;= h1 &amp;&amp; h1 &lt; 5) {
		r = x;
		g = 0;
		b = c;
	} else if(5 &lt;= h1 &amp;&amp; h1 &lt; 6) {
		r = c;
		g = 0;
		b = x;
	}
	m = l - (0.5 * c);
	return new RGB(r + m, g + m, b + m);
}

(function($){
	var macro = config.macros.RandomColorPalette = {
		messagesOn: false, 
		changedPaletteText: "We have assigned you a random theme by adjusting the [[ColorPalette]] tiddler.\nDon't like it? Click &lt;&lt;RandomColorPalette&gt;&gt; for another one.", 
		handler: function(place, macroName, params, wikifier, paramString, tiddler) {
			paramString = paramString || "";
			var options = macro.getOptions(paramString);
			macro.generatePalette(options, true);
		},
		optionTypes: {
			floats: ["hue", "saturation", "darkest", "lightness", "huevariance", "dark", "pale", "light", "mid",
				"saturation_light", "saturation_pale", "saturation_mid", "saturation_dark"
			]
		},
		getOptions: function(paramString) {
			var args = paramString.parseParams("name", null, true, false, true)[0];
			var options = {};
			var numbers = macro.optionTypes.floats;
			for(var i in args) {
				options[i] = numbers.indexOf(i) &gt; -1 ? parseFloat(args[i][0], 10) : args[i][0];
			}
			return options;
		},
		generateRandomNumber: function(min, max, info) {
			var num = (Math.random() * 1);
			info = !info ? { attempts:0 } : info;
			info.attempts += 1;
			var good = true;
			if(min == max) {
				return max;
			}
			if(min &amp;&amp; num &lt; min) {
				good = false;
			} else if(max &amp;&amp; num &gt; max) {
				good = false;
			}
			if(!good) {
				if(info.attempts &lt; 5) {
					return macro.generateRandomNumber(min, max, info);
				} else {
					if(max) {
						return max;
					} else if(min) {
						return min;
					} else {
						return 1;
					}
				}
			}
			return num;
		},
		getExistingPalette: function(asJSON) {
			var title = "ColorPalette";
			var tiddlerText;
			if(store.tiddlerExists(title)) {
				tiddlerText = store.getTiddlerText(title);
			} else if(store.isShadowTiddler(title)){
				tiddlerText = config.shadowTiddlers[title];
			}
			if(asJSON) {
				var json = {};
				if(tiddlerText) {
					var lines = tiddlerText.split("\n");
					for(var i = 0; i &lt; lines.length; i++) {
						var definition = lines[i].split(":");
						if(definition.length == 2) {
							var name = definition[0].trim();
							var value = definition[1].trim();
							json[name] = value;
						}
					}
				}
				return json;
			} else {
				return tiddlerText;
			}
		},
		generatePalette: function(options, save) {
			var outputRGB = options.rgb;
			var palette = macro.getExistingPalette(true);
			var hue = options.hue || Math.floor(Math.random() * 359);
			var saturation = options.saturation || macro.generateRandomNumber(0.3, 0.7);
			var dark = options.dark || options.darkest || macro.generateRandomNumber(0, 0.10);
			var pale = options.pale || options.lightness || macro.generateRandomNumber(0.90, 1);
			var delta = ( ( pale - dark ) / 3 );
			var mid = options.mid || dark + delta;
			var light = options.light || dark + (delta * 2);
			var lightness_values = {Dark: dark, Mid: mid, Light: light, Pale: pale};
			var saturation_values = {};
			for(i in lightness_values) {
				if(true) {
					saturation_values[i] = options["saturation_" + i.toLowerCase()] || saturation;
				}
			}

			var opposite_hue = (hue + 180) % 360;
			var seed = options.huevariance || Math.floor((85 * Math.random()) + 5); // we want it to be at least 5 degrees
			var huetwo = (opposite_hue + seed) % 360;
			var huethree = (opposite_hue - seed) % 360;
			if(huetwo &lt; 0) {
				huetwo = 360 + huetwo;
			}
			if(huethree &lt; 0) {
				huethree = 360 + huethree;
			}
			for(var j in lightness_values) {
				if(true) {
					var saturation = saturation_values[j];
					palette["Primary" + j] = HSL_TO_RGB(hue, saturation, lightness_values[j]);
					palette["Secondary" + j] = HSL_TO_RGB(huetwo, saturation, lightness_values[j]);
					palette["Tertiary" + j] = HSL_TO_RGB(huethree, saturation, lightness_values[j]);
				}
			}
			palette.Background = HSL_TO_RGB(hue, saturation, 0.92);
			palette.Foreground = HSL_TO_RGB(hue, saturation, 0.08);
			palette.ColorPaletteParameters = ["HSL([", hue, "|", seed, "], [", saturation_values.Pale, "|",
				saturation_values.Light, "|", saturation_values.Mid, "|", saturation_values.Dark, "],",
				"[", dark, "|", mid, "|", light, "|", pale, "])"].join("");
			// construct new ColorPalette
			var text = ["/*{{{*/\n"];
			var colorcode;
			for(var id in palette) {
				if(true) {
					var color = palette[id];
					colorcode = outputRGB ? color.toRGBString() : color.toString();
					text.push("%0: %1\n".format(id, colorcode));
				}
			}
			text.push("/*}}}*/");
			text = text.join("");
			if(save) {
				macro.saveColorPalette(text);
			}
			return text;
		},
		saveColorPalette: function(text) {
			var tid = store.getTiddler("ColorPalette");
			if(!tid) {
				tid = new Tiddler("ColorPalette");
				tid.fields = merge({}, config.defaultCustomFields);
			} // TODO: detect that the ColorPalette in the space comes from outside recipe
			tid.fields["server.page.revision"] = "false"; // edit conflicts dont matter

			// save the color palette in tid
			tid = store.saveTiddler(tid.title, tid.title, text, tid.modifier, tid.modified,
				tid.tags, tid.fields, false, tid.created, tid.creator);
			// an interval is used to cope with users clicking on the palette button quickly.
			if(macro._nextSave) {
				window.clearTimeout(macro._nextSave);
			}
			macro._nextSave = window.setTimeout(function() {
					autoSaveChanges(null, [tid]);
				}, 2000);
			// temporary workaround for IE.
			$.twStylesheet.remove({ id: "StyleSheetColors" });
			$.twStylesheet.remove({ id: "StyleSheet" });
			refreshAll();
			macro.reportChange();
			return tid;
		},
		reportChange: function() {
			if(macro.messagesOn) { // only display message once..
				var msgPlace = getMessageDiv();
				if(!$(".changedPalette", msgPlace)[0]) {
					var tempPlace = document.createElement("div");
					wikify("{{changedPalette{" + macro.changedPaletteText + "}}}", tempPlace);
					msgPlace.appendChild(tempPlace);
				}
			}
		}
	};
	var btnMacro = config.macros.RandomColorPaletteButton = {
			text: "New ColorPalette",
			tooltip: "Generate a random colour scheme for your TiddlyWiki",
			makeButton: function(place, options) {
				var btnHandler = function(ev) {
					var t = $(ev.target);
					var options = t.data("options");
					macro.generatePalette(options, true);
					ev.preventDefault();
					return false;
				};
				var btn = createTiddlyButton(place, this.text, this.tooltip, btnHandler);
				$(btn).data("options", options);
				return btn;
			},
			handler: function(place, macroName, params, wikifier, paramString, tiddler) {
				var options = macro.getOptions(paramString);
				btnMacro.makeButton(place, options);
			}
	};
})(jQuery);
//}}}</pre>
</div>
<div title="closeTiddler" server.title="closeTiddler" server.page.revision="1521934" server.etag="&quot;system-images_public/closeTiddler/1521934:90a810ebd8cf4773b5be2f49fe8062f173bc449a&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-images_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-images_public" server.permissions="read" server.content-type="image/svg+xml" modified="20131111192332" created="20131111192332" tags="excludeLists excludeSearch" _hash="1ddacf68b541cb91b7b896c9c2934ec79e8997a0">
<pre>&lt;svg xmlns="http://www.w3.org/2000/svg" xmlns:xl="http://www.w3.org/1999/xlink" version="1.1" viewBox="78 222 60 60" 
width="30" height="30"&gt;
&lt;g stroke="none" stroke-opacity="1" stroke-dasharray="none" fill="none" fill-opacity="1"&gt;
	&lt;g&gt;
		&lt;path d="M 107.92718 244.14815 L 86.651474 222.89253 L 78.85206 230.69925 L 100.120415 251.9476 L 78.774 273.27396 
		L 86.57342 281.08075 L 107.927216 259.74707 L 129.39981 281.19946 L 137.19922 273.39267 L 115.73397 251.94763 
		L 137.121155 230.58054 L 129.32175 222.77374 Z" fill="black" class="glyph"/&gt;
	&lt;/g&gt;
&lt;/g&gt;
&lt;/svg&gt;</pre>
</div>
<div title="TiddlyWebConfig" server.title="TiddlyWebConfig" server.page.revision="1521857" server.etag="&quot;system/TiddlyWebConfig/1521857:d23a3f465f25f195776facb6bfac2c0d0f03c02a&quot;" modifier="FND" creator="FND" server.workspace="bags/system" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system" server.permissions="read" server.content-type="text/javascript" modified="20130924180405" created="20130924180405" tags="excludeLists excludeSearch systemConfig" _hash="29e43eb7496ba0572556029d183cb3f434369f04">
<pre>/***
|''Name''|TiddlyWebConfig|
|''Description''|configuration settings for TiddlyWebWiki|
|''Author''|FND|
|''Version''|1.3.2|
|''Status''|stable|
|''Source''|http://svn.tiddlywiki.org/Trunk/association/plugins/TiddlyWebConfig.js|
|''License''|[[BSD|http://www.opensource.org/licenses/bsd-license.php]]|
|''Requires''|TiddlyWebAdaptor ServerSideSavingPlugin|
|''Keywords''|serverSide TiddlyWeb|
!Code
***/
//{{{
(function($) {

if(!config.extensions.ServerSideSavingPlugin) {
	throw "Missing dependency: ServerSideSavingPlugin";
}
if(!config.adaptors.tiddlyweb) {
	throw "Missing dependency: TiddlyWebAdaptor";
}

if(window.location.protocol != "file:") {
	config.options.chkAutoSave = true;
}

var adaptor = tiddler.getAdaptor();
var recipe = tiddler.fields["server.recipe"];
var workspace = recipe ? "recipes/" + recipe : "bags/common";

var plugin = config.extensions.tiddlyweb = {
	host: tiddler.fields["server.host"].replace(/\/$/, ""),
	username: null,
	status: {},

	getStatus: null, // assigned later
	getUserInfo: function(callback) {
		this.getStatus(function(status) {
			callback({
				name: plugin.username,
				anon: plugin.username ? plugin.username == "GUEST" : true
			});
		});
	},
	hasPermission: function(type, tiddler) {
		var perms = tiddler.fields["server.permissions"];
		if(perms) {
			return perms.split(", ").contains(type);
		} else {
			return true;
		}
	}
};

config.defaultCustomFields = {
	"server.type": tiddler.getServerType(),
	"server.host": plugin.host,
	"server.workspace": workspace
};

// modify toolbar commands

config.shadowTiddlers.ToolbarCommands = config.shadowTiddlers.ToolbarCommands.
	replace("syncing ", "revisions syncing ");

config.commands.saveTiddler.isEnabled = function(tiddler) {
	return plugin.hasPermission("write", tiddler) &amp;&amp; !tiddler.isReadOnly();
};

config.commands.deleteTiddler.isEnabled = function(tiddler) {
	return !readOnly &amp;&amp; plugin.hasPermission("delete", tiddler);
};

// hijack option macro to disable username editing
var _optionMacro = config.macros.option.handler;
config.macros.option.handler = function(place, macroName, params, wikifier,
		paramString) {
	if(params[0] == "txtUserName") {
		params[0] = "options." + params[0];
		var self = this;
		var args = arguments;
		args[0] = $("&lt;span /&gt;").appendTo(place)[0];
		plugin.getUserInfo(function(user) {
			config.macros.message.handler.apply(self, args);
		});
	} else {
		_optionMacro.apply(this, arguments);
	}
};

// hijack isReadOnly to take into account permissions and content type
var _isReadOnly = Tiddler.prototype.isReadOnly;
Tiddler.prototype.isReadOnly = function() {
	return _isReadOnly.apply(this, arguments) ||
		!plugin.hasPermission("write", this);
};

var getStatus = function(callback) {
	if(plugin.status.version) {
		callback(plugin.status);
	} else {
		var self = getStatus;
		if(self.pending) {
			if(callback) {
				self.queue.push(callback);
			}
		} else {
			self.pending = true;
			self.queue = callback ? [callback] : [];
			var _callback = function(context, userParams) {
				var status = context.serverStatus || {};
				for(var key in status) {
					if(key == "username") {
						plugin.username = status[key];
						config.macros.option.propagateOption("txtUserName",
							"value", plugin.username, "input");
					} else {
						plugin.status[key] = status[key];
					}
				}
				for(var i = 0; i &lt; self.queue.length; i++) {
					self.queue[i](plugin.status);
				}
				delete self.queue;
				delete self.pending;
			};
			adaptor.getStatus({ host: plugin.host }, null, _callback);
		}
	}
};
(plugin.getStatus = getStatus)(); // XXX: hacky (arcane combo of assignment plus execution)

})(jQuery);
//}}}</pre>
</div>
<div title="ToggleTiddlerPrivacyPlugin" server.title="ToggleTiddlerPrivacyPlugin" server.page.revision="1521863" server.etag="&quot;system-plugins_public/ToggleTiddlerPrivacyPlugin/1521863:fd0bba09d82b50dee62546f80cc42ec4a7808761&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-plugins_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-plugins_public" server.permissions="read" server.content-type="text/javascript" modified="20131111192330" created="20131111192330" tags="excludeLists excludeSearch systemConfig" _hash="3acf06056e188b31bcc3c42ec673a050886d64c4">
<pre>/***
|''Name''|ToggleTiddlerPrivacyPlugin|
|''Version''|0.7.1|
|''Status''|@@beta@@|
|''Description''|Allows you to set the privacy of new tiddlers and external tiddlers within an EditTemplate, and allows you to set a default privacy setting|
|''CoreVersion''|2.6.1|
|''Requires''|TiddlySpaceConfig|
|''Source''|http://github.com/TiddlySpace/tiddlyspace/raw/master/src/plugins/ToggleTiddlerPrivacyPlugin.js|
!Notes
When used in conjunction with TiddlySpaceTiddlerIconsPlugin changing the privacy setting will also interact with any privacy icons.

Currently use of
{{{&lt;&lt;setPrivacy defaultValue:public&gt;&gt;}}} is in conflict with {{{&lt;&lt;newTiddler fields:"server.workspace:x_private"&gt;&gt;}}}

There is an option, found in the tweak tab of the backstage, called txtPrivacyMode. Set this to either ''public'' or ''private'' depending on your security preference. If you choose not to set it then it will default to ''public''.
!Params
defaultValue:[private|public]
Allows you to set the default privacy value (Default is private)

!Code
***/
//{{{
(function($) {

	var tiddlyspace = config.extensions.tiddlyspace,
		macro;
	macro = config.macros.setPrivacy = {
		handler: function(place, macroName, params, wikifier, paramString, tiddler) {
			if(readOnly) {
				return;
			}
			var el = $(story.findContainingTiddler(place)),
				args = paramString.parseParams("name",
					null, true, false, true)[0],
				container = $("&lt;div /&gt;").
					addClass("privacySettings").
					appendTo(place)[0],
				currentSpace = tiddlyspace.currentSpace.name,
				currentBag = tiddler ? tiddler.fields["server.bag"] : false,
				// XXX: is the following reliable?
				isNewTiddler = el.hasClass("missing") || !currentBag,
				tiddlerStatus = tiddlyspace.getTiddlerStatusType(tiddler),
				customFields = el.attr("tiddlyfields"),
				defaultValue = "public",
				options = config.macros.tiddlerOrigin ?
						config.macros.tiddlerOrigin.getOptions(paramString) :
						{};
			customFields = customFields ? customFields.decodeHashMap() : {};
			if(isNewTiddler || !["public", "private", "unsyncedPrivate",
					"unsyncedPublic"].contains(tiddlerStatus)) {
				if(args.defaultValue) {
					defaultValue = args.defaultValue[0].toLowerCase();
				} else {
					defaultValue = config.options.chkPrivateMode ?
							"private" : "public";
				}
				defaultValue = defaultValue ?
						"%0_%1".format(currentSpace, defaultValue) :
						customFields["server.bag"];
				this.createRoundel(container, tiddler, currentSpace,
						defaultValue, options);
			}
		},
		updateEditFields: function(tiddlerEl, bag) {
			var saveBagField = $('[edit="server.bag"]', tiddlerEl),
				saveWorkspaceField = $('[edit="server.workspace"]', tiddlerEl),
				input = $("&lt;input /&gt;").attr("type", "hidden"),
				workspace = "bags/" + bag;
			if(saveBagField.length === 0) {
				input.clone().attr("edit", "server.bag").val(bag).
					appendTo(tiddlerEl);
			} else {
				saveBagField.val(bag);
			}
			// reset to prevent side effects
			$(tiddlerEl).attr("tiddlyFields", "");
			if(saveWorkspaceField.length === 0) {
				input.clone().attr("edit", "server.workspace").
					val(workspace).appendTo(tiddlerEl);
			} else {
				saveWorkspaceField.val(workspace);
			}
		},
		setBag: function(tiddlerEl, newBag, options) {
			var bagStatus,
				title = $(tiddlerEl).attr("tiddler"),
				tiddler = store.getTiddler(title),
				originButton = $(".originButton", tiddlerEl)[0],
				refreshIcon,
				newWorkspace = "bags/" + newBag,
				rPrivate = $("input[type=radio].isPrivate", tiddlerEl),
				rPublic = $("input[type=radio].isPublic", tiddlerEl);
			refreshIcon = function(type) {
				var originMacro = config.macros.tiddlerOrigin;
				if(originButton &amp;&amp; originMacro) {
					options.noclick = true;
					originMacro.showPrivacyRoundel(tiddler, type,
							originButton, options);
				}
			};
			macro.updateEditFields(tiddlerEl, newBag);
			if(tiddler) {
				tiddler.fields["server.bag"] = newBag;
				// for external tiddlers
				tiddler.fields["server.workspace"] = newWorkspace;
			}
			if(newBag.indexOf("_public") &gt; -1) {
				rPrivate.attr("checked", false);
				rPublic.attr("checked", true);
				bagStatus = "public";
			} else {
				rPublic.attr("checked", false); // explicitly do this for ie
				rPrivate.attr("checked", true);
				bagStatus = "private";
			}
			refreshIcon(bagStatus);
		},
		createRoundel: function(container, tiddler, currentSpace,
							   defaultValue, options) {
			var privateBag = "%0_private".format(currentSpace),
				publicBag = "%0_public".format(currentSpace),
				rbtn = $("&lt;input /&gt;").attr("type", "radio").
					attr("name", tiddler.title),
				el = story.findContainingTiddler(container);
			rbtn.clone().val("private").addClass("isPrivate").
				appendTo(container);
			$("&lt;label /&gt;").text("private").appendTo(container); // TODO: i18n
			rbtn.clone().val("public").addClass("isPublic")
				.appendTo(container);
			$("&lt;label /&gt;").text("public").appendTo(container); // TODO: i18n
			$("[type=radio]", container).click(function(ev) {
				var btn = $(ev.target);
				tiddler.fields["server.page.revision"] = "false";
				if(btn.hasClass("isPrivate")) { // private button clicked.
					$(el).addClass("isPrivate").removeClass("isPublic");
					macro.setBag(el, privateBag, options);
				} else {
					$(el).addClass("isPublic").removeClass("isPrivate");
					macro.setBag(el, publicBag, options);
				}
			});
			window.setTimeout(function() {
				macro.setBag(el, defaultValue, options);
			}, 100);
			// annoyingly this is needed as customFields are added to end of EditTemplate so are not present yet
			// and don't seem to respect any existing customFields.
		}
	};

}(jQuery));
//}}}</pre>
</div>
<div title="Backstage" server.title="Backstage" server.page.revision="1521902" server.etag="&quot;tiddlyspace/Backstage/1521902:544c361ba716b77556b8cc51a6ae158a3b2bca3b&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/tiddlyspace" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="tiddlyspace" server.permissions="read" server.content-type="" modified="20131111192332" created="20131111192332" tags="excludeLists excludeMissing excludeSearch" _hash="374716f48c21298abb095093dce2176965648975">
<pre>!SpaceUnplugged
{{unpluggedSpaceTab{
{{wizard{
&lt;&lt;image unsyncedIcon width:48&gt;&gt; Sync is currently unavailable in ~TiddlyWiki due to security constraints in modern browsers. Research is being done to build a suitable alternative. In the meantime if you have changed content in an offline ~TiddlyWiki, you can get your content back into ~TiddlySpace by using the ''import'' functionality from the backstage of the online wiki.
}}}
}}}

!Menu
&lt;&lt;message messages.memberStatus&gt;&gt; &lt;&lt;homeLink&gt;&gt;
{{unsyncedList{&lt;&lt;message messages.syncListHeading&gt;&gt; &lt;&lt;list filter [is[unsynced]]&gt;&gt;}}}

running TiddlySpace@glossary version &lt;&lt;message extensions.tiddlyweb.status.tiddlyspace_version&gt;&gt;
{{autotable{
&lt;&lt;tiddler Backstage##Resources&gt;&gt;
}}}

!Resources
[[blog|@@blog]] [[documentation|@@docs]] [[featured spaces|@@featured]] 

!ImportExport
&lt;&lt;fileImport&gt;&gt;
You can download this TiddlySpace as an offline TiddlyWiki:

{{chunkyButton{&lt;&lt;exportSpace&gt;&gt;}}}

!BackstageTiddlers
|upload a &lt;&lt;message messages.privacySetting&gt;&gt; file: &lt;&lt;binaryUpload&gt;&gt;|&lt;&lt;closeAll&gt;&gt;&lt;&lt;permaview&gt;&gt;&lt;&lt;newTiddler&gt;&gt;&lt;&lt;newJournal "DD MMM YYYY" "journal"&gt;&gt;&lt;&lt;saveChanges&gt;&gt;|
|&gt;|&lt;&lt;search&gt;&gt;|
|&gt;|&lt;&lt;tiddler Backstage##Tiddlers&gt;&gt;|

!Tiddlers
&lt;&lt;tabs
	txtMainTab
	"Recent" "Recently edited tiddlers" TabTimeline
	"All" "All tiddlers" TabAll
	"Public" "All public tiddlers" [[TiddlySpaceTabs##Public]]
	"Private" "All private tiddlers" [[TiddlySpaceTabs##Private]]
	"Tags" "All tags" TabTags
	"Spaces" "Tiddlers grouped by space" [[TiddlySpaceTabs##Spaces]]
	"Missing" "Missing tiddlers" TabMoreMissing
	"Orphans" "Orphaned tiddlers" TabMoreOrphans
	"Shadows" "Shadowed tiddlers" TabMoreShadowed
&gt;&gt;

!BatchOps
&lt;&lt;tabs
	txtPublisherTab
	"Private" "Move tiddlers from private to public" Backstage##BatchPrivate
	"Public" "Move tiddlers from public to private" Backstage##BatchPublic
&gt;&gt;

!BatchPrivate
&lt;&lt;TiddlySpacePublisher type:private&gt;&gt;

!BatchPublic
&lt;&lt;TiddlySpacePublisher type:public&gt;&gt;

!Plugins
''Note:'' Many of these plugins are core TiddlySpace plugins and cannot be changed unless first cloned.

&lt;&lt;tiddler PluginManager&gt;&gt;

!Tweaks
These options change behavior in TiddlyWiki //only// and may be ineffective in TiddlySpace.

&lt;&lt;tiddler AdvancedOptions&gt;&gt;</pre>
</div>
<div title="TiddlySpaceRevertRevision" server.title="TiddlySpaceRevertRevision" server.page.revision="1521871" server.etag="&quot;system-plugins_public/TiddlySpaceRevertRevision/1521871:3225af233615fd710b5e0bf1b63b696f962dfc98&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-plugins_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-plugins_public" server.permissions="read" server.content-type="text/javascript" modified="20131111192330" created="20131111192330" tags="excludeLists excludeMissing excludeSearch systemConfig" _hash="db2d6dc5a63b9262d62fb6ffe02dbe10fdd31feb">
<pre>/***
|''Name''|TiddlySpaceRevertRevision|
|''Description''|Revert to a previous revision|
|''Author''|BenGillies|
|''Version''|0.1|
|''Status''|unstable|
|''Source''|http://github.com/TiddlySpace/tiddlyspace|
|''CodeRepository''|http://github.com/TiddlySpace/tiddlyspace|
|''License''|[[BSD|http://www.opensource.org/licenses/bsd-license.php]]|
|''CoreVersion''|2.6.0|
|''Requires''|TiddlyWebAdaptor TiddlySpaceRevisionView|
!Usage
Add a control button to revert to a particular revision.

The button must be called from within a revision, as generated by TiddlySpaceRevisionView
!Code
***/
//{{{
(function($) {

config.commands.revert = {
	text: "revert",
	tooltip: "make this revision the current one",
	handler: function(ev, src, title) {
		var revElem = story.getTiddler(title);
		var tidToRevert = store.getTiddler($(revElem).attr("revName"));

		var revision = store.getTiddler(title);
		if ((revision) &amp;&amp; (tidToRevert)) {
			tidToRevert.text = revision.text;
			var newFields = merge({}, revision.fields);
			for (var fieldName in newFields) {
				if (fieldName.substr(0, 7) === "server.") {
					delete newFields[fieldName];
				}
			}
			merge(tidToRevert.fields, newFields);
			tidToRevert.tags = merge([], revision.tags);
			tidToRevert.fields.changecount = 1;
			delete tidToRevert.fields.doNotSave;

			store.saveTiddler(tidToRevert.title, tidToRevert.title,
				tidToRevert.text, null, null, tidToRevert.tags,
				tidToRevert.fields, false, tidToRevert.created, tidToRevert.creator);

			autoSaveChanges(true);
		}
	}
};

})(jQuery);
//}}}</pre>
</div>
<div title="saveTiddler" server.title="saveTiddler" server.page.revision="1521927" server.etag="&quot;system-images_public/saveTiddler/1521927:09e9f8bdba0b95d5a4ed6a8d8d952f1ccb2f5a49&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-images_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-images_public" server.permissions="read" server.content-type="image/svg+xml" modified="20131111192332" created="20131111192332" tags="excludeLists excludeSearch" _hash="461592520ce0f489a4d4a95f0dcb4e1e46d2f6e7">
<pre>&lt;svg xmlns="http://www.w3.org/2000/svg" xmlns:xl="http://www.w3.org/1999/xlink" version="1.1" viewBox="2 724 68 55" 
width="30" height="30"&gt;
&lt;g stroke="none" stroke-opacity="1" stroke-dasharray="none" fill="none" fill-opacity="1"&gt;
	&lt;g&gt;
		&lt;path d="M 2.25 756 L 11.25 747 L 24.75 760.4994 L 60.750004 724.4994 L 69.75 733.49902 
		L 24.749977 778.49976 Z" fill="#101010" class="glyph"/&gt;
	&lt;/g&gt;
&lt;/g&gt;
&lt;/svg&gt;</pre>
</div>
<div title="setDefaultTiddlers" server.title="setDefaultTiddlers" server.page.revision="1521878" server.etag="&quot;system-info_public/setDefaultTiddlers/1521878:88e65ddb9503a424719d0b55ca4c4673325551e5&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-info_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-info_public" server.permissions="read" server.content-type="" modified="20131111192330" created="20131111192330" tags="excludeLists excludeSearch" _hash="c632865df818925daec0d5040975797a27218e81">
<pre>Once you have some content then you may choose to determine a tiddler, or set of tiddlers to display each time you load ~TiddlySpace. This is determined by the [[DefaultTiddlers]].</pre>
</div>
<div title="_space" server.title="_space" server.page.revision="1521890" server.etag="&quot;tiddlyspace/_space/1521890:c9a31c1ee5562249c247a1a47a98cb709dd3e85d&quot;" modifier="None" creator="None" server.workspace="bags/tiddlyspace" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="tiddlyspace" server.permissions="read" server.content-type="text/html" modified="20131111192332" created="20131111192332" tags="excludeLists excludeMissing excludeSearch" _hash="8c535528a72c980d5c68cc9ca28ef21cb040b270">
<pre>&lt;!DOCTYPE html&gt;
&lt;html&gt;
&lt;head&gt;
	&lt;meta http-equiv="Content-Type" content="text/html;charset=utf-8"&gt;
	&lt;title&gt;This Space&lt;/title&gt;
	&lt;link href="/bags/common/tiddlers/profile.css" type='text/css' rel='stylesheet' &gt;
	&lt;link href="/bags/common/tiddlers/admin.css" type='text/css' rel='stylesheet' &gt;
	&lt;!--[if lte IE 8]&gt;
	&lt;script type="text/javascript" src="/bags/common/tiddlers/json2.js"&gt;&lt;/script&gt;
	&lt;script type="text/javascript" src="/bags/common/tiddlers/es5-shim.min.js"&gt;&lt;/script&gt;
	&lt;![endif]--&gt;
&lt;/head&gt;
&lt;body&gt;
&lt;div id="container"&gt;
	&lt;div id="text-html" class="main section"&gt;
		&lt;a class="app" href="/"&gt;home&lt;/a&gt;
		&lt;div class="left"&gt;
		&lt;h2&gt;About this space &lt;button class='toggleNext'&gt;&lt;/button&gt;&lt;/h2&gt;
		&lt;div id="siteinfo"&gt;&lt;/div&gt;
		&lt;h2&gt;Site Icon&lt;/h2&gt;
		&lt;div&gt;
			&lt;img id="siteicon" class="siteicon"&gt;
			&lt;form id="upload" method="POST" enctype="multipart/form-data"&gt;
				&lt;input type="hidden" name="title" value="SiteIcon" /&gt;
				&lt;input type="hidden" name="tags" value="excludeLists"&gt;
				&lt;input type="hidden" name="csrf_token" class="csrf" /&gt;
				&lt;input type="file" name="file" accept="image/*" /&gt;
				&lt;input class="btn" type="submit" value="upload" /&gt;
			&lt;/form&gt;
			&lt;div id="dropzone"&gt;Drop file here
				&lt;img class="notloading" src="/bags/common/tiddlers/ajax-loader.gif" alt="submitting SiteIcon" /&gt;
			&lt;/div&gt;
		&lt;/div&gt;
		&lt;h2&gt;Vital Statistics&lt;/h2&gt;
		&lt;div id="info"&gt;please wait while information is loaded about this space...&lt;/div&gt;
		&lt;button class="spacereset"&gt;Reset Space&lt;/button&gt;
		&lt;div class="reset-confirm-wrap messageArea"&gt;
			&lt;button class="close-btn" title="cancel reset"&gt;×&lt;/button&gt;
			&lt;p&gt;Are you sure you want to reset the space? You can't go back! This will remove all the content from the space!&lt;/p&gt;
			&lt;form class="cf"&gt;
				&lt;label for="reset-confirm"&gt;Enter the space name to confirm.&lt;/label&gt;
				&lt;input type="text" name="reset-confirm" class="reset-confirm-input inputBox" /&gt;
				&lt;button type="submit"&gt;Reset Now&lt;/button&gt;
			&lt;/form&gt;
			&lt;div class="reset-message-area"&gt;
				&lt;p class="performing"&gt;Resetting...&lt;/p&gt;
				&lt;p class="finished"&gt;Reset Done!&lt;/p&gt;
				&lt;p class="recipe-error-msg"&gt;Error removing includes. Please remove manually.&lt;/p&gt;
			&lt;/div&gt;
		&lt;/div&gt;
		&lt;/div&gt;
		&lt;div class="right"&gt;
		&lt;div class="ts-membership"&gt;
			&lt;h2&gt;
				Add Member
				&lt;a href="http://docs.tiddlyspace.com/What%20is%20a%20member%3F" title="What is a Member?" class="help"&gt;What is a Member?&lt;/a&gt;
			&lt;/h2&gt;
			&lt;div&gt;
				&lt;p&gt;Add a new member to your space by entering their name below. Enter a space name instead and prefix with @ to add everyone who is already a member of that space.&lt;/p&gt;
				&lt;form class="ts-members"&gt;
					&lt;input class="inputBox" type="text" name="username"&gt;
					&lt;input type="submit" value="Add Member" class="btn" /&gt;
				&lt;/form&gt;
			&lt;/div&gt;
			&lt;h2&gt;
				Existing Members &lt;button class='toggleNext'&gt;&lt;/button&gt;
			&lt;/h2&gt;
			&lt;div&gt;
				Your space currently has the following members: 
				&lt;ul class="ts-members"&gt;&lt;/ul&gt;
			&lt;/div&gt;
			&lt;h2&gt;
				Include Space
				&lt;a class="help" href="http://docs.tiddlyspace.com/What%20is%20space%20inclusion%3F" title="What is inclusion?"&gt;What is Inclusion?&lt;/a&gt;
			&lt;/h2&gt;
			&lt;form class="ts-includes"&gt;
				&lt;input class="inputBox" type="text" name="spacename"&gt;
				&lt;input type="submit" value="Include Space" class="btn" /&gt;
			&lt;/form&gt;
		&lt;/div&gt;
		&lt;div&gt;
			&lt;h2&gt;Included Spaces &lt;button class='toggleNext'&gt;&lt;/button&gt;&lt;/h2&gt;
			&lt;div&gt;
			This space includes the following spaces:
			&lt;ul class="ts-includes"&gt;&lt;/ul&gt;
			&lt;/div&gt;
		&lt;/div&gt;
		&lt;/div&gt;
		&lt;div class="clear"&gt;&lt;/div&gt;
	&lt;/div&gt;
&lt;/div&gt;
&lt;script src='/bags/common/tiddlers/backstage.js'&gt;&lt;/script&gt;
&lt;script src='/bags/common/tiddlers/jquery.js'&gt;&lt;/script&gt;
&lt;script src='/bags/tiddlyspace/tiddlers/chrjs'&gt;&lt;/script&gt;
&lt;script src='/bags/common/tiddlers/chrjs.space'&gt;&lt;/script&gt;
&lt;script src='/bags/common/tiddlers/chrjs.users'&gt;&lt;/script&gt;
&lt;script src='/bags/common/tiddlers/chrjs.identities'&gt;&lt;/script&gt;
&lt;script src='/bags/tiddlyspace/tiddlers/TiddlySpaceCSRF'&gt;&lt;/script&gt;
&lt;script src='/bags/common/tiddlers/jquery-form.js'&gt;&lt;/script&gt;
&lt;script src="/bags/common/tiddlers/siteiconupload.js"&gt;&lt;/script&gt;
&lt;script src="/bags/common/tiddlers/ts.js"&gt;&lt;/script&gt;
&lt;script src="/status.js"&gt;&lt;/script&gt;
&lt;script src="/bags/common/tiddlers/space.js"&gt;&lt;/script&gt;
&lt;/body&gt;
&lt;/html&gt;</pre>
</div>
<div title="GettingStarted [draft]" server.title="GettingStarted [draft]" server.page.revision="2564523" server.etag="&quot;honly-666_private/GettingStarted%20%5Bdraft%5D/2564523:8c58c653d92f761153d938d7b7b66aa55e9cce8e&quot;" modifier="honly-666" creator="honly-666" server.workspace="bags/honly-666_private" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="honly-666_private" server.permissions="read, write, create, delete" server.content-type="" modified="20160924143039" created="20160921035917" tags="不怕后悔 不留遗憾" publish.name="GettingStarted" _hash="2fd076160505568eb26d7efe11a7af0962413cf3">
<pre>&lt;html&gt;

 &lt;body&gt;


&lt;embed src="http://file01.16sucai.com/d/file/2014-01-16/13898530095157.jpg
/multiPlayer.swf" type="application/x-shockwave-flash" width="400" height="300" wmode="opaque"&gt;&lt;/embed&gt;
&lt;div align="center"&gt;
&lt;h1&gt;&lt;marquee behavior=alternate&gt;
人生就像心电图 必须折腾起来
&lt;br&gt;&lt;img src="t01be7e79362a809ea5.jpg"height="400"width="500"&gt;&lt;br&gt;


&lt;/div&gt;&lt;div align="center"&gt;
&lt;h1&gt;&lt;font color="blue"face="宋体"size="20"&gt;哈尼&lt;/font&gt;&lt;br/&gt;&lt;h1&gt;

你永远不知到明天和意外哪个先来&lt;br/&gt;

想要做的事要抓紧做&lt;br/&gt;

没说出口的话要记得说&lt;br/&gt;

无论如何&lt;br/&gt;

都希望我喜欢的你们能平平安安的过完这一生&lt;br/&gt;&lt;/div&gt;&lt;/marquee&gt;&lt;/h1&gt;&lt;br&gt;
     



  &lt;p style="color:#DC143C;font-size:30px;font-family: "微软雅黑"";
 &lt;br&gt; 人生就像心电图&lt;/br&gt;
          &lt;br&gt;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;必须折腾起来！&lt;/br&gt;
  &lt;/p&gt;

 &lt;/body&gt;
&lt;/html&gt;
&lt;html&gt;
&lt;p fontsize:60px;&gt; &amp;copy版权所有    贵州财经大学   魏玉婷&lt;/p&gt;
&lt;/html&gt;</pre>
</div>
<div title="robots" server.title="robots" server.page.revision="1521875" server.etag="&quot;system-info_public/robots/1521875:7e702a36d4d413a6376556bf4b3fe40b94eaee83&quot;" modifier="None" creator="None" server.workspace="bags/system-info_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-info_public" server.permissions="read" server.content-type="text/plain" modified="20130530195018" created="20130530195018" tags="excludeLists excludeSearch" _hash="35333958a4be1e71dffd5f713170f41c5785914a">
<pre>User-agent: *
Disallow: /bags
Disallow: /recipes</pre>
</div>
<div title="ErrorHandler" server.title="ErrorHandler" server.page.revision="1521896" server.etag="&quot;tiddlyspace/ErrorHandler/1521896:d8da0e919e061c40554a85cdcad6683b2fba0c36&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/tiddlyspace" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="tiddlyspace" server.permissions="read" server.content-type="text/javascript" modified="20131111192332" created="20131111192332" tags="excludeLists excludeSearch systemConfig" _hash="ffff853197a5561dfaef34fd40efbb0c738fbc79">
<pre>/***
|''Name''|ErrorHandlerPlugin|
|''Version''|0.4.3|
|''Author''|Jon Robson|
|''Description''|Localised tiddler save errors including edit conflict resolution.|
|''CoreVersion''|2.6.1|
|''Requires''|TiddlySpaceConfig|
***/
//{{{
(function($) {

var tiddlyspace = config.extensions.tiddlyspace;
var currentSpace = tiddlyspace.currentSpace.name;
tiddlyspace.getLocalTitle = function(title, workspace, suffix) {
	var endsWith = config.extensions.BinaryTiddlersPlugin.endsWith;
	if(!suffix) {
		var isPublic = endsWith(workspace, "_public");
		suffix = tiddlyspace.resolveSpaceName(workspace);
		if(currentSpace == suffix) {
			suffix = isPublic ? "public" : "private";
		} else {
			suffix = "@%0".format(suffix);
		}
	}
	return "%0 *(%1)*".format(title, suffix);
};

var sssp = config.extensions.ServerSideSavingPlugin;

var msgs = config.messages.editConflict = {
	loading: "Loading..",
	resolve: "[[Edit Conflict]]@glossary: this tiddler may have been changed by someone else.",
	reviewDiff: "review (recommended)",
	reviewDiffTooltip: "review changes made to this tiddler",
	reviewDiffError: "error retrieving revision.",
	save: "overwrite",
	saveTooltip: "make this revision the top revision of this tiddler",
	discard: "cancel",
	discardTooltip: "undo changes to this tiddler and get most recent version",
	diffTitle: "%0",
	diffFieldTitle: "%0 - fields",
	diffTextTitle: "%0 - text",
	updating: "updating your version...",
	diffHeader: ["Review the changes that have been made whilst you were editing this tiddler. ",
		"Fold relevant changes back into your version.\n",
		"{{removed{Red}}} highlight shows content removed. ",
		"{{added{Green}}} highlight shows content added.\n"].join(""),
	diffTextHeader: "View changes in text",
	diffFieldsHeader: "View changes in fields"
};

var plugin = config.extensions.errorHandler = {
	diffTags: ["excludeLists", "excludeMissing", "excludeSearch"],
	displayMessage: function(message, tiddler, context) {
		var desc = context &amp;&amp; context.httpStatus ? context.statusText :
			sssp.locale.connectionError;
		var reportArea = plugin.reportError(tiddler.title);
		var msg = $("&lt;div /&gt;").appendTo(reportArea);
		if(message == "saveConflict") {
			wikify(msgs.resolve, msg[0]);
			var choiceArea = $("&lt;div /&gt;").appendTo(reportArea)[0];
			plugin.editConflictHandler(choiceArea, tiddler);
		} else {
			msg.text(sssp.locale[message].format(tiddler.title, desc));
		}
	},
	editConflictHandler: function(container, tiddler) {
		var title = tiddler.title;
		var myrev = tiddler.fields["server.page.revision"];
		// note user now needs to edit, fix problem and save. 
		// TODO: make sure this gets reset in save callback
		store.getTiddler(title).fields["server.page.revision"] = "false";

		var diffBtn = createTiddlyButton(container, msgs.reviewDiff, msgs.reviewDiffTooltip, function(ev) {
			var title = $(ev.target).data("title");
			plugin.displayDiff(ev.target, store.getTiddler(title), myrev);
		});
		var saveBtn = createTiddlyButton(container, msgs.save, msgs.saveTooltip, function(ev) {
				var title = $(ev.target).data("title");
				var tid = store.saveTiddler(store.getTiddler(title));
				autoSaveChanges(null, [tid]);
			});
		var ignoreBtn = createTiddlyButton(container, msgs.discard, msgs.discardTooltip, function(ev) {
			var title = $(ev.target).text(msgs.updating).data("title");
			plugin.resetToServerVersion(store.getTiddler(title));
		});
		$([diffBtn, ignoreBtn, saveBtn]).data("title", title);
	},
	getDiffTiddlerTexts: function(diffText) {
		var chunks = diffText.split("\n  \n");
		if(chunks.length &lt; 2) {
			return [chunks[0], ""];
		} else {
			var diffFieldsText = "{{diff{\n%0\n}}}".format(chunks[0]);
			diffText = '{{diff{\n%0\n}}}'.format(chunks.splice(1, chunks.length).join("\n"));
			return [diffText, diffFieldsText];
		}
	},
	makeDiffTiddler: function(title, diff) {
		var newTiddler = new Tiddler(title);
		var tags = plugin.diffTags;
		newTiddler.text = msgs.loading;
		newTiddler.fields.doNotSave = true;
		newTiddler.tags = diff ? tags.concat(["diff"]) : tags;
		newTiddler = store.saveTiddler(newTiddler);
		$.extend(store.getTiddler(title).fields,
			config.defaultCustomFields); // allow option to save it
		return newTiddler;
	},
	displayDiff: function(src, tiddler, latestRevision) {
		var adaptor = tiddler.getAdaptor();
		var title = tiddler.title;
		var ts = new Date().formatString("0hh:0mm:0ss");
		var suffix = "edit conflict %0".format(ts);
		var diffTitle = tiddlyspace.getLocalTitle(msgs.diffTitle.format(title), "", suffix);
		var diffTextTitle = tiddlyspace.getLocalTitle(msgs.diffTextTitle.format(title), "", suffix);
		var diffFieldsTitle = tiddlyspace.getLocalTitle(msgs.diffFieldTitle.format(title), "", suffix);
		plugin.makeDiffTiddler(diffTextTitle, true);
		plugin.makeDiffTiddler(diffFieldsTitle, true);
		var newTiddler = plugin.makeDiffTiddler(diffTitle, false);
		newTiddler.text = ['%0\n&lt;&lt;slider chkViewDiffText "%1" "%2"&gt;&gt;\n',
			'&lt;&lt;slider chkViewDiffField "%3" "%4"&gt;&gt;'].join("").
			format(msgs.diffHeader, diffTextTitle, msgs.diffTextHeader,
				diffFieldsTitle, msgs.diffFieldsHeader);
		store.saveTiddler(newTiddler);

		var callback = function(r) {
			var text = plugin.getDiffTiddlerTexts(r);
			store.getTiddler(diffTextTitle).text = text[0];
			store.getTiddler(diffFieldsTitle).text = text[1];
			story.refreshTiddler(diffTitle, null, true);
		};
		var workspace = "bags/%0".format(tiddler.fields["server.bag"]);
		ajaxReq({
			type: "get",
			dataType: "text",
			url: "/diff?format=unified&amp;rev1=%0/%1/%2&amp;rev2=%0/%1".format(workspace, title, latestRevision),
			success: callback,
			error: function() {
				displayMessage(msgs.reviewDiffError);
			}
		});
		story.displayTiddler(src, diffTitle);
	},
	resetToServerVersion: function(tiddler) {
		var adaptor = tiddler.getAdaptor();
		var ctx = { 
			host: tiddler.fields["server.host"],
			workspace: "bags/" + tiddler.fields["server.bag"]
		};
		adaptor.getTiddler(tiddler.title, ctx, null, function(context) {
			store.saveTiddler(context.tiddler);
			story.refreshTiddler(tiddler.title);
			store.setDirty(false);
		});
	},
	reportError: function(title) {
		var el = story.getTiddler(title);
		if(!el) {
			el = story.displayTiddler(null, title);
		}
		return $("&lt;div /&gt;").addClass("error annotation").prependTo(el)[0];
	}
};

sssp.reportFailure = function(message, tiddler, context) {
	config.options.chkViewDiffText = config.options.chkViewDiffText === undefined ?
		true : config.options.chkViewDiffText;
	config.options.chkViewDiffFields = config.options.chkViewDiffFields || false;
	plugin.displayMessage(message, tiddler, context);
};

})(jQuery);
//}}}</pre>
</div>
<div title="How to socialise" server.title="How to socialise" server.page.revision="1521880" server.etag="&quot;system-info_public/How%20to%20socialise/1521880:3f4e4b9e072bee2a770d9c475137d9fe78135c40&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-info_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-info_public" server.permissions="read" server.content-type="" modified="20131111192330" created="20131111192330" tags="excludeLists excludeMissing excludeSearch" _hash="e730478f88ff38b560ebde4eaf4267b136bf6584">
<pre>There are a lot of interesting people using ~TiddlySpace that you might like to keep track of and interact with. There are a number of ways of doing this.

If you see a number in the speech bubble in one of your tiddlers, it means that someone is writing about the same thing as you. You can find out what they're saying by clicking on it. Likewise, if you see something interesting in someone else's space, you can respond to it and write up your own thoughts on the subject by clicking "Reply to this tiddler".

Additionally, if you find anyone interesting, or you find an interesting looking space and you'd like to know when it's changed, you can "follow" that space. To do this, simply create a tiddler with the title: {{{@space-name}}} and tag it {{{follow}}}. If you want, you can store some notes about that space in the body of the tiddler.

If you then want to know what happening, simply [[include|How do I include/exclude spaces?]]@docs the @tivity space and then visit your activity stream at [[/activity|/activity]], or just visit the @tapas space directly.

!Not sure who to follow?
Here's a few suggestions:
* @fnd
* @cdent
* @pmario
* @bengillies
* @dickon</pre>
</div>
<div title="TiddlySpaceTiddlerIconsPlugin" server.title="TiddlySpaceTiddlerIconsPlugin" server.page.revision="1521862" server.etag="&quot;system-plugins_public/TiddlySpaceTiddlerIconsPlugin/1521862:9ea2f0227e25ad09b603d8215b707612843ad51a&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-plugins_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-plugins_public" server.permissions="read" server.content-type="text/javascript" modified="20131111192330" created="20131111192330" tags="excludeLists excludeSearch systemConfig" _hash="5c6cfebcd3cc3fd2df109c0d59735aaae48850b4">
<pre>/***
|''Name''|TiddlySpaceTiddlerIconsPlugin|
|''Version''|0.8.10|
|''Status''|@@beta@@|
|''Author''|Jon Robson|
|''Description''|Provides ability to render SiteIcons and icons that correspond to the home location of given tiddlers|
|''Source''|http://github.com/TiddlySpace/tiddlyspace/raw/master/src/plugins/TiddlySpaceTiddlerIconsPlugin.js|
|''Requires''|TiddlySpaceConfig BinaryTiddlersPlugin ImageMacroPlugin TiddlySpacePublishingCommands|
!Notes
{{{&lt;&lt;tiddlerOrigin&gt;&gt;}}} shows the origin of the tiddler it is being run on.
In TiddlySpace terms this means it will determine whether the tiddler is external, public or private.
Where private it will analyse whether a public version exists and distinguish between the different scenarios.
If a tiddler is external, the SiteIcon of that external space will be shown

!Parameters
width / height : define a width or height of the outputted icon
label: if label parameter is set to yes, a label will accompany the icon.
!Code
***/
//{{{
(function($) {

if(!config.macros.image) {
	throw "Missing dependency: ImageMacroPlugin";
}

var imageMacro = config.macros.image;
var tiddlyspace = config.extensions.tiddlyspace;
var tweb = config.extensions.tiddlyweb;
var cmds = config.commands;
var cmd = cmds.publishTiddler;
tiddlyspace.resolveSpaceName = function(value) {
	var endsWith = config.extensions.BinaryTiddlersPlugin.endsWith;
	if(value) {
		value = value.indexOf("bags/") === 0 ? value.substr(5) : value;
		value = value.indexOf("recipes/") === 0 ? value.substr(8) : value;
		if(value.indexOf("@") === 0) {
			value = value.substr(1);
		}
		if(endsWith(value, "_public")) {
			value = value.substr(0, value.length - 7);
		} else if(endsWith(value, "_private")) {
			value = value.substr(0, value.length - 8);
		}
		value = value.toLowerCase();
	}
	return value;
};

tiddlyspace.renderAvatar = function(place, value, options) {
	options = options ? options : {};
	options.labelOptions = options.labelOptions ? options.labelOptions : { include: false, height: 48, width: 48 };
	options.imageOptions = options.imageOptions ? options.imageOptions : {};
	options.imageOptions.altImage = "/bags/common/tiddlers/defaultUserIcon";
	var container = $('&lt;div class="siteIcon" /&gt;').appendTo(place);
	value = tiddlyspace.resolveSpaceName(value);

	tweb.getStatus(function(status) {
		var link, noLabel;
		if(!value || value == config.views.wikified.defaultModifier ||
			value == config.views.wikified.shadowModifier) {
			var icon = config.views.wikified.shadowModifier == value ? "shadowIcon" : "missingIcon";
			if(store.tiddlerExists(icon)) {
				imageMacro.renderImage(container, icon, options.imageOptions);
			} else {
				noLabel = true;
			}
		} else {
			var spaceURI;
			if(value != tiddlyspace.currentSpace.name) {
				spaceURI = options.notSpace ? tiddlyspace.getHost(status.server_host) :
					tiddlyspace.getHost(status.server_host, value);
			}
			link = spaceURI ? $("&lt;a /&gt;").attr("href", spaceURI) : $("&lt;span /&gt;");
			link.text(value);

			var imageOptions = options.imageOptions;
			if(options.spaceLink &amp;&amp; !imageOptions.link) {
				imageOptions.link = spaceURI;
			}
			var avatar = options.notSpace ? false : value;
			var uri = tiddlyspace.getAvatar(status.server_host, avatar);
			imageMacro.renderImage(container, uri, options.imageOptions);
			if(!value) {
				value = "tiddlyspace";
			}
		}
		if(!noLabel &amp;&amp; options.labelOptions.include) {
			var prefix = $("&lt;span /&gt;").text(options.labelOptions.prefix || "")[0];
			var suffix = $("&lt;span /&gt;").text(options.labelOptions.suffix || "")[0];
			$('&lt;div class="label" /&gt;').append(prefix).append(link).
				append(suffix).appendTo(container);
		}
	});
	if(value) {
		var prefix = options.labelOptions.prefix || "";
		var suffix = options.labelOptions.suffix || "";
		var label = "%0%1%2".format(prefix, value, suffix);
		$(container).attr("title", label);
	}
};

var originMacro = config.macros.tiddlerOrigin = {
	locale: {
		"shadow": "shadow tiddler",
		"missing": "missing tiddler",
		"private": "private",
		"unknown": "unknown state",
		"public": "public",
		"unsyncedPrivate": "unsynced and private",
		"unsyncedPublic": "unsynced and public",
		externalPrefix: "from ",
		externalBagSuffix: " bag",
		externalSuffix: " space",
		publishPrivateDeletePrivate: "Are you sure you want to make this tiddler public?",
		moveToPrivate: "Are you sure you want to make this tiddler private? Only members will be able to see it.",
		pleaseWait: "please wait..",
		keepPublic: "keep public",
		cannotPublishDirtyTiddler: "The current tiddler is unsaved so cannot be published. Please save the tiddler first.",
		keepPrivate: "keep private",
		makePublic: "make public",
		makePrivate: "make private"
	},
	handler: function(place, macroName, params,wikifier, paramString, tiddler){
		var adaptor = tiddler.getAdaptor();
		var btn = $("&lt;div /&gt;").addClass("originButton").attr("params", paramString).
			attr("refresh", "macro").attr("macroName", macroName).appendTo(place)[0];
		$(btn).data("tiddler", tiddler);
		originMacro.refresh(btn);
	},
	refresh: function(btn) {
		$(btn).empty();
		var paramString = $(btn).attr("params");
		var tiddler = $(btn).data("tiddler");
		var options = originMacro.getOptions(paramString);
		var type = tiddlyspace.getTiddlerStatusType(tiddler);
		originMacro.renderIcon(tiddler, type, btn, options);
	},
	getOptions: function(paramString) {
		paramString = "%0 label:no width:48 height:48 spaceLink:yes preserveAspectRatio:yes".format(paramString);
		var parsedParams = paramString.parseParams("name");
		var params = parsedParams[0].name;
		var options = {
			labelOptions: originMacro._getLabelOptions(parsedParams),
			imageOptions: imageMacro.getArguments(paramString, []),
			noclick: parsedParams[0].interactive &amp;&amp;
				parsedParams[0].interactive[0] == "no" ? true : false
		};
		if(!options.noclick) {
			var spaceLink = parsedParams[0].spaceLink;
			options.spaceLink = spaceLink &amp;&amp; spaceLink[0] == "no" ? false : true;
		} else {
			options.spaceLink = false;
		}
		return options;
	},
	_getLabelOptions: function(parsedParams) {
		parsedParams = parsedParams[0];
		var includeLabel = !parsedParams.label || ( parsedParams.label &amp;&amp; parsedParams.label[0] == "yes" );
		var prefix = parsedParams.labelPrefix ? parsedParams.labelPrefix[0] : false;
		var suffix = parsedParams.labelSuffix ? parsedParams.labelSuffix[0] : false;
		return { include: includeLabel, suffix: suffix, prefix: prefix };
	},
	_isSpace: function(value) {
		value = value ? value : "";
		var endsWith = config.extensions.BinaryTiddlersPlugin.endsWith;
		if(endsWith(value, "_private") || endsWith(value, "_public")) {
			return true;
		} else {
			return false;
		}
	},
	renderIcon: function(tiddler, type, button, options) {
		var locale = originMacro.locale;
		originMacro.annotateTiddler(button, type);
		if(type != "external") {
			originMacro.showPrivacyRoundel(tiddler, type, button,
				options);
		} else {
			var prefix = options.labelOptions.prefix, suffix = options.labelOptions.suffix;
			var space = tiddler.fields["server.bag"];
			options.notSpace = !originMacro._isSpace(space);
			options.labelOptions.prefix = prefix ? prefix : locale.externalPrefix;
			options.labelOptions.suffix = suffix ? suffix : (options.notSpace ? locale.externalBagSuffix : locale.externalSuffix);

			tiddlyspace.renderAvatar(button, space, options);
		}
	},
	showPrivacyRoundel: function(thisTiddler, privacyType, button, options) {
		// there is a public tiddler as well as the current tiddler!
		// TODO: not this is not enough.. we also need to check if the public tiddler is the same as..
		// .. the private tiddler to determine whether this is a draft
		// use of hashes would be useful here.
		$(button).empty();
		var icon = "%0Icon".format(privacyType);
		if(privacyType.indexOf("unsynced") === 0 &amp;&amp; !store.tiddlerExists(icon)) {
			icon = "unsyncedIcon";
		}
		if(privacyType == "shadow") {
			if(!store.tiddlerExists(icon)) {
				icon = "bags/tiddlyspace/tiddlers/SiteIcon";
			}
		}
		if(privacyType == "missing" &amp;&amp; !store.tiddlerExists(icon)) {
			return; // the user is not making use of the missingIcon
		} else {
			imageMacro.renderImage(button, icon, options.imageOptions);
			originMacro.showLabel(button, privacyType, options.labelOptions);
			var cmd = originMacro.iconCommands[privacyType];
			if(cmd &amp;&amp; thisTiddler &amp;&amp; !options.noclick) {
				$(button).click(function(ev) {
					cmd(ev, thisTiddler);
				});
			}
		}
	},
	annotateTiddler: function(place, type) {
		var tidEl = $(story.findContainingTiddler(place));
		tidEl.
			removeClass("private public external privateAndPublic privateNotPublic shadow").
			addClass(type);
	},
	showLabel: function(button, type, options) {
		var locale = originMacro.locale;
		var label = options.label ? options.label : locale[type];
		label = label ? label : locale.unknown;
		if(options &amp;&amp; options.include) {
			$('&lt;div class="roundelLabel" /&gt;').html(label).appendTo(button);
		}
		$(button).attr("title", label);
	},
	confirm: function(ev, msg, onYes, options) {
		options = options ? options : {};
		onYes = onYes ? onYes : function(ev) {};
		var btn = $(".originButton", $(ev.target).parents())[0];
		var popup = Popup.create(btn);
		$(popup).addClass("confirmationPopup");
		$("&lt;div /&gt;").addClass("message").text(msg).appendTo(popup);
		$("&lt;button /&gt;").addClass("button").text(options.yesLabel || "yes").appendTo(popup).click(onYes);
		$("&lt;button /&gt;").addClass("button").text(options.noLabel || "no").click(function(ev) {
			Popup.remove();
		}).appendTo(popup);
		Popup.show();
		ev.stopPropagation();
		return false;
	},
	alert: function(ev, msg) {
		var popup = Popup.create(ev.target);
		$(popup).addClass("confirmationPopup alert");
		$("&lt;div /&gt;").addClass("message").text(msg).appendTo(popup);
		Popup.show();
		ev.stopPropagation();
	},
	reportDirty: function(el) {
		originMacro.alert(el, originMacro.locale.cannotPublishDirtyTiddler);
	},
	iconCommands: {
		"public": function(ev, tiddler) {
			if(!readOnly) {
				var locale = originMacro.locale;
				var msg = locale.moveToPrivate;
				if(story.isDirty(tiddler.title)) {
					originMacro.reportDirty(ev);
				} else {
					originMacro.confirm(ev, msg, function(ev) {
						var target = $(ev.target);
						var onComplete = function(info) {};
						var privateBag = cmd.toggleBag(tiddler, "private");
						cmd.moveTiddler(tiddler, {
							title: tiddler.title,
							fields: { "server.bag": privateBag }
						}, onComplete);
					}, { yesLabel: locale.makePrivate, noLabel: locale.keepPublic });
				}
			}
		},
		"private": function(ev, tiddler) {
			if(!readOnly) {
				var locale = originMacro.locale;
				var adaptor = tiddler.getAdaptor();
				var publishTo = tiddler.fields["publish.name"] || tiddler.title;
				var workspace = "bags/%0".format(tiddler.fields["server.bag"]);
				tiddler.fields["server.workspace"] = workspace;
				var publicBag = cmd.toggleBag(tiddler, "public");
				var msg;
				msg = locale.publishPrivateDeletePrivate;
				var title = tiddler.title;
				var newTitle = publishTo || tiddler.title;
				tiddler.fields["server.page.revision"] = "false";
				store.addTiddler(tiddler);
				if(story.isDirty(tiddler.title)) {
					originMacro.reportDirty(ev);
				} else {
					originMacro.confirm(ev, msg, function(ev) {
						var onComplete = function(info) {};
						cmd.moveTiddler(tiddler, {
							title: newTitle,
							fields: { "server.bag": publicBag }
						}, onComplete);
					}, { yesLabel: locale.makePublic, noLabel: locale.keepPrivate });
				}
			}
		}
	}
};

})(jQuery);
//}}}</pre>
</div>
<div title="ServerSideSavingPlugin" server.title="ServerSideSavingPlugin" server.page.revision="1521853" server.etag="&quot;system/ServerSideSavingPlugin/1521853:1487a9af6a763b0f27807353d340c2e38e7f386d&quot;" modifier="FND" creator="FND" server.workspace="bags/system" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system" server.permissions="read" server.content-type="text/javascript" modified="20130924180405" created="20130924180405" tags="excludeLists excludeSearch systemConfig" _hash="d72cde071d926d9c66939444817d7e8621d24d9c">
<pre>/***
|''Name''|ServerSideSavingPlugin|
|''Description''|server-side saving|
|''Author''|FND|
|''Version''|0.6.5|
|''Status''|stable|
|''Source''|http://svn.tiddlywiki.org/Trunk/association/plugins/ServerSideSavingPlugin.js|
|''License''|[[BSD|http://www.opensource.org/licenses/bsd-license.php]]|
|''CoreVersion''|2.5.3|
|''Keywords''|serverSide|
!Notes
This plugin relies on a dedicated adaptor to be present.
The specific nature of this plugin depends on the respective server.
!Revision History
!!v0.1 (2008-11-24)
* initial release
!!v0.2 (2008-12-01)
* added support for local saving
!!v0.3 (2008-12-03)
* added Save to Web macro for manual synchronization
!!v0.4 (2009-01-15)
* removed ServerConfig dependency by detecting server type from the respective tiddlers
!!v0.5 (2009-08-25)
* raised CoreVersion to 2.5.3 to take advantage of core fixes
!!v0.6 (2010-04-21)
* added notification about cross-domain restrictions to ImportTiddlers
!To Do
* conflict detection/resolution
* rename to ServerLinkPlugin?
* document deletion/renaming convention
!Code
***/
//{{{
(function($) {

readOnly = false; //# enable editing over HTTP

var plugin = config.extensions.ServerSideSavingPlugin = {};

plugin.locale = {
	saved: "%0 saved successfully",
	saveError: "Error saving %0: %1",
	saveConflict: "Error saving %0: edit conflict",
	deleted: "Removed %0",
	deleteError: "Error removing %0: %1",
	deleteLocalError: "Error removing %0 locally",
	removedNotice: "This tiddler has been deleted.",
	connectionError: "connection could not be established",
	hostError: "Unable to import from this location due to cross-domain restrictions."
};

plugin.sync = function(tiddlers) {
	tiddlers = tiddlers &amp;&amp; tiddlers[0] ? tiddlers : store.getTiddlers();
	$.each(tiddlers, function(i, tiddler) {
		var changecount = parseInt(tiddler.fields.changecount, 10);
		if(tiddler.fields.deleted === "true" &amp;&amp; changecount === 1) {
			plugin.removeTiddler(tiddler);
		} else if(tiddler.isTouched() &amp;&amp; !tiddler.doNotSave() &amp;&amp;
				tiddler.getServerType() &amp;&amp; tiddler.fields["server.host"]) { // XXX: server.host could be empty string
			delete tiddler.fields.deleted;
			plugin.saveTiddler(tiddler);
		}
	});
};

plugin.saveTiddler = function(tiddler) {
	try {
		var adaptor = this.getTiddlerServerAdaptor(tiddler);
	} catch(ex) {
		return false;
	}
	var context = {
		tiddler: tiddler,
		changecount: tiddler.fields.changecount,
		workspace: tiddler.fields["server.workspace"]
	};
	var serverTitle = tiddler.fields["server.title"]; // indicates renames
	if(!serverTitle) {
		tiddler.fields["server.title"] = tiddler.title;
	} else if(tiddler.title != serverTitle) {
		return adaptor.moveTiddler({ title: serverTitle },
			{ title: tiddler.title }, context, null, this.saveTiddlerCallback);
	}
	var req = adaptor.putTiddler(tiddler, context, {}, this.saveTiddlerCallback);
	return req ? tiddler : false;
};

plugin.saveTiddlerCallback = function(context, userParams) {
	var tiddler = context.tiddler;
	if(context.status) {
		if(tiddler.fields.changecount == context.changecount) { //# check for changes since save was triggered
			tiddler.clearChangeCount();
		} else if(tiddler.fields.changecount &gt; 0) {
			tiddler.fields.changecount -= context.changecount;
		}
		plugin.reportSuccess("saved", tiddler);
		store.setDirty(false);
	} else {
		if(context.httpStatus == 412) {
			plugin.reportFailure("saveConflict", tiddler);
		} else {
			plugin.reportFailure("saveError", tiddler, context);
		}
	}
};

plugin.removeTiddler = function(tiddler) {
	try {
		var adaptor = this.getTiddlerServerAdaptor(tiddler);
	} catch(ex) {
		return false;
	}
	var context = {
		host: tiddler.fields["server.host"],
		workspace: tiddler.fields["server.workspace"],
		tiddler: tiddler
	};
	var req = adaptor.deleteTiddler(tiddler, context, {}, this.removeTiddlerCallback);
	return req ? tiddler : false;
};

plugin.removeTiddlerCallback = function(context, userParams) {
	var tiddler = context.tiddler;
	if(context.status) {
		if(tiddler.fields.deleted === "true") {
			store.deleteTiddler(tiddler.title);
		} else {
			plugin.reportFailure("deleteLocalError", tiddler);
		}
		plugin.reportSuccess("deleted", tiddler);
		store.setDirty(false);
	} else {
		plugin.reportFailure("deleteError", tiddler, context);
	}
};

plugin.getTiddlerServerAdaptor = function(tiddler) { // XXX: rename?
	var type = tiddler.fields["server.type"] || config.defaultCustomFields["server.type"];
	return new config.adaptors[type]();
};

plugin.reportSuccess = function(msg, tiddler) {
	displayMessage(plugin.locale[msg].format([tiddler.title]));
};

plugin.reportFailure = function(msg, tiddler, context) {
	var desc = (context &amp;&amp; context.httpStatus) ? context.statusText :
		plugin.locale.connectionError;
	displayMessage(plugin.locale[msg].format([tiddler.title, desc]));
};

config.macros.saveToWeb = { // XXX: hijack existing sync macro?
	locale: { // TODO: merge with plugin.locale?
		btnLabel: "save to web",
		btnTooltip: "synchronize changes",
		btnAccessKey: null
	},

	handler: function(place, macroName, params, wikifier, paramString, tiddler) {
		createTiddlyButton(place, this.locale.btnLabel, this.locale.btnTooltip,
			plugin.sync, null, null, this.locale.btnAccessKey);
	}
};

// hijack saveChanges to trigger remote saving
var _saveChanges = saveChanges;
saveChanges = function(onlyIfDirty, tiddlers) {
	if(window.location.protocol == "file:") {
		_saveChanges.apply(this, arguments);
	} else {
		plugin.sync(tiddlers);
	}
};

// override removeTiddler to flag tiddler as deleted -- XXX: use hijack to preserve compatibility?
TiddlyWiki.prototype.removeTiddler = function(title) { // XXX: should override deleteTiddler instance method?
	var tiddler = this.fetchTiddler(title);
	if(tiddler) {
		tiddler.tags = ["excludeLists", "excludeSearch", "excludeMissing"];
		tiddler.text = plugin.locale.removedNotice;
		tiddler.fields.deleted = "true"; // XXX: rename to removed/tiddlerRemoved?
		tiddler.fields.changecount = "1";
		this.notify(title, true);
		this.setDirty(true);
	}
};

// hijack ImportTiddlers wizard to handle cross-domain restrictions
var _onOpen = config.macros.importTiddlers.onOpen;
config.macros.importTiddlers.onOpen = function(ev) {
	var btn = $(resolveTarget(ev));
	var url = btn.closest(".wizard").find("input[name=txtPath]").val();
	if(window.location.protocol != "file:" &amp;&amp; url.indexOf("://") != -1) {
		var host = url.split("/")[2];
		var macro = config.macros.importTiddlers;
		if(host != window.location.host) {
			btn.text(macro.cancelLabel).attr("title", macro.cancelPrompt);
			btn[0].onclick = macro.onCancel;
			$('&lt;span class="status" /&gt;').text(plugin.locale.hostError).insertAfter(btn);
			return false;
		}
	}
	return _onOpen.apply(this, arguments);
};

})(jQuery);
//}}}</pre>
</div>
<div title="GroupByPlugin" server.title="GroupByPlugin" server.page.revision="1521873" server.etag="&quot;system-plugins_public/GroupByPlugin/1521873:18f2a75dfcf3558ce6b03a0dd24f6fcf2b9ed373&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-plugins_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-plugins_public" server.permissions="read" server.content-type="text/javascript" modified="20131111192330" created="20131111192330" tags="excludeLists excludeSearch systemConfig" _hash="d4f41fa53916a920347fbe97303966ebeed68945">
<pre>/***
|''Name''|GroupByPlugin|
|''Description''|Mimics allTags macro to provide ways of creating lists grouping tiddlers by any field|
|''Version''|0.6.1|
|''Author''|Jon Robson|
|''Status''|beta|
!Usage
{{{&lt;&lt;groupBy tags&gt;&gt;}}}
mimics allTags macro

{{{&lt;&lt;groupBy server.bag&gt;&gt;}}}
groups by the server.bag field (this version contains TiddlySpace specific code for turning a bag into a space name)

{{{groupBy modified dateFormat:"YYYY"}}}
group tiddlers by year.

{{{&lt;&lt;groupBy tags exclude:excludeLists exclude:systemConfig&gt;&gt;}}}
group tiddlers by tag but exclude the tags with values excludeLists and systemConfig

Within that group you can also exclude things by filter
{{{groupBy modifier filter:[tag[film]]}}}
will group tiddlers tagged with film by modifier.
***/
//{{{
(function($) {
var taglocale = config.views.wikified.tag;
var macro = config.macros.groupBy = {
	locale: {
		tooltip: "all tiddlers in group %0",
		noTiddlers: "no tiddlers",
		openAllText: taglocale.openAllText,
		openAllTooltip: taglocale.openAllTooltip,
		openTiddler: "open tiddler with title %0"
	},
	morpher: {
		// TODO: note currently the following 2 morphers are TiddlySpace specific and probably should be in separate plugin
		"server.workspace": function(value, options) {
			return macro.morpher["server.bag"](value.replace("bags/", "").replace("recipes/", ""));
		},
		"server.bag": function(value, options) {
			if(typeof(value) !== "string") {
				return false;
			} else if(value.indexOf("_public") === -1 &amp;&amp; value.indexOf("_private") === -1) {
				value = "*%0".format(value); // add star for non-space bags.
			}
			return value.replace("_public", "").replace("_private", "");
		},
		created: function(value, options) {
			return value.formatString(options.dateFormat || "DD MMM YYYY");
		},
		modified: function(value, options) {
			return macro.morpher.created(value, options);
		}
	},

	handler: function(place, macroName, params, wikifier, paramString) {
		var field = params[0] || "server.workspace";
		var dateFormat = params[1] || "DD MMM YYYY";
		var container = $("&lt;div /&gt;").attr("macroName", macroName).addClass("groupBy").
			attr("refresh", "macro").attr("fieldName", field).
			attr("paramString", paramString).
			attr("dateFormat", dateFormat).appendTo(place)[0];
		macro.refresh(container);
	},
	isTypeArray: function(value) {
		var valueType = typeof value;
		if(valueType === "object" &amp;&amp; typeof value.length === "number" &amp;&amp;
			!(value.propertyIsEnumerable("length")) &amp;&amp;
			typeof value.splice === "function") { //is Array
			return true;
		} else {
			return false;
		}
	},
	_onClickGroup: function(ev, options) {
		var i, target = ev.target, locale = macro.locale;
		var tiddlers = $(target).closest(".templateContainer").data("tiddlers");
		var popup = $(Popup.create(target)).addClass("taggedTiddlerList")[0];
		var value = $(target).attr("value");
		var openAll = createTiddlyButton($("&lt;li /&gt;").appendTo(popup)[0],
			locale.openAllText.format(value), locale.openAllTooltip);
		$(openAll).click(function(ev) {
			story.displayTiddlers(ev.target, tiddlers);
			return false;
		});
		var listBreak = $("&lt;li /&gt;").addClass("listBreak").html("&lt;div /&gt;").appendTo(popup);
		for(i = 0; i &lt; tiddlers.length; i++) {
			var item = $("&lt;li /&gt;").appendTo(popup)[0];
			var template = store.getTiddlerText(options.template) || macro.template;
			wikify(template, item, null, tiddlers[i]);
		}
		listBreak.clone().appendTo(popup);
		$(createTiddlyLink($("&lt;li /&gt;").appendTo(popup)[0], value, false)).
			text(locale.openTiddler.format(value));
		Popup.show();
		ev.stopPropagation();
		return false;
	},
	_refresh: function(container, tiddlers, options) {
		var totalGroups = 0, locale = macro.locale, i, j;
		var excludeValues = options.exclude;
		var values = {}, value_ids = [];
		var field = options.field;
		var morpher = macro.morpher[field] || function(value) {
			return value;
		};
		for(i = 0; i &lt; tiddlers.length; i++) {
			var tiddler = tiddlers[i];
			var value = tiddler[field] || tiddler.fields[field];
			value = macro.isTypeArray(value) ? value : [ value ];
			for(j = 0; j &lt; value.length; j++) {
				var v = morpher(value[j], options);
				if(v &amp;&amp; $.inArray(v, excludeValues) === -1) {
					totalGroups += 1;
					if(!values[v]) {
						values[v] = [];
					}
					values[v].push(tiddler);
					value_ids.pushUnique(v);
				}
			}
		}
		var ul = $("&lt;ul /&gt;").appendTo(container)[0];
		if(totalGroups === 0) {
			$("&lt;li /&gt;").addClass("listTitle").text(locale.noTiddlers);
		}
		value_ids = value_ids.sort();
		var groupTemplate = store.getTiddlerText(options.groupTemplate);
		var onClick = function(ev) {
			macro._onClickGroup(ev, options);
		};
		for(i = 0; i &lt; value_ids.length; i++) {
			var title = value_ids[i];
			var info = getTiddlyLinkInfo(title);
			tiddlers = values[title];
			var btn = createTiddlyButton($("&lt;li /&gt;").appendTo(ul)[0],
				"%0 (%1)".format(title, tiddlers.length), locale.tooltip.format(title), null, info.classes);
			if(groupTemplate) {
				$(btn).empty();
				wikify(groupTemplate, btn, null, tiddlers[0]);
			}
			$(btn).click(onClick).attr("value", title).attr("refresh", "link").attr("tiddlyLink", title);
			$(btn).addClass("templateContainer").data("tiddlers", tiddlers);
		}
	},
	refresh: function(container) {
		container = $(container).empty();
		var paramString = container.attr("paramString");
		var args = paramString.parseParams("name", null, true, false, true)[0];
		var options = { field: container.attr("fieldName"), dateFormat: container.attr("dateFormat"), exclude: args.exclude || [],
			template: args.template ? args.template[0] : false, groupTemplate: args.groupTemplate ? args.groupTemplate[0] : "" };
		var tiddlers = args.filter ? store.filterTiddlers(args.filter[0]) : store.getTiddlers("title");
		macro._refresh(container, tiddlers, options);
	},
	template: "&lt;&lt;view title link&gt;&gt;"
};

}(jQuery));
//}}}</pre>
</div>
<div title="TiddlySpaceViewTypes" server.title="TiddlySpaceViewTypes" server.page.revision="1521869" server.etag="&quot;system-plugins_public/TiddlySpaceViewTypes/1521869:71232be5fe2ead4b1a8452c9e047621c2312adef&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-plugins_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-plugins_public" server.permissions="read" server.content-type="text/javascript" modified="20131111192330" created="20131111192330" tags="excludeLists excludeSearch systemConfig" _hash="0a5a070cb32ab7b3dc724809555448e9948cf232">
<pre>/***
|''Name''|TiddlySpaceViewTypes|
|''Version''|0.6.0|
|''Status''|@@beta@@|
|''Description''|Provides TiddlySpace specific view types|
|''Author''|Jon Robson|
|''Source''|http://github.com/TiddlySpace/tiddlyspace/raw/master/src/plugins/TiddlySpaceViewTypes.js|
|''Requires''|TiddlySpaceConfig TiddlySpaceTiddlerIconsPlugin|
!Usage
Provides replyLink, spaceLink and SiteIcon view types.
!!SiteIcon view parameters
* labelPrefix / labelSuffix : prefix or suffix the label with additional text. eg. labelPrefix:'modified by '
* spaceLink: if set to "yes" will make any avatars link to the corresponding space. {{{&lt;&lt;originMacro spaceLink:yes&gt;&gt;}}}

!Code
***/
//{{{
(function($) {

var tiddlyspace = config.extensions.tiddlyspace;
var originMacro = config.macros.tiddlerOrigin;
var tweb = config.extensions.tiddlyweb;

config.macros.view.replyLink = {
	locale: {
		label: "Reply to this tiddler"
	}
};

var _replyButtons = [];
var _replyInitialised, _replyScriptLoaded;
config.macros.view.views.replyLink = function(value, place, params, wikifier,
		paramString, tiddler) {
	var valueField = params[0];
	var imported;
	if(valueField == "title") { // special casing for imported tiddlers
		var localTitle = tiddler.title;
		var serverTitle = tiddler.fields["server.title"];
		if(serverTitle &amp;&amp; localTitle != serverTitle) {
			value = serverTitle ? serverTitle : localTitle;
			imported = true;
		}
	} else {
		title = tiddler[valueField] ? tiddler[valueField] : tiddler.fields[valueField];
	}
	var args = paramString.parseParams("anon")[0];
	var label = (args.label) ? args.label : config.macros.view.replyLink.locale.label;
	var space;
	if(tiddler) {
		var bag = tiddler.fields["server.bag"];
		space = tiddlyspace.resolveSpaceName(bag);
	}
	var container = $('&lt;span class="replyLink" /&gt;').appendTo(place)[0];

	tweb.getUserInfo(function(user) {
		if ((!user.anon) &amp;&amp; ((space &amp;&amp; user.name != space &amp;&amp;
				user.name != tiddlyspace.currentSpace.name) || imported)) {
			var link = $("&lt;a /&gt;")
				.text(config.macros.view.replyLink.locale.label)
				.appendTo(container)[0];

			if(typeof(createReplyButton) === "undefined") {
				_replyButtons.push(link);
			}
			if(_replyInitialised) {
				createReplyButton(link);
			} else if(!_replyScriptLoaded) {
				_replyScriptLoaded = true;
				$.getScript("/bags/common/tiddlers/_reply-button.js",
					function() {
						_replyInitialised = true;
						for(var i = 0; i &lt; _replyButtons.length; i++) {
							createReplyButton(_replyButtons[i]);
						}
						_replyButtons = [];
					});
			}
		}
	});

};

config.macros.view.views.spaceLink = function(value, place, params, wikifier,
		paramString, tiddler) {
		var spaceName = tiddlyspace.resolveSpaceName(value);
		var isBag = params[0] == "server.bag" &amp;&amp; value === spaceName ? true : false;
		var args = paramString.parseParams("anon")[0];
		var titleField = args.anon[2];
		var labelField = args.labelField ? args.labelField[0] : false;
		var label;
		if(labelField) {
			label = tiddler[labelField] ? tiddler[labelField] : tiddler.fields[labelField];
		} else {
			label = args.label ? args.label[0] : false;
		}
		var title = tiddler[titleField] ? tiddler[titleField] : tiddler.fields[titleField];

		var link = createSpaceLink(place, spaceName, title, label, isBag);
		if(args.external &amp;&amp; args.external[0] == "no") {
			$(link).click(function(ev) {
				var el = $(ev.target);
				var title = el.attr("tiddler");
				var bag = el.attr("bag");
				var space = el.attr("tiddlyspace");
				bag = space ? space + "_public" : bag;
				if(title &amp;&amp; bag) {
					ev.preventDefault();
					tiddlyspace.displayServerTiddler(el[0], title,
						"bags/" + bag);
				}
				return false;
			});
		}
};

config.macros.view.views.SiteIcon = function(value, place, params, wikifier,
		paramString, tiddler) {
	var options = originMacro.getOptions(paramString);
	if(!tiddler || value == "None") { // some core tiddlers lack modifier
		value = false;
	}
	var field = params[0];
	if(field == "server.bag") {
		options.notSpace = !originMacro._isSpace(value);
	}
	tiddlyspace.renderAvatar(place, value, options);
};

})(jQuery);
//}}}</pre>
</div>
<div title="DiffFormatter" server.title="DiffFormatter" server.page.revision="1521854" server.etag="&quot;system/DiffFormatter/1521854:6302f9b1cbff3f859c207a58de4b9c3d81713591&quot;" modifier="FND" creator="FND" server.workspace="bags/system" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system" server.permissions="read" server.content-type="text/javascript" modified="20130924180405" created="20130924180405" tags="excludeLists excludeSearch systemConfig" _hash="2232cd0549946d29c475cec846de3378177301ae">
<pre>/***
|''Name''|DiffFormatter|
|''Description''|highlighting of text comparisons|
|''Author''|FND|
|''Version''|0.9.0|
|''Status''|beta|
|''Source''|http://svn.tiddlywiki.org/Trunk/contributors/FND/formatters/DiffFormatter.js|
|''CodeRepository''|http://svn.tiddlywiki.org/Trunk/contributors/FND/|
|''License''|[[BSD|http://www.opensource.org/licenses/bsd-license.php]]|
|''Keywords''|formatting|
!Description
Highlights changes in a unified [[diff|http://en.wikipedia.org/wiki/Diff#Unified_format]].
!Notes
Based on Martin Budden's [[DiffFormatterPlugin|http://svn.tiddlywiki.org/Trunk/contributors/MartinBudden/formatters/DiffFormatterPlugin.js]].
!Usage
The formatter is applied to blocks wrapped in &lt;html&gt;&lt;code&gt;{{{diff{..}}}&lt;/code&gt;&lt;/html&gt; within tiddlers tagged with "diff".
!Revision History
!!v0.9 (2010-04-07)
* initial release; fork of DiffFormatterPlugin
!StyleSheet
.diff { white-space: pre; font-family: monospace; }
.diff ins, .diff del { display: block; text-decoration: none; }
.diff ins { background-color: #dfd; }
.diff del { background-color: #fdd; }
.diff .highlight { background-color: [[ColorPalette::SecondaryPale]]; }
!Code
***/
//{{{
(function() {

config.shadowTiddlers.StyleSheetDiffFormatter = store.getTiddlerText(tiddler.title + "##StyleSheet");
store.addNotification("StyleSheetDiffFormatter", refreshStyles);

var formatters = [{
		name: "diffWrapper",
		match: "^\\{\\{diff\\{\n", // XXX: suboptimal
		termRegExp: /(.*\}\}\})$/mg,
		handler: function(w) {
			var el = createTiddlyElement(w.output, "div", null, "diff");
			w.subWikifyTerm(el, this.termRegExp);
		}
	}, {
		name: "diffRange",
		match: "^(?:@@|[+\\-]{3}) ",
		lookaheadRegExp: /^(?:@@|[+\-]{3}) .*\n/mg,
		handler: function(w) {
			createTiddlyElement(w.output, "div", null, "highlight").
				innerHTML = "&amp;#8230;";
			this.lookaheadRegExp.lastIndex = w.matchStart;
			var lookaheadMatch = this.lookaheadRegExp.exec(w.source);
			if(lookaheadMatch &amp;&amp; lookaheadMatch.index == w.matchStart) {
				w.nextMatch = this.lookaheadRegExp.lastIndex;
			}
		}
	}, {
		name: "diffAdded",
		match: "^\\+",
		termRegExp: /(\n)/mg,
		handler: function(w) {
			var el = createTiddlyElement(w.output, "ins", null, "added");
			w.subWikifyTerm(el, this.termRegExp);
		}
	}, {
		name: "diffRemoved",
		match: "^-",
		termRegExp: /(\n)/mg,
		handler: function(w) {
			var el = createTiddlyElement(w.output, "del", null, "removed");
			w.subWikifyTerm(el, this.termRegExp);
		}
	}
];

config.parsers.diffFormatter = new Formatter(formatters);
config.parsers.diffFormatter.format = "diff";
config.parsers.diffFormatter.formatTag = "diff";

})();
//}}}</pre>
</div>
<div title="saveDraft" server.title="saveDraft" server.page.revision="1521925" server.etag="&quot;system-images_public/saveDraft/1521925:57c26b9b4f890da2079f2f589d4f3f0349a5c461&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-images_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-images_public" server.permissions="read" server.content-type="image/svg+xml" modified="20131111192332" created="20131111192332" tags="excludeLists excludeSearch" _hash="8b5516d12e2aafb4aecd48f696fcb276e61ac468">
<pre>&lt;svg xmlns="http://www.w3.org/2000/svg" xmlns:xl="http://www.w3.org/1999/xlink" version="1.1" viewBox="364 157 64 51" width="30" height="30"&gt;&lt;g stroke="none" stroke-opacity="1" stroke-dasharray="none" fill="none" fill-opacity="1"&gt;&lt;g&gt;&lt;path class="glyph" d="M 364.50006 184.50061 L 386.99985 207.00037 L 396 198.00002 L 373.50003 175.50066 Z M 403.02295 181.97704 C 400.38693 179.34099 396.11307 179.34099 393.47702 181.97704 C 390.841 184.61307 390.841 188.88695 393.47702 191.52298 C 396.11307 194.15903 400.38693 194.15903 403.02295 191.52298 C 405.65906 188.88695 405.65906 184.61307 403.02295 181.97704 M 414.27298 170.72704 C 411.63693 168.091 407.36307 168.091 404.72702 170.72704 C 402.091 173.36308 402.091 177.63693 404.72702 180.27296 C 407.36307 182.90901 411.63693 182.90901 414.27298 180.27296 C 416.90903 177.63693 416.90903 173.36308 414.27298 170.72704 M 425.523 159.47705 C 422.88696 156.841 418.6131 156.841 415.97705 159.47705 C 413.341 162.11308 413.341 166.38695 415.97705 169.02295 C 418.6131 171.65903 422.88696 171.65903 425.523 169.02295 C 428.15906 166.38695 428.15906 162.11308 425.523 159.47705" fill="#020202"/&gt;&lt;/g&gt;&lt;/g&gt;&lt;/svg&gt;</pre>
</div>
<div title="TiddlySpaceCloneCommand" server.title="TiddlySpaceCloneCommand" server.page.revision="1521898" server.etag="&quot;tiddlyspace/TiddlySpaceCloneCommand/1521898:5f0467878234e52dfb287e73d2f607891191d45f&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/tiddlyspace" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="tiddlyspace" server.permissions="read" server.content-type="text/javascript" modified="20131111192332" created="20131111192332" tags="excludeLists excludeSearch systemConfig" _hash="3ecfd7c955dc674752681565ad0ed68f8fcad5d9">
<pre>/***
|''Name''|TiddlySpaceCloneCommand|
|''Version''|0.5.8|
|''Description''|provides a toolbar command for cloning external tiddlers|
|''Status''|stable|
|''Source''|http://github.com/TiddlySpace/tiddlyspace/raw/master/src/plugins/TiddlySpaceCloneCommand.js|
|''Requires''|TiddlySpaceConfig TiddlySpaceFilters|
!Code
***/
//{{{
(function($) {

var cmd = config.commands;
var tiddlyspace = config.extensions.tiddlyspace;

var fieldsCache = {};

cmd.cloneTiddler = {
	text: cmd.editTiddler.text,
	tooltip: "Create a copy of this tiddler in the current space",
	errorMsg: "Error publishing %0: %1",

	isEnabled: function(tiddler) {
		return !config.filterHelpers.is.local(tiddler) &amp;&amp; !readOnly;
	},
	handler: function(ev, src, title) {
		var tiddler = store.getTiddler(title);
		if(tiddler) {
			fieldsCache[title] = $.extend({}, tiddler.fields);
			tiddler.fields["server.workspace"] = tiddlyspace.getCurrentWorkspace(config.options.chkPrivateMode ?
		"private" : "public");
			tiddler.fields["server.permissions"] = "read, write, create"; // no delete
			delete tiddler.fields["server.page.revision"];
			delete tiddler.fields["server.title"];
			delete tiddler.fields["server.etag"];
			// special handling for pseudo-shadow tiddlers
			if(tiddlyspace.coreBags.contains(tiddler.fields["server.bag"])) {
				tiddler.tags.remove("excludeLists");
			}
		} else { // ensure workspace is the current space
			var el = story.findContainingTiddler(src);
			el = $(el);
			var fields = el.attr("tiddlyfields");
			if(fields) { // inherited via TiddlyLink
				fields = fields.decodeHashMap();
				fields["server.workspace"] = config.
					defaultCustomFields["server.workspace"];
			} else {
				fields = config.defaultCustomFields;
			}
			fields = String.encodeHashMap(fields);
			el.attr("tiddlyfields", fields);
		}
		cmd.editTiddler.handler.apply(this, arguments);
		if(tiddler) {
			tiddler.fields["server.permissions"] += ", delete";
		}
		return false;
	}
};

cmd.editTiddler.isEnabled = function(tiddler) {
	return !cmd.cloneTiddler.isEnabled.apply(this, arguments);
};

// hijack cancelTiddler to restore original fields
var _cancelHandler = cmd.cancelTiddler.handler;
cmd.cancelTiddler.handler = function(ev, src, title) {
	var tiddler = store.getTiddler(title);
	if(tiddler) {
		tiddler.fields = fieldsCache[title] || tiddler.fields;
		delete fieldsCache[title];
	}
	return _cancelHandler.apply(this, arguments);
};

// hijack saveTiddler to clear unused fields stash
var _saveHandler = cmd.saveTiddler.handler;
cmd.saveTiddler.handler =  function(ev, src, title) {
	delete fieldsCache[title];
	return _saveHandler.apply(this, arguments);
};

})(jQuery);
//}}}</pre>
</div>
<div title="SideBarTabs" server.title="SideBarTabs" server.page.revision="1521918" server.etag="&quot;system-theme_public/SideBarTabs/1521918:946564d93583f52a591c2fab337704e15e15cb67&quot;" modifier="osmosoft" creator="osmosoft" server.workspace="bags/system-theme_public" server.type="tiddlyweb" server.host="http://honly-666.tiddlyspace.com" server.recipe="honly-666_private" server.bag="system-theme_public" server.permissions="read" server.content-type="" modified="20131111192330" created="20131111192330" tags="excludeLists excludeMissing excludeSearch" _hash="6b74609cea4ddb529f42d3331e63b7775376af47">
<pre>&lt;&lt;tiddler Backstage##Tiddlers&gt;&gt;</pre>
</div>
</div>
<!--POST-STOREAREA-->
<!--POST-BODY-START-->

<!--POST-BODY-END-->
<script id="jsArea" type="text/javascript">
//<![CDATA[

//
// Please note:
//
// * This code is designed to be readable but for compactness it only includes brief comments. You can see fuller comments
//   in the project repository at https://github.com/TiddlyWiki/tiddlywiki
//
// * You should never need to modify this source code directly. TiddlyWiki is carefully designed to allow deep customisation
//   without changing the core code. Please consult the development group at http://groups.google.com/group/TiddlyWikiDev
//
// JSLint directives
/*global jQuery:false, version:false */
/*jslint bitwise:true, browser:true, confusion:true, eqeq:true, evil:true, forin:true, maxerr:100, plusplus:true, regexp:true, sloppy:true, sub:true, undef:true, unparam:true, vars:true, white:true */
//--
//-- Configuration repository
//--

// Miscellaneous options
var config = {
	numRssItems: 20, // Number of items in the RSS feed
	animDuration: 400, // Duration of UI animations in milliseconds
	cascadeFast: 20, // Speed for cascade animations (higher == slower)
	cascadeSlow: 60, // Speed for EasterEgg cascade animations
	cascadeDepth: 5, // Depth of cascade animation
	locale: "en" // W3C language tag
};

// Hashmap of alternative parsers for the wikifier
config.parsers = {};

// Adaptors
config.adaptors = {};
config.defaultAdaptor = null;

// Backstage tasks
config.tasks = {};

// Annotations
config.annotations = {};

// Custom fields to be automatically added to new tiddlers
config.defaultCustomFields = {};

// Messages
config.messages = {
	messageClose: {},
	dates: {},
	tiddlerPopup: {}
};

// Options that can be set in the options panel and/or cookies
config.options = {
	chkRegExpSearch: false,
	chkCaseSensitiveSearch: false,
	chkIncrementalSearch: true,
	chkAnimate: true,
	chkSaveBackups: true,
	chkAutoSave: false,
	chkGenerateAnRssFeed: false,
	chkSaveEmptyTemplate: false,
	chkOpenInNewWindow: true,
	chkToggleLinks: false,
	chkHttpReadOnly: true,
	chkForceMinorUpdate: false,
	chkConfirmDelete: true,
	chkInsertTabs: false,
	chkUsePreForStorage: true, // Whether to use <pre> format for storage
	chkDisplayInstrumentation: false,
	txtBackupFolder: "",
	txtEditorFocus: "text",
	txtMainTab: "tabTimeline",
	txtMoreTab: "moreTabAll",
	txtMaxEditRows: "30",
	txtFileSystemCharSet: "UTF-8",
	txtTheme: ""
	};
config.optionsDesc = {};

config.optionsSource = {};

// Default tiddler templates
var DEFAULT_VIEW_TEMPLATE = 1;
var DEFAULT_EDIT_TEMPLATE = 2;
config.tiddlerTemplates = {
	1: "ViewTemplate",
	2: "EditTemplate"
};

// More messages (rather a legacy layout that should not really be like this)
config.views = {
	wikified: {
		tag: {}
	},
	editor: {
		tagChooser: {}
	}
};

// Backstage tasks
config.backstageTasks = ["save","importTask","tweak","upgrade","plugins"];

// Extensions
config.extensions = {};

// Macros; each has a 'handler' member that is inserted later
config.macros = {
	today: {},
	version: {},
	search: {sizeTextbox: 15},
	tiddler: {},
	tag: {},
	tags: {},
	tagging: {},
	timeline: {},
	allTags: {},
	list: {
		all: {},
		missing: {},
		orphans: {},
		shadowed: {},
		touched: {},
		filter: {}
	},
	closeAll: {},
	permaview: {},
	saveChanges: {},
	slider: {},
	option: {},
	options: {},
	newTiddler: {},
	newJournal: {},
	tabs: {},
	gradient: {},
	message: {},
	view: {defaultView: "text"},
	edit: {},
	tagChooser: {},
	toolbar: {},
	plugins: {},
	refreshDisplay: {},
	importTiddlers: {},
	upgrade: {
		source: "http://tiddlywiki-releases.tiddlyspace.com/upgrade",
		backupExtension: "pre.core.upgrade"
	},
	sync: {},
	annotations: {}
};

// Commands supported by the toolbar macro
config.commands = {
	closeTiddler: {},
	closeOthers: {},
	editTiddler: {},
	saveTiddler: {hideReadOnly: true},
	cancelTiddler: {},
	deleteTiddler: {hideReadOnly: true},
	permalink: {},
	references: {type: "popup"},
	jump: {type: "popup"},
	syncing: {type: "popup"},
	fields: {type: "popup"}
};

// Control of macro parameter evaluation
config.evaluateMacroParameters = "all";

// Basic regular expressions
config.textPrimitives = {
	upperLetter: "[A-Z\u00c0-\u00de\u0150\u0170]",
	lowerLetter: "[a-z0-9_\\-\u00df-\u00ff\u0151\u0171]",
	anyLetter:   "[A-Za-z0-9_\\-\u00c0-\u00de\u00df-\u00ff\u0150\u0170\u0151\u0171]",
	anyLetterStrict: "[A-Za-z0-9\u00c0-\u00de\u00df-\u00ff\u0150\u0170\u0151\u0171]"
};
if(!((new RegExp("[\u0150\u0170]","g")).test("\u0150"))) {
	config.textPrimitives = {
		upperLetter: "[A-Z\u00c0-\u00de]",
		lowerLetter: "[a-z0-9_\\-\u00df-\u00ff]",
		anyLetter:   "[A-Za-z0-9_\\-\u00c0-\u00de\u00df-\u00ff]",
		anyLetterStrict: "[A-Za-z0-9\u00c0-\u00de\u00df-\u00ff]"
	};
}
config.textPrimitives.sliceSeparator = "::";
config.textPrimitives.sectionSeparator = "##";
config.textPrimitives.urlPattern = "(?:file|http|https|mailto|ftp|irc|news|data):[^\\s'\"]+(?:/|\\b)";
config.textPrimitives.unWikiLink = "~";
config.textPrimitives.wikiLink = "(?:(?:" + config.textPrimitives.upperLetter + "+" +
	config.textPrimitives.lowerLetter + "+" +
	config.textPrimitives.upperLetter +
	config.textPrimitives.anyLetter + "*)|(?:" +
	config.textPrimitives.upperLetter + "{2,}" +
	config.textPrimitives.lowerLetter + "+))";

config.textPrimitives.cssLookahead = "(?:(" + config.textPrimitives.anyLetter + "+)\\(([^\\)\\|\\n]+)(?:\\):))|(?:(" + config.textPrimitives.anyLetter + "+):([^;\\|\\n]+);)";
config.textPrimitives.cssLookaheadRegExp = new RegExp(config.textPrimitives.cssLookahead,"mg");

config.textPrimitives.brackettedLink = "\\[\\[([^\\]]+)\\]\\]";
config.textPrimitives.titledBrackettedLink = "\\[\\[([^\\[\\]\\|]+)\\|([^\\[\\]\\|]+)\\]\\]";
config.textPrimitives.tiddlerForcedLinkRegExp = new RegExp("(?:" + config.textPrimitives.titledBrackettedLink + ")|(?:" +
	config.textPrimitives.brackettedLink + ")|(?:" +
	config.textPrimitives.urlPattern + ")","mg");
config.textPrimitives.tiddlerAnyLinkRegExp = new RegExp("("+ config.textPrimitives.wikiLink + ")|(?:" +
	config.textPrimitives.titledBrackettedLink + ")|(?:" +
	config.textPrimitives.brackettedLink + ")|(?:" +
	config.textPrimitives.urlPattern + ")","mg");

config.glyphs = {
	currBrowser: null,
	browsers: [],
	codes: {}
};

//--
//-- Shadow tiddlers
//--

config.shadowTiddlers = {
	StyleSheet: "",
	MarkupPreHead: "",
	MarkupPostHead: "",
	MarkupPreBody: "",
	MarkupPostBody: "",
	TabTimeline: '<<timeline>>',
	TabAll: '<<list all>>',
	TabTags: '<<allTags excludeLists>>',
	TabMoreMissing: '<<list missing>>',
	TabMoreOrphans: '<<list orphans>>',
	TabMoreShadowed: '<<list shadowed>>',
	AdvancedOptions: '<<options>>',
	PluginManager: '<<plugins>>',
	SystemSettings: '',
	ToolbarCommands: '|~ViewToolbar|closeTiddler closeOthers +editTiddler > fields syncing permalink references jump|\n|~EditToolbar|+saveTiddler -cancelTiddler deleteTiddler|',
	WindowTitle: '<<tiddler SiteTitle>> - <<tiddler SiteSubtitle>>'
};

// Browser detection... In a very few places, there's nothing else for it but to know what browser we're using.
config.userAgent = navigator.userAgent.toLowerCase();
config.browser = {
	isIE: config.userAgent.indexOf("msie") != -1 && config.userAgent.indexOf("opera") == -1,
	isGecko: navigator.product == "Gecko" && config.userAgent.indexOf("WebKit") == -1,
	ieVersion: /MSIE (\d{1,2}.\d)/i.exec(config.userAgent), // config.browser.ieVersion[1], if it exists, will be the IE version string, eg "6.0"
	isSafari: config.userAgent.indexOf("applewebkit") != -1,
	isBadSafari: !((new RegExp("[\u0150\u0170]","g")).test("\u0150")),
	firefoxDate: /gecko\/(\d{8})/i.exec(config.userAgent), // config.browser.firefoxDate[1], if it exists, will be Firefox release date as "YYYYMMDD"
	isOpera: config.userAgent.indexOf("opera") != -1,
	isChrome: config.userAgent.indexOf('chrome') > -1,
	isLinux: config.userAgent.indexOf("linux") != -1,
	isUnix: config.userAgent.indexOf("x11") != -1,
	isMac: config.userAgent.indexOf("mac") != -1,
	isWindows: config.userAgent.indexOf("win") != -1
};

merge(config.glyphs,{
	browsers: [
		function() {return config.browser.isIE;},
		function() {return true;}
		],
	codes: {
		downTriangle: ["\u25BC","\u25BE"],
		downArrow: ["\u2193","\u2193"],
		bentArrowLeft: ["\u2190","\u21A9"],
		bentArrowRight: ["\u2192","\u21AA"]
	}
});

//--
//-- Translateable strings
//--

// Strings in "double quotes" should be translated; strings in 'single quotes' should be left alone

merge(config.options,{
	txtUserName: "YourName"});

merge(config.tasks,{
	save: {text: "save", tooltip: "Save your changes to this TiddlyWiki"},
	importTask: {text: "import", tooltip: "Import tiddlers and plugins from other TiddlyWiki files and servers", content: '<<importTiddlers>>'},
	tweak: {text: "tweak", tooltip: "Tweak the appearance and behaviour of TiddlyWiki", content: '<<options>>'},
	upgrade: {text: "upgrade", tooltip: "Upgrade TiddlyWiki core code", content: '<<upgrade>>'},
	plugins: {text: "plugins", tooltip: "Manage installed plugins", content: '<<plugins>>'}
});

// Options that can be set in the options panel and/or cookies
merge(config.optionsDesc,{
	txtUserName: "Username for signing your edits",
	chkRegExpSearch: "Enable regular expressions for searches",
	chkCaseSensitiveSearch: "Case-sensitive searching",
	chkIncrementalSearch: "Incremental key-by-key searching",
	chkAnimate: "Enable animations",
	chkSaveBackups: "Keep backup file when saving changes",
	chkAutoSave: "Automatically save changes",
	chkGenerateAnRssFeed: "Generate an RSS feed when saving changes",
	chkSaveEmptyTemplate: "Generate an empty template when saving changes",
	chkOpenInNewWindow: "Open external links in a new window",
	chkToggleLinks: "Clicking on links to open tiddlers causes them to close",
	chkHttpReadOnly: "Hide editing features when viewed over HTTP",
	chkForceMinorUpdate: "Don't update modifier username and date when editing tiddlers",
	chkConfirmDelete: "Require confirmation before deleting tiddlers",
	chkInsertTabs: "Use the tab key to insert tab characters instead of moving between fields",
	txtBackupFolder: "Name of folder to use for backups",
	txtMaxEditRows: "Maximum number of rows in edit boxes",
	txtTheme: "Name of the theme to use",
	txtFileSystemCharSet: "Default character set for saving changes (Firefox/Mozilla only)"});

merge(config.messages,{
	customConfigError: "Problems were encountered loading plugins. See PluginManager for details",
	pluginError: "Error: %0",
	pluginDisabled: "Not executed because disabled via 'systemConfigDisable' tag",
	pluginForced: "Executed because forced via 'systemConfigForce' tag",
	pluginVersionError: "Not executed because this plugin needs a newer version of TiddlyWiki",
	nothingSelected: "Nothing is selected. You must select one or more items first",
	savedSnapshotError: "It appears that this TiddlyWiki has been incorrectly saved. Please see http://www.tiddlywiki.com/#Download for details",
	subtitleUnknown: "(unknown)",
	undefinedTiddlerToolTip: "The tiddler '%0' doesn't yet exist",
	shadowedTiddlerToolTip: "The tiddler '%0' doesn't yet exist, but has a pre-defined shadow value",
	tiddlerLinkTooltip: "%0 - %1, %2",
	externalLinkTooltip: "External link to %0",
	noTags: "There are no tagged tiddlers",
	notFileUrlError: "You need to save this TiddlyWiki to a file before you can save changes",
	cantSaveError: "It's not possible to save changes. Possible reasons include:\n- your browser doesn't support saving (Firefox, Internet Explorer, Safari and Opera all work if properly configured)\n- the pathname to your TiddlyWiki file contains illegal characters\n- the TiddlyWiki HTML file has been moved or renamed",
	invalidFileError: "The original file '%0' does not appear to be a valid TiddlyWiki",
	backupSaved: "Backup saved",
	backupFailed: "Failed to save backup file",
	rssSaved: "RSS feed saved",
	rssFailed: "Failed to save RSS feed file",
	emptySaved: "Empty template saved",
	emptyFailed: "Failed to save empty template file",
	mainSaved: "Main TiddlyWiki file saved",
	mainDownload: "Downloading/saving main TiddlyWiki file",
	mainDownloadManual: "RIGHT CLICK HERE to download/save main TiddlyWiki file",
	mainFailed: "Failed to save main TiddlyWiki file. Your changes have not been saved",
	macroError: "Error in macro <<%0>>",
	macroErrorDetails: "Error while executing macro <<%0>>:\n%1",
	missingMacro: "No such macro",
	overwriteWarning: "A tiddler named '%0' already exists. Choose OK to overwrite it",
	unsavedChangesWarning: "WARNING! There are unsaved changes in TiddlyWiki\n\nChoose OK to save\nChoose CANCEL to discard",
	confirmExit: "--------------------------------\n\nThere are unsaved changes in TiddlyWiki. If you continue you will lose those changes\n\n--------------------------------",
	saveInstructions: "SaveChanges",
	unsupportedTWFormat: "Unsupported TiddlyWiki format '%0'",
	tiddlerSaveError: "Error when saving tiddler '%0'",
	tiddlerLoadError: "Error when loading tiddler '%0'",
	wrongSaveFormat: "Cannot save with storage format '%0'. Using standard format for save.",
	invalidFieldName: "Invalid field name %0",
	fieldCannotBeChanged: "Field '%0' cannot be changed",
	loadingMissingTiddler: "Attempting to retrieve the tiddler '%0' from the '%1' server at:\n\n'%2' in the workspace '%3'",
	upgradeDone: "The upgrade to version %0 is now complete\n\nClick 'OK' to reload the newly upgraded TiddlyWiki",
	invalidCookie: "Invalid cookie '%0'"});

merge(config.messages.messageClose,{
	text: "close",
	tooltip: "close this message area"});

config.messages.backstage = {
	open: {text: "backstage", tooltip: "Open the backstage area to perform authoring and editing tasks"},
	close: {text: "close", tooltip: "Close the backstage area"},
	prompt: "backstage: ",
	decal: {
		edit: {text: "edit", tooltip: "Edit the tiddler '%0'"}
	}
};

config.messages.listView = {
	tiddlerTooltip: "Click for the full text of this tiddler",
	previewUnavailable: "(preview not available)"
};

config.messages.dates.months = ["January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November","December"];
config.messages.dates.days = ["Sunday", "Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday"];
config.messages.dates.shortMonths = ["Jan", "Feb", "Mar", "Apr", "May", "Jun", "Jul", "Aug", "Sep", "Oct", "Nov", "Dec"];
config.messages.dates.shortDays = ["Sun", "Mon", "Tue", "Wed", "Thu", "Fri", "Sat"];
// suffixes for dates, eg "1st","2nd","3rd"..."30th","31st"
config.messages.dates.daySuffixes = ["st","nd","rd","th","th","th","th","th","th","th",
		"th","th","th","th","th","th","th","th","th","th",
		"st","nd","rd","th","th","th","th","th","th","th",
		"st"];
config.messages.dates.am = "am";
config.messages.dates.pm = "pm";

merge(config.messages.tiddlerPopup,{
	});

merge(config.views.wikified.tag,{
	labelNoTags: "no tags",
	labelTags: "tags: ",
	openTag: "Open tag '%0'",
	tooltip: "Show tiddlers tagged with '%0'",
	openAllText: "Open all",
	openAllTooltip: "Open all of these tiddlers",
	popupNone: "No other tiddlers tagged with '%0'"});

merge(config.views.wikified,{
	defaultText: "The tiddler '%0' doesn't yet exist. Double-click to create it",
	defaultModifier: "(missing)",
	shadowModifier: "(built-in shadow tiddler)",
	dateFormat: "DD MMM YYYY",
	createdPrompt: "created"});

merge(config.views.editor,{
	tagPrompt: "Type tags separated with spaces, [[use double square brackets]] if necessary, or add existing",
	defaultText: "Type the text for '%0'"});

merge(config.views.editor.tagChooser,{
	text: "tags",
	tooltip: "Choose existing tags to add to this tiddler",
	popupNone: "There are no tags defined",
	tagTooltip: "Add the tag '%0'"});

merge(config.messages,{
	sizeTemplates:
		[
		{unit: 1024*1024*1024, template: "%0\u00a0GB"},
		{unit: 1024*1024, template: "%0\u00a0MB"},
		{unit: 1024, template: "%0\u00a0KB"},
		{unit: 1, template: "%0\u00a0B"}
		]});

merge(config.macros.search,{
	label: "search",
	prompt: "Search this TiddlyWiki",
	placeholder: "",
	accessKey: "F",
	successMsg: "%0 tiddlers found matching %1",
	failureMsg: "No tiddlers found matching %0"});

merge(config.macros.tagging,{
	label: "tagging: ",
	labelNotTag: "not tagging",
	tooltip: "List of tiddlers tagged with '%0'"});

merge(config.macros.timeline,{
	dateFormat: "DD MMM YYYY"});

merge(config.macros.allTags,{
	tooltip: "Show tiddlers tagged with '%0'",
	noTags: "There are no tagged tiddlers"});

config.macros.list.all.prompt = "All tiddlers in alphabetical order";
config.macros.list.missing.prompt = "Tiddlers that have links to them but are not defined";
config.macros.list.orphans.prompt = "Tiddlers that are not linked to from any other tiddlers";
config.macros.list.shadowed.prompt = "Tiddlers shadowed with default contents";
config.macros.list.touched.prompt = "Tiddlers that have been modified locally";

merge(config.macros.closeAll,{
	label: "close all",
	prompt: "Close all displayed tiddlers (except any that are being edited)"});

merge(config.macros.permaview,{
	label: "permaview",
	prompt: "Link to an URL that retrieves all the currently displayed tiddlers"});

merge(config.macros.saveChanges,{
	label: "save changes",
	prompt: "Save all tiddlers to create a new TiddlyWiki",
	accessKey: "S"});

merge(config.macros.newTiddler,{
	label: "new tiddler",
	prompt: "Create a new tiddler",
	title: "New Tiddler",
	accessKey: "N"});

merge(config.macros.newJournal,{
	label: "new journal",
	prompt: "Create a new tiddler from the current date and time",
	accessKey: "J"});

merge(config.macros.options,{
	wizardTitle: "Tweak advanced options",
	step1Title: "These options are saved in cookies in your browser",
	step1Html: "<input type='hidden' name='markList'></input><br><input type='checkbox' checked='false' name='chkUnknown'>Show unknown options</input>",
	unknownDescription: "//(unknown)//",
	listViewTemplate: {
		columns: [
			{name: 'Option', field: 'option', title: "Option", type: 'String'},
			{name: 'Description', field: 'description', title: "Description", type: 'WikiText'},
			{name: 'Name', field: 'name', title: "Name", type: 'String'}
			],
		rowClasses: [
			{className: 'lowlight', field: 'lowlight'}
			]}
	});

merge(config.macros.plugins,{
	wizardTitle: "Manage plugins",
	step1Title: "Currently loaded plugins",
	step1Html: "<input type='hidden' name='markList'></input>", // DO NOT TRANSLATE
	skippedText: "(This plugin has not been executed because it was added since startup)",
	noPluginText: "There are no plugins installed",
	confirmDeleteText: "Are you sure you want to delete these plugins:\n\n%0",
	removeLabel: "remove systemConfig tag",
	removePrompt: "Remove systemConfig tag",
	deleteLabel: "delete",
	deletePrompt: "Delete these tiddlers forever",
	listViewTemplate: {
		columns: [
			{name: 'Selected', field: 'Selected', rowName: 'title', type: 'Selector'},
			{name: 'Tiddler', field: 'tiddler', title: "Tiddler", type: 'Tiddler'},
			{name: 'Description', field: 'Description', title: "Description", type: 'String'},
			{name: 'Version', field: 'Version', title: "Version", type: 'String'},
			{name: 'Size', field: 'size', tiddlerLink: 'size', title: "Size", type: 'Size'},
			{name: 'Forced', field: 'forced', title: "Forced", tag: 'systemConfigForce', type: 'TagCheckbox'},
			{name: 'Disabled', field: 'disabled', title: "Disabled", tag: 'systemConfigDisable', type: 'TagCheckbox'},
			{name: 'Executed', field: 'executed', title: "Loaded", type: 'Boolean', trueText: "Yes", falseText: "No"},
			{name: 'Startup Time', field: 'startupTime', title: "Startup Time", type: 'String'},
			{name: 'Error', field: 'error', title: "Status", type: 'Boolean', trueText: "Error", falseText: "OK"},
			{name: 'Log', field: 'log', title: "Log", type: 'StringList'}
			],
		rowClasses: [
			{className: 'error', field: 'error'},
			{className: 'warning', field: 'warning'}
			]},
	listViewTemplateReadOnly: {
		columns: [
			{name: 'Tiddler', field: 'tiddler', title: "Tiddler", type: 'Tiddler'},
			{name: 'Description', field: 'Description', title: "Description", type: 'String'},
			{name: 'Version', field: 'Version', title: "Version", type: 'String'},
			{name: 'Size', field: 'size', tiddlerLink: 'size', title: "Size", type: 'Size'},
			{name: 'Executed', field: 'executed', title: "Loaded", type: 'Boolean', trueText: "Yes", falseText: "No"},
			{name: 'Startup Time', field: 'startupTime', title: "Startup Time", type: 'String'},
			{name: 'Error', field: 'error', title: "Status", type: 'Boolean', trueText: "Error", falseText: "OK"},
			{name: 'Log', field: 'log', title: "Log", type: 'StringList'}
			],
		rowClasses: [
			{className: 'error', field: 'error'},
			{className: 'warning', field: 'warning'}
			]}
	});

merge(config.macros.toolbar,{
	moreLabel: "more",
	morePrompt: "Show additional commands",
	lessLabel: "less",
	lessPrompt: "Hide additional commands",
	separator: "|"
	});

merge(config.macros.refreshDisplay,{
	label: "refresh",
	prompt: "Redraw the entire TiddlyWiki display"
	});

merge(config.macros.importTiddlers,{
	readOnlyWarning: "You cannot import into a read-only TiddlyWiki file. Try opening it from a file:// URL",
	wizardTitle: "Import tiddlers from another file or server",
	step1Title: "Step 1: Locate the server or TiddlyWiki file",
	step1Html: "Specify the type of the server: <select name='selTypes'><option value=''>Choose...</option></select><br>Enter the URL or pathname here: <input type='text' size=50 name='txtPath'><br>...or browse for a file: <input type='file' size=50 name='txtBrowse'><br><hr>...or select a pre-defined feed: <select name='selFeeds'><option value=''>Choose...</option></select>",
	openLabel: "open",
	openPrompt: "Open the connection to this file or server",
	statusOpenHost: "Opening the host",
	statusGetWorkspaceList: "Getting the list of available workspaces",
	step2Title: "Step 2: Choose the workspace",
	step2Html: "Enter a workspace name: <input type='text' size=50 name='txtWorkspace'><br>...or select a workspace: <select name='selWorkspace'><option value=''>Choose...</option></select>",
	cancelLabel: "cancel",
	cancelPrompt: "Cancel this import",
	statusOpenWorkspace: "Opening the workspace",
	statusGetTiddlerList: "Getting the list of available tiddlers",
	errorGettingTiddlerList: "Error getting list of tiddlers, click Cancel to try again",
	errorGettingTiddlerListHttp404: "Error retrieving tiddlers from url, please ensure the url exists. Click Cancel to try again.",
	errorGettingTiddlerListHttp: "Error retrieving tiddlers from url, please ensure this url exists and is <a href='http://enable-cors.org/'>CORS</a> enabled",
	errorGettingTiddlerListFile: "Error retrieving tiddlers from local file, please make sure the file is in the same directory as your TiddlyWiki. Click Cancel to try again.",
	step3Title: "Step 3: Choose the tiddlers to import",
	step3Html: "<input type='hidden' name='markList'></input><br><input type='checkbox' checked='true' name='chkSync'>Keep these tiddlers linked to this server so that you can synchronise subsequent changes</input><br><input type='checkbox' name='chkSave'>Save the details of this server in a 'systemServer' tiddler called:</input> <input type='text' size=25 name='txtSaveTiddler'>",
	importLabel: "import",
	importPrompt: "Import these tiddlers",
	confirmOverwriteText: "Are you sure you want to overwrite these tiddlers:\n\n%0",
	step4Title: "Step 4: Importing %0 tiddler(s)",
	step4Html: "<input type='hidden' name='markReport'></input>", // DO NOT TRANSLATE
	doneLabel: "done",
	donePrompt: "Close this wizard",
	statusDoingImport: "Importing tiddlers",
	statusDoneImport: "All tiddlers imported",
	systemServerNamePattern: "%2 on %1",
	systemServerNamePatternNoWorkspace: "%1",
	confirmOverwriteSaveTiddler: "The tiddler '%0' already exists. Click 'OK' to overwrite it with the details of this server, or 'Cancel' to leave it unchanged",
	serverSaveTemplate: "|''Type:''|%0|\n|''URL:''|%1|\n|''Workspace:''|%2|\n\nThis tiddler was automatically created to record the details of this server",
	serverSaveModifier: "(System)",
	listViewTemplate: {
		columns: [
			{name: 'Selected', field: 'Selected', rowName: 'title', type: 'Selector'},
			{name: 'Tiddler', field: 'tiddler', title: "Tiddler", type: 'Tiddler'},
			{name: 'Size', field: 'size', tiddlerLink: 'size', title: "Size", type: 'Size'},
			{name: 'Tags', field: 'tags', title: "Tags", type: 'Tags'}
			],
		rowClasses: [
			]}
	});

merge(config.macros.upgrade,{
	wizardTitle: "Upgrade TiddlyWiki core code",
	step1Title: "Update or repair this TiddlyWiki to the latest release",
	step1Html: "You are about to upgrade to the latest release of the TiddlyWiki core code (from <a href='%0' class='externalLink' target='_blank'>%1</a>). Your content will be preserved across the upgrade.<br><br>Note that core upgrades have been known to interfere with older plugins. If you run into problems with the upgraded file, see <a href='http://www.tiddlywiki.org/wiki/CoreUpgrades' class='externalLink' target='_blank'>http://www.tiddlywiki.org/wiki/CoreUpgrades</a>",
	errorCantUpgrade: "Unable to upgrade this TiddlyWiki. You can only perform upgrades on TiddlyWiki files stored locally",
	errorNotSaved: "You must save changes before you can perform an upgrade",
	step2Title: "Confirm the upgrade details",
	step2Html_downgrade: "You are about to downgrade to TiddlyWiki version %0 from %1.<br><br>Downgrading to an earlier version of the core code is not recommended",
	step2Html_restore: "This TiddlyWiki appears to be already using the latest version of the core code (%0).<br><br>You can continue to upgrade anyway to ensure that the core code hasn't been corrupted or damaged",
	step2Html_upgrade: "You are about to upgrade to TiddlyWiki version %0 from %1",
	upgradeLabel: "upgrade",
	upgradePrompt: "Prepare for the upgrade process",
	statusPreparingBackup: "Preparing backup",
	statusSavingBackup: "Saving backup file",
	errorSavingBackup: "There was a problem saving the backup file",
	statusLoadingCore: "Loading core code",
	errorLoadingCore: "Error loading the core code",
	errorCoreFormat: "Error with the new core code",
	statusSavingCore: "Saving the new core code",
	statusReloadingCore: "Reloading the new core code",
	startLabel: "start",
	startPrompt: "Start the upgrade process",
	cancelLabel: "cancel",
	cancelPrompt: "Cancel the upgrade process",
	step3Title: "Upgrade cancelled",
	step3Html: "You have cancelled the upgrade process"
	});

merge(config.macros.annotations,{
	});

merge(config.commands.closeTiddler,{
	text: "close",
	tooltip: "Close this tiddler"});

merge(config.commands.closeOthers,{
	text: "close others",
	tooltip: "Close all other tiddlers"});

merge(config.commands.editTiddler,{
	text: "edit",
	tooltip: "Edit this tiddler",
	readOnlyText: "view",
	readOnlyTooltip: "View the source of this tiddler"});

merge(config.commands.saveTiddler,{
	text: "done",
	tooltip: "Save changes to this tiddler"});

merge(config.commands.cancelTiddler,{
	text: "cancel",
	tooltip: "Undo changes to this tiddler",
	warning: "Are you sure you want to abandon your changes to '%0'?",
	readOnlyText: "done",
	readOnlyTooltip: "View this tiddler normally"});

merge(config.commands.deleteTiddler,{
	text: "delete",
	tooltip: "Delete this tiddler",
	warning: "Are you sure you want to delete '%0'?"});

merge(config.commands.permalink,{
	text: "permalink",
	tooltip: "Permalink for this tiddler"});

merge(config.commands.references,{
	text: "references",
	tooltip: "Show tiddlers that link to this one",
	popupNone: "No references"});

merge(config.commands.jump,{
	text: "jump",
	tooltip: "Jump to another open tiddler"});

merge(config.commands.fields,{
	text: "fields",
	tooltip: "Show the extended fields of this tiddler",
	emptyText: "There are no extended fields for this tiddler",
	listViewTemplate: {
		columns: [
			{name: 'Field', field: 'field', title: "Field", type: 'String'},
			{name: 'Value', field: 'value', title: "Value", type: 'String'}
			],
		rowClasses: [
			],
		buttons: [
			]}});

merge(config.shadowTiddlers,{
	DefaultTiddlers: "[[GettingStarted]]",
	MainMenu: "[[GettingStarted]]",
	SiteTitle: "My TiddlyWiki",
	SiteSubtitle: "a reusable non-linear personal web notebook",
	SiteUrl: "",
	SideBarOptions: '<<search>><<closeAll>><<permaview>><<newTiddler>><<newJournal "DD MMM YYYY" "journal">><<saveChanges>><<slider chkSliderOptionsPanel OptionsPanel "options \u00bb" "Change TiddlyWiki advanced options">>',
	SideBarTabs: '<<tabs txtMainTab "Timeline" "Timeline" TabTimeline "All" "All tiddlers" TabAll "Tags" "All tags" TabTags "More" "More lists" TabMore>>',
	TabMore: '<<tabs txtMoreTab "Missing" "Missing tiddlers" TabMoreMissing "Orphans" "Orphaned tiddlers" TabMoreOrphans "Shadowed" "Shadowed tiddlers" TabMoreShadowed>>'
	});

merge(config.annotations,{
	AdvancedOptions: "This shadow tiddler provides access to several advanced options",
	ColorPalette: "These values in this shadow tiddler determine the colour scheme of the ~TiddlyWiki user interface",
	DefaultTiddlers: "The tiddlers listed in this shadow tiddler will be automatically displayed when ~TiddlyWiki starts up",
	EditTemplate: "The HTML template in this shadow tiddler determines how tiddlers look while they are being edited",
	GettingStarted: "This shadow tiddler provides basic usage instructions",
	ImportTiddlers: "This shadow tiddler provides access to importing tiddlers",
	MainMenu: "This shadow tiddler is used as the contents of the main menu in the left-hand column of the screen",
	MarkupPreHead: "This tiddler is inserted at the top of the <head> section of the TiddlyWiki HTML file",
	MarkupPostHead: "This tiddler is inserted at the bottom of the <head> section of the TiddlyWiki HTML file",
	MarkupPreBody: "This tiddler is inserted at the top of the <body> section of the TiddlyWiki HTML file",
	MarkupPostBody: "This tiddler is inserted at the end of the <body> section of the TiddlyWiki HTML file immediately after the script block",
	OptionsPanel: "This shadow tiddler is used as the contents of the options panel slider in the right-hand sidebar",
	PageTemplate: "The HTML template in this shadow tiddler determines the overall ~TiddlyWiki layout",
	PluginManager: "This shadow tiddler provides access to the plugin manager",
	SideBarOptions: "This shadow tiddler is used as the contents of the option panel in the right-hand sidebar",
	SideBarTabs: "This shadow tiddler is used as the contents of the tabs panel in the right-hand sidebar",
	SiteSubtitle: "This shadow tiddler is used as the second part of the page title",
	SiteTitle: "This shadow tiddler is used as the first part of the page title",
	SiteUrl: "This shadow tiddler should be set to the full target URL for publication",
	StyleSheetColors: "This shadow tiddler contains CSS definitions related to the color of page elements. ''DO NOT EDIT THIS TIDDLER'', instead make your changes in the StyleSheet shadow tiddler",
	StyleSheet: "This tiddler can contain custom CSS definitions",
	StyleSheetLayout: "This shadow tiddler contains CSS definitions related to the layout of page elements. ''DO NOT EDIT THIS TIDDLER'', instead make your changes in the StyleSheet shadow tiddler",
	StyleSheetLocale: "This shadow tiddler contains CSS definitions related to the translation locale",
	StyleSheetPrint: "This shadow tiddler contains CSS definitions for printing",
	SystemSettings: "This tiddler is used to store configuration options for this TiddlyWiki document",
	TabAll: "This shadow tiddler contains the contents of the 'All' tab in the right-hand sidebar",
	TabMore: "This shadow tiddler contains the contents of the 'More' tab in the right-hand sidebar",
	TabMoreMissing: "This shadow tiddler contains the contents of the 'Missing' tab in the right-hand sidebar",
	TabMoreOrphans: "This shadow tiddler contains the contents of the 'Orphans' tab in the right-hand sidebar",
	TabMoreShadowed: "This shadow tiddler contains the contents of the 'Shadowed' tab in the right-hand sidebar",
	TabTags: "This shadow tiddler contains the contents of the 'Tags' tab in the right-hand sidebar",
	TabTimeline: "This shadow tiddler contains the contents of the 'Timeline' tab in the right-hand sidebar",
	ToolbarCommands: "This shadow tiddler determines which commands are shown in tiddler toolbars",
	ViewTemplate: "The HTML template in this shadow tiddler determines how tiddlers look"
	});
//--
//-- Main
//--

var params = null; // Command line parameters
var store = null; // TiddlyWiki storage
var story = null; // Main story
var formatter = null; // Default formatters for the wikifier
var anim = typeof Animator == "function" ? new Animator() : null; // Animation engine
var readOnly = false; // Whether we're in readonly mode
var highlightHack = null; // Embarrassing hack department...
var hadConfirmExit = false; // Don't warn more than once
var safeMode = false; // Disable all plugins and cookies
var showBackstage; // Whether to include the backstage area
var installedPlugins = []; // Information filled in when plugins are executed
var startingUp = false; // Whether we're in the process of starting up
var pluginInfo,tiddler; // Used to pass information to plugins in loadPlugins()

// Whether this file can be saved back to the same location [Preemption]
window.allowSave = window.allowSave || function(l)
{
	return true;
}

// Whether this file is being viewed locally
window.isLocal = function()
{
	return (document.location.protocol == "file:");
}

// Whether to use the JavaSaver applet
var useJavaSaver = window.isLocal() && (config.browser.isSafari || config.browser.isOpera);

// Allow preemption code a chance to tweak config and useJavaSaver [Preemption]
if (window.tweakConfig) window.tweakConfig();

if(!window || !window.console) {
	console = {tiddlywiki:true,log:function(message) {displayMessage(message);}};
}

// Starting up
function main()
{
	window.originalHTML=recreateOriginal();

	var t10,t9,t8,t7,t6,t5,t4,t3,t2,t1,t0 = new Date();
	startingUp = true;
	var doc = jQuery(document);
	jQuery.noConflict();
	window.onbeforeunload = function(e) {if(window.confirmExit) return confirmExit();};
	params = getParameters();
	if(params)
		params = params.parseParams("open",null,false);
	store = new TiddlyWiki({config:config});
	invokeParamifier(params,"oninit");
	story = new Story("tiddlerDisplay","tiddler");
	addEvent(document,"click",Popup.onDocumentClick);
	saveTest();
	var s;
	for(s=0; s<config.notifyTiddlers.length; s++)
		store.addNotification(config.notifyTiddlers[s].name,config.notifyTiddlers[s].notify);
	t1 = new Date();
	loadShadowTiddlers();
	doc.trigger("loadShadows");
	t2 = new Date();
	store.loadFromDiv("storeArea","store",true);
	doc.trigger("loadTiddlers");
	loadOptions();
	t3 = new Date();
	invokeParamifier(params,"onload");
	t4 = new Date();
	readOnly = window.isLocal() ? false : config.options.chkHttpReadOnly;
	var pluginProblem = loadPlugins("systemConfig");
	doc.trigger("loadPlugins");
	t5 = new Date();
	formatter = new Formatter(config.formatters);
	invokeParamifier(params,"onconfig");
	story.switchTheme(config.options.txtTheme);
	showBackstage = showBackstage !== undefined ? showBackstage : !readOnly;
	t6 = new Date();
	var m;
	for(m in config.macros) {
		if(config.macros[m].init)
			config.macros[m].init();
	}
	t7 = new Date();
	store.notifyAll();
	t8 = new Date();
	restart();
	refreshDisplay();
	t9 = new Date();
	if(pluginProblem) {
		story.displayTiddler(null,"PluginManager");
		displayMessage(config.messages.customConfigError);
	}
	if(showBackstage)
		backstage.init();
	t10 = new Date();
	if(config.options.chkDisplayInstrumentation) {
		displayMessage("LoadShadows " + (t2-t1) + " ms");
		displayMessage("LoadFromDiv " + (t3-t2) + " ms");
		displayMessage("LoadPlugins " + (t5-t4) + " ms");
		displayMessage("Macro init " + (t7-t6) + " ms");
		displayMessage("Notify " + (t8-t7) + " ms");
		displayMessage("Restart " + (t9-t8) + " ms");
		displayMessage("Total: " + (t10-t0) + " ms");
	}
	startingUp = false;
	doc.trigger("startup");
}

// Called on unload. All functions called conditionally since they themselves may have been unloaded.
function unload()
{
	if(window.checkUnsavedChanges)
		checkUnsavedChanges();
	if(window.scrubNodes)
		scrubNodes(document.body);
}

// Restarting
function restart()
{
	invokeParamifier(params,"onstart");
	if(story.isEmpty()) {
		story.displayDefaultTiddlers();
	}
	window.scrollTo(0,0);
}

function saveTest()
{
	var s = document.getElementById("saveTest");
	if(s.hasChildNodes())
		alert(config.messages.savedSnapshotError);
	s.appendChild(document.createTextNode("savetest"));
}

function loadShadowTiddlers()
{
	var shadows = new TiddlyWiki();
	shadows.loadFromDiv("shadowArea","shadows",true);
	shadows.forEachTiddler(function(title,tiddler){config.shadowTiddlers[title] = tiddler.text;});
}

function loadPlugins(tag)
{
	if(safeMode)
		return false;
	var tiddlers = store.getTaggedTiddlers(tag);
	tiddlers.sort(function(a,b) {return a.title < b.title ? -1 : (a.title == b.title ? 0 : 1);});
	var toLoad = [];
	var nLoaded = 0;
	var map = {};
	var nPlugins = tiddlers.length;
	installedPlugins = [];
	var i;
	for(i=0; i<nPlugins; i++) {
		var p = getPluginInfo(tiddlers[i]);
		installedPlugins[i] = p;
		var n = p.Name || p.title;
		if(n)
			map[n] = p;
		n = p.Source;
		if(n)
			map[n] = p;
	}
	var visit = function(p) {
		if(!p || p.done)
			return;
		p.done = 1;
		var reqs = p.Requires;
		if(reqs) {
			reqs = reqs.readBracketedList();
			var i;
			for(i=0; i<reqs.length; i++)
				visit(map[reqs[i]]);
		}
		toLoad.push(p);
	};
	for(i=0; i<nPlugins; i++)
		visit(installedPlugins[i]);
	for(i=0; i<toLoad.length; i++) {
		p = toLoad[i];
		pluginInfo = p;
		tiddler = p.tiddler;
		if(isPluginExecutable(p)) {
			if(isPluginEnabled(p)) {
				p.executed = true;
				var startTime = new Date();
				try {
					if(tiddler.text)
						window.eval(tiddler.text);
					nLoaded++;
				} catch(ex) {
					p.log.push(config.messages.pluginError.format([exceptionText(ex)]));
					p.error = true;
					if(!console.tiddlywiki) {
						console.log("error evaluating " + tiddler.title, ex);
					}
				}
				pluginInfo.startupTime = String((new Date()) - startTime) + "ms";
			} else {
				nPlugins--;
			}
		} else {
			p.warning = true;
		}
	}
	return nLoaded != nPlugins;
}

function getPluginInfo(tiddler)
{
	var p = store.getTiddlerSlices(tiddler.title,["Name","Description","Version","Requires","CoreVersion","Date","Source","Author","License","Browsers"]);
	p.tiddler = tiddler;
	p.title = tiddler.title;
	p.log = [];
	return p;
}

// Check that a particular plugin is valid for execution
function isPluginExecutable(plugin)
{
	if(plugin.tiddler.isTagged("systemConfigForce")) {
		plugin.log.push(config.messages.pluginForced);
		return true;
	}
	if(plugin["CoreVersion"]) {
		var coreVersion = plugin["CoreVersion"].split(".");
		var w = parseInt(coreVersion[0],10) - version.major;
		if(w == 0 && coreVersion[1])
			w = parseInt(coreVersion[1],10) - version.minor;
		if(w == 0 && coreVersion[2])
			w = parseInt(coreVersion[2],10) - version.revision;
		if(w > 0) {
			plugin.log.push(config.messages.pluginVersionError);
			return false;
		}
	}
	return true;
}

function isPluginEnabled(plugin)
{
	if(plugin.tiddler.isTagged("systemConfigDisable")) {
		plugin.log.push(config.messages.pluginDisabled);
		return false;
	}
	return true;
}

//--
//-- Paramifiers
//--

function getParameters()
{
	var p = null;
	if(window.location.hash) {
		p = decodeURIComponent(window.location.hash.substr(1));
		if(config.browser.firefoxDate != null && config.browser.firefoxDate[1] < "20051111")
			p = convertUTF8ToUnicode(p);
	}
	return p;
}

function invokeParamifier(params,handler)
{
	if(!params || params.length == undefined || params.length <= 1)
		return;
	var i;
	for(i=1; i<params.length; i++) {
		var p = config.paramifiers[params[i].name];
		if(p && p[handler] instanceof Function)
			p[handler](params[i].value);
		else {
			var h = config.optionHandlers[params[i].name.substr(0,3)];
			if(h && h.set instanceof Function)
				h.set(params[i].name,params[i].value);
		}
	}
}

config.paramifiers = {};

config.paramifiers.start = {
	oninit: function(v) {
		safeMode = v.toLowerCase() == "safe";
	}
};

config.paramifiers.open = {
	onstart: function(v) {
		if(!readOnly || store.tiddlerExists(v) || store.isShadowTiddler(v))
			story.displayTiddler("bottom",v,null,false,null);
	}
};

config.paramifiers.story = {
	onstart: function(v) {
		var list = store.getTiddlerText(v,"").parseParams("open",null,false);
		invokeParamifier(list,"onstart");
	}
};

config.paramifiers.search = {
	onstart: function(v) {
		story.search(v,false,false);
	}
};

config.paramifiers.searchRegExp = {
	onstart: function(v) {
		story.prototype.search(v,false,true);
	}
};

config.paramifiers.tag = {
	onstart: function(v) {
		story.displayTiddlers(null,store.filterTiddlers("[tag["+v+"]]"),null,false,null);
	}
};

config.paramifiers.newTiddler = {
	onstart: function(v) {
		var args = v.parseParams("anon", null, null)[0];
		var title = args.title ? args.title[0] : v;
		var customFields = args.fields ? args.fields[0] : null;
		if(!readOnly) {
			story.displayTiddler(null,title,DEFAULT_EDIT_TEMPLATE,false,null,customFields);
			story.focusTiddler(title,"text");
			var i,tags = args.tag || [];
			for(i=0;i<tags.length;i++) {
				story.setTiddlerTag(title,tags[i],+1);
			}
		}
	}
};

config.paramifiers.newJournal = {
	onstart: function(v) {
		if(!readOnly) {
			var now = new Date();
			var title = now.formatString(v.trim());
			story.displayTiddler(null,title,DEFAULT_EDIT_TEMPLATE);
			story.focusTiddler(title,"text");
		}
	}
};

config.paramifiers.readOnly = {
	onconfig: function(v) {
		var p = v.toLowerCase();
		readOnly = p == "yes" ? true : (p == "no" ? false : readOnly);
	}
};

config.paramifiers.theme = {
	onconfig: function(v) {
		story.switchTheme(v);
	}
};

config.paramifiers.upgrade = {
	onstart: function(v) {
		upgradeFrom(v);
	}
};

config.paramifiers.recent= {
	onstart: function(v) {
		var titles=[];
		var i,tiddlers=store.getTiddlers("modified","excludeLists").reverse();
		for(i=0; i<v && i<tiddlers.length; i++)
			titles.push(tiddlers[i].title);
		story.displayTiddlers(null,titles);
	}
};

config.paramifiers.filter = {
	onstart: function(v) {
		story.displayTiddlers(null,store.filterTiddlers(v),null,false);
	}
};

//--
//-- Formatter helpers
//--

function Formatter(formatters)
{
	var n;
	this.formatters = [];
	var pattern = [];
	for(n=0; n<formatters.length; n++) {
		pattern.push("(" + formatters[n].match + ")");
		this.formatters.push(formatters[n]);
	}
	this.formatterRegExp = new RegExp(pattern.join("|"),"mg");
}

config.formatterHelpers = {

	createElementAndWikify: function(w)
	{
		w.subWikifyTerm(createTiddlyElement(w.output,this.element),this.termRegExp);
	},

	inlineCssHelper: function(w)
	{
		var styles = [];
		config.textPrimitives.cssLookaheadRegExp.lastIndex = w.nextMatch;
		var lookaheadMatch = config.textPrimitives.cssLookaheadRegExp.exec(w.source);
		while(lookaheadMatch && lookaheadMatch.index == w.nextMatch) {
			var s,v;
			if(lookaheadMatch[1]) {
				s = lookaheadMatch[1].unDash();
				v = lookaheadMatch[2];
			} else {
				s = lookaheadMatch[3].unDash();
				v = lookaheadMatch[4];
			}
			if(s=="bgcolor")
				s = "backgroundColor";
			if(s=="float")
				s = "cssFloat";
			styles.push({style: s, value: v});
			w.nextMatch = lookaheadMatch.index + lookaheadMatch[0].length;
			config.textPrimitives.cssLookaheadRegExp.lastIndex = w.nextMatch;
			lookaheadMatch = config.textPrimitives.cssLookaheadRegExp.exec(w.source);
		}
		return styles;
	},

	applyCssHelper: function(e,styles)
	{
		var t;
		for(t=0; t< styles.length; t++) {
			try {
				e.style[styles[t].style] = styles[t].value;
			} catch (ex) {
			}
		}
	},

	enclosedTextHelper: function(w)
	{
		this.lookaheadRegExp.lastIndex = w.matchStart;
		var lookaheadMatch = this.lookaheadRegExp.exec(w.source);
		if(lookaheadMatch && lookaheadMatch.index == w.matchStart) {
			var text = lookaheadMatch[1];
			if(config.browser.isIE && (config.browser.ieVersion[1] < 10))
				text = text.replace(/\n/g,"\r");
			createTiddlyElement(w.output,this.element,null,null,text);
			w.nextMatch = lookaheadMatch.index + lookaheadMatch[0].length;
		}
	},

	isExternalLink: function(link)
	{
		if(store.tiddlerExists(link) || store.isShadowTiddler(link)) {
			return false;
		}
		var urlRegExp = new RegExp(config.textPrimitives.urlPattern,"mg");
		if(urlRegExp.exec(link)) {
			return true;
		}
		if(link.indexOf(".")!=-1 || link.indexOf("\\")!=-1 || link.indexOf("/")!=-1 || link.indexOf("#")!=-1) {
			return true;
		}
		return false;
	}

};

//--
//-- Standard formatters
//--

config.formatters = [
{
	name: "table",
	match: "^\\|(?:[^\\n]*)\\|(?:[fhck]?)$",
	lookaheadRegExp: /^\|([^\n]*)\|([fhck]?)$/mg,
	rowTermRegExp: /(\|(?:[fhck]?)$\n?)/mg,
	cellRegExp: /(?:\|([^\n\|]*)\|)|(\|[fhck]?$\n?)/mg,
	cellTermRegExp: /((?:\x20*)\|)/mg,
	rowTypes: {"c":"caption", "h":"thead", "":"tbody", "f":"tfoot"},
	handler: function(w)
	{
		var table = createTiddlyElement(w.output,"table",null,"twtable");
		var prevColumns = [];
		var currRowType = null;
		var rowContainer;
		var rowCount = 0;
		var onmouseover = function() {jQuery(this).addClass("hoverRow");};
		var onmouseout = function() {jQuery(this).removeClass("hoverRow");};
		w.nextMatch = w.matchStart;
		this.lookaheadRegExp.lastIndex = w.nextMatch;
		var lookaheadMatch = this.lookaheadRegExp.exec(w.source);
		while(lookaheadMatch && lookaheadMatch.index == w.nextMatch) {
			var nextRowType = lookaheadMatch[2];
			if(nextRowType == "k") {
				table.className = lookaheadMatch[1];
				w.nextMatch += lookaheadMatch[0].length+1;
			} else {
				if(nextRowType != currRowType) {
					rowContainer = createTiddlyElement(table,this.rowTypes[nextRowType]);
					currRowType = nextRowType;
				}
				if(currRowType == "c") {
					// Caption
					w.nextMatch++;
					if(rowContainer != table.firstChild)
						table.insertBefore(rowContainer,table.firstChild);
					rowContainer.setAttribute("align",rowCount == 0?"top":"bottom");
					w.subWikifyTerm(rowContainer,this.rowTermRegExp);
				} else {
					var theRow = createTiddlyElement(rowContainer,"tr",null,rowCount%2?"oddRow":"evenRow");
					theRow.onmouseover = onmouseover;
					theRow.onmouseout = onmouseout;
					this.rowHandler(w,theRow,prevColumns);
					rowCount++;
				}
			}
			this.lookaheadRegExp.lastIndex = w.nextMatch;
			lookaheadMatch = this.lookaheadRegExp.exec(w.source);
		}
	},
	rowHandler: function(w,e,prevColumns)
	{
		var col = 0;
		var colSpanCount = 1;
		var prevCell = null;
		this.cellRegExp.lastIndex = w.nextMatch;
		var cellMatch = this.cellRegExp.exec(w.source);
		while(cellMatch && cellMatch.index == w.nextMatch) {
			if(cellMatch[1] == "~") {
				// Rowspan
				var last = prevColumns[col];
				if(last) {
					last.rowSpanCount++;
					last.element.setAttribute("rowspan",last.rowSpanCount);
					last.element.setAttribute("rowSpan",last.rowSpanCount); // Needed for IE
					last.element.valign = "center";
					if(colSpanCount > 1) {
						last.element.setAttribute("colspan",colSpanCount);
						last.element.setAttribute("colSpan",colSpanCount); // Needed for IE
						colSpanCount = 1;
					}
				}
				w.nextMatch = this.cellRegExp.lastIndex-1;
			} else if(cellMatch[1] == ">") {
				// Colspan
				colSpanCount++;
				w.nextMatch = this.cellRegExp.lastIndex-1;
			} else if(cellMatch[2]) {
				// End of row
				if(prevCell && colSpanCount > 1) {
					prevCell.setAttribute("colspan",colSpanCount);
					prevCell.setAttribute("colSpan",colSpanCount); // Needed for IE
				}
				w.nextMatch = this.cellRegExp.lastIndex;
				break;
			} else {
				// Cell
				w.nextMatch++;
				var styles = config.formatterHelpers.inlineCssHelper(w);
				var spaceLeft = false;
				var chr = w.source.substr(w.nextMatch,1);
				while(chr == " ") {
					spaceLeft = true;
					w.nextMatch++;
					chr = w.source.substr(w.nextMatch,1);
				}
				var cell;
				if(chr == "!") {
					cell = createTiddlyElement(e,"th");
					w.nextMatch++;
				} else {
					cell = createTiddlyElement(e,"td");
				}
				prevCell = cell;
				prevColumns[col] = {rowSpanCount:1,element:cell};
				if(colSpanCount > 1) {
					cell.setAttribute("colspan",colSpanCount);
					cell.setAttribute("colSpan",colSpanCount); // Needed for IE
					colSpanCount = 1;
				}
				config.formatterHelpers.applyCssHelper(cell,styles);
				w.subWikifyTerm(cell,this.cellTermRegExp);
				if(w.matchText.substr(w.matchText.length-2,1) == " ") // spaceRight
					cell.align = spaceLeft ? "center" : "left";
				else if(spaceLeft)
					cell.align = "right";
				w.nextMatch--;
			}
			col++;
			this.cellRegExp.lastIndex = w.nextMatch;
			cellMatch = this.cellRegExp.exec(w.source);
		}
	}
},

{
	name: "heading",
	match: "^!{1,6}",
	termRegExp: /(\n)/mg,
	handler: function(w)
	{
		w.subWikifyTerm(createTiddlyElement(w.output,"h" + w.matchLength),this.termRegExp);
	}
},

{
	name: "list",
	match: "^(?:[\\*#;:]+)",
	lookaheadRegExp: /^(?:(?:(\*)|(#)|(;)|(:))+)/mg,
	termRegExp: /(\n)/mg,
	handler: function(w)
	{
		var stack = [w.output];
		var currLevel = 0, currType = null;
		var listLevel, listType, itemType, baseType;
		w.nextMatch = w.matchStart;
		this.lookaheadRegExp.lastIndex = w.nextMatch;
		var lookaheadMatch = this.lookaheadRegExp.exec(w.source);
		while(lookaheadMatch && lookaheadMatch.index == w.nextMatch) {
			if(lookaheadMatch[1]) {
				listType = "ul";
				itemType = "li";
			} else if(lookaheadMatch[2]) {
				listType = "ol";
				itemType = "li";
			} else if(lookaheadMatch[3]) {
				listType = "dl";
				itemType = "dt";
			} else if(lookaheadMatch[4]) {
				listType = "dl";
				itemType = "dd";
			}
			if(!baseType)
				baseType = listType;
			listLevel = lookaheadMatch[0].length;
			w.nextMatch += lookaheadMatch[0].length;
			var t;
			if(listLevel > currLevel) {
				for(t=currLevel; t<listLevel; t++) {
					var target = (currLevel == 0) ? stack[stack.length-1] : stack[stack.length-1].lastChild;
					stack.push(createTiddlyElement(target,listType));
				}
			} else if(listType!=baseType && listLevel==1) {
				w.nextMatch -= lookaheadMatch[0].length;
				return;
			} else if(listLevel < currLevel) {
				for(t=currLevel; t>listLevel; t--)
					stack.pop();
			} else if(listLevel == currLevel && listType != currType) {
				stack.pop();
				stack.push(createTiddlyElement(stack[stack.length-1].lastChild,listType));
			}
			currLevel = listLevel;
			currType = listType;
			var e = createTiddlyElement(stack[stack.length-1],itemType);
			w.subWikifyTerm(e,this.termRegExp);
			this.lookaheadRegExp.lastIndex = w.nextMatch;
			lookaheadMatch = this.lookaheadRegExp.exec(w.source);
		}
	}
},

{
	name: "quoteByBlock",
	match: "^<<<\\n",
	termRegExp: /(^<<<(\n|$))/mg,
	element: "blockquote",
	handler: config.formatterHelpers.createElementAndWikify
},

{
	name: "quoteByLine",
	match: "^>+",
	lookaheadRegExp: /^>+/mg,
	termRegExp: /(\n)/mg,
	element: "blockquote",
	handler: function(w)
	{
		var stack = [w.output];
		var currLevel = 0;
		var newLevel = w.matchLength;
		var t,matched;
		do {
			if(newLevel > currLevel) {
				for(t=currLevel; t<newLevel; t++)
					stack.push(createTiddlyElement(stack[stack.length-1],this.element));
			} else if(newLevel < currLevel) {
				for(t=currLevel; t>newLevel; t--)
					stack.pop();
			}
			currLevel = newLevel;
			w.subWikifyTerm(stack[stack.length-1],this.termRegExp);
			createTiddlyElement(stack[stack.length-1],"br");
			this.lookaheadRegExp.lastIndex = w.nextMatch;
			var lookaheadMatch = this.lookaheadRegExp.exec(w.source);
			matched = lookaheadMatch && lookaheadMatch.index == w.nextMatch;
			if(matched) {
				newLevel = lookaheadMatch[0].length;
				w.nextMatch += lookaheadMatch[0].length;
			}
		} while(matched);
	}
},

{
	name: "rule",
	match: "^----+$\\n?|<hr ?/?>\\n?",
	handler: function(w)
	{
		createTiddlyElement(w.output,"hr");
	}
},

{
	name: "monospacedByLine",
	match: "^(?:/\\*\\{\\{\\{\\*/|\\{\\{\\{|//\\{\\{\\{|<!--\\{\\{\\{-->)\\n",
	element: "pre",
	handler: function(w)
	{
		switch(w.matchText) {
		case "/*{{{*/\n": // CSS
			this.lookaheadRegExp = /\/\*\{\{\{\*\/\n*((?:^[^\n]*\n)+?)(\n*^\f*\/\*\}\}\}\*\/$\n?)/mg;
			break;
		case "{{{\n": // monospaced block
			this.lookaheadRegExp = /^\{\{\{\n((?:^[^\n]*\n)+?)(^\f*\}\}\}$\n?)/mg;
			break;
		case "//{{{\n": // plugin
			this.lookaheadRegExp = /^\/\/\{\{\{\n\n*((?:^[^\n]*\n)+?)(\n*^\f*\/\/\}\}\}$\n?)/mg;
			break;
		case "<!--{{{-->\n": //template
			this.lookaheadRegExp = /<!--\{\{\{-->\n*((?:^[^\n]*\n)+?)(\n*^\f*<!--\}\}\}-->$\n?)/mg;
			break;
		default:
			break;
		}
		config.formatterHelpers.enclosedTextHelper.call(this,w);
	}
},

{
	name: "wikifyComment",
	match: "^(?:/\\*\\*\\*|<!---)\\n",
	handler: function(w)
	{
		var termRegExp = (w.matchText == "/***\n") ? (/(^\*\*\*\/\n)/mg) : (/(^--->\n)/mg);
		w.subWikifyTerm(w.output,termRegExp);
	}
},

{
	name: "macro",
	match: "<<",
	lookaheadRegExp: /<<([^>\s]+)(?:\s*)((?:[^>]|(?:>(?!>)))*)>>/mg,
	handler: function(w)
	{
		this.lookaheadRegExp.lastIndex = w.matchStart;
		var lookaheadMatch = this.lookaheadRegExp.exec(w.source);
		if(lookaheadMatch && lookaheadMatch.index == w.matchStart && lookaheadMatch[1]) {
			w.nextMatch = this.lookaheadRegExp.lastIndex;
			invokeMacro(w.output,lookaheadMatch[1],lookaheadMatch[2],w,w.tiddler);
		}
	}
},

{
	name: "prettyLink",
	match: "\\[\\[",
	lookaheadRegExp: /\[\[(.*?)(?:\|(~)?(.*?))?\]\]/mg,
	handler: function(w)
	{
		this.lookaheadRegExp.lastIndex = w.matchStart;
		var lookaheadMatch = this.lookaheadRegExp.exec(w.source);
		if(lookaheadMatch && lookaheadMatch.index == w.matchStart) {
			var e;
			var text = lookaheadMatch[1];
			if(lookaheadMatch[3]) {
				// Pretty bracketted link
				var link = lookaheadMatch[3];
				e = (!lookaheadMatch[2] && config.formatterHelpers.isExternalLink(link)) ?
						createExternalLink(w.output,link) : createTiddlyLink(w.output,link,false,null,w.isStatic,w.tiddler);
			} else {
				// Simple bracketted link
				e = createTiddlyLink(w.output,text,false,null,w.isStatic,w.tiddler);
			}
			createTiddlyText(e,text);
			w.nextMatch = this.lookaheadRegExp.lastIndex;
		}
	}
},

{
	name: "wikiLink",
	match: config.textPrimitives.unWikiLink+"?"+config.textPrimitives.wikiLink,
	handler: function(w)
	{
		if(w.matchText.substr(0,1) == config.textPrimitives.unWikiLink) {
			w.outputText(w.output,w.matchStart+1,w.nextMatch);
			return;
		}
		if(w.matchStart > 0) {
			var preRegExp = new RegExp(config.textPrimitives.anyLetterStrict,"mg");
			preRegExp.lastIndex = w.matchStart-1;
			var preMatch = preRegExp.exec(w.source);
			if(preMatch.index == w.matchStart-1) {
				w.outputText(w.output,w.matchStart,w.nextMatch);
				return;
			}
		}
		if(w.autoLinkWikiWords || store.isShadowTiddler(w.matchText)) {
			var link = createTiddlyLink(w.output,w.matchText,false,null,w.isStatic,w.tiddler);
			w.outputText(link,w.matchStart,w.nextMatch);
		} else {
			w.outputText(w.output,w.matchStart,w.nextMatch);
		}
	}
},

{
	name: "urlLink",
	match: config.textPrimitives.urlPattern,
	handler: function(w)
	{
		w.outputText(createExternalLink(w.output,w.matchText),w.matchStart,w.nextMatch);
	}
},

{
	name: "image",
	match: "\\[[<>]?[Ii][Mm][Gg]\\[",
	lookaheadRegExp: /\[([<]?)(>?)[Ii][Mm][Gg]\[(?:([^\|\]]+)\|)?([^\[\]\|]+)\](?:\[([^\]]*)\])?\]/mg,
	handler: function(w)
	{
		this.lookaheadRegExp.lastIndex = w.matchStart;
		var lookaheadMatch = this.lookaheadRegExp.exec(w.source);
		if(lookaheadMatch && lookaheadMatch.index == w.matchStart) {
			var e = w.output;
			if(lookaheadMatch[5]) {
				var link = lookaheadMatch[5];
				e = config.formatterHelpers.isExternalLink(link) ? createExternalLink(w.output,link) : createTiddlyLink(w.output,link,false,null,w.isStatic,w.tiddler);
				jQuery(e).addClass("imageLink");
			}
			var img = createTiddlyElement(e,"img");
			if(lookaheadMatch[1])
				img.align = "left";
			else if(lookaheadMatch[2])
				img.align = "right";
			if(lookaheadMatch[3]) {
				img.title = lookaheadMatch[3];
				img.setAttribute("alt",lookaheadMatch[3]);
			}
			img.src = lookaheadMatch[4];
			w.nextMatch = this.lookaheadRegExp.lastIndex;
		}
	}
},

{
	name: "html",
	match: "<[Hh][Tt][Mm][Ll]>",
	lookaheadRegExp: /<[Hh][Tt][Mm][Ll]>((?:.|\n)*?)<\/[Hh][Tt][Mm][Ll]>/mg,
	handler: function(w)
	{
		this.lookaheadRegExp.lastIndex = w.matchStart;
		var lookaheadMatch = this.lookaheadRegExp.exec(w.source);
		if(lookaheadMatch && lookaheadMatch.index == w.matchStart) {
			createTiddlyElement(w.output,"span").innerHTML = lookaheadMatch[1];
			w.nextMatch = this.lookaheadRegExp.lastIndex;
		}
	}
},

{
	name: "commentByBlock",
	match: "/%",
	lookaheadRegExp: /\/%((?:.|\n)*?)%\//mg,
	handler: function(w)
	{
		this.lookaheadRegExp.lastIndex = w.matchStart;
		var lookaheadMatch = this.lookaheadRegExp.exec(w.source);
		if(lookaheadMatch && lookaheadMatch.index == w.matchStart)
			w.nextMatch = this.lookaheadRegExp.lastIndex;
	}
},

{
	name: "characterFormat",
	match: "''|//|__|\\^\\^|~~|--(?!\\s|$)|\\{\\{\\{",
	handler: function(w)
	{
		switch(w.matchText) {
		case "''":
			w.subWikifyTerm(w.output.appendChild(document.createElement("strong")),/('')/mg);
			break;
		case "//":
			w.subWikifyTerm(createTiddlyElement(w.output,"em"),/(\/\/)/mg);
			break;
		case "__":
			w.subWikifyTerm(createTiddlyElement(w.output,"u"),/(__)/mg);
			break;
		case "^^":
			w.subWikifyTerm(createTiddlyElement(w.output,"sup"),/(\^\^)/mg);
			break;
		case "~~":
			w.subWikifyTerm(createTiddlyElement(w.output,"sub"),/(~~)/mg);
			break;
		case "--":
			w.subWikifyTerm(createTiddlyElement(w.output,"strike"),/(--)/mg);
			break;
		case "{{{":
			var lookaheadRegExp = /\{\{\{((?:.|\n)*?)\}\}\}/mg;
			lookaheadRegExp.lastIndex = w.matchStart;
			var lookaheadMatch = lookaheadRegExp.exec(w.source);
			if(lookaheadMatch && lookaheadMatch.index == w.matchStart) {
				createTiddlyElement(w.output,"code",null,null,lookaheadMatch[1]);
				w.nextMatch = lookaheadRegExp.lastIndex;
			}
			break;
		}
	}
},

{
	name: "customFormat",
	match: "@@|\\{\\{",
	handler: function(w)
	{
		switch(w.matchText) {
		case "@@":
			var e = createTiddlyElement(w.output,"span");
			var styles = config.formatterHelpers.inlineCssHelper(w);
			if(styles.length == 0)
				e.className = "marked";
			else
				config.formatterHelpers.applyCssHelper(e,styles);
			w.subWikifyTerm(e,/(@@)/mg);
			break;
		case "{{":
			var lookaheadRegExp = /\{\{[\s]*([\w]+[\s\w]*)[\s]*\{(\n?)/mg;
			lookaheadRegExp.lastIndex = w.matchStart;
			var lookaheadMatch = lookaheadRegExp.exec(w.source);
			if(lookaheadMatch) {
				w.nextMatch = lookaheadRegExp.lastIndex;
				e = createTiddlyElement(w.output,lookaheadMatch[2] == "\n" ? "div" : "span",null,lookaheadMatch[1]);
				w.subWikifyTerm(e,/(\}\}\})/mg);
			}
			break;
		}
	}
},

{
	name: "mdash",
	match: "--",
	handler: function(w)
	{
		createTiddlyElement(w.output,"span").innerHTML = "&mdash;";
	}
},

{
	name: "lineBreak",
	match: "\\n|<br ?/?>",
	handler: function(w)
	{
		createTiddlyElement(w.output,"br");
	}
},

{
	name: "rawText",
	match: "\"{3}|<nowiki>",
	lookaheadRegExp: /(?:\"{3}|<nowiki>)((?:.|\n)*?)(?:\"{3}|<\/nowiki>)/mg,
	handler: function(w)
	{
		this.lookaheadRegExp.lastIndex = w.matchStart;
		var lookaheadMatch = this.lookaheadRegExp.exec(w.source);
		if(lookaheadMatch && lookaheadMatch.index == w.matchStart) {
			createTiddlyElement(w.output,"span",null,null,lookaheadMatch[1]);
			w.nextMatch = this.lookaheadRegExp.lastIndex;
		}
	}
},

{
	name: "htmlEntitiesEncoding",
	match: "(?:(?:&#?[a-zA-Z0-9]{2,8};|.)(?:&#?(?:x0*(?:3[0-6][0-9a-fA-F]|1D[c-fC-F][0-9a-fA-F]|20[d-fD-F][0-9a-fA-F]|FE2[0-9a-fA-F])|0*(?:76[89]|7[7-9][0-9]|8[0-7][0-9]|761[6-9]|76[2-7][0-9]|84[0-3][0-9]|844[0-7]|6505[6-9]|6506[0-9]|6507[0-1]));)+|&#?[a-zA-Z0-9]{2,8};)",
	handler: function(w)
	{
		createTiddlyElement(w.output,"span").innerHTML = w.matchText;
	}
}

];

//--
//-- Wikifier
//--

function getParser(tiddler,format)
{
	if(tiddler) {
		if(!format)
			format = tiddler.fields["wikiformat"];
		var i;
		if(format) {
			for(i in config.parsers) {
				if(format == config.parsers[i].format)
					return config.parsers[i];
			}
		} else {
			for(i in config.parsers) {
				if(tiddler.isTagged(config.parsers[i].formatTag))
					return config.parsers[i];
			}
		}
	}
	return formatter;
}

function Wikifier(source,formatter,highlightRegExp,tiddler)
{
	this.source = source;
	this.output = null;
	this.formatter = formatter;
	this.nextMatch = 0;
	this.autoLinkWikiWords = tiddler && tiddler.autoLinkWikiWords() == false ? false : true;
	this.highlightRegExp = highlightRegExp;
	this.highlightMatch = null;
	this.isStatic = false;
	if(highlightRegExp) {
		highlightRegExp.lastIndex = 0;
		this.highlightMatch = highlightRegExp.exec(source);
	}
	this.tiddler = tiddler;
}

Wikifier.prototype.wikifyPlain = function()
{
	var e = createTiddlyElement(document.body,"div");
	e.style.display = "none";
	this.subWikify(e);
	var text = jQuery(e).text();
	jQuery(e).remove();
	return text;
};

Wikifier.prototype.subWikify = function(output,terminator)
{
	try {
		if(terminator)
			this.subWikifyTerm(output,new RegExp("(" + terminator + ")","mg"));
		else
			this.subWikifyUnterm(output);
	} catch(ex) {
		showException(ex);
	}
};

Wikifier.prototype.subWikifyUnterm = function(output)
{
	var oldOutput = this.output;
	this.output = output;
	this.formatter.formatterRegExp.lastIndex = this.nextMatch;
	var formatterMatch = this.formatter.formatterRegExp.exec(this.source);
	while(formatterMatch) {
		// Output any text before the match
		if(formatterMatch.index > this.nextMatch)
			this.outputText(this.output,this.nextMatch,formatterMatch.index);
		// Set the match parameters for the handler
		this.matchStart = formatterMatch.index;
		this.matchLength = formatterMatch[0].length;
		this.matchText = formatterMatch[0];
		this.nextMatch = this.formatter.formatterRegExp.lastIndex;
		var t;
		for(t=1; t<formatterMatch.length; t++) {
			if(formatterMatch[t]) {
				this.formatter.formatters[t-1].handler(this);
				this.formatter.formatterRegExp.lastIndex = this.nextMatch;
				break;
			}
		}
		formatterMatch = this.formatter.formatterRegExp.exec(this.source);
	}
	if(this.nextMatch < this.source.length) {
		this.outputText(this.output,this.nextMatch,this.source.length);
		this.nextMatch = this.source.length;
	}
	this.output = oldOutput;
};

Wikifier.prototype.subWikifyTerm = function(output,terminatorRegExp)
{
	var oldOutput = this.output;
	this.output = output;
	terminatorRegExp.lastIndex = this.nextMatch;
	var terminatorMatch = terminatorRegExp.exec(this.source);
	this.formatter.formatterRegExp.lastIndex = this.nextMatch;
	var formatterMatch = this.formatter.formatterRegExp.exec(terminatorMatch ? this.source.substr(0,terminatorMatch.index) : this.source);
	while(terminatorMatch || formatterMatch) {
		if(terminatorMatch && (!formatterMatch || terminatorMatch.index <= formatterMatch.index)) {
			if(terminatorMatch.index > this.nextMatch)
				this.outputText(this.output,this.nextMatch,terminatorMatch.index);
			this.matchText = terminatorMatch[1];
			this.matchLength = terminatorMatch[1].length;
			this.matchStart = terminatorMatch.index;
			this.nextMatch = this.matchStart + this.matchLength;
			this.output = oldOutput;
			return;
		}
		if(formatterMatch.index > this.nextMatch)
			this.outputText(this.output,this.nextMatch,formatterMatch.index);
		this.matchStart = formatterMatch.index;
		this.matchLength = formatterMatch[0].length;
		this.matchText = formatterMatch[0];
		this.nextMatch = this.formatter.formatterRegExp.lastIndex;
		var t;
		for(t=1; t<formatterMatch.length; t++) {
			if(formatterMatch[t]) {
				this.formatter.formatters[t-1].handler(this);
				this.formatter.formatterRegExp.lastIndex = this.nextMatch;
				break;
			}
		}
		terminatorRegExp.lastIndex = this.nextMatch;
		terminatorMatch = terminatorRegExp.exec(this.source);
		formatterMatch = this.formatter.formatterRegExp.exec(terminatorMatch ? this.source.substr(0,terminatorMatch.index) : this.source);
	}
	if(this.nextMatch < this.source.length) {
		this.outputText(this.output,this.nextMatch,this.source.length);
		this.nextMatch = this.source.length;
	}
	this.output = oldOutput;
};

Wikifier.prototype.outputText = function(place,startPos,endPos)
{
	while(this.highlightMatch && (this.highlightRegExp.lastIndex > startPos) && (this.highlightMatch.index < endPos) && (startPos < endPos)) {
		if(this.highlightMatch.index > startPos) {
			createTiddlyText(place,this.source.substring(startPos,this.highlightMatch.index));
			startPos = this.highlightMatch.index;
		}
		var highlightEnd = Math.min(this.highlightRegExp.lastIndex,endPos);
		createTiddlyElement(place,"span",null,"highlight",this.source.substring(startPos,highlightEnd));
		startPos = highlightEnd;
		if(startPos >= this.highlightRegExp.lastIndex)
			this.highlightMatch = this.highlightRegExp.exec(this.source);
	}
	if(startPos < endPos) {
		createTiddlyText(place,this.source.substring(startPos,endPos));
	}
};

function wikify(source,output,highlightRegExp,tiddler)
{
	if(source) {
		var wikifier = new Wikifier(source,getParser(tiddler),highlightRegExp,tiddler);
		var t0 = new Date();
		wikifier.subWikify(output);
		if(tiddler && config.options.chkDisplayInstrumentation)
			displayMessage("wikify:" +tiddler.title+ " in " + (new Date()-t0) + " ms");
	}
}

function wikifyStatic(source,highlightRegExp,tiddler,format)
{
	var e = createTiddlyElement(document.body,"pre");
	e.style.display = "none";
	var html = "";
	if(source && source != "") {
		if(!tiddler)
			tiddler = new Tiddler("temp");
		var wikifier = new Wikifier(source,getParser(tiddler,format),highlightRegExp,tiddler);
		wikifier.isStatic = true;
		wikifier.subWikify(e);
		html = e.innerHTML;
		jQuery(e).remove();
	}
	return html;
}

function wikifyPlainText(text,limit,tiddler)
{
	if(limit > 0)
		text = text.substr(0,limit);
	var wikifier = new Wikifier(text,formatter,null,tiddler);
	return wikifier.wikifyPlain();
}

function highlightify(source,output,highlightRegExp,tiddler)
{
	if(source) {
		var wikifier = new Wikifier(source,formatter,highlightRegExp,tiddler);
		wikifier.outputText(output,0,source.length);
	}
}

//--
//-- Macro definitions
//--

function invokeMacro(place,macro,params,wikifier,tiddler)
{
	try {
		var m = config.macros[macro];
		if(m && m.handler) {
			var tiddlerElem = story.findContainingTiddler(place);
			window.tiddler = tiddlerElem ? store.getTiddler(tiddlerElem.getAttribute("tiddler")) : null;
			window.place = place;
			var allowEval = true;
			if(config.evaluateMacroParameters=="system") {
				if(!tiddler || tiddler.tags.indexOf("systemAllowEval") == -1) {
					allowEval = false;
				}
			}
			m.handler(place,macro,m.noPreParse?null:params.readMacroParams(!allowEval),wikifier,params,tiddler);
		} else {
			createTiddlyError(place,config.messages.macroError.format([macro]),config.messages.macroErrorDetails.format([macro,config.messages.missingMacro]));
		}
	} catch(ex) {
		createTiddlyError(place,config.messages.macroError.format([macro]),config.messages.macroErrorDetails.format([macro,ex.toString()]));
	}
}

config.macros.version.handler = function(place)
{
	jQuery("<span/>").text(formatVersion()).appendTo(place);
};

config.macros.today.handler = function(place,macroName,params)
{
	var now = new Date();
	var text = params[0] ? now.formatString(params[0].trim()) : now.toLocaleString();
	jQuery("<span/>").text(text).appendTo(place);
};

config.macros.list.template = "<<view title link>>";
config.macros.list.handler = function(place,macroName,params,wikifier,paramString)
{
	var list = document.createElement("ul");
	jQuery(list).attr({ refresh: "macro", macroName: macroName }).data("params", paramString);
	place.appendChild(list);
	this.refresh(list);
};

config.macros.list.refresh = function(list) {
	var paramString = jQuery(list).data("params");
	var params = paramString.readMacroParams();
	var args = paramString.parseParams("anon", null, null)[0];
	var type = args.anon ? args.anon[0] : "all";
	jQuery(list).empty().addClass("list list-" + type);
	var template = args.template ? store.getTiddlerText(args.template[0]) : false;
	if(!template) {
		template = config.macros.list.template;
	}
	if(this[type].prompt)
		createTiddlyElement(list,"li",null,"listTitle",this[type].prompt);
	var results;
	if(this[type].handler)
		results = this[type].handler(params);
	var t;
	for(t = 0; t < results.length; t++) {
		var li = document.createElement("li");
		list.appendChild(li);
		var tiddler = results[t];
		if(typeof(tiddler) == 'string') { // deal with missing etc..
				tiddler = store.getTiddler(tiddler) || new Tiddler(tiddler);
		}
		wikify(template, li, null, tiddler);
	}
	if(results.length === 0 && args.emptyMessage) {
		jQuery(list).addClass("emptyList");
		jQuery("<li />").text(args.emptyMessage[0]).appendTo(list);
	}
};

config.macros.list.all.handler = function(params)
{
	return store.reverseLookup("tags","excludeLists",false,"title");
};

config.macros.list.missing.handler = function(params)
{
	return store.getMissingLinks();
};

config.macros.list.orphans.handler = function(params)
{
	return store.getOrphans();
};

config.macros.list.shadowed.handler = function(params)
{
	return store.getShadowed();
};

config.macros.list.touched.handler = function(params)
{
	return store.getTouched();
};

config.macros.list.filter.handler = function(params)
{
	var filter = params[1];
	var results = [];
	if(filter) {
		var tiddlers = store.filterTiddlers(filter);
		var t;
		for(t=0; t<tiddlers.length; t++)
			results.push(tiddlers[t].title);
	}
	return results;
};

config.macros.allTags.handler = function(place,macroName,params)
{
	var tags = store.getTags(params[0]);
	var ul = createTiddlyElement(place,"ul");
	if(tags.length == 0)
		createTiddlyElement(ul,"li",null,"listTitle",this.noTags);
	var t;
	for(t=0; t<tags.length; t++) {
		var title = tags[t][0];
		var info = getTiddlyLinkInfo(title);
		var li = createTiddlyElement(ul,"li");
		var btn = createTiddlyButton(li,title + " (" + tags[t][1] + ")",this.tooltip.format([title]),onClickTag,info.classes);
		btn.setAttribute("tag",title);
		btn.setAttribute("refresh","link");
		btn.setAttribute("tiddlyLink",title);
		if(params[1]) {
			btn.setAttribute("sortby",params[1]);
		}
	}
};

var macro = config.macros.timeline;
merge(macro, {
	handler: function(place,macroName,params, wikifier, paramString, tiddler) {
		var container = jQuery("<div />").attr("params", paramString).
			attr("macroName", macroName).appendTo(place)[0];
		macro.refresh(container);
	},
	refresh: function(container) {
		jQuery(container).attr("refresh", "macro").empty();
		var paramString = jQuery(container).attr("params");
		var args = paramString.parseParams("anon", null, null)[0];
		var params = args.anon || [];

		var field = params[0] || "modified";
		var prefix = field.charAt(0);
		var no_prefix_field = prefix === "-" || prefix === "+" ? field.substr(1, field.length) : field;
		var dateFormat = params[2] || this.dateFormat;
		var groupTemplate = macro.groupTemplate.format(no_prefix_field, dateFormat);
		groupTemplate = args.groupTemplate ? store.getTiddlerText(args.groupTemplate[0]) || groupTemplate :
			groupTemplate;

		var itemTemplate = macro.itemTemplate;
		itemTemplate = args.template ? store.getTiddlerText(args.template[0]) || itemTemplate :
			itemTemplate;

		var tiddlers = args.filter ? store.sortTiddlers(store.filterTiddlers(args.filter[0]), field) :
			store.reverseLookup("tags", "excludeLists", false, field);
		var lastGroup = "", ul;
		var last = params[1] ? tiddlers.length-Math.min(tiddlers.length,parseInt(params[1],10)) : 0;
		var t;
		for(t=tiddlers.length-1; t>=last; t--) {
			var tiddler = tiddlers[t];
			var theGroup = wikifyPlainText(groupTemplate,0,tiddler);
			if(typeof(ul) == "undefined" || theGroup != lastGroup) {
				ul = document.createElement("ul");
				jQuery(ul).addClass("timeline");
				container.appendChild(ul);
				createTiddlyElement(ul,"li",null,"listTitle",theGroup);
				lastGroup = theGroup;
			}
			var item = createTiddlyElement(ul,"li",null,"listLink");
			wikify(itemTemplate,item,null,tiddler);
		}
	},
	groupTemplate: "<<view %0 date '%1'>>", 
	itemTemplate: "<<view title link>>"
});

config.macros.tiddler.handler = function(place,macroName,params,wikifier,paramString,tiddler)
{
	var allowEval = true;
	var stack = config.macros.tiddler.tiddlerStack;
	if(stack.length > 0 && config.evaluateMacroParameters == "system") {
		// included tiddler and "system" evaluation required, so check tiddler tagged appropriately
		var title = stack[stack.length-1];
		var pos = title.indexOf(config.textPrimitives.sectionSeparator);
		if(pos != -1) {
			title = title.substr(0,pos); // get the base tiddler title
		}
		var t = store.getTiddler(title);
		if(!t || t.tags.indexOf("systemAllowEval") == -1) {
			allowEval = false;
		}
	}
	params = paramString.parseParams("name",null,allowEval,false,true);
	var names = params[0]["name"];
	var tiddlerName = names[0];
	var className = names[1] || null;
	var args = params[0]["with"];
	var wrapper = createTiddlyElement(place,"span",null,className,null,{
		refresh: "content", tiddler: tiddlerName
	});
	if(args!==undefined)
		wrapper.setAttribute("args","[["+args.join("]] [[")+"]]");
	this.transclude(wrapper,tiddlerName,args);
};

config.macros.tiddler.transclude = function(wrapper,tiddlerName,args)
{
	var text = store.getTiddlerText(tiddlerName);
	if(!text)
		return;
	var stack = config.macros.tiddler.tiddlerStack;
	if(stack.indexOf(tiddlerName) !== -1)
		return;
	stack.push(tiddlerName);
	try {
		if(typeof args == "string")
			args = args.readBracketedList();
		var n = args ? Math.min(args.length,9) : 0;
		var i;
		for(i=0; i<n; i++) {
			var placeholderRE = new RegExp("\\$" + (i + 1),"mg");
			text = text.replace(placeholderRE,args[i]);
		}
		config.macros.tiddler.renderText(wrapper,text,tiddlerName);
	} finally {
		stack.pop();
	}
};

config.macros.tiddler.renderText = function(place,text,tiddlerName)
{
	wikify(text,place,null,store.getTiddler(tiddlerName));
};

config.macros.tiddler.tiddlerStack = [];

config.macros.tag.handler = function(place,macroName,params)
{
	var btn = createTagButton(place,params[0],null,params[1],params[2]);
	if(params[3]) {
		btn.setAttribute('sortby',params[3]);
	}
};

config.macros.tags.handler = function(place,macroName,params,wikifier,paramString,tiddler)
{
	params = paramString.parseParams("anon",null,true,false,false);
	var ul = createTiddlyElement(place,"ul");
	var title = getParam(params,"anon","");
	if(title && store.tiddlerExists(title))
		tiddler = store.getTiddler(title);
	var sep = getParam(params,"sep"," ");
	var lingo = config.views.wikified.tag;
	var label = null;
	var t;
	for(t=0; t<tiddler.tags.length; t++) {
		var tag = store.getTiddler(tiddler.tags[t]);
		if(!tag || !tag.tags.contains("excludeLists")) {
			if(!label)
				label = createTiddlyElement(ul,"li",null,"listTitle",lingo.labelTags.format([tiddler.title]));
			createTagButton(createTiddlyElement(ul,"li"),tiddler.tags[t],tiddler.title);
			if(t<tiddler.tags.length-1)
				createTiddlyText(ul,sep);
		}
	}
	if(!label)
		createTiddlyElement(ul,"li",null,"listTitle",lingo.labelNoTags.format([tiddler.title]));
};

config.macros.tagging.handler = function(place,macroName,params,wikifier,paramString,tiddler)
{
	params = paramString.parseParams("anon",null,true,false,false);
	var ul = createTiddlyElement(place,"ul");
	var title = getParam(params,"anon","");
	if(title == "" && tiddler instanceof Tiddler)
		title = tiddler.title;
	var sep = getParam(params,"sep"," ");
	ul.setAttribute("title",this.tooltip.format([title]));
	var sortby = getParam(params,"sortBy",false);
	var tagged = store.getTaggedTiddlers(title,sortby);
	var prompt = tagged.length == 0 ? this.labelNotTag : this.label;
	createTiddlyElement(ul,"li",null,"listTitle",prompt.format([title,tagged.length]));
	var t;
	for(t=0; t<tagged.length; t++) {
		createTiddlyLink(createTiddlyElement(ul,"li"),tagged[t].title,true);
		if(t<tagged.length-1)
			createTiddlyText(ul,sep);
	}
};

config.macros.closeAll.handler = function(place)
{
	createTiddlyButton(place,this.label,this.prompt,this.onClick);
};

config.macros.closeAll.onClick = function(e)
{
	story.closeAllTiddlers();
	return false;
};

config.macros.permaview.handler = function(place)
{
	createTiddlyButton(place,this.label,this.prompt,this.onClick);
};

config.macros.permaview.onClick = function(e)
{
	story.permaView();
	return false;
};

config.macros.saveChanges.handler = function(place,macroName,params)
{
	if(!readOnly)
		createTiddlyButton(place,params[0] || this.label,params[1] || this.prompt,this.onClick,null,null,this.accessKey);
};

config.macros.saveChanges.onClick = function(e)
{
	saveChanges();
	return false;
};

config.macros.slider.onClickSlider = function(ev)
{
	var n = this.nextSibling;
	var cookie = n.getAttribute("cookie");
	var isOpen = n.style.display != "none";
	if(config.options.chkAnimate && anim && typeof Slider == "function")
		anim.startAnimating(new Slider(n,!isOpen,null,"none"));
	else
		n.style.display = isOpen ? "none" : "block";
	config.options[cookie] = !isOpen;
	saveOption(cookie);
	return false;
};

config.macros.slider.createSlider = function(place,cookie,title,tooltip)
{
	var c = cookie || "";
	createTiddlyButton(place,title,tooltip,this.onClickSlider);
	var panel = createTiddlyElement(null,"div",null,"sliderPanel");
	panel.setAttribute("cookie",c);
	panel.style.display = config.options[c] ? "block" : "none";
	place.appendChild(panel);
	return panel;
};

config.macros.slider.handler = function(place,macroName,params)
{
	var panel = this.createSlider(place,params[0],params[2],params[3]);
	var text = store.getTiddlerText(params[1]);
	panel.setAttribute("refresh","content");
	panel.setAttribute("tiddler",params[1]);
	if(text)
		wikify(text,panel,null,store.getTiddler(params[1]));
};

// <<gradient [[tiddler name]] vert|horiz rgb rgb rgb rgb... >>
config.macros.gradient.handler = function(place,macroName,params,wikifier,paramString,tiddler)
{
	var panel = wikifier ? createTiddlyElement(place,"div",null,"gradient") : place;
	panel.style.position = "relative";
	panel.style.overflow = "hidden";
	panel.style.zIndex = "0";
	if(wikifier) {
		var styles = config.formatterHelpers.inlineCssHelper(wikifier);
		config.formatterHelpers.applyCssHelper(panel,styles);
	}
	params = paramString.parseParams("color");
	var locolors = [], hicolors = [];
	var t;
	for(t=2; t<params.length; t++) {
		var c = params[t].value;
		if(params[t].name == "snap") {
			hicolors[hicolors.length-1] = c;
		} else {
			locolors.push(c);
			hicolors.push(c);
		}
	}
	drawGradient(panel,params[1].value != "vert",locolors,hicolors);
	if(wikifier)
		wikifier.subWikify(panel,">>");
	if(document.all) {
		panel.style.height = "100%";
		panel.style.width = "100%";
	}
};

config.macros.message.handler = function(place,macroName,params)
{
	if(params[0]) {
		var names = params[0].split(".");
		var lookupMessage = function(root,nameIndex) {
				if(root[names[nameIndex]]) {
					if(nameIndex < names.length-1)
						return (lookupMessage(root[names[nameIndex]],nameIndex+1));
					else
						return root[names[nameIndex]];
				} else
					return null;
			};
		var m = lookupMessage(config,0);
		if(m == null)
			m = lookupMessage(window,0);
		createTiddlyText(place,m.toString().format(params.splice(1)));
	}
};


config.macros.view.depth = 0;
config.macros.view.values = [];
config.macros.view.views = {
	text: function(value,place,params,wikifier,paramString,tiddler) {
		highlightify(value,place,highlightHack,tiddler);
	},
	link: function(value,place,params,wikifier,paramString,tiddler) {
		createTiddlyLink(place,value,true);
	},
	wikified: function(value,place,params,wikifier,paramString,tiddler) {
		if(config.macros.view.depth>50)
			return;
		if(config.macros.view.depth>0) {
			if (value==config.macros.view.values[config.macros.view.depth-1]) {
				return;
			}
		}
		config.macros.view.values[config.macros.view.depth] = value;
		config.macros.view.depth++;
		if(params[2])
			value=params[2].unescapeLineBreaks().format([value]);
		wikify(value,place,highlightHack,tiddler);
		config.macros.view.depth--;
		config.macros.view.values[config.macros.view.depth] = null;
	},
	date: function(value,place,params,wikifier,paramString,tiddler) {
		value = Date.convertFromYYYYMMDDHHMM(value);
		createTiddlyText(place,value.formatString(params[2] || config.views.wikified.dateFormat));
	}
};

config.macros.view.handler = function(place,macroName,params,wikifier,paramString,tiddler)
{
	if((tiddler instanceof Tiddler) && params[0]) {
		var value = store.getValue(tiddler,params[0]);
		if(value) {
			var type = params[1] || config.macros.view.defaultView;
			var handler = config.macros.view.views[type];
			if(handler)
				handler(value,place,params,wikifier,paramString,tiddler);
		}
	}
};

config.macros.edit.handler = function(place,macroName,params,wikifier,paramString,tiddler)
{
	var field = params[0];
	var rows = params[1] || 0;
	var defVal = params[2] || '';
	if((tiddler instanceof Tiddler) && field) {
		story.setDirty(tiddler.title,true);
		var e,v;
		if(field != "text" && !rows) {
			e = createTiddlyElement(null,"input",null,null,null,{
				type: "text", edit: field, size: "40", autocomplete: "off"
			});
			e.value = store.getValue(tiddler,field) || defVal;
			place.appendChild(e);
		} else {
			var wrapper1 = createTiddlyElement(null,"fieldset",null,"fieldsetFix");
			var wrapper2 = createTiddlyElement(wrapper1,"div");
			e = createTiddlyElement(wrapper2,"textarea");
			e.value = v = store.getValue(tiddler,field) || defVal;
			rows = rows || 10;
			var lines = v.match(/\n/mg);
			var maxLines = Math.max(parseInt(config.options.txtMaxEditRows,10),5);
			if(lines != null && lines.length > rows)
				rows = lines.length + 5;
			rows = Math.min(rows,maxLines);
			e.setAttribute("rows",rows);
			e.setAttribute("edit",field);
			place.appendChild(wrapper1);
		}
		if(tiddler.isReadOnly()) {
			e.setAttribute("readOnly","readOnly");
			jQuery(e).addClass("readOnly");
		}
		return e;
	}
};

config.macros.tagChooser.onClick = function(ev)
{
	var e = ev || window.event;
	var lingo = config.views.editor.tagChooser;
	var popup = Popup.create(this);
	var tags = store.getTags(this.getAttribute("tags"));
	if(tags.length == 0)
		jQuery("<li/>").text(lingo.popupNone).appendTo(popup);
	var t;
	for(t=0; t<tags.length; t++) {
		var tag = createTiddlyButton(createTiddlyElement(popup,"li"),tags[t][0],lingo.tagTooltip.format([tags[t][0]]),config.macros.tagChooser.onTagClick);
		tag.setAttribute("tag",tags[t][0]);
		tag.setAttribute("tiddler",this.getAttribute("tiddler"));
	}
	Popup.show();
	e.cancelBubble = true;
	if(e.stopPropagation) e.stopPropagation();
	return false;
};

config.macros.tagChooser.onTagClick = function(ev)
{
	var e = ev || window.event;
	if(e.metaKey || e.ctrlKey) stopEvent(e); //# keep popup open on CTRL-click
	var tag = this.getAttribute("tag");
	var title = this.getAttribute("tiddler");
	if(!readOnly)
		story.setTiddlerTag(title,tag,0);
	return false;
};

config.macros.tagChooser.handler = function(place,macroName,params,wikifier,paramString,tiddler)
{
	if(tiddler instanceof Tiddler) {
		var lingo = config.views.editor.tagChooser;
		var btn = createTiddlyButton(place,lingo.text,lingo.tooltip,this.onClick);
		btn.setAttribute("tiddler",tiddler.title);
		btn.setAttribute("tags",params[0]);
	}
};

config.macros.refreshDisplay.handler = function(place)
{
	createTiddlyButton(place,this.label,this.prompt,this.onClick);
};

config.macros.refreshDisplay.onClick = function(e)
{
	refreshAll();
	return false;
};

config.macros.annotations.handler = function(place,macroName,params,wikifier,paramString,tiddler)
{
	var title = tiddler ? tiddler.title : null;
	var a = title ? config.annotations[title] : null;
	if(!tiddler || !title || !a)
		return;
	var text = a.format([title]);
	wikify(text,createTiddlyElement(place,"div",null,"annotation"),null,tiddler);
};
//--
//-- NewTiddler and NewJournal macros
//--

config.macros.newTiddler.createNewTiddlerButton = function(place,title,params,label,prompt,accessKey,newFocus,isJournal)
{
	var tags = [];
	var t;
	for(t=1; t<params.length; t++) {
		if((params[t].name == "anon" && t != 1) || (params[t].name == "tag"))
			tags.push(params[t].value);
	}
	label = getParam(params,"label",label);
	prompt = getParam(params,"prompt",prompt);
	accessKey = getParam(params,"accessKey",accessKey);
	newFocus = getParam(params,"focus",newFocus);
	var customFields = getParam(params,"fields","");
	if(!customFields && !store.isShadowTiddler(title))
		customFields = String.encodeHashMap(config.defaultCustomFields);
	var btn = createTiddlyButton(place,label,prompt,this.onClickNewTiddler,null,null,accessKey);
	btn.setAttribute("newTitle",title);
	btn.setAttribute("isJournal",isJournal ? "true" : "false");
	if(tags.length > 0)
		btn.setAttribute("params",tags.join("|"));
	btn.setAttribute("newFocus",newFocus);
	btn.setAttribute("newTemplate",getParam(params,"template",DEFAULT_EDIT_TEMPLATE));
	if(customFields !== "")
		btn.setAttribute("customFields",customFields);
	var text = getParam(params,"text");
	if(text !== undefined)
		btn.setAttribute("newText",text);
	return btn;
};

config.macros.newTiddler.onClickNewTiddler = function()
{
	var title = this.getAttribute("newTitle");
	if(this.getAttribute("isJournal") == "true") {
		title = new Date().formatString(title.trim());
	}
	var params = this.getAttribute("params");
	var tags = params ? params.split("|") : [];
	var focus = this.getAttribute("newFocus");
	var template = this.getAttribute("newTemplate");
	var customFields = this.getAttribute("customFields");
	if(!customFields && !store.isShadowTiddler(title))
		customFields = String.encodeHashMap(config.defaultCustomFields);
	story.displayTiddler(null,title,template,false,null,null);
	var tiddlerElem = story.getTiddler(title);
	if(customFields)
		story.addCustomFields(tiddlerElem,customFields);
	var text = this.getAttribute("newText");
	if(typeof text == "string" && story.getTiddlerField(title,"text"))
		story.getTiddlerField(title,"text").value = text.format([title]);
	var t;
	for(t=0;t<tags.length;t++)
		story.setTiddlerTag(title,tags[t],+1);
	story.focusTiddler(title,focus);
	return false;
};

config.macros.newTiddler.handler = function(place,macroName,params,wikifier,paramString)
{
	if(!readOnly) {
		params = paramString.parseParams("anon",null,true,false,false);
		var title = params[1] && params[1].name == "anon" ? params[1].value : this.title;
		title = getParam(params,"title",title);
		this.createNewTiddlerButton(place,title,params,this.label,this.prompt,this.accessKey,"title",false);
	}
};

config.macros.newJournal.handler = function(place,macroName,params,wikifier,paramString)
{
	if(!readOnly) {
		params = paramString.parseParams("anon",null,true,false,false);
		var title = params[1] && params[1].name == "anon" ? params[1].value : config.macros.timeline.dateFormat;
		title = getParam(params,"title",title);
		config.macros.newTiddler.createNewTiddlerButton(place,title,params,this.label,this.prompt,this.accessKey,"text",true);
	}
};

//--
//-- Search macro
//--

config.macros.search.handler = function(place,macroName,params,wikifier,paramString,tiddler)
{
	params = paramString.parseParams("anon",null,false,false,false);
	createTiddlyButton(place,this.label,this.prompt,this.onClick,"searchButton");
	var txt = createTiddlyElement(null,"input",null,"txtOptionInput searchField");
	txt.value = getParam(params,"anon","");
	if(config.browser.isSafari) {
		txt.setAttribute("type","search");
		txt.setAttribute("results","5");
	} else {
		txt.setAttribute("type","text");
	}
	place.appendChild(txt);
	txt.onkeyup = this.onKeyPress;
	txt.onfocus = this.onFocus;
	txt.setAttribute("size",this.sizeTextbox);
	txt.setAttribute("accessKey",getParam(params,"accesskey",this.accessKey));
	txt.setAttribute("autocomplete","off");
	txt.setAttribute("lastSearchText","");
	txt.setAttribute("placeholder",getParam(params,"placeholder",this.placeholder));
};

// Global because there's only ever one outstanding incremental search timer
config.macros.search.timeout = null;

config.macros.search.doSearch = function(txt)
{
	if(txt.value.length > 0) {
		story.search(txt.value,config.options.chkCaseSensitiveSearch,config.options.chkRegExpSearch);
		txt.setAttribute("lastSearchText",txt.value);
	}
};

config.macros.search.onClick = function(e)
{
	config.macros.search.doSearch(this.nextSibling);
	return false;
};

config.macros.search.onKeyPress = function(ev)
{
	var me = config.macros.search;
	var e = ev || window.event;
	switch(e.keyCode) {
		case 9: // Tab
			return;
		case 13: // Ctrl-Enter
		case 10: // Ctrl-Enter on IE PC
			me.doSearch(this);
			break;
		case 27: // Escape
			this.value = "";
			clearMessage();
			break;
	}
	if(config.options.chkIncrementalSearch) {
		if(this.value.length > 2) {
			if(this.value != this.getAttribute("lastSearchText")) {
				if(me.timeout) {
					clearTimeout(me.timeout);
				}
				var txt = this;
				me.timeout = setTimeout(function() {me.doSearch(txt);},500);
			}
		} else {
			if(me.timeout) {
				clearTimeout(me.timeout);
			}
		}
	}
};

config.macros.search.onFocus = function(e)
{
	this.select();
};

//--
//-- Tabs macro
//--

config.macros.tabs.handler = function(place,macroName,params)
{
	var cookie = params[0];
	var numTabs = (params.length-1)/3;
	var wrapper = createTiddlyElement(null,"div",null,"tabsetWrapper " + cookie);
	var tabset = createTiddlyElement(wrapper,"div",null,"tabset");
	tabset.setAttribute("cookie",cookie);
	var validTab = false;
	var t;
	for(t=0; t<numTabs; t++) {
		var label = params[t*3+1];
		var prompt = params[t*3+2];
		var content = params[t*3+3];
		var tab = createTiddlyButton(tabset,label,prompt,this.onClickTab,"tab tabUnselected");
		createTiddlyElement(tab,"span",null,null," ",{style:"font-size:0pt;line-height:0px"});
		tab.setAttribute("tab",label);
		tab.setAttribute("content",content);
		tab.title = prompt;
		if(config.options[cookie] == label)
			validTab = true;
	}
	if(!validTab)
		config.options[cookie] = params[1];
	place.appendChild(wrapper);
	this.switchTab(tabset,config.options[cookie]);
};

config.macros.tabs.onClickTab = function(e)
{
	config.macros.tabs.switchTab(this.parentNode,this.getAttribute("tab"));
	return false;
};

config.macros.tabs.switchTab = function(tabset,tab)
{
	var cookie = tabset.getAttribute("cookie");
	var theTab = null;
	var nodes = tabset.childNodes;
	var t;
	for(t=0; t<nodes.length; t++) {
		if(nodes[t].getAttribute && nodes[t].getAttribute("tab") == tab) {
			theTab = nodes[t];
			theTab.className = "tab tabSelected";
		} else {
			nodes[t].className = "tab tabUnselected";
		}
	}
	if(theTab) {
		if(tabset.nextSibling && tabset.nextSibling.className == "tabContents")
			jQuery(tabset.nextSibling).remove();
		var tabContent = createTiddlyElement(null,"div",null,"tabContents");
		tabset.parentNode.insertBefore(tabContent,tabset.nextSibling);
		var contentTitle = theTab.getAttribute("content");
		wikify(store.getTiddlerText(contentTitle),tabContent,null,store.getTiddler(contentTitle));
		if(cookie) {
			config.options[cookie] = tab;
			saveOption(cookie);
		}
	}
};

//--
//-- Tiddler toolbar
//--

// Create a toolbar command button
config.macros.toolbar.createCommand = function(place,commandName,tiddler,className)
{
	if(typeof commandName != "string") {
		var c = null;
		var t;
		for(t in config.commands) {
			if(config.commands[t] == commandName)
				c = t;
		}
		commandName = c;
	}
	if((tiddler instanceof Tiddler) && (typeof commandName == "string")) {
		var command = config.commands[commandName];
		if(command.isEnabled ? command.isEnabled(tiddler) : this.isCommandEnabled(command,tiddler)) {
			var text = command.getText ? command.getText(tiddler) : this.getCommandText(command,tiddler);
			var tooltip = command.getTooltip ? command.getTooltip(tiddler) : this.getCommandTooltip(command,tiddler);
			var cmd = command.type == "popup" ? this.onClickPopup : this.onClickCommand;
			var btn = createTiddlyButton(null,text,tooltip,cmd);
			btn.setAttribute("commandName",commandName);
			btn.setAttribute("tiddler",tiddler.title);
			jQuery(btn).addClass("command_" + commandName);
			if(className)
				jQuery(btn).addClass(className);
			place.appendChild(btn);
		}
	}
};

config.macros.toolbar.isCommandEnabled = function(command,tiddler)
{
	var title = tiddler.title;
	var ro = tiddler.isReadOnly();
	var shadow = store.isShadowTiddler(title) && !store.tiddlerExists(title);
	return (!ro || (ro && !command.hideReadOnly)) && !(shadow && command.hideShadow);
};

config.macros.toolbar.getCommandText = function(command,tiddler)
{
	return (tiddler.isReadOnly() && command.readOnlyText) || command.text;
};

config.macros.toolbar.getCommandTooltip = function(command,tiddler)
{
	return (tiddler.isReadOnly() && command.readOnlyTooltip) || command.tooltip;
};

config.macros.toolbar.onClickCommand = function(ev)
{
	var e = ev || window.event;
	e.cancelBubble = true;
	if(e.stopPropagation) e.stopPropagation();
	var command = config.commands[this.getAttribute("commandName")];
	return command.handler(e,this,this.getAttribute("tiddler"));
};

config.macros.toolbar.onClickPopup = function(ev)
{
	var e = ev || window.event;
	e.cancelBubble = true;
	if(e.stopPropagation) e.stopPropagation();
	var popup = Popup.create(this);
	var command = config.commands[this.getAttribute("commandName")];
	var title = this.getAttribute("tiddler");
	popup.setAttribute("tiddler",title);
	command.handlePopup(popup,title);
	Popup.show();
	return false;
};

// Invoke the first command encountered from a given place that is tagged with a specified class
config.macros.toolbar.invokeCommand = function(place,className,event)
{
	var children = place.getElementsByTagName("a");
	var t;
	for(t=0; t<children.length; t++) {
		var c = children[t];
		if(jQuery(c).hasClass(className) && c.getAttribute && c.getAttribute("commandName")) {
			if(c.onclick instanceof Function)
				c.onclick.call(c,event);
			break;
		}
	}
};

config.macros.toolbar.onClickMore = function(ev)
{
	var e = this.nextSibling;
	e.style.display = "inline";
	this.style.display = "none";
	return false;
};

config.macros.toolbar.onClickLess = function(ev)
{
	var e = this.parentNode;
	var m = e.previousSibling;
	e.style.display = "none";
	m.style.display = "inline";
	return false;
};

config.macros.toolbar.handler = function(place,macroName,params,wikifier,paramString,tiddler)
{
	var t;
	for(t=0; t<params.length; t++) {
		var btn;
		var c = params[t];
		switch(c) {
		case "!":
			createTiddlyText(place,this.separator);
			break;
		case "*":
			createTiddlyElement(place,"br");
			break;
		case "<":
			btn = createTiddlyButton(place,this.lessLabel,this.lessPrompt,config.macros.toolbar.onClickLess);
			jQuery(btn).addClass("lessCommand");
			break;
		case ">":
			btn = createTiddlyButton(place,this.moreLabel,this.morePrompt,config.macros.toolbar.onClickMore);
			jQuery(btn).addClass("moreCommand");
			var e = createTiddlyElement(place,"span",null,"moreCommand");
			e.style.display = "none";
			place = e;
			break;
		default:
			var className = "";
			switch(c.substr(0,1)) {
			case "+":
				className = "defaultCommand";
				c = c.substr(1);
				break;
			case "-":
				className = "cancelCommand";
				c = c.substr(1);
				break;
			}
			if(config.commands[c]) {
				this.createCommand(place,c,tiddler,className);
			} else {
				this.customCommand(place,c,wikifier,tiddler);
			}
			break;
		}
	}
};

// Overrideable function to extend toolbar handler
config.macros.toolbar.customCommand = function(place,command,wikifier,tiddler)
{
};

//--
//-- Menu and toolbar commands
//--

config.commands.closeTiddler.handler = function(event,src,title)
{
	if(story.isDirty(title) && !readOnly) {
		if(!confirm(config.commands.cancelTiddler.warning.format([title])))
			return false;
	}
	story.setDirty(title,false);
	story.closeTiddler(title,true);
	return false;
};

config.commands.closeOthers.handler = function(event,src,title)
{
	story.closeAllTiddlers(title);
	return false;
};

config.commands.editTiddler.handler = function(event,src,title)
{
	clearMessage();
	var tiddlerElem = story.getTiddler(title);
	var fields = tiddlerElem.getAttribute("tiddlyFields");
	story.displayTiddler(null,title,DEFAULT_EDIT_TEMPLATE,false,null,fields);
	var e = story.getTiddlerField(title,config.options.txtEditorFocus||"text");
	if(e) {
		setCaretPosition(e,0);
	}
	return false;
};

config.commands.saveTiddler.handler = function(event,src,title)
{
	var newTitle = story.saveTiddler(title,event.shiftKey);
	if(newTitle)
		story.displayTiddler(null,newTitle);
	return false;
};

config.commands.cancelTiddler.handler = function(event,src,title)
{
	if(story.hasChanges(title) && !readOnly) {
		if(!confirm(this.warning.format([title])))
			return false;
	}
	story.setDirty(title,false);
	story.displayTiddler(null,title);
	return false;
};

config.commands.deleteTiddler.handler = function(event,src,title)
{
	var deleteIt = true;
	if(config.options.chkConfirmDelete)
		deleteIt = confirm(this.warning.format([title]));
	if(deleteIt) {
		store.removeTiddler(title);
		story.closeTiddler(title,true);
		autoSaveChanges();
	}
	return false;
};

config.commands.permalink.handler = function(event,src,title)
{
	var t = encodeURIComponent(String.encodeTiddlyLink(title));
	if(window.location.hash != t)
		window.location.hash = t;
	return false;
};

config.commands.references.handlePopup = function(popup,title)
{
	var references = store.getReferringTiddlers(title);
	var c = false;
	var r;
	for(r=0; r<references.length; r++) {
		if(references[r].title != title && !references[r].isTagged("excludeLists")) {
			createTiddlyLink(createTiddlyElement(popup,"li"),references[r].title,true);
			c = true;
		}
	}
	if(!c)
		createTiddlyElement(popup,"li",null,"disabled",this.popupNone);
};

config.commands.jump.handlePopup = function(popup,title)
{
	story.forEachTiddler(function(title,element) {
		createTiddlyLink(createTiddlyElement(popup,"li"),title,true,null,false,null,true);
		});
};

config.commands.fields.handlePopup = function(popup,title)
{
	var tiddler = store.fetchTiddler(title);
	if(!tiddler)
		return;
	var items = [];
	store.forEachField(tiddler,function(tiddler,fieldName,value){items.push({field:fieldName,value:value});},true);
	items.sort(function(a,b) {return a.field < b.field ? -1 : (a.field == b.field ? 0 : +1);});
	if(items.length > 0)
		ListView.create(popup,items,this.listViewTemplate);
	else
		createTiddlyElement(popup,"div",null,null,this.emptyText);
};

//--
//-- Tiddler() object
//--

function Tiddler(title)
{
	this.title = title;
	this.text = "";
	this.creator = null;
	this.modifier = null;
	this.created = new Date();
	this.modified = this.created;
	this.links = [];
	this.linksUpdated = false;
	this.tags = [];
	this.fields = {};
	return this;
}

Tiddler.prototype.getLinks = function()
{
	if(this.linksUpdated==false)
		this.changed();
	return this.links;
};

// Returns the fields that are inherited in string field:"value" field2:"value2" format
Tiddler.prototype.getInheritedFields = function()
{
	var f = {};
	var i;
	for(i in this.fields) {
		if(i=="server.host" || i=="server.workspace" || i=="wikiformat"|| i=="server.type") {
			f[i] = this.fields[i];
		}
	}
	return String.encodeHashMap(f);
};

// Increment the changeCount of a tiddler
Tiddler.prototype.incChangeCount = function()
{
	var c = this.fields['changecount'];
	c = c ? parseInt(c,10) : 0;
	this.fields['changecount'] = String(c+1);
};

// Clear the changeCount of a tiddler
Tiddler.prototype.clearChangeCount = function()
{
	if(this.fields['changecount']) {
		delete this.fields['changecount'];
	}
};

Tiddler.prototype.doNotSave = function()
{
	return this.fields['doNotSave'];
};

// Returns true if the tiddler has been updated since the tiddler was created or downloaded
Tiddler.prototype.isTouched = function()
{
	var changecount = this.fields.changecount || 0;
	return changecount > 0;
};

// Change the text and other attributes of a tiddler
Tiddler.prototype.set = function(title,text,modifier,modified,tags,created,fields,creator)
{
	this.assign(title,text,modifier,modified,tags,created,fields,creator);
	this.changed();
	return this;
};

// Change the text and other attributes of a tiddler without triggered a tiddler.changed() call
Tiddler.prototype.assign = function(title,text,modifier,modified,tags,created,fields,creator)
{
	if(title != undefined)
		this.title = title;
	if(text != undefined)
		this.text = text;
	if(modifier != undefined)
		this.modifier = modifier;
	if(modified != undefined)
		this.modified = modified;
	if(creator != undefined)
		this.creator = creator;
	if(created != undefined)
		this.created = created;
	if(fields != undefined)
		this.fields = fields;
	if(tags != undefined)
		this.tags = (typeof tags == "string") ? tags.readBracketedList() : tags;
	else if(this.tags == undefined)
		this.tags = [];
	return this;
};

// Get the tags for a tiddler as a string (space delimited, using [[brackets]] for tags containing spaces)
Tiddler.prototype.getTags = function()
{
	return String.encodeTiddlyLinkList(this.tags);
};

// Test if a tiddler carries a tag
Tiddler.prototype.isTagged = function(tag)
{
	return this.tags.indexOf(tag) != -1;
};

// Static method to convert "\n" to newlines, "\s" to "\"
Tiddler.unescapeLineBreaks = function(text)
{
	return text ? text.unescapeLineBreaks() : "";
};

// Convert newlines to "\n", "\" to "\s"
Tiddler.prototype.escapeLineBreaks = function()
{
	return this.text.escapeLineBreaks();
};

// Updates the secondary information (like links[] array) after a change to a tiddler
Tiddler.prototype.changed = function()
{
	this.links = [];
	var text = this.text;
	// remove 'quoted' text before scanning tiddler source
	text = text.replace(/\/%((?:.|\n)*?)%\//g,"").
		replace(/\{{3}((?:.|\n)*?)\}{3}/g,"").
		replace(/"""((?:.|\n)*?)"""/g,"").
		replace(/<nowiki\>((?:.|\n)*?)<\/nowiki\>/g,"").
		replace(/<html\>((?:.|\n)*?)<\/html\>/g,"").
		replace(/<script((?:.|\n)*?)<\/script\>/g,"");
	var t = this.autoLinkWikiWords() ? 0 : 1;
	var tiddlerLinkRegExp = t==0 ? config.textPrimitives.tiddlerAnyLinkRegExp : config.textPrimitives.tiddlerForcedLinkRegExp;
	tiddlerLinkRegExp.lastIndex = 0;
	var formatMatch = tiddlerLinkRegExp.exec(text);
	while(formatMatch) {
		var lastIndex = tiddlerLinkRegExp.lastIndex;
		if(t==0 && formatMatch[1] && formatMatch[1] != this.title) {
			// wikiWordLink
			if(formatMatch.index > 0) {
				var preRegExp = new RegExp(config.textPrimitives.unWikiLink+"|"+config.textPrimitives.anyLetter,"mg");
				preRegExp.lastIndex = formatMatch.index-1;
				var preMatch = preRegExp.exec(text);
				if(preMatch.index != formatMatch.index-1)
					this.links.pushUnique(formatMatch[1]);
			} else {
				this.links.pushUnique(formatMatch[1]);
			}
		}
		else if(formatMatch[2-t] && !config.formatterHelpers.isExternalLink(formatMatch[3-t])) // titledBrackettedLink
			this.links.pushUnique(formatMatch[3-t]);
		else if(formatMatch[4-t] && formatMatch[4-t] != this.title) // brackettedLink
			this.links.pushUnique(formatMatch[4-t]);
		tiddlerLinkRegExp.lastIndex = lastIndex;
		formatMatch = tiddlerLinkRegExp.exec(text);
	}
	this.linksUpdated = true;
};

Tiddler.prototype.getSubtitle = function()
{
	var modifier = this.modifier;
	if(!modifier)
		modifier = config.messages.subtitleUnknown || "";
	var modified = this.modified;
	if(modified)
		modified = modified.toLocaleString();
	else
		modified = config.messages.subtitleUnknown || "";
	var f = config.messages.tiddlerLinkTooltip || "%0 - %1, %2";
	return f.format([this.title,modifier,modified]);
};

Tiddler.prototype.isReadOnly = function()
{
	return readOnly;
};

Tiddler.prototype.autoLinkWikiWords = function()
{
	return !(this.isTagged("systemConfig") || this.isTagged("excludeMissing"));
};

Tiddler.prototype.getServerType = function()
{
	var serverType = null;
	if(this.fields['server.type'])
		serverType = this.fields['server.type'];
	if(!serverType)
		serverType = this.fields['wikiformat'];
	if(serverType && !config.adaptors[serverType])
		serverType = null;
	return serverType;
};

Tiddler.prototype.getAdaptor = function()
{
	var serverType = this.getServerType();
	return serverType ? new config.adaptors[serverType]() : null;
};

//--
//-- TiddlyWiki instance contains TiddlerS
//--

function TiddlyWiki(params)
{
	var tiddlers = {}; // Hashmap by name of tiddlers
	if(params && params.config) {
		this.config = config;
	}
	this.tiddlersUpdated = false;
	this.namedNotifications = []; // Array of {name:,notify:} of notification functions
	this.notificationLevel = 0;
	this.slices = {}; // map tiddlerName->(map sliceName->sliceValue). Lazy.
	this.clear = function() {
		tiddlers = {};
		this.setDirty(false);
	};
	this.fetchTiddler = function(title) {
		var t = tiddlers[title];
		return t instanceof Tiddler ? t : null;
	};
	this.deleteTiddler = function(title) {
		delete this.slices[title];
		delete tiddlers[title];
	};
	this.addTiddler = function(tiddler) {
		delete this.slices[tiddler.title];
		tiddlers[tiddler.title] = tiddler;
	};
	this.forEachTiddler = function(callback) {
		var t;
		for(t in tiddlers) {
			var tiddler = tiddlers[t];
			if(tiddler instanceof Tiddler)
				callback.call(this,t,tiddler);
		}
	};
}

TiddlyWiki.prototype.setDirty = function(dirty)
{
	this.dirty = dirty;
};

TiddlyWiki.prototype.isDirty = function()
{
	return this.dirty;
};

TiddlyWiki.prototype.tiddlerExists = function(title)
{
	var t = this.fetchTiddler(title);
	return t != undefined;
};

TiddlyWiki.prototype.isShadowTiddler = function(title)
{
	return config.shadowTiddlers[title] === undefined ? false : true;
};

TiddlyWiki.prototype.isAvailable = function(title) {
	if (!title)
		return false;
	var s = title ? title.indexOf(config.textPrimitives.sectionSeparator) : -1;
	if(s!=-1)
		title = title.substr(0,s);
	return this.tiddlerExists(title) || this.isShadowTiddler(title);
};

TiddlyWiki.prototype.createTiddler = function(title)
{
	var tiddler = this.fetchTiddler(title);
	if(!tiddler) {
		tiddler = new Tiddler(title);
		this.addTiddler(tiddler);
		this.setDirty(true);
	}
	return tiddler;
};

TiddlyWiki.prototype.getTiddler = function(title)
{
	var t = this.fetchTiddler(title);
	if(t != undefined)
		return t;
	else
		return null;
};

TiddlyWiki.prototype.getShadowTiddlerText = function(title)
{
	if(typeof config.shadowTiddlers[title] == "string")
		return config.shadowTiddlers[title];
	else
		return "";
};

// Retrieve tiddler contents
TiddlyWiki.prototype.getTiddlerText = function(title,defaultText)
{
	if(!title)
		return defaultText;
	var pos = title.indexOf(config.textPrimitives.sectionSeparator);
	var section = null;
	if(pos != -1) {
		section = title.substr(pos + config.textPrimitives.sectionSeparator.length);
		title = title.substr(0,pos);
	}
	pos = title.indexOf(config.textPrimitives.sliceSeparator);
	if(pos != -1) {
		var slice = this.getTiddlerSlice(title.substr(0,pos),title.substr(pos + config.textPrimitives.sliceSeparator.length));
		if(slice)
			return slice;
	}
	var tiddler = this.fetchTiddler(title);
	var text = tiddler ? tiddler.text : null;
	if(!tiddler && this.isShadowTiddler(title)) {
		text = this.getShadowTiddlerText(title);
	}
	if(text) {
		if(!section)
			return text;
		var re = new RegExp("(^!{1,6}[ \t]*" + section.escapeRegExp() + "[ \t]*\n)","mg");
		re.lastIndex = 0;
		var match = re.exec(text);
		if(match) {
			var t = text.substr(match.index+match[1].length);
			var re2 = /^!/mg;
			re2.lastIndex = 0;
			match = re2.exec(t); //# search for the next heading
			if(match)
				t = t.substr(0,match.index-1);//# don't include final \n
			return t;
		}
		return defaultText;
	}
	if(defaultText != undefined)
		return defaultText;
	return null;
};

TiddlyWiki.prototype.getRecursiveTiddlerText = function(title,defaultText,depth)
{
	var bracketRegExp = new RegExp("(?:\\[\\[([^\\]]+)\\]\\])","mg");
	var text = this.getTiddlerText(title,null);
	if(text == null)
		return defaultText;
	var textOut = [];
	var match,lastPos = 0;
	do {
		match = bracketRegExp.exec(text);
		if(match) {
			textOut.push(text.substr(lastPos,match.index-lastPos));
			if(match[1]) {
				if(depth <= 0)
					textOut.push(match[1]);
				else
					textOut.push(this.getRecursiveTiddlerText(match[1],"",depth-1));
			}
			lastPos = match.index + match[0].length;
		} else {
			textOut.push(text.substr(lastPos));
		}
	} while(match);
	return textOut.join("");
};

//TiddlyWiki.prototype.slicesRE = /(?:^([\'\/]{0,2})~?([\.\w]+)\:\1[\t\x20]*([^\n]+)[\t\x20]*$)|(?:^\|([\'\/]{0,2})~?([\.\w]+)\:?\4\|[\t\x20]*([^\n]+)[\t\x20]*\|$)/gm;
TiddlyWiki.prototype.slicesRE = /(?:^([\'\/]{0,2})~?([\.\w]+)\:\1[\t\x20]*([^\n]*)[\t\x20]*$)|(?:^\|([\'\/]{0,2})~?([\.\w]+)\:?\4\|[\t\x20]*([^\|\n]*)[\t\x20]*\|$)/gm;
// @internal
TiddlyWiki.prototype.calcAllSlices = function(title)
{
	var slices = {};
	var text = this.getTiddlerText(title,"");
	this.slicesRE.lastIndex = 0;
	var m = this.slicesRE.exec(text);
	while(m) {
		if(m[2])
			slices[m[2]] = m[3];
		else
			slices[m[5]] = m[6];
		m = this.slicesRE.exec(text);
	}
	return slices;
};

// Returns the slice of text of the given name
TiddlyWiki.prototype.getTiddlerSlice = function(title,sliceName)
{
	var slices = this.slices[title];
	if(!slices) {
		slices = this.calcAllSlices(title);
		this.slices[title] = slices;
	}
	return slices[sliceName];
};

// Build an hashmap of the specified named slices of a tiddler
TiddlyWiki.prototype.getTiddlerSlices = function(title,sliceNames)
{
	var t,r = {};
	for(t=0; t<sliceNames.length; t++) {
		var slice = this.getTiddlerSlice(title,sliceNames[t]);
		if(slice)
			r[sliceNames[t]] = slice;
	}
	return r;
};

TiddlyWiki.prototype.suspendNotifications = function()
{
	this.notificationLevel--;
};

TiddlyWiki.prototype.resumeNotifications = function()
{
	this.notificationLevel++;
};

// Invoke the notification handlers for a particular tiddler
TiddlyWiki.prototype.notify = function(title,doBlanket)
{
	if(!this.notificationLevel) {
	    var t;
		for(t=0; t<this.namedNotifications.length; t++) {
			var n = this.namedNotifications[t];
			if((n.name == null && doBlanket) || (n.name == title))
				n.notify(title);
		}
	}
};

// Invoke the notification handlers for all tiddlers
TiddlyWiki.prototype.notifyAll = function()
{
	if(!this.notificationLevel) {
	    var t;
		for(t=0; t<this.namedNotifications.length; t++) {
			var n = this.namedNotifications[t];
			if(n.name)
				n.notify(n.name);
		}
	}
};

// Add a notification handler to a tiddler
TiddlyWiki.prototype.addNotification = function(title,fn)
{
	var i;
	for(i=0; i<this.namedNotifications.length; i++) {
		if((this.namedNotifications[i].name == title) && (this.namedNotifications[i].notify == fn))
			return this;
	}
	this.namedNotifications.push({name: title, notify: fn});
	return this;
};

TiddlyWiki.prototype.removeTiddler = function(title)
{
	var tiddler = this.fetchTiddler(title);
	if(tiddler) {
		this.deleteTiddler(title);
		this.notify(title,true);
		this.setDirty(true);
	}
};

// Reset the sync status of a freshly synced tiddler
TiddlyWiki.prototype.resetTiddler = function(title)
{
	var tiddler = this.fetchTiddler(title);
	if(tiddler) {
		tiddler.clearChangeCount();
		this.notify(title,true);
		this.setDirty(true);
	}
};

TiddlyWiki.prototype.setTiddlerTag = function(title,status,tag)
{
	var tiddler = this.fetchTiddler(title);
	if(tiddler) {
		var t = tiddler.tags.indexOf(tag);
		if(t != -1)
			tiddler.tags.splice(t,1);
		if(status)
			tiddler.tags.push(tag);
		tiddler.changed();
		tiddler.incChangeCount();
		this.notify(title,true);
		this.setDirty(true);
	}
};

TiddlyWiki.prototype.addTiddlerFields = function(title,fields)
{
	var tiddler = this.fetchTiddler(title);
	if(!tiddler)
		return;
	merge(tiddler.fields,fields);
	tiddler.changed();
	tiddler.incChangeCount();
	this.notify(title,true);
	this.setDirty(true);
};

// Store tiddler in TiddlyWiki instance
TiddlyWiki.prototype.saveTiddler = function(title,newTitle,newBody,modifier,modified,tags,fields,clearChangeCount,created,creator)
{
	var tiddler;
	if(title instanceof Tiddler) {
		tiddler = title;
		tiddler.fields = merge(merge({},tiddler.fields),config.defaultCustomFields,true);
		title = tiddler.title;
		newTitle = title;
	} else {
		tiddler = this.fetchTiddler(title);
		if(tiddler) {
			created = created || tiddler.created; // Preserve created date
			creator = creator || tiddler.creator;
			this.deleteTiddler(title);
		} else {
			created = created || modified;
			tiddler = new Tiddler();
		}
		fields = merge(merge({},fields),config.defaultCustomFields,true);
		tiddler.set(newTitle,newBody,modifier,modified,tags,created,fields,creator);
	}
	this.addTiddler(tiddler);
	if(clearChangeCount)
		tiddler.clearChangeCount();
	else
		tiddler.incChangeCount();
	if(title != newTitle)
		this.notify(title,true);
	this.notify(newTitle,true);
	this.setDirty(true);
	return tiddler;
};

TiddlyWiki.prototype.incChangeCount = function(title)
{
	var tiddler = this.fetchTiddler(title);
	if(tiddler)
		tiddler.incChangeCount();
};

TiddlyWiki.prototype.getLoader = function()
{
	if(!this.loader)
		this.loader = new TW21Loader();
	return this.loader;
};

TiddlyWiki.prototype.getSaver = function()
{
	if(!this.saver)
		this.saver = new TW21Saver();
	return this.saver;
};

// Return all tiddlers formatted as an HTML string
TiddlyWiki.prototype.allTiddlersAsHtml = function()
{
	return this.getSaver().externalize(store);
};

// Load contents of a TiddlyWiki from an HTML DIV
TiddlyWiki.prototype.loadFromDiv = function(src,idPrefix,noUpdate)
{
	this.idPrefix = idPrefix;
	var storeElem = (typeof src == "string") ? document.getElementById(src) : src;
	if(!storeElem)
		return;
	var tiddlers = this.getLoader().loadTiddlers(this,storeElem.childNodes);
	this.setDirty(false);
	if(!noUpdate) {
		var i;
		for(i = 0;i<tiddlers.length; i++)
			tiddlers[i].changed();
	}
	jQuery(document).trigger("loadTiddlers");
};

// Load contents of a TiddlyWiki from a string
// Returns null if there's an error
TiddlyWiki.prototype.importTiddlyWiki = function(text)
{
	var posDiv = locateStoreArea(text);
	if(!posDiv)
		return null;
	var content = "<" + "html><" + "body>" + text.substring(posDiv[0],posDiv[1] + endSaveArea.length) + "<" + "/body><" + "/html>";
	// Create the iframe
	var iframe = document.createElement("iframe");
	iframe.style.display = "none";
	document.body.appendChild(iframe);
	var doc = iframe.document;
	if(iframe.contentDocument)
		doc = iframe.contentDocument; // For NS6
	else if(iframe.contentWindow)
		doc = iframe.contentWindow.document; // For IE5.5 and IE6
	// Put the content in the iframe
	doc.open();
	doc.writeln(content);
	doc.close();
	// Load the content into a TiddlyWiki() object
	var storeArea = doc.getElementById("storeArea");
	this.loadFromDiv(storeArea,"store");
	// Get rid of the iframe
	iframe.parentNode.removeChild(iframe);
	return this;
};

TiddlyWiki.prototype.updateTiddlers = function()
{
	this.tiddlersUpdated = true;
	this.forEachTiddler(function(title,tiddler) {
		tiddler.changed();
	});
};

// Return an array of tiddlers matching a search regular expression
TiddlyWiki.prototype.search = function(searchRegExp,sortField,excludeTag,match)
{
	var candidates = this.reverseLookup("tags",excludeTag,!!match);
	var t,results = [];
	for(t=0; t<candidates.length; t++) {
		if((candidates[t].title.search(searchRegExp) != -1) || (candidates[t].text.search(searchRegExp) != -1))
			results.push(candidates[t]);
	}
	if(!sortField)
		sortField = "title";
	results.sort(function(a,b) {return a[sortField] < b[sortField] ? -1 : (a[sortField] == b[sortField] ? 0 : +1);});
	return results;
};

// Returns a list of all tags in use
//   excludeTag - if present, excludes tags that are themselves tagged with excludeTag
// Returns an array of arrays where [tag][0] is the name of the tag and [tag][1] is the number of occurances
TiddlyWiki.prototype.getTags = function(excludeTag)
{
	var results = [];
	this.forEachTiddler(function(title,tiddler) {
	    var g,c;
		for(g=0; g<tiddler.tags.length; g++) {
			var tag = tiddler.tags[g];
			var n = true;
			for(c=0; c<results.length; c++) {
				if(results[c][0] == tag) {
					n = false;
					results[c][1]++;
				}
			}
			if(n && excludeTag) {
				var t = this.fetchTiddler(tag);
				if(t && t.isTagged(excludeTag))
					n = false;
			}
			if(n)
				results.push([tag,1]);
		}
	});
	results.sort(function(a,b) {return a[0].toLowerCase() < b[0].toLowerCase() ? -1 : (a[0].toLowerCase() == b[0].toLowerCase() ? 0 : +1);});
	return results;
};

// Return an array of the tiddlers that are tagged with a given tag
TiddlyWiki.prototype.getTaggedTiddlers = function(tag,sortField)
{
	return this.reverseLookup("tags",tag,true,sortField);
};

TiddlyWiki.prototype.getValueTiddlers = function(field,value,sortField)
{
	return this.reverseLookup(field,value,true,sortField);
};

// Return an array of the tiddlers that link to a given tiddler
TiddlyWiki.prototype.getReferringTiddlers = function(title,unusedParameter,sortField)
{
	if(!this.tiddlersUpdated)
		this.updateTiddlers();
	return this.reverseLookup("links",title,true,sortField);
};

// Return an array of the tiddlers that do or do not have a specified entry in the specified storage array (ie, "links" or "tags")
// lookupMatch == true to match tiddlers, false to exclude tiddlers
TiddlyWiki.prototype.reverseLookup = function(lookupField,lookupValue,lookupMatch,sortField)
{
	var results = [];
	this.forEachTiddler(function(title,tiddler) {
		var f = !lookupMatch;
		var values;
		if(["links", "tags"].contains(lookupField)) {
			values = tiddler[lookupField];
		} else {
			var accessor = TiddlyWiki.standardFieldAccess[lookupField];
			if(accessor) {
				values = [ accessor.get(tiddler) ];
			} else {
				values = tiddler.fields[lookupField] ? [tiddler.fields[lookupField]] : [];
			}
		}
		var lookup;
		for(lookup=0; lookup<values.length; lookup++) {
			if(values[lookup] == lookupValue)
				f = lookupMatch;
		}
		if(f)
			results.push(tiddler);
	});
	if(!sortField)
		sortField = "title";
	return this.sortTiddlers(results,sortField);
};

// Return the tiddlers as a sorted array
TiddlyWiki.prototype.getTiddlers = function(field,excludeTag)
{
	var results = [];
	this.forEachTiddler(function(title,tiddler) {
		if(excludeTag == undefined || !tiddler.isTagged(excludeTag))
			results.push(tiddler);
	});
	if(field)
		results.sort(function(a,b) {return a[field] < b[field] ? -1 : (a[field] == b[field] ? 0 : +1);});
	return results;
};

// Return array of names of tiddlers that are referred to but not defined
TiddlyWiki.prototype.getMissingLinks = function()
{
	if(!this.tiddlersUpdated)
		this.updateTiddlers();
	var results = [];
	this.forEachTiddler(function (title,tiddler) {
		if(tiddler.isTagged("excludeMissing") || tiddler.isTagged("systemConfig"))
			return;
		var n;
		for(n=0; n<tiddler.links.length;n++) {
			var link = tiddler.links[n];
			if(this.getTiddlerText(link,null) == null && !this.isShadowTiddler(link) && !config.macros[link])
				results.pushUnique(link);
		}
	});
	results.sort();
	return results;
};

// Return an array of names of tiddlers that are defined but not referred to
TiddlyWiki.prototype.getOrphans = function()
{
	var results = [];
	this.forEachTiddler(function (title,tiddler) {
		if(this.getReferringTiddlers(title).length == 0 && !tiddler.isTagged("excludeLists"))
			results.push(title);
	});
	results.sort();
	return results;
};

// Return an array of names of all the shadow tiddlers
TiddlyWiki.prototype.getShadowed = function()
{
	var t,results = [];
	for(t in config.shadowTiddlers) {
		if(this.isShadowTiddler(t))
			results.push(t);
	}
	results.sort();
	return results;
};

// Return an array of tiddlers that have been touched since they were downloaded or created
TiddlyWiki.prototype.getTouched = function()
{
	var results = [];
	this.forEachTiddler(function(title,tiddler) {
		if(tiddler.isTouched())
			results.push(tiddler);
		});
	results.sort();
	return results;
};

// Resolves a Tiddler reference or tiddler title into a Tiddler object, or null if it doesn't exist
TiddlyWiki.prototype.resolveTiddler = function(tiddler)
{
	var t = (typeof tiddler == "string") ? this.getTiddler(tiddler) : tiddler;
	return t instanceof Tiddler ? t : null;
};

// Sort a list of tiddlers
TiddlyWiki.prototype.sortTiddlers = function(tiddlers,field)
{
	var asc = +1;
	switch(field.substr(0,1)) {
	case "-":
		asc = -1;
		field = field.substr(1);
		break;
	case "+":
		field = field.substr(1);
		break;
	}
	if(TiddlyWiki.standardFieldAccess[field]) {
		if(field=="title") {
			tiddlers.sort(function(a,b) {return a[field].toLowerCase() < b[field].toLowerCase() ? -asc : (a[field].toLowerCase() == b[field].toLowerCase() ? 0 : asc);});
		} else {
			tiddlers.sort(function(a,b) {return a[field] < b[field] ? -asc : (a[field] == b[field] ? 0 : asc);});
		}
	} else {
		tiddlers.sort(function(a,b) {return a.fields[field] < b.fields[field] ? -asc : (a.fields[field] == b.fields[field] ? 0 : +asc);});
	}
	return tiddlers;
};

//--
//-- Filter a list of tiddlers
//--

config.filters = {
	tiddler: function(results,match) {
		var title = match[1]||match[4];
		var tiddler = this.fetchTiddler(title);
		if(tiddler) {
			results.pushUnique(tiddler);
		} else if(this.isShadowTiddler(title)) {
			tiddler = new Tiddler();
			tiddler.set(title,this.getTiddlerText(title));
			results.pushUnique(tiddler);
		} else {
			results.pushUnique(new Tiddler(title));
		}
		return results;
	},
	tag: function(results,match) {
		var m,matched = this.getTaggedTiddlers(match[3]);
		for(m=0; m<matched.length; m++) {
			results.pushUnique(matched[m]);
		}
		return results;
	},
	sort: function(results,match) {
		return this.sortTiddlers(results,match[3]);
	},
	limit: function(results,match) {
		return results.slice(0,parseInt(match[3],10));
	},
	field: function(results,match) {
		var m,matched = this.getValueTiddlers(match[2],match[3]);
		for (m = 0; m < matched.length; m++) {
			results.pushUnique(matched[m]);
		}
		return results;
	}
};

// Filter a list of tiddlers
TiddlyWiki.prototype.filterTiddlers = function(filter)
{
	var re = /([^\s\[\]]+)|(?:\[([ \w\.\-]+)\[([^\]]+)\]\])|(?:\[\[([^\]]+)\]\])/mg;

	var results = [];
	if(filter) {
		var match = re.exec(filter);
		while(match) {
			var handler = (match[1]||match[4])?'tiddler':config.filters[match[2]]?match[2]:'field';
			results = config.filters[handler].call(this,results,match);
			match = re.exec(filter);
		}
	}
	return results;
};
// Returns true if path is a valid field name (path),
// i.e. a sequence of identifiers, separated by "."
TiddlyWiki.isValidFieldName = function(name)
{
	var match = /[a-zA-Z_]\w*(\.[a-zA-Z_]\w*)*/.exec(name);
	return match && (match[0] == name);
};

// Throws an exception when name is not a valid field name.
TiddlyWiki.checkFieldName = function(name)
{
	if(!TiddlyWiki.isValidFieldName(name))
		throw config.messages.invalidFieldName.format([name]);
};

function StringFieldAccess(n,readOnly)
{
	this.set = readOnly ?
			function(t,v) {if(v != t[n]) throw config.messages.fieldCannotBeChanged.format([n]);} :
			function(t,v) {if(v != t[n]) {t[n] = v; return true;}};
	this.get = function(t) {return t[n];};
}

function DateFieldAccess(n)
{
	this.set = function(t,v) {
		var d = v instanceof Date ? v : Date.convertFromYYYYMMDDHHMM(v);
		if(d != t[n]) {
			t[n] = d; return true;
		}
	};
	this.get = function(t) {return t[n].convertToYYYYMMDDHHMM();};
}

function LinksFieldAccess(n)
{
	this.set = function(t,v) {
		var s = (typeof v == "string") ? v.readBracketedList() : v;
		if(s.toString() != t[n].toString()) {
			t[n] = s; return true;
		}
	};
	this.get = function(t) {return String.encodeTiddlyLinkList(t[n]);};
}

TiddlyWiki.standardFieldAccess = {
	// The set functions return true when setting the data has changed the value.
	"title":    new StringFieldAccess("title",true),
	// Handle the "tiddler" field name as the title
	"tiddler":  new StringFieldAccess("title",true),
	"text":     new StringFieldAccess("text"),
	"modifier": new StringFieldAccess("modifier"),
	"modified": new DateFieldAccess("modified"),
	"creator":  new StringFieldAccess("creator"),
	"created":  new DateFieldAccess("created"),
	"tags":     new LinksFieldAccess("tags")
};

TiddlyWiki.isStandardField = function(name)
{
	return TiddlyWiki.standardFieldAccess[name] != undefined;
};

// Sets the value of the given field of the tiddler to the value.
// Setting an ExtendedField's value to null or undefined removes the field.
// Setting a namespace to undefined removes all fields of that namespace.
// The fieldName is case-insensitive.
// All values will be converted to a string value.
TiddlyWiki.prototype.setValue = function(tiddler,fieldName,value)
{
	TiddlyWiki.checkFieldName(fieldName);
	var t = this.resolveTiddler(tiddler);
	if(!t)
		return;
	fieldName = fieldName.toLowerCase();
	var isRemove = (value === undefined) || (value === null);
	var accessor = TiddlyWiki.standardFieldAccess[fieldName];
	if(accessor) {
		if(isRemove)
			// don't remove StandardFields
			return;
		var h = TiddlyWiki.standardFieldAccess[fieldName];
		if(!h.set(t,value))
			return;
	} else {
		var oldValue = t.fields[fieldName];
		if(isRemove) {
			if(oldValue !== undefined) {
				// deletes a single field
				delete t.fields[fieldName];
			} else {
				// no concrete value is defined for the fieldName
				// so we guess this is a namespace path.
				// delete all fields in a namespace
				var re = new RegExp("^"+fieldName+"\\.");
				var dirty = false;
				var n;
				for(n in t.fields) {
					if(n.match(re)) {
						delete t.fields[n];
						dirty = true;
					}
				}
				if(!dirty)
					return;
			}
		} else {
			// the "normal" set case. value is defined (not null/undefined)
			// For convenience provide a nicer conversion Date->String
			value = value instanceof Date ? value.convertToYYYYMMDDHHMMSSMMM() : String(value);
			if(oldValue == value)
				return;
			t.fields[fieldName] = value;
		}
	}
	// When we are here the tiddler/store really was changed.
	this.notify(t.title,true);
	if(!fieldName.match(/^temp\./))
		this.setDirty(true);
};

// Returns the value of the given field of the tiddler.
// The fieldName is case-insensitive.
// Will only return String values (or undefined).
TiddlyWiki.prototype.getValue = function(tiddler,fieldName)
{
	var t = this.resolveTiddler(tiddler);
	if(!t)
		return undefined;
	if(fieldName.indexOf(config.textPrimitives.sectionSeparator) === 0 || fieldName.indexOf(config.textPrimitives.sliceSeparator) === 0) {
		var sliceType = fieldName.substr(0, 2);
		var sliceName = fieldName.substring(2);
		return store.getTiddlerText("%0%1%2".format(t.title,sliceType,sliceName));
	} else {
		fieldName = fieldName.toLowerCase();
		var accessor = TiddlyWiki.standardFieldAccess[fieldName];
		if(accessor) {
			return accessor.get(t);
		}
	}
	return t.fields[fieldName];
};

// Calls the callback function for every field in the tiddler.
// When callback function returns a non-false value the iteration stops
// and that value is returned.
// The order of the fields is not defined.
// @param callback a function(tiddler,fieldName,value).
TiddlyWiki.prototype.forEachField = function(tiddler,callback,onlyExtendedFields)
{
	var t = this.resolveTiddler(tiddler);
	if(!t)
		return undefined;
	var n,result;
	for(n in t.fields) {
		result = callback(t,n,t.fields[n]);
		if(result)
			return result;
		}
	if(onlyExtendedFields)
		return undefined;
	for(n in TiddlyWiki.standardFieldAccess) {
		if(n != "tiddler") {
			// even though the "title" field can also be referenced through the name "tiddler"
			// we only visit this field once.
			result = callback(t,n,TiddlyWiki.standardFieldAccess[n].get(t));
			if(result)
				return result;
		}
	}
	return undefined;
};

//--
//-- Story functions
//--

function Story(containerId,idPrefix)
{
	this.container = containerId;
	this.idPrefix = idPrefix;
	this.highlightRegExp = null;
	this.tiddlerId = function(title) {
		title = title.replace(/_/g, "__").replace(/ /g, "_");
		var id = this.idPrefix + title;
		return id==this.container ? this.idPrefix + "_" + title : id;
	};
	this.containerId = function() {
		return this.container;
	};
}

Story.prototype.getTiddler = function(title)
{
	return document.getElementById(this.tiddlerId(title));
};

Story.prototype.getContainer = function()
{
	return document.getElementById(this.containerId());
};

Story.prototype.forEachTiddler = function(fn)
{
	var place = this.getContainer();
	if(!place)
		return;
	var e = place.firstChild;
	while(e) {
		var n = e.nextSibling;
		var title = e.getAttribute("tiddler");
		if(title) {
			fn.call(this,title,e);
		}
		e = n;
	}
};

Story.prototype.displayDefaultTiddlers = function()
{
	this.displayTiddlers(null,store.filterTiddlers(store.getTiddlerText("DefaultTiddlers")));
};

Story.prototype.displayTiddlers = function(srcElement,titles,template,animate,unused,customFields,toggle)
{
	var t;
	for(t = titles.length-1;t>=0;t--)
		this.displayTiddler(srcElement,titles[t],template,animate,unused,customFields);
};

Story.prototype.displayTiddler = function(srcElement,tiddler,template,animate,unused,customFields,toggle,animationSrc)
{
	var title = (tiddler instanceof Tiddler) ? tiddler.title : tiddler;
	var tiddlerElem = this.getTiddler(title);
	if(tiddlerElem) {
		if(toggle) {
			if(tiddlerElem.getAttribute("dirty") != "true")
				this.closeTiddler(title,true);
		} else {
			this.refreshTiddler(title,template,false,customFields);
		}
	} else {
		var place = this.getContainer();
		var before = this.positionTiddler(srcElement);
		tiddlerElem = this.createTiddler(place,before,title,template,customFields);
	}
	if(animationSrc && typeof animationSrc !== "string") {
		srcElement = animationSrc;
	}
	if(srcElement && typeof srcElement !== "string") {
		if(config.options.chkAnimate && (animate == undefined || animate == true) && anim && typeof Zoomer == "function" && typeof Scroller == "function")
			anim.startAnimating(new Zoomer(title,srcElement,tiddlerElem),new Scroller(tiddlerElem));
		else
			window.scrollTo(0,ensureVisible(tiddlerElem));
	}
	return tiddlerElem;
};

Story.prototype.positionTiddler = function(srcElement)
{
	var place = this.getContainer();
	var before = null;
	if(typeof srcElement == "string") {
		switch(srcElement) {
		case "top":
			before = place.firstChild;
			break;
		case "bottom":
			before = null;
			break;
		}
	} else {
		var after = this.findContainingTiddler(srcElement);
		if(after == null) {
			before = place.firstChild;
		} else if(after.nextSibling) {
			before = after.nextSibling;
			if(before.nodeType != 1)
				before = null;
		}
	}
	return before;
};

Story.prototype.createTiddler = function(place,before,title,template,customFields)
{
	var tiddlerElem = createTiddlyElement(null,"div",this.tiddlerId(title),"tiddler");
	tiddlerElem.setAttribute("refresh","tiddler");
	if(customFields)
		tiddlerElem.setAttribute("tiddlyFields",customFields);
	place.insertBefore(tiddlerElem,before);
	var defaultText = null;
	if(!store.tiddlerExists(title) && !store.isShadowTiddler(title))
		defaultText = this.loadMissingTiddler(title,customFields);
	this.refreshTiddler(title,template,false,customFields,defaultText);
	return tiddlerElem;
};

Story.prototype.loadMissingTiddler = function(title,fields,callback)
{
	var getTiddlerCallback = function(context)
	{
		if(context.status) {
			var t = context.tiddler;
			if(!t.created)
				t.created = new Date();
			if(!t.modified)
				t.modified = t.created;
			var dirty = store.isDirty();
			context.tiddler = store.saveTiddler(t.title,t.title,t.text,t.modifier,t.modified,t.tags,t.fields,true,t.created,t.creator);
			if(!window.allowSave())
				store.setDirty(dirty);
			autoSaveChanges();
		} else {
			story.refreshTiddler(context.title,null,true);
		}
		context.adaptor.close();
		if(callback) {
			callback(context);
		}
	};
	var tiddler = new Tiddler(title);
	tiddler.fields = typeof fields == "string" ? fields.decodeHashMap() : fields||{};
	var context = {serverType:tiddler.getServerType()};
	if(!context.serverType)
		return "";
	context.host = tiddler.fields['server.host'];
	context.workspace = tiddler.fields['server.workspace'];
	var adaptor = new config.adaptors[context.serverType]();
	adaptor.getTiddler(title,context,null,getTiddlerCallback);
	return config.messages.loadingMissingTiddler.format([title,context.serverType,context.host,context.workspace]);
};

Story.prototype.chooseTemplateForTiddler = function(title,template)
{
	if(!template)
		template = DEFAULT_VIEW_TEMPLATE;
	if(template == DEFAULT_VIEW_TEMPLATE || template == DEFAULT_EDIT_TEMPLATE)
		template = config.tiddlerTemplates[template];
	return template;
};

Story.prototype.getTemplateForTiddler = function(title,template,tiddler)
{
	return store.getRecursiveTiddlerText(template,null,10);
};

Story.prototype.refreshTiddler = function(title,template,force,customFields,defaultText)
{
	var tiddlerElem = this.getTiddler(title);
	if(tiddlerElem) {
		if(tiddlerElem.getAttribute("dirty") == "true" && !force)
			return tiddlerElem;
		template = this.chooseTemplateForTiddler(title,template);
		var currTemplate = tiddlerElem.getAttribute("template");
		if((template != currTemplate) || force) {
			var tiddler = store.getTiddler(title);
			if(!tiddler) {
				tiddler = new Tiddler();
				if(store.isShadowTiddler(title)) {
					var tags = [];
					tiddler.set(title,store.getTiddlerText(title),config.views.wikified.shadowModifier,version.date,tags,version.date);
				} else {
					var text = template=="EditTemplate" ?
								config.views.editor.defaultText.format([title]) :
								config.views.wikified.defaultText.format([title]);
					text = defaultText || text;
					var fields = customFields ? customFields.decodeHashMap() : null;
					tiddler.set(title,text,config.views.wikified.defaultModifier,version.date,[],version.date,fields);
				}
			}
			tiddlerElem.setAttribute("tags",tiddler.tags.join(" "));
			tiddlerElem.setAttribute("tiddler",title);
			tiddlerElem.setAttribute("template",template);
			tiddlerElem.onmouseover = this.onTiddlerMouseOver;
			tiddlerElem.onmouseout = this.onTiddlerMouseOut;
			tiddlerElem.ondblclick = this.onTiddlerDblClick;
			tiddlerElem[window.event?"onkeydown":"onkeypress"] = this.onTiddlerKeyPress;
			tiddlerElem.innerHTML = this.getTemplateForTiddler(title,template,tiddler);
			applyHtmlMacros(tiddlerElem,tiddler);
			if(store.getTaggedTiddlers(title).length > 0)
				jQuery(tiddlerElem).addClass("isTag");
			else
				jQuery(tiddlerElem).removeClass("isTag");
			if(store.tiddlerExists(title)) {
				jQuery(tiddlerElem).removeClass("shadow");
				jQuery(tiddlerElem).removeClass("missing");
			} else {
				jQuery(tiddlerElem).addClass(store.isShadowTiddler(title) ? "shadow" : "missing");
			}
			if(customFields)
				this.addCustomFields(tiddlerElem,customFields);
		}
	}
	return tiddlerElem;
};

Story.prototype.addCustomFields = function(place,customFields)
{
	var fields = customFields.decodeHashMap();
	var w = createTiddlyElement(place,"div",null,"customFields");
	w.style.display = "none";
	var t;
	for(t in fields) {
		var e = document.createElement("input");
		e.setAttribute("type","text");
		e.setAttribute("value",fields[t]);
		w.appendChild(e);
		e.setAttribute("edit",t);
	}
};

Story.prototype.refreshAllTiddlers = function(force)
{
	var e = this.getContainer().firstChild;
	while(e) {
		var template = e.getAttribute("template");
		if(template && e.getAttribute("dirty") != "true") {
			this.refreshTiddler(e.getAttribute("tiddler"),force ? null : template,true);
		}
		e = e.nextSibling;
	}
};

Story.prototype.onTiddlerMouseOver = function(e)
{
	jQuery(this).addClass("selected");
};

Story.prototype.onTiddlerMouseOut = function(e)
{
	jQuery(this).removeClass("selected");
};

Story.prototype.onTiddlerDblClick = function(ev)
{
	var e = ev || window.event;
	var target = resolveTarget(e);
	if(target && target.nodeName.toLowerCase() != "input" && target.nodeName.toLowerCase() != "textarea") {
		if(document.selection && document.selection.empty)
			document.selection.empty();
		config.macros.toolbar.invokeCommand(this,"defaultCommand",e);
		e.cancelBubble = true;
		if(e.stopPropagation) e.stopPropagation();
		return true;
	}
	return false;
};

Story.prototype.onTiddlerKeyPress = function(ev)
{
	var e = ev || window.event;
	clearMessage();
	var consume = false;
	var title = this.getAttribute("tiddler");
	var target = resolveTarget(e);
	switch(e.keyCode) {
	case 9: // Tab
		var ed = story.getTiddlerField(title,"text");
		if(target.tagName.toLowerCase() == "input" && ed.value==config.views.editor.defaultText.format([title])) {
			// moving from input field and editor still contains default text, so select it
			ed.focus();
			ed.select();
			consume = true;
		}
		if(config.options.chkInsertTabs && target.tagName.toLowerCase() == "textarea") {
			replaceSelection(target,String.fromCharCode(9));
			consume = true;
		}
		if(config.isOpera) {
			target.onblur = function() {
				this.focus();
				this.onblur = null;
			};
		}
		break;
	case 13: // Ctrl-Enter
	case 10: // Ctrl-Enter on IE PC
	case 77: // Ctrl-Enter is "M" on some platforms
		if(e.ctrlKey) {
			blurElement(this);
			config.macros.toolbar.invokeCommand(this,"defaultCommand",e);
			consume = true;
		}
		break;
	case 27: // Escape
		blurElement(this);
		config.macros.toolbar.invokeCommand(this,"cancelCommand",e);
		consume = true;
		break;
	}
	e.cancelBubble = consume;
	if(consume) {
		if(e.stopPropagation) e.stopPropagation(); // Stop Propagation
		e.returnValue = true; // Cancel The Event in IE
		if(e.preventDefault ) e.preventDefault(); // Cancel The Event in Moz
	}
	return !consume;
};

Story.prototype.getTiddlerField = function(title,field)
{
	var tiddlerElem = this.getTiddler(title);
	var e = null;
	if(tiddlerElem) {
		var t,children = tiddlerElem.getElementsByTagName("*");
		for(t=0; t<children.length; t++) {
			var c = children[t];
			if(c.tagName.toLowerCase() == "input" || c.tagName.toLowerCase() == "textarea") {
				if(!e)
					e = c;
				if(c.getAttribute("edit") == field)
					e = c;
			}
		}
	}
	return e;
};

Story.prototype.focusTiddler = function(title,field)
{
	var e = this.getTiddlerField(title,field);
	if(e) {
		e.focus();
		e.select();
	}
};

Story.prototype.blurTiddler = function(title)
{
	var tiddlerElem = this.getTiddler(title);
	if(tiddlerElem && tiddlerElem.focus && tiddlerElem.blur) {
		tiddlerElem.focus();
		tiddlerElem.blur();
	}
};

Story.prototype.setTiddlerField = function(title,tag,mode,field)
{
	var c = this.getTiddlerField(title,field);
	var tags = c.value.readBracketedList();
	tags.setItem(tag,mode);
	c.value = String.encodeTiddlyLinkList(tags);
};

Story.prototype.setTiddlerTag = function(title,tag,mode)
{
	this.setTiddlerField(title,tag,mode,"tags");
};

Story.prototype.closeTiddler = function(title,animate,unused)
{
	var tiddlerElem = this.getTiddler(title);
	if(tiddlerElem) {
		clearMessage();
		this.scrubTiddler(tiddlerElem);
		if(config.options.chkAnimate && animate && anim && typeof Slider == "function")
			anim.startAnimating(new Slider(tiddlerElem,false,null,"all"));
		else {
			jQuery(tiddlerElem).remove();
		}
	}
};

Story.prototype.scrubTiddler = function(tiddlerElem)
{
	tiddlerElem.id = null;
};

Story.prototype.setDirty = function(title,dirty)
{
	var tiddlerElem = this.getTiddler(title);
	if(tiddlerElem)
		tiddlerElem.setAttribute("dirty",dirty ? "true" : "false");
};

Story.prototype.isDirty = function(title)
{
	var tiddlerElem = this.getTiddler(title);
	if(tiddlerElem)
		return tiddlerElem.getAttribute("dirty") == "true";
	return null;
};

Story.prototype.areAnyDirty = function()
{
	var r = false;
	this.forEachTiddler(function(title,element) {
		if(this.isDirty(title))
			r = true;
	});
	return r;
};

Story.prototype.closeAllTiddlers = function(exclude)
{
	clearMessage();
	this.forEachTiddler(function(title,element) {
		if((title != exclude) && element.getAttribute("dirty") != "true")
			this.closeTiddler(title);
	});
	window.scrollTo(0,ensureVisible(this.container));
};

Story.prototype.isEmpty = function()
{
	var place = this.getContainer();
	return place && place.firstChild == null;
};

Story.prototype.search = function(text,useCaseSensitive,useRegExp)
{
	this.closeAllTiddlers();
	highlightHack = new RegExp(useRegExp ? text : text.escapeRegExp(),useCaseSensitive ? "mg" : "img");
	var matches = store.search(highlightHack,"title","excludeSearch");
	this.displayTiddlers(null,matches);
	highlightHack = null;
	var q = useRegExp ? "/" : "'";
	if(matches.length > 0)
		displayMessage(config.macros.search.successMsg.format([matches.length.toString(),q + text + q]));
	else
		displayMessage(config.macros.search.failureMsg.format([q + text + q]));
};

Story.prototype.findContainingTiddler = function(e)
{
	while(e && !jQuery(e).hasClass("tiddler")) {
		e = jQuery(e).hasClass("popup") && Popup.stack[0] ? Popup.stack[0].root : e.parentNode;
	}
	return e;
};

Story.prototype.gatherSaveFields = function(e,fields)
{
	if(e && e.getAttribute) {
		var f = e.getAttribute("edit");
		if(f)
			fields[f] = e.value.replace(/\r/mg,"");
		if(e.hasChildNodes()) {
			var t,c = e.childNodes;
			for(t=0; t<c.length; t++)
				this.gatherSaveFields(c[t],fields);
		}
	}
};

Story.prototype.hasChanges = function(title)
{
	var e = this.getTiddler(title);
	if(e) {
		var fields = {};
		this.gatherSaveFields(e,fields);
		if(store.fetchTiddler(title)) {
		    var n;
			for(n in fields) {
				if(store.getValue(title,n) != fields[n]) //# tiddler changed
					return true;
			}
		} else {
			if(store.isShadowTiddler(title) && store.getShadowTiddlerText(title) == fields.text) { //# not checking for title or tags
				return false;
			} else { //# changed shadow or new tiddler
				return true;
			}
		}
	}
	return false;
};

Story.prototype.saveTiddler = function(title,minorUpdate)
{
	var tiddlerElem = this.getTiddler(title);
	if(tiddlerElem) {
		var fields = {};
		this.gatherSaveFields(tiddlerElem,fields);
		var newTitle = fields.title || title;
		if(!store.tiddlerExists(newTitle)) {
			newTitle = newTitle.trim();
			var creator = config.options.txtUserName;
		}
		if(store.tiddlerExists(newTitle) && newTitle != title) {
			if(!confirm(config.messages.overwriteWarning.format([newTitle.toString()])))
				return null;
				title = newTitle;
		}
		if(newTitle != title)
			this.closeTiddler(newTitle,false);
		tiddlerElem.id = this.tiddlerId(newTitle);
		tiddlerElem.setAttribute("tiddler",newTitle);
		tiddlerElem.setAttribute("template",DEFAULT_VIEW_TEMPLATE);
		tiddlerElem.setAttribute("dirty","false");
		if(config.options.chkForceMinorUpdate)
			minorUpdate = !minorUpdate;
		if(!store.tiddlerExists(newTitle))
			minorUpdate = false;
		var newDate = new Date();
		if(store.tiddlerExists(title)) {
			var t = store.fetchTiddler(title);
			var extendedFields = t.fields;
			creator = t.creator;
		} else {
			extendedFields = merge({},config.defaultCustomFields);
		}
		var n;
		for(n in fields) {
			if(!TiddlyWiki.isStandardField(n))
				extendedFields[n] = fields[n];
		}
		var tiddler = store.saveTiddler(title,newTitle,fields.text,minorUpdate ? undefined : config.options.txtUserName,minorUpdate ? undefined : newDate,fields.tags,extendedFields,null,null,creator);
		autoSaveChanges(null,[tiddler]);
		return newTitle;
	}
	return null;
};

Story.prototype.permaView = function()
{
	var links = [];
	this.forEachTiddler(function(title,element) {
		links.push(String.encodeTiddlyLink(title));
	});
	var t = encodeURIComponent(links.join(" "));
	if(t == "")
		t = "#";
	if(window.location.hash != t)
		window.location.hash = t;
};

Story.prototype.switchTheme = function(theme)
{
	if(safeMode)
		return;

	var getSlice = function(theme,slice) {
		var r;
		if(readOnly)
			r = store.getTiddlerSlice(theme,slice+"ReadOnly") || store.getTiddlerSlice(theme,"Web"+slice);
		r = r || store.getTiddlerSlice(theme,slice);
		if(r && r.indexOf(config.textPrimitives.sectionSeparator)==0)
			r = theme + r;
		return store.isAvailable(r) ? r : slice;
	};

	var replaceNotification = function(i,name,theme,slice) {
		var newName = getSlice(theme,slice);
		if(name!=newName && store.namedNotifications[i].name==name) {
			store.namedNotifications[i].name = newName;
			return newName;
		}
		return name;
	};

	var pt = config.refresherData.pageTemplate;
	var vi = DEFAULT_VIEW_TEMPLATE;
	var vt = config.tiddlerTemplates[vi];
	var ei = DEFAULT_EDIT_TEMPLATE;
	var et = config.tiddlerTemplates[ei];

	var i;
	for(i=0; i<config.notifyTiddlers.length; i++) {
		var name = config.notifyTiddlers[i].name;
		switch(name) {
		case "PageTemplate":
			config.refresherData.pageTemplate = replaceNotification(i,config.refresherData.pageTemplate,theme,name);
			break;
		case "StyleSheet":
			removeStyleSheet(config.refresherData.styleSheet);
			config.refresherData.styleSheet = replaceNotification(i,config.refresherData.styleSheet,theme,name);
			break;
		case "ColorPalette":
			config.refresherData.colorPalette = replaceNotification(i,config.refresherData.colorPalette,theme,name);
			break;
		default:
			break;
		}
	}
	config.tiddlerTemplates[vi] = getSlice(theme,"ViewTemplate");
	config.tiddlerTemplates[ei] = getSlice(theme,"EditTemplate");
	if(!startingUp) {
		if(config.refresherData.pageTemplate!=pt || config.tiddlerTemplates[vi]!=vt || config.tiddlerTemplates[ei]!=et) {
			refreshAll();
			this.refreshAllTiddlers(true);
		} else {
			setStylesheet(store.getRecursiveTiddlerText(config.refresherData.styleSheet,"",10),config.refreshers.styleSheet);
		}
		config.options.txtTheme = theme;
		saveOption("txtTheme");
	}
};

//--
//-- Backstage
//--
// Backstage tasks
config.tasks.save.action = saveChanges;

var backstage = {
	area: null,
	toolbar: null,
	button: null,
	showButton: null,
	hideButton: null,
	cloak: null,
	panel: null,
	panelBody: null,
	panelFooter: null,
	currTabName: null,
	currTabElem: null,
	content: null,

	init: function() {
		var cmb = config.messages.backstage;
		this.area = document.getElementById("backstageArea");
		this.toolbar = jQuery("#backstageToolbar").empty()[0];
		this.button = jQuery("#backstageButton").empty()[0];
		this.button.style.display = "block";
		var t = cmb.open.text + " " + glyph("bentArrowLeft");
		this.showButton = createTiddlyButton(this.button,t,cmb.open.tooltip,
						function(e) {backstage.show(); return false;},null,"backstageShow");
		t = glyph("bentArrowRight") + " " + cmb.close.text;
		this.hideButton = createTiddlyButton(this.button,t,cmb.close.tooltip,
						function(e) {backstage.hide(); return false;},null,"backstageHide");
		this.cloak = document.getElementById("backstageCloak");
		this.panel = document.getElementById("backstagePanel");
		this.panelFooter = createTiddlyElement(this.panel,"div",null,"backstagePanelFooter");
		this.panelBody = createTiddlyElement(this.panel,"div",null,"backstagePanelBody");
		this.cloak.onmousedown = function(e) {backstage.switchTab(null);};
		createTiddlyText(this.toolbar,cmb.prompt);
		for(t=0; t<config.backstageTasks.length; t++) {
			var taskName = config.backstageTasks[t];
			var task = config.tasks[taskName];
			var handler = task.action ? this.onClickCommand : this.onClickTab;
			var text = task.text + (task.action ? "" : glyph("downTriangle"));
			var btn = createTiddlyButton(this.toolbar,text,task.tooltip,handler,"backstageTab");
			jQuery(btn).addClass(task.action ? "backstageAction" : "backstageTask");
			btn.setAttribute("task", taskName);
			}
		this.content = document.getElementById("contentWrapper");
		if(config.options.chkBackstage)
			this.show();
		else
			this.hide();
	},

	isVisible: function() {
		return this.area ? this.area.style.display == "block" : false;
	},

	show: function() {
		this.area.style.display = "block";
		if(anim && config.options.chkAnimate) {
			backstage.toolbar.style.left = findWindowWidth() + "px";
			var p = [{style: "left", start: findWindowWidth(), end: 0, template: "%0px"}];
			anim.startAnimating(new Morpher(backstage.toolbar,config.animDuration,p));
		} else {
			backstage.area.style.left = "0px";
		}
		jQuery(this.showButton).hide();
		jQuery(this.hideButton).show();
		config.options.chkBackstage = true;
		saveOption("chkBackstage");
		jQuery(this.content).addClass("backstageVisible");
	},

	hide: function() {
		if(this.currTabElem) {
			this.switchTab(null);
		} else {
			backstage.toolbar.style.left = "0px";
			if(anim && config.options.chkAnimate) {
				var p = [{style: "left", start: 0, end: findWindowWidth(), template: "%0px"}];
				var c = function(element,properties) {backstage.area.style.display = "none";};
				anim.startAnimating(new Morpher(backstage.toolbar,config.animDuration,p,c));
			} else {
				this.area.style.display = "none";
			}
			this.showButton.style.display = "block";
			this.hideButton.style.display = "none";
			config.options.chkBackstage = false;
			saveOption("chkBackstage");
			jQuery(this.content).removeClass("backstageVisible");
		}
	},

	onClickCommand: function(e) {
		var task = config.tasks[this.getAttribute("task")];
		if(task.action) {
			backstage.switchTab(null);
			task.action();
		}
		return false;
	},

	onClickTab: function(e) {
		backstage.switchTab(this.getAttribute("task"));
		return false;
	},

	// Switch to a given tab, or none if null is passed
	switchTab: function(tabName) {
		var tabElem = null;
		var e = this.toolbar.firstChild;
		while(e) {
			if(e.getAttribute && e.getAttribute("task") == tabName)
				tabElem = e;
			e = e.nextSibling;
		}
		if(tabName == backstage.currTabName) {
			backstage.hidePanel();
			return;
		}
		if(backstage.currTabElem) {
			jQuery(this.currTabElem).removeClass("backstageSelTab");
		}
		if(tabElem && tabName) {
			backstage.preparePanel();
			jQuery(tabElem).addClass("backstageSelTab");
			var task = config.tasks[tabName];
			wikify(task.content,backstage.panelBody,null,null);
			backstage.showPanel();
		} else if(backstage.currTabElem) {
			backstage.hidePanel();
		}
		backstage.currTabName = tabName;
		backstage.currTabElem = tabElem;
	},

	isPanelVisible: function() {
		return backstage.panel ? backstage.panel.style.display == "block" : false;
	},

	preparePanel: function() {
		backstage.cloak.style.height = findDocHeight() + "px";
		backstage.cloak.style.display = "block";
		jQuery(backstage.panelBody).empty();
		return backstage.panelBody;
	},

	showPanel: function() {
		backstage.panel.style.display = "block";
		if(anim && config.options.chkAnimate) {
			backstage.panel.style.top = (-backstage.panel.offsetHeight) + "px";
			var p = [{style: "top", start: -backstage.panel.offsetHeight, end: 0, template: "%0px"}];
			anim.startAnimating(new Morpher(backstage.panel,config.animDuration,p),new Scroller(backstage.panel,false));
		} else {
			backstage.panel.style.top = "0px";
		}
		return backstage.panelBody;
	},

	hidePanel: function() {
		if(backstage.currTabElem)
			jQuery(backstage.currTabElem).removeClass("backstageSelTab");
		backstage.currTabElem = null;
		backstage.currTabName = null;
		if(anim && config.options.chkAnimate) {
			var p = [
				{style: "top", start: 0, end: -(backstage.panel.offsetHeight), template: "%0px"},
				{style: "display", atEnd: "none"}
			];
			var c = function(element,properties) {backstage.cloak.style.display = "none";};
			anim.startAnimating(new Morpher(backstage.panel,config.animDuration,p,c));
		} else {
			jQuery([backstage.panel,backstage.cloak]).hide();
		}
	}
};

config.macros.backstage = {};

config.macros.backstage.handler = function(place,macroName,params)
{
	var backstageTask = config.tasks[params[0]];
	if(backstageTask)
		createTiddlyButton(place,backstageTask.text,backstageTask.tooltip,function(e) {backstage.switchTab(params[0]); return false;});
};

//--
//-- ImportTiddlers macro
//--

config.macros.importTiddlers.handler = function(place,macroName,params,wikifier,paramString,tiddler)
{
	if(readOnly) {
		createTiddlyElement(place,"div",null,"marked",this.readOnlyWarning);
		return;
	}
	var w = new Wizard();
	w.createWizard(place,this.wizardTitle);
	this.restart(w);
};

config.macros.importTiddlers.onCancel = function(e)
{
	var wizard = new Wizard(this);
	wizard.clear();
	config.macros.importTiddlers.restart(wizard);
	return false;
};

config.macros.importTiddlers.onClose = function(e)
{
	backstage.hidePanel();
	return false;
};

config.macros.importTiddlers.restart = function(wizard)
{
	var me = config.macros.importTiddlers;
	wizard.addStep(this.step1Title,this.step1Html);
	var t,s = wizard.getElement("selTypes");
	for(t in config.adaptors) {
		var e = createTiddlyElement(s,"option",null,null,config.adaptors[t].serverLabel || t);
		e.value = t;
	}
	if(config.defaultAdaptor)
		s.value = config.defaultAdaptor;
	s = wizard.getElement("selFeeds");
	var feeds = this.getFeeds();
	for(t in feeds) {
		e = createTiddlyElement(s,"option",null,null,t);
		e.value = t;
	}
	wizard.setValue("feeds",feeds);
	s.onchange = me.onFeedChange;
	var fileInput = wizard.getElement("txtBrowse");
	fileInput.onchange = me.onBrowseChange;
	fileInput.onkeyup = me.onBrowseChange;
	wizard.setButtons([{caption: this.openLabel, tooltip: this.openPrompt, onClick: me.onOpen}]);
	wizard.formElem.action = "javascript:;";
	wizard.formElem.onsubmit = function() {
		if(!this.txtPath || this.txtPath.value.length) //# check for manually entered path in first step
			this.lastChild.firstChild.onclick();
	};
};

config.macros.importTiddlers.getFeeds = function()
{
	var feeds = {};
	var t,tagged = store.getTaggedTiddlers("systemServer","title");
	for(t=0; t<tagged.length; t++) {
		var title = tagged[t].title;
		var serverType = store.getTiddlerSlice(title,"Type");
		if(!serverType)
			serverType = "file";
		feeds[title] = {title: title,
						url: store.getTiddlerSlice(title,"URL"),
						workspace: store.getTiddlerSlice(title,"Workspace"),
						workspaceList: store.getTiddlerSlice(title,"WorkspaceList"),
						tiddlerFilter: store.getTiddlerSlice(title,"TiddlerFilter"),
						serverType: serverType,
						description: store.getTiddlerSlice(title,"Description")};
	}
	return feeds;
};

config.macros.importTiddlers.onFeedChange = function(e)
{
	var wizard = new Wizard(this);
	var selTypes = wizard.getElement("selTypes");
	var fileInput = wizard.getElement("txtPath");
	var feeds = wizard.getValue("feeds");
	var f = feeds[this.value];
	if(f) {
		selTypes.value = f.serverType;
		fileInput.value = f.url;
		wizard.setValue("feedName",f.serverType);
		wizard.setValue("feedHost",f.url);
		wizard.setValue("feedWorkspace",f.workspace);
		wizard.setValue("feedWorkspaceList",f.workspaceList);
		wizard.setValue("feedTiddlerFilter",f.tiddlerFilter);
	}
	return false;
};

config.macros.importTiddlers.onBrowseChange = function(e)
{
	var wizard = new Wizard(this);
	var file = this.value;
	file = file.replace(/^C:\\fakepath\\/i,''); // remove fakepath (chrome/opera/safari)
	if(this.files && this.files[0]) {
		try {
			netscape.security.PrivilegeManager.enablePrivilege("UniversalFileRead");
			file = this.files[0].fileName; // REQUIRES PRIVILEGES.. NULL otherwise
		} catch (ex) {
			// non-priv fallback: combine filename with path to current document
			var path=getLocalPath(document.location.href);
			var slashpos=path.lastIndexOf('/'); if (slashpos==-1) slashpos=path.lastIndexOf('\\'); 
			if (slashpos!=-1) path=path.substr(0,slashpos+1); // remove filename, leave trailing 	slash
			file=path+file;
		}
	}
	var fileInput = wizard.getElement("txtPath");
	fileInput.value = config.macros.importTiddlers.getURLFromLocalPath(file);
	var serverType = wizard.getElement("selTypes");
	serverType.value = "file";
	return true;
};

config.macros.importTiddlers.getURLFromLocalPath = function(v)
{
	if(!v || !v.length)
		return v;
	v = v.replace(/\\/g,"/"); // use "/" for cross-platform consistency
	var u;
	var t = v.split(":");
	var p = t[1] || t[0]; // remove drive letter (if any)
	if(t[1] && (t[0] == "http" || t[0] == "https" || t[0] == "file")) {
		u = v;
	} else if(p.substr(0,1)=="/") {
		u = document.location.protocol + "//" + document.location.hostname + (t[1] ? "/" : "") + v;
	} else {
		var c = document.location.href.replace(/\\/g,"/");
		var pos = c.lastIndexOf("/");
		if(pos!=-1)
			c = c.substr(0,pos); // remove filename
		u = c + "/" + p;
	}
	return u;
};

config.macros.importTiddlers.onOpen = function(e)
{
	var me = config.macros.importTiddlers;
	var wizard = new Wizard(this);
	var fileInput = wizard.getElement("txtPath");
	var url = fileInput.value;
	var serverType = wizard.getElement("selTypes").value || config.defaultAdaptor;
	var adaptor = new config.adaptors[serverType]();
	wizard.setValue("adaptor",adaptor);
	wizard.setValue("serverType",serverType);
	wizard.setValue("host",url);
	adaptor.openHost(url,null,wizard,me.onOpenHost);
	wizard.setButtons([{caption: me.cancelLabel, tooltip: me.cancelPrompt, onClick: me.onCancel}],me.statusOpenHost);
	return false;
};

config.macros.importTiddlers.onOpenHost = function(context,wizard)
{
	var me = config.macros.importTiddlers;
	var adaptor = wizard.getValue("adaptor");
	if(context.status !== true)
		displayMessage("Error in importTiddlers.onOpenHost: " + context.statusText);
	adaptor.getWorkspaceList(context,wizard,me.onGetWorkspaceList);
	wizard.setButtons([{caption: me.cancelLabel, tooltip: me.cancelPrompt, onClick: me.onCancel}],me.statusGetWorkspaceList);
};

config.macros.importTiddlers.onGetWorkspaceList = function(context,wizard)
{
	var me = config.macros.importTiddlers;
	if(context.status !== true)
		displayMessage("Error in importTiddlers.onGetWorkspaceList: " + context.statusText);
	wizard.setValue("context",context);
	var workspace = wizard.getValue("feedWorkspace");
	if(!workspace && context.workspaces.length==1)
		workspace = context.workspaces[0].title;
	if(workspace) {
		context.adaptor.openWorkspace(workspace,context,wizard,me.onOpenWorkspace);
		wizard.setValue("workspace",workspace);
		wizard.setButtons([{caption: me.cancelLabel, tooltip: me.cancelPrompt, onClick: me.onCancel}],me.statusOpenWorkspace);
		return;
	}
	wizard.addStep(me.step2Title,me.step2Html);
	var t,s = wizard.getElement("selWorkspace");
	s.onchange = me.onWorkspaceChange;
	for(t=0; t<context.workspaces.length; t++) {
		var e = createTiddlyElement(s,"option",null,null,context.workspaces[t].title);
		e.value = context.workspaces[t].title;
	}
	var workspaceList = wizard.getValue("feedWorkspaceList");
	if(workspaceList) {
		var n,list = workspaceList.parseParams("workspace",null,false,true);
		for(n=1; n<list.length; n++) {
			if(context.workspaces.findByField("title",list[n].value) == null) {
				e = createTiddlyElement(s,"option",null,null,list[n].value);
				e.value = list[n].value;
			}
		}
	}
	if(workspace) {
		t = wizard.getElement("txtWorkspace");
		t.value = workspace;
	}
	wizard.setButtons([{caption: me.openLabel, tooltip: me.openPrompt, onClick: me.onChooseWorkspace}]);
};

config.macros.importTiddlers.onWorkspaceChange = function(e)
{
	var wizard = new Wizard(this);
	var t = wizard.getElement("txtWorkspace");
	t.value = this.value;
	this.selectedIndex = 0;
	return false;
};

config.macros.importTiddlers.onChooseWorkspace = function(e)
{
	var me = config.macros.importTiddlers;
	var wizard = new Wizard(this);
	var adaptor = wizard.getValue("adaptor");
	var workspace = wizard.getElement("txtWorkspace").value;
	wizard.setValue("workspace",workspace);
	var context = wizard.getValue("context");
	adaptor.openWorkspace(workspace,context,wizard,me.onOpenWorkspace);
	wizard.setButtons([{caption: me.cancelLabel, tooltip: me.cancelPrompt, onClick: me.onCancel}],me.statusOpenWorkspace);
	return false;
};

config.macros.importTiddlers.onOpenWorkspace = function(context,wizard)
{
	var me = config.macros.importTiddlers;
	if(context.status !== true)
		displayMessage("Error in importTiddlers.onOpenWorkspace: " + context.statusText);
	var adaptor = wizard.getValue("adaptor");
	var browse=wizard.getElement("txtBrowse");
	if (browse.files) context.file=browse.files[0]; // for HTML5 FileReader
	adaptor.getTiddlerList(context,wizard,me.onGetTiddlerList,wizard.getValue("feedTiddlerFilter"));
	wizard.setButtons([{caption: me.cancelLabel, tooltip: me.cancelPrompt, onClick: me.onCancel}],me.statusGetTiddlerList);
};

config.macros.importTiddlers.onGetTiddlerList = function(context,wizard)
{
	var me = config.macros.importTiddlers;
	if(context.status !== true) {
		var error = context.statusText||me.errorGettingTiddlerList;
		if(context.host.indexOf("file://") === 0) {
			error = me.errorGettingTiddlerListFile;
		} else {
			error = context.xhr && context.xhr.status == 404 ? me.errorGettingTiddlerListHttp404 :
				me.errorGettingTiddlerListHttp;
		}
		wizard.setButtons([{caption: me.cancelLabel, tooltip: me.cancelPrompt, onClick: me.onCancel}],"");
		jQuery("span.status", wizard.footerEl).html(error); // so error message can be html
		return;
	}
	// Extract data for the listview
	var listedTiddlers = [];
	if(context.tiddlers) {
		var n;
		for(n=0; n<context.tiddlers.length; n++) {
			var tiddler = context.tiddlers[n];
			listedTiddlers.push({
				title: tiddler.title,
				modified: tiddler.modified,
				modifier: tiddler.modifier,
				text: tiddler.text ? wikifyPlainText(tiddler.text,100) : "",
				tags: tiddler.tags,
				size: tiddler.text ? tiddler.text.length : 0,
				tiddler: tiddler
			});
		}
	}
	listedTiddlers.sort(function(a,b) {return a.title < b.title ? -1 : (a.title == b.title ? 0 : +1);});
	// Display the listview
	wizard.addStep(me.step3Title,me.step3Html);
	var markList = wizard.getElement("markList");
	var listWrapper = document.createElement("div");
	markList.parentNode.insertBefore(listWrapper,markList);
	var listView = ListView.create(listWrapper,listedTiddlers,me.listViewTemplate);
	wizard.setValue("listView",listView);
	wizard.setValue("context",context);
	var txtSaveTiddler = wizard.getElement("txtSaveTiddler");
	txtSaveTiddler.value = me.generateSystemServerName(wizard);
	wizard.setButtons([
			{caption: me.cancelLabel, tooltip: me.cancelPrompt, onClick: me.onCancel},
			{caption: me.importLabel, tooltip: me.importPrompt, onClick: me.doImport}
		]);
};

config.macros.importTiddlers.generateSystemServerName = function(wizard)
{
	var serverType = wizard.getValue("serverType");
	var host = wizard.getValue("host");
	var workspace = wizard.getValue("workspace");
	var pattern = config.macros.importTiddlers[workspace ? "systemServerNamePattern" : "systemServerNamePatternNoWorkspace"];
	return pattern.format([serverType,host,workspace]);
};

config.macros.importTiddlers.saveServerTiddler = function(wizard)
{
	var me = config.macros.importTiddlers;
	var txtSaveTiddler = wizard.getElement("txtSaveTiddler").value;
	if(store.tiddlerExists(txtSaveTiddler)) {
		if(!confirm(me.confirmOverwriteSaveTiddler.format([txtSaveTiddler])))
			return;
		store.suspendNotifications();
		store.removeTiddler(txtSaveTiddler);
		store.resumeNotifications();
	}
	var serverType = wizard.getValue("serverType");
	var host = wizard.getValue("host");
	var workspace = wizard.getValue("workspace");
	var text = me.serverSaveTemplate.format([serverType,host,workspace]);
	store.saveTiddler(txtSaveTiddler,txtSaveTiddler,text,me.serverSaveModifier,new Date(),["systemServer"]);
};

config.macros.importTiddlers.doImport = function(e)
{
	var me = config.macros.importTiddlers;
	var wizard = new Wizard(this);
	if(wizard.getElement("chkSave").checked)
		me.saveServerTiddler(wizard);
	var chkSync = wizard.getElement("chkSync").checked;
	wizard.setValue("sync",chkSync);
	var listView = wizard.getValue("listView");
	var rowNames = ListView.getSelectedRows(listView);
	var adaptor = wizard.getValue("adaptor");
	var overwrite = [];
	var t;
	for(t=0; t<rowNames.length; t++) {
		if(store.tiddlerExists(rowNames[t]))
			overwrite.push(rowNames[t]);
	}
	if(overwrite.length > 0) {
		if(!confirm(me.confirmOverwriteText.format([overwrite.join(", ")])))
			return false;
	}
	wizard.addStep(me.step4Title.format([rowNames.length]),me.step4Html);
	for(t=0; t<rowNames.length; t++) {
		var link = document.createElement("div");
		createTiddlyLink(link,rowNames[t],true);
		var place = wizard.getElement("markReport");
		place.parentNode.insertBefore(link,place);
	}
	wizard.setValue("remainingImports",rowNames.length);
	wizard.setButtons([
			{caption: me.cancelLabel, tooltip: me.cancelPrompt, onClick: me.onCancel}
		],me.statusDoingImport);
	var wizardContext = wizard.getValue("context");
	var tiddlers = wizardContext ? wizardContext.tiddlers : [];
	for(t=0; t<rowNames.length; t++) {
		var context = {
			allowSynchronous:true,
			tiddler:tiddlers[tiddlers.findByField("title",rowNames[t])]
		};
		adaptor.getTiddler(rowNames[t],context,wizard,me.onGetTiddler);
	}
	return false;
};

config.macros.importTiddlers.onGetTiddler = function(context,wizard)
{
	var me = config.macros.importTiddlers;
	if(!context.status)
		displayMessage("Error in importTiddlers.onGetTiddler: " + context.statusText);
	var tiddler = context.tiddler;
	store.suspendNotifications();
	store.saveTiddler(tiddler.title, tiddler.title, tiddler.text, tiddler.modifier, tiddler.modified, tiddler.tags, tiddler.fields, true, tiddler.created);
	if(!wizard.getValue("sync")) {
		store.setValue(tiddler.title,'server',null);
	}
	store.resumeNotifications();
	if(!context.isSynchronous)
		store.notify(tiddler.title,true);
	var remainingImports = wizard.getValue("remainingImports")-1;
	wizard.setValue("remainingImports",remainingImports);
	if(remainingImports == 0) {
		if(context.isSynchronous) {
			store.notifyAll();
			refreshDisplay();
		}
		wizard.setButtons([
				{caption: me.doneLabel, tooltip: me.donePrompt, onClick: me.onClose}
			],me.statusDoneImport);
		autoSaveChanges();
	}
};

//--
//-- Upgrade macro
//--

config.macros.upgrade.handler = function(place)
{
	var w = new Wizard();
	w.createWizard(place,this.wizardTitle);
	w.addStep(this.step1Title,this.step1Html.format([this.source,this.source]));
	w.setButtons([{caption: this.upgradeLabel, tooltip: this.upgradePrompt, onClick: this.onClickUpgrade}]);
};

config.macros.upgrade.onClickUpgrade = function(e)
{
	var me = config.macros.upgrade;
	var w = new Wizard(this);
	if(!window.allowSave()) {
		alert(me.errorCantUpgrade);
		return false;
	}
	if(story.areAnyDirty() || store.isDirty()) {
		alert(me.errorNotSaved);
		return false;
	}
	var localPath = getLocalPath(document.location.toString());
	var backupPath = getBackupPath(localPath,me.backupExtension);
	w.setValue("backupPath",backupPath);
	w.setButtons([],me.statusPreparingBackup);
	var original = loadOriginal(localPath);
	w.setButtons([],me.statusSavingBackup);
	var backup = copyFile(backupPath,localPath);
	if(!backup)
		backup = saveFile(backupPath,original);
	if(!backup) {
		w.setButtons([],me.errorSavingBackup);
		alert(me.errorSavingBackup);
		return false;
	}
	w.setButtons([],me.statusLoadingCore);
	var options = {
		type:"GET",
		url:me.source,
		processData:false,
		success:function(data,textStatus,jqXHR) {
			me.onLoadCore(true,w,jqXHR.responseText,me.source,jqXHR);
		},
		error:function(jqXHR,textStatus,errorThrown) {
			me.onLoadCore(false,w,null,me.source,jqXHR);
		}
	};
	ajaxReq(options);
	return false;
};

config.macros.upgrade.onLoadCore = function(status,params,responseText,url,xhr)
{
	var me = config.macros.upgrade;
	var w = params;
	var errMsg;
	if(!status)
		errMsg = me.errorLoadingCore;
	var newVer = me.extractVersion(responseText);
	if(!newVer)
		errMsg = me.errorCoreFormat;
	if(errMsg) {
		w.setButtons([],errMsg);
		alert(errMsg);
		return;
	}
	var onStartUpgrade = function(e) {
		w.setButtons([],me.statusSavingCore);
		var localPath = getLocalPath(document.location.toString());
		saveFile(localPath,responseText);
		w.setButtons([],me.statusReloadingCore);
		var backupPath = w.getValue("backupPath");
		var newLoc = document.location.toString() + "?time=" + new Date().convertToYYYYMMDDHHMM() + "#upgrade:[[" + encodeURI(backupPath) + "]]";
		window.setTimeout(function () {window.location = newLoc;},10);
	};
	var step2 = [me.step2Html_downgrade,me.step2Html_restore,me.step2Html_upgrade][compareVersions(version,newVer) + 1];
	w.addStep(me.step2Title,step2.format([formatVersion(newVer),formatVersion(version)]));
	w.setButtons([{caption: me.startLabel, tooltip: me.startPrompt, onClick: onStartUpgrade},{caption: me.cancelLabel, tooltip: me.cancelPrompt, onClick: me.onCancel}]);
};

config.macros.upgrade.onCancel = function(e)
{
	var me = config.macros.upgrade;
	var w = new Wizard(this);
	w.addStep(me.step3Title,me.step3Html);
	w.setButtons([]);
	return false;
};

config.macros.upgrade.extractVersion = function(upgradeFile)
{
	var re = /^var version = \{title: "([^"]+)", major: (\d+), minor: (\d+), revision: (\d+)(, beta: (\d+)){0,1}, date: new Date\("([^"]+)"\)/mg;
	var m = re.exec(upgradeFile);
	return m ? {title: m[1], major: m[2], minor: m[3], revision: m[4], beta: m[6], date: new Date(m[7])} : null;
};

function upgradeFrom(path)
{
	var importStore = new TiddlyWiki();
	var tw = loadFile(path);
	if(window.netscape !== undefined)
		tw = convertUTF8ToUnicode(tw);
	importStore.importTiddlyWiki(tw);
	importStore.forEachTiddler(function(title,tiddler) {
		if(!store.getTiddler(title)) {
			store.addTiddler(tiddler);
		}
	});
	refreshDisplay();
	saveChanges(); //# To create appropriate Markup* sections
	alert(config.messages.upgradeDone.format([formatVersion()]));
	window.location = window.location.toString().substr(0,window.location.toString().lastIndexOf("?"));
}

//--
//-- Manager UI for groups of tiddlers
//--

config.macros.plugins.handler = function(place,macroName,params,wikifier,paramString)
{
	var wizard = new Wizard();
	wizard.createWizard(place,this.wizardTitle);
	wizard.addStep(this.step1Title,this.step1Html);
	var markList = wizard.getElement("markList");
	var listWrapper = document.createElement("div");
	markList.parentNode.insertBefore(listWrapper,markList);
	listWrapper.setAttribute("refresh","macro");
	listWrapper.setAttribute("macroName","plugins");
	listWrapper.setAttribute("params",paramString);
	this.refresh(listWrapper,paramString);
};

config.macros.plugins.refresh = function(listWrapper,params)
{
	var me = config.macros.plugins;
	var wizard = new Wizard(listWrapper);
	var selectedRows = [];
	ListView.forEachSelector(listWrapper,function(e,rowName) {
			if(e.checked)
				selectedRows.push(e.getAttribute("rowName"));
		});
	jQuery(listWrapper).empty();
	params = params.parseParams("anon");
	var plugins = installedPlugins.slice(0);
	var t,tiddler,p;
	var configTiddlers = store.getTaggedTiddlers("systemConfig");
	for(t=0; t<configTiddlers.length; t++) {
		tiddler = configTiddlers[t];
		if(plugins.findByField("title",tiddler.title) == null) {
			p = getPluginInfo(tiddler);
			p.executed = false;
			p.log.splice(0,0,this.skippedText);
			plugins.push(p);
		}
	}
	for(t=0; t<plugins.length; t++) {
		p = plugins[t];
		p.size = p.tiddler.text ? p.tiddler.text.length : 0;
		p.forced = p.tiddler.isTagged("systemConfigForce");
		p.disabled = p.tiddler.isTagged("systemConfigDisable");
		p.Selected = selectedRows.indexOf(plugins[t].title) != -1;
	}
	if(plugins.length == 0) {
		createTiddlyElement(listWrapper,"em",null,null,this.noPluginText);
		wizard.setButtons([]);
	} else {
		var template = readOnly ? this.listViewTemplateReadOnly : this.listViewTemplate;
		var listView = ListView.create(listWrapper,plugins,template,this.onSelectCommand);
		wizard.setValue("listView",listView);
		if(!readOnly) {
			wizard.setButtons([
				{caption: me.removeLabel, tooltip: me.removePrompt, onClick: me.doRemoveTag},
				{caption: me.deleteLabel, tooltip: me.deletePrompt, onClick: me.doDelete}
			]);
		}
	}
};

config.macros.plugins.doRemoveTag = function(e)
{
	var wizard = new Wizard(this);
	var listView = wizard.getValue("listView");
	var rowNames = ListView.getSelectedRows(listView);
	if(rowNames.length == 0) {
		alert(config.messages.nothingSelected);
	} else {
		var t;
		for(t=0; t<rowNames.length; t++) {
			store.setTiddlerTag(rowNames[t],false,"systemConfig");
		}
		autoSaveChanges();
	}
};

config.macros.plugins.doDelete = function(e)
{
	var wizard = new Wizard(this);
	var listView = wizard.getValue("listView");
	var rowNames = ListView.getSelectedRows(listView);
	if(rowNames.length == 0) {
		alert(config.messages.nothingSelected);
	} else {
		if(confirm(config.macros.plugins.confirmDeleteText.format([rowNames.join(", ")]))) {
			var t;
			for(t=0; t<rowNames.length; t++) {
				store.removeTiddler(rowNames[t]);
				story.closeTiddler(rowNames[t],true);
			}
		}
		autoSaveChanges();
	}
};

//--
//-- Message area
//--

function getMessageDiv()
{
	var msgArea = document.getElementById("messageArea");
	if(!msgArea)
		return null;
	if(!msgArea.hasChildNodes())
		createTiddlyButton(createTiddlyElement(msgArea,"div",null,"messageToolbar"),
			config.messages.messageClose.text,
			config.messages.messageClose.tooltip,
			clearMessage);
	msgArea.style.display = "block";
	return createTiddlyElement(msgArea,"div");
}

function displayMessage(text,linkText)
{
	var e = getMessageDiv();
	if(!e) {
		alert(text);
		return;
	}
	if(linkText) {
		var link = createTiddlyElement(e,"a",null,null,text);
		link.href = linkText;
		link.target = "_blank";
	} else {
		e.appendChild(document.createTextNode(text));
	}
}

function clearMessage()
{
	var msgArea = document.getElementById("messageArea");
	if(msgArea) {
		jQuery(msgArea).empty();
		msgArea.style.display = "none";
	}
	return false;
}

//--
//-- Refresh mechanism
//--

config.notifyTiddlers = [
	{name: "SystemSettings", notify: onSystemSettingsChange},
	{name: "StyleSheetLayout", notify: refreshStyles},
	{name: "StyleSheetColors", notify: refreshStyles},
	{name: "StyleSheet", notify: refreshStyles},
	{name: "StyleSheetPrint", notify: refreshStyles},
	{name: "PageTemplate", notify: refreshPageTemplate},
	{name: "SiteTitle", notify: refreshPageTitle},
	{name: "SiteSubtitle", notify: refreshPageTitle},
	{name: "WindowTitle", notify: refreshPageTitle},
	{name: "ColorPalette", notify: refreshColorPalette},
	{name: null, notify: refreshDisplay}
];

config.refreshers = {
	link: function(e,changeList)
		{
		var title = e.getAttribute("tiddlyLink");
		refreshTiddlyLink(e,title);
		return true;
		},

	tiddler: function(e,changeList)
		{
		var title = e.getAttribute("tiddler");
		var template = e.getAttribute("template");
		if(changeList && (changeList.indexOf && changeList.indexOf(title) != -1) && !story.isDirty(title))
			story.refreshTiddler(title,template,true);
		else
			refreshElements(e,changeList);
		return true;
		},

	content: function(e,changeList)
		{
		var title = e.getAttribute("tiddler");
		var force = e.getAttribute("force");
		var args = e.getAttribute("args");
		if(force != null || changeList == null || (changeList.indexOf && changeList.indexOf(title) != -1)) {
			jQuery(e).empty();
			config.macros.tiddler.transclude(e,title,args);
			return true;
		} else
			return false;
		},

	macro: function(e,changeList)
		{
		var macro = e.getAttribute("macroName");
		var params = e.getAttribute("params");
		if(macro)
			macro = config.macros[macro];
		if(macro && macro.refresh)
			macro.refresh(e,params);
		return true;
		}
};

config.refresherData = {
	styleSheet: "StyleSheet",
	defaultStyleSheet: "StyleSheet",
	pageTemplate: "PageTemplate",
	defaultPageTemplate: "PageTemplate",
	colorPalette: "ColorPalette",
	defaultColorPalette: "ColorPalette"
};

function refreshElements(root,changeList)
{
	var c,nodes = root.childNodes;
	for(c=0; c<nodes.length; c++) {
		var e = nodes[c], type = null;
		if(e.getAttribute && (e.tagName ? e.tagName != "IFRAME" : true))
			type = e.getAttribute("refresh");
		var refresher = config.refreshers[type];
		var refreshed = false;
		if(refresher != undefined)
			refreshed = refresher(e,changeList);
		if(e.hasChildNodes() && !refreshed)
			refreshElements(e,changeList);
	}
}

function applyHtmlMacros(root,tiddler)
{
	var e = root.firstChild;
	while(e) {
		var nextChild = e.nextSibling;
		if(e.getAttribute) {
			var macro = e.getAttribute("macro");
			if(macro) {
				e.removeAttribute("macro");
				var params = "";
				var p = macro.indexOf(" ");
				if(p != -1) {
					params = macro.substr(p+1);
					macro = macro.substr(0,p);
				}
				invokeMacro(e,macro,params,null,tiddler);
			}
		}
		if(e.hasChildNodes())
			applyHtmlMacros(e,tiddler);
		e = nextChild;
	}
}

function refreshPageTemplate(title)
{
	var stash = jQuery("<div/>").appendTo("body").hide()[0];
	var display = story.getContainer();
	var nodes,t;
	if(display) {
		nodes = display.childNodes;
		for(t=nodes.length-1; t>=0; t--)
			stash.appendChild(nodes[t]);
	}
	var wrapper = document.getElementById("contentWrapper");

	if(!title || !store.isAvailable(title))
		title = config.refresherData.pageTemplate;
	if(!store.isAvailable(title))
		title = config.refresherData.defaultPageTemplate; //# this one is always avaialable
	wrapper.innerHTML = store.getRecursiveTiddlerText(title,null,10);
	applyHtmlMacros(wrapper);
	refreshElements(wrapper);
	display = story.getContainer();
	jQuery(display).empty();
	if(!display)
		display = createTiddlyElement(wrapper,"div",story.containerId());
	nodes = stash.childNodes;
	for(t=nodes.length-1; t>=0; t--)
		display.appendChild(nodes[t]);
	jQuery(stash).remove();
}

function refreshDisplay(hint)
{
	if(typeof hint == "string")
		hint = [hint];
	var e = document.getElementById("contentWrapper");
	refreshElements(e,hint);
	if(backstage.isPanelVisible()) {
		e = document.getElementById("backstage");
		refreshElements(e,hint);
	}
}

function refreshPageTitle()
{
	document.title = getPageTitle();
}

function getPageTitle()
{
	return wikifyPlainText(store.getTiddlerText("WindowTitle",""),null,tiddler);
}

function refreshStyles(title,doc)
{
	setStylesheet(title == null ? "" : store.getRecursiveTiddlerText(title,"",10),title,doc || document);
}

function refreshColorPalette(title)
{
	if(!startingUp)
		refreshAll();
}

function refreshAll()
{
	refreshPageTemplate();
	refreshDisplay();
	refreshStyles("StyleSheetLayout");
	refreshStyles("StyleSheetColors");
	refreshStyles(config.refresherData.styleSheet);
	refreshStyles("StyleSheetPrint");
}

//--
//-- Option handling
//--

config.optionHandlers = {
	'txt': {
		get: function(name) {return encodeCookie(config.options[name].toString());},
		set: function(name,value) {config.options[name] = decodeCookie(value);}
	},
	'chk': {
		get: function(name) {return config.options[name] ? 'true' : 'false';},
		set: function(name,value) {config.options[name] = value == 'true';}
	}
};

function setOption(name,value)
{
	var optType = name.substr(0,3);
	if(config.optionHandlers[optType] && config.optionHandlers[optType].set)
		config.optionHandlers[optType].set(name,value);
}

// Gets the value of an option as a string. Most code should just read from config.options.* directly
function getOption(name)
{
	var optType = name.substr(0,3);
	return config.optionHandlers[optType] && config.optionHandlers[optType].get ? config.optionHandlers[optType].get(name) : null;
}

function loadOptions()
{
	if(safeMode)
		return;
	loadCookies();
	loadSystemSettings();
}
// @Deprecated; retained for backwards compatibility
var loadOptionsCookie = loadOptions;

function getCookies()
{
	var cookieList = document.cookie.split(';');
	var i,cookies = {};
	for(i=0; i<cookieList.length; i++) {
		var p = cookieList[i].indexOf('=');
		if(p != -1) {
			var name = cookieList[i].substr(0,p).trim();
			var value = cookieList[i].substr(p+1).trim();
			cookies[name] = value;
		}
	}
	return cookies;
}

function loadCookies()
{
	var i,cookies = getCookies();
	if(cookies['TiddlyWiki']) {
		cookies = cookies['TiddlyWiki'].decodeHashMap();
	}
	for(i in cookies) {
		if(config.optionsSource[i] != 'setting') {
			setOption(i,cookies[i]);
		}
	}
}

function loadSystemSettings()
{
	var key,settings = store.calcAllSlices('SystemSettings');
	config.optionsSource = {};
	for(key in settings) {
		setOption(key,settings[key]);
		config.optionsSource[key] = 'setting';
	}
}

function onSystemSettingsChange()
{
	if(!startingUp) {
		loadSystemSettings();
	}
}

function saveOption(name)
{
	if(safeMode)
		return;
	if(name.match(/[()\s]/g, '_')) {
		alert(config.messages.invalidCookie.format([name]));
		return;
	}
	saveCookie(name);
	if(config.optionsSource[name] == 'setting') {
		saveSystemSetting(name,true);
	}
}
// @Deprecated; retained for backwards compatibility
var saveOptionCookie = saveOption;

function removeCookie(name)
{
	document.cookie = name + '=; expires=Thu, 01-Jan-1970 00:00:01 UTC; path=/;';
}

function saveCookie(name)
{
	var key,cookies = {};
	for(key in config.options) {
		var value = getOption(key);
		value = value == null ? 'false' : value;
		cookies[key] = value;
	}
	document.cookie = 'TiddlyWiki=' + String.encodeHashMap(cookies) + '; expires=Fri, 1 Jan 2038 12:00:00 UTC; path=/';
	cookies = getCookies();
	var c;
	for(c in cookies) {
		var optType = c.substr(0,3);
		if(config.optionHandlers[optType])
			removeCookie(c);
	}
}

var systemSettingSave;
function commitSystemSettings(storeWasDirty)
{
	if(systemSettingSave) {
		window.clearTimeout(systemSettingSave);
	}
	systemSettingSave = window.setTimeout(function() {
		var tiddler = store.getTiddler('SystemSettings');
		autoSaveChanges(null,[tiddler]);
	}, 1000);
}

function saveSystemSetting(name,saveFile)
{
	var title = 'SystemSettings';
	var slice = store.getTiddlerSlice(title,name);
	if(readOnly || slice === getOption(name)) {
		return; //# don't save if read-only or the option hasn't changed
	}
	var slices = store.calcAllSlices(title);
	var key;
	for(key in config.optionsSource) {
		var value = getOption(key) || '';
		if(slices[key] !== value) {
			slices[key] = value;
		}
	}
	var text = [];
	for(key in slices) {
		text.push('%0: %1'.format([key,slices[key]]));
	}
	text = text.sort().join('\n');
	var storeWasDirty = store.isDirty();
	var tiddler = store.getTiddler(title);
	if(tiddler) {
		tiddler.text = text;
		tiddler = store.saveTiddler(tiddler);
	} else {
		tiddler = store.saveTiddler(title,title,text,'System',new Date(),['excludeLists'],config.defaultCustomFields);
	}
	if(saveFile) {
		commitSystemSettings(storeWasDirty);
	}
}

function encodeCookie(s)
{
	return escape(convertUnicodeToHtmlEntities(s));
}

function decodeCookie(s)
{
	s = unescape(s);
	var re = /&#[0-9]{1,5};/g;
	return s.replace(re,function($0) {return String.fromCharCode(eval($0.replace(/[&#;]/g,'')));});
}

config.macros.option.genericCreate = function(place,type,opt,className,desc)
{
	var typeInfo = config.macros.option.types[type];
	var c = document.createElement(typeInfo.elementType);
	if(typeInfo.typeValue)
		c.setAttribute('type',typeInfo.typeValue);
	c[typeInfo.eventName] = typeInfo.onChange;
	c.setAttribute('option',opt);
	c.className = className || typeInfo.className;
	if(config.optionsDesc[opt])
		c.setAttribute('title',config.optionsDesc[opt]);
	place.appendChild(c);
	if(desc != 'no')
		createTiddlyText(place,config.optionsDesc[opt] || opt);
	c[typeInfo.valueField] = config.options[opt];
	return c;
};

config.macros.option.genericOnChange = function(e)
{
	var opt = this.getAttribute('option');
	if(opt) {
		var optType = opt.substr(0,3);
		var handler = config.macros.option.types[optType];
		if(handler.elementType && handler.valueField)
			config.macros.option.propagateOption(opt,handler.valueField,this[handler.valueField],handler.elementType,this);
	}
	return true;
};

config.macros.option.types = {
	'txt': {
		elementType: 'input',
		valueField: 'value',
		eventName: 'onchange',
		className: 'txtOptionInput',
		create: config.macros.option.genericCreate,
		onChange: config.macros.option.genericOnChange
	},
	'chk': {
		elementType: 'input',
		valueField: 'checked',
		eventName: 'onclick',
		className: 'chkOptionInput',
		typeValue: 'checkbox',
		create: config.macros.option.genericCreate,
		onChange: config.macros.option.genericOnChange
	}
};

config.macros.option.propagateOption = function(opt,valueField,value,elementType,elem)
{
	config.options[opt] = value;
	saveOption(opt);
	var t,nodes = document.getElementsByTagName(elementType);
	for(t=0; t<nodes.length; t++) {
		var optNode = nodes[t].getAttribute('option');
		if(opt == optNode && nodes[t]!=elem)
			nodes[t][valueField] = value;
	}
};

config.macros.option.handler = function(place,macroName,params,wikifier,paramString)
{
	params = paramString.parseParams('anon',null,true,false,false);
	var opt = (params[1] && params[1].name == 'anon') ? params[1].value : getParam(params,'name',null);
	var className = (params[2] && params[2].name == 'anon') ? params[2].value : getParam(params,'class',null);
	var desc = getParam(params,'desc','no');
	var type = opt.substr(0,3);
	var h = config.macros.option.types[type];
	if(h && h.create)
		h.create(place,type,opt,className,desc);
};

config.macros.options.handler = function(place,macroName,params,wikifier,paramString)
{
	params = paramString.parseParams('anon',null,true,false,false);
	var showUnknown = getParam(params,'showUnknown','no');
	var wizard = new Wizard();
	wizard.createWizard(place,this.wizardTitle);
	wizard.addStep(this.step1Title,this.step1Html);
	var markList = wizard.getElement('markList');
	var chkUnknown = wizard.getElement('chkUnknown');
	chkUnknown.checked = showUnknown == 'yes';
	chkUnknown.onchange = this.onChangeUnknown;
	var listWrapper = document.createElement('div');
	markList.parentNode.insertBefore(listWrapper,markList);
	wizard.setValue('listWrapper',listWrapper);
	this.refreshOptions(listWrapper,showUnknown == 'yes');
};

config.macros.options.refreshOptions = function(listWrapper,showUnknown)
{
	var n,opts = [];
	for(n in config.options) {
		var opt = {};
		opt.option = '';
		opt.name = n;
		opt.lowlight = !config.optionsDesc[n];
		opt.description = opt.lowlight ? this.unknownDescription : config.optionsDesc[n];
		if(!opt.lowlight || showUnknown)
			opts.push(opt);
	}
	opts.sort(function(a,b) {return a.name.substr(3) < b.name.substr(3) ? -1 : (a.name.substr(3) == b.name.substr(3) ? 0 : +1);});
	ListView.create(listWrapper,opts,this.listViewTemplate);
	for(n=0; n<opts.length; n++) {
		var type = opts[n].name.substr(0,3);
		var h = config.macros.option.types[type];
		if(h && h.create) {
			h.create(opts[n].colElements['option'],type,opts[n].name,null,'no');
		}
	}
};

config.macros.options.onChangeUnknown = function(e)
{
	var wizard = new Wizard(this);
	var listWrapper = wizard.getValue('listWrapper');
	jQuery(listWrapper).empty();
	config.macros.options.refreshOptions(listWrapper,this.checked);
	return false;
};

//--
//-- Saving
//--

var saveUsingSafari = false;

var startSaveArea = '<div id="' + 'storeArea">'; // Split up into two so that indexOf() of this source doesn't find it
var startSaveAreaRE = /<((div)|(DIV)) ((id)|(ID))=["']?storeArea['"]?>/; // Used for IE6
var endSaveArea = '</d' + 'iv>';
var endSaveAreaCaps = '</D' + 'IV>';

// If there are unsaved changes, force the user to confirm before exitting
function confirmExit()
{
	hadConfirmExit = true;
	if((store && store.isDirty && store.isDirty()) || (story && story.areAnyDirty && story.areAnyDirty()))
		return config.messages.confirmExit;
}

// Give the user a chance to save changes before exitting
function checkUnsavedChanges()
{
	if(store && store.isDirty && store.isDirty() && window.hadConfirmExit === false) {
		if(confirm(config.messages.unsavedChangesWarning))
			saveChanges();
	}
}

function updateLanguageAttribute(s)
{
	if(config.locale) {
		var mRE = /(<html(?:.*?)?)(?: xml:lang\="([a-z]+)")?(?: lang\="([a-z]+)")?>/;
		var m = mRE.exec(s);
		if(m) {
			var t = m[1];
			if(m[2])
				t += ' xml:lang="' + config.locale + '"';
			if(m[3])
				t += ' lang="' + config.locale + '"';
			t += ">";
			s = s.substr(0,m.index) + t + s.substr(m.index+m[0].length);
		}
	}
	return s;
}

function updateMarkupBlock(s,blockName,tiddlerName)
{
	return s.replaceChunk(
			"<!--%0-START-->".format([blockName]),
			"<!--%0-END-->".format([blockName]),
			"\n" + convertUnicodeToFileFormat(store.getRecursiveTiddlerText(tiddlerName,"")) + "\n");
}

function updateOriginal(original,posDiv,localPath)
{
	if(!posDiv)
		posDiv = locateStoreArea(original);
	if(!posDiv) {
		alert(config.messages.invalidFileError.format([localPath]));
		return null;
	}
	var revised = original.substr(0,posDiv[0] + startSaveArea.length) + "\n" +
				convertUnicodeToFileFormat(store.allTiddlersAsHtml()) + "\n" +
				original.substr(posDiv[1]);
	var newSiteTitle = convertUnicodeToFileFormat(getPageTitle()).htmlEncode();
	revised = revised.replaceChunk("<title"+">","</title"+">"," " + newSiteTitle + " ");
	revised = updateLanguageAttribute(revised);
	revised = updateMarkupBlock(revised,"PRE-HEAD","MarkupPreHead");
	revised = updateMarkupBlock(revised,"POST-HEAD","MarkupPostHead");
	revised = updateMarkupBlock(revised,"PRE-BODY","MarkupPreBody");
	revised = updateMarkupBlock(revised,"POST-SCRIPT","MarkupPostBody");
	return revised;
}

function locateStoreArea(original)
{
	// Locate the storeArea divs
	if(!original)
		return null;
	var posOpeningDiv = original.search(startSaveAreaRE);
	var limitClosingDiv = original.indexOf("<"+"!--POST-STOREAREA--"+">");
	if(limitClosingDiv == -1)
		limitClosingDiv = original.indexOf("<"+"!--POST-BODY-START--"+">");
	var start = limitClosingDiv == -1 ? original.length : limitClosingDiv;
	var posClosingDiv = original.lastIndexOf(endSaveArea,start);
	if(posClosingDiv == -1)
		posClosingDiv = original.lastIndexOf(endSaveAreaCaps,start);
	return (posOpeningDiv != -1 && posClosingDiv != -1) ? [posOpeningDiv,posClosingDiv] : null;
}

function autoSaveChanges(onlyIfDirty,tiddlers)
{
	if(config.options.chkAutoSave)
		saveChanges(onlyIfDirty,tiddlers);
}

function loadOriginal(localPath)
{
	var content=loadFile(localPath);
	if (!content) content=window.originalHTML||recreateOriginal();
	return content;
}

function recreateOriginal()
{
	// construct doctype
	var content = "<!DOCTYPE ";
	var t=document.doctype;
	if (!t) 
		content+="html"
	else {
		content+=t.name;
		if      (t.publicId)		content+=' PUBLIC "'+t.publicId+'"';
		else if (t.systemId)		content+=' SYSTEM "'+t.systemId+'"';
	}
	content+=' "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd"';
	content+='>\n';

	// append current document content
	content+=document.documentElement.outerHTML;

	content=content.replace(/<div id="saveTest">savetest<\/div>/,'<div id="saveTest"></div>');
	content=content.replace(/script><applet [^\>]*><\/applet>/g,'script>');
	content=content.replace(/><head>/,'>\n<head>');
	content=content.replace(/\n\n<\/body><\/html>$/,'</body>\n</html>\n');
	content=content.replace(/(<(meta) [^\>]*[^\/])>/g,'$1 />');
	content=content.replace(/<noscript>[^\<]*<\/noscript>/,
		function(m){return m.replace(/&lt;/g,'<').replace(/&gt;/g,'>');});
	content=content.replace(/<div id="copyright">[^\<]*<\/div>/,
		function(m){return m.replace(/\xA9/g,'&copy;');});

	return content;
}

// Save this tiddlywiki with the pending changes
function saveChanges(onlyIfDirty,tiddlers)
{
	if(onlyIfDirty && !store.isDirty())
		return;
	clearMessage();
	var t0 = new Date();
	var msg = config.messages;
	var originalPath = document.location.toString();
	if(!window.allowSave()) {
		alert(msg.notFileUrlError);
		if(store.tiddlerExists(msg.saveInstructions))
			story.displayTiddler(null,msg.saveInstructions);
		return;
	}
	var localPath = getLocalPath(originalPath);
	var original = loadOriginal(localPath);
	if(original == null) {
		alert(msg.cantSaveError);
		if(store.tiddlerExists(msg.saveInstructions))
			story.displayTiddler(null,msg.saveInstructions);
		return;
	}
	var posDiv = locateStoreArea(original);
	if(!posDiv) {
		alert(msg.invalidFileError.format([localPath]));
		return;
	}
	var co=config.options; //# abbreviation
	config.saveByDownload=false;
	config.saveByManualDownload=false;
	saveMain(localPath,original,posDiv);
	if (!config.saveByDownload && !config.saveByManualDownload) {
		if(co.chkSaveBackups)
			saveBackup(localPath,original);
		if(co.chkSaveEmptyTemplate)
			saveEmpty(localPath,original,posDiv);
		if(co.chkGenerateAnRssFeed && saveRss instanceof Function)
			saveRss(localPath);
	}
	if(co.chkDisplayInstrumentation)
		displayMessage("saveChanges " + (new Date()-t0) + " ms");
}


function saveMain(localPath,original,posDiv)
{
	var save;
	try {
		var revised = updateOriginal(original,posDiv,localPath);
		save = saveFile(localPath,revised);
	} catch (ex) {
		showException(ex);
	}
	if(save) {
		if (!config.saveByManualDownload) {
			if (config.saveByDownload) { //# set by HTML5DownloadSaveFile()
				var link = getDataURI(revised);
				var msg  = config.messages.mainDownload;
			} else {
				var link = "file://" + localPath;
				var msg  = config.messages.mainSaved;
			}
			displayMessage(msg,link);
		}
		store.setDirty(false);
	} else {
		alert(config.messages.mainFailed);
	}
}

function saveBackup(localPath,original)
{
	var backupPath = getBackupPath(localPath);
	var backup = copyFile(backupPath,localPath);
	if(!backup)
		backup = saveFile(backupPath,original);
	if(backup)
		displayMessage(config.messages.backupSaved,"file://" + backupPath);
	else
		alert(config.messages.backupFailed);
}

function saveEmpty(localPath,original,posDiv)
{
	var emptyPath,p;
	if((p = localPath.lastIndexOf("/")) != -1)
		emptyPath = localPath.substr(0,p) + "/";
	else if((p = localPath.lastIndexOf("\\")) != -1)
		emptyPath = localPath.substr(0,p) + "\\";
	else
		emptyPath = localPath + ".";
	emptyPath += "empty.html";
	var empty = original.substr(0,posDiv[0] + startSaveArea.length) + original.substr(posDiv[1]);
	var emptySave = saveFile(emptyPath,empty);
	if(emptySave)
		displayMessage(config.messages.emptySaved,"file://" + emptyPath);
	else
		alert(config.messages.emptyFailed);
}

// Translate URL to local path [Preemption]
window.getLocalPath = window.getLocalPath || function(origPath)
{
	var originalPath = convertUriToUTF8(origPath,config.options.txtFileSystemCharSet);
	// Remove any location or query part of the URL
	var argPos = originalPath.indexOf("?");
	if(argPos != -1)
		originalPath = originalPath.substr(0,argPos);
	var hashPos = originalPath.indexOf("#");
	if(hashPos != -1)
		originalPath = originalPath.substr(0,hashPos);
	// Convert file://localhost/ to file:///
	if(originalPath.indexOf("file://localhost/") == 0)
		originalPath = "file://" + originalPath.substr(16);
	// Convert to a native file format
	var localPath;
	if(originalPath.charAt(9) == ":") // pc local file
		localPath = unescape(originalPath.substr(8)).replace(new RegExp("/","g"),"\\");
	else if(originalPath.indexOf("file://///") == 0) // FireFox pc network file
		localPath = "\\\\" + unescape(originalPath.substr(10)).replace(new RegExp("/","g"),"\\");
	else if(originalPath.indexOf("file:///") == 0) // mac/unix local file
		localPath = unescape(originalPath.substr(7));
	else if(originalPath.indexOf("file:/") == 0) // mac/unix local file
		localPath = unescape(originalPath.substr(5));
	else // pc network file
		localPath = "\\\\" + unescape(originalPath.substr(7)).replace(new RegExp("/","g"),"\\");
	return localPath;
}

function getBackupPath(localPath,title,extension)
{
	var slash = "\\";
	var dirPathPos = localPath.lastIndexOf("\\");
	if(dirPathPos == -1) {
		dirPathPos = localPath.lastIndexOf("/");
		slash = "/";
	}
	var backupFolder = config.options.txtBackupFolder;
	if(!backupFolder || backupFolder == "")
		backupFolder = ".";
	var backupPath = localPath.substr(0,dirPathPos) + slash + backupFolder + localPath.substr(dirPathPos);
	backupPath = backupPath.substr(0,backupPath.lastIndexOf(".")) + ".";
	if(title)
		backupPath += title.replace(/[\\\/\*\?\":<> ]/g,"_") + ".";
	backupPath += (new Date()).convertToYYYYMMDDHHMMSSMMM() + "." + (extension || "html");
	return backupPath;
}

//--
//-- RSS Saving
//--

function saveRss(localPath)
{
	var rssPath = localPath.substr(0,localPath.lastIndexOf(".")) + ".xml";
	if(saveFile(rssPath,convertUnicodeToFileFormat(generateRss())))
		displayMessage(config.messages.rssSaved,"file://" + rssPath);
	else
		alert(config.messages.rssFailed);
}

tiddlerToRssItem = function(tiddler,uri)
{
	var s = "<title" + ">" + tiddler.title.htmlEncode() + "</title" + ">\n";
	s += "<description>" + wikifyStatic(tiddler.text,null,tiddler).htmlEncode() + "</description>\n";
	var i;
	for(i=0; i<tiddler.tags.length; i++)
		s += "<category>" + tiddler.tags[i] + "</category>\n";
	s += "<link>" + uri + "#" + encodeURIComponent(String.encodeTiddlyLink(tiddler.title)) + "</link>\n";
	s +="<pubDate>" + tiddler.modified.toGMTString() + "</pubDate>\n";
	return s;
};

function generateRss()
{
	var s = [];
	var d = new Date();
	var u = store.getTiddlerText("SiteUrl");
	// Assemble the header
	s.push("<" + "?xml version=\"1.0\"?" + ">");
	s.push("<rss version=\"2.0\">");
	s.push("<channel>");
	s.push("<title" + ">" + wikifyPlainText(store.getTiddlerText("SiteTitle",""),null,tiddler).htmlEncode() + "</title" + ">");
	if(u)
		s.push("<link>" + u.htmlEncode() + "</link>");
	s.push("<description>" + wikifyPlainText(store.getTiddlerText("SiteSubtitle",""),null,tiddler).htmlEncode() + "</description>");
	s.push("<language>" + config.locale + "</language>");
	s.push("<copyright>Copyright " + d.getFullYear() + " " + config.options.txtUserName.htmlEncode() + "</copyright>");
	s.push("<pubDate>" + d.toGMTString() + "</pubDate>");
	s.push("<lastBuildDate>" + d.toGMTString() + "</lastBuildDate>");
	s.push("<docs>http://blogs.law.harvard.edu/tech/rss</docs>");
	s.push("<generator>TiddlyWiki " + formatVersion() + "</generator>");
	// The body
	var tiddlers = store.getTiddlers("modified","excludeLists");
	var i,n = config.numRssItems > tiddlers.length ? 0 : tiddlers.length-config.numRssItems;
	for(i=tiddlers.length-1; i>=n; i--) {
		s.push("<item>\n" + tiddlerToRssItem(tiddlers[i],u) + "\n</item>");
	}
	// And footer
	s.push("</channel>");
	s.push("</rss>");
	// Save it all
	return s.join("\n");
}

//--
//-- Filesystem code
//--

// Copy a file in filesystem [Preemption]
window.copyFile = window.copyFile || function(dest,source)
{
	return config.browser.isIE ? ieCopyFile(dest,source) : false;
}


// Save a file in filesystem [Preemption]
window.saveFile = window.saveFile || function(fileUrl,content)
{
	var r = mozillaSaveFile(fileUrl,content);
	if(!r)
		r = ieSaveFile(fileUrl,content);
	if(!r)
		r = javaSaveFile(fileUrl,content);
	if(!r)
		r = HTML5DownloadSaveFile(fileUrl,content);
	if(!r)
		r = manualSaveFile(fileUrl,content);
	return r;
}

// Load a file from filesystem [Preemption]
window.loadFile = window.loadFile || function(fileUrl)
{
	var r = mozillaLoadFile(fileUrl);
	if((r == null) || (r == false))
		r = ieLoadFile(fileUrl);
	if((r == null) || (r == false))
		r = javaLoadFile(fileUrl);
	return r;
}

function ieCreatePath(path)
{
	try {
		var fso = new ActiveXObject("Scripting.FileSystemObject");
	} catch(ex) {
		return null;
	}

	var pos = path.lastIndexOf("\\");
	if(pos==-1)
		pos = path.lastIndexOf("/");
	if(pos!=-1)
		path = path.substring(0,pos+1);

	var scan = [path];
	var parent = fso.GetParentFolderName(path);
	while(parent && !fso.FolderExists(parent)) {
		scan.push(parent);
		parent = fso.GetParentFolderName(parent);
	}

	for(i=scan.length-1;i>=0;i--) {
		if(!fso.FolderExists(scan[i])) {
			fso.CreateFolder(scan[i]);
		}
	}
	return true;
}

// Returns null if it can't do it, false if there's an error, true if it saved OK
function ieSaveFile(filePath,content)
{
	ieCreatePath(filePath);
	try {
		var fso = new ActiveXObject("Scripting.FileSystemObject");
	} catch(ex) {
		return null;
	}
	var file = fso.OpenTextFile(filePath,2,-1,0);
	file.Write(content);
	file.Close();
	return true;
}

// Returns null if it can't do it, false if there's an error, or a string of the content if successful
function ieLoadFile(filePath)
{
	try {
		var fso = new ActiveXObject("Scripting.FileSystemObject");
		var file = fso.OpenTextFile(filePath,1);
		var content = file.ReadAll();
		file.Close();
	} catch(ex) {
		return null;
	}
	return content;
}

function ieCopyFile(dest,source)
{
	ieCreatePath(dest);
	try {
		var fso = new ActiveXObject("Scripting.FileSystemObject");
		fso.GetFile(source).Copy(dest);
	} catch(ex) {
		return false;
	}
	return true;
}

// Returns null if it can't do it, false if there's an error, true if it saved OK
function mozillaSaveFile(filePath,content)
{
	if(window.Components) {
		try {
			netscape.security.PrivilegeManager.enablePrivilege("UniversalXPConnect");
			var file = Components.classes["@mozilla.org/file/local;1"].createInstance(Components.interfaces.nsILocalFile);
			file.initWithPath(filePath);
			if(!file.exists())
				file.create(0,0x01B4);// 0x01B4 = 0664
			var out = Components.classes["@mozilla.org/network/file-output-stream;1"].createInstance(Components.interfaces.nsIFileOutputStream);
			out.init(file,0x22,0x04,null);
			out.write(content,content.length);
			out.flush();
			out.close();
			return true;
		} catch(ex) {
			return false;
		}
	}
	return null;
}

// Returns null if it can't do it, false if there's an error, or a string of the content if successful
function mozillaLoadFile(filePath)
{
	if(window.Components) {
		try {
			netscape.security.PrivilegeManager.enablePrivilege("UniversalXPConnect");
			var file = Components.classes["@mozilla.org/file/local;1"].createInstance(Components.interfaces.nsILocalFile);
			file.initWithPath(filePath);
			if(!file.exists())
				return null;
			var inputStream = Components.classes["@mozilla.org/network/file-input-stream;1"].createInstance(Components.interfaces.nsIFileInputStream);
			inputStream.init(file,0x01,0x04,null);
			var sInputStream = Components.classes["@mozilla.org/scriptableinputstream;1"].createInstance(Components.interfaces.nsIScriptableInputStream);
			sInputStream.init(inputStream);
			var contents = sInputStream.read(sInputStream.available());
			sInputStream.close();
			inputStream.close();
			return contents;
		} catch(ex) {
			return false;
		}
	}
	return null;
}

function javaUrlToFilename(url)
{
	var f = "//localhost";
	if(url.indexOf(f) == 0)
		return url.substring(f.length);
	var i = url.indexOf(":");
	return i > 0 ? url.substring(i-1) : url;
}

/*
 *
 * in between when the applet has been started
 * and the user has given permission to run the applet
 * we get an applet object, but it doesn't have the methods
 * we expect yet.
 *
 */
var LOG_TIDDLYSAVER = true;
function logTiddlySaverException(msg, ex) {
	var applet = document.applets['TiddlySaver'];
	console.log(msg + ": " + ex);
	if (LOG_TIDDLYSAVER && applet) {
		try {
			console.log(msg + ": " + applet.getLastErrorMsg());
			console.log(msg + ": " + applet.getLastErrorStackTrace());
		} catch (ex) {}
	}
}

function javaDebugInformation () {
	var applet = document.applets['TiddlySaver'];
	var what = [
		["Java Version", applet.getJavaVersion],
		["Last Exception", applet.getLastErrorMessage],
		["Last Exception Stack Trace", applet.getLastErrorStackTrace],
		["System Properties", applet.getSystemProperties] ];

	function formatItem (description, method) {
		try {
			 result = String(method.call(applet));
		} catch (ex) {
			 result = String(ex)
		}
		return description + ": " + result
	}

	return jQuery.map(what, function (item) { return formatItem.apply(this, item) })
			.join('\n\n')
}

function javaSaveFile(filePath,content)
{
	var applet = document.applets['TiddlySaver'];
	try {
		if (applet && filePath) 
			return applet.saveFile(javaUrlToFilename(filePath), "UTF-8", content);
	} catch(ex) {
		logTiddlySaverException("javaSaveFile", ex);
	}
	// is this next block working anywhere ? -- grmble
	try {
		var s = new java.io.PrintStream(new java.io.FileOutputStream(javaUrlToFilename(filePath)));
		s.print(content);
		s.close();
	} catch(ex2) {
		return null;
	}
	return true;
}

function javaLoadFile(filePath)
{
	var applet = document.applets['TiddlySaver'];
	try {
		if (applet && filePath) {
			var ret = applet.loadFile(javaUrlToFilename(filePath),"UTF-8");
			if(!ret)
				return null;
			return String(ret);
		}
	} catch(ex) {
		logTiddlySaverException("javaLoadFile", ex);
	}
	// is this next block working anywhere ? -- grmble
	var content = [];
	try {
		var r = new java.io.BufferedReader(new java.io.FileReader(javaUrlToFilename(filePath)));
		var line;
		while((line = r.readLine()) != null)
			content.push(String(line));
		r.close();
	} catch(ex2) {
		return null;
	}
	return content.join("\n");
}

function HTML5DownloadSaveFile(filePath,content)
{
	if(document.createElement("a").download !== undefined) {
		config.saveByDownload=true;
		var slashpos=filePath.lastIndexOf("/");
		if (slashpos==-1) slashpos=filePath.lastIndexOf("\\"); 
		var filename=filePath.substr(slashpos+1);
		var uri = getDataURI(content);
		var link = document.createElement("a");
		link.setAttribute("target","_blank");
		link.setAttribute("href",uri);
		link.setAttribute("download",filename);
		document.body.appendChild(link); link.click(); document.body.removeChild(link);
		return true;
	}
	return null;
}

// Returns null if it can't do it, false if there's an error, true if it saved OK
function manualSaveFile(filePath,content)
{
	// FALLBACK for showing a link to data: URI
	config.saveByManualDownload=true;
	var slashpos=filePath.lastIndexOf("/");
	if (slashpos==-1) slashpos=filePath.lastIndexOf("\\"); 
	var filename=filePath.substr(slashpos+1);
	var uri = getDataURI(content);
	displayMessage(config.messages.mainDownloadManual,uri);
	return true;
}

// construct data URI (using base64 encoding to preserve multi-byte encodings)
function getDataURI(data) {
	if (config.browser.isIE)
		return "data:text/html,"+encodeURIComponent(data);
	else
		return "data:text/html;base64,"+encodeBase64(data);
}

function encodeBase64(data) {
	if (!data) return "";
	var keyStr = "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789+/=";
	var out = "";
	var chr1,chr2,chr3="";
	var enc1,enc2,enc3,enc4="";
	for (var count=0,i=0; i<data.length; ) {
		chr1=data.charCodeAt(i++);
		chr2=data.charCodeAt(i++);
		chr3=data.charCodeAt(i++);
		enc1=chr1 >> 2;
		enc2=((chr1 & 3) << 4) | (chr2 >> 4);
		enc3=((chr2 & 15) << 2) | (chr3 >> 6);
		enc4=chr3 & 63;
		if (isNaN(chr2)) enc3=enc4=64;
		else if (isNaN(chr3)) enc4=64;
		out+=keyStr.charAt(enc1)+keyStr.charAt(enc2)+keyStr.charAt(enc3)+keyStr.charAt(enc4);
		chr1=chr2=chr3=enc1=enc2=enc3=enc4="";
	}
	return out;
}//--
//-- Filesystem utilities
//--

function convertUTF8ToUnicode(u)
{
	return config.browser.isOpera || !window.netscape ? manualConvertUTF8ToUnicode(u) : mozConvertUTF8ToUnicode(u);
}


function manualConvertUTF8ToUnicode(utf)
{
	var uni = utf;
	var src = 0;
	var dst = 0;
	var b1, b2, b3;
	var c;
	while(src < utf.length) {
		b1 = utf.charCodeAt(src++);
		if(b1 < 0x80) {
			dst++;
		} else if(b1 < 0xE0) {
			b2 = utf.charCodeAt(src++);
			c = String.fromCharCode(((b1 & 0x1F) << 6) | (b2 & 0x3F));
			uni = uni.substring(0,dst++).concat(c,utf.substr(src));
		} else {
			b2 = utf.charCodeAt(src++);
			b3 = utf.charCodeAt(src++);
			c = String.fromCharCode(((b1 & 0xF) << 12) | ((b2 & 0x3F) << 6) | (b3 & 0x3F));
			uni = uni.substring(0,dst++).concat(c,utf.substr(src));
		}
	}
	return uni;
}

function mozConvertUTF8ToUnicode(u)
{
	try {
		netscape.security.PrivilegeManager.enablePrivilege("UniversalXPConnect");
		var converter = Components.classes["@mozilla.org/intl/scriptableunicodeconverter"].createInstance(Components.interfaces.nsIScriptableUnicodeConverter);
		converter.charset = "UTF-8";
	} catch(ex) {
		return manualConvertUTF8ToUnicode(u);
	} // fallback
	var s = converter.ConvertToUnicode(u);
	var fin = converter.Finish();
	return fin.length > 0 ? s+fin : s;
}

function convertUnicodeToFileFormat(s)
{
	return config.browser.isOpera || !window.netscape ? (config.browser.isIE ? convertUnicodeToHtmlEntities(s) : s) : mozConvertUnicodeToUTF8(s);
}

function convertUnicodeToHtmlEntities(s)
{
	var re = /[^\u0000-\u007F]/g;
	return s.replace(re,function($0) {return "&#" + $0.charCodeAt(0).toString() + ";";});
}

function convertUnicodeToUTF8(s)
{
// return convertUnicodeToFileFormat to allow plugin migration
	return convertUnicodeToFileFormat(s);
}

function manualConvertUnicodeToUTF8(s)
{
	return unescape(encodeURIComponent(s));
}

function mozConvertUnicodeToUTF8(s)
{
	try {
		netscape.security.PrivilegeManager.enablePrivilege("UniversalXPConnect");
		var converter = Components.classes["@mozilla.org/intl/scriptableunicodeconverter"].createInstance(Components.interfaces.nsIScriptableUnicodeConverter);
		converter.charset = "UTF-8";
	} catch(ex) {
		return manualConvertUnicodeToUTF8(s);
	} // fallback
	var u = converter.ConvertFromUnicode(s);
	var fin = converter.Finish();
	return fin.length > 0 ? u + fin : u;
}

function convertUriToUTF8(uri,charSet)
{
	if(window.netscape == undefined || charSet == undefined || charSet == "")
		return uri;
	try {
		netscape.security.PrivilegeManager.enablePrivilege("UniversalXPConnect");
		var converter = Components.classes["@mozilla.org/intl/utf8converterservice;1"].getService(Components.interfaces.nsIUTF8ConverterService);
	} catch(ex) {
		return uri;
	}
	return converter.convertURISpecToUTF8(uri,charSet);
}
//--
//-- Server adaptor base class
//--

function AdaptorBase()
{
	this.host = null;
	this.store = null;
	return this;
}

AdaptorBase.prototype.close = function()
{
	return true;
};

AdaptorBase.prototype.fullHostName = function(host)
{
	if(!host)
		return '';
	host = host.trim();
	if(!host.match(/:\/\//))
		host = 'http://' + host;
	if(host.substr(host.length-1) == '/')
		host = host.substr(0,host.length-1);
	return host;
};

AdaptorBase.minHostName = function(host)
{
	return host;
};

AdaptorBase.prototype.setContext = function(context,userParams,callback)
{
	if(!context) context = {};
	context.userParams = userParams;
	if(callback) context.callback = callback;
	context.adaptor = this;
	if(!context.host)
		context.host = this.host;
	context.host = this.fullHostName(context.host);
	if(!context.workspace)
		context.workspace = this.workspace;
	return context;
};

// Open the specified host
AdaptorBase.prototype.openHost = function(host,context,userParams,callback)
{
	this.host = host;
	context = this.setContext(context,userParams,callback);
	context.status = true;
	if(callback)
		window.setTimeout(function() {context.callback(context,userParams);},10);
	return true;
};

// Open the specified workspace
AdaptorBase.prototype.openWorkspace = function(workspace,context,userParams,callback)
{
	this.workspace = workspace;
	context = this.setContext(context,userParams,callback);
	context.status = true;
	if(callback)
		window.setTimeout(function() {callback(context,userParams);},10);
	return true;
};

//--
//-- Server adaptor for talking to static TiddlyWiki files
//--

function FileAdaptor()
{
}

FileAdaptor.prototype = new AdaptorBase();

FileAdaptor.serverType = 'file';
FileAdaptor.serverLabel = 'TiddlyWiki';

FileAdaptor.loadTiddlyWikiSuccess = function(context,jqXHR)
{
	context.status = true;
	context.adaptor.store = new TiddlyWiki();
	if(!context.adaptor.store.importTiddlyWiki(jqXHR.responseText)) {
		context.statusText = config.messages.invalidFileError.format([context.host]);
		context.status = false;
	}
	context.complete(context,context.userParams);
};

FileAdaptor.loadTiddlyWikiError = function(context,jqXHR)
{
	context.status = false;
	context.statusText = jqXHR.message;
	context.complete(context,context.userParams);
};

// Get the list of workspaces on a given server
FileAdaptor.prototype.getWorkspaceList = function(context,userParams,callback)
{
	context = this.setContext(context,userParams,callback);
	context.workspaces = [{title:"(default)"}];
	context.status = true;
	if(callback)
		window.setTimeout(function() {callback(context,userParams);},10);
	return true;
};

// Gets the list of tiddlers within a given workspace
FileAdaptor.prototype.getTiddlerList = function(context,userParams,callback,filter)
{
	context = this.setContext(context,userParams,callback);
	if(!context.filter)
		context.filter = filter;
	context.complete = FileAdaptor.getTiddlerListComplete;
	if(this.store) {
		return context.complete(context,context.userParams);
	}
	var options = {
		type:"GET",
		url:context.host,
		file:context.file, // for HTML5 FileReader
		processData:false,
		success:function(data,textStatus,jqXHR) {
			FileAdaptor.loadTiddlyWikiSuccess(context,jqXHR);
		},
		error:function(jqXHR,textStatus,errorThrown) {
			context.xhr = jqXHR;
			FileAdaptor.loadTiddlyWikiError(context,jqXHR);
		}
	};
	return ajaxReq(options);
};

FileAdaptor.getTiddlerListComplete = function(context,userParams)
{
	if(context.status) {
		if(context.filter) {
			context.tiddlers = context.adaptor.store.filterTiddlers(context.filter);
		} else {
			context.tiddlers = [];
			context.adaptor.store.forEachTiddler(function(title,tiddler) {context.tiddlers.push(tiddler);});
		}
		var i;
		for(i=0; i<context.tiddlers.length; i++) {
			context.tiddlers[i].fields['server.type'] = FileAdaptor.serverType;
			context.tiddlers[i].fields['server.host'] = AdaptorBase.minHostName(context.host);
			context.tiddlers[i].fields['server.page.revision'] = context.tiddlers[i].modified.convertToYYYYMMDDHHMM();
		}
		context.status = true;
	}
	if(context.callback) {
		window.setTimeout(function() {context.callback(context,userParams);},10);
	}
	return true;
};

FileAdaptor.prototype.generateTiddlerInfo = function(tiddler)
{
	var info = {};
	info.uri = tiddler.fields['server.host'] + "#" + tiddler.title;
	return info;
};

// Retrieve a tiddler from a given workspace on a given server
FileAdaptor.prototype.getTiddler = function(title,context,userParams,callback)
{
	context = this.setContext(context,userParams,callback);
	context.title = title;
	context.complete = FileAdaptor.getTiddlerComplete;
	if(context.adaptor.store) {
		return context.complete(context,context.userParams);
	}
	var options = {
		type:"GET",
		url:context.host,
		processData:false,
		success:function(data,textStatus,jqXHR) {
			FileAdaptor.loadTiddlyWikiSuccess(context,jqXHR);
		},
		error:function(jqXHR,textStatus,errorThrown) {
			FileAdaptor.loadTiddlyWikiError(context,jqXHR);
		}
	};
	return ajaxReq(options);
};

FileAdaptor.getTiddlerComplete = function(context,userParams)
{
	var t = context.adaptor.store.fetchTiddler(context.title);
	if(t) {
		t.fields['server.type'] = FileAdaptor.serverType;
		t.fields['server.host'] = AdaptorBase.minHostName(context.host);
		t.fields['server.page.revision'] = t.modified.convertToYYYYMMDDHHMM();
		context.tiddler = t;
		context.status = true;
	} else { //# tiddler does not exist in document
		context.status = false;
	}
	if(context.allowSynchronous) {
		context.isSynchronous = true;
		context.callback(context,userParams);
	} else {
		window.setTimeout(function() {context.callback(context,userParams);},10);
	}
	return true;
};

FileAdaptor.prototype.close = function()
{
	this.store = null;
};

config.adaptors[FileAdaptor.serverType] = FileAdaptor;

config.defaultAdaptor = FileAdaptor.serverType;

//--
//-- HTTP request code
//--

function ajaxReq(args)
{
	if (args.file || args.url.startsWith("file"))  // LOCAL FILE
		return localAjax(args);
	return jQuery.ajax(args);
}

function localAjax(args)
{
	var success=function(data)
		{ args.success(data,"success",{ responseText:data }); }
	var failure=function(who)
		{ args.error({ message:who+": cannot read local file" },"error",0); }

	if (args.file) try { // HTML5 FileReader (Chrome, FF20+, Safari, etc.)
		var reader=new FileReader();
		reader.onload=function(e)  { success(e.target.result); }
		reader.onerror=function(e) { failure("FileReader"); }
		reader.readAsText(args.file);
		return true;
	} catch (ex) { ; }

	try { // local file I/O (IE, FF with TiddlyFox, Chrome/Safari with TiddlySaver, etc.)
		var data=loadFile(getLocalPath(args.url));
		if (data) success(data);
		else failure("loadFile");
		return true;
	} catch (ex) { ; }

	return true;
}

function httpReq(type,url,callback,params,headers,data,contentType,username,password,allowCache)
{
	var httpSuccess = function(xhr) {
		try {
			// IE error sometimes returns 1223 when it should be 204 so treat it as success, see #1450
			return (!xhr.status && location.protocol === "file:") ||
				(xhr.status >= 200 && xhr.status < 300) ||
				xhr.status === 304 || xhr.status === 1223;
		} catch(e) {}
		return false;
	};

	var options = {
		type:type,
		url:url,
		processData:false,
		data:data,
		cache:!!allowCache,
		beforeSend: function(xhr) {
			var i;
			for(i in headers)
				xhr.setRequestHeader(i,headers[i]);
		}
	};

	if(callback) {
		options.complete = function(xhr,textStatus) {
			if(httpSuccess(xhr))
				callback(true,params,xhr.responseText,url,xhr);
			else
				callback(false,params,null,url,xhr);
		};
	}
	if(contentType)
		options.contentType = contentType;
	if(username)
		options.username = username;
	if(password)
		options.password = password;
	try {
		if(window.Components && window.netscape && window.netscape.security && document.location.protocol.indexOf("http") == -1)
			window.netscape.security.PrivilegeManager.enablePrivilege("UniversalBrowserRead");
	} catch (ex) {
	}
	return jQuery.ajax(options);
}
//--
//-- TiddlyWiki-specific utility functions
//--

// Returns TiddlyWiki version string
function formatVersion(v)
{
	v = v || version;
	return v.major + "." + v.minor + "." + v.revision +
		(v.alpha ? " (alpha " + v.alpha + ")" : "") +
		(v.beta ? " (beta " + v.beta + ")" : "");
}

function compareVersions(v1,v2)
{
	var x1,x2,i,a = ["major","minor","revision"];
	for(i = 0; i<a.length; i++) {
		x1 = v1[a[i]] || 0;
		x2 = v2[a[i]] || 0;
		if(x1<x2)
			return 1;
		if(x1>x2)
			return -1;
	}
	x1 = v1.beta || 9999;
	x2 = v2.beta || 9999;
	if(x1<x2)
		return 1;
	return x1 > x2 ? -1 : 0;
}

function merge(dst,src,preserveExisting)
{
	var i;
	for(i in src) {
		if(!preserveExisting || dst[i] === undefined)
			dst[i] = src[i];
	}
	return dst;
}

// Resolve the target object of an event
function resolveTarget(e)
{
	var obj;
	if(e.target)
		obj = e.target;
	else if(e.srcElement)
		obj = e.srcElement;
	if(obj.nodeType == 3) // defeat Safari bug
		obj = obj.parentNode;
	return obj;
}

// Returns a string containing the description of an exception, optionally prepended by a message
function exceptionText(e,message)
{
	var s = e.description || e.toString();
	return message ? "%0:\n%1".format([message,s]) : s;
}

// Displays an alert of an exception description with optional message
function showException(e,message)
{
	alert(exceptionText(e,message));
}

function alertAndThrow(m)
{
	alert(m);
	throw(m);
}

function glyph(name)
{
	var g = config.glyphs;
	var b = g.currBrowser;
	if(b == null) {
		b = 0;
		while(b < g.browsers.length-1 && !g.browsers[b]())
			b++;
		g.currBrowser = b;
	}
	if(!g.codes[name])
		return "";
	return g.codes[name][b];
}

function createTiddlyText(parent,text)
{
	return parent.appendChild(document.createTextNode(text));
}

function createTiddlyCheckbox(parent,caption,checked,onChange)
{
	var cb = document.createElement("input");
	cb.setAttribute("type","checkbox");
	cb.onclick = onChange;
	parent.appendChild(cb);
	cb.checked = checked;
	cb.className = "chkOptionInput";
	if(caption)
		wikify(caption,parent);
	return cb;
}

function createTiddlyElement(parent,element,id,className,text,attribs)
{
	var n,e = document.createElement(element);
	if(className != null)
		e.className = className;
	if(id != null)
		e.setAttribute("id",id);
	if(text != null)
		e.appendChild(document.createTextNode(text));
	if(attribs) {
		for(n in attribs) {
			e.setAttribute(n,attribs[n]);
		}
	}
	if(parent != null)
		parent.appendChild(e);
	return e;
}

function createTiddlyButton(parent,text,tooltip,action,className,id,accessKey,attribs)
{
	var i,btn = document.createElement("a");
	btn.setAttribute("href","javascript:;");
	if(action) {
		btn.onclick = action;
	}
	if(tooltip)
		btn.setAttribute("title",tooltip);
	if(text)
		btn.appendChild(document.createTextNode(text));
	btn.className = className || "button";
	if(id)
		btn.id = id;
	if(attribs) {
		for(i in attribs) {
			btn.setAttribute(i,attribs[i]);
		}
	}
	if(parent)
		parent.appendChild(btn);
	if(accessKey)
		btn.setAttribute("accessKey",accessKey);
	return btn;
}

function createExternalLink(place,url,label)
{
	var link = document.createElement("a");
	link.className = "externalLink";
	link.href = url;
	var f = config.messages.externalLinkTooltip;
	link.title = f ? f.format([url]) : url;
	if(config.options.chkOpenInNewWindow)
		link.target = "_blank";
	place.appendChild(link);
	if(label)
		createTiddlyText(link, label);
	return link;
}

function getTiddlyLinkInfo(title,currClasses)
{
	var classes = currClasses ? currClasses.split(" ") : [];
	classes.pushUnique("tiddlyLink");
	var tiddler = store.fetchTiddler(title);
	var subTitle;
	if(tiddler) {
		subTitle = tiddler.getSubtitle();
		classes.pushUnique("tiddlyLinkExisting");
		classes.remove("tiddlyLinkNonExisting");
		classes.remove("shadow");
	} else {
	    var f;
		classes.remove("tiddlyLinkExisting");
		classes.pushUnique("tiddlyLinkNonExisting");
		if(store.isShadowTiddler(title)) {
			f = config.messages.shadowedTiddlerToolTip;
			classes.pushUnique("shadow");
		} else {
			f = config.messages.undefinedTiddlerToolTip;
			classes.remove("shadow");
		}
		subTitle = f ? f.format([title]) : "";
	}
	if(typeof config.annotations[title]=="string")
		subTitle = config.annotations[title];
	return {classes: classes.join(" "),subTitle: subTitle};
}

// Event handler for clicking on a tiddly link
function onClickTiddlerLink(ev)
{
	var e = ev || window.event;
	var target = resolveTarget(e);
	var link = target;
	var title = null;
	var fields = null;
	var noToggle = null;
	do {
		title = link.getAttribute("tiddlyLink");
		fields = link.getAttribute("tiddlyFields");
		noToggle = link.getAttribute("noToggle");
		link = link.parentNode;
	} while(title == null && link != null);
	if(!store.isShadowTiddler(title)) {
		var f = fields ? fields.decodeHashMap() : {};
		fields = String.encodeHashMap(merge(f,config.defaultCustomFields,true));
	}
	if(title) {
		var toggling = e.metaKey || e.ctrlKey;
		if(config.options.chkToggleLinks)
			toggling = !toggling;
		if(noToggle)
			toggling = false;
		if(store.getTiddler(title))
			fields = null;
		story.displayTiddler(target,title,null,true,null,fields,toggling);
	}
	clearMessage();
	return false;
}

function createTiddlyLink(place,title,includeText,className,isStatic,linkedFromTiddler,noToggle)
{
	var title = jQuery.trim(title);
	var text = includeText ? title : null;
	var i = getTiddlyLinkInfo(title,className);
	var btn = isStatic ? createExternalLink(place,store.getTiddlerText("SiteUrl",null) + "#" + title) : createTiddlyButton(place,text,i.subTitle,onClickTiddlerLink,i.classes);
	if(isStatic)
		btn.className += ' ' + className;
	btn.setAttribute("refresh","link");
	btn.setAttribute("tiddlyLink",title);
	if(noToggle)
		btn.setAttribute("noToggle","true");
	if(linkedFromTiddler) {
		var fields = linkedFromTiddler.getInheritedFields();
		if(fields)
			btn.setAttribute("tiddlyFields",fields);
	}
	return btn;
}

function refreshTiddlyLink(e,title)
{
	var i = getTiddlyLinkInfo(title,e.className);
	e.className = i.classes;
	e.title = i.subTitle;
}

function createTiddlyDropDown(place,onchange,options,defaultValue)
{
	var sel = createTiddlyElement(place,"select");
	sel.onchange = onchange;
	var t;
	for(t=0; t<options.length; t++) {
		var e = createTiddlyElement(sel,"option",null,null,options[t].caption);
		e.value = options[t].name;
		if(options[t].name == defaultValue)
			e.selected = true;
	}
	return sel;
}

//--
//-- TiddlyWiki-specific popup utility functions
//--

// Event handler for 'open all' on a tiddler popup
function onClickTagOpenAll(ev)
{
	var tiddlers = store.getTaggedTiddlers(this.getAttribute("tag"));
	var sortby = this.getAttribute("sortby");
	if(sortby&&sortby.length) {
		store.sortTiddlers(tiddlers,sortby);
	}
	story.displayTiddlers(this,tiddlers);
	return false;
}

// Event handler for clicking on a tiddler tag
function onClickTag(ev)
{
	var e = ev || window.event;
	var popup = Popup.create(this);
	jQuery(popup).addClass("taggedTiddlerList");
	var tag = this.getAttribute("tag");
	var title = this.getAttribute("tiddler");
	if(popup && tag) {
		var tagged = tag.indexOf("[")==-1 ? store.getTaggedTiddlers(tag) : store.filterTiddlers(tag);
		var sortby = this.getAttribute("sortby");
		if(sortby&&sortby.length) {
			store.sortTiddlers(tagged,sortby);
		}
		var titles = [];
		var r;
		for(r=0;r<tagged.length;r++) {
			if(tagged[r].title != title)
				titles.push(tagged[r].title);
		}
		var lingo = config.views.wikified.tag;
		if(titles.length > 0) {
			var openAll = createTiddlyButton(createTiddlyElement(popup,"li"),lingo.openAllText.format([tag]),lingo.openAllTooltip,onClickTagOpenAll);
			openAll.setAttribute("tag",tag);
			openAll.setAttribute("sortby",sortby);
			createTiddlyElement(createTiddlyElement(popup,"li",null,"listBreak"),"div");
			for(r=0; r<titles.length; r++) {
				createTiddlyLink(createTiddlyElement(popup,"li"),titles[r],true);
			}
		} else {
			createTiddlyElement(popup,"li",null,"disabled",lingo.popupNone.format([tag]));
		}
		createTiddlyElement(createTiddlyElement(popup,"li",null,"listBreak"),"div");
		var h = createTiddlyLink(createTiddlyElement(popup,"li"),tag,false);
		createTiddlyText(h,lingo.openTag.format([tag]));
	}
	Popup.show();
	e.cancelBubble = true;
	if(e.stopPropagation) e.stopPropagation();
	return false;
}

// Create a button for a tag with a popup listing all the tiddlers that it tags
function createTagButton(place,tag,excludeTiddler,title,tooltip)
{
	var btn = createTiddlyButton(place,title||tag,(tooltip||config.views.wikified.tag.tooltip).format([tag]),onClickTag);
	btn.setAttribute("tag",tag);
	if(excludeTiddler)
		btn.setAttribute("tiddler",excludeTiddler);
	return btn;
}

function onClickTiddlyPopup(ev)
{
	var e = ev || window.event;
	var tiddler = this.tiddler;
	if(tiddler.text) {
		var popup = Popup.create(this,"div","popupTiddler");
		wikify(tiddler.text,popup,null,tiddler);
		Popup.show();
	}
	if(e) e.cancelBubble = true;
	if(e && e.stopPropagation) e.stopPropagation();
	return false;
}

function createTiddlyPopup(place,caption,tooltip,tiddler)
{
	if(tiddler.text) {
		createTiddlyLink(place,caption,true);
		var btn = createTiddlyButton(place,glyph("downArrow"),tooltip,onClickTiddlyPopup,"tiddlerPopupButton");
		btn.tiddler = tiddler;
	} else {
		createTiddlyText(place,caption);
	}
}

function onClickError(ev)
{
	var e = ev || window.event;
	var popup = Popup.create(this);
	var lines = this.getAttribute("errorText").split("\n");
	var t;
	for(t=0; t<lines.length; t++)
		createTiddlyElement(popup,"li",null,null,lines[t]);
	Popup.show();
	e.cancelBubble = true;
	if(e.stopPropagation) e.stopPropagation();
	return false;
}

function createTiddlyError(place,title,text)
{
	var btn = createTiddlyButton(place,title,null,onClickError,"errorButton");
	if(text) btn.setAttribute("errorText",text);
}
//-
//- Animation engine
//-

function Animator()
{
	this.running = 0; // Incremented at start of each animation, decremented afterwards. If zero, the interval timer is disabled
	this.timerID = 0; // ID of the timer used for animating
	this.animations = []; // List of animations in progress
	return this;
}

// Start animation engine
Animator.prototype.startAnimating = function() //# Variable number of arguments
{
	var t;
	for(t=0; t<arguments.length; t++)
		this.animations.push(arguments[t]);
	if(this.running == 0) {
		var me = this;
		this.timerID = window.setInterval(function() {me.doAnimate(me);},10);
	}
	this.running += arguments.length;
};

// Perform an animation engine tick, calling each of the known animation modules
Animator.prototype.doAnimate = function(me)
{
	var a = 0;
	while(a < me.animations.length) {
		var animation = me.animations[a];
		if(animation.tick()) {
			a++;
		} else {
			me.animations.splice(a,1);
			if(--me.running == 0)
				window.clearInterval(me.timerID);
		}
	}
};

Animator.slowInSlowOut = function(progress)
{
	return(1-((Math.cos(progress * Math.PI)+1)/2));
};

//--
//-- Morpher animation
//--

// Animate a set of properties of an element
function Morpher(element,duration,properties,callback)
{
	this.element = element;
	this.duration = duration;
	this.properties = properties;
	this.startTime = new Date();
	this.endTime = Number(this.startTime) + duration;
	this.callback = callback;
	this.tick();
	return this;
}

Morpher.prototype.assignStyle = function(element,style,value)
{
	switch(style) {
	case "-tw-vertScroll":
		window.scrollTo(findScrollX(),value);
		break;
	case "-tw-horizScroll":
		window.scrollTo(value,findScrollY());
		break;
	default:
		element.style[style] = value;
		break;
	}
};

Morpher.prototype.stop = function()
{
	var t;
	for(t=0; t<this.properties.length; t++) {
		var p = this.properties[t];
		if(p.atEnd !== undefined) {
			this.assignStyle(this.element,p.style,p.atEnd);
		}
	}
	if(this.callback)
		this.callback(this.element,this.properties);
};

Morpher.prototype.tick = function()
{
	var currTime = Number(new Date());
	var t,progress = Animator.slowInSlowOut(Math.min(1,(currTime-this.startTime)/this.duration));
	for(t=0; t<this.properties.length; t++) {
		var p = this.properties[t];
		if(p.start !== undefined && p.end !== undefined) {
			var template = p.template || "%0";
			switch(p.format) {
			case undefined:
			case "style":
				var v = p.start + (p.end-p.start) * progress;
				this.assignStyle(this.element,p.style,template.format([v]));
				break;
			case "color":
				break;
			}
		}
	}
	if(currTime >= this.endTime) {
		this.stop();
		return false;
	}
	return true;
};

//--
//-- Zoomer animation
//--

function Zoomer(text,startElement,targetElement,unused)
{
	var e = createTiddlyElement(document.body,"div",null,"zoomer");
	createTiddlyElement(e,"div",null,null,text);
	var winWidth = findWindowWidth();
	var winHeight = findWindowHeight();
	var p = [
		{style: 'left', start: findPosX(startElement), end: findPosX(targetElement), template: '%0px'},
		{style: 'top', start: findPosY(startElement), end: findPosY(targetElement), template: '%0px'},
		{style: 'width', start: Math.min(startElement.scrollWidth,winWidth), end: Math.min(targetElement.scrollWidth,winWidth), template: '%0px', atEnd: 'auto'},
		{style: 'height', start: Math.min(startElement.scrollHeight,winHeight), end: Math.min(targetElement.scrollHeight,winHeight), template: '%0px', atEnd: 'auto'},
		{style: 'fontSize', start: 8, end: 24, template: '%0pt'}
	];
	var c = function(element,properties) {jQuery(element).remove();};
	return new Morpher(e,config.animDuration,p,c);
}

//--
//-- Scroller animation
//--

function Scroller(targetElement)
{
	var p = [{style: '-tw-vertScroll', start: findScrollY(), end: ensureVisible(targetElement)}];
	return new Morpher(targetElement,config.animDuration,p);
}

//--
//-- Slider animation
//--

// deleteMode - "none", "all" [delete target element and it's children], [only] "children" [but not the target element]
function Slider(element,opening,unused,deleteMode)
{
	element.style.overflow = 'hidden';
	if(opening)
		element.style.height = '0px'; // Resolves a Firefox flashing bug
	element.style.display = 'block';
	var height = element.scrollHeight;
	var p = [];
	var c = null;
	if(opening) {
		p.push({style: 'height', start: 0, end: height, template: '%0px', atEnd: 'auto'});
		p.push({style: 'opacity', start: 0, end: 1, template: '%0'});
		p.push({style: 'filter', start: 0, end: 100, template: 'alpha(opacity:%0)'});
	} else {
		p.push({style: 'height', start: height, end: 0, template: '%0px'});
		p.push({style: 'display', atEnd: 'none'});
		p.push({style: 'opacity', start: 1, end: 0, template: '%0'});
		p.push({style: 'filter', start: 100, end: 0, template: 'alpha(opacity:%0)'});
		switch(deleteMode) {
		case "all":
			c = function(element,properties) {jQuery(element).remove();};
			break;
		case "children":
			c = function(element,properties) {jQuery(element).empty();};
			break;
		}
	}
	return new Morpher(element,config.animDuration,p,c);
}

//--
//-- Popup menu
//--

var Popup = {
	stack: [] // Array of objects with members root: and popup:
	};

Popup.create = function(root,elem,className)
{
	var stackPosition = this.find(root,"popup");
	Popup.remove(stackPosition+1);
	var popup = createTiddlyElement(document.body,elem || "ol","popup",className || "popup");
	popup.stackPosition = stackPosition;
	Popup.stack.push({root: root, popup: popup});
	return popup;
};

Popup.onDocumentClick = function(ev)
{
	var e = ev || window.event;
	if(e.eventPhase == undefined)
		Popup.remove();
	else if(e.eventPhase == Event.BUBBLING_PHASE || e.eventPhase == Event.AT_TARGET)
		Popup.remove();
	return true;
};

Popup.show = function(valign,halign,offset)
{
	var curr = Popup.stack[Popup.stack.length-1];
	this.place(curr.root,curr.popup,valign,halign,offset);
	jQuery(curr.root).addClass("highlight");
	if(config.options.chkAnimate && anim && typeof Scroller == "function")
		anim.startAnimating(new Scroller(curr.popup));
	else
		window.scrollTo(0,ensureVisible(curr.popup));
};

Popup.place = function(root,popup,valign,halign,offset)
{
	if(!offset)
		offset = {x:0,y:0};
	if(popup.stackPosition >= 0 && !valign && !halign) {
		offset.x = offset.x + root.offsetWidth;
	} else {
		offset.x = (halign == "right") ? offset.x + root.offsetWidth : offset.x;
		offset.y = (valign == "top") ? offset.y : offset.y + root.offsetHeight;
	}
	var rootLeft = findPosX(root);
	var rootTop = findPosY(root);
	var popupLeft = rootLeft + offset.x;
	var popupTop = rootTop + offset.y;
	var winWidth = findWindowWidth();
	if(popup.offsetWidth > winWidth*0.75)
		popup.style.width = winWidth*0.75 + "px";
	var popupWidth = popup.offsetWidth;
	var scrollWidth = winWidth - document.body.offsetWidth;
	if(popupLeft + popupWidth > winWidth - scrollWidth - 1) {
		if(halign == "right")
			popupLeft = popupLeft - root.offsetWidth - popupWidth;
		else
			popupLeft = winWidth - popupWidth - scrollWidth - 1;
	}
	popup.style.left = popupLeft + "px";
	popup.style.top = popupTop + "px";
	popup.style.display = "block";
};

Popup.find = function(e)
{
	var t,pos = -1;
	for(t=this.stack.length-1; t>=0; t--) {
		if(isDescendant(e,this.stack[t].popup))
			pos = t;
	}
	return pos;
};

Popup.remove = function(pos)
{
	if(!pos) pos = 0;
	if(Popup.stack.length > pos) {
		Popup.removeFrom(pos);
	}
};

Popup.removeFrom = function(from)
{
	var t;
	for(t=Popup.stack.length-1; t>=from; t--) {
		var p = Popup.stack[t];
		jQuery(p.root).removeClass("highlight");
		jQuery(p.popup).remove();
	}
	Popup.stack = Popup.stack.slice(0,from);
};

//--
//-- Wizard support
//--

function Wizard(elem)
{
	if(elem) {
		this.formElem = findRelated(elem,"wizard","className");
		this.bodyElem = findRelated(this.formElem.firstChild,"wizardBody","className","nextSibling");
		this.footElem = findRelated(this.formElem.firstChild,"wizardFooter","className","nextSibling");
	} else {
		this.formElem = null;
		this.bodyElem = null;
		this.footElem = null;
	}
}

Wizard.prototype.setValue = function(name,value)
{
	jQuery(this.formElem).data(name, value);
};

Wizard.prototype.getValue = function(name)
{
	return this.formElem ? jQuery(this.formElem).data(name) : null;
};

Wizard.prototype.createWizard = function(place,title)
{
	this.formElem = createTiddlyElement(place,"form",null,"wizard");
	createTiddlyElement(this.formElem,"h1",null,null,title);
	this.bodyElem = createTiddlyElement(this.formElem,"div",null,"wizardBody");
	this.footElem = createTiddlyElement(this.formElem,"div",null,"wizardFooter");
	return this.formElem;
};

Wizard.prototype.clear = function()
{
	jQuery(this.bodyElem).empty();
};

Wizard.prototype.setButtons = function(buttonInfo,status)
{
	jQuery(this.footElem).empty();
	var t;
	for(t=0; t<buttonInfo.length; t++) {
		createTiddlyButton(this.footElem,buttonInfo[t].caption,buttonInfo[t].tooltip,buttonInfo[t].onClick);
		insertSpacer(this.footElem);
		}
	if(typeof status == "string") {
		createTiddlyElement(this.footElem,"span",null,"status",status);
	}
};

Wizard.prototype.addStep = function(stepTitle,html)
{
	jQuery(this.bodyElem).empty();
	var w = createTiddlyElement(this.bodyElem,"div");
	createTiddlyElement(w,"h2",null,null,stepTitle);
	var step = createTiddlyElement(w,"div",null,"wizardStep");
	step.innerHTML = html;
	applyHtmlMacros(step,tiddler);
};

Wizard.prototype.getElement = function(name)
{
	return this.formElem.elements[name];
};

//--
//-- ListView gadget
//--

var ListView = {};

// Create a listview
ListView.create = function(place,listObject,listTemplate,callback,className)
{
	var table = createTiddlyElement(place,"table",null,className || "listView twtable");
	var thead = createTiddlyElement(table,"thead");
	var t,r = createTiddlyElement(thead,"tr");
	for(t=0; t<listTemplate.columns.length; t++) {
		var columnTemplate = listTemplate.columns[t];
		var c = createTiddlyElement(r,"th");
		var colType = ListView.columnTypes[columnTemplate.type];
		if(colType && colType.createHeader) {
			colType.createHeader(c,columnTemplate,t);
			if(columnTemplate.className)
				jQuery(c).addClass(columnTemplate.className);
		}
	}
	var rc,tbody = createTiddlyElement(table,"tbody");
	for(rc=0; rc<listObject.length; rc++) {
		var rowObject = listObject[rc];
		r = createTiddlyElement(tbody,"tr");
		for(c=0; c<listTemplate.rowClasses.length; c++) {
			if(rowObject[listTemplate.rowClasses[c].field])
				jQuery(r).addClass(listTemplate.rowClasses[c].className);
		}
		rowObject.rowElement = r;
		rowObject.colElements = {};
		var cc;
		for(cc=0; cc<listTemplate.columns.length; cc++) {
			c = createTiddlyElement(r,"td");
			columnTemplate = listTemplate.columns[cc];
			var field = columnTemplate.field;
			colType = ListView.columnTypes[columnTemplate.type];
			if(colType && colType.createItem) {
				colType.createItem(c,rowObject,field,columnTemplate,cc,rc);
				if(columnTemplate.className)
					jQuery(c).addClass(columnTemplate.className);
			}
			rowObject.colElements[field] = c;
		}
	}
	if(callback && listTemplate.actions)
		createTiddlyDropDown(place,ListView.getCommandHandler(callback),listTemplate.actions);
	if(callback && listTemplate.buttons) {
		for(t=0; t<listTemplate.buttons.length; t++) {
			var a = listTemplate.buttons[t];
			if(a && a.name != "")
				createTiddlyButton(place,a.caption,null,ListView.getCommandHandler(callback,a.name,a.allowEmptySelection));
		}
	}
	return table;
};

ListView.getCommandHandler = function(callback,name,allowEmptySelection)
{
	return function(e) {
		var view = findRelated(this,"TABLE",null,"previousSibling");
		var tiddlers = [];
		ListView.forEachSelector(view,function(e,rowName) {
					if(e.checked)
						tiddlers.push(rowName);
					});
		if(tiddlers.length == 0 && !allowEmptySelection) {
			alert(config.messages.nothingSelected);
		} else {
			if(this.nodeName.toLowerCase() == "select") {
				callback(view,this.value,tiddlers);
				this.selectedIndex = 0;
			} else {
				callback(view,name,tiddlers);
			}
		}
	};
};

// Invoke a callback for each selector checkbox in the listview
ListView.forEachSelector = function(view,callback)
{
	var checkboxes = view.getElementsByTagName("input");
	var t,hadOne = false;
	for(t=0; t<checkboxes.length; t++) {
		var cb = checkboxes[t];
		if(cb.getAttribute("type") == "checkbox") {
			var rn = cb.getAttribute("rowName");
			if(rn) {
				callback(cb,rn);
				hadOne = true;
			}
		}
	}
	return hadOne;
};

ListView.getSelectedRows = function(view)
{
	var rowNames = [];
	ListView.forEachSelector(view,function(e,rowName) {
				if(e.checked)
					rowNames.push(rowName);
				});
	return rowNames;
};

ListView.columnTypes = {};

ListView.columnTypes.String = {
	createHeader: function(place,columnTemplate,col)
		{
			createTiddlyText(place,columnTemplate.title);
		},
	createItem: function(place,listObject,field,columnTemplate,col,row)
		{
			var v = listObject[field];
			if(v != undefined)
				createTiddlyText(place,v);
		}
};

ListView.columnTypes.WikiText = {
	createHeader: ListView.columnTypes.String.createHeader,
	createItem: function(place,listObject,field,columnTemplate,col,row)
		{
			var v = listObject[field];
			if(v != undefined)
				wikify(v,place,null,null);
		}
};

ListView.columnTypes.Tiddler = {
	createHeader: ListView.columnTypes.String.createHeader,
	createItem: function(place,listObject,field,columnTemplate,col,row)
		{
			var v = listObject[field];
			if(v != undefined && v.title)
				createTiddlyPopup(place,v.title,config.messages.listView.tiddlerTooltip,v);
		}
};

ListView.columnTypes.Size = {
	createHeader: ListView.columnTypes.String.createHeader,
	createItem: function(place,listObject,field,columnTemplate,col,row)
		{
			var msg = config.messages.sizeTemplates;
			var v = listObject[field];
			if(v != undefined) {
				var t = 0;
				while(t<msg.length-1 && v<msg[t].unit)
					t++;
				createTiddlyText(place,msg[t].template.format([Math.round(v/msg[t].unit)]));
			}
		}
};

ListView.columnTypes.Link = {
	createHeader: ListView.columnTypes.String.createHeader,
	createItem: function(place,listObject,field,columnTemplate,col,row)
		{
			var v = listObject[field];
			var c = columnTemplate.text;
			if(v != undefined)
				createExternalLink(place,v,c || v);
		}
};

ListView.columnTypes.Date = {
	createHeader: ListView.columnTypes.String.createHeader,
	createItem: function(place,listObject,field,columnTemplate,col,row)
		{
			var v = listObject[field];
			if(v != undefined)
				createTiddlyText(place,v.formatString(columnTemplate.dateFormat));
		}
};

ListView.columnTypes.StringList = {
	createHeader: ListView.columnTypes.String.createHeader,
	createItem: function(place,listObject,field,columnTemplate,col,row)
		{
			var v = listObject[field];
			if(v != undefined) {
				var t;
				for(t=0; t<v.length; t++) {
					createTiddlyText(place,v[t]);
					createTiddlyElement(place,"br");
				}
			}
		}
};

ListView.columnTypes.Selector = {
	createHeader: function(place,columnTemplate,col)
		{
			createTiddlyCheckbox(place,null,false,this.onHeaderChange);
		},
	createItem: function(place,listObject,field,columnTemplate,col,row)
		{
			var e = createTiddlyCheckbox(place,null,listObject[field],null);
			e.setAttribute("rowName",listObject[columnTemplate.rowName]);
		},
	onHeaderChange: function(e)
		{
			var state = this.checked;
			var view = findRelated(this,"TABLE");
			if(!view)
				return;
			ListView.forEachSelector(view,function(e,rowName) {
								e.checked = state;
							});
		}
};

ListView.columnTypes.Tags = {
	createHeader: ListView.columnTypes.String.createHeader,
	createItem: function(place,listObject,field,columnTemplate,col,row)
		{
			var tags = listObject[field];
			createTiddlyText(place,String.encodeTiddlyLinkList(tags));
		}
};

ListView.columnTypes.Boolean = {
	createHeader: ListView.columnTypes.String.createHeader,
	createItem: function(place,listObject,field,columnTemplate,col,row)
		{
			if(listObject[field] == true)
				createTiddlyText(place,columnTemplate.trueText);
			if(listObject[field] == false)
				createTiddlyText(place,columnTemplate.falseText);
		}
};

ListView.columnTypes.TagCheckbox = {
	createHeader: ListView.columnTypes.String.createHeader,
	createItem: function(place,listObject,field,columnTemplate,col,row)
		{
			var e = createTiddlyCheckbox(place,null,listObject[field],this.onChange);
			e.setAttribute("tiddler",listObject.title);
			e.setAttribute("tag",columnTemplate.tag);
		},
	onChange : function(e)
		{
			var tag = this.getAttribute("tag");
			var tiddler = this.getAttribute("tiddler");
			store.setTiddlerTag(tiddler,this.checked,tag);
		}
};

ListView.columnTypes.TiddlerLink = {
	createHeader: ListView.columnTypes.String.createHeader,
	createItem: function(place,listObject,field,columnTemplate,col,row)
		{
			var v = listObject[field];
			if(v != undefined) {
				var link = createTiddlyLink(place,listObject[columnTemplate.tiddlerLink],false,null);
				createTiddlyText(link,listObject[field]);
			}
		}
};

//--
//-- Augmented methods for the JavaScript Array() object
//--

// Add indexOf function if browser does not support it
if(!Array.indexOf) {
Array.prototype.indexOf = function(item,from)
{
	if(!from)
		from = 0;
	var i;
	for(i=from; i<this.length; i++) {
		if(this[i] === item)
			return i;
	}
	return -1;
};}

// Find an entry in a given field of the members of an array
Array.prototype.findByField = function(field,value)
{
	var t;
	for(t=0; t<this.length; t++) {
		if(this[t][field] === value)
			return t;
	}
	return null;
};

// Return whether an entry exists in an array
Array.prototype.contains = function(item)
{
	return this.indexOf(item) != -1;
};

// Adds, removes or toggles a particular value within an array
//  value - value to add
//  mode - +1 to add value, -1 to remove value, 0 to toggle it
Array.prototype.setItem = function(value,mode)
{
	var p = this.indexOf(value);
	if(mode == 0)
		mode = (p == -1) ? +1 : -1;
	if(mode == +1) {
		if(p == -1)
			this.push(value);
	} else if(mode == -1) {
		if(p != -1)
			this.splice(p,1);
	}
};

// Return whether one of a list of values exists in an array
Array.prototype.containsAny = function(items)
{
	var i;
	for(i=0; i<items.length; i++) {
		if(this.indexOf(items[i]) != -1)
			return true;
	}
	return false;
};

// Return whether all of a list of values exists in an array
Array.prototype.containsAll = function(items)
{
	var i;
	for(i = 0; i<items.length; i++) {
		if(this.indexOf(items[i]) == -1)
			return false;
	}
	return true;
};

// Push a new value into an array only if it is not already present in the array. If the optional unique parameter is false, it reverts to a normal push
Array.prototype.pushUnique = function(item,unique)
{
	if(unique === false) {
		this.push(item);
	} else {
		if(this.indexOf(item) == -1)
			this.push(item);
	}
};

Array.prototype.remove = function(item)
{
	var p = this.indexOf(item);
	if(p != -1)
		this.splice(p,1);
};

if(!Array.prototype.map) {
Array.prototype.map = function(fn,thisObj)
{
	var scope = thisObj || window;
	var i,j,a = [];
	for(i=0, j=this.length; i < j; ++i) {
		a.push(fn.call(scope,this[i],i,this));
	}
	return a;
};}

//--
//-- Augmented methods for the JavaScript String() object
//--

// Get characters from the right end of a string
String.prototype.right = function(n)
{
	return n < this.length ? this.slice(this.length-n) : this;
};

// Trim whitespace from both ends of a string
String.prototype.trim = function()
{
	return this.replace(/^\s*|\s*$/g,"");
};

// Convert a string from a CSS style property name to a JavaScript style name ("background-color" -> "backgroundColor")
String.prototype.unDash = function()
{
	var t,s = this.split("-");
	if(s.length > 1) {
		for(t=1; t<s.length; t++)
			s[t] = s[t].substr(0,1).toUpperCase() + s[t].substr(1);
	}
	return s.join("");
};

// Substitute substrings from an array into a format string that includes '%1'-type specifiers
String.prototype.format = function(s)
{
	var substrings = s && s.constructor == Array ? s : arguments;
	var subRegExp = /(?:%(\d+))/mg;
	var currPos = 0;
	var match,r = [];
	do {
		match = subRegExp.exec(this);
		if(match && match[1]) {
			if(match.index > currPos)
				r.push(this.substring(currPos,match.index));
			r.push(substrings[parseInt(match[1],10)]);
			currPos = subRegExp.lastIndex;
		}
	} while(match);
	if(currPos < this.length)
		r.push(this.substring(currPos,this.length));
	return r.join("");
};

// Escape any special RegExp characters with that character preceded by a backslash
String.prototype.escapeRegExp = function()
{
	var s = "\\^$*+?()=!|,{}[].";
	var t,c = this;
	for(t=0; t<s.length; t++)
		c = c.replace(new RegExp("\\" + s.substr(t,1),"g"),"\\" + s.substr(t,1));
	return c;
};

// Convert "\" to "\s", newlines to "\n" (and remove carriage returns)
String.prototype.escapeLineBreaks = function()
{
	return this.replace(/\\/mg,"\\s").replace(/\n/mg,"\\n").replace(/\r/mg,"");
};

// Convert "\n" to newlines, "\b" to " ", "\s" to "\" (and remove carriage returns)
String.prototype.unescapeLineBreaks = function()
{
	return this.replace(/\\n/mg,"\n").replace(/\\b/mg," ").replace(/\\s/mg,"\\").replace(/\r/mg,"");
};

// Convert & to "&amp;", < to "&lt;", > to "&gt;" and " to "&quot;"
String.prototype.htmlEncode = function()
{
	return this.replace(/&/mg,"&amp;").replace(/</mg,"&lt;").replace(/>/mg,"&gt;").replace(/\"/mg,"&quot;");
};

// Convert "&amp;" to &, "&lt;" to <, "&gt;" to > and "&quot;" to "
String.prototype.htmlDecode = function()
{
	return this.replace(/&lt;/mg,"<").replace(/&gt;/mg,">").replace(/&quot;/mg,"\"").replace(/&amp;/mg,"&");
};

// Parse a space-separated string of name:value parameters
// The result is an array of objects:
//   result[0] = object with a member for each parameter name, value of that member being an array of values
//   result[1..n] = one object for each parameter, with 'name' and 'value' members
String.prototype.parseParams = function(defaultName,defaultValue,allowEval,noNames,cascadeDefaults)
{
	var parseToken = function(match,p) {
		var n;
		if(match[p]) // Double quoted
			n = match[p];
		else if(match[p+1]) // Single quoted
			n = match[p+1];
		else if(match[p+2]) // Double-square-bracket quoted
			n = match[p+2];
		else if(match[p+3]) // Double-brace quoted
			try {
				n = match[p+3];
				if(allowEval && config.evaluateMacroParameters != "none") {
					if(config.evaluateMacroParameters == "restricted") {
						if(window.restrictedEval) {
							n = window.restrictedEval(n);
						}
					} else {
						n = window.eval(n);
					}
				}
			} catch(ex) {
				throw "Unable to evaluate {{" + match[p+3] + "}}: " + exceptionText(ex);
			}
		else if(match[p+4]) // Unquoted
			n = match[p+4];
		else if(match[p+5]) // empty quote
			n = "";
		return n;
	};
	var r = [{}];
	var dblQuote = "(?:\"((?:(?:\\\\\")|[^\"])+)\")";
	var sngQuote = "(?:'((?:(?:\\\\\')|[^'])+)')";
	var dblSquare = "(?:\\[\\[((?:\\s|\\S)*?)\\]\\])";
	var dblBrace = "(?:\\{\\{((?:\\s|\\S)*?)\\}\\})";
	var unQuoted = noNames ? "([^\"'\\s]\\S*)" : "([^\"':\\s][^\\s:]*)";
	var emptyQuote = "((?:\"\")|(?:''))";
	var skipSpace = "(?:\\s*)";
	var token = "(?:" + dblQuote + "|" + sngQuote + "|" + dblSquare + "|" + dblBrace + "|" + unQuoted + "|" + emptyQuote + ")";
	var re = noNames ? new RegExp(token,"mg") : new RegExp(skipSpace + token + skipSpace + "(?:(\\:)" + skipSpace + token + ")?","mg");
	var match;
	do {
		match = re.exec(this);
		if(match) {
			var n = parseToken(match,1);
			if(noNames) {
				r.push({name:"",value:n});
			} else {
				var v = parseToken(match,8);
				if(v == null && defaultName) {
					v = n;
					n = defaultName;
				} else if(v == null && defaultValue) {
					v = defaultValue;
				}
				r.push({name:n,value:v});
				if(cascadeDefaults) {
					defaultName = n;
					defaultValue = v;
				}
			}
		}
	} while(match);
	// Summarise parameters into first element
	var t;
	for(t=1; t<r.length; t++) {
		if(r[0][r[t].name])
			r[0][r[t].name].push(r[t].value);
		else
			r[0][r[t].name] = [r[t].value];
	}
	return r;
};

// Process a string list of macro parameters into an array. Parameters can be quoted with "", '',
// [[]], {{ }} or left unquoted (and therefore space-separated). Double-braces {{}} results in
// an *evaluated* parameter: e.g. {{config.options.txtUserName}} results in the current user's name.
String.prototype.readMacroParams = function(notAllowEval)
{
	var p = this.parseParams("list",null,!notAllowEval,true);
	var t,n = [];
	for(t=1; t<p.length; t++)
		n.push(p[t].value);
	return n;
};

// Process a string list of unique tiddler names into an array. Tiddler names that have spaces in them must be [[bracketed]]
String.prototype.readBracketedList = function(unique)
{
	var p = this.parseParams("list",null,false,true);
	var t,n = [];
	for(t=1; t<p.length; t++) {
		if(p[t].value)
			n.pushUnique(p[t].value,unique);
	}
	return n;
};

// Returns array with start and end index of chunk between given start and end marker, or undefined.
String.prototype.getChunkRange = function(start,end)
{
	var s = this.indexOf(start);
	if(s != -1) {
		s += start.length;
		var e = this.indexOf(end,s);
		if(e != -1)
			return [s,e];
	}
};

// Replace a chunk of a string given start and end markers
String.prototype.replaceChunk = function(start,end,sub)
{
	var r = this.getChunkRange(start,end);
	return r ? this.substring(0,r[0]) + sub + this.substring(r[1]) : this;
};

// Returns a chunk of a string between start and end markers, or undefined
String.prototype.getChunk = function(start,end)
{
	var r = this.getChunkRange(start,end);
	if(r)
		return this.substring(r[0],r[1]);
};


// Static method to bracket a string with double square brackets if it contains a space
String.encodeTiddlyLink = function(title)
{
	return title.indexOf(" ") == -1 ? title : "[[" + title + "]]";
};

// Static method to encodeTiddlyLink for every item in an array and join them with spaces
String.encodeTiddlyLinkList = function(list)
{
	if(list) {
		var t,results = [];
		for(t=0; t<list.length; t++)
			results.push(String.encodeTiddlyLink(list[t]));
		return results.join(" ");
	} else {
		return "";
	}
};

// Convert a string as a sequence of name:"value" pairs into a hashmap
String.prototype.decodeHashMap = function()
{
	var fields = this.parseParams("anon","",false);
	var t,r = {};
	for(t=1; t<fields.length; t++)
		r[fields[t].name] = fields[t].value;
	return r;
};

// Static method to encode a hashmap into a name:"value"... string
String.encodeHashMap = function(hashmap)
{
	var t,r = [];
	for(t in hashmap)
		r.push(t + ':"' + hashmap[t] + '"');
	return r.join(" ");
};

// Static method to left-pad a string with 0s to a certain width
String.zeroPad = function(n,d)
{
	var s = n.toString();
	if(s.length < d)
		s = "000000000000000000000000000".substr(0,d-s.length) + s;
	return s;
};

String.prototype.startsWith = function(prefix)
{
	return !prefix || this.substring(0,prefix.length) == prefix;
};

// Returns the first value of the given named parameter.
function getParam(params,name,defaultValue)
{
	if(!params)
		return defaultValue;
	var p = params[0][name];
	return p ? p[0] : defaultValue;
}

// Returns the first value of the given boolean named parameter.
function getFlag(params,name,defaultValue)
{
	return !!getParam(params,name,defaultValue);
}

//--
//-- Augmented methods for the JavaScript Date() object
//--

// Substitute date components into a string
Date.prototype.formatString = function(template)
{
	var t = template.replace(/0hh12/g,String.zeroPad(this.getHours12(),2));
	t = t.replace(/hh12/g,this.getHours12());
	t = t.replace(/0hh/g,String.zeroPad(this.getHours(),2));
	t = t.replace(/hh/g,this.getHours());
	t = t.replace(/mmm/g,config.messages.dates.shortMonths[this.getMonth()]);
	t = t.replace(/0mm/g,String.zeroPad(this.getMinutes(),2));
	t = t.replace(/mm/g,this.getMinutes());
	t = t.replace(/0ss/g,String.zeroPad(this.getSeconds(),2));
	t = t.replace(/ss/g,this.getSeconds());
	t = t.replace(/[ap]m/g,this.getAmPm().toLowerCase());
	t = t.replace(/[AP]M/g,this.getAmPm().toUpperCase());
	t = t.replace(/wYYYY/g,this.getYearForWeekNo());
	t = t.replace(/wYY/g,String.zeroPad(this.getYearForWeekNo()-2000,2));
	t = t.replace(/YYYY/g,this.getFullYear());
	t = t.replace(/YY/g,String.zeroPad(this.getFullYear()-2000,2));
	t = t.replace(/MMM/g,config.messages.dates.months[this.getMonth()]);
	t = t.replace(/0MM/g,String.zeroPad(this.getMonth()+1,2));
	t = t.replace(/MM/g,this.getMonth()+1);
	t = t.replace(/0WW/g,String.zeroPad(this.getWeek(),2));
	t = t.replace(/WW/g,this.getWeek());
	t = t.replace(/DDD/g,config.messages.dates.days[this.getDay()]);
	t = t.replace(/ddd/g,config.messages.dates.shortDays[this.getDay()]);
	t = t.replace(/0DD/g,String.zeroPad(this.getDate(),2));
	t = t.replace(/DDth/g,this.getDate()+this.daySuffix());
	t = t.replace(/DD/g,this.getDate());
	var tz = this.getTimezoneOffset();
	var atz = Math.abs(tz);
	t = t.replace(/TZD/g,(tz < 0 ? '+' : '-') + String.zeroPad(Math.floor(atz / 60),2) + ':' + String.zeroPad(atz % 60,2));
	t = t.replace(/\\/g,"");
	return t;
};

Date.prototype.getWeek = function()
{
	var dt = new Date(this.getTime());
	var d = dt.getDay();
	if(d==0) d=7;// JavaScript Sun=0, ISO Sun=7
	dt.setTime(dt.getTime()+(4-d)*86400000);// shift day to Thurs of same week to calculate weekNo
	var n = Math.floor((dt.getTime()-new Date(dt.getFullYear(),0,1)+3600000)/86400000);
	return Math.floor(n/7)+1;
};

Date.prototype.getYearForWeekNo = function()
{
	var dt = new Date(this.getTime());
	var d = dt.getDay();
	if(d==0) d=7;// JavaScript Sun=0, ISO Sun=7
	dt.setTime(dt.getTime()+(4-d)*86400000);// shift day to Thurs of same week
	return dt.getFullYear();
};

Date.prototype.getHours12 = function()
{
	var h = this.getHours();
	return h > 12 ? h-12 : ( h > 0 ? h : 12 );
};

Date.prototype.getAmPm = function()
{
	return this.getHours() >= 12 ? config.messages.dates.pm : config.messages.dates.am;
};

Date.prototype.daySuffix = function()
{
	return config.messages.dates.daySuffixes[this.getDate()-1];
};

// Convert a date to local YYYYMMDDHHMM string format
Date.prototype.convertToLocalYYYYMMDDHHMM = function()
{
	return this.getFullYear() + String.zeroPad(this.getMonth()+1,2) + String.zeroPad(this.getDate(),2) + String.zeroPad(this.getHours(),2) + String.zeroPad(this.getMinutes(),2);
};

// Convert a date to UTC YYYYMMDDHHMM string format
Date.prototype.convertToYYYYMMDDHHMM = function()
{
	return this.getUTCFullYear() + String.zeroPad(this.getUTCMonth()+1,2) + String.zeroPad(this.getUTCDate(),2) + String.zeroPad(this.getUTCHours(),2) + String.zeroPad(this.getUTCMinutes(),2);
};

// Convert a date to UTC YYYYMMDD.HHMMSSMMM string format
Date.prototype.convertToYYYYMMDDHHMMSSMMM = function()
{
	return this.getUTCFullYear() + String.zeroPad(this.getUTCMonth()+1,2) + String.zeroPad(this.getUTCDate(),2) + "." + String.zeroPad(this.getUTCHours(),2) + String.zeroPad(this.getUTCMinutes(),2) + String.zeroPad(this.getUTCSeconds(),2) + String.zeroPad(this.getUTCMilliseconds(),3) +"0";
};

// Static method to create a date from a UTC YYYYMMDDHHMM format string
Date.convertFromYYYYMMDDHHMM = function(d)
{
	d = d?d.replace(/[^0-9]/g, ""):"";
	return Date.convertFromYYYYMMDDHHMMSSMMM(d.substr(0,12));
};

// Static method to create a date from a UTC YYYYMMDDHHMMSS format string
Date.convertFromYYYYMMDDHHMMSS = function(d)
{
	d = d?d.replace(/[^0-9]/g, ""):"";
	return Date.convertFromYYYYMMDDHHMMSSMMM(d.substr(0,14));
};

// Static method to create a date from a UTC YYYYMMDDHHMMSSMMM format string
Date.convertFromYYYYMMDDHHMMSSMMM = function(d)
{
	d = d ? d.replace(/[^0-9]/g, "") : "";
	return new Date(Date.UTC(parseInt(d.substr(0,4),10),
			parseInt(d.substr(4,2),10)-1,
			parseInt(d.substr(6,2),10),
			parseInt(d.substr(8,2)||"00",10),
			parseInt(d.substr(10,2)||"00",10),
			parseInt(d.substr(12,2)||"00",10),
			parseInt(d.substr(14,3)||"000",10)));
};

//--
//-- RGB colour object
//--

// Construct an RGB colour object from a '#rrggbb', '#rgb' or 'rgb(n,n,n)' string or from separate r,g,b values
function RGB(r,g,b)
{
	this.r = 0;
	this.g = 0;
	this.b = 0;
	if(typeof r == "string") {
		if(r.substr(0,1) == "#") {
			if(r.length == 7) {
				this.r = parseInt(r.substr(1,2),16)/255;
				this.g = parseInt(r.substr(3,2),16)/255;
				this.b = parseInt(r.substr(5,2),16)/255;
			} else {
				this.r = parseInt(r.substr(1,1),16)/15;
				this.g = parseInt(r.substr(2,1),16)/15;
				this.b = parseInt(r.substr(3,1),16)/15;
			}
		} else {
			var rgbPattern = /rgb\s*\(\s*(\d{1,3})\s*,\s*(\d{1,3})\s*,\s*(\d{1,3})\s*\)/;
			var c = r.match(rgbPattern);
			if(c) {
				this.r = parseInt(c[1],10)/255;
				this.g = parseInt(c[2],10)/255;
				this.b = parseInt(c[3],10)/255;
			}
		}
	} else {
		this.r = r;
		this.g = g;
		this.b = b;
	}
	return this;
}

// Mixes this colour with another in a specified proportion
// c = other colour to mix
// f = 0..1 where 0 is this colour and 1 is the new colour
// Returns an RGB object
RGB.prototype.mix = function(c,f)
{
	return new RGB(this.r + (c.r-this.r) * f,this.g + (c.g-this.g) * f,this.b + (c.b-this.b) * f);
};

// Return an rgb colour as a #rrggbb format hex string
RGB.prototype.toString = function()
{
	var clamp = function(x,min,max) {
		return x < min ? min : (x > max ? max : x);
	};
	return "#" +
			("0" + Math.floor(clamp(this.r,0,1) * 255).toString(16)).right(2) +
			("0" + Math.floor(clamp(this.g,0,1) * 255).toString(16)).right(2) +
			("0" + Math.floor(clamp(this.b,0,1) * 255).toString(16)).right(2);
};

//--
//-- DOM utilities - many derived from www.quirksmode.org
//--

function drawGradient(place,horiz,locolors,hicolors)
{
	if(!hicolors)
		hicolors = locolors;
	var t;
	for(t=0; t<= 100; t+=2) {
		var bar = document.createElement("div");
		place.appendChild(bar);
		bar.style.position = "absolute";
		bar.style.left = horiz ? t + "%" : 0;
		bar.style.top = horiz ? 0 : t + "%";
		bar.style.width = horiz ? (101-t) + "%" : "100%";
		bar.style.height = horiz ? "100%" : (101-t) + "%";
		bar.style.zIndex = -1;
		var p = t/100*(locolors.length-1);
		var hc = hicolors[Math.floor(p)];
		if(typeof hc == "string")
			hc = new RGB(hc);
		var lc = locolors[Math.ceil(p)];
		if(typeof lc == "string")
			lc = new RGB(lc);
		bar.style.backgroundColor = hc.mix(lc,p-Math.floor(p)).toString();
	}
}

function addEvent(obj,type,fn)
{
	if(obj.attachEvent) {
		obj["e"+type+fn] = fn;
		obj[type+fn] = function(){obj["e"+type+fn](window.event);};
		obj.attachEvent("on"+type,obj[type+fn]);
	} else {
		obj.addEventListener(type,fn,false);
	}
}

function removeEvent(obj,type,fn)
{
	if(obj.detachEvent) {
		obj.detachEvent("on"+type,obj[type+fn]);
		obj[type+fn] = null;
	} else {
		obj.removeEventListener(type,fn,false);
	}
}

// Find the closest relative with a given property value (property defaults to tagName, relative defaults to parentNode)
function findRelated(e,value,name,relative)
{
	name = name || "tagName";
	relative = relative || "parentNode";
	if(name == "className") {
		while(e && !jQuery(e).hasClass(value)) {
			e = e[relative];
		}
	} else {
		while(e && e[name] != value) {
			e = e[relative];
		}
	}
	return e;
}

// Get the scroll position for window.scrollTo necessary to scroll a given element into view
function ensureVisible(e)
{
	var posTop = findPosY(e);
	var posBot = posTop + e.offsetHeight;
	var winTop = findScrollY();
	var winHeight = findWindowHeight();
	var winBot = winTop + winHeight;
	if(posTop < winTop) {
		return posTop;
	} else if(posBot > winBot) {
		if(e.offsetHeight < winHeight)
			return posTop - (winHeight - e.offsetHeight);
		else
			return posTop;
	} else {
		return winTop;
	}
}

// Get the current width of the display window
function findWindowWidth()
{
	return window.innerWidth || document.documentElement.clientWidth;
}

// Get the current height of the display window
function findWindowHeight()
{
	return window.innerHeight || document.documentElement.clientHeight;
}

// Get the current height of the document
function findDocHeight() {
    var D = document;
    return Math.max(
        Math.max(D.body.scrollHeight, D.documentElement.scrollHeight),
        Math.max(D.body.offsetHeight, D.documentElement.offsetHeight),
        Math.max(D.body.clientHeight, D.documentElement.clientHeight)
    );
}

// Get the current horizontal page scroll position
function findScrollX()
{
	return window.scrollX || document.documentElement.scrollLeft;
}

// Get the current vertical page scroll position
function findScrollY()
{
	return window.scrollY || document.documentElement.scrollTop;
}

function findPosX(obj)
{
	var curleft = 0;
	while(obj.offsetParent) {
		curleft += obj.offsetLeft;
		obj = obj.offsetParent;
	}
	return curleft;
}

function findPosY(obj)
{
	var curtop = 0;
	while(obj.offsetParent) {
		curtop += obj.offsetTop;
		obj = obj.offsetParent;
	}
	return curtop;
}

// Blur a particular element
function blurElement(e)
{
	if(e && e.focus && e.blur) {
		e.focus();
		e.blur();
	}
}

// Create a non-breaking space
function insertSpacer(place)
{
	var e = document.createTextNode(String.fromCharCode(160));
	if(place)
		place.appendChild(e);
	return e;
}

// Replace the current selection of a textarea or text input and scroll it into view
function replaceSelection(e,text)
{
	if(e.setSelectionRange) {
		var oldpos = e.selectionStart;
		var isRange = e.selectionEnd > e.selectionStart;
		e.value = e.value.substr(0,e.selectionStart) + text + e.value.substr(e.selectionEnd);
		e.setSelectionRange(isRange ? oldpos : oldpos + text.length,oldpos + text.length);
		var linecount = e.value.split("\n").length;
		var thisline = e.value.substr(0,e.selectionStart).split("\n").length-1;
		e.scrollTop = Math.floor((thisline - e.rows / 2) * e.scrollHeight / linecount);
	} else if(document.selection) {
		var range = document.selection.createRange();
		if(range.parentElement() == e) {
			var isCollapsed = range.text == "";
			range.text = text;
			if(!isCollapsed) {
				range.moveStart("character", -text.length);
				range.select();
			}
		}
	}
}

// Set the caret position in a text area
function setCaretPosition(e,pos)
{
	if(e.selectionStart || e.selectionStart == '0') {
		e.selectionStart = pos;
		e.selectionEnd = pos;
		e.focus();
	} else if(document.selection) {
		// IE support
		e.focus ();
		var sel = document.selection.createRange();
		sel.moveStart('character', -e.value.length);
		sel.moveStart('character',pos);
		sel.moveEnd('character',0);
		sel.select();
	}
}

// Returns the text of the given (text) node, possibly merging subsequent text nodes
function getNodeText(e)
{
	var t = "";
	while(e && e.nodeName == "#text") {
		t += e.nodeValue;
		e = e.nextSibling;
	}
	return t;
}

// Returns true if the element e has a given ancestor element
function isDescendant(e,ancestor)
{
	while(e) {
		if(e === ancestor)
			return true;
		e = e.parentNode;
	}
	return false;
}


// deprecate the following...

// Prevent an event from bubbling
function stopEvent(e)
{
	var ev = e || window.event;
	ev.cancelBubble = true;
	if(ev.stopPropagation) ev.stopPropagation();
	return false;
}

// Remove any event handlers or non-primitve custom attributes
function scrubNode(e)
{
	if(!config.browser.isIE)
		return;
	var att = e.attributes;
	if(att) {
		var t;
		for(t=0; t<att.length; t++) {
			var n = att[t].name;
			if(n !== "style" && (typeof e[n] === "function" || (typeof e[n] === "object" && e[n] != null))) {
				try {
					e[n] = null;
				} catch(ex) {
				}
			}
		}
	}
	var c = e.firstChild;
	while(c) {
		scrubNode(c);
		c = c.nextSibling;
	}
}

function setStylesheet(s,id,doc)
{
	jQuery.twStylesheet(s,{id:id,doc:doc});
}

function removeStyleSheet(id)
{
	jQuery.twStylesheet.remove({id:id});
}

//--
//-- LoaderBase and SaverBase
//--

function LoaderBase() {}

LoaderBase.prototype.loadTiddler = function(store,node,tiddlers)
{
	var title = this.getTitle(store,node);
	if(safeMode && store.isShadowTiddler(title))
		return;
	if(title) {
		var tiddler = store.createTiddler(title);
		this.internalizeTiddler(store,tiddler,title,node);
		tiddlers.push(tiddler);
	}
};

LoaderBase.prototype.loadTiddlers = function(store,nodes)
{
	var t,tiddlers = [];
	for(t = 0; t < nodes.length; t++) {
		try {
			this.loadTiddler(store,nodes[t],tiddlers);
		} catch(ex) {
			showException(ex,config.messages.tiddlerLoadError.format([this.getTitle(store,nodes[t])]));
		}
	}
	return tiddlers;
};

function SaverBase() {}

SaverBase.prototype.externalize = function(store)
{
	var results = [];
	var t,tiddlers = store.getTiddlers("title");
	for(t = 0; t < tiddlers.length; t++) {
		if(!tiddlers[t].doNotSave())
			results.push(this.externalizeTiddler(store, tiddlers[t]));
	}
	return results.join("\n");
};

//--
//-- TW21Loader (inherits from LoaderBase)
//--

function TW21Loader() {}

TW21Loader.prototype = new LoaderBase();

TW21Loader.prototype.getTitle = function(store,node)
{
	var title = null;
	if(node.getAttribute) {
		title = node.getAttribute("title");
		if(!title)
			title = node.getAttribute("tiddler");
	}
	if(!title && node.id) {
		var lenPrefix = store.idPrefix.length;
		if(node.id.substr(0,lenPrefix) == store.idPrefix)
			title = node.id.substr(lenPrefix);
	}
	return title;
};

TW21Loader.prototype.internalizeTiddler = function(store,tiddler,title,node)
{
	var e = node.firstChild;
	var text = null;
	if(node.getAttribute("tiddler")) {
		text = getNodeText(e).unescapeLineBreaks();
	} else {
		while(e.nodeName!="PRE" && e.nodeName!="pre") {
			e = e.nextSibling;
		}
		text = e.innerHTML.replace(/\r/mg,"").htmlDecode();
	}
	var creator = node.getAttribute("creator");
	var modifier = node.getAttribute("modifier");
	var c = node.getAttribute("created");
	var m = node.getAttribute("modified");
	var created = c ? Date.convertFromYYYYMMDDHHMMSS(c) : version.date;
	var modified = m ? Date.convertFromYYYYMMDDHHMMSS(m) : created;
	var tags = node.getAttribute("tags");
	var fields = {};
	var i,attrs = node.attributes;
	for(i = attrs.length-1; i >= 0; i--) {
		var name = attrs[i].name;
		if(attrs[i].specified && !TiddlyWiki.isStandardField(name)) {
			fields[name] = attrs[i].value.unescapeLineBreaks();
		}
	}
	tiddler.assign(title,text,modifier,modified,tags,created,fields,creator);
	return tiddler;
};

//--
//-- TW21Saver (inherits from SaverBase)
//--

function TW21Saver() {}

TW21Saver.prototype = new SaverBase();

TW21Saver.prototype.externalizeTiddler = function(store,tiddler)
{
	try {
		var extendedAttributes = "";
		var usePre = config.options.chkUsePreForStorage;
		store.forEachField(tiddler,
			function(tiddler,fieldName,value) {
				// don't store stuff from the temp namespace
				if(typeof value != "string")
					value = "";
				if(!fieldName.match(/^temp\./))
					extendedAttributes += ' %0="%1"'.format([fieldName,value.escapeLineBreaks().htmlEncode()]);
			},true);
		var created = tiddler.created;
		var modified = tiddler.modified;
		var attributes = tiddler.creator ? ' creator="' + tiddler.creator.htmlEncode() + '"' : "";
		attributes += tiddler.modifier ? ' modifier="' + tiddler.modifier.htmlEncode() + '"' : "";
		attributes += (usePre && created == version.date) ? "" :' created="' + created.convertToYYYYMMDDHHMM() + '"';
		attributes += (usePre && modified == created) ? "" : ' modified="' + modified.convertToYYYYMMDDHHMM() +'"';
		var tags = tiddler.getTags();
		if(!usePre || tags)
			attributes += ' tags="' + tags.htmlEncode() + '"';
		return ('<div %0="%1"%2%3>%4</'+'div>').format([
				usePre ? "title" : "tiddler",
				tiddler.title.htmlEncode(),
				attributes,
				extendedAttributes,
				usePre ? "\n<pre>" + tiddler.text.htmlEncode() + "</pre>\n" : tiddler.text.escapeLineBreaks().htmlEncode()
			]);
	} catch (ex) {
		throw exceptionText(ex,config.messages.tiddlerSaveError.format([tiddler.title]));
	}
};



//]]>
</script>

<script id="jsdeprecatedArea" type="text/javascript">
//<![CDATA[
//--
//-- Deprecated Crypto functions and associated conversion routines.
//-- Use the jQuery.encoding functions directly instead.
//--

// Crypto 'namespace'
function Crypto() {}

// Convert a string to an array of big-endian 32-bit words
Crypto.strToBe32s = function(str)
{
	return jQuery.encoding.strToBe32s(str);
};

// Convert an array of big-endian 32-bit words to a string
Crypto.be32sToStr = function(be)
{
	return jQuery.encoding.be32sToStr(be);
};

// Convert an array of big-endian 32-bit words to a hex string
Crypto.be32sToHex = function(be)
{
	return jQuery.encoding.be32sToHex(be);
};

// Return, in hex, the SHA-1 hash of a string
Crypto.hexSha1Str = function(str)
{
	return jQuery.encoding.digests.hexSha1Str(str);
};

// Return the SHA-1 hash of a string
Crypto.sha1Str = function(str)
{
	return jQuery.encoding.digests.sha1Str(str);
};

// Calculate the SHA-1 hash of an array of blen bytes of big-endian 32-bit words
Crypto.sha1 = function(x,blen)
{
	return jQuery.encoding.digests.sha1(x,blen);
};

//--
//-- Deprecated code
//--

// @Deprecated: Use createElementAndWikify and this.termRegExp instead
config.formatterHelpers.charFormatHelper = function(w)
{
	w.subWikify(createTiddlyElement(w.output,this.element),this.terminator);
};

// @Deprecated: Use enclosedTextHelper and this.lookaheadRegExp instead
config.formatterHelpers.monospacedByLineHelper = function(w)
{
	var lookaheadRegExp = new RegExp(this.lookahead,"mg");
	lookaheadRegExp.lastIndex = w.matchStart;
	var lookaheadMatch = lookaheadRegExp.exec(w.source);
	if(lookaheadMatch && lookaheadMatch.index == w.matchStart) {
		var text = lookaheadMatch[1];
		if(config.browser.isIE)
			text = text.replace(/\n/g,"\r");
		createTiddlyElement(w.output,"pre",null,null,text);
		w.nextMatch = lookaheadRegExp.lastIndex;
	}
};

// @Deprecated: Use <br> or <br /> instead of <<br>>
config.macros.br = {};
config.macros.br.handler = function(place)
{
	createTiddlyElement(place,"br");
};

// Find an entry in an array. Returns the array index or null
// @Deprecated: Use indexOf instead
Array.prototype.find = function(item)
{
	var i = this.indexOf(item);
	return i == -1 ? null : i;
};

// Load a tiddler from an HTML DIV. The caller should make sure to later call Tiddler.changed()
// @Deprecated: Use store.getLoader().internalizeTiddler instead
Tiddler.prototype.loadFromDiv = function(divRef,title)
{
	return store.getLoader().internalizeTiddler(store,this,title,divRef);
};

// Format the text for storage in an HTML DIV
// @Deprecated Use store.getSaver().externalizeTiddler instead.
Tiddler.prototype.saveToDiv = function()
{
	return store.getSaver().externalizeTiddler(store,this);
};

// @Deprecated: Use store.allTiddlersAsHtml() instead
function allTiddlersAsHtml()
{
	return store.allTiddlersAsHtml();
}

// @Deprecated: Use refreshPageTemplate instead
function applyPageTemplate(title)
{
	refreshPageTemplate(title);
}

// @Deprecated: Use story.displayTiddlers instead
function displayTiddlers(srcElement,titles,template,unused1,unused2,animate,unused3)
{
	story.displayTiddlers(srcElement,titles,template,animate);
}

// @Deprecated: Use story.displayTiddler instead
function displayTiddler(srcElement,title,template,unused1,unused2,animate,unused3)
{
	story.displayTiddler(srcElement,title,template,animate);
}

// @Deprecated: Use functions on right hand side directly instead
var createTiddlerPopup = Popup.create;
var scrollToTiddlerPopup = Popup.show;
var hideTiddlerPopup = Popup.remove;

// @Deprecated: Use right hand side directly instead
var regexpBackSlashEn = new RegExp("\\\\n","mg");
var regexpBackSlash = new RegExp("\\\\","mg");
var regexpBackSlashEss = new RegExp("\\\\s","mg");
var regexpNewLine = new RegExp("\n","mg");
var regexpCarriageReturn = new RegExp("\r","mg");

//--
//-- Deprecated FileAdaptor functions
//--

FileAdaptor.loadTiddlyWikiCallback = function(status,context,responseText,url,xhr)
{
	context.status = status;
	if(!status) {
		context.statusText = "Error reading file";
	} else {
		context.adaptor.store = new TiddlyWiki();
		if(!context.adaptor.store.importTiddlyWiki(responseText)) {
			context.statusText = config.messages.invalidFileError.format([url]);
			context.status = false;
		}
	}
	context.complete(context,context.userParams);
};

//--
//-- Deprecated HTTP request code
//-- Use the jQuery ajax functions directly instead
//--

function loadRemoteFile(url,callback,params)
{
	return httpReq("GET",url,callback,params);
}

function doHttp(type,url,data,contentType,username,password,callback,params,headers,allowCache)
{
	return httpReq(type,url,callback,params,headers,data,contentType,username,password,allowCache);
}

//--
//-- Deprecated String functions
//--

// @Deprecated: no direct replacement, since not used in core code
String.prototype.toJSONString = function()
{
	// Convert a string to it's JSON representation by encoding control characters, double quotes and backslash. See json.org
	var m = {
		'\b': '\\b',
		'\f': '\\f',
		'\n': '\\n',
		'\r': '\\r',
		'\t': '\\t',
		'"' : '\\"',
		'\\': '\\\\'
		};
	var replaceFn = function(a,b) {
		var c = m[b];
		if(c)
			return c;
		c = b.charCodeAt();
		return '\\u00' + Math.floor(c / 16).toString(16) + (c % 16).toString(16);
		};
	if(/["\\\x00-\x1f]/.test(this))
		return '"' + this.replace(/([\x00-\x1f\\"])/g,replaceFn) + '"';
	return '"' + this + '"';
};

//--
//-- Deprecated Tiddler code
//--

// @Deprecated: Use tiddlerToRssItem(tiddler,uri) instead
Tiddler.prototype.toRssItem = function(uri)
{
	return tiddlerToRssItem(this,uri);
};

// @Deprecated: Use "<item>\n" + tiddlerToRssItem(tiddler,uri)  + "\n</item>" instead
Tiddler.prototype.saveToRss = function(uri)
{
	return "<item>\n" + tiddlerToRssItem(this,uri) + "\n</item>";
};

// @Deprecated: Use jQuery.encoding.digests.hexSha1Str instead
Tiddler.prototype.generateFingerprint = function()
{
	return "0x" + Crypto.hexSha1Str(this.text);
};

//--
//-- Deprecated Number functions
//--

// @Deprecated: no direct replacement, since not used in core code
// Clamp a number to a range
Number.prototype.clamp = function(min,max)
{
	var c = this;
	if(c < min)
		c = min;
	if(c > max)
		c = max;
	return Number(c);
};

//--
//-- Deprecated utility functions
//-- Use the jQuery functions directly instead
//--

// Remove all children of a node
function removeChildren(e)
{
	jQuery(e).empty();
}

// Remove a node and all it's children
function removeNode(e)
{
	jQuery(e).remove();
}

// Return the content of an element as plain text with no formatting
function getPlainText(e)
{
	return jQuery(e).text();
}

function addClass(e,className)
{
	jQuery(e).addClass(className);
}

function removeClass(e,className)
{
	jQuery(e).removeClass(className);
}

function hasClass(e,className)
{
	return jQuery(e).hasClass(className);
}

//--
//-- Deprecated Wikifier code
//--

function wikifyPlain(title,theStore,limit)
{
	if(!theStore)
		theStore = store;
	if(theStore.tiddlerExists(title) || theStore.isShadowTiddler(title)) {
		return wikifyPlainText(theStore.getTiddlerText(title),limit,tiddler);
	} else {
		return "";
	}
}


//]]>
</script>
<script id="jslibArea" type="text/javascript">
//<![CDATA[
/*! jQuery v1.8.3 jquery.com | jquery.org/license */
(function(e,t){function _(e){var t=M[e]={};return v.each(e.split(y),function(e,n){t[n]=!0}),t}function H(e,n,r){if(r===t&&e.nodeType===1){var i="data-"+n.replace(P,"-$1").toLowerCase();r=e.getAttribute(i);if(typeof r=="string"){try{r=r==="true"?!0:r==="false"?!1:r==="null"?null:+r+""===r?+r:D.test(r)?v.parseJSON(r):r}catch(s){}v.data(e,n,r)}else r=t}return r}function B(e){var t;for(t in e){if(t==="data"&&v.isEmptyObject(e[t]))continue;if(t!=="toJSON")return!1}return!0}function et(){return!1}function tt(){return!0}function ut(e){return!e||!e.parentNode||e.parentNode.nodeType===11}function at(e,t){do e=e[t];while(e&&e.nodeType!==1);return e}function ft(e,t,n){t=t||0;if(v.isFunction(t))return v.grep(e,function(e,r){var i=!!t.call(e,r,e);return i===n});if(t.nodeType)return v.grep(e,function(e,r){return e===t===n});if(typeof t=="string"){var r=v.grep(e,function(e){return e.nodeType===1});if(it.test(t))return v.filter(t,r,!n);t=v.filter(t,r)}return v.grep(e,function(e,r){return v.inArray(e,t)>=0===n})}function lt(e){var t=ct.split("|"),n=e.createDocumentFragment();if(n.createElement)while(t.length)n.createElement(t.pop());return n}function Lt(e,t){return e.getElementsByTagName(t)[0]||e.appendChild(e.ownerDocument.createElement(t))}function At(e,t){if(t.nodeType!==1||!v.hasData(e))return;var n,r,i,s=v._data(e),o=v._data(t,s),u=s.events;if(u){delete o.handle,o.events={};for(n in u)for(r=0,i=u[n].length;r<i;r++)v.event.add(t,n,u[n][r])}o.data&&(o.data=v.extend({},o.data))}function Ot(e,t){var n;if(t.nodeType!==1)return;t.clearAttributes&&t.clearAttributes(),t.mergeAttributes&&t.mergeAttributes(e),n=t.nodeName.toLowerCase(),n==="object"?(t.parentNode&&(t.outerHTML=e.outerHTML),v.support.html5Clone&&e.innerHTML&&!v.trim(t.innerHTML)&&(t.innerHTML=e.innerHTML)):n==="input"&&Et.test(e.type)?(t.defaultChecked=t.checked=e.checked,t.value!==e.value&&(t.value=e.value)):n==="option"?t.selected=e.defaultSelected:n==="input"||n==="textarea"?t.defaultValue=e.defaultValue:n==="script"&&t.text!==e.text&&(t.text=e.text),t.removeAttribute(v.expando)}function Mt(e){return typeof e.getElementsByTagName!="undefined"?e.getElementsByTagName("*"):typeof e.querySelectorAll!="undefined"?e.querySelectorAll("*"):[]}function _t(e){Et.test(e.type)&&(e.defaultChecked=e.checked)}function Qt(e,t){if(t in e)return t;var n=t.charAt(0).toUpperCase()+t.slice(1),r=t,i=Jt.length;while(i--){t=Jt[i]+n;if(t in e)return t}return r}function Gt(e,t){return e=t||e,v.css(e,"display")==="none"||!v.contains(e.ownerDocument,e)}function Yt(e,t){var n,r,i=[],s=0,o=e.length;for(;s<o;s++){n=e[s];if(!n.style)continue;i[s]=v._data(n,"olddisplay"),t?(!i[s]&&n.style.display==="none"&&(n.style.display=""),n.style.display===""&&Gt(n)&&(i[s]=v._data(n,"olddisplay",nn(n.nodeName)))):(r=Dt(n,"display"),!i[s]&&r!=="none"&&v._data(n,"olddisplay",r))}for(s=0;s<o;s++){n=e[s];if(!n.style)continue;if(!t||n.style.display==="none"||n.style.display==="")n.style.display=t?i[s]||"":"none"}return e}function Zt(e,t,n){var r=Rt.exec(t);return r?Math.max(0,r[1]-(n||0))+(r[2]||"px"):t}function en(e,t,n,r){var i=n===(r?"border":"content")?4:t==="width"?1:0,s=0;for(;i<4;i+=2)n==="margin"&&(s+=v.css(e,n+$t[i],!0)),r?(n==="content"&&(s-=parseFloat(Dt(e,"padding"+$t[i]))||0),n!=="margin"&&(s-=parseFloat(Dt(e,"border"+$t[i]+"Width"))||0)):(s+=parseFloat(Dt(e,"padding"+$t[i]))||0,n!=="padding"&&(s+=parseFloat(Dt(e,"border"+$t[i]+"Width"))||0));return s}function tn(e,t,n){var r=t==="width"?e.offsetWidth:e.offsetHeight,i=!0,s=v.support.boxSizing&&v.css(e,"boxSizing")==="border-box";if(r<=0||r==null){r=Dt(e,t);if(r<0||r==null)r=e.style[t];if(Ut.test(r))return r;i=s&&(v.support.boxSizingReliable||r===e.style[t]),r=parseFloat(r)||0}return r+en(e,t,n||(s?"border":"content"),i)+"px"}function nn(e){if(Wt[e])return Wt[e];var t=v("<"+e+">").appendTo(i.body),n=t.css("display");t.remove();if(n==="none"||n===""){Pt=i.body.appendChild(Pt||v.extend(i.createElement("iframe"),{frameBorder:0,width:0,height:0}));if(!Ht||!Pt.createElement)Ht=(Pt.contentWindow||Pt.contentDocument).document,Ht.write("<!doctype html><html><body>"),Ht.close();t=Ht.body.appendChild(Ht.createElement(e)),n=Dt(t,"display"),i.body.removeChild(Pt)}return Wt[e]=n,n}function fn(e,t,n,r){var i;if(v.isArray(t))v.each(t,function(t,i){n||sn.test(e)?r(e,i):fn(e+"["+(typeof i=="object"?t:"")+"]",i,n,r)});else if(!n&&v.type(t)==="object")for(i in t)fn(e+"["+i+"]",t[i],n,r);else r(e,t)}function Cn(e){return function(t,n){typeof t!="string"&&(n=t,t="*");var r,i,s,o=t.toLowerCase().split(y),u=0,a=o.length;if(v.isFunction(n))for(;u<a;u++)r=o[u],s=/^\+/.test(r),s&&(r=r.substr(1)||"*"),i=e[r]=e[r]||[],i[s?"unshift":"push"](n)}}function kn(e,n,r,i,s,o){s=s||n.dataTypes[0],o=o||{},o[s]=!0;var u,a=e[s],f=0,l=a?a.length:0,c=e===Sn;for(;f<l&&(c||!u);f++)u=a[f](n,r,i),typeof u=="string"&&(!c||o[u]?u=t:(n.dataTypes.unshift(u),u=kn(e,n,r,i,u,o)));return(c||!u)&&!o["*"]&&(u=kn(e,n,r,i,"*",o)),u}function Ln(e,n){var r,i,s=v.ajaxSettings.flatOptions||{};for(r in n)n[r]!==t&&((s[r]?e:i||(i={}))[r]=n[r]);i&&v.extend(!0,e,i)}function An(e,n,r){var i,s,o,u,a=e.contents,f=e.dataTypes,l=e.responseFields;for(s in l)s in r&&(n[l[s]]=r[s]);while(f[0]==="*")f.shift(),i===t&&(i=e.mimeType||n.getResponseHeader("content-type"));if(i)for(s in a)if(a[s]&&a[s].test(i)){f.unshift(s);break}if(f[0]in r)o=f[0];else{for(s in r){if(!f[0]||e.converters[s+" "+f[0]]){o=s;break}u||(u=s)}o=o||u}if(o)return o!==f[0]&&f.unshift(o),r[o]}function On(e,t){var n,r,i,s,o=e.dataTypes.slice(),u=o[0],a={},f=0;e.dataFilter&&(t=e.dataFilter(t,e.dataType));if(o[1])for(n in e.converters)a[n.toLowerCase()]=e.converters[n];for(;i=o[++f];)if(i!=="*"){if(u!=="*"&&u!==i){n=a[u+" "+i]||a["* "+i];if(!n)for(r in a){s=r.split(" ");if(s[1]===i){n=a[u+" "+s[0]]||a["* "+s[0]];if(n){n===!0?n=a[r]:a[r]!==!0&&(i=s[0],o.splice(f--,0,i));break}}}if(n!==!0)if(n&&e["throws"])t=n(t);else try{t=n(t)}catch(l){return{state:"parsererror",error:n?l:"No conversion from "+u+" to "+i}}}u=i}return{state:"success",data:t}}function Fn(){try{return new e.XMLHttpRequest}catch(t){}}function In(){try{return new e.ActiveXObject("Microsoft.XMLHTTP")}catch(t){}}function $n(){return setTimeout(function(){qn=t},0),qn=v.now()}function Jn(e,t){v.each(t,function(t,n){var r=(Vn[t]||[]).concat(Vn["*"]),i=0,s=r.length;for(;i<s;i++)if(r[i].call(e,t,n))return})}function Kn(e,t,n){var r,i=0,s=0,o=Xn.length,u=v.Deferred().always(function(){delete a.elem}),a=function(){var t=qn||$n(),n=Math.max(0,f.startTime+f.duration-t),r=n/f.duration||0,i=1-r,s=0,o=f.tweens.length;for(;s<o;s++)f.tweens[s].run(i);return u.notifyWith(e,[f,i,n]),i<1&&o?n:(u.resolveWith(e,[f]),!1)},f=u.promise({elem:e,props:v.extend({},t),opts:v.extend(!0,{specialEasing:{}},n),originalProperties:t,originalOptions:n,startTime:qn||$n(),duration:n.duration,tweens:[],createTween:function(t,n,r){var i=v.Tween(e,f.opts,t,n,f.opts.specialEasing[t]||f.opts.easing);return f.tweens.push(i),i},stop:function(t){var n=0,r=t?f.tweens.length:0;for(;n<r;n++)f.tweens[n].run(1);return t?u.resolveWith(e,[f,t]):u.rejectWith(e,[f,t]),this}}),l=f.props;Qn(l,f.opts.specialEasing);for(;i<o;i++){r=Xn[i].call(f,e,l,f.opts);if(r)return r}return Jn(f,l),v.isFunction(f.opts.start)&&f.opts.start.call(e,f),v.fx.timer(v.extend(a,{anim:f,queue:f.opts.queue,elem:e})),f.progress(f.opts.progress).done(f.opts.done,f.opts.complete).fail(f.opts.fail).always(f.opts.always)}function Qn(e,t){var n,r,i,s,o;for(n in e){r=v.camelCase(n),i=t[r],s=e[n],v.isArray(s)&&(i=s[1],s=e[n]=s[0]),n!==r&&(e[r]=s,delete e[n]),o=v.cssHooks[r];if(o&&"expand"in o){s=o.expand(s),delete e[r];for(n in s)n in e||(e[n]=s[n],t[n]=i)}else t[r]=i}}function Gn(e,t,n){var r,i,s,o,u,a,f,l,c,h=this,p=e.style,d={},m=[],g=e.nodeType&&Gt(e);n.queue||(l=v._queueHooks(e,"fx"),l.unqueued==null&&(l.unqueued=0,c=l.empty.fire,l.empty.fire=function(){l.unqueued||c()}),l.unqueued++,h.always(function(){h.always(function(){l.unqueued--,v.queue(e,"fx").length||l.empty.fire()})})),e.nodeType===1&&("height"in t||"width"in t)&&(n.overflow=[p.overflow,p.overflowX,p.overflowY],v.css(e,"display")==="inline"&&v.css(e,"float")==="none"&&(!v.support.inlineBlockNeedsLayout||nn(e.nodeName)==="inline"?p.display="inline-block":p.zoom=1)),n.overflow&&(p.overflow="hidden",v.support.shrinkWrapBlocks||h.done(function(){p.overflow=n.overflow[0],p.overflowX=n.overflow[1],p.overflowY=n.overflow[2]}));for(r in t){s=t[r];if(Un.exec(s)){delete t[r],a=a||s==="toggle";if(s===(g?"hide":"show"))continue;m.push(r)}}o=m.length;if(o){u=v._data(e,"fxshow")||v._data(e,"fxshow",{}),"hidden"in u&&(g=u.hidden),a&&(u.hidden=!g),g?v(e).show():h.done(function(){v(e).hide()}),h.done(function(){var t;v.removeData(e,"fxshow",!0);for(t in d)v.style(e,t,d[t])});for(r=0;r<o;r++)i=m[r],f=h.createTween(i,g?u[i]:0),d[i]=u[i]||v.style(e,i),i in u||(u[i]=f.start,g&&(f.end=f.start,f.start=i==="width"||i==="height"?1:0))}}function Yn(e,t,n,r,i){return new Yn.prototype.init(e,t,n,r,i)}function Zn(e,t){var n,r={height:e},i=0;t=t?1:0;for(;i<4;i+=2-t)n=$t[i],r["margin"+n]=r["padding"+n]=e;return t&&(r.opacity=r.width=e),r}function tr(e){return v.isWindow(e)?e:e.nodeType===9?e.defaultView||e.parentWindow:!1}var n,r,i=e.document,s=e.location,o=e.navigator,u=e.jQuery,a=e.$,f=Array.prototype.push,l=Array.prototype.slice,c=Array.prototype.indexOf,h=Object.prototype.toString,p=Object.prototype.hasOwnProperty,d=String.prototype.trim,v=function(e,t){return new v.fn.init(e,t,n)},m=/[\-+]?(?:\d*\.|)\d+(?:[eE][\-+]?\d+|)/.source,g=/\S/,y=/\s+/,b=/^[\s\uFEFF\xA0]+|[\s\uFEFF\xA0]+$/g,w=/^(?:[^#<]*(<[\w\W]+>)[^>]*$|#([\w\-]*)$)/,E=/^<(\w+)\s*\/?>(?:<\/\1>|)$/,S=/^[\],:{}\s]*$/,x=/(?:^|:|,)(?:\s*\[)+/g,T=/\\(?:["\\\/bfnrt]|u[\da-fA-F]{4})/g,N=/"[^"\\\r\n]*"|true|false|null|-?(?:\d\d*\.|)\d+(?:[eE][\-+]?\d+|)/g,C=/^-ms-/,k=/-([\da-z])/gi,L=function(e,t){return(t+"").toUpperCase()},A=function(){i.addEventListener?(i.removeEventListener("DOMContentLoaded",A,!1),v.ready()):i.readyState==="complete"&&(i.detachEvent("onreadystatechange",A),v.ready())},O={};v.fn=v.prototype={constructor:v,init:function(e,n,r){var s,o,u,a;if(!e)return this;if(e.nodeType)return this.context=this[0]=e,this.length=1,this;if(typeof e=="string"){e.charAt(0)==="<"&&e.charAt(e.length-1)===">"&&e.length>=3?s=[null,e,null]:s=w.exec(e);if(s&&(s[1]||!n)){if(s[1])return n=n instanceof v?n[0]:n,a=n&&n.nodeType?n.ownerDocument||n:i,e=v.parseHTML(s[1],a,!0),E.test(s[1])&&v.isPlainObject(n)&&this.attr.call(e,n,!0),v.merge(this,e);o=i.getElementById(s[2]);if(o&&o.parentNode){if(o.id!==s[2])return r.find(e);this.length=1,this[0]=o}return this.context=i,this.selector=e,this}return!n||n.jquery?(n||r).find(e):this.constructor(n).find(e)}return v.isFunction(e)?r.ready(e):(e.selector!==t&&(this.selector=e.selector,this.context=e.context),v.makeArray(e,this))},selector:"",jquery:"1.8.3",length:0,size:function(){return this.length},toArray:function(){return l.call(this)},get:function(e){return e==null?this.toArray():e<0?this[this.length+e]:this[e]},pushStack:function(e,t,n){var r=v.merge(this.constructor(),e);return r.prevObject=this,r.context=this.context,t==="find"?r.selector=this.selector+(this.selector?" ":"")+n:t&&(r.selector=this.selector+"."+t+"("+n+")"),r},each:function(e,t){return v.each(this,e,t)},ready:function(e){return v.ready.promise().done(e),this},eq:function(e){return e=+e,e===-1?this.slice(e):this.slice(e,e+1)},first:function(){return this.eq(0)},last:function(){return this.eq(-1)},slice:function(){return this.pushStack(l.apply(this,arguments),"slice",l.call(arguments).join(","))},map:function(e){return this.pushStack(v.map(this,function(t,n){return e.call(t,n,t)}))},end:function(){return this.prevObject||this.constructor(null)},push:f,sort:[].sort,splice:[].splice},v.fn.init.prototype=v.fn,v.extend=v.fn.extend=function(){var e,n,r,i,s,o,u=arguments[0]||{},a=1,f=arguments.length,l=!1;typeof u=="boolean"&&(l=u,u=arguments[1]||{},a=2),typeof u!="object"&&!v.isFunction(u)&&(u={}),f===a&&(u=this,--a);for(;a<f;a++)if((e=arguments[a])!=null)for(n in e){r=u[n],i=e[n];if(u===i)continue;l&&i&&(v.isPlainObject(i)||(s=v.isArray(i)))?(s?(s=!1,o=r&&v.isArray(r)?r:[]):o=r&&v.isPlainObject(r)?r:{},u[n]=v.extend(l,o,i)):i!==t&&(u[n]=i)}return u},v.extend({noConflict:function(t){return e.$===v&&(e.$=a),t&&e.jQuery===v&&(e.jQuery=u),v},isReady:!1,readyWait:1,holdReady:function(e){e?v.readyWait++:v.ready(!0)},ready:function(e){if(e===!0?--v.readyWait:v.isReady)return;if(!i.body)return setTimeout(v.ready,1);v.isReady=!0;if(e!==!0&&--v.readyWait>0)return;r.resolveWith(i,[v]),v.fn.trigger&&v(i).trigger("ready").off("ready")},isFunction:function(e){return v.type(e)==="function"},isArray:Array.isArray||function(e){return v.type(e)==="array"},isWindow:function(e){return e!=null&&e==e.window},isNumeric:function(e){return!isNaN(parseFloat(e))&&isFinite(e)},type:function(e){return e==null?String(e):O[h.call(e)]||"object"},isPlainObject:function(e){if(!e||v.type(e)!=="object"||e.nodeType||v.isWindow(e))return!1;try{if(e.constructor&&!p.call(e,"constructor")&&!p.call(e.constructor.prototype,"isPrototypeOf"))return!1}catch(n){return!1}var r;for(r in e);return r===t||p.call(e,r)},isEmptyObject:function(e){var t;for(t in e)return!1;return!0},error:function(e){throw new Error(e)},parseHTML:function(e,t,n){var r;return!e||typeof e!="string"?null:(typeof t=="boolean"&&(n=t,t=0),t=t||i,(r=E.exec(e))?[t.createElement(r[1])]:(r=v.buildFragment([e],t,n?null:[]),v.merge([],(r.cacheable?v.clone(r.fragment):r.fragment).childNodes)))},parseJSON:function(t){if(!t||typeof t!="string")return null;t=v.trim(t);if(e.JSON&&e.JSON.parse)return e.JSON.parse(t);if(S.test(t.replace(T,"@").replace(N,"]").replace(x,"")))return(new Function("return "+t))();v.error("Invalid JSON: "+t)},parseXML:function(n){var r,i;if(!n||typeof n!="string")return null;try{e.DOMParser?(i=new DOMParser,r=i.parseFromString(n,"text/xml")):(r=new ActiveXObject("Microsoft.XMLDOM"),r.async="false",r.loadXML(n))}catch(s){r=t}return(!r||!r.documentElement||r.getElementsByTagName("parsererror").length)&&v.error("Invalid XML: "+n),r},noop:function(){},globalEval:function(t){t&&g.test(t)&&(e.execScript||function(t){e.eval.call(e,t)})(t)},camelCase:function(e){return e.replace(C,"ms-").replace(k,L)},nodeName:function(e,t){return e.nodeName&&e.nodeName.toLowerCase()===t.toLowerCase()},each:function(e,n,r){var i,s=0,o=e.length,u=o===t||v.isFunction(e);if(r){if(u){for(i in e)if(n.apply(e[i],r)===!1)break}else for(;s<o;)if(n.apply(e[s++],r)===!1)break}else if(u){for(i in e)if(n.call(e[i],i,e[i])===!1)break}else for(;s<o;)if(n.call(e[s],s,e[s++])===!1)break;return e},trim:d&&!d.call("\ufeff\u00a0")?function(e){return e==null?"":d.call(e)}:function(e){return e==null?"":(e+"").replace(b,"")},makeArray:function(e,t){var n,r=t||[];return e!=null&&(n=v.type(e),e.length==null||n==="string"||n==="function"||n==="regexp"||v.isWindow(e)?f.call(r,e):v.merge(r,e)),r},inArray:function(e,t,n){var r;if(t){if(c)return c.call(t,e,n);r=t.length,n=n?n<0?Math.max(0,r+n):n:0;for(;n<r;n++)if(n in t&&t[n]===e)return n}return-1},merge:function(e,n){var r=n.length,i=e.length,s=0;if(typeof r=="number")for(;s<r;s++)e[i++]=n[s];else while(n[s]!==t)e[i++]=n[s++];return e.length=i,e},grep:function(e,t,n){var r,i=[],s=0,o=e.length;n=!!n;for(;s<o;s++)r=!!t(e[s],s),n!==r&&i.push(e[s]);return i},map:function(e,n,r){var i,s,o=[],u=0,a=e.length,f=e instanceof v||a!==t&&typeof a=="number"&&(a>0&&e[0]&&e[a-1]||a===0||v.isArray(e));if(f)for(;u<a;u++)i=n(e[u],u,r),i!=null&&(o[o.length]=i);else for(s in e)i=n(e[s],s,r),i!=null&&(o[o.length]=i);return o.concat.apply([],o)},guid:1,proxy:function(e,n){var r,i,s;return typeof n=="string"&&(r=e[n],n=e,e=r),v.isFunction(e)?(i=l.call(arguments,2),s=function(){return e.apply(n,i.concat(l.call(arguments)))},s.guid=e.guid=e.guid||v.guid++,s):t},access:function(e,n,r,i,s,o,u){var a,f=r==null,l=0,c=e.length;if(r&&typeof r=="object"){for(l in r)v.access(e,n,l,r[l],1,o,i);s=1}else if(i!==t){a=u===t&&v.isFunction(i),f&&(a?(a=n,n=function(e,t,n){return a.call(v(e),n)}):(n.call(e,i),n=null));if(n)for(;l<c;l++)n(e[l],r,a?i.call(e[l],l,n(e[l],r)):i,u);s=1}return s?e:f?n.call(e):c?n(e[0],r):o},now:function(){return(new Date).getTime()}}),v.ready.promise=function(t){if(!r){r=v.Deferred();if(i.readyState==="complete")setTimeout(v.ready,1);else if(i.addEventListener)i.addEventListener("DOMContentLoaded",A,!1),e.addEventListener("load",v.ready,!1);else{i.attachEvent("onreadystatechange",A),e.attachEvent("onload",v.ready);var n=!1;try{n=e.frameElement==null&&i.documentElement}catch(s){}n&&n.doScroll&&function o(){if(!v.isReady){try{n.doScroll("left")}catch(e){return setTimeout(o,50)}v.ready()}}()}}return r.promise(t)},v.each("Boolean Number String Function Array Date RegExp Object".split(" "),function(e,t){O["[object "+t+"]"]=t.toLowerCase()}),n=v(i);var M={};v.Callbacks=function(e){e=typeof e=="string"?M[e]||_(e):v.extend({},e);var n,r,i,s,o,u,a=[],f=!e.once&&[],l=function(t){n=e.memory&&t,r=!0,u=s||0,s=0,o=a.length,i=!0;for(;a&&u<o;u++)if(a[u].apply(t[0],t[1])===!1&&e.stopOnFalse){n=!1;break}i=!1,a&&(f?f.length&&l(f.shift()):n?a=[]:c.disable())},c={add:function(){if(a){var t=a.length;(function r(t){v.each(t,function(t,n){var i=v.type(n);i==="function"?(!e.unique||!c.has(n))&&a.push(n):n&&n.length&&i!=="string"&&r(n)})})(arguments),i?o=a.length:n&&(s=t,l(n))}return this},remove:function(){return a&&v.each(arguments,function(e,t){var n;while((n=v.inArray(t,a,n))>-1)a.splice(n,1),i&&(n<=o&&o--,n<=u&&u--)}),this},has:function(e){return v.inArray(e,a)>-1},empty:function(){return a=[],this},disable:function(){return a=f=n=t,this},disabled:function(){return!a},lock:function(){return f=t,n||c.disable(),this},locked:function(){return!f},fireWith:function(e,t){return t=t||[],t=[e,t.slice?t.slice():t],a&&(!r||f)&&(i?f.push(t):l(t)),this},fire:function(){return c.fireWith(this,arguments),this},fired:function(){return!!r}};return c},v.extend({Deferred:function(e){var t=[["resolve","done",v.Callbacks("once memory"),"resolved"],["reject","fail",v.Callbacks("once memory"),"rejected"],["notify","progress",v.Callbacks("memory")]],n="pending",r={state:function(){return n},always:function(){return i.done(arguments).fail(arguments),this},then:function(){var e=arguments;return v.Deferred(function(n){v.each(t,function(t,r){var s=r[0],o=e[t];i[r[1]](v.isFunction(o)?function(){var e=o.apply(this,arguments);e&&v.isFunction(e.promise)?e.promise().done(n.resolve).fail(n.reject).progress(n.notify):n[s+"With"](this===i?n:this,[e])}:n[s])}),e=null}).promise()},promise:function(e){return e!=null?v.extend(e,r):r}},i={};return r.pipe=r.then,v.each(t,function(e,s){var o=s[2],u=s[3];r[s[1]]=o.add,u&&o.add(function(){n=u},t[e^1][2].disable,t[2][2].lock),i[s[0]]=o.fire,i[s[0]+"With"]=o.fireWith}),r.promise(i),e&&e.call(i,i),i},when:function(e){var t=0,n=l.call(arguments),r=n.length,i=r!==1||e&&v.isFunction(e.promise)?r:0,s=i===1?e:v.Deferred(),o=function(e,t,n){return function(r){t[e]=this,n[e]=arguments.length>1?l.call(arguments):r,n===u?s.notifyWith(t,n):--i||s.resolveWith(t,n)}},u,a,f;if(r>1){u=new Array(r),a=new Array(r),f=new Array(r);for(;t<r;t++)n[t]&&v.isFunction(n[t].promise)?n[t].promise().done(o(t,f,n)).fail(s.reject).progress(o(t,a,u)):--i}return i||s.resolveWith(f,n),s.promise()}}),v.support=function(){var t,n,r,s,o,u,a,f,l,c,h,p=i.createElement("div");p.setAttribute("className","t"),p.innerHTML="  <link/><table></table><a href='/a'>a</a><input type='checkbox'/>",n=p.getElementsByTagName("*"),r=p.getElementsByTagName("a")[0];if(!n||!r||!n.length)return{};s=i.createElement("select"),o=s.appendChild(i.createElement("option")),u=p.getElementsByTagName("input")[0],r.style.cssText="top:1px;float:left;opacity:.5",t={leadingWhitespace:p.firstChild.nodeType===3,tbody:!p.getElementsByTagName("tbody").length,htmlSerialize:!!p.getElementsByTagName("link").length,style:/top/.test(r.getAttribute("style")),hrefNormalized:r.getAttribute("href")==="/a",opacity:/^0.5/.test(r.style.opacity),cssFloat:!!r.style.cssFloat,checkOn:u.value==="on",optSelected:o.selected,getSetAttribute:p.className!=="t",enctype:!!i.createElement("form").enctype,html5Clone:i.createElement("nav").cloneNode(!0).outerHTML!=="<:nav></:nav>",boxModel:i.compatMode==="CSS1Compat",submitBubbles:!0,changeBubbles:!0,focusinBubbles:!1,deleteExpando:!0,noCloneEvent:!0,inlineBlockNeedsLayout:!1,shrinkWrapBlocks:!1,reliableMarginRight:!0,boxSizingReliable:!0,pixelPosition:!1},u.checked=!0,t.noCloneChecked=u.cloneNode(!0).checked,s.disabled=!0,t.optDisabled=!o.disabled;try{delete p.test}catch(d){t.deleteExpando=!1}!p.addEventListener&&p.attachEvent&&p.fireEvent&&(p.attachEvent("onclick",h=function(){t.noCloneEvent=!1}),p.cloneNode(!0).fireEvent("onclick"),p.detachEvent("onclick",h)),u=i.createElement("input"),u.value="t",u.setAttribute("type","radio"),t.radioValue=u.value==="t",u.setAttribute("checked","checked"),u.setAttribute("name","t"),p.appendChild(u),a=i.createDocumentFragment(),a.appendChild(p.lastChild),t.checkClone=a.cloneNode(!0).cloneNode(!0).lastChild.checked,t.appendChecked=u.checked,a.removeChild(u),a.appendChild(p);if(p.attachEvent)for(l in{submit:!0,change:!0,focusin:!0})f="on"+l,c=f in p,c||(p.setAttribute(f,"return;"),c=typeof p[f]=="function"),t[l+"Bubbles"]=c;return v(function(){var n,r,s,o,u="padding:0;margin:0;border:0;display:block;overflow:hidden;",a=i.getElementsByTagName("body")[0];if(!a)return;n=i.createElement("div"),n.style.cssText="visibility:hidden;border:0;width:0;height:0;position:static;top:0;margin-top:1px",a.insertBefore(n,a.firstChild),r=i.createElement("div"),n.appendChild(r),r.innerHTML="<table><tr><td></td><td>t</td></tr></table>",s=r.getElementsByTagName("td"),s[0].style.cssText="padding:0;margin:0;border:0;display:none",c=s[0].offsetHeight===0,s[0].style.display="",s[1].style.display="none",t.reliableHiddenOffsets=c&&s[0].offsetHeight===0,r.innerHTML="",r.style.cssText="box-sizing:border-box;-moz-box-sizing:border-box;-webkit-box-sizing:border-box;padding:1px;border:1px;display:block;width:4px;margin-top:1%;position:absolute;top:1%;",t.boxSizing=r.offsetWidth===4,t.doesNotIncludeMarginInBodyOffset=a.offsetTop!==1,e.getComputedStyle&&(t.pixelPosition=(e.getComputedStyle(r,null)||{}).top!=="1%",t.boxSizingReliable=(e.getComputedStyle(r,null)||{width:"4px"}).width==="4px",o=i.createElement("div"),o.style.cssText=r.style.cssText=u,o.style.marginRight=o.style.width="0",r.style.width="1px",r.appendChild(o),t.reliableMarginRight=!parseFloat((e.getComputedStyle(o,null)||{}).marginRight)),typeof r.style.zoom!="undefined"&&(r.innerHTML="",r.style.cssText=u+"width:1px;padding:1px;display:inline;zoom:1",t.inlineBlockNeedsLayout=r.offsetWidth===3,r.style.display="block",r.style.overflow="visible",r.innerHTML="<div></div>",r.firstChild.style.width="5px",t.shrinkWrapBlocks=r.offsetWidth!==3,n.style.zoom=1),a.removeChild(n),n=r=s=o=null}),a.removeChild(p),n=r=s=o=u=a=p=null,t}();var D=/(?:\{[\s\S]*\}|\[[\s\S]*\])$/,P=/([A-Z])/g;v.extend({cache:{},deletedIds:[],uuid:0,expando:"jQuery"+(v.fn.jquery+Math.random()).replace(/\D/g,""),noData:{embed:!0,object:"clsid:D27CDB6E-AE6D-11cf-96B8-444553540000",applet:!0},hasData:function(e){return e=e.nodeType?v.cache[e[v.expando]]:e[v.expando],!!e&&!B(e)},data:function(e,n,r,i){if(!v.acceptData(e))return;var s,o,u=v.expando,a=typeof n=="string",f=e.nodeType,l=f?v.cache:e,c=f?e[u]:e[u]&&u;if((!c||!l[c]||!i&&!l[c].data)&&a&&r===t)return;c||(f?e[u]=c=v.deletedIds.pop()||v.guid++:c=u),l[c]||(l[c]={},f||(l[c].toJSON=v.noop));if(typeof n=="object"||typeof n=="function")i?l[c]=v.extend(l[c],n):l[c].data=v.extend(l[c].data,n);return s=l[c],i||(s.data||(s.data={}),s=s.data),r!==t&&(s[v.camelCase(n)]=r),a?(o=s[n],o==null&&(o=s[v.camelCase(n)])):o=s,o},removeData:function(e,t,n){if(!v.acceptData(e))return;var r,i,s,o=e.nodeType,u=o?v.cache:e,a=o?e[v.expando]:v.expando;if(!u[a])return;if(t){r=n?u[a]:u[a].data;if(r){v.isArray(t)||(t in r?t=[t]:(t=v.camelCase(t),t in r?t=[t]:t=t.split(" ")));for(i=0,s=t.length;i<s;i++)delete r[t[i]];if(!(n?B:v.isEmptyObject)(r))return}}if(!n){delete u[a].data;if(!B(u[a]))return}o?v.cleanData([e],!0):v.support.deleteExpando||u!=u.window?delete u[a]:u[a]=null},_data:function(e,t,n){return v.data(e,t,n,!0)},acceptData:function(e){var t=e.nodeName&&v.noData[e.nodeName.toLowerCase()];return!t||t!==!0&&e.getAttribute("classid")===t}}),v.fn.extend({data:function(e,n){var r,i,s,o,u,a=this[0],f=0,l=null;if(e===t){if(this.length){l=v.data(a);if(a.nodeType===1&&!v._data(a,"parsedAttrs")){s=a.attributes;for(u=s.length;f<u;f++)o=s[f].name,o.indexOf("data-")||(o=v.camelCase(o.substring(5)),H(a,o,l[o]));v._data(a,"parsedAttrs",!0)}}return l}return typeof e=="object"?this.each(function(){v.data(this,e)}):(r=e.split(".",2),r[1]=r[1]?"."+r[1]:"",i=r[1]+"!",v.access(this,function(n){if(n===t)return l=this.triggerHandler("getData"+i,[r[0]]),l===t&&a&&(l=v.data(a,e),l=H(a,e,l)),l===t&&r[1]?this.data(r[0]):l;r[1]=n,this.each(function(){var t=v(this);t.triggerHandler("setData"+i,r),v.data(this,e,n),t.triggerHandler("changeData"+i,r)})},null,n,arguments.length>1,null,!1))},removeData:function(e){return this.each(function(){v.removeData(this,e)})}}),v.extend({queue:function(e,t,n){var r;if(e)return t=(t||"fx")+"queue",r=v._data(e,t),n&&(!r||v.isArray(n)?r=v._data(e,t,v.makeArray(n)):r.push(n)),r||[]},dequeue:function(e,t){t=t||"fx";var n=v.queue(e,t),r=n.length,i=n.shift(),s=v._queueHooks(e,t),o=function(){v.dequeue(e,t)};i==="inprogress"&&(i=n.shift(),r--),i&&(t==="fx"&&n.unshift("inprogress"),delete s.stop,i.call(e,o,s)),!r&&s&&s.empty.fire()},_queueHooks:function(e,t){var n=t+"queueHooks";return v._data(e,n)||v._data(e,n,{empty:v.Callbacks("once memory").add(function(){v.removeData(e,t+"queue",!0),v.removeData(e,n,!0)})})}}),v.fn.extend({queue:function(e,n){var r=2;return typeof e!="string"&&(n=e,e="fx",r--),arguments.length<r?v.queue(this[0],e):n===t?this:this.each(function(){var t=v.queue(this,e,n);v._queueHooks(this,e),e==="fx"&&t[0]!=="inprogress"&&v.dequeue(this,e)})},dequeue:function(e){return this.each(function(){v.dequeue(this,e)})},delay:function(e,t){return e=v.fx?v.fx.speeds[e]||e:e,t=t||"fx",this.queue(t,function(t,n){var r=setTimeout(t,e);n.stop=function(){clearTimeout(r)}})},clearQueue:function(e){return this.queue(e||"fx",[])},promise:function(e,n){var r,i=1,s=v.Deferred(),o=this,u=this.length,a=function(){--i||s.resolveWith(o,[o])};typeof e!="string"&&(n=e,e=t),e=e||"fx";while(u--)r=v._data(o[u],e+"queueHooks"),r&&r.empty&&(i++,r.empty.add(a));return a(),s.promise(n)}});var j,F,I,q=/[\t\r\n]/g,R=/\r/g,U=/^(?:button|input)$/i,z=/^(?:button|input|object|select|textarea)$/i,W=/^a(?:rea|)$/i,X=/^(?:autofocus|autoplay|async|checked|controls|defer|disabled|hidden|loop|multiple|open|readonly|required|scoped|selected)$/i,V=v.support.getSetAttribute;v.fn.extend({attr:function(e,t){return v.access(this,v.attr,e,t,arguments.length>1)},removeAttr:function(e){return this.each(function(){v.removeAttr(this,e)})},prop:function(e,t){return v.access(this,v.prop,e,t,arguments.length>1)},removeProp:function(e){return e=v.propFix[e]||e,this.each(function(){try{this[e]=t,delete this[e]}catch(n){}})},addClass:function(e){var t,n,r,i,s,o,u;if(v.isFunction(e))return this.each(function(t){v(this).addClass(e.call(this,t,this.className))});if(e&&typeof e=="string"){t=e.split(y);for(n=0,r=this.length;n<r;n++){i=this[n];if(i.nodeType===1)if(!i.className&&t.length===1)i.className=e;else{s=" "+i.className+" ";for(o=0,u=t.length;o<u;o++)s.indexOf(" "+t[o]+" ")<0&&(s+=t[o]+" ");i.className=v.trim(s)}}}return this},removeClass:function(e){var n,r,i,s,o,u,a;if(v.isFunction(e))return this.each(function(t){v(this).removeClass(e.call(this,t,this.className))});if(e&&typeof e=="string"||e===t){n=(e||"").split(y);for(u=0,a=this.length;u<a;u++){i=this[u];if(i.nodeType===1&&i.className){r=(" "+i.className+" ").replace(q," ");for(s=0,o=n.length;s<o;s++)while(r.indexOf(" "+n[s]+" ")>=0)r=r.replace(" "+n[s]+" "," ");i.className=e?v.trim(r):""}}}return this},toggleClass:function(e,t){var n=typeof e,r=typeof t=="boolean";return v.isFunction(e)?this.each(function(n){v(this).toggleClass(e.call(this,n,this.className,t),t)}):this.each(function(){if(n==="string"){var i,s=0,o=v(this),u=t,a=e.split(y);while(i=a[s++])u=r?u:!o.hasClass(i),o[u?"addClass":"removeClass"](i)}else if(n==="undefined"||n==="boolean")this.className&&v._data(this,"__className__",this.className),this.className=this.className||e===!1?"":v._data(this,"__className__")||""})},hasClass:function(e){var t=" "+e+" ",n=0,r=this.length;for(;n<r;n++)if(this[n].nodeType===1&&(" "+this[n].className+" ").replace(q," ").indexOf(t)>=0)return!0;return!1},val:function(e){var n,r,i,s=this[0];if(!arguments.length){if(s)return n=v.valHooks[s.type]||v.valHooks[s.nodeName.toLowerCase()],n&&"get"in n&&(r=n.get(s,"value"))!==t?r:(r=s.value,typeof r=="string"?r.replace(R,""):r==null?"":r);return}return i=v.isFunction(e),this.each(function(r){var s,o=v(this);if(this.nodeType!==1)return;i?s=e.call(this,r,o.val()):s=e,s==null?s="":typeof s=="number"?s+="":v.isArray(s)&&(s=v.map(s,function(e){return e==null?"":e+""})),n=v.valHooks[this.type]||v.valHooks[this.nodeName.toLowerCase()];if(!n||!("set"in n)||n.set(this,s,"value")===t)this.value=s})}}),v.extend({valHooks:{option:{get:function(e){var t=e.attributes.value;return!t||t.specified?e.value:e.text}},select:{get:function(e){var t,n,r=e.options,i=e.selectedIndex,s=e.type==="select-one"||i<0,o=s?null:[],u=s?i+1:r.length,a=i<0?u:s?i:0;for(;a<u;a++){n=r[a];if((n.selected||a===i)&&(v.support.optDisabled?!n.disabled:n.getAttribute("disabled")===null)&&(!n.parentNode.disabled||!v.nodeName(n.parentNode,"optgroup"))){t=v(n).val();if(s)return t;o.push(t)}}return o},set:function(e,t){var n=v.makeArray(t);return v(e).find("option").each(function(){this.selected=v.inArray(v(this).val(),n)>=0}),n.length||(e.selectedIndex=-1),n}}},attrFn:{},attr:function(e,n,r,i){var s,o,u,a=e.nodeType;if(!e||a===3||a===8||a===2)return;if(i&&v.isFunction(v.fn[n]))return v(e)[n](r);if(typeof e.getAttribute=="undefined")return v.prop(e,n,r);u=a!==1||!v.isXMLDoc(e),u&&(n=n.toLowerCase(),o=v.attrHooks[n]||(X.test(n)?F:j));if(r!==t){if(r===null){v.removeAttr(e,n);return}return o&&"set"in o&&u&&(s=o.set(e,r,n))!==t?s:(e.setAttribute(n,r+""),r)}return o&&"get"in o&&u&&(s=o.get(e,n))!==null?s:(s=e.getAttribute(n),s===null?t:s)},removeAttr:function(e,t){var n,r,i,s,o=0;if(t&&e.nodeType===1){r=t.split(y);for(;o<r.length;o++)i=r[o],i&&(n=v.propFix[i]||i,s=X.test(i),s||v.attr(e,i,""),e.removeAttribute(V?i:n),s&&n in e&&(e[n]=!1))}},attrHooks:{type:{set:function(e,t){if(U.test(e.nodeName)&&e.parentNode)v.error("type property can't be changed");else if(!v.support.radioValue&&t==="radio"&&v.nodeName(e,"input")){var n=e.value;return e.setAttribute("type",t),n&&(e.value=n),t}}},value:{get:function(e,t){return j&&v.nodeName(e,"button")?j.get(e,t):t in e?e.value:null},set:function(e,t,n){if(j&&v.nodeName(e,"button"))return j.set(e,t,n);e.value=t}}},propFix:{tabindex:"tabIndex",readonly:"readOnly","for":"htmlFor","class":"className",maxlength:"maxLength",cellspacing:"cellSpacing",cellpadding:"cellPadding",rowspan:"rowSpan",colspan:"colSpan",usemap:"useMap",frameborder:"frameBorder",contenteditable:"contentEditable"},prop:function(e,n,r){var i,s,o,u=e.nodeType;if(!e||u===3||u===8||u===2)return;return o=u!==1||!v.isXMLDoc(e),o&&(n=v.propFix[n]||n,s=v.propHooks[n]),r!==t?s&&"set"in s&&(i=s.set(e,r,n))!==t?i:e[n]=r:s&&"get"in s&&(i=s.get(e,n))!==null?i:e[n]},propHooks:{tabIndex:{get:function(e){var n=e.getAttributeNode("tabindex");return n&&n.specified?parseInt(n.value,10):z.test(e.nodeName)||W.test(e.nodeName)&&e.href?0:t}}}}),F={get:function(e,n){var r,i=v.prop(e,n);return i===!0||typeof i!="boolean"&&(r=e.getAttributeNode(n))&&r.nodeValue!==!1?n.toLowerCase():t},set:function(e,t,n){var r;return t===!1?v.removeAttr(e,n):(r=v.propFix[n]||n,r in e&&(e[r]=!0),e.setAttribute(n,n.toLowerCase())),n}},V||(I={name:!0,id:!0,coords:!0},j=v.valHooks.button={get:function(e,n){var r;return r=e.getAttributeNode(n),r&&(I[n]?r.value!=="":r.specified)?r.value:t},set:function(e,t,n){var r=e.getAttributeNode(n);return r||(r=i.createAttribute(n),e.setAttributeNode(r)),r.value=t+""}},v.each(["width","height"],function(e,t){v.attrHooks[t]=v.extend(v.attrHooks[t],{set:function(e,n){if(n==="")return e.setAttribute(t,"auto"),n}})}),v.attrHooks.contenteditable={get:j.get,set:function(e,t,n){t===""&&(t="false"),j.set(e,t,n)}}),v.support.hrefNormalized||v.each(["href","src","width","height"],function(e,n){v.attrHooks[n]=v.extend(v.attrHooks[n],{get:function(e){var r=e.getAttribute(n,2);return r===null?t:r}})}),v.support.style||(v.attrHooks.style={get:function(e){return e.style.cssText.toLowerCase()||t},set:function(e,t){return e.style.cssText=t+""}}),v.support.optSelected||(v.propHooks.selected=v.extend(v.propHooks.selected,{get:function(e){var t=e.parentNode;return t&&(t.selectedIndex,t.parentNode&&t.parentNode.selectedIndex),null}})),v.support.enctype||(v.propFix.enctype="encoding"),v.support.checkOn||v.each(["radio","checkbox"],function(){v.valHooks[this]={get:function(e){return e.getAttribute("value")===null?"on":e.value}}}),v.each(["radio","checkbox"],function(){v.valHooks[this]=v.extend(v.valHooks[this],{set:function(e,t){if(v.isArray(t))return e.checked=v.inArray(v(e).val(),t)>=0}})});var $=/^(?:textarea|input|select)$/i,J=/^([^\.]*|)(?:\.(.+)|)$/,K=/(?:^|\s)hover(\.\S+|)\b/,Q=/^key/,G=/^(?:mouse|contextmenu)|click/,Y=/^(?:focusinfocus|focusoutblur)$/,Z=function(e){return v.event.special.hover?e:e.replace(K,"mouseenter$1 mouseleave$1")};v.event={add:function(e,n,r,i,s){var o,u,a,f,l,c,h,p,d,m,g;if(e.nodeType===3||e.nodeType===8||!n||!r||!(o=v._data(e)))return;r.handler&&(d=r,r=d.handler,s=d.selector),r.guid||(r.guid=v.guid++),a=o.events,a||(o.events=a={}),u=o.handle,u||(o.handle=u=function(e){return typeof v=="undefined"||!!e&&v.event.triggered===e.type?t:v.event.dispatch.apply(u.elem,arguments)},u.elem=e),n=v.trim(Z(n)).split(" ");for(f=0;f<n.length;f++){l=J.exec(n[f])||[],c=l[1],h=(l[2]||"").split(".").sort(),g=v.event.special[c]||{},c=(s?g.delegateType:g.bindType)||c,g=v.event.special[c]||{},p=v.extend({type:c,origType:l[1],data:i,handler:r,guid:r.guid,selector:s,needsContext:s&&v.expr.match.needsContext.test(s),namespace:h.join(".")},d),m=a[c];if(!m){m=a[c]=[],m.delegateCount=0;if(!g.setup||g.setup.call(e,i,h,u)===!1)e.addEventListener?e.addEventListener(c,u,!1):e.attachEvent&&e.attachEvent("on"+c,u)}g.add&&(g.add.call(e,p),p.handler.guid||(p.handler.guid=r.guid)),s?m.splice(m.delegateCount++,0,p):m.push(p),v.event.global[c]=!0}e=null},global:{},remove:function(e,t,n,r,i){var s,o,u,a,f,l,c,h,p,d,m,g=v.hasData(e)&&v._data(e);if(!g||!(h=g.events))return;t=v.trim(Z(t||"")).split(" ");for(s=0;s<t.length;s++){o=J.exec(t[s])||[],u=a=o[1],f=o[2];if(!u){for(u in h)v.event.remove(e,u+t[s],n,r,!0);continue}p=v.event.special[u]||{},u=(r?p.delegateType:p.bindType)||u,d=h[u]||[],l=d.length,f=f?new RegExp("(^|\\.)"+f.split(".").sort().join("\\.(?:.*\\.|)")+"(\\.|$)"):null;for(c=0;c<d.length;c++)m=d[c],(i||a===m.origType)&&(!n||n.guid===m.guid)&&(!f||f.test(m.namespace))&&(!r||r===m.selector||r==="**"&&m.selector)&&(d.splice(c--,1),m.selector&&d.delegateCount--,p.remove&&p.remove.call(e,m));d.length===0&&l!==d.length&&((!p.teardown||p.teardown.call(e,f,g.handle)===!1)&&v.removeEvent(e,u,g.handle),delete h[u])}v.isEmptyObject(h)&&(delete g.handle,v.removeData(e,"events",!0))},customEvent:{getData:!0,setData:!0,changeData:!0},trigger:function(n,r,s,o){if(!s||s.nodeType!==3&&s.nodeType!==8){var u,a,f,l,c,h,p,d,m,g,y=n.type||n,b=[];if(Y.test(y+v.event.triggered))return;y.indexOf("!")>=0&&(y=y.slice(0,-1),a=!0),y.indexOf(".")>=0&&(b=y.split("."),y=b.shift(),b.sort());if((!s||v.event.customEvent[y])&&!v.event.global[y])return;n=typeof n=="object"?n[v.expando]?n:new v.Event(y,n):new v.Event(y),n.type=y,n.isTrigger=!0,n.exclusive=a,n.namespace=b.join("."),n.namespace_re=n.namespace?new RegExp("(^|\\.)"+b.join("\\.(?:.*\\.|)")+"(\\.|$)"):null,h=y.indexOf(":")<0?"on"+y:"";if(!s){u=v.cache;for(f in u)u[f].events&&u[f].events[y]&&v.event.trigger(n,r,u[f].handle.elem,!0);return}n.result=t,n.target||(n.target=s),r=r!=null?v.makeArray(r):[],r.unshift(n),p=v.event.special[y]||{};if(p.trigger&&p.trigger.apply(s,r)===!1)return;m=[[s,p.bindType||y]];if(!o&&!p.noBubble&&!v.isWindow(s)){g=p.delegateType||y,l=Y.test(g+y)?s:s.parentNode;for(c=s;l;l=l.parentNode)m.push([l,g]),c=l;c===(s.ownerDocument||i)&&m.push([c.defaultView||c.parentWindow||e,g])}for(f=0;f<m.length&&!n.isPropagationStopped();f++)l=m[f][0],n.type=m[f][1],d=(v._data(l,"events")||{})[n.type]&&v._data(l,"handle"),d&&d.apply(l,r),d=h&&l[h],d&&v.acceptData(l)&&d.apply&&d.apply(l,r)===!1&&n.preventDefault();return n.type=y,!o&&!n.isDefaultPrevented()&&(!p._default||p._default.apply(s.ownerDocument,r)===!1)&&(y!=="click"||!v.nodeName(s,"a"))&&v.acceptData(s)&&h&&s[y]&&(y!=="focus"&&y!=="blur"||n.target.offsetWidth!==0)&&!v.isWindow(s)&&(c=s[h],c&&(s[h]=null),v.event.triggered=y,s[y](),v.event.triggered=t,c&&(s[h]=c)),n.result}return},dispatch:function(n){n=v.event.fix(n||e.event);var r,i,s,o,u,a,f,c,h,p,d=(v._data(this,"events")||{})[n.type]||[],m=d.delegateCount,g=l.call(arguments),y=!n.exclusive&&!n.namespace,b=v.event.special[n.type]||{},w=[];g[0]=n,n.delegateTarget=this;if(b.preDispatch&&b.preDispatch.call(this,n)===!1)return;if(m&&(!n.button||n.type!=="click"))for(s=n.target;s!=this;s=s.parentNode||this)if(s.disabled!==!0||n.type!=="click"){u={},f=[];for(r=0;r<m;r++)c=d[r],h=c.selector,u[h]===t&&(u[h]=c.needsContext?v(h,this).index(s)>=0:v.find(h,this,null,[s]).length),u[h]&&f.push(c);f.length&&w.push({elem:s,matches:f})}d.length>m&&w.push({elem:this,matches:d.slice(m)});for(r=0;r<w.length&&!n.isPropagationStopped();r++){a=w[r],n.currentTarget=a.elem;for(i=0;i<a.matches.length&&!n.isImmediatePropagationStopped();i++){c=a.matches[i];if(y||!n.namespace&&!c.namespace||n.namespace_re&&n.namespace_re.test(c.namespace))n.data=c.data,n.handleObj=c,o=((v.event.special[c.origType]||{}).handle||c.handler).apply(a.elem,g),o!==t&&(n.result=o,o===!1&&(n.preventDefault(),n.stopPropagation()))}}return b.postDispatch&&b.postDispatch.call(this,n),n.result},props:"attrChange attrName relatedNode srcElement altKey bubbles cancelable ctrlKey currentTarget eventPhase metaKey relatedTarget shiftKey target timeStamp view which".split(" "),fixHooks:{},keyHooks:{props:"char charCode key keyCode".split(" "),filter:function(e,t){return e.which==null&&(e.which=t.charCode!=null?t.charCode:t.keyCode),e}},mouseHooks:{props:"button buttons clientX clientY fromElement offsetX offsetY pageX pageY screenX screenY toElement".split(" "),filter:function(e,n){var r,s,o,u=n.button,a=n.fromElement;return e.pageX==null&&n.clientX!=null&&(r=e.target.ownerDocument||i,s=r.documentElement,o=r.body,e.pageX=n.clientX+(s&&s.scrollLeft||o&&o.scrollLeft||0)-(s&&s.clientLeft||o&&o.clientLeft||0),e.pageY=n.clientY+(s&&s.scrollTop||o&&o.scrollTop||0)-(s&&s.clientTop||o&&o.clientTop||0)),!e.relatedTarget&&a&&(e.relatedTarget=a===e.target?n.toElement:a),!e.which&&u!==t&&(e.which=u&1?1:u&2?3:u&4?2:0),e}},fix:function(e){if(e[v.expando])return e;var t,n,r=e,s=v.event.fixHooks[e.type]||{},o=s.props?this.props.concat(s.props):this.props;e=v.Event(r);for(t=o.length;t;)n=o[--t],e[n]=r[n];return e.target||(e.target=r.srcElement||i),e.target.nodeType===3&&(e.target=e.target.parentNode),e.metaKey=!!e.metaKey,s.filter?s.filter(e,r):e},special:{load:{noBubble:!0},focus:{delegateType:"focusin"},blur:{delegateType:"focusout"},beforeunload:{setup:function(e,t,n){v.isWindow(this)&&(this.onbeforeunload=n)},teardown:function(e,t){this.onbeforeunload===t&&(this.onbeforeunload=null)}}},simulate:function(e,t,n,r){var i=v.extend(new v.Event,n,{type:e,isSimulated:!0,originalEvent:{}});r?v.event.trigger(i,null,t):v.event.dispatch.call(t,i),i.isDefaultPrevented()&&n.preventDefault()}},v.event.handle=v.event.dispatch,v.removeEvent=i.removeEventListener?function(e,t,n){e.removeEventListener&&e.removeEventListener(t,n,!1)}:function(e,t,n){var r="on"+t;e.detachEvent&&(typeof e[r]=="undefined"&&(e[r]=null),e.detachEvent(r,n))},v.Event=function(e,t){if(!(this instanceof v.Event))return new v.Event(e,t);e&&e.type?(this.originalEvent=e,this.type=e.type,this.isDefaultPrevented=e.defaultPrevented||e.returnValue===!1||e.getPreventDefault&&e.getPreventDefault()?tt:et):this.type=e,t&&v.extend(this,t),this.timeStamp=e&&e.timeStamp||v.now(),this[v.expando]=!0},v.Event.prototype={preventDefault:function(){this.isDefaultPrevented=tt;var e=this.originalEvent;if(!e)return;e.preventDefault?e.preventDefault():e.returnValue=!1},stopPropagation:function(){this.isPropagationStopped=tt;var e=this.originalEvent;if(!e)return;e.stopPropagation&&e.stopPropagation(),e.cancelBubble=!0},stopImmediatePropagation:function(){this.isImmediatePropagationStopped=tt,this.stopPropagation()},isDefaultPrevented:et,isPropagationStopped:et,isImmediatePropagationStopped:et},v.each({mouseenter:"mouseover",mouseleave:"mouseout"},function(e,t){v.event.special[e]={delegateType:t,bindType:t,handle:function(e){var n,r=this,i=e.relatedTarget,s=e.handleObj,o=s.selector;if(!i||i!==r&&!v.contains(r,i))e.type=s.origType,n=s.handler.apply(this,arguments),e.type=t;return n}}}),v.support.submitBubbles||(v.event.special.submit={setup:function(){if(v.nodeName(this,"form"))return!1;v.event.add(this,"click._submit keypress._submit",function(e){var n=e.target,r=v.nodeName(n,"input")||v.nodeName(n,"button")?n.form:t;r&&!v._data(r,"_submit_attached")&&(v.event.add(r,"submit._submit",function(e){e._submit_bubble=!0}),v._data(r,"_submit_attached",!0))})},postDispatch:function(e){e._submit_bubble&&(delete e._submit_bubble,this.parentNode&&!e.isTrigger&&v.event.simulate("submit",this.parentNode,e,!0))},teardown:function(){if(v.nodeName(this,"form"))return!1;v.event.remove(this,"._submit")}}),v.support.changeBubbles||(v.event.special.change={setup:function(){if($.test(this.nodeName)){if(this.type==="checkbox"||this.type==="radio")v.event.add(this,"propertychange._change",function(e){e.originalEvent.propertyName==="checked"&&(this._just_changed=!0)}),v.event.add(this,"click._change",function(e){this._just_changed&&!e.isTrigger&&(this._just_changed=!1),v.event.simulate("change",this,e,!0)});return!1}v.event.add(this,"beforeactivate._change",function(e){var t=e.target;$.test(t.nodeName)&&!v._data(t,"_change_attached")&&(v.event.add(t,"change._change",function(e){this.parentNode&&!e.isSimulated&&!e.isTrigger&&v.event.simulate("change",this.parentNode,e,!0)}),v._data(t,"_change_attached",!0))})},handle:function(e){var t=e.target;if(this!==t||e.isSimulated||e.isTrigger||t.type!=="radio"&&t.type!=="checkbox")return e.handleObj.handler.apply(this,arguments)},teardown:function(){return v.event.remove(this,"._change"),!$.test(this.nodeName)}}),v.support.focusinBubbles||v.each({focus:"focusin",blur:"focusout"},function(e,t){var n=0,r=function(e){v.event.simulate(t,e.target,v.event.fix(e),!0)};v.event.special[t]={setup:function(){n++===0&&i.addEventListener(e,r,!0)},teardown:function(){--n===0&&i.removeEventListener(e,r,!0)}}}),v.fn.extend({on:function(e,n,r,i,s){var o,u;if(typeof e=="object"){typeof n!="string"&&(r=r||n,n=t);for(u in e)this.on(u,n,r,e[u],s);return this}r==null&&i==null?(i=n,r=n=t):i==null&&(typeof n=="string"?(i=r,r=t):(i=r,r=n,n=t));if(i===!1)i=et;else if(!i)return this;return s===1&&(o=i,i=function(e){return v().off(e),o.apply(this,arguments)},i.guid=o.guid||(o.guid=v.guid++)),this.each(function(){v.event.add(this,e,i,r,n)})},one:function(e,t,n,r){return this.on(e,t,n,r,1)},off:function(e,n,r){var i,s;if(e&&e.preventDefault&&e.handleObj)return i=e.handleObj,v(e.delegateTarget).off(i.namespace?i.origType+"."+i.namespace:i.origType,i.selector,i.handler),this;if(typeof e=="object"){for(s in e)this.off(s,n,e[s]);return this}if(n===!1||typeof n=="function")r=n,n=t;return r===!1&&(r=et),this.each(function(){v.event.remove(this,e,r,n)})},bind:function(e,t,n){return this.on(e,null,t,n)},unbind:function(e,t){return this.off(e,null,t)},live:function(e,t,n){return v(this.context).on(e,this.selector,t,n),this},die:function(e,t){return v(this.context).off(e,this.selector||"**",t),this},delegate:function(e,t,n,r){return this.on(t,e,n,r)},undelegate:function(e,t,n){return arguments.length===1?this.off(e,"**"):this.off(t,e||"**",n)},trigger:function(e,t){return this.each(function(){v.event.trigger(e,t,this)})},triggerHandler:function(e,t){if(this[0])return v.event.trigger(e,t,this[0],!0)},toggle:function(e){var t=arguments,n=e.guid||v.guid++,r=0,i=function(n){var i=(v._data(this,"lastToggle"+e.guid)||0)%r;return v._data(this,"lastToggle"+e.guid,i+1),n.preventDefault(),t[i].apply(this,arguments)||!1};i.guid=n;while(r<t.length)t[r++].guid=n;return this.click(i)},hover:function(e,t){return this.mouseenter(e).mouseleave(t||e)}}),v.each("blur focus focusin focusout load resize scroll unload click dblclick mousedown mouseup mousemove mouseover mouseout mouseenter mouseleave change select submit keydown keypress keyup error contextmenu".split(" "),function(e,t){v.fn[t]=function(e,n){return n==null&&(n=e,e=null),arguments.length>0?this.on(t,null,e,n):this.trigger(t)},Q.test(t)&&(v.event.fixHooks[t]=v.event.keyHooks),G.test(t)&&(v.event.fixHooks[t]=v.event.mouseHooks)}),function(e,t){function nt(e,t,n,r){n=n||[],t=t||g;var i,s,a,f,l=t.nodeType;if(!e||typeof e!="string")return n;if(l!==1&&l!==9)return[];a=o(t);if(!a&&!r)if(i=R.exec(e))if(f=i[1]){if(l===9){s=t.getElementById(f);if(!s||!s.parentNode)return n;if(s.id===f)return n.push(s),n}else if(t.ownerDocument&&(s=t.ownerDocument.getElementById(f))&&u(t,s)&&s.id===f)return n.push(s),n}else{if(i[2])return S.apply(n,x.call(t.getElementsByTagName(e),0)),n;if((f=i[3])&&Z&&t.getElementsByClassName)return S.apply(n,x.call(t.getElementsByClassName(f),0)),n}return vt(e.replace(j,"$1"),t,n,r,a)}function rt(e){return function(t){var n=t.nodeName.toLowerCase();return n==="input"&&t.type===e}}function it(e){return function(t){var n=t.nodeName.toLowerCase();return(n==="input"||n==="button")&&t.type===e}}function st(e){return N(function(t){return t=+t,N(function(n,r){var i,s=e([],n.length,t),o=s.length;while(o--)n[i=s[o]]&&(n[i]=!(r[i]=n[i]))})})}function ot(e,t,n){if(e===t)return n;var r=e.nextSibling;while(r){if(r===t)return-1;r=r.nextSibling}return 1}function ut(e,t){var n,r,s,o,u,a,f,l=L[d][e+" "];if(l)return t?0:l.slice(0);u=e,a=[],f=i.preFilter;while(u){if(!n||(r=F.exec(u)))r&&(u=u.slice(r[0].length)||u),a.push(s=[]);n=!1;if(r=I.exec(u))s.push(n=new m(r.shift())),u=u.slice(n.length),n.type=r[0].replace(j," ");for(o in i.filter)(r=J[o].exec(u))&&(!f[o]||(r=f[o](r)))&&(s.push(n=new m(r.shift())),u=u.slice(n.length),n.type=o,n.matches=r);if(!n)break}return t?u.length:u?nt.error(e):L(e,a).slice(0)}function at(e,t,r){var i=t.dir,s=r&&t.dir==="parentNode",o=w++;return t.first?function(t,n,r){while(t=t[i])if(s||t.nodeType===1)return e(t,n,r)}:function(t,r,u){if(!u){var a,f=b+" "+o+" ",l=f+n;while(t=t[i])if(s||t.nodeType===1){if((a=t[d])===l)return t.sizset;if(typeof a=="string"&&a.indexOf(f)===0){if(t.sizset)return t}else{t[d]=l;if(e(t,r,u))return t.sizset=!0,t;t.sizset=!1}}}else while(t=t[i])if(s||t.nodeType===1)if(e(t,r,u))return t}}function ft(e){return e.length>1?function(t,n,r){var i=e.length;while(i--)if(!e[i](t,n,r))return!1;return!0}:e[0]}function lt(e,t,n,r,i){var s,o=[],u=0,a=e.length,f=t!=null;for(;u<a;u++)if(s=e[u])if(!n||n(s,r,i))o.push(s),f&&t.push(u);return o}function ct(e,t,n,r,i,s){return r&&!r[d]&&(r=ct(r)),i&&!i[d]&&(i=ct(i,s)),N(function(s,o,u,a){var f,l,c,h=[],p=[],d=o.length,v=s||dt(t||"*",u.nodeType?[u]:u,[]),m=e&&(s||!t)?lt(v,h,e,u,a):v,g=n?i||(s?e:d||r)?[]:o:m;n&&n(m,g,u,a);if(r){f=lt(g,p),r(f,[],u,a),l=f.length;while(l--)if(c=f[l])g[p[l]]=!(m[p[l]]=c)}if(s){if(i||e){if(i){f=[],l=g.length;while(l--)(c=g[l])&&f.push(m[l]=c);i(null,g=[],f,a)}l=g.length;while(l--)(c=g[l])&&(f=i?T.call(s,c):h[l])>-1&&(s[f]=!(o[f]=c))}}else g=lt(g===o?g.splice(d,g.length):g),i?i(null,o,g,a):S.apply(o,g)})}function ht(e){var t,n,r,s=e.length,o=i.relative[e[0].type],u=o||i.relative[" "],a=o?1:0,f=at(function(e){return e===t},u,!0),l=at(function(e){return T.call(t,e)>-1},u,!0),h=[function(e,n,r){return!o&&(r||n!==c)||((t=n).nodeType?f(e,n,r):l(e,n,r))}];for(;a<s;a++)if(n=i.relative[e[a].type])h=[at(ft(h),n)];else{n=i.filter[e[a].type].apply(null,e[a].matches);if(n[d]){r=++a;for(;r<s;r++)if(i.relative[e[r].type])break;return ct(a>1&&ft(h),a>1&&e.slice(0,a-1).join("").replace(j,"$1"),n,a<r&&ht(e.slice(a,r)),r<s&&ht(e=e.slice(r)),r<s&&e.join(""))}h.push(n)}return ft(h)}function pt(e,t){var r=t.length>0,s=e.length>0,o=function(u,a,f,l,h){var p,d,v,m=[],y=0,w="0",x=u&&[],T=h!=null,N=c,C=u||s&&i.find.TAG("*",h&&a.parentNode||a),k=b+=N==null?1:Math.E;T&&(c=a!==g&&a,n=o.el);for(;(p=C[w])!=null;w++){if(s&&p){for(d=0;v=e[d];d++)if(v(p,a,f)){l.push(p);break}T&&(b=k,n=++o.el)}r&&((p=!v&&p)&&y--,u&&x.push(p))}y+=w;if(r&&w!==y){for(d=0;v=t[d];d++)v(x,m,a,f);if(u){if(y>0)while(w--)!x[w]&&!m[w]&&(m[w]=E.call(l));m=lt(m)}S.apply(l,m),T&&!u&&m.length>0&&y+t.length>1&&nt.uniqueSort(l)}return T&&(b=k,c=N),x};return o.el=0,r?N(o):o}function dt(e,t,n){var r=0,i=t.length;for(;r<i;r++)nt(e,t[r],n);return n}function vt(e,t,n,r,s){var o,u,f,l,c,h=ut(e),p=h.length;if(!r&&h.length===1){u=h[0]=h[0].slice(0);if(u.length>2&&(f=u[0]).type==="ID"&&t.nodeType===9&&!s&&i.relative[u[1].type]){t=i.find.ID(f.matches[0].replace($,""),t,s)[0];if(!t)return n;e=e.slice(u.shift().length)}for(o=J.POS.test(e)?-1:u.length-1;o>=0;o--){f=u[o];if(i.relative[l=f.type])break;if(c=i.find[l])if(r=c(f.matches[0].replace($,""),z.test(u[0].type)&&t.parentNode||t,s)){u.splice(o,1),e=r.length&&u.join("");if(!e)return S.apply(n,x.call(r,0)),n;break}}}return a(e,h)(r,t,s,n,z.test(e)),n}function mt(){}var n,r,i,s,o,u,a,f,l,c,h=!0,p="undefined",d=("sizcache"+Math.random()).replace(".",""),m=String,g=e.document,y=g.documentElement,b=0,w=0,E=[].pop,S=[].push,x=[].slice,T=[].indexOf||function(e){var t=0,n=this.length;for(;t<n;t++)if(this[t]===e)return t;return-1},N=function(e,t){return e[d]=t==null||t,e},C=function(){var e={},t=[];return N(function(n,r){return t.push(n)>i.cacheLength&&delete e[t.shift()],e[n+" "]=r},e)},k=C(),L=C(),A=C(),O="[\\x20\\t\\r\\n\\f]",M="(?:\\\\.|[-\\w]|[^\\x00-\\xa0])+",_=M.replace("w","w#"),D="([*^$|!~]?=)",P="\\["+O+"*("+M+")"+O+"*(?:"+D+O+"*(?:(['\"])((?:\\\\.|[^\\\\])*?)\\3|("+_+")|)|)"+O+"*\\]",H=":("+M+")(?:\\((?:(['\"])((?:\\\\.|[^\\\\])*?)\\2|([^()[\\]]*|(?:(?:"+P+")|[^:]|\\\\.)*|.*))\\)|)",B=":(even|odd|eq|gt|lt|nth|first|last)(?:\\("+O+"*((?:-\\d)?\\d*)"+O+"*\\)|)(?=[^-]|$)",j=new RegExp("^"+O+"+|((?:^|[^\\\\])(?:\\\\.)*)"+O+"+$","g"),F=new RegExp("^"+O+"*,"+O+"*"),I=new RegExp("^"+O+"*([\\x20\\t\\r\\n\\f>+~])"+O+"*"),q=new RegExp(H),R=/^(?:#([\w\-]+)|(\w+)|\.([\w\-]+))$/,U=/^:not/,z=/[\x20\t\r\n\f]*[+~]/,W=/:not\($/,X=/h\d/i,V=/input|select|textarea|button/i,$=/\\(?!\\)/g,J={ID:new RegExp("^#("+M+")"),CLASS:new RegExp("^\\.("+M+")"),NAME:new RegExp("^\\[name=['\"]?("+M+")['\"]?\\]"),TAG:new RegExp("^("+M.replace("w","w*")+")"),ATTR:new RegExp("^"+P),PSEUDO:new RegExp("^"+H),POS:new RegExp(B,"i"),CHILD:new RegExp("^:(only|nth|first|last)-child(?:\\("+O+"*(even|odd|(([+-]|)(\\d*)n|)"+O+"*(?:([+-]|)"+O+"*(\\d+)|))"+O+"*\\)|)","i"),needsContext:new RegExp("^"+O+"*[>+~]|"+B,"i")},K=function(e){var t=g.createElement("div");try{return e(t)}catch(n){return!1}finally{t=null}},Q=K(function(e){return e.appendChild(g.createComment("")),!e.getElementsByTagName("*").length}),G=K(function(e){return e.innerHTML="<a href='#'></a>",e.firstChild&&typeof e.firstChild.getAttribute!==p&&e.firstChild.getAttribute("href")==="#"}),Y=K(function(e){e.innerHTML="<select></select>";var t=typeof e.lastChild.getAttribute("multiple");return t!=="boolean"&&t!=="string"}),Z=K(function(e){return e.innerHTML="<div class='hidden e'></div><div class='hidden'></div>",!e.getElementsByClassName||!e.getElementsByClassName("e").length?!1:(e.lastChild.className="e",e.getElementsByClassName("e").length===2)}),et=K(function(e){e.id=d+0,e.innerHTML="<a name='"+d+"'></a><div name='"+d+"'></div>",y.insertBefore(e,y.firstChild);var t=g.getElementsByName&&g.getElementsByName(d).length===2+g.getElementsByName(d+0).length;return r=!g.getElementById(d),y.removeChild(e),t});try{x.call(y.childNodes,0)[0].nodeType}catch(tt){x=function(e){var t,n=[];for(;t=this[e];e++)n.push(t);return n}}nt.matches=function(e,t){return nt(e,null,null,t)},nt.matchesSelector=function(e,t){return nt(t,null,null,[e]).length>0},s=nt.getText=function(e){var t,n="",r=0,i=e.nodeType;if(i){if(i===1||i===9||i===11){if(typeof e.textContent=="string")return e.textContent;for(e=e.firstChild;e;e=e.nextSibling)n+=s(e)}else if(i===3||i===4)return e.nodeValue}else for(;t=e[r];r++)n+=s(t);return n},o=nt.isXML=function(e){var t=e&&(e.ownerDocument||e).documentElement;return t?t.nodeName!=="HTML":!1},u=nt.contains=y.contains?function(e,t){var n=e.nodeType===9?e.documentElement:e,r=t&&t.parentNode;return e===r||!!(r&&r.nodeType===1&&n.contains&&n.contains(r))}:y.compareDocumentPosition?function(e,t){return t&&!!(e.compareDocumentPosition(t)&16)}:function(e,t){while(t=t.parentNode)if(t===e)return!0;return!1},nt.attr=function(e,t){var n,r=o(e);return r||(t=t.toLowerCase()),(n=i.attrHandle[t])?n(e):r||Y?e.getAttribute(t):(n=e.getAttributeNode(t),n?typeof e[t]=="boolean"?e[t]?t:null:n.specified?n.value:null:null)},i=nt.selectors={cacheLength:50,createPseudo:N,match:J,attrHandle:G?{}:{href:function(e){return e.getAttribute("href",2)},type:function(e){return e.getAttribute("type")}},find:{ID:r?function(e,t,n){if(typeof t.getElementById!==p&&!n){var r=t.getElementById(e);return r&&r.parentNode?[r]:[]}}:function(e,n,r){if(typeof n.getElementById!==p&&!r){var i=n.getElementById(e);return i?i.id===e||typeof i.getAttributeNode!==p&&i.getAttributeNode("id").value===e?[i]:t:[]}},TAG:Q?function(e,t){if(typeof t.getElementsByTagName!==p)return t.getElementsByTagName(e)}:function(e,t){var n=t.getElementsByTagName(e);if(e==="*"){var r,i=[],s=0;for(;r=n[s];s++)r.nodeType===1&&i.push(r);return i}return n},NAME:et&&function(e,t){if(typeof t.getElementsByName!==p)return t.getElementsByName(name)},CLASS:Z&&function(e,t,n){if(typeof t.getElementsByClassName!==p&&!n)return t.getElementsByClassName(e)}},relative:{">":{dir:"parentNode",first:!0}," ":{dir:"parentNode"},"+":{dir:"previousSibling",first:!0},"~":{dir:"previousSibling"}},preFilter:{ATTR:function(e){return e[1]=e[1].replace($,""),e[3]=(e[4]||e[5]||"").replace($,""),e[2]==="~="&&(e[3]=" "+e[3]+" "),e.slice(0,4)},CHILD:function(e){return e[1]=e[1].toLowerCase(),e[1]==="nth"?(e[2]||nt.error(e[0]),e[3]=+(e[3]?e[4]+(e[5]||1):2*(e[2]==="even"||e[2]==="odd")),e[4]=+(e[6]+e[7]||e[2]==="odd")):e[2]&&nt.error(e[0]),e},PSEUDO:function(e){var t,n;if(J.CHILD.test(e[0]))return null;if(e[3])e[2]=e[3];else if(t=e[4])q.test(t)&&(n=ut(t,!0))&&(n=t.indexOf(")",t.length-n)-t.length)&&(t=t.slice(0,n),e[0]=e[0].slice(0,n)),e[2]=t;return e.slice(0,3)}},filter:{ID:r?function(e){return e=e.replace($,""),function(t){return t.getAttribute("id")===e}}:function(e){return e=e.replace($,""),function(t){var n=typeof t.getAttributeNode!==p&&t.getAttributeNode("id");return n&&n.value===e}},TAG:function(e){return e==="*"?function(){return!0}:(e=e.replace($,"").toLowerCase(),function(t){return t.nodeName&&t.nodeName.toLowerCase()===e})},CLASS:function(e){var t=k[d][e+" "];return t||(t=new RegExp("(^|"+O+")"+e+"("+O+"|$)"))&&k(e,function(e){return t.test(e.className||typeof e.getAttribute!==p&&e.getAttribute("class")||"")})},ATTR:function(e,t,n){return function(r,i){var s=nt.attr(r,e);return s==null?t==="!=":t?(s+="",t==="="?s===n:t==="!="?s!==n:t==="^="?n&&s.indexOf(n)===0:t==="*="?n&&s.indexOf(n)>-1:t==="$="?n&&s.substr(s.length-n.length)===n:t==="~="?(" "+s+" ").indexOf(n)>-1:t==="|="?s===n||s.substr(0,n.length+1)===n+"-":!1):!0}},CHILD:function(e,t,n,r){return e==="nth"?function(e){var t,i,s=e.parentNode;if(n===1&&r===0)return!0;if(s){i=0;for(t=s.firstChild;t;t=t.nextSibling)if(t.nodeType===1){i++;if(e===t)break}}return i-=r,i===n||i%n===0&&i/n>=0}:function(t){var n=t;switch(e){case"only":case"first":while(n=n.previousSibling)if(n.nodeType===1)return!1;if(e==="first")return!0;n=t;case"last":while(n=n.nextSibling)if(n.nodeType===1)return!1;return!0}}},PSEUDO:function(e,t){var n,r=i.pseudos[e]||i.setFilters[e.toLowerCase()]||nt.error("unsupported pseudo: "+e);return r[d]?r(t):r.length>1?(n=[e,e,"",t],i.setFilters.hasOwnProperty(e.toLowerCase())?N(function(e,n){var i,s=r(e,t),o=s.length;while(o--)i=T.call(e,s[o]),e[i]=!(n[i]=s[o])}):function(e){return r(e,0,n)}):r}},pseudos:{not:N(function(e){var t=[],n=[],r=a(e.replace(j,"$1"));return r[d]?N(function(e,t,n,i){var s,o=r(e,null,i,[]),u=e.length;while(u--)if(s=o[u])e[u]=!(t[u]=s)}):function(e,i,s){return t[0]=e,r(t,null,s,n),!n.pop()}}),has:N(function(e){return function(t){return nt(e,t).length>0}}),contains:N(function(e){return function(t){return(t.textContent||t.innerText||s(t)).indexOf(e)>-1}}),enabled:function(e){return e.disabled===!1},disabled:function(e){return e.disabled===!0},checked:function(e){var t=e.nodeName.toLowerCase();return t==="input"&&!!e.checked||t==="option"&&!!e.selected},selected:function(e){return e.parentNode&&e.parentNode.selectedIndex,e.selected===!0},parent:function(e){return!i.pseudos.empty(e)},empty:function(e){var t;e=e.firstChild;while(e){if(e.nodeName>"@"||(t=e.nodeType)===3||t===4)return!1;e=e.nextSibling}return!0},header:function(e){return X.test(e.nodeName)},text:function(e){var t,n;return e.nodeName.toLowerCase()==="input"&&(t=e.type)==="text"&&((n=e.getAttribute("type"))==null||n.toLowerCase()===t)},radio:rt("radio"),checkbox:rt("checkbox"),file:rt("file"),password:rt("password"),image:rt("image"),submit:it("submit"),reset:it("reset"),button:function(e){var t=e.nodeName.toLowerCase();return t==="input"&&e.type==="button"||t==="button"},input:function(e){return V.test(e.nodeName)},focus:function(e){var t=e.ownerDocument;return e===t.activeElement&&(!t.hasFocus||t.hasFocus())&&!!(e.type||e.href||~e.tabIndex)},active:function(e){return e===e.ownerDocument.activeElement},first:st(function(){return[0]}),last:st(function(e,t){return[t-1]}),eq:st(function(e,t,n){return[n<0?n+t:n]}),even:st(function(e,t){for(var n=0;n<t;n+=2)e.push(n);return e}),odd:st(function(e,t){for(var n=1;n<t;n+=2)e.push(n);return e}),lt:st(function(e,t,n){for(var r=n<0?n+t:n;--r>=0;)e.push(r);return e}),gt:st(function(e,t,n){for(var r=n<0?n+t:n;++r<t;)e.push(r);return e})}},f=y.compareDocumentPosition?function(e,t){return e===t?(l=!0,0):(!e.compareDocumentPosition||!t.compareDocumentPosition?e.compareDocumentPosition:e.compareDocumentPosition(t)&4)?-1:1}:function(e,t){if(e===t)return l=!0,0;if(e.sourceIndex&&t.sourceIndex)return e.sourceIndex-t.sourceIndex;var n,r,i=[],s=[],o=e.parentNode,u=t.parentNode,a=o;if(o===u)return ot(e,t);if(!o)return-1;if(!u)return 1;while(a)i.unshift(a),a=a.parentNode;a=u;while(a)s.unshift(a),a=a.parentNode;n=i.length,r=s.length;for(var f=0;f<n&&f<r;f++)if(i[f]!==s[f])return ot(i[f],s[f]);return f===n?ot(e,s[f],-1):ot(i[f],t,1)},[0,0].sort(f),h=!l,nt.uniqueSort=function(e){var t,n=[],r=1,i=0;l=h,e.sort(f);if(l){for(;t=e[r];r++)t===e[r-1]&&(i=n.push(r));while(i--)e.splice(n[i],1)}return e},nt.error=function(e){throw new Error("Syntax error, unrecognized expression: "+e)},a=nt.compile=function(e,t){var n,r=[],i=[],s=A[d][e+" "];if(!s){t||(t=ut(e)),n=t.length;while(n--)s=ht(t[n]),s[d]?r.push(s):i.push(s);s=A(e,pt(i,r))}return s},g.querySelectorAll&&function(){var e,t=vt,n=/'|\\/g,r=/\=[\x20\t\r\n\f]*([^'"\]]*)[\x20\t\r\n\f]*\]/g,i=[":focus"],s=[":active"],u=y.matchesSelector||y.mozMatchesSelector||y.webkitMatchesSelector||y.oMatchesSelector||y.msMatchesSelector;K(function(e){e.innerHTML="<select><option selected=''></option></select>",e.querySelectorAll("[selected]").length||i.push("\\["+O+"*(?:checked|disabled|ismap|multiple|readonly|selected|value)"),e.querySelectorAll(":checked").length||i.push(":checked")}),K(function(e){e.innerHTML="<p test=''></p>",e.querySelectorAll("[test^='']").length&&i.push("[*^$]="+O+"*(?:\"\"|'')"),e.innerHTML="<input type='hidden'/>",e.querySelectorAll(":enabled").length||i.push(":enabled",":disabled")}),i=new RegExp(i.join("|")),vt=function(e,r,s,o,u){if(!o&&!u&&!i.test(e)){var a,f,l=!0,c=d,h=r,p=r.nodeType===9&&e;if(r.nodeType===1&&r.nodeName.toLowerCase()!=="object"){a=ut(e),(l=r.getAttribute("id"))?c=l.replace(n,"\\$&"):r.setAttribute("id",c),c="[id='"+c+"'] ",f=a.length;while(f--)a[f]=c+a[f].join("");h=z.test(e)&&r.parentNode||r,p=a.join(",")}if(p)try{return S.apply(s,x.call(h.querySelectorAll(p),0)),s}catch(v){}finally{l||r.removeAttribute("id")}}return t(e,r,s,o,u)},u&&(K(function(t){e=u.call(t,"div");try{u.call(t,"[test!='']:sizzle"),s.push("!=",H)}catch(n){}}),s=new RegExp(s.join("|")),nt.matchesSelector=function(t,n){n=n.replace(r,"='$1']");if(!o(t)&&!s.test(n)&&!i.test(n))try{var a=u.call(t,n);if(a||e||t.document&&t.document.nodeType!==11)return a}catch(f){}return nt(n,null,null,[t]).length>0})}(),i.pseudos.nth=i.pseudos.eq,i.filters=mt.prototype=i.pseudos,i.setFilters=new mt,nt.attr=v.attr,v.find=nt,v.expr=nt.selectors,v.expr[":"]=v.expr.pseudos,v.unique=nt.uniqueSort,v.text=nt.getText,v.isXMLDoc=nt.isXML,v.contains=nt.contains}(e);var nt=/Until$/,rt=/^(?:parents|prev(?:Until|All))/,it=/^.[^:#\[\.,]*$/,st=v.expr.match.needsContext,ot={children:!0,contents:!0,next:!0,prev:!0};v.fn.extend({find:function(e){var t,n,r,i,s,o,u=this;if(typeof e!="string")return v(e).filter(function(){for(t=0,n=u.length;t<n;t++)if(v.contains(u[t],this))return!0});o=this.pushStack("","find",e);for(t=0,n=this.length;t<n;t++){r=o.length,v.find(e,this[t],o);if(t>0)for(i=r;i<o.length;i++)for(s=0;s<r;s++)if(o[s]===o[i]){o.splice(i--,1);break}}return o},has:function(e){var t,n=v(e,this),r=n.length;return this.filter(function(){for(t=0;t<r;t++)if(v.contains(this,n[t]))return!0})},not:function(e){return this.pushStack(ft(this,e,!1),"not",e)},filter:function(e){return this.pushStack(ft(this,e,!0),"filter",e)},is:function(e){return!!e&&(typeof e=="string"?st.test(e)?v(e,this.context).index(this[0])>=0:v.filter(e,this).length>0:this.filter(e).length>0)},closest:function(e,t){var n,r=0,i=this.length,s=[],o=st.test(e)||typeof e!="string"?v(e,t||this.context):0;for(;r<i;r++){n=this[r];while(n&&n.ownerDocument&&n!==t&&n.nodeType!==11){if(o?o.index(n)>-1:v.find.matchesSelector(n,e)){s.push(n);break}n=n.parentNode}}return s=s.length>1?v.unique(s):s,this.pushStack(s,"closest",e)},index:function(e){return e?typeof e=="string"?v.inArray(this[0],v(e)):v.inArray(e.jquery?e[0]:e,this):this[0]&&this[0].parentNode?this.prevAll().length:-1},add:function(e,t){var n=typeof e=="string"?v(e,t):v.makeArray(e&&e.nodeType?[e]:e),r=v.merge(this.get(),n);return this.pushStack(ut(n[0])||ut(r[0])?r:v.unique(r))},addBack:function(e){return this.add(e==null?this.prevObject:this.prevObject.filter(e))}}),v.fn.andSelf=v.fn.addBack,v.each({parent:function(e){var t=e.parentNode;return t&&t.nodeType!==11?t:null},parents:function(e){return v.dir(e,"parentNode")},parentsUntil:function(e,t,n){return v.dir(e,"parentNode",n)},next:function(e){return at(e,"nextSibling")},prev:function(e){return at(e,"previousSibling")},nextAll:function(e){return v.dir(e,"nextSibling")},prevAll:function(e){return v.dir(e,"previousSibling")},nextUntil:function(e,t,n){return v.dir(e,"nextSibling",n)},prevUntil:function(e,t,n){return v.dir(e,"previousSibling",n)},siblings:function(e){return v.sibling((e.parentNode||{}).firstChild,e)},children:function(e){return v.sibling(e.firstChild)},contents:function(e){return v.nodeName(e,"iframe")?e.contentDocument||e.contentWindow.document:v.merge([],e.childNodes)}},function(e,t){v.fn[e]=function(n,r){var i=v.map(this,t,n);return nt.test(e)||(r=n),r&&typeof r=="string"&&(i=v.filter(r,i)),i=this.length>1&&!ot[e]?v.unique(i):i,this.length>1&&rt.test(e)&&(i=i.reverse()),this.pushStack(i,e,l.call(arguments).join(","))}}),v.extend({filter:function(e,t,n){return n&&(e=":not("+e+")"),t.length===1?v.find.matchesSelector(t[0],e)?[t[0]]:[]:v.find.matches(e,t)},dir:function(e,n,r){var i=[],s=e[n];while(s&&s.nodeType!==9&&(r===t||s.nodeType!==1||!v(s).is(r)))s.nodeType===1&&i.push(s),s=s[n];return i},sibling:function(e,t){var n=[];for(;e;e=e.nextSibling)e.nodeType===1&&e!==t&&n.push(e);return n}});var ct="abbr|article|aside|audio|bdi|canvas|data|datalist|details|figcaption|figure|footer|header|hgroup|mark|meter|nav|output|progress|section|summary|time|video",ht=/ jQuery\d+="(?:null|\d+)"/g,pt=/^\s+/,dt=/<(?!area|br|col|embed|hr|img|input|link|meta|param)(([\w:]+)[^>]*)\/>/gi,vt=/<([\w:]+)/,mt=/<tbody/i,gt=/<|&#?\w+;/,yt=/<(?:script|style|link)/i,bt=/<(?:script|object|embed|option|style)/i,wt=new RegExp("<(?:"+ct+")[\\s/>]","i"),Et=/^(?:checkbox|radio)$/,St=/checked\s*(?:[^=]|=\s*.checked.)/i,xt=/\/(java|ecma)script/i,Tt=/^\s*<!(?:\[CDATA\[|\-\-)|[\]\-]{2}>\s*$/g,Nt={option:[1,"<select multiple='multiple'>","</select>"],legend:[1,"<fieldset>","</fieldset>"],thead:[1,"<table>","</table>"],tr:[2,"<table><tbody>","</tbody></table>"],td:[3,"<table><tbody><tr>","</tr></tbody></table>"],col:[2,"<table><tbody></tbody><colgroup>","</colgroup></table>"],area:[1,"<map>","</map>"],_default:[0,"",""]},Ct=lt(i),kt=Ct.appendChild(i.createElement("div"));Nt.optgroup=Nt.option,Nt.tbody=Nt.tfoot=Nt.colgroup=Nt.caption=Nt.thead,Nt.th=Nt.td,v.support.htmlSerialize||(Nt._default=[1,"X<div>","</div>"]),v.fn.extend({text:function(e){return v.access(this,function(e){return e===t?v.text(this):this.empty().append((this[0]&&this[0].ownerDocument||i).createTextNode(e))},null,e,arguments.length)},wrapAll:function(e){if(v.isFunction(e))return this.each(function(t){v(this).wrapAll(e.call(this,t))});if(this[0]){var t=v(e,this[0].ownerDocument).eq(0).clone(!0);this[0].parentNode&&t.insertBefore(this[0]),t.map(function(){var e=this;while(e.firstChild&&e.firstChild.nodeType===1)e=e.firstChild;return e}).append(this)}return this},wrapInner:function(e){return v.isFunction(e)?this.each(function(t){v(this).wrapInner(e.call(this,t))}):this.each(function(){var t=v(this),n=t.contents();n.length?n.wrapAll(e):t.append(e)})},wrap:function(e){var t=v.isFunction(e);return this.each(function(n){v(this).wrapAll(t?e.call(this,n):e)})},unwrap:function(){return this.parent().each(function(){v.nodeName(this,"body")||v(this).replaceWith(this.childNodes)}).end()},append:function(){return this.domManip(arguments,!0,function(e){(this.nodeType===1||this.nodeType===11)&&this.appendChild(e)})},prepend:function(){return this.domManip(arguments,!0,function(e){(this.nodeType===1||this.nodeType===11)&&this.insertBefore(e,this.firstChild)})},before:function(){if(!ut(this[0]))return this.domManip(arguments,!1,function(e){this.parentNode.insertBefore(e,this)});if(arguments.length){var e=v.clean(arguments);return this.pushStack(v.merge(e,this),"before",this.selector)}},after:function(){if(!ut(this[0]))return this.domManip(arguments,!1,function(e){this.parentNode.insertBefore(e,this.nextSibling)});if(arguments.length){var e=v.clean(arguments);return this.pushStack(v.merge(this,e),"after",this.selector)}},remove:function(e,t){var n,r=0;for(;(n=this[r])!=null;r++)if(!e||v.filter(e,[n]).length)!t&&n.nodeType===1&&(v.cleanData(n.getElementsByTagName("*")),v.cleanData([n])),n.parentNode&&n.parentNode.removeChild(n);return this},empty:function(){var e,t=0;for(;(e=this[t])!=null;t++){e.nodeType===1&&v.cleanData(e.getElementsByTagName("*"));while(e.firstChild)e.removeChild(e.firstChild)}return this},clone:function(e,t){return e=e==null?!1:e,t=t==null?e:t,this.map(function(){return v.clone(this,e,t)})},html:function(e){return v.access(this,function(e){var n=this[0]||{},r=0,i=this.length;if(e===t)return n.nodeType===1?n.innerHTML.replace(ht,""):t;if(typeof e=="string"&&!yt.test(e)&&(v.support.htmlSerialize||!wt.test(e))&&(v.support.leadingWhitespace||!pt.test(e))&&!Nt[(vt.exec(e)||["",""])[1].toLowerCase()]){e=e.replace(dt,"<$1></$2>");try{for(;r<i;r++)n=this[r]||{},n.nodeType===1&&(v.cleanData(n.getElementsByTagName("*")),n.innerHTML=e);n=0}catch(s){}}n&&this.empty().append(e)},null,e,arguments.length)},replaceWith:function(e){return ut(this[0])?this.length?this.pushStack(v(v.isFunction(e)?e():e),"replaceWith",e):this:v.isFunction(e)?this.each(function(t){var n=v(this),r=n.html();n.replaceWith(e.call(this,t,r))}):(typeof e!="string"&&(e=v(e).detach()),this.each(function(){var t=this.nextSibling,n=this.parentNode;v(this).remove(),t?v(t).before(e):v(n).append(e)}))},detach:function(e){return this.remove(e,!0)},domManip:function(e,n,r){e=[].concat.apply([],e);var i,s,o,u,a=0,f=e[0],l=[],c=this.length;if(!v.support.checkClone&&c>1&&typeof f=="string"&&St.test(f))return this.each(function(){v(this).domManip(e,n,r)});if(v.isFunction(f))return this.each(function(i){var s=v(this);e[0]=f.call(this,i,n?s.html():t),s.domManip(e,n,r)});if(this[0]){i=v.buildFragment(e,this,l),o=i.fragment,s=o.firstChild,o.childNodes.length===1&&(o=s);if(s){n=n&&v.nodeName(s,"tr");for(u=i.cacheable||c-1;a<c;a++)r.call(n&&v.nodeName(this[a],"table")?Lt(this[a],"tbody"):this[a],a===u?o:v.clone(o,!0,!0))}o=s=null,l.length&&v.each(l,function(e,t){t.src?v.ajax?v.ajax({url:t.src,type:"GET",dataType:"script",async:!1,global:!1,"throws":!0}):v.error("no ajax"):v.globalEval((t.text||t.textContent||t.innerHTML||"").replace(Tt,"")),t.parentNode&&t.parentNode.removeChild(t)})}return this}}),v.buildFragment=function(e,n,r){var s,o,u,a=e[0];return n=n||i,n=!n.nodeType&&n[0]||n,n=n.ownerDocument||n,e.length===1&&typeof a=="string"&&a.length<512&&n===i&&a.charAt(0)==="<"&&!bt.test(a)&&(v.support.checkClone||!St.test(a))&&(v.support.html5Clone||!wt.test(a))&&(o=!0,s=v.fragments[a],u=s!==t),s||(s=n.createDocumentFragment(),v.clean(e,n,s,r),o&&(v.fragments[a]=u&&s)),{fragment:s,cacheable:o}},v.fragments={},v.each({appendTo:"append",prependTo:"prepend",insertBefore:"before",insertAfter:"after",replaceAll:"replaceWith"},function(e,t){v.fn[e]=function(n){var r,i=0,s=[],o=v(n),u=o.length,a=this.length===1&&this[0].parentNode;if((a==null||a&&a.nodeType===11&&a.childNodes.length===1)&&u===1)return o[t](this[0]),this;for(;i<u;i++)r=(i>0?this.clone(!0):this).get(),v(o[i])[t](r),s=s.concat(r);return this.pushStack(s,e,o.selector)}}),v.extend({clone:function(e,t,n){var r,i,s,o;v.support.html5Clone||v.isXMLDoc(e)||!wt.test("<"+e.nodeName+">")?o=e.cloneNode(!0):(kt.innerHTML=e.outerHTML,kt.removeChild(o=kt.firstChild));if((!v.support.noCloneEvent||!v.support.noCloneChecked)&&(e.nodeType===1||e.nodeType===11)&&!v.isXMLDoc(e)){Ot(e,o),r=Mt(e),i=Mt(o);for(s=0;r[s];++s)i[s]&&Ot(r[s],i[s])}if(t){At(e,o);if(n){r=Mt(e),i=Mt(o);for(s=0;r[s];++s)At(r[s],i[s])}}return r=i=null,o},clean:function(e,t,n,r){var s,o,u,a,f,l,c,h,p,d,m,g,y=t===i&&Ct,b=[];if(!t||typeof t.createDocumentFragment=="undefined")t=i;for(s=0;(u=e[s])!=null;s++){typeof u=="number"&&(u+="");if(!u)continue;if(typeof u=="string")if(!gt.test(u))u=t.createTextNode(u);else{y=y||lt(t),c=t.createElement("div"),y.appendChild(c),u=u.replace(dt,"<$1></$2>"),a=(vt.exec(u)||["",""])[1].toLowerCase(),f=Nt[a]||Nt._default,l=f[0],c.innerHTML=f[1]+u+f[2];while(l--)c=c.lastChild;if(!v.support.tbody){h=mt.test(u),p=a==="table"&&!h?c.firstChild&&c.firstChild.childNodes:f[1]==="<table>"&&!h?c.childNodes:[];for(o=p.length-1;o>=0;--o)v.nodeName(p[o],"tbody")&&!p[o].childNodes.length&&p[o].parentNode.removeChild(p[o])}!v.support.leadingWhitespace&&pt.test(u)&&c.insertBefore(t.createTextNode(pt.exec(u)[0]),c.firstChild),u=c.childNodes,c.parentNode.removeChild(c)}u.nodeType?b.push(u):v.merge(b,u)}c&&(u=c=y=null);if(!v.support.appendChecked)for(s=0;(u=b[s])!=null;s++)v.nodeName(u,"input")?_t(u):typeof u.getElementsByTagName!="undefined"&&v.grep(u.getElementsByTagName("input"),_t);if(n){m=function(e){if(!e.type||xt.test(e.type))return r?r.push(e.parentNode?e.parentNode.removeChild(e):e):n.appendChild(e)};for(s=0;(u=b[s])!=null;s++)if(!v.nodeName(u,"script")||!m(u))n.appendChild(u),typeof u.getElementsByTagName!="undefined"&&(g=v.grep(v.merge([],u.getElementsByTagName("script")),m),b.splice.apply(b,[s+1,0].concat(g)),s+=g.length)}return b},cleanData:function(e,t){var n,r,i,s,o=0,u=v.expando,a=v.cache,f=v.support.deleteExpando,l=v.event.special;for(;(i=e[o])!=null;o++)if(t||v.acceptData(i)){r=i[u],n=r&&a[r];if(n){if(n.events)for(s in n.events)l[s]?v.event.remove(i,s):v.removeEvent(i,s,n.handle);a[r]&&(delete a[r],f?delete i[u]:i.removeAttribute?i.removeAttribute(u):i[u]=null,v.deletedIds.push(r))}}}}),function(){var e,t;v.uaMatch=function(e){e=e.toLowerCase();var t=/(chrome)[ \/]([\w.]+)/.exec(e)||/(webkit)[ \/]([\w.]+)/.exec(e)||/(opera)(?:.*version|)[ \/]([\w.]+)/.exec(e)||/(msie) ([\w.]+)/.exec(e)||e.indexOf("compatible")<0&&/(mozilla)(?:.*? rv:([\w.]+)|)/.exec(e)||[];return{browser:t[1]||"",version:t[2]||"0"}},e=v.uaMatch(o.userAgent),t={},e.browser&&(t[e.browser]=!0,t.version=e.version),t.chrome?t.webkit=!0:t.webkit&&(t.safari=!0),v.browser=t,v.sub=function(){function e(t,n){return new e.fn.init(t,n)}v.extend(!0,e,this),e.superclass=this,e.fn=e.prototype=this(),e.fn.constructor=e,e.sub=this.sub,e.fn.init=function(r,i){return i&&i instanceof v&&!(i instanceof e)&&(i=e(i)),v.fn.init.call(this,r,i,t)},e.fn.init.prototype=e.fn;var t=e(i);return e}}();var Dt,Pt,Ht,Bt=/alpha\([^)]*\)/i,jt=/opacity=([^)]*)/,Ft=/^(top|right|bottom|left)$/,It=/^(none|table(?!-c[ea]).+)/,qt=/^margin/,Rt=new RegExp("^("+m+")(.*)$","i"),Ut=new RegExp("^("+m+")(?!px)[a-z%]+$","i"),zt=new RegExp("^([-+])=("+m+")","i"),Wt={BODY:"block"},Xt={position:"absolute",visibility:"hidden",display:"block"},Vt={letterSpacing:0,fontWeight:400},$t=["Top","Right","Bottom","Left"],Jt=["Webkit","O","Moz","ms"],Kt=v.fn.toggle;v.fn.extend({css:function(e,n){return v.access(this,function(e,n,r){return r!==t?v.style(e,n,r):v.css(e,n)},e,n,arguments.length>1)},show:function(){return Yt(this,!0)},hide:function(){return Yt(this)},toggle:function(e,t){var n=typeof e=="boolean";return v.isFunction(e)&&v.isFunction(t)?Kt.apply(this,arguments):this.each(function(){(n?e:Gt(this))?v(this).show():v(this).hide()})}}),v.extend({cssHooks:{opacity:{get:function(e,t){if(t){var n=Dt(e,"opacity");return n===""?"1":n}}}},cssNumber:{fillOpacity:!0,fontWeight:!0,lineHeight:!0,opacity:!0,orphans:!0,widows:!0,zIndex:!0,zoom:!0},cssProps:{"float":v.support.cssFloat?"cssFloat":"styleFloat"},style:function(e,n,r,i){if(!e||e.nodeType===3||e.nodeType===8||!e.style)return;var s,o,u,a=v.camelCase(n),f=e.style;n=v.cssProps[a]||(v.cssProps[a]=Qt(f,a)),u=v.cssHooks[n]||v.cssHooks[a];if(r===t)return u&&"get"in u&&(s=u.get(e,!1,i))!==t?s:f[n];o=typeof r,o==="string"&&(s=zt.exec(r))&&(r=(s[1]+1)*s[2]+parseFloat(v.css(e,n)),o="number");if(r==null||o==="number"&&isNaN(r))return;o==="number"&&!v.cssNumber[a]&&(r+="px");if(!u||!("set"in u)||(r=u.set(e,r,i))!==t)try{f[n]=r}catch(l){}},css:function(e,n,r,i){var s,o,u,a=v.camelCase(n);return n=v.cssProps[a]||(v.cssProps[a]=Qt(e.style,a)),u=v.cssHooks[n]||v.cssHooks[a],u&&"get"in u&&(s=u.get(e,!0,i)),s===t&&(s=Dt(e,n)),s==="normal"&&n in Vt&&(s=Vt[n]),r||i!==t?(o=parseFloat(s),r||v.isNumeric(o)?o||0:s):s},swap:function(e,t,n){var r,i,s={};for(i in t)s[i]=e.style[i],e.style[i]=t[i];r=n.call(e);for(i in t)e.style[i]=s[i];return r}}),e.getComputedStyle?Dt=function(t,n){var r,i,s,o,u=e.getComputedStyle(t,null),a=t.style;return u&&(r=u.getPropertyValue(n)||u[n],r===""&&!v.contains(t.ownerDocument,t)&&(r=v.style(t,n)),Ut.test(r)&&qt.test(n)&&(i=a.width,s=a.minWidth,o=a.maxWidth,a.minWidth=a.maxWidth=a.width=r,r=u.width,a.width=i,a.minWidth=s,a.maxWidth=o)),r}:i.documentElement.currentStyle&&(Dt=function(e,t){var n,r,i=e.currentStyle&&e.currentStyle[t],s=e.style;return i==null&&s&&s[t]&&(i=s[t]),Ut.test(i)&&!Ft.test(t)&&(n=s.left,r=e.runtimeStyle&&e.runtimeStyle.left,r&&(e.runtimeStyle.left=e.currentStyle.left),s.left=t==="fontSize"?"1em":i,i=s.pixelLeft+"px",s.left=n,r&&(e.runtimeStyle.left=r)),i===""?"auto":i}),v.each(["height","width"],function(e,t){v.cssHooks[t]={get:function(e,n,r){if(n)return e.offsetWidth===0&&It.test(Dt(e,"display"))?v.swap(e,Xt,function(){return tn(e,t,r)}):tn(e,t,r)},set:function(e,n,r){return Zt(e,n,r?en(e,t,r,v.support.boxSizing&&v.css(e,"boxSizing")==="border-box"):0)}}}),v.support.opacity||(v.cssHooks.opacity={get:function(e,t){return jt.test((t&&e.currentStyle?e.currentStyle.filter:e.style.filter)||"")?.01*parseFloat(RegExp.$1)+"":t?"1":""},set:function(e,t){var n=e.style,r=e.currentStyle,i=v.isNumeric(t)?"alpha(opacity="+t*100+")":"",s=r&&r.filter||n.filter||"";n.zoom=1;if(t>=1&&v.trim(s.replace(Bt,""))===""&&n.removeAttribute){n.removeAttribute("filter");if(r&&!r.filter)return}n.filter=Bt.test(s)?s.replace(Bt,i):s+" "+i}}),v(function(){v.support.reliableMarginRight||(v.cssHooks.marginRight={get:function(e,t){return v.swap(e,{display:"inline-block"},function(){if(t)return Dt(e,"marginRight")})}}),!v.support.pixelPosition&&v.fn.position&&v.each(["top","left"],function(e,t){v.cssHooks[t]={get:function(e,n){if(n){var r=Dt(e,t);return Ut.test(r)?v(e).position()[t]+"px":r}}}})}),v.expr&&v.expr.filters&&(v.expr.filters.hidden=function(e){return e.offsetWidth===0&&e.offsetHeight===0||!v.support.reliableHiddenOffsets&&(e.style&&e.style.display||Dt(e,"display"))==="none"},v.expr.filters.visible=function(e){return!v.expr.filters.hidden(e)}),v.each({margin:"",padding:"",border:"Width"},function(e,t){v.cssHooks[e+t]={expand:function(n){var r,i=typeof n=="string"?n.split(" "):[n],s={};for(r=0;r<4;r++)s[e+$t[r]+t]=i[r]||i[r-2]||i[0];return s}},qt.test(e)||(v.cssHooks[e+t].set=Zt)});var rn=/%20/g,sn=/\[\]$/,on=/\r?\n/g,un=/^(?:color|date|datetime|datetime-local|email|hidden|month|number|password|range|search|tel|text|time|url|week)$/i,an=/^(?:select|textarea)/i;v.fn.extend({serialize:function(){return v.param(this.serializeArray())},serializeArray:function(){return this.map(function(){return this.elements?v.makeArray(this.elements):this}).filter(function(){return this.name&&!this.disabled&&(this.checked||an.test(this.nodeName)||un.test(this.type))}).map(function(e,t){var n=v(this).val();return n==null?null:v.isArray(n)?v.map(n,function(e,n){return{name:t.name,value:e.replace(on,"\r\n")}}):{name:t.name,value:n.replace(on,"\r\n")}}).get()}}),v.param=function(e,n){var r,i=[],s=function(e,t){t=v.isFunction(t)?t():t==null?"":t,i[i.length]=encodeURIComponent(e)+"="+encodeURIComponent(t)};n===t&&(n=v.ajaxSettings&&v.ajaxSettings.traditional);if(v.isArray(e)||e.jquery&&!v.isPlainObject(e))v.each(e,function(){s(this.name,this.value)});else for(r in e)fn(r,e[r],n,s);return i.join("&").replace(rn,"+")};var ln,cn,hn=/#.*$/,pn=/^(.*?):[ \t]*([^\r\n]*)\r?$/mg,dn=/^(?:about|app|app\-storage|.+\-extension|file|res|widget):$/,vn=/^(?:GET|HEAD)$/,mn=/^\/\//,gn=/\?/,yn=/<script\b[^<]*(?:(?!<\/script>)<[^<]*)*<\/script>/gi,bn=/([?&])_=[^&]*/,wn=/^([\w\+\.\-]+:)(?:\/\/([^\/?#:]*)(?::(\d+)|)|)/,En=v.fn.load,Sn={},xn={},Tn=["*/"]+["*"];try{cn=s.href}catch(Nn){cn=i.createElement("a"),cn.href="",cn=cn.href}ln=wn.exec(cn.toLowerCase())||[],v.fn.load=function(e,n,r){if(typeof e!="string"&&En)return En.apply(this,arguments);if(!this.length)return this;var i,s,o,u=this,a=e.indexOf(" ");return a>=0&&(i=e.slice(a,e.length),e=e.slice(0,a)),v.isFunction(n)?(r=n,n=t):n&&typeof n=="object"&&(s="POST"),v.ajax({url:e,type:s,dataType:"html",data:n,complete:function(e,t){r&&u.each(r,o||[e.responseText,t,e])}}).done(function(e){o=arguments,u.html(i?v("<div>").append(e.replace(yn,"")).find(i):e)}),this},v.each("ajaxStart ajaxStop ajaxComplete ajaxError ajaxSuccess ajaxSend".split(" "),function(e,t){v.fn[t]=function(e){return this.on(t,e)}}),v.each(["get","post"],function(e,n){v[n]=function(e,r,i,s){return v.isFunction(r)&&(s=s||i,i=r,r=t),v.ajax({type:n,url:e,data:r,success:i,dataType:s})}}),v.extend({getScript:function(e,n){return v.get(e,t,n,"script")},getJSON:function(e,t,n){return v.get(e,t,n,"json")},ajaxSetup:function(e,t){return t?Ln(e,v.ajaxSettings):(t=e,e=v.ajaxSettings),Ln(e,t),e},ajaxSettings:{url:cn,isLocal:dn.test(ln[1]),global:!0,type:"GET",contentType:"application/x-www-form-urlencoded; charset=UTF-8",processData:!0,async:!0,accepts:{xml:"application/xml, text/xml",html:"text/html",text:"text/plain",json:"application/json, text/javascript","*":Tn},contents:{xml:/xml/,html:/html/,json:/json/},responseFields:{xml:"responseXML",text:"responseText"},converters:{"* text":e.String,"text html":!0,"text json":v.parseJSON,"text xml":v.parseXML},flatOptions:{context:!0,url:!0}},ajaxPrefilter:Cn(Sn),ajaxTransport:Cn(xn),ajax:function(e,n){function T(e,n,s,a){var l,y,b,w,S,T=n;if(E===2)return;E=2,u&&clearTimeout(u),o=t,i=a||"",x.readyState=e>0?4:0,s&&(w=An(c,x,s));if(e>=200&&e<300||e===304)c.ifModified&&(S=x.getResponseHeader("Last-Modified"),S&&(v.lastModified[r]=S),S=x.getResponseHeader("Etag"),S&&(v.etag[r]=S)),e===304?(T="notmodified",l=!0):(l=On(c,w),T=l.state,y=l.data,b=l.error,l=!b);else{b=T;if(!T||e)T="error",e<0&&(e=0)}x.status=e,x.statusText=(n||T)+"",l?d.resolveWith(h,[y,T,x]):d.rejectWith(h,[x,T,b]),x.statusCode(g),g=t,f&&p.trigger("ajax"+(l?"Success":"Error"),[x,c,l?y:b]),m.fireWith(h,[x,T]),f&&(p.trigger("ajaxComplete",[x,c]),--v.active||v.event.trigger("ajaxStop"))}typeof e=="object"&&(n=e,e=t),n=n||{};var r,i,s,o,u,a,f,l,c=v.ajaxSetup({},n),h=c.context||c,p=h!==c&&(h.nodeType||h instanceof v)?v(h):v.event,d=v.Deferred(),m=v.Callbacks("once memory"),g=c.statusCode||{},b={},w={},E=0,S="canceled",x={readyState:0,setRequestHeader:function(e,t){if(!E){var n=e.toLowerCase();e=w[n]=w[n]||e,b[e]=t}return this},getAllResponseHeaders:function(){return E===2?i:null},getResponseHeader:function(e){var n;if(E===2){if(!s){s={};while(n=pn.exec(i))s[n[1].toLowerCase()]=n[2]}n=s[e.toLowerCase()]}return n===t?null:n},overrideMimeType:function(e){return E||(c.mimeType=e),this},abort:function(e){return e=e||S,o&&o.abort(e),T(0,e),this}};d.promise(x),x.success=x.done,x.error=x.fail,x.complete=m.add,x.statusCode=function(e){if(e){var t;if(E<2)for(t in e)g[t]=[g[t],e[t]];else t=e[x.status],x.always(t)}return this},c.url=((e||c.url)+"").replace(hn,"").replace(mn,ln[1]+"//"),c.dataTypes=v.trim(c.dataType||"*").toLowerCase().split(y),c.crossDomain==null&&(a=wn.exec(c.url.toLowerCase()),c.crossDomain=!(!a||a[1]===ln[1]&&a[2]===ln[2]&&(a[3]||(a[1]==="http:"?80:443))==(ln[3]||(ln[1]==="http:"?80:443)))),c.data&&c.processData&&typeof c.data!="string"&&(c.data=v.param(c.data,c.traditional)),kn(Sn,c,n,x);if(E===2)return x;f=c.global,c.type=c.type.toUpperCase(),c.hasContent=!vn.test(c.type),f&&v.active++===0&&v.event.trigger("ajaxStart");if(!c.hasContent){c.data&&(c.url+=(gn.test(c.url)?"&":"?")+c.data,delete c.data),r=c.url;if(c.cache===!1){var N=v.now(),C=c.url.replace(bn,"$1_="+N);c.url=C+(C===c.url?(gn.test(c.url)?"&":"?")+"_="+N:"")}}(c.data&&c.hasContent&&c.contentType!==!1||n.contentType)&&x.setRequestHeader("Content-Type",c.contentType),c.ifModified&&(r=r||c.url,v.lastModified[r]&&x.setRequestHeader("If-Modified-Since",v.lastModified[r]),v.etag[r]&&x.setRequestHeader("If-None-Match",v.etag[r])),x.setRequestHeader("Accept",c.dataTypes[0]&&c.accepts[c.dataTypes[0]]?c.accepts[c.dataTypes[0]]+(c.dataTypes[0]!=="*"?", "+Tn+"; q=0.01":""):c.accepts["*"]);for(l in c.headers)x.setRequestHeader(l,c.headers[l]);if(!c.beforeSend||c.beforeSend.call(h,x,c)!==!1&&E!==2){S="abort";for(l in{success:1,error:1,complete:1})x[l](c[l]);o=kn(xn,c,n,x);if(!o)T(-1,"No Transport");else{x.readyState=1,f&&p.trigger("ajaxSend",[x,c]),c.async&&c.timeout>0&&(u=setTimeout(function(){x.abort("timeout")},c.timeout));try{E=1,o.send(b,T)}catch(k){if(!(E<2))throw k;T(-1,k)}}return x}return x.abort()},active:0,lastModified:{},etag:{}});var Mn=[],_n=/\?/,Dn=/(=)\?(?=&|$)|\?\?/,Pn=v.now();v.ajaxSetup({jsonp:"callback",jsonpCallback:function(){var e=Mn.pop()||v.expando+"_"+Pn++;return this[e]=!0,e}}),v.ajaxPrefilter("json jsonp",function(n,r,i){var s,o,u,a=n.data,f=n.url,l=n.jsonp!==!1,c=l&&Dn.test(f),h=l&&!c&&typeof a=="string"&&!(n.contentType||"").indexOf("application/x-www-form-urlencoded")&&Dn.test(a);if(n.dataTypes[0]==="jsonp"||c||h)return s=n.jsonpCallback=v.isFunction(n.jsonpCallback)?n.jsonpCallback():n.jsonpCallback,o=e[s],c?n.url=f.replace(Dn,"$1"+s):h?n.data=a.replace(Dn,"$1"+s):l&&(n.url+=(_n.test(f)?"&":"?")+n.jsonp+"="+s),n.converters["script json"]=function(){return u||v.error(s+" was not called"),u[0]},n.dataTypes[0]="json",e[s]=function(){u=arguments},i.always(function(){e[s]=o,n[s]&&(n.jsonpCallback=r.jsonpCallback,Mn.push(s)),u&&v.isFunction(o)&&o(u[0]),u=o=t}),"script"}),v.ajaxSetup({accepts:{script:"text/javascript, application/javascript, application/ecmascript, application/x-ecmascript"},contents:{script:/javascript|ecmascript/},converters:{"text script":function(e){return v.globalEval(e),e}}}),v.ajaxPrefilter("script",function(e){e.cache===t&&(e.cache=!1),e.crossDomain&&(e.type="GET",e.global=!1)}),v.ajaxTransport("script",function(e){if(e.crossDomain){var n,r=i.head||i.getElementsByTagName("head")[0]||i.documentElement;return{send:function(s,o){n=i.createElement("script"),n.async="async",e.scriptCharset&&(n.charset=e.scriptCharset),n.src=e.url,n.onload=n.onreadystatechange=function(e,i){if(i||!n.readyState||/loaded|complete/.test(n.readyState))n.onload=n.onreadystatechange=null,r&&n.parentNode&&r.removeChild(n),n=t,i||o(200,"success")},r.insertBefore(n,r.firstChild)},abort:function(){n&&n.onload(0,1)}}}});var Hn,Bn=e.ActiveXObject?function(){for(var e in Hn)Hn[e](0,1)}:!1,jn=0;v.ajaxSettings.xhr=e.ActiveXObject?function(){return!this.isLocal&&Fn()||In()}:Fn,function(e){v.extend(v.support,{ajax:!!e,cors:!!e&&"withCredentials"in e})}(v.ajaxSettings.xhr()),v.support.ajax&&v.ajaxTransport(function(n){if(!n.crossDomain||v.support.cors){var r;return{send:function(i,s){var o,u,a=n.xhr();n.username?a.open(n.type,n.url,n.async,n.username,n.password):a.open(n.type,n.url,n.async);if(n.xhrFields)for(u in n.xhrFields)a[u]=n.xhrFields[u];n.mimeType&&a.overrideMimeType&&a.overrideMimeType(n.mimeType),!n.crossDomain&&!i["X-Requested-With"]&&(i["X-Requested-With"]="XMLHttpRequest");try{for(u in i)a.setRequestHeader(u,i[u])}catch(f){}a.send(n.hasContent&&n.data||null),r=function(e,i){var u,f,l,c,h;try{if(r&&(i||a.readyState===4)){r=t,o&&(a.onreadystatechange=v.noop,Bn&&delete Hn[o]);if(i)a.readyState!==4&&a.abort();else{u=a.status,l=a.getAllResponseHeaders(),c={},h=a.responseXML,h&&h.documentElement&&(c.xml=h);try{c.text=a.responseText}catch(p){}try{f=a.statusText}catch(p){f=""}!u&&n.isLocal&&!n.crossDomain?u=c.text?200:404:u===1223&&(u=204)}}}catch(d){i||s(-1,d)}c&&s(u,f,c,l)},n.async?a.readyState===4?setTimeout(r,0):(o=++jn,Bn&&(Hn||(Hn={},v(e).unload(Bn)),Hn[o]=r),a.onreadystatechange=r):r()},abort:function(){r&&r(0,1)}}}});var qn,Rn,Un=/^(?:toggle|show|hide)$/,zn=new RegExp("^(?:([-+])=|)("+m+")([a-z%]*)$","i"),Wn=/queueHooks$/,Xn=[Gn],Vn={"*":[function(e,t){var n,r,i=this.createTween(e,t),s=zn.exec(t),o=i.cur(),u=+o||0,a=1,f=20;if(s){n=+s[2],r=s[3]||(v.cssNumber[e]?"":"px");if(r!=="px"&&u){u=v.css(i.elem,e,!0)||n||1;do a=a||".5",u/=a,v.style(i.elem,e,u+r);while(a!==(a=i.cur()/o)&&a!==1&&--f)}i.unit=r,i.start=u,i.end=s[1]?u+(s[1]+1)*n:n}return i}]};v.Animation=v.extend(Kn,{tweener:function(e,t){v.isFunction(e)?(t=e,e=["*"]):e=e.split(" ");var n,r=0,i=e.length;for(;r<i;r++)n=e[r],Vn[n]=Vn[n]||[],Vn[n].unshift(t)},prefilter:function(e,t){t?Xn.unshift(e):Xn.push(e)}}),v.Tween=Yn,Yn.prototype={constructor:Yn,init:function(e,t,n,r,i,s){this.elem=e,this.prop=n,this.easing=i||"swing",this.options=t,this.start=this.now=this.cur(),this.end=r,this.unit=s||(v.cssNumber[n]?"":"px")},cur:function(){var e=Yn.propHooks[this.prop];return e&&e.get?e.get(this):Yn.propHooks._default.get(this)},run:function(e){var t,n=Yn.propHooks[this.prop];return this.options.duration?this.pos=t=v.easing[this.easing](e,this.options.duration*e,0,1,this.options.duration):this.pos=t=e,this.now=(this.end-this.start)*t+this.start,this.options.step&&this.options.step.call(this.elem,this.now,this),n&&n.set?n.set(this):Yn.propHooks._default.set(this),this}},Yn.prototype.init.prototype=Yn.prototype,Yn.propHooks={_default:{get:function(e){var t;return e.elem[e.prop]==null||!!e.elem.style&&e.elem.style[e.prop]!=null?(t=v.css(e.elem,e.prop,!1,""),!t||t==="auto"?0:t):e.elem[e.prop]},set:function(e){v.fx.step[e.prop]?v.fx.step[e.prop](e):e.elem.style&&(e.elem.style[v.cssProps[e.prop]]!=null||v.cssHooks[e.prop])?v.style(e.elem,e.prop,e.now+e.unit):e.elem[e.prop]=e.now}}},Yn.propHooks.scrollTop=Yn.propHooks.scrollLeft={set:function(e){e.elem.nodeType&&e.elem.parentNode&&(e.elem[e.prop]=e.now)}},v.each(["toggle","show","hide"],function(e,t){var n=v.fn[t];v.fn[t]=function(r,i,s){return r==null||typeof r=="boolean"||!e&&v.isFunction(r)&&v.isFunction(i)?n.apply(this,arguments):this.animate(Zn(t,!0),r,i,s)}}),v.fn.extend({fadeTo:function(e,t,n,r){return this.filter(Gt).css("opacity",0).show().end().animate({opacity:t},e,n,r)},animate:function(e,t,n,r){var i=v.isEmptyObject(e),s=v.speed(t,n,r),o=function(){var t=Kn(this,v.extend({},e),s);i&&t.stop(!0)};return i||s.queue===!1?this.each(o):this.queue(s.queue,o)},stop:function(e,n,r){var i=function(e){var t=e.stop;delete e.stop,t(r)};return typeof e!="string"&&(r=n,n=e,e=t),n&&e!==!1&&this.queue(e||"fx",[]),this.each(function(){var t=!0,n=e!=null&&e+"queueHooks",s=v.timers,o=v._data(this);if(n)o[n]&&o[n].stop&&i(o[n]);else for(n in o)o[n]&&o[n].stop&&Wn.test(n)&&i(o[n]);for(n=s.length;n--;)s[n].elem===this&&(e==null||s[n].queue===e)&&(s[n].anim.stop(r),t=!1,s.splice(n,1));(t||!r)&&v.dequeue(this,e)})}}),v.each({slideDown:Zn("show"),slideUp:Zn("hide"),slideToggle:Zn("toggle"),fadeIn:{opacity:"show"},fadeOut:{opacity:"hide"},fadeToggle:{opacity:"toggle"}},function(e,t){v.fn[e]=function(e,n,r){return this.animate(t,e,n,r)}}),v.speed=function(e,t,n){var r=e&&typeof e=="object"?v.extend({},e):{complete:n||!n&&t||v.isFunction(e)&&e,duration:e,easing:n&&t||t&&!v.isFunction(t)&&t};r.duration=v.fx.off?0:typeof r.duration=="number"?r.duration:r.duration in v.fx.speeds?v.fx.speeds[r.duration]:v.fx.speeds._default;if(r.queue==null||r.queue===!0)r.queue="fx";return r.old=r.complete,r.complete=function(){v.isFunction(r.old)&&r.old.call(this),r.queue&&v.dequeue(this,r.queue)},r},v.easing={linear:function(e){return e},swing:function(e){return.5-Math.cos(e*Math.PI)/2}},v.timers=[],v.fx=Yn.prototype.init,v.fx.tick=function(){var e,n=v.timers,r=0;qn=v.now();for(;r<n.length;r++)e=n[r],!e()&&n[r]===e&&n.splice(r--,1);n.length||v.fx.stop(),qn=t},v.fx.timer=function(e){e()&&v.timers.push(e)&&!Rn&&(Rn=setInterval(v.fx.tick,v.fx.interval))},v.fx.interval=13,v.fx.stop=function(){clearInterval(Rn),Rn=null},v.fx.speeds={slow:600,fast:200,_default:400},v.fx.step={},v.expr&&v.expr.filters&&(v.expr.filters.animated=function(e){return v.grep(v.timers,function(t){return e===t.elem}).length});var er=/^(?:body|html)$/i;v.fn.offset=function(e){if(arguments.length)return e===t?this:this.each(function(t){v.offset.setOffset(this,e,t)});var n,r,i,s,o,u,a,f={top:0,left:0},l=this[0],c=l&&l.ownerDocument;if(!c)return;return(r=c.body)===l?v.offset.bodyOffset(l):(n=c.documentElement,v.contains(n,l)?(typeof l.getBoundingClientRect!="undefined"&&(f=l.getBoundingClientRect()),i=tr(c),s=n.clientTop||r.clientTop||0,o=n.clientLeft||r.clientLeft||0,u=i.pageYOffset||n.scrollTop,a=i.pageXOffset||n.scrollLeft,{top:f.top+u-s,left:f.left+a-o}):f)},v.offset={bodyOffset:function(e){var t=e.offsetTop,n=e.offsetLeft;return v.support.doesNotIncludeMarginInBodyOffset&&(t+=parseFloat(v.css(e,"marginTop"))||0,n+=parseFloat(v.css(e,"marginLeft"))||0),{top:t,left:n}},setOffset:function(e,t,n){var r=v.css(e,"position");r==="static"&&(e.style.position="relative");var i=v(e),s=i.offset(),o=v.css(e,"top"),u=v.css(e,"left"),a=(r==="absolute"||r==="fixed")&&v.inArray("auto",[o,u])>-1,f={},l={},c,h;a?(l=i.position(),c=l.top,h=l.left):(c=parseFloat(o)||0,h=parseFloat(u)||0),v.isFunction(t)&&(t=t.call(e,n,s)),t.top!=null&&(f.top=t.top-s.top+c),t.left!=null&&(f.left=t.left-s.left+h),"using"in t?t.using.call(e,f):i.css(f)}},v.fn.extend({position:function(){if(!this[0])return;var e=this[0],t=this.offsetParent(),n=this.offset(),r=er.test(t[0].nodeName)?{top:0,left:0}:t.offset();return n.top-=parseFloat(v.css(e,"marginTop"))||0,n.left-=parseFloat(v.css(e,"marginLeft"))||0,r.top+=parseFloat(v.css(t[0],"borderTopWidth"))||0,r.left+=parseFloat(v.css(t[0],"borderLeftWidth"))||0,{top:n.top-r.top,left:n.left-r.left}},offsetParent:function(){return this.map(function(){var e=this.offsetParent||i.body;while(e&&!er.test(e.nodeName)&&v.css(e,"position")==="static")e=e.offsetParent;return e||i.body})}}),v.each({scrollLeft:"pageXOffset",scrollTop:"pageYOffset"},function(e,n){var r=/Y/.test(n);v.fn[e]=function(i){return v.access(this,function(e,i,s){var o=tr(e);if(s===t)return o?n in o?o[n]:o.document.documentElement[i]:e[i];o?o.scrollTo(r?v(o).scrollLeft():s,r?s:v(o).scrollTop()):e[i]=s},e,i,arguments.length,null)}}),v.each({Height:"height",Width:"width"},function(e,n){v.each({padding:"inner"+e,content:n,"":"outer"+e},function(r,i){v.fn[i]=function(i,s){var o=arguments.length&&(r||typeof i!="boolean"),u=r||(i===!0||s===!0?"margin":"border");return v.access(this,function(n,r,i){var s;return v.isWindow(n)?n.document.documentElement["client"+e]:n.nodeType===9?(s=n.documentElement,Math.max(n.body["scroll"+e],s["scroll"+e],n.body["offset"+e],s["offset"+e],s["client"+e])):i===t?v.css(n,r,i,u):v.style(n,r,i,u)},n,o?i:t,o,null)}})}),e.jQuery=e.$=v,typeof define=="function"&&define.amd&&define.amd.jQuery&&define("jquery",[],function(){return v})})(window);
//]]>
</script>
<script id="jqueryArea" type="text/javascript">
//<![CDATA[
/*
jQuery.encoding.digests.sha1.js

SHA-1 digest and associated utility functions

Copyright (c) UnaMesa Association 2009

Dual licensed under the MIT and GPL licenses:
  http://www.opensource.org/licenses/mit-license.php
  http://www.gnu.org/licenses/gpl.html
*/

(function($) {

if(!$.encoding)
	$.encoding = {};
	$.extend($.encoding,{
		strToBe32s: function(str) {
			// Convert a string to an array of big-endian 32-bit words
			var be=[];
			var len=Math.floor(str.length/4);
			var i, j;
			for(i=0, j=0; i<len; i++, j+=4) {
				be[i]=((str.charCodeAt(j)&0xff) << 24)|((str.charCodeAt(j+1)&0xff) << 16)|((str.charCodeAt(j+2)&0xff) << 8)|(str.charCodeAt(j+3)&0xff);
			}
			while(j<str.length) {
				be[j>>2] |= (str.charCodeAt(j)&0xff)<<(24-(j*8)%32);
				j++;
			}
			return be;
		},
		be32sToStr: function(be) {
			// Convert an array of big-endian 32-bit words to a string
			var str='';
			for(var i=0;i<be.length*32;i+=8) {
				str += String.fromCharCode((be[i>>5]>>>(24-i%32)) & 0xff);
			}
			return str;
		},
		be32sToHex: function(be) {
			// Convert an array of big-endian 32-bit words to a hex string
			var hex='0123456789ABCDEF';
			var str='';
			for(var i=0;i<be.length*4;i++) {
				str += hex.charAt((be[i>>2]>>((3-i%4)*8+4))&0xF) + hex.charAt((be[i>>2]>>((3-i%4)*8))&0xF);
			}
			return str;
		}
	});
})(jQuery);


(function($) {

if(!$.encoding.digests)
	$.encoding.digests = {};
	$.extend($.encoding.digests,{
		hexSha1Str: function(str) {
			// Return, in hex, the SHA-1 hash of a string
			return $.encoding.be32sToHex($.encoding.digests.sha1Str(str));
		},
		sha1Str: function(str) {
			// Return the SHA-1 hash of a string
			return sha1($.encoding.strToBe32s(str),str.length);
		},
		sha1: function(x,blen) {
			// Calculate the SHA-1 hash of an array of blen bytes of big-endian 32-bit words
			return sha1($.encoding.strToBe32s(str),str.length);
		}
	});

	// Private functions.
	function sha1(x,blen) {
		// Calculate the SHA-1 hash of an array of blen bytes of big-endian 32-bit words
		function add32(a,b) {
			// Add 32-bit integers, wrapping at 32 bits
			// Uses 16-bit operations internally to work around bugs in some JavaScript interpreters.
			var lsw=(a&0xFFFF)+(b&0xFFFF);
			var msw=(a>>16)+(b>>16)+(lsw>>16);
			return (msw<<16)|(lsw&0xFFFF);
		}
		function AA(a,b,c,d,e) {
			// Cryptographic round helper function. Add five 32-bit integers, wrapping at 32 bits, second parameter is rotated left 5 bits before the addition
			// Uses 16-bit operations internally to work around bugs in some JavaScript interpreters.
			b=(b>>>27)|(b<<5);
			var lsw=(a&0xFFFF)+(b&0xFFFF)+(c&0xFFFF)+(d&0xFFFF)+(e&0xFFFF);
			var msw=(a>>16)+(b>>16)+(c>>16)+(d>>16)+(e>>16)+(lsw>>16);
			return (msw<<16)|(lsw&0xFFFF);
		}
		function RR(w,j) {
			// Cryptographic round helper function.
			var n=w[j-3]^w[j-8]^w[j-14]^w[j-16];
			return (n>>>31)|(n<<1);
		}

		var len=blen*8;
		x[len>>5] |= 0x80 << (24-len%32);
		x[((len+64>>9)<<4)+15]=len;
		var w=new Array(80);

		var k1=0x5A827999;
		var k2=0x6ED9EBA1;
		var k3=0x8F1BBCDC;
		var k4=0xCA62C1D6;

		var h0=0x67452301;
		var h1=0xEFCDAB89;
		var h2=0x98BADCFE;
		var h3=0x10325476;
		var h4=0xC3D2E1F0;

		for(var i=0;i<x.length;i+=16) {
			var j=0;
			var t;
			var a=h0;
			var b=h1;
			var c=h2;
			var d=h3;
			var e=h4;
			while(j<16) {
				w[j]=x[i+j];
				t=AA(e,a,d^(b&(c^d)),w[j],k1);
				e=d; d=c; c=(b>>>2)|(b<<30); b=a; a=t; j++;
			}
			while(j<20) {
				w[j]=RR(w,j);
				t=AA(e,a,d^(b&(c^d)),w[j],k1);
				e=d; d=c; c=(b>>>2)|(b<<30); b=a; a=t; j++;
			}
			while(j<40) {
				w[j]=RR(w,j);
				t=AA(e,a,b^c^d,w[j],k2);
				e=d; d=c; c=(b>>>2)|(b<<30); b=a; a=t; j++;
			}
			while(j<60) {
				w[j]=RR(w,j);
				t=AA(e,a,(b&c)|(d&(b|c)),w[j],k3);
				e=d; d=c; c=(b>>>2)|(b<<30); b=a; a=t; j++;
			}
			while(j<80) {
				w[j]=RR(w,j);
				t=AA(e,a,b^c^d,w[j],k4);
				e=d; d=c; c=(b>>>2)|(b<<30); b=a; a=t; j++;
			}
			h0=add32(h0,a);
			h1=add32(h1,b);
			h2=add32(h2,c);
			h3=add32(h3,d);
			h4=add32(h4,e);
		}
		return [h0,h1,h2,h3,h4];
	}
})(jQuery);
/*
jQuery.twStylesheet.js

jQuery plugin to dynamically insert CSS rules into a document

Usage:
  jQuery.twStylesheet applies style definitions
  jQuery.twStylesheet.remove neutralizes style definitions

Copyright (c) UnaMesa Association 2009

Triple licensed under the BSD, MIT and GPL licenses:
  http://www.opensource.org/licenses/bsd-license.php
  http://www.opensource.org/licenses/mit-license.php
  http://www.gnu.org/licenses/gpl.html
*/

(function($) {

var defaultId = "customStyleSheet"; // XXX: rename to dynamicStyleSheet?

// Add or replace a style sheet
// css argument is a string of CSS rule sets
// options.id is an optional name identifying the style sheet
// options.doc is an optional document reference
// N.B.: Uses DOM methods instead of jQuery to ensure cross-browser comaptibility.
$.twStylesheet = function(css, options) {
	options = options || {};
	var id = options.id || defaultId;
	var doc = options.doc || document;
	var el = doc.getElementById(id);
	if(doc.createStyleSheet) { // IE-specific handling
		if(el) {
			el.parentNode.removeChild(el);
		}
		doc.getElementsByTagName("head")[0].insertAdjacentHTML("beforeEnd",
			'&nbsp;<style id="' + id + '" type="text/css">' + css + '</style>'); // fails without &nbsp;
	} else { // modern browsers
		if(el) {
			el.replaceChild(doc.createTextNode(css), el.firstChild);
		} else {
			el = doc.createElement("style");
			el.type = "text/css";
			el.id = id;
			el.appendChild(doc.createTextNode(css));
			doc.getElementsByTagName("head")[0].appendChild(el);
		}
	}
};

// Remove existing style sheet
// options.id is an optional name identifying the style sheet
// options.doc is an optional document reference
$.twStylesheet.remove = function(options) {
	options = options || {};
	var id = options.id || defaultId;
	var doc = options.doc || document;
	var el = doc.getElementById(id);
	if(el) {
		el.parentNode.removeChild(el);
	}
};

})(jQuery);

//]]>
</script>
<script type="text/javascript">
//<![CDATA[
if(useJavaSaver)
	document.write("<applet style='position:absolute;left:-1px' name='TiddlySaver' code='TiddlySaver.class' archive='TiddlySaver.jar' width='1' height='1'></applet>");
//]]>
</script>
<!--POST-SCRIPT-START-->

<!--POST-SCRIPT-END-->
</body>
</html>

