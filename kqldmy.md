代发 wailian999

[U101] JS：classList 操作
来源：http://dali.zhongyouzk.top/Article/details/gt2kvftujpa.html

el.classList.toggle("active")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xkptrztw.html

[U102] JS：本地存储
来源：http://dali.zdqjudy.top/Article/details/gt2prtjksio.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.redwolf501.top/Article/details/gt2hlzykisy.html

[U103] JS：定时器
来源：http://dali.hysaishi.cn/Article/details/gt2khcqriey.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.pycfn.com/Article/details/gt2ebmenaog.html

[U104] JS：防抖
来源：http://dali.zhengqikj.top/Article/details/gt2oecdkwym.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gt2dgrbuvnx.html

[U105] JS：节流
来源：http://dali.cheryme.top/Article/details/gt2shavhblr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yanxiufei.cn/Article/details/gt2dwpvwind.html

[U106] JS：日期格式化
来源：http://dali.ivvv.top/Article/details/gt2xlrkspas.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.pycfn.com/Article/details/gt2adqkelmq.html

[U107] JS：数字千分位
来源：http://dali.chenzaomai.com/Article/details/gt2uozswixb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jqgfzy.top/Article/details/gt2hdqvpvze.html

[U108] JS：随机整数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jconmyzq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jyoumei.cn/Article/details/gt2llljonfx.html

[U109] JS：数组分组
来源：http://dali.nanxinkj.top/Article/details/gt2xggqzzeo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ppjwa.cn/Article/details/gt2uywrtyan.html

[U110] JS：数组分块
来源：http://dali.xinyue.icu/Article/details/gt2bmdwrwve.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yueranfly.top/Article/details/gt2wmmbjmqg.html

[U111] JS：对象转 Map
来源：http://dali.svipenyu.cn/Article/details/gt2mbpgxxtr.html

new Map(Object.entries(obj))
来源：http://dali.zycfv.cn/Article/details/gt2lpspmfbn.html

[U112] JS：字符串补位
来源：http://dali.iojbl.cn/Article/details/gt2bfdcjgpl.html

"7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gt2ssxbvorl.html

[U113] JS：正则替换全部
来源：http://dali.xylfe.cn/Article/details/gt2uvhicxej.html

s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2qzqonzbg.html

[U114] JS：JSON 深比较
来源：http://dali.quarkkingdee.top/Article/details/gt2hbexkumh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258.top/Article/details/gt2yjzvnwld.html

[U115] JS：生成 UUID
来源：http://dali.cqqwz.cn/Article/details/gt2fvztblzl.html

crypto.randomUUID()
来源：http://dali.andypj.xyz/Article/details/gt2wqrtknhe.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.redwolf501.top/Article/details/gt2hcszzwvp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jqgfzy.top/Article/details/gt2pwajoquz.html

[U117] JS：单元测试
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zpjjcnmo.html

npm i -D vitest;  npx vitest
来源：http://dali.zhoulong.xyz/Article/details/gt2rgqgrvxk.html

[U118] JS：开发服务器
来源：http://dali.jlsjyb.cn/Article/details/gt2kfuxubac.html

npm i -D vite;  npx vite
来源：http://dali.svipenyu.cn/Article/details/gt2houokjfq.html

[U119] JS：生产构建
来源：http://dali.daria6918.cn/Article/details/gt2tzbncwzq.html

npx vite build
来源：http://dali.gotoacloud.top/Article/details/gt2hdurstvq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhongyouzk.top/Article/details/gt2rtusfcbl.html

import.meta.env.VITE_API_URL
来源：http://dali.yj20258888.top/Article/details/gt2ddtchwzd.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2wixntfnv.html

统计汇总
来源：http://dali.sweek.top/Article/details/gt2rimjvfoi.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2zcizgwmr.html

按语言统计（条）：
来源：http://dali.c1oappe.top/Article/details/gt2nhtokjvp.html

Python ......... 252
来源：http://dali.nanxinkj.top/Article/details/gt2eyjqjffr.html

PHP ............ 252
来源：http://dali.yuanzhike.top/Article/details/gt2jidlqpsn.html

JavaScript ..... 252
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tqayavme.html

TypeScript ..... 212
来源：http://dali.shuidangran.top/Article/details/gt2inuzrttj.html

Java ........... 212
来源：http://dali.yueranfly.top/Article/details/gt2kjmoszsw.html

Go ............. 212
来源：http://dali.aizwys.cn/Article/details/gt2afclxouq.html

Ruby ........... 212
来源：http://dali.havefunace.top/Article/details/gt2zahralxt.html

C# ............. 212
来源：http://dali.gogol.net.cn/Article/details/gt2lifqcakd.html

C .............. 30
来源：http://dali.yangfankeji.com/Article/details/gt2dhqxczhr.html

C++ ............ 30
来源：http://dali.birdmap.top/Article/details/gt2plrpyylu.html

SQL ............ 90
来源：http://dali.fengsongda.top/Article/details/gt2jitqpief.html

Bash ........... 80
来源：http://dali.sysykeji.top/Article/details/gt2lpccztau.html

Kotlin ......... 15
来源：http://dali.tanke756.top/Article/details/gt2ecxwyyzb.html

Swift .......... 15
来源：http://dali.nanxinkj.top/Article/details/gt2tlnqvvrz.html

Lua ............ 10
来源：http://dali.quarkkingdee.top/Article/details/gt2jaocdkoq.html

Perl ........... 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vcfljeco.html

Scala .......... 10
来源：http://dali.redwolf501.top/Article/details/gt2efgcagbg.html

------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gt2qarkfwnc.html

合计 ........... 2106 条
来源：http://dali.ybcxt.top/Article/details/gt2dzgfsbdc.html

按章节统计：
来源：http://dali.ppjwa.cn/Article/details/gt2xhzevrxw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hysaishi.cn/Article/details/gt2khbkzqlb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hfpthk.cn/Article/details/gt2kvzqwzhm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yuanzhike.top/Article/details/gt2tjfgihcx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xziqi.cn/Article/details/gt2idtjnxez.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shangyingyoupin.top/Article/details/gt2staqurbv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shzxlz.cn/Article/details/gt2imrjoaqq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jianghu66.top/Article/details/gt2egcmrsuh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ybcxt.top/Article/details/gt2dowbspew.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gt2xugjidkl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hysaishi.cn/Article/details/gt2akkedcas.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gt2xzeakdst.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2plvamnnp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gt2xqwjumhh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.dashuyun.cn/Article/details/gt2qttcsclg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ybcxt.top/Article/details/gt2fmfblrey.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gt2riqepfzi.html

Q SQL 专题                              90
来源：http://dali.yj20258.top/Article/details/gt2irrrdfyk.html

R Bash 专题                             80
来源：http://dali.ydzc1.top/Article/details/gt2aajeqwek.html

S C / C++ 专题                          60
来源：http://dali.yj20258888.top/Article/details/gt2fegdznmb.html

T 其他语言补充                          60
来源：http://dali.sysykeji.top/Article/details/gt2utzmjtfk.html

U 高频实用片段                         120
来源：http://dali.dianchejie.cn/Article/details/gt2oixlzyur.html

------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ogzsqptg.html

合计                                  2106 条
来源：http://dali.dashuyun.cn/Article/details/gt2gtoesfjh.html

--------------------------------------------------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gt2fsltzejo.html

使用提醒
来源：http://dali.quarkkingdee.top/Article/details/gt2kfceejxi.html

--------------------------------------------------------------------------------
来源：http://dali.316326.xyz/Article/details/gt2rlskpouo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.iojbl.cn/Article/details/gt2edymlygp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zycfv.cn/Article/details/gt2wjhfapxx.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yongpay.top/Article/details/gt2sxflvdwr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.svipenyu.cn/Article/details/gt2zlaameac.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.gogol.net.cn/Article/details/gt2drxfyzmu.html

—— 文件结束 ——
来源：http://dali.cucudq.cn/Article/details/gt2ngujkwfi.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2otxayaac.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shzxlz.cn/Article/details/gt2bynedpwn.html

Common Programming Examples Cheat Book
来源：http://dali.jqgfzy.top/Article/details/gt2wslxfezu.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2fdwfszzk.html

【收录内容】
来源：http://dali.yj202588.top/Article/details/gt2fakfixok.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hongshengwenyu.top/Article/details/gt2tkjplpgm.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.vqdsnc.cn/Article/details/gt2gwxryccb.html

SQL · Bash · C · C++
来源：http://dali.yanxiufei.cn/Article/details/gt2dejltxdh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yj20258888.top/Article/details/gt2mvymyfkl.html

【使用说明】
来源：http://dali.zhoulong.xyz/Article/details/gt2hmiixncd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.316326.xyz/Article/details/gt2bqgfrjbn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.dianchejie.cn/Article/details/gt2cjqbktvd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xylfe.cn/Article/details/gt2wqtjdpzo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.sxryk.cn/Article/details/gt2npwnywwc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yj20258888.top/Article/details/gt2ytreyxde.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yangfankeji.com/Article/details/gt2jphegoll.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wrtdhmji.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hnqzz.top/Article/details/gt2wpvfenml.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.feifeiyinyue.top/Article/details/gt2pdwbiyaf.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jqgufenzy.top/Article/details/gt2hnxgrywg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hfpthk.cn/Article/details/gt2jhsfkvyi.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhiwuduotai.top/Article/details/gt2isekbdoi.html

【文件统计】
来源：http://dali.iojbl.cn/Article/details/gt2vdidypws.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yj202588.top/Article/details/gt2htiimnnv.html

--------------------------------------------------------------------------------
来源：http://dali.fengsongda.top/Article/details/gt2zqyoiwxn.html

目  录
来源：http://dali.jyoumei.cn/Article/details/gt2lhwimxin.html

--------------------------------------------------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gt2xokypddx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cheryme.top/Article/details/gt2fitkvvxu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2owauspic.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.gotoacloud.top/Article/details/gt2nfvurbnz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.daria6918.cn/Article/details/gt2atosdrll.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.daxiang520.top/Article/details/gt2vxhhplrz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhengqikj.top/Article/details/gt2daiwezye.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2miponeec.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2nymwywyn.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2cmtkyxvv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.meibo888.top/Article/details/gt2abxtozpa.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ykajvxvu.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gt2mynlbwdo.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cdnleiting.top/Article/details/gt2apcuieey.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.dianchejie.cn/Article/details/gt2cyyxzesa.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.chenzaomai.com/Article/details/gt2qaywdxsm.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gt2otckkvaw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yuanzhike.top/Article/details/gt2muinpoib.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ivvv.top/Article/details/gt2uhvxrehz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.chenzaomai.com/Article/details/gt2ypgamfad.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guannengcc.top/Article/details/gt2qexonsrt.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jianghu66.top/Article/details/gt2whbrkwyw.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2gftnqnbg.html

A. 基础语法与类型
来源：http://dali.xziqi.cn/Article/details/gt2yzopphnp.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2ytyetdgf.html

[A01] Hello World
来源：http://dali.xziqi.cn/Article/details/gt2fosopndf.html

Py:   print("Hello, World!")
来源：http://dali.yueranfly.top/Article/details/gt2txvztvgp.html

PHP:  echo "Hello, World!";
来源：http://dali.shuidangran.top/Article/details/gt2wcfrqxan.html

JS:   console.log("Hello, World!");
来源：http://dali.cdnleiting.top/Article/details/gt2bdjlqkct.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wcrdvhtf.html

Java: System.out.println("Hello, World!");
来源：http://dali.hammf.cn/Article/details/gt2eexlvcme.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.chenlongwang.top/Article/details/gt2xbzaebts.html

Ruby: puts "Hello, World!"
来源：http://dali.9152youxi.cn/Article/details/gt2sgrvdupx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jlsjyb.cn/Article/details/gt2nbmpqztx.html

[A02] 变量声明与赋值
来源：http://dali.sysykeji.top/Article/details/gt2haabgynk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cdnleiting.top/Article/details/gt2zjurlsgm.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2razkudlm.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hammf.cn/Article/details/gt2boakcdon.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xuanzx.com/Article/details/gt2irmgaqdv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jianghu66.top/Article/details/gt2dajciurx.html

Go:   name := "Alex"; age := 20
来源：http://dali.jianghu66.top/Article/details/gt2efdfbrzx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.chenlongwang.top/Article/details/gt2ckfkjaqj.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hammf.cn/Article/details/gt2erzabgxb.html

[A03] 常量定义
来源：http://dali.hammf.cn/Article/details/gt2zrbqaelg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.svipenyu.cn/Article/details/gt2hfafclnx.html

PHP:  const PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gt2oytnfjax.html

JS:   const PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gt2wgxpbgyu.html

TS:   const PI: number = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gt2piauuwgt.html

Java: static final double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gt2repsuenp.html

Go:   const PI = 3.14159
来源：http://dali.ybcxt.top/Article/details/gt2gsryotou.html

Ruby: PI = 3.14159
来源：http://dali.yj20258888.top/Article/details/gt2sddikhct.html

C#:   const double PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gt2asbgxtrx.html

[A04] 判断变量类型
来源：http://dali.yuxming.cn/Article/details/gt2mxbioduc.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uhedkecr.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jlsjyb.cn/Article/details/gt2btzswcpl.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.redwolf501.top/Article/details/gt2rjroryxj.html

TS:   typeof x; x instanceof Date
来源：http://dali.316326.xyz/Article/details/gt2shjolutk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.cucudq.cn/Article/details/gt2vmhmcmss.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yuxming.cn/Article/details/gt2odehacuf.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.nwbrower.top/Article/details/gt2dpmvricm.html

C#:   x.GetType().Name; x is int
来源：http://dali.cqqwz.cn/Article/details/gt2cvvovvbz.html

[A05] 整数除法与取模
来源：http://dali.quarkkingdee.top/Article/details/gt2qkdwmmwg.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jinqigfzy.top/Article/details/gt2ikbdiupa.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gt2vmqeewup.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sweek.top/Article/details/gt2gbxdjlun.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.daxiang520.top/Article/details/gt2chvsdiul.html

Java: 7 / 2; 7 % 2
来源：http://dali.ivvv.top/Article/details/gt2shpcvhic.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gt2qmcicdje.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.daria6918.cn/Article/details/gt2jgsfywaj.html

C#:   7 / 2; 7 % 2
来源：http://dali.sxryk.cn/Article/details/gt2xyddckwp.html

[A06] 字符串转数字
来源：http://dali.zhongyouzk.top/Article/details/gt2kdeuutsi.html

Py:   int("42"); float("3.14")
来源：http://dali.sufxvd.cn/Article/details/gt2siocvrdg.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.wangshuangyany.cn/Article/details/gt2tumxqtdy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.daxiang520.top/Article/details/gt2tzuizsxu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hongshengwenyu.top/Article/details/gt2tvbsnokq.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhengqikj.top/Article/details/gt2frkgogsn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.guowangkeji.top/Article/details/gt2ehdekcow.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yonumen.top/Article/details/gt2rbpscqmb.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.dashuyun.cn/Article/details/gt2yyftfliv.html

[A07] 数字转字符串
来源：http://dali.fzhhl.top/Article/details/gt2vogvryst.html

Py:   str(42)
来源：http://dali.zhongyouzk.top/Article/details/gt2mkpbjntd.html

PHP:  (string) 42; strval(42)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jefbvnzb.html

JS:   String(42); (42).toString()
来源：http://dali.ydzc1.top/Article/details/gt2soqbwymd.html

TS:   String(42)
来源：http://dali.zhoulong.xyz/Article/details/gt2qlrnpyuf.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.hnxiangtu.top/Article/details/gt2kkfviogo.html

Go:   strconv.Itoa(42)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2slnaxaez.html

Ruby: 42.to_s
来源：http://dali.gaohongyu789.top/Article/details/gt2phquzswu.html

C#:   42.ToString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ccnyobxv.html

[A08] 取整与四舍五入
来源：http://dali.0kj1m.cn/Article/details/gt2zymkgfyj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mhebgdnh.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yuanzhike.top/Article/details/gt2cdhulnys.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yueranfly.top/Article/details/gt2dasldhnh.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2umqgwfxz.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.sufxvd.cn/Article/details/gt2vgjrcdia.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.9152youxi.cn/Article/details/gt2ebkqartz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.birdmap.top/Article/details/gt2mzwpghvb.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.quarkkingdee.top/Article/details/gt2yaevzhdy.html

[A09] 绝对值与最大最小值
来源：http://dali.pycfn.com/Article/details/gt2afhrzzpn.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xziqi.cn/Article/details/gt2zbclnlmf.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gt2yvauyaaw.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.xuanzx.com/Article/details/gt2ctyruzps.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2tmnxhdvf.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2unbpaggq.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.dashuyun.cn/Article/details/gt2unmkxsdu.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.iojbl.cn/Article/details/gt2cmfdofes.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yj202588.top/Article/details/gt2cgzhyaum.html

[A10] 生成随机数
来源：http://dali.wangdashe.top/Article/details/gt2mwnmvfry.html

Py:   import random; random.randint(1, 100)
来源：http://dali.aizwys.cn/Article/details/gt2kgswsaov.html

PHP:  random_int(1, 100);
来源：http://dali.nanxuanxn.top/Article/details/gt2fjgppwrj.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mdxkokmb.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yangfankeji.com/Article/details/gt2mtujdkzd.html

Java: new Random().nextInt(100) + 1
来源：http://dali.xinyue.icu/Article/details/gt2ptbqohfy.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yuxming.cn/Article/details/gt2qiueqioy.html

Ruby: rand(1..100)
来源：http://dali.zycfv.cn/Article/details/gt2pjvmbibs.html

C#:   new Random().Next(1, 101)
来源：http://dali.svipenyu.cn/Article/details/gt2nwxkyygv.html

[A11] 条件表达式（三元）
来源：http://dali.wangshuangyany.cn/Article/details/gt2cakgfohn.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2szwzlsxp.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.gogol.net.cn/Article/details/gt2ggjpafuh.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.kuanghao11.cn/Article/details/gt2nhzkooqs.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.iojbl.cn/Article/details/gt2lnbsgdfs.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ncflzvag.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.shuidangran.top/Article/details/gt2tnmqcrsu.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vdprbphb.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.kuanghao11.cn/Article/details/gt2habplosv.html

[A12] 字符串插值 / 格式化
来源：http://dali.yj202588.top/Article/details/gt2dswfquhh.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.aizwys.cn/Article/details/gt2xadryibm.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.316326.xyz/Article/details/gt2zwlfgigs.html

JS:   `Hello, ${name}!`
来源：http://dali.xuetiantiany.cn/Article/details/gt2vasimmrd.html

TS:   `Hello, ${name}!`
来源：http://dali.guowangkeji.top/Article/details/gt2vfdvunts.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhoulong.xyz/Article/details/gt2ygcjxpmt.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.svipenyu.cn/Article/details/gt2jkcnccbo.html

Ruby: "Hello, #{name}!"
来源：http://dali.gaohongyu789.top/Article/details/gt2sgixobwz.html

C#:   $"Hello, {name}!"
来源：http://dali.xuanzx.com/Article/details/gt2fnadwdty.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.nwbrower.top/Article/details/gt2xkfrvovt.html

Py:   "第一行\n第二行"
来源：http://dali.zhixingplan.top/Article/details/gt2jivtynzz.html

PHP:  "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gt2dtelirza.html

JS:   "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gt2nhtsbyam.html

TS:   "第一行\n第二行"
来源：http://dali.316326.xyz/Article/details/gt2hgutbesb.html

Java: "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gt2bqkoskmo.html

Go:   "第一行\n第二行"
来源：http://dali.zhiwuduotai.top/Article/details/gt2dywzxmiv.html

Ruby: "第一行\n第二行"
来源：http://dali.yvedp.cn/Article/details/gt2quhwnczu.html

C#:   "第一行\n第二行"
来源：http://dali.haohaochexian.top/Article/details/gt2dlpskstx.html

[A14] 注释写法
来源：http://dali.sweek.top/Article/details/gt2gckusnfu.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.hysaishi.cn/Article/details/gt2zlskbpfw.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.iojbl.cn/Article/details/gt2fktxsfmj.html

JS:   // 单行；/* 多行 */
来源：http://dali.quarkkingdee.top/Article/details/gt2kyobbrqx.html

TS:   // 单行；/* 多行 */
来源：http://dali.shuidangran.top/Article/details/gt2fjstxztm.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.birdmap.top/Article/details/gt2gbteipcm.html

Go:   // 单行；/* 多行 */
来源：http://dali.feifeiyinyue.top/Article/details/gt2rchkzfcp.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.dianchejie.cn/Article/details/gt2tzxdddxj.html

C#:   // 单行；/* 多行 */
来源：http://dali.jianghu66.top/Article/details/gt2zrcnutnn.html

[A15] 空值判断与默认值
来源：http://dali.hnqzz.top/Article/details/gt2dkdgapnf.html

Py:   value = data or "默认值"
来源：http://dali.zhoulong.xyz/Article/details/gt2pwbbrahe.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yangfankeji.com/Article/details/gt2chkneqqm.html

JS:   const value = data ?? "默认值";
来源：http://dali.sweek.top/Article/details/gt2wggnlflv.html

TS:   const value = data ?? "默认值";
来源：http://dali.sysykeji.top/Article/details/gt2juvvkqlu.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.pengpengdd.cyou/Article/details/gt2miuangdc.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2meaywlch.html

Ruby: value = data || "默认值"
来源：http://dali.xziqi.cn/Article/details/gt2kknocvws.html

C#:   var value = data ?? "默认值";
来源：http://dali.smart0.xyz/Article/details/gt2wureqhkm.html

[A16] 真假值判断规则
来源：http://dali.pengpengdd.cyou/Article/details/gt2ekgxpuyw.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.svipenyu.cn/Article/details/gt2ihsdiscg.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xylfe.cn/Article/details/gt2tpmpyuml.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.birdmap.top/Article/details/gt2lkjnwihw.html

TS:   if (!x) {}
来源：http://dali.yuanzhike.top/Article/details/gt2uqcfbuhu.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jianghu66.top/Article/details/gt2niwdudmi.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.gotoacloud.top/Article/details/gt2rvmremkv.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.cashguo.top/Article/details/gt2mxmnektp.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.sufxvd.cn/Article/details/gt2ewmbnlxz.html

[A17] 位运算
来源：http://dali.svipenyu.cn/Article/details/gt2cayorsju.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cqqwz.cn/Article/details/gt2bqiuchbf.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.nwbrower.top/Article/details/gt2npfhxyim.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2lgpjxehg.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gt2btpqcnrm.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2qyclrgmz.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gt2ytbyiieb.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2czfvqyqr.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cashguo.top/Article/details/gt2mhfonclr.html


<!-- 参考信息 -->