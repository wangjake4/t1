代发 wailian999

[U85] JS：可选链
来源：http://dali.hfpthk.cn/Article/details/gt2aqfzizyr.html

a?.b?.c
来源：http://dali.nwbrower.top/Article/details/gt2vyovbkis.html

[U86] JS：空值合并
来源：http://dali.dashuyun.cn/Article/details/gt2aymkqjzr.html

a ?? b
来源：http://dali.yj20258.top/Article/details/gt2ffoikldb.html

[U87] JS：解构默认值
来源：http://dali.316326.xyz/Article/details/gt2vfzatzzn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jyoumei.cn/Article/details/gt2nhqvxnpv.html

[U88] JS：对象展开合并
来源：http://dali.yongpay.top/Article/details/gt2bvabwlgn.html

{ ...a, ...b }
来源：http://dali.nanxinkj.top/Article/details/gt2uhiziufr.html

[U89] JS：数组去重
来源：http://dali.snrcjt.cn/Article/details/gt2xewfjuta.html

[...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gt2rpqrwrcm.html

[U90] JS：数字数组排序
来源：http://dali.gaohongyu789.top/Article/details/gt2kxzimoaz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.redwolf501.top/Article/details/gt2vcegfzry.html

[U91] JS：对象键值遍历
来源：http://dali.ehwqpu.com/Article/details/gt2gliomamv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cqqwz.cn/Article/details/gt2oluwkupd.html

[U92] JS：深拷贝
来源：http://dali.tianlin.xyz/Article/details/gt2djmnfdsa.html

structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gt2oylewctf.html

[U93] JS：模板字符串
来源：http://dali.fengsongda.top/Article/details/gt2acuoespj.html

`共 ${n} 条`
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rpxlyiea.html

[U94] JS：箭头函数
来源：http://dali.fzhhl.top/Article/details/gt2xenonjdb.html

const double = x => x * 2;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2npgrnfkh.html

[U95] JS：Promise 包装
来源：http://dali.cashguo.top/Article/details/gt2qfndliak.html

new Promise((resolve, reject) => {})
来源：http://dali.snrcjt.cn/Article/details/gt2qamppchd.html

[U96] JS：async/await 与异常
来源：http://dali.fengsongda.top/Article/details/gt2kpwyfsmp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gt2ssiwsywi.html

[U97] JS：并发请求
来源：http://dali.jianghu66.top/Article/details/gt2fncgdugs.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gt2mdanaooe.html

[U98] JS：fetch 带 JSON
来源：http://dali.ivvv.top/Article/details/gt2xdywjoku.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.mhx1999.top/Article/details/gt2tajjqrmq.html

[U99] JS：事件监听
来源：http://dali.tianlin.xyz/Article/details/gt2mirzqkwi.html

el.addEventListener("click", e => {})
来源：http://dali.9152youxi.cn/Article/details/gt2xsiskusi.html

[U100] JS：DOM 查询
来源：http://dali.dianchejie.cn/Article/details/gt2ovkuhrsj.html

document.querySelector(".item")
来源：http://dali.ppjwa.cn/Article/details/gt2tvfoglen.html

[U101] JS：classList 操作
来源：http://dali.vqdsnc.cn/Article/details/gt2wplfsagu.html

el.classList.toggle("active")
来源：http://dali.9152youxi.cn/Article/details/gt2pedztiby.html

[U102] JS：本地存储
来源：http://dali.tanke756.top/Article/details/gt2agvzdpxg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ehwqpu.com/Article/details/gt2cwnqrvif.html

[U103] JS：定时器
来源：http://dali.yangfankeji.com/Article/details/gt2ijagtefw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cucudq.cn/Article/details/gt2yigwsbip.html

[U104] JS：防抖
来源：http://dali.nwbrower.top/Article/details/gt2zludgkzj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gt2wbmmemsp.html

[U105] JS：节流
来源：http://dali.aizwys.cn/Article/details/gt2psyaijce.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jqgfzy.top/Article/details/gt2nsbpeymj.html

[U106] JS：日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gt2qfgsmyaa.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhengqikj.top/Article/details/gt2csqkcgrx.html

[U107] JS：数字千分位
来源：http://dali.wangshuangyany.cn/Article/details/gt2aqqprhlj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.guowangkeji.top/Article/details/gt2ziyyfeow.html

[U108] JS：随机整数
来源：http://dali.gzhubu.top/Article/details/gt2zozjnogx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yonumen.top/Article/details/gt2tbbpucxn.html

[U109] JS：数组分组
来源：http://dali.sufxvd.cn/Article/details/gt2lnrxmlff.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jianghu66.top/Article/details/gt2xadxcecz.html

[U110] JS：数组分块
来源：http://dali.9152youxi.cn/Article/details/gt2jiwondbu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.snrcjt.cn/Article/details/gt2imxgwrai.html

[U111] JS：对象转 Map
来源：http://dali.haohaochexian.top/Article/details/gt2gondadtf.html

new Map(Object.entries(obj))
来源：http://dali.9152youxi.cn/Article/details/gt2zrbwwpcr.html

[U112] JS：字符串补位
来源：http://dali.yvedp.cn/Article/details/gt2gaknigev.html

"7".padStart(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gt2ysuckuty.html

[U113] JS：正则替换全部
来源：http://dali.smart0.xyz/Article/details/gt2gdmotppb.html

s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2qokxbveo.html

[U114] JS：JSON 深比较
来源：http://dali.zdqjudy.top/Article/details/gt2sedmvpgw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cucudq.cn/Article/details/gt2rezepjbg.html

[U115] JS：生成 UUID
来源：http://dali.xuanzx.com/Article/details/gt2xeidmcan.html

crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gt2ymibpexc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.mhx1999.top/Article/details/gt2xssomvjf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.iojbl.cn/Article/details/gt2xsgrosvs.html

[U117] JS：单元测试
来源：http://dali.cqqwz.cn/Article/details/gt2zbkocyxm.html

npm i -D vitest;  npx vitest
来源：http://dali.feifeiyinyue.top/Article/details/gt2znobhlqn.html

[U118] JS：开发服务器
来源：http://dali.tanke756.top/Article/details/gt2euewnqok.html

npm i -D vite;  npx vite
来源：http://dali.zhongyouzk.top/Article/details/gt2czqnhgxu.html

[U119] JS：生产构建
来源：http://dali.yueranfly.top/Article/details/gt2rsmeejyx.html

npx vite build
来源：http://dali.dashuyun.cn/Article/details/gt2kgsuogpm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gogol.net.cn/Article/details/gt2amrwatmz.html

import.meta.env.VITE_API_URL
来源：http://dali.jianghu66.top/Article/details/gt2mnzkcmlx.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2ykxqvyfp.html

统计汇总
来源：http://dali.ivvv.top/Article/details/gt2nalqicer.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2wobflzwh.html

按语言统计（条）：
来源：http://dali.hnqzz.top/Article/details/gt2qtqjvekk.html

Python ......... 252
来源：http://dali.shuidangran.top/Article/details/gt2xumdnzcx.html

PHP ............ 252
来源：http://dali.yj202588.top/Article/details/gt2tpctsqps.html

JavaScript ..... 252
来源：http://dali.gaohongyu789.top/Article/details/gt2sntuyjof.html

TypeScript ..... 212
来源：http://dali.wangdashe.top/Article/details/gt2reofdbol.html

Java ........... 212
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kjnpnmlm.html

Go ............. 212
来源：http://dali.yj20258888.top/Article/details/gt2pemibwmf.html

Ruby ........... 212
来源：http://dali.iojbl.cn/Article/details/gt2gllugoza.html

C# ............. 212
来源：http://dali.zhiwuduotai.top/Article/details/gt2vlayphre.html

C .............. 30
来源：http://dali.daria6918.cn/Article/details/gt2jtzodeei.html

C++ ............ 30
来源：http://dali.ydzc1.top/Article/details/gt2fdmhcukn.html

SQL ............ 90
来源：http://dali.ivvv.top/Article/details/gt2ooihndbs.html

Bash ........... 80
来源：http://dali.jinqigfzy.top/Article/details/gt2wlksbect.html

Kotlin ......... 15
来源：http://dali.cheryme.top/Article/details/gt2beydmosc.html

Swift .......... 15
来源：http://dali.redwolf501.top/Article/details/gt2axzpyple.html

Lua ............ 10
来源：http://dali.quarkkingdee.top/Article/details/gt2btiqwqql.html

Perl ........... 10
来源：http://dali.tianlin.xyz/Article/details/gt2jayuelml.html

Scala .......... 10
来源：http://dali.sxryk.cn/Article/details/gt2pkfvhihk.html

------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wmvyjghb.html

合计 ........... 2106 条
来源：http://dali.hfpthk.cn/Article/details/gt2duciywhb.html

按章节统计：
来源：http://dali.svipenyu.cn/Article/details/gt2olblmveb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hfpthk.cn/Article/details/gt2anijthet.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.dianchejie.cn/Article/details/gt2vgzdtbmh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zsbukkxb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.nwbrower.top/Article/details/gt2fmclidkz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xinyue.icu/Article/details/gt2gvsdayuj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.snrcjt.cn/Article/details/gt2ecmvwwhw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.birdmap.top/Article/details/gt2qotcixus.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dfxbprqt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gt2prptftvr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cheryme.top/Article/details/gt2umbfepyl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gt2pynbnzls.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gt2tanmgxej.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gt2ykziotgs.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.pengpengdd.cyou/Article/details/gt2numhugrv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hongshengwenyu.top/Article/details/gt2faglgyfn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.sweek.top/Article/details/gt2pkebhzxf.html

Q SQL 专题                              90
来源：http://dali.ydzc1.top/Article/details/gt2ajggmupw.html

R Bash 专题                             80
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mzcfeawv.html

S C / C++ 专题                          60
来源：http://dali.cheryme.top/Article/details/gt2hwlxbsbw.html

T 其他语言补充                          60
来源：http://dali.mhx1999.top/Article/details/gt2ljzwnbvw.html

U 高频实用片段                         120
来源：http://dali.quarkkingdee.top/Article/details/gt2dhfczsnc.html

------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gt2tyhzvdga.html

合计                                  2106 条
来源：http://dali.gzhubu.top/Article/details/gt2ltayxknz.html

--------------------------------------------------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gt2tyygqnyb.html

使用提醒
来源：http://dali.xinyue.icu/Article/details/gt2innqrrpz.html

--------------------------------------------------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gt2gyxzujyt.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cqqwz.cn/Article/details/gt2vrmmropx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.dashuyun.cn/Article/details/gt2wvdfurhc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ydzc1.top/Article/details/gt2jaxddhjg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yj20258888.top/Article/details/gt2mepcucrl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.smart0.xyz/Article/details/gt2zcbfdltk.html

—— 文件结束 ——
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vkzhhiyt.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2mgktwzny.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.9152youxi.cn/Article/details/gt2dmkgnbge.html

Common Programming Examples Cheat Book
来源：http://dali.pengpengdd.cyou/Article/details/gt2qixbsbac.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2wpnygrjh.html

【收录内容】
来源：http://dali.yonumen.top/Article/details/gt2wrcfegks.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yvedp.cn/Article/details/gt2kudtokwz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cashguo.top/Article/details/gt2oxhmfenu.html

SQL · Bash · C · C++
来源：http://dali.yuanzhike.top/Article/details/gt2jjdjuhxi.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.iojbl.cn/Article/details/gt2yfbrydks.html

【使用说明】
来源：http://dali.zhixingplan.top/Article/details/gt2rmcebabm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.smart0.xyz/Article/details/gt2hhmqahpz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.feifeiyinyue.top/Article/details/gt2heuoueam.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.dianchejie.cn/Article/details/gt2qhtkeviz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.wangdashe.top/Article/details/gt2jqljamdd.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jodwlyel.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.snrcjt.cn/Article/details/gt2aewyxaua.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.ivvv.top/Article/details/gt2yqrljfkd.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhiwuduotai.top/Article/details/gt2aycskbul.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jianghu66.top/Article/details/gt2ykimmepi.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhengqikj.top/Article/details/gt2fczlsrlm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.tianlin.xyz/Article/details/gt2bhihpfaw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yj20258.top/Article/details/gt2hvqznmnk.html

【文件统计】
来源：http://dali.kuanghao11.cn/Article/details/gt2lyjzgyzk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xziqi.cn/Article/details/gt2nntkbcas.html

--------------------------------------------------------------------------------
来源：http://dali.yj202588.top/Article/details/gt2cwfrpoqc.html

目  录
来源：http://dali.gzhubu.top/Article/details/gt2yhvbzmss.html

--------------------------------------------------------------------------------
来源：http://dali.yj202588.top/Article/details/gt2wqlxftqc.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yj20258888.top/Article/details/gt2nckergdl.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.sxryk.cn/Article/details/gt2enmcsuzv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.316326.xyz/Article/details/gt2gtyacpvw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2wmixyeup.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.andypj.xyz/Article/details/gt2rfpotxdx.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.gotoacloud.top/Article/details/gt2xnaroudv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jianghu66.top/Article/details/gt2zjhkqkth.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.tian-w.cn/Article/details/gt2jxdgqsuz.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gt2aafvmvlo.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hnqzz.top/Article/details/gt2bxhwffew.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.daxiang520.top/Article/details/gt2ovixklux.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gt2xpevsvjr.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.dashuyun.cn/Article/details/gt2opsbpbyh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.chenzaomai.com/Article/details/gt2lbrweqpb.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jvvisvfo.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gt2fconxwof.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.nanxinkj.top/Article/details/gt2cqimgwtz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.9152youxi.cn/Article/details/gt2uarndczp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.redwolf501.top/Article/details/gt2algewcsv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jyoumei.cn/Article/details/gt2hwmnsjlv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zdqjudy.top/Article/details/gt2dzwtkwec.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2hktayghe.html

A. 基础语法与类型
来源：http://dali.jqgufenzy.top/Article/details/gt2dsgohjfe.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2ebldwijp.html

[A01] Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2awnhlplj.html

Py:   print("Hello, World!")
来源：http://dali.shzxlz.cn/Article/details/gt2pimmkddc.html

PHP:  echo "Hello, World!";
来源：http://dali.0kj1m.cn/Article/details/gt2zkkmckaz.html

JS:   console.log("Hello, World!");
来源：http://dali.svipenyu.cn/Article/details/gt2pttuhlfr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cheryme.top/Article/details/gt2aorkamke.html

Java: System.out.println("Hello, World!");
来源：http://dali.gzhubu.top/Article/details/gt2fpyuawgz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yj20258.top/Article/details/gt2okwssdjx.html

Ruby: puts "Hello, World!"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dsrapibq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.kuanghao11.cn/Article/details/gt2stfkaqnp.html

[A02] 变量声明与赋值
来源：http://dali.jqgufenzy.top/Article/details/gt2tbyxifuy.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.gotoacloud.top/Article/details/gt2wuopryvr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhengqikj.top/Article/details/gt2vskmaamz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shzxlz.cn/Article/details/gt2rbjfebat.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.haohaochexian.top/Article/details/gt2kkrodzap.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.9152youxi.cn/Article/details/gt2fktfaavb.html

Go:   name := "Alex"; age := 20
来源：http://dali.jqgufenzy.top/Article/details/gt2uloxlrms.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yuanzhike.top/Article/details/gt2ajrgcnfo.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.aizwys.cn/Article/details/gt2jsxpjvgu.html

[A03] 常量定义
来源：http://dali.gaohongyu789.top/Article/details/gt2diivtsgf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.havefunace.top/Article/details/gt2tytyvwhx.html

PHP:  const PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gt2eawndzuj.html

JS:   const PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gt2mamzhnkf.html

TS:   const PI: number = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gt2rbispbun.html

Java: static final double PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gt2wuwmtjgs.html

Go:   const PI = 3.14159
来源：http://dali.sysykeji.top/Article/details/gt2haavqcfi.html

Ruby: PI = 3.14159
来源：http://dali.snrcjt.cn/Article/details/gt2xyozkqjv.html

C#:   const double PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gt2kppwssrk.html

[A04] 判断变量类型
来源：http://dali.redwolf501.top/Article/details/gt2yvrjaoks.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xinyue.icu/Article/details/gt2pehxfcqn.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iwtpnpzf.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.kuanghao11.cn/Article/details/gt2hmzcsfpw.html

TS:   typeof x; x instanceof Date
来源：http://dali.hysaishi.cn/Article/details/gt2uwzhvqtj.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jyoumei.cn/Article/details/gt2gtrkjhkm.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yonumen.top/Article/details/gt2ayokbqtl.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.316326.xyz/Article/details/gt2pbysejai.html

C#:   x.GetType().Name; x is int
来源：http://dali.redwolf501.top/Article/details/gt2mjlmdqwl.html

[A05] 整数除法与取模
来源：http://dali.jqgfzy.top/Article/details/gt2dqsfbalu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.kuanghao11.cn/Article/details/gt2pmxxvxts.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.birdmap.top/Article/details/gt2mgagyrhd.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gt2kkkknlbn.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gt2urvfmpve.html

Java: 7 / 2; 7 % 2
来源：http://dali.yj20258888.top/Article/details/gt2wtzfihgm.html

Go:   7 / 2; 7 % 2
来源：http://dali.xylfe.cn/Article/details/gt2mvprwawt.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xinyue.icu/Article/details/gt2sflydkna.html

C#:   7 / 2; 7 % 2
来源：http://dali.yj20258.top/Article/details/gt2nlqwponb.html

[A06] 字符串转数字
来源：http://dali.zycfv.cn/Article/details/gt2xfssqtdv.html

Py:   int("42"); float("3.14")
来源：http://dali.c1oappe.top/Article/details/gt2tpapkxll.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.xylfe.cn/Article/details/gt2rrjlspvx.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.quarkkingdee.top/Article/details/gt2xhioqxpz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hywenlv.cn/Article/details/gt2czyilset.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.xziqi.cn/Article/details/gt2zonllpha.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jwfctyyo.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.xinyue.icu/Article/details/gt2bkzfeocj.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yueranfly.top/Article/details/gt2fcbrbuwn.html

[A07] 数字转字符串
来源：http://dali.mhx1999.top/Article/details/gt2xerngghd.html

Py:   str(42)
来源：http://dali.sxryk.cn/Article/details/gt2xcifsoke.html

PHP:  (string) 42; strval(42)
来源：http://dali.zdqjudy.top/Article/details/gt2zhtbioja.html

JS:   String(42); (42).toString()
来源：http://dali.jqgufenzy.top/Article/details/gt2ampbpsbd.html

TS:   String(42)
来源：http://dali.jinqigfzy.top/Article/details/gt2nrxyttbf.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ivvv.top/Article/details/gt2sqjyipkp.html

Go:   strconv.Itoa(42)
来源：http://dali.yj20258888.top/Article/details/gt2wtmpnpzz.html

Ruby: 42.to_s
来源：http://dali.sxryk.cn/Article/details/gt2xhcpmqvz.html

C#:   42.ToString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ploupgkd.html

[A08] 取整与四舍五入
来源：http://dali.chenjidiqi.icu/Article/details/gt2epucmplf.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yueranfly.top/Article/details/gt2kdhupdie.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.gotoacloud.top/Article/details/gt2rspayclw.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.sxryk.cn/Article/details/gt2qpxftbsf.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.tian-w.cn/Article/details/gt2obnsefom.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gt2gctllglw.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jqgfzy.top/Article/details/gt2bdnompnl.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.shangyingyoupin.top/Article/details/gt2vmnzrhmq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jinqigfzy.top/Article/details/gt2uayckedp.html

[A09] 绝对值与最大最小值
来源：http://dali.zhixingplan.top/Article/details/gt2ojyvtvgp.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gt2pkzlkypp.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2aokpntyn.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hpzryumq.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hxauyeyz.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2nvwodggz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.gogol.net.cn/Article/details/gt2rlqiuzna.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.dianchejie.cn/Article/details/gt2yvdtinbi.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ozmogcpq.html

[A10] 生成随机数
来源：http://dali.xylfe.cn/Article/details/gt2pfumlgyh.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gsfnrqei.html

PHP:  random_int(1, 100);
来源：http://dali.xziqi.cn/Article/details/gt2ndttaqfx.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.tian-w.cn/Article/details/gt2zlkgatnd.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.vqdsnc.cn/Article/details/gt2klimuihr.html

Java: new Random().nextInt(100) + 1
来源：http://dali.sufxvd.cn/Article/details/gt2fzorylvl.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.bjfxy.top/Article/details/gt2qacfouis.html

Ruby: rand(1..100)
来源：http://dali.shzxlz.cn/Article/details/gt2xzmbbolm.html

C#:   new Random().Next(1, 101)
来源：http://dali.xziqi.cn/Article/details/gt2nmhcgfyq.html

[A11] 条件表达式（三元）
来源：http://dali.9152youxi.cn/Article/details/gt2bvbhrtxq.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.pengpengdd.cyou/Article/details/gt2nwmllljm.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hywenlv.cn/Article/details/gt2oqzgqwsl.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.hywenlv.cn/Article/details/gt2emxwcaqu.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.meibo888.top/Article/details/gt2chjyygjs.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.shzxlz.cn/Article/details/gt2avxibrtf.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.redwolf501.top/Article/details/gt2ypxquvjx.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2stszmlcj.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.fzhhl.top/Article/details/gt2rcsjtlbf.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhiwuduotai.top/Article/details/gt2rwmuljew.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.vqdsnc.cn/Article/details/gt2xmjhmoxt.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.cucudq.cn/Article/details/gt2yofkhrrr.html

JS:   `Hello, ${name}!`
来源：http://dali.ehwqpu.com/Article/details/gt2bpnxundd.html

TS:   `Hello, ${name}!`
来源：http://dali.tianlin.xyz/Article/details/gt2mvmvzogv.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.shzxlz.cn/Article/details/gt2bayxhkxx.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.dashuyun.cn/Article/details/gt2zezoukup.html

Ruby: "Hello, #{name}!"
来源：http://dali.zycfv.cn/Article/details/gt2tbhqghdp.html

C#:   $"Hello, {name}!"
来源：http://dali.redwolf501.top/Article/details/gt2alzehfgp.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hxikvgqu.html

Py:   "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gt2xqnsmcsu.html

PHP:  "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gt2yqtsngmo.html

JS:   "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gt2ptnfznwl.html

TS:   "第一行\n第二行"
来源：http://dali.quarkkingdee.top/Article/details/gt2xrpldyfe.html

Java: "第一行\n第二行"
来源：http://dali.iojbl.cn/Article/details/gt2ufdlttpx.html

Go:   "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gt2lcrkyhfn.html

Ruby: "第一行\n第二行"
来源：http://dali.xinyue.icu/Article/details/gt2auosfxqj.html

C#:   "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rztlbdxq.html

[A14] 注释写法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yhstlaft.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.cheryme.top/Article/details/gt2zximuitz.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.ehwqpu.com/Article/details/gt2shibtfri.html

JS:   // 单行；/* 多行 */
来源：http://dali.xinyue.icu/Article/details/gt2zaabeyhu.html


<!-- 参考信息 -->