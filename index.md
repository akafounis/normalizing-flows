## Normalizing Flows

<img src="normalizing-flows-main.png" width="400">

We used for this project 2 different datasets:

1. Shifted Guassian
2. 2 Moons

and 2 transformations: 

1. Affine Transformation

An affine tranformation scales each dimension independently and shifts the inputs by a constant offset. The tranformation is defined as follows:

![alt text](affine_definition.png)

where parameters a from R^D b from R^D. 
We apply 'exp' elementwise to 'a' to obtain positive scales for each dimension. 


2. Radial Transformation

A radial flow is a simple but expressive transformation. It has been introduced in this paper(https://arxiv.org/pdf/1505.05770.pdf) by Rezende and Mohamed. The transformation is defined as:
![alt text](radial_definiton.png)


**Results:** 

Dataset: Shifted Guassian

![alt text](Affine_flow1.png)

![alt text](affine_flow2.png)

![alt text](affine_flow3.png)

![alt text](affine_flow4.png)

![alt text](affine_flow5.png)

![alt text](affine_flow6.png)


Dataset: 2 Moons

![alt text](moons1.png)

![alt text](moons2.png)

![alt text](moons3.png)

![alt text](moons4.png)

![alt text](moons_loss.png)

![alt text](moons_result.png)

**PyTorch** was used for the development of the model.
