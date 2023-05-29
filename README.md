# rk3566_logo_generator
For adding your own boot logo for ArkOS for supported rk3566 devices

# Instructions for creating a kernel with your custom logo
1. Fork this repository
2. From your forked repository, go to Actions.
3. Click on **ArkOS Kernel with Logo Generator** under Actions on the left side of the screen.
4. On the right side, Click on Run workflow.
5. Select your Device
6. Paste the HTML link to the png image that should be downloaded to generate the current kernel with your preferred logo.
7. Wait 15-20 minutes or so.  If all goes well, The workflow should end with a green checkmark.
8. Click on the workflow and scroll down tot he Artifacts section.
9. Click on the image file and download it.
10. Open the image.zip file and transfer the Image (kernel) file in it to the fat32 boot partition on your sd card overwriting the existing one.
11. Boot your device and verify your logo appears during boot.

Notes:
- Only images in .png format will work and are possible for use in this process
- PNG logos for the RG353M/V/VS and RK2023 need to be in 640x480 resolution
- PNG logos for the RG503 need to be in 960x544 resolution
- This process has successfully been tested with images loaded to [imgbb](https://imgbb.com/upload) and [pasteboard.co](https://pasteboard.co/)

### Uploading png images to imgbb.com
 1. Go to [imgbb](https://imgbb.com/upload) and click on the **start uploading** button.
 2. Select your .png file from your local computer.
 3. Select your auto delete timeframe if you don't want your image stored at the site forever.
 4. Click Upload.
 5. Copy the link shown and use that for step 6 in the instructions above for creating a kernel with your custom logo.

### Uploading png images to pasteboard.co
 1. Go to [pasteboard.co](https://pasteboard.co/) and click on the green **Or Select Image** button.
 2. Select your .png file from your local computer.
 3. Click Upload.
 4. Copy the link shown and use that for step 6 in the instructions above for creating a kernel with your custom logo.
