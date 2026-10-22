代发 wailian999

[U93] JS：模板字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2fenkncbo.html

`共 ${n} 条`
来源：http://dali.snrcjt.cn/Article/details/gt2jwdikwtv.html

[U94] JS：箭头函数
来源：http://dali.ehwqpu.com/Article/details/gt2tlyhvqpf.html

const double = x => x * 2;
来源：http://dali.xinyue.icu/Article/details/gt2memcebtk.html

[U95] JS：Promise 包装
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aopehofu.html

new Promise((resolve, reject) => {})
来源：http://dali.jinqigfzy.top/Article/details/gt2tkcpjisz.html

[U96] JS：async/await 与异常
来源：http://dali.redwolf501.top/Article/details/gt2jeabjndx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gt2fjzrxbrv.html

[U97] JS：并发请求
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rkdnsfbd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gt2lyfqwbak.html

[U98] JS：fetch 带 JSON
来源：http://dali.bjfxy.top/Article/details/gt2koewfqwu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhoulong.xyz/Article/details/gt2ddkrmhug.html

[U99] JS：事件监听
来源：http://dali.jyoumei.cn/Article/details/gt2deqqktcm.html

el.addEventListener("click", e => {})
来源：http://dali.yj20258.top/Article/details/gt2zpoikhwk.html

[U100] JS：DOM 查询
来源：http://dali.bjfxy.top/Article/details/gt2flsyuwll.html

document.querySelector(".item")
来源：http://dali.hywenlv.cn/Article/details/gt2bvwrjqom.html

[U101] JS：classList 操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yxqeutyz.html

el.classList.toggle("active")
来源：http://dali.jinqigufen.top/Article/details/gt2rbjiyept.html

[U102] JS：本地存储
来源：http://dali.aizwys.cn/Article/details/gt2ohcsszmp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ydzc1.top/Article/details/gt2zijqyxdw.html

[U103] JS：定时器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qdntiqmz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yonumen.top/Article/details/gt2kctvshfg.html

[U104] JS：防抖
来源：http://dali.bjfxy.top/Article/details/gt2qimfxowb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gt2gbikgcmb.html

[U105] JS：节流
来源：http://dali.shangyingyoupin.top/Article/details/gt2jdoeolxu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ehwqpu.com/Article/details/gt2qluatanu.html

[U106] JS：日期格式化
来源：http://dali.yuxming.cn/Article/details/gt2bwfguexl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ehwqpu.com/Article/details/gt2gnddqqnj.html

[U107] JS：数字千分位
来源：http://dali.hammf.cn/Article/details/gt2qvjbpsjq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ppjwa.cn/Article/details/gt2qztrhscd.html

[U108] JS：随机整数
来源：http://dali.yj20258.top/Article/details/gt2aoyxpkgl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.tanke756.top/Article/details/gt2irbgcqkk.html

[U109] JS：数组分组
来源：http://dali.sweek.top/Article/details/gt2pwudmkqx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sufxvd.cn/Article/details/gt2dmbfpwos.html

[U110] JS：数组分块
来源：http://dali.dianchejie.cn/Article/details/gt2ynniffid.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yvedp.cn/Article/details/gt2jiklveuq.html

[U111] JS：对象转 Map
来源：http://dali.snrcjt.cn/Article/details/gt2kqpkndgo.html

new Map(Object.entries(obj))
来源：http://dali.andypj.xyz/Article/details/gt2zoxbanti.html

[U112] JS：字符串补位
来源：http://dali.xuetiantiany.cn/Article/details/gt2nbpdzwor.html

"7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uqneaznz.html

[U113] JS：正则替换全部
来源：http://dali.pycfn.com/Article/details/gt2olopohgp.html

s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gt2qyvlykzs.html

[U114] JS：JSON 深比较
来源：http://dali.svipenyu.cn/Article/details/gt2iynjvjmq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tbdzwdib.html

[U115] JS：生成 UUID
来源：http://dali.hywenlv.cn/Article/details/gt2olzgzeff.html

crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gt2pyswdakq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yanxiufei.cn/Article/details/gt2azzgpbma.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ppjwa.cn/Article/details/gt2yciwwgmh.html

[U117] JS：单元测试
来源：http://dali.cucudq.cn/Article/details/gt2bhzyifqb.html

npm i -D vitest;  npx vitest
来源：http://dali.yj202588.top/Article/details/gt2drvpwmmc.html

[U118] JS：开发服务器
来源：http://dali.shuidangran.top/Article/details/gt2hrztufnd.html

npm i -D vite;  npx vite
来源：http://dali.hywenlv.cn/Article/details/gt2crujkxye.html

[U119] JS：生产构建
来源：http://dali.feifeiyinyue.top/Article/details/gt2oinqxqzb.html

npx vite build
来源：http://dali.316326.xyz/Article/details/gt2qsuxpqtj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jiagoushi.top/Article/details/gt2genkptzm.html

import.meta.env.VITE_API_URL
来源：http://dali.svipenyu.cn/Article/details/gt2uqzlscnr.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2anvvoswq.html

统计汇总
来源：http://dali.tian-w.cn/Article/details/gt2fzdkznwj.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2ileyovqo.html

按语言统计（条）：
来源：http://dali.svipenyu.cn/Article/details/gt2yjldmejt.html

Python ......... 252
来源：http://dali.zycfv.cn/Article/details/gt2rmkvkzgq.html

PHP ............ 252
来源：http://dali.bjfxy.top/Article/details/gt2dyxbuuyg.html

JavaScript ..... 252
来源：http://dali.zhixingplan.top/Article/details/gt2ypoghnox.html

TypeScript ..... 212
来源：http://dali.jqgfzy.top/Article/details/gt2mahgowne.html

Java ........... 212
来源：http://dali.aibaodan.cn/Article/details/gt2bgsigwva.html

Go ............. 212
来源：http://dali.gzhubu.top/Article/details/gt2selufxyz.html

Ruby ........... 212
来源：http://dali.mhx1999.top/Article/details/gt2lnspcptz.html

C# ............. 212
来源：http://dali.yonumen.top/Article/details/gt2omqikker.html

C .............. 30
来源：http://dali.wangshuangyany.cn/Article/details/gt2ytoansru.html

C++ ............ 30
来源：http://dali.ppjwa.cn/Article/details/gt2swwynaiu.html

SQL ............ 90
来源：http://dali.svipenyu.cn/Article/details/gt2qecbqvev.html

Bash ........... 80
来源：http://dali.hnxiangtu.top/Article/details/gt2ogpirohd.html

Kotlin ......... 15
来源：http://dali.chenlongwang.top/Article/details/gt2inkkdwhy.html

Swift .......... 15
来源：http://dali.xinyue.icu/Article/details/gt2byxafbwd.html

Lua ............ 10
来源：http://dali.yanxiufei.cn/Article/details/gt2weptaseb.html

Perl ........... 10
来源：http://dali.daria6918.cn/Article/details/gt2hvspnfah.html

Scala .......... 10
来源：http://dali.yueranfly.top/Article/details/gt2yxhpkaba.html

------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gt2wmfgjyla.html

合计 ........... 2106 条
来源：http://dali.cheryme.top/Article/details/gt2htwrfaxg.html

按章节统计：
来源：http://dali.jyoumei.cn/Article/details/gt2ahtmrkkg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.nanxuanxn.top/Article/details/gt2amwbgfms.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hysaishi.cn/Article/details/gt2znruzzlc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.quarkkingdee.top/Article/details/gt2abazdart.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hywenlv.cn/Article/details/gt2yurchswf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cashguo.top/Article/details/gt2zxwxcodd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.sufxvd.cn/Article/details/gt2mgesexan.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gt2duwxssbm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hnxiangtu.top/Article/details/gt2kyfigpvz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gt2zxnlcytk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xylfe.cn/Article/details/gt2dpxwleil.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.iojbl.cn/Article/details/gt2pgfhofgr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gt2otwlqyah.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.feifeiyinyue.top/Article/details/gt2selwogzk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.guowangkeji.top/Article/details/gt2teeipesg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yongpay.top/Article/details/gt2xlfkxdzb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gt2zztnmhbc.html

Q SQL 专题                              90
来源：http://dali.cdnleiting.top/Article/details/gt2kthxkpbl.html

R Bash 专题                             80
来源：http://dali.fengsongda.top/Article/details/gt2hulstmca.html

S C / C++ 专题                          60
来源：http://dali.yongpay.top/Article/details/gt2ycdpsgwa.html

T 其他语言补充                          60
来源：http://dali.mhx1999.top/Article/details/gt2lbuqbdax.html

U 高频实用片段                         120
来源：http://dali.hfpthk.cn/Article/details/gt2ifpibdxh.html

------------------------------------
来源：http://dali.zycfv.cn/Article/details/gt2fyknnrdo.html

合计                                  2106 条
来源：http://dali.chenlongwang.top/Article/details/gt2saskguxb.html

--------------------------------------------------------------------------------
来源：http://dali.havefunace.top/Article/details/gt2ialdjyzm.html

使用提醒
来源：http://dali.ppjwa.cn/Article/details/gt2plqxvofn.html

--------------------------------------------------------------------------------
来源：http://dali.xinyue.icu/Article/details/gt2xxanwppk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ybcxt.top/Article/details/gt2aixbcxuk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.gzhubu.top/Article/details/gt2jrrwfrek.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.mhx1999.top/Article/details/gt2wkajmrvh.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.daria6918.cn/Article/details/gt2garsuaqr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hongshengwenyu.top/Article/details/gt2jgxajxmj.html

—— 文件结束 ——
来源：http://dali.jinqigfzy.top/Article/details/gt2rsrxqsyc.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2htlgesix.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.kuanghao11.cn/Article/details/gt2aigvtkof.html

Common Programming Examples Cheat Book
来源：http://dali.yangfankeji.com/Article/details/gt2zqmhdsgb.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2qrmmmdzo.html

【收录内容】
来源：http://dali.guowangkeji.top/Article/details/gt2kkhtegaa.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.dashuyun.cn/Article/details/gt2bcpkgvak.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cheryme.top/Article/details/gt2oszkxrcl.html

SQL · Bash · C · C++
来源：http://dali.cucudq.cn/Article/details/gt2xsoggyqf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.wangdashe.top/Article/details/gt2dxqnxzix.html

【使用说明】
来源：http://dali.sufxvd.cn/Article/details/gt2ahgmsypt.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.iojbl.cn/Article/details/gt2qxpulfym.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.dashuyun.cn/Article/details/gt2doeogdei.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.sufxvd.cn/Article/details/gt2iajstgwt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhixingplan.top/Article/details/gt2aclvwohd.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.316326.xyz/Article/details/gt2peroaefb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mwdgnuon.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.shangyingyoupin.top/Article/details/gt2zhxizzhb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.dianchejie.cn/Article/details/gt2txqaodcq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.dashuyun.cn/Article/details/gt2orldryed.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shzxlz.cn/Article/details/gt2hikhqovj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.haohaochexian.top/Article/details/gt2fgyxrqfo.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yj20258888.top/Article/details/gt2glcetjni.html

【文件统计】
来源：http://dali.mhx1999.top/Article/details/gt2uhykynxp.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hnqzz.top/Article/details/gt2bimbrsje.html

--------------------------------------------------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gt2zfnjujnw.html

目  录
来源：http://dali.chenlongwang.top/Article/details/gt2ripmumti.html

--------------------------------------------------------------------------------
来源：http://dali.jianghu66.top/Article/details/gt2perkbqay.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.c1oappe.top/Article/details/gt2dktmhumr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.snrcjt.cn/Article/details/gt2cuqwigas.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.9152youxi.cn/Article/details/gt2syrnalre.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2adnjdnou.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pyquyzeq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.smart0.xyz/Article/details/gt2lqadxyan.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.nanxinkj.top/Article/details/gt2xyfjpxgy.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.tianlin.xyz/Article/details/gt2yuhskmlg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gt2ktmqgnyc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.tianlin.xyz/Article/details/gt2yroeyrrd.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jyoumei.cn/Article/details/gt2lnclqpqz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2mkjzhzqc.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gt2evxiribu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shuidangran.top/Article/details/gt2hzmmzgxj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhixingplan.top/Article/details/gt2lkamrtoj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gt2tonnxlbs.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hywenlv.cn/Article/details/gt2ejjgfcps.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.sufxvd.cn/Article/details/gt2rweyesje.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xinyue.icu/Article/details/gt2zilzewlj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jyoumei.cn/Article/details/gt2teqpyoop.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenlongwang.top/Article/details/gt2tmekrhxm.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2lpfmqsci.html

A. 基础语法与类型
来源：http://dali.jlsjyb.cn/Article/details/gt2zkioxxjj.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2sxlwxwjc.html

[A01] Hello World
来源：http://dali.yongpay.top/Article/details/gt2gzyjkadl.html

Py:   print("Hello, World!")
来源：http://dali.jinqigufen.top/Article/details/gt2osjlznas.html

PHP:  echo "Hello, World!";
来源：http://dali.daxiang520.top/Article/details/gt2grfpmmfw.html

JS:   console.log("Hello, World!");
来源：http://dali.gotoacloud.top/Article/details/gt2wdxspiwa.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.svipenyu.cn/Article/details/gt2hfymrrza.html

Java: System.out.println("Hello, World!");
来源：http://dali.svipenyu.cn/Article/details/gt2yqiclrrc.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yj202588.top/Article/details/gt2hmyooqmw.html

Ruby: puts "Hello, World!"
来源：http://dali.zhixingplan.top/Article/details/gt2xcekdkfc.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.fzhhl.top/Article/details/gt2ryfgnauo.html

[A02] 变量声明与赋值
来源：http://dali.pengpengdd.cyou/Article/details/gt2qhevmron.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bexnpwiv.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2izbzmwaa.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.fengsongda.top/Article/details/gt2jfiqzmsr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zdqjudy.top/Article/details/gt2jzzfhggk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.daxiang520.top/Article/details/gt2ipwzpgyo.html

Go:   name := "Alex"; age := 20
来源：http://dali.nwbrower.top/Article/details/gt2llrrvddy.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gaohongyu789.top/Article/details/gt2enqmhaho.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.gogol.net.cn/Article/details/gt2cgcozzww.html

[A03] 常量定义
来源：http://dali.jiagoushi.top/Article/details/gt2nuhoiwsu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.haohaochexian.top/Article/details/gt2nweflhxk.html

PHP:  const PI = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gt2bypswets.html

JS:   const PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gt2kdogimkn.html

TS:   const PI: number = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gt2ujtjrgin.html

Java: static final double PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gt2xralllvp.html

Go:   const PI = 3.14159
来源：http://dali.shzxlz.cn/Article/details/gt2xuoeouvw.html

Ruby: PI = 3.14159
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kihhfsro.html

C#:   const double PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gt2gnzxftal.html

[A04] 判断变量类型
来源：http://dali.fzhhl.top/Article/details/gt2yyzfibni.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhoulong.xyz/Article/details/gt2ssbswhhn.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.nanxinkj.top/Article/details/gt2qceiltgs.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.316326.xyz/Article/details/gt2ahmcrzeb.html

TS:   typeof x; x instanceof Date
来源：http://dali.yj20258888.top/Article/details/gt2lwrqugaz.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.redwolf501.top/Article/details/gt2dbndxudn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dqtttccf.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.tanke756.top/Article/details/gt2clmyxtjm.html

C#:   x.GetType().Name; x is int
来源：http://dali.chenlongwang.top/Article/details/gt2zqhveczo.html

[A05] 整数除法与取模
来源：http://dali.snrcjt.cn/Article/details/gt2opyctcyj.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jinqigfzy.top/Article/details/gt2xhgixmxl.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yvedp.cn/Article/details/gt2oszlgtdh.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yueranfly.top/Article/details/gt2alutiqfi.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gt2pwflkryz.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2fkoahapp.html

Go:   7 / 2; 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gt2zamnthsp.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xinyue.icu/Article/details/gt2ixssoybe.html

C#:   7 / 2; 7 % 2
来源：http://dali.pycfn.com/Article/details/gt2yftukdxm.html

[A06] 字符串转数字
来源：http://dali.sysykeji.top/Article/details/gt2hjgturmg.html

Py:   int("42"); float("3.14")
来源：http://dali.zhixingplan.top/Article/details/gt2sciqatcr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.guannengcc.top/Article/details/gt2jyvrinvj.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.pycfn.com/Article/details/gt2wdjniokh.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.chenjidiqi.icu/Article/details/gt2fihkbikf.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ppvmmgvd.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yvedp.cn/Article/details/gt2tnqmcnaw.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.cashguo.top/Article/details/gt2qkcpzvzx.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ghutxllu.html

[A07] 数字转字符串
来源：http://dali.jqgfzy.top/Article/details/gt2wyddqdql.html

Py:   str(42)
来源：http://dali.tian-w.cn/Article/details/gt2hyrodxve.html

PHP:  (string) 42; strval(42)
来源：http://dali.iojbl.cn/Article/details/gt2apsfikza.html

JS:   String(42); (42).toString()
来源：http://dali.nanxinkj.top/Article/details/gt2fmakmnjs.html

TS:   String(42)
来源：http://dali.c1oappe.top/Article/details/gt2yzfoodhy.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.tianlin.xyz/Article/details/gt2nywgyedg.html

Go:   strconv.Itoa(42)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hoznrxac.html

Ruby: 42.to_s
来源：http://dali.cdnleiting.top/Article/details/gt2riwxlibw.html

C#:   42.ToString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2hbcggmvb.html

[A08] 取整与四舍五入
来源：http://dali.vqdsnc.cn/Article/details/gt2sordxhau.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.nanxuanxn.top/Article/details/gt2rpgftxkr.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.nwbrower.top/Article/details/gt2squxipvg.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.ehwqpu.com/Article/details/gt2pcqtroji.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.redwolf501.top/Article/details/gt2tsgljssu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ityfsire.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.daxiang520.top/Article/details/gt2xumbrkrd.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.ehwqpu.com/Article/details/gt2cbwiywfu.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.cucudq.cn/Article/details/gt2zsphbfgl.html

[A09] 绝对值与最大最小值
来源：http://dali.wangshuangyany.cn/Article/details/gt2ttvmmqdq.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.fzhhl.top/Article/details/gt2fpambzkr.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.andypj.xyz/Article/details/gt2dfcfdrrt.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.cucudq.cn/Article/details/gt2sanhmmkk.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2lytufwso.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gt2hfxezjkc.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.316326.xyz/Article/details/gt2rseenqam.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhongyouzk.top/Article/details/gt2uonrfpmb.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gt2nmelkfel.html

[A10] 生成随机数
来源：http://dali.guowangkeji.top/Article/details/gt2fexsbtch.html

Py:   import random; random.randint(1, 100)
来源：http://dali.ydzc1.top/Article/details/gt2gryduavk.html

PHP:  random_int(1, 100);
来源：http://dali.andypj.xyz/Article/details/gt2gzwxkqcm.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.fengsongda.top/Article/details/gt2gglhumhh.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sysykeji.top/Article/details/gt2qzliwefx.html

Java: new Random().nextInt(100) + 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2oajldyzh.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.guannengcc.top/Article/details/gt2plshbbfp.html

Ruby: rand(1..100)
来源：http://dali.sufxvd.cn/Article/details/gt2ldbwintb.html

C#:   new Random().Next(1, 101)
来源：http://dali.fengsongda.top/Article/details/gt2vjdythyr.html

[A11] 条件表达式（三元）
来源：http://dali.sysykeji.top/Article/details/gt2qdorstcw.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.tianlin.xyz/Article/details/gt2vmsilwsl.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.xuetiantiany.cn/Article/details/gt2oqjampqf.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.fengsongda.top/Article/details/gt2yxzyhsib.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.cheryme.top/Article/details/gt2sbawstwu.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ivvwwzfq.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.hnxiangtu.top/Article/details/gt2yuhnqnwl.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.ehwqpu.com/Article/details/gt2jxolgvxk.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qzaqnthz.html

[A12] 字符串插值 / 格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2itwwuixg.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.daria6918.cn/Article/details/gt2terosumj.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yj20258888.top/Article/details/gt2danpkrfx.html

JS:   `Hello, ${name}!`
来源：http://dali.cashguo.top/Article/details/gt2vysfakkk.html

TS:   `Hello, ${name}!`
来源：http://dali.sweek.top/Article/details/gt2acagolbv.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.haohaochexian.top/Article/details/gt2uwfzqmuk.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.svipenyu.cn/Article/details/gt2icckttfg.html

Ruby: "Hello, #{name}!"
来源：http://dali.zycfv.cn/Article/details/gt2ztiinant.html

C#:   $"Hello, {name}!"
来源：http://dali.0kj1m.cn/Article/details/gt2cahmvjri.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.daxiang520.top/Article/details/gt2zdlvwtag.html

Py:   "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gt2lndtslrz.html

PHP:  "第一行\n第二行"
来源：http://dali.jinqigfzy.top/Article/details/gt2uihhqiaa.html

JS:   "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gt2ovqvhzye.html

TS:   "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gt2jbinifva.html

Java: "第一行\n第二行"
来源：http://dali.hnqzz.top/Article/details/gt2kbysphsr.html

Go:   "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gt2llpsacgo.html

Ruby: "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gt2foynnsrb.html

C#:   "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gt2npvgxqyl.html

[A14] 注释写法
来源：http://dali.andypj.xyz/Article/details/gt2bdppofxc.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.dashuyun.cn/Article/details/gt2zgojpyft.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.pycfn.com/Article/details/gt2vvjqtqny.html

JS:   // 单行；/* 多行 */
来源：http://dali.cashguo.top/Article/details/gt2gzpnqbna.html

TS:   // 单行；/* 多行 */
来源：http://dali.gaohongyu789.top/Article/details/gt2srfnjrmm.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uveqlfbz.html

Go:   // 单行；/* 多行 */
来源：http://dali.kuanghao11.cn/Article/details/gt2qrbzxhsb.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.shuidangran.top/Article/details/gt2emrtfdpg.html

C#:   // 单行；/* 多行 */
来源：http://dali.fengsongda.top/Article/details/gt2cpqnvqad.html

[A15] 空值判断与默认值
来源：http://dali.jinqigfzy.top/Article/details/gt2dtgtymjp.html

Py:   value = data or "默认值"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rbhvifxa.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.sxryk.cn/Article/details/gt2cdulhvxx.html

JS:   const value = data ?? "默认值";
来源：http://dali.jlsjyb.cn/Article/details/gt2kmdedlnh.html

TS:   const value = data ?? "默认值";
来源：http://dali.mhx1999.top/Article/details/gt2dyeyeslk.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhongyouzk.top/Article/details/gt2taxwywwc.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yueranfly.top/Article/details/gt2djqbkqah.html

Ruby: value = data || "默认值"
来源：http://dali.guannengcc.top/Article/details/gt2zjivxert.html

C#:   var value = data ?? "默认值";
来源：http://dali.gaohongyu789.top/Article/details/gt2zgnwortc.html

[A16] 真假值判断规则
来源：http://dali.yj20258.top/Article/details/gt2cikhtumy.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.cucudq.cn/Article/details/gt2ngdykavt.html


<!-- 参考信息 -->