# DCGAN

In this repository, I have reproduced the DCGAN paper. The paper can be found here: [DCGAN](https://arxiv.org/pdf/1511.06434.pdf)
The implementation is done using PyTorch. I have also released pretrained models.
Also, I am publishing a colab notebook, with which you can reproduce the entire model in just one go. And with the help
of the pretrained models, you can also, see amazing results, right in your browser and start playing with it.

## How to use

0. Go to the Colab Notebook: [DCGAN Colab](https://colab.research.google.com/github/iArunava/DCGAN/blob/master/DCGAN.ipynb)

---

0. Clone the repository and cd into it
```
git clone https://github.com/iArunava/DCGAN.git
cd DCGAN/
```

1. [Upcoming]

## Samples generated using DCGAN

1. STL10 (Epochs: 100)

![dcgan](https://user-images.githubusercontent.com/26242097/52493917-aca3b280-2bf2-11e9-95a5-aa68704f1d8e.png)

2. CIFAR10 

3. Stanford Dogs Dataset

4. Faces Dataset

5. Stanford Cars Dataset

![Epoch 100](https://github.com/iArunava/DCGAN/blob/master/results/cars/fake_99.png)

6. Oxford Flowers Dataset

![Epoch 200](https://github.com/iArunava/DCGAN/blob/master/results/flowers/fake_99%20(2).png)

## Pretrained models

1. Generator trained on the Stanford Cars Dataset for 100 epochs: [100 epoch trained Generator](http://bit.ly/g-100-cars)


## License

The code in this repository is made available for free. Feel free to fork and go crazy.
Also, you are welcome to use this code in commercial purposes for free, with just proper linkage
redirecting back to this repository.
