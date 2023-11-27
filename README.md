This notebook is the submission towards the evaluative assignment of Engineer , Generative AI

Overview of the approach and the results achieved:
The Main aim is to Build a model that adapts to the style of the "Style Image" and then gives a stylized form of the input image as the output

I define two distances, one for the content
($D_C$) and one for the style ($D_S$).
$D_C$ measures how different the content
is between two images while ($D_S$) measures how different the style is
between two images. Then, I take a third image, the input, and
transform it to minimize both its content-distance with the
content-image and its style-distance with the style-image. Then I
import the necessary packages and begin the neural transfer.

The following two images are used:
Input Images
![dancing](https://github.com/Kishan-Pandey/NeuralStyleTransfer/assets/77564344/1e78555a-dafe-4807-ba92-857c04cbb2c6)

Style Image
![picasso](https://github.com/Kishan-Pandey/NeuralStyleTransfer/assets/77564344/530c661a-8355-41bd-a6cf-2f99b35be921)


