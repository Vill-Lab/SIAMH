# SIAMH
code for Similarity-preserving Iterative Asymmetric Mutual Hashing for Fast Person Re-identification  
Training details for differnet lenght of hash codes are shown in the folder of training logs.  
Train: python tools/train_net.py --config-file configs/Market1501/myconfig.yml --teacher-config-file configs_teacher/Market1501/myconfig.yml  
Test:  python tools/train_net.py --config-file configs/Market1501/myconfig.yml --teacher-config-file configs_teacher/Market1501/myconfig.yml --eval-only MODEL.WEIGHTS /path/to/checkpoint_file
