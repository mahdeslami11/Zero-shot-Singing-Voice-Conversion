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


result

In this paper, we propose the application of speaker embedding networks for zero-shot SVC. We suggest two architectures for carrying out zero-shot SVC using the WORLD
vocoder for modeling singing voice. Overall, we find that
speaker embeddings can indeed be used directly for zeroshot SVC. Moreover, zero-shot networks replacing onehot speaker labels with speaker embeddings perform as
well as (or even better than) their supervised closed set
counterparts, with the invaluable added benefits that they
can be trained on unlabeled data and can potentially adapt
to new voices without requiring further training. Furthermore, we show that there is some benefit to training zeroshot SVC networks by adapting an initial model trained on
large amounts of speech data. In future work, we will investigate learning latent factors which can allow for further
expressive manipulation of conversion results. While some
initial progress to this end has been made using Gaussian
Mixture VAEs (GMVAEs) , they have largely been
limited to sung vowels. We can likely generalize this to
more practical singing voice by utilizing the conditioning
signals used in this work. We are also interested in replacing the WORLD vocoder with learned vocoders based on
differentiable digital signal processing, as in  in
order to enable lightweight end-to-end training.


نویسنده مایل است از فرانسوا ژرمن و همه داوران ناشناس به خاطر نظرات ارزشمندشان 
در هنگام تهیه این مقاله که کیفیت این اثر را به طرز چشمگیری بهبود بخشید تشکر 
کند

The author would like to thank François Germain and all
the anonymous reviewers for their invaluable comments
while preparing this paper, which dramatically improved
the quality of this work.
  
  
 the project is taken from the orginal link   https://github.com/CorentinJ/Real-Time-Voice-Cloning 
 and https://sites.google.com/izotope.com/ismir2020-audio-demo
