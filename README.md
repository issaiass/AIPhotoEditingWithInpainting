# 1 - Project Overview
-    ### 1.1 - Project Introduction
     Generative models can be used in Computer Vision.  Here we will use the Meta Segment Anything Model (SAM) to select subjects in images by providing points and other inputs.

     Also we have an app able to swap the backgroupd of an image nd susbstitute it with a computer-generated one described through text.

-    ### 1.2 - Project Summary
     Our goal is to do an app that allows the selection of a subject and then change its background, OR keep the background and change the subject.

     The process involves a user uploading an image and selecting the main object by clicking on it. The Segment Anything Model (SAM) is activated to create a mask around the selected object, choosing the most accurate mask generated. The user is shown this result to either accept it or refine the mask further with additional points. Once the mask is finalized, the user gives a text description (and possibly a negative prompt) to specify a new background for the selected object. An infill model then creates this new background, and the final image is displayed. Optionally, the user can choose to invert the mask and substitute the subject while keeping the background, as in the example above.

     The goal of the application is to swap backgrounds, swap subjects, remove objects, and more!

     The main goal of the notebook is to write the basic functionality of the app: calling the SAM model and processing its output, as well as using a text2image diffusion model to generate the new background or subject.

## 2 - Project Instructions
- Load the Jupyter notebook.
- Follow the instructions contained there step by step running each line.
- The gradio app allows an interactive experience as is on the results images below in four (4). We will be able to start it from within the notebook. Then, by clicking on a link, you will be taken to a new tab with the gradio UI available for use.
- I suggest you to improve the results changing the Classifier-Free Guidance Scale (CFGS) or the random seed - which you now understand - and see which results you get.

## 3 - App instructions
- When finished the notebook, the app will be launched and can be excecuted via the link or inside the noteboook.

<details open>
<summary> <b>4 - Results<b></summary>

Some images that exemplify the results of the notebook
- From Clint Eastwood to Leonardo Di Caprio

![Client2DiCaprio](imgs/inpaint1.png "From Clint Eastwood to Leonardo Di Caprio")

- From That 70's Show to The Jackson's 5

![Client2DiCaprio](imgs/inpaint2.png "From Clint Eastwood to Leonardo Di Caprio")


<p align="center"> </p>
</details>

<details open>
<summary> <b>Issues<b></summary>

- no issues found yet.

</details>

<details open>
<summary> <b>Future Work<b></summary>

- None

</details>

<details open>
<summary> <b>Contributing<b></summary>

Your contributions are always welcome! Please feel free to fork and modify the content but remember to finally do a pull request.

</details>

<details open>
<summary> :iphone: <b>Having Problems?<b></summary>

<p align = "center">

[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/riawa)
[<img src="https://img.shields.io/badge/telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white"/>](https://t.me/issaiass)
[<img src="https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white">](https://www.instagram.com/daqsyspty/)
[<img src="https://img.shields.io/badge/twitter-%231DA1F2.svg?&style=for-the-badge&logo=twitter&logoColor=white" />](https://twitter.com/daqsyspty) 
[<img src ="https://img.shields.io/badge/facebook-%233b5998.svg?&style=for-the-badge&logo=facebook&logoColor=white%22">](https://www.facebook.com/daqsyspty)
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/riawe)
[<img src="https://img.shields.io/badge/tiktok-%23000000.svg?&style=for-the-badge&logo=tiktok&logoColor=white" />](https://www.linkedin.com/in/riawe)
[<img src="https://img.shields.io/badge/whatsapp-%23075e54.svg?&style=for-the-badge&logo=whatsapp&logoColor=white" />](https://wa.me/50766168542?text=Hello%20Rangel)
[<img src="https://img.shields.io/badge/hotmail-%23ffbb00.svg?&style=for-the-badge&logo=hotmail&logoColor=white" />](mailto:issaiass@hotmail.com)
[<img src="https://img.shields.io/badge/gmail-%23D14836.svg?&style=for-the-badge&logo=gmail&logoColor=white" />](mailto:riawalles@gmail.com)

</p>


</details>

<details open>
<summary> <b>License<b></summary>
<p align = "center">
<img src= "https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg" />
</p>
</details>