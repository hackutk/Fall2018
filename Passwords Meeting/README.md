# Workshop
### The Scenario
You have obtained the database dump of a website with ~20 development accounts. The dump contains 60,000+ encrypted values from random columns in the table. However, you have insider information that all **passwords** from this website are hashed using **SHA256**, and the admin is notorious for using common passwords.
### Your Job
Given this data dump, determine a way to filter out all fields except for the password hashes. Once you have obtained this list of hashed passwords, use a Rainbow Table or something similiar (such as [this](https://crackstation.net/), to crack the admin's password.
