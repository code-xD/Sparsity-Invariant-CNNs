# Sparsity-Invariant-CNNs
This repository contains all the files for you to implement **Sparsity Invariant CNN**. In order to run this project you need to make a Google Drive folder to upload these files in order to work with Google Colab. Open `CNN_v_s_Sparse_CNN_Tf.ipynb
` to run the program.

### How to Setup?

 1. Make a folder `train` in our project **ROOT** directory.
 2. Prepare the dataset now by downloading the [velodyne raw data](https://s3.eu-central-1.amazonaws.com/avg-kitti/data_depth_velodyne.zip)  extracting it in the `train` folder. 
 3. After dowloading the raw_input data download the [groundtruth](https://s3.eu-central-1.amazonaws.com/avg-kitti/data_depth_annotated.zip) and extract it in the same `train` folder.
 4. Make a folder `NNFL Assignment` in your `ROOT_DIR` of Google Drive and upload all the files from your project **ROOT** directory.
 
### Using a local runtime
Change the `ROOT_DIR` to the location of your project **root** in order to run the notebook in a local runtime. We have strictly used Google Colab and Google Drive for developing, running and troubleshooting the whole project so we can't guarantee on using a local runtime.

### Additional Information
1. The checkpoints and log files for different models training will be stored in `Models` folder and in-depth statistics can be found in the `Statistics` folder.
2. Already trained model names can be found in `models.txt` file in `Models` folder however the variables have been initialized in the notebook of already trained models.
3. The graphs and outputs of the network are stored in `Graphs and Output` folder. `Graphs and Output\multi_input_and_output_model.png` contain the flowchart of the network and can be referred to get an idea of the network.
