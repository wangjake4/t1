代发 wailian999

[U99] JS：事件监听
来源：http://dali.jyoumei.cn/Article/details/gthgcegxyt.html

el.addEventListener("click", e => {})
来源：http://dali.smart0.xyz/Article/details/gtnhotztay.html

[U100] JS：DOM 查询
来源：http://dali.jiagoushi.top/Article/details/gtmohujtsa.html

document.querySelector(".item")
来源：http://dali.feifeiyinyue.top/Article/details/gtwzerntla.html

[U101] JS：classList 操作
来源：http://dali.jinqigfzy.top/Article/details/gtdwurbgcz.html

el.classList.toggle("active")
来源：http://dali.yuanzhike.top/Article/details/gtadhpmgeh.html

[U102] JS：本地存储
来源：http://dali.jinqigfzy.top/Article/details/gtsefyhywp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.mhx1999.top/Article/details/gtjmxflnns.html

[U103] JS：定时器
来源：http://dali.0kj1m.cn/Article/details/gteshewtuh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ydzc1.top/Article/details/gtjmlzbgdy.html

[U104] JS：防抖
来源：http://dali.jinqigfzy.top/Article/details/gtpvenlfgq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnxiangtu.top/Article/details/gtuwpxiklo.html

[U105] JS：节流
来源：http://dali.redwolf501.top/Article/details/gtkaxgmakv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.mhx1999.top/Article/details/gtopjkzler.html

[U106] JS：日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gtxgikrnte.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yanxiufei.cn/Article/details/gtxbowgmpp.html

[U107] JS：数字千分位
来源：http://dali.redwolf501.top/Article/details/gtbspwjzoy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hywenlv.cn/Article/details/gttzqwlbzq.html

[U108] JS：随机整数
来源：http://dali.pycfn.com/Article/details/gtkkvhcyvt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yanxiufei.cn/Article/details/gtzeybnuek.html

[U109] JS：数组分组
来源：http://dali.feifeiyinyue.top/Article/details/gttolzsvok.html

Object.groupBy(arr, x => x.type)
来源：http://dali.dianchejie.cn/Article/details/gtimlgkkho.html

[U110] JS：数组分块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhdoxujx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinqigfzy.top/Article/details/gtptxapvuv.html

[U111] JS：对象转 Map
来源：http://dali.yj20258888.top/Article/details/gtbovnsffa.html

new Map(Object.entries(obj))
来源：http://dali.tanke756.top/Article/details/gtfklvkzde.html

[U112] JS：字符串补位
来源：http://dali.yj20258.top/Article/details/gtyzhzhavb.html

"7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtafehtrdp.html

[U113] JS：正则替换全部
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdklyfgz.html

s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtzpossgfx.html

[U114] JS：JSON 深比较
来源：http://dali.smart0.xyz/Article/details/gtdgptqyzd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sxryk.cn/Article/details/gtnuaqmvhf.html

[U115] JS：生成 UUID
来源：http://dali.fzhhl.top/Article/details/gtuhnbnaft.html

crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gtvecfqref.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xuanzx.com/Article/details/gtfzmylcho.html

/** @param {string} name */ function f(name) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtwdttirhe.html

[U117] JS：单元测试
来源：http://dali.yanxiufei.cn/Article/details/gtslzedphm.html

npm i -D vitest;  npx vitest
来源：http://dali.ydzc1.top/Article/details/gtskmpxqei.html

[U118] JS：开发服务器
来源：http://dali.yuanzhike.top/Article/details/gtkwnylipi.html

npm i -D vite;  npx vite
来源：http://dali.fzhhl.top/Article/details/gtemqntgll.html

[U119] JS：生产构建
来源：http://dali.hammf.cn/Article/details/gtaetasawr.html

npx vite build
来源：http://dali.9152youxi.cn/Article/details/gtonwiqjjt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cqqwz.cn/Article/details/gtkecathaj.html

import.meta.env.VITE_API_URL
来源：http://dali.vqdsnc.cn/Article/details/gtpavxlpgy.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtbrzhnrak.html

统计汇总
来源：http://dali.daxiang520.top/Article/details/gtcrltslqg.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gthvrtpyig.html

按语言统计（条）：
来源：http://dali.nanxuanxn.top/Article/details/gtbatlhfld.html

Python ......... 252
来源：http://dali.yj20258888.top/Article/details/gtflcqtyqi.html

PHP ............ 252
来源：http://dali.nanxinkj.top/Article/details/gtgeoolgfo.html

JavaScript ..... 252
来源：http://dali.c1oappe.top/Article/details/gthlkiddwg.html

TypeScript ..... 212
来源：http://dali.yj202588.top/Article/details/gtbvqyckzg.html

Java ........... 212
来源：http://dali.shzxlz.cn/Article/details/gttjbqzrox.html

Go ............. 212
来源：http://dali.meibo888.top/Article/details/gtdiyojalw.html

Ruby ........... 212
来源：http://dali.jlsjyb.cn/Article/details/gtaojmbwmu.html

C# ............. 212
来源：http://dali.ydzc1.top/Article/details/gtvlwjmotz.html

C .............. 30
来源：http://dali.shzxlz.cn/Article/details/gtxoqqfwcj.html

C++ ............ 30
来源：http://dali.bjfxy.top/Article/details/gtybeqxqwx.html

SQL ............ 90
来源：http://dali.yj202588.top/Article/details/gttxfwjcii.html

Bash ........... 80
来源：http://dali.sweek.top/Article/details/gtqzrmvcqf.html

Kotlin ......... 15
来源：http://dali.jinqigfzy.top/Article/details/gtpqnedoyt.html

Swift .......... 15
来源：http://dali.zdqjudy.top/Article/details/gtgqhzrkek.html

Lua ............ 10
来源：http://dali.zhongyouzk.top/Article/details/gtvxebjrdp.html

Perl ........... 10
来源：http://dali.cdnleiting.top/Article/details/gtntncidow.html

Scala .......... 10
来源：http://dali.jqgfzy.top/Article/details/gthiwmfaaz.html

------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswkrzsrh.html

合计 ........... 2106 条
来源：http://dali.tanke756.top/Article/details/gtqcikhxzg.html

按章节统计：
来源：http://dali.birdmap.top/Article/details/gtkgykxhhk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.dianchejie.cn/Article/details/gtnqyrvqdo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.svipenyu.cn/Article/details/gtkaowwvfx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jlsjyb.cn/Article/details/gtirjiesdb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gtqzmckpgi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.aizwys.cn/Article/details/gttnjgchqz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yangfankeji.com/Article/details/gtzbdfxikh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jqgfzy.top/Article/details/gtlghbtycp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.chenjidiqi.icu/Article/details/gtifmbtxmt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gtxgokrfry.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zycfv.cn/Article/details/gtrbmixfmq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gtnuxkyqyc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gtkhkajbie.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdawdiwjk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gtlsvtkbgb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvkqrlbg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gttqkqvmyw.html

Q SQL 专题                              90
来源：http://dali.zhoulong.xyz/Article/details/gtytuipwrl.html

R Bash 专题                             80
来源：http://dali.xuetiantiany.cn/Article/details/gtuadfsaye.html

S C / C++ 专题                          60
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphwvrygl.html

T 其他语言补充                          60
来源：http://dali.zhongyouzk.top/Article/details/gtnqswlmry.html

U 高频实用片段                         120
来源：http://dali.yvedp.cn/Article/details/gtrbmpocam.html

------------------------------------
来源：http://dali.xuanzx.com/Article/details/gtxqjhiefc.html

合计                                  2106 条
来源：http://dali.jinqigfzy.top/Article/details/gtlabdcptc.html

--------------------------------------------------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gtlpykdzca.html

使用提醒
来源：http://dali.hfpthk.cn/Article/details/gtgryojvad.html

--------------------------------------------------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gtmfpgbhoh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.vqdsnc.cn/Article/details/gtaedxwubb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.birdmap.top/Article/details/gtwkcyonac.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yuxming.cn/Article/details/gtlbefgkpb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hfpthk.cn/Article/details/gtpgnzgmth.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zdqjudy.top/Article/details/gtajwnjwre.html

—— 文件结束 ——
来源：http://dali.shzxlz.cn/Article/details/gtrutiltuf.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtgscsxebg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.havefunace.top/Article/details/gtmbalkpnp.html

Common Programming Examples Cheat Book
来源：http://dali.jiagoushi.top/Article/details/gteofoevtc.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtdbhxhpfn.html

【收录内容】
来源：http://dali.yj20258.top/Article/details/gtkhhhvltp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.gotoacloud.top/Article/details/gtpqshugws.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yonumen.top/Article/details/gtibcboqff.html

SQL · Bash · C · C++
来源：http://dali.hammf.cn/Article/details/gtupgoulou.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yj20258888.top/Article/details/gtypqyivbj.html

【使用说明】
来源：http://dali.yuanzhike.top/Article/details/gtxfwpduzd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.quarkkingdee.top/Article/details/gtgtsvcmfr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.wangdashe.top/Article/details/gtkcyppzbl.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.fzhhl.top/Article/details/gthayrlnec.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.guannengcc.top/Article/details/gtzapuszac.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.svipenyu.cn/Article/details/gtiomigopl.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.tian-w.cn/Article/details/gtjozmtocd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.sxryk.cn/Article/details/gtmgtwiazo.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hywenlv.cn/Article/details/gtetaygymq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.guowangkeji.top/Article/details/gtomeidgck.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jqgufenzy.top/Article/details/gtzlzafpkp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.vqdsnc.cn/Article/details/gtifzgfijh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.feifeiyinyue.top/Article/details/gtebxohjsp.html

【文件统计】
来源：http://dali.sysykeji.top/Article/details/gtbtmirpuy.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yonumen.top/Article/details/gtkczuipap.html

--------------------------------------------------------------------------------
来源：http://dali.yuxming.cn/Article/details/gtxnawpggx.html

目  录
来源：http://dali.sufxvd.cn/Article/details/gtfpnbkmeh.html

--------------------------------------------------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtvrwukdgf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.9152youxi.cn/Article/details/gtaohhndeu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtgsetdhnh.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.wangdashe.top/Article/details/gtbhyarjoi.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.gogol.net.cn/Article/details/gtmtrwqukg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.316326.xyz/Article/details/gtinslbvlu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jqgufenzy.top/Article/details/gtbwgvzatr.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.tanke756.top/Article/details/gttajlbvyg.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jianghu66.top/Article/details/gtyhyspqgn.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ydzc1.top/Article/details/gtqgcmtcky.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmvqeflw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gtmppzdkji.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gthspnaydc.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jyoumei.cn/Article/details/gtqnkaggyw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jqgufenzy.top/Article/details/gtvincdrpa.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hnxiangtu.top/Article/details/gthdguungp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gtiqznlwcd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.andypj.xyz/Article/details/gtvudsuidu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.guowangkeji.top/Article/details/gtyjublnoc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yonumen.top/Article/details/gtklrghdoq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenlongwang.top/Article/details/gtwopjbvzs.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.snrcjt.cn/Article/details/gtagrgdaet.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtjrynxzjf.html

A. 基础语法与类型
来源：http://dali.andypj.xyz/Article/details/gtlkjfluwj.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtcdzshltp.html

[A01] Hello World
来源：http://dali.tanke756.top/Article/details/gtxxxfubib.html

Py:   print("Hello, World!")
来源：http://dali.aizwys.cn/Article/details/gtysansvpc.html

PHP:  echo "Hello, World!";
来源：http://dali.xylfe.cn/Article/details/gtaexlokad.html

JS:   console.log("Hello, World!");
来源：http://dali.chenjidiqi.icu/Article/details/gtenbasvwp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.pycfn.com/Article/details/gtntyehhch.html

Java: System.out.println("Hello, World!");
来源：http://dali.aizwys.cn/Article/details/gtqtgzqwty.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.haohaochexian.top/Article/details/gtlzetrqga.html

Ruby: puts "Hello, World!"
来源：http://dali.jqgfzy.top/Article/details/gtckeiftzf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.gzhubu.top/Article/details/gtsshwyjfn.html

[A02] 变量声明与赋值
来源：http://dali.jyoumei.cn/Article/details/gttmuqruak.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jianghu66.top/Article/details/gtxrdimdav.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xuanzx.com/Article/details/gtdkqzzggy.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hysaishi.cn/Article/details/gtxvmccaio.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.sweek.top/Article/details/gtwcjsdxrm.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yangfankeji.com/Article/details/gtdsudotln.html

Go:   name := "Alex"; age := 20
来源：http://dali.yuanzhike.top/Article/details/gtlevszmsh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yvedp.cn/Article/details/gtpipmtpbo.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.bjfxy.top/Article/details/gtoiusiump.html

[A03] 常量定义
来源：http://dali.jlsjyb.cn/Article/details/gtehvbqkgb.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgwaulnx.html

PHP:  const PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtmhekeqlt.html

JS:   const PI = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtatxlyqpp.html

TS:   const PI: number = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtupqfzxrm.html

Java: static final double PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtmgrushln.html

Go:   const PI = 3.14159
来源：http://dali.quarkkingdee.top/Article/details/gtoroaonjp.html

Ruby: PI = 3.14159
来源：http://dali.sufxvd.cn/Article/details/gtfbgqicdf.html

C#:   const double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtabufaeck.html

[A04] 判断变量类型
来源：http://dali.gzhubu.top/Article/details/gttzineaoe.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yueranfly.top/Article/details/gtotzhwvmh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.pycfn.com/Article/details/gtbknrxmtf.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xuetiantiany.cn/Article/details/gtllxayyyw.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfapihcy.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ehwqpu.com/Article/details/gtzubikhhx.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jiagoushi.top/Article/details/gtxcmcjehy.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttsigceet.html

C#:   x.GetType().Name; x is int
来源：http://dali.xylfe.cn/Article/details/gtdjachbvr.html

[A05] 整数除法与取模
来源：http://dali.yuxming.cn/Article/details/gtbqzxetug.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.meibo888.top/Article/details/gtrvzbvxag.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.sxryk.cn/Article/details/gtciymdguh.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtqpcxemmn.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gtljtaonyb.html

Java: 7 / 2; 7 % 2
来源：http://dali.havefunace.top/Article/details/gtyxqczrbb.html

Go:   7 / 2; 7 % 2
来源：http://dali.guannengcc.top/Article/details/gtwwmhnlkm.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtxkoyfaec.html

C#:   7 / 2; 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gtclhkdngy.html

[A06] 字符串转数字
来源：http://dali.cucudq.cn/Article/details/gtbqsyhmki.html

Py:   int("42"); float("3.14")
来源：http://dali.feifeiyinyue.top/Article/details/gtxvtiouoa.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yongpay.top/Article/details/gtmkteppci.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.dashuyun.cn/Article/details/gtcxtsweef.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jqgfzy.top/Article/details/gtfuzuizpm.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jinqigufen.top/Article/details/gtmcloasuj.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yuxming.cn/Article/details/gttrqtvryl.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yuanzhike.top/Article/details/gtcczonmib.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.sysykeji.top/Article/details/gterxpesys.html

[A07] 数字转字符串
来源：http://dali.xziqi.cn/Article/details/gtqocmaeeu.html

Py:   str(42)
来源：http://dali.xuanzx.com/Article/details/gtngstimyz.html

PHP:  (string) 42; strval(42)
来源：http://dali.shangyingyoupin.top/Article/details/gtnhcxcany.html

JS:   String(42); (42).toString()
来源：http://dali.hnqzz.top/Article/details/gtxhfrbzqb.html

TS:   String(42)
来源：http://dali.yongpay.top/Article/details/gtqrhiadgq.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.chenlongwang.top/Article/details/gtlumisuoq.html

Go:   strconv.Itoa(42)
来源：http://dali.sysykeji.top/Article/details/gtsmeuqmnx.html

Ruby: 42.to_s
来源：http://dali.sysykeji.top/Article/details/gtbvccsbrl.html

C#:   42.ToString()
来源：http://dali.tian-w.cn/Article/details/gtblplxjhw.html

[A08] 取整与四舍五入
来源：http://dali.yongpay.top/Article/details/gtlibclqqd.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ehwqpu.com/Article/details/gtezfdxtax.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.wangdashe.top/Article/details/gtojrrhwes.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jyoumei.cn/Article/details/gtvywrivrb.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjlbxwoon.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhengqikj.top/Article/details/gtqgxclrqw.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yanxiufei.cn/Article/details/gtsuiiqhku.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.ybcxt.top/Article/details/gtxsifgnpr.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.wangdashe.top/Article/details/gtivooflew.html

[A09] 绝对值与最大最小值
来源：http://dali.hammf.cn/Article/details/gtuwncbkur.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtnhvvdoqq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gtrnhyxeot.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gtezwjjgpk.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yuxming.cn/Article/details/gtwgzwblmf.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtqcnjxuxk.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.sweek.top/Article/details/gthkkltncm.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.birdmap.top/Article/details/gtchoieyjj.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtruepgftn.html

[A10] 生成随机数
来源：http://dali.zhixingplan.top/Article/details/gtokvajsvh.html

Py:   import random; random.randint(1, 100)
来源：http://dali.andypj.xyz/Article/details/gtnluwhaxh.html

PHP:  random_int(1, 100);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgdvnarj.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shuidangran.top/Article/details/gtwpiylwsj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.nanxinkj.top/Article/details/gtynofsldg.html

Java: new Random().nextInt(100) + 1
来源：http://dali.hywenlv.cn/Article/details/gtirqbkoxj.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jianghu66.top/Article/details/gtghpdoxad.html

Ruby: rand(1..100)
来源：http://dali.feifeiyinyue.top/Article/details/gtticxndjn.html

C#:   new Random().Next(1, 101)
来源：http://dali.daria6918.cn/Article/details/gtumpjionw.html

[A11] 条件表达式（三元）
来源：http://dali.fzhhl.top/Article/details/gtimqkyezi.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.nanxuanxn.top/Article/details/gtfbhwsmeb.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.pycfn.com/Article/details/gtxuwdzprt.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.nanxuanxn.top/Article/details/gtxdopvjbn.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.c1oappe.top/Article/details/gtjluyyjpb.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gtgjppzaqd.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.aibaodan.cn/Article/details/gtesphobau.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.gzhubu.top/Article/details/gtjualognz.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.snrcjt.cn/Article/details/gtpsqrjkhe.html

[A12] 字符串插值 / 格式化
来源：http://dali.guannengcc.top/Article/details/gtxxwayznr.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.guannengcc.top/Article/details/gtullzqavb.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.cheryme.top/Article/details/gttvtefhfi.html

JS:   `Hello, ${name}!`
来源：http://dali.xuetiantiany.cn/Article/details/gtdmjvlisa.html

TS:   `Hello, ${name}!`
来源：http://dali.cucudq.cn/Article/details/gtdzzbmokd.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.nanxinkj.top/Article/details/gtcdsrwffh.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.daxiang520.top/Article/details/gtxvbjrnqk.html

Ruby: "Hello, #{name}!"
来源：http://dali.xuetiantiany.cn/Article/details/gtfjzqhjak.html

C#:   $"Hello, {name}!"
来源：http://dali.meibo888.top/Article/details/gtlzzpettc.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yuanzhike.top/Article/details/gtgmlpbyln.html

Py:   "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gtivcjmqso.html

PHP:  "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gtgqcwwdrn.html

JS:   "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gtepktcfqs.html

TS:   "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkzmenho.html

Java: "第一行\n第二行"
来源：http://dali.andypj.xyz/Article/details/gthkanlrzw.html

Go:   "第一行\n第二行"
来源：http://dali.chenlongwang.top/Article/details/gtwdcnrksu.html

Ruby: "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gtdlzcffjr.html

C#:   "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gtxgsbfvpe.html

[A14] 注释写法
来源：http://dali.nanxuanxn.top/Article/details/gtfipbqrze.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.sxryk.cn/Article/details/gtgpjnzlml.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.hnqzz.top/Article/details/gtsqhnnhos.html

JS:   // 单行；/* 多行 */
来源：http://dali.daria6918.cn/Article/details/gtgkpoptlj.html

TS:   // 单行；/* 多行 */
来源：http://dali.chenjidiqi.icu/Article/details/gtuuzrektb.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jiagoushi.top/Article/details/gtaqxoohph.html

Go:   // 单行；/* 多行 */
来源：http://dali.yangfankeji.com/Article/details/gtjkxwtqdy.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjwdyzbw.html

C#:   // 单行；/* 多行 */
来源：http://dali.hfpthk.cn/Article/details/gthofcdrlh.html

[A15] 空值判断与默认值
来源：http://dali.birdmap.top/Article/details/gtllevleai.html

Py:   value = data or "默认值"
来源：http://dali.guowangkeji.top/Article/details/gtluquyzqm.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yanxiufei.cn/Article/details/gtlapmdiig.html

JS:   const value = data ?? "默认值";
来源：http://dali.aizwys.cn/Article/details/gtentpuptn.html

TS:   const value = data ?? "默认值";
来源：http://dali.xinyue.icu/Article/details/gtzoxleuhy.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.wangdashe.top/Article/details/gtjvbsgwgs.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.vqdsnc.cn/Article/details/gtdpbgjeuk.html

Ruby: value = data || "默认值"
来源：http://dali.vqdsnc.cn/Article/details/gtiflbxlmf.html

C#:   var value = data ?? "默认值";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahahhdor.html

[A16] 真假值判断规则
来源：http://dali.jinqigufen.top/Article/details/gtdauzihrv.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.gzhubu.top/Article/details/gtcmuogyfr.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gtemwzsoqv.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.aizwys.cn/Article/details/gtucrthrpt.html

TS:   if (!x) {}
来源：http://dali.xylfe.cn/Article/details/gtacpwyfla.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtzzsoyvwy.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zdqjudy.top/Article/details/gtpyupswzc.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.wangdashe.top/Article/details/gtrilhkxgs.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.aizwys.cn/Article/details/gtjckqynvb.html

[A17] 位运算
来源：http://dali.zhiwuduotai.top/Article/details/gtplpqeljs.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkubsqfo.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.ehwqpu.com/Article/details/gtmgigiysi.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dashuyun.cn/Article/details/gtsxyolzqi.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yongpay.top/Article/details/gtcaaxkcnh.html


<!-- 参考信息 -->