---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat.

My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

# 📖 About Me

Hello, I am a Senior Algorithm Expert in the Multimodal Group at  <a href = 'https://www.01.ai'>01.AI</a>. My research interests cover computer vision, vision and language, and multimodal generation. Specifically, I focus on image generation, video generation, and speech generation, with precise control over these processes through text, images, and speech.
Before joining 01.AI, I was the head of the AI department at Xinhua Zhiyun, an Alibaba-affiliated company. Prior to that, I was the co-founder and CTO of <a href='https://uni-ubi.com'>UniUbi</a>. I received my master's degree in 2015 from the Institute of Automation, Chinese Academy of Sciences, under the supervision of Professor <a href='https://scholar.google.com/citations?user=Y-nyLGIAAAAJ&hl=zh-CN'>Stan Z. Li</a>. During my career, I have been dedicated to advancing AI research and have successfully implemented several AI applications, particularly in the areas of content creation and enhancement.
If you are interested in collaborating with me to explore the development of next-generation multimodal models, please feel free to contact me via email at (wangtaomarvel at gmail dot com).



<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 💻 Projects 

<div class='paper-box'><div class='paper-box-image'>
<div>
<div class="badge"></div>
<img src='images/whiteboard_exported_image.png' alt="sym" width="100%">
</div>
</div>

<div class='paper-box-text' markdown="1">
<b>Text-to-Image Generation Based on Multimodal Large Models</b>

- Project Duration: 2024
- This is an Any-to-Any Multimodal LLM project that supports using both images and text as conditions simultaneously. 
- By leveraging the powerful MLLM, it achieves superior text encoding and offers better prompt following compared to open-source models.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'>
<div>
<div class="badge"></div>
<img src='images/image_edit.png' alt="sym" width="100%">
</div>
</div>

<div class='paper-box-text' markdown="1">
<b>Intelligent Image Editing Based on Multimodal Large Models</b>

- Project Duration: 2024
- Enables various intelligent image editing tasks.
- Automatically generates Edit Type, Mask Prompt, and Output Image Prompt based on MLLM.
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'>
<div>
<div class="badge"></div>
<img src='images/talking_face.png' alt="sym" width="100%">
</div>
</div>

<div class='paper-box-text' markdown="1">
<b>Multimodal-Driven Digital Human Model for Thousands of Users</b>

- Project Duration: 2021-2023
- Supports customization of digital humans for multiple users (>1000) within a single model.
- Supports multiple input types, including voice, singing, and images.
- Extremely fast inference speed, utilizing RTX 4090 for 10x video synthesis speed.
</div>


<div class='paper-box-videos'>
    <div class="video-container">
        <video src="video/demo_douying_169.mp4" controls></video>
        <div class="video-title">speech-driven video synthesis</div>
    </div>
    <div class="video-container">
        <video src="video/girl_sing.mp4" controls></video>
        <div class="video-title">music-driven video synthesis</div>
    </div>
</div>

<!-- <div class='paper-box-videos'>
<video src="video/demo_douying_169.mp4" controls></video>
<video src="video/girl_sing.mp4" controls></video>
</div> -->

</div>


<!-- 
<div class='paper-box'>
<div class='paper-box-image'>
<div>
<div class="badge"></div>
<img src='images/talking_face.png' alt="sym" width="100%">
</div>
</div>

<div class='paper-box-text' markdown="1">
<b>Multimodal-Driven Digital Human Model for Thousands of Users</b>

- Supports customization of digital humans for multiple users (>1000) within a single model.
- Supports multiple input types, including voice, singing, and images.
- Extremely fast inference speed, utilizing RTX 4090 for 10x video synthesis speed.
</div>
</div>
<div> 
<iframe src="video/demo_douyin.mp4" allowfullscreen></iframe>
</div>
<div> 
<iframe src="video/girl_sing.MP4" allowfullscreen></iframe>
</div> -->


<div class='paper-box'>
<div class='paper-box-image'>
<div>
<div class="badge"></div>
<img src='images/tts.png' alt="sym" width="100%">
</div>
</div>

<div class='paper-box-text' markdown="1">
<b>Self-Supervised Multi-Speaker TTS Model</b>

- Project Duration: 2022-2023
- Seamlessly integrates phoneme prediction, phoneme alignment, and vocoder to achieve true self-supervised training, leveraging the value of big data.
- Supports multi-speaker training and zero-shot voice cloning.
- Non-autoregressive design, enabling fast inference speeds.
</div>

<div class='paper-box-audio'>
<div class='audio-box dual'>
<p>All Speakers in One Model</p>
<audio controls>
<source src="audio/All_Speakers_in_One_Model.wav" type="audio/wav">
Your browser does not support the audio element.
</audio>

</div>
<div class='audio-box dual'>
<p>Zero Shot Original Voice</p>
<audio controls>
<source src="audio/zero_shot_original_voice.wav" type="audio/wav">
Your browser does not support the audio element.
</audio>

</div>
<div class='audio-box dual'>
<p>Zero Shot Synthesized</p>
<audio controls>

<source src="audio/zero_shot_synthesized.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>

</div>
</div>

<!-- <div class='paper-box-audio'>
<div class='audio-box'>
<p>All Speakers in One Model</p>
<audio controls>
<source src="audio/All_Speakers_in_One_Model.wav" type="audio/wav">
Your browser does not support the audio element.
</audio>
</div>
<div class='audio-box'>
<p>Zero Shot Original Voice</p>
<audio controls>
<source src="audio/zero_shot_original_voice.wav" type="audio/wav">
Your browser does not support the audio element.
</audio>
</div>
<div class='audio-box'>
<p>Zero Shot Synthesized</p>
<audio controls>
<source src="audio/zero_shot_synthesized.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
</div>
</div> -->

</div>

# 📝 Publications 
<!-- - [Face liveness detection using 3D structure recovered from a single camera](https://nlpr.ia.ac.cn/2013papers/gjhy/gh95.pdf), Wang T, Yang J, Lei Z, et al. -->
- **Tao Wang**, Jianwei Yang, Zhen Lei, Shengcai Liao, Stan Z. Li. “Face Liveness Detection
Using 3D Structure Recovered from a Single Camera”. ICB2013. Madrid, Spain, June 4-7, 2013. Citations:162

# 🎖 Honors and Awards
- National Scholarship three times
- **Champion** of the first Alibaba Tianchi Big Data Competition, with a prize of 200,000 RMB
- **Champion** of the 2014 Double 11 Tmall Recommendation Algorithm Challenge, with a prize of 1,000,000 RMB


<!-- # 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->