---
title: ~/contact
layout: page
permalink: /contact
---

# Get in touch


<form action="https://formspree.io/f/mqknnzqy" method="POST">
  <input type="text" id="email" name="email" placeholder="your email" autocomplete="off">
  <input type="text" id="subject" name="subject" placeholder="your subject" autocomplete="off">
  <textarea rows="5" id="message" name="message" placeholder="your message" autocomplete="off"></textarea>
  <input type="submit" value="[ submit ]">
</form>

<hr />



Things might not go right way! 
So, here is my email: bijay.maharjan5@gmail.com



If you are curious why it won't work, then:
I am using AWS Amplify to host the site, and they do not provide CSR headers. And since this site is built using Jekyll, Jekyll is simply a static HTML generation tool. It doesn't have the ability to do anything besides generate HTML which includes inline HTML headers.

And we see errors like:

'...because it violates the following Content Security Policy directive...'



Will fix this soon.
