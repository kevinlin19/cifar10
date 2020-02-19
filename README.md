# cifar10
首次CNN model 建立，採用keras
- Dataset: Cifar10，共有10費資料: ['airplane', 'automobile', 'bird', 'cat', 'deer', 'dog', 'frog', 'horse', 'ship', 'truck']
- technique: 
  - image generation
  - CNN model w/ adagrad
  - PIL to reshape image
- Files description:

|File|Description|
|---|---|
|[keras_ConvNets.ipynb](https://github.com/kevinlin19/cifar10/blob/master/keras_ConvNets.ipynb) | 建立model|
|[keras_ConvNet_test3.ipynb](https://github.com/kevinlin19/cifar10/blob/master/keras_ConvNet_test3.ipynb) | 相較model1比較淺，效果較差|
|[use_keras_ConvNets.ipynb](https://github.com/kevinlin19/cifar10/blob/master/use_keras_ConvNets.ipynb) | 將存的model使用，建立show function，輸入testing set 的 number，會return種類|
