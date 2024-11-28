# Slides-Blogs
一些还不错的Slides和Blogs记录

## fuzzilli

- [(Guided-)fuzzing for JavaScript engines](https://saelo.github.io/presentations/offensivecon_19_fuzzilli.pdf) 2019年
- [The hunt for Chromium issue 1072171](https://sensepost.com/blog/2020/the-hunt-for-chromium-issue-1072171/) 2020年
- [Fuzzing JavaScript Engines with Fuzzilli](https://blog.doyensec.com/2020/09/09/fuzzilli-jerryscript.html) 2020年
- 论文：[FuzzIL: Coverage Guided Fuzzing for JavaScript Engines](https://saelo.github.io/papers/thesis.pdf) 2018年
- [How Fuzzilli Works](https://github.com/googleprojectzero/fuzzilli/blob/main/Docs/HowFuzzilliWorks.md)

## Hexacon 2024
- [Caught in the wild, past, present and future by Clem1](https://www.youtube.com/watch?v=2zrcemxCg4Y)
  - Google TAG 分享抓野外 0day 的方法和故事
- [What the hell is Windows's CLIP Service by Philippe Laulheret](https://www.youtube.com/watch?v=9t0Xt40RZEc)\
  - 逆向 Client License Platform，包括微软用到的代码混淆 “Warbird” 的分析
- [0-click RCE on Tesla Model 3 through TPMS Sensors by David Berard & Thomas Imbert](https://www.youtube.com/watch?v=R33cR3ZMTxM)
  - Pwn2Own 黑掉特斯拉 Model 3 的项目揭秘
- [Compromising the Host Kernel from the VMware Guest by Junoh Lee & Gwangun Jung](https://www.youtube.com/watch?v=DSEDpTd3iic)
  - VMWare 虚拟机逃逸，并串联另一个 Windows 漏洞获取宿主机内核权限
- [DMAKiller: DMA to Escape from QEMU/KVM by Yongkang Jia, Yiming Tao & Xiao Lei](https://www.youtube.com/watch?v=wL3LK9Dp4os)
  - 关于逃逸 QEMU 虚拟机的研究。国内的议题，作者们来自@ZJU。值得一提的是他们在24年 GeekCon 新加坡站演示了相关的挑战项目
- [Exploiting File Writes in Hardened Environments by Stefan Schiller](https://www.youtube.com/watch?v=ltmZNTP2KX4)
  - 在文件系统几乎完全只读的环境上，将 nodejs 任意文件上传漏洞转化为控制流劫持漏洞和 ROP 利用。
- [Defense through Offense by Andrew Calvano, Octavian Guzu & Ryan Hall](https://www.youtube.com/watch?v=yXMnpOsiAwA)
  - Facebook 内部安全团队对 Messenger 的蓝军测试，并公开一个已修复的 1-click 远程代码执行细节
- [Tales of a RCE in a video game by Thomas Dubier](https://www.youtube.com/watch?v=bWPSyPyIH1g)
  - Systemization of Knowledge，总结各种游戏 hacking 的手法
- [A New Era of macOS Sandbox Escapes: Diving into an Overlooked Attack Surface and Uncovering 10+ New Vulnerabilities](https://jhftss.github.io/A-New-Era-of-macOS-Sandbox-Escapes/)
  - Mickey 大佬关于 macOS App 沙箱的研究
 
## Browser
- [Bucket Effect on JS Engine: Exploiting Chrome Browser through WASM Flaws](https://www.geekcon.top/js/pdfjs/web/viewer.html?file=/doc/ppt/Bucket_Effect_on_JS_Engine_Exploiting_Chrome_Browser_through_WASM_Flaws_v1.0.pdf)
  - 玄武实验室的佬关于浏览器安全的研究
- [JIT Spray](https://www.matteomalvica.com/blog/2024/06/05/intro-v8-exploitation-maglev/#jit-spraying-shellcode)
