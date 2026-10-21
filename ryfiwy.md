代发 wailian999

[U101] JS：classList 操作
来源：http://dali.wangshuangyany.cn/Article/details/gtseynitph.html

el.classList.toggle("active")
来源：http://dali.mhx1999.top/Article/details/gtnhndayqr.html

[U102] JS：本地存储
来源：http://dali.zhoulong.xyz/Article/details/gtsvnrldul.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hysaishi.cn/Article/details/gtfpafnzef.html

[U103] JS：定时器
来源：http://dali.aibaodan.cn/Article/details/gtddpcdnbt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.andypj.xyz/Article/details/gtoauflpyw.html

[U104] JS：防抖
来源：http://dali.xinyue.icu/Article/details/gtkdyvvpdd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gtnujhoqho.html

[U105] JS：节流
来源：http://dali.gotoacloud.top/Article/details/gtnldvnsij.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jqgufenzy.top/Article/details/gtdknbpfol.html

[U106] JS：日期格式化
来源：http://dali.redwolf501.top/Article/details/gtuirypcvx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xinyue.icu/Article/details/gtyfftxkgg.html

[U107] JS：数字千分位
来源：http://dali.316326.xyz/Article/details/gtxmywtzvs.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbcvroqmh.html

[U108] JS：随机整数
来源：http://dali.xylfe.cn/Article/details/gtltjcbgrx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.guannengcc.top/Article/details/gtagetjjom.html

[U109] JS：数组分组
来源：http://dali.sweek.top/Article/details/gtoqulfzjc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ppjwa.cn/Article/details/gtpojwjqmb.html

[U110] JS：数组分块
来源：http://dali.shangyingyoupin.top/Article/details/gtpdghzvzy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yanxiufei.cn/Article/details/gtmmeczapn.html

[U111] JS：对象转 Map
来源：http://dali.sysykeji.top/Article/details/gtvsywozjj.html

new Map(Object.entries(obj))
来源：http://dali.yuxming.cn/Article/details/gtjdxkymef.html

[U112] JS：字符串补位
来源：http://dali.c1oappe.top/Article/details/gttkywxbra.html

"7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gttjbeqvmp.html

[U113] JS：正则替换全部
来源：http://dali.daxiang520.top/Article/details/gtoucdeiui.html

s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtzfvljvxx.html

[U114] JS：JSON 深比较
来源：http://dali.jqgufenzy.top/Article/details/gtzalvpuzj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gtpwsnqgpe.html

[U115] JS：生成 UUID
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkezbenz.html

crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtsmgcdsse.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.kuanghao11.cn/Article/details/gtnkfatwtc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.snrcjt.cn/Article/details/gtaqtuesde.html

[U117] JS：单元测试
来源：http://dali.cdnleiting.top/Article/details/gtchouqlud.html

npm i -D vitest;  npx vitest
来源：http://dali.cucudq.cn/Article/details/gtxmglhgyz.html

[U118] JS：开发服务器
来源：http://dali.yongpay.top/Article/details/gtaxvjfeuj.html

npm i -D vite;  npx vite
来源：http://dali.ivvv.top/Article/details/gtcrqaoten.html

[U119] JS：生产构建
来源：http://dali.hfpthk.cn/Article/details/gtmbajurrs.html

npx vite build
来源：http://dali.cqqwz.cn/Article/details/gtuusinmhf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhongyouzk.top/Article/details/gtmqhwasvb.html

import.meta.env.VITE_API_URL
来源：http://dali.xuanzx.com/Article/details/gtnsqceuux.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtyrwemcjq.html

统计汇总
来源：http://dali.cashguo.top/Article/details/gtyxmiilzn.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvwrkmbc.html

按语言统计（条）：
来源：http://dali.nanxuanxn.top/Article/details/gthiipdfio.html

Python ......... 252
来源：http://dali.jyoumei.cn/Article/details/gtgnlktqpy.html

PHP ............ 252
来源：http://dali.chenjidiqi.icu/Article/details/gttostvljh.html

JavaScript ..... 252
来源：http://dali.vqdsnc.cn/Article/details/gtbrpmlyob.html

TypeScript ..... 212
来源：http://dali.chenlongwang.top/Article/details/gttlsteydw.html

Java ........... 212
来源：http://dali.aibaodan.cn/Article/details/gtlkpftcbr.html

Go ............. 212
来源：http://dali.shzxlz.cn/Article/details/gtzrtqmyny.html

Ruby ........... 212
来源：http://dali.hfpthk.cn/Article/details/gtclfywfqh.html

C# ............. 212
来源：http://dali.guowangkeji.top/Article/details/gtdzgkjhnc.html

C .............. 30
来源：http://dali.zhengqikj.top/Article/details/gtaiewoeus.html

C++ ............ 30
来源：http://dali.smart0.xyz/Article/details/gthfmijljs.html

SQL ............ 90
来源：http://dali.zhixingplan.top/Article/details/gttycphmru.html

Bash ........... 80
来源：http://dali.316326.xyz/Article/details/gtvghsfpgr.html

Kotlin ......... 15
来源：http://dali.yvedp.cn/Article/details/gtdstpwftr.html

Swift .......... 15
来源：http://dali.zhengqikj.top/Article/details/gtfgwxwtfs.html

Lua ............ 10
来源：http://dali.cdnleiting.top/Article/details/gtoqmwayxq.html

Perl ........... 10
来源：http://dali.jinqigufen.top/Article/details/gtfdcruidb.html

Scala .......... 10
来源：http://dali.yonumen.top/Article/details/gtmawppolo.html

------------------------------------
来源：http://dali.ybcxt.top/Article/details/gtcpjlvlee.html

合计 ........... 2106 条
来源：http://dali.c1oappe.top/Article/details/gtpbsxnxrk.html

按章节统计：
来源：http://dali.chenjidiqi.icu/Article/details/gtvxnzcgzx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtuhpqhx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jlsjyb.cn/Article/details/gtgjeyantq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.vqdsnc.cn/Article/details/gtsijqjpfj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.9152youxi.cn/Article/details/gthxtlsbfj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hnxiangtu.top/Article/details/gtmuuxmxuw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yongpay.top/Article/details/gtbmmdouuu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbqxabqf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.sufxvd.cn/Article/details/gtvrhmwcgt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gtcafzkgky.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xinyue.icu/Article/details/gtmuboermo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gtxnakjbpd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gtunpkxvov.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.mhx1999.top/Article/details/gtirbhhxxw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yueranfly.top/Article/details/gtoxpjghlm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.daxiang520.top/Article/details/gtpscqbkty.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gtpxvyttce.html

Q SQL 专题                              90
来源：http://dali.hammf.cn/Article/details/gtzfxfqdir.html

R Bash 专题                             80
来源：http://dali.jinqigfzy.top/Article/details/gtxjoqqrya.html

S C / C++ 专题                          60
来源：http://dali.hongshengwenyu.top/Article/details/gtbttrrfck.html

T 其他语言补充                          60
来源：http://dali.yj202588.top/Article/details/gtwqvyrxws.html

U 高频实用片段                         120
来源：http://dali.mhx1999.top/Article/details/gtiqaojcof.html

------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gtrwusschf.html

合计                                  2106 条
来源：http://dali.yuanzhike.top/Article/details/gtjqkjprmi.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtpvgeopdy.html

使用提醒
来源：http://dali.bjfxy.top/Article/details/gtroeyqysn.html

--------------------------------------------------------------------------------
来源：http://dali.yj202588.top/Article/details/gtbqydneye.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xinyue.icu/Article/details/gtayvsylxc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.guannengcc.top/Article/details/gtchoczujn.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.dashuyun.cn/Article/details/gtzhqucylj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.redwolf501.top/Article/details/gtydzifpkd.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jqgfzy.top/Article/details/gtoruuotfc.html

—— 文件结束 ——
来源：http://dali.ppjwa.cn/Article/details/gtxxrvfvyx.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtuwekvmnq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.iojbl.cn/Article/details/gtksyvpjgj.html

Common Programming Examples Cheat Book
来源：http://dali.yongpay.top/Article/details/gtklswcxpz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtnyspzmtv.html

【收录内容】
来源：http://dali.gogol.net.cn/Article/details/gtijwtglxn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.9152youxi.cn/Article/details/gtlrfbozhg.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhoulong.xyz/Article/details/gtahrulmsn.html

SQL · Bash · C · C++
来源：http://dali.dashuyun.cn/Article/details/gtzlcbfjtv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jinqigufen.top/Article/details/gtftlybmbf.html

【使用说明】
来源：http://dali.pengpengdd.cyou/Article/details/gtgcvxnokn.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cashguo.top/Article/details/gtmbuiyucu.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xinyue.icu/Article/details/gtjvtqdmfr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.0kj1m.cn/Article/details/gthicheubk.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyynmbgy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.quarkkingdee.top/Article/details/gtyogekdon.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ppjwa.cn/Article/details/gtefnotyqn.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.c1oappe.top/Article/details/gthawuujlg.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yuanzhike.top/Article/details/gtobqtwcnn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yvedp.cn/Article/details/gtqccvtext.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yj20258.top/Article/details/gteelcipea.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jyoumei.cn/Article/details/gtmvaboxtm.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jinqigfzy.top/Article/details/gtfqeuutvc.html

【文件统计】
来源：http://dali.zhongyouzk.top/Article/details/gtchkckwch.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gogol.net.cn/Article/details/gtxpuyxlfz.html

--------------------------------------------------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtwbabqgum.html

目  录
来源：http://dali.yonumen.top/Article/details/gttbflblpt.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gtercfxluj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.sxryk.cn/Article/details/gtwjaxswbs.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.sufxvd.cn/Article/details/gtsaakkjma.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtesrgujcn.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hnqzz.top/Article/details/gtoozrsxzb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jyoumei.cn/Article/details/gtotzsgsen.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.bjfxy.top/Article/details/gtvpczakyr.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.tanke756.top/Article/details/gturwlcaih.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.meibo888.top/Article/details/gtbfplsozh.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gtupxxayvm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yvedp.cn/Article/details/gtguokskyd.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jiagoushi.top/Article/details/gtzvurzggc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gtluhlehup.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvlzhrhb.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.daxiang520.top/Article/details/gtboqcakpf.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hnxiangtu.top/Article/details/gtcrhbxsmx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.kuanghao11.cn/Article/details/gtduqxfzvp.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqwhayqa.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjownswus.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.cqqwz.cn/Article/details/gtlxafyqcv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.kuanghao11.cn/Article/details/gtxnimoybt.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sufxvd.cn/Article/details/gtlehrwupd.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtsdmqvvfx.html

A. 基础语法与类型
来源：http://dali.mhx1999.top/Article/details/gtyomkairz.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtevocrcqe.html

[A01] Hello World
来源：http://dali.xziqi.cn/Article/details/gtupfkughy.html

Py:   print("Hello, World!")
来源：http://dali.quarkkingdee.top/Article/details/gtbgkiortu.html

PHP:  echo "Hello, World!";
来源：http://dali.xuanzx.com/Article/details/gtvnilytuy.html

JS:   console.log("Hello, World!");
来源：http://dali.yuanzhike.top/Article/details/gtdubihlku.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.pengpengdd.cyou/Article/details/gtekoqales.html

Java: System.out.println("Hello, World!");
来源：http://dali.cashguo.top/Article/details/gtdzdodoip.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.fengsongda.top/Article/details/gtdefggbpv.html

Ruby: puts "Hello, World!"
来源：http://dali.guannengcc.top/Article/details/gtpmtdguzn.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ivvv.top/Article/details/gtclzezgni.html

[A02] 变量声明与赋值
来源：http://dali.jianghu66.top/Article/details/gtnvroaiop.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yj202588.top/Article/details/gtbtcviryt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.nanxuanxn.top/Article/details/gtzftkpzxg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.nwbrower.top/Article/details/gtartamsqk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yueranfly.top/Article/details/gtsbfpnacw.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.gotoacloud.top/Article/details/gtxdmmcrbq.html

Go:   name := "Alex"; age := 20
来源：http://dali.hongshengwenyu.top/Article/details/gtcesgmvqo.html

Ruby: name = "Alex"; age = 20
来源：http://dali.feifeiyinyue.top/Article/details/gtunndsufo.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.chenzaomai.com/Article/details/gthpqqhmcv.html

[A03] 常量定义
来源：http://dali.gogol.net.cn/Article/details/gtcmxepsaj.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jianghu66.top/Article/details/gtfrgeewma.html

PHP:  const PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtjbubbhdw.html

JS:   const PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtzamzfrmo.html

TS:   const PI: number = 3.14159;
来源：http://dali.316326.xyz/Article/details/gtjdvanwdm.html

Java: static final double PI = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtndlgmoyn.html

Go:   const PI = 3.14159
来源：http://dali.smart0.xyz/Article/details/gtohcwaabz.html

Ruby: PI = 3.14159
来源：http://dali.jinghuilouyu.cn/Article/details/gtexedvtth.html

C#:   const double PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtcgzwohzd.html

[A04] 判断变量类型
来源：http://dali.xuetiantiany.cn/Article/details/gtmeyqbndy.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.wangshuangyany.cn/Article/details/gtvfmmbbyv.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.sufxvd.cn/Article/details/gtpoieuqyh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.nanxuanxn.top/Article/details/gtbkcurgse.html

TS:   typeof x; x instanceof Date
来源：http://dali.cqqwz.cn/Article/details/gtzdbkwqmr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbnzxkcmp.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shzxlz.cn/Article/details/gtyrgxbzrj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yangfankeji.com/Article/details/gtyqstjxsa.html

C#:   x.GetType().Name; x is int
来源：http://dali.mhx1999.top/Article/details/gtiqckdsmu.html

[A05] 整数除法与取模
来源：http://dali.ydzc1.top/Article/details/gttkazllmk.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zdqjudy.top/Article/details/gtgwrszhex.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.havefunace.top/Article/details/gtncjlsvth.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gtywktcrys.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gtyvdxbmca.html

Java: 7 / 2; 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gtcxlunzhq.html

Go:   7 / 2; 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gtecybedta.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtqxfwtqbp.html

C#:   7 / 2; 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gtyudwjojk.html

[A06] 字符串转数字
来源：http://dali.zycfv.cn/Article/details/gtapkyjxkw.html

Py:   int("42"); float("3.14")
来源：http://dali.hysaishi.cn/Article/details/gtpwgnrviw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.xinyue.icu/Article/details/gtcxorlljh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hnxiangtu.top/Article/details/gtngakopnp.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.svipenyu.cn/Article/details/gtjpswapos.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.mhx1999.top/Article/details/gtodwqmoag.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.snrcjt.cn/Article/details/gtnsnhstjm.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.dashuyun.cn/Article/details/gtfjqtyjug.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.c1oappe.top/Article/details/gtxfeddotz.html

[A07] 数字转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtbhvdguot.html

Py:   str(42)
来源：http://dali.yj202588.top/Article/details/gtocmtpoai.html

PHP:  (string) 42; strval(42)
来源：http://dali.meibo888.top/Article/details/gtcgxlluih.html

JS:   String(42); (42).toString()
来源：http://dali.0kj1m.cn/Article/details/gtblcpouun.html

TS:   String(42)
来源：http://dali.dashuyun.cn/Article/details/gtgiunbdgg.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.xziqi.cn/Article/details/gtxibzccve.html

Go:   strconv.Itoa(42)
来源：http://dali.xuetiantiany.cn/Article/details/gtovmpmhyk.html

Ruby: 42.to_s
来源：http://dali.andypj.xyz/Article/details/gtdzaoebpb.html

C#:   42.ToString()
来源：http://dali.ybcxt.top/Article/details/gtdynpsnbp.html

[A08] 取整与四舍五入
来源：http://dali.jinqigufen.top/Article/details/gtfyxhlljs.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.sweek.top/Article/details/gtccnzspfr.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yonumen.top/Article/details/gtegomwvpu.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhengqikj.top/Article/details/gtfeibgsfr.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jqgfzy.top/Article/details/gtjdwpsxle.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.feifeiyinyue.top/Article/details/gtplvdfudb.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.gaohongyu789.top/Article/details/gtmhrzymdb.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.kuanghao11.cn/Article/details/gtahdnlvsy.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgfabdrdu.html

[A09] 绝对值与最大最小值
来源：http://dali.kuanghao11.cn/Article/details/gtvilbjzqm.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpljvrvr.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.tanke756.top/Article/details/gtiiutdqlq.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gttptlwvkg.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gtxnmjhqar.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gtxxfttcwr.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.9152youxi.cn/Article/details/gtajqgvngc.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.xylfe.cn/Article/details/gtykyqicpc.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yvedp.cn/Article/details/gtspuutkoi.html

[A10] 生成随机数
来源：http://dali.daxiang520.top/Article/details/gtybkglvbf.html

Py:   import random; random.randint(1, 100)
来源：http://dali.svipenyu.cn/Article/details/gtcckzwytx.html

PHP:  random_int(1, 100);
来源：http://dali.hongshengwenyu.top/Article/details/gtuirxjwqz.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.chenlongwang.top/Article/details/gtqienncjj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.tian-w.cn/Article/details/gtiizmgcje.html

Java: new Random().nextInt(100) + 1
来源：http://dali.hnqzz.top/Article/details/gtrzhlxdgj.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jinqigufen.top/Article/details/gtkzzflwql.html

Ruby: rand(1..100)
来源：http://dali.dashuyun.cn/Article/details/gtnehvymrx.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvqdlnvr.html

[A11] 条件表达式（三元）
来源：http://dali.tanke756.top/Article/details/gtlvkongqh.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.haohaochexian.top/Article/details/gtdiciomco.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yangfankeji.com/Article/details/gthlvmeqxl.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.wangdashe.top/Article/details/gtphwoshkw.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.ehwqpu.com/Article/details/gtfdegszua.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.gotoacloud.top/Article/details/gtiyqqujrw.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.cheryme.top/Article/details/gtbwkawirj.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.ydzc1.top/Article/details/gtlvqtdtbe.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.9152youxi.cn/Article/details/gtzvjjhluo.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpffvepl.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yonumen.top/Article/details/gteegqacxv.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.tanke756.top/Article/details/gtreoiinic.html

JS:   `Hello, ${name}!`
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiaqdfecz.html

TS:   `Hello, ${name}!`
来源：http://dali.jinqigfzy.top/Article/details/gtkxlldkib.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xziqi.cn/Article/details/gttpaoexmy.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.ydzc1.top/Article/details/gtihpelids.html

Ruby: "Hello, #{name}!"
来源：http://dali.wangdashe.top/Article/details/gtbylfuzsb.html

C#:   $"Hello, {name}!"
来源：http://dali.xziqi.cn/Article/details/gtysmocyyi.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.ydzc1.top/Article/details/gtqwypjkwe.html

Py:   "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gtkeqedvup.html

PHP:  "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gtaaqawyjk.html

JS:   "第一行\n第二行"
来源：http://dali.shanyushiyangtech.top/Article/details/gtzyqpylcn.html

TS:   "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gtwbmaotoh.html

Java: "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gtngirnayt.html

Go:   "第一行\n第二行"
来源：http://dali.yj202588.top/Article/details/gtweyvdzpa.html

Ruby: "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gtielanucj.html

C#:   "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gtkyzuznua.html

[A14] 注释写法
来源：http://dali.cqqwz.cn/Article/details/gtatdazhbr.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jyoumei.cn/Article/details/gtgokwzcjv.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.pycfn.com/Article/details/gtrztsauwd.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrxiqsym.html

TS:   // 单行；/* 多行 */
来源：http://dali.zdqjudy.top/Article/details/gtpbqpktjx.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hammf.cn/Article/details/gtxyuflgnl.html

Go:   // 单行；/* 多行 */
来源：http://dali.andypj.xyz/Article/details/gtijpdqjwa.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.xuanzx.com/Article/details/gtzwtmiglp.html

C#:   // 单行；/* 多行 */
来源：http://dali.svipenyu.cn/Article/details/gtvlagiamu.html

[A15] 空值判断与默认值
来源：http://dali.yangfankeji.com/Article/details/gtggbzjhzv.html

Py:   value = data or "默认值"
来源：http://dali.aibaodan.cn/Article/details/gtycyttsga.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.aibaodan.cn/Article/details/gtqfencgfd.html

JS:   const value = data ?? "默认值";
来源：http://dali.hongshengwenyu.top/Article/details/gtcpzenfeh.html

TS:   const value = data ?? "默认值";
来源：http://dali.nwbrower.top/Article/details/gtrlajrctc.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yonumen.top/Article/details/gtacigvdvq.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.dashuyun.cn/Article/details/gtjclubghm.html

Ruby: value = data || "默认值"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcneeinzf.html

C#:   var value = data ?? "默认值";
来源：http://dali.chenlongwang.top/Article/details/gtazypesrf.html

[A16] 真假值判断规则
来源：http://dali.zycfv.cn/Article/details/gtewixukgm.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zdqjudy.top/Article/details/gtywqxkivl.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yongpay.top/Article/details/gtqqlhpqwb.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yuanzhike.top/Article/details/gtdgvyzuin.html

TS:   if (!x) {}
来源：http://dali.guannengcc.top/Article/details/gtieecfaea.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.dashuyun.cn/Article/details/gtkggcppmi.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.pengpengdd.cyou/Article/details/gtifrqwxbs.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.cdnleiting.top/Article/details/gtxjtjduqn.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.dianchejie.cn/Article/details/gtyvcfigop.html

[A17] 位运算
来源：http://dali.svipenyu.cn/Article/details/gtsnybhqjp.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtcnnikxji.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.guowangkeji.top/Article/details/gtxfykbgru.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.andypj.xyz/Article/details/gtvzxuxken.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.gzhubu.top/Article/details/gtrwoepmiw.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gtzrvuoibe.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gtxljtrcks.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvmiqqzq.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guannengcc.top/Article/details/gtdtbwklzq.html


<!-- 参考信息 -->