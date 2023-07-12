# Multi-Objective GFlowNets

This repository contains the code for the experiments in [Multi-Objective GFlowNets](https://arxiv.org/abs/2210.12765). The code is split into different folders as follows:

* `mo_gfn` - Consists of the experiments on sequence-based domains (N-grams and DNA Aptamers).
* `mogfn-al` - Consists of the experiments on protein design in the active learning setting with MOGFN-AL.

Please follow the instructions in each directory to run the experiments. You can also clone any specific repo if you are interested in the specific experiment.

To clone all the repos use the `recursive` option while cloning
```bash
git clone https://github.com/GFNOrg/multi-objective-gfn --recursive
```

Please reach out to mokshjn00@gmail.com in case you have any issues. Alternatively you can open an issue on Github.

### Citation
```
@inproceedings{jain2023multi,
  title={Multi-objective gflownets},
  author={Jain, Moksh and Raparthy, Sharath Chandra and Hern{\'a}ndez-Garc{\i}́a, Alex and Rector-Brooks, Jarrid and Bengio, Yoshua and Miret, Santiago and Bengio, Emmanuel},
  booktitle={International Conference on Machine Learning},
  pages={14631--14653},
  year={2023},
  organization={PMLR}
}
```
