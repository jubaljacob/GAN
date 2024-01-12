# GAN Learning Repo

## Overview
Explore my GAN Learning repository, a collection of project files created while learning about Generative Adversarial Networks (GANs).

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
   git clone https://github.com/jubaljacob/GAN.git
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

You can modify the hyperparameters in the `Simple_GAN.py` file to experiment with different configurations, such as learning rate, number of epochs, batch size, etc.

## Acknowledgments

This project is inspired by the original GAN paper by Ian Goodfellow and the official PyTorch tutorials on GANs.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to fork and modify the code to suit your needs! If you encounter any issues or have suggestions, please open an issue or submit a pull request. Happy coding!
