README
_______

This simple program helps me create a new Contact card with details 
* name
* Position
* Company name
* HTTP page
* Email
* Phone-number

that can either be imported in contacts.google.com or in `Contacts` for MSFT Outlook.

Just run jupyter notebook AddNewContacts.ipynb

and press 'yes' or 'no' followed by CR/LF (Enter key) when you'll be asked.
Input is email.txt which is parsed and output is 'contacts.csv' only after your confirmation (see above).

Generated vCard:
--------------------
BEGIN:VCARD
Full Name: Jane Doe
Position: Senior Account Executive
Work Place: Microsoft Training, Inc.
Email: jane.doe@microsoft.com
Phone: (904) 777-3333
Webpage: http://microsoft.com
END:VCARD
--------------------
