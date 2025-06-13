# CUDA Bilinear Interpolation for Image Resizing

This project implements a high-performance image resizing algorithm using bilinear interpolation accelerated with CUDA. Designed to optimize processing speed by leveraging GPU parallelism, the system significantly outperforms traditional CPU-based methods. This project's purpose is to test the performance with OpenMP and MPI Implementations made by my group mates. The repository includes the CUDA implementation. Ideal for large-scale or real-time image processing tasks where efficiency and image quality are critical.

Key features:

- CUDA-based parallel bilinear interpolation for image resizing

- Optimized for 512x512 image resolution with extensibility for larger datasets

- Tested in Google Colab environment with performance metrics and visual outputs

# Setup 
1. Download the Images folder in the Github Repo.
2. Open the [CudaAssignment.ipynb](https://github.com/WongPowa/CUDABillinearInterpolation/blob/main/CUDAAssignment.ipynb) in the Github Repo.
3. Select the *Open in Colab* at the top of the page.
4. At the top right's dropdown bar, select change runtime type and ensure that it follows the image below
   ![image](https://github.com/user-attachments/assets/2b790c4d-82c2-4956-b685-7277d75a808a)
5. At the left navigation panel, select the folder icon and upload the images downloaded
6. Run the code by selecting the play icon.

