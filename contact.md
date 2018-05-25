---

layout: contact
permalink: /info/contact/
title: Contact Us
long_title: Contact Us
description: Reach out and we will respond as quickly as possible
---
<form 
    action="https://formspree.io/nkline@solarinnovations.com"
    method="POST"
    class="needs-validation" novalidate>
    <div class="form-group row">
        <label class="col-4 col-form-label text-right"  for="email">Full Name</label>
        <div class="col-sm-8">
          <input required name="full-name" class="form-control" id="email" aria-describedby="emailHelp" placeholder="Johnny B. Goode">
      </div>
    </div>
    <div class="form-group">
        <label for="email">Email address</label>
        <input required type="email" name="_replyto" class="form-control" id="email" aria-describedby="emailHelp" placeholder="Your@Email.com">
        <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
    </div>
    <div class="form-group">
        <label for="message">Message</label>
        <textarea required class="form-control" name="Message" id="message" rows="3"></textarea>
    </div>
    <input type="hidden" name="_subject" value="New IRT Contact Submission!" />
    <input type="text" name="_gotcha" style="display:none" />
    <input type="hidden" name="_next" value="{{ site.url }}/info/contact/thank-you/" />
    <input type="submit" class="btn btn-primary mb-2 float-right" value="Send">
</form>
<script>
(function() {
  'use strict';
  window.addEventListener('load', function() {
    // Fetch all the forms we want to apply custom Bootstrap validation styles to
    var forms = document.getElementsByClassName('needs-validation');
    // Loop over them and prevent submission
    var validation = Array.prototype.filter.call(forms, function(form) {
      form.addEventListener('submit', function(event) {
        if (form.checkValidity() === false) {
          event.preventDefault();
          event.stopPropagation();
        }
        form.classList.add('was-validated');
      }, false);
    });
  }, false);
})();
</script>