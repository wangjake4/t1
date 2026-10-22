代发 wailian999

[U83] JS：ES Module 导入导出
来源：http://dali.nanxuanxn.top/Article/details/gt2frlvffzc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.havefunace.top/Article/details/gt2xozajizk.html

[U84] JS：CommonJS 写法
来源：http://dali.daxiang520.top/Article/details/gt2inkcedjk.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhongyouzk.top/Article/details/gt2hmsbmygh.html

[U85] JS：可选链
来源：http://dali.9152youxi.cn/Article/details/gt2npscvlwm.html

a?.b?.c
来源：http://dali.hywenlv.cn/Article/details/gt2buwylkqw.html

[U86] JS：空值合并
来源：http://dali.fengsongda.top/Article/details/gt2bonnfivz.html

a ?? b
来源：http://dali.aizwys.cn/Article/details/gt2awomofee.html

[U87] JS：解构默认值
来源：http://dali.sweek.top/Article/details/gt2dtfpxnfw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.birdmap.top/Article/details/gt2jyubcrgs.html

[U88] JS：对象展开合并
来源：http://dali.hywenlv.cn/Article/details/gt2jamdromz.html

{ ...a, ...b }
来源：http://dali.smart0.xyz/Article/details/gt2folmcnez.html

[U89] JS：数组去重
来源：http://dali.andypj.xyz/Article/details/gt2kkfrjxxt.html

[...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gt2kpnhyzbu.html

[U90] JS：数字数组排序
来源：http://dali.hammf.cn/Article/details/gt2upjdmkwx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gt2ojdecgpt.html

[U91] JS：对象键值遍历
来源：http://dali.shzxlz.cn/Article/details/gt2hntejxzr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gaohongyu789.top/Article/details/gt2iqmgilyn.html

[U92] JS：深拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gnnokxsh.html

structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gt2njwbcbbw.html

[U93] JS：模板字符串
来源：http://dali.tian-w.cn/Article/details/gt2kztfsunj.html

`共 ${n} 条`
来源：http://dali.bjfxy.top/Article/details/gt2rfdruqfa.html

[U94] JS：箭头函数
来源：http://dali.sysykeji.top/Article/details/gt2wykfwzdz.html

const double = x => x * 2;
来源：http://dali.cucudq.cn/Article/details/gt2nwqfstft.html

[U95] JS：Promise 包装
来源：http://dali.9152youxi.cn/Article/details/gt2pwgikodi.html

new Promise((resolve, reject) => {})
来源：http://dali.shangyingyoupin.top/Article/details/gt2jzkqhetx.html

[U96] JS：async/await 与异常
来源：http://dali.birdmap.top/Article/details/gt2imntdaox.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gt2uguafzio.html

[U97] JS：并发请求
来源：http://dali.yanxiufei.cn/Article/details/gt2jgkblglb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gt2xkirbajk.html

[U98] JS：fetch 带 JSON
来源：http://dali.sysykeji.top/Article/details/gt2nbbwqdku.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.snrcjt.cn/Article/details/gt2lgyfznxq.html

[U99] JS：事件监听
来源：http://dali.andypj.xyz/Article/details/gt2vhhmmtim.html

el.addEventListener("click", e => {})
来源：http://dali.316326.xyz/Article/details/gt2cxdunggv.html

[U100] JS：DOM 查询
来源：http://dali.hfpthk.cn/Article/details/gt2gdgkeqrz.html

document.querySelector(".item")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tqcuijmp.html

[U101] JS：classList 操作
来源：http://dali.jyoumei.cn/Article/details/gt2cmwisqxz.html

el.classList.toggle("active")
来源：http://dali.jyoumei.cn/Article/details/gt2mgglgvgj.html

[U102] JS：本地存储
来源：http://dali.pengpengdd.cyou/Article/details/gt2armoscgt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.iojbl.cn/Article/details/gt2yzzguzam.html

[U103] JS：定时器
来源：http://dali.yueranfly.top/Article/details/gt2phukfokc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shuidangran.top/Article/details/gt2elrtymin.html

[U104] JS：防抖
来源：http://dali.jyoumei.cn/Article/details/gt2pbjmdoxd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xvmagkhe.html

[U105] JS：节流
来源：http://dali.svipenyu.cn/Article/details/gt2vdzampsz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jinqigufen.top/Article/details/gt2dwptsjlw.html

[U106] JS：日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gt2vvdblzqw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ybcxt.top/Article/details/gt2kfqlvazt.html

[U107] JS：数字千分位
来源：http://dali.dianchejie.cn/Article/details/gt2jenvsgvt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.daxiang520.top/Article/details/gt2xufrmajh.html

[U108] JS：随机整数
来源：http://dali.xziqi.cn/Article/details/gt2drigxgmw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.chenlongwang.top/Article/details/gt2wbcayqdh.html

[U109] JS：数组分组
来源：http://dali.nanxinkj.top/Article/details/gt2dkntmtxb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hfpthk.cn/Article/details/gt2xnomrnlc.html

[U110] JS：数组分块
来源：http://dali.cqqwz.cn/Article/details/gt2xhuswlvm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jqgfzy.top/Article/details/gt2mdfykngy.html

[U111] JS：对象转 Map
来源：http://dali.yongpay.top/Article/details/gt2ssdumryc.html

new Map(Object.entries(obj))
来源：http://dali.quarkkingdee.top/Article/details/gt2rpamavei.html

[U112] JS：字符串补位
来源：http://dali.ppjwa.cn/Article/details/gt2jkabaqon.html

"7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gt2stisxssi.html

[U113] JS：正则替换全部
来源：http://dali.meibo888.top/Article/details/gt2ufbnohaq.html

s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2avxtuwjc.html

[U114] JS：JSON 深比较
来源：http://dali.gaohongyu789.top/Article/details/gt2eejayzfz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cqqwz.cn/Article/details/gt2iryhqhoq.html

[U115] JS：生成 UUID
来源：http://dali.xylfe.cn/Article/details/gt2lgpkqxet.html

crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gt2isvwrovh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.daxiang520.top/Article/details/gt2ofunjtjn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bkuyimcs.html

[U117] JS：单元测试
来源：http://dali.hammf.cn/Article/details/gt2rnsszbub.html

npm i -D vitest;  npx vitest
来源：http://dali.tanke756.top/Article/details/gt2kwibwmdn.html

[U118] JS：开发服务器
来源：http://dali.aibaodan.cn/Article/details/gt2jnofdkzw.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2outowarl.html

[U119] JS：生产构建
来源：http://dali.9152youxi.cn/Article/details/gt2oftbtsmh.html

npx vite build
来源：http://dali.sxryk.cn/Article/details/gt2vexptvth.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.wangshuangyany.cn/Article/details/gt2sxmtpoik.html

import.meta.env.VITE_API_URL
来源：http://dali.svipenyu.cn/Article/details/gt2cetisbgx.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2jdmugllh.html

统计汇总
来源：http://dali.yueranfly.top/Article/details/gt2vilbdtxl.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2bbmhtoal.html

按语言统计（条）：
来源：http://dali.hfpthk.cn/Article/details/gt2hreydkis.html

Python ......... 252
来源：http://dali.jinqigufen.top/Article/details/gt2sbryzlmn.html

PHP ............ 252
来源：http://dali.ybcxt.top/Article/details/gt2ayagrhau.html

JavaScript ..... 252
来源：http://dali.yanxiufei.cn/Article/details/gt2jpsrgmvp.html

TypeScript ..... 212
来源：http://dali.0kj1m.cn/Article/details/gt2xmkqcfvz.html

Java ........... 212
来源：http://dali.jianghu66.top/Article/details/gt2wnzeqitz.html

Go ............. 212
来源：http://dali.hammf.cn/Article/details/gt2tzyfavrw.html

Ruby ........... 212
来源：http://dali.ivvv.top/Article/details/gt2qyuxnfmi.html

C# ............. 212
来源：http://dali.xuetiantiany.cn/Article/details/gt2ouehsckf.html

C .............. 30
来源：http://dali.shuidangran.top/Article/details/gt2uzgeedhv.html

C++ ............ 30
来源：http://dali.nwbrower.top/Article/details/gt2wreyefjv.html

SQL ............ 90
来源：http://dali.iojbl.cn/Article/details/gt2dqqtvkxu.html

Bash ........... 80
来源：http://dali.zhoulong.xyz/Article/details/gt2kznyocqt.html

Kotlin ......... 15
来源：http://dali.bjfxy.top/Article/details/gt2bpcyaeum.html

Swift .......... 15
来源：http://dali.wangdashe.top/Article/details/gt2pxifscuo.html

Lua ............ 10
来源：http://dali.yvedp.cn/Article/details/gt2chnlukzk.html

Perl ........... 10
来源：http://dali.fengsongda.top/Article/details/gt2wiijqiwy.html

Scala .......... 10
来源：http://dali.dashuyun.cn/Article/details/gt2bsprkkqr.html

------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gt2fhgbmibd.html

合计 ........... 2106 条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uylgbgdy.html

按章节统计：
来源：http://dali.ybcxt.top/Article/details/gt2ohvbdjeg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.wangdashe.top/Article/details/gt2diafpujy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gt2gctqlfzq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gt2amegjxjh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gogol.net.cn/Article/details/gt2agujkaes.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.chenjidiqi.icu/Article/details/gt2ieiyzvrn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cucudq.cn/Article/details/gt2wfvhsqym.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yongpay.top/Article/details/gt2ixvsyokc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.9152youxi.cn/Article/details/gt2omeccmoz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.iojbl.cn/Article/details/gt2hpiiprxk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.fengsongda.top/Article/details/gt2ofibobio.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gt2rrhekqiz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gt2bxsruknj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gt2ecuytgqt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shzxlz.cn/Article/details/gt2cvnhcbuk.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.birdmap.top/Article/details/gt2gyrbkwjg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gt2ffovswzm.html

Q SQL 专题                              90
来源：http://dali.zhixingplan.top/Article/details/gt2oyfflxia.html

R Bash 专题                             80
来源：http://dali.jqgfzy.top/Article/details/gt2siwcrvng.html

S C / C++ 专题                          60
来源：http://dali.yonumen.top/Article/details/gt2ksyrwnqk.html

T 其他语言补充                          60
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dfteskkb.html

U 高频实用片段                         120
来源：http://dali.hammf.cn/Article/details/gt2kbkyexew.html

------------------------------------
来源：http://dali.hnqzz.top/Article/details/gt2daptxnnb.html

合计                                  2106 条
来源：http://dali.jqgufenzy.top/Article/details/gt2zatsurtn.html

--------------------------------------------------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fwkcfvjq.html

使用提醒
来源：http://dali.cashguo.top/Article/details/gt2cxjggxgf.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gt2wxzrehuj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.nanxinkj.top/Article/details/gt2hpkqjxux.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ppjwa.cn/Article/details/gt2snouaqll.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xinyue.icu/Article/details/gt2regxmigo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xinyue.icu/Article/details/gt2rycxaqhu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ucyzauyc.html

—— 文件结束 ——
来源：http://dali.zhoulong.xyz/Article/details/gt2voweahod.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2eziocthq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.daxiang520.top/Article/details/gt2cmkozwjv.html

Common Programming Examples Cheat Book
来源：http://dali.jyoumei.cn/Article/details/gt2plszorwg.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2btmzuito.html

【收录内容】
来源：http://dali.c1oappe.top/Article/details/gt2npwgwoqa.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.sysykeji.top/Article/details/gt2menlxskk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.0kj1m.cn/Article/details/gt2jsuoncls.html

SQL · Bash · C · C++
来源：http://dali.fengsongda.top/Article/details/gt2eeqlpycv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.vqdsnc.cn/Article/details/gt2rhnnulcp.html

【使用说明】
来源：http://dali.snrcjt.cn/Article/details/gt2mxwolbmv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.chenjidiqi.icu/Article/details/gt2mqdnsree.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.haohaochexian.top/Article/details/gt2gpmckrrr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.shangyingyoupin.top/Article/details/gt2rnbdzmik.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zdqjudy.top/Article/details/gt2mooxyyoy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.kuanghao11.cn/Article/details/gt2hxkvtsvo.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhongyouzk.top/Article/details/gt2brypygrx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jlsjyb.cn/Article/details/gt2xgbbthnc.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.sufxvd.cn/Article/details/gt2sugykjou.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zdrugrpa.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.chenzaomai.com/Article/details/gt2qcwpkqhm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jlsjyb.cn/Article/details/gt2murbiwoj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.gotoacloud.top/Article/details/gt2fqextawe.html

【文件统计】
来源：http://dali.ehwqpu.com/Article/details/gt2obnswajt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ehwqpu.com/Article/details/gt2iusmclrs.html

--------------------------------------------------------------------------------
来源：http://dali.bjfxy.top/Article/details/gt2muuhhdtw.html

目  录
来源：http://dali.xylfe.cn/Article/details/gt2ojnioimh.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tfkkoggt.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.daxiang520.top/Article/details/gt2teoxbrvb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.fengsongda.top/Article/details/gt2cdeoyysy.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.bjfxy.top/Article/details/gt2oymgowkh.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.sxryk.cn/Article/details/gt2bydbkbbk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2blpyjphf.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.ybcxt.top/Article/details/gt2vvfumltn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xziqi.cn/Article/details/gt2tkxfgoyn.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2poqhyyyr.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.birdmap.top/Article/details/gt2sseuuujg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhengqikj.top/Article/details/gt2anbcfrjr.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ulaykpla.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rntapgla.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2danvzhvg.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.ivvv.top/Article/details/gt2czktubqv.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jqgfzy.top/Article/details/gt2nhfrfgrw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2trphgzgt.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.chenzaomai.com/Article/details/gt2wpglefuo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yj20258.top/Article/details/gt2yxemujtj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xinyue.icu/Article/details/gt2zjlcnyjb.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yanxiufei.cn/Article/details/gt2zfjertmt.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.cdnleiting.top/Article/details/gt2ockpuyla.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2qpycmtux.html

A. 基础语法与类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ahotkvlj.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2bmmlehae.html

[A01] Hello World
来源：http://dali.iojbl.cn/Article/details/gt2gtlhidwb.html

Py:   print("Hello, World!")
来源：http://dali.9152youxi.cn/Article/details/gt2bzzakcrb.html

PHP:  echo "Hello, World!";
来源：http://dali.xylfe.cn/Article/details/gt2vtzuifcr.html

JS:   console.log("Hello, World!");
来源：http://dali.havefunace.top/Article/details/gt2xnbmznid.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yj202588.top/Article/details/gt2opzyzssw.html

Java: System.out.println("Hello, World!");
来源：http://dali.mhx1999.top/Article/details/gt2ltxjzayg.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.svipenyu.cn/Article/details/gt2rjsmvpft.html

Ruby: puts "Hello, World!"
来源：http://dali.tian-w.cn/Article/details/gt2nbvbskkh.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2itepwcsb.html

[A02] 变量声明与赋值
来源：http://dali.hfpthk.cn/Article/details/gt2juztbdai.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hnxiangtu.top/Article/details/gt2zrqaklcj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yangfankeji.com/Article/details/gt2xmjsxqoo.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xuanzx.com/Article/details/gt2bpkppunu.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xuetiantiany.cn/Article/details/gt2nxfqsvxr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hysaishi.cn/Article/details/gt2liarruva.html

Go:   name := "Alex"; age := 20
来源：http://dali.pycfn.com/Article/details/gt2jlzeoxnp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gaohongyu789.top/Article/details/gt2qaichzka.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jianghu66.top/Article/details/gt2ityukjhy.html

[A03] 常量定义
来源：http://dali.hnqzz.top/Article/details/gt2lcarhrdu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.aibaodan.cn/Article/details/gt2stvtmdyg.html

PHP:  const PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gt2ktqerlxa.html

JS:   const PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gt2kbriwzvs.html

TS:   const PI: number = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gt2zxsiggey.html

Java: static final double PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gt2tlomtohu.html

Go:   const PI = 3.14159
来源：http://dali.ydzc1.top/Article/details/gt2hdllvzdq.html

Ruby: PI = 3.14159
来源：http://dali.fengsongda.top/Article/details/gt2villazix.html

C#:   const double PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gt2mwrttobf.html

[A04] 判断变量类型
来源：http://dali.jinqigfzy.top/Article/details/gt2pxqgbjsf.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.fzhhl.top/Article/details/gt2ysvlzaib.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gogol.net.cn/Article/details/gt2nixzqzuc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhiwuduotai.top/Article/details/gt2kcfofegm.html

TS:   typeof x; x instanceof Date
来源：http://dali.ehwqpu.com/Article/details/gt2danqskvz.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.chenlongwang.top/Article/details/gt2ykgpthps.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kqvporfs.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.chenlongwang.top/Article/details/gt2ynoyloeh.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vshcirdw.html

[A05] 整数除法与取模
来源：http://dali.gogol.net.cn/Article/details/gt2ifxthqyk.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.daxiang520.top/Article/details/gt2dbplcznm.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.bjfxy.top/Article/details/gt2gmwtkusk.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gt2ivpwjvqo.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cucudq.cn/Article/details/gt2rpnvrbjc.html

Java: 7 / 2; 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gt2eehsjrve.html

Go:   7 / 2; 7 % 2
来源：http://dali.yueranfly.top/Article/details/gt2oqotqeqr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gt2xpkwbogm.html

C#:   7 / 2; 7 % 2
来源：http://dali.xinyue.icu/Article/details/gt2stosjalc.html

[A06] 字符串转数字
来源：http://dali.cqqwz.cn/Article/details/gt2yasmhguh.html

Py:   int("42"); float("3.14")
来源：http://dali.yangfankeji.com/Article/details/gt2cfqlkrbi.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.ydzc1.top/Article/details/gt2mrajurro.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.sysykeji.top/Article/details/gt2mxapfmuy.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.vqdsnc.cn/Article/details/gt2swaraovo.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.chenlongwang.top/Article/details/gt2cgciliiu.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.daxiang520.top/Article/details/gt2pneyqban.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.vqdsnc.cn/Article/details/gt2gskswzmz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yonumen.top/Article/details/gt2pzjrxkil.html

[A07] 数字转字符串
来源：http://dali.gzhubu.top/Article/details/gt2gpjluxys.html

Py:   str(42)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ciewzfcz.html

PHP:  (string) 42; strval(42)
来源：http://dali.daxiang520.top/Article/details/gt2yavzojyl.html

JS:   String(42); (42).toString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2amdzcmdc.html

TS:   String(42)
来源：http://dali.fengsongda.top/Article/details/gt2skhxkacg.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.mhx1999.top/Article/details/gt2ainjvalu.html

Go:   strconv.Itoa(42)
来源：http://dali.shuidangran.top/Article/details/gt2xpevuljn.html

Ruby: 42.to_s
来源：http://dali.iojbl.cn/Article/details/gt2swgjbqfg.html

C#:   42.ToString()
来源：http://dali.tian-w.cn/Article/details/gt2bfktkkaq.html

[A08] 取整与四舍五入
来源：http://dali.wangshuangyany.cn/Article/details/gt2sslwqdfj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.xuanzx.com/Article/details/gt2rwerbxbq.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.wangdashe.top/Article/details/gt2vyphhhhw.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhongyouzk.top/Article/details/gt2cmeftkqw.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wkgccwog.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.vqdsnc.cn/Article/details/gt2jrrjbtvq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.shzxlz.cn/Article/details/gt2cnbiqtiz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yangfankeji.com/Article/details/gt2xzpxxxwl.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yuanzhike.top/Article/details/gt2lipwalod.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2izeskivb.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.c1oappe.top/Article/details/gt2tvkpzfaj.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gt2idrpnqjf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2grrkwcke.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gt2nsmkaqtx.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2judfpdtg.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.gotoacloud.top/Article/details/gt2eouakmep.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.aibaodan.cn/Article/details/gt2wmyluvap.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gt2cfbmtmhq.html

[A10] 生成随机数
来源：http://dali.quarkkingdee.top/Article/details/gt2kgofkgos.html

Py:   import random; random.randint(1, 100)
来源：http://dali.havefunace.top/Article/details/gt2wcbwmkzt.html

PHP:  random_int(1, 100);
来源：http://dali.c1oappe.top/Article/details/gt2aaldysae.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cucudq.cn/Article/details/gt2lbqqmssm.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cashguo.top/Article/details/gt2wbceflxk.html

Java: new Random().nextInt(100) + 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2jcwxqnhr.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.ivvv.top/Article/details/gt2dqddwyxg.html

Ruby: rand(1..100)
来源：http://dali.tanke756.top/Article/details/gt2omkshznf.html

C#:   new Random().Next(1, 101)
来源：http://dali.mhx1999.top/Article/details/gt2rrmadorv.html

[A11] 条件表达式（三元）
来源：http://dali.mhx1999.top/Article/details/gt2tltzvfic.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.haohaochexian.top/Article/details/gt2kmwkgvbh.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhoulong.xyz/Article/details/gt2cdvkfsdn.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.316326.xyz/Article/details/gt2hqlghjpz.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.vqdsnc.cn/Article/details/gt2sgmmoxyk.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.gaohongyu789.top/Article/details/gt2cseuyztl.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yj20258888.top/Article/details/gt2yzksdunl.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.meibo888.top/Article/details/gt2ilvkxfln.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.chenjidiqi.icu/Article/details/gt2njyfcell.html

[A12] 字符串插值 / 格式化
来源：http://dali.xinyue.icu/Article/details/gt2pevzlkdg.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.guannengcc.top/Article/details/gt2qecehzfr.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.cashguo.top/Article/details/gt2ctqzzqka.html

JS:   `Hello, ${name}!`
来源：http://dali.jiagoushi.top/Article/details/gt2fbdalgeu.html

TS:   `Hello, ${name}!`
来源：http://dali.fengsongda.top/Article/details/gt2gskvthhd.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2snnfljec.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.sysykeji.top/Article/details/gt2nigqhddu.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tehnukfc.html

C#:   $"Hello, {name}!"
来源：http://dali.daria6918.cn/Article/details/gt2fjhfqoqy.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.havefunace.top/Article/details/gt2eqvmsizh.html

Py:   "第一行\n第二行"
来源：http://dali.jqgfzy.top/Article/details/gt2eopkmrhg.html

PHP:  "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gt2mziqzhrr.html

JS:   "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gjiwlkvl.html

TS:   "第一行\n第二行"
来源：http://dali.guowangkeji.top/Article/details/gt2vbffiyiz.html

Java: "第一行\n第二行"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ezghxxkk.html

Go:   "第一行\n第二行"
来源：http://dali.nanxinkj.top/Article/details/gt2gwogpzix.html

Ruby: "第一行\n第二行"
来源：http://dali.pengpengdd.cyou/Article/details/gt2qjhsdcnd.html

C#:   "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gt2qktspfmc.html


<!-- 参考信息 -->