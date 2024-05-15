# SNU_FastMRI_Challenge_Yoongon
Under the 'FastMRI_Challenge' folder, all the project files exist.
- The 'train.py' file is for a training process of the deep learning model(VarNet)
- The 'reconstruct.py' is for a testing process of the trained model. It utilizes the leaderboard data set, which is different from the training data set.
- The 'leaderboard_eval.py' is for the calculation of the SSIM loss value of the tested model.
- The modules for data loading, training/testing, and the VarNet model are included in the 'utils' folder.

## Reference
[1] Zbontar, J.*, Knoll, F.*, Sriram, A.*, Murrell, T., Huang, Z., Muckley, M. J., ... & Lui, Y. W. (2018). fastMRI: An Open Dataset and Benchmarks for Accelerated MRI. arXiv preprint arXiv:1811.08839.

[2] Sriram, A.*, Zbontar, J.*, Murrell, T., Defazio, A., Zitnick, C. L., Yakubova, N., ... & Johnson, P. (2020). End-to-End Variational Networks for Accelerated MRI Reconstruction. In MICCAI, pages 64-73.

[3] Ronneberger, O., Fischer, P., & Brox, T. (2015, October). U-net: Convolutional networks for biomedical image segmentation. In International Conference on Medical image computing and computer-assisted intervention (pp. 234-241). Springer, Cham.
