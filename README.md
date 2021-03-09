This repository contains the local_manifests used for Android Open Source Project (AOSP)

Easy "clone and go" repository for a Android Open Source Project build core based.

# Instructions
 1. mkdir ~/android
 2. cd ~/android
 3. repo init -u https://android.googlesource.com/platform/manifest -b \<branch\>
 4. cd .repo
 5. git clone https://github.com/chinhpc/local_manifests.git -b \<branch\>
 6. cd ..
 7. repo sync -c -j$(nproc)
