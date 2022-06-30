# Image-Colorization
In this project I have used conditional GAN to implement image colorization. During the training the input RGB images is converted into LGB space and the L channels acts like the grey image input to the generator . The generator then produces the A and B channels which when concentrated with the original L channel are sent to the patch discriminator. The patch discriminator outputs a score for each patch, telling wheather it's real or not and thus helps the generator to learn.

