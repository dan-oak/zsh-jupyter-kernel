https://packaging.python.org/en/latest/tutorials/packaging-projects/

```zsh
pip install uv
uv build

twine upload --repository testpypi dist/*

pip install --index-url https://test.pypi.org/simple/ zsh-jupyter-kernel
python -m zsh_jupyter_kernel.install --sys-prefix

#version=`cat version`
twine upload \
  dist/zsh-jupyter-kernel-$version.tar.gz \
  dist/zsh_jupyter_kernel-$version-py3-none-any.whl
```
