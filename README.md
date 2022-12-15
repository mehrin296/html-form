!DOCTYPE html
<html lang="en">
<head>
<title>form</title>
</head>

<body>
  <h2>Registration form</h2>
  <form>
  
  <div> <br>
  <label for="fullname">fullname: </label>
  <input type="text"name="fullname" id="fullname">
  </div>
  
  <div>
  <label for="email">Email: </label>
  <input type = "email"name= "email"id= "email">
  </div> <br>
  
  <div>
  <label for = "password">Password: </label>
  <input type ="password" name="password"id="password">
  </div> <br>
  
  <div>
  <label for = "dob">Date of Birth: </label>
  <input type = "date"name="dob"id="dob">
  </div> <br>
  
  <div>
  <label for = "gender">Gender: </label>
  <input type ="radio"name="gender"id="gender"value="male">Male
  <input type = "radio"name="gender"id="gender"value="female">Female
  </div> <br>
  
  <div>
  <label for ="country">Country: </label>
  <select name =  "country">
  <option value ="bangladesh">Bangladesh</option>
  <option value ="india">India</option>
  <option value="usa">USA</option>
  </select>
  </div>
  
  <div>
  <label for = "about me>about me:</label> <br>
  <textarea col5="50"rows="20" </textarea>
  </div>
  
  <div>
  <input type = "submit">
  <input type = "save">
  </div> <br>
  
  <div>
  <label for = "phone">Please enter your phone number here: </label>
  <input type + "tel" id= "phone"name="phone">
  </div> <br>
  
  <div>
  <label for "birthday time">Birthday(date and time): </label>
  <input type="date time-local" id="birthday time" name="birthday time">
  </div> <br>
  
  <div>
  <input type ="radio" name="status"value="Married">Married <br>
  <input type = "radio"name= "status" value="single">single <br>
  </div>
  
  <div>
  <label for ="foods">choose a food : </label>
  <select name="foods"id="foods"multiple>
  <option value ="italian">Italian</option>
  <option value ="chinese">Chinese</option>
  <option value ="thai">Thai</option>
  </select>
  </div> <br>
  
  <input type ="submit" value="Submit">
  </form>
  </body>
  </html>
  
  
  
