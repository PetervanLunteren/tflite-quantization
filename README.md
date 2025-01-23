# tflite-quantization
Forked and adjusted from https://github.com/sanchit88/tf_model_quant. Model quantization using TFLite. 

You can convert models with `model_optimization_tflite.ipynb`.

### Installation
```
cd tf_model_quant
conda create --name quant_env -y
conda activate quant_env
conda install python==3.7.6 -y
pip install -r requirements.txt
pip install protobuf==3.20.*
pip install h5py==2.10.0 --force-reinstall
pip install scikit-learn
```
