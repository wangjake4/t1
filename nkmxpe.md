代发 wailian999

[U105] JS：节流
来源：http://dali.yongpay.top/Article/details/gt2hvcpevni.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xylfe.cn/Article/details/gt2byijwvwt.html

[U106] JS：日期格式化
来源：http://dali.bjfxy.top/Article/details/gt2kawtskjk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yvedp.cn/Article/details/gt2nstzfobu.html

[U107] JS：数字千分位
来源：http://dali.cdnleiting.top/Article/details/gt2wvifplmo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xuanzx.com/Article/details/gt2uhgumgwk.html

[U108] JS：随机整数
来源：http://dali.redwolf501.top/Article/details/gt2alzidrla.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.daxiang520.top/Article/details/gt2heolnyed.html

[U109] JS：数组分组
来源：http://dali.birdmap.top/Article/details/gt2zjstdvtx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cheryme.top/Article/details/gt2objmxtvx.html

[U110] JS：数组分块
来源：http://dali.wangdashe.top/Article/details/gt2wwretkjp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ivvv.top/Article/details/gt2aqqnobge.html

[U111] JS：对象转 Map
来源：http://dali.chenjidiqi.icu/Article/details/gt2bkaebeiw.html

new Map(Object.entries(obj))
来源：http://dali.meibo888.top/Article/details/gt2uzxslxqm.html

[U112] JS：字符串补位
来源：http://dali.cdnleiting.top/Article/details/gt2xxcjvsbz.html

"7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gt2frkhvtbc.html

[U113] JS：正则替换全部
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2crdpnuxq.html

s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2uhfyjbhj.html

[U114] JS：JSON 深比较
来源：http://dali.wangdashe.top/Article/details/gt2nkqtquvx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenzaomai.com/Article/details/gt2faiqdmus.html

[U115] JS：生成 UUID
来源：http://dali.dianchejie.cn/Article/details/gt2fyjqrjgx.html

crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mwgxckjx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yj20258.top/Article/details/gt2bihdznuy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ehwqpu.com/Article/details/gt2qwniyint.html

[U117] JS：单元测试
来源：http://dali.zhengqikj.top/Article/details/gt2kllkpcde.html

npm i -D vitest;  npx vitest
来源：http://dali.fzhhl.top/Article/details/gt2pgmezchf.html

[U118] JS：开发服务器
来源：http://dali.jyoumei.cn/Article/details/gt2esynrtsw.html

npm i -D vite;  npx vite
来源：http://dali.nanxinkj.top/Article/details/gt2nubgahno.html

[U119] JS：生产构建
来源：http://dali.quarkkingdee.top/Article/details/gt2lccdylys.html

npx vite build
来源：http://dali.xuanzx.com/Article/details/gt2chbszlpe.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.wangdashe.top/Article/details/gt2carkoxbc.html

import.meta.env.VITE_API_URL
来源：http://dali.9152youxi.cn/Article/details/gt2ozaerxjx.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2erjmvqek.html

统计汇总
来源：http://dali.zdqjudy.top/Article/details/gt2moszuokn.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2snvtxkkq.html

按语言统计（条）：
来源：http://dali.yj20258.top/Article/details/gt2susgtmum.html

Python ......... 252
来源：http://dali.zhiwuduotai.top/Article/details/gt2jyzvqrjx.html

PHP ............ 252
来源：http://dali.tian-w.cn/Article/details/gt2cauxurdy.html

JavaScript ..... 252
来源：http://dali.zhoulong.xyz/Article/details/gt2wntcfiua.html

TypeScript ..... 212
来源：http://dali.kuanghao11.cn/Article/details/gt2nqqlkrpt.html

Java ........... 212
来源：http://dali.kuanghao11.cn/Article/details/gt2hovarwzd.html

Go ............. 212
来源：http://dali.ehwqpu.com/Article/details/gt2lrbsurme.html

Ruby ........... 212
来源：http://dali.zhixingplan.top/Article/details/gt2baghwnsr.html

C# ............. 212
来源：http://dali.ivvv.top/Article/details/gt2ubwnlypb.html

C .............. 30
来源：http://dali.aizwys.cn/Article/details/gt2ypytqqjf.html

C++ ............ 30
来源：http://dali.shzxlz.cn/Article/details/gt2ypscbfne.html

SQL ............ 90
来源：http://dali.sysykeji.top/Article/details/gt2bwuchhjm.html

Bash ........... 80
来源：http://dali.yonumen.top/Article/details/gt2pkdlxrgh.html

Kotlin ......... 15
来源：http://dali.yj20258888.top/Article/details/gt2rpjlfrdc.html

Swift .......... 15
来源：http://dali.ppjwa.cn/Article/details/gt2nkfkwuug.html

Lua ............ 10
来源：http://dali.fzhhl.top/Article/details/gt2hkrmevwq.html

Perl ........... 10
来源：http://dali.yvedp.cn/Article/details/gt2awmadksd.html

Scala .......... 10
来源：http://dali.zycfv.cn/Article/details/gt2roglmooj.html

------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gt2cayhsfbb.html

合计 ........... 2106 条
来源：http://dali.hammf.cn/Article/details/gt2hbeclxjo.html

按章节统计：
来源：http://dali.yanxiufei.cn/Article/details/gt2rmpbkuto.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.nwbrower.top/Article/details/gt2hrxnkltf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.snrcjt.cn/Article/details/gt2kbwemvbd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hfpthk.cn/Article/details/gt2gbbgxznw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.wangshuangyany.cn/Article/details/gt2mbuqndxf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.guowangkeji.top/Article/details/gt2mooqandq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hfpthk.cn/Article/details/gt2ijjllglz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.nanxuanxn.top/Article/details/gt2ejacsjfm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.smart0.xyz/Article/details/gt2qssqqlzk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gt2caymxskk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.mhx1999.top/Article/details/gt2bckuudpx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gt2mkzzpjjs.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gt2tvsmevne.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gt2ztnnthwt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2encydfen.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cdnleiting.top/Article/details/gt2skpjhwbm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pyyzudmg.html

Q SQL 专题                              90
来源：http://dali.zhoulong.xyz/Article/details/gt2jjbykvan.html

R Bash 专题                             80
来源：http://dali.shuidangran.top/Article/details/gt2yvcxzrth.html

S C / C++ 专题                          60
来源：http://dali.sysykeji.top/Article/details/gt2zoqgroge.html

T 其他语言补充                          60
来源：http://dali.zhengqikj.top/Article/details/gt2ospztrzk.html

U 高频实用片段                         120
来源：http://dali.0kj1m.cn/Article/details/gt2iuwbdrpb.html

------------------------------------
来源：http://dali.bjfxy.top/Article/details/gt2bqisdbue.html

合计                                  2106 条
来源：http://dali.hammf.cn/Article/details/gt2fwdvmeah.html

--------------------------------------------------------------------------------
来源：http://dali.smart0.xyz/Article/details/gt2sjazkzvn.html

使用提醒
来源：http://dali.xinyue.icu/Article/details/gt2iiggggbp.html

--------------------------------------------------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gt2nvfzmxke.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhengqikj.top/Article/details/gt2prjjgkqs.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yuxming.cn/Article/details/gt2gmbrizcl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.c1oappe.top/Article/details/gt2pijsyvmd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qspokyco.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hfpthk.cn/Article/details/gt2zrgqltpi.html

—— 文件结束 ——
来源：http://dali.jqgufenzy.top/Article/details/gt2njdcnhcz.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2lmonilxw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jiagoushi.top/Article/details/gt2hiiuegpi.html

Common Programming Examples Cheat Book
来源：http://dali.chenjidiqi.icu/Article/details/gt2iydqlkok.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2ztlbtvqu.html

【收录内容】
来源：http://dali.birdmap.top/Article/details/gt2cbpcduox.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.pycfn.com/Article/details/gt2phmyhsrw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yvedp.cn/Article/details/gt2owsnjgfc.html

SQL · Bash · C · C++
来源：http://dali.gogol.net.cn/Article/details/gt2bryrwpcj.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xylfe.cn/Article/details/gt2afzmkbln.html

【使用说明】
来源：http://dali.zycfv.cn/Article/details/gt2yzryiark.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.redwolf501.top/Article/details/gt2wvqcvmww.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hnxiangtu.top/Article/details/gt2vpylybhe.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yueranfly.top/Article/details/gt2jpbhvoor.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.kuanghao11.cn/Article/details/gt2chkshhjm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hnxiangtu.top/Article/details/gt2gbglobpp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.sufxvd.cn/Article/details/gt2rgpsfpwu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.havefunace.top/Article/details/gt2zdvbhwux.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jyoumei.cn/Article/details/gt2pbixzbnh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ybcxt.top/Article/details/gt2ftncwpeo.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.chenzaomai.com/Article/details/gt2ybonjsoq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hnqzz.top/Article/details/gt2jlvfapvi.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.fzhhl.top/Article/details/gt2sgataynu.html

【文件统计】
来源：http://dali.wangdashe.top/Article/details/gt2edkxnjzf.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yuanzhike.top/Article/details/gt2xhnawsvq.html

--------------------------------------------------------------------------------
来源：http://dali.bjfxy.top/Article/details/gt2rubiicms.html

目  录
来源：http://dali.gzhubu.top/Article/details/gt2cbkhicvo.html

--------------------------------------------------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gt2qcfxaemf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yj20258.top/Article/details/gt2vxxzhjqf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eoducapv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2gkvdvmxn.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.bjfxy.top/Article/details/gt2bedmyynh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.dashuyun.cn/Article/details/gt2liwunprr.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2qhrfsbxr.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2msdlcani.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lzkuiemz.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shzxlz.cn/Article/details/gt2sivflfea.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yj202588.top/Article/details/gt2bdkegqut.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hywenlv.cn/Article/details/gt2xuolxmll.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gt2igyyweib.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gt2pftbzgfv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2rtumwtdo.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2ckiepnoi.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yvedp.cn/Article/details/gt2ytxptcbg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pzuesahx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.c1oappe.top/Article/details/gt2gngplhvo.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2erkzzazu.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgufenzy.top/Article/details/gt2xaumzooe.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.pycfn.com/Article/details/gt2hyaaqhpy.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2tgfvflbm.html

A. 基础语法与类型
来源：http://dali.jqgfzy.top/Article/details/gt2tohkfjwm.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2knngfshh.html

[A01] Hello World
来源：http://dali.wangdashe.top/Article/details/gt2weqvnrsv.html

Py:   print("Hello, World!")
来源：http://dali.xuetiantiany.cn/Article/details/gt2sfuuiuea.html

PHP:  echo "Hello, World!";
来源：http://dali.shuidangran.top/Article/details/gt2iigihcqi.html

JS:   console.log("Hello, World!");
来源：http://dali.havefunace.top/Article/details/gt2asnclfyg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yuanzhike.top/Article/details/gt2uimacibi.html

Java: System.out.println("Hello, World!");
来源：http://dali.chenlongwang.top/Article/details/gt2jtekefqf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.redwolf501.top/Article/details/gt2mxrgefip.html

Ruby: puts "Hello, World!"
来源：http://dali.jlsjyb.cn/Article/details/gt2rpgkwchu.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.gzhubu.top/Article/details/gt2ogvmbgvc.html

[A02] 变量声明与赋值
来源：http://dali.nanxinkj.top/Article/details/gt2ciueszzo.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cashguo.top/Article/details/gt2zzoikasw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jlsjyb.cn/Article/details/gt2lauulybq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.9152youxi.cn/Article/details/gt2xzphokqy.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.shuidangran.top/Article/details/gt2gvmsaztb.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.gaohongyu789.top/Article/details/gt2ozafbibn.html

Go:   name := "Alex"; age := 20
来源：http://dali.sxryk.cn/Article/details/gt2zwapcqxf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.feifeiyinyue.top/Article/details/gt2mbtoulwa.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.nwbrower.top/Article/details/gt2fjastgad.html

[A03] 常量定义
来源：http://dali.guannengcc.top/Article/details/gt2prpdyboa.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.sysykeji.top/Article/details/gt2jgxurjed.html

PHP:  const PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gt2kqpdbyyl.html

JS:   const PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gt2lhntbymr.html

TS:   const PI: number = 3.14159;
来源：http://dali.meibo888.top/Article/details/gt2wccdavcl.html

Java: static final double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gt2lpxjjydm.html

Go:   const PI = 3.14159
来源：http://dali.ppjwa.cn/Article/details/gt2nxrwrelc.html

Ruby: PI = 3.14159
来源：http://dali.cqqwz.cn/Article/details/gt2evcjndhp.html

C#:   const double PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gt2vbfnmvav.html

[A04] 判断变量类型
来源：http://dali.tian-w.cn/Article/details/gt2chbbxeis.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ueixrvli.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.xinyue.icu/Article/details/gt2yrivrdni.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jianghu66.top/Article/details/gt2lbwcaxmx.html

TS:   typeof x; x instanceof Date
来源：http://dali.gogol.net.cn/Article/details/gt2jblmlyci.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhengqikj.top/Article/details/gt2eraouoab.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zdqjudy.top/Article/details/gt2qmwedxvl.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.gotoacloud.top/Article/details/gt2dakrrhuk.html

C#:   x.GetType().Name; x is int
来源：http://dali.chenlongwang.top/Article/details/gt2hydesagq.html

[A05] 整数除法与取模
来源：http://dali.yuxming.cn/Article/details/gt2pvrpsypo.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.quarkkingdee.top/Article/details/gt2iacalphk.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gt2pzhmvnpv.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.iojbl.cn/Article/details/gt2mcplspwa.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gt2hcgytanf.html

Java: 7 / 2; 7 % 2
来源：http://dali.ybcxt.top/Article/details/gt2eozmcrad.html

Go:   7 / 2; 7 % 2
来源：http://dali.cucudq.cn/Article/details/gt2xgwjxgbj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yongpay.top/Article/details/gt2rbpmldzx.html

C#:   7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gt2nntranlv.html

[A06] 字符串转数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cyfavqgu.html

Py:   int("42"); float("3.14")
来源：http://dali.shangyingyoupin.top/Article/details/gt2iqybkmov.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.tianlin.xyz/Article/details/gt2dnzkummh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ydzc1.top/Article/details/gt2xrfsqote.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.bjfxy.top/Article/details/gt2rlsakslz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.xziqi.cn/Article/details/gt2pgweshkn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.chenzaomai.com/Article/details/gt2ffnoyidk.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.316326.xyz/Article/details/gt2mdqxmbps.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.kuanghao11.cn/Article/details/gt2ophdnqsf.html

[A07] 数字转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cxwemxcg.html

Py:   str(42)
来源：http://dali.pengpengdd.cyou/Article/details/gt2osgznwtr.html

PHP:  (string) 42; strval(42)
来源：http://dali.jyoumei.cn/Article/details/gt2lefyhehg.html

JS:   String(42); (42).toString()
来源：http://dali.smart0.xyz/Article/details/gt2cdvwismx.html

TS:   String(42)
来源：http://dali.haohaochexian.top/Article/details/gt2qfrucven.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.svipenyu.cn/Article/details/gt2ibrkjpsa.html

Go:   strconv.Itoa(42)
来源：http://dali.guannengcc.top/Article/details/gt2xmqadfyp.html

Ruby: 42.to_s
来源：http://dali.haohaochexian.top/Article/details/gt2snvpvfdk.html

C#:   42.ToString()
来源：http://dali.yangfankeji.com/Article/details/gt2hlyhgddn.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdmcans.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhoulong.xyz/Article/details/gt2eozzmhqz.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.daxiang520.top/Article/details/gt2vejfoesl.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.shuidangran.top/Article/details/gt2rsladlnk.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.wangdashe.top/Article/details/gt2hunqrmqc.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.cucudq.cn/Article/details/gt2maxosrgk.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rrznifpd.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.cdnleiting.top/Article/details/gt2wpdvgeuv.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jqgufenzy.top/Article/details/gt2qjwcwcpw.html

[A09] 绝对值与最大最小值
来源：http://dali.hammf.cn/Article/details/gt2lqjksnie.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.bjfxy.top/Article/details/gt2xnusyquc.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2vbzohcgc.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sbvfhkoj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.316326.xyz/Article/details/gt2aebxtuqy.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2esmzjtiy.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.pycfn.com/Article/details/gt2bamuxcnx.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.gzhubu.top/Article/details/gt2hvmmvadz.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2srnseikm.html

[A10] 生成随机数
来源：http://dali.9152youxi.cn/Article/details/gt2dwgqmred.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2inqtnqdz.html

PHP:  random_int(1, 100);
来源：http://dali.ivvv.top/Article/details/gt2plvqzhjy.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.aibaodan.cn/Article/details/gt2pryabvnd.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yuxming.cn/Article/details/gt2pvqscjzt.html

Java: new Random().nextInt(100) + 1
来源：http://dali.0kj1m.cn/Article/details/gt2xcyjzxvv.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.kuanghao11.cn/Article/details/gt2hoysqzdk.html

Ruby: rand(1..100)
来源：http://dali.daria6918.cn/Article/details/gt2kdjlkuov.html

C#:   new Random().Next(1, 101)
来源：http://dali.yanxiufei.cn/Article/details/gt2nkilqddm.html

[A11] 条件表达式（三元）
来源：http://dali.yj20258.top/Article/details/gt2soequhtp.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yj202588.top/Article/details/gt2rkooibew.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.jinqigfzy.top/Article/details/gt2qzhggaot.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.dianchejie.cn/Article/details/gt2nkgwngcg.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.hfpthk.cn/Article/details/gt2xdvsgppk.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.0kj1m.cn/Article/details/gt2guadeemi.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.guannengcc.top/Article/details/gt2fwonunlm.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.iojbl.cn/Article/details/gt2pdwyzwae.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.gogol.net.cn/Article/details/gt2benroyon.html

[A12] 字符串插值 / 格式化
来源：http://dali.yangfankeji.com/Article/details/gt2fwipgzvo.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.c1oappe.top/Article/details/gt2jshxuaoi.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uqbmcnue.html

JS:   `Hello, ${name}!`
来源：http://dali.zhoulong.xyz/Article/details/gt2rtftsdvu.html

TS:   `Hello, ${name}!`
来源：http://dali.gzhubu.top/Article/details/gt2phkfhhin.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yongpay.top/Article/details/gt2xuylxnqp.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.chenzaomai.com/Article/details/gt2hjtkxvhf.html

Ruby: "Hello, #{name}!"
来源：http://dali.tanke756.top/Article/details/gt2qlcqfiut.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhtlfsi.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.hfpthk.cn/Article/details/gt2jyxtdsah.html

Py:   "第一行\n第二行"
来源：http://dali.ehwqpu.com/Article/details/gt2neurnumo.html

PHP:  "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gt2gzdaoyie.html

JS:   "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gt2qplhshds.html

TS:   "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2whkvyvlp.html

Java: "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gt2zrfeddtm.html

Go:   "第一行\n第二行"
来源：http://dali.nanxinkj.top/Article/details/gt2yuxcmwqo.html

Ruby: "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gt2wagpxclu.html

C#:   "第一行\n第二行"
来源：http://dali.hammf.cn/Article/details/gt2mjdhoijw.html

[A14] 注释写法
来源：http://dali.cucudq.cn/Article/details/gt2cwjxnhad.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.hongshengwenyu.top/Article/details/gt2krybuesd.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.xylfe.cn/Article/details/gt2bgentbfm.html

JS:   // 单行；/* 多行 */
来源：http://dali.jianghu66.top/Article/details/gt2zwmnwjsj.html

TS:   // 单行；/* 多行 */
来源：http://dali.xuetiantiany.cn/Article/details/gt2cjxyguri.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.quarkkingdee.top/Article/details/gt2vlganuql.html

Go:   // 单行；/* 多行 */
来源：http://dali.ybcxt.top/Article/details/gt2lhgqtnhn.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.havefunace.top/Article/details/gt2xgeanzuf.html

C#:   // 单行；/* 多行 */
来源：http://dali.yangfankeji.com/Article/details/gt2ueppsslh.html

[A15] 空值判断与默认值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nufotpaf.html

Py:   value = data or "默认值"
来源：http://dali.mhx1999.top/Article/details/gt2gilsejol.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.sufxvd.cn/Article/details/gt2gwwmpfpg.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhengqikj.top/Article/details/gt2iwjvjyhj.html

TS:   const value = data ?? "默认值";
来源：http://dali.yongpay.top/Article/details/gt2kkgxqadb.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mphbojvl.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shuidangran.top/Article/details/gt2yurducvc.html

Ruby: value = data || "默认值"
来源：http://dali.kuanghao11.cn/Article/details/gt2usmhjuws.html

C#:   var value = data ?? "默认值";
来源：http://dali.wangdashe.top/Article/details/gt2pdkojzag.html

[A16] 真假值判断规则
来源：http://dali.shzxlz.cn/Article/details/gt2lfisjifu.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rmhlnarl.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.snrcjt.cn/Article/details/gt2ohyeefyd.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.tian-w.cn/Article/details/gt2htqbygiq.html

TS:   if (!x) {}
来源：http://dali.jiagoushi.top/Article/details/gt2pfmakphf.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.cdnleiting.top/Article/details/gt2eibbvbbx.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2ecjewczg.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.chenjidiqi.icu/Article/details/gt2pphdmcgw.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2svflqrnw.html

[A17] 位运算
来源：http://dali.chenzaomai.com/Article/details/gt2hibxjjxm.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hammf.cn/Article/details/gt2jedjsven.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhengqikj.top/Article/details/gt2ehpsbufy.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.vqdsnc.cn/Article/details/gt2ftxkuuvq.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gt2pnuacsgz.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gt2zdjvvttu.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.nanxinkj.top/Article/details/gt2bbvxhuba.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gt2ncdlijtl.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gt2bnclxdiu.html

[A18] 字符与 ASCII 码互转
来源：http://dali.daria6918.cn/Article/details/gt2vabmrpxd.html

Py:   ord("A"); chr(65)
来源：http://dali.jiagoushi.top/Article/details/gt2ojpjykxf.html

PHP:  ord("A"); chr(65)
来源：http://dali.ppjwa.cn/Article/details/gt2dpxnynwl.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hivxocry.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ppjwa.cn/Article/details/gt2hbmwxkzp.html

Java: (int) 'A'; (char) 65
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zhsyjjzo.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xqxzzueq.html

Ruby: "A".ord; 65.chr
来源：http://dali.ybcxt.top/Article/details/gt2uwovsmmu.html


<!-- 参考信息 -->