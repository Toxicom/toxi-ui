# toxi-ui
<h1>Warning! I am playing on 1440p 27", so when you import your profile, play around with UI scale</h1>
<hr>
<img src="https://i.imgur.com/6fqvuFH.png">
<b>This is my personal edit of ElvUI!</b>
I am not familiar with LUA coding, so if something doesn't work, I doubt I can help you, lol.
<hr>
<h2>To download my ElvUI profile, head to <a href="https://github.com/Toxicom/toxi-ui/releases">Releases</a> and grab the version you like the most!</h2>
<hr>
<h3>SharedMedia AddOn is still not updated for Shadowlands Pre-patch, therefore we have to import fonts manually via ElvUI. Every time you update ElvUI, you have to add fonts again.. If there's an easier way for that, lemme know.</h3>
<hr>
<h2><b>YOU WILL NEED THESE ADDONS!</b></h2>
<h3>I recommend using <a href="https://wowup.io/">wowup.io</a> for managing your addons.</h3>
<ul>
  <li><a href="https://www.tukui.org/download.php?client=win" target="_blank">ElvUI</a></li>
  <li><a href="https://www.curseforge.com/wow/addons/details" target="_blank">Details! Damage Meter</a></li>
  <li><a href="https://www.curseforge.com/wow/addons/plater-nameplates" target="_blank">Plater</a></li>
  <li><a href="https://www.tukui.org/download.php?client=win" target="_blank">ElvUI S&L</a></li>
  <li><a href="https://www.tukui.org/download.php?client=win" target="_blank">ElvUI ProjectAzilroka</a> for the Bezo texture</li>
  <li><a href="https://github.com/Vicious-wow/XIV_Databar" target="_blank">XIV Databar</a></li>
  <li><a href="https://www.curseforge.com/wow/addons/weakauras-2" target="_blank">Weak Auras</a></li>
  <li><a href="https://wago.io/IconSkins" target="_blank">WA for Icon Skinning</a></li>
  </ul>
<hr>
<h2>Installation guide:</h2>
<ol>
  <li>Download necessary files from <a href="https://github.com/Toxicom/toxi-ui/releases">Releases</a></li>
  <li>Add the <s>2</s> <b>1</b> <s>fonts</s> <b>font</b> to <b>\World of Warcraft\_retail_\Interface\AddOns\ElvUI\Media\Fonts</b></li>
  <li><ul>Font installation

<li>If this is a fresh ElvUI install and you're not afraid to break anything:
  <b>add SharedMedia.lua to \World of Warcraft\_retail_\Interface\AddOns\ElvUI\Media\</b></li>
<li>If you're afraid to lose some of your ElvUI profiles etc.:
  <b>open up SharedMedia.lua and manually add the font line, like this:</b></li></li></ul>
  
 ```
  AddMedia('font','BebasNeue-Regular.ttf',			'Bebas Neue')
 ```
 <li>Import the profiles of <b>ElvUI, Details!, Plater</b></li>
 <li>Get the Weak Auras profiles from <a href="https://luxthos.com">Luxthos</a></li>
 </ol>
<hr>
<h3>To enable UnitFrames fading back:</h3>
<ol>
<li>Type /ec</li>
<li>Navigate to UnitFrames -> Individual Units -> Player -> Fader</li>
<li>Check <b>Enable</b></li>
<li>Repeat the same for Unitframes -> Individual Units -> <b>Target</b> -> Fader</li>
</ol>
<h3>To enable ActionBars fading back:</h3>
<ol>
<li>Type /ec</li>
<li>Navigate to Action Bars -> Player Bars</li>
<li>Enable <b>Inherit Global Fade</b> for every bar that you want to fade</li>
</ol>
