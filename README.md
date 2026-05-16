1. What is convolution?

Convolution is a process where a small filter (kernel) moves over an image to detect important features such as edges, patterns, textures, or shapes. It helps the CNN learn meaningful visual information from images.

2. Why is pooling used?

Pooling is used to reduce the size of feature maps generated after convolution. This makes the model faster, reduces memory usage, and helps prevent overfitting while keeping the most important features.

3. Why is ReLU commonly used in CNNs?

ReLU (Rectified Linear Unit) is an activation function that converts negative values to zero and keeps positive values unchanged. It helps the model learn non-linear patterns efficiently and speeds up training.

4. Why are CNNs better than regular feed-forward networks for image data?

CNNs are better for image data because they automatically detect spatial patterns like edges, textures, and shapes using convolution layers. Regular feed-forward networks treat every pixel independently, making them less efficient and requiring far more parameters.


Task 7: Business Use Case Mapping
Manufacturing Quality Inspection

This computer vision solution can be used in the manufacturing industry for automated quality inspection of products.

In factories, products may develop defects such as scratches, dents, stains, or other surface damage during production. A CNN-based image classification system can automatically analyze product images and identify defective items in real time.

This helps manufacturers:

Reduce manual inspection effort
Improve inspection speed and accuracy
Detect defects early in the production process
Reduce production losses and waste
Maintain consistent product quality

Such systems are commonly used in automobile manufacturing, electronics production, metal surface inspection, and packaging industries.
