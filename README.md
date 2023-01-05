# ANPR-System
This a code for the ANPR system using transfer learning techniques. I have used SSDmobile net for the project. Other files are not uploaded due to size issues you can contact me for other files.

The task for me was to build basically a model which will detect the Number plate region within an image. 

This is one of my replicated projects, which I need to deliver to a company.

# Notes :

I got the License Plate Dataset from the kaggle, it was already annotated. So, I need not to annotate it again.

For the object detection (here License Plate) I used Tensorflow Object Detection toolkit. 

The tutorial was there on YouTube. I here used the MobiNet Architecture basically, transfer learning approach. 

The workflow was same : Taining and then Applying the model on the test images.

The model worked fine

# Ignore these :

In the code you can see, I applied OCR techniques, but due to contrast and brightness those were not working well. You can ignore it.
I also have not worked much upon that because that was not my main task.

At last, you can see that I converted the model into a TFlite version, this was because I need to deliver it for the Pi use.
The OCR techniques will then be built for the same, by another team mate.
