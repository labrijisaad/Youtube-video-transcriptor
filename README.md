## 🎥 `Youtube-video-transcriptor in Python` 🐍 :
<p align="center">
  <img src="https://user-images.githubusercontent.com/74627083/181471696-3de07398-b0d3-4a78-9fb9-06c49528b5c6.png" />
</p>

- 🎯 In this notebook, I tried to write a script capable of transcribing youtube videos (audios in general) using the google's speech-to-text.
- ⚠️ Things to consider before using this notebook:
 > 1️⃣ **`This script is meant to be run in google colaboratory!`**  <a href="https://colab.research.google.com/github/labrijisaad/Youtube-video-transcriptor" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
 
 > 2️⃣ This script can sometimes not detect text correctly, it's mainly due to noises or the way we speak in the video (speaking too fast or too slow)
 
 > 3️⃣ The general idea summary model is a community model available at [Huggingface](https://huggingface.co/) **`that only can be used on english texts`**, it can sometimes get the general idea wrong, especially if there is a lack of data.
 

<p align="center">⚠️⚠️⚠️ UPDATE ⚠️⚠️⚠️</p>

```
>>> In order to optimize the transcription time, I updated the script using python threads 😋, it helps to use the CPU resources provided by colab to the maximum.
>>> In terms of performance, you can transcribe a 30min video in ~35sec (it was ~2min30sec with the old script)
>>> You can find the code with threads in the updated notebook 😁
```

> - 🙌 Notebook made by [@labriji_saad](https://github.com/labrijisaad)
> - 🔗 Linledin [@labriji_saad](https://www.linkedin.com/in/labrijisaad/)
- 📫 Feel free to contact me if anything is wrong or if anything needs to be changed 😎!  **labrijisaad@gmail.com**
