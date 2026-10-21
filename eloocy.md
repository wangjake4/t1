代发 wailian999

[U99] JS：事件监听
来源：http://dali.zhengqikj.top/Article/details/gtdtfjuuis.html

el.addEventListener("click", e => {})
来源：http://dali.vqdsnc.cn/Article/details/gtckokzvpa.html

[U100] JS：DOM 查询
来源：http://dali.ydzc1.top/Article/details/gthemtdpwh.html

document.querySelector(".item")
来源：http://dali.redwolf501.top/Article/details/gtqbpoeigz.html

[U101] JS：classList 操作
来源：http://dali.tanke756.top/Article/details/gtvxcfesfj.html

el.classList.toggle("active")
来源：http://dali.zdqjudy.top/Article/details/gttpyvdott.html

[U102] JS：本地存储
来源：http://dali.9152youxi.cn/Article/details/gtulvrojwh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhiwuduotai.top/Article/details/gtvnalmeky.html

[U103] JS：定时器
来源：http://dali.zdqjudy.top/Article/details/gttlviybmu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.daria6918.cn/Article/details/gthnpwzoej.html

[U104] JS：防抖
来源：http://dali.nanxuanxn.top/Article/details/gteqktpqqd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gtuwvumrhg.html

[U105] JS：节流
来源：http://dali.tian-w.cn/Article/details/gtzgqwbnpv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.wangdashe.top/Article/details/gtwfaofogx.html

[U106] JS：日期格式化
来源：http://dali.zhixingplan.top/Article/details/gtkmzlmcoq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.chenlongwang.top/Article/details/gtajxjhcni.html

[U107] JS：数字千分位
来源：http://dali.jiagoushi.top/Article/details/gtswyzykcr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gtpdiewgzk.html

[U108] JS：随机整数
来源：http://dali.hammf.cn/Article/details/gtnlzrsxqe.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hnqzz.top/Article/details/gttflsodrp.html

[U109] JS：数组分组
来源：http://dali.quarkkingdee.top/Article/details/gtifvctloy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.haohaochexian.top/Article/details/gtrqsgpssz.html

[U110] JS：数组分块
来源：http://dali.yanxiufei.cn/Article/details/gtdzxbwmqg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yuxming.cn/Article/details/gtxmptncda.html

[U111] JS：对象转 Map
来源：http://dali.xuetiantiany.cn/Article/details/gtmdoqnsgk.html

new Map(Object.entries(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gtdclxjkvn.html

[U112] JS：字符串补位
来源：http://dali.aizwys.cn/Article/details/gtiohjcnmc.html

"7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gtuwxcuila.html

[U113] JS：正则替换全部
来源：http://dali.yangfankeji.com/Article/details/gtsetejqns.html

s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtbuipxpqu.html

[U114] JS：JSON 深比较
来源：http://dali.sxryk.cn/Article/details/gtyzpszbbw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cdnleiting.top/Article/details/gtjwqpxryn.html

[U115] JS：生成 UUID
来源：http://dali.vqdsnc.cn/Article/details/gtugyndzrg.html

crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gtirpegimk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ehwqpu.com/Article/details/gteejxrvcl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.redwolf501.top/Article/details/gtjhvxwcdl.html

[U117] JS：单元测试
来源：http://dali.feifeiyinyue.top/Article/details/gtjzxrbxhw.html

npm i -D vitest;  npx vitest
来源：http://dali.jyoumei.cn/Article/details/gtnyurkpwc.html

[U118] JS：开发服务器
来源：http://dali.ydzc1.top/Article/details/gtrqnezlon.html

npm i -D vite;  npx vite
来源：http://dali.bjfxy.top/Article/details/gttghabubd.html

[U119] JS：生产构建
来源：http://dali.yangfankeji.com/Article/details/gtcipoylpb.html

npx vite build
来源：http://dali.daxiang520.top/Article/details/gtlmrtwxwd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.pengpengdd.cyou/Article/details/gtddvlasgf.html

import.meta.env.VITE_API_URL
来源：http://dali.fzhhl.top/Article/details/gtazgkonqd.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtqgudlyyg.html

统计汇总
来源：http://dali.jlsjyb.cn/Article/details/gtlwijufoq.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtwlibvqiw.html

按语言统计（条）：
来源：http://dali.jiagoushi.top/Article/details/gtubxhzkyk.html

Python ......... 252
来源：http://dali.yuanzhike.top/Article/details/gtkeoxniih.html

PHP ............ 252
来源：http://dali.xylfe.cn/Article/details/gtnxblejkk.html

JavaScript ..... 252
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwgrjjgs.html

TypeScript ..... 212
来源：http://dali.jianghu66.top/Article/details/gtjyxrybsf.html

Java ........... 212
来源：http://dali.ydzc1.top/Article/details/gtoqwqmywn.html

Go ............. 212
来源：http://dali.zhengqikj.top/Article/details/gtrumtwsjs.html

Ruby ........... 212
来源：http://dali.zycfv.cn/Article/details/gtkrlpdubj.html

C# ............. 212
来源：http://dali.iojbl.cn/Article/details/gtgzwxyust.html

C .............. 30
来源：http://dali.dianchejie.cn/Article/details/gtrjdxntul.html

C++ ............ 30
来源：http://dali.yueranfly.top/Article/details/gtgucqsvzn.html

SQL ............ 90
来源：http://dali.cheryme.top/Article/details/gtxfgyymul.html

Bash ........... 80
来源：http://dali.xziqi.cn/Article/details/gtgfpcqivy.html

Kotlin ......... 15
来源：http://dali.shzxlz.cn/Article/details/gttashojyb.html

Swift .......... 15
来源：http://dali.xylfe.cn/Article/details/gtlnddnxun.html

Lua ............ 10
来源：http://dali.316326.xyz/Article/details/gtvrwnuzhp.html

Perl ........... 10
来源：http://dali.hnxiangtu.top/Article/details/gtegqbgjjz.html

Scala .......... 10
来源：http://dali.ydzc1.top/Article/details/gtxsvoabpj.html

------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtzmnmefsz.html

合计 ........... 2106 条
来源：http://dali.shangyingyoupin.top/Article/details/gtgnnjekhu.html

按章节统计：
来源：http://dali.pengpengdd.cyou/Article/details/gtegwkbekn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbdocpkv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xuanzx.com/Article/details/gtwcccggdq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.birdmap.top/Article/details/gtlrylmnsn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zdqjudy.top/Article/details/gtpvtkrmll.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yj20258888.top/Article/details/gtmiyousyz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jqgfzy.top/Article/details/gtvirnpoqp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xinyue.icu/Article/details/gtmsjpwzrm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jianghu66.top/Article/details/gtgbhluham.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gtsnvcbdjv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hysaishi.cn/Article/details/gtfjetcocb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gtzffdlhjq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gtvkojrgzy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gtmhrcsrag.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.aizwys.cn/Article/details/gthctvadup.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yonumen.top/Article/details/gtgteipopx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gtdbluqiie.html

Q SQL 专题                              90
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbkzivxl.html

R Bash 专题                             80
来源：http://dali.cheryme.top/Article/details/gtvwjcxawc.html

S C / C++ 专题                          60
来源：http://dali.svipenyu.cn/Article/details/gtlscjydto.html

T 其他语言补充                          60
来源：http://dali.jlsjyb.cn/Article/details/gtlejfvkom.html

U 高频实用片段                         120
来源：http://dali.zhiwuduotai.top/Article/details/gtxpxxhmwz.html

------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gtiqyypkor.html

合计                                  2106 条
来源：http://dali.wangdashe.top/Article/details/gtmuxhhfko.html

--------------------------------------------------------------------------------
来源：http://dali.nwbrower.top/Article/details/gtqmpxjquz.html

使用提醒
来源：http://dali.vqdsnc.cn/Article/details/gtlbuepljl.html

--------------------------------------------------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gtvabhlqtz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.daxiang520.top/Article/details/gtmsixvupc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jianghu66.top/Article/details/gtcfciqcgt.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yj20258.top/Article/details/gtyruzlhgu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jiagoushi.top/Article/details/gtfcztdmqe.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzipoituf.html

—— 文件结束 ——
来源：http://dali.havefunace.top/Article/details/gtrwonxhhq.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtuvfpomhb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yvedp.cn/Article/details/gtptqpiikp.html

Common Programming Examples Cheat Book
来源：http://dali.zhiwuduotai.top/Article/details/gthqaoltfq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtloeavrpl.html

【收录内容】
来源：http://dali.yuxming.cn/Article/details/gtpcbucwqj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.tanke756.top/Article/details/gtyxwrgkif.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.aibaodan.cn/Article/details/gtdsvumwxl.html

SQL · Bash · C · C++
来源：http://dali.hfpthk.cn/Article/details/gtausbxvgf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.wangshuangyany.cn/Article/details/gtswvuoixy.html

【使用说明】
来源：http://dali.sxryk.cn/Article/details/gtknajsjai.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yj20258.top/Article/details/gtuikhzlyo.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ydzc1.top/Article/details/gtbfmmeowx.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.guowangkeji.top/Article/details/gtqsyuiicx.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.wangshuangyany.cn/Article/details/gtlmqtoyxt.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.sufxvd.cn/Article/details/gtqjcvuycd.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cqqwz.cn/Article/details/gtvexwaalw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.snrcjt.cn/Article/details/gtdiqzwrvw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xziqi.cn/Article/details/gtyntkmwje.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.c1oappe.top/Article/details/gtltkixcqv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cucudq.cn/Article/details/gtpsmoftfv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.guowangkeji.top/Article/details/gtprrkauzv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jqgufenzy.top/Article/details/gtmlzbusmi.html

【文件统计】
来源：http://dali.yueranfly.top/Article/details/gtjuztasct.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.nanxuanxn.top/Article/details/gttwdyhaob.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gtilsrwsuu.html

目  录
来源：http://dali.yj20258.top/Article/details/gthjupkgvd.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gtvywlnsdw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hnqzz.top/Article/details/gtjsxrlxsn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.dianchejie.cn/Article/details/gtmmfvqexv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbcrfpwp.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xuanzx.com/Article/details/gtjqddhmei.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.wangdashe.top/Article/details/gtyjrnuitj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jinqigfzy.top/Article/details/gtmfhvipon.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.gogol.net.cn/Article/details/gtagaznhbr.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhengqikj.top/Article/details/gtsalwrjfa.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gtmqrkanhg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.haohaochexian.top/Article/details/gtmkwmlijp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gtzpnvhewd.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yueranfly.top/Article/details/gtiiznvgvf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gtzlhlzhdv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.fengsongda.top/Article/details/gtiiwxlkuc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hammf.cn/Article/details/gtfggwlisx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.fengsongda.top/Article/details/gtyybpanjl.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.smart0.xyz/Article/details/gthjybslut.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.tanke756.top/Article/details/gtxidjmkhu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yongpay.top/Article/details/gteftohloq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.feifeiyinyue.top/Article/details/gtcvgnxuml.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jyoumei.cn/Article/details/gtfrdavopz.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtnacaewdd.html

A. 基础语法与类型
来源：http://dali.yj202588.top/Article/details/gtbhpdvypr.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtkaesxuum.html

[A01] Hello World
来源：http://dali.bjfxy.top/Article/details/gtdtoxfqtr.html

Py:   print("Hello, World!")
来源：http://dali.hysaishi.cn/Article/details/gtyadpkced.html

PHP:  echo "Hello, World!";
来源：http://dali.zdqjudy.top/Article/details/gtvymajmoh.html

JS:   console.log("Hello, World!");
来源：http://dali.gotoacloud.top/Article/details/gtlnhivrub.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.redwolf501.top/Article/details/gtovfmajei.html

Java: System.out.println("Hello, World!");
来源：http://dali.nanxinkj.top/Article/details/gttwghvxta.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.chenzaomai.com/Article/details/gtlwpchoqg.html

Ruby: puts "Hello, World!"
来源：http://dali.zycfv.cn/Article/details/gtgrranybp.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hfpthk.cn/Article/details/gttdywyqhi.html

[A02] 变量声明与赋值
来源：http://dali.0kj1m.cn/Article/details/gtvxbbrcqw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.vqdsnc.cn/Article/details/gtngxhecot.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.svipenyu.cn/Article/details/gtlfddsmgg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhongyouzk.top/Article/details/gtbeuaqgqs.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.guowangkeji.top/Article/details/gtnswvniby.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yvedp.cn/Article/details/gtfewswlbw.html

Go:   name := "Alex"; age := 20
来源：http://dali.cashguo.top/Article/details/gtntfamwzh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.iojbl.cn/Article/details/gtnsygdera.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yvedp.cn/Article/details/gtsizoyiux.html

[A03] 常量定义
来源：http://dali.guowangkeji.top/Article/details/gtgmbmuzzp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ppjwa.cn/Article/details/gtpsyrronh.html

PHP:  const PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtijbtcxur.html

JS:   const PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtjcjxpwql.html

TS:   const PI: number = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtraasfbjv.html

Java: static final double PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtdqdgijhw.html

Go:   const PI = 3.14159
来源：http://dali.aibaodan.cn/Article/details/gtjhranmnm.html

Ruby: PI = 3.14159
来源：http://dali.sweek.top/Article/details/gtfgsvmdla.html

C#:   const double PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtjfmpqwfw.html

[A04] 判断变量类型
来源：http://dali.cqqwz.cn/Article/details/gtwarljgva.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhongyouzk.top/Article/details/gtywmsdoxg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cashguo.top/Article/details/gthtachlgf.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.dianchejie.cn/Article/details/gtsysdmqbv.html

TS:   typeof x; x instanceof Date
来源：http://dali.ybcxt.top/Article/details/gtngsswxzx.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.smart0.xyz/Article/details/gtvybevxcy.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.daria6918.cn/Article/details/gtabixfxux.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.dianchejie.cn/Article/details/gtmvbzmyfp.html

C#:   x.GetType().Name; x is int
来源：http://dali.ydzc1.top/Article/details/gtkwtwixqt.html

[A05] 整数除法与取模
来源：http://dali.guannengcc.top/Article/details/gtrpkvylib.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jinqigfzy.top/Article/details/gtyyykqmvz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.birdmap.top/Article/details/gtdctrjpas.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gthzqercaj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtqtaycebt.html

Java: 7 / 2; 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtgidpvppp.html

Go:   7 / 2; 7 % 2
来源：http://dali.daria6918.cn/Article/details/gtxgsqdnju.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gtnflvzvvz.html

C#:   7 / 2; 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gtjydnphlc.html

[A06] 字符串转数字
来源：http://dali.iojbl.cn/Article/details/gtxhotiezf.html

Py:   int("42"); float("3.14")
来源：http://dali.shzxlz.cn/Article/details/gtwlbrkgwv.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.kuanghao11.cn/Article/details/gtgqdjculv.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.meibo888.top/Article/details/gtdsejyndy.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.nanxuanxn.top/Article/details/gtmoqpemen.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.ivvv.top/Article/details/gtyaxwyqqd.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.haohaochexian.top/Article/details/gtqdezousj.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.nanxuanxn.top/Article/details/gtqiiulekt.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.iojbl.cn/Article/details/gtpuoknlnn.html

[A07] 数字转字符串
来源：http://dali.sxryk.cn/Article/details/gtbqjuihgc.html

Py:   str(42)
来源：http://dali.fengsongda.top/Article/details/gtswbrvyds.html

PHP:  (string) 42; strval(42)
来源：http://dali.kuanghao11.cn/Article/details/gtoztbqjqp.html

JS:   String(42); (42).toString()
来源：http://dali.smart0.xyz/Article/details/gtqxovkilw.html

TS:   String(42)
来源：http://dali.jianghu66.top/Article/details/gtqvdxhvvj.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ybcxt.top/Article/details/gtlpblewpu.html

Go:   strconv.Itoa(42)
来源：http://dali.aibaodan.cn/Article/details/gtxpqemfka.html

Ruby: 42.to_s
来源：http://dali.xuanzx.com/Article/details/gtyafoxral.html

C#:   42.ToString()
来源：http://dali.xylfe.cn/Article/details/gthjuwgziv.html

[A08] 取整与四舍五入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpsfsbcjm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.pycfn.com/Article/details/gtdgunytwl.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.cashguo.top/Article/details/gtfkvghrct.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.redwolf501.top/Article/details/gtguepopqw.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.tian-w.cn/Article/details/gtbnckfuhv.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gtiamyivsb.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.sysykeji.top/Article/details/gtvpogtiwg.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.hammf.cn/Article/details/gtnkzkanlp.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.cashguo.top/Article/details/gtylrvkznj.html

[A09] 绝对值与最大最小值
来源：http://dali.gaohongyu789.top/Article/details/gtflwfliqn.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gtzrlxqzym.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtdkbqtvaq.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gtcbyzbtiy.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.daria6918.cn/Article/details/gtxfkurfsj.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.daxiang520.top/Article/details/gtpusbqifm.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhengqikj.top/Article/details/gtjhpxnigz.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.kuanghao11.cn/Article/details/gtbhmjalnl.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtwlbjibhr.html

[A10] 生成随机数
来源：http://dali.zhoulong.xyz/Article/details/gtjwueubsh.html

Py:   import random; random.randint(1, 100)
来源：http://dali.hysaishi.cn/Article/details/gtkflguzqx.html

PHP:  random_int(1, 100);
来源：http://dali.sysykeji.top/Article/details/gtbvsddwjl.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.fengsongda.top/Article/details/gtvtascqas.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jiagoushi.top/Article/details/gtbookcqai.html

Java: new Random().nextInt(100) + 1
来源：http://dali.xuanzx.com/Article/details/gtsfqinpmi.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpcbrmlb.html

Ruby: rand(1..100)
来源：http://dali.ehwqpu.com/Article/details/gtspnvijyj.html

C#:   new Random().Next(1, 101)
来源：http://dali.ivvv.top/Article/details/gtkytperff.html

[A11] 条件表达式（三元）
来源：http://dali.cucudq.cn/Article/details/gtscplkrsc.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.sweek.top/Article/details/gtpeupuojj.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hnqzz.top/Article/details/gtprsnvhqn.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhoulong.xyz/Article/details/gtrsmncbhv.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.guowangkeji.top/Article/details/gtmylzpbcj.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yanxiufei.cn/Article/details/gtttdvrkdu.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhengqikj.top/Article/details/gtznaqmnwe.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhiwuduotai.top/Article/details/gtduedaybv.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxesfjgzs.html

[A12] 字符串插值 / 格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtsbjbhdwa.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.feifeiyinyue.top/Article/details/gtydnbwegb.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yuanzhike.top/Article/details/gtbwrzjjcl.html

JS:   `Hello, ${name}!`
来源：http://dali.wangshuangyany.cn/Article/details/gtkcchhqyb.html

TS:   `Hello, ${name}!`
来源：http://dali.yj20258.top/Article/details/gtfzfiovjw.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.chenlongwang.top/Article/details/gtuyrzzkcl.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.snrcjt.cn/Article/details/gtqbbnweya.html

Ruby: "Hello, #{name}!"
来源：http://dali.andypj.xyz/Article/details/gtbcoyhfly.html

C#:   $"Hello, {name}!"
来源：http://dali.shanyushiyangtech.top/Article/details/gtagcnioyv.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.cashguo.top/Article/details/gtjhshnuzm.html

Py:   "第一行\n第二行"
来源：http://dali.shzxlz.cn/Article/details/gtpkpmxjrl.html

PHP:  "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gthzyqpsfn.html

JS:   "第一行\n第二行"
来源：http://dali.fzhhl.top/Article/details/gtzelnznza.html

TS:   "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gtbowakxqo.html

Java: "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gtavplepim.html

Go:   "第一行\n第二行"
来源：http://dali.shzxlz.cn/Article/details/gtgqrpbwmb.html

Ruby: "第一行\n第二行"
来源：http://dali.hnxiangtu.top/Article/details/gtfnrccmjx.html

C#:   "第一行\n第二行"
来源：http://dali.yj202588.top/Article/details/gtyxmluple.html

[A14] 注释写法
来源：http://dali.wangshuangyany.cn/Article/details/gtxhfktofg.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yj20258.top/Article/details/gtgqynfepe.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.xinyue.icu/Article/details/gtbnienauf.html

JS:   // 单行；/* 多行 */
来源：http://dali.cqqwz.cn/Article/details/gtrjeiutmk.html

TS:   // 单行；/* 多行 */
来源：http://dali.chenzaomai.com/Article/details/gtkahynvjy.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gtghwjuult.html

Go:   // 单行；/* 多行 */
来源：http://dali.mhx1999.top/Article/details/gtxqcabqce.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.xuetiantiany.cn/Article/details/gtpryykylh.html

C#:   // 单行；/* 多行 */
来源：http://dali.shuidangran.top/Article/details/gtkikndutn.html

[A15] 空值判断与默认值
来源：http://dali.sysykeji.top/Article/details/gtfbxdhawf.html

Py:   value = data or "默认值"
来源：http://dali.havefunace.top/Article/details/gtivgewtnt.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.hongshengwenyu.top/Article/details/gthxblgpba.html

JS:   const value = data ?? "默认值";
来源：http://dali.yj20258.top/Article/details/gtfcfhjfog.html

TS:   const value = data ?? "默认值";
来源：http://dali.hfpthk.cn/Article/details/gtrksnqgec.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.dianchejie.cn/Article/details/gtewytedxq.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqrvvrnt.html

Ruby: value = data || "默认值"
来源：http://dali.jinqigufen.top/Article/details/gtyfenhren.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhixingplan.top/Article/details/gtvtyceenj.html

[A16] 真假值判断规则
来源：http://dali.jyoumei.cn/Article/details/gtiyebajeg.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.cdnleiting.top/Article/details/gthzsfmygi.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yuanzhike.top/Article/details/gtiatgyyxm.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.sysykeji.top/Article/details/gtghizffdg.html

TS:   if (!x) {}
来源：http://dali.daxiang520.top/Article/details/gtqnmwgflj.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.smart0.xyz/Article/details/gtnjhvknwm.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.mhx1999.top/Article/details/gtdykfkshe.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yongpay.top/Article/details/gtdsgrfkdf.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtfeqkruir.html

[A17] 位运算
来源：http://dali.dianchejie.cn/Article/details/gtyzxkazkm.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jianghu66.top/Article/details/gtlnezlfbr.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.havefunace.top/Article/details/gtwbrtddjl.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujnkccne.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.hnqzz.top/Article/details/gtbrufcebd.html


<!-- 参考信息 -->