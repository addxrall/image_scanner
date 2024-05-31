Simple document scanner that uses opencv.

how does it work?

Well, at the beggining it tries to detect edges (edged window on screenshots) of paper/document then uses the edges to find the contour (Outline window on screnshots) and in the end it applies perspective to emulate top-down view. 

sometimes it gets weird output when background and text on paper is not dark enough.

![image](https://github.com/addxrall/image_scanner/assets/50717284/112f1c54-7c5d-4824-9d7b-bc38e6379c6e)

![image](https://github.com/addxrall/image_scanner/assets/50717284/b9e6d96c-340c-4f00-b927-bca77f93b0b0)
