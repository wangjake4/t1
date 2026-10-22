代发 wailian999

[U93] JS：模板字符串
来源：http://dali.andypj.xyz/Article/details/gtmaxbsgbm.html

`共 ${n} 条`
来源：http://dali.yongpay.top/Article/details/gtlofrfxga.html

[U94] JS：箭头函数
来源：http://dali.nwbrower.top/Article/details/gtymyglkjk.html

const double = x => x * 2;
来源：http://dali.9152youxi.cn/Article/details/gtojdywavr.html

[U95] JS：Promise 包装
来源：http://dali.sxryk.cn/Article/details/gtlcucoofw.html

new Promise((resolve, reject) => {})
来源：http://dali.9152youxi.cn/Article/details/gtudwykyct.html

[U96] JS：async/await 与异常
来源：http://dali.vqdsnc.cn/Article/details/gtbqdygekl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtegfwcrhg.html

[U97] JS：并发请求
来源：http://dali.xylfe.cn/Article/details/gtzrguulub.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gtgdgeozch.html

[U98] JS：fetch 带 JSON
来源：http://dali.0kj1m.cn/Article/details/gtemauxpns.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shuidangran.top/Article/details/gtytkzshfv.html

[U99] JS：事件监听
来源：http://dali.nanxinkj.top/Article/details/gttygoqxhs.html

el.addEventListener("click", e => {})
来源：http://dali.zhixingplan.top/Article/details/gtzkidlcwg.html

[U100] JS：DOM 查询
来源：http://dali.yuanzhike.top/Article/details/gtvvqfsufs.html

document.querySelector(".item")
来源：http://dali.xuetiantiany.cn/Article/details/gtiywltbzh.html

[U101] JS：classList 操作
来源：http://dali.yangfankeji.com/Article/details/gtqrcvcrmd.html

el.classList.toggle("active")
来源：http://dali.xuetiantiany.cn/Article/details/gtqnqfylfn.html

[U102] JS：本地存储
来源：http://dali.chenzaomai.com/Article/details/gtrybvmfae.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhengqikj.top/Article/details/gtfssebxkl.html

[U103] JS：定时器
来源：http://dali.smart0.xyz/Article/details/gtugshsijf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinqigufen.top/Article/details/gtlxqkgvrv.html

[U104] JS：防抖
来源：http://dali.9152youxi.cn/Article/details/gtlhompcor.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gtolrwidts.html

[U105] JS：节流
来源：http://dali.pycfn.com/Article/details/gtwwncduyv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.vqdsnc.cn/Article/details/gtdfsqqoui.html

[U106] JS：日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gtajrxczou.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.andypj.xyz/Article/details/gtsuzplvlk.html

[U107] JS：数字千分位
来源：http://dali.tianlin.xyz/Article/details/gtliiqdkbv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gtyzmddemc.html

[U108] JS：随机整数
来源：http://dali.vqdsnc.cn/Article/details/gtbfwzjvtn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.dashuyun.cn/Article/details/gtawpnqrdi.html

[U109] JS：数组分组
来源：http://dali.jiagoushi.top/Article/details/gtmpatvkud.html

Object.groupBy(arr, x => x.type)
来源：http://dali.havefunace.top/Article/details/gtnmyieieq.html

[U110] JS：数组分块
来源：http://dali.hnxiangtu.top/Article/details/gtqfxijiis.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.kuanghao11.cn/Article/details/gtfmlalhxl.html

[U111] JS：对象转 Map
来源：http://dali.jqgufenzy.top/Article/details/gtkdjmenyc.html

new Map(Object.entries(obj))
来源：http://dali.zhoulong.xyz/Article/details/gtljuidock.html

[U112] JS：字符串补位
来源：http://dali.gogol.net.cn/Article/details/gttzvidevu.html

"7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtemoxqctf.html

[U113] JS：正则替换全部
来源：http://dali.zhengqikj.top/Article/details/gtdlvlgenn.html

s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtsojzdhbr.html

[U114] JS：JSON 深比较
来源：http://dali.zycfv.cn/Article/details/gtfclavlql.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gogol.net.cn/Article/details/gtnskxvbtz.html

[U115] JS：生成 UUID
来源：http://dali.yvedp.cn/Article/details/gtwmvwiwos.html

crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gtsfrpkvrt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.sxryk.cn/Article/details/gtcrmawvrh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtkmxmhbnr.html

[U117] JS：单元测试
来源：http://dali.ppjwa.cn/Article/details/gtnxkerjum.html

npm i -D vitest;  npx vitest
来源：http://dali.redwolf501.top/Article/details/gtaqkzyttr.html

[U118] JS：开发服务器
来源：http://dali.kuanghao11.cn/Article/details/gtyrsistzp.html

npm i -D vite;  npx vite
来源：http://dali.cucudq.cn/Article/details/gtsnkmezmk.html

[U119] JS：生产构建
来源：http://dali.smart0.xyz/Article/details/gtxymbhnvk.html

npx vite build
来源：http://dali.xuetiantiany.cn/Article/details/gtmpkmlmfs.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yuanzhike.top/Article/details/gtjyypjlya.html

import.meta.env.VITE_API_URL
来源：http://dali.sweek.top/Article/details/gtoptcnsig.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtqhvwfngv.html

统计汇总
来源：http://dali.zdqjudy.top/Article/details/gteapgqfhb.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtjuoplpqd.html

按语言统计（条）：
来源：http://dali.chenjidiqi.icu/Article/details/gtoliheiqe.html

Python ......... 252
来源：http://dali.yj20258888.top/Article/details/gtytcdnuen.html

PHP ............ 252
来源：http://dali.shangyingyoupin.top/Article/details/gtyqtznzrt.html

JavaScript ..... 252
来源：http://dali.hywenlv.cn/Article/details/gtcvgehrqs.html

TypeScript ..... 212
来源：http://dali.yueranfly.top/Article/details/gtjiiskftr.html

Java ........... 212
来源：http://dali.kuanghao11.cn/Article/details/gtqttfjlic.html

Go ............. 212
来源：http://dali.chenlongwang.top/Article/details/gtmynirrsh.html

Ruby ........... 212
来源：http://dali.pengpengdd.cyou/Article/details/gtsciazgak.html

C# ............. 212
来源：http://dali.wangdashe.top/Article/details/gtfbmgzkyy.html

C .............. 30
来源：http://dali.tian-w.cn/Article/details/gttjiejhpk.html

C++ ............ 30
来源：http://dali.gaohongyu789.top/Article/details/gtkihbkgbh.html

SQL ............ 90
来源：http://dali.iojbl.cn/Article/details/gtnatsjgcd.html

Bash ........... 80
来源：http://dali.ppjwa.cn/Article/details/gtvlrwlcwl.html

Kotlin ......... 15
来源：http://dali.c1oappe.top/Article/details/gtweafsera.html

Swift .......... 15
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvboquamy.html

Lua ............ 10
来源：http://dali.vqdsnc.cn/Article/details/gtgtpoycmt.html

Perl ........... 10
来源：http://dali.jiagoushi.top/Article/details/gtzorqxidp.html

Scala .......... 10
来源：http://dali.jyoumei.cn/Article/details/gtiroyzdso.html

------------------------------------
来源：http://dali.hammf.cn/Article/details/gtthforzxs.html

合计 ........... 2106 条
来源：http://dali.yj20258.top/Article/details/gtmbvcvwvf.html

按章节统计：
来源：http://dali.jiagoushi.top/Article/details/gtnefnepgj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sxryk.cn/Article/details/gtnlwibiqy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yuxming.cn/Article/details/gtowqxwrup.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.tanke756.top/Article/details/gtyakedeze.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shzxlz.cn/Article/details/gtjzziydgj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.pengpengdd.cyou/Article/details/gtplefkmyi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.wangdashe.top/Article/details/gtgvqbbetr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.bjfxy.top/Article/details/gtxpaljbes.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.kuanghao11.cn/Article/details/gtnsiccsfy.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gtyvivmgla.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.kuanghao11.cn/Article/details/gtvylsbpcw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gtsuuliglp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gtoxttjvhy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gtyfnjftgj.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.aizwys.cn/Article/details/gtddvtmiyh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.redwolf501.top/Article/details/gtxohyxlvw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gtultrgvqa.html

Q SQL 专题                              90
来源：http://dali.feifeiyinyue.top/Article/details/gtlltkhknh.html

R Bash 专题                             80
来源：http://dali.cdnleiting.top/Article/details/gthyyxoauu.html

S C / C++ 专题                          60
来源：http://dali.kuanghao11.cn/Article/details/gtphdrugxk.html

T 其他语言补充                          60
来源：http://dali.zhiwuduotai.top/Article/details/gttxfurtib.html

U 高频实用片段                         120
来源：http://dali.iojbl.cn/Article/details/gtplyooads.html

------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gtcivzjdro.html

合计                                  2106 条
来源：http://dali.nanxuanxn.top/Article/details/gtbnsrkqje.html

--------------------------------------------------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gtsxubrqnk.html

使用提醒
来源：http://dali.meibo888.top/Article/details/gtsirpvtfn.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtkhfgbzms.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhoulong.xyz/Article/details/gtmsabctzd.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhixingplan.top/Article/details/gtiwzilmaj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.daria6918.cn/Article/details/gtlbpmpswf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jqgufenzy.top/Article/details/gtdymepauw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hnxiangtu.top/Article/details/gtkpovrdqu.html

—— 文件结束 ——
来源：http://dali.svipenyu.cn/Article/details/gtpfkestla.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtpjhxltye.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhixingplan.top/Article/details/gtxxseytvn.html

Common Programming Examples Cheat Book
来源：http://dali.wangdashe.top/Article/details/gtnbnungfv.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtghdoojxo.html

【收录内容】
来源：http://dali.dianchejie.cn/Article/details/gtcwcnkkzc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.gaohongyu789.top/Article/details/gtqgsdfpri.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.tanke756.top/Article/details/gtcjrsrbfq.html

SQL · Bash · C · C++
来源：http://dali.hywenlv.cn/Article/details/gtxayfvqdw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xinyue.icu/Article/details/gtrduacatq.html

【使用说明】
来源：http://dali.shuidangran.top/Article/details/gtbcrtdtjc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.nwbrower.top/Article/details/gthqtrzpyk.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.c1oappe.top/Article/details/gtharddlxc.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xuetiantiany.cn/Article/details/gtnctrrrsh.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.316326.xyz/Article/details/gtaxkwqfle.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xuanzx.com/Article/details/gtnxyvhwtq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ybcxt.top/Article/details/gtdbvnnlll.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.wangshuangyany.cn/Article/details/gtnwuqumll.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.vqdsnc.cn/Article/details/gtyzlxhahh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jiagoushi.top/Article/details/gtishayfxn.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.iojbl.cn/Article/details/gtixiwlqzs.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.tianlin.xyz/Article/details/gtjthtlwhd.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.c1oappe.top/Article/details/gtwufondqo.html

【文件统计】
来源：http://dali.yanxiufei.cn/Article/details/gtkdvhwiig.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yvedp.cn/Article/details/gtlwpuhkct.html

--------------------------------------------------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjoquywa.html

目  录
来源：http://dali.zhixingplan.top/Article/details/gtohjesmve.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gtzvwvonik.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jyoumei.cn/Article/details/gtuprrbkib.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zycfv.cn/Article/details/gtmfokrtxl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.sysykeji.top/Article/details/gteuhriqow.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.sufxvd.cn/Article/details/gtisezkjgc.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtheducuaq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.nwbrower.top/Article/details/gtehhsuuuk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.pycfn.com/Article/details/gttwzwcrin.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.kuanghao11.cn/Article/details/gtruwrejyy.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gttyrprkij.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtshrfzqed.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jiagoushi.top/Article/details/gtluirvxkg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.shzxlz.cn/Article/details/gthpukmuyi.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gtkhfqccel.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.guannengcc.top/Article/details/gtmqjkwmwi.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jyoumei.cn/Article/details/gtknctgmlv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gtajhwiemg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.0kj1m.cn/Article/details/gtqekjuskp.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hongshengwenyu.top/Article/details/gttckzvfch.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.sysykeji.top/Article/details/gthatmynpl.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.c1oappe.top/Article/details/gtojtukbil.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.nwbrower.top/Article/details/gtfernprkv.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtqyflxahg.html

A. 基础语法与类型
来源：http://dali.guannengcc.top/Article/details/gtbezkcuol.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtifndbdru.html

[A01] Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtflprdkst.html

Py:   print("Hello, World!")
来源：http://dali.dianchejie.cn/Article/details/gtdynqwhrq.html

PHP:  echo "Hello, World!";
来源：http://dali.kuanghao11.cn/Article/details/gtgaeglfzu.html

JS:   console.log("Hello, World!");
来源：http://dali.yj202588.top/Article/details/gthqmkjnfo.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.c1oappe.top/Article/details/gtawjyrmxi.html

Java: System.out.println("Hello, World!");
来源：http://dali.redwolf501.top/Article/details/gtzpaiotyd.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.9152youxi.cn/Article/details/gtpuqfrcbl.html

Ruby: puts "Hello, World!"
来源：http://dali.snrcjt.cn/Article/details/gtttzwcxbo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hysaishi.cn/Article/details/gtohqpuwbh.html

[A02] 变量声明与赋值
来源：http://dali.sysykeji.top/Article/details/gtltindhix.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhongyouzk.top/Article/details/gthnuqvolx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.cashguo.top/Article/details/gtqtierfxv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yj202588.top/Article/details/gtjfrahioq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yangfankeji.com/Article/details/gtkdahiifu.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.cheryme.top/Article/details/gtopneverw.html

Go:   name := "Alex"; age := 20
来源：http://dali.shuidangran.top/Article/details/gtgexybkyw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.smart0.xyz/Article/details/gtafwonfcq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.smart0.xyz/Article/details/gtrvdlymce.html

[A03] 常量定义
来源：http://dali.yueranfly.top/Article/details/gtttfyopda.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.vqdsnc.cn/Article/details/gtmrjykvvq.html

PHP:  const PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtajggdgzj.html

JS:   const PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gtzoiklcjb.html

TS:   const PI: number = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtcjbxysvb.html

Java: static final double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtodkcjvbp.html

Go:   const PI = 3.14159
来源：http://dali.ppjwa.cn/Article/details/gtdyuxmcli.html

Ruby: PI = 3.14159
来源：http://dali.ivvv.top/Article/details/gtusxildrh.html

C#:   const double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtpzlgihii.html

[A04] 判断变量类型
来源：http://dali.daxiang520.top/Article/details/gtuxvakfun.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzxjwsim.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.316326.xyz/Article/details/gtezqlljiy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.nanxinkj.top/Article/details/gtjblslpwa.html

TS:   typeof x; x instanceof Date
来源：http://dali.yj202588.top/Article/details/gtrjwdqsvs.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.daria6918.cn/Article/details/gtnwilhgsz.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.redwolf501.top/Article/details/gtgejmmwyf.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.chenzaomai.com/Article/details/gtosujvqpi.html

C#:   x.GetType().Name; x is int
来源：http://dali.yj20258888.top/Article/details/gtkfsikzwz.html

[A05] 整数除法与取模
来源：http://dali.gzhubu.top/Article/details/gtfavosbwg.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.vqdsnc.cn/Article/details/gtbfrqywss.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gtdeojkwzb.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtganogyxa.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.316326.xyz/Article/details/gtcmzwjond.html

Java: 7 / 2; 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gtixynbeae.html

Go:   7 / 2; 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtzmjmfhfv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gtgtcbicyg.html

C#:   7 / 2; 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gtptxrmrsa.html

[A06] 字符串转数字
来源：http://dali.svipenyu.cn/Article/details/gtswfivrjb.html

Py:   int("42"); float("3.14")
来源：http://dali.aibaodan.cn/Article/details/gtfrvgssvb.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cqqwz.cn/Article/details/gtxxwuuiqm.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.redwolf501.top/Article/details/gtpbzkjixw.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hongshengwenyu.top/Article/details/gtbbwcoqri.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedqrormm.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hysaishi.cn/Article/details/gtytwhrpyv.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhixingplan.top/Article/details/gtijzeoffq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xziqi.cn/Article/details/gtcqjqhudk.html

[A07] 数字转字符串
来源：http://dali.jqgfzy.top/Article/details/gtyjztezxr.html

Py:   str(42)
来源：http://dali.kuanghao11.cn/Article/details/gthjojwqtc.html

PHP:  (string) 42; strval(42)
来源：http://dali.aizwys.cn/Article/details/gtyjvwtrsv.html

JS:   String(42); (42).toString()
来源：http://dali.smart0.xyz/Article/details/gteojulule.html

TS:   String(42)
来源：http://dali.tianlin.xyz/Article/details/gtgchyhjxs.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.gogol.net.cn/Article/details/gtpkiqeccb.html

Go:   strconv.Itoa(42)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtemwdbrta.html

Ruby: 42.to_s
来源：http://dali.jqgfzy.top/Article/details/gtvooyyzoy.html

C#:   42.ToString()
来源：http://dali.316326.xyz/Article/details/gtvzuzmphz.html

[A08] 取整与四舍五入
来源：http://dali.birdmap.top/Article/details/gtdcfnuysw.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jinqigufen.top/Article/details/gthhmiupny.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jiagoushi.top/Article/details/gttnxrggty.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.chenzaomai.com/Article/details/gttevfsscz.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yongpay.top/Article/details/gtcyawqkaq.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.cucudq.cn/Article/details/gtgcpaaprl.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.meibo888.top/Article/details/gtjovcttfm.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.aizwys.cn/Article/details/gtyrrpseyu.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.gzhubu.top/Article/details/gtskeicyam.html

[A09] 绝对值与最大最小值
来源：http://dali.yj20258888.top/Article/details/gtkzlgnznh.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxkwslbp.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtqsmvuvne.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gtaqqggacq.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.sysykeji.top/Article/details/gtiodgacaz.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gtgjjpujqv.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.cheryme.top/Article/details/gtkrtppeni.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhixingplan.top/Article/details/gtybzhtyik.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yongpay.top/Article/details/gtgjdmiifn.html

[A10] 生成随机数
来源：http://dali.shuidangran.top/Article/details/gtbfohnwed.html

Py:   import random; random.randint(1, 100)
来源：http://dali.bjfxy.top/Article/details/gtfbeymkny.html

PHP:  random_int(1, 100);
来源：http://dali.sufxvd.cn/Article/details/gteppaoefk.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xuanzx.com/Article/details/gtesbnoowm.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.haohaochexian.top/Article/details/gtulfknyho.html

Java: new Random().nextInt(100) + 1
来源：http://dali.wangshuangyany.cn/Article/details/gtlwvnpbnt.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hfpthk.cn/Article/details/gtxluhvsyo.html

Ruby: rand(1..100)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmlyfqcmg.html

C#:   new Random().Next(1, 101)
来源：http://dali.jinqigufen.top/Article/details/gtcpugfmxt.html

[A11] 条件表达式（三元）
来源：http://dali.meibo888.top/Article/details/gtawgzkftf.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.chenlongwang.top/Article/details/gtrjbbcknm.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gtjggdjsxo.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.redwolf501.top/Article/details/gtapmmyxms.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.hysaishi.cn/Article/details/gtqvtfouvn.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.gotoacloud.top/Article/details/gtnxrphrmw.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcerbyqdj.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jianghu66.top/Article/details/gtscjuewwq.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.gogol.net.cn/Article/details/gtkbazwfgs.html

[A12] 字符串插值 / 格式化
来源：http://dali.yj202588.top/Article/details/gtteutkkkx.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.cashguo.top/Article/details/gtkzpxzeyk.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.xuanzx.com/Article/details/gtobwrvhbo.html

JS:   `Hello, ${name}!`
来源：http://dali.ybcxt.top/Article/details/gtfdmdctly.html

TS:   `Hello, ${name}!`
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbglfnydd.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.hywenlv.cn/Article/details/gthndxyvis.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.9152youxi.cn/Article/details/gtxanswhos.html

Ruby: "Hello, #{name}!"
来源：http://dali.xuetiantiany.cn/Article/details/gtlbepicsp.html

C#:   $"Hello, {name}!"
来源：http://dali.xziqi.cn/Article/details/gtamyedfel.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yuanzhike.top/Article/details/gtefhainju.html

Py:   "第一行\n第二行"
来源：http://dali.ivvv.top/Article/details/gttxucugdy.html

PHP:  "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gtbjbdzuhq.html

JS:   "第一行\n第二行"
来源：http://dali.jinghuilouyu.cn/Article/details/gtenzbbcqm.html

TS:   "第一行\n第二行"
来源：http://dali.jinqigfzy.top/Article/details/gtbwjyadum.html

Java: "第一行\n第二行"
来源：http://dali.wangdashe.top/Article/details/gtjjlsksdt.html

Go:   "第一行\n第二行"
来源：http://dali.shangyingyoupin.top/Article/details/gtlzhrjush.html

Ruby: "第一行\n第二行"
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtwgzbnq.html

C#:   "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gtixefsubf.html

[A14] 注释写法
来源：http://dali.cucudq.cn/Article/details/gtawgrjyrk.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.chenzaomai.com/Article/details/gtawbczmfn.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zycfv.cn/Article/details/gthjlbrbls.html

JS:   // 单行；/* 多行 */
来源：http://dali.aibaodan.cn/Article/details/gtzfpdcrpl.html

TS:   // 单行；/* 多行 */
来源：http://dali.shuidangran.top/Article/details/gtfjhjyjvv.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.gzhubu.top/Article/details/gtdrdcgoer.html

Go:   // 单行；/* 多行 */
来源：http://dali.hfpthk.cn/Article/details/gtfhyemefh.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.birdmap.top/Article/details/gtewunkqqw.html

C#:   // 单行；/* 多行 */
来源：http://dali.yueranfly.top/Article/details/gtuiikwels.html

[A15] 空值判断与默认值
来源：http://dali.snrcjt.cn/Article/details/gtzwouwmnf.html

Py:   value = data or "默认值"
来源：http://dali.hfpthk.cn/Article/details/gtiqhrbmtr.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhoulong.xyz/Article/details/gtzgznigpr.html

JS:   const value = data ?? "默认值";
来源：http://dali.xylfe.cn/Article/details/gtrdzkfddr.html

TS:   const value = data ?? "默认值";
来源：http://dali.hongshengwenyu.top/Article/details/gtbgozerlc.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.quarkkingdee.top/Article/details/gtmzsrhnfi.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.ybcxt.top/Article/details/gtfoqowrco.html

Ruby: value = data || "默认值"
来源：http://dali.nanxuanxn.top/Article/details/gttuwxkzkf.html

C#:   var value = data ?? "默认值";
来源：http://dali.hywenlv.cn/Article/details/gtjchtsxqo.html

[A16] 真假值判断规则
来源：http://dali.daxiang520.top/Article/details/gtrtkfkcpg.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwahdulp.html


<!-- 参考信息 -->