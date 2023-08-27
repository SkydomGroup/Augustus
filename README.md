# Augustus

<div align=center>
    <img src="./Skydom.png">
    <br /><br />
    <p>A fork of <a href="https://GitHub.com/PaperMC/Paper">Paper</a> that modifies functions prohibited by Paper.</p>
</div>

[![Augustus CI](https://img.shields.io/github/actions/workflow/status/SkydomGroup/Augustus/Release.yml)](https://GitHub.com/SkydomGroup/Augustus/releases)
[![GitHub](https://img.shields.io/github/license/SkydomGroup/Augustus)](https://GitHub.com/SkydomGroup/Augustus/blob/master/LICENSE)


## English

### What is it?

* This project is a branch of [Paper](https://PaperMC.io/software/paper).
* [Paper's Repository](https://GitHub.com/PaperMC/Paper/)
* [Paper's Website](https://PaperMC.io/software/paper)
* The server core of [Minecraft Skydom Server](https://www.Skydom.org/) technology survival mode.

### What has been modified?

* Changed return information.
* Added support for sand during.
* Unprotected blocks.
* Fix tripwire update.

### How to use it?

#### The first method.
* Download the compiled Jar from [Release](https://github.com/SkydomGroup/Augustus/releases).

#### The second approach.
* Clone this repo.
* Run `./gradlew applyPatches`, then `./gradlew createReobfPaperclipJar` from your terminal.
* You can find the compiled Jar in the project root's *build/libs* directory.


## 中文(简体)

### 这是什么？

* 这是一个 [Paper](https://PaperMC.io/software/paper) 的分支。
* [Paper 的存储库](https://GitHub.com/PaperMC/Paper/)
* [Paper 的官方网站](https://PaperMC.io/software/paper)
* [Minecraft Skydom Server](https://www.Skydom.org/) 生电服所使用的核心。

### 修改了什么？

* 更改了返回信息。
* 新增了对刷沙机的支持。
* 取消了对方块的保护。
* 新增了对刷线机的支持。

### 我该如何使用它？

#### 第一种办法。
* 到 [Release](https://github.com/SkydomGroup/Augustus/releases) 去下载编译好的Jar。

#### 第二种办法。
* 克隆这个存储库。
* 打开你的终端并运行 `./gradlew applyPatches`后，再运行`./gradlew createReobfPaperclipJar` 。
* 运行完成后，您可以在 *build/libs* 找到构建好的Jar。