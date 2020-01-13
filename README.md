
注明：这项工作的原创性方法由[Gwern](https://www.gwern.net/)提出，我只不过是照着他的方法重现了一遍。
# 动漫脸生成器
&emsp;&emsp;这是一个用StyleGAN训练出的动漫脸生成器，生成效果如下所示。<br /><br /><br />

# 生成示例

## &emsp;&emsp;单张样本
&emsp;&emsp;&emsp;&emsp;&emsp;![Image text](https://github.com/a312863063/seeprettyface-ganerator-dongman/blob/master/examples/example_1.png)<br/><br/>
&emsp;&emsp;&emsp;&emsp;&emsp;![Image text](https://github.com/a312863063/seeprettyface-ganerator-dongman/blob/master/examples/example_2.png)<br/><br/>
&emsp;&emsp;&emsp;&emsp;&emsp;![Image text](https://github.com/a312863063/seeprettyface-ganerator-dongman/blob/master/examples/example_3.png)<br/><br/>

## 概览（有筛选）
![Image text](https://github.com/a312863063/seeprettyface-ganerator-dongman/blob/master/examples/64_examples.jpg)
<br /><br /><br />
# 运行代码
## 环境配置
&emsp;&emsp;Both Linux and Windows are supported, but we strongly recommend Linux for performance and compatibility reasons.<br/>
&emsp;&emsp;64-bit Python 3.6 installation. We recommend Anaconda3 with numpy 1.14.3 or newer.<br/>
&emsp;&emsp;TensorFlow 1.10.0 or newer with GPU support.<br/>
&emsp;&emsp;NVIDIA driver 391.35 or newer, CUDA toolkit 9.0 or newer, cuDNN 7.3.1 or newer.<br/>

## 运行步骤
&emsp;&emsp;1.在model文件夹中按照txt地址下载模型，放在该位置<br/>
&emsp;&emsp;2.运行generate_dongman.py<br/>
<br /><br /><br />
## 了解技术原理 & 获取训练集：[点此进入](http://www.seeprettyface.com/)
![Image text](https://github.com/a312863063/seeprettyface/blob/master/EP001-01.png)
