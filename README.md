# scaled_yolov4

images and labels need to be in coco format, which are in the drive folder below:
https://drive.google.com/file/d/1JzjJWWtArJumsIpqBjivBlTilw6ICHma/view?usp=sharing

if you want to build your own dataset, images need to be in the images/ folder, and labels need to be in the corresponding labels/ folder
labels need to be in the format (class, x_center, y_center, width, height). these values also need to be normalised, to be values between 0-1
i.e. divide x_center and width by 1280. divide y_center and height by 720
