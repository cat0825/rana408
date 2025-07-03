---
{"dg-publish":true,"dg-permalink":"/Welcome🎉","permalink":"/Welcome🎉/","tags":["gardenEntry"],"dgShowBacklinks":true,"dgShowLocalGraph":true,"dgShowInlineTitle":true}
---

<html>
  <head>
    <meta charset="utf-8">
    <title>408考研计算机启发性问题集（Demo版）</title>
    <style>
      body { font-family: 'PingFang SC', 'Microsoft YaHei', Arial, sans-serif; background: #f8f9fa; color: #222; margin: 0; padding: 0; }
      .container { max-width: 900px; margin: 40px auto; background: #fff; border-radius: 12px; box-shadow: 0 2px 12px #0001; padding: 36px 32px; }
      h1, h2, h3 { color: #4F8EF7; }
      ul { line-height: 1.8; }
      .badge { margin-right: 8px; }
      .right { text-align: right; }
      a { color: #4F8EF7; text-decoration: none; }
      a:hover { text-decoration: underline; }
      .warn { color: #e67e22; font-weight: bold; }
    </style>
  </head>
  <body>
    <div class="container">
      <div align="center">
        <h1>408考研计算机启发性问题集（Demo版）</h1>
        <p style="font-size:1.2em;">专为考研学子打造的408启发性问题笔记库</p>
        <img class="badge" src="https://img.shields.io/badge/OS-操作系统-blue" />
        <img class="badge" src="https://img.shields.io/badge/状态-Demo--预览版-orange" />
      </div>
      <br>
      <div style="font-size:1.1em;">
        <h2>📢 网站说明</h2>
        <p>
          本网站<strong>主要收集和整理408考研科目中的启发性问题</strong>，旨在帮助同学们开阔思路、发现知识盲区、提升理解深度。<br>
          <span class="warn">注意：</span>本网站<strong>不是</strong>一份全面的复习指南，也不包含所有基础知识点。请结合权威教材和系统课程进行复习，本网站内容仅供查漏补缺和思维训练参考。
        </p>
        <center>
          <h2>📢 紧急集结！408老兵连队，虚位以待！</h2>
          <h3>请即刻加入我们，一同征服考研408的战场！</h3>
          <h3><a href="https://live.bilibili.com/84074?session_id=06eeaec7317c8b3572d06fd19e67ff7d_A326AF39-2F03-49D4-B61B-6C2520C0C691&launch_id=1000216&live_from=71001">不引流了,千万不要点这个链接</a></h3>
        </center>
        <h2>📚 目录导航</h2>
        <ul>
          <li><b>数据结构</b>（待补充）</li>
          <li><b>计算机组成原理</b>（待补充）</li>
          <li><b>操作系统</b>
            <ul>
              <li>第一章：
                <ul>
                  <li>通道技术</li>
                  <li>中断处理程序</li>
                  <li>中断处理和子程序调用对寄存器的保存情况</li>
                  <li>从检测到中断信号到中断处理完成的流程解析</li>
                  <li>中断信号的优先级，多重中断的处理</li>
                  <li>通道技术和DMA的区别解释</li>
                  <li>操作系统当中的引导程序</li>
                  <li>关于所有的中断</li>
                </ul>
              </li>
              <li>进程与线程：
                <ul>
                  <li>进程映像的概念</li>
                  <li>死锁的四个必要条件</li>
                  <li>临界资源与共享资源</li>
                  <li>互斥信号量与同步信号量</li>
                  <li>signal操作与V操作</li>
                  <li>死锁避免、预防、检测算法</li>
                  <li>资源分配图</li>
                  <li>用户级线程为什么阻塞一个就全部阻塞了</li>
                  <li>多线程模型</li>
                  <li>管程</li>
                  <li>互斥与同步机制及其算法</li>
                  <li>PCB当中存储了什么</li>
                </ul>
              </li>
              <li>内存管理：
                <ul>
                  <li>动态分区算法</li>
                  <li>共享段、共享页</li>
                  <li>分页管理与分段管理下的动态链接</li>
                  <li>主存和外存的数据交换单位</li>
                  <li>段页式管理下的地址映射表组织</li>
                  <li>区分页目录表当中的表项和页表的页表项的逻辑地址结构组成</li>
                  <li>虚拟地址的生命周期</li>
                  <li>页式管理与段式管理内存</li>
                </ul>
              </li>
              <li>文件系统：
                <ul>
                  <li>close()与write()操作的思考</li>
                  <li>read()操作的工作流程</li>
                  <li>文件的逻辑结构以及索引文件</li>
                  <li>内存索引节点和磁盘索引节点你俩到底是什么关系</li>
                  <li>目录检索算法，一个文件检索的生命流程</li>
                  <li>成组链接法你怎么和空闲盘号栈有一腿</li>
                  <li>目录文件与inode节点</li>
                  <li>关于进程级打开文件表与系统级打开文件表</li>
                  <li>关于文件分配</li>
                  <li>内存映射文件</li>
                </ul>
              </li>
              <li>I/O管理：
                <ul>
                  <li>IO层次结构以及每层的作用</li>
                  <li>IO设备根据数据的存取和传输进行的分类</li>
                  <li>设备驱动程序的生命周期</li>
                  <li>IO的独立编址与统一编址，状态&控制寄存器</li>
                  <li>设备相关的数据结构以及根据逻辑设备名分配设备的具体流程</li>
                  <li>磁盘的低级格式化和高级格式化都进行了什么工作</li>
                </ul>
              </li>
            </ul>
          </li>
          <li><b>计算机网络</b>（待补充）</li>
        </ul>
        <h2>📬 反馈与贡献</h2>
        <p>如有建议、内容补充或发现问题，欢迎通过 <a href="mailto:meowovo1@gmail.com">meowovo1@gmail.com</a> 提交 issue 或联系作者。</p>
        <h2>🌱 未来规划</h2>
        <ul>
          <li>持续补充数据结构、计组、计网等408其他模块内容</li>
        </ul>
        <p class="right">👉 <a href="/408/导航">点我查看导航</a></p>
        <p style="color:#e74c3c;font-weight:bold;">你们千万不要加我的WeChat和我一起讨论408 千万不要!</p>
        <img src="附件/wechat.png" style="max-width:100%;border-radius:8px;box-shadow:0 1px 8px #0002;" alt="408考研笔记示意图">
      </div>
    </div>
  </body>
</html>
![wechat.png](/img/user/%E9%99%84%E4%BB%B6/wechat.png)