## ModuleNotFoundError: No module named 'matcha'

If you encounter the error `ModuleNotFoundError: No module named 'matcha'`, follow these steps to resolve it:

1. **Check the `third_party` Directory**:
   Ensure that the `Matcha-TTS` directory exists within the `third_party` directory of your project.

2. **Initialize Submodules**:
   If `Matcha-TTS` is missing, you need to initialize the Git submodules. Run the following command in your terminal:

   ```sh
   git submodule update --init --recursive

## Cannot Find `resource.zip` or Cannot Unzip `resource.zip`

If you encounter an issue where `resource.zip` cannot be found or cannot be unzipped, follow these steps:

1. **Ensure Git LFS is Installed**:
   Make sure you have Git LFS (Large File Storage) installed. If you haven't installed it yet, follow the [installation instructions here](https://git-lfs.github.com/).

2. **Clone the Repository**:
   Execute the following commands in your terminal to clone the repository:

   ```sh
   git clone https://www.modelscope.cn/iic/CosyVoice-ttsfrd.git pretrained_models/CosyVoice-ttsfrd

