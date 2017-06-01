# Jquery-Tutorial
Jquery Tutorial (Easy Notes)


Welcome To My Tutorials
_______________________

This is my tutorial notes for jquery. Whenever I need something to use about jquery, I can download anytime from my account of github. This is github's strong point.

01. Loading Function

HTML >> "<img class="img-responsive jquery_logo" src="jquery.png" alt="" />""

JS >> $('.jquery_logo').load(function(){
	 alert('Image is loading')
     });

** When you refresh the browser, the alert box will appear. But images is already loaded..

   * It doesn't work consistently nor reliably cross-browser
   * It doesn't fire correctly in WebKit if the image src is set to the same src as before
   * It doesn't correctly bubble up the DOM tree
   * Can cease to fire for images that already live in the browser's cache
