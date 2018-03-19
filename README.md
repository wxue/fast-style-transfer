## Fast Style Transfer

Forked from [Lengstrom's Original Repo](https://github.com/lengstrom/fast-style-transfer)

#### Run on OS X / Linux

Create conda env

```
conda create --name <env> --file requirements.txt
```

Active conda env

```
source activate <env>
```

Install Tensorflow

```
pip install tensorflow
```

Run

```
python evaluate.py --checkpoint ./checkpoints/udnie.ckpt --in-path ./input/test.jpg --out-path ./output/output_test_udnie.jpg
```
