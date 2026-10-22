代发 wailian999

[U101] JS：classList 操作
来源：http://dali.vqdsnc.cn/Article/details/gt2qzjupihy.html

el.classList.toggle("active")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sobxpfjv.html

[U102] JS：本地存储
来源：http://dali.yvedp.cn/Article/details/gt2wazkrbfn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.feifeiyinyue.top/Article/details/gt2odkuitsc.html

[U103] JS：定时器
来源：http://dali.yj202588.top/Article/details/gt2okdzxerm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yongpay.top/Article/details/gt2bkkfsxvx.html

[U104] JS：防抖
来源：http://dali.jqgufenzy.top/Article/details/gt2rvquwebk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xinyue.icu/Article/details/gt2jztteewa.html

[U105] JS：节流
来源：http://dali.xylfe.cn/Article/details/gt2ktcgovgb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xinyue.icu/Article/details/gt2fwclbimw.html

[U106] JS：日期格式化
来源：http://dali.snrcjt.cn/Article/details/gt2bvjadioj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hywenlv.cn/Article/details/gt2oqxhkofe.html

[U107] JS：数字千分位
来源：http://dali.yj20258888.top/Article/details/gt2nnfrzjrz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sysykeji.top/Article/details/gt2smzbhlwa.html

[U108] JS：随机整数
来源：http://dali.cqqwz.cn/Article/details/gt2dqccefed.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jqgufenzy.top/Article/details/gt2hsgigzyp.html

[U109] JS：数组分组
来源：http://dali.nwbrower.top/Article/details/gt2asmazscd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ybcxt.top/Article/details/gt2gnosatww.html

[U110] JS：数组分块
来源：http://dali.zhiwuduotai.top/Article/details/gt2nwofldaq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.nwbrower.top/Article/details/gt2klcystkr.html

[U111] JS：对象转 Map
来源：http://dali.hongshengwenyu.top/Article/details/gt2usohvvqk.html

new Map(Object.entries(obj))
来源：http://dali.yj20258.top/Article/details/gt2oyjxkgxd.html

[U112] JS：字符串补位
来源：http://dali.zdqjudy.top/Article/details/gt2ajocmzdy.html

"7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gt2iozyvvfs.html

[U113] JS：正则替换全部
来源：http://dali.nanxinkj.top/Article/details/gt2nvhgjbzq.html

s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gt2manunola.html

[U114] JS：JSON 深比较
来源：http://dali.kuanghao11.cn/Article/details/gt2ozfuncos.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.mhx1999.top/Article/details/gt2sjasosuf.html

[U115] JS：生成 UUID
来源：http://dali.hfpthk.cn/Article/details/gt2fnbmjsvd.html

crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gt2wumbompc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.havefunace.top/Article/details/gt2xjsrmruf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2uqjmrysy.html

[U117] JS：单元测试
来源：http://dali.aibaodan.cn/Article/details/gt2myeemhvn.html

npm i -D vitest;  npx vitest
来源：http://dali.iojbl.cn/Article/details/gt2wjmsqfnw.html

[U118] JS：开发服务器
来源：http://dali.cqqwz.cn/Article/details/gt2tordqsox.html

npm i -D vite;  npx vite
来源：http://dali.tianlin.xyz/Article/details/gt2wtezywgb.html

[U119] JS：生产构建
来源：http://dali.dianchejie.cn/Article/details/gt2sdrgasns.html

npx vite build
来源：http://dali.kuanghao11.cn/Article/details/gt2jtxiunts.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yueranfly.top/Article/details/gt2bnsliqxl.html

import.meta.env.VITE_API_URL
来源：http://dali.daxiang520.top/Article/details/gt2fskvqvqu.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2ucoovnym.html

统计汇总
来源：http://dali.yonumen.top/Article/details/gt2ibamssql.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2adnvodsz.html

按语言统计（条）：
来源：http://dali.gaohongyu789.top/Article/details/gt2bsrgfpil.html

Python ......... 252
来源：http://dali.yvedp.cn/Article/details/gt2cinwoqlx.html

PHP ............ 252
来源：http://dali.jiagoushi.top/Article/details/gt2homostaq.html

JavaScript ..... 252
来源：http://dali.hnqzz.top/Article/details/gt2wwgfrztz.html

TypeScript ..... 212
来源：http://dali.redwolf501.top/Article/details/gt2mwghxlnn.html

Java ........... 212
来源：http://dali.hywenlv.cn/Article/details/gt2tdrpbzld.html

Go ............. 212
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rxxirlto.html

Ruby ........... 212
来源：http://dali.dianchejie.cn/Article/details/gt2smoqebsy.html

C# ............. 212
来源：http://dali.snrcjt.cn/Article/details/gt2cqdgjuqj.html

C .............. 30
来源：http://dali.vqdsnc.cn/Article/details/gt2nstxnxzm.html

C++ ............ 30
来源：http://dali.jqgfzy.top/Article/details/gt2pwbkrqtf.html

SQL ............ 90
来源：http://dali.nanxuanxn.top/Article/details/gt2gvraifmu.html

Bash ........... 80
来源：http://dali.gotoacloud.top/Article/details/gt2outcrpvg.html

Kotlin ......... 15
来源：http://dali.dianchejie.cn/Article/details/gt2soixvjjq.html

Swift .......... 15
来源：http://dali.tian-w.cn/Article/details/gt2iqftydyr.html

Lua ............ 10
来源：http://dali.yangfankeji.com/Article/details/gt2xvyfanah.html

Perl ........... 10
来源：http://dali.zhiwuduotai.top/Article/details/gt2jxcjegqs.html

Scala .......... 10
来源：http://dali.nanxuanxn.top/Article/details/gt2ytjewbcz.html

------------------------------------
来源：http://dali.jinqigfzy.top/Article/details/gt2scizvggi.html

合计 ........... 2106 条
来源：http://dali.fzhhl.top/Article/details/gt2acvqyltu.html

按章节统计：
来源：http://dali.gzhubu.top/Article/details/gt2npzgczuz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jqgfzy.top/Article/details/gt2sjpemmeq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gt2xxwbipcb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.snrcjt.cn/Article/details/gt2kfoxagim.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.0kj1m.cn/Article/details/gt2wdntcwaf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.guannengcc.top/Article/details/gt2rekvlvtp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xylfe.cn/Article/details/gt2zforqrun.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gzhubu.top/Article/details/gt2dmorygjg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.meibo888.top/Article/details/gt2julotznm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gt2kkmffcho.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shuidangran.top/Article/details/gt2rjsbmdxe.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gt2ampdzgmi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.dianchejie.cn/Article/details/gt2usltyttj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gt2qgmedcpt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xnintezf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ppjwa.cn/Article/details/gt2dmdarqpn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gt2ggbgjpbq.html

Q SQL 专题                              90
来源：http://dali.wangdashe.top/Article/details/gt2xlufbwzb.html

R Bash 专题                             80
来源：http://dali.pycfn.com/Article/details/gt2bbvxaboi.html

S C / C++ 专题                          60
来源：http://dali.hammf.cn/Article/details/gt2khubljdn.html

T 其他语言补充                          60
来源：http://dali.quarkkingdee.top/Article/details/gt2qbwylkwk.html

U 高频实用片段                         120
来源：http://dali.iojbl.cn/Article/details/gt2jqacqaxj.html

------------------------------------
来源：http://dali.xinyue.icu/Article/details/gt2anpdqnij.html

合计                                  2106 条
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oqskuuch.html

--------------------------------------------------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2spiemnel.html

使用提醒
来源：http://dali.yvedp.cn/Article/details/gt2pfhgzyrt.html

--------------------------------------------------------------------------------
来源：http://dali.xziqi.cn/Article/details/gt2nkbqolax.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.sufxvd.cn/Article/details/gt2ureugwui.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hywenlv.cn/Article/details/gt2bhmdtcnv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.daria6918.cn/Article/details/gt2iwoatkds.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xuanzx.com/Article/details/gt2maueusvy.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ivvv.top/Article/details/gt2uoomeieq.html

—— 文件结束 ——
来源：http://dali.kuanghao11.cn/Article/details/gt2qytqonej.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2tnhlvrsx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.aizwys.cn/Article/details/gt2tsgcnere.html

Common Programming Examples Cheat Book
来源：http://dali.zhiwuduotai.top/Article/details/gt2vfdfsobr.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2omaivila.html

【收录内容】
来源：http://dali.havefunace.top/Article/details/gt2uyofodon.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.daxiang520.top/Article/details/gt2cwkqospy.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhongyouzk.top/Article/details/gt2ceadixdh.html

SQL · Bash · C · C++
来源：http://dali.tian-w.cn/Article/details/gt2qbmgsdew.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.shzxlz.cn/Article/details/gt2cvaptuxz.html

【使用说明】
来源：http://dali.tian-w.cn/Article/details/gt2iyoyrqod.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhongyouzk.top/Article/details/gt2dqhqabfv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.daxiang520.top/Article/details/gt2voaxgteg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.sxryk.cn/Article/details/gt2fwoxjvmt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2moevewyf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ylwtonvi.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhiwuduotai.top/Article/details/gt2aezvdphx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gotoacloud.top/Article/details/gt2iqpciqhx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hongshengwenyu.top/Article/details/gt2qtutlazh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cheryme.top/Article/details/gt2zudkbrml.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.gogol.net.cn/Article/details/gt2yjqtaslf.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hongshengwenyu.top/Article/details/gt2bdrozofh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.smart0.xyz/Article/details/gt2jxqxpryt.html

【文件统计】
来源：http://dali.haohaochexian.top/Article/details/gt2yoasxvtq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xinyue.icu/Article/details/gt2pefvlpyd.html

--------------------------------------------------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gt2knlzvcrv.html

目  录
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ofsssdyv.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gt2aropqcqn.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ysrglcit.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jqgfzy.top/Article/details/gt2kvwodfdm.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.fzhhl.top/Article/details/gt2mvtigjap.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.haohaochexian.top/Article/details/gt2rsaebduf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2zdgeeqpz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wtxqhllo.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jinqigufen.top/Article/details/gt2ajrkpdzk.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yvedp.cn/Article/details/gt2kbyybhyu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zycfv.cn/Article/details/gt2mfcthjcp.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ehwqpu.com/Article/details/gt2nuokwdge.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2jpqaleia.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2bkobkozu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2omaltudp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xylfe.cn/Article/details/gt2dylhyddh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yuanzhike.top/Article/details/gt2cutncyvt.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhengqikj.top/Article/details/gt2xdbyziij.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yueranfly.top/Article/details/gt2axugpxzv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.wangdashe.top/Article/details/gt2bcyegqkz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hysaishi.cn/Article/details/gt2orfujnbe.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258.top/Article/details/gt2pgvtailj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwlownu.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2soaddtwm.html

A. 基础语法与类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2epzupnmj.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2dvdhrqwn.html

[A01] Hello World
来源：http://dali.gaohongyu789.top/Article/details/gt2zepzbipl.html

Py:   print("Hello, World!")
来源：http://dali.cdnleiting.top/Article/details/gt2kmasslie.html

PHP:  echo "Hello, World!";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qsapahzf.html

JS:   console.log("Hello, World!");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ablwjene.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.0kj1m.cn/Article/details/gt2yqmkwesy.html

Java: System.out.println("Hello, World!");
来源：http://dali.cheryme.top/Article/details/gt2nfkfgtbh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.smart0.xyz/Article/details/gt2gyswkbyv.html

Ruby: puts "Hello, World!"
来源：http://dali.andypj.xyz/Article/details/gt2jjwoumtj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.havefunace.top/Article/details/gt2yjnrjype.html

[A02] 变量声明与赋值
来源：http://dali.wangshuangyany.cn/Article/details/gt2kkzqkixb.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.tanke756.top/Article/details/gt2rhbnkljj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.tianlin.xyz/Article/details/gt2htwdpakw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2badkevtr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gotoacloud.top/Article/details/gt2rirvbidu.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xafcmqgg.html

Go:   name := "Alex"; age := 20
来源：http://dali.hammf.cn/Article/details/gt2grlldzzw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.mhx1999.top/Article/details/gt2gkeaxkbc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jinqigfzy.top/Article/details/gt2xowmgjvj.html

[A03] 常量定义
来源：http://dali.vqdsnc.cn/Article/details/gt2ngzkeaiv.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yanxiufei.cn/Article/details/gt2dpjeipqh.html

PHP:  const PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gt2vwioqrne.html

JS:   const PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gt2tdojqjzw.html

TS:   const PI: number = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gt2wxgjjfwp.html

Java: static final double PI = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gt2blwfpazx.html

Go:   const PI = 3.14159
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zqocbzzb.html

Ruby: PI = 3.14159
来源：http://dali.jqgfzy.top/Article/details/gt2ycflxpdk.html

C#:   const double PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gt2qstnmjzy.html

[A04] 判断变量类型
来源：http://dali.yueranfly.top/Article/details/gt2nttvotng.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ivvv.top/Article/details/gt2xmspzvej.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cashguo.top/Article/details/gt2vubnsbsa.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xziqi.cn/Article/details/gt2oifcygyd.html

TS:   typeof x; x instanceof Date
来源：http://dali.jqgfzy.top/Article/details/gt2jvqnzvky.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.smart0.xyz/Article/details/gt2etoysqjr.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xuetiantiany.cn/Article/details/gt2hfdimdem.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yangfankeji.com/Article/details/gt2pwwrakgx.html

C#:   x.GetType().Name; x is int
来源：http://dali.nwbrower.top/Article/details/gt2fpyxated.html

[A05] 整数除法与取模
来源：http://dali.yuxming.cn/Article/details/gt2mzqbnjwq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jqgufenzy.top/Article/details/gt2vsryqkco.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ydzc1.top/Article/details/gt2muztsgbl.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gt2evgbgwsx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hnqzz.top/Article/details/gt2sravtirx.html

Java: 7 / 2; 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gt2npkwzqkg.html

Go:   7 / 2; 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gt2kaeurjcg.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gt2qvolxgcl.html

C#:   7 / 2; 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gt2pbhmkqzw.html

[A06] 字符串转数字
来源：http://dali.jyoumei.cn/Article/details/gt2maqrrzvd.html

Py:   int("42"); float("3.14")
来源：http://dali.ivvv.top/Article/details/gt2svzcuzxo.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.bjfxy.top/Article/details/gt2iqtlospw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.cqqwz.cn/Article/details/gt2qgzrfhph.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jlsjyb.cn/Article/details/gt2avqmoifi.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.hongshengwenyu.top/Article/details/gt2smloksly.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cvjllnmj.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.feifeiyinyue.top/Article/details/gt2qmcktast.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.shangyingyoupin.top/Article/details/gt2qvyiqpcq.html

[A07] 数字转字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2dlnpcrmo.html

Py:   str(42)
来源：http://dali.xylfe.cn/Article/details/gt2gbzspdkb.html

PHP:  (string) 42; strval(42)
来源：http://dali.ppjwa.cn/Article/details/gt2nrbnzybh.html

JS:   String(42); (42).toString()
来源：http://dali.yvedp.cn/Article/details/gt2iksniixf.html

TS:   String(42)
来源：http://dali.jyoumei.cn/Article/details/gt2xuovzevz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2adcaskiv.html

Go:   strconv.Itoa(42)
来源：http://dali.fzhhl.top/Article/details/gt2kjqtzsph.html

Ruby: 42.to_s
来源：http://dali.cqqwz.cn/Article/details/gt2ihtxhhtp.html

C#:   42.ToString()
来源：http://dali.redwolf501.top/Article/details/gt2zakzbtis.html

[A08] 取整与四舍五入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uoyuzoqs.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ydzc1.top/Article/details/gt2lpivxlxc.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jlsjyb.cn/Article/details/gt2ezbvwzsr.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zycfv.cn/Article/details/gt2bjfmbocp.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.tanke756.top/Article/details/gt2esfvulxh.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.svipenyu.cn/Article/details/gt2pybbtzck.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.shzxlz.cn/Article/details/gt2cuvgmxul.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhoulong.xyz/Article/details/gt2dfgbfuyh.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhengqikj.top/Article/details/gt2djblhbht.html

[A09] 绝对值与最大最小值
来源：http://dali.nanxinkj.top/Article/details/gt2qwmxvtmt.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yuxming.cn/Article/details/gt2igjwgjfz.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2adwgdcts.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.wangdashe.top/Article/details/gt2licogdxp.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.meibo888.top/Article/details/gt2nivnfcob.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2nksukbbw.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.ivvv.top/Article/details/gt2ulfnraxe.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.hnqzz.top/Article/details/gt2uyebtimu.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.bjfxy.top/Article/details/gt2xchedzkr.html

[A10] 生成随机数
来源：http://dali.yangfankeji.com/Article/details/gt2mtvyzmmf.html

Py:   import random; random.randint(1, 100)
来源：http://dali.xuanzx.com/Article/details/gt2qzcpesva.html

PHP:  random_int(1, 100);
来源：http://dali.snrcjt.cn/Article/details/gt2jzjtjgmy.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.nanxuanxn.top/Article/details/gt2zmvvmtiq.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2olzawpav.html

Java: new Random().nextInt(100) + 1
来源：http://dali.cdnleiting.top/Article/details/gt2nureswud.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.gogol.net.cn/Article/details/gt2phjxcfxv.html

Ruby: rand(1..100)
来源：http://dali.smart0.xyz/Article/details/gt2ebhtoolw.html

C#:   new Random().Next(1, 101)
来源：http://dali.dianchejie.cn/Article/details/gt2xpftsdfe.html

[A11] 条件表达式（三元）
来源：http://dali.fzhhl.top/Article/details/gt2eucprbkz.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.nwbrower.top/Article/details/gt2zswqvczm.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gt2hyslaeil.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.chenjidiqi.icu/Article/details/gt2mcmnsuba.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.guowangkeji.top/Article/details/gt2krecyvox.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdwdmosf.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtsqekz.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.nwbrower.top/Article/details/gt2dgbysttd.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.ydzc1.top/Article/details/gt2rjcwnueu.html

[A12] 字符串插值 / 格式化
来源：http://dali.yanxiufei.cn/Article/details/gt2dahfntbk.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yj202588.top/Article/details/gt2nvgxukmb.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynojcoyq.html

JS:   `Hello, ${name}!`
来源：http://dali.xziqi.cn/Article/details/gt2bkgrbneh.html

TS:   `Hello, ${name}!`
来源：http://dali.redwolf501.top/Article/details/gt2xrhanlzz.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yj20258.top/Article/details/gt2ydcmrdiy.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.ybcxt.top/Article/details/gt2twagkiud.html

Ruby: "Hello, #{name}!"
来源：http://dali.yuanzhike.top/Article/details/gt2scehaxvd.html

C#:   $"Hello, {name}!"
来源：http://dali.yj20258888.top/Article/details/gt2luahdrjt.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.jinqigufen.top/Article/details/gt2pjatigou.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2dejhlhqd.html

PHP:  "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gt2uefaqczk.html

JS:   "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gt2viiqmajf.html

TS:   "第一行\n第二行"
来源：http://dali.jqgufenzy.top/Article/details/gt2ndzhspvp.html

Java: "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aueioesr.html

Go:   "第一行\n第二行"
来源：http://dali.daxiang520.top/Article/details/gt2wsdeenya.html

Ruby: "第一行\n第二行"
来源：http://dali.xylfe.cn/Article/details/gt2vwszfqqi.html

C#:   "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gt2weysjiko.html

[A14] 注释写法
来源：http://dali.aizwys.cn/Article/details/gt2wipkuxgp.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.fengsongda.top/Article/details/gt2apwnivql.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yj20258888.top/Article/details/gt2bxydhvdu.html

JS:   // 单行；/* 多行 */
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kijrpusj.html

TS:   // 单行；/* 多行 */
来源：http://dali.yj20258.top/Article/details/gt2voozzmdl.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.cheryme.top/Article/details/gt2ywrxrlnx.html

Go:   // 单行；/* 多行 */
来源：http://dali.tian-w.cn/Article/details/gt2xyenduuj.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.meibo888.top/Article/details/gt2ojwnumre.html

C#:   // 单行；/* 多行 */
来源：http://dali.tanke756.top/Article/details/gt2tjyumvfe.html

[A15] 空值判断与默认值
来源：http://dali.ivvv.top/Article/details/gt2tfscgyka.html

Py:   value = data or "默认值"
来源：http://dali.sweek.top/Article/details/gt2fdoyefiv.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.c1oappe.top/Article/details/gt2ifztvowp.html

JS:   const value = data ?? "默认值";
来源：http://dali.9152youxi.cn/Article/details/gt2vqqqbucv.html

TS:   const value = data ?? "默认值";
来源：http://dali.shuidangran.top/Article/details/gt2mihucnaq.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.xziqi.cn/Article/details/gt2qxorpgre.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.hnxiangtu.top/Article/details/gt2yzzjzqax.html

Ruby: value = data || "默认值"
来源：http://dali.shzxlz.cn/Article/details/gt2hacqgejb.html

C#:   var value = data ?? "默认值";
来源：http://dali.sxryk.cn/Article/details/gt2sirrwtph.html

[A16] 真假值判断规则
来源：http://dali.c1oappe.top/Article/details/gt2vocqysej.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.sysykeji.top/Article/details/gt2rogkjqoc.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.gogol.net.cn/Article/details/gt2phucryzg.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.aibaodan.cn/Article/details/gt2rbeqlwpe.html

TS:   if (!x) {}
来源：http://dali.cucudq.cn/Article/details/gt2lxwgnspm.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.ydzc1.top/Article/details/gt2glclmvjd.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.xinyue.icu/Article/details/gt2ctdqicgu.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.xinyue.icu/Article/details/gt2wwucases.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.birdmap.top/Article/details/gt2stxbyjrz.html

[A17] 位运算
来源：http://dali.yonumen.top/Article/details/gt2ylegqbad.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yangfankeji.com/Article/details/gt2bobnkfjx.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yuanzhike.top/Article/details/gt2ghiwnkpm.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jlsjyb.cn/Article/details/gt2offbrjft.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gt2plxmswbk.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gt2egqqwfav.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jinqigufen.top/Article/details/gt2lvqzpjnn.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yueranfly.top/Article/details/gt2ckxurwmr.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gt2viczeemm.html


<!-- 参考信息 -->