# LPRNet_Pytorch - PyTorch License Plate Recognition

LPRNet_Pytorch is a high-performance and lightweight License Plate Recognition framework implemented in PyTorch. It is designed to fully support Chinese License Plate Recognition as well as license plates from other regions. Currently, it recognizes both blue and green license plates, including new energy vehicle plates in China. The framework is extensible to support other types of license plates with additional training data or fine-tuning.

## 🚀 Features

- **Extensibility:** Easily extend and fine-tune the model for other types of license plates.
- **Performance:** Achieves high accuracy with low inference time.
- **Pretrained Model:** Utilize the provided pretrained model to get started quickly.

## 🛠️ Dependencies

- PyTorch >= 1.0.0
- OpenCV-Python 3.x
- Python 3.x
- imutils
- Pillow
- NumPy

## 🤖 Pretrained Model

Download the pretrained model weights from [here](https://github.com/sirius-ai/LPRNet_Pytorch/tree/master/weights/).

## 🚦 Training and Testing

1. Prepare your datasets, ensuring image size is 94x24.
2. Modify the hyperparameters in the scripts based on your dataset path (`--train_img_dirs` or `--test_img_dirs`).
3. Adjust other hyperparameters as needed.
4. Run 'python train_LPRNet.py' or 'python test_LPRNet.py'.
5. To show testing results, add '--show true' or '--show 1' to the run command.

## 📈 Performance

- Personal test datasets.
- Includes blue/green license plates.
- Diverse images.
- Total test images: 27320.

|  Model Size | Personal Test Images (%) | Inference Time (ms)@GTX 1060 |
| ----------- | ----------------------- | --------------------------- |
| 1.7M        | 96.0+                   | 0.5-                        |

## 📚 References

1. [LPRNet: License Plate Recognition via Deep Neural Networks](https://arxiv.org/abs/1806.10447v1)
2. [PyTorch Documentation (Chinese)](https://pytorch-cn.readthedocs.io/zh/latest/)

## 🌟 Acknowledgments

If you find this project useful, please give it a star. Your support is greatly appreciated!

