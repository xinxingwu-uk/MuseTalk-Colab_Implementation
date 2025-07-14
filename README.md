# MuseTalk-Colab_Implementation

# Colab_Implementation-HeyGem

Here we provided ***a google colab implementation*** of HeyGem.

---
## Description

HeyGem is a free and open-source AI avatar project developed by Duix.com. It enables anyone to create ultra-realistic digital human avatars and produce AI-driven videos easily and at almost zero cost, using ordinary computer hardware.

HeyGem uses artificial intelligence to train digital avatars from real-person video data, bypassing the need for expensive and complex 3D modeling.

---
## Examples

### Case 1: Text + Orignal Video to Video ([Text2Video.ipynb](https://github.com/xinxingwu-uk/Colab_Implementation-HeyGem/blob/main/Text2Video.ipynb))
<table class="center">
<tr>
    <td width=30% style="border: none">
        Input 1
    </td>
    <td width=35% style="border: none">
        Input 2 (Original)
    </td>
    <td width=35% style="border: none">
        Output
    </td>
</tr>

<tr>
    <td width=30% style="border: none">
       In order to produce effective targeted therapies for cancer, scientists need to isolate the genetic and phenotypic characteristics of cancer cells ...
    </td>
    <td width=35% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/8665a86f-7508-4922-877a-1805e67ca507" muted="false"></video>
    </td>
    <td width=35% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/987cea5d-6d53-412a-8cf9-274d21aa27b5" muted="false"></video>
    </td>
</tr>
</table>


### Case 2: Text + Orignal Video to Video ([Text2Video.ipynb](https://github.com/xinxingwu-uk/Colab_Implementation-HeyGem/blob/main/Text2Video.ipynb))
<table class="center">
<tr>
    <td width=30% style="border: none">
        Input 1
    </td>
    <td width=35% style="border: none">
        Input 2 (Original)
    </td>
    <td width=35% style="border: none">
        Output
    </td>
</tr>

<tr>
    <td width=30% style="border: none">
       Large language model is gradually changing people's lives...
    </td>
    <td width=35% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/d91aef8f-bc0c-499d-bbc0-c5641b07f16b" muted="false"></video>
    </td>
    <td width=35% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/6b5a0f7d-e00e-4b78-a201-9c827cbf7599" muted="false"></video>
    </td>
</tr>
</table>


### Case 3: Audio + Orignal Video to Video ([Audio2Video.ipynb](https://github.com/xinxingwu-uk/Colab_Implementation-HeyGem/blob/main/Audio2Video.ipynb))
<table class="center">
<tr>
    <td width=30% style="border: none">
        Input 1
    </td>
    <td width=35% style="border: none">
        Input 2 (Original)
    </td>
    <td width=35% style="border: none">
        Output
    </td>
</tr>

<tr>
    <td width=30% style="border: none">
       <a href="https://github.com/xinxingwu-uk/Colab_Implementation-HeyGem/blob/main/resources/audio2videoAudio.mp3">Audio</a>
    </td>
    <td width=35% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/dc00158b-940c-4bc9-9556-7599c086b626" muted="false"></video>
    </td>
    <td width=35% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/a43c099c-c013-4cde-9d01-131ef0398590" muted="false"></video>
    </td>
</tr>
</table>


### Case 4: Audio + Orignal Video to Video ([Audio2Video.ipynb](https://github.com/xinxingwu-uk/Colab_Implementation-HeyGem/blob/main/Audio2Video.ipynb))
<table class="center">
<tr>
    <td width=30% style="border: none">
        Input 1
    </td>
    <td width=35% style="border: none">
        Input 2 (Original)
    </td>
    <td width=35% style="border: none">
        Output
    </td>
</tr>

<tr>
    <td width=30% style="border: none">
       <a href="https://github.com/xinxingwu-uk/Colab_Implementation-HeyGem/blob/main/resources/HeygemTest1Audio.mp3">Audio</a>
    </td>
    <td width=35% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/5a894218-93e3-4ba2-b063-4080ba6827e6" muted="false"></video>
    </td>
    <td width=35% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/b42927ac-47ad-4fc7-9ec8-f06261c0694a" muted="false"></video>
    </td>
</tr>
</table>

> ***Note 1***: We have observed that the model performs suboptimally when tested on animation videos. This is likely because the underlying model was primarily trained on real, human-centric datasets. As a result, its ability to generalize to animation videos is limited, and the outputs in these cases may be less accurate or realistic.

> ***Note 2*** (used A100GPU in Colab): Audio + Orignal Video to Video - Generating a 3-minute 54-second video takes approximately 4 minutes and 31 seconds. In comparison, generating an 18-second video requires about 1 minute and 18 seconds.


---
## 🔥 Procedures - Implementation in Colab

Setting in Colab: In the implementation, used A100GPU in Colab as follows

<img src="resources/fig0.png" width="280">

---

* ***Step 1***: Download the ipynb file https://github.com/xinxingwu-uk/Colab_Implementation-HeyGem/blob/main/DownloadModel.ipynb from the GitHub repository, then upload it to your Google Drive.

* ***Step 2***: In Google Drive, open the ipynb file by Google Colab

* ***Step 3***: Implement the ipynb file in Google Colab - Run all cells in the notebook to set up and download the project.

  <img src="resources/fig1.png" width="280">

* ***Step 4***: After execution, check your Google Drive in the same folder where the notebook is located. The whole project should now be available there - Google Drive folder: HeyGem-Linux-Python-Hack.

* ***Step 5***: Upload the ipynb files Audio2Video.ipynb (https://github.com/xinxingwu-uk/Colab_Implementation-HeyGem/blob/main/Audio2Video.ipynb) and Text2Video.ipynb (https://github.com/xinxingwu-uk/Colab_Implementation-HeyGem/blob/main/Text2Video.ipynb) in your Google Drive, right-click, and open with Google Colab. Then, run through the notebook step by step:

Take ***Text + Orignal Video to Video** ([Text2Video.ipynb](https://github.com/xinxingwu-uk/Colab_Implementation-HeyGem/blob/main/Text2Video.ipynb)) as an example,

> (a) Find the uploaded Text2Video.ipynb, open it

<img src="resources/fig2.png" width="280">

> (b) Mount Google Drive


> (c) Execute all cells in order for Text2Video.ipynb. After completing implementation, a file 1004-r.mp4 will appear in your Google Drive folder

<img src="resources/fig3.png" width="280">


---
>***Note***: All related materials, including notebooks, models, and output files, are provided in the [Google Drive](https://drive.google.com/drive/folders/16el0arUEDTnPHT7LIU0kU-LIMHWLGvVQ?usp=sharing)


---
## Acknowledgements

This project is based on [Original Project](https://github.com/xinxingwu-uk/MuseTalk/tree/main) licensed under the MIT License.

See [LICENSE](https://github.com/xinxingwu-uk/Colab_Implementation-Dance_ControlNeXt-SVD/blob/main/LICENSE) for details.
