代发 wailian999

[U105] JS：节流
来源：http://dali.sufxvd.cn/Article/details/gttcgedsgi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yj20258888.top/Article/details/gtceqhfebr.html

[U106] JS：日期格式化
来源：http://dali.havefunace.top/Article/details/gtfhpklcza.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinqigufen.top/Article/details/gteslcfkct.html

[U107] JS：数字千分位
来源：http://dali.chenlongwang.top/Article/details/gthtfokylc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gtufysbxxl.html

[U108] JS：随机整数
来源：http://dali.dashuyun.cn/Article/details/gtxidmxydg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.sufxvd.cn/Article/details/gtrjlntnkg.html

[U109] JS：数组分组
来源：http://dali.nanxinkj.top/Article/details/gtklshghtp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.guowangkeji.top/Article/details/gtkanvuuwk.html

[U110] JS：数组分块
来源：http://dali.gogol.net.cn/Article/details/gtxftwikcu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shangyingyoupin.top/Article/details/gtckiuaygc.html

[U111] JS：对象转 Map
来源：http://dali.9152youxi.cn/Article/details/gtcsypotcl.html

new Map(Object.entries(obj))
来源：http://dali.xylfe.cn/Article/details/gtveazgear.html

[U112] JS：字符串补位
来源：http://dali.nanxuanxn.top/Article/details/gtrmxoxhff.html

"7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gtokeuisqq.html

[U113] JS：正则替换全部
来源：http://dali.gotoacloud.top/Article/details/gttyakgdui.html

s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtelipglvf.html

[U114] JS：JSON 深比较
来源：http://dali.yonumen.top/Article/details/gthtckvybk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.birdmap.top/Article/details/gtzmdkpdrm.html

[U115] JS：生成 UUID
来源：http://dali.haohaochexian.top/Article/details/gtcbjoiofr.html

crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmsuocym.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.chenlongwang.top/Article/details/gtessqxjkt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hfpthk.cn/Article/details/gtdmpjvelr.html

[U117] JS：单元测试
来源：http://dali.wangdashe.top/Article/details/gtojxtncwp.html

npm i -D vitest;  npx vitest
来源：http://dali.fengsongda.top/Article/details/gtlzyqpkne.html

[U118] JS：开发服务器
来源：http://dali.zycfv.cn/Article/details/gtrreyrphh.html

npm i -D vite;  npx vite
来源：http://dali.zycfv.cn/Article/details/gttxtjrogx.html

[U119] JS：生产构建
来源：http://dali.yj20258888.top/Article/details/gtnaoybssj.html

npx vite build
来源：http://dali.316326.xyz/Article/details/gtzqdjrsjf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.c1oappe.top/Article/details/gtwuytimoy.html

import.meta.env.VITE_API_URL
来源：http://dali.zhaomingkeji.xyz/Article/details/gthuxwviyk.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gteeoictce.html

统计汇总
来源：http://dali.zhiwuduotai.top/Article/details/gtfjxmncej.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtuojvytwp.html

按语言统计（条）：
来源：http://dali.jinqigufen.top/Article/details/gtveyquowy.html

Python ......... 252
来源：http://dali.jyoumei.cn/Article/details/gtwdpcvtgi.html

PHP ............ 252
来源：http://dali.haohaochexian.top/Article/details/gtmvupsmmw.html

JavaScript ..... 252
来源：http://dali.yj202588.top/Article/details/gtcsidpltz.html

TypeScript ..... 212
来源：http://dali.daxiang520.top/Article/details/gtdpieeazq.html

Java ........... 212
来源：http://dali.wangshuangyany.cn/Article/details/gthxvrksil.html

Go ............. 212
来源：http://dali.hnqzz.top/Article/details/gtunxhpuxh.html

Ruby ........... 212
来源：http://dali.zhongyouzk.top/Article/details/gtsujgjhzc.html

C# ............. 212
来源：http://dali.snrcjt.cn/Article/details/gtazjdqmjb.html

C .............. 30
来源：http://dali.hywenlv.cn/Article/details/gtcccxpyeb.html

C++ ............ 30
来源：http://dali.sysykeji.top/Article/details/gtpcpyrvzb.html

SQL ............ 90
来源：http://dali.jiagoushi.top/Article/details/gtyrhhtuzd.html

Bash ........... 80
来源：http://dali.yongpay.top/Article/details/gtpseldcmp.html

Kotlin ......... 15
来源：http://dali.cqqwz.cn/Article/details/gtkvpaqtiu.html

Swift .......... 15
来源：http://dali.aizwys.cn/Article/details/gthktnjocc.html

Lua ............ 10
来源：http://dali.gotoacloud.top/Article/details/gtzxjhwahj.html

Perl ........... 10
来源：http://dali.xziqi.cn/Article/details/gtiwvhkqgl.html

Scala .......... 10
来源：http://dali.chenzaomai.com/Article/details/gtebhpoiqn.html

------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gtghaqmyxc.html

合计 ........... 2106 条
来源：http://dali.yongpay.top/Article/details/gtwvfgfbra.html

按章节统计：
来源：http://dali.cdnleiting.top/Article/details/gtxjtjsjrj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yj202588.top/Article/details/gtwnuzzpfo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hnxiangtu.top/Article/details/gtvmqvgfrc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvevjmnu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sxryk.cn/Article/details/gtkrjnwgaq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.dianchejie.cn/Article/details/gtusrydxsv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.dianchejie.cn/Article/details/gtehxarraz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.dianchejie.cn/Article/details/gtmjbrxjgv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hammf.cn/Article/details/gtzvdwodrw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gtslssyyvk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhdqlfwx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sweek.top/Article/details/gtptoxkmlz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gthceczwdf.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gtmzxllgtq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gtblbwchrf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhengqikj.top/Article/details/gtwuwshipm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gtqnjxlcss.html

Q SQL 专题                              90
来源：http://dali.jqgfzy.top/Article/details/gtpxyilcgv.html

R Bash 专题                             80
来源：http://dali.svipenyu.cn/Article/details/gtrykutfym.html

S C / C++ 专题                          60
来源：http://dali.daxiang520.top/Article/details/gtnftrterc.html

T 其他语言补充                          60
来源：http://dali.ydzc1.top/Article/details/gtbdzlydfw.html

U 高频实用片段                         120
来源：http://dali.yonumen.top/Article/details/gtavqwanpa.html

------------------------------------
来源：http://dali.guannengcc.top/Article/details/gtdpcypkwh.html

合计                                  2106 条
来源：http://dali.chenjidiqi.icu/Article/details/gtlwdjpvan.html

--------------------------------------------------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gteexpbdpb.html

使用提醒
来源：http://dali.chenzaomai.com/Article/details/gtjmnrdptr.html

--------------------------------------------------------------------------------
来源：http://dali.xuanzx.com/Article/details/gtuhnaetdg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.316326.xyz/Article/details/gtszzeikfk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gtgbabuisb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.gaohongyu789.top/Article/details/gtujnerpcd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.smart0.xyz/Article/details/gttepnyyrs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.sysykeji.top/Article/details/gtglwpquum.html

—— 文件结束 ——
来源：http://dali.9152youxi.cn/Article/details/gtmtyicuoc.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtjlrhhhvf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.nanxinkj.top/Article/details/gtalmcvfob.html

Common Programming Examples Cheat Book
来源：http://dali.cashguo.top/Article/details/gtqkcwyfoz.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtcalqlhvb.html

【收录内容】
来源：http://dali.havefunace.top/Article/details/gtfacpfhyw.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.c1oappe.top/Article/details/gtzbvretrk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yueranfly.top/Article/details/gtfzsclzko.html

SQL · Bash · C · C++
来源：http://dali.tianlin.xyz/Article/details/gtnamohyos.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.wangdashe.top/Article/details/gtwkbqlzte.html

【使用说明】
来源：http://dali.ydzc1.top/Article/details/gtqilnocvm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.wangshuangyany.cn/Article/details/gtearupudn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.sweek.top/Article/details/gtwkprghkr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xuanzx.com/Article/details/gtgqrylsbo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhongyouzk.top/Article/details/gtkxwgzfvr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.gogol.net.cn/Article/details/gtsoullfxf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.sufxvd.cn/Article/details/gtbawwlabj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhengqikj.top/Article/details/gtwrjjjpdb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.meibo888.top/Article/details/gtyktwuomj.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shangyingyoupin.top/Article/details/gtnqgogefv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.sysykeji.top/Article/details/gthgvooscd.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.mhx1999.top/Article/details/gtetnfpsqm.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hammf.cn/Article/details/gthdshafst.html

【文件统计】
来源：http://dali.shangyingyoupin.top/Article/details/gtqayjqqay.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.fengsongda.top/Article/details/gtlkzxqkce.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gtlumktalp.html

目  录
来源：http://dali.fzhhl.top/Article/details/gtxvzktrqn.html

--------------------------------------------------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gtvcdmwcwq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xylfe.cn/Article/details/gtuxmgursg.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.c1oappe.top/Article/details/gtfnlehvwd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffdnqvtg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.kuanghao11.cn/Article/details/gttogccvtt.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtnxgdzneg.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hammf.cn/Article/details/gtfplkcsju.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yueranfly.top/Article/details/gtwtvvwijl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.redwolf501.top/Article/details/gtojezunsd.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gtbcepvvzn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.cashguo.top/Article/details/gtgmfpugyp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gtcvxufgxg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hysaishi.cn/Article/details/gtlhwxavmu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jyoumei.cn/Article/details/gtwkfcpriw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtirigcnaw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtoopqnugb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gtjydsuhlj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.guowangkeji.top/Article/details/gtrhahjigq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.sufxvd.cn/Article/details/gtdhchbggd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.mhx1999.top/Article/details/gtduhngger.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuetiantiany.cn/Article/details/gtcjgdlyei.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.c1oappe.top/Article/details/gttslnnrfx.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtjlofdrvo.html

A. 基础语法与类型
来源：http://dali.c1oappe.top/Article/details/gtnshkiqfy.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtsdgqjrcc.html

[A01] Hello World
来源：http://dali.snrcjt.cn/Article/details/gtfzwxmjbm.html

Py:   print("Hello, World!")
来源：http://dali.gogol.net.cn/Article/details/gtgpqgeeyq.html

PHP:  echo "Hello, World!";
来源：http://dali.zycfv.cn/Article/details/gtkurbykqb.html

JS:   console.log("Hello, World!");
来源：http://dali.iojbl.cn/Article/details/gtdbwssuwy.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.daria6918.cn/Article/details/gtgfvimjzb.html

Java: System.out.println("Hello, World!");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcceajik.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.kuanghao11.cn/Article/details/gtlvuslqdg.html

Ruby: puts "Hello, World!"
来源：http://dali.chenlongwang.top/Article/details/gtoobmaxcs.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.quarkkingdee.top/Article/details/gtmqggbhgw.html

[A02] 变量声明与赋值
来源：http://dali.cdnleiting.top/Article/details/gtlwfefatj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cqqwz.cn/Article/details/gtqrptqbvu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.snrcjt.cn/Article/details/gtadektxek.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jiagoushi.top/Article/details/gtrkxldhbh.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.9152youxi.cn/Article/details/gtqcjxhlaj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.cqqwz.cn/Article/details/gtggsuvpla.html

Go:   name := "Alex"; age := 20
来源：http://dali.9152youxi.cn/Article/details/gtahkoywzg.html

Ruby: name = "Alex"; age = 20
来源：http://dali.kuanghao11.cn/Article/details/gthkhrxpny.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.shuidangran.top/Article/details/gtoxsnartz.html

[A03] 常量定义
来源：http://dali.9152youxi.cn/Article/details/gtzdvtdnck.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yuxming.cn/Article/details/gtcbgmlfzq.html

PHP:  const PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gtrkidsiun.html

JS:   const PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gttgcwubel.html

TS:   const PI: number = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtnxxldazf.html

Java: static final double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtmtomyhii.html

Go:   const PI = 3.14159
来源：http://dali.zdqjudy.top/Article/details/gtnofnqvfl.html

Ruby: PI = 3.14159
来源：http://dali.bjfxy.top/Article/details/gteglclusw.html

C#:   const double PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtlqzbougj.html

[A04] 判断变量类型
来源：http://dali.nanxuanxn.top/Article/details/gtqvjddoqt.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.shuidangran.top/Article/details/gtlucvpcwv.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.tianlin.xyz/Article/details/gtcusgfvxt.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.redwolf501.top/Article/details/gtrafmixrq.html

TS:   typeof x; x instanceof Date
来源：http://dali.jlsjyb.cn/Article/details/gtilutahvj.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.guannengcc.top/Article/details/gtwfeajmeu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gtjmospbrj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ppjwa.cn/Article/details/gtjlkntnwh.html

C#:   x.GetType().Name; x is int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjoajnxl.html

[A05] 整数除法与取模
来源：http://dali.kuanghao11.cn/Article/details/gtttxxhbwy.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yj20258888.top/Article/details/gtxzkawtvj.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gtdhvsqcdu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yongpay.top/Article/details/gtnpjdhgai.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.fzhhl.top/Article/details/gtenwusnre.html

Java: 7 / 2; 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmaurxgn.html

Go:   7 / 2; 7 % 2
来源：http://dali.sysykeji.top/Article/details/gtwgevqbpq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.sweek.top/Article/details/gtxqoszvfi.html

C#:   7 / 2; 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gtvmouexqn.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gtftniigiu.html

Py:   int("42"); float("3.14")
来源：http://dali.daria6918.cn/Article/details/gtaglznlgx.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.feifeiyinyue.top/Article/details/gtukjnefgd.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yanxiufei.cn/Article/details/gteudaglvc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfbwxdvm.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cashguo.top/Article/details/gtdbisbqom.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.nwbrower.top/Article/details/gtooehpfbu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.kuanghao11.cn/Article/details/gtuufhohqi.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jinqigfzy.top/Article/details/gtefbkmask.html

[A07] 数字转字符串
来源：http://dali.hysaishi.cn/Article/details/gtiogcubwh.html

Py:   str(42)
来源：http://dali.wangdashe.top/Article/details/gtfreikjqc.html

PHP:  (string) 42; strval(42)
来源：http://dali.jiagoushi.top/Article/details/gtroybhqax.html

JS:   String(42); (42).toString()
来源：http://dali.quarkkingdee.top/Article/details/gtkouqzglf.html

TS:   String(42)
来源：http://dali.ivvv.top/Article/details/gtyzezxrvy.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yueranfly.top/Article/details/gthjmapkjn.html

Go:   strconv.Itoa(42)
来源：http://dali.xuanzx.com/Article/details/gtqwmelbyw.html

Ruby: 42.to_s
来源：http://dali.ydzc1.top/Article/details/gtdjnmdegf.html

C#:   42.ToString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsolqfxto.html

[A08] 取整与四舍五入
来源：http://dali.fzhhl.top/Article/details/gtbdudkwlt.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbbxwiri.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.daxiang520.top/Article/details/gtctlqicis.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.daxiang520.top/Article/details/gtvnhhhinh.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.birdmap.top/Article/details/gtflulkuyh.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jinqigufen.top/Article/details/gtbogpdwih.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.hywenlv.cn/Article/details/gtscsgnxbc.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.daria6918.cn/Article/details/gtmelonikg.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.chenjidiqi.icu/Article/details/gtguvtmeeb.html

[A09] 绝对值与最大最小值
来源：http://dali.guannengcc.top/Article/details/gtalcdscez.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jianghu66.top/Article/details/gtmshrlpot.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjdeugep.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtjozyulxk.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gtidkjbcbf.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yj20258888.top/Article/details/gtjryikodd.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hnxiangtu.top/Article/details/gtyfhiqxsu.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.chenzaomai.com/Article/details/gtguxczlcw.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gtkxslummp.html

[A10] 生成随机数
来源：http://dali.hfpthk.cn/Article/details/gtcwyimmwb.html

Py:   import random; random.randint(1, 100)
来源：http://dali.dianchejie.cn/Article/details/gtkqkfjsym.html

PHP:  random_int(1, 100);
来源：http://dali.guowangkeji.top/Article/details/gtdfulruke.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhiwuduotai.top/Article/details/gthrhxjuxo.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.mhx1999.top/Article/details/gtcfqjkazd.html

Java: new Random().nextInt(100) + 1
来源：http://dali.ppjwa.cn/Article/details/gtxkjpwyjl.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.xziqi.cn/Article/details/gtkwtqyohq.html

Ruby: rand(1..100)
来源：http://dali.bjfxy.top/Article/details/gtrnayebcc.html

C#:   new Random().Next(1, 101)
来源：http://dali.wangshuangyany.cn/Article/details/gtnfwyddlp.html

[A11] 条件表达式（三元）
来源：http://dali.bjfxy.top/Article/details/gtfwmofiqd.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.smart0.xyz/Article/details/gtxvwmzeez.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.iojbl.cn/Article/details/gtvegcmien.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.tanke756.top/Article/details/gtkbdhltob.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.fengsongda.top/Article/details/gtjnhglzvb.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yuanzhike.top/Article/details/gtbvtazgou.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.smart0.xyz/Article/details/gtcynbhiya.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.hammf.cn/Article/details/gtvmkpmimg.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.guannengcc.top/Article/details/gtysdefslw.html

[A12] 字符串插值 / 格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtuoxlwhlw.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.gogol.net.cn/Article/details/gtkoyqqvhx.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yj20258888.top/Article/details/gtcwbatgvr.html

JS:   `Hello, ${name}!`
来源：http://dali.sysykeji.top/Article/details/gtsnkbylpo.html

TS:   `Hello, ${name}!`
来源：http://dali.zhengqikj.top/Article/details/gteibiowrk.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yj20258888.top/Article/details/gtuwlkgyjf.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.chenzaomai.com/Article/details/gtwaaxlynr.html

Ruby: "Hello, #{name}!"
来源：http://dali.xziqi.cn/Article/details/gtzmyoknvl.html

C#:   $"Hello, {name}!"
来源：http://dali.cucudq.cn/Article/details/gtnybbkqcs.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.fzhhl.top/Article/details/gtncdehmwd.html

Py:   "第一行\n第二行"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwffagfdn.html

PHP:  "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gtwojjyzrt.html

JS:   "第一行\n第二行"
来源：http://dali.andypj.xyz/Article/details/gtxbdhroot.html

TS:   "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gtfyfftprm.html

Java: "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gtqxyqflxw.html

Go:   "第一行\n第二行"
来源：http://dali.nanxinkj.top/Article/details/gtycudgdpm.html

Ruby: "第一行\n第二行"
来源：http://dali.xuanzx.com/Article/details/gtfmnbuxrw.html

C#:   "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gtrbiivmtq.html

[A14] 注释写法
来源：http://dali.zdqjudy.top/Article/details/gtopdwzuhh.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbdhridz.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.daxiang520.top/Article/details/gtplhnvyir.html

JS:   // 单行；/* 多行 */
来源：http://dali.jianghu66.top/Article/details/gtbwnirmbj.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvsbdhrx.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.dashuyun.cn/Article/details/gtuskfgmfa.html

Go:   // 单行；/* 多行 */
来源：http://dali.smart0.xyz/Article/details/gtdboeusow.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.wangshuangyany.cn/Article/details/gtfyhrkwpr.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhoulong.xyz/Article/details/gtpdkgrtxm.html

[A15] 空值判断与默认值
来源：http://dali.9152youxi.cn/Article/details/gtjvjrtkxx.html

Py:   value = data or "默认值"
来源：http://dali.ydzc1.top/Article/details/gtjteeveir.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.hywenlv.cn/Article/details/gtelnvmbqi.html

JS:   const value = data ?? "默认值";
来源：http://dali.vqdsnc.cn/Article/details/gtbeiorphy.html

TS:   const value = data ?? "默认值";
来源：http://dali.shzxlz.cn/Article/details/gtzskdsuzq.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.mhx1999.top/Article/details/gtyujcgexf.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.bjfxy.top/Article/details/gtlostyqxb.html

Ruby: value = data || "默认值"
来源：http://dali.gaohongyu789.top/Article/details/gtsbikpbly.html

C#:   var value = data ?? "默认值";
来源：http://dali.quarkkingdee.top/Article/details/gtuyllbsbj.html

[A16] 真假值判断规则
来源：http://dali.kuanghao11.cn/Article/details/gtqbhpbpzi.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.bjfxy.top/Article/details/gtticeeltx.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.nanxuanxn.top/Article/details/gtohnvsxwz.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.guowangkeji.top/Article/details/gtyjyyjrcb.html

TS:   if (!x) {}
来源：http://dali.bjfxy.top/Article/details/gtvidkvsnj.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhovegtf.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jyoumei.cn/Article/details/gtwkzeqjdv.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.0kj1m.cn/Article/details/gtrdtatpfx.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.vqdsnc.cn/Article/details/gtkfqbnciy.html

[A17] 位运算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnykvdxbx.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenjidiqi.icu/Article/details/gtepokxieh.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkdmklvy.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgfzy.top/Article/details/gtivmtuvam.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.daria6918.cn/Article/details/gtfmmhdnmu.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shzxlz.cn/Article/details/gtywhqcezk.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gtrlsfrjzj.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtldpxdiwh.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gtmuecsmmv.html

[A18] 字符与 ASCII 码互转
来源：http://dali.snrcjt.cn/Article/details/gtxjxvnasj.html

Py:   ord("A"); chr(65)
来源：http://dali.daria6918.cn/Article/details/gtpnzpjktd.html

PHP:  ord("A"); chr(65)
来源：http://dali.hnxiangtu.top/Article/details/gtzghpgeio.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xinyue.icu/Article/details/gttalfklha.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.smart0.xyz/Article/details/gtojlkqjek.html

Java: (int) 'A'; (char) 65
来源：http://dali.shangyingyoupin.top/Article/details/gtfzwckbsb.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuiqtkivz.html

Ruby: "A".ord; 65.chr
来源：http://dali.ivvv.top/Article/details/gtnpxymyly.html


<!-- 参考信息 -->