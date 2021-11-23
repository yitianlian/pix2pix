# pix2pix

All have been tested with python3.8 and pytorch 1.10 on Cuda 11.3

- Datasets:BW pictures and the color pictures
- Models.py: contain Generator and discriminator
- pix2pix: the main structure of the network

The project aim at transfer the BW picture to the pictures in color.

**Example**

~~~python
$ cd pix2pix/
$ python3 pix2pix.py
~~~

**Results**

The main problem is gan can't draw the picture in the right types of color.

![image-20211123084456882](C:\Users\谢承兴\AppData\Roaming\Typora\typora-user-images\image-20211123084456882.png)

![138000](E:\pix2pix\images\datasets\138000.png)