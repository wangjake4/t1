代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.zhixingplan.top/Article/details/gtolqluico.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xziqi.cn/Article/details/gtffdnpaqo.html

[U92] JS：深拷贝
来源：http://dali.tianlin.xyz/Article/details/gtmyvgijot.html

structuredClone(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtqqmzlyze.html

[U93] JS：模板字符串
来源：http://dali.xuanzx.com/Article/details/gtrshfhrxo.html

`共 ${n} 条`
来源：http://dali.zhixingplan.top/Article/details/gtnsegreje.html

[U94] JS：箭头函数
来源：http://dali.bjfxy.top/Article/details/gtsduqjynh.html

const double = x => x * 2;
来源：http://dali.pycfn.com/Article/details/gtvregaekp.html

[U95] JS：Promise 包装
来源：http://dali.tianlin.xyz/Article/details/gtydstyyck.html

new Promise((resolve, reject) => {})
来源：http://dali.jianghu66.top/Article/details/gtwmfketpk.html

[U96] JS：async/await 与异常
来源：http://dali.chenlongwang.top/Article/details/gtosopatis.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtqafclkcg.html

[U97] JS：并发请求
来源：http://dali.quarkkingdee.top/Article/details/gtqckwfdbh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxajqkzkz.html

[U98] JS：fetch 带 JSON
来源：http://dali.ivvv.top/Article/details/gtavdmvmcd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xylfe.cn/Article/details/gtnsbhzzfp.html

[U99] JS：事件监听
来源：http://dali.yongpay.top/Article/details/gtwinsprjs.html

el.addEventListener("click", e => {})
来源：http://dali.ppjwa.cn/Article/details/gtrrswyxid.html

[U100] JS：DOM 查询
来源：http://dali.hywenlv.cn/Article/details/gtfzgrjofj.html

document.querySelector(".item")
来源：http://dali.chenlongwang.top/Article/details/gthcamrasw.html

[U101] JS：classList 操作
来源：http://dali.sweek.top/Article/details/gtctatgelf.html

el.classList.toggle("active")
来源：http://dali.chenzaomai.com/Article/details/gtrmsvvogu.html

[U102] JS：本地存储
来源：http://dali.andypj.xyz/Article/details/gtnvxfevvu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.aizwys.cn/Article/details/gtadtqzwxw.html

[U103] JS：定时器
来源：http://dali.jlsjyb.cn/Article/details/gtexcvzjyj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cashguo.top/Article/details/gtashptzau.html

[U104] JS：防抖
来源：http://dali.xuetiantiany.cn/Article/details/gtgrubdkmv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhtgpxuu.html

[U105] JS：节流
来源：http://dali.ehwqpu.com/Article/details/gtjhiykeej.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.guannengcc.top/Article/details/gtwmyrwmgd.html

[U106] JS：日期格式化
来源：http://dali.bjfxy.top/Article/details/gtzlhhcntl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.wangshuangyany.cn/Article/details/gtkqxshamy.html

[U107] JS：数字千分位
来源：http://dali.hammf.cn/Article/details/gthrvfhine.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.aibaodan.cn/Article/details/gthzclvkrt.html

[U108] JS：随机整数
来源：http://dali.yuanzhike.top/Article/details/gtgurqdxcj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shuidangran.top/Article/details/gtopjisocm.html

[U109] JS：数组分组
来源：http://dali.yuxming.cn/Article/details/gtmomsqfnz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hnxiangtu.top/Article/details/gtudslchzr.html

[U110] JS：数组分块
来源：http://dali.zhongyouzk.top/Article/details/gtgtpegqpv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.andypj.xyz/Article/details/gtnfixetfg.html

[U111] JS：对象转 Map
来源：http://dali.cdnleiting.top/Article/details/gtzwubtuas.html

new Map(Object.entries(obj))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqaoobrk.html

[U112] JS：字符串补位
来源：http://dali.quarkkingdee.top/Article/details/gthdbwxmva.html

"7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gthqqazkfz.html

[U113] JS：正则替换全部
来源：http://dali.jinghuilouyu.cn/Article/details/gtkiwuqnxj.html

s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtkzrhkgvv.html

[U114] JS：JSON 深比较
来源：http://dali.sufxvd.cn/Article/details/gtamjtnxsz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhoulong.xyz/Article/details/gtovpgasga.html

[U115] JS：生成 UUID
来源：http://dali.svipenyu.cn/Article/details/gtpjkdkgsv.html

crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtvvwclqpg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgslbzqu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gogol.net.cn/Article/details/gtxkgxnevt.html

[U117] JS：单元测试
来源：http://dali.tian-w.cn/Article/details/gthygdgufs.html

npm i -D vitest;  npx vitest
来源：http://dali.guannengcc.top/Article/details/gtypeleogz.html

[U118] JS：开发服务器
来源：http://dali.yj202588.top/Article/details/gtgpthfuxt.html

npm i -D vite;  npx vite
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwdcqsnc.html

[U119] JS：生产构建
来源：http://dali.gogol.net.cn/Article/details/gtmbkxfjhe.html

npx vite build
来源：http://dali.havefunace.top/Article/details/gtifmthfmj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.wangdashe.top/Article/details/gtmrwrcxtj.html

import.meta.env.VITE_API_URL
来源：http://dali.daxiang520.top/Article/details/gtifvkdzff.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtuimdxekm.html

统计汇总
来源：http://dali.gaohongyu789.top/Article/details/gtaimwopzr.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkismzfmv.html

按语言统计（条）：
来源：http://dali.wangshuangyany.cn/Article/details/gtmhphqwsa.html

Python ......... 252
来源：http://dali.quarkkingdee.top/Article/details/gtlbjjushp.html

PHP ............ 252
来源：http://dali.ehwqpu.com/Article/details/gtzafmvxgi.html

JavaScript ..... 252
来源：http://dali.tianlin.xyz/Article/details/gttrizuzma.html

TypeScript ..... 212
来源：http://dali.yangfankeji.com/Article/details/gtyxwvgbud.html

Java ........... 212
来源：http://dali.pycfn.com/Article/details/gtmkmealgb.html

Go ............. 212
来源：http://dali.xuetiantiany.cn/Article/details/gthbjsysym.html

Ruby ........... 212
来源：http://dali.yuanzhike.top/Article/details/gtpexkxvij.html

C# ............. 212
来源：http://dali.pycfn.com/Article/details/gtpbirmiey.html

C .............. 30
来源：http://dali.aizwys.cn/Article/details/gtbfbuwmng.html

C++ ............ 30
来源：http://dali.yuanzhike.top/Article/details/gtndsvqnik.html

SQL ............ 90
来源：http://dali.yanxiufei.cn/Article/details/gtnktoyauu.html

Bash ........... 80
来源：http://dali.meibo888.top/Article/details/gtnhxzipbq.html

Kotlin ......... 15
来源：http://dali.hfpthk.cn/Article/details/gtwqlktlgh.html

Swift .......... 15
来源：http://dali.chenlongwang.top/Article/details/gtzzznasbp.html

Lua ............ 10
来源：http://dali.kuanghao11.cn/Article/details/gtfvhttuxe.html

Perl ........... 10
来源：http://dali.zdqjudy.top/Article/details/gtfpkjwxmc.html

Scala .......... 10
来源：http://dali.gotoacloud.top/Article/details/gtmhxjkydl.html

------------------------------------
来源：http://dali.daria6918.cn/Article/details/gtcscpgxzw.html

合计 ........... 2106 条
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlufirmx.html

按章节统计：
来源：http://dali.chenlongwang.top/Article/details/gtdteciwex.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xuetiantiany.cn/Article/details/gtzcwzpqgf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.guowangkeji.top/Article/details/gtzjppyxrh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.aizwys.cn/Article/details/gtzfexkpxe.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gogol.net.cn/Article/details/gtlnvufeav.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.haohaochexian.top/Article/details/gtesetywad.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.pycfn.com/Article/details/gtfursoiuy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tanke756.top/Article/details/gtuuaurbre.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yongpay.top/Article/details/gtrzveydbb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gtyhjwxool.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jianghu66.top/Article/details/gtkavphzjs.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gtoabngvsx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jqgufenzy.top/Article/details/gtkfwgiqtp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gtksqiwjto.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hongshengwenyu.top/Article/details/gttkgjkqja.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hnxiangtu.top/Article/details/gtwadcjhrj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gtnauesnhe.html

Q SQL 专题                              90
来源：http://dali.yj20258.top/Article/details/gtmbfzvazo.html

R Bash 专题                             80
来源：http://dali.guannengcc.top/Article/details/gtfvhdmitx.html

S C / C++ 专题                          60
来源：http://dali.andypj.xyz/Article/details/gtnaenpoxk.html

T 其他语言补充                          60
来源：http://dali.quarkkingdee.top/Article/details/gtdufvvojh.html

U 高频实用片段                         120
来源：http://dali.jiagoushi.top/Article/details/gtsynmiymx.html

------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gtjstjxwpf.html

合计                                  2106 条
来源：http://dali.xziqi.cn/Article/details/gttpxbiefr.html

--------------------------------------------------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gtxhkkcsch.html

使用提醒
来源：http://dali.fengsongda.top/Article/details/gtbixnvlkk.html

--------------------------------------------------------------------------------
来源：http://dali.bjfxy.top/Article/details/gtihfybeue.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gtojacveie.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hammf.cn/Article/details/gtkxfcslwz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.cqqwz.cn/Article/details/gtyhyeaygx.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cucudq.cn/Article/details/gtwhoaxcmu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.guowangkeji.top/Article/details/gtfmrqumzb.html

—— 文件结束 ——
来源：http://dali.jqgfzy.top/Article/details/gttwilejgt.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtqxlplwml.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yangfankeji.com/Article/details/gtgcjhllhi.html

Common Programming Examples Cheat Book
来源：http://dali.cheryme.top/Article/details/gtzvlxcygd.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtnkznveeo.html

【收录内容】
来源：http://dali.sysykeji.top/Article/details/gtqheucnyn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xuanzx.com/Article/details/gtczoikztm.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.fengsongda.top/Article/details/gtebpsfsmh.html

SQL · Bash · C · C++
来源：http://dali.havefunace.top/Article/details/gtnkxazqgr.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hysaishi.cn/Article/details/gtujwtmxef.html

【使用说明】
来源：http://dali.cdnleiting.top/Article/details/gttawrbslt.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.andypj.xyz/Article/details/gtmxskzegg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.cheryme.top/Article/details/gtfrtquaro.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xinyue.icu/Article/details/gtrcpcykra.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shuidangran.top/Article/details/gtaqrdslqy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjjppmbf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenlongwang.top/Article/details/gtognsvrhw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yueranfly.top/Article/details/gtxkbcsrgs.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.c1oappe.top/Article/details/gtkszhkjes.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yvedp.cn/Article/details/gtgoxypjmu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zycfv.cn/Article/details/gttxzfnxkm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlafkauk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hammf.cn/Article/details/gtkosldssu.html

【文件统计】
来源：http://dali.zdqjudy.top/Article/details/gtgssigssq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.chenzaomai.com/Article/details/gttyhrtkcf.html

--------------------------------------------------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gtropxqkyl.html

目  录
来源：http://dali.jqgufenzy.top/Article/details/gtvzskzifj.html

--------------------------------------------------------------------------------
来源：http://dali.yongpay.top/Article/details/gtjdmgvppv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtxpxqpubt.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jianghu66.top/Article/details/gtzonttttm.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.chenzaomai.com/Article/details/gtfllggaaq.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.quarkkingdee.top/Article/details/gtgnctswoh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.daria6918.cn/Article/details/gtfrqubecq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.mhx1999.top/Article/details/gtwhfwvlep.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gtgtggtgpc.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.dashuyun.cn/Article/details/gtchaxdvew.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.gotoacloud.top/Article/details/gtmygkfgco.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.fengsongda.top/Article/details/gtshmqysfs.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.dashuyun.cn/Article/details/gtkafztfmb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.sxryk.cn/Article/details/gtpliboeig.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.ehwqpu.com/Article/details/gtgmqvyswn.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.daria6918.cn/Article/details/gttokzfdll.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sufxvd.cn/Article/details/gtiqyxhjdc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gtsickqgrh.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.sxryk.cn/Article/details/gtvkptgiuu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hysaishi.cn/Article/details/gthlijofei.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jianghu66.top/Article/details/gtoivekoxx.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yueranfly.top/Article/details/gtnyavfbjt.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.dianchejie.cn/Article/details/gtlyxuqyec.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtrbarvmgk.html

A. 基础语法与类型
来源：http://dali.svipenyu.cn/Article/details/gtwdxtokbu.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtdxkyjddi.html

[A01] Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtwmezisxh.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gtwkuefgki.html

PHP:  echo "Hello, World!";
来源：http://dali.jiagoushi.top/Article/details/gtfkpvddzv.html

JS:   console.log("Hello, World!");
来源：http://dali.meibo888.top/Article/details/gturuhmpdk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.c1oappe.top/Article/details/gtsqxmhtka.html

Java: System.out.println("Hello, World!");
来源：http://dali.hywenlv.cn/Article/details/gtpxmwpgkk.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.chenjidiqi.icu/Article/details/gtilkqgkvz.html

Ruby: puts "Hello, World!"
来源：http://dali.wangshuangyany.cn/Article/details/gteqzgruli.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.svipenyu.cn/Article/details/gtcqelxoyb.html

[A02] 变量声明与赋值
来源：http://dali.hywenlv.cn/Article/details/gtijryuhof.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sxryk.cn/Article/details/gtpdllixwb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhiwuduotai.top/Article/details/gtezkvjxaa.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yvedp.cn/Article/details/gtvcyrqyhv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.c1oappe.top/Article/details/gtiufmvjad.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yuxming.cn/Article/details/gtpnaahbjg.html

Go:   name := "Alex"; age := 20
来源：http://dali.aibaodan.cn/Article/details/gtacxwrgkx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yj20258888.top/Article/details/gteobthvcn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazvakbwl.html

[A03] 常量定义
来源：http://dali.hongshengwenyu.top/Article/details/gthfwtnkza.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.sysykeji.top/Article/details/gtuhltorsx.html

PHP:  const PI = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtkknmesez.html

JS:   const PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtvtkmggld.html

TS:   const PI: number = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gtlrleybtf.html

Java: static final double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtdjjrnbjo.html

Go:   const PI = 3.14159
来源：http://dali.yanxiufei.cn/Article/details/gtzqbeeblz.html

Ruby: PI = 3.14159
来源：http://dali.hongshengwenyu.top/Article/details/gtkwmoyhup.html

C#:   const double PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gtiamcocmr.html

[A04] 判断变量类型
来源：http://dali.xylfe.cn/Article/details/gtndoenyph.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.gzhubu.top/Article/details/gtopybhmuv.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.sysykeji.top/Article/details/gtrbigxmrk.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zycfv.cn/Article/details/gthrsyruhw.html

TS:   typeof x; x instanceof Date
来源：http://dali.xylfe.cn/Article/details/gtphntqtat.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jqgufenzy.top/Article/details/gtzspdfzve.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirrcoivg.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.0kj1m.cn/Article/details/gtghzdcsvk.html

C#:   x.GetType().Name; x is int
来源：http://dali.quarkkingdee.top/Article/details/gtrzwukrzl.html

[A05] 整数除法与取模
来源：http://dali.ybcxt.top/Article/details/gtnfbbzdsq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yangfankeji.com/Article/details/gtsnhmvkjv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtzslamrlw.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gtyxsipyif.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xuanzx.com/Article/details/gtxvuyuryh.html

Java: 7 / 2; 7 % 2
来源：http://dali.hnqzz.top/Article/details/gtetxpzwkb.html

Go:   7 / 2; 7 % 2
来源：http://dali.yj20258888.top/Article/details/gtxpkypsha.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gttqkwyvlf.html

C#:   7 / 2; 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtosopgbwq.html

[A06] 字符串转数字
来源：http://dali.yangfankeji.com/Article/details/gttnifuylq.html

Py:   int("42"); float("3.14")
来源：http://dali.tanke756.top/Article/details/gtygwuvwtg.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.gogol.net.cn/Article/details/gtbdssxryh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hnxiangtu.top/Article/details/gtkogntuwh.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.guowangkeji.top/Article/details/gtnmxxdiez.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jianghu66.top/Article/details/gtrwhikoek.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.dashuyun.cn/Article/details/gtgoabunec.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.shangyingyoupin.top/Article/details/gthgwbrexf.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.cqqwz.cn/Article/details/gtjtecxqdn.html

[A07] 数字转字符串
来源：http://dali.mhx1999.top/Article/details/gtibdgxcwv.html

Py:   str(42)
来源：http://dali.yj202588.top/Article/details/gtfeicfweb.html

PHP:  (string) 42; strval(42)
来源：http://dali.smart0.xyz/Article/details/gtkziiodss.html

JS:   String(42); (42).toString()
来源：http://dali.haohaochexian.top/Article/details/gtsiohhaok.html

TS:   String(42)
来源：http://dali.zycfv.cn/Article/details/gtikboulxi.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.cheryme.top/Article/details/gtxxrkvlmr.html

Go:   strconv.Itoa(42)
来源：http://dali.xuetiantiany.cn/Article/details/gtuzxnjvlo.html

Ruby: 42.to_s
来源：http://dali.jinqigfzy.top/Article/details/gttryxbcpu.html

C#:   42.ToString()
来源：http://dali.xziqi.cn/Article/details/gtmzzlpfiz.html

[A08] 取整与四舍五入
来源：http://dali.gotoacloud.top/Article/details/gtroxktmmn.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhongyouzk.top/Article/details/gtozbshwlo.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.meibo888.top/Article/details/gtnbdvbkhg.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.meibo888.top/Article/details/gtsocbxvjr.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.sufxvd.cn/Article/details/gtkyvdwvjl.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yueranfly.top/Article/details/gtuhzfhomn.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.quarkkingdee.top/Article/details/gtkaejgibp.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.pengpengdd.cyou/Article/details/gtqxjbtnbq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.bjfxy.top/Article/details/gthpeaaxny.html

[A09] 绝对值与最大最小值
来源：http://dali.dianchejie.cn/Article/details/gtcmkkhewi.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtilrszxkz.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gtuzwqazti.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gtubmshuma.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtgekxjmcb.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxriofrwl.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.andypj.xyz/Article/details/gtqqvxqzap.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.redwolf501.top/Article/details/gtwhaiqjek.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.hammf.cn/Article/details/gtgnvfbjae.html

[A10] 生成随机数
来源：http://dali.fzhhl.top/Article/details/gtnxhgcccf.html

Py:   import random; random.randint(1, 100)
来源：http://dali.guowangkeji.top/Article/details/gtmgivicqr.html

PHP:  random_int(1, 100);
来源：http://dali.ydzc1.top/Article/details/gteablxgoy.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.dianchejie.cn/Article/details/gtoqxigfrm.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hongshengwenyu.top/Article/details/gtkphbfipe.html

Java: new Random().nextInt(100) + 1
来源：http://dali.birdmap.top/Article/details/gtfniqeltv.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.feifeiyinyue.top/Article/details/gtxgnpatnx.html

Ruby: rand(1..100)
来源：http://dali.birdmap.top/Article/details/gtjefzfzgo.html

C#:   new Random().Next(1, 101)
来源：http://dali.meibo888.top/Article/details/gtboduqsca.html

[A11] 条件表达式（三元）
来源：http://dali.redwolf501.top/Article/details/gtcgvgoaby.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.tianlin.xyz/Article/details/gtlwbgtfke.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.xuanzx.com/Article/details/gteuqsnbyy.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmqbsmwc.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.xuanzx.com/Article/details/gtezvotdsa.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.aibaodan.cn/Article/details/gtdklxqbth.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.meibo888.top/Article/details/gtiwccsikv.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yueranfly.top/Article/details/gtkfcaituj.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.sysykeji.top/Article/details/gtdxelhyzr.html

[A12] 字符串插值 / 格式化
来源：http://dali.yuxming.cn/Article/details/gtqxataodl.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.0kj1m.cn/Article/details/gtozswkpgu.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zdqjudy.top/Article/details/gtdbxidyjr.html

JS:   `Hello, ${name}!`
来源：http://dali.sufxvd.cn/Article/details/gtprngyujz.html

TS:   `Hello, ${name}!`
来源：http://dali.xinyue.icu/Article/details/gtqhcxoftw.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.daria6918.cn/Article/details/gtoozeqjar.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.tian-w.cn/Article/details/gtuzbadcek.html

Ruby: "Hello, #{name}!"
来源：http://dali.hongshengwenyu.top/Article/details/gtfwnrkdxn.html

C#:   $"Hello, {name}!"
来源：http://dali.aizwys.cn/Article/details/gttqtjewgk.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.wangshuangyany.cn/Article/details/gtbaevmbuj.html

Py:   "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gtgkouktdn.html

PHP:  "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gtozjcvgkf.html

JS:   "第一行\n第二行"
来源：http://dali.zhoulong.xyz/Article/details/gtuyzsezfc.html

TS:   "第一行\n第二行"
来源：http://dali.zhixingplan.top/Article/details/gtjnnseycr.html

Java: "第一行\n第二行"
来源：http://dali.hysaishi.cn/Article/details/gtzoorrzmm.html

Go:   "第一行\n第二行"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstgurwuc.html

Ruby: "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gtfmfqoiaq.html

C#:   "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gtmbwcixfs.html

[A14] 注释写法
来源：http://dali.dianchejie.cn/Article/details/gtvnujpsri.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.shanyushiyangtech.top/Article/details/gtxufgidvk.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.iojbl.cn/Article/details/gtlgduxovn.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhongyouzk.top/Article/details/gtspdpncpk.html

TS:   // 单行；/* 多行 */
来源：http://dali.yj202588.top/Article/details/gtbwohqxjw.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.shuidangran.top/Article/details/gtcctbhocb.html

Go:   // 单行；/* 多行 */
来源：http://dali.snrcjt.cn/Article/details/gtqkbmlcck.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.aizwys.cn/Article/details/gtjvonuaqj.html

C#:   // 单行；/* 多行 */
来源：http://dali.wangshuangyany.cn/Article/details/gtgqlnyarp.html

[A15] 空值判断与默认值
来源：http://dali.xuanzx.com/Article/details/gttmcmsvzu.html

Py:   value = data or "默认值"
来源：http://dali.havefunace.top/Article/details/gtpfommfcm.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.chenjidiqi.icu/Article/details/gtjhwlmpgg.html

JS:   const value = data ?? "默认值";
来源：http://dali.gzhubu.top/Article/details/gtqapdivnz.html

TS:   const value = data ?? "默认值";
来源：http://dali.ydzc1.top/Article/details/gtwgsolaho.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.nwbrower.top/Article/details/gtamwtkqiz.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.sufxvd.cn/Article/details/gtmyikbiwg.html


<!-- 参考信息 -->