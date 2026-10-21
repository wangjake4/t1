代发 wailian999

[U89] JS：数组去重
来源：http://dali.sxryk.cn/Article/details/gthfbnwihv.html

[...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gtqwgewauy.html

[U90] JS：数字数组排序
来源：http://dali.ivvv.top/Article/details/gtmacpgbfc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghluigkx.html

[U91] JS：对象键值遍历
来源：http://dali.nanxuanxn.top/Article/details/gtjnrivhrh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xuetiantiany.cn/Article/details/gtboefnjkf.html

[U92] JS：深拷贝
来源：http://dali.zhongyouzk.top/Article/details/gtbbrgxgdb.html

structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gtxmusgxrc.html

[U93] JS：模板字符串
来源：http://dali.meibo888.top/Article/details/gtqqaxvhnq.html

`共 ${n} 条`
来源：http://dali.yuanzhike.top/Article/details/gtakoyuiar.html

[U94] JS：箭头函数
来源：http://dali.nanxuanxn.top/Article/details/gtlzhfwgtc.html

const double = x => x * 2;
来源：http://dali.sysykeji.top/Article/details/gtsqltizjf.html

[U95] JS：Promise 包装
来源：http://dali.shuidangran.top/Article/details/gtntvljljq.html

new Promise((resolve, reject) => {})
来源：http://dali.0kj1m.cn/Article/details/gtqjvgxrkj.html

[U96] JS：async/await 与异常
来源：http://dali.jlsjyb.cn/Article/details/gttzrcitpo.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gthmalipby.html

[U97] JS：并发请求
来源：http://dali.hongshengwenyu.top/Article/details/gtievkcsez.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gtijmhaqye.html

[U98] JS：fetch 带 JSON
来源：http://dali.yonumen.top/Article/details/gtxysgnlja.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zdqjudy.top/Article/details/gtwynetchn.html

[U99] JS：事件监听
来源：http://dali.kuanghao11.cn/Article/details/gtvwyjeaxh.html

el.addEventListener("click", e => {})
来源：http://dali.mhx1999.top/Article/details/gthaoalhjt.html

[U100] JS：DOM 查询
来源：http://dali.c1oappe.top/Article/details/gttpablstx.html

document.querySelector(".item")
来源：http://dali.jqgfzy.top/Article/details/gtrnrpcdef.html

[U101] JS：classList 操作
来源：http://dali.hnxiangtu.top/Article/details/gtenzkxytn.html

el.classList.toggle("active")
来源：http://dali.fzhhl.top/Article/details/gtwxgtcftn.html

[U102] JS：本地存储
来源：http://dali.yvedp.cn/Article/details/gtijakksul.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.redwolf501.top/Article/details/gtjlhwdtzr.html

[U103] JS：定时器
来源：http://dali.sysykeji.top/Article/details/gtudjsnrta.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.wangshuangyany.cn/Article/details/gtfhostkky.html

[U104] JS：防抖
来源：http://dali.gaohongyu789.top/Article/details/gtpxwtwqeq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ivvv.top/Article/details/gtayrykbor.html

[U105] JS：节流
来源：http://dali.tianlin.xyz/Article/details/gtgfkithca.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.fengsongda.top/Article/details/gtrgepvcld.html

[U106] JS：日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gtpexcjmix.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhixingplan.top/Article/details/gtbxrlhkqh.html

[U107] JS：数字千分位
来源：http://dali.jinqigufen.top/Article/details/gtyeohrljg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gtgwpfhjyj.html

[U108] JS：随机整数
来源：http://dali.zycfv.cn/Article/details/gtrhlpeekq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.pycfn.com/Article/details/gtkpyhjrwi.html

[U109] JS：数组分组
来源：http://dali.gzhubu.top/Article/details/gtmtoiqubb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gthvbtywzx.html

[U110] JS：数组分块
来源：http://dali.yvedp.cn/Article/details/gtogryjpoi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cucudq.cn/Article/details/gtgofwjwgr.html

[U111] JS：对象转 Map
来源：http://dali.smart0.xyz/Article/details/gtvtpzxgll.html

new Map(Object.entries(obj))
来源：http://dali.wangdashe.top/Article/details/gtsbupomte.html

[U112] JS：字符串补位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzaljboz.html

"7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gtipblpwgr.html

[U113] JS：正则替换全部
来源：http://dali.dashuyun.cn/Article/details/gthdzygmbu.html

s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtxtxqqere.html

[U114] JS：JSON 深比较
来源：http://dali.xuanzx.com/Article/details/gtflddksyl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.birdmap.top/Article/details/gtrajkemqr.html

[U115] JS：生成 UUID
来源：http://dali.zhiwuduotai.top/Article/details/gtyfutlzzn.html

crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gtroazfqko.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.meibo888.top/Article/details/gtlevsbprk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.nanxuanxn.top/Article/details/gtmpqernul.html

[U117] JS：单元测试
来源：http://dali.cdnleiting.top/Article/details/gtixsfmemf.html

npm i -D vitest;  npx vitest
来源：http://dali.xuanzx.com/Article/details/gtchyfrbwu.html

[U118] JS：开发服务器
来源：http://dali.xziqi.cn/Article/details/gtnrqcroxa.html

npm i -D vite;  npx vite
来源：http://dali.gaohongyu789.top/Article/details/gtqusjnffs.html

[U119] JS：生产构建
来源：http://dali.chenjidiqi.icu/Article/details/gtxlqyvvrx.html

npx vite build
来源：http://dali.gotoacloud.top/Article/details/gtxqkwcdkc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.guannengcc.top/Article/details/gtwxnjxolp.html

import.meta.env.VITE_API_URL
来源：http://dali.meibo888.top/Article/details/gtyzsydagf.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtqgpsxhnc.html

统计汇总
来源：http://dali.jyoumei.cn/Article/details/gtdappshwu.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtvhepcmit.html

按语言统计（条）：
来源：http://dali.tanke756.top/Article/details/gtcagwqnfu.html

Python ......... 252
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteyecjwfp.html

PHP ............ 252
来源：http://dali.hammf.cn/Article/details/gtqqokvvxd.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gtyfotgfom.html

TypeScript ..... 212
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqzeunny.html

Java ........... 212
来源：http://dali.snrcjt.cn/Article/details/gtkrjilolk.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gtxerctvfy.html

Ruby ........... 212
来源：http://dali.ivvv.top/Article/details/gttbsqxmnc.html

C# ............. 212
来源：http://dali.smart0.xyz/Article/details/gtrwqxxujp.html

C .............. 30
来源：http://dali.yueranfly.top/Article/details/gtokjgedny.html

C++ ............ 30
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikaehdun.html

SQL ............ 90
来源：http://dali.nwbrower.top/Article/details/gtooqmplmj.html

Bash ........... 80
来源：http://dali.9152youxi.cn/Article/details/gtiugmujja.html

Kotlin ......... 15
来源：http://dali.yongpay.top/Article/details/gtsfewkccy.html

Swift .......... 15
来源：http://dali.xylfe.cn/Article/details/gtdkivfvuz.html

Lua ............ 10
来源：http://dali.fzhhl.top/Article/details/gteywikeek.html

Perl ........... 10
来源：http://dali.jqgufenzy.top/Article/details/gtorcdelcr.html

Scala .......... 10
来源：http://dali.yueranfly.top/Article/details/gtwzlbyirm.html

------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gtwyaetczo.html

合计 ........... 2106 条
来源：http://dali.hfpthk.cn/Article/details/gthrzbcmon.html

按章节统计：
来源：http://dali.feifeiyinyue.top/Article/details/gtkmvocvyl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hfpthk.cn/Article/details/gtwhibgjmj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xziqi.cn/Article/details/gttvbxqwvz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ivvv.top/Article/details/gtdpxjwile.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yangfankeji.com/Article/details/gtrckpcngz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.smart0.xyz/Article/details/gtpryuqzmr.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yj20258888.top/Article/details/gtrzckzvhk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ehwqpu.com/Article/details/gtbpoofzqr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cdnleiting.top/Article/details/gtxuzyjsaf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gtgjadrbwi.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yangfankeji.com/Article/details/gtdmqxigfc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gtubkkqdfb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gtudvnhfdx.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gtfzeygwxr.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jinghuilouyu.cn/Article/details/gtzveyieeu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cdnleiting.top/Article/details/gtjcuwrqui.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gtkasccqli.html

Q SQL 专题                              90
来源：http://dali.pengpengdd.cyou/Article/details/gtidqznljv.html

R Bash 专题                             80
来源：http://dali.haohaochexian.top/Article/details/gtubadujom.html

S C / C++ 专题                          60
来源：http://dali.0kj1m.cn/Article/details/gtemkhdoxz.html

T 其他语言补充                          60
来源：http://dali.kuanghao11.cn/Article/details/gtvgehocuf.html

U 高频实用片段                         120
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmspinnh.html

------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gthruqwabo.html

合计                                  2106 条
来源：http://dali.chenlongwang.top/Article/details/gtilvullxd.html

--------------------------------------------------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gtwghhuzwn.html

使用提醒
来源：http://dali.shuidangran.top/Article/details/gtugwkghvs.html

--------------------------------------------------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gtxuzblzbh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cheryme.top/Article/details/gtzwdwhxiv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hnxiangtu.top/Article/details/gtsnkslhxq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.smart0.xyz/Article/details/gtafaljuda.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.daria6918.cn/Article/details/gtwizcwkjk.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hfpthk.cn/Article/details/gteqgcfrla.html

—— 文件结束 ——
来源：http://dali.jyoumei.cn/Article/details/gtdfzodpod.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtglbxhrud.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jinqigufen.top/Article/details/gttuwkdbgq.html

Common Programming Examples Cheat Book
来源：http://dali.ydzc1.top/Article/details/gthowfzddv.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtsteqnurs.html

【收录内容】
来源：http://dali.yuxming.cn/Article/details/gttlwviijw.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jqgfzy.top/Article/details/gtpkoawjsf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.c1oappe.top/Article/details/gtsvokqphj.html

SQL · Bash · C · C++
来源：http://dali.sweek.top/Article/details/gtpatlspoa.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.sweek.top/Article/details/gtqytxhrmk.html

【使用说明】
来源：http://dali.kuanghao11.cn/Article/details/gtmonocppg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yangfankeji.com/Article/details/gtfnzhixgv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.kuanghao11.cn/Article/details/gtrgoothik.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yonumen.top/Article/details/gtkumgztsy.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.feifeiyinyue.top/Article/details/gtomiazmrd.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.redwolf501.top/Article/details/gtmuxqiskl.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zdqjudy.top/Article/details/gtyqkhwhej.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jlsjyb.cn/Article/details/gtcflfoscg.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yuxming.cn/Article/details/gtefxkwivn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yanxiufei.cn/Article/details/gtjkfctrae.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.daxiang520.top/Article/details/gtfqcsxpzv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.mhx1999.top/Article/details/gtdkwvoold.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.fengsongda.top/Article/details/gtalrmjiqr.html

【文件统计】
来源：http://dali.jinqigufen.top/Article/details/gtjfzpqoka.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yonumen.top/Article/details/gtkyajptvm.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtergplpnz.html

目  录
来源：http://dali.xylfe.cn/Article/details/gtmawtjkts.html

--------------------------------------------------------------------------------
来源：http://dali.sysykeji.top/Article/details/gtvhgpatta.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jinqigufen.top/Article/details/gtxluwcnrt.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvtrawoze.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jinqigufen.top/Article/details/gtvwdpdybe.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtycjzetni.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtotsocgcg.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.mhx1999.top/Article/details/gtkrukabex.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.bjfxy.top/Article/details/gtieqqbrel.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.bjfxy.top/Article/details/gtbjqngycr.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gtyogfdwqk.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gtpndjebqn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.0kj1m.cn/Article/details/gtyiytoxfi.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gtohavmopn.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cashguo.top/Article/details/gtcavnxdhd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.daria6918.cn/Article/details/gtyzykqeti.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.cucudq.cn/Article/details/gtamulytrn.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.tanke756.top/Article/details/gtactvjdte.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtojtoxmgj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.smart0.xyz/Article/details/gteobquesu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jiagoushi.top/Article/details/gtukttkxco.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgufenzy.top/Article/details/gtydmhtvvx.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenzaomai.com/Article/details/gtprghwzfj.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtgtxmvshd.html

A. 基础语法与类型
来源：http://dali.jinqigfzy.top/Article/details/gtimfpenzo.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtcumxopqm.html

[A01] Hello World
来源：http://dali.316326.xyz/Article/details/gtvpataxxu.html

Py:   print("Hello, World!")
来源：http://dali.shangyingyoupin.top/Article/details/gtmpgbxtng.html

PHP:  echo "Hello, World!";
来源：http://dali.redwolf501.top/Article/details/gtxbkgzxqf.html

JS:   console.log("Hello, World!");
来源：http://dali.shanyushiyangtech.top/Article/details/gtqcymdxol.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.guowangkeji.top/Article/details/gtnkrmsrtu.html

Java: System.out.println("Hello, World!");
来源：http://dali.smart0.xyz/Article/details/gtxfdoafjq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.snrcjt.cn/Article/details/gticlffgmy.html

Ruby: puts "Hello, World!"
来源：http://dali.yueranfly.top/Article/details/gtqzqgolnf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.pycfn.com/Article/details/gtzpvqyvjx.html

[A02] 变量声明与赋值
来源：http://dali.aizwys.cn/Article/details/gtbsyzecrc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.0kj1m.cn/Article/details/gtrjabkhrx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jqgufenzy.top/Article/details/gtmljnxqmw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yj202588.top/Article/details/gtegbliyyi.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.aibaodan.cn/Article/details/gtwyybhqjs.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yangfankeji.com/Article/details/gtrwsowctu.html

Go:   name := "Alex"; age := 20
来源：http://dali.jyoumei.cn/Article/details/gtbcbdfszf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.wangdashe.top/Article/details/gtwzcvddvi.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.9152youxi.cn/Article/details/gtzmcvllgk.html

[A03] 常量定义
来源：http://dali.xinyue.icu/Article/details/gtxuzmxgle.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.xylfe.cn/Article/details/gtemmnqpip.html

PHP:  const PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gttwivitbu.html

JS:   const PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gttfptqnof.html

TS:   const PI: number = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gtmipdfzpe.html

Java: static final double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtlwwfbsek.html

Go:   const PI = 3.14159
来源：http://dali.xziqi.cn/Article/details/gtgekblapm.html

Ruby: PI = 3.14159
来源：http://dali.iojbl.cn/Article/details/gtssqzwzzi.html

C#:   const double PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtldfvxxdr.html

[A04] 判断变量类型
来源：http://dali.birdmap.top/Article/details/gteaowuavy.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ppjwa.cn/Article/details/gtunhulvkb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.meibo888.top/Article/details/gttocvgbgx.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjfdpusb.html

TS:   typeof x; x instanceof Date
来源：http://dali.cheryme.top/Article/details/gtqfnfbvbr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.nanxuanxn.top/Article/details/gtebncaeoy.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.316326.xyz/Article/details/gtxohmhmcc.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xziqi.cn/Article/details/gtdnvwccdc.html

C#:   x.GetType().Name; x is int
来源：http://dali.jinqigufen.top/Article/details/gtxsvhydag.html

[A05] 整数除法与取模
来源：http://dali.aibaodan.cn/Article/details/gtmbehxycw.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhixingplan.top/Article/details/gtiderzhnt.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtcfgthnqs.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtpweqnxbm.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.haohaochexian.top/Article/details/gtlwxgwzuo.html

Java: 7 / 2; 7 % 2
来源：http://dali.ydzc1.top/Article/details/gtqqxitkwv.html

Go:   7 / 2; 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gtcnhvmolz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.pycfn.com/Article/details/gtylrbppgl.html

C#:   7 / 2; 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnizijkth.html

[A06] 字符串转数字
来源：http://dali.tian-w.cn/Article/details/gthfpysrox.html

Py:   int("42"); float("3.14")
来源：http://dali.cheryme.top/Article/details/gtxaltbbad.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yvedp.cn/Article/details/gttmegkcdx.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdufibtd.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.andypj.xyz/Article/details/gtbqclpfcc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjvvnqqn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yueranfly.top/Article/details/gtkyjfsoyd.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwaeepnks.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.chenlongwang.top/Article/details/gtyzmquien.html

[A07] 数字转字符串
来源：http://dali.sweek.top/Article/details/gtxeojixxm.html

Py:   str(42)
来源：http://dali.shuidangran.top/Article/details/gtdgvoesqi.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhongyouzk.top/Article/details/gtgbrypcvc.html

JS:   String(42); (42).toString()
来源：http://dali.chenzaomai.com/Article/details/gtzlvwpuwc.html

TS:   String(42)
来源：http://dali.zycfv.cn/Article/details/gtwliecnfh.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhongyouzk.top/Article/details/gtbtqyvocq.html

Go:   strconv.Itoa(42)
来源：http://dali.kuanghao11.cn/Article/details/gtesmktbur.html

Ruby: 42.to_s
来源：http://dali.fengsongda.top/Article/details/gtbuegixmy.html

C#:   42.ToString()
来源：http://dali.andypj.xyz/Article/details/gtpmgzjwqg.html

[A08] 取整与四舍五入
来源：http://dali.havefunace.top/Article/details/gtkllynuly.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhixingplan.top/Article/details/gttvzkrjoo.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhixingplan.top/Article/details/gthxrmzxlj.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhixingplan.top/Article/details/gtkxzpatwh.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hnqzz.top/Article/details/gttmcvcvnt.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.gotoacloud.top/Article/details/gtxwdlamhc.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.ybcxt.top/Article/details/gttpmjwgzj.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.birdmap.top/Article/details/gtukeezboj.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yuanzhike.top/Article/details/gthrlrhxeo.html

[A09] 绝对值与最大最小值
来源：http://dali.svipenyu.cn/Article/details/gttpdjzgyu.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gtwynkxtyk.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gtaqifkjzu.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hnqzz.top/Article/details/gthnbavkgg.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtbiihwcpb.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtofarovsp.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhppvdsl.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yvedp.cn/Article/details/gtbxqkmfik.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.aizwys.cn/Article/details/gticbruspk.html

[A10] 生成随机数
来源：http://dali.daria6918.cn/Article/details/gtfqeuupcs.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhongyouzk.top/Article/details/gtmnwbesuo.html

PHP:  random_int(1, 100);
来源：http://dali.pycfn.com/Article/details/gtfsbtczxi.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yongpay.top/Article/details/gtnhqbhptp.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xylfe.cn/Article/details/gtnpvwpryn.html

Java: new Random().nextInt(100) + 1
来源：http://dali.tanke756.top/Article/details/gtggmwpvfc.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.guannengcc.top/Article/details/gtlirajgfb.html

Ruby: rand(1..100)
来源：http://dali.aibaodan.cn/Article/details/gtmmapbksm.html

C#:   new Random().Next(1, 101)
来源：http://dali.pengpengdd.cyou/Article/details/gtlqhklwsu.html

[A11] 条件表达式（三元）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwsrwubdh.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.wangshuangyany.cn/Article/details/gtuytmgata.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hnqzz.top/Article/details/gttvxzlbrz.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.xinyue.icu/Article/details/gtvhibheev.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.fengsongda.top/Article/details/gtvbygnyoo.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.svipenyu.cn/Article/details/gtamsjomts.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzmeudtm.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhiwuduotai.top/Article/details/gtyilawbtx.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.hfpthk.cn/Article/details/gtlwbjshfq.html

[A12] 字符串插值 / 格式化
来源：http://dali.yj202588.top/Article/details/gtvqyfkcxg.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.sweek.top/Article/details/gtqmzqkubn.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.kuanghao11.cn/Article/details/gtvvjetiof.html

JS:   `Hello, ${name}!`
来源：http://dali.svipenyu.cn/Article/details/gtvnbywdrj.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gtfkjdmddd.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.9152youxi.cn/Article/details/gtcqgpaxsb.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.hnxiangtu.top/Article/details/gtiqhpcfqu.html

Ruby: "Hello, #{name}!"
来源：http://dali.fzhhl.top/Article/details/gtbcppfjgo.html

C#:   $"Hello, {name}!"
来源：http://dali.hongshengwenyu.top/Article/details/gtrawbemne.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.hnxiangtu.top/Article/details/gtjhwqbiaj.html

Py:   "第一行\n第二行"
来源：http://dali.ivvv.top/Article/details/gtimrhabdz.html

PHP:  "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gtludvobol.html

JS:   "第一行\n第二行"
来源：http://dali.hysaishi.cn/Article/details/gtpxfowdpv.html

TS:   "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gtiyhotmrg.html

Java: "第一行\n第二行"
来源：http://dali.tianlin.xyz/Article/details/gtjaaufofq.html

Go:   "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmywhmyip.html

Ruby: "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gtoqmfvxiw.html

C#:   "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gtztxzgiiy.html

[A14] 注释写法
来源：http://dali.xuetiantiany.cn/Article/details/gtjyvacoot.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.hammf.cn/Article/details/gtixtghzhw.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yongpay.top/Article/details/gtmtaashzh.html

JS:   // 单行；/* 多行 */
来源：http://dali.guannengcc.top/Article/details/gtqlwgilyh.html

TS:   // 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gtzcnzzzmh.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.sxryk.cn/Article/details/gtgrtpcjlg.html

Go:   // 单行；/* 多行 */
来源：http://dali.316326.xyz/Article/details/gtacwrybfa.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hywenlv.cn/Article/details/gtepfsptns.html

C#:   // 单行；/* 多行 */
来源：http://dali.cucudq.cn/Article/details/gtjgvowyxj.html

[A15] 空值判断与默认值
来源：http://dali.jianghu66.top/Article/details/gtabahakjn.html

Py:   value = data or "默认值"
来源：http://dali.jyoumei.cn/Article/details/gtaasukwqp.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.xuetiantiany.cn/Article/details/gtqyzkqzxf.html


<!-- 参考信息 -->