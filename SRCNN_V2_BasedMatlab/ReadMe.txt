这个代码是先利用MATLAB的bicubic插值得到低分辨率图像，然后再利用python进行超分辨率重建。
generate_h5_testdata.m是生成测试所需要的MATLAB插值结果，main_predict_matlab.py是采用SRCNN作者的方法进行重建的。
main_predict_python.py是采用python的方法进行重建的。
训练过程就不写了，都是采用作者训练好的结果。