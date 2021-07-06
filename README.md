# Registration-form-using-html-css
<!DOCTYPE html>
<html>

<head>
</head>
<title>
    Registration Form Fill Up
</title>

<body>
    <link rel="stylesheet" href="Mystyle.css">
    <h2>FILL UP THE FORM</h2>
    <p>
        <label for="Firstname">Firstname:</label>
        <input type="text" placeholder="Firstname" id="Firstname">
    </p>
    <p>
        <label for="Lastname">Lastname:</label>
        <input type="text" placeholder="Lastname" id="Lastname">
    </p>
    <label for="Course">Course:</label>
    <select name="Course" id="Course">
        <option value="Data Science">Data Science</option>
        <option value="ML & AI">ML & AI</option>
        <option value="Web Dev">Web Dev</option>
    </select>
    <p>
        <label for="Gender">Gender:</label>
    </p>
    <div>
        <label for="Female">Female</label>
        <input type="radio" name="Female" id="Female" value="Female">
        <label for="Male">Male</label>
        <input type="radio" name="Male" id="Male" value="Male">
        <label for="Other">Other</label>
        <input type="radio" name="Other" id="Other" value="Other">

    </div>
    <p>
        <label for="Phone Number">Phone Number:</label>
        <input type="text" placeholder="Phone Number" id="PhoneNumber">
    </p>
    <label for="Address">Address:</label>
    <input type="test" id="Address">
    <p>
        <label for="Email">Email:</label>
        <input type="text" placeholder="Email" id="Email">
    </p>
    <p>
        <label for="Password">Password:</label>
        <input type="text" placeholder="Password" id="Password">
    </p>
    <button>Submit</button>


</body>

</html>
button{
    padding:1em 2em;
    border:2px blue solid;
    border-radius: 40px;
    color:black;
    font-size:medium;
    background-color:rgb(100, 164, 237)
}
button:hover{
    border-color:steelblue;
    color:midnightblue;
    cursor:pointer;
}
*{
    margin:4px;
    background-color:lightskyblue;
}
body{
    font-size: 25px;
    font-style:initial;
    margin:8px 2px;
}
h2{
    font-size: 30px;
}
div{
    font-size: 15px;;
}
#Firstname{
    margin:12px 1px;
    padding:4px 4px;
}
#Lastname{
    margin:12px 1px;
     padding:4px 4px;
}
#Course{
    margin:12px 1px;
     padding:4px 12px;
}
#Gender{
    margin:12px 1px;
}
#PhoneNumber{
    margin:15px;
     padding:4px 4px;
}
#Email{
    margin:12px;
     padding:4px 4px;
}
#Password{
    margin:12px;
     padding:4px 4px;
}
#Address{
    margin:12px;
    padding:6px 60px;
}
.tag{
    border:2px solid black;
}
