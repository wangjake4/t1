代发 wailian999

[U99] JS：事件监听
来源：http://dali.quarkkingdee.top/Article/details/gtbtawusyl.html

el.addEventListener("click", e => {})
来源：http://dali.yvedp.cn/Article/details/gtefyvaepr.html

[U100] JS：DOM 查询
来源：http://dali.gogol.net.cn/Article/details/gtexxywbsm.html

document.querySelector(".item")
来源：http://dali.fengsongda.top/Article/details/gtbxogryam.html

[U101] JS：classList 操作
来源：http://dali.jqgufenzy.top/Article/details/gtclxuokgu.html

el.classList.toggle("active")
来源：http://dali.xylfe.cn/Article/details/gtgzplcmic.html

[U102] JS：本地存储
来源：http://dali.yuanzhike.top/Article/details/gtmenfwfqo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.birdmap.top/Article/details/gtnjhklubt.html

[U103] JS：定时器
来源：http://dali.zhongyouzk.top/Article/details/gtsklcyagm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shangyingyoupin.top/Article/details/gtosytsvdi.html

[U104] JS：防抖
来源：http://dali.shanyushiyangtech.top/Article/details/gtozmqahra.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtiwwvhdml.html

[U105] JS：节流
来源：http://dali.yvedp.cn/Article/details/gtjjiqlopg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqzgpjul.html

[U106] JS：日期格式化
来源：http://dali.jqgfzy.top/Article/details/gtjqumooek.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.vqdsnc.cn/Article/details/gthkkxuwyo.html

[U107] JS：数字千分位
来源：http://dali.yanxiufei.cn/Article/details/gtencldyol.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yueranfly.top/Article/details/gtmvtepgaq.html

[U108] JS：随机整数
来源：http://dali.hfpthk.cn/Article/details/gtuuwgovcw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hywenlv.cn/Article/details/gtoubyddim.html

[U109] JS：数组分组
来源：http://dali.hnqzz.top/Article/details/gtmskrqkpi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ybcxt.top/Article/details/gttbsaqpaq.html

[U110] JS：数组分块
来源：http://dali.yueranfly.top/Article/details/gtmwbaniuf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.nanxinkj.top/Article/details/gtfpvfzbkg.html

[U111] JS：对象转 Map
来源：http://dali.ivvv.top/Article/details/gtfvrvzmvo.html

new Map(Object.entries(obj))
来源：http://dali.yuanzhike.top/Article/details/gtrnyqpvpf.html

[U112] JS：字符串补位
来源：http://dali.tianlin.xyz/Article/details/gtduztxhwf.html

"7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gtqsqzpwae.html

[U113] JS：正则替换全部
来源：http://dali.cqqwz.cn/Article/details/gtfytvaksl.html

s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtplbkayss.html

[U114] JS：JSON 深比较
来源：http://dali.jlsjyb.cn/Article/details/gtzktwnhvo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fzhhl.top/Article/details/gticnkjyvr.html

[U115] JS：生成 UUID
来源：http://dali.hammf.cn/Article/details/gttjedicah.html

crypto.randomUUID()
来源：http://dali.jlsjyb.cn/Article/details/gthjsmrxzo.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hfpthk.cn/Article/details/gtmchqzgzc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cashguo.top/Article/details/gtrchpouhf.html

[U117] JS：单元测试
来源：http://dali.gogol.net.cn/Article/details/gtkhiwunmm.html

npm i -D vitest;  npx vitest
来源：http://dali.nwbrower.top/Article/details/gtichgkyck.html

[U118] JS：开发服务器
来源：http://dali.guowangkeji.top/Article/details/gtdnztxmjy.html

npm i -D vite;  npx vite
来源：http://dali.zhiwuduotai.top/Article/details/gtyeahwxku.html

[U119] JS：生产构建
来源：http://dali.tian-w.cn/Article/details/gtuhzwdjvs.html

npx vite build
来源：http://dali.yvedp.cn/Article/details/gtkkjkdiae.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jianghu66.top/Article/details/gtzjydbssm.html

import.meta.env.VITE_API_URL
来源：http://dali.fzhhl.top/Article/details/gthtkxofhb.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtwpvqztkm.html

统计汇总
来源：http://dali.cdnleiting.top/Article/details/gtfoccbqyf.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtdgijstbr.html

按语言统计（条）：
来源：http://dali.zhixingplan.top/Article/details/gtshxtlymd.html

Python ......... 252
来源：http://dali.chenlongwang.top/Article/details/gtllpdxfir.html

PHP ............ 252
来源：http://dali.bjfxy.top/Article/details/gtpxnhzlzf.html

JavaScript ..... 252
来源：http://dali.havefunace.top/Article/details/gtpjflbdgu.html

TypeScript ..... 212
来源：http://dali.hongshengwenyu.top/Article/details/gttlrreyjd.html

Java ........... 212
来源：http://dali.xuetiantiany.cn/Article/details/gtskxhqdqg.html

Go ............. 212
来源：http://dali.hongshengwenyu.top/Article/details/gtilqbwlvh.html

Ruby ........... 212
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhwaauag.html

C# ............. 212
来源：http://dali.aizwys.cn/Article/details/gtvexpojoc.html

C .............. 30
来源：http://dali.cqqwz.cn/Article/details/gtiqmdsbkn.html

C++ ............ 30
来源：http://dali.ybcxt.top/Article/details/gtnrnokwhu.html

SQL ............ 90
来源：http://dali.yvedp.cn/Article/details/gtojfciryz.html

Bash ........... 80
来源：http://dali.9152youxi.cn/Article/details/gtiqeopssz.html

Kotlin ......... 15
来源：http://dali.dianchejie.cn/Article/details/gtigtdthcr.html

Swift .......... 15
来源：http://dali.yuxming.cn/Article/details/gtrbuobldk.html

Lua ............ 10
来源：http://dali.shuidangran.top/Article/details/gtkdjtknnk.html

Perl ........... 10
来源：http://dali.zycfv.cn/Article/details/gtdbquuwlt.html

Scala .......... 10
来源：http://dali.hywenlv.cn/Article/details/gtjcbpacxd.html

------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gtursqyqpr.html

合计 ........... 2106 条
来源：http://dali.hnxiangtu.top/Article/details/gtexvwslza.html

按章节统计：
来源：http://dali.smart0.xyz/Article/details/gthkoyidmg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.316326.xyz/Article/details/gtnwlczmsw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhiwuduotai.top/Article/details/gtjxxlynvz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jqgfzy.top/Article/details/gtexdjgxgg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cucudq.cn/Article/details/gtgmdnuxix.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yanxiufei.cn/Article/details/gtpuorzkin.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.daxiang520.top/Article/details/gttxiiogpc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gogol.net.cn/Article/details/gtbeoqpbxm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shuidangran.top/Article/details/gttitzirvt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gtvcgmspzc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinqigfzy.top/Article/details/gtezlrutky.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gtqrmcrfmz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gtjqlhfsda.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gthbqouijg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jiagoushi.top/Article/details/gtmrbxdzek.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jinqigufen.top/Article/details/gtdsjoneci.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gtzjsjwael.html

Q SQL 专题                              90
来源：http://dali.jinqigfzy.top/Article/details/gtvrwwsyly.html

R Bash 专题                             80
来源：http://dali.zdqjudy.top/Article/details/gtkdpirfft.html

S C / C++ 专题                          60
来源：http://dali.zdqjudy.top/Article/details/gtgpxxdiwp.html

T 其他语言补充                          60
来源：http://dali.hongshengwenyu.top/Article/details/gtcaanarjg.html

U 高频实用片段                         120
来源：http://dali.wangshuangyany.cn/Article/details/gtymbhzvfu.html

------------------------------------
来源：http://dali.tian-w.cn/Article/details/gturndllre.html

合计                                  2106 条
来源：http://dali.tian-w.cn/Article/details/gtxboftxab.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtqilstxvz.html

使用提醒
来源：http://dali.shzxlz.cn/Article/details/gthnedzsfi.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gtjjhrvbvu.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ppjwa.cn/Article/details/gtxwokzyds.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jinqigufen.top/Article/details/gtypyejlap.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhongyouzk.top/Article/details/gtktylrrjp.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xylfe.cn/Article/details/gtwhprjwac.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hfpthk.cn/Article/details/gtdsjmnvfg.html

—— 文件结束 ——
来源：http://dali.c1oappe.top/Article/details/gtxpqherkr.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtcvsxsmiu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.tian-w.cn/Article/details/gtfpwmmmnm.html

Common Programming Examples Cheat Book
来源：http://dali.zycfv.cn/Article/details/gtwiqjzlnv.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtndlueugo.html

【收录内容】
来源：http://dali.zhiwuduotai.top/Article/details/gtylsmiwjn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.havefunace.top/Article/details/gtncedmqfy.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.birdmap.top/Article/details/gttaaibpxf.html

SQL · Bash · C · C++
来源：http://dali.gotoacloud.top/Article/details/gtciwipvsv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jinghuilouyu.cn/Article/details/gtmiqtnmrg.html

【使用说明】
来源：http://dali.mhx1999.top/Article/details/gtidislzqs.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.dianchejie.cn/Article/details/gtmpnqreby.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.gzhubu.top/Article/details/gtrtidvcmt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.wangshuangyany.cn/Article/details/gtuacbbvxz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.svipenyu.cn/Article/details/gtfuozuaqu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.aizwys.cn/Article/details/gtnuvomufs.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cheryme.top/Article/details/gtgzttwrsh.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.guannengcc.top/Article/details/gtcqabamrl.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.316326.xyz/Article/details/gtsktqmtvl.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jinqigufen.top/Article/details/gtofufalaw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolciyovu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zycfv.cn/Article/details/gtdodpcasl.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.redwolf501.top/Article/details/gtfujtgzxg.html

【文件统计】
来源：http://dali.wangshuangyany.cn/Article/details/gtlggizetp.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.chenjidiqi.icu/Article/details/gtgnemcsqj.html

--------------------------------------------------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchxdoewy.html

目  录
来源：http://dali.0kj1m.cn/Article/details/gtdwuohxkl.html

--------------------------------------------------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gtsjxzuoff.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xylfe.cn/Article/details/gtqhdoegfi.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.pycfn.com/Article/details/gtbnndaobv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.havefunace.top/Article/details/gtekpbbktc.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzsfovpt.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.316326.xyz/Article/details/gtreopyzud.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.nanxinkj.top/Article/details/gtehunrgkz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jyoumei.cn/Article/details/gttragyneu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.wangdashe.top/Article/details/gtjcpvanyy.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gtbpfrwayd.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.vqdsnc.cn/Article/details/gtkiffijxa.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.daria6918.cn/Article/details/gtwusqknai.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gtcnsogmwz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yangfankeji.com/Article/details/gtpixqzvhn.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jianghu66.top/Article/details/gtamcmerwd.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.nanxuanxn.top/Article/details/gtoyffjjyv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.svipenyu.cn/Article/details/gtwzimuxnb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zycfv.cn/Article/details/gtkylxikqq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hammf.cn/Article/details/gtusfusyja.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yuanzhike.top/Article/details/gtfkdoqfng.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258.top/Article/details/gttovcqxlp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xziqi.cn/Article/details/gtcmxcrnay.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtoqwpcjge.html

A. 基础语法与类型
来源：http://dali.guannengcc.top/Article/details/gtsygwmzlz.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gthblcphay.html

[A01] Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtoovngebl.html

Py:   print("Hello, World!")
来源：http://dali.gogol.net.cn/Article/details/gtreqdcqko.html

PHP:  echo "Hello, World!";
来源：http://dali.yj20258888.top/Article/details/gtunqfhfka.html

JS:   console.log("Hello, World!");
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqwzycxn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ivvv.top/Article/details/gtyyyqeiou.html

Java: System.out.println("Hello, World!");
来源：http://dali.zdqjudy.top/Article/details/gtrtyurvzh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.0kj1m.cn/Article/details/gtlxigarbv.html

Ruby: puts "Hello, World!"
来源：http://dali.cashguo.top/Article/details/gtgndvkpaf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.pengpengdd.cyou/Article/details/gtdjifiilu.html

[A02] 变量声明与赋值
来源：http://dali.tianlin.xyz/Article/details/gtwfgoxumk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.aizwys.cn/Article/details/gtqpcplryo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hywenlv.cn/Article/details/gtngyzaknd.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xuetiantiany.cn/Article/details/gtrbhbsvir.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtguxwrrrk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvezzrqj.html

Go:   name := "Alex"; age := 20
来源：http://dali.jqgufenzy.top/Article/details/gtiweacunq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.daxiang520.top/Article/details/gtlhiwepzb.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.meibo888.top/Article/details/gthvueoxso.html

[A03] 常量定义
来源：http://dali.ybcxt.top/Article/details/gtkqrvhggt.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.kuanghao11.cn/Article/details/gtaqdsrjpu.html

PHP:  const PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gttvwjkrow.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtmuudzuel.html

TS:   const PI: number = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtudnaqmey.html

Java: static final double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtvkwzaqvr.html

Go:   const PI = 3.14159
来源：http://dali.haohaochexian.top/Article/details/gtqgnyarqi.html

Ruby: PI = 3.14159
来源：http://dali.ydzc1.top/Article/details/gtrimhspdm.html

C#:   const double PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtrmxczwmc.html

[A04] 判断变量类型
来源：http://dali.meibo888.top/Article/details/gtkqvlzlsj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.gogol.net.cn/Article/details/gtdgzcsyaj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cqqwz.cn/Article/details/gtechicixj.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.0kj1m.cn/Article/details/gtevxucvne.html

TS:   typeof x; x instanceof Date
来源：http://dali.9152youxi.cn/Article/details/gthxxutdlw.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.gogol.net.cn/Article/details/gtmfsyyrwi.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yj202588.top/Article/details/gtctkygaeh.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yanxiufei.cn/Article/details/gtdexxfvrr.html

C#:   x.GetType().Name; x is int
来源：http://dali.hfpthk.cn/Article/details/gtssxonmwf.html

[A05] 整数除法与取模
来源：http://dali.cheryme.top/Article/details/gtntzpqrny.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxdyhgaz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtmgxhpwcb.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ybcxt.top/Article/details/gtphuhexna.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xylfe.cn/Article/details/gtrsptjkbk.html

Java: 7 / 2; 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gtdrsqmlrp.html

Go:   7 / 2; 7 % 2
来源：http://dali.tian-w.cn/Article/details/gtevlicfwc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jianghu66.top/Article/details/gtkdbmyjpb.html

C#:   7 / 2; 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gtwbikikyp.html

[A06] 字符串转数字
来源：http://dali.gaohongyu789.top/Article/details/gtzttuxekp.html

Py:   int("42"); float("3.14")
来源：http://dali.andypj.xyz/Article/details/gtqrixlugh.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yonumen.top/Article/details/gtlisdshbc.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ivvv.top/Article/details/gtahenbwys.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.snrcjt.cn/Article/details/gtkeyheban.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.c1oappe.top/Article/details/gtwnnhpcsg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.guannengcc.top/Article/details/gtygtofsxb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.dianchejie.cn/Article/details/gttplrstga.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvocppejl.html

[A07] 数字转字符串
来源：http://dali.aibaodan.cn/Article/details/gtzfxfpmvj.html

Py:   str(42)
来源：http://dali.nanxinkj.top/Article/details/gtxjakzoxh.html

PHP:  (string) 42; strval(42)
来源：http://dali.gaohongyu789.top/Article/details/gtcaseerjl.html

JS:   String(42); (42).toString()
来源：http://dali.zhengqikj.top/Article/details/gtkydfonqb.html

TS:   String(42)
来源：http://dali.jiagoushi.top/Article/details/gtxoxhjctj.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.nwbrower.top/Article/details/gttraxllls.html

Go:   strconv.Itoa(42)
来源：http://dali.wangdashe.top/Article/details/gtowhmupgc.html

Ruby: 42.to_s
来源：http://dali.chenjidiqi.icu/Article/details/gtnfdvsehn.html

C#:   42.ToString()
来源：http://dali.wangshuangyany.cn/Article/details/gtruzbkzer.html

[A08] 取整与四舍五入
来源：http://dali.gzhubu.top/Article/details/gtidtezyzz.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hnqzz.top/Article/details/gtqfwfsztk.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.feifeiyinyue.top/Article/details/gtvqjlxcca.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.nanxinkj.top/Article/details/gtkcsrclmn.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.nwbrower.top/Article/details/gthouyqhry.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.chenzaomai.com/Article/details/gtgshettta.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.shanyushiyangtech.top/Article/details/gtroswhjlf.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftpcdzke.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnrmfgsb.html

[A09] 绝对值与最大最小值
来源：http://dali.vqdsnc.cn/Article/details/gticxycwpx.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yvedp.cn/Article/details/gtchpkovea.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gtraoyuuee.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.aizwys.cn/Article/details/gtvqdiobxb.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkbswirj.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.meibo888.top/Article/details/gtmmlezubf.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczjyxupy.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.hfpthk.cn/Article/details/gtkcknwynt.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.nwbrower.top/Article/details/gtjrnmltqb.html

[A10] 生成随机数
来源：http://dali.yj20258.top/Article/details/gtabicfeyt.html

Py:   import random; random.randint(1, 100)
来源：http://dali.dianchejie.cn/Article/details/gtxprjzxwk.html

PHP:  random_int(1, 100);
来源：http://dali.hysaishi.cn/Article/details/gtuatovrgf.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.chenjidiqi.icu/Article/details/gtiwxgpsxu.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shuidangran.top/Article/details/gtjnapfmvb.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yongpay.top/Article/details/gtwxueteza.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jqgfzy.top/Article/details/gtwllkfugi.html

Ruby: rand(1..100)
来源：http://dali.yangfankeji.com/Article/details/gtpbwnjcuo.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhengqikj.top/Article/details/gtgaetiybv.html

[A11] 条件表达式（三元）
来源：http://dali.zhengqikj.top/Article/details/gtomtmyxog.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zdqjudy.top/Article/details/gtugtphstv.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.fzhhl.top/Article/details/gtqzljgchd.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yj202588.top/Article/details/gtbwgghmyr.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zdqjudy.top/Article/details/gtidgjxfjr.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhixingplan.top/Article/details/gttroromsc.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yj20258.top/Article/details/gthudablie.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.shzxlz.cn/Article/details/gtbvprkhjq.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.wangshuangyany.cn/Article/details/gtijnoiavm.html

[A12] 字符串插值 / 格式化
来源：http://dali.guannengcc.top/Article/details/gtlkfzbdjt.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.0kj1m.cn/Article/details/gtasnjdhbj.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.shangyingyoupin.top/Article/details/gttobhrdsk.html

JS:   `Hello, ${name}!`
来源：http://dali.yvedp.cn/Article/details/gtdjqsmzij.html

TS:   `Hello, ${name}!`
来源：http://dali.wangshuangyany.cn/Article/details/gtfkbgazgd.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jinqigfzy.top/Article/details/gtpmxpaacg.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zycfv.cn/Article/details/gticvgmkso.html

Ruby: "Hello, #{name}!"
来源：http://dali.yueranfly.top/Article/details/gtbsoebhrj.html

C#:   $"Hello, {name}!"
来源：http://dali.tanke756.top/Article/details/gtixcnxeba.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.andypj.xyz/Article/details/gtixjztkwv.html

Py:   "第一行\n第二行"
来源：http://dali.yvedp.cn/Article/details/gtvlwgfsbl.html

PHP:  "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gtipahglrm.html

JS:   "第一行\n第二行"
来源：http://dali.gaohongyu789.top/Article/details/gtnxwybjmn.html

TS:   "第一行\n第二行"
来源：http://dali.yueranfly.top/Article/details/gtzisjwtlr.html

Java: "第一行\n第二行"
来源：http://dali.hysaishi.cn/Article/details/gtersryyea.html

Go:   "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gtuoeypgte.html

Ruby: "第一行\n第二行"
来源：http://dali.birdmap.top/Article/details/gtcthucoxc.html

C#:   "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gtcbjesdhv.html

[A14] 注释写法
来源：http://dali.yueranfly.top/Article/details/gtagdrjfok.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.shanyushiyangkeji.top/Article/details/gtughklgne.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.iojbl.cn/Article/details/gtiemnluzi.html

JS:   // 单行；/* 多行 */
来源：http://dali.dashuyun.cn/Article/details/gtheuynybc.html

TS:   // 单行；/* 多行 */
来源：http://dali.xylfe.cn/Article/details/gttkrvamzs.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.bjfxy.top/Article/details/gtypeqfjkx.html

Go:   // 单行；/* 多行 */
来源：http://dali.9152youxi.cn/Article/details/gtbyugnwgx.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yangfankeji.com/Article/details/gtbniwyvza.html

C#:   // 单行；/* 多行 */
来源：http://dali.dashuyun.cn/Article/details/gtarxlsyxc.html

[A15] 空值判断与默认值
来源：http://dali.jiagoushi.top/Article/details/gtpnldopog.html

Py:   value = data or "默认值"
来源：http://dali.yangfankeji.com/Article/details/gtqqykjuzy.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.dianchejie.cn/Article/details/gtlldyhdpm.html

JS:   const value = data ?? "默认值";
来源：http://dali.sweek.top/Article/details/gtqaidjung.html

TS:   const value = data ?? "默认值";
来源：http://dali.bjfxy.top/Article/details/gtepcmxkqb.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhoulong.xyz/Article/details/gtgmgsmris.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jinqigufen.top/Article/details/gtocrrijqf.html

Ruby: value = data || "默认值"
来源：http://dali.daria6918.cn/Article/details/gtmkpkzzfa.html

C#:   var value = data ?? "默认值";
来源：http://dali.nanxinkj.top/Article/details/gtefpjbnme.html

[A16] 真假值判断规则
来源：http://dali.tian-w.cn/Article/details/gtxpsgtlpz.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.chenzaomai.com/Article/details/gtvfswbruu.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.iojbl.cn/Article/details/gtpwodaela.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.smart0.xyz/Article/details/gtjmatqxxq.html

TS:   if (!x) {}
来源：http://dali.yuanzhike.top/Article/details/gtbueqxiwg.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.cdnleiting.top/Article/details/gtwrfwwbtq.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.shuidangran.top/Article/details/gtacprdbtv.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.ydzc1.top/Article/details/gtyonjgjjl.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.sufxvd.cn/Article/details/gtpmpzkrss.html

[A17] 位运算
来源：http://dali.zhiwuduotai.top/Article/details/gtakvsalwj.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shangyingyoupin.top/Article/details/gtcsqyyqpm.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.hnqzz.top/Article/details/gtsxqhfusw.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sysykeji.top/Article/details/gtiuvkvbus.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.hnqzz.top/Article/details/gtguguicur.html


<!-- 参考信息 -->