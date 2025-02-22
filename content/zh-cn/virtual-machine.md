---
title: 虚拟机
status: Completed
category: 技术
tags: ["基本原理", "基础设施", ""]
---

## 是什么

虚拟机（VM）是一台计算机及其操作系统，不受特定硬件的约束。
虚拟机依靠 [虚拟化](/zh-cn/virtualization/) 将一台物理计算机分割成多个虚拟计算机。
这种分离使组织和基础设施供应商能够轻松地创建和销毁虚拟机，而不影响底层硬件。

## 解决的问题

虚拟机利用了虚拟化的优势。
当 [裸机](/bare-metal-machine/) 机器被束缚在一个单一的操作系统上时，该机器的资源的使用受到一定的限制。
另外，当一个操作系统被绑定在一个单一的物理机上时，它的可用性直接与该硬件联系在一起。
如果物理机由于维护或硬件故障而脱机，操作系统也会脱机。

## 如何帮助

通过消除操作系统和单一物理机之间的直接关系，你解决了裸机的几个问题：配置时间、硬件利用率和弹性。

由于不需要购买、安装或配置新的硬件来支持它，新计算机的配置时间得到了极大的改善。
虚拟机通过在一台物理机上放置多个虚拟机，使你能够更好地利用现有的物理硬件资源。
不受特定物理机的约束，虚拟机也比物理机更有弹性。
当一台物理机需要下线时，在其上运行的虚拟机可以被转移到另一台机器上，几乎没有停机时间。
