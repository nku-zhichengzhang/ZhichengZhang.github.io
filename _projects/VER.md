---
layout: page
title: Video Emotion Recognition
description: a demo that recognize the conveyed emotion of the video
img: assets/img/ver_fm.jpg
importance: 1
category: Affective Computing
---



## Emotion

Emotion refers to a person's disposition to respond to the media carrier. To this end, Video Emotion Recognition uncover the underlying attitude or opinions of viewers towards the given video.


<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="assets/video/sadness.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true loop=true muted=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="assets/video/vlog.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true loop=true muted=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="assets/video/maqima.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true loop=true muted=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="assets/video/mv.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true loop=true muted=true %}
    </div>
</div>
<div class="caption">
    Emotions conveyed in the video come across culture, nature, and situations.
    It involves film, VLog, animation, mv, and so on.
</div>

<div class="row mt-3">
    <div class="col-sm mt-4 mt-md-0">
        {% include video.html path="assets/video/yanzi.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true loop=true muted=true %}
    </div>
    <div class="col-sm mt-4 mt-md-0">
        {% include video.html path="assets/video/animal.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true loop=true muted=true %}
    </div>
    <div class="col-sm mt-4 mt-md-0">
        {% include video.html path="assets/video/pexels-engin-akyurt-6069112-960x540-30fps.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true loop=true %}
    </div>
</div>
<div class="caption">
The subject also covers humans, animals, landscapes, and others.
</div>


# Recognition Results
<script src="mermaid.full.min.js"></script>

<div class="row mt-3">
    <div class="col-sm mt-6 mt-md-0">
        {% include video.html path="assets/video/yanzi.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true loop=true %}
    </div>
    <!-- <div class="col-sm mt-6 mt-md-0"> -->
        <div class="mermaid">
        gantt
            dateFormat  YYYY-MM-DD
            title Adding GANTT diagram functionality to mermaid

            section A section
            Completed task            :done,    des1, 2014-01-06,2014-01-08
            Active task               :active,  des2, 2014-01-09, 3d
            Future task               :         des3, after des2, 5d
            Future task2              :         des4, after des3, 5d

            section Critical tasks
            Completed task in the critical line :crit, done, 2014-01-06,24h
            Implement parser and jison          :crit, done, after des1, 2d
            Create tests for parser             :crit, active, 3d
            Future task in critical line        :crit, 5d
            Create tests for renderer           :2d
            Add to mermaid                      :1d

            section Documentation
            Describe gantt syntax               :active, a1, after des1, 3d
            Add gantt diagram to demo page      :after a1  , 20h
            Add another diagram to demo page    :doc1, after a1  , 48h

            section Last section
            Describe gantt syntax               :after doc1, 3d
            Add gantt diagram to demo page      :20h
            Add another diagram to demo page    :48h
        </div>
    <!-- </div> -->
</div>

# Online Demo

We also provide an online demo that can upload any video you like.
Due to the limitation of computation power of our server, if you want to process images in batch, please refer to our provided script on [Github:WECL](https://github.com/nku-zhichengzhang/WECL) or [Github:TSL](https://github.com/nku-zhichengzhang/TSL300).

{% raw %}
```
Weakly Supervised Video Emotion Detection and Prediction via Cross-Modal Temporal Erasing Network
Zhicheng Zhang, Lijuan Wang, and Jufeng Yang
IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) 2023.
```
```
Temporal Sentiment Localization: Listen and Look in Untrimmed Videos
Zhicheng Zhang and Jufeng Yang
Proceedings of the 30th ACM International Conference on Multimedia (ACM MM) 2022.
```
{% endraw %}
