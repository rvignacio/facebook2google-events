# facebook2google-events
## Mule Demo App
This is a mule sample app, just to test how integration between different connectors works.
## Use
 - Import and run the project in Mule ESB
 - Create a sample facebook app and a sample google calendar app (default redirect uri is _redirect_).
 - Go to /facebook-authorize and save the token id.
 - Go to /google-authorize and save the token id.
 - Go to /add-events?fbTokenId=_firstToken_&gTokenId=_secondToken_
