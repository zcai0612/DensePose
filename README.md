# DensePose
DensePose for DeepFash datasets

## Weights
Download the weight and put it into the directory `weights\`
Download links: https://pan.baidu.com/s/1cnq_iJSkDMT6s_BrDRXkxQ?pwd=1ta7 

## Commands
```
            "args": [
                "show", "--output", "outputs/",
                "configs/model_final_844d15.yaml",
                "weights/model_final_844d15.pkl", "inputs/",
                "dp_segm", "-v"
            ]
```
Where `outputs/` is the output files directory and `inputs/` is the inputs files directory.
You can run the examples through:
```
python apply_net.py show --output outputs/ configs/model_final_844d15.yaml weights/model_final_844d15.pkl inputs/ dp_segm -v
```