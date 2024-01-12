## Simple GAN
I have implemented a simple GAN which consists of a very simple Generator and Discriminator implemented on the MNIST dataset using PyTorch and Tensorboard.

![Screenshot 2024-01-13 015545](https://github.com/jubaljacob/GAN/assets/71512643/b2646bd0-2b72-4d0c-9056-ad7cc9a5d14e)
![Screenshot 2024-01-13 015540](https://github.com/jubaljacob/GAN/assets/71512643/b4876ad5-591c-40f7-8bb1-338ac0b4a050)

## Prerequisites

Make sure you have the following dependencies installed:

- Python 3.x
- PyTorch
- torchvision
- Tensorboard

Install the required packages using:

```bash
pip install torch torchvision tensorboard matplotlib
```


## Usage

1. **Clone the repository:**

   ```bash
   [git clone https://github.com/jubaljacob/GAN.git](https://github.com/jubaljacob/GAN/new/main/Simple_GAN)
   ```

2. **Run the simple gan training script:**

   ```bash
   python Simple_GAN.py
   ```

   This will train the GAN on the MNIST dataset and save the generated images in the `output/` directory. Tensorboard logs will be stored in the `logs/` directory.

3. **Monitor training progress using Tensorboard:**

   ```bash
   tensorboard --logdir=logs/
   ```

   Open your browser and navigate to `http://localhost:6006/` to view the training metrics and generated images.

## Hyperparameters

While I have stopped at 50 epochs. You can modify the hyperparameters in the `Simple_GAN.py` file to experiment with different configurations, such as learning rate, number of epochs, batch size, etc.
