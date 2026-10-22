代发 wailian999

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvatrls.html

npm init -y;  npm i express
来源：http://dali.quarkkingdee.top/Article/details/gt2wlqdoger.html

[U82] JS：package.json 脚本
来源：http://dali.hysaishi.cn/Article/details/gt2ugjekvjw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jianghu66.top/Article/details/gt2ablgqftp.html

[U83] JS：ES Module 导入导出
来源：http://dali.fzhhl.top/Article/details/gt2gplykjhf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.chenjidiqi.icu/Article/details/gt2ociibieq.html

[U84] JS：CommonJS 写法
来源：http://dali.ivvv.top/Article/details/gt2gxeerppc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.guowangkeji.top/Article/details/gt2whqvjcok.html

[U85] JS：可选链
来源：http://dali.pycfn.com/Article/details/gt2crofopqw.html

a?.b?.c
来源：http://dali.zhengqikj.top/Article/details/gt2kevlitqb.html

[U86] JS：空值合并
来源：http://dali.cdnleiting.top/Article/details/gt2hegbaata.html

a ?? b
来源：http://dali.hnqzz.top/Article/details/gt2dxreiuxy.html

[U87] JS：解构默认值
来源：http://dali.nwbrower.top/Article/details/gt2awtsecio.html

const { a = 1, b = 2 } = obj;
来源：http://dali.cqqwz.cn/Article/details/gt2doxblzmz.html

[U88] JS：对象展开合并
来源：http://dali.fengsongda.top/Article/details/gt2fapaptzj.html

{ ...a, ...b }
来源：http://dali.dianchejie.cn/Article/details/gt2xybgvweg.html

[U89] JS：数组去重
来源：http://dali.wangdashe.top/Article/details/gt2aqctmtkd.html

[...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gt2qsxmzcyq.html

[U90] JS：数字数组排序
来源：http://dali.bjfxy.top/Article/details/gt2qultxtsp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2uecdcfeh.html

[U91] JS：对象键值遍历
来源：http://dali.snrcjt.cn/Article/details/gt2naplpgym.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ehwqpu.com/Article/details/gt2dtopbpir.html

[U92] JS：深拷贝
来源：http://dali.hysaishi.cn/Article/details/gt2nczjrxcw.html

structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2xlusuzmg.html

[U93] JS：模板字符串
来源：http://dali.tanke756.top/Article/details/gt2yzsvtqri.html

`共 ${n} 条`
来源：http://dali.yueranfly.top/Article/details/gt2fikokmne.html

[U94] JS：箭头函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2amonjssm.html

const double = x => x * 2;
来源：http://dali.dashuyun.cn/Article/details/gt2lhiwyqib.html

[U95] JS：Promise 包装
来源：http://dali.cheryme.top/Article/details/gt2sptkjnvl.html

new Promise((resolve, reject) => {})
来源：http://dali.hfpthk.cn/Article/details/gt2wixlttkd.html

[U96] JS：async/await 与异常
来源：http://dali.jinqigfzy.top/Article/details/gt2bduvznkp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gt2zxcpwdhm.html

[U97] JS：并发请求
来源：http://dali.hnxiangtu.top/Article/details/gt2ygzswfdb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gt2svxspzsd.html

[U98] JS：fetch 带 JSON
来源：http://dali.meibo888.top/Article/details/gt2fxoiyapz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhengqikj.top/Article/details/gt2avtpfnze.html

[U99] JS：事件监听
来源：http://dali.xziqi.cn/Article/details/gt2yhudnvdx.html

el.addEventListener("click", e => {})
来源：http://dali.aizwys.cn/Article/details/gt2nwvxiwif.html

[U100] JS：DOM 查询
来源：http://dali.dashuyun.cn/Article/details/gt2xozqkvxv.html

document.querySelector(".item")
来源：http://dali.ivvv.top/Article/details/gt2lnfglebi.html

[U101] JS：classList 操作
来源：http://dali.fzhhl.top/Article/details/gt2ffyxgfrp.html

el.classList.toggle("active")
来源：http://dali.smart0.xyz/Article/details/gt2pdogoocv.html

[U102] JS：本地存储
来源：http://dali.0kj1m.cn/Article/details/gt2rqizvdco.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhiwuduotai.top/Article/details/gt2lwyckznq.html

[U103] JS：定时器
来源：http://dali.xinyue.icu/Article/details/gt2angitpfj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.nwbrower.top/Article/details/gt2qcbdvtsk.html

[U104] JS：防抖
来源：http://dali.iojbl.cn/Article/details/gt2hxegcszf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gt2xnnmmrqc.html

[U105] JS：节流
来源：http://dali.xziqi.cn/Article/details/gt2lunydnwq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yueranfly.top/Article/details/gt2pkesfphn.html

[U106] JS：日期格式化
来源：http://dali.hammf.cn/Article/details/gt2kcixwdfk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.wangdashe.top/Article/details/gt2latathxz.html

[U107] JS：数字千分位
来源：http://dali.hysaishi.cn/Article/details/gt2gfkdjxyh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sweek.top/Article/details/gt2duiqybyy.html

[U108] JS：随机整数
来源：http://dali.zhengqikj.top/Article/details/gt2pgxigrou.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xuanzx.com/Article/details/gt2hbpxwjwp.html

[U109] JS：数组分组
来源：http://dali.sysykeji.top/Article/details/gt2qgfpftlf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.redwolf501.top/Article/details/gt2vouacjwv.html

[U110] JS：数组分块
来源：http://dali.meibo888.top/Article/details/gt2tgbolifs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sweek.top/Article/details/gt2wtfqbqla.html

[U111] JS：对象转 Map
来源：http://dali.gotoacloud.top/Article/details/gt2dtahttls.html

new Map(Object.entries(obj))
来源：http://dali.nanxinkj.top/Article/details/gt2kzdkrnwc.html

[U112] JS：字符串补位
来源：http://dali.jiagoushi.top/Article/details/gt2exrzxont.html

"7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gt2zscyqlti.html

[U113] JS：正则替换全部
来源：http://dali.zdqjudy.top/Article/details/gt2qoemswzr.html

s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2uxvmrrvm.html

[U114] JS：JSON 深比较
来源：http://dali.nanxuanxn.top/Article/details/gt2axtqjjio.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuanzhike.top/Article/details/gt2nstvfarm.html

[U115] JS：生成 UUID
来源：http://dali.jinqigfzy.top/Article/details/gt2brisuejw.html

crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gt2iieazpmk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hongshengwenyu.top/Article/details/gt2krtapqjp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yonumen.top/Article/details/gt2jzpknexv.html

[U117] JS：单元测试
来源：http://dali.chenlongwang.top/Article/details/gt2wfisxjke.html

npm i -D vitest;  npx vitest
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dkzilzos.html

[U118] JS：开发服务器
来源：http://dali.zhongyouzk.top/Article/details/gt2vhpiiydj.html

npm i -D vite;  npx vite
来源：http://dali.pycfn.com/Article/details/gt2spwzbwwl.html

[U119] JS：生产构建
来源：http://dali.smart0.xyz/Article/details/gt2nqskcnvi.html

npx vite build
来源：http://dali.xuetiantiany.cn/Article/details/gt2prcgptbt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.sysykeji.top/Article/details/gt2ufrxxwks.html

import.meta.env.VITE_API_URL
来源：http://dali.yangfankeji.com/Article/details/gt2xbjexxxk.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2gngbpbvr.html

统计汇总
来源：http://dali.jyoumei.cn/Article/details/gt2qpslafqh.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2wtecvaro.html

按语言统计（条）：
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cfvwjjtw.html

Python ......... 252
来源：http://dali.haohaochexian.top/Article/details/gt2antqualv.html

PHP ............ 252
来源：http://dali.jlsjyb.cn/Article/details/gt2hwsigoqz.html

JavaScript ..... 252
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lisdscgw.html

TypeScript ..... 212
来源：http://dali.jinqigufen.top/Article/details/gt2zyyeomlb.html

Java ........... 212
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ptcazasx.html

Go ............. 212
来源：http://dali.tianlin.xyz/Article/details/gt2uncjkhkg.html

Ruby ........... 212
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fymtnfwy.html

C# ............. 212
来源：http://dali.ivvv.top/Article/details/gt2xaqofmvf.html

C .............. 30
来源：http://dali.tanke756.top/Article/details/gt2uewwwpqy.html

C++ ............ 30
来源：http://dali.gaohongyu789.top/Article/details/gt2jvuomfgf.html

SQL ............ 90
来源：http://dali.ybcxt.top/Article/details/gt2fzzrfihj.html

Bash ........... 80
来源：http://dali.xziqi.cn/Article/details/gt2ermpetgt.html

Kotlin ......... 15
来源：http://dali.cqqwz.cn/Article/details/gt2btitixei.html

Swift .......... 15
来源：http://dali.sxryk.cn/Article/details/gt2mxcwgamo.html

Lua ............ 10
来源：http://dali.zhoulong.xyz/Article/details/gt2vxiymzze.html

Perl ........... 10
来源：http://dali.chenlongwang.top/Article/details/gt2yqfitcgq.html

Scala .......... 10
来源：http://dali.quarkkingdee.top/Article/details/gt2kodtzska.html

------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gt2cxnsjfwf.html

合计 ........... 2106 条
来源：http://dali.ppjwa.cn/Article/details/gt2rghfjfvw.html

按章节统计：
来源：http://dali.havefunace.top/Article/details/gt2pdhtrxeo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hammf.cn/Article/details/gt2rzmzqxpt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.guannengcc.top/Article/details/gt2hpbjkfxx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.svipenyu.cn/Article/details/gt2aonqymfr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.chenzaomai.com/Article/details/gt2nrtneike.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhixingplan.top/Article/details/gt2tkbgcjwv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.snrcjt.cn/Article/details/gt2gejbylmo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.chenlongwang.top/Article/details/gt2liddmgye.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nwbrower.top/Article/details/gt2pzbhlkgf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gt2fsbbvwmr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.aizwys.cn/Article/details/gt2cvloipkv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jfaxnhlh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cwfoeftv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gt2ilnnhrim.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hnqzz.top/Article/details/gt2ifbnazco.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.sweek.top/Article/details/gt2sinptxnp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gt2svshcjuu.html

Q SQL 专题                              90
来源：http://dali.zdqjudy.top/Article/details/gt2igerleod.html

R Bash 专题                             80
来源：http://dali.9152youxi.cn/Article/details/gt2oljedpko.html

S C / C++ 专题                          60
来源：http://dali.svipenyu.cn/Article/details/gt2srrbztuu.html

T 其他语言补充                          60
来源：http://dali.jqgufenzy.top/Article/details/gt2ozrjstwm.html

U 高频实用片段                         120
来源：http://dali.yangfankeji.com/Article/details/gt2qpimsjso.html

------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gt2epgjkgxd.html

合计                                  2106 条
来源：http://dali.cheryme.top/Article/details/gt2bcnnvknw.html

--------------------------------------------------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gt2uzyffrjl.html

使用提醒
来源：http://dali.sufxvd.cn/Article/details/gt2oiejstkw.html

--------------------------------------------------------------------------------
来源：http://dali.yonumen.top/Article/details/gt2qgftiizh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.nanxuanxn.top/Article/details/gt2swwhcuwu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.sweek.top/Article/details/gt2hnsuiuzy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.316326.xyz/Article/details/gt2wxsrsukj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xuetiantiany.cn/Article/details/gt2frugnkpz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.nanxinkj.top/Article/details/gt2veyciupv.html

—— 文件结束 ——
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dunzulyi.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2mpaxgdjm.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.aibaodan.cn/Article/details/gt2dgdmqrfr.html

Common Programming Examples Cheat Book
来源：http://dali.mhx1999.top/Article/details/gt2gjkvroak.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2apoywwmc.html

【收录内容】
来源：http://dali.yueranfly.top/Article/details/gt2bgwmafgd.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.daria6918.cn/Article/details/gt2tnmepkix.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.fzhhl.top/Article/details/gt2corytlxo.html

SQL · Bash · C · C++
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zwwbivbr.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.daria6918.cn/Article/details/gt2zctgvqsw.html

【使用说明】
来源：http://dali.yuanzhike.top/Article/details/gt2tcdhhgtn.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.nanxuanxn.top/Article/details/gt2nhtiqxjy.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jianghu66.top/Article/details/gt2wccrnxxd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.snrcjt.cn/Article/details/gt2mynnlbzy.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.bjfxy.top/Article/details/gt2ofwlpdkr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.snrcjt.cn/Article/details/gt2pvfcmwwq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.tanke756.top/Article/details/gt2lofzfyyf.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.nanxinkj.top/Article/details/gt2tnfmjjnt.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.sufxvd.cn/Article/details/gt2bawqkfas.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xydcxkqb.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ppjwa.cn/Article/details/gt2mydlqatz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.fengsongda.top/Article/details/gt2zwtciuxq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.chenlongwang.top/Article/details/gt2gbyfzgcd.html

【文件统计】
来源：http://dali.zycfv.cn/Article/details/gt2jgzovfpe.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ugybgxld.html

--------------------------------------------------------------------------------
来源：http://dali.smart0.xyz/Article/details/gt2deusltun.html

目  录
来源：http://dali.vqdsnc.cn/Article/details/gt2tykccsgh.html

--------------------------------------------------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gt2weicfbuk.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ehwqpu.com/Article/details/gt2hkymyhop.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2obgghldl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xuanzx.com/Article/details/gt2ocqxtpyd.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.316326.xyz/Article/details/gt2awrmgqkx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.cashguo.top/Article/details/gt2bwkmwxpk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.nanxinkj.top/Article/details/gt2rtdnconw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yvedp.cn/Article/details/gt2sbbkvtci.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2fhqbqetx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.gotoacloud.top/Article/details/gt2tezqpokh.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ehwqpu.com/Article/details/gt2zvitdivo.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mplyujae.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gt2rnkqxvrp.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gt2zxtgopra.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2acaqrdmu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shuidangran.top/Article/details/gt2kugvxppb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.nwbrower.top/Article/details/gt2xbgccrij.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cheryme.top/Article/details/gt2fgedulgj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.tianlin.xyz/Article/details/gt2coekxjgk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.snrcjt.cn/Article/details/gt2dfmzbpei.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hongshengwenyu.top/Article/details/gt2ngtvrffo.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xicjuoal.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2przzkinl.html

A. 基础语法与类型
来源：http://dali.zhengqikj.top/Article/details/gt2bindabbd.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2xadfispu.html

[A01] Hello World
来源：http://dali.ivvv.top/Article/details/gt2szzzqguc.html

Py:   print("Hello, World!")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ugcexnka.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlixnbp.html

JS:   console.log("Hello, World!");
来源：http://dali.tian-w.cn/Article/details/gt2hheuftem.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jinqigufen.top/Article/details/gt2kzoyjgjv.html

Java: System.out.println("Hello, World!");
来源：http://dali.chenjidiqi.icu/Article/details/gt2idzwcgfn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jianghu66.top/Article/details/gt2kdgehhhp.html

Ruby: puts "Hello, World!"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cnavlulp.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.meibo888.top/Article/details/gt2tngqidpg.html

[A02] 变量声明与赋值
来源：http://dali.ybcxt.top/Article/details/gt2tdkwietw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jrnembbc.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yj20258.top/Article/details/gt2nlgyrbgw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gt2tejczorw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yangfankeji.com/Article/details/gt2hrimzqvd.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.shzxlz.cn/Article/details/gt2tqkxtglo.html

Go:   name := "Alex"; age := 20
来源：http://dali.havefunace.top/Article/details/gt2qzamrlxo.html

Ruby: name = "Alex"; age = 20
来源：http://dali.nwbrower.top/Article/details/gt2xmyebbpk.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.cucudq.cn/Article/details/gt2tzhyeint.html

[A03] 常量定义
来源：http://dali.jianghu66.top/Article/details/gt2balfadtz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.316326.xyz/Article/details/gt2kudrupnj.html

PHP:  const PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gt2oqeqowfe.html

JS:   const PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gt2qqqxxvpw.html

TS:   const PI: number = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gt2yimpllpi.html

Java: static final double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gt2nvteonke.html

Go:   const PI = 3.14159
来源：http://dali.cashguo.top/Article/details/gt2jqqnmfgp.html

Ruby: PI = 3.14159
来源：http://dali.sxryk.cn/Article/details/gt2gkxwlgmm.html

C#:   const double PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gt2pbpmgdsp.html

[A04] 判断变量类型
来源：http://dali.quarkkingdee.top/Article/details/gt2bujxeeez.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gxbphbsi.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.redwolf501.top/Article/details/gt2donwuzao.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.daria6918.cn/Article/details/gt2cwtutbri.html

TS:   typeof x; x instanceof Date
来源：http://dali.nanxinkj.top/Article/details/gt2ccrfpqgy.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jqgufenzy.top/Article/details/gt2vxfjranj.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhiwuduotai.top/Article/details/gt2zjixcadc.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jqgufenzy.top/Article/details/gt2lwulzqdw.html

C#:   x.GetType().Name; x is int
来源：http://dali.chenlongwang.top/Article/details/gt2pupaaxwh.html

[A05] 整数除法与取模
来源：http://dali.yangfankeji.com/Article/details/gt2zynonapa.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.chenlongwang.top/Article/details/gt2qgpyukfi.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gt2nkuzsfrw.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj20258888.top/Article/details/gt2wdbgthnx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sysykeji.top/Article/details/gt2clzpgosj.html

Java: 7 / 2; 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gt2jfrmmhul.html

Go:   7 / 2; 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gt2haigsozw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gt2gfqkcmdj.html

C#:   7 / 2; 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gt2uvulqsts.html

[A06] 字符串转数字
来源：http://dali.smart0.xyz/Article/details/gt2qlnicmaf.html

Py:   int("42"); float("3.14")
来源：http://dali.nanxinkj.top/Article/details/gt2nhkklxet.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.nanxuanxn.top/Article/details/gt2ghhlvuks.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.daria6918.cn/Article/details/gt2myqmzfic.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hfpthk.cn/Article/details/gt2nmhlnhhv.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.meibo888.top/Article/details/gt2jafcxrkl.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.nwbrower.top/Article/details/gt2qxxarepr.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jyoumei.cn/Article/details/gt2gsdgddhj.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yuanzhike.top/Article/details/gt2yawdaltm.html

[A07] 数字转字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2ctguulgi.html

Py:   str(42)
来源：http://dali.svipenyu.cn/Article/details/gt2ruuqmqrk.html

PHP:  (string) 42; strval(42)
来源：http://dali.xylfe.cn/Article/details/gt2wvvoizxi.html

JS:   String(42); (42).toString()
来源：http://dali.fengsongda.top/Article/details/gt2oqvukbxc.html

TS:   String(42)
来源：http://dali.dashuyun.cn/Article/details/gt2ohqqgicy.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.andypj.xyz/Article/details/gt2xxwawluy.html

Go:   strconv.Itoa(42)
来源：http://dali.chenzaomai.com/Article/details/gt2wlwemwyg.html

Ruby: 42.to_s
来源：http://dali.hammf.cn/Article/details/gt2valneqxm.html

C#:   42.ToString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2zfkrgwcu.html

[A08] 取整与四舍五入
来源：http://dali.yueranfly.top/Article/details/gt2bbzlkwaa.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gt2lbixndfy.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yj20258.top/Article/details/gt2swqjfvty.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.chenlongwang.top/Article/details/gt2dxgmrodf.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jlsjyb.cn/Article/details/gt2wqxejtlp.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yongpay.top/Article/details/gt2wyvxffil.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yj20258888.top/Article/details/gt2wbydhlqf.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.nwbrower.top/Article/details/gt2mzemocrf.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wmiqmddw.html

[A09] 绝对值与最大最小值
来源：http://dali.aizwys.cn/Article/details/gt2lqyfkhju.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gt2wuczqmdd.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xinyue.icu/Article/details/gt2lqhwakdg.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.ydzc1.top/Article/details/gt2myhuujyr.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.fzhhl.top/Article/details/gt2gtyhyftr.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gt2ilggailj.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jyoumei.cn/Article/details/gt2zvojetva.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2geakqyen.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yuxming.cn/Article/details/gt2girlilog.html

[A10] 生成随机数
来源：http://dali.gaohongyu789.top/Article/details/gt2ybhkejmp.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yuxming.cn/Article/details/gt2kpptarla.html

PHP:  random_int(1, 100);
来源：http://dali.jyoumei.cn/Article/details/gt2xuhqlatv.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jianghu66.top/Article/details/gt2shnuyheo.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hywenlv.cn/Article/details/gt2rpbongfi.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yuxming.cn/Article/details/gt2zmnzjsxg.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.fzhhl.top/Article/details/gt2veeftwlt.html

Ruby: rand(1..100)
来源：http://dali.wangdashe.top/Article/details/gt2kudefmhu.html

C#:   new Random().Next(1, 101)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dqegpnoy.html

[A11] 条件表达式（三元）
来源：http://dali.quarkkingdee.top/Article/details/gt2rqmfgyff.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.mhx1999.top/Article/details/gt2ldokdvqy.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.sufxvd.cn/Article/details/gt2usvwvhik.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.wangshuangyany.cn/Article/details/gt2epdyzloj.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yj202588.top/Article/details/gt2mkmrzake.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xuanzx.com/Article/details/gt2wlypkges.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.tianlin.xyz/Article/details/gt2shncjgxx.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.pengpengdd.cyou/Article/details/gt2aakaprpz.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yuxming.cn/Article/details/gt2hjaniedv.html

[A12] 字符串插值 / 格式化
来源：http://dali.shuidangran.top/Article/details/gt2hkodclne.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhixingplan.top/Article/details/gt2skykatvy.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yueranfly.top/Article/details/gt2pchpyryp.html

JS:   `Hello, ${name}!`
来源：http://dali.ehwqpu.com/Article/details/gt2jxfldand.html

TS:   `Hello, ${name}!`
来源：http://dali.svipenyu.cn/Article/details/gt2jbfweeug.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.cucudq.cn/Article/details/gt2ugmsoidu.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.kuanghao11.cn/Article/details/gt2oxnahpva.html

Ruby: "Hello, #{name}!"
来源：http://dali.xuanzx.com/Article/details/gt2sqynxlgl.html

C#:   $"Hello, {name}!"
来源：http://dali.yanxiufei.cn/Article/details/gt2qavivcru.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.daxiang520.top/Article/details/gt2oxyoxrwc.html

Py:   "第一行\n第二行"
来源：http://dali.chenlongwang.top/Article/details/gt2nrdolhmi.html

PHP:  "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gt2zbqxyytm.html

JS:   "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gt2vowgvart.html

TS:   "第一行\n第二行"
来源：http://dali.zhoulong.xyz/Article/details/gt2puafffxy.html


<!-- 参考信息 -->