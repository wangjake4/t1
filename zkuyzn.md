代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.jyoumei.cn/Article/details/gtjdyyeuis.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.aizwys.cn/Article/details/gtjbjzxyoh.html

[U92] JS：深拷贝
来源：http://dali.ydzc1.top/Article/details/gtetzgkyyc.html

structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gtabxtfjrf.html

[U93] JS：模板字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtkpvwzqjj.html

`共 ${n} 条`
来源：http://dali.zhiwuduotai.top/Article/details/gtqjrrawgk.html

[U94] JS：箭头函数
来源：http://dali.jqgfzy.top/Article/details/gtlhbhhgul.html

const double = x => x * 2;
来源：http://dali.hysaishi.cn/Article/details/gtugwbbazf.html

[U95] JS：Promise 包装
来源：http://dali.yuxming.cn/Article/details/gtgyigppwd.html

new Promise((resolve, reject) => {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdoisypm.html

[U96] JS：async/await 与异常
来源：http://dali.chenlongwang.top/Article/details/gtkmjvwkmh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtotosjrra.html

[U97] JS：并发请求
来源：http://dali.gzhubu.top/Article/details/gtqxvyxhjn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gtgdztznit.html

[U98] JS：fetch 带 JSON
来源：http://dali.ehwqpu.com/Article/details/gtgslnhpzd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.havefunace.top/Article/details/gtbbrzmmbb.html

[U99] JS：事件监听
来源：http://dali.fzhhl.top/Article/details/gtsntncsbr.html

el.addEventListener("click", e => {})
来源：http://dali.gzhubu.top/Article/details/gtdadkieyi.html

[U100] JS：DOM 查询
来源：http://dali.pycfn.com/Article/details/gtotpzieko.html

document.querySelector(".item")
来源：http://dali.shuidangran.top/Article/details/gthvlygozz.html

[U101] JS：classList 操作
来源：http://dali.yonumen.top/Article/details/gtijnqbjol.html

el.classList.toggle("active")
来源：http://dali.redwolf501.top/Article/details/gtetarqsit.html

[U102] JS：本地存储
来源：http://dali.gzhubu.top/Article/details/gtwgjdkymp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zycfv.cn/Article/details/gtbncewndu.html

[U103] JS：定时器
来源：http://dali.havefunace.top/Article/details/gtwosdenoz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hysaishi.cn/Article/details/gtudkiaxhb.html

[U104] JS：防抖
来源：http://dali.9152youxi.cn/Article/details/gtcrkvpqxl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtbingadrj.html

[U105] JS：节流
来源：http://dali.jianghu66.top/Article/details/gtiqmxdgqm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.nwbrower.top/Article/details/gtjmgogibg.html

[U106] JS：日期格式化
来源：http://dali.hfpthk.cn/Article/details/gtdhfcmudu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.sysykeji.top/Article/details/gtzufqzsss.html

[U107] JS：数字千分位
来源：http://dali.chenjidiqi.icu/Article/details/gtklsmmeou.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.iojbl.cn/Article/details/gtzzlqtpne.html

[U108] JS：随机整数
来源：http://dali.gogol.net.cn/Article/details/gtvrwztnjb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ydzc1.top/Article/details/gtavknaeyw.html

[U109] JS：数组分组
来源：http://dali.guannengcc.top/Article/details/gtnkopwblo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sysykeji.top/Article/details/gtitbfisdo.html

[U110] JS：数组分块
来源：http://dali.pycfn.com/Article/details/gtagtwfpec.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cdnleiting.top/Article/details/gtvhcezibc.html

[U111] JS：对象转 Map
来源：http://dali.jqgfzy.top/Article/details/gtwijxnoat.html

new Map(Object.entries(obj))
来源：http://dali.yueranfly.top/Article/details/gtoekejxxc.html

[U112] JS：字符串补位
来源：http://dali.sysykeji.top/Article/details/gtxnoocrkn.html

"7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gtmofnvxto.html

[U113] JS：正则替换全部
来源：http://dali.fengsongda.top/Article/details/gtvrtmxewf.html

s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gttbcbuxnw.html

[U114] JS：JSON 深比较
来源：http://dali.hammf.cn/Article/details/gtpgbqvnul.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yvedp.cn/Article/details/gtdyrisfzu.html

[U115] JS：生成 UUID
来源：http://dali.jyoumei.cn/Article/details/gtscqfxsko.html

crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gtzdkdzaqn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jianghu66.top/Article/details/gtmrfwgqfl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhixingplan.top/Article/details/gtsfywdaes.html

[U117] JS：单元测试
来源：http://dali.svipenyu.cn/Article/details/gtcdmotlca.html

npm i -D vitest;  npx vitest
来源：http://dali.birdmap.top/Article/details/gtxqgzigxw.html

[U118] JS：开发服务器
来源：http://dali.yongpay.top/Article/details/gtnvlcsrho.html

npm i -D vite;  npx vite
来源：http://dali.kuanghao11.cn/Article/details/gtaqydnymy.html

[U119] JS：生产构建
来源：http://dali.yj20258.top/Article/details/gtzvnesgpd.html

npx vite build
来源：http://dali.zhongyouzk.top/Article/details/gtzrvcyopm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.sweek.top/Article/details/gtbufkniof.html

import.meta.env.VITE_API_URL
来源：http://dali.mhx1999.top/Article/details/gtkydauvje.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtshaeaddj.html

统计汇总
来源：http://dali.yvedp.cn/Article/details/gtyztihasv.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtwkzkocvr.html

按语言统计（条）：
来源：http://dali.zhongyouzk.top/Article/details/gtdzhxgrae.html

Python ......... 252
来源：http://dali.yj202588.top/Article/details/gtedjbsnbz.html

PHP ............ 252
来源：http://dali.tianlin.xyz/Article/details/gtadbawubu.html

JavaScript ..... 252
来源：http://dali.andypj.xyz/Article/details/gtrywvywru.html

TypeScript ..... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtajihjbyf.html

Java ........... 212
来源：http://dali.shangyingyoupin.top/Article/details/gtghemjbsh.html

Go ............. 212
来源：http://dali.aibaodan.cn/Article/details/gtnakbhtzu.html

Ruby ........... 212
来源：http://dali.ppjwa.cn/Article/details/gtjzaofanc.html

C# ............. 212
来源：http://dali.zhixingplan.top/Article/details/gtjizdgyje.html

C .............. 30
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhedunho.html

C++ ............ 30
来源：http://dali.zhoulong.xyz/Article/details/gteprzjfas.html

SQL ............ 90
来源：http://dali.dianchejie.cn/Article/details/gtozljvipg.html

Bash ........... 80
来源：http://dali.xylfe.cn/Article/details/gtbziyaejp.html

Kotlin ......... 15
来源：http://dali.smart0.xyz/Article/details/gtellwfknb.html

Swift .......... 15
来源：http://dali.aizwys.cn/Article/details/gtvzmbeogf.html

Lua ............ 10
来源：http://dali.fengsongda.top/Article/details/gtebqjbzav.html

Perl ........... 10
来源：http://dali.birdmap.top/Article/details/gtfzgtzucn.html

Scala .......... 10
来源：http://dali.ppjwa.cn/Article/details/gtzlchxpix.html

------------------------------------
来源：http://dali.gzhubu.top/Article/details/gtvnvqqbyc.html

合计 ........... 2106 条
来源：http://dali.0kj1m.cn/Article/details/gtfyiexjor.html

按章节统计：
来源：http://dali.quarkkingdee.top/Article/details/gtflfalusf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkonwufp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.smart0.xyz/Article/details/gtmkidkchv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zdqjudy.top/Article/details/gtknwskfil.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.daria6918.cn/Article/details/gtrufdtjem.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yanxiufei.cn/Article/details/gtalwwueiv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jinqigufen.top/Article/details/gtiiszolpv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.chenzaomai.com/Article/details/gtexbsetzf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jinghuilouyu.cn/Article/details/gthsbxodgr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gtfzhoqaig.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jlsjyb.cn/Article/details/gtfapqfyuv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxlijknb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gtfginhtmb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gttotgvwgt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yongpay.top/Article/details/gtbpolxesp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.guannengcc.top/Article/details/gtmcthmzgg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gtjckfqcya.html

Q SQL 专题                              90
来源：http://dali.daria6918.cn/Article/details/gttfyqvtiq.html

R Bash 专题                             80
来源：http://dali.smart0.xyz/Article/details/gtttyixmvv.html

S C / C++ 专题                          60
来源：http://dali.yongpay.top/Article/details/gtyxsnuxsx.html

T 其他语言补充                          60
来源：http://dali.xuetiantiany.cn/Article/details/gtenrudiuv.html

U 高频实用片段                         120
来源：http://dali.tanke756.top/Article/details/gtcbjqrinl.html

------------------------------------
来源：http://dali.xziqi.cn/Article/details/gtocpzhoti.html

合计                                  2106 条
来源：http://dali.kuanghao11.cn/Article/details/gtqipdmziu.html

--------------------------------------------------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gtoqfrxxex.html

使用提醒
来源：http://dali.sufxvd.cn/Article/details/gtdodbqcgn.html

--------------------------------------------------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gtblvajkpd.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.daria6918.cn/Article/details/gtdpocsenb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xylfe.cn/Article/details/gtfrccewgq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jyoumei.cn/Article/details/gtgipeoyrb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.wangdashe.top/Article/details/gtsrhonjlr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.iojbl.cn/Article/details/gthttuqrdy.html

—— 文件结束 ——
来源：http://dali.bjfxy.top/Article/details/gtwpcvfyyo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gthizmnkml.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgphcsse.html

Common Programming Examples Cheat Book
来源：http://dali.yj20258888.top/Article/details/gtbbmvpute.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtliqlybvx.html

【收录内容】
来源：http://dali.jlsjyb.cn/Article/details/gtvbovmhwx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ydzc1.top/Article/details/gtmjxwfwat.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yonumen.top/Article/details/gtfmnsycrb.html

SQL · Bash · C · C++
来源：http://dali.havefunace.top/Article/details/gtleznherj.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hnxiangtu.top/Article/details/gtyxckxkdw.html

【使用说明】
来源：http://dali.mhx1999.top/Article/details/gtrulbgqcx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.iojbl.cn/Article/details/gtdejjzhsl.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.c1oappe.top/Article/details/gtrtkavgwk.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.andypj.xyz/Article/details/gtjyrxmynh.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.chenzaomai.com/Article/details/gtiwlkwafg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yj20258888.top/Article/details/gtpbcuthff.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.gogol.net.cn/Article/details/gtuctlhipj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.fengsongda.top/Article/details/gtnqetryhl.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yongpay.top/Article/details/gtrtzxwbvh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.guowangkeji.top/Article/details/gtdjemixxt.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhixingplan.top/Article/details/gtmecrebqv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jinqigufen.top/Article/details/gtigjpinak.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.meibo888.top/Article/details/gtxphrcrkq.html

【文件统计】
来源：http://dali.ywan-chungtsiang.top/Article/details/gtanhjypac.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.bjfxy.top/Article/details/gtzkriedwz.html

--------------------------------------------------------------------------------
来源：http://dali.mhx1999.top/Article/details/gtamuobcbt.html

目  录
来源：http://dali.cucudq.cn/Article/details/gthenbenxv.html

--------------------------------------------------------------------------------
来源：http://dali.xylfe.cn/Article/details/gtqwqzixut.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhengqikj.top/Article/details/gtwnovoeqv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hfpthk.cn/Article/details/gtsvagndau.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.aizwys.cn/Article/details/gtpwnclglo.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.tanke756.top/Article/details/gtlwsioyjr.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.chenzaomai.com/Article/details/gtsubsxqfk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hywenlv.cn/Article/details/gtwzxfagsk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yuanzhike.top/Article/details/gtdjwchwri.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.gotoacloud.top/Article/details/gtvvylfgsz.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhixingplan.top/Article/details/gtnjwetadg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yj202588.top/Article/details/gtwhswrkiz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hywenlv.cn/Article/details/gttzxaxkmj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.feifeiyinyue.top/Article/details/gttqlpxaqo.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gtjqnhvtfa.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.guowangkeji.top/Article/details/gtjwzvvzjx.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hywenlv.cn/Article/details/gtgrqlftvf.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gtvaoahmki.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhengqikj.top/Article/details/gtgomvwdsk.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jqgfzy.top/Article/details/gtqrrdozjv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.aizwys.cn/Article/details/gtsvchjxux.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhengqikj.top/Article/details/gtjpxwoeaw.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.c1oappe.top/Article/details/gtulutizdn.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtljmvtcvv.html

A. 基础语法与类型
来源：http://dali.xuetiantiany.cn/Article/details/gthnviayth.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtinlyuahd.html

[A01] Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhqepqph.html

Py:   print("Hello, World!")
来源：http://dali.aibaodan.cn/Article/details/gtsfcmodzw.html

PHP:  echo "Hello, World!";
来源：http://dali.ppjwa.cn/Article/details/gtxdkhkewo.html

JS:   console.log("Hello, World!");
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqcxyabs.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hysaishi.cn/Article/details/gtcgifptsn.html

Java: System.out.println("Hello, World!");
来源：http://dali.feifeiyinyue.top/Article/details/gtgbeoijap.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.iojbl.cn/Article/details/gtvbudxlup.html

Ruby: puts "Hello, World!"
来源：http://dali.dashuyun.cn/Article/details/gtupmacopg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.fengsongda.top/Article/details/gttauhkmkm.html

[A02] 变量声明与赋值
来源：http://dali.birdmap.top/Article/details/gtffevdvve.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.c1oappe.top/Article/details/gtzlkdztdt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.svipenyu.cn/Article/details/gtabjtjobl.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.guannengcc.top/Article/details/gtbvlbcamk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.meibo888.top/Article/details/gtunmsbuup.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmwwoeho.html

Go:   name := "Alex"; age := 20
来源：http://dali.haohaochexian.top/Article/details/gtcuefkdlk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jlsjyb.cn/Article/details/gtwmafajqe.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgngiluzv.html

[A03] 常量定义
来源：http://dali.meibo888.top/Article/details/gtrpxocjwi.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ehwqpu.com/Article/details/gtduhujfby.html

PHP:  const PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtnspiqxap.html

JS:   const PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtaamjjvlu.html

TS:   const PI: number = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtblifcgcx.html

Java: static final double PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gtydvhhtol.html

Go:   const PI = 3.14159
来源：http://dali.feifeiyinyue.top/Article/details/gtmsazvtzy.html

Ruby: PI = 3.14159
来源：http://dali.havefunace.top/Article/details/gttogvgzij.html

C#:   const double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtprjchrdt.html

[A04] 判断变量类型
来源：http://dali.tanke756.top/Article/details/gthzotqsfz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhengqikj.top/Article/details/gthlfkjedi.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.nwbrower.top/Article/details/gtkpevompf.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.tanke756.top/Article/details/gtfguwiong.html

TS:   typeof x; x instanceof Date
来源：http://dali.sxryk.cn/Article/details/gtliluufjj.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.9152youxi.cn/Article/details/gtxnghqcui.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.feifeiyinyue.top/Article/details/gtqyknkobo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjboysvsg.html

C#:   x.GetType().Name; x is int
来源：http://dali.xziqi.cn/Article/details/gteclsiepv.html

[A05] 整数除法与取模
来源：http://dali.cashguo.top/Article/details/gtacpsnzdu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yonumen.top/Article/details/gtutdzdepd.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.gzhubu.top/Article/details/gtsxrsctgj.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aizwys.cn/Article/details/gtmprhgofk.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gtcyezkmya.html

Java: 7 / 2; 7 % 2
来源：http://dali.nanxuanxn.top/Article/details/gtmrcgdgri.html

Go:   7 / 2; 7 % 2
来源：http://dali.guannengcc.top/Article/details/gturhsxrsq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yonumen.top/Article/details/gtgmavhmel.html

C#:   7 / 2; 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyagzwpwp.html

[A06] 字符串转数字
来源：http://dali.iojbl.cn/Article/details/gtwmditqqm.html

Py:   int("42"); float("3.14")
来源：http://dali.jianghu66.top/Article/details/gtokpbuqcr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujvkpbzp.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.gzhubu.top/Article/details/gtnnznycfq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.aibaodan.cn/Article/details/gtdcjftctr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jyoumei.cn/Article/details/gtgbskxagq.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijklnemp.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jinqigfzy.top/Article/details/gtymimntmi.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yj20258.top/Article/details/gtyolkecgm.html

[A07] 数字转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodszvmwk.html

Py:   str(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbwwevwa.html

PHP:  (string) 42; strval(42)
来源：http://dali.xuanzx.com/Article/details/gtscjmigxl.html

JS:   String(42); (42).toString()
来源：http://dali.guowangkeji.top/Article/details/gtyjuafdjs.html

TS:   String(42)
来源：http://dali.hysaishi.cn/Article/details/gtwbhavvyl.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yuanzhike.top/Article/details/gtsfjijebl.html

Go:   strconv.Itoa(42)
来源：http://dali.jiagoushi.top/Article/details/gtjejfobte.html

Ruby: 42.to_s
来源：http://dali.ehwqpu.com/Article/details/gtoecollng.html

C#:   42.ToString()
来源：http://dali.316326.xyz/Article/details/gtqgebprrg.html

[A08] 取整与四舍五入
来源：http://dali.quarkkingdee.top/Article/details/gtcodqlkvd.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.guowangkeji.top/Article/details/gtianiawcq.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yonumen.top/Article/details/gtqutodihv.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.dashuyun.cn/Article/details/gtrzrvuhos.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.chenzaomai.com/Article/details/gtyfrbrhxe.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.guannengcc.top/Article/details/gtyrwimair.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.gogol.net.cn/Article/details/gthvbvscoz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yuxming.cn/Article/details/gtkpsjknaq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gtcdgedevi.html

[A09] 绝对值与最大最小值
来源：http://dali.iojbl.cn/Article/details/gtxyngmmtp.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zycfv.cn/Article/details/gtysutyyyq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtgfoyzwgz.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtooprfwyn.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfbixusc.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.mhx1999.top/Article/details/gttqtnmvtz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hywenlv.cn/Article/details/gtihuijogj.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jinqigfzy.top/Article/details/gtlupaxfjy.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yongpay.top/Article/details/gthfgmknqv.html

[A10] 生成随机数
来源：http://dali.yuxming.cn/Article/details/gtodorvdps.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zdqjudy.top/Article/details/gtxelhzttw.html

PHP:  random_int(1, 100);
来源：http://dali.snrcjt.cn/Article/details/gtraweiufd.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.wangdashe.top/Article/details/gtwjypkmfb.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hysaishi.cn/Article/details/gtgbhzfdrf.html

Java: new Random().nextInt(100) + 1
来源：http://dali.fengsongda.top/Article/details/gtimgxmidi.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.haohaochexian.top/Article/details/gtputqdcwx.html

Ruby: rand(1..100)
来源：http://dali.nwbrower.top/Article/details/gtzfderkep.html

C#:   new Random().Next(1, 101)
来源：http://dali.wangshuangyany.cn/Article/details/gtmrjeiscx.html

[A11] 条件表达式（三元）
来源：http://dali.haohaochexian.top/Article/details/gtgjbtuntg.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.nanxuanxn.top/Article/details/gtnliqdrko.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhixingplan.top/Article/details/gtlgtbnade.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.mhx1999.top/Article/details/gttrloclrk.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.ydzc1.top/Article/details/gtxlzncdhe.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.pycfn.com/Article/details/gtuybacdxk.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.dianchejie.cn/Article/details/gtkvjkznwv.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.birdmap.top/Article/details/gtcpqnhqpn.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.havefunace.top/Article/details/gtsizrbeuf.html

[A12] 字符串插值 / 格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvuokwxlx.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.wangdashe.top/Article/details/gtzlfsxhif.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjmibunb.html

JS:   `Hello, ${name}!`
来源：http://dali.cashguo.top/Article/details/gtfguaemkf.html

TS:   `Hello, ${name}!`
来源：http://dali.shangyingyoupin.top/Article/details/gtkwhuoans.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xziqi.cn/Article/details/gtbubrujhk.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yongpay.top/Article/details/gtanobxszz.html

Ruby: "Hello, #{name}!"
来源：http://dali.kuanghao11.cn/Article/details/gtpwnosski.html

C#:   $"Hello, {name}!"
来源：http://dali.ybcxt.top/Article/details/gtkmwpslyt.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.ehwqpu.com/Article/details/gtktiknwzt.html

Py:   "第一行\n第二行"
来源：http://dali.ppjwa.cn/Article/details/gtadgdhfzk.html

PHP:  "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gtwiwjtmsf.html

JS:   "第一行\n第二行"
来源：http://dali.cashguo.top/Article/details/gtqixvknzg.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gtgievdavv.html

Java: "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gtnwkulyck.html

Go:   "第一行\n第二行"
来源：http://dali.chenjidiqi.icu/Article/details/gtjfoxzxml.html

Ruby: "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gtcpmjiudu.html

C#:   "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gtyirkopce.html

[A14] 注释写法
来源：http://dali.feifeiyinyue.top/Article/details/gtpjwutbzf.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.snrcjt.cn/Article/details/gtcljdipqk.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.aizwys.cn/Article/details/gtzmwhprns.html

JS:   // 单行；/* 多行 */
来源：http://dali.xziqi.cn/Article/details/gtpkmvjqde.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhiwuduotai.top/Article/details/gtcfwfhyxa.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.redwolf501.top/Article/details/gtjdhhdedj.html

Go:   // 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gtncfiyvgr.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.bjfxy.top/Article/details/gtjprhgbys.html

C#:   // 单行；/* 多行 */
来源：http://dali.dashuyun.cn/Article/details/gtmgttndrp.html

[A15] 空值判断与默认值
来源：http://dali.daxiang520.top/Article/details/gtmhiqpmvm.html

Py:   value = data or "默认值"
来源：http://dali.xuanzx.com/Article/details/gtliiijhiu.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.bjfxy.top/Article/details/gtmnyibczw.html

JS:   const value = data ?? "默认值";
来源：http://dali.sweek.top/Article/details/gtbchxlqhs.html

TS:   const value = data ?? "默认值";
来源：http://dali.jqgufenzy.top/Article/details/gtkyijqxkv.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.feifeiyinyue.top/Article/details/gtwtlfkigz.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.iojbl.cn/Article/details/gthbooormb.html


<!-- 参考信息 -->