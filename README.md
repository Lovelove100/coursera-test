<!DOCTYPE html>
<html>
<head>
    <title>Module 2 Assignment</title>
    <link rel="stylesheet" type="text/css" href="cssreahersal.css">
</head>
<body>

    <h1>Our Menu</h1>



         <div class="row">

         <div  class="col-lg-4 col-md-6 col-xs-12">
        <section>
        
                <div id="dish-title-1">Chicken</div>
                <p> Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
                tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
                quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
                consequat.</p>
            
            </section>
        </div>
        
        <div class="col-lg-4 col-md-6 col-xs-12">
        <section>
            
                <div id="dish-title-2"> Beef </div>
                <p> Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
                tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
                quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
                consequat.</p>
            
        </section>
        </div>


        <div  class="col-lg-4 col-md-12 col-xs-12">
        <section>
            
                <div id="dish-title-3"> Sushi </div>
                <p> Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
                tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
                quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
                consequat.</p>
            
        </section>
        </div>  
    </div>
    
   </body>
</html>


/*=================================================================*/

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  /*content: border-box;*/
}
/*
body{
  font-family: 'balsamiq Sans' all;

}*/

h1{
  text-align: center;
  font-size: 1,75em;
  margin: 20px;
}

p  {
  padding: 5px;
  clear: both;
  color: blue;
  font-size: 1em;
 /* box-sizing: content-box;*/
}

/*dish-tittle-1 Chicken*/


section {
position: relative;
border: 2px solid black;
margin: 10px;
background-color: #9999;
}

/* simple Responsive Framework */

.row{
  width: 100%;
/*  padding: 0 15px;
  box-sizing: 100%*/
}




/* Large Devices Only*/
@media (min-width: 992px) {
.col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, 
.col-lg-6,.col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, 
.col-lg-11, .col-lg-12 
  {
    float: left;
  }
  .col-lg-4{
    width: 33.33%;
  }
  .col-lg-6{
    width: 50%;
  }
  .col-lg-12{
    width: 100%;
  }

}

/* Medium devices only*/

@media (min-width: 768px) and (max-width: 991px)
{
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5,
  .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10,
  .col-md-11, .col-md-12
  {
    float: left;
  }
  .col-md-6{
    width: 50%;
  }
  .col-md-6{
    width: 50%
  }
  .col-md-12{
    width: 100%
  }
}

/* small devices only */


@media (min-width:767 ) 
{
  .col-xs-1, .col-xs-2, .col-xs-3, .col-xs-4, .col-xs-5,
  .col-xs-6, .col-xs-7, .col-xs-8, .col-xs-9, .col-xs-10,
  .col-xs-11, .col-xs-12
  {
    float: left;
  }
  .col-xs-12{
    width: 100%;
  }
 } 

#dish-title-1{
  float: right;
  background-color: blue;
  border: 2px solid black;
  padding: 2px 20px;
  position: relative;
  top: -2px;
  right: -2px;
  font-size: 1.25em;
  }


#dish-title-2{
  float: right;
  background-color: red;
  border: 2px solid black;
  padding: 2px 20px;
  position: relative;
  top: -2px;
  right: -2px;
  font-size: 1.25em;
  }


#dish-title-3{
  float: right;
  background-color: green;
  border: 2px solid black;
  padding: 2px 20px;
  position: relative;
  top: -2px;
  right: -2px;
  font-size: 1.25em;
  }





/* specific Style */

/*.dish-title {
  float: right;
  position: relative;
  top: -1px;
  left: 1px;
  padding: 5px 50px;
  border: 1px #000000 solid;
  font-size: 1,25em;

}
*/
