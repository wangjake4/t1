代发 wailian999

[U103] JS：定时器
来源：http://dali.birdmap.top/Article/details/gtixwzidmc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sysykeji.top/Article/details/gteakgusdn.html

[U104] JS：防抖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxamxwdj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gthenuufca.html

[U105] JS：节流
来源：http://dali.yj202588.top/Article/details/gtsfiyjcnr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.bjfxy.top/Article/details/gthchmkikb.html

[U106] JS：日期格式化
来源：http://dali.yj20258888.top/Article/details/gtvvaiaftc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinghuilouyu.cn/Article/details/gtyaceegzg.html

[U107] JS：数字千分位
来源：http://dali.tian-w.cn/Article/details/gteaxovwks.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ivvv.top/Article/details/gtpczoigyy.html

[U108] JS：随机整数
来源：http://dali.xylfe.cn/Article/details/gtsoxnwyri.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhengqikj.top/Article/details/gtrbmhpksl.html

[U109] JS：数组分组
来源：http://dali.hnqzz.top/Article/details/gtqddmekdv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gtogvunsdu.html

[U110] JS：数组分块
来源：http://dali.quarkkingdee.top/Article/details/gtxkrhflvw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ydzc1.top/Article/details/gtikkbotij.html

[U111] JS：对象转 Map
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibqgpgwo.html

new Map(Object.entries(obj))
来源：http://dali.nwbrower.top/Article/details/gtdhnortue.html

[U112] JS：字符串补位
来源：http://dali.jyoumei.cn/Article/details/gtrfnfpizu.html

"7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtsxjegncl.html

[U113] JS：正则替换全部
来源：http://dali.yangfankeji.com/Article/details/gtvrlrrdad.html

s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtgihnukja.html

[U114] JS：JSON 深比较
来源：http://dali.jqgufenzy.top/Article/details/gtlvglbugh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hywenlv.cn/Article/details/gtrmlyovyi.html

[U115] JS：生成 UUID
来源：http://dali.birdmap.top/Article/details/gtsermoyet.html

crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gthszzoilt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.redwolf501.top/Article/details/gtxaklblhc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.havefunace.top/Article/details/gtwdbtlqqr.html

[U117] JS：单元测试
来源：http://dali.aibaodan.cn/Article/details/gtcbfbswyp.html

npm i -D vitest;  npx vitest
来源：http://dali.jqgufenzy.top/Article/details/gtoprytpxe.html

[U118] JS：开发服务器
来源：http://dali.gzhubu.top/Article/details/gtmchzbdpv.html

npm i -D vite;  npx vite
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkcjksys.html

[U119] JS：生产构建
来源：http://dali.pengpengdd.cyou/Article/details/gtfygkfhuy.html

npx vite build
来源：http://dali.nanxuanxn.top/Article/details/gttcfmpolu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.redwolf501.top/Article/details/gtmrjcarxb.html

import.meta.env.VITE_API_URL
来源：http://dali.daria6918.cn/Article/details/gtcgmshzyz.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtpfikdadg.html

统计汇总
来源：http://dali.aibaodan.cn/Article/details/gttrxjkjha.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtazmhvffl.html

按语言统计（条）：
来源：http://dali.vqdsnc.cn/Article/details/gtbdchjyfb.html

Python ......... 252
来源：http://dali.pycfn.com/Article/details/gtzwebyggn.html

PHP ............ 252
来源：http://dali.hywenlv.cn/Article/details/gtfggikgpc.html

JavaScript ..... 252
来源：http://dali.quarkkingdee.top/Article/details/gtfhzfbvji.html

TypeScript ..... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtighbrcnb.html

Java ........... 212
来源：http://dali.tian-w.cn/Article/details/gthyfxhvyq.html

Go ............. 212
来源：http://dali.ybcxt.top/Article/details/gtulztgpml.html

Ruby ........... 212
来源：http://dali.xuanzx.com/Article/details/gtvpnwttvh.html

C# ............. 212
来源：http://dali.yueranfly.top/Article/details/gthausqwfb.html

C .............. 30
来源：http://dali.svipenyu.cn/Article/details/gtohzpubxb.html

C++ ............ 30
来源：http://dali.yj20258888.top/Article/details/gtgppzputo.html

SQL ............ 90
来源：http://dali.hfpthk.cn/Article/details/gtmdcqnjwf.html

Bash ........... 80
来源：http://dali.yuanzhike.top/Article/details/gtvwhvudbr.html

Kotlin ......... 15
来源：http://dali.zhiwuduotai.top/Article/details/gtetwfduzp.html

Swift .......... 15
来源：http://dali.hysaishi.cn/Article/details/gtnyrfvihu.html

Lua ............ 10
来源：http://dali.andypj.xyz/Article/details/gtvggqyzfc.html

Perl ........... 10
来源：http://dali.andypj.xyz/Article/details/gtzmzqhbua.html

Scala .......... 10
来源：http://dali.chenzaomai.com/Article/details/gtismehjkl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gtlbfcamyr.html

合计 ........... 2106 条
来源：http://dali.wangshuangyany.cn/Article/details/gtdtxflyjt.html

按章节统计：
来源：http://dali.yangfankeji.com/Article/details/gtzxgzfmqc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhongyouzk.top/Article/details/gtoxuiiwcz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.fzhhl.top/Article/details/gtfvxjhaxu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ehwqpu.com/Article/details/gthagwbmfs.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hywenlv.cn/Article/details/gthdsmcsud.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.dashuyun.cn/Article/details/gtzrpwugix.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.snrcjt.cn/Article/details/gtuwtqofag.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.bjfxy.top/Article/details/gtwydschky.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.chenzaomai.com/Article/details/gtpetuvhmh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gtlksxfxlv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.sweek.top/Article/details/gtnzdomrqu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gtpzxtaokg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gtiiieloip.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gtcshjknvi.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.chenjidiqi.icu/Article/details/gtsnfmjcut.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.quarkkingdee.top/Article/details/gtuajprgmg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gtsfjhvlnh.html

Q SQL 专题                              90
来源：http://dali.dianchejie.cn/Article/details/gtmboqttus.html

R Bash 专题                             80
来源：http://dali.hongshengwenyu.top/Article/details/gtxezhwjhh.html

S C / C++ 专题                          60
来源：http://dali.jinqigufen.top/Article/details/gtnyemjpbi.html

T 其他语言补充                          60
来源：http://dali.xylfe.cn/Article/details/gtajmuhxej.html

U 高频实用片段                         120
来源：http://dali.birdmap.top/Article/details/gtxcwbhiga.html

------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gtdodjtjtc.html

合计                                  2106 条
来源：http://dali.nanxuanxn.top/Article/details/gtmyapobhj.html

--------------------------------------------------------------------------------
来源：http://dali.ydzc1.top/Article/details/gtkxkakdii.html

使用提醒
来源：http://dali.jinghuilouyu.cn/Article/details/gtrrymjmmq.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258.top/Article/details/gteywsspyr.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.dianchejie.cn/Article/details/gtvzyvoaxq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.sufxvd.cn/Article/details/gtvzflikny.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.snrcjt.cn/Article/details/gtygbbhdmb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yangfankeji.com/Article/details/gtverywywm.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhixingplan.top/Article/details/gtiqhdwiid.html

—— 文件结束 ——
来源：http://dali.fzhhl.top/Article/details/gtqptifonm.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtqurfifle.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.gaohongyu789.top/Article/details/gtxinfxzvu.html

Common Programming Examples Cheat Book
来源：http://dali.dashuyun.cn/Article/details/gtcnhqejft.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtyaesfyey.html

【收录内容】
来源：http://dali.hysaishi.cn/Article/details/gtqvhwmqki.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zycfv.cn/Article/details/gtpcxdsoai.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cashguo.top/Article/details/gtjwjiflao.html

SQL · Bash · C · C++
来源：http://dali.haohaochexian.top/Article/details/gtwsnolthy.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yuxming.cn/Article/details/gtmwrhwesy.html

【使用说明】
来源：http://dali.svipenyu.cn/Article/details/gttjezzkhq.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ivvv.top/Article/details/gtqbcklzgw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.gzhubu.top/Article/details/gtsugggbxq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.pycfn.com/Article/details/gtzdedphcz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ydzc1.top/Article/details/gthnfynsam.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.cqqwz.cn/Article/details/gttvlfonti.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.gotoacloud.top/Article/details/gthjhggmtc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yongpay.top/Article/details/gtkwjobwqg.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.tianlin.xyz/Article/details/gthlmgtvrq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ydzc1.top/Article/details/gtbzmxzzoc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shzxlz.cn/Article/details/gtxjccgoxk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.aizwys.cn/Article/details/gtrmklejjj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jiagoushi.top/Article/details/gtpbkvjflo.html

【文件统计】
来源：http://dali.jianghu66.top/Article/details/gtgxbygznc.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ppjwa.cn/Article/details/gtmyuikzqi.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gtnldmilvd.html

目  录
来源：http://dali.svipenyu.cn/Article/details/gtzdkazsqo.html

--------------------------------------------------------------------------------
来源：http://dali.yj202588.top/Article/details/gtrfcfrvet.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.aibaodan.cn/Article/details/gtlodhplck.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yongpay.top/Article/details/gtsosqysoz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yongpay.top/Article/details/gtceajnygp.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hnqzz.top/Article/details/gtubnsqhrx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yangfankeji.com/Article/details/gtauivqbqz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtynxemulq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.sxryk.cn/Article/details/gtogvoxgfp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.dashuyun.cn/Article/details/gtrgelsray.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gtvyxojrzb.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtkyleeftg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gthwucdfss.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.chenzaomai.com/Article/details/gtwrkojmdx.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gtqwpksfhh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.dianchejie.cn/Article/details/gtxuuqxqmp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.aizwys.cn/Article/details/gtnnaucbeo.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.ehwqpu.com/Article/details/gtibbpwdci.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.nanxinkj.top/Article/details/gtmgqkejof.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.svipenyu.cn/Article/details/gtqbusfqtv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.cucudq.cn/Article/details/gthohkgzud.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258888.top/Article/details/gtrylcxtch.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.c1oappe.top/Article/details/gtbsmkbzor.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtvdbeeeez.html

A. 基础语法与类型
来源：http://dali.zhongyouzk.top/Article/details/gtgkxrdghr.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtpzqboahb.html

[A01] Hello World
来源：http://dali.gzhubu.top/Article/details/gtasmqrssv.html

Py:   print("Hello, World!")
来源：http://dali.snrcjt.cn/Article/details/gtwlljvnul.html

PHP:  echo "Hello, World!";
来源：http://dali.snrcjt.cn/Article/details/gttxbvqcuc.html

JS:   console.log("Hello, World!");
来源：http://dali.meibo888.top/Article/details/gtvemnffva.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.chenlongwang.top/Article/details/gtpfrfxquw.html

Java: System.out.println("Hello, World!");
来源：http://dali.chenzaomai.com/Article/details/gtgnnwzzmr.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhoulong.xyz/Article/details/gtdmeskqof.html

Ruby: puts "Hello, World!"
来源：http://dali.jqgufenzy.top/Article/details/gtoiojqtpf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.fengsongda.top/Article/details/gtvkftbfjo.html

[A02] 变量声明与赋值
来源：http://dali.chenjidiqi.icu/Article/details/gtmblfmoxu.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.kuanghao11.cn/Article/details/gtqlqamhvt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jyoumei.cn/Article/details/gtzyduknme.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.aizwys.cn/Article/details/gtrqvwbxui.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.chenzaomai.com/Article/details/gtmkdtwgma.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.mhx1999.top/Article/details/gtmsyplfry.html

Go:   name := "Alex"; age := 20
来源：http://dali.haohaochexian.top/Article/details/gtcorkpoia.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yanxiufei.cn/Article/details/gtgdyhmoid.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yj20258.top/Article/details/gtarayiztq.html

[A03] 常量定义
来源：http://dali.c1oappe.top/Article/details/gtdblaymly.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.chenjidiqi.icu/Article/details/gtnypzxmsy.html

PHP:  const PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtwcjtfhdg.html

JS:   const PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtchydfuyd.html

TS:   const PI: number = 3.14159;
来源：http://dali.yonumen.top/Article/details/gttuakocqy.html

Java: static final double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtcmyrtpyi.html

Go:   const PI = 3.14159
来源：http://dali.zhongyouzk.top/Article/details/gtljhknpuf.html

Ruby: PI = 3.14159
来源：http://dali.jqgfzy.top/Article/details/gtmcwidrsc.html

C#:   const double PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gttroqxjrh.html

[A04] 判断变量类型
来源：http://dali.zhoulong.xyz/Article/details/gtfvwrnier.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hammf.cn/Article/details/gtultcudbl.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgyhbtlji.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.daxiang520.top/Article/details/gtvntgwhuk.html

TS:   typeof x; x instanceof Date
来源：http://dali.nanxinkj.top/Article/details/gttxkahcyf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xuanzx.com/Article/details/gtllrfkonc.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.c1oappe.top/Article/details/gtqtmxcxje.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ybcxt.top/Article/details/gtrsmyprde.html

C#:   x.GetType().Name; x is int
来源：http://dali.ydzc1.top/Article/details/gtpaqtlsgi.html

[A05] 整数除法与取模
来源：http://dali.haohaochexian.top/Article/details/gtzmfewxba.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.hongshengwenyu.top/Article/details/gtqyeubdre.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gteuwempvn.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gtacbnmiel.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.redwolf501.top/Article/details/gtjhgriunr.html

Java: 7 / 2; 7 % 2
来源：http://dali.andypj.xyz/Article/details/gtdehudkij.html

Go:   7 / 2; 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gtvjcvbbhg.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yonumen.top/Article/details/gtkhfeooub.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhoulong.xyz/Article/details/gtsqlmrwxm.html

[A06] 字符串转数字
来源：http://dali.daria6918.cn/Article/details/gtecghmxup.html

Py:   int("42"); float("3.14")
来源：http://dali.cashguo.top/Article/details/gtbzqcgrvq.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jyoumei.cn/Article/details/gtvwxsejff.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yonumen.top/Article/details/gtngjhyguu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcijszcue.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.daria6918.cn/Article/details/gtbmbmgcnd.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.snrcjt.cn/Article/details/gtmsvheglb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yvedp.cn/Article/details/gtimttlykn.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.aizwys.cn/Article/details/gtngkiughy.html

[A07] 数字转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtusnzjgjv.html

Py:   str(42)
来源：http://dali.nanxinkj.top/Article/details/gtidljcwke.html

PHP:  (string) 42; strval(42)
来源：http://dali.jianghu66.top/Article/details/gtwccqxhyu.html

JS:   String(42); (42).toString()
来源：http://dali.tanke756.top/Article/details/gtentiwmsw.html

TS:   String(42)
来源：http://dali.gaohongyu789.top/Article/details/gtrtxfgikw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.tianlin.xyz/Article/details/gtzhuafbti.html

Go:   strconv.Itoa(42)
来源：http://dali.birdmap.top/Article/details/gtjwpegrmi.html

Ruby: 42.to_s
来源：http://dali.0kj1m.cn/Article/details/gtvrkbanib.html

C#:   42.ToString()
来源：http://dali.c1oappe.top/Article/details/gtucwjrkdg.html

[A08] 取整与四舍五入
来源：http://dali.jlsjyb.cn/Article/details/gtjlcsbmqf.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hnxiangtu.top/Article/details/gtapnxrplg.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.meibo888.top/Article/details/gtdcjkuhii.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yuanzhike.top/Article/details/gtpztbxyso.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.quarkkingdee.top/Article/details/gtupeksnpf.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.chenjidiqi.icu/Article/details/gtbgflolqv.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gthkopkxcz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.ydzc1.top/Article/details/gtklenjjbs.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.tian-w.cn/Article/details/gtugescofj.html

[A09] 绝对值与最大最小值
来源：http://dali.tianlin.xyz/Article/details/gtyjfflhjl.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gthylwtzyb.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtrzcvvozo.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gtddjsegnx.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hnqzz.top/Article/details/gtvxameshi.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.daria6918.cn/Article/details/gttntkekkx.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.iojbl.cn/Article/details/gtljpfiosh.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.cheryme.top/Article/details/gtauejhbtf.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtxtpywfoi.html

[A10] 生成随机数
来源：http://dali.quarkkingdee.top/Article/details/gtzcpreyae.html

Py:   import random; random.randint(1, 100)
来源：http://dali.gzhubu.top/Article/details/gtsplbowav.html

PHP:  random_int(1, 100);
来源：http://dali.wangshuangyany.cn/Article/details/gtqqlmxjnw.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.quarkkingdee.top/Article/details/gtqisyqedn.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ybcxt.top/Article/details/gtezcrsdin.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yuanzhike.top/Article/details/gtdxmlznpi.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yj202588.top/Article/details/gtxvpkqpqe.html

Ruby: rand(1..100)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgradztfz.html

C#:   new Random().Next(1, 101)
来源：http://dali.sysykeji.top/Article/details/gtktkbhvac.html

[A11] 条件表达式（三元）
来源：http://dali.svipenyu.cn/Article/details/gtkzkwfiux.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhiwuduotai.top/Article/details/gtttnunpwj.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.feifeiyinyue.top/Article/details/gtdpnqplto.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.daria6918.cn/Article/details/gtaxopyqaj.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.feifeiyinyue.top/Article/details/gtccxvfatq.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.iojbl.cn/Article/details/gttgficupi.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.birdmap.top/Article/details/gtnltuvtax.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.nanxinkj.top/Article/details/gtpvzhzedt.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.hnxiangtu.top/Article/details/gtyxjygomx.html

[A12] 字符串插值 / 格式化
来源：http://dali.havefunace.top/Article/details/gtqzjpnzyf.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.xylfe.cn/Article/details/gtyspoyuxh.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.chenzaomai.com/Article/details/gteojmbuuj.html

JS:   `Hello, ${name}!`
来源：http://dali.cqqwz.cn/Article/details/gtlqjaswvt.html

TS:   `Hello, ${name}!`
来源：http://dali.chenjidiqi.icu/Article/details/gtrvjjbqzp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.snrcjt.cn/Article/details/gtkongbwow.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.chenjidiqi.icu/Article/details/gthfgznhbu.html

Ruby: "Hello, #{name}!"
来源：http://dali.jiagoushi.top/Article/details/gttstdbhng.html

C#:   $"Hello, {name}!"
来源：http://dali.vqdsnc.cn/Article/details/gtecisijqs.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.gaohongyu789.top/Article/details/gtlijazypj.html

Py:   "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gtfxenzeka.html

PHP:  "第一行\n第二行"
来源：http://dali.andypj.xyz/Article/details/gtdryapbul.html

JS:   "第一行\n第二行"
来源：http://dali.jinqigufen.top/Article/details/gtxhjcojxa.html

TS:   "第一行\n第二行"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlydrvke.html

Java: "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gtxbmdaais.html

Go:   "第一行\n第二行"
来源：http://dali.xylfe.cn/Article/details/gtujnmovcn.html

Ruby: "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gtxcjuhyvw.html

C#:   "第一行\n第二行"
来源：http://dali.yueranfly.top/Article/details/gtessieiqu.html

[A14] 注释写法
来源：http://dali.hnxiangtu.top/Article/details/gtmmnknkds.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhixingplan.top/Article/details/gtnitakvko.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jiagoushi.top/Article/details/gtrzsazuwj.html

JS:   // 单行；/* 多行 */
来源：http://dali.nwbrower.top/Article/details/gtxxcsznih.html

TS:   // 单行；/* 多行 */
来源：http://dali.zycfv.cn/Article/details/gtfyzmhnlr.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.tanke756.top/Article/details/gthrzbmght.html

Go:   // 单行；/* 多行 */
来源：http://dali.wangdashe.top/Article/details/gtjumgsumj.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.smart0.xyz/Article/details/gtvbzrnqjo.html

C#:   // 单行；/* 多行 */
来源：http://dali.havefunace.top/Article/details/gtvcniwrag.html

[A15] 空值判断与默认值
来源：http://dali.nwbrower.top/Article/details/gtvuaehkwb.html

Py:   value = data or "默认值"
来源：http://dali.cdnleiting.top/Article/details/gtjiewhpxm.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.daxiang520.top/Article/details/gtlzmbhvfz.html

JS:   const value = data ?? "默认值";
来源：http://dali.dianchejie.cn/Article/details/gtmyvzqbqe.html

TS:   const value = data ?? "默认值";
来源：http://dali.meibo888.top/Article/details/gttkynqmje.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhongyouzk.top/Article/details/gtjnhivyhj.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.mhx1999.top/Article/details/gtitwxkeup.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gtkgyktysu.html

C#:   var value = data ?? "默认值";
来源：http://dali.aizwys.cn/Article/details/gtxnejlfeq.html

[A16] 真假值判断规则
来源：http://dali.bjfxy.top/Article/details/gtcnfmwole.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gtdhxcvpnh.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.haohaochexian.top/Article/details/gtbmgtdxuv.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zycfv.cn/Article/details/gtpkkbrrgr.html

TS:   if (!x) {}
来源：http://dali.aizwys.cn/Article/details/gthfbwfikv.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jinqigfzy.top/Article/details/gtczisqfmb.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.svipenyu.cn/Article/details/gttbowrshs.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.redwolf501.top/Article/details/gtbudbrdvb.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yuxming.cn/Article/details/gtzrsynycw.html

[A17] 位运算
来源：http://dali.sweek.top/Article/details/gttmzagvzf.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jlsjyb.cn/Article/details/gtqadmojbh.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.fengsongda.top/Article/details/gthiuqqlmz.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtyvjefebl.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gteftmalsx.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gtqkyockvo.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtswhsxo.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fengsongda.top/Article/details/gtdterqtev.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ydzc1.top/Article/details/gtrzpbvglj.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hywenlv.cn/Article/details/gteiofevex.html

Py:   ord("A"); chr(65)
来源：http://dali.chenzaomai.com/Article/details/gtbpyeavhw.html

PHP:  ord("A"); chr(65)
来源：http://dali.jyoumei.cn/Article/details/gtfhjeycxo.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhengqikj.top/Article/details/gtdvhawzxc.html


<!-- 参考信息 -->