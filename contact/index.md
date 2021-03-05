---
layout: layouts/home.njk
permalink: /contact/
eleventyNavigation:
  key: Contact
  order: 4
---

<h1>Contact Me</h1>
<p>Contact me below</p>

<form name="contact" method="POST" data-netlify="true">
  <label for="fname">First Name:</label><br>
  <input type="text" id="fname" name="fname" required><br>
  <label for="lname">Last Name:</label><br>
  <input type="text" id="lname" name="lname"><br>
  <label for="email">Email:</label><br>
  <input type="email" id="email" name="email" required><br>
  <label for="message">Message:</label><br>
  <textarea id="message" name="message" rows="4" cols="50" required></textarea><br>
  <input type="checkbox" id="tandc" name="tandc" value="agree" required>
  <label for="tandc"> I agree to the terms and conditions</label><br>
  <input type="submit">

</form>