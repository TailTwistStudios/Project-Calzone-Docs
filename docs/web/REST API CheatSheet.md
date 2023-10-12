# REST API CheatSheet
A quick reference guide to all the REST API calls currently available.

## World Map (Mock-up)
- **GET** `/worldmap` Returns the current instance World Map as a JSON object.


## Sessions
**Important Note:** The session list is being constantly maintained, but maintained each time it needs to be accessed. Routes that retrieve a list of sessions will also trigger a purge of stale/abandoned sessions from the list itself, even if those entries were not requested.

- **GET** `/sessions` Returns a sanitized list of the currently running game sessions. *Causes a list refresh.*
- **POST** `/registersession` Accepts self-reported metadata about a session from a user on this instance. 
    
    *Requires:* `hostusername`, `hostIPv4`, `worldID`, `visibility`
    
    *Returns:* `checkIn`, `sessionID`, `sessionOwnerKey`, `sessionKeepAliveTime`

- **POST** `/checkinsession` Used by a session host to keep their session listing alive. 

    *Requires:* `sessionID`, `sessionOwnerKey`

- **POST** `/closesession` Used by a session host to manually remove their session. It's exptected that a game manually inform the webserver that a session has closed (if possible). 

    *Requires:* `sessionID`, `sessionOwnerKey`
    