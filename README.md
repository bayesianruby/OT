# Unmixing-with-Optimal-Transport


The goal of this project is to make a music transcription algorithm. The typical measures of fit used to
quantify the adequacy of the decomposition compare the data and template entries
frequency-wise. Building on the harmonic nature of sound, the new measure is 
invariant to shifts of energy to harmonically-related frequencies, as well as to small and local displacements of energy. Equipped
with this new measure of fit, the dictionary of note templates can be considerably simplified to a set of Dirac
vectors located at the target fundamental frequencies (musical pitch values).

In concrete terms, the aim is to move from the first spectrum to the second as shown below:

![téléchargement](https://user-images.githubusercontent.com/80846462/174449144-966e4a92-cbc6-4ef5-83d1-8cdec73a7582.png)
![téléchargement (1)](https://user-images.githubusercontent.com/80846462/174449146-eee6d297-960f-48c0-a943-b893cd4f2358.png)


This project is inspired by the following paper :

Rémi Flamary, Cédric Févotte, Nicolas Courty, Valentin Emiya. Optimal spectral transportation with application to music transcription. Advances in Neural Information Processing Systems (NIPS), Dec 2016, Barcelona, Spain.
