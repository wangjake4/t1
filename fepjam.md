代发 wailian999

[U81] JS：初始化项目
来源：http://dali.iojbl.cn/Article/details/gt2wcjaxbfm.html

npm init -y;  npm i express
来源：http://dali.birdmap.top/Article/details/gt2vynafswy.html

[U82] JS：package.json 脚本
来源：http://dali.mhx1999.top/Article/details/gt2dmuvsuoy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.nanxuanxn.top/Article/details/gt2klbmbzez.html

[U83] JS：ES Module 导入导出
来源：http://dali.xylfe.cn/Article/details/gt2pdxdkfco.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.c1oappe.top/Article/details/gt2onrxipew.html

[U84] JS：CommonJS 写法
来源：http://dali.jlsjyb.cn/Article/details/gt2ukrrruee.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shuidangran.top/Article/details/gt2yodvvwwu.html

[U85] JS：可选链
来源：http://dali.c1oappe.top/Article/details/gt2zxxnitdt.html

a?.b?.c
来源：http://dali.aizwys.cn/Article/details/gt2jgevocsm.html

[U86] JS：空值合并
来源：http://dali.daria6918.cn/Article/details/gt2gdfvelfl.html

a ?? b
来源：http://dali.hfpthk.cn/Article/details/gt2qhdhvxhk.html

[U87] JS：解构默认值
来源：http://dali.9152youxi.cn/Article/details/gt2lnilrhwa.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hfpthk.cn/Article/details/gt2genhygvq.html

[U88] JS：对象展开合并
来源：http://dali.chenzaomai.com/Article/details/gt2zrfkhfyt.html

{ ...a, ...b }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zakliapc.html

[U89] JS：数组去重
来源：http://dali.shangyingyoupin.top/Article/details/gt2umcrvqdp.html

[...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gt2wmhwqaos.html

[U90] JS：数字数组排序
来源：http://dali.nanxinkj.top/Article/details/gt2cxathxvf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gt2xlzvxfqc.html

[U91] JS：对象键值遍历
来源：http://dali.smart0.xyz/Article/details/gt2tjqxbsht.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhengqikj.top/Article/details/gt2ugtuqtku.html

[U92] JS：深拷贝
来源：http://dali.hnqzz.top/Article/details/gt2dagwfqdw.html

structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2ncqpxmdu.html

[U93] JS：模板字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2kalcfstb.html

`共 ${n} 条`
来源：http://dali.shzxlz.cn/Article/details/gt2cyboqtrl.html

[U94] JS：箭头函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2xquwawne.html

const double = x => x * 2;
来源：http://dali.guannengcc.top/Article/details/gt2uyglcono.html

[U95] JS：Promise 包装
来源：http://dali.0kj1m.cn/Article/details/gt2hyekzloi.html

new Promise((resolve, reject) => {})
来源：http://dali.quarkkingdee.top/Article/details/gt2ehbkjihv.html

[U96] JS：async/await 与异常
来源：http://dali.jiagoushi.top/Article/details/gt2vssydplz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gt2qxybfamv.html

[U97] JS：并发请求
来源：http://dali.shzxlz.cn/Article/details/gt2ezuujcgl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gt2yknbirvh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2szawotwl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yj20258888.top/Article/details/gt2twnalejj.html

[U99] JS：事件监听
来源：http://dali.yuxming.cn/Article/details/gt2ipxwcwsg.html

el.addEventListener("click", e => {})
来源：http://dali.aizwys.cn/Article/details/gt2dafqzicr.html

[U100] JS：DOM 查询
来源：http://dali.kuanghao11.cn/Article/details/gt2rxhdcfvv.html

document.querySelector(".item")
来源：http://dali.cheryme.top/Article/details/gt2gxmyutjs.html

[U101] JS：classList 操作
来源：http://dali.yueranfly.top/Article/details/gt2eutyscqd.html

el.classList.toggle("active")
来源：http://dali.mhx1999.top/Article/details/gt2fzjpelus.html

[U102] JS：本地存储
来源：http://dali.cheryme.top/Article/details/gt2vlcoenss.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.fengsongda.top/Article/details/gt2sdiyggug.html

[U103] JS：定时器
来源：http://dali.cucudq.cn/Article/details/gt2vufttomj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinqigfzy.top/Article/details/gt2vekmumao.html

[U104] JS：防抖
来源：http://dali.redwolf501.top/Article/details/gt2riwedctn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gt2vfhmgusi.html

[U105] JS：节流
来源：http://dali.kuanghao11.cn/Article/details/gt2omqzcplu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ppjwa.cn/Article/details/gt2xrqnachv.html

[U106] JS：日期格式化
来源：http://dali.jianghu66.top/Article/details/gt2uuadmucs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2crfupzek.html

[U107] JS：数字千分位
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dylcaksa.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.birdmap.top/Article/details/gt2undddalc.html

[U108] JS：随机整数
来源：http://dali.dianchejie.cn/Article/details/gt2djxspffu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.nanxuanxn.top/Article/details/gt2qxnkbrgf.html

[U109] JS：数组分组
来源：http://dali.yonumen.top/Article/details/gt2cvtxehgs.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jvxzfstg.html

[U110] JS：数组分块
来源：http://dali.jinqigufen.top/Article/details/gt2unffxjzx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.tianlin.xyz/Article/details/gt2svpcdyez.html

[U111] JS：对象转 Map
来源：http://dali.yangfankeji.com/Article/details/gt2zkqnsgvd.html

new Map(Object.entries(obj))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ibqabsul.html

[U112] JS：字符串补位
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mwxpyaeb.html

"7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gt2zxzdsbvh.html

[U113] JS：正则替换全部
来源：http://dali.havefunace.top/Article/details/gt2oftwrkdl.html

s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gt2qkxckclk.html

[U114] JS：JSON 深比较
来源：http://dali.yj20258.top/Article/details/gt2elurvvyh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangdashe.top/Article/details/gt2mcetcwxd.html

[U115] JS：生成 UUID
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jppvqdkr.html

crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gt2akrnolyi.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ndxzdheq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2quhgeeml.html

[U117] JS：单元测试
来源：http://dali.hysaishi.cn/Article/details/gt2opqbreuk.html

npm i -D vitest;  npx vitest
来源：http://dali.daxiang520.top/Article/details/gt2pfkrdzbx.html

[U118] JS：开发服务器
来源：http://dali.zhoulong.xyz/Article/details/gt2obeatkra.html

npm i -D vite;  npx vite
来源：http://dali.sufxvd.cn/Article/details/gt2vjnuiiqr.html

[U119] JS：生产构建
来源：http://dali.gzhubu.top/Article/details/gt2vlrvmmzd.html

npx vite build
来源：http://dali.gogol.net.cn/Article/details/gt2iqqeliyr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yvedp.cn/Article/details/gt2aygjkdap.html

import.meta.env.VITE_API_URL
来源：http://dali.hnqzz.top/Article/details/gt2matimqze.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2fqdvqgxa.html

统计汇总
来源：http://dali.daxiang520.top/Article/details/gt2dcxiugsi.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2flzolhtc.html

按语言统计（条）：
来源：http://dali.sweek.top/Article/details/gt2xacggihj.html

Python ......... 252
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fgjutcpe.html

PHP ............ 252
来源：http://dali.yuanzhike.top/Article/details/gt2hfanazbl.html

JavaScript ..... 252
来源：http://dali.cqqwz.cn/Article/details/gt2baczcjyd.html

TypeScript ..... 212
来源：http://dali.0kj1m.cn/Article/details/gt2nvcolwxr.html

Java ........... 212
来源：http://dali.nanxinkj.top/Article/details/gt2pyoimdqh.html

Go ............. 212
来源：http://dali.sufxvd.cn/Article/details/gt2tiwvjiwm.html

Ruby ........... 212
来源：http://dali.jqgfzy.top/Article/details/gt2qrrqblsk.html

C# ............. 212
来源：http://dali.sxryk.cn/Article/details/gt2thlkavkf.html

C .............. 30
来源：http://dali.yueranfly.top/Article/details/gt2phupmztt.html

C++ ............ 30
来源：http://dali.snrcjt.cn/Article/details/gt2zjxwjbvm.html

SQL ............ 90
来源：http://dali.nanxinkj.top/Article/details/gt2duyhdtkt.html

Bash ........... 80
来源：http://dali.daria6918.cn/Article/details/gt2zgqahgvs.html

Kotlin ......... 15
来源：http://dali.shzxlz.cn/Article/details/gt2batbxdvb.html

Swift .......... 15
来源：http://dali.xylfe.cn/Article/details/gt2ylotwtzs.html

Lua ............ 10
来源：http://dali.smart0.xyz/Article/details/gt2fxiaavvl.html

Perl ........... 10
来源：http://dali.hysaishi.cn/Article/details/gt2tyndtsej.html

Scala .......... 10
来源：http://dali.chenjidiqi.icu/Article/details/gt2mzgjhojp.html

------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gt2dnkbujni.html

合计 ........... 2106 条
来源：http://dali.gaohongyu789.top/Article/details/gt2yczghqet.html

按章节统计：
来源：http://dali.jqgufenzy.top/Article/details/gt2peifbydj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gotoacloud.top/Article/details/gt2wyyskozj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gt2iayrovll.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cheryme.top/Article/details/gt2tblijlxt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shuidangran.top/Article/details/gt2lgotlzxr.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jlsjyb.cn/Article/details/gt2rxqcudgz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hfpthk.cn/Article/details/gt2nmwlrycq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yanxiufei.cn/Article/details/gt2qsvkpuza.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jnetsmvu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gt2jvsasfqc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.haohaochexian.top/Article/details/gt2nxegyijx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gt2uuqplskw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gt2uwpuupwy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wozvivfn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jlsjyb.cn/Article/details/gt2zlklabae.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.nanxinkj.top/Article/details/gt2gkytxuir.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gt2aunsospu.html

Q SQL 专题                              90
来源：http://dali.yj20258.top/Article/details/gt2ptswupxm.html

R Bash 专题                             80
来源：http://dali.chenlongwang.top/Article/details/gt2nkpffwlo.html

S C / C++ 专题                          60
来源：http://dali.snrcjt.cn/Article/details/gt2tcnlxfzp.html

T 其他语言补充                          60
来源：http://dali.pycfn.com/Article/details/gt2ugbuyncf.html

U 高频实用片段                         120
来源：http://dali.hammf.cn/Article/details/gt2vqgnfein.html

------------------------------------
来源：http://dali.zycfv.cn/Article/details/gt2moikzuhj.html

合计                                  2106 条
来源：http://dali.cashguo.top/Article/details/gt2tufonmrj.html

--------------------------------------------------------------------------------
来源：http://dali.smart0.xyz/Article/details/gt2btqrxgrw.html

使用提醒
来源：http://dali.kuanghao11.cn/Article/details/gt2oqvobyoz.html

--------------------------------------------------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gt2izfyjdoi.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.chenjidiqi.icu/Article/details/gt2ydoempgb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ydzc1.top/Article/details/gt2jzzerzwb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ccqhxdfq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.redwolf501.top/Article/details/gt2wskhvdgz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.nanxuanxn.top/Article/details/gt2ymxklosd.html

—— 文件结束 ——
来源：http://dali.nanxuanxn.top/Article/details/gt2jcimjfbq.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2badnthrq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ednhduop.html

Common Programming Examples Cheat Book
来源：http://dali.ehwqpu.com/Article/details/gt2ntqxccuc.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2xvlfxgmx.html

【收录内容】
来源：http://dali.sufxvd.cn/Article/details/gt2uxzgwlsn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.316326.xyz/Article/details/gt2kqawnalh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.c1oappe.top/Article/details/gt2auzazvyj.html

SQL · Bash · C · C++
来源：http://dali.hammf.cn/Article/details/gt2jzaxkklk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.haohaochexian.top/Article/details/gt2imycmkrc.html

【使用说明】
来源：http://dali.xylfe.cn/Article/details/gt2kawpehuy.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yueranfly.top/Article/details/gt2elhrahhn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.sysykeji.top/Article/details/gt2wmgphjkk.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.nwbrower.top/Article/details/gt2yuvngzse.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.tianlin.xyz/Article/details/gt2gdnuduhv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.pengpengdd.cyou/Article/details/gt2xghlzaqq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xziqi.cn/Article/details/gt2jqaeaath.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hongshengwenyu.top/Article/details/gt2dvfffkyo.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hammf.cn/Article/details/gt2avwqdszq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hywenlv.cn/Article/details/gt2psnudzdy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aybpqgqk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xmollebf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.wangdashe.top/Article/details/gt2cydrabav.html

【文件统计】
来源：http://dali.hywenlv.cn/Article/details/gt2sswedxqm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.nanxinkj.top/Article/details/gt2btzgzqkp.html

--------------------------------------------------------------------------------
来源：http://dali.aizwys.cn/Article/details/gt2bowzrgny.html

目  录
来源：http://dali.pengpengdd.cyou/Article/details/gt2nkpkycpe.html

--------------------------------------------------------------------------------
来源：http://dali.hnqzz.top/Article/details/gt2tlejwayp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yangfankeji.com/Article/details/gt2tpxyqzoh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2tpuedmti.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mwrpchcl.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jqgfzy.top/Article/details/gt2ehmhgode.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2ctlqwbvb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2cmbyqxzy.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yuanzhike.top/Article/details/gt2cqwupnvi.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yj20258888.top/Article/details/gt2nsxprsaj.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gt2dzdshsls.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2hdxidcdl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gt2rrtluoid.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gt2hsqybist.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gt2emtrtlxg.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.mhx1999.top/Article/details/gt2mlprefwp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shzxlz.cn/Article/details/gt2oecuwdwl.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.guannengcc.top/Article/details/gt2yxumvqmg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jiagoushi.top/Article/details/gt2ajdqjeqv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yueranfly.top/Article/details/gt2hygurvkd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ttrzlmdq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yvedp.cn/Article/details/gt2tujongpx.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jyoumei.cn/Article/details/gt2cswnwybv.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2yvazknpa.html

A. 基础语法与类型
来源：http://dali.jqgufenzy.top/Article/details/gt2sznsjmxt.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ckyosatn.html

[A01] Hello World
来源：http://dali.fzhhl.top/Article/details/gt2siwlbkqn.html

Py:   print("Hello, World!")
来源：http://dali.iojbl.cn/Article/details/gt2fazyemaw.html

PHP:  echo "Hello, World!";
来源：http://dali.jyoumei.cn/Article/details/gt2spkyrnbp.html

JS:   console.log("Hello, World!");
来源：http://dali.iojbl.cn/Article/details/gt2zzkhnbiy.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yanxiufei.cn/Article/details/gt2fnwjwbuy.html

Java: System.out.println("Hello, World!");
来源：http://dali.andypj.xyz/Article/details/gt2hnwifyyq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.nwbrower.top/Article/details/gt2xlmqbudi.html

Ruby: puts "Hello, World!"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sbryzsqf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.tanke756.top/Article/details/gt2eyuqrgkp.html

[A02] 变量声明与赋值
来源：http://dali.hnqzz.top/Article/details/gt2toilshpl.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.wangshuangyany.cn/Article/details/gt2ykczgwjv.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.iojbl.cn/Article/details/gt2eijquiyg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yangfankeji.com/Article/details/gt2ejwpypie.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xuetiantiany.cn/Article/details/gt2xfauwown.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yj20258.top/Article/details/gt2aosqxtzj.html

Go:   name := "Alex"; age := 20
来源：http://dali.yonumen.top/Article/details/gt2mdoeaskl.html

Ruby: name = "Alex"; age = 20
来源：http://dali.feifeiyinyue.top/Article/details/gt2dzpasyzz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.birdmap.top/Article/details/gt2bgsspurf.html

[A03] 常量定义
来源：http://dali.yuxming.cn/Article/details/gt2owvtxixh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jqgfzy.top/Article/details/gt2bwhsgimm.html

PHP:  const PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gt2acnjqjjc.html

JS:   const PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gt2tlzyzagt.html

TS:   const PI: number = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gt2znwgpbkd.html

Java: static final double PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gt2citfyjnx.html

Go:   const PI = 3.14159
来源：http://dali.hywenlv.cn/Article/details/gt2ayaqqwtb.html

Ruby: PI = 3.14159
来源：http://dali.jinqigufen.top/Article/details/gt2fmtquggz.html

C#:   const double PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gt2jnypizts.html

[A04] 判断变量类型
来源：http://dali.zhengqikj.top/Article/details/gt2uxysxtxe.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yonumen.top/Article/details/gt2xhvigwpb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.fengsongda.top/Article/details/gt2xaimdwqj.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.andypj.xyz/Article/details/gt2hnnswxya.html

TS:   typeof x; x instanceof Date
来源：http://dali.yonumen.top/Article/details/gt2plwhmqel.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xuanzx.com/Article/details/gt2jimggqhw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.pycfn.com/Article/details/gt2yikkfxmn.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wvendfcy.html

C#:   x.GetType().Name; x is int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gcurjhrq.html

[A05] 整数除法与取模
来源：http://dali.tianlin.xyz/Article/details/gt2espszbqw.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xylfe.cn/Article/details/gt2aazgozeo.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.bjfxy.top/Article/details/gt2talrfpum.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.smart0.xyz/Article/details/gt2bblxzudf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gt2lmpsxtva.html

Java: 7 / 2; 7 % 2
来源：http://dali.yueranfly.top/Article/details/gt2oiyozjqx.html

Go:   7 / 2; 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gt2wmlhaukv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.cheryme.top/Article/details/gt2ouegutdr.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gsfaojni.html

[A06] 字符串转数字
来源：http://dali.chenlongwang.top/Article/details/gt2akfccwbm.html

Py:   int("42"); float("3.14")
来源：http://dali.xuanzx.com/Article/details/gt2nmsqfjyt.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.tian-w.cn/Article/details/gt2ushrwthy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.shzxlz.cn/Article/details/gt2otbwrmzy.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.0kj1m.cn/Article/details/gt2osodfgcb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.meibo888.top/Article/details/gt2hgusvffb.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2svtqrmoz.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2kknqeoov.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yvedp.cn/Article/details/gt2vjuxwfur.html

[A07] 数字转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2vzmcdomm.html

Py:   str(42)
来源：http://dali.316326.xyz/Article/details/gt2jwgvjhtp.html

PHP:  (string) 42; strval(42)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pzgbrmis.html

JS:   String(42); (42).toString()
来源：http://dali.xylfe.cn/Article/details/gt2vgrkccqx.html

TS:   String(42)
来源：http://dali.zhongyouzk.top/Article/details/gt2gqbagjmc.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pjjtbeds.html

Go:   strconv.Itoa(42)
来源：http://dali.andypj.xyz/Article/details/gt2tczrpvxb.html

Ruby: 42.to_s
来源：http://dali.snrcjt.cn/Article/details/gt2buurdmzy.html

C#:   42.ToString()
来源：http://dali.nanxuanxn.top/Article/details/gt2ytehsyet.html

[A08] 取整与四舍五入
来源：http://dali.fengsongda.top/Article/details/gt2ucmwpsop.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.cashguo.top/Article/details/gt2eitrpepf.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.birdmap.top/Article/details/gt2vmicplif.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gt2qyrbfoow.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.daxiang520.top/Article/details/gt2itdyxtgz.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hywenlv.cn/Article/details/gt2sueeimfa.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2shkkhctq.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.cdnleiting.top/Article/details/gt2bineatwj.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hnxiangtu.top/Article/details/gt2ciovwybx.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2dylkgxno.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jqgfzy.top/Article/details/gt2utzxytli.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zkiskhbw.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yj20258.top/Article/details/gt2uorcjsjw.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.fengsongda.top/Article/details/gt2lrgzkdnr.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2nkatqceb.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtfsidq.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.havefunace.top/Article/details/gt2igjpdhns.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.daxiang520.top/Article/details/gt2zmikvdwd.html

[A10] 生成随机数
来源：http://dali.cdnleiting.top/Article/details/gt2fexalumz.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jqgfzy.top/Article/details/gt2oljobxkq.html

PHP:  random_int(1, 100);
来源：http://dali.yuanzhike.top/Article/details/gt2oxbnrlfa.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2yemkppeq.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yangfankeji.com/Article/details/gt2sudgklbs.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yj20258888.top/Article/details/gt2xkhjydut.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.9152youxi.cn/Article/details/gt2bdwuftmq.html

Ruby: rand(1..100)
来源：http://dali.snrcjt.cn/Article/details/gt2knfnxqyt.html

C#:   new Random().Next(1, 101)
来源：http://dali.hnxiangtu.top/Article/details/gt2fqwszxvu.html

[A11] 条件表达式（三元）
来源：http://dali.yanxiufei.cn/Article/details/gt2iqehkmtl.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2smgyrukg.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.dianchejie.cn/Article/details/gt2bteorrez.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.mhx1999.top/Article/details/gt2qgfkfvga.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.c1oappe.top/Article/details/gt2qnlnwbyr.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.fzhhl.top/Article/details/gt2xhovaqsi.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.nanxinkj.top/Article/details/gt2bkxcxghq.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojtaypfg.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yanxiufei.cn/Article/details/gt2nemedehj.html

[A12] 字符串插值 / 格式化
来源：http://dali.hfpthk.cn/Article/details/gt2zdpsktaf.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.guannengcc.top/Article/details/gt2flwukzzb.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.ehwqpu.com/Article/details/gt2kctcleqe.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2wosuhdnj.html

TS:   `Hello, ${name}!`
来源：http://dali.birdmap.top/Article/details/gt2nowhwgug.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.ivvv.top/Article/details/gt2tduyzioj.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yueranfly.top/Article/details/gt2yvitshaw.html

Ruby: "Hello, #{name}!"
来源：http://dali.gotoacloud.top/Article/details/gt2yrzeuqxm.html

C#:   $"Hello, {name}!"
来源：http://dali.nanxuanxn.top/Article/details/gt2skokgptt.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.hywenlv.cn/Article/details/gt2gwwgtgcc.html

Py:   "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gt2tkpftytm.html

PHP:  "第一行\n第二行"
来源：http://dali.hfpthk.cn/Article/details/gt2lqxlgyxl.html

JS:   "第一行\n第二行"
来源：http://dali.hywenlv.cn/Article/details/gt2muanfoyw.html

TS:   "第一行\n第二行"
来源：http://dali.zhengqikj.top/Article/details/gt2rsyhkjfs.html


<!-- 参考信息 -->