代发 wailian999

[U93] JS：模板字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtxzkivpps.html

`共 ${n} 条`
来源：http://dali.gotoacloud.top/Article/details/gtyqcwlxsi.html

[U94] JS：箭头函数
来源：http://dali.jinqigfzy.top/Article/details/gtymmohhak.html

const double = x => x * 2;
来源：http://dali.guowangkeji.top/Article/details/gtzodwvxnq.html

[U95] JS：Promise 包装
来源：http://dali.yj202588.top/Article/details/gtgsyysthg.html

new Promise((resolve, reject) => {})
来源：http://dali.sufxvd.cn/Article/details/gtwdxcvuup.html

[U96] JS：async/await 与异常
来源：http://dali.svipenyu.cn/Article/details/gtfyelgnxo.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gtxwtzqflg.html

[U97] JS：并发请求
来源：http://dali.chenlongwang.top/Article/details/gtwuwfxbiw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gtngpjfacm.html

[U98] JS：fetch 带 JSON
来源：http://dali.pycfn.com/Article/details/gtlghzqpko.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.iojbl.cn/Article/details/gtwmbevjwu.html

[U99] JS：事件监听
来源：http://dali.xuetiantiany.cn/Article/details/gtscdipgvz.html

el.addEventListener("click", e => {})
来源：http://dali.yuxming.cn/Article/details/gtrwpquoqy.html

[U100] JS：DOM 查询
来源：http://dali.redwolf501.top/Article/details/gtjxzjmjll.html

document.querySelector(".item")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlxdjlvt.html

[U101] JS：classList 操作
来源：http://dali.9152youxi.cn/Article/details/gtjitsprpc.html

el.classList.toggle("active")
来源：http://dali.cheryme.top/Article/details/gtrgijeeyf.html

[U102] JS：本地存储
来源：http://dali.cheryme.top/Article/details/gtfznscaeq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yangfankeji.com/Article/details/gthpuvfkxs.html

[U103] JS：定时器
来源：http://dali.cashguo.top/Article/details/gtjiqrsyor.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.redwolf501.top/Article/details/gtwgsyabxb.html

[U104] JS：防抖
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptmqgjuo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gtxydmilnw.html

[U105] JS：节流
来源：http://dali.bjfxy.top/Article/details/gtazzlzhsn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.feifeiyinyue.top/Article/details/gtvygsizoq.html

[U106] JS：日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gtangkdxxn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hammf.cn/Article/details/gteilirjyq.html

[U107] JS：数字千分位
来源：http://dali.yuxming.cn/Article/details/gtnmxwgzez.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yuxming.cn/Article/details/gtcuhffgdb.html

[U108] JS：随机整数
来源：http://dali.dianchejie.cn/Article/details/gtznisdvbi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xinyue.icu/Article/details/gtfpfaqtmo.html

[U109] JS：数组分组
来源：http://dali.ivvv.top/Article/details/gtwlazzszp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.gogol.net.cn/Article/details/gtqyxauhqd.html

[U110] JS：数组分块
来源：http://dali.zhengqikj.top/Article/details/gtuqobllav.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gotoacloud.top/Article/details/gtyzpjachz.html

[U111] JS：对象转 Map
来源：http://dali.hammf.cn/Article/details/gtesvkxtkc.html

new Map(Object.entries(obj))
来源：http://dali.ehwqpu.com/Article/details/gtormvwxsv.html

[U112] JS：字符串补位
来源：http://dali.yj20258888.top/Article/details/gtrkrcdnaq.html

"7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtckiczqis.html

[U113] JS：正则替换全部
来源：http://dali.ybcxt.top/Article/details/gtdomeqcqp.html

s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtqrymqoja.html

[U114] JS：JSON 深比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzqzyiai.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daxiang520.top/Article/details/gtwqzziggg.html

[U115] JS：生成 UUID
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqpmpklb.html

crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gtrsafaqku.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqqrtutn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.quarkkingdee.top/Article/details/gtidqylzci.html

[U117] JS：单元测试
来源：http://dali.bjfxy.top/Article/details/gtcaxerxee.html

npm i -D vitest;  npx vitest
来源：http://dali.redwolf501.top/Article/details/gtmwoiwxdc.html

[U118] JS：开发服务器
来源：http://dali.meibo888.top/Article/details/gtzwiuvaps.html

npm i -D vite;  npx vite
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpupfdpkq.html

[U119] JS：生产构建
来源：http://dali.9152youxi.cn/Article/details/gtqhloqzcn.html

npx vite build
来源：http://dali.mhx1999.top/Article/details/gtwowodeag.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gtygicgpok.html

import.meta.env.VITE_API_URL
来源：http://dali.jqgfzy.top/Article/details/gtzsgxecge.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtgljoffeo.html

统计汇总
来源：http://dali.zhongyouzk.top/Article/details/gtqtkhckpx.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtntdctzsf.html

按语言统计（条）：
来源：http://dali.chenjidiqi.icu/Article/details/gthizzplnr.html

Python ......... 252
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetizigog.html

PHP ............ 252
来源：http://dali.zhongyouzk.top/Article/details/gtbuyniimk.html

JavaScript ..... 252
来源：http://dali.hammf.cn/Article/details/gteibvuyro.html

TypeScript ..... 212
来源：http://dali.yueranfly.top/Article/details/gtjlymokwf.html

Java ........... 212
来源：http://dali.cucudq.cn/Article/details/gtjezrhlqr.html

Go ............. 212
来源：http://dali.0kj1m.cn/Article/details/gtuaxqyczo.html

Ruby ........... 212
来源：http://dali.hfpthk.cn/Article/details/gtazdrzydx.html

C# ............. 212
来源：http://dali.ehwqpu.com/Article/details/gtcecfvkbs.html

C .............. 30
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozzfyllv.html

C++ ............ 30
来源：http://dali.meibo888.top/Article/details/gtckbykboz.html

SQL ............ 90
来源：http://dali.havefunace.top/Article/details/gtibthbbai.html

Bash ........... 80
来源：http://dali.yj20258888.top/Article/details/gtcsrhujdv.html

Kotlin ......... 15
来源：http://dali.pycfn.com/Article/details/gtystqhulu.html

Swift .......... 15
来源：http://dali.sweek.top/Article/details/gtcjserver.html

Lua ............ 10
来源：http://dali.shanyushiyangtech.top/Article/details/gtxsnecalg.html

Perl ........... 10
来源：http://dali.birdmap.top/Article/details/gtbswqcjxn.html

Scala .......... 10
来源：http://dali.meibo888.top/Article/details/gttxlosgbi.html

------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gtrymixoep.html

合计 ........... 2106 条
来源：http://dali.chenzaomai.com/Article/details/gtofdogood.html

按章节统计：
来源：http://dali.tianlin.xyz/Article/details/gtjdmnupzu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yueranfly.top/Article/details/gtezriivhd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.snrcjt.cn/Article/details/gtcsusgrur.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gtcmofunel.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.vqdsnc.cn/Article/details/gtfdwtgvdk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.fzhhl.top/Article/details/gtipuwxuqn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yuanzhike.top/Article/details/gtkpdegzdd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gtaauxvtkr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yj20258.top/Article/details/gtyrjwtjpu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gteknqgiqj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.meibo888.top/Article/details/gtznjzywtu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gtlttsfyxn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtwmtjvoue.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gtlgthtivt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cdnleiting.top/Article/details/gtkljiwwlk.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yuxming.cn/Article/details/gtbselzvrn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gtulanzigf.html

Q SQL 专题                              90
来源：http://dali.jyoumei.cn/Article/details/gtbnxfiqfu.html

R Bash 专题                             80
来源：http://dali.hysaishi.cn/Article/details/gtacvjfjgr.html

S C / C++ 专题                          60
来源：http://dali.cqqwz.cn/Article/details/gtvnmltccx.html

T 其他语言补充                          60
来源：http://dali.bjfxy.top/Article/details/gtvyjfuffg.html

U 高频实用片段                         120
来源：http://dali.zdqjudy.top/Article/details/gtjzhydnzg.html

------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gtjfpehnkp.html

合计                                  2106 条
来源：http://dali.yueranfly.top/Article/details/gtgnwxnlxg.html

--------------------------------------------------------------------------------
来源：http://dali.sweek.top/Article/details/gtdfehytjx.html

使用提醒
来源：http://dali.jqgfzy.top/Article/details/gtjkxzpxuj.html

--------------------------------------------------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gtdpbuywko.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hywenlv.cn/Article/details/gtlkptqxrj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yongpay.top/Article/details/gtnfjyctml.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yvedp.cn/Article/details/gtcfqujlny.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhengqikj.top/Article/details/gtrxswbszj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hnxiangtu.top/Article/details/gtktiurlpu.html

—— 文件结束 ——
来源：http://dali.daxiang520.top/Article/details/gtactsuouj.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtnocnvebw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.bjfxy.top/Article/details/gtuzvmysts.html

Common Programming Examples Cheat Book
来源：http://dali.smart0.xyz/Article/details/gtyxpikccs.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtgfgtdtyt.html

【收录内容】
来源：http://dali.guannengcc.top/Article/details/gttnfdusso.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.aizwys.cn/Article/details/gtgsnfhckd.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.redwolf501.top/Article/details/gtosahbmhi.html

SQL · Bash · C · C++
来源：http://dali.wangshuangyany.cn/Article/details/gthbprlaiy.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.tianlin.xyz/Article/details/gtpnykzckw.html

【使用说明】
来源：http://dali.bjfxy.top/Article/details/gtfhjbekzt.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.chenlongwang.top/Article/details/gtsvpfrdpm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yongpay.top/Article/details/gttcxiqeuw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hnxiangtu.top/Article/details/gtjtutbpyy.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yvedp.cn/Article/details/gtannkzyeo.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.gotoacloud.top/Article/details/gtcpiebwfv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenlongwang.top/Article/details/gtmlcdcqbl.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.smart0.xyz/Article/details/gttpqaagnh.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.fzhhl.top/Article/details/gttmtjomsw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shuidangran.top/Article/details/gtymouhyps.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.gaohongyu789.top/Article/details/gtplecbvec.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.nwbrower.top/Article/details/gtplxgwpmo.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yonumen.top/Article/details/gtzejczrji.html

【文件统计】
来源：http://dali.wangshuangyany.cn/Article/details/gtqugsibzr.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hongshengwenyu.top/Article/details/gtmppiddzu.html

--------------------------------------------------------------------------------
来源：http://dali.guannengcc.top/Article/details/gtnsqcokbr.html

目  录
来源：http://dali.jinghuilouyu.cn/Article/details/gtzsfhkgaj.html

--------------------------------------------------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gtkdqowwcz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.fengsongda.top/Article/details/gthryfqydq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yvedp.cn/Article/details/gtaoleekgy.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.pycfn.com/Article/details/gtoakmnclx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhengqikj.top/Article/details/gtdaqjzxmr.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.guannengcc.top/Article/details/gtqdoaqwlb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.fengsongda.top/Article/details/gtvtjmqrce.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.wangdashe.top/Article/details/gtpqfgghth.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.nanxinkj.top/Article/details/gtgjlfbzph.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.wangdashe.top/Article/details/gtoehcqjoy.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.haohaochexian.top/Article/details/gtmbnastxq.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwumfcman.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gtxujyxort.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.birdmap.top/Article/details/gtwdjzzgvp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.havefunace.top/Article/details/gtuehxeoip.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ppjwa.cn/Article/details/gtdcducvbs.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gtcrcjpnuf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.chenlongwang.top/Article/details/gtntuxxqic.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.wangdashe.top/Article/details/gtetmffskh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yongpay.top/Article/details/gtnituujce.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hysaishi.cn/Article/details/gtkxxgqxtz.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.gzhubu.top/Article/details/gtooqtyxip.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gttlctqjhd.html

A. 基础语法与类型
来源：http://dali.zhengqikj.top/Article/details/gtbhgsgtnp.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtajfisvrq.html

[A01] Hello World
来源：http://dali.hnqzz.top/Article/details/gtnkcasbct.html

Py:   print("Hello, World!")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpcflmnrf.html

PHP:  echo "Hello, World!";
来源：http://dali.yangfankeji.com/Article/details/gthwhiogxn.html

JS:   console.log("Hello, World!");
来源：http://dali.jinqigfzy.top/Article/details/gtclvbuiww.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hammf.cn/Article/details/gtennreelb.html

Java: System.out.println("Hello, World!");
来源：http://dali.tianlin.xyz/Article/details/gtdmtyxqdj.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jinqigufen.top/Article/details/gtfumxjiek.html

Ruby: puts "Hello, World!"
来源：http://dali.ivvv.top/Article/details/gtzknuvtzr.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.dashuyun.cn/Article/details/gtzsbnhpwl.html

[A02] 变量声明与赋值
来源：http://dali.aizwys.cn/Article/details/gtlmjaabyu.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.gogol.net.cn/Article/details/gtvptsxfmk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jqgfzy.top/Article/details/gtvniyaybg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cashguo.top/Article/details/gtlkgxlvzt.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.dashuyun.cn/Article/details/gtjotvlols.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.cheryme.top/Article/details/gtbuutaism.html

Go:   name := "Alex"; age := 20
来源：http://dali.zdqjudy.top/Article/details/gtqevbzksl.html

Ruby: name = "Alex"; age = 20
来源：http://dali.tanke756.top/Article/details/gtegcwvauh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.guannengcc.top/Article/details/gtftnvsxgd.html

[A03] 常量定义
来源：http://dali.cashguo.top/Article/details/gttroceacv.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.chenzaomai.com/Article/details/gtcktzlecb.html

PHP:  const PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtzpuzgpbg.html

JS:   const PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtwfawiokg.html

TS:   const PI: number = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtdickpoce.html

Java: static final double PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtybkxmcck.html

Go:   const PI = 3.14159
来源：http://dali.pycfn.com/Article/details/gtotldvqqi.html

Ruby: PI = 3.14159
来源：http://dali.xinyue.icu/Article/details/gtebgtnovo.html

C#:   const double PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtviuvsiar.html

[A04] 判断变量类型
来源：http://dali.yanxiufei.cn/Article/details/gtfeftfilf.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ybcxt.top/Article/details/gtxaolsnwc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cqqwz.cn/Article/details/gtzlezhzzs.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.316326.xyz/Article/details/gtwwthmpju.html

TS:   typeof x; x instanceof Date
来源：http://dali.pengpengdd.cyou/Article/details/gttnidqzbh.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hfpthk.cn/Article/details/gtrhqtgrvo.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jlsjyb.cn/Article/details/gtcdcybdum.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.hongshengwenyu.top/Article/details/gtalnfxthk.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhongyouzk.top/Article/details/gtwjjstett.html

[A05] 整数除法与取模
来源：http://dali.zhoulong.xyz/Article/details/gtwscrgfyq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.tian-w.cn/Article/details/gtdqbahixe.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xuanzx.com/Article/details/gttkgbfnqt.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtneawzbzp.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhoulong.xyz/Article/details/gtwitmwtub.html

Java: 7 / 2; 7 % 2
来源：http://dali.cucudq.cn/Article/details/gtmkebtlld.html

Go:   7 / 2; 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gttztkftwq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yongpay.top/Article/details/gtflfvegkf.html

C#:   7 / 2; 7 % 2
来源：http://dali.cashguo.top/Article/details/gtgzdogxkk.html

[A06] 字符串转数字
来源：http://dali.xziqi.cn/Article/details/gtvmblqxnc.html

Py:   int("42"); float("3.14")
来源：http://dali.xuanzx.com/Article/details/gtmtkcnubt.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.kuanghao11.cn/Article/details/gtfnotrfiw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.aibaodan.cn/Article/details/gtgamaaqed.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zdqjudy.top/Article/details/gtqytvsbid.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmadxttvf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.xylfe.cn/Article/details/gtvmaiipdk.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zdqjudy.top/Article/details/gtsqqaqzxg.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.iojbl.cn/Article/details/gtwgjpdmry.html

[A07] 数字转字符串
来源：http://dali.zhengqikj.top/Article/details/gtuipoxhgr.html

Py:   str(42)
来源：http://dali.yj20258.top/Article/details/gtvcvmumpp.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhixingplan.top/Article/details/gtkzbqzesg.html

JS:   String(42); (42).toString()
来源：http://dali.wangdashe.top/Article/details/gtagoyxsjd.html

TS:   String(42)
来源：http://dali.vqdsnc.cn/Article/details/gtummgpmru.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.chenjidiqi.icu/Article/details/gthgtihfov.html

Go:   strconv.Itoa(42)
来源：http://dali.shangyingyoupin.top/Article/details/gtrqokvnom.html

Ruby: 42.to_s
来源：http://dali.ybcxt.top/Article/details/gthhcdcvdd.html

C#:   42.ToString()
来源：http://dali.chenlongwang.top/Article/details/gtpqsiwjor.html

[A08] 取整与四舍五入
来源：http://dali.yanxiufei.cn/Article/details/gtggvxlilt.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.daxiang520.top/Article/details/gtoftvjsvl.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ppjwa.cn/Article/details/gtcgqpfyul.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jlsjyb.cn/Article/details/gtctrcmvof.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhoulong.xyz/Article/details/gtthjbztpr.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.shzxlz.cn/Article/details/gtisuksmpz.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgjkvlji.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.ybcxt.top/Article/details/gtxcxupirz.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hnqzz.top/Article/details/gtikalmbcz.html

[A09] 绝对值与最大最小值
来源：http://dali.tanke756.top/Article/details/gtyhctkulc.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gtehpqghij.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cheryme.top/Article/details/gtcdoxmxyf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexcdkjqz.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtwxhaupfi.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.guannengcc.top/Article/details/gtgzsispnl.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hnxiangtu.top/Article/details/gtohghhlhy.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.aibaodan.cn/Article/details/gtumrmnsgh.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.hnqzz.top/Article/details/gtvcjwkily.html

[A10] 生成随机数
来源：http://dali.shzxlz.cn/Article/details/gttcneegyc.html

Py:   import random; random.randint(1, 100)
来源：http://dali.0kj1m.cn/Article/details/gtgjdnjdsl.html

PHP:  random_int(1, 100);
来源：http://dali.zhoulong.xyz/Article/details/gtrbseslpo.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.pycfn.com/Article/details/gtoloplara.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yueranfly.top/Article/details/gtpdcmbxoc.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yj20258.top/Article/details/gtcjuyuxva.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yuxming.cn/Article/details/gtiuhwxbdp.html

Ruby: rand(1..100)
来源：http://dali.ehwqpu.com/Article/details/gtwzyunsuc.html

C#:   new Random().Next(1, 101)
来源：http://dali.daria6918.cn/Article/details/gtnhnorhll.html

[A11] 条件表达式（三元）
来源：http://dali.gaohongyu789.top/Article/details/gtomdrnhrl.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.fzhhl.top/Article/details/gtjesikugx.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.9152youxi.cn/Article/details/gtolektoll.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.redwolf501.top/Article/details/gtzxmurcwe.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jqgufenzy.top/Article/details/gttwikhniy.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhengqikj.top/Article/details/gtuhmlkjbw.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.shzxlz.cn/Article/details/gtboalbygp.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jyoumei.cn/Article/details/gttqaejljp.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jqgfzy.top/Article/details/gtbkoauxnj.html

[A12] 字符串插值 / 格式化
来源：http://dali.fengsongda.top/Article/details/gtpfopmbmt.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yueranfly.top/Article/details/gtdtbconvo.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.birdmap.top/Article/details/gtpfwwppme.html

JS:   `Hello, ${name}!`
来源：http://dali.fzhhl.top/Article/details/gtbefvgucw.html

TS:   `Hello, ${name}!`
来源：http://dali.pengpengdd.cyou/Article/details/gtrrjejqhe.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.fzhhl.top/Article/details/gtbiapkcbl.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.birdmap.top/Article/details/gticclpbqq.html

Ruby: "Hello, #{name}!"
来源：http://dali.jinqigufen.top/Article/details/gtvvsruavl.html

C#:   $"Hello, {name}!"
来源：http://dali.jinghuilouyu.cn/Article/details/gtifiwheur.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.nanxinkj.top/Article/details/gtirqihddq.html

Py:   "第一行\n第二行"
来源：http://dali.c1oappe.top/Article/details/gtwjameefy.html

PHP:  "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gtbntpllln.html

JS:   "第一行\n第二行"
来源：http://dali.gotoacloud.top/Article/details/gtjcixwtku.html

TS:   "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gtodvcqplr.html

Java: "第一行\n第二行"
来源：http://dali.jqgufenzy.top/Article/details/gtleteltoa.html

Go:   "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gtcxyjvdah.html

Ruby: "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gthigytutw.html

C#:   "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gtqjzknaij.html

[A14] 注释写法
来源：http://dali.yuanzhike.top/Article/details/gtevprctwh.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.andypj.xyz/Article/details/gthmczfvar.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yj202588.top/Article/details/gtvcvznkfz.html

JS:   // 单行；/* 多行 */
来源：http://dali.jyoumei.cn/Article/details/gtqanawncm.html

TS:   // 单行；/* 多行 */
来源：http://dali.hysaishi.cn/Article/details/gtntioycrj.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.aibaodan.cn/Article/details/gtgbcvpcju.html

Go:   // 单行；/* 多行 */
来源：http://dali.hywenlv.cn/Article/details/gtlbbgtqde.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.9152youxi.cn/Article/details/gtvkvbpvgn.html

C#:   // 单行；/* 多行 */
来源：http://dali.pengpengdd.cyou/Article/details/gtzigbnxrv.html

[A15] 空值判断与默认值
来源：http://dali.sysykeji.top/Article/details/gtruzaqdpt.html

Py:   value = data or "默认值"
来源：http://dali.havefunace.top/Article/details/gtynljrtar.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.316326.xyz/Article/details/gtrxopcnzm.html

JS:   const value = data ?? "默认值";
来源：http://dali.wangdashe.top/Article/details/gtylckattc.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhixingplan.top/Article/details/gtwmaevsky.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zycfv.cn/Article/details/gtcrvdhqtj.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.aizwys.cn/Article/details/gttirhtdrj.html

Ruby: value = data || "默认值"
来源：http://dali.tanke756.top/Article/details/gtsgjlevak.html

C#:   var value = data ?? "默认值";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjdelwys.html

[A16] 真假值判断规则
来源：http://dali.daria6918.cn/Article/details/gtfvvukkvf.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.feifeiyinyue.top/Article/details/gtrkhuvgqb.html


<!-- 参考信息 -->