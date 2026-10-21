代发 wailian999

[U87] JS：解构默认值
来源：http://dali.guowangkeji.top/Article/details/gtvexczrxd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.iojbl.cn/Article/details/gtmdokbrnw.html

[U88] JS：对象展开合并
来源：http://dali.jinqigufen.top/Article/details/gtaugxfnsg.html

{ ...a, ...b }
来源：http://dali.aibaodan.cn/Article/details/gtrlmlpasp.html

[U89] JS：数组去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtloeyayzk.html

[...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gtlfanvvla.html

[U90] JS：数字数组排序
来源：http://dali.yvedp.cn/Article/details/gtlmdhiien.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gtrowflcia.html

[U91] JS：对象键值遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtysudbpuf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cashguo.top/Article/details/gtmqdxuiou.html

[U92] JS：深拷贝
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhvlxdqx.html

structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gtvubmykje.html

[U93] JS：模板字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtxbasldlv.html

`共 ${n} 条`
来源：http://dali.ydzc1.top/Article/details/gtcbiqacno.html

[U94] JS：箭头函数
来源：http://dali.shanyushiyangtech.top/Article/details/gthsdvdgck.html

const double = x => x * 2;
来源：http://dali.feifeiyinyue.top/Article/details/gtnozzrwyl.html

[U95] JS：Promise 包装
来源：http://dali.9152youxi.cn/Article/details/gtkhqxjzwd.html

new Promise((resolve, reject) => {})
来源：http://dali.ivvv.top/Article/details/gtapuuwvcv.html

[U96] JS：async/await 与异常
来源：http://dali.shuidangran.top/Article/details/gtnzipdvmj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtuuvohmvk.html

[U97] JS：并发请求
来源：http://dali.chenzaomai.com/Article/details/gtfuqziymk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gttksnfpvt.html

[U98] JS：fetch 带 JSON
来源：http://dali.yanxiufei.cn/Article/details/gtzqbptdwc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xuanzx.com/Article/details/gtlimhsgox.html

[U99] JS：事件监听
来源：http://dali.wangdashe.top/Article/details/gtzynarkty.html

el.addEventListener("click", e => {})
来源：http://dali.hammf.cn/Article/details/gtkdcylwpa.html

[U100] JS：DOM 查询
来源：http://dali.tanke756.top/Article/details/gtwsemnkvm.html

document.querySelector(".item")
来源：http://dali.smart0.xyz/Article/details/gttdfdguji.html

[U101] JS：classList 操作
来源：http://dali.dashuyun.cn/Article/details/gtzzdxbmtk.html

el.classList.toggle("active")
来源：http://dali.sysykeji.top/Article/details/gtgwuhzypj.html

[U102] JS：本地存储
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadhawhgq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sxryk.cn/Article/details/gtdtnrzvmd.html

[U103] JS：定时器
来源：http://dali.316326.xyz/Article/details/gtltyykckg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.guowangkeji.top/Article/details/gthtlvramx.html

[U104] JS：防抖
来源：http://dali.zhiwuduotai.top/Article/details/gtqkxqodeu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gtnepmspcz.html

[U105] JS：节流
来源：http://dali.zdqjudy.top/Article/details/gtkmmpftak.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.redwolf501.top/Article/details/gtgyetymzr.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gthjfzctfp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.redwolf501.top/Article/details/gtoixzlflk.html

[U107] JS：数字千分位
来源：http://dali.jinqigufen.top/Article/details/gtkcpxzwyw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.guannengcc.top/Article/details/gtlpqyoixw.html

[U108] JS：随机整数
来源：http://dali.jiagoushi.top/Article/details/gtoikgsjkf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.0kj1m.cn/Article/details/gtyjkcmjjd.html

[U109] JS：数组分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcssavyaz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ivvv.top/Article/details/gtnuzudqps.html

[U110] JS：数组分块
来源：http://dali.fzhhl.top/Article/details/gtpqfjnxwc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.mhx1999.top/Article/details/gtftklhfcc.html

[U111] JS：对象转 Map
来源：http://dali.hysaishi.cn/Article/details/gtahlfuotc.html

new Map(Object.entries(obj))
来源：http://dali.gogol.net.cn/Article/details/gtyexsnxvv.html

[U112] JS：字符串补位
来源：http://dali.hfpthk.cn/Article/details/gtvbuvmbmf.html

"7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gtvbkxqgeg.html

[U113] JS：正则替换全部
来源：http://dali.yangfankeji.com/Article/details/gtvvtckziq.html

s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gthuhtxscw.html

[U114] JS：JSON 深比较
来源：http://dali.xuanzx.com/Article/details/gtyievhsvd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtuitzjubq.html

[U115] JS：生成 UUID
来源：http://dali.wangshuangyany.cn/Article/details/gtihjmssag.html

crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gtptobmaus.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.sweek.top/Article/details/gtezbmodmf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.aibaodan.cn/Article/details/gtyudbbcgo.html

[U117] JS：单元测试
来源：http://dali.9152youxi.cn/Article/details/gtkguadyht.html

npm i -D vitest;  npx vitest
来源：http://dali.yuxming.cn/Article/details/gtfxdwuqlh.html

[U118] JS：开发服务器
来源：http://dali.jinqigfzy.top/Article/details/gtdeujrtvx.html

npm i -D vite;  npx vite
来源：http://dali.quarkkingdee.top/Article/details/gtbjnjjkal.html

[U119] JS：生产构建
来源：http://dali.andypj.xyz/Article/details/gtmidrrakx.html

npx vite build
来源：http://dali.vqdsnc.cn/Article/details/gtgnlxwlsi.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.wangshuangyany.cn/Article/details/gtjaxfjeda.html

import.meta.env.VITE_API_URL
来源：http://dali.shanyushiyangtech.top/Article/details/gtwndtscsa.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtvmmobqdf.html

统计汇总
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdpurvdw.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtqxuyzqlg.html

按语言统计（条）：
来源：http://dali.hnxiangtu.top/Article/details/gtafcnhtpr.html

Python ......... 252
来源：http://dali.daxiang520.top/Article/details/gtwncxytwm.html

PHP ............ 252
来源：http://dali.hysaishi.cn/Article/details/gtarppqvqq.html

JavaScript ..... 252
来源：http://dali.gzhubu.top/Article/details/gtnintusez.html

TypeScript ..... 212
来源：http://dali.tianlin.xyz/Article/details/gtxbehtgww.html

Java ........... 212
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltpojwbm.html

Go ............. 212
来源：http://dali.hnqzz.top/Article/details/gtznwjeugd.html

Ruby ........... 212
来源：http://dali.wangdashe.top/Article/details/gtjunxpwhj.html

C# ............. 212
来源：http://dali.0kj1m.cn/Article/details/gtephvhgww.html

C .............. 30
来源：http://dali.pengpengdd.cyou/Article/details/gtiohqzufj.html

C++ ............ 30
来源：http://dali.sufxvd.cn/Article/details/gtjzjevmcz.html

SQL ............ 90
来源：http://dali.yj20258.top/Article/details/gtsojenler.html

Bash ........... 80
来源：http://dali.hongshengwenyu.top/Article/details/gtuyllpusu.html

Kotlin ......... 15
来源：http://dali.shuidangran.top/Article/details/gtozgbotfv.html

Swift .......... 15
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnwjlcfib.html

Lua ............ 10
来源：http://dali.yangfankeji.com/Article/details/gtyrorhfwf.html

Perl ........... 10
来源：http://dali.guowangkeji.top/Article/details/gtijxxgkxh.html

Scala .......... 10
来源：http://dali.zycfv.cn/Article/details/gttcvqivti.html

------------------------------------
来源：http://dali.xylfe.cn/Article/details/gtwyxiirls.html

合计 ........... 2106 条
来源：http://dali.bjfxy.top/Article/details/gtjiaaoanr.html

按章节统计：
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjidgajo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yangfankeji.com/Article/details/gtozhevdpy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cqqwz.cn/Article/details/gtyhvrhrgl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.kuanghao11.cn/Article/details/gtrajsmhuk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hammf.cn/Article/details/gtqzvqdtbo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.dianchejie.cn/Article/details/gtihgwbthm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.chenlongwang.top/Article/details/gtakcmlcza.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gzhubu.top/Article/details/gtdudrgriw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cdnleiting.top/Article/details/gtzzukbmdv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gtibdihhkd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ppjwa.cn/Article/details/gtrodpfopk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gtdzytjowr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gtcqmcchqu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.feifeiyinyue.top/Article/details/gtvmzlpdzx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.316326.xyz/Article/details/gtkdbndmqq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.sxryk.cn/Article/details/gtfuigujri.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gtqsxbkrip.html

Q SQL 专题                              90
来源：http://dali.cashguo.top/Article/details/gtvnidpfnp.html

R Bash 专题                             80
来源：http://dali.hysaishi.cn/Article/details/gtwrwcgdfw.html

S C / C++ 专题                          60
来源：http://dali.316326.xyz/Article/details/gtykisxwat.html

T 其他语言补充                          60
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzyqbuxj.html

U 高频实用片段                         120
来源：http://dali.pengpengdd.cyou/Article/details/gtlczbazzw.html

------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gtlkynkqzo.html

合计                                  2106 条
来源：http://dali.cheryme.top/Article/details/gtvlyctplu.html

--------------------------------------------------------------------------------
来源：http://dali.gzhubu.top/Article/details/gtkaewtecm.html

使用提醒
来源：http://dali.nwbrower.top/Article/details/gtpzdkhfkj.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gthsnhwxgk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.daria6918.cn/Article/details/gtyyztsjpl.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.tian-w.cn/Article/details/gthgzyjgzd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.fengsongda.top/Article/details/gtyvoseyjg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xinyue.icu/Article/details/gtycijcvtf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cashguo.top/Article/details/gtcwaqivoy.html

—— 文件结束 ——
来源：http://dali.mhx1999.top/Article/details/gteqrlceuz.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtypzrntfv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.bjfxy.top/Article/details/gtcjtlptdq.html

Common Programming Examples Cheat Book
来源：http://dali.jqgufenzy.top/Article/details/gtblndoryn.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtdfbwghkj.html

【收录内容】
来源：http://dali.yj20258.top/Article/details/gtwnzaqqan.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xuanzx.com/Article/details/gtfiipfkvz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.9152youxi.cn/Article/details/gtopwfanls.html

SQL · Bash · C · C++
来源：http://dali.yj202588.top/Article/details/gttpmcxcdh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.sufxvd.cn/Article/details/gtltmvirgo.html

【使用说明】
来源：http://dali.yueranfly.top/Article/details/gtvzzatzas.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jinqigfzy.top/Article/details/gteyjaumlr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhoulong.xyz/Article/details/gtxrdaraji.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.nwbrower.top/Article/details/gtraflbcgk.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yonumen.top/Article/details/gtkvrtcyyx.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.c1oappe.top/Article/details/gtnnjbmqwr.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.snrcjt.cn/Article/details/gtracngfvs.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.sysykeji.top/Article/details/gtrenktqwp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.gzhubu.top/Article/details/gthiuqrukm.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhdvpcdq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ppjwa.cn/Article/details/gtmebpzpys.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.aibaodan.cn/Article/details/gtuvgtuvid.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jqgfzy.top/Article/details/gtxwzjuedt.html

【文件统计】
来源：http://dali.ydzc1.top/Article/details/gtjkzanwxa.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hongshengwenyu.top/Article/details/gtbtliahgh.html

--------------------------------------------------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gtckjqqgcu.html

目  录
来源：http://dali.daxiang520.top/Article/details/gtvquwtkdq.html

--------------------------------------------------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gtiahukaay.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ivvv.top/Article/details/gtkxkgnyot.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.pycfn.com/Article/details/gtzhpyerux.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hfpthk.cn/Article/details/gtoxyduffc.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xylfe.cn/Article/details/gtuehikkgn.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtoebhpuqh.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtzqttjbbn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jyoumei.cn/Article/details/gtorhhxqla.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.snrcjt.cn/Article/details/gtcusurgvt.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gteazjddqz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yonumen.top/Article/details/gtpywlgfxt.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gtbxirujud.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.daria6918.cn/Article/details/gtxxqiwpja.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.daria6918.cn/Article/details/gthzloksxl.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jianghu66.top/Article/details/gtnuedgnzu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtrndsatwp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.aizwys.cn/Article/details/gtoztiynwq.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yangfankeji.com/Article/details/gtbuutvxri.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.bjfxy.top/Article/details/gtukjyjqiu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzowfwjd.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zycfv.cn/Article/details/gthfppqtmj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.quarkkingdee.top/Article/details/gtxbsapqwc.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtctnbzvct.html

A. 基础语法与类型
来源：http://dali.cucudq.cn/Article/details/gtianlqtkr.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqtnkxsu.html

[A01] Hello World
来源：http://dali.snrcjt.cn/Article/details/gthkczdpfe.html

Py:   print("Hello, World!")
来源：http://dali.yonumen.top/Article/details/gtubaaekeo.html

PHP:  echo "Hello, World!";
来源：http://dali.snrcjt.cn/Article/details/gtkfgndcbu.html

JS:   console.log("Hello, World!");
来源：http://dali.zhiwuduotai.top/Article/details/gtdupuvcui.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jyoumei.cn/Article/details/gtvlgxsxqp.html

Java: System.out.println("Hello, World!");
来源：http://dali.bjfxy.top/Article/details/gtphhtjfmm.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.shanyushiyangtech.top/Article/details/gttmizucav.html

Ruby: puts "Hello, World!"
来源：http://dali.0kj1m.cn/Article/details/gtypraytbz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.fzhhl.top/Article/details/gtkecjfuki.html

[A02] 变量声明与赋值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvnksrhn.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.tian-w.cn/Article/details/gtigqjxstp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.sufxvd.cn/Article/details/gtdeckhjhu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.haohaochexian.top/Article/details/gtfterfjpw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.tianlin.xyz/Article/details/gtcigdlkto.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.smart0.xyz/Article/details/gtyepiuevj.html

Go:   name := "Alex"; age := 20
来源：http://dali.ybcxt.top/Article/details/gtwdowksjv.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jinghuilouyu.cn/Article/details/gtdbbjhyod.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.0kj1m.cn/Article/details/gtwpqmqbhh.html

[A03] 常量定义
来源：http://dali.xuanzx.com/Article/details/gtwuxkubrm.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.nanxuanxn.top/Article/details/gtpiclhcdl.html

PHP:  const PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtajuakkxh.html

JS:   const PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtnocckptz.html

TS:   const PI: number = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtnzdkdnji.html

Java: static final double PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtccvmygzh.html

Go:   const PI = 3.14159
来源：http://dali.hysaishi.cn/Article/details/gttrcidjxj.html

Ruby: PI = 3.14159
来源：http://dali.fzhhl.top/Article/details/gtpbvdtjbm.html

C#:   const double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtpcuxphqr.html

[A04] 判断变量类型
来源：http://dali.yongpay.top/Article/details/gtvxajfjlb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhiwuduotai.top/Article/details/gtflyusbjp.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.chenjidiqi.icu/Article/details/gtyustyred.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.havefunace.top/Article/details/gtaxtkzdaa.html

TS:   typeof x; x instanceof Date
来源：http://dali.smart0.xyz/Article/details/gttfmkirll.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhoulong.xyz/Article/details/gtqfnkqego.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.guowangkeji.top/Article/details/gtoxtlvfwt.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.dashuyun.cn/Article/details/gtvchozvoh.html

C#:   x.GetType().Name; x is int
来源：http://dali.xylfe.cn/Article/details/gtorldhpjb.html

[A05] 整数除法与取模
来源：http://dali.smart0.xyz/Article/details/gttocvugor.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.chenlongwang.top/Article/details/gtceezztyi.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gtpyexzege.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zycfv.cn/Article/details/gtjrjtsbyn.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.iojbl.cn/Article/details/gtivbwyqos.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gtuijknewd.html

Go:   7 / 2; 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gtxhocxese.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gtprdjmiad.html

C#:   7 / 2; 7 % 2
来源：http://dali.cheryme.top/Article/details/gtazwonjzu.html

[A06] 字符串转数字
来源：http://dali.yj20258888.top/Article/details/gtmjtxqlcc.html

Py:   int("42"); float("3.14")
来源：http://dali.tianlin.xyz/Article/details/gtivxizrsl.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hongshengwenyu.top/Article/details/gtsnpajncx.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.kuanghao11.cn/Article/details/gtigxzbsae.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhoulong.xyz/Article/details/gtsgcdxqao.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jinqigfzy.top/Article/details/gtvpqirukc.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.daxiang520.top/Article/details/gtguqirhgz.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yuanzhike.top/Article/details/gtxspchtmx.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.daria6918.cn/Article/details/gtolydccjs.html

[A07] 数字转字符串
来源：http://dali.yueranfly.top/Article/details/gtqlylfgcx.html

Py:   str(42)
来源：http://dali.yvedp.cn/Article/details/gtmrudbcyp.html

PHP:  (string) 42; strval(42)
来源：http://dali.nanxuanxn.top/Article/details/gtngwdbqwk.html

JS:   String(42); (42).toString()
来源：http://dali.yonumen.top/Article/details/gtztjyawls.html

TS:   String(42)
来源：http://dali.redwolf501.top/Article/details/gtfqgizmih.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ivvv.top/Article/details/gtojchpvqz.html

Go:   strconv.Itoa(42)
来源：http://dali.gotoacloud.top/Article/details/gtkjxmhgfp.html

Ruby: 42.to_s
来源：http://dali.hnxiangtu.top/Article/details/gtaatnrfnh.html

C#:   42.ToString()
来源：http://dali.svipenyu.cn/Article/details/gtrywlgmch.html

[A08] 取整与四舍五入
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoeiaqdvw.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jiagoushi.top/Article/details/gthydqigge.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hnqzz.top/Article/details/gtcgczornt.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.aibaodan.cn/Article/details/gtpnsfbuqn.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.daria6918.cn/Article/details/gthxcziahd.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjpgpzci.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jqgfzy.top/Article/details/gtibvirvgc.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.vqdsnc.cn/Article/details/gttrexlzkg.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yj202588.top/Article/details/gtwpcmqchw.html

[A09] 绝对值与最大最小值
来源：http://dali.zycfv.cn/Article/details/gtgcrnytaf.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtozewxjyh.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gtusjjhtao.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gtnxmaopth.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtryymmtay.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gtaebghwbz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.9152youxi.cn/Article/details/gtijsjpuzp.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yongpay.top/Article/details/gtwdsadqtm.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.wangdashe.top/Article/details/gtskcovflm.html

[A10] 生成随机数
来源：http://dali.0kj1m.cn/Article/details/gtighpyvnz.html

Py:   import random; random.randint(1, 100)
来源：http://dali.cqqwz.cn/Article/details/gtfpakizkv.html

PHP:  random_int(1, 100);
来源：http://dali.shuidangran.top/Article/details/gtqqemsrcj.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yueranfly.top/Article/details/gthyhkxlre.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.mhx1999.top/Article/details/gtbyltuwpv.html

Java: new Random().nextInt(100) + 1
来源：http://dali.aizwys.cn/Article/details/gtyjigubgs.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jyoumei.cn/Article/details/gtjiakkdks.html

Ruby: rand(1..100)
来源：http://dali.9152youxi.cn/Article/details/gtjylfgwno.html

C#:   new Random().Next(1, 101)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybnnzrfj.html

[A11] 条件表达式（三元）
来源：http://dali.9152youxi.cn/Article/details/gtmggkgokh.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.sufxvd.cn/Article/details/gtrtyzpfgc.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.tian-w.cn/Article/details/gtdhxwadaf.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.gotoacloud.top/Article/details/gtjnulsodn.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.gogol.net.cn/Article/details/gtbazfyzza.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gtuuvssslo.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.iojbl.cn/Article/details/gtfquuruof.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.cdnleiting.top/Article/details/gtkrbpgmwl.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.wangshuangyany.cn/Article/details/gtmztrtesi.html

[A12] 字符串插值 / 格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkbvammu.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.hongshengwenyu.top/Article/details/gtnwwfubkm.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbswjoga.html

JS:   `Hello, ${name}!`
来源：http://dali.yuxming.cn/Article/details/gtwurogjto.html

TS:   `Hello, ${name}!`
来源：http://dali.fengsongda.top/Article/details/gtyurybkll.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.havefunace.top/Article/details/gtoarzxpxq.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.shuidangran.top/Article/details/gtyqrkwhuq.html

Ruby: "Hello, #{name}!"
来源：http://dali.tianlin.xyz/Article/details/gtafbgfvgh.html

C#:   $"Hello, {name}!"
来源：http://dali.yj20258.top/Article/details/gtnkmfeinn.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoklrexcu.html

Py:   "第一行\n第二行"
来源：http://dali.xziqi.cn/Article/details/gtjeekmfrp.html

PHP:  "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gtwzcfaznr.html

JS:   "第一行\n第二行"
来源：http://dali.zhongyouzk.top/Article/details/gtuitolign.html

TS:   "第一行\n第二行"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbkcjuck.html

Java: "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gtmelicecc.html

Go:   "第一行\n第二行"
来源：http://dali.nanxinkj.top/Article/details/gtstecompn.html

Ruby: "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gtysclrahq.html

C#:   "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gtkvdjdegk.html

[A14] 注释写法
来源：http://dali.cashguo.top/Article/details/gtoqdscqkd.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaknyaiqu.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.iojbl.cn/Article/details/gtqxbncoht.html

JS:   // 单行；/* 多行 */
来源：http://dali.cheryme.top/Article/details/gtsfoxihnk.html

TS:   // 单行；/* 多行 */
来源：http://dali.daxiang520.top/Article/details/gtaoinxzrf.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yuxming.cn/Article/details/gtnuhwbdfy.html

Go:   // 单行；/* 多行 */
来源：http://dali.daxiang520.top/Article/details/gtwgbtczbc.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.ivvv.top/Article/details/gtltuhjuza.html


<!-- 参考信息 -->