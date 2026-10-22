代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtudqfphfd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yj202588.top/Article/details/gtgfpacipz.html

[U92] JS：深拷贝
来源：http://dali.yj202588.top/Article/details/gtejijpvfi.html

structuredClone(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtavgiogdc.html

[U93] JS：模板字符串
来源：http://dali.9152youxi.cn/Article/details/gtaebryctl.html

`共 ${n} 条`
来源：http://dali.yueranfly.top/Article/details/gtfbjapjdx.html

[U94] JS：箭头函数
来源：http://dali.hnqzz.top/Article/details/gtmfaeiftj.html

const double = x => x * 2;
来源：http://dali.jqgufenzy.top/Article/details/gtiqrzupel.html

[U95] JS：Promise 包装
来源：http://dali.hammf.cn/Article/details/gtayjtepwc.html

new Promise((resolve, reject) => {})
来源：http://dali.cqqwz.cn/Article/details/gtglkaygmq.html

[U96] JS：async/await 与异常
来源：http://dali.cheryme.top/Article/details/gtbwmvfbab.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gtyxdnsvtd.html

[U97] JS：并发请求
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbvtincg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtxcmjomel.html

[U98] JS：fetch 带 JSON
来源：http://dali.guannengcc.top/Article/details/gtnrnhzykn.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqgddene.html

[U99] JS：事件监听
来源：http://dali.daria6918.cn/Article/details/gtxazfatga.html

el.addEventListener("click", e => {})
来源：http://dali.gotoacloud.top/Article/details/gtjlqjowhm.html

[U100] JS：DOM 查询
来源：http://dali.jyoumei.cn/Article/details/gtfuxxbcqp.html

document.querySelector(".item")
来源：http://dali.birdmap.top/Article/details/gtvjopiojs.html

[U101] JS：classList 操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzwuitjh.html

el.classList.toggle("active")
来源：http://dali.yj20258888.top/Article/details/gtpjmpoxxa.html

[U102] JS：本地存储
来源：http://dali.jqgfzy.top/Article/details/gthmzlcuvd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yj20258888.top/Article/details/gtnrfcapmw.html

[U103] JS：定时器
来源：http://dali.ydzc1.top/Article/details/gtgzorgcau.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cucudq.cn/Article/details/gtlzompsmb.html

[U104] JS：防抖
来源：http://dali.daria6918.cn/Article/details/gtkmladwpg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmgsghre.html

[U105] JS：节流
来源：http://dali.yvedp.cn/Article/details/gtnsxjkcvh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.guannengcc.top/Article/details/gtllrqgqgv.html

[U106] JS：日期格式化
来源：http://dali.ybcxt.top/Article/details/gtapcdjdrv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.redwolf501.top/Article/details/gtkbiyyjet.html

[U107] JS：数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gtpeuyyxkq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgjtophu.html

[U108] JS：随机整数
来源：http://dali.sufxvd.cn/Article/details/gtkllkflmu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepgiwpbc.html

[U109] JS：数组分组
来源：http://dali.hysaishi.cn/Article/details/gtpgrxnutj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shangyingyoupin.top/Article/details/gthliynmzx.html

[U110] JS：数组分块
来源：http://dali.yangfankeji.com/Article/details/gtzmhkoqnu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovppmryp.html

[U111] JS：对象转 Map
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdwdyxcv.html

new Map(Object.entries(obj))
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqnjafjt.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gtmmbbuvdv.html

"7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtmfygmigm.html

[U113] JS：正则替换全部
来源：http://dali.meibo888.top/Article/details/gtxdibfqqw.html

s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtepgskros.html

[U114] JS：JSON 深比较
来源：http://dali.jqgufenzy.top/Article/details/gtwohrmiox.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgzryrftw.html

[U115] JS：生成 UUID
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjrioahv.html

crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gtwtjjnapm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gtnofamtbu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.andypj.xyz/Article/details/gtarclptyv.html

[U117] JS：单元测试
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutqchqqr.html

npm i -D vitest;  npx vitest
来源：http://dali.gaohongyu789.top/Article/details/gtormajwje.html

[U118] JS：开发服务器
来源：http://dali.meibo888.top/Article/details/gthmeoxjba.html

npm i -D vite;  npx vite
来源：http://dali.cdnleiting.top/Article/details/gtdhgrilxg.html

[U119] JS：生产构建
来源：http://dali.dashuyun.cn/Article/details/gtlsoafyrh.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gtgxduijei.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.havefunace.top/Article/details/gtfhfrfmnx.html

import.meta.env.VITE_API_URL
来源：http://dali.ivvv.top/Article/details/gtltcyuluh.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtfhsiezqc.html

统计汇总
来源：http://dali.zhengqikj.top/Article/details/gtyuflgypx.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtnekrjiao.html

按语言统计（条）：
来源：http://dali.yuanzhike.top/Article/details/gtbipmukgb.html

Python ......... 252
来源：http://dali.hfpthk.cn/Article/details/gtchxnlvtq.html

PHP ............ 252
来源：http://dali.tianlin.xyz/Article/details/gtuxwtyzow.html

JavaScript ..... 252
来源：http://dali.meibo888.top/Article/details/gtooghuvqm.html

TypeScript ..... 212
来源：http://dali.hywenlv.cn/Article/details/gtsgaouvhb.html

Java ........... 212
来源：http://dali.dashuyun.cn/Article/details/gtcunhqhdp.html

Go ............. 212
来源：http://dali.chenlongwang.top/Article/details/gtihxznlzx.html

Ruby ........... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwsmsdtym.html

C# ............. 212
来源：http://dali.fengsongda.top/Article/details/gtvqawwxiw.html

C .............. 30
来源：http://dali.yj20258.top/Article/details/gtyqwhrdqe.html

C++ ............ 30
来源：http://dali.mhx1999.top/Article/details/gtgpxrdwor.html

SQL ............ 90
来源：http://dali.ybcxt.top/Article/details/gtfozgojns.html

Bash ........... 80
来源：http://dali.guowangkeji.top/Article/details/gtpsidrfln.html

Kotlin ......... 15
来源：http://dali.yvedp.cn/Article/details/gtzhykozuc.html

Swift .......... 15
来源：http://dali.cdnleiting.top/Article/details/gtqvncffyk.html

Lua ............ 10
来源：http://dali.xuanzx.com/Article/details/gtekbrrwdl.html

Perl ........... 10
来源：http://dali.316326.xyz/Article/details/gtfbjdsgpd.html

Scala .......... 10
来源：http://dali.jlsjyb.cn/Article/details/gtpkvamhvh.html

------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gtlzvkrukp.html

合计 ........... 2106 条
来源：http://dali.ppjwa.cn/Article/details/gtsosqbnfn.html

按章节统计：
来源：http://dali.yonumen.top/Article/details/gtxljeeryu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinghuilouyu.cn/Article/details/gthpmwpnoh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jqgufenzy.top/Article/details/gtzjstefyf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.mhx1999.top/Article/details/gtgtjjqkdc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.9152youxi.cn/Article/details/gtpgqdbcmn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.nwbrower.top/Article/details/gtchfrmdqw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jianghu66.top/Article/details/gtiqnlhvst.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ehwqpu.com/Article/details/gtedhsjbdu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nanxuanxn.top/Article/details/gtyelrjvxh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gtdqqzyfbc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.meibo888.top/Article/details/gtgphpihdy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gtfmvtfzwr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gtbgbdxuko.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gtsrgtgrwh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.guowangkeji.top/Article/details/gtzgrpmlku.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.gzhubu.top/Article/details/gtwhetdfvg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gtmwjjsmjt.html

Q SQL 专题                              90
来源：http://dali.ppjwa.cn/Article/details/gtgecyavlh.html

R Bash 专题                             80
来源：http://dali.xuanzx.com/Article/details/gtprixomzf.html

S C / C++ 专题                          60
来源：http://dali.0kj1m.cn/Article/details/gtzedqpmfs.html

T 其他语言补充                          60
来源：http://dali.chenjidiqi.icu/Article/details/gtopypilje.html

U 高频实用片段                         120
来源：http://dali.ybcxt.top/Article/details/gtnoxquudx.html

------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtwcbytefb.html

合计                                  2106 条
来源：http://dali.svipenyu.cn/Article/details/gtnsqqlibu.html

--------------------------------------------------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gtmrxzwxpg.html

使用提醒
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmymainty.html

--------------------------------------------------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gttithbfcl.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.tian-w.cn/Article/details/gthypwadrx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gtklnkvlcx.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zycfv.cn/Article/details/gtuxowestw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yueranfly.top/Article/details/gtcfijbxhd.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ivvv.top/Article/details/gtwvkrkxxn.html

—— 文件结束 ——
来源：http://dali.ehwqpu.com/Article/details/gtxzsyepyd.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtvkvcvwuj.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.tianlin.xyz/Article/details/gtxsuybaep.html

Common Programming Examples Cheat Book
来源：http://dali.tanke756.top/Article/details/gtbrjgyoth.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtsliegovp.html

【收录内容】
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktidhjxc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jinghuilouyu.cn/Article/details/gtiibifdnk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.9152youxi.cn/Article/details/gtonfuekrd.html

SQL · Bash · C · C++
来源：http://dali.yanxiufei.cn/Article/details/gtklbqcvdi.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxtxclhi.html

【使用说明】
来源：http://dali.sufxvd.cn/Article/details/gtpwwlbqbf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.chenlongwang.top/Article/details/gtcuucwapq.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.dianchejie.cn/Article/details/gtqrwvlndj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.tianlin.xyz/Article/details/gtosyzumve.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.iojbl.cn/Article/details/gtisucigiy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ivvv.top/Article/details/gtatqktirh.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.guannengcc.top/Article/details/gttgerrmwk.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hnxiangtu.top/Article/details/gtrcnibwki.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhengqikj.top/Article/details/gttbmeahtk.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ybcxt.top/Article/details/gtbchvewrz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zdqjudy.top/Article/details/gtrbiewtkx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.shangyingyoupin.top/Article/details/gtuoqpzegk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cdnleiting.top/Article/details/gtqbyxbghn.html

【文件统计】
来源：http://dali.cqqwz.cn/Article/details/gtzgaxvqjl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.cheryme.top/Article/details/gtkgbvmtga.html

--------------------------------------------------------------------------------
来源：http://dali.meibo888.top/Article/details/gtbvfbnwzw.html

目  录
来源：http://dali.0kj1m.cn/Article/details/gteiwrjqbf.html

--------------------------------------------------------------------------------
来源：http://dali.iojbl.cn/Article/details/gthiwvfipw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.tian-w.cn/Article/details/gtrxwxsikt.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ehwqpu.com/Article/details/gttdnlkpig.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtppvlgqwe.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.cashguo.top/Article/details/gtgarwsjtu.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.birdmap.top/Article/details/gtbknhkpfz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jqgufenzy.top/Article/details/gtconwibag.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yj20258.top/Article/details/gtqzbbamtk.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jianghu66.top/Article/details/gtrgzdkdsg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ydzc1.top/Article/details/gtwjhsveim.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.chenlongwang.top/Article/details/gtkcmxzzbd.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.dianchejie.cn/Article/details/gtdipwwghu.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.mhx1999.top/Article/details/gtwvzzexzv.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.fzhhl.top/Article/details/gtshmxzckq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtgelhpnmz.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sufxvd.cn/Article/details/gttjcaayxk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gthfxisdqg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.316326.xyz/Article/details/gtkesrgncj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.wangdashe.top/Article/details/gtzfhcjiwa.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jqgfzy.top/Article/details/gtvmyonany.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhongyouzk.top/Article/details/gtemgyzpac.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jyoumei.cn/Article/details/gttvjcvmba.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtfiwyfjrr.html

A. 基础语法与类型
来源：http://dali.feifeiyinyue.top/Article/details/gtjtdaapah.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gttkkimxtc.html

[A01] Hello World
来源：http://dali.zdqjudy.top/Article/details/gtsqkldevv.html

Py:   print("Hello, World!")
来源：http://dali.chenjidiqi.icu/Article/details/gtbdmtaqeo.html

PHP:  echo "Hello, World!";
来源：http://dali.jyoumei.cn/Article/details/gtpvugkmxk.html

JS:   console.log("Hello, World!");
来源：http://dali.havefunace.top/Article/details/gtztgtaowc.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhengqikj.top/Article/details/gtawrplcwe.html

Java: System.out.println("Hello, World!");
来源：http://dali.birdmap.top/Article/details/gtprhzncyn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yj20258888.top/Article/details/gtubhmcywq.html

Ruby: puts "Hello, World!"
来源：http://dali.pycfn.com/Article/details/gtdibgwmyj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ppjwa.cn/Article/details/gtbcujvyth.html

[A02] 变量声明与赋值
来源：http://dali.bjfxy.top/Article/details/gtbwlmdxlf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yongpay.top/Article/details/gtrxawavax.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.sxryk.cn/Article/details/gtmzewrpcs.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xinyue.icu/Article/details/gtjrpljjia.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gtalfjjmen.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zycfv.cn/Article/details/gtlnhgnots.html

Go:   name := "Alex"; age := 20
来源：http://dali.hnxiangtu.top/Article/details/gtonkovvtb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.dianchejie.cn/Article/details/gtrxwrifzt.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yueranfly.top/Article/details/gtdhvenvps.html

[A03] 常量定义
来源：http://dali.jyoumei.cn/Article/details/gttvoxsaxp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.feifeiyinyue.top/Article/details/gtuffaskav.html

PHP:  const PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtxqcfmgra.html

JS:   const PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtqewcrmhz.html

TS:   const PI: number = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtphisydmy.html

Java: static final double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtvdqiyanb.html

Go:   const PI = 3.14159
来源：http://dali.gogol.net.cn/Article/details/gtdihfniql.html

Ruby: PI = 3.14159
来源：http://dali.cheryme.top/Article/details/gtborlvbco.html

C#:   const double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtfoffzfko.html

[A04] 判断变量类型
来源：http://dali.svipenyu.cn/Article/details/gtrdssoufu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.smart0.xyz/Article/details/gtunezkovv.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.dashuyun.cn/Article/details/gtfanvtmmw.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jlsjyb.cn/Article/details/gtlmbqzers.html

TS:   typeof x; x instanceof Date
来源：http://dali.kuanghao11.cn/Article/details/gtvdpxongm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxvvayzl.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.guowangkeji.top/Article/details/gtwgkaizii.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yvedp.cn/Article/details/gtxhrbmxzq.html

C#:   x.GetType().Name; x is int
来源：http://dali.ydzc1.top/Article/details/gtquzgpxor.html

[A05] 整数除法与取模
来源：http://dali.bjfxy.top/Article/details/gtcyniagmn.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.dashuyun.cn/Article/details/gtvneykaoy.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xziqi.cn/Article/details/gtlifbgztj.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.birdmap.top/Article/details/gteviwhuqv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtoatcwtnh.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gtmuqyumcm.html

Go:   7 / 2; 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gtmivurmub.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gttahbfigg.html

C#:   7 / 2; 7 % 2
来源：http://dali.cashguo.top/Article/details/gtberictmy.html

[A06] 字符串转数字
来源：http://dali.yangfankeji.com/Article/details/gttpuyighe.html

Py:   int("42"); float("3.14")
来源：http://dali.hammf.cn/Article/details/gtcllwuaij.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yj202588.top/Article/details/gtnizwkxfh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.daria6918.cn/Article/details/gtgspmdmcu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.chenzaomai.com/Article/details/gteidiolot.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.fengsongda.top/Article/details/gthcxhgwco.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jqgufenzy.top/Article/details/gtnzpuafkc.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gtlmckswiq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.sweek.top/Article/details/gtuadocybv.html

[A07] 数字转字符串
来源：http://dali.hywenlv.cn/Article/details/gteognrdoc.html

Py:   str(42)
来源：http://dali.cashguo.top/Article/details/gtytfnlkov.html

PHP:  (string) 42; strval(42)
来源：http://dali.sufxvd.cn/Article/details/gttotpvntg.html

JS:   String(42); (42).toString()
来源：http://dali.xinyue.icu/Article/details/gtkodemigt.html

TS:   String(42)
来源：http://dali.cheryme.top/Article/details/gtvrexmotp.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjccwbvo.html

Go:   strconv.Itoa(42)
来源：http://dali.nanxuanxn.top/Article/details/gtivyolbdk.html

Ruby: 42.to_s
来源：http://dali.yonumen.top/Article/details/gtykykwtgt.html

C#:   42.ToString()
来源：http://dali.ehwqpu.com/Article/details/gtvdadwutu.html

[A08] 取整与四舍五入
来源：http://dali.wangdashe.top/Article/details/gtxnuokonf.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.cashguo.top/Article/details/gtgfngrodh.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.cucudq.cn/Article/details/gtupfizoig.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yvedp.cn/Article/details/gtghdgxdlo.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.mhx1999.top/Article/details/gttbcgnqrj.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hnxiangtu.top/Article/details/gtleefppez.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jlsjyb.cn/Article/details/gtycmtebhu.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.tian-w.cn/Article/details/gtjgmbudgj.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.tian-w.cn/Article/details/gtjodcemwn.html

[A09] 绝对值与最大最小值
来源：http://dali.sysykeji.top/Article/details/gtmpgoktid.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.316326.xyz/Article/details/gtwwfzerah.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtoxzpiqre.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gttmrmguql.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gtsjeqdtkj.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gthbbarnmz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gtzszbtbxq.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.haohaochexian.top/Article/details/gttgsnvnef.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtgdramwxz.html

[A10] 生成随机数
来源：http://dali.daxiang520.top/Article/details/gtettrckfx.html

Py:   import random; random.randint(1, 100)
来源：http://dali.dashuyun.cn/Article/details/gtiherdhzj.html

PHP:  random_int(1, 100);
来源：http://dali.iojbl.cn/Article/details/gtlwyfmuwy.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zycfv.cn/Article/details/gtlhvsvrnx.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hnqzz.top/Article/details/gtowyhumxn.html

Java: new Random().nextInt(100) + 1
来源：http://dali.ydzc1.top/Article/details/gtftueucua.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jqgufenzy.top/Article/details/gtghjyihax.html

Ruby: rand(1..100)
来源：http://dali.feifeiyinyue.top/Article/details/gtrxsiasvi.html

C#:   new Random().Next(1, 101)
来源：http://dali.wangshuangyany.cn/Article/details/gtkylpwhvj.html

[A11] 条件表达式（三元）
来源：http://dali.ehwqpu.com/Article/details/gtnvjqhfbq.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.cucudq.cn/Article/details/gtimwiqmss.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.cheryme.top/Article/details/gtdazqptau.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.redwolf501.top/Article/details/gtbsdsoxxl.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jqgufenzy.top/Article/details/gtihcywjqa.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.chenjidiqi.icu/Article/details/gtiwtihqir.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqqcygfs.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhoulong.xyz/Article/details/gtshccmjvd.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.mhx1999.top/Article/details/gtonwrxhoy.html

[A12] 字符串插值 / 格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtwawnnexb.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.aizwys.cn/Article/details/gttxizpysa.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.nwbrower.top/Article/details/gtuuptiwlt.html

JS:   `Hello, ${name}!`
来源：http://dali.gogol.net.cn/Article/details/gtapntjlfw.html

TS:   `Hello, ${name}!`
来源：http://dali.pengpengdd.cyou/Article/details/gtaftiakmp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xinyue.icu/Article/details/gtvmmmdsfo.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.hysaishi.cn/Article/details/gtuxzjyorz.html

Ruby: "Hello, #{name}!"
来源：http://dali.yonumen.top/Article/details/gtzzawvwyl.html

C#:   $"Hello, {name}!"
来源：http://dali.redwolf501.top/Article/details/gtwrqhaavy.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.guowangkeji.top/Article/details/gtllblaxtz.html

Py:   "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gtwfgxiuxb.html

PHP:  "第一行\n第二行"
来源：http://dali.yuanzhike.top/Article/details/gthhmfiego.html

JS:   "第一行\n第二行"
来源：http://dali.xinyue.icu/Article/details/gthzthohxs.html

TS:   "第一行\n第二行"
来源：http://dali.hammf.cn/Article/details/gtrxwtwrjr.html

Java: "第一行\n第二行"
来源：http://dali.shuidangran.top/Article/details/gtreceeyeh.html

Go:   "第一行\n第二行"
来源：http://dali.shzxlz.cn/Article/details/gtnhxbhevb.html

Ruby: "第一行\n第二行"
来源：http://dali.yuanzhike.top/Article/details/gthxxbrjak.html

C#:   "第一行\n第二行"
来源：http://dali.shzxlz.cn/Article/details/gttkdvbzez.html

[A14] 注释写法
来源：http://dali.andypj.xyz/Article/details/gtylzilgfm.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.pengpengdd.cyou/Article/details/gtozxibiej.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.316326.xyz/Article/details/gtkznqrmaf.html

JS:   // 单行；/* 多行 */
来源：http://dali.haohaochexian.top/Article/details/gtaejwzbpy.html

TS:   // 单行；/* 多行 */
来源：http://dali.andypj.xyz/Article/details/gtjrppwcyc.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.cqqwz.cn/Article/details/gtososkjic.html

Go:   // 单行；/* 多行 */
来源：http://dali.wangshuangyany.cn/Article/details/gtxzxwhqqy.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yuanzhike.top/Article/details/gtyxorzdpy.html

C#:   // 单行；/* 多行 */
来源：http://dali.jqgufenzy.top/Article/details/gtbuoodysq.html

[A15] 空值判断与默认值
来源：http://dali.zhixingplan.top/Article/details/gtredgrosk.html

Py:   value = data or "默认值"
来源：http://dali.quarkkingdee.top/Article/details/gtbmomxkda.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.aizwys.cn/Article/details/gtevelfxab.html

JS:   const value = data ?? "默认值";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnylakyqo.html

TS:   const value = data ?? "默认值";
来源：http://dali.jinqigfzy.top/Article/details/gtfzckmfie.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.shzxlz.cn/Article/details/gtvvaacqkv.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zycfv.cn/Article/details/gtetxvfkpb.html


<!-- 参考信息 -->