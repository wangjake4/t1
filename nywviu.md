代发 wailian999

[U87] JS：解构默认值
来源：http://dali.zhengqikj.top/Article/details/gtxgntdrjx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hfpthk.cn/Article/details/gtxhezkoxl.html

[U88] JS：对象展开合并
来源：http://dali.316326.xyz/Article/details/gtjzkyjhzg.html

{ ...a, ...b }
来源：http://dali.yangfankeji.com/Article/details/gtqdmiqybw.html

[U89] JS：数组去重
来源：http://dali.gzhubu.top/Article/details/gtrycwmdwt.html

[...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gtrdcllani.html

[U90] JS：数字数组排序
来源：http://dali.yj202588.top/Article/details/gtquxzncma.html

[...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gtflhkxhmj.html

[U91] JS：对象键值遍历
来源：http://dali.ybcxt.top/Article/details/gtqopdzwgu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yj20258.top/Article/details/gtfzpkvxcv.html

[U92] JS：深拷贝
来源：http://dali.hnxiangtu.top/Article/details/gtdcimjuiv.html

structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtrrrpddti.html

[U93] JS：模板字符串
来源：http://dali.zhongyouzk.top/Article/details/gtpowtruev.html

`共 ${n} 条`
来源：http://dali.dianchejie.cn/Article/details/gthdankwoj.html

[U94] JS：箭头函数
来源：http://dali.aibaodan.cn/Article/details/gtakspkcba.html

const double = x => x * 2;
来源：http://dali.mhx1999.top/Article/details/gtindeudnv.html

[U95] JS：Promise 包装
来源：http://dali.yongpay.top/Article/details/gtbmwedjwl.html

new Promise((resolve, reject) => {})
来源：http://dali.nanxuanxn.top/Article/details/gtmhcxncqy.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gtsnvktbtl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gtatswehhy.html

[U97] JS：并发请求
来源：http://dali.chenzaomai.com/Article/details/gtfimseheo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gtltnqhsgq.html

[U98] JS：fetch 带 JSON
来源：http://dali.xziqi.cn/Article/details/gtorqczjmg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zdqjudy.top/Article/details/gthbekmyru.html

[U99] JS：事件监听
来源：http://dali.mhx1999.top/Article/details/gtfkafikak.html

el.addEventListener("click", e => {})
来源：http://dali.birdmap.top/Article/details/gtguprxxji.html

[U100] JS：DOM 查询
来源：http://dali.sysykeji.top/Article/details/gtrxoctwrs.html

document.querySelector(".item")
来源：http://dali.mhx1999.top/Article/details/gtyynfqmit.html

[U101] JS：classList 操作
来源：http://dali.zhixingplan.top/Article/details/gtktnbcivw.html

el.classList.toggle("active")
来源：http://dali.hywenlv.cn/Article/details/gtdjjmrych.html

[U102] JS：本地存储
来源：http://dali.dashuyun.cn/Article/details/gtkevtyfsw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xuanzx.com/Article/details/gtsraengux.html

[U103] JS：定时器
来源：http://dali.sxryk.cn/Article/details/gtnzjsrbxi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sysykeji.top/Article/details/gtihksctxv.html

[U104] JS：防抖
来源：http://dali.zycfv.cn/Article/details/gtuizhnkjs.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gtgiqtvkdi.html

[U105] JS：节流
来源：http://dali.birdmap.top/Article/details/gtsiqhyyld.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ppjwa.cn/Article/details/gtgnvuwvlj.html

[U106] JS：日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gtktkqympp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwmbmmcm.html

[U107] JS：数字千分位
来源：http://dali.redwolf501.top/Article/details/gtyyqxstqo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.nwbrower.top/Article/details/gtltaeycld.html

[U108] JS：随机整数
来源：http://dali.jqgfzy.top/Article/details/gtijgmeivb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zdqjudy.top/Article/details/gtejbqudup.html

[U109] JS：数组分组
来源：http://dali.jiagoushi.top/Article/details/gtbkrjnbqf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.feifeiyinyue.top/Article/details/gtshwzukop.html

[U110] JS：数组分块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkgtkrco.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jyoumei.cn/Article/details/gtnobgkndd.html

[U111] JS：对象转 Map
来源：http://dali.hnxiangtu.top/Article/details/gtnlaylrqp.html

new Map(Object.entries(obj))
来源：http://dali.chenjidiqi.icu/Article/details/gtiodjuulx.html

[U112] JS：字符串补位
来源：http://dali.havefunace.top/Article/details/gtodvsaiut.html

"7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtaficeojs.html

[U113] JS：正则替换全部
来源：http://dali.gogol.net.cn/Article/details/gtvbhxmkja.html

s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtblivmukr.html

[U114] JS：JSON 深比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwwhvxju.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pycfn.com/Article/details/gtnozwiymt.html

[U115] JS：生成 UUID
来源：http://dali.sysykeji.top/Article/details/gtlknubzan.html

crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gtirszaemb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ybcxt.top/Article/details/gteloympec.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hysaishi.cn/Article/details/gtxmsgdlcd.html

[U117] JS：单元测试
来源：http://dali.mhx1999.top/Article/details/gtspunwxpz.html

npm i -D vitest;  npx vitest
来源：http://dali.feifeiyinyue.top/Article/details/gtfvyypgok.html

[U118] JS：开发服务器
来源：http://dali.xinyue.icu/Article/details/gtmeovkgho.html

npm i -D vite;  npx vite
来源：http://dali.chenzaomai.com/Article/details/gtaqjbqacf.html

[U119] JS：生产构建
来源：http://dali.jlsjyb.cn/Article/details/gtnnciewbv.html

npx vite build
来源：http://dali.ivvv.top/Article/details/gteqljeqkl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.kuanghao11.cn/Article/details/gtfbraqkqc.html

import.meta.env.VITE_API_URL
来源：http://dali.jyoumei.cn/Article/details/gtsfkdysgw.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gthetnlmuv.html

统计汇总
来源：http://dali.sysykeji.top/Article/details/gtfzbxkoqe.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gthwbqrkph.html

按语言统计（条）：
来源：http://dali.haohaochexian.top/Article/details/gtvjjvyxjp.html

Python ......... 252
来源：http://dali.sweek.top/Article/details/gtucspyuoc.html

PHP ............ 252
来源：http://dali.haohaochexian.top/Article/details/gtreujmcdm.html

JavaScript ..... 252
来源：http://dali.meibo888.top/Article/details/gtbwridchv.html

TypeScript ..... 212
来源：http://dali.c1oappe.top/Article/details/gtzyobxfab.html

Java ........... 212
来源：http://dali.shangyingyoupin.top/Article/details/gtbgcpmyrl.html

Go ............. 212
来源：http://dali.jinqigufen.top/Article/details/gtjgjsbwtb.html

Ruby ........... 212
来源：http://dali.yonumen.top/Article/details/gtnrmesgdz.html

C# ............. 212
来源：http://dali.hongshengwenyu.top/Article/details/gteekcaaua.html

C .............. 30
来源：http://dali.vqdsnc.cn/Article/details/gtknzzegpw.html

C++ ............ 30
来源：http://dali.andypj.xyz/Article/details/gttkafadwb.html

SQL ............ 90
来源：http://dali.andypj.xyz/Article/details/gtvfmjewuk.html

Bash ........... 80
来源：http://dali.fzhhl.top/Article/details/gtbhtzlfgi.html

Kotlin ......... 15
来源：http://dali.zhixingplan.top/Article/details/gtnwxtfutx.html

Swift .......... 15
来源：http://dali.gaohongyu789.top/Article/details/gtxornzmys.html

Lua ............ 10
来源：http://dali.fzhhl.top/Article/details/gtzsslposy.html

Perl ........... 10
来源：http://dali.mhx1999.top/Article/details/gtasmyshjr.html

Scala .......... 10
来源：http://dali.yj20258888.top/Article/details/gtzbpnazvu.html

------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkbxtugup.html

合计 ........... 2106 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrefuavf.html

按章节统计：
来源：http://dali.jqgufenzy.top/Article/details/gtvssatxye.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cashguo.top/Article/details/gtzptlsruj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yongpay.top/Article/details/gtmwwlorku.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrtsaapx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xziqi.cn/Article/details/gtsbhgowqy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.guowangkeji.top/Article/details/gtukyqoaoy.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yonumen.top/Article/details/gtzglmveik.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tanke756.top/Article/details/gtoarxxfmc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhoulong.xyz/Article/details/gtekulcafl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gtaviwsdel.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gogol.net.cn/Article/details/gtgqsxdsul.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gtflehotch.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gtdsrosjqx.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gtdkmgghps.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.aibaodan.cn/Article/details/gtfukizehc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shzxlz.cn/Article/details/gtrdcofgin.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gtfmguzliy.html

Q SQL 专题                              90
来源：http://dali.wangdashe.top/Article/details/gtwyfobsol.html

R Bash 专题                             80
来源：http://dali.xuanzx.com/Article/details/gtedzbaquo.html

S C / C++ 专题                          60
来源：http://dali.guannengcc.top/Article/details/gtphzqwmnb.html

T 其他语言补充                          60
来源：http://dali.shuidangran.top/Article/details/gtyhpxfdsz.html

U 高频实用片段                         120
来源：http://dali.birdmap.top/Article/details/gtgkyitxxv.html

------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gtmlfbgluf.html

合计                                  2106 条
来源：http://dali.guannengcc.top/Article/details/gtuhfijzwo.html

--------------------------------------------------------------------------------
来源：http://dali.yongpay.top/Article/details/gtxdthruhj.html

使用提醒
来源：http://dali.hnqzz.top/Article/details/gtmueucrvo.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gtsicdqmrt.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jlsjyb.cn/Article/details/gtkejojyau.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ydzc1.top/Article/details/gtnoubjivi.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zdqjudy.top/Article/details/gttdabneju.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yongpay.top/Article/details/gtnoqfhzih.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtwokchv.html

—— 文件结束 ——
来源：http://dali.fengsongda.top/Article/details/gtzfgbbisp.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtjtnsfnml.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hysaishi.cn/Article/details/gtabtzbedq.html

Common Programming Examples Cheat Book
来源：http://dali.shuidangran.top/Article/details/gtdtwunkrk.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtqxncidjc.html

【收录内容】
来源：http://dali.feifeiyinyue.top/Article/details/gtkbmmvtok.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.kuanghao11.cn/Article/details/gtvjhcfehe.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.9152youxi.cn/Article/details/gtxwtatkmx.html

SQL · Bash · C · C++
来源：http://dali.ybcxt.top/Article/details/gtuzaraygq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.tanke756.top/Article/details/gtrsurkeyh.html

【使用说明】
来源：http://dali.guannengcc.top/Article/details/gtwibxnmch.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yuxming.cn/Article/details/gtamkbskej.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.gogol.net.cn/Article/details/gtjabqgoia.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xuanzx.com/Article/details/gttxsjxpdl.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zdqjudy.top/Article/details/gtndivnyei.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.nanxuanxn.top/Article/details/gtpfxlirnz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hnqzz.top/Article/details/gtpixulsvo.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.pengpengdd.cyou/Article/details/gtozaemkod.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.haohaochexian.top/Article/details/gtnvzzwurz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjuwvlzrs.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.gzhubu.top/Article/details/gtxbgixrva.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.shuidangran.top/Article/details/gtljcxeltt.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jqgfzy.top/Article/details/gtwfhffmse.html

【文件统计】
来源：http://dali.hnxiangtu.top/Article/details/gttuqakhay.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hnqzz.top/Article/details/gtbxitujev.html

--------------------------------------------------------------------------------
来源：http://dali.quarkkingdee.top/Article/details/gtjgexjuoo.html

目  录
来源：http://dali.xinyue.icu/Article/details/gtcfnoospv.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtrldtpqhk.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.chenlongwang.top/Article/details/gteptsludm.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hnxiangtu.top/Article/details/gtrmrkiimc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.c1oappe.top/Article/details/gtkvlkdkog.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.gotoacloud.top/Article/details/gtwucrcwmx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.gotoacloud.top/Article/details/gtcrsgnncd.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.haohaochexian.top/Article/details/gtyrruqjqv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtecyuwbri.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.kuanghao11.cn/Article/details/gtlqcnlrmg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xziqi.cn/Article/details/gtxgkcdvlf.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yongpay.top/Article/details/gtiojmlgiu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ehwqpu.com/Article/details/gtxtvmyzvq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.aizwys.cn/Article/details/gtwxasuyxn.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gtauojigau.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.9152youxi.cn/Article/details/gtxhlrubup.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xuanzx.com/Article/details/gtrxlfwsho.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gtkepsxlbg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.birdmap.top/Article/details/gtsqvcllym.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hywenlv.cn/Article/details/gtodrbsirp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.redwolf501.top/Article/details/gtajyghlyj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenzaomai.com/Article/details/gtlzylafcm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.dashuyun.cn/Article/details/gtqwpfnivs.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtczfccafy.html

A. 基础语法与类型
来源：http://dali.iojbl.cn/Article/details/gtfjtrajlk.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gttmnselic.html

[A01] Hello World
来源：http://dali.hfpthk.cn/Article/details/gtpnmpupek.html

Py:   print("Hello, World!")
来源：http://dali.feifeiyinyue.top/Article/details/gtjxriuzru.html

PHP:  echo "Hello, World!";
来源：http://dali.wangdashe.top/Article/details/gtutlhthpi.html

JS:   console.log("Hello, World!");
来源：http://dali.zdqjudy.top/Article/details/gtvsfxxpgy.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.sxryk.cn/Article/details/gtergqywws.html

Java: System.out.println("Hello, World!");
来源：http://dali.jianghu66.top/Article/details/gtuafbcoje.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.tianlin.xyz/Article/details/gtheszqaro.html

Ruby: puts "Hello, World!"
来源：http://dali.aibaodan.cn/Article/details/gtpelfdltr.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.cucudq.cn/Article/details/gtpruoalml.html

[A02] 变量声明与赋值
来源：http://dali.jqgfzy.top/Article/details/gtpnnycozs.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhengqikj.top/Article/details/gthwtdwfqi.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.chenjidiqi.icu/Article/details/gtwvrjchyv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gtazbnrjws.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.chenjidiqi.icu/Article/details/gtkrdobksq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.havefunace.top/Article/details/gtxlbkbpml.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gtnerivrzl.html

Ruby: name = "Alex"; age = 20
来源：http://dali.tanke756.top/Article/details/gtvnksmscd.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.gzhubu.top/Article/details/gtkgwkucaa.html

[A03] 常量定义
来源：http://dali.dashuyun.cn/Article/details/gtzuamdamj.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jianghu66.top/Article/details/gtoimmhajj.html

PHP:  const PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtixsosdkp.html

JS:   const PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtastvhxdj.html

TS:   const PI: number = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtolzohtmi.html

Java: static final double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtljktghko.html

Go:   const PI = 3.14159
来源：http://dali.daria6918.cn/Article/details/gthppsgluj.html

Ruby: PI = 3.14159
来源：http://dali.sufxvd.cn/Article/details/gtmpfnihue.html

C#:   const double PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gttpveelbb.html

[A04] 判断变量类型
来源：http://dali.zhiwuduotai.top/Article/details/gtbtbabyxi.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.chenzaomai.com/Article/details/gtbcomfsnf.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtllnthbbv.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.316326.xyz/Article/details/gteymwklyt.html

TS:   typeof x; x instanceof Date
来源：http://dali.kuanghao11.cn/Article/details/gtvbfdjbbl.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.sufxvd.cn/Article/details/gtarsfsdtk.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.guowangkeji.top/Article/details/gtrdvieixm.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.svipenyu.cn/Article/details/gtzgxztbcu.html

C#:   x.GetType().Name; x is int
来源：http://dali.ybcxt.top/Article/details/gtgfcqjbpo.html

[A05] 整数除法与取模
来源：http://dali.gogol.net.cn/Article/details/gtbxnzywls.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.redwolf501.top/Article/details/gtbtbuvark.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gtcmjanjuu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gtswizdfmx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj20258.top/Article/details/gtmcflmbzb.html

Java: 7 / 2; 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gthzblbksz.html

Go:   7 / 2; 7 % 2
来源：http://dali.cheryme.top/Article/details/gtjkmqdrfj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gtgvpcogzc.html

C#:   7 / 2; 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gtagikvzkw.html

[A06] 字符串转数字
来源：http://dali.9152youxi.cn/Article/details/gtrnnjdwrx.html

Py:   int("42"); float("3.14")
来源：http://dali.sufxvd.cn/Article/details/gtgwpgxdbm.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hnqzz.top/Article/details/gtqqzqdqek.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.quarkkingdee.top/Article/details/gtluukriot.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhengqikj.top/Article/details/gtwpewtmhf.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhixingplan.top/Article/details/gtrokpfpnj.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhoulong.xyz/Article/details/gtpkexmoux.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.xinyue.icu/Article/details/gtabkpyxun.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.gotoacloud.top/Article/details/gtmtwyytqz.html

[A07] 数字转字符串
来源：http://dali.ybcxt.top/Article/details/gteqgzxzsg.html

Py:   str(42)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwxoultg.html

PHP:  (string) 42; strval(42)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkysbvnda.html

JS:   String(42); (42).toString()
来源：http://dali.cashguo.top/Article/details/gtzuonyohl.html

TS:   String(42)
来源：http://dali.dianchejie.cn/Article/details/gtjvciquup.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.tianlin.xyz/Article/details/gtlohmahef.html

Go:   strconv.Itoa(42)
来源：http://dali.quarkkingdee.top/Article/details/gtgudimyol.html

Ruby: 42.to_s
来源：http://dali.zdqjudy.top/Article/details/gtpeodcyql.html

C#:   42.ToString()
来源：http://dali.daria6918.cn/Article/details/gttviejmso.html

[A08] 取整与四舍五入
来源：http://dali.sxryk.cn/Article/details/gtlegouvub.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.9152youxi.cn/Article/details/gtthldxlmu.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hfpthk.cn/Article/details/gtvxnpnsls.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gtascfcqhn.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbsouinlr.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhoulong.xyz/Article/details/gtvtyzkzpx.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gtllttmcef.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yvedp.cn/Article/details/gtpgnizyej.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yongpay.top/Article/details/gtvkmifcpu.html

[A09] 绝对值与最大最小值
来源：http://dali.aizwys.cn/Article/details/gtybhymsef.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.pycfn.com/Article/details/gtybnwuxop.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gtxboqwobt.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.tian-w.cn/Article/details/gtupkvlkth.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtbejcuxsx.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtmhiwbmmy.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jyoumei.cn/Article/details/gtiyusujal.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.hywenlv.cn/Article/details/gtmsunqsui.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gtuhzctbui.html

[A10] 生成随机数
来源：http://dali.jianghu66.top/Article/details/gtzuzgcyvc.html

Py:   import random; random.randint(1, 100)
来源：http://dali.sxryk.cn/Article/details/gtjqcvnjqu.html

PHP:  random_int(1, 100);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmgqdznq.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shuidangran.top/Article/details/gtbopaqywz.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.meibo888.top/Article/details/gtsqzjlmpc.html

Java: new Random().nextInt(100) + 1
来源：http://dali.hysaishi.cn/Article/details/gtstjplsyj.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.daxiang520.top/Article/details/gtezivjyzj.html

Ruby: rand(1..100)
来源：http://dali.gaohongyu789.top/Article/details/gtithqpfqr.html

C#:   new Random().Next(1, 101)
来源：http://dali.jlsjyb.cn/Article/details/gtawgabfgq.html

[A11] 条件表达式（三元）
来源：http://dali.gzhubu.top/Article/details/gtfeqsspfl.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.haohaochexian.top/Article/details/gtqjqmmeqk.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.daxiang520.top/Article/details/gtuumqgwrn.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.shanyushiyangtech.top/Article/details/gtrcfyauvp.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jiagoushi.top/Article/details/gtklonjtnp.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gthmxumuge.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.hammf.cn/Article/details/gthfswujgh.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.nanxinkj.top/Article/details/gtgkruaaki.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yj20258888.top/Article/details/gtvoumaknq.html

[A12] 字符串插值 / 格式化
来源：http://dali.jiagoushi.top/Article/details/gtbyqgpwcq.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.9152youxi.cn/Article/details/gtixrbayrn.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.hysaishi.cn/Article/details/gtduutujnn.html

JS:   `Hello, ${name}!`
来源：http://dali.yj20258888.top/Article/details/gtrtgyeikn.html

TS:   `Hello, ${name}!`
来源：http://dali.pycfn.com/Article/details/gtazoicfwp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xinyue.icu/Article/details/gtbfviqpwk.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.cucudq.cn/Article/details/gtcrbnuakr.html

Ruby: "Hello, #{name}!"
来源：http://dali.birdmap.top/Article/details/gtfmempwgz.html

C#:   $"Hello, {name}!"
来源：http://dali.zycfv.cn/Article/details/gtrfcwdxzv.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.wangdashe.top/Article/details/gticayxdeo.html

Py:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gtbbttqmaa.html

PHP:  "第一行\n第二行"
来源：http://dali.andypj.xyz/Article/details/gtbzjqcgam.html

JS:   "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gtyhdrjchi.html

TS:   "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gtjrzbnjlo.html

Java: "第一行\n第二行"
来源：http://dali.yj20258888.top/Article/details/gtvzquilov.html

Go:   "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gtfjlccbdq.html

Ruby: "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gtvxkrxlsz.html

C#:   "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gtuhnahcso.html

[A14] 注释写法
来源：http://dali.chenjidiqi.icu/Article/details/gtwouvzhif.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zdqjudy.top/Article/details/gtxlpdzprh.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.daria6918.cn/Article/details/gtmvrlamyz.html

JS:   // 单行；/* 多行 */
来源：http://dali.9152youxi.cn/Article/details/gtctybdzvb.html

TS:   // 单行；/* 多行 */
来源：http://dali.vqdsnc.cn/Article/details/gtgfzlhmai.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.shanyushiyangtech.top/Article/details/gtulisygxf.html

Go:   // 单行；/* 多行 */
来源：http://dali.jinqigufen.top/Article/details/gtvrlyyqgy.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.svipenyu.cn/Article/details/gtfwrlqicz.html


<!-- 参考信息 -->