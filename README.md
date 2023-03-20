### CLIENT FLOW
* Enter channel with or without invoice/id
* Get message from bot / enter verification room
* Give invoice/id
* Receive accept/deny message
* Receieve message mentioning admins / help
* Receieve roles / permissions / nicknames

### BOT FLOW
* Check for invoice/id submit
* When msg, check database for invoice/id
* If valid, send accept/deny msg
* Give roles / permissions


### DATABASE
>ENTRIES CAN BE ADDED BY API OR MANUALLY
* id (invoice / api)
* username
* added_date
* expiry_date
* product


