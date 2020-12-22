<h2>Paper.</h2>
 https://arxiv.org/pdf/1312.6114.pdf

<h2> Variational AutoEncoder. </h2>
VAE is an autoencoder whose encodings distribution is regularised during the training in order to ensure that its latent space has good properties allowing us to generate some new data. Moreover, the term “variational” comes from the close relation there is between the regularisation and the variational inference method in statistics.
<h2> Installation.</h2>
 <ul>
  <li> tensorflow==2.2.0 </li>
  <li> Python==3.6.6 </li> 
  </ul>
<h2> Code structure. </h2>
All the code is written is <b>vae.ipynb file</b>. And only train for one epoch.
<h2> Dataset. </h2>
The dataset used is mnist dataset. Which was already present in tensorflow examples.
<h2> Loss </h2> 
I use two type of loss as mentioned in the paper of variational auto encoder. 
 <ul>
 <li> KL divergence Loss. </li>
 <li> Marginal Likelihood. </li>
 </ul>
 <h2>Contribute. </h2>
 Feel free to check out the code, and contribute as well as point out if their is any problem.
 
