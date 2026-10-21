代发 wailian999

[U87] JS：解构默认值
来源：http://dali.hysaishi.cn/Article/details/gtgwvrzvdr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hywenlv.cn/Article/details/gtvysssvnr.html

[U88] JS：对象展开合并
来源：http://dali.aibaodan.cn/Article/details/gtonweaqwe.html

{ ...a, ...b }
来源：http://dali.yj202588.top/Article/details/gtbmiitumh.html

[U89] JS：数组去重
来源：http://dali.yuanzhike.top/Article/details/gtstphhdjh.html

[...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gthlgbsubk.html

[U90] JS：数字数组排序
来源：http://dali.xylfe.cn/Article/details/gtdxivynhw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gtbqxnblbe.html

[U91] JS：对象键值遍历
来源：http://dali.jlsjyb.cn/Article/details/gtlfoapxnd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.redwolf501.top/Article/details/gtojyuovaf.html

[U92] JS：深拷贝
来源：http://dali.gotoacloud.top/Article/details/gtbyxoxwcv.html

structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtqbfxgvkh.html

[U93] JS：模板字符串
来源：http://dali.andypj.xyz/Article/details/gtgdooqytk.html

`共 ${n} 条`
来源：http://dali.yuxming.cn/Article/details/gtyurtvsmi.html

[U94] JS：箭头函数
来源：http://dali.aizwys.cn/Article/details/gtlhoebzbs.html

const double = x => x * 2;
来源：http://dali.guannengcc.top/Article/details/gtjtnrpctx.html

[U95] JS：Promise 包装
来源：http://dali.yj20258.top/Article/details/gtspbxzhje.html

new Promise((resolve, reject) => {})
来源：http://dali.jinghuilouyu.cn/Article/details/gtlyohrbit.html

[U96] JS：async/await 与异常
来源：http://dali.hnxiangtu.top/Article/details/gtmxxipinz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtqwqjsnac.html

[U97] JS：并发请求
来源：http://dali.fzhhl.top/Article/details/gtrftiwuyi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtnxxrcwmh.html

[U98] JS：fetch 带 JSON
来源：http://dali.hongshengwenyu.top/Article/details/gthukclbhg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hongshengwenyu.top/Article/details/gtrrsjhptk.html

[U99] JS：事件监听
来源：http://dali.cdnleiting.top/Article/details/gtlqhvmjng.html

el.addEventListener("click", e => {})
来源：http://dali.snrcjt.cn/Article/details/gtslwdshid.html

[U100] JS：DOM 查询
来源：http://dali.zhixingplan.top/Article/details/gtddrhjzwl.html

document.querySelector(".item")
来源：http://dali.fzhhl.top/Article/details/gtqspdcaux.html

[U101] JS：classList 操作
来源：http://dali.yj20258888.top/Article/details/gtexukfofx.html

el.classList.toggle("active")
来源：http://dali.hfpthk.cn/Article/details/gtoyafxazu.html

[U102] JS：本地存储
来源：http://dali.yongpay.top/Article/details/gtugcritkj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gtnkcyvytc.html

[U103] JS：定时器
来源：http://dali.zhixingplan.top/Article/details/gthjxqmrvk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gaohongyu789.top/Article/details/gtbrwfurbg.html

[U104] JS：防抖
来源：http://dali.meibo888.top/Article/details/gtznfascbw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtcqpiatii.html

[U105] JS：节流
来源：http://dali.gogol.net.cn/Article/details/gtdvqkklvk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.chenlongwang.top/Article/details/gtoekgursx.html

[U106] JS：日期格式化
来源：http://dali.sweek.top/Article/details/gtnzbibcjk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.feifeiyinyue.top/Article/details/gtffodyanj.html

[U107] JS：数字千分位
来源：http://dali.xziqi.cn/Article/details/gtixhsbxnk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jiagoushi.top/Article/details/gtjijstviu.html

[U108] JS：随机整数
来源：http://dali.feifeiyinyue.top/Article/details/gttfcpfzma.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.gaohongyu789.top/Article/details/gtwiflexlv.html

[U109] JS：数组分组
来源：http://dali.shzxlz.cn/Article/details/gtrxcblfxb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yanxiufei.cn/Article/details/gtewhxzwrr.html

[U110] JS：数组分块
来源：http://dali.birdmap.top/Article/details/gtliexzjkm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.chenjidiqi.icu/Article/details/gtbabrpxof.html

[U111] JS：对象转 Map
来源：http://dali.yj20258.top/Article/details/gtizslkwkl.html

new Map(Object.entries(obj))
来源：http://dali.nwbrower.top/Article/details/gtjtwcfhqx.html

[U112] JS：字符串补位
来源：http://dali.jianghu66.top/Article/details/gtnodtoabh.html

"7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gtidhfiber.html

[U113] JS：正则替换全部
来源：http://dali.kuanghao11.cn/Article/details/gttnbfpxwi.html

s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtjukauxyj.html

[U114] JS：JSON 深比较
来源：http://dali.shangyingyoupin.top/Article/details/gtxdbqsaxz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gthiogyccx.html

[U115] JS：生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gtcqnqmubn.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gtlqxneipn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhixingplan.top/Article/details/gtczksqzsj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yanxiufei.cn/Article/details/gtmrxzdfoa.html

[U117] JS：单元测试
来源：http://dali.yuxming.cn/Article/details/gtoemknhtp.html

npm i -D vitest;  npx vitest
来源：http://dali.jyoumei.cn/Article/details/gtpqskgxqz.html

[U118] JS：开发服务器
来源：http://dali.tian-w.cn/Article/details/gtvuyccupa.html

npm i -D vite;  npx vite
来源：http://dali.jqgufenzy.top/Article/details/gtfhhrbvoe.html

[U119] JS：生产构建
来源：http://dali.zhoulong.xyz/Article/details/gtgycoichs.html

npx vite build
来源：http://dali.zycfv.cn/Article/details/gtfzofkinw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zycfv.cn/Article/details/gtxjicplde.html

import.meta.env.VITE_API_URL
来源：http://dali.xinyue.icu/Article/details/gtmswqxrcs.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtfhheaxyl.html

统计汇总
来源：http://dali.nanxinkj.top/Article/details/gtxhsjjmuy.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtyshibvnx.html

按语言统计（条）：
来源：http://dali.yvedp.cn/Article/details/gtqvyrntwf.html

Python ......... 252
来源：http://dali.nwbrower.top/Article/details/gttdlfgwxg.html

PHP ............ 252
来源：http://dali.nwbrower.top/Article/details/gtmuayurcn.html

JavaScript ..... 252
来源：http://dali.yongpay.top/Article/details/gtsdxherdc.html

TypeScript ..... 212
来源：http://dali.svipenyu.cn/Article/details/gtlhyknqmt.html

Java ........... 212
来源：http://dali.zdqjudy.top/Article/details/gtawykkbqx.html

Go ............. 212
来源：http://dali.xylfe.cn/Article/details/gtuvxlddxt.html

Ruby ........... 212
来源：http://dali.zhoulong.xyz/Article/details/gtvxtzvykh.html

C# ............. 212
来源：http://dali.zdqjudy.top/Article/details/gtcemzhgue.html

C .............. 30
来源：http://dali.birdmap.top/Article/details/gteockaecz.html

C++ ............ 30
来源：http://dali.sufxvd.cn/Article/details/gtnifwsjku.html

SQL ............ 90
来源：http://dali.gaohongyu789.top/Article/details/gtsxytvzrc.html

Bash ........... 80
来源：http://dali.gogol.net.cn/Article/details/gtmqbcuhko.html

Kotlin ......... 15
来源：http://dali.yj20258.top/Article/details/gtzkvzyfzw.html

Swift .......... 15
来源：http://dali.wangdashe.top/Article/details/gtqraltwyr.html

Lua ............ 10
来源：http://dali.jlsjyb.cn/Article/details/gteiucpbwa.html

Perl ........... 10
来源：http://dali.zhongyouzk.top/Article/details/gtkxwjppna.html

Scala .......... 10
来源：http://dali.xuanzx.com/Article/details/gttobsukwy.html

------------------------------------
来源：http://dali.daxiang520.top/Article/details/gtyinalvll.html

合计 ........... 2106 条
来源：http://dali.xinyue.icu/Article/details/gteqlfrdny.html

按章节统计：
来源：http://dali.nwbrower.top/Article/details/gtbgufbhxf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shzxlz.cn/Article/details/gtsdosiaps.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinghuilouyu.cn/Article/details/gtllvuyhxw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hfpthk.cn/Article/details/gtpdqeeoqs.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yj202588.top/Article/details/gtfhhiogot.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.chenjidiqi.icu/Article/details/gtqnoeginu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.nanxinkj.top/Article/details/gtmunvesfa.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmlfnnhmm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zycfv.cn/Article/details/gtkpavcdfx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gtlsawpzhg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.bjfxy.top/Article/details/gtruydwwwi.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gtydbsfuyd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gtnhdizaqo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gtnuzgmhri.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhiwuduotai.top/Article/details/gtzbiyfemq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cqqwz.cn/Article/details/gtoymnorvi.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gtuydxqobb.html

Q SQL 专题                              90
来源：http://dali.guannengcc.top/Article/details/gtmwxdxdsm.html

R Bash 专题                             80
来源：http://dali.yuanzhike.top/Article/details/gtlalhxtll.html

S C / C++ 专题                          60
来源：http://dali.gaohongyu789.top/Article/details/gtenyuqfmn.html

T 其他语言补充                          60
来源：http://dali.shangyingyoupin.top/Article/details/gtbhojdlwf.html

U 高频实用片段                         120
来源：http://dali.zhongyouzk.top/Article/details/gtnpbofjos.html

------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpvfqtlj.html

合计                                  2106 条
来源：http://dali.ivvv.top/Article/details/gtgkaztyvt.html

--------------------------------------------------------------------------------
来源：http://dali.yj202588.top/Article/details/gtybhtmzzi.html

使用提醒
来源：http://dali.sweek.top/Article/details/gtlonriyrk.html

--------------------------------------------------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gtgqupikks.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hywenlv.cn/Article/details/gtlihbccfk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.tian-w.cn/Article/details/gtavolrzdj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.kuanghao11.cn/Article/details/gtttkfbewq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.dianchejie.cn/Article/details/gtgothgzqu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.quarkkingdee.top/Article/details/gtpulioabe.html

—— 文件结束 ——
来源：http://dali.hfpthk.cn/Article/details/gtmxayidrh.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtxskfttvy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.fengsongda.top/Article/details/gtsifhjagy.html

Common Programming Examples Cheat Book
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxctzjqy.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtgqhztmpv.html

【收录内容】
来源：http://dali.fengsongda.top/Article/details/gtkvywekky.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhixingplan.top/Article/details/gtatyusyzh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.tianlin.xyz/Article/details/gtutlhehit.html

SQL · Bash · C · C++
来源：http://dali.daria6918.cn/Article/details/gtjozbrjvq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.nanxuanxn.top/Article/details/gtnxtcahce.html

【使用说明】
来源：http://dali.hongshengwenyu.top/Article/details/gtvjbxdjni.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cdnleiting.top/Article/details/gtqlelnrbm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xylfe.cn/Article/details/gthcbkutwz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jqgufenzy.top/Article/details/gttlghtabt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.sysykeji.top/Article/details/gtubsdwluu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.c1oappe.top/Article/details/gtyjcihyao.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.aibaodan.cn/Article/details/gtcomzdxiv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.316326.xyz/Article/details/gtknzzsadu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdzoibfy.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yj20258.top/Article/details/gtgadvagsh.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.sweek.top/Article/details/gtgvhzvhcg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.sufxvd.cn/Article/details/gtfwjlyvri.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yuxming.cn/Article/details/gtktjmkzuc.html

【文件统计】
来源：http://dali.zhoulong.xyz/Article/details/gtahyfjast.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.nanxuanxn.top/Article/details/gtwiwrupgy.html

--------------------------------------------------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gtlpeeujbi.html

目  录
来源：http://dali.cqqwz.cn/Article/details/gtmppsiugp.html

--------------------------------------------------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gtqakjvtwy.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.chenlongwang.top/Article/details/gtqbdjnpya.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.nwbrower.top/Article/details/gtrnxdenct.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhongyouzk.top/Article/details/gtibtodems.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jianghu66.top/Article/details/gtbslzzzum.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtxknnsirf.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.andypj.xyz/Article/details/gtcbyjcmop.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.tianlin.xyz/Article/details/gtrutmikeo.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtznkjlmps.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.kuanghao11.cn/Article/details/gtwpksbmhf.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhixingplan.top/Article/details/gttzrzotuy.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hywenlv.cn/Article/details/gtoqzphrhl.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhengqikj.top/Article/details/gttamxezhs.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xinyue.icu/Article/details/gttmobyuzr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.sysykeji.top/Article/details/gtxdqbwcuo.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhengqikj.top/Article/details/gtybxajnbk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gtunownkma.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.meibo888.top/Article/details/gtjwmdbuoc.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.fzhhl.top/Article/details/gtrpxrkpkp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zycfv.cn/Article/details/gttuttznap.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gogol.net.cn/Article/details/gtmkygkewd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtyedoqpzm.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtrmldlomy.html

A. 基础语法与类型
来源：http://dali.c1oappe.top/Article/details/gtbxaepemz.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtllumcech.html

[A01] Hello World
来源：http://dali.tanke756.top/Article/details/gthgdfzwsn.html

Py:   print("Hello, World!")
来源：http://dali.ivvv.top/Article/details/gtudmianrs.html

PHP:  echo "Hello, World!";
来源：http://dali.zhoulong.xyz/Article/details/gtgiqyntjy.html

JS:   console.log("Hello, World!");
来源：http://dali.yj20258888.top/Article/details/gtgfqxscaw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.dashuyun.cn/Article/details/gtxrvceylt.html

Java: System.out.println("Hello, World!");
来源：http://dali.daxiang520.top/Article/details/gtxgmtyqgj.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jianghu66.top/Article/details/gtfnhpmdqk.html

Ruby: puts "Hello, World!"
来源：http://dali.zhoulong.xyz/Article/details/gtmstuewef.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yuxming.cn/Article/details/gtghwargpg.html

[A02] 变量声明与赋值
来源：http://dali.jyoumei.cn/Article/details/gtasvdhamk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.svipenyu.cn/Article/details/gtfnqtaskq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.cqqwz.cn/Article/details/gtfpzbygnv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.bjfxy.top/Article/details/gtjwpztbrc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zdqjudy.top/Article/details/gtswgirnrk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.nanxinkj.top/Article/details/gtcasfajxy.html

Go:   name := "Alex"; age := 20
来源：http://dali.wangdashe.top/Article/details/gtqrpamzka.html

Ruby: name = "Alex"; age = 20
来源：http://dali.tian-w.cn/Article/details/gtmibwbpba.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqcodttvw.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gtqphsromx.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ybcxt.top/Article/details/gtnjupxebg.html

PHP:  const PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtsgjrrlke.html

JS:   const PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtlhpauhuq.html

TS:   const PI: number = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtmuqbjjtj.html

Java: static final double PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtdltoccgr.html

Go:   const PI = 3.14159
来源：http://dali.jqgfzy.top/Article/details/gtlnltrlvr.html

Ruby: PI = 3.14159
来源：http://dali.svipenyu.cn/Article/details/gtannviyxn.html

C#:   const double PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtcegilhar.html

[A04] 判断变量类型
来源：http://dali.sweek.top/Article/details/gtnofeomza.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.shuidangran.top/Article/details/gtxqruftig.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.sysykeji.top/Article/details/gtxidmnjsw.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.tanke756.top/Article/details/gthcgnqbgu.html

TS:   typeof x; x instanceof Date
来源：http://dali.hongshengwenyu.top/Article/details/gtdwrocspk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shzxlz.cn/Article/details/gtvmaalvlu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jlsjyb.cn/Article/details/gtrshkwalt.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.guannengcc.top/Article/details/gtbzzajtvj.html

C#:   x.GetType().Name; x is int
来源：http://dali.ydzc1.top/Article/details/gtgrwlepjd.html

[A05] 整数除法与取模
来源：http://dali.fengsongda.top/Article/details/gtnshbxskb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yangfankeji.com/Article/details/gtchrklphv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gtoweouxcb.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.haohaochexian.top/Article/details/gtkjtrjocw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtkbmmzoma.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaryrzetv.html

Go:   7 / 2; 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gthbvkfeot.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtozwwisoi.html

C#:   7 / 2; 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygnplhzm.html

[A06] 字符串转数字
来源：http://dali.iojbl.cn/Article/details/gtutmckxgm.html

Py:   int("42"); float("3.14")
来源：http://dali.jianghu66.top/Article/details/gtwsxgxxjs.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.pengpengdd.cyou/Article/details/gtolsieszl.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.xinyue.icu/Article/details/gtcrqjiuvw.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hnxiangtu.top/Article/details/gtzasqzcns.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cdnleiting.top/Article/details/gtbcmntqhb.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.sufxvd.cn/Article/details/gtppfueghi.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhengqikj.top/Article/details/gtkuugegpv.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwljtxgk.html

[A07] 数字转字符串
来源：http://dali.dianchejie.cn/Article/details/gthjknzmhc.html

Py:   str(42)
来源：http://dali.jianghu66.top/Article/details/gthsmyphqf.html

PHP:  (string) 42; strval(42)
来源：http://dali.gotoacloud.top/Article/details/gtwamkntit.html

JS:   String(42); (42).toString()
来源：http://dali.nwbrower.top/Article/details/gtspligufr.html

TS:   String(42)
来源：http://dali.ydzc1.top/Article/details/gtmiixfdyg.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jiagoushi.top/Article/details/gtcfmllamr.html

Go:   strconv.Itoa(42)
来源：http://dali.hfpthk.cn/Article/details/gttluriggc.html

Ruby: 42.to_s
来源：http://dali.cashguo.top/Article/details/gtuhwsufyg.html

C#:   42.ToString()
来源：http://dali.zhongyouzk.top/Article/details/gtfmluoxxn.html

[A08] 取整与四舍五入
来源：http://dali.sweek.top/Article/details/gtjoswxyjp.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jinqigufen.top/Article/details/gtctvdjanz.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hammf.cn/Article/details/gtzuvyvuzd.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zdqjudy.top/Article/details/gtiahhpgnt.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.ydzc1.top/Article/details/gtuabneerh.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zdqjudy.top/Article/details/gttdgsxyts.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gtymnjefkg.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.hnxiangtu.top/Article/details/gtzpsstgkq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ivvv.top/Article/details/gtznlbuqjt.html

[A09] 绝对值与最大最小值
来源：http://dali.jiagoushi.top/Article/details/gtgccfojtn.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cheryme.top/Article/details/gtqycxvkjj.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cheryme.top/Article/details/gtgrvmdbiy.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.tanke756.top/Article/details/gthcgycnsb.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gtyomxbhcz.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gtvzxpnegp.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yuanzhike.top/Article/details/gtouoccvda.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.daxiang520.top/Article/details/gthcgyiaif.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gtyqdzlryx.html

[A10] 生成随机数
来源：http://dali.cheryme.top/Article/details/gtuaoatqsv.html

Py:   import random; random.randint(1, 100)
来源：http://dali.fengsongda.top/Article/details/gthhgrzjwa.html

PHP:  random_int(1, 100);
来源：http://dali.pengpengdd.cyou/Article/details/gtrikwetny.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.dianchejie.cn/Article/details/gtgltbfftw.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cucudq.cn/Article/details/gtdortznbi.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtznqgdsdv.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.ydzc1.top/Article/details/gtwtglunms.html

Ruby: rand(1..100)
来源：http://dali.yonumen.top/Article/details/gtrussrekz.html

C#:   new Random().Next(1, 101)
来源：http://dali.guannengcc.top/Article/details/gtvesvebmh.html

[A11] 条件表达式（三元）
来源：http://dali.jlsjyb.cn/Article/details/gtvjnpqusy.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjxfdekq.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.c1oappe.top/Article/details/gtlippuras.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yuanzhike.top/Article/details/gtxswcxeew.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jinqigfzy.top/Article/details/gtqdnegsth.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.aibaodan.cn/Article/details/gtdylincju.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.hywenlv.cn/Article/details/gtlsdeixxo.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.wangshuangyany.cn/Article/details/gtslpspkex.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.svipenyu.cn/Article/details/gtnpgdunpl.html

[A12] 字符串插值 / 格式化
来源：http://dali.yongpay.top/Article/details/gtsyalcxio.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.cashguo.top/Article/details/gtugnbunlm.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvzqiivj.html

JS:   `Hello, ${name}!`
来源：http://dali.gzhubu.top/Article/details/gtndmcduef.html

TS:   `Hello, ${name}!`
来源：http://dali.gzhubu.top/Article/details/gtxruphhcl.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.nanxinkj.top/Article/details/gtevyjayge.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yueranfly.top/Article/details/gtxkqvfwfg.html

Ruby: "Hello, #{name}!"
来源：http://dali.havefunace.top/Article/details/gtrtpdckzi.html

C#:   $"Hello, {name}!"
来源：http://dali.yanxiufei.cn/Article/details/gtmefasrnd.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.meibo888.top/Article/details/gttgdshgxr.html

Py:   "第一行\n第二行"
来源：http://dali.316326.xyz/Article/details/gtirsoymzf.html

PHP:  "第一行\n第二行"
来源：http://dali.yueranfly.top/Article/details/gthonnnqsh.html

JS:   "第一行\n第二行"
来源：http://dali.gaohongyu789.top/Article/details/gtrcfgtsps.html

TS:   "第一行\n第二行"
来源：http://dali.ehwqpu.com/Article/details/gtdqskifrm.html

Java: "第一行\n第二行"
来源：http://dali.sxryk.cn/Article/details/gtgeputovn.html

Go:   "第一行\n第二行"
来源：http://dali.ppjwa.cn/Article/details/gtaqpwglpt.html

Ruby: "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gthiryhjue.html

C#:   "第一行\n第二行"
来源：http://dali.zhixingplan.top/Article/details/gtjdtsrlqp.html

[A14] 注释写法
来源：http://dali.yanxiufei.cn/Article/details/gtfesqeheq.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.ydzc1.top/Article/details/gticyhuqch.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.sysykeji.top/Article/details/gtdhfjuobx.html

JS:   // 单行；/* 多行 */
来源：http://dali.jlsjyb.cn/Article/details/gttdnkeczc.html

TS:   // 单行；/* 多行 */
来源：http://dali.xuanzx.com/Article/details/gtirryhojc.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.kuanghao11.cn/Article/details/gtgubavutq.html

Go:   // 单行；/* 多行 */
来源：http://dali.cdnleiting.top/Article/details/gtpkoojlhk.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hywenlv.cn/Article/details/gtgkfedydh.html


<!-- 参考信息 -->