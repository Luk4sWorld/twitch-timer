# twitch-timer
a timer that counts up and can be reset via twitch chat  

## usage
simply point an url to index.html for example as an OBS browser source.  
the string after the '#' hash sign contains the settings encoded as URI parameters.  

## configuration
current settings supported:
* channel: the channel it shall listen on.
* command: the string it shall search for to reset the timer
* font: the font family for the text (be ware of URI encoding, hash string will try to decode)
* size: the font size (a CSS compatible value like "40px")

## example
(WIP)  
`Luk4sWorld.github.io/twitch-timer/index.html#channel=Luk4sWorld&command=!reset&font=Comic%20Sans%20MS&size=40px`  
