---
layout: post
title:  "The padlock doesn't mean a site is safe"
categories: Security
author: Dave Rand
---
Most web browsers show a padlock in the address bar when you're securely connected to a website. This means the information sent between your browser and the web server is encrypted, so eavesdroppers are unable to read passwords, payment details, or any other sensitive information that might be sent.

While the padlock indicates a secure *connection*, it does not guarantee the website itself is *safe*. Some phishing attacks include links to fake websites that use secure connections, and when visiting such a website your browser would show a padlock to indicate a secure connection *even when connected to a fake website*. For example, this forged PayPal site uses a secure connection:<br/>
<span class="ImageCenter">![Alt](/assets/images/blog-fake-paypal-login.png "Forged PayPal site")</span>

When accessing a secure website, look carefully at the web address. Sometimes the address is too long for your browser so display, so part of it may be hidden by the address bar. In such cases, an address that looks like 'www.paypal.com' might actually be 'www.paypal.com-e.site' or something similar. 

Before sending sensitive information to a website, ensure the web address is correct by clicking on the address and reading what's there. Everything in between 'https://' and the next slash '/' should match what you would expect. In our PayPal example, you should see something like 'www.paypal.com' or 'paypal.co.uk', not 'www.paypal.com-e.site'. If in doubt, phone Computer Help NI for advice.
