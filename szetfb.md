代发 wailian999

[U95] JS：Promise 包装
来源：http://dali.yvedp.cn/Article/details/gtqtmzqitc.html

new Promise((resolve, reject) => {})
来源：http://dali.chenjidiqi.icu/Article/details/gtyaeigcld.html

[U96] JS：async/await 与异常
来源：http://dali.dianchejie.cn/Article/details/gtuzkvxaru.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtndnkqfsv.html

[U97] JS：并发请求
来源：http://dali.yueranfly.top/Article/details/gttrhrrrgh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gtkhuoekrf.html

[U98] JS：fetch 带 JSON
来源：http://dali.shzxlz.cn/Article/details/gtosgwmgcv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.ydzc1.top/Article/details/gtbgrlwzen.html

[U99] JS：事件监听
来源：http://dali.feifeiyinyue.top/Article/details/gtvpwxguon.html

el.addEventListener("click", e => {})
来源：http://dali.jiagoushi.top/Article/details/gtcfzmivyw.html

[U100] JS：DOM 查询
来源：http://dali.daxiang520.top/Article/details/gthweaqguw.html

document.querySelector(".item")
来源：http://dali.cheryme.top/Article/details/gtvsmjmhll.html

[U101] JS：classList 操作
来源：http://dali.jyoumei.cn/Article/details/gthviovwjk.html

el.classList.toggle("active")
来源：http://dali.aibaodan.cn/Article/details/gtsnfahmre.html

[U102] JS：本地存储
来源：http://dali.shuidangran.top/Article/details/gtyubljxbc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.mhx1999.top/Article/details/gtmhlnqpov.html

[U103] JS：定时器
来源：http://dali.tian-w.cn/Article/details/gtfiyvttms.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xylfe.cn/Article/details/gtecoxdxvr.html

[U104] JS：防抖
来源：http://dali.jyoumei.cn/Article/details/gtpzmgotyd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtsnavyogj.html

[U105] JS：节流
来源：http://dali.gzhubu.top/Article/details/gthngtebjv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.chenzaomai.com/Article/details/gttuqvvtms.html

[U106] JS：日期格式化
来源：http://dali.zhengqikj.top/Article/details/gtjnwtdxrm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.wangdashe.top/Article/details/gtrtplcovr.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gtacldpysk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhongyouzk.top/Article/details/gtmjwfeikn.html

[U108] JS：随机整数
来源：http://dali.redwolf501.top/Article/details/gtioexgwdk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.tian-w.cn/Article/details/gtpimvownp.html

[U109] JS：数组分组
来源：http://dali.xziqi.cn/Article/details/gtqwiybril.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hysaishi.cn/Article/details/gtyxybkmqw.html

[U110] JS：数组分块
来源：http://dali.quarkkingdee.top/Article/details/gtxxzmzmef.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdcnmpqv.html

[U111] JS：对象转 Map
来源：http://dali.zhiwuduotai.top/Article/details/gtcovuybdj.html

new Map(Object.entries(obj))
来源：http://dali.cucudq.cn/Article/details/gtritegpvk.html

[U112] JS：字符串补位
来源：http://dali.jinqigufen.top/Article/details/gtcxekquln.html

"7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtlrzksqrl.html

[U113] JS：正则替换全部
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtaavzmd.html

s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtwiufnyaq.html

[U114] JS：JSON 深比较
来源：http://dali.hammf.cn/Article/details/gtqrerdztw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yonumen.top/Article/details/gtqbxfqojh.html

[U115] JS：生成 UUID
来源：http://dali.jinghuilouyu.cn/Article/details/gttgvtwfep.html

crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtqzowkjsf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gtjrhvihoh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yangfankeji.com/Article/details/gtdonynekk.html

[U117] JS：单元测试
来源：http://dali.sysykeji.top/Article/details/gtiytkvygz.html

npm i -D vitest;  npx vitest
来源：http://dali.hongshengwenyu.top/Article/details/gtzzcisvap.html

[U118] JS：开发服务器
来源：http://dali.jqgfzy.top/Article/details/gtwtmzxyzs.html

npm i -D vite;  npx vite
来源：http://dali.ppjwa.cn/Article/details/gteocpeygv.html

[U119] JS：生产构建
来源：http://dali.zdqjudy.top/Article/details/gtwssmohyr.html

npx vite build
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchcahrdl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ppjwa.cn/Article/details/gtqldickeh.html

import.meta.env.VITE_API_URL
来源：http://dali.gogol.net.cn/Article/details/gtrltlarbl.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtaaqyqrtz.html

统计汇总
来源：http://dali.daxiang520.top/Article/details/gtjjbmbkir.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxoyzarv.html

按语言统计（条）：
来源：http://dali.yj20258.top/Article/details/gtlceqxgii.html

Python ......... 252
来源：http://dali.hysaishi.cn/Article/details/gtjufqbuhw.html

PHP ............ 252
来源：http://dali.jlsjyb.cn/Article/details/gtplkbpbdw.html

JavaScript ..... 252
来源：http://dali.jqgufenzy.top/Article/details/gtjuxrderq.html

TypeScript ..... 212
来源：http://dali.jiagoushi.top/Article/details/gtjayuakvf.html

Java ........... 212
来源：http://dali.xuanzx.com/Article/details/gtlczifave.html

Go ............. 212
来源：http://dali.iojbl.cn/Article/details/gtppazckpi.html

Ruby ........... 212
来源：http://dali.zdqjudy.top/Article/details/gtctphxzcn.html

C# ............. 212
来源：http://dali.hfpthk.cn/Article/details/gtehwimoul.html

C .............. 30
来源：http://dali.birdmap.top/Article/details/gtbrenunah.html

C++ ............ 30
来源：http://dali.sweek.top/Article/details/gtichnnscb.html

SQL ............ 90
来源：http://dali.jianghu66.top/Article/details/gtdeieldhl.html

Bash ........... 80
来源：http://dali.9152youxi.cn/Article/details/gtaxvismkn.html

Kotlin ......... 15
来源：http://dali.shuidangran.top/Article/details/gtyszkxjkt.html

Swift .......... 15
来源：http://dali.yonumen.top/Article/details/gtljrtsqsb.html

Lua ............ 10
来源：http://dali.pycfn.com/Article/details/gtjfwccjby.html

Perl ........... 10
来源：http://dali.jinghuilouyu.cn/Article/details/gtdakjpnwl.html

Scala .......... 10
来源：http://dali.yueranfly.top/Article/details/gthbqpjapx.html

------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gtbrvnnioy.html

合计 ........... 2106 条
来源：http://dali.iojbl.cn/Article/details/gtlyifwepz.html

按章节统计：
来源：http://dali.ppjwa.cn/Article/details/gtkonulxkb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.svipenyu.cn/Article/details/gtezgocrfh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.chenjidiqi.icu/Article/details/gtefgbvtkr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.fengsongda.top/Article/details/gtzsrvtzot.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknmmvzxk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.mhx1999.top/Article/details/gtemvkrfze.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.snrcjt.cn/Article/details/gtmkwgqzpf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ppjwa.cn/Article/details/gtmxvtlqef.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jyoumei.cn/Article/details/gtkxbmaukq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gtjcjichzh.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xuanzx.com/Article/details/gtkgkedrzd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gtoiusiski.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gtbapsaebd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gtpyoqxitd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.feifeiyinyue.top/Article/details/gtgzueleax.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.fengsongda.top/Article/details/gtqniwlygy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gtjzygkfic.html

Q SQL 专题                              90
来源：http://dali.gogol.net.cn/Article/details/gtnddujytx.html

R Bash 专题                             80
来源：http://dali.feifeiyinyue.top/Article/details/gtewwfxaxa.html

S C / C++ 专题                          60
来源：http://dali.gaohongyu789.top/Article/details/gtvzxokkkd.html

T 其他语言补充                          60
来源：http://dali.tian-w.cn/Article/details/gtjeugzkuh.html

U 高频实用片段                         120
来源：http://dali.yuxming.cn/Article/details/gtqkrrwyxr.html

------------------------------------
来源：http://dali.ybcxt.top/Article/details/gtweyummsl.html

合计                                  2106 条
来源：http://dali.gaohongyu789.top/Article/details/gtjllnaegz.html

--------------------------------------------------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gtllimvkhp.html

使用提醒
来源：http://dali.snrcjt.cn/Article/details/gtiyizijfp.html

--------------------------------------------------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gtftsvzfuq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.pycfn.com/Article/details/gtotupvbga.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xylfe.cn/Article/details/gtwjxvunat.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.tanke756.top/Article/details/gtajtzcyog.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.sxryk.cn/Article/details/gtrxkefvuu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.tanke756.top/Article/details/gtswghlqkm.html

—— 文件结束 ——
来源：http://dali.fengsongda.top/Article/details/gtphnhnubr.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtckrlmmyj.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yanxiufei.cn/Article/details/gtvushwenl.html

Common Programming Examples Cheat Book
来源：http://dali.yueranfly.top/Article/details/gtghsvrncw.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtredsskmy.html

【收录内容】
来源：http://dali.zdqjudy.top/Article/details/gtqestbbrh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.havefunace.top/Article/details/gtgxsqxbzo.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.shuidangran.top/Article/details/gtmjthdnlq.html

SQL · Bash · C · C++
来源：http://dali.jiagoushi.top/Article/details/gtpoasmoov.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.gaohongyu789.top/Article/details/gtfqrferog.html

【使用说明】
来源：http://dali.jyoumei.cn/Article/details/gtgnkibndc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhengqikj.top/Article/details/gtwxderxfz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yonumen.top/Article/details/gthxwhghuk.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.sysykeji.top/Article/details/gtmnhfcfjo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zdqjudy.top/Article/details/gtcmwbfosm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yj202588.top/Article/details/gtynoucrrq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.havefunace.top/Article/details/gtbwucqjsd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugxjtrye.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xuetiantiany.cn/Article/details/gtewpuqhpt.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ydzc1.top/Article/details/gtarkxtrqc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhixingplan.top/Article/details/gtrmvfudkv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.cheryme.top/Article/details/gtbaaqzwdl.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cashguo.top/Article/details/gtsrxvwinu.html

【文件统计】
来源：http://dali.dashuyun.cn/Article/details/gtetvytget.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhengqikj.top/Article/details/gtyrnknwtc.html

--------------------------------------------------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gtoqbnbbak.html

目  录
来源：http://dali.gogol.net.cn/Article/details/gthrzwbkwc.html

--------------------------------------------------------------------------------
来源：http://dali.nwbrower.top/Article/details/gtjdbxqhmr.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.0kj1m.cn/Article/details/gtnshlindp.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.kuanghao11.cn/Article/details/gtyiywekhy.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.9152youxi.cn/Article/details/gtbbqcirdu.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hnxiangtu.top/Article/details/gtatougabc.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yueranfly.top/Article/details/gteworello.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.meibo888.top/Article/details/gtnvffigzz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcszrgne.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzxoilux.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gtehgfbvwd.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shzxlz.cn/Article/details/gtplilhheg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtjnswtwgo.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yuxming.cn/Article/details/gtphqvazng.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cashguo.top/Article/details/gtqsaegljk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.c1oappe.top/Article/details/gtbfwzfwba.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.dashuyun.cn/Article/details/gtduaohyhh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gtlotmmiml.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.nwbrower.top/Article/details/gtexdvissr.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyihdpzdb.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.0kj1m.cn/Article/details/gtuiwctlni.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fengsongda.top/Article/details/gtwfconxqs.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.gogol.net.cn/Article/details/gtqtejshbq.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtnjyreqrk.html

A. 基础语法与类型
来源：http://dali.vqdsnc.cn/Article/details/gtjtgbvhdn.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtwlnkyyjc.html

[A01] Hello World
来源：http://dali.andypj.xyz/Article/details/gtkuzfqiet.html

Py:   print("Hello, World!")
来源：http://dali.daria6918.cn/Article/details/gtopheyhuv.html

PHP:  echo "Hello, World!";
来源：http://dali.gzhubu.top/Article/details/gtdpqgigub.html

JS:   console.log("Hello, World!");
来源：http://dali.fzhhl.top/Article/details/gtryytrixs.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtucaxky.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gttbjqhybw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.tanke756.top/Article/details/gtkqpdhqox.html

Ruby: puts "Hello, World!"
来源：http://dali.chenzaomai.com/Article/details/gtocvefxku.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jlsjyb.cn/Article/details/gtjcssfarm.html

[A02] 变量声明与赋值
来源：http://dali.fengsongda.top/Article/details/gthnwcpqxs.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yonumen.top/Article/details/gtdfqulbwl.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yanxiufei.cn/Article/details/gtwibpqvzz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.chenjidiqi.icu/Article/details/gtjyvfyiez.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hywenlv.cn/Article/details/gtzshohjet.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.nanxinkj.top/Article/details/gtcagchsii.html

Go:   name := "Alex"; age := 20
来源：http://dali.wangshuangyany.cn/Article/details/gtkkldptco.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gaohongyu789.top/Article/details/gtdktmbpob.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zdqjudy.top/Article/details/gtomxezhzc.html

[A03] 常量定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibcffvub.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zdqjudy.top/Article/details/gtdlvnoukr.html

PHP:  const PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtwrvzmzsj.html

JS:   const PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtfawxyfon.html

TS:   const PI: number = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtiqasbjtn.html

Java: static final double PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gteydtegtc.html

Go:   const PI = 3.14159
来源：http://dali.ppjwa.cn/Article/details/gtmdlbbyxd.html

Ruby: PI = 3.14159
来源：http://dali.svipenyu.cn/Article/details/gtlkumhjbe.html

C#:   const double PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtyfhpqizm.html

[A04] 判断变量类型
来源：http://dali.c1oappe.top/Article/details/gtgfywnbnq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.cheryme.top/Article/details/gtzwotytgr.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.xuanzx.com/Article/details/gtgufgmovr.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hysaishi.cn/Article/details/gtakxvzmmq.html

TS:   typeof x; x instanceof Date
来源：http://dali.shzxlz.cn/Article/details/gtsxwjhfop.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jqgufenzy.top/Article/details/gtzsdvmmeg.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.andypj.xyz/Article/details/gtbrlznxhj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.guannengcc.top/Article/details/gtiksyqbdh.html

C#:   x.GetType().Name; x is int
来源：http://dali.tanke756.top/Article/details/gtdhvetgtz.html

[A05] 整数除法与取模
来源：http://dali.xuanzx.com/Article/details/gtfharqxfs.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngsrdyqb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtiwebstgx.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aizwys.cn/Article/details/gtyfbxvesv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.daxiang520.top/Article/details/gtiggwgqml.html

Java: 7 / 2; 7 % 2
来源：http://dali.dashuyun.cn/Article/details/gteutqgnlj.html

Go:   7 / 2; 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gtygnybnsx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yueranfly.top/Article/details/gtwbozirnl.html

C#:   7 / 2; 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gtozumlpzc.html

[A06] 字符串转数字
来源：http://dali.hywenlv.cn/Article/details/gtsnbokavf.html

Py:   int("42"); float("3.14")
来源：http://dali.jyoumei.cn/Article/details/gtluxcjpic.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.chenzaomai.com/Article/details/gtvfufvfbi.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.bjfxy.top/Article/details/gtpgfhglwg.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.sysykeji.top/Article/details/gtoqgziile.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.xuanzx.com/Article/details/gttxikanim.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.guannengcc.top/Article/details/gtcpvqbgfx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.tianlin.xyz/Article/details/gtyxeaijnm.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.316326.xyz/Article/details/gtuhcrbewc.html

[A07] 数字转字符串
来源：http://dali.nwbrower.top/Article/details/gtlgwzugbz.html

Py:   str(42)
来源：http://dali.wangshuangyany.cn/Article/details/gtytieuxzl.html

PHP:  (string) 42; strval(42)
来源：http://dali.hnqzz.top/Article/details/gtfpmfdgsk.html

JS:   String(42); (42).toString()
来源：http://dali.yangfankeji.com/Article/details/gtfnpftboc.html

TS:   String(42)
来源：http://dali.hywenlv.cn/Article/details/gtnotsqcza.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.316326.xyz/Article/details/gtyxcsgevq.html

Go:   strconv.Itoa(42)
来源：http://dali.shuidangran.top/Article/details/gtiibkvnpa.html

Ruby: 42.to_s
来源：http://dali.fengsongda.top/Article/details/gtjpkjvhoe.html

C#:   42.ToString()
来源：http://dali.yj202588.top/Article/details/gtwpisiypy.html

[A08] 取整与四舍五入
来源：http://dali.guannengcc.top/Article/details/gtxabgaica.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.shangyingyoupin.top/Article/details/gttgxyodld.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hongshengwenyu.top/Article/details/gttuemghxr.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.ybcxt.top/Article/details/gtkndjlros.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yuxming.cn/Article/details/gtazsyieei.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.shzxlz.cn/Article/details/gtrfnytpkq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.hammf.cn/Article/details/gtzavwzirf.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.andypj.xyz/Article/details/gtvjgxxquj.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.tanke756.top/Article/details/gthcvjrogo.html

[A09] 绝对值与最大最小值
来源：http://dali.ybcxt.top/Article/details/gtddkezmab.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yueranfly.top/Article/details/gtxaawgiax.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtsiklwscm.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gttuybgrrn.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtaelwkmbo.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gtwywzzfrz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.fengsongda.top/Article/details/gtwtybqmmc.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.shangyingyoupin.top/Article/details/gtzjbouxcf.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtqbwdnwyg.html

[A10] 生成随机数
来源：http://dali.yj202588.top/Article/details/gttpksfilo.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zdqjudy.top/Article/details/gtxwthxtpz.html

PHP:  random_int(1, 100);
来源：http://dali.daria6918.cn/Article/details/gthpycwxqt.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.smart0.xyz/Article/details/gtrnjfsioj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.vqdsnc.cn/Article/details/gtczbrihvu.html

Java: new Random().nextInt(100) + 1
来源：http://dali.gzhubu.top/Article/details/gtisvveavi.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jinqigfzy.top/Article/details/gtfczgutxy.html

Ruby: rand(1..100)
来源：http://dali.hongshengwenyu.top/Article/details/gtyrssmusb.html

C#:   new Random().Next(1, 101)
来源：http://dali.jqgfzy.top/Article/details/gtlmxxxztj.html

[A11] 条件表达式（三元）
来源：http://dali.sweek.top/Article/details/gtobgngtpr.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.hysaishi.cn/Article/details/gtvrkqsjak.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.jiagoushi.top/Article/details/gtzmjmnstq.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.hongshengwenyu.top/Article/details/gtlayovucx.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.andypj.xyz/Article/details/gtebhsmspc.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.feifeiyinyue.top/Article/details/gtwrdaiysu.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.nanxinkj.top/Article/details/gtmbblyfks.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.gotoacloud.top/Article/details/gttqcynpjj.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jlsjyb.cn/Article/details/gtsevoryfo.html

[A12] 字符串插值 / 格式化
来源：http://dali.hnxiangtu.top/Article/details/gtobmczzcu.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.fengsongda.top/Article/details/gtspuomhds.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.svipenyu.cn/Article/details/gtqekudxxl.html

JS:   `Hello, ${name}!`
来源：http://dali.birdmap.top/Article/details/gtcxkzeiqj.html

TS:   `Hello, ${name}!`
来源：http://dali.jyoumei.cn/Article/details/gtgrkwclov.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.nanxuanxn.top/Article/details/gtblnobupo.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.fzhhl.top/Article/details/gtqfpkfcwq.html

Ruby: "Hello, #{name}!"
来源：http://dali.guannengcc.top/Article/details/gtuufdjhtu.html

C#:   $"Hello, {name}!"
来源：http://dali.hammf.cn/Article/details/gtuvgqklyb.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.tanke756.top/Article/details/gtxnsrxhmz.html

Py:   "第一行\n第二行"
来源：http://dali.hywenlv.cn/Article/details/gtqxkekmkh.html

PHP:  "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gtvmbcvsns.html

JS:   "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gtlwzkfzry.html

TS:   "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gtqqoygqcq.html

Java: "第一行\n第二行"
来源：http://dali.hnxiangtu.top/Article/details/gtladkxbls.html

Go:   "第一行\n第二行"
来源：http://dali.jinqigfzy.top/Article/details/gtoqpzqlgc.html

Ruby: "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gtlehlbepo.html

C#:   "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gtqyvidvmv.html

[A14] 注释写法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhgrypli.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jqgfzy.top/Article/details/gtegcinmow.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.gogol.net.cn/Article/details/gtpfyuanuq.html

JS:   // 单行；/* 多行 */
来源：http://dali.jinqigufen.top/Article/details/gtpgnprkhp.html

TS:   // 单行；/* 多行 */
来源：http://dali.gogol.net.cn/Article/details/gtbwvjbstd.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.shangyingyoupin.top/Article/details/gtlmgigoba.html

Go:   // 单行；/* 多行 */
来源：http://dali.havefunace.top/Article/details/gtvluoscad.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhixingplan.top/Article/details/gtovuvezdq.html

C#:   // 单行；/* 多行 */
来源：http://dali.9152youxi.cn/Article/details/gtnifdmweo.html

[A15] 空值判断与默认值
来源：http://dali.yj20258888.top/Article/details/gtpniopfdm.html

Py:   value = data or "默认值"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpywiyfnd.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.kuanghao11.cn/Article/details/gtfyomobpt.html

JS:   const value = data ?? "默认值";
来源：http://dali.xziqi.cn/Article/details/gtkxtpqrrv.html

TS:   const value = data ?? "默认值";
来源：http://dali.yj20258888.top/Article/details/gtflzgwdqd.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.guannengcc.top/Article/details/gtfalphrmp.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.tianlin.xyz/Article/details/gtaoobsxvq.html

Ruby: value = data || "默认值"
来源：http://dali.jqgfzy.top/Article/details/gtfkvqoyrs.html

C#:   var value = data ?? "默认值";
来源：http://dali.xuanzx.com/Article/details/gttphlbbyr.html

[A16] 真假值判断规则
来源：http://dali.hongshengwenyu.top/Article/details/gthsseonkc.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhongyouzk.top/Article/details/gtuvbypdfz.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.tanke756.top/Article/details/gtiqsuqhkp.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhiwuduotai.top/Article/details/gtkwncsbbm.html

TS:   if (!x) {}
来源：http://dali.bjfxy.top/Article/details/gtssccaoju.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yuanzhike.top/Article/details/gtracekdgf.html


<!-- 参考信息 -->