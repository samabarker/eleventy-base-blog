---
layout: layouts/home.njk
eleventyNavigation:
  key: Contact
  order: 4
---
<div class="container">
  <div class="row p-5">
    <div class="col-12 text-center">
      <h1>Contact</h1><br>
    </div>
    <div class="col-12 text-center">
      <form name="contact" method="POST" data-netlify="true">
        <label for="fname">Name:</label><br>
        <input type="text" id="name" name="name" required><br><br>
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" required><br><br>
        <label for="message">Message:</label><br>
        <textarea id="message" name="message" rows="4" cols="50" required></textarea><br><br>
        <input type="submit">
      </form>
    </div>
  </div>
</div>
