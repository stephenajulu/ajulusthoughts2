---
title: Contact
---

Hi, there? 

Would you like to contact us?

Feel free to fill in the details below and send us a message and we'll on our way to reply.


### Note:

SPAM will be deleted.

Kindly don't submit confidential tips here rather use our secure means listed here: [Tip Us Securely](/tip-us)

To sign up as an advertiser, use [Advertise Here Page](/advertise-here)

Check our [Code of Conduct](/code-of-conduct) to see what will be accepted and what will be rejected before contacting us.

<section id="subscriptionSection" class="section narrow">
  <div class="subscription-container">
        <div class="subscription-content">
<form id="subscriptionForm" class="subscription-form" data-netlify="true">
<fieldset>
<!-- Form Name -->
<legend class="subscription-heading">Contact Us</legend>
<!-- Text input-->
<div class="form-group">
  <label class="col-md-4 control-label" for="name">What's your name/company name?</label>  
  <div class="col-md-4">
  <input id="name" name="name" type="text" placeholder="e.g John Doe" class="form-control input-md" required="">
  </div>
</div>
<!-- Text input-->
<div class="form-group">
  <label class="col-md-4 control-label" for="email">What's your email?</label>  
  <div class="col-md-4">
  <input id="emailInput" class="subscription-input" name="email" type="text" placeholder="e.g johndoe@gmail.com" class="form-control input-md" pattern="^[a-zA-Z0-9.!#$%&'*+/=?^_`{|}~-]+@[a-zA-Z0-9](?:[a-zA-Z0-9-]{0,61}[a-zA-Z0-9])?(?:\.[a-zA-Z0-9](?:[a-zA-Z0-9-]{0,61}[a-zA-Z0-9])?)*$" required>
  </div>
</div>
<!-- Multiple Radios -->
<div class="form-group">
  <label class="col-md-4 control-label" for="purpose">The Purpose?</label>
  <div class="col-md-4">
  <div class="radio">
    <label for="purpose-0">
      <input type="radio" name="purpose" id="purpose-0" value="1" checked="checked">
      Advertise/Become a Sponsor🤝
    </label>
	</div>
  <div class="radio">
    <label for="purpose-1">
      <input type="radio" name="purpose" id="purpose-1" value="2">
      Become an author 😎
    </label>
	</div>
  <div class="radio">
    <label for="purpose-2">
      <input type="radio" name="purpose" id="purpose-2" value="3">
      Voice an opinion 🗣
    </label>
	</div>
  <div class="radio">
    <label for="purpose-3">
      <input type="radio" name="purpose" id="purpose-3" value="4">
      Inquire about oour services 💼
    </label>
	</div>
  <div class="radio">
    <label for="purpose-4">
      <input type="radio" name="purpose" id="purpose-4" value="5">
      Feature us(Hooray! 🎉)
    </label>
	</div>
  <div class="radio">
    <label for="purpose-5">
      <input type="radio" name="purpose" id="purpose-5" value="6">
      Report an issue/bug 🙁🐛
    </label>
	</div>
  <div class="radio">
    <label for="purpose-6">
      <input type="radio" name="purpose" id="purpose-6" value="7">
      Request coverage on a topic 🤩
    </label>
	</div>
  <div class="radio">
    <label for="purpose-7">
      <input type="radio" name="purpose" id="purpose-7" value="8">
      Copyright and Legal 👮‍♂️
    </label>
	</div>
  <div class="radio">
    <label for="purpose-8">
      <input type="radio" name="purpose" id="purpose-8" value="9">
      Just saying hi 👋
    </label>
	</div>
  <div class="radio">
    <label for="purpose-9">
      <input type="radio" name="purpose" id="purpose-9" value="10">
      Join Our Newsletter 📨
    </label>
	</div>
  <div class="radio">
    <label for="purpose-10">
      <input type="radio" name="purpose" id="purpose-10" value="11">
      Other 😃
    </label>
	</div>
  </div>
</div>
<!-- Textarea -->
<div class="form-group">
  <label class="col-md-4 control-label" for="message">Would you like to attach a message?</label>
  <div class="col-md-4">                     
    <textarea class="form-control" id="message" name="message"></textarea>
  </div>
</div>
<!-- Button -->
<div class="form-group">
  <label class="col-md-4 control-label" for="submit"></label>
  <div class="col-md-4">
    <button id="submit submitButton" name="submit" class="btn btn-primary submit-button">Send The Message</button>
  </div>
  <div class="subscription-error-message">
                    The email you entered is not valid.
                </div>
</div>
</fieldset>
</form>
</div>
</div>
</section>

{{ $script := resources.Get "js/addFormStyles.js" }}
<script src="{{ $script.RelPermalink }}"></script>
