---

layout: contact
permalink: /info/contact/pro-staff/
title: Pro Staff Submission
long_title: Pro Staff Submission
description: Fill out the form and submit to be considered for a Pro-Staff position
---


<form 
    action="https://formspree.io/nkline@solarinnovations.com"
    method="POST"
    class="needs-validation" novalidate>
    <div class="form-group">
        <label for="name">Full Name</label>
        <input required type="name" name="Name" class="form-control" id="name" placeholder="Johnny B. Goode">
    </div>
    <div class="form-group">
        <label for="email">Email address</label>
        <input required type="email" name="_replyto" class="form-control" id="email" aria-describedby="emailHelp" placeholder="Your@Email.com">
        <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
    </div>
    <div class="form-group">
        <label for="phone">Phone Number</label>
        <input required type="phone" name="Phone" class="form-control" id="phone" placeholder="222-444-9876">
    </div>
    <div class="form-group">
        <label for="address">Address</label>
        <textarea required class="form-control" name="Address" id="address" rows="3"></textarea>
    </div>
    <div class="form-group">
      <label for="sponsor">Are you sponsored?</label>
      <select id="sponsor" Name="Sponsorship" class="form-control">
        <option>No</option>
        <option>Yes</option>
      </select>
    </div>
    <div class="form-group">
      <label for="Captian">Are you Captian?</label>
      <select id="Captian" Name="Captian" class="form-control">
        <option>No</option>
        <option>Yes</option>
      </select>
    </div>
    <div class="form-group">
        <label for="charter-numbers">How many anglers do you usually have on your charter or guide trip?</label>
        <input required type="charter-numbers" name="Number of anglers per charter trip" class="form-control" id="charter-numbers" placeholder="2-4">
    </div>
    <div class="form-group">
        <label for="fish">What species of fish do you most often target?</label>
        <input required type="fish" name="Fish species targeted" class="form-control" id="fish" placeholder="Pike, Bass, etc...">
    </div>
    <div class="form-group">
        <label for="fishing-hours">How many hours per week do you sually fish?</label>
        <input required type="fishing-hours" name="Number of hours/week fished" class="form-control" id="fishing-hours" placeholder="10-15hrs">
    </div>
    <div class="form-group">
        <label for="techniques">What techniques do you use most often?</label>
        <textarea required class="form-control" name="Fishing Techniques" id="techniques" rows="3"></textarea>
    </div>
    <div class="form-group">
        <label for="fishing-months">What months do you fish the most?</label>
        <textarea required class="form-control" name="What months do you fish the most?" id="fishing-months" rows="3"></textarea>
    </div>
    <div class="form-group">
        <label for="fishing-rods">What type and size fishing rods do you most often use?</label>
        <textarea required type="fishing-rods" name="Fishing rods used" class="form-control" id="fishing-rods" ></textarea>
    </div>
    <input type="hidden" name="_subject" value="New IRT Pro-Staff Submission!" />
    <input type="hidden" name="_next" value="{{ site.url }}" />
    <input type="text" name="_gotcha" style="display:none" />
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