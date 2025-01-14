---
title: "Image Captioning using CLIP and Marian"
subtitle: "How we combined CLIP and Marian to build an image captioning model for Indonesian."
excerpt: "How we combined CLIP and Marian to build an image captioning model for Indonesian."
date: 2019-07-01
author: "Eric Anderson"
draft: false
images:
  - /blog/assets/built-in-contact-form-thumbnail.png
series:
  - huggingface jax flax event
tags:
  - report
categories:
  - image-captioning
layout: single-sidebar
---

### Functional Form

This theme has a **form-to-email** feature built in, thanks to the simple Formspree integration. All you need to activate the form is a valid recipient email address saved in the front matter of the form
(`/content/forms/contact.md`). Of course, the example shown below (`your@email.here`) must not be used. Please use your actual email address.

```toml
# please replace with a valid Formspree form id or email address
formspree_form_id: your@email.here
```

Update that file and you're ready to begin receiving submissions. Just submit
the active form for the first time, and complete the email address verification
step with Formspree, and your contact form is live. The next time someone
fills it out, the submission will land in your inbox.

### Multiple Layouts

The files included with the theme have a contact page ready for copy/paste, or
you can type `hugo new forms/contact.md` and you're off to the races. There are two
layouts for `forms` – `split-right`, and `split-left` – you guessed it, one puts
the form on the right and the other on the left. You just fill out the front
matter, and the rest is automatic.

```toml
# layout options: split-right or split-left
layout: split-right
```

Both layouts display the page title and description opposite the form, and you
can also choose to show your social icon links if you have those configured in
the `config.toml` file.
