---
title: Side projects (AI/ML & creative coding)
pubDate: '2025-04-01'
---

Outside of design, I enjoy using code as a medium for creative expression and experimentation, often taking a playful approach, using tools in unconventional ways. Below are some of my favorite projects since 2018.

---

##### Study with Me, 2018
I made this app for my sister to help her stay focused during exam season. Inspired by the [‘Study With Me’ video series](https://www.youtube.com/watch?v=1ex_bNIFR1A) on YouTube, the application plays a 1-hour video of someone quietly studying. It can detect when my sister look away, and will nag her whenever she gets distracted.

**Tools**</br>
Wekinator, Processing, OpenCV

Audio transcripts (Vietnamese to English):
- Mích, học bài đi _Mích, back to study_
- Mích đừng mất tập trung nữa _Mích, stop losing focus_
- Học đi cho mẹ vui _Mích, study and make your mom happy_
- Mích đang nghĩ gì đấy? _Mích, what are you doing?_
- Đã bảo rồi đừng có mất tập trung nữa _I told you so, focus!_

::link{url="https://youtu.be/L3PLmjyZy0E"}
![_](./_assets/schoolofma/studywithme.png) 

---

##### Art-DCGAN, 2018
Using [Robbie Barrat's art-DCGAN](https://github.com/robbiebarrat/art-DCGAN), a modified implementation of DCGAN focused on generative art, I trained my own model on a dataset of 1,700 Ukiyo-e paintings scraped from [Wikiart](https://www.wikiart.org/en/paintings-by-style/ukiyo-e?select=featured).

![_](./_assets/schoolofma/epoch700.png)

---

##### People with My Name, 2018
I google-searched my full name and scraped the first 500 image results. From those, I cropped out faces and used [t-SNE](https://lvdmaaten.github.io/tsne/) for dimensionality reduction to cluster similar images. It’s worth noting that Trang Nguyen is a fairly common Vietnamese name. I made this with [Aarón Montoya-Moraga](https://github.com/montoyamoraga)’s Google Images scraping tool
 and [Andreas Refsgaard](https://www.andreasrefsgaard.dk/)’s face-cropping Processing tool.

**Tools**</br>
Processing, t-SNE

![_](./_assets/schoolofma/myname-2.jpg)

---

##### Git Song, 2018
I turned my [GitHub contribution graph](https://github.com/topics/contribution-graph) into music. As time moves forward, notes play to represent daily contributions; the more contributions, the higher and louder the note. The data is mapped across 3 octaves, starting from octave 4.

**Tools**</br>
[Sonic Pi](https://sonic-pi.net/)

::link{url="https://youtu.be/R-gS9AFVL1o"}

---

##### Audio Reactive Visuals, 2018
A series of audio-reactive posters I created for [Midlight](https://soundcloud.com/midlight/) using Processing. The original static visuals were designed by [Studio Naam](https://studionaam.com/).

**Tools**</br>
Processing

![](./_assets/midlight/midlight-2.gif)
![](./_assets/midlight/midlight-5.gif)
![](./_assets/midlight/midlight-6.gif)

---

##### Spark AR filters, 2018
A filter I developed in Spark AR as part of the Meta's Spark AR Hackathon Berlin in 2018.


**Tools**<br>
Spark AR

![Presenting my project at Meta's Spark AR Hackathon in Berlin](./_assets/schoolofma/sparkar_hackathon_pic.jpg)

---


##### AV Performance, 2019
In 2019, I took a 2-month VJ course using [Resolume](https://www.resolume.com/), and as part of the graduation show, I performed a live AV show at [Public Art Lab](https://www.publicartlab-berlin.de/).


**Tools**<br>
Resolume

::link{url="https://www.youtube.com/watch?v=l3Yla2WUaiw"}

![_](./_assets/schoolofma/resolume.jpg)


---

##### P5.js PoseNet as MIDI Controller, 2020 
Control Ableton Live with your hands. Built with PoseNet, a machine learning model that enables real-time human pose estimation by detecting key points on the body and face. [See demo video](https://vimeo.com/331012711?fl=pl&fe=sh).

**Tool**<br>
Ableton Live, PoseNet

![](./_assets/schoolofma/posenet.gif)

---

##### Visualisation for Spectral Resonator, 2022

An alternative visualisation I built for [Spectral Resonator](https://www.ableton.com/en/blog/spectral-sound-a-look-at-live-11s-new-spectral-devices/). 

**Tools**</br>
Processing


![_](./_assets/schoolofma/transmute_02.gif)
![_](./_assets/schoolofma/transmute_03.gif)

---


##### Datadog Hello Kitty Theme, 2024
Wanting a refreshing departure from Datadog's traditional utilitarian look and feel, I gave the UI a makeover. This Hello Kitty theme introduced a soft pastel color palette, rounded corners and playful animations everywhere! 

**Tools**<br>
Figma, Giphy


![_](./_assets/hellokitty/datadog-hello-kitty.gif)

![Sad and happy HTTP status code pills](./_assets/hellokitty/statuscode.png)

---

**Bufo Emoji Generator, 2025** <br>

A fun little website I built for generating custom [Bufo](https://knowyourmeme.com/memes/froge-worry-frog) Slack emojis. I manually created the assets and vibe-coded this in Cursor over a couple of days. [Check it out](https://bufo-generator.pages.dev/).

**Tools**</br>
Figma, Cursor

::link{url="https://bufo-generator.pages.dev/"}

![](./_assets/schoolofma/bufo.png)

---


##### Animating scatterplots with Vega-Lite, 2025
Data visualisations created when Datadog rolled out the support for [Vega-Lite](https://en.wikipedia.org/wiki/Vega_and_Vega-Lite_visualisation_grammars).  An open-source visualization grammar that allows allows users to create graphs that are not available within the native Datadog widget and query system. 

**Tools**<br>
Vega-Lite

The first animation I created was this [scatterplot of falling raindrops](https://vega.github.io/editor/#/url/vega-lite/N4IgJAzgxgFgpgWwIYgFwhgF0wBwqgegIDc4BzJAOjIEtMYBXAI0poHsDp5kTykBaADZ04JAKyUAVhDYA7EABoQOJACckCCGgDaoWRrhoQmGgkNK5O0HFKzMW1KEwBPHIfQmzqxcZiq22ILuAIwADAC+Sgw4ACZImO7GpnAAFLJsAO4pAJTZIOEAuoVKcZgojiDESIIMcA66IAAeRsEATJQAzKEA7N0+zkZdlKFiACzB+QqgzeitwcOtYgBs-UajAJyUS0vrYpPTRnMLy6uzS5StPev7TYOhlN07racgreeX3deRB+gdHZRiAAc6z6SgGZwB60WNxmIA65yhHQmYLW91GHUBfW+t3QowRrSRLwxAOCJ2xsLEoRewU2212MMO53GoQ6L0BlGChPJqJJrUB1PZYlJK256CW7UBlz2KNxEklfwZYrlING1IkI3GipAgNGHNCbxerVpOz2ou1-yBIKJ8zEUNNUxxIG6-x14utlBB3WeZpBHM+0pA4JAo26nSWwX5Zu6EjakpeS3ZnImZo2D3RKxlIDEcoJrLNHV1HVt8eN9LNby221BgaMS1D3Txqp9lFGmOemaWur5Gy1urCBszIbDEa1-x6OyJHK5DthwJbbZeurp9p+IDCY8e10zRsrZZnRnW522dfjOYVUfZeNJL2WFyuWsPLfXL19Dc7Wu69037Zr6E+u5XR1O06YtM0fD4vn3dBKTZeZPW9KCsyZZ9M26ODegQ1dRnuIU+TZM880Q0YJSlalQnueVCNXI4+TmNlBWFLU2gBTtkV-NdyOGMZk0QiRWLZC1GMKSJjHUWQIAAMzYVQECsEAoGqKAGEEeJEgAckAXg3AHKdtSfCQBwQEQNhJBoG4FMEJSVISFpyIAAgAalslJSgYBBKGcWz+FszxRDCUJslsgBSWy-Ic2yIBoWRnPiVz3NsgAqbzkgIPzyLyJR9KMBA2FIABNfICiUOBZCgNgYkisg0FAcFQAkmg4EEGIspyuB8qUFw3CMABHBgkDsOh4hoUgfGgap3FAGI2GQSKdFCBQ-KKESZlq+rGqMZp2tcRIer6kwyhMYaRIigAvcbKmqWo0EuESEkaTAqpAOqGqa9AjJMnwOsSdIEEi6p8hE5BVAAayMW77vCIA), using a simple dataset with about 40 points.Each point is represented with a 💧 emoji using Vega-Lite’s [text mark](https://vega.github.io/vega/docs/marks/text/).

![Static scatterplot with emoji](./_assets/vegalite/visualization.png)

To make the raindrops "fall", I added a timer. It updates every 10ms and is the time that passed since  the visualization loaded. 

```jsx
{
  "name": "time", 
     "on": [{"events": {"type": "timer", "throttle": 10}, "update": "now()"}] 
}
```

Using this timer, I updated the Y position of each raindrop with a combination of modulo (%) and sine to create looping vertical movement with some variation in speed:

```jsx
"transform": [
    {
      "calculate": "100 + (datum.y - time/100) % 100 + sin(datum.y * time/10000)",
      "as": "moveY"
    }
  ]
```
And voilà, animated rain. [View code.](https://vega.github.io/editor/#/url/vega-lite/N4IgJAzgxgFgpgWwIYgFwhgF0wBwqgegIDc4BzJAOjIEtMYBXAI0poHsDp5kTykBaADZ04JAKyUAVhDYA7EABoQOJACckCCGgDaoWRrhoQmGgkNK5O0HFKzMW1KEwBPHIfQmzqxcZiq22ILuAIwADAC+Sgw4ACZImO7GpnAAFLJsAO4pAJTZIOEAuoVKcZgojiDESIIMcA66IAAeRsEATJQAzKEA7N0+zkZdlKFiACzB+QqgzeitwcOtYgBs-UajAJyUS0vrYpPTRnMLy6uzS5StPev7TYOhlN07racgreeX3deRB+gdHZRiAAc6z6SgGZwB60WNxmIA65yhHQmYLW91GHUBfW+t3QowRrSRLwxAOCJ2xsLEoRewU2212MMO53GoQ6L0BlGChPJqJJrUB1PZYlJK256CW7UBlz2KNxEklfwZYrlING1IkI3GipAgNGHNCbxerVpOz2ou1-yBIKJ8zEUNNUxxIG6-x14utlBB3WeZpBHM+0pA4JAo26nSWwX5Zu6EjakpeS3ZnImZo2D3RKxlIDEcoJrLNHV1HVt8eN9LNby221BgaMS1D3Txqp9lFGmOemaWur5Gy1urCBszIbDEa1-x6OyJHK5DthwJbbZeurp9p+IDCY8e10zRsrZZnRnW522dfjOYVUfZeNJL2WFyuWsPLfXL19Dc7Wu69037Zr6E+u5XR1O06YtM0fD4vn3dBKTZeZPW9KCsyZZ9M26ODegQ1dRnuIU+TZM880Q0YJSlalQnueVCNXI4+TmNlBWFLU2gBTtkV-NdyOGMZk0QiRWLZC1GMKSJjHUWQIAAMzYVQECsEAoGqKAGEEeJEgAckAXg3AHKdtSfCQBwQEQNhJBoG4FMEJSVISFpyIAAgAalslJSgYBBKGcWz+FszxRDCUJslsgBSWy-Ic2yIBoWRnPiVz3NsgAqbzkgIPzyLyJR9KMBA2FIABNfICiUOBZCgNgYkisg0FAcFQAkmg4EEGIspyuB8qUFw3CMABHBgkDsOh4hoUgfGgap3FAGI2GQSKdFCBQ-KKESZlq+rGqMZp2tcRIer6kwyhMYaRIigAvcbKmqWo0EuESEkaTAqpAOqGqa9AjJMnwOsSdIEEi6p8hE5BVAAayMW77vCIA)

![_](./_assets/vegalite/vegalite-13.gif)

After that, other animations were created in a similar approach with different functions, using [Graphtoy](https://graphtoy.com/?f1(x,t)=4%20+%204*smoothstep(0,0.7,sin(x+t))&v1=false&f2(x,t)=clamp((atan(((x/10.)%25100)/8-1)*60),%200,%20100)&v2=true&f3(x,t)=sqrt((x/10.)%25100)%20*%208&v3=true&f4(x,t)=((x%20-%20200)/10.)%25100&v4=true&f5(x,t)=(t%20+%20floor(x-t))/2%20-%205&v5=false&f6(x,t)=sin(f5(x,t))%20-%205&v6=false&grid=1&coords=521.7855192792142,66.89164551771165,597.4221734999295) to test and visualise the motion path. 

![_](./_assets/vegalite/vegalite-4.png)

![_](./_assets/vegalite/vegalite-5.gif)

I also experimented with creating cross-graph animations, moving an object from one graph to another. I did this by having each graph renders a different segment of the animation’s X-axis. When loaded together, they appear as one continuous animation spread across panels. The effect only works if all graphs load simultaneously.

![_](./_assets/vegalite/vegalite-15.gif)

![Animated graphs displayed inside a Datadog dashboard](./_assets/vegalite/animated-graphs-2.gif)

---


##### A color tool for Flame Graphs, 2025
A small tool I built using Cursor to test colors for [flame graphs](https://www.brendangregg.com/flamegraphs.html), a visualization for stack traces of profiled software. The tool was based on [Leonardo](https://https://github.com/adobe/leonardo?tab=readme-ov-file), an open source contrast-based color generator. However, it couldn't generate the flame graphs very well, so I ended up testing the updated palette directly in our codebase.


**Tools**<br>
Cursor

![_](./_assets/schoolofma/colors.png)

::link{url="https://flamegraph-colors.pages.dev/"}