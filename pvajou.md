代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2jyzmvhdu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.shangyingyoupin.top/Article/details/gt2inspxypp.html

[U92] JS：深拷贝
来源：http://dali.cheryme.top/Article/details/gt2zcuzoojc.html

structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2hhergzus.html

[U93] JS：模板字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2vfbychod.html

`共 ${n} 条`
来源：http://dali.gaohongyu789.top/Article/details/gt2digkqrjc.html

[U94] JS：箭头函数
来源：http://dali.vqdsnc.cn/Article/details/gt2vfudmoqn.html

const double = x => x * 2;
来源：http://dali.chenjidiqi.icu/Article/details/gt2iegmyddt.html

[U95] JS：Promise 包装
来源：http://dali.xylfe.cn/Article/details/gt2hamtwlwy.html

new Promise((resolve, reject) => {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dunuyhlv.html

[U96] JS：async/await 与异常
来源：http://dali.9152youxi.cn/Article/details/gt2rfthmvnd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wovezyxv.html

[U97] JS：并发请求
来源：http://dali.zdqjudy.top/Article/details/gt2busvinvv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gt2mtyrscgl.html

[U98] JS：fetch 带 JSON
来源：http://dali.fzhhl.top/Article/details/gt2guocjace.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.dianchejie.cn/Article/details/gt2kjexqzrz.html

[U99] JS：事件监听
来源：http://dali.birdmap.top/Article/details/gt2tyowxlzg.html

el.addEventListener("click", e => {})
来源：http://dali.dashuyun.cn/Article/details/gt2rarqsqdl.html

[U100] JS：DOM 查询
来源：http://dali.bjfxy.top/Article/details/gt2hlgmfgng.html

document.querySelector(".item")
来源：http://dali.cucudq.cn/Article/details/gt2mtkqaqvq.html

[U101] JS：classList 操作
来源：http://dali.yuxming.cn/Article/details/gt2motblwmf.html

el.classList.toggle("active")
来源：http://dali.wangshuangyany.cn/Article/details/gt2odydmdjx.html

[U102] JS：本地存储
来源：http://dali.shangyingyoupin.top/Article/details/gt2gvegmdbj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.wangdashe.top/Article/details/gt2jhxktaty.html

[U103] JS：定时器
来源：http://dali.jianghu66.top/Article/details/gt2nbtnherv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.0kj1m.cn/Article/details/gt2gpquzdqq.html

[U104] JS：防抖
来源：http://dali.pengpengdd.cyou/Article/details/gt2svptmxod.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangshuangyany.cn/Article/details/gt2rixslpsl.html

[U105] JS：节流
来源：http://dali.gaohongyu789.top/Article/details/gt2hmhxteya.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.fengsongda.top/Article/details/gt2ntknoebo.html

[U106] JS：日期格式化
来源：http://dali.nwbrower.top/Article/details/gt2rtxuzksr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhoulong.xyz/Article/details/gt2mhvpiiwz.html

[U107] JS：数字千分位
来源：http://dali.hnqzz.top/Article/details/gt2jiyxwcml.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gt2pjnpjspf.html

[U108] JS：随机整数
来源：http://dali.smart0.xyz/Article/details/gt2ufklhjpl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.aibaodan.cn/Article/details/gt2irfoaxtz.html

[U109] JS：数组分组
来源：http://dali.mhx1999.top/Article/details/gt2bavppfyv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jqgfzy.top/Article/details/gt2nnbherbf.html

[U110] JS：数组分块
来源：http://dali.xinyue.icu/Article/details/gt2yqxeaewa.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cqqwz.cn/Article/details/gt2pdywpgvx.html

[U111] JS：对象转 Map
来源：http://dali.haohaochexian.top/Article/details/gt2nliytsks.html

new Map(Object.entries(obj))
来源：http://dali.tian-w.cn/Article/details/gt2apljmmgy.html

[U112] JS：字符串补位
来源：http://dali.mhx1999.top/Article/details/gt2kstkhoih.html

"7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gt2idupiglx.html

[U113] JS：正则替换全部
来源：http://dali.quarkkingdee.top/Article/details/gt2crewhymv.html

s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2pbyvtsrv.html

[U114] JS：JSON 深比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2cyqfduos.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yongpay.top/Article/details/gt2kspdlkej.html

[U115] JS：生成 UUID
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yholtjjw.html

crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fxhowiyn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cashguo.top/Article/details/gt2ttwebrtk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ppjwa.cn/Article/details/gt2zjjckbbs.html

[U117] JS：单元测试
来源：http://dali.zhengqikj.top/Article/details/gt2ypzfnyds.html

npm i -D vitest;  npx vitest
来源：http://dali.shanyushiyangtech.top/Article/details/gt2muzbgbwm.html

[U118] JS：开发服务器
来源：http://dali.xuanzx.com/Article/details/gt2ophogtnp.html

npm i -D vite;  npx vite
来源：http://dali.vqdsnc.cn/Article/details/gt2vozsrkzw.html

[U119] JS：生产构建
来源：http://dali.chenlongwang.top/Article/details/gt2pvjwvfoo.html

npx vite build
来源：http://dali.xziqi.cn/Article/details/gt2xrdknszz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shuidangran.top/Article/details/gt2tvhurozx.html

import.meta.env.VITE_API_URL
来源：http://dali.hongshengwenyu.top/Article/details/gt2jekqvypl.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2omedbaei.html

统计汇总
来源：http://dali.hongshengwenyu.top/Article/details/gt2swhiwoqd.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2cbcilnhi.html

按语言统计（条）：
来源：http://dali.xinyue.icu/Article/details/gt2rmdmupyu.html

Python ......... 252
来源：http://dali.kuanghao11.cn/Article/details/gt2jmhwwkvm.html

PHP ............ 252
来源：http://dali.chenjidiqi.icu/Article/details/gt2gwuzcxfm.html

JavaScript ..... 252
来源：http://dali.kuanghao11.cn/Article/details/gt2pmccubcn.html

TypeScript ..... 212
来源：http://dali.fengsongda.top/Article/details/gt2uvkgisqf.html

Java ........... 212
来源：http://dali.jiagoushi.top/Article/details/gt2xwuaxkwy.html

Go ............. 212
来源：http://dali.chenlongwang.top/Article/details/gt2eiiosour.html

Ruby ........... 212
来源：http://dali.ppjwa.cn/Article/details/gt2wezbnckx.html

C# ............. 212
来源：http://dali.ybcxt.top/Article/details/gt2mljngrsl.html

C .............. 30
来源：http://dali.vqdsnc.cn/Article/details/gt2qbajtaob.html

C++ ............ 30
来源：http://dali.snrcjt.cn/Article/details/gt2htiljbbu.html

SQL ............ 90
来源：http://dali.pengpengdd.cyou/Article/details/gt2bgsiheln.html

Bash ........... 80
来源：http://dali.birdmap.top/Article/details/gt2eroubypa.html

Kotlin ......... 15
来源：http://dali.cheryme.top/Article/details/gt2ifqjnxwl.html

Swift .......... 15
来源：http://dali.yonumen.top/Article/details/gt2ounoppye.html

Lua ............ 10
来源：http://dali.xuetiantiany.cn/Article/details/gt2jjsfitre.html

Perl ........... 10
来源：http://dali.tian-w.cn/Article/details/gt2arwyovyg.html

Scala .......... 10
来源：http://dali.yvedp.cn/Article/details/gt2dlpbfhgw.html

------------------------------------
来源：http://dali.wangdashe.top/Article/details/gt2rfigalqh.html

合计 ........... 2106 条
来源：http://dali.meibo888.top/Article/details/gt2hjksribo.html

按章节统计：
来源：http://dali.hnqzz.top/Article/details/gt2ufqjmkrg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xuetiantiany.cn/Article/details/gt2dlsvkygd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gotoacloud.top/Article/details/gt2mvachfuf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gt2idwtiehc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.vqdsnc.cn/Article/details/gt2pcgnfsbj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cdnleiting.top/Article/details/gt2thlurlrn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.havefunace.top/Article/details/gt2ibuwqpsz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gt2pzofuwlz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yuanzhike.top/Article/details/gt2nxjleqem.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gt2gvkancpu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xuanzx.com/Article/details/gt2gryfjzca.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gt2wrrsthgw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gt2nsmfrkss.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gt2qdpirfbc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj202588.top/Article/details/gt2pwhfwnbt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zdqjudy.top/Article/details/gt2zcoxmcjf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.sweek.top/Article/details/gt2zfbghliv.html

Q SQL 专题                              90
来源：http://dali.jqgufenzy.top/Article/details/gt2lvhtyvjx.html

R Bash 专题                             80
来源：http://dali.yangfankeji.com/Article/details/gt2gngeulav.html

S C / C++ 专题                          60
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cmromojq.html

T 其他语言补充                          60
来源：http://dali.guowangkeji.top/Article/details/gt2dsatesxn.html

U 高频实用片段                         120
来源：http://dali.jlsjyb.cn/Article/details/gt2hciibkwp.html

------------------------------------
来源：http://dali.jianghu66.top/Article/details/gt2ohxyzndw.html

合计                                  2106 条
来源：http://dali.yuanzhike.top/Article/details/gt2wmzspktx.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigfzy.top/Article/details/gt2lzmkuhhn.html

使用提醒
来源：http://dali.yj20258.top/Article/details/gt2rzcvovna.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gt2ymykpedw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.c1oappe.top/Article/details/gt2upnbsjqj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cdnleiting.top/Article/details/gt2progskbw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xinyue.icu/Article/details/gt2mokbwjxg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.c1oappe.top/Article/details/gt2vbtmtmpg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.chenjidiqi.icu/Article/details/gt2wuflikhz.html

—— 文件结束 ——
来源：http://dali.aizwys.cn/Article/details/gt2utlsnnvk.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2irrkcfok.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ivvv.top/Article/details/gt2dawealse.html

Common Programming Examples Cheat Book
来源：http://dali.cdnleiting.top/Article/details/gt2tvctvzhx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nofvhlft.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2otnotqoo.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hnxiangtu.top/Article/details/gt2jmiqenvv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.sweek.top/Article/details/gt2xqwpkwmb.html

SQL · Bash · C · C++
来源：http://dali.yuxming.cn/Article/details/gt2fxyqaeqn.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.nanxuanxn.top/Article/details/gt2cejvgafz.html

【使用说明】
来源：http://dali.gotoacloud.top/Article/details/gt2shqtlxzl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.feifeiyinyue.top/Article/details/gt2uhwotfqv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinqigufen.top/Article/details/gt2znjherwi.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.aizwys.cn/Article/details/gt2nwhopwtn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yuanzhike.top/Article/details/gt2brgmutfp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yanxiufei.cn/Article/details/gt2fticctak.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.9152youxi.cn/Article/details/gt2vukkzyjf.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.kuanghao11.cn/Article/details/gt2rcgsjkpe.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xuetiantiany.cn/Article/details/gt2lcshqbdx.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wsjbxias.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zdqjudy.top/Article/details/gt2vxglnxvo.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xylfe.cn/Article/details/gt2cmrmbggz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jinqigfzy.top/Article/details/gt2zssvcohd.html

【文件统计】
来源：http://dali.cdnleiting.top/Article/details/gt2flqhjexr.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhengqikj.top/Article/details/gt2lencdkyu.html

--------------------------------------------------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gt2eyitfcse.html

目  录
来源：http://dali.jinqigfzy.top/Article/details/gt2bizuinmu.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gt2lqjzvxhl.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yueranfly.top/Article/details/gt2oqyijbmw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.pengpengdd.cyou/Article/details/gt2aavxqtsk.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.aizwys.cn/Article/details/gt2xcioquwr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.iojbl.cn/Article/details/gt2lcnbzzlz.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sqjuupqc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xylfe.cn/Article/details/gt2jqqyqoga.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.birdmap.top/Article/details/gt2osigtkbz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hysaishi.cn/Article/details/gt2nieonspk.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ydzc1.top/Article/details/gt2uvulvofz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.chenzaomai.com/Article/details/gt2ccezbwao.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.chenzaomai.com/Article/details/gt2vdiqjfrx.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2cxibqpmd.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.svipenyu.cn/Article/details/gt2vixrjzuz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yvedp.cn/Article/details/gt2qlpuicpd.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xylfe.cn/Article/details/gt2jlrrotbb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.gzhubu.top/Article/details/gt2noewiwvg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xinyue.icu/Article/details/gt2zupsoqtl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yueranfly.top/Article/details/gt2bcsviqop.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.snrcjt.cn/Article/details/gt2ibppcvhc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zycfv.cn/Article/details/gt2gjijowje.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.aibaodan.cn/Article/details/gt2offwvxab.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2xvdmakoy.html

A. 基础语法与类型
来源：http://dali.sysykeji.top/Article/details/gt2yjooeqvl.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2ujarhqmf.html

[A01] Hello World
来源：http://dali.hywenlv.cn/Article/details/gt2hndmgezg.html

Py:   print("Hello, World!")
来源：http://dali.zhengqikj.top/Article/details/gt2yctdagca.html

PHP:  echo "Hello, World!";
来源：http://dali.ydzc1.top/Article/details/gt2dvvojplm.html

JS:   console.log("Hello, World!");
来源：http://dali.sufxvd.cn/Article/details/gt2wmsdwmqj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.gaohongyu789.top/Article/details/gt2lzdayzwm.html

Java: System.out.println("Hello, World!");
来源：http://dali.aibaodan.cn/Article/details/gt2isbsftrv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lrbgdbpz.html

Ruby: puts "Hello, World!"
来源：http://dali.cheryme.top/Article/details/gt2sbvlirtj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jinqigfzy.top/Article/details/gt2aplrecjz.html

[A02] 变量声明与赋值
来源：http://dali.zhixingplan.top/Article/details/gt2cbromvey.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ppjwa.cn/Article/details/gt2jgbqsxht.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tvinkghk.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cdnleiting.top/Article/details/gt2obhvbusu.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.smart0.xyz/Article/details/gt2hixrilxv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xziqi.cn/Article/details/gt2thkjqmsa.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2gjroelkn.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jinqigufen.top/Article/details/gt2fzgosvxh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.aibaodan.cn/Article/details/gt2gfghoexa.html

[A03] 常量定义
来源：http://dali.shuidangran.top/Article/details/gt2fhlbzftn.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.sufxvd.cn/Article/details/gt2jfeklldw.html

PHP:  const PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gt2fhqmheaq.html

JS:   const PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gt2atgokpxj.html

TS:   const PI: number = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gt2tgbtwtko.html

Java: static final double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gt2tgxlfadv.html

Go:   const PI = 3.14159
来源：http://dali.c1oappe.top/Article/details/gt2wjukknzn.html

Ruby: PI = 3.14159
来源：http://dali.yongpay.top/Article/details/gt2twaxkmyb.html

C#:   const double PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gt2spcwstyh.html

[A04] 判断变量类型
来源：http://dali.yongpay.top/Article/details/gt2sdiqtdsr.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.dashuyun.cn/Article/details/gt2ztkpgzps.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.sysykeji.top/Article/details/gt2ytpbnvuu.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.316326.xyz/Article/details/gt2fribkymx.html

TS:   typeof x; x instanceof Date
来源：http://dali.shanyushiyangtech.top/Article/details/gt2efzzidbq.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xinyue.icu/Article/details/gt2tukqjjyf.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.daxiang520.top/Article/details/gt2jzttpjwg.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xylfe.cn/Article/details/gt2taxocaxi.html

C#:   x.GetType().Name; x is int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oxskhzma.html

[A05] 整数除法与取模
来源：http://dali.jyoumei.cn/Article/details/gt2wktgueks.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cqqwz.cn/Article/details/gt2cmnjfphk.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gt2cgkivljn.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gt2cuwzlqhm.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.nanxuanxn.top/Article/details/gt2utzmscni.html

Java: 7 / 2; 7 % 2
来源：http://dali.hnqzz.top/Article/details/gt2oxhcaddw.html

Go:   7 / 2; 7 % 2
来源：http://dali.xziqi.cn/Article/details/gt2wxkaesrc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gt2mjvgmfrh.html

C#:   7 / 2; 7 % 2
来源：http://dali.yvedp.cn/Article/details/gt2gunvexcv.html

[A06] 字符串转数字
来源：http://dali.yueranfly.top/Article/details/gt2jdgduxrn.html

Py:   int("42"); float("3.14")
来源：http://dali.meibo888.top/Article/details/gt2fxxpjhct.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jianghu66.top/Article/details/gt2mivcaocu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.xziqi.cn/Article/details/gt2jveglrvt.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.gaohongyu789.top/Article/details/gt2eeuvndun.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jinqigufen.top/Article/details/gt2iwdkrqwe.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljixlpvb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.chenlongwang.top/Article/details/gt2lddnwktk.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2frubrkyx.html

[A07] 数字转字符串
来源：http://dali.haohaochexian.top/Article/details/gt2qxdwezol.html

Py:   str(42)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rkymlxmv.html

PHP:  (string) 42; strval(42)
来源：http://dali.mhx1999.top/Article/details/gt2oqhmcqru.html

JS:   String(42); (42).toString()
来源：http://dali.hammf.cn/Article/details/gt2nvkckhsd.html

TS:   String(42)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bezejmwp.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xpzbpcqm.html

Go:   strconv.Itoa(42)
来源：http://dali.jqgfzy.top/Article/details/gt2pscpjrch.html

Ruby: 42.to_s
来源：http://dali.meibo888.top/Article/details/gt2ojpfswmj.html

C#:   42.ToString()
来源：http://dali.guowangkeji.top/Article/details/gt2gvwxyboz.html

[A08] 取整与四舍五入
来源：http://dali.shanyushiyangtech.top/Article/details/gt2witoviln.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.xuanzx.com/Article/details/gt2zqqbguhj.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jqgfzy.top/Article/details/gt2kccpzbhg.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.c1oappe.top/Article/details/gt2qsdvlgng.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jqgfzy.top/Article/details/gt2zlrwijyf.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.quarkkingdee.top/Article/details/gt2mhfjwxyx.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jlsjyb.cn/Article/details/gt2bkbvrgtm.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.0kj1m.cn/Article/details/gt2vszmoprv.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.vqdsnc.cn/Article/details/gt2morpfnsv.html

[A09] 绝对值与最大最小值
来源：http://dali.sysykeji.top/Article/details/gt2iltmgyyc.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.havefunace.top/Article/details/gt2mhaywygz.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.smart0.xyz/Article/details/gt2nhiakkpp.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fasicrjv.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gt2vieaztma.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lzavmskd.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.wangdashe.top/Article/details/gt2ssfxyyqg.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yvedp.cn/Article/details/gt2zsxhnuxg.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xotfadty.html

[A10] 生成随机数
来源：http://dali.xinyue.icu/Article/details/gt2pzbdlfxg.html

Py:   import random; random.randint(1, 100)
来源：http://dali.xylfe.cn/Article/details/gt2ylopbhhj.html

PHP:  random_int(1, 100);
来源：http://dali.9152youxi.cn/Article/details/gt2kdnqhfue.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sweek.top/Article/details/gt2neynuwdv.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.smart0.xyz/Article/details/gt2znacpitl.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jinqigufen.top/Article/details/gt2rnzffwhn.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.birdmap.top/Article/details/gt2pxenjzps.html

Ruby: rand(1..100)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jgtadnqc.html

C#:   new Random().Next(1, 101)
来源：http://dali.jqgufenzy.top/Article/details/gt2qminwjjq.html

[A11] 条件表达式（三元）
来源：http://dali.gotoacloud.top/Article/details/gt2cbtidtnk.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.snrcjt.cn/Article/details/gt2ibdlalgu.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hongshengwenyu.top/Article/details/gt2mdkklaaf.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.9152youxi.cn/Article/details/gt2gzrwqyba.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iblhuqso.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.fengsongda.top/Article/details/gt2rmmpacxd.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jiagoushi.top/Article/details/gt2uaknkmpp.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.svipenyu.cn/Article/details/gt2dhkbywpl.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.cucudq.cn/Article/details/gt2jtozlelp.html

[A12] 字符串插值 / 格式化
来源：http://dali.sweek.top/Article/details/gt2ewliyolm.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jlsjyb.cn/Article/details/gt2bznlvvtb.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.kuanghao11.cn/Article/details/gt2leuydbkz.html

JS:   `Hello, ${name}!`
来源：http://dali.cucudq.cn/Article/details/gt2sokucafu.html

TS:   `Hello, ${name}!`
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bypujtnq.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zycfv.cn/Article/details/gt2rksyuhut.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.wangshuangyany.cn/Article/details/gt2notbipnk.html

Ruby: "Hello, #{name}!"
来源：http://dali.jiagoushi.top/Article/details/gt2czvglucs.html

C#:   $"Hello, {name}!"
来源：http://dali.zycfv.cn/Article/details/gt2xfpdanpr.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zdqjudy.top/Article/details/gt2wwevusnj.html

Py:   "第一行\n第二行"
来源：http://dali.zhengqikj.top/Article/details/gt2wlhgbplw.html

PHP:  "第一行\n第二行"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kxiwhpbh.html

JS:   "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gt2ohkkbojj.html

TS:   "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gt2pcpfrucd.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vopedcpu.html

Go:   "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gt2ixwcxkdq.html

Ruby: "第一行\n第二行"
来源：http://dali.shuidangran.top/Article/details/gt2ysfgmrul.html

C#:   "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hldbzpkp.html

[A14] 注释写法
来源：http://dali.hnxiangtu.top/Article/details/gt2vgazjxag.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.sweek.top/Article/details/gt2addeyyyo.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.chenjidiqi.icu/Article/details/gt2pacffknw.html

JS:   // 单行；/* 多行 */
来源：http://dali.ehwqpu.com/Article/details/gt2arhjriyf.html

TS:   // 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gt2bulujdbo.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.gaohongyu789.top/Article/details/gt2cqyfhrup.html

Go:   // 单行；/* 多行 */
来源：http://dali.gaohongyu789.top/Article/details/gt2pjkokrmz.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.xziqi.cn/Article/details/gt2innlvmrq.html

C#:   // 单行；/* 多行 */
来源：http://dali.xziqi.cn/Article/details/gt2hvdrquuv.html

[A15] 空值判断与默认值
来源：http://dali.yanxiufei.cn/Article/details/gt2zbiqxeze.html

Py:   value = data or "默认值"
来源：http://dali.xinyue.icu/Article/details/gt2bandxmvw.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.tanke756.top/Article/details/gt2rvrhpxbi.html

JS:   const value = data ?? "默认值";
来源：http://dali.gaohongyu789.top/Article/details/gt2dclcequp.html

TS:   const value = data ?? "默认值";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nbpekism.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.smart0.xyz/Article/details/gt2vdmlxidb.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ifyokjoy.html


<!-- 参考信息 -->