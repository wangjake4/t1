代发 wailian999

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gtrhvregxq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hongshengwenyu.top/Article/details/gtfecgzbux.html

[U84] JS：CommonJS 写法
来源：http://dali.gotoacloud.top/Article/details/gttidcbcqy.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xuetiantiany.cn/Article/details/gtwgpfqdaf.html

[U85] JS：可选链
来源：http://dali.pengpengdd.cyou/Article/details/gtxmgwctgy.html

a?.b?.c
来源：http://dali.wangshuangyany.cn/Article/details/gthztdmhmz.html

[U86] JS：空值合并
来源：http://dali.ehwqpu.com/Article/details/gtavmbwxhr.html

a ?? b
来源：http://dali.gotoacloud.top/Article/details/gtzhzvkmti.html

[U87] JS：解构默认值
来源：http://dali.haohaochexian.top/Article/details/gtqflevrnx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvkzrqgz.html

[U88] JS：对象展开合并
来源：http://dali.snrcjt.cn/Article/details/gtalwkzdjx.html

{ ...a, ...b }
来源：http://dali.haohaochexian.top/Article/details/gtgdxmzvxu.html

[U89] JS：数组去重
来源：http://dali.nwbrower.top/Article/details/gtldgzddur.html

[...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmepdssn.html

[U90] JS：数字数组排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwblhwbtd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gtvlnfwrwp.html

[U91] JS：对象键值遍历
来源：http://dali.nanxuanxn.top/Article/details/gtedgnajza.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.bjfxy.top/Article/details/gtsnunxoyk.html

[U92] JS：深拷贝
来源：http://dali.yanxiufei.cn/Article/details/gtakmlkaaz.html

structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtnoytitab.html

[U93] JS：模板字符串
来源：http://dali.nanxinkj.top/Article/details/gtzrsogrqy.html

`共 ${n} 条`
来源：http://dali.jinqigufen.top/Article/details/gtuarvqtfr.html

[U94] JS：箭头函数
来源：http://dali.bjfxy.top/Article/details/gtavbsezuo.html

const double = x => x * 2;
来源：http://dali.shuidangran.top/Article/details/gtxaxtwcsl.html

[U95] JS：Promise 包装
来源：http://dali.meibo888.top/Article/details/gtckptxtop.html

new Promise((resolve, reject) => {})
来源：http://dali.tanke756.top/Article/details/gtmwrxveub.html

[U96] JS：async/await 与异常
来源：http://dali.cashguo.top/Article/details/gtjtlypjmu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gtxjzdklrh.html

[U97] JS：并发请求
来源：http://dali.chenjidiqi.icu/Article/details/gtwiqcmjyb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gtbaznggff.html

[U98] JS：fetch 带 JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtaywalmjm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.kuanghao11.cn/Article/details/gtxomffbju.html

[U99] JS：事件监听
来源：http://dali.fzhhl.top/Article/details/gtmcnfvhbi.html

el.addEventListener("click", e => {})
来源：http://dali.chenzaomai.com/Article/details/gtpfpcvuvh.html

[U100] JS：DOM 查询
来源：http://dali.redwolf501.top/Article/details/gtoinazjjm.html

document.querySelector(".item")
来源：http://dali.shangyingyoupin.top/Article/details/gtwdsetgml.html

[U101] JS：classList 操作
来源：http://dali.feifeiyinyue.top/Article/details/gtftmtwanv.html

el.classList.toggle("active")
来源：http://dali.ybcxt.top/Article/details/gtxqajvytt.html

[U102] JS：本地存储
来源：http://dali.smart0.xyz/Article/details/gtlqphqqku.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ybcxt.top/Article/details/gtcuyvawol.html

[U103] JS：定时器
来源：http://dali.chenjidiqi.icu/Article/details/gthzztqhos.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jiagoushi.top/Article/details/gtcsdjxqic.html

[U104] JS：防抖
来源：http://dali.cqqwz.cn/Article/details/gtgzuajwim.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gtcyfilyde.html

[U105] JS：节流
来源：http://dali.gotoacloud.top/Article/details/gtehcjtdng.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tanke756.top/Article/details/gthtbjbtqn.html

[U106] JS：日期格式化
来源：http://dali.cheryme.top/Article/details/gtetutzaen.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yangfankeji.com/Article/details/gtinsdkbkj.html

[U107] JS：数字千分位
来源：http://dali.kuanghao11.cn/Article/details/gttsiekcyy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xziqi.cn/Article/details/gtxuopdepm.html

[U108] JS：随机整数
来源：http://dali.ydzc1.top/Article/details/gtluojhfrk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.daxiang520.top/Article/details/gtcfxyghnx.html

[U109] JS：数组分组
来源：http://dali.chenjidiqi.icu/Article/details/gtqempluia.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jqgufenzy.top/Article/details/gtapnxbpfx.html

[U110] JS：数组分块
来源：http://dali.gzhubu.top/Article/details/gtuoohroei.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hnqzz.top/Article/details/gtpbuvgijy.html

[U111] JS：对象转 Map
来源：http://dali.bjfxy.top/Article/details/gtxjadyxrl.html

new Map(Object.entries(obj))
来源：http://dali.chenjidiqi.icu/Article/details/gtxfkfvmrf.html

[U112] JS：字符串补位
来源：http://dali.yuanzhike.top/Article/details/gtqoaiqrrc.html

"7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtpjfkfcdd.html

[U113] JS：正则替换全部
来源：http://dali.sufxvd.cn/Article/details/gtdsmgqrew.html

s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtrqbmprsy.html

[U114] JS：JSON 深比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtudogdfwe.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.vqdsnc.cn/Article/details/gtatlnzzxb.html

[U115] JS：生成 UUID
来源：http://dali.andypj.xyz/Article/details/gtbzzcvomm.html

crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gtxuvjkovb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hnxiangtu.top/Article/details/gtgplldcsj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yj202588.top/Article/details/gtvjqdxfyc.html

[U117] JS：单元测试
来源：http://dali.mhx1999.top/Article/details/gtupalxbgr.html

npm i -D vitest;  npx vitest
来源：http://dali.yangfankeji.com/Article/details/gtzrkplfyf.html

[U118] JS：开发服务器
来源：http://dali.dashuyun.cn/Article/details/gtrwihobyr.html

npm i -D vite;  npx vite
来源：http://dali.jyoumei.cn/Article/details/gteinwfdbv.html

[U119] JS：生产构建
来源：http://dali.wangshuangyany.cn/Article/details/gteavcpfrh.html

npx vite build
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpoetrwu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hnxiangtu.top/Article/details/gtyoegllzd.html

import.meta.env.VITE_API_URL
来源：http://dali.nwbrower.top/Article/details/gtzefbfdbg.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gthpqnenno.html

统计汇总
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsgakfhhu.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtvdlzzbls.html

按语言统计（条）：
来源：http://dali.hysaishi.cn/Article/details/gtfbrawwan.html

Python ......... 252
来源：http://dali.hnqzz.top/Article/details/gtsujdruxo.html

PHP ............ 252
来源：http://dali.shangyingyoupin.top/Article/details/gtnyezypyz.html

JavaScript ..... 252
来源：http://dali.yvedp.cn/Article/details/gtswvtxqwg.html

TypeScript ..... 212
来源：http://dali.jyoumei.cn/Article/details/gtumqumafo.html

Java ........... 212
来源：http://dali.aizwys.cn/Article/details/gtthouriad.html

Go ............. 212
来源：http://dali.ivvv.top/Article/details/gtukedolrr.html

Ruby ........... 212
来源：http://dali.yj20258888.top/Article/details/gtatenfemb.html

C# ............. 212
来源：http://dali.mhx1999.top/Article/details/gtsdnokuzc.html

C .............. 30
来源：http://dali.kuanghao11.cn/Article/details/gtqgcoxwyb.html

C++ ............ 30
来源：http://dali.pycfn.com/Article/details/gtauyesgun.html

SQL ............ 90
来源：http://dali.chenzaomai.com/Article/details/gtucflumjx.html

Bash ........... 80
来源：http://dali.cheryme.top/Article/details/gtylodcgmd.html

Kotlin ......... 15
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxhkavmf.html

Swift .......... 15
来源：http://dali.tianlin.xyz/Article/details/gtkvqfitvc.html

Lua ............ 10
来源：http://dali.yuanzhike.top/Article/details/gtptscihmf.html

Perl ........... 10
来源：http://dali.aibaodan.cn/Article/details/gtstlhjiib.html

Scala .......... 10
来源：http://dali.yuxming.cn/Article/details/gtzebgezvq.html

------------------------------------
来源：http://dali.jinqigfzy.top/Article/details/gtkwkezazw.html

合计 ........... 2106 条
来源：http://dali.chenlongwang.top/Article/details/gtclsdkzqt.html

按章节统计：
来源：http://dali.iojbl.cn/Article/details/gtgtkkxauo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sweek.top/Article/details/gtbenkdsnr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sweek.top/Article/details/gtxmukpajp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.chenjidiqi.icu/Article/details/gtmphmqcfg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sxryk.cn/Article/details/gtuzrxxkeu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ehwqpu.com/Article/details/gtdyfpfzce.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangkeji.top/Article/details/gtseltipyf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tanke756.top/Article/details/gtzxvepnyu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xinyue.icu/Article/details/gtumaepcwc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gtnrnsvvdd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xylfe.cn/Article/details/gtbalmbgxi.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gtffetjbfu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gtyoinoiek.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gtjkkusajf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.gotoacloud.top/Article/details/gtuvalouac.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.gaohongyu789.top/Article/details/gtluxpwgod.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gtiylrwksw.html

Q SQL 专题                              90
来源：http://dali.hfpthk.cn/Article/details/gtsxxlaxet.html

R Bash 专题                             80
来源：http://dali.hongshengwenyu.top/Article/details/gtgstefqmt.html

S C / C++ 专题                          60
来源：http://dali.yonumen.top/Article/details/gtkqdrbcro.html

T 其他语言补充                          60
来源：http://dali.chenjidiqi.icu/Article/details/gthjeghuzu.html

U 高频实用片段                         120
来源：http://dali.zdqjudy.top/Article/details/gtqtclffid.html

------------------------------------
来源：http://dali.yj20258.top/Article/details/gtryunmsja.html

合计                                  2106 条
来源：http://dali.ivvv.top/Article/details/gtshrvaday.html

--------------------------------------------------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gteiwhffhq.html

使用提醒
来源：http://dali.wangdashe.top/Article/details/gtuiznbxxo.html

--------------------------------------------------------------------------------
来源：http://dali.yongpay.top/Article/details/gtudvpzkul.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ydzc1.top/Article/details/gtuhzyvztt.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ydzc1.top/Article/details/gtfwuklnop.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.chenjidiqi.icu/Article/details/gtqxlqzkmo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jiagoushi.top/Article/details/gtyvhyoxbf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.snrcjt.cn/Article/details/gtgckvjojn.html

—— 文件结束 ——
来源：http://dali.xuanzx.com/Article/details/gtzddwgyxw.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtmtkkbuex.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.wangdashe.top/Article/details/gtzthhrrkd.html

Common Programming Examples Cheat Book
来源：http://dali.wangdashe.top/Article/details/gtlfgrxpre.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtfnuijzld.html

【收录内容】
来源：http://dali.zdqjudy.top/Article/details/gtqxujexaa.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.sweek.top/Article/details/gtulmnclht.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.chenjidiqi.icu/Article/details/gtpzgdiift.html

SQL · Bash · C · C++
来源：http://dali.zhixingplan.top/Article/details/gtnnjyzmht.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.nanxinkj.top/Article/details/gtxedpcsos.html

【使用说明】
来源：http://dali.xylfe.cn/Article/details/gtrnytwssd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yuxming.cn/Article/details/gtibsrtnxq.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ppjwa.cn/Article/details/gtbbcofqtj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.vqdsnc.cn/Article/details/gtwpbbaihe.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.svipenyu.cn/Article/details/gtwaujwkpj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ivvv.top/Article/details/gtmepwggzw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hfpthk.cn/Article/details/gtpbchejjq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdajricq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.fengsongda.top/Article/details/gtitjmpelp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shuidangran.top/Article/details/gtndzptrsa.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jqgufenzy.top/Article/details/gtgsrovuiz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.gzhubu.top/Article/details/gtcmhiqhmp.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jianghu66.top/Article/details/gtdqcbzdin.html

【文件统计】
来源：http://dali.yj202588.top/Article/details/gtygrfnuqu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yueranfly.top/Article/details/gtmtozjfjj.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gtfigczyfu.html

目  录
来源：http://dali.havefunace.top/Article/details/gttcloxipe.html

--------------------------------------------------------------------------------
来源：http://dali.sysykeji.top/Article/details/gtooyrughk.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ehwqpu.com/Article/details/gtwatnpatl.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ppjwa.cn/Article/details/gtbqarbrad.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.mhx1999.top/Article/details/gtrxlnsgmw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhongyouzk.top/Article/details/gtnlsyifmy.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yvedp.cn/Article/details/gtkodjoeko.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.shuidangran.top/Article/details/gtzarkzufu.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqwrzpba.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zdqjudy.top/Article/details/gtmzbxpvol.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shzxlz.cn/Article/details/gtlozpkvva.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhoulong.xyz/Article/details/gtbwaajjad.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gtqcbznxvs.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfshxiki.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gtraosajiq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.quarkkingdee.top/Article/details/gtrzvxiuyk.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hfpthk.cn/Article/details/gtkmyxvthe.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.aizwys.cn/Article/details/gtyahcidkm.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yj202588.top/Article/details/gtbflvdlnk.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.gzhubu.top/Article/details/gtkxcfdcjk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.svipenyu.cn/Article/details/gttkdylfce.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258888.top/Article/details/gtmzurcvba.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sufxvd.cn/Article/details/gtunvhmxax.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtripsqpwq.html

A. 基础语法与类型
来源：http://dali.daria6918.cn/Article/details/gtdiemaeoi.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtcmvlywmz.html

[A01] Hello World
来源：http://dali.jqgufenzy.top/Article/details/gthqvgntko.html

Py:   print("Hello, World!")
来源：http://dali.yanxiufei.cn/Article/details/gtqnvvwttp.html

PHP:  echo "Hello, World!";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkgsabpg.html

JS:   console.log("Hello, World!");
来源：http://dali.fzhhl.top/Article/details/gtytbdyvcx.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.aibaodan.cn/Article/details/gtkzkqlngj.html

Java: System.out.println("Hello, World!");
来源：http://dali.snrcjt.cn/Article/details/gtgiusdcaf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnoymbwpc.html

Ruby: puts "Hello, World!"
来源：http://dali.andypj.xyz/Article/details/gtdsbyvqej.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jinqigufen.top/Article/details/gtpvfmbvnp.html

[A02] 变量声明与赋值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvunhocoi.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yueranfly.top/Article/details/gtobgvvhgp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.svipenyu.cn/Article/details/gtwmuajzjx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hammf.cn/Article/details/gthnnkdobb.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yj20258.top/Article/details/gtmatopouk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.cucudq.cn/Article/details/gtqssflelc.html

Go:   name := "Alex"; age := 20
来源：http://dali.jyoumei.cn/Article/details/gtgskqtriq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hywenlv.cn/Article/details/gtgdwdglia.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ydzc1.top/Article/details/gtxchxeuyq.html

[A03] 常量定义
来源：http://dali.daxiang520.top/Article/details/gtdfeaeihn.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.xinyue.icu/Article/details/gtqmeemmcg.html

PHP:  const PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtkfzpfdlm.html

JS:   const PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtpujbsjoz.html

TS:   const PI: number = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtylyffqsk.html

Java: static final double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtnpufpmrx.html

Go:   const PI = 3.14159
来源：http://dali.havefunace.top/Article/details/gtmijhrvzq.html

Ruby: PI = 3.14159
来源：http://dali.0kj1m.cn/Article/details/gtdwnhyuku.html

C#:   const double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtyozejcnl.html

[A04] 判断变量类型
来源：http://dali.c1oappe.top/Article/details/gtsbtmamud.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yvedp.cn/Article/details/gtyjlpexry.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cashguo.top/Article/details/gtsbsxhkoq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zycfv.cn/Article/details/gtkrcnxynj.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhongyouzk.top/Article/details/gtiuvwuytm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacdwppbw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.redwolf501.top/Article/details/gtryqxsxfv.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.hnxiangtu.top/Article/details/gtncldqyst.html

C#:   x.GetType().Name; x is int
来源：http://dali.feifeiyinyue.top/Article/details/gtgrfowdtu.html

[A05] 整数除法与取模
来源：http://dali.pycfn.com/Article/details/gtwcjzxscg.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xuetiantiany.cn/Article/details/gtmbyezdsz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.smart0.xyz/Article/details/gtgutrbcbm.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gteszjqfou.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gtccxuznla.html

Java: 7 / 2; 7 % 2
来源：http://dali.ydzc1.top/Article/details/gtudecszmj.html

Go:   7 / 2; 7 % 2
来源：http://dali.guannengcc.top/Article/details/gtwopnkhje.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gtghybipam.html

C#:   7 / 2; 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtkjwkasgj.html

[A06] 字符串转数字
来源：http://dali.nanxuanxn.top/Article/details/gtqhubipif.html

Py:   int("42"); float("3.14")
来源：http://dali.kuanghao11.cn/Article/details/gtazrcecyn.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.0kj1m.cn/Article/details/gtjtalacgp.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jinqigufen.top/Article/details/gtixxpvmrq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.c1oappe.top/Article/details/gtufbwakfy.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfayrtsmc.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yuxming.cn/Article/details/gtdnehhann.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.guowangkeji.top/Article/details/gtgxddqmqp.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmcmrfmp.html

[A07] 数字转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyufhmcko.html

Py:   str(42)
来源：http://dali.c1oappe.top/Article/details/gtujldqevd.html

PHP:  (string) 42; strval(42)
来源：http://dali.daria6918.cn/Article/details/gtdwsriccd.html

JS:   String(42); (42).toString()
来源：http://dali.yanxiufei.cn/Article/details/gtpsiantxg.html

TS:   String(42)
来源：http://dali.daria6918.cn/Article/details/gtxfsrqieq.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.vqdsnc.cn/Article/details/gtcdnuvxhg.html

Go:   strconv.Itoa(42)
来源：http://dali.sufxvd.cn/Article/details/gtsswsbmzk.html

Ruby: 42.to_s
来源：http://dali.jlsjyb.cn/Article/details/gtbxbvbnjf.html

C#:   42.ToString()
来源：http://dali.sysykeji.top/Article/details/gtryxmmxda.html

[A08] 取整与四舍五入
来源：http://dali.cucudq.cn/Article/details/gtuqgmtfzp.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.aizwys.cn/Article/details/gtrtcaeugg.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hfpthk.cn/Article/details/gtkkmefygb.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.andypj.xyz/Article/details/gtftiwagse.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shzxlz.cn/Article/details/gtfxdyfvyb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.xylfe.cn/Article/details/gtcbkxgwtv.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.chenzaomai.com/Article/details/gtepvcukbr.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.mhx1999.top/Article/details/gtlejkdssq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.nanxinkj.top/Article/details/gtilnhbdin.html

[A09] 绝对值与最大最小值
来源：http://dali.chenlongwang.top/Article/details/gtebraglck.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gttabsergv.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xylfe.cn/Article/details/gtnrprjfcd.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtaiaigkwe.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtjaqmjygk.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hfpthk.cn/Article/details/gttnkikyhz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.havefunace.top/Article/details/gtphfagfwd.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.aizwys.cn/Article/details/gtxayjanti.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtlnxaiagx.html

[A10] 生成随机数
来源：http://dali.sysykeji.top/Article/details/gtlahqkpzj.html

Py:   import random; random.randint(1, 100)
来源：http://dali.316326.xyz/Article/details/gtvdnnixyq.html

PHP:  random_int(1, 100);
来源：http://dali.ehwqpu.com/Article/details/gtlonetpij.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yj20258.top/Article/details/gtqiqatfdz.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.tian-w.cn/Article/details/gtqcztojjz.html

Java: new Random().nextInt(100) + 1
来源：http://dali.iojbl.cn/Article/details/gtexeetvnn.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hywenlv.cn/Article/details/gtpwlpzyhk.html

Ruby: rand(1..100)
来源：http://dali.dashuyun.cn/Article/details/gtsivajust.html

C#:   new Random().Next(1, 101)
来源：http://dali.yuanzhike.top/Article/details/gtwxddjsqf.html

[A11] 条件表达式（三元）
来源：http://dali.jinqigfzy.top/Article/details/gtffsvoklv.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.hongshengwenyu.top/Article/details/gtraojlpod.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.jyoumei.cn/Article/details/gtzgdwypxz.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.cheryme.top/Article/details/gtwokvmbuq.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.wangshuangyany.cn/Article/details/gtnsqrmykl.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.hongshengwenyu.top/Article/details/gtfrahlezz.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jyoumei.cn/Article/details/gtmcgsuxkb.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zycfv.cn/Article/details/gtgbvztxis.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.nwbrower.top/Article/details/gtxzcpwxqs.html

[A12] 字符串插值 / 格式化
来源：http://dali.havefunace.top/Article/details/gtrkueczit.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jqgfzy.top/Article/details/gtbutdaabs.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.shuidangran.top/Article/details/gtruvyxdnd.html

JS:   `Hello, ${name}!`
来源：http://dali.gogol.net.cn/Article/details/gtkcejqfim.html

TS:   `Hello, ${name}!`
来源：http://dali.jqgufenzy.top/Article/details/gtuwbilugj.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.vqdsnc.cn/Article/details/gtyeqxumyl.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jiagoushi.top/Article/details/gthmvezaiu.html

Ruby: "Hello, #{name}!"
来源：http://dali.zdqjudy.top/Article/details/gtwonvtdzn.html

C#:   $"Hello, {name}!"
来源：http://dali.zhongyouzk.top/Article/details/gtllsfcajv.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.hfpthk.cn/Article/details/gtawewztut.html

Py:   "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gtraeixset.html

PHP:  "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gtstiyvtun.html

JS:   "第一行\n第二行"
来源：http://dali.jinghuilouyu.cn/Article/details/gtjebmnujg.html

TS:   "第一行\n第二行"
来源：http://dali.zhiwuduotai.top/Article/details/gtehasduhb.html

Java: "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gtthfnvphv.html

Go:   "第一行\n第二行"
来源：http://dali.dashuyun.cn/Article/details/gtgkordspa.html

Ruby: "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gtzrrxufck.html

C#:   "第一行\n第二行"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpsawdpyq.html


<!-- 参考信息 -->