代发 wailian999

[U97] JS：并发请求
来源：http://dali.zhoulong.xyz/Article/details/gt2nipdjany.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.mhx1999.top/Article/details/gt2wdorafht.html

[U98] JS：fetch 带 JSON
来源：http://dali.smart0.xyz/Article/details/gt2qrpcctzj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hnxiangtu.top/Article/details/gt2bxdabcvc.html

[U99] JS：事件监听
来源：http://dali.jinqigufen.top/Article/details/gt2ywseddpa.html

el.addEventListener("click", e => {})
来源：http://dali.gaohongyu789.top/Article/details/gt2kirnpzqy.html

[U100] JS：DOM 查询
来源：http://dali.birdmap.top/Article/details/gt2cfxejtlz.html

document.querySelector(".item")
来源：http://dali.gaohongyu789.top/Article/details/gt2zknzfesu.html

[U101] JS：classList 操作
来源：http://dali.kuanghao11.cn/Article/details/gt2qtejhckj.html

el.classList.toggle("active")
来源：http://dali.tian-w.cn/Article/details/gt2kakqktkp.html

[U102] JS：本地存储
来源：http://dali.cdnleiting.top/Article/details/gt2vttincvn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.daria6918.cn/Article/details/gt2hvtdestf.html

[U103] JS：定时器
来源：http://dali.c1oappe.top/Article/details/gt2rpjjlcwd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sbnnbpkp.html

[U104] JS：防抖
来源：http://dali.jlsjyb.cn/Article/details/gt2ggjzjsub.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gt2ygqokyxu.html

[U105] JS：节流
来源：http://dali.pengpengdd.cyou/Article/details/gt2safibwii.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.fzhhl.top/Article/details/gt2lgzzygie.html

[U106] JS：日期格式化
来源：http://dali.cdnleiting.top/Article/details/gt2cgmctbba.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.9152youxi.cn/Article/details/gt2ksvievmk.html

[U107] JS：数字千分位
来源：http://dali.tianlin.xyz/Article/details/gt2odgvgyxi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zybzeyot.html

[U108] JS：随机整数
来源：http://dali.cqqwz.cn/Article/details/gt2kspvsxro.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yuanzhike.top/Article/details/gt2vhkixirw.html

[U109] JS：数组分组
来源：http://dali.yj202588.top/Article/details/gt2moguegmp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cucudq.cn/Article/details/gt2cuoqyywy.html

[U110] JS：数组分块
来源：http://dali.guowangkeji.top/Article/details/gt2fomwakud.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shzxlz.cn/Article/details/gt2xzziqgxd.html

[U111] JS：对象转 Map
来源：http://dali.jyoumei.cn/Article/details/gt2luyvfjen.html

new Map(Object.entries(obj))
来源：http://dali.cucudq.cn/Article/details/gt2nqqjjams.html

[U112] JS：字符串补位
来源：http://dali.shangyingyoupin.top/Article/details/gt2zjztfusw.html

"7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gt2ozswquhc.html

[U113] JS：正则替换全部
来源：http://dali.0kj1m.cn/Article/details/gt2nxrviddc.html

s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gt2wecladku.html

[U114] JS：JSON 深比较
来源：http://dali.tianlin.xyz/Article/details/gt2qptwbcex.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.iojbl.cn/Article/details/gt2jznqkjkd.html

[U115] JS：生成 UUID
来源：http://dali.jlsjyb.cn/Article/details/gt2nyzkcybi.html

crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gt2wmaqoghj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.svipenyu.cn/Article/details/gt2dtmwkerh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cucudq.cn/Article/details/gt2qptuuyub.html

[U117] JS：单元测试
来源：http://dali.cheryme.top/Article/details/gt2mxsoqxpl.html

npm i -D vitest;  npx vitest
来源：http://dali.xuanzx.com/Article/details/gt2nioietit.html

[U118] JS：开发服务器
来源：http://dali.zhixingplan.top/Article/details/gt2licvzonw.html

npm i -D vite;  npx vite
来源：http://dali.yj20258.top/Article/details/gt2pjeerhkn.html

[U119] JS：生产构建
来源：http://dali.316326.xyz/Article/details/gt2bwulwzbf.html

npx vite build
来源：http://dali.mhx1999.top/Article/details/gt2ecdcucrt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.mhx1999.top/Article/details/gt2uhceiadh.html

import.meta.env.VITE_API_URL
来源：http://dali.wangdashe.top/Article/details/gt2vadkynke.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2zucstltv.html

统计汇总
来源：http://dali.yj202588.top/Article/details/gt2jzszlamh.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2hfydvggv.html

按语言统计（条）：
来源：http://dali.redwolf501.top/Article/details/gt2pzplmcrx.html

Python ......... 252
来源：http://dali.svipenyu.cn/Article/details/gt2hmopmrsk.html

PHP ............ 252
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gqsydcge.html

JavaScript ..... 252
来源：http://dali.cqqwz.cn/Article/details/gt2balvkmxh.html

TypeScript ..... 212
来源：http://dali.aibaodan.cn/Article/details/gt2zrdrdfje.html

Java ........... 212
来源：http://dali.guowangkeji.top/Article/details/gt2newfkvzv.html

Go ............. 212
来源：http://dali.mhx1999.top/Article/details/gt2oftmdlgh.html

Ruby ........... 212
来源：http://dali.havefunace.top/Article/details/gt2shiodzbv.html

C# ............. 212
来源：http://dali.guannengcc.top/Article/details/gt2ssdvdmpt.html

C .............. 30
来源：http://dali.316326.xyz/Article/details/gt2lxuqafra.html

C++ ............ 30
来源：http://dali.zhongyouzk.top/Article/details/gt2taqnfdof.html

SQL ............ 90
来源：http://dali.fzhhl.top/Article/details/gt2obppoaix.html

Bash ........... 80
来源：http://dali.jianghu66.top/Article/details/gt2ecvpikzy.html

Kotlin ......... 15
来源：http://dali.haohaochexian.top/Article/details/gt2tztltrkx.html

Swift .......... 15
来源：http://dali.zhengqikj.top/Article/details/gt2idswmotn.html

Lua ............ 10
来源：http://dali.zdqjudy.top/Article/details/gt2pcmqqxop.html

Perl ........... 10
来源：http://dali.jianghu66.top/Article/details/gt2opdffrmh.html

Scala .......... 10
来源：http://dali.sufxvd.cn/Article/details/gt2odghqrwg.html

------------------------------------
来源：http://dali.yueranfly.top/Article/details/gt2bbyljnrz.html

合计 ........... 2106 条
来源：http://dali.smart0.xyz/Article/details/gt2ipvtaudj.html

按章节统计：
来源：http://dali.sysykeji.top/Article/details/gt2icileyxo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.kuanghao11.cn/Article/details/gt2crztmopj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dkjvxeeg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xuanzx.com/Article/details/gt2hwvvlgsb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.wangdashe.top/Article/details/gt2jksrsehl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sxryk.cn/Article/details/gt2thcktrrz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.c1oappe.top/Article/details/gt2wydpfsza.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhiwuduotai.top/Article/details/gt2icqmfzsl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cheryme.top/Article/details/gt2wzoaxzwz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gt2eopeotxg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.c1oappe.top/Article/details/gt2hgvavsxo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gt2iinktlwm.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfyprgv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gt2jasritsx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hywenlv.cn/Article/details/gt2lcquujpn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hongshengwenyu.top/Article/details/gt2tabtkktp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gt2gjpgchxk.html

Q SQL 专题                              90
来源：http://dali.kuanghao11.cn/Article/details/gt2tlflyvin.html

R Bash 专题                             80
来源：http://dali.yj20258888.top/Article/details/gt2xuqeuovm.html

S C / C++ 专题                          60
来源：http://dali.snrcjt.cn/Article/details/gt2ykxjtywk.html

T 其他语言补充                          60
来源：http://dali.wangshuangyany.cn/Article/details/gt2gsdinhfn.html

U 高频实用片段                         120
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ycqkxjru.html

------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gt2zvziylqi.html

合计                                  2106 条
来源：http://dali.dianchejie.cn/Article/details/gt2tzirchmh.html

--------------------------------------------------------------------------------
来源：http://dali.bjfxy.top/Article/details/gt2wogzrdjv.html

使用提醒
来源：http://dali.wangdashe.top/Article/details/gt2mnrqqqop.html

--------------------------------------------------------------------------------
来源：http://dali.meibo888.top/Article/details/gt2xtrotjde.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hnxiangtu.top/Article/details/gt2dauojxuk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hpsvkyoo.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.sysykeji.top/Article/details/gt2pvfvhfgo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.quarkkingdee.top/Article/details/gt2amzncnyh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xuetiantiany.cn/Article/details/gt2vrpjfyjj.html

—— 文件结束 ——
来源：http://dali.zhixingplan.top/Article/details/gt2twfptnxg.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2szkvgnwg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yonumen.top/Article/details/gt2fwvmzdln.html

Common Programming Examples Cheat Book
来源：http://dali.xziqi.cn/Article/details/gt2kmmqvvlh.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2nctmelou.html

【收录内容】
来源：http://dali.snrcjt.cn/Article/details/gt2yauapqkb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cashguo.top/Article/details/gt2cltndcua.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.wangshuangyany.cn/Article/details/gt2rivugdfn.html

SQL · Bash · C · C++
来源：http://dali.cqqwz.cn/Article/details/gt2rrukqwvl.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.guowangkeji.top/Article/details/gt2czjgqrne.html

【使用说明】
来源：http://dali.zhengqikj.top/Article/details/gt2winngvft.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yueranfly.top/Article/details/gt2yxsfkidc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.cdnleiting.top/Article/details/gt2uxmfuram.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ybcxt.top/Article/details/gt2zktyghjp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jinqigfzy.top/Article/details/gt2jqlgxkra.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yuxming.cn/Article/details/gt2fcyzdnel.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.sufxvd.cn/Article/details/gt2ejvloxmc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.daxiang520.top/Article/details/gt2yyalmfmy.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.daxiang520.top/Article/details/gt2lcahyeko.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.guannengcc.top/Article/details/gt2uwpdnqst.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.meibo888.top/Article/details/gt2imsedjhv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhixingplan.top/Article/details/gt2nkuazbhc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.tianlin.xyz/Article/details/gt2zxglufeu.html

【文件统计】
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vcygyzes.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.snrcjt.cn/Article/details/gt2wxumprdp.html

--------------------------------------------------------------------------------
来源：http://dali.daria6918.cn/Article/details/gt2pfvcyefs.html

目  录
来源：http://dali.daria6918.cn/Article/details/gt2naaofvef.html

--------------------------------------------------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rornkkyv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cucudq.cn/Article/details/gt2adqzdxzy.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hfpthk.cn/Article/details/gt2papvokcu.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2heqxoufn.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jubrqfak.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.bjfxy.top/Article/details/gt2vgeynuyk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.pycfn.com/Article/details/gt2yubdsgeh.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.guowangkeji.top/Article/details/gt2xznssggj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.9152youxi.cn/Article/details/gt2xolfebsf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2rtketxeh.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2pgflswff.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gt2ikdzhpvl.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yvedp.cn/Article/details/gt2iqqdkubb.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.chenlongwang.top/Article/details/gt2ixtkxnzb.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.chenzaomai.com/Article/details/gt2pbfxjgrd.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zycfv.cn/Article/details/gt2ymhnnfla.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ycpsoycm.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.havefunace.top/Article/details/gt2rygemzpg.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ehwqpu.com/Article/details/gt2fomwyafg.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.cucudq.cn/Article/details/gt2lzdelers.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gt2unkuqmjy.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jiagoushi.top/Article/details/gt2kgqxfkcy.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2irhuyszd.html

A. 基础语法与类型
来源：http://dali.ybcxt.top/Article/details/gt2oszwozvb.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2sejngoms.html

[A01] Hello World
来源：http://dali.redwolf501.top/Article/details/gt2ndcfaccf.html

Py:   print("Hello, World!")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ukfqcmwn.html

PHP:  echo "Hello, World!";
来源：http://dali.wangdashe.top/Article/details/gt2mivdfuzw.html

JS:   console.log("Hello, World!");
来源：http://dali.dashuyun.cn/Article/details/gt2lppdwiym.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhiwuduotai.top/Article/details/gt2fjhvbyow.html

Java: System.out.println("Hello, World!");
来源：http://dali.hysaishi.cn/Article/details/gt2abtbwtcr.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.pycfn.com/Article/details/gt2qlgtbqex.html

Ruby: puts "Hello, World!"
来源：http://dali.yongpay.top/Article/details/gt2biebfalt.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.cqqwz.cn/Article/details/gt2vmywjrsc.html

[A02] 变量声明与赋值
来源：http://dali.aibaodan.cn/Article/details/gt2eimaigxa.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.nwbrower.top/Article/details/gt2badcwytv.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.haohaochexian.top/Article/details/gt2gguuktvw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.pycfn.com/Article/details/gt2aqnnvmlm.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.fzhhl.top/Article/details/gt2hunuzgth.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.havefunace.top/Article/details/gt2uxrqdgta.html

Go:   name := "Alex"; age := 20
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kcuwanat.html

Ruby: name = "Alex"; age = 20
来源：http://dali.316326.xyz/Article/details/gt2fmpaijjw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.chenlongwang.top/Article/details/gt2txgrhzfs.html

[A03] 常量定义
来源：http://dali.meibo888.top/Article/details/gt2kshzgxec.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hnqzz.top/Article/details/gt2vqaplmse.html

PHP:  const PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gt2utsblxfw.html

JS:   const PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gt2bpvicdfe.html

TS:   const PI: number = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gt2xdubxood.html

Java: static final double PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gt2asccsgbu.html

Go:   const PI = 3.14159
来源：http://dali.0kj1m.cn/Article/details/gt2tcghnpbm.html

Ruby: PI = 3.14159
来源：http://dali.meibo888.top/Article/details/gt2olehrqpc.html

C#:   const double PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gt2pqrxlzth.html

[A04] 判断变量类型
来源：http://dali.jiagoushi.top/Article/details/gt2dgyvolty.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.havefunace.top/Article/details/gt2eyupkwec.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jianghu66.top/Article/details/gt2mgkkucti.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hfpthk.cn/Article/details/gt2shsxhnrx.html

TS:   typeof x; x instanceof Date
来源：http://dali.xinyue.icu/Article/details/gt2ldmwjtss.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yuxming.cn/Article/details/gt2zuxrwneu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hammf.cn/Article/details/gt2zsudkxey.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.pycfn.com/Article/details/gt2qeecxrdu.html

C#:   x.GetType().Name; x is int
来源：http://dali.ydzc1.top/Article/details/gt2mjcgmrhx.html

[A05] 整数除法与取模
来源：http://dali.yongpay.top/Article/details/gt2ixdqbzdt.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wcjctohu.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2furqnelc.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.daxiang520.top/Article/details/gt2ilalibob.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gt2dqcdyckj.html

Java: 7 / 2; 7 % 2
来源：http://dali.xziqi.cn/Article/details/gt2rhishkcg.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gt2wxpbybyf.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.pycfn.com/Article/details/gt2uetvfzkx.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gt2ukmeovej.html

[A06] 字符串转数字
来源：http://dali.gotoacloud.top/Article/details/gt2feebonwj.html

Py:   int("42"); float("3.14")
来源：http://dali.jinqigfzy.top/Article/details/gt2diyygjvs.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vdrfadew.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jiagoushi.top/Article/details/gt2uhwnflmu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.dashuyun.cn/Article/details/gt2pwmdqilu.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ztduahxt.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.aizwys.cn/Article/details/gt2mxwlsmpb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hnxiangtu.top/Article/details/gt2flapntvd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhongyouzk.top/Article/details/gt2mrhgebze.html

[A07] 数字转字符串
来源：http://dali.yueranfly.top/Article/details/gt2jnbbjiwj.html

Py:   str(42)
来源：http://dali.dianchejie.cn/Article/details/gt2zrjdxdcs.html

PHP:  (string) 42; strval(42)
来源：http://dali.mhx1999.top/Article/details/gt2labxlfvw.html

JS:   String(42); (42).toString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2auzdbfvc.html

TS:   String(42)
来源：http://dali.shuidangran.top/Article/details/gt2kdszibzw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pcfefarp.html

Go:   strconv.Itoa(42)
来源：http://dali.shuidangran.top/Article/details/gt2rzsuwlhw.html

Ruby: 42.to_s
来源：http://dali.havefunace.top/Article/details/gt2nwrsmoxx.html

C#:   42.ToString()
来源：http://dali.ppjwa.cn/Article/details/gt2csvxftye.html

[A08] 取整与四舍五入
来源：http://dali.zhoulong.xyz/Article/details/gt2zwlmzfjn.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.daria6918.cn/Article/details/gt2tkqfbuxx.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.gogol.net.cn/Article/details/gt2cockexda.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jlsjyb.cn/Article/details/gt2ssxywhqh.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.havefunace.top/Article/details/gt2zoaytvhy.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.c1oappe.top/Article/details/gt2zbwzanwf.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.chenlongwang.top/Article/details/gt2ucydpuew.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yj20258.top/Article/details/gt2qzqxjgjz.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.aibaodan.cn/Article/details/gt2gptcyuxo.html

[A09] 绝对值与最大最小值
来源：http://dali.sufxvd.cn/Article/details/gt2jvraricj.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.birdmap.top/Article/details/gt2jjpnmjuq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2akqlqtat.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gt2wjyjmnum.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ljpkmqit.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.havefunace.top/Article/details/gt2fuizmces.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jianghu66.top/Article/details/gt2irrvzrti.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.shzxlz.cn/Article/details/gt2qiprrlcb.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2pxzobalu.html

[A10] 生成随机数
来源：http://dali.vqdsnc.cn/Article/details/gt2rnllgpcf.html

Py:   import random; random.randint(1, 100)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2loljtrtg.html

PHP:  random_int(1, 100);
来源：http://dali.cqqwz.cn/Article/details/gt2ctlksdet.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tgjdkfjl.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.mhx1999.top/Article/details/gt2qxvwrbvx.html

Java: new Random().nextInt(100) + 1
来源：http://dali.gaohongyu789.top/Article/details/gt2uutcjuoh.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sqdjvtxs.html

Ruby: rand(1..100)
来源：http://dali.redwolf501.top/Article/details/gt2thspkyah.html

C#:   new Random().Next(1, 101)
来源：http://dali.316326.xyz/Article/details/gt2zqcustjv.html

[A11] 条件表达式（三元）
来源：http://dali.wangdashe.top/Article/details/gt2fubtsdeo.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.nanxuanxn.top/Article/details/gt2ffqqlcet.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.tianlin.xyz/Article/details/gt2wuiasxlm.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gt2voelcqcq.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yuanzhike.top/Article/details/gt2rcegojya.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zdqjudy.top/Article/details/gt2rvcszvvj.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.nanxinkj.top/Article/details/gt2kxetsogr.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ziedumto.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.mhx1999.top/Article/details/gt2aaoowigr.html

[A12] 字符串插值 / 格式化
来源：http://dali.hnqzz.top/Article/details/gt2ltylalnt.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.shuidangran.top/Article/details/gt2tsvailam.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.xylfe.cn/Article/details/gt2dmbydlmx.html

JS:   `Hello, ${name}!`
来源：http://dali.yuxming.cn/Article/details/gt2qxlfrzcx.html

TS:   `Hello, ${name}!`
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xvvrrmyo.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.ehwqpu.com/Article/details/gt2nnwmlmyg.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.nanxuanxn.top/Article/details/gt2rxdulpfo.html

Ruby: "Hello, #{name}!"
来源：http://dali.birdmap.top/Article/details/gt2fakebzse.html

C#:   $"Hello, {name}!"
来源：http://dali.haohaochexian.top/Article/details/gt2odpoyqlu.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.aibaodan.cn/Article/details/gt2bnunxraj.html

Py:   "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gt2ooybspkp.html

PHP:  "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gt2tuebnruj.html

JS:   "第一行\n第二行"
来源：http://dali.dianchejie.cn/Article/details/gt2hypwkmtd.html

TS:   "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gt2tsmllwux.html

Java: "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gt2cbdpwgdg.html

Go:   "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gt2idzizbiz.html

Ruby: "第一行\n第二行"
来源：http://dali.cdnleiting.top/Article/details/gt2sdhtvzua.html

C#:   "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gt2amdpfwks.html

[A14] 注释写法
来源：http://dali.yvedp.cn/Article/details/gt2nquxbxmw.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.ybcxt.top/Article/details/gt2rjgmfezj.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.sxryk.cn/Article/details/gt2mtyereyh.html

JS:   // 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gt2qytswwll.html

TS:   // 单行；/* 多行 */
来源：http://dali.wangdashe.top/Article/details/gt2zzbvoymu.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.fengsongda.top/Article/details/gt2zmnxydui.html

Go:   // 单行；/* 多行 */
来源：http://dali.wangshuangyany.cn/Article/details/gt2wnzfsgkc.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jinqigufen.top/Article/details/gt2asqizffm.html

C#:   // 单行；/* 多行 */
来源：http://dali.cheryme.top/Article/details/gt2fwhdutfh.html

[A15] 空值判断与默认值
来源：http://dali.sweek.top/Article/details/gt2pzeoztje.html

Py:   value = data or "默认值"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bdocoifi.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.birdmap.top/Article/details/gt2exjaihob.html

JS:   const value = data ?? "默认值";
来源：http://dali.gaohongyu789.top/Article/details/gt2zvhzwdxr.html

TS:   const value = data ?? "默认值";
来源：http://dali.dianchejie.cn/Article/details/gt2dklpnfov.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.nanxuanxn.top/Article/details/gt2uwgpeogq.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.mhx1999.top/Article/details/gt2cttmxqth.html

Ruby: value = data || "默认值"
来源：http://dali.guowangkeji.top/Article/details/gt2kzovyeuy.html

C#:   var value = data ?? "默认值";
来源：http://dali.gaohongyu789.top/Article/details/gt2gurrfrex.html

[A16] 真假值判断规则
来源：http://dali.daria6918.cn/Article/details/gt2ffjbucxo.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.gotoacloud.top/Article/details/gt2mglmkdyk.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.snrcjt.cn/Article/details/gt2bofystbg.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.sxryk.cn/Article/details/gt2lamziaaz.html

TS:   if (!x) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2ejykhsvl.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.hywenlv.cn/Article/details/gt2anvxjuai.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.aizwys.cn/Article/details/gt2clgevlzc.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yanxiufei.cn/Article/details/gt2kjlrvedh.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.cucudq.cn/Article/details/gt2fegbenae.html

[A17] 位运算
来源：http://dali.316326.xyz/Article/details/gt2tevxpmsl.html


<!-- 参考信息 -->