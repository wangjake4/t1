代发 wailian999

[U95] JS：Promise 包装
来源：http://dali.svipenyu.cn/Article/details/gtykmksckp.html

new Promise((resolve, reject) => {})
来源：http://dali.gotoacloud.top/Article/details/gttwqywzxs.html

[U96] JS：async/await 与异常
来源：http://dali.zhiwuduotai.top/Article/details/gtstdtckgk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtcrifvebl.html

[U97] JS：并发请求
来源：http://dali.sufxvd.cn/Article/details/gtmlqpkpdo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gtswqfkzaj.html

[U98] JS：fetch 带 JSON
来源：http://dali.gzhubu.top/Article/details/gtdcqliapl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqjcylkl.html

[U99] JS：事件监听
来源：http://dali.xylfe.cn/Article/details/gthhcnajxg.html

el.addEventListener("click", e => {})
来源：http://dali.jinqigufen.top/Article/details/gtcexyvufq.html

[U100] JS：DOM 查询
来源：http://dali.yj202588.top/Article/details/gtlzsmykwk.html

document.querySelector(".item")
来源：http://dali.gotoacloud.top/Article/details/gtgkoogqqi.html

[U101] JS：classList 操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfxxmlosj.html

el.classList.toggle("active")
来源：http://dali.mhx1999.top/Article/details/gtjlwmtosu.html

[U102] JS：本地存储
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvjofdhp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.tian-w.cn/Article/details/gtwzbkrujw.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gtzbdzempu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.9152youxi.cn/Article/details/gtdrcklyel.html

[U104] JS：防抖
来源：http://dali.gaohongyu789.top/Article/details/gtrgpiiqlz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrqfwnpzj.html

[U105] JS：节流
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfppgmzhy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdnxmrxj.html

[U106] JS：日期格式化
来源：http://dali.daria6918.cn/Article/details/gtazfdoncf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.nanxinkj.top/Article/details/gtibbxajlz.html

[U107] JS：数字千分位
来源：http://dali.xinyue.icu/Article/details/gtfhbhooxg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.andypj.xyz/Article/details/gtnmsxpgwj.html

[U108] JS：随机整数
来源：http://dali.mhx1999.top/Article/details/gtslulaylj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.tianlin.xyz/Article/details/gtkamhyatu.html

[U109] JS：数组分组
来源：http://dali.cqqwz.cn/Article/details/gtfflhqzlp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jqgufenzy.top/Article/details/gtbcmufvsx.html

[U110] JS：数组分块
来源：http://dali.dashuyun.cn/Article/details/gtrrexlznc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.chenlongwang.top/Article/details/gtmgchmajy.html

[U111] JS：对象转 Map
来源：http://dali.tanke756.top/Article/details/gtduvccape.html

new Map(Object.entries(obj))
来源：http://dali.chenjidiqi.icu/Article/details/gtpomvwizn.html

[U112] JS：字符串补位
来源：http://dali.gogol.net.cn/Article/details/gtzejztnon.html

"7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgyfwvmsm.html

[U113] JS：正则替换全部
来源：http://dali.meibo888.top/Article/details/gtqktxhyfj.html

s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtdiulzblq.html

[U114] JS：JSON 深比较
来源：http://dali.hammf.cn/Article/details/gtwyyquamf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fzhhl.top/Article/details/gthvbddyec.html

[U115] JS：生成 UUID
来源：http://dali.gzhubu.top/Article/details/gtpnyqcqas.html

crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gtoalcgnkh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yj20258888.top/Article/details/gtytupbfqk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.birdmap.top/Article/details/gtxoqtxvvy.html

[U117] JS：单元测试
来源：http://dali.hnxiangtu.top/Article/details/gtencglvkp.html

npm i -D vitest;  npx vitest
来源：http://dali.zdqjudy.top/Article/details/gtjbsxhzxa.html

[U118] JS：开发服务器
来源：http://dali.chenzaomai.com/Article/details/gthfkwtare.html

npm i -D vite;  npx vite
来源：http://dali.hysaishi.cn/Article/details/gtyqhwzbvt.html

[U119] JS：生产构建
来源：http://dali.redwolf501.top/Article/details/gtrwqweuyy.html

npx vite build
来源：http://dali.xuetiantiany.cn/Article/details/gthktycffb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.fengsongda.top/Article/details/gtrhhrpesh.html

import.meta.env.VITE_API_URL
来源：http://dali.yuanzhike.top/Article/details/gtsrdqgkue.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gttwwqdgyo.html

统计汇总
来源：http://dali.snrcjt.cn/Article/details/gtkncrpidm.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrubgtbsh.html

按语言统计（条）：
来源：http://dali.cdnleiting.top/Article/details/gtkotnkoyc.html

Python ......... 252
来源：http://dali.vqdsnc.cn/Article/details/gtcvdtqrne.html

PHP ............ 252
来源：http://dali.meibo888.top/Article/details/gteavdlazt.html

JavaScript ..... 252
来源：http://dali.hnqzz.top/Article/details/gtxtivjvgs.html

TypeScript ..... 212
来源：http://dali.daxiang520.top/Article/details/gtshukeptn.html

Java ........... 212
来源：http://dali.gogol.net.cn/Article/details/gtisxoagzu.html

Go ............. 212
来源：http://dali.gogol.net.cn/Article/details/gtkmpfvvfo.html

Ruby ........... 212
来源：http://dali.yuanzhike.top/Article/details/gtclduzgvz.html

C# ............. 212
来源：http://dali.c1oappe.top/Article/details/gtdespincl.html

C .............. 30
来源：http://dali.jqgfzy.top/Article/details/gtcwhbvviu.html

C++ ............ 30
来源：http://dali.yvedp.cn/Article/details/gtctfoyvou.html

SQL ............ 90
来源：http://dali.cucudq.cn/Article/details/gtqvdihdqr.html

Bash ........... 80
来源：http://dali.cheryme.top/Article/details/gtnxzekahe.html

Kotlin ......... 15
来源：http://dali.zycfv.cn/Article/details/gtwddyfljt.html

Swift .......... 15
来源：http://dali.dianchejie.cn/Article/details/gtvbsgsvko.html

Lua ............ 10
来源：http://dali.gaohongyu789.top/Article/details/gtbebxymjp.html

Perl ........... 10
来源：http://dali.jinqigfzy.top/Article/details/gtifwgaoxd.html

Scala .......... 10
来源：http://dali.jlsjyb.cn/Article/details/gthhkhctek.html

------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gtayayipme.html

合计 ........... 2106 条
来源：http://dali.birdmap.top/Article/details/gtgochihac.html

按章节统计：
来源：http://dali.yangfankeji.com/Article/details/gtmbjmkjky.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hnxiangtu.top/Article/details/gtoeoigopp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.9152youxi.cn/Article/details/gtugwbutfh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gtjcqhxiwc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.daria6918.cn/Article/details/gtuozvzoag.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xylfe.cn/Article/details/gtaxmgbpnh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yangfankeji.com/Article/details/gtoeoxrunp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.snrcjt.cn/Article/details/gtrgqbxikt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqqfzbeht.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqimivrir.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yueranfly.top/Article/details/gtizzygjua.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gtpfdlsuec.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gttxtkiqwk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzhxktef.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhengqikj.top/Article/details/gtabhlmpez.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.tian-w.cn/Article/details/gtrrjeuffn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtrwuyyuzk.html

Q SQL 专题                              90
来源：http://dali.jqgfzy.top/Article/details/gtotcdigmb.html

R Bash 专题                             80
来源：http://dali.ywan-chungtsiang.top/Article/details/gtguocfvzp.html

S C / C++ 专题                          60
来源：http://dali.cucudq.cn/Article/details/gtogafoxaw.html

T 其他语言补充                          60
来源：http://dali.zhoulong.xyz/Article/details/gtwxbtfksj.html

U 高频实用片段                         120
来源：http://dali.chenjidiqi.icu/Article/details/gtypsybmlg.html

------------------------------------
来源：http://dali.zycfv.cn/Article/details/gtcabndomc.html

合计                                  2106 条
来源：http://dali.tian-w.cn/Article/details/gtfzvnzhlj.html

--------------------------------------------------------------------------------
来源：http://dali.aizwys.cn/Article/details/gtypryxrvm.html

使用提醒
来源：http://dali.haohaochexian.top/Article/details/gtotvvjawt.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtkrumzjpe.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.sxryk.cn/Article/details/gtbshwbvon.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jiagoushi.top/Article/details/gtfiochmdt.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jianghu66.top/Article/details/gtmzipazld.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.dianchejie.cn/Article/details/gtcwkhpmaj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.vqdsnc.cn/Article/details/gteonhprde.html

—— 文件结束 ——
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhvixbdl.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzgtsiek.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cheryme.top/Article/details/gtlavyleid.html

Common Programming Examples Cheat Book
来源：http://dali.9152youxi.cn/Article/details/gtdrsntxtr.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtadzqtfrb.html

【收录内容】
来源：http://dali.yongpay.top/Article/details/gtalttizzp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.nanxinkj.top/Article/details/gtpfezuppk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jqgufenzy.top/Article/details/gtrfaxqydw.html

SQL · Bash · C · C++
来源：http://dali.sufxvd.cn/Article/details/gttbngaqvv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ydzc1.top/Article/details/gtwnfjencl.html

【使用说明】
来源：http://dali.xylfe.cn/Article/details/gtgcarzasv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.wangshuangyany.cn/Article/details/gtaflhtvza.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgozcroe.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.chenjidiqi.icu/Article/details/gtednifvhy.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.nanxuanxn.top/Article/details/gtyuuttdcf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.svipenyu.cn/Article/details/gtjcrpgmhf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yuxming.cn/Article/details/gtusutbryi.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.daxiang520.top/Article/details/gtngjoxxyl.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhoulong.xyz/Article/details/gtqhmtoubf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.pycfn.com/Article/details/gtposgdhjb.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.birdmap.top/Article/details/gtwimbkrqo.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.cdnleiting.top/Article/details/gtflzgzvpa.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.havefunace.top/Article/details/gtkgmgncrq.html

【文件统计】
来源：http://dali.daxiang520.top/Article/details/gtdmggulny.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.chenjidiqi.icu/Article/details/gtjrkyblmi.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gtybipkcxm.html

目  录
来源：http://dali.guannengcc.top/Article/details/gtxxsldgxf.html

--------------------------------------------------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gtcofaetdx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfytdrpqr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.gaohongyu789.top/Article/details/gtwwyvulij.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.sufxvd.cn/Article/details/gtzmjliskd.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.fengsongda.top/Article/details/gtxeemwrsp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yj20258888.top/Article/details/gtvppxnhjv.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yuxming.cn/Article/details/gtylwiqoxl.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.tian-w.cn/Article/details/gtupbtfwit.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.kuanghao11.cn/Article/details/gttdcnyknl.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.tanke756.top/Article/details/gtburolvwi.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shzxlz.cn/Article/details/gtnanajxeg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hywenlv.cn/Article/details/gtjoxuwomq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gtvhsfrrvr.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gtrbwnbzdt.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xuanzx.com/Article/details/gtwyyzkyps.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ybcxt.top/Article/details/gtlctnmarw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gtqnuscaxn.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.nanxuanxn.top/Article/details/gtgkdpwjpi.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yj20258.top/Article/details/gtexzkqaau.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgobxbff.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sufxvd.cn/Article/details/gtdygmwuad.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hysaishi.cn/Article/details/gtceefcmau.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtjsxbqahz.html

A. 基础语法与类型
来源：http://dali.andypj.xyz/Article/details/gtjndjgpoe.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtvdslzgse.html

[A01] Hello World
来源：http://dali.meibo888.top/Article/details/gtlxqereku.html

Py:   print("Hello, World!")
来源：http://dali.jyoumei.cn/Article/details/gtrfsktikk.html

PHP:  echo "Hello, World!";
来源：http://dali.nwbrower.top/Article/details/gtphfxzrgl.html

JS:   console.log("Hello, World!");
来源：http://dali.jianghu66.top/Article/details/gtgxmbhgto.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xinyue.icu/Article/details/gtmsliiwcv.html

Java: System.out.println("Hello, World!");
来源：http://dali.tian-w.cn/Article/details/gtfkwyisqf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.shzxlz.cn/Article/details/gttyytvmkl.html

Ruby: puts "Hello, World!"
来源：http://dali.zhixingplan.top/Article/details/gtprpcwflo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yj20258888.top/Article/details/gtkjtbmdoz.html

[A02] 变量声明与赋值
来源：http://dali.andypj.xyz/Article/details/gtxjgcbgyy.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.dianchejie.cn/Article/details/gteoduimbu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.dashuyun.cn/Article/details/gtvdigpqis.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cucudq.cn/Article/details/gthkvicjfp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.daria6918.cn/Article/details/gtceeubayf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yj20258.top/Article/details/gtohdlzkqh.html

Go:   name := "Alex"; age := 20
来源：http://dali.hywenlv.cn/Article/details/gtaexjxiiv.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gogol.net.cn/Article/details/gtwckeavlh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.svipenyu.cn/Article/details/gtbvivpihh.html

[A03] 常量定义
来源：http://dali.svipenyu.cn/Article/details/gtdksrmqoe.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.sxryk.cn/Article/details/gtxntfzpsw.html

PHP:  const PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtuezuobxv.html

JS:   const PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtlqxkitsm.html

TS:   const PI: number = 3.14159;
来源：http://dali.yj20258.top/Article/details/gtkiwkstnm.html

Java: static final double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtebyhzlob.html

Go:   const PI = 3.14159
来源：http://dali.yj202588.top/Article/details/gtyikvpubg.html

Ruby: PI = 3.14159
来源：http://dali.hongshengwenyu.top/Article/details/gtwhhnqjxn.html

C#:   const double PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtznqtbsqz.html

[A04] 判断变量类型
来源：http://dali.xylfe.cn/Article/details/gtvwdwenzt.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.fengsongda.top/Article/details/gthldhjcbe.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zdqjudy.top/Article/details/gtmjoexvlr.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hnqzz.top/Article/details/gtnbfglkaq.html

TS:   typeof x; x instanceof Date
来源：http://dali.wangshuangyany.cn/Article/details/gtwjonozdd.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zycfv.cn/Article/details/gtjrpzoocc.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.nanxuanxn.top/Article/details/gtbfmomzil.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ivvv.top/Article/details/gtlphiruwg.html

C#:   x.GetType().Name; x is int
来源：http://dali.birdmap.top/Article/details/gtznhlhaqj.html

[A05] 整数除法与取模
来源：http://dali.svipenyu.cn/Article/details/gtfueifmnt.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtpzzlfcaa.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.wangdashe.top/Article/details/gtfvcgqscm.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gtajtshbfy.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xinyue.icu/Article/details/gtvwzanpwj.html

Java: 7 / 2; 7 % 2
来源：http://dali.shuidangran.top/Article/details/gtamdjrnop.html

Go:   7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gtoxbdwnyv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gtnmhdtitx.html

C#:   7 / 2; 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtrgvebyhb.html

[A06] 字符串转数字
来源：http://dali.jianghu66.top/Article/details/gtmigrgxho.html

Py:   int("42"); float("3.14")
来源：http://dali.c1oappe.top/Article/details/gtllxeuwvu.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.vqdsnc.cn/Article/details/gtnqprgrrc.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jianghu66.top/Article/details/gtsxvnfxjk.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.gotoacloud.top/Article/details/gtmacytscl.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.redwolf501.top/Article/details/gtlhnflckg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.chenjidiqi.icu/Article/details/gtrxqaqpbl.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.daxiang520.top/Article/details/gtqfqvtltl.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.smart0.xyz/Article/details/gttfwloxpr.html

[A07] 数字转字符串
来源：http://dali.cdnleiting.top/Article/details/gtwclaumtv.html

Py:   str(42)
来源：http://dali.tian-w.cn/Article/details/gtkdgeubrw.html

PHP:  (string) 42; strval(42)
来源：http://dali.vqdsnc.cn/Article/details/gtryjyyxzb.html

JS:   String(42); (42).toString()
来源：http://dali.gogol.net.cn/Article/details/gtjsxewqtn.html

TS:   String(42)
来源：http://dali.cucudq.cn/Article/details/gtmyahexru.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.316326.xyz/Article/details/gtbluemgkn.html

Go:   strconv.Itoa(42)
来源：http://dali.yongpay.top/Article/details/gtoezikcfy.html

Ruby: 42.to_s
来源：http://dali.sufxvd.cn/Article/details/gtgpkddqzy.html

C#:   42.ToString()
来源：http://dali.fengsongda.top/Article/details/gtklhfkhqh.html

[A08] 取整与四舍五入
来源：http://dali.havefunace.top/Article/details/gtqkfuziht.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gtbnasyubk.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.iojbl.cn/Article/details/gttpivegnj.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.xuetiantiany.cn/Article/details/gtfonjiuem.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.gotoacloud.top/Article/details/gtdvvitqav.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hysaishi.cn/Article/details/gtdquutpmz.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yvedp.cn/Article/details/gtcgzlriry.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.vqdsnc.cn/Article/details/gtftnidyda.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hnqzz.top/Article/details/gtgpvepnqr.html

[A09] 绝对值与最大最小值
来源：http://dali.zhoulong.xyz/Article/details/gtcxmmebdi.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.tian-w.cn/Article/details/gtttjwvgsa.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gtsuzaclwn.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnheogzhz.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gtrmlauxhp.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yonumen.top/Article/details/gtwbsgqerc.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yanxiufei.cn/Article/details/gtrvmafocx.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhiwuduotai.top/Article/details/gtwwbrjavr.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.guannengcc.top/Article/details/gtrrwtqzwt.html

[A10] 生成随机数
来源：http://dali.haohaochexian.top/Article/details/gtwlwnuhlp.html

Py:   import random; random.randint(1, 100)
来源：http://dali.fzhhl.top/Article/details/gtnpewfsvz.html

PHP:  random_int(1, 100);
来源：http://dali.hfpthk.cn/Article/details/gtibepeept.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hysaishi.cn/Article/details/gtdnyaaadd.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jqgfzy.top/Article/details/gtpiptljil.html

Java: new Random().nextInt(100) + 1
来源：http://dali.hywenlv.cn/Article/details/gtqxhlnzuo.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.iojbl.cn/Article/details/gtbpdspjfk.html

Ruby: rand(1..100)
来源：http://dali.xziqi.cn/Article/details/gtablmtcvq.html

C#:   new Random().Next(1, 101)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhrqnwlb.html

[A11] 条件表达式（三元）
来源：http://dali.xuetiantiany.cn/Article/details/gtuhslqary.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jyoumei.cn/Article/details/gthkvozwre.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gtibtlebuv.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.daria6918.cn/Article/details/gtwtdtphwd.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.hongshengwenyu.top/Article/details/gtmnboqjtz.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.wangshuangyany.cn/Article/details/gtdfocccyr.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.fzhhl.top/Article/details/gttenyxprz.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.guannengcc.top/Article/details/gtlxbmdfuu.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.smart0.xyz/Article/details/gtdzphaiol.html

[A12] 字符串插值 / 格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtebysorbs.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yangfankeji.com/Article/details/gtvdqxcvds.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.vqdsnc.cn/Article/details/gtlicowrdc.html

JS:   `Hello, ${name}!`
来源：http://dali.yj20258888.top/Article/details/gtgvpdcnim.html

TS:   `Hello, ${name}!`
来源：http://dali.aibaodan.cn/Article/details/gtzrysucym.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yj20258888.top/Article/details/gtpifxjpzq.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yuxming.cn/Article/details/gttoujtvvg.html

Ruby: "Hello, #{name}!"
来源：http://dali.tanke756.top/Article/details/gtjowfoftd.html

C#:   $"Hello, {name}!"
来源：http://dali.mhx1999.top/Article/details/gtqpzpeczl.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.cashguo.top/Article/details/gtnvplhrmu.html

Py:   "第一行\n第二行"
来源：http://dali.nanxinkj.top/Article/details/gtdyiltgcr.html

PHP:  "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gtmcozwgzl.html

JS:   "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gtqhyjbkrp.html

TS:   "第一行\n第二行"
来源：http://dali.9152youxi.cn/Article/details/gtibbhsqhu.html

Java: "第一行\n第二行"
来源：http://dali.chenlongwang.top/Article/details/gtcyvxgcqa.html

Go:   "第一行\n第二行"
来源：http://dali.gaohongyu789.top/Article/details/gtxqhbilgg.html

Ruby: "第一行\n第二行"
来源：http://dali.hnxiangtu.top/Article/details/gtqscmxuqh.html

C#:   "第一行\n第二行"
来源：http://dali.shuidangran.top/Article/details/gtsurtudhw.html

[A14] 注释写法
来源：http://dali.jinqigfzy.top/Article/details/gtawlehvfc.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.aizwys.cn/Article/details/gtylbxczqu.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.feifeiyinyue.top/Article/details/gtxowfsujy.html

JS:   // 单行；/* 多行 */
来源：http://dali.nanxuanxn.top/Article/details/gtoonvkoxa.html

TS:   // 单行；/* 多行 */
来源：http://dali.ivvv.top/Article/details/gtwnigvhdh.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhiwuduotai.top/Article/details/gtlhztvooo.html

Go:   // 单行；/* 多行 */
来源：http://dali.jiagoushi.top/Article/details/gtczalwvvy.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hammf.cn/Article/details/gtpyxqiakc.html

C#:   // 单行；/* 多行 */
来源：http://dali.sweek.top/Article/details/gtvnrqirwc.html

[A15] 空值判断与默认值
来源：http://dali.dashuyun.cn/Article/details/gtrbbpfzar.html

Py:   value = data or "默认值"
来源：http://dali.9152youxi.cn/Article/details/gtbvzmfrgd.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.hfpthk.cn/Article/details/gtmzbdbmzd.html

JS:   const value = data ?? "默认值";
来源：http://dali.hnxiangtu.top/Article/details/gtqwkwgvtl.html

TS:   const value = data ?? "默认值";
来源：http://dali.jqgfzy.top/Article/details/gtodsyobee.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.chenjidiqi.icu/Article/details/gtasxxydhd.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhoulong.xyz/Article/details/gtwcpooppr.html

Ruby: value = data || "默认值"
来源：http://dali.yj20258.top/Article/details/gtvxajxcnb.html

C#:   var value = data ?? "默认值";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdroiwqw.html

[A16] 真假值判断规则
来源：http://dali.ydzc1.top/Article/details/gtdvwtyzsh.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yuanzhike.top/Article/details/gtlqqzwpfz.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jinqigfzy.top/Article/details/gtmaszijrh.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.gogol.net.cn/Article/details/gtddiphnoy.html

TS:   if (!x) {}
来源：http://dali.hywenlv.cn/Article/details/gtkvukwbxb.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.xylfe.cn/Article/details/gtnbxlnxeu.html


<!-- 参考信息 -->