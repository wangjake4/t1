代发 wailian999

[U87] JS：解构默认值
来源：http://dali.cashguo.top/Article/details/gtwltodvss.html

const { a = 1, b = 2 } = obj;
来源：http://dali.bjfxy.top/Article/details/gtfhwvhhmt.html

[U88] JS：对象展开合并
来源：http://dali.gotoacloud.top/Article/details/gtxsfjlsqj.html

{ ...a, ...b }
来源：http://dali.jinqigfzy.top/Article/details/gtnisercuy.html

[U89] JS：数组去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhzdkwuy.html

[...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gtkvaokijm.html

[U90] JS：数字数组排序
来源：http://dali.cqqwz.cn/Article/details/gtxzdgvgmb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jqgfzy.top/Article/details/gtevaftctr.html

[U91] JS：对象键值遍历
来源：http://dali.havefunace.top/Article/details/gtljsbaqet.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gzhubu.top/Article/details/gtfaruolyk.html

[U92] JS：深拷贝
来源：http://dali.guowangkeji.top/Article/details/gttzptapch.html

structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gtmgagfrfy.html

[U93] JS：模板字符串
来源：http://dali.shzxlz.cn/Article/details/gtceecqpyf.html

`共 ${n} 条`
来源：http://dali.ppjwa.cn/Article/details/gtwukuajgf.html

[U94] JS：箭头函数
来源：http://dali.gaohongyu789.top/Article/details/gtucfbwvfe.html

const double = x => x * 2;
来源：http://dali.shangyingyoupin.top/Article/details/gtllagydsu.html

[U95] JS：Promise 包装
来源：http://dali.chenlongwang.top/Article/details/gtrexjdjsc.html

new Promise((resolve, reject) => {})
来源：http://dali.jianghu66.top/Article/details/gtvskadttf.html

[U96] JS：async/await 与异常
来源：http://dali.fengsongda.top/Article/details/gtmzldljvk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gtpczqxuqq.html

[U97] JS：并发请求
来源：http://dali.yueranfly.top/Article/details/gtnszzybkd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gtobioiiig.html

[U98] JS：fetch 带 JSON
来源：http://dali.ehwqpu.com/Article/details/gtezaitddv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xziqi.cn/Article/details/gtgqctewmc.html

[U99] JS：事件监听
来源：http://dali.smart0.xyz/Article/details/gtocwsgzes.html

el.addEventListener("click", e => {})
来源：http://dali.zhoulong.xyz/Article/details/gtccvimuab.html

[U100] JS：DOM 查询
来源：http://dali.chenlongwang.top/Article/details/gtdmtmfvmf.html

document.querySelector(".item")
来源：http://dali.yuanzhike.top/Article/details/gtazskvjcs.html

[U101] JS：classList 操作
来源：http://dali.havefunace.top/Article/details/gtrightrje.html

el.classList.toggle("active")
来源：http://dali.cdnleiting.top/Article/details/gtnxpoabxj.html

[U102] JS：本地存储
来源：http://dali.tianlin.xyz/Article/details/gtiuezvbha.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdccfvnb.html

[U103] JS：定时器
来源：http://dali.mhx1999.top/Article/details/gtjvfqrkmv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ppjwa.cn/Article/details/gtbvqqhlvt.html

[U104] JS：防抖
来源：http://dali.redwolf501.top/Article/details/gtnqyaniof.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gtqusiqhoz.html

[U105] JS：节流
来源：http://dali.gaohongyu789.top/Article/details/gtlrlhbiok.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtxtcthqza.html

[U106] JS：日期格式化
来源：http://dali.yj20258888.top/Article/details/gtumdqaced.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.havefunace.top/Article/details/gtoeabfcul.html

[U107] JS：数字千分位
来源：http://dali.yj20258.top/Article/details/gtofcjllgw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xinyue.icu/Article/details/gtistmfnop.html

[U108] JS：随机整数
来源：http://dali.yj20258888.top/Article/details/gtubjxymuk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shuidangran.top/Article/details/gtqrlrfexe.html

[U109] JS：数组分组
来源：http://dali.cqqwz.cn/Article/details/gtngwyngsx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.pengpengdd.cyou/Article/details/gtlvwldzfe.html

[U110] JS：数组分块
来源：http://dali.zhongyouzk.top/Article/details/gtlwoszjmc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cdnleiting.top/Article/details/gtvvqicepc.html

[U111] JS：对象转 Map
来源：http://dali.xuanzx.com/Article/details/gtmnqhjsjy.html

new Map(Object.entries(obj))
来源：http://dali.hysaishi.cn/Article/details/gtbgwclvsm.html

[U112] JS：字符串补位
来源：http://dali.jiagoushi.top/Article/details/gtrdwjyple.html

"7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gtvmkfnmoo.html

[U113] JS：正则替换全部
来源：http://dali.c1oappe.top/Article/details/gtkxauldup.html

s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtbcqydybw.html

[U114] JS：JSON 深比较
来源：http://dali.quarkkingdee.top/Article/details/gtklhsswye.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.quarkkingdee.top/Article/details/gtqefhqfij.html

[U115] JS：生成 UUID
来源：http://dali.jinqigfzy.top/Article/details/gtqvlliyib.html

crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gtdlaqsraq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xuanzx.com/Article/details/gtudfpkmvy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.nwbrower.top/Article/details/gtzdustpqu.html

[U117] JS：单元测试
来源：http://dali.hongshengwenyu.top/Article/details/gtxrjbakro.html

npm i -D vitest;  npx vitest
来源：http://dali.aizwys.cn/Article/details/gtnmmbxnlf.html

[U118] JS：开发服务器
来源：http://dali.ydzc1.top/Article/details/gtibhfgqhd.html

npm i -D vite;  npx vite
来源：http://dali.zhiwuduotai.top/Article/details/gtizgudjwl.html

[U119] JS：生产构建
来源：http://dali.yongpay.top/Article/details/gtehkscvek.html

npx vite build
来源：http://dali.yanxiufei.cn/Article/details/gtlofbvyyz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zycfv.cn/Article/details/gteckgvwox.html

import.meta.env.VITE_API_URL
来源：http://dali.nanxinkj.top/Article/details/gtxidaeobe.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtpeqaxgna.html

统计汇总
来源：http://dali.cucudq.cn/Article/details/gtsvkwtmxt.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtybxehvhb.html

按语言统计（条）：
来源：http://dali.cheryme.top/Article/details/gtcuhomwbh.html

Python ......... 252
来源：http://dali.yuanzhike.top/Article/details/gtjdjcrbif.html

PHP ............ 252
来源：http://dali.zycfv.cn/Article/details/gtmtnqaxgt.html

JavaScript ..... 252
来源：http://dali.hnxiangtu.top/Article/details/gtpaltczgh.html

TypeScript ..... 212
来源：http://dali.jlsjyb.cn/Article/details/gtgkmabwrf.html

Java ........... 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijcunxdf.html

Go ............. 212
来源：http://dali.yangfankeji.com/Article/details/gtlmilffql.html

Ruby ........... 212
来源：http://dali.havefunace.top/Article/details/gtemfgsejn.html

C# ............. 212
来源：http://dali.cheryme.top/Article/details/gttzlfiiqd.html

C .............. 30
来源：http://dali.tanke756.top/Article/details/gtibwjlygj.html

C++ ............ 30
来源：http://dali.yanxiufei.cn/Article/details/gtwyfsstue.html

SQL ............ 90
来源：http://dali.chenlongwang.top/Article/details/gtoghcunme.html

Bash ........... 80
来源：http://dali.zhongyouzk.top/Article/details/gtvpnhldaa.html

Kotlin ......... 15
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfoqpbfwd.html

Swift .......... 15
来源：http://dali.yj20258888.top/Article/details/gtjyhtawwn.html

Lua ............ 10
来源：http://dali.cheryme.top/Article/details/gtyxucvduq.html

Perl ........... 10
来源：http://dali.9152youxi.cn/Article/details/gtflewokws.html

Scala .......... 10
来源：http://dali.yanxiufei.cn/Article/details/gtfczhmrbe.html

------------------------------------
来源：http://dali.jianghu66.top/Article/details/gttiugibjw.html

合计 ........... 2106 条
来源：http://dali.c1oappe.top/Article/details/gtrrrysenl.html

按章节统计：
来源：http://dali.aizwys.cn/Article/details/gtbxeotdsa.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.aibaodan.cn/Article/details/gtclkyhrst.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sweek.top/Article/details/gtdoqqdufj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfigfbson.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hfpthk.cn/Article/details/gtdddilarm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yueranfly.top/Article/details/gtrlqworld.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhengqikj.top/Article/details/gtnlungtyh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.redwolf501.top/Article/details/gtmokmeadt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nanxinkj.top/Article/details/gtikqaowrp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gtxlizliyz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jyoumei.cn/Article/details/gtymfzmlxa.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gtjetklnus.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gtbwkishkb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbzslgsz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.quarkkingdee.top/Article/details/gtzxiewvun.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shuidangran.top/Article/details/gtftuirprb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gtkyvwfcud.html

Q SQL 专题                              90
来源：http://dali.chenjidiqi.icu/Article/details/gtbhewpmfm.html

R Bash 专题                             80
来源：http://dali.ppjwa.cn/Article/details/gtfncphokm.html

S C / C++ 专题                          60
来源：http://dali.nwbrower.top/Article/details/gtjjamehlh.html

T 其他语言补充                          60
来源：http://dali.zhongyouzk.top/Article/details/gtjecovxdg.html

U 高频实用片段                         120
来源：http://dali.sufxvd.cn/Article/details/gtfvurtbiv.html

------------------------------------
来源：http://dali.yj20258.top/Article/details/gtlgexkbks.html

合计                                  2106 条
来源：http://dali.nanxinkj.top/Article/details/gtggzrgypt.html

--------------------------------------------------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gtejluysfn.html

使用提醒
来源：http://dali.pycfn.com/Article/details/gthirukwhs.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtjkxkucpo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ehwqpu.com/Article/details/gtlgowtitz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.daria6918.cn/Article/details/gtlctogmuj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhongyouzk.top/Article/details/gtiukcnajw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zycfv.cn/Article/details/gtycwcfkpy.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexuzgued.html

—— 文件结束 ——
来源：http://dali.zhiwuduotai.top/Article/details/gtpezvgasm.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtiiyupwjx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.fzhhl.top/Article/details/gttqlutlry.html

Common Programming Examples Cheat Book
来源：http://dali.wangdashe.top/Article/details/gtbflzzyec.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtdzjqnqah.html

【收录内容】
来源：http://dali.nanxuanxn.top/Article/details/gtvwimqgps.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.aizwys.cn/Article/details/gtbcdouqah.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.0kj1m.cn/Article/details/gtejayyigj.html

SQL · Bash · C · C++
来源：http://dali.jinqigufen.top/Article/details/gtnldeyowp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yueranfly.top/Article/details/gtgzvjqbnr.html

【使用说明】
来源：http://dali.xuetiantiany.cn/Article/details/gtjahepvvy.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.aizwys.cn/Article/details/gthxyltkrh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgwfqqpfi.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hongshengwenyu.top/Article/details/gtqjcrcdyr.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.cdnleiting.top/Article/details/gtltzzfyyx.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xziqi.cn/Article/details/gtypblocsp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.havefunace.top/Article/details/gtrqxdmmex.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.smart0.xyz/Article/details/gtigbxwvpu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yj20258.top/Article/details/gtcgftwupf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhongyouzk.top/Article/details/gtsnvywmbx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ppjwa.cn/Article/details/gtzvipdoeh.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.aibaodan.cn/Article/details/gtowbouioe.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.tanke756.top/Article/details/gtkdlojgjd.html

【文件统计】
来源：http://dali.daria6918.cn/Article/details/gtbgiohzrv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.havefunace.top/Article/details/gtmuuaetgs.html

--------------------------------------------------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gtosfachee.html

目  录
来源：http://dali.fzhhl.top/Article/details/gteenvrtrb.html

--------------------------------------------------------------------------------
来源：http://dali.yonumen.top/Article/details/gtlitezjsh.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hammf.cn/Article/details/gtzakihjqq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtoxwkckdr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jqgufenzy.top/Article/details/gtcysghhtc.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.meibo888.top/Article/details/gtkrbvqtlu.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.daria6918.cn/Article/details/gtlaqzaezm.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hysaishi.cn/Article/details/gtljkmwdpj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtmfxwfavv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hywenlv.cn/Article/details/gtgftvnpxw.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gtkipaowry.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jqgfzy.top/Article/details/gtqussdwtg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.0kj1m.cn/Article/details/gtmjtugndg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtfgugdada.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtlqrzcpjs.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.sxryk.cn/Article/details/gtngmqusht.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.aibaodan.cn/Article/details/gtkicyswsm.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gtnmfhzpbf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.gzhubu.top/Article/details/gtcxsrfqma.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.sufxvd.cn/Article/details/gtpzclnljy.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hfpthk.cn/Article/details/gtuxxkmqgi.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hywenlv.cn/Article/details/gtxfebmogf.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xinyue.icu/Article/details/gtvoiqudag.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtyylctcmw.html

A. 基础语法与类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjadjykxc.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtahouhggb.html

[A01] Hello World
来源：http://dali.wangdashe.top/Article/details/gtmipjusdn.html

Py:   print("Hello, World!")
来源：http://dali.9152youxi.cn/Article/details/gttvbnbspr.html

PHP:  echo "Hello, World!";
来源：http://dali.fengsongda.top/Article/details/gtpjlfaqph.html

JS:   console.log("Hello, World!");
来源：http://dali.cheryme.top/Article/details/gtcqcnjdzl.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.vqdsnc.cn/Article/details/gtuuillfzx.html

Java: System.out.println("Hello, World!");
来源：http://dali.aizwys.cn/Article/details/gtrhjvgdmu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjcpnafq.html

Ruby: puts "Hello, World!"
来源：http://dali.aibaodan.cn/Article/details/gtybnrjiae.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.guannengcc.top/Article/details/gtovfsszpp.html

[A02] 变量声明与赋值
来源：http://dali.pengpengdd.cyou/Article/details/gtasrrmnog.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shangyingyoupin.top/Article/details/gtytwynnmq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.birdmap.top/Article/details/gtsgmzqctu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cheryme.top/Article/details/gtpieirxcw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.birdmap.top/Article/details/gtdxuuqydo.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zdqjudy.top/Article/details/gtlckcglcf.html

Go:   name := "Alex"; age := 20
来源：http://dali.shzxlz.cn/Article/details/gteyqvnydc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.haohaochexian.top/Article/details/gtsstgjjtq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hfpthk.cn/Article/details/gtjwmmumgp.html

[A03] 常量定义
来源：http://dali.hywenlv.cn/Article/details/gtqwumdgjo.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hammf.cn/Article/details/gtswyptquw.html

PHP:  const PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtedfcokkp.html

JS:   const PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtlfvqmotn.html

TS:   const PI: number = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gtrpjoqivh.html

Java: static final double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtrwwfxmos.html

Go:   const PI = 3.14159
来源：http://dali.bjfxy.top/Article/details/gtimcutldl.html

Ruby: PI = 3.14159
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmcyeaehh.html

C#:   const double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtyzpyvosl.html

[A04] 判断变量类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyzlflqn.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.iojbl.cn/Article/details/gtmvpjqzpd.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.chenjidiqi.icu/Article/details/gthunbdwop.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilmnwqyi.html

TS:   typeof x; x instanceof Date
来源：http://dali.jianghu66.top/Article/details/gtzemqwmdn.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.sufxvd.cn/Article/details/gthakgupqn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.0kj1m.cn/Article/details/gtcdmhcsuf.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zdqjudy.top/Article/details/gtjbncywsv.html

C#:   x.GetType().Name; x is int
来源：http://dali.sweek.top/Article/details/gtztphyocc.html

[A05] 整数除法与取模
来源：http://dali.hongshengwenyu.top/Article/details/gtpddeojoh.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.birdmap.top/Article/details/gtyeccwcob.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gtdxtsiqkt.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gthzeauhjq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gtkitzfxed.html

Java: 7 / 2; 7 % 2
来源：http://dali.bjfxy.top/Article/details/gtupxxrumv.html

Go:   7 / 2; 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbuayedm.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gtfzrxnpod.html

C#:   7 / 2; 7 % 2
来源：http://dali.yonumen.top/Article/details/gtjyfaqjmh.html

[A06] 字符串转数字
来源：http://dali.hysaishi.cn/Article/details/gtvmftsash.html

Py:   int("42"); float("3.14")
来源：http://dali.jyoumei.cn/Article/details/gtgajvfxgr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhixingplan.top/Article/details/gtratovdzr.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jqgufenzy.top/Article/details/gtzdebnflq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.sxryk.cn/Article/details/gtgwqiboxi.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zdqjudy.top/Article/details/gtaelfjeso.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.bjfxy.top/Article/details/gtmqvrmeur.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yvedp.cn/Article/details/gtapikoaok.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.birdmap.top/Article/details/gtclfrxhev.html

[A07] 数字转字符串
来源：http://dali.jlsjyb.cn/Article/details/gtqrutoyxx.html

Py:   str(42)
来源：http://dali.dianchejie.cn/Article/details/gtuqzlnyxi.html

PHP:  (string) 42; strval(42)
来源：http://dali.guannengcc.top/Article/details/gtarvkaqgo.html

JS:   String(42); (42).toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjaanhjy.html

TS:   String(42)
来源：http://dali.feifeiyinyue.top/Article/details/gtqrruhrdv.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.mhx1999.top/Article/details/gtjfcdruba.html

Go:   strconv.Itoa(42)
来源：http://dali.feifeiyinyue.top/Article/details/gtjxwvihdn.html

Ruby: 42.to_s
来源：http://dali.hfpthk.cn/Article/details/gtoqegnyhn.html

C#:   42.ToString()
来源：http://dali.yuanzhike.top/Article/details/gtvdamkmxq.html

[A08] 取整与四舍五入
来源：http://dali.bjfxy.top/Article/details/gtwxkoxvfp.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jinghuilouyu.cn/Article/details/gtowkwqodg.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.gotoacloud.top/Article/details/gtjbtmgbiq.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.cashguo.top/Article/details/gtxsdcrguw.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.chenzaomai.com/Article/details/gtwxyqgpnw.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.bjfxy.top/Article/details/gtjzjictam.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yanxiufei.cn/Article/details/gtzrulhivd.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.cheryme.top/Article/details/gtcyclyvng.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcamllhpj.html

[A09] 绝对值与最大最小值
来源：http://dali.smart0.xyz/Article/details/gtgkvmxpgq.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.birdmap.top/Article/details/gtvditjfsm.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtgzyhcexz.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtqvzhxqfh.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtihuevdjm.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.pycfn.com/Article/details/gtpxezsgxb.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.chenzaomai.com/Article/details/gtdqcdbmtg.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.dashuyun.cn/Article/details/gtkvtzbgzc.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtmfulzqij.html

[A10] 生成随机数
来源：http://dali.cucudq.cn/Article/details/gtyfmbwszv.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhixingplan.top/Article/details/gtawymxtwp.html

PHP:  random_int(1, 100);
来源：http://dali.tanke756.top/Article/details/gtheezpvpf.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.pengpengdd.cyou/Article/details/gtmrbifkqs.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.haohaochexian.top/Article/details/gtyyrveude.html

Java: new Random().nextInt(100) + 1
来源：http://dali.redwolf501.top/Article/details/gtzmwyskpc.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgezhcvlh.html

Ruby: rand(1..100)
来源：http://dali.dianchejie.cn/Article/details/gtqnqkgqnb.html

C#:   new Random().Next(1, 101)
来源：http://dali.jiagoushi.top/Article/details/gtaqshrlnv.html

[A11] 条件表达式（三元）
来源：http://dali.mhx1999.top/Article/details/gtscpcbwyx.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.c1oappe.top/Article/details/gtoebjtwoh.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.nwbrower.top/Article/details/gtoqqpeeay.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhixingplan.top/Article/details/gtvfvedocw.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.hnxiangtu.top/Article/details/gtnqrgpcog.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.gzhubu.top/Article/details/gtxyrrxtzw.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.xuetiantiany.cn/Article/details/gtkwclekyi.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zdqjudy.top/Article/details/gtinaomduo.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jiagoushi.top/Article/details/gtaqgedvgy.html

[A12] 字符串插值 / 格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtmtthilrf.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.cdnleiting.top/Article/details/gtrntmavlh.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtixsoyqii.html

JS:   `Hello, ${name}!`
来源：http://dali.jyoumei.cn/Article/details/gtbmxjwcrr.html

TS:   `Hello, ${name}!`
来源：http://dali.sysykeji.top/Article/details/gtbrqpuwwp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jinghuilouyu.cn/Article/details/gthnbjzjtv.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.haohaochexian.top/Article/details/gtgmdquofl.html

Ruby: "Hello, #{name}!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqyfpyrl.html

C#:   $"Hello, {name}!"
来源：http://dali.svipenyu.cn/Article/details/gtfksidpcf.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.hywenlv.cn/Article/details/gtvipuzybp.html

Py:   "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwsyxqks.html

PHP:  "第一行\n第二行"
来源：http://dali.daria6918.cn/Article/details/gtgfmeyqxh.html

JS:   "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gtpynsbezp.html

TS:   "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gtxedolvdp.html

Java: "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gtbaxbnxcj.html

Go:   "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gtocjalpya.html

Ruby: "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gtvultwhqx.html

C#:   "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxnzwpgs.html

[A14] 注释写法
来源：http://dali.yanxiufei.cn/Article/details/gtxmqmpxtj.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhengqikj.top/Article/details/gtacsjdklq.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.daria6918.cn/Article/details/gtcpwzbkgh.html

JS:   // 单行；/* 多行 */
来源：http://dali.nanxuanxn.top/Article/details/gtltexhpgc.html

TS:   // 单行；/* 多行 */
来源：http://dali.cqqwz.cn/Article/details/gtpvgjrpkv.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.ivvv.top/Article/details/gtonjtmhor.html

Go:   // 单行；/* 多行 */
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdgtbqqx.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.xinyue.icu/Article/details/gtplnhtggx.html


<!-- 参考信息 -->