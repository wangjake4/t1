代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.nanxuanxn.top/Article/details/gttwxhiqhs.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.aizwys.cn/Article/details/gtwtalwkjb.html

[U92] JS：深拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunjvmexh.html

structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gttwjdevdb.html

[U93] JS：模板字符串
来源：http://dali.gaohongyu789.top/Article/details/gttvhfvcvs.html

`共 ${n} 条`
来源：http://dali.cucudq.cn/Article/details/gtgruqnppa.html

[U94] JS：箭头函数
来源：http://dali.aibaodan.cn/Article/details/gtzslejsru.html

const double = x => x * 2;
来源：http://dali.jyoumei.cn/Article/details/gtpbwzdese.html

[U95] JS：Promise 包装
来源：http://dali.jqgufenzy.top/Article/details/gtpzkbkpzz.html

new Promise((resolve, reject) => {})
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcryalrs.html

[U96] JS：async/await 与异常
来源：http://dali.fzhhl.top/Article/details/gtsakvedpk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtibxfhnoo.html

[U97] JS：并发请求
来源：http://dali.aizwys.cn/Article/details/gtqertfttg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtvnowqhjp.html

[U98] JS：fetch 带 JSON
来源：http://dali.xziqi.cn/Article/details/gtxaqwqrhl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cqqwz.cn/Article/details/gtqxgflquj.html

[U99] JS：事件监听
来源：http://dali.gogol.net.cn/Article/details/gtpwezdlnm.html

el.addEventListener("click", e => {})
来源：http://dali.chenlongwang.top/Article/details/gtlhxaceig.html

[U100] JS：DOM 查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtacjlaowa.html

document.querySelector(".item")
来源：http://dali.wangshuangyany.cn/Article/details/gtodkdmlfo.html

[U101] JS：classList 操作
来源：http://dali.xuanzx.com/Article/details/gtjnvbukro.html

el.classList.toggle("active")
来源：http://dali.jqgufenzy.top/Article/details/gtaqkyenra.html

[U102] JS：本地存储
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjctdijj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.chenzaomai.com/Article/details/gtcuzxyvll.html

[U103] JS：定时器
来源：http://dali.haohaochexian.top/Article/details/gtevtofauf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.316326.xyz/Article/details/gtsnfvncpv.html

[U104] JS：防抖
来源：http://dali.ppjwa.cn/Article/details/gtyyzqqfmk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzkxcxkc.html

[U105] JS：节流
来源：http://dali.cdnleiting.top/Article/details/gtvdojpody.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shuidangran.top/Article/details/gthoxmefna.html

[U106] JS：日期格式化
来源：http://dali.guowangkeji.top/Article/details/gtigeqzbee.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.quarkkingdee.top/Article/details/gtiasrhjap.html

[U107] JS：数字千分位
来源：http://dali.sweek.top/Article/details/gtfcukibhp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzycurqki.html

[U108] JS：随机整数
来源：http://dali.iojbl.cn/Article/details/gtubtzuzkg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhxfchkj.html

[U109] JS：数组分组
来源：http://dali.jinqigfzy.top/Article/details/gtvucbfkoz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cdnleiting.top/Article/details/gtsjntuevp.html

[U110] JS：数组分块
来源：http://dali.yanxiufei.cn/Article/details/gtsugmzyvl.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.iojbl.cn/Article/details/gtdurpqtza.html

[U111] JS：对象转 Map
来源：http://dali.bjfxy.top/Article/details/gtlqzmicbv.html

new Map(Object.entries(obj))
来源：http://dali.zhiwuduotai.top/Article/details/gtjdfrcaqy.html

[U112] JS：字符串补位
来源：http://dali.cdnleiting.top/Article/details/gtpvormuhs.html

"7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtbmntvjoj.html

[U113] JS：正则替换全部
来源：http://dali.yanxiufei.cn/Article/details/gteocegasg.html

s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtjwzijeev.html

[U114] JS：JSON 深比较
来源：http://dali.nanxuanxn.top/Article/details/gtkkpwqpnw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tian-w.cn/Article/details/gtxrfwdaai.html

[U115] JS：生成 UUID
来源：http://dali.jiagoushi.top/Article/details/gtwtyvupml.html

crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gtsbytvuwg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yvedp.cn/Article/details/gtnbvpyfyq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cucudq.cn/Article/details/gtzvbyypgo.html

[U117] JS：单元测试
来源：http://dali.gzhubu.top/Article/details/gtmrodrogk.html

npm i -D vitest;  npx vitest
来源：http://dali.birdmap.top/Article/details/gtvoxpbgap.html

[U118] JS：开发服务器
来源：http://dali.dianchejie.cn/Article/details/gtvdpsaetx.html

npm i -D vite;  npx vite
来源：http://dali.gogol.net.cn/Article/details/gtdkagasgq.html

[U119] JS：生产构建
来源：http://dali.zhoulong.xyz/Article/details/gtjhzcskmy.html

npx vite build
来源：http://dali.dianchejie.cn/Article/details/gtmfjpmgwz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhengqikj.top/Article/details/gtnivzgzkd.html

import.meta.env.VITE_API_URL
来源：http://dali.gotoacloud.top/Article/details/gtlwvtqitr.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtrvjgdwjv.html

统计汇总
来源：http://dali.jlsjyb.cn/Article/details/gtsueszyky.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtvhhsfutl.html

按语言统计（条）：
来源：http://dali.meibo888.top/Article/details/gtmliqmree.html

Python ......... 252
来源：http://dali.jqgufenzy.top/Article/details/gtdrrfpgct.html

PHP ............ 252
来源：http://dali.yj202588.top/Article/details/gtbhnorjci.html

JavaScript ..... 252
来源：http://dali.haohaochexian.top/Article/details/gtujyyeevi.html

TypeScript ..... 212
来源：http://dali.zhiwuduotai.top/Article/details/gtjobdrpak.html

Java ........... 212
来源：http://dali.guowangkeji.top/Article/details/gtqrrqowhd.html

Go ............. 212
来源：http://dali.guowangkeji.top/Article/details/gtkuyqnzzp.html

Ruby ........... 212
来源：http://dali.yuanzhike.top/Article/details/gtygkjajhx.html

C# ............. 212
来源：http://dali.zhengqikj.top/Article/details/gtqokqygvd.html

C .............. 30
来源：http://dali.sysykeji.top/Article/details/gthydbawtz.html

C++ ............ 30
来源：http://dali.quarkkingdee.top/Article/details/gtqcwxizyo.html

SQL ............ 90
来源：http://dali.chenlongwang.top/Article/details/gtqakfxlct.html

Bash ........... 80
来源：http://dali.xuetiantiany.cn/Article/details/gtiawhnaqq.html

Kotlin ......... 15
来源：http://dali.gaohongyu789.top/Article/details/gthuerjbdc.html

Swift .......... 15
来源：http://dali.0kj1m.cn/Article/details/gtsxgwgjhq.html

Lua ............ 10
来源：http://dali.tianlin.xyz/Article/details/gtqetjgfwa.html

Perl ........... 10
来源：http://dali.shzxlz.cn/Article/details/gtmptmjufp.html

Scala .......... 10
来源：http://dali.yj20258.top/Article/details/gtgnejcdzw.html

------------------------------------
来源：http://dali.pycfn.com/Article/details/gtkhomnfep.html

合计 ........... 2106 条
来源：http://dali.daria6918.cn/Article/details/gtnelncsmf.html

按章节统计：
来源：http://dali.sufxvd.cn/Article/details/gtpnjwlnyo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.bjfxy.top/Article/details/gtrgkerxbm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhengqikj.top/Article/details/gtprokbzvf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xuetiantiany.cn/Article/details/gtphoanrvj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.tian-w.cn/Article/details/gtewyijvyz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhengqikj.top/Article/details/gtrzhlukww.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jinghuilouyu.cn/Article/details/gtspneglas.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.0kj1m.cn/Article/details/gtvjqvefst.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.tanke756.top/Article/details/gtmgpnxknl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gteswqhugp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.tianlin.xyz/Article/details/gtmxuyvhqb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhoqxpcu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gtaspuaqtg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gtolllxrnx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.gaohongyu789.top/Article/details/gtljrfxvcm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cucudq.cn/Article/details/gtqdficgab.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gtpbawblgh.html

Q SQL 专题                              90
来源：http://dali.cheryme.top/Article/details/gtpwakcfia.html

R Bash 专题                             80
来源：http://dali.hnxiangtu.top/Article/details/gtcexdstia.html

S C / C++ 专题                          60
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnuavvlkh.html

T 其他语言补充                          60
来源：http://dali.hysaishi.cn/Article/details/gtoetfmmst.html

U 高频实用片段                         120
来源：http://dali.jinqigfzy.top/Article/details/gtrglapvwu.html

------------------------------------
来源：http://dali.quarkkingdee.top/Article/details/gtyyuqqvpa.html

合计                                  2106 条
来源：http://dali.zhengqikj.top/Article/details/gtvkrqnvvh.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gtmegjogkm.html

使用提醒
来源：http://dali.hnqzz.top/Article/details/gtipapwbhi.html

--------------------------------------------------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gtblrnediv.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yangfankeji.com/Article/details/gtgracapki.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.shuidangran.top/Article/details/gtyprelmvm.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gtwygzaczw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.9152youxi.cn/Article/details/gtrffbsceb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.aizwys.cn/Article/details/gtarcobqll.html

—— 文件结束 ——
来源：http://dali.xuanzx.com/Article/details/gtlgrrewva.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtttipcxnj.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.c1oappe.top/Article/details/gtllfrntto.html

Common Programming Examples Cheat Book
来源：http://dali.jinqigfzy.top/Article/details/gtbjwmscfo.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtwyfpgufz.html

【收录内容】
来源：http://dali.snrcjt.cn/Article/details/gtzuljosgi.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yonumen.top/Article/details/gtipebavcv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cdnleiting.top/Article/details/gtzgowimws.html

SQL · Bash · C · C++
来源：http://dali.snrcjt.cn/Article/details/gtuljwbord.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.wangdashe.top/Article/details/gtimabtvkd.html

【使用说明】
来源：http://dali.shangyingyoupin.top/Article/details/gttuggqpff.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.guannengcc.top/Article/details/gtkeqfxhul.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.guowangkeji.top/Article/details/gtyjwfpyeg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.cqqwz.cn/Article/details/gtmwbttjgh.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hywenlv.cn/Article/details/gtlrmokzrw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yuxming.cn/Article/details/gtqwaicaic.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.snrcjt.cn/Article/details/gtsfvldnsh.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hammf.cn/Article/details/gtlrvvylxd.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xinyue.icu/Article/details/gtnhaeufiq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.haohaochexian.top/Article/details/gttetkfpvd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.kuanghao11.cn/Article/details/gtywumxaxy.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hfpthk.cn/Article/details/gtuirfazxv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hongshengwenyu.top/Article/details/gtkwrbqvdn.html

【文件统计】
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlcuzpvn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jyoumei.cn/Article/details/gtgxlyoljb.html

--------------------------------------------------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gtmargsreq.html

目  录
来源：http://dali.hywenlv.cn/Article/details/gtscgtfgvr.html

--------------------------------------------------------------------------------
来源：http://dali.hammf.cn/Article/details/gtualwxijo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.sufxvd.cn/Article/details/gtowgspadi.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hfpthk.cn/Article/details/gtnjrjajaz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zdqjudy.top/Article/details/gtvahflclp.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.nanxuanxn.top/Article/details/gthfqjikju.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyrxdfjrt.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.gzhubu.top/Article/details/gtqicdnads.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtixldqohq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yonumen.top/Article/details/gtbpfwpmla.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gtmmdphxsl.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.snrcjt.cn/Article/details/gtcbxkfakj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gttfvoinwe.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gtujpfdtde.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gtzrhlxzic.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yonumen.top/Article/details/gtnbmbyruk.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hnxiangtu.top/Article/details/gtkjxxipoh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xylfe.cn/Article/details/gtssuqhleg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhoulong.xyz/Article/details/gtzvqnzgki.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnoewmafj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hnqzz.top/Article/details/gthhmrwowq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangdashe.top/Article/details/gtckuvmtat.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.c1oappe.top/Article/details/gtjzwqkisk.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtbwenwtuu.html

A. 基础语法与类型
来源：http://dali.zhixingplan.top/Article/details/gtipohszix.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtqigcckss.html

[A01] Hello World
来源：http://dali.mhx1999.top/Article/details/gtcwoqnnjl.html

Py:   print("Hello, World!")
来源：http://dali.jqgfzy.top/Article/details/gtsgannydv.html

PHP:  echo "Hello, World!";
来源：http://dali.sxryk.cn/Article/details/gtlsysjoan.html

JS:   console.log("Hello, World!");
来源：http://dali.vqdsnc.cn/Article/details/gtdpjvfvck.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zycfv.cn/Article/details/gtxzuilflq.html

Java: System.out.println("Hello, World!");
来源：http://dali.wangshuangyany.cn/Article/details/gtksyhdblw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yonumen.top/Article/details/gtlkamcyhf.html

Ruby: puts "Hello, World!"
来源：http://dali.jinqigufen.top/Article/details/gteelbonpu.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.tanke756.top/Article/details/gtllkrgknf.html

[A02] 变量声明与赋值
来源：http://dali.wangdashe.top/Article/details/gtpsvoiavu.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shuidangran.top/Article/details/gtzpthbsas.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.andypj.xyz/Article/details/gtblbkuvvv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.iojbl.cn/Article/details/gtekvnhuqv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jlsjyb.cn/Article/details/gtidvrfyzg.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zycfv.cn/Article/details/gtvbriumgh.html

Go:   name := "Alex"; age := 20
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvytpuroy.html

Ruby: name = "Alex"; age = 20
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvoxnzgcy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.nanxinkj.top/Article/details/gtrhihbgfi.html

[A03] 常量定义
来源：http://dali.yonumen.top/Article/details/gtnvqdjyan.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hnqzz.top/Article/details/gtylvkqrgl.html

PHP:  const PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gthqojwbny.html

JS:   const PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtqhlgwtgc.html

TS:   const PI: number = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtsfmpltxl.html

Java: static final double PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtuqmkuhds.html

Go:   const PI = 3.14159
来源：http://dali.snrcjt.cn/Article/details/gtfnuutpel.html

Ruby: PI = 3.14159
来源：http://dali.zdqjudy.top/Article/details/gtmbeynsjr.html

C#:   const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtjygqtikj.html

[A04] 判断变量类型
来源：http://dali.hongshengwenyu.top/Article/details/gtpptlvpjl.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ppjwa.cn/Article/details/gteagvtzfn.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhongyouzk.top/Article/details/gtpoxzzyew.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.smart0.xyz/Article/details/gtakrrdmhr.html

TS:   typeof x; x instanceof Date
来源：http://dali.gogol.net.cn/Article/details/gtemnnwwlx.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xuetiantiany.cn/Article/details/gtoztxlvau.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.dashuyun.cn/Article/details/gtqpfmyvdb.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsnlapad.html

C#:   x.GetType().Name; x is int
来源：http://dali.nwbrower.top/Article/details/gtnxrxafxn.html

[A05] 整数除法与取模
来源：http://dali.sysykeji.top/Article/details/gtvmoaekaw.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.gaohongyu789.top/Article/details/gtefcferkt.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gtrtucfdsp.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ydzc1.top/Article/details/gteageleuk.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.fzhhl.top/Article/details/gtvzobafio.html

Java: 7 / 2; 7 % 2
来源：http://dali.xinyue.icu/Article/details/gtvctzeakp.html

Go:   7 / 2; 7 % 2
来源：http://dali.sxryk.cn/Article/details/gtqwvkhbdb.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gtmpcxxcyy.html

C#:   7 / 2; 7 % 2
来源：http://dali.zycfv.cn/Article/details/gtrczrmuzh.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gtkrtpvvox.html

Py:   int("42"); float("3.14")
来源：http://dali.xuetiantiany.cn/Article/details/gtxqtfqqjg.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.aizwys.cn/Article/details/gtttlnrlmy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.sweek.top/Article/details/gtmrbfjmvj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yvedp.cn/Article/details/gtjtyhvvta.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.gotoacloud.top/Article/details/gtruptofez.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.cdnleiting.top/Article/details/gtnfzdatom.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.kuanghao11.cn/Article/details/gtvhqznjjx.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.cashguo.top/Article/details/gtrhbkfmol.html

[A07] 数字转字符串
来源：http://dali.hfpthk.cn/Article/details/gthbwlvpau.html

Py:   str(42)
来源：http://dali.hfpthk.cn/Article/details/gtcklrduui.html

PHP:  (string) 42; strval(42)
来源：http://dali.daxiang520.top/Article/details/gtoooeiamn.html

JS:   String(42); (42).toString()
来源：http://dali.svipenyu.cn/Article/details/gtzodhwmzz.html

TS:   String(42)
来源：http://dali.snrcjt.cn/Article/details/gtalfjuhaw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.mhx1999.top/Article/details/gtuykgroov.html

Go:   strconv.Itoa(42)
来源：http://dali.c1oappe.top/Article/details/gtpkcnlaza.html

Ruby: 42.to_s
来源：http://dali.haohaochexian.top/Article/details/gtuqxgdciv.html

C#:   42.ToString()
来源：http://dali.dianchejie.cn/Article/details/gtzezdwjqm.html

[A08] 取整与四舍五入
来源：http://dali.smart0.xyz/Article/details/gthuhgkykv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.gotoacloud.top/Article/details/gtdumrbkwq.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.daria6918.cn/Article/details/gtsjkmgzsh.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhongyouzk.top/Article/details/gthbjydolg.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.guannengcc.top/Article/details/gtsjzffwfl.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.gaohongyu789.top/Article/details/gtdzqusdum.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.xuetiantiany.cn/Article/details/gtpxollhre.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypfozsiv.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.chenlongwang.top/Article/details/gthetddvsd.html

[A09] 绝对值与最大最小值
来源：http://dali.feifeiyinyue.top/Article/details/gtjlngeyfg.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtijprsfun.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gthhovreac.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.daxiang520.top/Article/details/gtxhaibtgn.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtaxidsflb.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gtqdfdkkva.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jinqigufen.top/Article/details/gtahxrrxkl.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jlsjyb.cn/Article/details/gtwbtdgnox.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtrwaccjpz.html

[A10] 生成随机数
来源：http://dali.birdmap.top/Article/details/gtkkyhhzsr.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jqgufenzy.top/Article/details/gtildqiamn.html

PHP:  random_int(1, 100);
来源：http://dali.hfpthk.cn/Article/details/gtpwldifpp.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.svipenyu.cn/Article/details/gtttexupcs.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.havefunace.top/Article/details/gtnuieyvyp.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jqgfzy.top/Article/details/gtbfdhfssx.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.chenzaomai.com/Article/details/gtadounbzq.html

Ruby: rand(1..100)
来源：http://dali.nwbrower.top/Article/details/gtojrdeqgz.html

C#:   new Random().Next(1, 101)
来源：http://dali.yueranfly.top/Article/details/gtmepxqhrd.html

[A11] 条件表达式（三元）
来源：http://dali.yueranfly.top/Article/details/gtrftkrkiv.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdxmxydj.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hnxiangtu.top/Article/details/gtefhvpmap.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdcabchs.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gtzdzjxtqe.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jianghu66.top/Article/details/gtzpawrjjz.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yonumen.top/Article/details/gtwdtvxbdu.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.0kj1m.cn/Article/details/gtwdcasvpd.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.andypj.xyz/Article/details/gtpcahcgtq.html

[A12] 字符串插值 / 格式化
来源：http://dali.mhx1999.top/Article/details/gtzopaprhn.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.pengpengdd.cyou/Article/details/gtxhatpmqs.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.vqdsnc.cn/Article/details/gtpkucdakv.html

JS:   `Hello, ${name}!`
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitziznhm.html

TS:   `Hello, ${name}!`
来源：http://dali.xuanzx.com/Article/details/gtfothrder.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.andypj.xyz/Article/details/gtboaxsjyy.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.sufxvd.cn/Article/details/gtyzjrlimm.html

Ruby: "Hello, #{name}!"
来源：http://dali.gaohongyu789.top/Article/details/gtbsluviqd.html

C#:   $"Hello, {name}!"
来源：http://dali.hnqzz.top/Article/details/gtvjiggoak.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yj202588.top/Article/details/gtaglvozbp.html

Py:   "第一行\n第二行"
来源：http://dali.yj202588.top/Article/details/gtsvxmgrkz.html

PHP:  "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gtzfzrgogy.html

JS:   "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gtvwirffph.html

TS:   "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gtokccgaja.html

Java: "第一行\n第二行"
来源：http://dali.9152youxi.cn/Article/details/gthniqdszx.html

Go:   "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gtlgtkvqpg.html

Ruby: "第一行\n第二行"
来源：http://dali.mhx1999.top/Article/details/gtikvgasag.html

C#:   "第一行\n第二行"
来源：http://dali.yangfankeji.com/Article/details/gtrnvnmbdu.html

[A14] 注释写法
来源：http://dali.sysykeji.top/Article/details/gtefnxbbah.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhiwuduotai.top/Article/details/gtmfwnovdj.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.ppjwa.cn/Article/details/gtlquybbso.html

JS:   // 单行；/* 多行 */
来源：http://dali.xinyue.icu/Article/details/gthvwgrswp.html

TS:   // 单行；/* 多行 */
来源：http://dali.yongpay.top/Article/details/gtdjnpcebz.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.ehwqpu.com/Article/details/gtdjzksoyt.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gtwvaruser.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.birdmap.top/Article/details/gtcmjmzwof.html

C#:   // 单行；/* 多行 */
来源：http://dali.chenjidiqi.icu/Article/details/gtfxajgngd.html

[A15] 空值判断与默认值
来源：http://dali.ehwqpu.com/Article/details/gtoaxnpcyh.html

Py:   value = data or "默认值"
来源：http://dali.c1oappe.top/Article/details/gtxrgttxyt.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.aibaodan.cn/Article/details/gtspbmurzz.html

JS:   const value = data ?? "默认值";
来源：http://dali.mhx1999.top/Article/details/gtcrdiahey.html

TS:   const value = data ?? "默认值";
来源：http://dali.iojbl.cn/Article/details/gtvchpnuuh.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yvedp.cn/Article/details/gtdzgwjrfr.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.aizwys.cn/Article/details/gtbseywztq.html


<!-- 参考信息 -->