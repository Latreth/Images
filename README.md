# Projet de M1 Digital Geometry / Computational Geometry / Image Processing


Ce projet réalisé en python3 est l'implémentation de [cet algorithme](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/criminisi_cvpr2003.pdf)

Nous utilisons la librairie OpenCV et Numpy.

Si vous voulez réaliser vos propres tests le masque doit être blanc et noir, où la zone noire est la zone a cacher.



## Compiler avec une taille de masque prédéfinie à trois:

### python3 inpainting.py image masque

ou

### ./inpainting.py image masque
(Cependant dans ce cas la, il faut faire :
  sudo chmod +x inpainting.py)


## Compiler avec votre propre taille de masque (attention plus la taille du masque est grande moins l'algorithme sera efficace):

### python3 inpainting.py image masque nb_de_pixel_dans_le_masque

par ex :
python3 inpainting.py test.png masque.png 5

ou

### ./inpainting.py image masque nb_de_pixel_dans_le_masque
