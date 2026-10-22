代发 wailian999

[U99] JS：事件监听
来源：http://dali.zhengqikj.top/Article/details/gt2lvxeelfm.html

el.addEventListener("click", e => {})
来源：http://dali.mhx1999.top/Article/details/gt2dibsqzvn.html

[U100] JS：DOM 查询
来源：http://dali.c1oappe.top/Article/details/gt2strblelm.html

document.querySelector(".item")
来源：http://dali.meibo888.top/Article/details/gt2khpzgpgx.html

[U101] JS：classList 操作
来源：http://dali.aibaodan.cn/Article/details/gt2nqpiwwnc.html

el.classList.toggle("active")
来源：http://dali.gogol.net.cn/Article/details/gt2thpohypj.html

[U102] JS：本地存储
来源：http://dali.zycfv.cn/Article/details/gt2yjdvwtwb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.redwolf501.top/Article/details/gt2zxuvyiyj.html

[U103] JS：定时器
来源：http://dali.hammf.cn/Article/details/gt2wixwrbhh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.aizwys.cn/Article/details/gt2otnpewut.html

[U104] JS：防抖
来源：http://dali.yj202588.top/Article/details/gt2krgfhpji.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gt2juitowcy.html

[U105] JS：节流
来源：http://dali.jlsjyb.cn/Article/details/gt2teytgaen.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sysykeji.top/Article/details/gt2ldmqeuzm.html

[U106] JS：日期格式化
来源：http://dali.hfpthk.cn/Article/details/gt2qfazptmr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cdnleiting.top/Article/details/gt2gicrmhsp.html

[U107] JS：数字千分位
来源：http://dali.redwolf501.top/Article/details/gt2solzxhqu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gt2njeflaoq.html

[U108] JS：随机整数
来源：http://dali.haohaochexian.top/Article/details/gt2sorhxrit.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.guannengcc.top/Article/details/gt2asswylgp.html

[U109] JS：数组分组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vdeotuph.html

Object.groupBy(arr, x => x.type)
来源：http://dali.svipenyu.cn/Article/details/gt2xwttcqjv.html

[U110] JS：数组分块
来源：http://dali.svipenyu.cn/Article/details/gt2npqqtzcd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.mhx1999.top/Article/details/gt2odmntrwx.html

[U111] JS：对象转 Map
来源：http://dali.svipenyu.cn/Article/details/gt2rfpvqkwe.html

new Map(Object.entries(obj))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ampjbwqk.html

[U112] JS：字符串补位
来源：http://dali.yongpay.top/Article/details/gt2qzwtyiet.html

"7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2drvujssr.html

[U113] JS：正则替换全部
来源：http://dali.nwbrower.top/Article/details/gt2xaxojcsf.html

s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2wqqutcgf.html

[U114] JS：JSON 深比较
来源：http://dali.jqgfzy.top/Article/details/gt2jmcwweqq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258888.top/Article/details/gt2vqmiwqjk.html

[U115] JS：生成 UUID
来源：http://dali.pycfn.com/Article/details/gt2lgvhetbf.html

crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gt2boqpssbg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hnxiangtu.top/Article/details/gt2tmjyjkxw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhixingplan.top/Article/details/gt2pifkulpo.html

[U117] JS：单元测试
来源：http://dali.yueranfly.top/Article/details/gt2edkvkefu.html

npm i -D vitest;  npx vitest
来源：http://dali.mhx1999.top/Article/details/gt2brbwlnvy.html

[U118] JS：开发服务器
来源：http://dali.tian-w.cn/Article/details/gt2geklfbfu.html

npm i -D vite;  npx vite
来源：http://dali.yuanzhike.top/Article/details/gt2znbpysam.html

[U119] JS：生产构建
来源：http://dali.daxiang520.top/Article/details/gt2entygrbi.html

npx vite build
来源：http://dali.hnqzz.top/Article/details/gt2axfmzhhw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yj20258888.top/Article/details/gt2jcvsnbum.html

import.meta.env.VITE_API_URL
来源：http://dali.hongshengwenyu.top/Article/details/gt2xqsdznov.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2uzdiqwdq.html

统计汇总
来源：http://dali.tian-w.cn/Article/details/gt2saksmmnw.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2omqljwue.html

按语言统计（条）：
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kdyshppe.html

Python ......... 252
来源：http://dali.yongpay.top/Article/details/gt2kcxchktq.html

PHP ............ 252
来源：http://dali.havefunace.top/Article/details/gt2atohzibv.html

JavaScript ..... 252
来源：http://dali.yueranfly.top/Article/details/gt2jpyjyzvm.html

TypeScript ..... 212
来源：http://dali.redwolf501.top/Article/details/gt2scspnyxr.html

Java ........... 212
来源：http://dali.yuxming.cn/Article/details/gt2ybgtmcjf.html

Go ............. 212
来源：http://dali.tianlin.xyz/Article/details/gt2nmrbqwcv.html

Ruby ........... 212
来源：http://dali.xziqi.cn/Article/details/gt2iekryipp.html

C# ............. 212
来源：http://dali.pengpengdd.cyou/Article/details/gt2wutsqwvu.html

C .............. 30
来源：http://dali.ydzc1.top/Article/details/gt2ikqgdsxq.html

C++ ............ 30
来源：http://dali.cdnleiting.top/Article/details/gt2pchaudnr.html

SQL ............ 90
来源：http://dali.guannengcc.top/Article/details/gt2lnqikkdf.html

Bash ........... 80
来源：http://dali.gzhubu.top/Article/details/gt2zscaykzz.html

Kotlin ......... 15
来源：http://dali.shangyingyoupin.top/Article/details/gt2pnvasdrs.html

Swift .......... 15
来源：http://dali.9152youxi.cn/Article/details/gt2qhyoocin.html

Lua ............ 10
来源：http://dali.nanxinkj.top/Article/details/gt2hgusruqg.html

Perl ........... 10
来源：http://dali.yueranfly.top/Article/details/gt2ahmeaijk.html

Scala .......... 10
来源：http://dali.xuanzx.com/Article/details/gt2xmsewyxy.html

------------------------------------
来源：http://dali.havefunace.top/Article/details/gt2pprsriag.html

合计 ........... 2106 条
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yhnjxwce.html

按章节统计：
来源：http://dali.ppjwa.cn/Article/details/gt2kuydsckr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ehwqpu.com/Article/details/gt2gzlzqkft.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.fzhhl.top/Article/details/gt2xrwdvqqb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.quarkkingdee.top/Article/details/gt2llignfyb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yongpay.top/Article/details/gt2mdtqkkht.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yangfankeji.com/Article/details/gt2djblxoxf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shzxlz.cn/Article/details/gt2waigaotc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gt2nopfaeik.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.daxiang520.top/Article/details/gt2rievsrew.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gt2byvkejmm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jiagoushi.top/Article/details/gt2fngkwqkk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gt2djhsvjhm.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gt2efhuijeb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gt2iprfopul.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.tianlin.xyz/Article/details/gt2vttmpuer.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.vqdsnc.cn/Article/details/gt2rnvygiso.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2adtcvbox.html

Q SQL 专题                              90
来源：http://dali.yanxiufei.cn/Article/details/gt2ioprmsgp.html

R Bash 专题                             80
来源：http://dali.nanxinkj.top/Article/details/gt2vxjljtji.html

S C / C++ 专题                          60
来源：http://dali.ivvv.top/Article/details/gt2lhnspanp.html

T 其他语言补充                          60
来源：http://dali.xziqi.cn/Article/details/gt2uxxboeid.html

U 高频实用片段                         120
来源：http://dali.sufxvd.cn/Article/details/gt2gsgeweih.html

------------------------------------
来源：http://dali.fengsongda.top/Article/details/gt2uldmprvy.html

合计                                  2106 条
来源：http://dali.yangfankeji.com/Article/details/gt2jelvvlpf.html

--------------------------------------------------------------------------------
来源：http://dali.cashguo.top/Article/details/gt2zymqqodq.html

使用提醒
来源：http://dali.redwolf501.top/Article/details/gt2nhaewpli.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gt2dsvdzpim.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhoulong.xyz/Article/details/gt2hkfdmagn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jlnnadac.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rtozhxil.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.sxryk.cn/Article/details/gt2kicgnqvs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.nanxuanxn.top/Article/details/gt2rnqmvrtp.html

—— 文件结束 ——
来源：http://dali.yj20258.top/Article/details/gt2wubvsnjq.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2ebpyiuid.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hywenlv.cn/Article/details/gt2dztxqkbq.html

Common Programming Examples Cheat Book
来源：http://dali.zhixingplan.top/Article/details/gt2xeaubvax.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2xnlkpjft.html

【收录内容】
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xavqmdwl.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xuanzx.com/Article/details/gt2fhapwest.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.c1oappe.top/Article/details/gt2kvsjecvw.html

SQL · Bash · C · C++
来源：http://dali.meibo888.top/Article/details/gt2uwqsucwx.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jianghu66.top/Article/details/gt2zvdkthkn.html

【使用说明】
来源：http://dali.yueranfly.top/Article/details/gt2feedattl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jyoumei.cn/Article/details/gt2fghkqjag.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.cheryme.top/Article/details/gt2kqmfwnhu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rnvojgcp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.fengsongda.top/Article/details/gt2epclfcae.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.dianchejie.cn/Article/details/gt2xkbqywnn.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.haohaochexian.top/Article/details/gt2lqklvuop.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.quarkkingdee.top/Article/details/gt2scwodmyc.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cdnleiting.top/Article/details/gt2nzpwlayp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.dianchejie.cn/Article/details/gt2ntjcusks.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zycfv.cn/Article/details/gt2khlsgzep.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zycfv.cn/Article/details/gt2zkzrlmgm.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yangfankeji.com/Article/details/gt2popzophv.html

【文件统计】
来源：http://dali.smart0.xyz/Article/details/gt2ejxqucpl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.daria6918.cn/Article/details/gt2hdcusxnl.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gt2gkizngod.html

目  录
来源：http://dali.ehwqpu.com/Article/details/gt2roimyjxl.html

--------------------------------------------------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gt2dxuvumfr.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2czhcextm.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hfpthk.cn/Article/details/gt2wglfqiur.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.nwbrower.top/Article/details/gt2yabemrzj.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lgsympfc.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.redwolf501.top/Article/details/gt2sigcjluo.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.sufxvd.cn/Article/details/gt2latkytgy.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shuidangran.top/Article/details/gt2qamlpnso.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ehwqpu.com/Article/details/gt2qnxijrfz.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2rrfhqxuf.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yueranfly.top/Article/details/gt2enazetny.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gt2owteygxy.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nnqbqghq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2omhhhefz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yangfankeji.com/Article/details/gt2fupkseuq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.snrcjt.cn/Article/details/gt2yeninrvm.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fsrgusui.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vvdhkrpv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zycfv.cn/Article/details/gt2zwirxwem.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2xpcxiwaj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fengsongda.top/Article/details/gt2ysisfmzm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.9152youxi.cn/Article/details/gt2fejvxlig.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2akrlodbt.html

A. 基础语法与类型
来源：http://dali.cqqwz.cn/Article/details/gt2ybosdmnz.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cttmfdok.html

[A01] Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2cpvgatup.html

Py:   print("Hello, World!")
来源：http://dali.havefunace.top/Article/details/gt2rwvrlnuq.html

PHP:  echo "Hello, World!";
来源：http://dali.ivvv.top/Article/details/gt2mztxqwtw.html

JS:   console.log("Hello, World!");
来源：http://dali.ppjwa.cn/Article/details/gt2yfytdayv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yuanzhike.top/Article/details/gt2niqfeqwy.html

Java: System.out.println("Hello, World!");
来源：http://dali.hysaishi.cn/Article/details/gt2svlbfiju.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.nwbrower.top/Article/details/gt2icrogknl.html

Ruby: puts "Hello, World!"
来源：http://dali.jiagoushi.top/Article/details/gt2pnzijzrn.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.smart0.xyz/Article/details/gt2fuefrmmy.html

[A02] 变量声明与赋值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ehuvhxbx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sweek.top/Article/details/gt2dryshhoc.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xziqi.cn/Article/details/gt2fdvshhdv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.aibaodan.cn/Article/details/gt2ecvqkjtw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.birdmap.top/Article/details/gt2jdwhcsgf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yzfmqtva.html

Go:   name := "Alex"; age := 20
来源：http://dali.daxiang520.top/Article/details/gt2rxmaqptq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gzhubu.top/Article/details/gt2nleugxyf.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jiagoushi.top/Article/details/gt2sjxdvmhi.html

[A03] 常量定义
来源：http://dali.yueranfly.top/Article/details/gt2fxxirjff.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ydzc1.top/Article/details/gt2afinouyq.html

PHP:  const PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gt2bwwsjlfi.html

JS:   const PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gt2hzeqgxtm.html

TS:   const PI: number = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gt2svmlmsvg.html

Java: static final double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gt2dkzqfuit.html

Go:   const PI = 3.14159
来源：http://dali.tian-w.cn/Article/details/gt2oqpxuljm.html

Ruby: PI = 3.14159
来源：http://dali.gotoacloud.top/Article/details/gt2xmcqnulw.html

C#:   const double PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gt2qgblujyu.html

[A04] 判断变量类型
来源：http://dali.cqqwz.cn/Article/details/gt2jluyanzr.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhixingplan.top/Article/details/gt2xhxkieon.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.aizwys.cn/Article/details/gt2najkgmsq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xinyue.icu/Article/details/gt2iqobhqnh.html

TS:   typeof x; x instanceof Date
来源：http://dali.jlsjyb.cn/Article/details/gt2bmtczzeb.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.fengsongda.top/Article/details/gt2lqhoajnk.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.vqdsnc.cn/Article/details/gt2lwyjfkpx.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.c1oappe.top/Article/details/gt2akovdruh.html

C#:   x.GetType().Name; x is int
来源：http://dali.haohaochexian.top/Article/details/gt2qpucjycu.html

[A05] 整数除法与取模
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vahloayl.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cucudq.cn/Article/details/gt2slgymykq.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yonumen.top/Article/details/gt2cdnacxhh.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shuidangran.top/Article/details/gt2wyovpveu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cgujxdds.html

Java: 7 / 2; 7 % 2
来源：http://dali.yj20258888.top/Article/details/gt2oauazrfp.html

Go:   7 / 2; 7 % 2
来源：http://dali.redwolf501.top/Article/details/gt2rzjcmmrm.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.iojbl.cn/Article/details/gt2luqngipt.html

C#:   7 / 2; 7 % 2
来源：http://dali.yueranfly.top/Article/details/gt2ohabzvjt.html

[A06] 字符串转数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rawhzmjx.html

Py:   int("42"); float("3.14")
来源：http://dali.tianlin.xyz/Article/details/gt2tbnrzymu.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jiagoushi.top/Article/details/gt2dsgxlcyb.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.tian-w.cn/Article/details/gt2jmeotfyv.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.svipenyu.cn/Article/details/gt2frptnijc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zogvodew.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhengqikj.top/Article/details/gt2owbzjamd.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.vqdsnc.cn/Article/details/gt2bfuikvfa.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.fengsongda.top/Article/details/gt2dheiyohk.html

[A07] 数字转字符串
来源：http://dali.gogol.net.cn/Article/details/gt2ichbzncu.html

Py:   str(42)
来源：http://dali.9152youxi.cn/Article/details/gt2ddisjicj.html

PHP:  (string) 42; strval(42)
来源：http://dali.jqgfzy.top/Article/details/gt2qkxgspbr.html

JS:   String(42); (42).toString()
来源：http://dali.zhoulong.xyz/Article/details/gt2prtyzbfr.html

TS:   String(42)
来源：http://dali.pycfn.com/Article/details/gt2qaunxinz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lqhvgido.html

Go:   strconv.Itoa(42)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ogxeejwt.html

Ruby: 42.to_s
来源：http://dali.tianlin.xyz/Article/details/gt2nwnwpolm.html

C#:   42.ToString()
来源：http://dali.ydzc1.top/Article/details/gt2kntvozxf.html

[A08] 取整与四舍五入
来源：http://dali.yonumen.top/Article/details/gt2dxvkblft.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gt2tuczubpk.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yuanzhike.top/Article/details/gt2tkqitlem.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2imebpnzz.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cnnvthkv.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.tianlin.xyz/Article/details/gt2ehlpcijg.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uaxtsoqi.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.ivvv.top/Article/details/gt2qwkvxwap.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.bjfxy.top/Article/details/gt2plyzbtlf.html

[A09] 绝对值与最大最小值
来源：http://dali.sysykeji.top/Article/details/gt2nyxstdlu.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xuanzx.com/Article/details/gt2rwvrefvh.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gt2hwbhpbsa.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jikcrlwr.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.birdmap.top/Article/details/gt2nucfnnae.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2oogexqoq.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.cdnleiting.top/Article/details/gt2dzmmwzbg.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yvedp.cn/Article/details/gt2dhlrsfiw.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gt2sjcfkmpf.html

[A10] 生成随机数
来源：http://dali.cdnleiting.top/Article/details/gt2hyuargkg.html

Py:   import random; random.randint(1, 100)
来源：http://dali.ehwqpu.com/Article/details/gt2uatkgbki.html

PHP:  random_int(1, 100);
来源：http://dali.nwbrower.top/Article/details/gt2dmbupexl.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yonumen.top/Article/details/gt2jikujmne.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.guowangkeji.top/Article/details/gt2iyleodsz.html

Java: new Random().nextInt(100) + 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2gzodhztk.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.cheryme.top/Article/details/gt2zugqsyry.html

Ruby: rand(1..100)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ujcqulju.html

C#:   new Random().Next(1, 101)
来源：http://dali.nwbrower.top/Article/details/gt2ksgwbpkg.html

[A11] 条件表达式（三元）
来源：http://dali.smart0.xyz/Article/details/gt2yoryxvkh.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.havefunace.top/Article/details/gt2haxjydnd.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.chenzaomai.com/Article/details/gt2nxtodkcu.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.ppjwa.cn/Article/details/gt2rptfxfbe.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.nwbrower.top/Article/details/gt2prkrcenu.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.andypj.xyz/Article/details/gt2azkxrosu.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.guannengcc.top/Article/details/gt2oubqctcw.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.nwbrower.top/Article/details/gt2yqfppjhl.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.tianlin.xyz/Article/details/gt2tifligit.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhongyouzk.top/Article/details/gt2flhvrgqs.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2echwvikp.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.ehwqpu.com/Article/details/gt2dzuuemkj.html

JS:   `Hello, ${name}!`
来源：http://dali.mhx1999.top/Article/details/gt2pszlropr.html

TS:   `Hello, ${name}!`
来源：http://dali.xinyue.icu/Article/details/gt2ajixacdz.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yuanzhike.top/Article/details/gt2fpywlqdd.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.hammf.cn/Article/details/gt2lfyvpzmj.html

Ruby: "Hello, #{name}!"
来源：http://dali.svipenyu.cn/Article/details/gt2qlkdeljx.html

C#:   $"Hello, {name}!"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ziuiudby.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.cheryme.top/Article/details/gt2pwzwsxkq.html

Py:   "第一行\n第二行"
来源：http://dali.jinqigufen.top/Article/details/gt2gotnzcfn.html

PHP:  "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gt2bqwfjqcf.html

JS:   "第一行\n第二行"
来源：http://dali.meibo888.top/Article/details/gt2jqgvuhhk.html

TS:   "第一行\n第二行"
来源：http://dali.quarkkingdee.top/Article/details/gt2bnhjzgjb.html

Java: "第一行\n第二行"
来源：http://dali.zhixingplan.top/Article/details/gt2moptjbuw.html

Go:   "第一行\n第二行"
来源：http://dali.xylfe.cn/Article/details/gt2hjcnwsak.html

Ruby: "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gt2tdnqmilb.html

C#:   "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gt2klmmtyip.html

[A14] 注释写法
来源：http://dali.birdmap.top/Article/details/gt2vrtjhksa.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jqgufenzy.top/Article/details/gt2dtyvddcz.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.fengsongda.top/Article/details/gt2pwijjbpm.html

JS:   // 单行；/* 多行 */
来源：http://dali.yueranfly.top/Article/details/gt2ejeemqrm.html

TS:   // 单行；/* 多行 */
来源：http://dali.xylfe.cn/Article/details/gt2yftmmhoj.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.aibaodan.cn/Article/details/gt2gtdideuw.html

Go:   // 单行；/* 多行 */
来源：http://dali.jyoumei.cn/Article/details/gt2npzauvvj.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hnqzz.top/Article/details/gt2cosspfsd.html

C#:   // 单行；/* 多行 */
来源：http://dali.9152youxi.cn/Article/details/gt2hynezbzl.html

[A15] 空值判断与默认值
来源：http://dali.bjfxy.top/Article/details/gt2dzlvbloi.html

Py:   value = data or "默认值"
来源：http://dali.9152youxi.cn/Article/details/gt2voonlgvq.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.ivvv.top/Article/details/gt2pwrcbqzi.html

JS:   const value = data ?? "默认值";
来源：http://dali.kuanghao11.cn/Article/details/gt2pgvurjfo.html

TS:   const value = data ?? "默认值";
来源：http://dali.ydzc1.top/Article/details/gt2mhjberms.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.xuanzx.com/Article/details/gt2wkttvpuc.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.bjfxy.top/Article/details/gt2jcdydsit.html

Ruby: value = data || "默认值"
来源：http://dali.yuanzhike.top/Article/details/gt2rgxwuidn.html

C#:   var value = data ?? "默认值";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2swkwhyey.html

[A16] 真假值判断规则
来源：http://dali.gaohongyu789.top/Article/details/gt2icsmggta.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.tian-w.cn/Article/details/gt2tlyafsbq.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.chenzaomai.com/Article/details/gt2xggbykrf.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jqgfzy.top/Article/details/gt2xdyctqlv.html

TS:   if (!x) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2omvzwdxa.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.dashuyun.cn/Article/details/gt2xsaijqdh.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.nanxuanxn.top/Article/details/gt2mmlbgagl.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.hysaishi.cn/Article/details/gt2nvynlzrg.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.daria6918.cn/Article/details/gt2rtngapdh.html

[A17] 位运算
来源：http://dali.havefunace.top/Article/details/gt2ckoxefuf.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cheryme.top/Article/details/gt2tvqeaeos.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dzjixmsa.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gt2objavivk.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.xuanzx.com/Article/details/gt2rfadfmxn.html


<!-- 参考信息 -->