代发 wailian999

[U101] JS：classList 操作
来源：http://dali.mhx1999.top/Article/details/gt2gxltgdsx.html

el.classList.toggle("active")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bmwyfuoe.html

[U102] JS：本地存储
来源：http://dali.yj20258888.top/Article/details/gt2ydkrxime.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nwbrower.top/Article/details/gt2ptgztrlc.html

[U103] JS：定时器
来源：http://dali.dashuyun.cn/Article/details/gt2lmemvoff.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.dashuyun.cn/Article/details/gt2szuqzvjv.html

[U104] JS：防抖
来源：http://dali.snrcjt.cn/Article/details/gt2awoayicn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gt2gadroxjn.html

[U105] JS：节流
来源：http://dali.ydzc1.top/Article/details/gt2ybwswpzv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shzxlz.cn/Article/details/gt2ujbomkci.html

[U106] JS：日期格式化
来源：http://dali.tianlin.xyz/Article/details/gt2siwmdidf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shuidangran.top/Article/details/gt2farkgtej.html

[U107] JS：数字千分位
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dvterohx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.bjfxy.top/Article/details/gt2lloejpgn.html

[U108] JS：随机整数
来源：http://dali.jyoumei.cn/Article/details/gt2qyxjsptk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.dianchejie.cn/Article/details/gt2ldonubjj.html

[U109] JS：数组分组
来源：http://dali.jqgfzy.top/Article/details/gt2icwbhoky.html

Object.groupBy(arr, x => x.type)
来源：http://dali.haohaochexian.top/Article/details/gt2tavpwmpc.html

[U110] JS：数组分块
来源：http://dali.gotoacloud.top/Article/details/gt2cspfebmu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jyoumei.cn/Article/details/gt2rmabfehh.html

[U111] JS：对象转 Map
来源：http://dali.yuanzhike.top/Article/details/gt2jyurglcn.html

new Map(Object.entries(obj))
来源：http://dali.yj20258.top/Article/details/gt2bmhjyvyn.html

[U112] JS：字符串补位
来源：http://dali.chenjidiqi.icu/Article/details/gt2hufbmitq.html

"7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gt2lyjcptfp.html

[U113] JS：正则替换全部
来源：http://dali.yj202588.top/Article/details/gt2pqsiaetl.html

s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aamrqzun.html

[U114] JS：JSON 深比较
来源：http://dali.nwbrower.top/Article/details/gt2hxmjteet.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.birdmap.top/Article/details/gt2kixyucoc.html

[U115] JS：生成 UUID
来源：http://dali.hammf.cn/Article/details/gt2jnrlocyj.html

crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gt2lltrfkvk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gogol.net.cn/Article/details/gt2rwurnhmw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhengqikj.top/Article/details/gt2nmbchgbp.html

[U117] JS：单元测试
来源：http://dali.jianghu66.top/Article/details/gt2fvwcfqpm.html

npm i -D vitest;  npx vitest
来源：http://dali.jiagoushi.top/Article/details/gt2zvkotjsq.html

[U118] JS：开发服务器
来源：http://dali.ybcxt.top/Article/details/gt2tlayrvvp.html

npm i -D vite;  npx vite
来源：http://dali.xuetiantiany.cn/Article/details/gt2pcjddhng.html

[U119] JS：生产构建
来源：http://dali.tianlin.xyz/Article/details/gt2niuigrnh.html

npx vite build
来源：http://dali.zhiwuduotai.top/Article/details/gt2eugeykck.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhiwuduotai.top/Article/details/gt2gcmxdgyw.html

import.meta.env.VITE_API_URL
来源：http://dali.jinqigfzy.top/Article/details/gt2wuwojtbi.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2nwwalysk.html

统计汇总
来源：http://dali.jinqigufen.top/Article/details/gt2vdlmihlh.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2rqhurvgv.html

按语言统计（条）：
来源：http://dali.yuanzhike.top/Article/details/gt2ixmjvzbn.html

Python ......... 252
来源：http://dali.aizwys.cn/Article/details/gt2ekapssyz.html

PHP ............ 252
来源：http://dali.wangshuangyany.cn/Article/details/gt2imaurvsm.html

JavaScript ..... 252
来源：http://dali.meibo888.top/Article/details/gt2aehrsjlw.html

TypeScript ..... 212
来源：http://dali.xuanzx.com/Article/details/gt2clypfwam.html

Java ........... 212
来源：http://dali.shzxlz.cn/Article/details/gt2zldpckxr.html

Go ............. 212
来源：http://dali.dashuyun.cn/Article/details/gt2hyyxupvd.html

Ruby ........... 212
来源：http://dali.mhx1999.top/Article/details/gt2tlxicizf.html

C# ............. 212
来源：http://dali.sxryk.cn/Article/details/gt2fokzpqrn.html

C .............. 30
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sqcjjvox.html

C++ ............ 30
来源：http://dali.aibaodan.cn/Article/details/gt2eaelwvdk.html

SQL ............ 90
来源：http://dali.nwbrower.top/Article/details/gt2pmuushtw.html

Bash ........... 80
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rndkvmvm.html

Kotlin ......... 15
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vncdkprb.html

Swift .......... 15
来源：http://dali.hongshengwenyu.top/Article/details/gt2qpuegoen.html

Lua ............ 10
来源：http://dali.xziqi.cn/Article/details/gt2rbxhxrzq.html

Perl ........... 10
来源：http://dali.pycfn.com/Article/details/gt2acmouzuj.html

Scala .......... 10
来源：http://dali.cheryme.top/Article/details/gt2pqjaxuwi.html

------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gt2ziwgbbmn.html

合计 ........... 2106 条
来源：http://dali.zhongyouzk.top/Article/details/gt2gnutmhfn.html

按章节统计：
来源：http://dali.xylfe.cn/Article/details/gt2wabxcwwi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xziqi.cn/Article/details/gt2bgwzdprj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sweek.top/Article/details/gt2xckbndtt.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wrinifzh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cqqwz.cn/Article/details/gt2oneyexou.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jyoumei.cn/Article/details/gt2imfdnvbc.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.guannengcc.top/Article/details/gt2qunhdgki.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.wangdashe.top/Article/details/gt2xetnizyx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rowmvucr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zyeunklj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.0kj1m.cn/Article/details/gt2zuoojhmt.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jqgufenzy.top/Article/details/gt2mrlvcuzl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhiwuduotai.top/Article/details/gt2zovuvtix.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gt2roivwphc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zycfv.cn/Article/details/gt2hpztarjw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xinyue.icu/Article/details/gt2diwefxdm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gt2tksbtnoc.html

Q SQL 专题                              90
来源：http://dali.wangshuangyany.cn/Article/details/gt2kklumpds.html

R Bash 专题                             80
来源：http://dali.guannengcc.top/Article/details/gt2qbnkchtc.html

S C / C++ 专题                          60
来源：http://dali.gotoacloud.top/Article/details/gt2vyebcljp.html

T 其他语言补充                          60
来源：http://dali.ivvv.top/Article/details/gt2vnivmfsn.html

U 高频实用片段                         120
来源：http://dali.tian-w.cn/Article/details/gt2kxmxpqwv.html

------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gt2igcsomeo.html

合计                                  2106 条
来源：http://dali.gaohongyu789.top/Article/details/gt2ticnyhfz.html

--------------------------------------------------------------------------------
来源：http://dali.yongpay.top/Article/details/gt2ntkfiaiy.html

使用提醒
来源：http://dali.hnxiangtu.top/Article/details/gt2pmuyhpdn.html

--------------------------------------------------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gt2mnyuyvvl.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xuetiantiany.cn/Article/details/gt2zguqfufx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.shzxlz.cn/Article/details/gt2tnejxihb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yvedp.cn/Article/details/gt2ixietizj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yuanzhike.top/Article/details/gt2wksvwdik.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jinqigfzy.top/Article/details/gt2uhrztoij.html

—— 文件结束 ——
来源：http://dali.smart0.xyz/Article/details/gt2qwesrgup.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2wixnadrr.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhongyouzk.top/Article/details/gt2smgkchwo.html

Common Programming Examples Cheat Book
来源：http://dali.feifeiyinyue.top/Article/details/gt2zbsggtyy.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2lkrgfhlc.html

【收录内容】
来源：http://dali.birdmap.top/Article/details/gt2zfflhtqm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xuanzx.com/Article/details/gt2fwibzljb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cheryme.top/Article/details/gt2osuhqgjv.html

SQL · Bash · C · C++
来源：http://dali.dianchejie.cn/Article/details/gt2wvqfyvyq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yvedp.cn/Article/details/gt2ibqvjhkc.html

【使用说明】
来源：http://dali.pengpengdd.cyou/Article/details/gt2niuwejoa.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.sysykeji.top/Article/details/gt2iljehpoi.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.quarkkingdee.top/Article/details/gt2wrbkplnk.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hdwarwho.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhixingplan.top/Article/details/gt2mywmniai.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xinyue.icu/Article/details/gt2eepofebj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ybcxt.top/Article/details/gt2msvzqmxa.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yvedp.cn/Article/details/gt2wzgpophd.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.fengsongda.top/Article/details/gt2nwbcxuzl.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hfpthk.cn/Article/details/gt2aaplovwq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yj20258888.top/Article/details/gt2sdxclxpj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.smart0.xyz/Article/details/gt2fyxuycih.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yonumen.top/Article/details/gt2dokwzetq.html

【文件统计】
来源：http://dali.gogol.net.cn/Article/details/gt2ueydmudv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jqgfzy.top/Article/details/gt2jnobzaml.html

--------------------------------------------------------------------------------
来源：http://dali.yuxming.cn/Article/details/gt2njeisrke.html

目  录
来源：http://dali.316326.xyz/Article/details/gt2dthpifqa.html

--------------------------------------------------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gt2idwwcyhr.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cqqwz.cn/Article/details/gt2xqxdhtpg.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.pengpengdd.cyou/Article/details/gt2gxjtjfkh.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.andypj.xyz/Article/details/gt2bffdhklj.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wbefxsxw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ehwqpu.com/Article/details/gt2feebehuk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yuanzhike.top/Article/details/gt2elikvxgu.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yvedp.cn/Article/details/gt2qzxxyspf.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2zufwzhzc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ehwqpu.com/Article/details/gt2mozueqmh.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yj20258888.top/Article/details/gt2byaxocqk.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gt2oikdogyo.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.daria6918.cn/Article/details/gt2wniefxyz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.ivvv.top/Article/details/gt2ljhgdimi.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.iojbl.cn/Article/details/gt2jgiijgcb.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yangfankeji.com/Article/details/gt2ecszhnlx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2khhwmskl.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.svipenyu.cn/Article/details/gt2flylluim.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.gogol.net.cn/Article/details/gt2uztvpamd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2skzzkyvx.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangdashe.top/Article/details/gt2ipgrhjxt.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuanzhike.top/Article/details/gt2gcsnvelf.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2ozseksda.html

A. 基础语法与类型
来源：http://dali.quarkkingdee.top/Article/details/gt2qbfrsayq.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2tgdkhitz.html

[A01] Hello World
来源：http://dali.havefunace.top/Article/details/gt2aucbjvwu.html

Py:   print("Hello, World!")
来源：http://dali.shangyingyoupin.top/Article/details/gt2bygfsbyp.html

PHP:  echo "Hello, World!";
来源：http://dali.yanxiufei.cn/Article/details/gt2zzgibelq.html

JS:   console.log("Hello, World!");
来源：http://dali.ydzc1.top/Article/details/gt2pmlclzvn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.316326.xyz/Article/details/gt2vbnruezl.html

Java: System.out.println("Hello, World!");
来源：http://dali.birdmap.top/Article/details/gt2nogzjdvk.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jianghu66.top/Article/details/gt2uocwxgxb.html

Ruby: puts "Hello, World!"
来源：http://dali.yj20258.top/Article/details/gt2nkzliemi.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.chenjidiqi.icu/Article/details/gt2atyctmkf.html

[A02] 变量声明与赋值
来源：http://dali.gaohongyu789.top/Article/details/gt2tziecfnz.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.daxiang520.top/Article/details/gt2seqvnyua.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jianghu66.top/Article/details/gt2oihvofew.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ybcxt.top/Article/details/gt2zutlmdsh.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jyoumei.cn/Article/details/gt2jqahmals.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hywenlv.cn/Article/details/gt2bzhkncap.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvvuhbq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.iojbl.cn/Article/details/gt2yjqjpntl.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jqgufenzy.top/Article/details/gt2ucelmgvw.html

[A03] 常量定义
来源：http://dali.yj202588.top/Article/details/gt2ckcipjid.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.tian-w.cn/Article/details/gt2hkvscmay.html

PHP:  const PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gt2zkzthozr.html

JS:   const PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gt2pzuajmfj.html

TS:   const PI: number = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gt2ubsmieea.html

Java: static final double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gt2vxvsraos.html

Go:   const PI = 3.14159
来源：http://dali.zdqjudy.top/Article/details/gt2pjagmggh.html

Ruby: PI = 3.14159
来源：http://dali.daxiang520.top/Article/details/gt2gowpyzro.html

C#:   const double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gt2brvyvspo.html

[A04] 判断变量类型
来源：http://dali.jqgfzy.top/Article/details/gt2rjgmfmjv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xylfe.cn/Article/details/gt2kuyiipav.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hnxiangtu.top/Article/details/gt2meybtert.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.pengpengdd.cyou/Article/details/gt2bwfzzhhb.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cpmqkguw.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.vqdsnc.cn/Article/details/gt2tipnodce.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xinyue.icu/Article/details/gt2hqpevukz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jlsjyb.cn/Article/details/gt2wqifmavo.html

C#:   x.GetType().Name; x is int
来源：http://dali.0kj1m.cn/Article/details/gt2mwjdfkmg.html

[A05] 整数除法与取模
来源：http://dali.gaohongyu789.top/Article/details/gt2zrtyzkzo.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2soawxbbm.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gt2ldfntmmf.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gt2bwgtunkf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gzhubu.top/Article/details/gt2znkrzrca.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhoulong.xyz/Article/details/gt2dbyxqnfs.html

Go:   7 / 2; 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gt2uehtelqk.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yonumen.top/Article/details/gt2dpvbazoc.html

C#:   7 / 2; 7 % 2
来源：http://dali.wangdashe.top/Article/details/gt2fumbdvsn.html

[A06] 字符串转数字
来源：http://dali.hnqzz.top/Article/details/gt2khhfyriz.html

Py:   int("42"); float("3.14")
来源：http://dali.yangfankeji.com/Article/details/gt2bqxscmjn.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.c1oappe.top/Article/details/gt2eqnktzse.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.0kj1m.cn/Article/details/gt2maihmhdk.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.dashuyun.cn/Article/details/gt2pvbfabqv.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.chenzaomai.com/Article/details/gt2pinimglf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jqgfzy.top/Article/details/gt2rqyxumnm.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.xziqi.cn/Article/details/gt2rlkasawo.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jianghu66.top/Article/details/gt2vnpczfuw.html

[A07] 数字转字符串
来源：http://dali.yuxming.cn/Article/details/gt2asrlfxel.html

Py:   str(42)
来源：http://dali.yj20258888.top/Article/details/gt2zpetoocu.html

PHP:  (string) 42; strval(42)
来源：http://dali.xziqi.cn/Article/details/gt2qjrqymog.html

JS:   String(42); (42).toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ygsatwpm.html

TS:   String(42)
来源：http://dali.zhengqikj.top/Article/details/gt2cpvcjqbl.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.quarkkingdee.top/Article/details/gt2aecedcik.html

Go:   strconv.Itoa(42)
来源：http://dali.yuanzhike.top/Article/details/gt2ugsxoeki.html

Ruby: 42.to_s
来源：http://dali.yangfankeji.com/Article/details/gt2xwrimvtm.html

C#:   42.ToString()
来源：http://dali.yueranfly.top/Article/details/gt2qrcsyuvx.html

[A08] 取整与四舍五入
来源：http://dali.hfpthk.cn/Article/details/gt2voyisfoy.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.xziqi.cn/Article/details/gt2gpqmwvip.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.smart0.xyz/Article/details/gt2iiztvhyz.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.hysaishi.cn/Article/details/gt2townrqgh.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhixingplan.top/Article/details/gt2owtzvcuo.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gt2yqobnzbu.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.meibo888.top/Article/details/gt2nlpnerme.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.xylfe.cn/Article/details/gt2gioseffe.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.wangdashe.top/Article/details/gt2asrcdgfc.html

[A09] 绝对值与最大最小值
来源：http://dali.ehwqpu.com/Article/details/gt2pqaojqcp.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.daria6918.cn/Article/details/gt2bezalyet.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ivvv.top/Article/details/gt2djjzselp.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gt2rfphudqb.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.andypj.xyz/Article/details/gt2rlofkerl.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2txmpffat.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhoulong.xyz/Article/details/gt2sobfnvxz.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yongpay.top/Article/details/gt2heqfwdig.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2sfspkznl.html

[A10] 生成随机数
来源：http://dali.zycfv.cn/Article/details/gt2imzvbgqk.html

Py:   import random; random.randint(1, 100)
来源：http://dali.gzhubu.top/Article/details/gt2dpvvxzpd.html

PHP:  random_int(1, 100);
来源：http://dali.sweek.top/Article/details/gt2lhcpqdmi.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.tanke756.top/Article/details/gt2hetseriw.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2atnpkmpk.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yuxming.cn/Article/details/gt2thpleqmc.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.sxryk.cn/Article/details/gt2sghjhsha.html

Ruby: rand(1..100)
来源：http://dali.tanke756.top/Article/details/gt2lolwnsva.html

C#:   new Random().Next(1, 101)
来源：http://dali.yueranfly.top/Article/details/gt2tpgfkfxh.html

[A11] 条件表达式（三元）
来源：http://dali.guowangkeji.top/Article/details/gt2ieqbfrva.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yj202588.top/Article/details/gt2teybhngg.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.fengsongda.top/Article/details/gt2mpodsfbr.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.daria6918.cn/Article/details/gt2tfbdkmos.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yj20258888.top/Article/details/gt2rmtdnyyt.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yj202588.top/Article/details/gt2kxocuvwd.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rxznpawo.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jlsjyb.cn/Article/details/gt2rjayxqpk.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yuxming.cn/Article/details/gt2dogdvyze.html

[A12] 字符串插值 / 格式化
来源：http://dali.dashuyun.cn/Article/details/gt2fwtflzax.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yj202588.top/Article/details/gt2fpltvqhw.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.bjfxy.top/Article/details/gt2qlwypalu.html

JS:   `Hello, ${name}!`
来源：http://dali.yonumen.top/Article/details/gt2rnijuyaw.html

TS:   `Hello, ${name}!`
来源：http://dali.daxiang520.top/Article/details/gt2kxgzijgh.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yangfankeji.com/Article/details/gt2ayozuxux.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.snrcjt.cn/Article/details/gt2yiolbzqf.html

Ruby: "Hello, #{name}!"
来源：http://dali.sufxvd.cn/Article/details/gt2caepwrvw.html

C#:   $"Hello, {name}!"
来源：http://dali.tian-w.cn/Article/details/gt2osvimhpe.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.sufxvd.cn/Article/details/gt2azqhvecn.html

Py:   "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gt2iuohhuia.html

PHP:  "第一行\n第二行"
来源：http://dali.shuidangran.top/Article/details/gt2rfqvywuy.html

JS:   "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gt2fknxgbjk.html

TS:   "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gt2aataofoh.html

Java: "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gt2nplfthot.html

Go:   "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gt2hujbhoxk.html

Ruby: "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gt2dcgovhar.html

C#:   "第一行\n第二行"
来源：http://dali.316326.xyz/Article/details/gt2pzqbidak.html

[A14] 注释写法
来源：http://dali.shangyingyoupin.top/Article/details/gt2yebmqjcv.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.mhx1999.top/Article/details/gt2tkjgthgw.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yvedp.cn/Article/details/gt2ojizgqfn.html

JS:   // 单行；/* 多行 */
来源：http://dali.gotoacloud.top/Article/details/gt2inhifqvr.html

TS:   // 单行；/* 多行 */
来源：http://dali.jyoumei.cn/Article/details/gt2cqemvgld.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.gaohongyu789.top/Article/details/gt2huxhixzs.html

Go:   // 单行；/* 多行 */
来源：http://dali.dashuyun.cn/Article/details/gt2ukitcfro.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.xuanzx.com/Article/details/gt2kttyhqmx.html

C#:   // 单行；/* 多行 */
来源：http://dali.xuanzx.com/Article/details/gt2dgvaedup.html

[A15] 空值判断与默认值
来源：http://dali.andypj.xyz/Article/details/gt2cpazmbme.html

Py:   value = data or "默认值"
来源：http://dali.cqqwz.cn/Article/details/gt2buztqmes.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.gotoacloud.top/Article/details/gt2anukilbb.html

JS:   const value = data ?? "默认值";
来源：http://dali.jiagoushi.top/Article/details/gt2hzhujgkc.html

TS:   const value = data ?? "默认值";
来源：http://dali.c1oappe.top/Article/details/gt2vlcaqlwy.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.hysaishi.cn/Article/details/gt2gqfqbbnx.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bcdcrzmd.html

Ruby: value = data || "默认值"
来源：http://dali.nwbrower.top/Article/details/gt2vqjjnbvm.html

C#:   var value = data ?? "默认值";
来源：http://dali.meibo888.top/Article/details/gt2bhfmmfug.html

[A16] 真假值判断规则
来源：http://dali.ydzc1.top/Article/details/gt2lhuduwcn.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.hywenlv.cn/Article/details/gt2nenspoox.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.shuidangran.top/Article/details/gt2zekdmysp.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.nanxinkj.top/Article/details/gt2sefspbdm.html

TS:   if (!x) {}
来源：http://dali.chenzaomai.com/Article/details/gt2qldwopzc.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.chenlongwang.top/Article/details/gt2osazibbp.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.xinyue.icu/Article/details/gt2ihubavxr.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.hnqzz.top/Article/details/gt2yrhmrfjw.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2rpqdubsn.html

[A17] 位运算
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qdmilegd.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yangfankeji.com/Article/details/gt2acumgxio.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2bcgitjix.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ydzc1.top/Article/details/gt2aafpojml.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gt2uknnazei.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.havefunace.top/Article/details/gt2zbhvziii.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.hammf.cn/Article/details/gt2gaeqrmmx.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnqzz.top/Article/details/gt2nufsfyml.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhongyouzk.top/Article/details/gt2hdblbezb.html


<!-- 参考信息 -->