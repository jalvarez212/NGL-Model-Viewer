# NGL-Model-Viewer
Framework for rendering atomic structures in 3D on the web. 

#Set-up

Webapp3.html calls ngl.js to load and render 3d model data in browser. ngl.js creates a canvas in <div id="viewport">


#Known Bugs
1) Canvas goes black on mobile after only a few seconds of inactivity. Visible on firefox/safari/chrome on MacOS. 
  a) I've tried using responsive css syntax to override. Doesn't seem to affect the canvas and viewport size. 

#Potential solution
1) writing script that listens for the window size after load and overrides HTML styles if window size width < 481px. 




#Citation

https://github.com/arose/ngl

AS Rose, AR Bradley, Y Valasatava, JM Duarte, A Prlić and PW Rose. NGL viewer: web-based molecular graphics for large complexes. Bioinformatics: bty419, 2018. doi:10.1093/bioinformatics/bty419

AS Rose and PW Hildebrand. NGL Viewer: a web application for molecular visualization. Nucl Acids Res (1 July 2015) 43 (W1): W576-W579 first published online April 29, 2015. doi:10.1093/nar/gkv402
