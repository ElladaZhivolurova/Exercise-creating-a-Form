# Exercise-creating-a-Form
<i> I went through the very hard chapter about "Forms" and this is an example of one of the forms. </i>

<html>

     <head>
        <title> Forms </title>
     </head>

    <body>  
       <form action = "http://www.example.com/review.php" method ="get">
   <fieldset>

         <legend>
            User Data:
         </legend>

       <label>
          Name:
           <input type="text" name="name" size="30" maxlength="100">
       </label>

         <br />

         <label>
          Email:
            <input type="email" name="email" size ="30" maxlength="100">
         </label>

         <br />

    </fieldset>

     <br />

    <fieldset>
         <legend>
           Your Opinion:
         </legend>

       <p>
         <label for="hear-about">
        How did you hear about us?
         </label>

       <select name="referrer" id="hear-about">
         <option value="google">Google</option>
         <option value="friends"> Friends </option>
         <option value="advert"> Advert </option>
         <option value="other"> Other </option>
     </select>

       </p>

     <p> 
      Will you visit our site again?
    <br />

    <label> 
      <input type="radio" name="rating" value="yes" />
     Yes
    </label>

    <label> 
      <input type="radio" name="rating" value="no" />
     No
    </label>

    <label> 
      <input type="radio" name="rating" value="maybe" />
     Maybe
    </label>

     </p>

  <p>
     <label for="comments">
        Comments:
     </label>

     <br />

     <textarea rows="4" cols="40" id="comments"> </textarea>

  </p>

  <label>
   <input type="checkbox" name="subscribe" checked="checked" />
    I want to receive the newsletter
  </label>

    <br />

    <input type ="submit" value="Submit review" />

     </fieldset>

    </form>

   </body>

</html>

