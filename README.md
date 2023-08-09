# MGPFD (Multi-Goal Path Finding Dataset)
This is a dataset for multi-goal path finding problem, including a training dataset and a simulation dataset.


************Training Dataset************
    - For learning-based methods (like S&Reg[1]) to solve the MGPF problem
    - Including promising region segmentation, guideline prediction, and length regression
    - Details of the learning-based methods refer to [1]
    
    
    
************Simulation Dataset[updating]************
    - For test the performance of MGPF algorithms
    - Including seen scenarios and unseen senarios
    - parts of unseen scenarios stem from [2]
    
    
    
    
Reference 

[1]@misc{huang2023sreg,
      title={S&Reg: End-to-End Learning-Based Model for Multi-Goal Path Planning Problem}, 
      author={Yuan Huang and Kairui Gu and Hee-hyol Lee},
      year={2023},
      eprint={2308.04160},
      archivePrefix={arXiv},
      primaryClass={cs.RO}
}

[2]Wang. Satellite buildings semantic segmentation data (version
6). (2021). [Online]. Available: https://www.kaggle.com/datasets/hyyyrwang/buildings-dataset
