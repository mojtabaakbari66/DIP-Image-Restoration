# DIP-Image-Restoration
Wiener filter implementation in python with auto selection k based on best PSNR and MSSIM
This is a practice for Digital Image Processing (Gonzalez 4th ed. book) that automatically estimate best K value in wiener filter eq.

There is two value for K:
   1. K for best image MSSIM score 
   2. K for best PSNR

As you can see, their values are not equal, but they are close to each other.

![final_result](https://user-images.githubusercontent.com/73604520/230790797-fe2395c3-7fb4-4bd0-8330-a1008385313d.jpg)

![final_result](https://user-images.githubusercontent.com/73604520/230790779-c34b850e-5e01-450e-beaf-53255aad4530.jpg)
