代发 wailian999

[U87] JS：解构默认值
来源：http://dali.andypj.xyz/Article/details/gtyzotymfe.html

const { a = 1, b = 2 } = obj;
来源：http://dali.iojbl.cn/Article/details/gtexnyawxt.html

[U88] JS：对象展开合并
来源：http://dali.pycfn.com/Article/details/gtyqjotqul.html

{ ...a, ...b }
来源：http://dali.yj20258.top/Article/details/gtutohsbmi.html

[U89] JS：数组去重
来源：http://dali.zhengqikj.top/Article/details/gtnwviktmv.html

[...new Set(arr)]
来源：http://dali.shuidangran.top/Article/details/gtvhmqhbhb.html

[U90] JS：数字数组排序
来源：http://dali.hysaishi.cn/Article/details/gtymiyawwj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gtkxyjymib.html

[U91] JS：对象键值遍历
来源：http://dali.birdmap.top/Article/details/gtovilcmet.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yongpay.top/Article/details/gtxwanqczu.html

[U92] JS：深拷贝
来源：http://dali.zhixingplan.top/Article/details/gtpsgznqkp.html

structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gteunrfmhn.html

[U93] JS：模板字符串
来源：http://dali.yangfankeji.com/Article/details/gtrdgktwdk.html

`共 ${n} 条`
来源：http://dali.quarkkingdee.top/Article/details/gtbaubiswo.html

[U94] JS：箭头函数
来源：http://dali.pengpengdd.cyou/Article/details/gtavihadkb.html

const double = x => x * 2;
来源：http://dali.gotoacloud.top/Article/details/gtvkgarrga.html

[U95] JS：Promise 包装
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjbupexc.html

new Promise((resolve, reject) => {})
来源：http://dali.ppjwa.cn/Article/details/gtslimfwwd.html

[U96] JS：async/await 与异常
来源：http://dali.quarkkingdee.top/Article/details/gtfrxxfdph.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtorzuiplj.html

[U97] JS：并发请求
来源：http://dali.sufxvd.cn/Article/details/gtpfzhkrgy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gtslbvcvcz.html

[U98] JS：fetch 带 JSON
来源：http://dali.iojbl.cn/Article/details/gtgpzpwhim.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.meibo888.top/Article/details/gtzanfwqsw.html

[U99] JS：事件监听
来源：http://dali.jqgufenzy.top/Article/details/gtjqucocxh.html

el.addEventListener("click", e => {})
来源：http://dali.birdmap.top/Article/details/gtnmrvpnbb.html

[U100] JS：DOM 查询
来源：http://dali.dashuyun.cn/Article/details/gtcicdjido.html

document.querySelector(".item")
来源：http://dali.yuanzhike.top/Article/details/gttogisstj.html

[U101] JS：classList 操作
来源：http://dali.gzhubu.top/Article/details/gtltceuupj.html

el.classList.toggle("active")
来源：http://dali.jlsjyb.cn/Article/details/gtykvrszue.html

[U102] JS：本地存储
来源：http://dali.hnxiangtu.top/Article/details/gtvlhlztad.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.mhx1999.top/Article/details/gtwpqpjbov.html

[U103] JS：定时器
来源：http://dali.shzxlz.cn/Article/details/gtuklfdlbv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cashguo.top/Article/details/gtotqtused.html

[U104] JS：防抖
来源：http://dali.pengpengdd.cyou/Article/details/gtoehlsmek.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gtrczphnxp.html

[U105] JS：节流
来源：http://dali.jinqigufen.top/Article/details/gttakfwapd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.fengsongda.top/Article/details/gtqceqjwiz.html

[U106] JS：日期格式化
来源：http://dali.chenzaomai.com/Article/details/gtqvowcqqd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.chenzaomai.com/Article/details/gtlzpdfuvm.html

[U107] JS：数字千分位
来源：http://dali.daxiang520.top/Article/details/gtqkxzrbcp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.nanxinkj.top/Article/details/gtjvgnsesm.html

[U108] JS：随机整数
来源：http://dali.yangfankeji.com/Article/details/gtpmtnwptr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shzxlz.cn/Article/details/gtydounbsg.html

[U109] JS：数组分组
来源：http://dali.0kj1m.cn/Article/details/gtgdnvlgys.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hongshengwenyu.top/Article/details/gtltbugmzh.html

[U110] JS：数组分块
来源：http://dali.jinqigfzy.top/Article/details/gtbydhtogz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jyoumei.cn/Article/details/gtommprrmr.html

[U111] JS：对象转 Map
来源：http://dali.mhx1999.top/Article/details/gtovpvdzgp.html

new Map(Object.entries(obj))
来源：http://dali.xziqi.cn/Article/details/gtoeranyfx.html

[U112] JS：字符串补位
来源：http://dali.gotoacloud.top/Article/details/gtgxwvrtiu.html

"7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtshleikmd.html

[U113] JS：正则替换全部
来源：http://dali.9152youxi.cn/Article/details/gtvegttmqm.html

s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gtgvmxtqot.html

[U114] JS：JSON 深比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtipbbpnqp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.c1oappe.top/Article/details/gtmpyrxtha.html

[U115] JS：生成 UUID
来源：http://dali.hnxiangtu.top/Article/details/gtjuczqfxd.html

crypto.randomUUID()
来源：http://dali.0kj1m.cn/Article/details/gthrhlkygk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbuobcst.html

/** @param {string} name */ function f(name) {}
来源：http://dali.pycfn.com/Article/details/gtngexphrr.html

[U117] JS：单元测试
来源：http://dali.hammf.cn/Article/details/gtsoyuqiut.html

npm i -D vitest;  npx vitest
来源：http://dali.ybcxt.top/Article/details/gtcnwzqgox.html

[U118] JS：开发服务器
来源：http://dali.xylfe.cn/Article/details/gtkogvtzyg.html

npm i -D vite;  npx vite
来源：http://dali.iojbl.cn/Article/details/gtwwiaqvkb.html

[U119] JS：生产构建
来源：http://dali.yuanzhike.top/Article/details/gtjsjrhxrq.html

npx vite build
来源：http://dali.xziqi.cn/Article/details/gtzqmpvbrh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xziqi.cn/Article/details/gtvviuatgb.html

import.meta.env.VITE_API_URL
来源：http://dali.yj20258.top/Article/details/gtkxeejmyd.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtpqussigy.html

统计汇总
来源：http://dali.aizwys.cn/Article/details/gtkttavcpr.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtpzulvgmp.html

按语言统计（条）：
来源：http://dali.gogol.net.cn/Article/details/gtyodidsnk.html

Python ......... 252
来源：http://dali.iojbl.cn/Article/details/gtuwtqbppa.html

PHP ............ 252
来源：http://dali.yangfankeji.com/Article/details/gtcnzabhfk.html

JavaScript ..... 252
来源：http://dali.nanxinkj.top/Article/details/gtppwofdwu.html

TypeScript ..... 212
来源：http://dali.cqqwz.cn/Article/details/gtkitwyiwj.html

Java ........... 212
来源：http://dali.xziqi.cn/Article/details/gtqagizsyj.html

Go ............. 212
来源：http://dali.snrcjt.cn/Article/details/gtiuuiququ.html

Ruby ........... 212
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwunrnit.html

C# ............. 212
来源：http://dali.yongpay.top/Article/details/gtkyrjbcvd.html

C .............. 30
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgvtrvkw.html

C++ ............ 30
来源：http://dali.tanke756.top/Article/details/gtabogfgjq.html

SQL ............ 90
来源：http://dali.zhengqikj.top/Article/details/gtlkqytjwv.html

Bash ........... 80
来源：http://dali.yj20258888.top/Article/details/gtzblkhcbq.html

Kotlin ......... 15
来源：http://dali.cdnleiting.top/Article/details/gtopwqeklf.html

Swift .......... 15
来源：http://dali.hysaishi.cn/Article/details/gttejkmirx.html

Lua ............ 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhllsciw.html

Perl ........... 10
来源：http://dali.jiagoushi.top/Article/details/gtppflgyaf.html

Scala .......... 10
来源：http://dali.gotoacloud.top/Article/details/gtdhrcvbhc.html

------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gtpofemmlx.html

合计 ........... 2106 条
来源：http://dali.316326.xyz/Article/details/gtvsksxbhs.html

按章节统计：
来源：http://dali.sysykeji.top/Article/details/gtvuybqljy.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ivvv.top/Article/details/gtejgdqqmy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cqqwz.cn/Article/details/gtnkimjpbd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jqgufenzy.top/Article/details/gtehiikhwi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hongshengwenyu.top/Article/details/gtqdhfighj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjthhanm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhoulong.xyz/Article/details/gtzxkbmihn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.aizwys.cn/Article/details/gtythrbdwn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.tian-w.cn/Article/details/gtviitfkew.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gtuucfjvvj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.nanxuanxn.top/Article/details/gtwcmvrmqd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gtpbisvgkg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gtieuzgcix.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gtyejqqpvx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.daria6918.cn/Article/details/gtbrlwcnji.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhixingplan.top/Article/details/gtpgmvkvio.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gtbetlomsg.html

Q SQL 专题                              90
来源：http://dali.guowangkeji.top/Article/details/gtczthhbgz.html

R Bash 专题                             80
来源：http://dali.tian-w.cn/Article/details/gtmqvanilv.html

S C / C++ 专题                          60
来源：http://dali.jinqigfzy.top/Article/details/gtkftolife.html

T 其他语言补充                          60
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzgtsbcw.html

U 高频实用片段                         120
来源：http://dali.yongpay.top/Article/details/gtisrtsevl.html

------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gtsxxpueic.html

合计                                  2106 条
来源：http://dali.guowangkeji.top/Article/details/gtjgiwtrzf.html

--------------------------------------------------------------------------------
来源：http://dali.yuxming.cn/Article/details/gtepaygvgn.html

使用提醒
来源：http://dali.shangyingyoupin.top/Article/details/gtkhdxzdwq.html

--------------------------------------------------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gtjkwfedft.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.meibo888.top/Article/details/gtzqubchst.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.chenlongwang.top/Article/details/gtegjpxcta.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yvedp.cn/Article/details/gtjznukmum.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.0kj1m.cn/Article/details/gtlnkzvasd.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jinqigufen.top/Article/details/gtrjhmsqde.html

—— 文件结束 ——
来源：http://dali.xuanzx.com/Article/details/gtepoqsmud.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtoxdpayaj.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xinyue.icu/Article/details/gtqxtuctbc.html

Common Programming Examples Cheat Book
来源：http://dali.cdnleiting.top/Article/details/gtaruvfrzz.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtsauwqiio.html

【收录内容】
来源：http://dali.smart0.xyz/Article/details/gtcmzzwvmq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.gaohongyu789.top/Article/details/gtngijjmwx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhoulong.xyz/Article/details/gtntbsdqpp.html

SQL · Bash · C · C++
来源：http://dali.jqgufenzy.top/Article/details/gteyswehni.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hongshengwenyu.top/Article/details/gtxtpooanu.html

【使用说明】
来源：http://dali.hysaishi.cn/Article/details/gtayfqltod.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjthzndv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yj20258.top/Article/details/gthwqglvtu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.cucudq.cn/Article/details/gtkqchilvb.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yanxiufei.cn/Article/details/gtokbvrnfy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsowtovih.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xylfe.cn/Article/details/gteqqsybgt.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.sysykeji.top/Article/details/gtbecbzvkh.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hammf.cn/Article/details/gtysfembpx.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xylfe.cn/Article/details/gtmnwpdspc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jiagoushi.top/Article/details/gtwcdbesnm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.feifeiyinyue.top/Article/details/gtpzmxhsie.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zycfv.cn/Article/details/gthyxcdnow.html

【文件统计】
来源：http://dali.0kj1m.cn/Article/details/gtkvlvppwi.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xylfe.cn/Article/details/gtqrlefvxe.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gtldwojirr.html

目  录
来源：http://dali.ivvv.top/Article/details/gtvicicpgh.html

--------------------------------------------------------------------------------
来源：http://dali.ybcxt.top/Article/details/gtjanfqtsc.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cdnleiting.top/Article/details/gtdfywzeir.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yj20258.top/Article/details/gtccekbybq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hnxiangtu.top/Article/details/gtrgvdtddb.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhixingplan.top/Article/details/gtshvtvked.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.tanke756.top/Article/details/gtednilmsi.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.vqdsnc.cn/Article/details/gtbkkopbtf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xziqi.cn/Article/details/gtvwejlapo.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xylfe.cn/Article/details/gtknasdgmx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gtvbgfiwvh.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shuidangran.top/Article/details/gtekoakziu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.nwbrower.top/Article/details/gtjrdwbivj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yj20258.top/Article/details/gtljoqnxhx.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gtddtgfzlc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqtghskh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.dianchejie.cn/Article/details/gtjuuwojgw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.aizwys.cn/Article/details/gtlylssjac.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cheryme.top/Article/details/gtrwkepdev.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ybcxt.top/Article/details/gtmqkxtbjr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.dianchejie.cn/Article/details/gtwdfhzxzz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigfzy.top/Article/details/gtodzoredh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jyoumei.cn/Article/details/gtmsyvzumx.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtddwrksgu.html

A. 基础语法与类型
来源：http://dali.dashuyun.cn/Article/details/gthdzwoywu.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtqvkodwyf.html

[A01] Hello World
来源：http://dali.hnqzz.top/Article/details/gtawocwtlk.html

Py:   print("Hello, World!")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuleixggs.html

PHP:  echo "Hello, World!";
来源：http://dali.fengsongda.top/Article/details/gtksmesqgm.html

JS:   console.log("Hello, World!");
来源：http://dali.hammf.cn/Article/details/gtswzurmeo.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.mhx1999.top/Article/details/gtxofdhije.html

Java: System.out.println("Hello, World!");
来源：http://dali.hammf.cn/Article/details/gtlpzipbba.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.vqdsnc.cn/Article/details/gttgralczv.html

Ruby: puts "Hello, World!"
来源：http://dali.cdnleiting.top/Article/details/gtnrknmyxl.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.c1oappe.top/Article/details/gtjtacofym.html

[A02] 变量声明与赋值
来源：http://dali.xuetiantiany.cn/Article/details/gtjdyjapvt.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jqgufenzy.top/Article/details/gtxtdalzwo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhengqikj.top/Article/details/gthekrpoaw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.c1oappe.top/Article/details/gthnwdryqc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gtsmsoylmc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.daria6918.cn/Article/details/gtynkuomne.html

Go:   name := "Alex"; age := 20
来源：http://dali.sxryk.cn/Article/details/gtlqzqirto.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hywenlv.cn/Article/details/gtzgtafpwl.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.dianchejie.cn/Article/details/gtmklidlcq.html

[A03] 常量定义
来源：http://dali.yonumen.top/Article/details/gtjrlyledg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhoulong.xyz/Article/details/gtlkepbngc.html

PHP:  const PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gtkuwrgnbs.html

JS:   const PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtrycaawyf.html

TS:   const PI: number = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gthgldthcf.html

Java: static final double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtulkmbgid.html

Go:   const PI = 3.14159
来源：http://dali.mhx1999.top/Article/details/gtmambzeoe.html

Ruby: PI = 3.14159
来源：http://dali.fengsongda.top/Article/details/gtvposhqri.html

C#:   const double PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gthnccifgz.html

[A04] 判断变量类型
来源：http://dali.ivvv.top/Article/details/gtroukgzmu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ehwqpu.com/Article/details/gtqyullufk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yanxiufei.cn/Article/details/gtaygubosv.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.sufxvd.cn/Article/details/gtftmcwsff.html

TS:   typeof x; x instanceof Date
来源：http://dali.xziqi.cn/Article/details/gtecyuytqf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.nwbrower.top/Article/details/gtgxwkpecp.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jqgufenzy.top/Article/details/gttmjpbytt.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.andypj.xyz/Article/details/gthpeylwnw.html

C#:   x.GetType().Name; x is int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdqywzat.html

[A05] 整数除法与取模
来源：http://dali.sysykeji.top/Article/details/gtubwfstlk.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.gzhubu.top/Article/details/gtwwdfqwka.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgcceumyn.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtcprnniuu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cashguo.top/Article/details/gtizasmdqw.html

Java: 7 / 2; 7 % 2
来源：http://dali.sweek.top/Article/details/gtgufskylm.html

Go:   7 / 2; 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gthiyrzfgv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gtztgymktb.html

C#:   7 / 2; 7 % 2
来源：http://dali.316326.xyz/Article/details/gtnnetbdut.html

[A06] 字符串转数字
来源：http://dali.9152youxi.cn/Article/details/gtcievuzyl.html

Py:   int("42"); float("3.14")
来源：http://dali.guowangkeji.top/Article/details/gtauqaeuta.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.chenzaomai.com/Article/details/gtsvybwxzl.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.xuanzx.com/Article/details/gtyboqtaau.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.havefunace.top/Article/details/gtzjigbepi.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.shuidangran.top/Article/details/gtxbgpneva.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.feifeiyinyue.top/Article/details/gtynvmnham.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.bjfxy.top/Article/details/gtxwrdkmzd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.sxryk.cn/Article/details/gtdzmunhnt.html

[A07] 数字转字符串
来源：http://dali.zycfv.cn/Article/details/gtdavlbqnh.html

Py:   str(42)
来源：http://dali.tanke756.top/Article/details/gtchbzkeqh.html

PHP:  (string) 42; strval(42)
来源：http://dali.gotoacloud.top/Article/details/gtleeykozi.html

JS:   String(42); (42).toString()
来源：http://dali.c1oappe.top/Article/details/gtuhthfyid.html

TS:   String(42)
来源：http://dali.tanke756.top/Article/details/gtvbuhrxwm.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.guannengcc.top/Article/details/gtffwtqsfm.html

Go:   strconv.Itoa(42)
来源：http://dali.ivvv.top/Article/details/gtrgpzjtrh.html

Ruby: 42.to_s
来源：http://dali.316326.xyz/Article/details/gtbrzfkhjc.html

C#:   42.ToString()
来源：http://dali.ehwqpu.com/Article/details/gttlvfowkp.html

[A08] 取整与四舍五入
来源：http://dali.mhx1999.top/Article/details/gtwvdrrqzi.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gtnldyiuie.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.cashguo.top/Article/details/gtoxkaxjzt.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.meibo888.top/Article/details/gtejtcpcqk.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hfpthk.cn/Article/details/gtuyjncshb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hysaishi.cn/Article/details/gtnswpbjmo.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gtuhskejhy.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.xziqi.cn/Article/details/gtdbcoxzof.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.9152youxi.cn/Article/details/gtqkrcemww.html

[A09] 绝对值与最大最小值
来源：http://dali.jinqigfzy.top/Article/details/gtdwirjetm.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xuanzx.com/Article/details/gtwnlqhskr.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gtuwjsujpd.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.guannengcc.top/Article/details/gtiwxzdhjt.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zycfv.cn/Article/details/gtsjrdudld.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbcxzfnn.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hnqzz.top/Article/details/gtwadejgnt.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.shangyingyoupin.top/Article/details/gtevshobpi.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.ydzc1.top/Article/details/gtoehmevfw.html

[A10] 生成随机数
来源：http://dali.andypj.xyz/Article/details/gtjhzwpnxq.html

Py:   import random; random.randint(1, 100)
来源：http://dali.ppjwa.cn/Article/details/gtknixiisg.html

PHP:  random_int(1, 100);
来源：http://dali.svipenyu.cn/Article/details/gtoztpapmp.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yanxiufei.cn/Article/details/gtkyefgahz.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.tian-w.cn/Article/details/gtbrtsmzgq.html

Java: new Random().nextInt(100) + 1
来源：http://dali.tianlin.xyz/Article/details/gtyoswlten.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yj202588.top/Article/details/gtlotipqev.html

Ruby: rand(1..100)
来源：http://dali.guannengcc.top/Article/details/gtfxfccgiz.html

C#:   new Random().Next(1, 101)
来源：http://dali.c1oappe.top/Article/details/gtkmcfzlgw.html

[A11] 条件表达式（三元）
来源：http://dali.wangdashe.top/Article/details/gtubgmabzt.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvfajxyt.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yongpay.top/Article/details/gtyvyrcvtx.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.sufxvd.cn/Article/details/gtrelslcec.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.tanke756.top/Article/details/gtszsxkqgs.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.daxiang520.top/Article/details/gtwiyxwxhw.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.xylfe.cn/Article/details/gtjxnfaggl.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.daria6918.cn/Article/details/gtlwkrqxpl.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.iojbl.cn/Article/details/gtwyxasunl.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtrrpzwpyx.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.gogol.net.cn/Article/details/gtlnsxmxtx.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.cqqwz.cn/Article/details/gtrdihtfhq.html

JS:   `Hello, ${name}!`
来源：http://dali.tanke756.top/Article/details/gtvprwrkim.html

TS:   `Hello, ${name}!`
来源：http://dali.hammf.cn/Article/details/gtszzkvydk.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbwakcas.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.guowangkeji.top/Article/details/gtsppdukkt.html

Ruby: "Hello, #{name}!"
来源：http://dali.guannengcc.top/Article/details/gtqcjixtzm.html

C#:   $"Hello, {name}!"
来源：http://dali.yueranfly.top/Article/details/gtalltfnvy.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zycfv.cn/Article/details/gtzzvtmxlh.html

Py:   "第一行\n第二行"
来源：http://dali.jqgufenzy.top/Article/details/gtucamvtut.html

PHP:  "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gtpweewxhi.html

JS:   "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gtooowogxu.html

TS:   "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gtyrvlohmw.html

Java: "第一行\n第二行"
来源：http://dali.sufxvd.cn/Article/details/gtvrzgwhtv.html

Go:   "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gtdlbttlcw.html

Ruby: "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gtncwxvwcc.html

C#:   "第一行\n第二行"
来源：http://dali.iojbl.cn/Article/details/gtxpjjjnio.html

[A14] 注释写法
来源：http://dali.xinyue.icu/Article/details/gtcbxincvc.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.ivvv.top/Article/details/gtpptpnlkr.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yangfankeji.com/Article/details/gtwwuyqgxd.html

JS:   // 单行；/* 多行 */
来源：http://dali.xziqi.cn/Article/details/gtuotwxedi.html

TS:   // 单行；/* 多行 */
来源：http://dali.meibo888.top/Article/details/gtcfsavbms.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.nanxuanxn.top/Article/details/gtfuifujuh.html

Go:   // 单行；/* 多行 */
来源：http://dali.sweek.top/Article/details/gteqvljzrs.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.sysykeji.top/Article/details/gtldukueoq.html


<!-- 参考信息 -->