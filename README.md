# Custom_Face_Recognition
*This repository contains code for a custom face recognition implemented in python. Using the code in this repository, one can create a 
face recognition system having eye blink detector as an anti-spoofing method, that prevents a photo to be used as a measure to detect a
face.*

This code can be used to create a software as well as a hardware implementation to create a face recognition unlocking system.
<table>
  <tr>
    <td align="center"><a href="https://unsplash.com/photos/8PMvB4VyVXA"><img src="https://images.unsplash.com/photo-1541647376583-8934aaf3448a?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=334&q=80" width="350"" alt="Source"/><br /><sub><i>Source</i></sub></a></td>
    <td align="center"><a href="https://unsplash.com/photos/BGz8vO3pK8k"><img src="https://images.unsplash.com/photo-1464863979621-258859e62245?ixlib=rb-1.2.1&auto=format&fit=crop&w=333&q=80" width="350" alt="Source"/><br /><sub><i>Source</i></sub></a></td>
    </tr>
 </table>


## Steps Involved
Run the files preferably on the command line.
* Run ```pip install -r requirements.txt``` to install all required libraries. *Check out <a href="https://medium.com/@boscacci/why-and-how-to-make-a-requirements-txt-f329c685181e">this article</a>
to know more about requirements.txt.*

* Run ```python face_store_data.py```. Input the name of the person of whom you are creating the dataset of images.
Now, with the face recognition window as the active window, use key 'k' to cature your image when the camera recognizes your face. After
capturing a good amount of photos, use key 'q' to exit.<br>
***Advice**: The more images the better :camera:. Try to click atleast 50 to get a good recognition system. Also, if your camera doesn't
recognize your face, invest in a better camera :stuck_out_tongue:*
* Run ```python train.py```. Sit tight for a few seconds :coffee:

* Run ```python final_code.py``` and VOILA! you have your own face recognition system.

A special thanks to https://pyimagesearch.com. Their website helped a lot. Do check out their website for
many more awesome projects.
