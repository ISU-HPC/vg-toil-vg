Bootstrap: docker
from: quay.io/vgteam/vg:v1.13.0-190-g140522d9-t279-run

%labels

MAINTAINER ynanyam@iastate.edu

%post

apt-get update -y
apt-get install -y python-pip

pip install toil
pip install toil-vg

