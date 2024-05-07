### Paper Title: 
Blind 3D Video Stabilization with Spatio-Temporally Varying Motion Blur

### Abstract: 
Video stabilization compensates for frame shake during acquisition. Existing 3D methods model perspective through data-driven training or motion estimation. Yet, they struggle with shaky videos featuring abrupt movements, leading to local motion blur. This is common in real-world scenes with blind motion. Combining stabilization and deblurring faces challenges as motion blur intensity changes continuously. The direct method lacks spatio-temporal information, hindering cross-frame compensation. Our Cross-frame-temporal Network addresses blind motion blur, utilizing cross-frame temporal features. It includes a Blur Transform Block (BTBlock) for spatially varying motion blur, adapting to non-uniform effects. Our Temporal-aware Network (TANet) further suppresses motion blur. Limited pair-training data with motion blur hinders practical application. Our method, employing an un-pretrained in-test strategy, surpasses state-of-the-art methods, as shown in extensive experiments.

### Ours Method Vs State-of-the-Art:

##### Visual Comparison
![image](https://github.com/leadingme163/Blind_3D_Video_Stabilization/blob/main/Video_Comparison_2D.gif)  
![image](https://github.com/leadingme163/Blind_3D_Video_Stabilization/blob/main/Video_Comparison.gif)  

##### Depths Comparison
![image](https://github.com/leadingme163/Blind_3D_Video_Stabilization/blob/main/Depth_Comparison.gif)

( **Note:** If the GIFs don't load on the webpage, kindly download them for review. )


### MotionBlur Dataset Example
To provide a visual understanding of the dataset, below is a sample video from our dataset. You can access the full dataset via this link: [Google Drive Dataset Link](https://drive.google.com/file/d/1NdpJK7shKc-OYcr6mh3JDNX37rsryaEl/view?usp=sharing).

![Sample Video](https://github.com/leadingme163/Blind_3D_Video_Stabilization/blob/main/MotionBlur/sample_video.gif)

( **Note:** If the Images don't load on the webpage, kindly download them for review. )
