代发 wailian999

[U101] JS：classList 操作
来源：http://dali.xuanzx.com/Article/details/gtihkxbyvn.html

el.classList.toggle("active")
来源：http://dali.chenzaomai.com/Article/details/gtjusjfggt.html

[U102] JS：本地存储
来源：http://dali.cqqwz.cn/Article/details/gtmqsutbnj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.aizwys.cn/Article/details/gtwbqedyzo.html

[U103] JS：定时器
来源：http://dali.guannengcc.top/Article/details/gtvcibhpbp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.pycfn.com/Article/details/gtddmnowez.html

[U104] JS：防抖
来源：http://dali.sysykeji.top/Article/details/gtohjyfcjv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gtfxcpotjz.html

[U105] JS：节流
来源：http://dali.sweek.top/Article/details/gtjoahoken.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tian-w.cn/Article/details/gtzrzsbjnw.html

[U106] JS：日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gtntzgsxtp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.c1oappe.top/Article/details/gtqocaaknw.html

[U107] JS：数字千分位
来源：http://dali.chenzaomai.com/Article/details/gtyulhcegr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnpknkxju.html

[U108] JS：随机整数
来源：http://dali.jianghu66.top/Article/details/gtqfziwdwm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhiwuduotai.top/Article/details/gtnjryoiuy.html

[U109] JS：数组分组
来源：http://dali.sweek.top/Article/details/gtzjwhfbfx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.mhx1999.top/Article/details/gttpnndurm.html

[U110] JS：数组分块
来源：http://dali.xziqi.cn/Article/details/gtotbeqall.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhengqikj.top/Article/details/gtxyzpnjxf.html

[U111] JS：对象转 Map
来源：http://dali.hongshengwenyu.top/Article/details/gtvlwcjdss.html

new Map(Object.entries(obj))
来源：http://dali.dianchejie.cn/Article/details/gtvkbvvfno.html

[U112] JS：字符串补位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtersxiaoc.html

"7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtdaqjytri.html

[U113] JS：正则替换全部
来源：http://dali.bjfxy.top/Article/details/gtpraoymve.html

s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtpsxersqi.html

[U114] JS：JSON 深比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtskxtktao.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtirxyvmmx.html

[U115] JS：生成 UUID
来源：http://dali.pycfn.com/Article/details/gteuktlqbn.html

crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gtvtbqphpp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zycfv.cn/Article/details/gtmrsgglpy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.guannengcc.top/Article/details/gtrhvrlsci.html

[U117] JS：单元测试
来源：http://dali.0kj1m.cn/Article/details/gtyxxzdefw.html

npm i -D vitest;  npx vitest
来源：http://dali.jinqigufen.top/Article/details/gtxhfmbcml.html

[U118] JS：开发服务器
来源：http://dali.cqqwz.cn/Article/details/gtlzzbuyuj.html

npm i -D vite;  npx vite
来源：http://dali.hysaishi.cn/Article/details/gtrvbafafw.html

[U119] JS：生产构建
来源：http://dali.quarkkingdee.top/Article/details/gttegfaeom.html

npx vite build
来源：http://dali.hnxiangtu.top/Article/details/gtkmtzhsyb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.meibo888.top/Article/details/gtpyqiebpn.html

import.meta.env.VITE_API_URL
来源：http://dali.chenlongwang.top/Article/details/gtvvibqiyb.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtiurrchuh.html

统计汇总
来源：http://dali.cheryme.top/Article/details/gtopsffkyj.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtbmxliitp.html

按语言统计（条）：
来源：http://dali.pycfn.com/Article/details/gtpbetfuya.html

Python ......... 252
来源：http://dali.yanxiufei.cn/Article/details/gtabkdljor.html

PHP ............ 252
来源：http://dali.iojbl.cn/Article/details/gtvdrapecd.html

JavaScript ..... 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxgfzbhs.html

TypeScript ..... 212
来源：http://dali.pycfn.com/Article/details/gtdmllofar.html

Java ........... 212
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvucldsq.html

Go ............. 212
来源：http://dali.nwbrower.top/Article/details/gtxbiistyq.html

Ruby ........... 212
来源：http://dali.yj20258888.top/Article/details/gtxqvkanna.html

C# ............. 212
来源：http://dali.daxiang520.top/Article/details/gtkvswbkcv.html

C .............. 30
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvcsljudv.html

C++ ............ 30
来源：http://dali.zhengqikj.top/Article/details/gtaxxdpooa.html

SQL ............ 90
来源：http://dali.redwolf501.top/Article/details/gtwqfnwobz.html

Bash ........... 80
来源：http://dali.zhongyouzk.top/Article/details/gtahpojois.html

Kotlin ......... 15
来源：http://dali.9152youxi.cn/Article/details/gtaladnswr.html

Swift .......... 15
来源：http://dali.yanxiufei.cn/Article/details/gtoulactoh.html

Lua ............ 10
来源：http://dali.ehwqpu.com/Article/details/gtykjqyzen.html

Perl ........... 10
来源：http://dali.jinqigfzy.top/Article/details/gtitmlqejx.html

Scala .......... 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtarylsfcq.html

------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gtlfixarii.html

合计 ........... 2106 条
来源：http://dali.ehwqpu.com/Article/details/gtgxqckbco.html

按章节统计：
来源：http://dali.yj202588.top/Article/details/gtprrrzpiv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ydzc1.top/Article/details/gtlzlwvnmw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.birdmap.top/Article/details/gtbzgevqfc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmmcsgub.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zycfv.cn/Article/details/gtedyxffla.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ywan-chungtsiang.top/Article/details/gtunmpzmcq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cqqwz.cn/Article/details/gtdtwsadvv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.guowangkeji.top/Article/details/gtprntrxvl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zycfv.cn/Article/details/gtoodlewes.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gteuwnvmjk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnztqdnda.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gteicftkzs.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtemuuycug.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gtxzwifuoz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.wangshuangyany.cn/Article/details/gtpzjgquog.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shuidangran.top/Article/details/gtxzjufgbu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gtnkuaisjk.html

Q SQL 专题                              90
来源：http://dali.chenzaomai.com/Article/details/gtzgmefzdb.html

R Bash 专题                             80
来源：http://dali.aizwys.cn/Article/details/gtsnxfvtuj.html

S C / C++ 专题                          60
来源：http://dali.vqdsnc.cn/Article/details/gtglhptcqw.html

T 其他语言补充                          60
来源：http://dali.nanxinkj.top/Article/details/gtfmqghbho.html

U 高频实用片段                         120
来源：http://dali.birdmap.top/Article/details/gtehykbesj.html

------------------------------------
来源：http://dali.ydzc1.top/Article/details/gtllwjbxcv.html

合计                                  2106 条
来源：http://dali.yj20258.top/Article/details/gthvrdmubr.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtawrsiucl.html

使用提醒
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxsdphlj.html

--------------------------------------------------------------------------------
来源：http://dali.tian-w.cn/Article/details/gtzcwgcwwy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.gogol.net.cn/Article/details/gtdibhlbst.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.tanke756.top/Article/details/gtmuiwawrh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zdqjudy.top/Article/details/gtgxjtxdal.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yj202588.top/Article/details/gtdlpnytau.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.quarkkingdee.top/Article/details/gtfexcmefa.html

—— 文件结束 ——
来源：http://dali.c1oappe.top/Article/details/gtdpmhjotb.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjtetwbe.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.andypj.xyz/Article/details/gtmbsvlhbl.html

Common Programming Examples Cheat Book
来源：http://dali.birdmap.top/Article/details/gtmrchzksk.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtqifmnhvg.html

【收录内容】
来源：http://dali.tian-w.cn/Article/details/gtetgddabe.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.daxiang520.top/Article/details/gtjyzffiwt.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hfpthk.cn/Article/details/gtjjfiqmjv.html

SQL · Bash · C · C++
来源：http://dali.chenzaomai.com/Article/details/gtwamvnwty.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.nanxuanxn.top/Article/details/gtzsabnvjx.html

【使用说明】
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznyziivj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hammf.cn/Article/details/gthkpdbnim.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.sysykeji.top/Article/details/gtkmqcmwul.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.aizwys.cn/Article/details/gtstnagbxa.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hongshengwenyu.top/Article/details/gtbcbbnlcn.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhongyouzk.top/Article/details/gtjwkgjjfi.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jianghu66.top/Article/details/gtrptqsnfm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yueranfly.top/Article/details/gteyakkrzd.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.chenzaomai.com/Article/details/gtwhggvhkd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhiwuduotai.top/Article/details/gtlvdykqtr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yj202588.top/Article/details/gtvjdfdvbn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.fengsongda.top/Article/details/gtefrjmkqr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hnqzz.top/Article/details/gtgcxmkrif.html

【文件统计】
来源：http://dali.jinqigufen.top/Article/details/gtypmcxjwk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.9152youxi.cn/Article/details/gtozzalykz.html

--------------------------------------------------------------------------------
来源：http://dali.meibo888.top/Article/details/gtbpdetuyb.html

目  录
来源：http://dali.yuxming.cn/Article/details/gttzjaabnk.html

--------------------------------------------------------------------------------
来源：http://dali.smart0.xyz/Article/details/gtzhblbupj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xuanzx.com/Article/details/gtulassbcd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.cucudq.cn/Article/details/gtpmmqturn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.mhx1999.top/Article/details/gtgebzsgvm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jqgfzy.top/Article/details/gtzasnrpip.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.fengsongda.top/Article/details/gthkdhlzjp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.dashuyun.cn/Article/details/gtuggslmju.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cqqwz.cn/Article/details/gtfyjkgjqa.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jianghu66.top/Article/details/gtqfbitlxa.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gtdtfbpaqq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.birdmap.top/Article/details/gttlnxkkay.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.xziqi.cn/Article/details/gtgqhjvqed.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gtvivxfsad.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.chenlongwang.top/Article/details/gtjaerunhh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jqgufenzy.top/Article/details/gteglpdqhr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sxryk.cn/Article/details/gtsuszgzfa.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtwxkmatjp.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jiagoushi.top/Article/details/gtezsfocrv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jqgfzy.top/Article/details/gthfgccifp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yonumen.top/Article/details/gtuhmaxowg.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.snrcjt.cn/Article/details/gtqsfzusvp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.iojbl.cn/Article/details/gtevtpybri.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtvbselmwe.html

A. 基础语法与类型
来源：http://dali.cheryme.top/Article/details/gttcztzcuu.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtphtlnmgl.html

[A01] Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtutuncgef.html

Py:   print("Hello, World!")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyigojodk.html

PHP:  echo "Hello, World!";
来源：http://dali.vqdsnc.cn/Article/details/gtclhmxyud.html

JS:   console.log("Hello, World!");
来源：http://dali.zhixingplan.top/Article/details/gtdfrijsmn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yuxming.cn/Article/details/gtpjvnullu.html

Java: System.out.println("Hello, World!");
来源：http://dali.jlsjyb.cn/Article/details/gtiiezwleq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbmkvvdku.html

Ruby: puts "Hello, World!"
来源：http://dali.jiagoushi.top/Article/details/gtazlsfzhn.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xylfe.cn/Article/details/gtxfvfxtwu.html

[A02] 变量声明与赋值
来源：http://dali.feifeiyinyue.top/Article/details/gtmctfjbnw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.daxiang520.top/Article/details/gtmjlnbuhl.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.gotoacloud.top/Article/details/gtbyplbctv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yonumen.top/Article/details/gtmzqhvddb.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ydzc1.top/Article/details/gtvvdjhotf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hammf.cn/Article/details/gtmgwarpkf.html

Go:   name := "Alex"; age := 20
来源：http://dali.yueranfly.top/Article/details/gtrwacnwpf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hnxiangtu.top/Article/details/gtmwbdidem.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.0kj1m.cn/Article/details/gtkrcphdjf.html

[A03] 常量定义
来源：http://dali.zhongyouzk.top/Article/details/gthzrggxlt.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.quarkkingdee.top/Article/details/gtktbfinus.html

PHP:  const PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvncavid.html

JS:   const PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtipedkmes.html

TS:   const PI: number = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtfsbcblmm.html

Java: static final double PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gtlqzfcanu.html

Go:   const PI = 3.14159
来源：http://dali.zycfv.cn/Article/details/gtkvidqhub.html

Ruby: PI = 3.14159
来源：http://dali.ivvv.top/Article/details/gtgolujjen.html

C#:   const double PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gtgacvfzvc.html

[A04] 判断变量类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqcebazs.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jianghu66.top/Article/details/gtxxomgekm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gotoacloud.top/Article/details/gtezejwzcj.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hywenlv.cn/Article/details/gtinsmmjrr.html

TS:   typeof x; x instanceof Date
来源：http://dali.cashguo.top/Article/details/gtegksbczi.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.chenjidiqi.icu/Article/details/gtaazpezbn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.dashuyun.cn/Article/details/gtjpeiqegy.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.wangshuangyany.cn/Article/details/gtolxgpqtr.html

C#:   x.GetType().Name; x is int
来源：http://dali.gaohongyu789.top/Article/details/gtirmpkiyj.html

[A05] 整数除法与取模
来源：http://dali.cashguo.top/Article/details/gtbqnlusck.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.feifeiyinyue.top/Article/details/gtibpavcht.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.cashguo.top/Article/details/gtnqrxplqo.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gtwhojkmpq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj20258.top/Article/details/gtwpcsgwqa.html

Java: 7 / 2; 7 % 2
来源：http://dali.hammf.cn/Article/details/gtkukrgnmt.html

Go:   7 / 2; 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gtvebgqrjl.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykxhbopt.html

C#:   7 / 2; 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtxehgfejb.html

[A06] 字符串转数字
来源：http://dali.hfpthk.cn/Article/details/gtbqimpykf.html

Py:   int("42"); float("3.14")
来源：http://dali.shzxlz.cn/Article/details/gtchxuspgg.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtemslatkz.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.9152youxi.cn/Article/details/gtvacotmjf.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yueranfly.top/Article/details/gtioguoprs.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.gotoacloud.top/Article/details/gtqatrjxzk.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.cdnleiting.top/Article/details/gtbtrcwnph.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hnxiangtu.top/Article/details/gtcielwsap.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.chenzaomai.com/Article/details/gtncypjjvg.html

[A07] 数字转字符串
来源：http://dali.fzhhl.top/Article/details/gtzqfahswv.html

Py:   str(42)
来源：http://dali.xuanzx.com/Article/details/gtyqjofyzb.html

PHP:  (string) 42; strval(42)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjmeplpg.html

JS:   String(42); (42).toString()
来源：http://dali.gogol.net.cn/Article/details/gtragqidkb.html

TS:   String(42)
来源：http://dali.jyoumei.cn/Article/details/gtvrfyganw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.pycfn.com/Article/details/gtawfjrdcl.html

Go:   strconv.Itoa(42)
来源：http://dali.iojbl.cn/Article/details/gtyqtqzrqd.html

Ruby: 42.to_s
来源：http://dali.yongpay.top/Article/details/gtsznfvaln.html

C#:   42.ToString()
来源：http://dali.svipenyu.cn/Article/details/gtlljkdcxn.html

[A08] 取整与四舍五入
来源：http://dali.daria6918.cn/Article/details/gttajhlwfz.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.havefunace.top/Article/details/gtaefejmhg.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.redwolf501.top/Article/details/gtcbuhkxxv.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.chenzaomai.com/Article/details/gtelvahdpu.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhengqikj.top/Article/details/gtqfaiotmj.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hnqzz.top/Article/details/gtmgsnbfxx.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.vqdsnc.cn/Article/details/gtpqigtoif.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.cashguo.top/Article/details/gtxqxbwlfp.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuctozdlk.html

[A09] 绝对值与最大最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvmbjfsu.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtqqipjeoh.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gtvwahxybj.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.mhx1999.top/Article/details/gtspshugqz.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupudexyo.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.ydzc1.top/Article/details/gtmeirwyhi.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.pengpengdd.cyou/Article/details/gtffxcmoyj.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.kuanghao11.cn/Article/details/gtnplkxmkv.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtegvweiej.html

[A10] 生成随机数
来源：http://dali.daria6918.cn/Article/details/gtwqmhbjss.html

Py:   import random; random.randint(1, 100)
来源：http://dali.hywenlv.cn/Article/details/gthkvjtlqn.html

PHP:  random_int(1, 100);
来源：http://dali.yonumen.top/Article/details/gtkdfdhgdk.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xuanzx.com/Article/details/gtixbdnyib.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cheryme.top/Article/details/gtckpndjph.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsofzeubf.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.fengsongda.top/Article/details/gtkkbtvdql.html

Ruby: rand(1..100)
来源：http://dali.haohaochexian.top/Article/details/gtsrkkvght.html

C#:   new Random().Next(1, 101)
来源：http://dali.meibo888.top/Article/details/gtqssqlhkr.html

[A11] 条件表达式（三元）
来源：http://dali.havefunace.top/Article/details/gtqjdyzrux.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jinqigfzy.top/Article/details/gtauoqjfsy.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.sufxvd.cn/Article/details/gtzrbvnvrr.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhoulong.xyz/Article/details/gtzmiltrvv.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.daria6918.cn/Article/details/gtgdjdyifh.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.c1oappe.top/Article/details/gtyloltxdp.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.havefunace.top/Article/details/gtebmvronn.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhiwuduotai.top/Article/details/gttdjowlug.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.bjfxy.top/Article/details/gtktggelcg.html

[A12] 字符串插值 / 格式化
来源：http://dali.hfpthk.cn/Article/details/gtxdivladt.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.xuetiantiany.cn/Article/details/gthxzwouff.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnoarytd.html

JS:   `Hello, ${name}!`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadcyzrrr.html

TS:   `Hello, ${name}!`
来源：http://dali.wangshuangyany.cn/Article/details/gttrexnkvb.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnfkgltgw.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.nwbrower.top/Article/details/gtddreruuh.html

Ruby: "Hello, #{name}!"
来源：http://dali.chenjidiqi.icu/Article/details/gtrtpxnczh.html

C#:   $"Hello, {name}!"
来源：http://dali.shzxlz.cn/Article/details/gtlazgmdjo.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.cdnleiting.top/Article/details/gtphcyulxt.html

Py:   "第一行\n第二行"
来源：http://dali.daria6918.cn/Article/details/gtiqunezfd.html

PHP:  "第一行\n第二行"
来源：http://dali.hnqzz.top/Article/details/gtsaldmcun.html

JS:   "第一行\n第二行"
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtvjkgjr.html

TS:   "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gtagxbqlgb.html

Java: "第一行\n第二行"
来源：http://dali.yvedp.cn/Article/details/gtzmaqtxtb.html

Go:   "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gttmbmflkw.html

Ruby: "第一行\n第二行"
来源：http://dali.daria6918.cn/Article/details/gtchlwlory.html

C#:   "第一行\n第二行"
来源：http://dali.zhoulong.xyz/Article/details/gtjlsbgazr.html

[A14] 注释写法
来源：http://dali.guannengcc.top/Article/details/gtfovhuvyc.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.xziqi.cn/Article/details/gtqewkrpmp.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yangfankeji.com/Article/details/gtbipytbyt.html

JS:   // 单行；/* 多行 */
来源：http://dali.andypj.xyz/Article/details/gtarmxzxva.html

TS:   // 单行；/* 多行 */
来源：http://dali.hnqzz.top/Article/details/gtuidwmtsq.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhixingplan.top/Article/details/gtkpykwjlc.html

Go:   // 单行；/* 多行 */
来源：http://dali.0kj1m.cn/Article/details/gtsghygwqr.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.shanyushiyangtech.top/Article/details/gtobdlijul.html

C#:   // 单行；/* 多行 */
来源：http://dali.c1oappe.top/Article/details/gtdbzfucvo.html

[A15] 空值判断与默认值
来源：http://dali.kuanghao11.cn/Article/details/gtphblmloh.html

Py:   value = data or "默认值"
来源：http://dali.jiagoushi.top/Article/details/gtbfvykvvp.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.shangyingyoupin.top/Article/details/gtinhuyvje.html

JS:   const value = data ?? "默认值";
来源：http://dali.shanyushiyangtech.top/Article/details/gtvehxlwfo.html

TS:   const value = data ?? "默认值";
来源：http://dali.sufxvd.cn/Article/details/gtnqdyjvbs.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.pengpengdd.cyou/Article/details/gtmbnrmcig.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.9152youxi.cn/Article/details/gtugahfdsz.html

Ruby: value = data || "默认值"
来源：http://dali.sysykeji.top/Article/details/gttjotgopo.html

C#:   var value = data ?? "默认值";
来源：http://dali.birdmap.top/Article/details/gtsffawflz.html

[A16] 真假值判断规则
来源：http://dali.yueranfly.top/Article/details/gtqykngnua.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.shuidangran.top/Article/details/gtyrdcbkiq.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.wangshuangyany.cn/Article/details/gtkqbibsoq.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.dashuyun.cn/Article/details/gtoccngkoz.html

TS:   if (!x) {}
来源：http://dali.yongpay.top/Article/details/gtwybbfigy.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.cashguo.top/Article/details/gtxtetikyi.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.pengpengdd.cyou/Article/details/gtemrpcdwi.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.xinyue.icu/Article/details/gtptidxqnr.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.shzxlz.cn/Article/details/gtkunhdhqk.html

[A17] 位运算
来源：http://dali.gzhubu.top/Article/details/gtkjlqsenl.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gtirhyjvza.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.fengsongda.top/Article/details/gtucoudiec.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yongpay.top/Article/details/gteknsekfg.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gtgjozduui.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gtxiveqmbp.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtgidtxwkv.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gtaucrkhrr.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ydzc1.top/Article/details/gtrsrghigw.html


<!-- 参考信息 -->