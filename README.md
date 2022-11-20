# AI-for-Facial-Recognisation-
This Model is used for facial attribute recognition/classification.



Introduction:

We encounter the applications of Facial Recognition in out day to day activities. Our cell phone uses Face ID to unlock, cameras give a small square highlighting the faces of human, used in social media etc. I like googles facial recognition where all the similar faces from our google photos will be collected and asks for their identity, after providing the identity the same will be updated in our contacts. 
This is a fascinating technology where the identification of faces is done by facial attributes like colour, shape, wears glasses or not, hair type etc. “As a typical classification problem, face attribute prediction has been addressed using deep learning. Current state-of-the-art performance was achieved by using two cascaded Convolutional Neural Networks (CNNs).” (Chen, Jenkins 2017)
In this module I would be attempting to train a deep neural network based on facial attributes like wrinkles, freckles, glasses, hair colour and hair top. This would be a stepping stone in understanding the how the above network works in a real world. In this network I would be feeding the neurons with images which will be annotated and try to predict the output by passing random images. 

The Model is to implement a ML solution for facial attribute recognition.
The facial attributes are:
- wrinkles (binary: has/does_not_have), class 0: does_not_have, class 1: has
- freakles (binary: has/does_not_have), class 0: does_not_have, class 1: has
- glasses (3 values: do_not_wear/wear_normal/wear_sunglasses), class 0:
does_not_wear, class 1: wear_ normal, class 2: wear_sunglasses
- hair_color (9 values: brown/black/gray/blond/red/white/mixed/other), class 0: brown,
class 1: black, class 2: gray, class 3: blond, class 4: red, class 5: white, class 6: mixed,
class 7: other, class 8: not_visible
- hair_top (4 values: bald or shaved, has_few_hair, has_thick_hair), class 0: bald or
shaved, class 1: has_few_hair, class 2: has_thick_hair, class 3: not_visible


