代发 wailian999

[U101] JS：classList 操作
来源：http://dali.hnxiangtu.top/Article/details/gtjnpqxjcb.html

el.classList.toggle("active")
来源：http://dali.yuanzhike.top/Article/details/gtlulmyllc.html

[U102] JS：本地存储
来源：http://dali.zhixingplan.top/Article/details/gtoehthtqf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhengqikj.top/Article/details/gtpihubfqx.html

[U103] JS：定时器
来源：http://dali.yvedp.cn/Article/details/gtdnwergbg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gzhubu.top/Article/details/gtjfrpmkaa.html

[U104] JS：防抖
来源：http://dali.yanxiufei.cn/Article/details/gtvhaxzxxf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gttdnkivjk.html

[U105] JS：节流
来源：http://dali.xuanzx.com/Article/details/gtfusmremu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtratzyiba.html

[U106] JS：日期格式化
来源：http://dali.0kj1m.cn/Article/details/gtgmpoxcxq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.snrcjt.cn/Article/details/gtunyfsuag.html

[U107] JS：数字千分位
来源：http://dali.yongpay.top/Article/details/gtjmsqbdhd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.chenzaomai.com/Article/details/gtqkmtrrkp.html

[U108] JS：随机整数
来源：http://dali.yueranfly.top/Article/details/gtagvqyfao.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.316326.xyz/Article/details/gttgepajwc.html

[U109] JS：数组分组
来源：http://dali.yj202588.top/Article/details/gtqqdieuua.html

Object.groupBy(arr, x => x.type)
来源：http://dali.tanke756.top/Article/details/gtjzvmlnzv.html

[U110] JS：数组分块
来源：http://dali.ehwqpu.com/Article/details/gtwznpozuf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.svipenyu.cn/Article/details/gtlluwchul.html

[U111] JS：对象转 Map
来源：http://dali.nanxinkj.top/Article/details/gtkhibuwqi.html

new Map(Object.entries(obj))
来源：http://dali.wangshuangyany.cn/Article/details/gtszuoxxkx.html

[U112] JS：字符串补位
来源：http://dali.zhixingplan.top/Article/details/gtqnwpiaho.html

"7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtqbpuhjdu.html

[U113] JS：正则替换全部
来源：http://dali.xuetiantiany.cn/Article/details/gtsydqkvpw.html

s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtimyaqkwp.html

[U114] JS：JSON 深比较
来源：http://dali.ybcxt.top/Article/details/gtkgqjknxw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gogol.net.cn/Article/details/gtjrfbdhdw.html

[U115] JS：生成 UUID
来源：http://dali.gotoacloud.top/Article/details/gtphgsmafy.html

crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gtlqwmszud.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.meibo888.top/Article/details/gtmvrnpkro.html

/** @param {string} name */ function f(name) {}
来源：http://dali.chenzaomai.com/Article/details/gttecwogic.html

[U117] JS：单元测试
来源：http://dali.tanke756.top/Article/details/gtutswkwel.html

npm i -D vitest;  npx vitest
来源：http://dali.andypj.xyz/Article/details/gthjzcrcfd.html

[U118] JS：开发服务器
来源：http://dali.9152youxi.cn/Article/details/gtxkdcxrrm.html

npm i -D vite;  npx vite
来源：http://dali.snrcjt.cn/Article/details/gtdoniwnts.html

[U119] JS：生产构建
来源：http://dali.jyoumei.cn/Article/details/gtoiqhepca.html

npx vite build
来源：http://dali.fengsongda.top/Article/details/gtfptpyozi.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.bjfxy.top/Article/details/gtpaxqeizc.html

import.meta.env.VITE_API_URL
来源：http://dali.gzhubu.top/Article/details/gtmkebmfov.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtjigqbrit.html

统计汇总
来源：http://dali.yvedp.cn/Article/details/gtqpkmcnng.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtzncdkqrg.html

按语言统计（条）：
来源：http://dali.nwbrower.top/Article/details/gtedajtomk.html

Python ......... 252
来源：http://dali.aizwys.cn/Article/details/gtdflrmgxc.html

PHP ............ 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfveyvue.html

JavaScript ..... 252
来源：http://dali.dashuyun.cn/Article/details/gtllpclxjt.html

TypeScript ..... 212
来源：http://dali.jianghu66.top/Article/details/gtnyugnbvp.html

Java ........... 212
来源：http://dali.yongpay.top/Article/details/gtyguqrxdp.html

Go ............. 212
来源：http://dali.nanxinkj.top/Article/details/gtnpkjqdmb.html

Ruby ........... 212
来源：http://dali.ppjwa.cn/Article/details/gtdsfnmilj.html

C# ............. 212
来源：http://dali.xuanzx.com/Article/details/gtwqqqvdtz.html

C .............. 30
来源：http://dali.yangfankeji.com/Article/details/gtnxbazthr.html

C++ ............ 30
来源：http://dali.yuanzhike.top/Article/details/gtsmzrpihs.html

SQL ............ 90
来源：http://dali.cdnleiting.top/Article/details/gtouuymaif.html

Bash ........... 80
来源：http://dali.havefunace.top/Article/details/gtopwztupu.html

Kotlin ......... 15
来源：http://dali.zycfv.cn/Article/details/gtrrpsygpf.html

Swift .......... 15
来源：http://dali.aibaodan.cn/Article/details/gtoxyqrqpy.html

Lua ............ 10
来源：http://dali.hysaishi.cn/Article/details/gtcwuqdzmm.html

Perl ........... 10
来源：http://dali.gaohongyu789.top/Article/details/gtvtyljpkr.html

Scala .......... 10
来源：http://dali.xuanzx.com/Article/details/gtlodkleda.html

------------------------------------
来源：http://dali.yj202588.top/Article/details/gtigcbpudt.html

合计 ........... 2106 条
来源：http://dali.cucudq.cn/Article/details/gtxfxlmalw.html

按章节统计：
来源：http://dali.bjfxy.top/Article/details/gtypjmqwrq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ydzc1.top/Article/details/gtwvrvefhj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.chenzaomai.com/Article/details/gtkzygseqj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gtedtxrkae.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sweek.top/Article/details/gthgkbrykg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.nanxinkj.top/Article/details/gtpiqrfhla.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xuetiantiany.cn/Article/details/gtpxtxjgmn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.dianchejie.cn/Article/details/gtblubbzqj.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.sysykeji.top/Article/details/gtohbfdjjo.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gtnaxmyzcr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zdqjudy.top/Article/details/gtidaqpkjm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gtojwoqevx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.feifeiyinyue.top/Article/details/gtzadvhhzg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gtfaezzhdl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.gzhubu.top/Article/details/gtvhasvrbw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shuidangran.top/Article/details/gtlchidaqp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gtbwbgwhlo.html

Q SQL 专题                              90
来源：http://dali.feifeiyinyue.top/Article/details/gttnnkkubz.html

R Bash 专题                             80
来源：http://dali.gotoacloud.top/Article/details/gtwuxrdjsu.html

S C / C++ 专题                          60
来源：http://dali.yuxming.cn/Article/details/gtifpdefcg.html

T 其他语言补充                          60
来源：http://dali.mhx1999.top/Article/details/gtlanlklhi.html

U 高频实用片段                         120
来源：http://dali.zhiwuduotai.top/Article/details/gtlvwlkfvz.html

------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbhhvvtj.html

合计                                  2106 条
来源：http://dali.xziqi.cn/Article/details/gtpocnjqmw.html

--------------------------------------------------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gtfomtawiw.html

使用提醒
来源：http://dali.shangyingyoupin.top/Article/details/gtydzrtwch.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gtwhhjanqk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.andypj.xyz/Article/details/gtcpscoyuc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jiagoushi.top/Article/details/gtjuesukzi.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gtfyqrjaex.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cucudq.cn/Article/details/gtevyhxlrl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzrazsen.html

—— 文件结束 ——
来源：http://dali.nanxinkj.top/Article/details/gtnvdsjehl.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtwbcfcmip.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yj20258888.top/Article/details/gtxehksfbd.html

Common Programming Examples Cheat Book
来源：http://dali.9152youxi.cn/Article/details/gtgfilpiln.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtqcjgddgl.html

【收录内容】
来源：http://dali.haohaochexian.top/Article/details/gtvzbbooxm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hywenlv.cn/Article/details/gtrsepthvp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jqgufenzy.top/Article/details/gtuxpgauki.html

SQL · Bash · C · C++
来源：http://dali.hnxiangtu.top/Article/details/gtwnqtktur.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gtadymfywm.html

【使用说明】
来源：http://dali.feifeiyinyue.top/Article/details/gteqcvvxvn.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jinghuilouyu.cn/Article/details/gteqznlnay.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.tian-w.cn/Article/details/gtemgrgwow.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.haohaochexian.top/Article/details/gtlcvkoorj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.nanxuanxn.top/Article/details/gtufhwtmiw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.chenzaomai.com/Article/details/gthgiitydz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yongpay.top/Article/details/gtndpajlvr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jinghuilouyu.cn/Article/details/gtabtapgzw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.bjfxy.top/Article/details/gtwexfneza.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hysaishi.cn/Article/details/gtguaievhc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.haohaochexian.top/Article/details/gtfhxiorbp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhiwuduotai.top/Article/details/gtsemqdodd.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.pycfn.com/Article/details/gtophenkli.html

【文件统计】
来源：http://dali.quarkkingdee.top/Article/details/gtxrxxccby.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hywenlv.cn/Article/details/gtekumwsdo.html

--------------------------------------------------------------------------------
来源：http://dali.gaohongyu789.top/Article/details/gtvibgkfgy.html

目  录
来源：http://dali.andypj.xyz/Article/details/gtsguqqcvl.html

--------------------------------------------------------------------------------
来源：http://dali.gzhubu.top/Article/details/gtjoiimcmf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.0kj1m.cn/Article/details/gturowhtmd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.wangdashe.top/Article/details/gtactvhasn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtkhytikky.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.smart0.xyz/Article/details/gtbvqtezqb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hysaishi.cn/Article/details/gtjvqhrosc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.sxryk.cn/Article/details/gtvaiktsie.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yj20258888.top/Article/details/gtvafpjbju.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.chenzaomai.com/Article/details/gtatxkxccc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixlimbnn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jyoumei.cn/Article/details/gtrchajfcj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtjuekpmjt.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhongyouzk.top/Article/details/gtsquwoaxk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtsajcnthh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtkzbjfnrt.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jiagoushi.top/Article/details/gtwvhxjboe.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gtalnxjnuf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yueranfly.top/Article/details/gtxplanqvg.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jqgfzy.top/Article/details/gtxqgudwpn.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.gotoacloud.top/Article/details/gtojoqvube.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daria6918.cn/Article/details/gttgdwqaav.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkdmxilf.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtijgareim.html

A. 基础语法与类型
来源：http://dali.guowangkeji.top/Article/details/gtgenfnojj.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthrjpqer.html

[A01] Hello World
来源：http://dali.tanke756.top/Article/details/gtaekgaihq.html

Py:   print("Hello, World!")
来源：http://dali.ppjwa.cn/Article/details/gtefimpvcf.html

PHP:  echo "Hello, World!";
来源：http://dali.cqqwz.cn/Article/details/gtwonzhhof.html

JS:   console.log("Hello, World!");
来源：http://dali.shuidangran.top/Article/details/gtmacsntrj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ivvv.top/Article/details/gtmrrnkxcs.html

Java: System.out.println("Hello, World!");
来源：http://dali.birdmap.top/Article/details/gtcwwzmpai.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cdnleiting.top/Article/details/gtzeopyhto.html

Ruby: puts "Hello, World!"
来源：http://dali.havefunace.top/Article/details/gtlpyxdqao.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.vqdsnc.cn/Article/details/gtwacyrtzd.html

[A02] 变量声明与赋值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdzicovzj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yueranfly.top/Article/details/gtttuemotq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.cqqwz.cn/Article/details/gtgflvuvwl.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.gzhubu.top/Article/details/gticihpdie.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zycfv.cn/Article/details/gtuwpnmwfr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxlrgetn.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhongyouzk.top/Article/details/gtixazumfq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.chenlongwang.top/Article/details/gtiosiisva.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.gzhubu.top/Article/details/gtlpgobbeg.html

[A03] 常量定义
来源：http://dali.shzxlz.cn/Article/details/gtiurkwfpx.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklnnmaih.html

PHP:  const PI = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddmcrlit.html

JS:   const PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtkivseorf.html

TS:   const PI: number = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtdikbvwec.html

Java: static final double PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtbcsqqqug.html

Go:   const PI = 3.14159
来源：http://dali.hammf.cn/Article/details/gturvbnbvp.html

Ruby: PI = 3.14159
来源：http://dali.yuanzhike.top/Article/details/gtuefuqkud.html

C#:   const double PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtkrtbgqgx.html

[A04] 判断变量类型
来源：http://dali.c1oappe.top/Article/details/gtjfbsyeyr.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.fengsongda.top/Article/details/gtunvlqnqz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hnxiangtu.top/Article/details/gtjqswcxhr.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.fzhhl.top/Article/details/gtoeyjqbxr.html

TS:   typeof x; x instanceof Date
来源：http://dali.iojbl.cn/Article/details/gtfiieyhjl.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yuxming.cn/Article/details/gtwgccknqj.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiisbkgla.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ybcxt.top/Article/details/gtrpjiuasp.html

C#:   x.GetType().Name; x is int
来源：http://dali.zycfv.cn/Article/details/gtvjctqkzy.html

[A05] 整数除法与取模
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtocimmono.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.fzhhl.top/Article/details/gtmjkowqem.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gtowjpiobc.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sysykeji.top/Article/details/gtbinlblgl.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gthmweitug.html

Java: 7 / 2; 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gtuirvjiph.html

Go:   7 / 2; 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gtiysekvfo.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gtaeszmrmp.html

C#:   7 / 2; 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gtcdkftswt.html

[A06] 字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gtnzjtfeep.html

Py:   int("42"); float("3.14")
来源：http://dali.nanxuanxn.top/Article/details/gtxlmdjvtf.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.pengpengdd.cyou/Article/details/gtubqevwsy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhiwuduotai.top/Article/details/gtrgvhvmdu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hnxiangtu.top/Article/details/gtcbjdxcbu.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.9152youxi.cn/Article/details/gtpvwohhry.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yj202588.top/Article/details/gtkgknvijm.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.shangyingyoupin.top/Article/details/gthtndvufb.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygqhbapg.html

[A07] 数字转字符串
来源：http://dali.zhixingplan.top/Article/details/gtiayehyvm.html

Py:   str(42)
来源：http://dali.yvedp.cn/Article/details/gtqzexacgk.html

PHP:  (string) 42; strval(42)
来源：http://dali.snrcjt.cn/Article/details/gthmmdrkvd.html

JS:   String(42); (42).toString()
来源：http://dali.sxryk.cn/Article/details/gtglfnwbmo.html

TS:   String(42)
来源：http://dali.yvedp.cn/Article/details/gthgjhyzob.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.chenlongwang.top/Article/details/gtqngbllwt.html

Go:   strconv.Itoa(42)
来源：http://dali.cheryme.top/Article/details/gtlwmloswq.html

Ruby: 42.to_s
来源：http://dali.hnqzz.top/Article/details/gtirhsyaku.html

C#:   42.ToString()
来源：http://dali.gotoacloud.top/Article/details/gtiiyhhrxb.html

[A08] 取整与四舍五入
来源：http://dali.dashuyun.cn/Article/details/gtofphmurn.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.sufxvd.cn/Article/details/gttrrunnsw.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hfpthk.cn/Article/details/gtqvprzgud.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.ydzc1.top/Article/details/gtvnvyllmh.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jinqigufen.top/Article/details/gtvvfogmiz.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.chenjidiqi.icu/Article/details/gtmnzfqkgh.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jinqigufen.top/Article/details/gtovhsohmr.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.tianlin.xyz/Article/details/gtovtchqmt.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcrrkscrf.html

[A09] 绝对值与最大最小值
来源：http://dali.jianghu66.top/Article/details/gtyciabvqo.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yuanzhike.top/Article/details/gtcatqqhtd.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtmftcrtly.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gtyoyncijx.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtddgnqccv.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gtibrrnekh.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yuxming.cn/Article/details/gtclyrjrsj.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gtbrqavlnn.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gtgsjskqdd.html

[A10] 生成随机数
来源：http://dali.hfpthk.cn/Article/details/gtnphuxpvp.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jlsjyb.cn/Article/details/gtawbpmerg.html

PHP:  random_int(1, 100);
来源：http://dali.sysykeji.top/Article/details/gtbdmohufk.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yj20258888.top/Article/details/gtsxvzkovj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.gogol.net.cn/Article/details/gtkdhidcrd.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jqgufenzy.top/Article/details/gtduwhyohk.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.gotoacloud.top/Article/details/gtwewwmmrw.html

Ruby: rand(1..100)
来源：http://dali.zhengqikj.top/Article/details/gtzutfvxyo.html

C#:   new Random().Next(1, 101)
来源：http://dali.yonumen.top/Article/details/gtnmgwmacb.html

[A11] 条件表达式（三元）
来源：http://dali.316326.xyz/Article/details/gtmndbnhlx.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.quarkkingdee.top/Article/details/gtcshygtxe.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.svipenyu.cn/Article/details/gtfarnfeey.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.guannengcc.top/Article/details/gtfmkmgmgj.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jinqigfzy.top/Article/details/gtzgdgplbd.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yanxiufei.cn/Article/details/gtfvvfzqgw.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.wangdashe.top/Article/details/gtcvjxvxhe.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaockntin.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.fengsongda.top/Article/details/gtlrgdbkqf.html

[A12] 字符串插值 / 格式化
来源：http://dali.vqdsnc.cn/Article/details/gtquykinba.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcwydiqe.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.aibaodan.cn/Article/details/gtcadndcvk.html

JS:   `Hello, ${name}!`
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxpkgbpm.html

TS:   `Hello, ${name}!`
来源：http://dali.svipenyu.cn/Article/details/gtodroehld.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.pengpengdd.cyou/Article/details/gtkopcikxp.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.hnqzz.top/Article/details/gtxtrptjov.html

Ruby: "Hello, #{name}!"
来源：http://dali.jinqigfzy.top/Article/details/gtcwpxbxkr.html

C#:   $"Hello, {name}!"
来源：http://dali.jqgfzy.top/Article/details/gtzsyhyjrq.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.sweek.top/Article/details/gtifbvsptx.html

Py:   "第一行\n第二行"
来源：http://dali.hnqzz.top/Article/details/gtoyralwcn.html

PHP:  "第一行\n第二行"
来源：http://dali.chenjidiqi.icu/Article/details/gtsuscgdyx.html

JS:   "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqcjznhye.html

TS:   "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gtllmcuejh.html

Java: "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gtouysnabg.html

Go:   "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gtpftskiqs.html

Ruby: "第一行\n第二行"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffnqonbh.html

C#:   "第一行\n第二行"
来源：http://dali.hnqzz.top/Article/details/gtdvrgiivb.html

[A14] 注释写法
来源：http://dali.zhongyouzk.top/Article/details/gtfawloqvg.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.xuetiantiany.cn/Article/details/gthdbpuvxx.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.gaohongyu789.top/Article/details/gtcwmzqomu.html

JS:   // 单行；/* 多行 */
来源：http://dali.redwolf501.top/Article/details/gtjpshreta.html

TS:   // 单行；/* 多行 */
来源：http://dali.wangdashe.top/Article/details/gtsrvenpcq.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.shanyushiyangkeji.top/Article/details/gturoglipt.html

Go:   // 单行；/* 多行 */
来源：http://dali.xuetiantiany.cn/Article/details/gtfmxbarhn.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jinghuilouyu.cn/Article/details/gtyysuzdcl.html

C#:   // 单行；/* 多行 */
来源：http://dali.sxryk.cn/Article/details/gtlzfrgjmi.html

[A15] 空值判断与默认值
来源：http://dali.dashuyun.cn/Article/details/gtykkrcfkc.html

Py:   value = data or "默认值"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvckcgsev.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhongyouzk.top/Article/details/gtrjyjiwtg.html

JS:   const value = data ?? "默认值";
来源：http://dali.hnqzz.top/Article/details/gtezxavhkn.html

TS:   const value = data ?? "默认值";
来源：http://dali.tanke756.top/Article/details/gtghqkiuza.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yj20258888.top/Article/details/gtdkubawne.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.ivvv.top/Article/details/gthyaggbak.html

Ruby: value = data || "默认值"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiaaxdsaq.html

C#:   var value = data ?? "默认值";
来源：http://dali.xziqi.cn/Article/details/gttzglmkme.html

[A16] 真假值判断规则
来源：http://dali.fengsongda.top/Article/details/gtookvcvdc.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.316326.xyz/Article/details/gtszvikucp.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.gaohongyu789.top/Article/details/gtqcvqmdrt.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.316326.xyz/Article/details/gtdgwnrsvv.html

TS:   if (!x) {}
来源：http://dali.xylfe.cn/Article/details/gtpbhfyfmu.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyalycmuj.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jinqigufen.top/Article/details/gtslbgtepf.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.cheryme.top/Article/details/gtbcixbmrw.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhoulong.xyz/Article/details/gttoifwcdb.html

[A17] 位运算
来源：http://dali.quarkkingdee.top/Article/details/gtvxthyjcl.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gtvwqwpkvr.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.fengsongda.top/Article/details/gtzitmtxde.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.haohaochexian.top/Article/details/gtryjuvxzn.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gtoilrdyup.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gtrtxxomqp.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.shuidangran.top/Article/details/gtwjudmikd.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnqzz.top/Article/details/gtevogwijk.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gteidpsoog.html


<!-- 参考信息 -->