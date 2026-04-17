This source code is for the MC-TSE-TP model proposed in the paper, entitled Trajectory Prediction with Motion Control Model and Temporal Evolution Fusion for Multi-Agent Flocking Control Under Communication Attacks.
In the zip file, trajectory_generator.py file is used to generate the sample data for training the MC-TSE-TP model;
trajectory_predict.py file is used to train the MC-TSE-TP model, the parameter "reduction" of loss function in the file is set to reduction="sum", but in the training of the paper, the parameter is set to reduction="mean";
trajectory_predict_test.py file is used to test the MC-TSE-TP model;
RNN.py file provides the agent motion model;
"*.pth" files (such as: predict_model_ST_len10_V6.pth) are trained MC-TSE-TP model;
GCN_4_obs_DDPG_v3_dist_attation_reward_v4.py file in class_pack file folder provides the MC-TSE-TP network model;

We will optimize this project in the future.
