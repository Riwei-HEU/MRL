# MRL

**MRL w/o MNS**

python main_sin.py --dataset phone --K 1 --loss mrl --ns dns --n_negs 16 --gpu_id 0

python main_sin.py --dataset sport --K 1 --loss mrl --ns dns --n_negs 16 --gpu_id 0

python main_sin.py --dataset tool --K 1 --loss mrl --ns dns --n_negs 16 --gpu_id 0

**MRL w/ MNS**

python main_mul.py --dataset phone --K 5 --loss mrl --ns dns --n_negs 16 --gpu_id 0

python main_mul.py --dataset sport  --K 5 --loss mrl --ns dns --n_negs 16 --gpu_id 0

python main_mul.py --dataset tool --K 5 --loss mrl --ns dns --n_negs 16 --gpu_id 0
