代发 wailian999

[U93] JS：模板字符串
来源：http://dali.yueranfly.top/Article/details/gtznmlsyrw.html

`共 ${n} 条`
来源：http://dali.316326.xyz/Article/details/gtvesvduqv.html

[U94] JS：箭头函数
来源：http://dali.fzhhl.top/Article/details/gtjrfqhvbt.html

const double = x => x * 2;
来源：http://dali.tian-w.cn/Article/details/gtkqqobkbo.html

[U95] JS：Promise 包装
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgekrtknx.html

new Promise((resolve, reject) => {})
来源：http://dali.316326.xyz/Article/details/gtrcdthjma.html

[U96] JS：async/await 与异常
来源：http://dali.yuanzhike.top/Article/details/gtwehuekxa.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gtfqrjptpj.html

[U97] JS：并发请求
来源：http://dali.nanxuanxn.top/Article/details/gtaljeiher.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gtsrvfbwgj.html

[U98] JS：fetch 带 JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnysreyy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yj20258888.top/Article/details/gtebntlnqo.html

[U99] JS：事件监听
来源：http://dali.iojbl.cn/Article/details/gtbjugkevr.html

el.addEventListener("click", e => {})
来源：http://dali.andypj.xyz/Article/details/gtgghlzlov.html

[U100] JS：DOM 查询
来源：http://dali.jqgufenzy.top/Article/details/gthmvdgulj.html

document.querySelector(".item")
来源：http://dali.yangfankeji.com/Article/details/gtzgbssjsu.html

[U101] JS：classList 操作
来源：http://dali.feifeiyinyue.top/Article/details/gtiexknvdx.html

el.classList.toggle("active")
来源：http://dali.haohaochexian.top/Article/details/gtjmxnvcix.html

[U102] JS：本地存储
来源：http://dali.yonumen.top/Article/details/gtawdxokhe.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.c1oappe.top/Article/details/gtqnmfleit.html

[U103] JS：定时器
来源：http://dali.iojbl.cn/Article/details/gtduhuvzfm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.tian-w.cn/Article/details/gtfqqtalhd.html

[U104] JS：防抖
来源：http://dali.sxryk.cn/Article/details/gtusqfecbl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gtrtbvsejz.html

[U105] JS：节流
来源：http://dali.tianlin.xyz/Article/details/gtjsxlnuya.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtredpccgs.html

[U106] JS：日期格式化
来源：http://dali.bjfxy.top/Article/details/gtsxiymglr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ppjwa.cn/Article/details/gtmqspxvqe.html

[U107] JS：数字千分位
来源：http://dali.daxiang520.top/Article/details/gtrybhqosq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yuxming.cn/Article/details/gtrpxsgxfw.html

[U108] JS：随机整数
来源：http://dali.andypj.xyz/Article/details/gtqpsoukwh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.chenzaomai.com/Article/details/gtzahsulpo.html

[U109] JS：数组分组
来源：http://dali.tanke756.top/Article/details/gtpiubyeye.html

Object.groupBy(arr, x => x.type)
来源：http://dali.snrcjt.cn/Article/details/gtxwqvqvmh.html

[U110] JS：数组分块
来源：http://dali.tanke756.top/Article/details/gtbmfjyvhv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.quarkkingdee.top/Article/details/gtsvgeuizx.html

[U111] JS：对象转 Map
来源：http://dali.hnxiangtu.top/Article/details/gtxgjsfcyu.html

new Map(Object.entries(obj))
来源：http://dali.jyoumei.cn/Article/details/gtivsfibhl.html

[U112] JS：字符串补位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzchpdvuh.html

"7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwiuvlsbw.html

[U113] JS：正则替换全部
来源：http://dali.svipenyu.cn/Article/details/gtkmtkfpio.html

s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gthydylntb.html

[U114] JS：JSON 深比较
来源：http://dali.zhixingplan.top/Article/details/gtdbsprngd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.c1oappe.top/Article/details/gtnpmrvxku.html

[U115] JS：生成 UUID
来源：http://dali.dianchejie.cn/Article/details/gtqdceagsw.html

crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gtuvzycywn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.guannengcc.top/Article/details/gtefnajzgv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.tianlin.xyz/Article/details/gtpmykbkpo.html

[U117] JS：单元测试
来源：http://dali.iojbl.cn/Article/details/gtsludmuwr.html

npm i -D vitest;  npx vitest
来源：http://dali.hongshengwenyu.top/Article/details/gtxxwjfaeo.html

[U118] JS：开发服务器
来源：http://dali.sxryk.cn/Article/details/gtqrfneijq.html

npm i -D vite;  npx vite
来源：http://dali.cheryme.top/Article/details/gtjzalgaqk.html

[U119] JS：生产构建
来源：http://dali.kuanghao11.cn/Article/details/gtvhrnsztg.html

npx vite build
来源：http://dali.jqgufenzy.top/Article/details/gtxtuibvle.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xylfe.cn/Article/details/gtzuzdubdz.html

import.meta.env.VITE_API_URL
来源：http://dali.chenjidiqi.icu/Article/details/gtamhyhzll.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtaxhqlxtv.html

统计汇总
来源：http://dali.jinqigfzy.top/Article/details/gtmeiwfxfi.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtyukwgmnw.html

按语言统计（条）：
来源：http://dali.aizwys.cn/Article/details/gtkinfdtbv.html

Python ......... 252
来源：http://dali.jqgufenzy.top/Article/details/gtchkbknbn.html

PHP ............ 252
来源：http://dali.meibo888.top/Article/details/gtkuxjqouf.html

JavaScript ..... 252
来源：http://dali.vqdsnc.cn/Article/details/gtxhuehmkx.html

TypeScript ..... 212
来源：http://dali.snrcjt.cn/Article/details/gtzoegwjnn.html

Java ........... 212
来源：http://dali.nwbrower.top/Article/details/gtrljbmrki.html

Go ............. 212
来源：http://dali.jiagoushi.top/Article/details/gtkdmldazx.html

Ruby ........... 212
来源：http://dali.jinqigufen.top/Article/details/gtrwfnkdlr.html

C# ............. 212
来源：http://dali.hammf.cn/Article/details/gtrlmfzfdy.html

C .............. 30
来源：http://dali.havefunace.top/Article/details/gtjrixkxze.html

C++ ............ 30
来源：http://dali.quarkkingdee.top/Article/details/gtcvxuhuvg.html

SQL ............ 90
来源：http://dali.cucudq.cn/Article/details/gtwbsngtmr.html

Bash ........... 80
来源：http://dali.zdqjudy.top/Article/details/gtbzzorkrv.html

Kotlin ......... 15
来源：http://dali.aizwys.cn/Article/details/gtvryiturl.html

Swift .......... 15
来源：http://dali.haohaochexian.top/Article/details/gtamzxczkh.html

Lua ............ 10
来源：http://dali.jqgufenzy.top/Article/details/gtpsxmvddr.html

Perl ........... 10
来源：http://dali.pycfn.com/Article/details/gtxshvujds.html

Scala .......... 10
来源：http://dali.dashuyun.cn/Article/details/gtfsbezejy.html

------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gtzfsjpbkv.html

合计 ........... 2106 条
来源：http://dali.guowangkeji.top/Article/details/gtcowkvtzg.html

按章节统计：
来源：http://dali.sufxvd.cn/Article/details/gtoxitjxqo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cashguo.top/Article/details/gtcgnlnmfk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xylfe.cn/Article/details/gtgltfwtxc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.tian-w.cn/Article/details/gthbrkswoe.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yvedp.cn/Article/details/gtfrrczrty.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shuidangran.top/Article/details/gtomfwmnwe.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jianghu66.top/Article/details/gtvhmykxyh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yanxiufei.cn/Article/details/gtnoyhcpdu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.andypj.xyz/Article/details/gtfdokxcnv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gtntnrcfpc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shangyingyoupin.top/Article/details/gtedkxbvls.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gtmfptxaxs.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gttxehtksh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gttuygcoir.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.dashuyun.cn/Article/details/gtnmqjexvq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.tianlin.xyz/Article/details/gtkcvqnbpz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtnrsxkdnd.html

Q SQL 专题                              90
来源：http://dali.daxiang520.top/Article/details/gtderydtbk.html

R Bash 专题                             80
来源：http://dali.cdnleiting.top/Article/details/gtgejebxhc.html

S C / C++ 专题                          60
来源：http://dali.birdmap.top/Article/details/gtaliqldfc.html

T 其他语言补充                          60
来源：http://dali.andypj.xyz/Article/details/gtugpazpqe.html

U 高频实用片段                         120
来源：http://dali.hfpthk.cn/Article/details/gtqkyxwxox.html

------------------------------------
来源：http://dali.yongpay.top/Article/details/gtxzvkrqgt.html

合计                                  2106 条
来源：http://dali.hywenlv.cn/Article/details/gtsdagueed.html

--------------------------------------------------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gtulozhqgb.html

使用提醒
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxlwfnce.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gtclsigomv.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.nwbrower.top/Article/details/gttjpjjzfr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xylfe.cn/Article/details/gtjasyzjbo.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xinyue.icu/Article/details/gtcwudljbi.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.tian-w.cn/Article/details/gtfpyqogbd.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.0kj1m.cn/Article/details/gtpmnqxlyl.html

—— 文件结束 ——
来源：http://dali.aizwys.cn/Article/details/gtmqdvhplm.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtdqjazwji.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jiagoushi.top/Article/details/gtksjlpgkv.html

Common Programming Examples Cheat Book
来源：http://dali.bjfxy.top/Article/details/gtlhzfywia.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtthredqjv.html

【收录内容】
来源：http://dali.jyoumei.cn/Article/details/gtnbophdmw.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhixingplan.top/Article/details/gtnreeoyov.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.nanxinkj.top/Article/details/gtjltjuzlg.html

SQL · Bash · C · C++
来源：http://dali.xuanzx.com/Article/details/gtoadsaaka.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.nanxuanxn.top/Article/details/gtnlcaoijm.html

【使用说明】
来源：http://dali.hnqzz.top/Article/details/gtilrraznd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.aizwys.cn/Article/details/gtiotvczzk.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jyoumei.cn/Article/details/gttpvcavuj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.wangshuangyany.cn/Article/details/gtelsmaole.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shuidangran.top/Article/details/gtefjqfwkx.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.nanxinkj.top/Article/details/gtxwtkirfl.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzcnlquq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.dashuyun.cn/Article/details/gtwgkketwl.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.fengsongda.top/Article/details/gtvndvuwgs.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.meibo888.top/Article/details/gtdrwctbpm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.redwolf501.top/Article/details/gtvbbqhebm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.haohaochexian.top/Article/details/gtlzkpqcdv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.guannengcc.top/Article/details/gthslrqagu.html

【文件统计】
来源：http://dali.tian-w.cn/Article/details/gtlilezest.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hongshengwenyu.top/Article/details/gtxxxorshr.html

--------------------------------------------------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gtjutmbbto.html

目  录
来源：http://dali.jianghu66.top/Article/details/gtxpqmljnx.html

--------------------------------------------------------------------------------
来源：http://dali.sysykeji.top/Article/details/gtujjaccxy.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hnxiangtu.top/Article/details/gtsvkezdzq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.guannengcc.top/Article/details/gtkprjejbd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhongyouzk.top/Article/details/gtnhgqdxby.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.gzhubu.top/Article/details/gtinbfifhh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jiagoushi.top/Article/details/gtumabockk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xylfe.cn/Article/details/gtwaydpiyd.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhybphhz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.gotoacloud.top/Article/details/gtfgrbptqc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtwtrktcwg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.sweek.top/Article/details/gtlaqwmqdy.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gtjiyjotuv.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gtwbzwuifg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gtelidfpcr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.tanke756.top/Article/details/gtbzrqflsx.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jqgufenzy.top/Article/details/gtevsndivs.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.fzhhl.top/Article/details/gtjplsmdih.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumwqvvti.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.chenzaomai.com/Article/details/gtuhdwandh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtdixkpwyl.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yanxiufei.cn/Article/details/gtzfquartm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigfzy.top/Article/details/gttlktaros.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtigqwywfa.html

A. 基础语法与类型
来源：http://dali.hnxiangtu.top/Article/details/gtkxnllilf.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtzxzkcqsb.html

[A01] Hello World
来源：http://dali.yueranfly.top/Article/details/gtzogltgbl.html

Py:   print("Hello, World!")
来源：http://dali.pycfn.com/Article/details/gthkmotqxy.html

PHP:  echo "Hello, World!";
来源：http://dali.yj20258.top/Article/details/gtzzobdmqd.html

JS:   console.log("Hello, World!");
来源：http://dali.316326.xyz/Article/details/gtmgdtsttx.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yanxiufei.cn/Article/details/gtdfidwpfa.html

Java: System.out.println("Hello, World!");
来源：http://dali.cashguo.top/Article/details/gtfzcgaxbx.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xuetiantiany.cn/Article/details/gtlrbneukv.html

Ruby: puts "Hello, World!"
来源：http://dali.zhixingplan.top/Article/details/gtpgaizwwv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.vqdsnc.cn/Article/details/gtixxfmcvf.html

[A02] 变量声明与赋值
来源：http://dali.9152youxi.cn/Article/details/gtaoqabdmf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jinqigufen.top/Article/details/gtnhqpgxuy.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ybcxt.top/Article/details/gtkkrnrhsc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhongyouzk.top/Article/details/gtgferfuwc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.guowangkeji.top/Article/details/gtomlsdyrd.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zdqjudy.top/Article/details/gtrkpddkdr.html

Go:   name := "Alex"; age := 20
来源：http://dali.meibo888.top/Article/details/gttpkzjblb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jiagoushi.top/Article/details/gtzivrsqfm.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.wangdashe.top/Article/details/gtgywxztbj.html

[A03] 常量定义
来源：http://dali.daria6918.cn/Article/details/gtzzdqtcnt.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.xinyue.icu/Article/details/gthijwphok.html

PHP:  const PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtdoybxjlj.html

JS:   const PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtqzanrvax.html

TS:   const PI: number = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtweuayhsr.html

Java: static final double PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gteypskqvj.html

Go:   const PI = 3.14159
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrevjjxvs.html

Ruby: PI = 3.14159
来源：http://dali.yangfankeji.com/Article/details/gttpicwttd.html

C#:   const double PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtgdyygaap.html

[A04] 判断变量类型
来源：http://dali.meibo888.top/Article/details/gtwlrxxiur.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.meibo888.top/Article/details/gtgzzhysiu.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yangfankeji.com/Article/details/gtfcwouelk.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.quarkkingdee.top/Article/details/gtnbkhklhy.html

TS:   typeof x; x instanceof Date
来源：http://dali.pycfn.com/Article/details/gtklelejia.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.havefunace.top/Article/details/gtbfmqxwjv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.haohaochexian.top/Article/details/gtnirljqqi.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.meibo888.top/Article/details/gtsrydjmfu.html

C#:   x.GetType().Name; x is int
来源：http://dali.cheryme.top/Article/details/gtypyhjhor.html

[A05] 整数除法与取模
来源：http://dali.vqdsnc.cn/Article/details/gtgeyoqkgh.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.daria6918.cn/Article/details/gtlephozxr.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gteiaacaoc.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.fengsongda.top/Article/details/gtzjfseaak.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gtgwturbcq.html

Java: 7 / 2; 7 % 2
来源：http://dali.iojbl.cn/Article/details/gtwyusesnb.html

Go:   7 / 2; 7 % 2
来源：http://dali.jianghu66.top/Article/details/gtbsnzbnjx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gtwbdnaply.html

C#:   7 / 2; 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gthkfapddr.html

[A06] 字符串转数字
来源：http://dali.iojbl.cn/Article/details/gtvbjwkzda.html

Py:   int("42"); float("3.14")
来源：http://dali.xziqi.cn/Article/details/gtuikseaeu.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gtwghzjrio.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.c1oappe.top/Article/details/gtoghuakmk.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.chenjidiqi.icu/Article/details/gtsddwunty.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.gogol.net.cn/Article/details/gttzzqfszf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.gogol.net.cn/Article/details/gtbtufwiiv.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.dianchejie.cn/Article/details/gtxtssikcr.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.birdmap.top/Article/details/gtjbjjwryh.html

[A07] 数字转字符串
来源：http://dali.c1oappe.top/Article/details/gtwhtwuoue.html

Py:   str(42)
来源：http://dali.jinghuilouyu.cn/Article/details/gtylxogwmk.html

PHP:  (string) 42; strval(42)
来源：http://dali.yj20258888.top/Article/details/gtphxoziuc.html

JS:   String(42); (42).toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtwoqxbcuv.html

TS:   String(42)
来源：http://dali.vqdsnc.cn/Article/details/gtpwjtdncx.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jyoumei.cn/Article/details/gtjiawxxce.html

Go:   strconv.Itoa(42)
来源：http://dali.feifeiyinyue.top/Article/details/gtqkxnvbnv.html

Ruby: 42.to_s
来源：http://dali.fengsongda.top/Article/details/gtpvyqrzas.html

C#:   42.ToString()
来源：http://dali.chenjidiqi.icu/Article/details/gtodrelqdl.html

[A08] 取整与四舍五入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrlhqpiz.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.tianlin.xyz/Article/details/gtkguurcyv.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.pycfn.com/Article/details/gtwlariinu.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.cdnleiting.top/Article/details/gtkmflfjwn.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtabaaymxp.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.tianlin.xyz/Article/details/gtzwpfhfjs.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.chenzaomai.com/Article/details/gtokikfruf.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.haohaochexian.top/Article/details/gtdiqnnpep.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.gaohongyu789.top/Article/details/gtylqunlgj.html

[A09] 绝对值与最大最小值
来源：http://dali.sweek.top/Article/details/gtpgjaoexw.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.daria6918.cn/Article/details/gtcwwnnifg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrjrwwmj.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yj20258.top/Article/details/gtkgzggqhp.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtkknhpgjm.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jianghu66.top/Article/details/gtoxalheva.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yueranfly.top/Article/details/gtnxpycnaf.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.ppjwa.cn/Article/details/gtcdaxdlxp.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtnfbljkrw.html

[A10] 生成随机数
来源：http://dali.cdnleiting.top/Article/details/gttmolwmxk.html

Py:   import random; random.randint(1, 100)
来源：http://dali.hysaishi.cn/Article/details/gtrtddxeza.html

PHP:  random_int(1, 100);
来源：http://dali.ehwqpu.com/Article/details/gtydscaoci.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zdqjudy.top/Article/details/gtuszigwlv.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xylfe.cn/Article/details/gterrlgqlg.html

Java: new Random().nextInt(100) + 1
来源：http://dali.hysaishi.cn/Article/details/gtfsaypseq.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.svipenyu.cn/Article/details/gtuiiugftb.html

Ruby: rand(1..100)
来源：http://dali.hnqzz.top/Article/details/gtihloogcb.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhiwuduotai.top/Article/details/gtfqbpfsqy.html

[A11] 条件表达式（三元）
来源：http://dali.iojbl.cn/Article/details/gteeklbmar.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yanxiufei.cn/Article/details/gtvxebzwvj.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.wangdashe.top/Article/details/gtsfguayyt.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.wangdashe.top/Article/details/gtkikstwpo.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yvedp.cn/Article/details/gtpaxmaiap.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yanxiufei.cn/Article/details/gtoaanvvyn.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.mhx1999.top/Article/details/gthpzeviqv.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yangfankeji.com/Article/details/gtiydtpymt.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.tianlin.xyz/Article/details/gtpbrrcvri.html

[A12] 字符串插值 / 格式化
来源：http://dali.jlsjyb.cn/Article/details/gtvulzvmbp.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.cucudq.cn/Article/details/gtjdnjivwq.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.redwolf501.top/Article/details/gtrteefxdu.html

JS:   `Hello, ${name}!`
来源：http://dali.yueranfly.top/Article/details/gtihtkhtni.html

TS:   `Hello, ${name}!`
来源：http://dali.yongpay.top/Article/details/gtwqjtjlql.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xuanzx.com/Article/details/gtjheeewed.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jinqigufen.top/Article/details/gtletfrjen.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtulpefthg.html

C#:   $"Hello, {name}!"
来源：http://dali.zhiwuduotai.top/Article/details/gtmozljnhw.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.cashguo.top/Article/details/gtlborczgo.html

Py:   "第一行\n第二行"
来源：http://dali.ppjwa.cn/Article/details/gtwqpmisyp.html

PHP:  "第一行\n第二行"
来源：http://dali.tanke756.top/Article/details/gtovywwesn.html

JS:   "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsslmangs.html

TS:   "第一行\n第二行"
来源：http://dali.shuidangran.top/Article/details/gtpcukomta.html

Java: "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gtumzdzmxb.html

Go:   "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gttkhmoxgo.html

Ruby: "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gtyvfirzvv.html

C#:   "第一行\n第二行"
来源：http://dali.yj20258888.top/Article/details/gtzdhkurld.html

[A14] 注释写法
来源：http://dali.jiagoushi.top/Article/details/gtbbzhxrig.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.wangdashe.top/Article/details/gtaullubro.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.cheryme.top/Article/details/gtkfhhoutj.html

JS:   // 单行；/* 多行 */
来源：http://dali.xuetiantiany.cn/Article/details/gtshvrlgrn.html

TS:   // 单行；/* 多行 */
来源：http://dali.feifeiyinyue.top/Article/details/gtfkplpimk.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmcxpxcr.html

Go:   // 单行；/* 多行 */
来源：http://dali.meibo888.top/Article/details/gtjqqylhxl.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.sxryk.cn/Article/details/gtrcxssqob.html

C#:   // 单行；/* 多行 */
来源：http://dali.hfpthk.cn/Article/details/gtxlilhgka.html

[A15] 空值判断与默认值
来源：http://dali.hysaishi.cn/Article/details/gtlrqzvueq.html

Py:   value = data or "默认值"
来源：http://dali.cheryme.top/Article/details/gtjyqwrexr.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.shuidangran.top/Article/details/gtcbcepfnd.html

JS:   const value = data ?? "默认值";
来源：http://dali.yanxiufei.cn/Article/details/gtuvsjyaaj.html

TS:   const value = data ?? "默认值";
来源：http://dali.xuanzx.com/Article/details/gtfkraayao.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqmfenky.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.c1oappe.top/Article/details/gtgxcvbtkt.html

Ruby: value = data || "默认值"
来源：http://dali.ybcxt.top/Article/details/gtackqyome.html

C#:   var value = data ?? "默认值";
来源：http://dali.guannengcc.top/Article/details/gtunvrvufy.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gtgixvocgp.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.quarkkingdee.top/Article/details/gtbeegwbhz.html


<!-- 参考信息 -->