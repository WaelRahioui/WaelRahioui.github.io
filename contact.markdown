---
layout: page
title: Contact Me
description: Have questions? I have answers
#permalink: /contact/
background: '/1661730685085.jpeg'
---
I created this blog with the aim of sharing my passion for Machine Learning and its advancements with others who share an interest in this field 🤖. I believe that staying informed about the latest research and trends is crucial for professionals, academics, and enthusiasts alike 💻📚, and I hope this blog will be a valuable resource for anyone looking to keep up with the latest developments in AI 💡.

As a Master’s student at UC Berkeley, I am constantly exposed to cutting-edge research and innovative ideas in the field. By writing about these topics, I hope to not only share my own insights and understanding 💭, but also to encourage dialogue and collaboration with others who are equally invested in the future of AI.

If you have any questions or would like to get in touch, feel free to reach out to me through the contact information below. I would be more than happy to hear from you! 💬


<form name="sentMessage" id="contactForm" novalidate>
    <div class="control-group">
      <div class="form-group floating-label-form-group controls">
        <label>Name</label>
        <input type="text" class="form-control" placeholder="Name" id="name" required data-validation-required-message="Please enter your name.">
        <p class="help-block text-danger"></p>
      </div>
    </div>
    <div class="control-group">
      <div class="form-group floating-label-form-group controls">
        <label>Email Address</label>
        <input type="email" class="form-control" placeholder="Email Address" id="email" required data-validation-required-message="Please enter your email address.">
        <p class="help-block text-danger"></p>
      </div>
    </div>
    <div class="control-group">
      <div class="form-group col-xs-12 floating-label-form-group controls">
        <label>Phone Number</label>
        <input type="tel" class="form-control" placeholder="Phone Number" id="phone" required data-validation-required-message="Please enter your phone number.">
        <p class="help-block text-danger"></p>
      </div>
    </div>
    <div class="control-group">
      <div class="form-group floating-label-form-group controls">
        <label>Message</label>
        <textarea rows="5" class="form-control" placeholder="Message" id="message" required data-validation-required-message="Please enter a message."></textarea>
        <p class="help-block text-danger"></p>
      </div>
    </div>
    <br>
    <div id="success"></div>
    <div class="form-group">
      <button type="submit" class="btn btn-primary" id="sendMessageButton">Send</button>
    </div>
  </form>