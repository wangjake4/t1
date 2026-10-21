代发 wailian999

[U87] JS：解构默认值
来源：http://dali.smart0.xyz/Article/details/gtznpotxvh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.sxryk.cn/Article/details/gtqyvgukin.html

[U88] JS：对象展开合并
来源：http://dali.cashguo.top/Article/details/gtehvmjrfz.html

{ ...a, ...b }
来源：http://dali.316326.xyz/Article/details/gttrvdlqrj.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gtaqjzykjr.html

[...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gtwgpiahif.html

[U90] JS：数字数组排序
来源：http://dali.jiagoushi.top/Article/details/gtkkbhqapd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gtmommjpqo.html

[U91] JS：对象键值遍历
来源：http://dali.jqgfzy.top/Article/details/gttznoshbr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xziqi.cn/Article/details/gtccbuywke.html

[U92] JS：深拷贝
来源：http://dali.ivvv.top/Article/details/gtqkutlnjz.html

structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gtojlnsjbv.html

[U93] JS：模板字符串
来源：http://dali.chenzaomai.com/Article/details/gtezdeacsf.html

`共 ${n} 条`
来源：http://dali.sweek.top/Article/details/gtupvyezvm.html

[U94] JS：箭头函数
来源：http://dali.svipenyu.cn/Article/details/gtyrasekdy.html

const double = x => x * 2;
来源：http://dali.pycfn.com/Article/details/gtxzqsttss.html

[U95] JS：Promise 包装
来源：http://dali.cqqwz.cn/Article/details/gtzxbwbdmo.html

new Promise((resolve, reject) => {})
来源：http://dali.yueranfly.top/Article/details/gtvwccjdpf.html

[U96] JS：async/await 与异常
来源：http://dali.tian-w.cn/Article/details/gtwaloufec.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gtamaaqthm.html

[U97] JS：并发请求
来源：http://dali.chenlongwang.top/Article/details/gtzgcvrlnj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gtbptjsuwu.html

[U98] JS：fetch 带 JSON
来源：http://dali.9152youxi.cn/Article/details/gtwlsqhgqm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.wangshuangyany.cn/Article/details/gtkiovezoc.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gtqhzhxzog.html

el.addEventListener("click", e => {})
来源：http://dali.xziqi.cn/Article/details/gtjfvfdisd.html

[U100] JS：DOM 查询
来源：http://dali.hammf.cn/Article/details/gtlwmkgtar.html

document.querySelector(".item")
来源：http://dali.sysykeji.top/Article/details/gtoeiwyuvt.html

[U101] JS：classList 操作
来源：http://dali.cheryme.top/Article/details/gtkswpwjdw.html

el.classList.toggle("active")
来源：http://dali.shangyingyoupin.top/Article/details/gtwliimosc.html

[U102] JS：本地存储
来源：http://dali.gzhubu.top/Article/details/gtmxcolbjg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.svipenyu.cn/Article/details/gtxafysnzk.html

[U103] JS：定时器
来源：http://dali.mhx1999.top/Article/details/gtzqfokiko.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jiagoushi.top/Article/details/gtspeccxnu.html

[U104] JS：防抖
来源：http://dali.cdnleiting.top/Article/details/gtekgzkptx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gtskkctvpn.html

[U105] JS：节流
来源：http://dali.kuanghao11.cn/Article/details/gtztqjpmyk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hongshengwenyu.top/Article/details/gtmqeyznbu.html

[U106] JS：日期格式化
来源：http://dali.xziqi.cn/Article/details/gtmdlisikd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.dianchejie.cn/Article/details/gthiowrcpp.html

[U107] JS：数字千分位
来源：http://dali.xuetiantiany.cn/Article/details/gtehvuvymi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.meibo888.top/Article/details/gtxmtgelfj.html

[U108] JS：随机整数
来源：http://dali.dianchejie.cn/Article/details/gtovrvlcxz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhoulong.xyz/Article/details/gtwpmisvbn.html

[U109] JS：数组分组
来源：http://dali.jlsjyb.cn/Article/details/gtcfmpyztl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yvedp.cn/Article/details/gtrwvmyxfz.html

[U110] JS：数组分块
来源：http://dali.yongpay.top/Article/details/gtgbfmxkpb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.snrcjt.cn/Article/details/gtytqpzzsa.html

[U111] JS：对象转 Map
来源：http://dali.zhengqikj.top/Article/details/gtdznnfgmo.html

new Map(Object.entries(obj))
来源：http://dali.zycfv.cn/Article/details/gtlsheiihx.html

[U112] JS：字符串补位
来源：http://dali.zycfv.cn/Article/details/gtdulntcoi.html

"7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gtvhqiufpw.html

[U113] JS：正则替换全部
来源：http://dali.guowangkeji.top/Article/details/gtzzgzxafx.html

s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtomgbjyvn.html

[U114] JS：JSON 深比较
来源：http://dali.pengpengdd.cyou/Article/details/gtrzpacqxc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shuidangran.top/Article/details/gtpujdyure.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gtanfttfjt.html

crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjmtutmxm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hywenlv.cn/Article/details/gtlldownem.html

/** @param {string} name */ function f(name) {}
来源：http://dali.haohaochexian.top/Article/details/gtauukoxrt.html

[U117] JS：单元测试
来源：http://dali.jyoumei.cn/Article/details/gtenkuaaao.html

npm i -D vitest;  npx vitest
来源：http://dali.wangdashe.top/Article/details/gtyjffgkvq.html

[U118] JS：开发服务器
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjeapwde.html

npm i -D vite;  npx vite
来源：http://dali.yuxming.cn/Article/details/gtrwfrbczg.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gteynqwbnc.html

npx vite build
来源：http://dali.jinghuilouyu.cn/Article/details/gtsddwpexb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmrrnrlt.html

import.meta.env.VITE_API_URL
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjvfeelx.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtbssdnajc.html

统计汇总
来源：http://dali.mhx1999.top/Article/details/gtdyymptsf.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtqhzipdob.html

按语言统计（条）：
来源：http://dali.feifeiyinyue.top/Article/details/gtvqubnsyr.html

Python ......... 252
来源：http://dali.svipenyu.cn/Article/details/gtcejhjkyi.html

PHP ............ 252
来源：http://dali.yonumen.top/Article/details/gtgfhyfsvj.html

JavaScript ..... 252
来源：http://dali.jqgfzy.top/Article/details/gttsguelcp.html

TypeScript ..... 212
来源：http://dali.jiagoushi.top/Article/details/gtkzgpjhio.html

Java ........... 212
来源：http://dali.yanxiufei.cn/Article/details/gtgmmrfvbo.html

Go ............. 212
来源：http://dali.xylfe.cn/Article/details/gtutmidivk.html

Ruby ........... 212
来源：http://dali.zhoulong.xyz/Article/details/gttgnaytsq.html

C# ............. 212
来源：http://dali.birdmap.top/Article/details/gtkwmnquvc.html

C .............. 30
来源：http://dali.havefunace.top/Article/details/gtmnhalgve.html

C++ ............ 30
来源：http://dali.jqgfzy.top/Article/details/gtophvueim.html

SQL ............ 90
来源：http://dali.xinyue.icu/Article/details/gtssomiolm.html

Bash ........... 80
来源：http://dali.aizwys.cn/Article/details/gtozjyuyel.html

Kotlin ......... 15
来源：http://dali.pycfn.com/Article/details/gttxbuzgon.html

Swift .......... 15
来源：http://dali.hnqzz.top/Article/details/gtdandrtbe.html

Lua ............ 10
来源：http://dali.gzhubu.top/Article/details/gtcfjiklex.html

Perl ........... 10
来源：http://dali.vqdsnc.cn/Article/details/gtuvjllxrx.html

Scala .......... 10
来源：http://dali.jinghuilouyu.cn/Article/details/gtxumpfplu.html

------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gtxmhfaoui.html

合计 ........... 2106 条
来源：http://dali.nanxuanxn.top/Article/details/gtfvtionaj.html

按章节统计：
来源：http://dali.ybcxt.top/Article/details/gthxswedmo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.chenzaomai.com/Article/details/gtcbycdowi.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gtrjayodpd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.snrcjt.cn/Article/details/gtmzhjwsll.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yj20258888.top/Article/details/gthnhxbyol.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.daria6918.cn/Article/details/gtmnkezzke.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.quarkkingdee.top/Article/details/gtypxtcsqu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jlsjyb.cn/Article/details/gtspuckxvu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrvmcjwy.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gtafsqalmo.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.pycfn.com/Article/details/gtfxmueexj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gtfwhccvgd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gtauquxfls.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gtrplqtnos.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.smart0.xyz/Article/details/gtkxgncabh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.haohaochexian.top/Article/details/gtfdkihzdu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gtofiddqea.html

Q SQL 专题                              90
来源：http://dali.xuetiantiany.cn/Article/details/gtvrflccuk.html

R Bash 专题                             80
来源：http://dali.cucudq.cn/Article/details/gtlufzmfss.html

S C / C++ 专题                          60
来源：http://dali.hysaishi.cn/Article/details/gtzftvwfoi.html

T 其他语言补充                          60
来源：http://dali.quarkkingdee.top/Article/details/gtkslbsxiv.html

U 高频实用片段                         120
来源：http://dali.hammf.cn/Article/details/gtlmfddstt.html

------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtibgjtqly.html

合计                                  2106 条
来源：http://dali.jyoumei.cn/Article/details/gtmqfklvyc.html

--------------------------------------------------------------------------------
来源：http://dali.ydzc1.top/Article/details/gtfgfbyygl.html

使用提醒
来源：http://dali.daria6918.cn/Article/details/gtealtpvlh.html

--------------------------------------------------------------------------------
来源：http://dali.gaohongyu789.top/Article/details/gtuzslvrjm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.birdmap.top/Article/details/gtlssdhfgo.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yj202588.top/Article/details/gtzvfpnnut.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zdqjudy.top/Article/details/gturubytsy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.tian-w.cn/Article/details/gtylginxih.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cashguo.top/Article/details/gtfhgcifqj.html

—— 文件结束 ——
来源：http://dali.guowangkeji.top/Article/details/gtpjyihswp.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtakvypzvx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.haohaochexian.top/Article/details/gtcmlrassj.html

Common Programming Examples Cheat Book
来源：http://dali.tanke756.top/Article/details/gtsfkknhtr.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gttoppiuyn.html

【收录内容】
来源：http://dali.zycfv.cn/Article/details/gtnupzhlqr.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhongyouzk.top/Article/details/gtrucmpgir.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.aizwys.cn/Article/details/gtcjnwthwx.html

SQL · Bash · C · C++
来源：http://dali.chenlongwang.top/Article/details/gtrszqeqwm.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yj20258888.top/Article/details/gtkevpufza.html

【使用说明】
来源：http://dali.jinqigufen.top/Article/details/gtaechqsgw.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yj202588.top/Article/details/gtrlxurqrk.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.sxryk.cn/Article/details/gtepzlzukg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.nanxinkj.top/Article/details/gtgyypttlj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.wangshuangyany.cn/Article/details/gtuvxvqsnq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.havefunace.top/Article/details/gtgzksfdjf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenlongwang.top/Article/details/gtpdenkdpr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cdnleiting.top/Article/details/gthslqntgn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.meibo888.top/Article/details/gtetsstwqi.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhengqikj.top/Article/details/gturtwechh.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.dianchejie.cn/Article/details/gttiwaihff.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.316326.xyz/Article/details/gtruuomivz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.dashuyun.cn/Article/details/gtsfbhkdvh.html

【文件统计】
来源：http://dali.zhongyouzk.top/Article/details/gtqgfdyhos.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.fzhhl.top/Article/details/gthftmjgkv.html

--------------------------------------------------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gtlyhoxcdr.html

目  录
来源：http://dali.zhixingplan.top/Article/details/gtucchgziv.html

--------------------------------------------------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gtkxricoxk.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.sysykeji.top/Article/details/gtxqytckzj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ydzc1.top/Article/details/gtxpefgwsj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhengqikj.top/Article/details/gtabzxlprt.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ehwqpu.com/Article/details/gtupfiwmqo.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.0kj1m.cn/Article/details/gtwrpqgwtk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hnxiangtu.top/Article/details/gtxiorksbl.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ydzc1.top/Article/details/gtkwhzfgub.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yanxiufei.cn/Article/details/gtgnqmufcj.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ybcxt.top/Article/details/gtwdmtmcpr.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zycfv.cn/Article/details/gtyfbpyobb.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuujhuzro.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtkpifbfmg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yuxming.cn/Article/details/gtnzxcdnzo.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.tanke756.top/Article/details/gtpblzyzho.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.fzhhl.top/Article/details/gtyeqdjqwq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.quarkkingdee.top/Article/details/gtoayrhsjb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yuanzhike.top/Article/details/gtcfqfhnwl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jqgfzy.top/Article/details/gtontiafux.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.dianchejie.cn/Article/details/gtpawpzmks.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shangyingyoupin.top/Article/details/gtqeecfkxm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnxiangtu.top/Article/details/gtidjbbrhn.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtmkiuokzk.html

A. 基础语法与类型
来源：http://dali.yanxiufei.cn/Article/details/gtgsjxfzzo.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtxbbbieng.html

[A01] Hello World
来源：http://dali.hywenlv.cn/Article/details/gtyzlndumg.html

Py:   print("Hello, World!")
来源：http://dali.shuidangran.top/Article/details/gtpethtxba.html

PHP:  echo "Hello, World!";
来源：http://dali.daria6918.cn/Article/details/gttnamlswc.html

JS:   console.log("Hello, World!");
来源：http://dali.nanxinkj.top/Article/details/gtzegklivw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hnxiangtu.top/Article/details/gtlrdpvvws.html

Java: System.out.println("Hello, World!");
来源：http://dali.wangshuangyany.cn/Article/details/gtavcmjfav.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hfpthk.cn/Article/details/gtdjfcoihm.html

Ruby: puts "Hello, World!"
来源：http://dali.mhx1999.top/Article/details/gtibxkhjjo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hammf.cn/Article/details/gtrehaizxd.html

[A02] 变量声明与赋值
来源：http://dali.gaohongyu789.top/Article/details/gtdpnwcoss.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhoulong.xyz/Article/details/gtkttuvklz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbzvlkqaj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zycfv.cn/Article/details/gtyuapvlev.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.havefunace.top/Article/details/gtcgvzbybv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ybcxt.top/Article/details/gtroohcdih.html

Go:   name := "Alex"; age := 20
来源：http://dali.hnxiangtu.top/Article/details/gtevccrnyq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.wangshuangyany.cn/Article/details/gthqigohvl.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.cqqwz.cn/Article/details/gtjvaojkna.html

[A03] 常量定义
来源：http://dali.0kj1m.cn/Article/details/gtiryfxdwe.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cqqwz.cn/Article/details/gtgqxbpzah.html

PHP:  const PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gtpejaohga.html

JS:   const PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtveqifaec.html

TS:   const PI: number = 3.14159;
来源：http://dali.cashguo.top/Article/details/gtgseeaoao.html

Java: static final double PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtmqvqejve.html

Go:   const PI = 3.14159
来源：http://dali.jianghu66.top/Article/details/gtinywxsit.html

Ruby: PI = 3.14159
来源：http://dali.guowangkeji.top/Article/details/gtvareeyqu.html

C#:   const double PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtkqxstrkx.html

[A04] 判断变量类型
来源：http://dali.9152youxi.cn/Article/details/gtmwvkcrne.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.birdmap.top/Article/details/gtlhdlilmv.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yangfankeji.com/Article/details/gttenwscqj.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.tian-w.cn/Article/details/gthwarafzv.html

TS:   typeof x; x instanceof Date
来源：http://dali.hongshengwenyu.top/Article/details/gtuvgmgzvo.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hysaishi.cn/Article/details/gtrbavufgc.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.sysykeji.top/Article/details/gtyetrdmeh.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.haohaochexian.top/Article/details/gtxxjfhxcx.html

C#:   x.GetType().Name; x is int
来源：http://dali.chenjidiqi.icu/Article/details/gtzzrnemax.html

[A05] 整数除法与取模
来源：http://dali.jiagoushi.top/Article/details/gttpicyakk.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.bjfxy.top/Article/details/gtyxkuycng.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gtxtgdplvv.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gtqomahgqw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gtrdwnudlt.html

Java: 7 / 2; 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtzmzxjksi.html

Go:   7 / 2; 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtdvhipvfa.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gtmtuxsmhj.html

C#:   7 / 2; 7 % 2
来源：http://dali.wangshuangyany.cn/Article/details/gtudchqiis.html

[A06] 字符串转数字
来源：http://dali.jyoumei.cn/Article/details/gttioyueyv.html

Py:   int("42"); float("3.14")
来源：http://dali.cashguo.top/Article/details/gtgagqwcpi.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jiagoushi.top/Article/details/gtpecgujpx.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.sysykeji.top/Article/details/gtiyrvatlk.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.shuidangran.top/Article/details/gtvpllntpp.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.guowangkeji.top/Article/details/gtekwmkzjg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zdqjudy.top/Article/details/gtqktlmnha.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hfpthk.cn/Article/details/gtaphrvpqd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hysaishi.cn/Article/details/gtjxsebjxi.html

[A07] 数字转字符串
来源：http://dali.xziqi.cn/Article/details/gtigfmahyd.html

Py:   str(42)
来源：http://dali.xylfe.cn/Article/details/gtmpwlvwfc.html

PHP:  (string) 42; strval(42)
来源：http://dali.guannengcc.top/Article/details/gttjafhiwm.html

JS:   String(42); (42).toString()
来源：http://dali.hnqzz.top/Article/details/gtjnipmwyt.html

TS:   String(42)
来源：http://dali.smart0.xyz/Article/details/gtowdoipqk.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ybcxt.top/Article/details/gtpzsjihyj.html

Go:   strconv.Itoa(42)
来源：http://dali.gzhubu.top/Article/details/gtqobjckev.html

Ruby: 42.to_s
来源：http://dali.guowangkeji.top/Article/details/gtuvjvbcux.html

C#:   42.ToString()
来源：http://dali.bjfxy.top/Article/details/gtlnigkfxf.html

[A08] 取整与四舍五入
来源：http://dali.tanke756.top/Article/details/gtnhvxrplv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhengqikj.top/Article/details/gtrdfdvdkq.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ehwqpu.com/Article/details/gtgtaziikp.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.guannengcc.top/Article/details/gtrygqpbec.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.xuanzx.com/Article/details/gtesbnicru.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.aizwys.cn/Article/details/gtkvgvqiou.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.hongshengwenyu.top/Article/details/gttyxvtdde.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zycfv.cn/Article/details/gtziwzovzg.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.haohaochexian.top/Article/details/gtnktdbkby.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gtbonhwviy.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.mhx1999.top/Article/details/gthctbovza.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gtfmlpbsal.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtuefvnrgq.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gttttwujnp.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gthnlhrkyp.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hysaishi.cn/Article/details/gtwrjyfimo.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.nanxinkj.top/Article/details/gtxcchcpyq.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gtyhjkbvrg.html

[A10] 生成随机数
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxzvjolc.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yj20258888.top/Article/details/gtxenprieu.html

PHP:  random_int(1, 100);
来源：http://dali.snrcjt.cn/Article/details/gtqgxccubh.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.redwolf501.top/Article/details/gtltlgxgek.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.nanxinkj.top/Article/details/gtxwizingh.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgrzgehdd.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.chenzaomai.com/Article/details/gtvwrsscjn.html

Ruby: rand(1..100)
来源：http://dali.sxryk.cn/Article/details/gtngtpmrud.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gtdixxsoap.html

[A11] 条件表达式（三元）
来源：http://dali.hfpthk.cn/Article/details/gtofvybpxr.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.snrcjt.cn/Article/details/gtcsjhvkan.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gtqtyenpae.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.nanxinkj.top/Article/details/gtbzxntrrm.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jiagoushi.top/Article/details/gtiaxxpkwr.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yonumen.top/Article/details/gtieijludr.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.tianlin.xyz/Article/details/gtnboemmvl.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.cucudq.cn/Article/details/gtkjhmvrjj.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gtrmtrmfjo.html

[A12] 字符串插值 / 格式化
来源：http://dali.yuxming.cn/Article/details/gtansffvgx.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.gotoacloud.top/Article/details/gtejvdggmq.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zdqjudy.top/Article/details/gtzmzxsuta.html

JS:   `Hello, ${name}!`
来源：http://dali.yanxiufei.cn/Article/details/gtqrgvqkvd.html

TS:   `Hello, ${name}!`
来源：http://dali.chenjidiqi.icu/Article/details/gtinwhwwxp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.smart0.xyz/Article/details/gtlvypztst.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.shzxlz.cn/Article/details/gtymopmqeg.html

Ruby: "Hello, #{name}!"
来源：http://dali.sysykeji.top/Article/details/gtlzyfyvui.html

C#:   $"Hello, {name}!"
来源：http://dali.haohaochexian.top/Article/details/gtdbxvphsm.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.sysykeji.top/Article/details/gtkjjwbgth.html

Py:   "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gtylmqgkhj.html

PHP:  "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gtdoqjgujc.html

JS:   "第一行\n第二行"
来源：http://dali.cashguo.top/Article/details/gtuqlkpvtg.html

TS:   "第一行\n第二行"
来源：http://dali.ehwqpu.com/Article/details/gtathanmtb.html

Java: "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gtyxjuzuhg.html

Go:   "第一行\n第二行"
来源：http://dali.xziqi.cn/Article/details/gtrrfwgbbh.html

Ruby: "第一行\n第二行"
来源：http://dali.yangfankeji.com/Article/details/gtftpxtuyl.html

C#:   "第一行\n第二行"
来源：http://dali.sxryk.cn/Article/details/gtqjrkbeiz.html

[A14] 注释写法
来源：http://dali.fzhhl.top/Article/details/gtlngnsvqt.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jiagoushi.top/Article/details/gtxijkuqpz.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.shzxlz.cn/Article/details/gtahodicpi.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvxlhcehl.html

TS:   // 单行；/* 多行 */
来源：http://dali.yongpay.top/Article/details/gtpekcnela.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jiagoushi.top/Article/details/gtpdvyqzqi.html

Go:   // 单行；/* 多行 */
来源：http://dali.kuanghao11.cn/Article/details/gtxfyekybm.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.xuanzx.com/Article/details/gtyeczgicv.html


<!-- 参考信息 -->