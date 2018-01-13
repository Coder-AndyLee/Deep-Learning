# Anaconda
### 保存和加载环境
- `conda env export > environment.yaml` 将包保存为 [YAML](http://www.yaml.org/)
	- 其中，命令的第一部分 `conda env export` 用于输出环境中的所有包的名称（包括 Python 版本）。
	- 导出命令的第二部分 `> environment.yaml` 将导出的文本写入到 YAML 文件 `environment.yaml` 中。

### 删除环境

- 如果你不再使用某些环境，可以使用 `conda env remove -n env_name` 删除指定的环境（在这里名为 `env_name`）。

---

# Jupyter Notebook

### 在Markdown和代码间相互切换

- 通过使用键盘快捷键，可以很快很简单地在Markdown和代码单元格之间相互切换。从Markdown切换到单元格，按 `Y` 。从代码切换到Markdown，按 `M`。

### 创建一个新的单元格

- 最常见的命令之一是创建一个新的单元格。你可以通过在命令模式按 `A` 在当前单元格上方创建一个单元格。按 `B` 在当前选定的单元格下方创建一个单元格。

### Magic 关键字

- Magic 命令的前面带有一个或两个百分号（`%` 或 `%%`），分别对应行 Magic 命令和单元格 Magic 命令。

#### 代码计时

- 在需要计算代码运行时间的 行 / 单元格 前加入 %timeit / %%timeit。

#### 在 notebook 中嵌入可视化内容

- 要直接在 notebook 中呈现图形，应将通过命令 `%matplotlib inline` 内联后端一起使用。
- 在分辨率较高的屏幕（例如 Retina 显示屏）上，notebook 中的默认图像可能会显得模糊。可以在 `%matplotlib inline` 之后使用 `%config InlineBackend.figure_format = 'retina'` 来呈现分辨率较高的图像。









