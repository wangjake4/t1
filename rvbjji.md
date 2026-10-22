代发 wailian999

[U103] JS：定时器
来源：http://dali.xuanzx.com/Article/details/gt2mpeplorz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sysykeji.top/Article/details/gt2cowwfwxu.html

[U104] JS：防抖
来源：http://dali.svipenyu.cn/Article/details/gt2pfaxwtcf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2llrcxewk.html

[U105] JS：节流
来源：http://dali.316326.xyz/Article/details/gt2voqownad.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hfpthk.cn/Article/details/gt2stkebttc.html

[U106] JS：日期格式化
来源：http://dali.sysykeji.top/Article/details/gt2evdtsuxe.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jiagoushi.top/Article/details/gt2gvgeqwvj.html

[U107] JS：数字千分位
来源：http://dali.sufxvd.cn/Article/details/gt2ruzruneh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.feifeiyinyue.top/Article/details/gt2oujxpnet.html

[U108] JS：随机整数
来源：http://dali.smart0.xyz/Article/details/gt2oehnblca.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ybcxt.top/Article/details/gt2rpfovfks.html

[U109] JS：数组分组
来源：http://dali.xylfe.cn/Article/details/gt2dotofinh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gt2fugdymkf.html

[U110] JS：数组分块
来源：http://dali.aibaodan.cn/Article/details/gt2yoldlnqj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.fengsongda.top/Article/details/gt2pvcfxixn.html

[U111] JS：对象转 Map
来源：http://dali.jyoumei.cn/Article/details/gt2kvdkdtqn.html

new Map(Object.entries(obj))
来源：http://dali.wangshuangyany.cn/Article/details/gt2ofkghvoz.html

[U112] JS：字符串补位
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2afgnvsml.html

"7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gt2yzbvdkpl.html

[U113] JS：正则替换全部
来源：http://dali.chenlongwang.top/Article/details/gt2iqgnxcnj.html

s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gt2scsnjeso.html

[U114] JS：JSON 深比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2tooinxat.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sysykeji.top/Article/details/gt2lenekxkt.html

[U115] JS：生成 UUID
来源：http://dali.cucudq.cn/Article/details/gt2omfrzlhz.html

crypto.randomUUID()
来源：http://dali.yj20258.top/Article/details/gt2lpcdstud.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gogol.net.cn/Article/details/gt2qsjqlkac.html

/** @param {string} name */ function f(name) {}
来源：http://dali.sufxvd.cn/Article/details/gt2vydcebfu.html

[U117] JS：单元测试
来源：http://dali.chenzaomai.com/Article/details/gt2siejypfc.html

npm i -D vitest;  npx vitest
来源：http://dali.svipenyu.cn/Article/details/gt2acdlnkxr.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyzkbjw.html

npm i -D vite;  npx vite
来源：http://dali.sxryk.cn/Article/details/gt2wpzphcyp.html

[U119] JS：生产构建
来源：http://dali.jyoumei.cn/Article/details/gt2mxweubrj.html

npx vite build
来源：http://dali.nanxinkj.top/Article/details/gt2vqhhlmji.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cashguo.top/Article/details/gt2iexzfcoo.html

import.meta.env.VITE_API_URL
来源：http://dali.hnqzz.top/Article/details/gt2vrjnbyrf.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2uzmkddux.html

统计汇总
来源：http://dali.birdmap.top/Article/details/gt2vvkiqwuv.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2bhkaaxmc.html

按语言统计（条）：
来源：http://dali.fzhhl.top/Article/details/gt2jalojlte.html

Python ......... 252
来源：http://dali.sufxvd.cn/Article/details/gt2fdtrhsfn.html

PHP ............ 252
来源：http://dali.hongshengwenyu.top/Article/details/gt2igttyaxs.html

JavaScript ..... 252
来源：http://dali.zhoulong.xyz/Article/details/gt2jjtrgiwj.html

TypeScript ..... 212
来源：http://dali.cheryme.top/Article/details/gt2orxufyii.html

Java ........... 212
来源：http://dali.nanxuanxn.top/Article/details/gt2enbxanuv.html

Go ............. 212
来源：http://dali.sufxvd.cn/Article/details/gt2codjgnwd.html

Ruby ........... 212
来源：http://dali.0kj1m.cn/Article/details/gt2fpqqfvbi.html

C# ............. 212
来源：http://dali.c1oappe.top/Article/details/gt2gewszabc.html

C .............. 30
来源：http://dali.jqgfzy.top/Article/details/gt2uurarkqy.html

C++ ............ 30
来源：http://dali.chenzaomai.com/Article/details/gt2ekbjalei.html

SQL ............ 90
来源：http://dali.andypj.xyz/Article/details/gt2altfpvzy.html

Bash ........... 80
来源：http://dali.jinqigfzy.top/Article/details/gt2mnbgimlj.html

Kotlin ......... 15
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wiqpbsho.html

Swift .......... 15
来源：http://dali.pengpengdd.cyou/Article/details/gt2esjddrqr.html

Lua ............ 10
来源：http://dali.c1oappe.top/Article/details/gt2sfcufwak.html

Perl ........... 10
来源：http://dali.hongshengwenyu.top/Article/details/gt2pbhmfbjf.html

Scala .......... 10
来源：http://dali.cucudq.cn/Article/details/gt2ixaiyowo.html

------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gt2ydzdyudj.html

合计 ........... 2106 条
来源：http://dali.dianchejie.cn/Article/details/gt2ovmqlhwn.html

按章节统计：
来源：http://dali.cheryme.top/Article/details/gt2yiozllrg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yvedp.cn/Article/details/gt2feaaclzk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhiwuduotai.top/Article/details/gt2bpaztgqc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2omenwhfg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jinqigfzy.top/Article/details/gt2gguqtqki.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yueranfly.top/Article/details/gt2tmlkifsl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.fengsongda.top/Article/details/gt2fdrrjqzt.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2awhbfaup.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.316326.xyz/Article/details/gt2vyvmeech.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gt2kupwolel.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2udhismju.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gt2xhcoyklb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gt2clwcsibg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gt2yhpjgqxh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.nanxuanxn.top/Article/details/gt2koztoqln.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.dashuyun.cn/Article/details/gt2brzdbris.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gt2qdloxemp.html

Q SQL 专题                              90
来源：http://dali.mhx1999.top/Article/details/gt2ejxqgsko.html

R Bash 专题                             80
来源：http://dali.guowangkeji.top/Article/details/gt2uzsqutvk.html

S C / C++ 专题                          60
来源：http://dali.sweek.top/Article/details/gt2dhyutzgc.html

T 其他语言补充                          60
来源：http://dali.jianghu66.top/Article/details/gt2lrvhpfwj.html

U 高频实用片段                         120
来源：http://dali.jinqigufen.top/Article/details/gt2moxkojsh.html

------------------------------------
来源：http://dali.guannengcc.top/Article/details/gt2gvqqacln.html

合计                                  2106 条
来源：http://dali.tanke756.top/Article/details/gt2ltkkzbnm.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gt2prrvugcn.html

使用提醒
来源：http://dali.sysykeji.top/Article/details/gt2udtolfvi.html

--------------------------------------------------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gt2tnoqkebz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hzsgkiwx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.redwolf501.top/Article/details/gt2ikufcqxv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.dianchejie.cn/Article/details/gt2zlmbtcek.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.fzhhl.top/Article/details/gt2khwpwoby.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.316326.xyz/Article/details/gt2jqljlrsn.html

—— 文件结束 ——
来源：http://dali.nanxuanxn.top/Article/details/gt2dbvvraza.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2lokzayta.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hysaishi.cn/Article/details/gt2bslgciiy.html

Common Programming Examples Cheat Book
来源：http://dali.316326.xyz/Article/details/gt2vsmlzbqs.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2veqsmnat.html

【收录内容】
来源：http://dali.dashuyun.cn/Article/details/gt2jpuixzlg.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhiwuduotai.top/Article/details/gt2huhvbbro.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.wangdashe.top/Article/details/gt2zbtlhrje.html

SQL · Bash · C · C++
来源：http://dali.gogol.net.cn/Article/details/gt2xpmxdjti.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhoulong.xyz/Article/details/gt2xhidetwj.html

【使用说明】
来源：http://dali.jyoumei.cn/Article/details/gt2ojfyxwsb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ehwqpu.com/Article/details/gt2vjgfxlvo.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinqigfzy.top/Article/details/gt2shhfilud.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xinyue.icu/Article/details/gt2mqdjrfdq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hnqzz.top/Article/details/gt2odanednt.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xylfe.cn/Article/details/gt2pfrxieud.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cqqwz.cn/Article/details/gt2lwhsexdk.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.smart0.xyz/Article/details/gt2qlnxxkko.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.haohaochexian.top/Article/details/gt2ktmnhruy.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.gogol.net.cn/Article/details/gt2xlpxxgvt.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.wangshuangyany.cn/Article/details/gt2uvzduowr.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ksyozfph.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhiwuduotai.top/Article/details/gt2fsrwroaw.html

【文件统计】
来源：http://dali.yuanzhike.top/Article/details/gt2sppdumed.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.nwbrower.top/Article/details/gt2zgnrygcl.html

--------------------------------------------------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gt2esntnexx.html

目  录
来源：http://dali.havefunace.top/Article/details/gt2aiuisfkx.html

--------------------------------------------------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gt2kwehewen.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2tjbchhkn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2tewrsyql.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.bjfxy.top/Article/details/gt2upzgytge.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ctsjnxlh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2utymgdbh.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2jmeaduub.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.andypj.xyz/Article/details/gt2cwphyrmo.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.gzhubu.top/Article/details/gt2mtdqutxq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gt2hcdgzgpa.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.cheryme.top/Article/details/gt2tobqduga.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iwivrevv.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.pycfn.com/Article/details/gt2kvfrwzho.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xylfe.cn/Article/details/gt2mybmgwwm.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yj20258.top/Article/details/gt2bizikgsb.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2icnuiubb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yangfankeji.com/Article/details/gt2muvihwmf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yj20258.top/Article/details/gt2uucyfmxw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.sweek.top/Article/details/gt2gnbtuuwu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.cheryme.top/Article/details/gt2vhrhisql.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hfpthk.cn/Article/details/gt2nyilwwcp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ldkrajcv.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2xucshdzg.html

A. 基础语法与类型
来源：http://dali.dashuyun.cn/Article/details/gt2ehqdumml.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2umtxznus.html

[A01] Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2dobivhft.html

Py:   print("Hello, World!")
来源：http://dali.zhengqikj.top/Article/details/gt2ajdiqcwx.html

PHP:  echo "Hello, World!";
来源：http://dali.jinqigfzy.top/Article/details/gt2mcxocvoe.html

JS:   console.log("Hello, World!");
来源：http://dali.zhongyouzk.top/Article/details/gt2wfcnmnjn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sswfubct.html

Java: System.out.println("Hello, World!");
来源：http://dali.chenzaomai.com/Article/details/gt2asmvpqlk.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.tian-w.cn/Article/details/gt2eafuocet.html

Ruby: puts "Hello, World!"
来源：http://dali.bjfxy.top/Article/details/gt2hggtqdfw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yj20258.top/Article/details/gt2wvgtjpah.html

[A02] 变量声明与赋值
来源：http://dali.ivvv.top/Article/details/gt2idlvvnap.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.9152youxi.cn/Article/details/gt2dgzpjouq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.chenjidiqi.icu/Article/details/gt2vlirppmq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.smart0.xyz/Article/details/gt2kmcaxquo.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yanxiufei.cn/Article/details/gt2tbjcghog.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yj20258.top/Article/details/gt2gjzwuxry.html

Go:   name := "Alex"; age := 20
来源：http://dali.yuanzhike.top/Article/details/gt2mcstezos.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gotoacloud.top/Article/details/gt2jumisprw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.gaohongyu789.top/Article/details/gt2cnsjpkhb.html

[A03] 常量定义
来源：http://dali.sxryk.cn/Article/details/gt2csafgsyt.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zycfv.cn/Article/details/gt2ksaphqxu.html

PHP:  const PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gt2djrkprdc.html

JS:   const PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gt2gzarmlak.html

TS:   const PI: number = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gt2kxwzyrrs.html

Java: static final double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gt2oypqniaj.html

Go:   const PI = 3.14159
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eiziipxg.html

Ruby: PI = 3.14159
来源：http://dali.wangdashe.top/Article/details/gt2ytugcana.html

C#:   const double PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gt2nlljhelx.html

[A04] 判断变量类型
来源：http://dali.pycfn.com/Article/details/gt2xzhbnucw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xuanzx.com/Article/details/gt2alkyxmvm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.kuanghao11.cn/Article/details/gt2dewijkvz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.cqqwz.cn/Article/details/gt2fteojrkh.html

TS:   typeof x; x instanceof Date
来源：http://dali.ivvv.top/Article/details/gt2rogmlnbo.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.aizwys.cn/Article/details/gt2ncolajpq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jqgfzy.top/Article/details/gt2wqqterqm.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.cheryme.top/Article/details/gt2cmljtlti.html

C#:   x.GetType().Name; x is int
来源：http://dali.tianlin.xyz/Article/details/gt2xgsecccw.html

[A05] 整数除法与取模
来源：http://dali.yuxming.cn/Article/details/gt2gcyqvmto.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.nanxinkj.top/Article/details/gt2mamjwrrs.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2weibywhl.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2gkimfgcx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zyugmixy.html

Java: 7 / 2; 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pdejqejy.html

Go:   7 / 2; 7 % 2
来源：http://dali.zycfv.cn/Article/details/gt2ffhiwjbz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xinyue.icu/Article/details/gt2fyvvopmg.html

C#:   7 / 2; 7 % 2
来源：http://dali.ybcxt.top/Article/details/gt2pxghfzcu.html

[A06] 字符串转数字
来源：http://dali.yueranfly.top/Article/details/gt2txurdycf.html

Py:   int("42"); float("3.14")
来源：http://dali.vqdsnc.cn/Article/details/gt2gwubldxc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.quarkkingdee.top/Article/details/gt2ctshmqpo.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.gogol.net.cn/Article/details/gt2visavccu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hammf.cn/Article/details/gt2pruvggtc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.birdmap.top/Article/details/gt2xecsaykb.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.guannengcc.top/Article/details/gt2ukjkfptq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hywenlv.cn/Article/details/gt2sgzehvsm.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.0kj1m.cn/Article/details/gt2ltijvfzs.html

[A07] 数字转字符串
来源：http://dali.ehwqpu.com/Article/details/gt2pkslpnoy.html

Py:   str(42)
来源：http://dali.quarkkingdee.top/Article/details/gt2mfxkybgj.html

PHP:  (string) 42; strval(42)
来源：http://dali.yj20258888.top/Article/details/gt2wdqlplub.html

JS:   String(42); (42).toString()
来源：http://dali.tanke756.top/Article/details/gt2kqsjjdtm.html

TS:   String(42)
来源：http://dali.zhixingplan.top/Article/details/gt2padhqmym.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.pycfn.com/Article/details/gt2alaifqje.html

Go:   strconv.Itoa(42)
来源：http://dali.hysaishi.cn/Article/details/gt2nqqsftcr.html

Ruby: 42.to_s
来源：http://dali.chenzaomai.com/Article/details/gt2wzgxnhpu.html

C#:   42.ToString()
来源：http://dali.hnxiangtu.top/Article/details/gt2jihwoknx.html

[A08] 取整与四舍五入
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vyldwdna.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yonumen.top/Article/details/gt2exxqbils.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhixingplan.top/Article/details/gt2vgnhscwm.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zdqjudy.top/Article/details/gt2sebspyef.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jqgfzy.top/Article/details/gt2ngpcjmxb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.sxryk.cn/Article/details/gt2djoygbgj.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.hongshengwenyu.top/Article/details/gt2evclkzlt.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.havefunace.top/Article/details/gt2dbsyweov.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yuxming.cn/Article/details/gt2efrtoybu.html

[A09] 绝对值与最大最小值
来源：http://dali.9152youxi.cn/Article/details/gt2jwtnzqbg.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sweek.top/Article/details/gt2nqtswdnh.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2elmihxon.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pobyldxj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gt2kurdngdn.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2drdgcxvv.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.andypj.xyz/Article/details/gt2pfkhhfgw.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yvedp.cn/Article/details/gt2ooqnnrhe.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.hfpthk.cn/Article/details/gt2ejtnsgoa.html

[A10] 生成随机数
来源：http://dali.gaohongyu789.top/Article/details/gt2fzjsdxkh.html

Py:   import random; random.randint(1, 100)
来源：http://dali.shangyingyoupin.top/Article/details/gt2siozukhg.html

PHP:  random_int(1, 100);
来源：http://dali.hongshengwenyu.top/Article/details/gt2gkzbhcez.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.chenzaomai.com/Article/details/gt2pbavtpqa.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zycfv.cn/Article/details/gt2pakhqvlf.html

Java: new Random().nextInt(100) + 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2trczdlgx.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hywenlv.cn/Article/details/gt2cgerdjgj.html

Ruby: rand(1..100)
来源：http://dali.sysykeji.top/Article/details/gt2wkwntjks.html

C#:   new Random().Next(1, 101)
来源：http://dali.tanke756.top/Article/details/gt2ytcofpjd.html

[A11] 条件表达式（三元）
来源：http://dali.hongshengwenyu.top/Article/details/gt2xmbhjddh.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.xziqi.cn/Article/details/gt2osckaaft.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.nwbrower.top/Article/details/gt2ubimzzrz.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhiwuduotai.top/Article/details/gt2xupcxibk.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yldbtfgy.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.dashuyun.cn/Article/details/gt2qifkvdnp.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.mhx1999.top/Article/details/gt2jglnlusl.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gt2gbfbtzyr.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.ivvv.top/Article/details/gt2ykmqtlss.html

[A12] 字符串插值 / 格式化
来源：http://dali.kuanghao11.cn/Article/details/gt2yamohesv.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yonumen.top/Article/details/gt2veplcczo.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.hywenlv.cn/Article/details/gt2eidnmrjx.html

JS:   `Hello, ${name}!`
来源：http://dali.gogol.net.cn/Article/details/gt2cfwdrhnf.html

TS:   `Hello, ${name}!`
来源：http://dali.xylfe.cn/Article/details/gt2ygvaeyzh.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vbbqsnsk.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.sufxvd.cn/Article/details/gt2tapimmpu.html

Ruby: "Hello, #{name}!"
来源：http://dali.sweek.top/Article/details/gt2qfqvxhlw.html

C#:   $"Hello, {name}!"
来源：http://dali.yangfankeji.com/Article/details/gt2bfxdonsd.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.cucudq.cn/Article/details/gt2qkqzuhsj.html

Py:   "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gt2yvpdhlgy.html

PHP:  "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gt2peexglxh.html

JS:   "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gt2pitimcsh.html

TS:   "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gt2tnrojfll.html

Java: "第一行\n第二行"
来源：http://dali.jinqigfzy.top/Article/details/gt2zzsgyunv.html

Go:   "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gt2pmzardtn.html

Ruby: "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gt2odlhpzqv.html

C#:   "第一行\n第二行"
来源：http://dali.cdnleiting.top/Article/details/gt2yqrtjqzt.html

[A14] 注释写法
来源：http://dali.zhixingplan.top/Article/details/gt2dkydopmv.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.dashuyun.cn/Article/details/gt2keqlijko.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.ppjwa.cn/Article/details/gt2trknoxsp.html

JS:   // 单行；/* 多行 */
来源：http://dali.nanxuanxn.top/Article/details/gt2pcyousyj.html

TS:   // 单行；/* 多行 */
来源：http://dali.havefunace.top/Article/details/gt2wcwpzpka.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hongshengwenyu.top/Article/details/gt2yplbsedq.html

Go:   // 单行；/* 多行 */
来源：http://dali.feifeiyinyue.top/Article/details/gt2ncoaiehr.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jqgfzy.top/Article/details/gt2qmjdospa.html

C#:   // 单行；/* 多行 */
来源：http://dali.nanxuanxn.top/Article/details/gt2hvtdcjow.html

[A15] 空值判断与默认值
来源：http://dali.hysaishi.cn/Article/details/gt2uoynihug.html

Py:   value = data or "默认值"
来源：http://dali.gzhubu.top/Article/details/gt2slapahjr.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.bjfxy.top/Article/details/gt2psbsmhty.html

JS:   const value = data ?? "默认值";
来源：http://dali.guowangkeji.top/Article/details/gt2yrlwieza.html

TS:   const value = data ?? "默认值";
来源：http://dali.havefunace.top/Article/details/gt2omqbwbaj.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jianghu66.top/Article/details/gt2jacsjniy.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yj202588.top/Article/details/gt2jvpumjnv.html

Ruby: value = data || "默认值"
来源：http://dali.jqgfzy.top/Article/details/gt2qotlxcun.html

C#:   var value = data ?? "默认值";
来源：http://dali.iojbl.cn/Article/details/gt2cwkowcqe.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlmzccj.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jinqigfzy.top/Article/details/gt2yxmkobjk.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jinqigufen.top/Article/details/gt2vfjfijmm.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.kuanghao11.cn/Article/details/gt2clfsafub.html

TS:   if (!x) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2orginzzf.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.andypj.xyz/Article/details/gt2pqngevid.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.andypj.xyz/Article/details/gt2cpmgklga.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.kuanghao11.cn/Article/details/gt2tqpfpqfk.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.ppjwa.cn/Article/details/gt2rieoswhf.html

[A17] 位运算
来源：http://dali.dianchejie.cn/Article/details/gt2wvpwmfgz.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ujrxxyae.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.daxiang520.top/Article/details/gt2uwriedkg.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.snrcjt.cn/Article/details/gt2lgyhslix.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.shzxlz.cn/Article/details/gt2zwxetran.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shzxlz.cn/Article/details/gt2dgviejvk.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yongpay.top/Article/details/gt2duplqpds.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gt2eqjnwbwk.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ppjwa.cn/Article/details/gt2kvgdofsy.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jinqigfzy.top/Article/details/gt2fkbsvndp.html

Py:   ord("A"); chr(65)
来源：http://dali.0kj1m.cn/Article/details/gt2injnufsc.html

PHP:  ord("A"); chr(65)
来源：http://dali.ppjwa.cn/Article/details/gt2hirysmch.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.mhx1999.top/Article/details/gt2wodfdfio.html


<!-- 参考信息 -->