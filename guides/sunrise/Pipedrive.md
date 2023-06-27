---
layout: page
menubar: guides_menu
title: Pipedrive
subtitle: Connects Central to Pipedrive
show_sidebar: false
toc: true
---

## Pipedrive Homepage

The homepage offers a feature that allows users to synchronise Pipedrive individuals with contacts in Central. Users can search for matching individuals based on the date they were added, specifying a date range using "from" and "to" dates. Once the matching records are found, users can review them and choose which ones to import as contacts in Central. When creating contacts in Central, the address from Pipedrive's organisation will be utilised as the address for the newly created contacts.

The table provided below outlines the correspondence between the fields in Pipedrive and Central.

```
(Pipedrive) -> (Central)
(Person) First Name -> (Contact) First Name
(Person) Last Name -> (Contact) Last Name
(Organisation) Address Street Number -> (Address) Line One
(Organisation) Address Route -> (Address) Line Two
(Organisation) Address Locality -> (Address) Town
(Organisation) Address Country -> (Address) Country
(Organisation) Address Postal Code -> (Address) Post Code
```

The creation of contacts will involve utilising the "Other Contact" category along with the "Business" address type.
