---
layout: wikipage
permalink: /
---
<div class="logoAndForkMe">
<span class="forkme">
<a href="https://github.com/zlatinb/muwire"><img width="149" height="149" src="/forkme.png" class="attachment-full size-full" alt="Fork me on GitHub"></a>
</span>
<span class="logo">
<img src="MuWire.png"/><br/>
<center><p><b><font size="+2">Easy anonymous file sharing  using I2P technology</font></b></p></center>
</span>
</div>
<script language="JavaScript">

const VERSION="0.8.13"
const beta=true

<!--
// This script sets OSName variable as follows:
// "Windows"    for all versions of Windows
// "MacOS"      for all versions of Macintosh OS
// "Linux"      for all versions of Linux
// "UNIX"       for all other UNIX flavors 
// "Unknown OS" indicates failure to detect the OS

var OSName="Unknown OS";
if (navigator.appVersion.indexOf("Win")!=-1) OSName="Windows";
if (navigator.appVersion.indexOf("Mac")!=-1) OSName="MacOS";
if (navigator.appVersion.indexOf("Linux")!=-1) OSName="Linux";
else if (navigator.appVersion.indexOf("X11")!=-1) OSName="UNIX";

window.mobileAndTabletCheck = function() {
  let check = false;
  (function(a){if(/(android|bb\d+|meego).+mobile|avantgo|bada\/|blackberry|blazer|compal|elaine|fennec|hiptop|iemobile|ip(hone|od)|iris|kindle|lge |maemo|midp|mmp|mobile.+firefox|netfront|opera m(ob|in)i|palm( os)?|phone|p(ixi|re)\/|plucker|pocket|psp|series(4|6)0|symbian|treo|up\.(browser|link)|vodafone|wap|windows ce|xda|xiino|android|ipad|playbook|silk/i.test(a)||/1207|6310|6590|3gso|4thp|50[1-6]i|770s|802s|a wa|abac|ac(er|oo|s\-)|ai(ko|rn)|al(av|ca|co)|amoi|an(ex|ny|yw)|aptu|ar(ch|go)|as(te|us)|attw|au(di|\-m|r |s )|avan|be(ck|ll|nq)|bi(lb|rd)|bl(ac|az)|br(e|v)w|bumb|bw\-(n|u)|c55\/|capi|ccwa|cdm\-|cell|chtm|cldc|cmd\-|co(mp|nd)|craw|da(it|ll|ng)|dbte|dc\-s|devi|dica|dmob|do(c|p)o|ds(12|\-d)|el(49|ai)|em(l2|ul)|er(ic|k0)|esl8|ez([4-7]0|os|wa|ze)|fetc|fly(\-|_)|g1 u|g560|gene|gf\-5|g\-mo|go(\.w|od)|gr(ad|un)|haie|hcit|hd\-(m|p|t)|hei\-|hi(pt|ta)|hp( i|ip)|hs\-c|ht(c(\-| |_|a|g|p|s|t)|tp)|hu(aw|tc)|i\-(20|go|ma)|i230|iac( |\-|\/)|ibro|idea|ig01|ikom|im1k|inno|ipaq|iris|ja(t|v)a|jbro|jemu|jigs|kddi|keji|kgt( |\/)|klon|kpt |kwc\-|kyo(c|k)|le(no|xi)|lg( g|\/(k|l|u)|50|54|\-[a-w])|libw|lynx|m1\-w|m3ga|m50\/|ma(te|ui|xo)|mc(01|21|ca)|m\-cr|me(rc|ri)|mi(o8|oa|ts)|mmef|mo(01|02|bi|de|do|t(\-| |o|v)|zz)|mt(50|p1|v )|mwbp|mywa|n10[0-2]|n20[2-3]|n30(0|2)|n50(0|2|5)|n7(0(0|1)|10)|ne((c|m)\-|on|tf|wf|wg|wt)|nok(6|i)|nzph|o2im|op(ti|wv)|oran|owg1|p800|pan(a|d|t)|pdxg|pg(13|\-([1-8]|c))|phil|pire|pl(ay|uc)|pn\-2|po(ck|rt|se)|prox|psio|pt\-g|qa\-a|qc(07|12|21|32|60|\-[2-7]|i\-)|qtek|r380|r600|raks|rim9|ro(ve|zo)|s55\/|sa(ge|ma|mm|ms|ny|va)|sc(01|h\-|oo|p\-)|sdk\/|se(c(\-|0|1)|47|mc|nd|ri)|sgh\-|shar|sie(\-|m)|sk\-0|sl(45|id)|sm(al|ar|b3|it|t5)|so(ft|ny)|sp(01|h\-|v\-|v )|sy(01|mb)|t2(18|50)|t6(00|10|18)|ta(gt|lk)|tcl\-|tdg\-|tel(i|m)|tim\-|t\-mo|to(pl|sh)|ts(70|m\-|m3|m5)|tx\-9|up(\.b|g1|si)|utst|v400|v750|veri|vi(rg|te)|vk(40|5[0-3]|\-v)|vm40|voda|vulc|vx(52|53|60|61|70|80|81|83|85|98)|w3c(\-| )|webc|whit|wi(g |nc|nw)|wmlb|wonu|x700|yas\-|your|zeto|zte\-/i.test(a.substr(0,4))) check = true;})(navigator.userAgent||navigator.vendor||window.opera);
  return check;
};
</script>
<style>
div.logoAndForkMe {
   position:relative;
}
span.forkme {
  float:left;
  position:absolute;
}
span.logo {
}

.screenshot {
   float: left;
   width: 30%;
   margin: 10px;
   border : 1px solid black;
}

.screenshot img {
   opacity: 0.8;
   cursor:pointer;
}

.screenshot img:hover {
   opacity: 1;
}

.screenshots {
   background-color: #d8e1d8;
   border-radius: 6px;
   border: 3px solid black; 
}

.screenshots:after {
   content : "";
   display:table;
   clear : both;
}

.imgContainer {
   position: relative;
   display : none;
   border: 3px solid black;
   border-radius: 6px; 
}

.closebtn {
   position: absolute;
   top: 10px;
   right: 15px;
   color : black;
   font-size: 35px;
   cursor: pointer;
}

a.get-muwire {
   display: inline-block;
  top: 50%;
  padding: .4em;
  margin: .2em;
  line-height: 1em;
  font-size: 1.8em;
  color: white;
  font-family: Arial, Helvetica, sans-serif;
  font-weight: bold;
  text-transform: uppercase;
  text-decoration: none;
  text-align: center;
  //background: green;
  background-image : radial-gradient(#3fb97a 30%, green);
  border-radius: .3em;
  text-shadow: 1px 1px 1px rgba(0,0,0,.2);
  box-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3), 1em 3em 2em 0.5em rgba(255, 255, 255, 0.3) inset, inset -.2em -.5em 1em -0em rgba(0,0,0,.3);
  border : 3px solid black;
}
a.get-muwire:hover {
  color: #333333
}

a.get-beta {
   display: inline-block;
  top: 50%;
  padding: .4em;
  margin: .2em;
  line-height: 1em;
  font-size: 1.8em;
  color: white;
  font-family: Arial, Helvetica, sans-serif;
  font-weight: bold;
  text-transform: uppercase;
  text-decoration: none;
  text-align: center;
  //background: green;
  background-image : radial-gradient(orange 30%, darkorange);
  border-radius: .3em;
  text-shadow: 1px 1px 1px rgba(0,0,0,.2);
  box-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3), 1em 3em 2em 0.5em rgba(255, 255, 255, 0.3) inset, inset -.2em -.5em 1em -0em rgba(0,0,0,.3);
  border : 3px solid black;
}
a.get-beta:hover {
  color: #333333
}

a.platforms {
   display: inline-block;
  top: 50%;
  padding: .4em;
  margin: .2em;
  line-height: 1em;
  font-size: 1.4em;
  color: white;
  font-family: Arial, Helvetica, sans-serif;
  font-weight: bold;
  text-transform: uppercase;
  text-decoration: none;
  text-align: center;
  //background: green;
  background-image : radial-gradient(blue 30%, darkblue);
  border-radius: .3em;
  text-shadow: 1px 1px 1px rgba(0,0,0,.2);
  box-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3), 1em 3em 2em 0.5em rgba(255, 255, 255, 0.3) inset, inset -.2em -.5em 1em -0em rgba(0,0,0,.3);
  border : 3px solid black;
}
a.platforms:hover {
  color: #333333
}

div.unixType {
  border: 3px solid black;
  margin: 20px;
  border-radius: 6px;
  background-color: #d8e1d8;
}

h2.left {
  text-align: left;
}

</style>

<p><big>MuWire is an anonymous file-sharing program.  You can share, search and download files of any type.  For more information, see <a href="https://muwire.com/about.html">About MuWire</a></big></p>

<p><big>MuWire is completely free and open source.  There are no bundled ads or offers of any kind.</big></p>

<h2>Download</h2>
<center>
<noscript>
<style>
a.get-muwire {
	display: block;
}
</style>
<p>You do not have JavaScript enabled so your OS cannot be detected.  Please choose one of the following download options:</p>
{% include platforms.html %}
</noscript>
<script language="JavaScript">
if (window.mobileAndTabletCheck()) {
    document.write("<font size='+2'><b>MuWire does not work on mobile devices or tablets yet.  Please come back later.</b></font><br/>");
} else if (OSName == "Windows") {
    document.write('<a class="get-muwire" href="https://muwire.com/downloads/MuWire-' + VERSION + '.exe">Get MuWire ' + VERSION + ' for Windows</a></br>');
    if (beta)
        document.write('<a class="get-beta" href="https://muwire.com/beta.html">Get MuWire BETA</a></br>')
    document.write("<a class='platforms' href='https://muwire.com/index-nojs.html'>other platforms</a></br>")
} else if (OSName == "MacOS") {
    document.write('<a class="get-muwire" href="https://muwire.com/downloads/MuWire-' + VERSION +'.dmg">Get MuWire ' + VERSION + ' for Intel Macs</a></br>');
    document.write('<a class="get-muwire" href="https://muwire.com/downloads/MuWire-arm64-' + VERSION +'.dmg">Get MuWire ' + VERSION + ' for Apple Macs</a></br>');
    if (beta)
        document.write('<a class="get-beta" href="https://muwire.com/beta.html">Get MuWire BETA</a></br>')
    document.write("<a class='platforms' href='https://muwire.com/index-nojs.html'>other platforms</a></br>")
} else {
    document.write("<div class='unixType'>")
    document.write("<b>Linux</b><br/>");
    document.write('<b>x86-64 (Desktops, laptops)</b>: <a href="https://muwire.com/downloads/MuWire-' + VERSION + '.AppImage">MuWire-' + VERSION + '.AppImage</a></br>');
    document.write('<b>aarch64 (Raspberry Pi 64-bit)</b>: <a href="https://muwire.com/downloads/MuWire-aarch64-' + VERSION + '.AppImage">MuWire-aarch64-' + VERSION + '.AppImage</a></br>');
    document.write('Mark the file executable and run it.  You may need to install <a href="https://github.com/AppImage/AppImageKit/wiki/FUSE">FUSE</a>.</br>');
    document.write('</div>');
    document.write("<div class='unixType'>")
    document.write('<b>Other UNIX systems or non-X86 architectures</b>:<br/> Download <a href="https://muwire.com/downloads/MuWire-' + VERSION + '.zip">MuWire-' + VERSION + '.zip</a></br>');
    document.write('Unzip the file and run the <i>bin/MuWire</i> script.  ');
    document.write('You need to have Java 11 and an I2P router.</br> ');
    document.write('<a href="https://muwire.com/downloads/MuWire-' + VERSION + '.zip.sig">GPG Signature</a>  ');
    document.write('<a href="https://keybase.io/zlatinb">GPG key</a></br>');
    document.write('<a href="https://github.com/zlatinb/muwire/wiki/GPG-Signatures">How to verify signatures</a><br/>')
    document.write('This is a reproducible build.  <a href="https://github.com/zlatinb/muwire/wiki/Reproducible-build">More info</a>')
    document.write("</div>")
    if (beta)
        document.write('<a class="get-beta" href="https://muwire.com/beta.html">Get MuWire BETA</a></br>')
    document.write("<a class='platforms' href='https://muwire.com/index-nojs.html'>other platforms</a></br>")

}
</script>
<br/>
</center>

<style>
.accordion {
  border-radius:6px;
  color: #444;
  padding: 8px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  transition: 0.8s;
}

.featureName {
  font-weight: bold;
  font-size: 15px;
  color: white;
  display: inline-block;
  padding : 0.5em;
  border-radius: 6px;
  width:20em;
  text-align:center;
  margin-left: 1.5em;
  text-shadow: 1px 1px 1px rgba(0,0,0,.2);
  background-image : radial-gradient(#3fb97a 40%, green);
  border : 3px solid black;
}


.active {
  text-decoration-line: underline;
}

.panel {
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.3s ease-out;
  border-radius : 6px;
  color: black;
  background-color: #d8e1d8;
}

.tooltip {
  position: relative;
  display: inline-block;
  color:black;
  font-weight:bold;
  background-color: #d8e1d8;
  border-radius : 6px;
  padding : 0.3em;
  margin-bottom : 0.4em;
  border: 3px solid black;
}

.tooltip .tooltiptext {
  visibility: hidden;
  width: 240px;
  text-align: center;
  border-radius: 6px;
  padding: 10px;

  /* Position the tooltip */
  position: absolute;
  z-index: 1;
  color: white;
  margin-left:20px;
  background-image: radial-gradient(#84a684 50%,#3fb97a);
  border: 3px solid black;

}

.tooltip:hover .tooltiptext {
  visibility: visible;
}

div#fmot {
  float:left;
}
div#powered {
  float: right;
}
div#dedicated {
  text-align:center;
  display:inline-block;
  margin-top:25px;
}

</style>

## Running MuWire
The first time you run MuWire it will ask you to choose a nickname.  That nickname is combined with a cryptographically strong I2P address and forms your unique identity on MuWire.  For more info see <a href="/nicknames.html">MuWire Nicknames</a>.

## Features
<noscript>
<style>
div#features {
	display: none;
}
</style>
Please click on the features menu above to see the different features MuWire offers.
</noscript>
<div id="features">
<div class="accordion">
<p class="featureName">Finding files shared by others</p>
<div class="panel">
You can search by keywords or by file hash.  All keywords have to match for a result to be returned.
If you want to share or find a specific file you can use the hash to make sure it is the right one.  You can also use <a class="panelLink" href="/search-phrases.html">Search Phrases</a>.<br/>
</div>
</div>

<div class="accordion">
<p class="featureName">Sharing your own files</p>
<div class="panel">
You can <a class="panelLink" href="/sharing.html">share your own files</a> with other MuWire
users, with several options:
<ul><li>You can organize the files into
<a class="panelLink" href="/file-feeds.html">automatic feeds</a> like for a blog.</li>
<li>You can <a class="panelLink" href="/sidecar-files.html">add comments</a>
about your shared files.</li>
<li>You can <a href="/file-certificates.html">issue a certificate</a>
for a file you share to prove to others that you have the file.</li>
<li>You can group several files together into a
<a class="panelLink" href="/collections.html">Collection</a>.</li>
</ul>

</div>
</div>

<div class="accordion">
<p class="featureName">Messages And Chat</p>
<div class="panel">
You can <a class="panelLink" href="/chat.html">communicate with other MuWire users</a> anonymously.
</div>
</div>

<div class="accordion">
<p class="featureName">Web of Trust</p>
<div class="panel">
You can choose to <a class="panelLink" href="/trust.html">trust or distrust</a> other MuWire users,
and see who they trust and distrust in turn.
</div>
</div>
</div>

<script>
var acc = document.getElementsByClassName("accordion");
var i;

for (i = 0; i < acc.length; i++) {
  acc[i].addEventListener("mouseenter", function() {
    var button = this.getElementsByTagName("p")[0]
    button.classList.toggle("active");
    var panel = this.getElementsByTagName("div")[0]
    panel.style.maxHeight = panel.scrollHeight + "px";
    panel.style.border = "3px solid black"
    panel.style.padding = "0.2em 18px 0.2em"
  });
  acc[i].addEventListener("mouseleave", function() {
    var button = this.getElementsByTagName("p")[0]
    button.classList.toggle("active");
    var panel = this.getElementsByTagName("div")[0]
    panel.style.maxHeight = null;
    panel.style.border = null
    panel.style.padding = null
  })
}

function expandImg(imgs) {
    var expandedImg = document.getElementById("expandedImg")
    expandedImg.src = imgs.src
    expandedImg.parentElement.style.display = "block"
}

</script>

