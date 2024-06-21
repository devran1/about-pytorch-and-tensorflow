
### torch without cpu download






put inside the requirements.txt file

python3.7 (maybe)
```
--find-links https://download.pytorch.org/whl/torch_stable.html

torch==1.6.0+cpu

torchvision==0.7.0+cpu
```
python3.11
```
--find-links https://download.pytorch.org/whl/torch_stable.html

torch==2.0.0+cpu

torchvision==0.15.0+cpu
```




### tensorflow without cpu download


```
tensorflow-cpu==2.7.0
tensorflow-cpu==2.10.0
```
if you need to change anything with compat instead off adding compat to every line just add the code below
```
import tensorflow.compat.v1 as tf
tf.disable_v2_behavior()
```
#### installing from requirements.txt use

```
pip install -r requirements.txt
```
#### for uninstaling

```
pip uninstall -r requirements.txt -y
```
#### open3d 

open3d  (408.6 MB) #python3.7

record3d maybe I can use them in slam???



#### how do you install tkinter

```
sudo apt-get install python3.7-tk
sudo apt-get install python3.11-tk python3-dev 
sudo apt-get install python3-tk python3-dev
```

----------------------------

no matter what you are downloading start it or make it work in an environment

(github repos work in virtualenv (environments) and the things you build works in environments )
```
python environment
virtualenv env
source env/bin/activate
```
or 
```
sudo apt install python3.12-venv
```
```
python3.11 -m venv env
source env/bin/activate
```

then copy the files inside of the environment

after that download requirements ....etc
```
pip -r install requirements.txt
```
