# User Information Tab

The User Information Tab is the first tab shown when you navigate to a specific User in Manage1to1. From this screen you will be able to see various aspects of a user including
 a quick snapshot of their devices, incidents, as well as allowing various functions such as device checkout, AUP acceptance and more.
 
## Initial Overview

This tab will showcase several key details about Manage1to1. Most prominently you will see the User Information section. This section contains the basic information regarding
 this particular user. Many of these items will be displayed in accordance with the user permissions that the currently logged in administrator has.
 
## User Information Box

![User Information Box](../_media/screenshots/user-info-box.png ':size=50%')

This box contains all of the basic information regarding the user including their ID number, name, building, etc. Additionally, this box will contain any user-defined Custom
 Fields that are marked to be shown if they contain data.
 
### Restricted Plan Setup

![Restricted Plan Setup](../_media/screenshots/restriction-plan.png ':size=50%')

Manage1to1 supports the ability for an administrative user to denote a restriction onto the User. This is a notice that is shown any time the User page is opened, as well as in
 reports. This feature allows you to put in some information that may be important in handling certain situations.
 
?> **Note:** You must have the appropriate permissions to View and Modify Restriction Plans. Administrators without the ability to View Restricted Plans will simply see a Restriction Plan Box with no content.

## User Sidebar

The sidebar provides a quick snapshot of some important user-specific data. Additionally, Manage1to1 supports the uploading of user photos to the system. This helps your Manage1to1
 administrative users put a face to the names they are seeing, helping ensure better
 service and most importantly accurate interactions.
 
### Uploading User Photos
 
 Loading photos into Manage1to1 is easy. We support all major photo formats (.png, .jpg, and .gif). The photos should be named in the format of `localid.ext` where the `localid` value is your district's internal student/staff ID number for the user and `ext` being the file extension.
 
Once the files are prepared, login to the sFTP server that your main district contact was provided when your Manage1to1 service was started. Once logged in, you will see 2
  folders - `data` and `idphotos`. Upload the photos into the `idphotos` directory root.
  
?> **Note:** Manage1to1 will not read subfolders placed within the `idphotos` directory. If a photo does not exist for a user, a blank silhouette will be shown instead.

### Checking Out a Device

![Checking Out a Device](../_media/screenshots/checkout-device.png ':size=50%')

From the User Information Tab, you are able to checkout a device to a user. To do this, simply click on the Checkout Device button underneath the user photo and stats summary. A popup will be displayed with your cursor already in the Search Field. From this screen it is possible to use a barcode scanner or immediately begin typing the device's Barcode, Asset Tag or Loaner Number. Each letter you type will result in list being instantly filtered.
 
![Checkout Confirmation](../_media/screenshots/user-checkout-confirmation.png ':size=50%')

Once you have identified the device you wish to checkout, simply click the Checkout Device button under the Action column. You will be redirected to a confirmation screen showcasing a quick snapshot of the User and Device you are about to link together. The current timestamp is input into the Date Issued Field, however this can be manually adjusted as needed. Clicking `Check-Out Device` will check the indicated device out to the user whereas clicking `Cancel & Return to User Profile` will stop the checkout process and return you to the user profile screen.

### Accepting Device Fee / AUP

If the User has not yet paid their device fee or accepted their AUP, a button will appear below the Checkout Device button. Clicking on the respective button will perform the action.

If an invoice was created that contained a Device Fee, it will automatically be marked as paid once the invoice has been paid. 

### Printing a Snapshot

Clicking on the Print Snapshot button will render a printer-friendly version of the entire User Information Tab. This is particularly useful when wanting to showcase information to users who may not have access to Manage1to1 such as Parents or Teachers. This file can then be printed or saved as a PDF for your consumption.

## Current Devices Box

![Current Devices](../_media/screenshots/user-current-devices.png ':size=50%')

This box will showcase all of the devices that are currently in posession of this user. A quick snapshot of information is available here including the Issue Date, Model of Device, Serial Number, Asset Tag, Loaner # (if applicable), and an action row that will allow you to view the device, check in the device, or create an incident about the device.

## Current Incidents Box

![Current Incidents](../_media/screenshots/user-current-incidents.png ':size=50%')

This box will showcase all of the outstanding (not Completed) incidents that are associated with this user. A quick snapshot of information is available here including the Incident Date, Model of Device, Serial Number, a Quick Visual Reference for the Incident, and a hidden action row that will allow you to view the incident directly by clicking the blue + symbol.
