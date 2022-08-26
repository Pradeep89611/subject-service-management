# subject-service-management
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style> 
    .table-container{
          padding:0 10px;
          margin: 40px auto 0px;
    }
    .heading{
        color:blue;
        margin-top:40px;

    }
    .table thead{
        background-color: red;
        font-size:25px;
    
    }
    .table thead tr th{
        padding:20px;
        vertical-align:top;
        border:1px solid;
        opacity:1;
        letter-spacing:0.35px;

    }
    .table  tbody tr td{
padding:8px;
background-color: white;
text-align: center;
border:1px solid black;
    }
    .table  tbody tr td .btn{
        display: inline-block;
        background-color: aqua;
        width:130px;
    }
    </style>
</head>
<body>
    <h1 class="heading"> HELLO  my name is j.pradeep! i will explaning the case study to you, if you have any doubt feel free to ask</h1>

    <div class="table-container">
<table class="table"> 
    <thead> 
        <tr>
            <th> serial number</th>
            <th>subject code</th>
            <th>subject id</th>
            <th>subject name</th>
            <th>subject professor</th>
            <th>professor contact</th>
            <th>view staff details</th>

            
        </tr>
    </thead>
    <tbody>
    <tr>
        <td>1</td>
        <td> physics</td>
        <td> 101</td>
        <td> 2002021</td>
        <td> y.shamsi</td> 
        <td>9999999999</td>
        <td data-label="#"> <a href="#" class="btn"> view details</a></td>
    </tr>
    <td>2</td>
    <td> social</td>
    <td> 102</td>
    <td> 2002022</td>
    <td> k.karun kumar</td> 
    <td>9999999999</td>
    <td data-label="#"> <a href="#" class="btn"> view details</a></td>
</tr>
<td>3</td>
<td> maths</td>
<td> 103</td>
<td> 2002023</td>
<td> s.mukesh</td>
<td>9999999997</td>
<td data-label="#"> <a href="#" class="btn"> view details</a></td>
</tr>
<td>4</td>
<td> environment science</td>
<td> 103</td>
<td> 2002024</td>
<td> r.sasthri</td>
<td>9999999969</td> 
<td data-label="#"> <a href="#" class="btn"> view details</a></td>
</tr>
<td>5</td>
<td> chemistry</td>
<td> 105</td>
<td> 2002025</td>
<td>  t.anil kumar</td> 
<td>9999999599</td>
<td data-label="#"> <a href="#" class="btn"> view details</a></td>
</tr>
</tbody>
</table>
    </div>
</body>
</html>
