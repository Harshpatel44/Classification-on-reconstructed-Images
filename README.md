<h2>Classification-on-reconstructed-Images</h2>
<p>The project was about classifying MNIST data of low dimensions. After de-noising the reconstructed images using auto-encoders, I classified them using convolutional network and evaluated the performance. The images were reconstructed using PCA.</p>

<h3>In this notebook, We do as the following</h3>
<p>1. Prepare the MNIST dataset</p>
<p>2. Apply dimensionality reduction on the dataset using PCA ( variance = 0.90 )</p>
<p>3. Reconstruct the data from PCA ( the reconstructed data is noisy images )</p>
<p>4. Denoise the images using autoencoders</p>
<p>5. Train and test the denoised images on CNN model and evaluate the results.</p>
<p>6. Now, again apply dimensionality reduction using PCA with variance=0.50 and evaluate the resuls after training with CNN model.</p>

<h3>Results</h3>
<p>Training Accuracy on PCA (variance = 0.90) = 98% </p>
<p>Training Accuracy on PCA (variance = 0.50) = 95% </p>

<h3>Developers</h3>
<p><i>Harsh Patel</i></p>
