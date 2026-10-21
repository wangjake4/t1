代发 wailian999

[U93] JS：模板字符串
来源：http://dali.xylfe.cn/Article/details/gtyxpshtuu.html

`共 ${n} 条`
来源：http://dali.jinqigfzy.top/Article/details/gtpjckzmrz.html

[U94] JS：箭头函数
来源：http://dali.aibaodan.cn/Article/details/gtgodcgkyt.html

const double = x => x * 2;
来源：http://dali.316326.xyz/Article/details/gtkwbvlenh.html

[U95] JS：Promise 包装
来源：http://dali.jqgufenzy.top/Article/details/gtkqbxqqye.html

new Promise((resolve, reject) => {})
来源：http://dali.ydzc1.top/Article/details/gtcxqdtehc.html

[U96] JS：async/await 与异常
来源：http://dali.tianlin.xyz/Article/details/gtkekkgrhc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gtbfbsuerf.html

[U97] JS：并发请求
来源：http://dali.meibo888.top/Article/details/gtdmbeokdf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gtyqikgszc.html

[U98] JS：fetch 带 JSON
来源：http://dali.wangdashe.top/Article/details/gtqvmsvobd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.guannengcc.top/Article/details/gtbpajphhx.html

[U99] JS：事件监听
来源：http://dali.sweek.top/Article/details/gtgjusiusb.html

el.addEventListener("click", e => {})
来源：http://dali.xziqi.cn/Article/details/gtgmmzpjij.html

[U100] JS：DOM 查询
来源：http://dali.guannengcc.top/Article/details/gtvznjtwqj.html

document.querySelector(".item")
来源：http://dali.316326.xyz/Article/details/gtpgugifbc.html

[U101] JS：classList 操作
来源：http://dali.svipenyu.cn/Article/details/gtyyxtooti.html

el.classList.toggle("active")
来源：http://dali.birdmap.top/Article/details/gtexapgylo.html

[U102] JS：本地存储
来源：http://dali.xylfe.cn/Article/details/gtlyyaxjpx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.kuanghao11.cn/Article/details/gtwpunrayc.html

[U103] JS：定时器
来源：http://dali.jyoumei.cn/Article/details/gtqhdsrwgk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yongpay.top/Article/details/gtualmeuwb.html

[U104] JS：防抖
来源：http://dali.cucudq.cn/Article/details/gtxgdeocqo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gtjmaeuvru.html

[U105] JS：节流
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxmfmzln.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.pycfn.com/Article/details/gtpbrbykww.html

[U106] JS：日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtmtmqyqov.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctnnibog.html

[U107] JS：数字千分位
来源：http://dali.hongshengwenyu.top/Article/details/gtcghhaulg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gtuafkxiay.html

[U108] JS：随机整数
来源：http://dali.yueranfly.top/Article/details/gtjmqmjuck.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yongpay.top/Article/details/gthgosbdgj.html

[U109] JS：数组分组
来源：http://dali.pycfn.com/Article/details/gtscsfvzna.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shuidangran.top/Article/details/gtwihkmxxl.html

[U110] JS：数组分块
来源：http://dali.vqdsnc.cn/Article/details/gtkskxarcn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.tanke756.top/Article/details/gtchvblftq.html

[U111] JS：对象转 Map
来源：http://dali.yuxming.cn/Article/details/gtokqqryyh.html

new Map(Object.entries(obj))
来源：http://dali.yuxming.cn/Article/details/gtupmqktyi.html

[U112] JS：字符串补位
来源：http://dali.hnqzz.top/Article/details/gtzpcwypqr.html

"7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtjhmtropd.html

[U113] JS：正则替换全部
来源：http://dali.zdqjudy.top/Article/details/gtpzfsgmun.html

s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtqrapvddp.html

[U114] JS：JSON 深比较
来源：http://dali.yongpay.top/Article/details/gtquzwgtay.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jianghu66.top/Article/details/gtgxedompu.html

[U115] JS：生成 UUID
来源：http://dali.jinqigfzy.top/Article/details/gtvqjzezqh.html

crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gtutcrscnq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.wangdashe.top/Article/details/gtbvbrlbiv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdratbylu.html

[U117] JS：单元测试
来源：http://dali.haohaochexian.top/Article/details/gtfjjhvxjd.html

npm i -D vitest;  npx vitest
来源：http://dali.9152youxi.cn/Article/details/gtukzwxgsd.html

[U118] JS：开发服务器
来源：http://dali.pycfn.com/Article/details/gtsauwpyxu.html

npm i -D vite;  npx vite
来源：http://dali.jianghu66.top/Article/details/gtsjfkcowk.html

[U119] JS：生产构建
来源：http://dali.yanxiufei.cn/Article/details/gtwbguofys.html

npx vite build
来源：http://dali.0kj1m.cn/Article/details/gtcqmsvduv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gtpempvjqx.html

import.meta.env.VITE_API_URL
来源：http://dali.daria6918.cn/Article/details/gtkzpofazy.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtacewihjf.html

统计汇总
来源：http://dali.guowangkeji.top/Article/details/gttlfvjdqt.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtejvjmspc.html

按语言统计（条）：
来源：http://dali.jinqigufen.top/Article/details/gtnxzsiqat.html

Python ......... 252
来源：http://dali.pycfn.com/Article/details/gtlxzgckqt.html

PHP ............ 252
来源：http://dali.zhixingplan.top/Article/details/gtbgodlbge.html

JavaScript ..... 252
来源：http://dali.xylfe.cn/Article/details/gtpmlpitoc.html

TypeScript ..... 212
来源：http://dali.gogol.net.cn/Article/details/gthduyzvkb.html

Java ........... 212
来源：http://dali.havefunace.top/Article/details/gtfgbylasy.html

Go ............. 212
来源：http://dali.shangyingyoupin.top/Article/details/gtvrwbhekj.html

Ruby ........... 212
来源：http://dali.andypj.xyz/Article/details/gtmpmgkomj.html

C# ............. 212
来源：http://dali.daria6918.cn/Article/details/gttwhbuwnv.html

C .............. 30
来源：http://dali.tanke756.top/Article/details/gtouhytujc.html

C++ ............ 30
来源：http://dali.cdnleiting.top/Article/details/gtpmucqrhd.html

SQL ............ 90
来源：http://dali.guowangkeji.top/Article/details/gtmuiivetj.html

Bash ........... 80
来源：http://dali.iojbl.cn/Article/details/gtcmzrnpzw.html

Kotlin ......... 15
来源：http://dali.smart0.xyz/Article/details/gtaibrmmiw.html

Swift .......... 15
来源：http://dali.zycfv.cn/Article/details/gtgxjspipt.html

Lua ............ 10
来源：http://dali.bjfxy.top/Article/details/gtijpaukpn.html

Perl ........... 10
来源：http://dali.wangshuangyany.cn/Article/details/gtayctpuik.html

Scala .......... 10
来源：http://dali.jyoumei.cn/Article/details/gtekkwbujy.html

------------------------------------
来源：http://dali.yuxming.cn/Article/details/gtefzyader.html

合计 ........... 2106 条
来源：http://dali.aibaodan.cn/Article/details/gtkyoogkyi.html

按章节统计：
来源：http://dali.jqgufenzy.top/Article/details/gtubfpprvi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yj20258888.top/Article/details/gtqqefjgwe.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.haohaochexian.top/Article/details/gtpfrychfu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gtlignbgaf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gtqcbynwye.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.pycfn.com/Article/details/gtrcxpqjwm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jinqigfzy.top/Article/details/gtfffspaci.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.fengsongda.top/Article/details/gtbbtrpzxk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmndphtt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gtjvsvecyw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gotoacloud.top/Article/details/gtcgkhwulo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gtojsghpyb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.dianchejie.cn/Article/details/gtjibsufbg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gtosvldmqo.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.tian-w.cn/Article/details/gtrjdzjigi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvivkijw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gtctnejkff.html

Q SQL 专题                              90
来源：http://dali.jyoumei.cn/Article/details/gttkxufzsh.html

R Bash 专题                             80
来源：http://dali.cheryme.top/Article/details/gtkgsypudt.html

S C / C++ 专题                          60
来源：http://dali.yj20258.top/Article/details/gtnxroxyvm.html

T 其他语言补充                          60
来源：http://dali.shangyingyoupin.top/Article/details/gtbvzzbpzl.html

U 高频实用片段                         120
来源：http://dali.redwolf501.top/Article/details/gtfxjbymtl.html

------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gthngfwozo.html

合计                                  2106 条
来源：http://dali.feifeiyinyue.top/Article/details/gtaolosmaq.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gtniujoqit.html

使用提醒
来源：http://dali.sxryk.cn/Article/details/gtxwyjojpw.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtzmajrzry.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.chenzaomai.com/Article/details/gtvbvyuvsd.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhoulong.xyz/Article/details/gtblvahsox.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhixingplan.top/Article/details/gtqinqdequ.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jinqigfzy.top/Article/details/gtjexunrex.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yuxming.cn/Article/details/gtujhjkofj.html

—— 文件结束 ——
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxgwylqk.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtdkmfljys.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.daxiang520.top/Article/details/gtuwbnduyo.html

Common Programming Examples Cheat Book
来源：http://dali.yj20258.top/Article/details/gtofbwqpiq.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtooysnoyq.html

【收录内容】
来源：http://dali.snrcjt.cn/Article/details/gtioutxzda.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.sxryk.cn/Article/details/gttpxjtghi.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yuxming.cn/Article/details/gtlpnzfzfj.html

SQL · Bash · C · C++
来源：http://dali.kuanghao11.cn/Article/details/gtburxfrhl.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.bjfxy.top/Article/details/gtooexxfyn.html

【使用说明】
来源：http://dali.pengpengdd.cyou/Article/details/gtblviifrb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvcmcnul.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hnqzz.top/Article/details/gtszgmrpne.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.shangyingyoupin.top/Article/details/gtxdheuatl.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.nanxuanxn.top/Article/details/gtweqgurfx.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jinqigufen.top/Article/details/gtdcisjnrq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.aizwys.cn/Article/details/gtkcmxgkwv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.shzxlz.cn/Article/details/gtgncnxsce.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.sxryk.cn/Article/details/gtrlhcgyga.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cheryme.top/Article/details/gtrqhifgdl.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cheryme.top/Article/details/gtrfrzovwz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zycfv.cn/Article/details/gtmdfrxtxr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.nwbrower.top/Article/details/gtqqlpdjyp.html

【文件统计】
来源：http://dali.cqqwz.cn/Article/details/gterpdrysw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hysaishi.cn/Article/details/gtnrdrwmco.html

--------------------------------------------------------------------------------
来源：http://dali.gzhubu.top/Article/details/gthixnzyyc.html

目  录
来源：http://dali.jinqigufen.top/Article/details/gtqxrjwbir.html

--------------------------------------------------------------------------------
来源：http://dali.fzhhl.top/Article/details/gtixroqigb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtnlpwprdf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtjuaxaihh.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yonumen.top/Article/details/gtxwtqeebu.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.fzhhl.top/Article/details/gthxgwwtgk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yueranfly.top/Article/details/gttzfsnxpj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yj202588.top/Article/details/gtrizrayjs.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yueranfly.top/Article/details/gtfbryncnt.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yvedp.cn/Article/details/gttfttygnt.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhixingplan.top/Article/details/gtvhvyxwve.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhmnrghw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.chenzaomai.com/Article/details/gtmtdtxnto.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yanxiufei.cn/Article/details/gtfkdffifr.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtjpjvdqzr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.nanxinkj.top/Article/details/gtvsiyutpj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.cashguo.top/Article/details/gtplpbiqdc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtnbbfjhhl.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.c1oappe.top/Article/details/gtcyairast.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.chenzaomai.com/Article/details/gtayafsmse.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtrvprgkxy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigufen.top/Article/details/gtndlzninq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.vqdsnc.cn/Article/details/gtswmuqllf.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtpvztlelc.html

A. 基础语法与类型
来源：http://dali.shzxlz.cn/Article/details/gtslrgddlk.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtvthcpidi.html

[A01] Hello World
来源：http://dali.yuxming.cn/Article/details/gtzoeskwbh.html

Py:   print("Hello, World!")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqxazuyf.html

PHP:  echo "Hello, World!";
来源：http://dali.guowangkeji.top/Article/details/gtlmaiqgif.html

JS:   console.log("Hello, World!");
来源：http://dali.zhongyouzk.top/Article/details/gttflplxwh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.meibo888.top/Article/details/gtpwojzpsb.html

Java: System.out.println("Hello, World!");
来源：http://dali.tanke756.top/Article/details/gtdctxsjtc.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ybcxt.top/Article/details/gtbuvepcgx.html

Ruby: puts "Hello, World!"
来源：http://dali.jinghuilouyu.cn/Article/details/gtiqqksvky.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.kuanghao11.cn/Article/details/gtprukuzqq.html

[A02] 变量声明与赋值
来源：http://dali.gogol.net.cn/Article/details/gtffhbnvot.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yj20258.top/Article/details/gtqbhjgqay.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.quarkkingdee.top/Article/details/gtfuvwrxbc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojkavtpf.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yanxiufei.cn/Article/details/gttpzopbfy.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ybcxt.top/Article/details/gtfnvwvecf.html

Go:   name := "Alex"; age := 20
来源：http://dali.cashguo.top/Article/details/gtffgspbme.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xuanzx.com/Article/details/gtrisophvn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhengqikj.top/Article/details/gtphrutfgb.html

[A03] 常量定义
来源：http://dali.hnxiangtu.top/Article/details/gtdbcuuhsz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shuidangran.top/Article/details/gtqlevfpcb.html

PHP:  const PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtoebuoezd.html

JS:   const PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvfpugbh.html

TS:   const PI: number = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gteehchyfu.html

Java: static final double PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gtbmjvbego.html

Go:   const PI = 3.14159
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajiiuhzb.html

Ruby: PI = 3.14159
来源：http://dali.ydzc1.top/Article/details/gtukviipai.html

C#:   const double PI = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtnxqxjbzc.html

[A04] 判断变量类型
来源：http://dali.bjfxy.top/Article/details/gtxplsohkz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.bjfxy.top/Article/details/gtjlsdvqgj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.0kj1m.cn/Article/details/gtiodvfesc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xziqi.cn/Article/details/gteahghbjc.html

TS:   typeof x; x instanceof Date
来源：http://dali.cqqwz.cn/Article/details/gtolzimxlt.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.daxiang520.top/Article/details/gtodzfecsm.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsakzbqvb.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.gotoacloud.top/Article/details/gtkxtsxmcd.html

C#:   x.GetType().Name; x is int
来源：http://dali.jianghu66.top/Article/details/gtdfasynhx.html

[A05] 整数除法与取模
来源：http://dali.gotoacloud.top/Article/details/gtcpzjdrxf.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.gogol.net.cn/Article/details/gteoftbcbq.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgktdzks.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtpugilfde.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtycrfcdeu.html

Java: 7 / 2; 7 % 2
来源：http://dali.fengsongda.top/Article/details/gtezfuoccx.html

Go:   7 / 2; 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtebnnijco.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.sxryk.cn/Article/details/gtajnnkqbx.html

C#:   7 / 2; 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gtjmicywbf.html

[A06] 字符串转数字
来源：http://dali.jyoumei.cn/Article/details/gtdhjglcne.html

Py:   int("42"); float("3.14")
来源：http://dali.zhongyouzk.top/Article/details/gtxqivqxqu.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.sysykeji.top/Article/details/gtqdyqqtwr.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hnqzz.top/Article/details/gthbzrrgmo.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hammf.cn/Article/details/gtwbcrkhyu.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cucudq.cn/Article/details/gtsegewfim.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.chenjidiqi.icu/Article/details/gtalkfemrm.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.daxiang520.top/Article/details/gtrhtfmhvq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.dianchejie.cn/Article/details/gtoloxgcsz.html

[A07] 数字转字符串
来源：http://dali.yvedp.cn/Article/details/gtxovstxvk.html

Py:   str(42)
来源：http://dali.snrcjt.cn/Article/details/gtmkalpxke.html

PHP:  (string) 42; strval(42)
来源：http://dali.mhx1999.top/Article/details/gtbntpzufm.html

JS:   String(42); (42).toString()
来源：http://dali.zhixingplan.top/Article/details/gtlsmccyjn.html

TS:   String(42)
来源：http://dali.smart0.xyz/Article/details/gtuxbfukxi.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.vqdsnc.cn/Article/details/gtdrntqzht.html

Go:   strconv.Itoa(42)
来源：http://dali.nanxuanxn.top/Article/details/gtswtckqwu.html

Ruby: 42.to_s
来源：http://dali.andypj.xyz/Article/details/gtbsmftzwv.html

C#:   42.ToString()
来源：http://dali.aibaodan.cn/Article/details/gttcbwnwgv.html

[A08] 取整与四舍五入
来源：http://dali.yongpay.top/Article/details/gttcccmhvd.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.chenjidiqi.icu/Article/details/gtwbprvdxt.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zycfv.cn/Article/details/gtwsvxchhz.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.hywenlv.cn/Article/details/gtfibwuxdb.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.cqqwz.cn/Article/details/gtopvymjhg.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.bjfxy.top/Article/details/gtrqwcayoq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.hysaishi.cn/Article/details/gtdgohopxs.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.hnxiangtu.top/Article/details/gtluwzlzox.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.aizwys.cn/Article/details/gtbyjogbng.html

[A09] 绝对值与最大最小值
来源：http://dali.sxryk.cn/Article/details/gtqpaxdekt.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gtbtkdygyt.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtcucshycg.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtvtactfcw.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtjbdbkevl.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gtzigidefa.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.guowangkeji.top/Article/details/gtbcdpzgyd.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.meibo888.top/Article/details/gtueoxissi.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.hnqzz.top/Article/details/gtccqqnhib.html

[A10] 生成随机数
来源：http://dali.hywenlv.cn/Article/details/gtlwouorqp.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zycfv.cn/Article/details/gtpfiwchfe.html

PHP:  random_int(1, 100);
来源：http://dali.shanyushiyangtech.top/Article/details/gthvytlfnn.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jinqigufen.top/Article/details/gtnpvpzvkr.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yj202588.top/Article/details/gtcycjozof.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yongpay.top/Article/details/gtlrkbnkoz.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmuzrhyhm.html

Ruby: rand(1..100)
来源：http://dali.zhengqikj.top/Article/details/gtchekmvoy.html

C#:   new Random().Next(1, 101)
来源：http://dali.yvedp.cn/Article/details/gtrccmcput.html

[A11] 条件表达式（三元）
来源：http://dali.guowangkeji.top/Article/details/gttmhmbejb.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.hnxiangtu.top/Article/details/gtlmweyqbj.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.sweek.top/Article/details/gtulpbjnrp.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.shzxlz.cn/Article/details/gthuvkzjcb.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.chenlongwang.top/Article/details/gttqtopoxw.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.cheryme.top/Article/details/gtqvvgvvni.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.shzxlz.cn/Article/details/gtmgzfnixn.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.sysykeji.top/Article/details/gtthahbwte.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhulrbgk.html

[A12] 字符串插值 / 格式化
来源：http://dali.zdqjudy.top/Article/details/gtgxgivvtv.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.hongshengwenyu.top/Article/details/gtviblkkpd.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gtsklzjuji.html

JS:   `Hello, ${name}!`
来源：http://dali.smart0.xyz/Article/details/gtzuvplwly.html

TS:   `Hello, ${name}!`
来源：http://dali.hnqzz.top/Article/details/gtnrjkbhdo.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.shangyingyoupin.top/Article/details/gtdnghoxjn.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.tianlin.xyz/Article/details/gtvvttfrpw.html

Ruby: "Hello, #{name}!"
来源：http://dali.aibaodan.cn/Article/details/gtnnblkhrk.html

C#:   $"Hello, {name}!"
来源：http://dali.shangyingyoupin.top/Article/details/gtfnkdvopj.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yuanzhike.top/Article/details/gtyzrpfqdz.html

Py:   "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftnfkruh.html

PHP:  "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gtrkeomyvj.html

JS:   "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gtfzhkwsyt.html

TS:   "第一行\n第二行"
来源：http://dali.ivvv.top/Article/details/gtpykmnnte.html

Java: "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gtjxymeyia.html

Go:   "第一行\n第二行"
来源：http://dali.zhiwuduotai.top/Article/details/gtmsypdptl.html

Ruby: "第一行\n第二行"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpayavmst.html

C#:   "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gtpvdagaxe.html

[A14] 注释写法
来源：http://dali.shanyushiyangtech.top/Article/details/gtmirpnmfz.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.shanyushiyangtech.top/Article/details/gtggpskngr.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.nanxuanxn.top/Article/details/gtjbrzvfff.html

JS:   // 单行；/* 多行 */
来源：http://dali.yongpay.top/Article/details/gtiuushdpm.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gtjlsgntgp.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jinqigfzy.top/Article/details/gtlmdburhg.html

Go:   // 单行；/* 多行 */
来源：http://dali.xylfe.cn/Article/details/gtlqviafrb.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.iojbl.cn/Article/details/gtkhrfypmd.html

C#:   // 单行；/* 多行 */
来源：http://dali.hnqzz.top/Article/details/gtzwmhfdka.html

[A15] 空值判断与默认值
来源：http://dali.wangdashe.top/Article/details/gtmyiihqob.html

Py:   value = data or "默认值"
来源：http://dali.gotoacloud.top/Article/details/gthcchydoe.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.pengpengdd.cyou/Article/details/gtvgzapubm.html

JS:   const value = data ?? "默认值";
来源：http://dali.redwolf501.top/Article/details/gtwxanqlmm.html

TS:   const value = data ?? "默认值";
来源：http://dali.ivvv.top/Article/details/gtbshxzkku.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zycfv.cn/Article/details/gtlpkrbeic.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jinqigfzy.top/Article/details/gtintqwvmd.html

Ruby: value = data || "默认值"
来源：http://dali.pengpengdd.cyou/Article/details/gtbnbvdjpl.html

C#:   var value = data ?? "默认值";
来源：http://dali.gogol.net.cn/Article/details/gtpahjrhgc.html

[A16] 真假值判断规则
来源：http://dali.nanxuanxn.top/Article/details/gthzojbjgh.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.haohaochexian.top/Article/details/gtmykrgxth.html


<!-- 参考信息 -->