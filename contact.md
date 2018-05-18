---

layout: contact
permalink: /info/contact/
title: Contact Us
long_title: Contact Us
description: Reach out and we will respond as quickly as possible
# cover: /images/sketch.png
# cover: /assets/images/cover-photos/grumser.JPG
# cover_alt:  greenhouses cover sketch
# categories: Greenhouse Planning
# tags: 
#     - Greenhouse Planning
#     - Planning
#     - Greenhouse
#     - Greenhouses
---


<form 
    action="https://formspree.io/nkline@solarinnovations.com"
    method="POST" class="mb-5 ">
    <div class="form-group">
        <label for="email">Full Name</label>
        <input type="email" name="full-name" class="form-control" id="email" aria-describedby="emailHelp" placeholder="Johnny B. Goode">
    </div>
    <div class="form-group">
        <label for="email">Email address</label>
        <input type="email" name="_replyto" class="form-control" id="email" aria-describedby="emailHelp" placeholder="Your@Email.com">
        <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
    </div>
    <div class="form-group">
        <label for="exampleFormControlTextarea1">Message</label>
        <textarea class="form-control" name="content" id="exampleFormControlTextarea1" rows="3"></textarea>
    </div>
    <input type="hidden" name="_subject" value="New IRT Contact Submission!" />
    <input type="text" name="_gotcha" style="display:none" />
    <input type="submit" class="btn btn-primary mb-2" value="Send">
</form>