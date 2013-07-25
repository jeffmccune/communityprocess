<!SLIDE>
# How the weekly summary works

Github Gist as a persistent data store!

 1. App reads a Liquid template from a raw github URL
 2. Collect all completed Trello cards
 3. Fill in the template with the card data
 4. Post the resulting Markdown back to the Gist

No persistent state in the app or the database.  Liquid template is easily
updated.
