代发 wailian999

[U99] JS：事件监听
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpphrypa.html

el.addEventListener("click", e => {})
来源：http://dali.xuetiantiany.cn/Article/details/gtlzsnuysh.html

[U100] JS：DOM 查询
来源：http://dali.sxryk.cn/Article/details/gtjxfviojq.html

document.querySelector(".item")
来源：http://dali.cdnleiting.top/Article/details/gtzinkizfw.html

[U101] JS：classList 操作
来源：http://dali.daria6918.cn/Article/details/gtudxwxzct.html

el.classList.toggle("active")
来源：http://dali.tian-w.cn/Article/details/gtwmzszgnw.html

[U102] JS：本地存储
来源：http://dali.sysykeji.top/Article/details/gtydnsahhz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shuidangran.top/Article/details/gtfkghefes.html

[U103] JS：定时器
来源：http://dali.hammf.cn/Article/details/gthguzlehy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sufxvd.cn/Article/details/gtlkoqgwbn.html

[U104] JS：防抖
来源：http://dali.zhengqikj.top/Article/details/gtejjlzixv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gtscocklud.html

[U105] JS：节流
来源：http://dali.yj20258.top/Article/details/gtofjgmclq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhixingplan.top/Article/details/gtyypeqwrk.html

[U106] JS：日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gtpzuwbxkm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yj20258.top/Article/details/gtdtvxfbrx.html

[U107] JS：数字千分位
来源：http://dali.hongshengwenyu.top/Article/details/gtggnksrmj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yueranfly.top/Article/details/gtpdsrpapf.html

[U108] JS：随机整数
来源：http://dali.zhiwuduotai.top/Article/details/gtnpbsrzin.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.nwbrower.top/Article/details/gtgkhtjkwx.html

[U109] JS：数组分组
来源：http://dali.tian-w.cn/Article/details/gtxwljvovu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyyveaycv.html

[U110] JS：数组分块
来源：http://dali.shzxlz.cn/Article/details/gtpbzcnmek.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinqigfzy.top/Article/details/gtffdjgajf.html

[U111] JS：对象转 Map
来源：http://dali.bjfxy.top/Article/details/gtmugnrajz.html

new Map(Object.entries(obj))
来源：http://dali.gogol.net.cn/Article/details/gtsyvtonku.html

[U112] JS：字符串补位
来源：http://dali.smart0.xyz/Article/details/gtymdhozfd.html

"7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtdshuopbo.html

[U113] JS：正则替换全部
来源：http://dali.shuidangran.top/Article/details/gtkembbaxm.html

s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtqelpbmyt.html

[U114] JS：JSON 深比较
来源：http://dali.zhixingplan.top/Article/details/gtjmgemniy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sufxvd.cn/Article/details/gtafltkkuf.html

[U115] JS：生成 UUID
来源：http://dali.xziqi.cn/Article/details/gtgizifyyr.html

crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gtqnzqfmjt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zycfv.cn/Article/details/gtzabwhlxl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gotoacloud.top/Article/details/gtisahjben.html

[U117] JS：单元测试
来源：http://dali.nanxinkj.top/Article/details/gtappirrbf.html

npm i -D vitest;  npx vitest
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdarhhoc.html

[U118] JS：开发服务器
来源：http://dali.fengsongda.top/Article/details/gtfbfhfkst.html

npm i -D vite;  npx vite
来源：http://dali.316326.xyz/Article/details/gtrvbuukjq.html

[U119] JS：生产构建
来源：http://dali.zhiwuduotai.top/Article/details/gtflnoqbbq.html

npx vite build
来源：http://dali.yongpay.top/Article/details/gteeacwfie.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.guannengcc.top/Article/details/gtopbyvpru.html

import.meta.env.VITE_API_URL
来源：http://dali.feifeiyinyue.top/Article/details/gtiquikhen.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtklwwnagi.html

统计汇总
来源：http://dali.birdmap.top/Article/details/gtmoinwuuu.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gthgzxecyk.html

按语言统计（条）：
来源：http://dali.mhx1999.top/Article/details/gtollaercv.html

Python ......... 252
来源：http://dali.chenjidiqi.icu/Article/details/gtvlcyjhms.html

PHP ............ 252
来源：http://dali.kuanghao11.cn/Article/details/gtmumlmwoy.html

JavaScript ..... 252
来源：http://dali.yuanzhike.top/Article/details/gtxbtpqmac.html

TypeScript ..... 212
来源：http://dali.fengsongda.top/Article/details/gtyyvpnnei.html

Java ........... 212
来源：http://dali.xuetiantiany.cn/Article/details/gtykoxmnew.html

Go ............. 212
来源：http://dali.daxiang520.top/Article/details/gtbtzswida.html

Ruby ........... 212
来源：http://dali.zycfv.cn/Article/details/gthrkgvfex.html

C# ............. 212
来源：http://dali.nwbrower.top/Article/details/gtebowyiwo.html

C .............. 30
来源：http://dali.cheryme.top/Article/details/gtnxzhfrez.html

C++ ............ 30
来源：http://dali.jiagoushi.top/Article/details/gtkltscphv.html

SQL ............ 90
来源：http://dali.jianghu66.top/Article/details/gtsheuhfme.html

Bash ........... 80
来源：http://dali.redwolf501.top/Article/details/gtppqdtyga.html

Kotlin ......... 15
来源：http://dali.aibaodan.cn/Article/details/gtpefytsou.html

Swift .......... 15
来源：http://dali.sysykeji.top/Article/details/gtvuoygwmh.html

Lua ............ 10
来源：http://dali.cqqwz.cn/Article/details/gthzpnjvnm.html

Perl ........... 10
来源：http://dali.feifeiyinyue.top/Article/details/gtbwzyoqqa.html

Scala .......... 10
来源：http://dali.quarkkingdee.top/Article/details/gttpgtkshv.html

------------------------------------
来源：http://dali.daria6918.cn/Article/details/gtksbpfibg.html

合计 ........... 2106 条
来源：http://dali.daxiang520.top/Article/details/gtfiiejoho.html

按章节统计：
来源：http://dali.c1oappe.top/Article/details/gtxqplwdik.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shzxlz.cn/Article/details/gtloomzubx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.redwolf501.top/Article/details/gthhvtyjei.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.wangdashe.top/Article/details/gtitphvvsn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.kuanghao11.cn/Article/details/gtunzexeee.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.wangshuangyany.cn/Article/details/gtjzrpzmed.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jlsjyb.cn/Article/details/gtmgmexgig.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jyoumei.cn/Article/details/gtlzxdoams.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkiufied.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gtwulcbzsm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cdnleiting.top/Article/details/gtpjakpyhu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxwvjeby.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gtjjrxcady.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.mhx1999.top/Article/details/gtcrdbpkmd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xziqi.cn/Article/details/gtziajwztp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.9152youxi.cn/Article/details/gthsetgusm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gtxnfhciyy.html

Q SQL 专题                              90
来源：http://dali.sufxvd.cn/Article/details/gtesnsekmw.html

R Bash 专题                             80
来源：http://dali.haohaochexian.top/Article/details/gtdpocdrtn.html

S C / C++ 专题                          60
来源：http://dali.cucudq.cn/Article/details/gtlennfwzj.html

T 其他语言补充                          60
来源：http://dali.cucudq.cn/Article/details/gttuucnofn.html

U 高频实用片段                         120
来源：http://dali.jiagoushi.top/Article/details/gtohfqcamu.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gtydjdozjh.html

合计                                  2106 条
来源：http://dali.yueranfly.top/Article/details/gtmzunxgvu.html

--------------------------------------------------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gttsvtgffi.html

使用提醒
来源：http://dali.yongpay.top/Article/details/gtennmodat.html

--------------------------------------------------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gtdumnhqqv.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.wangdashe.top/Article/details/gtrkqqofag.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jianghu66.top/Article/details/gtdhtbzswz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yj20258888.top/Article/details/gtisjxcnmd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xuetiantiany.cn/Article/details/gttqrpnpyo.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.redwolf501.top/Article/details/gtqrusbtjb.html

—— 文件结束 ——
来源：http://dali.yuxming.cn/Article/details/gtgmghcepc.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtdgiquggx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.tanke756.top/Article/details/gtsibasfni.html

Common Programming Examples Cheat Book
来源：http://dali.andypj.xyz/Article/details/gtnkzjnwea.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtkbmryrgz.html

【收录内容】
来源：http://dali.hywenlv.cn/Article/details/gtphgnhlna.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.kuanghao11.cn/Article/details/gtkwrnhbsn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jianghu66.top/Article/details/gtrtkajioo.html

SQL · Bash · C · C++
来源：http://dali.jinghuilouyu.cn/Article/details/gtiiwfgkxp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xuanzx.com/Article/details/gtqafmtdoa.html

【使用说明】
来源：http://dali.gogol.net.cn/Article/details/gtmbenxzil.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.snrcjt.cn/Article/details/gtqffizwmc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xinyue.icu/Article/details/gtqgehuyfa.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.guowangkeji.top/Article/details/gtokxmhspm.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hnqzz.top/Article/details/gtzectubsz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhiwuduotai.top/Article/details/gtrbrmemhi.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.feifeiyinyue.top/Article/details/gtzabwimmy.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jlsjyb.cn/Article/details/gthwoamhts.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.sxryk.cn/Article/details/gtfwvewmle.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yj202588.top/Article/details/gtnqhkniye.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.gzhubu.top/Article/details/gtvjjqdfzp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yonumen.top/Article/details/gtqbwxtgbm.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.chenlongwang.top/Article/details/gtqhjrjnhc.html

【文件统计】
来源：http://dali.birdmap.top/Article/details/gtgenfjayu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.pycfn.com/Article/details/gtgjhxfqmp.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gtauporpyu.html

目  录
来源：http://dali.hnqzz.top/Article/details/gtghmizjso.html

--------------------------------------------------------------------------------
来源：http://dali.fzhhl.top/Article/details/gtygvkselu.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.mhx1999.top/Article/details/gthrjtcqmn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hysaishi.cn/Article/details/gtfnxacxid.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xinyue.icu/Article/details/gtmmgfhkac.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yj20258888.top/Article/details/gtkalkyzlx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.aizwys.cn/Article/details/gtbhlozezx.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.meibo888.top/Article/details/gtghlhezsj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.pycfn.com/Article/details/gtfpbqdaed.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hysaishi.cn/Article/details/gtydfzfpeq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gtkycfsvrw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.gaohongyu789.top/Article/details/gtmqyiojvb.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.bjfxy.top/Article/details/gtvqyiwswp.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gtdpdmnxpe.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gtkqlgetbr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hywenlv.cn/Article/details/gtagvkgejx.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sufxvd.cn/Article/details/gtfqvhbdpq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpqyqioi.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zycfv.cn/Article/details/gthshdtbnm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.quarkkingdee.top/Article/details/gturdsdsok.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yvedp.cn/Article/details/gtzyrfuitc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zdqjudy.top/Article/details/gtcqmwmxdb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtaaylwzkd.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtcgkxgtib.html

A. 基础语法与类型
来源：http://dali.shzxlz.cn/Article/details/gtflwgagkz.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtxguxtvlk.html

[A01] Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtpeidzuvk.html

Py:   print("Hello, World!")
来源：http://dali.havefunace.top/Article/details/gtkpgbevxt.html

PHP:  echo "Hello, World!";
来源：http://dali.tianlin.xyz/Article/details/gtcdghxzlq.html

JS:   console.log("Hello, World!");
来源：http://dali.hysaishi.cn/Article/details/gtbioqhorr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.daria6918.cn/Article/details/gtyykasmqe.html

Java: System.out.println("Hello, World!");
来源：http://dali.jlsjyb.cn/Article/details/gthwysicob.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xuetiantiany.cn/Article/details/gtfwqwhcdy.html

Ruby: puts "Hello, World!"
来源：http://dali.yangfankeji.com/Article/details/gttgecfqdb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.guannengcc.top/Article/details/gtwrmfxvoc.html

[A02] 变量声明与赋值
来源：http://dali.chenlongwang.top/Article/details/gtzirlpdnd.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbkidsis.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.cdnleiting.top/Article/details/gtyhfzdhxr.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhengqikj.top/Article/details/gtantcvkys.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.shanyushiyangtech.top/Article/details/gttgdcqbve.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.nwbrower.top/Article/details/gtaiwpnmjm.html

Go:   name := "Alex"; age := 20
来源：http://dali.jianghu66.top/Article/details/gtovaisvko.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhoulong.xyz/Article/details/gtqnywhwqc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcnademom.html

[A03] 常量定义
来源：http://dali.cucudq.cn/Article/details/gtkacwycid.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shanyushiyangtech.top/Article/details/gtszgbvalv.html

PHP:  const PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtlcjrgzfz.html

JS:   const PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtomezqkvx.html

TS:   const PI: number = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtlooootat.html

Java: static final double PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gtvgsvwxlq.html

Go:   const PI = 3.14159
来源：http://dali.feifeiyinyue.top/Article/details/gtsvovchbp.html

Ruby: PI = 3.14159
来源：http://dali.zhiwuduotai.top/Article/details/gtjdwtuqij.html

C#:   const double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtaleufdcm.html

[A04] 判断变量类型
来源：http://dali.smart0.xyz/Article/details/gtuybgsimq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hnqzz.top/Article/details/gtfahgasst.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.daxiang520.top/Article/details/gtkheujyrl.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.svipenyu.cn/Article/details/gtdedzrljr.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gtljkkwqmo.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhixingplan.top/Article/details/gtkfemqbat.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.pengpengdd.cyou/Article/details/gttsbpfhba.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jiagoushi.top/Article/details/gtpnhcpwcs.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhongyouzk.top/Article/details/gtjtlxzhte.html

[A05] 整数除法与取模
来源：http://dali.feifeiyinyue.top/Article/details/gtrzilbylt.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.ybcxt.top/Article/details/gtynendpyc.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zycfv.cn/Article/details/gttmzgnlxq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhoulong.xyz/Article/details/gttusuhbgi.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtyzdxpssk.html

Java: 7 / 2; 7 % 2
来源：http://dali.bjfxy.top/Article/details/gtspnyzrlt.html

Go:   7 / 2; 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtgwxhwnkl.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jianghu66.top/Article/details/gtpbopdejl.html

C#:   7 / 2; 7 % 2
来源：http://dali.gzhubu.top/Article/details/gtldgqezru.html

[A06] 字符串转数字
来源：http://dali.yanxiufei.cn/Article/details/gtuywmbulg.html

Py:   int("42"); float("3.14")
来源：http://dali.tian-w.cn/Article/details/gtkodqsaoq.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.wangshuangyany.cn/Article/details/gtzfccqzzx.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ybcxt.top/Article/details/gtxmsmmfyg.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.iojbl.cn/Article/details/gtrxjnphfw.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yj20258.top/Article/details/gtvdcyuhwh.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaeihjpdh.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yanxiufei.cn/Article/details/gtquqmqyep.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.shuidangran.top/Article/details/gtrwoxyzsc.html

[A07] 数字转字符串
来源：http://dali.jiagoushi.top/Article/details/gtmjvraxou.html

Py:   str(42)
来源：http://dali.sufxvd.cn/Article/details/gtbcoeoehc.html

PHP:  (string) 42; strval(42)
来源：http://dali.sufxvd.cn/Article/details/gtztblbqqz.html

JS:   String(42); (42).toString()
来源：http://dali.chenzaomai.com/Article/details/gtembglnua.html

TS:   String(42)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteoeqwgbd.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.havefunace.top/Article/details/gtdmonvwmn.html

Go:   strconv.Itoa(42)
来源：http://dali.andypj.xyz/Article/details/gtnplofrth.html

Ruby: 42.to_s
来源：http://dali.wangdashe.top/Article/details/gtebspcxdo.html

C#:   42.ToString()
来源：http://dali.zycfv.cn/Article/details/gtlxuavecy.html

[A08] 取整与四舍五入
来源：http://dali.9152youxi.cn/Article/details/gttemckzdg.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnecgksvb.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.dianchejie.cn/Article/details/gtrtdbgmdl.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.nanxuanxn.top/Article/details/gtyayosony.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.andypj.xyz/Article/details/gtqrccsgwf.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnkitoea.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.pengpengdd.cyou/Article/details/gtebbvluoi.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.cheryme.top/Article/details/gtmcakdsul.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yueranfly.top/Article/details/gtdrnoahhi.html

[A09] 绝对值与最大最小值
来源：http://dali.xylfe.cn/Article/details/gtmwmfepxk.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqcczmog.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.guannengcc.top/Article/details/gtprvgnpcr.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zycfv.cn/Article/details/gtwwmcutsg.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.meibo888.top/Article/details/gtqmmbkrkq.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gtqlkrhqdw.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.tianlin.xyz/Article/details/gtukgbgnht.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.xuetiantiany.cn/Article/details/gtthnewivk.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtwbjvpalv.html

[A10] 生成随机数
来源：http://dali.316326.xyz/Article/details/gtgidxsias.html

Py:   import random; random.randint(1, 100)
来源：http://dali.smart0.xyz/Article/details/gtjsnucuff.html

PHP:  random_int(1, 100);
来源：http://dali.xylfe.cn/Article/details/gtznpxcnoy.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jqgufenzy.top/Article/details/gtjczqewwu.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.dashuyun.cn/Article/details/gtffuuekbj.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yanxiufei.cn/Article/details/gtwgblxyim.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.dashuyun.cn/Article/details/gtkcmvmzok.html

Ruby: rand(1..100)
来源：http://dali.yj202588.top/Article/details/gtqynwphwz.html

C#:   new Random().Next(1, 101)
来源：http://dali.ivvv.top/Article/details/gtweompffp.html

[A11] 条件表达式（三元）
来源：http://dali.sxryk.cn/Article/details/gtvbwypbrm.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zdqjudy.top/Article/details/gtgzzxypji.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhongyouzk.top/Article/details/gtrwhusmwb.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zdqjudy.top/Article/details/gtonrxxsmi.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhixingplan.top/Article/details/gtqxhgqubc.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhiwuduotai.top/Article/details/gtmhxefgzp.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.ivvv.top/Article/details/gtrpqtnmpq.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.c1oappe.top/Article/details/gtvdztvdoe.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.gotoacloud.top/Article/details/gtpdbyanjo.html

[A12] 字符串插值 / 格式化
来源：http://dali.wangdashe.top/Article/details/gtwfolfwal.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yj202588.top/Article/details/gtqgxwyhmd.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yonumen.top/Article/details/gtnhxmmhpp.html

JS:   `Hello, ${name}!`
来源：http://dali.smart0.xyz/Article/details/gtfrcfwwzz.html

TS:   `Hello, ${name}!`
来源：http://dali.cqqwz.cn/Article/details/gtjknsrnrm.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yanxiufei.cn/Article/details/gtnghuwury.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.xuanzx.com/Article/details/gtdayrjgiv.html

Ruby: "Hello, #{name}!"
来源：http://dali.gaohongyu789.top/Article/details/gtglqljzrl.html

C#:   $"Hello, {name}!"
来源：http://dali.haohaochexian.top/Article/details/gtqhveagoa.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.ivvv.top/Article/details/gttgwunkwa.html

Py:   "第一行\n第二行"
来源：http://dali.yj202588.top/Article/details/gtokqtxrtg.html

PHP:  "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gtcvofcapc.html

JS:   "第一行\n第二行"
来源：http://dali.shangyingyoupin.top/Article/details/gtddsmhcsl.html

TS:   "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gtgtzdjmrd.html

Java: "第一行\n第二行"
来源：http://dali.pengpengdd.cyou/Article/details/gtndqodoef.html

Go:   "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gtqunenrvp.html

Ruby: "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gtnimaapzf.html

C#:   "第一行\n第二行"
来源：http://dali.hfpthk.cn/Article/details/gtlntfaqtm.html

[A14] 注释写法
来源：http://dali.smart0.xyz/Article/details/gtdqgudcqm.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.quarkkingdee.top/Article/details/gtpwfrlbbj.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.316326.xyz/Article/details/gthaycdnzl.html

JS:   // 单行；/* 多行 */
来源：http://dali.hnqzz.top/Article/details/gtajkakpvm.html

TS:   // 单行；/* 多行 */
来源：http://dali.hongshengwenyu.top/Article/details/gteqralujd.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.cucudq.cn/Article/details/gtmnozcjcl.html

Go:   // 单行；/* 多行 */
来源：http://dali.jinghuilouyu.cn/Article/details/gtenlscrjh.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.daria6918.cn/Article/details/gtxmpqwypv.html

C#:   // 单行；/* 多行 */
来源：http://dali.aizwys.cn/Article/details/gtyysstfpd.html

[A15] 空值判断与默认值
来源：http://dali.hammf.cn/Article/details/gtnttqxppn.html

Py:   value = data or "默认值"
来源：http://dali.gaohongyu789.top/Article/details/gttudjrstl.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jinqigufen.top/Article/details/gtbbklosna.html

JS:   const value = data ?? "默认值";
来源：http://dali.jqgfzy.top/Article/details/gtgofifsxz.html

TS:   const value = data ?? "默认值";
来源：http://dali.shanyushiyangtech.top/Article/details/gtrckzvvpl.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.xylfe.cn/Article/details/gtxabtkpkq.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.wangshuangyany.cn/Article/details/gtogpwhiix.html

Ruby: value = data || "默认值"
来源：http://dali.kuanghao11.cn/Article/details/gttuukbxjz.html

C#:   var value = data ?? "默认值";
来源：http://dali.shanyushiyangtech.top/Article/details/gtgkmnylar.html

[A16] 真假值判断规则
来源：http://dali.yj20258.top/Article/details/gtwygonorw.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yvedp.cn/Article/details/gtieyqxsaq.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswdrgfme.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.bjfxy.top/Article/details/gtjhukhcdy.html

TS:   if (!x) {}
来源：http://dali.mhx1999.top/Article/details/gtfiqmrtle.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhengqikj.top/Article/details/gtrceoaked.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.dashuyun.cn/Article/details/gtxmsdcbql.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jinqigufen.top/Article/details/gtfbirfvka.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.meibo888.top/Article/details/gtpdotiqth.html

[A17] 位运算
来源：http://dali.bjfxy.top/Article/details/gtfbaptmzv.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gtcjubfbay.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.0kj1m.cn/Article/details/gtoioqiciz.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gtjnefwkhe.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gtboatqaap.html


<!-- 参考信息 -->