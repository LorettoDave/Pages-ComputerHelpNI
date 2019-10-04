---
layout: post
title:  "The padlock doesn't mean a site is safe"
tags: Security
author: Dave Rand
---
Your web browser shows a green padlock when you're securely connected to a website. This means your information will be encrypted in transit, so eavesdroppers are unable to read passwords, payment details, or other sensitive information.

While the padlock indicates a secure connection, it does not guarantee the website itself is safe. Some phishing attacks include links to fake websites that use secure connections, so your browser could show a green padlock *even when connected to a fake website*. For example, this forged PayPal site uses a secure connection:<br/>
<span class="ImageCenter">![Alt](/assets/images/blog-fake-paypal-login.png "Forged PayPal site")</span>

When accessing a secure website, look carefully at the web address. Sometimes the full URL may be hidden, so what looks like 'www.paypal.com' might actually be 'www.paypal.com-e.site' or something similar. Before sending sensitive information to a website, ensure the web address is correct—even if your browser displays a green padlock.
