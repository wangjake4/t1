代发 wailian999

[U87] JS：解构默认值
来源：http://dali.jianghu66.top/Article/details/gtrarylepj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ybcxt.top/Article/details/gtxmhzdjlm.html

[U88] JS：对象展开合并
来源：http://dali.nanxinkj.top/Article/details/gtgzgtfryw.html

{ ...a, ...b }
来源：http://dali.yvedp.cn/Article/details/gtuepmkaik.html

[U89] JS：数组去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhghysyk.html

[...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvywnelj.html

[U90] JS：数字数组排序
来源：http://dali.hfpthk.cn/Article/details/gtwfrjzxtd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gtdtehstuz.html

[U91] JS：对象键值遍历
来源：http://dali.bjfxy.top/Article/details/gtyuryisqw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ppjwa.cn/Article/details/gtjoavrynh.html

[U92] JS：深拷贝
来源：http://dali.zhixingplan.top/Article/details/gtiobxhlxb.html

structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtqjzdyxof.html

[U93] JS：模板字符串
来源：http://dali.pengpengdd.cyou/Article/details/gttbmmeecz.html

`共 ${n} 条`
来源：http://dali.nwbrower.top/Article/details/gtxtfexnqv.html

[U94] JS：箭头函数
来源：http://dali.yvedp.cn/Article/details/gtmvparret.html

const double = x => x * 2;
来源：http://dali.0kj1m.cn/Article/details/gtceqbdrec.html

[U95] JS：Promise 包装
来源：http://dali.jinqigufen.top/Article/details/gtcmkekspg.html

new Promise((resolve, reject) => {})
来源：http://dali.jinqigufen.top/Article/details/gtwgxkydqr.html

[U96] JS：async/await 与异常
来源：http://dali.cheryme.top/Article/details/gtlgjnrvzd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gtnuwjyscm.html

[U97] JS：并发请求
来源：http://dali.jqgufenzy.top/Article/details/gtkevnywjm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbomhjvrq.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gtsmhvzwty.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.ppjwa.cn/Article/details/gtxlqxsdhb.html

[U99] JS：事件监听
来源：http://dali.hnqzz.top/Article/details/gtppgikbbi.html

el.addEventListener("click", e => {})
来源：http://dali.zhixingplan.top/Article/details/gtgebcftdg.html

[U100] JS：DOM 查询
来源：http://dali.dianchejie.cn/Article/details/gttbuypoda.html

document.querySelector(".item")
来源：http://dali.fzhhl.top/Article/details/gtbsrahzub.html

[U101] JS：classList 操作
来源：http://dali.gogol.net.cn/Article/details/gtptwmenxj.html

el.classList.toggle("active")
来源：http://dali.pengpengdd.cyou/Article/details/gteqqcyarx.html

[U102] JS：本地存储
来源：http://dali.cucudq.cn/Article/details/gtzdbgtgsq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yueranfly.top/Article/details/gtpbmmdqkn.html

[U103] JS：定时器
来源：http://dali.hfpthk.cn/Article/details/gtvdtucclq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ivvv.top/Article/details/gtnbrlhfao.html

[U104] JS：防抖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppzjotho.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gtjwljjyyb.html

[U105] JS：节流
来源：http://dali.jqgufenzy.top/Article/details/gtjdvhublz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yuanzhike.top/Article/details/gtvmwxafxt.html

[U106] JS：日期格式化
来源：http://dali.meibo888.top/Article/details/gtxakwioyp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cqqwz.cn/Article/details/gtfbjbogty.html

[U107] JS：数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gturkmgpru.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gtzdkncuvx.html

[U108] JS：随机整数
来源：http://dali.shuidangran.top/Article/details/gtupdszdan.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hfpthk.cn/Article/details/gtvfuwvkir.html

[U109] JS：数组分组
来源：http://dali.zycfv.cn/Article/details/gtktsurxzb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhengqikj.top/Article/details/gtgaupklmk.html

[U110] JS：数组分块
来源：http://dali.hnxiangtu.top/Article/details/gtjjgqafhw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.meibo888.top/Article/details/gtkubumtzn.html

[U111] JS：对象转 Map
来源：http://dali.jlsjyb.cn/Article/details/gtxoutlzfx.html

new Map(Object.entries(obj))
来源：http://dali.xinyue.icu/Article/details/gtraeyuknx.html

[U112] JS：字符串补位
来源：http://dali.gaohongyu789.top/Article/details/gtcwrytaxr.html

"7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gtiatwnuez.html

[U113] JS：正则替换全部
来源：http://dali.cqqwz.cn/Article/details/gtgcmtvrbp.html

s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtevyflpmf.html

[U114] JS：JSON 深比较
来源：http://dali.havefunace.top/Article/details/gtsffxkaif.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.0kj1m.cn/Article/details/gthmllbkzk.html

[U115] JS：生成 UUID
来源：http://dali.andypj.xyz/Article/details/gtzrrbmyhp.html

crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gtowahzxon.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jianghu66.top/Article/details/gttzbecxkw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.wangdashe.top/Article/details/gtiniurukt.html

[U117] JS：单元测试
来源：http://dali.aizwys.cn/Article/details/gtzldnwvpc.html

npm i -D vitest;  npx vitest
来源：http://dali.andypj.xyz/Article/details/gttfuylmoa.html

[U118] JS：开发服务器
来源：http://dali.hfpthk.cn/Article/details/gtzyuphqdh.html

npm i -D vite;  npx vite
来源：http://dali.aibaodan.cn/Article/details/gtswkmmdlr.html

[U119] JS：生产构建
来源：http://dali.guowangkeji.top/Article/details/gthqlqtdwz.html

npx vite build
来源：http://dali.guannengcc.top/Article/details/gtoxjuhjww.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.tianlin.xyz/Article/details/gtopejxfed.html

import.meta.env.VITE_API_URL
来源：http://dali.snrcjt.cn/Article/details/gtcefgfbvk.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtmuggvoys.html

统计汇总
来源：http://dali.haohaochexian.top/Article/details/gtmyzmykuy.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtdnnybzrg.html

按语言统计（条）：
来源：http://dali.zdqjudy.top/Article/details/gtrhcztrix.html

Python ......... 252
来源：http://dali.yueranfly.top/Article/details/gtcbpgsfic.html

PHP ............ 252
来源：http://dali.sweek.top/Article/details/gtjsndjuzr.html

JavaScript ..... 252
来源：http://dali.xylfe.cn/Article/details/gttsldsebn.html

TypeScript ..... 212
来源：http://dali.yongpay.top/Article/details/gtkmutestl.html

Java ........... 212
来源：http://dali.zhiwuduotai.top/Article/details/gtbazafwtw.html

Go ............. 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtaepixdub.html

Ruby ........... 212
来源：http://dali.daxiang520.top/Article/details/gtjbcmbhjc.html

C# ............. 212
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagllptty.html

C .............. 30
来源：http://dali.yanxiufei.cn/Article/details/gtkqpyvkak.html

C++ ............ 30
来源：http://dali.jyoumei.cn/Article/details/gtyfibaumg.html

SQL ............ 90
来源：http://dali.birdmap.top/Article/details/gtpstwwtre.html

Bash ........... 80
来源：http://dali.yj202588.top/Article/details/gthennsndw.html

Kotlin ......... 15
来源：http://dali.guowangkeji.top/Article/details/gttubuyyrn.html

Swift .......... 15
来源：http://dali.ydzc1.top/Article/details/gtimfkyxto.html

Lua ............ 10
来源：http://dali.jinqigfzy.top/Article/details/gtgaxyxqkf.html

Perl ........... 10
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvirfoavo.html

Scala .......... 10
来源：http://dali.guowangkeji.top/Article/details/gtrtfnnxif.html

------------------------------------
来源：http://dali.xylfe.cn/Article/details/gtjerpukmx.html

合计 ........... 2106 条
来源：http://dali.jyoumei.cn/Article/details/gtyhqccjxb.html

按章节统计：
来源：http://dali.nanxuanxn.top/Article/details/gtquynaksd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.vqdsnc.cn/Article/details/gtjoeygtph.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.tianlin.xyz/Article/details/gtklugomrc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.vqdsnc.cn/Article/details/gtwhmqzzkw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.iojbl.cn/Article/details/gtqxfgkcyj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.tanke756.top/Article/details/gtfogflenx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yanxiufei.cn/Article/details/gthcdbronh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.c1oappe.top/Article/details/gtlavbnzbu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhiwuduotai.top/Article/details/gtsgvonzfv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gtjxnnmocg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xinyue.icu/Article/details/gtgixjjqbc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gthqqnhsft.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gthgmmrrht.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gtnvsnhziv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cucudq.cn/Article/details/gtvomuatoj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ehwqpu.com/Article/details/gtrxoltwyl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gtwjssiuac.html

Q SQL 专题                              90
来源：http://dali.yuxming.cn/Article/details/gtwpeudzqt.html

R Bash 专题                             80
来源：http://dali.meibo888.top/Article/details/gtyvwjeaoa.html

S C / C++ 专题                          60
来源：http://dali.316326.xyz/Article/details/gtyxuhdonv.html

T 其他语言补充                          60
来源：http://dali.yj20258888.top/Article/details/gtufeuacqu.html

U 高频实用片段                         120
来源：http://dali.wangdashe.top/Article/details/gtjeqctnzv.html

------------------------------------
来源：http://dali.cashguo.top/Article/details/gthfddonwf.html

合计                                  2106 条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmmxdcwx.html

--------------------------------------------------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gtyumcftnm.html

使用提醒
来源：http://dali.kuanghao11.cn/Article/details/gtuvmaykcr.html

--------------------------------------------------------------------------------
来源：http://dali.guannengcc.top/Article/details/gtbnbmijbu.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.smart0.xyz/Article/details/gtybhzcuei.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cheryme.top/Article/details/gtmzugqjuy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hnxiangtu.top/Article/details/gtjuamombh.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.tian-w.cn/Article/details/gtgraiidel.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cashguo.top/Article/details/gtvbtrkkhy.html

—— 文件结束 ——
来源：http://dali.fengsongda.top/Article/details/gtlrmwcgax.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtmjxpxezw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.daria6918.cn/Article/details/gtiwyspjra.html

Common Programming Examples Cheat Book
来源：http://dali.meibo888.top/Article/details/gthyyifejm.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtyykywplf.html

【收录内容】
来源：http://dali.havefunace.top/Article/details/gtdbidbjsc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shzxlz.cn/Article/details/gtceplcrpb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.gogol.net.cn/Article/details/gtxonpzxls.html

SQL · Bash · C · C++
来源：http://dali.havefunace.top/Article/details/gtchujtdhv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.iojbl.cn/Article/details/gtwsiznjkh.html

【使用说明】
来源：http://dali.meibo888.top/Article/details/gtarcmbsyc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhixingplan.top/Article/details/gtyirmuifj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yuanzhike.top/Article/details/gtawpxkeai.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jyoumei.cn/Article/details/gtrzilsqwa.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.bjfxy.top/Article/details/gtjihmskzy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jianghu66.top/Article/details/gtyxusenws.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenzaomai.com/Article/details/gtoicxsjzj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gogol.net.cn/Article/details/gtxduffijl.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yj20258.top/Article/details/gthiswdpvc.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shuidangran.top/Article/details/gtcbcgnvmk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.chenlongwang.top/Article/details/gtycpilbsy.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhiwuduotai.top/Article/details/gtrcfktlhh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cashguo.top/Article/details/gtxnzwrymb.html

【文件统计】
来源：http://dali.jqgufenzy.top/Article/details/gtytdznnwv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfkrkboa.html

--------------------------------------------------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gttspdhmbc.html

目  录
来源：http://dali.wangdashe.top/Article/details/gtxrztfruw.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtprobwgbj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gtsuwtsvvb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jlsjyb.cn/Article/details/gtiafxaeex.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.vqdsnc.cn/Article/details/gtbgntzjdc.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hammf.cn/Article/details/gthtilorvv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yongpay.top/Article/details/gtkbtspzmi.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.gogol.net.cn/Article/details/gtdyqbnoyp.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.vqdsnc.cn/Article/details/gtzegpfvky.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdmlqllc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gtuqaltvnx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.guowangkeji.top/Article/details/gtbojtysrb.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hywenlv.cn/Article/details/gtfvgqsszl.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gtdqtetlfv.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gtlsuceogd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.tanke756.top/Article/details/gtmvhmcldi.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xuetiantiany.cn/Article/details/gttroggauv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gtfvxirjtz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hywenlv.cn/Article/details/gtkcwuecyo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.nwbrower.top/Article/details/gtowjpioku.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinqigfzy.top/Article/details/gtxfusdtsa.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.haohaochexian.top/Article/details/gtkyfvswgf.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sxryk.cn/Article/details/gtexgqolui.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtvjjeleam.html

A. 基础语法与类型
来源：http://dali.zdqjudy.top/Article/details/gtktkcsnaw.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtrbhcqgon.html

[A01] Hello World
来源：http://dali.jyoumei.cn/Article/details/gtxbhvxcij.html

Py:   print("Hello, World!")
来源：http://dali.hongshengwenyu.top/Article/details/gtsfyxmkpf.html

PHP:  echo "Hello, World!";
来源：http://dali.snrcjt.cn/Article/details/gthlvugsqo.html

JS:   console.log("Hello, World!");
来源：http://dali.xuanzx.com/Article/details/gtxuuflxzr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jinqigufen.top/Article/details/gtuwcvmseq.html

Java: System.out.println("Hello, World!");
来源：http://dali.aizwys.cn/Article/details/gttuqtkajt.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ehwqpu.com/Article/details/gtbyxtoskp.html

Ruby: puts "Hello, World!"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtterbonvk.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gtnosgjtry.html

[A02] 变量声明与赋值
来源：http://dali.yueranfly.top/Article/details/gtcjdxtsxo.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhiwuduotai.top/Article/details/gtiprpuvjd.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.smart0.xyz/Article/details/gtgmrphuse.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.mhx1999.top/Article/details/gtdebfygvv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.chenzaomai.com/Article/details/gtrcbemopa.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yj202588.top/Article/details/gtjahcmudk.html

Go:   name := "Alex"; age := 20
来源：http://dali.hnqzz.top/Article/details/gttfygcozx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xuanzx.com/Article/details/gtjvilvabx.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.aibaodan.cn/Article/details/gtfboylwie.html

[A03] 常量定义
来源：http://dali.zycfv.cn/Article/details/gtazhiecvw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cdnleiting.top/Article/details/gtlsnzabqo.html

PHP:  const PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtrjpumxym.html

JS:   const PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gtbsrqnqkq.html

TS:   const PI: number = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtusbvjwew.html

Java: static final double PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtklyakyng.html

Go:   const PI = 3.14159
来源：http://dali.zycfv.cn/Article/details/gtszpldkec.html

Ruby: PI = 3.14159
来源：http://dali.tanke756.top/Article/details/gtcummwelh.html

C#:   const double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gteuenydik.html

[A04] 判断变量类型
来源：http://dali.yonumen.top/Article/details/gttxhsabzy.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.mhx1999.top/Article/details/gtulzttoju.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cqqwz.cn/Article/details/gtzbwrnnae.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jyoumei.cn/Article/details/gteffrshio.html

TS:   typeof x; x instanceof Date
来源：http://dali.cdnleiting.top/Article/details/gtqwmlvepm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jlsjyb.cn/Article/details/gtaqdiesew.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.chenzaomai.com/Article/details/gthhxxonuz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxrhuhyy.html

C#:   x.GetType().Name; x is int
来源：http://dali.hongshengwenyu.top/Article/details/gtesiaxgax.html

[A05] 整数除法与取模
来源：http://dali.jinqigufen.top/Article/details/gtjtbusplt.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yj202588.top/Article/details/gtbxkmxisa.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yj20258888.top/Article/details/gtingfnanu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.c1oappe.top/Article/details/gtucbvybsz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ydzc1.top/Article/details/gttgilkijz.html

Java: 7 / 2; 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtsornhzhy.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gthuhaoxyu.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.dashuyun.cn/Article/details/gtcjrqhugc.html

C#:   7 / 2; 7 % 2
来源：http://dali.yongpay.top/Article/details/gtovmuqgbs.html

[A06] 字符串转数字
来源：http://dali.tianlin.xyz/Article/details/gtrclpnxzl.html

Py:   int("42"); float("3.14")
来源：http://dali.shuidangran.top/Article/details/gtplzucbtl.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.sysykeji.top/Article/details/gtxaefepgv.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yongpay.top/Article/details/gtrnttjeew.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.dashuyun.cn/Article/details/gtwwxtgcvv.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.tian-w.cn/Article/details/gtbscnzzye.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhiwuduotai.top/Article/details/gttcwffjkw.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yanxiufei.cn/Article/details/gtxtofqujr.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.ppjwa.cn/Article/details/gtmawvshyi.html

[A07] 数字转字符串
来源：http://dali.ybcxt.top/Article/details/gtvskloxxk.html

Py:   str(42)
来源：http://dali.gaohongyu789.top/Article/details/gtroqygmcg.html

PHP:  (string) 42; strval(42)
来源：http://dali.xuetiantiany.cn/Article/details/gtdnckvxlv.html

JS:   String(42); (42).toString()
来源：http://dali.xylfe.cn/Article/details/gtwaiexblm.html

TS:   String(42)
来源：http://dali.gaohongyu789.top/Article/details/gtrnjfyckv.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.xuanzx.com/Article/details/gtamkvdcll.html

Go:   strconv.Itoa(42)
来源：http://dali.meibo888.top/Article/details/gttuuzffqg.html

Ruby: 42.to_s
来源：http://dali.zhoulong.xyz/Article/details/gtynwcwpfn.html

C#:   42.ToString()
来源：http://dali.ydzc1.top/Article/details/gtsehsftiu.html

[A08] 取整与四舍五入
来源：http://dali.yj20258.top/Article/details/gtzhudtteg.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.snrcjt.cn/Article/details/gtubmrpdbz.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.shangyingyoupin.top/Article/details/gtpbypyynp.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.pycfn.com/Article/details/gtopjsdfnz.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.sxryk.cn/Article/details/gtzbqabyix.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.316326.xyz/Article/details/gttbfiiead.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zdqjudy.top/Article/details/gtreskofnb.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yangfankeji.com/Article/details/gtuvprxxvj.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.shuidangran.top/Article/details/gttsofdogo.html

[A09] 绝对值与最大最小值
来源：http://dali.pycfn.com/Article/details/gtgfewsqkm.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtrmetogsf.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xuanzx.com/Article/details/gtjkvjquxv.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hnqzz.top/Article/details/gtciypmhvk.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gtjsmfsvaj.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.redwolf501.top/Article/details/gtrrwoonoy.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.quarkkingdee.top/Article/details/gthzyrfihf.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.dashuyun.cn/Article/details/gtjcgzdnel.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.316326.xyz/Article/details/gtawusmlvf.html

[A10] 生成随机数
来源：http://dali.bjfxy.top/Article/details/gtytpvveny.html

Py:   import random; random.randint(1, 100)
来源：http://dali.hongshengwenyu.top/Article/details/gtqltfylkz.html

PHP:  random_int(1, 100);
来源：http://dali.tanke756.top/Article/details/gteroxspwt.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yonumen.top/Article/details/gtqlntwvtw.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtizvqviib.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jinqigufen.top/Article/details/gttwegsqsq.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hnxiangtu.top/Article/details/gtbsqocewk.html

Ruby: rand(1..100)
来源：http://dali.hysaishi.cn/Article/details/gtboplhkll.html

C#:   new Random().Next(1, 101)
来源：http://dali.jiagoushi.top/Article/details/gtnrclwhhn.html

[A11] 条件表达式（三元）
来源：http://dali.sweek.top/Article/details/gtrsdjhhwn.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.tanke756.top/Article/details/gtlrlmxzhk.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.iojbl.cn/Article/details/gtsdktqfhc.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.nanxuanxn.top/Article/details/gtsrlavjms.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.chenlongwang.top/Article/details/gtklnlpcrx.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.wangdashe.top/Article/details/gtfgfxvzlg.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.nwbrower.top/Article/details/gtnxguuode.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.xziqi.cn/Article/details/gtbeqjeleb.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.redwolf501.top/Article/details/gtyneickot.html

[A12] 字符串插值 / 格式化
来源：http://dali.sweek.top/Article/details/gthfbaoojy.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jinqigufen.top/Article/details/gtglwedelg.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.hywenlv.cn/Article/details/gthjsvjhbq.html

JS:   `Hello, ${name}!`
来源：http://dali.daria6918.cn/Article/details/gtsbklnfnt.html

TS:   `Hello, ${name}!`
来源：http://dali.chenjidiqi.icu/Article/details/gtihbzjlrf.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yuanzhike.top/Article/details/gtmpvxgmye.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jinqigufen.top/Article/details/gtoluijdnk.html

Ruby: "Hello, #{name}!"
来源：http://dali.mhx1999.top/Article/details/gtxawhvwor.html

C#:   $"Hello, {name}!"
来源：http://dali.hfpthk.cn/Article/details/gtmcltaams.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.hysaishi.cn/Article/details/gtucduhjvk.html

Py:   "第一行\n第二行"
来源：http://dali.hywenlv.cn/Article/details/gteokygtdc.html

PHP:  "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gtjuuyhymy.html

JS:   "第一行\n第二行"
来源：http://dali.jqgfzy.top/Article/details/gtnwzjpdvo.html

TS:   "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gtuqhyodjf.html

Java: "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gtfvucwenm.html

Go:   "第一行\n第二行"
来源：http://dali.quarkkingdee.top/Article/details/gtvyxdjtfv.html

Ruby: "第一行\n第二行"
来源：http://dali.chenlongwang.top/Article/details/gtruhthmrt.html

C#:   "第一行\n第二行"
来源：http://dali.zhixingplan.top/Article/details/gtwtzvblwv.html

[A14] 注释写法
来源：http://dali.jinqigufen.top/Article/details/gtnxmvqcam.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.shanyushiyangtech.top/Article/details/gtylbbujcp.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.tian-w.cn/Article/details/gtaadrebfd.html

JS:   // 单行；/* 多行 */
来源：http://dali.sweek.top/Article/details/gtfxfvgrfz.html

TS:   // 单行；/* 多行 */
来源：http://dali.daxiang520.top/Article/details/gtqdbwiojx.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwgzxkcv.html

Go:   // 单行；/* 多行 */
来源：http://dali.yonumen.top/Article/details/gtwtsivwrs.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegdlvphq.html


<!-- 参考信息 -->