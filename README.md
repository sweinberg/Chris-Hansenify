# Chris Hansenify

**Chris Hansenify** is a simple Javascript bookmarklet that displays a stern looking Chris Hansen, former host of MSNBC's *To Catch A Predator*, on the left side of your browser screen. If you find yourself viewing questionable content online, simply click the bookmarklet and "have a seat over there."


**Note:** try it out by dragging the "Chris Hansenify" button to your bookmarks bar.

[![Chris Hansenify][2]][1]

  [1]: javascript:(function()%7Bchrishansenify%3D%22%3Ca%20href%3D%27javascript:(function()%7Bdocument.getElementById(%5C%22glasses%5C%22).style.display%3D%5C%22none%5C%22%3Breturn%7D)()%3B%27%3E%3Cimg%20src%3D%27https://lh3.ggpht.com/-0xToZLlI3Eo/Tgx1Bj9m9sI/AAAAAAAAI78/AyEFs0OkJkw/s1600/chris_hansen.gif%27%20width%3D%27%25%27%20height%3D%27%25%27%3E%3C/a%3E%22%3Bvar%20div_popup%3Bdiv_popup%3Ddocument.createElement(%27div%27)%3Bdiv_popup.innerHTML%3Dchrishansenify%3Bdiv_popup.id%3D%22glasses%22%3Bdiv_popup.setAttribute(%22style%22,%22position:fixed%3Bz-index:1000%3Btop:-10px%3Bright:0px%3Bwidth:100%25%3Bheight:100%25%3B%22)%3Bdocument.getElementsByTagName(%22body%22)%5B0%5D.appendChild(div_popup)%3B%7D)()%3B
  [2]: https://s3.amazonaws.com/f.cl.ly/items/390R3u2Y1Z3s1w0p2r0N/chrishansenify.png (hover text)

***
#License

Feel free to modify, distribute, and play around with this code. No attribution required.