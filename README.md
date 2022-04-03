# Prerequisite
run `pip install` to install the following packages 
- humanfriendly
- jsonpickle
- tensorflow-gpu (tested on tensorflow-gpu==2.2.0)

run `git clone` to download the following repo
- `git clone https://github.com/microsoft/CameraTraps/`
- `git clone https://github.com/microsoft/ai4eutils/`

MegaDetector is used to detect objects in the image, dowload the network model using the link
-  `wget https://lilablobssc.blob.core.windows.net/models/camera_traps/megadetector/md_v4.1.0/md_v4.1.0.pb`

All folders should be in the same directory level as scripts folder.

# How to run the jupyter notebook
- Simply open the notebook and start running, ensure to use GPU to accelerate inference