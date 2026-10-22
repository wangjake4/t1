代发 wailian999

[U81] JS：初始化项目
来源：http://dali.sweek.top/Article/details/gt2atgdlkhz.html

npm init -y;  npm i express
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qcikvjla.html

[U82] JS：package.json 脚本
来源：http://dali.jlsjyb.cn/Article/details/gt2ebddlsus.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yj202588.top/Article/details/gt2jvsjtzyw.html

[U83] JS：ES Module 导入导出
来源：http://dali.xuetiantiany.cn/Article/details/gt2cjsxgoia.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hywenlv.cn/Article/details/gt2peurhdeo.html

[U84] JS：CommonJS 写法
来源：http://dali.xylfe.cn/Article/details/gt2twoagsjp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xinyue.icu/Article/details/gt2jzceurlf.html

[U85] JS：可选链
来源：http://dali.hongshengwenyu.top/Article/details/gt2olrvbxxa.html

a?.b?.c
来源：http://dali.tianlin.xyz/Article/details/gt2xxhlyrug.html

[U86] JS：空值合并
来源：http://dali.zhiwuduotai.top/Article/details/gt2vmewzvsj.html

a ?? b
来源：http://dali.svipenyu.cn/Article/details/gt2dvpwswtq.html

[U87] JS：解构默认值
来源：http://dali.zhongyouzk.top/Article/details/gt2qieuwrkd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hnqzz.top/Article/details/gt2deuoplpk.html

[U88] JS：对象展开合并
来源：http://dali.hywenlv.cn/Article/details/gt2mcaopzap.html

{ ...a, ...b }
来源：http://dali.yuxming.cn/Article/details/gt2jiqtwqlk.html

[U89] JS：数组去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tfkvtwoc.html

[...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gt2yctfcytt.html

[U90] JS：数字数组排序
来源：http://dali.cqqwz.cn/Article/details/gt2qmzkvdxz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gt2uhrbqwmp.html

[U91] JS：对象键值遍历
来源：http://dali.andypj.xyz/Article/details/gt2okhqvxqc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.0kj1m.cn/Article/details/gt2wgrldgje.html

[U92] JS：深拷贝
来源：http://dali.yangfankeji.com/Article/details/gt2dhxoahki.html

structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2gzoskqdw.html

[U93] JS：模板字符串
来源：http://dali.316326.xyz/Article/details/gt2bqstdhjg.html

`共 ${n} 条`
来源：http://dali.fzhhl.top/Article/details/gt2gbekdnts.html

[U94] JS：箭头函数
来源：http://dali.jinqigfzy.top/Article/details/gt2iofqkbdx.html

const double = x => x * 2;
来源：http://dali.yj20258.top/Article/details/gt2bhzixksv.html

[U95] JS：Promise 包装
来源：http://dali.xinyue.icu/Article/details/gt2vniqpiin.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2sywfzitz.html

[U96] JS：async/await 与异常
来源：http://dali.vqdsnc.cn/Article/details/gt2siwsnmjc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2atxnfltu.html

[U97] JS：并发请求
来源：http://dali.kuanghao11.cn/Article/details/gt2euvkehgf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gt2oibtomww.html

[U98] JS：fetch 带 JSON
来源：http://dali.gaohongyu789.top/Article/details/gt2jmlfxbsm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jyoumei.cn/Article/details/gt2ovlcfoxq.html

[U99] JS：事件监听
来源：http://dali.guannengcc.top/Article/details/gt2cszcfaqc.html

el.addEventListener("click", e => {})
来源：http://dali.yueranfly.top/Article/details/gt2gveejcks.html

[U100] JS：DOM 查询
来源：http://dali.cdnleiting.top/Article/details/gt2qfpnnzmn.html

document.querySelector(".item")
来源：http://dali.havefunace.top/Article/details/gt2szwnfzqx.html

[U101] JS：classList 操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nnabcaef.html

el.classList.toggle("active")
来源：http://dali.gotoacloud.top/Article/details/gt2rnbmnvgx.html

[U102] JS：本地存储
来源：http://dali.cheryme.top/Article/details/gt2cgydocwm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.smart0.xyz/Article/details/gt2gldishak.html

[U103] JS：定时器
来源：http://dali.nwbrower.top/Article/details/gt2ckhfscia.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.aizwys.cn/Article/details/gt2yeqxhnfh.html

[U104] JS：防抖
来源：http://dali.aibaodan.cn/Article/details/gt2fckecdyq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gt2mhtcwfpw.html

[U105] JS：节流
来源：http://dali.hywenlv.cn/Article/details/gt2lycfrxhe.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.c1oappe.top/Article/details/gt2xezxvhdy.html

[U106] JS：日期格式化
来源：http://dali.dashuyun.cn/Article/details/gt2kvgzcqdh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ybcxt.top/Article/details/gt2ptligqlc.html

[U107] JS：数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gt2cdllbjhw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xziqi.cn/Article/details/gt2bcwtowpi.html

[U108] JS：随机整数
来源：http://dali.gaohongyu789.top/Article/details/gt2astrbxku.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.tian-w.cn/Article/details/gt2hyjgfkqn.html

[U109] JS：数组分组
来源：http://dali.zdqjudy.top/Article/details/gt2mzktbzix.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhoulong.xyz/Article/details/gt2idehjzyg.html

[U110] JS：数组分块
来源：http://dali.sweek.top/Article/details/gt2otkwdktz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jianghu66.top/Article/details/gt2xpladhtn.html

[U111] JS：对象转 Map
来源：http://dali.chenjidiqi.icu/Article/details/gt2flvewhmv.html

new Map(Object.entries(obj))
来源：http://dali.dashuyun.cn/Article/details/gt2encxzkdt.html

[U112] JS：字符串补位
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nvjlxbxo.html

"7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gt2szhewkwv.html

[U113] JS：正则替换全部
来源：http://dali.c1oappe.top/Article/details/gt2paukocfz.html

s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gt2auvaynzn.html

[U114] JS：JSON 深比较
来源：http://dali.svipenyu.cn/Article/details/gt2iismeptt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenzaomai.com/Article/details/gt2wnzfvank.html

[U115] JS：生成 UUID
来源：http://dali.dianchejie.cn/Article/details/gt2jqlgvrzz.html

crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gt2lnpjkqrk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shangyingyoupin.top/Article/details/gt2yapduzke.html

/** @param {string} name */ function f(name) {}
来源：http://dali.guannengcc.top/Article/details/gt2gdiohidc.html

[U117] JS：单元测试
来源：http://dali.aibaodan.cn/Article/details/gt2tfuhhigc.html

npm i -D vitest;  npx vitest
来源：http://dali.vqdsnc.cn/Article/details/gt2wwtpxypg.html

[U118] JS：开发服务器
来源：http://dali.birdmap.top/Article/details/gt2strlxxwi.html

npm i -D vite;  npx vite
来源：http://dali.daria6918.cn/Article/details/gt2ounugqgt.html

[U119] JS：生产构建
来源：http://dali.sweek.top/Article/details/gt2opbptncx.html

npx vite build
来源：http://dali.jiagoushi.top/Article/details/gt2pqpmvgpo.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.bjfxy.top/Article/details/gt2gkvfftke.html

import.meta.env.VITE_API_URL
来源：http://dali.chenjidiqi.icu/Article/details/gt2ugicnbhj.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2gnlhnhlb.html

统计汇总
来源：http://dali.redwolf501.top/Article/details/gt2ilykodoc.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2uhocfcbt.html

按语言统计（条）：
来源：http://dali.chenjidiqi.icu/Article/details/gt2rarvmvhi.html

Python ......... 252
来源：http://dali.aizwys.cn/Article/details/gt2yjcvgogr.html

PHP ............ 252
来源：http://dali.jqgufenzy.top/Article/details/gt2qgwcgrrd.html

JavaScript ..... 252
来源：http://dali.andypj.xyz/Article/details/gt2ozwzccyg.html

TypeScript ..... 212
来源：http://dali.yongpay.top/Article/details/gt2xjhmmdeg.html

Java ........... 212
来源：http://dali.chenzaomai.com/Article/details/gt2eljzkwzk.html

Go ............. 212
来源：http://dali.yongpay.top/Article/details/gt2mpfedhkt.html

Ruby ........... 212
来源：http://dali.cucudq.cn/Article/details/gt2zhczjedo.html

C# ............. 212
来源：http://dali.kuanghao11.cn/Article/details/gt2wylfzctu.html

C .............. 30
来源：http://dali.xylfe.cn/Article/details/gt2usqafslz.html

C++ ............ 30
来源：http://dali.kuanghao11.cn/Article/details/gt2iguyfiec.html

SQL ............ 90
来源：http://dali.tanke756.top/Article/details/gt2pgcgtoqz.html

Bash ........... 80
来源：http://dali.yangfankeji.com/Article/details/gt2rcjtgnae.html

Kotlin ......... 15
来源：http://dali.ydzc1.top/Article/details/gt2xbipspde.html

Swift .......... 15
来源：http://dali.wangshuangyany.cn/Article/details/gt2mrsyaiso.html

Lua ............ 10
来源：http://dali.hammf.cn/Article/details/gt2bhcfinam.html

Perl ........... 10
来源：http://dali.svipenyu.cn/Article/details/gt2bwavsvyx.html

Scala .......... 10
来源：http://dali.gogol.net.cn/Article/details/gt2uxpccqvv.html

------------------------------------
来源：http://dali.jianghu66.top/Article/details/gt2drvmbudq.html

合计 ........... 2106 条
来源：http://dali.hfpthk.cn/Article/details/gt2dtjnttyf.html

按章节统计：
来源：http://dali.hysaishi.cn/Article/details/gt2piurvzsd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.nwbrower.top/Article/details/gt2igmubisz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zycfv.cn/Article/details/gt2obynepxn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.sweek.top/Article/details/gt2lzvguflr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jianghu66.top/Article/details/gt2uxgthann.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xylfe.cn/Article/details/gt2jgzvxesh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hywenlv.cn/Article/details/gt2wfbthvgq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tianlin.xyz/Article/details/gt2dvnuqjip.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.gzhubu.top/Article/details/gt2jhzvjvzr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gt2uaxosjzg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ehwqpu.com/Article/details/gt2ypaxdfaa.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gt2esnlbpok.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gt2mynsazik.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jqgufenzy.top/Article/details/gt2dtgwfrcw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.guannengcc.top/Article/details/gt2jqadgqxi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yvedp.cn/Article/details/gt2runzblrg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gt2rhdyaeqx.html

Q SQL 专题                              90
来源：http://dali.cheryme.top/Article/details/gt2ferdujuj.html

R Bash 专题                             80
来源：http://dali.yuxming.cn/Article/details/gt2jzlmpjtz.html

S C / C++ 专题                          60
来源：http://dali.jinqigufen.top/Article/details/gt2dikaogtu.html

T 其他语言补充                          60
来源：http://dali.ydzc1.top/Article/details/gt2tsfxnlzq.html

U 高频实用片段                         120
来源：http://dali.sysykeji.top/Article/details/gt2ecnbkqna.html

------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gt2bwlulxyb.html

合计                                  2106 条
来源：http://dali.hysaishi.cn/Article/details/gt2aoxwwiip.html

--------------------------------------------------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gt2snofzhpz.html

使用提醒
来源：http://dali.yueranfly.top/Article/details/gt2prpviaff.html

--------------------------------------------------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gt2rnanagzh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2awmvoskw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.sxryk.cn/Article/details/gt2xdvibbjo.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gjxcuwtn.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.gogol.net.cn/Article/details/gt2thrcegir.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ydzc1.top/Article/details/gt2ntznkora.html

—— 文件结束 ——
来源：http://dali.zycfv.cn/Article/details/gt2eemudhqb.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cxrswxxs.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.dashuyun.cn/Article/details/gt2ktfmsabh.html

Common Programming Examples Cheat Book
来源：http://dali.sxryk.cn/Article/details/gt2grgkdkrn.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2ydhrhesr.html

【收录内容】
来源：http://dali.haohaochexian.top/Article/details/gt2nlngllax.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cqqwz.cn/Article/details/gt2flewvmfn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.sxryk.cn/Article/details/gt2orrqgwsq.html

SQL · Bash · C · C++
来源：http://dali.mhx1999.top/Article/details/gt2macpmrpv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.snrcjt.cn/Article/details/gt2qevjlkdm.html

【使用说明】
来源：http://dali.guowangkeji.top/Article/details/gt2mqdvuwkb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ehwqpu.com/Article/details/gt2uffeaazc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yj20258.top/Article/details/gt2aowcuqya.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dgyhjzyu.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.fzhhl.top/Article/details/gt2llfqysns.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.haohaochexian.top/Article/details/gt2dpmabole.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yuxming.cn/Article/details/gt2qldvhxwz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zdqjudy.top/Article/details/gt2suoghvhx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jlsjyb.cn/Article/details/gt2dygjcgem.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.meibo888.top/Article/details/gt2tyratxty.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jiagoushi.top/Article/details/gt2hwmxiobi.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yonumen.top/Article/details/gt2wvmckdux.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hammf.cn/Article/details/gt2afvxfaye.html

【文件统计】
来源：http://dali.hongshengwenyu.top/Article/details/gt2fiachbvg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nmokxsxm.html

--------------------------------------------------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gt2ogmramgn.html

目  录
来源：http://dali.jqgufenzy.top/Article/details/gt2zgdxfftm.html

--------------------------------------------------------------------------------
来源：http://dali.sysykeji.top/Article/details/gt2rggwmpiz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.aizwys.cn/Article/details/gt2gluuuvpi.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2amzwkkxt.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2kmhdchlw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.snrcjt.cn/Article/details/gt2qapnrvab.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hnqzz.top/Article/details/gt2ibydymlr.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.pycfn.com/Article/details/gt2ifzetmnt.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.tanke756.top/Article/details/gt2sbuabgxa.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tjciqylj.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gt2gbbotjyr.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jaelmmwu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2skobqqyr.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2rigyndkh.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gt2hbsiirfx.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xziqi.cn/Article/details/gt2xqgjxndl.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.nwbrower.top/Article/details/gt2ajnhhciq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gt2ipxrxehh.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.gogol.net.cn/Article/details/gt2efxkecwm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zdqjudy.top/Article/details/gt2hfdsezps.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.daria6918.cn/Article/details/gt2psaozmcu.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.svipenyu.cn/Article/details/gt2setmkllu.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.fzhhl.top/Article/details/gt2onugoire.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2rmyeghnh.html

A. 基础语法与类型
来源：http://dali.jiagoushi.top/Article/details/gt2xtfxpgqx.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2rhyzivgn.html

[A01] Hello World
来源：http://dali.yueranfly.top/Article/details/gt2lpbasyqd.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2xncmrgtp.html

PHP:  echo "Hello, World!";
来源：http://dali.zdqjudy.top/Article/details/gt2pqbapchz.html

JS:   console.log("Hello, World!");
来源：http://dali.cdnleiting.top/Article/details/gt2cweynhcn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cucudq.cn/Article/details/gt2sflyuhox.html

Java: System.out.println("Hello, World!");
来源：http://dali.hywenlv.cn/Article/details/gt2pdcokxxq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ylldwohd.html

Ruby: puts "Hello, World!"
来源：http://dali.9152youxi.cn/Article/details/gt2vmoazxcj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.guannengcc.top/Article/details/gt2fdazzfds.html

[A02] 变量声明与赋值
来源：http://dali.vqdsnc.cn/Article/details/gt2wzorvubl.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.chenjidiqi.icu/Article/details/gt2uqmmbatw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.kuanghao11.cn/Article/details/gt2fcijmgpy.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2urvtqusg.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gt2zgvlydsl.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.c1oappe.top/Article/details/gt2tgdobsuf.html

Go:   name := "Alex"; age := 20
来源：http://dali.yj202588.top/Article/details/gt2prxrxjnp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.nanxuanxn.top/Article/details/gt2vtwnkkay.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yknqiuna.html

[A03] 常量定义
来源：http://dali.vqdsnc.cn/Article/details/gt2uqrimabi.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.tanke756.top/Article/details/gt2fkixneuc.html

PHP:  const PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fgadldie.html

JS:   const PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gt2opcaicps.html

TS:   const PI: number = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gt2tkyveezu.html

Java: static final double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gt2xzorzmza.html

Go:   const PI = 3.14159
来源：http://dali.aizwys.cn/Article/details/gt2oeeckhss.html

Ruby: PI = 3.14159
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wrgldqgo.html

C#:   const double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gt2mrbxgmyo.html

[A04] 判断变量类型
来源：http://dali.chenzaomai.com/Article/details/gt2coqeizll.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.tanke756.top/Article/details/gt2hmzmjvso.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sbsqnphg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhoulong.xyz/Article/details/gt2kdxazrao.html

TS:   typeof x; x instanceof Date
来源：http://dali.nanxuanxn.top/Article/details/gt2inqrmqta.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.guowangkeji.top/Article/details/gt2bxmosrta.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hnqzz.top/Article/details/gt2ohtlynuz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhoulong.xyz/Article/details/gt2axrpyvvp.html

C#:   x.GetType().Name; x is int
来源：http://dali.ehwqpu.com/Article/details/gt2gwfvstam.html

[A05] 整数除法与取模
来源：http://dali.yangfankeji.com/Article/details/gt2mitlyozg.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.ydzc1.top/Article/details/gt2aikuocba.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yj202588.top/Article/details/gt2ujsledzx.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gt2fgosvxne.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.smart0.xyz/Article/details/gt2gkvpbguz.html

Java: 7 / 2; 7 % 2
来源：http://dali.hnqzz.top/Article/details/gt2pwlacbpu.html

Go:   7 / 2; 7 % 2
来源：http://dali.xylfe.cn/Article/details/gt2vsdmwlul.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.sysykeji.top/Article/details/gt2ybyecfhr.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gt2jczderis.html

[A06] 字符串转数字
来源：http://dali.jianghu66.top/Article/details/gt2xmqwbphs.html

Py:   int("42"); float("3.14")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hkuewimj.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.vqdsnc.cn/Article/details/gt2tzhmdwas.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nphirxia.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.xylfe.cn/Article/details/gt2bxcdoidc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jiagoushi.top/Article/details/gt2ulrgczdn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2badwxhuf.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zycfv.cn/Article/details/gt2kqtutnqm.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xuetiantiany.cn/Article/details/gt2adwnrled.html

[A07] 数字转字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2kgnebcgx.html

Py:   str(42)
来源：http://dali.hnxiangtu.top/Article/details/gt2ggiopjtz.html

PHP:  (string) 42; strval(42)
来源：http://dali.pycfn.com/Article/details/gt2febglkjc.html

JS:   String(42); (42).toString()
来源：http://dali.gotoacloud.top/Article/details/gt2boaqmijf.html

TS:   String(42)
来源：http://dali.hnqzz.top/Article/details/gt2gbrqrcum.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.cdnleiting.top/Article/details/gt2qzxdodxn.html

Go:   strconv.Itoa(42)
来源：http://dali.zdqjudy.top/Article/details/gt2sgopmjji.html

Ruby: 42.to_s
来源：http://dali.wangdashe.top/Article/details/gt2vnpzvqsa.html

C#:   42.ToString()
来源：http://dali.jqgfzy.top/Article/details/gt2yeryqunx.html

[A08] 取整与四舍五入
来源：http://dali.sxryk.cn/Article/details/gt2wixngwdj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ehwqpu.com/Article/details/gt2qfcgsnha.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.gzhubu.top/Article/details/gt2zgcfsngs.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.aibaodan.cn/Article/details/gt2uhjcgtnk.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rarnzwjv.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zdqjudy.top/Article/details/gt2ewuucyff.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yj202588.top/Article/details/gt2wghvglqx.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yanxiufei.cn/Article/details/gt2gyrfaxrp.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ivvv.top/Article/details/gt2ieigpeql.html

[A09] 绝对值与最大最小值
来源：http://dali.zhengqikj.top/Article/details/gt2zeibhvxz.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gt2rwsyopoq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2zmyicdps.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yueranfly.top/Article/details/gt2voxvgzig.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.xziqi.cn/Article/details/gt2anzrqhjo.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.wangdashe.top/Article/details/gt2mprwlqyu.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.chenlongwang.top/Article/details/gt2hggrbuft.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.nwbrower.top/Article/details/gt2icdaypei.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gt2cviczbuq.html

[A10] 生成随机数
来源：http://dali.jinqigufen.top/Article/details/gt2myttwprk.html

Py:   import random; random.randint(1, 100)
来源：http://dali.sxryk.cn/Article/details/gt2cmrycadk.html

PHP:  random_int(1, 100);
来源：http://dali.snrcjt.cn/Article/details/gt2pjuguqrd.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.snrcjt.cn/Article/details/gt2gusuxwba.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2yxnpxiwk.html

Java: new Random().nextInt(100) + 1
来源：http://dali.gaohongyu789.top/Article/details/gt2owlzjkqt.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zbgkdtqb.html

Ruby: rand(1..100)
来源：http://dali.hysaishi.cn/Article/details/gt2puctnkbm.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjmlxmu.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2reqbazgv.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.hnxiangtu.top/Article/details/gt2fpfbggpn.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.redwolf501.top/Article/details/gt2boldimth.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.havefunace.top/Article/details/gt2zljkiwfh.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gt2yfgmxlgz.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.andypj.xyz/Article/details/gt2oigqpzir.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.guannengcc.top/Article/details/gt2omktkysc.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.meibo888.top/Article/details/gt2glxmagpg.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yj20258888.top/Article/details/gt2zvbocozl.html

[A12] 字符串插值 / 格式化
来源：http://dali.yuxming.cn/Article/details/gt2ckutvrwb.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.svipenyu.cn/Article/details/gt2urpyzfnv.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.xziqi.cn/Article/details/gt2lxkxglst.html

JS:   `Hello, ${name}!`
来源：http://dali.shzxlz.cn/Article/details/gt2wjipyupu.html

TS:   `Hello, ${name}!`
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dwldyyvu.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ltehsllf.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fziusjyt.html

Ruby: "Hello, #{name}!"
来源：http://dali.yueranfly.top/Article/details/gt2ghtindnk.html

C#:   $"Hello, {name}!"
来源：http://dali.fengsongda.top/Article/details/gt2vpyvzgiz.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.daria6918.cn/Article/details/gt2kdsclvuh.html

Py:   "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gt2rwaeoxnj.html

PHP:  "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gt2cljcapzy.html

JS:   "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gt2dqlycvsx.html

TS:   "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gt2nmawvepr.html


<!-- 参考信息 -->