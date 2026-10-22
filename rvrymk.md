代发 wailian999

[U97] JS：并发请求
来源：http://dali.cdnleiting.top/Article/details/gt2iwzhifbq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gt2mtnnhlrj.html

[U98] JS：fetch 带 JSON
来源：http://dali.tian-w.cn/Article/details/gt2pqmrczda.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bqtoanvv.html

[U99] JS：事件监听
来源：http://dali.nanxinkj.top/Article/details/gt2nywaemkf.html

el.addEventListener("click", e => {})
来源：http://dali.sxryk.cn/Article/details/gt2poiwsewl.html

[U100] JS：DOM 查询
来源：http://dali.hnqzz.top/Article/details/gt2ybtujrar.html

document.querySelector(".item")
来源：http://dali.xziqi.cn/Article/details/gt2nmxxksus.html

[U101] JS：classList 操作
来源：http://dali.svipenyu.cn/Article/details/gt2rlakcfpp.html

el.classList.toggle("active")
来源：http://dali.aibaodan.cn/Article/details/gt2jtklzota.html

[U102] JS：本地存储
来源：http://dali.hysaishi.cn/Article/details/gt2nbfgxowr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yonumen.top/Article/details/gt2vpabopfm.html

[U103] JS：定时器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rgvpmsya.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yj20258.top/Article/details/gt2swlzhrub.html

[U104] JS：防抖
来源：http://dali.mhx1999.top/Article/details/gt2sffhjukc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gt2ucwuziks.html

[U105] JS：节流
来源：http://dali.jinqigufen.top/Article/details/gt2abebmxyb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yuxming.cn/Article/details/gt2ukxpkdub.html

[U106] JS：日期格式化
来源：http://dali.mhx1999.top/Article/details/gt2ewddqzlg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinqigufen.top/Article/details/gt2hwmpussm.html

[U107] JS：数字千分位
来源：http://dali.jianghu66.top/Article/details/gt2ojriavnb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fedwpkym.html

[U108] JS：随机整数
来源：http://dali.316326.xyz/Article/details/gt2pdkocnce.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.chenlongwang.top/Article/details/gt2avfpyxpf.html

[U109] JS：数组分组
来源：http://dali.meibo888.top/Article/details/gt2hsnpsuev.html

Object.groupBy(arr, x => x.type)
来源：http://dali.birdmap.top/Article/details/gt2lkzvehri.html

[U110] JS：数组分块
来源：http://dali.shangyingyoupin.top/Article/details/gt2zmxecphp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cdnleiting.top/Article/details/gt2gzhmmoif.html

[U111] JS：对象转 Map
来源：http://dali.jyoumei.cn/Article/details/gt2yiiwxasp.html

new Map(Object.entries(obj))
来源：http://dali.sweek.top/Article/details/gt2wlahnbru.html

[U112] JS：字符串补位
来源：http://dali.zhixingplan.top/Article/details/gt2qhwqfgjp.html

"7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gt2nqhyrvlu.html

[U113] JS：正则替换全部
来源：http://dali.ivvv.top/Article/details/gt2vbrkklds.html

s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gt2nyazfzjs.html

[U114] JS：JSON 深比较
来源：http://dali.guowangkeji.top/Article/details/gt2duhnmtep.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2idolbdvy.html

[U115] JS：生成 UUID
来源：http://dali.chenzaomai.com/Article/details/gt2lgezaqmt.html

crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xleagmkb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cucudq.cn/Article/details/gt2veayqqdw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2klirakqm.html

[U117] JS：单元测试
来源：http://dali.mhx1999.top/Article/details/gt2usvgwqmu.html

npm i -D vitest;  npx vitest
来源：http://dali.haohaochexian.top/Article/details/gt2qonxmpzb.html

[U118] JS：开发服务器
来源：http://dali.316326.xyz/Article/details/gt2yddhhbkd.html

npm i -D vite;  npx vite
来源：http://dali.cucudq.cn/Article/details/gt2gynzxqnm.html

[U119] JS：生产构建
来源：http://dali.guowangkeji.top/Article/details/gt2tkdrvzjb.html

npx vite build
来源：http://dali.daxiang520.top/Article/details/gt2abenqzud.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.dashuyun.cn/Article/details/gt2zshbkvls.html

import.meta.env.VITE_API_URL
来源：http://dali.zdqjudy.top/Article/details/gt2lmffpczq.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2mecbxtlx.html

统计汇总
来源：http://dali.hywenlv.cn/Article/details/gt2exemfizb.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2ytvmqwwd.html

按语言统计（条）：
来源：http://dali.quarkkingdee.top/Article/details/gt2mlrxozwn.html

Python ......... 252
来源：http://dali.pengpengdd.cyou/Article/details/gt2gjpqmrmy.html

PHP ............ 252
来源：http://dali.cucudq.cn/Article/details/gt2zqafcmgu.html

JavaScript ..... 252
来源：http://dali.quarkkingdee.top/Article/details/gt2rruovwlo.html

TypeScript ..... 212
来源：http://dali.ehwqpu.com/Article/details/gt2hmbtgdey.html

Java ........... 212
来源：http://dali.hammf.cn/Article/details/gt2rnpddqkn.html

Go ............. 212
来源：http://dali.guannengcc.top/Article/details/gt2npnbrphs.html

Ruby ........... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2afsfxqvn.html

C# ............. 212
来源：http://dali.chenjidiqi.icu/Article/details/gt2ndouieqw.html

C .............. 30
来源：http://dali.smart0.xyz/Article/details/gt2feelmhgj.html

C++ ............ 30
来源：http://dali.yj202588.top/Article/details/gt2bzzuindt.html

SQL ............ 90
来源：http://dali.gaohongyu789.top/Article/details/gt2ddecohdf.html

Bash ........... 80
来源：http://dali.jlsjyb.cn/Article/details/gt2frwednmm.html

Kotlin ......... 15
来源：http://dali.yj20258.top/Article/details/gt2gshbhcem.html

Swift .......... 15
来源：http://dali.zycfv.cn/Article/details/gt2zublrhlb.html

Lua ............ 10
来源：http://dali.mhx1999.top/Article/details/gt2blpokpzu.html

Perl ........... 10
来源：http://dali.birdmap.top/Article/details/gt2oljelkdy.html

Scala .......... 10
来源：http://dali.ppjwa.cn/Article/details/gt2onshosee.html

------------------------------------
来源：http://dali.jianghu66.top/Article/details/gt2oamykcty.html

合计 ........... 2106 条
来源：http://dali.shuidangran.top/Article/details/gt2hxhkvuyh.html

按章节统计：
来源：http://dali.cheryme.top/Article/details/gt2cpmexoas.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sxryk.cn/Article/details/gt2vygshfjg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gt2spazpzgh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yuxming.cn/Article/details/gt2sfwefgts.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yvedp.cn/Article/details/gt2teqwftjc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jqgfzy.top/Article/details/gt2zclpzfhg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.9152youxi.cn/Article/details/gt2fdvgsioj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2imnktsob.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ppjwa.cn/Article/details/gt2pimooqmv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gt2mqwiuigt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.wangshuangyany.cn/Article/details/gt2jameyyxz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gt2dmizenxq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yj20258888.top/Article/details/gt2rsgkczer.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gt2emeigtqt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oqzqrsph.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cucudq.cn/Article/details/gt2dfsyarpo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gt2wwkmsuix.html

Q SQL 专题                              90
来源：http://dali.iojbl.cn/Article/details/gt2wsudpbba.html

R Bash 专题                             80
来源：http://dali.iojbl.cn/Article/details/gt2cagxzvbl.html

S C / C++ 专题                          60
来源：http://dali.tianlin.xyz/Article/details/gt2eqlgormz.html

T 其他语言补充                          60
来源：http://dali.ydzc1.top/Article/details/gt2qnnzcnvn.html

U 高频实用片段                         120
来源：http://dali.havefunace.top/Article/details/gt2zhdjzpdl.html

------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gt2psozupoh.html

合计                                  2106 条
来源：http://dali.sxryk.cn/Article/details/gt2rqnwkejk.html

--------------------------------------------------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gt2eyemoxau.html

使用提醒
来源：http://dali.cdnleiting.top/Article/details/gt2awbcwjvm.html

--------------------------------------------------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gt2wldtelgm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.vqdsnc.cn/Article/details/gt2lnkcsank.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.havefunace.top/Article/details/gt2pqmjkbfp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yj20258888.top/Article/details/gt2tyspabhy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.aizwys.cn/Article/details/gt2mfbxeffd.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.sysykeji.top/Article/details/gt2ehjkefek.html

—— 文件结束 ——
来源：http://dali.cdnleiting.top/Article/details/gt2vwulyfjl.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2rafovtxd.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kyncnnrg.html

Common Programming Examples Cheat Book
来源：http://dali.jqgfzy.top/Article/details/gt2uqaqwjvh.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2xlkzaatv.html

【收录内容】
来源：http://dali.yangfankeji.com/Article/details/gt2omeswvje.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cdnleiting.top/Article/details/gt2hopfokky.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jianghu66.top/Article/details/gt2nihlgpeu.html

SQL · Bash · C · C++
来源：http://dali.svipenyu.cn/Article/details/gt2hodmyuso.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.fzhhl.top/Article/details/gt2ucbogten.html

【使用说明】
来源：http://dali.yj20258888.top/Article/details/gt2goftdvfz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zycfv.cn/Article/details/gt2thezajou.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xinyue.icu/Article/details/gt2elpwcaqg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yongpay.top/Article/details/gt2assrucix.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yj20258.top/Article/details/gt2gnotpebr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.vqdsnc.cn/Article/details/gt2ijdclfqz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hywenlv.cn/Article/details/gt2hzlxsdqg.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.xylfe.cn/Article/details/gt2cqmegjvi.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ttcnrrnk.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xinyue.icu/Article/details/gt2mbhjnwur.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.tianlin.xyz/Article/details/gt2awprdgzv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.cqqwz.cn/Article/details/gt2pvdqtwol.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.ybcxt.top/Article/details/gt2vfqvtgmc.html

【文件统计】
来源：http://dali.nanxuanxn.top/Article/details/gt2bejsudad.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yueranfly.top/Article/details/gt2topqdxsn.html

--------------------------------------------------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gt2rgirgpyu.html

目  录
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wpsjowrm.html

--------------------------------------------------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gt2agacyadx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.daxiang520.top/Article/details/gt2seyqfxzw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hywenlv.cn/Article/details/gt2jgkggtuw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xuanzx.com/Article/details/gt2yazbzmme.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.chenlongwang.top/Article/details/gt2yoaoglnj.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ybxdukrt.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2urfnjtuj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.0kj1m.cn/Article/details/gt2mnasfdte.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2uqwatkvm.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gt2lgxbpzmq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ngqvunet.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gt2qljolglm.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2incndxqh.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2gvsqzhkv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shzxlz.cn/Article/details/gt2gzqutsxi.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hywenlv.cn/Article/details/gt2lmmewiao.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.meibo888.top/Article/details/gt2sqntwvha.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xinyue.icu/Article/details/gt2oyyviwmw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yonumen.top/Article/details/gt2uoupvkrp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.fengsongda.top/Article/details/gt2swvxiquz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.birdmap.top/Article/details/gt2apiiwxzl.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.guowangkeji.top/Article/details/gt2ktmiqeiw.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2fhkwltik.html

A. 基础语法与类型
来源：http://dali.tianlin.xyz/Article/details/gt2isfkcpge.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2gvzsmqaz.html

[A01] Hello World
来源：http://dali.gaohongyu789.top/Article/details/gt2spjyhssg.html

Py:   print("Hello, World!")
来源：http://dali.nanxinkj.top/Article/details/gt2tfqueikf.html

PHP:  echo "Hello, World!";
来源：http://dali.andypj.xyz/Article/details/gt2qthdluki.html

JS:   console.log("Hello, World!");
来源：http://dali.jqgufenzy.top/Article/details/gt2pqjrtgqv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.haohaochexian.top/Article/details/gt2uthxvceu.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhixingplan.top/Article/details/gt2qbhjddnb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.haohaochexian.top/Article/details/gt2uvaycmjc.html

Ruby: puts "Hello, World!"
来源：http://dali.jinqigfzy.top/Article/details/gt2faiztasg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hnxiangtu.top/Article/details/gt2aamyqatx.html

[A02] 变量声明与赋值
来源：http://dali.svipenyu.cn/Article/details/gt2bdgysqfe.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shuidangran.top/Article/details/gt2wtveahpn.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.snrcjt.cn/Article/details/gt2heojdilo.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sznqcevp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.nwbrower.top/Article/details/gt2fwfjoxak.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yangfankeji.com/Article/details/gt2guhbrvca.html

Go:   name := "Alex"; age := 20
来源：http://dali.yj20258888.top/Article/details/gt2yshbydcp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.ivvv.top/Article/details/gt2jhhiseka.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.kuanghao11.cn/Article/details/gt2mcarenoh.html

[A03] 常量定义
来源：http://dali.yj20258.top/Article/details/gt2cvqxaquu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.birdmap.top/Article/details/gt2ckpkharf.html

PHP:  const PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gt2ydceyjkn.html

JS:   const PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gt2ssogkgmj.html

TS:   const PI: number = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vxffgwxf.html

Java: static final double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gt2wmgnuoyy.html

Go:   const PI = 3.14159
来源：http://dali.tanke756.top/Article/details/gt2otprjrrr.html

Ruby: PI = 3.14159
来源：http://dali.tianlin.xyz/Article/details/gt2ksgacqww.html

C#:   const double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gt2vppycdks.html

[A04] 判断变量类型
来源：http://dali.svipenyu.cn/Article/details/gt2vohxpsyk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.bjfxy.top/Article/details/gt2nwxxqyds.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cucudq.cn/Article/details/gt2zrzfssns.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.pengpengdd.cyou/Article/details/gt2xumuodya.html

TS:   typeof x; x instanceof Date
来源：http://dali.wangdashe.top/Article/details/gt2rzphyrii.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yihyvdst.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.ehwqpu.com/Article/details/gt2btqmpade.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.pycfn.com/Article/details/gt2mwsjkafe.html

C#:   x.GetType().Name; x is int
来源：http://dali.hfpthk.cn/Article/details/gt2xhdtymce.html

[A05] 整数除法与取模
来源：http://dali.haohaochexian.top/Article/details/gt2lozqaaoi.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jqgfzy.top/Article/details/gt2bhxexumq.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gt2xaebpuqu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gt2kvfzeune.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.dashuyun.cn/Article/details/gt2qrgzjucg.html

Java: 7 / 2; 7 % 2
来源：http://dali.yj202588.top/Article/details/gt2ddptvhrx.html

Go:   7 / 2; 7 % 2
来源：http://dali.ivvv.top/Article/details/gt2fnxwwmqq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.gzhubu.top/Article/details/gt2xvugxocb.html

C#:   7 / 2; 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gt2gkqzecjf.html

[A06] 字符串转数字
来源：http://dali.yvedp.cn/Article/details/gt2zprdysco.html

Py:   int("42"); float("3.14")
来源：http://dali.ppjwa.cn/Article/details/gt2itzcjblr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhixingplan.top/Article/details/gt2fgdecitm.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.wangdashe.top/Article/details/gt2qprcimqp.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.xuetiantiany.cn/Article/details/gt2fmyqgnud.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yj20258888.top/Article/details/gt2bjuvdnjn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2citjwike.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.xuanzx.com/Article/details/gt2xovagaxy.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yj202588.top/Article/details/gt2hzzyqofi.html

[A07] 数字转字符串
来源：http://dali.nwbrower.top/Article/details/gt2yyicsrrm.html

Py:   str(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lcarwhge.html

PHP:  (string) 42; strval(42)
来源：http://dali.gogol.net.cn/Article/details/gt2qyfzzmox.html

JS:   String(42); (42).toString()
来源：http://dali.zdqjudy.top/Article/details/gt2tiqttjpl.html

TS:   String(42)
来源：http://dali.cdnleiting.top/Article/details/gt2ykanmacn.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.birdmap.top/Article/details/gt2jmflsgpv.html

Go:   strconv.Itoa(42)
来源：http://dali.gaohongyu789.top/Article/details/gt2oihavmyx.html

Ruby: 42.to_s
来源：http://dali.fengsongda.top/Article/details/gt2mzihbvup.html

C#:   42.ToString()
来源：http://dali.xylfe.cn/Article/details/gt2cmvaygux.html

[A08] 取整与四舍五入
来源：http://dali.chenjidiqi.icu/Article/details/gt2udtojfcl.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.birdmap.top/Article/details/gt2ygvnjqmc.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhixingplan.top/Article/details/gt2vuyhkott.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.xziqi.cn/Article/details/gt2dzghvagj.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hfpthk.cn/Article/details/gt2uoywaqmw.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.cashguo.top/Article/details/gt2nfcmjftf.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jqgfzy.top/Article/details/gt2nwcygygk.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.ehwqpu.com/Article/details/gt2ixamyvhp.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yj20258.top/Article/details/gt2owqgscft.html

[A09] 绝对值与最大最小值
来源：http://dali.pycfn.com/Article/details/gt2lkcrjvsx.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ssezipgg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2kulvucvm.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.andypj.xyz/Article/details/gt2gxqfsobr.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2ybguqnko.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gt2bngdkcxg.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.cheryme.top/Article/details/gt2pvpcujap.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.hnqzz.top/Article/details/gt2eawkimjg.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gt2xzmzflpu.html

[A10] 生成随机数
来源：http://dali.ppjwa.cn/Article/details/gt2rslorlnq.html

Py:   import random; random.randint(1, 100)
来源：http://dali.tianlin.xyz/Article/details/gt2rfuxqwct.html

PHP:  random_int(1, 100);
来源：http://dali.tianlin.xyz/Article/details/gt2yvfhehrc.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhoulong.xyz/Article/details/gt2zytuuclr.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cucudq.cn/Article/details/gt2shgyfjnf.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yongpay.top/Article/details/gt2ornhjgwv.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jqgufenzy.top/Article/details/gt2oubbqdso.html

Ruby: rand(1..100)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dvklfbhi.html

C#:   new Random().Next(1, 101)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tuckkgjb.html

[A11] 条件表达式（三元）
来源：http://dali.ehwqpu.com/Article/details/gt2dpetwdtb.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2midtotnf.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.daria6918.cn/Article/details/gt2bvgqcuuz.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jiagoushi.top/Article/details/gt2wvaicavc.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.hnxiangtu.top/Article/details/gt2icayvgzt.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.chenlongwang.top/Article/details/gt2noreyjim.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yuanzhike.top/Article/details/gt2bqmherhr.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.smart0.xyz/Article/details/gt2jugqsglz.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yj20258888.top/Article/details/gt2rcsbzeiy.html

[A12] 字符串插值 / 格式化
来源：http://dali.bjfxy.top/Article/details/gt2gapblcqu.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gravaivc.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhoulong.xyz/Article/details/gt2nnzqtkfc.html

JS:   `Hello, ${name}!`
来源：http://dali.aibaodan.cn/Article/details/gt2rxhkhoxd.html

TS:   `Hello, ${name}!`
来源：http://dali.hnxiangtu.top/Article/details/gt2oxzaryxu.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cqqctfyp.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.dashuyun.cn/Article/details/gt2wriodimk.html

Ruby: "Hello, #{name}!"
来源：http://dali.hnxiangtu.top/Article/details/gt2fvbkohiw.html

C#:   $"Hello, {name}!"
来源：http://dali.andypj.xyz/Article/details/gt2zxjizpto.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.xuanzx.com/Article/details/gt2rcykwfsv.html

Py:   "第一行\n第二行"
来源：http://dali.gaohongyu789.top/Article/details/gt2fcqbteeu.html

PHP:  "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gt2izzgihcw.html

JS:   "第一行\n第二行"
来源：http://dali.hfpthk.cn/Article/details/gt2pigukuzv.html

TS:   "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gt2lpkecwdj.html

Java: "第一行\n第二行"
来源：http://dali.tanke756.top/Article/details/gt2uyrpbfuz.html

Go:   "第一行\n第二行"
来源：http://dali.guowangkeji.top/Article/details/gt2swiqtgkx.html

Ruby: "第一行\n第二行"
来源：http://dali.cdnleiting.top/Article/details/gt2gacxfegj.html

C#:   "第一行\n第二行"
来源：http://dali.ybcxt.top/Article/details/gt2aoiyzxek.html

[A14] 注释写法
来源：http://dali.hywenlv.cn/Article/details/gt2lyrfvoyb.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.kuanghao11.cn/Article/details/gt2vmplwzah.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yjpkvyxn.html

JS:   // 单行；/* 多行 */
来源：http://dali.meibo888.top/Article/details/gt2eeppphre.html

TS:   // 单行；/* 多行 */
来源：http://dali.guowangkeji.top/Article/details/gt2khrdnjvt.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zdqjudy.top/Article/details/gt2tdbyeoyp.html

Go:   // 单行；/* 多行 */
来源：http://dali.yj20258888.top/Article/details/gt2eslaahhf.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhongyouzk.top/Article/details/gt2oyjjhwti.html

C#:   // 单行；/* 多行 */
来源：http://dali.chenzaomai.com/Article/details/gt2vbdsykey.html

[A15] 空值判断与默认值
来源：http://dali.iojbl.cn/Article/details/gt2jqsngpqz.html

Py:   value = data or "默认值"
来源：http://dali.hywenlv.cn/Article/details/gt2upoppkub.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pefubwpt.html

JS:   const value = data ?? "默认值";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ywoqhnmv.html

TS:   const value = data ?? "默认值";
来源：http://dali.wangshuangyany.cn/Article/details/gt2uvvtzrhc.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jinqigufen.top/Article/details/gt2cijyzbct.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yongpay.top/Article/details/gt2qgbajrmn.html

Ruby: value = data || "默认值"
来源：http://dali.havefunace.top/Article/details/gt2fncgciyr.html

C#:   var value = data ?? "默认值";
来源：http://dali.aizwys.cn/Article/details/gt2zbhrtwvh.html

[A16] 真假值判断规则
来源：http://dali.9152youxi.cn/Article/details/gt2bxzsteks.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.shzxlz.cn/Article/details/gt2cvhnbtyy.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hnqzz.top/Article/details/gt2mnocumol.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.nanxuanxn.top/Article/details/gt2ixnmgkgq.html

TS:   if (!x) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lgebiirx.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2iukdhonx.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.nanxinkj.top/Article/details/gt2fkolvkkp.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.hnqzz.top/Article/details/gt2yvykbtkw.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.andypj.xyz/Article/details/gt2emhfsjij.html

[A17] 位运算
来源：http://dali.cheryme.top/Article/details/gt2lxjtshgr.html


<!-- 参考信息 -->