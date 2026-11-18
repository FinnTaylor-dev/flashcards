# A level flashcards

Navigate to relevant folder
Then run:

```bash
hashcards drill .
```

To practise a specfic file use

```bash
hashcards drill --from-deck=<NAME>
```
Options:

    --card-limit=<N>: Limit the session to at most N cards.
    --new-card-limit=<N>: Limit the number of new cards in the session.
    --host=<HOST>: Bind the web server to a specific host address (default: 127.0.0.1).
    --port=<PORT>: Use a specific port (default: 8000).
    --resource-hostname=<HOSTNAME>: Use a specific hostname when rewriting linked media resource URLs (default: localhost).
    --from-deck=<NAME>: Only drill cards from a deck with the given name.
    --open-browser=<true|false>: Whether or not to open the browser after the server starts (default: true).

