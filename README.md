# crf-image-labeling

Thanks to [snknitin's](https://github.com/snknitin) code of conditional random field model used in ocr, I wrote an api myself based on his code and it is easily used for sequence labeling as shown in my code. </br>
</br>
The code is implemted in numpy and I divided the model and running example into two py documents. In crf_main.py, I used mini-batch sgd with nesterov momentum update, achieving the accuracy of 99% and 95% on training and testing sets, respectively. </br>
