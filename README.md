# google_id_tracker
Location tracking using Google Authenticator ID


## Steps
1. Go to https://docs.google.com/document/
2. Create a document
3. Click share and then click inspect element (Network Tab)
4. Add a user with any email address. **Don't send the invite**
5. Check the Network tab and inspect the network request for Fetch/XHR and search 'lookup'
6. Scroll to the bottom and copy the 'X-Goog-Api-Key', also copy the autherisation: SAPISIDHASH (Headers tab)
7. Edit the tampermonkey script in the files with the 'X-Goog-Api-Key' and SAPISIDHASH near the top of the file.
8. **Don't share these to anyone**
9. Then go to https://clients6.google.com
10. Type in the email address
11. Now you can go to google maps at https://www.google.com/maps/contrib/1234567/reviews Replace the number on the end with the extracted number from the email.


### Credits
Thanks to https://github.com/pentestfunctions being the first person I seen do this.
