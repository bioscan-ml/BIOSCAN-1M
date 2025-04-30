# BIOSCAN-1M

BIOSCAN-1M Dataset images. 

###### <h3> Image Access
The original images of the BIOSCAN-1M dataset were captured using a Keyence VHX-7000 Digital Microscope system imaging system at a resolution of 2880×2160 pixels. 
All image packages of the BIOSCAN-1M dataset are available in the [GoogleDrive](https://drive.google.com/drive/u/1/folders/1kD9cXuQ1FdL30etp7sjy_Gs_NAAJ3EXI),
within the following folders:



> **ℹ️ Note**: The original BIOSCAN-1M images are high-resolution RGB JPEGs (2880×2160 pixels), which contribute to large package sizes.
For the BIOSCAN-5M dataset, these images were resized to 1024×768 pixels (referred to as original_full), significantly reducing the overall package size.

| **Folder Name**              | **Description**                                                           | **File Format / Name**                                |
|-----------------------------|---------------------------------------------------------------------------|--------------------------------------------------------|
| `BIOSCAN_1M_original_images` | Original full-size images, split into 113 zip files                       | `bioscan_images_original_full_part{1..113}.zip`        |
| `BIOSCAN_1M_cropped_images`  | Cropped images, split into 113 zip files                                  | `bioscan_images_cropped_full_part{1..113}.zip`         |
| `BIOSCAN_1M_original_256`    | Original images resized to 256 on the smaller dimension (ZIP format)      | `original_256.zip`                                     |
| `BIOSCAN_1M_original_256`    | Original images resized to 256 on the smaller dimension (HDF5 format)     | `original_256.hdf5`                                    |
| `BIOSCAN_1M_cropped_256`     | Cropped images resized to 256 on the smaller dimension (ZIP format)       | `cropped_256.zip`                                      |
| `BIOSCAN_1M_cropped_256`     | Cropped images resized to 256 on the smaller dimension (HDF5 format)      | `cropped_256.hdf5`                                     |


###### <h3> Low-quality images
Low-quality images from the BIOSCAN-1M dataset have been identified and documented. Their corresponding `sampleid`s are listed in the file:

`BIOSCAN_1M_low_quality_images.xlsx`

This file is available in the [GoogleDrive](https://drive.google.com/drive/u/1/folders/1kD9cXuQ1FdL30etp7sjy_Gs_NAAJ3EXI) folder.



