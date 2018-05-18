---

layout: contact
permalink: /info/support/reel-registration/
title: Reel Registration
long_title: Reel Registration
description: Register your reel to claim your Limited Lifetime Warranty
---


<div id="messageBox"></div>
<form id="reel-registration"  novalidate>
    <div class="form-group row">
        <label for="serial-number" class="col-sm-4 col-form-label text-right">Reel Serial Number</label>
        <div class="col-sm-8">
            <div class="input-group mb-2">
                <div class="input-group-prepend">
                    <div class="input-group-text">#</div>
                </div>
                <input required class="form-control" id="SN" name="SN" placeholder="1234">
            </div>
        </div>
    </div>
    <div class="form-group row">
        <label for="name" class="col-sm-4 col-form-label text-right">Full Name</label>
        <div class="col-sm-8">
            <input required class="form-control" id="Name" name="Name" placeholder="Johnny B. Goode">
        </div>
    </div>
    <div class="form-group row">
        <label for="email" class="col-sm-4 col-form-label text-right">Email</label>
        <div class="col-sm-8">
            <input type="email" required class="form-control" id="email" name="Email" placeholder="Your@Email.com">
        </div>
    </div>
    <div class="form-group row">
        <label for="phone" class="col-sm-4 col-form-label text-right">Phone</label>
        <div class="col-sm-8">
            <input required class="form-control" id="phone" name="Phone" placeholder="777-123-4567">
        </div>
    </div>
    <div class="form-group row">
        <label for="address" class="col-sm-4 col-form-label text-right">Address</label>
        <div class="col-sm-8">
            <textarea required class="form-control" id="address" name="Address" placeholder="31 Roberts Road, Pine Grove, Pennsylvania 17963"></textarea>
        </div>
    </div>
    <div class="form-group row">
        <label for="country" class="col-sm-4 col-form-label text-right">Country</label>
        <div class="col-sm-8">
            <input required class="form-control" id="country" name="Country" placeholder="US">
        </div>
    </div>
    <div class="form-group row">
        <label for="company" class="col-sm-4 col-form-label text-right">Company</label>
        <div class="col-sm-8">
            <input required class="form-control" id="company" name="Company" placeholder="IRT Reels">
        </div>
    </div>
    <div class="row">
        <span class="col-8 my-auto text-right" style="color:#d83105"><strong>All fields are required.</strong></span>
        <button type="submit" id="submit-form" class="btn btn-primary col-4 btn-block">Submit</button>
    </div>

</form>


