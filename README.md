# Neural-Style-Transfer
This project uses Neural Style Transfer algorithms to recreate content pictures with respect to different painting styles.
The following project is conducted based on Leon A. Gatys et al. (2015) A Neural Algorithm of Artistic Style https://arxiv.org/abs/1508.06576.
With genuine respect to the original papers, I took the liberty to rewrite the algorithms with respect to the mathematical formulations and use InceptionV3 architecture instead of original VGG19 which was mentioned in the paper.

Moreover, additional information are provided below:

  - Image size : (1200, 1200, 3)
  - Pre-trained network : InceptionV3 
  - Weights : Imagenet
  - Content layer : "conv2d_93"
  - Style layers :
  -    - ('conv2d_64', 0.1),
  -    - ('conv2d_65', 0.1),
  -    - ('conv2d_66', 0.1),
  -    - ('conv2d_67', 0.1),
  -    - ('conv2d_68', 0.1),
  -    - ('conv2d_69', 0.1),
  -    - ('conv2d_70', 0.1),
  -    - ('conv2d_71', 0.1),
  -    - ('conv2d_72', 0.1),
  -    - ('conv2d_73', 0.1)
  
Also, in addition to the main algorithm provided in .ipynb format (notebook), there is another directory namely, Pictures including 4 subdirectories namely, Content, Style, Output, and Result.

Content directory : Consists of different content pictures.

Style directory : Consists of different Styles of paintings (Cubism, Expressionism, etc.).

Output directory : Consists of different steps of the transformations.

Result directory : Consists of final result after the transformations.

Note that due to computational expensivity, I have not tried multiple example and only changed the style of a bridge into post-impressionism style of the Starry Night by Vincent Van Gogh.
I am looking forward to try this algorithm with various architectures in search of better outcomes.

Please, feel free to modify the layers or  even the architecture and use your own images for more thrilling personal experiences.


