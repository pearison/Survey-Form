<!DOCTYPE html>
<html>
  <head>
    <h1 id="title">Medical Survey Form</h1>
    <link rel="stylesheet" type="text/css" href="styles.css">
  </head>
  <body>
       <p id="description">Thanks for filling in your opinion to help our fight against Malaria</p>
       <form id="survey-form">
         <fieldset>
           <label id="name-label">Name <input type="text" name="username" id="name" placeholder="Surname first" required/></label>
           <label id="number-label">Age <input type="number" name="age" id="number" placeholder="Enter  your age" min="13" max="99" required/></label>
           <label id="email-label">Email <input type="email" name="email" id="email" placeholder="Enter your email" required/></label>
           <label>What is your blood type <select name="blood-type" id="dropdown">
            <option value="">(select one)</option>
            <option value="1">AA</option>
            <option value="2">AS</option>
            <option value="3">SS</option>
            <option value="4">Other</option> </select>
           </label>
         </fieldset>
         <fieldset> How often do you get sick with Malaria? 
           <label><input type="radio" name="occurrence" value="sickness" class="inline" required/> Often</label>
           <label><input type="radio" name="occurrence" value="sickness" class="inline" required/> Once in a while</label>
           <label><input type="radio" name="occurrence" value="sickness" class="inline" required />Almost never</label></fieldset>
         <fieldset>
           How do you treat yourself and prevent Malaria next time? 
           <label><input type="checkbox" name="treatment" value="measures" class="inline" required />Through self-medication</label>
           <label><input type="checkbox" name="treatment" value="measures" class="inline" required />Through doctor prescription</label>
           <label><input type="checkbox" name="treatment" value="measures" class="inline" required />I do nothing</label>
           <label><input type="checkbox" name="treatment" value="measures" class="inline" required />I use herbal product</label>
           <label><input type="checkbox" name="treatment" value="measures" class="inline" required />I clear my gutter monthly</label>
           <label><input type="checkbox" name="treatment" value="measures" class="inline" required />I spray my house with insecticide weekly</label>
           <hr class="line">
           <label>Your personal view on Malaria:
          <textarea name="bio" rows="3" cols="30" placeholder="Malaria affect me in a..."></textarea>
			  </label>
        <input type="submit" id="submit" value="Submit" />
         </fieldset>
       </form>
  </body>
</html>
