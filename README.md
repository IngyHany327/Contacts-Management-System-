# Contacts-Management-System-
Contact Management System
Functionality
Contact Creation and Management:

Users can create and manage contacts by specifying details such as name, phone number, email, and address.
Contacts can be categorized as Friend or Work.
Friend contacts include additional details like birthdays, while work contacts include job titles.
Contact Modification:

Contacts can be updated by modifying their details like phone number, email, or address.
Specific categories (Friend or Work) allow editing their unique attributes, such as updating birthdays or job titles.
Contact Categories
Friend Contacts:

Includes attributes such as name, phone number, email, address, and birthday.
Useful for personal relationships.
Work Contacts:

Includes attributes such as name, phone number, email, address, and job title.
Tailored for professional connections.
Error Handling and Validation
Validation Mechanisms:

Ensures proper input formats, such as valid email addresses and non-empty names.
Prevents adding duplicate contacts based on the name and phone number.
Robust Error Handling:

Handles cases where users attempt to update or delete nonexistent contacts.
Ensures that empty fields during contact creation are flagged appropriately.
Duplicate Prevention:

The system avoids duplicate contacts by validating unique identifiers like phone numbers.
Scalability and Maintenance
Modular Design:

Separate classes for contacts (Contact, FriendContact, and WorkContact) and a manager class (ContactManager) for managing them.
Simplifies debugging, testing, and future feature additions.
Extensibility:

Easy to add new contact categories or additional attributes, such as social media handles.
Performance Optimization:

Efficient algorithms for searching, sorting, and managing contacts in large datasets.
Testing and Validation
Unit Testing:

Each class and its methods are tested independently to ensure proper functionality.
Integration Testing:

Validates interactions between components, such as linking the ContactManager with FriendContact and WorkContact.
User Acceptance Testing (UAT):

Verifies the system’s usability and reliability with input from end-users.
General Flow
Contact Creation:

Users create contacts by selecting a category (Friend or Work) and filling in the required fields.
Viewing Contacts:

Contacts are displayed in a sorted manner, either by name or by category.
Contact Modification:

Existing contacts can be searched by name and updated with new details.
Contact Deletion:

Users can remove unwanted contacts based on their name.
Future Enhancements
Social Media Integration:

Add fields for storing social media handles and links for each contact.
Search Filters:

Enable advanced search options like filtering contacts by categories or specific attributes.
Data Backup and Export:

Provide functionality to export contacts to CSV or JSON formats for backup and sharing.
Mobile Integration:

Extend the system to mobile platforms for better accessibility and usability.
The Contact Management System is a reliable, user-friendly application designed for managing personal and professional connections effectively. It emphasizes flexibility, scalability, and ease of use.
