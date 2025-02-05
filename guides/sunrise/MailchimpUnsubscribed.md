---
layout: page
menubar: guides_menu
title: Mailchimp Unsubscribed
subtitle: Updates Mailchimp unsubscribes in Central.
show_sidebar: false
toc: true
hero_height: is-small
hide_footer: true
---

## Mailchimp Unsubscribed Homepage

### Overview:

The unsubscribe feature allows synchronisation of contacts unsubscribed in Mailchimp to specific fields in Central. It's important to note that only the value in the Extra Field is set, and no actual contact data is transferred. For instance, if Bob Testington (with email bob@gmail.com) exists in both Mailchimp and Central, and Bob unsubscribes in Mailchimp, this information can be saved in a designated Extra Field (let's say "Unsubscribed in Mailchimp") in Central. Utilising this feature in Sunrise, you can bulk update the "Unsubscribed in Mailchimp" Extra Field in Central based on the information from Mailchimp.

### Configuration:

In the settings form, set the Unsubscribed Extra Field name to the text Extra Field, and the Extra Value to the text value indicating that the contact has been unsubscribed. Ensure that this selected Extra Field is applicable to contacts (and not just clients).

### Usage:

Once contacts are unsubscribed in Mailchimp, navigate to the Sunrise Mailchimp Unsubscribed page to list all contacts marked as unsubscribed in Mailchimp but without the Extra Field set in Central yet. If you choose to update (by selecting contacts and clicking on the Update button), the Extra Field/Extra Value will be set for the selected contacts. The extra value will be configured to match the value specified in the Settings form.
