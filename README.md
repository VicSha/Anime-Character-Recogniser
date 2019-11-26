# Anime-Character-Recogniser<br/>
This isn't perfect.... so don't expect it to be <br/>

# Usage <br/>
Two seperate files. <br/> 
"Webcam" requires you to allow access to webcam and then you can put a picture up in front of it or something like that <br/>
"File" allows you to set the image src in the html file to a *locally stored* image. Trying to use a url will most likely run into issues <br/>
You also should for "File" host the html file and image on a local server then connect through your browser using <br/>http://localhost:(PORT)/index(File).html <br/>


# Model trained using teachablemachine<br/>
Current Characters trained:<br/>
-Lelouch Lamperouge (35 Images)<br/>
-Edward Elric (36 Images)<br/>
-L Lawliet (32 Images)<br/>
-Naruto Uzumaki (43 Images)<br/> 
-Ken Kaneki (31 Images)<br/>
-Taiga Aisaka (31 Images)<br/>
-Megumin (33 Images)<br/>
-Kazuto Kirigaya (27 Images)<br/>
-Asuna Yuuki (24 Images)<br/>
-C.C. (29 Images)<br/>
-Konata Izumi (42 Images)<br/>
-Holo (23 Images)<br/>

Epochs:500 (Higher than neccessary) <br/>
Batch Size:32 <br/>
Learning Rate: 0.001 <br/>

If you'd like to help adding extra characters or adding more image samples to sets already there, feel free to do so using the issues tab and labeling your issue as "enhancement" or whatever it may be
