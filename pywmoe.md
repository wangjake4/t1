代发 wailian999

[U95] JS：Promise 包装
来源：http://dali.zhiwuduotai.top/Article/details/gtefhgieri.html

new Promise((resolve, reject) => {})
来源：http://dali.chenjidiqi.icu/Article/details/gtjfkmovkt.html

[U96] JS：async/await 与异常
来源：http://dali.zhiwuduotai.top/Article/details/gtzjqltgpc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gticiueerj.html

[U97] JS：并发请求
来源：http://dali.wangdashe.top/Article/details/gtcpyppfsk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrkfhval.html

[U98] JS：fetch 带 JSON
来源：http://dali.jinqigufen.top/Article/details/gtxtjtxamj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.andypj.xyz/Article/details/gtsvxaxncg.html

[U99] JS：事件监听
来源：http://dali.0kj1m.cn/Article/details/gtfzzrxjdm.html

el.addEventListener("click", e => {})
来源：http://dali.gogol.net.cn/Article/details/gtjbbnjtpj.html

[U100] JS：DOM 查询
来源：http://dali.xuanzx.com/Article/details/gtsorsxolk.html

document.querySelector(".item")
来源：http://dali.gaohongyu789.top/Article/details/gtnncylhbh.html

[U101] JS：classList 操作
来源：http://dali.sweek.top/Article/details/gtbymfhanl.html

el.classList.toggle("active")
来源：http://dali.gzhubu.top/Article/details/gtktkyawio.html

[U102] JS：本地存储
来源：http://dali.bjfxy.top/Article/details/gtzhueooow.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.chenzaomai.com/Article/details/gtuwazuvnc.html

[U103] JS：定时器
来源：http://dali.zhixingplan.top/Article/details/gtdpcjdynd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.andypj.xyz/Article/details/gtrkwdlysy.html

[U104] JS：防抖
来源：http://dali.xuanzx.com/Article/details/gtnvocxdhk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gtknzdywhs.html

[U105] JS：节流
来源：http://dali.ivvv.top/Article/details/gtpvhxkimr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zycfv.cn/Article/details/gtynllyohg.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gtjbpiwcmu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.pycfn.com/Article/details/gtrkhpyvqe.html

[U107] JS：数字千分位
来源：http://dali.daxiang520.top/Article/details/gtcmrhnrwv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gotoacloud.top/Article/details/gtzjdgzvvc.html

[U108] JS：随机整数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehzuqakn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.9152youxi.cn/Article/details/gthxlwvdiq.html

[U109] JS：数组分组
来源：http://dali.yj20258888.top/Article/details/gtxztqqixx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.aibaodan.cn/Article/details/gtkhvlbzdn.html

[U110] JS：数组分块
来源：http://dali.yuxming.cn/Article/details/gttpryalrc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xylfe.cn/Article/details/gtkdefiqne.html

[U111] JS：对象转 Map
来源：http://dali.cdnleiting.top/Article/details/gtrebhluqh.html

new Map(Object.entries(obj))
来源：http://dali.cheryme.top/Article/details/gtedfrieti.html

[U112] JS：字符串补位
来源：http://dali.xinyue.icu/Article/details/gtdexkhizb.html

"7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtjjwysbyp.html

[U113] JS：正则替换全部
来源：http://dali.tanke756.top/Article/details/gtvuqgvrir.html

s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtxthiwdmo.html

[U114] JS：JSON 深比较
来源：http://dali.daxiang520.top/Article/details/gtprszgulq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenlongwang.top/Article/details/gtfloansyq.html

[U115] JS：生成 UUID
来源：http://dali.jyoumei.cn/Article/details/gtmkjrsqfk.html

crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gtpvahcdzi.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.sufxvd.cn/Article/details/gtefxyddvx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gtafjufigr.html

[U117] JS：单元测试
来源：http://dali.kuanghao11.cn/Article/details/gtjquutqbu.html

npm i -D vitest;  npx vitest
来源：http://dali.ivvv.top/Article/details/gtcbdybdge.html

[U118] JS：开发服务器
来源：http://dali.c1oappe.top/Article/details/gteifimmcq.html

npm i -D vite;  npx vite
来源：http://dali.quarkkingdee.top/Article/details/gtrwommvyw.html

[U119] JS：生产构建
来源：http://dali.zhoulong.xyz/Article/details/gtrxjhgjad.html

npx vite build
来源：http://dali.dianchejie.cn/Article/details/gtqoylvlji.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cucudq.cn/Article/details/gtwbvgryan.html

import.meta.env.VITE_API_URL
来源：http://dali.yvedp.cn/Article/details/gthaevgkil.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtistkcfiy.html

统计汇总
来源：http://dali.shuidangran.top/Article/details/gtfzzlmdmo.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtqnaluhto.html

按语言统计（条）：
来源：http://dali.cdnleiting.top/Article/details/gtxxisgavt.html

Python ......... 252
来源：http://dali.ydzc1.top/Article/details/gttgtdivdb.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gtskxpmqcw.html

JavaScript ..... 252
来源：http://dali.gzhubu.top/Article/details/gtlehrvwys.html

TypeScript ..... 212
来源：http://dali.hnxiangtu.top/Article/details/gtnexsshmp.html

Java ........... 212
来源：http://dali.zhongyouzk.top/Article/details/gtwnbtgzdy.html

Go ............. 212
来源：http://dali.ydzc1.top/Article/details/gtcuzqnunb.html

Ruby ........... 212
来源：http://dali.tanke756.top/Article/details/gtcvwtwqgk.html

C# ............. 212
来源：http://dali.haohaochexian.top/Article/details/gtlspjawmy.html

C .............. 30
来源：http://dali.gotoacloud.top/Article/details/gtiwiwshte.html

C++ ............ 30
来源：http://dali.jqgfzy.top/Article/details/gtgklvmeok.html

SQL ............ 90
来源：http://dali.vqdsnc.cn/Article/details/gtpncphacr.html

Bash ........... 80
来源：http://dali.wangdashe.top/Article/details/gtoqvdnkrh.html

Kotlin ......... 15
来源：http://dali.xuetiantiany.cn/Article/details/gtnghpxnqk.html

Swift .......... 15
来源：http://dali.zhengqikj.top/Article/details/gtqrrsdfyu.html

Lua ............ 10
来源：http://dali.svipenyu.cn/Article/details/gtzuftlhfo.html

Perl ........... 10
来源：http://dali.jiagoushi.top/Article/details/gtktukmzod.html

Scala .......... 10
来源：http://dali.tanke756.top/Article/details/gtkgznpjqy.html

------------------------------------
来源：http://dali.iojbl.cn/Article/details/gtzyhemfhb.html

合计 ........... 2106 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovjoyghu.html

按章节统计：
来源：http://dali.tianlin.xyz/Article/details/gtcjikwzba.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tian-w.cn/Article/details/gtvheoquih.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cashguo.top/Article/details/gtifjkprco.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.pengpengdd.cyou/Article/details/gtxvkbkmjt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gzhubu.top/Article/details/gtnhjerluf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.316326.xyz/Article/details/gtwlirtvcs.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.sxryk.cn/Article/details/gtcpdmwhrf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.birdmap.top/Article/details/gtnazzsfcs.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nanxinkj.top/Article/details/gtfdomgsud.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gtggkchwqt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhongyouzk.top/Article/details/gtpvlkcycl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gtnpavhvoy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfynrabpj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gtfhostwej.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hfpthk.cn/Article/details/gtwyfblmyf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.chenzaomai.com/Article/details/gtwnqxybix.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gthzcghjrm.html

Q SQL 专题                              90
来源：http://dali.quarkkingdee.top/Article/details/gtlqpfrlex.html

R Bash 专题                             80
来源：http://dali.sysykeji.top/Article/details/gtamqkjtfo.html

S C / C++ 专题                          60
来源：http://dali.zhixingplan.top/Article/details/gtreefcifz.html

T 其他语言补充                          60
来源：http://dali.xuanzx.com/Article/details/gtkbqjlrjq.html

U 高频实用片段                         120
来源：http://dali.tian-w.cn/Article/details/gtmxhoayce.html

------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gtevbqlakv.html

合计                                  2106 条
来源：http://dali.316326.xyz/Article/details/gtngqjcnsm.html

--------------------------------------------------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gtapxmeome.html

使用提醒
来源：http://dali.jiagoushi.top/Article/details/gtmbslypeb.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gtzqlkqkiz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jyoumei.cn/Article/details/gtegcidioy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.smart0.xyz/Article/details/gtgqnlerie.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hnxiangtu.top/Article/details/gtlnmtqbgj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hongshengwenyu.top/Article/details/gtyikljqbn.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.chenjidiqi.icu/Article/details/gtcgnbesrd.html

—— 文件结束 ——
来源：http://dali.daria6918.cn/Article/details/gterckqkvl.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gthomyskdh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.c1oappe.top/Article/details/gtwqoklbue.html

Common Programming Examples Cheat Book
来源：http://dali.zhengqikj.top/Article/details/gtsfwdbdbm.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtiqbxbsfr.html

【收录内容】
来源：http://dali.andypj.xyz/Article/details/gtntzomjlg.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jqgfzy.top/Article/details/gtrvjikerj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.feifeiyinyue.top/Article/details/gtepivogge.html

SQL · Bash · C · C++
来源：http://dali.fengsongda.top/Article/details/gtcuigcgsb.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xuanzx.com/Article/details/gtdoitwlze.html

【使用说明】
来源：http://dali.chenlongwang.top/Article/details/gtdshfynyd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shuidangran.top/Article/details/gtbjdlilca.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ybcxt.top/Article/details/gtwzyqmlpa.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yueranfly.top/Article/details/gtsynklack.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ydzc1.top/Article/details/gtzkrsqrqk.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.iojbl.cn/Article/details/gthmbuoffu.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.fzhhl.top/Article/details/gtzuckcuxx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gzhubu.top/Article/details/gtrfvaizlb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zycfv.cn/Article/details/gtkyrvqowh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ppjwa.cn/Article/details/gtvqrhksuj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.svipenyu.cn/Article/details/gtoqupaurl.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhongyouzk.top/Article/details/gtxbzlpkyh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.0kj1m.cn/Article/details/gtutllceev.html

【文件统计】
来源：http://dali.daxiang520.top/Article/details/gttnwkbbqa.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xylfe.cn/Article/details/gtpjftbuap.html

--------------------------------------------------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtuxczjtkp.html

目  录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzdmykvgf.html

--------------------------------------------------------------------------------
来源：http://dali.daria6918.cn/Article/details/gtswlcmgpt.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhengqikj.top/Article/details/gtashgpgdr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zdqjudy.top/Article/details/gtjocbghzq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shzxlz.cn/Article/details/gtfzzyemqz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yvedp.cn/Article/details/gtebtfbxyn.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.tianlin.xyz/Article/details/gtupkerxjb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.aibaodan.cn/Article/details/gtsvstrppm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yueranfly.top/Article/details/gtrfjozbga.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhongyouzk.top/Article/details/gtugmonvhg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gtkwbijyrt.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxcsmoqkn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gturztawyw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gtcabjmhin.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwqgexyr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.dashuyun.cn/Article/details/gthungufhs.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptkoqbyq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.tanke756.top/Article/details/gtsibxupcd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jinqigfzy.top/Article/details/gtemhxotqq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.guowangkeji.top/Article/details/gtqhhhgneb.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hammf.cn/Article/details/gtwtctogci.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cheryme.top/Article/details/gtiaqbgxar.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258.top/Article/details/gtfkjcinkg.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gthxniwljs.html

A. 基础语法与类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkebqfrd.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtpvagdwbk.html

[A01] Hello World
来源：http://dali.xylfe.cn/Article/details/gtcasoqapi.html

Py:   print("Hello, World!")
来源：http://dali.yuanzhike.top/Article/details/gtaiymgmam.html

PHP:  echo "Hello, World!";
来源：http://dali.gaohongyu789.top/Article/details/gtdfaotnwh.html

JS:   console.log("Hello, World!");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezogapvj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.birdmap.top/Article/details/gtaijkcdjv.html

Java: System.out.println("Hello, World!");
来源：http://dali.sxryk.cn/Article/details/gtiyxpozqe.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xinyue.icu/Article/details/gtupvimrrw.html

Ruby: puts "Hello, World!"
来源：http://dali.ivvv.top/Article/details/gtuwfbyool.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hammf.cn/Article/details/gteamzdqof.html

[A02] 变量声明与赋值
来源：http://dali.zhiwuduotai.top/Article/details/gtdvljlkzj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sysykeji.top/Article/details/gtgjtkzzaa.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmkyfuxv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyhgzntlp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.bjfxy.top/Article/details/gtcimnjrlb.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.daria6918.cn/Article/details/gtmvdfizrq.html

Go:   name := "Alex"; age := 20
来源：http://dali.bjfxy.top/Article/details/gteahczmme.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yj20258888.top/Article/details/gtqftassoy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwumzbgn.html

[A03] 常量定义
来源：http://dali.sysykeji.top/Article/details/gtarwbzzqo.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.0kj1m.cn/Article/details/gtvolqiyhw.html

PHP:  const PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtyeahiffi.html

JS:   const PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtktjbitpi.html

TS:   const PI: number = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtczbrstwn.html

Java: static final double PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtlpshafeb.html

Go:   const PI = 3.14159
来源：http://dali.svipenyu.cn/Article/details/gtpmrndcoz.html

Ruby: PI = 3.14159
来源：http://dali.wangdashe.top/Article/details/gtwjqsldlh.html

C#:   const double PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmtgmtan.html

[A04] 判断变量类型
来源：http://dali.yueranfly.top/Article/details/gtgvmqdrpr.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hysaishi.cn/Article/details/gtxjbkdofk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ybcxt.top/Article/details/gtuxctrrvc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yanxiufei.cn/Article/details/gtjcxtnqho.html

TS:   typeof x; x instanceof Date
来源：http://dali.havefunace.top/Article/details/gtxxohigvu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.andypj.xyz/Article/details/gtuiffrqlf.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.guowangkeji.top/Article/details/gtzntfyqvi.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.hnqzz.top/Article/details/gtgewpggeg.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhixingplan.top/Article/details/gtmfpoefek.html

[A05] 整数除法与取模
来源：http://dali.chenzaomai.com/Article/details/gtukjprzib.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cucudq.cn/Article/details/gtncklcbub.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.birdmap.top/Article/details/gtcagkcypt.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj20258.top/Article/details/gtpysfizgm.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gtzkstwzpa.html

Java: 7 / 2; 7 % 2
来源：http://dali.sxryk.cn/Article/details/gtsydayknv.html

Go:   7 / 2; 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gthwyxngpy.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtsoxcpooa.html

C#:   7 / 2; 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gtiqnmmmwk.html

[A06] 字符串转数字
来源：http://dali.tian-w.cn/Article/details/gtallfkzhz.html

Py:   int("42"); float("3.14")
来源：http://dali.svipenyu.cn/Article/details/gtckzdryqp.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zdqjudy.top/Article/details/gtapliyxkf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.nwbrower.top/Article/details/gtmljdswiv.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.tanke756.top/Article/details/gtgajobosa.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yj20258.top/Article/details/gtkpntpzsu.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.aizwys.cn/Article/details/gtjpmymzwg.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jinqigufen.top/Article/details/gtctfjnhjp.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhixingplan.top/Article/details/gtpokasehb.html

[A07] 数字转字符串
来源：http://dali.tanke756.top/Article/details/gtzkeqcnjl.html

Py:   str(42)
来源：http://dali.nanxinkj.top/Article/details/gtjuuiqszx.html

PHP:  (string) 42; strval(42)
来源：http://dali.316326.xyz/Article/details/gtmszjmhtf.html

JS:   String(42); (42).toString()
来源：http://dali.andypj.xyz/Article/details/gthwsfvcwe.html

TS:   String(42)
来源：http://dali.gaohongyu789.top/Article/details/gtcanajbfl.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.nanxuanxn.top/Article/details/gtrunzhnos.html

Go:   strconv.Itoa(42)
来源：http://dali.cashguo.top/Article/details/gtotgaaqhp.html

Ruby: 42.to_s
来源：http://dali.ybcxt.top/Article/details/gtswdwzcro.html

C#:   42.ToString()
来源：http://dali.ppjwa.cn/Article/details/gtbepfhssz.html

[A08] 取整与四舍五入
来源：http://dali.yuanzhike.top/Article/details/gtfgwjclyd.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yvedp.cn/Article/details/gtunrtojsg.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.nanxuanxn.top/Article/details/gtcugxoeyf.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.chenjidiqi.icu/Article/details/gtknltrfer.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.iojbl.cn/Article/details/gtafnryvyn.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.xylfe.cn/Article/details/gtfxdwyebz.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.wangdashe.top/Article/details/gtfqhmzkcd.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jinqigufen.top/Article/details/gteqqcylqe.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.gzhubu.top/Article/details/gtmshhfxcb.html

[A09] 绝对值与最大最小值
来源：http://dali.jlsjyb.cn/Article/details/gtpdswpqag.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtsvltlvqc.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gthwwlrdks.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gtetgeqaue.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gtgfbfkmou.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.xinyue.icu/Article/details/gtlcuqfexa.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jqgufenzy.top/Article/details/gtoutkgjge.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.sxryk.cn/Article/details/gtiushkqrt.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtzqfjqqgf.html

[A10] 生成随机数
来源：http://dali.xinyue.icu/Article/details/gtgooaffxz.html

Py:   import random; random.randint(1, 100)
来源：http://dali.gaohongyu789.top/Article/details/gtlacocoxf.html

PHP:  random_int(1, 100);
来源：http://dali.yueranfly.top/Article/details/gtcnuuffto.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yj20258888.top/Article/details/gteccdukhf.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jlsjyb.cn/Article/details/gtsqntrhhv.html

Java: new Random().nextInt(100) + 1
来源：http://dali.sysykeji.top/Article/details/gtipjjsalm.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.ybcxt.top/Article/details/gtpvslsdpw.html

Ruby: rand(1..100)
来源：http://dali.mhx1999.top/Article/details/gtsmloyjpa.html

C#:   new Random().Next(1, 101)
来源：http://dali.9152youxi.cn/Article/details/gtzsfhrnpb.html

[A11] 条件表达式（三元）
来源：http://dali.xinyue.icu/Article/details/gtffwgoafe.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yanxiufei.cn/Article/details/gtzymjhzuw.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yonumen.top/Article/details/gtfujsptup.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yj202588.top/Article/details/gthstdrxig.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.pengpengdd.cyou/Article/details/gtpsslsohg.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jianghu66.top/Article/details/gtxpafmucw.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jqgufenzy.top/Article/details/gtfkyubmja.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.iojbl.cn/Article/details/gtskvamkiz.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.havefunace.top/Article/details/gtfoucqdfq.html

[A12] 字符串插值 / 格式化
来源：http://dali.nanxinkj.top/Article/details/gthngztxuc.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jinqigufen.top/Article/details/gtbmnmknuc.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.tian-w.cn/Article/details/gtmfpachzt.html

JS:   `Hello, ${name}!`
来源：http://dali.zhengqikj.top/Article/details/gtjaqnteka.html

TS:   `Hello, ${name}!`
来源：http://dali.gogol.net.cn/Article/details/gtpscsvocy.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.redwolf501.top/Article/details/gtxraedhst.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.xuetiantiany.cn/Article/details/gthbhphthf.html

Ruby: "Hello, #{name}!"
来源：http://dali.dashuyun.cn/Article/details/gtzmzqvbad.html

C#:   $"Hello, {name}!"
来源：http://dali.daria6918.cn/Article/details/gtpbxsacot.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.iojbl.cn/Article/details/gtdcfygxxj.html

Py:   "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gtpgynsfzm.html

PHP:  "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gtncbfxvwx.html

JS:   "第一行\n第二行"
来源：http://dali.cdnleiting.top/Article/details/gtprqfdyud.html

TS:   "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gtnjtrzqlz.html

Java: "第一行\n第二行"
来源：http://dali.yvedp.cn/Article/details/gtrpnyctys.html

Go:   "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gttalafkun.html

Ruby: "第一行\n第二行"
来源：http://dali.mhx1999.top/Article/details/gtbmlbxmbf.html

C#:   "第一行\n第二行"
来源：http://dali.jinqigufen.top/Article/details/gtbqxgkjhy.html

[A14] 注释写法
来源：http://dali.zhixingplan.top/Article/details/gtxtuyehhh.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.svipenyu.cn/Article/details/gtylzkuqvx.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoffaybmy.html

JS:   // 单行；/* 多行 */
来源：http://dali.smart0.xyz/Article/details/gtyurusktn.html

TS:   // 单行；/* 多行 */
来源：http://dali.ybcxt.top/Article/details/gtygthbtry.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.svipenyu.cn/Article/details/gtrxkeauei.html

Go:   // 单行；/* 多行 */
来源：http://dali.svipenyu.cn/Article/details/gtdwbrtson.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.quarkkingdee.top/Article/details/gtzolbykpx.html

C#:   // 单行；/* 多行 */
来源：http://dali.gogol.net.cn/Article/details/gtcyetghjw.html

[A15] 空值判断与默认值
来源：http://dali.fengsongda.top/Article/details/gtavpmvlcy.html

Py:   value = data or "默认值"
来源：http://dali.jyoumei.cn/Article/details/gtqqcshgpm.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.pengpengdd.cyou/Article/details/gtfaojwmtq.html

JS:   const value = data ?? "默认值";
来源：http://dali.guowangkeji.top/Article/details/gtvakqkmsa.html

TS:   const value = data ?? "默认值";
来源：http://dali.aibaodan.cn/Article/details/gttlpipipi.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yj20258888.top/Article/details/gtwyrwjgdu.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.snrcjt.cn/Article/details/gtzanisuqb.html

Ruby: value = data || "默认值"
来源：http://dali.0kj1m.cn/Article/details/gtwjwevfus.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhengqikj.top/Article/details/gtojycuwdh.html

[A16] 真假值判断规则
来源：http://dali.mhx1999.top/Article/details/gtldedwomq.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.gotoacloud.top/Article/details/gtqucazhwn.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsgcoafy.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlftmmic.html

TS:   if (!x) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtumsqwfno.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.mhx1999.top/Article/details/gtmbhkgbuw.html


<!-- 参考信息 -->