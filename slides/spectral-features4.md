##  Spectral Features

<p class="fragment fade-up">We can build **a graph from pixels in images** with the weights between pixels decided by a function, `$w_{ij}(I_i, I_j, \mathbf{x_i}, \mathbf{x_j})$` </p>

<p class="fragment fade-up" style="text-align: center">Example over images, `$\quad w_{ij} = \frac{1}{(\mathbf{x_i}-\mathbf{x_j})^2}e^{\frac{(I_i-I_j)^2}{\sigma^2}}$`

<img class="plain"  src="resources/features_lena.png" width=75%/></p>
