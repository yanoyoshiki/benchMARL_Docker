# how to start docker env
git submodule update --init --recursive

xhost+

cd ##your directory##/docker

sh build.sh

sh run.sh

pip install -e /root/VectorizedMultiAgentSimulator

pip install torchrl

pip install -e /root/BenchMARL
