# SCUT_emblem

这些矢量图并非官方提供的，而是由网络上提供的旧版学校标识矢量图进行修改而来。

如果采用本项目提供的学校标识的话，不建议使用 CMYK 目录下的。该目录的文件更多的是试图说明学校各个部门使用的混乱的标识中出现三色渐变（蓝-浅紫-白）的原因。（双色渐变，即蓝-白渐变，貌似才是原始的标识的颜色）

## Contributors

- **DevlinNul**: 基于旧版矢量图（`base.eps`）进行个别元素调整（1934->1918），并重新设定了渐变条的色彩参数。
- **paran3xus**: 提供了渐变条色彩参数的选择与校正技术支持。
- **hanjiatong**: 提供了 `base.eps` ，为后续的修改提供了基础。

## 文件说明

### PDF 格式

注意所有文件名中标注为 `渐变色` 的 PDF 文件的 `1918` 都是文本而非路径，其他 PDF 文件中的 `1918` 都是路径。

可能是由于 PDF 文件遵循的标准不一样的问题，目前目录中所有由 Ghostscript 生成的 PDF 均支持在 $\LaTeX$ 的 `tikz` 宏包的 `\node`命令的 `opacity` 键指定不透明度，而由 Adobe PDF library 生成的均不支持（该键无效）。

如果需要给 PDF 文档加水印，请用 `单色校徽` 。

### SVG 格式

略。

## 部分作图思路

之所以要裁边，是因为如果不裁，那么最外面的边界处会有一些底层的色块露出来，而我有强迫症。裁就是用橡皮擦把下方的图层擦掉一部分。

## Disclaimer

本项目中的学校标识文件仅供学习交流。应用本项目提供的学校标识的课程论文、毕业设计等由于未使用官方标识，存在不被认可的风险。如需求稳，请移步SCUT官网以获取官方提供的高清位图：[学校标识](https://www.scut.edu.cn/new/9017/list.htm)。

**The university logos provided here are for academic use only. Using these unofficial versions in formal assignments or theses may lead to academic rejection. To ensure compliance, please download official high-resolution bitmaps from the SCUT website: <https://www.scut.edu.cn/new/9017/list.htm>.**

## 致谢

- 感谢 `hanjiatong` 提供了保留编辑属性的旧版校名校徽矢量图（eps格式）。
- 感谢 `paran3xus` 为渐变条色彩参数选择与校正提供技术支持。

<!-- ## contact

邮箱：<stream12nul@163.com> -->
