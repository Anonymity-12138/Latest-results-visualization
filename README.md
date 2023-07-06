# Latest-results-visualization
![Upper](/title-upper-comp.png "Visualization of the results of a re-comparison with Infoswap")
<div align="center">***Figure 1. Visualization of the results of a re-comparison with Infoswap***</div>


In order to re-evaluate the facial swapping effect of our proposed method, we compared RCLSwap again with the state-of-the-art method, InfoSwap, on this set of examples. 
- ***Eye area problem (the green bounding box)***: Firstly, we have to acknowledge that our generation of the eye region is still imperfect in certain images, such as the target image in the first column, where InfoSwap achieves a better restoration effect. However, this is not the case for all samples, as evidenced by the additional visualization results provided in the experimental section of our paper.
- ***Artifacts and preservation of facial attributes (the red and yellow bounding box)***: RCLSwap performs better in restoring the target face. For instance, in the synthesized images, RCLSwap exhibits superior performance in reproducing the **glasses legs** of the person in the third column. Additionally, in the fourth column, it can be observed that InfoSwap suffers from **unclear boundaries** between the synthesized face and the background, accompanied by noticeable artifacts. Furthermore, InfoSwap even directly loses **the black dots** on the person's face.
- ***Image quality and face detail***: These images have not undergone deliberate post-processing. Both the images generated by RCLSwap and InfoSwap are of size 512×512 resolution. However, it can be noticed that the images synthesized by InfoSwap are more **blurry**, losing a significant amount of facial details from both the target and the source faces, resulting in an **overly smooth appearance**. On the other hand, the images synthesized by RCLSwap better restore the facial details, including **wrinkles and eye bags**. This may be attributed to the use of the StyleGAN framework, which has demonstrated excellent performance in synthesizing high-resolution images.
