# ImageCompression

Converting an image to its DFT representation, we can compress images by dropping (setting to 0) signals of the DFT that are less than a specified tolerance. As a result, this "drop ratio" corresponds to image compression, as we don't need to store pixels that we set to zero.

## Usage
Run the notebook. You can replace `operahall.png` with any other image, ensuring that it is a **square image, dimensions of multiple 32**, e.g. 512x512.

The final plot is an error plot, which illustratively shows which values were dropped in a specified compression.

The pdf also shows the result of running the ImageCompression DFT algorithm on the `operahall.png` example.