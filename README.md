This is a WIP code on implementing Deep Convolutional GAN Architecture on the [Pokemon Dataset]((https://www.kaggle.com/datasets/kvpratama/pokemon-images-dataset/data)) 

![image](https://github.com/One-eyed-warrior/PokeGAN/assets/75874625/ae839647-1472-48ab-9f1b-422027aff6e0)

This fun little endeavor of mine is essentially built upon concepts from [Radford et al. (2015)](https://arxiv.org/abs/1511.06434) 

Currently, I am not getting clear results (hence why it's WIP), Hopefully after some fine tuning I can get it up and running. 

Also facing issues with computation power (oh well). Hopefully, all will be resolved soon.

[UPDATE] 24/4/24: Alright, I changed the architecture for the generator a bit and it looks more coherent now, although I suspect I definitely need more epochs 
![image](https://github.com/One-eyed-warrior/PokeGAN/assets/75874625/db7508b2-1643-4f9f-92eb-5595bb00b795)


[UPDATE] 5/5/24: Getting more or less desirable results, changed the Network architecture by a lot ([Kaggle](https://www.kaggle.com/code/algord/pokemon-dcgan)), ran the code on a kaggle notebook using a T4 GPU X2 for about 500 epochs. Planning on modifying my older architecture to match this performance now that the computational power issue has been resolved. (Output isn't visible in the notebook because I suppose it doesn't support the generated GIF with the video player buttons)


[UPDATE] 9/5/24: Got it working on my local Gtx 1650, gonna tinker around a bit 


[UPDATE] 11/5/24: too much noise on local gpu, 1000 epochs fail to generate anything even remotely comprehensible. I think previous results were the best ones yet. As you can see down below the Discriminator loss is high => It might be overpowering the generator due to which the generator fails over and over.

Also, the Discriminator loss  abnormally spikes at epochs 274 & 275, which basically dooms the remaining cycles for the Generator. 
![image](https://github.com/One-eyed-warrior/PokeGAN/assets/75874625/42e9e14a-0f62-41e4-81f0-6e4f320a9588)



Generator


![image](https://github.com/One-eyed-warrior/PokeGAN/assets/75874625/31fc1052-d9c3-4d2a-b619-1e665b7fcc1d)


Discriminator


![image](https://github.com/One-eyed-warrior/PokeGAN/assets/75874625/276868b7-34aa-48d6-b08c-3c2d441581df)


DIFFERENCE FROM MAIN: Basically used a better [kaggle dataset](https://www.kaggle.com/datasets/hlrhegemony/pokemon-image-dataset) with over 2.5k clean labelled pokemon images.
This one also had significant noise towards the end, but the results in the middle turned out nice.


Output over 1000 epochs:


https://github.com/One-eyed-warrior/PokeGAN/assets/75874625/30f4c348-8479-4746-89fe-762c11779e08

Some great candidates from this one:

![image](https://github.com/One-eyed-warrior/PokeGAN/assets/75874625/4ec8b87d-28f0-4034-a182-9ceaed0ff737)
![image](https://github.com/One-eyed-warrior/PokeGAN/assets/75874625/94a2d70b-6a22-49eb-8a2d-4b2f65727210)
![image](https://github.com/One-eyed-warrior/PokeGAN/assets/75874625/4e043ef7-8992-447f-b4f5-ee10367d0c02)



















