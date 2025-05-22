---
layout: page
menubar: guides_menu
title: Direct Debits
subtitle: Enables integration between Central and BACS processes.
show_sidebar: false
toc: true
hero_height: is-small
hide_footer: true
---

## Direct Debits Homepage

### Access

User access to the Direct Debits functionality is controlled via two CCH Central tasks and their associated task permissions. Assign the following roles (task permissions) to the appropriate user groups in CCH:

```
CIT.Sunrise Direct Debits
CIT.Sunrise Direct Debits.Administrator
```

### Adding New Clients

To add a new client to Direct Debits:

1. In the CCH Clients tab, set the Payment Type to Direct Debits.
2. The client (if not closed) will then appear in the Clients tab on the Direct Debits homepage.
3. Set the Activation Date and check the Active tickbox.
4. Optionally, enter a specific Amount to Collect, or leave it blank. If left blank, the system will calculate the outstanding amount during the Direct Debits run.
5. Set the T Code to 01 or another appropriate value.

### Creating a Run

To schedule a Direct Debits run:

1. Specify the desired date for the run.
2. All configured clients will appear in the list—either showing outstanding amounts or the fixed amounts set in the Clients screen.
3. By default, the Amount to Collect is based on the outstanding amount, unless a payment plan is in place.
4. Clients can be added or removed from the run using the Add and Remove buttons.
5. Totals for both Collected and Allocated amounts are displayed above the grid.

### Record Colours

* Red: Records that require bank details to be reviewed or corrected.
* Light Gray: Records that are not yet activated. These can be reviewed in the Clients screen.
* Light Yellow: certified records.

### AUDDIS

The AUDDIS file can be generated for all 0N records at any point while the run is open.

### Proposing Records

* Adjust the Amount to Collect and Amount to Allocate as needed.
* Once ready, Propose the records. This enables the next stage: Certification

### Certification

Who Can Certify?

1. Partners can certify records for their own clients.
2. Employees configured in CCH Central with certification permissions can certify on behalf of partners.

A run is considered fully certified only when all records within it have been certified.

Amounts can be modified for any record that is temporarily Uncertified or Unproposed.

### Grouping Records

To group records:

1. Assign the same Core Reference to each related client.
2. The Core Reference identifies a shared collection—for example:
* Client A collects £1,000.
* £500 is allocated to Client A.
* £500 is allocated to another client with the same Core Reference.

This functionality supports grouped allocations.

### Completing a Run

* A Direct Debits file can be generated and processed using the BASC program.

* If all records in the run are certified, the run can be Closed.

Upon closure, all transactions are posted to CCH Central and allocated where applicable.

Records from completed runs can be reviewed in the History tab.
