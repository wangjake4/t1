代发 wailian999

[U81] JS：初始化项目
来源：http://dali.yvedp.cn/Article/details/gthudeypmw.html

npm init -y;  npm i express
来源：http://dali.havefunace.top/Article/details/gtmvpwojho.html

[U82] JS：package.json 脚本
来源：http://dali.hfpthk.cn/Article/details/gtprcxoaqm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.fzhhl.top/Article/details/gthijiigzp.html

[U83] JS：ES Module 导入导出
来源：http://dali.jianghu66.top/Article/details/gtuipgdmjn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ydzc1.top/Article/details/gtthhkfahd.html

[U84] JS：CommonJS 写法
来源：http://dali.jqgufenzy.top/Article/details/gtbptcawee.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shanyushiyangtech.top/Article/details/gttkbxdufc.html

[U85] JS：可选链
来源：http://dali.dashuyun.cn/Article/details/gtgqjqnvuo.html

a?.b?.c
来源：http://dali.sufxvd.cn/Article/details/gtlzunupxb.html

[U86] JS：空值合并
来源：http://dali.zhiwuduotai.top/Article/details/gtsdowuhyy.html

a ?? b
来源：http://dali.snrcjt.cn/Article/details/gtbdobegaf.html

[U87] JS：解构默认值
来源：http://dali.haohaochexian.top/Article/details/gtytaymbnk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yonumen.top/Article/details/gtyvperwic.html

[U88] JS：对象展开合并
来源：http://dali.xziqi.cn/Article/details/gtywtnxnpu.html

{ ...a, ...b }
来源：http://dali.zhixingplan.top/Article/details/gtugcrqrab.html

[U89] JS：数组去重
来源：http://dali.ehwqpu.com/Article/details/gtzrphwoqe.html

[...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gtwtholaar.html

[U90] JS：数字数组排序
来源：http://dali.xuetiantiany.cn/Article/details/gtxlwlstsh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gtsmcyxqly.html

[U91] JS：对象键值遍历
来源：http://dali.hnqzz.top/Article/details/gtlurlqmhl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yuxming.cn/Article/details/gtwzgapheg.html

[U92] JS：深拷贝
来源：http://dali.svipenyu.cn/Article/details/gtyqpyisbz.html

structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gttykcjwvg.html

[U93] JS：模板字符串
来源：http://dali.redwolf501.top/Article/details/gtezelzozv.html

`共 ${n} 条`
来源：http://dali.andypj.xyz/Article/details/gtudwxtyux.html

[U94] JS：箭头函数
来源：http://dali.xuetiantiany.cn/Article/details/gtpmispsos.html

const double = x => x * 2;
来源：http://dali.tian-w.cn/Article/details/gtjjxohyxf.html

[U95] JS：Promise 包装
来源：http://dali.yonumen.top/Article/details/gtbakpbyrx.html

new Promise((resolve, reject) => {})
来源：http://dali.zhixingplan.top/Article/details/gtpgxyovvt.html

[U96] JS：async/await 与异常
来源：http://dali.xuetiantiany.cn/Article/details/gtdblrurva.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gtsbknyzca.html

[U97] JS：并发请求
来源：http://dali.sweek.top/Article/details/gtpzkmymnr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gtagqvddxv.html

[U98] JS：fetch 带 JSON
来源：http://dali.yueranfly.top/Article/details/gtyrxolmbf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.wangdashe.top/Article/details/gtehafkknn.html

[U99] JS：事件监听
来源：http://dali.jlsjyb.cn/Article/details/gttjtpykhx.html

el.addEventListener("click", e => {})
来源：http://dali.jinqigufen.top/Article/details/gtcaidickb.html

[U100] JS：DOM 查询
来源：http://dali.gotoacloud.top/Article/details/gtfdfwwlhi.html

document.querySelector(".item")
来源：http://dali.yj20258.top/Article/details/gtomtbbgjt.html

[U101] JS：classList 操作
来源：http://dali.shzxlz.cn/Article/details/gtkabvcjrv.html

el.classList.toggle("active")
来源：http://dali.chenjidiqi.icu/Article/details/gtemvmhzwt.html

[U102] JS：本地存储
来源：http://dali.cheryme.top/Article/details/gtmbhqlski.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yongpay.top/Article/details/gttvtkjuyg.html

[U103] JS：定时器
来源：http://dali.ehwqpu.com/Article/details/gtunokyqyl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.pengpengdd.cyou/Article/details/gttmhirxqb.html

[U104] JS：防抖
来源：http://dali.ppjwa.cn/Article/details/gtqeurfzlz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gtrqdxikpq.html

[U105] JS：节流
来源：http://dali.andypj.xyz/Article/details/gtrevyestr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.c1oappe.top/Article/details/gtldlelzja.html

[U106] JS：日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gtkircyqun.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.aizwys.cn/Article/details/gtbyaojpyb.html

[U107] JS：数字千分位
来源：http://dali.zhiwuduotai.top/Article/details/gtdovsfead.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xylfe.cn/Article/details/gtgakdzynf.html

[U108] JS：随机整数
来源：http://dali.hysaishi.cn/Article/details/gtbgycudxu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.chenzaomai.com/Article/details/gtnrqngoph.html

[U109] JS：数组分组
来源：http://dali.jlsjyb.cn/Article/details/gtvtsujuuj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.mhx1999.top/Article/details/gtfolaefve.html

[U110] JS：数组分块
来源：http://dali.quarkkingdee.top/Article/details/gtvjfbkvms.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shangyingyoupin.top/Article/details/gttshgahwy.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gtycxkbzdv.html

new Map(Object.entries(obj))
来源：http://dali.cdnleiting.top/Article/details/gtfjrvejtg.html

[U112] JS：字符串补位
来源：http://dali.316326.xyz/Article/details/gtivrgpibx.html

"7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtzxlrjlri.html

[U113] JS：正则替换全部
来源：http://dali.guannengcc.top/Article/details/gtmetxhuxv.html

s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtyeyicapd.html

[U114] JS：JSON 深比较
来源：http://dali.bjfxy.top/Article/details/gtywqknrid.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jiagoushi.top/Article/details/gtghjkyzpn.html

[U115] JS：生成 UUID
来源：http://dali.xylfe.cn/Article/details/gtghegjobh.html

crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gttomtspug.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ivvv.top/Article/details/gtsysdnxxc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.c1oappe.top/Article/details/gtyggmixei.html

[U117] JS：单元测试
来源：http://dali.havefunace.top/Article/details/gtkzdxdksn.html

npm i -D vitest;  npx vitest
来源：http://dali.hysaishi.cn/Article/details/gtdrtifxme.html

[U118] JS：开发服务器
来源：http://dali.9152youxi.cn/Article/details/gtlyukloma.html

npm i -D vite;  npx vite
来源：http://dali.zhiwuduotai.top/Article/details/gtkvwnozdr.html

[U119] JS：生产构建
来源：http://dali.zhixingplan.top/Article/details/gtnanhhiou.html

npx vite build
来源：http://dali.dianchejie.cn/Article/details/gtuvmhlmtj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yj20258.top/Article/details/gtbslmtmpt.html

import.meta.env.VITE_API_URL
来源：http://dali.zhengqikj.top/Article/details/gtrgzdhbay.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtledkrvrx.html

统计汇总
来源：http://dali.jianghu66.top/Article/details/gtxtpzuijc.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtrfrzfdwv.html

按语言统计（条）：
来源：http://dali.xuanzx.com/Article/details/gtkdfxxxqg.html

Python ......... 252
来源：http://dali.cdnleiting.top/Article/details/gtklzgxctr.html

PHP ............ 252
来源：http://dali.shzxlz.cn/Article/details/gtqicxxtsu.html

JavaScript ..... 252
来源：http://dali.ydzc1.top/Article/details/gtmningmba.html

TypeScript ..... 212
来源：http://dali.jyoumei.cn/Article/details/gtqmutywxv.html

Java ........... 212
来源：http://dali.chenzaomai.com/Article/details/gtoyuekxdv.html

Go ............. 212
来源：http://dali.ybcxt.top/Article/details/gtgiiccpbl.html

Ruby ........... 212
来源：http://dali.andypj.xyz/Article/details/gtthiqxyvu.html

C# ............. 212
来源：http://dali.bjfxy.top/Article/details/gtdhahdfeb.html

C .............. 30
来源：http://dali.shangyingyoupin.top/Article/details/gtezvqateg.html

C++ ............ 30
来源：http://dali.xziqi.cn/Article/details/gthevkzaiv.html

SQL ............ 90
来源：http://dali.pengpengdd.cyou/Article/details/gtnnseecld.html

Bash ........... 80
来源：http://dali.gaohongyu789.top/Article/details/gtglofcbfh.html

Kotlin ......... 15
来源：http://dali.dashuyun.cn/Article/details/gtwjrkuzrh.html

Swift .......... 15
来源：http://dali.cdnleiting.top/Article/details/gtqhbzhbbk.html

Lua ............ 10
来源：http://dali.cdnleiting.top/Article/details/gtrmnpbtci.html

Perl ........... 10
来源：http://dali.jqgufenzy.top/Article/details/gtxxzveaux.html

Scala .......... 10
来源：http://dali.nanxinkj.top/Article/details/gtkrbegnme.html

------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gtyzlctvmq.html

合计 ........... 2106 条
来源：http://dali.xuetiantiany.cn/Article/details/gtqznalqpb.html

按章节统计：
来源：http://dali.sxryk.cn/Article/details/gtjdyygciq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zycfv.cn/Article/details/gtumwqkhzr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gogol.net.cn/Article/details/gtiyfejkej.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yuanzhike.top/Article/details/gtebxejxcn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xylfe.cn/Article/details/gthsjeqpls.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.tian-w.cn/Article/details/gtfizryaqa.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.wangshuangyany.cn/Article/details/gtfoyurzan.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ivvv.top/Article/details/gthlrlwibx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yj20258.top/Article/details/gtxqxgheri.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sweek.top/Article/details/gtsoqlrtkr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.tanke756.top/Article/details/gtvifzmylr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gtzqrkbyvo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gtdtrcaerc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gtnswpgybv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.tian-w.cn/Article/details/gtfzddvzpk.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jinqigufen.top/Article/details/gtiobznfrg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gtcbcohkhw.html

Q SQL 专题                              90
来源：http://dali.shangyingyoupin.top/Article/details/gtbyzzxxvt.html

R Bash 专题                             80
来源：http://dali.316326.xyz/Article/details/gtnymyptjl.html

S C / C++ 专题                          60
来源：http://dali.smart0.xyz/Article/details/gtxtjjbkyl.html

T 其他语言补充                          60
来源：http://dali.xziqi.cn/Article/details/gtvpooidxr.html

U 高频实用片段                         120
来源：http://dali.jlsjyb.cn/Article/details/gtcgvpeoot.html

------------------------------------
来源：http://dali.cheryme.top/Article/details/gtxtawgtdo.html

合计                                  2106 条
来源：http://dali.svipenyu.cn/Article/details/gtiqkhhyjp.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gtnnwjkvjl.html

使用提醒
来源：http://dali.ppjwa.cn/Article/details/gtecwxltac.html

--------------------------------------------------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gthzpjjpyf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhiwuduotai.top/Article/details/gtizlbrjbz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.9152youxi.cn/Article/details/gtjsalsodt.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yangfankeji.com/Article/details/gtrwrsxghe.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.aizwys.cn/Article/details/gtazlxbhbw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jqgufenzy.top/Article/details/gtvgeapsvv.html

—— 文件结束 ——
来源：http://dali.iojbl.cn/Article/details/gtipzdtibu.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtjzyujprb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.andypj.xyz/Article/details/gtiexpbidu.html

Common Programming Examples Cheat Book
来源：http://dali.hfpthk.cn/Article/details/gtkxmsafec.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtfammperj.html

【收录内容】
来源：http://dali.yvedp.cn/Article/details/gtarrgdpvo.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hnqzz.top/Article/details/gtycmzggpl.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.ybcxt.top/Article/details/gtbkmhkicf.html

SQL · Bash · C · C++
来源：http://dali.yongpay.top/Article/details/gtjxupicnw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.fengsongda.top/Article/details/gtzdhqzxxk.html

【使用说明】
来源：http://dali.zhiwuduotai.top/Article/details/gtyublavxx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.quarkkingdee.top/Article/details/gtbegnpuwm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.cucudq.cn/Article/details/gtbauwazko.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jinqigfzy.top/Article/details/gtkhzjvdla.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.pengpengdd.cyou/Article/details/gtzuvwxded.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.feifeiyinyue.top/Article/details/gttcqhvvuv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.tian-w.cn/Article/details/gtgeviabtv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.chenlongwang.top/Article/details/gtmwpaxgoi.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.nanxinkj.top/Article/details/gtgibsdrgk.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yongpay.top/Article/details/gtyprsoesx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.havefunace.top/Article/details/gtkftoeejt.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.nanxinkj.top/Article/details/gtjkxpljae.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.0kj1m.cn/Article/details/gtbhyexrwm.html

【文件统计】
来源：http://dali.chenlongwang.top/Article/details/gtecdtdiyb.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xylfe.cn/Article/details/gtmddnjtbr.html

--------------------------------------------------------------------------------
来源：http://dali.ydzc1.top/Article/details/gtkzhzfasj.html

目  录
来源：http://dali.daxiang520.top/Article/details/gtxuveqzbe.html

--------------------------------------------------------------------------------
来源：http://dali.iojbl.cn/Article/details/gthwqcqifb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtddagzpsu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtiswmyiqy.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hammf.cn/Article/details/gtrvvvvadq.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xuetiantiany.cn/Article/details/gteaqnahzm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.sysykeji.top/Article/details/gtsgyrrkoi.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jyoumei.cn/Article/details/gtlbzdmcvr.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.guowangkeji.top/Article/details/gtoizkiybs.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtqcupmnoq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gtxuuugbsi.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yonumen.top/Article/details/gtmvylocqw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqmojzgr.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.chenlongwang.top/Article/details/gtzcxshoua.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvurhxmtq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.aibaodan.cn/Article/details/gtoffnatnk.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yanxiufei.cn/Article/details/gtnepuepdx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.guannengcc.top/Article/details/gtllioakfn.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhixingplan.top/Article/details/gtrhjbhlcw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.daxiang520.top/Article/details/gtkflenohy.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ivvv.top/Article/details/gtmmigkctf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenzaomai.com/Article/details/gtwlqqpxhq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ehwqpu.com/Article/details/gtnhkeqyxn.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtmmcjdbyy.html

A. 基础语法与类型
来源：http://dali.haohaochexian.top/Article/details/gtpughbufz.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtdetvsosp.html

[A01] Hello World
来源：http://dali.cucudq.cn/Article/details/gtyulcxzqa.html

Py:   print("Hello, World!")
来源：http://dali.hfpthk.cn/Article/details/gtuxyxiofg.html

PHP:  echo "Hello, World!";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtquwstbrq.html

JS:   console.log("Hello, World!");
来源：http://dali.zdqjudy.top/Article/details/gtvbgdvwka.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jiagoushi.top/Article/details/gtvosrfgpk.html

Java: System.out.println("Hello, World!");
来源：http://dali.cqqwz.cn/Article/details/gtwyhyaeui.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.9152youxi.cn/Article/details/gtyeuvqzwe.html

Ruby: puts "Hello, World!"
来源：http://dali.hysaishi.cn/Article/details/gtgtyljaeo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yj20258.top/Article/details/gtdyznkbft.html

[A02] 变量声明与赋值
来源：http://dali.wangshuangyany.cn/Article/details/gtwipulhfa.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shangyingyoupin.top/Article/details/gtmaeeqmix.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hnxiangtu.top/Article/details/gtmdnhavfy.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cheryme.top/Article/details/gtpsdesrwr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.fzhhl.top/Article/details/gtxysbsgla.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gtonkmcgzt.html

Go:   name := "Alex"; age := 20
来源：http://dali.meibo888.top/Article/details/gtxoguuyvt.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zdqjudy.top/Article/details/gtvydwlsme.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gtkauqygqh.html

[A03] 常量定义
来源：http://dali.chenlongwang.top/Article/details/gtwfaonwyx.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yangfankeji.com/Article/details/gtgmebcpcr.html

PHP:  const PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gtscmvjcdy.html

JS:   const PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtrregvoga.html

TS:   const PI: number = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtszenregi.html

Java: static final double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtrgwaykfp.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gtxqmokhbk.html

Ruby: PI = 3.14159
来源：http://dali.quarkkingdee.top/Article/details/gthyexjjkn.html

C#:   const double PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtomrudrbx.html

[A04] 判断变量类型
来源：http://dali.yangfankeji.com/Article/details/gtkitdoysh.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hammf.cn/Article/details/gtgnciwduj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shzxlz.cn/Article/details/gttwcwuwsk.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.havefunace.top/Article/details/gthlcwdbxs.html

TS:   typeof x; x instanceof Date
来源：http://dali.cashguo.top/Article/details/gtybxyxdow.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yuanzhike.top/Article/details/gtiyudyvkr.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yueranfly.top/Article/details/gtijadbcsg.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.havefunace.top/Article/details/gtycmwgxhd.html

C#:   x.GetType().Name; x is int
来源：http://dali.cucudq.cn/Article/details/gtojxueqfp.html

[A05] 整数除法与取模
来源：http://dali.yanxiufei.cn/Article/details/gtmzrcrbmi.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhongyouzk.top/Article/details/gtmweqrwmi.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gtnsvtexnq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gtxyttduym.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtgjllzllq.html

Java: 7 / 2; 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gtotpfwgbh.html

Go:   7 / 2; 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gtasbcpzwp.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yonumen.top/Article/details/gtfjijuofj.html

C#:   7 / 2; 7 % 2
来源：http://dali.yuxming.cn/Article/details/gtbradzyyv.html

[A06] 字符串转数字
来源：http://dali.haohaochexian.top/Article/details/gthilubize.html

Py:   int("42"); float("3.14")
来源：http://dali.jqgufenzy.top/Article/details/gtwthoseks.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yuanzhike.top/Article/details/gtccipjjlu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.chenlongwang.top/Article/details/gtbwuvhijh.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.quarkkingdee.top/Article/details/gtnymufkka.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.guowangkeji.top/Article/details/gtklukclfr.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yangfankeji.com/Article/details/gtfaxpojue.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jqgfzy.top/Article/details/gtkwpndqgg.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.ybcxt.top/Article/details/gtxvswvkcx.html

[A07] 数字转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxgajifq.html

Py:   str(42)
来源：http://dali.tian-w.cn/Article/details/gtqvbuawlg.html

PHP:  (string) 42; strval(42)
来源：http://dali.yuanzhike.top/Article/details/gtwnbqnakp.html

JS:   String(42); (42).toString()
来源：http://dali.gzhubu.top/Article/details/gtrpaozkji.html

TS:   String(42)
来源：http://dali.jinghuilouyu.cn/Article/details/gthbwojqaq.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.dashuyun.cn/Article/details/gtmqzmmtay.html

Go:   strconv.Itoa(42)
来源：http://dali.iojbl.cn/Article/details/gtpuijqdyv.html

Ruby: 42.to_s
来源：http://dali.sweek.top/Article/details/gtmbmfphgk.html

C#:   42.ToString()
来源：http://dali.zhixingplan.top/Article/details/gtoqkccfny.html

[A08] 取整与四舍五入
来源：http://dali.smart0.xyz/Article/details/gtgzoxpwcq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gtwamjkmxo.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.andypj.xyz/Article/details/gteuqpyqos.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.nanxuanxn.top/Article/details/gtauygatwf.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yvedp.cn/Article/details/gtfvaxssar.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jinqigufen.top/Article/details/gtabfwdfup.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yj20258888.top/Article/details/gtivusxdmx.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhiwuduotai.top/Article/details/gttygmjzwn.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.9152youxi.cn/Article/details/gtdmsrmgxl.html

[A09] 绝对值与最大最小值
来源：http://dali.redwolf501.top/Article/details/gtoovmbsxw.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yj20258888.top/Article/details/gtsheywgop.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.c1oappe.top/Article/details/gtkacwlqkg.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zycfv.cn/Article/details/gtveqeyqaj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtyrgjivkq.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hammf.cn/Article/details/gthhztqkbz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.shuidangran.top/Article/details/gtongczbrk.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.vqdsnc.cn/Article/details/gtrpllnrsf.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.redwolf501.top/Article/details/gtyccijfiq.html

[A10] 生成随机数
来源：http://dali.9152youxi.cn/Article/details/gtokatiwvr.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jlsjyb.cn/Article/details/gtdkmnylnh.html

PHP:  random_int(1, 100);
来源：http://dali.ivvv.top/Article/details/gtvhpekvof.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cashguo.top/Article/details/gtpfmvzkeu.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhixingplan.top/Article/details/gttuhslbuy.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yongpay.top/Article/details/gtjtxyiwxg.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.cqqwz.cn/Article/details/gtxcqvbnxx.html

Ruby: rand(1..100)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpiuxyfd.html

C#:   new Random().Next(1, 101)
来源：http://dali.pengpengdd.cyou/Article/details/gtyizirqju.html

[A11] 条件表达式（三元）
来源：http://dali.andypj.xyz/Article/details/gtuzbmnwxe.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yanxiufei.cn/Article/details/gtsubctloo.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.chenlongwang.top/Article/details/gtfuvwompi.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.havefunace.top/Article/details/gtvkvnpmmj.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.dianchejie.cn/Article/details/gtbnrwnsas.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedpfoogm.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.dianchejie.cn/Article/details/gtrfdweomy.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.smart0.xyz/Article/details/gtijbcmldc.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.havefunace.top/Article/details/gtkxhqzlrn.html

[A12] 字符串插值 / 格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gtavlcweeg.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.mhx1999.top/Article/details/gtbgxixvak.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.andypj.xyz/Article/details/gtdjpohxfq.html

JS:   `Hello, ${name}!`
来源：http://dali.sufxvd.cn/Article/details/gthxwaahco.html

TS:   `Hello, ${name}!`
来源：http://dali.guowangkeji.top/Article/details/gtmbvqpfot.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gtnjgqclom.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yvedp.cn/Article/details/gtbbmoxthy.html

Ruby: "Hello, #{name}!"
来源：http://dali.nanxinkj.top/Article/details/gtaymnzhwa.html

C#:   $"Hello, {name}!"
来源：http://dali.wangdashe.top/Article/details/gttgivwcsa.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.jinqigufen.top/Article/details/gthesdgtgm.html

Py:   "第一行\n第二行"
来源：http://dali.xuanzx.com/Article/details/gtrthsgfxm.html

PHP:  "第一行\n第二行"
来源：http://dali.tanke756.top/Article/details/gtjlycqzja.html

JS:   "第一行\n第二行"
来源：http://dali.xziqi.cn/Article/details/gtrpbbsvbn.html

TS:   "第一行\n第二行"
来源：http://dali.zhengqikj.top/Article/details/gtxqxkykdy.html


<!-- 参考信息 -->