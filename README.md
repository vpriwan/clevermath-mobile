A repository of the original clevermath-org/clevermath-mobile.

This clevermath-mobile is created by Unity. There are atleast 8 files larger than 100MB.
So we have to use Git LFS to upload the files.

Reference from https://docs.github.com/en/github/managing-large-files/about-storage-and-bandwidth-usage
"About storage and bandwidth usage
Every account using Git Large File Storage receives 1 GB of free storage and 1 GB a month of free bandwidth. If the bandwidth and storage quotas are not enough, you can choose to purchase an additional quota for Git LFS."
=> Bandwidth only effected from DOWNLOADING.
=> If we don't want to pay for the additional quota fee, we have to be careful on downloading large files.

For the first time to downloadin the original files, because of 1GB a month of the large file limitations, and because the large files in this project totally are more than 1.2GB, so we have to separately downloading the large files.

The project will mostly keep tracking the most neccessary part, Assets/C4Gamekit, so maybe we should:
- Download Assets/C4Gamekit from this repository
- Downloading the rest of the project from Google Drive.


= = = = = = = = = = = =
Reference from https://docs.github.com/en/github/managing-large-files/about-storage-and-bandwidth-usage

** Bandwidth only be caculated from downloading the large files. So we should be careful and try to avoid downloading large files directly from this repository as possible as we can. **

"Tracking storage and bandwidth use

When you commit and push a change to a file tracked with Git LFS, a new version of the entire file is pushed and the total file size is counted against the repository owner's storage limit. When you download a file tracked with Git LFS, the total file size is counted against the repository owner's bandwidth limit. Git LFS uploads do not count against the bandwidth limit.

For example:

    If you push a 500 MB file to Git LFS, you'll use 500 MB of your allotted storage and none of your bandwidth. If you make a 1 byte change and push the file again, you'll use another 500 MB of storage and no bandwidth, bringing your total usage for these two pushes to 1 GB of storage and zero bandwidth.
    If you download a 500 MB file that's tracked with LFS, you'll use 500 MB of the repository owner's allotted bandwidth. If a collaborator pushes a change to the file and you pull the new version to your local repository, you'll use another 500 MB of bandwidth, bringing the total usage for these two downloads to 1 GB of bandwidth."
