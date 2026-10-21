代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.cheryme.top/Article/details/gtwuyxtbfs.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.birdmap.top/Article/details/gtwstzxnzr.html

[U92] JS：深拷贝
来源：http://dali.jqgfzy.top/Article/details/gtsdkhdpmr.html

structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gtalkzckvd.html

[U93] JS：模板字符串
来源：http://dali.fengsongda.top/Article/details/gthklvjlpy.html

`共 ${n} 条`
来源：http://dali.cqqwz.cn/Article/details/gtfwykbeuw.html

[U94] JS：箭头函数
来源：http://dali.bjfxy.top/Article/details/gttualaefh.html

const double = x => x * 2;
来源：http://dali.yj20258.top/Article/details/gtulmguxyt.html

[U95] JS：Promise 包装
来源：http://dali.yj20258.top/Article/details/gtrpiwvowk.html

new Promise((resolve, reject) => {})
来源：http://dali.jqgufenzy.top/Article/details/gtapbxbeks.html

[U96] JS：async/await 与异常
来源：http://dali.yj202588.top/Article/details/gtaodiqrrt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtoqizaonj.html

[U97] JS：并发请求
来源：http://dali.hfpthk.cn/Article/details/gtwdssinaq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gtwnvevvav.html

[U98] JS：fetch 带 JSON
来源：http://dali.jyoumei.cn/Article/details/gtsorciyfv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.fengsongda.top/Article/details/gtceklmdkp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gtbmwygzjq.html

el.addEventListener("click", e => {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyiczgjrg.html

[U100] JS：DOM 查询
来源：http://dali.ppjwa.cn/Article/details/gteuxnduba.html

document.querySelector(".item")
来源：http://dali.zhoulong.xyz/Article/details/gtjzcxvgll.html

[U101] JS：classList 操作
来源：http://dali.xuetiantiany.cn/Article/details/gtueytsbon.html

el.classList.toggle("active")
来源：http://dali.daria6918.cn/Article/details/gtwqoiqawj.html

[U102] JS：本地存储
来源：http://dali.gotoacloud.top/Article/details/gtnnhogdcs.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hnxiangtu.top/Article/details/gtimyadtkm.html

[U103] JS：定时器
来源：http://dali.ehwqpu.com/Article/details/gtovckxfmu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhixingplan.top/Article/details/gtwvymmofi.html

[U104] JS：防抖
来源：http://dali.ybcxt.top/Article/details/gtulavrlna.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gtdmkrbhdi.html

[U105] JS：节流
来源：http://dali.snrcjt.cn/Article/details/gtunhdncqt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.nanxuanxn.top/Article/details/gtrfzrsypr.html

[U106] JS：日期格式化
来源：http://dali.meibo888.top/Article/details/gttoqrfvsg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yangfankeji.com/Article/details/gtntnuodhe.html

[U107] JS：数字千分位
来源：http://dali.yangfankeji.com/Article/details/gtasaqqdag.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.wangshuangyany.cn/Article/details/gtxwnoqeqs.html

[U108] JS：随机整数
来源：http://dali.hysaishi.cn/Article/details/gtgckmveay.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.sufxvd.cn/Article/details/gtmyrgemcp.html

[U109] JS：数组分组
来源：http://dali.bjfxy.top/Article/details/gtwxbilano.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sufxvd.cn/Article/details/gtdrickkvl.html

[U110] JS：数组分块
来源：http://dali.xinyue.icu/Article/details/gttqxvlwie.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jyoumei.cn/Article/details/gttmwtlnqc.html

[U111] JS：对象转 Map
来源：http://dali.cashguo.top/Article/details/gtzxysczyz.html

new Map(Object.entries(obj))
来源：http://dali.jyoumei.cn/Article/details/gtoperhpda.html

[U112] JS：字符串补位
来源：http://dali.zhoulong.xyz/Article/details/gthtiondgl.html

"7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtdmgkxkjt.html

[U113] JS：正则替换全部
来源：http://dali.zhaomingkeji.xyz/Article/details/gtooaribxq.html

s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtdglaqmnr.html

[U114] JS：JSON 深比较
来源：http://dali.yvedp.cn/Article/details/gtfboxfqrg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jiagoushi.top/Article/details/gtugetdmnn.html

[U115] JS：生成 UUID
来源：http://dali.xinyue.icu/Article/details/gtgoftgtvz.html

crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gtuvbqcvxi.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.dianchejie.cn/Article/details/gttqnnkebv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yuxming.cn/Article/details/gtauiwrozl.html

[U117] JS：单元测试
来源：http://dali.sweek.top/Article/details/gtmqtwpexo.html

npm i -D vitest;  npx vitest
来源：http://dali.cqqwz.cn/Article/details/gtaowbrhwy.html

[U118] JS：开发服务器
来源：http://dali.shuidangran.top/Article/details/gtcpakfnhx.html

npm i -D vite;  npx vite
来源：http://dali.shangyingyoupin.top/Article/details/gtcyaktehy.html

[U119] JS：生产构建
来源：http://dali.hysaishi.cn/Article/details/gtutpqgxsb.html

npx vite build
来源：http://dali.c1oappe.top/Article/details/gtcutbmwvm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yj20258.top/Article/details/gtqytubxji.html

import.meta.env.VITE_API_URL
来源：http://dali.ppjwa.cn/Article/details/gtttpekmou.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtwpdcxwba.html

统计汇总
来源：http://dali.jiagoushi.top/Article/details/gtnhjpsijx.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtvlyrolgi.html

按语言统计（条）：
来源：http://dali.zhixingplan.top/Article/details/gtqubbvmcd.html

Python ......... 252
来源：http://dali.andypj.xyz/Article/details/gtictzgzan.html

PHP ............ 252
来源：http://dali.quarkkingdee.top/Article/details/gtltezkvkr.html

JavaScript ..... 252
来源：http://dali.meibo888.top/Article/details/gtcjlahpom.html

TypeScript ..... 212
来源：http://dali.hongshengwenyu.top/Article/details/gtiudtyszc.html

Java ........... 212
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtzevzvx.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gthhivwxbk.html

Ruby ........... 212
来源：http://dali.ivvv.top/Article/details/gtqvqmnhej.html

C# ............. 212
来源：http://dali.dianchejie.cn/Article/details/gtpvuzlggt.html

C .............. 30
来源：http://dali.dianchejie.cn/Article/details/gtbshiubci.html

C++ ............ 30
来源：http://dali.gzhubu.top/Article/details/gtbkdbbmqf.html

SQL ............ 90
来源：http://dali.jlsjyb.cn/Article/details/gtzlcyvakl.html

Bash ........... 80
来源：http://dali.zhixingplan.top/Article/details/gtxfiqsinp.html

Kotlin ......... 15
来源：http://dali.hongshengwenyu.top/Article/details/gtmjocahoq.html

Swift .......... 15
来源：http://dali.jqgfzy.top/Article/details/gtwxfifqxp.html

Lua ............ 10
来源：http://dali.smart0.xyz/Article/details/gttlhpijwv.html

Perl ........... 10
来源：http://dali.haohaochexian.top/Article/details/gtaqzawnfo.html

Scala .......... 10
来源：http://dali.yanxiufei.cn/Article/details/gthhgwbbhm.html

------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gtcsmzfqvq.html

合计 ........... 2106 条
来源：http://dali.shzxlz.cn/Article/details/gtlqjvpcae.html

按章节统计：
来源：http://dali.andypj.xyz/Article/details/gttppqlpth.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hfpthk.cn/Article/details/gtlwfqsddh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gtwknwmcic.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.iojbl.cn/Article/details/gtziasnjwg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ehwqpu.com/Article/details/gtjoijuhhx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.chenlongwang.top/Article/details/gttahaodml.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zdqjudy.top/Article/details/gtdksilcey.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.sweek.top/Article/details/gtalgjvugt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.fzhhl.top/Article/details/gtphjzscka.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gtoeyinzvw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.quarkkingdee.top/Article/details/gtnndbnhwh.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gtcgbmwoli.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gthtnfsdhz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gtguymnsno.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.gaohongyu789.top/Article/details/gtozivuyrf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jiagoushi.top/Article/details/gtoovbykrs.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gtkhllbqiy.html

Q SQL 专题                              90
来源：http://dali.jinqigufen.top/Article/details/gtfjnlibvr.html

R Bash 专题                             80
来源：http://dali.xuanzx.com/Article/details/gtoazpbcwj.html

S C / C++ 专题                          60
来源：http://dali.zhixingplan.top/Article/details/gtdeklnjyb.html

T 其他语言补充                          60
来源：http://dali.yongpay.top/Article/details/gtwtypyfry.html

U 高频实用片段                         120
来源：http://dali.jiagoushi.top/Article/details/gtxmjommdw.html

------------------------------------
来源：http://dali.bjfxy.top/Article/details/gtimlbawuu.html

合计                                  2106 条
来源：http://dali.jlsjyb.cn/Article/details/gtrshcifuf.html

--------------------------------------------------------------------------------
来源：http://dali.hammf.cn/Article/details/gtsnwzycjw.html

使用提醒
来源：http://dali.ppjwa.cn/Article/details/gtvahymbav.html

--------------------------------------------------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gtpxsfwlvt.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.pycfn.com/Article/details/gtqqxydbzv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jinqigufen.top/Article/details/gttndtkijq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.tianlin.xyz/Article/details/gtnklacczs.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hfpthk.cn/Article/details/gtrhqushus.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xinyue.icu/Article/details/gtciuqfqzd.html

—— 文件结束 ——
来源：http://dali.sufxvd.cn/Article/details/gtcszpytkd.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtykijgrkw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hywenlv.cn/Article/details/gtokkminqy.html

Common Programming Examples Cheat Book
来源：http://dali.yj20258.top/Article/details/gtoycptavl.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtrbonkjpp.html

【收录内容】
来源：http://dali.sysykeji.top/Article/details/gtbtvvrsiz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xinyue.icu/Article/details/gtfrdhurlp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.daxiang520.top/Article/details/gtspdwcnvg.html

SQL · Bash · C · C++
来源：http://dali.zhongyouzk.top/Article/details/gtzifrdgpz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhongyouzk.top/Article/details/gtkqgqvfkf.html

【使用说明】
来源：http://dali.feifeiyinyue.top/Article/details/gtlmofzdcc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yuanzhike.top/Article/details/gtulmwewnp.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.gaohongyu789.top/Article/details/gtwinmyvbz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.snrcjt.cn/Article/details/gtkbgotnel.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jqgufenzy.top/Article/details/gtagskyuzt.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.mhx1999.top/Article/details/gtatyfjghq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hongshengwenyu.top/Article/details/gtbbtzpbmr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yj20258888.top/Article/details/gtsimjvdpm.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yueranfly.top/Article/details/gtdnyuzony.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shzxlz.cn/Article/details/gtjtwqmstg.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cucudq.cn/Article/details/gtriyvfore.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.dashuyun.cn/Article/details/gtzafvxjad.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yuxming.cn/Article/details/gteveonjkp.html

【文件统计】
来源：http://dali.jqgufenzy.top/Article/details/gtjfzcefnq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.0kj1m.cn/Article/details/gtrrhwirql.html

--------------------------------------------------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gtyhghbdqi.html

目  录
来源：http://dali.ybcxt.top/Article/details/gtygcdsblo.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gtyamefmty.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hysaishi.cn/Article/details/gtyakghapo.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zycfv.cn/Article/details/gtojhdunhh.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jqgfzy.top/Article/details/gtystxueoe.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.cdnleiting.top/Article/details/gtvartcckv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.dianchejie.cn/Article/details/gtvmzpalbn.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.c1oappe.top/Article/details/gtbmmysviz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.aizwys.cn/Article/details/gtcwpjpdix.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hnqzz.top/Article/details/gtkxirscqc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gtsumuckcl.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hnqzz.top/Article/details/gtjmyccqkl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhongyouzk.top/Article/details/gthpmlleva.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cdnleiting.top/Article/details/gtnznhjyyg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtwwrefahk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.havefunace.top/Article/details/gtbhcxhsjj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.wangshuangyany.cn/Article/details/gthegsjqvi.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gtckwkrlsr.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.nwbrower.top/Article/details/gtregwhokk.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cashguo.top/Article/details/gtlnyouerh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.guannengcc.top/Article/details/gtnltgmzet.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.0kj1m.cn/Article/details/gtmjqbzqpj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jlsjyb.cn/Article/details/gtwlfpjlcd.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtshqwscmt.html

A. 基础语法与类型
来源：http://dali.yj20258888.top/Article/details/gtvtgwgxlx.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtlzxqymwh.html

[A01] Hello World
来源：http://dali.birdmap.top/Article/details/gtsjwtggvb.html

Py:   print("Hello, World!")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwxkrfgg.html

PHP:  echo "Hello, World!";
来源：http://dali.hnxiangtu.top/Article/details/gtprgexmvb.html

JS:   console.log("Hello, World!");
来源：http://dali.cucudq.cn/Article/details/gtuyawqhgu.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.tianlin.xyz/Article/details/gtuazuzxkg.html

Java: System.out.println("Hello, World!");
来源：http://dali.cheryme.top/Article/details/gtxdvtowar.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sxryk.cn/Article/details/gtqrxrelwl.html

Ruby: puts "Hello, World!"
来源：http://dali.guannengcc.top/Article/details/gtctsdrpco.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.cashguo.top/Article/details/gtmdueqpff.html

[A02] 变量声明与赋值
来源：http://dali.feifeiyinyue.top/Article/details/gtmwvslxhg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shangyingyoupin.top/Article/details/gtadsamtpq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yuanzhike.top/Article/details/gtomocjzyi.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.bjfxy.top/Article/details/gtcbdxfbyn.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.havefunace.top/Article/details/gtttkmtvri.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.guowangkeji.top/Article/details/gtfkbdkciz.html

Go:   name := "Alex"; age := 20
来源：http://dali.jlsjyb.cn/Article/details/gtcfynjepv.html

Ruby: name = "Alex"; age = 20
来源：http://dali.nanxinkj.top/Article/details/gtrryindhv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.meibo888.top/Article/details/gteemujsnt.html

[A03] 常量定义
来源：http://dali.ppjwa.cn/Article/details/gtevzdwzyz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.9152youxi.cn/Article/details/gtdwgtoxha.html

PHP:  const PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtbkbqtlmh.html

JS:   const PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtoyvgoahy.html

TS:   const PI: number = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtactwxelp.html

Java: static final double PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtxzziyqeh.html

Go:   const PI = 3.14159
来源：http://dali.cqqwz.cn/Article/details/gtbrfpytrw.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gtzayqvnfp.html

C#:   const double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtrieuebwg.html

[A04] 判断变量类型
来源：http://dali.shzxlz.cn/Article/details/gtpiathrem.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.snrcjt.cn/Article/details/gtcamxnzlo.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.chenzaomai.com/Article/details/gtcdonalut.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.shzxlz.cn/Article/details/gtmclzddsy.html

TS:   typeof x; x instanceof Date
来源：http://dali.xylfe.cn/Article/details/gtvlfbbwew.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.guannengcc.top/Article/details/gtpygmchzr.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.316326.xyz/Article/details/gtekzbyqrx.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ehwqpu.com/Article/details/gthhlvuime.html

C#:   x.GetType().Name; x is int
来源：http://dali.yanxiufei.cn/Article/details/gtiorxdtar.html

[A05] 整数除法与取模
来源：http://dali.c1oappe.top/Article/details/gtxlubqbpd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.birdmap.top/Article/details/gtqarojkfr.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gtthlsycjy.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gtopxmyusv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xuanzx.com/Article/details/gtimxezusj.html

Java: 7 / 2; 7 % 2
来源：http://dali.bjfxy.top/Article/details/gtpjwlfsjy.html

Go:   7 / 2; 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gtenakguyo.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.meibo888.top/Article/details/gtqkiqnivw.html

C#:   7 / 2; 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gtfazdofda.html

[A06] 字符串转数字
来源：http://dali.nwbrower.top/Article/details/gtqeizxczn.html

Py:   int("42"); float("3.14")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjggajwj.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yongpay.top/Article/details/gtfwjprpvy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.wangshuangyany.cn/Article/details/gtnqcprdoo.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.shanyushiyangtech.top/Article/details/gthmdyejam.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.xinyue.icu/Article/details/gtyjhzstkr.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.mhx1999.top/Article/details/gtaiiwyykl.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.pycfn.com/Article/details/gtpzexwcyu.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.havefunace.top/Article/details/gttgudiere.html

[A07] 数字转字符串
来源：http://dali.nwbrower.top/Article/details/gtjguuavsz.html

Py:   str(42)
来源：http://dali.andypj.xyz/Article/details/gtbuqdcnec.html

PHP:  (string) 42; strval(42)
来源：http://dali.jianghu66.top/Article/details/gtxbwwxpsz.html

JS:   String(42); (42).toString()
来源：http://dali.ppjwa.cn/Article/details/gtbcubctka.html

TS:   String(42)
来源：http://dali.zhiwuduotai.top/Article/details/gtiedgwzta.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jqgfzy.top/Article/details/gtkulstvah.html

Go:   strconv.Itoa(42)
来源：http://dali.shzxlz.cn/Article/details/gtfgsnjqow.html

Ruby: 42.to_s
来源：http://dali.bjfxy.top/Article/details/gtkgudochz.html

C#:   42.ToString()
来源：http://dali.yonumen.top/Article/details/gtdypghhbs.html

[A08] 取整与四舍五入
来源：http://dali.ppjwa.cn/Article/details/gtmnrdbkhl.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.snrcjt.cn/Article/details/gtrkeorryl.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.nanxinkj.top/Article/details/gtvoxjbcyv.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jqgufenzy.top/Article/details/gthqguaqsn.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yj20258.top/Article/details/gtopkgsost.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.redwolf501.top/Article/details/gtytbuanyt.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yj20258.top/Article/details/gtipwqeuxf.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.shanyushiyangkeji.top/Article/details/gtishnrley.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.bjfxy.top/Article/details/gtehzfihkb.html

[A09] 绝对值与最大最小值
来源：http://dali.meibo888.top/Article/details/gtgbvtvxpu.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gtepsfyzjm.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepdwrtvn.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtefclzbsk.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.pycfn.com/Article/details/gtegnrctgn.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gthlflvxti.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jqgfzy.top/Article/details/gtluqazjzn.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.tianlin.xyz/Article/details/gtfubhyeft.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yj20258.top/Article/details/gtawvfdyiy.html

[A10] 生成随机数
来源：http://dali.xuanzx.com/Article/details/gthnaakddt.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zycfv.cn/Article/details/gtqhrjkyjf.html

PHP:  random_int(1, 100);
来源：http://dali.c1oappe.top/Article/details/gtbkwsaudy.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yueranfly.top/Article/details/gtlcinyqvd.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xuanzx.com/Article/details/gtekpurhza.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yongpay.top/Article/details/gteebyuclm.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.meibo888.top/Article/details/gtwghkxvzp.html

Ruby: rand(1..100)
来源：http://dali.meibo888.top/Article/details/gtgtcjcrjo.html

C#:   new Random().Next(1, 101)
来源：http://dali.aibaodan.cn/Article/details/gtwbbkcgfk.html

[A11] 条件表达式（三元）
来源：http://dali.tianlin.xyz/Article/details/gtnfbiuwub.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.ehwqpu.com/Article/details/gtmwccmlom.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhixingplan.top/Article/details/gtnnrmszva.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jianghu66.top/Article/details/gtxysanvze.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhoulong.xyz/Article/details/gtgjugyrwp.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zdqjudy.top/Article/details/gtmpvcfhak.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jqgfzy.top/Article/details/gtybtvdhkk.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jlsjyb.cn/Article/details/gtacfmayhg.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.tianlin.xyz/Article/details/gtevcnidkm.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtzosmfsay.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.ybcxt.top/Article/details/gtnlslfitb.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhengqikj.top/Article/details/gtinzisfko.html

JS:   `Hello, ${name}!`
来源：http://dali.gogol.net.cn/Article/details/gtfuqnbfmg.html

TS:   `Hello, ${name}!`
来源：http://dali.xylfe.cn/Article/details/gtykmhnmzb.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.shangyingyoupin.top/Article/details/gtzqgtshoq.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.svipenyu.cn/Article/details/gtnfrjwsgm.html

Ruby: "Hello, #{name}!"
来源：http://dali.sufxvd.cn/Article/details/gtrlnyrmcb.html

C#:   $"Hello, {name}!"
来源：http://dali.daria6918.cn/Article/details/gtpealeyje.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.nanxinkj.top/Article/details/gtwunffpnx.html

Py:   "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gtxveerpag.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gtntdvdpmg.html

JS:   "第一行\n第二行"
来源：http://dali.ehwqpu.com/Article/details/gtjejblxkm.html

TS:   "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gtglhtgunt.html

Java: "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gtzxjvqtto.html

Go:   "第一行\n第二行"
来源：http://dali.hywenlv.cn/Article/details/gtvwinyyth.html

Ruby: "第一行\n第二行"
来源：http://dali.zhongyouzk.top/Article/details/gtcgmmdtjd.html

C#:   "第一行\n第二行"
来源：http://dali.hywenlv.cn/Article/details/gtozfxurzo.html

[A14] 注释写法
来源：http://dali.hammf.cn/Article/details/gtdiombibu.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.vqdsnc.cn/Article/details/gtpqhspceo.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.iojbl.cn/Article/details/gtwbaqaift.html

JS:   // 单行；/* 多行 */
来源：http://dali.hammf.cn/Article/details/gttwdxolsz.html

TS:   // 单行；/* 多行 */
来源：http://dali.guowangkeji.top/Article/details/gtaoudguxx.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.xuetiantiany.cn/Article/details/gtqtkouzcx.html

Go:   // 单行；/* 多行 */
来源：http://dali.hnqzz.top/Article/details/gtnmtttcon.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.dianchejie.cn/Article/details/gttgmmcusz.html

C#:   // 单行；/* 多行 */
来源：http://dali.feifeiyinyue.top/Article/details/gtautnwrwu.html

[A15] 空值判断与默认值
来源：http://dali.meibo888.top/Article/details/gtchqdqzrl.html

Py:   value = data or "默认值"
来源：http://dali.ivvv.top/Article/details/gtnlsgltmb.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jqgfzy.top/Article/details/gtayarodqp.html

JS:   const value = data ?? "默认值";
来源：http://dali.jinqigufen.top/Article/details/gtsecezkrf.html

TS:   const value = data ?? "默认值";
来源：http://dali.birdmap.top/Article/details/gtqezykbkw.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yonumen.top/Article/details/gtjtkmdzti.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.cucudq.cn/Article/details/gtktzxcgmf.html


<!-- 参考信息 -->