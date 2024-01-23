# ChatGLM3-6B
## 环境准备
我们实践了两种平台进行选择
*  在[autodl](https://www.autodl.com/)平台中租一个3090等24G显存的显卡机器，如下图所示镜像选择`PyTorch`-->`2.0.0`-->`3.8(ubuntu20.04)`-->`11.8`
*  在 [InternStudio](https://studio.intern-ai.org.cn/) 平台中选择 A100(1/4) 的配置，如下图所示镜像选择 `Cuda11.7-conda`，如下图所示：
在Terminal中，进行pip换源和安装依赖包
