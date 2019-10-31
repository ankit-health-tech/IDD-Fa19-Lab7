# Video Doorbell, Lab 7

*A lab report by Ankit M.*

### In This Report

1. Upload a video of your version of the camera lab to your lab Github repository
1. As usual, update your class Hub repository to add your [forked IDD-Fa18-Lab7](/FAR-Lab/IDD-Fa18-Lab7) repository.
1. Answer the questions in-line below on your README.md.

## Part A. HelloYou from the Raspberry Pi

**a. Link to a video of your HelloYou sketch running.**

Video of the running Hello You sketch is encloser here(https://youtu.be/0x6_zI6HwPg)

## Part B. Web Camera

**a. Compare `helloYou/server.js` and `IDD-Fa18-Lab7/pictureServer.js`. What elements had to be added or changed to enable the web camera? (Hint: It might be good to know that there is a UNIX command called `diff` that compares files.)**

The snippet below controls taking the picture. Other than this ofcourse since the picture needs to be stored its naming structure is encoded in a separate snippet of code.

Relevant snippet: <br>
"
 //Third, the picture is  taken and saved to the `public/` folder
>     NodeWebcam.capture('public/'+imageName, opts, function( err, data ) {
>     io.emit('newPicture',(imageName+'.jpg')); ///Lastly, the new name is send to the client web browser.
>     /// The browser will take this new name and load the picture from the public folder.
>   });

"
**b. Include a video of your working video doorbell**

Link to the working doorbell(https://youtu.be/jLDjTjOOZrA)

## Part C. Make it your own

**a. Find, install, and try out a node-based library and try to incorporate into your lab. Document your successes and failures (totally okay!) for your writeup. This will help others in class figure out cool new tools and capabilities.**

**b. Upload a video of your working modified project**
