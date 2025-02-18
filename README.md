# tflite-quantization
Forked and adjusted from https://github.com/sanchit88/tf_model_quant. Model quantization using TFLite. 

First train a `.h5` model in the conda env below, then quantise with `model_optimization_tflite.ipynb`.

### Installation
```
git clone https://github.com/PetervanLunteren/tflite-quantization.git
cd tflite-quantization
conda create --name quant_env -y
conda activate quant_env
conda install python==3.7.6 -y
pip install -r requirements.txt
pip install protobuf==3.20.*
pip install h5py==2.10.0 --force-reinstall
pip install scikit-learn
```
