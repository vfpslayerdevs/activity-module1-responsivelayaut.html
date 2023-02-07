<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Responsive Layout</title>
<style>

/********** Base styles **********/
* {
  box-sizing: border-box;
}
body{
    background-color: gray;
}
h1 {
  text-align: center;
  margin-bottom: 15px;
  margin-left: 50px;
  margin-right: 50px;
  background-color: gainsboro;
  border: 1px solid black;
  
}

p {
  text-align: center;
  position: relative;
  background-color: rgb(184, 11, 11);
  width: 100%;
  height: 160px;
  margin-right: auto;
  margin-left: auto;
  margin-top: -20px;
  margin-bottom: auto;
  font-family: Helvetica;
  color: white;
}
h3{ position: relative;
    padding: 5px;
    top: 0px;
    left: 0px;
    text-align: right;
    background-color: red;
    margin-top: auto;
    margin-left: 140px;
    border: 1px solid gainsboro;
    width: auto;
    
}

/* Simple Responsive Framework. */
.row {  
  position: absolute;
  background-color: gray;
  width: 100%;
  margin-left: 90px;
  float: left;
}

/********** Large devices only **********/
@media (min-width: 992px){
    .linha1,.linha2,.linha3{
    float: left;
    border: 1px solid black;
    background-color: gray;
    margin: 20px;
    width: 100%;
    box-sizing: border-box;
  }
  .linha1{
    width: 25%;
  }
  .linha2{
    width: 25%;
  }
  .linha3{width: 25%}
  .col-lg-1 {
    width: 8.33%;
  }
  .col-lg-2 {
    width: 16.66%;
  }
  .col-lg-3 {
    margin: 15px;
    width: 33.33%;
  }
  .col-lg-4 {
    width: 33.33%;
  }
  .col-lg-5 {
    width: 41.66%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-7 {
    width: 58.33%;
  }
  .col-lg-8 {
    width: 66.66%;
  }
  .col-lg-9 {
    width: 74.99%;
  }
  .col-lg-10 {
    width: 83.33%;
  }
  .col-lg-11 {
    width: 91.66%;
  }
  .col-lg-12 {
    width: 100%;
  }
}



/********** Medium devices only **********/
@media (min-width: 768px) and (max-width: 990px) {
  .linha1,.linha2,.linha3{
   float: left;
   clear: right;
    border: 1px solid black;
    background-color: gray;
    margin: 10px;
    margin-bottom: 10px;
    width: 100%;
    box-sizing: border-box;
    
  }
.linha1{width: 35%;}
.linha2{width: 35%;
        margin-left: 60px;     
}
.linha3{width: 80%;
        margin-right: -20px;
}
.li3{ position: relative;
    padding: 5px;
    top: 0px;
    left: 0px;
    text-align: right;
    background-color: red;
    margin-top: auto;
    margin-left: 350px;
    border: 1px solid gainsboro;
    width: auto;

}
.menu1{
  margin-left: 90px;
  margin-right: 30px;
}
}
  .col-md-1 {
    width: 8.33%;
  }
  .col-md-2 {
    width: 16.66%;
  }
  .col-md-3 {

    width: 33.33%;
  }
  .col-md-4 {
    
    width: 33.33%;
  }
  .col-md-5 {
    width: 41.66%;
  }
  .col-md-6 {
    
    width: 50%;
  }
  .col-md-7 {
    width: 58.33%;
  }
  .col-md-8 {
    width: 66.66%;
  }
  .col-md-9 {
    width: 74.99%;
  }
  .col-md-10 {
    width: 83.33%;
  }
  .col-md-11 {
  
    width: 91.66%;
  }
  .col-md-12 {
    width: 100%;
  }
@media(max-width: 767px){ .linha1,.linha2,.linha3{
    float: left;
    clear: both;
    border: 1px solid black;
    background-color: gray;
    margin: 20px;
    width: 100%;
    box-sizing: border-box;
  }
  .linha1{
    margin-left: 80px;
    width: 50%;
  }
  .linha2{
    margin-left: 80px;
    width: 50%;
  }
  .linha3{
    margin-left: 80px;
    width: 50%}

}
</style>
</head>
<body>
<h1 class="menu1">Menu</h1>

<div class="row">
  <div class="linha1"><h3> titulo 1</h3><p>Item 1</p></div>
  <div class="linha2"><h3> titulo 2</h3><p>Item 2 Wow this is cool</p></div>
  <div class="linha3"><h3 class="li3"> titulo 3</h3><p>Item 3</p></div>
</div>

</body>
</html>
