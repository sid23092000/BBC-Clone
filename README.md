# BBC-Clone
A front end interacting web page of BBC Clone
<html>
<head>
    <title>
      Technology - BBC News
    </title>
        <style type="text/css">
    #topbar
            {
                width:1000px;
                margin:0 auto;
                
                height: 40px;
                 
            }
            body
            {
                margin: 0;
                padding: 0;
                font-family: Helvetica,Arial,sans-serif;
            }
    #logo
            {
                padding: 0%;
                margin-top: 0px;
                width: 100px;
                float: left;
                margin-right: 8px;
            }
    .topbar-section
            {
             float: left;
                border-left: 1px #CCCCCC solid;
                height: 130%;
            }
    #signin-image
            {
                
                width: 20px;
                margin: 11px 15px;
                float: left;
            }
    #signin-text  
            {
                font-weight: bold;
                font-size: 90%;
                position: relative;
                top: 14px;
                padding-right: 50px;
            }
            #wigglyline
            {
                float: left;
                height: 35px; 
                vertical-align: top;
                margin-top: -10px;
            }
            
            #bell{
                height: 25px;
               margin-left: 2px;
                margin: 9px 8px 0 8px; 
                margin-top: -5px;
            
            }
            #bell-div
            {
                height: 25px;
                margin: 9px 8px 0 8px;
            float: left;
            }
            .topbar-menu
            {
                font-weight: bold;
                font-size: 90%;
                padding: 15px 15px 0 15px;
                height: 27px;
                
            }
            #more-arrow
            {
                width: 16px;
                margin-left: 20px;
            }
            #search-box
            {
                   background-color: #E4E4E4;
                border: black;
                font-weight: bold;
                font-size: 14px;
                padding: 5px;
                 margin: 5px 0 5px 5px;
                float: left;
                width: 80%;
            }
            
            
            .clear{
                clear: both;
            }
            #menu-bar-container{
                border-top: 1px solid #CCCCCC;
                background-color: #BB1919;
                width: 100%;
                height: 70px;
                margin-top: 1px;
            }
            #menu-bar
            {
                width: 1000px;
                margin: 0 auto;
            }
            h1{
                padding: 0;
                margin: 0;
                color: white;
                font-size: 40px;
                font-weight: normal;
                padding-top: 10px;
                float: left;
                margin-top: 1px; 
            }
            #local-news{
            border: 1px black solid;
                float: right;
                width: 180px;
                padding: 10px 5px 0 5px;
                margin: 5px 5px 0 0;
                margin-top: 15px;
            }
            #local-news a{
                color: white;
                text-decoration: none;
                font-size: 20px;
                position: relative;
                top: -5px;
            }
            #local-news a:hover{
                text-decoration: underline;
                
            }
            #local-news img{
                height: 20px; 
            }
            #menu-bar-2-container
            {
                background-color: #A91717;
                width: 100%;
            }
            #menu-bar-2
            {
                width: 1000px;
                margin: 0 auto;
                height: 30px;
            }
            #menu-bar-2 a{
                color: white;
                text-decoration: none;
                padding: 0 10px;
                border-right: 1px solid #BB4545;
                font-size: 14px;
                position: relative;
                top: 10px;
            }
            #menu-bar-2 a:hover{
                text-decoration: underline;
            }
            .no-border{
                border: none !important;
            }
            #down-arrow{
                height: 10px;
                position: relative;
                top: 10px;
            }
            #page-container{
                width: 1000px;
                margin: 0 auto;
                
            }
            h2{
                font-weight: normal;
                margin-top: 40px;
                font-size: 20px;
                border-bottom: 2px solid #a91717;
                width: 105px;
            }
            h3 a{
                color: black;
                font-size: 30px;
                text-decoration: none;
            }
            h3 a:hover{
                color: #1167a8;
            }
            #article-summary{
                color: #5a5a5a;
                width: 270px;
            }
        .clock
            {
                height: 15px;
                position: relative;
                top: -12px;
            }
            #clock{
                height: 15px;
                position: relative;
                top: 1px;
            }
            .topic-link{
                text-decoration: none;
                color: #a91717;
                position: relative;
                top: -13px;
            }
            article-summary a:hover{
                color: #1167a8;
            }
            #article-container{
                float: left;;
                width: 670px;
                border-right: 1px solid #CCCCCC;
                border-bottom: 1px solid #CCCCCC;
            }
            #main-article-image{
                width: 310px;
                margin-left: 20px;
                margin-left: 310px;
                margin-top: -220px;
            }
            #article-hr{
                color: #a91717;
                width: 50px;
            }
            .article-link{
                color: black;
                text-decoration: none;
            }
                
            #watch-listen{
                margin-left: 700px;
                margin-top: -330px;
            }
            h4{
                font-size: 30px;
            }
            .article-side-image
            {
                float: left;
                 width: 100px;
                margin-top: -25px;
            }
            .watch-listen-link{
                color: black;
                text-decoration: none;
                font-weight: bold;
                font-size: 15px;
                text-align: left;
                position: relative;
                top: -20px;
                padding-left: 10px;
                margin-right: 10px;
                
                
            }
            .date{
                padding-right: 10px;
                position: relative;
                top: -13px;
            }
            #date{
                padding-right: 10px;
                position: relative;
                top: 1px;
            }
    </style>    
</head> 
 <body>
    <div id="topbar">
        <img id="logo" src ="images/logo.png">
        <div id="signin-div" class="topbar-section">
            <img id="signin-image" src="images/download.png">
            <span id="signin-text">Sign in</span></div>
        <div id="bell-div">
    <img id="wigglyline" src="images/line.png">
            <img id="bell" src="images/bell.png"></div>
          
             
            <div class="topbar-section topbar-menu">News</div>
   <div class="topbar-section topbar-menu">Sport</div>
        <div class="topbar-section topbar-menu">Wealth</div>
    
            <div class="topbar-section topbar-menu">iPlayer</div>
            <div class="topbar-section topbar-menu">T.V</div>
            <div class="topbar-section topbar-menu">More
                <img id="more-arrow" src="images/drop.png"></div>
     <div class="topbar-section">
         <input id="search-box" type="text" placeholder="Search"></div></div>
    <div class="clear"></div> 
     <div id="menu-bar-container">
         <div id="menu-bar">
             <h1>NEWS</h1> 
         <div id="local-news">
         <a href="">Find local News</a>
         <img src="images/pointer.jpg">
             </div></div>
     
     <div class="clear"></div>
     <div id="menu-bar-2-container">
         <div id="menu-bar-2"><a href="">Home</a>
    <a href="">U.K</a>
          <a href="">World</a>
          <a href="">Politics</a> 
          <a href="">Business</a>
          <a href="">Tech</a>
          <a href="">Science</a>
          <a href="">Health</a>
          <a href="">Education</a>
          <a href="">Entertainment & Arts</a>
          <a href="">Video & Audio</a>
          <a href="">U.K</a>
          <a href="" class="no-border">More</a>
             <img id="down-arrow"src="images/drop.png">
         </div>
     </div>
     </div>
     <div class="clear"></div>
     <div id="page-container">
     <div id="main-article">
         <h2>Technology</h2>
         <div id="article-container">
         <h3><a href="">Asda bug exposed payment detail</a></h3>
         <div id="article-summary">
             <p> Security vulnerabilities that put customers at risk have affected Asda's website for a couple of years, a security expert has revealed.</p>
             <p><img id="clock" src="images/clock.png"><span id="date"> 14 June 2019</span><a href="">| Technology</a></p>
            <hr id="article-hr" align="left">
             <p><a class="article-link" href="">*Surveillance fire hit in hack attack</a></p><p><a class="article-link" href="">*eBay flaw has existed for months</a></p>
             </div>
            
             <img id="main-article-image" src="images/asda.jpg">
         
         </div>
          
         
         </div>
         <div class="clear"></div>
        <div id="watch-listen">
         <h4>Watch/Listen</h4>
         <img class="article-side-image" src="images/images.jpg">
            <p><a class="watch-listen-link" href="">U.K science chief backs blockchains</a></p>
            <p><img class="clock" src="images/clock.png"> <span class="date">14 June 2019</span><a class="topic-link" href="">| Technology</a></p>
            <br>
              <img class="article-side-image" src="images/images%20(1).jpg">
            <p><a class="watch-listen-link" href="">Technology has brought world closer</a></p>
            <p><img class="clock" src="images/clock.png"> <span class="date">14 June 2019</span><a class="topic-link" href="">| Science</a></p>
            <br>
            <img class="article-side-image" src="images/images%20(2).jpg">
            <p><a class="watch-listen-link" href="">Countries encouraging technology</a></p>
            <p><img class="clock" src="images/clock.png"> <span class="date">14 June 2019</span><a class="topic-link" href="">| Health</a></p>
            <br>
            <img class="article-side-image" src="images/images%20(3).jpg">
            <p><a class="watch-listen-link" href="">World brought the new era           of development</a></p>
            <p><img class="clock" src="images/clock.png"> <span class="date">14 June 2019</span><a class="topic-link" href="">| Development</a></p>
            <br>
         </div>
     </div>
    </body>
</html>
         
