# Chris Hansenify

A simple Javascript bookmarklet that displays a stern looking Chris Hansen, former host of MSNBC's *To Catch A Predator*, on the left side of your browser screen. If you find yourself viewing questionable content online, simply click the bookmarklet and "have a seat over there."


Try it out by saving the following as a bookmark and clicking on it:

`javascript:(function()%7Bchrishansenify%3D%22%3Cimg%20src%3D%27https://lh3.ggpht.com/-0xToZLlI3Eo/Tgx1Bj9m9sI/AAAAAAAAI78/AyEFs0OkJkw/s1600/chris_hansen.gif%27%20width%3D%27%25%27%20height%3D%27%25%27%3E%3C/a%3E%22%3Bvar%20div_popup%3Bdiv_popup%3Ddocument.createElement(%27div%27)%3Bdiv_popup.innerHTML%3Dchrishansenify%3Bdiv_popup.setAttribute(%22style%22,%22position:fixed%3Bz-index:1000%3Btop:-10px%3Bright:0px%3Bwidth:100%25%3Bheight:100%25%3B%22)%3Bdocument.getElementsByTagName(%22body%22)%5B0%5D.appendChild(div_popup)%3B%7D)()%3B`