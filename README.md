# Form-a-Story
Codecademy HTML Practice Project
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css?family=Open+Sans" rel="stylesheet">
    <title>Form a Story</title>
  </head>
  <body>
    <section id="top">
      <img src="https://content.codecademy.com/courses/learn-html-forms/formAStoryLogo.svg" alt="Form A Story Logo">
    </section>

    <section id="main">
      <h1>Complete the Form -<br> Complete the Story!</h1>
      <hr>
      <!--Add your form below:-->
      <form action="story.html" method="GET">
    
     
  <label for="animal-1">Animal 1:</label>
  <br>
<input id="animal-1" type="text" name="animal-1" required> 
 <br>
 <label for="animal-2">Animal 2:</label>
  <br>
<input  id="animal-2" type="text" name="animal-2" required> 
 <br>
<label for="animal-3">Animal 3:</label>
  <br>
<input id="animal-3" type="text" name="animal-2" required> 
 <br>
<label for="adj-1">Adjective (past tense):</label>
  <br>
<input id="adj-1" type="text" name="adj-1" required> 
 <br>
<label for="verb-1">Verb (ends in -ing):</label>
  <br>
<input id="verb-1" type="text" name="verb-1" required> 
 <br>
 <label for="num-1">Number:</label>
  <br>
<input id="num-1" type="text" name="num-1" required> 
 <br>
 <span> Yes or No:</span>
 <br>
<input id="yes" type="radio" name="answer" value="yes" required>
<label for="yes">Yes</label>
 <br>
 <input id="no" type="radio" name="answer" value="no" required>
<label for="no">No</label>
 <br>
 <label for="speed">Relative speed (ends in -er):</label>
 <br>
 <select id="speed" name="speed" required>
<option value="slower">Slower</option>
<option value="faster">Faster</option>
   </select>
   <br>
   <label for="quote">Motivational Quote:</label>
<input id="quote" name="quote" type="text" required list="quote-choices">
   <br>
   <datalist id="quote-choices"></datalist>
   <option value="winner gets ice cream!"></option>
   <option value="winner gets pizza!"></option>
   <option value="winner gets sweets!"></option>
   <br>
   <label for="message">Meaningful Message:</label>
   <br>
   <textarea id="message" name="message" rows="8" cols="40" required></textarea>
   <br>
 <input type="submit" value="Form My Story!">
        </form>
    </section>
  </body>
</html>
