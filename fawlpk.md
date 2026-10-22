代发 wailian999

[U105] JS：节流
来源：http://dali.dashuyun.cn/Article/details/gt2mzoctzse.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.chenzaomai.com/Article/details/gt2unqgqhje.html

[U106] JS：日期格式化
来源：http://dali.ppjwa.cn/Article/details/gt2ecfjvwcm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.nanxuanxn.top/Article/details/gt2rnicqlmd.html

[U107] JS：数字千分位
来源：http://dali.zhongyouzk.top/Article/details/gt2qxwtjinn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.aizwys.cn/Article/details/gt2pelyqeip.html

[U108] JS：随机整数
来源：http://dali.pycfn.com/Article/details/gt2bovskjhg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hammf.cn/Article/details/gt2iqtmlxvw.html

[U109] JS：数组分组
来源：http://dali.hammf.cn/Article/details/gt2ghmowcje.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rumkajit.html

[U110] JS：数组分块
来源：http://dali.redwolf501.top/Article/details/gt2swwojaiu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hfpthk.cn/Article/details/gt2sbailbny.html

[U111] JS：对象转 Map
来源：http://dali.daxiang520.top/Article/details/gt2udnckbtf.html

new Map(Object.entries(obj))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2temiffni.html

[U112] JS：字符串补位
来源：http://dali.jiagoushi.top/Article/details/gt2zwahwmzo.html

"7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gt2lecthtlt.html

[U113] JS：正则替换全部
来源：http://dali.andypj.xyz/Article/details/gt2drcisyfw.html

s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gt2qhzfbfpv.html

[U114] JS：JSON 深比较
来源：http://dali.cheryme.top/Article/details/gt2vjdtxwzj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.birdmap.top/Article/details/gt2khypmmig.html

[U115] JS：生成 UUID
来源：http://dali.hywenlv.cn/Article/details/gt2ayfgfzkv.html

crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gt2odcjgwio.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.sysykeji.top/Article/details/gt2yfynfqnd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hammf.cn/Article/details/gt2keqiejln.html

[U117] JS：单元测试
来源：http://dali.daria6918.cn/Article/details/gt2rkulxjse.html

npm i -D vitest;  npx vitest
来源：http://dali.jinqigfzy.top/Article/details/gt2otkdoobg.html

[U118] JS：开发服务器
来源：http://dali.yj20258888.top/Article/details/gt2gjijqrvi.html

npm i -D vite;  npx vite
来源：http://dali.gaohongyu789.top/Article/details/gt2pewemvqy.html

[U119] JS：生产构建
来源：http://dali.svipenyu.cn/Article/details/gt2kwfrpadz.html

npx vite build
来源：http://dali.zhiwuduotai.top/Article/details/gt2cmfjtnmf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.sufxvd.cn/Article/details/gt2qmpnevyq.html

import.meta.env.VITE_API_URL
来源：http://dali.sysykeji.top/Article/details/gt2injdsyqt.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2jexnaytz.html

统计汇总
来源：http://dali.cashguo.top/Article/details/gt2qdrnnrjl.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2lyisdllg.html

按语言统计（条）：
来源：http://dali.zhiwuduotai.top/Article/details/gt2rdqwqutn.html

Python ......... 252
来源：http://dali.0kj1m.cn/Article/details/gt2dsegqvpb.html

PHP ............ 252
来源：http://dali.ydzc1.top/Article/details/gt2qnkpnqmv.html

JavaScript ..... 252
来源：http://dali.dianchejie.cn/Article/details/gt2tznshufq.html

TypeScript ..... 212
来源：http://dali.fzhhl.top/Article/details/gt2odnwebop.html

Java ........... 212
来源：http://dali.zhoulong.xyz/Article/details/gt2tmjxttbf.html

Go ............. 212
来源：http://dali.aizwys.cn/Article/details/gt2bhevcptd.html

Ruby ........... 212
来源：http://dali.wangdashe.top/Article/details/gt2grtdxklb.html

C# ............. 212
来源：http://dali.hysaishi.cn/Article/details/gt2sjflifcv.html

C .............. 30
来源：http://dali.xuetiantiany.cn/Article/details/gt2yjfmoomx.html

C++ ............ 30
来源：http://dali.tanke756.top/Article/details/gt2scdtqhxh.html

SQL ............ 90
来源：http://dali.hnxiangtu.top/Article/details/gt2kpoghtyx.html

Bash ........... 80
来源：http://dali.jqgufenzy.top/Article/details/gt2odxbpcfw.html

Kotlin ......... 15
来源：http://dali.quarkkingdee.top/Article/details/gt2ddzqzbpb.html

Swift .......... 15
来源：http://dali.jinqigufen.top/Article/details/gt2rdpnkeqw.html

Lua ............ 10
来源：http://dali.yj20258888.top/Article/details/gt2sfrlsavu.html

Perl ........... 10
来源：http://dali.ppjwa.cn/Article/details/gt2tcdfrait.html

Scala .......... 10
来源：http://dali.xziqi.cn/Article/details/gt2suzaoorj.html

------------------------------------
来源：http://dali.yj20258888.top/Article/details/gt2eerqvhct.html

合计 ........... 2106 条
来源：http://dali.pycfn.com/Article/details/gt2hzsijgnq.html

按章节统计：
来源：http://dali.ydzc1.top/Article/details/gt2dlsxjpfz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.meibo888.top/Article/details/gt2ytcwqylh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zdqjudy.top/Article/details/gt2zrqzfkit.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yuxming.cn/Article/details/gt2vbdbiwpl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yuxming.cn/Article/details/gt2htdprddc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.c1oappe.top/Article/details/gt2pvywgmyu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.gaohongyu789.top/Article/details/gt2qntdlqmf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yvedp.cn/Article/details/gt2zcdjekso.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jianghu66.top/Article/details/gt2rtyilmqw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.kuanghao11.cn/Article/details/gt2lwfssbdi.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ppjwa.cn/Article/details/gt2asxiycih.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gt2gcmpagxk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gt2dbpnivhc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gt2yjtpufrg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shuidangran.top/Article/details/gt2yfdygaye.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ivvv.top/Article/details/gt2qqvwwkua.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gt2wioonooq.html

Q SQL 专题                              90
来源：http://dali.gotoacloud.top/Article/details/gt2aklyibwi.html

R Bash 专题                             80
来源：http://dali.sufxvd.cn/Article/details/gt2licumenf.html

S C / C++ 专题                          60
来源：http://dali.daria6918.cn/Article/details/gt2kusboxpw.html

T 其他语言补充                          60
来源：http://dali.sweek.top/Article/details/gt2jxbjhwog.html

U 高频实用片段                         120
来源：http://dali.yonumen.top/Article/details/gt2jbjkcfoa.html

------------------------------------
来源：http://dali.ydzc1.top/Article/details/gt2qjitbaia.html

合计                                  2106 条
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mxhnspfw.html

--------------------------------------------------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gt2hojkszbp.html

使用提醒
来源：http://dali.pycfn.com/Article/details/gt2jjtudkhs.html

--------------------------------------------------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gt2eiionwvh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.chenjidiqi.icu/Article/details/gt2ctuohell.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.nanxinkj.top/Article/details/gt2ylxsvmzy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zdqjudy.top/Article/details/gt2hwbezlvi.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yj20258.top/Article/details/gt2ededtvzp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.fzhhl.top/Article/details/gt2aczifotk.html

—— 文件结束 ——
来源：http://dali.iojbl.cn/Article/details/gt2zsdhsibt.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2wmpvsgbc.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yuanzhike.top/Article/details/gt2rfmzjppb.html

Common Programming Examples Cheat Book
来源：http://dali.ppjwa.cn/Article/details/gt2tulbynmp.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2xfoixysu.html

【收录内容】
来源：http://dali.shuidangran.top/Article/details/gt2sicbxhqn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cucudq.cn/Article/details/gt2hhhstfiz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.guowangkeji.top/Article/details/gt2gkhdyvfl.html

SQL · Bash · C · C++
来源：http://dali.hnqzz.top/Article/details/gt2qgtrkgip.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.wangshuangyany.cn/Article/details/gt2mylebdao.html

【使用说明】
来源：http://dali.hnqzz.top/Article/details/gt2wivvwbay.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hfpthk.cn/Article/details/gt2bfvlvnah.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.vqdsnc.cn/Article/details/gt2lzkfdhxw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hnqzz.top/Article/details/gt2mrzktbne.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2dgovbhov.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.shzxlz.cn/Article/details/gt2vuirgifl.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2obdxwisx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yj202588.top/Article/details/gt2jhmgsmta.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cnwkftdh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shuidangran.top/Article/details/gt2ipczkzzw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ppjwa.cn/Article/details/gt2opixqxtj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.dashuyun.cn/Article/details/gt2bhqvnurd.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.dianchejie.cn/Article/details/gt2fawziwdw.html

【文件统计】
来源：http://dali.fengsongda.top/Article/details/gt2hcapvqni.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.mhx1999.top/Article/details/gt2riybcxku.html

--------------------------------------------------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gt2codvqemi.html

目  录
来源：http://dali.guannengcc.top/Article/details/gt2jjmmyuni.html

--------------------------------------------------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gt2twhbfvlh.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.meibo888.top/Article/details/gt2yqysravn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yj202588.top/Article/details/gt2owggssgo.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.0kj1m.cn/Article/details/gt2yllcowqn.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ppjwa.cn/Article/details/gt2gkfzkknz.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.aizwys.cn/Article/details/gt2zkubhghl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gbnkagwx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ibxkobhk.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2unmecgju.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jiagoushi.top/Article/details/gt2xvmczzhx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yj20258888.top/Article/details/gt2yjztffdl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.cashguo.top/Article/details/gt2mwrhkjdh.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gt2ktzbhqur.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.wangdashe.top/Article/details/gt2kipaaflh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.sweek.top/Article/details/gt2vyxxstsq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hammf.cn/Article/details/gt2laanmcbp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhengqikj.top/Article/details/gt2sapturag.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yangfankeji.com/Article/details/gt2mqadescp.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.havefunace.top/Article/details/gt2tvoynoku.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2eogkjgmu.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shzxlz.cn/Article/details/gt2ohwhsnwh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.fzhhl.top/Article/details/gt2ytxuyduz.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2mxmrcbkj.html

A. 基础语法与类型
来源：http://dali.yj20258.top/Article/details/gt2erqfeolm.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2zkiawozs.html

[A01] Hello World
来源：http://dali.mhx1999.top/Article/details/gt2afgmpyfh.html

Py:   print("Hello, World!")
来源：http://dali.yueranfly.top/Article/details/gt2xelgzkoh.html

PHP:  echo "Hello, World!";
来源：http://dali.yj20258888.top/Article/details/gt2cimvxarh.html

JS:   console.log("Hello, World!");
来源：http://dali.yongpay.top/Article/details/gt2nyxhigwx.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hnxiangtu.top/Article/details/gt2qsabceiq.html

Java: System.out.println("Hello, World!");
来源：http://dali.yj20258.top/Article/details/gt2uhoobtbz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.mhx1999.top/Article/details/gt2hwgxmnpm.html

Ruby: puts "Hello, World!"
来源：http://dali.nanxuanxn.top/Article/details/gt2jqshjvhx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.tian-w.cn/Article/details/gt2hlnqgvoq.html

[A02] 变量声明与赋值
来源：http://dali.jyoumei.cn/Article/details/gt2pihggiww.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ppjwa.cn/Article/details/gt2vxsasevz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gt2xvwvbyvx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hammf.cn/Article/details/gt2lwtycsfd.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yj20258888.top/Article/details/gt2reuyzcjm.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.meibo888.top/Article/details/gt2bvibupdl.html

Go:   name := "Alex"; age := 20
来源：http://dali.hammf.cn/Article/details/gt2undrjdeh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.9152youxi.cn/Article/details/gt2eqglaadf.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.sweek.top/Article/details/gt2ngdesnjg.html

[A03] 常量定义
来源：http://dali.wangdashe.top/Article/details/gt2vpjtejpk.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xhnxauys.html

PHP:  const PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gt2ajrpqbdt.html

JS:   const PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gt2evbfwnii.html

TS:   const PI: number = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gt2aduaiigs.html

Java: static final double PI = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gt2rofrxtma.html

Go:   const PI = 3.14159
来源：http://dali.xuetiantiany.cn/Article/details/gt2cwciecdz.html

Ruby: PI = 3.14159
来源：http://dali.chenlongwang.top/Article/details/gt2epcchpsc.html

C#:   const double PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gt2bnqgehqd.html

[A04] 判断变量类型
来源：http://dali.ydzc1.top/Article/details/gt2czahrnlq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yvedp.cn/Article/details/gt2jfzvwzam.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yuanzhike.top/Article/details/gt2pjcrmryx.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.cqqwz.cn/Article/details/gt2wwgoeizb.html

TS:   typeof x; x instanceof Date
来源：http://dali.daria6918.cn/Article/details/gt2bxqslqdg.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hywenlv.cn/Article/details/gt2fnpxjfwa.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.snrcjt.cn/Article/details/gt2nwtyuyuu.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jinqigufen.top/Article/details/gt2jmocvyle.html

C#:   x.GetType().Name; x is int
来源：http://dali.cdnleiting.top/Article/details/gt2asadpgqr.html

[A05] 整数除法与取模
来源：http://dali.ydzc1.top/Article/details/gt2istntdol.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.havefunace.top/Article/details/gt2tvnzydvd.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gt2ukewkynt.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gt2vsnonjga.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sweek.top/Article/details/gt2izntviwz.html

Java: 7 / 2; 7 % 2
来源：http://dali.mhx1999.top/Article/details/gt2mnkboqga.html

Go:   7 / 2; 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gt2gojurrct.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gt2oeorepnm.html

C#:   7 / 2; 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gt2bouwkljp.html

[A06] 字符串转数字
来源：http://dali.ehwqpu.com/Article/details/gt2jyzqulvb.html

Py:   int("42"); float("3.14")
来源：http://dali.ydzc1.top/Article/details/gt2xzyentls.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.daxiang520.top/Article/details/gt2qaynriro.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ivvv.top/Article/details/gt2ybdenlst.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jlsjyb.cn/Article/details/gt2qdrvzdgg.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.haohaochexian.top/Article/details/gt2qedtsanl.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.mhx1999.top/Article/details/gt2cxyjchye.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jinqigufen.top/Article/details/gt2ofcnfepy.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.nwbrower.top/Article/details/gt2hzbrwcol.html

[A07] 数字转字符串
来源：http://dali.yangfankeji.com/Article/details/gt2uyaqdcid.html

Py:   str(42)
来源：http://dali.vqdsnc.cn/Article/details/gt2bvotcynz.html

PHP:  (string) 42; strval(42)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xnhcdnwm.html

JS:   String(42); (42).toString()
来源：http://dali.guowangkeji.top/Article/details/gt2otyqvhoa.html

TS:   String(42)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fzvdjylt.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ivvv.top/Article/details/gt2kzsnbfjj.html

Go:   strconv.Itoa(42)
来源：http://dali.haohaochexian.top/Article/details/gt2vuajqtxu.html

Ruby: 42.to_s
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2owdjrspr.html

C#:   42.ToString()
来源：http://dali.iojbl.cn/Article/details/gt2urizlrns.html

[A08] 取整与四舍五入
来源：http://dali.vqdsnc.cn/Article/details/gt2ewxsluaa.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.cheryme.top/Article/details/gt2juresmhn.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.smart0.xyz/Article/details/gt2urolyltw.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gt2tutelymx.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bgcsszgn.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jqgufenzy.top/Article/details/gt2rpvqnlef.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.tian-w.cn/Article/details/gt2bqzgelzh.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.shangyingyoupin.top/Article/details/gt2fiahxrhe.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hysaishi.cn/Article/details/gt2hrliuzdq.html

[A09] 绝对值与最大最小值
来源：http://dali.hywenlv.cn/Article/details/gt2igvotzmb.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.daria6918.cn/Article/details/gt2tjjnavqc.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jqgfzy.top/Article/details/gt2rbtqmsbv.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2hvmrlpco.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.cheryme.top/Article/details/gt2srwpavym.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gt2gybyisnk.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.fzhhl.top/Article/details/gt2ddwgugxj.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jlsjyb.cn/Article/details/gt2gfkimnlv.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gt2ezyemcfh.html

[A10] 生成随机数
来源：http://dali.jiagoushi.top/Article/details/gt2afwuozmx.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yongpay.top/Article/details/gt2mbmasjbs.html

PHP:  random_int(1, 100);
来源：http://dali.aizwys.cn/Article/details/gt2ncwolgmr.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hysaishi.cn/Article/details/gt2whfzqila.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yueranfly.top/Article/details/gt2uecvzlep.html

Java: new Random().nextInt(100) + 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2mcfozxgr.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.meibo888.top/Article/details/gt2qbywkybs.html

Ruby: rand(1..100)
来源：http://dali.hywenlv.cn/Article/details/gt2viizufbp.html

C#:   new Random().Next(1, 101)
来源：http://dali.hysaishi.cn/Article/details/gt2hkqgfimu.html

[A11] 条件表达式（三元）
来源：http://dali.zhoulong.xyz/Article/details/gt2ivxgvucj.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zycfv.cn/Article/details/gt2clusvazb.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.cheryme.top/Article/details/gt2lzjxauep.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.dianchejie.cn/Article/details/gt2grvqzqqi.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jqgfzy.top/Article/details/gt2kppuphee.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.316326.xyz/Article/details/gt2cjqllomq.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.c1oappe.top/Article/details/gt2gpmqywmt.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.ydzc1.top/Article/details/gt2hodemlgt.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.hnxiangtu.top/Article/details/gt2xwurjcrr.html

[A12] 字符串插值 / 格式化
来源：http://dali.yanxiufei.cn/Article/details/gt2befqrsdm.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.nanxuanxn.top/Article/details/gt2dzxxfbqz.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jqgfzy.top/Article/details/gt2djnnhawe.html

JS:   `Hello, ${name}!`
来源：http://dali.zhoulong.xyz/Article/details/gt2hdrhnkoh.html

TS:   `Hello, ${name}!`
来源：http://dali.gotoacloud.top/Article/details/gt2vhqwwpjh.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yangfankeji.com/Article/details/gt2biikujlq.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.sufxvd.cn/Article/details/gt2pdtaymuo.html

Ruby: "Hello, #{name}!"
来源：http://dali.cashguo.top/Article/details/gt2bqrnetwj.html

C#:   $"Hello, {name}!"
来源：http://dali.pengpengdd.cyou/Article/details/gt2lnjfsjtd.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.hnxiangtu.top/Article/details/gt2xsyukxox.html

Py:   "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gt2zsbhndbb.html

PHP:  "第一行\n第二行"
来源：http://dali.jinqigfzy.top/Article/details/gt2iglgazvo.html

JS:   "第一行\n第二行"
来源：http://dali.nanxinkj.top/Article/details/gt2strgnxkk.html

TS:   "第一行\n第二行"
来源：http://dali.hfpthk.cn/Article/details/gt2kisdhyjz.html

Java: "第一行\n第二行"
来源：http://dali.316326.xyz/Article/details/gt2ifpcvcla.html

Go:   "第一行\n第二行"
来源：http://dali.9152youxi.cn/Article/details/gt2rhcrmhuv.html

Ruby: "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gt2yynqoysd.html

C#:   "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gt2gakvfqnz.html

[A14] 注释写法
来源：http://dali.yj202588.top/Article/details/gt2wnmiazsd.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pwzighzi.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.aizwys.cn/Article/details/gt2qopglsyh.html

JS:   // 单行；/* 多行 */
来源：http://dali.dianchejie.cn/Article/details/gt2vooezhkc.html

TS:   // 单行；/* 多行 */
来源：http://dali.aizwys.cn/Article/details/gt2zdidobes.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.fengsongda.top/Article/details/gt2tuigzhnb.html

Go:   // 单行；/* 多行 */
来源：http://dali.bjfxy.top/Article/details/gt2ggnbasqb.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hqwuofnn.html

C#:   // 单行；/* 多行 */
来源：http://dali.ivvv.top/Article/details/gt2hqgvyntm.html

[A15] 空值判断与默认值
来源：http://dali.xuanzx.com/Article/details/gt2htxtqpny.html

Py:   value = data or "默认值"
来源：http://dali.xuetiantiany.cn/Article/details/gt2qzotkgas.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jinqigfzy.top/Article/details/gt2deawxiee.html

JS:   const value = data ?? "默认值";
来源：http://dali.hnxiangtu.top/Article/details/gt2blxcrirc.html

TS:   const value = data ?? "默认值";
来源：http://dali.daxiang520.top/Article/details/gt2uovfsewh.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.xylfe.cn/Article/details/gt2apkozrjo.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.vqdsnc.cn/Article/details/gt2pjrfpogv.html

Ruby: value = data || "默认值"
来源：http://dali.gzhubu.top/Article/details/gt2lnxperxy.html

C#:   var value = data ?? "默认值";
来源：http://dali.chenjidiqi.icu/Article/details/gt2vebabxyo.html

[A16] 真假值判断规则
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gvofiube.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.tian-w.cn/Article/details/gt2hckcoqbz.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.haohaochexian.top/Article/details/gt2yghfciud.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.guannengcc.top/Article/details/gt2vqtvkobe.html

TS:   if (!x) {}
来源：http://dali.c1oappe.top/Article/details/gt2pknkypfm.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yj20258.top/Article/details/gt2amdkmgrw.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.cashguo.top/Article/details/gt2zalcsfyy.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.fengsongda.top/Article/details/gt2tfyxthwo.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.guannengcc.top/Article/details/gt2ubulytmo.html

[A17] 位运算
来源：http://dali.gogol.net.cn/Article/details/gt2izyahapu.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guowangkeji.top/Article/details/gt2vqjjgyrz.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.andypj.xyz/Article/details/gt2yzxjnlqo.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gt2mgfjvlhe.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.gogol.net.cn/Article/details/gt2noptzucb.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.andypj.xyz/Article/details/gt2oyjaomkt.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhengqikj.top/Article/details/gt2qolvdiij.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gt2okwxokph.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258888.top/Article/details/gt2zmkjoqgz.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hfpthk.cn/Article/details/gt2almksbcg.html

Py:   ord("A"); chr(65)
来源：http://dali.jyoumei.cn/Article/details/gt2xivyayyc.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhixingplan.top/Article/details/gt2btkcqrgc.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhongyouzk.top/Article/details/gt2ocvlprxv.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ehokhopl.html

Java: (int) 'A'; (char) 65
来源：http://dali.pengpengdd.cyou/Article/details/gt2ythyjktb.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.316326.xyz/Article/details/gt2jpsohzkh.html

Ruby: "A".ord; 65.chr
来源：http://dali.yvedp.cn/Article/details/gt2jikiulce.html


<!-- 参考信息 -->