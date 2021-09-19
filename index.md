<!DOCTYPE html>
<html lang="en">



<head>
 <meta charset="utf-8">
 <title>Your page title here :)</title>
 <meta name="description" content="">
 <meta name="author" content="">
 <meta name="viewport" content="width=device-width, initial-scale=1">
 <link rel="preconnect" href="https://fonts.gstatic.com/" />
 <link href="https://fonts.googleapis.com/css?family=Muli:400" rel="stylesheet" />
 <link href="//fonts.googleapis.com/css?family=Raleway:400,300,600" rel="stylesheet" type="text/css">
 <link rel="stylesheet" href="skeleton.css">
 <link rel="icon" type="image/png" href="images/favicon.png">
 <style>@@ -0,0 +1,543 @@
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@200&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Encode+Sans+SC:wght@100&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@400&display=swap');
@font-face {
    font-family: "mono1";
    src: url("IBM.ttf");
}
html {
 overflow-x: hidden;
 margin: 0px;
 text-rendering: optimizeLegibility;
 scroll-behavior: smooth;
}

body {
 margin: 0;
background-image: linear-gradient(to bottom, lightgray, rgba(130, 130, 130, 1), gray, #cfc4ce, #739494, lightgray);
}
#logo1 {
    cursor: pointer;
 position: absolute;
    transform: translate(-50%);
 left: 50%;
 font-family: "mono1", sans-serif;
 text-decoration: underline;
 background: rgb(47, 47, 47);
 color: aliceblue;
 
 padding: 24px;
 align-content: center;
 display: flex;
    margin-top: 78px;
    border-radius: 50%;
 aspect-ratio: 1;
 align-items: center;
 text-align: center;
 mix-blend-mode: normal;
 transition: 1s;}
#logo1:hover { background: rgba(177, 177, 177, 0);
color: black}


h1.load {
  text-align: center;
  text-transform: uppercase;
  font-family: "mono1", monospace;
  color: transparent;
  letter-spacing:-2vw ;
    cursor: all-scroll;
     font-size: 3em;
 font-weight: 800;
}
@media (min-width: 645px) { 
h1.load {
  text-align: center;
  text-transform: uppercase;
  font-family: "mono1", monospace;
  color: transparent;
  letter-spacing:0px ;
    cursor: all-scroll;
     font-size: 3em;
 font-weight: 800;
}
}
h2 {
 padding: 6px 16px;
 background-color: rgba(255, 15, 5, 0);
 font-family: "Josefin Sans", sans-serif;
 font-size: 1.6em;
 margin: 8px 2px 6px 2px;
 font-weight: 400;
 color: #444;
 border-bottom: 1px solid lightslategray;
}

h3 {
 text-align: center;
 font-family: "mono1";
 color: #444;
 font-size: 2em;
 line-height: 1.6;
 letter-spacing: 1.4px;
 margin: 0px;
 font-weight: 100;
 text-shadow: 0px 0px 10px #acacac
}

h4 {
 font-family: "mono1", monospace;
 font-size: 1em;
 line-height: 1.6;
 letter-spacing: 1.4px;
 margin: 0px;
 font-weight: 200;
}
h44 {
    opacity: 0;
    display: block;
    text-align: center;
 font-family: "mono1", monospace;
 font-size: 1em;
 line-height: 1.6;
 letter-spacing: 1.4px;
 margin: 0px;
 font-weight: 200;
    animation: fadein 1s;
    animation-delay: 4s;
    animation-fill-mode: forwards;
}
@keyframes fadein {
    from { opacity: 0; }
    to   { opacity: 1; }
}


h5 {
 font-family: 'Encode Sans SC', sans-serif;
 font-size: 1.2em;
 line-height: 1.8;
 letter-spacing: 1.6px;
 margin: 0px;
 font-weight: 400;
}

h6 {
 display: inline;
 color: #fff;
 font-family: 'Josefin Sans', 'jose', sans-serif;
 font-weight: 300;
 font-size: 2em;
 margin: 0px;
 margin-bottom: 4em;
 letter-spacing: 4vw;
 text-shadow: 0px 0px 22px white;
}

h8 {
    display: block;
 font-family: "mono1", monospace;
 font-size: 1em;
 line-height: 1.6;
 letter-spacing: 1.4px;
 margin: 0px;
 font-weight: 200;
}
hr {
    width: 66%; height: px; margin: 1em auto; border: 1px solid gray;
}



#dev1 {
    width: 3.2em;
 position: fixed;
 top: 1.8vh;
 left:  calc(50vw - 6vh);
 color: rgba(255, 255, 255, 0.77);
 text-shadow: 0px 0px 10px black;
 transition: 0.4s;
          filter:drop-shadow(2px 2px 6px white) invert(80%);


}

#dev1:hover {
 transition: 0.3s;
      filter:drop-shadow(2px 2px 10px black) invert(80%);
 text-shadow: 0px 0px 10px gray;
}
@media screen and (max-width: 600px) 
{
#dev1 {
display: none;
   }
}
#dev2 {
        width: 3.2em;

 position: fixed;
 top: 2.5vh;
 left:  calc(50vw - -0.5vh);
 color: rgba(255, 255, 255, 0.77);

 transition: 0.4s;
          filter:drop-shadow(2px 2px 6px white) invert(80%);
}

#dev2:hover {
 transition: 0.3s;
      filter:drop-shadow(2px 2px 10px black) invert(80%);
}
@media screen and (max-width: 600px) 
{
    #dev2 {
display: none;
   }
}
a {
 cursor: pointer;
 text-decoration: none;
 color: #444;
}

p {
 color: black;
 font-family: "Poppins", sans-serif;
 line-height: 1.2;
}

.close-btn {
 text-align: right;
 position: fixed;
 color: rgb(255, 255, 255);

 font-size: 5em;
 top: -8px;
 right: 8px;
 font-weight: 100;
 font-family: serif;
 z-index: 4;

 text-shadow: 0px 0px 8px black,  0px 0px 12px black;
 transition: 0.2s;
}

.close-btn:hover {
    text-shadow: 0px 0px 10px gray;
}

.modal-window {
 position: fixed;
 background-color: rgba(0, 0, 0, 0.5);
 top: 0;
 right: 0;
 bottom: 0;
 left: 0;
 z-index: 99;
 visibility: hidden;
 opacity: 0;
 pointer-events: none;
 transition: 0.6s;
 margin: 0px;
}

.modal-window:target {
 visibility: visible;
 opacity: 1;
 pointer-events: auto;
}

.modal-window:target>#ee {
 visibility: visible;
 margin: 10vmin 5vw;
 height: 80vh;
 width: 90vw;
 border: 0;
}

@media screen and (max-width: 600px) {
 .modal-window:target>#ee {
  visibility: visible;
  margin: 4vw 4vw;
  height: 80vh;
  width: 92vw;
  border: 0;

 }
}


#ee {
 margin: 40vmin 50vw;
 width: 10vw;
 height: 10vh;
 border: 0;
 background-color: rgba(0, 0, 0, 0.507);
 box-shadow: 4px 10px 18px 1px rgba(0, 0, 0, 0.8), 0px 0px 60px 1px rgba(255, 255, 255, 0.4);
 transition: 0.6s;
}

iframe {
 border: 0;
}

.container {
 margin: 0%;
 display: grid;
 justify-content: center;
 align-items: center;
 height: 40vh;
}

.main1 {
 align-items: center;
 justify-content: center;
 align-content: center;
 width: 100%;
 /* height: ; */
 display: flex;
 flex-flow: row wrap;
 z-index: 2;
    opacity: 0;
        animation: fadein 4s;
    animation-delay: 4s;
    animation-fill-mode: forwards;
}

.ruta1 {
 margin: 10px;
 padding: 10px;
 width: 20em;
 height: auto;
 box-shadow: 2px 2px 12px black;
 background-color: white;
 z-index: 2;
 transition: 0.4s;
}

.ruta1:hover {
 transition: 0.4s;
 transform: scale(1.04);
}

.two {
 transition: 0.4s;
 padding: 80px 0px;
 width: 100%;
 margin: 0px 0px;
 display: flex;
 align-items: center;
 justify-content: center;
 align-content: center;
 flex-wrap: wrap;
 background-image: radial-gradient(closest-side, rgba(255, 255, 255, 0) 0%, rgba(255, 255, 255, 0) 25%, rgba(150, 150, 150, 0) 90%);
 max-width: 1900px;
 z-index: 2;
}

#aa1 {
 background-image: url("https://164.one/tempsnipolker-1024x502.jpg");
 background-size: cover;
 background-position: center;
 width: 22em;
 height: 13.5em;
 box-shadow: 2px 2px 12px black;
}

#aa2 {
 background-image: url("https://164.one/tempsnip2.jpg");
 background-size: cover;
 background-position: center;
 width: 22em;
 height: 13.5em;
 box-shadow: 2px 2px 12px black;
}

#aa3 {
 background-image: url("hello164.webp");
 background-size: cover;
 background-position: center;
 width: 22em;
 height: 13.5em;
 box-shadow: 2px 2px 12px black;
}

#aa4 {
 background-image: url("pb1.jpg");
 background-size: cover;
 background-position: left;
 width: 22em;
 height: 13.5em;
 box-shadow: 2px 2px 12px black;
}

#aa5 {
 background-image: url("https://www.w3schools.com/w3images/streetart2.jpg");
 background-size: cover;
 background-position: center;
 width: 22em;
 height: 13.5em;
 box-shadow: 2px 2px 12px black;
}

#aa6 {
 background-image: url("https://164.one/abisko.jpg");
 background-size: cover;
 background-position: center;
 width: 22em;
 height: 13.5em;
 box-shadow: 2px 2px 12px black;
}

.dot {
 position:absolute;
 left: 50%;
 transform: translate(-50%, -50%);
 height: 0px;
 width: 0px;
 background-color: rgba(220, 220, 220, 0.5);
 border-radius: 50%;
 box-shadow: 0px 0px 140px 65px white;
}

.box1 {
 background-color: none;
 margin: 0px 0px 0px 0px;
 text-align: right;
 padding: 15px;
}

.box1 img {
 margin: 0.9em 0.4em 0.4em 0.4em;
 width: 6em;
 height: 6em;
 border-radius: 50%;
}

.skal1 {
 margin: auto;
 background-color: rgba(240, 255, 255, 0.6);
 max-width: 500px;
 /* height: ; */
 display: flex;
 flex-direction: row;
 flex-wrap: nowrap;
 justify-content: flex-end;
 align-items: center;
 align-content: center;
 padding: 0px 12px;
}

.site-info {
 text-align: center;
 color: #fff;
 margin: 40px;
}

.divider {
    height: 25px;
}


/*-------------------------------------------------*/



.load span{
  text-shadow:
    0 0 2px rgba(204, 208, 212,0.9),
    0 15px 25px rgba(0, 0, 0, 0.3),
    0 -2px 3px rgba(0, 0, 0, 0.1),
    0 -5px 10px rgba(255, 255, 255, 0.5),
    0 5px 10px rgba(0, 0, 0, 0.3),
    0 3px 4px rgba(255, 255, 255, 0.2),
    0 0 20px rgba(255, 255, 255, 0.45);
  
    animation: loading 2.20s ease-in-out 2 alternate;
}

@keyframes loading {
	to {text-shadow:
    0 0 2px rgba(204, 208, 212,0.2),
    0 0 3px rgba(0, 0, 0, 0.02),
    0 0 0 rgba(0, 0, 0, 0),
    0 0 0 rgba(255, 255, 255, 0),
    0 0 0 rgba(0, 0, 0, 0),
    0 0 0 rgba(255, 255, 255, 0),
    0 0 0 rgba(255, 255, 255, 0);}
}

.load span:nth-child(2){
  animation-delay:0.15s;
}
.load span:nth-child(3){
  animation-delay:0.30s;
}
.load span:nth-child(4){
  animation-delay:0.45s;
}
.load span:nth-child(5){
  animation-delay:0.60s;
}
.load span:nth-child(6){
  animation-delay:0.75s;
}
.load span:nth-child(7){
  animation-delay:0.90s;
}
.load span:nth-child(8){
  animation-delay:1.05s;
}
.load span:nth-child(9){
  animation-delay:1.20s;
}

/*----------------------------------------------------------------*/

::-webkit-scrollbar {
 width: 0px;
 height: 0px;
}

 ::-webkit-scrollbar-button {
 width: 0px;
 height: 0px;
}

 ::-webkit-scrollbar-thumb {
 background: #e1e1e1;
 border: 0px none #ffffff;
 border-radius: 5px;
}

 ::-webkit-scrollbar-thumb:hover {
 background: #ffffff;
}

 ::-webkit-scrollbar-thumb:active {
 background: #000000;
}

 ::-webkit-scrollbar-track {
 background: rgba(222, 222, 222, 0.5);
 border: 0px none #ffffff;
 border-radius: 50px;
}

 ::-webkit-scrollbar-track:hover {
 background: #666666;
}

 ::-webkit-scrollbar-track:active {
 background: #333333;
}

 ::-webkit-scrollbar-corner {
 background: transparent;
}


h44 {
    
}</style>
</head>
<body>
    <main>
<div class="divider"></div>
 <div class="skal1">
  <div class="box1">
   <h1>Leon Ljunghorn</h1>

   <h2>css/js-kodare, webbutvecklare</h2>

   <h2>0790372242</h2>
   <h2>
    <a href="#">leon@164.one</a>
   </h2>
  </div>
  <div class="box1"> <img src="https://faroutmagazine.co.uk/static/uploads/2020/02/Iggy-Pop-1977-2.jpg"></div>
 </div>
<a href="#menu1"><h3>164.one</h3></a>
</main>
<div id="menu1"><h4>hh</h4><h4>hh</h4><h4>hh</h4></div>
</body>

</html>
