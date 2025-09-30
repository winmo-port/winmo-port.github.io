---
# An instance of the Contact widget.
# Documentation: https://docs.hugoblox.com/getting-started/page-builder/
widget: blank

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50

title: Get in touch
subtitle: Please fill out the form below and I’ll get back to you soon!

design:
  columns: '1'
---

<form action="https://formspree.io/f/xgvnkkng" method="POST">
  <label for="name">Your name:</label><br>
  <input type="text" id="name" name="name" required style="width:100%;padding:8px;margin-bottom:10px;"><br>

  <label for="email">Your email:</label><br>
  <input type="email" id="email" name="email" required style="width:100%;padding:8px;margin-bottom:10px;"><br>

  <label for="message">Message:</label><br>
  <textarea id="message" name="message" required style="width:100%;padding:8px;height:150px;margin-bottom:10px;"></textarea>
<br>

  <button type="submit" style="padding:10px 20px;background:#007bff;color:#fff;border:none;border-radius:5px;">
    Send
  </button>
</form>
