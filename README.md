## Speed-Tuned Portfolio 

### To run:
1. Download or clone repo
2. In the directory you've placed this, run 'Python -m SimpleHTTPServer [port]'
3. (Optional with ngrok) to make site publicly available, run 'ngrok [port]' and follow the URL provided

Steps taken:
* blocking JS & CSS moved outside of head
* CSS & JS minified
* Print css set to separate css file and called via media="print"
* pizza view css & js minified, mobile-friendly CSS & viewport added
* Pizza: added a requestAnimationFrame wrapper
* Pizza: runs updatePositions on scroll
* Pizza: resized image to exact dimensions
* Added evidence of all 90+ PageSpeed insights in root
* Added evidence of 60fps in console
* Hardware-accelerated "resize"

All pages score 92 or better (mobile & desktop) on page speed insights