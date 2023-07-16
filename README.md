# Offer-letter.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Offer Letter</title>
    <link rel="stylesheet" href="./CSS/style.css">
</head>
<body>

    <div class="main">

    <div id="top">
        <div id="topUpper">
            <div id="header">
                <h2>InternPE</h2>
                <p>Jaipur Rajasthan</p>
            </div>
            <div id="logo">
                <img src="./Images/logo.jpeg" alt="logo">
            </div>
        </div>

        <div id="topBottom">
            <h1><pre>  Offer Letter</pre></h1>
            <h2><pre>   <u>IPI#14954</u></pre></h2>
        </div>
    </div>

    <div id="bottom">
        <div id="salutation">
            <p><b>Dear Banoth Sariyu,</b></p>
        </div>
        
        <div id="para1">
            <p>We are delighted to welcome you for the internship of <b>Web Development</b>
                internship in our company. This internship is being observed by INTERNPE, as a learning opportunity for you.</p>
        </div>

        <div id="para2">
            <p>Your internship starts on <b>03/07/2023</b> and ends on <b>30/07/2023</b> It's <b>4
                Weeks</b> program. It's also an Unpaid program all focus is on learning.</p>
        </div>

        <div id="para3">
            <p>We look forward to a worthwhile and faithful association that will make you equipped for future projects.
                Wishing you the most enjoyable and truly meaningful internship program experience.</p>
        </div>
    </div>
    
    <div id="footer">
        <img src="./Images/images.jpg" alt="image">
        <p><a href="https://internpe.in">https://internpe.in</a></p>
    </div>

    </div>

</body>
</html>
@import url('https://fonts.googleapis.com/css2?family-Poppins:wght@300;400;500;600;700;800;900&display=swap') ;
*{
    font-family: 'Poppins', sans-serif;
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    /* align-items: center;
    justify-content: center; */
}

/* .main{
    text-align: center;
} */

/* .main { */
    /* position: absolute; */
  /* top: 50%; */
  /* left: 50%; */
  /* transform: translate(-50%, -50%); */
/* } */
  
html, body{
    height: 100%;
    width: 100%;
    /* height: 210mm;
    width: 297mm; */
}

#top{
    width: 100%;
    /* width: 297mm; */
    padding: 50px;
}

#topUpper{
    width: 100%;
    height: 90%;

    /* height: 189mm;
    width: 297mm; */
    display: flex;
    justify-content: space-between;
    align-items: center;
}

#header h2{
    font-size: 50px;
    color: #5F7BCD;
}

#header p{
    font-size:20px;
}


#logo img{
    width: 320px;
    height: 320px;
}

#topBottom{
    position: relative;
    width: 100%;
    /* width: 297mm; */
    display: flex;
    justify-content: space-between;
    align-items: end;
}

#topBottom h1{
    font-size: 100px;
    padding-bottom: 2px;
    color: #5F7BCD;
    border-bottom: 2px solid #5F7BCD;
}
    
#topBottom h1::after{
    position: absolute;
    content :"";
    height: 5px;
    width: 5%;
    background-color:#5F7BCD;
}
    
#topBottom h2{
    font-size: 70px;
    padding-bottom: 2px;
    border-bottom: 2px solid #5F7BCD;
}
    
#topBottom h2::after{
    position: absolute;
    content:"";
    height: 5px;
    width: 5%;
    background-color:#5F7BCD;
}

#bottom{
    font-size: 45px;
    text-justify: auto;
    margin-top: 100px;
    padding: 50px;
}
    
#salutation p{
    margin-bottom: 100px;
    padding-bottom: 50px;
}
    
#para1 p{
    margin-bottom: 100px;
    padding-bottom: 50px;
}

#para2 p{
    margin-bottom: 100px;
    padding-bottom: 50px;
}
    
#footer img{
    /* border: lpx solid red; */
    width: 100%;
    /* width: 297mm; */
}

#footer p{
    text-align: center;
    font-size: 20px;
}
