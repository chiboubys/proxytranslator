# proxytranslator
a translator application build with java and swing. each language dictionary stored in a server and the directions to this server handled by a proxy server (UDP protocol)

Schema : 

1. **Client** ----> Chosing : Source Language & Destination Language.
1. **CLient** ----> Translator App (Enter the Word to translate).
1.                           **App** -> **Proxy** -> Send the word to be translated to the destination server.
1.**Client** <----Result---- **App** <- **Proxy** <- Result | error <- Destination Server.

