# MP4_AdobeChallenge

## Proposed Methodology
The high level design diagram of the proposed approach is as
shown in Figure given below

![High Level Design Diagram](https://github.com/MoyankGiri/MP4_AdobeChallenge/blob/main/Assets/InterIITMP4.jpg)

As shown, the input consists of various modalities of inputs
such as images, videos, GIFs and Text. Each of these modal-
ities must be handled uniquely.
The proposed methodology tries to efficiently tackle this by
projecting the various modalities of data onto a common
modality, which is here Text. Therefore, here the data pro-
vided in the form of Image and Video are converted into Text
format, using Image and Video Captioning.
Using advanced methods for Image and Video Captioning,
the methodology mainly works over the idea of capturing and
representing images as text, and therefore, bringing the entire
data into a common parameter space which can be effectively
used for the intended purpose.
Further the proposed approach has an efficient working due
to the type of data used, which is tweets. In general, these
tweets have context in them via hashtags and account infor-
mation, which would therefore, help in interlinking the visual
data and its text representation.
Now, once all the data is processed as text, we pass the entire
data to separate models to tackle each of the individual tasks,
which are Behaviour Prediction and Content Generation. For
the Behaviour Prediction, we make use of Regression mod-
els while for Content Generation we make use of Large Lan-
guage Models (LLMs) to which data is communicated in the
form of prompts
