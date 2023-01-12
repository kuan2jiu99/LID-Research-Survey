# LID-Research-Survey
Language Identification Paper Survey

## InterSpeech 2022

* Improving Language Identification of Accented Speech [1]
  * LID systems that perform exceptionally well on native speech, have dramatically worse accuracy on identifying the language from non-    native speech and native speech with a distinctive regional accent.
  * This paper shows that for speech with a non-native or regional accent, the accuracy of spoken language identification systems drops dramatically, and that the accuracy of identifying the language is inversely correlated with the strength of the accent.
  * Besides accents, length of utterance, noise level and type of speech also have an impact on the performance of LID.
  * Combining acoustic feature and ASR-based feature for improving LID.
  * Combining character n-gram based Naive Bayes text classification models with a system that uses acoustic representation increases the robustness of LID systems to accented speech by a large margin, without sacrificing accuracy on native speech.


* A Multimodal Strategy for Singing Language Identification [2] 
  * In this paper, we present an automated multimodal approach to identify the singing language of songs that scales to millions of songs.
  * The proposed model uses a variety of song-level features, including a consumption embedding derived from sessions listening data from a music streaming service, segment-level vocals embedding computed from the vocal track of a song, and generic timbral features.
  * Most LID models are trained on spoken speech and human dialog, thus they have lower accuracy when applied to singing language in music due to variable phonation in singing.



* Streaming End-to-End Multilingual Speech Recognition with Joint Language Identification [3]
  * In this paper, we propose to modify the structure of the cascaded-encoder-based recurrent neural network transducer (RNN-T) model by integrating a per-frame language identifier (LID) predictor.
  * RNN-T with cascaded encoders can achieve streaming ASR with low latency using first-pass decoding with no right-context, and achieve lower word error rates (WERs) us- ing second-pass decoding with longer right-context.


* Transducer-based language embedding for spoken language identification [4] 
  * In this paper, we propose a novel transducer-based language embedding method that integrates the RNN-T model into a language embedding extraction framework. Benefiting from the advantages of the RNN-T’s acoustic and linguistic representa- tion, the proposed method can encode both acoustic and explicit linguistic features for building robust LID systems.


* PHO-LID: A Unified Model Incorporating Acoustic-Phonetic and Phonotactic Information for Language Identification [5]
  * In this paper, we proposed the PHO-LID model that incorporates the phonetic and phonotactic information for LID without the need for phoneme annotations.
  * Since acoustic-phonetic and phonotactic cues depict the language identities of a speech signal in different granularities, it is natural to consider both jointly to achieve high LID performance.



## Reference
* [1] https://www.isca-speech.org/archive/pdfs/interspeech_2022/kukk22_interspeech.pdf
* [2] https://www.isca-speech.org/archive/pdfs/interspeech_2022/lee22o_interspeech.pdf
* [3] https://www.isca-speech.org/archive/pdfs/interspeech_2022/zhang22da_interspeech.pdf
* [4] https://www.isca-speech.org/archive/pdfs/interspeech_2022/shen22b_interspeech.pdf
* [5] https://www.isca-speech.org/archive/pdfs/interspeech_2022/liu22e_interspeech.pdf
