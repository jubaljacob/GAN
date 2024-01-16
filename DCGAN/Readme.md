
## Simple GAN
I have implemented a DCGAN(Deep Convolutional Generative Adversarial Network) system  on the MNIST dataset using PyTorch and Tensorboard.

![Screenshot 2024-01-17 012931](https://github.com/jubaljacob/GAN/assets/71512643/b7ece285-6cb6-48cc-b53a-7389e638c8d5)
![Screenshot 2024-01-17 012936](https://github.com/jubaljacob/GAN/assets/71512643/9374e9db-66d0-4b8f-b580-ac3e432dc43d)


## Prerequisites

Make sure you have the following dependencies installed:

- Python 3.x
- PyTorch
- torchvision
- Tensorboard

Install the required packages using:

```bash
pip install torch torchvision tensorboard 
```


## Usage

1. **Clone the repository:**

   ```bash
   [git clone https://github.com/jubaljacob/GAN.git](https://github.com/jubaljacob/GAN/new/main/DCGAN)
   ```

2. **Run the DCGAN training script:**

   ```bash
   python train.py
   ```

   This will train the GAN on the MNIST dataset and save the generated images in the `output/` directory. Tensorboard logs will be stored in the `logs/` directory.

3. **Monitor training progress using Tensorboard:**

   ```bash
   tensorboard --logdir=logs/
   ```

   Open your browser and navigate to `http://localhost:6006/` to view the training metrics and generated images.

## Hyperparameters

While I have stopped at 5 epochs. You can modify the hyperparameters in the `train.py` file to experiment with different configurations, such as learning rate, number of epochs, batch size, etc.
