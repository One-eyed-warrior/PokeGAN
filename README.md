This is a WIP code on implementing Deep Convolutional GAN Architecture on the [Pokemon Dataset]((https://www.kaggle.com/datasets/kvpratama/pokemon-images-dataset/data)) 

![image](https://github.com/One-eyed-warrior/PokeGAN/assets/75874625/ae839647-1472-48ab-9f1b-422027aff6e0)

This fun little endeavor of mine is essentially built upon concepts from [Radford et al. (2015)](https://arxiv.org/abs/1511.06434) 

Currently, I am not getting clear results (hence why it's WIP), Hopefully after some fine tuning I can get it up and running. 

Also facing issues with computation power (oh well). Hopefully, all will be resolved soon.

[UPDATE] 24/4/24: Alright, I changed the architecture for the generator a bit and it looks more coherent now, although I suspect I definitely need more epochs 
![image](https://github.com/One-eyed-warrior/PokeGAN/assets/75874625/db7508b2-1643-4f9f-92eb-5595bb00b795)


[UPDATE] 5/5/24: Getting more or less desirable results, changed the Network architecture by a lot ([Kaggle](https://www.kaggle.com/code/algord/pokemon-dcgan)), ran the code on a kaggle notebook using a T4 GPU X2 for about 500 epochs. Planning on modifying my older architecture to match this performance now that the computational power issue has been resolved.


Generator
![image](https://github.com/One-eyed-warrior/PokeGAN/assets/75874625/31fc1052-d9c3-4d2a-b619-1e665b7fcc1d)

Discriminator
![image](https://github.com/One-eyed-warrior/PokeGAN/assets/75874625/276868b7-34aa-48d6-b08c-3c2d441581df)





some sample outputs from the current state of this code: 
![image](https://github.com/One-eyed-warrior/PokeGAN/assets/75874625/f3569968-8369-4a86-89a8-df292e75e44c)
![image](https://github.com/One-eyed-warrior/PokeGAN/assets/75874625/886b72f3-d1fb-4ba5-a294-52a6eda93834)
![image](https://github.com/One-eyed-warrior/PokeGAN/assets/75874625/9709654a-a02d-4ecd-b1cc-59eaf7fca08c)

Some that I think make great potential candidates:
![image](https://github.com/One-eyed-warrior/PokeGAN/assets/75874625/f089daed-a347-49bd-9a3c-637d3f0f175d)
![image](https://github.com/One-eyed-warrior/PokeGAN/assets/75874625/1ea33835-5fbe-4526-af62-8e74eff597ef)
![image](https://github.com/One-eyed-warrior/PokeGAN/assets/75874625/63acf207-675f-4768-a71f-c9008d530c42)








