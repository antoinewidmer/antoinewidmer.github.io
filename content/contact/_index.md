---
title: "Contact"
subtitle: "Get in touch with the IPC4MH Coordination Team"
type: "page"
# Optional: add to menu via your site config if not already linked
# menu:
#   main:
#     weight: 50
#     name: "Contact"
---

For enquiries about the IPC4MH project, partnerships, or media, please use the form below.

<form action="https://usebasin.com/f/YOUR_BASIN_ENDPOINT" method="POST" accept-charset="UTF-8" class="form">
  <!-- Honeypot -->
  <input type="text" name="company" tabindex="-1" autocomplete="off" style="position:absolute;left:-5000px;opacity:0" aria-hidden="true">

  <div class="grid" style="display:grid;grid-template-columns:1fr 1fr;gap:1rem;">
    <div style="grid-column:span 1;">
      <label for="name">Name *</label>
      <input id="name" name="name" type="text" required>
    </div>

    <div style="grid-column:span 1;">
      <label for="email">Email *</label>
      <input id="email" name="email" type="email" required>
    </div>

    <div style="grid-column:1 / -1;">
      <label for="subject">Subject</label>
      <input id="subject" name="subject" type="text">
    </div>

    <div style="grid-column:1 / -1;">
      <label for="message">Message *</label>
      <textarea id="message" name="message" rows="6" required></textarea>
    </div>

    <div style="grid-column:1 / -1;display:flex;align-items:flex-start;gap:.5rem;">
      <input id="consent" name="consent" type="checkbox" required>
      <label for="consent" style="margin:0;">
        I consent to IPC4MH processing my data for the sole purpose of answering this enquiry. I understand I can request deletion in accordance with GDPR.
      </label>
    </div>

    <input type="hidden" name="_subject" value="IPC4MH Contact Form Submission">
    <!-- Optional redirect -->
    <!-- <input type="hidden" name="_redirect" value="https://ipc4mh.eu/contact/thanks/"> -->

    <div style="grid-column:1 / -1;">
      <button type="submit" class="btn btn-primary">Send message</button>
    </div>
  </div>
</form>



---

### Data protection notice
Messages submitted via this form are transmitted to the IPC4MH coordination team and processed exclusively for project-related communications. No data are shared with third parties. You may request deletion at any time.
