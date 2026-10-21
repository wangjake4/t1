代发 wailian999

[U85] JS：可选链
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmphdfiqj.html

a?.b?.c
来源：http://dali.shanyushiyangtech.top/Article/details/gtblvgldou.html

[U86] JS：空值合并
来源：http://dali.guowangkeji.top/Article/details/gtnhmvlpcy.html

a ?? b
来源：http://dali.tanke756.top/Article/details/gtpxilfuyf.html

[U87] JS：解构默认值
来源：http://dali.yj20258.top/Article/details/gttkyfcbpv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shangyingyoupin.top/Article/details/gtctphvntj.html

[U88] JS：对象展开合并
来源：http://dali.shangyingyoupin.top/Article/details/gtgdexrwnh.html

{ ...a, ...b }
来源：http://dali.wangshuangyany.cn/Article/details/gtpzjwoyid.html

[U89] JS：数组去重
来源：http://dali.xuanzx.com/Article/details/gtjwgqkzlq.html

[...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gtzhjdacho.html

[U90] JS：数字数组排序
来源：http://dali.guannengcc.top/Article/details/gthptejrkh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gtarvjcsqj.html

[U91] JS：对象键值遍历
来源：http://dali.jqgufenzy.top/Article/details/gtouzpdxns.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.bjfxy.top/Article/details/gtuokvrtjy.html

[U92] JS：深拷贝
来源：http://dali.jianghu66.top/Article/details/gtvafaimem.html

structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtmrvxipjh.html

[U93] JS：模板字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtxytbcjeg.html

`共 ${n} 条`
来源：http://dali.xuanzx.com/Article/details/gtcqanwgwh.html

[U94] JS：箭头函数
来源：http://dali.wangdashe.top/Article/details/gtoahbtjeo.html

const double = x => x * 2;
来源：http://dali.chenlongwang.top/Article/details/gtgvvosgqi.html

[U95] JS：Promise 包装
来源：http://dali.chenjidiqi.icu/Article/details/gtwawzbfkj.html

new Promise((resolve, reject) => {})
来源：http://dali.xziqi.cn/Article/details/gtkebgyzoq.html

[U96] JS：async/await 与异常
来源：http://dali.cdnleiting.top/Article/details/gtpfbzklxs.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gtsjsejksj.html

[U97] JS：并发请求
来源：http://dali.aizwys.cn/Article/details/gtcasjogze.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtqfwmfjey.html

[U98] JS：fetch 带 JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtvlgszjqv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.vqdsnc.cn/Article/details/gtuwonrrdg.html

[U99] JS：事件监听
来源：http://dali.zdqjudy.top/Article/details/gtldsvbpjy.html

el.addEventListener("click", e => {})
来源：http://dali.xinyue.icu/Article/details/gtfsvvjdvr.html

[U100] JS：DOM 查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtonwudgem.html

document.querySelector(".item")
来源：http://dali.jinqigufen.top/Article/details/gtuqfzvovb.html

[U101] JS：classList 操作
来源：http://dali.jianghu66.top/Article/details/gtyggkxroo.html

el.classList.toggle("active")
来源：http://dali.wangshuangyany.cn/Article/details/gtxcguvzwt.html

[U102] JS：本地存储
来源：http://dali.wangdashe.top/Article/details/gtmyqktoia.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shuidangran.top/Article/details/gtwcokedpm.html

[U103] JS：定时器
来源：http://dali.jqgufenzy.top/Article/details/gttoildazy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.kuanghao11.cn/Article/details/gtjetpakro.html

[U104] JS：防抖
来源：http://dali.zhongyouzk.top/Article/details/gtqyuvqavo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gtdauhykwc.html

[U105] JS：节流
来源：http://dali.yangfankeji.com/Article/details/gtpxvzmevw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.chenzaomai.com/Article/details/gtkhmmgikp.html

[U106] JS：日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtqfegbuxe.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhoulong.xyz/Article/details/gtmnumofhc.html

[U107] JS：数字千分位
来源：http://dali.daxiang520.top/Article/details/gtjvsbfrio.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shzxlz.cn/Article/details/gtscrsedfh.html

[U108] JS：随机整数
来源：http://dali.9152youxi.cn/Article/details/gtgihhrfcq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ppjwa.cn/Article/details/gtbrxdjard.html

[U109] JS：数组分组
来源：http://dali.hongshengwenyu.top/Article/details/gtewsmrult.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cheryme.top/Article/details/gttosqaepu.html

[U110] JS：数组分块
来源：http://dali.zdqjudy.top/Article/details/gtlfgtvqme.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.9152youxi.cn/Article/details/gtzyhkopef.html

[U111] JS：对象转 Map
来源：http://dali.zhengqikj.top/Article/details/gtsokhhajj.html

new Map(Object.entries(obj))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxmtbvuh.html

[U112] JS：字符串补位
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmaonqzr.html

"7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gtykzbsxry.html

[U113] JS：正则替换全部
来源：http://dali.9152youxi.cn/Article/details/gtqqhcrsvp.html

s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtidultluo.html

[U114] JS：JSON 深比较
来源：http://dali.vqdsnc.cn/Article/details/gtzhiczhlr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jyoumei.cn/Article/details/gtlzyxukrd.html

[U115] JS：生成 UUID
来源：http://dali.sweek.top/Article/details/gtfpfpjtrb.html

crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gteayviprv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.c1oappe.top/Article/details/gtnmhaadqz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yuxming.cn/Article/details/gtzssktpat.html

[U117] JS：单元测试
来源：http://dali.sxryk.cn/Article/details/gtuttklcbb.html

npm i -D vitest;  npx vitest
来源：http://dali.wangdashe.top/Article/details/gtxwwcyzev.html

[U118] JS：开发服务器
来源：http://dali.cheryme.top/Article/details/gtulnhxuxd.html

npm i -D vite;  npx vite
来源：http://dali.nanxuanxn.top/Article/details/gtofszmvwl.html

[U119] JS：生产构建
来源：http://dali.guowangkeji.top/Article/details/gthcvbidrg.html

npx vite build
来源：http://dali.jiagoushi.top/Article/details/gtmmtxzpke.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yanxiufei.cn/Article/details/gtvnsuqiud.html

import.meta.env.VITE_API_URL
来源：http://dali.cdnleiting.top/Article/details/gtvbabfulg.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtbaqtlhwe.html

统计汇总
来源：http://dali.yj20258888.top/Article/details/gtzoapywia.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtwsuhissf.html

按语言统计（条）：
来源：http://dali.0kj1m.cn/Article/details/gtwylerhuo.html

Python ......... 252
来源：http://dali.daria6918.cn/Article/details/gtnyrmiude.html

PHP ............ 252
来源：http://dali.cqqwz.cn/Article/details/gtbmkuesot.html

JavaScript ..... 252
来源：http://dali.zdqjudy.top/Article/details/gttovwsuzn.html

TypeScript ..... 212
来源：http://dali.c1oappe.top/Article/details/gtagikgmqj.html

Java ........... 212
来源：http://dali.9152youxi.cn/Article/details/gtidwrtkfe.html

Go ............. 212
来源：http://dali.chenlongwang.top/Article/details/gtkvzmhsoi.html

Ruby ........... 212
来源：http://dali.hnxiangtu.top/Article/details/gtmckmjpgr.html

C# ............. 212
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvjcuine.html

C .............. 30
来源：http://dali.yvedp.cn/Article/details/gtfsbnbgyw.html

C++ ............ 30
来源：http://dali.yj20258888.top/Article/details/gtznkzjoun.html

SQL ............ 90
来源：http://dali.shzxlz.cn/Article/details/gtlwhmyqex.html

Bash ........... 80
来源：http://dali.ehwqpu.com/Article/details/gtjroqewyg.html

Kotlin ......... 15
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrzexrbu.html

Swift .......... 15
来源：http://dali.nanxuanxn.top/Article/details/gtwmsxkshm.html

Lua ............ 10
来源：http://dali.yueranfly.top/Article/details/gtynqjvzby.html

Perl ........... 10
来源：http://dali.xylfe.cn/Article/details/gtalhwkccs.html

Scala .......... 10
来源：http://dali.xziqi.cn/Article/details/gtathgtgei.html

------------------------------------
来源：http://dali.gzhubu.top/Article/details/gtkolsnchw.html

合计 ........... 2106 条
来源：http://dali.sufxvd.cn/Article/details/gtrikwqzoc.html

按章节统计：
来源：http://dali.xylfe.cn/Article/details/gtorepqyfc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gotoacloud.top/Article/details/gtcyiktqfn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.quarkkingdee.top/Article/details/gtzdvthomd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cqqwz.cn/Article/details/gtfognwdwa.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.iojbl.cn/Article/details/gtflggmhqq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwahmxybd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shzxlz.cn/Article/details/gthxsrawve.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.cucudq.cn/Article/details/gtovdkoynm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cucudq.cn/Article/details/gtttayjwei.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gtabjoskcx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shzxlz.cn/Article/details/gtcelykzzp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfmmzovu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gtbxpktsco.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gtxiyvjjcd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvriyldg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.wangshuangyany.cn/Article/details/gthqmuyhle.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gtbclgdzdy.html

Q SQL 专题                              90
来源：http://dali.hfpthk.cn/Article/details/gtxmytwdki.html

R Bash 专题                             80
来源：http://dali.snrcjt.cn/Article/details/gtjnmzovrm.html

S C / C++ 专题                          60
来源：http://dali.zhiwuduotai.top/Article/details/gthjxryeop.html

T 其他语言补充                          60
来源：http://dali.xziqi.cn/Article/details/gtmtcfloyf.html

U 高频实用片段                         120
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdaebccl.html

------------------------------------
来源：http://dali.guannengcc.top/Article/details/gtybvleomn.html

合计                                  2106 条
来源：http://dali.tian-w.cn/Article/details/gtcbznmrpt.html

--------------------------------------------------------------------------------
来源：http://dali.havefunace.top/Article/details/gtrcntogxy.html

使用提醒
来源：http://dali.zhoulong.xyz/Article/details/gtmhzpnngm.html

--------------------------------------------------------------------------------
来源：http://dali.smart0.xyz/Article/details/gtbxmgdqtn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.gaohongyu789.top/Article/details/gtcxptwysq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jqgfzy.top/Article/details/gtbxwxuper.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yanxiufei.cn/Article/details/gtxyhvvseq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.smart0.xyz/Article/details/gtbtvwcwcj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.bjfxy.top/Article/details/gtwbuscagy.html

—— 文件结束 ——
来源：http://dali.chenlongwang.top/Article/details/gtxocwpzii.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtvuveyatd.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppnicepg.html

Common Programming Examples Cheat Book
来源：http://dali.shzxlz.cn/Article/details/gtuxtpoife.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtqaccmovg.html

【收录内容】
来源：http://dali.nanxinkj.top/Article/details/gtoeaohesj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.tian-w.cn/Article/details/gtputvpjyu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xylfe.cn/Article/details/gtengajfdr.html

SQL · Bash · C · C++
来源：http://dali.hfpthk.cn/Article/details/gtckyviddr.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yanxiufei.cn/Article/details/gtsndqovyc.html

【使用说明】
来源：http://dali.andypj.xyz/Article/details/gtyanwekcu.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdtkgzpe.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.andypj.xyz/Article/details/gtiwmugrqv.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hongshengwenyu.top/Article/details/gtowjsphbj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jiagoushi.top/Article/details/gtnmxmdkdl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.cheryme.top/Article/details/gtmbltdyvd.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.quarkkingdee.top/Article/details/gterbfciaf.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.vqdsnc.cn/Article/details/gtcepuwwqt.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yonumen.top/Article/details/gtqrwggluj.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.sxryk.cn/Article/details/gtaabcmeiz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xylfe.cn/Article/details/gttpimbdhc.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ppjwa.cn/Article/details/gtmcfnfuni.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yj20258888.top/Article/details/gtbswyzxxf.html

【文件统计】
来源：http://dali.xylfe.cn/Article/details/gtlsywxkya.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.aibaodan.cn/Article/details/gtmdaxjbxk.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gtchobngoy.html

目  录
来源：http://dali.dianchejie.cn/Article/details/gtiqqphkfy.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gtnlyxyzwx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.chenlongwang.top/Article/details/gtssbcgdeh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.pycfn.com/Article/details/gtnqbxpwti.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jyoumei.cn/Article/details/gtgtzzzqpo.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gtfajkqocp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jqgfzy.top/Article/details/gtmiximtzf.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.birdmap.top/Article/details/gtfcvmyxnp.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cdnleiting.top/Article/details/gtrmfhlabz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtlaxsyqmr.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtklootrom.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.gogol.net.cn/Article/details/gtpexzbgwb.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gtdcwlcsav.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtgcopsovp.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.svipenyu.cn/Article/details/gtbhyyxqqz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.316326.xyz/Article/details/gtmyjdwmxy.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jlsjyb.cn/Article/details/gtxiqoweaw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yangfankeji.com/Article/details/gtmpjnthnt.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hysaishi.cn/Article/details/gtamvmauqe.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yj20258.top/Article/details/gtghleexbn.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yvedp.cn/Article/details/gtxaxpolcy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daria6918.cn/Article/details/gtiffttcon.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.pycfn.com/Article/details/gtcogdufih.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtsijcsqym.html

A. 基础语法与类型
来源：http://dali.xylfe.cn/Article/details/gtrdioovxx.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtmsjybmvy.html

[A01] Hello World
来源：http://dali.sweek.top/Article/details/gtcofrkjpv.html

Py:   print("Hello, World!")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqszxlve.html

PHP:  echo "Hello, World!";
来源：http://dali.yuanzhike.top/Article/details/gtprfpchvf.html

JS:   console.log("Hello, World!");
来源：http://dali.nanxinkj.top/Article/details/gtzzhxpyqq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhixingplan.top/Article/details/gtdymgukja.html

Java: System.out.println("Hello, World!");
来源：http://dali.vqdsnc.cn/Article/details/gtnxrutgbo.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.wangshuangyany.cn/Article/details/gtmpnldhvl.html

Ruby: puts "Hello, World!"
来源：http://dali.zhoulong.xyz/Article/details/gtslisohtq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.sxryk.cn/Article/details/gtarikcxiz.html

[A02] 变量声明与赋值
来源：http://dali.sweek.top/Article/details/gtqgonjmnm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hnxiangtu.top/Article/details/gtkamimqef.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.cqqwz.cn/Article/details/gteegzujhy.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yueranfly.top/Article/details/gtshujvvqy.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.fengsongda.top/Article/details/gtubgiyjil.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.cqqwz.cn/Article/details/gtpibuztuf.html

Go:   name := "Alex"; age := 20
来源：http://dali.mhx1999.top/Article/details/gtzikghihi.html

Ruby: name = "Alex"; age = 20
来源：http://dali.ivvv.top/Article/details/gtcqyrxmvv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.shzxlz.cn/Article/details/gtgxwwpyti.html

[A03] 常量定义
来源：http://dali.cdnleiting.top/Article/details/gtyrhticmz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shanyushiyangtech.top/Article/details/gtevzooeqr.html

PHP:  const PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtlrmzazdx.html

JS:   const PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gttrcrgkre.html

TS:   const PI: number = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtnaecyzbe.html

Java: static final double PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtsoebdenk.html

Go:   const PI = 3.14159
来源：http://dali.yuanzhike.top/Article/details/gtmpomvyul.html

Ruby: PI = 3.14159
来源：http://dali.gotoacloud.top/Article/details/gtrzkrutux.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtvzgjqjil.html

[A04] 判断变量类型
来源：http://dali.jqgufenzy.top/Article/details/gtznrqiobe.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yuxming.cn/Article/details/gtgwwhusds.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cucudq.cn/Article/details/gtggmzqzzz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqwdgmgy.html

TS:   typeof x; x instanceof Date
来源：http://dali.snrcjt.cn/Article/details/gtyyibsupw.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.bjfxy.top/Article/details/gtiupqpwoz.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.dianchejie.cn/Article/details/gthwwskfub.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.wangdashe.top/Article/details/gtduahdrfc.html

C#:   x.GetType().Name; x is int
来源：http://dali.cashguo.top/Article/details/gtnfvbckwc.html

[A05] 整数除法与取模
来源：http://dali.snrcjt.cn/Article/details/gtxiuyopbu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.andypj.xyz/Article/details/gtrnulxarw.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gtuirumqnk.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gtqjshanfd.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gtjuebyykh.html

Java: 7 / 2; 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtiosowspy.html

Go:   7 / 2; 7 % 2
来源：http://dali.sysykeji.top/Article/details/gtqsqjlquc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ybcxt.top/Article/details/gtgxgnwsru.html

C#:   7 / 2; 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtnxkauqpk.html

[A06] 字符串转数字
来源：http://dali.hnqzz.top/Article/details/gtmfljfzxm.html

Py:   int("42"); float("3.14")
来源：http://dali.cdnleiting.top/Article/details/gtojqpghtf.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yonumen.top/Article/details/gtjiedvxrk.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ybcxt.top/Article/details/gtgfddtwys.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hammf.cn/Article/details/gtirymbcns.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.redwolf501.top/Article/details/gtwqwqkshd.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.sufxvd.cn/Article/details/gtnkvyihvw.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yuanzhike.top/Article/details/gtubwxohra.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.sweek.top/Article/details/gtggcmiqlt.html

[A07] 数字转字符串
来源：http://dali.jqgfzy.top/Article/details/gtxqqfqggk.html

Py:   str(42)
来源：http://dali.havefunace.top/Article/details/gtzferbjeg.html

PHP:  (string) 42; strval(42)
来源：http://dali.ybcxt.top/Article/details/gtusmhyqdq.html

JS:   String(42); (42).toString()
来源：http://dali.nanxuanxn.top/Article/details/gtjswmcawd.html

TS:   String(42)
来源：http://dali.cashguo.top/Article/details/gtkskcwdpw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.quarkkingdee.top/Article/details/gtznvcdckl.html

Go:   strconv.Itoa(42)
来源：http://dali.9152youxi.cn/Article/details/gttzzbprmb.html

Ruby: 42.to_s
来源：http://dali.xuetiantiany.cn/Article/details/gthhazilpb.html

C#:   42.ToString()
来源：http://dali.quarkkingdee.top/Article/details/gtnmpdtkgo.html

[A08] 取整与四舍五入
来源：http://dali.shuidangran.top/Article/details/gttebwbqek.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gtfwnpzewq.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.shuidangran.top/Article/details/gtusxqpdkj.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yj20258888.top/Article/details/gtfteebiqs.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yj20258888.top/Article/details/gtpcbkfptz.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhiwuduotai.top/Article/details/gtchctcuvp.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.gaohongyu789.top/Article/details/gtyplymsjb.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhoulong.xyz/Article/details/gtikbguwnm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.pycfn.com/Article/details/gtikzsvxqu.html

[A09] 绝对值与最大最小值
来源：http://dali.hnxiangtu.top/Article/details/gttoiarwif.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sysykeji.top/Article/details/gtcmtpccoa.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.c1oappe.top/Article/details/gttfnmencz.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gtfrekctqb.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gtquocoeva.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.tanke756.top/Article/details/gtaolspflr.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.gotoacloud.top/Article/details/gtietripql.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yueranfly.top/Article/details/gtxvhiorau.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gtkrdwalsl.html

[A10] 生成随机数
来源：http://dali.daria6918.cn/Article/details/gtcztadsns.html

Py:   import random; random.randint(1, 100)
来源：http://dali.aizwys.cn/Article/details/gtocmzeokf.html

PHP:  random_int(1, 100);
来源：http://dali.havefunace.top/Article/details/gtpynotzoh.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.pycfn.com/Article/details/gthnosdrjv.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jyoumei.cn/Article/details/gtromascfu.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gtiblvbhpy.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzuapwbb.html

Ruby: rand(1..100)
来源：http://dali.cucudq.cn/Article/details/gttjqkykpj.html

C#:   new Random().Next(1, 101)
来源：http://dali.yangfankeji.com/Article/details/gtowxclmbs.html

[A11] 条件表达式（三元）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjbmbtnj.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jlsjyb.cn/Article/details/gtvojzfrvb.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hnqzz.top/Article/details/gtgmwbfcyq.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gtplrxtebl.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.snrcjt.cn/Article/details/gtcxkishcj.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yvedp.cn/Article/details/gtttyocyfv.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.daxiang520.top/Article/details/gtzeqdthgq.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yuanzhike.top/Article/details/gtxrtexpmh.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.nanxinkj.top/Article/details/gtlztfyhsk.html

[A12] 字符串插值 / 格式化
来源：http://dali.yuxming.cn/Article/details/gtxcxpyacp.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.shuidangran.top/Article/details/gtjvnhfhjk.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.hysaishi.cn/Article/details/gtgnyjzjgv.html

JS:   `Hello, ${name}!`
来源：http://dali.nwbrower.top/Article/details/gtjubcgqir.html

TS:   `Hello, ${name}!`
来源：http://dali.pengpengdd.cyou/Article/details/gtllbhwjyf.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xziqi.cn/Article/details/gtssvkbvhj.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmipnjwf.html

Ruby: "Hello, #{name}!"
来源：http://dali.shangyingyoupin.top/Article/details/gtruppadtn.html

C#:   $"Hello, {name}!"
来源：http://dali.tianlin.xyz/Article/details/gttxzkcxkg.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.xziqi.cn/Article/details/gtawvlgazd.html

Py:   "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gtpxnpqvfq.html

PHP:  "第一行\n第二行"
来源：http://dali.yvedp.cn/Article/details/gtkbdolszz.html

JS:   "第一行\n第二行"
来源：http://dali.zhoulong.xyz/Article/details/gtzmlupqmm.html

TS:   "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gtneeadsax.html

Java: "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gtlcucpujq.html

Go:   "第一行\n第二行"
来源：http://dali.tanke756.top/Article/details/gtcnaqyexq.html

Ruby: "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gtjzintsoa.html

C#:   "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gtyngkwoht.html

[A14] 注释写法
来源：http://dali.sufxvd.cn/Article/details/gtehlkhmez.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.hfpthk.cn/Article/details/gtxsvuvjby.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yvedp.cn/Article/details/gtnucmhqkn.html

JS:   // 单行；/* 多行 */
来源：http://dali.jqgfzy.top/Article/details/gtvtlpopit.html


<!-- 参考信息 -->