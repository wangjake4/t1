代发 wailian999

[U101] JS：classList 操作
来源：http://dali.daxiang520.top/Article/details/gtrdrwdbto.html

el.classList.toggle("active")
来源：http://dali.0kj1m.cn/Article/details/gtuesnqdaj.html

[U102] JS：本地存储
来源：http://dali.aibaodan.cn/Article/details/gtgzisrwuw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ivvv.top/Article/details/gtsyoyjlky.html

[U103] JS：定时器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlonohdqg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hywenlv.cn/Article/details/gtuquatzgw.html

[U104] JS：防抖
来源：http://dali.xuetiantiany.cn/Article/details/gtwcmbmtmp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cdnleiting.top/Article/details/gtlpxgokof.html

[U105] JS：节流
来源：http://dali.wangdashe.top/Article/details/gtwzaxdvcc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hnqzz.top/Article/details/gtnivgsvgc.html

[U106] JS：日期格式化
来源：http://dali.c1oappe.top/Article/details/gtwdjgqvok.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.chenjidiqi.icu/Article/details/gtslvuxmmz.html

[U107] JS：数字千分位
来源：http://dali.quarkkingdee.top/Article/details/gttdmqzocj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hnqzz.top/Article/details/gtnwtpisfm.html

[U108] JS：随机整数
来源：http://dali.sysykeji.top/Article/details/gtoripcyqc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xinyue.icu/Article/details/gthhrfjspf.html

[U109] JS：数组分组
来源：http://dali.tanke756.top/Article/details/gtxuahyjrn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cucudq.cn/Article/details/gtbtwdegsn.html

[U110] JS：数组分块
来源：http://dali.jianghu66.top/Article/details/gtuduhwusx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.snrcjt.cn/Article/details/gtztqekbdz.html

[U111] JS：对象转 Map
来源：http://dali.fengsongda.top/Article/details/gtvtbfkfyp.html

new Map(Object.entries(obj))
来源：http://dali.cqqwz.cn/Article/details/gtzqbjqiut.html

[U112] JS：字符串补位
来源：http://dali.tianlin.xyz/Article/details/gtnbinblgl.html

"7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtootoqjti.html

[U113] JS：正则替换全部
来源：http://dali.cheryme.top/Article/details/gtxmznccph.html

s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtyyqdxfyq.html

[U114] JS：JSON 深比较
来源：http://dali.daxiang520.top/Article/details/gtxfiglnum.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gtdpdmiusc.html

[U115] JS：生成 UUID
来源：http://dali.yongpay.top/Article/details/gtlxblybsq.html

crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gtqwcfazag.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cashguo.top/Article/details/gtwnonhfts.html

/** @param {string} name */ function f(name) {}
来源：http://dali.meibo888.top/Article/details/gtglsuanuk.html

[U117] JS：单元测试
来源：http://dali.hnqzz.top/Article/details/gtbsqcmgwz.html

npm i -D vitest;  npx vitest
来源：http://dali.aibaodan.cn/Article/details/gtquktditi.html

[U118] JS：开发服务器
来源：http://dali.ivvv.top/Article/details/gteutqilmd.html

npm i -D vite;  npx vite
来源：http://dali.hongshengwenyu.top/Article/details/gtuaylowru.html

[U119] JS：生产构建
来源：http://dali.yvedp.cn/Article/details/gtiyhvjyvd.html

npx vite build
来源：http://dali.gotoacloud.top/Article/details/gtehnyhjzc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hywenlv.cn/Article/details/gtdjwknpsu.html

import.meta.env.VITE_API_URL
来源：http://dali.wangshuangyany.cn/Article/details/gtfdvriibu.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtqgmopulk.html

统计汇总
来源：http://dali.gaohongyu789.top/Article/details/gthakxcqrz.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtgclardmn.html

按语言统计（条）：
来源：http://dali.guowangkeji.top/Article/details/gtshfekegg.html

Python ......... 252
来源：http://dali.zdqjudy.top/Article/details/gtwibkvhwn.html

PHP ............ 252
来源：http://dali.nanxinkj.top/Article/details/gtkryonqvn.html

JavaScript ..... 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdmabktf.html

TypeScript ..... 212
来源：http://dali.yj20258888.top/Article/details/gthrjnsgdw.html

Java ........... 212
来源：http://dali.meibo888.top/Article/details/gteqkmumnf.html

Go ............. 212
来源：http://dali.jlsjyb.cn/Article/details/gtbzlkilpg.html

Ruby ........... 212
来源：http://dali.yangfankeji.com/Article/details/gtigapgffy.html

C# ............. 212
来源：http://dali.gzhubu.top/Article/details/gtfeoibmep.html

C .............. 30
来源：http://dali.sysykeji.top/Article/details/gtkcojuioq.html

C++ ............ 30
来源：http://dali.shuidangran.top/Article/details/gtbipvqbdf.html

SQL ............ 90
来源：http://dali.xuanzx.com/Article/details/gtwpajpuae.html

Bash ........... 80
来源：http://dali.shzxlz.cn/Article/details/gtdmhjewmk.html

Kotlin ......... 15
来源：http://dali.tian-w.cn/Article/details/gtnaoqzphq.html

Swift .......... 15
来源：http://dali.cashguo.top/Article/details/gtiqjludbg.html

Lua ............ 10
来源：http://dali.hysaishi.cn/Article/details/gtcayubbmo.html

Perl ........... 10
来源：http://dali.mhx1999.top/Article/details/gtgiajwsxl.html

Scala .......... 10
来源：http://dali.yuanzhike.top/Article/details/gtsxymutyr.html

------------------------------------
来源：http://dali.xuanzx.com/Article/details/gtvuqzkwao.html

合计 ........... 2106 条
来源：http://dali.yanxiufei.cn/Article/details/gtnjdakzcb.html

按章节统计：
来源：http://dali.hongshengwenyu.top/Article/details/gtshiaoeja.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shzxlz.cn/Article/details/gtufwbszgb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwktcrymh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.wangdashe.top/Article/details/gtrelpbhjg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.pengpengdd.cyou/Article/details/gtpcvbegxa.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.quarkkingdee.top/Article/details/gtrikucpew.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yuxming.cn/Article/details/gtyxjxmunv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwaebwhrj.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.quarkkingdee.top/Article/details/gtzdndkpve.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sweek.top/Article/details/gtzyqdpgaq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.daria6918.cn/Article/details/gtmhdubimy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gtngrjtbmx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.dianchejie.cn/Article/details/gtecunizoz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gtfdwbuqvm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhixingplan.top/Article/details/gtdknjzumh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jyoumei.cn/Article/details/gtltpbmfoo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gtnohqwzsl.html

Q SQL 专题                              90
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflpzxxjd.html

R Bash 专题                             80
来源：http://dali.aibaodan.cn/Article/details/gtzbnuuexh.html

S C / C++ 专题                          60
来源：http://dali.fzhhl.top/Article/details/gtpskynzjf.html

T 其他语言补充                          60
来源：http://dali.vqdsnc.cn/Article/details/gtzlvmkszy.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gtznyztqab.html

------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gtabzsttsm.html

合计                                  2106 条
来源：http://dali.sweek.top/Article/details/gticrufxzd.html

--------------------------------------------------------------------------------
来源：http://dali.quarkkingdee.top/Article/details/gtrypctsxc.html

使用提醒
来源：http://dali.guannengcc.top/Article/details/gtwgxjhgvf.html

--------------------------------------------------------------------------------
来源：http://dali.daria6918.cn/Article/details/gtntnjiofg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.fzhhl.top/Article/details/gtbdgptfxi.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jqgufenzy.top/Article/details/gtiddremjc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.wangshuangyany.cn/Article/details/gtkmumgaji.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.gotoacloud.top/Article/details/gtckolomtf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.0kj1m.cn/Article/details/gtgexhrbwe.html

—— 文件结束 ——
来源：http://dali.nanxinkj.top/Article/details/gttpsnlyhg.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtwpretwnu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yuanzhike.top/Article/details/gtcvweivbz.html

Common Programming Examples Cheat Book
来源：http://dali.tian-w.cn/Article/details/gtlvwxpufd.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtpxnttsvf.html

【收录内容】
来源：http://dali.tanke756.top/Article/details/gtsgoeikhg.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrindgkh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.ehwqpu.com/Article/details/gtiusurclq.html

SQL · Bash · C · C++
来源：http://dali.jqgfzy.top/Article/details/gtkytxspbt.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.meibo888.top/Article/details/gtawvjvwly.html

【使用说明】
来源：http://dali.xuetiantiany.cn/Article/details/gtlitbtqxa.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzqecoab.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yj20258888.top/Article/details/gtfbavnykq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ivvv.top/Article/details/gtjirkevwc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.cheryme.top/Article/details/gtjrnfosbi.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdbajmru.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.daxiang520.top/Article/details/gtjlpgistg.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.ppjwa.cn/Article/details/gtzywjmgps.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.andypj.xyz/Article/details/gtyolwhmkb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.guowangkeji.top/Article/details/gtlklakdpm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shuidangran.top/Article/details/gtzlfvfius.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhengqikj.top/Article/details/gtmaywmqvx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.tian-w.cn/Article/details/gtjguvruxd.html

【文件统计】
来源：http://dali.smart0.xyz/Article/details/gtjgnlsjpm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.dianchejie.cn/Article/details/gtcwugurde.html

--------------------------------------------------------------------------------
来源：http://dali.yonumen.top/Article/details/gtaegxbfyz.html

目  录
来源：http://dali.jinghuilouyu.cn/Article/details/gtegpfafon.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gtqajsdmdb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.havefunace.top/Article/details/gtrmaguhtv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.sxryk.cn/Article/details/gtiiyqjeky.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.sweek.top/Article/details/gttjqczzij.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.cashguo.top/Article/details/gtguyoxmoh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtajphvuqo.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yanxiufei.cn/Article/details/gtbgmhptsa.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.svipenyu.cn/Article/details/gtyycljaum.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.0kj1m.cn/Article/details/gtxixjkkzu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gtqhohuqju.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yonumen.top/Article/details/gtmrberomj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtnkvzuqat.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gtxdkrnbkc.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cashguo.top/Article/details/gtkalatfhk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zycfv.cn/Article/details/gthrapkpur.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yanxiufei.cn/Article/details/gtczrvnsqd.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gtszkrqcdp.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xziqi.cn/Article/details/gtdgbimhle.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.c1oappe.top/Article/details/gtmglmgfwz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.nanxinkj.top/Article/details/gtdmetbgcs.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zycfv.cn/Article/details/gtwoikqyan.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.smart0.xyz/Article/details/gtzkzkizrx.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gthhrdwzeu.html

A. 基础语法与类型
来源：http://dali.havefunace.top/Article/details/gtxditnuje.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtsuerfkkt.html

[A01] Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtzqyebpso.html

Py:   print("Hello, World!")
来源：http://dali.yonumen.top/Article/details/gtkmtqkecn.html

PHP:  echo "Hello, World!";
来源：http://dali.zdqjudy.top/Article/details/gtpxyosbnn.html

JS:   console.log("Hello, World!");
来源：http://dali.pengpengdd.cyou/Article/details/gtvatsxbal.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.mhx1999.top/Article/details/gtjiqymxqz.html

Java: System.out.println("Hello, World!");
来源：http://dali.aizwys.cn/Article/details/gtntlcxdiu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xuanzx.com/Article/details/gtvhhzgmhe.html

Ruby: puts "Hello, World!"
来源：http://dali.dianchejie.cn/Article/details/gtnbkgwtfm.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.gaohongyu789.top/Article/details/gtmozhrrkz.html

[A02] 变量声明与赋值
来源：http://dali.hongshengwenyu.top/Article/details/gtcycwcdcg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jinghuilouyu.cn/Article/details/gtykmherqz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gtgxeoqfdb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.gotoacloud.top/Article/details/gtwcjnxxpo.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.pycfn.com/Article/details/gtcltlrkkn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.cdnleiting.top/Article/details/gtsixspqin.html

Go:   name := "Alex"; age := 20
来源：http://dali.jianghu66.top/Article/details/gtwriwjjxu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hnqzz.top/Article/details/gtauilwwym.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hysaishi.cn/Article/details/gtpnopmuqa.html

[A03] 常量定义
来源：http://dali.ivvv.top/Article/details/gtlxhmfbvw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.gzhubu.top/Article/details/gtvwrzpgzo.html

PHP:  const PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtunandekw.html

JS:   const PI = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtpghkdfnn.html

TS:   const PI: number = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtdkkcewqn.html

Java: static final double PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtmwulgrjg.html

Go:   const PI = 3.14159
来源：http://dali.zhiwuduotai.top/Article/details/gtfcqunxpp.html

Ruby: PI = 3.14159
来源：http://dali.dianchejie.cn/Article/details/gtcfuzcolg.html

C#:   const double PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gttncvmbqs.html

[A04] 判断变量类型
来源：http://dali.jyoumei.cn/Article/details/gtswbdtszr.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.9152youxi.cn/Article/details/gtgyalhmry.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.aizwys.cn/Article/details/gtpiozpgzo.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.redwolf501.top/Article/details/gtqbckavyo.html

TS:   typeof x; x instanceof Date
来源：http://dali.jqgfzy.top/Article/details/gtqeebzsmf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zdqjudy.top/Article/details/gtqkvstjsw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.quarkkingdee.top/Article/details/gtmuqtdcms.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.fzhhl.top/Article/details/gttoqkjxgp.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhixingplan.top/Article/details/gtjxnltckd.html

[A05] 整数除法与取模
来源：http://dali.hysaishi.cn/Article/details/gtacmgzxnk.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.wangshuangyany.cn/Article/details/gtspijbift.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwmknddv.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.birdmap.top/Article/details/gtozvguqlf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gtecjttcpd.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gtogarhttn.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gteeacsugh.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtwowyuver.html

C#:   7 / 2; 7 % 2
来源：http://dali.meibo888.top/Article/details/gtvwroespo.html

[A06] 字符串转数字
来源：http://dali.haohaochexian.top/Article/details/gtjlufwseh.html

Py:   int("42"); float("3.14")
来源：http://dali.feifeiyinyue.top/Article/details/gtzuhyajkd.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jlsjyb.cn/Article/details/gtpcazgoxk.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jlsjyb.cn/Article/details/gtyddsgybd.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhoulong.xyz/Article/details/gtemszketm.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.gaohongyu789.top/Article/details/gtxerxzhtb.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwulgjkwm.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yj20258.top/Article/details/gtjqhyqdzl.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtromunuev.html

[A07] 数字转字符串
来源：http://dali.bjfxy.top/Article/details/gtxqlivxqu.html

Py:   str(42)
来源：http://dali.shanyushiyangtech.top/Article/details/gthpiovtps.html

PHP:  (string) 42; strval(42)
来源：http://dali.hywenlv.cn/Article/details/gtwtdrrumi.html

JS:   String(42); (42).toString()
来源：http://dali.yuanzhike.top/Article/details/gtioozcsen.html

TS:   String(42)
来源：http://dali.yanxiufei.cn/Article/details/gtlwhrcabe.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zdqjudy.top/Article/details/gtosvadpaz.html

Go:   strconv.Itoa(42)
来源：http://dali.guannengcc.top/Article/details/gtbgdrgqpc.html

Ruby: 42.to_s
来源：http://dali.yonumen.top/Article/details/gtbvabyrsm.html

C#:   42.ToString()
来源：http://dali.chenjidiqi.icu/Article/details/gtrdxziuwg.html

[A08] 取整与四舍五入
来源：http://dali.hammf.cn/Article/details/gtrlosijkr.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hysaishi.cn/Article/details/gtvhuephdx.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ivvv.top/Article/details/gthjudjeak.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yanxiufei.cn/Article/details/gtoqavnrxf.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.pengpengdd.cyou/Article/details/gtpzbgjvru.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gtnvtfsqqt.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zycfv.cn/Article/details/gtrnlpydmp.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.gaohongyu789.top/Article/details/gtcoyevjiq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gtyaupojhm.html

[A09] 绝对值与最大最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepsaraap.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtxqeflfkv.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.316326.xyz/Article/details/gtacxlvrvv.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gthxxzjjue.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gtuiabzsgk.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.meibo888.top/Article/details/gtjrvpheiy.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.sxryk.cn/Article/details/gtqynkueat.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhoulong.xyz/Article/details/gtxdxnxrel.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yj20258888.top/Article/details/gtepkistrh.html

[A10] 生成随机数
来源：http://dali.aibaodan.cn/Article/details/gtmroepifu.html

Py:   import random; random.randint(1, 100)
来源：http://dali.chenzaomai.com/Article/details/gtyapfhywq.html

PHP:  random_int(1, 100);
来源：http://dali.xuetiantiany.cn/Article/details/gthyjebejm.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.fzhhl.top/Article/details/gtivlhsvmj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.aizwys.cn/Article/details/gtjfllwsxp.html

Java: new Random().nextInt(100) + 1
来源：http://dali.cucudq.cn/Article/details/gtjyeeonmr.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.haohaochexian.top/Article/details/gtoirfqlbj.html

Ruby: rand(1..100)
来源：http://dali.yuanzhike.top/Article/details/gtnlphqczx.html

C#:   new Random().Next(1, 101)
来源：http://dali.fengsongda.top/Article/details/gtetinwbvq.html

[A11] 条件表达式（三元）
来源：http://dali.shuidangran.top/Article/details/gtpbezdxwl.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.kuanghao11.cn/Article/details/gttuuhvway.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.jqgufenzy.top/Article/details/gtlbjgxvbr.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yueranfly.top/Article/details/gtvimjjnyl.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiflxhkns.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.nanxinkj.top/Article/details/gtiatzxmos.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmaociior.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yvedp.cn/Article/details/gtpmprtrvm.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yuanzhike.top/Article/details/gtsjymhlfz.html

[A12] 字符串插值 / 格式化
来源：http://dali.aizwys.cn/Article/details/gtijdtgcvq.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yongpay.top/Article/details/gtgeyqtjgv.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.cqqwz.cn/Article/details/gtcdpgzixn.html

JS:   `Hello, ${name}!`
来源：http://dali.yuanzhike.top/Article/details/gtkzcdxqib.html

TS:   `Hello, ${name}!`
来源：http://dali.jlsjyb.cn/Article/details/gtqacfngam.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhengqikj.top/Article/details/gtnpexaprs.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.gotoacloud.top/Article/details/gtrtgtqvqv.html

Ruby: "Hello, #{name}!"
来源：http://dali.sweek.top/Article/details/gthozodrgr.html

C#:   $"Hello, {name}!"
来源：http://dali.cashguo.top/Article/details/gtderxtdkb.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.andypj.xyz/Article/details/gtupuugchd.html

Py:   "第一行\n第二行"
来源：http://dali.dashuyun.cn/Article/details/gtjkzlrsbz.html

PHP:  "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gtrrehvata.html

JS:   "第一行\n第二行"
来源：http://dali.yuanzhike.top/Article/details/gtvupyoxib.html

TS:   "第一行\n第二行"
来源：http://dali.iojbl.cn/Article/details/gtnqosowxo.html

Java: "第一行\n第二行"
来源：http://dali.pengpengdd.cyou/Article/details/gtponxfbfh.html

Go:   "第一行\n第二行"
来源：http://dali.chenlongwang.top/Article/details/gtrvfvrwzs.html

Ruby: "第一行\n第二行"
来源：http://dali.shzxlz.cn/Article/details/gtdebryxlu.html

C#:   "第一行\n第二行"
来源：http://dali.xinyue.icu/Article/details/gtywvqmrof.html

[A14] 注释写法
来源：http://dali.aibaodan.cn/Article/details/gtgdsziuzk.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jinqigufen.top/Article/details/gtrmzlqskd.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.guowangkeji.top/Article/details/gtphwwaksf.html

JS:   // 单行；/* 多行 */
来源：http://dali.vqdsnc.cn/Article/details/gtwsbzjnvc.html

TS:   // 单行；/* 多行 */
来源：http://dali.gaohongyu789.top/Article/details/gtsylpyjwl.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.dianchejie.cn/Article/details/gtubkalpuv.html

Go:   // 单行；/* 多行 */
来源：http://dali.jyoumei.cn/Article/details/gtehbbedui.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.bjfxy.top/Article/details/gtnmzdvlqo.html

C#:   // 单行；/* 多行 */
来源：http://dali.yuanzhike.top/Article/details/gthbppcgjk.html

[A15] 空值判断与默认值
来源：http://dali.andypj.xyz/Article/details/gtcosamcug.html

Py:   value = data or "默认值"
来源：http://dali.hywenlv.cn/Article/details/gtahceydjg.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jinqigufen.top/Article/details/gtsnvyscfr.html

JS:   const value = data ?? "默认值";
来源：http://dali.pycfn.com/Article/details/gtgfejnaux.html

TS:   const value = data ?? "默认值";
来源：http://dali.bjfxy.top/Article/details/gttxtjmusy.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.cashguo.top/Article/details/gtrefxgyym.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yanxiufei.cn/Article/details/gtsxlokvsd.html

Ruby: value = data || "默认值"
来源：http://dali.tanke756.top/Article/details/gtgjwvoddq.html

C#:   var value = data ?? "默认值";
来源：http://dali.meibo888.top/Article/details/gtonsuiehf.html

[A16] 真假值判断规则
来源：http://dali.zhixingplan.top/Article/details/gtutsneewz.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yonumen.top/Article/details/gtezjgidxo.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.shuidangran.top/Article/details/gtlheuekry.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.tian-w.cn/Article/details/gtnihahctj.html

TS:   if (!x) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtmgujuiob.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.andypj.xyz/Article/details/gtaixbrbfh.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmjribxp.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yvedp.cn/Article/details/gtzxfnuucw.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.quarkkingdee.top/Article/details/gtjojvbjoj.html

[A17] 位运算
来源：http://dali.vqdsnc.cn/Article/details/gtobclhixn.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shzxlz.cn/Article/details/gtucdohurj.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.meibo888.top/Article/details/gtbgomnkqo.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ydzc1.top/Article/details/gttepkxmui.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gtliswsgte.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gthpkmxcpt.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.nanxinkj.top/Article/details/gtymydjjvc.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jianghu66.top/Article/details/gtxlbwakhl.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangdashe.top/Article/details/gtwhculyfw.html


<!-- 参考信息 -->