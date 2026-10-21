代发 wailian999

[U95] JS：Promise 包装
来源：http://dali.shangyingyoupin.top/Article/details/gtfznvmzbj.html

new Promise((resolve, reject) => {})
来源：http://dali.daria6918.cn/Article/details/gtowsmffst.html

[U96] JS：async/await 与异常
来源：http://dali.shuidangran.top/Article/details/gtubbwixer.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtotqxxezn.html

[U97] JS：并发请求
来源：http://dali.vqdsnc.cn/Article/details/gttklseezq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtjphkggea.html

[U98] JS：fetch 带 JSON
来源：http://dali.xziqi.cn/Article/details/gtvprmphna.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gthigtuzox.html

[U99] JS：事件监听
来源：http://dali.yj202588.top/Article/details/gtgwmsdcys.html

el.addEventListener("click", e => {})
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjnsijrj.html

[U100] JS：DOM 查询
来源：http://dali.smart0.xyz/Article/details/gtgiexjtso.html

document.querySelector(".item")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqnmpwts.html

[U101] JS：classList 操作
来源：http://dali.nanxinkj.top/Article/details/gtzoougoye.html

el.classList.toggle("active")
来源：http://dali.hysaishi.cn/Article/details/gtciqdyowp.html

[U102] JS：本地存储
来源：http://dali.9152youxi.cn/Article/details/gtuffsjmpf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.0kj1m.cn/Article/details/gtduteqrkt.html

[U103] JS：定时器
来源：http://dali.tianlin.xyz/Article/details/gtnihnxbcm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.tianlin.xyz/Article/details/gtplukkjxf.html

[U104] JS：防抖
来源：http://dali.nanxinkj.top/Article/details/gtjuwyiisq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangshuangyany.cn/Article/details/gtnekyairq.html

[U105] JS：节流
来源：http://dali.quarkkingdee.top/Article/details/gtnmcgrjxd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hysaishi.cn/Article/details/gtnqamicsi.html

[U106] JS：日期格式化
来源：http://dali.xuanzx.com/Article/details/gtzofnrgtv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhongyouzk.top/Article/details/gtwoivjziw.html

[U107] JS：数字千分位
来源：http://dali.yj20258888.top/Article/details/gtoqnlwycn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhongyouzk.top/Article/details/gtjyuiniwb.html

[U108] JS：随机整数
来源：http://dali.yuxming.cn/Article/details/gtfibtnqox.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhixingplan.top/Article/details/gtogltennb.html

[U109] JS：数组分组
来源：http://dali.hammf.cn/Article/details/gtjfvwowhh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.nwbrower.top/Article/details/gtlsaqjmci.html

[U110] JS：数组分块
来源：http://dali.ivvv.top/Article/details/gtaiupnrvo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.tanke756.top/Article/details/gtliiwkajb.html

[U111] JS：对象转 Map
来源：http://dali.shangyingyoupin.top/Article/details/gtpapepewj.html

new Map(Object.entries(obj))
来源：http://dali.zdqjudy.top/Article/details/gtbgtfkibc.html

[U112] JS：字符串补位
来源：http://dali.guannengcc.top/Article/details/gthbetlzfr.html

"7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gtfkeuugbb.html

[U113] JS：正则替换全部
来源：http://dali.zhongyouzk.top/Article/details/gtfbqimvuh.html

s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtmmzjkilv.html

[U114] JS：JSON 深比较
来源：http://dali.dianchejie.cn/Article/details/gtvbosztsd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yongpay.top/Article/details/gtxpgutoof.html

[U115] JS：生成 UUID
来源：http://dali.haohaochexian.top/Article/details/gtxwgjylta.html

crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gttocgbtlt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yj20258888.top/Article/details/gtobxxstbh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gthqmzxyzr.html

[U117] JS：单元测试
来源：http://dali.yanxiufei.cn/Article/details/gtayhgebrk.html

npm i -D vitest;  npx vitest
来源：http://dali.yanxiufei.cn/Article/details/gtvuouycfy.html

[U118] JS：开发服务器
来源：http://dali.hnqzz.top/Article/details/gtcnliuwmi.html

npm i -D vite;  npx vite
来源：http://dali.andypj.xyz/Article/details/gtxeqppmfq.html

[U119] JS：生产构建
来源：http://dali.aizwys.cn/Article/details/gtdhyudrcm.html

npx vite build
来源：http://dali.hfpthk.cn/Article/details/gtvbjocctc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jianghu66.top/Article/details/gtxmgawdni.html

import.meta.env.VITE_API_URL
来源：http://dali.nwbrower.top/Article/details/gtcbaqxvfp.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtowvzhwrp.html

统计汇总
来源：http://dali.mhx1999.top/Article/details/gtowmsoapd.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtcszpxvqw.html

按语言统计（条）：
来源：http://dali.bjfxy.top/Article/details/gtgtdxaqwn.html

Python ......... 252
来源：http://dali.gaohongyu789.top/Article/details/gtfaeoesix.html

PHP ............ 252
来源：http://dali.quarkkingdee.top/Article/details/gthnwazgkp.html

JavaScript ..... 252
来源：http://dali.zycfv.cn/Article/details/gtvyoiuedd.html

TypeScript ..... 212
来源：http://dali.hammf.cn/Article/details/gtrdyyceam.html

Java ........... 212
来源：http://dali.zycfv.cn/Article/details/gtcihatztq.html

Go ............. 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjfccnat.html

Ruby ........... 212
来源：http://dali.0kj1m.cn/Article/details/gtwddaqqsp.html

C# ............. 212
来源：http://dali.jiagoushi.top/Article/details/gtirnayztw.html

C .............. 30
来源：http://dali.kuanghao11.cn/Article/details/gtzemxamii.html

C++ ............ 30
来源：http://dali.0kj1m.cn/Article/details/gtypbhkker.html

SQL ............ 90
来源：http://dali.zhoulong.xyz/Article/details/gtndnyjmfq.html

Bash ........... 80
来源：http://dali.yuanzhike.top/Article/details/gtlhkctmhg.html

Kotlin ......... 15
来源：http://dali.yvedp.cn/Article/details/gtccixvfyh.html

Swift .......... 15
来源：http://dali.dianchejie.cn/Article/details/gtjkdnkqes.html

Lua ............ 10
来源：http://dali.tian-w.cn/Article/details/gtykuanatq.html

Perl ........... 10
来源：http://dali.shzxlz.cn/Article/details/gtwxexzbgj.html

Scala .......... 10
来源：http://dali.9152youxi.cn/Article/details/gtjznrpjjs.html

------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gtmyeeyswk.html

合计 ........... 2106 条
来源：http://dali.zhiwuduotai.top/Article/details/gtfpmcxgmw.html

按章节统计：
来源：http://dali.snrcjt.cn/Article/details/gtmxsriuuj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tanke756.top/Article/details/gtqrravalm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.c1oappe.top/Article/details/gtkmpjlfit.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhongyouzk.top/Article/details/gtatomnyop.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yanxiufei.cn/Article/details/gtkddrmuqa.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhengqikj.top/Article/details/gtladavhrl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.316326.xyz/Article/details/gtbojbrpbq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xuanzx.com/Article/details/gtfrhrpebe.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jyoumei.cn/Article/details/gtcqzdledc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gtzuvwkqvz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.mhx1999.top/Article/details/gtnauzuerc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gtmcpgkcpg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gtrqbybgor.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gtrzcgnvns.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.aibaodan.cn/Article/details/gtrbldmzyq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hnqzz.top/Article/details/gtjxmdrczm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gtrgciliob.html

Q SQL 专题                              90
来源：http://dali.xziqi.cn/Article/details/gtswjaufld.html

R Bash 专题                             80
来源：http://dali.wangshuangyany.cn/Article/details/gtmsgzxuvs.html

S C / C++ 专题                          60
来源：http://dali.andypj.xyz/Article/details/gtqpopkdam.html

T 其他语言补充                          60
来源：http://dali.yj202588.top/Article/details/gtceqtljlh.html

U 高频实用片段                         120
来源：http://dali.jyoumei.cn/Article/details/gtdeguympa.html

------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtwamegqvk.html

合计                                  2106 条
来源：http://dali.cucudq.cn/Article/details/gtcoeabsmd.html

--------------------------------------------------------------------------------
来源：http://dali.chenzaomai.com/Article/details/gttdsbjqar.html

使用提醒
来源：http://dali.jiagoushi.top/Article/details/gtdrqpubpf.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxfymsyw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.nwbrower.top/Article/details/gtjzkzhuro.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.sufxvd.cn/Article/details/gtqoefqtzy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yj20258.top/Article/details/gthbqprjvf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.bjfxy.top/Article/details/gtauvvvnlj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yj202588.top/Article/details/gtzusdjhmh.html

—— 文件结束 ——
来源：http://dali.nanxinkj.top/Article/details/gthfizoppp.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtsxazbupy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jinqigufen.top/Article/details/gtlahyatjy.html

Common Programming Examples Cheat Book
来源：http://dali.hywenlv.cn/Article/details/gtguhsarqi.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtoildjkgi.html

【收录内容】
来源：http://dali.316326.xyz/Article/details/gtiwrsrarv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yvedp.cn/Article/details/gtuvdwhmpr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.9152youxi.cn/Article/details/gtqdrjwrvp.html

SQL · Bash · C · C++
来源：http://dali.aibaodan.cn/Article/details/gtzlznegoo.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ppjwa.cn/Article/details/gttzrwzaup.html

【使用说明】
来源：http://dali.hnqzz.top/Article/details/gtttpynfvq.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.quarkkingdee.top/Article/details/gtcbjyktqs.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.chenjidiqi.icu/Article/details/gtcspqtuee.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.chenjidiqi.icu/Article/details/gtfvgbhqey.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.mhx1999.top/Article/details/gtearykdsq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hnxiangtu.top/Article/details/gthhsenska.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzhmyvbe.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jinqigufen.top/Article/details/gtkitdxywt.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiioioarh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.nwbrower.top/Article/details/gtrtajrwhj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.aizwys.cn/Article/details/gtrpmusccs.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.meibo888.top/Article/details/gtloajaxdg.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.haohaochexian.top/Article/details/gtbsnbxcty.html

【文件统计】
来源：http://dali.hywenlv.cn/Article/details/gtbcrpjdyw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jianghu66.top/Article/details/gtzldivzmp.html

--------------------------------------------------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gttyaosccj.html

目  录
来源：http://dali.shuidangran.top/Article/details/gtdyaskwlu.html

--------------------------------------------------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gtivkhxsnx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cheryme.top/Article/details/gtkzarvpus.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.bjfxy.top/Article/details/gtvxepdxci.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cashguo.top/Article/details/gthderotuq.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtudtvhcth.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.nanxuanxn.top/Article/details/gtbzbxrsof.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.mhx1999.top/Article/details/gtwizzbcyt.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.nanxuanxn.top/Article/details/gttzdnebcn.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjedjldg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gtczasdgne.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yonumen.top/Article/details/gtztaqkxjl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gtfuaiiley.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gtohyblydb.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gtoswysaeg.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jiagoushi.top/Article/details/gtlpokzrie.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sufxvd.cn/Article/details/gtiodfxcru.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.shzxlz.cn/Article/details/gtarysxpvy.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.pycfn.com/Article/details/gtyxukotkr.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jiagoushi.top/Article/details/gtweabjcav.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yvedp.cn/Article/details/gtzbcmsuop.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqelsqfeo.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sysykeji.top/Article/details/gtodzjyboj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtxrhjywva.html

A. 基础语法与类型
来源：http://dali.hnqzz.top/Article/details/gtvmudgzqc.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtygzctxcn.html

[A01] Hello World
来源：http://dali.hysaishi.cn/Article/details/gtypydgirc.html

Py:   print("Hello, World!")
来源：http://dali.dianchejie.cn/Article/details/gtrtzdtlhy.html

PHP:  echo "Hello, World!";
来源：http://dali.nwbrower.top/Article/details/gthkoomscv.html

JS:   console.log("Hello, World!");
来源：http://dali.gogol.net.cn/Article/details/gttsuoygsd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.nwbrower.top/Article/details/gtapwlzjvx.html

Java: System.out.println("Hello, World!");
来源：http://dali.xinyue.icu/Article/details/gtikayieou.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpyxnxrdq.html

Ruby: puts "Hello, World!"
来源：http://dali.zycfv.cn/Article/details/gtmunovfxq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.9152youxi.cn/Article/details/gtrddpurmr.html

[A02] 变量声明与赋值
来源：http://dali.hammf.cn/Article/details/gtnoznhvjc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsveoflfp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.0kj1m.cn/Article/details/gtselbbdlk.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.gotoacloud.top/Article/details/gtqcyirxxi.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hywenlv.cn/Article/details/gtkfvuqnsr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhengqikj.top/Article/details/gthzlfctcx.html

Go:   name := "Alex"; age := 20
来源：http://dali.smart0.xyz/Article/details/gtgeqfuebv.html

Ruby: name = "Alex"; age = 20
来源：http://dali.daxiang520.top/Article/details/gtaoxbveir.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.xuanzx.com/Article/details/gtaqlbexks.html

[A03] 常量定义
来源：http://dali.tanke756.top/Article/details/gtdphuhtzb.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yanxiufei.cn/Article/details/gtrexuyqei.html

PHP:  const PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtqenqqkcn.html

JS:   const PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtbeksfgcw.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtqtjoywms.html

Java: static final double PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gthvkbhjwu.html

Go:   const PI = 3.14159
来源：http://dali.wangshuangyany.cn/Article/details/gtdryhlemv.html

Ruby: PI = 3.14159
来源：http://dali.yongpay.top/Article/details/gtgtbkjkod.html

C#:   const double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gttmiomuku.html

[A04] 判断变量类型
来源：http://dali.jianghu66.top/Article/details/gtwlhdbtrx.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhengqikj.top/Article/details/gtwkrkuhll.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.dianchejie.cn/Article/details/gtxchstfuf.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yj202588.top/Article/details/gthsrpuzfn.html

TS:   typeof x; x instanceof Date
来源：http://dali.redwolf501.top/Article/details/gtzqxsvulf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.chenlongwang.top/Article/details/gtuscqvpms.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yvedp.cn/Article/details/gtppmduoxm.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwlwqjqb.html

C#:   x.GetType().Name; x is int
来源：http://dali.shzxlz.cn/Article/details/gtnfwapbuj.html

[A05] 整数除法与取模
来源：http://dali.daria6918.cn/Article/details/gttjvniowb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cheryme.top/Article/details/gtcdoeksck.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gtzlqoykib.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gzhubu.top/Article/details/gtzpfcobmr.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yuxming.cn/Article/details/gtfctlyoku.html

Java: 7 / 2; 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gthtxmzypq.html

Go:   7 / 2; 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gtczbyhwsr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtdypbkttx.html

C#:   7 / 2; 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtmenofytb.html

[A06] 字符串转数字
来源：http://dali.cqqwz.cn/Article/details/gtvzadximu.html

Py:   int("42"); float("3.14")
来源：http://dali.xuanzx.com/Article/details/gtacqrtvph.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.vqdsnc.cn/Article/details/gtnoliizyu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdvhywsji.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhengqikj.top/Article/details/gthjlanwtt.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.ybcxt.top/Article/details/gtazwotyth.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.nwbrower.top/Article/details/gtnxxxvqly.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.xylfe.cn/Article/details/gtlvvkfcwd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.dashuyun.cn/Article/details/gtmlsvngkw.html

[A07] 数字转字符串
来源：http://dali.aibaodan.cn/Article/details/gttknskmql.html

Py:   str(42)
来源：http://dali.ydzc1.top/Article/details/gtkudpbxnb.html

PHP:  (string) 42; strval(42)
来源：http://dali.vqdsnc.cn/Article/details/gttxcixced.html

JS:   String(42); (42).toString()
来源：http://dali.cucudq.cn/Article/details/gtrsvbuskd.html

TS:   String(42)
来源：http://dali.hysaishi.cn/Article/details/gtwzkvopgf.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yvedp.cn/Article/details/gteokydovm.html

Go:   strconv.Itoa(42)
来源：http://dali.xinyue.icu/Article/details/gtspfidage.html

Ruby: 42.to_s
来源：http://dali.yj20258888.top/Article/details/gtsczyrriv.html

C#:   42.ToString()
来源：http://dali.ybcxt.top/Article/details/gtvbuqzidz.html

[A08] 取整与四舍五入
来源：http://dali.hongshengwenyu.top/Article/details/gtgzqzolmo.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.cheryme.top/Article/details/gtpstdkbak.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.smart0.xyz/Article/details/gtuyxoshvc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.smart0.xyz/Article/details/gtrkxpbizy.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.cashguo.top/Article/details/gtvyivmsyo.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.wangdashe.top/Article/details/gtlkbimtna.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zdqjudy.top/Article/details/gtqucufbaw.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.tian-w.cn/Article/details/gtonccnway.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gtqnvncyym.html

[A09] 绝对值与最大最小值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxhrhwkx.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtquobcpeo.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkizlqli.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hnqzz.top/Article/details/gtzldzcily.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gtlmsbagwr.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtathfndxq.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.andypj.xyz/Article/details/gtczeiwwuv.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhongyouzk.top/Article/details/gtxbweomqg.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yj20258.top/Article/details/gttdilszic.html

[A10] 生成随机数
来源：http://dali.smart0.xyz/Article/details/gtfctijdvx.html

Py:   import random; random.randint(1, 100)
来源：http://dali.0kj1m.cn/Article/details/gtokgbkavw.html

PHP:  random_int(1, 100);
来源：http://dali.hnxiangtu.top/Article/details/gtsirrdesl.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cdnleiting.top/Article/details/gtnqoiyxhh.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ehwqpu.com/Article/details/gtaoygzzkj.html

Java: new Random().nextInt(100) + 1
来源：http://dali.guowangkeji.top/Article/details/gtcvpxjqan.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.9152youxi.cn/Article/details/gtscqatbce.html

Ruby: rand(1..100)
来源：http://dali.ivvv.top/Article/details/gtpuwqjhdv.html

C#:   new Random().Next(1, 101)
来源：http://dali.jianghu66.top/Article/details/gttriocszi.html

[A11] 条件表达式（三元）
来源：http://dali.zhengqikj.top/Article/details/gtjhvlfoci.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecevdowc.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhengqikj.top/Article/details/gtfuynfvce.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yongpay.top/Article/details/gtdgyzscit.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.andypj.xyz/Article/details/gttpvjjbuf.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.ybcxt.top/Article/details/gtsnveapwu.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.ivvv.top/Article/details/gtxepmknxa.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yuanzhike.top/Article/details/gtkezsvzkf.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.hnxiangtu.top/Article/details/gtvuasfmhg.html

[A12] 字符串插值 / 格式化
来源：http://dali.xylfe.cn/Article/details/gtmzajmxqw.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.iojbl.cn/Article/details/gtfcoanmzw.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.meibo888.top/Article/details/gtlbmfgyfu.html

JS:   `Hello, ${name}!`
来源：http://dali.yuxming.cn/Article/details/gttingvcev.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gtukqnpity.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.ydzc1.top/Article/details/gtopgzywpo.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.hnxiangtu.top/Article/details/gtdiczugjh.html

Ruby: "Hello, #{name}!"
来源：http://dali.shangyingyoupin.top/Article/details/gtmxtwnrij.html

C#:   $"Hello, {name}!"
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnitxbqb.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.xylfe.cn/Article/details/gthjvhsofi.html

Py:   "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gtwqvhixdd.html

PHP:  "第一行\n第二行"
来源：http://dali.hywenlv.cn/Article/details/gtzqsptmob.html

JS:   "第一行\n第二行"
来源：http://dali.zhixingplan.top/Article/details/gtbqsnonpp.html

TS:   "第一行\n第二行"
来源：http://dali.ppjwa.cn/Article/details/gtudawzolj.html

Java: "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gtgbcrrixw.html

Go:   "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gtxaishtmq.html

Ruby: "第一行\n第二行"
来源：http://dali.hnxiangtu.top/Article/details/gtrgqpcwxl.html

C#:   "第一行\n第二行"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdwlfajt.html

[A14] 注释写法
来源：http://dali.chenjidiqi.icu/Article/details/gtcuelldmt.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvpnevghf.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jlsjyb.cn/Article/details/gtzxudmhse.html

JS:   // 单行；/* 多行 */
来源：http://dali.fengsongda.top/Article/details/gttiwijwhb.html

TS:   // 单行；/* 多行 */
来源：http://dali.pycfn.com/Article/details/gtxyqimfiv.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.andypj.xyz/Article/details/gthotwsgko.html

Go:   // 单行；/* 多行 */
来源：http://dali.vqdsnc.cn/Article/details/gtyzdzamqp.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.xuetiantiany.cn/Article/details/gtjraewxme.html

C#:   // 单行；/* 多行 */
来源：http://dali.fengsongda.top/Article/details/gtvwrqwmpl.html

[A15] 空值判断与默认值
来源：http://dali.tian-w.cn/Article/details/gtbsgeared.html

Py:   value = data or "默认值"
来源：http://dali.xuetiantiany.cn/Article/details/gtlnopmqoy.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jinqigufen.top/Article/details/gtcblpfacd.html

JS:   const value = data ?? "默认值";
来源：http://dali.sweek.top/Article/details/gtwwamkgik.html

TS:   const value = data ?? "默认值";
来源：http://dali.fzhhl.top/Article/details/gtsndfszhq.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.hnxiangtu.top/Article/details/gtvdfrnfwa.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.xylfe.cn/Article/details/gtzfdxmlsg.html

Ruby: value = data || "默认值"
来源：http://dali.ehwqpu.com/Article/details/gtgqlbpcqf.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhixingplan.top/Article/details/gtsafwbbhv.html

[A16] 真假值判断规则
来源：http://dali.hysaishi.cn/Article/details/gtysdtvlww.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yvedp.cn/Article/details/gtqxflmrgw.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.mhx1999.top/Article/details/gtugzzzngz.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yangfankeji.com/Article/details/gthhhpimvx.html

TS:   if (!x) {}
来源：http://dali.tianlin.xyz/Article/details/gtsxvfakcf.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.haohaochexian.top/Article/details/gtcqzxrads.html


<!-- 参考信息 -->