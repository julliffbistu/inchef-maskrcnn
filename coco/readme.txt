python ./labelme2coco.py --input_dir ./labelme/train2019 --output_dir ./annotations/train2019 --filename instances_train2019 --labels labels.txt



python ./labelme2coco.py --input_dir ./labelme/val2019 --output_dir ./annotations/val2019 --filename instances_val2019 --labels labels.txt



python ./labelme2coco.py --input_dir ./labelme/test2019 --output_dir ./annotations/test2019 --filename instances_test2019 --labels labels.txt
