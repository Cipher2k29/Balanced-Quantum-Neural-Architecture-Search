# Balanced-Quantum-Neural-Architecture-Search
This repository contains the code implementation for the paper "Banlanced Quantum Neural Architecture Search".

[BQNAS paper](https://doi.org/10.1016/j.neucom.2024.127860)

![BQNAS Framework:](https://github.com/XDU-AI-LYYLab/BanlancedQNAS/assets/40205661/aa180358-4d90-4e92-ba19-adfb465bbeb8)

# Usage
pytorch 1.12

The configs can be adjusted in lib/config_file/
Search stage:
```Shell
python search_example.py
```

Training stage:
```Shell
python evaluate_example.py
```


# Citation
If you find this code implementation useful in your research, please consider citing the following paper:
```
@article{li2024balanced,
    title={Balanced quantum neural architecture search},
    author={Li, Yangyang and Liu, Guanlong and Zhao, Peixiang and Shang, Ronghua and Jiao, Licheng},
    journal={Neurocomputing},
    volume={594},
    pages={127860},
    year={2024},
    publisher={Elsevier}
}
```
