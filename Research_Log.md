# Constellation 2.0 Research Log

### August 17th, 2018

- Decided to pivot from old idea
- New idea uses applied linear regression for edge detection, and then formulate planes via a neural network
- From the planes found in an image, you can find their distance from camera at different points on the shape and use it to form a "gradient distance" and find the orientation of the plane
- Read some papers and did some research into optimization problems, tradeoffs, and gradient descent

### August 18th, 2018

- restructured code to fit library format
- explored different machine learning libraries to carry out neural network function-
  - tensorflow
  - keras
  - Scikit learn (current favorite)
  - scikit flow? - could merge high accuracy, gpu acceleration, and good efficiency from tensorflow with easy-to-use sklearn
- explored different training functions - backprop, cross entropy?
- derived equations for finding line of best fit
- researching distance math for distnace gradient