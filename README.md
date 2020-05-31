# proxytranslator
a translator application build with java and swing. each language dictionary stored in a server and the directions to this server handled by a proxy server (UDP protocol)

Schema : 
1. Client ----> Chosing : Source Language & Destination Language
2. CLient ----> Translator App (Enter the Word to translate) 
3.                       (App) -> Proxy -> Searching for the destination server and send the word to be translated to it.
4.Client <----Result---- (App) <- Proxy <- Result | error <- Destination Server
