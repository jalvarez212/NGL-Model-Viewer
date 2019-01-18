# NGL-Model-Viewer
Framework for rendering atomic structures in 3D on the web. 


#Known Bugs
1) Canvas goes black on mobile after only a few seconds of inactivity. Visible on firefox/safari/chrome on MacOS. 
  a) I've tried using responsive css syntax to override. Doesn't seem to affect the canvas and viewport size. 

#Potential solution
1) writing script that listens for the window size after load and overrides HTML styles if window size width < 481px. 

