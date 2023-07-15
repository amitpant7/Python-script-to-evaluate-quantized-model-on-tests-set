# Python-script-to-evaluate-quantized-model-on-tests-set
Dequantizing the Vitis ai quantized model to evaluate its performance on the test set in Pytorch. \\

  -Requires Vitis AI, I have used vitis-ai-pytorch docker container
  -Adjust the directory structure according to or change the dataset file path and model file path.

example: evaluate model on subset of 1000 images from val
```
python eval_quant.py --subset_len 1000
```
