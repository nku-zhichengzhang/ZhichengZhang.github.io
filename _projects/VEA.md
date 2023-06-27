---
layout: page
title: Video Emotion Recognition
description: a demo that recognize the conveyed emotion of a video
img: assets/img/ver_fm.jpg
importance: 1
category: Affective Computing
---




# Video Emotion Recognition

Emotion refers to a person's disposition to respond to the media carrier. To this end, Video Emotion Recognition uncover the underlying attitude or opinions of viewers towards the given video.


<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="assets/video/sadness.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="assets/video/vlog.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="assets/video/maqima.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="assets/video/mv.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>
<div class="caption">
    Emotions conveyed in the video come across culture, nature, and situations.
    It involves film, VLog, animation, mv, and so on.
</div>

<div class="row mt-3">
    <div class="col-sm mt-4 mt-md-0">
        {% include video.html path="assets/video/yanzi.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
    <div class="col-sm mt-4 mt-md-0">
        {% include video.html path="assets/video/animal.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
    <div class="col-sm mt-4 mt-md-0">
        {% include video.html path="assets/video/pexels-engin-akyurt-6069112-960x540-30fps.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>
<div class="caption">
The subject also covers human, animal, landscape, and others.
</div>


# Results

<div class="row mt-3">
    <div class="col-sm mt-6 mt-md-0">
        {% include video.html path="assets/video/yanzi.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/animal_results.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>

# Online Demo

We also provide a online demo that can upload any video you like.
Due to the limitation of computation power of our server, if you want to process images in batch, please refer to our provided script on [Github:WECL](https://github.com/nku-zhichengzhang/WECL) or [Github:TSL](https://github.com/nku-zhichengzhang/TSL300).

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
