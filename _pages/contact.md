---
title: "Contact"
permalink: "/contact.html"
---

<address>
  <strong>Malta Dominican Province</strong><br>
  Dominican Fathers,<br>
St. Dominic Square, Rabat,<br>
RBT 2521, Malta<br>
  <abbr title="Phone">P: </abbr>+356 2141 6680<br>
</address>
<address>
  <a href="mailto:claude3371@hotmail.com ">info@mdp.org.mt</a>
</address>

<form action="https://formspree.io/{{site.email}}" method="POST">    
<p class="mb-4">Please send your message to {{site.name}}. We will reply as soon as possible!</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Name*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="E-mail Address*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Message*" required></textarea>    
<input class="btn btn-success" type="submit" value="Send">
</form>