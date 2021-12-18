﻿# AKAN-TRIAL
 
<!DOCTYPE html>
<html lang="en">

<head>
    <link rel="stylesheet" href="../css/demo.css">
    <script src="../js/demodos.js" defer></script>
    <title>akan name calculator</title>


    </head>

    <p>This is a web application that takes a user's birthday and calculates the day of the week 
        they were born and then depending on their gender outputs their Akan Name. 

        Akan names are derived from Ghanian culture. Frequently in Ghana, 
        children are given their first name as a 'day name' which corresponds to the day 
        in the week they were born. Input your details to get your Akan name!</p>

    <style>
        div {
          margin-bottom: 10px;
        }
        label {
          display: inline-block;
          width: 150px;
          text-align: right;
        }
      </style>
    </head>
    <body>
      <form>
        <div>
          <label>Birthday</label>
          <input type="text"  id="BirthDay"/>
        </div>
        <div>
          <label>Birthmonth</label>
          <input type="text" id="BirthMonth"/>
        </div>
        <div>
          <label>Birthyear</label>
          <input type="text"  id="BirthYear"/> 
        <div>
            <label>Birthgender</label>
            <input type="text" id="Birthgender"/> 
          </div>
        </form>
        
     

    <button type="submit" onclick="handleClick()">Submit</button>

    <p id="resultHere">Display answer here</p>

</body>

</html>
