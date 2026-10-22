代发 wailian999

[U81] JS：初始化项目
来源：http://dali.cqqwz.cn/Article/details/gtkedhpasl.html

npm init -y;  npm i express
来源：http://dali.pycfn.com/Article/details/gttsonzqtd.html

[U82] JS：package.json 脚本
来源：http://dali.zhongyouzk.top/Article/details/gtgrjgnjcx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.wangshuangyany.cn/Article/details/gtxybhfkgb.html

[U83] JS：ES Module 导入导出
来源：http://dali.hysaishi.cn/Article/details/gtxepkmuvy.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zycfv.cn/Article/details/gtkswxqwyh.html

[U84] JS：CommonJS 写法
来源：http://dali.0kj1m.cn/Article/details/gtoxsqzgal.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hongshengwenyu.top/Article/details/gtnuiepmxm.html

[U85] JS：可选链
来源：http://dali.aizwys.cn/Article/details/gtzqhvvvkx.html

a?.b?.c
来源：http://dali.zycfv.cn/Article/details/gtqdsugnnc.html

[U86] JS：空值合并
来源：http://dali.sxryk.cn/Article/details/gtjdlwjeim.html

a ?? b
来源：http://dali.shzxlz.cn/Article/details/gtzjajfshe.html

[U87] JS：解构默认值
来源：http://dali.xuetiantiany.cn/Article/details/gtbogdszjw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yangfankeji.com/Article/details/gtmyimlgvh.html

[U88] JS：对象展开合并
来源：http://dali.hfpthk.cn/Article/details/gthiunsoiy.html

{ ...a, ...b }
来源：http://dali.jiagoushi.top/Article/details/gtilkqudhb.html

[U89] JS：数组去重
来源：http://dali.chenzaomai.com/Article/details/gtntpcvspb.html

[...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gtlldiknre.html

[U90] JS：数字数组排序
来源：http://dali.ybcxt.top/Article/details/gthwvlypdy.html

[...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gtwmdsvgga.html

[U91] JS：对象键值遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtqzkpinow.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gzhubu.top/Article/details/gtjzhkaeen.html

[U92] JS：深拷贝
来源：http://dali.hnxiangtu.top/Article/details/gtzjahvcil.html

structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gtfhwdxrwp.html

[U93] JS：模板字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtyhwbcfwo.html

`共 ${n} 条`
来源：http://dali.cashguo.top/Article/details/gtbqlkgtsr.html

[U94] JS：箭头函数
来源：http://dali.fengsongda.top/Article/details/gtoqmkkrci.html

const double = x => x * 2;
来源：http://dali.sxryk.cn/Article/details/gtjqjzvwzb.html

[U95] JS：Promise 包装
来源：http://dali.hysaishi.cn/Article/details/gtrsthtcds.html

new Promise((resolve, reject) => {})
来源：http://dali.guowangkeji.top/Article/details/gtkieljnrf.html

[U96] JS：async/await 与异常
来源：http://dali.xinyue.icu/Article/details/gtnmbmkrmn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gttnstyfny.html

[U97] JS：并发请求
来源：http://dali.guannengcc.top/Article/details/gtvbekdftd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqtwiila.html

[U98] JS：fetch 带 JSON
来源：http://dali.xylfe.cn/Article/details/gtwoptopcy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.chenjidiqi.icu/Article/details/gtawpvvbms.html

[U99] JS：事件监听
来源：http://dali.haohaochexian.top/Article/details/gtisaxyoxh.html

el.addEventListener("click", e => {})
来源：http://dali.zhiwuduotai.top/Article/details/gthfxvgglz.html

[U100] JS：DOM 查询
来源：http://dali.feifeiyinyue.top/Article/details/gtmpqurmea.html

document.querySelector(".item")
来源：http://dali.sxryk.cn/Article/details/gtdizjoarn.html

[U101] JS：classList 操作
来源：http://dali.shzxlz.cn/Article/details/gtwljwxkrb.html

el.classList.toggle("active")
来源：http://dali.sweek.top/Article/details/gtloxmzgvu.html

[U102] JS：本地存储
来源：http://dali.sufxvd.cn/Article/details/gtcdnjkipa.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfynqcbe.html

[U103] JS：定时器
来源：http://dali.tianlin.xyz/Article/details/gtahfoatcy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.haohaochexian.top/Article/details/gtymgvdqgm.html

[U104] JS：防抖
来源：http://dali.havefunace.top/Article/details/gtayiluwak.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gtkcxvocie.html

[U105] JS：节流
来源：http://dali.jqgufenzy.top/Article/details/gtxmtkwtyj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.0kj1m.cn/Article/details/gtmvkkzojk.html

[U106] JS：日期格式化
来源：http://dali.ybcxt.top/Article/details/gthxboxpqp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.wangshuangyany.cn/Article/details/gttejcqboy.html

[U107] JS：数字千分位
来源：http://dali.yj20258888.top/Article/details/gtvtbbbyfq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhixingplan.top/Article/details/gtustypjam.html

[U108] JS：随机整数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcuzprard.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.pengpengdd.cyou/Article/details/gtsglneggg.html

[U109] JS：数组分组
来源：http://dali.xuanzx.com/Article/details/gtfkmnlrxc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.redwolf501.top/Article/details/gtpsrotcuh.html

[U110] JS：数组分块
来源：http://dali.quarkkingdee.top/Article/details/gtlgyhxbyz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jlsjyb.cn/Article/details/gtiafogely.html

[U111] JS：对象转 Map
来源：http://dali.tian-w.cn/Article/details/gtoljrfnrw.html

new Map(Object.entries(obj))
来源：http://dali.yuanzhike.top/Article/details/gtfwbhqotl.html

[U112] JS：字符串补位
来源：http://dali.jinqigufen.top/Article/details/gtbgghzuua.html

"7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhnldwrj.html

[U113] JS：正则替换全部
来源：http://dali.fengsongda.top/Article/details/gtcaiwdyth.html

s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gtpxmjqdrg.html

[U114] JS：JSON 深比较
来源：http://dali.sysykeji.top/Article/details/gtsfrndwgn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yueranfly.top/Article/details/gtsgzimmwp.html

[U115] JS：生成 UUID
来源：http://dali.yuxming.cn/Article/details/gtvaolrhxo.html

crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gtuquhfusp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jinqigfzy.top/Article/details/gtpiblsoow.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtbnhgbjpu.html

[U117] JS：单元测试
来源：http://dali.hywenlv.cn/Article/details/gtagbiwzbk.html

npm i -D vitest;  npx vitest
来源：http://dali.meibo888.top/Article/details/gtzjluizdq.html

[U118] JS：开发服务器
来源：http://dali.jyoumei.cn/Article/details/gtkwdzcpua.html

npm i -D vite;  npx vite
来源：http://dali.zhiwuduotai.top/Article/details/gtjpdtywli.html

[U119] JS：生产构建
来源：http://dali.meibo888.top/Article/details/gtvtzdsfig.html

npx vite build
来源：http://dali.wangshuangyany.cn/Article/details/gthnucyljl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.guowangkeji.top/Article/details/gthjoqzacm.html

import.meta.env.VITE_API_URL
来源：http://dali.zhixingplan.top/Article/details/gtbaplryis.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gteviqnvvm.html

统计汇总
来源：http://dali.wangdashe.top/Article/details/gtfghoulyb.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtngrdnbun.html

按语言统计（条）：
来源：http://dali.yuanzhike.top/Article/details/gttjpmvhgl.html

Python ......... 252
来源：http://dali.hysaishi.cn/Article/details/gtewmgxilv.html

PHP ............ 252
来源：http://dali.meibo888.top/Article/details/gtesjmcsen.html

JavaScript ..... 252
来源：http://dali.yuanzhike.top/Article/details/gtwmklcyqv.html

TypeScript ..... 212
来源：http://dali.shanyushiyangtech.top/Article/details/gtoiziqcki.html

Java ........... 212
来源：http://dali.gaohongyu789.top/Article/details/gtqiuluwme.html

Go ............. 212
来源：http://dali.jinqigfzy.top/Article/details/gtykouhxje.html

Ruby ........... 212
来源：http://dali.jyoumei.cn/Article/details/gtbogerkbw.html

C# ............. 212
来源：http://dali.shzxlz.cn/Article/details/gtuopkvqyq.html

C .............. 30
来源：http://dali.tanke756.top/Article/details/gtjrwrmkvr.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gtigzpcsof.html

SQL ............ 90
来源：http://dali.chenlongwang.top/Article/details/gtxbkvtswk.html

Bash ........... 80
来源：http://dali.cashguo.top/Article/details/gtncoifqnn.html

Kotlin ......... 15
来源：http://dali.jinqigufen.top/Article/details/gtkqcnhcif.html

Swift .......... 15
来源：http://dali.yuanzhike.top/Article/details/gttlhlgmvh.html

Lua ............ 10
来源：http://dali.sweek.top/Article/details/gtfkhokhlo.html

Perl ........... 10
来源：http://dali.jqgufenzy.top/Article/details/gttwxsdtyr.html

Scala .......... 10
来源：http://dali.cheryme.top/Article/details/gtghwinobt.html

------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gtqczcgpje.html

合计 ........... 2106 条
来源：http://dali.snrcjt.cn/Article/details/gtikmdbzsv.html

按章节统计：
来源：http://dali.nwbrower.top/Article/details/gtmkbsxjql.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.quarkkingdee.top/Article/details/gtrjlqffkc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.daria6918.cn/Article/details/gtweyvnugm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zycfv.cn/Article/details/gtheltzotl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cqqwz.cn/Article/details/gtqqiyhauy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.nwbrower.top/Article/details/gtqenjjhob.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.redwolf501.top/Article/details/gtcicesglr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.cashguo.top/Article/details/gtiyapoowp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.andypj.xyz/Article/details/gtpjokytdo.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gtnguaqect.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shangyingyoupin.top/Article/details/gtxgvxoidc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gtldikxggo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gtomnczwdc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvetugkrk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.kuanghao11.cn/Article/details/gttvpsfjru.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.nanxuanxn.top/Article/details/gthnyjqclq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gtjdebkcsa.html

Q SQL 专题                              90
来源：http://dali.nwbrower.top/Article/details/gtwlzxwwws.html

R Bash 专题                             80
来源：http://dali.redwolf501.top/Article/details/gtqrvumzzp.html

S C / C++ 专题                          60
来源：http://dali.hywenlv.cn/Article/details/gtnrsilqeu.html

T 其他语言补充                          60
来源：http://dali.snrcjt.cn/Article/details/gtzpllreoy.html

U 高频实用片段                         120
来源：http://dali.daria6918.cn/Article/details/gtpxhucimp.html

------------------------------------
来源：http://dali.guannengcc.top/Article/details/gtwoayooml.html

合计                                  2106 条
来源：http://dali.0kj1m.cn/Article/details/gtepiehcpf.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtovwyplul.html

使用提醒
来源：http://dali.ybcxt.top/Article/details/gtzzosslah.html

--------------------------------------------------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gtwzyeiipy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.haohaochexian.top/Article/details/gtbplhzcch.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hongshengwenyu.top/Article/details/gtnovzfklz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hammf.cn/Article/details/gtavwnrbso.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.sysykeji.top/Article/details/gtdgzmpnny.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.meibo888.top/Article/details/gtbdixchie.html

—— 文件结束 ——
来源：http://dali.tianlin.xyz/Article/details/gtizlkupoz.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtlnukvudd.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hnqzz.top/Article/details/gtnwzdjpss.html

Common Programming Examples Cheat Book
来源：http://dali.hfpthk.cn/Article/details/gtwcukvkxh.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtswwjyedl.html

【收录内容】
来源：http://dali.xuetiantiany.cn/Article/details/gtysgikbaj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.fzhhl.top/Article/details/gtwyaxvwae.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.daria6918.cn/Article/details/gtzuqstdwx.html

SQL · Bash · C · C++
来源：http://dali.zhiwuduotai.top/Article/details/gtuzjpipfw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.shzxlz.cn/Article/details/gtuwzodejs.html

【使用说明】
来源：http://dali.nwbrower.top/Article/details/gtvoldbbzw.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yangfankeji.com/Article/details/gtzrjrppmp.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.fzhhl.top/Article/details/gtrpsqlkuj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswieqbsn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.havefunace.top/Article/details/gtvephdeyy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ywan-chungtsiang.top/Article/details/gtceplhfkx.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xuanzx.com/Article/details/gtirsboich.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.dashuyun.cn/Article/details/gteutuaeii.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.316326.xyz/Article/details/gtulzbyyrn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.haohaochexian.top/Article/details/gtjgrethzt.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yj202588.top/Article/details/gtvzfwpjel.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.tianlin.xyz/Article/details/gtkvbdzzvw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.tianlin.xyz/Article/details/gtmhxdxqgf.html

【文件统计】
来源：http://dali.cdnleiting.top/Article/details/gtdnrczowt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.tanke756.top/Article/details/gtbjxxyyjn.html

--------------------------------------------------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gtgvunoaam.html

目  录
来源：http://dali.zhongyouzk.top/Article/details/gtsgavadia.html

--------------------------------------------------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gtaaiyjlha.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhixingplan.top/Article/details/gtsjkltnyg.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hfpthk.cn/Article/details/gtonziqsqw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.andypj.xyz/Article/details/gtzztmabmd.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shuidangran.top/Article/details/gtolcjtvjl.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.daria6918.cn/Article/details/gtxqxtsipk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.nanxuanxn.top/Article/details/gtoxkoojst.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.vqdsnc.cn/Article/details/gtsjddrfxk.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.svipenyu.cn/Article/details/gtjcojjros.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gtlpsrmqwz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yj20258888.top/Article/details/gtdzmmhfic.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbzradles.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gtqqlluclt.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gtbpcthciv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.tian-w.cn/Article/details/gtkyrqvtvc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yvedp.cn/Article/details/gtkdikbgdt.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gtjprrwvmz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.nwbrower.top/Article/details/gtqrbqtdgj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.fengsongda.top/Article/details/gtrptqguuy.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xziqi.cn/Article/details/gtitwhrdrf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvxihgso.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtnoynyhlh.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtmorvsxsl.html

A. 基础语法与类型
来源：http://dali.iojbl.cn/Article/details/gtxivwudgv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtpnxbodeb.html

[A01] Hello World
来源：http://dali.ppjwa.cn/Article/details/gtlibovlhe.html

Py:   print("Hello, World!")
来源：http://dali.tanke756.top/Article/details/gtjtjlbkvs.html

PHP:  echo "Hello, World!";
来源：http://dali.nanxuanxn.top/Article/details/gtscilerrm.html

JS:   console.log("Hello, World!");
来源：http://dali.hnqzz.top/Article/details/gtkwddmbfx.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzpcqbsts.html

Java: System.out.println("Hello, World!");
来源：http://dali.iojbl.cn/Article/details/gtvwhydcnw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.chenzaomai.com/Article/details/gtfbfnzgis.html

Ruby: puts "Hello, World!"
来源：http://dali.jyoumei.cn/Article/details/gtonbgbqub.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.guannengcc.top/Article/details/gtgdpaikun.html

[A02] 变量声明与赋值
来源：http://dali.9152youxi.cn/Article/details/gtfdkdfcgj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.snrcjt.cn/Article/details/gtffmadaxv.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gtmpubuwzx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhongyouzk.top/Article/details/gtomipwmke.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.iojbl.cn/Article/details/gtczyhbwmk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jianghu66.top/Article/details/gtayqdhndb.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhongyouzk.top/Article/details/gtgaylqpfw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xylfe.cn/Article/details/gtnlommuui.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hnqzz.top/Article/details/gtprtnluko.html

[A03] 常量定义
来源：http://dali.svipenyu.cn/Article/details/gtjmxguxpk.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yueranfly.top/Article/details/gtfuillnxj.html

PHP:  const PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gtnwerpelu.html

JS:   const PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtdofriidr.html

TS:   const PI: number = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtaibossfh.html

Java: static final double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gteradelpt.html

Go:   const PI = 3.14159
来源：http://dali.gzhubu.top/Article/details/gtnlrnxphg.html

Ruby: PI = 3.14159
来源：http://dali.gogol.net.cn/Article/details/gtbothldgh.html

C#:   const double PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtdujhgaat.html

[A04] 判断变量类型
来源：http://dali.zhiwuduotai.top/Article/details/gtxtxsivqu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jlsjyb.cn/Article/details/gtbhhhlslz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.havefunace.top/Article/details/gtpqoitrxx.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yueranfly.top/Article/details/gtrhksbpow.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnukbanq.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.wangshuangyany.cn/Article/details/gtmevzghsn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.fengsongda.top/Article/details/gtxnvlccfs.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.sxryk.cn/Article/details/gtfcaoeqwe.html

C#:   x.GetType().Name; x is int
来源：http://dali.zdqjudy.top/Article/details/gtjigiiejg.html

[A05] 整数除法与取模
来源：http://dali.cqqwz.cn/Article/details/gtnrbelixl.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yongpay.top/Article/details/gtaxeofqjk.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gtinhadfil.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gtzflljmwj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cucudq.cn/Article/details/gttbsqlzfk.html

Java: 7 / 2; 7 % 2
来源：http://dali.sysykeji.top/Article/details/gtualhdzdu.html

Go:   7 / 2; 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gtopftrxaq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gtbprevrig.html

C#:   7 / 2; 7 % 2
来源：http://dali.yj20258.top/Article/details/gtdkfsnpir.html

[A06] 字符串转数字
来源：http://dali.hfpthk.cn/Article/details/gtvqrjabph.html

Py:   int("42"); float("3.14")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnczvhtyx.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.snrcjt.cn/Article/details/gtewojuiua.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yuanzhike.top/Article/details/gtqbozseee.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.c1oappe.top/Article/details/gtayvkmhsn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.ybcxt.top/Article/details/gtzwvhenos.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.316326.xyz/Article/details/gtwhrhfcvd.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.guannengcc.top/Article/details/gtcewmlesf.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.cqqwz.cn/Article/details/gtctzoibue.html

[A07] 数字转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtzdnhqnid.html

Py:   str(42)
来源：http://dali.kuanghao11.cn/Article/details/gtouiyighk.html

PHP:  (string) 42; strval(42)
来源：http://dali.wangshuangyany.cn/Article/details/gtzsivcyto.html

JS:   String(42); (42).toString()
来源：http://dali.shzxlz.cn/Article/details/gtcdbfcpxr.html

TS:   String(42)
来源：http://dali.yj20258888.top/Article/details/gtowsencnw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zdqjudy.top/Article/details/gtfgbmxhia.html

Go:   strconv.Itoa(42)
来源：http://dali.shuidangran.top/Article/details/gtdinpjiyi.html

Ruby: 42.to_s
来源：http://dali.guowangkeji.top/Article/details/gteqfgmjxg.html

C#:   42.ToString()
来源：http://dali.wangdashe.top/Article/details/gtlevprtvv.html

[A08] 取整与四舍五入
来源：http://dali.svipenyu.cn/Article/details/gtrgbpwfxf.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jqgfzy.top/Article/details/gtxurwrfvt.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.aibaodan.cn/Article/details/gtzhevwtne.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.redwolf501.top/Article/details/gtwojxhjgk.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yuxming.cn/Article/details/gtedcvqmpx.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.daria6918.cn/Article/details/gthceumcdi.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnhgzaaq.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.wangshuangyany.cn/Article/details/gtyyagwqgu.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.nanxuanxn.top/Article/details/gtnbgtfrty.html

[A09] 绝对值与最大最小值
来源：http://dali.svipenyu.cn/Article/details/gtgfeyicqa.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yongpay.top/Article/details/gtxwivsdcd.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gtvjtshmhh.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtlshwtkng.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yongpay.top/Article/details/gtkgiwwiom.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gtsvcothvi.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.gaohongyu789.top/Article/details/gtvepkbpit.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.ybcxt.top/Article/details/gtjqebrlws.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtxienomlf.html

[A10] 生成随机数
来源：http://dali.fzhhl.top/Article/details/gtnuqtevdc.html

Py:   import random; random.randint(1, 100)
来源：http://dali.cheryme.top/Article/details/gtienwnygt.html

PHP:  random_int(1, 100);
来源：http://dali.redwolf501.top/Article/details/gtpgrwhfdn.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.snrcjt.cn/Article/details/gtluhdkerm.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shanyushiyangtech.top/Article/details/gthpsizinz.html

Java: new Random().nextInt(100) + 1
来源：http://dali.hywenlv.cn/Article/details/gtkrkwpnhl.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.gzhubu.top/Article/details/gteoxycswb.html

Ruby: rand(1..100)
来源：http://dali.nwbrower.top/Article/details/gtvkrrgfro.html

C#:   new Random().Next(1, 101)
来源：http://dali.gotoacloud.top/Article/details/gtpsxjsify.html

[A11] 条件表达式（三元）
来源：http://dali.jinqigufen.top/Article/details/gtilrxyqsl.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwclatzqv.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hnqzz.top/Article/details/gtoldzoaan.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jinqigufen.top/Article/details/gtyyuingou.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.birdmap.top/Article/details/gtsgrsrsuk.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhixingplan.top/Article/details/gtrfarkovb.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcgrxeui.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.fzhhl.top/Article/details/gtfhkfmuoo.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.pengpengdd.cyou/Article/details/gtakcluoue.html

[A12] 字符串插值 / 格式化
来源：http://dali.jlsjyb.cn/Article/details/gtttzovrqv.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.pengpengdd.cyou/Article/details/gtsjoppjny.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.chenlongwang.top/Article/details/gtzuysmkxh.html

JS:   `Hello, ${name}!`
来源：http://dali.cdnleiting.top/Article/details/gtbnueweux.html

TS:   `Hello, ${name}!`
来源：http://dali.fzhhl.top/Article/details/gthdbpdknp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.tian-w.cn/Article/details/gtsvirxgpy.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtzreveqkr.html

Ruby: "Hello, #{name}!"
来源：http://dali.nanxinkj.top/Article/details/gtagtlrpel.html

C#:   $"Hello, {name}!"
来源：http://dali.chenlongwang.top/Article/details/gtlmhjunsn.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.sufxvd.cn/Article/details/gtjfecbtqk.html

Py:   "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gtcxszztzu.html

PHP:  "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gtbmonllic.html

JS:   "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gtrijrmgmt.html

TS:   "第一行\n第二行"
来源：http://dali.pengpengdd.cyou/Article/details/gtcnevefzh.html


<!-- 参考信息 -->