# Face_Dector using Web Cam Stream

The Repository consists of the files required to run a Face detector algorithm on Web Cam Streams

## Setup

### Fork
1. Click fork on the top right.
2. Select namespace, choose your username.
3. Select Visibility to Private.
4. Click Fork Project.

### Clone Repo to Local Machine
1. Copy the clone with the HTTPS link.
2. Open a terminal in Ubuntu.
3. Using the terminal, navigate to a folder where you want to save the homeworks.
4. Install Git, Clone repo, set upstream.

After cloning the repo, run the following command in the directory where the repo was Cloned
```bash
python3 face_web_cam_dector.py -p deploy.prototxt -m res10_300x300_ssd_iter_140000_fp16.caffemodel -c 0.5

