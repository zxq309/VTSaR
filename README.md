# Aerial Person Detection for Search and Rescue: Survey and Benchmarks
## Collection process of VTSaR Dataset
We have conducted a comprehensive Aerial Person Detection (APD) dataset labeled as ”VTSaR”, which stands out from the existing publicly accessible APD datasets by offering a greater diversity of scenes, varying personnel behaviors, flexible capture angles, differing capture heights, and an inclusion of aligned visible and infrared samples along with synthetic samples. Our captured system is equipped with a dual-camera gimbal that integrates visible and infrared cameras. This configuration facilitates the simultaneous acquisition of visible and infrared images, providing a diverse corpus of image data gleaned from different perspectives and under varied visibility conditions.
![fig8](imgs/fig8.png)

## Sample examples from the A-VTSaR dataset
Obtaining samples from authentic Search and Rescue (SaR) scenarios often proves challenging due to various logistical constraints and statutory regulations. Most samples in our dataset were procured from regions close to personal activity. Nonetheless, limited financial resources frequently hamper the acquisition of samples from flora-dense forests, mountainous terrains, and expansive bodies of water.
![fig9](imgs/fig9.png)

## Examples of AS-VTSaR dataset samples
We adopted an approach to artificially synthesize samples, which incorporating merging numerous visible images via cropping and stitching techniques alongside sourcing high-resolution training samples rendered from cropped regions consistently featuring at least one person. The offline Mosaic approach was applied to infrared images to ensure equivalent sample sizes and consistent crop positioning between visible and infrared images within the same batch. Furthermore, we utilized a simple linear weighting methodology to merge visible and infrared images.
![fig10](imgs/fig10.png)

The dataset can be downlaoded from https://pan.baidu.com/s/12P4tUg03KSYQYlA3E1iD0Q?pwd=zs5z, the code is zs5z.
