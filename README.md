# DIC2Cells: A novel deep learning-based tool for cell segmentation in differential interference contrast (DIC) images
Please find the paper here: [OrgaMeas: A high-throughput image analysis pipeline optimized for effectively measuring organellar dynamics in live cells](URL)

## What is this?
DIC2Cells is an user-friendly tool for cell segmentation in DIC images that utilizes the power of deep learning.<br>
We provide a Google Colab notebook (**DIC2Cells.ipynb**), which allows users to test DIC2Cells with their own data without installing the code on their local machine and preparation of high-spec PC.

<img width="1625" alt="スクリーンショット 2024-01-25 15 58 02" src="https://github.com/MitoTAIKI/DIC2Cells/assets/110826399/2046b04e-1bd5-42e9-bf75-534ad9e77923">

## How to use
### 0. Download a Google Colab notebook & pre-trained model<br>
At first, you should download [**DIC2Cells.ipynb**](https://github.com/MitoTAIKI/DIC2Cells) & [**pre-trained model**](URL) from this GitHub site to your local computer.

### 1. Preparation<br>
Create your own [**Google account**](https://accounts.google.com/lifecycle/steps/signup/name?dsh=S1678113772:1706167885430878&flowEntry=SignUp&flowName=GlifWebSignIn&theme=glif&TL=AHNYTIQNkTFicz0QZM45UrHYA9mi96Mh8AjrEx_J1pC8UnfbpU0Y5RtOSwMM9rwm) and open [**Google Drive**](https://drive.google.com/drive/my-drive).<br>

### 2. Structures of the files and folders<br>
<pre>
My Drive
  |ー analysis
  　　　|ー DIC2Cells.ipynb
  　　　|ー DIC2Cells (Upload pre-trained DIC2Cells model)
  　　　|ー test_A (Upload your own DIC images)
</pre>

### 3. Test your own data<br>
Open the DIC2Cells.ipynb file and **click the play buttons**, in order from Step 0.<br>
After the end of step 2, you can find results in **DIC2Cells/test_latest/images**.

## How to train with your own data
Please check [NVIDIA/pix2pixHD](https://github.com/NVIDIA/pix2pixHD) & its [**issues**](https://github.com/NVIDIA/pix2pixHD/issues/138).<br>
If you face the difficulty in coding for your own training or something, please contact to us!

## How to cite this work
