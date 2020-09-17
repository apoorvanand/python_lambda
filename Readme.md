create a folder same name as lambda function and put the code into folder
open terminal and go one folder up and install dependency for python 3.6 --> pip3 install {packagename} -t "foldername"
aws lambda update-function-code --function-name demoapp --zip fileb://demoapp.zip
packages :
https://files.pythonhosted.org/packages/e6/de/a0d3defd8f338eaf53ef716e40ef6d6c277c35d50e09b586e170169cdf0d/pandas-0.24.1-cp36-cp36m-manylinux1_x86_64.whl
https://files.pythonhosted.org/packages/f5/bf/4981bcbee43934f0adb8f764a1e70ab0ee5a448f6505bd04a87a2fda2a8b/numpy-1.16.1-cp36-cp36m-manylinux1_x86_64.whl
pip3 install joblib

Ref :
https://medium.com/@korniichuk/lambda-with-pandas-fd81aa2ff25e





