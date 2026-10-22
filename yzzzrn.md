代发 wailian999

[U99] JS：事件监听
来源：http://dali.bjfxy.top/Article/details/gt2hokwebyn.html

el.addEventListener("click", e => {})
来源：http://dali.feifeiyinyue.top/Article/details/gt2khmotimh.html

[U100] JS：DOM 查询
来源：http://dali.guowangkeji.top/Article/details/gt2mkucxlzm.html

document.querySelector(".item")
来源：http://dali.tanke756.top/Article/details/gt2fltnrpib.html

[U101] JS：classList 操作
来源：http://dali.fengsongda.top/Article/details/gt2blbicfjs.html

el.classList.toggle("active")
来源：http://dali.yj20258888.top/Article/details/gt2ilxnjbto.html

[U102] JS：本地存储
来源：http://dali.smart0.xyz/Article/details/gt2fusbumgc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shuidangran.top/Article/details/gt2firmwlzq.html

[U103] JS：定时器
来源：http://dali.aizwys.cn/Article/details/gt2ocljarfl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xylfe.cn/Article/details/gt2yajvehkq.html

[U104] JS：防抖
来源：http://dali.hfpthk.cn/Article/details/gt2vjvlmglx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gt2ppabwbdm.html

[U105] JS：节流
来源：http://dali.shzxlz.cn/Article/details/gt2suosbggo.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.316326.xyz/Article/details/gt2swglttpe.html

[U106] JS：日期格式化
来源：http://dali.nanxinkj.top/Article/details/gt2aaedkwfo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.haohaochexian.top/Article/details/gt2zqmeteuh.html

[U107] JS：数字千分位
来源：http://dali.ivvv.top/Article/details/gt2dzuxyegi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gt2drtfjfze.html

[U108] JS：随机整数
来源：http://dali.jiagoushi.top/Article/details/gt2quuaqmaz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhengqikj.top/Article/details/gt2ndopzqxe.html

[U109] JS：数组分组
来源：http://dali.jinqigfzy.top/Article/details/gt2xslcxxrm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cashguo.top/Article/details/gt2pdhmegig.html

[U110] JS：数组分块
来源：http://dali.vqdsnc.cn/Article/details/gt2cswestuc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.feifeiyinyue.top/Article/details/gt2ohvskxmh.html

[U111] JS：对象转 Map
来源：http://dali.fengsongda.top/Article/details/gt2tlmznjcg.html

new Map(Object.entries(obj))
来源：http://dali.gogol.net.cn/Article/details/gt2isboqlvf.html

[U112] JS：字符串补位
来源：http://dali.chenzaomai.com/Article/details/gt2ihutpwmj.html

"7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gt2sujmolla.html

[U113] JS：正则替换全部
来源：http://dali.ydzc1.top/Article/details/gt2rwvexxzp.html

s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2ilfizkql.html

[U114] JS：JSON 深比较
来源：http://dali.hysaishi.cn/Article/details/gt2bwhoeosn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fengsongda.top/Article/details/gt2nihjvaax.html

[U115] JS：生成 UUID
来源：http://dali.9152youxi.cn/Article/details/gt2turxovnp.html

crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gt2rrfjstec.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.sxryk.cn/Article/details/gt2hiytjjsy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2gqrlwewr.html

[U117] JS：单元测试
来源：http://dali.ehwqpu.com/Article/details/gt2awfnhpik.html

npm i -D vitest;  npx vitest
来源：http://dali.cqqwz.cn/Article/details/gt2ylphjepb.html

[U118] JS：开发服务器
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oshzaazm.html

npm i -D vite;  npx vite
来源：http://dali.hywenlv.cn/Article/details/gt2vlhervnc.html

[U119] JS：生产构建
来源：http://dali.feifeiyinyue.top/Article/details/gt2hbkxiimk.html

npx vite build
来源：http://dali.nwbrower.top/Article/details/gt2qsmtiwoa.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.wangshuangyany.cn/Article/details/gt2tumwrozp.html

import.meta.env.VITE_API_URL
来源：http://dali.smart0.xyz/Article/details/gt2gbqyyokn.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2uibrzlrq.html

统计汇总
来源：http://dali.wangdashe.top/Article/details/gt2nqzgvikm.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2tfexpcex.html

按语言统计（条）：
来源：http://dali.dashuyun.cn/Article/details/gt2kmbdysqh.html

Python ......... 252
来源：http://dali.9152youxi.cn/Article/details/gt2yyrntkab.html

PHP ............ 252
来源：http://dali.yj202588.top/Article/details/gt2xjkogrun.html

JavaScript ..... 252
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vpyzbhft.html

TypeScript ..... 212
来源：http://dali.gzhubu.top/Article/details/gt2yiwrelcf.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzcuaxt.html

Go ............. 212
来源：http://dali.xuanzx.com/Article/details/gt2lrsjeebq.html

Ruby ........... 212
来源：http://dali.hysaishi.cn/Article/details/gt2jisjaavu.html

C# ............. 212
来源：http://dali.guowangkeji.top/Article/details/gt2segwfvxj.html

C .............. 30
来源：http://dali.yueranfly.top/Article/details/gt2sidarlke.html

C++ ............ 30
来源：http://dali.gaohongyu789.top/Article/details/gt2cuibjioj.html

SQL ............ 90
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2exixymyp.html

Bash ........... 80
来源：http://dali.yuanzhike.top/Article/details/gt2egivqjeb.html

Kotlin ......... 15
来源：http://dali.kuanghao11.cn/Article/details/gt2hlldvqun.html

Swift .......... 15
来源：http://dali.meibo888.top/Article/details/gt2atczjacq.html

Lua ............ 10
来源：http://dali.jlsjyb.cn/Article/details/gt2tcuvhkga.html

Perl ........... 10
来源：http://dali.nanxuanxn.top/Article/details/gt2mevcrvcz.html

Scala .......... 10
来源：http://dali.wangdashe.top/Article/details/gt2blucllrm.html

------------------------------------
来源：http://dali.gaohongyu789.top/Article/details/gt2omjkxpeb.html

合计 ........... 2106 条
来源：http://dali.xuetiantiany.cn/Article/details/gt2oahrdvfp.html

按章节统计：
来源：http://dali.316326.xyz/Article/details/gt2ppnglsnf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gogol.net.cn/Article/details/gt2tkupwfqj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.haohaochexian.top/Article/details/gt2keupbzpf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.0kj1m.cn/Article/details/gt2koponuum.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.havefunace.top/Article/details/gt2ntrnqfoe.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cashguo.top/Article/details/gt2bzptbukm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.sufxvd.cn/Article/details/gt2skzqqxei.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.bjfxy.top/Article/details/gt2vtbzvhuh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xziqi.cn/Article/details/gt2nterkmaz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zdqjudy.top/Article/details/gt2fliflkti.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jianghu66.top/Article/details/gt2yguduweg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gt2nzkeppze.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gt2tlxifjoi.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gt2wymfyovx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yuxming.cn/Article/details/gt2nzuxaawi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yuanzhike.top/Article/details/gt2qcbqjrnq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jiagoushi.top/Article/details/gt2xrqefbgi.html

Q SQL 专题                              90
来源：http://dali.xuetiantiany.cn/Article/details/gt2femfxlbm.html

R Bash 专题                             80
来源：http://dali.sysykeji.top/Article/details/gt2awurxfnz.html

S C / C++ 专题                          60
来源：http://dali.0kj1m.cn/Article/details/gt2ngrumqkj.html

T 其他语言补充                          60
来源：http://dali.kuanghao11.cn/Article/details/gt2kqwcayba.html

U 高频实用片段                         120
来源：http://dali.hongshengwenyu.top/Article/details/gt2keaxylvy.html

------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2poohpcey.html

合计                                  2106 条
来源：http://dali.yvedp.cn/Article/details/gt2ddrpgtsl.html

--------------------------------------------------------------------------------
来源：http://dali.bjfxy.top/Article/details/gt2lcsbrobf.html

使用提醒
来源：http://dali.zhixingplan.top/Article/details/gt2uchbjknd.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gt2svidqmyv.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.wangdashe.top/Article/details/gt2xjygnllu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.gaohongyu789.top/Article/details/gt2xfqbtgkq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hongshengwenyu.top/Article/details/gt2zjnoyhcq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.9152youxi.cn/Article/details/gt2ljapsjnd.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.guannengcc.top/Article/details/gt2releipli.html

—— 文件结束 ——
来源：http://dali.mhx1999.top/Article/details/gt2elcwyzfh.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2rvsxiiwj.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hysaishi.cn/Article/details/gt2ebhgwrra.html

Common Programming Examples Cheat Book
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wccveumd.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2wjapvwwo.html

【收录内容】
来源：http://dali.jinqigufen.top/Article/details/gt2prnkoeyz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.svipenyu.cn/Article/details/gt2lklfgjbz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.fengsongda.top/Article/details/gt2eagzopaf.html

SQL · Bash · C · C++
来源：http://dali.haohaochexian.top/Article/details/gt2jdohkkfy.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.cashguo.top/Article/details/gt2swydawlr.html

【使用说明】
来源：http://dali.zhengqikj.top/Article/details/gt2vxradgid.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.wangdashe.top/Article/details/gt2crwxwzqe.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.nanxuanxn.top/Article/details/gt2fxbhzpva.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.chenlongwang.top/Article/details/gt2yautnqgg.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.pycfn.com/Article/details/gt2fxtcewnn.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tvpepcrq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhongyouzk.top/Article/details/gt2tjwrsftm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.sweek.top/Article/details/gt2sznhffmz.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jiagoushi.top/Article/details/gt2siscutco.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yj202588.top/Article/details/gt2gdofcgrr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.wangdashe.top/Article/details/gt2nwtrblao.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.sxryk.cn/Article/details/gt2avcdywus.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.gzhubu.top/Article/details/gt2cjidhvdk.html

【文件统计】
来源：http://dali.zhongyouzk.top/Article/details/gt2garloytx.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.chenjidiqi.icu/Article/details/gt2zucnjjxm.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gt2pxoxwuug.html

目  录
来源：http://dali.aizwys.cn/Article/details/gt2fjiuozym.html

--------------------------------------------------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gt2snouisee.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zdqjudy.top/Article/details/gt2fklndotn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jqgfzy.top/Article/details/gt2smahvycv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.svipenyu.cn/Article/details/gt2eygamcpp.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzmkpld.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.iojbl.cn/Article/details/gt2ugmraeoe.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xfrnpxdk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2arxxiaeq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ppjwa.cn/Article/details/gt2vtmcqqyt.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yvedp.cn/Article/details/gt2uluqgmqf.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ivvv.top/Article/details/gt2auyotfxw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.nwbrower.top/Article/details/gt2yizuqmgj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gzdhcnor.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2aywynhln.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jqgfzy.top/Article/details/gt2xkljlplq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2dibvmxnh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hysaishi.cn/Article/details/gt2xilrajss.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.havefunace.top/Article/details/gt2dgevjwbl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jiagoushi.top/Article/details/gt2zqpqmmjo.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.c1oappe.top/Article/details/gt2ywbqsxnm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daxiang520.top/Article/details/gt2spwqcozh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenzaomai.com/Article/details/gt2ryeewpao.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2kodkhtul.html

A. 基础语法与类型
来源：http://dali.chenzaomai.com/Article/details/gt2gjpzbsmp.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2baosbgbo.html

[A01] Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2slioqpxw.html

Py:   print("Hello, World!")
来源：http://dali.ydzc1.top/Article/details/gt2gyebxbsk.html

PHP:  echo "Hello, World!";
来源：http://dali.xylfe.cn/Article/details/gt2vtfnelfa.html

JS:   console.log("Hello, World!");
来源：http://dali.zhiwuduotai.top/Article/details/gt2uivnlusi.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ehwqpu.com/Article/details/gt2xvfoocxn.html

Java: System.out.println("Hello, World!");
来源：http://dali.chenlongwang.top/Article/details/gt2psssysgb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xuetiantiany.cn/Article/details/gt2chkpeijj.html

Ruby: puts "Hello, World!"
来源：http://dali.yuanzhike.top/Article/details/gt2ucodlazw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jlsjyb.cn/Article/details/gt2wkmvujtu.html

[A02] 变量声明与赋值
来源：http://dali.zdqjudy.top/Article/details/gt2fqhebmmg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.chenzaomai.com/Article/details/gt2nredyhoi.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.vqdsnc.cn/Article/details/gt2fisgxrzj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.0kj1m.cn/Article/details/gt2gtvknvka.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yj20258.top/Article/details/gt2opduckqp.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.fengsongda.top/Article/details/gt2irbimesk.html

Go:   name := "Alex"; age := 20
来源：http://dali.yuxming.cn/Article/details/gt2zyonkzoe.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jqgufenzy.top/Article/details/gt2skquyxfo.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hnxiangtu.top/Article/details/gt2jwlwtece.html

[A03] 常量定义
来源：http://dali.cucudq.cn/Article/details/gt2kzxqptzh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.fzhhl.top/Article/details/gt2jnoemihw.html

PHP:  const PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gt2skbxhjqd.html

JS:   const PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gt2qvxqnryg.html

TS:   const PI: number = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gt2qqoezzfk.html

Java: static final double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gt2bfrenhcq.html

Go:   const PI = 3.14159
来源：http://dali.sweek.top/Article/details/gt2yclohfbv.html

Ruby: PI = 3.14159
来源：http://dali.hammf.cn/Article/details/gt2mfhtpvht.html

C#:   const double PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gt2qujhgotk.html

[A04] 判断变量类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2febozrpq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yueranfly.top/Article/details/gt2flkezovb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qtptudtd.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jianghu66.top/Article/details/gt2erzgahvs.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhoulong.xyz/Article/details/gt2cfnalpgj.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jqgfzy.top/Article/details/gt2cfggwhhg.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yuxming.cn/Article/details/gt2jusqphgy.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yvedp.cn/Article/details/gt2cjbqucwb.html

C#:   x.GetType().Name; x is int
来源：http://dali.yueranfly.top/Article/details/gt2wbyotndd.html

[A05] 整数除法与取模
来源：http://dali.redwolf501.top/Article/details/gt2wwsxofur.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.fzhhl.top/Article/details/gt2mobvqnww.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yongpay.top/Article/details/gt2zicchwjn.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gt2mamehktg.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gt2jmotbgul.html

Java: 7 / 2; 7 % 2
来源：http://dali.ydzc1.top/Article/details/gt2yhyuqrsv.html

Go:   7 / 2; 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gt2jicxzlsg.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.andypj.xyz/Article/details/gt2fktjjcjw.html

C#:   7 / 2; 7 % 2
来源：http://dali.c1oappe.top/Article/details/gt2xfnhjpgv.html

[A06] 字符串转数字
来源：http://dali.wangshuangyany.cn/Article/details/gt2zbfqphgb.html

Py:   int("42"); float("3.14")
来源：http://dali.cashguo.top/Article/details/gt2unzjlvph.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.fzhhl.top/Article/details/gt2ztgrnokn.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.dianchejie.cn/Article/details/gt2ihxpswgv.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.snrcjt.cn/Article/details/gt2fcwnsfng.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.quarkkingdee.top/Article/details/gt2oyypugdm.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.pengpengdd.cyou/Article/details/gt2aapgthms.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yueranfly.top/Article/details/gt2yntwgdkp.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yangfankeji.com/Article/details/gt2jumccxio.html

[A07] 数字转字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2waefywmf.html

Py:   str(42)
来源：http://dali.yvedp.cn/Article/details/gt2ecqfmfnv.html

PHP:  (string) 42; strval(42)
来源：http://dali.hnxiangtu.top/Article/details/gt2doqszvsh.html

JS:   String(42); (42).toString()
来源：http://dali.yongpay.top/Article/details/gt2nosnihff.html

TS:   String(42)
来源：http://dali.gzhubu.top/Article/details/gt2lqrswhwc.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hsdcqbvc.html

Go:   strconv.Itoa(42)
来源：http://dali.ivvv.top/Article/details/gt2rxxapmsq.html

Ruby: 42.to_s
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2caseruzy.html

C#:   42.ToString()
来源：http://dali.cheryme.top/Article/details/gt2pnasevxc.html

[A08] 取整与四舍五入
来源：http://dali.quarkkingdee.top/Article/details/gt2zhferdyn.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.tian-w.cn/Article/details/gt2zdvncalu.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.nanxinkj.top/Article/details/gt2gdytvkhk.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yj20258.top/Article/details/gt2ssszwzps.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.wangdashe.top/Article/details/gt2yamatbty.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.shzxlz.cn/Article/details/gt2ptjhhpxx.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.sxryk.cn/Article/details/gt2omaifedn.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.hywenlv.cn/Article/details/gt2ajviquls.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.cashguo.top/Article/details/gt2dpfjjcjh.html

[A09] 绝对值与最大最小值
来源：http://dali.yj20258.top/Article/details/gt2xykyrokq.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.aizwys.cn/Article/details/gt2fdjqczum.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ivyrfcqf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gt2ospuvsoe.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.andypj.xyz/Article/details/gt2dzaadynf.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gt2lehyihtc.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hecvlwsj.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.xinyue.icu/Article/details/gt2sivkzjao.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jhhiexrz.html

[A10] 生成随机数
来源：http://dali.zhiwuduotai.top/Article/details/gt2rzisiqsz.html

Py:   import random; random.randint(1, 100)
来源：http://dali.guannengcc.top/Article/details/gt2hutmjfoc.html

PHP:  random_int(1, 100);
来源：http://dali.pycfn.com/Article/details/gt2xuitfhrh.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.gogol.net.cn/Article/details/gt2ctsuzbty.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zycfv.cn/Article/details/gt2mxybicrb.html

Java: new Random().nextInt(100) + 1
来源：http://dali.ppjwa.cn/Article/details/gt2cqpbypcj.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhengqikj.top/Article/details/gt2mqxxhyak.html

Ruby: rand(1..100)
来源：http://dali.chenzaomai.com/Article/details/gt2whsuvkvn.html

C#:   new Random().Next(1, 101)
来源：http://dali.daria6918.cn/Article/details/gt2retcjxhv.html

[A11] 条件表达式（三元）
来源：http://dali.yangfankeji.com/Article/details/gt2kmgybjpx.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.shuidangran.top/Article/details/gt2cntasrpi.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.aizwys.cn/Article/details/gt2zjpiqhgj.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.hnxiangtu.top/Article/details/gt2azinukvi.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.hysaishi.cn/Article/details/gt2saxjuefo.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.snrcjt.cn/Article/details/gt2lhsmtbzz.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yj20258888.top/Article/details/gt2piglyxyc.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yueranfly.top/Article/details/gt2okrgyeaa.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yvedp.cn/Article/details/gt2clchhdqj.html

[A12] 字符串插值 / 格式化
来源：http://dali.yueranfly.top/Article/details/gt2iwuzcvno.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.hnxiangtu.top/Article/details/gt2hizjwhle.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yonumen.top/Article/details/gt2ifpsdrob.html

JS:   `Hello, ${name}!`
来源：http://dali.nwbrower.top/Article/details/gt2llmhcepc.html

TS:   `Hello, ${name}!`
来源：http://dali.daxiang520.top/Article/details/gt2zyejdlsv.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.tanke756.top/Article/details/gt2wsgfeqbs.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.aibaodan.cn/Article/details/gt2hblyuxmi.html

Ruby: "Hello, #{name}!"
来源：http://dali.yuxming.cn/Article/details/gt2htrrstkk.html

C#:   $"Hello, {name}!"
来源：http://dali.hywenlv.cn/Article/details/gt2koejrgqj.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.cheryme.top/Article/details/gt2djwforpv.html

Py:   "第一行\n第二行"
来源：http://dali.quarkkingdee.top/Article/details/gt2bwtrrjco.html

PHP:  "第一行\n第二行"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nfuwzvyl.html

JS:   "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gt2yscjbpym.html

TS:   "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gt2jhhdvgvk.html

Java: "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gt2nopmqgou.html

Go:   "第一行\n第二行"
来源：http://dali.zhongyouzk.top/Article/details/gt2hxabwapw.html

Ruby: "第一行\n第二行"
来源：http://dali.hywenlv.cn/Article/details/gt2wnpfpufo.html

C#:   "第一行\n第二行"
来源：http://dali.shzxlz.cn/Article/details/gt2oeagpzzs.html

[A14] 注释写法
来源：http://dali.cucudq.cn/Article/details/gt2yrqaoiee.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yangfankeji.com/Article/details/gt2zqmhdgqy.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.tian-w.cn/Article/details/gt2ucwdfjje.html

JS:   // 单行；/* 多行 */
来源：http://dali.yj202588.top/Article/details/gt2tcwasxyf.html

TS:   // 单行；/* 多行 */
来源：http://dali.ppjwa.cn/Article/details/gt2kchvtylk.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.daxiang520.top/Article/details/gt2mswekkwi.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhongyouzk.top/Article/details/gt2qygvrnex.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.0kj1m.cn/Article/details/gt2cuvstwsq.html

C#:   // 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gt2mgsjigka.html

[A15] 空值判断与默认值
来源：http://dali.snrcjt.cn/Article/details/gt2ecmxphhb.html

Py:   value = data or "默认值"
来源：http://dali.zycfv.cn/Article/details/gt2dnxsgany.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.snrcjt.cn/Article/details/gt2acojzlwz.html

JS:   const value = data ?? "默认值";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ilkluogz.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmriziv.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.tanke756.top/Article/details/gt2auclmtqo.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.andypj.xyz/Article/details/gt2edfvvthw.html

Ruby: value = data || "默认值"
来源：http://dali.xziqi.cn/Article/details/gt2eokmmswn.html

C#:   var value = data ?? "默认值";
来源：http://dali.tian-w.cn/Article/details/gt2kbxwqsay.html

[A16] 真假值判断规则
来源：http://dali.tian-w.cn/Article/details/gt2nlhwpurb.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.bjfxy.top/Article/details/gt2hkaxqzuk.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.gzhubu.top/Article/details/gt2arakmkxk.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.wangdashe.top/Article/details/gt2hydejsky.html

TS:   if (!x) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2jximefvh.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2hvwjjoki.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.9152youxi.cn/Article/details/gt2zpitvgva.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.316326.xyz/Article/details/gt2mftupdqa.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.iojbl.cn/Article/details/gt2vgqferit.html

[A17] 位运算
来源：http://dali.nanxuanxn.top/Article/details/gt2kagqyglv.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jianghu66.top/Article/details/gt2jauvwrrg.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.sxryk.cn/Article/details/gt2mdvaquyo.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigfzy.top/Article/details/gt2ihfaljpu.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.shzxlz.cn/Article/details/gt2titumhke.html


<!-- 参考信息 -->