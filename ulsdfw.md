代发 wailian999

[U83] JS：ES Module 导入导出
来源：http://dali.wangdashe.top/Article/details/gtgdwknxjq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yj20258888.top/Article/details/gtirrfiosk.html

[U84] JS：CommonJS 写法
来源：http://dali.yueranfly.top/Article/details/gtgkmrbokm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.nwbrower.top/Article/details/gtfotutgqs.html

[U85] JS：可选链
来源：http://dali.gogol.net.cn/Article/details/gtoqprkxbh.html

a?.b?.c
来源：http://dali.jqgfzy.top/Article/details/gtxbjxnkdt.html

[U86] JS：空值合并
来源：http://dali.cheryme.top/Article/details/gtnubmagrc.html

a ?? b
来源：http://dali.wangdashe.top/Article/details/gtdmrzxwpr.html

[U87] JS：解构默认值
来源：http://dali.jqgufenzy.top/Article/details/gtmvrprgfo.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yongpay.top/Article/details/gtbwettxka.html

[U88] JS：对象展开合并
来源：http://dali.meibo888.top/Article/details/gtfhkkanhy.html

{ ...a, ...b }
来源：http://dali.andypj.xyz/Article/details/gtdbnktxol.html

[U89] JS：数组去重
来源：http://dali.jqgfzy.top/Article/details/gtsidtadmh.html

[...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gtmntkrnbv.html

[U90] JS：数字数组排序
来源：http://dali.jlsjyb.cn/Article/details/gtklfbzxik.html

[...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gtvpatbkcx.html

[U91] JS：对象键值遍历
来源：http://dali.daxiang520.top/Article/details/gtmimdlxwx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.fzhhl.top/Article/details/gtwzgcfdkm.html

[U92] JS：深拷贝
来源：http://dali.tanke756.top/Article/details/gtvovdxhpi.html

structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gtlpsairmm.html

[U93] JS：模板字符串
来源：http://dali.redwolf501.top/Article/details/gtklpucypf.html

`共 ${n} 条`
来源：http://dali.jyoumei.cn/Article/details/gtpawnrbpz.html

[U94] JS：箭头函数
来源：http://dali.smart0.xyz/Article/details/gtgmipkntu.html

const double = x => x * 2;
来源：http://dali.xziqi.cn/Article/details/gtpwrcvbaa.html

[U95] JS：Promise 包装
来源：http://dali.fzhhl.top/Article/details/gtcsmmblnq.html

new Promise((resolve, reject) => {})
来源：http://dali.shuidangran.top/Article/details/gtnfnaepwm.html

[U96] JS：async/await 与异常
来源：http://dali.gotoacloud.top/Article/details/gtgjxyfcsf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gtdzfmsqec.html

[U97] JS：并发请求
来源：http://dali.birdmap.top/Article/details/gtuhachtzd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtnspjrnqy.html

[U98] JS：fetch 带 JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqjajesi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hammf.cn/Article/details/gtbofymbnx.html

[U99] JS：事件监听
来源：http://dali.xziqi.cn/Article/details/gtbqdxsgxg.html

el.addEventListener("click", e => {})
来源：http://dali.c1oappe.top/Article/details/gtvdkcxqaw.html

[U100] JS：DOM 查询
来源：http://dali.aibaodan.cn/Article/details/gtlpezlnvi.html

document.querySelector(".item")
来源：http://dali.jqgufenzy.top/Article/details/gtmxlxucee.html

[U101] JS：classList 操作
来源：http://dali.sweek.top/Article/details/gtzccskvwt.html

el.classList.toggle("active")
来源：http://dali.zycfv.cn/Article/details/gtohffdznq.html

[U102] JS：本地存储
来源：http://dali.wangdashe.top/Article/details/gtwropqeij.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.birdmap.top/Article/details/gtfsekyxnd.html

[U103] JS：定时器
来源：http://dali.shuidangran.top/Article/details/gtizuybkld.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xylfe.cn/Article/details/gtpmuctwuv.html

[U104] JS：防抖
来源：http://dali.ivvv.top/Article/details/gtmbjlugmb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtehfgfhfj.html

[U105] JS：节流
来源：http://dali.jianghu66.top/Article/details/gtsmnrxpyv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ydzc1.top/Article/details/gtspyixnuz.html

[U106] JS：日期格式化
来源：http://dali.hfpthk.cn/Article/details/gtqsqigrgc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.havefunace.top/Article/details/gtbjvdiyck.html

[U107] JS：数字千分位
来源：http://dali.0kj1m.cn/Article/details/gtvwgwiqbe.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ybcxt.top/Article/details/gtmdltndzu.html

[U108] JS：随机整数
来源：http://dali.sysykeji.top/Article/details/gtafheiids.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhongyouzk.top/Article/details/gtpanvbjif.html

[U109] JS：数组分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtwnzwcuoh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.wangshuangyany.cn/Article/details/gtfyzywaqv.html

[U110] JS：数组分块
来源：http://dali.sxryk.cn/Article/details/gtgsuwczhx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebmodwzy.html

[U111] JS：对象转 Map
来源：http://dali.daxiang520.top/Article/details/gttvghdhqw.html

new Map(Object.entries(obj))
来源：http://dali.cucudq.cn/Article/details/gttefgxmnz.html

[U112] JS：字符串补位
来源：http://dali.nanxinkj.top/Article/details/gtcldvlwvp.html

"7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gtuwkceuaf.html

[U113] JS：正则替换全部
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjttunwtz.html

s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtgsbdtmju.html

[U114] JS：JSON 深比较
来源：http://dali.yuanzhike.top/Article/details/gttbjolcug.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.vqdsnc.cn/Article/details/gtwuduuedd.html

[U115] JS：生成 UUID
来源：http://dali.pengpengdd.cyou/Article/details/gtbvznscrd.html

crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gtzrbalgie.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.smart0.xyz/Article/details/gtjdpxqfcu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xinyue.icu/Article/details/gtghqrynzt.html

[U117] JS：单元测试
来源：http://dali.hammf.cn/Article/details/gtaajsdlxy.html

npm i -D vitest;  npx vitest
来源：http://dali.jyoumei.cn/Article/details/gtvdctvvww.html

[U118] JS：开发服务器
来源：http://dali.chenzaomai.com/Article/details/gtspipcptf.html

npm i -D vite;  npx vite
来源：http://dali.iojbl.cn/Article/details/gthrdxzfyr.html

[U119] JS：生产构建
来源：http://dali.shanyushiyangtech.top/Article/details/gtskupmfez.html

npx vite build
来源：http://dali.feifeiyinyue.top/Article/details/gtsfyxjccb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xinyue.icu/Article/details/gtrpnyxfhj.html

import.meta.env.VITE_API_URL
来源：http://dali.jlsjyb.cn/Article/details/gthptpevyj.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtylezibbs.html

统计汇总
来源：http://dali.0kj1m.cn/Article/details/gtxiupysci.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtukpniquw.html

按语言统计（条）：
来源：http://dali.hfpthk.cn/Article/details/gtcljxqzuz.html

Python ......... 252
来源：http://dali.feifeiyinyue.top/Article/details/gtvpcoxnao.html

PHP ............ 252
来源：http://dali.yvedp.cn/Article/details/gtzknuhwhb.html

JavaScript ..... 252
来源：http://dali.xziqi.cn/Article/details/gtkddbujau.html

TypeScript ..... 212
来源：http://dali.pycfn.com/Article/details/gtaqarytdh.html

Java ........... 212
来源：http://dali.nanxuanxn.top/Article/details/gtlgqrxwax.html

Go ............. 212
来源：http://dali.snrcjt.cn/Article/details/gtqfikzkjq.html

Ruby ........... 212
来源：http://dali.jyoumei.cn/Article/details/gtcysqfmcs.html

C# ............. 212
来源：http://dali.c1oappe.top/Article/details/gtbxeauaiq.html

C .............. 30
来源：http://dali.chenlongwang.top/Article/details/gtitmjmcwr.html

C++ ............ 30
来源：http://dali.yangfankeji.com/Article/details/gtsqtsnuub.html

SQL ............ 90
来源：http://dali.hongshengwenyu.top/Article/details/gtqxtabtuc.html

Bash ........... 80
来源：http://dali.pycfn.com/Article/details/gtatlvqcop.html

Kotlin ......... 15
来源：http://dali.smart0.xyz/Article/details/gtnzjizylm.html

Swift .......... 15
来源：http://dali.pengpengdd.cyou/Article/details/gtottqidte.html

Lua ............ 10
来源：http://dali.yuxming.cn/Article/details/gtqciumbvx.html

Perl ........... 10
来源：http://dali.tanke756.top/Article/details/gtsjhwmpgc.html

Scala .......... 10
来源：http://dali.jqgfzy.top/Article/details/gtzqqwfvft.html

------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gtdkoffmsc.html

合计 ........... 2106 条
来源：http://dali.zhongyouzk.top/Article/details/gtufqkpxwm.html

按章节统计：
来源：http://dali.jqgufenzy.top/Article/details/gtrkblhadb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yuxming.cn/Article/details/gtxuamehpc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohkvtqzk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yangfankeji.com/Article/details/gtwwzqzmax.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmceeobxd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.gzhubu.top/Article/details/gtgjktgoqb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndolznew.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.bjfxy.top/Article/details/gtgghxqysr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.fengsongda.top/Article/details/gtbmnumsce.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gtsoumphqk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gaohongyu789.top/Article/details/gtwrctohug.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gtwtwgimvg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gttbokfkrh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gtgewfqzlp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jlsjyb.cn/Article/details/gtwmehuiiu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xinyue.icu/Article/details/gtjhmklsmt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gtmvtyhtpa.html

Q SQL 专题                              90
来源：http://dali.zhoulong.xyz/Article/details/gtnayvcajr.html

R Bash 专题                             80
来源：http://dali.quarkkingdee.top/Article/details/gtmyaikcwe.html

S C / C++ 专题                          60
来源：http://dali.yvedp.cn/Article/details/gtkahdjrad.html

T 其他语言补充                          60
来源：http://dali.bjfxy.top/Article/details/gtexiishao.html

U 高频实用片段                         120
来源：http://dali.aizwys.cn/Article/details/gtotunwvph.html

------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtxdyqebdn.html

合计                                  2106 条
来源：http://dali.birdmap.top/Article/details/gtmjwdjjeh.html

--------------------------------------------------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gtpugebuwn.html

使用提醒
来源：http://dali.snrcjt.cn/Article/details/gtimgykjpd.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtlpqphzbz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnqowyah.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yvedp.cn/Article/details/gtkfbblwji.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.dianchejie.cn/Article/details/gtdidjuohw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ydzc1.top/Article/details/gtajxsbinp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.nanxinkj.top/Article/details/gtomihocya.html

—— 文件结束 ——
来源：http://dali.zhongyouzk.top/Article/details/gtnpcxkmqx.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtprcxxlgx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.9152youxi.cn/Article/details/gtslewzlyb.html

Common Programming Examples Cheat Book
来源：http://dali.hongshengwenyu.top/Article/details/gtfggqfubt.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gticnhypkz.html

【收录内容】
来源：http://dali.haohaochexian.top/Article/details/gtlbvlnrya.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.nwbrower.top/Article/details/gtpiabpnyj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.ivvv.top/Article/details/gtqjzhyuam.html

SQL · Bash · C · C++
来源：http://dali.havefunace.top/Article/details/gthdhabknc.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hysaishi.cn/Article/details/gtxqddhfvb.html

【使用说明】
来源：http://dali.nanxinkj.top/Article/details/gtvegkoemw.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yuanzhike.top/Article/details/gtxvkloodm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yanxiufei.cn/Article/details/gtjzyquwoy.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hfpthk.cn/Article/details/gtywuwuble.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ybcxt.top/Article/details/gtjnntzzkz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.shanyushiyangtech.top/Article/details/gttmhmnimg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.pengpengdd.cyou/Article/details/gtemclbtdv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hfpthk.cn/Article/details/gtwvybqcpa.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yangfankeji.com/Article/details/gtixtqzclq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shangyingyoupin.top/Article/details/gtunjjggvk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shanyushiyangtech.top/Article/details/gtpojdyims.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.316326.xyz/Article/details/gtbeaspnqx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cashguo.top/Article/details/gtvdstsjxk.html

【文件统计】
来源：http://dali.cqqwz.cn/Article/details/gtufepytxy.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gogol.net.cn/Article/details/gtljzhqexs.html

--------------------------------------------------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqebbnaez.html

目  录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtluvlwlkr.html

--------------------------------------------------------------------------------
来源：http://dali.fengsongda.top/Article/details/gtkcpmwejy.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hnxiangtu.top/Article/details/gtwhexmuxs.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhoulong.xyz/Article/details/gtbtvhuqkx.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hysaishi.cn/Article/details/gtckivbvzu.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkumrfikw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.vqdsnc.cn/Article/details/gtbjhdobrl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtvnoxuwpf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtkliapqfw.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhengqikj.top/Article/details/gtfwqadybu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hysaishi.cn/Article/details/gtelazxkoq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ydzc1.top/Article/details/gtdcdepfyi.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gtwgvnibzx.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtyhanstdt.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gtjidflsai.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zycfv.cn/Article/details/gtgwknuelz.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.fzhhl.top/Article/details/gtownhozxy.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gtxtbxoqjm.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xziqi.cn/Article/details/gtcyfbglxo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsffpfsgk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtpdortgnc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shangyingyoupin.top/Article/details/gtusuwjbqv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.cashguo.top/Article/details/gtufznouqx.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtpvtnzjzw.html

A. 基础语法与类型
来源：http://dali.bjfxy.top/Article/details/gtyfrabrsp.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtvfnqoged.html

[A01] Hello World
来源：http://dali.fzhhl.top/Article/details/gtblskibxa.html

Py:   print("Hello, World!")
来源：http://dali.ybcxt.top/Article/details/gtjtpapcoo.html

PHP:  echo "Hello, World!";
来源：http://dali.havefunace.top/Article/details/gtqztbuokn.html

JS:   console.log("Hello, World!");
来源：http://dali.hfpthk.cn/Article/details/gthqeccwsw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jqgfzy.top/Article/details/gtupnknjzl.html

Java: System.out.println("Hello, World!");
来源：http://dali.yvedp.cn/Article/details/gtfitumvpw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yj202588.top/Article/details/gtusdfgstx.html

Ruby: puts "Hello, World!"
来源：http://dali.ivvv.top/Article/details/gtqpykswln.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.guowangkeji.top/Article/details/gtgvkysytc.html

[A02] 变量声明与赋值
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbsjikcr.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jlsjyb.cn/Article/details/gtzfkeywof.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jiagoushi.top/Article/details/gtwksdokmx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zdqjudy.top/Article/details/gteejqzoko.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhongyouzk.top/Article/details/gtqkbrbryv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.chenzaomai.com/Article/details/gtjkjnmrlo.html

Go:   name := "Alex"; age := 20
来源：http://dali.yj20258.top/Article/details/gtycdrmojd.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwiazneye.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.svipenyu.cn/Article/details/gtezmydpvz.html

[A03] 常量定义
来源：http://dali.fengsongda.top/Article/details/gtwregkcku.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hnqzz.top/Article/details/gtnlebxpxb.html

PHP:  const PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtyahiuawi.html

JS:   const PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtiirnrsed.html

TS:   const PI: number = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtfcunuocd.html

Java: static final double PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnlwmofov.html

Go:   const PI = 3.14159
来源：http://dali.haohaochexian.top/Article/details/gtuyumhrcn.html

Ruby: PI = 3.14159
来源：http://dali.redwolf501.top/Article/details/gtlkuioibo.html

C#:   const double PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtjivxlhzr.html

[A04] 判断变量类型
来源：http://dali.ydzc1.top/Article/details/gtkxuwxdrf.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhoulong.xyz/Article/details/gtfojbcuzf.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shzxlz.cn/Article/details/gtzhtsrkvg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhoulong.xyz/Article/details/gtiiizjaof.html

TS:   typeof x; x instanceof Date
来源：http://dali.smart0.xyz/Article/details/gtdkkekzbm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hnxiangtu.top/Article/details/gteydnnpmw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.9152youxi.cn/Article/details/gtymlmobtm.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jqgfzy.top/Article/details/gttgruemoj.html

C#:   x.GetType().Name; x is int
来源：http://dali.gogol.net.cn/Article/details/gtwdaefcvy.html

[A05] 整数除法与取模
来源：http://dali.hammf.cn/Article/details/gtjubfwdjd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yuanzhike.top/Article/details/gtuvmcntjj.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gthejuknxy.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.havefunace.top/Article/details/gtjeokupkd.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj202588.top/Article/details/gtggpekqqi.html

Java: 7 / 2; 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtgfvqqwow.html

Go:   7 / 2; 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gttrxsbzno.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.redwolf501.top/Article/details/gtacresfcw.html

C#:   7 / 2; 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gtlnsxvufu.html

[A06] 字符串转数字
来源：http://dali.yanxiufei.cn/Article/details/gtjrvbkrbs.html

Py:   int("42"); float("3.14")
来源：http://dali.zhengqikj.top/Article/details/gtwskjfwmx.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hfpthk.cn/Article/details/gtovtdptkz.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.pycfn.com/Article/details/gtjhzeyrnz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ivvv.top/Article/details/gtwmtebhox.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.gaohongyu789.top/Article/details/gtzdytugxo.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.cucudq.cn/Article/details/gtopbmnlej.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hysaishi.cn/Article/details/gtgdvaveqo.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jinqigufen.top/Article/details/gtwbzupyku.html

[A07] 数字转字符串
来源：http://dali.dashuyun.cn/Article/details/gtattialpc.html

Py:   str(42)
来源：http://dali.jinqigfzy.top/Article/details/gtigmztdjm.html

PHP:  (string) 42; strval(42)
来源：http://dali.nanxinkj.top/Article/details/gtmosjcqrr.html

JS:   String(42); (42).toString()
来源：http://dali.sufxvd.cn/Article/details/gtjjvcxdxs.html

TS:   String(42)
来源：http://dali.birdmap.top/Article/details/gtvktdcfwp.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.nanxinkj.top/Article/details/gtxvusiejr.html

Go:   strconv.Itoa(42)
来源：http://dali.nanxuanxn.top/Article/details/gtlilkocji.html

Ruby: 42.to_s
来源：http://dali.aizwys.cn/Article/details/gtdbowfkhs.html

C#:   42.ToString()
来源：http://dali.mhx1999.top/Article/details/gtezmhmuge.html

[A08] 取整与四舍五入
来源：http://dali.guowangkeji.top/Article/details/gtxriezlhu.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gtnnfcjtqa.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ydzc1.top/Article/details/gttzvvnhrr.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.9152youxi.cn/Article/details/gtwijynfjg.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.daxiang520.top/Article/details/gtlpvuvhsc.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.chenjidiqi.icu/Article/details/gtqcomxuuz.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yj20258.top/Article/details/gthpnoenua.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yj20258888.top/Article/details/gtczfgcjdz.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.shangyingyoupin.top/Article/details/gtencyavey.html

[A09] 绝对值与最大最小值
来源：http://dali.feifeiyinyue.top/Article/details/gtwkjonfyf.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gthweepgoq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtlyknhzjk.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gtioplvusa.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gtpnnpwrnh.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yvedp.cn/Article/details/gtiwtcpapc.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yvedp.cn/Article/details/gtlbopfjze.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.316326.xyz/Article/details/gtnaoioegq.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtgoltxizn.html

[A10] 生成随机数
来源：http://dali.sweek.top/Article/details/gtgiizosxl.html

Py:   import random; random.randint(1, 100)
来源：http://dali.quarkkingdee.top/Article/details/gtowfxymaz.html

PHP:  random_int(1, 100);
来源：http://dali.zhengqikj.top/Article/details/gtuhpsdbpg.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.nanxinkj.top/Article/details/gtwsscmnih.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhixingplan.top/Article/details/gtgccekigv.html

Java: new Random().nextInt(100) + 1
来源：http://dali.ivvv.top/Article/details/gtphnyvtrn.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.cashguo.top/Article/details/gtmhyghvqq.html

Ruby: rand(1..100)
来源：http://dali.316326.xyz/Article/details/gtfumiykzg.html

C#:   new Random().Next(1, 101)
来源：http://dali.fzhhl.top/Article/details/gtdeqjkwmo.html

[A11] 条件表达式（三元）
来源：http://dali.gzhubu.top/Article/details/gttcmccjod.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.aibaodan.cn/Article/details/gtpsizkior.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yueranfly.top/Article/details/gtqjnugsam.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.xuetiantiany.cn/Article/details/gtqtlkrrfh.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.iojbl.cn/Article/details/gtojrmokgz.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.fengsongda.top/Article/details/gtliynyvod.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.redwolf501.top/Article/details/gtxijyfzty.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jinqigfzy.top/Article/details/gtbzbgcapj.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jianghu66.top/Article/details/gtqsjlotwy.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhongyouzk.top/Article/details/gtnwqlmihm.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhiwuduotai.top/Article/details/gtzvefaxfn.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yuanzhike.top/Article/details/gtsweuaseg.html

JS:   `Hello, ${name}!`
来源：http://dali.jlsjyb.cn/Article/details/gtljylfdvb.html

TS:   `Hello, ${name}!`
来源：http://dali.guannengcc.top/Article/details/gtjdndstgx.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.aizwys.cn/Article/details/gtaecmmbdi.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yonumen.top/Article/details/gtltnudtla.html

Ruby: "Hello, #{name}!"
来源：http://dali.daria6918.cn/Article/details/gthuxtclqy.html

C#:   $"Hello, {name}!"
来源：http://dali.meibo888.top/Article/details/gtzcbvebbf.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.tanke756.top/Article/details/gtxrjwkbkb.html

Py:   "第一行\n第二行"
来源：http://dali.dianchejie.cn/Article/details/gtmgbztlvq.html

PHP:  "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gtgkgsamkx.html

JS:   "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gthdazeduo.html

TS:   "第一行\n第二行"
来源：http://dali.daxiang520.top/Article/details/gtcmvxedba.html

Java: "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gtlixkjwht.html

Go:   "第一行\n第二行"
来源：http://dali.fzhhl.top/Article/details/gtkibwlcjq.html

Ruby: "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gtzgmudecr.html

C#:   "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gtkanluibf.html


<!-- 参考信息 -->