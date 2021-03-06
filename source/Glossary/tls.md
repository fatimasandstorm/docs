---
layout: page
weight: 0
title: Transport Layer Security
navigation:
  show: true
seo:
  title: Transport Layer Security
  override: true
  description: Protect transmission of email information with TLS and SendGrid
---
Transport Layer Security (TLS) is an encryption protocol that’s used to encrypt information in transit over the Internet.  TLS uses certificates to encrypt sessions to maintain confidentiality of information.  SendGrid uses TLS to encrypt sessions with its application via HTTPS and API.

SendGrid also utilizes “opportunistic TLS” for [sending email via SMTP]({{root_url}}/Getting_Started/Sending_Emails_With_SendGrid/index.html) or our [Web API]({{root_url}}/API_Reference/Web_API/index.html).  Opportunistic TLS means that we will encrypt your email sending from your end point all the way to the recipient, providing that the recipient’s mail server is configured to support TLS.

Using TLS is increasingly important to protect your privacy and the privacy of your recipients, and to prevent online surveillance.  

For more background on opportunistic TLS, read our blog post on the [Future of Email Security](https://sendgrid.com/blog/sendgrid-and-the-future-of-email-security/).  

For information on configuring your system to utilize TLS, see our information on [setting up your server]({{root_url}}/User_Guide/Setting_Up_Your_Server/index.html) for sending email.
