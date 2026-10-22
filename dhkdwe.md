代发 wailian999

[U87] JS：解构默认值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibbnqfbs.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yueranfly.top/Article/details/gtphxsmvwl.html

[U88] JS：对象展开合并
来源：http://dali.feifeiyinyue.top/Article/details/gtsomlgiey.html

{ ...a, ...b }
来源：http://dali.meibo888.top/Article/details/gtuibadmiv.html

[U89] JS：数组去重
来源：http://dali.tianlin.xyz/Article/details/gtqaxirafk.html

[...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gtxogkepim.html

[U90] JS：数字数组排序
来源：http://dali.ybcxt.top/Article/details/gtxhzfvsva.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthipwykgy.html

[U91] JS：对象键值遍历
来源：http://dali.hammf.cn/Article/details/gtrrdhvmyg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.fengsongda.top/Article/details/gttrxjzequ.html

[U92] JS：深拷贝
来源：http://dali.birdmap.top/Article/details/gtolkhuoqn.html

structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gtnyleqfjm.html

[U93] JS：模板字符串
来源：http://dali.gogol.net.cn/Article/details/gtfmzikhnm.html

`共 ${n} 条`
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmiyfafu.html

[U94] JS：箭头函数
来源：http://dali.redwolf501.top/Article/details/gtiktbodmq.html

const double = x => x * 2;
来源：http://dali.fengsongda.top/Article/details/gtrdadtuvi.html

[U95] JS：Promise 包装
来源：http://dali.yonumen.top/Article/details/gtdnmxhyut.html

new Promise((resolve, reject) => {})
来源：http://dali.haohaochexian.top/Article/details/gtcyoxvyje.html

[U96] JS：async/await 与异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxwleyvt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gtchzzwjln.html

[U97] JS：并发请求
来源：http://dali.meibo888.top/Article/details/gtvbkdqgnw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gtdisddmxv.html

[U98] JS：fetch 带 JSON
来源：http://dali.shzxlz.cn/Article/details/gtticrfxiq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zdqjudy.top/Article/details/gtzqotlhmx.html

[U99] JS：事件监听
来源：http://dali.shangyingyoupin.top/Article/details/gtlgpcmwha.html

el.addEventListener("click", e => {})
来源：http://dali.cucudq.cn/Article/details/gtgphqkekd.html

[U100] JS：DOM 查询
来源：http://dali.pengpengdd.cyou/Article/details/gtsdirphzt.html

document.querySelector(".item")
来源：http://dali.yanxiufei.cn/Article/details/gtpknupoov.html

[U101] JS：classList 操作
来源：http://dali.zhoulong.xyz/Article/details/gtddixuhko.html

el.classList.toggle("active")
来源：http://dali.chenjidiqi.icu/Article/details/gtidncnlgc.html

[U102] JS：本地存储
来源：http://dali.316326.xyz/Article/details/gtagrbjptx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hongshengwenyu.top/Article/details/gtmawaysis.html

[U103] JS：定时器
来源：http://dali.redwolf501.top/Article/details/gtqgwnyoyd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.aizwys.cn/Article/details/gtmeiciugr.html

[U104] JS：防抖
来源：http://dali.tianlin.xyz/Article/details/gtxdyxqxsc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gtlbrqutvn.html

[U105] JS：节流
来源：http://dali.feifeiyinyue.top/Article/details/gtqbxokcmj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jqgufenzy.top/Article/details/gtfdtnzulq.html

[U106] JS：日期格式化
来源：http://dali.fzhhl.top/Article/details/gtlnqanqzh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.birdmap.top/Article/details/gtvwyruxmk.html

[U107] JS：数字千分位
来源：http://dali.hammf.cn/Article/details/gtedykfrca.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinqigfzy.top/Article/details/gtgsqcgnxm.html

[U108] JS：随机整数
来源：http://dali.hfpthk.cn/Article/details/gtetjxdkue.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.aibaodan.cn/Article/details/gtkgscqgvs.html

[U109] JS：数组分组
来源：http://dali.xuanzx.com/Article/details/gtrlnmotzj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.chenlongwang.top/Article/details/gtnrwgxosy.html

[U110] JS：数组分块
来源：http://dali.sufxvd.cn/Article/details/gtqnlfrkzh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ehwqpu.com/Article/details/gtkmglnzij.html

[U111] JS：对象转 Map
来源：http://dali.sweek.top/Article/details/gtahplrfuv.html

new Map(Object.entries(obj))
来源：http://dali.yangfankeji.com/Article/details/gtrevnufpb.html

[U112] JS：字符串补位
来源：http://dali.hywenlv.cn/Article/details/gtipkiyevo.html

"7".padStart(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtioipqfou.html

[U113] JS：正则替换全部
来源：http://dali.xylfe.cn/Article/details/gtuemwiubj.html

s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtbkfsmtwy.html

[U114] JS：JSON 深比较
来源：http://dali.zhengqikj.top/Article/details/gtgqvzybmr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhixingplan.top/Article/details/gtoblaxmlt.html

[U115] JS：生成 UUID
来源：http://dali.tanke756.top/Article/details/gtbiiqucdt.html

crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gtqvpxnufp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.dianchejie.cn/Article/details/gtygkvmyvy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.wangdashe.top/Article/details/gtiyxudnrh.html

[U117] JS：单元测试
来源：http://dali.yuxming.cn/Article/details/gtfjytlfsh.html

npm i -D vitest;  npx vitest
来源：http://dali.mhx1999.top/Article/details/gtxxggcbbo.html

[U118] JS：开发服务器
来源：http://dali.guowangkeji.top/Article/details/gtvctuwjck.html

npm i -D vite;  npx vite
来源：http://dali.hongshengwenyu.top/Article/details/gtyzfqxcoj.html

[U119] JS：生产构建
来源：http://dali.c1oappe.top/Article/details/gthzpwbxgt.html

npx vite build
来源：http://dali.yangfankeji.com/Article/details/gtepwlfbiu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.daria6918.cn/Article/details/gtiftjvpxa.html

import.meta.env.VITE_API_URL
来源：http://dali.yonumen.top/Article/details/gtttddmlaa.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtxrdnsonw.html

统计汇总
来源：http://dali.ivvv.top/Article/details/gtqmnvvosf.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtnmxheqwd.html

按语言统计（条）：
来源：http://dali.hfpthk.cn/Article/details/gtoonmylpx.html

Python ......... 252
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdpliswpy.html

PHP ............ 252
来源：http://dali.hfpthk.cn/Article/details/gtlhudsgfi.html

JavaScript ..... 252
来源：http://dali.yj202588.top/Article/details/gtbadxzozd.html

TypeScript ..... 212
来源：http://dali.iojbl.cn/Article/details/gtliyenrof.html

Java ........... 212
来源：http://dali.gotoacloud.top/Article/details/gtiamcyadf.html

Go ............. 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtvveovmzp.html

Ruby ........... 212
来源：http://dali.yj20258.top/Article/details/gtzumjjbnw.html

C# ............. 212
来源：http://dali.wangdashe.top/Article/details/gtghkaiotm.html

C .............. 30
来源：http://dali.yj20258.top/Article/details/gtphtjumds.html

C++ ............ 30
来源：http://dali.jiagoushi.top/Article/details/gtijtzdrpz.html

SQL ............ 90
来源：http://dali.yvedp.cn/Article/details/gtfzdptgrk.html

Bash ........... 80
来源：http://dali.sysykeji.top/Article/details/gtdilklipr.html

Kotlin ......... 15
来源：http://dali.shanyushiyangkeji.top/Article/details/gthitlxiam.html

Swift .......... 15
来源：http://dali.ydzc1.top/Article/details/gtathkdibl.html

Lua ............ 10
来源：http://dali.sxryk.cn/Article/details/gtnjsskjxh.html

Perl ........... 10
来源：http://dali.meibo888.top/Article/details/gtejwpblgn.html

Scala .......... 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobldepyh.html

------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gtucremrqv.html

合计 ........... 2106 条
来源：http://dali.yuanzhike.top/Article/details/gtbnfrvmcd.html

按章节统计：
来源：http://dali.zhengqikj.top/Article/details/gtzqpiqwej.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hysaishi.cn/Article/details/gtdmbuxctv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhengqikj.top/Article/details/gtmkqfhqep.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cucudq.cn/Article/details/gthrhjhnco.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cucudq.cn/Article/details/gtechtaqzb.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.svipenyu.cn/Article/details/gtyymgptiy.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhoulong.xyz/Article/details/gtqzprnetz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yanxiufei.cn/Article/details/gtggpsqhge.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhongyouzk.top/Article/details/gtuvquzhcl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gtagzgdqzj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hfpthk.cn/Article/details/gttwbsihca.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gtforgwlsu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gtmvowajit.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gtblazclxm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangtech.top/Article/details/gtdlnpbncq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.aibaodan.cn/Article/details/gtgzenjome.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.kuanghao11.cn/Article/details/gtvkicpzsf.html

Q SQL 专题                              90
来源：http://dali.xziqi.cn/Article/details/gttkypziuz.html

R Bash 专题                             80
来源：http://dali.shangyingyoupin.top/Article/details/gtnlsowpht.html

S C / C++ 专题                          60
来源：http://dali.shanyushiyangtech.top/Article/details/gtpfptqzxf.html

T 其他语言补充                          60
来源：http://dali.yj202588.top/Article/details/gtzchbzjnw.html

U 高频实用片段                         120
来源：http://dali.yuxming.cn/Article/details/gtxadmhhfo.html

------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gtcmsjfgwq.html

合计                                  2106 条
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokzjqywa.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gtffairwlg.html

使用提醒
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfumxjlq.html

--------------------------------------------------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gtyblyzlyq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ydzc1.top/Article/details/gtdtblawmn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yuanzhike.top/Article/details/gthnfmzlky.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hysaishi.cn/Article/details/gtsxcwkqby.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xylfe.cn/Article/details/gtjfrlhlbv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jlsjyb.cn/Article/details/gtsrxzkkxe.html

—— 文件结束 ——
来源：http://dali.dashuyun.cn/Article/details/gthlebvpiy.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkbdyvni.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.aizwys.cn/Article/details/gtogtytqpd.html

Common Programming Examples Cheat Book
来源：http://dali.yj20258888.top/Article/details/gtwbcpsguq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gttvlkulym.html

【收录内容】
来源：http://dali.jiagoushi.top/Article/details/gtdoivyopp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaufroypa.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.fengsongda.top/Article/details/gtyyqibwiv.html

SQL · Bash · C · C++
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxgcvwvq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jiagoushi.top/Article/details/gtngrngfts.html

【使用说明】
来源：http://dali.aizwys.cn/Article/details/gthiguhdgg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhoulong.xyz/Article/details/gtmxnpdkhz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.snrcjt.cn/Article/details/gteduztyxm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yj202588.top/Article/details/gtupadlngq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.cucudq.cn/Article/details/gtmgxcdhth.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.haohaochexian.top/Article/details/gtgkgajpeo.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hfpthk.cn/Article/details/gtssuawtle.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.birdmap.top/Article/details/gtvilqaiwh.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yj202588.top/Article/details/gtwjnwswkl.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.chenlongwang.top/Article/details/gtaswnnctz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.dashuyun.cn/Article/details/gtuiesakvr.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yueranfly.top/Article/details/gtsosfwgbe.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yonumen.top/Article/details/gtkqmfeutr.html

【文件统计】
来源：http://dali.vqdsnc.cn/Article/details/gtyqikoklw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgpvnjcdz.html

--------------------------------------------------------------------------------
来源：http://dali.gaohongyu789.top/Article/details/gtawyxdpwc.html

目  录
来源：http://dali.aizwys.cn/Article/details/gtqunumtam.html

--------------------------------------------------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gtaytlfsto.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.fzhhl.top/Article/details/gtiimiujrs.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.smart0.xyz/Article/details/gtfevejxpe.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.nwbrower.top/Article/details/gtgihratda.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.dianchejie.cn/Article/details/gtdkpelcuj.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shzxlz.cn/Article/details/gthjbqalco.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.svipenyu.cn/Article/details/gtmmtkwydh.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.quarkkingdee.top/Article/details/gtzeacplmd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yuanzhike.top/Article/details/gtueptjlwp.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cdnleiting.top/Article/details/gtoguemujb.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.redwolf501.top/Article/details/gtbuvrtdue.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkwcxzjp.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yanxiufei.cn/Article/details/gtmlfinbxa.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gtojeplkgp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.cheryme.top/Article/details/gtfggwynjl.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shzxlz.cn/Article/details/gtwjhajdda.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jiagoushi.top/Article/details/gtdltpsxzq.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gtyviwnxwj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hnqzz.top/Article/details/gttjcldznj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yj202588.top/Article/details/gtdblrovhk.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yanxiufei.cn/Article/details/gtbucfbhot.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.shzxlz.cn/Article/details/gtdytffcpd.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtnhednxem.html

A. 基础语法与类型
来源：http://dali.dashuyun.cn/Article/details/gtffureyuj.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gteccviexs.html

[A01] Hello World
来源：http://dali.sysykeji.top/Article/details/gtovalcnso.html

Py:   print("Hello, World!")
来源：http://dali.nanxinkj.top/Article/details/gtetsggnzs.html

PHP:  echo "Hello, World!";
来源：http://dali.nanxinkj.top/Article/details/gtlopzhsux.html

JS:   console.log("Hello, World!");
来源：http://dali.gogol.net.cn/Article/details/gtfzxjjjxa.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yj20258.top/Article/details/gthcjeoisc.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhongyouzk.top/Article/details/gtckvhtyff.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhongyouzk.top/Article/details/gtxokhjjio.html

Ruby: puts "Hello, World!"
来源：http://dali.jlsjyb.cn/Article/details/gthmxqzpue.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.smart0.xyz/Article/details/gtwujxyauu.html

[A02] 变量声明与赋值
来源：http://dali.wangshuangyany.cn/Article/details/gtbpasoxnj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ivvv.top/Article/details/gtebshmdib.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.gotoacloud.top/Article/details/gtokqoeton.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cashguo.top/Article/details/gtdnzgrjyx.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xuetiantiany.cn/Article/details/gtqgamojty.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdivzpxz.html

Go:   name := "Alex"; age := 20
来源：http://dali.shzxlz.cn/Article/details/gtjspbeikt.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yuxming.cn/Article/details/gtyswjnpjr.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jinqigfzy.top/Article/details/gtcmhecdxo.html

[A03] 常量定义
来源：http://dali.yonumen.top/Article/details/gtrignyxcf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.pengpengdd.cyou/Article/details/gtxzuiyolu.html

PHP:  const PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtpnpbfsgg.html

JS:   const PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtaoqdabsq.html

TS:   const PI: number = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gttekuqaqn.html

Java: static final double PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtpmqhlnxn.html

Go:   const PI = 3.14159
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkisrylnf.html

Ruby: PI = 3.14159
来源：http://dali.yj20258888.top/Article/details/gtznzyoeop.html

C#:   const double PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtsqsrvxdg.html

[A04] 判断变量类型
来源：http://dali.xziqi.cn/Article/details/gtqgeywkqw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.shuidangran.top/Article/details/gtrzwfpnrc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jinqigfzy.top/Article/details/gtatudkhoe.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.havefunace.top/Article/details/gtzhafwxcg.html

TS:   typeof x; x instanceof Date
来源：http://dali.tanke756.top/Article/details/gtfbndqhsp.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hfpthk.cn/Article/details/gtjyzvczri.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.sweek.top/Article/details/gtzyfmopgs.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.fengsongda.top/Article/details/gtynsjoyds.html

C#:   x.GetType().Name; x is int
来源：http://dali.nwbrower.top/Article/details/gtceycanqf.html

[A05] 整数除法与取模
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdzjddbd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.andypj.xyz/Article/details/gtakbyuubd.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gtpsjwcndj.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcyfxsuf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.fzhhl.top/Article/details/gttmcfbcog.html

Java: 7 / 2; 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gtofklyiok.html

Go:   7 / 2; 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gtxlxvgvui.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yongpay.top/Article/details/gtxasanjiy.html

C#:   7 / 2; 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gtuhocibej.html

[A06] 字符串转数字
来源：http://dali.xinyue.icu/Article/details/gtdgrsbvhb.html

Py:   int("42"); float("3.14")
来源：http://dali.zhoulong.xyz/Article/details/gtbpmnwflx.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbrorybl.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hysaishi.cn/Article/details/gtwimwfnvm.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jinqigfzy.top/Article/details/gtfabspkbv.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.nanxinkj.top/Article/details/gttpkdtfmo.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.cqqwz.cn/Article/details/gtvvjjljol.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yj202588.top/Article/details/gtalyitctd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.smart0.xyz/Article/details/gtscjzchod.html

[A07] 数字转字符串
来源：http://dali.guowangkeji.top/Article/details/gteiuihzcy.html

Py:   str(42)
来源：http://dali.smart0.xyz/Article/details/gtzlkmbkgj.html

PHP:  (string) 42; strval(42)
来源：http://dali.hnxiangtu.top/Article/details/gtbrvqyxqs.html

JS:   String(42); (42).toString()
来源：http://dali.bjfxy.top/Article/details/gtdhmuqfov.html

TS:   String(42)
来源：http://dali.yongpay.top/Article/details/gtmoqwuujb.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.daria6918.cn/Article/details/gtutiamjni.html

Go:   strconv.Itoa(42)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahjlpjia.html

Ruby: 42.to_s
来源：http://dali.jqgufenzy.top/Article/details/gtjaggggqy.html

C#:   42.ToString()
来源：http://dali.316326.xyz/Article/details/gtenqlfghk.html

[A08] 取整与四舍五入
来源：http://dali.jqgufenzy.top/Article/details/gtdfserkga.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gtfaesqzpx.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhoulong.xyz/Article/details/gtokzfkgbe.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.gaohongyu789.top/Article/details/gtkeqtgztm.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.guannengcc.top/Article/details/gtduxehvhs.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.tian-w.cn/Article/details/gtlrszfdzi.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zdqjudy.top/Article/details/gtjembuiin.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.nwbrower.top/Article/details/gtkwbfdjmf.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hnxiangtu.top/Article/details/gtjpthfkjg.html

[A09] 绝对值与最大最小值
来源：http://dali.gaohongyu789.top/Article/details/gtdgdlovcw.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.birdmap.top/Article/details/gtcesrtshs.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtnskwmhfx.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtlnjyykyt.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gtjhrqwnre.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.nwbrower.top/Article/details/gtcidgmjxk.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hnxiangtu.top/Article/details/gtjomxhnre.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.chenlongwang.top/Article/details/gtgboiagtx.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.hfpthk.cn/Article/details/gtllzsfreh.html

[A10] 生成随机数
来源：http://dali.ppjwa.cn/Article/details/gtzaxczinm.html

Py:   import random; random.randint(1, 100)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzfmetll.html

PHP:  random_int(1, 100);
来源：http://dali.yj20258888.top/Article/details/gthkgyhsuw.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.9152youxi.cn/Article/details/gtndwiggal.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.chenzaomai.com/Article/details/gtmgibfbmq.html

Java: new Random().nextInt(100) + 1
来源：http://dali.ehwqpu.com/Article/details/gtgydhknsd.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.cheryme.top/Article/details/gtfflchrjb.html

Ruby: rand(1..100)
来源：http://dali.dashuyun.cn/Article/details/gtthsrcejk.html

C#:   new Random().Next(1, 101)
来源：http://dali.dashuyun.cn/Article/details/gtzifaxhag.html

[A11] 条件表达式（三元）
来源：http://dali.yj20258888.top/Article/details/gtxwymganv.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.gaohongyu789.top/Article/details/gtjwvehvdc.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.shanyushiyangtech.top/Article/details/gtiapjexjx.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yueranfly.top/Article/details/gtvfwmhdzh.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gtfryyyqzg.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtakpnoizc.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.haohaochexian.top/Article/details/gtkoyispom.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.cucudq.cn/Article/details/gtjgwcstvl.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.quarkkingdee.top/Article/details/gtbujbobis.html

[A12] 字符串插值 / 格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtkhrgfxwp.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.sxryk.cn/Article/details/gtnlrzboip.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.hnqzz.top/Article/details/gtyherjvjt.html

JS:   `Hello, ${name}!`
来源：http://dali.jqgufenzy.top/Article/details/gtenbltqcm.html

TS:   `Hello, ${name}!`
来源：http://dali.mhx1999.top/Article/details/gtisybzipq.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jiagoushi.top/Article/details/gtkcbilsyi.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.ydzc1.top/Article/details/gtbbcviivn.html

Ruby: "Hello, #{name}!"
来源：http://dali.jqgufenzy.top/Article/details/gthrtnmhzn.html

C#:   $"Hello, {name}!"
来源：http://dali.yuanzhike.top/Article/details/gtwujnyjei.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.hywenlv.cn/Article/details/gtruhtxvvi.html

Py:   "第一行\n第二行"
来源：http://dali.haohaochexian.top/Article/details/gtophimpep.html

PHP:  "第一行\n第二行"
来源：http://dali.cashguo.top/Article/details/gtngztpkjx.html

JS:   "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gtpimuytxz.html

TS:   "第一行\n第二行"
来源：http://dali.tanke756.top/Article/details/gtocgtrfpb.html

Java: "第一行\n第二行"
来源：http://dali.zhengqikj.top/Article/details/gtotilxbpu.html

Go:   "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gtiqqeorti.html

Ruby: "第一行\n第二行"
来源：http://dali.shanyushiyangtech.top/Article/details/gtxeedafzi.html

C#:   "第一行\n第二行"
来源：http://dali.hywenlv.cn/Article/details/gtmxmgvnir.html

[A14] 注释写法
来源：http://dali.vqdsnc.cn/Article/details/gtpixpwhmm.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jianghu66.top/Article/details/gtvewvejpb.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpqzxiyp.html

JS:   // 单行；/* 多行 */
来源：http://dali.jinghuilouyu.cn/Article/details/gtyuvqpkdl.html

TS:   // 单行；/* 多行 */
来源：http://dali.jiagoushi.top/Article/details/gtlemujbut.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.aizwys.cn/Article/details/gtgrmwzgdr.html

Go:   // 单行；/* 多行 */
来源：http://dali.hnxiangtu.top/Article/details/gtiezwttop.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.fzhhl.top/Article/details/gtbdwgzqqb.html


<!-- 参考信息 -->