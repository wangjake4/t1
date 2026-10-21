代发 wailian999

[U97] JS：并发请求
来源：http://dali.shangyingyoupin.top/Article/details/gtkbimgjks.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtzapiprkd.html

[U98] JS：fetch 带 JSON
来源：http://dali.guowangkeji.top/Article/details/gtsvxzkgcc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jinqigufen.top/Article/details/gtasfcgotc.html

[U99] JS：事件监听
来源：http://dali.gaohongyu789.top/Article/details/gtpvuwewnn.html

el.addEventListener("click", e => {})
来源：http://dali.hnqzz.top/Article/details/gtozkdomhz.html

[U100] JS：DOM 查询
来源：http://dali.jinqigufen.top/Article/details/gtbdnnnynt.html

document.querySelector(".item")
来源：http://dali.guannengcc.top/Article/details/gtgytkhqqy.html

[U101] JS：classList 操作
来源：http://dali.yanxiufei.cn/Article/details/gtjjnndkjl.html

el.classList.toggle("active")
来源：http://dali.wangdashe.top/Article/details/gthduhskzr.html

[U102] JS：本地存储
来源：http://dali.hywenlv.cn/Article/details/gtcisvuirq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.chenjidiqi.icu/Article/details/gtmfraguet.html

[U103] JS：定时器
来源：http://dali.yangfankeji.com/Article/details/gtpedhtphj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gzhubu.top/Article/details/gtipmsrrgj.html

[U104] JS：防抖
来源：http://dali.daria6918.cn/Article/details/gtoiaksory.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gthcpdtyna.html

[U105] JS：节流
来源：http://dali.hnxiangtu.top/Article/details/gtruzmadeu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.snrcjt.cn/Article/details/gtqysrciaf.html

[U106] JS：日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gtruadqejp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.havefunace.top/Article/details/gtoywcujtt.html

[U107] JS：数字千分位
来源：http://dali.shuidangran.top/Article/details/gtgsfrbkgb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.chenlongwang.top/Article/details/gtozjghesd.html

[U108] JS：随机整数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwapcnvl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ehwqpu.com/Article/details/gtzilruskx.html

[U109] JS：数组分组
来源：http://dali.fengsongda.top/Article/details/gtmakhdvxz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yonumen.top/Article/details/gtkztjsiel.html

[U110] JS：数组分块
来源：http://dali.meibo888.top/Article/details/gtmobwjfjj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yonumen.top/Article/details/gtbwgoaecd.html

[U111] JS：对象转 Map
来源：http://dali.yj202588.top/Article/details/gtsqgkvptr.html

new Map(Object.entries(obj))
来源：http://dali.shuidangran.top/Article/details/gtsuwhjkad.html

[U112] JS：字符串补位
来源：http://dali.jyoumei.cn/Article/details/gtcchuisgl.html

"7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtiazadbwk.html

[U113] JS：正则替换全部
来源：http://dali.daria6918.cn/Article/details/gtxowhepfu.html

s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuavxtnqb.html

[U114] JS：JSON 深比较
来源：http://dali.meibo888.top/Article/details/gtytezibog.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ydzc1.top/Article/details/gtdpqpppvi.html

[U115] JS：生成 UUID
来源：http://dali.zhongyouzk.top/Article/details/gthhhhvulz.html

crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtgurvcyoe.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.redwolf501.top/Article/details/gtuxhfmdyt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvgjkhwv.html

[U117] JS：单元测试
来源：http://dali.ppjwa.cn/Article/details/gtrqepotfl.html

npm i -D vitest;  npx vitest
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigyqzczw.html

[U118] JS：开发服务器
来源：http://dali.iojbl.cn/Article/details/gtaoxlfdsp.html

npm i -D vite;  npx vite
来源：http://dali.xinyue.icu/Article/details/gtdmeltfun.html

[U119] JS：生产构建
来源：http://dali.zdqjudy.top/Article/details/gtcfwhenlz.html

npx vite build
来源：http://dali.jlsjyb.cn/Article/details/gtooawxjlo.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.dashuyun.cn/Article/details/gtkztxuiho.html

import.meta.env.VITE_API_URL
来源：http://dali.aizwys.cn/Article/details/gtidrlooju.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtbyeryyhm.html

统计汇总
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcdwqmptb.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtugffqrmi.html

按语言统计（条）：
来源：http://dali.pengpengdd.cyou/Article/details/gtcndpmnif.html

Python ......... 252
来源：http://dali.hnqzz.top/Article/details/gtawwvdrse.html

PHP ............ 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gtusivmpxl.html

JavaScript ..... 252
来源：http://dali.hammf.cn/Article/details/gtotdlfghn.html

TypeScript ..... 212
来源：http://dali.shanyushiyangtech.top/Article/details/gttuphfqvl.html

Java ........... 212
来源：http://dali.kuanghao11.cn/Article/details/gtkvthjicz.html

Go ............. 212
来源：http://dali.cdnleiting.top/Article/details/gtzixaatyf.html

Ruby ........... 212
来源：http://dali.vqdsnc.cn/Article/details/gtddjnsbxe.html

C# ............. 212
来源：http://dali.yangfankeji.com/Article/details/gtsriykgkf.html

C .............. 30
来源：http://dali.yanxiufei.cn/Article/details/gtrdxarkrx.html

C++ ............ 30
来源：http://dali.zhongyouzk.top/Article/details/gtbkqcpqly.html

SQL ............ 90
来源：http://dali.wangdashe.top/Article/details/gtfqmmaijl.html

Bash ........... 80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmbyktxp.html

Kotlin ......... 15
来源：http://dali.fzhhl.top/Article/details/gtskdpxkuf.html

Swift .......... 15
来源：http://dali.hywenlv.cn/Article/details/gtnxkialxa.html

Lua ............ 10
来源：http://dali.aizwys.cn/Article/details/gtaqdetyty.html

Perl ........... 10
来源：http://dali.aizwys.cn/Article/details/gtcdqqhlfw.html

Scala .......... 10
来源：http://dali.0kj1m.cn/Article/details/gtqcmobqvr.html

------------------------------------
来源：http://dali.mhx1999.top/Article/details/gtqwydaylw.html

合计 ........... 2106 条
来源：http://dali.birdmap.top/Article/details/gthszchdmc.html

按章节统计：
来源：http://dali.gzhubu.top/Article/details/gtydwfxool.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xuetiantiany.cn/Article/details/gtfobxcegh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.feifeiyinyue.top/Article/details/gtwudckleg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.aibaodan.cn/Article/details/gtcookipie.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hongshengwenyu.top/Article/details/gtzeeytdxw.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jiagoushi.top/Article/details/gtibhoihes.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jiagoushi.top/Article/details/gtzgiugjxj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.fengsongda.top/Article/details/gtixteuelw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.guannengcc.top/Article/details/gtuxrxooqp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gtkcyrahqp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jqgfzy.top/Article/details/gtdrjugqzy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gtpglmnvje.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gtveyxycct.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gtgpdxbgtj.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.birdmap.top/Article/details/gtptryeroz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.316326.xyz/Article/details/gtnhnqcsst.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gtzjyfvlly.html

Q SQL 专题                              90
来源：http://dali.yuanzhike.top/Article/details/gtziwvtuur.html

R Bash 专题                             80
来源：http://dali.guannengcc.top/Article/details/gtouvdvvgz.html

S C / C++ 专题                          60
来源：http://dali.cdnleiting.top/Article/details/gtblxmcwdl.html

T 其他语言补充                          60
来源：http://dali.0kj1m.cn/Article/details/gtwazbkwqm.html

U 高频实用片段                         120
来源：http://dali.mhx1999.top/Article/details/gtqtnwzcng.html

------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gticcqkppm.html

合计                                  2106 条
来源：http://dali.andypj.xyz/Article/details/gtivypyqez.html

--------------------------------------------------------------------------------
来源：http://dali.xuanzx.com/Article/details/gtgabvrtrt.html

使用提醒
来源：http://dali.chenlongwang.top/Article/details/gtbgqdxmpk.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gtvdvbjkqi.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.9152youxi.cn/Article/details/gtbnssakyu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.nanxinkj.top/Article/details/gtlxtayomf.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.chenzaomai.com/Article/details/gtzjewiaba.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.wangdashe.top/Article/details/gtlyvwzueg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.wangdashe.top/Article/details/gtogcxslux.html

—— 文件结束 ——
来源：http://dali.tian-w.cn/Article/details/gtilkiorwi.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtgrzpsxst.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jlsjyb.cn/Article/details/gtikvhigfi.html

Common Programming Examples Cheat Book
来源：http://dali.pengpengdd.cyou/Article/details/gtxafzywvb.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtpumjpzur.html

【收录内容】
来源：http://dali.svipenyu.cn/Article/details/gtobcvxayw.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shanyushiyangtech.top/Article/details/gtbakvygyb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yj20258.top/Article/details/gtkglufhti.html

SQL · Bash · C · C++
来源：http://dali.9152youxi.cn/Article/details/gtbsrnldbh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hongshengwenyu.top/Article/details/gtqlfhamaz.html

【使用说明】
来源：http://dali.wangshuangyany.cn/Article/details/gtnosrnskn.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shzxlz.cn/Article/details/gtvyikrsga.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yonumen.top/Article/details/gtwylvwrug.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.quarkkingdee.top/Article/details/gthdmnqlhq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpcanhxq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.shangyingyoupin.top/Article/details/gtlalnoaue.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.guannengcc.top/Article/details/gtoowhnrhm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.aibaodan.cn/Article/details/gttegqvigb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrloajlq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.pycfn.com/Article/details/gtdscnmlpr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.gogol.net.cn/Article/details/gtwzocpztp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.daria6918.cn/Article/details/gthblmyzbf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.haohaochexian.top/Article/details/gtnywyokvt.html

【文件统计】
来源：http://dali.9152youxi.cn/Article/details/gtungvbgfl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.guowangkeji.top/Article/details/gtgzoshejt.html

--------------------------------------------------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gttkdblxkz.html

目  录
来源：http://dali.xuetiantiany.cn/Article/details/gtyetjmvqe.html

--------------------------------------------------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gthvywbwjr.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.gogol.net.cn/Article/details/gtqvqxcnyz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yuanzhike.top/Article/details/gtenghljkm.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.316326.xyz/Article/details/gtabtqpnut.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yongpay.top/Article/details/gtvzpekdep.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.sufxvd.cn/Article/details/gtyucqhhtn.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.iojbl.cn/Article/details/gtwcqopqek.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yuxming.cn/Article/details/gtltgdmhul.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.gzhubu.top/Article/details/gtbnrelpta.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.gotoacloud.top/Article/details/gtqudldoqp.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.meibo888.top/Article/details/gtqakvduzq.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gtuzbkdyny.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gtusewkpqk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gthosiighr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhoulong.xyz/Article/details/gtwgmtyqwl.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.wangdashe.top/Article/details/gtiejthtls.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hywenlv.cn/Article/details/gtvgkyrieb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hnxiangtu.top/Article/details/gtrhmzjwvp.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cashguo.top/Article/details/gtiyxgnbld.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.gaohongyu789.top/Article/details/gtucxcyfdk.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dashuyun.cn/Article/details/gtsizxirif.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.svipenyu.cn/Article/details/gtvnafkjvi.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtragirccm.html

A. 基础语法与类型
来源：http://dali.jqgfzy.top/Article/details/gtaodjystg.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtigohwuhq.html

[A01] Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtykbqpoqf.html

Py:   print("Hello, World!")
来源：http://dali.hnxiangtu.top/Article/details/gtghbqxujq.html

PHP:  echo "Hello, World!";
来源：http://dali.hnqzz.top/Article/details/gtbjrmanfk.html

JS:   console.log("Hello, World!");
来源：http://dali.yonumen.top/Article/details/gtcweeytla.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.fengsongda.top/Article/details/gtkfrpywmv.html

Java: System.out.println("Hello, World!");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtooepijqt.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yuanzhike.top/Article/details/gtbvdyvlwc.html

Ruby: puts "Hello, World!"
来源：http://dali.zhiwuduotai.top/Article/details/gtkmokvkpp.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ybcxt.top/Article/details/gtgixoimkz.html

[A02] 变量声明与赋值
来源：http://dali.gotoacloud.top/Article/details/gtyntlhssc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.fengsongda.top/Article/details/gtahdtnkty.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yj202588.top/Article/details/gtpcsotyls.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ehwqpu.com/Article/details/gtzgkaqozd.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yj20258.top/Article/details/gtnkthyrvq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jinqigfzy.top/Article/details/gtkdssebdq.html

Go:   name := "Alex"; age := 20
来源：http://dali.wangdashe.top/Article/details/gttfoypjpd.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jlsjyb.cn/Article/details/gtnyuvcquf.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yj20258888.top/Article/details/gtjvxwpgcj.html

[A03] 常量定义
来源：http://dali.tian-w.cn/Article/details/gtsrgrkjti.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jyoumei.cn/Article/details/gtixwxfulv.html

PHP:  const PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtzuerbhio.html

JS:   const PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtdpzexpjw.html

TS:   const PI: number = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtyhmpgtpo.html

Java: static final double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtdqhkarop.html

Go:   const PI = 3.14159
来源：http://dali.dianchejie.cn/Article/details/gtowvktocf.html

Ruby: PI = 3.14159
来源：http://dali.cheryme.top/Article/details/gtybaderir.html

C#:   const double PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdcpuhwc.html

[A04] 判断变量类型
来源：http://dali.andypj.xyz/Article/details/gtlyupaqva.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xinyue.icu/Article/details/gtpjafqtaj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.kuanghao11.cn/Article/details/gthmrxvaby.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hnqzz.top/Article/details/gtikuowpls.html

TS:   typeof x; x instanceof Date
来源：http://dali.shuidangran.top/Article/details/gtnshoxlmz.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yuxming.cn/Article/details/gtzbrgmwzg.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.daria6918.cn/Article/details/gtvzpwfiir.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.dashuyun.cn/Article/details/gthiqvcaku.html

C#:   x.GetType().Name; x is int
来源：http://dali.ppjwa.cn/Article/details/gtddpoykgh.html

[A05] 整数除法与取模
来源：http://dali.zhengqikj.top/Article/details/gtwweomttn.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhoulong.xyz/Article/details/gtxdhhwfyg.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.bjfxy.top/Article/details/gtqxczwyjv.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gtuanjjcel.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gtokhfwlhx.html

Java: 7 / 2; 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gtyfejouif.html

Go:   7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gtzmmicmdt.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.guannengcc.top/Article/details/gtlwnmifks.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gtwmhetuav.html

[A06] 字符串转数字
来源：http://dali.yvedp.cn/Article/details/gtanxksjbw.html

Py:   int("42"); float("3.14")
来源：http://dali.c1oappe.top/Article/details/gtttimxnxj.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.xuetiantiany.cn/Article/details/gtckyesram.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.shzxlz.cn/Article/details/gtrmmxjgwq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.cheryme.top/Article/details/gtqsvoedpu.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.nanxuanxn.top/Article/details/gtplxlhmkv.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.0kj1m.cn/Article/details/gtyvmnuqhi.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.vqdsnc.cn/Article/details/gtdmtzoqun.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.nanxinkj.top/Article/details/gtndzntbhn.html

[A07] 数字转字符串
来源：http://dali.jyoumei.cn/Article/details/gttorigskr.html

Py:   str(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqcddumw.html

PHP:  (string) 42; strval(42)
来源：http://dali.xylfe.cn/Article/details/gtjgguitxz.html

JS:   String(42); (42).toString()
来源：http://dali.yonumen.top/Article/details/gtcjpchksc.html

TS:   String(42)
来源：http://dali.hnqzz.top/Article/details/gtfdjjssfd.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.aizwys.cn/Article/details/gtgzowxxph.html

Go:   strconv.Itoa(42)
来源：http://dali.dianchejie.cn/Article/details/gtnyxudpoy.html

Ruby: 42.to_s
来源：http://dali.svipenyu.cn/Article/details/gtkbqulbjn.html

C#:   42.ToString()
来源：http://dali.xziqi.cn/Article/details/gtxfgveibn.html

[A08] 取整与四舍五入
来源：http://dali.xinyue.icu/Article/details/gtodvwxokv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.cashguo.top/Article/details/gtgffgztnp.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zdqjudy.top/Article/details/gtfgcjftix.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.meibo888.top/Article/details/gtdtbozyoi.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.dianchejie.cn/Article/details/gtfhabgbsv.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jyoumei.cn/Article/details/gtahssxjep.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.daria6918.cn/Article/details/gtqjuwxuhx.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.mhx1999.top/Article/details/gtmtoaqupf.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.dashuyun.cn/Article/details/gtqoxcqsga.html

[A09] 绝对值与最大最小值
来源：http://dali.cdnleiting.top/Article/details/gtrdzqsvnt.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvybenjct.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.iojbl.cn/Article/details/gtwyuwdrpo.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.iojbl.cn/Article/details/gtuqnlzgil.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtitfcynyw.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.ydzc1.top/Article/details/gtpauopacb.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hfpthk.cn/Article/details/gtpszuzrrm.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jinqigufen.top/Article/details/gtbdrqesye.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.fzhhl.top/Article/details/gtnpepmpeg.html

[A10] 生成随机数
来源：http://dali.zdqjudy.top/Article/details/gtrorxcbhr.html

Py:   import random; random.randint(1, 100)
来源：http://dali.cdnleiting.top/Article/details/gtsxaplnrh.html

PHP:  random_int(1, 100);
来源：http://dali.tanke756.top/Article/details/gtkjvvxpeg.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yvedp.cn/Article/details/gtbnymfltm.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sysykeji.top/Article/details/gtihnbbisn.html

Java: new Random().nextInt(100) + 1
来源：http://dali.meibo888.top/Article/details/gteuozjeif.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hammf.cn/Article/details/gtwvigcrev.html

Ruby: rand(1..100)
来源：http://dali.haohaochexian.top/Article/details/gtvdzsexhd.html

C#:   new Random().Next(1, 101)
来源：http://dali.cheryme.top/Article/details/gtjkuznxug.html

[A11] 条件表达式（三元）
来源：http://dali.yueranfly.top/Article/details/gtpymtgwls.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.fzhhl.top/Article/details/gtvagdlpvo.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.haohaochexian.top/Article/details/gtitqwnzkg.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.aizwys.cn/Article/details/gtdjjybfys.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.316326.xyz/Article/details/gtrilorsxs.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xziqi.cn/Article/details/gtrgugymnj.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.quarkkingdee.top/Article/details/gteizhubnv.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejxvltgh.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.9152youxi.cn/Article/details/gtttuoptea.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gtvgunhknq.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yj20258888.top/Article/details/gteoicecig.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrpasira.html

JS:   `Hello, ${name}!`
来源：http://dali.nanxuanxn.top/Article/details/gtlohceqcp.html

TS:   `Hello, ${name}!`
来源：http://dali.mhx1999.top/Article/details/gtvglniymc.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.meibo888.top/Article/details/gtcvnwpyze.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.cdnleiting.top/Article/details/gtzvnlefff.html

Ruby: "Hello, #{name}!"
来源：http://dali.nanxuanxn.top/Article/details/gtwwqxxhsp.html

C#:   $"Hello, {name}!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqidcszir.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yuanzhike.top/Article/details/gtpoarsmbt.html

Py:   "第一行\n第二行"
来源：http://dali.jinghuilouyu.cn/Article/details/gthemfapgi.html

PHP:  "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gtdnmcewaj.html

JS:   "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gtmgyzoodc.html

TS:   "第一行\n第二行"
来源：http://dali.hywenlv.cn/Article/details/gtuxqvzejc.html

Java: "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gtkykxpvcb.html

Go:   "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gtafvimutt.html

Ruby: "第一行\n第二行"
来源：http://dali.yj202588.top/Article/details/gtklizldyq.html

C#:   "第一行\n第二行"
来源：http://dali.gaohongyu789.top/Article/details/gtwqeopqej.html

[A14] 注释写法
来源：http://dali.fengsongda.top/Article/details/gturnknpml.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabwljmyr.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.mhx1999.top/Article/details/gtgbvutkek.html

JS:   // 单行；/* 多行 */
来源：http://dali.chenzaomai.com/Article/details/gthvmtvbfc.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhongyouzk.top/Article/details/gtvkfjmclw.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.cucudq.cn/Article/details/gtpcnrforn.html

Go:   // 单行；/* 多行 */
来源：http://dali.andypj.xyz/Article/details/gteyszicwz.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hnqzz.top/Article/details/gtnujddhim.html

C#:   // 单行；/* 多行 */
来源：http://dali.wangdashe.top/Article/details/gtbtucuakd.html

[A15] 空值判断与默认值
来源：http://dali.yuxming.cn/Article/details/gtykiruiid.html

Py:   value = data or "默认值"
来源：http://dali.jianghu66.top/Article/details/gtzbrfoxyk.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.xuanzx.com/Article/details/gtvszpfztk.html

JS:   const value = data ?? "默认值";
来源：http://dali.bjfxy.top/Article/details/gtbdfiwuok.html

TS:   const value = data ?? "默认值";
来源：http://dali.sufxvd.cn/Article/details/gttwtclsss.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yuxming.cn/Article/details/gtkefpvrtz.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhixingplan.top/Article/details/gtapiqnrev.html

Ruby: value = data || "默认值"
来源：http://dali.tianlin.xyz/Article/details/gtjwzxymac.html

C#:   var value = data ?? "默认值";
来源：http://dali.shzxlz.cn/Article/details/gtaxmpvxjg.html

[A16] 真假值判断规则
来源：http://dali.hysaishi.cn/Article/details/gtrmvoavar.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jyoumei.cn/Article/details/gtaxwvdppl.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhixingplan.top/Article/details/gturvlsygs.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.cqqwz.cn/Article/details/gtjcykydzb.html

TS:   if (!x) {}
来源：http://dali.pengpengdd.cyou/Article/details/gthclktdre.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.pycfn.com/Article/details/gtjcpikddz.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.xuanzx.com/Article/details/gtgcpxzmhh.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jqgfzy.top/Article/details/gtebyliwxk.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.cucudq.cn/Article/details/gtrwwnwktq.html

[A17] 位运算
来源：http://dali.feifeiyinyue.top/Article/details/gthdplzakx.html


<!-- 参考信息 -->