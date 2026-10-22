代发 wailian999

[U97] JS：并发请求
来源：http://dali.c1oappe.top/Article/details/gtswjiuuvr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtzuretwkc.html

[U98] JS：fetch 带 JSON
来源：http://dali.hysaishi.cn/Article/details/gtngohpjsd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.smart0.xyz/Article/details/gtpshvntje.html

[U99] JS：事件监听
来源：http://dali.wangdashe.top/Article/details/gtkjywtzph.html

el.addEventListener("click", e => {})
来源：http://dali.birdmap.top/Article/details/gtbeayxyvq.html

[U100] JS：DOM 查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnzojpvv.html

document.querySelector(".item")
来源：http://dali.jqgfzy.top/Article/details/gttrzqlvlx.html

[U101] JS：classList 操作
来源：http://dali.pycfn.com/Article/details/gtjtzzhskb.html

el.classList.toggle("active")
来源：http://dali.zhoulong.xyz/Article/details/gtuworgyst.html

[U102] JS：本地存储
来源：http://dali.jlsjyb.cn/Article/details/gtxfxydmul.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sxryk.cn/Article/details/gtzwxbdebu.html

[U103] JS：定时器
来源：http://dali.cqqwz.cn/Article/details/gtctysppxt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvknrvbiv.html

[U104] JS：防抖
来源：http://dali.guannengcc.top/Article/details/gthndwfeer.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gtxdzzswnq.html

[U105] JS：节流
来源：http://dali.ehwqpu.com/Article/details/gtudfzwstz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yj20258.top/Article/details/gthslqkthm.html

[U106] JS：日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycfwgbdn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.fengsongda.top/Article/details/gtsvlgxrmk.html

[U107] JS：数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gtsqmixdlp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.pycfn.com/Article/details/gtfplstqej.html

[U108] JS：随机整数
来源：http://dali.tanke756.top/Article/details/gtshgxayls.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ivvv.top/Article/details/gtuwlzsjya.html

[U109] JS：数组分组
来源：http://dali.daxiang520.top/Article/details/gtmvgzmomz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.dianchejie.cn/Article/details/gtzulknelq.html

[U110] JS：数组分块
来源：http://dali.sufxvd.cn/Article/details/gtqyncgtkk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xuetiantiany.cn/Article/details/gtnrtyscbx.html

[U111] JS：对象转 Map
来源：http://dali.yj20258.top/Article/details/gtmnofchqf.html

new Map(Object.entries(obj))
来源：http://dali.316326.xyz/Article/details/gtjkkrcpqj.html

[U112] JS：字符串补位
来源：http://dali.yanxiufei.cn/Article/details/gtuqqjxenr.html

"7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtoudgryky.html

[U113] JS：正则替换全部
来源：http://dali.aizwys.cn/Article/details/gtmrkqjbdi.html

s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtbtkdxwgn.html

[U114] JS：JSON 深比较
来源：http://dali.yuanzhike.top/Article/details/gtkzlveraw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgfzy.top/Article/details/gtwpssxhhf.html

[U115] JS：生成 UUID
来源：http://dali.yongpay.top/Article/details/gtynhydtmj.html

crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gtjfgqqorb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgotweful.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yonumen.top/Article/details/gtuxicbjxn.html

[U117] JS：单元测试
来源：http://dali.birdmap.top/Article/details/gtdnjwdjnj.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gtdoqsmbja.html

[U118] JS：开发服务器
来源：http://dali.jyoumei.cn/Article/details/gtyjakyzrk.html

npm i -D vite;  npx vite
来源：http://dali.ehwqpu.com/Article/details/gtkvqiefjd.html

[U119] JS：生产构建
来源：http://dali.hnxiangtu.top/Article/details/gtvhdmgbsr.html

npx vite build
来源：http://dali.tanke756.top/Article/details/gtemjocwrg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hywenlv.cn/Article/details/gtbhxkzjmj.html

import.meta.env.VITE_API_URL
来源：http://dali.jyoumei.cn/Article/details/gtjxsgvflq.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtwefbqbcp.html

统计汇总
来源：http://dali.sxryk.cn/Article/details/gtjrhxhceu.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtkllcigxk.html

按语言统计（条）：
来源：http://dali.dashuyun.cn/Article/details/gtnvqcxuit.html

Python ......... 252
来源：http://dali.hnxiangtu.top/Article/details/gtcltbbhmd.html

PHP ............ 252
来源：http://dali.yj20258888.top/Article/details/gttfdilffq.html

JavaScript ..... 252
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrlzixaz.html

TypeScript ..... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtylgvsbrp.html

Java ........... 212
来源：http://dali.jianghu66.top/Article/details/gthhmjgrkg.html

Go ............. 212
来源：http://dali.tian-w.cn/Article/details/gttujkairu.html

Ruby ........... 212
来源：http://dali.yj20258.top/Article/details/gtwymgkwrw.html

C# ............. 212
来源：http://dali.zhiwuduotai.top/Article/details/gtgrahswdu.html

C .............. 30
来源：http://dali.wangdashe.top/Article/details/gttnfkgdln.html

C++ ............ 30
来源：http://dali.yonumen.top/Article/details/gteshfepio.html

SQL ............ 90
来源：http://dali.gogol.net.cn/Article/details/gtngmxspge.html

Bash ........... 80
来源：http://dali.cdnleiting.top/Article/details/gtmzfqsipf.html

Kotlin ......... 15
来源：http://dali.gzhubu.top/Article/details/gtdumtwomq.html

Swift .......... 15
来源：http://dali.ehwqpu.com/Article/details/gtkmkihxfi.html

Lua ............ 10
来源：http://dali.tanke756.top/Article/details/gtspkedoql.html

Perl ........... 10
来源：http://dali.hammf.cn/Article/details/gtsptzkjqn.html

Scala .......... 10
来源：http://dali.chenjidiqi.icu/Article/details/gtqoatdjtk.html

------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtdqqwxayj.html

合计 ........... 2106 条
来源：http://dali.hywenlv.cn/Article/details/gtpheuodnf.html

按章节统计：
来源：http://dali.kuanghao11.cn/Article/details/gtghstsqoo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.nanxuanxn.top/Article/details/gtpzxgjhlt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.dashuyun.cn/Article/details/gtkkxykvcm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.gzhubu.top/Article/details/gtitdwfdmp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ydzc1.top/Article/details/gtexsqnagy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.fzhhl.top/Article/details/gtjdzgrkqz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ehwqpu.com/Article/details/gthjtfqicf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gtfgklxpuy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yangfankeji.com/Article/details/gtifwhcpwg.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gtopzsaswb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xuetiantiany.cn/Article/details/gttgjxxrtx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gtrhnnzvot.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gtimspakmo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gtwoglznyt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhoulong.xyz/Article/details/gtstjgmchm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.gogol.net.cn/Article/details/gtnjakhkqj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gtsklwazno.html

Q SQL 专题                              90
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqclvxcp.html

R Bash 专题                             80
来源：http://dali.cashguo.top/Article/details/gtsfskpskd.html

S C / C++ 专题                          60
来源：http://dali.guannengcc.top/Article/details/gtbogcgimu.html

T 其他语言补充                          60
来源：http://dali.cdnleiting.top/Article/details/gtwagyvnrf.html

U 高频实用片段                         120
来源：http://dali.ydzc1.top/Article/details/gtcflkuowj.html

------------------------------------
来源：http://dali.bjfxy.top/Article/details/gtihcikvxq.html

合计                                  2106 条
来源：http://dali.zhiwuduotai.top/Article/details/gtppjctofy.html

--------------------------------------------------------------------------------
来源：http://dali.gaohongyu789.top/Article/details/gtbmfvavxg.html

使用提醒
来源：http://dali.zhengqikj.top/Article/details/gtsxbgbknc.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gtohqkxiyy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.pengpengdd.cyou/Article/details/gtzvafsvsd.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xuanzx.com/Article/details/gtwyvjlmau.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xinyue.icu/Article/details/gtptypjbxf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jianghu66.top/Article/details/gtyfdkixzp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.pengpengdd.cyou/Article/details/gtuwazxkmw.html

—— 文件结束 ——
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukmhcnxy.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtvmnqbbdy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zdqjudy.top/Article/details/gtalpmtwht.html

Common Programming Examples Cheat Book
来源：http://dali.zhengqikj.top/Article/details/gtxzhjppfx.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtgqnhquwo.html

【收录内容】
来源：http://dali.meibo888.top/Article/details/gtfaqeafhd.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ehwqpu.com/Article/details/gtgqqvhxtu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.chenjidiqi.icu/Article/details/gtjtwicuwf.html

SQL · Bash · C · C++
来源：http://dali.xuanzx.com/Article/details/gtfkiugbwl.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hongshengwenyu.top/Article/details/gtthnsvjkt.html

【使用说明】
来源：http://dali.pengpengdd.cyou/Article/details/gtkpsoqnrw.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.chenjidiqi.icu/Article/details/gtlmmkxcfj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ywan-chungtsiang.top/Article/details/gtquaxfdck.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hammf.cn/Article/details/gtyilxntsm.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.chenlongwang.top/Article/details/gtwjrzgnoj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yueranfly.top/Article/details/gtvksttqmv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.sufxvd.cn/Article/details/gtapifzxul.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.shangyingyoupin.top/Article/details/gtztzfhqxk.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.gotoacloud.top/Article/details/gtmphznnlr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jianghu66.top/Article/details/gtqtdxvwmc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.smart0.xyz/Article/details/gtgimjbgbu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.haohaochexian.top/Article/details/gtnsvhahoz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.gaohongyu789.top/Article/details/gtcwfuwuwa.html

【文件统计】
来源：http://dali.zhixingplan.top/Article/details/gtfjjzjkze.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhixingplan.top/Article/details/gtqvjaukbw.html

--------------------------------------------------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gtkddvqawm.html

目  录
来源：http://dali.gogol.net.cn/Article/details/gtzenxlspk.html

--------------------------------------------------------------------------------
来源：http://dali.xylfe.cn/Article/details/gtqdozcqsw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhengqikj.top/Article/details/gtayeqfvup.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.svipenyu.cn/Article/details/gtnnzomcde.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.smart0.xyz/Article/details/gtyagcxtbe.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gtkrelnnye.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yangfankeji.com/Article/details/gtvfeerqat.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.snrcjt.cn/Article/details/gttewbwfoy.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.316326.xyz/Article/details/gtwxbwlcrh.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.aizwys.cn/Article/details/gtaxrbsfsi.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gtwvafkwdb.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yvedp.cn/Article/details/gtknakokfi.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yj20258888.top/Article/details/gtufglnqsi.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gtzgbeumfv.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwzlgqwc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.cashguo.top/Article/details/gttnehxgdx.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.havefunace.top/Article/details/gtmrawqrhx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.wangdashe.top/Article/details/gtpywyjwfr.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zycfv.cn/Article/details/gtmfrcugge.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.kuanghao11.cn/Article/details/gtumbmtjhm.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtjqwfupbx.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yanxiufei.cn/Article/details/gthuqqksoj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnxiangtu.top/Article/details/gtumwdraed.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtdjgrxysa.html

A. 基础语法与类型
来源：http://dali.haohaochexian.top/Article/details/gthnddohoh.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtdyuzcfbh.html

[A01] Hello World
来源：http://dali.zhixingplan.top/Article/details/gtmhjgeebr.html

Py:   print("Hello, World!")
来源：http://dali.9152youxi.cn/Article/details/gtqxyfabyf.html

PHP:  echo "Hello, World!";
来源：http://dali.quarkkingdee.top/Article/details/gtuimzobop.html

JS:   console.log("Hello, World!");
来源：http://dali.cucudq.cn/Article/details/gtktuvchgf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.iojbl.cn/Article/details/gtedzuleak.html

Java: System.out.println("Hello, World!");
来源：http://dali.xinyue.icu/Article/details/gtueshujeg.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ehwqpu.com/Article/details/gtzbuugigs.html

Ruby: puts "Hello, World!"
来源：http://dali.bjfxy.top/Article/details/gtxhttvsgp.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.tanke756.top/Article/details/gtygvexpsf.html

[A02] 变量声明与赋值
来源：http://dali.kuanghao11.cn/Article/details/gtawlunjwg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yj202588.top/Article/details/gtetuwerri.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.sufxvd.cn/Article/details/gteijyynlc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.sysykeji.top/Article/details/gthddmvvku.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhixingplan.top/Article/details/gtranbedfp.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yanxiufei.cn/Article/details/gtpeggfzeo.html

Go:   name := "Alex"; age := 20
来源：http://dali.yangfankeji.com/Article/details/gtsaocjuld.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zdqjudy.top/Article/details/gtswayutxc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yj20258888.top/Article/details/gtsgvyujyn.html

[A03] 常量定义
来源：http://dali.hfpthk.cn/Article/details/gtbfrvdsmw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.c1oappe.top/Article/details/gtmvfvsvqj.html

PHP:  const PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtzgpmxezr.html

JS:   const PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtfmlfxonf.html

TS:   const PI: number = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtygkrrlst.html

Java: static final double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtnvzqwvjc.html

Go:   const PI = 3.14159
来源：http://dali.jlsjyb.cn/Article/details/gtnfeohceq.html

Ruby: PI = 3.14159
来源：http://dali.jqgufenzy.top/Article/details/gtbhcipwnv.html

C#:   const double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtniqwocok.html

[A04] 判断变量类型
来源：http://dali.bjfxy.top/Article/details/gtojrggssc.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.tianlin.xyz/Article/details/gtivgbjcwg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cashguo.top/Article/details/gttxrltvvk.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.chenjidiqi.icu/Article/details/gtswztemzj.html

TS:   typeof x; x instanceof Date
来源：http://dali.yonumen.top/Article/details/gttyvnmftp.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jinghuilouyu.cn/Article/details/gtlquspnox.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.meibo888.top/Article/details/gtcqyejlwh.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.hysaishi.cn/Article/details/gtssunfudy.html

C#:   x.GetType().Name; x is int
来源：http://dali.tianlin.xyz/Article/details/gtonykgnsk.html

[A05] 整数除法与取模
来源：http://dali.nanxinkj.top/Article/details/gtrrnhczxb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cdnleiting.top/Article/details/gtukgtzjzj.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvuxpeyg.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpooikkz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtwkcakjla.html

Java: 7 / 2; 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gtkovnanze.html

Go:   7 / 2; 7 % 2
来源：http://dali.fengsongda.top/Article/details/gtvpsgwyif.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.daria6918.cn/Article/details/gtvfxwexqq.html

C#:   7 / 2; 7 % 2
来源：http://dali.shuidangran.top/Article/details/gtsbqbdsfs.html

[A06] 字符串转数字
来源：http://dali.zdqjudy.top/Article/details/gtgjbijeru.html

Py:   int("42"); float("3.14")
来源：http://dali.aizwys.cn/Article/details/gtdbehxtmv.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.shuidangran.top/Article/details/gtvmbllmhc.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.cashguo.top/Article/details/gtdoofgczk.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbmgsbyu.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvdxatvu.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.cashguo.top/Article/details/gtduhtfbon.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.gogol.net.cn/Article/details/gtfzxpqwom.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.dianchejie.cn/Article/details/gtnmfvenaw.html

[A07] 数字转字符串
来源：http://dali.sysykeji.top/Article/details/gtczaemoqn.html

Py:   str(42)
来源：http://dali.yongpay.top/Article/details/gtvoyqpsji.html

PHP:  (string) 42; strval(42)
来源：http://dali.xylfe.cn/Article/details/gthyjvfeir.html

JS:   String(42); (42).toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrkzyncp.html

TS:   String(42)
来源：http://dali.mhx1999.top/Article/details/gtuvfjagvk.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexcmpqde.html

Go:   strconv.Itoa(42)
来源：http://dali.ivvv.top/Article/details/gtkmsufsrx.html

Ruby: 42.to_s
来源：http://dali.dashuyun.cn/Article/details/gtwkwnxpxk.html

C#:   42.ToString()
来源：http://dali.quarkkingdee.top/Article/details/gtlhrsbebo.html

[A08] 取整与四舍五入
来源：http://dali.tian-w.cn/Article/details/gtzidfetxo.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.svipenyu.cn/Article/details/gtymdeaxao.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ivvv.top/Article/details/gteoyqzmay.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jinqigfzy.top/Article/details/gtvienqdxy.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.tianlin.xyz/Article/details/gtxxhgpipq.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.dashuyun.cn/Article/details/gtzcvtacyx.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.gotoacloud.top/Article/details/gtqvxlkrau.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yuanzhike.top/Article/details/gtxqarihcv.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yongpay.top/Article/details/gtwopljkjf.html

[A09] 绝对值与最大最小值
来源：http://dali.andypj.xyz/Article/details/gtvumuqgnq.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.mhx1999.top/Article/details/gticmkynfh.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxppnqmqn.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hnqzz.top/Article/details/gtbgcxoyzf.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.guannengcc.top/Article/details/gteuutqqur.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gteurypity.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jinqigufen.top/Article/details/gttebazxrf.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxwesthtk.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtdnykrgam.html

[A10] 生成随机数
来源：http://dali.dashuyun.cn/Article/details/gtyibnnscz.html

Py:   import random; random.randint(1, 100)
来源：http://dali.havefunace.top/Article/details/gtyqywnuqu.html

PHP:  random_int(1, 100);
来源：http://dali.vqdsnc.cn/Article/details/gtewejgoyf.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hammf.cn/Article/details/gtjnrziveg.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.wangdashe.top/Article/details/gtqtuukjnp.html

Java: new Random().nextInt(100) + 1
来源：http://dali.ppjwa.cn/Article/details/gtbrqgsjsg.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.guowangkeji.top/Article/details/gtslcclrcq.html

Ruby: rand(1..100)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomradzef.html

C#:   new Random().Next(1, 101)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlxmbxva.html

[A11] 条件表达式（三元）
来源：http://dali.chenjidiqi.icu/Article/details/gtiyyapyle.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.iojbl.cn/Article/details/gtyvhxctjd.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gtawshmnti.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.ivvv.top/Article/details/gttgwgpttc.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.vqdsnc.cn/Article/details/gtipeewthl.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.kuanghao11.cn/Article/details/gtynnkfrrj.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yvedp.cn/Article/details/gtslxrljhu.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.redwolf501.top/Article/details/gtjiglmucd.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jqgfzy.top/Article/details/gtsoorohpp.html

[A12] 字符串插值 / 格式化
来源：http://dali.ydzc1.top/Article/details/gtwoalvrqs.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.bjfxy.top/Article/details/gtnlzuykln.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yongpay.top/Article/details/gtmmcblyld.html

JS:   `Hello, ${name}!`
来源：http://dali.yangfankeji.com/Article/details/gtpnjupcki.html

TS:   `Hello, ${name}!`
来源：http://dali.jqgufenzy.top/Article/details/gtiahlzect.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zdqjudy.top/Article/details/gthheowxmv.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.ydzc1.top/Article/details/gtjrgyjbua.html

Ruby: "Hello, #{name}!"
来源：http://dali.chenlongwang.top/Article/details/gtqvqjwalo.html

C#:   $"Hello, {name}!"
来源：http://dali.9152youxi.cn/Article/details/gtaxkbrixb.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.pengpengdd.cyou/Article/details/gtcwzhvdae.html

Py:   "第一行\n第二行"
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgpsnueh.html

PHP:  "第一行\n第二行"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobbcplby.html

JS:   "第一行\n第二行"
来源：http://dali.gotoacloud.top/Article/details/gtmcxpdkhv.html

TS:   "第一行\n第二行"
来源：http://dali.yvedp.cn/Article/details/gtgxayexlm.html

Java: "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gteeuahxkq.html

Go:   "第一行\n第二行"
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzhtykax.html

Ruby: "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gtwmyenpht.html

C#:   "第一行\n第二行"
来源：http://dali.daxiang520.top/Article/details/gtxsqsrzhl.html

[A14] 注释写法
来源：http://dali.yongpay.top/Article/details/gtdeuqssog.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jiagoushi.top/Article/details/gtnhhglico.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.tanke756.top/Article/details/gthqpkzsvp.html

JS:   // 单行；/* 多行 */
来源：http://dali.chenlongwang.top/Article/details/gttqddqyti.html

TS:   // 单行；/* 多行 */
来源：http://dali.yonumen.top/Article/details/gtphmvxzpl.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.nwbrower.top/Article/details/gtlrmmwlai.html

Go:   // 单行；/* 多行 */
来源：http://dali.zdqjudy.top/Article/details/gtzmxmhakr.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.sysykeji.top/Article/details/gtjhgcufsg.html

C#:   // 单行；/* 多行 */
来源：http://dali.quarkkingdee.top/Article/details/gthbvvrmbd.html

[A15] 空值判断与默认值
来源：http://dali.hnxiangtu.top/Article/details/gtympxinmo.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gtpmrclvkc.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jiagoushi.top/Article/details/gtykdkcldt.html

JS:   const value = data ?? "默认值";
来源：http://dali.jinqigufen.top/Article/details/gtfvjlpmrd.html

TS:   const value = data ?? "默认值";
来源：http://dali.jyoumei.cn/Article/details/gtltdonpka.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.gotoacloud.top/Article/details/gtvdptfwvs.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.fzhhl.top/Article/details/gtouukiwyu.html

Ruby: value = data || "默认值"
来源：http://dali.hongshengwenyu.top/Article/details/gtlugutqey.html

C#:   var value = data ?? "默认值";
来源：http://dali.gotoacloud.top/Article/details/gtppxwtnaa.html

[A16] 真假值判断规则
来源：http://dali.jianghu66.top/Article/details/gtlqmpexuw.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jqgufenzy.top/Article/details/gtyinaryun.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.chenlongwang.top/Article/details/gthwcdzuup.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.bjfxy.top/Article/details/gtyxnkwbll.html

TS:   if (!x) {}
来源：http://dali.cheryme.top/Article/details/gtnbxczhqq.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jinqigufen.top/Article/details/gtddjluhml.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jyoumei.cn/Article/details/gtlnimzwmz.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yj20258888.top/Article/details/gtsvnnfxgj.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.dashuyun.cn/Article/details/gtwhdeukxh.html

[A17] 位运算
来源：http://dali.tianlin.xyz/Article/details/gtlbklkzdt.html


<!-- 参考信息 -->