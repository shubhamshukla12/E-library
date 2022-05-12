# e_Library
Users and Authentication
There are two roles of users, librarian.

A librarian manages cataloging, and can assist circulation as well.
A patron is a customer of the library. He can search for books, borrow and returns books.
For simplicity, we allow any user with any email address to be able to create his account using an email as the username, and password of his choice. The user also needs to provide a university ID of 6 digits.
Your app must send an email to the user with a verification code. The user needs to use that verification code to complete his account registration. A registered user cannot really use features in the system until his account is verified. A confirmation email must be sent to the user after completion of account verification.
For simplicity, we only and automatically register any user with an SJSU email account (@sjsu.edu) to be a librarian. A librarian cannot be a patron, which means he has to use a different email to register if he needs a patron account as well.
No two patrons can have the same university ID, neither can two librarians.
