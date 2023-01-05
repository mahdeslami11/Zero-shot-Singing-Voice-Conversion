# Zero-shot-Singing-Voice-Conversion

Unofficial implementation of <a href="https://program.ismir2020.net/poster_1-08.html">zero-shot svc</a> presented at ISMIR 2020, in Pytorch.

```bibtex
@misc{Nercessian2020Zero-shot,
    title={Zero-shot Singing Voice Conversion},
    author={Shahan Nercessian},
    booktitle={Submitted to International Society for Music Information Retrieval},
    year={2020},
    url={https://program.ismir2020.net/poster_1-08.html},
    
}
```

In this paper, we propose the application of speaker embedding networks for zero-shot SVC. We suggest two architectures for carrying out zero-shot SVC using the WORLD vocoder for modeling singing voice. Overall, we find that speaker embeddings can indeed be used directly for zeroshot SVC. Moreover, zero-shot networks replacing onehot speaker labels with speaker embeddings perform as well as (or even better than) their supervised closed set counterparts, with the invaluable added benefits that they can be trained on unlabeled data and can potentially adapt to new voices without requiring further training. Furthermore, we show that there is some benefit to training zeroshot SVC networks by adapting an initial model trained on large amounts of speech data. In future work, we will investigate learning latent factors which can allow for further expressive manipulation of conversion results. While some initial progress to this end has been made using Gaussian Mixture VAEs (GMVAEs) , they have largely been limited to sung vowels. We can likely generalize this to more practical singing voice by utilizing the conditioning signals used in this work. We are also interested in replacing the WORLD vocoder with learned vocoders based on differentiable digital signal processing, as in in order to enable lightweight end-to-end 


my name is Mozhgan Dehghan Azad

40014140111066 student number

Digital signal processing Eslami


https://github.com/ak9250/Zero-shot-Singing-Voice-Conversion


other link in the aeticle:

  https://sites.google.com/izotope.com/ismir2020-audio-demo
  
  https://github.com/CorentinJ/Real-Time-Voice-Cloning
