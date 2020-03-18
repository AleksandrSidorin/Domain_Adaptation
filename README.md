# Domain_Adaptation

## Dataset

I am going to apply domain adaptation on digitis. Mainly because the images are small so they dont require a lot of computations and because most of the papers use it for evaluating their models. We have two datasets:

**MNIST:**
MNIST is a handwritten-digit dataset, where all images are in greyscale and have digits in a fixed orientation.
<img width="544" alt="Снимок экрана 2020-03-18 в 3 11 17 PM" src="https://user-images.githubusercontent.com/55827366/76949670-b980f280-692a-11ea-88fe-c044ad4b6bb6.png">

**SVHN:**
SVHN images are real-world RGB images of digits (in different orientations) taken from street house numbers.

<img width="494" alt="Снимок экрана 2020-03-18 в 3 12 12 PM" src="https://user-images.githubusercontent.com/55827366/76949742-dc130b80-692a-11ea-9499-c00c1effbcb5.png">

For the purpose of this Project we will consider.

SVHN: source domain.
MNIST: target domain

Training:

Access to source domain labels.
No Access to target domain labels.
Access to images from both domains.
Meaning we can use source domain with the labels but target domain we cannot use its labels for training.

Testing:

Accuracy on target domain is the goal.
Accuracy on source domain is not important.
