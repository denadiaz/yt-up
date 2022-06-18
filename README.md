# Directly upload media from Google drive to Youtube using google colab
email: denadiaz@proton.me

As a deep learning enthusiast re-implemneting models using the google colab environment,
i aim to keep my operations/implementation on the internet as much as possible especially data heavy ones like video upload

Youtube uploader is python 2 script that will upload your machine learning output video especially computer vision from 
google colab to youtube using Youtube API V3

# Pre-requisities
Youtube Developer account/console (https://console.developers.google.com) \
Youtube API V3 Enabled\
Client ID/Secret Key(See tutorial google)

# Dependencies
The script shall automatically install all the dependencies 

# Running from Live Notebook in Google Colab
!git clone https://github.com/denadiaz/yt-up.git \
!cd yt-up\
!python yt-up/setup.py\
!python2 yt-up/upload.py
