代发 wailian999

[U95] JS：Promise 包装
来源：http://dali.xylfe.cn/Article/details/gt2dxzmncha.html

new Promise((resolve, reject) => {})
来源：http://dali.zhixingplan.top/Article/details/gt2kgibrocu.html

[U96] JS：async/await 与异常
来源：http://dali.yj20258888.top/Article/details/gt2unimsccm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gt2gfnxohog.html

[U97] JS：并发请求
来源：http://dali.hnxiangtu.top/Article/details/gt2zvibgpro.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gt2pqraldud.html

[U98] JS：fetch 带 JSON
来源：http://dali.jqgufenzy.top/Article/details/gt2cgmhedwk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cqqwz.cn/Article/details/gt2ekakijns.html

[U99] JS：事件监听
来源：http://dali.pengpengdd.cyou/Article/details/gt2zmrldbrw.html

el.addEventListener("click", e => {})
来源：http://dali.cqqwz.cn/Article/details/gt2okcmbpxq.html

[U100] JS：DOM 查询
来源：http://dali.tanke756.top/Article/details/gt2tzptvltu.html

document.querySelector(".item")
来源：http://dali.jianghu66.top/Article/details/gt2kcsyohyh.html

[U101] JS：classList 操作
来源：http://dali.guannengcc.top/Article/details/gt2psfsydeb.html

el.classList.toggle("active")
来源：http://dali.hfpthk.cn/Article/details/gt2sgpplibk.html

[U102] JS：本地存储
来源：http://dali.ppjwa.cn/Article/details/gt2bvqdvkhd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yonumen.top/Article/details/gt2pkoxzfuz.html

[U103] JS：定时器
来源：http://dali.hongshengwenyu.top/Article/details/gt2jpgqdkno.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.quarkkingdee.top/Article/details/gt2gypkjpav.html

[U104] JS：防抖
来源：http://dali.ivvv.top/Article/details/gt2ahpclzxz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gt2xjqkaamn.html

[U105] JS：节流
来源：http://dali.svipenyu.cn/Article/details/gt2fkqsegmq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.havefunace.top/Article/details/gt2bqdmqnrh.html

[U106] JS：日期格式化
来源：http://dali.wangdashe.top/Article/details/gt2ppezrtdr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bvwoxakk.html

[U107] JS：数字千分位
来源：http://dali.cheryme.top/Article/details/gt2ofhufzxo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.9152youxi.cn/Article/details/gt2tlpnotms.html

[U108] JS：随机整数
来源：http://dali.ehwqpu.com/Article/details/gt2tjxdehxx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hnxiangtu.top/Article/details/gt2gkomqnev.html

[U109] JS：数组分组
来源：http://dali.yonumen.top/Article/details/gt2ycduhzvv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.c1oappe.top/Article/details/gt2lsolqguv.html

[U110] JS：数组分块
来源：http://dali.nanxinkj.top/Article/details/gt2iedokgmc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ehwqpu.com/Article/details/gt2pfiznhgj.html

[U111] JS：对象转 Map
来源：http://dali.yueranfly.top/Article/details/gt2unvycngs.html

new Map(Object.entries(obj))
来源：http://dali.cdnleiting.top/Article/details/gt2nymvretc.html

[U112] JS：字符串补位
来源：http://dali.jqgufenzy.top/Article/details/gt2olzknxdw.html

"7".padStart(3, "0")
来源：http://dali.fzhhl.top/Article/details/gt2siszsrci.html

[U113] JS：正则替换全部
来源：http://dali.nwbrower.top/Article/details/gt2xygklxwp.html

s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gt2tkxwcrbz.html

[U114] JS：JSON 深比较
来源：http://dali.wangdashe.top/Article/details/gt2jixpwvsi.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guowangkeji.top/Article/details/gt2tvmhvqxj.html

[U115] JS：生成 UUID
来源：http://dali.daria6918.cn/Article/details/gt2jljqihdn.html

crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gt2zkholqvf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.tanke756.top/Article/details/gt2erzrqnsq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ehwqpu.com/Article/details/gt2idtooqjz.html

[U117] JS：单元测试
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cfykgnrx.html

npm i -D vitest;  npx vitest
来源：http://dali.daria6918.cn/Article/details/gt2woulaanb.html

[U118] JS：开发服务器
来源：http://dali.gogol.net.cn/Article/details/gt2stagspkd.html

npm i -D vite;  npx vite
来源：http://dali.pengpengdd.cyou/Article/details/gt2mhfmeict.html

[U119] JS：生产构建
来源：http://dali.zdqjudy.top/Article/details/gt2tyjnvffo.html

npx vite build
来源：http://dali.ppjwa.cn/Article/details/gt2ltijjedy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.fengsongda.top/Article/details/gt2xjhnlwaq.html

import.meta.env.VITE_API_URL
来源：http://dali.yuxming.cn/Article/details/gt2rodfffpt.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2yyfjnhzf.html

统计汇总
来源：http://dali.shzxlz.cn/Article/details/gt2pfnzvcrc.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ebaaoerk.html

按语言统计（条）：
来源：http://dali.shanyushiyangtech.top/Article/details/gt2whglttib.html

Python ......... 252
来源：http://dali.haohaochexian.top/Article/details/gt2ybjrhkxp.html

PHP ............ 252
来源：http://dali.guannengcc.top/Article/details/gt2lmjphkao.html

JavaScript ..... 252
来源：http://dali.hnxiangtu.top/Article/details/gt2xsnnnvoh.html

TypeScript ..... 212
来源：http://dali.sxryk.cn/Article/details/gt2dfpyggqj.html

Java ........... 212
来源：http://dali.hysaishi.cn/Article/details/gt2truauiil.html

Go ............. 212
来源：http://dali.jinqigfzy.top/Article/details/gt2bjqfndfz.html

Ruby ........... 212
来源：http://dali.yueranfly.top/Article/details/gt2cycmyeok.html

C# ............. 212
来源：http://dali.hywenlv.cn/Article/details/gt2einlvnmu.html

C .............. 30
来源：http://dali.gaohongyu789.top/Article/details/gt2dwqiiodk.html

C++ ............ 30
来源：http://dali.aibaodan.cn/Article/details/gt2xucyuybj.html

SQL ............ 90
来源：http://dali.c1oappe.top/Article/details/gt2cryqgohf.html

Bash ........... 80
来源：http://dali.zdqjudy.top/Article/details/gt2uzprlbde.html

Kotlin ......... 15
来源：http://dali.pycfn.com/Article/details/gt2qqyriqgh.html

Swift .......... 15
来源：http://dali.zhixingplan.top/Article/details/gt2tcfmjgls.html

Lua ............ 10
来源：http://dali.cheryme.top/Article/details/gt2gxvisxcz.html

Perl ........... 10
来源：http://dali.hongshengwenyu.top/Article/details/gt2bbdkuciw.html

Scala .......... 10
来源：http://dali.gogol.net.cn/Article/details/gt2gbfhoafo.html

------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2icreiilv.html

合计 ........... 2106 条
来源：http://dali.hywenlv.cn/Article/details/gt2aafyungx.html

按章节统计：
来源：http://dali.nwbrower.top/Article/details/gt2rwlrmgks.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tianlin.xyz/Article/details/gt2rxcwjkbi.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhengqikj.top/Article/details/gt2hmxeqrix.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yangfankeji.com/Article/details/gt2cemuefgs.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zycfv.cn/Article/details/gt2miwkbrdn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhixingplan.top/Article/details/gt2iiiqlcik.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.sxryk.cn/Article/details/gt2kfmusywc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wkezvtbj.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.haohaochexian.top/Article/details/gt2finbseji.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.mhx1999.top/Article/details/gt2sytmalxi.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhengqikj.top/Article/details/gt2exdnkfpn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gt2kqbpptyt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gt2jykdjixk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gt2aeddghxd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xylfe.cn/Article/details/gt2psphbsln.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.feifeiyinyue.top/Article/details/gt2jgcbfvze.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lidjyzmv.html

Q SQL 专题                              90
来源：http://dali.mhx1999.top/Article/details/gt2xdomkgoe.html

R Bash 专题                             80
来源：http://dali.kuanghao11.cn/Article/details/gt2zriseqpn.html

S C / C++ 专题                          60
来源：http://dali.xziqi.cn/Article/details/gt2cfqtnqia.html

T 其他语言补充                          60
来源：http://dali.wangshuangyany.cn/Article/details/gt2zoqlktsw.html

U 高频实用片段                         120
来源：http://dali.ydzc1.top/Article/details/gt2bslgssgi.html

------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gt2ilicljbx.html

合计                                  2106 条
来源：http://dali.guowangkeji.top/Article/details/gt2gkzcrinj.html

--------------------------------------------------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gt2sjhwtazy.html

使用提醒
来源：http://dali.haohaochexian.top/Article/details/gt2dxyhcpyt.html

--------------------------------------------------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gt2mvxoenen.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.chenlongwang.top/Article/details/gt2psybyxug.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xziqi.cn/Article/details/gt2xpugjmff.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.quarkkingdee.top/Article/details/gt2mtvohrtl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hammf.cn/Article/details/gt2arnrxizu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.kuanghao11.cn/Article/details/gt2fqcahmfq.html

—— 文件结束 ——
来源：http://dali.sufxvd.cn/Article/details/gt2bqzrmysx.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2ygurinxh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yueranfly.top/Article/details/gt2dbqaytjc.html

Common Programming Examples Cheat Book
来源：http://dali.tian-w.cn/Article/details/gt2hlariwor.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2shqekkvq.html

【收录内容】
来源：http://dali.xuanzx.com/Article/details/gt2dzjncopw.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.c1oappe.top/Article/details/gt2qrgexpsy.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.dashuyun.cn/Article/details/gt2rihbneoq.html

SQL · Bash · C · C++
来源：http://dali.xuetiantiany.cn/Article/details/gt2rxesmqda.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yj20258.top/Article/details/gt2iwggnfku.html

【使用说明】
来源：http://dali.xuetiantiany.cn/Article/details/gt2jeeyyddg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yueranfly.top/Article/details/gt2sktryidi.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zdqjudy.top/Article/details/gt2shzrwbvp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.quarkkingdee.top/Article/details/gt2szxceykb.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.chenzaomai.com/Article/details/gt2cwkpnige.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ivvv.top/Article/details/gt2mktxnavx.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenjidiqi.icu/Article/details/gt2myurpfhw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cashguo.top/Article/details/gt2ozhlfsae.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.meibo888.top/Article/details/gt2wsbidzog.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.nanxinkj.top/Article/details/gt2nhvwcvnz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.sxryk.cn/Article/details/gt2vtewgdfr.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhengqikj.top/Article/details/gt2ubgftjvq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.dashuyun.cn/Article/details/gt2eqdoqpwc.html

【文件统计】
来源：http://dali.ppjwa.cn/Article/details/gt2zmmhjecr.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hnqzz.top/Article/details/gt2gvcacdgp.html

--------------------------------------------------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gt2uzplrvxb.html

目  录
来源：http://dali.feifeiyinyue.top/Article/details/gt2hoksiutk.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gt2iwxnjxqs.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.birdmap.top/Article/details/gt2ccdsmqcu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ydzc1.top/Article/details/gt2owwndnax.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2kqnpaxuc.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2dbsoabmq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.sweek.top/Article/details/gt2mgfztaup.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.chenlongwang.top/Article/details/gt2nnmgvxoz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.sysykeji.top/Article/details/gt2amdshaxx.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2smdfopmf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.sxryk.cn/Article/details/gt2uoprdpyv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2sauuamat.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gt2lusbredl.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gt2uziztkwv.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gt2ylovdoao.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jinqigufen.top/Article/details/gt2qwiasctx.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sweek.top/Article/details/gt2zzxfvbuj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gt2dxfksxax.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yj202588.top/Article/details/gt2gqleyzsa.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.tanke756.top/Article/details/gt2sbzuzrbe.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zycfv.cn/Article/details/gt2pwccyqau.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigfzy.top/Article/details/gt2mjnkmdft.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.aibaodan.cn/Article/details/gt2cxrhowzf.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2wuzynlav.html

A. 基础语法与类型
来源：http://dali.jinqigufen.top/Article/details/gt2zknddjfv.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2hwhqzyjm.html

[A01] Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2omuoejkl.html

Py:   print("Hello, World!")
来源：http://dali.kuanghao11.cn/Article/details/gt2mumwrofs.html

PHP:  echo "Hello, World!";
来源：http://dali.havefunace.top/Article/details/gt2yxvimnnc.html

JS:   console.log("Hello, World!");
来源：http://dali.hnqzz.top/Article/details/gt2tlkdtqik.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ivvv.top/Article/details/gt2cgxpgfbk.html

Java: System.out.println("Hello, World!");
来源：http://dali.jqgufenzy.top/Article/details/gt2xvztcgny.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cucudq.cn/Article/details/gt2dnytahjy.html

Ruby: puts "Hello, World!"
来源：http://dali.cqqwz.cn/Article/details/gt2libbkixo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hfpthk.cn/Article/details/gt2camegicv.html

[A02] 变量声明与赋值
来源：http://dali.chenzaomai.com/Article/details/gt2golusaxt.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.wangdashe.top/Article/details/gt2ycpfyarn.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xziqi.cn/Article/details/gt2uiuhahmd.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhixingplan.top/Article/details/gt2bjsvqvpe.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cheryme.top/Article/details/gt2zeyzglds.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.nanxinkj.top/Article/details/gt2wdcfeiwq.html

Go:   name := "Alex"; age := 20
来源：http://dali.shuidangran.top/Article/details/gt2yyayllhk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bhypffre.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jianghu66.top/Article/details/gt2wmumqjrz.html

[A03] 常量定义
来源：http://dali.zdqjudy.top/Article/details/gt2yrtylxfq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.nanxinkj.top/Article/details/gt2jitdcdpk.html

PHP:  const PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gt2ggbtmhwu.html

JS:   const PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gt2rmdsouml.html

TS:   const PI: number = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gt2ngsfitbt.html

Java: static final double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gt2ygdettkh.html

Go:   const PI = 3.14159
来源：http://dali.ivvv.top/Article/details/gt2wtrktbun.html

Ruby: PI = 3.14159
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bctodndh.html

C#:   const double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gt2nhaqndrj.html

[A04] 判断变量类型
来源：http://dali.jianghu66.top/Article/details/gt2eymjhqxv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jqgufenzy.top/Article/details/gt2hkneeohx.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2naulnpre.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.0kj1m.cn/Article/details/gt2owlcdwis.html

TS:   typeof x; x instanceof Date
来源：http://dali.svipenyu.cn/Article/details/gt2qpyucgai.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.cashguo.top/Article/details/gt2cjjyxvlc.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yuanzhike.top/Article/details/gt2nmetjkej.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yj20258.top/Article/details/gt2rwfapkqw.html

C#:   x.GetType().Name; x is int
来源：http://dali.hnqzz.top/Article/details/gt2uknafvdg.html

[A05] 整数除法与取模
来源：http://dali.sysykeji.top/Article/details/gt2clpepcfn.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2ayiwiatm.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.sweek.top/Article/details/gt2aedoihia.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sweek.top/Article/details/gt2aiybdvfc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2mlsmmcvi.html

Java: 7 / 2; 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gt2seotetmd.html

Go:   7 / 2; 7 % 2
来源：http://dali.jianghu66.top/Article/details/gt2dasvbuzf.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ydzc1.top/Article/details/gt2omjsjokk.html

C#:   7 / 2; 7 % 2
来源：http://dali.hammf.cn/Article/details/gt2uqluyvek.html

[A06] 字符串转数字
来源：http://dali.yueranfly.top/Article/details/gt2rrtuzebp.html

Py:   int("42"); float("3.14")
来源：http://dali.hnxiangtu.top/Article/details/gt2uphqqszw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.dianchejie.cn/Article/details/gt2jmiacrft.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.tianlin.xyz/Article/details/gt2scghjiru.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ydzc1.top/Article/details/gt2itnitzbo.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.meibo888.top/Article/details/gt2clcecosv.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.guowangkeji.top/Article/details/gt2bpjaskcc.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.cucudq.cn/Article/details/gt2tfnzetmb.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jlsjyb.cn/Article/details/gt2nsaaccas.html

[A07] 数字转字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2bgxibzgy.html

Py:   str(42)
来源：http://dali.yvedp.cn/Article/details/gt2mfurnuba.html

PHP:  (string) 42; strval(42)
来源：http://dali.snrcjt.cn/Article/details/gt2ykptncdk.html

JS:   String(42); (42).toString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2bnvbjyuu.html

TS:   String(42)
来源：http://dali.ybcxt.top/Article/details/gt2xnpglwoi.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jyoumei.cn/Article/details/gt2cqueisis.html

Go:   strconv.Itoa(42)
来源：http://dali.xinyue.icu/Article/details/gt2ozbupcof.html

Ruby: 42.to_s
来源：http://dali.feifeiyinyue.top/Article/details/gt2gzuscjlw.html

C#:   42.ToString()
来源：http://dali.shzxlz.cn/Article/details/gt2kbnuedme.html

[A08] 取整与四舍五入
来源：http://dali.zhixingplan.top/Article/details/gt2qbkszqrd.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.fengsongda.top/Article/details/gt2wmurdxzf.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.gotoacloud.top/Article/details/gt2decyepbn.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.snrcjt.cn/Article/details/gt2mecopluc.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.svipenyu.cn/Article/details/gt2zyrllntb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.xuanzx.com/Article/details/gt2qktxrbsy.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dbiqpaso.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.bjfxy.top/Article/details/gt2pqptbyyh.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.guowangkeji.top/Article/details/gt2hhqyazmf.html

[A09] 绝对值与最大最小值
来源：http://dali.0kj1m.cn/Article/details/gt2xplbrdrr.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gt2omzrcets.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ivvv.top/Article/details/gt2gvbwmdkv.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.mhx1999.top/Article/details/gt2yxvepevf.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2iwpioncl.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lvobbhlt.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yongpay.top/Article/details/gt2xlgiswei.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.xziqi.cn/Article/details/gt2xkuoarpp.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.pycfn.com/Article/details/gt2syrenccr.html

[A10] 生成随机数
来源：http://dali.gotoacloud.top/Article/details/gt2iaxovtuf.html

Py:   import random; random.randint(1, 100)
来源：http://dali.sufxvd.cn/Article/details/gt2ikdnshmk.html

PHP:  random_int(1, 100);
来源：http://dali.jyoumei.cn/Article/details/gt2vhlxmkuo.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2httnbsyu.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yangfankeji.com/Article/details/gt2adewyxkn.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yongpay.top/Article/details/gt2zvzrtnvh.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hywenlv.cn/Article/details/gt2wnssyemz.html

Ruby: rand(1..100)
来源：http://dali.xuanzx.com/Article/details/gt2kdvbbret.html

C#:   new Random().Next(1, 101)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yzouwcge.html

[A11] 条件表达式（三元）
来源：http://dali.hnxiangtu.top/Article/details/gt2zdyidrkp.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.hywenlv.cn/Article/details/gt2vafgxggh.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.feifeiyinyue.top/Article/details/gt2jauxbdqf.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.cashguo.top/Article/details/gt2imukguyx.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yuxming.cn/Article/details/gt2turazjop.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xuetiantiany.cn/Article/details/gt2lrjcmahu.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.kuanghao11.cn/Article/details/gt2omhfnxmi.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.xziqi.cn/Article/details/gt2ejnpfxyy.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.svipenyu.cn/Article/details/gt2brzyqyua.html

[A12] 字符串插值 / 格式化
来源：http://dali.jinqigufen.top/Article/details/gt2favghzjv.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.kuanghao11.cn/Article/details/gt2wcuxfhxr.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.hywenlv.cn/Article/details/gt2dxiwuvpn.html

JS:   `Hello, ${name}!`
来源：http://dali.snrcjt.cn/Article/details/gt2frmlzmof.html

TS:   `Hello, ${name}!`
来源：http://dali.daria6918.cn/Article/details/gt2pksdvpoq.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yonumen.top/Article/details/gt2bulcxipk.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.ydzc1.top/Article/details/gt2cjujowhj.html

Ruby: "Hello, #{name}!"
来源：http://dali.andypj.xyz/Article/details/gt2niawjwmp.html

C#:   $"Hello, {name}!"
来源：http://dali.daria6918.cn/Article/details/gt2zhgsagro.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yanxiufei.cn/Article/details/gt2zffimkti.html

Py:   "第一行\n第二行"
来源：http://dali.sufxvd.cn/Article/details/gt2rcxdycll.html

PHP:  "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gt2yzijzung.html

JS:   "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gt2kerlsets.html

TS:   "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gt2qxuntimm.html

Java: "第一行\n第二行"
来源：http://dali.ivvv.top/Article/details/gt2clhbqfvk.html

Go:   "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gt2qqdhcjjm.html

Ruby: "第一行\n第二行"
来源：http://dali.pengpengdd.cyou/Article/details/gt2hucdbxju.html

C#:   "第一行\n第二行"
来源：http://dali.iojbl.cn/Article/details/gt2gguhshfy.html

[A14] 注释写法
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jbqofzoa.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.tianlin.xyz/Article/details/gt2lzdnkoaj.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.xuetiantiany.cn/Article/details/gt2dwzjwtfn.html

JS:   // 单行；/* 多行 */
来源：http://dali.daria6918.cn/Article/details/gt2zteietlw.html

TS:   // 单行；/* 多行 */
来源：http://dali.jqgufenzy.top/Article/details/gt2esafubis.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zycfv.cn/Article/details/gt2kwlmdcxd.html

Go:   // 单行；/* 多行 */
来源：http://dali.smart0.xyz/Article/details/gt2vbqdcewn.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.tanke756.top/Article/details/gt2knrhgwfo.html

C#:   // 单行；/* 多行 */
来源：http://dali.aizwys.cn/Article/details/gt2gsjoinaf.html

[A15] 空值判断与默认值
来源：http://dali.xylfe.cn/Article/details/gt2nkasjfpl.html

Py:   value = data or "默认值"
来源：http://dali.jianghu66.top/Article/details/gt2kahvxbft.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.redwolf501.top/Article/details/gt2ynyqgslt.html

JS:   const value = data ?? "默认值";
来源：http://dali.xuanzx.com/Article/details/gt2scpyalji.html

TS:   const value = data ?? "默认值";
来源：http://dali.sxryk.cn/Article/details/gt2phyivdar.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhixingplan.top/Article/details/gt2pcmmyxtp.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jinqigufen.top/Article/details/gt2fublydqj.html

Ruby: value = data || "默认值"
来源：http://dali.daria6918.cn/Article/details/gt2eeomwuxd.html

C#:   var value = data ?? "默认值";
来源：http://dali.yj202588.top/Article/details/gt2wqvgnhcj.html

[A16] 真假值判断规则
来源：http://dali.fzhhl.top/Article/details/gt2qknvahsq.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.ivvv.top/Article/details/gt2pcmxfgsr.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.wangshuangyany.cn/Article/details/gt2ddpnuzva.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.redwolf501.top/Article/details/gt2rrzvozul.html

TS:   if (!x) {}
来源：http://dali.zycfv.cn/Article/details/gt2jtkwbvhz.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2awccnprc.html


<!-- 参考信息 -->