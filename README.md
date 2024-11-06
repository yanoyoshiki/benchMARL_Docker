# how to start docker env
任意の場所に移動してクローン


cd benchMARL_docker


mkdir src


src下に各リポジトリをクローン

git@github.com:proroklab/VectorizedMultiAgentSimulator.git


git@github.com:facebookresearch/BenchMARL.git


xhost+

cd ##your directory##/docker

sh build.sh

sh run.sh

pip install -e /root/VectorizedMultiAgentSimulator

pip install torchrl

pip install -e /root/BenchMARL
