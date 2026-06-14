# TML 2026 Task 3 - Adversarial Robustness

## Recreating the Best Leaderboard Result

Run `resnet34_pgd10.ipynb` on Kaggle with a T4 GPU and internet enabled.

The notebook will automatically download the dataset, train the model, and submit to the leaderboard. Replace `API_KEY` with your actual API key before running.

## Repository Structure

- `resnet18_pgd7.ipynb` — baseline experiment (ResNet18, PGD-7, 100 epochs, batch size 256)
- `resnet34_pgd10.ipynb` — best result (ResNet34, PGD-10, 120 epochs, batch size 128)

Both notebooks contain the same training pipeline. The only differences are the model architecture and the hyperparameters listed above.

## Requirements

All dependencies are installed within the notebooks. No manual setup required.
