<DOCTYPE html>
<html> 
<head>
    <title>Register an Employee Form</title>
    <h1>Employee Registration Form</h1>
    <form action="thank you.html">
    </form>
    <label for="fullname=">Full Name:</label><br>
    <input type="text" name="fullname" id="full name"placeholder="Enter your full name"auto focus required/>*<br/>
    <label for="email">E-mail:</label><br/>
    <input type="email"name="email"id="email"placeholder="enter a valid e-mail" required />*<br/>
    <label for="dateofbirth">date of birth:</label><br/>
    <input type="date" name="date of birth"id="date of birth" required/>*<br/>
    <label for="age">Age:</label><br/>
    <input type="number" name="age" id="age" size="6"min="18" max="120"step="1" value="21" /><br/>
    <label for="rating">years of experience:</label><br/>
    <input type="range" name="rating"id="rating"min="0"max="100"step="1"value="0"/><br/>
    <label for="phone">phone:</label><br/>
    <input type="text" name="phone" id="phone"pattern="(0-9)(3)-(0-9)(3)-(0-9)(4)"placeholder="xxx-xxx-xxxx"required/>*<br/>
    <input type="submit" value="Register"/>
    <p>Fields marked*are required.</p> 
    http://localhost/layout/registerEmployee.html
    <input type="range" name="rating" id="rating" min="0" max="100"step="1" value="0"/>
    <span id="ratingvalue">0</span>
    <input type="range" name="rating" id="rating" min="0"max="100"step="1" value="0"onchange="displayratinga(this);" />
    <script>
        function displayrating(slider){
        document.getElementbyid("ratingvalue").innerHTML=slider.value;
    }
    http://localhost/layout/registerEmployee.html
    function displayrating(slider){
        document.getelementById("ratingvalue").innerHTMl=slider.value;
    }
    </script>
    <span id="ratingvalue">0</span><br/>
    <output name=output>0</output><br/>
    <input type="range" name="rating" id="rating" min="0"max="100"step="1"oninpu="outputt.value=rating.value"/>
    <style type="text/css">
    :required,:invalid{background-color:pink;}
    :valid {background-color: white;}    
    </style>
