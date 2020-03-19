# ContactManager
Simple demo application that shows the existing contacts.

# App Screenshots

<table>
  <tr>
    <td>Display All Contacts</td>
     <td>Contact Details</td>
     <td>Edit Contact</td>
  </tr>
  <tr>
    <td><img src="screenshots/AllContacts.png" width=270 height=480></td>
    <td><img src="screenshots/ContactDetails.png" width=270 height=480></td>
    <td><img src="screenshots/Edit_Contact.png" width=270 height=480></td>
  </tr>
 </table>
 
 # Project Structure
 
 ### ViewControllers
 
 #### ContactViewController
 
 This ViewController used to present the existing contact details in TableView
 
 #### ContactEditViewController
 
 This ViewController used to edit existing contact add add new contact
 
 #### ContactDetailsViewController
 
 This ViewController used view the contact details, call relevant phone number and default dialler will open.
 
 ### ContactDataService
 
 This class used to retrive contact details, add Contact, Delete Contact and update Contact to CNContactStore.
 
 ### ContactDataManager
 
 This manager class manages the add/edit/delete contact details
 





