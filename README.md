# DeepFake Image Motion Animation
The following is a DeepFake Image Motion Animation model implemented as per this [paper](https://proceedings.neurips.cc/paper/2019/file/31c0b36aef265d9221af80872ceb62f9-Paper.pdf) . The model takes 2 things : Driving video & Source image . It then re-creates a new video by taking the object motion from driving video and appearance from the source image.


<div align="center">
<div> <b> (Architecture of the Model) </b> </div>
<Img src="/assets/architecture.png" width='85%' />
</div>

## Output :
Below are the results I got from using a pre-trained model trained on "VoxCeleb" dataset,where the source images contain images of myself and some of my high school friends.

#### 1] Me and My friends singing BakaMitai (ばかみたい)
<div align="center">
<Img src="/assets/BakaMitai_Collage_GIF.gif" width='85%' />
</div>


#### 2] Me and My friends imitating Obama
<div align="center">
<Img src="/assets/Obama_Collage_GIF.gif" width='85%' />
</div>













