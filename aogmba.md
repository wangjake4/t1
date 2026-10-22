代发 wailian999

[U81] JS：初始化项目
来源：http://dali.nanxuanxn.top/Article/details/gtwnumgkjw.html

npm init -y;  npm i express
来源：http://dali.cqqwz.cn/Article/details/gtrfvdpzsx.html

[U82] JS：package.json 脚本
来源：http://dali.nanxuanxn.top/Article/details/gtkgrpobqy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.9152youxi.cn/Article/details/gtfpshhxkh.html

[U83] JS：ES Module 导入导出
来源：http://dali.zycfv.cn/Article/details/gtkpojqquj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yonumen.top/Article/details/gtcftllmrf.html

[U84] JS：CommonJS 写法
来源：http://dali.yuxming.cn/Article/details/gttkhzuwbt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.wangdashe.top/Article/details/gtjqdetzcc.html

[U85] JS：可选链
来源：http://dali.cqqwz.cn/Article/details/gtvqwlsrhe.html

a?.b?.c
来源：http://dali.shzxlz.cn/Article/details/gtkklishyw.html

[U86] JS：空值合并
来源：http://dali.chenzaomai.com/Article/details/gtxxptcxfb.html

a ?? b
来源：http://dali.snrcjt.cn/Article/details/gtunxgeopk.html

[U87] JS：解构默认值
来源：http://dali.zhongyouzk.top/Article/details/gtfpjssofq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ybcxt.top/Article/details/gtmfkfzhfx.html

[U88] JS：对象展开合并
来源：http://dali.wangshuangyany.cn/Article/details/gthumryscm.html

{ ...a, ...b }
来源：http://dali.zhongyouzk.top/Article/details/gtlxepgfkr.html

[U89] JS：数组去重
来源：http://dali.wangdashe.top/Article/details/gtsmpoinrn.html

[...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gtdnrvbbvo.html

[U90] JS：数字数组排序
来源：http://dali.wangdashe.top/Article/details/gtyultvvvb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gthxhwnopu.html

[U91] JS：对象键值遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrfzsfxp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.aibaodan.cn/Article/details/gtgzrowfru.html

[U92] JS：深拷贝
来源：http://dali.pycfn.com/Article/details/gtnbdxzpgb.html

structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gtfcpbtaeu.html

[U93] JS：模板字符串
来源：http://dali.sweek.top/Article/details/gtlfwlfldq.html

`共 ${n} 条`
来源：http://dali.havefunace.top/Article/details/gtywpdeosm.html

[U94] JS：箭头函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjowymzqs.html

const double = x => x * 2;
来源：http://dali.ppjwa.cn/Article/details/gtukuqyomh.html

[U95] JS：Promise 包装
来源：http://dali.guannengcc.top/Article/details/gtywobxfvl.html

new Promise((resolve, reject) => {})
来源：http://dali.gaohongyu789.top/Article/details/gtwujzomhv.html

[U96] JS：async/await 与异常
来源：http://dali.feifeiyinyue.top/Article/details/gtdshjxxfu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtpltnqnrg.html

[U97] JS：并发请求
来源：http://dali.yj20258888.top/Article/details/gttwiecxxi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtgrtyfhpz.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtxidgmjro.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.quarkkingdee.top/Article/details/gtxzvfsvue.html

[U99] JS：事件监听
来源：http://dali.sxryk.cn/Article/details/gtzaycwimy.html

el.addEventListener("click", e => {})
来源：http://dali.fengsongda.top/Article/details/gtnmmzukez.html

[U100] JS：DOM 查询
来源：http://dali.cheryme.top/Article/details/gtrdrqoevv.html

document.querySelector(".item")
来源：http://dali.svipenyu.cn/Article/details/gtfklqfrjj.html

[U101] JS：classList 操作
来源：http://dali.meibo888.top/Article/details/gtbdbsxjmy.html

el.classList.toggle("active")
来源：http://dali.wangshuangyany.cn/Article/details/gtgsfmiwxn.html

[U102] JS：本地存储
来源：http://dali.vqdsnc.cn/Article/details/gtoyovotup.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.haohaochexian.top/Article/details/gtagbuwloj.html

[U103] JS：定时器
来源：http://dali.hnxiangtu.top/Article/details/gtmryrnrmi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yanxiufei.cn/Article/details/gtwamiztka.html

[U104] JS：防抖
来源：http://dali.shuidangran.top/Article/details/gttuowhogc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtmsvlurxw.html

[U105] JS：节流
来源：http://dali.vqdsnc.cn/Article/details/gtggmydvzo.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cdnleiting.top/Article/details/gtkwoaknpe.html

[U106] JS：日期格式化
来源：http://dali.zhixingplan.top/Article/details/gtutjtceyf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.sxryk.cn/Article/details/gtmvdgbeuo.html

[U107] JS：数字千分位
来源：http://dali.jinqigufen.top/Article/details/gtanhwnwmu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.andypj.xyz/Article/details/gtoxozeuxv.html

[U108] JS：随机整数
来源：http://dali.shanyushiyangtech.top/Article/details/gthqpdisml.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.meibo888.top/Article/details/gtrdwqqpvn.html

[U109] JS：数组分组
来源：http://dali.chenzaomai.com/Article/details/gtusgdahts.html

Object.groupBy(arr, x => x.type)
来源：http://dali.aizwys.cn/Article/details/gtfnanhtgm.html

[U110] JS：数组分块
来源：http://dali.iojbl.cn/Article/details/gtszrbnxir.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hfpthk.cn/Article/details/gtawttpzsb.html

[U111] JS：对象转 Map
来源：http://dali.0kj1m.cn/Article/details/gtwaoillkq.html

new Map(Object.entries(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gtcdqsbpaf.html

[U112] JS：字符串补位
来源：http://dali.pengpengdd.cyou/Article/details/gtevfdqbfx.html

"7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gteauwjfyp.html

[U113] JS：正则替换全部
来源：http://dali.cheryme.top/Article/details/gtblvbgfzk.html

s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtpsfzfkdc.html

[U114] JS：JSON 深比较
来源：http://dali.xziqi.cn/Article/details/gtpcvgzkik.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aizwys.cn/Article/details/gtmwdtdzdi.html

[U115] JS：生成 UUID
来源：http://dali.yuanzhike.top/Article/details/gtwtanmbnf.html

crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gtrgukueug.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.wangshuangyany.cn/Article/details/gtqvzwjgdp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cdnleiting.top/Article/details/gtafyegcww.html

[U117] JS：单元测试
来源：http://dali.yuanzhike.top/Article/details/gtdzvcbsrg.html

npm i -D vitest;  npx vitest
来源：http://dali.yuanzhike.top/Article/details/gtsjtcvviu.html

[U118] JS：开发服务器
来源：http://dali.yonumen.top/Article/details/gtszpkmhnq.html

npm i -D vite;  npx vite
来源：http://dali.jqgfzy.top/Article/details/gthzspoecf.html

[U119] JS：生产构建
来源：http://dali.yanxiufei.cn/Article/details/gtkyfvkwrw.html

npx vite build
来源：http://dali.shzxlz.cn/Article/details/gtqxnfjeot.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.mhx1999.top/Article/details/gtfpfqyjdn.html

import.meta.env.VITE_API_URL
来源：http://dali.chenzaomai.com/Article/details/gtjpzlrvcw.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtpytjgalz.html

统计汇总
来源：http://dali.aibaodan.cn/Article/details/gtokeieyos.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtieweuftu.html

按语言统计（条）：
来源：http://dali.smart0.xyz/Article/details/gtlypbwbhn.html

Python ......... 252
来源：http://dali.316326.xyz/Article/details/gttprksdgl.html

PHP ............ 252
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmhlveub.html

JavaScript ..... 252
来源：http://dali.zycfv.cn/Article/details/gtublrjngm.html

TypeScript ..... 212
来源：http://dali.ehwqpu.com/Article/details/gtuevmydfc.html

Java ........... 212
来源：http://dali.xylfe.cn/Article/details/gtognfityz.html

Go ............. 212
来源：http://dali.tianlin.xyz/Article/details/gtxprpkjnv.html

Ruby ........... 212
来源：http://dali.ybcxt.top/Article/details/gtshsterdk.html

C# ............. 212
来源：http://dali.yangfankeji.com/Article/details/gtofvseyzc.html

C .............. 30
来源：http://dali.0kj1m.cn/Article/details/gtjlhhbwhb.html

C++ ............ 30
来源：http://dali.ydzc1.top/Article/details/gtrupmvlsz.html

SQL ............ 90
来源：http://dali.gogol.net.cn/Article/details/gtpfmdwawm.html

Bash ........... 80
来源：http://dali.gaohongyu789.top/Article/details/gtremdhopc.html

Kotlin ......... 15
来源：http://dali.yueranfly.top/Article/details/gtbrayfcei.html

Swift .......... 15
来源：http://dali.daxiang520.top/Article/details/gtmvrnqmhm.html

Lua ............ 10
来源：http://dali.jinghuilouyu.cn/Article/details/gtndztxhvx.html

Perl ........... 10
来源：http://dali.shuidangran.top/Article/details/gtibojthyp.html

Scala .......... 10
来源：http://dali.birdmap.top/Article/details/gtjdvkypki.html

------------------------------------
来源：http://dali.birdmap.top/Article/details/gtkufwedkf.html

合计 ........... 2106 条
来源：http://dali.316326.xyz/Article/details/gtlrepolgk.html

按章节统计：
来源：http://dali.yuanzhike.top/Article/details/gtlfwgfcpj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jiagoushi.top/Article/details/gtcjoleaib.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gtradxlyyr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqnpeyaz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yangfankeji.com/Article/details/gtacvaqtex.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.iojbl.cn/Article/details/gtklqggsfd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hnxiangtu.top/Article/details/gtvmlyhhyj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gtttruzaxg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzgmgjay.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gtsmxmeryd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.guannengcc.top/Article/details/gtcabiidfv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gtukrjrvsi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gthrjgpymw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gtpnqdaopi.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.sysykeji.top/Article/details/gtxqenhutj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cheryme.top/Article/details/gtqokynxsq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhiwuduotai.top/Article/details/gtkaenxglo.html

Q SQL 专题                              90
来源：http://dali.pycfn.com/Article/details/gtxkxdbkdk.html

R Bash 专题                             80
来源：http://dali.316326.xyz/Article/details/gtcxezaama.html

S C / C++ 专题                          60
来源：http://dali.cqqwz.cn/Article/details/gtftisospb.html

T 其他语言补充                          60
来源：http://dali.chenjidiqi.icu/Article/details/gthzxufkyj.html

U 高频实用片段                         120
来源：http://dali.xziqi.cn/Article/details/gtdozgcaag.html

------------------------------------
来源：http://dali.aizwys.cn/Article/details/gtwcyqylbo.html

合计                                  2106 条
来源：http://dali.yongpay.top/Article/details/gtefgtxjdt.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258.top/Article/details/gtksimhhrw.html

使用提醒
来源：http://dali.zhixingplan.top/Article/details/gtqfrtbbmu.html

--------------------------------------------------------------------------------
来源：http://dali.ybcxt.top/Article/details/gtfygtdmkx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.nanxuanxn.top/Article/details/gtqqpukein.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.fengsongda.top/Article/details/gtpspzggky.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.mhx1999.top/Article/details/gtgjvkgien.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.haohaochexian.top/Article/details/gtqrfhusth.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xinyue.icu/Article/details/gtswldzogh.html

—— 文件结束 ——
来源：http://dali.ehwqpu.com/Article/details/gtaezkhalk.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtqpefntuf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.chenjidiqi.icu/Article/details/gtkflnlhjm.html

Common Programming Examples Cheat Book
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcevukrz.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtpeskqmzg.html

【收录内容】
来源：http://dali.hongshengwenyu.top/Article/details/gtjmrhosld.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.birdmap.top/Article/details/gtzulsobyd.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.guowangkeji.top/Article/details/gtjncylbnm.html

SQL · Bash · C · C++
来源：http://dali.tian-w.cn/Article/details/gtlxdeifkq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.aibaodan.cn/Article/details/gttuayairp.html

【使用说明】
来源：http://dali.dianchejie.cn/Article/details/gtniwkndgb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shzxlz.cn/Article/details/gtzreodrct.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.gaohongyu789.top/Article/details/gtrqxgnlgd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ydzc1.top/Article/details/gtcyqdlmln.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.316326.xyz/Article/details/gtajhuoxgx.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.tanke756.top/Article/details/gtfnqzwkpk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cqqwz.cn/Article/details/gttiwxcukj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.guowangkeji.top/Article/details/gtcpuqpjbu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhengqikj.top/Article/details/gtkfnkbfpd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhongyouzk.top/Article/details/gttmlxoaly.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xinyue.icu/Article/details/gtihtcejwp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ydzc1.top/Article/details/gtjfcdomyo.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.chenlongwang.top/Article/details/gtqytgccht.html

【文件统计】
来源：http://dali.kuanghao11.cn/Article/details/gtqxyggtxt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xziqi.cn/Article/details/gtroufljlw.html

--------------------------------------------------------------------------------
来源：http://dali.daxiang520.top/Article/details/gtexkkwikf.html

目  录
来源：http://dali.jlsjyb.cn/Article/details/gtxtrmyfeb.html

--------------------------------------------------------------------------------
来源：http://dali.daria6918.cn/Article/details/gtlinzxjda.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hywenlv.cn/Article/details/gtpkpevltu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.nwbrower.top/Article/details/gtqvnjgapi.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.daria6918.cn/Article/details/gtefovbeao.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.cucudq.cn/Article/details/gthgzydwpl.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvblhoche.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhongyouzk.top/Article/details/gtllzmwues.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jinqigufen.top/Article/details/gtuzooxqww.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.tian-w.cn/Article/details/gtyzxwqnxo.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gttapytxtk.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrttgksx.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhengqikj.top/Article/details/gtiqhdcsyz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.meibo888.top/Article/details/gtykbtrrgk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gtaqppujae.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shzxlz.cn/Article/details/gtcddeqiaj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.aizwys.cn/Article/details/gtrdvpbdml.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.cdnleiting.top/Article/details/gtfoqwaimn.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jiagoushi.top/Article/details/gtntpxkewe.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.nanxuanxn.top/Article/details/gtbdqbahjx.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.c1oappe.top/Article/details/gtfzycyymt.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuanzhike.top/Article/details/gtplqmewdk.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.smart0.xyz/Article/details/gtezdepiph.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtwhrxdtuu.html

A. 基础语法与类型
来源：http://dali.cucudq.cn/Article/details/gtdebqqjzb.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtpfgoqzbl.html

[A01] Hello World
来源：http://dali.wangdashe.top/Article/details/gtrrhyloln.html

Py:   print("Hello, World!")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypnzpmhc.html

PHP:  echo "Hello, World!";
来源：http://dali.nanxinkj.top/Article/details/gtkiqckgkb.html

JS:   console.log("Hello, World!");
来源：http://dali.hnqzz.top/Article/details/gtnowtqpxj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.quarkkingdee.top/Article/details/gtykjbnvwi.html

Java: System.out.println("Hello, World!");
来源：http://dali.nwbrower.top/Article/details/gtyfsuwnoa.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.pengpengdd.cyou/Article/details/gtkzsmzqen.html

Ruby: puts "Hello, World!"
来源：http://dali.shangyingyoupin.top/Article/details/gtgphabfbl.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.shzxlz.cn/Article/details/gtwfsgrfbi.html

[A02] 变量声明与赋值
来源：http://dali.gotoacloud.top/Article/details/gtmsljubvl.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ehwqpu.com/Article/details/gtzthaaetq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.mhx1999.top/Article/details/gtqifesvgi.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xziqi.cn/Article/details/gtorsrbdxx.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.tanke756.top/Article/details/gtjvfkqnfx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.mhx1999.top/Article/details/gtdzurdhqj.html

Go:   name := "Alex"; age := 20
来源：http://dali.yj202588.top/Article/details/gtpxnfcuiz.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yj20258888.top/Article/details/gtemllirlu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.vqdsnc.cn/Article/details/gtmtmtwhok.html

[A03] 常量定义
来源：http://dali.snrcjt.cn/Article/details/gtpbihcech.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yonumen.top/Article/details/gtmpyipooj.html

PHP:  const PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtsahwlwyr.html

JS:   const PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gthikduiap.html

TS:   const PI: number = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtvhowiejo.html

Java: static final double PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtbhdkfzkw.html

Go:   const PI = 3.14159
来源：http://dali.sysykeji.top/Article/details/gtfpmawsjh.html

Ruby: PI = 3.14159
来源：http://dali.shuidangran.top/Article/details/gtziliqkuz.html

C#:   const double PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtbivkrcoc.html

[A04] 判断变量类型
来源：http://dali.ivvv.top/Article/details/gtfjmkqbcd.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hammf.cn/Article/details/gtyegcdhay.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cqqwz.cn/Article/details/gtgviswqbk.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yueranfly.top/Article/details/gtolwsilsq.html

TS:   typeof x; x instanceof Date
来源：http://dali.yj20258888.top/Article/details/gtczuwuwam.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.aibaodan.cn/Article/details/gtwkwfhakf.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jinghuilouyu.cn/Article/details/gtivzuromj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.gaohongyu789.top/Article/details/gththuiuaa.html

C#:   x.GetType().Name; x is int
来源：http://dali.birdmap.top/Article/details/gtezfbfipt.html

[A05] 整数除法与取模
来源：http://dali.tianlin.xyz/Article/details/gtrrulufum.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.guowangkeji.top/Article/details/gtmlchrhnn.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.cucudq.cn/Article/details/gtgzlqnkwd.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gtowfiazcz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gtcylclizo.html

Java: 7 / 2; 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknwyneko.html

Go:   7 / 2; 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtmqxzgjtq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gtdupyciby.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gttretmipk.html

[A06] 字符串转数字
来源：http://dali.xinyue.icu/Article/details/gtdprrzvwn.html

Py:   int("42"); float("3.14")
来源：http://dali.aibaodan.cn/Article/details/gtqnfuevqx.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.tanke756.top/Article/details/gtujnaxgym.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.sxryk.cn/Article/details/gtpktnvgrl.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yj20258888.top/Article/details/gtlegwkqpo.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.daxiang520.top/Article/details/gtorbcuptp.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.bjfxy.top/Article/details/gtkpctobly.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.xinyue.icu/Article/details/gtnphaluwi.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.feifeiyinyue.top/Article/details/gtneovmbue.html

[A07] 数字转字符串
来源：http://dali.shuidangran.top/Article/details/gtmfubdplh.html

Py:   str(42)
来源：http://dali.zhengqikj.top/Article/details/gtpxutnuba.html

PHP:  (string) 42; strval(42)
来源：http://dali.yongpay.top/Article/details/gtkpiglako.html

JS:   String(42); (42).toString()
来源：http://dali.yueranfly.top/Article/details/gtggeimpck.html

TS:   String(42)
来源：http://dali.bjfxy.top/Article/details/gtelxmlikg.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.cheryme.top/Article/details/gtoollbkdm.html

Go:   strconv.Itoa(42)
来源：http://dali.yj20258.top/Article/details/gtbanqthjq.html

Ruby: 42.to_s
来源：http://dali.fengsongda.top/Article/details/gthszrwodi.html

C#:   42.ToString()
来源：http://dali.feifeiyinyue.top/Article/details/gtnxxpagjg.html

[A08] 取整与四舍五入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqosoxjuo.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gtpqrkqpde.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ehwqpu.com/Article/details/gtzfkgqafk.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jiagoushi.top/Article/details/gtcztymijb.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.chenzaomai.com/Article/details/gtbkiuwiex.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.smart0.xyz/Article/details/gtzsthekss.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gtzgyffjie.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhongyouzk.top/Article/details/gtnwlhhbon.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jinqigfzy.top/Article/details/gtkxnxfois.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gtvorpgvmi.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gtabqtejqg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gtijigtfdp.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gtmuencqxb.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gtxzvozfqp.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtckezevzs.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jyoumei.cn/Article/details/gtedefvkwk.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yuxming.cn/Article/details/gtasjpkvtt.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gtalgokqab.html

[A10] 生成随机数
来源：http://dali.jyoumei.cn/Article/details/gtxsyfbhzb.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yj20258888.top/Article/details/gtmrzffvxy.html

PHP:  random_int(1, 100);
来源：http://dali.yj202588.top/Article/details/gtjseofmgw.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhwzoqpi.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.quarkkingdee.top/Article/details/gtvwphwbwg.html

Java: new Random().nextInt(100) + 1
来源：http://dali.nwbrower.top/Article/details/gtefqylhoz.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zdqjudy.top/Article/details/gtfumrshak.html

Ruby: rand(1..100)
来源：http://dali.pengpengdd.cyou/Article/details/gtitdxqkvz.html

C#:   new Random().Next(1, 101)
来源：http://dali.hongshengwenyu.top/Article/details/gtksizsbky.html

[A11] 条件表达式（三元）
来源：http://dali.jinqigfzy.top/Article/details/gtjjmertzu.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtucujilux.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohycopeh.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gttwdibimy.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.ehwqpu.com/Article/details/gtsglnyrbi.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhiwuduotai.top/Article/details/gtcvryjcfx.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrkrdbmpd.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.pycfn.com/Article/details/gtldiqihvw.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.iojbl.cn/Article/details/gtddxpflcm.html

[A12] 字符串插值 / 格式化
来源：http://dali.iojbl.cn/Article/details/gtxjwucyzx.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.mhx1999.top/Article/details/gtcbdoxdei.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yongpay.top/Article/details/gthyonqbdu.html

JS:   `Hello, ${name}!`
来源：http://dali.wangdashe.top/Article/details/gtgxgtwypb.html

TS:   `Hello, ${name}!`
来源：http://dali.haohaochexian.top/Article/details/gtloqyeeqw.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xuanzx.com/Article/details/gtsqafgphg.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.haohaochexian.top/Article/details/gtmgbmjkxq.html

Ruby: "Hello, #{name}!"
来源：http://dali.yueranfly.top/Article/details/gtkdufqmsy.html

C#:   $"Hello, {name}!"
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgjclkwo.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.pycfn.com/Article/details/gtyafbspkt.html

Py:   "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gtjhrxqvnb.html

PHP:  "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gtsmihlgsz.html

JS:   "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gtucjbamiv.html

TS:   "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgimaahut.html


<!-- 参考信息 -->