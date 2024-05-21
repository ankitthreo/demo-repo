# Demo

run the followings
```sh
pip install -r requirements.txt
cd Hello
```
for single step reaction use `run_one.sh` and for multistep use `run_multi.sh`. Both these files need 5 set of arguments: master_seed (for training data shuffling), pytorch_seed (to get the same initialization), data_id (for example, for NS0 it's 25, for GP it's 0, etc.), split_id and GPU_id. For better clarity, it's recommended to watch those files. All the arguments provided in those files are used to get our main trained model. Modify accordingly to train your datasets. You can use `rand_run.py` with our default running seed values to get the trained models to reproduce the result.
```
python rand_run.py $GPU_id
```
For example, `python rand_run.py 0`.

Description: will be added soon!
