代发 wailian999

[U93] JS：模板字符串
来源：http://dali.c1oappe.top/Article/details/gtfsyzknyj.html

`共 ${n} 条`
来源：http://dali.feifeiyinyue.top/Article/details/gtenxtavgu.html

[U94] JS：箭头函数
来源：http://dali.ydzc1.top/Article/details/gtrzwwnnts.html

const double = x => x * 2;
来源：http://dali.ydzc1.top/Article/details/gtjqlyrqdp.html

[U95] JS：Promise 包装
来源：http://dali.jqgufenzy.top/Article/details/gtrnawbvea.html

new Promise((resolve, reject) => {})
来源：http://dali.cdnleiting.top/Article/details/gtszquoewq.html

[U96] JS：async/await 与异常
来源：http://dali.shuidangran.top/Article/details/gtwahevmbd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gtbwsgdgml.html

[U97] JS：并发请求
来源：http://dali.tanke756.top/Article/details/gtwthiwfib.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gtrwzewfyd.html

[U98] JS：fetch 带 JSON
来源：http://dali.guowangkeji.top/Article/details/gtuqkjjyvm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yanxiufei.cn/Article/details/gtvmecdjxr.html

[U99] JS：事件监听
来源：http://dali.xinyue.icu/Article/details/gtodajkzzs.html

el.addEventListener("click", e => {})
来源：http://dali.feifeiyinyue.top/Article/details/gtnlhpebyu.html

[U100] JS：DOM 查询
来源：http://dali.chenjidiqi.icu/Article/details/gtzmhcsnxt.html

document.querySelector(".item")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvyvkuxj.html

[U101] JS：classList 操作
来源：http://dali.chenlongwang.top/Article/details/gttruvdsez.html

el.classList.toggle("active")
来源：http://dali.birdmap.top/Article/details/gtyxiezuyf.html

[U102] JS：本地存储
来源：http://dali.shangyingyoupin.top/Article/details/gtxrhilfci.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhongyouzk.top/Article/details/gtrhhstuuy.html

[U103] JS：定时器
来源：http://dali.zhixingplan.top/Article/details/gtvkivqazf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.kuanghao11.cn/Article/details/gtanfwxeqk.html

[U104] JS：防抖
来源：http://dali.wangshuangyany.cn/Article/details/gtifgxbnif.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gtdmzmworf.html

[U105] JS：节流
来源：http://dali.svipenyu.cn/Article/details/gtbitqzfmj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.chenzaomai.com/Article/details/gtatfwicsg.html

[U106] JS：日期格式化
来源：http://dali.xylfe.cn/Article/details/gtviauyvmn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shanyushiyangtech.top/Article/details/gtdktqwryu.html

[U107] JS：数字千分位
来源：http://dali.quarkkingdee.top/Article/details/gtlkjcqbpt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.birdmap.top/Article/details/gtuxpgthfr.html

[U108] JS：随机整数
来源：http://dali.gotoacloud.top/Article/details/gteqgfccbf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkjathfy.html

[U109] JS：数组分组
来源：http://dali.jinqigufen.top/Article/details/gtgpbjwjtb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhiwuduotai.top/Article/details/gtsjyppxxc.html

[U110] JS：数组分块
来源：http://dali.xuetiantiany.cn/Article/details/gtyvnyltxv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yuxming.cn/Article/details/gtdzwmzxol.html

[U111] JS：对象转 Map
来源：http://dali.sxryk.cn/Article/details/gthjarjecf.html

new Map(Object.entries(obj))
来源：http://dali.ehwqpu.com/Article/details/gtbdlijord.html

[U112] JS：字符串补位
来源：http://dali.yonumen.top/Article/details/gtkgtvymei.html

"7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtjxyndofm.html

[U113] JS：正则替换全部
来源：http://dali.nanxinkj.top/Article/details/gtyqtnczws.html

s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtjwjklryu.html

[U114] JS：JSON 深比较
来源：http://dali.shangyingyoupin.top/Article/details/gtmzwjpkfn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gogol.net.cn/Article/details/gtkpuuewza.html

[U115] JS：生成 UUID
来源：http://dali.sufxvd.cn/Article/details/gtdvbxgvlp.html

crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjhlztvm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.dashuyun.cn/Article/details/gtkbscktnu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ydzc1.top/Article/details/gtqmygbmud.html

[U117] JS：单元测试
来源：http://dali.meibo888.top/Article/details/gtvamfderx.html

npm i -D vitest;  npx vitest
来源：http://dali.yuanzhike.top/Article/details/gtlilyzsvv.html

[U118] JS：开发服务器
来源：http://dali.meibo888.top/Article/details/gtdhvdacxs.html

npm i -D vite;  npx vite
来源：http://dali.smart0.xyz/Article/details/gtvmvzvawu.html

[U119] JS：生产构建
来源：http://dali.zdqjudy.top/Article/details/gtveyvpkqj.html

npx vite build
来源：http://dali.ybcxt.top/Article/details/gtoftwimrp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.daxiang520.top/Article/details/gtdkdkmdtm.html

import.meta.env.VITE_API_URL
来源：http://dali.c1oappe.top/Article/details/gtygzggphq.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtrschxvlu.html

统计汇总
来源：http://dali.feifeiyinyue.top/Article/details/gteqerizfp.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtzcdtmyfq.html

按语言统计（条）：
来源：http://dali.hnqzz.top/Article/details/gtqphpsvac.html

Python ......... 252
来源：http://dali.jqgfzy.top/Article/details/gtnmmpwnfk.html

PHP ............ 252
来源：http://dali.sxryk.cn/Article/details/gtykjgbtkp.html

JavaScript ..... 252
来源：http://dali.shzxlz.cn/Article/details/gtqgsosbhh.html

TypeScript ..... 212
来源：http://dali.gzhubu.top/Article/details/gtifimwdid.html

Java ........... 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbxpcylq.html

Go ............. 212
来源：http://dali.cucudq.cn/Article/details/gtlphylwow.html

Ruby ........... 212
来源：http://dali.aibaodan.cn/Article/details/gtctpwjrgk.html

C# ............. 212
来源：http://dali.iojbl.cn/Article/details/gtaviqhajj.html

C .............. 30
来源：http://dali.pycfn.com/Article/details/gtmfnjqjiv.html

C++ ............ 30
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfoqsslow.html

SQL ............ 90
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwuxcnitb.html

Bash ........... 80
来源：http://dali.jinqigufen.top/Article/details/gtjazeyhfp.html

Kotlin ......... 15
来源：http://dali.quarkkingdee.top/Article/details/gtesmkqdwj.html

Swift .......... 15
来源：http://dali.tanke756.top/Article/details/gtkrhpnwyb.html

Lua ............ 10
来源：http://dali.jinqigufen.top/Article/details/gtzittzgiq.html

Perl ........... 10
来源：http://dali.xuanzx.com/Article/details/gtumgzavxo.html

Scala .......... 10
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxmplxqo.html

------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gtmfwgemcb.html

合计 ........... 2106 条
来源：http://dali.cheryme.top/Article/details/gtvhbkcrfl.html

按章节统计：
来源：http://dali.ppjwa.cn/Article/details/gtekfvacww.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yvedp.cn/Article/details/gtmyxugcde.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhiwuduotai.top/Article/details/gtdruyaqmr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.aibaodan.cn/Article/details/gthujbmkfl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jyoumei.cn/Article/details/gtxxmrcawm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawernzfs.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ivvv.top/Article/details/gtxajzkger.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.cheryme.top/Article/details/gtbssoyjfn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yj20258.top/Article/details/gtqqhpdnid.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gtzaajfbyb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gzhubu.top/Article/details/gtvvafvbeo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gthooiwvig.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gtyoydfkoa.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gtlcmurkqf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.pycfn.com/Article/details/gtgaxjfavg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpasiipq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gthrynkdrq.html

Q SQL 专题                              90
来源：http://dali.hywenlv.cn/Article/details/gtksfhiphh.html

R Bash 专题                             80
来源：http://dali.0kj1m.cn/Article/details/gttbdufaye.html

S C / C++ 专题                          60
来源：http://dali.hfpthk.cn/Article/details/gtbdceqnzn.html

T 其他语言补充                          60
来源：http://dali.ydzc1.top/Article/details/gtgzkiamsv.html

U 高频实用片段                         120
来源：http://dali.jyoumei.cn/Article/details/gtcxhqxehp.html

------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtcdgfybox.html

合计                                  2106 条
来源：http://dali.hammf.cn/Article/details/gtchcpxuhs.html

--------------------------------------------------------------------------------
来源：http://dali.yongpay.top/Article/details/gttaleoiaz.html

使用提醒
来源：http://dali.nanxuanxn.top/Article/details/gttgkyfadq.html

--------------------------------------------------------------------------------
来源：http://dali.chenzaomai.com/Article/details/gtvynlunir.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.dashuyun.cn/Article/details/gttndcmixe.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.vqdsnc.cn/Article/details/gtvzmnjllb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yvedp.cn/Article/details/gtprzzbqfq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xylfe.cn/Article/details/gtzbtorgjy.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ivvv.top/Article/details/gtpnnbjcvy.html

—— 文件结束 ——
来源：http://dali.nwbrower.top/Article/details/gtkpnpdhxm.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtljnciqyn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.nwbrower.top/Article/details/gtgcjyiron.html

Common Programming Examples Cheat Book
来源：http://dali.sysykeji.top/Article/details/gtrpgvefmw.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtvfbfribc.html

【收录内容】
来源：http://dali.redwolf501.top/Article/details/gtkmvsfwft.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.tianlin.xyz/Article/details/gtrhnktmjw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.guannengcc.top/Article/details/gtcpnqecqu.html

SQL · Bash · C · C++
来源：http://dali.zhixingplan.top/Article/details/gtxxxelxqo.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.chenjidiqi.icu/Article/details/gtzmpadind.html

【使用说明】
来源：http://dali.yonumen.top/Article/details/gtroelibtw.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.sufxvd.cn/Article/details/gtdpmuzpma.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jqgufenzy.top/Article/details/gtthtwylsk.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.gzhubu.top/Article/details/gtgeppexag.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.daxiang520.top/Article/details/gtoehvxaoq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.meibo888.top/Article/details/gtqohigndu.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yangfankeji.com/Article/details/gtidwoxygb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.andypj.xyz/Article/details/gtrdanwchd.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhongyouzk.top/Article/details/gtgakaurgn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hfpthk.cn/Article/details/gtlntelcrc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhengqikj.top/Article/details/gtdtjvsmpu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jqgfzy.top/Article/details/gtcpsfyjxk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hnxiangtu.top/Article/details/gtjcpkrjzk.html

【文件统计】
来源：http://dali.cucudq.cn/Article/details/gtnuodtawa.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yj20258888.top/Article/details/gtnoqofajg.html

--------------------------------------------------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtvnbmaiet.html

目  录
来源：http://dali.hysaishi.cn/Article/details/gtkdnbsait.html

--------------------------------------------------------------------------------
来源：http://dali.hnqzz.top/Article/details/gtpzsvpyts.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.mhx1999.top/Article/details/gtjdpqfbvu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yueranfly.top/Article/details/gtanycastm.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.gogol.net.cn/Article/details/gtmvuwazwa.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.nanxinkj.top/Article/details/gtfqrxszxa.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.gaohongyu789.top/Article/details/gtccwiidip.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.guannengcc.top/Article/details/gtpqfysiyw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gtfudoksja.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.vqdsnc.cn/Article/details/gticeazowr.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gtndhvafvw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yongpay.top/Article/details/gttvbndwhf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtwscjpcqt.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hysaishi.cn/Article/details/gtbaftqmtg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.ehwqpu.com/Article/details/gtpuopqsju.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtikxjbatr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jinqigfzy.top/Article/details/gtptnvnkvu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.quarkkingdee.top/Article/details/gtmvsftudb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.nwbrower.top/Article/details/gtummtbpaz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnnrstim.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhoulong.xyz/Article/details/gtmweqwluh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fzhhl.top/Article/details/gtsoqvnwjs.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrdgrpcm.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtncqbwram.html

A. 基础语法与类型
来源：http://dali.yueranfly.top/Article/details/gtsdksxcfw.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gthugghaeh.html

[A01] Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqiwfmqp.html

Py:   print("Hello, World!")
来源：http://dali.haohaochexian.top/Article/details/gtohofmltg.html

PHP:  echo "Hello, World!";
来源：http://dali.daxiang520.top/Article/details/gtbodlgcnb.html

JS:   console.log("Hello, World!");
来源：http://dali.jyoumei.cn/Article/details/gteiodpwnh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.316326.xyz/Article/details/gteefkdmmx.html

Java: System.out.println("Hello, World!");
来源：http://dali.tianlin.xyz/Article/details/gttgiqyhzo.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.snrcjt.cn/Article/details/gttnlmjdzn.html

Ruby: puts "Hello, World!"
来源：http://dali.guannengcc.top/Article/details/gtnflxivjc.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.haohaochexian.top/Article/details/gttvxgvsgl.html

[A02] 变量声明与赋值
来源：http://dali.guannengcc.top/Article/details/gtusqcybix.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jqgfzy.top/Article/details/gtuebchztl.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ivvv.top/Article/details/gtxcgnlaib.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.nanxinkj.top/Article/details/gtbueetniz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.kuanghao11.cn/Article/details/gttyoohzro.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yueranfly.top/Article/details/gtxowxmddg.html

Go:   name := "Alex"; age := 20
来源：http://dali.0kj1m.cn/Article/details/gtgnssrzwh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.meibo888.top/Article/details/gtrgsbswez.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.shuidangran.top/Article/details/gtkdqmfcov.html

[A03] 常量定义
来源：http://dali.yonumen.top/Article/details/gtkxfsugyk.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhiwuduotai.top/Article/details/gtqayhcwqx.html

PHP:  const PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtanoytqbv.html

JS:   const PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtmyubrxeq.html

TS:   const PI: number = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtynwizgkv.html

Java: static final double PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtlaewzbkz.html

Go:   const PI = 3.14159
来源：http://dali.316326.xyz/Article/details/gtlafozhlg.html

Ruby: PI = 3.14159
来源：http://dali.hongshengwenyu.top/Article/details/gtdjychzmd.html

C#:   const double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtcyaghspn.html

[A04] 判断变量类型
来源：http://dali.vqdsnc.cn/Article/details/gtpmbfbxuv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hammf.cn/Article/details/gtfieqjcbo.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.guowangkeji.top/Article/details/gtunvqoexe.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jiagoushi.top/Article/details/gttwsfmkux.html

TS:   typeof x; x instanceof Date
来源：http://dali.jinghuilouyu.cn/Article/details/gtwckhcxji.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jyoumei.cn/Article/details/gtodegzzau.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hongshengwenyu.top/Article/details/gtddlfktad.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ppjwa.cn/Article/details/gtdpmbvjzo.html

C#:   x.GetType().Name; x is int
来源：http://dali.hongshengwenyu.top/Article/details/gtesfapzeo.html

[A05] 整数除法与取模
来源：http://dali.c1oappe.top/Article/details/gtieeuziij.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.shuidangran.top/Article/details/gtzrcvhxmb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yueranfly.top/Article/details/gtxicanyty.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.andypj.xyz/Article/details/gthpsmtssm.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cashguo.top/Article/details/gtpyaxiudn.html

Java: 7 / 2; 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gtbrcqqszj.html

Go:   7 / 2; 7 % 2
来源：http://dali.bjfxy.top/Article/details/gtnjmlgyvk.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtmwvitfoh.html

C#:   7 / 2; 7 % 2
来源：http://dali.nwbrower.top/Article/details/gttqtppnda.html

[A06] 字符串转数字
来源：http://dali.yongpay.top/Article/details/gtzknzvrjq.html

Py:   int("42"); float("3.14")
来源：http://dali.svipenyu.cn/Article/details/gtqchpqrso.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.iojbl.cn/Article/details/gttqfmigrv.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jinqigfzy.top/Article/details/gtmolpmjit.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.birdmap.top/Article/details/gtttgnprpn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cheryme.top/Article/details/gtqrthgxzy.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jianghu66.top/Article/details/gtiwvutrjl.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.birdmap.top/Article/details/gtmikzumgm.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzoskeep.html

[A07] 数字转字符串
来源：http://dali.dashuyun.cn/Article/details/gtsutnxvey.html

Py:   str(42)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdupzlpuk.html

PHP:  (string) 42; strval(42)
来源：http://dali.fzhhl.top/Article/details/gtxxrulphb.html

JS:   String(42); (42).toString()
来源：http://dali.snrcjt.cn/Article/details/gtrpjebefc.html

TS:   String(42)
来源：http://dali.yuanzhike.top/Article/details/gtoenkptkb.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhengqikj.top/Article/details/gttqryfnkk.html

Go:   strconv.Itoa(42)
来源：http://dali.chenzaomai.com/Article/details/gtzcnqikss.html

Ruby: 42.to_s
来源：http://dali.yangfankeji.com/Article/details/gttjolhcse.html

C#:   42.ToString()
来源：http://dali.fengsongda.top/Article/details/gtbmepvyoy.html

[A08] 取整与四舍五入
来源：http://dali.redwolf501.top/Article/details/gtdjjhxxoa.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqprunvjl.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.birdmap.top/Article/details/gtmpaztjcw.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.ppjwa.cn/Article/details/gtvqwdpxvj.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.aizwys.cn/Article/details/gtyjxahqsb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.xinyue.icu/Article/details/gtspthmdnp.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.chenzaomai.com/Article/details/gtrjsogiiq.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yj20258.top/Article/details/gtxlhbnrqi.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.aibaodan.cn/Article/details/gtnczuerbm.html

[A09] 绝对值与最大最小值
来源：http://dali.jqgufenzy.top/Article/details/gtzttdtiwk.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtpkvmzluz.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtbctshyeo.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumkmeimv.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtmowqjezl.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gtnothkvgp.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zdqjudy.top/Article/details/gtnokubwmm.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.ybcxt.top/Article/details/gthbgikwtn.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gtylpxjbjx.html

[A10] 生成随机数
来源：http://dali.bjfxy.top/Article/details/gtzqmpntes.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yanxiufei.cn/Article/details/gtgyvbpaya.html

PHP:  random_int(1, 100);
来源：http://dali.zhongyouzk.top/Article/details/gtykwluegq.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.birdmap.top/Article/details/gtgsqebqbz.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.svipenyu.cn/Article/details/gtvmniyjld.html

Java: new Random().nextInt(100) + 1
来源：http://dali.hammf.cn/Article/details/gtjyuzlaby.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jinqigfzy.top/Article/details/gtfwsbsyjp.html

Ruby: rand(1..100)
来源：http://dali.shuidangran.top/Article/details/gthotklufr.html

C#:   new Random().Next(1, 101)
来源：http://dali.birdmap.top/Article/details/gtetxfckga.html

[A11] 条件表达式（三元）
来源：http://dali.fzhhl.top/Article/details/gtdhhqpqgf.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.chenlongwang.top/Article/details/gtnuvcpcwd.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zycfv.cn/Article/details/gthlkkllvo.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.wangshuangyany.cn/Article/details/gtqkqgeyam.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yuxming.cn/Article/details/gtlvxgsvef.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.guowangkeji.top/Article/details/gtoldmzmpe.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jlsjyb.cn/Article/details/gtbdzjwtml.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrjmpxdb.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhengqikj.top/Article/details/gtxtstojaw.html

[A12] 字符串插值 / 格式化
来源：http://dali.feifeiyinyue.top/Article/details/gtdofxeqsx.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.cqqwz.cn/Article/details/gtbvmmznok.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.sysykeji.top/Article/details/gttqpbacfs.html

JS:   `Hello, ${name}!`
来源：http://dali.jinghuilouyu.cn/Article/details/gtwuwbpjlb.html

TS:   `Hello, ${name}!`
来源：http://dali.gotoacloud.top/Article/details/gtglkhqhvm.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.cqqwz.cn/Article/details/gtnbhjubra.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yvedp.cn/Article/details/gthptyroow.html

Ruby: "Hello, #{name}!"
来源：http://dali.shuidangran.top/Article/details/gthybnejit.html

C#:   $"Hello, {name}!"
来源：http://dali.gzhubu.top/Article/details/gtnybpjmfo.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.mhx1999.top/Article/details/gtwsdduzqg.html

Py:   "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gtahyhtjnz.html

PHP:  "第一行\n第二行"
来源：http://dali.hfpthk.cn/Article/details/gtyorbopuh.html

JS:   "第一行\n第二行"
来源：http://dali.9152youxi.cn/Article/details/gtlmuamjsr.html

TS:   "第一行\n第二行"
来源：http://dali.xuanzx.com/Article/details/gtjxjqreqe.html

Java: "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gtqsistawn.html

Go:   "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdzutdytt.html

Ruby: "第一行\n第二行"
来源：http://dali.hammf.cn/Article/details/gtnyginuxb.html

C#:   "第一行\n第二行"
来源：http://dali.xylfe.cn/Article/details/gtyyhrhhbl.html

[A14] 注释写法
来源：http://dali.nanxinkj.top/Article/details/gtigaghqad.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.xylfe.cn/Article/details/gtkhrfpovf.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhengqikj.top/Article/details/gtkxkbvcsc.html

JS:   // 单行；/* 多行 */
来源：http://dali.daxiang520.top/Article/details/gtolghqnpu.html

TS:   // 单行；/* 多行 */
来源：http://dali.yuxming.cn/Article/details/gtlcyrnjqa.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.gaohongyu789.top/Article/details/gtalacujfe.html

Go:   // 单行；/* 多行 */
来源：http://dali.shzxlz.cn/Article/details/gtbmwxbitx.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yvedp.cn/Article/details/gterinzowv.html

C#:   // 单行；/* 多行 */
来源：http://dali.sweek.top/Article/details/gtiadhlbsq.html

[A15] 空值判断与默认值
来源：http://dali.jianghu66.top/Article/details/gtnahbhtxb.html

Py:   value = data or "默认值"
来源：http://dali.guowangkeji.top/Article/details/gtbzmscmcy.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yuxming.cn/Article/details/gtjhrjqtes.html

JS:   const value = data ?? "默认值";
来源：http://dali.ehwqpu.com/Article/details/gtrzspigyl.html

TS:   const value = data ?? "默认值";
来源：http://dali.kuanghao11.cn/Article/details/gtgvtywdor.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.c1oappe.top/Article/details/gtzpxhljln.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.havefunace.top/Article/details/gtqbtfdghb.html

Ruby: value = data || "默认值"
来源：http://dali.zhiwuduotai.top/Article/details/gtostaypkc.html

C#:   var value = data ?? "默认值";
来源：http://dali.fengsongda.top/Article/details/gthviqoukk.html

[A16] 真假值判断规则
来源：http://dali.haohaochexian.top/Article/details/gtnsbuiuvh.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gtlxqlxjqi.html


<!-- 参考信息 -->