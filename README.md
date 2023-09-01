# PhoneBook
Description- This Phonebook Web Application id created to efficiently manage large no of contacts. 
It has a helpful feature you've probably seen on many websites before – Auto Suggestion. 
Even though it's common, I have made it super easy to use.
With this feature, when you start typing a phone number, it'll suggest contacts, just like you've seen elsewhere. 
This makes it a breeze to find and manage your contacts, making your life simpler and more organized.

# Key Features-
- # Auto Suggestion:

1. Auto suggestion is a common feature in many web applications and is particularly useful in a phonebook application.
2. It provides real-time suggestions as users type in a phone number, helping them find contacts quickly without needing to type the entire number.
3. The implementation of this feature is likely based on a Trie data structure, which is an efficient way to store and search for strings (in this case, phone numbers) with a common prefix.

- # Duplicate Phone Number Prevention:
1. The Trie data structure is utilized to ensure that there are no duplicate phone numbers in the phonebook.
2. When a new contact is added or an existing one is updated, the application likely checks the Trie data structure to see if the phone number already exists.
3. This feature helps maintain data integrity and prevents users from accidentally adding the same phone number multiple times.

- # Invalid Phone Number Validation:
1. The application checks for invalid phone numbers and prevents their insertion. This is crucial for ensuring that only valid and formatted phone numbers are added to the phonebook.
2. Validating phone numbers can help avoid issues with incorrect or improperly formatted numbers that could cause problems when trying to contact someone.

- # Sorting Contacts:
1. The Trie data structure is used for sorting contacts based on their phone numbers.
2. Sorting contacts based on phone numbers can make it easier to find and manage them. Users can quickly locate a contact by searching for their phone number or by browsing through the list in a sorted order.

Auto-Suggestion feature-
![Screenshot 2023-09-01 203811](https://github.com/amangour7909/Phonebook/assets/127648041/604a9e89-6ae5-43ff-93ef-20e1362b6835)

Calling on clicking contact-
![Screenshot 2023-09-01 203838](https://github.com/amangour7909/Phonebook/assets/127648041/1939c306-cf3a-444e-bfce-b00b6122e3b1)

Insert contacts in sorted order-
![Screenshot 2023-09-01 203644](https://github.com/amangour7909/Phonebook/assets/127648041/f1dd36d7-4e3a-4eb3-8ed7-59e35e354f99)

Phone no validation-
![Screenshot 2023-09-01 210322](https://github.com/amangour7909/Phonebook/assets/127648041/9a477562-5a50-4894-937c-63366f8dfd07)


Duplicate phone number check-
![Screenshot 2023-09-01 203731](https://github.com/amangour7909/Phonebook/assets/127648041/15a2102a-7662-4e02-8bba-75322806f118)
