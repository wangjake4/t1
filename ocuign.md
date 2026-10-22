代发 wailian999

[U89] JS：数组去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gwuiavec.html

[...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gt2omipxwgi.html

[U90] JS：数字数组排序
来源：http://dali.tianlin.xyz/Article/details/gt2ssuasbnh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gt2oixzjhhp.html

[U91] JS：对象键值遍历
来源：http://dali.ydzc1.top/Article/details/gt2qviufkfq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hongshengwenyu.top/Article/details/gt2ivhqnxfo.html

[U92] JS：深拷贝
来源：http://dali.daria6918.cn/Article/details/gt2vqngosfx.html

structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gt2jhdpogmc.html

[U93] JS：模板字符串
来源：http://dali.meibo888.top/Article/details/gt2mcrytkdw.html

`共 ${n} 条`
来源：http://dali.zhiwuduotai.top/Article/details/gt2rcpqxdqc.html

[U94] JS：箭头函数
来源：http://dali.hysaishi.cn/Article/details/gt2ftsscbew.html

const double = x => x * 2;
来源：http://dali.aibaodan.cn/Article/details/gt2olsjoexb.html

[U95] JS：Promise 包装
来源：http://dali.yanxiufei.cn/Article/details/gt2mgwlwmur.html

new Promise((resolve, reject) => {})
来源：http://dali.smart0.xyz/Article/details/gt2qlnnuawg.html

[U96] JS：async/await 与异常
来源：http://dali.haohaochexian.top/Article/details/gt2fsddtoqc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gt2hhrewfoc.html

[U97] JS：并发请求
来源：http://dali.jinqigufen.top/Article/details/gt2zerjjksg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gt2vhnywprf.html

[U98] JS：fetch 带 JSON
来源：http://dali.birdmap.top/Article/details/gt2evzbnroy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zycfv.cn/Article/details/gt2whpwijqu.html

[U99] JS：事件监听
来源：http://dali.chenzaomai.com/Article/details/gt2sdueznrz.html

el.addEventListener("click", e => {})
来源：http://dali.zhengqikj.top/Article/details/gt2ofqdwndg.html

[U100] JS：DOM 查询
来源：http://dali.9152youxi.cn/Article/details/gt2ijvdjmat.html

document.querySelector(".item")
来源：http://dali.tanke756.top/Article/details/gt2ofaldtjv.html

[U101] JS：classList 操作
来源：http://dali.jinqigufen.top/Article/details/gt2kysxpoap.html

el.classList.toggle("active")
来源：http://dali.fzhhl.top/Article/details/gt2wcjzjahl.html

[U102] JS：本地存储
来源：http://dali.c1oappe.top/Article/details/gt2wnzaoiyd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.daxiang520.top/Article/details/gt2aymfyqtf.html

[U103] JS：定时器
来源：http://dali.yvedp.cn/Article/details/gt2zcfjpdys.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.daxiang520.top/Article/details/gt2bohlinpl.html

[U104] JS：防抖
来源：http://dali.yuxming.cn/Article/details/gt2bwsgdaxf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gt2bcahctxs.html

[U105] JS：节流
来源：http://dali.xinyue.icu/Article/details/gt2hyuixwuv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ppjwa.cn/Article/details/gt2wiaguqgz.html

[U106] JS：日期格式化
来源：http://dali.cdnleiting.top/Article/details/gt2kbkeirut.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yangfankeji.com/Article/details/gt2arfbteew.html

[U107] JS：数字千分位
来源：http://dali.sweek.top/Article/details/gt2imupabha.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vtcroaxq.html

[U108] JS：随机整数
来源：http://dali.yj20258888.top/Article/details/gt2rxtzufrq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.havefunace.top/Article/details/gt2wqyygpga.html

[U109] JS：数组分组
来源：http://dali.meibo888.top/Article/details/gt2fnoyrisw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yahzkxxq.html

[U110] JS：数组分块
来源：http://dali.xuetiantiany.cn/Article/details/gt2fvworqpf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.aibaodan.cn/Article/details/gt2vagckqwj.html

[U111] JS：对象转 Map
来源：http://dali.hnxiangtu.top/Article/details/gt2nczezqjm.html

new Map(Object.entries(obj))
来源：http://dali.chenjidiqi.icu/Article/details/gt2gituqvjw.html

[U112] JS：字符串补位
来源：http://dali.cashguo.top/Article/details/gt2xdnwkjmr.html

"7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gt2wqwmgmzj.html

[U113] JS：正则替换全部
来源：http://dali.fengsongda.top/Article/details/gt2meitnots.html

s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2qvvynyef.html

[U114] JS：JSON 深比较
来源：http://dali.cheryme.top/Article/details/gt2fhdxpqwc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guannengcc.top/Article/details/gt2dnitvgju.html

[U115] JS：生成 UUID
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qftqqine.html

crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gt2gktcgmiz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2spfwqnfq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gotoacloud.top/Article/details/gt2rgkiyqnu.html

[U117] JS：单元测试
来源：http://dali.xylfe.cn/Article/details/gt2jfylhmpa.html

npm i -D vitest;  npx vitest
来源：http://dali.nanxinkj.top/Article/details/gt2wdljmwty.html

[U118] JS：开发服务器
来源：http://dali.jinqigufen.top/Article/details/gt2lfzxdpoc.html

npm i -D vite;  npx vite
来源：http://dali.zhongyouzk.top/Article/details/gt2rmaqcvdf.html

[U119] JS：生产构建
来源：http://dali.ydzc1.top/Article/details/gt2frckijhp.html

npx vite build
来源：http://dali.tianlin.xyz/Article/details/gt2zbtvqrif.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.guannengcc.top/Article/details/gt2dsredani.html

import.meta.env.VITE_API_URL
来源：http://dali.tian-w.cn/Article/details/gt2kfdjasfi.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2exdmfost.html

统计汇总
来源：http://dali.jlsjyb.cn/Article/details/gt2pzhnqzde.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2ndnybavu.html

按语言统计（条）：
来源：http://dali.hysaishi.cn/Article/details/gt2skbvyahv.html

Python ......... 252
来源：http://dali.jinqigfzy.top/Article/details/gt2xxuljfoj.html

PHP ............ 252
来源：http://dali.316326.xyz/Article/details/gt2fqosdqcy.html

JavaScript ..... 252
来源：http://dali.fzhhl.top/Article/details/gt2fbkpqerl.html

TypeScript ..... 212
来源：http://dali.kuanghao11.cn/Article/details/gt2kvbkzrgq.html

Java ........... 212
来源：http://dali.tian-w.cn/Article/details/gt2fncmigva.html

Go ............. 212
来源：http://dali.guannengcc.top/Article/details/gt2ctwbzlch.html

Ruby ........... 212
来源：http://dali.yj20258.top/Article/details/gt2keleouej.html

C# ............. 212
来源：http://dali.guannengcc.top/Article/details/gt2zfaqhdng.html

C .............. 30
来源：http://dali.nanxuanxn.top/Article/details/gt2ynionsoa.html

C++ ............ 30
来源：http://dali.yueranfly.top/Article/details/gt2qvjaqblo.html

SQL ............ 90
来源：http://dali.jqgfzy.top/Article/details/gt2fzrruvef.html

Bash ........... 80
来源：http://dali.hammf.cn/Article/details/gt2vcysnpox.html

Kotlin ......... 15
来源：http://dali.cashguo.top/Article/details/gt2mcsjfaan.html

Swift .......... 15
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qhukielq.html

Lua ............ 10
来源：http://dali.wangshuangyany.cn/Article/details/gt2yunmeqky.html

Perl ........... 10
来源：http://dali.shangyingyoupin.top/Article/details/gt2jvscwpmo.html

Scala .......... 10
来源：http://dali.hnxiangtu.top/Article/details/gt2ncdbctpt.html

------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nqvoavsf.html

合计 ........... 2106 条
来源：http://dali.gogol.net.cn/Article/details/gt2tnlxmhgm.html

按章节统计：
来源：http://dali.xuetiantiany.cn/Article/details/gt2rajljawz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rllkvnlt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sysykeji.top/Article/details/gt2gxsjhuhl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gt2jwhhcqcv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gotoacloud.top/Article/details/gt2tvkmstif.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hikthnmf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xuetiantiany.cn/Article/details/gt2skxxjalk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ivvv.top/Article/details/gt2htinbjfg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yj202588.top/Article/details/gt2wqpviwol.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gt2fwepyfta.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinqigfzy.top/Article/details/gt2cwhazxbu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gt2twcwyqoh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gt2pcknsvnw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gt2lwdffmwe.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.aizwys.cn/Article/details/gt2ezrnlbja.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.pengpengdd.cyou/Article/details/gt2tkkfioui.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gt2yerigqls.html

Q SQL 专题                              90
来源：http://dali.c1oappe.top/Article/details/gt2btsbnfvi.html

R Bash 专题                             80
来源：http://dali.gotoacloud.top/Article/details/gt2zyelkvuj.html

S C / C++ 专题                          60
来源：http://dali.yj202588.top/Article/details/gt2vuclgbwi.html

T 其他语言补充                          60
来源：http://dali.9152youxi.cn/Article/details/gt2hheqilav.html

U 高频实用片段                         120
来源：http://dali.chenlongwang.top/Article/details/gt2pvvtbgvh.html

------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gt2fnlqfdfe.html

合计                                  2106 条
来源：http://dali.shangyingyoupin.top/Article/details/gt2qqtonywe.html

--------------------------------------------------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gt2xfgdizih.html

使用提醒
来源：http://dali.pengpengdd.cyou/Article/details/gt2hqdfjcno.html

--------------------------------------------------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gt2tefcrnhp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.guowangkeji.top/Article/details/gt2ytadrety.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.0kj1m.cn/Article/details/gt2hjjnkvyb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.fzhhl.top/Article/details/gt2kiyhjkbh.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zdqjudy.top/Article/details/gt2bxqcbweu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.vqdsnc.cn/Article/details/gt2lxktcchz.html

—— 文件结束 ——
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ldikdvpp.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2xrzwhsln.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhiwuduotai.top/Article/details/gt2nlqvkqhb.html

Common Programming Examples Cheat Book
来源：http://dali.xinyue.icu/Article/details/gt2kkykctya.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2ffmsskno.html

【收录内容】
来源：http://dali.zhoulong.xyz/Article/details/gt2ylrfegxo.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.fengsongda.top/Article/details/gt2hinljeel.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.snrcjt.cn/Article/details/gt2lzpcfpig.html

SQL · Bash · C · C++
来源：http://dali.cucudq.cn/Article/details/gt2iptrjxle.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.gaohongyu789.top/Article/details/gt2qrgieref.html

【使用说明】
来源：http://dali.smart0.xyz/Article/details/gt2zzvoajgl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.nanxuanxn.top/Article/details/gt2bddmcyxh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhengqikj.top/Article/details/gt2ainyulsd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yongpay.top/Article/details/gt2dnjbeozx.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jinqigufen.top/Article/details/gt2fbtprxmq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hammf.cn/Article/details/gt2vspcwbcz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhengqikj.top/Article/details/gt2ggapcrdx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.iojbl.cn/Article/details/gt2yxtnonjf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.dashuyun.cn/Article/details/gt2nohwmnqp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.0kj1m.cn/Article/details/gt2makzkqai.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.chenzaomai.com/Article/details/gt2urgluxfl.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xylfe.cn/Article/details/gt2vlgmelxc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hnqzz.top/Article/details/gt2fqfbsvnx.html

【文件统计】
来源：http://dali.hnxiangtu.top/Article/details/gt2oootexbf.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xuetiantiany.cn/Article/details/gt2jffzqhut.html

--------------------------------------------------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gt2lflumoph.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2pymifprd.html

--------------------------------------------------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gt2lyybzijg.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jinqigufen.top/Article/details/gt2uzqoeuzs.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2vhwbvqrh.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ocjzkxzn.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ppjwa.cn/Article/details/gt2gshnlgdd.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hammf.cn/Article/details/gt2pynolxqh.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.dashuyun.cn/Article/details/gt2vlhjzzao.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.birdmap.top/Article/details/gt2cnijotfj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xziqi.cn/Article/details/gt2wpvrbkgb.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhengqikj.top/Article/details/gt2izjyxucz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.sufxvd.cn/Article/details/gt2jhsmpqyp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gt2zdtxikls.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tandiiuw.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gt2xrkkszxv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xinyue.icu/Article/details/gt2delftzrn.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sufxvd.cn/Article/details/gt2nrlvlxgu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gt2oezqkbdp.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cheryme.top/Article/details/gt2jrsimbky.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cdnleiting.top/Article/details/gt2kmbvqlsj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.wangdashe.top/Article/details/gt2irwjwajk.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.mhx1999.top/Article/details/gt2scrlowas.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2yqrkfwgj.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2hlwfcywi.html

A. 基础语法与类型
来源：http://dali.xinyue.icu/Article/details/gt2atadpxub.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2uyklrpbl.html

[A01] Hello World
来源：http://dali.havefunace.top/Article/details/gt2nzenzwlx.html

Py:   print("Hello, World!")
来源：http://dali.0kj1m.cn/Article/details/gt2czunonzu.html

PHP:  echo "Hello, World!";
来源：http://dali.jqgufenzy.top/Article/details/gt2xfkgwyzd.html

JS:   console.log("Hello, World!");
来源：http://dali.jqgufenzy.top/Article/details/gt2mufqilsg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xylfe.cn/Article/details/gt2wcadaivs.html

Java: System.out.println("Hello, World!");
来源：http://dali.iojbl.cn/Article/details/gt2yvqqxbik.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eveviwdy.html

Ruby: puts "Hello, World!"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wqkfiqqg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.cheryme.top/Article/details/gt2shpmeicl.html

[A02] 变量声明与赋值
来源：http://dali.havefunace.top/Article/details/gt2syeelfbp.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vvakugxk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.tian-w.cn/Article/details/gt2whwwrczg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jinqigufen.top/Article/details/gt2nuweesup.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.0kj1m.cn/Article/details/gt2hartgjfk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hysaishi.cn/Article/details/gt2bumewgtc.html

Go:   name := "Alex"; age := 20
来源：http://dali.mhx1999.top/Article/details/gt2xnunyvfx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hywenlv.cn/Article/details/gt2xqasktmw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ofctsuzf.html

[A03] 常量定义
来源：http://dali.haohaochexian.top/Article/details/gt2igvskjnd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.chenlongwang.top/Article/details/gt2zuixwtmw.html

PHP:  const PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gt2abknqyqo.html

JS:   const PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gt2kuiaxypk.html

TS:   const PI: number = 3.14159;
来源：http://dali.yj202588.top/Article/details/gt2vcfbntzh.html

Java: static final double PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gt2infomrbb.html

Go:   const PI = 3.14159
来源：http://dali.birdmap.top/Article/details/gt2cbzpxtzd.html

Ruby: PI = 3.14159
来源：http://dali.feifeiyinyue.top/Article/details/gt2iyowiivf.html

C#:   const double PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gt2szzkfyqx.html

[A04] 判断变量类型
来源：http://dali.ehwqpu.com/Article/details/gt2dpidyxgp.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.tian-w.cn/Article/details/gt2swjvprve.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jiagoushi.top/Article/details/gt2pgmsmgor.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yuxming.cn/Article/details/gt2isahrexy.html

TS:   typeof x; x instanceof Date
来源：http://dali.guannengcc.top/Article/details/gt2dtvipvrr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.aizwys.cn/Article/details/gt2kusayeah.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.aibaodan.cn/Article/details/gt2mgslpeit.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jinqigfzy.top/Article/details/gt2zymektby.html

C#:   x.GetType().Name; x is int
来源：http://dali.yongpay.top/Article/details/gt2wrcpbokn.html

[A05] 整数除法与取模
来源：http://dali.hammf.cn/Article/details/gt2hphupage.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.pycfn.com/Article/details/gt2lmotiaua.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gt2jkglmhmg.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tanke756.top/Article/details/gt2rcrbhgnw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.wangdashe.top/Article/details/gt2bakoomxg.html

Java: 7 / 2; 7 % 2
来源：http://dali.iojbl.cn/Article/details/gt2wqzddhgf.html

Go:   7 / 2; 7 % 2
来源：http://dali.bjfxy.top/Article/details/gt2zsbumyvw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.nanxuanxn.top/Article/details/gt2liirixpz.html

C#:   7 / 2; 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gt2ajbonmox.html

[A06] 字符串转数字
来源：http://dali.xinyue.icu/Article/details/gt2mwkhdqfa.html

Py:   int("42"); float("3.14")
来源：http://dali.yueranfly.top/Article/details/gt2benkjtzs.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.sxryk.cn/Article/details/gt2ndtvkogg.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.guowangkeji.top/Article/details/gt2hqhxmoxf.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.feifeiyinyue.top/Article/details/gt2guhujtzc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jyoumei.cn/Article/details/gt2hbbxwqho.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ydzc1.top/Article/details/gt2rhxtpijy.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.tian-w.cn/Article/details/gt2mdpioobs.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.iojbl.cn/Article/details/gt2gnfztyya.html

[A07] 数字转字符串
来源：http://dali.wangdashe.top/Article/details/gt2xtgindtq.html

Py:   str(42)
来源：http://dali.shuidangran.top/Article/details/gt2ugddlcse.html

PHP:  (string) 42; strval(42)
来源：http://dali.hnqzz.top/Article/details/gt2xxenoscl.html

JS:   String(42); (42).toString()
来源：http://dali.cucudq.cn/Article/details/gt2tazutrlg.html

TS:   String(42)
来源：http://dali.ivvv.top/Article/details/gt2jddqqymv.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.9152youxi.cn/Article/details/gt2ejnxnlsu.html

Go:   strconv.Itoa(42)
来源：http://dali.ydzc1.top/Article/details/gt2nhcdzrgm.html

Ruby: 42.to_s
来源：http://dali.aibaodan.cn/Article/details/gt2andgnaae.html

C#:   42.ToString()
来源：http://dali.daxiang520.top/Article/details/gt2qkmgsagm.html

[A08] 取整与四舍五入
来源：http://dali.316326.xyz/Article/details/gt2berbfxxb.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.mhx1999.top/Article/details/gt2nxawzomi.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.fzhhl.top/Article/details/gt2jnucmucl.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jyoumei.cn/Article/details/gt2zjvmcmfx.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.bjfxy.top/Article/details/gt2yategked.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.tianlin.xyz/Article/details/gt2eceoaacv.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gt2wqtqdxps.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jqgfzy.top/Article/details/gt2loqymzfb.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.fengsongda.top/Article/details/gt2osksxqre.html

[A09] 绝对值与最大最小值
来源：http://dali.yuxming.cn/Article/details/gt2xmkuixrp.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2cgplnzjg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gt2ywxoidqx.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2zdkuxdah.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.xziqi.cn/Article/details/gt2xrkklupr.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gt2ssgxlaqh.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.316326.xyz/Article/details/gt2agivlvbh.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.tanke756.top/Article/details/gt2ftchgaxk.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dlswpldj.html

[A10] 生成随机数
来源：http://dali.hfpthk.cn/Article/details/gt2xrenkids.html

Py:   import random; random.randint(1, 100)
来源：http://dali.tanke756.top/Article/details/gt2zhksynnt.html

PHP:  random_int(1, 100);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ldwxvqcz.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yj20258888.top/Article/details/gt2jqpbcold.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2sicynwei.html

Java: new Random().nextInt(100) + 1
来源：http://dali.nanxinkj.top/Article/details/gt2vxbztvwp.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.9152youxi.cn/Article/details/gt2xskhubbw.html

Ruby: rand(1..100)
来源：http://dali.jyoumei.cn/Article/details/gt2uaukfuco.html

C#:   new Random().Next(1, 101)
来源：http://dali.hammf.cn/Article/details/gt2ciswaltp.html

[A11] 条件表达式（三元）
来源：http://dali.jinqigufen.top/Article/details/gt2eagmkiyl.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.pycfn.com/Article/details/gt2dglgbmym.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.nanxinkj.top/Article/details/gt2qnsnxlho.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jqgfzy.top/Article/details/gt2lcdqppcx.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yonumen.top/Article/details/gt2xbduzztx.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.sufxvd.cn/Article/details/gt2zotrdeep.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jiagoushi.top/Article/details/gt2kemqoaut.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.meibo888.top/Article/details/gt2bholdegh.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.0kj1m.cn/Article/details/gt2pmpwgmfw.html

[A12] 字符串插值 / 格式化
来源：http://dali.wangdashe.top/Article/details/gt2dfwbjmyu.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jinqigufen.top/Article/details/gt2vlbmifpn.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jqgfzy.top/Article/details/gt2ttjehzuo.html

JS:   `Hello, ${name}!`
来源：http://dali.quarkkingdee.top/Article/details/gt2nnlpwnyn.html

TS:   `Hello, ${name}!`
来源：http://dali.xylfe.cn/Article/details/gt2rgpvscwt.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jianghu66.top/Article/details/gt2ioldzpje.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.nanxuanxn.top/Article/details/gt2eeutypbb.html

Ruby: "Hello, #{name}!"
来源：http://dali.yvedp.cn/Article/details/gt2mznemtwd.html

C#:   $"Hello, {name}!"
来源：http://dali.zhengqikj.top/Article/details/gt2olxtckln.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.ehwqpu.com/Article/details/gt2dnlmqlma.html

Py:   "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gt2ytevqfyp.html

PHP:  "第一行\n第二行"
来源：http://dali.9152youxi.cn/Article/details/gt2sjmhmufr.html

JS:   "第一行\n第二行"
来源：http://dali.yuanzhike.top/Article/details/gt2iivnmdpb.html

TS:   "第一行\n第二行"
来源：http://dali.jqgfzy.top/Article/details/gt2dmabkviw.html

Java: "第一行\n第二行"
来源：http://dali.xuanzx.com/Article/details/gt2tzvuvrra.html

Go:   "第一行\n第二行"
来源：http://dali.jqgufenzy.top/Article/details/gt2cxwflymi.html

Ruby: "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gt2vtzsbymp.html

C#:   "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gt2wezrbino.html

[A14] 注释写法
来源：http://dali.sweek.top/Article/details/gt2aaaveusk.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yj202588.top/Article/details/gt2qmgoiozp.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.daria6918.cn/Article/details/gt2qhvbixjk.html

JS:   // 单行；/* 多行 */
来源：http://dali.daria6918.cn/Article/details/gt2jemoultf.html

TS:   // 单行；/* 多行 */
来源：http://dali.hnqzz.top/Article/details/gt2gxmsqilq.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.ppjwa.cn/Article/details/gt2onintsqv.html

Go:   // 单行；/* 多行 */
来源：http://dali.aizwys.cn/Article/details/gt2hqdpkwdy.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.bjfxy.top/Article/details/gt2moxxylrs.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsnahnp.html

[A15] 空值判断与默认值
来源：http://dali.yonumen.top/Article/details/gt2lublvoqn.html

Py:   value = data or "默认值"
来源：http://dali.chenlongwang.top/Article/details/gt2fsuwsuqa.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.cashguo.top/Article/details/gt2utfwgjqm.html


<!-- 参考信息 -->