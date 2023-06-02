---
layout: page
title: whisper.unity
description: Automatic speech recognition (ASR) model for Unity3d running on your local machine
img: assets/img/projects/whisper.jpg
importance: 970
category: open source
---

Open-source Unity3d bindings for the <a href="https://github.com/ggerganov/whisper.cpp">whisper.cpp</a>. It provides high-performance inference of <a href="https://github.com/openai/whisper">OpenAI's Whisper</a> automatic speech recognition (ASR) model running on your local machine.

Main features:

- Multilingual, supports around 60 languages
- Can translate one language to another (e.g. German speech to English text)
- Different models sizes offering speed and accuracy tradeoffs
- Runs on local users device without Internet connection
- Free and open source, can be used in commercial projects

Here is some samples of whisper.unity:

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="assets/video/whisper_multilang.mp4" class="img-fluid rounded z-depth-1" controls=true %}
        <div class="caption">
            "whisper-small.bin" model tested in English, German and Russian from microphone
        </div>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="assets/video/whisper_sub.mp4" class="img-fluid rounded z-depth-1" controls=true %}
        <div class="caption">
            "whisper.tiny" in subtitles demo, color shows confidence level for each token
        </div>
    </div>
</div>

<a href="https://github.com/Macoron/whisper.unity">[Download on Github]</a>
