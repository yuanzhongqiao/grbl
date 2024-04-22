<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/gnea/gnea-Media/blob/master/Grbl%20Logo/Grbl%20Logo%20250px.png?raw=true"><img src="https://github.com/gnea/gnea-Media/raw/master/Grbl%20Logo/Grbl%20Logo%20250px.png?raw=true" alt="GitHub 徽标" style="max-width: 100%;"></a></p>
<hr>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Grbl v1.1 已经</font></font><a href="https://github.com/gnea/grbl/releases"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在这里</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发布了！</font></font></h3><a id="user-content-grbl-v11-has-been-released-here" class="anchor" aria-label="永久链接：Grbl v1.1 已发布！" href="#grbl-v11-has-been-released-here"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通知：本站将被淘汰并迁移至新站！</font></font></h3><a id="user-content-notice-this-site-will-be-phased-out-and-moved-to-the-new-one" class="anchor" aria-label="永久链接：通知：该网站将被淘汰并迁移至新网站！" href="#notice-this-site-will-be-phased-out-and-moved-to-the-new-one"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<hr>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Grbl 是 CNC 铣削中基于并行端口的运动控制的不折不扣、高性能、低成本的替代方案。只要配备 Atmega 328，它就可以在普通 Arduino (Duemillanove/Uno) 上运行。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该控制器采用高度优化的 C 语言编写，利用 AVR 芯片的每一项巧妙功能来实现精确定时和异步操作。它能够维持高达 30kHz 的稳定、无抖动控制脉冲。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">它接受符合标准的 G 代码，并已通过多种 CAM 工具的输出进行测试，没有出现任何问题。完全支持圆弧、圆和螺旋运动以及所有其他主要 G 代码命令。不支持宏函数、变量和大多数固定循环，但我们认为 GUI 无论如何可以更好地将它们转换为直接的 G 代码。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Grbl 包括具有前瞻性的完整加速管理。这意味着控制器将查看未来多达 18 种运动，并提前规划其速度，以提供平稳的加速和无冲击的转弯。</font></font></p>
<ul dir="auto">
<li>
<p dir="auto"><a href="https://github.com/grbl/grbl/wiki/Licensing"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">许可</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：Grbl 是免费软件，根据 GPLv3 许可证发布。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如需更多信息和帮助，请查看我们的</font></font><strong><a href="https://github.com/grbl/grbl/wiki"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Wiki 页面！</font></font></a></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您发现该信息已过时，请通过编辑或通知我们的社区来帮助我们保持更新！谢谢！</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">首席开发人员 [ </font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2011 年至今</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">]：Sungeun(Sonny) K. Jeon，博士（美国）又名@chamnit</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">首席开发人员 [ </font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2009 - 2011</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ]：Simen Svale Skogsrud（挪威）。又名 Grbl 的创始人/创造者/先驱/之父。</font></font></p>
</li>
</ul>
<hr>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Grbl CNC 项目的官方支持者</font></font></h3><a id="user-content-official-supporters-of-the-grbl-cnc-project" class="anchor" aria-label="永久链接：Grbl CNC 项目的官方支持者" href="#official-supporters-of-the-grbl-cnc-project"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/gnea/gnea-Media/blob/master/Contributors.png?raw=true"><img src="https://github.com/gnea/gnea-Media/raw/master/Contributors.png?raw=true" alt="官方支持者" style="max-width: 100%;"></a></p>
<hr>
<p dir="auto"><em><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">总支：</font></font></strong></em></p>
<ul dir="auto">
<li><a href="http://bit.ly/1I8Ey4S" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Grbl v0.9j Atmega328p 16mhz 115200baud 具有通用默认值</font></font></a> <em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">(2016-03-17)</font></font></em>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">升级到 GRBL v0.9 时的重要信息：</font></font></strong></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">波特率现在为</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">115200</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（之前为 9600）。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">归位循环已更新。基于开关触发器而不是释放点定位。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">现在默认启用可变主轴。 Z 限位(D12) 和主轴使能(D11) 已切换为访问D11 上的硬件PWM。如果您不将 Z 限位开关重新连接到 D12，则归位将不起作用。</font></font></li>
</ul>
</li>
</ul>
<p dir="auto"><em><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">档案：</font></font></strong></em></p>
<ul dir="auto">
<li><a href="http://bit.ly/1EiviDk" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Grbl v0.9i Atmega328p 16mhz 115200baud 具有通用默认值</font></font></a></li>
<li><a href="http://bit.ly/1m8E1Qa" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Grbl v0.9g Atmega328p 16mhz 115200baud 具有通用默认值</font></font></a></li>
<li><a href="http://bit.ly/SSdCJE" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Grbl v0.8c Atmega328p 16mhz 9600 波特</font></font></a></li>
<li><a href="http://bit.ly/ZhL15G" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Grbl v0.7d Atmega328p 16mhz 9600 波特</font></font></a></li>
<li><a href="http://bit.ly/VD04A5" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Grbl v0.6b Atmega328p 16mhz 9600 波特</font></font></a></li>
<li><a href="http://bit.ly/W75BS1" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Grbl v0.51 Atmega328p 16mhz 9600 波特</font></font></a></li>
<li><a href="http://bit.ly/SScWnE" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Grbl v0.6b Atmega168 16mhz 9600 波特</font></font></a></li>
<li><a href="http://bit.ly/VXyrYu" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Grbl v0.51 Atmega168 16mhz 9600 波特</font></font></a></li>
</ul>
<hr>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">v0.9j 更新摘要</font></font></h2><a id="user-content-update-summary-for-v09j" class="anchor" aria-label="永久链接：v0.9j 更新摘要" href="#update-summary-for-v09j"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">恢复 EEPROM 功能：</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一组新的恢复 EEPROM 功能，可帮助 OEM 和用户将其 Grbl 安装重置为构建默认值。有关详细信息，请参阅配置 Grbl Wiki。</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">输入引脚的更多配置选项</font></font></strong></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">错误修复包括：</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">软限位错误处理、S0 时禁用主轴、G38.x 的 G 代码报告。</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">v0.9i 更新摘要</font></font></h2><a id="user-content-update-summary-for-v09i" class="anchor" aria-label="永久链接：v0.9i 更新摘要" href="#update-summary-for-v09i"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">重要的：</font></font></strong>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">归位循环已更新。基于触发点而不是释放点定位。</font></font></strong></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">系统调整：$14 周期自动启动已被删除。不再有 QUEUE 状态。</font></font></strong></li>
</ul>
</li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">新 G 代码</font></font></strong></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CoreXY 支持</font></font></strong></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安全门支架</font></font></strong></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">完全限制和控制引脚可配置性</font></font></strong></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其他编译时功能选项</font></font></strong></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">v0.8 至 v0.9h 的更新摘要</font></font></h2><a id="user-content-update-summary-for-v09h-from-v08" class="anchor" aria-label="永久链接：v0.8 至 v0.9h 的更新摘要" href="#update-summary-for-v09h-from-v08"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">重要的：</font></font></strong></p>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认串行波特率现在为 115200！ （原为 9600）</font></font></strong></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Z 限制 (D12) 和主轴启用 (D11) 引脚已切换为支持可变主轴！</font></font></strong></li>
</ul>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">超平滑步进算法</font></font></strong></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">稳定性和稳健性更新</font></font></strong></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">(x4)+ 更快的规划器</font></font></strong></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可通过 Arduino IDE 编译！</font></font></strong></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">G 代码解析器大修</font></font></strong></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">独立的加速度和速度设置</font></font></strong></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">软限制</font></font></strong></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">探测</font></font></strong></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">动态刀具长度偏置</font></font></strong></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">改善电弧性能</font></font></strong></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CPU引脚映射</font></font></strong></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">新的 Grbl 模拟器！ （作者：@jgeisler 和 @ashely）</font></font></strong></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可配置的实时状态报告</font></font></strong></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更新的归航程序</font></font></strong></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可选限制引脚共享</font></font></strong></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可选的可变主轴速度输出</font></font></strong></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其他编译时功能选项</font></font></strong></p>
</li>
<li></li>
</ul>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>List of Supported G-Codes in Grbl v0.9 Master:
  - Non-Modal Commands: G4, G10L2, G10L20, G28, G30, G28.1, G30.1, G53, G92, G92.1
  - Motion Modes: G0, G1, G2, G3, G38.2, G38.3, G38.4, G38.5, G80
  - Feed Rate Modes: G93, G94
  - Unit Modes: G20, G21
  - Distance Modes: G90, G91
  - Arc IJK Distance Modes: G91.1
  - Plane Select Modes: G17, G18, G19
  - Tool Length Offset Modes: G43.1, G49
  - Cutter Compensation Modes: G40
  - Coordinate System Modes: G54, G55, G56, G57, G58, G59
  - Control Modes: G61
  - Program Flow: M0, M1, M2, M30*
  - Coolant Control: M7*, M8, M9
  - Spindle Control: M3, M4, M5
  - Valid Non-Command Words: F, I, J, K, L, N, P, R, S, T, X, Y, Z
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="List of Supported G-Codes in Grbl v0.9 Master:
  - Non-Modal Commands: G4, G10L2, G10L20, G28, G30, G28.1, G30.1, G53, G92, G92.1
  - Motion Modes: G0, G1, G2, G3, G38.2, G38.3, G38.4, G38.5, G80
  - Feed Rate Modes: G93, G94
  - Unit Modes: G20, G21
  - Distance Modes: G90, G91
  - Arc IJK Distance Modes: G91.1
  - Plane Select Modes: G17, G18, G19
  - Tool Length Offset Modes: G43.1, G49
  - Cutter Compensation Modes: G40
  - Coordinate System Modes: G54, G55, G56, G57, G58, G59
  - Control Modes: G61
  - Program Flow: M0, M1, M2, M30*
  - Coolant Control: M7*, M8, M9
  - Spindle Control: M3, M4, M5
  - Valid Non-Command Words: F, I, J, K, L, N, P, R, S, T, X, Y, Z" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</article></div>
