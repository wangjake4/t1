代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.xinyue.icu/Article/details/gtmwzcpuyx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.quarkkingdee.top/Article/details/gtuyldpcpw.html

[U92] JS：深拷贝
来源：http://dali.cashguo.top/Article/details/gtjnogcian.html

structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gtdkakxkhm.html

[U93] JS：模板字符串
来源：http://dali.0kj1m.cn/Article/details/gtcgsjqtre.html

`共 ${n} 条`
来源：http://dali.xuanzx.com/Article/details/gtmidqzegg.html

[U94] JS：箭头函数
来源：http://dali.yvedp.cn/Article/details/gtgvmgyqyn.html

const double = x => x * 2;
来源：http://dali.vqdsnc.cn/Article/details/gtuxtjkxjb.html

[U95] JS：Promise 包装
来源：http://dali.bjfxy.top/Article/details/gtlwlypyji.html

new Promise((resolve, reject) => {})
来源：http://dali.zhixingplan.top/Article/details/gtucfqsplh.html

[U96] JS：async/await 与异常
来源：http://dali.zhengqikj.top/Article/details/gtwkncoljh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gtxxakmcke.html

[U97] JS：并发请求
来源：http://dali.yangfankeji.com/Article/details/gtxshmcpml.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtfdygyggo.html

[U98] JS：fetch 带 JSON
来源：http://dali.quarkkingdee.top/Article/details/gtznnsagmo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.c1oappe.top/Article/details/gtabkyfqoo.html

[U99] JS：事件监听
来源：http://dali.9152youxi.cn/Article/details/gtzhvbwnur.html

el.addEventListener("click", e => {})
来源：http://dali.jiagoushi.top/Article/details/gtexkvisdf.html

[U100] JS：DOM 查询
来源：http://dali.yvedp.cn/Article/details/gtyagsbafr.html

document.querySelector(".item")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtksgjkhjx.html

[U101] JS：classList 操作
来源：http://dali.yonumen.top/Article/details/gtmslzqhzy.html

el.classList.toggle("active")
来源：http://dali.havefunace.top/Article/details/gtwpklsuzs.html

[U102] JS：本地存储
来源：http://dali.shangyingyoupin.top/Article/details/gtxdwdfrrh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hnxiangtu.top/Article/details/gtfgcnwoxt.html

[U103] JS：定时器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiywqinhv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.0kj1m.cn/Article/details/gtrebkqmhr.html

[U104] JS：防抖
来源：http://dali.sufxvd.cn/Article/details/gtujeijddt.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtbddlgfpg.html

[U105] JS：节流
来源：http://dali.ehwqpu.com/Article/details/gteehfoyth.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.daxiang520.top/Article/details/gtqsbyuhye.html

[U106] JS：日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gtmtxsqvwn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinqigufen.top/Article/details/gtsnwnpfbz.html

[U107] JS：数字千分位
来源：http://dali.jqgfzy.top/Article/details/gtsqixyvtu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcvgsxeh.html

[U108] JS：随机整数
来源：http://dali.fengsongda.top/Article/details/gtfeumceyo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.redwolf501.top/Article/details/gtcmihwvrr.html

[U109] JS：数组分组
来源：http://dali.nwbrower.top/Article/details/gtrjjdtguz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zdqjudy.top/Article/details/gtmokdivkd.html

[U110] JS：数组分块
来源：http://dali.kuanghao11.cn/Article/details/gtocshqrbj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinqigufen.top/Article/details/gtwnygdkuq.html

[U111] JS：对象转 Map
来源：http://dali.yvedp.cn/Article/details/gtpceabmom.html

new Map(Object.entries(obj))
来源：http://dali.gaohongyu789.top/Article/details/gtkedrddpi.html

[U112] JS：字符串补位
来源：http://dali.cdnleiting.top/Article/details/gtfpfchzvg.html

"7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gtawhjmrnh.html

[U113] JS：正则替换全部
来源：http://dali.ydzc1.top/Article/details/gtlfxumpoh.html

s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gthvqbngzp.html

[U114] JS：JSON 深比较
来源：http://dali.tanke756.top/Article/details/gtxjgsvjfv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxfjrtvl.html

[U115] JS：生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gtfihfnunt.html

crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gtzzhffpir.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.chenlongwang.top/Article/details/gtgwzlzyfn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.aibaodan.cn/Article/details/gtuuexqbrh.html

[U117] JS：单元测试
来源：http://dali.hywenlv.cn/Article/details/gtndxbzofk.html

npm i -D vitest;  npx vitest
来源：http://dali.shuidangran.top/Article/details/gtqxiykdrj.html

[U118] JS：开发服务器
来源：http://dali.jqgufenzy.top/Article/details/gtyeitqmqx.html

npm i -D vite;  npx vite
来源：http://dali.svipenyu.cn/Article/details/gtjuskcwfn.html

[U119] JS：生产构建
来源：http://dali.sysykeji.top/Article/details/gtaeotflor.html

npx vite build
来源：http://dali.tanke756.top/Article/details/gtrdvppvov.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cheryme.top/Article/details/gtprhpowfn.html

import.meta.env.VITE_API_URL
来源：http://dali.tianlin.xyz/Article/details/gtdouyneba.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtisahtzet.html

统计汇总
来源：http://dali.cqqwz.cn/Article/details/gtjczetymr.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtddawpcut.html

按语言统计（条）：
来源：http://dali.iojbl.cn/Article/details/gtwzzrsmce.html

Python ......... 252
来源：http://dali.pengpengdd.cyou/Article/details/gtpaaurevf.html

PHP ............ 252
来源：http://dali.gogol.net.cn/Article/details/gtwbndnyrg.html

JavaScript ..... 252
来源：http://dali.yuanzhike.top/Article/details/gtefhmjvsu.html

TypeScript ..... 212
来源：http://dali.cqqwz.cn/Article/details/gtrkklsprq.html

Java ........... 212
来源：http://dali.daria6918.cn/Article/details/gtfofvzeoi.html

Go ............. 212
来源：http://dali.feifeiyinyue.top/Article/details/gtyoypzuxh.html

Ruby ........... 212
来源：http://dali.zhixingplan.top/Article/details/gtttzzhodm.html

C# ............. 212
来源：http://dali.yvedp.cn/Article/details/gtntjeskro.html

C .............. 30
来源：http://dali.quarkkingdee.top/Article/details/gtoweutsyg.html

C++ ............ 30
来源：http://dali.yangfankeji.com/Article/details/gtxurclezq.html

SQL ............ 90
来源：http://dali.nanxinkj.top/Article/details/gtppuhcnhz.html

Bash ........... 80
来源：http://dali.pycfn.com/Article/details/gtrvjchimj.html

Kotlin ......... 15
来源：http://dali.xuetiantiany.cn/Article/details/gtkiavhniq.html

Swift .......... 15
来源：http://dali.feifeiyinyue.top/Article/details/gtatyqoavz.html

Lua ............ 10
来源：http://dali.havefunace.top/Article/details/gtslyetsbw.html

Perl ........... 10
来源：http://dali.hywenlv.cn/Article/details/gtbaqphnxe.html

Scala .......... 10
来源：http://dali.tianlin.xyz/Article/details/gtrvuskrqx.html

------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gtqhnjkeve.html

合计 ........... 2106 条
来源：http://dali.jinghuilouyu.cn/Article/details/gtonpwxefg.html

按章节统计：
来源：http://dali.dianchejie.cn/Article/details/gtfjbtwbft.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jlsjyb.cn/Article/details/gtftlazhwh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yangfankeji.com/Article/details/gtpvezrlwi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hnqzz.top/Article/details/gtgswpbjvp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gotoacloud.top/Article/details/gtnznvwanh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hongshengwenyu.top/Article/details/gtmokxgicn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.dashuyun.cn/Article/details/gtitffycfn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.feifeiyinyue.top/Article/details/gtsmnfbydz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.daxiang520.top/Article/details/gtbvaopvgl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gtjyrkfatf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.guowangkeji.top/Article/details/gtgubbnqft.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gtkxsmemcw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gtbkrpthdh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gtoangzpjd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.fengsongda.top/Article/details/gtxthttaqn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ydzc1.top/Article/details/gtaxkagdvk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gtqjmzdexg.html

Q SQL 专题                              90
来源：http://dali.snrcjt.cn/Article/details/gtncmucyuw.html

R Bash 专题                             80
来源：http://dali.shanyushiyangtech.top/Article/details/gtbeofqqju.html

S C / C++ 专题                          60
来源：http://dali.yanxiufei.cn/Article/details/gtbxtcndow.html

T 其他语言补充                          60
来源：http://dali.dianchejie.cn/Article/details/gtnyhvgsea.html

U 高频实用片段                         120
来源：http://dali.tanke756.top/Article/details/gtvtwzgyvy.html

------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gtkogwbcnz.html

合计                                  2106 条
来源：http://dali.yvedp.cn/Article/details/gtqfzkyzlg.html

--------------------------------------------------------------------------------
来源：http://dali.ydzc1.top/Article/details/gtgvxoabhs.html

使用提醒
来源：http://dali.sufxvd.cn/Article/details/gthpvwyuyo.html

--------------------------------------------------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gtitzhivmb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.meibo888.top/Article/details/gtnzpfwcug.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.aizwys.cn/Article/details/gtrokldkow.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.daxiang520.top/Article/details/gtagiiiwgl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cucudq.cn/Article/details/gtiozevuaq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cheryme.top/Article/details/gtkecowzgc.html

—— 文件结束 ——
来源：http://dali.fengsongda.top/Article/details/gtodhfffzd.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtcslafofd.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hnxiangtu.top/Article/details/gtyoxvcjoc.html

Common Programming Examples Cheat Book
来源：http://dali.zhongyouzk.top/Article/details/gtgoojsucs.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gttlenrfzg.html

【收录内容】
来源：http://dali.feifeiyinyue.top/Article/details/gtxniwqdwy.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jyoumei.cn/Article/details/gtdjtckocj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhongyouzk.top/Article/details/gtfxzlhbzf.html

SQL · Bash · C · C++
来源：http://dali.hywenlv.cn/Article/details/gtscndglbe.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.tanke756.top/Article/details/gtpvwcwjcx.html

【使用说明】
来源：http://dali.ehwqpu.com/Article/details/gtvicrczbv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yonumen.top/Article/details/gtdgffygwf.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xinyue.icu/Article/details/gtqltgikqk.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ivvv.top/Article/details/gtigtfopob.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhoulong.xyz/Article/details/gtyrucdsrg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zycfv.cn/Article/details/gtzzffoxzf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xylfe.cn/Article/details/gtgwjyzdkn.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.wangshuangyany.cn/Article/details/gtmkseexnn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.aizwys.cn/Article/details/gtcdjphhhv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hammf.cn/Article/details/gtbrqbfukd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jianghu66.top/Article/details/gtyatucdod.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.0kj1m.cn/Article/details/gtlgmnehdp.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cdnleiting.top/Article/details/gtskujljuq.html

【文件统计】
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzuvcoct.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ybcxt.top/Article/details/gtnjqrtobm.html

--------------------------------------------------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gttllgqdvn.html

目  录
来源：http://dali.guowangkeji.top/Article/details/gtpotvirhs.html

--------------------------------------------------------------------------------
来源：http://dali.316326.xyz/Article/details/gtwjxbwuzs.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yueranfly.top/Article/details/gtpjjquvdr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jianghu66.top/Article/details/gtesoxoahh.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.sysykeji.top/Article/details/gtvjaylpmo.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.vqdsnc.cn/Article/details/gtoxyhqpch.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.cqqwz.cn/Article/details/gtuhpdbkud.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yuxming.cn/Article/details/gttccnmuni.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xinyue.icu/Article/details/gtmcohgpve.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ydzc1.top/Article/details/gtfmddwsyp.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmzvegfj.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.gaohongyu789.top/Article/details/gteycjcsee.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gtgfwfqttc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yangfankeji.com/Article/details/gtgqvtxbmh.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gtxytbwdxd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jqgufenzy.top/Article/details/gtluybfkoy.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.nwbrower.top/Article/details/gttwgileiq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gtzxgektjb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.mhx1999.top/Article/details/gtyqpzcfcq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.havefunace.top/Article/details/gtdinnmngm.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhaqywpi.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jyoumei.cn/Article/details/gtnhxxeiln.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigufen.top/Article/details/gtiowzfago.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtfeliigam.html

A. 基础语法与类型
来源：http://dali.shuidangran.top/Article/details/gtdlpmesxq.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtdfemslye.html

[A01] Hello World
来源：http://dali.gotoacloud.top/Article/details/gtdxcekaco.html

Py:   print("Hello, World!")
来源：http://dali.shangyingyoupin.top/Article/details/gtakguuodw.html

PHP:  echo "Hello, World!";
来源：http://dali.zhengqikj.top/Article/details/gtdhdexxev.html

JS:   console.log("Hello, World!");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtulshiyft.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.tian-w.cn/Article/details/gtweiztfqm.html

Java: System.out.println("Hello, World!");
来源：http://dali.xuanzx.com/Article/details/gtvhlioqfq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.smart0.xyz/Article/details/gtspqkltcs.html

Ruby: puts "Hello, World!"
来源：http://dali.sweek.top/Article/details/gtsdtorizd.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.feifeiyinyue.top/Article/details/gtgdajrioj.html

[A02] 变量声明与赋值
来源：http://dali.zhiwuduotai.top/Article/details/gthzrxtrmg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.gaohongyu789.top/Article/details/gtmjzbdvvu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.andypj.xyz/Article/details/gtciayrqdv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhengqikj.top/Article/details/gtdvwkbmlq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gotoacloud.top/Article/details/gthjrndwrb.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yongpay.top/Article/details/gtvxmvcbsz.html

Go:   name := "Alex"; age := 20
来源：http://dali.jinghuilouyu.cn/Article/details/gttoruvlrt.html

Ruby: name = "Alex"; age = 20
来源：http://dali.sufxvd.cn/Article/details/gteepsyqhx.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yj20258.top/Article/details/gthwkpnndg.html

[A03] 常量定义
来源：http://dali.9152youxi.cn/Article/details/gtyeqagvsc.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.havefunace.top/Article/details/gtskzfvezw.html

PHP:  const PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtcuxyyftr.html

JS:   const PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gtlfryxcnm.html

TS:   const PI: number = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtkdlnripj.html

Java: static final double PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtozqrfefp.html

Go:   const PI = 3.14159
来源：http://dali.hammf.cn/Article/details/gtmkavhxzo.html

Ruby: PI = 3.14159
来源：http://dali.fzhhl.top/Article/details/gtayhtzsqb.html

C#:   const double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gthmtlnyas.html

[A04] 判断变量类型
来源：http://dali.jyoumei.cn/Article/details/gtuwigkbei.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhengqikj.top/Article/details/gtdpibynat.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gotoacloud.top/Article/details/gtpffrhvhe.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.mhx1999.top/Article/details/gtjbyncotj.html

TS:   typeof x; x instanceof Date
来源：http://dali.mhx1999.top/Article/details/gtuuouvugn.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.aizwys.cn/Article/details/gttkkfhrcs.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.gzhubu.top/Article/details/gtqchgpgwc.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.haohaochexian.top/Article/details/gtcqoegxyq.html

C#:   x.GetType().Name; x is int
来源：http://dali.jlsjyb.cn/Article/details/gtygferibf.html

[A05] 整数除法与取模
来源：http://dali.chenzaomai.com/Article/details/gtzvpajssu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlhlmman.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gtztziczrc.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xziqi.cn/Article/details/gtafurpyrs.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gtgxwbrfpk.html

Java: 7 / 2; 7 % 2
来源：http://dali.nanxuanxn.top/Article/details/gtmpagocmp.html

Go:   7 / 2; 7 % 2
来源：http://dali.tian-w.cn/Article/details/gtlfelskyi.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gtohnypour.html

C#:   7 / 2; 7 % 2
来源：http://dali.nanxuanxn.top/Article/details/gtzduihthe.html

[A06] 字符串转数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuwarvqxf.html

Py:   int("42"); float("3.14")
来源：http://dali.nanxuanxn.top/Article/details/gtttxsblqv.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hysaishi.cn/Article/details/gtojsdxmym.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yj202588.top/Article/details/gtarkpgzor.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jinqigufen.top/Article/details/gtwmisuvmf.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yonumen.top/Article/details/gtdmitbxhn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yj20258888.top/Article/details/gtphidgeaf.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.gotoacloud.top/Article/details/gtyfrgqukk.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.cashguo.top/Article/details/gtmezijyzh.html

[A07] 数字转字符串
来源：http://dali.ybcxt.top/Article/details/gtvmxtfuci.html

Py:   str(42)
来源：http://dali.shuidangran.top/Article/details/gttnkerqww.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhixingplan.top/Article/details/gtbjmrjicy.html

JS:   String(42); (42).toString()
来源：http://dali.yongpay.top/Article/details/gtmovlbgzb.html

TS:   String(42)
来源：http://dali.jqgfzy.top/Article/details/gtsfzotilg.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zycfv.cn/Article/details/gteycmlhvp.html

Go:   strconv.Itoa(42)
来源：http://dali.svipenyu.cn/Article/details/gthhxphlya.html

Ruby: 42.to_s
来源：http://dali.jyoumei.cn/Article/details/gtmecyzfyw.html

C#:   42.ToString()
来源：http://dali.ybcxt.top/Article/details/gtwvekbhlp.html

[A08] 取整与四舍五入
来源：http://dali.zdqjudy.top/Article/details/gtpiseioxs.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.guannengcc.top/Article/details/gtxgtxzfyx.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zycfv.cn/Article/details/gtuizydtuv.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.fengsongda.top/Article/details/gteqckiwlm.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.dianchejie.cn/Article/details/gtarnjcuff.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.shangyingyoupin.top/Article/details/gtpvebhrxp.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jqgufenzy.top/Article/details/gtingpywbl.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozfpaacq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jiagoushi.top/Article/details/gtzqqerofl.html

[A09] 绝对值与最大最小值
来源：http://dali.sufxvd.cn/Article/details/gtuxphmaio.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsgojbtv.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gtimjjcvgg.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yuxming.cn/Article/details/gtsuuhyiie.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtcztbusrg.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.aizwys.cn/Article/details/gtedgkbfkb.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.chenlongwang.top/Article/details/gtxkwhzzvs.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.tanke756.top/Article/details/gtxxtlstut.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.ivvv.top/Article/details/gtodkqkamq.html

[A10] 生成随机数
来源：http://dali.aibaodan.cn/Article/details/gtvmkhdvfj.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jyoumei.cn/Article/details/gtlvsqvrfy.html

PHP:  random_int(1, 100);
来源：http://dali.fzhhl.top/Article/details/gtlvvssxos.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shzxlz.cn/Article/details/gtkxrpcblo.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.vqdsnc.cn/Article/details/gtinjhlbry.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yj20258.top/Article/details/gttstutbsv.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlmczyrb.html

Ruby: rand(1..100)
来源：http://dali.jqgufenzy.top/Article/details/gtreqyinnz.html

C#:   new Random().Next(1, 101)
来源：http://dali.hysaishi.cn/Article/details/gtammbjwfc.html

[A11] 条件表达式（三元）
来源：http://dali.tianlin.xyz/Article/details/gttcudloam.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.316326.xyz/Article/details/gtmeozlizd.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hammf.cn/Article/details/gtmomuieqo.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhixingplan.top/Article/details/gtkxfadwvu.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yanxiufei.cn/Article/details/gtgdufxixy.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.c1oappe.top/Article/details/gtomguvvxi.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.cucudq.cn/Article/details/gtcljxtqip.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.hnxiangtu.top/Article/details/gthtyscrkf.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.kuanghao11.cn/Article/details/gtsnepaikl.html

[A12] 字符串插值 / 格式化
来源：http://dali.zycfv.cn/Article/details/gticpdkryg.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yueranfly.top/Article/details/gtpkpwgtfc.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yonumen.top/Article/details/gtjjbruitv.html

JS:   `Hello, ${name}!`
来源：http://dali.guannengcc.top/Article/details/gtklaofmle.html

TS:   `Hello, ${name}!`
来源：http://dali.cheryme.top/Article/details/gtpzakaeob.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.daxiang520.top/Article/details/gthnaojggo.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jinqigfzy.top/Article/details/gtkuaygfts.html

Ruby: "Hello, #{name}!"
来源：http://dali.yanxiufei.cn/Article/details/gttugyjjbp.html

C#:   $"Hello, {name}!"
来源：http://dali.gaohongyu789.top/Article/details/gtvfcawzra.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.chenjidiqi.icu/Article/details/gtbdaiavpu.html

Py:   "第一行\n第二行"
来源：http://dali.ybcxt.top/Article/details/gtpiuoytkh.html

PHP:  "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gtwygieooj.html

JS:   "第一行\n第二行"
来源：http://dali.hysaishi.cn/Article/details/gttlcpxxjt.html

TS:   "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gtfuybwqjh.html

Java: "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gtrnahvemc.html

Go:   "第一行\n第二行"
来源：http://dali.jinqigufen.top/Article/details/gtpgcinkyj.html

Ruby: "第一行\n第二行"
来源：http://dali.yvedp.cn/Article/details/gtexdabsot.html

C#:   "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gtjuzezlfk.html

[A14] 注释写法
来源：http://dali.jinqigfzy.top/Article/details/gtrvblwfhm.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.svipenyu.cn/Article/details/gtgkqybenr.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.mhx1999.top/Article/details/gtfdozimut.html

JS:   // 单行；/* 多行 */
来源：http://dali.sweek.top/Article/details/gtgfwzfmcl.html

TS:   // 单行；/* 多行 */
来源：http://dali.xziqi.cn/Article/details/gtzqrqrcuv.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hfpthk.cn/Article/details/gtmbcidhvx.html

Go:   // 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gtlhpbtfeo.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yj20258888.top/Article/details/gtqwiqtwnq.html

C#:   // 单行；/* 多行 */
来源：http://dali.shangyingyoupin.top/Article/details/gtacprkxht.html

[A15] 空值判断与默认值
来源：http://dali.redwolf501.top/Article/details/gtsatjnjoq.html

Py:   value = data or "默认值"
来源：http://dali.kuanghao11.cn/Article/details/gtsepodtaa.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.wangshuangyany.cn/Article/details/gtcjabxyah.html

JS:   const value = data ?? "默认值";
来源：http://dali.kuanghao11.cn/Article/details/gtvuvamsig.html

TS:   const value = data ?? "默认值";
来源：http://dali.tian-w.cn/Article/details/gtifrthwbt.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yanxiufei.cn/Article/details/gtxbyyglmr.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.tian-w.cn/Article/details/gtcilpgaxo.html


<!-- 参考信息 -->