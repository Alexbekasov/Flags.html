<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <link rel="stylesheet" href="tabelstyle.css">
</head>
<body>
<h1>Tabelid</h1>
<table id="table1">
    <caption>Lihtne Tabel 2x2</caption>
    <tr>
        <td>1</td>
        <td>2</td>
    </tr>
    <tr>
        <td>3</td>
        <td>4</td>
    </tr>
</table>
/*tabel2*/
<table id="table2">
    <caption>Natuke keeruline</caption>
    <tr>
        <td>1</td>
        <td>2</td>
    </tr>
    <tr>
        <td colspan="2">3</td>
    </tr>
</table>

<table id="table3">
    <caption>Natukene keeruline tabel 2</caption>
    <tr>
        <td rowspan="2">1</td>
        <td>2</td>
    </tr>
    <tr>
        <td>3</td>

    </tr>
</table>

<<table id="table4">
    <caption>Tabel 4</caption>
    <tr>
        <td rowspan="2">1</td>
        <td>2</td>
        <td>3</td>
    </tr>
    <tr>
        <td colspan="2">4</td>
    </tr>
    <tr>
        <td colspan="2">5</td>
        <td>6</td>
    </tr>
</table>
<h1>Tabelid</h1>
<table id="table5">
    <caption>Eesti Lipp</caption>
    <tr>
        <td></td>
    </tr>
    <tr>
        <td></td>
    </tr>
    <tr>
        <td></td>
    </tr>
</table>

<table id="table6">
    <caption>Prantsusmaa</caption>
    <tr>
        <td></td>
        <td></td>
        <td></td>
    </tr>
</table>
<table id="table7">
    <caption>Denmark</caption>
    <tr>
        <td class="red"></td>
        <td class="white"></td>
        <td class="red"></td>
    </tr>
    <tr>
        <td class="white"></td>
        <td class="red"></td>
        <td class="white"></td>
    </tr>
    <tr>
        <td class="red"></td>
        <td class="white"></td>
        <td class="red"></td>
    </tr>
</table>
<table id="table8">
    <caption>Swiss</caption>
    <tr>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td></td>
        <td colspan="3"></td>
    </tr>
    <tr>
        <td></td>
        <td></td>
        <td></td>
    </tr>
</table>


</body>
</html>

-----------------------------------------------------


table#table1{ /*html failis table id=tabel1*/
    width: 50%;
    text-align: center;
    border: 1px solid black;
    border-collapse: collapse; /*uhine aaris*/
}
#table1 td{
    width: 50%;
    text-align: center;
    border: 1px solid black;
}
#table1 tr:nth-child(1) td:nth-child(1){
    /*1.rida 1.lahter*/
    background-color: red;
}
#table1 tr:nth-child(1) td:nth-child(2){
    /*1.rida 1.lahter*/
    background-color: lightblue;
}
#table1 tr:nth-child(2) td:nth-child(1){
    /*1.rida 1.lahter*/
    background-color: lightyellow;
}
#table1 tr:nth-child(2) td:nth-child(2){
    /*1.rida 1.lahter*/
    background-color: lightgreen;
}
/************************* table id=table1**********************/
table#table2{ /*html failis table id=tabel1*/
    width: 30%;
    height: 100px;
    text-align: center;
    border: 1px solid black;
}
#table2 td {
    width: 50%;
    text-align: center;
    border: 1px solid black;
}


table#table1{ /*html failis table id=tabel3*/
    width: 20%;
    height: 100px;
    text-align: center;
    border: 1px solid black;
}
#table3 td{
    width: 50%;
    text-align: center;
    border: 1px solid black;
}




table#table4{
    width: 50%;
    text-align: center;
    border: 1px solid black;
    border-collapse: collapse; /*uhine aaris*/
}
#table4 td{
    width: 50%;
    text-align: center;
    border: 1px solid black;
}
#table4 tr:nth-child(1) td:nth-child(1){
    /*1.rida 1.lahter*/
    background-color: red;
}
#table4 tr:nth-child(1) td:nth-child(2){
    /*1.rida 1.lahter*/
    background-color: lightpink;
}
#table4 tr:nth-child(1) td:nth-child(3) {
    /*1.rida 1.lahter*/
    background-color: lightsalmon;
}
    #table4 tr:nth-child(2) td:nth-child(1) {
        /*1.rida 1.lahter*/
        background-color: blue;
    }

#table4 tr:nth-child(3) td:nth-child(1){
    /*1.rida 1.lahter*/
    background-color: brown;
}
#table4 tr:nth-child(3) td:nth-child(2){
    /*1.rida 1.lahter*/
    background-color: yellow;
}




table#table5{ /*html failis table id=tabel1*/
    width: 50%;
    text-align: center;
    border: 1px solid black;
    border-collapse: collapse; /*uhine aaris*/
}
#table5 td {
    width: 330px;
    height: 210px;
    text-align: center;
    border: 1px solid black;

}
#eesti{
    width: 330px;
    height: 210px;
    border: 1px solid gray;
    border-collapse: collapse;
}

#eesti tr:nth-child(1) td:nth-child(1){
    background-color: #0000ff;
}

#eesti tr:nth-child(1) td:nth-child(1){
    background-color: black;
}

#eesti tr:nth-child(1) td:nth-child(1){
    background-color:white;
}

/*******************************************/
table#table6{ /*html failis table id=tabel1*/
    width: 50%;
    text-align: center;
    border: 1px solid black;
    border-collapse: collapse; /*uhine aaris*/
}
#table6 td {
    width: 330px;
    height: 210px;
    text-align: center;
    border: 1px solid black;

}
#prantsusmaa{
    width: 330px;
    height: 210px;
    border: 1px solid gray;
    border-collapse: collapse;
}

#prantsusmaa tr:nth-child(1) td:nth-child(1){
    background-color: #0000ff;
}

#prantsusmaa tr:nth-child(1) td:nth-child(1){
    background-color: white;
}

#prantsusmaa tr:nth-child(1) td:nth-child(1){
    background-color:red;
}

/***************************************************/

table#table7{ /*html failis table id=tabel1*/
    width: 50%;
    text-align: center;
    border: 1px solid black;
    border-collapse: collapse; /*uhine aaris*/
}
#table7 td {
    width: 330px;
    height: 210px;
    text-align: center;
    border: 1px solid black;

}
#eesti{
    width: 330px;
    height: 210px;
    border: 1px solid gray;
    border-collapse: collapse;
}

#table7 {
    width: 300px;
    height: 180px;
    border-collapse: collapse;
}

#table7 td {
    width: 100px;
    height: 60px;
}

#table7 td.red {
    background-color: red;
}

#table7 td.white {
    background-color: white;
}

#table7 tr:nth-child(2) td:nth-child(2) {
    background-color: red;
}

#table7 tr:nth-child(1) td:nth-child(2),
#table7 tr:nth-child(2) td:nth-child(1),
#table7 tr:nth-child(2) td:nth-child(3),
#table7 tr:nth-child(3) td:nth-child(2) {
    background-color: white;
}
/***********************/


#table8 {
    width: 100px;
    height: 100px;
    border-collapse: collapse;
    background-color: white;
}

#table8 td {
    border: 1px solid transparent;
}


#table8 tr:nth-child(1) td:nth-child(1){
    background-color: white;
}
#table8 tr:nth-child(1) td:nth-child(1){
    background-color: red;
}

#table8 tr:nth-child(3) td:nth-child(1) {
    background-color: white;
}

#table8 tr:nth-child(3) td:nth-child(1) {
    background-color: red;
}


#table8 tr:nth-child(3) td:nth-child(3) {
    background-color: red;
}

#table8 tr:nth-child(1) td:nth-child(3) {
    background-color: red;
}
