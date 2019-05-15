---
layout: page
title: contact
form: true
---

<div class="row justify-content-between">
<div class="col-md-8 pr-5">

<p>This website is built with Jekyll and many other gem-based themes.</p>

<p class="md-5"><img class="md-5 img-fluid shadow-lg" src="img/treehouse.jpg" alt="jekyll template" /></p>

<p>Please, read the docs <a href="https://google.com/">here</a>.</p>

<h4>Questions or bug reports?</h4>

<p>Head over to my <a href="https://github.com/dizzySummer">Github repository</a>!</p>


<a target="_blank" href="https://yahoo.com/" class="btn btn-danger">1st button</a> <a target="_blank" href="https://google.com/" class="btn btn-warning">2nd button</a>

</div>

<div class="col-md-4">

<p>Want to get in touch? Fill out the form below to send me a message and I will get back to you as soon as possible!</p>
<form name="sentMessage" action="https://getform.io/f/1d000e19-f4c6-45f4-9db5-9b9449d42d9e" method="POST" accept-charset="UTF-8" >

<div class="control-group">
<div class="form-group floating-label-form-group controls">
  <label>Subject</label>
  <input type="text" class="form-control" placeholder="Subject" name="subject" id="subject" data-validation-required-message="Please enter your subject.">
  <p class="help-block text-danger"></p>
</div>
</div>
<div class="control-group">
<div class="form-group floating-label-form-group controls">
  <label>Name</label>
  <input type="text" class="form-control" placeholder="Name" name="name" id="name" required data-validation-required-message="Please enter your name.">
  <p class="help-block text-danger"></p>
</div>
</div>
<div class="control-group">
<div class="form-group floating-label-form-group controls">
  <label>Email Address</label>
  <input type="email" class="form-control" placeholder="Email Address" name="email" id="email" required data-validation-required-message="Please enter your email address.">
  <p class="help-block text-danger"></p>
</div>
</div>
<div class="control-group">
  <div class="form-group col-xs-12 floating-label-form-group">
    <label>Phone Number</label>
    <input type="tel"  class="form-control"  placeholder="Phone Number" name="tel" id="phone">
    <p class="help-block text-danger"></p>
  </div>
</div>
<div class="control-group">
<div class="form-group floating-label-form-group controls">
  <label>Message</label>
  <textarea rows="5" class="form-control" placeholder="Message" name="_message" id="message" required data-validation-required-message="Please enter a message."></textarea>
  <p class="help-block text-danger"></p>
</div>
</div>
<br>
<div id="success"></div>
<div class="form-group">
<button type="submit" class="btn btn-primary" id="sendMessageButton">Send</button>
</div>
</form>
</div>
</div>
