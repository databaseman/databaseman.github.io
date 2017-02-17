---
layout: page
title: Contact
permalink: /contact/
#feature-img: "img/color.png"
---
<form action="https://getsimpleform.com/messages?form_api_token=814cd8baca7412d1b50b6f689e9ce8b7" method="post">
  <!-- the redirect_to is optional, the form will redirect to the referrer on submission --> 
    <input type='hidden' name='redirect_to' value='https://databaseman.github.io/thank-you/' />
    <!-- all your input fields here.... -->
    <div class="form-group">
      <label for="senderName">Your Name</label>
      <input id="senderName" class="form-control" name="name" type="text" placeholder="Your full Name" />
    </div>
 
    <div class="form-group">
      <label for="senderEmail">Email address</label>
      <input id="senderEmail" class="form-control" name="email" type="email" placeholder="Your Email" />
    </div>
 
    <div class="form-group">
      <label for="senderEmail">Type Your Message</label>
      <textarea class="form-control" name="message" rows="8" placeholder="Type your message here"></textarea>
    </div>
    <button class="btn btn-default" type="submit">Send Message</button>
</form>
