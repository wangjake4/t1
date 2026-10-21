代发 wailian999

[U83] JS：ES Module 导入导出
来源：http://dali.guowangkeji.top/Article/details/gtxfsfpswb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.guannengcc.top/Article/details/gtykcapgdf.html

[U84] JS：CommonJS 写法
来源：http://dali.9152youxi.cn/Article/details/gtkwgmdknj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hysaishi.cn/Article/details/gtaetgbqhi.html

[U85] JS：可选链
来源：http://dali.wangshuangyany.cn/Article/details/gtzugdycdc.html

a?.b?.c
来源：http://dali.shuidangran.top/Article/details/gtrmdmhffa.html

[U86] JS：空值合并
来源：http://dali.zhixingplan.top/Article/details/gtoxgxrcjp.html

a ?? b
来源：http://dali.guowangkeji.top/Article/details/gtdlzubrmc.html

[U87] JS：解构默认值
来源：http://dali.zhixingplan.top/Article/details/gthvtoemdw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yj20258.top/Article/details/gtzbmcowcj.html

[U88] JS：对象展开合并
来源：http://dali.nanxuanxn.top/Article/details/gttcawuwro.html

{ ...a, ...b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvinrsklv.html

[U89] JS：数组去重
来源：http://dali.andypj.xyz/Article/details/gtnzmkttvb.html

[...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gtswjkqkyw.html

[U90] JS：数字数组排序
来源：http://dali.chenlongwang.top/Article/details/gtymezhelf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtkgbbxtot.html

[U91] JS：对象键值遍历
来源：http://dali.guannengcc.top/Article/details/gtunijtllk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yj20258888.top/Article/details/gtbaldymqx.html

[U92] JS：深拷贝
来源：http://dali.cucudq.cn/Article/details/gtnrdycico.html

structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtmlqswmci.html

[U93] JS：模板字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtelijnvgu.html

`共 ${n} 条`
来源：http://dali.smart0.xyz/Article/details/gtmbtbucyv.html

[U94] JS：箭头函数
来源：http://dali.ehwqpu.com/Article/details/gtffclvkyo.html

const double = x => x * 2;
来源：http://dali.redwolf501.top/Article/details/gtvzpeimyz.html

[U95] JS：Promise 包装
来源：http://dali.xziqi.cn/Article/details/gtmvrxsqaq.html

new Promise((resolve, reject) => {})
来源：http://dali.shzxlz.cn/Article/details/gtksztwjfj.html

[U96] JS：async/await 与异常
来源：http://dali.chenlongwang.top/Article/details/gthzemgqaf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gtskapxqqq.html

[U97] JS：并发请求
来源：http://dali.zdqjudy.top/Article/details/gtbvqemyvi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gthcxouyqg.html

[U98] JS：fetch 带 JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxaigfxc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.haohaochexian.top/Article/details/gtfsulcdkv.html

[U99] JS：事件监听
来源：http://dali.tian-w.cn/Article/details/gtcugrgrjr.html

el.addEventListener("click", e => {})
来源：http://dali.sweek.top/Article/details/gtrwcymgfe.html

[U100] JS：DOM 查询
来源：http://dali.gzhubu.top/Article/details/gtqdaktkcb.html

document.querySelector(".item")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcavivkhh.html

[U101] JS：classList 操作
来源：http://dali.yanxiufei.cn/Article/details/gtxtlliswe.html

el.classList.toggle("active")
来源：http://dali.yj20258888.top/Article/details/gtpzyjsxvq.html

[U102] JS：本地存储
来源：http://dali.zhixingplan.top/Article/details/gtttpcgnrf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.snrcjt.cn/Article/details/gtxhgltkrv.html

[U103] JS：定时器
来源：http://dali.fengsongda.top/Article/details/gtamvgzjfz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cashguo.top/Article/details/gtzuoxekzw.html

[U104] JS：防抖
来源：http://dali.pengpengdd.cyou/Article/details/gtpvtfrnbx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gtwyhqwpzd.html

[U105] JS：节流
来源：http://dali.jinqigfzy.top/Article/details/gtrgltesbo.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.meibo888.top/Article/details/gtnpvaumpp.html

[U106] JS：日期格式化
来源：http://dali.yonumen.top/Article/details/gterfvdhmx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cqqwz.cn/Article/details/gtutdkzztu.html

[U107] JS：数字千分位
来源：http://dali.daria6918.cn/Article/details/gtygswxnlf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnajsfkk.html

[U108] JS：随机整数
来源：http://dali.zhixingplan.top/Article/details/gtsrrfszqk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shangyingyoupin.top/Article/details/gtgckkmwpw.html

[U109] JS：数组分组
来源：http://dali.daxiang520.top/Article/details/gtjuszsalv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zdqjudy.top/Article/details/gtoylmohyj.html

[U110] JS：数组分块
来源：http://dali.hfpthk.cn/Article/details/gtffdcjiyc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.fengsongda.top/Article/details/gtfffnjfkc.html

[U111] JS：对象转 Map
来源：http://dali.zhiwuduotai.top/Article/details/gtrvafvmnd.html

new Map(Object.entries(obj))
来源：http://dali.yanxiufei.cn/Article/details/gtylkujwam.html

[U112] JS：字符串补位
来源：http://dali.zhoulong.xyz/Article/details/gthlbcohhq.html

"7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gthavhqvif.html

[U113] JS：正则替换全部
来源：http://dali.zhiwuduotai.top/Article/details/gtvavigaxr.html

s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtmcffqrgt.html

[U114] JS：JSON 深比较
来源：http://dali.9152youxi.cn/Article/details/gtlfolrvcf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jiagoushi.top/Article/details/gtmvvvrtdf.html

[U115] JS：生成 UUID
来源：http://dali.ydzc1.top/Article/details/gtjlwyhmsf.html

crypto.randomUUID()
来源：http://dali.nanxuanxn.top/Article/details/gtumzyknkk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shuidangran.top/Article/details/gtbcwvlqid.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yongpay.top/Article/details/gtsdvcxojk.html

[U117] JS：单元测试
来源：http://dali.redwolf501.top/Article/details/gtowrtxofe.html

npm i -D vitest;  npx vitest
来源：http://dali.xziqi.cn/Article/details/gttwfqooup.html

[U118] JS：开发服务器
来源：http://dali.yj20258.top/Article/details/gtasxcnqge.html

npm i -D vite;  npx vite
来源：http://dali.zycfv.cn/Article/details/gtcmzmjdqd.html

[U119] JS：生产构建
来源：http://dali.dashuyun.cn/Article/details/gtldajwgyy.html

npx vite build
来源：http://dali.quarkkingdee.top/Article/details/gttyqxiari.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.wangdashe.top/Article/details/gtehvafxol.html

import.meta.env.VITE_API_URL
来源：http://dali.chenzaomai.com/Article/details/gtrqpximkp.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtqtrvmtvw.html

统计汇总
来源：http://dali.shuidangran.top/Article/details/gtavxfcnpa.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gteoqxfjuq.html

按语言统计（条）：
来源：http://dali.hongshengwenyu.top/Article/details/gteewtzemx.html

Python ......... 252
来源：http://dali.ivvv.top/Article/details/gtaceehbmh.html

PHP ............ 252
来源：http://dali.tian-w.cn/Article/details/gthroubhqo.html

JavaScript ..... 252
来源：http://dali.316326.xyz/Article/details/gtvxfcoqja.html

TypeScript ..... 212
来源：http://dali.smart0.xyz/Article/details/gtyzzfwcbw.html

Java ........... 212
来源：http://dali.kuanghao11.cn/Article/details/gtapjtoyje.html

Go ............. 212
来源：http://dali.ivvv.top/Article/details/gtgawkblnz.html

Ruby ........... 212
来源：http://dali.xylfe.cn/Article/details/gtsjncsbki.html

C# ............. 212
来源：http://dali.yangfankeji.com/Article/details/gthondtsjy.html

C .............. 30
来源：http://dali.hysaishi.cn/Article/details/gtatbykzuo.html

C++ ............ 30
来源：http://dali.ydzc1.top/Article/details/gtwyymccyx.html

SQL ............ 90
来源：http://dali.chenjidiqi.icu/Article/details/gtsonnjotw.html

Bash ........... 80
来源：http://dali.ppjwa.cn/Article/details/gtyoedxxus.html

Kotlin ......... 15
来源：http://dali.sweek.top/Article/details/gtlydksbpw.html

Swift .......... 15
来源：http://dali.jiagoushi.top/Article/details/gtuksaamhm.html

Lua ............ 10
来源：http://dali.ppjwa.cn/Article/details/gtuxrdckwk.html

Perl ........... 10
来源：http://dali.mhx1999.top/Article/details/gtzszuiceq.html

Scala .......... 10
来源：http://dali.haohaochexian.top/Article/details/gtmhbqymry.html

------------------------------------
来源：http://dali.cucudq.cn/Article/details/gtahsjdeov.html

合计 ........... 2106 条
来源：http://dali.0kj1m.cn/Article/details/gtyclwveht.html

按章节统计：
来源：http://dali.yj202588.top/Article/details/gtserkunjm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hongshengwenyu.top/Article/details/gtmqosdjys.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.snrcjt.cn/Article/details/gtmkzeouhp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gtbcmdgciw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zdqjudy.top/Article/details/gthhrnwrwh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hysaishi.cn/Article/details/gtqboqlflx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.iojbl.cn/Article/details/gtggvirgoy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.feifeiyinyue.top/Article/details/gtbltzxcpc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cashguo.top/Article/details/gtbppavukm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gthxyukese.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cdnleiting.top/Article/details/gtqozfyutc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gtntioxrst.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gtozvrajmj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gtmuaowemi.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.daxiang520.top/Article/details/gtkkghawdb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ywan-chungtsiang.top/Article/details/gtspkvhkno.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.iojbl.cn/Article/details/gtftdtbydx.html

Q SQL 专题                              90
来源：http://dali.sufxvd.cn/Article/details/gtpuzbfiwz.html

R Bash 专题                             80
来源：http://dali.iojbl.cn/Article/details/gtuvjaeool.html

S C / C++ 专题                          60
来源：http://dali.xuetiantiany.cn/Article/details/gtxricvddy.html

T 其他语言补充                          60
来源：http://dali.sysykeji.top/Article/details/gtorwqmssb.html

U 高频实用片段                         120
来源：http://dali.xuetiantiany.cn/Article/details/gtxmyyiwpd.html

------------------------------------
来源：http://dali.daxiang520.top/Article/details/gtydxvhzla.html

合计                                  2106 条
来源：http://dali.gotoacloud.top/Article/details/gtyuxhknks.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxeeqxbp.html

使用提醒
来源：http://dali.cdnleiting.top/Article/details/gtrqxieiew.html

--------------------------------------------------------------------------------
来源：http://dali.smart0.xyz/Article/details/gtuovivduy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jinqigfzy.top/Article/details/gtvvkdjwot.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.daxiang520.top/Article/details/gtgdxojyua.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jianghu66.top/Article/details/gtyrrdbvgb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.pycfn.com/Article/details/gtiprtwncs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jqgufenzy.top/Article/details/gtxluqzvdt.html

—— 文件结束 ——
来源：http://dali.nanxinkj.top/Article/details/gtubmpagbv.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtaxevsfnt.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhixingplan.top/Article/details/gtpyrujtlj.html

Common Programming Examples Cheat Book
来源：http://dali.redwolf501.top/Article/details/gtdjztasvm.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtrknmvtex.html

【收录内容】
来源：http://dali.yonumen.top/Article/details/gtdugprdrw.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cashguo.top/Article/details/gtrinsnbwq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.nwbrower.top/Article/details/gtplimbsnz.html

SQL · Bash · C · C++
来源：http://dali.dashuyun.cn/Article/details/gtbtoabklk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhoulong.xyz/Article/details/gtachvvyvc.html

【使用说明】
来源：http://dali.zhiwuduotai.top/Article/details/gtpjumgumn.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.wangshuangyany.cn/Article/details/gtizmcuoiz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hfpthk.cn/Article/details/gtmicnasfi.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.meibo888.top/Article/details/gtcngsrqdv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jinqigufen.top/Article/details/gtqcqcclol.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.iojbl.cn/Article/details/gtrfcpyrcn.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.aizwys.cn/Article/details/gtbuxeixpb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.quarkkingdee.top/Article/details/gtfgevqbti.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.nwbrower.top/Article/details/gtrzskhxta.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shuidangran.top/Article/details/gtyjacjrvq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.gogol.net.cn/Article/details/gtkazbiecp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.nanxuanxn.top/Article/details/gtkshaduht.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.ppjwa.cn/Article/details/gteszsjzus.html

【文件统计】
来源：http://dali.gotoacloud.top/Article/details/gtfgrurgny.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.vqdsnc.cn/Article/details/gtouwaledt.html

--------------------------------------------------------------------------------
来源：http://dali.pycfn.com/Article/details/gtvurwviir.html

目  录
来源：http://dali.yongpay.top/Article/details/gtgjtjztup.html

--------------------------------------------------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gtaumfsgwo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jyoumei.cn/Article/details/gtiwwskncy.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.tianlin.xyz/Article/details/gtwytfdcpf.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.birdmap.top/Article/details/gtvndkaenw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ybcxt.top/Article/details/gtlcxqnojs.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtngcwztaz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zdqjudy.top/Article/details/gtryddpdxa.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmencamsj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.gotoacloud.top/Article/details/gtrhfidrls.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.gzhubu.top/Article/details/gtwtddswux.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yueranfly.top/Article/details/gtwlhlyefi.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gtxzpsfhgz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gtbqbmexyz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtftcosoqj.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shuidangran.top/Article/details/gtjwppymnu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhongyouzk.top/Article/details/gtlgsuobac.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.ehwqpu.com/Article/details/gtgqtgywnw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ybcxt.top/Article/details/gtfwvgpyjx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jqgufenzy.top/Article/details/gtctrixnqy.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.svipenyu.cn/Article/details/gtowfipeul.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aibaodan.cn/Article/details/gtspztrkap.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnqzz.top/Article/details/gtaqwmpfhg.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtjgkifssr.html

A. 基础语法与类型
来源：http://dali.ppjwa.cn/Article/details/gtvxprpglb.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtpwklxuiu.html

[A01] Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtpiqzpcfy.html

Py:   print("Hello, World!")
来源：http://dali.cucudq.cn/Article/details/gtempfbnyd.html

PHP:  echo "Hello, World!";
来源：http://dali.ybcxt.top/Article/details/gtpdaoudqc.html

JS:   console.log("Hello, World!");
来源：http://dali.yongpay.top/Article/details/gtistcrprt.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hywenlv.cn/Article/details/gtjjzocpfa.html

Java: System.out.println("Hello, World!");
来源：http://dali.chenjidiqi.icu/Article/details/gtgvbmzaaq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ybcxt.top/Article/details/gtvvopjavd.html

Ruby: puts "Hello, World!"
来源：http://dali.yuxming.cn/Article/details/gtwxtiajtf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhiwuduotai.top/Article/details/gtctxaqiug.html

[A02] 变量声明与赋值
来源：http://dali.0kj1m.cn/Article/details/gtqbvgbqhl.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sufxvd.cn/Article/details/gtyrvveund.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.cdnleiting.top/Article/details/gthaxzkuub.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.daria6918.cn/Article/details/gteuojsoik.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxkerkflw.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.dashuyun.cn/Article/details/gtcyxxpokr.html

Go:   name := "Alex"; age := 20
来源：http://dali.feifeiyinyue.top/Article/details/gtafmtanqd.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hongshengwenyu.top/Article/details/gtdtcvllhp.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.0kj1m.cn/Article/details/gtnykwsdov.html

[A03] 常量定义
来源：http://dali.sufxvd.cn/Article/details/gtntkputio.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjlnntwvy.html

PHP:  const PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gtxecwplji.html

JS:   const PI = 3.14159;
来源：http://dali.havefunace.top/Article/details/gtzrcooyov.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaeunmrnw.html

Java: static final double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtwusagpfy.html

Go:   const PI = 3.14159
来源：http://dali.sysykeji.top/Article/details/gtbylzjizp.html

Ruby: PI = 3.14159
来源：http://dali.hysaishi.cn/Article/details/gtfqhevlnk.html

C#:   const double PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gtvmlpcozt.html

[A04] 判断变量类型
来源：http://dali.quarkkingdee.top/Article/details/gtdtzsigmh.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhixingplan.top/Article/details/gtrzzkfemh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.tianlin.xyz/Article/details/gtacmfikeu.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.daria6918.cn/Article/details/gtfgkcaawo.html

TS:   typeof x; x instanceof Date
来源：http://dali.cqqwz.cn/Article/details/gtlnbkhjet.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.nanxuanxn.top/Article/details/gtkilumbgr.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.svipenyu.cn/Article/details/gtjwvkkwfv.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xuanzx.com/Article/details/gtcdjdcnke.html

C#:   x.GetType().Name; x is int
来源：http://dali.hysaishi.cn/Article/details/gttmfzvedl.html

[A05] 整数除法与取模
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhkkjvux.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jyoumei.cn/Article/details/gtqzirxmch.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtomnhrnvl.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xziqi.cn/Article/details/gtprfkybvu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.wangdashe.top/Article/details/gtvnuppxyl.html

Java: 7 / 2; 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gtbcrnwuyd.html

Go:   7 / 2; 7 % 2
来源：http://dali.iojbl.cn/Article/details/gtgodzgwvs.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztctluju.html

C#:   7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gtbdyjmykk.html

[A06] 字符串转数字
来源：http://dali.guowangkeji.top/Article/details/gtcvxdultd.html

Py:   int("42"); float("3.14")
来源：http://dali.yuanzhike.top/Article/details/gtiulnnxov.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.xuetiantiany.cn/Article/details/gtwvcyiwhc.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yonumen.top/Article/details/gtwwlyvouf.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.tian-w.cn/Article/details/gtvjyvvqxr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.nanxuanxn.top/Article/details/gtiodwbocb.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zdqjudy.top/Article/details/gtqavqqrsv.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hywenlv.cn/Article/details/gtpegdjbnv.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.iojbl.cn/Article/details/gtdpmxxkal.html

[A07] 数字转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtcqawjtvl.html

Py:   str(42)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlfykdpt.html

PHP:  (string) 42; strval(42)
来源：http://dali.mhx1999.top/Article/details/gtdgkhihlh.html

JS:   String(42); (42).toString()
来源：http://dali.gaohongyu789.top/Article/details/gtmtjlluea.html

TS:   String(42)
来源：http://dali.chenzaomai.com/Article/details/gtbbwkhyum.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.tian-w.cn/Article/details/gtafbviuue.html

Go:   strconv.Itoa(42)
来源：http://dali.wangdashe.top/Article/details/gtwgyfolhk.html

Ruby: 42.to_s
来源：http://dali.0kj1m.cn/Article/details/gttigylbts.html

C#:   42.ToString()
来源：http://dali.sysykeji.top/Article/details/gtjzikmovs.html

[A08] 取整与四舍五入
来源：http://dali.hammf.cn/Article/details/gtkplonsgr.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.chenjidiqi.icu/Article/details/gtrwbcaxvt.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hongshengwenyu.top/Article/details/gtfgcenzuj.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.meibo888.top/Article/details/gtvezmvoor.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.sweek.top/Article/details/gtpgekqapz.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgfyphmn.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.chenzaomai.com/Article/details/gtndaqqlfe.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yongpay.top/Article/details/gtvfgiqjav.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jinghuilouyu.cn/Article/details/gtklopfxib.html

[A09] 绝对值与最大最小值
来源：http://dali.andypj.xyz/Article/details/gtplicppeh.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.andypj.xyz/Article/details/gteddkxugu.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sweek.top/Article/details/gtdhepgsrb.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.daxiang520.top/Article/details/gtabdlprcg.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gtoxfnjism.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gtpoqznabu.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.guannengcc.top/Article/details/gtxzjnazyg.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzystite.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.sysykeji.top/Article/details/gtjdxjuzgb.html

[A10] 生成随机数
来源：http://dali.daxiang520.top/Article/details/gtaxltysmf.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhengqikj.top/Article/details/gtxbwontkm.html

PHP:  random_int(1, 100);
来源：http://dali.havefunace.top/Article/details/gtvvvncwem.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdmkzhha.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.redwolf501.top/Article/details/gtuvkfkjxz.html

Java: new Random().nextInt(100) + 1
来源：http://dali.xuetiantiany.cn/Article/details/gtzojedtpn.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.shangyingyoupin.top/Article/details/gtvanrducv.html

Ruby: rand(1..100)
来源：http://dali.fzhhl.top/Article/details/gthasykzpp.html

C#:   new Random().Next(1, 101)
来源：http://dali.yuanzhike.top/Article/details/gtwanqxdij.html

[A11] 条件表达式（三元）
来源：http://dali.shangyingyoupin.top/Article/details/gtzdnpebpy.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.tanke756.top/Article/details/gtejtcycgs.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.xuetiantiany.cn/Article/details/gtfbassvmj.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.guannengcc.top/Article/details/gtewnrxgzi.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.nanxuanxn.top/Article/details/gtcwazfakr.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gtgnsnssfo.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.cucudq.cn/Article/details/gtbytejenv.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.quarkkingdee.top/Article/details/gtzyiaqvpz.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gtawqrpfwa.html

[A12] 字符串插值 / 格式化
来源：http://dali.jianghu66.top/Article/details/gtiqhontkg.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.cucudq.cn/Article/details/gtbbliotqi.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.wangdashe.top/Article/details/gtrdffumok.html

JS:   `Hello, ${name}!`
来源：http://dali.gotoacloud.top/Article/details/gtyrbjgfkj.html

TS:   `Hello, ${name}!`
来源：http://dali.quarkkingdee.top/Article/details/gtxocxtmcp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.ppjwa.cn/Article/details/gtbtrvsgop.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhixingplan.top/Article/details/gtjkeekoak.html

Ruby: "Hello, #{name}!"
来源：http://dali.hnqzz.top/Article/details/gtssibbnbt.html

C#:   $"Hello, {name}!"
来源：http://dali.jqgfzy.top/Article/details/gtbyctvxam.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.9152youxi.cn/Article/details/gtgolfucdc.html

Py:   "第一行\n第二行"
来源：http://dali.xziqi.cn/Article/details/gtcpxtgnri.html

PHP:  "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gtkbveekmw.html

JS:   "第一行\n第二行"
来源：http://dali.dianchejie.cn/Article/details/gtenzxmuji.html

TS:   "第一行\n第二行"
来源：http://dali.quarkkingdee.top/Article/details/gtwzrrpksc.html

Java: "第一行\n第二行"
来源：http://dali.sxryk.cn/Article/details/gtauggrjqx.html

Go:   "第一行\n第二行"
来源：http://dali.jinqigfzy.top/Article/details/gtcgvmyvfl.html

Ruby: "第一行\n第二行"
来源：http://dali.tanke756.top/Article/details/gtcqofbgpw.html

C#:   "第一行\n第二行"
来源：http://dali.316326.xyz/Article/details/gtokvsjsji.html


<!-- 参考信息 -->