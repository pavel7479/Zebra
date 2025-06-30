# Zebra
## Структура датасета
## My_First_Project.v4i.yolov11/
#├── train/
#│   ├── images/
#│   ├── labels/
#├── valid/
#│   ├── images/
#│   ├── labels/
#├── test/
#│   ├── images/
#│   ├── labels/
#├── data.yaml

Код запускается последовательно.
Внимание обратить на пути:
path_dataset = '/content/drive/MyDrive/Zebra/My_First_Project.v4i.yolov11'
project_dir = '/content/drive/MyDrive/Zebra/Results'
model = YOLO('/content/drive/MyDrive/Zebra/Results/exp1/weights/best.pt')
у вас они будут другими
