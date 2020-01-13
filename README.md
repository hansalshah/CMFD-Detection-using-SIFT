# Copy-Move Forgery Detection using SIFT and GLCM-based Texture Analysis

Repo for the paper (https://ieeexplore.ieee.org/abstract/document/8929276)

The main contribution of this paper lies in improving the accuracy of the model when there are Similar but Genuine Objects (SGO) present in the scene. Unlike previous methods, addition to GLCM based textural analysis helps eliminate these False detections and thus improves accuracy.

Below is such an example where both images are output from our algorithm:

The left image has is the case of an image having SGO and the algorithm correctly doesn't classify any forgeries in it but the right picture is actually forged and the algorithm successfully detects the forged objects in the image.

<img align="left" src="https://github.com/hansalshah/CMFD-Detection-using-SIFT/blob/master/Images/sgo_cup.png">
<img align="right" src="https://github.com/hansalshah/CMFD-Detection-using-SIFT/blob/master/Images/tampered_cup.png"><br>


<br/><br/><br/><br/><be/><br/><br/><br/>NOTE: The initial code has been adapted from the implementation of “A sift-based forensic method for copymove attack detection and transformation recovery” by Amerini et al.
