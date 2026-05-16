1. What is convolution?

Convolution is a process where a small filter (kernel) moves over an image to detect important features such as edges, patterns, textures, or shapes. It helps the CNN learn meaningful visual information from images.

2. Why is pooling used?

Pooling is used to reduce the size of feature maps generated after convolution. This makes the model faster, reduces memory usage, and helps prevent overfitting while keeping the most important features.

3. Why is ReLU commonly used in CNNs?

ReLU (Rectified Linear Unit) is an activation function that converts negative values to zero and keeps positive values unchanged. It helps the model learn non-linear patterns efficiently and speeds up training.

4. Why are CNNs better than regular feed-forward networks for image data?

CNNs are better for image data because they automatically detect spatial patterns like edges, textures, and shapes using convolution layers. Regular feed-forward networks treat every pixel independently, making them less efficient and requiring far more parameters.
