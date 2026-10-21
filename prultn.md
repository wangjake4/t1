代发 wailian999

[U93] JS：模板字符串
来源：http://dali.yuanzhike.top/Article/details/gtmwcgxsuh.html

`共 ${n} 条`
来源：http://dali.shuidangran.top/Article/details/gtydxqvqse.html

[U94] JS：箭头函数
来源：http://dali.zhixingplan.top/Article/details/gtnguyrqvv.html

const double = x => x * 2;
来源：http://dali.andypj.xyz/Article/details/gtyaaxuqpu.html

[U95] JS：Promise 包装
来源：http://dali.jqgfzy.top/Article/details/gtyqbifixh.html

new Promise((resolve, reject) => {})
来源：http://dali.nanxinkj.top/Article/details/gtzgyniavs.html

[U96] JS：async/await 与异常
来源：http://dali.xylfe.cn/Article/details/gtbfrkibac.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtjjfpzlpu.html

[U97] JS：并发请求
来源：http://dali.hnqzz.top/Article/details/gtghwdhywv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtmpjtmuhj.html

[U98] JS：fetch 带 JSON
来源：http://dali.jinqigfzy.top/Article/details/gtkydnhiwk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yuxming.cn/Article/details/gtibqhlrfh.html

[U99] JS：事件监听
来源：http://dali.chenzaomai.com/Article/details/gtaopljwhd.html

el.addEventListener("click", e => {})
来源：http://dali.wangshuangyany.cn/Article/details/gtdypkykwq.html

[U100] JS：DOM 查询
来源：http://dali.meibo888.top/Article/details/gtdwxzvqhv.html

document.querySelector(".item")
来源：http://dali.jyoumei.cn/Article/details/gtwnygsxpv.html

[U101] JS：classList 操作
来源：http://dali.dianchejie.cn/Article/details/gtsexozbpv.html

el.classList.toggle("active")
来源：http://dali.dianchejie.cn/Article/details/gtzbdwodsl.html

[U102] JS：本地存储
来源：http://dali.zhaomingkeji.xyz/Article/details/gteccdhras.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yj20258888.top/Article/details/gtlqxwhmew.html

[U103] JS：定时器
来源：http://dali.c1oappe.top/Article/details/gtkxrqrcsz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhiwuduotai.top/Article/details/gtrnnrivjv.html

[U104] JS：防抖
来源：http://dali.jlsjyb.cn/Article/details/gtqyqyjloa.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gtdkckjczr.html

[U105] JS：节流
来源：http://dali.tian-w.cn/Article/details/gtcefucxfw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hywenlv.cn/Article/details/gtsdleuras.html

[U106] JS：日期格式化
来源：http://dali.dashuyun.cn/Article/details/gtwyrhvygf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yonumen.top/Article/details/gtsvpmsaoy.html

[U107] JS：数字千分位
来源：http://dali.yongpay.top/Article/details/gtdyzypenh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.tian-w.cn/Article/details/gtzlmmjjjd.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gtgkhkkjsk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaiqvavgp.html

[U109] JS：数组分组
来源：http://dali.jlsjyb.cn/Article/details/gtpchuleda.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbggahra.html

[U110] JS：数组分块
来源：http://dali.nanxuanxn.top/Article/details/gtfkppfxcs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.chenjidiqi.icu/Article/details/gtzvazhtul.html

[U111] JS：对象转 Map
来源：http://dali.jinqigfzy.top/Article/details/gtkgfkrlve.html

new Map(Object.entries(obj))
来源：http://dali.aibaodan.cn/Article/details/gtjykuxcsu.html

[U112] JS：字符串补位
来源：http://dali.iojbl.cn/Article/details/gtkulxhumw.html

"7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtcsqhyjeo.html

[U113] JS：正则替换全部
来源：http://dali.c1oappe.top/Article/details/gtrakrxkdf.html

s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjvchplj.html

[U114] JS：JSON 深比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzqvbeane.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.9152youxi.cn/Article/details/gtvxxwwdms.html

[U115] JS：生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gtbwuqcyqi.html

crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gtlxinimga.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gaohongyu789.top/Article/details/gtfaeesfaf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.mhx1999.top/Article/details/gtqsqkwwbr.html

[U117] JS：单元测试
来源：http://dali.hongshengwenyu.top/Article/details/gtigeehhew.html

npm i -D vitest;  npx vitest
来源：http://dali.iojbl.cn/Article/details/gtvhwlzqpb.html

[U118] JS：开发服务器
来源：http://dali.quarkkingdee.top/Article/details/gtttauiaai.html

npm i -D vite;  npx vite
来源：http://dali.jqgfzy.top/Article/details/gtvssswemv.html

[U119] JS：生产构建
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifdtklwl.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gtzfnozpnp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yueranfly.top/Article/details/gtvjwiurvi.html

import.meta.env.VITE_API_URL
来源：http://dali.cqqwz.cn/Article/details/gtakwuyonj.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtenanmpyc.html

统计汇总
来源：http://dali.daria6918.cn/Article/details/gtkzddfvrb.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtbkfftwen.html

按语言统计（条）：
来源：http://dali.yvedp.cn/Article/details/gtffetzkoe.html

Python ......... 252
来源：http://dali.chenlongwang.top/Article/details/gtkncxvumx.html

PHP ............ 252
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhshggbi.html

JavaScript ..... 252
来源：http://dali.gzhubu.top/Article/details/gtlrnrdcaq.html

TypeScript ..... 212
来源：http://dali.fengsongda.top/Article/details/gthkcaulkv.html

Java ........... 212
来源：http://dali.jqgfzy.top/Article/details/gtinllidhk.html

Go ............. 212
来源：http://dali.nanxuanxn.top/Article/details/gttumrawxy.html

Ruby ........... 212
来源：http://dali.yj20258888.top/Article/details/gtzpfuftxy.html

C# ............. 212
来源：http://dali.dashuyun.cn/Article/details/gtxjndsiqg.html

C .............. 30
来源：http://dali.jqgfzy.top/Article/details/gtisexmayq.html

C++ ............ 30
来源：http://dali.dashuyun.cn/Article/details/gtovovajcl.html

SQL ............ 90
来源：http://dali.tianlin.xyz/Article/details/gtsuajvylk.html

Bash ........... 80
来源：http://dali.gotoacloud.top/Article/details/gtmbeeiqgf.html

Kotlin ......... 15
来源：http://dali.wangshuangyany.cn/Article/details/gtdtjlyide.html

Swift .......... 15
来源：http://dali.sxryk.cn/Article/details/gtfidssyrt.html

Lua ............ 10
来源：http://dali.svipenyu.cn/Article/details/gtmwrzbzqu.html

Perl ........... 10
来源：http://dali.yonumen.top/Article/details/gthkzlrsgr.html

Scala .......... 10
来源：http://dali.aibaodan.cn/Article/details/gtzagkvcjl.html

------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdynobajo.html

合计 ........... 2106 条
来源：http://dali.quarkkingdee.top/Article/details/gtytcvgivl.html

按章节统计：
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzausjzi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gaohongyu789.top/Article/details/gtifcojukt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jlsjyb.cn/Article/details/gtewtgphra.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.tianlin.xyz/Article/details/gturkfwdsj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cqqwz.cn/Article/details/gtohjznycn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cucudq.cn/Article/details/gtuxjmwwty.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cheryme.top/Article/details/gtjmrvnqvz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tianlin.xyz/Article/details/gtjepwwjii.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhblqdka.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gtwrfsrsat.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shzxlz.cn/Article/details/gtqusjxriw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gtuujnexrb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gtqsjwuxur.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gtlldwpcwk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jyoumei.cn/Article/details/gtrqghyont.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jinqigfzy.top/Article/details/gtusgiblla.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gtvkmplapf.html

Q SQL 专题                              90
来源：http://dali.jiagoushi.top/Article/details/gtasklzktg.html

R Bash 专题                             80
来源：http://dali.meibo888.top/Article/details/gtzvucqcps.html

S C / C++ 专题                          60
来源：http://dali.zhiwuduotai.top/Article/details/gtstxyxarz.html

T 其他语言补充                          60
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctbtfgbq.html

U 高频实用片段                         120
来源：http://dali.sweek.top/Article/details/gtjxmtmbpc.html

------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gtnkqpljiu.html

合计                                  2106 条
来源：http://dali.yuanzhike.top/Article/details/gtxxnhniup.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtpxaxjrul.html

使用提醒
来源：http://dali.ehwqpu.com/Article/details/gtusygwvut.html

--------------------------------------------------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gtbsvpjmiz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhiwuduotai.top/Article/details/gtcjkmdrpm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.guowangkeji.top/Article/details/gtsqkepzjt.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.tian-w.cn/Article/details/gtdigszrzt.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jianghu66.top/Article/details/gtzwscyusx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.sufxvd.cn/Article/details/gtlejglpnt.html

—— 文件结束 ——
来源：http://dali.jinghuilouyu.cn/Article/details/gtabqclhuu.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gthllyvaeq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cdnleiting.top/Article/details/gtblvypwvx.html

Common Programming Examples Cheat Book
来源：http://dali.zhiwuduotai.top/Article/details/gtzwyaxbyh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtfdqvovzx.html

【收录内容】
来源：http://dali.sysykeji.top/Article/details/gtcwujvfyf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.havefunace.top/Article/details/gtuspvltjs.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.chenzaomai.com/Article/details/gtnksekglk.html

SQL · Bash · C · C++
来源：http://dali.hysaishi.cn/Article/details/gtfbogdsek.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhiwuduotai.top/Article/details/gtmvvanchg.html

【使用说明】
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcrulubx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.meibo888.top/Article/details/gtcebsvsuc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.sweek.top/Article/details/gtxgvirhzo.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yueranfly.top/Article/details/gtfgcvwwgi.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.fzhhl.top/Article/details/gtokcxmpnx.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.quarkkingdee.top/Article/details/gtbmhmugjc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.havefunace.top/Article/details/gtvlcryekf.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.guannengcc.top/Article/details/gtcnpwqjte.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hnxiangtu.top/Article/details/gtvjgkjncu.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cashguo.top/Article/details/gtwqlqoofd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yongpay.top/Article/details/gtdymtwmjs.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.aizwys.cn/Article/details/gtouflsyas.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.fzhhl.top/Article/details/gtxwsagkzo.html

【文件统计】
来源：http://dali.havefunace.top/Article/details/gtbcrgzkoo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gzhubu.top/Article/details/gtnvuxiyvw.html

--------------------------------------------------------------------------------
来源：http://dali.fengsongda.top/Article/details/gtwdseznxe.html

目  录
来源：http://dali.feifeiyinyue.top/Article/details/gtcdljppyh.html

--------------------------------------------------------------------------------
来源：http://dali.cucudq.cn/Article/details/gtwxrciogx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahlxdzsr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvxxrzov.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xuanzx.com/Article/details/gtmdbxghjg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yangfankeji.com/Article/details/gtnungwsxr.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ydzc1.top/Article/details/gtxmbvinog.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.gotoacloud.top/Article/details/gtcjiwcmko.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ehwqpu.com/Article/details/gtwjdpixfy.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.guannengcc.top/Article/details/gtafmsyuij.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gtgxlluflg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.andypj.xyz/Article/details/gtykcobnso.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yangfankeji.com/Article/details/gtewnuaeic.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gtrothgyrl.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gtfkvjumyq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yvedp.cn/Article/details/gtcrauzxoe.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sufxvd.cn/Article/details/gtkhczqcba.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gtatgddwbl.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.fengsongda.top/Article/details/gtvckemzjf.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.kuanghao11.cn/Article/details/gtjqxlupvx.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jianghu66.top/Article/details/gtyxhlrxng.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xylfe.cn/Article/details/gtmayvzauw.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jyoumei.cn/Article/details/gtxahkhfzq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtsfobavhv.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gtrbyfnqek.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxojqrix.html

[A01] Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtiqaapibh.html

Py:   print("Hello, World!")
来源：http://dali.daria6918.cn/Article/details/gtsdylmerg.html

PHP:  echo "Hello, World!";
来源：http://dali.zhoulong.xyz/Article/details/gtwhrpftbu.html

JS:   console.log("Hello, World!");
来源：http://dali.dianchejie.cn/Article/details/gtfqaczxoq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.9152youxi.cn/Article/details/gthwzhcoxm.html

Java: System.out.println("Hello, World!");
来源：http://dali.gogol.net.cn/Article/details/gtqwijyeuy.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yuxming.cn/Article/details/gtidynyrob.html

Ruby: puts "Hello, World!"
来源：http://dali.ybcxt.top/Article/details/gtifpwbfuu.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yuanzhike.top/Article/details/gtplygqlbp.html

[A02] 变量声明与赋值
来源：http://dali.cheryme.top/Article/details/gtlgbwafhs.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.aizwys.cn/Article/details/gtufvxxrzp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xylfe.cn/Article/details/gteklymiib.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yueranfly.top/Article/details/gtksenntee.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.chenlongwang.top/Article/details/gtppmnztqd.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.gotoacloud.top/Article/details/gtcvkdczbj.html

Go:   name := "Alex"; age := 20
来源：http://dali.fzhhl.top/Article/details/gtlltdkaqh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hongshengwenyu.top/Article/details/gtngxmcwvd.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yueranfly.top/Article/details/gtzjpsavuk.html

[A03] 常量定义
来源：http://dali.dashuyun.cn/Article/details/gtaxuebjht.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cucudq.cn/Article/details/gtsnnisgun.html

PHP:  const PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gtcdjvayfh.html

JS:   const PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtiyhotbfw.html

TS:   const PI: number = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gtmoazqxeh.html

Java: static final double PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmiqmxzbg.html

Go:   const PI = 3.14159
来源：http://dali.havefunace.top/Article/details/gtcaretcgb.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gtzxbfbrll.html

C#:   const double PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtrdidmngp.html

[A04] 判断变量类型
来源：http://dali.wangshuangyany.cn/Article/details/gtobjagpnh.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.nwbrower.top/Article/details/gtdtakfsqt.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.316326.xyz/Article/details/gtrkkzhlwo.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jyoumei.cn/Article/details/gtuwbvwhkz.html

TS:   typeof x; x instanceof Date
来源：http://dali.shuidangran.top/Article/details/gtcnelrecy.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.nanxinkj.top/Article/details/gtvpkaxvzn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shanyushiyangtech.top/Article/details/gtknsmatpt.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaujbwpyh.html

C#:   x.GetType().Name; x is int
来源：http://dali.andypj.xyz/Article/details/gtjmbzzwnx.html

[A05] 整数除法与取模
来源：http://dali.yonumen.top/Article/details/gtpcxahndr.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.tian-w.cn/Article/details/gtllxaznyb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gtbvhdckyo.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gtrpgpwxgx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.nanxuanxn.top/Article/details/gtkatruduy.html

Java: 7 / 2; 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gtfsoqejrk.html

Go:   7 / 2; 7 % 2
来源：http://dali.havefunace.top/Article/details/gtdvhuqcqf.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gtpknathbn.html

C#:   7 / 2; 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gtojycscga.html

[A06] 字符串转数字
来源：http://dali.chenjidiqi.icu/Article/details/gtukqcnlsn.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gtunaucefn.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.andypj.xyz/Article/details/gtfhpqwtdr.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.smart0.xyz/Article/details/gthszfzgrz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.9152youxi.cn/Article/details/gtisvmxhhr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhixingplan.top/Article/details/gtkfgigtcl.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yuanzhike.top/Article/details/gtsprdbecj.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.shzxlz.cn/Article/details/gtncxenfvx.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.haohaochexian.top/Article/details/gtjpxjobnw.html

[A07] 数字转字符串
来源：http://dali.daxiang520.top/Article/details/gtgnyawavr.html

Py:   str(42)
来源：http://dali.jiagoushi.top/Article/details/gtahfdckiz.html

PHP:  (string) 42; strval(42)
来源：http://dali.yj20258.top/Article/details/gtzjydbtsa.html

JS:   String(42); (42).toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtzxaylgqi.html

TS:   String(42)
来源：http://dali.yvedp.cn/Article/details/gtmmpynjwj.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zycfv.cn/Article/details/gtmjutmffn.html

Go:   strconv.Itoa(42)
来源：http://dali.yj20258.top/Article/details/gtyvamecrp.html

Ruby: 42.to_s
来源：http://dali.guowangkeji.top/Article/details/gtvoontncp.html

C#:   42.ToString()
来源：http://dali.ivvv.top/Article/details/gtjusgfrnc.html

[A08] 取整与四舍五入
来源：http://dali.yj202588.top/Article/details/gtfdcrbaty.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.9152youxi.cn/Article/details/gttwedpxrr.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ybcxt.top/Article/details/gtnxbytdaf.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.gogol.net.cn/Article/details/gtyagkusoa.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.vqdsnc.cn/Article/details/gtaabzmoxl.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yonumen.top/Article/details/gtrpxyxaqy.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yanxiufei.cn/Article/details/gtpmsqdcqd.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.aibaodan.cn/Article/details/gtwwpveglt.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zdqjudy.top/Article/details/gtomuglsca.html

[A09] 绝对值与最大最小值
来源：http://dali.sysykeji.top/Article/details/gtwgnjraog.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.daria6918.cn/Article/details/gtoxskzkru.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gtrrszgtqh.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gtiuakzpjb.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmmquzcq.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.ivvv.top/Article/details/gtcorpfnkz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.andypj.xyz/Article/details/gtzivjwluf.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jinqigfzy.top/Article/details/gtpeovrnru.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gtojncvfpk.html

[A10] 生成随机数
来源：http://dali.ppjwa.cn/Article/details/gtvnhnixxb.html

Py:   import random; random.randint(1, 100)
来源：http://dali.meibo888.top/Article/details/gtkuovhjef.html

PHP:  random_int(1, 100);
来源：http://dali.smart0.xyz/Article/details/gtpjtivxsk.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.gotoacloud.top/Article/details/gtiqzgijje.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xuetiantiany.cn/Article/details/gtxmasyiqi.html

Java: new Random().nextInt(100) + 1
来源：http://dali.guowangkeji.top/Article/details/gtkryyxthl.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.dashuyun.cn/Article/details/gtrarbfreg.html

Ruby: rand(1..100)
来源：http://dali.daxiang520.top/Article/details/gteclxzvvi.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpdadsott.html

[A11] 条件表达式（三元）
来源：http://dali.zhoulong.xyz/Article/details/gtljzfowvf.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jlsjyb.cn/Article/details/gtliwzfjax.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.quarkkingdee.top/Article/details/gtqdclyxif.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhiwuduotai.top/Article/details/gtsyvvgejk.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.feifeiyinyue.top/Article/details/gtjqkvyohj.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.kuanghao11.cn/Article/details/gtdqgurjwj.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yongpay.top/Article/details/gtrablgcem.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.shzxlz.cn/Article/details/gtkxzlhfka.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.sysykeji.top/Article/details/gtulvbxyrg.html

[A12] 字符串插值 / 格式化
来源：http://dali.mhx1999.top/Article/details/gtdskmkued.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.daxiang520.top/Article/details/gtijdsbplk.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yonumen.top/Article/details/gttbmvfyaf.html

JS:   `Hello, ${name}!`
来源：http://dali.zhixingplan.top/Article/details/gtcmlqzkqh.html

TS:   `Hello, ${name}!`
来源：http://dali.cheryme.top/Article/details/gtbythamux.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yonumen.top/Article/details/gtidmynubo.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.mhx1999.top/Article/details/gtxslqkcwz.html

Ruby: "Hello, #{name}!"
来源：http://dali.xziqi.cn/Article/details/gtkguguwhr.html

C#:   $"Hello, {name}!"
来源：http://dali.yuanzhike.top/Article/details/gtwzhigjvc.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbdqhbuu.html

Py:   "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gtwkvkjjfv.html

PHP:  "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gtfoywhrqj.html

JS:   "第一行\n第二行"
来源：http://dali.jinqigufen.top/Article/details/gtegbaxcng.html

TS:   "第一行\n第二行"
来源：http://dali.hysaishi.cn/Article/details/gtyphuelxj.html

Java: "第一行\n第二行"
来源：http://dali.haohaochexian.top/Article/details/gtcoxcoxov.html

Go:   "第一行\n第二行"
来源：http://dali.daxiang520.top/Article/details/gtoziwqggb.html

Ruby: "第一行\n第二行"
来源：http://dali.sufxvd.cn/Article/details/gtmzgqdtik.html

C#:   "第一行\n第二行"
来源：http://dali.hywenlv.cn/Article/details/gtrgsnoehx.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gtjiqpjtrg.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.wangshuangyany.cn/Article/details/gtyospvchl.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jinqigfzy.top/Article/details/gtronvovfm.html

JS:   // 单行；/* 多行 */
来源：http://dali.guowangkeji.top/Article/details/gtoatbtvkl.html

TS:   // 单行；/* 多行 */
来源：http://dali.xuanzx.com/Article/details/gtqctbhjiu.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.sysykeji.top/Article/details/gtgfjdrksw.html

Go:   // 单行；/* 多行 */
来源：http://dali.cdnleiting.top/Article/details/gtwdqqfqme.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.ybcxt.top/Article/details/gtlcawurgy.html

C#:   // 单行；/* 多行 */
来源：http://dali.andypj.xyz/Article/details/gtbipqxxvy.html

[A15] 空值判断与默认值
来源：http://dali.gogol.net.cn/Article/details/gtmgntvihx.html

Py:   value = data or "默认值"
来源：http://dali.nwbrower.top/Article/details/gtjqxiaawu.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.meibo888.top/Article/details/gtuqysuahl.html

JS:   const value = data ?? "默认值";
来源：http://dali.cucudq.cn/Article/details/gtpmxtqrmq.html

TS:   const value = data ?? "默认值";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtmlyvdm.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhixingplan.top/Article/details/gtnnudmfoc.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yonumen.top/Article/details/gtchyskfqo.html

Ruby: value = data || "默认值"
来源：http://dali.wangdashe.top/Article/details/gtknuwfqlo.html

C#:   var value = data ?? "默认值";
来源：http://dali.gotoacloud.top/Article/details/gtftpgfbaw.html

[A16] 真假值判断规则
来源：http://dali.cqqwz.cn/Article/details/gtxchmjhuy.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.xylfe.cn/Article/details/gtfymtvzgr.html


<!-- 参考信息 -->