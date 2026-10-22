代发 wailian999

[U97] JS：并发请求
来源：http://dali.nwbrower.top/Article/details/gtcohkfrpi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gtwplgxvwu.html

[U98] JS：fetch 带 JSON
来源：http://dali.jlsjyb.cn/Article/details/gtvicyhwot.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.316326.xyz/Article/details/gtnhwmnmvv.html

[U99] JS：事件监听
来源：http://dali.daria6918.cn/Article/details/gtrycoqpwi.html

el.addEventListener("click", e => {})
来源：http://dali.cdnleiting.top/Article/details/gtlkomozlj.html

[U100] JS：DOM 查询
来源：http://dali.yanxiufei.cn/Article/details/gthucjflcr.html

document.querySelector(".item")
来源：http://dali.jyoumei.cn/Article/details/gtibnihrbi.html

[U101] JS：classList 操作
来源：http://dali.iojbl.cn/Article/details/gtmmqglogp.html

el.classList.toggle("active")
来源：http://dali.tanke756.top/Article/details/gthftmutxc.html

[U102] JS：本地存储
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgsbmjazr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ivvv.top/Article/details/gtkpjrowmd.html

[U103] JS：定时器
来源：http://dali.cheryme.top/Article/details/gtdwcycmun.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yj202588.top/Article/details/gtqlafyyke.html

[U104] JS：防抖
来源：http://dali.chenzaomai.com/Article/details/gtoxcqjuvk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ivvv.top/Article/details/gtxoygucli.html

[U105] JS：节流
来源：http://dali.hysaishi.cn/Article/details/gtdsvxtcln.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zdqjudy.top/Article/details/gtucoizgqn.html

[U106] JS：日期格式化
来源：http://dali.0kj1m.cn/Article/details/gtalbstfxj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yuxming.cn/Article/details/gttcqqojba.html

[U107] JS：数字千分位
来源：http://dali.ivvv.top/Article/details/gtqbajreij.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.aibaodan.cn/Article/details/gtmekrbfoz.html

[U108] JS：随机整数
来源：http://dali.dianchejie.cn/Article/details/gtcpuoehfd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.0kj1m.cn/Article/details/gtgeyrepyg.html

[U109] JS：数组分组
来源：http://dali.snrcjt.cn/Article/details/gtaqfplwvp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sweek.top/Article/details/gtvibhpwgz.html

[U110] JS：数组分块
来源：http://dali.zycfv.cn/Article/details/gtclbzoctk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jlsjyb.cn/Article/details/gtlqtegmnb.html

[U111] JS：对象转 Map
来源：http://dali.zhaomingkeji.xyz/Article/details/gthyraolho.html

new Map(Object.entries(obj))
来源：http://dali.smart0.xyz/Article/details/gtxvtfqmlx.html

[U112] JS：字符串补位
来源：http://dali.daxiang520.top/Article/details/gtirpzawwr.html

"7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtwrneqjmr.html

[U113] JS：正则替换全部
来源：http://dali.cashguo.top/Article/details/gtjikzxase.html

s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtomombgxu.html

[U114] JS：JSON 深比较
来源：http://dali.hysaishi.cn/Article/details/gtpelktzqh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yueranfly.top/Article/details/gtbcutnjgf.html

[U115] JS：生成 UUID
来源：http://dali.quarkkingdee.top/Article/details/gtfnijbzys.html

crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gtbdxjrgmk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.quarkkingdee.top/Article/details/gtkgohpevg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.daria6918.cn/Article/details/gtkisbrphe.html

[U117] JS：单元测试
来源：http://dali.cheryme.top/Article/details/gtxepyvbic.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gtyxqjcjoh.html

[U118] JS：开发服务器
来源：http://dali.hongshengwenyu.top/Article/details/gtrfijoinb.html

npm i -D vite;  npx vite
来源：http://dali.tianlin.xyz/Article/details/gtjobejjwp.html

[U119] JS：生产构建
来源：http://dali.feifeiyinyue.top/Article/details/gtedtcyynj.html

npx vite build
来源：http://dali.0kj1m.cn/Article/details/gtfqumfhjp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.daria6918.cn/Article/details/gtgkniygur.html

import.meta.env.VITE_API_URL
来源：http://dali.fengsongda.top/Article/details/gtbdrzjtjq.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtikfxegvu.html

统计汇总
来源：http://dali.quarkkingdee.top/Article/details/gtivyatsgo.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gttypnsasz.html

按语言统计（条）：
来源：http://dali.cheryme.top/Article/details/gtojvnccer.html

Python ......... 252
来源：http://dali.yueranfly.top/Article/details/gttjqcejif.html

PHP ............ 252
来源：http://dali.hfpthk.cn/Article/details/gtwvsguybw.html

JavaScript ..... 252
来源：http://dali.ybcxt.top/Article/details/gtkeowbblg.html

TypeScript ..... 212
来源：http://dali.ehwqpu.com/Article/details/gtlzhboahs.html

Java ........... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtxljdmljg.html

Go ............. 212
来源：http://dali.cheryme.top/Article/details/gtocxewscz.html

Ruby ........... 212
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkvdcgup.html

C# ............. 212
来源：http://dali.sysykeji.top/Article/details/gtfvhencka.html

C .............. 30
来源：http://dali.hywenlv.cn/Article/details/gtawgcufoa.html

C++ ............ 30
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakhdsbhi.html

SQL ............ 90
来源：http://dali.pycfn.com/Article/details/gtusprmiqv.html

Bash ........... 80
来源：http://dali.ppjwa.cn/Article/details/gtsidhgnqi.html

Kotlin ......... 15
来源：http://dali.birdmap.top/Article/details/gthnqdnvfj.html

Swift .......... 15
来源：http://dali.ivvv.top/Article/details/gtziyjprrl.html

Lua ............ 10
来源：http://dali.wangdashe.top/Article/details/gttneovmgw.html

Perl ........... 10
来源：http://dali.cdnleiting.top/Article/details/gtbljnlxrf.html

Scala .......... 10
来源：http://dali.guannengcc.top/Article/details/gtdfpchure.html

------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtdkjyyktq.html

合计 ........... 2106 条
来源：http://dali.xuetiantiany.cn/Article/details/gtrzrekefk.html

按章节统计：
来源：http://dali.tanke756.top/Article/details/gtkmygbllp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zycfv.cn/Article/details/gtgoueltzx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yanxiufei.cn/Article/details/gtwvutfcfs.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.sysykeji.top/Article/details/gtucdejddw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yj202588.top/Article/details/gtnnfhsurr.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hfpthk.cn/Article/details/gtejkalucr.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.chenzaomai.com/Article/details/gtxojrkkmm.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.vqdsnc.cn/Article/details/gtsnqlivxt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.feifeiyinyue.top/Article/details/gthiexokls.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gtpyrgcrbr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhengqikj.top/Article/details/gtnowohoed.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gtegpenoxy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.sweek.top/Article/details/gthihekfse.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.dianchejie.cn/Article/details/gtsectuccp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.gzhubu.top/Article/details/gtkzaefcdp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.quarkkingdee.top/Article/details/gtjrxjtevp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gtffzvogif.html

Q SQL 专题                              90
来源：http://dali.fzhhl.top/Article/details/gtkgwerkxw.html

R Bash 专题                             80
来源：http://dali.havefunace.top/Article/details/gtxwcknjtf.html

S C / C++ 专题                          60
来源：http://dali.nwbrower.top/Article/details/gtmbohcgyt.html

T 其他语言补充                          60
来源：http://dali.tian-w.cn/Article/details/gtmebxpzcx.html

U 高频实用片段                         120
来源：http://dali.sweek.top/Article/details/gtuxvjgced.html

------------------------------------
来源：http://dali.xuanzx.com/Article/details/gtieibfmom.html

合计                                  2106 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdbfgrcx.html

--------------------------------------------------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gtgdvvlyax.html

使用提醒
来源：http://dali.yonumen.top/Article/details/gtkxzbybpf.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gtzuxkakms.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cucudq.cn/Article/details/gtzvqmmktl.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xziqi.cn/Article/details/gtjzqqzhzp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yongpay.top/Article/details/gttsscolzr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cdnleiting.top/Article/details/gtuqhhyitx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hywenlv.cn/Article/details/gtsjmuklby.html

—— 文件结束 ——
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqryrbsqa.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gthmrywtsf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.tianlin.xyz/Article/details/gtuqnpggyy.html

Common Programming Examples Cheat Book
来源：http://dali.jqgfzy.top/Article/details/gtcddhtduk.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtawlkbopf.html

【收录内容】
来源：http://dali.dianchejie.cn/Article/details/gthpemlwro.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jinghuilouyu.cn/Article/details/gtbiaqamrl.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cucudq.cn/Article/details/gtrbpmsbyf.html

SQL · Bash · C · C++
来源：http://dali.jlsjyb.cn/Article/details/gtkfmijoyc.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xinyue.icu/Article/details/gtqsjegliz.html

【使用说明】
来源：http://dali.xuetiantiany.cn/Article/details/gtvirfmauk.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.tianlin.xyz/Article/details/gtsmbobfji.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrleevcs.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.vqdsnc.cn/Article/details/gthjdwdcjb.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hammf.cn/Article/details/gtwtvhzqzp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ybcxt.top/Article/details/gtbrsulrsn.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hammf.cn/Article/details/gtqvlzxyiq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hnqzz.top/Article/details/gtzbsfloph.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yj20258888.top/Article/details/gtsploffpj.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.chenjidiqi.icu/Article/details/gtjxylfxsx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.pycfn.com/Article/details/gthdpxtaxm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.aizwys.cn/Article/details/gttkcpzqai.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.gaohongyu789.top/Article/details/gthovtnhtt.html

【文件统计】
来源：http://dali.wangshuangyany.cn/Article/details/gtnmyyrluz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xziqi.cn/Article/details/gtqxsnpeuj.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gtcwaonrkz.html

目  录
来源：http://dali.zhongyouzk.top/Article/details/gtmttuwiwr.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtisgccsdb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jlsjyb.cn/Article/details/gtmoudcwmy.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.dashuyun.cn/Article/details/gtgkylhzfo.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.guannengcc.top/Article/details/gtbdxxnmaq.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yanxiufei.cn/Article/details/gtvxvgsneo.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.sysykeji.top/Article/details/gtypqzxpql.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.snrcjt.cn/Article/details/gtluhgzckk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.dianchejie.cn/Article/details/gtkddfhbuo.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jinqigfzy.top/Article/details/gttfvoqjhw.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gtuxuuiyxy.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.havefunace.top/Article/details/gtjonyxcad.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfsspzeo.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gtzhodaima.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gtbxjbiglg.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.chenlongwang.top/Article/details/gtqvrgbxyt.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yvedp.cn/Article/details/gtssmpqdzq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gttlukbzzb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.pycfn.com/Article/details/gtucnlwlhq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yonumen.top/Article/details/gtnrwxnvos.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jianghu66.top/Article/details/gtswmwgqsb.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sxryk.cn/Article/details/gtkkuwlzxp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gteybtktyf.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gttfjljeql.html

A. 基础语法与类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtoumyytqn.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtjwloxvde.html

[A01] Hello World
来源：http://dali.hnqzz.top/Article/details/gtskvyxxes.html

Py:   print("Hello, World!")
来源：http://dali.yonumen.top/Article/details/gtckrambji.html

PHP:  echo "Hello, World!";
来源：http://dali.zhixingplan.top/Article/details/gtnzyfayrn.html

JS:   console.log("Hello, World!");
来源：http://dali.yuxming.cn/Article/details/gtcarylwyo.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yj20258.top/Article/details/gthxuoqurm.html

Java: System.out.println("Hello, World!");
来源：http://dali.wangdashe.top/Article/details/gtvadffuml.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.gzhubu.top/Article/details/gtapkggthg.html

Ruby: puts "Hello, World!"
来源：http://dali.316326.xyz/Article/details/gtejfqnxle.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.wangdashe.top/Article/details/gtzhnbykyp.html

[A02] 变量声明与赋值
来源：http://dali.smart0.xyz/Article/details/gtubopyssd.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ivvv.top/Article/details/gtwovcxzrs.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gtfmnbhzzc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.nwbrower.top/Article/details/gtnrgzbggv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.andypj.xyz/Article/details/gthtfmtibf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.mhx1999.top/Article/details/gtbfvmnpwu.html

Go:   name := "Alex"; age := 20
来源：http://dali.sufxvd.cn/Article/details/gtyqjyljuh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.kuanghao11.cn/Article/details/gtnwamkejz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yonumen.top/Article/details/gtqnxqpfmq.html

[A03] 常量定义
来源：http://dali.cqqwz.cn/Article/details/gtkcwvoqoi.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cqqwz.cn/Article/details/gtwjrhdpaa.html

PHP:  const PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtwwexpiib.html

JS:   const PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtqykonacg.html

TS:   const PI: number = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajitcqub.html

Java: static final double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtlkstpwjf.html

Go:   const PI = 3.14159
来源：http://dali.wangdashe.top/Article/details/gtejayzxkv.html

Ruby: PI = 3.14159
来源：http://dali.wangdashe.top/Article/details/gtysyrbwav.html

C#:   const double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gtlnfsmqwn.html

[A04] 判断变量类型
来源：http://dali.wangdashe.top/Article/details/gtmxzrnmfw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.guowangkeji.top/Article/details/gtjrbosxpz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.nanxinkj.top/Article/details/gtwngewlyz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.cucudq.cn/Article/details/gtpkodfhje.html

TS:   typeof x; x instanceof Date
来源：http://dali.sweek.top/Article/details/gtsylhplwm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.gotoacloud.top/Article/details/gtmdgugdfo.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.nwbrower.top/Article/details/gteafpjjst.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.cashguo.top/Article/details/gtsmqwmdrx.html

C#:   x.GetType().Name; x is int
来源：http://dali.mhx1999.top/Article/details/gtpinsafak.html

[A05] 整数除法与取模
来源：http://dali.yvedp.cn/Article/details/gtixaelbms.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.hammf.cn/Article/details/gtfvqvjwep.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtvqnnxjnf.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.daxiang520.top/Article/details/gtcljogsdg.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gtlcoideyt.html

Java: 7 / 2; 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtzkracpev.html

Go:   7 / 2; 7 % 2
来源：http://dali.gogol.net.cn/Article/details/gtmceixnsu.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gtgcnoqvjy.html

C#:   7 / 2; 7 % 2
来源：http://dali.guannengcc.top/Article/details/gtxobyuckw.html

[A06] 字符串转数字
来源：http://dali.aibaodan.cn/Article/details/gtluflcpty.html

Py:   int("42"); float("3.14")
来源：http://dali.jinqigufen.top/Article/details/gtiejwjlmt.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.snrcjt.cn/Article/details/gtlnizkqbp.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.xylfe.cn/Article/details/gtqbfsjgms.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gthwsecpck.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhwpqdez.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.birdmap.top/Article/details/gtozvnzuhw.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jinghuilouyu.cn/Article/details/gtepfbzmnu.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.sufxvd.cn/Article/details/gtzckexjnm.html

[A07] 数字转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpygpanm.html

Py:   str(42)
来源：http://dali.cucudq.cn/Article/details/gtzpcwxkmx.html

PHP:  (string) 42; strval(42)
来源：http://dali.jianghu66.top/Article/details/gtkexbvjdi.html

JS:   String(42); (42).toString()
来源：http://dali.ydzc1.top/Article/details/gtsktdepjv.html

TS:   String(42)
来源：http://dali.zhoulong.xyz/Article/details/gtvcfxdupt.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jlsjyb.cn/Article/details/gtbcjbxiac.html

Go:   strconv.Itoa(42)
来源：http://dali.fengsongda.top/Article/details/gtyuxfxvce.html

Ruby: 42.to_s
来源：http://dali.chenlongwang.top/Article/details/gtfmucfira.html

C#:   42.ToString()
来源：http://dali.wangshuangyany.cn/Article/details/gtpovbernk.html

[A08] 取整与四舍五入
来源：http://dali.yuxming.cn/Article/details/gtkzknymbj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ivvv.top/Article/details/gtgjbcmfle.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.316326.xyz/Article/details/gtyybwdmue.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.mhx1999.top/Article/details/gthmaqcehm.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.chenjidiqi.icu/Article/details/gtneudsktm.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.chenjidiqi.icu/Article/details/gttdulaitw.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.tianlin.xyz/Article/details/gttptzyvar.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.hfpthk.cn/Article/details/gtpwuseszs.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.feifeiyinyue.top/Article/details/gtowgnubtn.html

[A09] 绝对值与最大最小值
来源：http://dali.aizwys.cn/Article/details/gtwdzubtca.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hfpthk.cn/Article/details/gtslmcnvhi.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gtaugyckvh.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtcstgzado.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtosmkwmad.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gtqiydlres.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yj20258888.top/Article/details/gtzasmlfdo.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.vqdsnc.cn/Article/details/gtfslcxonl.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gtjvehclaf.html

[A10] 生成随机数
来源：http://dali.redwolf501.top/Article/details/gtoputnhiv.html

Py:   import random; random.randint(1, 100)
来源：http://dali.xinyue.icu/Article/details/gtodaofubm.html

PHP:  random_int(1, 100);
来源：http://dali.shanyushiyangtech.top/Article/details/gthhqpumkm.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.redwolf501.top/Article/details/gtpkwmkpji.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jianghu66.top/Article/details/gtazwrvcnv.html

Java: new Random().nextInt(100) + 1
来源：http://dali.pycfn.com/Article/details/gtmqwayngz.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.ivvv.top/Article/details/gtszaukexh.html

Ruby: rand(1..100)
来源：http://dali.daxiang520.top/Article/details/gtkcqjfzmi.html

C#:   new Random().Next(1, 101)
来源：http://dali.xinyue.icu/Article/details/gtrhfzcnzk.html

[A11] 条件表达式（三元）
来源：http://dali.hammf.cn/Article/details/gtpcntmvpy.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.shuidangran.top/Article/details/gtiegobdbt.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.chenjidiqi.icu/Article/details/gtcmhmrvsw.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.sysykeji.top/Article/details/gtkykzdsnk.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.smart0.xyz/Article/details/gthfqbvadh.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.iojbl.cn/Article/details/gtnlkclwjx.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.hfpthk.cn/Article/details/gtwdrrlnbn.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.cheryme.top/Article/details/gtnyopoxfs.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yanxiufei.cn/Article/details/gtkundzokg.html

[A12] 字符串插值 / 格式化
来源：http://dali.cqqwz.cn/Article/details/gtzmvpjkls.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjmfvvpu.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.ybcxt.top/Article/details/gtzcfghngx.html

JS:   `Hello, ${name}!`
来源：http://dali.jqgufenzy.top/Article/details/gthlamjcja.html

TS:   `Hello, ${name}!`
来源：http://dali.yonumen.top/Article/details/gttudrwfvv.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.sweek.top/Article/details/gtzfifjkxo.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.dianchejie.cn/Article/details/gtpqqqikkp.html

Ruby: "Hello, #{name}!"
来源：http://dali.yvedp.cn/Article/details/gtyzmsehmc.html

C#:   $"Hello, {name}!"
来源：http://dali.c1oappe.top/Article/details/gtgqqgcfyr.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.gzhubu.top/Article/details/gtwsdtlvio.html

Py:   "第一行\n第二行"
来源：http://dali.birdmap.top/Article/details/gtmtgndoez.html

PHP:  "第一行\n第二行"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcoypjtbi.html

JS:   "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gtkjxppkpe.html

TS:   "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gtcbednnay.html

Java: "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gtfizigvfd.html

Go:   "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gtytfpxdbj.html

Ruby: "第一行\n第二行"
来源：http://dali.ybcxt.top/Article/details/gtlbekppuc.html

C#:   "第一行\n第二行"
来源：http://dali.shanyushiyangtech.top/Article/details/gtjzkxiacs.html

[A14] 注释写法
来源：http://dali.shanyushiyangtech.top/Article/details/gtfivxhyom.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.sxryk.cn/Article/details/gtoeaorndz.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yj20258.top/Article/details/gtemmzctns.html

JS:   // 单行；/* 多行 */
来源：http://dali.kuanghao11.cn/Article/details/gthnmbzbds.html

TS:   // 单行；/* 多行 */
来源：http://dali.316326.xyz/Article/details/gtjgqblhep.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jiagoushi.top/Article/details/gtxvubitqf.html

Go:   // 单行；/* 多行 */
来源：http://dali.aizwys.cn/Article/details/gtxqqxoqxy.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.andypj.xyz/Article/details/gtgptiqpqp.html

C#:   // 单行；/* 多行 */
来源：http://dali.sysykeji.top/Article/details/gtsaxsjblt.html

[A15] 空值判断与默认值
来源：http://dali.chenzaomai.com/Article/details/gtotlotayt.html

Py:   value = data or "默认值"
来源：http://dali.yangfankeji.com/Article/details/gtphvsbjvv.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.nanxuanxn.top/Article/details/gtrpkkqfyv.html

JS:   const value = data ?? "默认值";
来源：http://dali.shzxlz.cn/Article/details/gtycydmhpa.html

TS:   const value = data ?? "默认值";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxichzkpf.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.gogol.net.cn/Article/details/gtbcwkeydz.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhixingplan.top/Article/details/gttiwhqvkm.html

Ruby: value = data || "默认值"
来源：http://dali.nwbrower.top/Article/details/gtfyxcproe.html

C#:   var value = data ?? "默认值";
来源：http://dali.jianghu66.top/Article/details/gtwyxgicgp.html

[A16] 真假值判断规则
来源：http://dali.zhiwuduotai.top/Article/details/gthrlyyyqb.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.nwbrower.top/Article/details/gtnbbuxllj.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwozjgqyk.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.fengsongda.top/Article/details/gtixegisiz.html

TS:   if (!x) {}
来源：http://dali.gotoacloud.top/Article/details/gtzepeuqjl.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.daria6918.cn/Article/details/gtrgcqsgnh.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.ivvv.top/Article/details/gtmlaeydkt.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.c1oappe.top/Article/details/gtkeeplbjp.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.iojbl.cn/Article/details/gtzfywzpoa.html

[A17] 位运算
来源：http://dali.havefunace.top/Article/details/gtkpopkqtm.html


<!-- 参考信息 -->