# rk3566_logo_generator
For adding your own boot logo for ArkOS for supported rk3566 devices

# Instructions for creating a kernel with your custom logo
1. Fork this repository
2. From your forked repository, go to Actions.
3. Enable Workflows.
4. Click on **ArkOS Kernel with Logo Generator** under Actions on the left side of the screen.
5. On the right side, Click on Run workflow.
6. Select your Device.
7. Paste the HTML link to the png image that should be downloaded to generate the current kernel with your preferred logo.
   - Images from [imgbb.com](https://github.com/christianhaitian/rk3566_logo_generator#uploading-png-images-to-imgbbcom) or [pasteboard.co](https://github.com/christianhaitian/rk3566_logo_generator#uploading-png-images-to-pasteboardco) are recommended for this process.  See instructions below about how to use either free site.
8. Wait 15-20 minutes or so.  If all goes well, The workflow should end with a green checkmark.
9. Click on the workflow and scroll down to the Artifacts section.
10. Click on the image file and download it.
11. Open the downloaded image .zip file and transfer the Image (kernel) file in it to the fat32 boot partition on your sd card overwriting the existing one.
12. Boot your device and verify your logo appears during boot.

Notes:
- Only images in .png format will work and are possible for use in this process
- PNG logos for the RG353M/V/VS and RK2023 devices Must be 640 pixels in width and 480 pixels in height
- PNG logos for the RG503 must be 960 pixels in width and 544 pixels in height
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
