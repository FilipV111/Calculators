# Calculators

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- <link rel="stylesheet" href="css.css"> -->
    <style>
        body{
    background-image: url(cover\ for\ home.jpg);
}


div{
    float: left;
}

.cz{

    color: azure;
    background: url(table\ fopr\ school.jpg);
    background-repeat: round;
    width: 500px;
    height: 500px;
    margin: 5rem;

    border: 0.3rem solid white;

}

.cz1 {

    color: azure;
    background: url(table\ fopr\ school.jpg);
    background-repeat: round;
    width: 500px;
    height: 500px;
    margin: 5rem;

    border: 0.3rem solid white;
    float: left;

}

.cz2 {

    color: azure;
    background: url(table\ fopr\ school.jpg);
    background-repeat: round;
    width: 500px;
    height: 500px;
    margin: 5rem;
    
    border: 0.3rem solid white;
    float: left;
}

.cz3 {

    color: azure;
    background: url(table\ fopr\ school.jpg);
    background-repeat: round;
    width: 500px;
    height: 500px;
    margin: 5rem;

    border: 0.3rem solid white;
    float: left;
}

.cz4 {

    color: azure;
    background: url(table\ fopr\ school.jpg);
    background-repeat: round;
    width: 500px;
    height: 500px;
    margin: 5rem;

    border: 0.3rem solid white;
    float: left;
}

.cz5 {

    color: azure;
    background: url(table\ fopr\ school.jpg);
    background-repeat: round;
    width: 500px;
    height: 500px;
    margin: 5rem;

    border: 0.3rem solid white;
    float: left;
}

#divcalculators{
    background: url(5529077.jpg);
    background-size: cover;
}


#div11 {
    margin: 2rem;
}

.form {
    margin: 2rem;
}

.cz22{
    margin: 2rem;
    
}

.cz44{
    margin: 2rem;
}



#proba{
    float: left;
    margin: 1rem;
}


#cButton{
    background-color: green;
    color: black;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    
}

p{
    color: black;
    font-size: large;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}


#pages{

    width: 15rem;
    height: 5rem;
    
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    background-image: url();



    display: inline-block;
    outline: none;
    cursor: pointer;
    font-size: 14px;
    line-height: 1;
    border-radius: 500px;
    transition-property: background-color,border-color,color,box-shadow,filter;
    transition-duration: .3s;
    border: 1px solid transparent;
    letter-spacing: 2px;
    min-width: 160px;
    text-transform: uppercase;
    white-space: normal;
    font-weight: 700;
    text-align: center;
    padding: 16px 14px 18px;
    color: #fff;
    background-color: #15883e;
    height: 48px;


    background-color: #1db954;
}
    </style>
</head>
<body>
<!-- This is start of calculators -->
<div id="divcalculators">

    <div class="cz">
        <br>
        <br>

            <div id="div11">
        <p>PERCENTAGE CALCULATION</p>

        <label for="">Enter a number:</label><br>
        <input type="text" id="number"><br>

        <label for="">Enter a %:</label><br>
        <input type="text" id="procent"><br>
        <br>
        
        <input type="button" id="cButton" onclick="calculatE(1)" name="unit"
        value="CALCULATE"><br>
        <br>

        <label for="">Result</label><br>
        <input type="text" id="result" name="">
            </div>
            <br>
            <br>
    </div>


<!-- ------------------------------------------------------------------------------- -->

    <div class="cz1">
        <br>
            <div class="form">
        <p>MINI CALCULATOR</p>
        <label for="">Enter a First Number</label><br>
        <input type="text" id="textBox1"><br>
        <label for="">Enter a Second Number</label><br>
        <input type="text" id="textBox2"><br>
        <br>
        <label for="">SELECT A OPERATION</label><br>

        <input type="radio" id="add" value="Addition" name="unit" onclick="calculate(1)">
        <label for="">+</label>

        <input type="radio" id="sub" value="Subtraction" name="unit"
        onclick="calculate(2)">
        <label for="">-</label>

        <input type="radio" id="mul" value="Multiplication" name="unit"
        onclick="calculate(3)">
        <label for="">*</label>

        <input type="radio" id="divi" value="Division" name="unit" onclick="calculate(4)">
        <label for="">/</label>        
        <br>
        <br>
        <br>
        <label for="">Result</label><br>
        <input type="text" id="Result" name="">
            </div>
        <br>
        <br>
        <br>
        <br>
        <br>
        <br>
    </div>



<!-- ---------------------------------------------------------------------------------- -->


    <div class="cz2">

            <div class="cz22">
        
                <p>PERIMITER OF A PARALLELOGRAM</p>
        <label for="">Enter Side a</label><br>
        <input type="text" id="sidea"><br>
        <label for="">Enter Side b</label><br>
        <input type="text" id="sideb"><br>
        <br>


        <input type="button" id="cButton" onclick="calculatEE(1)" name="unit" value="CALCULATE">
        <br>
        <label for="">Result</label><br>
        <input type="text" id="RResult" name="">
        
        
        <br>
                <p>AREA OF A PARALLELOGRAM</p>
        <label for="">Enter Side a</label><br>
        <input type="text" id="sideaa"><br>
        <label for="">Enter h</label><br>
        <input type="text" id="h"><br>

        <br>
        <input type="button" id="cButton" onclick="calculatEEE(1)" name="unit" value="CALCULATE">
        <br>
        <label for="">Result</label><br>
        <input type="text" id="RRResult" name="">

            </div>


    </div>

    <br>
    <br>
    <br>
    <!-- -------------------------------------------------------------------------------- -->

    <div class="cz3">


                    <div id="proba">
        <p>PERIMETER OF A TRAPEZOID</p>
        <label for="">Enter Side a</label><br>
        <input type="text" id="trasidea"><br>
        <label for="">Enter Side b</label><br>
        <input type="text" id="trasideb"><br>
        <label for="">Enter Side c</label><br>
        <input type="text" id="trasidec"><br>
        <label for="">Enter Side d</label><br>
        <input type="text" id="trasided"><br>
        <br>
        
        
    <input type="button" id="cButton" onclick="traperimeter(1)" name="unit" value="CALCULATE">
    <br>
    <label for="">Result</label><br>
    <input type="text" id="perresult" name="">
                    </div>






                    <div id="proba">
        <p>AREA OF TRAPEZOID</p>
        <label for="">Enter Side a</label><br>
        <input type="text" id="trapsidea"><br>
        <label for="">Enter Side b</label><br>
        <input type="text" id="trapsideb"><br>
        <label for="">Enter h</label><br>
        <input type="text" id="trah"><br>
    <br>
        
        
    <input type="button" id="cButton" onclick="traarea(1)" name="unit" value="CALCULATE">
    <br>
    <label for="">Result</label><br>
    <input type="text" id="areresult" name="">
                    </div>

    </div>


    <br>
    <br>
    <br>
    <br>
    <br>
    
<!-- ---------------------------------------------------------------------------------- -->
        
        <div class="cz4">


                    <div class="cz44">
            <p>DELTOID PERIMETER </p>
            <label for="">Enter side a</label><br>
            <input type="text" id="delta"><br>
            <label for="">Enter side b</label><br>
            <input type="text" id="deltb"><br>


        <br>
        <input type="button" id="cButton" onclick="deltoid(1)" name="unit" value="CALCULATE">
        <label for="">Result</label><br><br>
        <input type="text" id="reeesult">
                    </div>













    </div>










    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>






    <div class="cz5">


    </div>


</div> 
<!-- This is end of calculators  -->




<script>
// MATH CALCULATORS ///////////////////////////////////////////////////////
function calculatE(constant) {

    var number = document.getElementById('number').value * 1 ;
    var procent = document.getElementById('procent').value  * 1 ;
    var ffresult;
    switch(constant) {
        case 1 :
            ffresult =  procent / 100 * number ;
            break;
    } 

    document.getElementById("result").value = ffresult;
}


//------------------------------------------------------

function calculate(choice) {
    var n1 = document.getElementById('textBox1').value * 1;
    var n2 = document.getElementById('textBox2').value * 1;
    var fresult;
    switch(choice) {
        case 1 :
            fresult = n1 + n2;
            break;
        case 2 :
            fresult = n1 - n2;
            break;
        case 3 :
            fresult = n1 * n2;
            break;
        case 4 :
            fresult = n1 / n2;
            break;
    }

    document.getElementById("Result").value = fresult;

}

//===============================================================

function calculatEE(cons) {

    var sidea = document.getElementById('sidea').value * 1 ;
    var sideb = document.getElementById('sideb').value  * 1 ;
    var fffresult;
    switch(cons) {
        case 1 :
            fffresult = ( 2 * sidea ) + ( 2 * sideb ) ;
            break;
    } 

    document.getElementById("RResult").value = fffresult;
}


function calculatEEE(conss) {

    var sideaa = document.getElementById('sideaa').value * 1 ;
    var h = document.getElementById('h').value  * 1 ;
    var ffffresult;
    switch(conss) {
        case 1 :
            ffffresult = sideaa * h ;
            break;
    } 

    document.getElementById("RRResult").value = ffffresult;
}

//===========================================================




function traperimeter(per) {

    var trasidea = document.getElementById('trasidea').value * 1 ;
    var trasideb = document.getElementById('trasideb').value  * 1 ;
    var trasidec = document.getElementById('trasidec').value  * 1 ;
    var trasided = document.getElementById('trasided').value  * 1 ;
    var perresult;

    switch(per) {
        case 1 :
            perresult = trasidea + trasideb + trasidec + trasided ;
            break;
    } 

    document.getElementById("perresult").value = perresult;
}


function traarea(area) {

    let trapsidea = document.getElementById('trapsidea').value * 1 ;
    let trapsideb = document.getElementById('trapsideb').value  * 1 ;
    let trah = document.getElementById('trah').value  * 1 ;
    let areresult;

    switch(area) {
        case 1 :
            areresult = ( ( (trapsidea + trapsideb) / 2 ) * trah );
            break;
    } 

    document.getElementById("areresult").value = areresult;
}

//=====================================================================


function deltoid(delta){

    var deltoida = document.getElementById('delta').value * 1;
    var deltoidb = document.getElementById('deltb').value * 1;
    
    var resulttttt;

    switch(delta) {
        case 1 : 
            resulttttt = ( 2 * ( deltoida + deltoidb ) ) ;
            break;
        
    }

    document.getElementById('reeesult').value = resulttttt;
}


</script>

</body>
</html>
