---
layout: page
title: Contact
permalink: /contact/
---

<img align="right" style="padding-right: 16px;" src="{{ "/assets/img/contact.jpg" | relative_url }}" alt="Get in touch" width="310" />

If you have any enquiries and would like to get in touch, you can write me an email using the form below.

Business hours:

Tuesday - Saturday 09:30am - 16:30pm (IST)

<form class="contact" target="_blank" action="mailto:{{ site.email }}" method="GET" enctype="text/plain">
  <input name="subject" type="text" placeholder="Subject" />

  <textarea name="body" placeholder="Hi there..."></textarea>
  <br>

  <input type="submit" value="Send" />
</form>
