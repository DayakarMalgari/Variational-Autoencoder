# Variational-Autoencoder
Variational Autoencoder to Reconstruct input and Generate new images

Variational Autoencoder to reconstruct (or generate) images from latent space

Resolution of the reconstructed images is 256x256

Manipulated latent vector values to generate new images with variation

20 cat images and 20 dog images (both repeated 5 times) and split as training and validation data

Loss(MSE) has been reduced to less than 0.00026 for reconstructed images

Original and Reconstructed (with no changes to latent variables) or Generated (with changes to latent variables) images plotted side-by-side

Image to image translation such as cat to dog, dog to cat, colored to black, white to colored, cat to human and other translations demostrated (plotted)

Several new images plotted to show the noise, blurriness and faded color in generated images with respect to mean and standard deviation.

## Variations after increasing all latent variable values by 25%. As you see, there is a drop in resolution of the image and increase in noise.

![Generated_with_25%_changes_to_latent_space](https://user-images.githubusercontent.com/88380811/138744039-fc1a1bb2-3dc4-4060-9780-f4154723e761.png)



## Top left corner image is the only original image, rest all generated. Bottom right corner image is with maximum mean and standard deviation 

![cat1_variations](https://user-images.githubusercontent.com/88380811/138751403-d485c94b-88af-4d5b-a3e4-03e3a9bad861.png)

## Top left corner cat image and bottom right corner girl image are original. Rest all created for image-to-image translation.

![cat_to_human_translation](https://user-images.githubusercontent.com/88380811/138750501-ec8ee947-a231-4ee5-b00a-fb388ff78f5e.png)

## Dog to cat translation with low mean and high standard deviation. 

 ![dog_to_cat_with_low_mean_high_std](https://user-images.githubusercontent.com/88380811/138749341-3280bb7a-90a3-49d7-8d2f-cfd168dc8987.png)

## Cat to dog translation with high mean and low standard deviation.

![cat_to_dog_with_high_mean_low_std](https://user-images.githubusercontent.com/88380811/138749853-fc4620b9-b483-4035-b92c-ad8a7523d752.png)











