acme-web-design-1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width">
    <meta name="description" content="Affordable and professional web design,professional web design">\
    <meta name="keywords" content="web design,affordable web design,proje">
    <meta name="author" content="Reyhan Yediyildiz">

    <title>Acme Web Design|Welcome</title>
    <link rel="stylesheet" href="./css/style.css">
   <style>

     body{
        font:15px/1.5 Arial,Helvetica,sans-serif;
        padding:0;
        margin:0;
        background-color:#f4f4f4;
    }

    /*Global*/
    container{
        width:80%;
        margin:auto;
        overflow: hidden;
    }
    ul{
        margin:0;
        padding: 0;
    }

    .button_1{
        height:38px; 
        background:#e8491d; 
        border:0;
        padding-left:20px;
        padding-right:20px;
        color:#ffffff;
    }

    .dark{
        padding:15px; 
        background:#35424a; 
        color:#ffffff;
        margin-top:10px;
        margin-bottom:10px;
       
    }


      /*Header**/
      header{
        background-color:#35424a; 
        color:#ffffff; 
        padding-top:30px;
        min-height:auto70px;
        border-bottom:#e8491d 3px solid ;
    }

    header a{
        color:#ffffff; 
        text-decoration:none;
        text-transform:uppercase;
        font-size:16px;
    }

    header li{
        font:left; 
        display:inline;
        padding:0 20px 0 20px;
    }
    header #branding{
        float:left; 
    }

    header nav{
        float:right; 
        margin-top:10px;
    }

    header .highlight,header .current a{
        color:#e8491d; 
        font-weight:bold;
    }

header a:hover{
        color:#cccccc; 
        font-weight:bold;
    }

     /*Showcase*/
     showcase{
        mim-height:400px; 
        color:#ffffff; 
        background:url(`../img/showcase.jpg)no-repeat 0 -400px;
        text-align:center;
        color:#ffffff;
    }

    #showcase h1{
        margin-top:100px; 
        font-size:55px;
        margin-bottom:10px;
    }

    #showcase p{
        font-size:20px; 
        
    }
    /*Newsletter*/
    #newsletter{
        padding:15px; 
        color:#ffffff;
        background:#35424a;
    }

    #newsletter h1{
        float:left;
    }

    #newsletter form{
        float:right;
        margin-top:15px;
    }

    #newsletter input[type="email"]{
        padding:4px;
        height:25px;
        width:250px;
    }

/*Boxes*/
#boxes.box{
        float: left;
        text-align:center;
        width:30%;
        padding: 18px;
    }

    #boxes .box img{
        width:90px;
    }
/*Sidebar*/
aside#sidebar{
        float:right;
        width:30%;
        margin-top:10px;
    }
aside#sidebar .quote input,aside#sidebar .quote textarea{
        width:90%;
        padding:5px;
    }
    /Main-col*/
     article#main-col{
        float:left;
        width:65%;
    }

/*Services*/
ul#services li{
        list-style:none;
        padding:20px;
        border:#cccccc solid 1px;
        background:#e6e6e6;
    }


    footer{
        padding:20px; 
        margin-top:20px; 
        background-color:#e8491d;
        text-align:center;
        color:#ffffff;
    }
/*Media Queries*/

@media(max-width:768px){
    header #branding,
    header nav,
    header nav li
    newsletter h1,newsletter form,#boxes .box,
    articel#main-col,
    aside#sidebar{
        float:none;
        text-align:center;
        width:100%;
    }
    header{
        padding-bottom:20px;
    }
    #showcase h1{
        margin-top:40px;
    }
    #newsletter button,.quote button{
        display:block;
        width:100%;
    }

    #newsletter form input[type="email"],.quote input,.quote textarea{
        margin buttom:5px;
        width:100%;
    }
}
    ul{
        margin:0;
        padding: 0;
    }

    .button_1{
        height:38px; 
        background:#e8491d; 
        border:0;
        padding-left:20px;
        padding-right:20px;
        color:#ffffff;
    }

   </style>
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
    <h1>Acme Web Design</h1>
    <p>Lorem Ipsum is slechts een proeftekst uit het drukkerij- en zetterijwezen. </p>
            </div>
            <nav>
<ul>
    <li class="current"><a href="index.html">Home</a></li>
    <li><a href="about.html">About</a></li>
    <li><a href="services.html">Services</a></li>
</ul>

            </nav>
        </div>
    </header>
<section id="showcase">
     <div class="container">
        <h1>Affordable Professional Web Design</h1>   
        <p>Lorem Ipsum is slechts een proeftekst uit het drukkerij- en zetterijwezen. </p>
     </div>
</section>

<section id="newsletter">
    <div class="container">
        <h1>Subscribe To Our Newsletter</h1> 
        <form>
            <input type="email" placeholder="Enter Email...">
            <button type="submit" class="button_1">
        </form>
        </div>
        </section>


        <section id="boxes">
            <div class="container">
                <div class="box">
                    <img src="./img/logo_html.png">
               <h3>HTML5 Mqrkup</h3>   
               <p>Lorem Ipsum is slechts een proeftekst uit het drukkerij- en zetterijwezen. </p>
            </div>
            <div class="box">
                <img src="./img/logo_css.png">
                <h3>CSS3 Styling</h3>
                <p>Lorem Ipsum is slechts een proeftekst uit het drukkerij- en zetterijwezen. </p>
            </div>
            <div class="box">
                <img src="./img/logo_brush.png">
                <h3>Graphic Design</h3>   
                <p>Lorem Ipsum is slechts een proeftekst uit het drukkerij- en zetterijwezen. </p>
             </div>
             </div>
       </section>
</body>
</html>

