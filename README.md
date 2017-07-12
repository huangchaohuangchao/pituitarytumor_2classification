# pituitarytumor_2classification
First:get the ROI pictures by using Matlab. 
Second:convert those pictures into TFRecord. 
Finally: using transforming learn to creat a CNN and use data refine it

##import
images.tostring()//img.tobytes()

tf.int32 no need to have ''       int32 need to have ''

os.listdir(filepath)   we can get all the file name under filepath

open image we can use 'from PIL import Image' and 'Image.open(filename)'

if batch_size is too big, it will be memory leak error

placeholder can't be feed with tensor       we can feed with tensor.eval(session=sess).reshape()

