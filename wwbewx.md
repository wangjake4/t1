代发 wailian999

[U89] JS：数组去重
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fqwbojlj.html

[...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gt2kwyjjmfr.html

[U90] JS：数字数组排序
来源：http://dali.hongshengwenyu.top/Article/details/gt2dabmrrxa.html

[...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gt2yhkwkxon.html

[U91] JS：对象键值遍历
来源：http://dali.yuanzhike.top/Article/details/gt2yqbbjhjv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.havefunace.top/Article/details/gt2cecjobtl.html

[U92] JS：深拷贝
来源：http://dali.zhengqikj.top/Article/details/gt2zcvckipe.html

structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gt2exavkmmc.html

[U93] JS：模板字符串
来源：http://dali.haohaochexian.top/Article/details/gt2bdbaasjy.html

`共 ${n} 条`
来源：http://dali.gzhubu.top/Article/details/gt2ftihyzaz.html

[U94] JS：箭头函数
来源：http://dali.meibo888.top/Article/details/gt2bcxpkpby.html

const double = x => x * 2;
来源：http://dali.yuxming.cn/Article/details/gt2trwyuvqr.html

[U95] JS：Promise 包装
来源：http://dali.snrcjt.cn/Article/details/gt2ufrfyktn.html

new Promise((resolve, reject) => {})
来源：http://dali.hywenlv.cn/Article/details/gt2ibartxta.html

[U96] JS：async/await 与异常
来源：http://dali.0kj1m.cn/Article/details/gt2wakrqzri.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gt2wvfkmbpv.html

[U97] JS：并发请求
来源：http://dali.fzhhl.top/Article/details/gt2gtcjtxkn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gt2rfokzwlr.html

[U98] JS：fetch 带 JSON
来源：http://dali.ydzc1.top/Article/details/gt2fwssdolr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zycfv.cn/Article/details/gt2ylysyezu.html

[U99] JS：事件监听
来源：http://dali.yongpay.top/Article/details/gt2ebhzicox.html

el.addEventListener("click", e => {})
来源：http://dali.aibaodan.cn/Article/details/gt2fuxyjidt.html

[U100] JS：DOM 查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2covqluma.html

document.querySelector(".item")
来源：http://dali.cashguo.top/Article/details/gt2jhtrpjue.html

[U101] JS：classList 操作
来源：http://dali.sweek.top/Article/details/gt2ctwawhkb.html

el.classList.toggle("active")
来源：http://dali.xinyue.icu/Article/details/gt2riqtwvpw.html

[U102] JS：本地存储
来源：http://dali.yj20258888.top/Article/details/gt2jslkdhuk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jianghu66.top/Article/details/gt2zpnekkgr.html

[U103] JS：定时器
来源：http://dali.sweek.top/Article/details/gt2sqnvvuot.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhongyouzk.top/Article/details/gt2mruxmwtn.html

[U104] JS：防抖
来源：http://dali.svipenyu.cn/Article/details/gt2ipeqzgjo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gt2wpqriqer.html

[U105] JS：节流
来源：http://dali.wangdashe.top/Article/details/gt2oqeslajn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.quarkkingdee.top/Article/details/gt2dhtmxmge.html

[U106] JS：日期格式化
来源：http://dali.zhoulong.xyz/Article/details/gt2bppkjaid.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cashguo.top/Article/details/gt2euexfpdy.html

[U107] JS：数字千分位
来源：http://dali.cdnleiting.top/Article/details/gt2ddlnhlaq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ppjwa.cn/Article/details/gt2xyjbcviw.html

[U108] JS：随机整数
来源：http://dali.shzxlz.cn/Article/details/gt2kfuogiyh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.nwbrower.top/Article/details/gt2oacrijbe.html

[U109] JS：数组分组
来源：http://dali.tian-w.cn/Article/details/gt2noxhtedf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.c1oappe.top/Article/details/gt2xcstmcco.html

[U110] JS：数组分块
来源：http://dali.jqgfzy.top/Article/details/gt2emkqlwfm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gzhubu.top/Article/details/gt2enooxctq.html

[U111] JS：对象转 Map
来源：http://dali.svipenyu.cn/Article/details/gt2wfsvdwih.html

new Map(Object.entries(obj))
来源：http://dali.yj202588.top/Article/details/gt2tjakexcp.html

[U112] JS：字符串补位
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cttbqnrr.html

"7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gt2kugndcqb.html

[U113] JS：正则替换全部
来源：http://dali.jyoumei.cn/Article/details/gt2tunyntan.html

s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gt2prohmmbm.html

[U114] JS：JSON 深比较
来源：http://dali.zhongyouzk.top/Article/details/gt2reluddel.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fzhhl.top/Article/details/gt2nndmqnyk.html

[U115] JS：生成 UUID
来源：http://dali.guannengcc.top/Article/details/gt2lftaqgym.html

crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gt2dqnctkcq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xuetiantiany.cn/Article/details/gt2unxyixgn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yonumen.top/Article/details/gt2fmwyyvhg.html

[U117] JS：单元测试
来源：http://dali.feifeiyinyue.top/Article/details/gt2vchpaczp.html

npm i -D vitest;  npx vitest
来源：http://dali.havefunace.top/Article/details/gt2knpjnpeu.html

[U118] JS：开发服务器
来源：http://dali.xuanzx.com/Article/details/gt2tctwlpib.html

npm i -D vite;  npx vite
来源：http://dali.shangyingyoupin.top/Article/details/gt2zqbioxeq.html

[U119] JS：生产构建
来源：http://dali.jianghu66.top/Article/details/gt2chuahrpb.html

npx vite build
来源：http://dali.nwbrower.top/Article/details/gt2prsqsiqw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ivvv.top/Article/details/gt2yuvsevhk.html

import.meta.env.VITE_API_URL
来源：http://dali.yonumen.top/Article/details/gt2scuawtqj.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2ilyyndhe.html

统计汇总
来源：http://dali.tanke756.top/Article/details/gt2qqudpmpf.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2nmtekuef.html

按语言统计（条）：
来源：http://dali.hysaishi.cn/Article/details/gt2jlwjqhsm.html

Python ......... 252
来源：http://dali.jinqigfzy.top/Article/details/gt2pnwsnqip.html

PHP ............ 252
来源：http://dali.svipenyu.cn/Article/details/gt2awybzuzp.html

JavaScript ..... 252
来源：http://dali.fzhhl.top/Article/details/gt2sqobcnsi.html

TypeScript ..... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ijbbqpvl.html

Java ........... 212
来源：http://dali.zdqjudy.top/Article/details/gt2lwaximyx.html

Go ............. 212
来源：http://dali.xylfe.cn/Article/details/gt2kuesvnqb.html

Ruby ........... 212
来源：http://dali.havefunace.top/Article/details/gt2cbbtwozs.html

C# ............. 212
来源：http://dali.ivvv.top/Article/details/gt2jkvihlvv.html

C .............. 30
来源：http://dali.yanxiufei.cn/Article/details/gt2zbxuyltb.html

C++ ............ 30
来源：http://dali.mhx1999.top/Article/details/gt2cahnpsnu.html

SQL ............ 90
来源：http://dali.aizwys.cn/Article/details/gt2ocpalxti.html

Bash ........... 80
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dewspckk.html

Kotlin ......... 15
来源：http://dali.zhengqikj.top/Article/details/gt2jywtzwnb.html

Swift .......... 15
来源：http://dali.daxiang520.top/Article/details/gt2lsysczax.html

Lua ............ 10
来源：http://dali.andypj.xyz/Article/details/gt2lizczjds.html

Perl ........... 10
来源：http://dali.ivvv.top/Article/details/gt2welbrvvz.html

Scala .......... 10
来源：http://dali.xylfe.cn/Article/details/gt2xytsdyrf.html

------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iqnqzlym.html

合计 ........... 2106 条
来源：http://dali.bjfxy.top/Article/details/gt2pzkdnrey.html

按章节统计：
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mlqrafya.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.pycfn.com/Article/details/gt2swsvpnhh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.0kj1m.cn/Article/details/gt2jbgquuli.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shzxlz.cn/Article/details/gt2kosdeilp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jinqigufen.top/Article/details/gt2jrkzbmdw.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.quarkkingdee.top/Article/details/gt2mmwmweko.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.daxiang520.top/Article/details/gt2qxexiqvm.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gogol.net.cn/Article/details/gt2xfsrncjn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ppjwa.cn/Article/details/gt2ucjxhnwq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.feifeiyinyue.top/Article/details/gt2gflwtysz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.pengpengdd.cyou/Article/details/gt2moyknlil.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gt2vpelzuqt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gt2jlfaslys.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gt2rdvogpcr.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.sxryk.cn/Article/details/gt2royptpvz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jqgufenzy.top/Article/details/gt2ctsxnino.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gt2wwognflr.html

Q SQL 专题                              90
来源：http://dali.aibaodan.cn/Article/details/gt2yyvljbme.html

R Bash 专题                             80
来源：http://dali.xuetiantiany.cn/Article/details/gt2dcspuskt.html

S C / C++ 专题                          60
来源：http://dali.yonumen.top/Article/details/gt2wuwsmbtu.html

T 其他语言补充                          60
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ktuppeua.html

U 高频实用片段                         120
来源：http://dali.birdmap.top/Article/details/gt2xexzdbgm.html

------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gt2byjyntzz.html

合计                                  2106 条
来源：http://dali.iojbl.cn/Article/details/gt2kyndcsyy.html

--------------------------------------------------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gt2vbammlur.html

使用提醒
来源：http://dali.hnqzz.top/Article/details/gt2ztjibgub.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gt2sttbccvt.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.smart0.xyz/Article/details/gt2niatffaw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.gogol.net.cn/Article/details/gt2bzkofkuj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hotbpwuo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.nanxinkj.top/Article/details/gt2dysyjjgs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cqqwz.cn/Article/details/gt2mnnqsjfw.html

—— 文件结束 ——
来源：http://dali.sxryk.cn/Article/details/gt2lezhqrop.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2oggdmpss.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cqqwz.cn/Article/details/gt2wtmhoojq.html

Common Programming Examples Cheat Book
来源：http://dali.jinqigfzy.top/Article/details/gt2phrflaqu.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2kcyjutgv.html

【收录内容】
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wjdkziha.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.gzhubu.top/Article/details/gt2exqpenna.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.feifeiyinyue.top/Article/details/gt2bndwwulm.html

SQL · Bash · C · C++
来源：http://dali.shangyingyoupin.top/Article/details/gt2iijildvm.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.dashuyun.cn/Article/details/gt2fcrkcscc.html

【使用说明】
来源：http://dali.cucudq.cn/Article/details/gt2ofdemgal.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.tian-w.cn/Article/details/gt2pyxngttb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.birdmap.top/Article/details/gt2npapaffq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.haohaochexian.top/Article/details/gt2zytryaqq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ivvv.top/Article/details/gt2mfbmtjvm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jlsjyb.cn/Article/details/gt2nkerxuls.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.nanxinkj.top/Article/details/gt2cjgwdchc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gaohongyu789.top/Article/details/gt2shiikrcy.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.tanke756.top/Article/details/gt2ylhavqnz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.gaohongyu789.top/Article/details/gt2mlmuzwec.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2epyhwqmz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.cheryme.top/Article/details/gt2mlpmlvqp.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hfpthk.cn/Article/details/gt2xlfswbmm.html

【文件统计】
来源：http://dali.shangyingyoupin.top/Article/details/gt2roshacog.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.smart0.xyz/Article/details/gt2xpafwxbj.html

--------------------------------------------------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gt2hhbejbyv.html

目  录
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mgwyptut.html

--------------------------------------------------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gt2kqvfpqnh.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.haohaochexian.top/Article/details/gt2ptlemcqr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.nanxinkj.top/Article/details/gt2kcyqzynj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.0kj1m.cn/Article/details/gt2hoeguxzo.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nfxelhre.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.havefunace.top/Article/details/gt2dltmtamd.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.snrcjt.cn/Article/details/gt2dlshqjek.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2aakkbmme.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2exzrrhop.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2nacnlaah.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2kakusykc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gt2jbiqkuyx.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gt2jkqhmwsp.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gt2mzymxnsz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hywenlv.cn/Article/details/gt2gikqiufr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xziqi.cn/Article/details/gt2vvhzljex.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhengqikj.top/Article/details/gt2towxmxmi.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cdnleiting.top/Article/details/gt2mwhbxtae.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.sufxvd.cn/Article/details/gt2qztzuqqo.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qhslkrzn.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ivvv.top/Article/details/gt2iccgjrto.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2rovhifwe.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2ljodqjfz.html

A. 基础语法与类型
来源：http://dali.quarkkingdee.top/Article/details/gt2cnzyvsxq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2qsoaevut.html

[A01] Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2lfigpbww.html

Py:   print("Hello, World!")
来源：http://dali.yj202588.top/Article/details/gt2rfpuezto.html

PHP:  echo "Hello, World!";
来源：http://dali.zhoulong.xyz/Article/details/gt2yfikvqge.html

JS:   console.log("Hello, World!");
来源：http://dali.ydzc1.top/Article/details/gt2itpnbdxl.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.0kj1m.cn/Article/details/gt2bpnitmcm.html

Java: System.out.println("Hello, World!");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wteiicmx.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sweek.top/Article/details/gt2wamwrfkv.html

Ruby: puts "Hello, World!"
来源：http://dali.chenjidiqi.icu/Article/details/gt2mkvrpqpu.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.gotoacloud.top/Article/details/gt2qygrxgpi.html

[A02] 变量声明与赋值
来源：http://dali.cqqwz.cn/Article/details/gt2bypdijgj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shangyingyoupin.top/Article/details/gt2erslrtmn.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.mhx1999.top/Article/details/gt2zrimlmtw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xylfe.cn/Article/details/gt2uvjttnzw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vyzztnla.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zdqjudy.top/Article/details/gt2jhbqtpgt.html

Go:   name := "Alex"; age := 20
来源：http://dali.mhx1999.top/Article/details/gt2zhijbahw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.dianchejie.cn/Article/details/gt2yojbfsrn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yanxiufei.cn/Article/details/gt2htitltha.html

[A03] 常量定义
来源：http://dali.sweek.top/Article/details/gt2fhfaphiv.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ybcxt.top/Article/details/gt2owktlidc.html

PHP:  const PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gt2robchvwf.html

JS:   const PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gt2eiblhbgm.html

TS:   const PI: number = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gt2wxbkethh.html

Java: static final double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gt2mmdojndo.html

Go:   const PI = 3.14159
来源：http://dali.jyoumei.cn/Article/details/gt2qsrhaqlj.html

Ruby: PI = 3.14159
来源：http://dali.jinqigfzy.top/Article/details/gt2drcwoqpa.html

C#:   const double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gt2tgjmcvrg.html

[A04] 判断变量类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2cloedtnr.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kwvtggwl.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.vqdsnc.cn/Article/details/gt2clznihxx.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.svipenyu.cn/Article/details/gt2ycstkgrl.html

TS:   typeof x; x instanceof Date
来源：http://dali.yueranfly.top/Article/details/gt2lusuixbd.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yangfankeji.com/Article/details/gt2nyoicdrv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.fzhhl.top/Article/details/gt2sjgkldbh.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xinyue.icu/Article/details/gt2fhphwwxf.html

C#:   x.GetType().Name; x is int
来源：http://dali.316326.xyz/Article/details/gt2fawrcevs.html

[A05] 整数除法与取模
来源：http://dali.zhiwuduotai.top/Article/details/gt2nkexpwdx.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yangfankeji.com/Article/details/gt2kibvxjny.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yj20258.top/Article/details/gt2xvvhneqr.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2lgbccnfn.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gt2tjtffnof.html

Java: 7 / 2; 7 % 2
来源：http://dali.wangdashe.top/Article/details/gt2tqlrminj.html

Go:   7 / 2; 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gt2ycslrlzf.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gt2sulmdajl.html

C#:   7 / 2; 7 % 2
来源：http://dali.cashguo.top/Article/details/gt2zkejrozg.html

[A06] 字符串转数字
来源：http://dali.cheryme.top/Article/details/gt2vobaluem.html

Py:   int("42"); float("3.14")
来源：http://dali.chenzaomai.com/Article/details/gt2cxcpmiso.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yueranfly.top/Article/details/gt2gokdskjp.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hywenlv.cn/Article/details/gt2jkolcybg.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.shzxlz.cn/Article/details/gt2asgcioio.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mazjawhd.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.redwolf501.top/Article/details/gt2lyyiugry.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.quarkkingdee.top/Article/details/gt2qmpqgced.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.wangshuangyany.cn/Article/details/gt2caiflhpe.html

[A07] 数字转字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2voacyqbm.html

Py:   str(42)
来源：http://dali.mhx1999.top/Article/details/gt2mfizcqei.html

PHP:  (string) 42; strval(42)
来源：http://dali.zdqjudy.top/Article/details/gt2kbunuozd.html

JS:   String(42); (42).toString()
来源：http://dali.tanke756.top/Article/details/gt2ybfbdtbu.html

TS:   String(42)
来源：http://dali.yj20258.top/Article/details/gt2sqnxlusl.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.gogol.net.cn/Article/details/gt2scgqzxse.html

Go:   strconv.Itoa(42)
来源：http://dali.tanke756.top/Article/details/gt2hwicuawp.html

Ruby: 42.to_s
来源：http://dali.hysaishi.cn/Article/details/gt2fwlxtuke.html

C#:   42.ToString()
来源：http://dali.sysykeji.top/Article/details/gt2ydrqigpw.html

[A08] 取整与四舍五入
来源：http://dali.yueranfly.top/Article/details/gt2eroyyrcs.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.sufxvd.cn/Article/details/gt2lugbfogn.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jiagoushi.top/Article/details/gt2tyownwxk.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.cheryme.top/Article/details/gt2jnmkleig.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jqgufenzy.top/Article/details/gt2ngzkebhf.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.tian-w.cn/Article/details/gt2qjuafjlt.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ypbcqhre.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.hywenlv.cn/Article/details/gt2yirqxsoh.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.tanke756.top/Article/details/gt2uzztzzjk.html

[A09] 绝对值与最大最小值
来源：http://dali.jqgufenzy.top/Article/details/gt2weqgsmmu.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yj20258888.top/Article/details/gt2fnmajhsb.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gt2yuqzpykg.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.ydzc1.top/Article/details/gt2vjkyhjtu.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gt2ckcmzhns.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.xziqi.cn/Article/details/gt2dpdjpeyr.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bwekdmws.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.sysykeji.top/Article/details/gt2hrkkkraz.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gt2gfkbagad.html

[A10] 生成随机数
来源：http://dali.9152youxi.cn/Article/details/gt2nnaebhmc.html

Py:   import random; random.randint(1, 100)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2njicspdo.html

PHP:  random_int(1, 100);
来源：http://dali.xinyue.icu/Article/details/gt2yxnqxtan.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2kesuibar.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xylfe.cn/Article/details/gt2tqddfbqp.html

Java: new Random().nextInt(100) + 1
来源：http://dali.cqqwz.cn/Article/details/gt2yjqvatxh.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.0kj1m.cn/Article/details/gt2klmrbbjq.html

Ruby: rand(1..100)
来源：http://dali.redwolf501.top/Article/details/gt2rgzjjnsr.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkibclk.html

[A11] 条件表达式（三元）
来源：http://dali.cqqwz.cn/Article/details/gt2lgwfelue.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.vqdsnc.cn/Article/details/gt2rukyspyg.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yj20258888.top/Article/details/gt2wnivoedq.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.nanxuanxn.top/Article/details/gt2fkhtlqgg.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.wangshuangyany.cn/Article/details/gt2ssyddycw.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zrskjxme.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jqgufenzy.top/Article/details/gt2vkmngxvh.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.meibo888.top/Article/details/gt2thpxnhrq.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.c1oappe.top/Article/details/gt2lagrsthi.html

[A12] 字符串插值 / 格式化
来源：http://dali.daria6918.cn/Article/details/gt2wimxdsru.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.shuidangran.top/Article/details/gt2uhklyulf.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zdqjudy.top/Article/details/gt2deactjba.html

JS:   `Hello, ${name}!`
来源：http://dali.zhiwuduotai.top/Article/details/gt2oeydjuqg.html

TS:   `Hello, ${name}!`
来源：http://dali.yanxiufei.cn/Article/details/gt2tfkiflnr.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bijyqhaa.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.xuanzx.com/Article/details/gt2dtqzzwpy.html

Ruby: "Hello, #{name}!"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rpzojcqr.html

C#:   $"Hello, {name}!"
来源：http://dali.meibo888.top/Article/details/gt2wgtevqgu.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yanxiufei.cn/Article/details/gt2psnkyvvf.html

Py:   "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gt2ctfivrjw.html

PHP:  "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gt2nmejkkql.html

JS:   "第一行\n第二行"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2taplyjzt.html

TS:   "第一行\n第二行"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ypufsmgr.html

Java: "第一行\n第二行"
来源：http://dali.dashuyun.cn/Article/details/gt2fehzzfrf.html

Go:   "第一行\n第二行"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2suvzjvvl.html

Ruby: "第一行\n第二行"
来源：http://dali.ehwqpu.com/Article/details/gt2madabhkt.html

C#:   "第一行\n第二行"
来源：http://dali.chenjidiqi.icu/Article/details/gt2asorxwjg.html

[A14] 注释写法
来源：http://dali.shuidangran.top/Article/details/gt2befozine.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.chenzaomai.com/Article/details/gt2qvclvmvh.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rpjmihre.html

JS:   // 单行；/* 多行 */
来源：http://dali.hfpthk.cn/Article/details/gt2khufztcr.html

TS:   // 单行；/* 多行 */
来源：http://dali.yanxiufei.cn/Article/details/gt2trhuiuwu.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.meibo888.top/Article/details/gt2gghnawgz.html

Go:   // 单行；/* 多行 */
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lcvcmghy.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hammf.cn/Article/details/gt2ngeseuma.html

C#:   // 单行；/* 多行 */
来源：http://dali.fengsongda.top/Article/details/gt2kyqywycv.html

[A15] 空值判断与默认值
来源：http://dali.chenlongwang.top/Article/details/gt2ewkkypml.html

Py:   value = data or "默认值"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ogwuzunq.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.hongshengwenyu.top/Article/details/gt2ivygcjnj.html


<!-- 参考信息 -->