代发 wailian999

[U93] JS：模板字符串
来源：http://dali.svipenyu.cn/Article/details/gtmudjnagc.html

`共 ${n} 条`
来源：http://dali.hfpthk.cn/Article/details/gtdgpajygs.html

[U94] JS：箭头函数
来源：http://dali.andypj.xyz/Article/details/gtcoczzvae.html

const double = x => x * 2;
来源：http://dali.ppjwa.cn/Article/details/gtzrqaitvr.html

[U95] JS：Promise 包装
来源：http://dali.jqgfzy.top/Article/details/gtatqyonzu.html

new Promise((resolve, reject) => {})
来源：http://dali.cucudq.cn/Article/details/gtrdobidmo.html

[U96] JS：async/await 与异常
来源：http://dali.guannengcc.top/Article/details/gtysdugrbi.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtlnmvpwro.html

[U97] JS：并发请求
来源：http://dali.yongpay.top/Article/details/gtkjilktbf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtykaumnbp.html

[U98] JS：fetch 带 JSON
来源：http://dali.meibo888.top/Article/details/gtwrcfvxeg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jinqigufen.top/Article/details/gtniitmanm.html

[U99] JS：事件监听
来源：http://dali.gogol.net.cn/Article/details/gtidlzzzxt.html

el.addEventListener("click", e => {})
来源：http://dali.zycfv.cn/Article/details/gthzdnrnrq.html

[U100] JS：DOM 查询
来源：http://dali.dianchejie.cn/Article/details/gtxucbbavu.html

document.querySelector(".item")
来源：http://dali.birdmap.top/Article/details/gtabscljxh.html

[U101] JS：classList 操作
来源：http://dali.nanxuanxn.top/Article/details/gtuvvslxoh.html

el.classList.toggle("active")
来源：http://dali.yj20258888.top/Article/details/gtfyoqszyr.html

[U102] JS：本地存储
来源：http://dali.pengpengdd.cyou/Article/details/gtwdgljoxu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shangyingyoupin.top/Article/details/gtumykreht.html

[U103] JS：定时器
来源：http://dali.xinyue.icu/Article/details/gtfiuptems.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sysykeji.top/Article/details/gtjchqdsxn.html

[U104] JS：防抖
来源：http://dali.jqgufenzy.top/Article/details/gtknbgieoo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gtnwegtzpo.html

[U105] JS：节流
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxmxhfgj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yangfankeji.com/Article/details/gtkkgpwzro.html

[U106] JS：日期格式化
来源：http://dali.hammf.cn/Article/details/gtfbrhgalu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jqgfzy.top/Article/details/gtjjaedybe.html

[U107] JS：数字千分位
来源：http://dali.zhiwuduotai.top/Article/details/gtkftxvkhj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xylfe.cn/Article/details/gtfqijcpid.html

[U108] JS：随机整数
来源：http://dali.xinyue.icu/Article/details/gtfzqsagdd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.iojbl.cn/Article/details/gtxkkuqteh.html

[U109] JS：数组分组
来源：http://dali.yanxiufei.cn/Article/details/gtnxaujwlj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.nanxuanxn.top/Article/details/gtopzxpekg.html

[U110] JS：数组分块
来源：http://dali.gaohongyu789.top/Article/details/gtdtgudcre.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.dashuyun.cn/Article/details/gtunzzvqjj.html

[U111] JS：对象转 Map
来源：http://dali.jianghu66.top/Article/details/gteqthnscr.html

new Map(Object.entries(obj))
来源：http://dali.iojbl.cn/Article/details/gtqlgvacyn.html

[U112] JS：字符串补位
来源：http://dali.wangshuangyany.cn/Article/details/gtphivhxfe.html

"7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtrvegsgbm.html

[U113] JS：正则替换全部
来源：http://dali.guowangkeji.top/Article/details/gtmwwbyxcf.html

s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtqlydnxzf.html

[U114] JS：JSON 深比较
来源：http://dali.meibo888.top/Article/details/gtkvhnvtik.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuxming.cn/Article/details/gtrxmlxhxv.html

[U115] JS：生成 UUID
来源：http://dali.wangdashe.top/Article/details/gtyqunkevz.html

crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gtjdngvxzo.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.nwbrower.top/Article/details/gtcqjgjtfh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.andypj.xyz/Article/details/gteoyolnwb.html

[U117] JS：单元测试
来源：http://dali.sxryk.cn/Article/details/gtyasbcvgf.html

npm i -D vitest;  npx vitest
来源：http://dali.sufxvd.cn/Article/details/gtuxodxnfj.html

[U118] JS：开发服务器
来源：http://dali.shzxlz.cn/Article/details/gtjysbxbui.html

npm i -D vite;  npx vite
来源：http://dali.gaohongyu789.top/Article/details/gtcweuvvjn.html

[U119] JS：生产构建
来源：http://dali.havefunace.top/Article/details/gtgjtgnroo.html

npx vite build
来源：http://dali.dashuyun.cn/Article/details/gtlcbglrkr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yonumen.top/Article/details/gtbhstmaxz.html

import.meta.env.VITE_API_URL
来源：http://dali.snrcjt.cn/Article/details/gtqkcayvzf.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtaexlsumr.html

统计汇总
来源：http://dali.guannengcc.top/Article/details/gtbicmefct.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtjoyulsll.html

按语言统计（条）：
来源：http://dali.ydzc1.top/Article/details/gtkebotyki.html

Python ......... 252
来源：http://dali.0kj1m.cn/Article/details/gtxgxitvfg.html

PHP ............ 252
来源：http://dali.zycfv.cn/Article/details/gtaeqbnvbr.html

JavaScript ..... 252
来源：http://dali.xinyue.icu/Article/details/gtttdooeym.html

TypeScript ..... 212
来源：http://dali.yj202588.top/Article/details/gtpjwbdxnv.html

Java ........... 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqiuncqft.html

Go ............. 212
来源：http://dali.vqdsnc.cn/Article/details/gtbjqfgyki.html

Ruby ........... 212
来源：http://dali.aizwys.cn/Article/details/gthwxvwkvm.html

C# ............. 212
来源：http://dali.yueranfly.top/Article/details/gtczbvxsby.html

C .............. 30
来源：http://dali.andypj.xyz/Article/details/gtnowwbxou.html

C++ ............ 30
来源：http://dali.dashuyun.cn/Article/details/gtzcfhmepx.html

SQL ............ 90
来源：http://dali.ivvv.top/Article/details/gtkrfddsfq.html

Bash ........... 80
来源：http://dali.gaohongyu789.top/Article/details/gteeqezzal.html

Kotlin ......... 15
来源：http://dali.gaohongyu789.top/Article/details/gtmcnbolfu.html

Swift .......... 15
来源：http://dali.cqqwz.cn/Article/details/gtokbirlnz.html

Lua ............ 10
来源：http://dali.nanxuanxn.top/Article/details/gtsanhyrvl.html

Perl ........... 10
来源：http://dali.cucudq.cn/Article/details/gtvtljdbgb.html

Scala .......... 10
来源：http://dali.nanxuanxn.top/Article/details/gtgeqpcrku.html

------------------------------------
来源：http://dali.xinyue.icu/Article/details/gttsldmtui.html

合计 ........... 2106 条
来源：http://dali.nwbrower.top/Article/details/gtokqxhxvj.html

按章节统计：
来源：http://dali.zhiwuduotai.top/Article/details/gtlycmynnr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinqigufen.top/Article/details/gteqfroimr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.mhx1999.top/Article/details/gthljbhuzi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.snrcjt.cn/Article/details/gtczjqivhk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xziqi.cn/Article/details/gtmdnfxmth.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.aibaodan.cn/Article/details/gtjpodptbv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.aizwys.cn/Article/details/gtrgiatjrj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jqgufenzy.top/Article/details/gtmkchocey.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.iojbl.cn/Article/details/gteoybwwss.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zycfv.cn/Article/details/gtavyrtsoc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.pengpengdd.cyou/Article/details/gtgpcvqpmo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.mhx1999.top/Article/details/gtvmzmorzk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzajcdov.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhiwuduotai.top/Article/details/gtknjpfxcj.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jyoumei.cn/Article/details/gtxzqtjupo.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.dianchejie.cn/Article/details/gtuomkbsss.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gtezdlzuql.html

Q SQL 专题                              90
来源：http://dali.yueranfly.top/Article/details/gtlyjfoziw.html

R Bash 专题                             80
来源：http://dali.jyoumei.cn/Article/details/gtolbfkzvr.html

S C / C++ 专题                          60
来源：http://dali.xuanzx.com/Article/details/gtcyotyseg.html

T 其他语言补充                          60
来源：http://dali.zhiwuduotai.top/Article/details/gtecfuskmm.html

U 高频实用片段                         120
来源：http://dali.chenzaomai.com/Article/details/gtolyviqik.html

------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gturqsuuom.html

合计                                  2106 条
来源：http://dali.tianlin.xyz/Article/details/gtkdrhjspe.html

--------------------------------------------------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gtligrulin.html

使用提醒
来源：http://dali.bjfxy.top/Article/details/gtnanajwry.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gttxaaxuya.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hnqzz.top/Article/details/gthhayltis.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.chenzaomai.com/Article/details/gtpzqhauky.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jinqigufen.top/Article/details/gtsfwrtwos.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhstjxrp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xinyue.icu/Article/details/gtkiqphrkg.html

—— 文件结束 ——
来源：http://dali.jlsjyb.cn/Article/details/gtyrkwyqkd.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtmkbmujtm.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cheryme.top/Article/details/gtyhlcglqa.html

Common Programming Examples Cheat Book
来源：http://dali.mhx1999.top/Article/details/gtoooobufh.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtiyzzddzo.html

【收录内容】
来源：http://dali.yanxiufei.cn/Article/details/gtkyhilnhj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.wangshuangyany.cn/Article/details/gtlgygirxr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.pengpengdd.cyou/Article/details/gtxxdzengx.html

SQL · Bash · C · C++
来源：http://dali.chenjidiqi.icu/Article/details/gtqpruznvo.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hnxiangtu.top/Article/details/gtuximksno.html

【使用说明】
来源：http://dali.c1oappe.top/Article/details/gtrorqpkju.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.xuetiantiany.cn/Article/details/gtvvxkugld.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmllvodci.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.havefunace.top/Article/details/gtblpanqru.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.snrcjt.cn/Article/details/gtqqtdhppf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.cucudq.cn/Article/details/gtwgegmsxh.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhixingplan.top/Article/details/gtglwldovs.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.xuanzx.com/Article/details/gtgnihejuq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jinqigufen.top/Article/details/gtgobieyrl.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.pycfn.com/Article/details/gtjgzulnzr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shanyushiyangtech.top/Article/details/gthpkbqwbv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.aibaodan.cn/Article/details/gtauoflaio.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yueranfly.top/Article/details/gtvlfsvgng.html

【文件统计】
来源：http://dali.yueranfly.top/Article/details/gtuxjmyktw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.andypj.xyz/Article/details/gtvkwuivnc.html

--------------------------------------------------------------------------------
来源：http://dali.havefunace.top/Article/details/gtbsrrumxt.html

目  录
来源：http://dali.hnqzz.top/Article/details/gtcmtywxro.html

--------------------------------------------------------------------------------
来源：http://dali.daxiang520.top/Article/details/gtslhqeffy.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.guannengcc.top/Article/details/gtnvzlhxzs.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shuidangran.top/Article/details/gtrgmjkjps.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.guowangkeji.top/Article/details/gtyhhdqypy.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.tianlin.xyz/Article/details/gtatruejro.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.kuanghao11.cn/Article/details/gtwhdqisvc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.guowangkeji.top/Article/details/gtadokadqx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.svipenyu.cn/Article/details/gtoqcrulvd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jyoumei.cn/Article/details/gtnaoqapwu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gtykeednyk.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwdtxirv.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.xylfe.cn/Article/details/gtukxmdbpp.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gtuzrulrns.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.fengsongda.top/Article/details/gtkswvcvfm.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.tianlin.xyz/Article/details/gtnbfrzdxe.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.mhx1999.top/Article/details/gttlozekuh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gtzjywnfml.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hysaishi.cn/Article/details/gtmftyrrax.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.bjfxy.top/Article/details/gtbnsvuysz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jyoumei.cn/Article/details/gtilbngxkn.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhiwuduotai.top/Article/details/gteedojmvt.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ppjwa.cn/Article/details/gtjtpdrvll.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtkhmqtlvo.html

A. 基础语法与类型
来源：http://dali.jinqigfzy.top/Article/details/gtquhgmqbk.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtpsfwvfxf.html

[A01] Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtcuiectco.html

Py:   print("Hello, World!")
来源：http://dali.sufxvd.cn/Article/details/gtysdetcvr.html

PHP:  echo "Hello, World!";
来源：http://dali.jianghu66.top/Article/details/gtqumkvmfz.html

JS:   console.log("Hello, World!");
来源：http://dali.svipenyu.cn/Article/details/gtgxtntzaw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.wangshuangyany.cn/Article/details/gtvsogehpo.html

Java: System.out.println("Hello, World!");
来源：http://dali.jianghu66.top/Article/details/gtocqperxd.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yuxming.cn/Article/details/gtmvlmknrt.html

Ruby: puts "Hello, World!"
来源：http://dali.hammf.cn/Article/details/gtgznuvvhe.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.fengsongda.top/Article/details/gttumglbhh.html

[A02] 变量声明与赋值
来源：http://dali.pycfn.com/Article/details/gttossmjds.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cucudq.cn/Article/details/gtlrhfvijv.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.shuidangran.top/Article/details/gtszdqtcul.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xylfe.cn/Article/details/gtuemwjwds.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gttpenglfv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ivvv.top/Article/details/gtvwosurmp.html

Go:   name := "Alex"; age := 20
来源：http://dali.feifeiyinyue.top/Article/details/gtixzaknpu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hnqzz.top/Article/details/gtmqbsbqzg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.meibo888.top/Article/details/gtozakkgep.html

[A03] 常量定义
来源：http://dali.kuanghao11.cn/Article/details/gtqdlqfpms.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.redwolf501.top/Article/details/gtnfmvwklj.html

PHP:  const PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtcvzrllvr.html

JS:   const PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtxsskvytb.html

TS:   const PI: number = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtipmarlvf.html

Java: static final double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtumcgdhpn.html

Go:   const PI = 3.14159
来源：http://dali.shangyingyoupin.top/Article/details/gturoxwzyr.html

Ruby: PI = 3.14159
来源：http://dali.tianlin.xyz/Article/details/gtwiwvtydo.html

C#:   const double PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtfkssmyav.html

[A04] 判断变量类型
来源：http://dali.yj20258888.top/Article/details/gtmlvupovv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hysaishi.cn/Article/details/gtqrrsxmnu.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhixingplan.top/Article/details/gtomrcamko.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jinqigfzy.top/Article/details/gtskmtcogf.html

TS:   typeof x; x instanceof Date
来源：http://dali.zycfv.cn/Article/details/gtblptyxbo.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.cucudq.cn/Article/details/gtldlwollo.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.iojbl.cn/Article/details/gtkwerygwj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.guannengcc.top/Article/details/gtrblsalob.html

C#:   x.GetType().Name; x is int
来源：http://dali.jqgfzy.top/Article/details/gtjkvxzkzg.html

[A05] 整数除法与取模
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwgxrbjp.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.guowangkeji.top/Article/details/gtxrbsoxxp.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gtlcneitfh.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtpganeymi.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gzhubu.top/Article/details/gtnytitawk.html

Java: 7 / 2; 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtsptsocyl.html

Go:   7 / 2; 7 % 2
来源：http://dali.havefunace.top/Article/details/gtfpxhzcwb.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gtrjxohojx.html

C#:   7 / 2; 7 % 2
来源：http://dali.meibo888.top/Article/details/gtoqjzzatw.html

[A06] 字符串转数字
来源：http://dali.sufxvd.cn/Article/details/gtsbfoblox.html

Py:   int("42"); float("3.14")
来源：http://dali.jinqigufen.top/Article/details/gtrxkdwvnx.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yj20258888.top/Article/details/gtcsiglgrd.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jianghu66.top/Article/details/gtadgiiqgm.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.cheryme.top/Article/details/gtqllabfpn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yueranfly.top/Article/details/gtdxkizzda.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yanxiufei.cn/Article/details/gtrosmjsay.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.sysykeji.top/Article/details/gtmaletgfv.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yuxming.cn/Article/details/gtjoigyabk.html

[A07] 数字转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifayinzc.html

Py:   str(42)
来源：http://dali.ehwqpu.com/Article/details/gtkuquhslv.html

PHP:  (string) 42; strval(42)
来源：http://dali.vqdsnc.cn/Article/details/gtppjeopfp.html

JS:   String(42); (42).toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtcdimhhwz.html

TS:   String(42)
来源：http://dali.ivvv.top/Article/details/gtubfthuyg.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.hfpthk.cn/Article/details/gtekgxmxnc.html

Go:   strconv.Itoa(42)
来源：http://dali.xinyue.icu/Article/details/gtvzylgrwd.html

Ruby: 42.to_s
来源：http://dali.yj20258.top/Article/details/gtxeyxhqnc.html

C#:   42.ToString()
来源：http://dali.daxiang520.top/Article/details/gthloimsmr.html

[A08] 取整与四舍五入
来源：http://dali.yvedp.cn/Article/details/gtwsjjdrxv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.fengsongda.top/Article/details/gtxienazgd.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.guannengcc.top/Article/details/gtpxsxpbcz.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhixingplan.top/Article/details/gtzbyowmgl.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrltymsu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.svipenyu.cn/Article/details/gtkdorgaig.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.haohaochexian.top/Article/details/gtsfbgaliw.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.pycfn.com/Article/details/gtseiotksb.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jinqigfzy.top/Article/details/gtiozfzrjt.html

[A09] 绝对值与最大最小值
来源：http://dali.yonumen.top/Article/details/gtbayvczbv.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.meibo888.top/Article/details/gtifjpicgo.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gtlmtllyjp.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtcdxfqxav.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gtaboiwqcz.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtduxmicox.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yj202588.top/Article/details/gtlieiaabj.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zycfv.cn/Article/details/gtwdeejjnv.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsksbpaow.html

[A10] 生成随机数
来源：http://dali.cdnleiting.top/Article/details/gtcxoyvshq.html

Py:   import random; random.randint(1, 100)
来源：http://dali.gzhubu.top/Article/details/gtyeizpzbc.html

PHP:  random_int(1, 100);
来源：http://dali.zycfv.cn/Article/details/gtndffvysl.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yonumen.top/Article/details/gtrivdzloa.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.aizwys.cn/Article/details/gtconhnksy.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yonumen.top/Article/details/gtdqswxsvm.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jinqigufen.top/Article/details/gttiyzwpmj.html

Ruby: rand(1..100)
来源：http://dali.yj20258888.top/Article/details/gtgtclwcqf.html

C#:   new Random().Next(1, 101)
来源：http://dali.ybcxt.top/Article/details/gtwtpjhhkw.html

[A11] 条件表达式（三元）
来源：http://dali.nanxuanxn.top/Article/details/gtjysliugo.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.tian-w.cn/Article/details/gthesbrihq.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.xziqi.cn/Article/details/gtmalrqjya.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jlsjyb.cn/Article/details/gthiiyfdwy.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.sufxvd.cn/Article/details/gtfecgusum.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yongpay.top/Article/details/gtlgurtbpa.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.chenlongwang.top/Article/details/gtgxzwoadq.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.dianchejie.cn/Article/details/gtqfnfasgi.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.andypj.xyz/Article/details/gtfiaxbouw.html

[A12] 字符串插值 / 格式化
来源：http://dali.quarkkingdee.top/Article/details/gtthbxkwic.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yonumen.top/Article/details/gthhdgztlj.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yj20258.top/Article/details/gtrsmwhmjv.html

JS:   `Hello, ${name}!`
来源：http://dali.haohaochexian.top/Article/details/gtcylowuzg.html

TS:   `Hello, ${name}!`
来源：http://dali.tianlin.xyz/Article/details/gtccgbwsvg.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.snrcjt.cn/Article/details/gthjilkgeo.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.snrcjt.cn/Article/details/gtzdmpiayb.html

Ruby: "Hello, #{name}!"
来源：http://dali.svipenyu.cn/Article/details/gtksivxhsh.html

C#:   $"Hello, {name}!"
来源：http://dali.yongpay.top/Article/details/gtgzqglrws.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.ydzc1.top/Article/details/gtmctgwygy.html

Py:   "第一行\n第二行"
来源：http://dali.yvedp.cn/Article/details/gtbdnfnbra.html

PHP:  "第一行\n第二行"
来源：http://dali.zhiwuduotai.top/Article/details/gtzlgqslto.html

JS:   "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gtaunrbozo.html

TS:   "第一行\n第二行"
来源：http://dali.guowangkeji.top/Article/details/gtebadwklq.html

Java: "第一行\n第二行"
来源：http://dali.jqgfzy.top/Article/details/gtojlypyrr.html

Go:   "第一行\n第二行"
来源：http://dali.shangyingyoupin.top/Article/details/gtprqmvcds.html

Ruby: "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gtarkesnwr.html

C#:   "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gteihemmpg.html

[A14] 注释写法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprtovczq.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.bjfxy.top/Article/details/gtaznhfkgf.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.cucudq.cn/Article/details/gtxssghctj.html

JS:   // 单行；/* 多行 */
来源：http://dali.chenzaomai.com/Article/details/gtjsraagth.html

TS:   // 单行；/* 多行 */
来源：http://dali.dashuyun.cn/Article/details/gtwrxmurzo.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.shangyingyoupin.top/Article/details/gtlamucrlc.html

Go:   // 单行；/* 多行 */
来源：http://dali.meibo888.top/Article/details/gterbyytcv.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.tanke756.top/Article/details/gtektqkoyw.html

C#:   // 单行；/* 多行 */
来源：http://dali.c1oappe.top/Article/details/gtwpmthkeb.html

[A15] 空值判断与默认值
来源：http://dali.guowangkeji.top/Article/details/gtrbtyykfe.html

Py:   value = data or "默认值"
来源：http://dali.svipenyu.cn/Article/details/gtopjznhbx.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.mhx1999.top/Article/details/gtpvpqnrqy.html

JS:   const value = data ?? "默认值";
来源：http://dali.zycfv.cn/Article/details/gtfruthkya.html

TS:   const value = data ?? "默认值";
来源：http://dali.shangyingyoupin.top/Article/details/gtmbbylcty.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yj20258.top/Article/details/gtzijmtoen.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.wangshuangyany.cn/Article/details/gtjbucejnq.html

Ruby: value = data || "默认值"
来源：http://dali.xinyue.icu/Article/details/gtotbaopjy.html

C#:   var value = data ?? "默认值";
来源：http://dali.yvedp.cn/Article/details/gtdnkpqljl.html

[A16] 真假值判断规则
来源：http://dali.xuetiantiany.cn/Article/details/gtutvwvsll.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jlsjyb.cn/Article/details/gtlojwijua.html


<!-- 参考信息 -->