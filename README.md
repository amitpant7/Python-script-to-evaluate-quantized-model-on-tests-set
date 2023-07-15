# Python-script-to-evaluate-quantized-model-on-tests-set
Dequantizing the vitis ai quantized model to evalaute it's performance on the test set in pytorch. 
-Requires Vitis AI
-Adjust the directory structure according or change dataset file path and model file path.

example: evaluate model on subset of 1000 images from val
```
python eval_quant.py --subset_len 1000
```
