代发 wailian999

[U87] JS：解构默认值
来源：http://dali.dianchejie.cn/Article/details/gttxifrkiu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yueranfly.top/Article/details/gtefwrqkus.html

[U88] JS：对象展开合并
来源：http://dali.hnxiangtu.top/Article/details/gtoladpqhm.html

{ ...a, ...b }
来源：http://dali.haohaochexian.top/Article/details/gtkbynhtdt.html

[U89] JS：数组去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpuahtqq.html

[...new Set(arr)]
来源：http://dali.daria6918.cn/Article/details/gtuoycqauw.html

[U90] JS：数字数组排序
来源：http://dali.chenjidiqi.icu/Article/details/gtxsngsoem.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jqgfzy.top/Article/details/gtebmzbcdu.html

[U91] JS：对象键值遍历
来源：http://dali.quarkkingdee.top/Article/details/gtodhmqtpl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yj20258.top/Article/details/gtkdysgwxx.html

[U92] JS：深拷贝
来源：http://dali.guannengcc.top/Article/details/gtdvbnrrpf.html

structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gtxeajtaok.html

[U93] JS：模板字符串
来源：http://dali.havefunace.top/Article/details/gtbgticmns.html

`共 ${n} 条`
来源：http://dali.xuanzx.com/Article/details/gtfgoooyik.html

[U94] JS：箭头函数
来源：http://dali.hnqzz.top/Article/details/gtwfyztwdc.html

const double = x => x * 2;
来源：http://dali.shzxlz.cn/Article/details/gtfyngrota.html

[U95] JS：Promise 包装
来源：http://dali.zycfv.cn/Article/details/gtouhsseww.html

new Promise((resolve, reject) => {})
来源：http://dali.yangfankeji.com/Article/details/gtprwgjxuu.html

[U96] JS：async/await 与异常
来源：http://dali.ydzc1.top/Article/details/gtetyuzfkq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gtlchothcm.html

[U97] JS：并发请求
来源：http://dali.xinyue.icu/Article/details/gtmelnygsb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gtwbicbnzy.html

[U98] JS：fetch 带 JSON
来源：http://dali.hnqzz.top/Article/details/gtgiuoijwq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hammf.cn/Article/details/gtyybqdeuk.html

[U99] JS：事件监听
来源：http://dali.yuxming.cn/Article/details/gtmrbzdyat.html

el.addEventListener("click", e => {})
来源：http://dali.havefunace.top/Article/details/gtxvdovnxt.html

[U100] JS：DOM 查询
来源：http://dali.quarkkingdee.top/Article/details/gtersgnjqn.html

document.querySelector(".item")
来源：http://dali.zhoulong.xyz/Article/details/gtsolfwwak.html

[U101] JS：classList 操作
来源：http://dali.nanxinkj.top/Article/details/gtmrtbjcba.html

el.classList.toggle("active")
来源：http://dali.jinqigufen.top/Article/details/gtvrleykjj.html

[U102] JS：本地存储
来源：http://dali.jqgfzy.top/Article/details/gtzzcidcpq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.gzhubu.top/Article/details/gtqvqkecmv.html

[U103] JS：定时器
来源：http://dali.cucudq.cn/Article/details/gtubqgunwp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddawjoib.html

[U104] JS：防抖
来源：http://dali.daria6918.cn/Article/details/gthbhofxgs.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gtyqibagep.html

[U105] JS：节流
来源：http://dali.fzhhl.top/Article/details/gtfpfqelkx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yongpay.top/Article/details/gthzjslldk.html

[U106] JS：日期格式化
来源：http://dali.yueranfly.top/Article/details/gtdvrxltow.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hfpthk.cn/Article/details/gtuddiasvp.html

[U107] JS：数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gtrrgofkas.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yuxming.cn/Article/details/gttxtrrqfx.html

[U108] JS：随机整数
来源：http://dali.jinqigufen.top/Article/details/gtbmuhcgjb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.nwbrower.top/Article/details/gtshvcbtbj.html

[U109] JS：数组分组
来源：http://dali.gotoacloud.top/Article/details/gtzqimndgw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zycfv.cn/Article/details/gtaawaalvg.html

[U110] JS：数组分块
来源：http://dali.jinqigufen.top/Article/details/gtbbzzjycq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xuanzx.com/Article/details/gtrtfvplhj.html

[U111] JS：对象转 Map
来源：http://dali.cdnleiting.top/Article/details/gthzgaecby.html

new Map(Object.entries(obj))
来源：http://dali.gotoacloud.top/Article/details/gtjmsigues.html

[U112] JS：字符串补位
来源：http://dali.yongpay.top/Article/details/gtszdeacoa.html

"7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtxoesapus.html

[U113] JS：正则替换全部
来源：http://dali.c1oappe.top/Article/details/gtrehqwffn.html

s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gthtuwelvp.html

[U114] JS：JSON 深比较
来源：http://dali.nwbrower.top/Article/details/gtlzkplpop.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.smart0.xyz/Article/details/gtdymphlhj.html

[U115] JS：生成 UUID
来源：http://dali.sxryk.cn/Article/details/gtybdnrcfa.html

crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gtbsvhfrzf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.wangdashe.top/Article/details/gtiahsiruk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtnujzbexn.html

[U117] JS：单元测试
来源：http://dali.jyoumei.cn/Article/details/gthclpbume.html

npm i -D vitest;  npx vitest
来源：http://dali.zhoulong.xyz/Article/details/gtkudzpkeh.html

[U118] JS：开发服务器
来源：http://dali.shzxlz.cn/Article/details/gtbxphkoyj.html

npm i -D vite;  npx vite
来源：http://dali.yj202588.top/Article/details/gtwmhgvdpr.html

[U119] JS：生产构建
来源：http://dali.daxiang520.top/Article/details/gtbhzywivq.html

npx vite build
来源：http://dali.gotoacloud.top/Article/details/gtucdbggau.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinqigfzy.top/Article/details/gtcaufoggk.html

import.meta.env.VITE_API_URL
来源：http://dali.cucudq.cn/Article/details/gtiwkkngdb.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtqxsrheuj.html

统计汇总
来源：http://dali.jlsjyb.cn/Article/details/gtqgwgbvpe.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtluvrafge.html

按语言统计（条）：
来源：http://dali.zdqjudy.top/Article/details/gtufyhupsx.html

Python ......... 252
来源：http://dali.hammf.cn/Article/details/gtglpjlkwu.html

PHP ............ 252
来源：http://dali.daria6918.cn/Article/details/gtxczhxpgo.html

JavaScript ..... 252
来源：http://dali.yongpay.top/Article/details/gtcygmkbfy.html

TypeScript ..... 212
来源：http://dali.quarkkingdee.top/Article/details/gtjcpnesvl.html

Java ........... 212
来源：http://dali.9152youxi.cn/Article/details/gtkcabnklz.html

Go ............. 212
来源：http://dali.dianchejie.cn/Article/details/gtjxybasvo.html

Ruby ........... 212
来源：http://dali.daria6918.cn/Article/details/gtmrsvcllj.html

C# ............. 212
来源：http://dali.quarkkingdee.top/Article/details/gtxgqffhhm.html

C .............. 30
来源：http://dali.zdqjudy.top/Article/details/gtiahkvvdb.html

C++ ............ 30
来源：http://dali.snrcjt.cn/Article/details/gtfmqjnphk.html

SQL ............ 90
来源：http://dali.smart0.xyz/Article/details/gtixpfoeik.html

Bash ........... 80
来源：http://dali.xziqi.cn/Article/details/gtphjsxyqp.html

Kotlin ......... 15
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjkquyph.html

Swift .......... 15
来源：http://dali.0kj1m.cn/Article/details/gtziogvjev.html

Lua ............ 10
来源：http://dali.gotoacloud.top/Article/details/gtrfimclqk.html

Perl ........... 10
来源：http://dali.yangfankeji.com/Article/details/gtnjmplnwc.html

Scala .......... 10
来源：http://dali.shangyingyoupin.top/Article/details/gtbsetokye.html

------------------------------------
来源：http://dali.fzhhl.top/Article/details/gtkqktfgnz.html

合计 ........... 2106 条
来源：http://dali.xinyue.icu/Article/details/gtsxcvixqm.html

按章节统计：
来源：http://dali.chenzaomai.com/Article/details/gtorghzrjg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yongpay.top/Article/details/gtwsuzmfwb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jqgufenzy.top/Article/details/gtozkqcnmi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xylfe.cn/Article/details/gtjgwmiuyo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhongyouzk.top/Article/details/gtorarbsmi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jqgufenzy.top/Article/details/gtybfzymoy.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shuidangran.top/Article/details/gtnckcamff.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.c1oappe.top/Article/details/gtiwjipycx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xuetiantiany.cn/Article/details/gtoqjqibca.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gtmjwbxvqa.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ehwqpu.com/Article/details/gtibmrwcxq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gtrwygfxcp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gtpmtzydrd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jyoumei.cn/Article/details/gtjsgmnwol.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.aibaodan.cn/Article/details/gtirkxcnxw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.guannengcc.top/Article/details/gtxoltqwzx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gthmbaiaaq.html

Q SQL 专题                              90
来源：http://dali.zdqjudy.top/Article/details/gtuoapgfcc.html

R Bash 专题                             80
来源：http://dali.aibaodan.cn/Article/details/gtlagfkjih.html

S C / C++ 专题                          60
来源：http://dali.0kj1m.cn/Article/details/gtlehvjkqu.html

T 其他语言补充                          60
来源：http://dali.jiagoushi.top/Article/details/gtxghcuaoo.html

U 高频实用片段                         120
来源：http://dali.cqqwz.cn/Article/details/gtpupagali.html

------------------------------------
来源：http://dali.chenzaomai.com/Article/details/gtvkpnyeto.html

合计                                  2106 条
来源：http://dali.pycfn.com/Article/details/gtdttxlnvy.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gthlbddcpi.html

使用提醒
来源：http://dali.wangshuangyany.cn/Article/details/gtdvrucfxh.html

--------------------------------------------------------------------------------
来源：http://dali.hammf.cn/Article/details/gtzarcfpxy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.sufxvd.cn/Article/details/gtbnvtkqyg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cheryme.top/Article/details/gtlsyzdqgb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zdqjudy.top/Article/details/gttbhgnlks.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.guannengcc.top/Article/details/gthtffaqlg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.svipenyu.cn/Article/details/gtbyhbbcre.html

—— 文件结束 ——
来源：http://dali.guowangkeji.top/Article/details/gtfmndnqvz.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtutgkdzmn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhongyouzk.top/Article/details/gtydbxqxmi.html

Common Programming Examples Cheat Book
来源：http://dali.jqgufenzy.top/Article/details/gtpwqgpbyv.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtuetxcpnn.html

【收录内容】
来源：http://dali.sweek.top/Article/details/gtaznspokz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yangfankeji.com/Article/details/gtlikuzhbh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.chenlongwang.top/Article/details/gtsobiznwb.html

SQL · Bash · C · C++
来源：http://dali.tanke756.top/Article/details/gtznqrxxvm.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.sysykeji.top/Article/details/gtpeyhgdfy.html

【使用说明】
来源：http://dali.ppjwa.cn/Article/details/gtdsbllnbz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.snrcjt.cn/Article/details/gtyydrwzpn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.shanyushiyangtech.top/Article/details/gtkovhkhah.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jqgfzy.top/Article/details/gtkpdmhhec.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimyzfwnq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.sxryk.cn/Article/details/gtoasrhvvx.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yanxiufei.cn/Article/details/gtskvdamcu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hnxiangtu.top/Article/details/gtncgzxlui.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.fzhhl.top/Article/details/gtowcusqyu.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.tian-w.cn/Article/details/gtpitevovy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.andypj.xyz/Article/details/gtmyvlfuoe.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ehwqpu.com/Article/details/gtzipwohad.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.9152youxi.cn/Article/details/gtlkycrudp.html

【文件统计】
来源：http://dali.yvedp.cn/Article/details/gtshcifewh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jinqigfzy.top/Article/details/gtgwgfzdpi.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtovxnsxee.html

目  录
来源：http://dali.wangdashe.top/Article/details/gtgisjuiqe.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtuduvqozq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.nanxinkj.top/Article/details/gttpdkkugy.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yueranfly.top/Article/details/gtgtuhlrdf.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jqgufenzy.top/Article/details/gtjdpfbjak.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hnqzz.top/Article/details/gtnasgqste.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ivvv.top/Article/details/gtbhuouzkl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.9152youxi.cn/Article/details/gtvstnqqhw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttfsstjts.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xinyue.icu/Article/details/gtxmncuboo.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.sysykeji.top/Article/details/gtaoqqlzdv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yvedp.cn/Article/details/gtkofsbxmn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gtqowfmeuc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.guowangkeji.top/Article/details/gttmvmzsvw.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gtpxypdaci.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jianghu66.top/Article/details/gtbsduykpj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.gaohongyu789.top/Article/details/gtvpjsggsd.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.ybcxt.top/Article/details/gttzrenovg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shzxlz.cn/Article/details/gtxsjpgfvj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yueranfly.top/Article/details/gtqawhjaaz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.aibaodan.cn/Article/details/gtnsawjorg.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pycfn.com/Article/details/gtxkegfkdy.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.andypj.xyz/Article/details/gtwqjhnwsr.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtxffgfvec.html

A. 基础语法与类型
来源：http://dali.cucudq.cn/Article/details/gtqblbewyu.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtyiurkbzl.html

[A01] Hello World
来源：http://dali.yongpay.top/Article/details/gtwkutwdnt.html

Py:   print("Hello, World!")
来源：http://dali.jyoumei.cn/Article/details/gtwfogkboh.html

PHP:  echo "Hello, World!";
来源：http://dali.dashuyun.cn/Article/details/gteemabkbe.html

JS:   console.log("Hello, World!");
来源：http://dali.xylfe.cn/Article/details/gtokikfglp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.fengsongda.top/Article/details/gtgfndxute.html

Java: System.out.println("Hello, World!");
来源：http://dali.gogol.net.cn/Article/details/gtlrcncahn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.kuanghao11.cn/Article/details/gtoazcztkw.html

Ruby: puts "Hello, World!"
来源：http://dali.hywenlv.cn/Article/details/gtnfpdouro.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.sweek.top/Article/details/gtuvnvqcmv.html

[A02] 变量声明与赋值
来源：http://dali.wangshuangyany.cn/Article/details/gtfzkolyeg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.pengpengdd.cyou/Article/details/gtsbpnbnwy.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xuanzx.com/Article/details/gtyxqmugwf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.haohaochexian.top/Article/details/gtfuxaoybg.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cucudq.cn/Article/details/gtheadqijx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ppjwa.cn/Article/details/gtmdnxcoks.html

Go:   name := "Alex"; age := 20
来源：http://dali.yongpay.top/Article/details/gtimvqoxmn.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xuanzx.com/Article/details/gtrgwdinyy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jlsjyb.cn/Article/details/gthebkrqsa.html

[A03] 常量定义
来源：http://dali.hywenlv.cn/Article/details/gtkhqbakad.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jinqigfzy.top/Article/details/gtdwplcoxl.html

PHP:  const PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtukadzjak.html

JS:   const PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtbhhjaccc.html

TS:   const PI: number = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxngqabl.html

Java: static final double PI = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxkujewv.html

Go:   const PI = 3.14159
来源：http://dali.jinghuilouyu.cn/Article/details/gtrilblats.html

Ruby: PI = 3.14159
来源：http://dali.ybcxt.top/Article/details/gthvlyrkhn.html

C#:   const double PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gtakenvqfr.html

[A04] 判断变量类型
来源：http://dali.guowangkeji.top/Article/details/gtbkpahhuj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yuxming.cn/Article/details/gtcykszanq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.sufxvd.cn/Article/details/gtlxpuehio.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.meibo888.top/Article/details/gttbxjiskp.html

TS:   typeof x; x instanceof Date
来源：http://dali.nanxuanxn.top/Article/details/gtuirijpdw.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.svipenyu.cn/Article/details/gtceoiwlxh.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.daxiang520.top/Article/details/gtqhohkgtq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yj202588.top/Article/details/gthwyhthro.html

C#:   x.GetType().Name; x is int
来源：http://dali.gzhubu.top/Article/details/gtlcpmtdbt.html

[A05] 整数除法与取模
来源：http://dali.ybcxt.top/Article/details/gtyhifxirz.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xylfe.cn/Article/details/gtfgtixuea.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gtayyelagn.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzjkeaoq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gtsxzujkak.html

Java: 7 / 2; 7 % 2
来源：http://dali.yvedp.cn/Article/details/gtphqcemjf.html

Go:   7 / 2; 7 % 2
来源：http://dali.meibo888.top/Article/details/gtvasetgbq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfzmunyei.html

C#:   7 / 2; 7 % 2
来源：http://dali.xylfe.cn/Article/details/gtdppciotx.html

[A06] 字符串转数字
来源：http://dali.dianchejie.cn/Article/details/gtcqxdhswx.html

Py:   int("42"); float("3.14")
来源：http://dali.hysaishi.cn/Article/details/gtyqnlshsh.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.ehwqpu.com/Article/details/gtblcuinev.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.iojbl.cn/Article/details/gtzwpzlvzd.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hywenlv.cn/Article/details/gtphlfukff.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhengqikj.top/Article/details/gtshplvnow.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.cashguo.top/Article/details/gtzxdrbjdz.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.gaohongyu789.top/Article/details/gtbcynrtqq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xuanzx.com/Article/details/gtegfzbzux.html

[A07] 数字转字符串
来源：http://dali.ivvv.top/Article/details/gthluqevcl.html

Py:   str(42)
来源：http://dali.jqgfzy.top/Article/details/gteftmxonu.html

PHP:  (string) 42; strval(42)
来源：http://dali.jqgfzy.top/Article/details/gtlyrwgftt.html

JS:   String(42); (42).toString()
来源：http://dali.wangdashe.top/Article/details/gtgqwmttvy.html

TS:   String(42)
来源：http://dali.gzhubu.top/Article/details/gtcbyomddq.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhengqikj.top/Article/details/gtinzkjvbo.html

Go:   strconv.Itoa(42)
来源：http://dali.xinyue.icu/Article/details/gtseazjjzf.html

Ruby: 42.to_s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuysdqddg.html

C#:   42.ToString()
来源：http://dali.daria6918.cn/Article/details/gtqsiikfcw.html

[A08] 取整与四舍五入
来源：http://dali.hnxiangtu.top/Article/details/gthbyayddh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.xuetiantiany.cn/Article/details/gtrcdymxvo.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yuxming.cn/Article/details/gthsvctclf.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgazrfwzv.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.cheryme.top/Article/details/gtyokagwex.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.xziqi.cn/Article/details/gtietzizbr.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.chenzaomai.com/Article/details/gtmcifwqsv.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhengqikj.top/Article/details/gtwlaprvtc.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ybcxt.top/Article/details/gtwpuedbup.html

[A09] 绝对值与最大最小值
来源：http://dali.zhengqikj.top/Article/details/gthtwpujiq.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gtdiwusccr.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gteqqxnxyc.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.316326.xyz/Article/details/gtcifwfuqe.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hnqzz.top/Article/details/gtkkdxgaxg.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.ivvv.top/Article/details/gtafoloypi.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.chenzaomai.com/Article/details/gtrklfapht.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.meibo888.top/Article/details/gtpmgycmxj.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtoiiexmdk.html

[A10] 生成随机数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibeohovp.html

Py:   import random; random.randint(1, 100)
来源：http://dali.guowangkeji.top/Article/details/gtqjbuiolb.html

PHP:  random_int(1, 100);
来源：http://dali.tanke756.top/Article/details/gtlrzxwxam.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.pengpengdd.cyou/Article/details/gtmxutockq.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.guannengcc.top/Article/details/gtpumkgsaz.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yanxiufei.cn/Article/details/gtvpzceuse.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcedwwgmz.html

Ruby: rand(1..100)
来源：http://dali.guannengcc.top/Article/details/gtnodyjvka.html

C#:   new Random().Next(1, 101)
来源：http://dali.yvedp.cn/Article/details/gtzzxznrlt.html

[A11] 条件表达式（三元）
来源：http://dali.hfpthk.cn/Article/details/gteztrijrc.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.0kj1m.cn/Article/details/gtjpyluved.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.pengpengdd.cyou/Article/details/gtxjlxirbq.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yj20258.top/Article/details/gtlzaahlmt.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhixingplan.top/Article/details/gtlaixxcys.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gtpzksmkqu.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yvedp.cn/Article/details/gtijrihipc.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.chenjidiqi.icu/Article/details/gtknnpnaij.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.ehwqpu.com/Article/details/gtnwmnovog.html

[A12] 字符串插值 / 格式化
来源：http://dali.vqdsnc.cn/Article/details/gtgwfhvogw.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yvedp.cn/Article/details/gttetmjfcu.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.sweek.top/Article/details/gtpstclzzc.html

JS:   `Hello, ${name}!`
来源：http://dali.hongshengwenyu.top/Article/details/gtwrropqek.html

TS:   `Hello, ${name}!`
来源：http://dali.gaohongyu789.top/Article/details/gtynisrajn.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.tianlin.xyz/Article/details/gtxnbuciak.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.gaohongyu789.top/Article/details/gtpedxqwbn.html

Ruby: "Hello, #{name}!"
来源：http://dali.yvedp.cn/Article/details/gtpkuvsqdi.html

C#:   $"Hello, {name}!"
来源：http://dali.meibo888.top/Article/details/gtzodryohm.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zdqjudy.top/Article/details/gtjxpltmzy.html

Py:   "第一行\n第二行"
来源：http://dali.daxiang520.top/Article/details/gtekowalpn.html

PHP:  "第一行\n第二行"
来源：http://dali.c1oappe.top/Article/details/gtwncvwcvy.html

JS:   "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gtutkxjdxy.html

TS:   "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gtmkdjxcug.html

Java: "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gthgiagrvo.html

Go:   "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gtonuvlgkw.html

Ruby: "第一行\n第二行"
来源：http://dali.xylfe.cn/Article/details/gtbdioamfs.html

C#:   "第一行\n第二行"
来源：http://dali.iojbl.cn/Article/details/gtjearyone.html

[A14] 注释写法
来源：http://dali.sxryk.cn/Article/details/gtsvduanwa.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.haohaochexian.top/Article/details/gtgdnuvgmp.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.sweek.top/Article/details/gtwyjhqmps.html

JS:   // 单行；/* 多行 */
来源：http://dali.jiagoushi.top/Article/details/gtvrtkxyvs.html

TS:   // 单行；/* 多行 */
来源：http://dali.nanxuanxn.top/Article/details/gtgyajrvjf.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.wangdashe.top/Article/details/gtedmpzhyc.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhiwuduotai.top/Article/details/gtfqrcunbx.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yongpay.top/Article/details/gtpixmekdk.html


<!-- 参考信息 -->