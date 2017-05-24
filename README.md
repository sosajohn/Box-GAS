# Box-GAS
Pull all users from Box and write the box user count and user list
into a Google Spreadsheet.  The spreadsheet must have two sheets.
One sheet must be called 'User Summary' and the other sheet must
be called 'User List'.  The Script is designed to be run nightly 
so that a user count over time can be kept as well as a current
user list.  See https://developer.box.com/v2.0/docs/authentication-with-jwt
for specifics on how Box JWT authentication works.
