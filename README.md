# Zsh kernel for Jupyter

![](https://raw.githubusercontent.com/dahn-zk/zsh-jupyter-kernel/master/screenshots/example.png)

a simple Z Shell Jupyter kernel powered by Python, IPyKernel, Pexpect,
and enthusiasm — turn your scripts into notebooks!

## installation

[PyPI](https://pypi.org/project/zsh-jupyter-kernel/):

```sh
pip install zsh_jupyter_kernel
```

### install kernel file

see the help command for details
```sh
python -m zsh_jupyter_kernel.install --help
```

## development

```sh
pip install uv
uv sync
uv run python -m zsh_jupyter_kernel.install --sys-prefix
uv run pytest
```
