HTML5 Canvas Tests with Kineticjs
=================================

Code is based on tutorial: http://www.html5canvastutorials.com/labs/html5-canvas-drag-and-drop-resize-and-invert-images/
And code example:
http://jsbin.com/abejab/3/edit#source


Features to test
----------------
- Drag image from computer
- Drag image from another website
- Drag image from same website
- Click image from same website
- Resize
- Rotate
- Delete
- Flip (x axis)
- Multiple images from different sources
- Canvas size based on first image added
- Canvas download
- Browser detection


Currently working
-----------------
- Drag image from computer
- Click image from same website
- Multiple images from different sources
- Resize
- Rotate
- Delete (double click)
- Flip
- Canvas size based on first image added (dragged only)


Currently broken
----------------
- Multiple rotate/resize/flip changes causes jumpiness


Notes
-----
- First image dragged to canvas becomes the background; it wipes anything currently on the canvas, and resizes the canvas to the image size (resized if goes over a max width and height)