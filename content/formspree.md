+++
title = "Contact"
weight = 60
menuname = "Contact"
draft = false
+++

<form id="contactform" method="post" action="https://formspree.io/zeevtorrestal@gmail.com">
	<div class="field half first">
		<input type="text" name="name" id="name" placeholder="Name"/>
	</div>
	<div class="field half">
		<input type="email" id="email" name="email" placeholder="Email">
	</div>
	<div class="field">
		<textarea name="message" id="message" rows="3" placeholder="Message"></textarea>
	</div>
	<ul class="actions">
		<li><input type="submit" value="Send message" class="special" /></li>
		<li><input type="reset" value="Reset" /></li>
	</ul>
	<input type="hidden" name="_next" value="?sent#formspree" />
	<input type="hidden" name="_subject" value="Subject for your mail like new message" />
	<input type="text" name="_gotcha" style="display:none" />
</form>
<span id="contactformsent">Thank you for your message</span>

<script>
$(document).ready(function($) {
    $(function(){
        if (window.location.search == "?sent") {
        	$('#contactform').hide();
        	$('#contactformsent').show();
        } else {
        	$('#contactformsent').hide();
        }
    });
});
</script>


{{< socialLinks >}} {{< gmaps pb="!1m18!1m12!1m3!1d47789.67680750795!2d173.93280799999997!3d-41.52908575!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x6d390e0080e269bd%3A0xa00ef88e796a530!2sBlenheim!5e0!3m2!1sen!2snz!4v1537014591074" >}}
