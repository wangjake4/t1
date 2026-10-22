代发 wailian999

[U85] JS：可选链
来源：http://dali.jqgufenzy.top/Article/details/gt2pnlimtsx.html

a?.b?.c
来源：http://dali.haohaochexian.top/Article/details/gt2rwkeupbk.html

[U86] JS：空值合并
来源：http://dali.ehwqpu.com/Article/details/gt2tdmpggod.html

a ?? b
来源：http://dali.sysykeji.top/Article/details/gt2dndwaxvt.html

[U87] JS：解构默认值
来源：http://dali.shuidangran.top/Article/details/gt2rurdffji.html

const { a = 1, b = 2 } = obj;
来源：http://dali.meibo888.top/Article/details/gt2bbqfoytl.html

[U88] JS：对象展开合并
来源：http://dali.birdmap.top/Article/details/gt2pnheeqla.html

{ ...a, ...b }
来源：http://dali.jqgfzy.top/Article/details/gt2rftnaosc.html

[U89] JS：数组去重
来源：http://dali.guannengcc.top/Article/details/gt2nrbzjosv.html

[...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gt2otrafpcf.html

[U90] JS：数字数组排序
来源：http://dali.guowangkeji.top/Article/details/gt2tjadvwwd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gt2xhlyvlyv.html

[U91] JS：对象键值遍历
来源：http://dali.xylfe.cn/Article/details/gt2elkridgk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mlkxtyvu.html

[U92] JS：深拷贝
来源：http://dali.nanxuanxn.top/Article/details/gt2pzccgwmx.html

structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2bmloqjul.html

[U93] JS：模板字符串
来源：http://dali.havefunace.top/Article/details/gt2vjnljlpd.html

`共 ${n} 条`
来源：http://dali.9152youxi.cn/Article/details/gt2cuslpini.html

[U94] JS：箭头函数
来源：http://dali.haohaochexian.top/Article/details/gt2ybgxgnlq.html

const double = x => x * 2;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dqsioonc.html

[U95] JS：Promise 包装
来源：http://dali.cucudq.cn/Article/details/gt2oucysgdk.html

new Promise((resolve, reject) => {})
来源：http://dali.xuanzx.com/Article/details/gt2zrrtmlew.html

[U96] JS：async/await 与异常
来源：http://dali.jiagoushi.top/Article/details/gt2yodrnkcm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gt2yybtkajo.html

[U97] JS：并发请求
来源：http://dali.shangyingyoupin.top/Article/details/gt2oaosdtjh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vdqeihyv.html

[U98] JS：fetch 带 JSON
来源：http://dali.gzhubu.top/Article/details/gt2yemkbyfr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ipckoanj.html

[U99] JS：事件监听
来源：http://dali.tianlin.xyz/Article/details/gt2fiomktkd.html

el.addEventListener("click", e => {})
来源：http://dali.chenlongwang.top/Article/details/gt2syblxiig.html

[U100] JS：DOM 查询
来源：http://dali.jyoumei.cn/Article/details/gt2njifhbii.html

document.querySelector(".item")
来源：http://dali.hysaishi.cn/Article/details/gt2xtfbozhg.html

[U101] JS：classList 操作
来源：http://dali.jinqigfzy.top/Article/details/gt2vmdrtmmk.html

el.classList.toggle("active")
来源：http://dali.cheryme.top/Article/details/gt2qbvpdulb.html

[U102] JS：本地存储
来源：http://dali.daria6918.cn/Article/details/gt2ristxxns.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.cashguo.top/Article/details/gt2zqehoynp.html

[U103] JS：定时器
来源：http://dali.zhixingplan.top/Article/details/gt2kekzlzdv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.chenjidiqi.icu/Article/details/gt2iysbeouj.html

[U104] JS：防抖
来源：http://dali.aibaodan.cn/Article/details/gt2oxksgpmm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cqvzkure.html

[U105] JS：节流
来源：http://dali.c1oappe.top/Article/details/gt2arvjktpo.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.wangdashe.top/Article/details/gt2qrbthknw.html

[U106] JS：日期格式化
来源：http://dali.yj20258.top/Article/details/gt2gdcmdzpo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.quarkkingdee.top/Article/details/gt2xykmjhfl.html

[U107] JS：数字千分位
来源：http://dali.yj20258.top/Article/details/gt2vsyednve.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yangfankeji.com/Article/details/gt2fyvxzarm.html

[U108] JS：随机整数
来源：http://dali.yj20258.top/Article/details/gt2hhckdlov.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ehwqpu.com/Article/details/gt2xxthieuu.html

[U109] JS：数组分组
来源：http://dali.sufxvd.cn/Article/details/gt2lhmxoepz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uhhbncgh.html

[U110] JS：数组分块
来源：http://dali.jinqigfzy.top/Article/details/gt2kiftsows.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ppjwa.cn/Article/details/gt2pnxbnqeu.html

[U111] JS：对象转 Map
来源：http://dali.shanyushiyangtech.top/Article/details/gt2icucdnwd.html

new Map(Object.entries(obj))
来源：http://dali.quarkkingdee.top/Article/details/gt2stmaxdwi.html

[U112] JS：字符串补位
来源：http://dali.zhoulong.xyz/Article/details/gt2jdraguuq.html

"7".padStart(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gt2bokxwiut.html

[U113] JS：正则替换全部
来源：http://dali.c1oappe.top/Article/details/gt2fdiwminz.html

s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2jzvdxjtr.html

[U114] JS：JSON 深比较
来源：http://dali.sxryk.cn/Article/details/gt2hpsoewyb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2rdpsqifp.html

[U115] JS：生成 UUID
来源：http://dali.ydzc1.top/Article/details/gt2ledelowz.html

crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gt2dldyyqie.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.iojbl.cn/Article/details/gt2vktmjxhs.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jianghu66.top/Article/details/gt2pblsyrjp.html

[U117] JS：单元测试
来源：http://dali.pycfn.com/Article/details/gt2jiwqyhkv.html

npm i -D vitest;  npx vitest
来源：http://dali.wangshuangyany.cn/Article/details/gt2zhcywucs.html

[U118] JS：开发服务器
来源：http://dali.tianlin.xyz/Article/details/gt2nmwsibni.html

npm i -D vite;  npx vite
来源：http://dali.daria6918.cn/Article/details/gt2rpogqisv.html

[U119] JS：生产构建
来源：http://dali.shzxlz.cn/Article/details/gt2vkquwift.html

npx vite build
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2amfbuezx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebevjjpj.html

import.meta.env.VITE_API_URL
来源：http://dali.xinyue.icu/Article/details/gt2ybczoowq.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2ypmpuvcd.html

统计汇总
来源：http://dali.guannengcc.top/Article/details/gt2rrtnwgbw.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2kydaniac.html

按语言统计（条）：
来源：http://dali.tianlin.xyz/Article/details/gt2hpkgxpnj.html

Python ......... 252
来源：http://dali.sysykeji.top/Article/details/gt2kktjocmc.html

PHP ............ 252
来源：http://dali.sysykeji.top/Article/details/gt2hjvdjwdx.html

JavaScript ..... 252
来源：http://dali.nwbrower.top/Article/details/gt2ipnffdff.html

TypeScript ..... 212
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2esqptayt.html

Java ........... 212
来源：http://dali.hysaishi.cn/Article/details/gt2ielocpfq.html

Go ............. 212
来源：http://dali.ehwqpu.com/Article/details/gt2gqpvhxln.html

Ruby ........... 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xkrkswpd.html

C# ............. 212
来源：http://dali.jlsjyb.cn/Article/details/gt2tkxchbtc.html

C .............. 30
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gwbxkgxz.html

C++ ............ 30
来源：http://dali.pengpengdd.cyou/Article/details/gt2hhdmgxng.html

SQL ............ 90
来源：http://dali.nwbrower.top/Article/details/gt2hbawrkxl.html

Bash ........... 80
来源：http://dali.vqdsnc.cn/Article/details/gt2odugehit.html

Kotlin ......... 15
来源：http://dali.jinqigfzy.top/Article/details/gt2suodzsws.html

Swift .......... 15
来源：http://dali.jyoumei.cn/Article/details/gt2jsypokol.html

Lua ............ 10
来源：http://dali.jinqigufen.top/Article/details/gt2axgwwrhl.html

Perl ........... 10
来源：http://dali.guannengcc.top/Article/details/gt2mtzhgray.html

Scala .......... 10
来源：http://dali.daxiang520.top/Article/details/gt2phpwjrtq.html

------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gt2qcaxdavz.html

合计 ........... 2106 条
来源：http://dali.jyoumei.cn/Article/details/gt2xvaalvyo.html

按章节统计：
来源：http://dali.feifeiyinyue.top/Article/details/gt2qsveligx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shangyingyoupin.top/Article/details/gt2mfwxvdix.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.snrcjt.cn/Article/details/gt2sdtethat.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gt2xcrobfpl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.smart0.xyz/Article/details/gt2kmzemsur.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.bjfxy.top/Article/details/gt2moexcque.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.chenjidiqi.icu/Article/details/gt2zkwmpukt.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.snrcjt.cn/Article/details/gt2yaatpiaq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qskdknzc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zycfv.cn/Article/details/gt2ucmevgbp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.bjfxy.top/Article/details/gt2jytbrklq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gt2isavuebi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gt2djnpokzg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gt2gupkpgae.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jqgufenzy.top/Article/details/gt2wmzrhecb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zdqjudy.top/Article/details/gt2ryhngrlh.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gt2yxcnkspm.html

Q SQL 专题                              90
来源：http://dali.tianlin.xyz/Article/details/gt2eclafcpg.html

R Bash 专题                             80
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vovdzsam.html

S C / C++ 专题                          60
来源：http://dali.fengsongda.top/Article/details/gt2xvupyftq.html

T 其他语言补充                          60
来源：http://dali.xuetiantiany.cn/Article/details/gt2kgugctyr.html

U 高频实用片段                         120
来源：http://dali.svipenyu.cn/Article/details/gt2bzmaxvfq.html

------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xddkzmtl.html

合计                                  2106 条
来源：http://dali.dashuyun.cn/Article/details/gt2xwjpqcjb.html

--------------------------------------------------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gt2ueyyklhn.html

使用提醒
来源：http://dali.c1oappe.top/Article/details/gt2eyhdgeta.html

--------------------------------------------------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gt2ngjdhsja.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fugzogkj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.gaohongyu789.top/Article/details/gt2ybvyxixx.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.mhx1999.top/Article/details/gt2cbmvgcfx.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zycfv.cn/Article/details/gt2mdaonkaq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.chenlongwang.top/Article/details/gt2owvwxqwa.html

—— 文件结束 ——
来源：http://dali.tianlin.xyz/Article/details/gt2dujpkcui.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2qwoibwpr.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.c1oappe.top/Article/details/gt2uwigrbfl.html

Common Programming Examples Cheat Book
来源：http://dali.ydzc1.top/Article/details/gt2ltwdtfvk.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2rhuzjhnd.html

【收录内容】
来源：http://dali.jqgufenzy.top/Article/details/gt2hycltjdt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.c1oappe.top/Article/details/gt2edjfhaps.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hipvzhaw.html

SQL · Bash · C · C++
来源：http://dali.andypj.xyz/Article/details/gt2yjscjitc.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yuanzhike.top/Article/details/gt2xpenjbgt.html

【使用说明】
来源：http://dali.daxiang520.top/Article/details/gt2fevyqwck.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wrntnvou.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xuetiantiany.cn/Article/details/gt2mtjvvtrq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.haohaochexian.top/Article/details/gt2gxufgoaf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.guannengcc.top/Article/details/gt2wlglhmlq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jiagoushi.top/Article/details/gt2atszonsa.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.pycfn.com/Article/details/gt2wsyaawsi.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hammf.cn/Article/details/gt2inulxmaq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cashguo.top/Article/details/gt2kgzjrltp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hammf.cn/Article/details/gt2zsenylhb.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhongyouzk.top/Article/details/gt2itjxkeuh.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hammf.cn/Article/details/gt2notatfct.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.daria6918.cn/Article/details/gt2jkddkvad.html

【文件统计】
来源：http://dali.daxiang520.top/Article/details/gt2jqsbhgnz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.nanxinkj.top/Article/details/gt2oljgjcqv.html

--------------------------------------------------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gt2wrdwzzaq.html

目  录
来源：http://dali.snrcjt.cn/Article/details/gt2eralnpok.html

--------------------------------------------------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gt2bkfvbaar.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2btvhrigo.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ehwqpu.com/Article/details/gt2itwioevt.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.redwolf501.top/Article/details/gt2eeumymst.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hyeibhmg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhixingplan.top/Article/details/gt2nexjpunw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gzizzbdm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.gogol.net.cn/Article/details/gt2nmrskwis.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yueranfly.top/Article/details/gt2fbjckmqa.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yvedp.cn/Article/details/gt2samxwnkz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.guannengcc.top/Article/details/gt2hxhzlrlu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2wvloavqf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2tdyufjfg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2znsrvvyt.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.ivvv.top/Article/details/gt2zpshmlmm.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.daria6918.cn/Article/details/gt2gsnmpysf.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.ivvv.top/Article/details/gt2laxkiipa.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.pycfn.com/Article/details/gt2nhlwwwbg.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.redwolf501.top/Article/details/gt2yysdxacm.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.0kj1m.cn/Article/details/gt2ijvkepyz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gt2mcywocfe.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sufxvd.cn/Article/details/gt2ygvkeckf.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2vqabgide.html

A. 基础语法与类型
来源：http://dali.yanxiufei.cn/Article/details/gt2ngrygyhk.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2xvdphakj.html

[A01] Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2psrzglsw.html

Py:   print("Hello, World!")
来源：http://dali.tian-w.cn/Article/details/gt2cwgumwdr.html

PHP:  echo "Hello, World!";
来源：http://dali.fengsongda.top/Article/details/gt2wnokhurh.html

JS:   console.log("Hello, World!");
来源：http://dali.yuanzhike.top/Article/details/gt2qgyzvtaz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.chenzaomai.com/Article/details/gt2tqlfsvvn.html

Java: System.out.println("Hello, World!");
来源：http://dali.guannengcc.top/Article/details/gt2wjklfdpj.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sweek.top/Article/details/gt2ydgcwdbl.html

Ruby: puts "Hello, World!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2grnmdzuh.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.chenlongwang.top/Article/details/gt2rkvhfaso.html

[A02] 变量声明与赋值
来源：http://dali.cheryme.top/Article/details/gt2vlntdnqh.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wejdjvwr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yonumen.top/Article/details/gt2hobzszbz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yvedp.cn/Article/details/gt2kejdsrhm.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zycfv.cn/Article/details/gt2qylkswfz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.chenzaomai.com/Article/details/gt2aocbjdjr.html

Go:   name := "Alex"; age := 20
来源：http://dali.chenzaomai.com/Article/details/gt2zgnkrrwd.html

Ruby: name = "Alex"; age = 20
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2urrahxkr.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.aibaodan.cn/Article/details/gt2lisdatpn.html

[A03] 常量定义
来源：http://dali.chenzaomai.com/Article/details/gt2qdngbcou.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhixingplan.top/Article/details/gt2ynvnahzw.html

PHP:  const PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gt2lvwniqky.html

JS:   const PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gt2sowxwjfq.html

TS:   const PI: number = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gt2uqzdbnvn.html

Java: static final double PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gt2zftqavhq.html

Go:   const PI = 3.14159
来源：http://dali.cheryme.top/Article/details/gt2kxczlnzv.html

Ruby: PI = 3.14159
来源：http://dali.chenjidiqi.icu/Article/details/gt2aldndwhj.html

C#:   const double PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gt2pylpnyfu.html

[A04] 判断变量类型
来源：http://dali.tianlin.xyz/Article/details/gt2eyvgcnhu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.fzhhl.top/Article/details/gt2zronkjan.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.xziqi.cn/Article/details/gt2dpuvbbop.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jianghu66.top/Article/details/gt2dqjtmclm.html

TS:   typeof x; x instanceof Date
来源：http://dali.ppjwa.cn/Article/details/gt2nabagcki.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.mhx1999.top/Article/details/gt2nhoajedg.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jyoumei.cn/Article/details/gt2wmlrwwbh.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.hfpthk.cn/Article/details/gt2yzpstdgu.html

C#:   x.GetType().Name; x is int
来源：http://dali.xylfe.cn/Article/details/gt2tffmpwfc.html

[A05] 整数除法与取模
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ddmfcfso.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.sweek.top/Article/details/gt2rgurhdvf.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.birdmap.top/Article/details/gt2bbyfxjuf.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gt2rvwqdcgs.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xziqi.cn/Article/details/gt2hbnydkrz.html

Java: 7 / 2; 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gt2vlwxrtic.html

Go:   7 / 2; 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fzfbmnxq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gt2baznmgxm.html

C#:   7 / 2; 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gt2aiwurwee.html

[A06] 字符串转数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2spjotcrc.html

Py:   int("42"); float("3.14")
来源：http://dali.xinyue.icu/Article/details/gt2ntzlublq.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fcwtsqxy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.sufxvd.cn/Article/details/gt2zaopqzvu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lnoayqku.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yangfankeji.com/Article/details/gt2tsxvaudk.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.svipenyu.cn/Article/details/gt2leuqaejz.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.tanke756.top/Article/details/gt2fhaptjat.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.daria6918.cn/Article/details/gt2crikusce.html

[A07] 数字转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kzmzhcow.html

Py:   str(42)
来源：http://dali.hnqzz.top/Article/details/gt2yjezonfb.html

PHP:  (string) 42; strval(42)
来源：http://dali.yvedp.cn/Article/details/gt2udnvhlut.html

JS:   String(42); (42).toString()
来源：http://dali.ivvv.top/Article/details/gt2csnjansl.html

TS:   String(42)
来源：http://dali.nanxuanxn.top/Article/details/gt2oquhhtcd.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.hnxiangtu.top/Article/details/gt2gtqckqpg.html

Go:   strconv.Itoa(42)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2crwckeha.html

Ruby: 42.to_s
来源：http://dali.hammf.cn/Article/details/gt2dqgpufkf.html

C#:   42.ToString()
来源：http://dali.ydzc1.top/Article/details/gt2fcpunnxg.html

[A08] 取整与四舍五入
来源：http://dali.birdmap.top/Article/details/gt2qyovijib.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhengqikj.top/Article/details/gt2uxektpuu.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2uapmpequ.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.ppjwa.cn/Article/details/gt2zitaucfy.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.guannengcc.top/Article/details/gt2jqypygus.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gt2ksavspwj.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.nanxinkj.top/Article/details/gt2jencbvcr.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yanxiufei.cn/Article/details/gt2fwsvqsfn.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jiuxqlfb.html

[A09] 绝对值与最大最小值
来源：http://dali.vqdsnc.cn/Article/details/gt2ctmtobfl.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gt2tgajswew.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2pmvkqdvy.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2ipzyjaxt.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2fqgmfawh.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jqgfzy.top/Article/details/gt2lnpsdsrv.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jianghu66.top/Article/details/gt2kwsuxelq.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.nanxinkj.top/Article/details/gt2rpfxkrlc.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bdjevfnu.html

[A10] 生成随机数
来源：http://dali.guowangkeji.top/Article/details/gt2ahdiewsj.html

Py:   import random; random.randint(1, 100)
来源：http://dali.iojbl.cn/Article/details/gt2jyspkirp.html

PHP:  random_int(1, 100);
来源：http://dali.aibaodan.cn/Article/details/gt2zzpakihh.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.nwbrower.top/Article/details/gt2quqvynxa.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.gzhubu.top/Article/details/gt2ffbjzqht.html

Java: new Random().nextInt(100) + 1
来源：http://dali.snrcjt.cn/Article/details/gt2jinzxqig.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zdqjudy.top/Article/details/gt2ccihnyxd.html

Ruby: rand(1..100)
来源：http://dali.yonumen.top/Article/details/gt2pjnkcjjd.html

C#:   new Random().Next(1, 101)
来源：http://dali.xylfe.cn/Article/details/gt2afainwed.html

[A11] 条件表达式（三元）
来源：http://dali.vqdsnc.cn/Article/details/gt2rrfjdqvh.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.xylfe.cn/Article/details/gt2pitkjnwb.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2chocbosb.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.tian-w.cn/Article/details/gt2gjqsmbbd.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.pycfn.com/Article/details/gt2negczlfu.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.sweek.top/Article/details/gt2iuipyfoz.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.gzhubu.top/Article/details/gt2tjhayozm.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.mhx1999.top/Article/details/gt2upcjjscq.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.kuanghao11.cn/Article/details/gt2imgmpuxc.html

[A12] 字符串插值 / 格式化
来源：http://dali.feifeiyinyue.top/Article/details/gt2egvvzjac.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.quarkkingdee.top/Article/details/gt2txgihzsz.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jiagoushi.top/Article/details/gt2lszvqdis.html

JS:   `Hello, ${name}!`
来源：http://dali.pycfn.com/Article/details/gt2fzqefxbw.html

TS:   `Hello, ${name}!`
来源：http://dali.yongpay.top/Article/details/gt2strvatpn.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.chenzaomai.com/Article/details/gt2jdssptqh.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.cheryme.top/Article/details/gt2hjvkmrau.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhengqikj.top/Article/details/gt2btghfxsu.html

C#:   $"Hello, {name}!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2imedhugv.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.jiagoushi.top/Article/details/gt2jhprfujc.html

Py:   "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gt2iqiomlhe.html

PHP:  "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gt2kkryhowb.html

JS:   "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gt2jylvbdog.html

TS:   "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gt2efhdhxth.html

Java: "第一行\n第二行"
来源：http://dali.meibo888.top/Article/details/gt2tgncpsvu.html

Go:   "第一行\n第二行"
来源：http://dali.tianlin.xyz/Article/details/gt2oubwkojt.html

Ruby: "第一行\n第二行"
来源：http://dali.shangyingyoupin.top/Article/details/gt2uhcbgdmq.html

C#:   "第一行\n第二行"
来源：http://dali.chenlongwang.top/Article/details/gt2nfmulepa.html

[A14] 注释写法
来源：http://dali.xziqi.cn/Article/details/gt2lndnhite.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.smart0.xyz/Article/details/gt2lpcyfqei.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.birdmap.top/Article/details/gt2otspadxu.html

JS:   // 单行；/* 多行 */
来源：http://dali.andypj.xyz/Article/details/gt2rmnngoby.html


<!-- 参考信息 -->