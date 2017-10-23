body {
       
background: linear-gradient(#ffffff 50%, rgba(255,255,255,0) 0) 0 0,
radial-gradient(circle closest-side, #FFFFFF 53%, rgba(255,255,255,0) 0) 0 0,
radial-gradient(circle closest-side, #FFFFFF 50%, rgba(255,255,255,0) 0) 55px 0 #48B;
background-size:110px 200px;
background-repeat:repeat-x;

margin-left: 2cm;
margin-right: 2cm;
margin-bottom: 2.5cm;
padding: none;
}
ul {
    text-align:center;
}

/*Headers and paragraph titles-->*/
#header {
    font-style: italic;
    line-height:140px;
    font-size: 56px;
    letter-spacing: 1px;
    color: rgba(255, 170, 0, 0.904);
    text-align: center;  
}

h1 { /*don't have anything here yet*/
    color:rgb(184, 121, 13);
    text-align: center;
    text-decoration:underline;
    font-style: italic;
    letter-spacing: 1px;
    font-family: "Arial", Helvetica, sans-serif;
}
h2 {
    color:rgb(255, 255, 255);
    text-align: center;
    font-size:30px;
    text-shadow: 1px blue;
    font-style: Arial, Helvetica, "sans-serif";
}
h3 {
    color:#000000;
    font-style: "Helvetica", sans-serif;
    text-align: center;
    font-size:17px;
}
h4 { 
    text-align: center;
}

p {
    text-align: Justify;
    text-indent:50px;
    line-height: 1.5;
    color:#000000;
    font-style: "Times New Roman"; 
    border: 25px solid rgba(255, 255, 255, 0);
    border-radius: 20px;
    background-color: rgba(255, 170, 0, 0.904); 
    box-shadow: 10px 10px 5px rgb(18, 9, 49);
}

/*For the Buttons Linking to UH pages*/

.button{ 
    margin: 15px;
    position:relative;
    left:285px; 
    display:inline-block;
    border-radius:10px;
    background-color: rgb(94, 215, 252);
    border:none;
    color:rgb(255, 255, 255);
    text-align: center;
    font-size: 20px;
    padding:27px;
    width:200px;
    transition: all 0.5s;
    cursor: pointer;
    
}
.button span {
    cursor: pointer;
    display:inline-block;
    position: relative;
    transition: 0.5s;
}
.button span:after {
    content: '\00bb';
    position: absolute;
    opacity: 90%;
    top: 0;
    right:-20px;
    transition: 0.5s;
}

.button:hover span {
    padding-right: 25px;
}
.button:hover span:after {
    opacity:8;
    right:0;
}
a:link, a:visited {
    background-color:none;
    text-decoration:none;
}

/*second button*/


.button2{ 
    margin:15px;
    position: absolute;
    right: 383px;
    display:inline-block;
    border-radius:10px;
    background-color:rgb(250, 191, 90);
    border:none;
    color:rgb(255, 255, 255);
    text-align: center;
    font-size: 20px;
    padding:27px;
    width:200px;
    transition: all 0.5s;
    cursor: pointer;    
}
.button2 span {
    cursor: pointer;
    display:inline-block;
    position: relative;
    transition: 0.5s;
}
.button2 span:after {
    content: '\00bb';
    position: absolute;
    opacity: 90%;
    top: 0;
    right:-20px;
    transition: 0.5s;
}
.button2:hover span {
    padding-right: 25px;
}
.button2:hover span:after {
    opacity:8;
    right:0;
}

/*For the table*/ 
#caption {
    font-size:29px;
    font-style: courier, "comic sans MS header", trebuchet, impact;
    color:rgb(154, 255, 238);
    letter-spacing:1px;
    line-height:2.1;
}
table, th,td {
    border: 1px solid black;

}
table tr:nth-child(even) {
    background-color:Orange;
}
table tr:nth-child(odd){
    background-color:White;
}
th {
    background-color:Teal;
    color:white;
}
th, td {
    padding: 10px; 
    text-align: center;
}
table {
    border-spacing: 4px;
    box-shadow: 10px 10px 5px black;
}
