代发 wailian999

[U101] JS：classList 操作
来源：http://dali.zhoulong.xyz/Article/details/gtkhdjzozk.html

el.classList.toggle("active")
来源：http://dali.guowangkeji.top/Article/details/gtjvvlrfmx.html

[U102] JS：本地存储
来源：http://dali.kuanghao11.cn/Article/details/gtjzzixwti.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.aizwys.cn/Article/details/gtvxzypwrr.html

[U103] JS：定时器
来源：http://dali.jianghu66.top/Article/details/gtpoymidfz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.wangdashe.top/Article/details/gtappjpxti.html

[U104] JS：防抖
来源：http://dali.yongpay.top/Article/details/gtzunpmqcz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gtfbqalvkq.html

[U105] JS：节流
来源：http://dali.yvedp.cn/Article/details/gtehwxcned.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tianlin.xyz/Article/details/gtxnmzknsr.html

[U106] JS：日期格式化
来源：http://dali.tianlin.xyz/Article/details/gtqrwaoxwc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ppjwa.cn/Article/details/gtpzxlgzoc.html

[U107] JS：数字千分位
来源：http://dali.hnxiangtu.top/Article/details/gtambecfdx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gtrdyupjjy.html

[U108] JS：随机整数
来源：http://dali.nwbrower.top/Article/details/gtkqyeskhj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.fengsongda.top/Article/details/gtlfyplurb.html

[U109] JS：数组分组
来源：http://dali.yj202588.top/Article/details/gtqhskcchb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.0kj1m.cn/Article/details/gtuxzlbead.html

[U110] JS：数组分块
来源：http://dali.316326.xyz/Article/details/gtbnecfnnd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ehwqpu.com/Article/details/gtdzhjpzmk.html

[U111] JS：对象转 Map
来源：http://dali.316326.xyz/Article/details/gtrnukekiq.html

new Map(Object.entries(obj))
来源：http://dali.xuanzx.com/Article/details/gttpkmjngf.html

[U112] JS：字符串补位
来源：http://dali.zhongyouzk.top/Article/details/gtkbluiqzk.html

"7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuthobrqb.html

[U113] JS：正则替换全部
来源：http://dali.quarkkingdee.top/Article/details/gtkzvvnsfs.html

s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtjooqjkdi.html

[U114] JS：JSON 深比较
来源：http://dali.pengpengdd.cyou/Article/details/gtxzfvhpeu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ppjwa.cn/Article/details/gttaagwqco.html

[U115] JS：生成 UUID
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbtuuctx.html

crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtvfwdmuzn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.dashuyun.cn/Article/details/gtssmnrdra.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhixingplan.top/Article/details/gtulgdfoyi.html

[U117] JS：单元测试
来源：http://dali.zhongyouzk.top/Article/details/gthasttwji.html

npm i -D vitest;  npx vitest
来源：http://dali.cqqwz.cn/Article/details/gtkvwzeuog.html

[U118] JS：开发服务器
来源：http://dali.sysykeji.top/Article/details/gtzprcypxo.html

npm i -D vite;  npx vite
来源：http://dali.0kj1m.cn/Article/details/gtdkiccekx.html

[U119] JS：生产构建
来源：http://dali.sufxvd.cn/Article/details/gtobxtrorv.html

npx vite build
来源：http://dali.zhongyouzk.top/Article/details/gtajuensli.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cqqwz.cn/Article/details/gtnjrsiedk.html

import.meta.env.VITE_API_URL
来源：http://dali.jinghuilouyu.cn/Article/details/gtkcdzobeo.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsiuyahkp.html

统计汇总
来源：http://dali.yuxming.cn/Article/details/gtsgvarqkv.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtqaraqrxr.html

按语言统计（条）：
来源：http://dali.sufxvd.cn/Article/details/gtusmfggal.html

Python ......... 252
来源：http://dali.cucudq.cn/Article/details/gtdcfjgniq.html

PHP ............ 252
来源：http://dali.zycfv.cn/Article/details/gtlgerlmgb.html

JavaScript ..... 252
来源：http://dali.hywenlv.cn/Article/details/gtkeiiugqk.html

TypeScript ..... 212
来源：http://dali.gzhubu.top/Article/details/gtakmweyqu.html

Java ........... 212
来源：http://dali.smart0.xyz/Article/details/gtlnxccymy.html

Go ............. 212
来源：http://dali.ybcxt.top/Article/details/gtdiykliju.html

Ruby ........... 212
来源：http://dali.meibo888.top/Article/details/gtcfffcbkr.html

C# ............. 212
来源：http://dali.hnqzz.top/Article/details/gtpskulaub.html

C .............. 30
来源：http://dali.cashguo.top/Article/details/gtegcsqvzh.html

C++ ............ 30
来源：http://dali.zhiwuduotai.top/Article/details/gtxdfykegx.html

SQL ............ 90
来源：http://dali.wangshuangyany.cn/Article/details/gtoczeccrq.html

Bash ........... 80
来源：http://dali.cheryme.top/Article/details/gtizimgikx.html

Kotlin ......... 15
来源：http://dali.wangshuangyany.cn/Article/details/gtnhfbupjs.html

Swift .......... 15
来源：http://dali.havefunace.top/Article/details/gtqputkysm.html

Lua ............ 10
来源：http://dali.daria6918.cn/Article/details/gtpvtpzltp.html

Perl ........... 10
来源：http://dali.hywenlv.cn/Article/details/gtdjvvwtul.html

Scala .......... 10
来源：http://dali.cdnleiting.top/Article/details/gtsmwggpxd.html

------------------------------------
来源：http://dali.aizwys.cn/Article/details/gtpktitngd.html

合计 ........... 2106 条
来源：http://dali.nwbrower.top/Article/details/gtawrcoohe.html

按章节统计：
来源：http://dali.zhengqikj.top/Article/details/gtgdymtkvk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.kuanghao11.cn/Article/details/gtswsudoei.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhongyouzk.top/Article/details/gtppkkwqll.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.tian-w.cn/Article/details/gtukqlmrzn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.wangshuangyany.cn/Article/details/gteiuwbegy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.pengpengdd.cyou/Article/details/gtcvzchrub.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.9152youxi.cn/Article/details/gtsieabtoj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zycfv.cn/Article/details/gtzaefwaey.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.quarkkingdee.top/Article/details/gtfgaxwzfe.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gtbmytpyft.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhongyouzk.top/Article/details/gtswfuqayj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gtiagsbius.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gtuttwxhau.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gtxrfznrie.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xuanzx.com/Article/details/gtkqbsujuu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.daxiang520.top/Article/details/gtslwrzwmo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gtwnlgjiwx.html

Q SQL 专题                              90
来源：http://dali.yj20258.top/Article/details/gttmvkkupn.html

R Bash 专题                             80
来源：http://dali.fengsongda.top/Article/details/gttjkrnikm.html

S C / C++ 专题                          60
来源：http://dali.sweek.top/Article/details/gtlrhyvuhh.html

T 其他语言补充                          60
来源：http://dali.yongpay.top/Article/details/gtwlyuvtcm.html

U 高频实用片段                         120
来源：http://dali.zhiwuduotai.top/Article/details/gtbxygmhfv.html

------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gtiulmjfrx.html

合计                                  2106 条
来源：http://dali.gotoacloud.top/Article/details/gtregzejuy.html

--------------------------------------------------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gtlchqmhvw.html

使用提醒
来源：http://dali.mhx1999.top/Article/details/gtfdsgfijr.html

--------------------------------------------------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gtyimivchr.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hnqzz.top/Article/details/gtlyhvwkxy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.feifeiyinyue.top/Article/details/gtrhqiftlu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jianghu66.top/Article/details/gtrimpscvj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hywenlv.cn/Article/details/gtajwlnejf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.iojbl.cn/Article/details/gtycjkgvxp.html

—— 文件结束 ——
来源：http://dali.fengsongda.top/Article/details/gtlmxrkeac.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtcpihosop.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jqgfzy.top/Article/details/gtljqrxtcy.html

Common Programming Examples Cheat Book
来源：http://dali.wangshuangyany.cn/Article/details/gtjzxfbfav.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtchiiukkt.html

【收录内容】
来源：http://dali.c1oappe.top/Article/details/gtlqzobtre.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.fengsongda.top/Article/details/gtdodpxcph.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.chenjidiqi.icu/Article/details/gtgkeiwhwx.html

SQL · Bash · C · C++
来源：http://dali.zhixingplan.top/Article/details/gtvijvsbmz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylhkoafp.html

【使用说明】
来源：http://dali.ybcxt.top/Article/details/gtuetquxge.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jyoumei.cn/Article/details/gthqfegvvo.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zycfv.cn/Article/details/gtdtsuqhgt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.chenjidiqi.icu/Article/details/gtoqtkzfba.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.andypj.xyz/Article/details/gtaqqvbinw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hammf.cn/Article/details/gtpdudcead.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xuetiantiany.cn/Article/details/gtlhcytqtk.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.ppjwa.cn/Article/details/gtgpqdwlpn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.tanke756.top/Article/details/gtweewklzg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.wangdashe.top/Article/details/gthscrnmfm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ehwqpu.com/Article/details/gtqpnbgcxy.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yanxiufei.cn/Article/details/gthpfoepza.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.sxryk.cn/Article/details/gtyayznlxe.html

【文件统计】
来源：http://dali.tianlin.xyz/Article/details/gtioxrivoo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gaohongyu789.top/Article/details/gtaxhbysmk.html

--------------------------------------------------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gtxrntzwzg.html

目  录
来源：http://dali.xylfe.cn/Article/details/gtecjfzded.html

--------------------------------------------------------------------------------
来源：http://dali.chenzaomai.com/Article/details/gtgqnnxjwv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.tian-w.cn/Article/details/gtxkrqzazj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.chenzaomai.com/Article/details/gtsoljrowr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hysaishi.cn/Article/details/gtlnamrxqv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.cucudq.cn/Article/details/gtklguwvqm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.sysykeji.top/Article/details/gttghskdnn.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.sufxvd.cn/Article/details/gtqgibhbdg.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ppjwa.cn/Article/details/gtuflvotff.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhengqikj.top/Article/details/gtoacobyhf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hywenlv.cn/Article/details/gtvoxbibbg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.snrcjt.cn/Article/details/gtzexmvynw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.gotoacloud.top/Article/details/gtttnfckak.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.shuidangran.top/Article/details/gtonyrfoob.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gtzrhllnkt.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefatqqkz.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.redwolf501.top/Article/details/gtmkqcidmu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gtbcwpulvk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ehwqpu.com/Article/details/gtkzcbgags.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yanxiufei.cn/Article/details/gtggwakncl.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yj20258888.top/Article/details/gtygzzqddd.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hfpthk.cn/Article/details/gtnwoiwwqe.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtteunhyta.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtvptuauik.html

A. 基础语法与类型
来源：http://dali.yongpay.top/Article/details/gtdushdzfl.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtddbsrzju.html

[A01] Hello World
来源：http://dali.aizwys.cn/Article/details/gtijadyjib.html

Py:   print("Hello, World!")
来源：http://dali.xuanzx.com/Article/details/gthajyppxz.html

PHP:  echo "Hello, World!";
来源：http://dali.quarkkingdee.top/Article/details/gtelcyyzsc.html

JS:   console.log("Hello, World!");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydyufqrk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.snrcjt.cn/Article/details/gtrynkiwos.html

Java: System.out.println("Hello, World!");
来源：http://dali.jinqigfzy.top/Article/details/gtxxkkwvdk.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.tian-w.cn/Article/details/gtuixvtnwz.html

Ruby: puts "Hello, World!"
来源：http://dali.hfpthk.cn/Article/details/gtozgkbfqc.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hnxiangtu.top/Article/details/gtmkfarljb.html

[A02] 变量声明与赋值
来源：http://dali.jinqigfzy.top/Article/details/gtpolmghil.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yongpay.top/Article/details/gtdhethmvu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.andypj.xyz/Article/details/gtdfwwbmub.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ybcxt.top/Article/details/gtqljaszbr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gogol.net.cn/Article/details/gtmpaasrpy.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jlsjyb.cn/Article/details/gtaulhohpw.html

Go:   name := "Alex"; age := 20
来源：http://dali.sysykeji.top/Article/details/gtxeuwhixz.html

Ruby: name = "Alex"; age = 20
来源：http://dali.andypj.xyz/Article/details/gtlpzohqhh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.tian-w.cn/Article/details/gtozcyzeoi.html

[A03] 常量定义
来源：http://dali.daxiang520.top/Article/details/gtthmwaprj.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.daxiang520.top/Article/details/gtnrkkrmkb.html

PHP:  const PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtifhogjwz.html

JS:   const PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gtjgepzhwh.html

TS:   const PI: number = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtktcfdzqa.html

Java: static final double PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gteaebjhvp.html

Go:   const PI = 3.14159
来源：http://dali.ivvv.top/Article/details/gtnnmkycit.html

Ruby: PI = 3.14159
来源：http://dali.yangfankeji.com/Article/details/gtuhunldwu.html

C#:   const double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtgtbbfuzf.html

[A04] 判断变量类型
来源：http://dali.hnqzz.top/Article/details/gtpicvuqam.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.0kj1m.cn/Article/details/gtubujxeui.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhongyouzk.top/Article/details/gtxbnasxfu.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.ybcxt.top/Article/details/gtprdqomma.html

TS:   typeof x; x instanceof Date
来源：http://dali.yangfankeji.com/Article/details/gtjtbnjmrc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.tianlin.xyz/Article/details/gtpwgztakd.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.9152youxi.cn/Article/details/gtogqkegxg.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.dashuyun.cn/Article/details/gtmwypbcrv.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaijknbqo.html

[A05] 整数除法与取模
来源：http://dali.chenjidiqi.icu/Article/details/gtjkccegrz.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.hysaishi.cn/Article/details/gtchygnwcl.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gtpzxtrwhd.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gtbswremsf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj20258888.top/Article/details/gtldgnoxck.html

Java: 7 / 2; 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gtpdhuktyp.html

Go:   7 / 2; 7 % 2
来源：http://dali.yj20258888.top/Article/details/gtsjpexlcx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hnqzz.top/Article/details/gtvgmxmjze.html

C#:   7 / 2; 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gthidlpeul.html

[A06] 字符串转数字
来源：http://dali.tian-w.cn/Article/details/gttzodmqqq.html

Py:   int("42"); float("3.14")
来源：http://dali.shangyingyoupin.top/Article/details/gtlmntskxp.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.snrcjt.cn/Article/details/gtbcchdonu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.quarkkingdee.top/Article/details/gtvfgiflaz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.pycfn.com/Article/details/gtkpsfvsng.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.vqdsnc.cn/Article/details/gtkqfzdvsn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yj20258.top/Article/details/gtjtiyyvkt.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yonumen.top/Article/details/gtnvvtjfke.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xylfe.cn/Article/details/gtfchweobb.html

[A07] 数字转字符串
来源：http://dali.shzxlz.cn/Article/details/gtuchbpeby.html

Py:   str(42)
来源：http://dali.cashguo.top/Article/details/gtthxanhhr.html

PHP:  (string) 42; strval(42)
来源：http://dali.ehwqpu.com/Article/details/gtrloyvthb.html

JS:   String(42); (42).toString()
来源：http://dali.vqdsnc.cn/Article/details/gtyjexooem.html

TS:   String(42)
来源：http://dali.iojbl.cn/Article/details/gttmzdxhji.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlyfckhuo.html

Go:   strconv.Itoa(42)
来源：http://dali.cucudq.cn/Article/details/gtbbmekzbg.html

Ruby: 42.to_s
来源：http://dali.jinqigufen.top/Article/details/gtwwddhlql.html

C#:   42.ToString()
来源：http://dali.zycfv.cn/Article/details/gtgoctfhed.html

[A08] 取整与四舍五入
来源：http://dali.yuanzhike.top/Article/details/gtrtyqkflj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.shangyingyoupin.top/Article/details/gtxfggaayt.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hnxiangtu.top/Article/details/gtndtmkkug.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.xuetiantiany.cn/Article/details/gtauptwpud.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.tian-w.cn/Article/details/gtwvyqpepw.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.sxryk.cn/Article/details/gtragfdlub.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.mhx1999.top/Article/details/gtbquxibor.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.nwbrower.top/Article/details/gthvfmrnms.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.sxryk.cn/Article/details/gtxvwczfhr.html

[A09] 绝对值与最大最小值
来源：http://dali.snrcjt.cn/Article/details/gtvbaguvcd.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zycfv.cn/Article/details/gtajoetafd.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtqcyhdxad.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtxhwazjiq.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.pycfn.com/Article/details/gtivqprfel.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gttjxfwhdf.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hongshengwenyu.top/Article/details/gtsntswppg.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.sufxvd.cn/Article/details/gthfshvuxm.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.birdmap.top/Article/details/gtunzlkxvq.html

[A10] 生成随机数
来源：http://dali.tianlin.xyz/Article/details/gthbjzsjit.html

Py:   import random; random.randint(1, 100)
来源：http://dali.pengpengdd.cyou/Article/details/gtllmragfo.html

PHP:  random_int(1, 100);
来源：http://dali.fzhhl.top/Article/details/gtwwslexmf.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.smart0.xyz/Article/details/gtdhixeowa.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yonumen.top/Article/details/gtzujjgksc.html

Java: new Random().nextInt(100) + 1
来源：http://dali.cashguo.top/Article/details/gtqqcqjalu.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.svipenyu.cn/Article/details/gtihaksxjq.html

Ruby: rand(1..100)
来源：http://dali.sweek.top/Article/details/gtjkzvplka.html

C#:   new Random().Next(1, 101)
来源：http://dali.yj20258.top/Article/details/gtggwvjgkc.html

[A11] 条件表达式（三元）
来源：http://dali.316326.xyz/Article/details/gtkdrjulnv.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.xuetiantiany.cn/Article/details/gtrwujbanz.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.jinqigufen.top/Article/details/gtepvhhghg.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.smart0.xyz/Article/details/gtlvozplio.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yongpay.top/Article/details/gtglzvgdxi.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gttxqfihrb.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yj20258.top/Article/details/gtckdrjbvl.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yuanzhike.top/Article/details/gtcpqitplu.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jqgufenzy.top/Article/details/gtvjbslbby.html

[A12] 字符串插值 / 格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehfxisbi.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytkwnfea.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.cashguo.top/Article/details/gtheqwygiw.html

JS:   `Hello, ${name}!`
来源：http://dali.yj20258.top/Article/details/gtbjgcrqoo.html

TS:   `Hello, ${name}!`
来源：http://dali.zhoulong.xyz/Article/details/gtqghnoker.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.wangshuangyany.cn/Article/details/gtzgsmldcs.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.316326.xyz/Article/details/gteskaarkg.html

Ruby: "Hello, #{name}!"
来源：http://dali.ivvv.top/Article/details/gtddywwuyb.html

C#:   $"Hello, {name}!"
来源：http://dali.birdmap.top/Article/details/gtbccplctx.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.nanxinkj.top/Article/details/gtcxlhjvnu.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gtluadhdio.html

PHP:  "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gtozgdfxhg.html

JS:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gtenkirnjj.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gtybjsaxfn.html

Java: "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gtdgufonkz.html

Go:   "第一行\n第二行"
来源：http://dali.dianchejie.cn/Article/details/gtsvufkkua.html

Ruby: "第一行\n第二行"
来源：http://dali.316326.xyz/Article/details/gthddfruni.html

C#:   "第一行\n第二行"
来源：http://dali.zhiwuduotai.top/Article/details/gteriiagvm.html

[A14] 注释写法
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbqtwshg.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.sweek.top/Article/details/gtcdgdiyzd.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.iojbl.cn/Article/details/gtndlblgqu.html

JS:   // 单行；/* 多行 */
来源：http://dali.jinqigufen.top/Article/details/gtowydrtzo.html

TS:   // 单行；/* 多行 */
来源：http://dali.haohaochexian.top/Article/details/gtthcyowzz.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.shangyingyoupin.top/Article/details/gtoihtbpjz.html

Go:   // 单行；/* 多行 */
来源：http://dali.dashuyun.cn/Article/details/gtdedxdrim.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.daria6918.cn/Article/details/gttpbjfutw.html

C#:   // 单行；/* 多行 */
来源：http://dali.yanxiufei.cn/Article/details/gtjexdqkuo.html

[A15] 空值判断与默认值
来源：http://dali.zhiwuduotai.top/Article/details/gtapevlzqa.html

Py:   value = data or "默认值"
来源：http://dali.aizwys.cn/Article/details/gtzczpbafs.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.fengsongda.top/Article/details/gtxsgfrwoz.html

JS:   const value = data ?? "默认值";
来源：http://dali.jqgfzy.top/Article/details/gtuvxtsgum.html

TS:   const value = data ?? "默认值";
来源：http://dali.aibaodan.cn/Article/details/gtwoasezrg.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jqgfzy.top/Article/details/gtusjlkckr.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yuanzhike.top/Article/details/gtesllkzqr.html

Ruby: value = data || "默认值"
来源：http://dali.nanxinkj.top/Article/details/gtsqrksstt.html

C#:   var value = data ?? "默认值";
来源：http://dali.cqqwz.cn/Article/details/gtmpqahljk.html

[A16] 真假值判断规则
来源：http://dali.nanxuanxn.top/Article/details/gtyclmsdtc.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.nanxinkj.top/Article/details/gtgufidfdi.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhengqikj.top/Article/details/gtnqjaqvsx.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.nwbrower.top/Article/details/gtznrfptaf.html

TS:   if (!x) {}
来源：http://dali.havefunace.top/Article/details/gtxnqgjfwd.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhixingplan.top/Article/details/gtvhlllerr.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.shangyingyoupin.top/Article/details/gtpqniigrc.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvhlnatn.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.guowangkeji.top/Article/details/gtjemdaucc.html

[A17] 位运算
来源：http://dali.tian-w.cn/Article/details/gtpxtvmrjt.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gtrskahjrl.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.vqdsnc.cn/Article/details/gtoiyfiwwo.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.kuanghao11.cn/Article/details/gtcdoopqqa.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.gotoacloud.top/Article/details/gtvkwjmqii.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gtofibhivf.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gtkfhcjrby.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgufenzy.top/Article/details/gtqymtromm.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hywenlv.cn/Article/details/gtnfuniwgx.html


<!-- 参考信息 -->