# Over and Underexposed Dataset

Our image dataset which contains images of various exposures as well as the original images.

We utilized the dataset in pix2pix_application.ipynb to both train and test on.

## Installation
```bash
## The following command downloads the dataset from Google Drive

!wget --load-cookies /tmp/cookies.txt "https://docs.google.com/uc?export=download&confirm=$(wget --quiet --save-cookies /tmp/cookies.txt --keep-session-cookies --no-check-certificate 'https://docs.google.com/uc?export=download&id=14CkA9OldSeL5dgzyzT6jRfT3I4jpvWHD' -O- | sed -rn 's/.*confirm=([0-9A-Za-z_]+).*/\1\n/p')&id=14CkA9OldSeL5dgzyzT6jRfT3I4jpvWHD" -O overexposed && rm -rf /tmp/cookies.txt
```
