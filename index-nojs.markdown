---
layout: wikipage
permalink: /index-nojs.html
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
  display: block;
  top: 50%;
  padding: .4em;
  margin: .3em;
  line-height: 1em;
  font-size: 1.8em;
  color: white;
  font-family: Arial, Helvetica, sans-serif;
  font-weight: bold;
  text-transform: uppercase;
  text-decoration: none;
  text-align: center;
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
  text-align: left;
}

h2.left {
  text-align: left;
}

</style>

# All Platforms

MuWire is available for the following platforms:

{% include platforms.html %}
