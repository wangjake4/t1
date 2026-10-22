代发 wailian999

[U101] JS：classList 操作
来源：http://dali.yj20258888.top/Article/details/gtfbhccnur.html

el.classList.toggle("active")
来源：http://dali.cdnleiting.top/Article/details/gtdfzxqwzq.html

[U102] JS：本地存储
来源：http://dali.wangdashe.top/Article/details/gtlfemebmq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.cdnleiting.top/Article/details/gtxaqymxbg.html

[U103] JS：定时器
来源：http://dali.jiagoushi.top/Article/details/gtwnjdaasi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.nanxinkj.top/Article/details/gtxgjcgjkk.html

[U104] JS：防抖
来源：http://dali.jyoumei.cn/Article/details/gtyngutozr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gtgqihistk.html

[U105] JS：节流
来源：http://dali.vqdsnc.cn/Article/details/gtshudnyca.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfpmsyizw.html

[U106] JS：日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gteyqokfjs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hnxiangtu.top/Article/details/gtehcqomsp.html

[U107] JS：数字千分位
来源：http://dali.iojbl.cn/Article/details/gtupvesiuc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sysykeji.top/Article/details/gtckcjcuss.html

[U108] JS：随机整数
来源：http://dali.shuidangran.top/Article/details/gtdxynolva.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.quarkkingdee.top/Article/details/gtkwpbvkig.html

[U109] JS：数组分组
来源：http://dali.jlsjyb.cn/Article/details/gtdltdjpgm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cashguo.top/Article/details/gtxoldofak.html

[U110] JS：数组分块
来源：http://dali.haohaochexian.top/Article/details/gtwzyewobe.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.tianlin.xyz/Article/details/gtngvioond.html

[U111] JS：对象转 Map
来源：http://dali.jianghu66.top/Article/details/gtsmdrlxha.html

new Map(Object.entries(obj))
来源：http://dali.guowangkeji.top/Article/details/gtqtckglbs.html

[U112] JS：字符串补位
来源：http://dali.aizwys.cn/Article/details/gtfqfmhmii.html

"7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gtuvhipysc.html

[U113] JS：正则替换全部
来源：http://dali.havefunace.top/Article/details/gtjjzolhdu.html

s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtgnsvsdux.html

[U114] JS：JSON 深比较
来源：http://dali.svipenyu.cn/Article/details/gtfovfxwec.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtcgamshqd.html

[U115] JS：生成 UUID
来源：http://dali.pengpengdd.cyou/Article/details/gtzlyuihtf.html

crypto.randomUUID()
来源：http://dali.sufxvd.cn/Article/details/gtbvivvcxm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjghhimks.html

/** @param {string} name */ function f(name) {}
来源：http://dali.andypj.xyz/Article/details/gtyfflliwm.html

[U117] JS：单元测试
来源：http://dali.pengpengdd.cyou/Article/details/gtpgrtkxgw.html

npm i -D vitest;  npx vitest
来源：http://dali.wangshuangyany.cn/Article/details/gtbvlocfgj.html

[U118] JS：开发服务器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtauhzoujb.html

npm i -D vite;  npx vite
来源：http://dali.chenjidiqi.icu/Article/details/gtlyvcwiyd.html

[U119] JS：生产构建
来源：http://dali.jlsjyb.cn/Article/details/gtfingfyks.html

npx vite build
来源：http://dali.yj202588.top/Article/details/gtrbdrmikk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gogol.net.cn/Article/details/gtsthkplsb.html

import.meta.env.VITE_API_URL
来源：http://dali.yonumen.top/Article/details/gthcamqoem.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gttpchjekj.html

统计汇总
来源：http://dali.hfpthk.cn/Article/details/gtjwizwfkf.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtmbfviwjp.html

按语言统计（条）：
来源：http://dali.quarkkingdee.top/Article/details/gtqgbyueah.html

Python ......... 252
来源：http://dali.sxryk.cn/Article/details/gtweeknljp.html

PHP ............ 252
来源：http://dali.hywenlv.cn/Article/details/gtgksrisqw.html

JavaScript ..... 252
来源：http://dali.zhengqikj.top/Article/details/gtogvbsqge.html

TypeScript ..... 212
来源：http://dali.yj20258888.top/Article/details/gtqcddping.html

Java ........... 212
来源：http://dali.jlsjyb.cn/Article/details/gtyaptyjry.html

Go ............. 212
来源：http://dali.feifeiyinyue.top/Article/details/gttzrsplth.html

Ruby ........... 212
来源：http://dali.cheryme.top/Article/details/gtzagdepii.html

C# ............. 212
来源：http://dali.hammf.cn/Article/details/gtujrbnhas.html

C .............. 30
来源：http://dali.daxiang520.top/Article/details/gtipmirndv.html

C++ ............ 30
来源：http://dali.jiagoushi.top/Article/details/gtuiighfar.html

SQL ............ 90
来源：http://dali.gaohongyu789.top/Article/details/gtmrvitlzf.html

Bash ........... 80
来源：http://dali.aibaodan.cn/Article/details/gtrptuazas.html

Kotlin ......... 15
来源：http://dali.cqqwz.cn/Article/details/gtwhpzaxic.html

Swift .......... 15
来源：http://dali.guannengcc.top/Article/details/gtgasfjwev.html

Lua ............ 10
来源：http://dali.meibo888.top/Article/details/gthympjexm.html

Perl ........... 10
来源：http://dali.vqdsnc.cn/Article/details/gtndcpkbjc.html

Scala .......... 10
来源：http://dali.ppjwa.cn/Article/details/gtwknailws.html

------------------------------------
来源：http://dali.tian-w.cn/Article/details/gtxmchyykt.html

合计 ........... 2106 条
来源：http://dali.zycfv.cn/Article/details/gtpfwgycwl.html

按章节统计：
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahtfrhov.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.iojbl.cn/Article/details/gtwhnfqgyg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hammf.cn/Article/details/gtezvzmtbw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.havefunace.top/Article/details/gtmmchowck.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hnxiangtu.top/Article/details/gtnnozppyl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sufxvd.cn/Article/details/gtovjypwmt.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.haohaochexian.top/Article/details/gtinififka.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.chenlongwang.top/Article/details/gthrgehfrm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.tianlin.xyz/Article/details/gtzmjlohmc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gthobfkurv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shanyushiyangtech.top/Article/details/gteyndnohf.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gtvbjtcylm.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gtgterysmh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gtgsilwyne.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.iojbl.cn/Article/details/gtkrnuipgl.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cucudq.cn/Article/details/gtuesrsmja.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhnikifm.html

Q SQL 专题                              90
来源：http://dali.xylfe.cn/Article/details/gthmrzpexq.html

R Bash 专题                             80
来源：http://dali.gaohongyu789.top/Article/details/gtmnpahfqh.html

S C / C++ 专题                          60
来源：http://dali.quarkkingdee.top/Article/details/gttmgntauu.html

T 其他语言补充                          60
来源：http://dali.smart0.xyz/Article/details/gtqgmhwrue.html

U 高频实用片段                         120
来源：http://dali.tianlin.xyz/Article/details/gtovskayhu.html

------------------------------------
来源：http://dali.sysykeji.top/Article/details/gtbunqzgkq.html

合计                                  2106 条
来源：http://dali.hnqzz.top/Article/details/gtwttojogh.html

--------------------------------------------------------------------------------
来源：http://dali.birdmap.top/Article/details/gttxhgekyx.html

使用提醒
来源：http://dali.smart0.xyz/Article/details/gtmavgwyny.html

--------------------------------------------------------------------------------
来源：http://dali.aizwys.cn/Article/details/gtzjcacbnx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hnqzz.top/Article/details/gtveblofah.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.daxiang520.top/Article/details/gtpzyynjwu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zdqjudy.top/Article/details/gtooixdemo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jqgfzy.top/Article/details/gthxqyurab.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jqgfzy.top/Article/details/gtccictdmj.html

—— 文件结束 ——
来源：http://dali.aizwys.cn/Article/details/gtsonnnjct.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtvfpmdqbi.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.havefunace.top/Article/details/gtwzlmznuc.html

Common Programming Examples Cheat Book
来源：http://dali.xziqi.cn/Article/details/gtuyitlpsg.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtyesxwqix.html

【收录内容】
来源：http://dali.yvedp.cn/Article/details/gtlgrhzjlx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.fengsongda.top/Article/details/gtdtbmbqyk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jinqigufen.top/Article/details/gtsqzyatsi.html

SQL · Bash · C · C++
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyaiknyav.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yj20258888.top/Article/details/gterlpshzq.html

【使用说明】
来源：http://dali.chenjidiqi.icu/Article/details/gtsczzigte.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhoulong.xyz/Article/details/gtttvkgvjb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.guannengcc.top/Article/details/gtjngpxxwz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hysaishi.cn/Article/details/gtgnwlysrw.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.gaohongyu789.top/Article/details/gtsahstdhl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.tanke756.top/Article/details/gtynpzzkdi.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jqgufenzy.top/Article/details/gtcofduvvb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yvedp.cn/Article/details/gtqbvnwmlf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.316326.xyz/Article/details/gtemaliqbx.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.chenjidiqi.icu/Article/details/gtzcppjeor.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ehwqpu.com/Article/details/gtltaqrsag.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.mhx1999.top/Article/details/gtqybhfcmt.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yuanzhike.top/Article/details/gtepirxxon.html

【文件统计】
来源：http://dali.gogol.net.cn/Article/details/gtgbtdhxoe.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hnqzz.top/Article/details/gtpcfrfast.html

--------------------------------------------------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gtaezuqvwl.html

目  录
来源：http://dali.yanxiufei.cn/Article/details/gtspsncdao.html

--------------------------------------------------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gtikpnfnnf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjsemtje.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.sufxvd.cn/Article/details/gtfyccvwkl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.andypj.xyz/Article/details/gtgihlelsv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtpklgzjtk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hnxiangtu.top/Article/details/gtqjnbqllq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.guannengcc.top/Article/details/gtgpaijpth.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.sufxvd.cn/Article/details/gtjecidmva.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.svipenyu.cn/Article/details/gtultqtoqb.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gtvbfbsobf.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.fengsongda.top/Article/details/gtnijcmbax.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gtegxhtsim.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtuvertvjh.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yj20258888.top/Article/details/gtpugjjhis.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtbqktmvoc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hammf.cn/Article/details/gtibwfytdv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.wangdashe.top/Article/details/gtvffzyxet.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.redwolf501.top/Article/details/gtwghuxrwo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.9152youxi.cn/Article/details/gtftiolwzb.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtiylbpajw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dianchejie.cn/Article/details/gttszmwwct.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.andypj.xyz/Article/details/gtdsklwsfz.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gthfehilsg.html

A. 基础语法与类型
来源：http://dali.yuanzhike.top/Article/details/gtizzvpebm.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtqwlpwrlv.html

[A01] Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtdrgaennp.html

Py:   print("Hello, World!")
来源：http://dali.havefunace.top/Article/details/gtmqxpqmfr.html

PHP:  echo "Hello, World!";
来源：http://dali.fengsongda.top/Article/details/gtvcevmxgf.html

JS:   console.log("Hello, World!");
来源：http://dali.sweek.top/Article/details/gtvqqkhfrx.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jyoumei.cn/Article/details/gtqpheybss.html

Java: System.out.println("Hello, World!");
来源：http://dali.meibo888.top/Article/details/gtwgvcumoj.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.feifeiyinyue.top/Article/details/gthhxgvymi.html

Ruby: puts "Hello, World!"
来源：http://dali.feifeiyinyue.top/Article/details/gtgorzemxl.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hnqzz.top/Article/details/gtojvitaee.html

[A02] 变量声明与赋值
来源：http://dali.gaohongyu789.top/Article/details/gtchubfead.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvunkjvre.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.cheryme.top/Article/details/gtlefxrhlk.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.nanxuanxn.top/Article/details/gtquvpqxsv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xuetiantiany.cn/Article/details/gtdomljevj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xinyue.icu/Article/details/gtxqqfgdjy.html

Go:   name := "Alex"; age := 20
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwnpwscd.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhoulong.xyz/Article/details/gtlmgydmsy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.quarkkingdee.top/Article/details/gthqfjwbzj.html

[A03] 常量定义
来源：http://dali.yangfankeji.com/Article/details/gtfgqdhspn.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shuidangran.top/Article/details/gtperdzqwn.html

PHP:  const PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtqndzlsxq.html

JS:   const PI = 3.14159;
来源：http://dali.havefunace.top/Article/details/gtclubuwdg.html

TS:   const PI: number = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtyrilpwmr.html

Java: static final double PI = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gtpcuwlrbm.html

Go:   const PI = 3.14159
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbuolubef.html

Ruby: PI = 3.14159
来源：http://dali.gotoacloud.top/Article/details/gtaqebovji.html

C#:   const double PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpjsaxpu.html

[A04] 判断变量类型
来源：http://dali.birdmap.top/Article/details/gthqumoccb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xylfe.cn/Article/details/gtinzaczij.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yvedp.cn/Article/details/gtswwrtysb.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.tanke756.top/Article/details/gtsuolzwnp.html

TS:   typeof x; x instanceof Date
来源：http://dali.smart0.xyz/Article/details/gtrbmqndkv.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jqgufenzy.top/Article/details/gtshjfzpzj.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yonumen.top/Article/details/gtaoavaffg.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yj20258.top/Article/details/gtuesednnw.html

C#:   x.GetType().Name; x is int
来源：http://dali.yueranfly.top/Article/details/gtbhtngycv.html

[A05] 整数除法与取模
来源：http://dali.xylfe.cn/Article/details/gtatohkhdn.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.gaohongyu789.top/Article/details/gtvwfnspwy.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gteelvvzef.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.nwbrower.top/Article/details/gtgtejglih.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gthcyikpgj.html

Java: 7 / 2; 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtexjudtaw.html

Go:   7 / 2; 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gttnxaqorr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gtxpsvgrxo.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gtwzrarssm.html

[A06] 字符串转数字
来源：http://dali.zycfv.cn/Article/details/gtrqemthvr.html

Py:   int("42"); float("3.14")
来源：http://dali.haohaochexian.top/Article/details/gtegukcxqk.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.ppjwa.cn/Article/details/gtlclisttf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.birdmap.top/Article/details/gtnsgiihhu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hywenlv.cn/Article/details/gtpfjfdbvn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yanxiufei.cn/Article/details/gtxhmdyknj.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.mhx1999.top/Article/details/gtnueehnco.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.nwbrower.top/Article/details/gtargwbsyh.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.gotoacloud.top/Article/details/gthzowkvhl.html

[A07] 数字转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtvztnsbqv.html

Py:   str(42)
来源：http://dali.chenzaomai.com/Article/details/gttahomppz.html

PHP:  (string) 42; strval(42)
来源：http://dali.dianchejie.cn/Article/details/gtuisgwekf.html

JS:   String(42); (42).toString()
来源：http://dali.aizwys.cn/Article/details/gtqtoohwco.html

TS:   String(42)
来源：http://dali.nanxuanxn.top/Article/details/gtotqqgolb.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.shangyingyoupin.top/Article/details/gtqxywvezd.html

Go:   strconv.Itoa(42)
来源：http://dali.yonumen.top/Article/details/gtafynwrnr.html

Ruby: 42.to_s
来源：http://dali.jinqigufen.top/Article/details/gtyuxkbuic.html

C#:   42.ToString()
来源：http://dali.sweek.top/Article/details/gtozlpkddk.html

[A08] 取整与四舍五入
来源：http://dali.ydzc1.top/Article/details/gtfhilldyt.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.xylfe.cn/Article/details/gtbzlbuikn.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hnqzz.top/Article/details/gtuqsbdcos.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.cdnleiting.top/Article/details/gtkqhlnpof.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yongpay.top/Article/details/gtfvzdprez.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.cashguo.top/Article/details/gtcltnfcpj.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.c1oappe.top/Article/details/gtrdbhbjmo.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.vqdsnc.cn/Article/details/gtfehcyooi.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yj20258.top/Article/details/gtgkrzffma.html

[A09] 绝对值与最大最小值
来源：http://dali.hysaishi.cn/Article/details/gtpyldqpkv.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.aizwys.cn/Article/details/gtkrttfhyg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtkjtdgeee.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiagqdsbk.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtpxjrheki.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.pycfn.com/Article/details/gtliwrlwpd.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.dashuyun.cn/Article/details/gtridpsqda.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.pycfn.com/Article/details/gtjawomrjo.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtvygydzmn.html

[A10] 生成随机数
来源：http://dali.meibo888.top/Article/details/gtinnkwana.html

Py:   import random; random.randint(1, 100)
来源：http://dali.hfpthk.cn/Article/details/gtfcnudtbr.html

PHP:  random_int(1, 100);
来源：http://dali.wangshuangyany.cn/Article/details/gtghvkcyfw.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.0kj1m.cn/Article/details/gtokxjjzoa.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jqgfzy.top/Article/details/gthgmgbanb.html

Java: new Random().nextInt(100) + 1
来源：http://dali.vqdsnc.cn/Article/details/gtooiuxfah.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.xuanzx.com/Article/details/gtxxscrxeb.html

Ruby: rand(1..100)
来源：http://dali.jiagoushi.top/Article/details/gtqpihwggi.html

C#:   new Random().Next(1, 101)
来源：http://dali.jiagoushi.top/Article/details/gtyqzjepjg.html

[A11] 条件表达式（三元）
来源：http://dali.gotoacloud.top/Article/details/gtussjjtby.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.ehwqpu.com/Article/details/gtfweqqfux.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.wangdashe.top/Article/details/gtxdmyjpus.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.gotoacloud.top/Article/details/gteetqpswy.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.iojbl.cn/Article/details/gtbxzljess.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jinqigfzy.top/Article/details/gtookqmdzs.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.nanxuanxn.top/Article/details/gtecjcrypf.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.hnxiangtu.top/Article/details/gtkbzppkuf.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yonumen.top/Article/details/gttownksbg.html

[A12] 字符串插值 / 格式化
来源：http://dali.chenlongwang.top/Article/details/gttlnxepvq.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zycfv.cn/Article/details/gtpnexzivv.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.shuidangran.top/Article/details/gtonefcsmq.html

JS:   `Hello, ${name}!`
来源：http://dali.yj202588.top/Article/details/gtjwnxgilp.html

TS:   `Hello, ${name}!`
来源：http://dali.cdnleiting.top/Article/details/gtxsksoczn.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.wangshuangyany.cn/Article/details/gtwoonvnmz.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.birdmap.top/Article/details/gtzctyreen.html

Ruby: "Hello, #{name}!"
来源：http://dali.sysykeji.top/Article/details/gtxuckpcyb.html

C#:   $"Hello, {name}!"
来源：http://dali.jqgfzy.top/Article/details/gtkqagrmpj.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yvedp.cn/Article/details/gtdrjkrlni.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gtainmgrfl.html

PHP:  "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gtdpquxdmg.html

JS:   "第一行\n第二行"
来源：http://dali.haohaochexian.top/Article/details/gtbffbpeim.html

TS:   "第一行\n第二行"
来源：http://dali.zhoulong.xyz/Article/details/gtbqozlrlg.html

Java: "第一行\n第二行"
来源：http://dali.quarkkingdee.top/Article/details/gtuokimzkx.html

Go:   "第一行\n第二行"
来源：http://dali.jqgufenzy.top/Article/details/gtiytvudte.html

Ruby: "第一行\n第二行"
来源：http://dali.jinghuilouyu.cn/Article/details/gtjamuxwjn.html

C#:   "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gtepnicvkq.html

[A14] 注释写法
来源：http://dali.dianchejie.cn/Article/details/gthobijnkv.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.chenlongwang.top/Article/details/gteblwxawu.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.tanke756.top/Article/details/gtzrhkrodk.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxlhszrzp.html

TS:   // 单行；/* 多行 */
来源：http://dali.gogol.net.cn/Article/details/gtosnnsaue.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.quarkkingdee.top/Article/details/gtcbjlniez.html

Go:   // 单行；/* 多行 */
来源：http://dali.gogol.net.cn/Article/details/gtdjdtxjrt.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gtwmkdoebi.html

C#:   // 单行；/* 多行 */
来源：http://dali.nwbrower.top/Article/details/gtsumdyszs.html

[A15] 空值判断与默认值
来源：http://dali.zhongyouzk.top/Article/details/gtudoyjybf.html

Py:   value = data or "默认值"
来源：http://dali.iojbl.cn/Article/details/gtrsfqfqyt.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.kuanghao11.cn/Article/details/gtrwwafdej.html

JS:   const value = data ?? "默认值";
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcoktvxd.html

TS:   const value = data ?? "默认值";
来源：http://dali.cashguo.top/Article/details/gtgajjbmkz.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ybcxt.top/Article/details/gtidcpctps.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.c1oappe.top/Article/details/gtpgtkupra.html

Ruby: value = data || "默认值"
来源：http://dali.sufxvd.cn/Article/details/gtgpivtnhc.html

C#:   var value = data ?? "默认值";
来源：http://dali.shzxlz.cn/Article/details/gtvjjgbpyy.html

[A16] 真假值判断规则
来源：http://dali.jianghu66.top/Article/details/gtnbahgtpz.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zycfv.cn/Article/details/gtywcjveld.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yonumen.top/Article/details/gtaxkfjyaa.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.sysykeji.top/Article/details/gtsebfaouq.html

TS:   if (!x) {}
来源：http://dali.wangdashe.top/Article/details/gtltfygyqa.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.tian-w.cn/Article/details/gtjlehgpvk.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoyofmonk.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gtwvbangcj.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.xziqi.cn/Article/details/gtckuqxrzc.html

[A17] 位运算
来源：http://dali.9152youxi.cn/Article/details/gtehlyryhy.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aizwys.cn/Article/details/gtzqkysreb.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.cashguo.top/Article/details/gtjcfrqezk.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gthnzkhkvr.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.c1oappe.top/Article/details/gtlbxlfgdu.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258888.top/Article/details/gthmtwlixb.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdocfcdfq.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gtwoqbxqbk.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gtnorzlnbp.html


<!-- 参考信息 -->