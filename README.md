# MuseTalk-Colab_Implementation

Here we provided ***a Google Colab implementation*** of ControlNeXt-SVD-v2.

---
## Description

ControlNeXt-SVD-v2 is a deep learning framework for image animation. It is specifically designed to generate realistic video sequences by animating a single input image of a person according to a driving pose sequence—such as a video of someone dancing or performing movements. Given a source image and a reference motion sequence, ControlNeXt-SVD-v2 synthesizes a new video where the person in the image faithfully follows the provided poses.

---
## Examples

### Postive case
<table class="center">
<tr>
    <td width=50% style="border: none">
        Input
    </td>
    <td width=50% style="border: none">
        Output
    </td>
</tr>

<tr>
    <td width=50% style="border: none">
        <img src="resources/a.png" width="680">
    </td>
    <td width=50% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/88730187-5ee5-4fca-9330-8c1c85cb0ade" muted="false"></video>
    </td>
</tr>
</table>


<table class="center">
<tr>
    <td width=50% style="border: none">
        Input
    </td>
    <td width=50% style="border: none">
        Output
    </td>
</tr>

<tr>
    <td width=50% style="border: none">
        <img src="resources/b.png" width="680">
    </td>
    <td width=50% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/4ffee606-6829-4605-9c0b-068c2d9e709d" muted="false"></video>
    </td>
</tr>
</table>


<table class="center">
<tr>
    <td width=50% style="border: none">
        Input
    </td>
    <td width=50% style="border: none">
        Output
    </td>
</tr>

    
<tr>
    <td width=50% style="border: none">
        <img src="resources/c.jpg" width="680">
    </td>
    <td width=50% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/0e43d1b5-d35a-4bab-843a-72dc51477e3a" muted="false"></video>
    </td>
</tr>
</table>


<table class="center">
<tr>
    <td width=50% style="border: none">
        Input
    </td>
    <td width=50% style="border: none">
        Output
    </td>
</tr>

<tr>
    <td width=50% style="border: none">
        <img src="resources/d.jpg" width="680">
    </td>
    <td width=50% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/a9f3e2e8-ecd4-4eef-a3ec-bb3ca490b88d" muted="false"></video>
    </td>
</tr>
</table>

<table class="center">
<tr>
    <td width=50% style="border: none">
        Input
    </td>
    <td width=50% style="border: none">
        Output
    </td>
</tr>

<tr>
    <td width=50% style="border: none">
        <img src="resources/f.png" width="680">
    </td>
    <td width=50% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/ae973465-10f3-4906-9b20-fbfd190f6407" muted="false"></video>
    </td>
</tr>
</table>

---
### Negative case

> We observed that the model performs suboptimally when tested on animal images. This is likely because the underlying model was trained predominantly on human-centric datasets. As a result, its ability to generalize to animals is limited, and outputs may be less accurate or realistic in these cases.

<table class="center">
<tr>
    <td width=50% style="border: none">
        Input
    </td>
    <td width=50% style="border: none">
        Output
    </td>
</tr>

<tr>
    <td width=50% style="border: none">
        <img src="resources/e.jpeg" width="680">
    </td>
    <td width=50% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/b10e5ee1-21b8-4118-91e5-80f346ed0622" muted="false"></video>
    </td>
</tr>
</table>


---
## 🔥 Procedures - Implementation in Colab

Setting in Colab: In the implementation, used A100GPU in Colab as follows

<img src="resources/fig2.png" width="280">

---

* ***Step 1***: Download the ipynb file https://github.com/xinxingwu-uk/Colab_Implementation-Dance_ControlNeXt-SVD/blob/main/DownloadModel.ipynb from the GitHub repository, then upload it to your Google Drive.

* ***Step 2***: In Google Drive, open the ipynb file by Google Colab

* ***Step 3***: Implement the ipynb file in Google Colab - Run all cells in the notebook to set up and download the project. 

* ***Step 4***: After execution, check your Google Drive in the same folder where the notebook is located. The whole project should now be available there - Google Drive folder: ControlNeXtSVDv2.

* ***Step 5***: Find the ipynb file Test.ipynb (https://github.com/xinxingwu-uk/Colab_Implementation-Dance_ControlNeXt-SVD/blob/main/Test.ipynb) in your Google Drive, right-click, and open it with Google Colab. Then, run through the notebook step by step:

> (a) Find Test.ipynb, open it

  <img src="resources/fig1.png" width="280">

> (b) Mount Google Drive

  <img src="resources/fig3.png" width="280">

> (c) Execute all cells in order. After completing implementation (set up the model and dependencies, etc.), an outputs folder will appear in your Google Drive.
You can find the generated results (such as output videos) in this folder.

  <img src="resources/fig0.png" width="280">

---
>***Note***: All related materials, including notebooks, models, and output files, are provided in the [Google Drive](https://drive.google.com/drive/folders/1zgomM77AcOfVmfVe0pVwe_TSkoyZaEXa?usp=sharing)

---
## Acknowledgements

This project is based on [Original Project](https://github.com/xinxingwu-uk/MuseTalk/tree/main) licensed under the MIT License.

See [LICENSE](https://github.com/xinxingwu-uk/Colab_Implementation-Dance_ControlNeXt-SVD/blob/main/LICENSE) for details.
