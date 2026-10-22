代发 wailian999

[U103] JS：定时器
来源：http://dali.yueranfly.top/Article/details/gt2dipfhkkp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.nwbrower.top/Article/details/gt2bykfkprq.html

[U104] JS：防抖
来源：http://dali.daxiang520.top/Article/details/gt2ezxbchal.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gt2nlzssxwr.html

[U105] JS：节流
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2unjixsto.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhiwuduotai.top/Article/details/gt2mllpgsah.html

[U106] JS：日期格式化
来源：http://dali.yj202588.top/Article/details/gt2zfojrgkc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhiwuduotai.top/Article/details/gt2mdkrnrwn.html

[U107] JS：数字千分位
来源：http://dali.zhixingplan.top/Article/details/gt2lasonrle.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jiagoushi.top/Article/details/gt2yskbwizz.html

[U108] JS：随机整数
来源：http://dali.andypj.xyz/Article/details/gt2dkidaqrx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.chenzaomai.com/Article/details/gt2dlzuhxmj.html

[U109] JS：数组分组
来源：http://dali.wangdashe.top/Article/details/gt2oejdkfic.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sweek.top/Article/details/gt2dijmecbl.html

[U110] JS：数组分块
来源：http://dali.birdmap.top/Article/details/gt2tklicupu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gaohongyu789.top/Article/details/gt2ysrerlmd.html

[U111] JS：对象转 Map
来源：http://dali.fengsongda.top/Article/details/gt2pwhzeqxd.html

new Map(Object.entries(obj))
来源：http://dali.yuxming.cn/Article/details/gt2xishfhau.html

[U112] JS：字符串补位
来源：http://dali.chenjidiqi.icu/Article/details/gt2zurwvegh.html

"7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gt2zcnqjlxr.html

[U113] JS：正则替换全部
来源：http://dali.9152youxi.cn/Article/details/gt2eeiacbmc.html

s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gt2ryundztb.html

[U114] JS：JSON 深比较
来源：http://dali.yangfankeji.com/Article/details/gt2xqknsqhw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigufen.top/Article/details/gt2uvxragcw.html

[U115] JS：生成 UUID
来源：http://dali.nanxinkj.top/Article/details/gt2zuvbewnr.html

crypto.randomUUID()
来源：http://dali.0kj1m.cn/Article/details/gt2tmauoocg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bxtnljbg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.tanke756.top/Article/details/gt2knfpigsz.html

[U117] JS：单元测试
来源：http://dali.gzhubu.top/Article/details/gt2flkqauqg.html

npm i -D vitest;  npx vitest
来源：http://dali.yj20258.top/Article/details/gt2krwjheqt.html

[U118] JS：开发服务器
来源：http://dali.yj20258.top/Article/details/gt2jmcdbyfz.html

npm i -D vite;  npx vite
来源：http://dali.daria6918.cn/Article/details/gt2blufsute.html

[U119] JS：生产构建
来源：http://dali.chenjidiqi.icu/Article/details/gt2zjzyosom.html

npx vite build
来源：http://dali.birdmap.top/Article/details/gt2xhouobfd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shangyingyoupin.top/Article/details/gt2hdvsqfio.html

import.meta.env.VITE_API_URL
来源：http://dali.dashuyun.cn/Article/details/gt2wjqpdxyh.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aokhyrme.html

统计汇总
来源：http://dali.hammf.cn/Article/details/gt2zqdlkpel.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2rugxwhqs.html

按语言统计（条）：
来源：http://dali.pengpengdd.cyou/Article/details/gt2gdpchzsy.html

Python ......... 252
来源：http://dali.jyoumei.cn/Article/details/gt2nvrtgyyn.html

PHP ............ 252
来源：http://dali.nanxuanxn.top/Article/details/gt2fyccmoch.html

JavaScript ..... 252
来源：http://dali.jyoumei.cn/Article/details/gt2jeedwhfi.html

TypeScript ..... 212
来源：http://dali.xylfe.cn/Article/details/gt2ffoytpqx.html

Java ........... 212
来源：http://dali.ybcxt.top/Article/details/gt2xdbmrrbz.html

Go ............. 212
来源：http://dali.xziqi.cn/Article/details/gt2abycstxk.html

Ruby ........... 212
来源：http://dali.wangshuangyany.cn/Article/details/gt2ojsmnnep.html

C# ............. 212
来源：http://dali.quarkkingdee.top/Article/details/gt2ccritxag.html

C .............. 30
来源：http://dali.jianghu66.top/Article/details/gt2rtjlyykr.html

C++ ............ 30
来源：http://dali.shuidangran.top/Article/details/gt2bgqmwfmh.html

SQL ............ 90
来源：http://dali.yuxming.cn/Article/details/gt2qoobmgqr.html

Bash ........... 80
来源：http://dali.yj202588.top/Article/details/gt2emfhxoqu.html

Kotlin ......... 15
来源：http://dali.bjfxy.top/Article/details/gt2skrkumgj.html

Swift .......... 15
来源：http://dali.birdmap.top/Article/details/gt2irxlqupc.html

Lua ............ 10
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hguqkcjt.html

Perl ........... 10
来源：http://dali.yuanzhike.top/Article/details/gt2sumotkgp.html

Scala .......... 10
来源：http://dali.andypj.xyz/Article/details/gt2mqwuzybq.html

------------------------------------
来源：http://dali.hammf.cn/Article/details/gt2ydiobaxq.html

合计 ........... 2106 条
来源：http://dali.hfpthk.cn/Article/details/gt2gudwmkfu.html

按章节统计：
来源：http://dali.daria6918.cn/Article/details/gt2ffobvojr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hfpthk.cn/Article/details/gt2qxabnaal.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.havefunace.top/Article/details/gt2xfsdodxu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jqgufenzy.top/Article/details/gt2csiygfcn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.meibo888.top/Article/details/gt2dwlofcli.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.haohaochexian.top/Article/details/gt2jgnkgcyb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xylfe.cn/Article/details/gt2rkvtuian.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tian-w.cn/Article/details/gt2hjrmulrs.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.kuanghao11.cn/Article/details/gt2sgyrpxgj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhixingplan.top/Article/details/gt2gynkurrb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.pycfn.com/Article/details/gt2zfzaqhrg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gt2pfsbbbsf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gt2wxebutzx.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpaiymo.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.9152youxi.cn/Article/details/gt2yuqsaebe.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.gotoacloud.top/Article/details/gt2krmhmnaz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gt2xfvgbsku.html

Q SQL 专题                              90
来源：http://dali.jqgufenzy.top/Article/details/gt2exiouhlh.html

R Bash 专题                             80
来源：http://dali.chenlongwang.top/Article/details/gt2aggktfua.html

S C / C++ 专题                          60
来源：http://dali.aibaodan.cn/Article/details/gt2obfccjyo.html

T 其他语言补充                          60
来源：http://dali.aibaodan.cn/Article/details/gt2imnxcgad.html

U 高频实用片段                         120
来源：http://dali.cheryme.top/Article/details/gt2hlekfzcu.html

------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gt2rnychwqp.html

合计                                  2106 条
来源：http://dali.hammf.cn/Article/details/gt2hywcwpjv.html

--------------------------------------------------------------------------------
来源：http://dali.cashguo.top/Article/details/gt2rlpjaskg.html

使用提醒
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dbzbokfd.html

--------------------------------------------------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gt2mdiggrry.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yanxiufei.cn/Article/details/gt2rldjenet.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhoulong.xyz/Article/details/gt2zfmvojtp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xziqi.cn/Article/details/gt2pzraopao.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jyoumei.cn/Article/details/gt2suintcct.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.gaohongyu789.top/Article/details/gt2dltmxfmg.html

—— 文件结束 ——
来源：http://dali.cheryme.top/Article/details/gt2aqhulerg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2igsxcpzd.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhiwuduotai.top/Article/details/gt2pwuquwwy.html

Common Programming Examples Cheat Book
来源：http://dali.meibo888.top/Article/details/gt2gmqujaus.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2rhuqleah.html

【收录内容】
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nidvpwwm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.pycfn.com/Article/details/gt2jhquydsk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.svipenyu.cn/Article/details/gt2gufjhytv.html

SQL · Bash · C · C++
来源：http://dali.vqdsnc.cn/Article/details/gt2tsnulnjn.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.aibaodan.cn/Article/details/gt2pdaavpap.html

【使用说明】
来源：http://dali.jqgfzy.top/Article/details/gt2zagmmoil.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.redwolf501.top/Article/details/gt2cwxekxks.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.vqdsnc.cn/Article/details/gt2fbakmamc.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.pycfn.com/Article/details/gt2hvhaaeiq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.wangdashe.top/Article/details/gt2narfwvsz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.chenzaomai.com/Article/details/gt2ijubzuwk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.redwolf501.top/Article/details/gt2mhmipasz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhiwuduotai.top/Article/details/gt2wedwxeij.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.wangdashe.top/Article/details/gt2fcemrimm.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.meibo888.top/Article/details/gt2umzeicwj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jqgufenzy.top/Article/details/gt2aubiqqaf.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hongshengwenyu.top/Article/details/gt2bqlcznvi.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.smart0.xyz/Article/details/gt2avjbezth.html

【文件统计】
来源：http://dali.shzxlz.cn/Article/details/gt2vrjevtbw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.dashuyun.cn/Article/details/gt2orldtdvw.html

--------------------------------------------------------------------------------
来源：http://dali.ybcxt.top/Article/details/gt2vvlgyzoz.html

目  录
来源：http://dali.xziqi.cn/Article/details/gt2wbvmdzeb.html

--------------------------------------------------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gt2uqhvsmqc.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2vvyxzfdj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2uqcxvuhe.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2huedcnbc.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yonumen.top/Article/details/gt2xwqrwnle.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jinqigufen.top/Article/details/gt2kbvvwiqr.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.meibo888.top/Article/details/gt2vjvcfkoh.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.wangdashe.top/Article/details/gt2hbwsfhsz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.havefunace.top/Article/details/gt2namviryi.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gt2blrbwhat.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.chenlongwang.top/Article/details/gt2bbxoebst.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.daxiang520.top/Article/details/gt2bucgahkn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2ssjmdlcg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.ivvv.top/Article/details/gt2ndvphqej.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.bjfxy.top/Article/details/gt2ccinynxs.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2amfdoxys.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gt2snnqlrtz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2noyjvgfj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ehwqpu.com/Article/details/gt2kgncojxg.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fjbkcuaw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hfpthk.cn/Article/details/gt2ncnjrkum.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.aizwys.cn/Article/details/gt2ktruqpww.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2uiydcqyl.html

A. 基础语法与类型
来源：http://dali.pycfn.com/Article/details/gt2rdlmyxez.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2bpxkjzmv.html

[A01] Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lqgyxtjz.html

Py:   print("Hello, World!")
来源：http://dali.gzhubu.top/Article/details/gt2rkhjqvjv.html

PHP:  echo "Hello, World!";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ddisholk.html

JS:   console.log("Hello, World!");
来源：http://dali.fengsongda.top/Article/details/gt2ceprpuxy.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yonumen.top/Article/details/gt2ywiqvutb.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aedbkkbv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sysykeji.top/Article/details/gt2mxsfvfni.html

Ruby: puts "Hello, World!"
来源：http://dali.cashguo.top/Article/details/gt2jxxnitby.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ppjwa.cn/Article/details/gt2gsbpbbic.html

[A02] 变量声明与赋值
来源：http://dali.yj20258.top/Article/details/gt2dcjvcyvr.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sysykeji.top/Article/details/gt2fqflnrzn.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.sufxvd.cn/Article/details/gt2jzcidgah.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ivvv.top/Article/details/gt2lkrembcu.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cqqwz.cn/Article/details/gt2tkcdlegk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtapdgms.html

Go:   name := "Alex"; age := 20
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rgzevsps.html

Ruby: name = "Alex"; age = 20
来源：http://dali.dashuyun.cn/Article/details/gt2flwsnlay.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hysaishi.cn/Article/details/gt2mwwdtspe.html

[A03] 常量定义
来源：http://dali.gotoacloud.top/Article/details/gt2nxpfpjyi.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.havefunace.top/Article/details/gt2zidqidcr.html

PHP:  const PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gt2xsrhgjws.html

JS:   const PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gt2jxrfheuz.html

TS:   const PI: number = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gt2qcfbilhn.html

Java: static final double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gt2uyrhwgto.html

Go:   const PI = 3.14159
来源：http://dali.aizwys.cn/Article/details/gt2gahigqet.html

Ruby: PI = 3.14159
来源：http://dali.smart0.xyz/Article/details/gt2mosbsmcw.html

C#:   const double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gt2mpbhobmg.html

[A04] 判断变量类型
来源：http://dali.tian-w.cn/Article/details/gt2wkzbkbkm.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yangfankeji.com/Article/details/gt2atgolyjo.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yj20258.top/Article/details/gt2acrkibvh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jyoumei.cn/Article/details/gt2mxkpsagl.html

TS:   typeof x; x instanceof Date
来源：http://dali.svipenyu.cn/Article/details/gt2venvywke.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yj20258888.top/Article/details/gt2iguxikmp.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.sufxvd.cn/Article/details/gt2xtwpzpmi.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ivvv.top/Article/details/gt2lefrzjhh.html

C#:   x.GetType().Name; x is int
来源：http://dali.chenjidiqi.icu/Article/details/gt2ewlbfcza.html

[A05] 整数除法与取模
来源：http://dali.yueranfly.top/Article/details/gt2kmmnprzh.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2ipqjgrhq.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2kdiftuhb.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gt2mdeilxoz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gt2meporuvh.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gt2qywezhip.html

Go:   7 / 2; 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gt2qiqscrme.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.redwolf501.top/Article/details/gt2bvucgsyb.html

C#:   7 / 2; 7 % 2
来源：http://dali.xziqi.cn/Article/details/gt2setgoarz.html

[A06] 字符串转数字
来源：http://dali.yueranfly.top/Article/details/gt2kotccuhe.html

Py:   int("42"); float("3.14")
来源：http://dali.9152youxi.cn/Article/details/gt2kjsznsfs.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jlsjyb.cn/Article/details/gt2jcsyqhfn.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zycfv.cn/Article/details/gt2whzlprzi.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.iojbl.cn/Article/details/gt2axyjcgkp.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jiagoushi.top/Article/details/gt2wpvvnmsk.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.aibaodan.cn/Article/details/gt2ycygscqb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.aibaodan.cn/Article/details/gt2lwycjpsk.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.nanxuanxn.top/Article/details/gt2sbzflvbb.html

[A07] 数字转字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2lsnegtpp.html

Py:   str(42)
来源：http://dali.tian-w.cn/Article/details/gt2nrwzoids.html

PHP:  (string) 42; strval(42)
来源：http://dali.meibo888.top/Article/details/gt2rmfbcsyt.html

JS:   String(42); (42).toString()
来源：http://dali.gotoacloud.top/Article/details/gt2upjcmcoz.html

TS:   String(42)
来源：http://dali.jqgufenzy.top/Article/details/gt2upwyfzxs.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.birdmap.top/Article/details/gt2imconamj.html

Go:   strconv.Itoa(42)
来源：http://dali.zhoulong.xyz/Article/details/gt2xgpywypa.html

Ruby: 42.to_s
来源：http://dali.nwbrower.top/Article/details/gt2dyabjerr.html

C#:   42.ToString()
来源：http://dali.smart0.xyz/Article/details/gt2jeapqsts.html

[A08] 取整与四舍五入
来源：http://dali.snrcjt.cn/Article/details/gt2gqkdunsn.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jiagoushi.top/Article/details/gt2gsptyshh.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ivvv.top/Article/details/gt2wqvtyngd.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.chenlongwang.top/Article/details/gt2wroatqgv.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.bjfxy.top/Article/details/gt2pbcfyzvg.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hongshengwenyu.top/Article/details/gt2iaobzedv.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yonumen.top/Article/details/gt2srpdunew.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yueranfly.top/Article/details/gt2jjywsuuq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jinqigufen.top/Article/details/gt2pzjreimv.html

[A09] 绝对值与最大最小值
来源：http://dali.xinyue.icu/Article/details/gt2slpggdbz.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2vxyoqfqe.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2qkaqbfaf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.smart0.xyz/Article/details/gt2cojsqlbn.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2ogdbsoej.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yongpay.top/Article/details/gt2hlrwwmrx.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.daxiang520.top/Article/details/gt2qokhnfng.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.shuidangran.top/Article/details/gt2wytnmbye.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hsgjgsli.html

[A10] 生成随机数
来源：http://dali.sweek.top/Article/details/gt2asibcgsd.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zycfv.cn/Article/details/gt2tzffyelk.html

PHP:  random_int(1, 100);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2irggftmr.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cdnleiting.top/Article/details/gt2ppatxyyk.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cucudq.cn/Article/details/gt2boqlhcke.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yueranfly.top/Article/details/gt2mrjpdayl.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yvedp.cn/Article/details/gt2xmaaehpx.html

Ruby: rand(1..100)
来源：http://dali.nwbrower.top/Article/details/gt2dcpsvsbu.html

C#:   new Random().Next(1, 101)
来源：http://dali.fzhhl.top/Article/details/gt2iwidpjfm.html

[A11] 条件表达式（三元）
来源：http://dali.smart0.xyz/Article/details/gt2jwmsrgas.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zycfv.cn/Article/details/gt2bcftpfaf.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.smart0.xyz/Article/details/gt2lfjtvhgo.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhengqikj.top/Article/details/gt2imuygshf.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.haohaochexian.top/Article/details/gt2zjeqdshk.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.gotoacloud.top/Article/details/gt2nblvldee.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.svipenyu.cn/Article/details/gt2ioorvqju.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.ybcxt.top/Article/details/gt2sxtioycv.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yanxiufei.cn/Article/details/gt2ivulgdia.html

[A12] 字符串插值 / 格式化
来源：http://dali.bjfxy.top/Article/details/gt2qxbyqwxm.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.gogol.net.cn/Article/details/gt2mxtrvyaq.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.daxiang520.top/Article/details/gt2jogqydwy.html

JS:   `Hello, ${name}!`
来源：http://dali.aizwys.cn/Article/details/gt2mzixevrj.html

TS:   `Hello, ${name}!`
来源：http://dali.svipenyu.cn/Article/details/gt2vyqqoseb.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lptpasge.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.ivvv.top/Article/details/gt2jklvpckq.html

Ruby: "Hello, #{name}!"
来源：http://dali.yj20258888.top/Article/details/gt2fsrvlvyd.html

C#:   $"Hello, {name}!"
来源：http://dali.shangyingyoupin.top/Article/details/gt2klpjwbse.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.pengpengdd.cyou/Article/details/gt2fzkpugdk.html

Py:   "第一行\n第二行"
来源：http://dali.dashuyun.cn/Article/details/gt2vcxtincj.html

PHP:  "第一行\n第二行"
来源：http://dali.gotoacloud.top/Article/details/gt2pijxgcnr.html

JS:   "第一行\n第二行"
来源：http://dali.zhoulong.xyz/Article/details/gt2zsizlhfk.html

TS:   "第一行\n第二行"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ezzlvnhq.html

Java: "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gt2yipnfmpr.html

Go:   "第一行\n第二行"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2adxvsvkp.html

Ruby: "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gt2kzjlkwfw.html

C#:   "第一行\n第二行"
来源：http://dali.yvedp.cn/Article/details/gt2edofdsoi.html

[A14] 注释写法
来源：http://dali.redwolf501.top/Article/details/gt2jhqgnmar.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yvedp.cn/Article/details/gt2vgzqkpgq.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zdqjudy.top/Article/details/gt2eayvgwgh.html

JS:   // 单行；/* 多行 */
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dezmzgbt.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gfcbrgni.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.cqqwz.cn/Article/details/gt2zunwvtft.html

Go:   // 单行；/* 多行 */
来源：http://dali.ivvv.top/Article/details/gt2hpejttha.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hongshengwenyu.top/Article/details/gt2tcsyrutb.html

C#:   // 单行；/* 多行 */
来源：http://dali.aibaodan.cn/Article/details/gt2rgucnrbb.html

[A15] 空值判断与默认值
来源：http://dali.vqdsnc.cn/Article/details/gt2vawvtvbk.html

Py:   value = data or "默认值"
来源：http://dali.meibo888.top/Article/details/gt2ccqdxyun.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.cucudq.cn/Article/details/gt2yffiugic.html

JS:   const value = data ?? "默认值";
来源：http://dali.chenlongwang.top/Article/details/gt2choapqdg.html

TS:   const value = data ?? "默认值";
来源：http://dali.xylfe.cn/Article/details/gt2ylaxadci.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxxtbaj.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhongyouzk.top/Article/details/gt2dimkcnzf.html

Ruby: value = data || "默认值"
来源：http://dali.sufxvd.cn/Article/details/gt2wsxhicfq.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhiwuduotai.top/Article/details/gt2zvuulhhd.html

[A16] 真假值判断规则
来源：http://dali.cucudq.cn/Article/details/gt2gvidboaj.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.sysykeji.top/Article/details/gt2mpatndrx.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.ybcxt.top/Article/details/gt2psbskjhx.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jlsjyb.cn/Article/details/gt2oyoxxlvl.html

TS:   if (!x) {}
来源：http://dali.gogol.net.cn/Article/details/gt2xsouoicb.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.svipenyu.cn/Article/details/gt2pczdyurg.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.shangyingyoupin.top/Article/details/gt2mpbbwrfb.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.haohaochexian.top/Article/details/gt2ryebqwuo.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.snrcjt.cn/Article/details/gt2wspvpbhk.html

[A17] 位运算
来源：http://dali.aizwys.cn/Article/details/gt2mbutlwtn.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pycfn.com/Article/details/gt2xvnuddgi.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yj202588.top/Article/details/gt2hlcavnyh.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gt2wsvlcltz.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2fedgviua.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhixingplan.top/Article/details/gt2zcvyqlem.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.dianchejie.cn/Article/details/gt2wwlckitt.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ydzc1.top/Article/details/gt2emivjcqq.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.mhx1999.top/Article/details/gt2dbgavibn.html

[A18] 字符与 ASCII 码互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pthhqvmb.html

Py:   ord("A"); chr(65)
来源：http://dali.jinqigfzy.top/Article/details/gt2ynezmhjk.html

PHP:  ord("A"); chr(65)
来源：http://dali.cqqwz.cn/Article/details/gt2tbzdmssb.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.kuanghao11.cn/Article/details/gt2jsgvrhuy.html


<!-- 参考信息 -->