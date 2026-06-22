# qche.in
REBORN FROM RUIN 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>QCHE ARCHIVE</title>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&display=swap');

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Inter, sans-serif;
}

body{
background:#0a0a0a;
color:#fff;
overflow-x:hidden;
}

/* NAV */
nav{
position:fixed;
top:0;
width:100%;
display:flex;
justify-content:space-between;
padding:20px 40px;
z-index:100;
mix-blend-mode:difference;
}

nav h1{
font-size:16px;
letter-spacing:6px;
font-weight:600;
}

nav a{
color:#fff;
text-decoration:none;
margin-left:25px;
font-size:12px;
letter-spacing:3px;
opacity:0.8;
}

/* HERO */
.hero{
height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
background:black;
}

.hero h2{
font-size:clamp(50px,8vw,140px);
letter-spacing:12px;
font-weight:600;
}

.hero p{
max-width:600px;
margin-top:20px;
color:#aaa;
font-size:14px;
line-height:1.8;
}

.btn{
margin-top:30px;
padding:14px 40px;
border:1px solid #fff;
text-decoration:none;
color:#fff;
font-size:12px;
letter-spacing:3px;
transition:0.3s;
}

.btn:hover{
background:#fff;
color:#000;
}

/* COLLECTION */
.section{
padding:120px 5%;
}

.section h3{
font-size:30px;
letter-spacing:4px;
margin-bottom:40px;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:20px;
}

.card{
background:#111;
overflow:hidden;
border:1px solid #1f1f1f;
transition:0.3s;
}

.card:hover{
transform:scale(1.02);
}

.card img{
width:100%;
display:block;
}

.info{
padding:15px;
}

.info h4{
font-size:14px;
letter-spacing:2px;
}

.info p{
font-size:12px;
color:#aaa;
margin-top:5px;
}

/* FOOTER */
footer{
padding:80px 20px;
text-align:center;
border-top:1px solid #1f1f
