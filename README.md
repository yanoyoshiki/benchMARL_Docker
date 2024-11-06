# how to start docker env
git submodule update --init --recursive

xhost+

sh build.sh

sh run.sh

pip install -e /root/VectorizedMultiAgentSimulator

pip install torchrl

pip install -e /root/BenchMARL
