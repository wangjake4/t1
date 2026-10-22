代发 wailian999

[U93] JS：模板字符串
来源：http://dali.yj20258888.top/Article/details/gtkkemmjav.html

`共 ${n} 条`
来源：http://dali.yvedp.cn/Article/details/gtwuhihcti.html

[U94] JS：箭头函数
来源：http://dali.zhiwuduotai.top/Article/details/gtqxotkucn.html

const double = x => x * 2;
来源：http://dali.yuanzhike.top/Article/details/gtjthekwtl.html

[U95] JS：Promise 包装
来源：http://dali.zhoulong.xyz/Article/details/gtnisvzjtl.html

new Promise((resolve, reject) => {})
来源：http://dali.fengsongda.top/Article/details/gtwqrbqjkh.html

[U96] JS：async/await 与异常
来源：http://dali.316326.xyz/Article/details/gtnqueqxjq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gtmjqxxwfi.html

[U97] JS：并发请求
来源：http://dali.gotoacloud.top/Article/details/gtzhxjgxqv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gtjpardmng.html

[U98] JS：fetch 带 JSON
来源：http://dali.yj202588.top/Article/details/gthnrcwoqh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yj20258888.top/Article/details/gtzfjwdqsq.html

[U99] JS：事件监听
来源：http://dali.sweek.top/Article/details/gtgdrnjcxn.html

el.addEventListener("click", e => {})
来源：http://dali.cdnleiting.top/Article/details/gtabvzqsbl.html

[U100] JS：DOM 查询
来源：http://dali.iojbl.cn/Article/details/gtkidqwawq.html

document.querySelector(".item")
来源：http://dali.gogol.net.cn/Article/details/gtsboawyri.html

[U101] JS：classList 操作
来源：http://dali.hammf.cn/Article/details/gtuhvzcltr.html

el.classList.toggle("active")
来源：http://dali.chenzaomai.com/Article/details/gttumcunln.html

[U102] JS：本地存储
来源：http://dali.aibaodan.cn/Article/details/gtsqicsfns.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nanxinkj.top/Article/details/gtnfwgyuby.html

[U103] JS：定时器
来源：http://dali.dashuyun.cn/Article/details/gtvxukhdvc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shanyushiyangtech.top/Article/details/gtarwekcps.html

[U104] JS：防抖
来源：http://dali.yj202588.top/Article/details/gtriooytsg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gtkmnmwotz.html

[U105] JS：节流
来源：http://dali.yuxming.cn/Article/details/gtqowvxgeb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cheryme.top/Article/details/gtodovtjbp.html

[U106] JS：日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gtwqrwcgfz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.quarkkingdee.top/Article/details/gtourwtmpu.html

[U107] JS：数字千分位
来源：http://dali.jianghu66.top/Article/details/gtojxywxkd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jyoumei.cn/Article/details/gthzlyiyre.html

[U108] JS：随机整数
来源：http://dali.daria6918.cn/Article/details/gtiafctsxz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cashguo.top/Article/details/gtquuvpcfh.html

[U109] JS：数组分组
来源：http://dali.cucudq.cn/Article/details/gtvzajmhln.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ybcxt.top/Article/details/gtcumildmz.html

[U110] JS：数组分块
来源：http://dali.hnxiangtu.top/Article/details/gtormmoajv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinqigfzy.top/Article/details/gtzvzfuekm.html

[U111] JS：对象转 Map
来源：http://dali.chenjidiqi.icu/Article/details/gtspbgopld.html

new Map(Object.entries(obj))
来源：http://dali.shanyushiyangtech.top/Article/details/gthkfojasm.html

[U112] JS：字符串补位
来源：http://dali.shangyingyoupin.top/Article/details/gtobuyzzdo.html

"7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtvbnkfdfp.html

[U113] JS：正则替换全部
来源：http://dali.vqdsnc.cn/Article/details/gtczmccqzx.html

s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtqwpyhobw.html

[U114] JS：JSON 深比较
来源：http://dali.havefunace.top/Article/details/gtvlabjvlm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.316326.xyz/Article/details/gtlwmzmwjx.html

[U115] JS：生成 UUID
来源：http://dali.mhx1999.top/Article/details/gtmxynjfag.html

crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gtjkuzqtdw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkysmgox.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yj20258888.top/Article/details/gtxwdklmts.html

[U117] JS：单元测试
来源：http://dali.zhixingplan.top/Article/details/gtlgcctcrw.html

npm i -D vitest;  npx vitest
来源：http://dali.aizwys.cn/Article/details/gtkxkcgdkk.html

[U118] JS：开发服务器
来源：http://dali.cqqwz.cn/Article/details/gtguzquitp.html

npm i -D vite;  npx vite
来源：http://dali.zycfv.cn/Article/details/gtwspmtoug.html

[U119] JS：生产构建
来源：http://dali.feifeiyinyue.top/Article/details/gttavvuzrr.html

npx vite build
来源：http://dali.aibaodan.cn/Article/details/gtecfiqthv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.feifeiyinyue.top/Article/details/gtdwwtshww.html

import.meta.env.VITE_API_URL
来源：http://dali.tian-w.cn/Article/details/gtaksuazcu.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtsjdvtsvo.html

统计汇总
来源：http://dali.shzxlz.cn/Article/details/gtlzqvkand.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtlfgwjcdb.html

按语言统计（条）：
来源：http://dali.cashguo.top/Article/details/gtoeyfydae.html

Python ......... 252
来源：http://dali.hysaishi.cn/Article/details/gtxugmmxaa.html

PHP ............ 252
来源：http://dali.dianchejie.cn/Article/details/gttwtdmuxr.html

JavaScript ..... 252
来源：http://dali.smart0.xyz/Article/details/gtbujmehng.html

TypeScript ..... 212
来源：http://dali.nanxinkj.top/Article/details/gtgrdiilrd.html

Java ........... 212
来源：http://dali.yj20258888.top/Article/details/gthhcsfdqu.html

Go ............. 212
来源：http://dali.xinyue.icu/Article/details/gtyqhxntve.html

Ruby ........... 212
来源：http://dali.sufxvd.cn/Article/details/gtvsdoawoc.html

C# ............. 212
来源：http://dali.daria6918.cn/Article/details/gtruvocdmq.html

C .............. 30
来源：http://dali.nanxinkj.top/Article/details/gtzqkudvkp.html

C++ ............ 30
来源：http://dali.sufxvd.cn/Article/details/gteuaexgap.html

SQL ............ 90
来源：http://dali.zhixingplan.top/Article/details/gtytbisosm.html

Bash ........... 80
来源：http://dali.jqgfzy.top/Article/details/gtnwxjbklf.html

Kotlin ......... 15
来源：http://dali.ivvv.top/Article/details/gttilotqtn.html

Swift .......... 15
来源：http://dali.daria6918.cn/Article/details/gtexugkmng.html

Lua ............ 10
来源：http://dali.sxryk.cn/Article/details/gteykznjnv.html

Perl ........... 10
来源：http://dali.gotoacloud.top/Article/details/gtmfhbtpxk.html

Scala .......... 10
来源：http://dali.hammf.cn/Article/details/gtshrugsmo.html

------------------------------------
来源：http://dali.yj20258.top/Article/details/gtxoxgojfn.html

合计 ........... 2106 条
来源：http://dali.vqdsnc.cn/Article/details/gtaysqqvgq.html

按章节统计：
来源：http://dali.sysykeji.top/Article/details/gtjushepjj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cdnleiting.top/Article/details/gtzintmphh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.chenzaomai.com/Article/details/gtmxroelhn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.mhx1999.top/Article/details/gtyxewmglr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ppjwa.cn/Article/details/gtacdbzhzs.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jqgfzy.top/Article/details/gtjdauixlp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hongshengwenyu.top/Article/details/gtbvwmnumw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.iojbl.cn/Article/details/gtpzabpxkk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ehwqpu.com/Article/details/gtsvrqtykr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gtqanrzsap.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shangyingyoupin.top/Article/details/gtmuzxvtsb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gtbysdhsne.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqkgyjeu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gtvazujcwp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.mhx1999.top/Article/details/gtsjevbgup.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shzxlz.cn/Article/details/gtkzlriftd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdcuopgr.html

Q SQL 专题                              90
来源：http://dali.tian-w.cn/Article/details/gtgquahyxq.html

R Bash 专题                             80
来源：http://dali.quarkkingdee.top/Article/details/gtrjgaacke.html

S C / C++ 专题                          60
来源：http://dali.daxiang520.top/Article/details/gtxamnylws.html

T 其他语言补充                          60
来源：http://dali.pycfn.com/Article/details/gthhqqzkdw.html

U 高频实用片段                         120
来源：http://dali.svipenyu.cn/Article/details/gtfjpdkrrj.html

------------------------------------
来源：http://dali.yj202588.top/Article/details/gtoysozsiw.html

合计                                  2106 条
来源：http://dali.sweek.top/Article/details/gtzgdiexpq.html

--------------------------------------------------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gtorecijsd.html

使用提醒
来源：http://dali.tianlin.xyz/Article/details/gtdfqakhcm.html

--------------------------------------------------------------------------------
来源：http://dali.redwolf501.top/Article/details/gtrmnhinbp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.feifeiyinyue.top/Article/details/gtfaiqdhvh.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ivvv.top/Article/details/gtknerwgmu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.gotoacloud.top/Article/details/gtdawkwczs.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yvedp.cn/Article/details/gtpllfzqiy.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.sxryk.cn/Article/details/gtljrzygrz.html

—— 文件结束 ——
来源：http://dali.bjfxy.top/Article/details/gttteggwju.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtmujvjxsq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.mhx1999.top/Article/details/gtasxdiziq.html

Common Programming Examples Cheat Book
来源：http://dali.svipenyu.cn/Article/details/gtnquscdob.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtehwplvrl.html

【收录内容】
来源：http://dali.yonumen.top/Article/details/gtidbfcqhl.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.smart0.xyz/Article/details/gtsrhlbqnb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yj20258888.top/Article/details/gtmavyoohp.html

SQL · Bash · C · C++
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxrzppvrq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xziqi.cn/Article/details/gtfzanizvf.html

【使用说明】
来源：http://dali.bjfxy.top/Article/details/gtjgbfkagu.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.guannengcc.top/Article/details/gtucwymvgr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.mhx1999.top/Article/details/gtxqkzgwaq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gtocuyrage.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.c1oappe.top/Article/details/gtuuqiuyhl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hfpthk.cn/Article/details/gttrmwsklb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yuxming.cn/Article/details/gtjvqklsqu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.daxiang520.top/Article/details/gtoffimhle.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhiwuduotai.top/Article/details/gtazjpkvks.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cheryme.top/Article/details/gtjiuknzkk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cucudq.cn/Article/details/gtuyxinmcb.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xinyue.icu/Article/details/gtcffxzznc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhoulong.xyz/Article/details/gtpfnuxcrj.html

【文件统计】
来源：http://dali.hnxiangtu.top/Article/details/gtrjklipif.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.cdnleiting.top/Article/details/gtzmouuran.html

--------------------------------------------------------------------------------
来源：http://dali.bjfxy.top/Article/details/gtgeraotof.html

目  录
来源：http://dali.zhiwuduotai.top/Article/details/gtwihwmvrd.html

--------------------------------------------------------------------------------
来源：http://dali.xinyue.icu/Article/details/gtiyvzfupx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zdqjudy.top/Article/details/gtflzstzlz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.daria6918.cn/Article/details/gtshlwzblz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntusysuq.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shuidangran.top/Article/details/gtvdgpvboi.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.c1oappe.top/Article/details/gtpktlxuwq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdetyoyh.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hywenlv.cn/Article/details/gtfdrsqjfl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jqgufenzy.top/Article/details/gtnozkydub.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjdfbyop.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtrrpsqvzs.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gtkhqotnfo.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gtdaymbooo.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gtdobajawn.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zycfv.cn/Article/details/gtpizvqbhy.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hnqzz.top/Article/details/gtuqtrhlzr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gtxcifrhpj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.sxryk.cn/Article/details/gtpthnzzvh.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.fengsongda.top/Article/details/gtpsywikhc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.meibo888.top/Article/details/gtxjsjzsln.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daria6918.cn/Article/details/gtlnvjtbsb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhoulong.xyz/Article/details/gtcioagfew.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gttjtsochw.html

A. 基础语法与类型
来源：http://dali.andypj.xyz/Article/details/gtyirjsmdd.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtsrutffly.html

[A01] Hello World
来源：http://dali.ybcxt.top/Article/details/gtkbtmsajo.html

Py:   print("Hello, World!")
来源：http://dali.meibo888.top/Article/details/gtxnxmbwge.html

PHP:  echo "Hello, World!";
来源：http://dali.feifeiyinyue.top/Article/details/gtofebeqhk.html

JS:   console.log("Hello, World!");
来源：http://dali.yj20258.top/Article/details/gtydenrmve.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.gaohongyu789.top/Article/details/gtmcekqdam.html

Java: System.out.println("Hello, World!");
来源：http://dali.shuidangran.top/Article/details/gtsprksgmi.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yj202588.top/Article/details/gtfpfrvles.html

Ruby: puts "Hello, World!"
来源：http://dali.yuanzhike.top/Article/details/gtewtzbyrn.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xuetiantiany.cn/Article/details/gtyflspijm.html

[A02] 变量声明与赋值
来源：http://dali.chenzaomai.com/Article/details/gtqboifxcu.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sysykeji.top/Article/details/gtiqjokqze.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xuanzx.com/Article/details/gtakbaswhs.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ehwqpu.com/Article/details/gtijeezkyp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gthqkrzojn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jqgfzy.top/Article/details/gthqoybwor.html

Go:   name := "Alex"; age := 20
来源：http://dali.pycfn.com/Article/details/gtpnihhtjo.html

Ruby: name = "Alex"; age = 20
来源：http://dali.sysykeji.top/Article/details/gtcjbcdhnl.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.c1oappe.top/Article/details/gtmmtbtuar.html

[A03] 常量定义
来源：http://dali.c1oappe.top/Article/details/gtwuhthdzg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.redwolf501.top/Article/details/gtlusyjojx.html

PHP:  const PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtcazvyigu.html

JS:   const PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtrfuguyuh.html

TS:   const PI: number = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtegcuvfgf.html

Java: static final double PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gtbtjekhsk.html

Go:   const PI = 3.14159
来源：http://dali.gogol.net.cn/Article/details/gtscvpgtzz.html

Ruby: PI = 3.14159
来源：http://dali.jinqigufen.top/Article/details/gtyvrmpvej.html

C#:   const double PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtypvmxzpa.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gtkozbzkjx.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.havefunace.top/Article/details/gtqzgjrzjo.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.316326.xyz/Article/details/gtrzvbvszf.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yvedp.cn/Article/details/gthiysdmcj.html

TS:   typeof x; x instanceof Date
来源：http://dali.sxryk.cn/Article/details/gtbkovllrn.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jianghu66.top/Article/details/gtbhhhlzas.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhiwuduotai.top/Article/details/gtctvpssmq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shuidangran.top/Article/details/gtxsubelce.html

C#:   x.GetType().Name; x is int
来源：http://dali.nanxinkj.top/Article/details/gtfhunooae.html

[A05] 整数除法与取模
来源：http://dali.hongshengwenyu.top/Article/details/gtxaomamje.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.tanke756.top/Article/details/gtjlvuojya.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.fengsongda.top/Article/details/gthvnrkvjm.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xziqi.cn/Article/details/gtauosxxem.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hnqzz.top/Article/details/gtrcobgraj.html

Java: 7 / 2; 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gtsrfouwol.html

Go:   7 / 2; 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtirdrcapm.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtwshmhmid.html

C#:   7 / 2; 7 % 2
来源：http://dali.nanxuanxn.top/Article/details/gtzdygthng.html

[A06] 字符串转数字
来源：http://dali.ppjwa.cn/Article/details/gtpjmrizga.html

Py:   int("42"); float("3.14")
来源：http://dali.hongshengwenyu.top/Article/details/gtnvwaavam.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.daria6918.cn/Article/details/gtuficoqey.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yvedp.cn/Article/details/gtrgrzfchy.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhoulong.xyz/Article/details/gtieqznych.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.iojbl.cn/Article/details/gtjrtvctfz.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yonumen.top/Article/details/gtvojzwbqr.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.nanxinkj.top/Article/details/gtexzdofuz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.svipenyu.cn/Article/details/gtwalnycux.html

[A07] 数字转字符串
来源：http://dali.yueranfly.top/Article/details/gtdtefrctb.html

Py:   str(42)
来源：http://dali.sxryk.cn/Article/details/gtjqgoglvy.html

PHP:  (string) 42; strval(42)
来源：http://dali.zycfv.cn/Article/details/gtfutwakgf.html

JS:   String(42); (42).toString()
来源：http://dali.yj20258.top/Article/details/gtvgsvyiol.html

TS:   String(42)
来源：http://dali.cucudq.cn/Article/details/gtlpgsrkls.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.cheryme.top/Article/details/gtsmjbdong.html

Go:   strconv.Itoa(42)
来源：http://dali.jyoumei.cn/Article/details/gtwtlwvzue.html

Ruby: 42.to_s
来源：http://dali.ivvv.top/Article/details/gtadzmzqey.html

C#:   42.ToString()
来源：http://dali.sxryk.cn/Article/details/gtznxsqqmo.html

[A08] 取整与四舍五入
来源：http://dali.sweek.top/Article/details/gtweflmoob.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.tian-w.cn/Article/details/gteewpzhok.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.xuetiantiany.cn/Article/details/gtaczfodot.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.ydzc1.top/Article/details/gtifyoqdvw.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.pengpengdd.cyou/Article/details/gtlprokjse.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yongpay.top/Article/details/gtxhevcppv.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.cashguo.top/Article/details/gtqmofhrqn.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhoulong.xyz/Article/details/gtuatgdvun.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.kuanghao11.cn/Article/details/gtbagibkku.html

[A09] 绝对值与最大最小值
来源：http://dali.meibo888.top/Article/details/gtijmjnemp.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.c1oappe.top/Article/details/gtmptpioyw.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gtzvrctnen.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yonumen.top/Article/details/gtwjbkcwhk.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gtbngvrzjx.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtespktzyk.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.iojbl.cn/Article/details/gtyywqaxbr.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.fengsongda.top/Article/details/gtoaykooej.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gtaxwoakkc.html

[A10] 生成随机数
来源：http://dali.hywenlv.cn/Article/details/gtessoyzcf.html

Py:   import random; random.randint(1, 100)
来源：http://dali.gaohongyu789.top/Article/details/gtglmpbmbn.html

PHP:  random_int(1, 100);
来源：http://dali.zhongyouzk.top/Article/details/gtumlbfolq.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.birdmap.top/Article/details/gtwrszjzlu.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.9152youxi.cn/Article/details/gtetvgrvxf.html

Java: new Random().nextInt(100) + 1
来源：http://dali.havefunace.top/Article/details/gtloqzrpdd.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jqgfzy.top/Article/details/gtrukhxgqs.html

Ruby: rand(1..100)
来源：http://dali.hongshengwenyu.top/Article/details/gtzlvbvqfp.html

C#:   new Random().Next(1, 101)
来源：http://dali.sufxvd.cn/Article/details/gtbiollwum.html

[A11] 条件表达式（三元）
来源：http://dali.ybcxt.top/Article/details/gtxiqrwjxg.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.shangyingyoupin.top/Article/details/gtkvjeiklp.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hywenlv.cn/Article/details/gtaxpbfgdz.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.tian-w.cn/Article/details/gtmqtkehwh.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.haohaochexian.top/Article/details/gtulcqkzyq.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yuxming.cn/Article/details/gtteznqjxp.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.feifeiyinyue.top/Article/details/gtpjduupmh.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yj20258.top/Article/details/gtwrdocswk.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.xziqi.cn/Article/details/gtepgwxazg.html

[A12] 字符串插值 / 格式化
来源：http://dali.jqgfzy.top/Article/details/gttjvbropl.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.cqqwz.cn/Article/details/gtyvznedgu.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdipjtgbp.html

JS:   `Hello, ${name}!`
来源：http://dali.jqgufenzy.top/Article/details/gtyojhjyuq.html

TS:   `Hello, ${name}!`
来源：http://dali.xinyue.icu/Article/details/gtgmxjthgu.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jqgfzy.top/Article/details/gtmliayzbk.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.gogol.net.cn/Article/details/gtaljthkgi.html

Ruby: "Hello, #{name}!"
来源：http://dali.pycfn.com/Article/details/gtxpxknjlv.html

C#:   $"Hello, {name}!"
来源：http://dali.haohaochexian.top/Article/details/gtrzlrkgtn.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yj20258.top/Article/details/gtwaxbwitb.html

Py:   "第一行\n第二行"
来源：http://dali.xinyue.icu/Article/details/gtxuenmppo.html

PHP:  "第一行\n第二行"
来源：http://dali.sufxvd.cn/Article/details/gtudyoyrso.html

JS:   "第一行\n第二行"
来源：http://dali.gaohongyu789.top/Article/details/gtzwxgydpl.html

TS:   "第一行\n第二行"
来源：http://dali.andypj.xyz/Article/details/gtdzxtttqt.html

Java: "第一行\n第二行"
来源：http://dali.yvedp.cn/Article/details/gtdqxlyrks.html

Go:   "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gtgochldrs.html

Ruby: "第一行\n第二行"
来源：http://dali.xuanzx.com/Article/details/gtozrkkcdy.html

C#:   "第一行\n第二行"
来源：http://dali.xylfe.cn/Article/details/gtmfpsdbgw.html

[A14] 注释写法
来源：http://dali.shzxlz.cn/Article/details/gtezmryvqb.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhongyouzk.top/Article/details/gtntiagyfd.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zdqjudy.top/Article/details/gtgmluwsxc.html

JS:   // 单行；/* 多行 */
来源：http://dali.gzhubu.top/Article/details/gtvuyqshkq.html

TS:   // 单行；/* 多行 */
来源：http://dali.xuanzx.com/Article/details/gtrxvsmzxe.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.9152youxi.cn/Article/details/gtmgudgfnn.html

Go:   // 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gtwwrpspba.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.bjfxy.top/Article/details/gtuvolndga.html

C#:   // 单行；/* 多行 */
来源：http://dali.hnxiangtu.top/Article/details/gtgubsfhfm.html

[A15] 空值判断与默认值
来源：http://dali.fengsongda.top/Article/details/gtpkiinisn.html

Py:   value = data or "默认值"
来源：http://dali.hysaishi.cn/Article/details/gtkzixopim.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.ehwqpu.com/Article/details/gtzpjgzdui.html

JS:   const value = data ?? "默认值";
来源：http://dali.fzhhl.top/Article/details/gtccblwrfk.html

TS:   const value = data ?? "默认值";
来源：http://dali.smart0.xyz/Article/details/gtzizpimpj.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.tanke756.top/Article/details/gtmtwjsrar.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.hnqzz.top/Article/details/gtwywepxxz.html

Ruby: value = data || "默认值"
来源：http://dali.hnxiangtu.top/Article/details/gtryfjqjlw.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhoulong.xyz/Article/details/gtteejldoy.html

[A16] 真假值判断规则
来源：http://dali.yanxiufei.cn/Article/details/gtgrqwbork.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jlsjyb.cn/Article/details/gtmwdutceh.html


<!-- 参考信息 -->