#### Author: Vincent Yeo

### Image Recognition with Fashion MNIST dataset

#### Background:

Fashion e-commerce has grown to lucrative business, driven by the accessibility of internet into the global market, connecting wholesalers and consumers via browser. Combined with search engines and mobile devices, e-commerce platform can drives the sales further by allowing consumers to search for products by uploading images of the desired items, taken from their smart phones. Thus, a model to recognise images of clothing would be useful for ecommerce to deliver their service to consumers better to drive sales.

#### Dataset:
The Fashion MNIST serves as a replacement for the MNIST dataset as benchmark for machine learning algorithms. It contains the similar 28x28 grayscale images associated with 10 classes of objects. 

#### Task: 

To build a Convolutional Neural Network (CNN) to classify 10 categories of fashion items from their images

#### Results & Analysis
Model achieves 80.73% on unseen test data

Based on each precision score, the model's prediction would be realised truely for

+ the `T-shirt/top`, 80% of the time.
+ the `Trouser`, 97% of the time.
+ the `Pullover`, 76% of the time.
+ the `Dress`, 82% of the time.
+ the `Coat`, 58% of the time.
+ the `Sandal`, 93% of the time.
+ the `Shirt`, 55% of the time.
+ the `Sneaker`, 89% of the time.
+ the `Bag`, 94% of the time.
+ the `Ankle Boot`, 90% of the time.

Based on each recall score, the model's prediction for

+ the `T-shirt/top` has about 74% being correct.
+ the `Trouser` has about 95% being correct.
+ the `Pullover` has about 58% being correct.
+ the `Dress` has about 83% being correct.
+ the `Coat` has about 83% being correct.
+ the `Sandal` has about 90% being correct.
+ the `Shirt` has about 50% being correct.
+ the `Sneaker` has about 90% being correct.
+ the `Bag` has about 92% being correct.
+ the `Ankle Boot` has about 93% being correct.

Based on each f1 score, the weighted average of the precision and recall for

+ the `T-shirt/top` is 77%
+ the `Trouser` is 96%
+ the `Pullover` is 66%
+ the `Dress` is 83%
+ the `Coat` is 68%
+ the `Sandal` is 91%
+ the `Shirt` is 53%
+ the `Sneaker` is 90%
+ the `Bag` is 93%
+ the `Ankle Boot` is 91%

#### Future Works:
+ Model can be trained with more specific subclasses of each categorized items for more specific fashion items to be displayed to the consumers.