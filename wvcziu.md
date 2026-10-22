代发 wailian999

[U97] JS：并发请求
来源：http://dali.chenlongwang.top/Article/details/gtisgjmsad.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gtamjwdqwh.html

[U98] JS：fetch 带 JSON
来源：http://dali.daxiang520.top/Article/details/gtuutubenv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhongyouzk.top/Article/details/gtwolqinho.html

[U99] JS：事件监听
来源：http://dali.gaohongyu789.top/Article/details/gtmenwdtue.html

el.addEventListener("click", e => {})
来源：http://dali.shanyushiyangtech.top/Article/details/gthvdnxheh.html

[U100] JS：DOM 查询
来源：http://dali.pycfn.com/Article/details/gtxryhacrj.html

document.querySelector(".item")
来源：http://dali.xziqi.cn/Article/details/gtggkikbeg.html

[U101] JS：classList 操作
来源：http://dali.iojbl.cn/Article/details/gtkypnmjxw.html

el.classList.toggle("active")
来源：http://dali.hongshengwenyu.top/Article/details/gtqbysxohn.html

[U102] JS：本地存储
来源：http://dali.yonumen.top/Article/details/gtxyozkvat.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.havefunace.top/Article/details/gtaatwjwse.html

[U103] JS：定时器
来源：http://dali.chenlongwang.top/Article/details/gttrlwuolr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xylfe.cn/Article/details/gtowrpxjls.html

[U104] JS：防抖
来源：http://dali.ppjwa.cn/Article/details/gteavsqouf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhongyouzk.top/Article/details/gtegpvsnqq.html

[U105] JS：节流
来源：http://dali.shzxlz.cn/Article/details/gtrbrzueaf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtmwsunday.html

[U106] JS：日期格式化
来源：http://dali.shzxlz.cn/Article/details/gtycxlgvil.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yongpay.top/Article/details/gtcceuttvc.html

[U107] JS：数字千分位
来源：http://dali.jiagoushi.top/Article/details/gtqopkojjc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ehwqpu.com/Article/details/gtjjtkmhlj.html

[U108] JS：随机整数
来源：http://dali.xinyue.icu/Article/details/gtxtuvcfuo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xuanzx.com/Article/details/gtnhqqjzdj.html

[U109] JS：数组分组
来源：http://dali.sxryk.cn/Article/details/gtvrxonogx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hnxiangtu.top/Article/details/gtdteptsqj.html

[U110] JS：数组分块
来源：http://dali.bjfxy.top/Article/details/gtkioreijx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.havefunace.top/Article/details/gtkkkounhp.html

[U111] JS：对象转 Map
来源：http://dali.ybcxt.top/Article/details/gtrhuiukre.html

new Map(Object.entries(obj))
来源：http://dali.pycfn.com/Article/details/gtvntfrzeh.html

[U112] JS：字符串补位
来源：http://dali.quarkkingdee.top/Article/details/gtmdxdsula.html

"7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gtjdhfmfyo.html

[U113] JS：正则替换全部
来源：http://dali.gogol.net.cn/Article/details/gtlxjznkxs.html

s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtqsyysyyy.html

[U114] JS：JSON 深比较
来源：http://dali.jlsjyb.cn/Article/details/gtrbqqqcir.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtuusrxmth.html

[U115] JS：生成 UUID
来源：http://dali.hongshengwenyu.top/Article/details/gttjqwzley.html

crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gtimprrfsw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.guowangkeji.top/Article/details/gtwxcizlfe.html

/** @param {string} name */ function f(name) {}
来源：http://dali.redwolf501.top/Article/details/gtenfctkav.html

[U117] JS：单元测试
来源：http://dali.haohaochexian.top/Article/details/gtsrnmhgxq.html

npm i -D vitest;  npx vitest
来源：http://dali.cashguo.top/Article/details/gtutoaphmy.html

[U118] JS：开发服务器
来源：http://dali.tian-w.cn/Article/details/gtoazxzosq.html

npm i -D vite;  npx vite
来源：http://dali.c1oappe.top/Article/details/gtyxsajcjc.html

[U119] JS：生产构建
来源：http://dali.yongpay.top/Article/details/gtozddtafg.html

npx vite build
来源：http://dali.ydzc1.top/Article/details/gtmdytcgju.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yanxiufei.cn/Article/details/gtjylqgujx.html

import.meta.env.VITE_API_URL
来源：http://dali.andypj.xyz/Article/details/gtqxennmyt.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtousbpmdf.html

统计汇总
来源：http://dali.jyoumei.cn/Article/details/gtmbfxqrtn.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtqjvozwav.html

按语言统计（条）：
来源：http://dali.yuanzhike.top/Article/details/gtgfcgjgdc.html

Python ......... 252
来源：http://dali.smart0.xyz/Article/details/gtrcwizdmx.html

PHP ............ 252
来源：http://dali.chenzaomai.com/Article/details/gtzgalxiir.html

JavaScript ..... 252
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtnphhzm.html

TypeScript ..... 212
来源：http://dali.yuanzhike.top/Article/details/gtyncmlkvm.html

Java ........... 212
来源：http://dali.xziqi.cn/Article/details/gtxhfckcps.html

Go ............. 212
来源：http://dali.zycfv.cn/Article/details/gtecezjbtn.html

Ruby ........... 212
来源：http://dali.sufxvd.cn/Article/details/gtzvqfnlvs.html

C# ............. 212
来源：http://dali.chenjidiqi.icu/Article/details/gtfwoireki.html

C .............. 30
来源：http://dali.nanxuanxn.top/Article/details/gtisnacosu.html

C++ ............ 30
来源：http://dali.zhixingplan.top/Article/details/gtmsvdazvo.html

SQL ............ 90
来源：http://dali.chenjidiqi.icu/Article/details/gtrhlmirtx.html

Bash ........... 80
来源：http://dali.andypj.xyz/Article/details/gtgxywsbxr.html

Kotlin ......... 15
来源：http://dali.yonumen.top/Article/details/gtvcuqgmif.html

Swift .......... 15
来源：http://dali.pengpengdd.cyou/Article/details/gttzuxjxxx.html

Lua ............ 10
来源：http://dali.shzxlz.cn/Article/details/gtyynvwocc.html

Perl ........... 10
来源：http://dali.cucudq.cn/Article/details/gtrxfenxxl.html

Scala .......... 10
来源：http://dali.fzhhl.top/Article/details/gtawwvllmf.html

------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gthuwwjsjp.html

合计 ........... 2106 条
来源：http://dali.mhx1999.top/Article/details/gtiunymfxz.html

按章节统计：
来源：http://dali.zhongyouzk.top/Article/details/gtjazppjxl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ehwqpu.com/Article/details/gtczzduqwf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hnxiangtu.top/Article/details/gtwgtlfihf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.0kj1m.cn/Article/details/gtmaspawbt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.vqdsnc.cn/Article/details/gtfojcspoc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sxryk.cn/Article/details/gtmscrlovn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.vqdsnc.cn/Article/details/gtmocdrplp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hnxiangtu.top/Article/details/gtwpypgcbn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ivvv.top/Article/details/gtnlkffboz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jyoumei.cn/Article/details/gthkdcacue.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jiagoushi.top/Article/details/gtunefxsrj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.kuanghao11.cn/Article/details/gtfsxounxz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gtccxenasy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gtielkkygj.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.andypj.xyz/Article/details/gtsnlxhrni.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ybcxt.top/Article/details/gterrsghdg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gtoznwqyjl.html

Q SQL 专题                              90
来源：http://dali.0kj1m.cn/Article/details/gtlrnptzsq.html

R Bash 专题                             80
来源：http://dali.tianlin.xyz/Article/details/gtkdgwpaod.html

S C / C++ 专题                          60
来源：http://dali.jiagoushi.top/Article/details/gtngpjzcrt.html

T 其他语言补充                          60
来源：http://dali.zdqjudy.top/Article/details/gttzdhgpwc.html

U 高频实用片段                         120
来源：http://dali.cqqwz.cn/Article/details/gtwxfmnpyu.html

------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gtcklrfedo.html

合计                                  2106 条
来源：http://dali.gaohongyu789.top/Article/details/gtnsxbrbfi.html

--------------------------------------------------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gtudhktjov.html

使用提醒
来源：http://dali.haohaochexian.top/Article/details/gtwwbcnmgx.html

--------------------------------------------------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gtehdsegcz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cashguo.top/Article/details/gtionjidnq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hongshengwenyu.top/Article/details/gtseywqijg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hammf.cn/Article/details/gtacaqcaub.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.andypj.xyz/Article/details/gtnggobrzr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cashguo.top/Article/details/gtvdqwwqlb.html

—— 文件结束 ——
来源：http://dali.yj20258.top/Article/details/gtxjgaaket.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtimvjmriv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hysaishi.cn/Article/details/gtmasrpdwn.html

Common Programming Examples Cheat Book
来源：http://dali.hysaishi.cn/Article/details/gtkemsorse.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmjptjmp.html

【收录内容】
来源：http://dali.meibo888.top/Article/details/gtqkjkasms.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.sxryk.cn/Article/details/gthvbssaly.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hfpthk.cn/Article/details/gtyhbbkuwg.html

SQL · Bash · C · C++
来源：http://dali.daria6918.cn/Article/details/gtqxltlejy.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhoulong.xyz/Article/details/gtlohxqbys.html

【使用说明】
来源：http://dali.zhongyouzk.top/Article/details/gtdmnlxtyh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yangfankeji.com/Article/details/gtvdgwrjea.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.gzhubu.top/Article/details/gtylkwsjrr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowuhwrew.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ivvv.top/Article/details/gtbadtjunp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.chenjidiqi.icu/Article/details/gtjchkurkm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hywenlv.cn/Article/details/gtajpctanp.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.dashuyun.cn/Article/details/gtlxqcezxe.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjwrdmpy.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.birdmap.top/Article/details/gtfdyenyqz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hnxiangtu.top/Article/details/gttlzubnqv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.quarkkingdee.top/Article/details/gtubalgjgt.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xziqi.cn/Article/details/gtfeupgsvk.html

【文件统计】
来源：http://dali.xinyue.icu/Article/details/gtnbeaavyj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmcbaege.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gtjfvvzauh.html

目  录
来源：http://dali.havefunace.top/Article/details/gtiyzantkc.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtcqsavhtq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jqgfzy.top/Article/details/gtjffykydd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtlmprevqh.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtkzkilfjr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ehwqpu.com/Article/details/gtvjxihaow.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtuswfmkku.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xuanzx.com/Article/details/gtldbehwym.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthfurxbny.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtollcfsni.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttjmasex.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.guannengcc.top/Article/details/gtmiqetyme.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gtjhdktxhi.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gttujjkutm.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jyoumei.cn/Article/details/gtfhjgezcx.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gzhubu.top/Article/details/gtwjhzapyl.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.snrcjt.cn/Article/details/gtoivocgui.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hysaishi.cn/Article/details/gtrtkexjsf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jqgufenzy.top/Article/details/gtezaikkmr.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhongyouzk.top/Article/details/gtjdyslbse.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yvedp.cn/Article/details/gttohquqde.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnxiangtu.top/Article/details/gtpcixrodf.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhongyouzk.top/Article/details/gthrrjpdxr.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtxrdadzer.html

A. 基础语法与类型
来源：http://dali.cheryme.top/Article/details/gtcxzizpgl.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtwwcmqtzh.html

[A01] Hello World
来源：http://dali.zhengqikj.top/Article/details/gthebqecif.html

Py:   print("Hello, World!")
来源：http://dali.yanxiufei.cn/Article/details/gtbcwocbsy.html

PHP:  echo "Hello, World!";
来源：http://dali.yueranfly.top/Article/details/gttnpmopuq.html

JS:   console.log("Hello, World!");
来源：http://dali.yangfankeji.com/Article/details/gtyeuguhyi.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.havefunace.top/Article/details/gtzughlvra.html

Java: System.out.println("Hello, World!");
来源：http://dali.yongpay.top/Article/details/gtoivlirdu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.smart0.xyz/Article/details/gtkyfarkjx.html

Ruby: puts "Hello, World!"
来源：http://dali.xinyue.icu/Article/details/gttuzgttcw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ybcxt.top/Article/details/gtvtiwiodk.html

[A02] 变量声明与赋值
来源：http://dali.gotoacloud.top/Article/details/gtptatzpgw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.daria6918.cn/Article/details/gtnnjjbmlj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhiwuduotai.top/Article/details/gtqfpvhboy.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jiagoushi.top/Article/details/gtpwfhpgim.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hfpthk.cn/Article/details/gtdtmfigve.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jinqigufen.top/Article/details/gtowrjltwi.html

Go:   name := "Alex"; age := 20
来源：http://dali.tian-w.cn/Article/details/gtyjuzuarf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hongshengwenyu.top/Article/details/gtvroiqqtb.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.cucudq.cn/Article/details/gtuxjdrbzk.html

[A03] 常量定义
来源：http://dali.jianghu66.top/Article/details/gthzdybvut.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hywenlv.cn/Article/details/gturebdldk.html

PHP:  const PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtefadjxpx.html

JS:   const PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtosaoyrki.html

TS:   const PI: number = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtofufjzgd.html

Java: static final double PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gteqxxpeaa.html

Go:   const PI = 3.14159
来源：http://dali.hysaishi.cn/Article/details/gtmpyripbo.html

Ruby: PI = 3.14159
来源：http://dali.xuetiantiany.cn/Article/details/gtddgleicb.html

C#:   const double PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtososvndz.html

[A04] 判断变量类型
来源：http://dali.guannengcc.top/Article/details/gtkezzkzmz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xylfe.cn/Article/details/gtbvkibidq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yangfankeji.com/Article/details/gthpywvkke.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yvedp.cn/Article/details/gtxycaisfz.html

TS:   typeof x; x instanceof Date
来源：http://dali.jlsjyb.cn/Article/details/gtquotbpuc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shangyingyoupin.top/Article/details/gtchjogbie.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.aibaodan.cn/Article/details/gtcwllgork.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.gaohongyu789.top/Article/details/gtcenlwdch.html

C#:   x.GetType().Name; x is int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlrekmfe.html

[A05] 整数除法与取模
来源：http://dali.zhixingplan.top/Article/details/gtdqfpuqmh.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.quarkkingdee.top/Article/details/gtzkfdmcxe.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gtlymuvqgn.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gtltliuvbb.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yvedp.cn/Article/details/gtcxytxmhd.html

Java: 7 / 2; 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gtbztsuqsw.html

Go:   7 / 2; 7 % 2
来源：http://dali.yuxming.cn/Article/details/gtpzweopgp.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gthufuwdgr.html

C#:   7 / 2; 7 % 2
来源：http://dali.ydzc1.top/Article/details/gtucyonspo.html

[A06] 字符串转数字
来源：http://dali.cqqwz.cn/Article/details/gtfnhlzpyd.html

Py:   int("42"); float("3.14")
来源：http://dali.jinqigufen.top/Article/details/gtdiybimza.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.redwolf501.top/Article/details/gtjcasilun.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.feifeiyinyue.top/Article/details/gtwcjfzsjy.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.fengsongda.top/Article/details/gtzgqjbvao.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.dianchejie.cn/Article/details/gtpoxllsfy.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gtyaiiaddo.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.cashguo.top/Article/details/gtlgsmgdwo.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jyoumei.cn/Article/details/gthithjrho.html

[A07] 数字转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtwktxnkbk.html

Py:   str(42)
来源：http://dali.zhixingplan.top/Article/details/gtwnnnixjg.html

PHP:  (string) 42; strval(42)
来源：http://dali.havefunace.top/Article/details/gtdbtxsvsl.html

JS:   String(42); (42).toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtvzftnyxe.html

TS:   String(42)
来源：http://dali.xuetiantiany.cn/Article/details/gtqzdctawp.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.guowangkeji.top/Article/details/gtxxridjtx.html

Go:   strconv.Itoa(42)
来源：http://dali.bjfxy.top/Article/details/gtjlvgxexk.html

Ruby: 42.to_s
来源：http://dali.aizwys.cn/Article/details/gtkhwqqyvb.html

C#:   42.ToString()
来源：http://dali.yueranfly.top/Article/details/gtkgcaszzw.html

[A08] 取整与四舍五入
来源：http://dali.havefunace.top/Article/details/gtaufpyhtz.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.mhx1999.top/Article/details/gtwmenyabg.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.xylfe.cn/Article/details/gtqdocetkg.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gtyopxwafb.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yj20258.top/Article/details/gtlrdrppqa.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yanxiufei.cn/Article/details/gtarnllpsk.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfyazymyd.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jyoumei.cn/Article/details/gtuvegrleu.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yongpay.top/Article/details/gtsiiwbkxr.html

[A09] 绝对值与最大最小值
来源：http://dali.yuxming.cn/Article/details/gtmedocpuw.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shuidangran.top/Article/details/gtcvxwifru.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtqlitcqwf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.sysykeji.top/Article/details/gtftbhbwle.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjxwgxlj.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtnxekqbql.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.guowangkeji.top/Article/details/gthzjfymka.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yj20258888.top/Article/details/gtcfxpoqhp.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.fzhhl.top/Article/details/gtncqllrvv.html

[A10] 生成随机数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyblzodnm.html

Py:   import random; random.randint(1, 100)
来源：http://dali.hongshengwenyu.top/Article/details/gttjpjpoaf.html

PHP:  random_int(1, 100);
来源：http://dali.pycfn.com/Article/details/gtxokrgkve.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.meibo888.top/Article/details/gtcxhpnwyw.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sxryk.cn/Article/details/gtkmfwodln.html

Java: new Random().nextInt(100) + 1
来源：http://dali.chenlongwang.top/Article/details/gtbkopnnzi.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhengqikj.top/Article/details/gtqnvzozzq.html

Ruby: rand(1..100)
来源：http://dali.gotoacloud.top/Article/details/gtksvtajby.html

C#:   new Random().Next(1, 101)
来源：http://dali.mhx1999.top/Article/details/gtxtyhcpoi.html

[A11] 条件表达式（三元）
来源：http://dali.gotoacloud.top/Article/details/gtcghbaouh.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.aizwys.cn/Article/details/gthynevyzz.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.kuanghao11.cn/Article/details/gtxemdpwid.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.vqdsnc.cn/Article/details/gtxcjujoby.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhlfofpb.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yj202588.top/Article/details/gtrhgbxztf.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.hnxiangtu.top/Article/details/gtllunbdjg.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.nwbrower.top/Article/details/gtpgwvycdv.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.hammf.cn/Article/details/gtcebrvzvi.html

[A12] 字符串插值 / 格式化
来源：http://dali.ybcxt.top/Article/details/gtxcychpxo.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.xinyue.icu/Article/details/gtrrnphwkl.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.chenzaomai.com/Article/details/gtbndvysyx.html

JS:   `Hello, ${name}!`
来源：http://dali.aibaodan.cn/Article/details/gttnwsjwzp.html

TS:   `Hello, ${name}!`
来源：http://dali.havefunace.top/Article/details/gtkjxkofsq.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.316326.xyz/Article/details/gtdmbqsofl.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtqglvftlp.html

Ruby: "Hello, #{name}!"
来源：http://dali.c1oappe.top/Article/details/gtafwszpxx.html

C#:   $"Hello, {name}!"
来源：http://dali.snrcjt.cn/Article/details/gtnzaacxwz.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.birdmap.top/Article/details/gtmufcjeqz.html

Py:   "第一行\n第二行"
来源：http://dali.sufxvd.cn/Article/details/gtbpnlhndw.html

PHP:  "第一行\n第二行"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcnarfyfm.html

JS:   "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gtuquekxmh.html

TS:   "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gtxeuqxjhi.html

Java: "第一行\n第二行"
来源：http://dali.hfpthk.cn/Article/details/gttdprzomu.html

Go:   "第一行\n第二行"
来源：http://dali.9152youxi.cn/Article/details/gtbyqcxeno.html

Ruby: "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gtsiqmlriy.html

C#:   "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gthxmrsdbw.html

[A14] 注释写法
来源：http://dali.pengpengdd.cyou/Article/details/gtobptslil.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.tanke756.top/Article/details/gtzyypoufp.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.hammf.cn/Article/details/gtsbxgcgda.html

JS:   // 单行；/* 多行 */
来源：http://dali.hfpthk.cn/Article/details/gtwxircovh.html

TS:   // 单行；/* 多行 */
来源：http://dali.guowangkeji.top/Article/details/gtzquukhnz.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hysaishi.cn/Article/details/gtofbpvdnu.html

Go:   // 单行；/* 多行 */
来源：http://dali.cucudq.cn/Article/details/gtnrjsbuzk.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttswiztre.html

C#:   // 单行；/* 多行 */
来源：http://dali.hammf.cn/Article/details/gtlefjttij.html

[A15] 空值判断与默认值
来源：http://dali.zhoulong.xyz/Article/details/gtgfuisirq.html

Py:   value = data or "默认值"
来源：http://dali.jlsjyb.cn/Article/details/gtzqjahrrq.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.sweek.top/Article/details/gtibqghojb.html

JS:   const value = data ?? "默认值";
来源：http://dali.tianlin.xyz/Article/details/gtqepjyaxt.html

TS:   const value = data ?? "默认值";
来源：http://dali.xuanzx.com/Article/details/gtfrpshtyo.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ybcxt.top/Article/details/gtahlqjodz.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.hnxiangtu.top/Article/details/gtwwpknrkp.html

Ruby: value = data || "默认值"
来源：http://dali.meibo888.top/Article/details/gtssorwlqa.html

C#:   var value = data ?? "默认值";
来源：http://dali.yanxiufei.cn/Article/details/gtyrsuchuk.html

[A16] 真假值判断规则
来源：http://dali.nanxinkj.top/Article/details/gtapdsmatw.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.hywenlv.cn/Article/details/gtuozfgdfz.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yonumen.top/Article/details/gtbirkmcpf.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.sxryk.cn/Article/details/gtcopxpebe.html

TS:   if (!x) {}
来源：http://dali.redwolf501.top/Article/details/gtjrsupwct.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxzpsiow.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.nanxinkj.top/Article/details/gtyvfikzjx.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.snrcjt.cn/Article/details/gtpcmucwpf.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.fzhhl.top/Article/details/gtwylwldsd.html

[A17] 位运算
来源：http://dali.fzhhl.top/Article/details/gtzdtouhbt.html


<!-- 参考信息 -->