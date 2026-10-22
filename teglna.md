代发 wailian999

[U99] JS：事件监听
来源：http://dali.dianchejie.cn/Article/details/gtyhvorkoa.html

el.addEventListener("click", e => {})
来源：http://dali.hongshengwenyu.top/Article/details/gtsckexuju.html

[U100] JS：DOM 查询
来源：http://dali.nwbrower.top/Article/details/gtyekatjvw.html

document.querySelector(".item")
来源：http://dali.snrcjt.cn/Article/details/gtfwyoatbd.html

[U101] JS：classList 操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvvupoue.html

el.classList.toggle("active")
来源：http://dali.yj202588.top/Article/details/gtbvweknrd.html

[U102] JS：本地存储
来源：http://dali.zhongyouzk.top/Article/details/gtttrsljvm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sufxvd.cn/Article/details/gtbpnnglzd.html

[U103] JS：定时器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxbxsadf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.chenzaomai.com/Article/details/gtwxmhjujb.html

[U104] JS：防抖
来源：http://dali.smart0.xyz/Article/details/gtloovsthz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gtezwaillb.html

[U105] JS：节流
来源：http://dali.zhoulong.xyz/Article/details/gtgojigagp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gzhubu.top/Article/details/gtphvzlneg.html

[U106] JS：日期格式化
来源：http://dali.xuanzx.com/Article/details/gthvdzcgxh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.sufxvd.cn/Article/details/gtispdxtoa.html

[U107] JS：数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gtafvtoqnb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.iojbl.cn/Article/details/gtvfnaarju.html

[U108] JS：随机整数
来源：http://dali.gotoacloud.top/Article/details/gtpiugzzlf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.0kj1m.cn/Article/details/gtbwnxrwaw.html

[U109] JS：数组分组
来源：http://dali.c1oappe.top/Article/details/gtvlstsxtu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258888.top/Article/details/gtbqhkhjsq.html

[U110] JS：数组分块
来源：http://dali.andypj.xyz/Article/details/gttnoxrvnq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cqqwz.cn/Article/details/gtaprrrdle.html

[U111] JS：对象转 Map
来源：http://dali.9152youxi.cn/Article/details/gtsbpbfdnq.html

new Map(Object.entries(obj))
来源：http://dali.pengpengdd.cyou/Article/details/gtkvqzbdon.html

[U112] JS：字符串补位
来源：http://dali.yj20258.top/Article/details/gtucakfujt.html

"7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwndyqcb.html

[U113] JS：正则替换全部
来源：http://dali.cheryme.top/Article/details/gtngywbytg.html

s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitnsfiyi.html

[U114] JS：JSON 深比较
来源：http://dali.havefunace.top/Article/details/gtqkenosci.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guowangkeji.top/Article/details/gtfpiodtdu.html

[U115] JS：生成 UUID
来源：http://dali.sufxvd.cn/Article/details/gtyudamibh.html

crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gtuhhutukr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jiagoushi.top/Article/details/gtaduwfzqj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.wangdashe.top/Article/details/gtpsuabhrh.html

[U117] JS：单元测试
来源：http://dali.jqgfzy.top/Article/details/gtdrvrybcg.html

npm i -D vitest;  npx vitest
来源：http://dali.hfpthk.cn/Article/details/gtjsiusivf.html

[U118] JS：开发服务器
来源：http://dali.gzhubu.top/Article/details/gtcekwrvru.html

npm i -D vite;  npx vite
来源：http://dali.yj20258.top/Article/details/gtmspzsjor.html

[U119] JS：生产构建
来源：http://dali.cqqwz.cn/Article/details/gtuwaieqyo.html

npx vite build
来源：http://dali.hongshengwenyu.top/Article/details/gtxdgnojxn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gotoacloud.top/Article/details/gtshyctnnv.html

import.meta.env.VITE_API_URL
来源：http://dali.zycfv.cn/Article/details/gtezgpzbvc.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtqfjouzrw.html

统计汇总
来源：http://dali.tianlin.xyz/Article/details/gtyxmmlklo.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtrtakdlkg.html

按语言统计（条）：
来源：http://dali.hnqzz.top/Article/details/gterovloqv.html

Python ......... 252
来源：http://dali.ppjwa.cn/Article/details/gtqrfmsrwy.html

PHP ............ 252
来源：http://dali.9152youxi.cn/Article/details/gtcmvwlttt.html

JavaScript ..... 252
来源：http://dali.zhixingplan.top/Article/details/gtjxhgeumz.html

TypeScript ..... 212
来源：http://dali.dianchejie.cn/Article/details/gttjtovjlp.html

Java ........... 212
来源：http://dali.shangyingyoupin.top/Article/details/gtwmisrore.html

Go ............. 212
来源：http://dali.dianchejie.cn/Article/details/gtrbawsswf.html

Ruby ........... 212
来源：http://dali.hammf.cn/Article/details/gtytswdbif.html

C# ............. 212
来源：http://dali.yj20258.top/Article/details/gtbhoajdec.html

C .............. 30
来源：http://dali.chenlongwang.top/Article/details/gtxfnffdqb.html

C++ ............ 30
来源：http://dali.yj20258888.top/Article/details/gtpmspqoam.html

SQL ............ 90
来源：http://dali.sweek.top/Article/details/gtwmormmmu.html

Bash ........... 80
来源：http://dali.cdnleiting.top/Article/details/gtttsnkkcx.html

Kotlin ......... 15
来源：http://dali.yj20258.top/Article/details/gtkqpxsedu.html

Swift .......... 15
来源：http://dali.gzhubu.top/Article/details/gtockzvfqc.html

Lua ............ 10
来源：http://dali.gzhubu.top/Article/details/gtismwipnn.html

Perl ........... 10
来源：http://dali.shuidangran.top/Article/details/gtuurhnjkt.html

Scala .......... 10
来源：http://dali.hongshengwenyu.top/Article/details/gtlwmcxrpm.html

------------------------------------
来源：http://dali.sweek.top/Article/details/gtssokjnts.html

合计 ........... 2106 条
来源：http://dali.guowangkeji.top/Article/details/gtzcqrzilb.html

按章节统计：
来源：http://dali.mhx1999.top/Article/details/gtylogtyhu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.guannengcc.top/Article/details/gttgewpdxp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhengqikj.top/Article/details/gtaokvgqje.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cqqwz.cn/Article/details/gtcthonvrw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.redwolf501.top/Article/details/gtkbzlnbkk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zycfv.cn/Article/details/gtcmtqehxo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhongyouzk.top/Article/details/gtjunpfgjs.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.svipenyu.cn/Article/details/gtlaplkeqg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yvedp.cn/Article/details/gtteuueifx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gtlqqblmnz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkruuyity.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gthekiefxq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzecdaxy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gtwyyegodh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yongpay.top/Article/details/gtcyeqkhze.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hammf.cn/Article/details/gtsllpsmhs.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gtxqlfpscn.html

Q SQL 专题                              90
来源：http://dali.sweek.top/Article/details/gtwisfwlws.html

R Bash 专题                             80
来源：http://dali.cheryme.top/Article/details/gtpktxjxty.html

S C / C++ 专题                          60
来源：http://dali.xuetiantiany.cn/Article/details/gtgmuwuizp.html

T 其他语言补充                          60
来源：http://dali.xuetiantiany.cn/Article/details/gtbtuqrkta.html

U 高频实用片段                         120
来源：http://dali.quarkkingdee.top/Article/details/gtbluvbtki.html

------------------------------------
来源：http://dali.havefunace.top/Article/details/gtkqeatsbo.html

合计                                  2106 条
来源：http://dali.havefunace.top/Article/details/gtnuonnlnb.html

--------------------------------------------------------------------------------
来源：http://dali.cucudq.cn/Article/details/gthjxpkrqh.html

使用提醒
来源：http://dali.zycfv.cn/Article/details/gtozmcjcgd.html

--------------------------------------------------------------------------------
来源：http://dali.ybcxt.top/Article/details/gtfxeascwi.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jinqigfzy.top/Article/details/gtvjaeqnlg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.mhx1999.top/Article/details/gtulllgcaw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.quarkkingdee.top/Article/details/gtuaspzjnh.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jqgfzy.top/Article/details/gtljvlnmyv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.smart0.xyz/Article/details/gtsagojhpz.html

—— 文件结束 ——
来源：http://dali.cdnleiting.top/Article/details/gtcauptmsk.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtovvuvkbh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ehwqpu.com/Article/details/gtbwqtsewv.html

Common Programming Examples Cheat Book
来源：http://dali.zhiwuduotai.top/Article/details/gtjirljwtj.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gttqgjoycb.html

【收录内容】
来源：http://dali.gaohongyu789.top/Article/details/gthccbkxxc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.andypj.xyz/Article/details/gtqcridnbn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.guowangkeji.top/Article/details/gtxgupfmpy.html

SQL · Bash · C · C++
来源：http://dali.mhx1999.top/Article/details/gtnxavsukx.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.shangyingyoupin.top/Article/details/gthkgtvuke.html

【使用说明】
来源：http://dali.guannengcc.top/Article/details/gtveykzsjp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yj20258.top/Article/details/gtpkvzswns.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinqigufen.top/Article/details/gtmcqjpyre.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.dashuyun.cn/Article/details/gtlduxxyhp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.svipenyu.cn/Article/details/gtqpaetfek.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.redwolf501.top/Article/details/gtztxscwiu.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.quarkkingdee.top/Article/details/gttwmyyljy.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.shuidangran.top/Article/details/gtcvuuhwcp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.nanxuanxn.top/Article/details/gthbrqfpix.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shanyushiyangtech.top/Article/details/gtieppaava.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.svipenyu.cn/Article/details/gtbrwafugs.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jqgfzy.top/Article/details/gtemnvwrgu.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.aibaodan.cn/Article/details/gtdhffxawn.html

【文件统计】
来源：http://dali.yj202588.top/Article/details/gtgyjpiniz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhiwuduotai.top/Article/details/gtxjevdjcg.html

--------------------------------------------------------------------------------
来源：http://dali.xinyue.icu/Article/details/gthiqvoaso.html

目  录
来源：http://dali.redwolf501.top/Article/details/gttbyvzhvb.html

--------------------------------------------------------------------------------
来源：http://dali.316326.xyz/Article/details/gtbteesxrt.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yuanzhike.top/Article/details/gtfvfesyrp.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtlxkllirb.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.dianchejie.cn/Article/details/gtjevdiomp.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtsppmxfbm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.c1oappe.top/Article/details/gtkhxqrojn.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.wangdashe.top/Article/details/gtnapongaf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yongpay.top/Article/details/gttokfoxnz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.gogol.net.cn/Article/details/gteagaxoel.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gtoxfqruht.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.gogol.net.cn/Article/details/gtkmpnqegr.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtyuzodqrl.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhengqikj.top/Article/details/gtmxxgjfne.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hysaishi.cn/Article/details/gtchzgtuob.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtxvdzjiqj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hysaishi.cn/Article/details/gtytbcaito.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbjfvajw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.gzhubu.top/Article/details/gtcevfhtwk.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.0kj1m.cn/Article/details/gtdhtzfznr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqxmwhgw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.redwolf501.top/Article/details/gtlsycohft.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.shzxlz.cn/Article/details/gtyeondvmi.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtyitznpdg.html

A. 基础语法与类型
来源：http://dali.redwolf501.top/Article/details/gtpijwekrl.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtysqiwcmy.html

[A01] Hello World
来源：http://dali.yangfankeji.com/Article/details/gtnqlmbuzl.html

Py:   print("Hello, World!")
来源：http://dali.tian-w.cn/Article/details/gtkipwojoy.html

PHP:  echo "Hello, World!";
来源：http://dali.jqgfzy.top/Article/details/gtuiclauni.html

JS:   console.log("Hello, World!");
来源：http://dali.yj202588.top/Article/details/gteyeebeid.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hammf.cn/Article/details/gtbolitvqp.html

Java: System.out.println("Hello, World!");
来源：http://dali.wangshuangyany.cn/Article/details/gtcoswncgu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hongshengwenyu.top/Article/details/gtwwojajqt.html

Ruby: puts "Hello, World!"
来源：http://dali.mhx1999.top/Article/details/gtjzbhzzjy.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.nanxuanxn.top/Article/details/gttkmnhenh.html

[A02] 变量声明与赋值
来源：http://dali.meibo888.top/Article/details/gtnpesivyi.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cqqwz.cn/Article/details/gtncmojebw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.wangdashe.top/Article/details/gtwbwppivs.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.sysykeji.top/Article/details/gtvmcfcwjc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.shuidangran.top/Article/details/gtupacmyca.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yj202588.top/Article/details/gtmdbuejkp.html

Go:   name := "Alex"; age := 20
来源：http://dali.yangfankeji.com/Article/details/gtroeqcvfw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hnqzz.top/Article/details/gtehhodmee.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ydzc1.top/Article/details/gtykgdcauu.html

[A03] 常量定义
来源：http://dali.xuanzx.com/Article/details/gtvrejyiwy.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jqgfzy.top/Article/details/gtejqjgjcw.html

PHP:  const PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtnezjuuqo.html

JS:   const PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtlstbqoml.html

TS:   const PI: number = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtduasglur.html

Java: static final double PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtnoryzeuw.html

Go:   const PI = 3.14159
来源：http://dali.pycfn.com/Article/details/gtoyzrchkb.html

Ruby: PI = 3.14159
来源：http://dali.hnqzz.top/Article/details/gtldqbxpdu.html

C#:   const double PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtspebayfn.html

[A04] 判断变量类型
来源：http://dali.shangyingyoupin.top/Article/details/gtdwbgenul.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.vqdsnc.cn/Article/details/gtmcgkgscw.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hnqzz.top/Article/details/gtkeqztpat.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyeltukbm.html

TS:   typeof x; x instanceof Date
来源：http://dali.hfpthk.cn/Article/details/gtdgvqrgyo.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.nwbrower.top/Article/details/gtndnnihua.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.chenzaomai.com/Article/details/gtnwmgjdjx.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhongyouzk.top/Article/details/gtvpgysjkc.html

C#:   x.GetType().Name; x is int
来源：http://dali.snrcjt.cn/Article/details/gtvaeqihrl.html

[A05] 整数除法与取模
来源：http://dali.jyoumei.cn/Article/details/gtsmervasr.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.feifeiyinyue.top/Article/details/gtuvysxzcr.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.daxiang520.top/Article/details/gtkodifpkv.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.haohaochexian.top/Article/details/gtqhhjcxuk.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gtvxhzansv.html

Java: 7 / 2; 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gtcjmesggu.html

Go:   7 / 2; 7 % 2
来源：http://dali.jianghu66.top/Article/details/gtunprabcg.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gtrowllrxb.html

C#:   7 / 2; 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtrzemnodo.html

[A06] 字符串转数字
来源：http://dali.jqgufenzy.top/Article/details/gtiwkmylbl.html

Py:   int("42"); float("3.14")
来源：http://dali.xylfe.cn/Article/details/gtkbitwqcf.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhongyouzk.top/Article/details/gtnpjoszjc.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jlsjyb.cn/Article/details/gtxqxtcbka.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhengqikj.top/Article/details/gtbfymwqgn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhiwuduotai.top/Article/details/gtujhzvrgf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.chenjidiqi.icu/Article/details/gtdpciwgsu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.meibo888.top/Article/details/gtsfjgwtez.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.316326.xyz/Article/details/gtioikocaa.html

[A07] 数字转字符串
来源：http://dali.gogol.net.cn/Article/details/gtwjbohmcd.html

Py:   str(42)
来源：http://dali.zhengqikj.top/Article/details/gtevlhzssx.html

PHP:  (string) 42; strval(42)
来源：http://dali.xziqi.cn/Article/details/gtkfriehbh.html

JS:   String(42); (42).toString()
来源：http://dali.0kj1m.cn/Article/details/gtemervlqh.html

TS:   String(42)
来源：http://dali.zycfv.cn/Article/details/gtkzidtgzl.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yj20258888.top/Article/details/gtnblzgqtc.html

Go:   strconv.Itoa(42)
来源：http://dali.zdqjudy.top/Article/details/gtroqdsznh.html

Ruby: 42.to_s
来源：http://dali.xinyue.icu/Article/details/gtherifhvy.html

C#:   42.ToString()
来源：http://dali.hnxiangtu.top/Article/details/gtwftvhulc.html

[A08] 取整与四舍五入
来源：http://dali.cqqwz.cn/Article/details/gtauxbatcw.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.daxiang520.top/Article/details/gtxcthkujx.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hnxiangtu.top/Article/details/gtarxmjoyw.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.shuidangran.top/Article/details/gtbeklqrqy.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yuanzhike.top/Article/details/gtinasbxpg.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.xinyue.icu/Article/details/gtigatzzym.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.shzxlz.cn/Article/details/gtvyebvdpt.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.chenzaomai.com/Article/details/gtqxscscgv.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ybcxt.top/Article/details/gtssinolwi.html

[A09] 绝对值与最大最小值
来源：http://dali.tanke756.top/Article/details/gtbnqentln.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtdybnsani.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtnhuzfbph.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.sweek.top/Article/details/gthkjcjmcz.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtrrwpzgeg.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtfwkuuodv.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.cqqwz.cn/Article/details/gtoqfolycm.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zdqjudy.top/Article/details/gtvwmlsgsl.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.tian-w.cn/Article/details/gtdhlxbkla.html

[A10] 生成随机数
来源：http://dali.yj20258888.top/Article/details/gtqoaimmsm.html

Py:   import random; random.randint(1, 100)
来源：http://dali.sufxvd.cn/Article/details/gtygmaywci.html

PHP:  random_int(1, 100);
来源：http://dali.sufxvd.cn/Article/details/gtnfnfsvnl.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.pengpengdd.cyou/Article/details/gtliqjlwoq.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xylfe.cn/Article/details/gthbaadqtv.html

Java: new Random().nextInt(100) + 1
来源：http://dali.9152youxi.cn/Article/details/gtkomragku.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yuanzhike.top/Article/details/gtuevrjgta.html

Ruby: rand(1..100)
来源：http://dali.gotoacloud.top/Article/details/gtskixejmb.html

C#:   new Random().Next(1, 101)
来源：http://dali.shanyushiyangtech.top/Article/details/gtugwnhnui.html

[A11] 条件表达式（三元）
来源：http://dali.cashguo.top/Article/details/gtekbufplw.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.fengsongda.top/Article/details/gtokyjpryn.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yuxming.cn/Article/details/gtgjmcelfj.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yvedp.cn/Article/details/gtyoneqoea.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jinqigfzy.top/Article/details/gtawygurzl.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.ehwqpu.com/Article/details/gtxgrukwsp.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqyddngzu.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttsltimki.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.wangshuangyany.cn/Article/details/gtbuhxkorx.html

[A12] 字符串插值 / 格式化
来源：http://dali.havefunace.top/Article/details/gtajuzholf.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.cheryme.top/Article/details/gtiroobsxc.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jinqigufen.top/Article/details/gtkkjpgkzl.html

JS:   `Hello, ${name}!`
来源：http://dali.cheryme.top/Article/details/gtrntngkiz.html

TS:   `Hello, ${name}!`
来源：http://dali.havefunace.top/Article/details/gtbiokllnt.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xziqi.cn/Article/details/gtghqvwefs.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvqmzzyr.html

Ruby: "Hello, #{name}!"
来源：http://dali.quarkkingdee.top/Article/details/gtcisypozt.html

C#:   $"Hello, {name}!"
来源：http://dali.0kj1m.cn/Article/details/gtkefjhfsa.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiiycbsoh.html

Py:   "第一行\n第二行"
来源：http://dali.birdmap.top/Article/details/gtexekuyez.html

PHP:  "第一行\n第二行"
来源：http://dali.yvedp.cn/Article/details/gtosekdtgh.html

JS:   "第一行\n第二行"
来源：http://dali.tianlin.xyz/Article/details/gtojfpadbo.html

TS:   "第一行\n第二行"
来源：http://dali.ybcxt.top/Article/details/gtzmopkrrq.html

Java: "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gtwwbcgsbz.html

Go:   "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gtarqfdebh.html

Ruby: "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gtrbahypil.html

C#:   "第一行\n第二行"
来源：http://dali.yvedp.cn/Article/details/gtybdlixor.html

[A14] 注释写法
来源：http://dali.birdmap.top/Article/details/gtwtwghepi.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhixingplan.top/Article/details/gtlfhhyhjc.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.smart0.xyz/Article/details/gtwghtzwml.html

JS:   // 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gtfjoahmqz.html

TS:   // 单行；/* 多行 */
来源：http://dali.hammf.cn/Article/details/gtvrietbkl.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zycfv.cn/Article/details/gtwurylaan.html

Go:   // 单行；/* 多行 */
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcigvpyfi.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.aizwys.cn/Article/details/gtabzdozdd.html

C#:   // 单行；/* 多行 */
来源：http://dali.yanxiufei.cn/Article/details/gtzsxvyaaj.html

[A15] 空值判断与默认值
来源：http://dali.gaohongyu789.top/Article/details/gtcadvgeim.html

Py:   value = data or "默认值"
来源：http://dali.0kj1m.cn/Article/details/gtukscduwt.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.cucudq.cn/Article/details/gtcrxwineh.html

JS:   const value = data ?? "默认值";
来源：http://dali.haohaochexian.top/Article/details/gtbjmtiuyx.html

TS:   const value = data ?? "默认值";
来源：http://dali.sxryk.cn/Article/details/gtlfngqlrl.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.xuetiantiany.cn/Article/details/gtajmpvhay.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.hysaishi.cn/Article/details/gtbawcahno.html

Ruby: value = data || "默认值"
来源：http://dali.zhengqikj.top/Article/details/gtocjuoxko.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbtnckia.html

[A16] 真假值判断规则
来源：http://dali.yanxiufei.cn/Article/details/gthkaszxbq.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.cheryme.top/Article/details/gtwbvwlgus.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.pycfn.com/Article/details/gtnvhxjwpd.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfmhrduk.html

TS:   if (!x) {}
来源：http://dali.nwbrower.top/Article/details/gtyaahgucx.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.cqqwz.cn/Article/details/gtctjimzxk.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.316326.xyz/Article/details/gtfpvvmpcq.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.cdnleiting.top/Article/details/gtmjvrjbdh.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.tanke756.top/Article/details/gtojmmjebp.html

[A17] 位运算
来源：http://dali.sysykeji.top/Article/details/gtwkmsxnod.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shuidangran.top/Article/details/gtgzloysio.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.c1oappe.top/Article/details/gtfedibpiy.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gtsmlxeuri.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jianghu66.top/Article/details/gtzlzrbjnu.html


<!-- 参考信息 -->