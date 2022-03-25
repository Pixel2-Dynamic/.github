# Pixel 2 Dynamic Partition Project  
## By Lunarixus & Contributors  
> You're either working hard or hardly working.  

# What is the aim of this project?  
As of Android 12 we're beginning to really have to spare space within the system image  
as we do not have the space to store things such as Gapps within the ROM. To try and  
combat the early retirement of Pixel 2/2 XL devices I have decided to take inspiration  
from Google's use of retrofit partitions on Pixel 3 devices and attempt to backport it.  

# Requirements  
Obviously this project isn't something that is going to just 'slot in' on normal devices:
- You need to be repartitioned (script WIP)

# Warnings  
With the release of PixelExperience 12 by PixelBoot there is also a new repartitioning script  
created by him with the intent to make system partitions bigger, **do not** attempt to use that  
script if you intend on using anything from this project as we require product_a and product_b  
instead of larger system partitions.  

# How to build  
Currently this organisation only hosts trees for AOSP 11, instructions coming soon.  

# Which repos are which?  
device_google_wahoo -> Pixel 2/2 XL Common Tree, clones to device/google/wahoo  
device_google_wahoo-kernel -> Pixel 2/2 XL Common Kernel Prebuilts & Modules  
device_google_taimen -> Pixel 2 XL Specific Tree, clones to device/google/taimen  
~~device_google_walleye -> Pixel 2 Specific Tree, clones to device/google/walleye~~  
android-kernel_private_msm-google -> Pixel 2/2 XL Common Kernel Source, clones to private/msm-google  
vendor_google_taimen -> Pixel 2 XL Specific Vendor Blobs, clones to vendor/google/taimen  
~~vendor_google_walleye -> Pixel 2 Specific Vendor Blobs, clones to vendor/google/walleye~~  

# Current Status  
device_google_wahoo: WIP  
~~device_google_wahoo-kernel: WIP~~  
device_google_taimen: WIP  
~~device_google_walleye: WIP~~  
android-kernel_private_msm-google: WIP  
vendor_google_taimen: WIP  
~~vendor_google_walleye: WIP~~  

# Credits  
- Google (obviously)
- Lunarixus
