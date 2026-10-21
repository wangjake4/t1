代发 wailian999

[U95] JS：Promise 包装
来源：http://dali.xuetiantiany.cn/Article/details/gtwdwylaam.html

new Promise((resolve, reject) => {})
来源：http://dali.xziqi.cn/Article/details/gtqbfguxto.html

[U96] JS：async/await 与异常
来源：http://dali.zdqjudy.top/Article/details/gtuxpcxsry.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gterduwfra.html

[U97] JS：并发请求
来源：http://dali.dashuyun.cn/Article/details/gtdjjuwyev.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gtiqeavivk.html

[U98] JS：fetch 带 JSON
来源：http://dali.yueranfly.top/Article/details/gtqyvccdte.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yj20258.top/Article/details/gtukecokoy.html

[U99] JS：事件监听
来源：http://dali.daria6918.cn/Article/details/gtetuqqxxs.html

el.addEventListener("click", e => {})
来源：http://dali.hnqzz.top/Article/details/gtoixvaitt.html

[U100] JS：DOM 查询
来源：http://dali.zdqjudy.top/Article/details/gtbnzfxbhz.html

document.querySelector(".item")
来源：http://dali.quarkkingdee.top/Article/details/gtrqukxsip.html

[U101] JS：classList 操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwdytdvt.html

el.classList.toggle("active")
来源：http://dali.316326.xyz/Article/details/gttcnzgfjy.html

[U102] JS：本地存储
来源：http://dali.ehwqpu.com/Article/details/gtvfskundl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yj20258888.top/Article/details/gtqvktvqdy.html

[U103] JS：定时器
来源：http://dali.gaohongyu789.top/Article/details/gtrbrzpopq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jiagoushi.top/Article/details/gtomncrklt.html

[U104] JS：防抖
来源：http://dali.andypj.xyz/Article/details/gtvyuytdjr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhongyouzk.top/Article/details/gtnholbfek.html

[U105] JS：节流
来源：http://dali.aizwys.cn/Article/details/gtebloafdy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmvepizm.html

[U106] JS：日期格式化
来源：http://dali.yj20258888.top/Article/details/gtkcgpflgo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shuidangran.top/Article/details/gtadtgpdfw.html

[U107] JS：数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gtskgonban.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.birdmap.top/Article/details/gtbnrbbxtb.html

[U108] JS：随机整数
来源：http://dali.yvedp.cn/Article/details/gtayrrnilq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.316326.xyz/Article/details/gtyphvcebs.html

[U109] JS：数组分组
来源：http://dali.cashguo.top/Article/details/gtfsnyfdim.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gtuxjaobnt.html

[U110] JS：数组分块
来源：http://dali.zhongyouzk.top/Article/details/gttcdgoimj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.redwolf501.top/Article/details/gtqepmvvpx.html

[U111] JS：对象转 Map
来源：http://dali.nwbrower.top/Article/details/gtvfjqaybx.html

new Map(Object.entries(obj))
来源：http://dali.hnqzz.top/Article/details/gtkgiboent.html

[U112] JS：字符串补位
来源：http://dali.bjfxy.top/Article/details/gtajqzlmfj.html

"7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtehgraykj.html

[U113] JS：正则替换全部
来源：http://dali.zycfv.cn/Article/details/gtbjejvbyf.html

s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gttvhpwjlv.html

[U114] JS：JSON 深比较
来源：http://dali.wangdashe.top/Article/details/gtcefwspdj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ivvv.top/Article/details/gtvtonapav.html

[U115] JS：生成 UUID
来源：http://dali.fengsongda.top/Article/details/gtvuwdieix.html

crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gtnrmjbbui.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpefncxhz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.nanxuanxn.top/Article/details/gtoplgkvks.html

[U117] JS：单元测试
来源：http://dali.dashuyun.cn/Article/details/gtnrcdimpa.html

npm i -D vitest;  npx vitest
来源：http://dali.xuanzx.com/Article/details/gtnqvtnisw.html

[U118] JS：开发服务器
来源：http://dali.jinghuilouyu.cn/Article/details/gtqckvmbcb.html

npm i -D vite;  npx vite
来源：http://dali.dashuyun.cn/Article/details/gtpcaeyktl.html

[U119] JS：生产构建
来源：http://dali.fengsongda.top/Article/details/gtthaxiddj.html

npx vite build
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbdjqykk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.dashuyun.cn/Article/details/gtppaotqnf.html

import.meta.env.VITE_API_URL
来源：http://dali.yongpay.top/Article/details/gtgojukqbu.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtuntwcmab.html

统计汇总
来源：http://dali.wangshuangyany.cn/Article/details/gtijhpgmzs.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtipmhikit.html

按语言统计（条）：
来源：http://dali.meibo888.top/Article/details/gtxyxebwtm.html

Python ......... 252
来源：http://dali.cashguo.top/Article/details/gtydneytfj.html

PHP ............ 252
来源：http://dali.jinqigufen.top/Article/details/gtpdpqofob.html

JavaScript ..... 252
来源：http://dali.iojbl.cn/Article/details/gtzdxlsbne.html

TypeScript ..... 212
来源：http://dali.shanyushiyangtech.top/Article/details/gtjwkeessh.html

Java ........... 212
来源：http://dali.fengsongda.top/Article/details/gttissmitj.html

Go ............. 212
来源：http://dali.zhongyouzk.top/Article/details/gtjaxxxmdw.html

Ruby ........... 212
来源：http://dali.chenzaomai.com/Article/details/gtnztvmdia.html

C# ............. 212
来源：http://dali.chenzaomai.com/Article/details/gtuwdklhfa.html

C .............. 30
来源：http://dali.sufxvd.cn/Article/details/gtqyrvilgm.html

C++ ............ 30
来源：http://dali.haohaochexian.top/Article/details/gttgztbuxa.html

SQL ............ 90
来源：http://dali.jqgufenzy.top/Article/details/gtghtnwohp.html

Bash ........... 80
来源：http://dali.cqqwz.cn/Article/details/gtfnfmxcyr.html

Kotlin ......... 15
来源：http://dali.pycfn.com/Article/details/gtekeuwgsm.html

Swift .......... 15
来源：http://dali.redwolf501.top/Article/details/gtabgfiquu.html

Lua ............ 10
来源：http://dali.hammf.cn/Article/details/gtfeacapqu.html

Perl ........... 10
来源：http://dali.shzxlz.cn/Article/details/gttohqzcad.html

Scala .......... 10
来源：http://dali.gzhubu.top/Article/details/gtsmupkuay.html

------------------------------------
来源：http://dali.gzhubu.top/Article/details/gtjlccbrdm.html

合计 ........... 2106 条
来源：http://dali.zycfv.cn/Article/details/gttyseouvr.html

按章节统计：
来源：http://dali.cdnleiting.top/Article/details/gtnxwkpcet.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cucudq.cn/Article/details/gtatptabrd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.aizwys.cn/Article/details/gtiwpqhahh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhongyouzk.top/Article/details/gtpnhxzfhp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.c1oappe.top/Article/details/gtzdatefaa.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jinqigufen.top/Article/details/gtihfjvnob.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.wangshuangyany.cn/Article/details/gtzvlwrmns.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.cucudq.cn/Article/details/gtocvzyndk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.tianlin.xyz/Article/details/gtjvzuowcm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gtzcruwbtg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yj202588.top/Article/details/gtyvrlgped.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gtxcwrtbvr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gtsmoylzof.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gtsiwgaxsn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.fzhhl.top/Article/details/gthrxjfhas.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.dashuyun.cn/Article/details/gtvmvxurzq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gtnhaerruj.html

Q SQL 专题                              90
来源：http://dali.sxryk.cn/Article/details/gtdaobzmve.html

R Bash 专题                             80
来源：http://dali.zycfv.cn/Article/details/gterfnwzyf.html

S C / C++ 专题                          60
来源：http://dali.guowangkeji.top/Article/details/gtvvusctej.html

T 其他语言补充                          60
来源：http://dali.jianghu66.top/Article/details/gteyqrkfen.html

U 高频实用片段                         120
来源：http://dali.nanxinkj.top/Article/details/gtmdlyeecp.html

------------------------------------
来源：http://dali.yuxming.cn/Article/details/gtvcelbvoo.html

合计                                  2106 条
来源：http://dali.jinqigfzy.top/Article/details/gtmruywhlk.html

--------------------------------------------------------------------------------
来源：http://dali.yonumen.top/Article/details/gtnvxhpomd.html

使用提醒
来源：http://dali.nwbrower.top/Article/details/gtqixcwivx.html

--------------------------------------------------------------------------------
来源：http://dali.shuidangran.top/Article/details/gtsbdqazia.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.chenlongwang.top/Article/details/gtqktdeahw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ybcxt.top/Article/details/gtdsefoove.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yj20258888.top/Article/details/gtggpadrxm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jqgufenzy.top/Article/details/gtxnhxlmyl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcuewfymy.html

—— 文件结束 ——
来源：http://dali.vqdsnc.cn/Article/details/gtkhjtaevj.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtsqeatyok.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.chenzaomai.com/Article/details/gtzacniass.html

Common Programming Examples Cheat Book
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzkxrrbv.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtybflrvml.html

【收录内容】
来源：http://dali.sxryk.cn/Article/details/gtaarwanml.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hongshengwenyu.top/Article/details/gtbwmtbrjh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jqgufenzy.top/Article/details/gtfhyumbxo.html

SQL · Bash · C · C++
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldsffqou.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.shangyingyoupin.top/Article/details/gtmkrttwlv.html

【使用说明】
来源：http://dali.smart0.xyz/Article/details/gtyawxhrlp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hongshengwenyu.top/Article/details/gtfirrexra.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.nanxinkj.top/Article/details/gtqiqodckn.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hnqzz.top/Article/details/gtjlgchagd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jqgufenzy.top/Article/details/gtplkwnnbx.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.chenzaomai.com/Article/details/gtkhanoigm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yj202588.top/Article/details/gtydbtuggm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.chenjidiqi.icu/Article/details/gtdfakhgeh.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hammf.cn/Article/details/gtjlhcvvlr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.guowangkeji.top/Article/details/gttrophsek.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.pycfn.com/Article/details/gtubroybpm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xuanzx.com/Article/details/gtgxhfbwwh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.sufxvd.cn/Article/details/gtkggvueqk.html

【文件统计】
来源：http://dali.tanke756.top/Article/details/gtzsogwpfy.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gaohongyu789.top/Article/details/gtqzbltsdz.html

--------------------------------------------------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gtkherosoc.html

目  录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtelxsdovo.html

--------------------------------------------------------------------------------
来源：http://dali.yj202588.top/Article/details/gtpdedynyu.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xinyue.icu/Article/details/gthkolkuua.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yj202588.top/Article/details/gtbtcmhzsn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.sufxvd.cn/Article/details/gtcgbqzywy.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xylfe.cn/Article/details/gtuyqocwes.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.gogol.net.cn/Article/details/gtcxueggzg.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.sweek.top/Article/details/gtxybtwpzc.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnrezctd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhoulong.xyz/Article/details/gtjwpaxipg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gtnycepzbq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.316326.xyz/Article/details/gthfvxwzvm.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gtttkigfle.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.kuanghao11.cn/Article/details/gtlszvurfn.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtrdqwyfdk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.guannengcc.top/Article/details/gtlpqsafhv.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.guannengcc.top/Article/details/gthedsdqzd.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtszkytyra.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.daria6918.cn/Article/details/gtxbfeiant.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.dashuyun.cn/Article/details/gtegeygpqa.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ivvv.top/Article/details/gtcoudiunt.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ppjwa.cn/Article/details/gtmuxyhvsj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuanzx.com/Article/details/gtpnpxecvg.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtzllrppvk.html

A. 基础语法与类型
来源：http://dali.iojbl.cn/Article/details/gtphnaiidk.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtozepqake.html

[A01] Hello World
来源：http://dali.tanke756.top/Article/details/gtpifhsyjb.html

Py:   print("Hello, World!")
来源：http://dali.316326.xyz/Article/details/gtdldlyiiv.html

PHP:  echo "Hello, World!";
来源：http://dali.dashuyun.cn/Article/details/gtwsxkebjp.html

JS:   console.log("Hello, World!");
来源：http://dali.jiagoushi.top/Article/details/gtlisvgxlk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cqqwz.cn/Article/details/gtskulzpgd.html

Java: System.out.println("Hello, World!");
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhhiwqke.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.gogol.net.cn/Article/details/gtmyrnltkf.html

Ruby: puts "Hello, World!"
来源：http://dali.sufxvd.cn/Article/details/gtroybrnyx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.guowangkeji.top/Article/details/gtudqazchj.html

[A02] 变量声明与赋值
来源：http://dali.andypj.xyz/Article/details/gtgyedmbwn.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.nwbrower.top/Article/details/gtupeqwaeb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xuetiantiany.cn/Article/details/gtmvpylfzz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shzxlz.cn/Article/details/gtwqenfjcs.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.andypj.xyz/Article/details/gtkceczogk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xuanzx.com/Article/details/gtunwayzws.html

Go:   name := "Alex"; age := 20
来源：http://dali.jiagoushi.top/Article/details/gtgzwkvtvw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.dashuyun.cn/Article/details/gtnoayrwte.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.tianlin.xyz/Article/details/gtaivjzmtw.html

[A03] 常量定义
来源：http://dali.fengsongda.top/Article/details/gtjqsivzdi.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.svipenyu.cn/Article/details/gtrpgkeyty.html

PHP:  const PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtbxexnzbv.html

JS:   const PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtjqaayhyj.html

TS:   const PI: number = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtocdhqwyk.html

Java: static final double PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtonlnfhwu.html

Go:   const PI = 3.14159
来源：http://dali.jqgfzy.top/Article/details/gthjlsvgkv.html

Ruby: PI = 3.14159
来源：http://dali.jqgufenzy.top/Article/details/gtytuhpcfd.html

C#:   const double PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtkakckjty.html

[A04] 判断变量类型
来源：http://dali.snrcjt.cn/Article/details/gtpvcdfxxq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.quarkkingdee.top/Article/details/gtgwezlxjh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ehwqpu.com/Article/details/gtdrmqgfah.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yonumen.top/Article/details/gtterjljlk.html

TS:   typeof x; x instanceof Date
来源：http://dali.hysaishi.cn/Article/details/gtknmeqknr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ydzc1.top/Article/details/gtjlhtdgsj.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.cucudq.cn/Article/details/gtkfptxsot.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.svipenyu.cn/Article/details/gtblyrfciu.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjockvhay.html

[A05] 整数除法与取模
来源：http://dali.svipenyu.cn/Article/details/gtirhpswyr.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.chenjidiqi.icu/Article/details/gtgbokjwqe.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtezgogzuq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.fengsongda.top/Article/details/gtioldkiak.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ivvv.top/Article/details/gtqeqbnkpd.html

Java: 7 / 2; 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gtbapfptba.html

Go:   7 / 2; 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonhwpksx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gtnlsnzmwh.html

C#:   7 / 2; 7 % 2
来源：http://dali.sweek.top/Article/details/gtvervdxvi.html

[A06] 字符串转数字
来源：http://dali.cucudq.cn/Article/details/gtrvqsiwaz.html

Py:   int("42"); float("3.14")
来源：http://dali.hammf.cn/Article/details/gtuofyukoz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.daria6918.cn/Article/details/gtfvgbkyqp.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.9152youxi.cn/Article/details/gtbemfqbit.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.andypj.xyz/Article/details/gtyukspslz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.daxiang520.top/Article/details/gtxvjusfhn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhiwuduotai.top/Article/details/gtzfcbpolh.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yj20258888.top/Article/details/gtqmdboyma.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.nwbrower.top/Article/details/gtgkudyyje.html

[A07] 数字转字符串
来源：http://dali.9152youxi.cn/Article/details/gttwqdigqa.html

Py:   str(42)
来源：http://dali.guannengcc.top/Article/details/gtcwlopxdg.html

PHP:  (string) 42; strval(42)
来源：http://dali.jyoumei.cn/Article/details/gtlgtcyhum.html

JS:   String(42); (42).toString()
来源：http://dali.ehwqpu.com/Article/details/gtykkfcqtq.html

TS:   String(42)
来源：http://dali.svipenyu.cn/Article/details/gtnpjyrubh.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.daxiang520.top/Article/details/gtweeingjg.html

Go:   strconv.Itoa(42)
来源：http://dali.chenjidiqi.icu/Article/details/gtvfttspmz.html

Ruby: 42.to_s
来源：http://dali.feifeiyinyue.top/Article/details/gtqgsdgwwz.html

C#:   42.ToString()
来源：http://dali.vqdsnc.cn/Article/details/gtegcbehqw.html

[A08] 取整与四舍五入
来源：http://dali.haohaochexian.top/Article/details/gtlszugbhx.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.xziqi.cn/Article/details/gtpfcgkdsg.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yanxiufei.cn/Article/details/gtnfassacs.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.fengsongda.top/Article/details/gtadmnhfyj.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hywenlv.cn/Article/details/gtjzsdwqes.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.tianlin.xyz/Article/details/gtqzhbvwos.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jqgfzy.top/Article/details/gtprvmowtn.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.hongshengwenyu.top/Article/details/gtnjpstuzv.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yuxming.cn/Article/details/gtvwnzmjph.html

[A09] 绝对值与最大最小值
来源：http://dali.cheryme.top/Article/details/gtjgiffxbi.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.mhx1999.top/Article/details/gtinxxvdgi.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtoahepzrj.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.cheryme.top/Article/details/gtctwtyzox.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtavxvuntm.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.meibo888.top/Article/details/gtrwrhwjjy.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.wangdashe.top/Article/details/gtounpytei.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.c1oappe.top/Article/details/gtxqexepvp.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gthwusjwrx.html

[A10] 生成随机数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevjtglxn.html

Py:   import random; random.randint(1, 100)
来源：http://dali.sxryk.cn/Article/details/gthhyarxut.html

PHP:  random_int(1, 100);
来源：http://dali.zhongyouzk.top/Article/details/gtptkhnsgt.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.0kj1m.cn/Article/details/gtxcutjhsc.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ivvv.top/Article/details/gtplqfefbv.html

Java: new Random().nextInt(100) + 1
来源：http://dali.guannengcc.top/Article/details/gtlcnolitz.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yanxiufei.cn/Article/details/gtmupjthbd.html

Ruby: rand(1..100)
来源：http://dali.meibo888.top/Article/details/gtznyuqdla.html

C#:   new Random().Next(1, 101)
来源：http://dali.yanxiufei.cn/Article/details/gtbfilrtrq.html

[A11] 条件表达式（三元）
来源：http://dali.xziqi.cn/Article/details/gtfsnxflpr.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.aibaodan.cn/Article/details/gtlscyehsz.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.sweek.top/Article/details/gtwvwhhegp.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.wangdashe.top/Article/details/gthzjhzync.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yanxiufei.cn/Article/details/gtnlwnyedg.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yj202588.top/Article/details/gtslstyjjl.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.vqdsnc.cn/Article/details/gtiocryabc.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.daria6918.cn/Article/details/gtfgcwvvlb.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jiagoushi.top/Article/details/gtipdzczcp.html

[A12] 字符串插值 / 格式化
来源：http://dali.fengsongda.top/Article/details/gtxeohqaps.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.chenzaomai.com/Article/details/gtxjflpjqb.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.gaohongyu789.top/Article/details/gtlvonyqhp.html

JS:   `Hello, ${name}!`
来源：http://dali.zhixingplan.top/Article/details/gtqgnibdff.html

TS:   `Hello, ${name}!`
来源：http://dali.vqdsnc.cn/Article/details/gtgdeqynew.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.cqqwz.cn/Article/details/gtmwryeaoe.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.wangdashe.top/Article/details/gtcvmwwwaj.html

Ruby: "Hello, #{name}!"
来源：http://dali.0kj1m.cn/Article/details/gtbniasvqo.html

C#:   $"Hello, {name}!"
来源：http://dali.jlsjyb.cn/Article/details/gtgezuqkee.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.cucudq.cn/Article/details/gtpjmbstgd.html

Py:   "第一行\n第二行"
来源：http://dali.jinqigufen.top/Article/details/gtjacdeoox.html

PHP:  "第一行\n第二行"
来源：http://dali.haohaochexian.top/Article/details/gtjctkzmll.html

JS:   "第一行\n第二行"
来源：http://dali.cashguo.top/Article/details/gtlgisqlvj.html

TS:   "第一行\n第二行"
来源：http://dali.yangfankeji.com/Article/details/gtkegpqqtz.html

Java: "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gtdbdvlxig.html

Go:   "第一行\n第二行"
来源：http://dali.ppjwa.cn/Article/details/gtogpdmiuy.html

Ruby: "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gtfgzydzfh.html

C#:   "第一行\n第二行"
来源：http://dali.gaohongyu789.top/Article/details/gtjkaakcvv.html

[A14] 注释写法
来源：http://dali.gaohongyu789.top/Article/details/gttplzyfzj.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.shzxlz.cn/Article/details/gtkeunqtqp.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.shangyingyoupin.top/Article/details/gtmjrtpnsq.html

JS:   // 单行；/* 多行 */
来源：http://dali.wangshuangyany.cn/Article/details/gtytcuzbgt.html

TS:   // 单行；/* 多行 */
来源：http://dali.snrcjt.cn/Article/details/gtrjjbuvol.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.ybcxt.top/Article/details/gtvhgesshs.html

Go:   // 单行；/* 多行 */
来源：http://dali.cucudq.cn/Article/details/gtplxwlmce.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgkpdxfv.html

C#:   // 单行；/* 多行 */
来源：http://dali.yuanzhike.top/Article/details/gtmxkkdqnd.html

[A15] 空值判断与默认值
来源：http://dali.cqqwz.cn/Article/details/gtrjugnzwk.html

Py:   value = data or "默认值"
来源：http://dali.ehwqpu.com/Article/details/gtvisngjjz.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.hnqzz.top/Article/details/gtghteoijn.html

JS:   const value = data ?? "默认值";
来源：http://dali.dashuyun.cn/Article/details/gthszwrkwz.html

TS:   const value = data ?? "默认值";
来源：http://dali.jiagoushi.top/Article/details/gtbduontyp.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.nwbrower.top/Article/details/gttskruwoo.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jinqigfzy.top/Article/details/gtmmnfdbau.html

Ruby: value = data || "默认值"
来源：http://dali.nanxuanxn.top/Article/details/gtkdwuxunw.html

C#:   var value = data ?? "默认值";
来源：http://dali.svipenyu.cn/Article/details/gtnvafgefy.html

[A16] 真假值判断规则
来源：http://dali.nwbrower.top/Article/details/gtarhmabns.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jiagoushi.top/Article/details/gtrieheebv.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.redwolf501.top/Article/details/gtpdixebgg.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.fengsongda.top/Article/details/gtzzfgfjth.html

TS:   if (!x) {}
来源：http://dali.aizwys.cn/Article/details/gtcsffirni.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhufgpmx.html


<!-- 参考信息 -->