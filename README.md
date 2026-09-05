# Student-registration-form-html-
This form allows a student to:  Enter name, email and password. Select date of birth and gender. Select a department. Choose hobbies. Enter address. Submit or reset the form.
<DOCTYPE html>
<head>
<title>Students Registration</title>
</head>
<body>
<style>
body {
    background-color: powderblue;
}
h1 {
    color:blue;
}
h2 {
    color: orange;
}
p {
    color: red;
}
input,select,textarea{
    border: 2px solid gray;
}
</style>

<h1>Students Registration Form</h1>

<p>Please enter your information below.</p>

<h2>Personal Information</h2>

<label>Student Name</label>
<input type="text">
<br><br>

<label>Email</label>
<input type="email">
<br><br>

<label>Password</label>
<input type="password">
<br><br>

<h2>Date Of Birth</h2>
<input type="date">

<h2>Gender</h2>

<input type="radio"name="Gender"value="male">
<label>Male</label>

<input type="radio"name="Gender"value="female">
<label>Female</label>

<h2>Select your department</h2>
<select>
<option>Computer Science</option>
<option>Artificial Intelligence</option>
<option>Software Engineering</option>
<option>Data Science</option>
</select>

<h2>Select your hobbies</h2>

<input type="checkbox">
<label>Reading</label>

<input type="checkbox">
<label>Gaming</label>

<input type="checkbox">
<label>Sports</label>

<h2>Address</h2>

<textarea rows="5" cols="40"></textarea>
<br><br>
<input type="submit"value="Submit">
<input type="reset"value="Reset">
</body>
</html>

