<!doctype html>
<html lang="se">
<head>
    <meta charset="UTF-8">
    <meta name="description" content="hehe">
    <title>test</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
    
    
    <style>
::-webkit-scrollbar{
width: 0px;
height: 0px;
}
::-webkit-scrollbar-track{
border-radius: 0px;
}
.material-icons {
  font-family: 'Material Icons';
  font-weight: normal;
  font-style: normal;
  font-size: 24px;  /* Preferred icon size */
  display: inline-block;
  line-height: 1;
  text-transform: none;
  letter-spacing: normal;
  word-wrap: normal;
  white-space: nowrap;
  direction: ltr;
}
		html {
			overflow-x: hidden;
			margin: 0px;
			text-rendering: optimizeLegibility;
			scroll-behavior: smooth;
            
		}
        body {
            background: repeating-linear-gradient(white, white, white);
        }
		.big {
            height: 50vmax;
			margin: 0px;
			background: url(https://images.unsplash.com/photo-1538138322212-4d551224c97f?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1234&q=80) no-repeat;
            background-size: 120vmax;
            background-position: top center;
            animation: 4s linear 0s infinite alternate big1;
        }

        @keyframes big1 {
            0%{background-position: right 50% bottom 85%;}
            100%{background-position: right 50% bottom -5%;}
            
        }
        #logo1{
	position:fixed;
	top: 12vmin;
	left: 12vw;
	display: flex;
	justify-content: center;
	align-items: center;
	width:36vw;
	height:36vw;
	background: radial-gradient(rgb(255, 0, 0),rgb(255, 0, 0), rgba(0, 0, 0, 0),  rgba(255, 255, 255, 0), rgba(255, 255, 255, 0));
	border-radius:50%;
    mix-blend-mode:color-burn;
	z-index: 6;
    isolation: isolate;
    transition: 4s;
	}
    #logo1:target{
	background: radial-gradient(rgb(0, 0, 0),rgb(0, 0, 0), rgba(0, 0, 0, 0),  rgba(255, 255, 255, 0), rgba(255, 255, 255, 0));
    mix-blend-mode:difference;
	}

    #logo2{
	position:fixed;
	top: 12vmin;
	left: 22vw;
	display: flex;
	justify-content: center;
	align-items: center;
	width:36vw;
	height:36vw;
	background: radial-gradient(rgb(0, 0, 255),rgb(0, 0, 255), rgba(0, 0, 0, 0),  rgba(255, 255, 255, 0), rgba(255, 255, 255, 0));
	border-radius:50%;
    mix-blend-mode:color-burn;
	z-index: 6;
    isolation: isolate;
    transition: 4s;
	}
    #logo2:target{
	background: radial-gradient(rgb(0, 0, 0),rgb(0, 0, 0), rgba(0, 0, 0, 0),  rgba(255, 255, 255, 0), rgba(255, 255, 255, 0));
    mix-blend-mode:difference;
	}

    #logo3{
	position:fixed;
	top: 12vmin;
	left: 42vw;
	display: flex;
	justify-content: center;
	align-items: center;
	width:36vw;
	height:36vw;
	background: radial-gradient(rgb(0, 255, 0),rgb(0, 255, 0), rgba(0, 0, 0, 0),  rgba(255, 255, 255, 0), rgba(255, 255, 255, 0));
	border-radius:50%;
    mix-blend-mode:color-burn;
	z-index: 6;
    isolation: isolate;
    transition: 4s;
	}
    #logo3:target{
	background: radial-gradient(rgb(0, 0, 0),rgb(0, 0, 0), rgba(0, 0, 0, 0),  rgba(255, 255, 255, 0), rgba(255, 255, 255, 0));
    mix-blend-mode:difference;
	}

    #logo4{
	position:fixed;
	top: 12vmin;
	left: 52vw;
	display: flex;
	justify-content: center;
	align-items: center;
	width:36vw;
	height:36vw;
	background: radial-gradient(rgb(255, 0, 234),rgb(255, 0, 234), rgba(0, 0, 0, 0),  rgba(255, 255, 255, 0), rgba(255, 255, 255, 0));
	border-radius:50%;
    mix-blend-mode:color-burn;
	z-index: 6;
    isolation: isolate;
    transition: 4s;
	}
    #logo4:target{
	background: radial-gradient(rgb(145, 140, 15),rgb(145, 140, 15), rgba(0, 0, 0, 0),  rgba(255, 255, 255, 0), rgba(255, 255, 255, 0));
    mix-blend-mode:difference;
	}
    #logo5{
	position:fixed;
	top: 12vmin;
	left: 32vw;
	display: flex;
	justify-content: center;
	align-items: center;
	width:36vw;
	height:36vw;
	background: radial-gradient(rgb(187, 187, 187),rgb(187, 187, 187), rgba(0, 0, 0, 0),  rgba(255, 255, 255, 0), rgba(255, 255, 255, 0));
	border-radius:50%;
    mix-blend-mode:color-burn;
	z-index: 6;
    isolation: isolate;
    transition: 4s;
	}
    #logo5:target{
	background: radial-gradient(rgb(0, 0, 0),rgb(0, 0, 0), rgba(0, 0, 0, 0),  rgba(255, 255, 255, 0), rgba(255, 255, 255, 0));
    mix-blend-mode:difference;
	}

    
    #lo2:target{
	position:fixed;
	top: 12vmin;
	left: 32vw;
	display: flex;
	justify-content: center;
	align-items: center;
	width:36vw;
	height:36vw;
	background: radial-gradient(rgb(0, 0, 0),rgb(0, 0, 0), rgba(0, 0, 0, 0),  rgba(255, 255, 255, 0), rgba(255, 255, 255, 0));
	border-radius:50%;
    mix-blend-mode:luminosity;
	z-index: 6;
    isolation: isolate;
    transition: 4s;
	}
    #logo1:hover, #logo2:hover, #logo3:hover, #logo4:hover{
        background:rgba(255, 0, 0, 0.6);
        transition: 4s;
    }
	h9 {
	  font-size:5em;
      font-weight: 800;
	  font-family:sans-serif;
	  color: rgb(255, 255, 255);
	  mix-blend-mode: lighten;
      text-shadow: 2px 2px 6px rgba(36, 36, 36, 0.4);
	}
    </style>
    </head>
    <body>
<div class="big">
    <div id="logo1"><h9>HEST</h9>
    </div>
    <div id="logo2"><h9>HEST</h9>
    </div>
    <div id="logo3"><h9>HEST</h9>
    </div>
    <div id="logo4"><h9>HEST</h9>
    </div>
    <div id="logo5"><h9>HEST</h9>
    </div>
</div> <a href="#logo1"> <span class="material-icons">
        stay_primary_portrait
    </span></a>
<a href="#logo2"> <span class="material-icons">
        stay_primary_portrait
    </span></a> <a href="#logo3"> <span class="material-icons">
        stay_primary_portrait
    </span></a>
<a href="#logo4"> <span class="material-icons">
        stay_primary_portrait
    </span></a>
    <a href="#logo5"> <span class="material-icons">
        stay_primary_portrait
    </span></a>
</body>
</html>
