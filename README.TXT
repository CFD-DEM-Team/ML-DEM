Step1. install & run the following code:
The code works with TensorFlow and PyTorch. I used TensorFlow.
https://github.com/isl-org/DeepLagrangianFluids

Step2, Setup & run DEM cases to generate Training & Testing Data
e.g. set up cases using Nodeworks,hopper_h040

Step3, convert MFiX output to compressed records using:
code/DeepLagrangianFluids/datasets/post_mfix.sh

Step4, Train the model
code/DeepLagrangianFluids/scripts/trainHopperLoss5frames.py

Step5, Test the model
code/DeepLagrangianFluids/scripts/test_hopper5cm_h035.sh

Step6, Post-Processing
scripts in post
