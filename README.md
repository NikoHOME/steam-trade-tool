# steam-trade-tool W.I.P

A simple terminal tool for trading tf2 items.

Currently avaible actions :
- url (creates a trade offer from a trade url)
- deal [keys] [metal] [my_items] : [client_items] (send a trade offer with specified items, keys and metal)
- exit (exits program)
- new (restart program)

## deal formating

- [keys] - ammount of keys the client will give, can be negative
- [metal] - ammount of metal the client will five, can be negative, **represented with refined metal fractions e.g. 12.33**
- [my_items] - list of your items with market names seperated by a space, **multiple words in an item name are seperated by an undersoce e.g. The_Jag**
- [:] - own item and client item seperator
- [client_items] - the same as above  
