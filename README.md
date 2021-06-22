# gwnet
---
Pytorch based deep learning modules for analyzing gravitational wave data.
It consists of neural network classes and loss functions.


## References
```illinois.py``` consists of the convolutional neural networks which is employed in George \& Huerta (2016) Phys. Rev. D***.
It is recommended to cite the paper

```TSYAutoencoder.py``` consists of the implementation of conditional variational autoencoder. This is useful for a rapid parameter estimation. This is originally proposed by Gabbard *et al.* (2019)[2]. They applied the conditional variational autoencoder for GW signals from merging binary black holes. I applied CVAE for ringdown graviational waves from merged remnant black holes [3].

You can find the code ```Vitamin_C``` which is implemented by H.Gabbard. It is based on TensorFlow.


[1] D. George \& E. A. Huerta, Physical Review D***
[2] H. Gabbard *et al.*, arXiv: 1909.06296 (See also, github page of H.Gabbard)
[3] T. S. Yamamoto \& T. Tanaka, arXiv: 2002.12095


## Requirement
- Pytorch
- numpy
- json

You can get these modules by ```pip```, i.e.,
```$ pip install torch numpy json```


The network parameters are not implemented 
```json`` is used for loading the 


## Author
Takahiro S. Yamamoto
