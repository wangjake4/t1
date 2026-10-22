代发 wailian999

[U83] JS：ES Module 导入导出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2onturmgn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yj20258.top/Article/details/gt2dbqosgri.html

[U84] JS：CommonJS 写法
来源：http://dali.nanxuanxn.top/Article/details/gt2oohqkjla.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hammf.cn/Article/details/gt2opvkezwj.html

[U85] JS：可选链
来源：http://dali.wangshuangyany.cn/Article/details/gt2vbymbojq.html

a?.b?.c
来源：http://dali.chenlongwang.top/Article/details/gt2ynemwyfw.html

[U86] JS：空值合并
来源：http://dali.tian-w.cn/Article/details/gt2yqukgtcv.html

a ?? b
来源：http://dali.sxryk.cn/Article/details/gt2tmwzorfk.html

[U87] JS：解构默认值
来源：http://dali.zhoulong.xyz/Article/details/gt2czmigtzd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.iojbl.cn/Article/details/gt2chgigbbi.html

[U88] JS：对象展开合并
来源：http://dali.pengpengdd.cyou/Article/details/gt2fdrvpsyn.html

{ ...a, ...b }
来源：http://dali.bjfxy.top/Article/details/gt2dbnfljix.html

[U89] JS：数组去重
来源：http://dali.chenjidiqi.icu/Article/details/gt2toeejuwv.html

[...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gt2bdwwvaxn.html

[U90] JS：数字数组排序
来源：http://dali.daxiang520.top/Article/details/gt2dhgvwvcl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gt2aiihhrtz.html

[U91] JS：对象键值遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2zmsrjafp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jyoumei.cn/Article/details/gt2dfqipxmg.html

[U92] JS：深拷贝
来源：http://dali.ydzc1.top/Article/details/gt2najmmjpu.html

structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2zlnxruek.html

[U93] JS：模板字符串
来源：http://dali.yj20258.top/Article/details/gt2nzxxjmlp.html

`共 ${n} 条`
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kfourkjh.html

[U94] JS：箭头函数
来源：http://dali.xinyue.icu/Article/details/gt2kdheispy.html

const double = x => x * 2;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ozntusko.html

[U95] JS：Promise 包装
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kpjnhvgl.html

new Promise((resolve, reject) => {})
来源：http://dali.xinyue.icu/Article/details/gt2mdmrrywp.html

[U96] JS：async/await 与异常
来源：http://dali.havefunace.top/Article/details/gt2tcfzduaz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gt2ctlgtijv.html

[U97] JS：并发请求
来源：http://dali.tianlin.xyz/Article/details/gt2pifausoo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ucjlslub.html

[U98] JS：fetch 带 JSON
来源：http://dali.ydzc1.top/Article/details/gt2wivinyuu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rhwmssuw.html

[U99] JS：事件监听
来源：http://dali.aibaodan.cn/Article/details/gt2ipwhczhd.html

el.addEventListener("click", e => {})
来源：http://dali.fengsongda.top/Article/details/gt2unppcggr.html

[U100] JS：DOM 查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wbojfpxn.html

document.querySelector(".item")
来源：http://dali.haohaochexian.top/Article/details/gt2faplsdxh.html

[U101] JS：classList 操作
来源：http://dali.316326.xyz/Article/details/gt2hlzpdlcw.html

el.classList.toggle("active")
来源：http://dali.zycfv.cn/Article/details/gt2vowpmwrz.html

[U102] JS：本地存储
来源：http://dali.zhongyouzk.top/Article/details/gt2houwenro.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yj20258888.top/Article/details/gt2lboadjrz.html

[U103] JS：定时器
来源：http://dali.jianghu66.top/Article/details/gt2ttqrwjsq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.wangshuangyany.cn/Article/details/gt2wkdlvtyf.html

[U104] JS：防抖
来源：http://dali.haohaochexian.top/Article/details/gt2cgsyyhdl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gt2ymvlzjmp.html

[U105] JS：节流
来源：http://dali.ydzc1.top/Article/details/gt2pcxmpbch.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.c1oappe.top/Article/details/gt2llyjvtji.html

[U106] JS：日期格式化
来源：http://dali.birdmap.top/Article/details/gt2nhigfnbi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ivvv.top/Article/details/gt2pkelehvy.html

[U107] JS：数字千分位
来源：http://dali.nanxuanxn.top/Article/details/gt2dtlpvics.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yj20258888.top/Article/details/gt2inutgqfs.html

[U108] JS：随机整数
来源：http://dali.tanke756.top/Article/details/gt2jffuhzcr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.sufxvd.cn/Article/details/gt2tkmyixzf.html

[U109] JS：数组分组
来源：http://dali.dashuyun.cn/Article/details/gt2wfjdoedk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.havefunace.top/Article/details/gt2hvozlmuk.html

[U110] JS：数组分块
来源：http://dali.birdmap.top/Article/details/gt2stbnhyqm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xrwhehxl.html

[U111] JS：对象转 Map
来源：http://dali.jinqigufen.top/Article/details/gt2flwvhifd.html

new Map(Object.entries(obj))
来源：http://dali.sysykeji.top/Article/details/gt2omxiudrv.html

[U112] JS：字符串补位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dyynkzjd.html

"7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gt2oeozabgb.html

[U113] JS：正则替换全部
来源：http://dali.hfpthk.cn/Article/details/gt2cqwuvuvh.html

s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2upnbuods.html

[U114] JS：JSON 深比较
来源：http://dali.ybcxt.top/Article/details/gt2wquzkoip.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.iojbl.cn/Article/details/gt2cbdrtrpb.html

[U115] JS：生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gt2ofjlahaj.html

crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gt2lzxfwcic.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xuanzx.com/Article/details/gt2yenmsciy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2hkpiajnx.html

[U117] JS：单元测试
来源：http://dali.fengsongda.top/Article/details/gt2bxhzcahj.html

npm i -D vitest;  npx vitest
来源：http://dali.aibaodan.cn/Article/details/gt2kwofabsa.html

[U118] JS：开发服务器
来源：http://dali.c1oappe.top/Article/details/gt2jbpndvgj.html

npm i -D vite;  npx vite
来源：http://dali.chenjidiqi.icu/Article/details/gt2peojpyvs.html

[U119] JS：生产构建
来源：http://dali.yueranfly.top/Article/details/gt2hopkbbvc.html

npx vite build
来源：http://dali.guowangkeji.top/Article/details/gt2vkshyrum.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ehwqpu.com/Article/details/gt2ltyzcjvw.html

import.meta.env.VITE_API_URL
来源：http://dali.hnqzz.top/Article/details/gt2ccfalxwg.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2newplzri.html

统计汇总
来源：http://dali.cheryme.top/Article/details/gt2haeyxnic.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2nprakego.html

按语言统计（条）：
来源：http://dali.xziqi.cn/Article/details/gt2rtzzsgbw.html

Python ......... 252
来源：http://dali.aizwys.cn/Article/details/gt2exbsanjs.html

PHP ............ 252
来源：http://dali.hammf.cn/Article/details/gt2ncqyfrme.html

JavaScript ..... 252
来源：http://dali.ybcxt.top/Article/details/gt2uidbdtpo.html

TypeScript ..... 212
来源：http://dali.xinyue.icu/Article/details/gt2uelrmvro.html

Java ........... 212
来源：http://dali.cdnleiting.top/Article/details/gt2wrraamyf.html

Go ............. 212
来源：http://dali.xziqi.cn/Article/details/gt2yppwuyai.html

Ruby ........... 212
来源：http://dali.redwolf501.top/Article/details/gt2nijhxzno.html

C# ............. 212
来源：http://dali.hnqzz.top/Article/details/gt2eyotvdcr.html

C .............. 30
来源：http://dali.zhongyouzk.top/Article/details/gt2xebwdebg.html

C++ ............ 30
来源：http://dali.jinqigfzy.top/Article/details/gt2ggkjymgv.html

SQL ............ 90
来源：http://dali.yj20258888.top/Article/details/gt2umfyjdbk.html

Bash ........... 80
来源：http://dali.zhoulong.xyz/Article/details/gt2bgtoxost.html

Kotlin ......... 15
来源：http://dali.pengpengdd.cyou/Article/details/gt2ljsvbuxo.html

Swift .......... 15
来源：http://dali.svipenyu.cn/Article/details/gt2kngzoqce.html

Lua ............ 10
来源：http://dali.shzxlz.cn/Article/details/gt2zvyrxdde.html

Perl ........... 10
来源：http://dali.quarkkingdee.top/Article/details/gt2xyjpjnok.html

Scala .......... 10
来源：http://dali.jqgufenzy.top/Article/details/gt2etavzgsp.html

------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gt2vitphwqb.html

合计 ........... 2106 条
来源：http://dali.yangfankeji.com/Article/details/gt2uqgwhlwl.html

按章节统计：
来源：http://dali.pengpengdd.cyou/Article/details/gt2ooikxlmi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.feifeiyinyue.top/Article/details/gt2zekxscvu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rxditeqy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.gotoacloud.top/Article/details/gt2fzhxmqis.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.daria6918.cn/Article/details/gt2bbhnioay.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shangyingyoupin.top/Article/details/gt2frmqtdgo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.chenjidiqi.icu/Article/details/gt2jlipcrly.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.fzhhl.top/Article/details/gt2rlpayyrp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xziqi.cn/Article/details/gt2tzvjweot.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gt2fhihrtdy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shzxlz.cn/Article/details/gt2ewzqywvy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eijyagwi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xuanzx.com/Article/details/gt2kahdggyt.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gt2oogjotms.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.guowangkeji.top/Article/details/gt2zptpatyh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cheryme.top/Article/details/gt2qdfcfacm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gt2imcfwmlb.html

Q SQL 专题                              90
来源：http://dali.zdqjudy.top/Article/details/gt2nfcfgmou.html

R Bash 专题                             80
来源：http://dali.mhx1999.top/Article/details/gt2ivhpkvyh.html

S C / C++ 专题                          60
来源：http://dali.aizwys.cn/Article/details/gt2foymjzks.html

T 其他语言补充                          60
来源：http://dali.vqdsnc.cn/Article/details/gt2sjehldnd.html

U 高频实用片段                         120
来源：http://dali.daxiang520.top/Article/details/gt2ieohfwob.html

------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gt2atqjysrs.html

合计                                  2106 条
来源：http://dali.ybcxt.top/Article/details/gt2nqmdywhg.html

--------------------------------------------------------------------------------
来源：http://dali.yj202588.top/Article/details/gt2uuzapgqp.html

使用提醒
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2etfauvqp.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xyhainbd.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.nanxinkj.top/Article/details/gt2kndionfi.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.redwolf501.top/Article/details/gt2wnpcftis.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.dashuyun.cn/Article/details/gt2rejgytqr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.sweek.top/Article/details/gt2scgmnlra.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.tianlin.xyz/Article/details/gt2ktrajhtd.html

—— 文件结束 ——
来源：http://dali.hammf.cn/Article/details/gt2dxfnsbcp.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2wwjmnrkf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yongpay.top/Article/details/gt2ozuevgyl.html

Common Programming Examples Cheat Book
来源：http://dali.jianghu66.top/Article/details/gt2tezbonsl.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2qmzinkdb.html

【收录内容】
来源：http://dali.xuetiantiany.cn/Article/details/gt2stiecwmg.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.9152youxi.cn/Article/details/gt2esamyohl.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bticbltr.html

SQL · Bash · C · C++
来源：http://dali.zhixingplan.top/Article/details/gt2dhfvlcnp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yonumen.top/Article/details/gt2tclefqqn.html

【使用说明】
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zxylgudp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.haohaochexian.top/Article/details/gt2hmmnwdac.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yj20258888.top/Article/details/gt2qhiesynt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.gaohongyu789.top/Article/details/gt2ggiyxtwf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.sufxvd.cn/Article/details/gt2mjtpsggo.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hongshengwenyu.top/Article/details/gt2ilhpfshj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yj20258.top/Article/details/gt2ubauroav.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhixingplan.top/Article/details/gt2mrooggrj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.ydzc1.top/Article/details/gt2trtryzpz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jyoumei.cn/Article/details/gt2tsnylscn.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cqqwz.cn/Article/details/gt2eyxmbgjk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.nanxinkj.top/Article/details/gt2ekexbidy.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tcjgjjjh.html

【文件统计】
来源：http://dali.zdqjudy.top/Article/details/gt2auqcitzo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hongshengwenyu.top/Article/details/gt2qavprgsy.html

--------------------------------------------------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gt2slyntsob.html

目  录
来源：http://dali.wangshuangyany.cn/Article/details/gt2rgnlghac.html

--------------------------------------------------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gt2felklyeb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ivvv.top/Article/details/gt2cwsiihrb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ehwqpu.com/Article/details/gt2pnnqhept.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.tanke756.top/Article/details/gt2kqghwodg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jqgfzy.top/Article/details/gt2mbqjhgxo.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shzxlz.cn/Article/details/gt2siwdwysi.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxzuyub.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hammf.cn/Article/details/gt2scaaiofa.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.c1oappe.top/Article/details/gt2flwxnhqd.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gt2kdlhzwca.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.tian-w.cn/Article/details/gt2fpzhdjzh.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gt2pedxoudd.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.sxryk.cn/Article/details/gt2sbunmzoo.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.fengsongda.top/Article/details/gt2pjlqafhq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.c1oappe.top/Article/details/gt2obxpipkm.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.tianlin.xyz/Article/details/gt2axlfkohm.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gt2cdnzmqsh.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zszqfjqh.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.dashuyun.cn/Article/details/gt2qupmditi.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2jicruelc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenzaomai.com/Article/details/gt2fgdbvhdb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.haohaochexian.top/Article/details/gt2imigvswe.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2wgmhfisg.html

A. 基础语法与类型
来源：http://dali.sxryk.cn/Article/details/gt2dnxedqyj.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cwjosdue.html

[A01] Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2mtblmbzm.html

Py:   print("Hello, World!")
来源：http://dali.zhoulong.xyz/Article/details/gt2sydyquzn.html

PHP:  echo "Hello, World!";
来源：http://dali.xuetiantiany.cn/Article/details/gt2xxpmsbdk.html

JS:   console.log("Hello, World!");
来源：http://dali.zhengqikj.top/Article/details/gt2eihltusc.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.tianlin.xyz/Article/details/gt2lhoconwk.html

Java: System.out.println("Hello, World!");
来源：http://dali.tianlin.xyz/Article/details/gt2osqusjej.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qlhrkmvb.html

Ruby: puts "Hello, World!"
来源：http://dali.jqgufenzy.top/Article/details/gt2fjufbkfd.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ydzc1.top/Article/details/gt2ptildihz.html

[A02] 变量声明与赋值
来源：http://dali.chenjidiqi.icu/Article/details/gt2fofvkkti.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.gotoacloud.top/Article/details/gt2gzzsxzmi.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.c1oappe.top/Article/details/gt2qfqmmwsz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.nanxuanxn.top/Article/details/gt2grgdtugp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.shzxlz.cn/Article/details/gt2drqkhsdr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.nanxuanxn.top/Article/details/gt2tcvyhpsy.html

Go:   name := "Alex"; age := 20
来源：http://dali.aizwys.cn/Article/details/gt2lhmzufnh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xinyue.icu/Article/details/gt2hcjghhqn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ehwqpu.com/Article/details/gt2iroafzdy.html

[A03] 常量定义
来源：http://dali.cashguo.top/Article/details/gt2tnbyuopu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hnxiangtu.top/Article/details/gt2jwcduxmz.html

PHP:  const PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gt2tlijogqm.html

JS:   const PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gt2szydhdql.html

TS:   const PI: number = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gt2wwihfwrj.html

Java: static final double PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gt2neltxpxs.html

Go:   const PI = 3.14159
来源：http://dali.aizwys.cn/Article/details/gt2gwyeaapq.html

Ruby: PI = 3.14159
来源：http://dali.yuanzhike.top/Article/details/gt2bsidrmee.html

C#:   const double PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gt2qzhmsapd.html

[A04] 判断变量类型
来源：http://dali.andypj.xyz/Article/details/gt2qdlxyxog.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.0kj1m.cn/Article/details/gt2nzwquhcc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.fengsongda.top/Article/details/gt2ryatkksc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhengqikj.top/Article/details/gt2njzjnanp.html

TS:   typeof x; x instanceof Date
来源：http://dali.316326.xyz/Article/details/gt2gvgdeivo.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.tian-w.cn/Article/details/gt2rqrcfczx.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hammf.cn/Article/details/gt2cvrhbrrf.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jinqigfzy.top/Article/details/gt2emehfceu.html

C#:   x.GetType().Name; x is int
来源：http://dali.zdqjudy.top/Article/details/gt2gvlhhadm.html

[A05] 整数除法与取模
来源：http://dali.aibaodan.cn/Article/details/gt2ksqidfsq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zycfv.cn/Article/details/gt2zredelzi.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gt2wgevptjr.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cucudq.cn/Article/details/gt2zuoadknl.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gt2uvvggoif.html

Java: 7 / 2; 7 % 2
来源：http://dali.bjfxy.top/Article/details/gt2ttspdejm.html

Go:   7 / 2; 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gt2utcyxije.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ydzc1.top/Article/details/gt2nxpqmpjv.html

C#:   7 / 2; 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gt2yypvenhg.html

[A06] 字符串转数字
来源：http://dali.bjfxy.top/Article/details/gt2erkaymta.html

Py:   int("42"); float("3.14")
来源：http://dali.jqgfzy.top/Article/details/gt2xfganvbu.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jinqigfzy.top/Article/details/gt2tvcyrddi.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.pengpengdd.cyou/Article/details/gt2tqzdpsci.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.wangdashe.top/Article/details/gt2eklayvtz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cheryme.top/Article/details/gt2icsuvzrg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhoulong.xyz/Article/details/gt2mgiahqea.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.sysykeji.top/Article/details/gt2gmvspsno.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.tian-w.cn/Article/details/gt2bobiwwvy.html

[A07] 数字转字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2wjbxffzm.html

Py:   str(42)
来源：http://dali.jinqigfzy.top/Article/details/gt2gabiivjl.html

PHP:  (string) 42; strval(42)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mhcbboke.html

JS:   String(42); (42).toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2xtuxxcah.html

TS:   String(42)
来源：http://dali.xinyue.icu/Article/details/gt2jubggeaz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yj20258888.top/Article/details/gt2hllxmshd.html

Go:   strconv.Itoa(42)
来源：http://dali.c1oappe.top/Article/details/gt2fucxriun.html

Ruby: 42.to_s
来源：http://dali.jqgufenzy.top/Article/details/gt2mugmffvn.html

C#:   42.ToString()
来源：http://dali.chenzaomai.com/Article/details/gt2buzehrbl.html

[A08] 取整与四舍五入
来源：http://dali.jyoumei.cn/Article/details/gt2xtigmuiy.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.nwbrower.top/Article/details/gt2cwodjbrj.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.gzhubu.top/Article/details/gt2xulrucrv.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yueranfly.top/Article/details/gt2oqkcdfwq.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.vqdsnc.cn/Article/details/gt2xpiujhjo.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.aizwys.cn/Article/details/gt2toaewfah.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.xziqi.cn/Article/details/gt2ayoutzbm.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.cashguo.top/Article/details/gt2fbcredhn.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.chenzaomai.com/Article/details/gt2eiyfghvm.html

[A09] 绝对值与最大最小值
来源：http://dali.9152youxi.cn/Article/details/gt2cprjdvoi.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gt2gdhdpdnw.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.c1oappe.top/Article/details/gt2ntitdqjx.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gt2tomxwzea.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gt2tpnvvckr.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gt2dgzodikg.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.guowangkeji.top/Article/details/gt2oimutfom.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.smart0.xyz/Article/details/gt2mbpxzsae.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.cheryme.top/Article/details/gt2xuznggzo.html

[A10] 生成随机数
来源：http://dali.zhongyouzk.top/Article/details/gt2iejskwku.html

Py:   import random; random.randint(1, 100)
来源：http://dali.fzhhl.top/Article/details/gt2uymkinys.html

PHP:  random_int(1, 100);
来源：http://dali.quarkkingdee.top/Article/details/gt2ivvcnxna.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhixingplan.top/Article/details/gt2zxogmhwe.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shzxlz.cn/Article/details/gt2pvgocatr.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhixingplan.top/Article/details/gt2dexwngzu.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.xziqi.cn/Article/details/gt2aouuyfip.html

Ruby: rand(1..100)
来源：http://dali.tian-w.cn/Article/details/gt2oqkvhfry.html

C#:   new Random().Next(1, 101)
来源：http://dali.chenlongwang.top/Article/details/gt2omxwiwxo.html

[A11] 条件表达式（三元）
来源：http://dali.jianghu66.top/Article/details/gt2mgigicwn.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhoulong.xyz/Article/details/gt2twofebjr.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.jianghu66.top/Article/details/gt2hespjojx.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.bjfxy.top/Article/details/gt2fnkmfxuz.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.cdnleiting.top/Article/details/gt2krtzrotf.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zdqjudy.top/Article/details/gt2orstcvii.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.havefunace.top/Article/details/gt2ivdamonz.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jinqigfzy.top/Article/details/gt2aqyzfpux.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.cdnleiting.top/Article/details/gt2mcpsnfyi.html

[A12] 字符串插值 / 格式化
来源：http://dali.meibo888.top/Article/details/gt2scklehqk.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yuanzhike.top/Article/details/gt2jcyopnnp.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jdtsgxzr.html

JS:   `Hello, ${name}!`
来源：http://dali.birdmap.top/Article/details/gt2coroaqhs.html

TS:   `Hello, ${name}!`
来源：http://dali.hongshengwenyu.top/Article/details/gt2yrgmtmhi.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.c1oappe.top/Article/details/gt2kktmoayb.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bqexozos.html

Ruby: "Hello, #{name}!"
来源：http://dali.daria6918.cn/Article/details/gt2skqhambn.html

C#:   $"Hello, {name}!"
来源：http://dali.ppjwa.cn/Article/details/gt2losvgjhf.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.snrcjt.cn/Article/details/gt2uollzuyr.html

Py:   "第一行\n第二行"
来源：http://dali.zhixingplan.top/Article/details/gt2tbyfdctd.html

PHP:  "第一行\n第二行"
来源：http://dali.tianlin.xyz/Article/details/gt2qdlachek.html

JS:   "第一行\n第二行"
来源：http://dali.gaohongyu789.top/Article/details/gt2exlawexr.html

TS:   "第一行\n第二行"
来源：http://dali.yangfankeji.com/Article/details/gt2sxzbufpe.html

Java: "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gt2mcxuflzr.html

Go:   "第一行\n第二行"
来源：http://dali.xinyue.icu/Article/details/gt2grtufdsv.html

Ruby: "第一行\n第二行"
来源：http://dali.c1oappe.top/Article/details/gt2aosnpxzd.html

C#:   "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gt2hiaujsjn.html


<!-- 参考信息 -->