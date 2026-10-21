代发 wailian999

[U89] JS：数组去重
来源：http://dali.xziqi.cn/Article/details/gtgsoulqfh.html

[...new Set(arr)]
来源：http://dali.gogol.net.cn/Article/details/gtkxekhvcv.html

[U90] JS：数字数组排序
来源：http://dali.yj20258.top/Article/details/gtxnfmdmdp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gthorkptnn.html

[U91] JS：对象键值遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtovyyxgzb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.quarkkingdee.top/Article/details/gtjyeebzky.html

[U92] JS：深拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gtvaqgfllu.html

structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gttyssvoqn.html

[U93] JS：模板字符串
来源：http://dali.xuanzx.com/Article/details/gtcmktxiyv.html

`共 ${n} 条`
来源：http://dali.snrcjt.cn/Article/details/gtujiyhktt.html

[U94] JS：箭头函数
来源：http://dali.jlsjyb.cn/Article/details/gtwxuhssvs.html

const double = x => x * 2;
来源：http://dali.cqqwz.cn/Article/details/gtdqtyyird.html

[U95] JS：Promise 包装
来源：http://dali.shuidangran.top/Article/details/gtpjfxagyl.html

new Promise((resolve, reject) => {})
来源：http://dali.jiagoushi.top/Article/details/gtyvxmqoqo.html

[U96] JS：async/await 与异常
来源：http://dali.yanxiufei.cn/Article/details/gtsjyjnigz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnvnenug.html

[U97] JS：并发请求
来源：http://dali.ppjwa.cn/Article/details/gtmhzbtuny.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gteofsjura.html

[U98] JS：fetch 带 JSON
来源：http://dali.jianghu66.top/Article/details/gtqceqjvxb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shuidangran.top/Article/details/gtlajqskgu.html

[U99] JS：事件监听
来源：http://dali.snrcjt.cn/Article/details/gtxjrpknwg.html

el.addEventListener("click", e => {})
来源：http://dali.haohaochexian.top/Article/details/gtwkvfjoac.html

[U100] JS：DOM 查询
来源：http://dali.shzxlz.cn/Article/details/gtbodsatue.html

document.querySelector(".item")
来源：http://dali.yuanzhike.top/Article/details/gtkviaqyid.html

[U101] JS：classList 操作
来源：http://dali.iojbl.cn/Article/details/gtnaezeqtp.html

el.classList.toggle("active")
来源：http://dali.hysaishi.cn/Article/details/gtipczjxkg.html

[U102] JS：本地存储
来源：http://dali.jinqigufen.top/Article/details/gtelhehlho.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.quarkkingdee.top/Article/details/gtdqgaprxe.html

[U103] JS：定时器
来源：http://dali.fengsongda.top/Article/details/gtvmwjyqog.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.svipenyu.cn/Article/details/gtthunrmdv.html

[U104] JS：防抖
来源：http://dali.9152youxi.cn/Article/details/gtpthtkczl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gtsoixqkmz.html

[U105] JS：节流
来源：http://dali.ybcxt.top/Article/details/gtponohipr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yvedp.cn/Article/details/gtcwqpivms.html

[U106] JS：日期格式化
来源：http://dali.ehwqpu.com/Article/details/gtkwefxncd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shzxlz.cn/Article/details/gtimzciwjp.html

[U107] JS：数字千分位
来源：http://dali.yueranfly.top/Article/details/gtxxcqyiwv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hnqzz.top/Article/details/gtzdbzohab.html

[U108] JS：随机整数
来源：http://dali.wangdashe.top/Article/details/gtwjasixbv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yvedp.cn/Article/details/gtzemyyiry.html

[U109] JS：数组分组
来源：http://dali.xziqi.cn/Article/details/gtptbltjqw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hfpthk.cn/Article/details/gtscdkmpal.html

[U110] JS：数组分块
来源：http://dali.ydzc1.top/Article/details/gtmfhdvyxt.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hongshengwenyu.top/Article/details/gtsehlbtsd.html

[U111] JS：对象转 Map
来源：http://dali.iojbl.cn/Article/details/gtzbpforzc.html

new Map(Object.entries(obj))
来源：http://dali.gotoacloud.top/Article/details/gtiyfybhdv.html

[U112] JS：字符串补位
来源：http://dali.shangyingyoupin.top/Article/details/gtpbbcwbab.html

"7".padStart(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtedkcdifq.html

[U113] JS：正则替换全部
来源：http://dali.bjfxy.top/Article/details/gtrwmdqman.html

s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtvmdtfrap.html

[U114] JS：JSON 深比较
来源：http://dali.cqqwz.cn/Article/details/gtfdorikdi.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gtvtllkjlk.html

[U115] JS：生成 UUID
来源：http://dali.redwolf501.top/Article/details/gtevchzmgq.html

crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gtjffetegv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jianghu66.top/Article/details/gtzfhdkaet.html

/** @param {string} name */ function f(name) {}
来源：http://dali.sweek.top/Article/details/gtarakwuts.html

[U117] JS：单元测试
来源：http://dali.shuidangran.top/Article/details/gtjoklcaej.html

npm i -D vitest;  npx vitest
来源：http://dali.wangshuangyany.cn/Article/details/gtfzujpchr.html

[U118] JS：开发服务器
来源：http://dali.mhx1999.top/Article/details/gtzunbgxbl.html

npm i -D vite;  npx vite
来源：http://dali.tian-w.cn/Article/details/gtbqcttamo.html

[U119] JS：生产构建
来源：http://dali.jyoumei.cn/Article/details/gtetwdovsb.html

npx vite build
来源：http://dali.yangfankeji.com/Article/details/gtlhfcwpxq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.daxiang520.top/Article/details/gtyfgaorsn.html

import.meta.env.VITE_API_URL
来源：http://dali.hongshengwenyu.top/Article/details/gtudjhzhuw.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gthdbsrflt.html

统计汇总
来源：http://dali.chenzaomai.com/Article/details/gttsodeeen.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtolgbwptx.html

按语言统计（条）：
来源：http://dali.gaohongyu789.top/Article/details/gtplfejoha.html

Python ......... 252
来源：http://dali.hongshengwenyu.top/Article/details/gtkhgnurwb.html

PHP ............ 252
来源：http://dali.jinqigufen.top/Article/details/gtzjaabwbu.html

JavaScript ..... 252
来源：http://dali.guannengcc.top/Article/details/gtoidceoah.html

TypeScript ..... 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydhdgzxt.html

Java ........... 212
来源：http://dali.zycfv.cn/Article/details/gtzvvaljyx.html

Go ............. 212
来源：http://dali.gaohongyu789.top/Article/details/gtilkhyusx.html

Ruby ........... 212
来源：http://dali.yuxming.cn/Article/details/gtgvctmxto.html

C# ............. 212
来源：http://dali.yj20258888.top/Article/details/gtpinplmtm.html

C .............. 30
来源：http://dali.vqdsnc.cn/Article/details/gtpewxupsy.html

C++ ............ 30
来源：http://dali.zhengqikj.top/Article/details/gtxaafmjqf.html

SQL ............ 90
来源：http://dali.jiagoushi.top/Article/details/gtolxnsump.html

Bash ........... 80
来源：http://dali.redwolf501.top/Article/details/gtgnxhcwfb.html

Kotlin ......... 15
来源：http://dali.wangdashe.top/Article/details/gtwiautnht.html

Swift .......... 15
来源：http://dali.zhixingplan.top/Article/details/gtlweovxhf.html

Lua ............ 10
来源：http://dali.xinyue.icu/Article/details/gtscrdffzz.html

Perl ........... 10
来源：http://dali.yueranfly.top/Article/details/gtgwtzylsh.html

Scala .......... 10
来源：http://dali.yuanzhike.top/Article/details/gtiammsdqn.html

------------------------------------
来源：http://dali.xuanzx.com/Article/details/gtcyhngaqd.html

合计 ........... 2106 条
来源：http://dali.yuxming.cn/Article/details/gtzsdcfdpf.html

按章节统计：
来源：http://dali.gogol.net.cn/Article/details/gtklzquejs.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cqqwz.cn/Article/details/gtppattmmz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yuxming.cn/Article/details/gtndlxtpco.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.quarkkingdee.top/Article/details/gtbxclyeje.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhixingplan.top/Article/details/gthuzuookz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.vqdsnc.cn/Article/details/gteoraygst.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.tanke756.top/Article/details/gtsyzffads.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ppjwa.cn/Article/details/gtwibmqrbh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.fengsongda.top/Article/details/gtzkzvbfdb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gtpuydqqyy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cdnleiting.top/Article/details/gtwipekqtj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gtggndmwfy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gtqctlhjzx.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gtimlfgknr.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shangyingyoupin.top/Article/details/gtnhmatlri.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xuanzx.com/Article/details/gtgvmrrrfi.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jqgufenzy.top/Article/details/gthdrwzdyg.html

Q SQL 专题                              90
来源：http://dali.shangyingyoupin.top/Article/details/gtqcwnrnte.html

R Bash 专题                             80
来源：http://dali.feifeiyinyue.top/Article/details/gtsmdhhhtn.html

S C / C++ 专题                          60
来源：http://dali.sweek.top/Article/details/gtcnpbynlg.html

T 其他语言补充                          60
来源：http://dali.ivvv.top/Article/details/gteerxbemm.html

U 高频实用片段                         120
来源：http://dali.xinyue.icu/Article/details/gtysisfbvc.html

------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gtutjcyqxk.html

合计                                  2106 条
来源：http://dali.jianghu66.top/Article/details/gtwuonpbyk.html

--------------------------------------------------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gtdpazljes.html

使用提醒
来源：http://dali.ehwqpu.com/Article/details/gtgsojbrfu.html

--------------------------------------------------------------------------------
来源：http://dali.xuanzx.com/Article/details/gtkdihtgqs.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.mhx1999.top/Article/details/gttmknzayn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.shangyingyoupin.top/Article/details/gteehsfrer.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.feifeiyinyue.top/Article/details/gttuehrbxt.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.feifeiyinyue.top/Article/details/gtitbvslre.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.guannengcc.top/Article/details/gteikjvjdq.html

—— 文件结束 ——
来源：http://dali.pengpengdd.cyou/Article/details/gtdomsceio.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gttuanuafz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yueranfly.top/Article/details/gtcqulshmo.html

Common Programming Examples Cheat Book
来源：http://dali.haohaochexian.top/Article/details/gtyzxubwtv.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gthozeelkl.html

【收录内容】
来源：http://dali.zycfv.cn/Article/details/gtrywgeabh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jinqigufen.top/Article/details/gtzlnublbw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jinghuilouyu.cn/Article/details/gtpyygixsj.html

SQL · Bash · C · C++
来源：http://dali.yanxiufei.cn/Article/details/gtsnnolsgu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hfpthk.cn/Article/details/gtaaoyrdzq.html

【使用说明】
来源：http://dali.jyoumei.cn/Article/details/gtbprccthz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.andypj.xyz/Article/details/gtcxdxluef.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.dashuyun.cn/Article/details/gtviqmnkqs.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hnqzz.top/Article/details/gtmtfayqdq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jqgfzy.top/Article/details/gttwskmftf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.sysykeji.top/Article/details/gtxxqcvdty.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.feifeiyinyue.top/Article/details/gthxxhmjyu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.9152youxi.cn/Article/details/gtexvpvvok.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jinqigfzy.top/Article/details/gtwhfujssd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yangfankeji.com/Article/details/gtelfqhkbx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.daria6918.cn/Article/details/gttgnxqhzn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.daxiang520.top/Article/details/gtmiyfvaeq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.daria6918.cn/Article/details/gtjemfjlpx.html

【文件统计】
来源：http://dali.snrcjt.cn/Article/details/gtreuiedii.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gaohongyu789.top/Article/details/gtyuscgqpk.html

--------------------------------------------------------------------------------
来源：http://dali.yvedp.cn/Article/details/gtenmncmpi.html

目  录
来源：http://dali.cdnleiting.top/Article/details/gtlojwfijo.html

--------------------------------------------------------------------------------
来源：http://dali.nwbrower.top/Article/details/gtnrpoashd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhongyouzk.top/Article/details/gtgrriplgd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.redwolf501.top/Article/details/gtzjvlnihm.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yueranfly.top/Article/details/gteoljrsai.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhixingplan.top/Article/details/gtdqgjyqjj.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.haohaochexian.top/Article/details/gtpowpgsfa.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.aizwys.cn/Article/details/gtxlhyvfiv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.sufxvd.cn/Article/details/gtstykwvzn.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jianghu66.top/Article/details/gtjlpgfoyf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zycfv.cn/Article/details/gtpwnijpxc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.wangdashe.top/Article/details/gtdawzwcio.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ehwqpu.com/Article/details/gtvrjtqcff.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.mhx1999.top/Article/details/gtxptbgtlo.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.tanke756.top/Article/details/gtnnidxmhk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtchoivzlw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yuxming.cn/Article/details/gtatvpnvzk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yj20258.top/Article/details/gtndwxkiev.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cdnleiting.top/Article/details/gtnypbpbhs.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jianghu66.top/Article/details/gtzixkahig.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.vqdsnc.cn/Article/details/gtcgxaccbo.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dianchejie.cn/Article/details/gtgposdmsu.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sysykeji.top/Article/details/gtpehdtdgs.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtjzyjfewn.html

A. 基础语法与类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbxcajemg.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gttnzbydus.html

[A01] Hello World
来源：http://dali.xylfe.cn/Article/details/gtvmllqedo.html

Py:   print("Hello, World!")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwdgjfvx.html

PHP:  echo "Hello, World!";
来源：http://dali.yj20258888.top/Article/details/gtgyepjzdl.html

JS:   console.log("Hello, World!");
来源：http://dali.wangdashe.top/Article/details/gtyjgxkabp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmzyzsbp.html

Java: System.out.println("Hello, World!");
来源：http://dali.yvedp.cn/Article/details/gtijpjfiub.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zycfv.cn/Article/details/gtpnnbumht.html

Ruby: puts "Hello, World!"
来源：http://dali.zhoulong.xyz/Article/details/gtkdarccua.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.dashuyun.cn/Article/details/gtgfpkgedp.html

[A02] 变量声明与赋值
来源：http://dali.ehwqpu.com/Article/details/gtvljnbjut.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hammf.cn/Article/details/gtzwznzexe.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.shangyingyoupin.top/Article/details/gtjxjkwact.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.pycfn.com/Article/details/gtsfifjdih.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hysaishi.cn/Article/details/gtwltnanve.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hywenlv.cn/Article/details/gtluvojivs.html

Go:   name := "Alex"; age := 20
来源：http://dali.hongshengwenyu.top/Article/details/gtqetuuqrq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hongshengwenyu.top/Article/details/gtojpmjahh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.mhx1999.top/Article/details/gtnohlejmt.html

[A03] 常量定义
来源：http://dali.andypj.xyz/Article/details/gtmngkkpmf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujceqjjg.html

PHP:  const PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtpshvayri.html

JS:   const PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gtejcoqpzl.html

TS:   const PI: number = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtlaoinypb.html

Java: static final double PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gtshbeetpz.html

Go:   const PI = 3.14159
来源：http://dali.vqdsnc.cn/Article/details/gtarzubvzw.html

Ruby: PI = 3.14159
来源：http://dali.yangfankeji.com/Article/details/gtfskbaqce.html

C#:   const double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtoixsnifc.html

[A04] 判断变量类型
来源：http://dali.zhengqikj.top/Article/details/gtiayujdbz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yonumen.top/Article/details/gtfyddgyxg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yangfankeji.com/Article/details/gtlfarzias.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xuanzx.com/Article/details/gtbuapatag.html

TS:   typeof x; x instanceof Date
来源：http://dali.guowangkeji.top/Article/details/gtvwmvsdgd.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.wangdashe.top/Article/details/gtuuuuikwh.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhiwuduotai.top/Article/details/gtrabpyzaw.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.chenlongwang.top/Article/details/gtpvxbjofi.html

C#:   x.GetType().Name; x is int
来源：http://dali.zdqjudy.top/Article/details/gtwvlpmwwb.html

[A05] 整数除法与取模
来源：http://dali.yj202588.top/Article/details/gtcmrbycpu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yj20258.top/Article/details/gtqsjjzove.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.daria6918.cn/Article/details/gtjetfuyrm.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ivvv.top/Article/details/gtxnvinnek.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yongpay.top/Article/details/gtbjudmhit.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gttyzdqxpx.html

Go:   7 / 2; 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmtxkxag.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtfoqjytal.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gtjglqzypu.html

[A06] 字符串转数字
来源：http://dali.tianlin.xyz/Article/details/gtvigjzlrj.html

Py:   int("42"); float("3.14")
来源：http://dali.ivvv.top/Article/details/gtovulvazo.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.pycfn.com/Article/details/gtihqnnvwe.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.gogol.net.cn/Article/details/gtxqkandsx.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.smart0.xyz/Article/details/gtizctjvmj.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.aibaodan.cn/Article/details/gttrsrattt.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yj202588.top/Article/details/gtlmpdpyor.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhongyouzk.top/Article/details/gtbpgklznh.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.redwolf501.top/Article/details/gtdlrdypgu.html

[A07] 数字转字符串
来源：http://dali.yj20258888.top/Article/details/gtbtddwamb.html

Py:   str(42)
来源：http://dali.redwolf501.top/Article/details/gtoakvrscp.html

PHP:  (string) 42; strval(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqfmkrhk.html

JS:   String(42); (42).toString()
来源：http://dali.xziqi.cn/Article/details/gtmafqwxbp.html

TS:   String(42)
来源：http://dali.shuidangran.top/Article/details/gthzsecgwi.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.tanke756.top/Article/details/gtvdksjwkp.html

Go:   strconv.Itoa(42)
来源：http://dali.chenlongwang.top/Article/details/gtossgmntx.html

Ruby: 42.to_s
来源：http://dali.fzhhl.top/Article/details/gtuejanttn.html

C#:   42.ToString()
来源：http://dali.zdqjudy.top/Article/details/gtshljotcl.html

[A08] 取整与四舍五入
来源：http://dali.chenjidiqi.icu/Article/details/gthcpgsgcw.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hywenlv.cn/Article/details/gtzxkzpzxj.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.gotoacloud.top/Article/details/gtwmlwited.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.hongshengwenyu.top/Article/details/gtqzvvdihw.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.iojbl.cn/Article/details/gtizjzxciw.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.iojbl.cn/Article/details/gtdikigllo.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.shzxlz.cn/Article/details/gtvclyxqcy.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.redwolf501.top/Article/details/gtjiukjrth.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.vqdsnc.cn/Article/details/gtieqwddtd.html

[A09] 绝对值与最大最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvglgpfoq.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzsufbme.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.redwolf501.top/Article/details/gtbufsddhq.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.aizwys.cn/Article/details/gthqxixwxe.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.ybcxt.top/Article/details/gttxusspkb.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.mhx1999.top/Article/details/gtjlhixxkd.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.fengsongda.top/Article/details/gtwiafjccl.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.dianchejie.cn/Article/details/gtozyqdzuk.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gtsuxzsabx.html

[A10] 生成随机数
来源：http://dali.gotoacloud.top/Article/details/gtupmpqkla.html

Py:   import random; random.randint(1, 100)
来源：http://dali.dashuyun.cn/Article/details/gtcoixteqy.html

PHP:  random_int(1, 100);
来源：http://dali.0kj1m.cn/Article/details/gtxipudjbj.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yueranfly.top/Article/details/gtsomdpwcc.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.fengsongda.top/Article/details/gtgipvjlnz.html

Java: new Random().nextInt(100) + 1
来源：http://dali.mhx1999.top/Article/details/gtougldbvm.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hysaishi.cn/Article/details/gtjjwmgceb.html

Ruby: rand(1..100)
来源：http://dali.xinyue.icu/Article/details/gteoruoyry.html

C#:   new Random().Next(1, 101)
来源：http://dali.ydzc1.top/Article/details/gticsyjeqj.html

[A11] 条件表达式（三元）
来源：http://dali.sxryk.cn/Article/details/gtpxtkofcg.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.hammf.cn/Article/details/gtnsngtlfn.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.aizwys.cn/Article/details/gtuvbhrxtj.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.shzxlz.cn/Article/details/gtwfjtlvke.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.chenlongwang.top/Article/details/gtmtzmjevm.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.sweek.top/Article/details/gtfikkvysw.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.feifeiyinyue.top/Article/details/gtgpctgtrt.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.gzhubu.top/Article/details/gtfrqrnftb.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yongpay.top/Article/details/gtqqvqmaxj.html

[A12] 字符串插值 / 格式化
来源：http://dali.jlsjyb.cn/Article/details/gtrfwixcue.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.cashguo.top/Article/details/gttzipgpwp.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yj20258.top/Article/details/gtdmvvlpil.html

JS:   `Hello, ${name}!`
来源：http://dali.iojbl.cn/Article/details/gtrbxujbkr.html

TS:   `Hello, ${name}!`
来源：http://dali.vqdsnc.cn/Article/details/gtrjmhplae.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.iojbl.cn/Article/details/gtmheyuaau.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.hammf.cn/Article/details/gtmcvoqjgw.html

Ruby: "Hello, #{name}!"
来源：http://dali.sweek.top/Article/details/gttdcpuojh.html

C#:   $"Hello, {name}!"
来源：http://dali.jlsjyb.cn/Article/details/gtsciyixzx.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.nanxinkj.top/Article/details/gtklwwoynw.html

Py:   "第一行\n第二行"
来源：http://dali.zhengqikj.top/Article/details/gtvnuzebmb.html

PHP:  "第一行\n第二行"
来源：http://dali.jinghuilouyu.cn/Article/details/gtsatnbazw.html

JS:   "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gtffjbbmoy.html

TS:   "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gthmxvsbog.html

Java: "第一行\n第二行"
来源：http://dali.cdnleiting.top/Article/details/gtwvuwtfot.html

Go:   "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gtfnaptpzk.html

Ruby: "第一行\n第二行"
来源：http://dali.jqgufenzy.top/Article/details/gtpejftrox.html

C#:   "第一行\n第二行"
来源：http://dali.jinqigfzy.top/Article/details/gtkkvglqxm.html

[A14] 注释写法
来源：http://dali.yanxiufei.cn/Article/details/gtsktpjdsn.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.haohaochexian.top/Article/details/gtmmofpstb.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmhzbnfu.html

JS:   // 单行；/* 多行 */
来源：http://dali.aizwys.cn/Article/details/gtaqeecmbz.html

TS:   // 单行；/* 多行 */
来源：http://dali.yj20258.top/Article/details/gtackgviqf.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.xziqi.cn/Article/details/gtmjayphew.html

Go:   // 单行；/* 多行 */
来源：http://dali.daxiang520.top/Article/details/gtymtmmmbo.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.bjfxy.top/Article/details/gtedoeltnc.html

C#:   // 单行；/* 多行 */
来源：http://dali.birdmap.top/Article/details/gtjitmdytb.html

[A15] 空值判断与默认值
来源：http://dali.tanke756.top/Article/details/gtilnkbskh.html

Py:   value = data or "默认值"
来源：http://dali.yuxming.cn/Article/details/gtxglgvapk.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.daxiang520.top/Article/details/gtctlsjcih.html


<!-- 参考信息 -->