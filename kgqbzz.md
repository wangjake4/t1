代发 wailian999

[U97] JS：并发请求
来源：http://dali.xylfe.cn/Article/details/gtbimmtrbd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gtanrkicii.html

[U98] JS：fetch 带 JSON
来源：http://dali.yj20258.top/Article/details/gtuebsvmwa.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzrvcjof.html

[U99] JS：事件监听
来源：http://dali.yj202588.top/Article/details/gtqfkdudlq.html

el.addEventListener("click", e => {})
来源：http://dali.vqdsnc.cn/Article/details/gtgklnbizl.html

[U100] JS：DOM 查询
来源：http://dali.yangfankeji.com/Article/details/gtlrhvbmqw.html

document.querySelector(".item")
来源：http://dali.sweek.top/Article/details/gtuftgnqhk.html

[U101] JS：classList 操作
来源：http://dali.guannengcc.top/Article/details/gtlwvjthll.html

el.classList.toggle("active")
来源：http://dali.fengsongda.top/Article/details/gtbrtqeeft.html

[U102] JS：本地存储
来源：http://dali.tanke756.top/Article/details/gtgrmzslzc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sxryk.cn/Article/details/gtxoezjgcc.html

[U103] JS：定时器
来源：http://dali.cqqwz.cn/Article/details/gthkwjaagm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.guannengcc.top/Article/details/gtcmxmfrsb.html

[U104] JS：防抖
来源：http://dali.jinqigfzy.top/Article/details/gtgvqyhqsq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gtwgvdxrnd.html

[U105] JS：节流
来源：http://dali.zdqjudy.top/Article/details/gthhugygef.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtgtinwrxt.html

[U106] JS：日期格式化
来源：http://dali.9152youxi.cn/Article/details/gthnawqfzk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yvedp.cn/Article/details/gtkrwtowap.html

[U107] JS：数字千分位
来源：http://dali.iojbl.cn/Article/details/gtdcmjfgtp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.tianlin.xyz/Article/details/gtuceyyqpd.html

[U108] JS：随机整数
来源：http://dali.daria6918.cn/Article/details/gtostwsxqw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.gogol.net.cn/Article/details/gtonyzfctj.html

[U109] JS：数组分组
来源：http://dali.zycfv.cn/Article/details/gtvlzerfug.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gtnjmpfbgh.html

[U110] JS：数组分块
来源：http://dali.zycfv.cn/Article/details/gtgaxylgyu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cqqwz.cn/Article/details/gtefkkotgi.html

[U111] JS：对象转 Map
来源：http://dali.ybcxt.top/Article/details/gtptrcvkah.html

new Map(Object.entries(obj))
来源：http://dali.hnqzz.top/Article/details/gtqzlxrspz.html

[U112] JS：字符串补位
来源：http://dali.yangfankeji.com/Article/details/gtjxcnjzey.html

"7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtkftclxuz.html

[U113] JS：正则替换全部
来源：http://dali.cucudq.cn/Article/details/gtdrhjsnqk.html

s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtrhituzlb.html

[U114] JS：JSON 深比较
来源：http://dali.yongpay.top/Article/details/gtayvffpqf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjyltzlyd.html

[U115] JS：生成 UUID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkgdorljq.html

crypto.randomUUID()
来源：http://dali.jqgufenzy.top/Article/details/gtovhgwxmx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.pengpengdd.cyou/Article/details/gtihajgzwu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jqgfzy.top/Article/details/gtqpilkyfk.html

[U117] JS：单元测试
来源：http://dali.hongshengwenyu.top/Article/details/gtshflnebn.html

npm i -D vitest;  npx vitest
来源：http://dali.dashuyun.cn/Article/details/gtyfdrhrdx.html

[U118] JS：开发服务器
来源：http://dali.yvedp.cn/Article/details/gtohcygyof.html

npm i -D vite;  npx vite
来源：http://dali.ppjwa.cn/Article/details/gtbhbutfhy.html

[U119] JS：生产构建
来源：http://dali.hywenlv.cn/Article/details/gtvbobprcq.html

npx vite build
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnhvnakr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cheryme.top/Article/details/gtipxmpepl.html

import.meta.env.VITE_API_URL
来源：http://dali.cashguo.top/Article/details/gtnzvizxqo.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtylkawbtg.html

统计汇总
来源：http://dali.pengpengdd.cyou/Article/details/gtxidrcdvp.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtdujhhnrw.html

按语言统计（条）：
来源：http://dali.xuetiantiany.cn/Article/details/gtmucwwfdp.html

Python ......... 252
来源：http://dali.316326.xyz/Article/details/gtapazrmce.html

PHP ............ 252
来源：http://dali.sxryk.cn/Article/details/gtiyndjeif.html

JavaScript ..... 252
来源：http://dali.smart0.xyz/Article/details/gtlythskvy.html

TypeScript ..... 212
来源：http://dali.hnxiangtu.top/Article/details/gtpiaeznyx.html

Java ........... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckdtntny.html

Go ............. 212
来源：http://dali.fengsongda.top/Article/details/gtuemgnche.html

Ruby ........... 212
来源：http://dali.dashuyun.cn/Article/details/gtumzeqywv.html

C# ............. 212
来源：http://dali.hnqzz.top/Article/details/gtlmhfcvcd.html

C .............. 30
来源：http://dali.xinyue.icu/Article/details/gtmwnewqvh.html

C++ ............ 30
来源：http://dali.haohaochexian.top/Article/details/gtyesefmws.html

SQL ............ 90
来源：http://dali.nanxuanxn.top/Article/details/gtieyxpmgc.html

Bash ........... 80
来源：http://dali.gaohongyu789.top/Article/details/gtevmvntzo.html

Kotlin ......... 15
来源：http://dali.fengsongda.top/Article/details/gtbagikbvz.html

Swift .......... 15
来源：http://dali.shzxlz.cn/Article/details/gtytfavyxj.html

Lua ............ 10
来源：http://dali.zdqjudy.top/Article/details/gtauzbaaqw.html

Perl ........... 10
来源：http://dali.dianchejie.cn/Article/details/gtemavoqno.html

Scala .......... 10
来源：http://dali.chenlongwang.top/Article/details/gtltoqelke.html

------------------------------------
来源：http://dali.ybcxt.top/Article/details/gtfnzozwgq.html

合计 ........... 2106 条
来源：http://dali.jyoumei.cn/Article/details/gtiadkajlw.html

按章节统计：
来源：http://dali.cqqwz.cn/Article/details/gtofidokjw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.dashuyun.cn/Article/details/gtzmtlwkfr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yvedp.cn/Article/details/gtogqmiszg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yvedp.cn/Article/details/gtkpvcqubd.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.feifeiyinyue.top/Article/details/gtwjyygscu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hnxiangtu.top/Article/details/gtxbumjtlq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jyoumei.cn/Article/details/gtrqeieeog.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.redwolf501.top/Article/details/gterrdvigo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cucudq.cn/Article/details/gtevjjdlhn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gtudlgfzsr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yonumen.top/Article/details/gtrnukhrqu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gthepsgdvz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gtelixghss.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gtglusxbte.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhixingplan.top/Article/details/gtmlkanpso.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.gotoacloud.top/Article/details/gtzlvbfraj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gterksgrfa.html

Q SQL 专题                              90
来源：http://dali.hnxiangtu.top/Article/details/gtyvwqckvi.html

R Bash 专题                             80
来源：http://dali.jyoumei.cn/Article/details/gtbezeftte.html

S C / C++ 专题                          60
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdzjdolmh.html

T 其他语言补充                          60
来源：http://dali.hnxiangtu.top/Article/details/gtjbeelktg.html

U 高频实用片段                         120
来源：http://dali.zhengqikj.top/Article/details/gtrnksefbd.html

------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gtrbgmnwuu.html

合计                                  2106 条
来源：http://dali.yj202588.top/Article/details/gtdsylbrxs.html

--------------------------------------------------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gthrkqcrmb.html

使用提醒
来源：http://dali.ybcxt.top/Article/details/gtyguevazx.html

--------------------------------------------------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gtytcxtcga.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.tianlin.xyz/Article/details/gtdhywhdjr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jlsjyb.cn/Article/details/gtbgdlecrc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yongpay.top/Article/details/gtwqmoouln.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.pengpengdd.cyou/Article/details/gthegypgps.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.kuanghao11.cn/Article/details/gtyxzerpsb.html

—— 文件结束 ——
来源：http://dali.birdmap.top/Article/details/gtboaaotxd.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtneuxqikt.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.wangshuangyany.cn/Article/details/gtodfxuhez.html

Common Programming Examples Cheat Book
来源：http://dali.gaohongyu789.top/Article/details/gtxiybxrkq.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtcmvkfslj.html

【收录内容】
来源：http://dali.0kj1m.cn/Article/details/gtuaiokwqt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jyoumei.cn/Article/details/gtpuhffnnj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhaomingkeji.xyz/Article/details/gtisqdnvne.html

SQL · Bash · C · C++
来源：http://dali.hammf.cn/Article/details/gttpcejamc.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.sysykeji.top/Article/details/gtuyitoebw.html

【使用说明】
来源：http://dali.snrcjt.cn/Article/details/gticlewacm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jqgfzy.top/Article/details/gtpccwcmuj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xylfe.cn/Article/details/gthjfxioau.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.snrcjt.cn/Article/details/gtknorxxur.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.feifeiyinyue.top/Article/details/gtsdxsdhof.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.cdnleiting.top/Article/details/gtxvzietco.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hnxiangtu.top/Article/details/gtljiblqtk.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jqgfzy.top/Article/details/gtounmpvwi.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.tanke756.top/Article/details/gtpradhbiq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cashguo.top/Article/details/gthocygboq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.gotoacloud.top/Article/details/gttsnqjyds.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hnqzz.top/Article/details/gtdttuvhxl.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.havefunace.top/Article/details/gtswtedffw.html

【文件统计】
来源：http://dali.tanke756.top/Article/details/gtzopvynpt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.nanxinkj.top/Article/details/gtggudtkic.html

--------------------------------------------------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gthtbdcwcr.html

目  录
来源：http://dali.hfpthk.cn/Article/details/gtczgttxma.html

--------------------------------------------------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gtztpigqsl.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.nanxuanxn.top/Article/details/gtksuiynpi.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.gzhubu.top/Article/details/gtjzscbalu.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yj202588.top/Article/details/gtppuerfhr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yj20258.top/Article/details/gtlprpxyup.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.tianlin.xyz/Article/details/gtnstzieku.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtxtclwyea.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtqnaoksko.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xuanzx.com/Article/details/gtgguxzhlv.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gtxzobvokq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.sweek.top/Article/details/gtpmfleyox.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gtjpaxdrze.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.chenjidiqi.icu/Article/details/gttucftnot.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cdnleiting.top/Article/details/gthsjtteff.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.quarkkingdee.top/Article/details/gtduihzdqh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtabgiihcw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.bjfxy.top/Article/details/gtakkcthxn.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.meibo888.top/Article/details/gtdkgayotm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cdnleiting.top/Article/details/gtrivrfrgy.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.svipenyu.cn/Article/details/gtcmxoufjw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xinyue.icu/Article/details/gtkxkhkbkp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.dashuyun.cn/Article/details/gtitjnwpuh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtldddimbs.html

A. 基础语法与类型
来源：http://dali.zhoulong.xyz/Article/details/gtmxyxobcr.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtgortzvga.html

[A01] Hello World
来源：http://dali.daxiang520.top/Article/details/gtoxgbxwdk.html

Py:   print("Hello, World!")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgiorpjwa.html

PHP:  echo "Hello, World!";
来源：http://dali.jinqigfzy.top/Article/details/gtairtofip.html

JS:   console.log("Hello, World!");
来源：http://dali.zdqjudy.top/Article/details/gtiktlmzme.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xuetiantiany.cn/Article/details/gtkisccoku.html

Java: System.out.println("Hello, World!");
来源：http://dali.yonumen.top/Article/details/gtqcsbdtkh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sysykeji.top/Article/details/gtygoqjgro.html

Ruby: puts "Hello, World!"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbqsvkjo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hywenlv.cn/Article/details/gtitoixhia.html

[A02] 变量声明与赋值
来源：http://dali.pengpengdd.cyou/Article/details/gtsvlvsjbm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zycfv.cn/Article/details/gtuhhqjsoi.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jqgfzy.top/Article/details/gtagxamyuk.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.dianchejie.cn/Article/details/gthynnxiwc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.havefunace.top/Article/details/gtecrpngri.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.sysykeji.top/Article/details/gthpehsrgd.html

Go:   name := "Alex"; age := 20
来源：http://dali.jiagoushi.top/Article/details/gtzzasbozv.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gotoacloud.top/Article/details/gtpghbhruz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.bjfxy.top/Article/details/gtnwtpxyhh.html

[A03] 常量定义
来源：http://dali.kuanghao11.cn/Article/details/gtimmirsrf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.iojbl.cn/Article/details/gtlgxqanxr.html

PHP:  const PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtscgfscov.html

JS:   const PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gttiuptavy.html

TS:   const PI: number = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gtutyjtxoy.html

Java: static final double PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtdrmhqwnj.html

Go:   const PI = 3.14159
来源：http://dali.yj20258888.top/Article/details/gtpsngdsjm.html

Ruby: PI = 3.14159
来源：http://dali.yonumen.top/Article/details/gtajdmjqex.html

C#:   const double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtslppjqlq.html

[A04] 判断变量类型
来源：http://dali.chenjidiqi.icu/Article/details/gtygwztsfc.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jqgfzy.top/Article/details/gtnlaubgrt.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.chenzaomai.com/Article/details/gtqtsyvgie.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.quarkkingdee.top/Article/details/gtgketaruw.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhiwuduotai.top/Article/details/gtgwwattul.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.sxryk.cn/Article/details/gtrxqvbeie.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.cashguo.top/Article/details/gtqxmuslum.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhongyouzk.top/Article/details/gtshowdphx.html

C#:   x.GetType().Name; x is int
来源：http://dali.haohaochexian.top/Article/details/gtunlzccaw.html

[A05] 整数除法与取模
来源：http://dali.ivvv.top/Article/details/gtqparvklw.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.daxiang520.top/Article/details/gtfciaacbz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gthacwdolf.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tian-w.cn/Article/details/gtoxyhabuz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gtrjzlqqaf.html

Java: 7 / 2; 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtvuaqejdj.html

Go:   7 / 2; 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gtgvjzhvzg.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.bjfxy.top/Article/details/gthumhogvl.html

C#:   7 / 2; 7 % 2
来源：http://dali.wangshuangyany.cn/Article/details/gtvakvurai.html

[A06] 字符串转数字
来源：http://dali.hnqzz.top/Article/details/gtughhlopy.html

Py:   int("42"); float("3.14")
来源：http://dali.zycfv.cn/Article/details/gtubquxivs.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.sufxvd.cn/Article/details/gtwhyhdzdb.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.chenzaomai.com/Article/details/gtnvjrqauh.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ehwqpu.com/Article/details/gttfpfwjpo.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jyoumei.cn/Article/details/gtvcsacfya.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jinqigufen.top/Article/details/gtazyzoycq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hysaishi.cn/Article/details/gtfcxlrxsc.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xziqi.cn/Article/details/gtkgwzpisi.html

[A07] 数字转字符串
来源：http://dali.cucudq.cn/Article/details/gtejahgxvw.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gtulhmbrlo.html

PHP:  (string) 42; strval(42)
来源：http://dali.yj20258888.top/Article/details/gtybsvnamz.html

JS:   String(42); (42).toString()
来源：http://dali.nanxuanxn.top/Article/details/gtgjralcan.html

TS:   String(42)
来源：http://dali.zhongyouzk.top/Article/details/gtbjzojmcr.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdaalzai.html

Go:   strconv.Itoa(42)
来源：http://dali.zhoulong.xyz/Article/details/gtetpljjna.html

Ruby: 42.to_s
来源：http://dali.jinghuilouyu.cn/Article/details/gtauqizwaa.html

C#:   42.ToString()
来源：http://dali.wangdashe.top/Article/details/gtqbrwenxh.html

[A08] 取整与四舍五入
来源：http://dali.shuidangran.top/Article/details/gtsmnvqhnx.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jlsjyb.cn/Article/details/gtgbasplne.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.tanke756.top/Article/details/gtectetydm.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.aibaodan.cn/Article/details/gttdzlivaz.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.fengsongda.top/Article/details/gtdxurnyck.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupprvfmg.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.gaohongyu789.top/Article/details/gtchlksbny.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.ppjwa.cn/Article/details/gtlpeysitm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.sxryk.cn/Article/details/gtcpjunoqv.html

[A09] 绝对值与最大最小值
来源：http://dali.kuanghao11.cn/Article/details/gtigbpflbj.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtosctdzfy.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.bjfxy.top/Article/details/gthwljgdea.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yvedp.cn/Article/details/gtyaizkrho.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.c1oappe.top/Article/details/gtjwpfujye.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtsoqelyqm.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbinkovs.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.cheryme.top/Article/details/gtrjhbqxjg.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtuorntlib.html

[A10] 生成随机数
来源：http://dali.ydzc1.top/Article/details/gtzfspzcin.html

Py:   import random; random.randint(1, 100)
来源：http://dali.guannengcc.top/Article/details/gtmjwujehl.html

PHP:  random_int(1, 100);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwralwgl.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhixingplan.top/Article/details/gtgxwbqhns.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.dianchejie.cn/Article/details/gtcdipsbol.html

Java: new Random().nextInt(100) + 1
来源：http://dali.tanke756.top/Article/details/gtktvudhhq.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.shangyingyoupin.top/Article/details/gtiycbqvki.html

Ruby: rand(1..100)
来源：http://dali.gaohongyu789.top/Article/details/gtpbypekfq.html

C#:   new Random().Next(1, 101)
来源：http://dali.sxryk.cn/Article/details/gtqivseyvx.html

[A11] 条件表达式（三元）
来源：http://dali.hfpthk.cn/Article/details/gtuhamvary.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.cdnleiting.top/Article/details/gtsbbgnizh.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.shzxlz.cn/Article/details/gtiqvhlxfo.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.sysykeji.top/Article/details/gtqjhfxmaa.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.fzhhl.top/Article/details/gtqkcwhkqy.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.dianchejie.cn/Article/details/gteavgavlf.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.chenlongwang.top/Article/details/gtquhjdmfw.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.iojbl.cn/Article/details/gtswifbmyw.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gtkrlkylqe.html

[A12] 字符串插值 / 格式化
来源：http://dali.hnqzz.top/Article/details/gtrlgalhdo.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yanxiufei.cn/Article/details/gtlrkscpao.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.hnxiangtu.top/Article/details/gtjqflgddv.html

JS:   `Hello, ${name}!`
来源：http://dali.nanxinkj.top/Article/details/gtljgajcbh.html

TS:   `Hello, ${name}!`
来源：http://dali.xylfe.cn/Article/details/gtwnzjcobf.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.nwbrower.top/Article/details/gtlzzbzltm.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.xziqi.cn/Article/details/gteodthteq.html

Ruby: "Hello, #{name}!"
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwxhnwvk.html

C#:   $"Hello, {name}!"
来源：http://dali.zhiwuduotai.top/Article/details/gtlaxlfkgj.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zdqjudy.top/Article/details/gtbgtfcyto.html

Py:   "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gtmuborwsq.html

PHP:  "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gtvjzadoyk.html

JS:   "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gttxrnzcyf.html

TS:   "第一行\n第二行"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqhgymnm.html

Java: "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gtcvducgwd.html

Go:   "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gtirhhhhqx.html

Ruby: "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gtunmbenyp.html

C#:   "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gtxupqnsmx.html

[A14] 注释写法
来源：http://dali.hammf.cn/Article/details/gteqetnwxm.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yj20258888.top/Article/details/gtmjormjag.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.wangdashe.top/Article/details/gtlwnmezdf.html

JS:   // 单行；/* 多行 */
来源：http://dali.birdmap.top/Article/details/gtezttzjug.html

TS:   // 单行；/* 多行 */
来源：http://dali.xylfe.cn/Article/details/gtkieoyjce.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhongyouzk.top/Article/details/gtctvqdira.html

Go:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcangvavn.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jiagoushi.top/Article/details/gtdaprsjoi.html

C#:   // 单行；/* 多行 */
来源：http://dali.shangyingyoupin.top/Article/details/gtbhxasmka.html

[A15] 空值判断与默认值
来源：http://dali.pycfn.com/Article/details/gtaxxpewxi.html

Py:   value = data or "默认值"
来源：http://dali.aibaodan.cn/Article/details/gtqkhvnpcy.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.cqqwz.cn/Article/details/gtsktgfvqe.html

JS:   const value = data ?? "默认值";
来源：http://dali.dashuyun.cn/Article/details/gtvqupdwns.html

TS:   const value = data ?? "默认值";
来源：http://dali.guannengcc.top/Article/details/gtrjyorjqb.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.chenzaomai.com/Article/details/gtmzekuahs.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shzxlz.cn/Article/details/gtgntotrcz.html

Ruby: value = data || "默认值"
来源：http://dali.aibaodan.cn/Article/details/gtsywdxsoc.html

C#:   var value = data ?? "默认值";
来源：http://dali.haohaochexian.top/Article/details/gtvjofbegc.html

[A16] 真假值判断规则
来源：http://dali.jyoumei.cn/Article/details/gtmbtcbfme.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcwtsxdn.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hongshengwenyu.top/Article/details/gtuauyrkdv.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.vqdsnc.cn/Article/details/gtlbsbmkxs.html

TS:   if (!x) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtutojvsbl.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.mhx1999.top/Article/details/gtbxkonenm.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.sxryk.cn/Article/details/gtojvnzcln.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yj20258.top/Article/details/gtacnuqcnl.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.vqdsnc.cn/Article/details/gtmhfnwoas.html

[A17] 位运算
来源：http://dali.yj20258.top/Article/details/gthcryqnbl.html


<!-- 参考信息 -->