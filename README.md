# Responsive-website

<!DOCTYPE html>
<html>
    <head>
        <title>Responsive website</title>
    </head>
    <style>
        body {
    background-color:black;
    color:white;
    margin:0px;
    padding:0px;
    width:400vw;
    
    background:url("https://source.unsplash.com/user/erondu/1600x900") no-repeat center center/cover;
    background-size:700vw 140vh;
    opacity:100000;
}
.navi{
    display:flex;
    flex-direction:row;
    font-size:20px;
    font-weight:bold ;
    margin:15px 1px;
}
li{
    padding:1px;
    list-style:none;
   /* margin:5px 2px;*/
    
}
li:hover{
    color:gray;
}
.box{
   /* margin-left:1px;
    margin-right:0px;*/
  /*  margin:6px;*/
}
section{
    display:flex;
    flex-direction:column;*/
    
   /* justify-content:center;
    align-items:center;*/
    margin:3px 2px;
   /* border:2px solid red;*/
    height:50vh;
    align-items:center;
    justify-content:center ;
    
    
    
    
    
    
}
/*header::before{
background:url("https://source.unsplash.com/user/erondu/1600x900") no-repeat  center center/cover;
    
}*/
h3{
    text-align:center ;
    font-size:3rem;
}
p{
    text-align:center ;
    margin:0px;
    padding:0px;
}
/*section::before{
    content:"this is heading";
}
/*section::before{
    content:"this is first heading";
}*/

.search{
     float:left ;
     margin:-20px 190px;
     text-align:right ;
     padding:20px;
    
    
   /* border:1px solid red;*/
}
input{
    text-align:left  ;
    padding:8px 8px;
    color:black;
    border:2px solid black;
    border-radius:10px;
    font-size:15px;
}
nav div button{
    float: left;
  width: 10%;
  padding: 6px;
  margin:3px 0px;
  background-color:cyan;
  color: white;
  font-size: 17px;
  border: 1px solid grey;
  border-left: none;
  cursor: pointer;
  border-radius:10px;
  position:absolute ;
  top:14px;
  left:787px;
/
    </style>
    <body>
       <header>
           <nav class="navbar">
               <ul class="navi">
                   <li class="box">Home &nbsp &nbsp   </li>
                   <li class="box">About Us &nbsp &nbsp</li>
                   <li class="box">Contect Us &nbsp &nbsp</li>
                   <li class="box">Services</li>
                   <div class="search">
                <button type="submit"><i class="fa fa-search">search</i></button>
                       <input type="search" placeholder="search this website">
                   </div>
               </ul>
           </nav>
       </header>
       <section>
           <h3>Welcome to Mjahid Website</h3>
           <p>TypeScript is a typed superset of JavaScript by definition. As a result, all current JavaScript is TypeScript compliant. Also, you may transform.</p>
           <hr>
       </section>
      <!-- <datalist>
       <summery>name</summery>
           <li>name</li>
           <li>father</li>
           <li>mother</li>
           <li>brother</li>
           <li>sister</li>
       </datalist>-->
       
    
     
       
    </body>
</html>
