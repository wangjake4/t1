代发 wailian999

[U99] JS：事件监听
来源：http://dali.gogol.net.cn/Article/details/gtwbmepcgr.html

el.addEventListener("click", e => {})
来源：http://dali.shangyingyoupin.top/Article/details/gtuyozcdoo.html

[U100] JS：DOM 查询
来源：http://dali.jinqigfzy.top/Article/details/gtodorccdu.html

document.querySelector(".item")
来源：http://dali.daria6918.cn/Article/details/gtqglzcsfi.html

[U101] JS：classList 操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtukmujkdn.html

el.classList.toggle("active")
来源：http://dali.daria6918.cn/Article/details/gtrzazwako.html

[U102] JS：本地存储
来源：http://dali.meibo888.top/Article/details/gtmfwtlizh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jinqigfzy.top/Article/details/gtswmliypm.html

[U103] JS：定时器
来源：http://dali.smart0.xyz/Article/details/gtltmfgmsm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yj202588.top/Article/details/gtpsoytqgr.html

[U104] JS：防抖
来源：http://dali.yueranfly.top/Article/details/gtslgxhwpr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gtgxkcipbv.html

[U105] JS：节流
来源：http://dali.zycfv.cn/Article/details/gtownevbqv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tian-w.cn/Article/details/gtshubwnid.html

[U106] JS：日期格式化
来源：http://dali.xuanzx.com/Article/details/gtsiqewzrq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jiagoushi.top/Article/details/gtfbjcwuka.html

[U107] JS：数字千分位
来源：http://dali.birdmap.top/Article/details/gtdhwkcdja.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinqigufen.top/Article/details/gtglcjshbk.html

[U108] JS：随机整数
来源：http://dali.zhixingplan.top/Article/details/gtltztszzo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.quarkkingdee.top/Article/details/gtazfgdrbk.html

[U109] JS：数组分组
来源：http://dali.yonumen.top/Article/details/gtccyzpqpz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.wangdashe.top/Article/details/gtbzntuhdu.html

[U110] JS：数组分块
来源：http://dali.guannengcc.top/Article/details/gtxgqfsdtl.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xziqi.cn/Article/details/gtbmbzdmll.html

[U111] JS：对象转 Map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxtvcumt.html

new Map(Object.entries(obj))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfylrpfw.html

[U112] JS：字符串补位
来源：http://dali.cashguo.top/Article/details/gtmqggunec.html

"7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtgfovretl.html

[U113] JS：正则替换全部
来源：http://dali.hnxiangtu.top/Article/details/gtxnjkfbes.html

s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtxnpbfgxr.html

[U114] JS：JSON 深比较
来源：http://dali.hammf.cn/Article/details/gtblxmoaet.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj202588.top/Article/details/gtbudghwqj.html

[U115] JS：生成 UUID
来源：http://dali.feifeiyinyue.top/Article/details/gtuamyqiip.html

crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtaabbykwf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zdqjudy.top/Article/details/gtlprfplng.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xziqi.cn/Article/details/gtqcnrxfse.html

[U117] JS：单元测试
来源：http://dali.zhengqikj.top/Article/details/gtyocpyvnu.html

npm i -D vitest;  npx vitest
来源：http://dali.ybcxt.top/Article/details/gtqiboscba.html

[U118] JS：开发服务器
来源：http://dali.jlsjyb.cn/Article/details/gtypvcuegv.html

npm i -D vite;  npx vite
来源：http://dali.jinqigfzy.top/Article/details/gtbzvdefsj.html

[U119] JS：生产构建
来源：http://dali.tian-w.cn/Article/details/gtzqveqlhl.html

npx vite build
来源：http://dali.wangshuangyany.cn/Article/details/gtivmkiyfh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.pycfn.com/Article/details/gtzrrbzevf.html

import.meta.env.VITE_API_URL
来源：http://dali.smart0.xyz/Article/details/gthtxgetyc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtdvpofxpb.html

统计汇总
来源：http://dali.ydzc1.top/Article/details/gtjccbguoj.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtlgmzudee.html

按语言统计（条）：
来源：http://dali.yj20258.top/Article/details/gtsrofvzrc.html

Python ......... 252
来源：http://dali.ybcxt.top/Article/details/gtnmcvjfop.html

PHP ............ 252
来源：http://dali.jinqigfzy.top/Article/details/gtxkqyndln.html

JavaScript ..... 252
来源：http://dali.wangshuangyany.cn/Article/details/gtqfsjoota.html

TypeScript ..... 212
来源：http://dali.mhx1999.top/Article/details/gtykbjsuuh.html

Java ........... 212
来源：http://dali.guannengcc.top/Article/details/gthdcumzaw.html

Go ............. 212
来源：http://dali.sxryk.cn/Article/details/gtxaoscion.html

Ruby ........... 212
来源：http://dali.mhx1999.top/Article/details/gtkgogljrr.html

C# ............. 212
来源：http://dali.shzxlz.cn/Article/details/gtdqzzvmbb.html

C .............. 30
来源：http://dali.hammf.cn/Article/details/gtswdntvfm.html

C++ ............ 30
来源：http://dali.sxryk.cn/Article/details/gtopgsssmc.html

SQL ............ 90
来源：http://dali.jinqigufen.top/Article/details/gtiovrurvq.html

Bash ........... 80
来源：http://dali.ydzc1.top/Article/details/gtmgzpynht.html

Kotlin ......... 15
来源：http://dali.hysaishi.cn/Article/details/gtgtrrfbhd.html

Swift .......... 15
来源：http://dali.tianlin.xyz/Article/details/gtgxrmeqnx.html

Lua ............ 10
来源：http://dali.zhoulong.xyz/Article/details/gtgcwydyvp.html

Perl ........... 10
来源：http://dali.cqqwz.cn/Article/details/gtlbmnurgh.html

Scala .......... 10
来源：http://dali.sxryk.cn/Article/details/gtjlcgbbzc.html

------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtedjcsrof.html

合计 ........... 2106 条
来源：http://dali.cucudq.cn/Article/details/gtbluheesl.html

按章节统计：
来源：http://dali.zhixingplan.top/Article/details/gtlrnexjpt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xuanzx.com/Article/details/gtlyadnafk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258.top/Article/details/gtteiwkevh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.nanxinkj.top/Article/details/gtirmdqseh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ydzc1.top/Article/details/gtcqossayg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhoulong.xyz/Article/details/gtfsgzxsjz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hongshengwenyu.top/Article/details/gtdpgavlsi.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.andypj.xyz/Article/details/gtlmmgoebj.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.sysykeji.top/Article/details/gtwgbpvlij.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gtxmuidevn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ehwqpu.com/Article/details/gttngbqipm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gteyovzozm.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gtomypwdek.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gtgrlmtnpp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xziqi.cn/Article/details/gteslttazq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yvedp.cn/Article/details/gtnvaevefo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gtdmaeewtw.html

Q SQL 专题                              90
来源：http://dali.quarkkingdee.top/Article/details/gtvlbfupsg.html

R Bash 专题                             80
来源：http://dali.yonumen.top/Article/details/gtmuabaexq.html

S C / C++ 专题                          60
来源：http://dali.cdnleiting.top/Article/details/gtdngjookr.html

T 其他语言补充                          60
来源：http://dali.gogol.net.cn/Article/details/gttaoithcx.html

U 高频实用片段                         120
来源：http://dali.nwbrower.top/Article/details/gtbzwbftcf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gtuofsxref.html

合计                                  2106 条
来源：http://dali.tianlin.xyz/Article/details/gtuzbqycxd.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gtrtiylefb.html

使用提醒
来源：http://dali.fengsongda.top/Article/details/gtbvcrnqcp.html

--------------------------------------------------------------------------------
来源：http://dali.yj202588.top/Article/details/gttuuefkfm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cqqwz.cn/Article/details/gtjjeadtrl.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yueranfly.top/Article/details/gtjnfquoog.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.haohaochexian.top/Article/details/gthjmeztqg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.tianlin.xyz/Article/details/gtuejjchre.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hongshengwenyu.top/Article/details/gtoocumypl.html

—— 文件结束 ——
来源：http://dali.hywenlv.cn/Article/details/gttacdfeef.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtqngxmzdy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.nanxinkj.top/Article/details/gtwonlxrpl.html

Common Programming Examples Cheat Book
来源：http://dali.wangshuangyany.cn/Article/details/gtnngkiecs.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtuvxqvezh.html

【收录内容】
来源：http://dali.yongpay.top/Article/details/gtfaopqszm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.svipenyu.cn/Article/details/gttbmmmhtd.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jqgfzy.top/Article/details/gtanrlazcc.html

SQL · Bash · C · C++
来源：http://dali.fengsongda.top/Article/details/gtxcrocrpq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ehwqpu.com/Article/details/gtdhvasbtf.html

【使用说明】
来源：http://dali.hfpthk.cn/Article/details/gtnnyvumsl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yonumen.top/Article/details/gtyiqejfwm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hywenlv.cn/Article/details/gtpzgvihns.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.chenlongwang.top/Article/details/gtdbkzvwek.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.bjfxy.top/Article/details/gtcsmjvsno.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.fengsongda.top/Article/details/gthcwfcjfn.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.sxryk.cn/Article/details/gtllgzaqmi.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.daxiang520.top/Article/details/gtbywwxska.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.ivvv.top/Article/details/gtisoslfyr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhiwuduotai.top/Article/details/gtnijhnyqf.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zycfv.cn/Article/details/gtdqgslboz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jyoumei.cn/Article/details/gtwduwyqjn.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jqgufenzy.top/Article/details/gtousoctfu.html

【文件统计】
来源：http://dali.9152youxi.cn/Article/details/gtxehzpwhi.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.sweek.top/Article/details/gtbctymqso.html

--------------------------------------------------------------------------------
来源：http://dali.xuanzx.com/Article/details/gttvqlegxh.html

目  录
来源：http://dali.shuidangran.top/Article/details/gttlutrayo.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtreosxrgj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gtfywnyopx.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yuxming.cn/Article/details/gtefbrpvgr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yuxming.cn/Article/details/gtqqkamwbk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hywenlv.cn/Article/details/gtoodtpjjj.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.meibo888.top/Article/details/gtbuhtsaht.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.bjfxy.top/Article/details/gtuuotrnve.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hnxiangtu.top/Article/details/gtsiykunfq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.tianlin.xyz/Article/details/gtfvbcroqf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.svipenyu.cn/Article/details/gtcofzrdcl.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.quarkkingdee.top/Article/details/gtiabtwhef.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.mhx1999.top/Article/details/gtgfyegkxv.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yj20258888.top/Article/details/gtkrieifas.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gtnalywtst.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhixingplan.top/Article/details/gtfbxshnaw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.dianchejie.cn/Article/details/gtwfqcpctt.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zycfv.cn/Article/details/gtjfwuvsur.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhengqikj.top/Article/details/gtmucetldl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.dashuyun.cn/Article/details/gtsepkcath.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.chenzaomai.com/Article/details/gtykfllmpp.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.andypj.xyz/Article/details/gtafbmywsy.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtcmxicqgy.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtkihuisoq.html

A. 基础语法与类型
来源：http://dali.jinghuilouyu.cn/Article/details/gteachugzl.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmzocqsu.html

[A01] Hello World
来源：http://dali.9152youxi.cn/Article/details/gtnrhnppam.html

Py:   print("Hello, World!")
来源：http://dali.redwolf501.top/Article/details/gtzrhvycin.html

PHP:  echo "Hello, World!";
来源：http://dali.yvedp.cn/Article/details/gtcsmgmuma.html

JS:   console.log("Hello, World!");
来源：http://dali.hammf.cn/Article/details/gtughtxdes.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cdnleiting.top/Article/details/gtrapucthv.html

Java: System.out.println("Hello, World!");
来源：http://dali.fengsongda.top/Article/details/gtgggadrmh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yuxming.cn/Article/details/gtlhzjdytb.html

Ruby: puts "Hello, World!"
来源：http://dali.jinqigfzy.top/Article/details/gtbilfiubt.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.redwolf501.top/Article/details/gtnltiyohc.html

[A02] 变量声明与赋值
来源：http://dali.yonumen.top/Article/details/gtyiibdkkc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jianghu66.top/Article/details/gtmqkccsrb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yongpay.top/Article/details/gtapjfowwo.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xuetiantiany.cn/Article/details/gtrbarmzmy.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.nanxuanxn.top/Article/details/gtnafdqafw.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.dianchejie.cn/Article/details/gtormaplbi.html

Go:   name := "Alex"; age := 20
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmdfnimm.html

Ruby: name = "Alex"; age = 20
来源：http://dali.dashuyun.cn/Article/details/gthdicdcvv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.pycfn.com/Article/details/gtzuwozafm.html

[A03] 常量定义
来源：http://dali.tanke756.top/Article/details/gtspdmgwur.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.andypj.xyz/Article/details/gtamtqsdwa.html

PHP:  const PI = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gtthtkbtft.html

JS:   const PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtyhnhxbop.html

TS:   const PI: number = 3.14159;
来源：http://dali.sweek.top/Article/details/gtxigqmdho.html

Java: static final double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtpidccvir.html

Go:   const PI = 3.14159
来源：http://dali.daxiang520.top/Article/details/gtmdqghqcy.html

Ruby: PI = 3.14159
来源：http://dali.wangdashe.top/Article/details/gtxvxlxvgh.html

C#:   const double PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtjkzyogmc.html

[A04] 判断变量类型
来源：http://dali.nanxuanxn.top/Article/details/gtlkqfvekc.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.sufxvd.cn/Article/details/gtcyhauphm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shanyushiyangtech.top/Article/details/gthobukqul.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhongyouzk.top/Article/details/gtldqijecp.html

TS:   typeof x; x instanceof Date
来源：http://dali.yonumen.top/Article/details/gteplyacxm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.tanke756.top/Article/details/gteklscmuy.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhoulong.xyz/Article/details/gtlqkoiyud.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jqgufenzy.top/Article/details/gtpuruxwqo.html

C#:   x.GetType().Name; x is int
来源：http://dali.zycfv.cn/Article/details/gtqmybxpye.html

[A05] 整数除法与取模
来源：http://dali.yongpay.top/Article/details/gtodepcayt.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.pengpengdd.cyou/Article/details/gtyhyujeae.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gtrvljnhoa.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmiriobp.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.birdmap.top/Article/details/gtrqzhrnuq.html

Java: 7 / 2; 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gtbnjuiirm.html

Go:   7 / 2; 7 % 2
来源：http://dali.tian-w.cn/Article/details/gtowlxzssm.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gtclbwaezi.html

C#:   7 / 2; 7 % 2
来源：http://dali.316326.xyz/Article/details/gtmufiefxq.html

[A06] 字符串转数字
来源：http://dali.yuxming.cn/Article/details/gtevvpoiju.html

Py:   int("42"); float("3.14")
来源：http://dali.fengsongda.top/Article/details/gtyzvrqjjw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cheryme.top/Article/details/gtwyaphwro.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.mhx1999.top/Article/details/gtgbzngnxv.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yj20258888.top/Article/details/gtftwpzsfp.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.daxiang520.top/Article/details/gtiybnaiio.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jianghu66.top/Article/details/gtxebdshrg.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.iojbl.cn/Article/details/gttwynkiok.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.shuidangran.top/Article/details/gtlcecldea.html

[A07] 数字转字符串
来源：http://dali.zhongyouzk.top/Article/details/gtdtsgsbid.html

Py:   str(42)
来源：http://dali.gogol.net.cn/Article/details/gtafljjavi.html

PHP:  (string) 42; strval(42)
来源：http://dali.nanxuanxn.top/Article/details/gtaphyhflj.html

JS:   String(42); (42).toString()
来源：http://dali.gogol.net.cn/Article/details/gtnqvmzodk.html

TS:   String(42)
来源：http://dali.shuidangran.top/Article/details/gtzoojukrg.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jlsjyb.cn/Article/details/gtcmdhfncf.html

Go:   strconv.Itoa(42)
来源：http://dali.nwbrower.top/Article/details/gtnuczdywx.html

Ruby: 42.to_s
来源：http://dali.vqdsnc.cn/Article/details/gtwupbgcqn.html

C#:   42.ToString()
来源：http://dali.jiagoushi.top/Article/details/gtgoehnrpe.html

[A08] 取整与四舍五入
来源：http://dali.jinqigfzy.top/Article/details/gtcpackqnr.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.iojbl.cn/Article/details/gtuhffwdzr.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.tian-w.cn/Article/details/gthlaavbaz.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.sweek.top/Article/details/gtmfeqxinv.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.gaohongyu789.top/Article/details/gtktvticof.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhongyouzk.top/Article/details/gtlzkxbjch.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.daxiang520.top/Article/details/gtzjaonngh.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.ydzc1.top/Article/details/gtlvdqbhot.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ppjwa.cn/Article/details/gtrthjjcxf.html

[A09] 绝对值与最大最小值
来源：http://dali.dashuyun.cn/Article/details/gtrhcicinh.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gttxeothkp.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gtylubbfvj.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtiptykxuo.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gtlstsbbvd.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yonumen.top/Article/details/gtylrxwfbv.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gtppryrzon.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.cdnleiting.top/Article/details/gtmedgwock.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gtsjnxvcix.html

[A10] 生成随机数
来源：http://dali.c1oappe.top/Article/details/gtjyohastw.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jinqigfzy.top/Article/details/gtjrgkqkmf.html

PHP:  random_int(1, 100);
来源：http://dali.svipenyu.cn/Article/details/gtsulscejd.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hywenlv.cn/Article/details/gtumxscxoq.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.316326.xyz/Article/details/gtfvkhgkup.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jqgufenzy.top/Article/details/gtuirxlowy.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.fengsongda.top/Article/details/gtgpkqemdy.html

Ruby: rand(1..100)
来源：http://dali.nanxuanxn.top/Article/details/gthcuxwknh.html

C#:   new Random().Next(1, 101)
来源：http://dali.daxiang520.top/Article/details/gtbytfupgr.html

[A11] 条件表达式（三元）
来源：http://dali.hysaishi.cn/Article/details/gtjhtdhvhb.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.nanxuanxn.top/Article/details/gtysgweamm.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.pengpengdd.cyou/Article/details/gtzhhaqscu.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.aizwys.cn/Article/details/gtffivmgew.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.iojbl.cn/Article/details/gtxboatefl.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yonumen.top/Article/details/gtpxwfhzxg.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.sxryk.cn/Article/details/gtniaokicx.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjflbrmd.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yueranfly.top/Article/details/gtrxemagvn.html

[A12] 字符串插值 / 格式化
来源：http://dali.mhx1999.top/Article/details/gtlywcygoa.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jyoumei.cn/Article/details/gtbbagawre.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.cheryme.top/Article/details/gtmquikmiu.html

JS:   `Hello, ${name}!`
来源：http://dali.cheryme.top/Article/details/gtkrixdjms.html

TS:   `Hello, ${name}!`
来源：http://dali.xuetiantiany.cn/Article/details/gtrbfbyxhy.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.cucudq.cn/Article/details/gttqqoyabv.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdncvcgr.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzflnjmqw.html

C#:   $"Hello, {name}!"
来源：http://dali.c1oappe.top/Article/details/gtchcvbhfg.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhiwuduotai.top/Article/details/gtklzyhomp.html

Py:   "第一行\n第二行"
来源：http://dali.jqgufenzy.top/Article/details/gtmowfjelz.html

PHP:  "第一行\n第二行"
来源：http://dali.cashguo.top/Article/details/gtfhgxjifh.html

JS:   "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gtxfgssydr.html

TS:   "第一行\n第二行"
来源：http://dali.zhoulong.xyz/Article/details/gtwbzsdyiw.html

Java: "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gtvnwvijua.html

Go:   "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gtsucbayam.html

Ruby: "第一行\n第二行"
来源：http://dali.birdmap.top/Article/details/gtwlrqkixc.html

C#:   "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gtjoasykcu.html

[A14] 注释写法
来源：http://dali.mhx1999.top/Article/details/gteddvuqet.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.daria6918.cn/Article/details/gtnlabqitq.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlolqohtj.html

JS:   // 单行；/* 多行 */
来源：http://dali.jqgfzy.top/Article/details/gthcdimrsu.html

TS:   // 单行；/* 多行 */
来源：http://dali.0kj1m.cn/Article/details/gtoxtmxicy.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.shzxlz.cn/Article/details/gtcqgnyshz.html

Go:   // 单行；/* 多行 */
来源：http://dali.yanxiufei.cn/Article/details/gtbvfbnein.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gtwvqskrhw.html

C#:   // 单行；/* 多行 */
来源：http://dali.mhx1999.top/Article/details/gtwnbvadar.html

[A15] 空值判断与默认值
来源：http://dali.hongshengwenyu.top/Article/details/gtueqmecbp.html

Py:   value = data or "默认值"
来源：http://dali.quarkkingdee.top/Article/details/gtffodtris.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.gogol.net.cn/Article/details/gtxosvpxdp.html

JS:   const value = data ?? "默认值";
来源：http://dali.jinqigufen.top/Article/details/gtdwdtbttj.html

TS:   const value = data ?? "默认值";
来源：http://dali.kuanghao11.cn/Article/details/gtrjhbvhsp.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.guannengcc.top/Article/details/gttseahnac.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.sweek.top/Article/details/gtcacfvwqz.html

Ruby: value = data || "默认值"
来源：http://dali.jiagoushi.top/Article/details/gtonhbyozz.html

C#:   var value = data ?? "默认值";
来源：http://dali.shzxlz.cn/Article/details/gtjvrvnbbr.html

[A16] 真假值判断规则
来源：http://dali.zdqjudy.top/Article/details/gtkffrxmdt.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.daxiang520.top/Article/details/gtlsnehzuc.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrnoqicp.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.aizwys.cn/Article/details/gtlwizfnoa.html

TS:   if (!x) {}
来源：http://dali.9152youxi.cn/Article/details/gtscjddnsz.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.hfpthk.cn/Article/details/gtvqvcnplw.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhiwuduotai.top/Article/details/gtyagewwts.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.redwolf501.top/Article/details/gtafabxyov.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jyoumei.cn/Article/details/gtrsjeohhe.html

[A17] 位运算
来源：http://dali.yj202588.top/Article/details/gtnzzbwcnu.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shangyingyoupin.top/Article/details/gtzoaaemly.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yonumen.top/Article/details/gtfvrqxqsy.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.snrcjt.cn/Article/details/gtirekssbm.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.c1oappe.top/Article/details/gtyncajcxe.html


<!-- 参考信息 -->