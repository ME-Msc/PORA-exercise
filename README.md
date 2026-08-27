# PORA Exercises

用于完成并提交 Stanford ASL 的
[Principles of Robot Autonomy 课程练习](https://github.com/StanfordASL/pora-exercises)。

## 使用

安装 [uv](https://docs.astral.sh/uv/getting-started/installation/) 后运行：

```bash
uv sync --locked
uv run --locked jupyter lab notebook.ipynb
```

项目使用 Python 3.11；依赖由 `pyproject.toml` 声明、`uv.lock` 锁定。
本地环境位于 `.venv/`，无需提交。PyTorch 使用 CPU 版本。

Linux 如需运行视频或无显示器实验：

```bash
sudo apt install -y swig ffmpeg xvfb
```

课程 notebook、素材及模型仍归原权利人所有；本仓库建议保持私有。
