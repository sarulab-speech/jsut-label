# jsut-label
HTS-style context labels of [JSUT corpus](https://sites.google.com/site/shinnosuketakamichi/publication/jsut) available for speech synthesis system such as [HTS](http://hts.sp.nitech.ac.jp/), [Merlin](https://github.com/CSTR-edinburgh/merlin), and [nnmnkwii](https://github.com/r9y9/nnmnkwii). Phonetic and prosodic information are based on manual annotation. Time information are automatically estimated using [Julius](https://github.com/julius-speech/julius).
Currently, this repository provides the labels of the BASIC5000 subset. Also, the pronounced texts and kanas are listed in [./text_kana](text_kana).

## Notice
The context labels are not completely the same format as those created using OpenJTalk. The followings are NOT supported in the labels.
- Unvoiced vowels, which are genrally annotated as A, E, I, O and U.
- Word information (part-of-speech, conjugation type, and inflected form)

## License
The label data is licensed with the CC-BY-SA 4.0, etc. See LICENSE.txt file for the detail.

## Contributors
- Tomoki Koriyama (Main contributor) ([@hyama5](https://github.com/hyama5))
- [Shinnosuke Takamichi](https://sites.google.com/site/shinnosuketakamichi/)

## Acknowledgements
This work was supported by the following grants:
- KAKENHI Grant Number 17K12711
- [The GAP foundation program of the University of Tokyo](https://sites.google.com/site/shinnosuketakamichi/research-topics/gap2019)

## Links
+ [JSUT (Japanese speech corpus of Saruwatari-lab., University of Tokyo)](https://sites.google.com/site/shinnosuketakamichi/publication/jsut)
+ [r9y9/just-lab](https://github.com/r9y9/jsut-lab) ... provides automatically generated labels by using OpenJTalk.
+ [HMM/DNN-based Speech Synthesis System (HTS)](http://hts.sp.nitech.ac.jp/) ... provides label format in the demo scripts.
## Reference
+ Ryosuke Sonobe, Shinnosuke Takamichi, and Hiroshi Saruwatari, "JSUT corpus: free large-scale Japanese speech corpus for end-to-end speech synthesis," arXiv preprint, 1711.00354, Sep. 2017.
+ Shinnosuke Takamichi, Ryosuke Sonobe, Kentaro Mitsui, Yuki Saito, Tomoki Koriyama, Naoko Tanji, Hiroshi Saruwatari, "JSUT and JVS: free Japanese voice corpora for accelerating speech synthesis research," Acoustical Science and Technology, Vol.xxx, No.xxx, pp.xxx-xxx, 2020.

