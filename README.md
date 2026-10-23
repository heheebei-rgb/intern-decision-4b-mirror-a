# Intern-Decision-4B 权重镜像 Part A（GitHub 源码包分发）

[internlm/Intern-Decision-4B](https://github.com/internlm/Intern-Decision)（多模态结构化决策模型，apache-2.0，Qwen3.5-4B 底座）权重的分块镜像。**需与 Part B 仓库一起下载才完整。**

## 下载与重建
1. **Code → Download ZIP**（两个 part 仓库都要下）
2. 两个 ZIP 解压到同一目录
3. 各自执行 `python3 merge_and_verify.py`（合并分块 + sha256 校验，纯标准库）
4. 本目录产物: `model-language-0001-save_rank0.safetensors` (3.97GB) + `model.safetensors.index.json` + `config.json`
