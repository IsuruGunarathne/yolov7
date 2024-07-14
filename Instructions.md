https://www.youtube.com/watch?v=n2mupnfIuFY&t=1s

## set up conda environment

```bash
conda activate yolov7

## Install dependencies

pip install -r requirements.txt

## normal script

python detect.py --weights yolov7-tiny.pt --conf 0.4 --img-size 640 --source vid360.mp4

## modifited script for visualization

python detect_viz.py --weights yolov7-tiny.pt --conf-thres 0.4 --img-size 640 --source vid360.mp4 --view-img

python detect_viz.py --weights yolov7.pt --conf-thres 0.4 --img-size 640 --source vid360.mp4 --view-img

```
