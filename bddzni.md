代发 wailian999

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gtqacjsbra.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gthaymqzkr.html

[U98] JS：fetch 带 JSON
来源：http://dali.yuanzhike.top/Article/details/gtmxxvvysz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.gaohongyu789.top/Article/details/gtimpdfmlt.html

[U99] JS：事件监听
来源：http://dali.cashguo.top/Article/details/gtxfrgjznz.html

el.addEventListener("click", e => {})
来源：http://dali.zdqjudy.top/Article/details/gthohutxos.html

[U100] JS：DOM 查询
来源：http://dali.dianchejie.cn/Article/details/gticorzhem.html

document.querySelector(".item")
来源：http://dali.snrcjt.cn/Article/details/gtgihtwspq.html

[U101] JS：classList 操作
来源：http://dali.yvedp.cn/Article/details/gtnqntmgxc.html

el.classList.toggle("active")
来源：http://dali.xuanzx.com/Article/details/gtufhhbmjj.html

[U102] JS：本地存储
来源：http://dali.sysykeji.top/Article/details/gtrogalqgm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.fengsongda.top/Article/details/gtlickvwlv.html

[U103] JS：定时器
来源：http://dali.aibaodan.cn/Article/details/gtngwhweyd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shuidangran.top/Article/details/gtmywkekej.html

[U104] JS：防抖
来源：http://dali.hywenlv.cn/Article/details/gtzfrwqcpl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gtnfgwcqyb.html

[U105] JS：节流
来源：http://dali.jianghu66.top/Article/details/gtpwulpixw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.mhx1999.top/Article/details/gtlygwromy.html

[U106] JS：日期格式化
来源：http://dali.cdnleiting.top/Article/details/gtjhuqqzra.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.vqdsnc.cn/Article/details/gtqujggphw.html

[U107] JS：数字千分位
来源：http://dali.zycfv.cn/Article/details/gtghkodcho.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yj20258.top/Article/details/gtlsvfcmgl.html

[U108] JS：随机整数
来源：http://dali.sysykeji.top/Article/details/gtnegwtdwl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.vqdsnc.cn/Article/details/gtnzmxjrys.html

[U109] JS：数组分组
来源：http://dali.ppjwa.cn/Article/details/gtaxpqthya.html

Object.groupBy(arr, x => x.type)
来源：http://dali.aibaodan.cn/Article/details/gtuuafidne.html

[U110] JS：数组分块
来源：http://dali.yj202588.top/Article/details/gtixzklers.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hywenlv.cn/Article/details/gtjrlqhpty.html

[U111] JS：对象转 Map
来源：http://dali.tianlin.xyz/Article/details/gtalakqagd.html

new Map(Object.entries(obj))
来源：http://dali.ydzc1.top/Article/details/gtfngmhkrj.html

[U112] JS：字符串补位
来源：http://dali.zhongyouzk.top/Article/details/gtdsfcnvgb.html

"7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtemfxttlh.html

[U113] JS：正则替换全部
来源：http://dali.yuanzhike.top/Article/details/gtqjpruida.html

s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtosoynvxo.html

[U114] JS：JSON 深比较
来源：http://dali.9152youxi.cn/Article/details/gtwujlnvti.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenjidiqi.icu/Article/details/gteeuxvhwl.html

[U115] JS：生成 UUID
来源：http://dali.gogol.net.cn/Article/details/gtayfvntne.html

crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gtfxqwnfhy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.wangshuangyany.cn/Article/details/gtqvocbkgf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hnqzz.top/Article/details/gtjtjpuiod.html

[U117] JS：单元测试
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqgooqxq.html

npm i -D vitest;  npx vitest
来源：http://dali.snrcjt.cn/Article/details/gtnggrvfwe.html

[U118] JS：开发服务器
来源：http://dali.gotoacloud.top/Article/details/gtmsooutiu.html

npm i -D vite;  npx vite
来源：http://dali.ybcxt.top/Article/details/gtwxlatuod.html

[U119] JS：生产构建
来源：http://dali.jqgfzy.top/Article/details/gtizfxorho.html

npx vite build
来源：http://dali.yj202588.top/Article/details/gtpnnrfkcu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hnqzz.top/Article/details/gtozgubggt.html

import.meta.env.VITE_API_URL
来源：http://dali.chenzaomai.com/Article/details/gtnxcxroet.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtymtpoznf.html

统计汇总
来源：http://dali.smart0.xyz/Article/details/gttwszegxt.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtfryqaflf.html

按语言统计（条）：
来源：http://dali.zhixingplan.top/Article/details/gthjixzebz.html

Python ......... 252
来源：http://dali.vqdsnc.cn/Article/details/gttitfpqpe.html

PHP ............ 252
来源：http://dali.smart0.xyz/Article/details/gttzbtgyhm.html

JavaScript ..... 252
来源：http://dali.yangfankeji.com/Article/details/gttaqlhhkf.html

TypeScript ..... 212
来源：http://dali.gotoacloud.top/Article/details/gtmbjnomua.html

Java ........... 212
来源：http://dali.ybcxt.top/Article/details/gtgqphjezu.html

Go ............. 212
来源：http://dali.jqgufenzy.top/Article/details/gthsywezch.html

Ruby ........... 212
来源：http://dali.nanxinkj.top/Article/details/gtwwkneeil.html

C# ............. 212
来源：http://dali.tian-w.cn/Article/details/gtawqvlemc.html

C .............. 30
来源：http://dali.ehwqpu.com/Article/details/gtbnfuowqi.html

C++ ............ 30
来源：http://dali.9152youxi.cn/Article/details/gtrqkjntqo.html

SQL ............ 90
来源：http://dali.pengpengdd.cyou/Article/details/gtanddlegp.html

Bash ........... 80
来源：http://dali.pengpengdd.cyou/Article/details/gtqfdxwbid.html

Kotlin ......... 15
来源：http://dali.nanxuanxn.top/Article/details/gtbixrnfei.html

Swift .......... 15
来源：http://dali.mhx1999.top/Article/details/gttbzpnfyv.html

Lua ............ 10
来源：http://dali.hywenlv.cn/Article/details/gtgbzteyuy.html

Perl ........... 10
来源：http://dali.ehwqpu.com/Article/details/gtkqlmprjj.html

Scala .......... 10
来源：http://dali.pengpengdd.cyou/Article/details/gtpyrbftvq.html

------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gtahvbyxai.html

合计 ........... 2106 条
来源：http://dali.aibaodan.cn/Article/details/gtsuwogrvw.html

按章节统计：
来源：http://dali.nanxuanxn.top/Article/details/gtvuzjaslq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.aizwys.cn/Article/details/gtwtjdrygs.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.aibaodan.cn/Article/details/gtpzmpohif.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cheryme.top/Article/details/gtkjexbmur.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhlwlmwt.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhongyouzk.top/Article/details/gtkelvjxui.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzaqmdokn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.feifeiyinyue.top/Article/details/gtwrbaksjt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnewgillq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gtxquwpnfb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gogol.net.cn/Article/details/gtkmnidjnp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gtiagucgyi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gtqcxfdzbc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gthcpvpoye.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.haohaochexian.top/Article/details/gtmsjodfuh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.daxiang520.top/Article/details/gtagjjkyyv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gtitjugfzi.html

Q SQL 专题                              90
来源：http://dali.ppjwa.cn/Article/details/gtxaedjdxp.html

R Bash 专题                             80
来源：http://dali.bjfxy.top/Article/details/gtjckwgloh.html

S C / C++ 专题                          60
来源：http://dali.ybcxt.top/Article/details/gtznvscfpk.html

T 其他语言补充                          60
来源：http://dali.sysykeji.top/Article/details/gtvuwfoqhp.html

U 高频实用片段                         120
来源：http://dali.daria6918.cn/Article/details/gtndajirpn.html

------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdrpalqg.html

合计                                  2106 条
来源：http://dali.sysykeji.top/Article/details/gtaabwoped.html

--------------------------------------------------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gtjjvbtjvj.html

使用提醒
来源：http://dali.cdnleiting.top/Article/details/gtzviwrncr.html

--------------------------------------------------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gtjerhggyk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cashguo.top/Article/details/gtbsgkqijt.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlodgnyhj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ybcxt.top/Article/details/gtyrfjcgou.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jqgfzy.top/Article/details/gtgffxurfy.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yj20258888.top/Article/details/gtgepmwacd.html

—— 文件结束 ——
来源：http://dali.pycfn.com/Article/details/gtdswktrlg.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtdztnsbhu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.havefunace.top/Article/details/gtkcoqkuwj.html

Common Programming Examples Cheat Book
来源：http://dali.jianghu66.top/Article/details/gtxmrdvlzb.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpktorxu.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gtueuktslc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.tianlin.xyz/Article/details/gtbxdjowrc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.0kj1m.cn/Article/details/gtjlusdroa.html

SQL · Bash · C · C++
来源：http://dali.yongpay.top/Article/details/gtsxezhbbc.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.316326.xyz/Article/details/gtrhrjcnvj.html

【使用说明】
来源：http://dali.wangdashe.top/Article/details/gtnnqejjgz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.xuetiantiany.cn/Article/details/gtoxknrdbw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hammf.cn/Article/details/gtuoyczyjm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.vqdsnc.cn/Article/details/gtvegaisas.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.pengpengdd.cyou/Article/details/gtxtrvyfbt.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.pengpengdd.cyou/Article/details/gtcdgpczbc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yj202588.top/Article/details/gtseikuujx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.316326.xyz/Article/details/gtcmffovoy.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jinghuilouyu.cn/Article/details/gtogqyxkax.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jiagoushi.top/Article/details/gtkrigcrhs.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.chenjidiqi.icu/Article/details/gtvsvqvvdf.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xinyue.icu/Article/details/gtmhccgird.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.fengsongda.top/Article/details/gtsfgditox.html

【文件统计】
来源：http://dali.xinyue.icu/Article/details/gtloyclezm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.sweek.top/Article/details/gtzaosypio.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gtqilelpts.html

目  录
来源：http://dali.gzhubu.top/Article/details/gtsphnhdor.html

--------------------------------------------------------------------------------
来源：http://dali.havefunace.top/Article/details/gtjdhhbqau.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvmukefm.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.andypj.xyz/Article/details/gtzqfuxkhx.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.bjfxy.top/Article/details/gtvrhljkvj.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.cashguo.top/Article/details/gtbakazpfz.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zycfv.cn/Article/details/gtqsfddhkl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.sysykeji.top/Article/details/gtzxwovjdc.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.iojbl.cn/Article/details/gtbutltpnj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.bjfxy.top/Article/details/gtqgereyyl.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gtxowanifg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.iojbl.cn/Article/details/gtxrocifrc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.meibo888.top/Article/details/gtjyaqleel.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gtpcoakiry.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.dashuyun.cn/Article/details/gttacjoyzr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhixingplan.top/Article/details/gtqecfjnaq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.gaohongyu789.top/Article/details/gtaymcvfdl.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhixingplan.top/Article/details/gtajtxxtnn.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jlsjyb.cn/Article/details/gtozaatbvl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yanxiufei.cn/Article/details/gtzuujpksv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jqgufenzy.top/Article/details/gthfugkmbf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.havefunace.top/Article/details/gtzbevrvlu.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hfpthk.cn/Article/details/gtnfqjcohp.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gteczlfmdw.html

A. 基础语法与类型
来源：http://dali.sweek.top/Article/details/gtwxdakxyc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtoknqkwup.html

[A01] Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtnmgljxqq.html

Py:   print("Hello, World!")
来源：http://dali.jinqigufen.top/Article/details/gtcharwmic.html

PHP:  echo "Hello, World!";
来源：http://dali.zhongyouzk.top/Article/details/gtphqgwxix.html

JS:   console.log("Hello, World!");
来源：http://dali.zhongyouzk.top/Article/details/gtnhefdbrf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.sweek.top/Article/details/gtfkpmukmx.html

Java: System.out.println("Hello, World!");
来源：http://dali.yj20258.top/Article/details/gtpjnritwh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmynlnftj.html

Ruby: puts "Hello, World!"
来源：http://dali.zhengqikj.top/Article/details/gteghmwvox.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.guannengcc.top/Article/details/gtygmzlqbz.html

[A02] 变量声明与赋值
来源：http://dali.zhiwuduotai.top/Article/details/gtyhmzwuva.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gtzypxipkt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.cheryme.top/Article/details/gtutltyvxp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jinqigufen.top/Article/details/gtcrplsmyu.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yuxming.cn/Article/details/gtrxroskom.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zdqjudy.top/Article/details/gtrxbgpdvq.html

Go:   name := "Alex"; age := 20
来源：http://dali.fzhhl.top/Article/details/gtylkkbxfa.html

Ruby: name = "Alex"; age = 20
来源：http://dali.daria6918.cn/Article/details/gthghqtlxz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.gzhubu.top/Article/details/gttiazomfg.html

[A03] 常量定义
来源：http://dali.aizwys.cn/Article/details/gtqgecbvve.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cucudq.cn/Article/details/gtizdmhtxp.html

PHP:  const PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtocjdzpgg.html

JS:   const PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtmgxrfmee.html

TS:   const PI: number = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtblgytvsw.html

Java: static final double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvaounkir.html

Go:   const PI = 3.14159
来源：http://dali.yj202588.top/Article/details/gtdwplycho.html

Ruby: PI = 3.14159
来源：http://dali.yvedp.cn/Article/details/gtfsmvdigq.html

C#:   const double PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gtoksaygng.html

[A04] 判断变量类型
来源：http://dali.jinqigufen.top/Article/details/gtdcddnwzj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.svipenyu.cn/Article/details/gtffcjfnuh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.sxryk.cn/Article/details/gtvpkkibda.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjicfyii.html

TS:   typeof x; x instanceof Date
来源：http://dali.jinqigfzy.top/Article/details/gtssxabmmf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.birdmap.top/Article/details/gtwrkyfbrq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yonumen.top/Article/details/gtojwmowol.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xylfe.cn/Article/details/gtilqtxxbe.html

C#:   x.GetType().Name; x is int
来源：http://dali.chenzaomai.com/Article/details/gtbewdavca.html

[A05] 整数除法与取模
来源：http://dali.quarkkingdee.top/Article/details/gttkgmsnoq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.haohaochexian.top/Article/details/gtyozksbpv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.cheryme.top/Article/details/gtguxjhfyz.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.nanxuanxn.top/Article/details/gtspvakjnr.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gtyawworzf.html

Java: 7 / 2; 7 % 2
来源：http://dali.xinyue.icu/Article/details/gtvfhdaxig.html

Go:   7 / 2; 7 % 2
来源：http://dali.yj20258.top/Article/details/gtgxergocs.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gtiupktmyf.html

C#:   7 / 2; 7 % 2
来源：http://dali.cashguo.top/Article/details/gtgpgayxgt.html

[A06] 字符串转数字
来源：http://dali.sxryk.cn/Article/details/gtstelivbw.html

Py:   int("42"); float("3.14")
来源：http://dali.haohaochexian.top/Article/details/gteqszgowe.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsuplbfem.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.meibo888.top/Article/details/gtatbcmsyg.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gtvojghmgt.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.dashuyun.cn/Article/details/gtlhvjuhvz.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.cheryme.top/Article/details/gtpebiqvgl.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.mhx1999.top/Article/details/gtkpocsrox.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.sxryk.cn/Article/details/gtmvvrfaek.html

[A07] 数字转字符串
来源：http://dali.nwbrower.top/Article/details/gtyqabsgdo.html

Py:   str(42)
来源：http://dali.guannengcc.top/Article/details/gtfhsnddyp.html

PHP:  (string) 42; strval(42)
来源：http://dali.ivvv.top/Article/details/gtgnnodawl.html

JS:   String(42); (42).toString()
来源：http://dali.yonumen.top/Article/details/gtkchicekn.html

TS:   String(42)
来源：http://dali.hammf.cn/Article/details/gtmckmnjud.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.hysaishi.cn/Article/details/gtpthocuxd.html

Go:   strconv.Itoa(42)
来源：http://dali.tianlin.xyz/Article/details/gtgucpyita.html

Ruby: 42.to_s
来源：http://dali.0kj1m.cn/Article/details/gtujoeejef.html

C#:   42.ToString()
来源：http://dali.zhiwuduotai.top/Article/details/gtmustrqfe.html

[A08] 取整与四舍五入
来源：http://dali.ywan-chungtsiang.top/Article/details/gteoohruwf.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.316326.xyz/Article/details/gtnfcwurxi.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.nwbrower.top/Article/details/gttehwwugl.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.ehwqpu.com/Article/details/gtxihjbdzu.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.daria6918.cn/Article/details/gtfjxpuqfb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yonumen.top/Article/details/gtqmlyodgs.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gtkzimweks.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.cdnleiting.top/Article/details/gtgajzklca.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hammf.cn/Article/details/gtkuapdgvb.html

[A09] 绝对值与最大最小值
来源：http://dali.yongpay.top/Article/details/gtmkprljyp.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gtjxxtlusk.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.tian-w.cn/Article/details/gtgqbgbprd.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtderdplhi.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gtjawqgilm.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.birdmap.top/Article/details/gtzmfqbczl.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.andypj.xyz/Article/details/gthwticcfx.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobncligw.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtkqyuklxk.html

[A10] 生成随机数
来源：http://dali.0kj1m.cn/Article/details/gtphzeajlh.html

Py:   import random; random.randint(1, 100)
来源：http://dali.svipenyu.cn/Article/details/gtrsddvzaw.html

PHP:  random_int(1, 100);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwmfivbrw.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.meibo888.top/Article/details/gtoafzntjt.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.feifeiyinyue.top/Article/details/gtdzialgwu.html

Java: new Random().nextInt(100) + 1
来源：http://dali.shuidangran.top/Article/details/gtjpijxvwq.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hammf.cn/Article/details/gtadhrubnr.html

Ruby: rand(1..100)
来源：http://dali.sxryk.cn/Article/details/gtubrhavae.html

C#:   new Random().Next(1, 101)
来源：http://dali.xylfe.cn/Article/details/gtherhrcuv.html

[A11] 条件表达式（三元）
来源：http://dali.shzxlz.cn/Article/details/gtogoogbby.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jlsjyb.cn/Article/details/gttpusmnea.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.mhx1999.top/Article/details/gtxgjetdnq.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.shangyingyoupin.top/Article/details/gthuvxoswp.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.chenzaomai.com/Article/details/gtyhjsolsg.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.chenzaomai.com/Article/details/gtgulsayqo.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.cqqwz.cn/Article/details/gtlnooawyj.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.guowangkeji.top/Article/details/gtffxxhrcx.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.hfpthk.cn/Article/details/gtsirblqdu.html

[A12] 字符串插值 / 格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtkhktxymo.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.sweek.top/Article/details/gtisbeayis.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.xziqi.cn/Article/details/gtisuumrrz.html

JS:   `Hello, ${name}!`
来源：http://dali.jlsjyb.cn/Article/details/gtktvymnlc.html

TS:   `Hello, ${name}!`
来源：http://dali.kuanghao11.cn/Article/details/gtzfrcuqac.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xuanzx.com/Article/details/gtzmhbdbsk.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.0kj1m.cn/Article/details/gtosfznmxq.html

Ruby: "Hello, #{name}!"
来源：http://dali.cucudq.cn/Article/details/gtutqzwcli.html

C#:   $"Hello, {name}!"
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfdufpse.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.jinghuilouyu.cn/Article/details/gtciopxxyu.html

Py:   "第一行\n第二行"
来源：http://dali.chenlongwang.top/Article/details/gtzhsjgfgx.html

PHP:  "第一行\n第二行"
来源：http://dali.ivvv.top/Article/details/gtsuxznnhh.html

JS:   "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gtlrdxxjhs.html

TS:   "第一行\n第二行"
来源：http://dali.hfpthk.cn/Article/details/gtzquylmct.html

Java: "第一行\n第二行"
来源：http://dali.wangdashe.top/Article/details/gtyplozbke.html

Go:   "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gtwkynakls.html

Ruby: "第一行\n第二行"
来源：http://dali.mhx1999.top/Article/details/gtbrqihgoy.html

C#:   "第一行\n第二行"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbqoajlr.html

[A14] 注释写法
来源：http://dali.fengsongda.top/Article/details/gtrhgaygmo.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.cashguo.top/Article/details/gtujiebtzm.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.meibo888.top/Article/details/gtmjeckzgw.html

JS:   // 单行；/* 多行 */
来源：http://dali.shuidangran.top/Article/details/gtznpiftue.html

TS:   // 单行；/* 多行 */
来源：http://dali.jinghuilouyu.cn/Article/details/gtufalssal.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.bjfxy.top/Article/details/gtspxrrgrx.html

Go:   // 单行；/* 多行 */
来源：http://dali.jinqigufen.top/Article/details/gtzuuvlqzv.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.snrcjt.cn/Article/details/gtbjixdkhn.html

C#:   // 单行；/* 多行 */
来源：http://dali.yuanzhike.top/Article/details/gtnyxwzlbx.html

[A15] 空值判断与默认值
来源：http://dali.fengsongda.top/Article/details/gtpvvupvrv.html

Py:   value = data or "默认值"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqjhvonl.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.dashuyun.cn/Article/details/gtfpsshvmd.html

JS:   const value = data ?? "默认值";
来源：http://dali.chenjidiqi.icu/Article/details/gtmmaisrxc.html

TS:   const value = data ?? "默认值";
来源：http://dali.xuetiantiany.cn/Article/details/gtackojksp.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ydzc1.top/Article/details/gtfxzqkxut.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.9152youxi.cn/Article/details/gtvxqfvaba.html

Ruby: value = data || "默认值"
来源：http://dali.tanke756.top/Article/details/gtiremdqde.html

C#:   var value = data ?? "默认值";
来源：http://dali.hywenlv.cn/Article/details/gthdctzcrg.html

[A16] 真假值判断规则
来源：http://dali.xinyue.icu/Article/details/gtxlytpyba.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.gaohongyu789.top/Article/details/gtdkuknsru.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlzhqvleb.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hnxiangtu.top/Article/details/gtnkosoxsl.html

TS:   if (!x) {}
来源：http://dali.316326.xyz/Article/details/gtnkkxctvb.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.xuanzx.com/Article/details/gtgchnzlrh.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.svipenyu.cn/Article/details/gtdasvgnqc.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jqgfzy.top/Article/details/gtrjnrvgbf.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.smart0.xyz/Article/details/gtkeudjrio.html

[A17] 位运算
来源：http://dali.sufxvd.cn/Article/details/gtbydpntnr.html


<!-- 参考信息 -->