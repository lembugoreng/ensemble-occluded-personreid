Torchreid
===========
Torchreid is a library for deep-learning person re-identification, written in `PyTorch <https://pytorch.org/>`_ and developed for our ICCV'19 project, `Omni-Scale Feature Learning for Person Re-Identification <https://arxiv.org/abs/1905.00953>`_.


Code: https://github.com/KaiyangZhou/deep-person-reid.

Documentation: https://kaiyangzhou.github.io/deep-person-reid/.

How-to instructions: https://kaiyangzhou.github.io/deep-person-reid/user_guide.

Model zoo: https://kaiyangzhou.github.io/deep-person-reid/MODEL_ZOO.

Tech report: https://arxiv.org/abs/1910.10093.



Installation
---------------

Make sure `conda <https://www.anaconda.com/distribution/>`_ is installed.


.. code-block:: bash

    # cd to your preferred directory and clone this repo
    git clone https://github.com/KaiyangZhou/deep-person-reid.git

    # create environment
    cd deep-person-reid/
    conda create --name torchreid python=3.7
    conda activate torchreid

    # install dependencies
    # make sure `which python` and `which pip` point to the correct path
    pip install -r requirements.txt

    # install torch and torchvision (select the proper cuda version to suit your machine)
    conda install pytorch torchvision cudatoolkit=9.0 -c pytorch

    # install torchreid (don't need to re-build it if you modify the source code)
    python setup.py develop

Quick Start
------------

Navigate towards the personreid.ipynb to begin using torchreid with added changes such as ensemble learning!

