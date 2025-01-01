# wav2lip_288x288 introduction
This is a project about talking faces. We use288X288 sized facial images for training, which can generate720p, 1080p, 2k,  human videos.
We have done the following work:
1. Add or remove video cutting codes.
2. Add filelists to generate code.
3. Trained 600 people, 30 hours, and over 30000 pieces of data.
4. Open sourced the checkpoint for a discriminator with 150000 steps and a val_rass of 0.28.
5. Open sourced a checkpoint for a generator with 360000 steps and a val_rass of 0.25.
6. Dear friends, you can load pre training weights for easy subsequent training.


# wav2lip-288x288 Project situation
<p align='center'>
  <b>
    <a href="https://www.bilibili.com/video/BV1zK421v7wh/?vd_source=7720ff9e037156b51374d14ee8f76b51">Video </a>
    | 
    <a href="https://github.com/langzizhixin">Project Page</a>
    |
    <a href="https://github.com/langzizhixin/wav2lip-576x576">Code</a> 
  </b>
</p> 
  <p align='center'>  
    <img src='576x576-CorrespondingVideo.jpg' width='1000'/>
  </p>

# wav2lip-576x576 Code Release Plan
This project is not yet mature enough.
We will gradually release the code, first release the data processing code, then release the inference code, and when the time is ripe, we will release the training code.

# acknowledge
The code is mainly borrowed from wav2lip, wav2lip-288, wav2lip-384, ER-NeRF, etc.
Thank you for their wonderful work.

# author
Project  made by Lu Rui from Langzizhixin Technology company in Chengdu, China, 2025.1.1

# Code contribution
At present, the video preprocessing, facial cropping, and audio Hubert processing codes have been completed. Welcome everyone to contribute code related to network structure, training, and inference.

# Citing
https://github.com/primepake/wav2lip_288x288
https://github.com/Rudrabha/Wav2Lip
Thank the above two authors.
