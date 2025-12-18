<div align="center">

![Image](https://github.com/user-attachments/assets/e504135e-67fd-4fa1-b0e4-d495358d8aa5)

[![TEN Releases]( https://img.shields.io/github/v/release/ten-framework/ten-vad?color=369eff&labelColor=gray&logo=github&style=flat-square )](https://github.com/TEN-framework/ten-vad/releases)
[![Release Date](https://img.shields.io/github/release-date/ten-framework/ten-vad?labelColor=gray&style=flat-square)](https://github.com/TEN-framework/ten-vad/releases)
[![Discussion posts](https://img.shields.io/github/discussions/TEN-framework/ten-vad?labelColor=gray&color=%20%23f79009)](https://github.com/TEN-framework/ten-vad/discussions/)
[![Commits](https://img.shields.io/github/commit-activity/m/TEN-framework/ten-vad?labelColor=gray&color=pink)](https://github.com/TEN-framework/ten-vad/graphs/commit-activity)
[![Issues closed](https://img.shields.io/github/issues-search?query=repo%3ATEN-framework%2Ften-vad%20is%3Aclosed&label=issues%20closed&labelColor=gray&color=green)](https://github.com/TEN-framework/ten-vad/issues)
![](https://img.shields.io/github/contributors/ten-framework/ten-vad?color=c4f042&labelColor=gray&style=flat-square)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome!-brightgreen.svg?style=flat-square)](https://github.com/TEN-framework/ten-vad/pulls)
[![HuggingFace TEN VAD](https://img.shields.io/badge/Hugging%20Face-TEN%20VAD-yellow?style=flat&logo=huggingface)](https://huggingface.co/TEN-framework/ten-vad)
[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/TEN-framework/TEN-vad)
<!-- [![ReadmeX](https://raw.githubusercontent.com/CodePhiliaX/resource-trusteeship/main/readmex.svg)](https://readmex.com/TEN-framework/ten-vad) -->


[![README（英文）][lang-en-badge]][lang-en-readme]
[![简体中文指南][lang-zh-badge]][lang-zh-readme]

<a href="https://trendshift.io/repositories/14548" target="_blank"><img src="https://trendshift.io/api/badge/repositories/14548" alt="TEN-framework%2Ften-vad | Trendshift" style="width: 250px; height: 55px;" width="250" height="55"/></a>

</div>

<br>

## 最新更新 🔥
- [2025/11] **WASM** 构建指南和浏览器测试 Demo发布啦！您可以在 `lib/Web` and `examples`中查看。
- [2025/11] 新增 **Linux、macOS** 上使用 **ONNX** 模型的 **Python** 推理！ 感谢 [Guy Nicholson](https://github.com/guynich) 的贡献！
- [2025/11] 新增 **Linux、macOS** 和 **Windows** 上 **pre-lib** 的 **Golang** 用法，感谢 [hylarucoder](https://github.com/hylarucoder) 的贡献！
- [2025/11] 新增 **Linux、macOS、Windows、Android** 上 **pre-lib** 的 **Java** 用法，感谢 [ZhangYang(arthasking123)](https://github.com/arthasking123) 的贡献！
- [2025/07] 🎉 重磅! **TEN VAD** 现已集成到 [**k2-fsa/sherpa-onnx**](https://github.com/k2-fsa/sherpa-onnx) 中, 感谢 [Fangjun Kuang](https://github.com/csukuangfj)！开发者可以更精确的提取语音片段，并获得更好的 ASR 体验！参考文档➡️ [Documentation](https://k2-fsa.github.io/sherpa/onnx/vad/ten-vad.html#) 。
- [2025/07] 新增 **macOS** 和 **Windows** 上 **pre-lib** 的 **Python** 推理。
- [2025/06] TEN VAD **ONNX** 模型和相应的预处理代码现已开源！开发者现在可以在**任何平台**和**任何硬件架构**上部署 **TEN VAD**。
- [2025/06] 新增适用于 **Web WASM** 支持的 **WASM+JS**。

<br>

## 目录
- [欢迎使用 TEN](#welcome-to-ten)
- [TEN Hugging Face Space](#ten-hugging-face-space)
- [TEN VAD 简介](#introduction)
- [主要特点](#key-features)
  - [高性能](#1-high-performance)
    - [性能对比](#11-performance-comparison)
  - [智能体友好](#2-agent-friendly)
  - [轻量级](#3-lightweight)
  - [支持多种编程语言和平台](#4-multiple-programming-languages-and-platforms)
  - [支持的采样率和帧移](#5-supported-sampling-rate-and-hop-size)
- [开发者推荐](#developers-testimonial)
- [安装指南](#installation)
- [快速开始](#quick-start)
  - [Python 用法](#python-usage)
    - [Linux / macOS / Windows](#1-linux--macos--windows)
  - [JS 用法](#js-usage)
  - [Java 用法](#java-usage)
  - [Go (Golang) 用法](#go-golang-usage)
  - [C 用法](#c-usage)
    - [Linux](#1-linux)
    - [Windows](#2-windows)
    - [macOS](#3-macos)
    - [Android](#4-android)
    - [iOS](#5-ios)
- [TEN 生态](#ten-ecosystem)
- [问题解答](#ask-questions)
- [引用](#citations)
- [许可证](#license)

<br>

## 欢迎使用 TEN 

TEN 是一个面向语音对话 AI 代理的开源框架。

[TEN 生态][ten-ecosystem-anchor] 包含 [TEN Framework][ten-framework-link]、[代理示例][ten-agent-example-link]、[VAD][ten-vad-link]、[Turn Detection][ten-turn-detection-link] 以及 [Portal][ten-portal-link]。

<br>

| 社区渠道 | 用途 |
| ---------------- | ------- |
| [![Follow on X](https://img.shields.io/twitter/follow/TenFramework?logo=X&color=%20%23f5f5f5)](https://twitter.com/intent/follow?screen_name=TenFramework) | 在 X 上关注 TEN Framework，获取更新与公告 |
| [![Follow on LinkedIn](https://custom-icon-badges.demolab.com/badge/LinkedIn-TEN_Framework-0A66C2?logo=linkedin-white&logoColor=fff)](https://www.linkedin.com/company/ten-framework) | 在 LinkedIn 上关注 TEN Framework，获取动态和公告 |
| [![Discord TEN Community](https://img.shields.io/badge/Discord-Join%20TEN%20Community-5865F2?style=flat&logo=discord&logoColor=white)](https://discord.gg/VnPftUzAMJ) | 加入 Discord 社区，与开发者交流 |
| [![Hugging Face Space](https://img.shields.io/badge/Hugging%20Face-TEN%20Framework-yellow?style=flat&logo=huggingface)](https://huggingface.co/TEN-framework) | 加入 Hugging Face 社区，探索我们的空间与模型 |
| [![WeChat](https://img.shields.io/badge/TEN_Framework-WeChat_Group-%2307C160?logo=wechat&labelColor=darkgreen&color=gray)](https://github.com/TEN-framework/ten-agent/discussions/170) | 加入微信社群，与中文社区讨论 |

<br>

> \[!IMPORTANT]
>
> **请关注 TEN ！** ⭐️
>
> 获取版本更新等最新动态。您的支持能帮助 TEN 变得更好！

<br>

![TEN star us gif](https://github.com/user-attachments/assets/eeebe996-8c14-4bf7-82ae-f1a1f7e30705)

<br>

## TEN Hugging Face Space

<https://github.com/user-attachments/assets/725a8318-d679-4b17-b9e4-e3dce999b298>

欢迎访问 [TEN Hugging Face Space](https://huggingface.co/spaces/TEN-framework/ten-agent-demo)，体验带有 TEN VAD 与 TEN Turn Detection 的 Agent Demo！

<br>

## **项目简介**

**TEN VAD** 是一个专为企业级应用设计的实时语音活动检测模型，提供准确的帧级人声检测。相比业界常用的 WebRTC VAD 和 Silero VAD ，它的精度更高。此外，与 Silero VAD 相比，TEN VAD 具有更低的计算复杂度，消耗更少内存。同时，该架构的时间效率能够实现快速的语音活动检测，显著减少对话式 AI 系统中的端到端响应延迟和轮次检测延迟。

<br>

## **主要特点**

### **1. 高性能:**

下图展示了 WebRTC VAD（基于 pitch 音高）、Silero VAD 和 TEN VAD 的精确度-召回率曲线。该对比是在经过精确人工标注的测试集上进行的。测试集中的音频文件来源于 librispeech、gigaspeech、DNS Challenge 等。如图所示，TEN VAD 实现了最佳性能。此外，我们在内部大型真实业务数据集上进行了交叉验证，结果证明了该对比的可复现性。**带有标注标签的测试集**已发布在本仓库的 "testset" 目录下。

 <br>

![PR Curves Performance Comparison](https://github.com/TEN-framework/ten-vad/raw/main/examples/images/PR_Curves_testset.png)

*请注意，默认阈值 0.5 用于生成二元语音指示器（0 代表非语音信号，1 代表语音信号）。此阈值需要根据您的特定领域任务进行调整。* 


### **1.1 性能对比**

开发者可以在 Linux x64 上执行以下脚本，在开源测试集上复现 TEN VAD 和 Silero VAD 的性能对比 PR 曲线（如前文图中所示），只需一行代码。输出图表将保存在与脚本相同的目录下。

```
cd ./examples
python plot_pr_curves.py
```

<br>

### **2. 智能体友好:**

如下图所示，TEN VAD 能够快速检测出语音与非语音之间的过渡，而 Silero VAD 则存在数百毫秒的延迟，这会增加人机交互系统中的端到端累计延迟。此外，如 6.5 秒到 7.0 秒音频段所示，Silero VAD 未能识别相邻语音段之间的短暂静音。

![Agent-Friendly Response](https://github.com/TEN-framework/ten-vad/raw/main/examples/images/Agent-Friendly-image.png)
<br>

### **3. 轻量级:**

我们在五个不同平台、配备不同 CPU 上对 TEN VAD 和 Silero VAD 的 RTF（实时因子）以及包体大小进行了对比，TEN VAD 的计算复杂度更低，包体更小。

<table>
  <tr>
    <th align="center" rowspan="2" valign="middle"> 平台 </th>
    <th align="center" rowspan="2" valign="middle"> CPU </th>
    <th align="center" colspan="2"> RTF </th>
    <th align="center" colspan="2"> 包大小 </th>

  </tr>
  <tr>
    <th align="center" style="white-space: nowrap;"> TEN VAD </th>
    <th align="center" style="white-space: nowrap;"> Silero VAD </th>
    <th align="center"> TEN VAD </th>
    <th align="center"> Silero VAD </th>
  </tr>
  <tr>
    <th align="center" rowspan="3"> Linux </th>
    <td style="white-space: nowrap;"> AMD Ryzen 9 5900X 12-Core </td>
    <td align="center"> 0.0150 </td>
    <td align="center" rowspan="2" valign="middle"> / </td>
    <td align="center" rowspan="3" valign="middle"> 306KB </td>
    <td align="center" rowspan="10" style="white-space: nowrap;" valign="middle"> 2.16MB(JIT) / 2.22MB(ONNX) </td>
  </tr>
  <tr>
    <td style="white-space: nowrap;"> Intel(R) Xeon(R) Platinum 8253 </td>
    <td align="center"> 0.0136 </td>
  </tr>
  <tr>
    <td style="white-space: nowrap;"> Intel(R) Xeon(R) Gold 6348 CPU @ 2.60GHz </td>
    <td align="center"> 0.0086 </td>
    <td align="center"> 0.0127 </td>
  </tr>
  <tr>
    <th align="center"> Windows </th>
    <td> Intel i7-10710U </td>
    <td align="center"> 0.0150 </td>
    <td align="center" rowspan="7" valign="middle"> / </td>
    <td align="center" style="white-space: nowrap;"> 464KB(x86) / 508KB(x64) </td>
  </tr>
  <tr>
    <th align="center"> macOS </th>
    <td> M1 </td>
    <td align="center"> 0.0160 </td>
    <td align="center"> 731KB </td>
  </tr>
  <tr>
    <th align="center"> Web </th>
    <td> macOS(M1) </td>
    <td align="center"> 0.010 </td>
    <td align="center"> 277KB </td>
  </tr>
  <tr>
    <th align="center" rowspan="2"> Android </th>
    <td> Galaxy J6+ (32bit, 425) </td>
    <td align="center"> 0.0570 </td>
    <td align="center" rowspan="2" style="white-space: nowrap;"> 373KB(v7a) / 532KB(v8a)</td>
  </tr>
  <tr>
    <td> Oppo A3s (450) </td>
    <td align="center"> 0.0490 </td>
  </tr>
  <tr>
    <th align="center" rowspan="2"> iOS </th>
    <td> iPhone6 (A8) </td>
    <td align="center"> 0.0210 </td>
    <td align="center" rowspan="2"> 320KB</td>
  </tr>
  <tr>
    <td> iPhone8 (A11) </td>
    <td align="center"> 0.0050 </td>
  </tr>
</table>
<br>

### **4. 支持多种编程语言和平台:**

TEN VAD 为五个操作系统（Linux x64、Windows、macOS、Android、iOS）提供了跨平台 C 语言兼容性，以及为 Linux x64 优化的 Python 绑定，以及用于 Web 的 wasm。
<br>

### **5. 支持的采样率和帧移（Hop Size）:**

TEN VAD 的音频输入为 16kHz，支持可配置的帧移（优化的帧配置：160/256 采样点 = 10/16 毫秒）。其他采样率需要重采样到 16kHz。
<br>

## **开发者推荐**
> * "我们选择 TEN VAD 是因为与其他 VAD 相比，它能更快、更准确地检测日语的句尾，并且仍然保持足够轻量和快速，适合实时应用。” - LiveCap, Hakase shojo

> * "TEN VAD 的整体性能优于 Silero VAD。其高准确性和低资源消耗帮助我们提高了效率并显著降低了成本。” - Rustpbx.
> 
<br>

## **安装指南**

```
git clone https://github.com/TEN-framework/ten-vad.git
```

<br>

## **快速开始**

该项目通过动态库链接支持五个主要平台。

<table>
  <tr>
    <th align="center"> 平台 </th>
    <th align="center"> Dynamic Lib </th>
    <th align="center"> Supported Arch </th>
    <th align="center"> Interface Language </th>
    <th align="center"> Header </th>
    <th align="center"> Comment </v>
  </tr>
  <tr>
    <th align="center"> Linux </th>
    <td align="center"> libten_vad.so </td>
    <td align="center"> x64 </td>
    <td align="center"> Python, C, Java, Go </td>
    <td rowspan="6">ten_vad.h <br> ten_vad.py <br> ten_vad.js <br> TenVad.java</td>
    <td>  </td>
  </tr>
  <tr>
    <th align="center"> Windows </th>
    <td align="center"> ten_vad.dll </td>
    <td align="center"> x64, x86 </td>
    <td align="center"> C, Java, Go </td>
    <td>  </td>
  </tr>
  <tr>
    <th align="center"> macOS </th>
    <td align="center"> ten_vad.framework </td>
    <td align="center"> arm64, x86_64 </td>
    <td align="center"> C, Java, Go </td>
    <td>  </td>
  </tr>
  <tr>
    <th align="center"> Web </th>
    <td align="center"> ten_vad.wasm </td>
    <td align="center"> / </td>
    <td align="center"> JS </td>
    <td>  </td>
  </tr>
  <tr>
    <th align="center"> Android </th>
    <td align="center"> libten_vad.so </td>
    <td align="center"> arm64-v8a, armeabi-v7a </td>
    <td align="center"> C, Java </td>
    <td>  </td>
  </tr>
  <tr>
    <th align="center"> iOS </th>
    <td align="center"> ten_vad.framework </td>
    <td align="center"> arm64 </td>
    <td align="center"> C </td>
    <td> 1. not simulator <br> 2. not iPad </td>
  </tr>

</table>
<br>

### **Python 用法**

#### **1. Linux / macOS / Windows**

#### **依赖项**

- numpy (Version 1.17.4/1.26.4 verified)
- scipy (Version >= 1.5.0)
- scikit-learn (Version 1.2.2/1.5.0 verified, 绘制 PR 曲线使用)
- matplotlib (Version 3.1.3/3.10.0 verified, 绘制 PR 曲线使用)
- torchaudio (Version 2.2.2 verified, 绘制 PR 曲线使用)

- Python version 3.8.19/3.10.14 verified

*注意: 您可以使用上述软件包的其他版本，但我们未进行测试。*

<br>

该 **lib** 仅依赖 python, 您必须通过 requirements.txt 安装依赖项:

`pip install -r requirements.txt`

如果运行 Demo 或者绘制 PR 曲线，您需要安装依赖项：

`pip install -r ./examples/requirements.txt`

*注意：如果您没有安装 **libc++1** (Linux), 您需要通过以下代码来安装：*

```
sudo apt update
sudo apt install libc++1
```

<br>

#### **Prebuilt-libs 用法**

*注意: 对于 Python 的使用, 您可以通过 **git clone** 或者 **pip** 的任意一种进行。*

##### **通过 git clone 使用:**

1. 克隆仓库

```
git clone https://github.com/TEN-framework/ten-vad.git
```

2. 进入 examples 目录

```
cd ./examples
```

3. 测试

```
python test.py s0724-s0730.wav out.txt
```

<br>

##### **通过 pip 使用:**

1. 通过 pip 安装

```
pip install -U --force-reinstall -v git+https://github.com/TEN-framework/ten-vad.git
```

2. 编写您自己的用例并导入该类， TenVAD 类的属性可以参考 ten_vad.py

```
from ten_vad import TenVad
```

<br>

#### **ONNX model 的用法**
您需要预先从[官方网站](https://github.com/microsoft/onnxruntime)下载 **ONNX Runtime** 的安装包. 请注意，ONNX Runtime 的版本必须高于或者等于 1.17.1 (如：onnxruntime-linux-x64-1.17.1.tgz).
<br>


您可以从[官方网站](https://github.com/microsoft/onnxruntime/tags)查看 **ONNX Runtime** 版本. 例如通过 [官方](https://github.com/microsoft/onnxruntime/releases/download/v1.17.1/onnxruntime-linux-x64-1.17.1.tgz)下载1.17.1版本（Linux x64）并提取压缩文件后. 您会获得两个重要的目录：`include/` - 头文件, `lib/` - 库文件。

```
1) cd examples_onnx/python
2) ./build-and-deploy-linux.sh --ort-path /absolute/path/to/your/onnxruntime/root/dir # For Linux.
```

**注意**
1. 如果在运行 build-and-deploy-linux.sh 不同的目录下执行 ONNX Demo，请确保创建指向 src/onnx_model/ 的符号链接，以防止 ONNX 模型文件加载失败。

2. ONNX 模型位于 src/onnx_model 目录中。

3. 对于 macOS，请运行 build-and-deploy-macos.sh。

<br>

### **JS 用法**

##### **依赖项**

- Node.js (macOS v14.18.2, Linux v16.20.2 verified)
- 终端
- 浏览器

##### **用法**

```
终端
1）cd ./examples
2）node test_node.js s0724-s0730.wav out.txt

浏览器
1）python3 -m http.server 8000
2）Open browser and navigate to http://localhost:8000/examples/test_browser.html
```

<br>

### **Java 用法**

TEN VAD 通过 JNI (Java Native Interface) 绑定，为所有主要平台提供了全面的 Java 支持。

#### **依赖项**

- Java 8 或更高版本
- `lib/` 目录中的本地库
- JNI 头文件

#### **编译**

```bash
# Compile Java source, note if JNA library is not installed, you should download it first. For example, you can download JNA library and include it here. You can also export it to the CLASSPATH environment variables
wget https://repo1.maven.org/maven2/net/java/dev/jna/jna/5.13.0/jna-5.13.0.jar # I just picked a random version
javac -encoding UTF-8 -cp jna-5.13.0.jar -d . include/TenVad.java examples/TestTenVad.java

# Run example in the project root directory
java -cp .:jna-5.13.0.jar TestTenVad examples/s0724-s0730.wav examples/out.txt

# Run example in the examples directory
java -cp ..:../jna-5.13.0.jar TestTenVad s0724-s0730.wav out.txt
```

#### **示例代码**

```java
import com.ten.vad.TenVad;

public class VADExample {
    public static void main(String[] args) {
        // Create VAD instance
        TenVad vad = new TenVad(256, 0.5f);
        
        // Process audio frame
        short[] audioFrame = new short[256]; // 16ms at 16kHz
        // ... fill audioFrame with audio data ...
        
        TenVad.VadResult result = vad.process(audioFrame);
        System.out.println("Probability: " + result.getProbability());
        System.out.println("Voice detected: " + result.isVoiceDetected());
        
        // Clean up
        vad.destroy();
    }
}
```

#### **特定平台说明**

- **Linux**: 需要 `libc++1` 包
- **Windows**: 确保安装了 Visual C++ Redistributable
- **macOS**: 无额外要求
- **Android**: 使用 Android NDK 进行本地库集成

#### **API 参考**

```java
public class TenVad {
    // Constructor
    public TenVad(int hopSize, float threshold)
    
    // Process audio frame
    public VadResult process(short[] audioData)
    
    // Get library version
    public static String getVersion()
    
    // Cleanup
    public void destroy()
}

public static class VadResult {
    public float getProbability()    // [0.0, 1.0]
    public int getFlag()            // 0 or 1
    public boolean isVoiceDetected() // true if voice detected
}
```

<br>


### **Go (Golang) 用法**

TEN VAD 为 Linux, macOS 以及 Windows 提供 Golang 支持.

#### **使用编译**
```
cd examples/go-tenvad
go build -o tenvad .
./tenvad
```
#### **不使用编译**
```
cd examples/go-tenvad
export LD_LIBRARY_PATH=../../lib/Linux/x64:$LD_LIBRARY_PATH # For Windows and macOS, export the corresponding lib path instead
go run .
```

<br>

### **C 用法**

#### **构建脚本**

位于 examples/ directory 或 examples_onnx/ (在 Linux 上的 **ONNX** 用法):

- Linux: build-and-deploy-linux.sh
- Windows: build-and-deploy-windows.bat
- macOS: build-and-deploy-mac.sh
- Android: build-and-deploy-android.sh
- iOS: build-and-deploy-ios.sh

#### **动态库配置**

Runtime 库路径配置:

- Linux/Android: LD_LIBRARY_PATH
- macOS: DYLD_FRAMEWORK_PATH
- Windows: DLL in executable directory or system PATH

#### **自定义**

- 修改特定平台的构建脚本
- 调整 CMakeLists.txt
- 配置工具链以及架构设置

#### **用法概述**

- 导航到 examples/ 或 examples_onnx/ (在 Linux 上的 **ONNX** 用法)
- 执行特定平台的构建脚本
- 配置动态库路径
- 使用样例音频 s0724-s0730.wav 运行 demo
- 处理结果保存至 out.txt

<br>

各平台具体用法如下： <br>

#### **1. Linux**

##### **依赖项**

- Clang (e.g. 6.0.0-1ubuntu2 verified)
- CMake
- Terminal

*注意：如果您没有安装 **libc++1**, 您需要使用下方代码安装它：*

```
sudo apt update
sudo apt install libc++1
```

##### **prebuilt-lib 的用法**

```
1) cd ./examples
2) ./build-and-deploy-linux.sh
```


##### **ONNX 的用法**
您需要预先从[官方网站](https://github.com/microsoft/onnxruntime)下载 **ONNX Runtime** 的安装包. 请注意，ONNX Runtime 的版本必须高于或者等于 1.17.1 (如：onnxruntime-linux-x64-1.17.1.tgz).
<br>


您可以从[官方网站](https://github.com/microsoft/onnxruntime/tags)查看 **ONNX Runtime** 版本. 例如通过 [官方](https://github.com/microsoft/onnxruntime/releases/download/v1.17.1/onnxruntime-linux-x64-1.17.1.tgz)下载1.17.1版本（Linux x64）并提取压缩文件后. 您会获得两个重要的目录：`include/` - 头文件, `lib/` - 库文件。

```
1) cd examples_onnx/python
2) ./build-and-deploy-linux.sh --ort-path /absolute/path/to/your/onnxruntime/root/dir # Linux. 
```

**注意**
1. 如果在运行 build-and-deploy-linux.sh 不同的目录下执行 ONNX Demo，请确保创建指向 src/onnx_model/ 的符号链接，以防止 ONNX 模型文件加载失败。

2. ONNX 模型位于`src/onnx_model`目录中。

3. 对于 macOS，请运行 build-and-deploy-macos.sh。

4. ONNX example 的构建可以参考 [examples_onnx/README.md](/examples_onnx/README.md).


<br>

#### **2. Windows**

##### **依赖项**

- Visual Studio (2017, 2019, 2022 verified)
- CMake (3.26.0-rc6 verified)
- 终端 (MINGW64 或者 powershell)

##### **用法**

```
1) cd ./examples
2) 使用您的偏好配置 "build-and-deploy-windows.bat"
    - 架构 (default: x64)
    - Visual Studio 版本 (default: 2019)
3) ./build-and-deploy-windows.bat
```

<br>

#### **3. macOS**

##### **依赖项**

- Xcode (15.2 verified)
- CMake (3.19.2 verified)

##### **用法**

```
1) cd ./examples
2) 使用您的目标架构配置 "build-and-deploy-mac.sh"：
  - 默认: arm64 (Apple Silicon)
  - 可选: x86_64 (Intel)
3) ./build-and-deploy-mac.sh
```

<br>

#### **4. Android**

##### **依赖项**

- NDK (r25b, macOS verified)
- CMake (3.19.2, macOS verified)
- adb (1.0.41, macOS verified)

##### **用法**

```
1) cd ./examples
2) 导出 ANDROID_NDK=/path/to/android-ndk  # 将其替换为您的 NDK 安装路径
3) 使用您的构建设置配置 "build-and-deploy-android.sh" 
  - 架构: arm64-v8a (default) or armeabi-v7a
  - 工具链: aarch64-linux-android-clang (default) (默认) 或自定义 NDK 工具链
4) ./build-and-deploy-android.sh
```

<br>

#### **5. iOS**

##### **依赖项**

Xcode (15.2, macOS verified)
CMake (3.19.2, macOS verified)

##### **用法**

1. 进入 examples 目录

```
cd ./examples
```

2. 为 iOS 的构建创建 Xcode 项目文件

```
./build-and-deploy-ios.sh
```

3.  跟随下方步骤在 iOS 设备上构建和测试：

    3.1. 使用 Xcode 打开 .xcodeproj 文件: 
    a) cd ./build-ios
    b) open ./ten_vad_demo.xcodeproj

    3.2. 在 Xcode IDE 中, 选择 ten_vad_demo 目标 (检查项: Edit Scheme → Run → Release), 然后选择您的 iOS 设备（非模拟器）。

    ![iOS Setup Image 1](https://github.com/TEN-framework/ten-vad/raw/main/examples/images/ios_image_1.jpg)

    3.3. 将 ten_vad/lib/iOS/ten_vad.framework 拖到 "Frameworks, Libraries, and Embedded Content"中

    - (在 TARGETS → ten_vad_demo → ten_vad_demo → General, 将 Embed 设置为 "Embed & Sign").

    - 或通过以下方式直接添加: "Frameworks, Libraries, and Embedded Content" → "+" → Add Other... → Add Files →...

    - 注意: 如果未完成此步骤，您可能会遇到以下运行时错误："dyld: Library not loaded: @rpath/ten_vad.framework/ten_vad"。

    ![iOS Setup Image 2](https://github.com/TEN-framework/ten-vad/raw/main/examples/images/ios_image_2.png)

      3.4. 配置 iOS 设备签名

      - 在 TARGETS → ten_vad_demo → Signing & Capabilities → Signing

      - 将 Bundle Identifier: 将 "com.yourcompany" 修改为您自己的;

      - 指定 Provisioning Profile

    -  TARGETS → ten_vad_demo → Build Settings → Signing → Code Signing Identity:

      - 指定您的证书

      3.5. 在 Xcode 中构建并在您的设备上运行演示.

<br>

## TEN Ecosystem

| 项目 | 预览 |
| ------- | ------- |
| [**️TEN Framework**][ten-framework-link]<br>对话式 AI 智能体开源框架。<br><br>![][ten-framework-shield] | ![][ten-framework-banner] |
| [**TEN VAD**][ten-vad-link]<br>低延迟、轻量级、高性能语音活动检测模型 (VAD).<br><br>![][ten-vad-shield] | ![][ten-vad-banner] |
| [**️ TEN Turn Detection**][ten-turn-detection-link]<br>情境感知对话轮次检测<br><br>![][ten-turn-detection-shield] | ![][ten-turn-detection-banner] |
| [**TEN Agent Examples**][ten-agent-example-link]<br>基于 TEN 的智能体 Demo.<br><br> | ![][ten-agent-example-banner] |
| [**TEN Portal**][ten-portal-link]<br>TEN 官方网站/文档站/博客站.<br><br>![][ten-portal-shield] | ![][ten-portal-banner] |


<br>

## 问题解答

TEN VAD 可在以下 AI 驱动的问答平台上使用。它们可以帮助您以多种语言快速准确地找到答案，涵盖从基本设置到高级实现细节的所有内容。

| 服务e | 入口 |
| ------- | ---- |
| DeepWiki | [![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/TEN-framework/TEN-vad) |
| ReadmeX | [![ReadmeX](https://raw.githubusercontent.com/CodePhiliaX/resource-trusteeship/main/readmex.svg)](https://readmex.com/TEN-framework/ten-vad) |

<br>

## **引用**

```
@misc{TEN VAD,
  author = {TEN Team},
  title = {TEN VAD: A Low-Latency, Lightweight and High-Performance Streaming Voice Activity Detector (VAD)},
  year = {2025},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {https://github.com/TEN-framework/ten-vad.git},
  email = {developer@ten.ai}
}
```

<br>

## 许可证

- 除下列目录外，TEN VAD 以 Apache License 2.0（带有额外条款）发布，详见根目录下的 LICENSE 文件。 
- `pitch_est.cc` 包含修改和派生自 [LPCNet](https://github.com/xiph/LPCNet) 的代码, 采用 [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html) 和 [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html) 许可, 详情请参阅根目录下的 NOTICES 文件。

<br>

[back-to-top]: https://img.shields.io/badge/-Back_to_top-gray?style=flat-square
[ten-framework-shield]: https://img.shields.io/github/stars/ten-framework/ten_framework?color=ffcb47&labelColor=gray&style=flat-square&logo=github
[ten-framework-banner]: https://github.com/user-attachments/assets/2a560a74-68f3-4f4a-9ec8-89464c42a9c7
[ten-framework-link]: https://github.com/ten-framework/ten_framework

[ten-ecosystem-anchor]: #ten-ecosystem

[ten-vad-link]: https://github.com/ten-framework/ten-vad
[ten-vad-shield]: https://img.shields.io/github/stars/ten-framework/ten-vad?color=ffcb47&labelColor=gray&style=flat-square&logo=github
[ten-vad-banner]: https://github.com/user-attachments/assets/e504135e-67fd-4fa1-b0e4-d495358d8aa5

[ten-turn-detection-link]: https://github.com/ten-framework/ten-turn-detection
[ten-turn-detection-shield]: https://img.shields.io/github/stars/ten-framework/ten-turn-detection?color=ffcb47&labelColor=gray&style=flat-square&logo=github
[ten-turn-detection-banner]: https://github.com/user-attachments/assets/c72d82cc-3667-496c-8bd6-3d194a91c452

[ten-agent-example-link]: https://github.com/TEN-framework/ten-framework/tree/main/ai_agents/agents/examples
[ten-agent-example-banner]:https://github.com/user-attachments/assets/7f735633-c7f6-4432-b6b4-d2a2977ca588

[ten-portal-link]: https://github.com/ten-framework/portal
[ten-portal-shield]: https://img.shields.io/github/stars/ten-framework/portal?color=ffcb47&labelColor=gray&style=flat-square&logo=github
[ten-portal-banner]: https://github.com/user-attachments/assets/f56c75b9-722c-4156-902d-ae98ce2b3b5e


<!-- Localized READMEs -->
[lang-en-badge]: https://img.shields.io/badge/English-lightgrey
[lang-en-readme]: https://github.com/TEN-framework/ten-vad/blob/main/README.md
[lang-zh-badge]: https://img.shields.io/badge/简体中文-lightgrey
[lang-zh-readme]: https://github.com/bluemotional/ten-vad/blob/main/docs/README-CN.md