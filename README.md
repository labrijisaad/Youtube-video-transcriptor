## 🎥 `Youtube-video-transcriptor in Python` 🐍

<p align="center">
  <img src="https://user-images.githubusercontent.com/74627083/181471696-3de07398-b0d3-4a78-9fb9-06c49528b5c6.png" width="70%/>
</p>

> - 🎯 In this project, I developed a script in Python that uses Google's speech-to-text technology to transcribe audio from YouTube videos.
> - ⚠️ Please note the following before using the script:
>   - 1️⃣ **`The script is intended to be run on Google Colaboratory!`**  <a href="https://colab.research.google.com/github/labrijisaad/Youtube-video-transcriptor" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
>   - 2️⃣ The script may not always accurately transcribe text due to noise or the way the speaker talks in the video (e.g. speaking too fast or too slow).
>   - 3️⃣ **`The summary model`** used in the script is a community model available on [Huggingface](https://huggingface.co/) that **`only supports English text`**. It may not always accurately capture the general idea of the transcription, especially if there is a lack of data.
 

<p align="center">❓❓❓ HOW TO USE ❓❓❓</p>

```
>>> 1️⃣ Run the notebook in Colab (make sure you are logged into Colab with your Google account).
>>> 2️⃣ Paste the URL of the youtube video you want to transcribe into the `url` variable.
>>> 3️⃣ Replace the `lang` variable with the language spoken in the video (all instructions are provided in the notebook).
>>> 4️⃣ Run all cells (shortcut: `CTRL + F9`)
>>> 5️⃣ Download the generated TXT files (there will be two in total: one for the transcription and one for the translated transcription).
```

<p align="center">⚠️⚠️⚠️ UPDATE ⚠️⚠️⚠️</p>

```
>>> To optimize transcription time, I have updated the script to use `Python threads`, which helps to fully utilize the CPU resources provided by Colab. 
>>> As a result, the performance has significantly improved - a 30-minute video can now be transcribed in approximately 35 seconds, compared to the previous time of 2 minutes and 30 seconds. 
>>> You can find the updated script with threads in the accompanying notebook. 😁
```

> - 🙌 Notebook made by [@labriji_saad](https://github.com/labrijisaad)
> - 🔗 Linledin [@labriji_saad](https://www.linkedin.com/in/labrijisaad/)
- 📫 Feel free to contact me if anything is wrong or if anything needs to be changed 😎!  **labrijisaad@gmail.com**
