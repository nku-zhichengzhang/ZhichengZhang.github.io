---
layout: page
title: Video Emotion Recognition
description: a demo that recognize the conveyed emotion of the video
img: assets/img/ver_fm.jpg
importance: 1
category: Affective Computing
mermaid: true
---



## Emotion
---
Emotion refers to a person's disposition to respond to the media carrier. To this end, Video Emotion Recognition uncover the underlying attitude or opinions of viewers towards the given video.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        <center>
            <span class="label label-default"><span style="color:red;font-weight:bold;">Neg</span>-Sadness</span>
        </center>
        {% include video.html path="assets/video/sadness.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true loop=true muted=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <center>
            <span class="label label-default"><span style="color:green;font-weight:bold;">Pos</span>-Happyness</span>
        </center>
        {% include video.html path="assets/video/vlog.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true loop=true muted=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <center>
            <span class="label label-default"><span style="color:red;font-weight:bold;">Neg</span>-Sadness</span>
        </center>
        {% include video.html path="assets/video/maqima.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true loop=true muted=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <center>
            <span class="label label-default"><span style="color:red;font-weight:bold;">Neg</span>-Sadness</span>
        </center>
        {% include video.html path="assets/video/mv.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true loop=true muted=true %}
    </div>
</div>
<div class="caption">
    Emotions conveyed in the video come across culture, nature, and situations.
    It involves film, VLog, animation, mv, and so on.
</div>

<div class="row mt-3">
    <div class="col-sm mt-4 mt-md-0">
        <center>
            <span class="label label-default"><span style="color:red;font-weight:bold;">Neg</span>-Sadness</span>
        </center>
        {% include video.html path="assets/video/yanzi.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true loop=true muted=true %}
    </div>
    <div class="col-sm mt-4 mt-md-0">
        <center>
            <span class="label label-default"><span style="color:red;font-weight:bold;">Neg</span>-Sadness</span>
        </center>
        {% include video.html path="assets/video/animal.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true loop=true muted=true %}
    </div>
    <div class="col-sm mt-4 mt-md-0">
        <center>
            <span class="label label-default"><span style="color:red;font-weight:bold;">Neg</span>-Sadness</span>
        </center>
        {% include video.html path="assets/video/pexels-engin-akyurt-6069112-960x540-30fps.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true loop=true %}
    </div>
</div>
<div class="caption">
The subject also covers humans, animals, landscapes, and others.
</div>


## Recognition Example
---
<script src="mermaid.full.min.js"></script>

<div class="row">
    <div class="col-sm">
        {% include video.html path="assets/video/yanzi.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true loop=true %}
    </div>
    <!-- <div class="col-sm mt-6 mt-md-0"> -->
    <div class="col-sm">
        <div id="pos_val_bar" style="background:#DDDDDD; width:11.7%;">
            <p id="pos_val" class="pl-5" style="font-size:23px;white-space:nowrap;">&#128512; Positive: 11.7</p>
        </div>
        <div id="neg_val_bar" style="background:#DDDDDD; width:88.3%;">
                <p id="neg_val" class="pl-5" style="font-size:23px;white-space:nowrap;">&#128533; Negative: 88.3</p>
        </div>
        <hr/>
        <div class="mermaid">
            gantt
            title Emotion Confidence
            dateFormat X
            axisFormat %s
            section Amusement
            5:0, 5
            section Contentment
            0: 0, 0
            section Awe
            2: 0, 2
            section Excitement
            2: 0, 2
            section Fear
            25: 0, 25
            section Sadness
            22: 0, 22
            section Disgust
            6: 0, 6
            section Anger
            38: 0, 38
        </div>
    </div>
    
</div>


## Online Demo
---
We also provide an online demo that can upload any video you like.
Due to the limitation of computation power of our server, if you want to process images in batch, please refer to our provided script on [Github:WECL](https://github.com/nku-zhichengzhang/WECL) or [Github:TSL](https://github.com/nku-zhichengzhang/TSL300).


## Related Papers
---
- Weakly Supervised Video Emotion Detection and Prediction via Cross-Modal Temporal Erasing Network. Zhicheng Zhang, Lijuan Wang, and Jufeng Yang, IEEE CVPR, 2023.

- Temporal Sentiment Localization: Listen and Look in Untrimmed Videos. Zhicheng Zhang and Jufeng Yang, ACM Multimedia, 2022.
