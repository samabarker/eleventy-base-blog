---
layout: layouts/home.njk
eleventyNavigation:
  key: Contact
  order: 4
---
<div class="container">
  <div class="row">
    <div class="col-12 text-center p-5">
      <h1>Contact</h1>
    </div>
    <div class="col-12 text-center">
      <form name="contact" method="POST" data-netlify="true">
        <label for="fname">First Name:</label><br>
        <input type="text" id="fname" name="fname" required><br><br>
        <label for="lname">Last Name:</label><br>
        <input type="text" id="lname" name="lname"><br><br>
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" required><br><br>
        <label for="message">Message:</label><br>
        <textarea id="message" name="message" rows="4" cols="50" required></textarea><br><br>
        <input type="checkbox" id="tandc" name="tandc" value="agree" required>
        <label for="tandc"> I agree to the terms and conditions</label><br><br>
        <input type="submit"><br><br>
      </form>
    </div>
  </div>
</div>
