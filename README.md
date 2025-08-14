# 3D-Gaussian-Splatting-Colab-on-the-fly GOOGLE COLAB NOTEBOOK IMPLEMENTATION

# On-the-fly Reconstruction for Large-Scale Novel View Synthesis from Unposed Images

This repository provides resources and guidance to perform large-scale novel view synthesis from unposed images, based on the work of Meuleman et al. (2025). The aim is to reconstruct high-quality 3D models and generate point clouds from a collection of images.

## Features

- Generate 3D reconstructions from unposed images.
- Output point clouds in .PLY format for visualization.
- Optimized for GPU use in Google Colab.
- Beginner-friendly setup and step-by-step workflow.

## Getting Started

1. **Clone the repository:** Download the project files and submodules to your local environment or Colab session.
2. **Prepare your environment:** Ensure your system has a compatible Python version and GPU drivers.
3. **Install dependencies:** All required Python packages are listed in `requirements.txt`.
4. **Prepare datasets:** Organize your images in folders. Each dataset should have a subfolder called `images` containing your pictures.
5. **Run training:** The repository allows you to train the model on your images to generate 3D reconstructions.
6. **Export results:** After training, the output includes point clouds (.PLY files) that can be visualized in any standard 3D viewer.

## Using Your Own Images

- Create a folder for your dataset (e.g., `Sculpture` or `Structure`).
- Place all your images in the folder’s `images` subfolder.
- The repository will process these images and generate a 3D reconstruction.

## Viewing Outputs

- The output `.PLY` files can be opened in tools like Meshlab, Blender, or online viewers such as [SuperSplat 3D editor](https://superspl.at/editor/).
- For easy sharing, outputs can also be downloaded from Colab or your local machine.

## Recommendations

- **GPU recommended:** For faster processing, especially with large image datasets.
- **Memory management:** Large datasets may require downsampling images or adjusting batch size.
- **Download outputs:** Files stored in Colab are temporary; always download results to preserve them.

## Citation


> Meuleman, A., Shah, I., Lanvin, A., Kerbl, B., & Drettakis, G. (2025). *On-the-fly Reconstruction for Large-Scale Novel View Synthesis from Unposed Images.* ACM Transactions on Graphics, 44(4).

## References

- Meuleman et al., 2025, ACM TOG, 44(4)  
- Mip-NeRF360 dataset: [https://github.com/google/mipnerf](https://github.com/google/mipnerf)  
- SuperSplat 3D viewer: [https://superspl.at/editor/](https://superspl.at/editor/)
