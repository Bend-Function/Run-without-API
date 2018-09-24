# Run-without-API

Install Run-without-API-py3.whl 

The programm which needs TensorFlow Object Detection API can run in any computer which is not setup the API.

ps：just run test programm


安装Run-without-API-py3.whl 

你就可以在任何没有安装TensorFlow Object Detection API的电脑上运行这个API的检测程序了


object_detection_tutorial.py & test_images is a test programm & test images.

You shuld download them tegother and let them in a same folder.

if you see two images which have sign after you run the programm(maybe it will cost you 1 min)

It shows the package was installed successfuly.


object_detection_tutorial.py & test_images 这是测试的程序

你必须一起下载，并放在一个文件夹下

如果你在程序运行最后看到两张带标注的图片（大概一分钟）

那么说明这个"库"安装成功了



The using method of this package:

using:

from obapi import label_map_util

from obapi import visualization_utils as vis_util


instend：

from utils import label_map_util

from utils import visualization_utils as vis_util

or

from object_detection.utils import label_map_util

from object_detection.utils import visualization_utils as vis_util


使用这个“库”的方法：

使用

from obapi import label_map_util

from obapi import visualization_utils as vis_util


替换：

from utils import label_map_util

from utils import visualization_utils as vis_util

或

from object_detection.utils import label_map_util

from object_detection.utils import visualization_utils as vis_util



Also,you have to install Tensorflow & PIL(pillow) & matplotlib.they will using in demo.


当然，您必须安装Tensorflow & PIL(pillow)和matplotlib。他们将在demo中使用。
