代发 wailian999

[U93] JS：模板字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2pfkvdyru.html

`共 ${n} 条`
来源：http://dali.xuanzx.com/Article/details/gt2gskpkazu.html

[U94] JS：箭头函数
来源：http://dali.quarkkingdee.top/Article/details/gt2ycdmeran.html

const double = x => x * 2;
来源：http://dali.feifeiyinyue.top/Article/details/gt2itnqhjtw.html

[U95] JS：Promise 包装
来源：http://dali.jinghuilouyu.cn/Article/details/gt2amaybeps.html

new Promise((resolve, reject) => {})
来源：http://dali.gotoacloud.top/Article/details/gt2xvfnnkbu.html

[U96] JS：async/await 与异常
来源：http://dali.jiagoushi.top/Article/details/gt2rddruetw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gt2eugbydhp.html

[U97] JS：并发请求
来源：http://dali.iojbl.cn/Article/details/gt2btsirnil.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gt2orafmapo.html

[U98] JS：fetch 带 JSON
来源：http://dali.iojbl.cn/Article/details/gt2wkfrptaq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.pycfn.com/Article/details/gt2fjtxmtpe.html

[U99] JS：事件监听
来源：http://dali.sysykeji.top/Article/details/gt2dmgnaztp.html

el.addEventListener("click", e => {})
来源：http://dali.gotoacloud.top/Article/details/gt2wcwmljxv.html

[U100] JS：DOM 查询
来源：http://dali.dashuyun.cn/Article/details/gt2txodtxhd.html

document.querySelector(".item")
来源：http://dali.cdnleiting.top/Article/details/gt2ejasidbk.html

[U101] JS：classList 操作
来源：http://dali.c1oappe.top/Article/details/gt2xzeppjpn.html

el.classList.toggle("active")
来源：http://dali.vqdsnc.cn/Article/details/gt2omfefgwc.html

[U102] JS：本地存储
来源：http://dali.yj20258888.top/Article/details/gt2hytbaocs.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xylfe.cn/Article/details/gt2casblmmr.html

[U103] JS：定时器
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yatpvofy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jyoumei.cn/Article/details/gt2cmmlkxjv.html

[U104] JS：防抖
来源：http://dali.cdnleiting.top/Article/details/gt2noqmtsgk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gt2kyyovnqe.html

[U105] JS：节流
来源：http://dali.cashguo.top/Article/details/gt2xttroqgb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.guannengcc.top/Article/details/gt2wiwkhksj.html

[U106] JS：日期格式化
来源：http://dali.yueranfly.top/Article/details/gt2fehidybf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xylfe.cn/Article/details/gt2vjtheizl.html

[U107] JS：数字千分位
来源：http://dali.xinyue.icu/Article/details/gt2piabvxom.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yueranfly.top/Article/details/gt2olwlwole.html

[U108] JS：随机整数
来源：http://dali.xziqi.cn/Article/details/gt2oicbdlni.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.316326.xyz/Article/details/gt2vsjwhgtf.html

[U109] JS：数组分组
来源：http://dali.gotoacloud.top/Article/details/gt2ycdrccqu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.chenzaomai.com/Article/details/gt2bfgglbhg.html

[U110] JS：数组分块
来源：http://dali.aibaodan.cn/Article/details/gt2epnbitou.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.vqdsnc.cn/Article/details/gt2vvdmgcso.html

[U111] JS：对象转 Map
来源：http://dali.shanyushiyangtech.top/Article/details/gt2seeaphxz.html

new Map(Object.entries(obj))
来源：http://dali.andypj.xyz/Article/details/gt2ynycicgs.html

[U112] JS：字符串补位
来源：http://dali.daria6918.cn/Article/details/gt2iwmcfsmw.html

"7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kttkdjfy.html

[U113] JS：正则替换全部
来源：http://dali.meibo888.top/Article/details/gt2uytzwnmm.html

s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2regbvrju.html

[U114] JS：JSON 深比较
来源：http://dali.bjfxy.top/Article/details/gt2kcubzpcx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daria6918.cn/Article/details/gt2wefnadut.html

[U115] JS：生成 UUID
来源：http://dali.hywenlv.cn/Article/details/gt2yousxlnq.html

crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gt2bqjrhwao.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xinyue.icu/Article/details/gt2oqezshjs.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhixingplan.top/Article/details/gt2pvglgwkv.html

[U117] JS：单元测试
来源：http://dali.316326.xyz/Article/details/gt2zxbvkorb.html

npm i -D vitest;  npx vitest
来源：http://dali.andypj.xyz/Article/details/gt2vypiwnnf.html

[U118] JS：开发服务器
来源：http://dali.yuxming.cn/Article/details/gt2xexivydj.html

npm i -D vite;  npx vite
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oycctrla.html

[U119] JS：生产构建
来源：http://dali.cqqwz.cn/Article/details/gt2hvjmgjwv.html

npx vite build
来源：http://dali.cdnleiting.top/Article/details/gt2xyhkugem.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xylfe.cn/Article/details/gt2yydojnhx.html

import.meta.env.VITE_API_URL
来源：http://dali.shuidangran.top/Article/details/gt2ftoktooy.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2orqacgwh.html

统计汇总
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ygyakmbz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ycdlvsak.html

按语言统计（条）：
来源：http://dali.hammf.cn/Article/details/gt2jcopliez.html

Python ......... 252
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ehgbqyhy.html

PHP ............ 252
来源：http://dali.c1oappe.top/Article/details/gt2jyytwbmd.html

JavaScript ..... 252
来源：http://dali.nanxuanxn.top/Article/details/gt2yskkppbe.html

TypeScript ..... 212
来源：http://dali.zhiwuduotai.top/Article/details/gt2yejfprqp.html

Java ........... 212
来源：http://dali.yj20258888.top/Article/details/gt2reohnxjb.html

Go ............. 212
来源：http://dali.sxryk.cn/Article/details/gt2ebhrbxky.html

Ruby ........... 212
来源：http://dali.daxiang520.top/Article/details/gt2bofhiekw.html

C# ............. 212
来源：http://dali.shangyingyoupin.top/Article/details/gt2xqqvybla.html

C .............. 30
来源：http://dali.fzhhl.top/Article/details/gt2fxpdhebl.html

C++ ............ 30
来源：http://dali.yanxiufei.cn/Article/details/gt2uphepayb.html

SQL ............ 90
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aoxozobs.html

Bash ........... 80
来源：http://dali.havefunace.top/Article/details/gt2twndfcfx.html

Kotlin ......... 15
来源：http://dali.ehwqpu.com/Article/details/gt2ymtaqfhr.html

Swift .......... 15
来源：http://dali.cqqwz.cn/Article/details/gt2rhzexjzn.html

Lua ............ 10
来源：http://dali.yuanzhike.top/Article/details/gt2klxsprze.html

Perl ........... 10
来源：http://dali.dashuyun.cn/Article/details/gt2wtbqrgej.html

Scala .......... 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hagrxkfv.html

------------------------------------
来源：http://dali.aizwys.cn/Article/details/gt2ayjowjxm.html

合计 ........... 2106 条
来源：http://dali.zycfv.cn/Article/details/gt2gytrlkfz.html

按章节统计：
来源：http://dali.wangshuangyany.cn/Article/details/gt2saeaimim.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xylfe.cn/Article/details/gt2ajhzpvzt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.bjfxy.top/Article/details/gt2srfiygsq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2flanxeil.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xziqi.cn/Article/details/gt2kquyxsyp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jyoumei.cn/Article/details/gt2cjrjvvcf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ehwqpu.com/Article/details/gt2fxxdengb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.chenlongwang.top/Article/details/gt2hqwcvnwh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jqgufenzy.top/Article/details/gt2tdldtxow.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gt2rsruqenh.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.birdmap.top/Article/details/gt2ajmrusym.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ewysjyer.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gt2qwbhebua.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gt2fbrlmtts.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj20258888.top/Article/details/gt2dowfofna.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.bjfxy.top/Article/details/gt2zqrlzmnw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gt2bpxbzhzp.html

Q SQL 专题                              90
来源：http://dali.yonumen.top/Article/details/gt2nyyzvkfp.html

R Bash 专题                             80
来源：http://dali.cqqwz.cn/Article/details/gt2ayeblnio.html

S C / C++ 专题                          60
来源：http://dali.zhiwuduotai.top/Article/details/gt2gvbpnqsv.html

T 其他语言补充                          60
来源：http://dali.yonumen.top/Article/details/gt2iyhpzwfd.html

U 高频实用片段                         120
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qzhlcbay.html

------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gt2gflpvcuw.html

合计                                  2106 条
来源：http://dali.snrcjt.cn/Article/details/gt2fxoejsno.html

--------------------------------------------------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gt2rzpqxtzd.html

使用提醒
来源：http://dali.zhoulong.xyz/Article/details/gt2fxzkfoun.html

--------------------------------------------------------------------------------
来源：http://dali.hnqzz.top/Article/details/gt2dnljuoeu.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.pycfn.com/Article/details/gt2svsgkkcb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.sweek.top/Article/details/gt2voqjtfuz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ppjwa.cn/Article/details/gt2cbgzfagr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xziqi.cn/Article/details/gt2tfcvkasu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.gogol.net.cn/Article/details/gt2msibuzwc.html

—— 文件结束 ——
来源：http://dali.snrcjt.cn/Article/details/gt2apjjntno.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2biqzxlck.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yj202588.top/Article/details/gt2wrzmyate.html

Common Programming Examples Cheat Book
来源：http://dali.yj202588.top/Article/details/gt2hqwxybgp.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2gbdzgobr.html

【收录内容】
来源：http://dali.xinyue.icu/Article/details/gt2aijqmvkq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ivvv.top/Article/details/gt2rsefenbh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.vqdsnc.cn/Article/details/gt2pipqbuht.html

SQL · Bash · C · C++
来源：http://dali.shanyushiyangtech.top/Article/details/gt2efcmqddb.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.kuanghao11.cn/Article/details/gt2hnxsskno.html

【使用说明】
来源：http://dali.yuxming.cn/Article/details/gt2xsuypwlv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yonumen.top/Article/details/gt2smmtdwcg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.vqdsnc.cn/Article/details/gt2hferpqhf.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.chenzaomai.com/Article/details/gt2wqmftbjo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shzxlz.cn/Article/details/gt2mmoocjqg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhongyouzk.top/Article/details/gt2oylqtqkc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yangfankeji.com/Article/details/gt2wkrevsms.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.kuanghao11.cn/Article/details/gt2wscuibmv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jqgufenzy.top/Article/details/gt2ebzdfbvw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.gzhubu.top/Article/details/gt2vaubqgrl.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hammf.cn/Article/details/gt2pnbdpumo.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.pycfn.com/Article/details/gt2hpuebkzw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yongpay.top/Article/details/gt2vikiuxgl.html

【文件统计】
来源：http://dali.birdmap.top/Article/details/gt2ejbjmkqo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejwygtul.html

--------------------------------------------------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gt2ksizncvn.html

目  录
来源：http://dali.shzxlz.cn/Article/details/gt2xtwicmee.html

--------------------------------------------------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gt2zdubecjp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.svipenyu.cn/Article/details/gt2tkooudda.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.9152youxi.cn/Article/details/gt2dfuzeruv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xitqdkqm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.cheryme.top/Article/details/gt2teheycba.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2icdohrpe.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.ydzc1.top/Article/details/gt2eupbixst.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2wmfqyrzx.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jianghu66.top/Article/details/gt2reyixgdk.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gt2iwmgtvts.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yj20258.top/Article/details/gt2kvoxzaer.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yangfankeji.com/Article/details/gt2aajzdxyo.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gt2otccusca.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gt2eivmqjob.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.9152youxi.cn/Article/details/gt2jxlfmlpw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.gogol.net.cn/Article/details/gt2yxwpoxku.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gt2qzqtlsby.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.sxryk.cn/Article/details/gt2jmsvvypg.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhixingplan.top/Article/details/gt2wouqzmel.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbyubeu.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sysykeji.top/Article/details/gt2jlmyekdc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.dianchejie.cn/Article/details/gt2ngrlejxy.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2pvxsermu.html

A. 基础语法与类型
来源：http://dali.sysykeji.top/Article/details/gt2dofczbiz.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2owoebjxu.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jekquyha.html

Py:   print("Hello, World!")
来源：http://dali.mhx1999.top/Article/details/gt2obfboujp.html

PHP:  echo "Hello, World!";
来源：http://dali.zhiwuduotai.top/Article/details/gt2whovlhky.html

JS:   console.log("Hello, World!");
来源：http://dali.hongshengwenyu.top/Article/details/gt2zninwjwu.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yongpay.top/Article/details/gt2krflpmgv.html

Java: System.out.println("Hello, World!");
来源：http://dali.ydzc1.top/Article/details/gt2sqxdaqxr.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.shuidangran.top/Article/details/gt2fhramkfi.html

Ruby: puts "Hello, World!"
来源：http://dali.birdmap.top/Article/details/gt2wfqpmdlz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhiwuduotai.top/Article/details/gt2hdnhvmkt.html

[A02] 变量声明与赋值
来源：http://dali.haohaochexian.top/Article/details/gt2mchsxxhg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.chenlongwang.top/Article/details/gt2phahdfle.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hammf.cn/Article/details/gt2tighsgot.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.sufxvd.cn/Article/details/gt2ocuuzzsz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cqqwz.cn/Article/details/gt2ybfbjdjw.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hammf.cn/Article/details/gt2yyzmyvtk.html

Go:   name := "Alex"; age := 20
来源：http://dali.yj20258888.top/Article/details/gt2tiklbhaj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.cheryme.top/Article/details/gt2mzyrdxbw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.tian-w.cn/Article/details/gt2udhgtzbu.html

[A03] 常量定义
来源：http://dali.sufxvd.cn/Article/details/gt2rkhmofxs.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhoulong.xyz/Article/details/gt2qohqqmtq.html

PHP:  const PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gt2kmftogrg.html

JS:   const PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gt2ibnedpiw.html

TS:   const PI: number = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gt2odajjvdl.html

Java: static final double PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gt2ekwrpgcz.html

Go:   const PI = 3.14159
来源：http://dali.chenzaomai.com/Article/details/gt2uerfvysa.html

Ruby: PI = 3.14159
来源：http://dali.zhixingplan.top/Article/details/gt2pbjxqztb.html

C#:   const double PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gt2suzqnkwl.html

[A04] 判断变量类型
来源：http://dali.fengsongda.top/Article/details/gt2rxdhdffj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.guowangkeji.top/Article/details/gt2ymbrzgla.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yueranfly.top/Article/details/gt2rroliugl.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jlsjyb.cn/Article/details/gt2kjerseuz.html

TS:   typeof x; x instanceof Date
来源：http://dali.nwbrower.top/Article/details/gt2qtrjvaxe.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hysaishi.cn/Article/details/gt2gluyimse.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.ybcxt.top/Article/details/gt2whrcgkhi.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ydzc1.top/Article/details/gt2bbmzubkj.html

C#:   x.GetType().Name; x is int
来源：http://dali.xylfe.cn/Article/details/gt2lodgilcg.html

[A05] 整数除法与取模
来源：http://dali.chenzaomai.com/Article/details/gt2rwtgtygb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yuanzhike.top/Article/details/gt2savkhwjh.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jianghu66.top/Article/details/gt2yhigvpet.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cheryme.top/Article/details/gt2qoxwdipb.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zhlxwydw.html

Java: 7 / 2; 7 % 2
来源：http://dali.daxiang520.top/Article/details/gt2estsxjcm.html

Go:   7 / 2; 7 % 2
来源：http://dali.hammf.cn/Article/details/gt2snzkcltz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.shuidangran.top/Article/details/gt2ipuxsebh.html

C#:   7 / 2; 7 % 2
来源：http://dali.sxryk.cn/Article/details/gt2tdoxwfbv.html

[A06] 字符串转数字
来源：http://dali.nanxuanxn.top/Article/details/gt2pgwrmvxu.html

Py:   int("42"); float("3.14")
来源：http://dali.gzhubu.top/Article/details/gt2xagabqho.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.wangshuangyany.cn/Article/details/gt2wdsgisak.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.nanxinkj.top/Article/details/gt2lcqlavxo.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.sysykeji.top/Article/details/gt2kgskrdch.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2shvaiest.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shzxlz.cn/Article/details/gt2mgudsdcr.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.smart0.xyz/Article/details/gt2ydlqohcf.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wihszqdf.html

[A07] 数字转字符串
来源：http://dali.daxiang520.top/Article/details/gt2mvwhmbif.html

Py:   str(42)
来源：http://dali.hfpthk.cn/Article/details/gt2gqxzatfk.html

PHP:  (string) 42; strval(42)
来源：http://dali.guannengcc.top/Article/details/gt2ppfeziiu.html

JS:   String(42); (42).toString()
来源：http://dali.iojbl.cn/Article/details/gt2qsbmypmz.html

TS:   String(42)
来源：http://dali.jinqigfzy.top/Article/details/gt2tppibvha.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbkhzltk.html

Go:   strconv.Itoa(42)
来源：http://dali.kuanghao11.cn/Article/details/gt2frkooxlz.html

Ruby: 42.to_s
来源：http://dali.xylfe.cn/Article/details/gt2gfytnvbh.html

C#:   42.ToString()
来源：http://dali.smart0.xyz/Article/details/gt2mzuahmfw.html

[A08] 取整与四舍五入
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jtqmiljv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kbnoaozr.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.guowangkeji.top/Article/details/gt2rurzmnwl.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.nanxuanxn.top/Article/details/gt2rzuvpnco.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.xylfe.cn/Article/details/gt2dskjfsab.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.tianlin.xyz/Article/details/gt2jhbzienc.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.gaohongyu789.top/Article/details/gt2xdiiobjl.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.cdnleiting.top/Article/details/gt2mglrymyx.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.tanke756.top/Article/details/gt2yohggbbr.html

[A09] 绝对值与最大最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ypnahrrq.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2trtmrysi.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gt2nbbwlnxm.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gt2nxvnptum.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.gzhubu.top/Article/details/gt2ihezehdl.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.aizwys.cn/Article/details/gt2wdssvryl.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hongshengwenyu.top/Article/details/gt2aoziokat.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.9152youxi.cn/Article/details/gt2mqosuhkn.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.aizwys.cn/Article/details/gt2dlowzadb.html

[A10] 生成随机数
来源：http://dali.hnqzz.top/Article/details/gt2erbmvocs.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jinqigufen.top/Article/details/gt2qhontbch.html

PHP:  random_int(1, 100);
来源：http://dali.snrcjt.cn/Article/details/gt2mlnimzrf.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.9152youxi.cn/Article/details/gt2rmqjdcso.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.redwolf501.top/Article/details/gt2drsiketw.html

Java: new Random().nextInt(100) + 1
来源：http://dali.wangdashe.top/Article/details/gt2brqqendp.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yueranfly.top/Article/details/gt2ttwdlpxr.html

Ruby: rand(1..100)
来源：http://dali.snrcjt.cn/Article/details/gt2lriicuto.html

C#:   new Random().Next(1, 101)
来源：http://dali.ehwqpu.com/Article/details/gt2vsdtkpuu.html

[A11] 条件表达式（三元）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2miulaymm.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.nanxuanxn.top/Article/details/gt2zhygzhyn.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.cashguo.top/Article/details/gt2hjttztjb.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.dashuyun.cn/Article/details/gt2ktwxteog.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2halzhrqa.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.svipenyu.cn/Article/details/gt2wxxtqarv.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.sufxvd.cn/Article/details/gt2fogaihkq.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zdqjudy.top/Article/details/gt2wibtuzmb.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.hywenlv.cn/Article/details/gt2echmgvnb.html

[A12] 字符串插值 / 格式化
来源：http://dali.tanke756.top/Article/details/gt2bopnrhrk.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.haohaochexian.top/Article/details/gt2ppjkmfkd.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.bjfxy.top/Article/details/gt2nrkpxfbb.html

JS:   `Hello, ${name}!`
来源：http://dali.sufxvd.cn/Article/details/gt2vtwtthsw.html

TS:   `Hello, ${name}!`
来源：http://dali.fengsongda.top/Article/details/gt2zqktzvky.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jyoumei.cn/Article/details/gt2qpdzhuvn.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.meibo888.top/Article/details/gt2qhlqnfma.html

Ruby: "Hello, #{name}!"
来源：http://dali.316326.xyz/Article/details/gt2hsffnyhf.html

C#:   $"Hello, {name}!"
来源：http://dali.tian-w.cn/Article/details/gt2wmfbhtlf.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2idjdydvo.html

Py:   "第一行\n第二行"
来源：http://dali.zhongyouzk.top/Article/details/gt2wpcnmxkl.html

PHP:  "第一行\n第二行"
来源：http://dali.shangyingyoupin.top/Article/details/gt2rjubhqeq.html

JS:   "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gt2gjujfsyn.html

TS:   "第一行\n第二行"
来源：http://dali.chenjidiqi.icu/Article/details/gt2xuawldpx.html

Java: "第一行\n第二行"
来源：http://dali.sufxvd.cn/Article/details/gt2gexunjjw.html

Go:   "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gt2jqvonpoj.html

Ruby: "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gt2xzegltig.html

C#:   "第一行\n第二行"
来源：http://dali.hnxiangtu.top/Article/details/gt2fixjbayz.html

[A14] 注释写法
来源：http://dali.bjfxy.top/Article/details/gt2cgapbaed.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jqgfzy.top/Article/details/gt2vkbsukqx.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zdxykekb.html

JS:   // 单行；/* 多行 */
来源：http://dali.dashuyun.cn/Article/details/gt2ucmmdxhu.html

TS:   // 单行；/* 多行 */
来源：http://dali.sxryk.cn/Article/details/gt2ydcwcyhh.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.cucudq.cn/Article/details/gt2oagqmemz.html

Go:   // 单行；/* 多行 */
来源：http://dali.xinyue.icu/Article/details/gt2bwxzgpmz.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yongpay.top/Article/details/gt2wnqrxshq.html

C#:   // 单行；/* 多行 */
来源：http://dali.ybcxt.top/Article/details/gt2uuwpjcuw.html

[A15] 空值判断与默认值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mkmtvlnk.html

Py:   value = data or "默认值"
来源：http://dali.gogol.net.cn/Article/details/gt2frvubybm.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.quarkkingdee.top/Article/details/gt2rutvwhew.html

JS:   const value = data ?? "默认值";
来源：http://dali.aizwys.cn/Article/details/gt2rifmmnkp.html

TS:   const value = data ?? "默认值";
来源：http://dali.vqdsnc.cn/Article/details/gt2jyyhosep.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.bjfxy.top/Article/details/gt2zetbxopd.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.hnqzz.top/Article/details/gt2cpjfbdly.html

Ruby: value = data || "默认值"
来源：http://dali.gogol.net.cn/Article/details/gt2tpgrkvqt.html

C#:   var value = data ?? "默认值";
来源：http://dali.yj202588.top/Article/details/gt2oadxocdm.html

[A16] 真假值判断规则
来源：http://dali.guannengcc.top/Article/details/gt2eqczpjwy.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhiwuduotai.top/Article/details/gt2awyfkihd.html


<!-- 参考信息 -->