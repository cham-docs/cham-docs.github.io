---
layout: page
menubar: guides_menu
title: Pipedrive
subtitle: Connects Central to Pipedrive
show_sidebar: false
toc: true
---

## Pipedrive Homepage

The homepage functionality allows users to create contacts in Central using contact information sourced from Pipedrive. Besides contacts, addresses are also generated in Central, along with a set of custom fields.

Custom fields encompass an array of additional fields, inclusive of default Central properties, to which the homepage writes when importing data from Pipedrive to Central.

## Custom Fields/Extra Fields

The supported fields for each contact include:

- ExpectedClosedDate (Date)
- LetterOfEngagement (Text)
- ProfessionalClearance (Text)
- ClientSource (Text)
- MoneyLaundering (Text)
- GoogledClient (Text)
- ClientDateOfBirth (Date)
- UniqueTaxReference (Text)
- NationalInsuranceNumber (Text)
- Submit (Text)
- AmlReceived (Text)

Please be aware that only Text and Date data types are compatible.

## Contact

The required information for creating a contact involves:

- First Name
- Last Name
- Date of Birth
- National Insurance Number (from Pipedrive's custom field)
- Unique Tax Reference (from Pipedrive's custom field)

## Address

For the primary address type, it is established for the contact, including mapping. The organisation's address is assumed to be identical to the contact's address with specific mappings:

(Pipedrive field name on the right)

- AddressLineOne (Street Number)
- AddressLineTwo (Route)
- AddressLineThree (Subpremises)
- Town (Locality)
- County = (Admin Area Level 2)
- Country = (Country)
- PostCode = (Postal Code)

## Unsupported/Known Issues

- National Insurance format
- Unique Tax Reference format
- No organisations - please create one
- Duplicate Names are not currently allowed
- Middle name is not supported
- All records are created marked as female.
- Records should have both first and last names.
- Date format has to be set to UK.
- Without an organisation, the contact would not have an address.
- Empty address fields are not supported.
