# MachineLearning_OREILLY
Hands-on Machine Learning with Scikit-Learn, Keras &amp; TensorFlow

export ML_PATH="$HOME/<directory>"
mkdir -p $ML_PATH

python3 -m pip --version
python3 -m pip install --user -U pip


Creating an isolated environment

python3 -m pip install --user -U virtualenv

cd $ML_PATH
python3 -m virtualenv my_env

cd $ML_PATH
source my_env/bin/activate # on Linux or mac
.\my_env/Scripts\activate  # on Windows


for this repo 
Please install the following dependencies

python3 -m pip install -U jupyter matplotlib numpy pandas scipy scikit-learn


