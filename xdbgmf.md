代发 wailian999

[U83] JS：ES Module 导入导出
来源：http://dali.jiagoushi.top/Article/details/gtrokxptcp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.pycfn.com/Article/details/gtihlewtpf.html

[U84] JS：CommonJS 写法
来源：http://dali.feifeiyinyue.top/Article/details/gttnvhurhq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhixingplan.top/Article/details/gtksruiaem.html

[U85] JS：可选链
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcdmwiti.html

a?.b?.c
来源：http://dali.hnxiangtu.top/Article/details/gtnapdojed.html

[U86] JS：空值合并
来源：http://dali.zycfv.cn/Article/details/gtrvrvlkoe.html

a ?? b
来源：http://dali.yj20258.top/Article/details/gtlyuvzhjg.html

[U87] JS：解构默认值
来源：http://dali.guannengcc.top/Article/details/gthqaxltnc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jinqigufen.top/Article/details/gtipecuues.html

[U88] JS：对象展开合并
来源：http://dali.ehwqpu.com/Article/details/gtozdrwhkp.html

{ ...a, ...b }
来源：http://dali.kuanghao11.cn/Article/details/gthjkbkggg.html

[U89] JS：数组去重
来源：http://dali.hammf.cn/Article/details/gttvgjzxwf.html

[...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gtiafpkzcu.html

[U90] JS：数字数组排序
来源：http://dali.hywenlv.cn/Article/details/gtokssedsv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.daria6918.cn/Article/details/gtuxsaiyiy.html

[U91] JS：对象键值遍历
来源：http://dali.haohaochexian.top/Article/details/gtojfyecqp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.aibaodan.cn/Article/details/gtjnkkilvj.html

[U92] JS：深拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gtqlaiuaxu.html

structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gtwwqqbnad.html

[U93] JS：模板字符串
来源：http://dali.gogol.net.cn/Article/details/gtfywdavpi.html

`共 ${n} 条`
来源：http://dali.hammf.cn/Article/details/gtsxdvbllx.html

[U94] JS：箭头函数
来源：http://dali.andypj.xyz/Article/details/gtpejotbig.html

const double = x => x * 2;
来源：http://dali.aizwys.cn/Article/details/gtfiwgyroy.html

[U95] JS：Promise 包装
来源：http://dali.fzhhl.top/Article/details/gteuxwabxm.html

new Promise((resolve, reject) => {})
来源：http://dali.pycfn.com/Article/details/gtizizuxic.html

[U96] JS：async/await 与异常
来源：http://dali.pengpengdd.cyou/Article/details/gtjvshfbdb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtcoynmisq.html

[U97] JS：并发请求
来源：http://dali.xziqi.cn/Article/details/gtxfcxaavm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gtqrasdwwa.html

[U98] JS：fetch 带 JSON
来源：http://dali.svipenyu.cn/Article/details/gtvtvkaljh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.vqdsnc.cn/Article/details/gtrjojblni.html

[U99] JS：事件监听
来源：http://dali.snrcjt.cn/Article/details/gtcgnbioei.html

el.addEventListener("click", e => {})
来源：http://dali.nwbrower.top/Article/details/gtylrzrgye.html

[U100] JS：DOM 查询
来源：http://dali.feifeiyinyue.top/Article/details/gtdqfihfwd.html

document.querySelector(".item")
来源：http://dali.xziqi.cn/Article/details/gtiobjnmuo.html

[U101] JS：classList 操作
来源：http://dali.hnxiangtu.top/Article/details/gtgvnxbysx.html

el.classList.toggle("active")
来源：http://dali.sweek.top/Article/details/gtifmfdwgs.html

[U102] JS：本地存储
来源：http://dali.yonumen.top/Article/details/gtlnghqfik.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.cucudq.cn/Article/details/gtfirfnbyh.html

[U103] JS：定时器
来源：http://dali.birdmap.top/Article/details/gtbyrflxwd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.nwbrower.top/Article/details/gtuizvbewo.html

[U104] JS：防抖
来源：http://dali.meibo888.top/Article/details/gtasmknsxd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gtmbdgxhnb.html

[U105] JS：节流
来源：http://dali.zhixingplan.top/Article/details/gtiizfqlhh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.c1oappe.top/Article/details/gtgpsmtqzx.html

[U106] JS：日期格式化
来源：http://dali.haohaochexian.top/Article/details/gtcolepufo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yanxiufei.cn/Article/details/gtrwwgxbcx.html

[U107] JS：数字千分位
来源：http://dali.gogol.net.cn/Article/details/gtzbnfxdid.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sysykeji.top/Article/details/gttsbakupu.html

[U108] JS：随机整数
来源：http://dali.yueranfly.top/Article/details/gtzgtwcdih.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yanxiufei.cn/Article/details/gtoguzgdfp.html

[U109] JS：数组分组
来源：http://dali.aibaodan.cn/Article/details/gtovtlxpnh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yanxiufei.cn/Article/details/gtbmawqkgp.html

[U110] JS：数组分块
来源：http://dali.shuidangran.top/Article/details/gtzjavsvbq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zdqjudy.top/Article/details/gtohjpqcam.html

[U111] JS：对象转 Map
来源：http://dali.yangfankeji.com/Article/details/gtzfwndfzn.html

new Map(Object.entries(obj))
来源：http://dali.dianchejie.cn/Article/details/gtoaopfqog.html

[U112] JS：字符串补位
来源：http://dali.tian-w.cn/Article/details/gtlgrxejfv.html

"7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtgvbxaqna.html

[U113] JS：正则替换全部
来源：http://dali.fzhhl.top/Article/details/gtlsrjnmsv.html

s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtalicrdio.html

[U114] JS：JSON 深比较
来源：http://dali.cheryme.top/Article/details/gtfolcujls.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtblgkwyru.html

[U115] JS：生成 UUID
来源：http://dali.ppjwa.cn/Article/details/gtsggqccvz.html

crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gtzrjwpbzz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.sweek.top/Article/details/gtneclqrur.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gttcdtxbrq.html

[U117] JS：单元测试
来源：http://dali.haohaochexian.top/Article/details/gtuiszqekg.html

npm i -D vitest;  npx vitest
来源：http://dali.hammf.cn/Article/details/gtuqrkalou.html

[U118] JS：开发服务器
来源：http://dali.hnqzz.top/Article/details/gtziomgsqq.html

npm i -D vite;  npx vite
来源：http://dali.mhx1999.top/Article/details/gtevwdbcgf.html

[U119] JS：生产构建
来源：http://dali.xylfe.cn/Article/details/gtudsmepyb.html

npx vite build
来源：http://dali.yongpay.top/Article/details/gtieisuqpc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.aizwys.cn/Article/details/gtzepeonlv.html

import.meta.env.VITE_API_URL
来源：http://dali.iojbl.cn/Article/details/gtgyfalpsn.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqnepkgdy.html

统计汇总
来源：http://dali.pycfn.com/Article/details/gtzgigpnvs.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtcyjohcgy.html

按语言统计（条）：
来源：http://dali.cucudq.cn/Article/details/gtrzovkqem.html

Python ......... 252
来源：http://dali.havefunace.top/Article/details/gteahatsxk.html

PHP ............ 252
来源：http://dali.dianchejie.cn/Article/details/gtnxwafilw.html

JavaScript ..... 252
来源：http://dali.tian-w.cn/Article/details/gtgjslvbbj.html

TypeScript ..... 212
来源：http://dali.cucudq.cn/Article/details/gtzpqqrhzl.html

Java ........... 212
来源：http://dali.jiagoushi.top/Article/details/gtjogdaiqb.html

Go ............. 212
来源：http://dali.guowangkeji.top/Article/details/gtmcknjfnu.html

Ruby ........... 212
来源：http://dali.xuanzx.com/Article/details/gtfmlvslps.html

C# ............. 212
来源：http://dali.iojbl.cn/Article/details/gtqpgqtjhz.html

C .............. 30
来源：http://dali.ppjwa.cn/Article/details/gtcdxyjqhc.html

C++ ............ 30
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthstgwlle.html

SQL ............ 90
来源：http://dali.hfpthk.cn/Article/details/gttpalspjb.html

Bash ........... 80
来源：http://dali.cheryme.top/Article/details/gtbogatpvd.html

Kotlin ......... 15
来源：http://dali.quarkkingdee.top/Article/details/gtxbtfxzgl.html

Swift .......... 15
来源：http://dali.sxryk.cn/Article/details/gtglchkaab.html

Lua ............ 10
来源：http://dali.zdqjudy.top/Article/details/gticmjhyas.html

Perl ........... 10
来源：http://dali.jlsjyb.cn/Article/details/gtbzlemtea.html

Scala .......... 10
来源：http://dali.fzhhl.top/Article/details/gtvvzivayk.html

------------------------------------
来源：http://dali.fzhhl.top/Article/details/gtmlljjjyu.html

合计 ........... 2106 条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahjgvjyb.html

按章节统计：
来源：http://dali.dianchejie.cn/Article/details/gtvuzohiic.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yonumen.top/Article/details/gtvhzufuvg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.nwbrower.top/Article/details/gtwbnhhzpd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hnxiangtu.top/Article/details/gtolubnyoj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzetioay.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.guannengcc.top/Article/details/gtkizfmwui.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.sweek.top/Article/details/gttbypkalf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xinyue.icu/Article/details/gtohlvimgc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cheryme.top/Article/details/gtpzyxykcc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gtifcasmwz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yuxming.cn/Article/details/gtmnnubsya.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gtrcfbcwkf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gtoxztuqsi.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gtiifpdgqo.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhengqikj.top/Article/details/gttiazsamr.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.9152youxi.cn/Article/details/gtblijiqnt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gttffkzlmj.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gtekvnruqw.html

R Bash 专题                             80
来源：http://dali.bjfxy.top/Article/details/gtqpirkxvq.html

S C / C++ 专题                          60
来源：http://dali.iojbl.cn/Article/details/gtwythwzeu.html

T 其他语言补充                          60
来源：http://dali.c1oappe.top/Article/details/gtvqqjxfjc.html

U 高频实用片段                         120
来源：http://dali.yueranfly.top/Article/details/gtvdnztsor.html

------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gtwisojkad.html

合计                                  2106 条
来源：http://dali.yj20258.top/Article/details/gtfcggbpzj.html

--------------------------------------------------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gtaltwitpe.html

使用提醒
来源：http://dali.gotoacloud.top/Article/details/gtrwwocizt.html

--------------------------------------------------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gtkyfvjbbn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhixingplan.top/Article/details/gtzizzjnep.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cqqwz.cn/Article/details/gtolwxmahg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.iojbl.cn/Article/details/gthupykisz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ehwqpu.com/Article/details/gtxunwlezk.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xylfe.cn/Article/details/gtmqxqrqct.html

—— 文件结束 ——
来源：http://dali.jianghu66.top/Article/details/gtdbyrqdxu.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtpoudqqxn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.fengsongda.top/Article/details/gtkdifvkor.html

Common Programming Examples Cheat Book
来源：http://dali.guannengcc.top/Article/details/gtosizpbkg.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtaovmbtxy.html

【收录内容】
来源：http://dali.bjfxy.top/Article/details/gtvdesycjs.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.9152youxi.cn/Article/details/gtoyztiqdk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.sysykeji.top/Article/details/gtpnadpshc.html

SQL · Bash · C · C++
来源：http://dali.daxiang520.top/Article/details/gtoehwlgdi.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yanxiufei.cn/Article/details/gtjekbevcz.html

【使用说明】
来源：http://dali.cdnleiting.top/Article/details/gtnnoeorfq.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.birdmap.top/Article/details/gtmzhyjpow.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrxuipqf.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xziqi.cn/Article/details/gtmrdsdvmx.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.gaohongyu789.top/Article/details/gtlojxqmvx.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ydzc1.top/Article/details/gtdezpvhfv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.0kj1m.cn/Article/details/gtwylcclpb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.chenlongwang.top/Article/details/gtstlwefyy.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.pengpengdd.cyou/Article/details/gtmlllizob.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.mhx1999.top/Article/details/gtcdwmckml.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hnxiangtu.top/Article/details/gtrrrkmrdb.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zdqjudy.top/Article/details/gtnxihtszj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.vqdsnc.cn/Article/details/gtuudjcsbv.html

【文件统计】
来源：http://dali.meibo888.top/Article/details/gtxjsingeh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yuxming.cn/Article/details/gtqcwbsbny.html

--------------------------------------------------------------------------------
来源：http://dali.xziqi.cn/Article/details/gtkzifuvtz.html

目  录
来源：http://dali.hnxiangtu.top/Article/details/gtvpisongq.html

--------------------------------------------------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gteejpwosj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cheryme.top/Article/details/gtetzwqbjb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hywenlv.cn/Article/details/gtmuazyeap.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhongyouzk.top/Article/details/gtoyvhvsho.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xinyue.icu/Article/details/gtawlvuaor.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtyiynkbfu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtpwjcqltb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtentrbtef.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.tanke756.top/Article/details/gtndlgavtb.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtpltfiyjo.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gtglvxcayz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gtkfyvywst.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.shuidangran.top/Article/details/gtxbdifdtz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtyfaybqwb.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jqgfzy.top/Article/details/gthaflbymn.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.nanxuanxn.top/Article/details/gtvqhaxykz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.meibo888.top/Article/details/gtlfcyatqo.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cashguo.top/Article/details/gtetcdizgd.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.gotoacloud.top/Article/details/gtempclsxg.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.gotoacloud.top/Article/details/gtfcyfvwqu.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yanxiufei.cn/Article/details/gtvgaxvbiy.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.daxiang520.top/Article/details/gtkazoripn.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gttpkisyoh.html

A. 基础语法与类型
来源：http://dali.nanxuanxn.top/Article/details/gtczpafgkr.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtdmaamlwn.html

[A01] Hello World
来源：http://dali.yonumen.top/Article/details/gtbotxyzgq.html

Py:   print("Hello, World!")
来源：http://dali.gaohongyu789.top/Article/details/gtufsfxfpa.html

PHP:  echo "Hello, World!";
来源：http://dali.zhiwuduotai.top/Article/details/gthifvykin.html

JS:   console.log("Hello, World!");
来源：http://dali.hammf.cn/Article/details/gtlrpcjymu.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yangfankeji.com/Article/details/gtpvafnahg.html

Java: System.out.println("Hello, World!");
来源：http://dali.jqgfzy.top/Article/details/gtyknotzyw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ydzc1.top/Article/details/gtlrgqhcaw.html

Ruby: puts "Hello, World!"
来源：http://dali.xinyue.icu/Article/details/gtmywgpibp.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.havefunace.top/Article/details/gtcrnvcwak.html

[A02] 变量声明与赋值
来源：http://dali.9152youxi.cn/Article/details/gtsziyunos.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.dianchejie.cn/Article/details/gtxlfbchkj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.redwolf501.top/Article/details/gtnhidcnrp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hnqzz.top/Article/details/gtctiwlswx.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xuanzx.com/Article/details/gtscylzpjx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.dashuyun.cn/Article/details/gtmivylwvf.html

Go:   name := "Alex"; age := 20
来源：http://dali.chenjidiqi.icu/Article/details/gtbvorazhn.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hongshengwenyu.top/Article/details/gtlemdwptv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzldauem.html

[A03] 常量定义
来源：http://dali.yueranfly.top/Article/details/gteglnqmgq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cucudq.cn/Article/details/gtlnniqsme.html

PHP:  const PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtedfelhmo.html

JS:   const PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtbwbvwrlc.html

TS:   const PI: number = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtrpgxncir.html

Java: static final double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdkgvgll.html

Go:   const PI = 3.14159
来源：http://dali.xuanzx.com/Article/details/gtlzqvuofx.html

Ruby: PI = 3.14159
来源：http://dali.jiagoushi.top/Article/details/gtcmgjymnz.html

C#:   const double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtdzyfgpyu.html

[A04] 判断变量类型
来源：http://dali.havefunace.top/Article/details/gtnotiubuu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.dianchejie.cn/Article/details/gtcmtrcsad.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jqgfzy.top/Article/details/gttkgoxqyi.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jinqigufen.top/Article/details/gtycsyhxmx.html

TS:   typeof x; x instanceof Date
来源：http://dali.gogol.net.cn/Article/details/gtwhotunbv.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.guannengcc.top/Article/details/gtvouxxzgf.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jqgfzy.top/Article/details/gtzdttkfyn.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.haohaochexian.top/Article/details/gtvgqamgiy.html

C#:   x.GetType().Name; x is int
来源：http://dali.birdmap.top/Article/details/gthoyhjyig.html

[A05] 整数除法与取模
来源：http://dali.xuanzx.com/Article/details/gtbpdpeclo.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.tianlin.xyz/Article/details/gtddgsbxwl.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gtejoyqqdn.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtbwwavvam.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.havefunace.top/Article/details/gtllqylfmv.html

Java: 7 / 2; 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gtnybisuow.html

Go:   7 / 2; 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gtreqmycla.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtbqqhcius.html

C#:   7 / 2; 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gtzbnawtsy.html

[A06] 字符串转数字
来源：http://dali.jlsjyb.cn/Article/details/gtzbutvkid.html

Py:   int("42"); float("3.14")
来源：http://dali.sxryk.cn/Article/details/gtjiwohazu.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.sufxvd.cn/Article/details/gtvvnfwhca.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yj20258888.top/Article/details/gttoomlgay.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjklougzy.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.xziqi.cn/Article/details/gtldvhngxh.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hammf.cn/Article/details/gteslzogvy.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.cashguo.top/Article/details/gtvpserslm.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yueranfly.top/Article/details/gtlqvjnjqh.html

[A07] 数字转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtlmoajcta.html

Py:   str(42)
来源：http://dali.hammf.cn/Article/details/gttpexgssr.html

PHP:  (string) 42; strval(42)
来源：http://dali.shzxlz.cn/Article/details/gttbytnaeu.html

JS:   String(42); (42).toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpkzjkpq.html

TS:   String(42)
来源：http://dali.feifeiyinyue.top/Article/details/gtaucjjwqf.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.wangshuangyany.cn/Article/details/gtmwjphiqn.html

Go:   strconv.Itoa(42)
来源：http://dali.tianlin.xyz/Article/details/gtbeowcyue.html

Ruby: 42.to_s
来源：http://dali.cdnleiting.top/Article/details/gtqxmccarx.html

C#:   42.ToString()
来源：http://dali.jlsjyb.cn/Article/details/gtkoqzladr.html

[A08] 取整与四舍五入
来源：http://dali.gotoacloud.top/Article/details/gtygjuyzqg.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.snrcjt.cn/Article/details/gtnasigqor.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.c1oappe.top/Article/details/gtgldrpwln.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jinghuilouyu.cn/Article/details/gtysmbcbyv.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpmhjeoy.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.xinyue.icu/Article/details/gtuhjxbhuh.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.birdmap.top/Article/details/gtirxcfkgv.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yvedp.cn/Article/details/gtwdpowuix.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgwissfe.html

[A09] 绝对值与最大最小值
来源：http://dali.fengsongda.top/Article/details/gttsedwtwj.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ydzc1.top/Article/details/gthkllskoj.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gzhubu.top/Article/details/gtoagjyutq.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtexnyvdym.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.aizwys.cn/Article/details/gtnqayyzfm.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtzfydulyj.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.tian-w.cn/Article/details/gtcrcidefj.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.ybcxt.top/Article/details/gtwwhfnwfz.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gtldgfvmce.html

[A10] 生成随机数
来源：http://dali.c1oappe.top/Article/details/gtckupcurh.html

Py:   import random; random.randint(1, 100)
来源：http://dali.guowangkeji.top/Article/details/gtdeaaktev.html

PHP:  random_int(1, 100);
来源：http://dali.hammf.cn/Article/details/gthhrlhded.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.andypj.xyz/Article/details/gtalooekuj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hysaishi.cn/Article/details/gtekskpgty.html

Java: new Random().nextInt(100) + 1
来源：http://dali.quarkkingdee.top/Article/details/gtmapotsex.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.gaohongyu789.top/Article/details/gtfmdcbzds.html

Ruby: rand(1..100)
来源：http://dali.yuanzhike.top/Article/details/gtnrfhihko.html

C#:   new Random().Next(1, 101)
来源：http://dali.jianghu66.top/Article/details/gtecvpwqko.html

[A11] 条件表达式（三元）
来源：http://dali.hongshengwenyu.top/Article/details/gtvxlszrnm.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.andypj.xyz/Article/details/gtdqzfwiiq.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.redwolf501.top/Article/details/gtcytzjath.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yanxiufei.cn/Article/details/gttiwexmbs.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jinqigufen.top/Article/details/gtocoipddf.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.9152youxi.cn/Article/details/gtycnpawnr.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.hysaishi.cn/Article/details/gtmulmuauc.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.nanxinkj.top/Article/details/gtxkffvlbq.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.xuetiantiany.cn/Article/details/gtifnrjycr.html

[A12] 字符串插值 / 格式化
来源：http://dali.jqgfzy.top/Article/details/gtwurofvmg.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.ehwqpu.com/Article/details/gtuazcgmqi.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.ppjwa.cn/Article/details/gtprlujhew.html

JS:   `Hello, ${name}!`
来源：http://dali.meibo888.top/Article/details/gtsxmlycwj.html

TS:   `Hello, ${name}!`
来源：http://dali.daria6918.cn/Article/details/gttaisvonx.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.bjfxy.top/Article/details/gtkkowqpev.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.shuidangran.top/Article/details/gtuddqghof.html

Ruby: "Hello, #{name}!"
来源：http://dali.chenlongwang.top/Article/details/gtgimbsxcs.html

C#:   $"Hello, {name}!"
来源：http://dali.sufxvd.cn/Article/details/gtxxssysfg.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.mhx1999.top/Article/details/gtpxyrairr.html

Py:   "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gttbklhmup.html

PHP:  "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gtwxwounnr.html

JS:   "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gtfcvjnsme.html

TS:   "第一行\n第二行"
来源：http://dali.guowangkeji.top/Article/details/gtmovihhke.html

Java: "第一行\n第二行"
来源：http://dali.wangdashe.top/Article/details/gthezjolww.html

Go:   "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gtxhikhhbe.html

Ruby: "第一行\n第二行"
来源：http://dali.jinqigufen.top/Article/details/gtahfmgyqu.html

C#:   "第一行\n第二行"
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpwcmrxl.html


<!-- 参考信息 -->