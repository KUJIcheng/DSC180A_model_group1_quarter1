# Weekly Course Labs Repository

This repository contains experimental code and data for weekly labs from week 2 to week 4. Each week is organized into separate folders (`week_2`, `week_3`, `week_4`), containing experiments or tests completed during that week along with some function implementations for discussions.

## Repository Structure

- **week_2**: Includes download instructions and simulations for calculating LLaMA parameters by passing the corresponding parameters.
- **week_3**: Contains code for calculating FLOPs and Peak Memory. The package used for FLOPs calculation did not yield ideal results.
- **week_4**: Contains tests on Memory Usage for training and inference of the LLaMA2-7b model under FP32 and mixed precision. This helps the group explore how to calculate Memory Usage. All data is stored in the `Experiment_result` folder, while code is in the `Experiment_code` folder.

## Installation

To set up your environment to run the experiments, you will need to install the following packages:

```bash
pip install transformers torch
pip install pytorch_memlab
```

Make sure you have the necessary hardware and software to support these installations, especially if you are planning to run models that require GPU support.

## Environment Variables

Before running the experiments, you are free to set the environment variable to disable Hugging Face Hub symlinks warning:

```bash
export HF_HUB_DISABLE_SYMLINKS_WARNING="1"
```

## Additional Notes

- Ensure that you have activated the appropriate Python environment before executing any scripts if you are using virtual environments or conda.