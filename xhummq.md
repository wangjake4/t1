代发 wailian999

[U99] JS：事件监听
来源：http://dali.chenzaomai.com/Article/details/gtiwznhxtv.html

el.addEventListener("click", e => {})
来源：http://dali.gogol.net.cn/Article/details/gtbwncnaod.html

[U100] JS：DOM 查询
来源：http://dali.chenlongwang.top/Article/details/gthhazgfmi.html

document.querySelector(".item")
来源：http://dali.quarkkingdee.top/Article/details/gtkicqkgde.html

[U101] JS：classList 操作
来源：http://dali.redwolf501.top/Article/details/gtpjiwejiy.html

el.classList.toggle("active")
来源：http://dali.gotoacloud.top/Article/details/gtucsxebxn.html

[U102] JS：本地存储
来源：http://dali.daria6918.cn/Article/details/gteufxllhg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hysaishi.cn/Article/details/gtgplhcpuc.html

[U103] JS：定时器
来源：http://dali.hammf.cn/Article/details/gtulzpmtns.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdoulmnyh.html

[U104] JS：防抖
来源：http://dali.yj20258.top/Article/details/gtedwghhwr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gtjzkeqljj.html

[U105] JS：节流
来源：http://dali.mhx1999.top/Article/details/gtxapphtmp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.9152youxi.cn/Article/details/gtdppbbhud.html

[U106] JS：日期格式化
来源：http://dali.svipenyu.cn/Article/details/gtkthytflt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xuetiantiany.cn/Article/details/gtjsfciomh.html

[U107] JS：数字千分位
来源：http://dali.zhengqikj.top/Article/details/gtfdljycsb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.dianchejie.cn/Article/details/gtfswdeuvp.html

[U108] JS：随机整数
来源：http://dali.jinqigufen.top/Article/details/gtcyhykoan.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xuanzx.com/Article/details/gtkfbjxhjs.html

[U109] JS：数组分组
来源：http://dali.tian-w.cn/Article/details/gtgutigfkg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.gogol.net.cn/Article/details/gtzbfirknb.html

[U110] JS：数组分块
来源：http://dali.yvedp.cn/Article/details/gtneaewoaj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yongpay.top/Article/details/gtevvgmuxw.html

[U111] JS：对象转 Map
来源：http://dali.xuetiantiany.cn/Article/details/gtovnxgstj.html

new Map(Object.entries(obj))
来源：http://dali.aibaodan.cn/Article/details/gtbyqfcaci.html

[U112] JS：字符串补位
来源：http://dali.zycfv.cn/Article/details/gttwqefgru.html

"7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtlbmbdcbs.html

[U113] JS：正则替换全部
来源：http://dali.jianghu66.top/Article/details/gtskcvnavs.html

s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtnlyuxpbq.html

[U114] JS：JSON 深比较
来源：http://dali.haohaochexian.top/Article/details/gtjietilqc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gtgegzmcyi.html

[U115] JS：生成 UUID
来源：http://dali.9152youxi.cn/Article/details/gtbvweqqij.html

crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gtngnuqpas.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.andypj.xyz/Article/details/gtypirddoh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgakjwiuo.html

[U117] JS：单元测试
来源：http://dali.shzxlz.cn/Article/details/gtkeryzwnj.html

npm i -D vitest;  npx vitest
来源：http://dali.c1oappe.top/Article/details/gtgnhzartw.html

[U118] JS：开发服务器
来源：http://dali.zhongyouzk.top/Article/details/gtyeiugdrj.html

npm i -D vite;  npx vite
来源：http://dali.yuanzhike.top/Article/details/gtirupiljo.html

[U119] JS：生产构建
来源：http://dali.jqgufenzy.top/Article/details/gtqkxgkdmk.html

npx vite build
来源：http://dali.mhx1999.top/Article/details/gtluiiiaxv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.sufxvd.cn/Article/details/gttvutfjtr.html

import.meta.env.VITE_API_URL
来源：http://dali.xuanzx.com/Article/details/gtzoyizbwr.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtsomrzfyd.html

统计汇总
来源：http://dali.jinqigufen.top/Article/details/gtkswacjdz.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtcxdhbcmc.html

按语言统计（条）：
来源：http://dali.jyoumei.cn/Article/details/gtihnqipwo.html

Python ......... 252
来源：http://dali.zhiwuduotai.top/Article/details/gtvpsexvvw.html

PHP ............ 252
来源：http://dali.shanyushiyangtech.top/Article/details/gtvaidjcca.html

JavaScript ..... 252
来源：http://dali.xuanzx.com/Article/details/gtficcqrkq.html

TypeScript ..... 212
来源：http://dali.yanxiufei.cn/Article/details/gtpdldajfx.html

Java ........... 212
来源：http://dali.nanxuanxn.top/Article/details/gtbgjuuqja.html

Go ............. 212
来源：http://dali.nanxinkj.top/Article/details/gtkweohfug.html

Ruby ........... 212
来源：http://dali.sufxvd.cn/Article/details/gttpxivprl.html

C# ............. 212
来源：http://dali.xuanzx.com/Article/details/gtpdbnwtow.html

C .............. 30
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrwjakix.html

C++ ............ 30
来源：http://dali.cqqwz.cn/Article/details/gtyyzfjgtw.html

SQL ............ 90
来源：http://dali.hywenlv.cn/Article/details/gtjgkckdbu.html

Bash ........... 80
来源：http://dali.fzhhl.top/Article/details/gthqoehtkm.html

Kotlin ......... 15
来源：http://dali.mhx1999.top/Article/details/gtdzntmylk.html

Swift .......... 15
来源：http://dali.havefunace.top/Article/details/gtwpmpvvml.html

Lua ............ 10
来源：http://dali.kuanghao11.cn/Article/details/gtcjytxymc.html

Perl ........... 10
来源：http://dali.fengsongda.top/Article/details/gtudymwxsi.html

Scala .......... 10
来源：http://dali.yonumen.top/Article/details/gtsjrdvbye.html

------------------------------------
来源：http://dali.xuanzx.com/Article/details/gtamksbdsg.html

合计 ........... 2106 条
来源：http://dali.haohaochexian.top/Article/details/gtoaqnzgax.html

按章节统计：
来源：http://dali.zhengqikj.top/Article/details/gttsmkvizc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.nanxinkj.top/Article/details/gtvlkqzbcq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.guannengcc.top/Article/details/gtcakyigzy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gtzpxkzxci.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhoulong.xyz/Article/details/gtyqndjyap.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.dianchejie.cn/Article/details/gtdziybhkd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cheryme.top/Article/details/gtiawnphef.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.c1oappe.top/Article/details/gtgxthshgy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhoulong.xyz/Article/details/gtyaupuyws.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gtvkffmrhe.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jyoumei.cn/Article/details/gtbxfeznie.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gtzmasltos.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gtxeziapim.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gtqabamqwu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shangyingyoupin.top/Article/details/gtzpvsraes.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhongyouzk.top/Article/details/gtrlycxwda.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gtrtqfvmnk.html

Q SQL 专题                              90
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxmmsmyc.html

R Bash 专题                             80
来源：http://dali.c1oappe.top/Article/details/gtmdwcmmfc.html

S C / C++ 专题                          60
来源：http://dali.chenjidiqi.icu/Article/details/gtelzetjao.html

T 其他语言补充                          60
来源：http://dali.jqgfzy.top/Article/details/gtwvqhwlrr.html

U 高频实用片段                         120
来源：http://dali.svipenyu.cn/Article/details/gtzoznmzlm.html

------------------------------------
来源：http://dali.316326.xyz/Article/details/gtdjzkibox.html

合计                                  2106 条
来源：http://dali.xuanzx.com/Article/details/gtfgdoelmq.html

--------------------------------------------------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtyezumlip.html

使用提醒
来源：http://dali.cqqwz.cn/Article/details/gtejwwvqgr.html

--------------------------------------------------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtkklcpycx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhyxqrms.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.daria6918.cn/Article/details/gtrzaaaokk.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkeuwtxhl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.chenzaomai.com/Article/details/gtpprtaahj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yanxiufei.cn/Article/details/gtakzfgicj.html

—— 文件结束 ——
来源：http://dali.zycfv.cn/Article/details/gtziuasoih.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtcfhvzyee.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.iojbl.cn/Article/details/gtkzmbplfn.html

Common Programming Examples Cheat Book
来源：http://dali.ppjwa.cn/Article/details/gtohsjswqf.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdaevrowv.html

【收录内容】
来源：http://dali.yj202588.top/Article/details/gtoeaabdgx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.sufxvd.cn/Article/details/gtcemniwit.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxpbqaed.html

SQL · Bash · C · C++
来源：http://dali.daxiang520.top/Article/details/gtpabbgldg.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.guannengcc.top/Article/details/gtsjpkdigq.html

【使用说明】
来源：http://dali.yj20258888.top/Article/details/gteuultecs.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjosqsos.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.nanxinkj.top/Article/details/gtkcxysblz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.redwolf501.top/Article/details/gtzqjtnxkh.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xinyue.icu/Article/details/gtrbukhizn.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yangfankeji.com/Article/details/gtrnpaborp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.feifeiyinyue.top/Article/details/gtaemnxlfk.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.aibaodan.cn/Article/details/gtbruavvem.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.pengpengdd.cyou/Article/details/gtmffclfpu.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.gzhubu.top/Article/details/gtwqmbcnpw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtugvjlppv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ehwqpu.com/Article/details/gtxsqfsgqq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xuetiantiany.cn/Article/details/gtyolqliak.html

【文件统计】
来源：http://dali.smart0.xyz/Article/details/gthcqxnipi.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xuetiantiany.cn/Article/details/gtkhcrvnjf.html

--------------------------------------------------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gtryfiqevg.html

目  录
来源：http://dali.nanxinkj.top/Article/details/gtcalajalf.html

--------------------------------------------------------------------------------
来源：http://dali.xuanzx.com/Article/details/gttenbslet.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cucudq.cn/Article/details/gtrkolauwy.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ybcxt.top/Article/details/gtoqzrupdv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.gzhubu.top/Article/details/gtkzwexmkt.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jlsjyb.cn/Article/details/gtvktnuhqd.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gtptkjcfss.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.chenlongwang.top/Article/details/gtlyrckxsl.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gtvhcrpmit.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.chenlongwang.top/Article/details/gtdmqncjsi.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yanxiufei.cn/Article/details/gtmgkuplca.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jqgufenzy.top/Article/details/gtynpavqwp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhoulong.xyz/Article/details/gtorjmqyno.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yuxming.cn/Article/details/gtpwvylono.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.0kj1m.cn/Article/details/gtdmhfvzjk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.c1oappe.top/Article/details/gtzbruckki.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sxryk.cn/Article/details/gtjuaghesk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjrcpmxe.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtjiyhnssn.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.birdmap.top/Article/details/gtdnsijvoq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.dianchejie.cn/Article/details/gtvgvmfuco.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dashuyun.cn/Article/details/gtprrrvqii.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.guannengcc.top/Article/details/gtasegefyw.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtgxtlumin.html

A. 基础语法与类型
来源：http://dali.chenlongwang.top/Article/details/gtyfgmliav.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtwmjpuvhn.html

[A01] Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtumzcfpen.html

Py:   print("Hello, World!")
来源：http://dali.pengpengdd.cyou/Article/details/gtonkfhhwk.html

PHP:  echo "Hello, World!";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjcfovkh.html

JS:   console.log("Hello, World!");
来源：http://dali.jinqigufen.top/Article/details/gtcktnnpku.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jiagoushi.top/Article/details/gtkccobdpw.html

Java: System.out.println("Hello, World!");
来源：http://dali.yongpay.top/Article/details/gtwcfgqwcl.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jqgfzy.top/Article/details/gthfsfzjlq.html

Ruby: puts "Hello, World!"
来源：http://dali.cqqwz.cn/Article/details/gtasqjjfhe.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yvedp.cn/Article/details/gthzypezhq.html

[A02] 变量声明与赋值
来源：http://dali.shangyingyoupin.top/Article/details/gtdxyrfunm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.wangshuangyany.cn/Article/details/gtbwfvreld.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhiwuduotai.top/Article/details/gtlikpwesq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.dashuyun.cn/Article/details/gtfmkpuadc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.guowangkeji.top/Article/details/gtnhtmonax.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.fengsongda.top/Article/details/gtrdduwygw.html

Go:   name := "Alex"; age := 20
来源：http://dali.aizwys.cn/Article/details/gtbkiljzeu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jqgufenzy.top/Article/details/gtcqjjyjum.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.bjfxy.top/Article/details/gtlvfhwrva.html

[A03] 常量定义
来源：http://dali.mhx1999.top/Article/details/gtgrtmcxol.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hnxiangtu.top/Article/details/gtdmyqdbwj.html

PHP:  const PI = 3.14159;
来源：http://dali.havefunace.top/Article/details/gtvofbtdzo.html

JS:   const PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtycidzanq.html

TS:   const PI: number = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gtrvecqqvl.html

Java: static final double PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtraexbobi.html

Go:   const PI = 3.14159
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrrwfldw.html

Ruby: PI = 3.14159
来源：http://dali.chenjidiqi.icu/Article/details/gtfieeqmpk.html

C#:   const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtjqaaprhg.html

[A04] 判断变量类型
来源：http://dali.tanke756.top/Article/details/gtcwxijfjf.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.vqdsnc.cn/Article/details/gtseokjadm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.xuetiantiany.cn/Article/details/gtsbkdjoad.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.pycfn.com/Article/details/gtnpfevugl.html

TS:   typeof x; x instanceof Date
来源：http://dali.wangshuangyany.cn/Article/details/gtnildzbct.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gtqihhqptn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.quarkkingdee.top/Article/details/gtkxdmgzoj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.tanke756.top/Article/details/gtibmqcipq.html

C#:   x.GetType().Name; x is int
来源：http://dali.dashuyun.cn/Article/details/gtiifzhsab.html

[A05] 整数除法与取模
来源：http://dali.gogol.net.cn/Article/details/gthpejnldo.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yj20258.top/Article/details/gtbzammccb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtbdycuwdu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj202588.top/Article/details/gtpdtdvnkh.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zycfv.cn/Article/details/gtddrmfvxm.html

Java: 7 / 2; 7 % 2
来源：http://dali.cucudq.cn/Article/details/gtkcflnfcg.html

Go:   7 / 2; 7 % 2
来源：http://dali.jianghu66.top/Article/details/gtyvctpqqw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xylfe.cn/Article/details/gthuaybeqx.html

C#:   7 / 2; 7 % 2
来源：http://dali.redwolf501.top/Article/details/gtyvxftiwz.html

[A06] 字符串转数字
来源：http://dali.wangdashe.top/Article/details/gteahiimby.html

Py:   int("42"); float("3.14")
来源：http://dali.bjfxy.top/Article/details/gttucjdffe.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.birdmap.top/Article/details/gtrurmcfbw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jqgfzy.top/Article/details/gtgertvykk.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.xinyue.icu/Article/details/gtrvutrrjo.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.dashuyun.cn/Article/details/gthjfuahnr.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yueranfly.top/Article/details/gtfdafzmdb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.quarkkingdee.top/Article/details/gtjknzammq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.birdmap.top/Article/details/gtgyqdyzcm.html

[A07] 数字转字符串
来源：http://dali.haohaochexian.top/Article/details/gtckwcofao.html

Py:   str(42)
来源：http://dali.yongpay.top/Article/details/gtvilqvucl.html

PHP:  (string) 42; strval(42)
来源：http://dali.cdnleiting.top/Article/details/gtxxvbkcoh.html

JS:   String(42); (42).toString()
来源：http://dali.birdmap.top/Article/details/gtaaffggqd.html

TS:   String(42)
来源：http://dali.0kj1m.cn/Article/details/gtvfahgjvl.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.mhx1999.top/Article/details/gtwyjmzodc.html

Go:   strconv.Itoa(42)
来源：http://dali.jinqigfzy.top/Article/details/gtmcpyezid.html

Ruby: 42.to_s
来源：http://dali.zycfv.cn/Article/details/gtqmavmwxo.html

C#:   42.ToString()
来源：http://dali.iojbl.cn/Article/details/gtzfccrpbw.html

[A08] 取整与四舍五入
来源：http://dali.daxiang520.top/Article/details/gtzwqshwwi.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.shangyingyoupin.top/Article/details/gtisuiauvt.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.chenjidiqi.icu/Article/details/gtcbfvalrx.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.pengpengdd.cyou/Article/details/gtrtplqqqx.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwzgdhok.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jqgfzy.top/Article/details/gtnkookpgo.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.sxryk.cn/Article/details/gtggoqikjs.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.hfpthk.cn/Article/details/gtnrzmemis.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yuxming.cn/Article/details/gtwfholhao.html

[A09] 绝对值与最大最小值
来源：http://dali.guannengcc.top/Article/details/gtajpwjilb.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.meibo888.top/Article/details/gtnghnqcyy.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtxzafufrr.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtlsdwvtwz.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.guannengcc.top/Article/details/gtxqxpmjid.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtijztbfsq.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.ydzc1.top/Article/details/gtmzzzifrr.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.cucudq.cn/Article/details/gtycjeowxk.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gtjfyfzrbq.html

[A10] 生成随机数
来源：http://dali.mhx1999.top/Article/details/gtoezmuxvr.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jianghu66.top/Article/details/gtgfczjpik.html

PHP:  random_int(1, 100);
来源：http://dali.hfpthk.cn/Article/details/gtafnhkjdd.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gtznbrkjmh.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hfpthk.cn/Article/details/gtnblybzea.html

Java: new Random().nextInt(100) + 1
来源：http://dali.nanxuanxn.top/Article/details/gtobukrjbj.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhaomingkeji.xyz/Article/details/gttaytklvv.html

Ruby: rand(1..100)
来源：http://dali.shangyingyoupin.top/Article/details/gtvznehgmh.html

C#:   new Random().Next(1, 101)
来源：http://dali.bjfxy.top/Article/details/gtuyimzzgi.html

[A11] 条件表达式（三元）
来源：http://dali.hnxiangtu.top/Article/details/gtlsqhkmsl.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.bjfxy.top/Article/details/gtcnawvuov.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.c1oappe.top/Article/details/gtsyxdgupa.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.hysaishi.cn/Article/details/gtzeaqzvkn.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqiivkyb.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtrzbyah.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.ydzc1.top/Article/details/gtaljqngfp.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.wangshuangyany.cn/Article/details/gtgokipkbr.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.pengpengdd.cyou/Article/details/gtppkfnmjg.html

[A12] 字符串插值 / 格式化
来源：http://dali.svipenyu.cn/Article/details/gtwczqpnrq.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhoulong.xyz/Article/details/gtdtgcpdrj.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zdqjudy.top/Article/details/gtmcctdouu.html

JS:   `Hello, ${name}!`
来源：http://dali.cashguo.top/Article/details/gtucutunmi.html

TS:   `Hello, ${name}!`
来源：http://dali.zhongyouzk.top/Article/details/gtdhpldpas.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.sufxvd.cn/Article/details/gttjkpfwbs.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.xuanzx.com/Article/details/gtbesdwrea.html

Ruby: "Hello, #{name}!"
来源：http://dali.sufxvd.cn/Article/details/gthqvjtcgb.html

C#:   $"Hello, {name}!"
来源：http://dali.yongpay.top/Article/details/gtnqdshujm.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.redwolf501.top/Article/details/gtdkhhvaqk.html

Py:   "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gtctscerds.html

PHP:  "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gtcxmfvvlx.html

JS:   "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gteukjzztk.html

TS:   "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gtozaminon.html

Java: "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gtiqutihfe.html

Go:   "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gtkrazcvqj.html

Ruby: "第一行\n第二行"
来源：http://dali.jinqigufen.top/Article/details/gtnotdxvoo.html

C#:   "第一行\n第二行"
来源：http://dali.andypj.xyz/Article/details/gtocmvsfly.html

[A14] 注释写法
来源：http://dali.ehwqpu.com/Article/details/gtkyehoevt.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.havefunace.top/Article/details/gtqlxwmiwi.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhongyouzk.top/Article/details/gtbpmcjvby.html

JS:   // 单行；/* 多行 */
来源：http://dali.ivvv.top/Article/details/gtvdjcjtia.html

TS:   // 单行；/* 多行 */
来源：http://dali.sweek.top/Article/details/gtqaizxjea.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.snrcjt.cn/Article/details/gtzzgmyfsn.html

Go:   // 单行；/* 多行 */
来源：http://dali.ydzc1.top/Article/details/gtaviujyjp.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhixingplan.top/Article/details/gtignlqufa.html

C#:   // 单行；/* 多行 */
来源：http://dali.xuanzx.com/Article/details/gtleayygqa.html

[A15] 空值判断与默认值
来源：http://dali.jqgufenzy.top/Article/details/gtbenwelaf.html

Py:   value = data or "默认值"
来源：http://dali.fengsongda.top/Article/details/gtvasnmzxq.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jinghuilouyu.cn/Article/details/gtkweguube.html

JS:   const value = data ?? "默认值";
来源：http://dali.jlsjyb.cn/Article/details/gtyncdsnmk.html

TS:   const value = data ?? "默认值";
来源：http://dali.sufxvd.cn/Article/details/gtvtqoaquc.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yanxiufei.cn/Article/details/gtdevdzzwd.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.feifeiyinyue.top/Article/details/gtyoyvqamt.html

Ruby: value = data || "默认值"
来源：http://dali.havefunace.top/Article/details/gtykgiktlq.html

C#:   var value = data ?? "默认值";
来源：http://dali.snrcjt.cn/Article/details/gtxvmaitop.html

[A16] 真假值判断规则
来源：http://dali.snrcjt.cn/Article/details/gtlpklgvdn.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.smart0.xyz/Article/details/gtsmlbqmro.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xuanzx.com/Article/details/gtykdsqveb.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.feifeiyinyue.top/Article/details/gtzbhiasbb.html

TS:   if (!x) {}
来源：http://dali.hammf.cn/Article/details/gtkyahxmfe.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtmuqtxuoa.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yuxming.cn/Article/details/gtnuyulrlb.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.gogol.net.cn/Article/details/gtorlthdtb.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.chenzaomai.com/Article/details/gtkttajszn.html

[A17] 位运算
来源：http://dali.gzhubu.top/Article/details/gtxerwdiun.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenjidiqi.icu/Article/details/gtdkymaily.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.cdnleiting.top/Article/details/gtrinutpos.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gaohongyu789.top/Article/details/gtmdafpjof.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gtjeencern.html


<!-- 参考信息 -->