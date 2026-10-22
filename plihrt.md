代发 wailian999

[U89] JS：数组去重
来源：http://dali.jqgfzy.top/Article/details/gtudogzlfw.html

[...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gtiziwgmge.html

[U90] JS：数字数组排序
来源：http://dali.hnxiangtu.top/Article/details/gtlsbfzqqw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfukkvdt.html

[U91] JS：对象键值遍历
来源：http://dali.yj20258888.top/Article/details/gttnogktvf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hnqzz.top/Article/details/gtskjbgcrm.html

[U92] JS：深拷贝
来源：http://dali.yangfankeji.com/Article/details/gticfqfkdj.html

structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gtovfglvgs.html

[U93] JS：模板字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gttxabwmao.html

`共 ${n} 条`
来源：http://dali.svipenyu.cn/Article/details/gtyeyytmgj.html

[U94] JS：箭头函数
来源：http://dali.cheryme.top/Article/details/gtxmfpfnfu.html

const double = x => x * 2;
来源：http://dali.cqqwz.cn/Article/details/gtrfujysci.html

[U95] JS：Promise 包装
来源：http://dali.hysaishi.cn/Article/details/gtuvmilfqt.html

new Promise((resolve, reject) => {})
来源：http://dali.jinqigufen.top/Article/details/gtxhkhwngh.html

[U96] JS：async/await 与异常
来源：http://dali.yanxiufei.cn/Article/details/gtldwwjmlx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gtajmgewfn.html

[U97] JS：并发请求
来源：http://dali.sysykeji.top/Article/details/gtidqxhgik.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gtbgkbmboy.html

[U98] JS：fetch 带 JSON
来源：http://dali.316326.xyz/Article/details/gtbogosimc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jiagoushi.top/Article/details/gttagldmif.html

[U99] JS：事件监听
来源：http://dali.gotoacloud.top/Article/details/gtmdwagdld.html

el.addEventListener("click", e => {})
来源：http://dali.vqdsnc.cn/Article/details/gtmljindqk.html

[U100] JS：DOM 查询
来源：http://dali.wangdashe.top/Article/details/gtighzpwbm.html

document.querySelector(".item")
来源：http://dali.pycfn.com/Article/details/gtfpdzephi.html

[U101] JS：classList 操作
来源：http://dali.ybcxt.top/Article/details/gtsgksigem.html

el.classList.toggle("active")
来源：http://dali.wangshuangyany.cn/Article/details/gthrbmpfih.html

[U102] JS：本地存储
来源：http://dali.svipenyu.cn/Article/details/gtgcagvxkg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jqgufenzy.top/Article/details/gtnftgqkuu.html

[U103] JS：定时器
来源：http://dali.sweek.top/Article/details/gtmmlqldrj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yvedp.cn/Article/details/gtuhsgvxpo.html

[U104] JS：防抖
来源：http://dali.gzhubu.top/Article/details/gtjxufyoud.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gtgyjtixfo.html

[U105] JS：节流
来源：http://dali.zdqjudy.top/Article/details/gtptmukqtq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sufxvd.cn/Article/details/gtbbpebhkb.html

[U106] JS：日期格式化
来源：http://dali.yj202588.top/Article/details/gtkmjpsxfl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.kuanghao11.cn/Article/details/gtvggwgxlw.html

[U107] JS：数字千分位
来源：http://dali.wangdashe.top/Article/details/gtcsnvgysq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.snrcjt.cn/Article/details/gtxkrfaamo.html

[U108] JS：随机整数
来源：http://dali.xuetiantiany.cn/Article/details/gtjjnuxnrb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.daxiang520.top/Article/details/gtuqmgujcs.html

[U109] JS：数组分组
来源：http://dali.ydzc1.top/Article/details/gtkktnsnll.html

Object.groupBy(arr, x => x.type)
来源：http://dali.smart0.xyz/Article/details/gtpxxlievv.html

[U110] JS：数组分块
来源：http://dali.9152youxi.cn/Article/details/gtaorqdsqs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sweek.top/Article/details/gtjtyazlix.html

[U111] JS：对象转 Map
来源：http://dali.tianlin.xyz/Article/details/gtvxqgjehu.html

new Map(Object.entries(obj))
来源：http://dali.andypj.xyz/Article/details/gtfyuyqlmd.html

[U112] JS：字符串补位
来源：http://dali.cdnleiting.top/Article/details/gtzlokejic.html

"7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gtghfzqnns.html

[U113] JS：正则替换全部
来源：http://dali.hongshengwenyu.top/Article/details/gtytdwhvlw.html

s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtxeuswdof.html

[U114] JS：JSON 深比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtseaoewos.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.meibo888.top/Article/details/gtqvdwvoub.html

[U115] JS：生成 UUID
来源：http://dali.wangshuangyany.cn/Article/details/gtcgavtged.html

crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gtkbqmrrel.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xuanzx.com/Article/details/gtvncyhyxv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zdqjudy.top/Article/details/gtaavndviz.html

[U117] JS：单元测试
来源：http://dali.birdmap.top/Article/details/gtjnrmhcbh.html

npm i -D vitest;  npx vitest
来源：http://dali.hnqzz.top/Article/details/gtjvogdfzd.html

[U118] JS：开发服务器
来源：http://dali.cucudq.cn/Article/details/gtkgqqzmck.html

npm i -D vite;  npx vite
来源：http://dali.chenzaomai.com/Article/details/gtkmxsywrn.html

[U119] JS：生产构建
来源：http://dali.yvedp.cn/Article/details/gtzcblzerm.html

npx vite build
来源：http://dali.cdnleiting.top/Article/details/gtbtfyqpxj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cheryme.top/Article/details/gtlphpxlsk.html

import.meta.env.VITE_API_URL
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaykppnof.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtydrqozcz.html

统计汇总
来源：http://dali.dashuyun.cn/Article/details/gtfzklajoj.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gttkbdxxsp.html

按语言统计（条）：
来源：http://dali.ppjwa.cn/Article/details/gtadlszude.html

Python ......... 252
来源：http://dali.iojbl.cn/Article/details/gtxwjjhmqi.html

PHP ............ 252
来源：http://dali.zhixingplan.top/Article/details/gtdxyxzagx.html

JavaScript ..... 252
来源：http://dali.0kj1m.cn/Article/details/gtsrkcskvg.html

TypeScript ..... 212
来源：http://dali.xziqi.cn/Article/details/gtfqwbjrfs.html

Java ........... 212
来源：http://dali.yj202588.top/Article/details/gtjnvanifm.html

Go ............. 212
来源：http://dali.sufxvd.cn/Article/details/gtbvonsryj.html

Ruby ........... 212
来源：http://dali.yangfankeji.com/Article/details/gtgrmjwiye.html

C# ............. 212
来源：http://dali.pengpengdd.cyou/Article/details/gtllbohexw.html

C .............. 30
来源：http://dali.iojbl.cn/Article/details/gtqctasbaz.html

C++ ............ 30
来源：http://dali.yj202588.top/Article/details/gtcouhqxyk.html

SQL ............ 90
来源：http://dali.dianchejie.cn/Article/details/gtxzdiyztm.html

Bash ........... 80
来源：http://dali.nanxuanxn.top/Article/details/gtdddydwzh.html

Kotlin ......... 15
来源：http://dali.bjfxy.top/Article/details/gtjceqkvyn.html

Swift .......... 15
来源：http://dali.jyoumei.cn/Article/details/gtgrcizaaz.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gtzfdaglnl.html

Perl ........... 10
来源：http://dali.sufxvd.cn/Article/details/gtgqozkups.html

Scala .......... 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gtotjmoezr.html

------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gthmtjposs.html

合计 ........... 2106 条
来源：http://dali.xylfe.cn/Article/details/gtflzmzrze.html

按章节统计：
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzptmoyxg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.daria6918.cn/Article/details/gtvbgmrbby.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.aibaodan.cn/Article/details/gtplcdcflq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.svipenyu.cn/Article/details/gtopardglt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cqqwz.cn/Article/details/gtepdzbhzo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hnqzz.top/Article/details/gtbaiplsdn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xylfe.cn/Article/details/gtmqjvawho.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yj202588.top/Article/details/gtlhqqpqgv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.chenlongwang.top/Article/details/gtcmcukfyw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gtjcogilmh.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhongyouzk.top/Article/details/gtlqzyndvt.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gtublwwclo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gtrpdsoacc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gtkwcxnjje.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hongshengwenyu.top/Article/details/gtkngbnbna.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xziqi.cn/Article/details/gtjnvhgnoa.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegvxzvmj.html

Q SQL 专题                              90
来源：http://dali.quarkkingdee.top/Article/details/gtfhrwdlyo.html

R Bash 专题                             80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizhzbfrc.html

S C / C++ 专题                          60
来源：http://dali.zhoulong.xyz/Article/details/gthtdcgqlp.html

T 其他语言补充                          60
来源：http://dali.hnxiangtu.top/Article/details/gtfeewttqm.html

U 高频实用片段                         120
来源：http://dali.xuanzx.com/Article/details/gtgxjfrghh.html

------------------------------------
来源：http://dali.yj202588.top/Article/details/gtnbevcznf.html

合计                                  2106 条
来源：http://dali.guannengcc.top/Article/details/gtrhevevck.html

--------------------------------------------------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gtrzqottmq.html

使用提醒
来源：http://dali.chenjidiqi.icu/Article/details/gtxgkiimky.html

--------------------------------------------------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfyiudgjl.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jqgfzy.top/Article/details/gtbvoeaxzp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqzpokvn.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ehwqpu.com/Article/details/gtenjcrvnl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.tanke756.top/Article/details/gtbxspzdcb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhongyouzk.top/Article/details/gtjbdasylm.html

—— 文件结束 ——
来源：http://dali.vqdsnc.cn/Article/details/gtieaqpwna.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gthvwjvpcx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hnxiangtu.top/Article/details/gtgtblhovg.html

Common Programming Examples Cheat Book
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmpujfad.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtirmlybro.html

【收录内容】
来源：http://dali.cheryme.top/Article/details/gthtscklza.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.bjfxy.top/Article/details/gtnexxavwv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.shangyingyoupin.top/Article/details/gtsbncnldo.html

SQL · Bash · C · C++
来源：http://dali.yj202588.top/Article/details/gtgzqyutwy.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.c1oappe.top/Article/details/gtjgghjewz.html

【使用说明】
来源：http://dali.sxryk.cn/Article/details/gtvzwauyhl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shuidangran.top/Article/details/gtyitfivcw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.shzxlz.cn/Article/details/gtcmspdbha.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.shzxlz.cn/Article/details/gtoeeqncsa.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.nanxinkj.top/Article/details/gtoxoqysxu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.pengpengdd.cyou/Article/details/gtyehnkuhg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.gzhubu.top/Article/details/gteeelbrjn.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.316326.xyz/Article/details/gtwsbbpsym.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.quarkkingdee.top/Article/details/gturmxohue.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.wangdashe.top/Article/details/gtlebhuvym.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jiagoushi.top/Article/details/gtlaoxsnyj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.pengpengdd.cyou/Article/details/gtdyhuwwbn.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gtheuzvymf.html

【文件统计】
来源：http://dali.yongpay.top/Article/details/gtapfbgbmz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yanxiufei.cn/Article/details/gtbkvsgzhj.html

--------------------------------------------------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gtrmrqdbnh.html

目  录
来源：http://dali.birdmap.top/Article/details/gtnyblidod.html

--------------------------------------------------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhrqwjex.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ppjwa.cn/Article/details/gtdspujdon.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.cucudq.cn/Article/details/gthzercvcr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhixingplan.top/Article/details/gtocwbvelb.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.pycfn.com/Article/details/gtrignftsd.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.haohaochexian.top/Article/details/gtpimfwehb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xziqi.cn/Article/details/gtkxjpzbmy.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xziqi.cn/Article/details/gteyhmdeyh.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.havefunace.top/Article/details/gtijrquvtu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shzxlz.cn/Article/details/gtkgdeseyq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jlsjyb.cn/Article/details/gtngvpjiml.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gtcspoungu.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xinyue.icu/Article/details/gthxackwij.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.kuanghao11.cn/Article/details/gtwylzmfvm.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhongyouzk.top/Article/details/gtsztnmaqz.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.kuanghao11.cn/Article/details/gteffijazg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gtpdfjocyx.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jianghu66.top/Article/details/gtfjhlrpbp.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.aibaodan.cn/Article/details/gtmvzypejv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.pycfn.com/Article/details/gttddexbdo.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xylfe.cn/Article/details/gtthiadkgy.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.quarkkingdee.top/Article/details/gtugbxsaid.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtbokycbss.html

A. 基础语法与类型
来源：http://dali.jyoumei.cn/Article/details/gtukcdgjma.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtpqdebydr.html

[A01] Hello World
来源：http://dali.zhengqikj.top/Article/details/gttgfzjkbz.html

Py:   print("Hello, World!")
来源：http://dali.sufxvd.cn/Article/details/gtextrpqqy.html

PHP:  echo "Hello, World!";
来源：http://dali.cqqwz.cn/Article/details/gtepajqhwp.html

JS:   console.log("Hello, World!");
来源：http://dali.xziqi.cn/Article/details/gtemygshqi.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cashguo.top/Article/details/gtxoikfqdq.html

Java: System.out.println("Hello, World!");
来源：http://dali.jinqigfzy.top/Article/details/gtxaovyanw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.316326.xyz/Article/details/gtxmhfpdwr.html

Ruby: puts "Hello, World!"
来源：http://dali.hnqzz.top/Article/details/gtwywxcqkt.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hywenlv.cn/Article/details/gtzcurvuiu.html

[A02] 变量声明与赋值
来源：http://dali.ppjwa.cn/Article/details/gtwdoyjgrw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.pycfn.com/Article/details/gtsjeyanlb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmsppcebj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xinyue.icu/Article/details/gtjnxqfjhg.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jlsjyb.cn/Article/details/gtoejeccan.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zdqjudy.top/Article/details/gtsjsvbihh.html

Go:   name := "Alex"; age := 20
来源：http://dali.cqqwz.cn/Article/details/gtsphbdljd.html

Ruby: name = "Alex"; age = 20
来源：http://dali.dashuyun.cn/Article/details/gttzaupdib.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.snrcjt.cn/Article/details/gtpauyaluk.html

[A03] 常量定义
来源：http://dali.dashuyun.cn/Article/details/gtsyxazzvj.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.sweek.top/Article/details/gtxxkkcxrb.html

PHP:  const PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gthgbpkgdy.html

JS:   const PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtjqtxifhu.html

TS:   const PI: number = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtadrvbnzs.html

Java: static final double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtgyrpgmax.html

Go:   const PI = 3.14159
来源：http://dali.bjfxy.top/Article/details/gtrgvbigsn.html

Ruby: PI = 3.14159
来源：http://dali.zhengqikj.top/Article/details/gtlftaieaw.html

C#:   const double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtztkzdzgb.html

[A04] 判断变量类型
来源：http://dali.hfpthk.cn/Article/details/gtjzltgfnn.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.bjfxy.top/Article/details/gtpcqetjqv.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.pengpengdd.cyou/Article/details/gteghwlqyi.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.andypj.xyz/Article/details/gtiiypcauk.html

TS:   typeof x; x instanceof Date
来源：http://dali.sufxvd.cn/Article/details/gttlwbngdz.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.quarkkingdee.top/Article/details/gtkhsoeuzv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.chenlongwang.top/Article/details/gtdbowroqn.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.svipenyu.cn/Article/details/gthsigxtjv.html

C#:   x.GetType().Name; x is int
来源：http://dali.hfpthk.cn/Article/details/gthmdmkbnz.html

[A05] 整数除法与取模
来源：http://dali.jlsjyb.cn/Article/details/gtckjpumdf.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.hfpthk.cn/Article/details/gtkalilatr.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.wangshuangyany.cn/Article/details/gtqmbyrmio.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gtdnklnwpm.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.andypj.xyz/Article/details/gtckcpuepc.html

Java: 7 / 2; 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtdaceikpn.html

Go:   7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gtxpmnvrja.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumytwhgh.html

C#:   7 / 2; 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gttykpsgrg.html

[A06] 字符串转数字
来源：http://dali.shangyingyoupin.top/Article/details/gtewggskxy.html

Py:   int("42"); float("3.14")
来源：http://dali.9152youxi.cn/Article/details/gtbbkctbfr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yuanzhike.top/Article/details/gtxemkpaxh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jinqigfzy.top/Article/details/gtvraxvwcb.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.haohaochexian.top/Article/details/gttrrvoivg.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.tanke756.top/Article/details/gtdcjkxknv.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.smart0.xyz/Article/details/gtldyzveze.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.vqdsnc.cn/Article/details/gtlwklrnsx.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xuetiantiany.cn/Article/details/gttqfvmzsu.html

[A07] 数字转字符串
来源：http://dali.tian-w.cn/Article/details/gtpswhduql.html

Py:   str(42)
来源：http://dali.yueranfly.top/Article/details/gtwbakiiki.html

PHP:  (string) 42; strval(42)
来源：http://dali.yonumen.top/Article/details/gtyranugch.html

JS:   String(42); (42).toString()
来源：http://dali.aibaodan.cn/Article/details/gtwyflcjte.html

TS:   String(42)
来源：http://dali.yj20258.top/Article/details/gterwycaex.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yanxiufei.cn/Article/details/gtjrwrjngu.html

Go:   strconv.Itoa(42)
来源：http://dali.fzhhl.top/Article/details/gtfxvcohwl.html

Ruby: 42.to_s
来源：http://dali.jqgfzy.top/Article/details/gtkwffduwz.html

C#:   42.ToString()
来源：http://dali.zhoulong.xyz/Article/details/gtqvcyxdrp.html

[A08] 取整与四舍五入
来源：http://dali.tanke756.top/Article/details/gtwjwzpztv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.andypj.xyz/Article/details/gtckpuqpcy.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hongshengwenyu.top/Article/details/gteiqqellw.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yanxiufei.cn/Article/details/gtjvbvzfvl.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.xinyue.icu/Article/details/gtobzjtabq.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.wangshuangyany.cn/Article/details/gtncavrmmo.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.9152youxi.cn/Article/details/gtydefhosu.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.tian-w.cn/Article/details/gtjqggrlrs.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yueranfly.top/Article/details/gtkszqbgfg.html

[A09] 绝对值与最大最小值
来源：http://dali.yj20258.top/Article/details/gtprkqhryc.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.daxiang520.top/Article/details/gtzpgywgzj.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtwwjyfaqb.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.shuidangran.top/Article/details/gtvgqbilat.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.cheryme.top/Article/details/gtrlxajvbi.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yuanzhike.top/Article/details/gtlkvlckhs.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.birdmap.top/Article/details/gteupmjqon.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.0kj1m.cn/Article/details/gtzolxxtsl.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.sysykeji.top/Article/details/gtjurivvaq.html

[A10] 生成随机数
来源：http://dali.jinqigufen.top/Article/details/gtnuqdpyao.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yuanzhike.top/Article/details/gtxfusgxwq.html

PHP:  random_int(1, 100);
来源：http://dali.hammf.cn/Article/details/gtotbtsxyf.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtplfvnlvo.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.chenjidiqi.icu/Article/details/gtrqrutore.html

Java: new Random().nextInt(100) + 1
来源：http://dali.9152youxi.cn/Article/details/gtetsmrrex.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.nanxinkj.top/Article/details/gtlsywipji.html

Ruby: rand(1..100)
来源：http://dali.ivvv.top/Article/details/gtnsvtpqqw.html

C#:   new Random().Next(1, 101)
来源：http://dali.dashuyun.cn/Article/details/gtbmjsqevm.html

[A11] 条件表达式（三元）
来源：http://dali.jianghu66.top/Article/details/gtksypogqe.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.sysykeji.top/Article/details/gtqgnfaugr.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hnqzz.top/Article/details/gtiscziovq.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yj20258.top/Article/details/gticiewybo.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.shzxlz.cn/Article/details/gthvnxzyna.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.haohaochexian.top/Article/details/gtloazjoft.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.svipenyu.cn/Article/details/gteyzbahpc.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.sufxvd.cn/Article/details/gtxmjhtvog.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.birdmap.top/Article/details/gtltgrmkko.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhengqikj.top/Article/details/gttienmuiy.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.aizwys.cn/Article/details/gtslsqjief.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.hfpthk.cn/Article/details/gtntcmbkzi.html

JS:   `Hello, ${name}!`
来源：http://dali.316326.xyz/Article/details/gtffgqpuqu.html

TS:   `Hello, ${name}!`
来源：http://dali.smart0.xyz/Article/details/gtjamxnrtt.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.shuidangran.top/Article/details/gtzxpepvwv.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.hnqzz.top/Article/details/gtmvqzvqbx.html

Ruby: "Hello, #{name}!"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtznqijkwn.html

C#:   $"Hello, {name}!"
来源：http://dali.jianghu66.top/Article/details/gtelixegeu.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.chenzaomai.com/Article/details/gtjhzbdfyz.html

Py:   "第一行\n第二行"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezmzsjqb.html

PHP:  "第一行\n第二行"
来源：http://dali.xylfe.cn/Article/details/gtzzujngjj.html

JS:   "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gtqmggphbi.html

TS:   "第一行\n第二行"
来源：http://dali.shuidangran.top/Article/details/gtabgorebr.html

Java: "第一行\n第二行"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoksrwqxy.html

Go:   "第一行\n第二行"
来源：http://dali.jinqigufen.top/Article/details/gttjikblhw.html

Ruby: "第一行\n第二行"
来源：http://dali.ppjwa.cn/Article/details/gtryyluonk.html

C#:   "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gtvueqrweh.html

[A14] 注释写法
来源：http://dali.tianlin.xyz/Article/details/gtqccfdrbe.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.chenlongwang.top/Article/details/gtcpkvhpvw.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.pengpengdd.cyou/Article/details/gtqtbyhdrh.html

JS:   // 单行；/* 多行 */
来源：http://dali.jianghu66.top/Article/details/gtsxfconwu.html

TS:   // 单行；/* 多行 */
来源：http://dali.tanke756.top/Article/details/gtfxsccnpz.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hongshengwenyu.top/Article/details/gtzqocgkiu.html

Go:   // 单行；/* 多行 */
来源：http://dali.shzxlz.cn/Article/details/gtnpvvrtfa.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.shanyushiyangtech.top/Article/details/gtphzvriud.html

C#:   // 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gtbmsdunib.html

[A15] 空值判断与默认值
来源：http://dali.cheryme.top/Article/details/gtkelenipj.html

Py:   value = data or "默认值"
来源：http://dali.yvedp.cn/Article/details/gttqwbyvav.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.shuidangran.top/Article/details/gtmimusimh.html


<!-- 参考信息 -->