# 环境准备

## 一、安装Lean
* 免安装直接使用在线环境（不建议长期使用）：
    * https://live.lean-lang.org/
* Windows：建议挂代理并直接通过VSCode插件安装
    * 插件：leanprover.lean4
    * 代理：设置环境变量 HTTP_PROXY 和 HTTPS_PROXY
* Linux/Mac：使用命令行一键安装
    * Linux: `wget -q https://raw.githubusercontent.com/leanprover-community/mathlib4/master/scripts/install_debian.sh && bash install_debian.sh ; rm -f install_debian.sh && source ~/.profile`
    * Mac：`bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/leanprover-community/mathlib4/master/scripts/install_macos.sh)" && source ~/.profile`
* 更详细的文档：
    * 中文：https://www.leanprover.cn/install/
    * 英文：https://lean-lang.org/documentation/setup/

## 二、创建工程

* 形式化证明时使用的工程通常需要结合Mathlib
    * 建议直接迁出这个样例工程：
        * https://github.com/leanprover-community/mathematics_in_lean
    * 或者参考我之前的学习工程：
        * https://github.com/tdzl2003/learn_lean/tree/main/math
    * 或是阅读文档建立自己的工程（可能要花掉不少的时间）
* 然后在工程根目录下建立一个自己的子文件夹（如Study），里面存放学习过程的代码。
