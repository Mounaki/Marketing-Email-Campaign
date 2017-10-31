# Marketing-Email-Campaign


Goal

Optimizing marketing campaigns is one of the most common data science tasks. Among the many possible marketing tools, one of the most 
efficient is using emails.
Emails are great cause they are free and can be easily personalized. Email optimization involves personalizing the text and/or the subject, who should receive it, when should be sent, etc. Machine Learning excels at this.

Challenge Description

The marketing team of an e-commerce site has launched an email campaign. This site has email addresses from all the users who created an account in the past.
They have chosen a random sample of users and emailed them. The email let the user know about a new feature implemented on the site. From the marketing team perspective, a success is if the user clicks on the link inside of the email. This link takes the user to the company site.

Data

The 3 tables are:

Email_table - info about each email that was sent

Columns:

email_id : the Id of the email that was sent. It is unique by email
email_text : there are two versions of the email: one has "long text" (i.e. has 4
paragraphs) and one has "short text" (just 2 paragraphs)
email_version : some emails were "personalized" (i.e. they had the name of the user
receiving the email in the incipit, such as "Hi John,"), while some emails were
"generic" (the incipit was just "Hi,").
hour : the user local time when the email was sent.
weekday : the day when the email was sent.
user_country : the country where the user receiving the email was based. It comes from
the user ip address when she created the account.
user_past_purchases : how many items in the past were bought by the user receiving
the email


Email_opened_table - the id of the emails that were opened at least once.

Columns:

email_id : the id of the emails that were opened, i.e. the user clicked on the email and, supposedly, read it.

Link_clicked_table - the id of the emails whose link inside was clicked at least once. This user was then brought to the site.

Columns:

email_id : if the user clicked on the link within the email, then the id of the email shows
up on this table.
