<!DOCTYPE html>
<html>
<head>  
  <title>HTML Forms</title>
</head>
<body>
  
  <h1>HTML Forms</h1>
  
  <form>
    <label for="username">enter username:</label>
    <input type="text" id="username" name="username" placeholder="username" required>
    <br><br>
    <label for="email">enter email:</label>
    <input type="email" id="email" name="email"placeholder="your email" required>
    <br><br>
    <label for="password">password:</label>
    <input type="password" id="password" name="password"placeholder="choose a password" required>
    
    <p>Select your age:</p>
    
    <input type="radio" name="age" value="0-25" id="option-1">
    <label for="option-2">0-25</label>
    <input type="radio" name="age" value="0-25" id="option-2">
    <label for="option-3">26-50</label>
    <input type="radio" name="age" value="0-25" id="option-1">
    <label for="option-3">51+</label>
    
    <br><br>
    
    <label for="question">Security question:</label>
    <select name="question" id="question">
    <option value="q1">What colour are your favorite pair of socks?</option>
    <option value="q2">If you could be a vegetable, what it be?</option>
    <option value="q3">What is your best ever security question?</option></select>
    
    <br><br>
    
    <label for="answer">Security question answer:</label>
    <input type="text" id="answer" name="answer">
    
    <br><br>
    
    <label for="bio">Your bio:</label><br>
    
    <textarea name="bio" id="bio" cols="30" rows="10" placeholder="about you..."></textarea>
    
    <br><br>
    
    <input type="submit" value="submit the form">
    
  </form>
  
  
</body>
</html>
