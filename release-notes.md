# Release Notes

Whenever a new version of Manage1to1 is released, we publish the change log/release notes on our website. Beginning June 01, 2019 - we have re-termed change log to be release notes as it is more applicable to the style of information we provide. Below you can find a link to view the release notes of each release.

_(We are presently migrating from our old change log page to this new format and until complete, this page may not be complete)_

## 3.0.3

*September 5th, 2020*

**Release Type:** Maintenance

#### Bugs
- MAN-499	Photos broken if the admin does not have LocalID permissions
- MAN-497	Unable to change status of Incidents without a user assigned
- MAN-496   Allow users to be edited if over license count
- MAN-495	Grade inaccurate in Incident Snapshots
- MAN-500	Ensure Invoice Permissions Pass through correctly
- MAN-498	Incident Photo Upload not working and has incorrect text

## 3.0.2

*August 11th, 2020*

**Release Type:** Maintenance

#### Notable Changes
> - Introduced additional report filters on various reports
> - Various improvements

#### Bugs
- MAN-478	Daily Tasks not running properly
- MAN-479	Ensure Large Tables shrink more efficiently
- MAN-480	Cleanup processed data for user-initiated imports
- MAN-477	Student Photos fail to load if a letter is present in the Student ID
- MAN-481	500 Error on User Export
- MAN-483	Incident Flags are missing when hidden in the Admin Area
- MAN-484	Adding a device note results in a 404 page
- MAN-464	Configuration is cleared when users modify allowed values while not logged in
- MAN-476	Cannot change incident status
- MAN-475	Add user results in a 404 error

#### Improvements
- MAN-482	Enhanced filters on Reports
- MAN-486	Increased efficiency of Encrypting and Decrypting sensitive data
- MAN-488   Migrate CDN content to self-maintained CDN

#### Features
- MAN-485	Customization of License Alert Thresholds

## 3.0.1

*July 27th, 2020*

**Release Type:** Maintenance

#### Notable Changes
> - Allow both per-user and per-device insurance
> - Introduced batch Invoice PDF processing

#### Bugs
- MAN-466	Device checkouts have incorrect data when upgrading
- MAN-463	Device OS is inaccurate on the Device Edit page
- MAN-461	Unable to modify existing invoices
- MAN-469	User Incident History is missing
- MAN-470	Unable to remove Invoice Transactions
- MAN-455	Graduation Year ignores the currently set school year
- MAN-471   Adding an Invoice from the User Profile screen does not bind the invoice to the user automatically
- MAN-471	Email Address Fields processing as required even when optional
- MAN-467	Polish 3rd party integrations display in the UI
- MAN-473	Ensure non-loaner devices do not require a loaner number to add or modify

#### Features
- MAN-468   Allow both Per-User & Per-Device Insurance to be set
- MAN-458   Introduce Batch Invoice PDF processing

## 3.0.1

*July 27th, 2020*

**Release Type:** Major

#### Notable Changes
> - Introduced a brand-new layout
> - Optimized all scripting on all pages to decrease loading time
> - Introduced a global, intelligent search feature
> - Introduced customizable Invoice Statuses

#### Bugs
- MAN-357	Resolved Incident Photo Error
- MAN-358	Resolved all record logging date inconsistencies
- MAN-360	Activity Log Cleanup was terminating daily tasks
- MAN-364	Unable to set visibility for Device Type/Model
- MAN-365	Incidents will not update as Flagged
- MAN-368	Unable to delete Users, Devices, Incidents, or Invoices due to Notes being present
- MAN-402	Cannot set a Device as a Loaner
- MAN-403	Device Export times out
- MAN-404	Cannot update email addresses via automated Student Update Import
- MAN-413	Staff Import File is being ignored
- MAN-414	CSV is not recognized on machines without Excel installed during the Upload
- MAN-416	Ensure Email Templates are not stripping formatting
- MAN-418	Cannot create or update incidents with no associated user
- MAN-437	Checkout Device button is missing under certain circumstances
- MAN-443	Cannot unhide or hide devices via UI
- MAN-445	Error if an image size cannot be calculated while emailing an invoice with associated images
- MAN-455	Graduation Year calculates from the current date and time instead of the configured school year

#### Improvements
- MAN-406	School Year Rollover resets Device Fee and AUP Flags for Student Users
- MAN-415	Additional Options to for Automation Student Updated Introduced
- MAN-419	Standardized Date Formatting
- MAN-363	Improved Licensing Handling for Overages, Suspensions, and Expired Licenses
- MAN-412	Prevent the Display of Account Overdue Status to Non-Point of Contact Users

#### Features
- MAN-338	Documentation Links are now Provided on Every Page
- MAN-352	Introduced a new Layout Theme
- MAN-220	Google SSO Login Integration
- MAN-369	Global Intelligent Searching
- MAN-420	Customizable Invoice Statuses
- MAN-431	Incident Export
- MAN-408	Robust Email Templating
- MAN-449	Printable Incident Snapshot
- MAN-454	Daily Flagged Incident Email
- MAN-287	Bulk Staff Import Utility
- MAN-456	Selectable Username Generation Type
- MAN-88	Email End User when an Incident Status is set to "Waiting Pickup"