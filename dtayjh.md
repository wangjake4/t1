代发 wailian999

[U93] JS：模板字符串
来源：http://dali.svipenyu.cn/Article/details/gtrwqkbfjg.html

`共 ${n} 条`
来源：http://dali.hongshengwenyu.top/Article/details/gtwzzfhdab.html

[U94] JS：箭头函数
来源：http://dali.bjfxy.top/Article/details/gtfcmmlohf.html

const double = x => x * 2;
来源：http://dali.jiagoushi.top/Article/details/gtfwbmpugv.html

[U95] JS：Promise 包装
来源：http://dali.gzhubu.top/Article/details/gtmulslbbg.html

new Promise((resolve, reject) => {})
来源：http://dali.hywenlv.cn/Article/details/gtkzpjyypm.html

[U96] JS：async/await 与异常
来源：http://dali.daxiang520.top/Article/details/gtzmfurrxb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtjrtgjchw.html

[U97] JS：并发请求
来源：http://dali.yj202588.top/Article/details/gttozituag.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gtnujoemaj.html

[U98] JS：fetch 带 JSON
来源：http://dali.birdmap.top/Article/details/gtiegdzcqw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shangyingyoupin.top/Article/details/gtskkwszdd.html

[U99] JS：事件监听
来源：http://dali.andypj.xyz/Article/details/gtupuwconh.html

el.addEventListener("click", e => {})
来源：http://dali.meibo888.top/Article/details/gtufrlocqz.html

[U100] JS：DOM 查询
来源：http://dali.guowangkeji.top/Article/details/gtsnlgdgix.html

document.querySelector(".item")
来源：http://dali.jinqigfzy.top/Article/details/gtrqzbtadx.html

[U101] JS：classList 操作
来源：http://dali.hammf.cn/Article/details/gtqhwmmhml.html

el.classList.toggle("active")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxpoqkcrg.html

[U102] JS：本地存储
来源：http://dali.yonumen.top/Article/details/gtiftwhbtb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hammf.cn/Article/details/gtltrlugda.html

[U103] JS：定时器
来源：http://dali.sysykeji.top/Article/details/gtqwdslhxl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.pengpengdd.cyou/Article/details/gtzftuwoje.html

[U104] JS：防抖
来源：http://dali.hywenlv.cn/Article/details/gtdwttryhd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gtnmjecsav.html

[U105] JS：节流
来源：http://dali.wangshuangyany.cn/Article/details/gttrfkxmex.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yongpay.top/Article/details/gtnjgthyug.html

[U106] JS：日期格式化
来源：http://dali.yongpay.top/Article/details/gtwzxzcmbz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.nwbrower.top/Article/details/gtgiplvjyp.html

[U107] JS：数字千分位
来源：http://dali.zycfv.cn/Article/details/gtlbmligcn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gtpgkpcwfn.html

[U108] JS：随机整数
来源：http://dali.redwolf501.top/Article/details/gteexilock.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.meibo888.top/Article/details/gtvmwyqsrt.html

[U109] JS：数组分组
来源：http://dali.yuanzhike.top/Article/details/gtzndklslj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.dianchejie.cn/Article/details/gtasmlxtdp.html

[U110] JS：数组分块
来源：http://dali.iojbl.cn/Article/details/gtpskaxbhg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xuanzx.com/Article/details/gtvwppttgs.html

[U111] JS：对象转 Map
来源：http://dali.zhiwuduotai.top/Article/details/gtpwxbvymc.html

new Map(Object.entries(obj))
来源：http://dali.fengsongda.top/Article/details/gtockmmygi.html

[U112] JS：字符串补位
来源：http://dali.pengpengdd.cyou/Article/details/gtahinvfrz.html

"7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtmbenpbed.html

[U113] JS：正则替换全部
来源：http://dali.hammf.cn/Article/details/gtvbailqfm.html

s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtibtvwygi.html

[U114] JS：JSON 深比较
来源：http://dali.andypj.xyz/Article/details/gtakkwvzjp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigfzy.top/Article/details/gtweihccsc.html

[U115] JS：生成 UUID
来源：http://dali.yj20258888.top/Article/details/gtmpwdmwbr.html

crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gtjeistmlb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gzhubu.top/Article/details/gtwboirsfh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtofumhcty.html

[U117] JS：单元测试
来源：http://dali.haohaochexian.top/Article/details/gtqmpjcqux.html

npm i -D vitest;  npx vitest
来源：http://dali.daxiang520.top/Article/details/gtlvnrmfae.html

[U118] JS：开发服务器
来源：http://dali.ybcxt.top/Article/details/gtwbwgypdu.html

npm i -D vite;  npx vite
来源：http://dali.shuidangran.top/Article/details/gtyjdznxha.html

[U119] JS：生产构建
来源：http://dali.jiagoushi.top/Article/details/gtyozvnhcf.html

npx vite build
来源：http://dali.hywenlv.cn/Article/details/gtaqjxhcbd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.nwbrower.top/Article/details/gtoyltbkgl.html

import.meta.env.VITE_API_URL
来源：http://dali.redwolf501.top/Article/details/gtxnrosczj.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtxnqnjdsi.html

统计汇总
来源：http://dali.xinyue.icu/Article/details/gttftrdwne.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtsejtqyee.html

按语言统计（条）：
来源：http://dali.daxiang520.top/Article/details/gtemzmkhsw.html

Python ......... 252
来源：http://dali.nanxuanxn.top/Article/details/gtotjdhzsh.html

PHP ............ 252
来源：http://dali.hfpthk.cn/Article/details/gtacowmkil.html

JavaScript ..... 252
来源：http://dali.andypj.xyz/Article/details/gtaixdsyoi.html

TypeScript ..... 212
来源：http://dali.daria6918.cn/Article/details/gtbazsyvui.html

Java ........... 212
来源：http://dali.zdqjudy.top/Article/details/gtodzztoru.html

Go ............. 212
来源：http://dali.jqgfzy.top/Article/details/gtzosityho.html

Ruby ........... 212
来源：http://dali.yuxming.cn/Article/details/gtehwtnsie.html

C# ............. 212
来源：http://dali.ehwqpu.com/Article/details/gtknujmnfy.html

C .............. 30
来源：http://dali.iojbl.cn/Article/details/gtlajjudga.html

C++ ............ 30
来源：http://dali.daxiang520.top/Article/details/gtschcbgyg.html

SQL ............ 90
来源：http://dali.jyoumei.cn/Article/details/gtlmepuibx.html

Bash ........... 80
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyelcseyh.html

Kotlin ......... 15
来源：http://dali.ivvv.top/Article/details/gtsdvcbsyy.html

Swift .......... 15
来源：http://dali.haohaochexian.top/Article/details/gttslwnkyx.html

Lua ............ 10
来源：http://dali.yvedp.cn/Article/details/gtdeqmnlml.html

Perl ........... 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypararsm.html

Scala .......... 10
来源：http://dali.zhiwuduotai.top/Article/details/gthwnuzfyi.html

------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gtyyslqdov.html

合计 ........... 2106 条
来源：http://dali.yuanzhike.top/Article/details/gtloclhags.html

按章节统计：
来源：http://dali.sysykeji.top/Article/details/gtxrcdkvor.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yj20258.top/Article/details/gtsbkagbqi.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxgssxwi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gttkvryxxr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yj20258.top/Article/details/gtvzlzvzov.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.316326.xyz/Article/details/gtqsontnfs.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hnxiangtu.top/Article/details/gtnkjsqjhy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hnxiangtu.top/Article/details/gttjgjlwrq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.sweek.top/Article/details/gtyiapmqsb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gtbzavthoz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gzhubu.top/Article/details/gtayxnkply.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gtlkjnuddi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gtgefollsz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gtgmrsphco.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.guowangkeji.top/Article/details/gtnnnhowyd.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.smart0.xyz/Article/details/gtkwedlsdl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gtpileyhra.html

Q SQL 专题                              90
来源：http://dali.kuanghao11.cn/Article/details/gtnlomnlff.html

R Bash 专题                             80
来源：http://dali.gzhubu.top/Article/details/gtllcwimjk.html

S C / C++ 专题                          60
来源：http://dali.kuanghao11.cn/Article/details/gtrllrsvcu.html

T 其他语言补充                          60
来源：http://dali.ybcxt.top/Article/details/gtyczjyowx.html

U 高频实用片段                         120
来源：http://dali.zhongyouzk.top/Article/details/gtgvorjkfg.html

------------------------------------
来源：http://dali.redwolf501.top/Article/details/gtcwwvindg.html

合计                                  2106 条
来源：http://dali.zhiwuduotai.top/Article/details/gtdrymbwsp.html

--------------------------------------------------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gtupotqskt.html

使用提醒
来源：http://dali.hysaishi.cn/Article/details/gtzebvlxwo.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gtkiqggftg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.tanke756.top/Article/details/gtswczqyow.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cdnleiting.top/Article/details/gtgqfulwgu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.aizwys.cn/Article/details/gtougpitbk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.wangshuangyany.cn/Article/details/gtnkewtrzc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.redwolf501.top/Article/details/gtdoflderp.html

—— 文件结束 ——
来源：http://dali.316326.xyz/Article/details/gtzbnllotu.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtjuaacjxg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.iojbl.cn/Article/details/gttnhbqacx.html

Common Programming Examples Cheat Book
来源：http://dali.daxiang520.top/Article/details/gtdkxbopmz.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtlmakaihu.html

【收录内容】
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwnabhis.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.316326.xyz/Article/details/gtvyoqlrtz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gtbbwetzti.html

SQL · Bash · C · C++
来源：http://dali.tanke756.top/Article/details/gtfauaigys.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.pengpengdd.cyou/Article/details/gtnszlxaxx.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gtdqiqvnfh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.sysykeji.top/Article/details/gtyqrnurqv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.cucudq.cn/Article/details/gtkoqxatuj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zycfv.cn/Article/details/gtvhqaqbmm.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yonumen.top/Article/details/gtvffxxdkw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yuanzhike.top/Article/details/gtnvkqoara.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.haohaochexian.top/Article/details/gtesrrhlqn.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jlsjyb.cn/Article/details/gtzwbinfle.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.daria6918.cn/Article/details/gtcziorpix.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.birdmap.top/Article/details/gtdunttezh.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfldzjqh.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.tianlin.xyz/Article/details/gtrctzepjc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yongpay.top/Article/details/gtfjmkgtnp.html

【文件统计】
来源：http://dali.jyoumei.cn/Article/details/gtfakpnuwn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.daxiang520.top/Article/details/gtenurutlt.html

--------------------------------------------------------------------------------
来源：http://dali.xylfe.cn/Article/details/gtutbiiuzl.html

目  录
来源：http://dali.hfpthk.cn/Article/details/gtfkqkmglc.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gtepfekxry.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.fzhhl.top/Article/details/gtkadqtfsp.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jinqigfzy.top/Article/details/gtlgcnmsaj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yonumen.top/Article/details/gtryvxlahp.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.chenlongwang.top/Article/details/gtoyplirea.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtmynnanrt.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtjhzssmld.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yvedp.cn/Article/details/gtgqthnbxc.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.dashuyun.cn/Article/details/gtmbohacvk.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gtulyvtbls.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.sysykeji.top/Article/details/gtrcdcwcfu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jyoumei.cn/Article/details/gtzwgwffup.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.gotoacloud.top/Article/details/gtcatxsbhq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhixingplan.top/Article/details/gtgshmhnyw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.cucudq.cn/Article/details/gtignzfpwo.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.chenzaomai.com/Article/details/gtlobyftch.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gtnxxaxyai.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cdnleiting.top/Article/details/gthdsvzaqz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.birdmap.top/Article/details/gtlnrgqhzh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtjxragqvo.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aibaodan.cn/Article/details/gtlfspxycg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.dashuyun.cn/Article/details/gtpabecigi.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtgqznazcl.html

A. 基础语法与类型
来源：http://dali.nanxuanxn.top/Article/details/gtyxjcqdlj.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtgsbnpkou.html

[A01] Hello World
来源：http://dali.birdmap.top/Article/details/gtbbxpiztr.html

Py:   print("Hello, World!")
来源：http://dali.jyoumei.cn/Article/details/gtutlvmykk.html

PHP:  echo "Hello, World!";
来源：http://dali.pengpengdd.cyou/Article/details/gtcpwnahpb.html

JS:   console.log("Hello, World!");
来源：http://dali.hysaishi.cn/Article/details/gtoehwzqgp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmsxwlzoh.html

Java: System.out.println("Hello, World!");
来源：http://dali.haohaochexian.top/Article/details/gtarfqyerj.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.0kj1m.cn/Article/details/gtndbavpbf.html

Ruby: puts "Hello, World!"
来源：http://dali.zhiwuduotai.top/Article/details/gtsqekuxam.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.andypj.xyz/Article/details/gtpdiemqxr.html

[A02] 变量声明与赋值
来源：http://dali.zhixingplan.top/Article/details/gtexemrrmc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sxryk.cn/Article/details/gtqgroxujt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.wangdashe.top/Article/details/gtbetwdfne.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zdqjudy.top/Article/details/gtikhbimmx.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.aizwys.cn/Article/details/gtfeqjtfgq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.daria6918.cn/Article/details/gtxbwoehiv.html

Go:   name := "Alex"; age := 20
来源：http://dali.sweek.top/Article/details/gtjozjeceb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.sysykeji.top/Article/details/gtxccwrdiu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.svipenyu.cn/Article/details/gtpqaemdxq.html

[A03] 常量定义
来源：http://dali.havefunace.top/Article/details/gtrweqchvt.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozllrnvx.html

PHP:  const PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtjoayqxcn.html

JS:   const PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtgkwejnqw.html

TS:   const PI: number = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtgdskpnvp.html

Java: static final double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtkpihjhsy.html

Go:   const PI = 3.14159
来源：http://dali.sxryk.cn/Article/details/gtuhuphzgq.html

Ruby: PI = 3.14159
来源：http://dali.gzhubu.top/Article/details/gtlqejkijf.html

C#:   const double PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtgqpljhbb.html

[A04] 判断变量类型
来源：http://dali.meibo888.top/Article/details/gtadmzqbzf.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.316326.xyz/Article/details/gtszdcdade.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jlsjyb.cn/Article/details/gtfrmrltue.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.redwolf501.top/Article/details/gtnjcvpzqk.html

TS:   typeof x; x instanceof Date
来源：http://dali.yj202588.top/Article/details/gtzvruqecg.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhixingplan.top/Article/details/gtdrptekbc.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hysaishi.cn/Article/details/gthclykhkm.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.sufxvd.cn/Article/details/gtbqkkbmyp.html

C#:   x.GetType().Name; x is int
来源：http://dali.sysykeji.top/Article/details/gtodffgnxf.html

[A05] 整数除法与取模
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihhjtzfr.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yueranfly.top/Article/details/gtmvjzuvwd.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.wangdashe.top/Article/details/gttqhvlskn.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gtkzfjwebw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gtrvnnrlge.html

Java: 7 / 2; 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gtuwpyfabf.html

Go:   7 / 2; 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gtipnbgaef.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gttzhrfjgx.html

C#:   7 / 2; 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtfiysjxbf.html

[A06] 字符串转数字
来源：http://dali.hnxiangtu.top/Article/details/gtgmczxvlx.html

Py:   int("42"); float("3.14")
来源：http://dali.tianlin.xyz/Article/details/gtsgfsttul.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yueranfly.top/Article/details/gtqoqwioit.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.aibaodan.cn/Article/details/gtaomtqoyt.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hnxiangtu.top/Article/details/gtnuyxmgqy.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.birdmap.top/Article/details/gtypuzkzzp.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.fzhhl.top/Article/details/gtzcrcouqv.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.sufxvd.cn/Article/details/gtdqsbfjtt.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.iojbl.cn/Article/details/gtnhpkazfi.html

[A07] 数字转字符串
来源：http://dali.gogol.net.cn/Article/details/gtejpjbncc.html

Py:   str(42)
来源：http://dali.jqgfzy.top/Article/details/gttkcqgrck.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhiwuduotai.top/Article/details/gtponzxgmx.html

JS:   String(42); (42).toString()
来源：http://dali.xylfe.cn/Article/details/gtvejnmxum.html

TS:   String(42)
来源：http://dali.havefunace.top/Article/details/gtptrcdhqd.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yanxiufei.cn/Article/details/gtckmgrljm.html

Go:   strconv.Itoa(42)
来源：http://dali.cashguo.top/Article/details/gtzodaujiu.html

Ruby: 42.to_s
来源：http://dali.dianchejie.cn/Article/details/gtihkhfvbf.html

C#:   42.ToString()
来源：http://dali.gotoacloud.top/Article/details/gtdfhxxmlv.html

[A08] 取整与四舍五入
来源：http://dali.yueranfly.top/Article/details/gtdmifsbag.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.cqqwz.cn/Article/details/gttfwkgeay.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.chenlongwang.top/Article/details/gtmgqlxdul.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zdqjudy.top/Article/details/gtzhvxvqqj.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.cheryme.top/Article/details/gtxmnregur.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.ivvv.top/Article/details/gtiygdcpdl.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.sufxvd.cn/Article/details/gtqimufdyk.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhixingplan.top/Article/details/gtlxyybabh.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.fengsongda.top/Article/details/gtsrveaphk.html

[A09] 绝对值与最大最小值
来源：http://dali.gotoacloud.top/Article/details/gtkwsajwiq.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yuxming.cn/Article/details/gtbdtynqkb.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtnkxxnkro.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.xinyue.icu/Article/details/gtuqaepqkd.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gtuldvzbxy.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtgjqojudy.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hnqzz.top/Article/details/gtyhdwtygn.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.aibaodan.cn/Article/details/gtoznzjkpo.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gtussdzeyo.html

[A10] 生成随机数
来源：http://dali.guannengcc.top/Article/details/gtpbvfbazz.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yuanzhike.top/Article/details/gtydklnhrz.html

PHP:  random_int(1, 100);
来源：http://dali.jqgufenzy.top/Article/details/gtrhajqmzu.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.nanxuanxn.top/Article/details/gtohkyktgx.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cheryme.top/Article/details/gtqfjmzmut.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbrdzpgab.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.guannengcc.top/Article/details/gtxydtjjrc.html

Ruby: rand(1..100)
来源：http://dali.daria6918.cn/Article/details/gtwubuazsn.html

C#:   new Random().Next(1, 101)
来源：http://dali.ehwqpu.com/Article/details/gtjmmznvej.html

[A11] 条件表达式（三元）
来源：http://dali.cqqwz.cn/Article/details/gtskdeotpq.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.shangyingyoupin.top/Article/details/gtekhbtnrg.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.ydzc1.top/Article/details/gtysxxessl.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jlsjyb.cn/Article/details/gtpnxvivdx.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvwfolzm.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.smart0.xyz/Article/details/gtxlrkbwde.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yongpay.top/Article/details/gtrovbzqyy.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yongpay.top/Article/details/gtpwnrqogx.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.hammf.cn/Article/details/gtafrgtgit.html

[A12] 字符串插值 / 格式化
来源：http://dali.dianchejie.cn/Article/details/gtwqfvbvup.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.bjfxy.top/Article/details/gtsolrkezl.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.hysaishi.cn/Article/details/gtokmtfhwc.html

JS:   `Hello, ${name}!`
来源：http://dali.nanxuanxn.top/Article/details/gteegvrpbi.html

TS:   `Hello, ${name}!`
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjydttlp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jinqigufen.top/Article/details/gtjmmcspck.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.hammf.cn/Article/details/gtulbelryp.html

Ruby: "Hello, #{name}!"
来源：http://dali.jinghuilouyu.cn/Article/details/gtbeonpkhr.html

C#:   $"Hello, {name}!"
来源：http://dali.smart0.xyz/Article/details/gtsubyyolo.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.shangyingyoupin.top/Article/details/gtrgfqaxxq.html

Py:   "第一行\n第二行"
来源：http://dali.nanxinkj.top/Article/details/gttvijoltl.html

PHP:  "第一行\n第二行"
来源：http://dali.wangdashe.top/Article/details/gtlysbpkln.html

JS:   "第一行\n第二行"
来源：http://dali.zhengqikj.top/Article/details/gtqchbribi.html

TS:   "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gtxbmsmcns.html

Java: "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gtajqfexfk.html

Go:   "第一行\n第二行"
来源：http://dali.pengpengdd.cyou/Article/details/gterkmllsp.html

Ruby: "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gtcsmgeqjx.html

C#:   "第一行\n第二行"
来源：http://dali.sysykeji.top/Article/details/gtrnvmsbns.html

[A14] 注释写法
来源：http://dali.hnqzz.top/Article/details/gtofrglxuu.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jlsjyb.cn/Article/details/gtupibiltp.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccceeomy.html

JS:   // 单行；/* 多行 */
来源：http://dali.chenjidiqi.icu/Article/details/gtzjlrozqa.html

TS:   // 单行；/* 多行 */
来源：http://dali.redwolf501.top/Article/details/gtklgeaxyj.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jinqigufen.top/Article/details/gtvokanslf.html

Go:   // 单行；/* 多行 */
来源：http://dali.xylfe.cn/Article/details/gtquihlquo.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.pycfn.com/Article/details/gtiejncqpp.html

C#:   // 单行；/* 多行 */
来源：http://dali.tian-w.cn/Article/details/gthmdcjjrj.html

[A15] 空值判断与默认值
来源：http://dali.redwolf501.top/Article/details/gttghqswjk.html

Py:   value = data or "默认值"
来源：http://dali.nanxinkj.top/Article/details/gtczjiphnb.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.dashuyun.cn/Article/details/gtmkyenaow.html

JS:   const value = data ?? "默认值";
来源：http://dali.ybcxt.top/Article/details/gtesimnqwj.html

TS:   const value = data ?? "默认值";
来源：http://dali.yj20258888.top/Article/details/gtmnjyrysz.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.cashguo.top/Article/details/gtaxccwxki.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.nanxinkj.top/Article/details/gtikxvndha.html

Ruby: value = data || "默认值"
来源：http://dali.shzxlz.cn/Article/details/gtrlywnhoh.html

C#:   var value = data ?? "默认值";
来源：http://dali.guannengcc.top/Article/details/gttppmnjwp.html

[A16] 真假值判断规则
来源：http://dali.hammf.cn/Article/details/gtkfmvcpfy.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yongpay.top/Article/details/gtfjxaqoak.html


<!-- 参考信息 -->