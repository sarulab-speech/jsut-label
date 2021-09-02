# e2e_symbol
The phonemes labels for end-to-end speech synthesis. They also includes prosodic symbols such as accent nuclei.

## Format
The labels are defined by the following styles. The symbols are based on [山本・高道2021] and [Kurihara2020]. "-" is a separator.
- hiragana.yaml
> ^て]にすにも#あ]るけど_よ[んだいた]いかいって#な]に?$
- katakana.yaml
> ^テ]ニスニモ#ア]ルケド_ヨ[ンダイタ]イカイッテ#ナ]ニ?$
- phoneme.yaml
> ^-t-e-]-n-i-s-u-n-i-m-o-#-a-]-r-u-k-e-d-o-_-y-o-[-N-d-a-i-t-a-]-i-k-a-i-cl-t-e-#-n-a-]-n-i-?-$

## Prosodic labels
The prosodic labels are common to the three styles. 

| Label | Description |
| --- | --- |
| ^ | The beggning of sentence |
| $ | The end of sentence |
| _ | Pause |
| # | Accent phrase boundary |
| [ | Accent symbol: low to high |
| ] | Accent nucleus symbol: high to low |
| ? | rise-type boundary pitch movement (question sentence) |


## Reference
+ [山本・高道2021] 山本龍一・高道慎之介 著『Pythonで学ぶ音声合成　機械学習実践シリーズ』インプレス，2021.
+ [Kurihara2020] Kiyoshi KURIHARA, Nobumasa SEIYAMA, Tadashi KUMANO, "Prosodic Features Control by Symbols as Input of Sequence-to-Sequence Acoustic Modeling for Neural TTS," IEICE Transactions on Information and Systems, 2021, E104.D, No.2, pp. 302-311.

