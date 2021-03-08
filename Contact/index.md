---
layout: layouts/post.njk
title: Contact
templateClass: tmpl-post
eleventyNavigation:
  key: Contact
  order: 6
---


<form name="contact" method="POST" data-netlify="true">
  <p>
    <label>Your Name: <input type="text " name="name" pattern="[a-zA-Z0-9!?,.]{0,30}" placeholder="Type here" maxlength="40" required/></label>   
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" placeholder="Type here" maxlength="40" required/></label>
  </p>
  <p>
    <div class="form-check">
      <input class="form-check-input" type="radio" name="flexRadioDefault" id="flexRadioDefault1">
      <label class="form-check-label" for="flexRadioDefault1">
        Sumbit a recipe
      </label>
    </div>
    <div class="form-check">
      <input class="form-check-input" type="radio" name="flexRadioDefault" id="flexRadioDefault2" checked>
      <label class="form-check-label" for="flexRadioDefault2">
        Just say hi
      </label>
    </div>
    <div class="form-check">
      <input class="form-check-input" type="radio" name="flexRadioDefault" id="flexRadioDefault3" checked>
      <label class="form-check-label" for="flexRadioDefault3">
        Other
      </label>
    </div>
        

  <!--
    <label>Reason for conacting: <select name="Reason for conacting[]" multiple>
      <option value="Just to say hi">Just to say hi</option>
      <option value="Submit a recipe">Submit a recipe</option>
      <option value="Other">Other</option>
    </select></label>
    -->
  </p>
  <p>
    <label>Message: <textarea name="message" pattern="[a-zA-Z0-9!?,.]{0,40}" placeholder="Please write more info here."></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>