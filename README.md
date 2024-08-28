# Survey-Form-Easy-Life
Survey form for Students that complete her/his course 
<!DOCTYPE html>
<html lang="en">
<head>
 <title>Survey Form</title>
 <link rel="stylesheet" href="C:\git\index.css">
 <meta charset="=UTF-8"/>
</head>  
<body>
 <header>
<div id="title"><h1>Survey Form Easy Life</h1>
 </header>   
    <div class="form-control">
      <label for="name" id="label-name">Name
       </label>
       <input type="text" id="name" placeholder="Enter your Name"/>
    </div>
    <div>
     <div class="form-control">
      <label for="email" id="label-email">Email
      </label>
      <input type="email" id="email" placeholder="Enter your Email">
    </div>
    <div class="form-control">
     <label for="age" id="label-age">Age
     </label>
     <input type="number" id="age" placeholder="Enter your Age" min="16" max="50" class="right input-field" id="number">
     </div>
    <div class="form-control">
     <label for="role" id="label-role">which option best describes you?
     </label>
      <select name="role" id="role">
        <option value="Student">Student</option>
        <option value="intern">Intern</option>
        <option value="teacher">Teacher</option>
        <option value="other">Other</option>
    </div>
</div>
<div class="form-group">
  <p>Select your gender?</p>
  <label>
    <input type="radio" name="gender" value="Male" class="input-radio"/>Male</label><br></br>
    <label>
      <input type="radio" name="gender" value="Female" class="input-radio"/>Female</label><br></br>
    <label>
      <input type="radio" name="gender" value="Other" class="input-radio"/>Other</label>
</div>
    <div class="form-control">
    <label>Would you recommend Easy Life to a friend?</label>
    <labelfor="recommend-1">
     <input type="radio" id="recommend-1" name="recommend">Yes</input>
     <label for="recommend-2">
     <input type="radio" id="recommend-2" name="recommend">No<input> 
     <label for="recommend-3">
      <input type="radio" id="recommend-3" name="recommend">Maybe</input>
     </label>
    </div> 
    <div class="form-group">
        <p>Which Lesson you like or more intersting to you?<span class="clue">(Check all that apply)</span></p>
        <label>
          <input name="prefer" value="vital sign" type="checkbox" class="input-checkbox"/>Vital sign</label><br></br>
        <label>
          <input name="prefer" value="wounds" type="checkbox" class="input-checkbox"/>Wounds</label><br></br>
        <label>
          <input name="prefer" value="insect sting" type="checkbox" class="input-checkbox"/>Insect Sting</label><br></br>
        <label>
          <input name="prefer" value="Stroke" type="checkbox" class="input-checkbox"/>Stroke</label><br></br>
        <label>
          <input name="prefer" value="patient transportation" type="checkbox" class="input-checkbox"/>Patient Transportation
          </label><br></br>
      </div> 
      <div class="form-group">
        <p>Any comments or suggestions?</p>
            <textarea id="comments" class="input-textarea" name="comment" placeholder="Enter your comment here..."></textarea>
    </div>
    <button type="submit" id="submit" value="submit" class="submit-button">Submit</button>
</form>
</div>
