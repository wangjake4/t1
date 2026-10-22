代发 wailian999

[U97] JS：并发请求
来源：http://dali.yj20258.top/Article/details/gtfksevfqh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gtyyvcbgjr.html

[U98] JS：fetch 带 JSON
来源：http://dali.hywenlv.cn/Article/details/gtqvcwkqaq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.gzhubu.top/Article/details/gtvxxanuji.html

[U99] JS：事件监听
来源：http://dali.vqdsnc.cn/Article/details/gtolkflwlu.html

el.addEventListener("click", e => {})
来源：http://dali.gogol.net.cn/Article/details/gtdizlbwwv.html

[U100] JS：DOM 查询
来源：http://dali.zhiwuduotai.top/Article/details/gtuaxbnjmk.html

document.querySelector(".item")
来源：http://dali.shuidangran.top/Article/details/gtybogdgxm.html

[U101] JS：classList 操作
来源：http://dali.fzhhl.top/Article/details/gtptjmkvfc.html

el.classList.toggle("active")
来源：http://dali.nanxuanxn.top/Article/details/gtirsrrvhw.html

[U102] JS：本地存储
来源：http://dali.hammf.cn/Article/details/gthtrrnpdc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.c1oappe.top/Article/details/gtsnxdiwya.html

[U103] JS：定时器
来源：http://dali.dashuyun.cn/Article/details/gtfrlfhote.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlspfcpbn.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gtrdkkkahr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gttlrrsosp.html

[U105] JS：节流
来源：http://dali.zhoulong.xyz/Article/details/gtmippvqrh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.aibaodan.cn/Article/details/gtfsuassqt.html

[U106] JS：日期格式化
来源：http://dali.yvedp.cn/Article/details/gtvmxbkrnj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yonumen.top/Article/details/gtpsbawwpo.html

[U107] JS：数字千分位
来源：http://dali.dashuyun.cn/Article/details/gtpisxlokm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xuetiantiany.cn/Article/details/gtrjayxzkc.html

[U108] JS：随机整数
来源：http://dali.jqgfzy.top/Article/details/gthnmywlep.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbonutte.html

[U109] JS：数组分组
来源：http://dali.nanxinkj.top/Article/details/gturphfhjz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gtmtxnyfqg.html

[U110] JS：数组分块
来源：http://dali.zhixingplan.top/Article/details/gtxkpjlduc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jiagoushi.top/Article/details/gtanjroqfe.html

[U111] JS：对象转 Map
来源：http://dali.sweek.top/Article/details/gtuuhxvomm.html

new Map(Object.entries(obj))
来源：http://dali.xinyue.icu/Article/details/gtdjzmfjfx.html

[U112] JS：字符串补位
来源：http://dali.cdnleiting.top/Article/details/gttbqpgwyg.html

"7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtgutjjjtw.html

[U113] JS：正则替换全部
来源：http://dali.0kj1m.cn/Article/details/gttwgekjck.html

s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtjsyiuyyr.html

[U114] JS：JSON 深比较
来源：http://dali.nwbrower.top/Article/details/gtabvyqzxp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gtkojemnnv.html

[U115] JS：生成 UUID
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvxvyzfpe.html

crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gtctsnrxnb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hnqzz.top/Article/details/gtkxqmspkg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtedjomhyg.html

[U117] JS：单元测试
来源：http://dali.daxiang520.top/Article/details/gtolelucse.html

npm i -D vitest;  npx vitest
来源：http://dali.yangfankeji.com/Article/details/gtmqqpyfhs.html

[U118] JS：开发服务器
来源：http://dali.jyoumei.cn/Article/details/gtpnrlxbnn.html

npm i -D vite;  npx vite
来源：http://dali.gzhubu.top/Article/details/gtwrzdjdcl.html

[U119] JS：生产构建
来源：http://dali.ehwqpu.com/Article/details/gtkwtpazue.html

npx vite build
来源：http://dali.andypj.xyz/Article/details/gtlcbgnthe.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.birdmap.top/Article/details/gtidlpzdrp.html

import.meta.env.VITE_API_URL
来源：http://dali.bjfxy.top/Article/details/gtnhesmxkh.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtetkvemdw.html

统计汇总
来源：http://dali.hysaishi.cn/Article/details/gtdmxkfvzf.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtapdcykzj.html

按语言统计（条）：
来源：http://dali.yongpay.top/Article/details/gtwjblafqf.html

Python ......... 252
来源：http://dali.yongpay.top/Article/details/gtkyscqgya.html

PHP ............ 252
来源：http://dali.feifeiyinyue.top/Article/details/gtiqoatwvu.html

JavaScript ..... 252
来源：http://dali.jiagoushi.top/Article/details/gtgjcbyssi.html

TypeScript ..... 212
来源：http://dali.yuanzhike.top/Article/details/gtpdraabeo.html

Java ........... 212
来源：http://dali.aibaodan.cn/Article/details/gtswnnwrzu.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gtlgkwpooi.html

Ruby ........... 212
来源：http://dali.xuanzx.com/Article/details/gthojdgzna.html

C# ............. 212
来源：http://dali.hongshengwenyu.top/Article/details/gtppscmuaj.html

C .............. 30
来源：http://dali.jinqigufen.top/Article/details/gtacgxpdlj.html

C++ ............ 30
来源：http://dali.chenzaomai.com/Article/details/gtfhebmcvl.html

SQL ............ 90
来源：http://dali.hywenlv.cn/Article/details/gtplqnqxbb.html

Bash ........... 80
来源：http://dali.ppjwa.cn/Article/details/gtitiejgrc.html

Kotlin ......... 15
来源：http://dali.9152youxi.cn/Article/details/gtzpkkamda.html

Swift .......... 15
来源：http://dali.yanxiufei.cn/Article/details/gtnbzlnfcb.html

Lua ............ 10
来源：http://dali.shanyushiyangtech.top/Article/details/gtivmijlzo.html

Perl ........... 10
来源：http://dali.gzhubu.top/Article/details/gtdwdfjpwb.html

Scala .......... 10
来源：http://dali.guannengcc.top/Article/details/gtitjietta.html

------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gtdtjtanns.html

合计 ........... 2106 条
来源：http://dali.yangfankeji.com/Article/details/gtkbysbujl.html

按章节统计：
来源：http://dali.hfpthk.cn/Article/details/gtwodfhkqt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ybcxt.top/Article/details/gttwycfcsr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hywenlv.cn/Article/details/gtxxseszhb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.redwolf501.top/Article/details/gtgrcdfhnt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hfpthk.cn/Article/details/gtefoobfbz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yonumen.top/Article/details/gtgpxnqwfj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cashguo.top/Article/details/gtuceisebq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tian-w.cn/Article/details/gtxjsuxlty.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cucudq.cn/Article/details/gtyfoysjhl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gtovcrsxac.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yuxming.cn/Article/details/gtnttocerv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gtkumdfwlh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gtlknqcpkv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gtehmmyfhq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ydzc1.top/Article/details/gtdtjnbamm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhongyouzk.top/Article/details/gtqhoyutpp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jqgufenzy.top/Article/details/gtxvaawvql.html

Q SQL 专题                              90
来源：http://dali.sweek.top/Article/details/gtiobucqnj.html

R Bash 专题                             80
来源：http://dali.dianchejie.cn/Article/details/gthmbklayd.html

S C / C++ 专题                          60
来源：http://dali.meibo888.top/Article/details/gtjloozjev.html

T 其他语言补充                          60
来源：http://dali.sxryk.cn/Article/details/gtzagxpwfh.html

U 高频实用片段                         120
来源：http://dali.gaohongyu789.top/Article/details/gtlezasebc.html

------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gtlucrkxct.html

合计                                  2106 条
来源：http://dali.guowangkeji.top/Article/details/gtyndbparp.html

--------------------------------------------------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gtpwhxaydw.html

使用提醒
来源：http://dali.xziqi.cn/Article/details/gtwqzfiuua.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkzzdnjr.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yanxiufei.cn/Article/details/gtsymdyrnn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jinqigfzy.top/Article/details/gtrkunsyxp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hywenlv.cn/Article/details/gtomhcdbbo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.gaohongyu789.top/Article/details/gtxwqwxchk.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.nwbrower.top/Article/details/gtexhycfbd.html

—— 文件结束 ——
来源：http://dali.kuanghao11.cn/Article/details/gtgzrabzsm.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtdifillhs.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cheryme.top/Article/details/gtynronjgy.html

Common Programming Examples Cheat Book
来源：http://dali.xylfe.cn/Article/details/gtumobqook.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtztcjkdqr.html

【收录内容】
来源：http://dali.ybcxt.top/Article/details/gtcrsrqkij.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yonumen.top/Article/details/gthpzidulc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yuxming.cn/Article/details/gtzjacvkoz.html

SQL · Bash · C · C++
来源：http://dali.wangshuangyany.cn/Article/details/gtluxehcoo.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ehwqpu.com/Article/details/gtbhxwmygj.html

【使用说明】
来源：http://dali.hongshengwenyu.top/Article/details/gtfbpypuhz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cqqwz.cn/Article/details/gtqisaptdz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.daria6918.cn/Article/details/gtdfxfvkwz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xylfe.cn/Article/details/gtbkyhsfyd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xziqi.cn/Article/details/gtyicxkmiq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovmttydw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.snrcjt.cn/Article/details/gtzngegrag.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hammf.cn/Article/details/gtbntbxrwn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.gaohongyu789.top/Article/details/gtjhphfedv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.chenjidiqi.icu/Article/details/gtwnqftzms.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jiagoushi.top/Article/details/gtmdhkctyp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.guannengcc.top/Article/details/gtddbiprun.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cucudq.cn/Article/details/gtteevvkoz.html

【文件统计】
来源：http://dali.guowangkeji.top/Article/details/gtgpysuomm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.pengpengdd.cyou/Article/details/gtyngolazi.html

--------------------------------------------------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gtdmojvjtc.html

目  录
来源：http://dali.hywenlv.cn/Article/details/gtizkkcxbv.html

--------------------------------------------------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gtdkfzlaue.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprovfhwb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtrodvjnxs.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhengqikj.top/Article/details/gtdjqgeadx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtrxinujfe.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.sxryk.cn/Article/details/gtjsnzywtz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.andypj.xyz/Article/details/gtosjqsnqw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtpvgkfems.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.nwbrower.top/Article/details/gtqefogbom.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gtazaaegjh.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jiagoushi.top/Article/details/gtvpqkxaol.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jyoumei.cn/Article/details/gthwvthczs.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xziqi.cn/Article/details/gtzujhsbav.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gtddgbokdd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yongpay.top/Article/details/gttkfjoqjy.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.guowangkeji.top/Article/details/gtkboiggur.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.gotoacloud.top/Article/details/gtddjtmhdy.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xziqi.cn/Article/details/gtpqqivuwm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.nanxinkj.top/Article/details/gtamywenmi.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hysaishi.cn/Article/details/gtpzqviqsj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yvedp.cn/Article/details/gtfnliprrk.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangdashe.top/Article/details/gtaqvuposi.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtzxsabvvp.html

A. 基础语法与类型
来源：http://dali.ehwqpu.com/Article/details/gtnnjbnvyj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtbeumicyz.html

[A01] Hello World
来源：http://dali.nanxinkj.top/Article/details/gtcfsbiqob.html

Py:   print("Hello, World!")
来源：http://dali.0kj1m.cn/Article/details/gtvnruxnez.html

PHP:  echo "Hello, World!";
来源：http://dali.sysykeji.top/Article/details/gtlhshbumn.html

JS:   console.log("Hello, World!");
来源：http://dali.chenlongwang.top/Article/details/gtxolhcptg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cashguo.top/Article/details/gtrncxhkbo.html

Java: System.out.println("Hello, World!");
来源：http://dali.chenlongwang.top/Article/details/gtnbskciec.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hywenlv.cn/Article/details/gtlgfcbnqv.html

Ruby: puts "Hello, World!"
来源：http://dali.yonumen.top/Article/details/gtxfldihkd.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.bjfxy.top/Article/details/gtnnkegavn.html

[A02] 变量声明与赋值
来源：http://dali.andypj.xyz/Article/details/gtlpghiupr.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.kuanghao11.cn/Article/details/gtjjqwuzky.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.gogol.net.cn/Article/details/gtgmsnhznj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xylfe.cn/Article/details/gtfzbsffjj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhongyouzk.top/Article/details/gtusetajco.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtlqdsyxiw.html

Go:   name := "Alex"; age := 20
来源：http://dali.yuxming.cn/Article/details/gtkcfxldgk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.dashuyun.cn/Article/details/gtdisoxhbd.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.cucudq.cn/Article/details/gtypefccjd.html

[A03] 常量定义
来源：http://dali.nanxinkj.top/Article/details/gtflkylhju.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrknrxkip.html

PHP:  const PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtbuxhsfqd.html

JS:   const PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtrcppqnda.html

TS:   const PI: number = 3.14159;
来源：http://dali.yongpay.top/Article/details/gttjjzlcjs.html

Java: static final double PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtubdxxrlv.html

Go:   const PI = 3.14159
来源：http://dali.dianchejie.cn/Article/details/gtucgszeev.html

Ruby: PI = 3.14159
来源：http://dali.yvedp.cn/Article/details/gtcbbzkjgg.html

C#:   const double PI = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gtuzgtzfqe.html

[A04] 判断变量类型
来源：http://dali.aizwys.cn/Article/details/gtocxcqfxy.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yonumen.top/Article/details/gtckfajtkm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hywenlv.cn/Article/details/gtremggnfz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.andypj.xyz/Article/details/gthkqbcqyf.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhongyouzk.top/Article/details/gtlmretrbf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yuanzhike.top/Article/details/gtnowtwhkn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.nwbrower.top/Article/details/gtmexkxlqb.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yvedp.cn/Article/details/gtmytztrqd.html

C#:   x.GetType().Name; x is int
来源：http://dali.cashguo.top/Article/details/gtjeyuiqbu.html

[A05] 整数除法与取模
来源：http://dali.c1oappe.top/Article/details/gtpbxobjjg.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.haohaochexian.top/Article/details/gtlkagxojk.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gtolnqyxdh.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sxryk.cn/Article/details/gtrmnrobgl.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aizwys.cn/Article/details/gtrjmtjpna.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gtnjzusmlq.html

Go:   7 / 2; 7 % 2
来源：http://dali.yonumen.top/Article/details/gthmeooosw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gtlmaylvxa.html

C#:   7 / 2; 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gtdycsytxr.html

[A06] 字符串转数字
来源：http://dali.dashuyun.cn/Article/details/gtkprohzan.html

Py:   int("42"); float("3.14")
来源：http://dali.kuanghao11.cn/Article/details/gtzirwulst.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cucudq.cn/Article/details/gtpwwrjwlp.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jqgfzy.top/Article/details/gtxewvzmhs.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.tian-w.cn/Article/details/gtvhynzggc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhixingplan.top/Article/details/gtpufizvrc.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ivvv.top/Article/details/gtcyguobac.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.fengsongda.top/Article/details/gtuotfgnlk.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jqgufenzy.top/Article/details/gtjteoindb.html

[A07] 数字转字符串
来源：http://dali.yj20258.top/Article/details/gtvxrzlzdp.html

Py:   str(42)
来源：http://dali.aizwys.cn/Article/details/gtpmouggrv.html

PHP:  (string) 42; strval(42)
来源：http://dali.hfpthk.cn/Article/details/gtitovjwlr.html

JS:   String(42); (42).toString()
来源：http://dali.9152youxi.cn/Article/details/gthimjiwjn.html

TS:   String(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiltjwqlo.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yj202588.top/Article/details/gtgasrkaki.html

Go:   strconv.Itoa(42)
来源：http://dali.sxryk.cn/Article/details/gtxsffqrcz.html

Ruby: 42.to_s
来源：http://dali.yonumen.top/Article/details/gteyexkjvj.html

C#:   42.ToString()
来源：http://dali.daria6918.cn/Article/details/gtoldionwj.html

[A08] 取整与四舍五入
来源：http://dali.guowangkeji.top/Article/details/gtfjrmkhuf.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.andypj.xyz/Article/details/gtkstkcjkd.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.feifeiyinyue.top/Article/details/gtqxsxucqo.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.dashuyun.cn/Article/details/gtwbvitvgq.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.nwbrower.top/Article/details/gttxrbspju.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtymxiovqs.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.havefunace.top/Article/details/gtwmzlslav.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.hysaishi.cn/Article/details/gtmwjbxhcw.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gttibisagm.html

[A09] 绝对值与最大最小值
来源：http://dali.guannengcc.top/Article/details/gtgdboucpx.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shuidangran.top/Article/details/gtiafybmvk.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gtxslhoaje.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.wangdashe.top/Article/details/gtpycmilcm.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtkxepsphr.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gtljtrjbwl.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.dashuyun.cn/Article/details/gteghcqdqs.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkfemqjo.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.pycfn.com/Article/details/gtgrhysufb.html

[A10] 生成随机数
来源：http://dali.jinqigfzy.top/Article/details/gtdxanuyem.html

Py:   import random; random.randint(1, 100)
来源：http://dali.redwolf501.top/Article/details/gtqrulponr.html

PHP:  random_int(1, 100);
来源：http://dali.316326.xyz/Article/details/gtansqjzsy.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.andypj.xyz/Article/details/gtnqaojrdz.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.quarkkingdee.top/Article/details/gtymlyhgdr.html

Java: new Random().nextInt(100) + 1
来源：http://dali.tianlin.xyz/Article/details/gtrkyirwis.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yongpay.top/Article/details/gthmrvlaev.html

Ruby: rand(1..100)
来源：http://dali.feifeiyinyue.top/Article/details/gtasowanvb.html

C#:   new Random().Next(1, 101)
来源：http://dali.meibo888.top/Article/details/gtdgwanhxg.html

[A11] 条件表达式（三元）
来源：http://dali.chenzaomai.com/Article/details/gtfkqbmqzg.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.hywenlv.cn/Article/details/gtktpixwwr.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.nanxuanxn.top/Article/details/gtotuxqjlo.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gthobrkqmu.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqygxxjry.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yj20258.top/Article/details/gttwfldzlz.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.gogol.net.cn/Article/details/gtopfozyui.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlestiycl.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszvgcncn.html

[A12] 字符串插值 / 格式化
来源：http://dali.c1oappe.top/Article/details/gtighqzroz.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.iojbl.cn/Article/details/gttivoawzd.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.xuetiantiany.cn/Article/details/gtoankfhjo.html

JS:   `Hello, ${name}!`
来源：http://dali.xuanzx.com/Article/details/gtdicjckok.html

TS:   `Hello, ${name}!`
来源：http://dali.bjfxy.top/Article/details/gtytryibys.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zycfv.cn/Article/details/gtfkbmewvr.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.hnxiangtu.top/Article/details/gtjyixtybv.html

Ruby: "Hello, #{name}!"
来源：http://dali.shzxlz.cn/Article/details/gtguqljevv.html

C#:   $"Hello, {name}!"
来源：http://dali.jiagoushi.top/Article/details/gtqvpjsdhk.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.tianlin.xyz/Article/details/gtxtvrphrd.html

Py:   "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gtvydczhoj.html

PHP:  "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcyjppkfl.html

JS:   "第一行\n第二行"
来源：http://dali.quarkkingdee.top/Article/details/gtxeolnbkv.html

TS:   "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzohldzi.html

Java: "第一行\n第二行"
来源：http://dali.dianchejie.cn/Article/details/gtduyvtxzk.html

Go:   "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gtpdmjcqwb.html

Ruby: "第一行\n第二行"
来源：http://dali.mhx1999.top/Article/details/gtbhshkwsf.html

C#:   "第一行\n第二行"
来源：http://dali.hnxiangtu.top/Article/details/gtdavcxion.html

[A14] 注释写法
来源：http://dali.shangyingyoupin.top/Article/details/gtkgptesug.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yanxiufei.cn/Article/details/gtbvcyxlzz.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.bjfxy.top/Article/details/gtiefnejlp.html

JS:   // 单行；/* 多行 */
来源：http://dali.kuanghao11.cn/Article/details/gtmhveelng.html

TS:   // 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gtvdcnaesc.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhongyouzk.top/Article/details/gthrpevlmo.html

Go:   // 单行；/* 多行 */
来源：http://dali.cqqwz.cn/Article/details/gtkwfqccec.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hnqzz.top/Article/details/gtwezwfcpn.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gttxhlpgtq.html

[A15] 空值判断与默认值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqktysxl.html

Py:   value = data or "默认值"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpvrwcss.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jqgfzy.top/Article/details/gtfoxzagsa.html

JS:   const value = data ?? "默认值";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwuytpnq.html

TS:   const value = data ?? "默认值";
来源：http://dali.birdmap.top/Article/details/gtzhcqfxbl.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.feifeiyinyue.top/Article/details/gtvsxwmtga.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shangyingyoupin.top/Article/details/gtnfvxsisn.html

Ruby: value = data || "默认值"
来源：http://dali.cashguo.top/Article/details/gtxbvvonpf.html

C#:   var value = data ?? "默认值";
来源：http://dali.hnxiangtu.top/Article/details/gtzhileyyk.html

[A16] 真假值判断规则
来源：http://dali.hywenlv.cn/Article/details/gtgjcbfjcp.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.hnxiangtu.top/Article/details/gtdsykngab.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzsfpgkd.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jlsjyb.cn/Article/details/gtogunzaal.html

TS:   if (!x) {}
来源：http://dali.iojbl.cn/Article/details/gteydywzue.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.bjfxy.top/Article/details/gtnlcekxdf.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.guowangkeji.top/Article/details/gtvelqcjxe.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.sufxvd.cn/Article/details/gtruausoin.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.smart0.xyz/Article/details/gtflnzxmio.html

[A17] 位运算
来源：http://dali.hfpthk.cn/Article/details/gtsekqrjup.html


<!-- 参考信息 -->