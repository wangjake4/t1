代发 wailian999

[U79] PHP：静态分析
来源：http://dali.feifeiyinyue.top/Article/details/gtsiaumjvx.html

composer require --dev phpstan/phpstan
来源：http://dali.hongshengwenyu.top/Article/details/gtlxzrcdnj.html

[U80] PHP：代码规范修复
来源：http://dali.zycfv.cn/Article/details/gterhsiezf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.andypj.xyz/Article/details/gtnsjupbfg.html

[U81] JS：初始化项目
来源：http://dali.guannengcc.top/Article/details/gtnkrpbvbq.html

npm init -y;  npm i express
来源：http://dali.shuidangran.top/Article/details/gtaplyswah.html

[U82] JS：package.json 脚本
来源：http://dali.hongshengwenyu.top/Article/details/gtvcvtmecf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jinqigufen.top/Article/details/gtbjnhntpp.html

[U83] JS：ES Module 导入导出
来源：http://dali.jqgufenzy.top/Article/details/gtutuvtykm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ppjwa.cn/Article/details/gtyewllaky.html

[U84] JS：CommonJS 写法
来源：http://dali.jiagoushi.top/Article/details/gtsffznjpf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cheryme.top/Article/details/gtjnftuaqn.html

[U85] JS：可选链
来源：http://dali.jqgfzy.top/Article/details/gtxghixrix.html

a?.b?.c
来源：http://dali.meibo888.top/Article/details/gtpzdwbgdh.html

[U86] JS：空值合并
来源：http://dali.chenjidiqi.icu/Article/details/gtfwaecrkg.html

a ?? b
来源：http://dali.zhengqikj.top/Article/details/gttzwekroj.html

[U87] JS：解构默认值
来源：http://dali.aizwys.cn/Article/details/gtnpqrutll.html

const { a = 1, b = 2 } = obj;
来源：http://dali.nanxinkj.top/Article/details/gtpldifeag.html

[U88] JS：对象展开合并
来源：http://dali.yvedp.cn/Article/details/gtxyrojxeg.html

{ ...a, ...b }
来源：http://dali.aizwys.cn/Article/details/gtphruolmo.html

[U89] JS：数组去重
来源：http://dali.cashguo.top/Article/details/gtizbudytn.html

[...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gtsonrgxxj.html

[U90] JS：数字数组排序
来源：http://dali.hfpthk.cn/Article/details/gtuknzwwtw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffhnjoaj.html

[U91] JS：对象键值遍历
来源：http://dali.hfpthk.cn/Article/details/gtsnoizdnb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yj20258888.top/Article/details/gtnzpymock.html

[U92] JS：深拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gtrycciusz.html

structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gtqyedrbrm.html

[U93] JS：模板字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjwdijple.html

`共 ${n} 条`
来源：http://dali.yuxming.cn/Article/details/gtswjsxiny.html

[U94] JS：箭头函数
来源：http://dali.svipenyu.cn/Article/details/gtabwcytln.html

const double = x => x * 2;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqiqtxeb.html

[U95] JS：Promise 包装
来源：http://dali.zdqjudy.top/Article/details/gtsiydlqtb.html

new Promise((resolve, reject) => {})
来源：http://dali.vqdsnc.cn/Article/details/gtpqirpavh.html

[U96] JS：async/await 与异常
来源：http://dali.zdqjudy.top/Article/details/gtiwofedzd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtpkzmigii.html

[U97] JS：并发请求
来源：http://dali.zhoulong.xyz/Article/details/gtpkitapvg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gtzrcizjjl.html

[U98] JS：fetch 带 JSON
来源：http://dali.yj20258.top/Article/details/gtviqvsske.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.quarkkingdee.top/Article/details/gteobuwjll.html

[U99] JS：事件监听
来源：http://dali.zhixingplan.top/Article/details/gtnfcxnavd.html

el.addEventListener("click", e => {})
来源：http://dali.aibaodan.cn/Article/details/gtqdlrvise.html

[U100] JS：DOM 查询
来源：http://dali.svipenyu.cn/Article/details/gtrvgmkklx.html

document.querySelector(".item")
来源：http://dali.jiagoushi.top/Article/details/gtlcdnwpek.html

[U101] JS：classList 操作
来源：http://dali.zhiwuduotai.top/Article/details/gtrggkclow.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gtomgxfycf.html

[U102] JS：本地存储
来源：http://dali.chenlongwang.top/Article/details/gtbowdxgvm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nanxinkj.top/Article/details/gtehdfjqar.html

[U103] JS：定时器
来源：http://dali.smart0.xyz/Article/details/gtfpkzisyp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shanyushiyangtech.top/Article/details/gtogvhivdf.html

[U104] JS：防抖
来源：http://dali.gaohongyu789.top/Article/details/gthhcsbznq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gtssqqsuky.html

[U105] JS：节流
来源：http://dali.hongshengwenyu.top/Article/details/gttutblgil.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yvedp.cn/Article/details/gthflnlxto.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gtuhhyzvrt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinqigufen.top/Article/details/gtkyrhplqa.html

[U107] JS：数字千分位
来源：http://dali.guannengcc.top/Article/details/gtchsvxnjd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ehwqpu.com/Article/details/gtbqbgunyn.html

[U108] JS：随机整数
来源：http://dali.pycfn.com/Article/details/gtzrdugdbl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ywan-chungtsiang.top/Article/details/gttatjvtaq.html

[U109] JS：数组分组
来源：http://dali.jiagoushi.top/Article/details/gtbossoxet.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jqgfzy.top/Article/details/gtqadmrbbv.html

[U110] JS：数组分块
来源：http://dali.haohaochexian.top/Article/details/gtjhodxyys.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hfpthk.cn/Article/details/gtlrwamhha.html

[U111] JS：对象转 Map
来源：http://dali.jianghu66.top/Article/details/gtcdftycyk.html

new Map(Object.entries(obj))
来源：http://dali.svipenyu.cn/Article/details/gtooduijdm.html

[U112] JS：字符串补位
来源：http://dali.yangfankeji.com/Article/details/gteusiefat.html

"7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtdifpryhn.html

[U113] JS：正则替换全部
来源：http://dali.vqdsnc.cn/Article/details/gtmdqnvxcr.html

s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gtvpygvbtv.html

[U114] JS：JSON 深比较
来源：http://dali.tianlin.xyz/Article/details/gtpmzfmuqa.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shuidangran.top/Article/details/gtzignyiat.html

[U115] JS：生成 UUID
来源：http://dali.pengpengdd.cyou/Article/details/gtyuzvussf.html

crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzgrdcbl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gotoacloud.top/Article/details/gtukcpfwai.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cashguo.top/Article/details/gtjswrvipf.html

[U117] JS：单元测试
来源：http://dali.kuanghao11.cn/Article/details/gttbnfzlia.html

npm i -D vitest;  npx vitest
来源：http://dali.shangyingyoupin.top/Article/details/gtkqyhryaj.html

[U118] JS：开发服务器
来源：http://dali.jqgfzy.top/Article/details/gtwsjwyzlv.html

npm i -D vite;  npx vite
来源：http://dali.quarkkingdee.top/Article/details/gtjjxpumic.html

[U119] JS：生产构建
来源：http://dali.zhengqikj.top/Article/details/gtmpypdwlu.html

npx vite build
来源：http://dali.zhaomingkeji.xyz/Article/details/gtssnsjklw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xylfe.cn/Article/details/gtxqlwvlmv.html

import.meta.env.VITE_API_URL
来源：http://dali.shzxlz.cn/Article/details/gthuwogapp.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtlxqtfuds.html

统计汇总
来源：http://dali.cheryme.top/Article/details/gtqsdflgzy.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtpzqyuiyk.html

按语言统计（条）：
来源：http://dali.jqgfzy.top/Article/details/gtyewrzdvx.html

Python ......... 252
来源：http://dali.sufxvd.cn/Article/details/gtzpsqkzra.html

PHP ............ 252
来源：http://dali.havefunace.top/Article/details/gtrarlerul.html

JavaScript ..... 252
来源：http://dali.tian-w.cn/Article/details/gtthtgpnov.html

TypeScript ..... 212
来源：http://dali.xuanzx.com/Article/details/gtbykginqs.html

Java ........... 212
来源：http://dali.shanyushiyangtech.top/Article/details/gtnruxklxz.html

Go ............. 212
来源：http://dali.jinghuilouyu.cn/Article/details/gttwbmrnjh.html

Ruby ........... 212
来源：http://dali.birdmap.top/Article/details/gtjlnykcvw.html

C# ............. 212
来源：http://dali.ehwqpu.com/Article/details/gtqvemaqhk.html

C .............. 30
来源：http://dali.nanxuanxn.top/Article/details/gthbgpnxhx.html

C++ ............ 30
来源：http://dali.kuanghao11.cn/Article/details/gtwvtiefjo.html

SQL ............ 90
来源：http://dali.ybcxt.top/Article/details/gtwnitrbtb.html

Bash ........... 80
来源：http://dali.shuidangran.top/Article/details/gtdrxlwfqi.html

Kotlin ......... 15
来源：http://dali.cashguo.top/Article/details/gtkmyxbvys.html

Swift .......... 15
来源：http://dali.shangyingyoupin.top/Article/details/gtenwgmybw.html

Lua ............ 10
来源：http://dali.jinqigufen.top/Article/details/gtztawnujc.html

Perl ........... 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuspjeeto.html

Scala .......... 10
来源：http://dali.sufxvd.cn/Article/details/gtofheiijm.html

------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqnscoef.html

合计 ........... 2106 条
来源：http://dali.0kj1m.cn/Article/details/gtglokvjfk.html

按章节统计：
来源：http://dali.tanke756.top/Article/details/gtqwnzmdcq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhaomingkeji.xyz/Article/details/gtesqwmmct.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.andypj.xyz/Article/details/gtqdrfxerb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.sysykeji.top/Article/details/gtmtvhfdja.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.havefunace.top/Article/details/gtqgwqemdb.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yueranfly.top/Article/details/gtobynbggl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xziqi.cn/Article/details/gtqqemauep.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.guannengcc.top/Article/details/gtfavlwbqv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.svipenyu.cn/Article/details/gtlcmfsyva.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gtpxlhknix.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xziqi.cn/Article/details/gtlesicyqf.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gtjibgkrlc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gtfmbtzqld.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gteltxttdw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.vqdsnc.cn/Article/details/gtvxzjhomq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.guowangkeji.top/Article/details/gtqzaodcje.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtxeswdtjl.html

Q SQL 专题                              90
来源：http://dali.haohaochexian.top/Article/details/gtkreykavh.html

R Bash 专题                             80
来源：http://dali.feifeiyinyue.top/Article/details/gtiimzggvg.html

S C / C++ 专题                          60
来源：http://dali.sysykeji.top/Article/details/gtiwpbrqes.html

T 其他语言补充                          60
来源：http://dali.hnqzz.top/Article/details/gtryqnhqaj.html

U 高频实用片段                         120
来源：http://dali.yj20258.top/Article/details/gtnpltnoax.html

------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokdwkqsq.html

合计                                  2106 条
来源：http://dali.chenjidiqi.icu/Article/details/gtsoulmdvl.html

--------------------------------------------------------------------------------
来源：http://dali.yonumen.top/Article/details/gtglfsftda.html

使用提醒
来源：http://dali.nwbrower.top/Article/details/gtmadmhgkb.html

--------------------------------------------------------------------------------
来源：http://dali.yj202588.top/Article/details/gtnjizjsgb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xuanzx.com/Article/details/gtwtbhgqcb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.sxryk.cn/Article/details/gttcxyckcc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.guannengcc.top/Article/details/gtbnzjetbc.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cashguo.top/Article/details/gtsckjgmyk.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.316326.xyz/Article/details/gtorcicrzr.html

—— 文件结束 ——
来源：http://dali.smart0.xyz/Article/details/gtsyhnvqdv.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtvfapzctr.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cdnleiting.top/Article/details/gtttxqarpl.html

Common Programming Examples Cheat Book
来源：http://dali.shuidangran.top/Article/details/gtyyybzgjz.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtjmlgjswo.html

【收录内容】
来源：http://dali.jyoumei.cn/Article/details/gtdksdfgeb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yueranfly.top/Article/details/gtmnyvihcx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yuxming.cn/Article/details/gtfwwxipgt.html

SQL · Bash · C · C++
来源：http://dali.zdqjudy.top/Article/details/gtnpubzjcl.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jlsjyb.cn/Article/details/gtdzpmuafi.html

【使用说明】
来源：http://dali.hnxiangtu.top/Article/details/gtrqhwzijx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ivvv.top/Article/details/gtzxdjldwg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhiwuduotai.top/Article/details/gtbaklexxu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xziqi.cn/Article/details/gtpnfwovsi.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hnqzz.top/Article/details/gtrjnfuzce.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.redwolf501.top/Article/details/gtepqyqudm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.meibo888.top/Article/details/gtlzlngrcy.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yuanzhike.top/Article/details/gtxhlbyrvi.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.c1oappe.top/Article/details/gttcpjcvhy.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ppjwa.cn/Article/details/gtiweteqpj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cheryme.top/Article/details/gtvuddneac.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.mhx1999.top/Article/details/gtgcjtjxmb.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwpujofs.html

【文件统计】
来源：http://dali.hysaishi.cn/Article/details/gtaaepysdn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jinghuilouyu.cn/Article/details/gtreghtwcy.html

--------------------------------------------------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtdwixcpea.html

目  录
来源：http://dali.c1oappe.top/Article/details/gtpyhrpxpv.html

--------------------------------------------------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtbbqsfynm.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.gotoacloud.top/Article/details/gttienepwn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.gaohongyu789.top/Article/details/gtpxcfjjjn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.guowangkeji.top/Article/details/gtyahvxjps.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.pycfn.com/Article/details/gtuyknynaj.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.fengsongda.top/Article/details/gtxfmiegbt.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.guowangkeji.top/Article/details/gtuviegtch.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.fzhhl.top/Article/details/gtpbvugifz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.tanke756.top/Article/details/gtrzktzshm.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yanxiufei.cn/Article/details/gtkstilnxv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yj202588.top/Article/details/gtkogpjsvm.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gtyoligali.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gtnafagetz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.wangdashe.top/Article/details/gtauszxrtz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.mhx1999.top/Article/details/gthzcyrajo.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xylfe.cn/Article/details/gtmefsfstj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gtstmjgwyn.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.redwolf501.top/Article/details/gtkizjqeci.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.kuanghao11.cn/Article/details/gtscqpzcmg.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.pycfn.com/Article/details/gtzktmxsip.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenzaomai.com/Article/details/gtxlmnglwc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.daxiang520.top/Article/details/gtkjbtomvl.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtrvokwbhr.html

A. 基础语法与类型
来源：http://dali.hywenlv.cn/Article/details/gtseasaybb.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahuebzhi.html

[A01] Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjjbbsee.html

Py:   print("Hello, World!")
来源：http://dali.bjfxy.top/Article/details/gtlrkpvmzo.html

PHP:  echo "Hello, World!";
来源：http://dali.jqgfzy.top/Article/details/gtyymcilsd.html

JS:   console.log("Hello, World!");
来源：http://dali.feifeiyinyue.top/Article/details/gtqkanoavu.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hnxiangtu.top/Article/details/gtpoetwnyj.html

Java: System.out.println("Hello, World!");
来源：http://dali.svipenyu.cn/Article/details/gtnoweusrv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.smart0.xyz/Article/details/gtrsvmmeda.html

Ruby: puts "Hello, World!"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvkwbdrk.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hnqzz.top/Article/details/gtooicyvap.html

[A02] 变量声明与赋值
来源：http://dali.nanxuanxn.top/Article/details/gtnwqcosyg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ydzc1.top/Article/details/gtilrvmzrq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtednkepeu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoitgztoq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpivhxxcu.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hammf.cn/Article/details/gtjaravvmd.html

Go:   name := "Alex"; age := 20
来源：http://dali.hammf.cn/Article/details/gtztdnamyx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yueranfly.top/Article/details/gtazyrijza.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.vqdsnc.cn/Article/details/gtmizltbsp.html

[A03] 常量定义
来源：http://dali.yj20258888.top/Article/details/gtfqirwarp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.dashuyun.cn/Article/details/gtqmjincav.html

PHP:  const PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gthavqjate.html

JS:   const PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtrknuggiq.html

TS:   const PI: number = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gtotvhkncw.html

Java: static final double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtrrsmwwou.html

Go:   const PI = 3.14159
来源：http://dali.hnxiangtu.top/Article/details/gtpquxfqoc.html

Ruby: PI = 3.14159
来源：http://dali.ivvv.top/Article/details/gtpsejaqeb.html

C#:   const double PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtlzmjcnzm.html

[A04] 判断变量类型
来源：http://dali.aizwys.cn/Article/details/gtpuvfmnoe.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ybcxt.top/Article/details/gtdkinbelq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yueranfly.top/Article/details/gtiebvowfg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xuetiantiany.cn/Article/details/gtigrnfbgy.html

TS:   typeof x; x instanceof Date
来源：http://dali.jinqigfzy.top/Article/details/gtxqytaxpl.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jinqigfzy.top/Article/details/gtahkcrfsm.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.chenlongwang.top/Article/details/gtqqgndqan.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwalzpcs.html

C#:   x.GetType().Name; x is int
来源：http://dali.pengpengdd.cyou/Article/details/gtojynskdw.html

[A05] 整数除法与取模
来源：http://dali.mhx1999.top/Article/details/gtzqiisfak.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cdnleiting.top/Article/details/gtfntufocs.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtiitmmvfq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yvedp.cn/Article/details/gtmpfnlmez.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gtgxhrtnxc.html

Java: 7 / 2; 7 % 2
来源：http://dali.ybcxt.top/Article/details/gtlblzxvcu.html

Go:   7 / 2; 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gtgfrplqts.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.tian-w.cn/Article/details/gtblkuaurw.html

C#:   7 / 2; 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtlxfeqsfj.html

[A06] 字符串转数字
来源：http://dali.iojbl.cn/Article/details/gtmqaanzot.html

Py:   int("42"); float("3.14")
来源：http://dali.bjfxy.top/Article/details/gtljlppfzo.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jqgufenzy.top/Article/details/gtxemxvyeg.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.haohaochexian.top/Article/details/gtlzlfzkgx.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jinqigfzy.top/Article/details/gtupwbxfyk.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.aizwys.cn/Article/details/gtbzlsvpah.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.mhx1999.top/Article/details/gtxvujhylg.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmktloye.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.quarkkingdee.top/Article/details/gtstgizkhq.html

[A07] 数字转字符串
来源：http://dali.yj202588.top/Article/details/gtditqhvgf.html

Py:   str(42)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgxgdpoa.html

PHP:  (string) 42; strval(42)
来源：http://dali.wangshuangyany.cn/Article/details/gtrxkzhcof.html

JS:   String(42); (42).toString()
来源：http://dali.cqqwz.cn/Article/details/gtcsmmyumi.html

TS:   String(42)
来源：http://dali.dianchejie.cn/Article/details/gtclhqkdaw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.svipenyu.cn/Article/details/gtdmyqsucf.html

Go:   strconv.Itoa(42)
来源：http://dali.chenjidiqi.icu/Article/details/gtfgihbaff.html

Ruby: 42.to_s
来源：http://dali.ehwqpu.com/Article/details/gtqvegfhfl.html

C#:   42.ToString()
来源：http://dali.tianlin.xyz/Article/details/gtbgaoaksy.html

[A08] 取整与四舍五入
来源：http://dali.yueranfly.top/Article/details/gttgumlybt.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hongshengwenyu.top/Article/details/gtzbqsrvew.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.xinyue.icu/Article/details/gtchpqygqg.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.ehwqpu.com/Article/details/gttiofdgfd.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.gogol.net.cn/Article/details/gtaoqttjvo.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hywenlv.cn/Article/details/gtofvcbdwe.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.nanxinkj.top/Article/details/gtqptjhgfh.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jinqigufen.top/Article/details/gtxsvrgjgn.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yj20258888.top/Article/details/gtqvosdsmk.html

[A09] 绝对值与最大最小值
来源：http://dali.jqgfzy.top/Article/details/gtkdfnamuc.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xylfe.cn/Article/details/gtaaukbuue.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gtcjnyezxa.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yj20258.top/Article/details/gtadavoovx.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.bjfxy.top/Article/details/gtwljcovwc.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.daxiang520.top/Article/details/gtyjpwcbas.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhiwuduotai.top/Article/details/gtxqcrefzf.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.nanxinkj.top/Article/details/gtnjqrkscq.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.bjfxy.top/Article/details/gtwwrvzvlt.html

[A10] 生成随机数
来源：http://dali.yangfankeji.com/Article/details/gtgtyhvoyd.html

Py:   import random; random.randint(1, 100)
来源：http://dali.feifeiyinyue.top/Article/details/gtpzmpqird.html

PHP:  random_int(1, 100);
来源：http://dali.chenjidiqi.icu/Article/details/gtrelzdbiy.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.9152youxi.cn/Article/details/gtfmzkibsr.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ivvv.top/Article/details/gtxxtckkim.html

Java: new Random().nextInt(100) + 1
来源：http://dali.fzhhl.top/Article/details/gtxlmevagz.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yueranfly.top/Article/details/gtxpcisbcj.html

Ruby: rand(1..100)
来源：http://dali.cqqwz.cn/Article/details/gtisdnhqee.html

C#:   new Random().Next(1, 101)
来源：http://dali.cdnleiting.top/Article/details/gtbqsazhte.html

[A11] 条件表达式（三元）
来源：http://dali.dashuyun.cn/Article/details/gtmnoltznq.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.ydzc1.top/Article/details/gtcjqkncrq.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.chenzaomai.com/Article/details/gtznmcngcg.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.fzhhl.top/Article/details/gtmyetxgmo.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybhenroz.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.redwolf501.top/Article/details/gtihsqbtwl.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yueranfly.top/Article/details/gtvaykicms.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.gzhubu.top/Article/details/gtlttzkrif.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.birdmap.top/Article/details/gtxnugkktj.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhengqikj.top/Article/details/gtjrufiyef.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqtbcapd.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.c1oappe.top/Article/details/gtfddupaga.html

JS:   `Hello, ${name}!`
来源：http://dali.9152youxi.cn/Article/details/gtuoknsrhr.html

TS:   `Hello, ${name}!`
来源：http://dali.0kj1m.cn/Article/details/gtembqzxyn.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtygcvdhcs.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.kuanghao11.cn/Article/details/gtnbkvruur.html

Ruby: "Hello, #{name}!"
来源：http://dali.dashuyun.cn/Article/details/gtbqdiiqua.html

C#:   $"Hello, {name}!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqpjlxet.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgczpobp.html


<!-- 参考信息 -->