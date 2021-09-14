```bash
# ARM, M1

/Users/mohammadkamruzzaman/miniforge3/bin/conda create -n  tf_arm
conda activate /Users/mohammadkamruzzaman/miniforge3/envs/tf_arm
/Users/mohammadkamruzzaman/miniforge3/bin/conda install -y python=3.8
file $(which python)
python3 -m ssl

pip install --force pip==20.2.4 wheel setuptools cached-property six
cd mywork1/tf_macos/tensorflow_macos/arm64
pip install --upgrade --no-dependencies --force  numpy-1.18.5-cp38-cp38-macosx_11_0_arm64.whl grpcio-1.33.2-cp38-cp38-macosx_11_0_arm64.whl h5py-2.10.0-cp38-cp38-macosx_11_0_arm64.whl tensorflow_addons_macos-0.1a3-cp38-cp38-macosx_11_0_arm64.whl
pip install absl-py astunparse flatbuffers gast google_pasta keras_preprocessing opt_einsum protobuf tensorflow_estimator termcolor typing_extensions wrapt wheel tensorboard typeguard
pip install --upgrade --force --no-dependencies  tensorflow_macos-0.1a3-cp38-cp38-macosx_11_0_arm64.whl
pip install jupyter
python -m ipykernel install --name=tf_arm
/Users/mohammadkamruzzaman/miniforge3/bin/conda install scipy pandas matplotlib

cd code
jupyter notebook



```

```
bash .start_anaconda_envX86
conda create --name tf_x86_py39 python=3.9
conda activate tf_x86_py39

pip install tensorflow
pip install opencv-python



```
