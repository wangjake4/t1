代发 wailian999

[U81] JS：初始化项目
来源：http://dali.hysaishi.cn/Article/details/gt2gimsutdz.html

npm init -y;  npm i express
来源：http://dali.vqdsnc.cn/Article/details/gt2rvpcegig.html

[U82] JS：package.json 脚本
来源：http://dali.nanxuanxn.top/Article/details/gt2wtmjjlqs.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jiagoushi.top/Article/details/gt2snwpozar.html

[U83] JS：ES Module 导入导出
来源：http://dali.shangyingyoupin.top/Article/details/gt2mkbmefdf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.chenlongwang.top/Article/details/gt2sqcxgvua.html

[U84] JS：CommonJS 写法
来源：http://dali.yanxiufei.cn/Article/details/gt2dfkhoubc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pvhgpfha.html

[U85] JS：可选链
来源：http://dali.andypj.xyz/Article/details/gt2focnpekm.html

a?.b?.c
来源：http://dali.yonumen.top/Article/details/gt2meuijnvd.html

[U86] JS：空值合并
来源：http://dali.vqdsnc.cn/Article/details/gt2wwccmhjv.html

a ?? b
来源：http://dali.xuetiantiany.cn/Article/details/gt2hzsvjmnw.html

[U87] JS：解构默认值
来源：http://dali.shuidangran.top/Article/details/gt2xyrwsovi.html

const { a = 1, b = 2 } = obj;
来源：http://dali.snrcjt.cn/Article/details/gt2nyxbtvwf.html

[U88] JS：对象展开合并
来源：http://dali.chenlongwang.top/Article/details/gt2iyzwqncx.html

{ ...a, ...b }
来源：http://dali.dianchejie.cn/Article/details/gt2kytinxdm.html

[U89] JS：数组去重
来源：http://dali.yj20258.top/Article/details/gt2kjfmcvko.html

[...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gt2zqruhtrq.html

[U90] JS：数字数组排序
来源：http://dali.meibo888.top/Article/details/gt2bkzzreyu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gt2kmcxwchb.html

[U91] JS：对象键值遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2rsgzouxm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jinqigfzy.top/Article/details/gt2vixrpswx.html

[U92] JS：深拷贝
来源：http://dali.birdmap.top/Article/details/gt2igezkuoc.html

structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gt2zfusxadh.html

[U93] JS：模板字符串
来源：http://dali.jianghu66.top/Article/details/gt2jxzedqqj.html

`共 ${n} 条`
来源：http://dali.gotoacloud.top/Article/details/gt2htroilvw.html

[U94] JS：箭头函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2veygrkwx.html

const double = x => x * 2;
来源：http://dali.xuetiantiany.cn/Article/details/gt2bcntnuov.html

[U95] JS：Promise 包装
来源：http://dali.sufxvd.cn/Article/details/gt2uvuitwdp.html

new Promise((resolve, reject) => {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jadyuqxm.html

[U96] JS：async/await 与异常
来源：http://dali.daxiang520.top/Article/details/gt2eqbpueai.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gt2dcfhazhw.html

[U97] JS：并发请求
来源：http://dali.chenzaomai.com/Article/details/gt2yqztfrzc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gt2lqcuadmq.html

[U98] JS：fetch 带 JSON
来源：http://dali.cqqwz.cn/Article/details/gt2lbevtkbi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhongyouzk.top/Article/details/gt2cizoemnz.html

[U99] JS：事件监听
来源：http://dali.pengpengdd.cyou/Article/details/gt2ruqqmuzf.html

el.addEventListener("click", e => {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2axfbgsjv.html

[U100] JS：DOM 查询
来源：http://dali.yj20258888.top/Article/details/gt2szpqedog.html

document.querySelector(".item")
来源：http://dali.mhx1999.top/Article/details/gt2wozqjqog.html

[U101] JS：classList 操作
来源：http://dali.gogol.net.cn/Article/details/gt2szgbvekb.html

el.classList.toggle("active")
来源：http://dali.zhengqikj.top/Article/details/gt2vkinates.html

[U102] JS：本地存储
来源：http://dali.xuanzx.com/Article/details/gt2jouglcou.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hammf.cn/Article/details/gt2obkbmeas.html

[U103] JS：定时器
来源：http://dali.jqgufenzy.top/Article/details/gt2mjdvqqcl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cheryme.top/Article/details/gt2qjlldqgr.html

[U104] JS：防抖
来源：http://dali.ydzc1.top/Article/details/gt2cdgglmoi.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigfzy.top/Article/details/gt2msxprely.html

[U105] JS：节流
来源：http://dali.redwolf501.top/Article/details/gt2clvmxqqq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.nanxinkj.top/Article/details/gt2glrinpcl.html

[U106] JS：日期格式化
来源：http://dali.fengsongda.top/Article/details/gt2dzvosnhj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.birdmap.top/Article/details/gt2emwgklky.html

[U107] JS：数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zubssmqr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2oboilvwc.html

[U108] JS：随机整数
来源：http://dali.0kj1m.cn/Article/details/gt2mjobmmlj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shanyushiyangtech.top/Article/details/gt2txqnyiyo.html

[U109] JS：数组分组
来源：http://dali.cashguo.top/Article/details/gt2aqglrgby.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gt2mhhghvdo.html

[U110] JS：数组分块
来源：http://dali.svipenyu.cn/Article/details/gt2xcextcre.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.chenzaomai.com/Article/details/gt2duzhyqga.html

[U111] JS：对象转 Map
来源：http://dali.zhiwuduotai.top/Article/details/gt2wdzzccjp.html

new Map(Object.entries(obj))
来源：http://dali.birdmap.top/Article/details/gt2eubackjq.html

[U112] JS：字符串补位
来源：http://dali.iojbl.cn/Article/details/gt2yqamieah.html

"7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gt2dokyjcht.html

[U113] JS：正则替换全部
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fznebmia.html

s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gt2kbwlcgbk.html

[U114] JS：JSON 深比较
来源：http://dali.wangdashe.top/Article/details/gt2zjjhjvhk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dashuyun.cn/Article/details/gt2khnhsuez.html

[U115] JS：生成 UUID
来源：http://dali.gotoacloud.top/Article/details/gt2tvxsvfll.html

crypto.randomUUID()
来源：http://dali.tianlin.xyz/Article/details/gt2cifhoptt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shzxlz.cn/Article/details/gt2kjnsasdl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.snrcjt.cn/Article/details/gt2qmmgbxot.html

[U117] JS：单元测试
来源：http://dali.shangyingyoupin.top/Article/details/gt2qzuaprfp.html

npm i -D vitest;  npx vitest
来源：http://dali.tanke756.top/Article/details/gt2nroagvzl.html

[U118] JS：开发服务器
来源：http://dali.shanyushiyangtech.top/Article/details/gt2clwuqsty.html

npm i -D vite;  npx vite
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wjullosl.html

[U119] JS：生产构建
来源：http://dali.cashguo.top/Article/details/gt2ceevobyx.html

npx vite build
来源：http://dali.cdnleiting.top/Article/details/gt2zhulvnqm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.nwbrower.top/Article/details/gt2gchyduis.html

import.meta.env.VITE_API_URL
来源：http://dali.fengsongda.top/Article/details/gt2ikiketak.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2agqipkoa.html

统计汇总
来源：http://dali.haohaochexian.top/Article/details/gt2xnitjtqc.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2oykggwlr.html

按语言统计（条）：
来源：http://dali.ydzc1.top/Article/details/gt2charfhto.html

Python ......... 252
来源：http://dali.zdqjudy.top/Article/details/gt2vuagbiop.html

PHP ............ 252
来源：http://dali.cheryme.top/Article/details/gt2repqrevt.html

JavaScript ..... 252
来源：http://dali.guowangkeji.top/Article/details/gt2cuhygego.html

TypeScript ..... 212
来源：http://dali.havefunace.top/Article/details/gt2rpzvmnqr.html

Java ........... 212
来源：http://dali.yonumen.top/Article/details/gt2aykpxeng.html

Go ............. 212
来源：http://dali.smart0.xyz/Article/details/gt2gmcloyou.html

Ruby ........... 212
来源：http://dali.jianghu66.top/Article/details/gt2rhzhieug.html

C# ............. 212
来源：http://dali.cqqwz.cn/Article/details/gt2akfvesud.html

C .............. 30
来源：http://dali.xuetiantiany.cn/Article/details/gt2uziiyipu.html

C++ ............ 30
来源：http://dali.daria6918.cn/Article/details/gt2vbywbczc.html

SQL ............ 90
来源：http://dali.xuetiantiany.cn/Article/details/gt2txeepxev.html

Bash ........... 80
来源：http://dali.cucudq.cn/Article/details/gt2slqfvukc.html

Kotlin ......... 15
来源：http://dali.cqqwz.cn/Article/details/gt2mctyxfvr.html

Swift .......... 15
来源：http://dali.feifeiyinyue.top/Article/details/gt2matewxix.html

Lua ............ 10
来源：http://dali.gotoacloud.top/Article/details/gt2wnrrsbxe.html

Perl ........... 10
来源：http://dali.jyoumei.cn/Article/details/gt2sqnjaztn.html

Scala .......... 10
来源：http://dali.guannengcc.top/Article/details/gt2wbmervbj.html

------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gt2smiyrrip.html

合计 ........... 2106 条
来源：http://dali.jinqigfzy.top/Article/details/gt2usfyqljx.html

按章节统计：
来源：http://dali.bjfxy.top/Article/details/gt2dvkaemrh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gotoacloud.top/Article/details/gt2kcnionlg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ivvv.top/Article/details/gt2brmldeaf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.smart0.xyz/Article/details/gt2hmvlgdxt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hammf.cn/Article/details/gt2kebqgcng.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.wangshuangyany.cn/Article/details/gt2lsnrpgfe.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.0kj1m.cn/Article/details/gt2hznxqofd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ydzc1.top/Article/details/gt2wejekhwo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ppjwa.cn/Article/details/gt2ugvfrbwz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gt2ebiqzdxj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinqigfzy.top/Article/details/gt2ntsxnjwq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gt2xuxpxgiz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gt2adzuuxay.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gt2nwcpniit.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.guannengcc.top/Article/details/gt2dvotjvnv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yuxming.cn/Article/details/gt2fubrwsdn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gt2dqdnsmml.html

Q SQL 专题                              90
来源：http://dali.fengsongda.top/Article/details/gt2fyidnhqk.html

R Bash 专题                             80
来源：http://dali.feifeiyinyue.top/Article/details/gt2gykfkbed.html

S C / C++ 专题                          60
来源：http://dali.zhixingplan.top/Article/details/gt2yvjkorui.html

T 其他语言补充                          60
来源：http://dali.dianchejie.cn/Article/details/gt2plfdynww.html

U 高频实用片段                         120
来源：http://dali.jlsjyb.cn/Article/details/gt2wiiexfox.html

------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gt2nopunysr.html

合计                                  2106 条
来源：http://dali.daria6918.cn/Article/details/gt2ftudpche.html

--------------------------------------------------------------------------------
来源：http://dali.chenzaomai.com/Article/details/gt2ahosbyfn.html

使用提醒
来源：http://dali.zycfv.cn/Article/details/gt2rmygojbj.html

--------------------------------------------------------------------------------
来源：http://dali.gzhubu.top/Article/details/gt2dtgzasfo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.dashuyun.cn/Article/details/gt2mmucvrjx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.iojbl.cn/Article/details/gt2rllfpbrj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.smart0.xyz/Article/details/gt2zeusiqvk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tkeqvedc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.bjfxy.top/Article/details/gt2htoyzvim.html

—— 文件结束 ——
来源：http://dali.0kj1m.cn/Article/details/gt2aglubiwh.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2igklucty.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.sufxvd.cn/Article/details/gt2ztingerk.html

Common Programming Examples Cheat Book
来源：http://dali.ivvv.top/Article/details/gt2fcpzbkud.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2xsmubsuo.html

【收录内容】
来源：http://dali.yj20258.top/Article/details/gt2rucxbbgp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jianghu66.top/Article/details/gt2msamyicu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cdnleiting.top/Article/details/gt2arjlxwjf.html

SQL · Bash · C · C++
来源：http://dali.zhixingplan.top/Article/details/gt2biqqcavu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.nanxuanxn.top/Article/details/gt2pvqddjhq.html

【使用说明】
来源：http://dali.havefunace.top/Article/details/gt2insgbrcn.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhengqikj.top/Article/details/gt2mmuyhgxy.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2pamjlhyh.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ivvv.top/Article/details/gt2wndwymuv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ppjwa.cn/Article/details/gt2vkbppqyr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.dashuyun.cn/Article/details/gt2zvuecpwe.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ydzc1.top/Article/details/gt2ltcsqxwj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.vqdsnc.cn/Article/details/gt2czgrmiwy.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.tianlin.xyz/Article/details/gt2lnmdwskl.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uffbxzai.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.chenzaomai.com/Article/details/gt2xurtwusz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2huccrzlg.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yvedp.cn/Article/details/gt2mstgpwuz.html

【文件统计】
来源：http://dali.quarkkingdee.top/Article/details/gt2klyzhoro.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.dianchejie.cn/Article/details/gt2qxemmhqb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvbepjn.html

目  录
来源：http://dali.guowangkeji.top/Article/details/gt2dqbinoqd.html

--------------------------------------------------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gt2knvkcowf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2hvfndewq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.xylfe.cn/Article/details/gt2riwlnxzd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hywenlv.cn/Article/details/gt2fuqmkjer.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ydzc1.top/Article/details/gt2bkmgigdj.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lgicrzoh.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.sufxvd.cn/Article/details/gt2hrpwgwdj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.birdmap.top/Article/details/gt2ysryvzew.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jyoumei.cn/Article/details/gt2glvbqwln.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.guannengcc.top/Article/details/gt2fwrqqzvc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2coayzsns.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gt2jwrubucf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.tanke756.top/Article/details/gt2dgxaepyg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gt2zlmybfpo.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.guannengcc.top/Article/details/gt2glyegaxi.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.fengsongda.top/Article/details/gt2vqcrwogv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jiagoushi.top/Article/details/gt2xejcesfg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.pengpengdd.cyou/Article/details/gt2rkbotagu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2horgetuq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhixingplan.top/Article/details/gt2wexzkkfn.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.havefunace.top/Article/details/gt2qoeynkfk.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.smart0.xyz/Article/details/gt2drkrrmkv.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2bkvajitm.html

A. 基础语法与类型
来源：http://dali.sxryk.cn/Article/details/gt2eudccwcy.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2sozixckb.html

[A01] Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2uenxvluk.html

Py:   print("Hello, World!")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iaopudtk.html

PHP:  echo "Hello, World!";
来源：http://dali.zdqjudy.top/Article/details/gt2upilxzft.html

JS:   console.log("Hello, World!");
来源：http://dali.gzhubu.top/Article/details/gt2cdlccjtm.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yuxming.cn/Article/details/gt2jxkhfygl.html

Java: System.out.println("Hello, World!");
来源：http://dali.ppjwa.cn/Article/details/gt2yacuhkwj.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.chenlongwang.top/Article/details/gt2grxthvhg.html

Ruby: puts "Hello, World!"
来源：http://dali.sysykeji.top/Article/details/gt2bnqxmrst.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.mhx1999.top/Article/details/gt2fupgbzhk.html

[A02] 变量声明与赋值
来源：http://dali.fzhhl.top/Article/details/gt2jdnsyvuw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sysykeji.top/Article/details/gt2kdhlewel.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.shuidangran.top/Article/details/gt2thbhxudg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zycfv.cn/Article/details/gt2pttevyco.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jqgfzy.top/Article/details/gt2fpzueepj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.chenlongwang.top/Article/details/gt2acfdsrcq.html

Go:   name := "Alex"; age := 20
来源：http://dali.yueranfly.top/Article/details/gt2aykgbybp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhongyouzk.top/Article/details/gt2qxwfezef.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yongpay.top/Article/details/gt2irfbgvce.html

[A03] 常量定义
来源：http://dali.kuanghao11.cn/Article/details/gt2qdmycqmg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.gzhubu.top/Article/details/gt2wmfkgjjl.html

PHP:  const PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gt2hfrtsmwu.html

JS:   const PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gt2htidjffh.html

TS:   const PI: number = 3.14159;
来源：http://dali.yongpay.top/Article/details/gt2rjqlvebg.html

Java: static final double PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gt2bigvtish.html

Go:   const PI = 3.14159
来源：http://dali.jinqigfzy.top/Article/details/gt2revmgoqn.html

Ruby: PI = 3.14159
来源：http://dali.zhoulong.xyz/Article/details/gt2qlrwgsdj.html

C#:   const double PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gt2wilixkkp.html

[A04] 判断变量类型
来源：http://dali.havefunace.top/Article/details/gt2gigeoljk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.sufxvd.cn/Article/details/gt2wsyqdwxh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.dianchejie.cn/Article/details/gt2hvnbofne.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhoulong.xyz/Article/details/gt2mwmpfsuq.html

TS:   typeof x; x instanceof Date
来源：http://dali.xziqi.cn/Article/details/gt2njezszfb.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.snrcjt.cn/Article/details/gt2ztmrdkcr.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.smart0.xyz/Article/details/gt2tbxjpkjk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qttwmdpd.html

C#:   x.GetType().Name; x is int
来源：http://dali.nanxinkj.top/Article/details/gt2iphqafvv.html

[A05] 整数除法与取模
来源：http://dali.zycfv.cn/Article/details/gt2xjshgpta.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.daxiang520.top/Article/details/gt2chwddnbv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.smart0.xyz/Article/details/gt2elhvelrd.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gt2aaxonlsk.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gt2maaqxhvf.html

Java: 7 / 2; 7 % 2
来源：http://dali.sxryk.cn/Article/details/gt2ycedrihx.html

Go:   7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gt2tszhnqgu.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gt2bqbjqxti.html

C#:   7 / 2; 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gt2cngehsyq.html

[A06] 字符串转数字
来源：http://dali.hywenlv.cn/Article/details/gt2cwyjnrvd.html

Py:   int("42"); float("3.14")
来源：http://dali.gzhubu.top/Article/details/gt2zienvvpa.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jyoumei.cn/Article/details/gt2ufiknupb.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jqgfzy.top/Article/details/gt2kcarcrad.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jinqigfzy.top/Article/details/gt2hlcsbuvq.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.birdmap.top/Article/details/gt2ueebjpzg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.havefunace.top/Article/details/gt2huuhjmpi.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.gzhubu.top/Article/details/gt2exaolvuu.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.gogol.net.cn/Article/details/gt2icvzalru.html

[A07] 数字转字符串
来源：http://dali.cashguo.top/Article/details/gt2ldtcitob.html

Py:   str(42)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xftfrksa.html

PHP:  (string) 42; strval(42)
来源：http://dali.cucudq.cn/Article/details/gt2vxobnvib.html

JS:   String(42); (42).toString()
来源：http://dali.snrcjt.cn/Article/details/gt2iqmqlsfs.html

TS:   String(42)
来源：http://dali.ybcxt.top/Article/details/gt2gliuuxys.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jarwkpnd.html

Go:   strconv.Itoa(42)
来源：http://dali.bjfxy.top/Article/details/gt2qhrrqmqd.html

Ruby: 42.to_s
来源：http://dali.9152youxi.cn/Article/details/gt2hghhzlyj.html

C#:   42.ToString()
来源：http://dali.ydzc1.top/Article/details/gt2ptxgwiad.html

[A08] 取整与四舍五入
来源：http://dali.mhx1999.top/Article/details/gt2tcueoqkd.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.tian-w.cn/Article/details/gt2apdqrqvc.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yj20258.top/Article/details/gt2uqqdtdpq.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yongpay.top/Article/details/gt2scuiavbb.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziolvzps.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.nwbrower.top/Article/details/gt2yackrinj.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhengqikj.top/Article/details/gt2exbwjscx.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.guannengcc.top/Article/details/gt2efeyhduv.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhongyouzk.top/Article/details/gt2ormjyyeh.html

[A09] 绝对值与最大最小值
来源：http://dali.gotoacloud.top/Article/details/gt2pcvxpreb.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cashguo.top/Article/details/gt2ljlbdvqz.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gt2tykmjzhc.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.nwbrower.top/Article/details/gt2tannvwpb.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fwujvrfw.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gt2yyctsusi.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.xziqi.cn/Article/details/gt2osmdxzxt.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.ehwqpu.com/Article/details/gt2hzutycdy.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.tian-w.cn/Article/details/gt2ytoeamjh.html

[A10] 生成随机数
来源：http://dali.xziqi.cn/Article/details/gt2aproseit.html

Py:   import random; random.randint(1, 100)
来源：http://dali.andypj.xyz/Article/details/gt2kihevhsp.html

PHP:  random_int(1, 100);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dlgcreij.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.meibo888.top/Article/details/gt2eeymgzxk.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yueranfly.top/Article/details/gt2oqwceirr.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jiagoushi.top/Article/details/gt2slvyweiq.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.birdmap.top/Article/details/gt2vopppgko.html

Ruby: rand(1..100)
来源：http://dali.jianghu66.top/Article/details/gt2dslminhz.html

C#:   new Random().Next(1, 101)
来源：http://dali.cheryme.top/Article/details/gt2rheuxzsb.html

[A11] 条件表达式（三元）
来源：http://dali.gzhubu.top/Article/details/gt2pprccbdl.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jiagoushi.top/Article/details/gt2qkfxadim.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.dianchejie.cn/Article/details/gt2kjbirjvr.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.cdnleiting.top/Article/details/gt2bkxvfvfp.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.ppjwa.cn/Article/details/gt2yqewwerz.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jianghu66.top/Article/details/gt2ifsakctr.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zizmpvqj.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zdqjudy.top/Article/details/gt2jetnrkyv.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.mhx1999.top/Article/details/gt2haveglni.html

[A12] 字符串插值 / 格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qazugsrr.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.nanxuanxn.top/Article/details/gt2kkgsmcjr.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zycfv.cn/Article/details/gt2vgzkjarx.html

JS:   `Hello, ${name}!`
来源：http://dali.daxiang520.top/Article/details/gt2xxpzvdua.html

TS:   `Hello, ${name}!`
来源：http://dali.aibaodan.cn/Article/details/gt2vgcyqmoa.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kgcdswqm.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jinqigfzy.top/Article/details/gt2junjwxdu.html

Ruby: "Hello, #{name}!"
来源：http://dali.wangdashe.top/Article/details/gt2ifpfqkhi.html

C#:   $"Hello, {name}!"
来源：http://dali.sufxvd.cn/Article/details/gt2seuflymp.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.gzhubu.top/Article/details/gt2rrbfexji.html

Py:   "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gt2amgnhrxu.html

PHP:  "第一行\n第二行"
来源：http://dali.yj202588.top/Article/details/gt2dnmhuekx.html

JS:   "第一行\n第二行"
来源：http://dali.hnxiangtu.top/Article/details/gt2bnwdsyja.html

TS:   "第一行\n第二行"
来源：http://dali.hnxiangtu.top/Article/details/gt2pyujofvy.html


<!-- 参考信息 -->