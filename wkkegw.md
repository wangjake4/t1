代发 wailian999

[U89] JS：数组去重
来源：http://dali.316326.xyz/Article/details/gt2wdomedgc.html

[...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gt2vjygzujn.html

[U90] JS：数字数组排序
来源：http://dali.zhengqikj.top/Article/details/gt2qcxgzotr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gt2hrflfdpq.html

[U91] JS：对象键值遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2rcqglebg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ydzc1.top/Article/details/gt2mlaqhbdz.html

[U92] JS：深拷贝
来源：http://dali.yongpay.top/Article/details/gt2jhqcznaa.html

structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gt2xoxquxfq.html

[U93] JS：模板字符串
来源：http://dali.pycfn.com/Article/details/gt2fllndsyw.html

`共 ${n} 条`
来源：http://dali.dianchejie.cn/Article/details/gt2dgaxafet.html

[U94] JS：箭头函数
来源：http://dali.birdmap.top/Article/details/gt2mmzhdkzo.html

const double = x => x * 2;
来源：http://dali.yueranfly.top/Article/details/gt2ddrkqmyy.html

[U95] JS：Promise 包装
来源：http://dali.ppjwa.cn/Article/details/gt2krvhskgr.html

new Promise((resolve, reject) => {})
来源：http://dali.mhx1999.top/Article/details/gt2rcajkdfu.html

[U96] JS：async/await 与异常
来源：http://dali.bjfxy.top/Article/details/gt2rwoodkbu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gt2zsnwrpul.html

[U97] JS：并发请求
来源：http://dali.iojbl.cn/Article/details/gt2bjqawcsg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gt2kdducvqi.html

[U98] JS：fetch 带 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gt2tzifzfug.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhixingplan.top/Article/details/gt2bnscwuna.html

[U99] JS：事件监听
来源：http://dali.meibo888.top/Article/details/gt2bbqljsyj.html

el.addEventListener("click", e => {})
来源：http://dali.zycfv.cn/Article/details/gt2znebvzzm.html

[U100] JS：DOM 查询
来源：http://dali.ivvv.top/Article/details/gt2cqplgzax.html

document.querySelector(".item")
来源：http://dali.jlsjyb.cn/Article/details/gt2noqenhvl.html

[U101] JS：classList 操作
来源：http://dali.fzhhl.top/Article/details/gt2diqehkur.html

el.classList.toggle("active")
来源：http://dali.cqqwz.cn/Article/details/gt2tjblramf.html

[U102] JS：本地存储
来源：http://dali.sxryk.cn/Article/details/gt2janyomky.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.c1oappe.top/Article/details/gt2ffsarwoj.html

[U103] JS：定时器
来源：http://dali.pengpengdd.cyou/Article/details/gt2rfmvfhfu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.mhx1999.top/Article/details/gt2obobcsyl.html

[U104] JS：防抖
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ebyongkk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gt2eawkugag.html

[U105] JS：节流
来源：http://dali.cdnleiting.top/Article/details/gt2fphagfqm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cdnleiting.top/Article/details/gt2njkwenvb.html

[U106] JS：日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gt2kezfrqix.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.chenzaomai.com/Article/details/gt2boatbcfd.html

[U107] JS：数字千分位
来源：http://dali.ybcxt.top/Article/details/gt2qhcxikoo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xuanzx.com/Article/details/gt2ocharbnw.html

[U108] JS：随机整数
来源：http://dali.chenzaomai.com/Article/details/gt2xpifqdmo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cdnleiting.top/Article/details/gt2zevgxbfa.html

[U109] JS：数组分组
来源：http://dali.jqgfzy.top/Article/details/gt2hgwhjnry.html

Object.groupBy(arr, x => x.type)
来源：http://dali.havefunace.top/Article/details/gt2qptkyaac.html

[U110] JS：数组分块
来源：http://dali.vqdsnc.cn/Article/details/gt2mmjwhxqm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.redwolf501.top/Article/details/gt2gkbmykjc.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjhkqhs.html

new Map(Object.entries(obj))
来源：http://dali.aizwys.cn/Article/details/gt2gkskxlmp.html

[U112] JS：字符串补位
来源：http://dali.svipenyu.cn/Article/details/gt2pnnxldno.html

"7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gt2vitsumok.html

[U113] JS：正则替换全部
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wxbwbjzv.html

s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2awxwgwyc.html

[U114] JS：JSON 深比较
来源：http://dali.gzhubu.top/Article/details/gt2cpxpstcx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj202588.top/Article/details/gt2sagfonci.html

[U115] JS：生成 UUID
来源：http://dali.snrcjt.cn/Article/details/gt2iijrlhlu.html

crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gt2wrovtlyt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cqqwz.cn/Article/details/gt2gfdfkzpl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.birdmap.top/Article/details/gt2lltatiat.html

[U117] JS：单元测试
来源：http://dali.nwbrower.top/Article/details/gt2kynbbwnk.html

npm i -D vitest;  npx vitest
来源：http://dali.yuxming.cn/Article/details/gt2plvzuliw.html

[U118] JS：开发服务器
来源：http://dali.vqdsnc.cn/Article/details/gt2soynolta.html

npm i -D vite;  npx vite
来源：http://dali.hfpthk.cn/Article/details/gt2yalpbdqg.html

[U119] JS：生产构建
来源：http://dali.jinghuilouyu.cn/Article/details/gt2celceqhe.html

npx vite build
来源：http://dali.fengsongda.top/Article/details/gt2qzglibad.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jyoumei.cn/Article/details/gt2vwmlwzqu.html

import.meta.env.VITE_API_URL
来源：http://dali.dianchejie.cn/Article/details/gt2uhkkaalg.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2kyesjlvx.html

统计汇总
来源：http://dali.ppjwa.cn/Article/details/gt2xapfmqao.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2onakwjve.html

按语言统计（条）：
来源：http://dali.quarkkingdee.top/Article/details/gt2yzgkeiff.html

Python ......... 252
来源：http://dali.wangdashe.top/Article/details/gt2gwyxojpf.html

PHP ............ 252
来源：http://dali.xylfe.cn/Article/details/gt2bylklcye.html

JavaScript ..... 252
来源：http://dali.shangyingyoupin.top/Article/details/gt2rkhifnfd.html

TypeScript ..... 212
来源：http://dali.yonumen.top/Article/details/gt2vodzbkiy.html

Java ........... 212
来源：http://dali.daria6918.cn/Article/details/gt2wkzkdvbi.html

Go ............. 212
来源：http://dali.wangdashe.top/Article/details/gt2utoasiwf.html

Ruby ........... 212
来源：http://dali.jinqigufen.top/Article/details/gt2tdujuvnj.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2upxqtuku.html

C .............. 30
来源：http://dali.316326.xyz/Article/details/gt2zwbcelvd.html

C++ ............ 30
来源：http://dali.dianchejie.cn/Article/details/gt2okurhsao.html

SQL ............ 90
来源：http://dali.cashguo.top/Article/details/gt2vmygbncz.html

Bash ........... 80
来源：http://dali.ydzc1.top/Article/details/gt2ibcyjlni.html

Kotlin ......... 15
来源：http://dali.yangfankeji.com/Article/details/gt2fwshogrp.html

Swift .......... 15
来源：http://dali.pycfn.com/Article/details/gt2gybfievb.html

Lua ............ 10
来源：http://dali.gzhubu.top/Article/details/gt2puixbvug.html

Perl ........... 10
来源：http://dali.guannengcc.top/Article/details/gt2fosedyvt.html

Scala .......... 10
来源：http://dali.sufxvd.cn/Article/details/gt2qxamnbsb.html

------------------------------------
来源：http://dali.c1oappe.top/Article/details/gt2snigsskm.html

合计 ........... 2106 条
来源：http://dali.ybcxt.top/Article/details/gt2wqnfvcix.html

按章节统计：
来源：http://dali.hnqzz.top/Article/details/gt2mwfjcptu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xulayynt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xziqi.cn/Article/details/gt2htrqwqbn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.316326.xyz/Article/details/gt2sflbnxsq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jqgufenzy.top/Article/details/gt2flpbopyl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yj20258.top/Article/details/gt2yynlqwcv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhixingplan.top/Article/details/gt2nbbdlujm.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.chenjidiqi.icu/Article/details/gt2bzfcafxa.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jyoumei.cn/Article/details/gt2khwqipuy.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gt2nvafljgx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.chenzaomai.com/Article/details/gt2nzvqxnvd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gt2bplspwqm.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gt2sltbncdl.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gt2jryphzts.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yangfankeji.com/Article/details/gt2bdtlfdvj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cucudq.cn/Article/details/gt2aurooikt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gt2fmryvvol.html

Q SQL 专题                              90
来源：http://dali.havefunace.top/Article/details/gt2eijtmfqt.html

R Bash 专题                             80
来源：http://dali.zhengqikj.top/Article/details/gt2qqzqwirj.html

S C / C++ 专题                          60
来源：http://dali.ydzc1.top/Article/details/gt2putqzbkj.html

T 其他语言补充                          60
来源：http://dali.0kj1m.cn/Article/details/gt2eukdgzjv.html

U 高频实用片段                         120
来源：http://dali.yueranfly.top/Article/details/gt2pbgycqhw.html

------------------------------------
来源：http://dali.sysykeji.top/Article/details/gt2zyndodae.html

合计                                  2106 条
来源：http://dali.cucudq.cn/Article/details/gt2mimlqfls.html

--------------------------------------------------------------------------------
来源：http://dali.fengsongda.top/Article/details/gt2synxprte.html

使用提醒
来源：http://dali.fengsongda.top/Article/details/gt2gmucuuno.html

--------------------------------------------------------------------------------
来源：http://dali.smart0.xyz/Article/details/gt2dkxtgoav.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ppjwa.cn/Article/details/gt2aerykgbw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.haohaochexian.top/Article/details/gt2sqxrzqul.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.shangyingyoupin.top/Article/details/gt2itsynvgi.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.pycfn.com/Article/details/gt2rnwndiia.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.chenjidiqi.icu/Article/details/gt2hbqyztln.html

—— 文件结束 ——
来源：http://dali.gogol.net.cn/Article/details/gt2ndcisadl.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2ualimqva.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hysaishi.cn/Article/details/gt2bpyvyone.html

Common Programming Examples Cheat Book
来源：http://dali.gogol.net.cn/Article/details/gt2qokyuilw.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2koyjovsv.html

【收录内容】
来源：http://dali.tianlin.xyz/Article/details/gt2rjdskmqc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shuidangran.top/Article/details/gt2rklpixyg.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jqgufenzy.top/Article/details/gt2ixyzlcsq.html

SQL · Bash · C · C++
来源：http://dali.svipenyu.cn/Article/details/gt2qgpxtnwg.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.fengsongda.top/Article/details/gt2hnxgsqck.html

【使用说明】
来源：http://dali.zhoulong.xyz/Article/details/gt2hbntafom.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.nanxinkj.top/Article/details/gt2ykaqqegm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.sxryk.cn/Article/details/gt2irxequao.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.chenlongwang.top/Article/details/gt2oueqvqvi.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.mhx1999.top/Article/details/gt2edorqpwx.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.cucudq.cn/Article/details/gt2tcxxzhmr.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jinqigfzy.top/Article/details/gt2cxslxzki.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cqqwz.cn/Article/details/gt2shmfbnht.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.svipenyu.cn/Article/details/gt2qpjnqwsx.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhoulong.xyz/Article/details/gt2ullgypxm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xuanzx.com/Article/details/gt2zatjswbp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.bjfxy.top/Article/details/gt2gilccdfk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.shangyingyoupin.top/Article/details/gt2lcbvbmmz.html

【文件统计】
来源：http://dali.hnxiangtu.top/Article/details/gt2ifjokblg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhoulong.xyz/Article/details/gt2lvptyywm.html

--------------------------------------------------------------------------------
来源：http://dali.jianghu66.top/Article/details/gt2ciiwklan.html

目  录
来源：http://dali.yj20258888.top/Article/details/gt2grgzfnug.html

--------------------------------------------------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gt2ipwgbbup.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.haohaochexian.top/Article/details/gt2biidkblm.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hywenlv.cn/Article/details/gt2ihojhryw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ubigzhap.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.cucudq.cn/Article/details/gt2zucvycfg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.9152youxi.cn/Article/details/gt2mwnvtgnl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yongpay.top/Article/details/gt2kystynwx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ehwqpu.com/Article/details/gt2nqypcfjg.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2rwtymfgh.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aujvlszl.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ufskskgr.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.fengsongda.top/Article/details/gt2ylmonbdp.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.svipenyu.cn/Article/details/gt2jevvuytd.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gt2wsribaih.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.fzhhl.top/Article/details/gt2xbzfqudj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shzxlz.cn/Article/details/gt2eexzefps.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2gaebeszq.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yvedp.cn/Article/details/gt2itynrvcl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hammf.cn/Article/details/gt2hwxzjzbb.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ppjwa.cn/Article/details/gt2zzigkmhk.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hongshengwenyu.top/Article/details/gt2qzisegra.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jqgfzy.top/Article/details/gt2ntmhamzk.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2vbtkawpd.html

A. 基础语法与类型
来源：http://dali.mhx1999.top/Article/details/gt2ddvbwhxl.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2rsajzdkt.html

[A01] Hello World
来源：http://dali.yongpay.top/Article/details/gt2ofsdtwzc.html

Py:   print("Hello, World!")
来源：http://dali.xziqi.cn/Article/details/gt2mmgikzyr.html

PHP:  echo "Hello, World!";
来源：http://dali.hnxiangtu.top/Article/details/gt2czfgyuzh.html

JS:   console.log("Hello, World!");
来源：http://dali.wangdashe.top/Article/details/gt2pxtwubhg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yvedp.cn/Article/details/gt2eiprpgga.html

Java: System.out.println("Hello, World!");
来源：http://dali.jinqigufen.top/Article/details/gt2pbyxwnoa.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.gzhubu.top/Article/details/gt2gsmwsiai.html

Ruby: puts "Hello, World!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sjbpzfhf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uiibddgo.html

[A02] 变量声明与赋值
来源：http://dali.mhx1999.top/Article/details/gt2elteizio.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xuanzx.com/Article/details/gt2qeyvqfnb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.bjfxy.top/Article/details/gt2lupyddsn.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ivvv.top/Article/details/gt2fzuejphi.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.iojbl.cn/Article/details/gt2ozstaguy.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.9152youxi.cn/Article/details/gt2bmbzlakh.html

Go:   name := "Alex"; age := 20
来源：http://dali.316326.xyz/Article/details/gt2gwksqzjd.html

Ruby: name = "Alex"; age = 20
来源：http://dali.c1oappe.top/Article/details/gt2qsctjsuf.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hammf.cn/Article/details/gt2lspevule.html

[A03] 常量定义
来源：http://dali.xylfe.cn/Article/details/gt2pboyykui.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.sysykeji.top/Article/details/gt2fsypyhrj.html

PHP:  const PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2etfujnex.html

JS:   const PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gt2nirvhtda.html

TS:   const PI: number = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gt2gqbuqczj.html

Java: static final double PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gt2rypnohab.html

Go:   const PI = 3.14159
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vlbxvtfr.html

Ruby: PI = 3.14159
来源：http://dali.andypj.xyz/Article/details/gt2jwwenszd.html

C#:   const double PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bqotjmyz.html

[A04] 判断变量类型
来源：http://dali.gogol.net.cn/Article/details/gt2gtboppgb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2thwrijpz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hywenlv.cn/Article/details/gt2kjffdjku.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.aizwys.cn/Article/details/gt2ymgwuvgx.html

TS:   typeof x; x instanceof Date
来源：http://dali.fzhhl.top/Article/details/gt2zcefiyfj.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yvedp.cn/Article/details/gt2qdsmhldm.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hfpthk.cn/Article/details/gt2iyoowttg.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yangfankeji.com/Article/details/gt2dhxmupxk.html

C#:   x.GetType().Name; x is int
来源：http://dali.gzhubu.top/Article/details/gt2ydgrphvw.html

[A05] 整数除法与取模
来源：http://dali.xuetiantiany.cn/Article/details/gt2btmcgltn.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xylfe.cn/Article/details/gt2folkyekf.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2spceoipd.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gt2isynuqkd.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2ylsuyzgx.html

Java: 7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gt2igslxxzc.html

Go:   7 / 2; 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gt2ujpiarwn.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yj202588.top/Article/details/gt2mxevjkbb.html

C#:   7 / 2; 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gt2vyjvchoq.html

[A06] 字符串转数字
来源：http://dali.redwolf501.top/Article/details/gt2zxutywud.html

Py:   int("42"); float("3.14")
来源：http://dali.316326.xyz/Article/details/gt2gzlmsdoj.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.dianchejie.cn/Article/details/gt2mzkelybe.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.wangshuangyany.cn/Article/details/gt2sdlevtia.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.daria6918.cn/Article/details/gt2sbqzlqgn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.gogol.net.cn/Article/details/gt2nddpukyq.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.tanke756.top/Article/details/gt2pcvpozlh.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yonumen.top/Article/details/gt2gdaumlme.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.guowangkeji.top/Article/details/gt2svxzfkye.html

[A07] 数字转字符串
来源：http://dali.hysaishi.cn/Article/details/gt2klbwejuq.html

Py:   str(42)
来源：http://dali.chenlongwang.top/Article/details/gt2wmiljeiv.html

PHP:  (string) 42; strval(42)
来源：http://dali.tian-w.cn/Article/details/gt2jwdvbhbg.html

JS:   String(42); (42).toString()
来源：http://dali.chenzaomai.com/Article/details/gt2qtmroiho.html

TS:   String(42)
来源：http://dali.bjfxy.top/Article/details/gt2xrsjfstq.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.tianlin.xyz/Article/details/gt2uksyexgf.html

Go:   strconv.Itoa(42)
来源：http://dali.tian-w.cn/Article/details/gt2dtlpqjlk.html

Ruby: 42.to_s
来源：http://dali.c1oappe.top/Article/details/gt2onevtyjp.html

C#:   42.ToString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aykxdxlx.html

[A08] 取整与四舍五入
来源：http://dali.zdqjudy.top/Article/details/gt2bgfwiges.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.iojbl.cn/Article/details/gt2qynkgvoj.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.quarkkingdee.top/Article/details/gt2unjwsygd.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yongpay.top/Article/details/gt2qbzqauuy.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.sysykeji.top/Article/details/gt2uvxzgrfb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.quarkkingdee.top/Article/details/gt2cyuhdmnj.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yilfenuh.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.gzhubu.top/Article/details/gt2ljtpedtv.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hywenlv.cn/Article/details/gt2zrifcphp.html

[A09] 绝对值与最大最小值
来源：http://dali.svipenyu.cn/Article/details/gt2nsmbmpbf.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gt2ovfdbppm.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.bjfxy.top/Article/details/gt2lrpesdwv.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wysevjvt.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.xziqi.cn/Article/details/gt2lgqokhth.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gt2xyjqxtle.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.ydzc1.top/Article/details/gt2munfwdjt.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.guowangkeji.top/Article/details/gt2rqwhrcyj.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gt2gqslvwlh.html

[A10] 生成随机数
来源：http://dali.aizwys.cn/Article/details/gt2pxdvzuyl.html

Py:   import random; random.randint(1, 100)
来源：http://dali.tian-w.cn/Article/details/gt2bvnjmxlb.html

PHP:  random_int(1, 100);
来源：http://dali.jyoumei.cn/Article/details/gt2iugbaykl.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.fengsongda.top/Article/details/gt2dcksekwv.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2falhweir.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhoulong.xyz/Article/details/gt2cdwhvmez.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.smart0.xyz/Article/details/gt2qpldtovx.html

Ruby: rand(1..100)
来源：http://dali.guannengcc.top/Article/details/gt2yegrbmqv.html

C#:   new Random().Next(1, 101)
来源：http://dali.yonumen.top/Article/details/gt2yofmlwqa.html

[A11] 条件表达式（三元）
来源：http://dali.jqgfzy.top/Article/details/gt2rlcuythl.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.sweek.top/Article/details/gt2wwjtnqyu.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.fzhhl.top/Article/details/gt2yttvzdaf.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.shangyingyoupin.top/Article/details/gt2gvxqkuno.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.sufxvd.cn/Article/details/gt2bmqqzjvo.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.feifeiyinyue.top/Article/details/gt2hhytbkld.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.shzxlz.cn/Article/details/gt2fwuzfddc.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.feifeiyinyue.top/Article/details/gt2whwdvvtj.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.9152youxi.cn/Article/details/gt2madqmgeh.html

[A12] 字符串插值 / 格式化
来源：http://dali.yueranfly.top/Article/details/gt2fpngaefw.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzpimxo.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.chenlongwang.top/Article/details/gt2vymputty.html

JS:   `Hello, ${name}!`
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hnfsiwsm.html

TS:   `Hello, ${name}!`
来源：http://dali.wangdashe.top/Article/details/gt2ontwbkyk.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.daria6918.cn/Article/details/gt2dqjchilm.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.kuanghao11.cn/Article/details/gt2gloohbdx.html

Ruby: "Hello, #{name}!"
来源：http://dali.yanxiufei.cn/Article/details/gt2spzaktdz.html

C#:   $"Hello, {name}!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jqdcdmjk.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.hnxiangtu.top/Article/details/gt2sacaqvpz.html

Py:   "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gt2kfebhofe.html

PHP:  "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gt2zxzvrjob.html

JS:   "第一行\n第二行"
来源：http://dali.andypj.xyz/Article/details/gt2ogxkcbqk.html

TS:   "第一行\n第二行"
来源：http://dali.zhiwuduotai.top/Article/details/gt2bvdpnfpl.html

Java: "第一行\n第二行"
来源：http://dali.haohaochexian.top/Article/details/gt2domsancy.html

Go:   "第一行\n第二行"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sbdjppzn.html

Ruby: "第一行\n第二行"
来源：http://dali.ppjwa.cn/Article/details/gt2lxymaaue.html

C#:   "第一行\n第二行"
来源：http://dali.316326.xyz/Article/details/gt2nnbgnwhv.html

[A14] 注释写法
来源：http://dali.nanxinkj.top/Article/details/gt2rttyzlor.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.shangyingyoupin.top/Article/details/gt2mzvjpvqu.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.ppjwa.cn/Article/details/gt2dfljykns.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2moieqwtr.html

TS:   // 单行；/* 多行 */
来源：http://dali.yj202588.top/Article/details/gt2uukpbtfi.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jqgfzy.top/Article/details/gt2ugsprrgv.html

Go:   // 单行；/* 多行 */
来源：http://dali.yangfankeji.com/Article/details/gt2ytpbsbvq.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.fzhhl.top/Article/details/gt2doasvuiz.html

C#:   // 单行；/* 多行 */
来源：http://dali.nwbrower.top/Article/details/gt2egizewkc.html

[A15] 空值判断与默认值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wrwtqmct.html

Py:   value = data or "默认值"
来源：http://dali.yongpay.top/Article/details/gt2atnjyvjb.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.sysykeji.top/Article/details/gt2bxholaom.html


<!-- 参考信息 -->