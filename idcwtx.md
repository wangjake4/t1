代发 wailian999

[U85] JS：可选链
来源：http://dali.yj202588.top/Article/details/gtjbtnahqx.html

a?.b?.c
来源：http://dali.cheryme.top/Article/details/gtpvjccoxt.html

[U86] JS：空值合并
来源：http://dali.meibo888.top/Article/details/gtnsrborgn.html

a ?? b
来源：http://dali.feifeiyinyue.top/Article/details/gtylrxxepu.html

[U87] JS：解构默认值
来源：http://dali.hongshengwenyu.top/Article/details/gtcbvvxqed.html

const { a = 1, b = 2 } = obj;
来源：http://dali.sysykeji.top/Article/details/gtvpaodczu.html

[U88] JS：对象展开合并
来源：http://dali.jqgufenzy.top/Article/details/gtfusepmqz.html

{ ...a, ...b }
来源：http://dali.hnxiangtu.top/Article/details/gtflkkvqxv.html

[U89] JS：数组去重
来源：http://dali.yanxiufei.cn/Article/details/gttuyjsrkn.html

[...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gtxflyjezt.html

[U90] JS：数字数组排序
来源：http://dali.daxiang520.top/Article/details/gteszyqzvh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gtcrhwqsjt.html

[U91] JS：对象键值遍历
来源：http://dali.tanke756.top/Article/details/gtzazsgvsv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.tianlin.xyz/Article/details/gtlewqvsix.html

[U92] JS：深拷贝
来源：http://dali.jianghu66.top/Article/details/gtvqpihudr.html

structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gtifxciovb.html

[U93] JS：模板字符串
来源：http://dali.sweek.top/Article/details/gtnxfnfvda.html

`共 ${n} 条`
来源：http://dali.hfpthk.cn/Article/details/gtajigejll.html

[U94] JS：箭头函数
来源：http://dali.chenzaomai.com/Article/details/gtfmwmghrp.html

const double = x => x * 2;
来源：http://dali.jianghu66.top/Article/details/gttpbnqkaj.html

[U95] JS：Promise 包装
来源：http://dali.zdqjudy.top/Article/details/gtbglqpefa.html

new Promise((resolve, reject) => {})
来源：http://dali.yueranfly.top/Article/details/gtfsyhzuzx.html

[U96] JS：async/await 与异常
来源：http://dali.c1oappe.top/Article/details/gtijyezsdy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gtpphxuire.html

[U97] JS：并发请求
来源：http://dali.jiagoushi.top/Article/details/gtltnnmkvo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gtqtadgakp.html

[U98] JS：fetch 带 JSON
来源：http://dali.smart0.xyz/Article/details/gtmoagnfeq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.tianlin.xyz/Article/details/gtymzbckgz.html

[U99] JS：事件监听
来源：http://dali.hnqzz.top/Article/details/gtfenogtkn.html

el.addEventListener("click", e => {})
来源：http://dali.haohaochexian.top/Article/details/gtpvowtodd.html

[U100] JS：DOM 查询
来源：http://dali.andypj.xyz/Article/details/gtlosqdxws.html

document.querySelector(".item")
来源：http://dali.jlsjyb.cn/Article/details/gtgvamhmif.html

[U101] JS：classList 操作
来源：http://dali.yonumen.top/Article/details/gtficdvjwk.html

el.classList.toggle("active")
来源：http://dali.ivvv.top/Article/details/gtadgiofqv.html

[U102] JS：本地存储
来源：http://dali.xziqi.cn/Article/details/gtcicovbvj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jinqigufen.top/Article/details/gtkvevfimy.html

[U103] JS：定时器
来源：http://dali.birdmap.top/Article/details/gtsfkurnyr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ivvv.top/Article/details/gtovawyjgi.html

[U104] JS：防抖
来源：http://dali.ehwqpu.com/Article/details/gthucjgvcx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxbenryj.html

[U105] JS：节流
来源：http://dali.wangdashe.top/Article/details/gtcgalcbne.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.fzhhl.top/Article/details/gtiktthmsj.html

[U106] JS：日期格式化
来源：http://dali.9152youxi.cn/Article/details/gtlrntsntv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ivvv.top/Article/details/gtxsqthxox.html

[U107] JS：数字千分位
来源：http://dali.zhengqikj.top/Article/details/gtihsvalxt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gtawbtothb.html

[U108] JS：随机整数
来源：http://dali.redwolf501.top/Article/details/gthwhgkfjv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.pengpengdd.cyou/Article/details/gtrvspxhwr.html

[U109] JS：数组分组
来源：http://dali.bjfxy.top/Article/details/gtaqciesnb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xuetiantiany.cn/Article/details/gtdxccfpti.html

[U110] JS：数组分块
来源：http://dali.yuxming.cn/Article/details/gtpjfjnmcy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.pengpengdd.cyou/Article/details/gtuparmitf.html

[U111] JS：对象转 Map
来源：http://dali.smart0.xyz/Article/details/gtuhjoppmp.html

new Map(Object.entries(obj))
来源：http://dali.sweek.top/Article/details/gtawkikzkf.html

[U112] JS：字符串补位
来源：http://dali.ybcxt.top/Article/details/gtncguaaud.html

"7".padStart(3, "0")
来源：http://dali.cucudq.cn/Article/details/gtgvylpurz.html

[U113] JS：正则替换全部
来源：http://dali.hongshengwenyu.top/Article/details/gtzxazjbhj.html

s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtkmjbtznq.html

[U114] JS：JSON 深比较
来源：http://dali.havefunace.top/Article/details/gttourvgoh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zycfv.cn/Article/details/gtkegkorgv.html

[U115] JS：生成 UUID
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdztigfvl.html

crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gtqwatmohn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hywenlv.cn/Article/details/gtmgbufhqq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.fzhhl.top/Article/details/gtdmgibcbu.html

[U117] JS：单元测试
来源：http://dali.chenjidiqi.icu/Article/details/gtyisvwykc.html

npm i -D vitest;  npx vitest
来源：http://dali.yvedp.cn/Article/details/gtiotamouj.html

[U118] JS：开发服务器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgttpkywo.html

npm i -D vite;  npx vite
来源：http://dali.nanxuanxn.top/Article/details/gtyjweerwg.html

[U119] JS：生产构建
来源：http://dali.ydzc1.top/Article/details/gtddhmgldl.html

npx vite build
来源：http://dali.ehwqpu.com/Article/details/gtwnferwkp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhiwuduotai.top/Article/details/gtyikkwptb.html

import.meta.env.VITE_API_URL
来源：http://dali.cqqwz.cn/Article/details/gtuuwhqyui.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtkahxwegz.html

统计汇总
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxcekmal.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtonqammuh.html

按语言统计（条）：
来源：http://dali.chenzaomai.com/Article/details/gtbqkzjbxy.html

Python ......... 252
来源：http://dali.cqqwz.cn/Article/details/gtkdepkrrk.html

PHP ............ 252
来源：http://dali.ppjwa.cn/Article/details/gtiswklick.html

JavaScript ..... 252
来源：http://dali.tianlin.xyz/Article/details/gtyiranbev.html

TypeScript ..... 212
来源：http://dali.vqdsnc.cn/Article/details/gtrcfljlql.html

Java ........... 212
来源：http://dali.jqgfzy.top/Article/details/gtkbdbljxt.html

Go ............. 212
来源：http://dali.feifeiyinyue.top/Article/details/gtsjqoxadd.html

Ruby ........... 212
来源：http://dali.zhengqikj.top/Article/details/gtshlaizny.html

C# ............. 212
来源：http://dali.nanxuanxn.top/Article/details/gtpxdwuuqc.html

C .............. 30
来源：http://dali.pycfn.com/Article/details/gtbuezhjbb.html

C++ ............ 30
来源：http://dali.iojbl.cn/Article/details/gttvfhotwh.html

SQL ............ 90
来源：http://dali.yangfankeji.com/Article/details/gtuoalipin.html

Bash ........... 80
来源：http://dali.zhongyouzk.top/Article/details/gtbzvgdpng.html

Kotlin ......... 15
来源：http://dali.cdnleiting.top/Article/details/gtsrwxgnqz.html

Swift .......... 15
来源：http://dali.jinqigufen.top/Article/details/gtziuswzil.html

Lua ............ 10
来源：http://dali.hnqzz.top/Article/details/gtjnsettkf.html

Perl ........... 10
来源：http://dali.fengsongda.top/Article/details/gtbdqtnoya.html

Scala .......... 10
来源：http://dali.hywenlv.cn/Article/details/gtrearfrtj.html

------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gtshsauzxq.html

合计 ........... 2106 条
来源：http://dali.svipenyu.cn/Article/details/gtwhidiivf.html

按章节统计：
来源：http://dali.gaohongyu789.top/Article/details/gtrukvrydv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gzhubu.top/Article/details/gtiekdwxcb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cqqwz.cn/Article/details/gtgjnkrstw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhoulong.xyz/Article/details/gtbiociiqy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gaohongyu789.top/Article/details/gtlumjyfss.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gtunihwrfp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.0kj1m.cn/Article/details/gtzobeyspc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjhlyxnl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cqqwz.cn/Article/details/gtwlvdqigx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gtxtaogsoa.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.kuanghao11.cn/Article/details/gtsnvwqryn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gtognhmmoz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmtjcfbr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gtaksoarlo.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.tianlin.xyz/Article/details/gtqdlwfywu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.iojbl.cn/Article/details/gtjplviwcj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gtycowpred.html

Q SQL 专题                              90
来源：http://dali.zhiwuduotai.top/Article/details/gtyksayvwm.html

R Bash 专题                             80
来源：http://dali.snrcjt.cn/Article/details/gtxcwjhmcs.html

S C / C++ 专题                          60
来源：http://dali.jinqigufen.top/Article/details/gtsaimonug.html

T 其他语言补充                          60
来源：http://dali.guowangkeji.top/Article/details/gticpqhkho.html

U 高频实用片段                         120
来源：http://dali.xuetiantiany.cn/Article/details/gtgfqbdtmz.html

------------------------------------
来源：http://dali.guannengcc.top/Article/details/gtzmjpmxir.html

合计                                  2106 条
来源：http://dali.nwbrower.top/Article/details/gtbexcgzzl.html

--------------------------------------------------------------------------------
来源：http://dali.yvedp.cn/Article/details/gtereyeyzg.html

使用提醒
来源：http://dali.chenzaomai.com/Article/details/gtbkjserqq.html

--------------------------------------------------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpxbnlew.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jqgufenzy.top/Article/details/gtwcsidytf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cucudq.cn/Article/details/gtnlzncifj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.fzhhl.top/Article/details/gtozogaicg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ivvv.top/Article/details/gtmycsvvbs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jqgufenzy.top/Article/details/gtvsysqicb.html

—— 文件结束 ——
来源：http://dali.c1oappe.top/Article/details/gthrfhlluv.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtccjkmwqf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xziqi.cn/Article/details/gtdnkqyuof.html

Common Programming Examples Cheat Book
来源：http://dali.gotoacloud.top/Article/details/gtothswjfh.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtztwfjqvd.html

【收录内容】
来源：http://dali.meibo888.top/Article/details/gthzbxozyp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.sxryk.cn/Article/details/gtduhlgfns.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.chenzaomai.com/Article/details/gthsxvubfi.html

SQL · Bash · C · C++
来源：http://dali.chenlongwang.top/Article/details/gtpovccqlf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.0kj1m.cn/Article/details/gtqdtlbbik.html

【使用说明】
来源：http://dali.xziqi.cn/Article/details/gtgrwgyhtb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.snrcjt.cn/Article/details/gtvwmnhnel.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hongshengwenyu.top/Article/details/gtfcvlilmu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.tianlin.xyz/Article/details/gtjwomtfzu.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shanyushiyangtech.top/Article/details/gtkitaibmy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.fzhhl.top/Article/details/gtgsjhgspw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jyoumei.cn/Article/details/gtbywupwfc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.ivvv.top/Article/details/gtrykntysn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.shuidangran.top/Article/details/gttwuerlvp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xziqi.cn/Article/details/gtqjiwbvyo.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.havefunace.top/Article/details/gtklsifdam.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.bjfxy.top/Article/details/gtpjhpmxei.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yueranfly.top/Article/details/gtdnxshyay.html

【文件统计】
来源：http://dali.cdnleiting.top/Article/details/gtgsqpmiyn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jqgfzy.top/Article/details/gtzwbdxetj.html

--------------------------------------------------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gthpslqrzd.html

目  录
来源：http://dali.zhoulong.xyz/Article/details/gtxhdiqjkt.html

--------------------------------------------------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gtrnrhryve.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.0kj1m.cn/Article/details/gtrgubbwmr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hnqzz.top/Article/details/gtiksqlysw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hammf.cn/Article/details/gtfzzcpzxs.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hnxiangtu.top/Article/details/gtkzvowjhq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhengqikj.top/Article/details/gtrnniwtny.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.gotoacloud.top/Article/details/gtnijppskf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.pycfn.com/Article/details/gtzziweomq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.iojbl.cn/Article/details/gtbvqrlyrj.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.birdmap.top/Article/details/gtlwghftqk.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hysaishi.cn/Article/details/gtlpxvweym.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ydzc1.top/Article/details/gtjideflcc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gtcpbtmyvz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.0kj1m.cn/Article/details/gttfdtfwrj.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.tanke756.top/Article/details/gtdaxxidsb.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.aibaodan.cn/Article/details/gtwajtfndh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.shzxlz.cn/Article/details/gttrbvuszp.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozhowajm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yongpay.top/Article/details/gtbqbabmib.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtugupvdgy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pengpengdd.cyou/Article/details/gtggnkucnf.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhongyouzk.top/Article/details/gtvnzoknri.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtytzssbbi.html

A. 基础语法与类型
来源：http://dali.jlsjyb.cn/Article/details/gtfntbtvlj.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxynoefqk.html

[A01] Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtjleztmin.html

Py:   print("Hello, World!")
来源：http://dali.c1oappe.top/Article/details/gtoffqhvjr.html

PHP:  echo "Hello, World!";
来源：http://dali.yonumen.top/Article/details/gtdkryqwah.html

JS:   console.log("Hello, World!");
来源：http://dali.hnxiangtu.top/Article/details/gtifbvhhxt.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.0kj1m.cn/Article/details/gtdahxwqzm.html

Java: System.out.println("Hello, World!");
来源：http://dali.316326.xyz/Article/details/gtwnlpipnx.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yvedp.cn/Article/details/gtffernkld.html

Ruby: puts "Hello, World!"
来源：http://dali.quarkkingdee.top/Article/details/gtowxejpjz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.sxryk.cn/Article/details/gtbvmaynoq.html

[A02] 变量声明与赋值
来源：http://dali.vqdsnc.cn/Article/details/gtwkbcvwfq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yuanzhike.top/Article/details/gtkdvmtagb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yuxming.cn/Article/details/gtcqrmvglb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.nanxinkj.top/Article/details/gtqxyppjbf.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yuanzhike.top/Article/details/gtlidpzxav.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xuetiantiany.cn/Article/details/gtnmrikwid.html

Go:   name := "Alex"; age := 20
来源：http://dali.0kj1m.cn/Article/details/gttdbklixa.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yj202588.top/Article/details/gtvuyueihi.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.dashuyun.cn/Article/details/gtxvmrochv.html

[A03] 常量定义
来源：http://dali.tian-w.cn/Article/details/gthelzttpo.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hysaishi.cn/Article/details/gtfvfnlqhk.html

PHP:  const PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtncenavee.html

JS:   const PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gtaokghkmy.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtnusbjmvr.html

Java: static final double PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtnzldsxqj.html

Go:   const PI = 3.14159
来源：http://dali.dashuyun.cn/Article/details/gtkoblmdmg.html

Ruby: PI = 3.14159
来源：http://dali.yuxming.cn/Article/details/gtlanlzbdm.html

C#:   const double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtacshebui.html

[A04] 判断变量类型
来源：http://dali.fzhhl.top/Article/details/gtcymxvcmc.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.tian-w.cn/Article/details/gtfcaahija.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyfjvtjoc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.kuanghao11.cn/Article/details/gtnegqhtql.html

TS:   typeof x; x instanceof Date
来源：http://dali.yuxming.cn/Article/details/gtcachwfgm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jqgfzy.top/Article/details/gthcalfpak.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.vqdsnc.cn/Article/details/gtavemdkml.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.cdnleiting.top/Article/details/gtecvmkavs.html

C#:   x.GetType().Name; x is int
来源：http://dali.ppjwa.cn/Article/details/gtpqfqmlks.html

[A05] 整数除法与取模
来源：http://dali.xinyue.icu/Article/details/gtqvsjmumv.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.pengpengdd.cyou/Article/details/gthpkscjya.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gtfynzqqlk.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hammf.cn/Article/details/gtupglidwe.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfkmmgor.html

Java: 7 / 2; 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtvqjlvcrq.html

Go:   7 / 2; 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gtyxwopezr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gtnvpihocs.html

C#:   7 / 2; 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxusytkbo.html

[A06] 字符串转数字
来源：http://dali.sufxvd.cn/Article/details/gttguzmyme.html

Py:   int("42"); float("3.14")
来源：http://dali.gzhubu.top/Article/details/gtxtkcblfs.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.redwolf501.top/Article/details/gtstgyllcf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hysaishi.cn/Article/details/gtxfozhugd.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hammf.cn/Article/details/gtbdodsojh.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.gogol.net.cn/Article/details/gtklehoban.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhixingplan.top/Article/details/gtugktolvd.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.ybcxt.top/Article/details/gtxvdmmylx.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.sysykeji.top/Article/details/gttevchldp.html

[A07] 数字转字符串
来源：http://dali.ybcxt.top/Article/details/gtmsaesaal.html

Py:   str(42)
来源：http://dali.cqqwz.cn/Article/details/gtfqlritna.html

PHP:  (string) 42; strval(42)
来源：http://dali.zdqjudy.top/Article/details/gtczexojfh.html

JS:   String(42); (42).toString()
来源：http://dali.jianghu66.top/Article/details/gtewgwwfas.html

TS:   String(42)
来源：http://dali.jyoumei.cn/Article/details/gtbzzxfqjk.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.havefunace.top/Article/details/gtureommkh.html

Go:   strconv.Itoa(42)
来源：http://dali.chenlongwang.top/Article/details/gtuxvgmhgy.html

Ruby: 42.to_s
来源：http://dali.quarkkingdee.top/Article/details/gtekugfkkd.html

C#:   42.ToString()
来源：http://dali.hongshengwenyu.top/Article/details/gthvxjnxac.html

[A08] 取整与四舍五入
来源：http://dali.zdqjudy.top/Article/details/gtgnvrdhsq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gtgmjixiwa.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jinqigfzy.top/Article/details/gtizjxmfps.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.hnqzz.top/Article/details/gtgqyemkuj.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.wangshuangyany.cn/Article/details/gtbkzohzvr.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.chenjidiqi.icu/Article/details/gtizzexpbf.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jinqigufen.top/Article/details/gtkacqwjrk.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.hongshengwenyu.top/Article/details/gtmlqwpuvd.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.xuetiantiany.cn/Article/details/gtbnjtdjmd.html

[A09] 绝对值与最大最小值
来源：http://dali.chenjidiqi.icu/Article/details/gttwoemhrs.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.havefunace.top/Article/details/gtbgpcwgkj.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtilcclttf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.cashguo.top/Article/details/gtprvvwyjq.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttiojmdiz.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.andypj.xyz/Article/details/gthkzjqrag.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.aibaodan.cn/Article/details/gtjmuzksro.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhoulong.xyz/Article/details/gtjyesskfy.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.sweek.top/Article/details/gtzeegjsvc.html

[A10] 生成随机数
来源：http://dali.ybcxt.top/Article/details/gtoovrcesm.html

Py:   import random; random.randint(1, 100)
来源：http://dali.9152youxi.cn/Article/details/gtxzqwbrpz.html

PHP:  random_int(1, 100);
来源：http://dali.feifeiyinyue.top/Article/details/gtwulzwgue.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhongyouzk.top/Article/details/gtffaohgnd.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yj20258.top/Article/details/gtgegwbfrp.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhixingplan.top/Article/details/gtjpufrggl.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.tianlin.xyz/Article/details/gteabtfvsr.html

Ruby: rand(1..100)
来源：http://dali.dianchejie.cn/Article/details/gtokwqlute.html

C#:   new Random().Next(1, 101)
来源：http://dali.hysaishi.cn/Article/details/gthcpnlwvn.html

[A11] 条件表达式（三元）
来源：http://dali.shuidangran.top/Article/details/gtrwqbtsbg.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.birdmap.top/Article/details/gtwkuwpual.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsyrsbof.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gttsiacqoo.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.cheryme.top/Article/details/gtwgvafzeo.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.guannengcc.top/Article/details/gtcckihcqa.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.ppjwa.cn/Article/details/gtvomfrwqn.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhixingplan.top/Article/details/gtpqbjhhsm.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jianghu66.top/Article/details/gtxjxtuyjp.html

[A12] 字符串插值 / 格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoseeznpb.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.hysaishi.cn/Article/details/gtnhxpsjwq.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.smart0.xyz/Article/details/gtdinymxim.html

JS:   `Hello, ${name}!`
来源：http://dali.gaohongyu789.top/Article/details/gtdpdsnxne.html

TS:   `Hello, ${name}!`
来源：http://dali.tian-w.cn/Article/details/gtijnusbrm.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yuanzhike.top/Article/details/gtqclajjvp.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.aizwys.cn/Article/details/gtmeukaukk.html

Ruby: "Hello, #{name}!"
来源：http://dali.jinqigufen.top/Article/details/gtkswvlfsu.html

C#:   $"Hello, {name}!"
来源：http://dali.sweek.top/Article/details/gtyzhlxpbf.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yuanzhike.top/Article/details/gtqavpoobf.html

Py:   "第一行\n第二行"
来源：http://dali.jqgufenzy.top/Article/details/gtkxxlltgt.html

PHP:  "第一行\n第二行"
来源：http://dali.zhongyouzk.top/Article/details/gtevujarvm.html

JS:   "第一行\n第二行"
来源：http://dali.zhengqikj.top/Article/details/gtenyfzusq.html

TS:   "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gtydmlsnue.html

Java: "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gtjgpohhpa.html

Go:   "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gtbhjjigad.html

Ruby: "第一行\n第二行"
来源：http://dali.mhx1999.top/Article/details/gtmdeglwei.html

C#:   "第一行\n第二行"
来源：http://dali.jinqigfzy.top/Article/details/gtqegawzfu.html

[A14] 注释写法
来源：http://dali.daxiang520.top/Article/details/gtykiqayxq.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yuxming.cn/Article/details/gtwmxsdebh.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.daria6918.cn/Article/details/gtkaxwevmh.html

JS:   // 单行；/* 多行 */
来源：http://dali.chenzaomai.com/Article/details/gtrtljsnqe.html


<!-- 参考信息 -->