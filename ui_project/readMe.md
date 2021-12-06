# UI for object detection labeling in EVA
### Contributors: Daniel Justice, Haosong Ma, Kevin Perdomo

## What is this project addressing? 

We are addressing the issue of EVA not giving completetly accurate labels for different videos. This Project addresses that by utilizing **Label Studio** [[Github](https://github.com/heartexlabs/label-studio)]. Label Studio provides a labeling platform that is able to be set up programatically from a jupyter notebook. 


#   Set Up

1. Install Eva in the parent directory and follow the steps to set it up.
2. Install Label Studio
    - Option 1: Follow the instructions [*Install Locally Using Anaconda*](https://github.com/heartexlabs/label-studio#install-locally-with-anaconda) **Note**: Pick this option if you do not plan to modify the source code. 
    - Option 2: Alternatively, [*Install for local development*](https://github.com/heartexlabs/label-studio#install-for-local-development) **Note**: Pick this option if plan on modifying the UI
3. Baseds on installation method, open a terminal, activate the eva conda environment, and ***launch Label Studio***.
4. Run through the ui_data_import.ipynb to understand the workflow. 