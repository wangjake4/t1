代发 wailian999

[U101] JS：classList 操作
来源：http://dali.zhengqikj.top/Article/details/gt2kffrxmsq.html

el.classList.toggle("active")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hhqoueoq.html

[U102] JS：本地存储
来源：http://dali.tanke756.top/Article/details/gt2ikzdhekm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xuanzx.com/Article/details/gt2tfxbkrmd.html

[U103] JS：定时器
来源：http://dali.jyoumei.cn/Article/details/gt2ygjmmxep.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xinyue.icu/Article/details/gt2gtbwduve.html

[U104] JS：防抖
来源：http://dali.shangyingyoupin.top/Article/details/gt2neettpsh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangshuangyany.cn/Article/details/gt2kdcnbcla.html

[U105] JS：节流
来源：http://dali.tian-w.cn/Article/details/gt2ehafnkfj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jiagoushi.top/Article/details/gt2eykbvyud.html

[U106] JS：日期格式化
来源：http://dali.xuanzx.com/Article/details/gt2uptnfudp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.meibo888.top/Article/details/gt2jyqsxnsa.html

[U107] JS：数字千分位
来源：http://dali.bjfxy.top/Article/details/gt2iadaqlod.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.aibaodan.cn/Article/details/gt2zsoorfbw.html

[U108] JS：随机整数
来源：http://dali.cheryme.top/Article/details/gt2hwwvugnw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cheryme.top/Article/details/gt2eqhtjmqp.html

[U109] JS：数组分组
来源：http://dali.yj202588.top/Article/details/gt2ipykuunq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gt2dveeilhp.html

[U110] JS：数组分块
来源：http://dali.redwolf501.top/Article/details/gt2ocqcudqt.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cdnleiting.top/Article/details/gt2oksgqgue.html

[U111] JS：对象转 Map
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kdyvagwd.html

new Map(Object.entries(obj))
来源：http://dali.xziqi.cn/Article/details/gt2udbpcaxv.html

[U112] JS：字符串补位
来源：http://dali.andypj.xyz/Article/details/gt2wjpszhis.html

"7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gt2ukhcolcw.html

[U113] JS：正则替换全部
来源：http://dali.ehwqpu.com/Article/details/gt2dsucoqdy.html

s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2wjkyaruv.html

[U114] JS：JSON 深比较
来源：http://dali.jinqigfzy.top/Article/details/gt2bbowhpwe.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cdnleiting.top/Article/details/gt2aycfsvdt.html

[U115] JS：生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gt2lmruazmj.html

crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jquneoky.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.bjfxy.top/Article/details/gt2qfbhhglr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shuidangran.top/Article/details/gt2avmqfgsl.html

[U117] JS：单元测试
来源：http://dali.gogol.net.cn/Article/details/gt2cymgpwpc.html

npm i -D vitest;  npx vitest
来源：http://dali.zdqjudy.top/Article/details/gt2gcxugevo.html

[U118] JS：开发服务器
来源：http://dali.yuanzhike.top/Article/details/gt2ttjooslr.html

npm i -D vite;  npx vite
来源：http://dali.yuanzhike.top/Article/details/gt2rsajlzye.html

[U119] JS：生产构建
来源：http://dali.hnxiangtu.top/Article/details/gt2lbnjvyhj.html

npx vite build
来源：http://dali.nanxinkj.top/Article/details/gt2sugyhfmi.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.dianchejie.cn/Article/details/gt2utcjbhht.html

import.meta.env.VITE_API_URL
来源：http://dali.pycfn.com/Article/details/gt2dabccytl.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ahhvczpw.html

统计汇总
来源：http://dali.zhengqikj.top/Article/details/gt2bzcopjbg.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2fozujzje.html

按语言统计（条）：
来源：http://dali.fzhhl.top/Article/details/gt2dkknhzsk.html

Python ......... 252
来源：http://dali.gzhubu.top/Article/details/gt2wjzecqsh.html

PHP ............ 252
来源：http://dali.zhixingplan.top/Article/details/gt2xlushnvu.html

JavaScript ..... 252
来源：http://dali.gotoacloud.top/Article/details/gt2pmyyfrqf.html

TypeScript ..... 212
来源：http://dali.ybcxt.top/Article/details/gt2duvacpag.html

Java ........... 212
来源：http://dali.ivvv.top/Article/details/gt2lfidruco.html

Go ............. 212
来源：http://dali.jinqigufen.top/Article/details/gt2mrmdanqf.html

Ruby ........... 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nsgnpbal.html

C# ............. 212
来源：http://dali.fzhhl.top/Article/details/gt2cwpavmew.html

C .............. 30
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2durdxqsh.html

C++ ............ 30
来源：http://dali.gzhubu.top/Article/details/gt2xtqcfowb.html

SQL ............ 90
来源：http://dali.cucudq.cn/Article/details/gt2pqlmyggl.html

Bash ........... 80
来源：http://dali.chenzaomai.com/Article/details/gt2zvzhrvhs.html

Kotlin ......... 15
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jragnfxv.html

Swift .......... 15
来源：http://dali.hnxiangtu.top/Article/details/gt2mtmkjgbi.html

Lua ............ 10
来源：http://dali.jinqigfzy.top/Article/details/gt2lrupipox.html

Perl ........... 10
来源：http://dali.iojbl.cn/Article/details/gt2uycwlmbu.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsksgsr.html

------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vrrqtlqq.html

合计 ........... 2106 条
来源：http://dali.xinyue.icu/Article/details/gt2hrwohbof.html

按章节统计：
来源：http://dali.jyoumei.cn/Article/details/gt2lpibmtyi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jiagoushi.top/Article/details/gt2wowekzdp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.nwbrower.top/Article/details/gt2mzkvpltt.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.316326.xyz/Article/details/gt2ixrdpkaw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhengqikj.top/Article/details/gt2stpwvexp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.aibaodan.cn/Article/details/gt2autfxvsx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hnqzz.top/Article/details/gt2yzwlduqw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yangfankeji.com/Article/details/gt2lwzndzcw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yongpay.top/Article/details/gt2dflhgcch.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gt2mqytqxnp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.birdmap.top/Article/details/gt2kioccstn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gt2qhaoyfbo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gt2sgsjueus.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gt2qmvltdzj.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hongshengwenyu.top/Article/details/gt2qnqstplp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.tanke756.top/Article/details/gt2fymaxefy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.mhx1999.top/Article/details/gt2ulpcshvc.html

Q SQL 专题                              90
来源：http://dali.havefunace.top/Article/details/gt2awmdihtp.html

R Bash 专题                             80
来源：http://dali.tanke756.top/Article/details/gt2aaeibyki.html

S C / C++ 专题                          60
来源：http://dali.yj20258.top/Article/details/gt2vrbrvpfh.html

T 其他语言补充                          60
来源：http://dali.sysykeji.top/Article/details/gt2jqpouafq.html

U 高频实用片段                         120
来源：http://dali.chenjidiqi.icu/Article/details/gt2upxaeons.html

------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gt2fhyajciv.html

合计                                  2106 条
来源：http://dali.yangfankeji.com/Article/details/gt2reocjywf.html

--------------------------------------------------------------------------------
来源：http://dali.ybcxt.top/Article/details/gt2vvozfdes.html

使用提醒
来源：http://dali.kuanghao11.cn/Article/details/gt2aahujdhy.html

--------------------------------------------------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gt2sczpybgc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yuanzhike.top/Article/details/gt2gedpkavt.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.guannengcc.top/Article/details/gt2rglsngaw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xuanzx.com/Article/details/gt2oyvrgesa.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.sxryk.cn/Article/details/gt2luwrxiah.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.c1oappe.top/Article/details/gt2jyzhdkkb.html

—— 文件结束 ——
来源：http://dali.ehwqpu.com/Article/details/gt2jrdgvfgj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ztjrdvqv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jqgufenzy.top/Article/details/gt2ftwdqpej.html

Common Programming Examples Cheat Book
来源：http://dali.yvedp.cn/Article/details/gt2qzklarwa.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2kllkvaws.html

【收录内容】
来源：http://dali.c1oappe.top/Article/details/gt2arfpezfc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.meibo888.top/Article/details/gt2mpijgvzi.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.vqdsnc.cn/Article/details/gt2lnclxhys.html

SQL · Bash · C · C++
来源：http://dali.aizwys.cn/Article/details/gt2ytkbpjjq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hfpthk.cn/Article/details/gt2zzgmbdbn.html

【使用说明】
来源：http://dali.c1oappe.top/Article/details/gt2yxwxehcf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cheryme.top/Article/details/gt2ebpywpni.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yongpay.top/Article/details/gt2axmojwwv.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.cdnleiting.top/Article/details/gt2djhjnczk.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jqgfzy.top/Article/details/gt2arehmmvq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yanxiufei.cn/Article/details/gt2pyxdraje.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.haohaochexian.top/Article/details/gt2lrytojtq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.ydzc1.top/Article/details/gt2enbiqqpn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jiagoushi.top/Article/details/gt2usaznjuz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ydzc1.top/Article/details/gt2qlxsmrcr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jianghu66.top/Article/details/gt2ybluaefg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.cheryme.top/Article/details/gt2kbuykogr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cheryme.top/Article/details/gt2powgugpt.html

【文件统计】
来源：http://dali.wangshuangyany.cn/Article/details/gt2hpolhswp.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.andypj.xyz/Article/details/gt2tzpgrjxx.html

--------------------------------------------------------------------------------
来源：http://dali.ybcxt.top/Article/details/gt2rfnwjyso.html

目  录
来源：http://dali.smart0.xyz/Article/details/gt2ghfxdxga.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gt2qidjeefu.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.mhx1999.top/Article/details/gt2zagceiur.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.guannengcc.top/Article/details/gt2wibthmja.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.nwbrower.top/Article/details/gt2hpmowfmh.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.wangdashe.top/Article/details/gt2ikxzralz.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.cashguo.top/Article/details/gt2fhqigwta.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xinyue.icu/Article/details/gt2xgkczopk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zycfv.cn/Article/details/gt2hnuvbukv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zycfv.cn/Article/details/gt2rokhivfa.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gt2gefxrzag.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yangfankeji.com/Article/details/gt2hxnxgqhm.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2jrbvsmqc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2ulpoaele.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gt2bqenvhnk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2yejzwgqh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2sfwttbcx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.gotoacloud.top/Article/details/gt2bfdqunyl.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.nanxinkj.top/Article/details/gt2apxjdond.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hywenlv.cn/Article/details/gt2raxwhuol.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hnqzz.top/Article/details/gt2raeubnli.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxuanxn.top/Article/details/gt2mrleumls.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ydzc1.top/Article/details/gt2rushlmfh.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2zzyrnfcv.html

A. 基础语法与类型
来源：http://dali.yvedp.cn/Article/details/gt2msvrpbux.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2sztxzumk.html

[A01] Hello World
来源：http://dali.aibaodan.cn/Article/details/gt2beglpgts.html

Py:   print("Hello, World!")
来源：http://dali.yueranfly.top/Article/details/gt2ibiargse.html

PHP:  echo "Hello, World!";
来源：http://dali.chenzaomai.com/Article/details/gt2cictcpwc.html

JS:   console.log("Hello, World!");
来源：http://dali.feifeiyinyue.top/Article/details/gt2dypkegqe.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.wangshuangyany.cn/Article/details/gt2negwtfbg.html

Java: System.out.println("Hello, World!");
来源：http://dali.cucudq.cn/Article/details/gt2whgccunu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhoulong.xyz/Article/details/gt2wffgatfa.html

Ruby: puts "Hello, World!"
来源：http://dali.9152youxi.cn/Article/details/gt2vxmtbapz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.cashguo.top/Article/details/gt2pidcnlef.html

[A02] 变量声明与赋值
来源：http://dali.nwbrower.top/Article/details/gt2dpcjltus.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.chenzaomai.com/Article/details/gt2rqvtpwsx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.0kj1m.cn/Article/details/gt2dswoxebe.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ehwqpu.com/Article/details/gt2wdebttkj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.chenjidiqi.icu/Article/details/gt2pwsszhck.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jlsjyb.cn/Article/details/gt2ravttkmm.html

Go:   name := "Alex"; age := 20
来源：http://dali.yanxiufei.cn/Article/details/gt2rjjocznf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yj202588.top/Article/details/gt2uebeperg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jinqigfzy.top/Article/details/gt2dlnrvzhd.html

[A03] 常量定义
来源：http://dali.jinghuilouyu.cn/Article/details/gt2reqmyiiy.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cdnleiting.top/Article/details/gt2mlkqhkea.html

PHP:  const PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gt2ncfcxfdi.html

JS:   const PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gt2ijlmguju.html

TS:   const PI: number = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gt2stgayxtn.html

Java: static final double PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gt2iyogrmxs.html

Go:   const PI = 3.14159
来源：http://dali.vqdsnc.cn/Article/details/gt2oapmudai.html

Ruby: PI = 3.14159
来源：http://dali.shzxlz.cn/Article/details/gt2vyrziubd.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbelpwt.html

[A04] 判断变量类型
来源：http://dali.yueranfly.top/Article/details/gt2dftpjluj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ehwqpu.com/Article/details/gt2hlkzdvxp.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ppjwa.cn/Article/details/gt2svwdepxt.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yj20258.top/Article/details/gt2ohpfpprv.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhongyouzk.top/Article/details/gt2hekgnoub.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kropqvki.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ufzgovpi.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yangfankeji.com/Article/details/gt2qozetmvz.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhoulong.xyz/Article/details/gt2ziilhcbp.html

[A05] 整数除法与取模
来源：http://dali.zhongyouzk.top/Article/details/gt2lxqrzptf.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jiagoushi.top/Article/details/gt2edsmbdxp.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.cashguo.top/Article/details/gt2dhfqpxwy.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj202588.top/Article/details/gt2xzspmrbq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gt2vgxpsmfm.html

Java: 7 / 2; 7 % 2
来源：http://dali.yj202588.top/Article/details/gt2jfuwesyw.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gt2pkkdsjzj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gt2jecuyxqz.html

C#:   7 / 2; 7 % 2
来源：http://dali.daria6918.cn/Article/details/gt2aqnhgsre.html

[A06] 字符串转数字
来源：http://dali.cdnleiting.top/Article/details/gt2cswgqtbr.html

Py:   int("42"); float("3.14")
来源：http://dali.yj202588.top/Article/details/gt2bwbnxnoo.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cashguo.top/Article/details/gt2slyowtos.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.bjfxy.top/Article/details/gt2evvykbxx.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.tanke756.top/Article/details/gt2ujpmkmbf.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.aizwys.cn/Article/details/gt2tewcuimc.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yj20258888.top/Article/details/gt2bjpsctrw.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jiagoushi.top/Article/details/gt2jbgfwbeu.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xinyue.icu/Article/details/gt2dnuacuqb.html

[A07] 数字转字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2lmrtjpgo.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2puzgslwm.html

PHP:  (string) 42; strval(42)
来源：http://dali.daria6918.cn/Article/details/gt2abekyzet.html

JS:   String(42); (42).toString()
来源：http://dali.daxiang520.top/Article/details/gt2iantuvoy.html

TS:   String(42)
来源：http://dali.cucudq.cn/Article/details/gt2iftjdbyg.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.smart0.xyz/Article/details/gt2jazfmsjn.html

Go:   strconv.Itoa(42)
来源：http://dali.hfpthk.cn/Article/details/gt2yiguualu.html

Ruby: 42.to_s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uvxllqxv.html

C#:   42.ToString()
来源：http://dali.svipenyu.cn/Article/details/gt2unsttfkn.html

[A08] 取整与四舍五入
来源：http://dali.daxiang520.top/Article/details/gt2toeycunk.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hfhzfpgs.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oqbbumcc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.guowangkeji.top/Article/details/gt2vogvdccb.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.xuanzx.com/Article/details/gt2mbnevgyq.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.gogol.net.cn/Article/details/gt2hmrhzbcy.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.mhx1999.top/Article/details/gt2bcvbvrjo.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.nanxinkj.top/Article/details/gt2jasylueb.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ybcxt.top/Article/details/gt2bxehobrk.html

[A09] 绝对值与最大最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vlwhdosq.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jshferyc.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gt2mhtbcxqp.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2oroutqac.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.tian-w.cn/Article/details/gt2vfzdhclp.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gt2msxmhiyt.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.feifeiyinyue.top/Article/details/gt2weqvhedk.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zycfv.cn/Article/details/gt2hsmoxyqn.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2coghxopt.html

[A10] 生成随机数
来源：http://dali.zhixingplan.top/Article/details/gt2qddwwyso.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jqgfzy.top/Article/details/gt2csuviayw.html

PHP:  random_int(1, 100);
来源：http://dali.gogol.net.cn/Article/details/gt2fswuaiqn.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.0kj1m.cn/Article/details/gt2jnyoawse.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.fzhhl.top/Article/details/gt2knsnpios.html

Java: new Random().nextInt(100) + 1
来源：http://dali.316326.xyz/Article/details/gt2dvpmuxix.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.birdmap.top/Article/details/gt2pgmefhac.html

Ruby: rand(1..100)
来源：http://dali.zhongyouzk.top/Article/details/gt2iyezffhj.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kkiwdefw.html

[A11] 条件表达式（三元）
来源：http://dali.pengpengdd.cyou/Article/details/gt2eyyaphwu.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.andypj.xyz/Article/details/gt2ndnbomdw.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hywenlv.cn/Article/details/gt2uddoczpr.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gksyldow.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhiwuduotai.top/Article/details/gt2jrsglmwg.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gt2iuchjeul.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.ivvv.top/Article/details/gt2cedbwgld.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.c1oappe.top/Article/details/gt2lheljysq.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.pycfn.com/Article/details/gt2neoyoiky.html

[A12] 字符串插值 / 格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nimngetn.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ywdckzjm.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.guannengcc.top/Article/details/gt2omjxkdgy.html

JS:   `Hello, ${name}!`
来源：http://dali.bjfxy.top/Article/details/gt2mmfmojzp.html

TS:   `Hello, ${name}!`
来源：http://dali.bjfxy.top/Article/details/gt2bhjilpow.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.hammf.cn/Article/details/gt2ulbztkvk.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yuanzhike.top/Article/details/gt2rhbegxjd.html

Ruby: "Hello, #{name}!"
来源：http://dali.316326.xyz/Article/details/gt2rfgaazrj.html

C#:   $"Hello, {name}!"
来源：http://dali.yj202588.top/Article/details/gt2qgkpttbe.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.havefunace.top/Article/details/gt2ikuzzwst.html

Py:   "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gt2wtiyqssw.html

PHP:  "第一行\n第二行"
来源：http://dali.birdmap.top/Article/details/gt2vrnniacr.html

JS:   "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gt2vgkwoqxd.html

TS:   "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gt2spzxbtsw.html

Java: "第一行\n第二行"
来源：http://dali.dashuyun.cn/Article/details/gt2irlrjrue.html

Go:   "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gt2kdtmcntm.html

Ruby: "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gt2lvgrdaym.html

C#:   "第一行\n第二行"
来源：http://dali.wangdashe.top/Article/details/gt2wkiyzcms.html

[A14] 注释写法
来源：http://dali.c1oappe.top/Article/details/gt2xinyhcgs.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.nanxuanxn.top/Article/details/gt2zefzhqdp.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.tanke756.top/Article/details/gt2flgximfn.html

JS:   // 单行；/* 多行 */
来源：http://dali.chenzaomai.com/Article/details/gt2pwhlpzdu.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2oncgmxqp.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.feifeiyinyue.top/Article/details/gt2moudjyzk.html

Go:   // 单行；/* 多行 */
来源：http://dali.sxryk.cn/Article/details/gt2swgmrhqg.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jqgfzy.top/Article/details/gt2mooshpeg.html

C#:   // 单行；/* 多行 */
来源：http://dali.yueranfly.top/Article/details/gt2jxkqmmll.html

[A15] 空值判断与默认值
来源：http://dali.xylfe.cn/Article/details/gt2zxrafupb.html

Py:   value = data or "默认值"
来源：http://dali.jqgfzy.top/Article/details/gt2chmafecv.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.hammf.cn/Article/details/gt2mirbzyca.html

JS:   const value = data ?? "默认值";
来源：http://dali.dashuyun.cn/Article/details/gt2vgcwfuaw.html

TS:   const value = data ?? "默认值";
来源：http://dali.ybcxt.top/Article/details/gt2siijwvar.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.fzhhl.top/Article/details/gt2srtfgbsy.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yangfankeji.com/Article/details/gt2zndbelmm.html

Ruby: value = data || "默认值"
来源：http://dali.hammf.cn/Article/details/gt2sksizejf.html

C#:   var value = data ?? "默认值";
来源：http://dali.jinqigufen.top/Article/details/gt2jlmnmesc.html

[A16] 真假值判断规则
来源：http://dali.jqgufenzy.top/Article/details/gt2cbmonadw.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.birdmap.top/Article/details/gt2cifvpzjy.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.mhx1999.top/Article/details/gt2qlafmlri.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hywenlv.cn/Article/details/gt2hpjhqudb.html

TS:   if (!x) {}
来源：http://dali.zycfv.cn/Article/details/gt2vhfjtyqj.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2hzwrtprh.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.andypj.xyz/Article/details/gt2qtlddedb.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.hammf.cn/Article/details/gt2qbkpnfma.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.xinyue.icu/Article/details/gt2quorkbyj.html

[A17] 位运算
来源：http://dali.jiagoushi.top/Article/details/gt2mzxcbewv.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gt2mnlbddcx.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2irxixqec.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ivvv.top/Article/details/gt2gdaloniw.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.gaohongyu789.top/Article/details/gt2hfnugvfa.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangdashe.top/Article/details/gt2sgeqoyga.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gt2byjlsurf.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ehwqpu.com/Article/details/gt2pqhqpemm.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.9152youxi.cn/Article/details/gt2ibukuafd.html


<!-- 参考信息 -->