# Project-Task-3
<!DOCTYPE html>
<html>
<head></head>
<body>
<hr>
<form action="story.html" method="GET">
<label for="name"> Animal:</label>
<input id="name" type="text" name="Animal-1" required /><br><br>
<label for="name"> Another Animal:</label>
<input id="name" type="text" name="Animal-2" required /><br><br>
<label for="name"> One More Animal:</label>
<input id="name" type="text" name="Animal-3" required /><br><br>
<label for="name"> Adjective (past tense):</label>
<input id="name" type="text" name="adj-1" required /><br><br>
<label for="name"> Verb (ends in -ing):</label>
<input id="name" type="text" name="verb-1" required /><br><br>
<label for="num-1"> Number: </label>
<input type="Number:" id="Number" name="Number" required /><br><br>
<span>
<input type="radio" id="yes" name="answer" value="yes" required />
<label for="yes">Yes</label>
<input type="radio" id="no" name="answer"  value="no" required />
<label for="no">No</label><br><br>
</span>
<label for="speed">Relative speed (ends in -er):</label><br><br>
<select id="country" id="speed" name="Relative speed (ends in -er)" required >
<option value="select speed">select speed</option>
<option value="slower"> slower</option>
<option value="runner">runner</option>
<option value="faster">faster</option>
</select><br><br>
<label for="quote">Motivational Quote:</label>
<input id="quote" name="quote" type="text" list="quote-choices" required />
<datalist id="quote-choices"> 
<option value="workout motivation quotes"></option>
<option value="heart touching"></option>
</datalist><br><br>
<label for="message">Meaningfull message:</label><br><br>
<textarea id="message" name="message" rows="8" col="40" required /></textarea><br>
<input type="submit"  value="Form My Story!">
</form>
</body>
</html>
