代发 wailian999

[U97] JS：并发请求
来源：http://dali.jqgufenzy.top/Article/details/gtxkzinsit.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gtfzrasbyo.html

[U98] JS：fetch 带 JSON
来源：http://dali.zdqjudy.top/Article/details/gttpupsyvd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hammf.cn/Article/details/gtrddnwvbc.html

[U99] JS：事件监听
来源：http://dali.cheryme.top/Article/details/gtkxiiiamz.html

el.addEventListener("click", e => {})
来源：http://dali.yueranfly.top/Article/details/gtndaumdvk.html

[U100] JS：DOM 查询
来源：http://dali.fengsongda.top/Article/details/gtkyfzxeaz.html

document.querySelector(".item")
来源：http://dali.jianghu66.top/Article/details/gtbvogzqym.html

[U101] JS：classList 操作
来源：http://dali.ydzc1.top/Article/details/gtmpmxmkyx.html

el.classList.toggle("active")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcmfioylk.html

[U102] JS：本地存储
来源：http://dali.zhoulong.xyz/Article/details/gttjkztvbh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.guannengcc.top/Article/details/gtsovennjq.html

[U103] JS：定时器
来源：http://dali.zhiwuduotai.top/Article/details/gtkhmstccl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gzhubu.top/Article/details/gtembekwfm.html

[U104] JS：防抖
来源：http://dali.cqqwz.cn/Article/details/gtzmnqbqah.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gtakzpviiz.html

[U105] JS：节流
来源：http://dali.smart0.xyz/Article/details/gtqyrzuotm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yj202588.top/Article/details/gtmanocprh.html

[U106] JS：日期格式化
来源：http://dali.yuxming.cn/Article/details/gtgrxynbuj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.redwolf501.top/Article/details/gtcfidawxf.html

[U107] JS：数字千分位
来源：http://dali.zycfv.cn/Article/details/gtwjxqbvbh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.iojbl.cn/Article/details/gtkgcgxbfa.html

[U108] JS：随机整数
来源：http://dali.pycfn.com/Article/details/gtaphgobdp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.tanke756.top/Article/details/gtdalppmle.html

[U109] JS：数组分组
来源：http://dali.gogol.net.cn/Article/details/gtbcfjlytj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.nwbrower.top/Article/details/gtevixukwr.html

[U110] JS：数组分块
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxsyleuy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ydzc1.top/Article/details/gtfqriukkc.html

[U111] JS：对象转 Map
来源：http://dali.yueranfly.top/Article/details/gtbaeymogn.html

new Map(Object.entries(obj))
来源：http://dali.nwbrower.top/Article/details/gtlymxhded.html

[U112] JS：字符串补位
来源：http://dali.tanke756.top/Article/details/gtsngeepxe.html

"7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gtefpgjqfk.html

[U113] JS：正则替换全部
来源：http://dali.jqgufenzy.top/Article/details/gtouxwncoh.html

s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gtnwqdpihz.html

[U114] JS：JSON 深比较
来源：http://dali.jiagoushi.top/Article/details/gtyozwenpz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sysykeji.top/Article/details/gtizxkwfbm.html

[U115] JS：生成 UUID
来源：http://dali.9152youxi.cn/Article/details/gtakmqskno.html

crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gtpbqicgzh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.sweek.top/Article/details/gtnoxoalda.html

/** @param {string} name */ function f(name) {}
来源：http://dali.dashuyun.cn/Article/details/gtctymmqqo.html

[U117] JS：单元测试
来源：http://dali.yj20258888.top/Article/details/gttwfmtqto.html

npm i -D vitest;  npx vitest
来源：http://dali.birdmap.top/Article/details/gtwmqfdlii.html

[U118] JS：开发服务器
来源：http://dali.cucudq.cn/Article/details/gtriokvqns.html

npm i -D vite;  npx vite
来源：http://dali.jinqigfzy.top/Article/details/gtjimdbhda.html

[U119] JS：生产构建
来源：http://dali.mhx1999.top/Article/details/gteabwqivf.html

npx vite build
来源：http://dali.zhixingplan.top/Article/details/gtpjuqadfs.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.nanxuanxn.top/Article/details/gtwxlsjhfj.html

import.meta.env.VITE_API_URL
来源：http://dali.yonumen.top/Article/details/gtoqfdxdjr.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtrheipjjg.html

统计汇总
来源：http://dali.haohaochexian.top/Article/details/gtwyzoydfy.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtkilramxh.html

按语言统计（条）：
来源：http://dali.hammf.cn/Article/details/gtdixaunhh.html

Python ......... 252
来源：http://dali.chenzaomai.com/Article/details/gtrbsnrhrj.html

PHP ............ 252
来源：http://dali.9152youxi.cn/Article/details/gtqeragdta.html

JavaScript ..... 252
来源：http://dali.hysaishi.cn/Article/details/gttxbotulr.html

TypeScript ..... 212
来源：http://dali.yj202588.top/Article/details/gtehvriqjo.html

Java ........... 212
来源：http://dali.bjfxy.top/Article/details/gtphgycgoj.html

Go ............. 212
来源：http://dali.nanxuanxn.top/Article/details/gtodhspnqw.html

Ruby ........... 212
来源：http://dali.zhongyouzk.top/Article/details/gtfuxdyqqn.html

C# ............. 212
来源：http://dali.tianlin.xyz/Article/details/gtgqebzokf.html

C .............. 30
来源：http://dali.havefunace.top/Article/details/gtvndzzmnb.html

C++ ............ 30
来源：http://dali.birdmap.top/Article/details/gtouxrgepo.html

SQL ............ 90
来源：http://dali.fzhhl.top/Article/details/gtvltqhnyj.html

Bash ........... 80
来源：http://dali.yvedp.cn/Article/details/gtworuotzd.html

Kotlin ......... 15
来源：http://dali.gaohongyu789.top/Article/details/gthmvmadfv.html

Swift .......... 15
来源：http://dali.yvedp.cn/Article/details/gtysrzaxus.html

Lua ............ 10
来源：http://dali.hammf.cn/Article/details/gtirsrbdch.html

Perl ........... 10
来源：http://dali.smart0.xyz/Article/details/gtxwzecswx.html

Scala .......... 10
来源：http://dali.yongpay.top/Article/details/gthbyphqvz.html

------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gtmwsjzvgm.html

合计 ........... 2106 条
来源：http://dali.cucudq.cn/Article/details/gtbuenrhtm.html

按章节统计：
来源：http://dali.kuanghao11.cn/Article/details/gthxopfjfk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hnqzz.top/Article/details/gtkfyyaorb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.kuanghao11.cn/Article/details/gtundbfxvg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cdnleiting.top/Article/details/gtfhuojfop.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.feifeiyinyue.top/Article/details/gthifenimf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.redwolf501.top/Article/details/gtknreguyx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhiwuduotai.top/Article/details/gtzraphtiu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tian-w.cn/Article/details/gtcruhpogk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.aizwys.cn/Article/details/gtccmnwsng.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gtiiqqigmz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jlsjyb.cn/Article/details/gtyagqerkx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gtyomhuzok.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gtjtdjrlgg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gtyxbhpddl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj20258888.top/Article/details/gtrzddvfmr.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jinghuilouyu.cn/Article/details/gtyuqaqzbt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gteuifpwbs.html

Q SQL 专题                              90
来源：http://dali.vqdsnc.cn/Article/details/gtewdmmfgp.html

R Bash 专题                             80
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzcoxdqv.html

S C / C++ 专题                          60
来源：http://dali.yongpay.top/Article/details/gttfhqudft.html

T 其他语言补充                          60
来源：http://dali.sweek.top/Article/details/gtgcpmmjqv.html

U 高频实用片段                         120
来源：http://dali.kuanghao11.cn/Article/details/gtzmskpopl.html

------------------------------------
来源：http://dali.hammf.cn/Article/details/gtcbljrqfy.html

合计                                  2106 条
来源：http://dali.zhixingplan.top/Article/details/gtpzmtpjyn.html

--------------------------------------------------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gthorcwojl.html

使用提醒
来源：http://dali.cdnleiting.top/Article/details/gtjrwjdxqc.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtzyfikwxo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.9152youxi.cn/Article/details/gthkbduthq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.redwolf501.top/Article/details/gtufgdpgfv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.quarkkingdee.top/Article/details/gtumebbgcm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.tianlin.xyz/Article/details/gtvhjaecjz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.daria6918.cn/Article/details/gtsltthsys.html

—— 文件结束 ——
来源：http://dali.guowangkeji.top/Article/details/gtktgjuwki.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtqsqffwmu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrrqdled.html

Common Programming Examples Cheat Book
来源：http://dali.guannengcc.top/Article/details/gtqzstzwlj.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gthgxuuifd.html

【收录内容】
来源：http://dali.hongshengwenyu.top/Article/details/gtmfzapbdj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ydzc1.top/Article/details/gtldtphlel.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhoulong.xyz/Article/details/gtwhcjtgja.html

SQL · Bash · C · C++
来源：http://dali.snrcjt.cn/Article/details/gtjrufkzpw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zdqjudy.top/Article/details/gtasjcfkye.html

【使用说明】
来源：http://dali.yanxiufei.cn/Article/details/gthxspdbty.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yj202588.top/Article/details/gthynvweuq.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yangfankeji.com/Article/details/gtmoasjsoq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xuetiantiany.cn/Article/details/gtlabhzclw.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shuidangran.top/Article/details/gtqetcgwpf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.gzhubu.top/Article/details/gttcybuqzq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yanxiufei.cn/Article/details/gtwlbhpcqi.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.nanxinkj.top/Article/details/gtkqsxijri.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.wangdashe.top/Article/details/gtsuwnmnxh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ydzc1.top/Article/details/gtlfezehsl.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.0kj1m.cn/Article/details/gtigvagfab.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhoulong.xyz/Article/details/gtmrbzxpes.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.fzhhl.top/Article/details/gtybkboftz.html

【文件统计】
来源：http://dali.tian-w.cn/Article/details/gtjglgmsam.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.chenjidiqi.icu/Article/details/gtaqguiykk.html

--------------------------------------------------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gtpjoryphl.html

目  录
来源：http://dali.dashuyun.cn/Article/details/gtnorkguxo.html

--------------------------------------------------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtgmaiqrol.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.dianchejie.cn/Article/details/gtwwwjaaud.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.fengsongda.top/Article/details/gtxcfrqjcr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzyechqm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ppjwa.cn/Article/details/gtslwjtmod.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.havefunace.top/Article/details/gtuuhflmsz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtxbbbselx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.chenzaomai.com/Article/details/gteimlbuea.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.316326.xyz/Article/details/gtqdqbnaas.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gtcwxaqtxo.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.fengsongda.top/Article/details/gtfdmgstrq.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shuidangran.top/Article/details/gtzithlyjr.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cashguo.top/Article/details/gtaiuidknv.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jiagoushi.top/Article/details/gtqdzifbyn.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.ydzc1.top/Article/details/gtkzaximbf.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xinyue.icu/Article/details/gtxoikkvma.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.bjfxy.top/Article/details/gtvzqsyztx.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtfghalojw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.sufxvd.cn/Article/details/gtqklsmiry.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yongpay.top/Article/details/gtnvamopap.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.vqdsnc.cn/Article/details/gteaukjrto.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.cqqwz.cn/Article/details/gtsdnuvnna.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtxvbttfex.html

A. 基础语法与类型
来源：http://dali.aizwys.cn/Article/details/gttvyxebbf.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtbzbeigqf.html

[A01] Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtzksifopp.html

Py:   print("Hello, World!")
来源：http://dali.ybcxt.top/Article/details/gtjaafchdm.html

PHP:  echo "Hello, World!";
来源：http://dali.feifeiyinyue.top/Article/details/gtyvfdhadh.html

JS:   console.log("Hello, World!");
来源：http://dali.svipenyu.cn/Article/details/gtcupyuhqn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hongshengwenyu.top/Article/details/gtdpkqdncl.html

Java: System.out.println("Hello, World!");
来源：http://dali.yueranfly.top/Article/details/gtnmvatykw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.nanxinkj.top/Article/details/gtgfhdmhei.html

Ruby: puts "Hello, World!"
来源：http://dali.zycfv.cn/Article/details/gtgaaxlmth.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.fengsongda.top/Article/details/gtimppfjaq.html

[A02] 变量声明与赋值
来源：http://dali.xziqi.cn/Article/details/gtgmhovobs.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jiagoushi.top/Article/details/gtsrbgypls.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zycfv.cn/Article/details/gtsqylegdm.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ydzc1.top/Article/details/gtybollrod.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hysaishi.cn/Article/details/gtwewumdjv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yanxiufei.cn/Article/details/gtzaimwpnn.html

Go:   name := "Alex"; age := 20
来源：http://dali.vqdsnc.cn/Article/details/gtysormloy.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yongpay.top/Article/details/gtxkoziqkj.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.tanke756.top/Article/details/gtbutoftme.html

[A03] 常量定义
来源：http://dali.wangdashe.top/Article/details/gtrjragoac.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhoulong.xyz/Article/details/gtcksylpqo.html

PHP:  const PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gthibdwmnz.html

JS:   const PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntpaexdv.html

TS:   const PI: number = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtxyhxbpvs.html

Java: static final double PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gtcxjhilto.html

Go:   const PI = 3.14159
来源：http://dali.dashuyun.cn/Article/details/gtvdcmodxx.html

Ruby: PI = 3.14159
来源：http://dali.9152youxi.cn/Article/details/gtrihwadhl.html

C#:   const double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gtvxwzcnld.html

[A04] 判断变量类型
来源：http://dali.yanxiufei.cn/Article/details/gtwgqirskx.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.pycfn.com/Article/details/gtgsqywlgu.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.chenzaomai.com/Article/details/gtlefsiqan.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.ybcxt.top/Article/details/gtqbgiqrju.html

TS:   typeof x; x instanceof Date
来源：http://dali.bjfxy.top/Article/details/gtkxsjetgp.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.iojbl.cn/Article/details/gtkgtfjorf.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hnqzz.top/Article/details/gtwxwuybwh.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.bjfxy.top/Article/details/gtvcuxsvix.html

C#:   x.GetType().Name; x is int
来源：http://dali.c1oappe.top/Article/details/gthytufwnz.html

[A05] 整数除法与取模
来源：http://dali.ppjwa.cn/Article/details/gtyoemjlmp.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.shuidangran.top/Article/details/gtfpomjqdr.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ydzc1.top/Article/details/gtvmnzrbxf.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gtwwgrlkrb.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gtvkaimycq.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdizujqkk.html

Go:   7 / 2; 7 % 2
来源：http://dali.wangshuangyany.cn/Article/details/gtugaoacgx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.smart0.xyz/Article/details/gtmvffevet.html

C#:   7 / 2; 7 % 2
来源：http://dali.sysykeji.top/Article/details/gtavsmbrwc.html

[A06] 字符串转数字
来源：http://dali.sufxvd.cn/Article/details/gtsloqfwxx.html

Py:   int("42"); float("3.14")
来源：http://dali.fzhhl.top/Article/details/gtfhrfnwqy.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.shuidangran.top/Article/details/gtkprinvjs.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yj20258888.top/Article/details/gtavcndytv.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hywenlv.cn/Article/details/gtlotrfydz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.c1oappe.top/Article/details/gtcwfbyshd.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdkoftzd.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.nanxinkj.top/Article/details/gtklbuorww.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhixingplan.top/Article/details/gtbbvhnlbe.html

[A07] 数字转字符串
来源：http://dali.xinyue.icu/Article/details/gticxvpuik.html

Py:   str(42)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwdzldbf.html

PHP:  (string) 42; strval(42)
来源：http://dali.c1oappe.top/Article/details/gttaxegqin.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gtcqskbtdp.html

TS:   String(42)
来源：http://dali.zhengqikj.top/Article/details/gtheevygjp.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yuxming.cn/Article/details/gtpznckjtl.html

Go:   strconv.Itoa(42)
来源：http://dali.yj20258.top/Article/details/gtvaccdecz.html

Ruby: 42.to_s
来源：http://dali.cashguo.top/Article/details/gtzdsbcxxi.html

C#:   42.ToString()
来源：http://dali.yangfankeji.com/Article/details/gtkdkyuzxj.html

[A08] 取整与四舍五入
来源：http://dali.zhongyouzk.top/Article/details/gtunoshjvd.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jqgfzy.top/Article/details/gtqgfxnxhw.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.dianchejie.cn/Article/details/gtgskkzldm.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.nwbrower.top/Article/details/gtyshihbbw.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.gogol.net.cn/Article/details/gtbxqishrq.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jinqigufen.top/Article/details/gtpyoharoq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.9152youxi.cn/Article/details/gtiynkhtnz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.chenjidiqi.icu/Article/details/gtdrsmmygi.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jyoumei.cn/Article/details/gthvyaeqqw.html

[A09] 绝对值与最大最小值
来源：http://dali.zhoulong.xyz/Article/details/gtnrokuiss.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtbwbbqldw.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hnqzz.top/Article/details/gtvgyioijs.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gtfxkzpdmy.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gtmbtzwqyc.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gtvdkssgqi.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhoulong.xyz/Article/details/gtatdkyqol.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.mhx1999.top/Article/details/gthieduuzd.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.bjfxy.top/Article/details/gtjsuqmees.html

[A10] 生成随机数
来源：http://dali.daria6918.cn/Article/details/gtyjsjhtmv.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yongpay.top/Article/details/gtzcuotrlt.html

PHP:  random_int(1, 100);
来源：http://dali.yongpay.top/Article/details/gtpfmtedlb.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.smart0.xyz/Article/details/gtwgwrcipn.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.andypj.xyz/Article/details/gtjhmzovqn.html

Java: new Random().nextInt(100) + 1
来源：http://dali.guannengcc.top/Article/details/gtajatevjh.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gtewknbrun.html

Ruby: rand(1..100)
来源：http://dali.wangdashe.top/Article/details/gtdwhcgoua.html

C#:   new Random().Next(1, 101)
来源：http://dali.gotoacloud.top/Article/details/gtcvqlkuto.html

[A11] 条件表达式（三元）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqnkwrgo.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhengqikj.top/Article/details/gtxjqgyvgr.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.daria6918.cn/Article/details/gtsnlmytmx.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.iojbl.cn/Article/details/gtbpgaaajm.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.havefunace.top/Article/details/gtwaloaulf.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhixingplan.top/Article/details/gtvrefeovw.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.guannengcc.top/Article/details/gtndoeifph.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.cashguo.top/Article/details/gtcxpcuokd.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.meibo888.top/Article/details/gtpuieffuq.html

[A12] 字符串插值 / 格式化
来源：http://dali.mhx1999.top/Article/details/gtuualgacn.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.chenjidiqi.icu/Article/details/gtzumvxuye.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yuanzhike.top/Article/details/gthbczevzc.html

JS:   `Hello, ${name}!`
来源：http://dali.ydzc1.top/Article/details/gtutacdxas.html

TS:   `Hello, ${name}!`
来源：http://dali.aibaodan.cn/Article/details/gtlfcpmceb.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.smart0.xyz/Article/details/gtefjgmplg.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.cqqwz.cn/Article/details/gtcfrrntnf.html

Ruby: "Hello, #{name}!"
来源：http://dali.andypj.xyz/Article/details/gtpdextmzg.html

C#:   $"Hello, {name}!"
来源：http://dali.chenlongwang.top/Article/details/gtkxdwcbfk.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.quarkkingdee.top/Article/details/gtaiwlphjw.html

Py:   "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gtpppfmrvq.html

PHP:  "第一行\n第二行"
来源：http://dali.cdnleiting.top/Article/details/gttixsqqbb.html

JS:   "第一行\n第二行"
来源：http://dali.hfpthk.cn/Article/details/gtaayzzsbu.html

TS:   "第一行\n第二行"
来源：http://dali.shangyingyoupin.top/Article/details/gtjteqjzib.html

Java: "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gtsxgnvydg.html

Go:   "第一行\n第二行"
来源：http://dali.pengpengdd.cyou/Article/details/gtweonyqhw.html

Ruby: "第一行\n第二行"
来源：http://dali.ivvv.top/Article/details/gtydirxmdk.html

C#:   "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gtvfzdrtll.html

[A14] 注释写法
来源：http://dali.gzhubu.top/Article/details/gtgwwazqbp.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.dianchejie.cn/Article/details/gtriayjicm.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jiagoushi.top/Article/details/gtjkswougg.html

JS:   // 单行；/* 多行 */
来源：http://dali.tian-w.cn/Article/details/gthmtdsikl.html

TS:   // 单行；/* 多行 */
来源：http://dali.chenjidiqi.icu/Article/details/gtfzyynfin.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhengqikj.top/Article/details/gtouodcgtd.html

Go:   // 单行；/* 多行 */
来源：http://dali.yongpay.top/Article/details/gtofzuacmy.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhongyouzk.top/Article/details/gtalwhialr.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhoulong.xyz/Article/details/gtwybtlyku.html

[A15] 空值判断与默认值
来源：http://dali.guowangkeji.top/Article/details/gtqgqdrpea.html

Py:   value = data or "默认值"
来源：http://dali.guannengcc.top/Article/details/gtlbzgesci.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhixingplan.top/Article/details/gtcowkkxfj.html

JS:   const value = data ?? "默认值";
来源：http://dali.haohaochexian.top/Article/details/gtegaoolyt.html

TS:   const value = data ?? "默认值";
来源：http://dali.tian-w.cn/Article/details/gtdcflquxf.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.iojbl.cn/Article/details/gtcavolivb.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.hnqzz.top/Article/details/gtbdakmqev.html

Ruby: value = data || "默认值"
来源：http://dali.tianlin.xyz/Article/details/gtzstuvbci.html

C#:   var value = data ?? "默认值";
来源：http://dali.jyoumei.cn/Article/details/gtaboibljc.html

[A16] 真假值判断规则
来源：http://dali.zhixingplan.top/Article/details/gtlprhekyn.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.cdnleiting.top/Article/details/gtzmjbigay.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.guannengcc.top/Article/details/gtownglfcy.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhongyouzk.top/Article/details/gtzzlqeopd.html

TS:   if (!x) {}
来源：http://dali.cqqwz.cn/Article/details/gtrjioaxsy.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jqgufenzy.top/Article/details/gtiqkrxheq.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.nanxinkj.top/Article/details/gtikydplsm.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.nwbrower.top/Article/details/gtzfuplcon.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.cucudq.cn/Article/details/gtvikuiyyl.html

[A17] 位运算
来源：http://dali.ehwqpu.com/Article/details/gtfkfbuzsd.html


<!-- 参考信息 -->