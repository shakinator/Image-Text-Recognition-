# Image text recognition 
## About 
Reading or Recognizing Text from Images is a challenging Task in the field of Computer Vision. This is mainly because Text in Images exhibit diversity and variability. Backgrounds of Images are virtually unpredictable as some images may have dark background, some may have light background and there are even cases where image fonts and background have same color with a small outline differentiating Text from the Background. There might be patterns of Text appearing in the image with different fonts, orientations, and varying lengths. The Text in Images can also be blurred or distorted.
## Problem at hand
Given an input Image we need to predict the Text in the Image with a reasonable accuracy >80% (Exact match with the actual Text Labels) and should have a good letter match accuracy.

Well that is fine you say, are there any constraints? Yes, there are.

There is a Low Latency requirement meaning, given a picture the model should be able to predict the Text quickly
Predict Text from Images with Variable length Labels/Words.

## Some of the sample Images with text inside 
<img src="https://user-images.githubusercontent.com/65782416/191494010-583dd2e5-8be5-4a31-844f-e303e52321cb.jpg" alt="" size="75" align="left"></a>
<img src="https://user-images.githubusercontent.com/65782416/191494023-f0e8d6c4-9380-459e-826c-93843cc7eeb3.jpg" alt="" size="50" align="left"></a>
