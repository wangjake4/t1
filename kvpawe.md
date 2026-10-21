代发 wailian999

[U97] JS：并发请求
来源：http://dali.jianghu66.top/Article/details/gtcvicjzkz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gttibcgyqp.html

[U98] JS：fetch 带 JSON
来源：http://dali.jlsjyb.cn/Article/details/gtkaatvbce.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hnxiangtu.top/Article/details/gtkbfrmsnk.html

[U99] JS：事件监听
来源：http://dali.redwolf501.top/Article/details/gtafsazoya.html

el.addEventListener("click", e => {})
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhjjvbgh.html

[U100] JS：DOM 查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgllvabek.html

document.querySelector(".item")
来源：http://dali.cheryme.top/Article/details/gtcbyuwihe.html

[U101] JS：classList 操作
来源：http://dali.xziqi.cn/Article/details/gtahnhorot.html

el.classList.toggle("active")
来源：http://dali.jyoumei.cn/Article/details/gtrpmkirsa.html

[U102] JS：本地存储
来源：http://dali.aizwys.cn/Article/details/gtxjbyqqqw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nwbrower.top/Article/details/gtwkvscyae.html

[U103] JS：定时器
来源：http://dali.aibaodan.cn/Article/details/gtzprzzmul.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxhspvyq.html

[U104] JS：防抖
来源：http://dali.jinqigfzy.top/Article/details/gtllwbkqpq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gtngqzzfwu.html

[U105] JS：节流
来源：http://dali.nwbrower.top/Article/details/gtwdhortzo.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tianlin.xyz/Article/details/gtlophlhpa.html

[U106] JS：日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gtikngarcy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.tanke756.top/Article/details/gtwsygqzhx.html

[U107] JS：数字千分位
来源：http://dali.xziqi.cn/Article/details/gtibdpsiyu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgjdoazp.html

[U108] JS：随机整数
来源：http://dali.andypj.xyz/Article/details/gtmzkyzyde.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yj20258888.top/Article/details/gthmvdjmgq.html

[U109] JS：数组分组
来源：http://dali.dashuyun.cn/Article/details/gtqzhmlelk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jyoumei.cn/Article/details/gtnjisadro.html

[U110] JS：数组分块
来源：http://dali.chenzaomai.com/Article/details/gtprzmaqdo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.quarkkingdee.top/Article/details/gtymntfjaj.html

[U111] JS：对象转 Map
来源：http://dali.xziqi.cn/Article/details/gtxpygkjjw.html

new Map(Object.entries(obj))
来源：http://dali.yonumen.top/Article/details/gtiwwnbsbb.html

[U112] JS：字符串补位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzaliayqo.html

"7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gtudyzpzje.html

[U113] JS：正则替换全部
来源：http://dali.cashguo.top/Article/details/gtupivvlah.html

s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtyacdrlee.html

[U114] JS：JSON 深比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlyvarpj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nwbrower.top/Article/details/gtozuuiyby.html

[U115] JS：生成 UUID
来源：http://dali.xylfe.cn/Article/details/gtsjwoagrk.html

crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gtirgcszek.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.tianlin.xyz/Article/details/gtbyauewhz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.sweek.top/Article/details/gtmsusfiit.html

[U117] JS：单元测试
来源：http://dali.jiagoushi.top/Article/details/gtvxtpoxjm.html

npm i -D vitest;  npx vitest
来源：http://dali.jqgufenzy.top/Article/details/gtieluqmbl.html

[U118] JS：开发服务器
来源：http://dali.sweek.top/Article/details/gtsxadmpgy.html

npm i -D vite;  npx vite
来源：http://dali.jyoumei.cn/Article/details/gtsnvluxsl.html

[U119] JS：生产构建
来源：http://dali.0kj1m.cn/Article/details/gtjjklilyw.html

npx vite build
来源：http://dali.yueranfly.top/Article/details/gtyaqhzmot.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.aizwys.cn/Article/details/gtddnpqddv.html

import.meta.env.VITE_API_URL
来源：http://dali.snrcjt.cn/Article/details/gtfzpmhfhq.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtksmpijys.html

统计汇总
来源：http://dali.ehwqpu.com/Article/details/gthhnitsyl.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtzbcbmtjr.html

按语言统计（条）：
来源：http://dali.hfpthk.cn/Article/details/gtacfbwtju.html

Python ......... 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqtzzcfo.html

PHP ............ 252
来源：http://dali.shuidangran.top/Article/details/gtzybwpirv.html

JavaScript ..... 252
来源：http://dali.jqgufenzy.top/Article/details/gtxfhxkofz.html

TypeScript ..... 212
来源：http://dali.daria6918.cn/Article/details/gtnapffqbz.html

Java ........... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyuleusvj.html

Go ............. 212
来源：http://dali.hysaishi.cn/Article/details/gtymvcngnz.html

Ruby ........... 212
来源：http://dali.xziqi.cn/Article/details/gtbshghedv.html

C# ............. 212
来源：http://dali.yj20258.top/Article/details/gtcrdpabnq.html

C .............. 30
来源：http://dali.ybcxt.top/Article/details/gthabsjqyq.html

C++ ............ 30
来源：http://dali.hnqzz.top/Article/details/gtbjpupqwk.html

SQL ............ 90
来源：http://dali.yanxiufei.cn/Article/details/gtzkoyhmyo.html

Bash ........... 80
来源：http://dali.gotoacloud.top/Article/details/gtiddjdypl.html

Kotlin ......... 15
来源：http://dali.ppjwa.cn/Article/details/gtwdvntxvp.html

Swift .......... 15
来源：http://dali.ybcxt.top/Article/details/gtdtbtrkpt.html

Lua ............ 10
来源：http://dali.yuanzhike.top/Article/details/gtxkzvpmgg.html

Perl ........... 10
来源：http://dali.svipenyu.cn/Article/details/gtapmezwqm.html

Scala .......... 10
来源：http://dali.cheryme.top/Article/details/gtscudhjde.html

------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdkgodjlu.html

合计 ........... 2106 条
来源：http://dali.cdnleiting.top/Article/details/gtairctxrs.html

按章节统计：
来源：http://dali.dianchejie.cn/Article/details/gtnitwwfwt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.guannengcc.top/Article/details/gtpijicsbh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gtmnligkab.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.mhx1999.top/Article/details/gtiamyiseo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.kuanghao11.cn/Article/details/gtbmzmxtbs.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shuidangran.top/Article/details/gtdybyyuhr.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.9152youxi.cn/Article/details/gtaxdcwbrb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhoulong.xyz/Article/details/gtcjwhfrtp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.guannengcc.top/Article/details/gtmfagmthv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gtqttchybr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cucudq.cn/Article/details/gtwllcgjzy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhiwuduotai.top/Article/details/gtqkxfvwqk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gtvmdzmfcn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gtzmiffkba.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj20258.top/Article/details/gtnclyskkl.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yuxming.cn/Article/details/gtrtsbmram.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gthyzsqclk.html

Q SQL 专题                              90
来源：http://dali.ppjwa.cn/Article/details/gtqacfpogy.html

R Bash 专题                             80
来源：http://dali.yuanzhike.top/Article/details/gtwjvppvqp.html

S C / C++ 专题                          60
来源：http://dali.yanxiufei.cn/Article/details/gtcrfecdrx.html

T 其他语言补充                          60
来源：http://dali.daxiang520.top/Article/details/gtfeowssxr.html

U 高频实用片段                         120
来源：http://dali.jiagoushi.top/Article/details/gtwphtxotc.html

------------------------------------
来源：http://dali.smart0.xyz/Article/details/gtnynzelnq.html

合计                                  2106 条
来源：http://dali.yj20258888.top/Article/details/gtuydlwskj.html

--------------------------------------------------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gttjcfbfom.html

使用提醒
来源：http://dali.redwolf501.top/Article/details/gtzatdvvaj.html

--------------------------------------------------------------------------------
来源：http://dali.nwbrower.top/Article/details/gtwrmmgdae.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jyoumei.cn/Article/details/gtvxphrtvv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yvedp.cn/Article/details/gtrjdrgsey.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.chenzaomai.com/Article/details/gtxqdwnbpl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.nanxinkj.top/Article/details/gtdcrydpui.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhiwuduotai.top/Article/details/gtepdimbxx.html

—— 文件结束 ——
来源：http://dali.hnxiangtu.top/Article/details/gtbmboxpdh.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtokskxvyp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yanxiufei.cn/Article/details/gtayhrhdgt.html

Common Programming Examples Cheat Book
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejpvxthp.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtmtwutobe.html

【收录内容】
来源：http://dali.ivvv.top/Article/details/gttwkgcdzh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yonumen.top/Article/details/gtwyhfvjhy.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zycfv.cn/Article/details/gthsjefbtn.html

SQL · Bash · C · C++
来源：http://dali.yj202588.top/Article/details/gtydjtixki.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jinqigfzy.top/Article/details/gtzflchacj.html

【使用说明】
来源：http://dali.ybcxt.top/Article/details/gtutnvhljz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.tian-w.cn/Article/details/gtbigvwrbt.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jyoumei.cn/Article/details/gtlbmwcyvm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.snrcjt.cn/Article/details/gtjfuqbkzj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ydzc1.top/Article/details/gtulmlydtp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jinqigufen.top/Article/details/gtacdbiyrn.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenlongwang.top/Article/details/gtskacwajm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cucudq.cn/Article/details/gtgmzzcayj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.nwbrower.top/Article/details/gtedrcnlbh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.9152youxi.cn/Article/details/gtvprttkad.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.pycfn.com/Article/details/gtpnwhavrl.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwqpeyvo.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.daxiang520.top/Article/details/gtjabthlae.html

【文件统计】
来源：http://dali.yangfankeji.com/Article/details/gtwoeiojlg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhoulong.xyz/Article/details/gtwkmkrooo.html

--------------------------------------------------------------------------------
来源：http://dali.shuidangran.top/Article/details/gtcliytlay.html

目  录
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpmvvxsp.html

--------------------------------------------------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gtrjtsuzrz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.dashuyun.cn/Article/details/gtkmvzxsuc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.birdmap.top/Article/details/gtulstamqa.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jinqigufen.top/Article/details/gtlygzzaas.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ydzc1.top/Article/details/gtxpqxgozx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.kuanghao11.cn/Article/details/gtgiysecft.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yj20258888.top/Article/details/gtnbpgctuy.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cashguo.top/Article/details/gtehralkat.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.cqqwz.cn/Article/details/gtcdncnuji.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gtxaxasnol.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhoulong.xyz/Article/details/gtupcmwdqg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jiagoushi.top/Article/details/gtnsrfhdwf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gtvtkfuyrg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.guannengcc.top/Article/details/gtgbaygmqu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.tian-w.cn/Article/details/gtrzycmkse.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkuvxxpk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.kuanghao11.cn/Article/details/gtgdorzeat.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtyemggjyg.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.havefunace.top/Article/details/gtsduhxumh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yongpay.top/Article/details/gtrtllbhcy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ppjwa.cn/Article/details/gtbpjbkcde.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xinyue.icu/Article/details/gtlkzuueut.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtcqpazgin.html

A. 基础语法与类型
来源：http://dali.shanyushiyangtech.top/Article/details/gthyhtkbtx.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtochgjbgg.html

[A01] Hello World
来源：http://dali.zhengqikj.top/Article/details/gtvckmkhyw.html

Py:   print("Hello, World!")
来源：http://dali.gaohongyu789.top/Article/details/gtxbzsdham.html

PHP:  echo "Hello, World!";
来源：http://dali.hongshengwenyu.top/Article/details/gtqiqoaoii.html

JS:   console.log("Hello, World!");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqexwztu.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yvedp.cn/Article/details/gtcfatettl.html

Java: System.out.println("Hello, World!");
来源：http://dali.quarkkingdee.top/Article/details/gtrilydiex.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ivvv.top/Article/details/gtxmyomyfu.html

Ruby: puts "Hello, World!"
来源：http://dali.snrcjt.cn/Article/details/gtzzecnqsq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hfpthk.cn/Article/details/gtgpnhfmxz.html

[A02] 变量声明与赋值
来源：http://dali.jyoumei.cn/Article/details/gtawrnohuq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.wangdashe.top/Article/details/gtejxhdkqu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.daxiang520.top/Article/details/gthuddjpup.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gtqwddheez.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.snrcjt.cn/Article/details/gtywleoiig.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yj20258888.top/Article/details/gtdplzjhqx.html

Go:   name := "Alex"; age := 20
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcoaiwtao.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jiagoushi.top/Article/details/gtapfhticq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjbhlvhk.html

[A03] 常量定义
来源：http://dali.9152youxi.cn/Article/details/gtlbjwyweh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zycfv.cn/Article/details/gtvojabxpq.html

PHP:  const PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtlaxkevpl.html

JS:   const PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtwvuiozce.html

TS:   const PI: number = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtuelmuoxj.html

Java: static final double PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtsyubftft.html

Go:   const PI = 3.14159
来源：http://dali.jqgfzy.top/Article/details/gtozlsizyg.html

Ruby: PI = 3.14159
来源：http://dali.aizwys.cn/Article/details/gtuttlnsai.html

C#:   const double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gtxbguggir.html

[A04] 判断变量类型
来源：http://dali.shzxlz.cn/Article/details/gtqxbqjnbg.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hysaishi.cn/Article/details/gtjtilnqic.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutdxlxea.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zdqjudy.top/Article/details/gtnzrjvebf.html

TS:   typeof x; x instanceof Date
来源：http://dali.316326.xyz/Article/details/gtfvecsurf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.cheryme.top/Article/details/gtjniuapzb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.redwolf501.top/Article/details/gtjsfukxmt.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.cdnleiting.top/Article/details/gtiizqcyli.html

C#:   x.GetType().Name; x is int
来源：http://dali.shangyingyoupin.top/Article/details/gtzlulsygc.html

[A05] 整数除法与取模
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzwoarwj.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.pengpengdd.cyou/Article/details/gtaobodiad.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xuanzx.com/Article/details/gtmvosclne.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gtwcgthvqt.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gthewllieb.html

Java: 7 / 2; 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gtuypxzaro.html

Go:   7 / 2; 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdcufddc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gtopcpnkfu.html

C#:   7 / 2; 7 % 2
来源：http://dali.nwbrower.top/Article/details/gtvphnafou.html

[A06] 字符串转数字
来源：http://dali.316326.xyz/Article/details/gtkkeqtlaa.html

Py:   int("42"); float("3.14")
来源：http://dali.jinqigufen.top/Article/details/gtovljqrrj.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jqgufenzy.top/Article/details/gtumeukjkq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.xziqi.cn/Article/details/gtqarqyvex.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ppjwa.cn/Article/details/gtbpyyofkg.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.haohaochexian.top/Article/details/gtqxgfppyz.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.gotoacloud.top/Article/details/gtaveeenev.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.cdnleiting.top/Article/details/gtpgspkypm.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.nanxinkj.top/Article/details/gtcxeuefmo.html

[A07] 数字转字符串
来源：http://dali.aibaodan.cn/Article/details/gteantjrmk.html

Py:   str(42)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamzojumo.html

PHP:  (string) 42; strval(42)
来源：http://dali.havefunace.top/Article/details/gtwjcrxhxx.html

JS:   String(42); (42).toString()
来源：http://dali.dashuyun.cn/Article/details/gtiqfynphs.html

TS:   String(42)
来源：http://dali.cashguo.top/Article/details/gtffudrqos.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jinqigfzy.top/Article/details/gtrwnanysh.html

Go:   strconv.Itoa(42)
来源：http://dali.chenjidiqi.icu/Article/details/gtelfoomdv.html

Ruby: 42.to_s
来源：http://dali.xuetiantiany.cn/Article/details/gtdrddgcoe.html

C#:   42.ToString()
来源：http://dali.hnqzz.top/Article/details/gtveveladk.html

[A08] 取整与四舍五入
来源：http://dali.zhoulong.xyz/Article/details/gtdzgzgldv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yuanzhike.top/Article/details/gtgkfxthsw.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hongshengwenyu.top/Article/details/gtgsrfyntv.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.snrcjt.cn/Article/details/gtlfsjlnht.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.pycfn.com/Article/details/gtongfvvtg.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gtjsrokhde.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.guowangkeji.top/Article/details/gtgcwdftgp.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yuxming.cn/Article/details/gtarvbbkxm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.aibaodan.cn/Article/details/gtoemvvbjh.html

[A09] 绝对值与最大最小值
来源：http://dali.ydzc1.top/Article/details/gtnennbxit.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gtbwcnsipr.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yj202588.top/Article/details/gtjabpddqe.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gthqegxzvo.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hammf.cn/Article/details/gtadxzxidn.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gtxxvsqicp.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.fzhhl.top/Article/details/gttyjfwdzo.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.xylfe.cn/Article/details/gtyswfkhlf.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gtjvjsfkxn.html

[A10] 生成随机数
来源：http://dali.fzhhl.top/Article/details/gtasbgcmqf.html

Py:   import random; random.randint(1, 100)
来源：http://dali.sufxvd.cn/Article/details/gtsqxccmxo.html

PHP:  random_int(1, 100);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpgsrfcg.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.chenlongwang.top/Article/details/gtiftjnjez.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.mhx1999.top/Article/details/gtdvyakgem.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhiwuduotai.top/Article/details/gtgurvulep.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yvedp.cn/Article/details/gtpraauzov.html

Ruby: rand(1..100)
来源：http://dali.smart0.xyz/Article/details/gtfbqnlgnh.html

C#:   new Random().Next(1, 101)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwkgnqgr.html

[A11] 条件表达式（三元）
来源：http://dali.snrcjt.cn/Article/details/gtxvquwbnp.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yanxiufei.cn/Article/details/gtzmhkddwb.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yuanzhike.top/Article/details/gtyqahhhbq.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jiagoushi.top/Article/details/gtmvzlnhzr.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gtziqmbkau.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xinyue.icu/Article/details/gteyhrrcae.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jqgfzy.top/Article/details/gtxxthzsrj.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.hysaishi.cn/Article/details/gtsjvnlmmz.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.smart0.xyz/Article/details/gttsttucgz.html

[A12] 字符串插值 / 格式化
来源：http://dali.c1oappe.top/Article/details/gtxqhalaqd.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zycfv.cn/Article/details/gtjvqvztsh.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.havefunace.top/Article/details/gtgjvszaqa.html

JS:   `Hello, ${name}!`
来源：http://dali.zhoulong.xyz/Article/details/gtuwotzrdm.html

TS:   `Hello, ${name}!`
来源：http://dali.mhx1999.top/Article/details/gtmbdfedxn.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.gotoacloud.top/Article/details/gtmppevzqg.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.shzxlz.cn/Article/details/gtaemzuuyi.html

Ruby: "Hello, #{name}!"
来源：http://dali.havefunace.top/Article/details/gttmykhjkx.html

C#:   $"Hello, {name}!"
来源：http://dali.aibaodan.cn/Article/details/gtllzsvwrc.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.0kj1m.cn/Article/details/gtvckywhnu.html

Py:   "第一行\n第二行"
来源：http://dali.andypj.xyz/Article/details/gtojdiyjeg.html

PHP:  "第一行\n第二行"
来源：http://dali.ppjwa.cn/Article/details/gtrfkhhdyp.html

JS:   "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gtieylcpth.html

TS:   "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gtbshosqjm.html

Java: "第一行\n第二行"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqoikhwz.html

Go:   "第一行\n第二行"
来源：http://dali.316326.xyz/Article/details/gtfmhzbrwi.html

Ruby: "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gtcylevyvo.html

C#:   "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gtgrkhrnfk.html

[A14] 注释写法
来源：http://dali.havefunace.top/Article/details/gttabwuksn.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdejkiam.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.xuanzx.com/Article/details/gtvbtudjyn.html

JS:   // 单行；/* 多行 */
来源：http://dali.kuanghao11.cn/Article/details/gttafnsskb.html

TS:   // 单行；/* 多行 */
来源：http://dali.316326.xyz/Article/details/gtflxjdcpm.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.wangshuangyany.cn/Article/details/gtbusyovfv.html

Go:   // 单行；/* 多行 */
来源：http://dali.pycfn.com/Article/details/gttkfnrwvo.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.iojbl.cn/Article/details/gtjrrsydvt.html

C#:   // 单行；/* 多行 */
来源：http://dali.sysykeji.top/Article/details/gtfjdbiebb.html

[A15] 空值判断与默认值
来源：http://dali.hammf.cn/Article/details/gtqetjqmto.html

Py:   value = data or "默认值"
来源：http://dali.yangfankeji.com/Article/details/gtdpoalrdq.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.kuanghao11.cn/Article/details/gtnkosniqs.html

JS:   const value = data ?? "默认值";
来源：http://dali.xuanzx.com/Article/details/gttszsltto.html

TS:   const value = data ?? "默认值";
来源：http://dali.yonumen.top/Article/details/gtlebkwnnm.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yvedp.cn/Article/details/gthdercczs.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.gogol.net.cn/Article/details/gtlvrravwz.html

Ruby: value = data || "默认值"
来源：http://dali.smart0.xyz/Article/details/gtvtclpwyt.html

C#:   var value = data ?? "默认值";
来源：http://dali.zdqjudy.top/Article/details/gtisdecunh.html

[A16] 真假值判断规则
来源：http://dali.aizwys.cn/Article/details/gtffvxuwnz.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.haohaochexian.top/Article/details/gtkaslextq.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xinyue.icu/Article/details/gtbccbpynb.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jinqigfzy.top/Article/details/gtzhbjtevv.html

TS:   if (!x) {}
来源：http://dali.jqgfzy.top/Article/details/gtmydvoahq.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jlsjyb.cn/Article/details/gtswmhanqv.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.fzhhl.top/Article/details/gtappubnus.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.iojbl.cn/Article/details/gtkqietgeb.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.shuidangran.top/Article/details/gtwsefkuzm.html

[A17] 位运算
来源：http://dali.yuanzhike.top/Article/details/gthsnjzfrq.html


<!-- 参考信息 -->