---
title: "Contact"
date: 2021-06-17T13:58:33+07:00
draft: false
---

<section class="flex flex-align-items-center flex-justify-content-center">
    <div>
        <h1 class="text-center">Contact Me</h1>
        <h3 class="text-center">I'll <span id="word-rotating">Listen to,Care about,Solve</span> Your Problem</h3>
    </div>
</section>

<section class="margin-xlarge margin-large@m margin-remove-horizontal@m grid grid-4-columns grid-1-columns@m gap-medium">
    <div>
        <h6>Email</h6>
        <p><a id="email-link"></a></p>
        <h6>Address</h6>
        <p>3rd Floor at Penggung Shophouse<br/>Semarang, Indonesia<br/>Postal 50227</p>
        <h6>Phone</h6>
        <p><a href="tel:+6285727760737">+62 85 727 760 737</a></p>
    </div>
    <div class="grid-column-span-3 grid-column-span-1@m">
        <h4>Send message for me directly!</h4>
        <form id="contact-form" method="post" role="form">
            <div class="form-field margin-remove-left margin-remove-top">
                <label class="form-label margin-remove-top">Name</label>
                <div class="form-control">
                    <input id="form-name" name="name" type="text" placeholder="Please enter your name" class="form-input width-1/2 width-1/1@m" />
                </div>
            </div>
            <div class="form-field margin-remove-horizontal">
                <label class="form-label">Email</label>
                <div class="form-control">
                    <input id="form_email" name="_replyto" type="email" placeholder="Please enter your email" class="form-input width-1/2 width-1/1@m" />
                    <input type="hidden" name="_subject" value="Yay! You got new message" />
                    <input type="hidden" name="_next" value="/contact/thanks" />
                </div>
            </div>
            <div class="form-field margin-remove-horizontal">
                <label class="form-label">Message</label>
                <div class="form-control">
                    <textarea id="form_message" name="message" placeholder="Message for me" class="form-input width-1/1" rows="6"></textarea>
                </div>
            </div>
            <div class="form-field margin-remove-horizontal">
                <div class="form-control">
                    <button type="submit" class="button button-primary">Send message</button>
                </div>
            </div>
        </form>
    </div>
</section>

<script>
    var emailLink =  document.getElementById('email-link');
    emailLink.setAttribute('href', 'mailto:' + 'hi' + '@' + 'pratamabayu' + '.' + 'com');
    emailLink.innerText = 'hi' + '@' + 'pratamabayu' + '.' + 'com';

    var contactform =  document.getElementById('contact-form');
    contactform.setAttribute('action', '//formspree.io/' + 'contact.me.pratama.bayu' + '@' + 'gmail' + '.' + 'com');
</script>
