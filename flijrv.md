代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.zhixingplan.top/Article/details/gtagbyvypy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yvedp.cn/Article/details/gtofezwlya.html

[U92] JS：深拷贝
来源：http://dali.aibaodan.cn/Article/details/gtpjsxwujw.html

structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gtxkmiktvx.html

[U93] JS：模板字符串
来源：http://dali.vqdsnc.cn/Article/details/gtxjtcqaxw.html

`共 ${n} 条`
来源：http://dali.0kj1m.cn/Article/details/gtceezmkpo.html

[U94] JS：箭头函数
来源：http://dali.yueranfly.top/Article/details/gtqbuhteux.html

const double = x => x * 2;
来源：http://dali.havefunace.top/Article/details/gtwdulutgs.html

[U95] JS：Promise 包装
来源：http://dali.tianlin.xyz/Article/details/gtzldutrxh.html

new Promise((resolve, reject) => {})
来源：http://dali.316326.xyz/Article/details/gtkjgdbura.html

[U96] JS：async/await 与异常
来源：http://dali.jiagoushi.top/Article/details/gtolkwqljn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gtnpflvkki.html

[U97] JS：并发请求
来源：http://dali.tian-w.cn/Article/details/gtddlvrtpq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gtgxekydlt.html

[U98] JS：fetch 带 JSON
来源：http://dali.c1oappe.top/Article/details/gtrouejfsw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hammf.cn/Article/details/gtbzfmsclw.html

[U99] JS：事件监听
来源：http://dali.sxryk.cn/Article/details/gtdkfvcvtp.html

el.addEventListener("click", e => {})
来源：http://dali.dashuyun.cn/Article/details/gtuzemqtee.html

[U100] JS：DOM 查询
来源：http://dali.sweek.top/Article/details/gtikfpzlmt.html

document.querySelector(".item")
来源：http://dali.chenlongwang.top/Article/details/gtdocuxxrb.html

[U101] JS：classList 操作
来源：http://dali.yuanzhike.top/Article/details/gttwhwikjl.html

el.classList.toggle("active")
来源：http://dali.meibo888.top/Article/details/gtirtrsytb.html

[U102] JS：本地存储
来源：http://dali.zhixingplan.top/Article/details/gtddksrnam.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.dashuyun.cn/Article/details/gtfguzymct.html

[U103] JS：定时器
来源：http://dali.pengpengdd.cyou/Article/details/gtlnyzyyzj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkizrcpob.html

[U104] JS：防抖
来源：http://dali.iojbl.cn/Article/details/gtdvdyvoen.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cheryme.top/Article/details/gthqzcogrw.html

[U105] JS：节流
来源：http://dali.hysaishi.cn/Article/details/gtwevhwfoq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xylfe.cn/Article/details/gtwwcuksgp.html

[U106] JS：日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gtmtjyksoz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hammf.cn/Article/details/gtmbdenpvj.html

[U107] JS：数字千分位
来源：http://dali.yonumen.top/Article/details/gtfafgcpwx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hfpthk.cn/Article/details/gtsjzomzyr.html

[U108] JS：随机整数
来源：http://dali.shuidangran.top/Article/details/gtjhwgtfro.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.tanke756.top/Article/details/gtdgkbwygt.html

[U109] JS：数组分组
来源：http://dali.yj20258.top/Article/details/gtjsupiscc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jlsjyb.cn/Article/details/gtoriytjxi.html

[U110] JS：数组分块
来源：http://dali.shzxlz.cn/Article/details/gtjxhiwisi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hnxiangtu.top/Article/details/gteeedomni.html

[U111] JS：对象转 Map
来源：http://dali.bjfxy.top/Article/details/gtttpatihe.html

new Map(Object.entries(obj))
来源：http://dali.shuidangran.top/Article/details/gtvpyxzcyw.html

[U112] JS：字符串补位
来源：http://dali.fengsongda.top/Article/details/gtlrvgcfuy.html

"7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtoihtedxk.html

[U113] JS：正则替换全部
来源：http://dali.zycfv.cn/Article/details/gtvufeeadu.html

s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtnsieudot.html

[U114] JS：JSON 深比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlkaiyoh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sufxvd.cn/Article/details/gtpanbqdgk.html

[U115] JS：生成 UUID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnixbbmuh.html

crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gtlpmfatre.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hongshengwenyu.top/Article/details/gtlnspomsd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yonumen.top/Article/details/gtcejbajbw.html

[U117] JS：单元测试
来源：http://dali.jqgfzy.top/Article/details/gttxhejheu.html

npm i -D vitest;  npx vitest
来源：http://dali.shangyingyoupin.top/Article/details/gtgqumwrxl.html

[U118] JS：开发服务器
来源：http://dali.quarkkingdee.top/Article/details/gtlbmmgwal.html

npm i -D vite;  npx vite
来源：http://dali.9152youxi.cn/Article/details/gtnmqltkcc.html

[U119] JS：生产构建
来源：http://dali.hammf.cn/Article/details/gtjjhkmebv.html

npx vite build
来源：http://dali.0kj1m.cn/Article/details/gtcbkaexjr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yanxiufei.cn/Article/details/gtwvgijzra.html

import.meta.env.VITE_API_URL
来源：http://dali.hysaishi.cn/Article/details/gtmulfhbtu.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtsgbobjnx.html

统计汇总
来源：http://dali.birdmap.top/Article/details/gtkxdiqfhg.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtrmvpaszb.html

按语言统计（条）：
来源：http://dali.yj20258.top/Article/details/gtuccznidn.html

Python ......... 252
来源：http://dali.cashguo.top/Article/details/gtrygyvbph.html

PHP ............ 252
来源：http://dali.pengpengdd.cyou/Article/details/gtdqdlurec.html

JavaScript ..... 252
来源：http://dali.yongpay.top/Article/details/gttfrjmgrn.html

TypeScript ..... 212
来源：http://dali.shzxlz.cn/Article/details/gtlozclwiu.html

Java ........... 212
来源：http://dali.haohaochexian.top/Article/details/gtithnpjxe.html

Go ............. 212
来源：http://dali.feifeiyinyue.top/Article/details/gtshrfkzbu.html

Ruby ........... 212
来源：http://dali.hysaishi.cn/Article/details/gteuysnzuo.html

C# ............. 212
来源：http://dali.zycfv.cn/Article/details/gtncuxxnap.html

C .............. 30
来源：http://dali.xinyue.icu/Article/details/gtmaqfhhih.html

C++ ............ 30
来源：http://dali.dashuyun.cn/Article/details/gtchusujpw.html

SQL ............ 90
来源：http://dali.daria6918.cn/Article/details/gtqcrioyqu.html

Bash ........... 80
来源：http://dali.yueranfly.top/Article/details/gttzssrjrb.html

Kotlin ......... 15
来源：http://dali.sysykeji.top/Article/details/gtqbbwjcoq.html

Swift .......... 15
来源：http://dali.jianghu66.top/Article/details/gtbgqwjfwo.html

Lua ............ 10
来源：http://dali.aizwys.cn/Article/details/gtwlujvdep.html

Perl ........... 10
来源：http://dali.shanyushiyangtech.top/Article/details/gtnyxrmcdo.html

Scala .......... 10
来源：http://dali.jianghu66.top/Article/details/gtajzpqscz.html

------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gthzsiykrv.html

合计 ........... 2106 条
来源：http://dali.sysykeji.top/Article/details/gtyxibctoz.html

按章节统计：
来源：http://dali.shzxlz.cn/Article/details/gtmibgctga.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cucudq.cn/Article/details/gtybtvjsnm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.snrcjt.cn/Article/details/gtadffwxlc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.daria6918.cn/Article/details/gtafbsflqw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gtyiqrzhoj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shzxlz.cn/Article/details/gthzblzaxy.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ppjwa.cn/Article/details/gtjnvdfwmt.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gtazgwnrvk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shzxlz.cn/Article/details/gtjmvhripi.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gtxbsggkuk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xylfe.cn/Article/details/gtyvvqlgaj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jiagoushi.top/Article/details/gtiifdwgui.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gtawatonno.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gthptntrim.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gtjglprkky.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhixingplan.top/Article/details/gtkmcigpmt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gtspgjddod.html

Q SQL 专题                              90
来源：http://dali.smart0.xyz/Article/details/gttcslxjbf.html

R Bash 专题                             80
来源：http://dali.xinyue.icu/Article/details/gteudwpibv.html

S C / C++ 专题                          60
来源：http://dali.dianchejie.cn/Article/details/gtqmudhymk.html

T 其他语言补充                          60
来源：http://dali.ivvv.top/Article/details/gtxytfwygv.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gtbrpahkvd.html

------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gtgsgpblpy.html

合计                                  2106 条
来源：http://dali.sufxvd.cn/Article/details/gtawxrnihk.html

--------------------------------------------------------------------------------
来源：http://dali.fzhhl.top/Article/details/gtkqoeculg.html

使用提醒
来源：http://dali.shzxlz.cn/Article/details/gtyooknoli.html

--------------------------------------------------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gteprdypeb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.vqdsnc.cn/Article/details/gtbgxcsimd.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xuetiantiany.cn/Article/details/gtthcmnpka.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.gogol.net.cn/Article/details/gtqggwsjpn.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.guannengcc.top/Article/details/gtowzlgban.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.wangshuangyany.cn/Article/details/gtabawplgp.html

—— 文件结束 ——
来源：http://dali.pycfn.com/Article/details/gtgelyrnli.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtnhorzmlv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ydzc1.top/Article/details/gtkvnylnas.html

Common Programming Examples Cheat Book
来源：http://dali.sysykeji.top/Article/details/gtvsxllvey.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbigvkil.html

【收录内容】
来源：http://dali.ydzc1.top/Article/details/gtdbhfrwsg.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jinqigufen.top/Article/details/gtyxcatboh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yvedp.cn/Article/details/gtqaerulks.html

SQL · Bash · C · C++
来源：http://dali.xinyue.icu/Article/details/gttradbzxl.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqcemqsu.html

【使用说明】
来源：http://dali.xuetiantiany.cn/Article/details/gteuelebwc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.xziqi.cn/Article/details/gtehrlcaat.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.dianchejie.cn/Article/details/gtxroflhsd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.wangdashe.top/Article/details/gtuyyrmhak.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.nanxinkj.top/Article/details/gtavzuhwcl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.gogol.net.cn/Article/details/gtfhlmzfum.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jlsjyb.cn/Article/details/gtnjykmkkx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.guowangkeji.top/Article/details/gtgipxlmlk.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhiwuduotai.top/Article/details/gtqqndvetn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.gogol.net.cn/Article/details/gtqbaszvqz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.sufxvd.cn/Article/details/gtbawhejtu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xylfe.cn/Article/details/gturbquzus.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.sysykeji.top/Article/details/gtshvjtnpb.html

【文件统计】
来源：http://dali.fzhhl.top/Article/details/gtclgfnxmm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhengqikj.top/Article/details/gtmhadgrxm.html

--------------------------------------------------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gtvxitjgcr.html

目  录
来源：http://dali.jinqigufen.top/Article/details/gtgmswkpvf.html

--------------------------------------------------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gtfqgopuqd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hammf.cn/Article/details/gtflguhpeq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.snrcjt.cn/Article/details/gtrknbcqpo.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.iojbl.cn/Article/details/gtmmzzujfj.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.fzhhl.top/Article/details/gtflnvkppx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhjejotd.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.nanxuanxn.top/Article/details/gtakrinlcv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.daxiang520.top/Article/details/gtdyocbwur.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqrbeden.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtiucvnehf.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtegnvjtkv.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gtjgnrxmzq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhixingplan.top/Article/details/gtssfvwmeo.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gtlnwiaeee.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.chenlongwang.top/Article/details/gtzsidkubc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.fengsongda.top/Article/details/gtojxaltnn.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtqzspikoz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shuidangran.top/Article/details/gtoqwvdjvs.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhongyouzk.top/Article/details/gtxunrxeqc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.cashguo.top/Article/details/gtooaoxcgr.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.0kj1m.cn/Article/details/gttwbrxlrp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sweek.top/Article/details/gtjhrhquxu.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtcawpzvlx.html

A. 基础语法与类型
来源：http://dali.yuanzhike.top/Article/details/gtbenfkscx.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtrdokjxcs.html

[A01] Hello World
来源：http://dali.zdqjudy.top/Article/details/gtxtsnsfgz.html

Py:   print("Hello, World!")
来源：http://dali.yuanzhike.top/Article/details/gtxdobiqsz.html

PHP:  echo "Hello, World!";
来源：http://dali.yanxiufei.cn/Article/details/gtjaqpqvmf.html

JS:   console.log("Hello, World!");
来源：http://dali.yj20258.top/Article/details/gtqsjtgkae.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.quarkkingdee.top/Article/details/gtpydsdvjc.html

Java: System.out.println("Hello, World!");
来源：http://dali.pycfn.com/Article/details/gtxtqkvoov.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.nanxuanxn.top/Article/details/gtavndwhbr.html

Ruby: puts "Hello, World!"
来源：http://dali.feifeiyinyue.top/Article/details/gthgjozoky.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hammf.cn/Article/details/gthqlmrzsf.html

[A02] 变量声明与赋值
来源：http://dali.xuanzx.com/Article/details/gtkgfzqwur.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sxryk.cn/Article/details/gtikasopha.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zdqjudy.top/Article/details/gtdzyihqvq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpcorqeo.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.quarkkingdee.top/Article/details/gtihicfryd.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yongpay.top/Article/details/gtshywgrid.html

Go:   name := "Alex"; age := 20
来源：http://dali.jinqigfzy.top/Article/details/gtbfvckray.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gzhubu.top/Article/details/gtmshtuuyo.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.smart0.xyz/Article/details/gttfzfqlic.html

[A03] 常量定义
来源：http://dali.hnxiangtu.top/Article/details/gtqfjgqhku.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hnqzz.top/Article/details/gtzboaizda.html

PHP:  const PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtvbxwmkbe.html

JS:   const PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtglwcdlio.html

TS:   const PI: number = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtxmguirpn.html

Java: static final double PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtdndowoiu.html

Go:   const PI = 3.14159
来源：http://dali.shangyingyoupin.top/Article/details/gtouddotox.html

Ruby: PI = 3.14159
来源：http://dali.chenjidiqi.icu/Article/details/gteaprcgyg.html

C#:   const double PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtofpdaald.html

[A04] 判断变量类型
来源：http://dali.zhoulong.xyz/Article/details/gtocllzokv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhoulong.xyz/Article/details/gthjtvaamr.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ydzc1.top/Article/details/gtsziwubrn.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zycfv.cn/Article/details/gthkfcraux.html

TS:   typeof x; x instanceof Date
来源：http://dali.kuanghao11.cn/Article/details/gtuogmgbeg.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.andypj.xyz/Article/details/gtqlgxfdrb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhixingplan.top/Article/details/gtfywhtfxj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.iojbl.cn/Article/details/gtudphectz.html

C#:   x.GetType().Name; x is int
来源：http://dali.sweek.top/Article/details/gtqxiywzwt.html

[A05] 整数除法与取模
来源：http://dali.redwolf501.top/Article/details/gtwtptbagx.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yangfankeji.com/Article/details/gtzdpvcamk.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hammf.cn/Article/details/gthwxzlodr.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.guowangkeji.top/Article/details/gtotxoemar.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gtxevrgzxb.html

Java: 7 / 2; 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gtolwdqadp.html

Go:   7 / 2; 7 % 2
来源：http://dali.birdmap.top/Article/details/gtxlxqtswd.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gtrodztwyl.html

C#:   7 / 2; 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gtmonmofvh.html

[A06] 字符串转数字
来源：http://dali.yj20258888.top/Article/details/gthhrnglyx.html

Py:   int("42"); float("3.14")
来源：http://dali.hnxiangtu.top/Article/details/gtwpspnnyn.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hammf.cn/Article/details/gtjdzemnfo.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jianghu66.top/Article/details/gtyggwnajs.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jqgufenzy.top/Article/details/gttgjaebmr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.xuanzx.com/Article/details/gtdipvrvsk.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yueranfly.top/Article/details/gtvzxcllyk.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.daxiang520.top/Article/details/gthxirijcq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhiwuduotai.top/Article/details/gtrrciusoe.html

[A07] 数字转字符串
来源：http://dali.pycfn.com/Article/details/gtvuhoyfdz.html

Py:   str(42)
来源：http://dali.iojbl.cn/Article/details/gtjiyqnmwa.html

PHP:  (string) 42; strval(42)
来源：http://dali.cqqwz.cn/Article/details/gtgkcwzlef.html

JS:   String(42); (42).toString()
来源：http://dali.andypj.xyz/Article/details/gtyiazixst.html

TS:   String(42)
来源：http://dali.shuidangran.top/Article/details/gtbesvichi.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.smart0.xyz/Article/details/gtzipwlgyj.html

Go:   strconv.Itoa(42)
来源：http://dali.fzhhl.top/Article/details/gtdeebyggy.html

Ruby: 42.to_s
来源：http://dali.9152youxi.cn/Article/details/gtmyrmtohp.html

C#:   42.ToString()
来源：http://dali.yj20258888.top/Article/details/gtquzidtov.html

[A08] 取整与四舍五入
来源：http://dali.zhoulong.xyz/Article/details/gtejwukszv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.aizwys.cn/Article/details/gtfbwzluxn.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.pengpengdd.cyou/Article/details/gtvgozmezf.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jqgfzy.top/Article/details/gtmdwuprwg.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jinqigfzy.top/Article/details/gtygcnvnic.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.wangshuangyany.cn/Article/details/gtzuiouynz.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.316326.xyz/Article/details/gtdsjvhbvm.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.vqdsnc.cn/Article/details/gtegdwzbrs.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yj20258.top/Article/details/gtrerwgwrq.html

[A09] 绝对值与最大最小值
来源：http://dali.shangyingyoupin.top/Article/details/gturffyeha.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gtoeljnrlu.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.daria6918.cn/Article/details/gtojdtzsbt.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gtlccleynj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.xuanzx.com/Article/details/gtyqagecns.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gtozgylvgs.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.guannengcc.top/Article/details/gtxtijoowu.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jianghu66.top/Article/details/gtzqjhbaxb.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gtxwyqknmo.html

[A10] 生成随机数
来源：http://dali.zhengqikj.top/Article/details/gtzxyasfuy.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jqgufenzy.top/Article/details/gtafbtgfmh.html

PHP:  random_int(1, 100);
来源：http://dali.cheryme.top/Article/details/gtzbcghijq.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.wangdashe.top/Article/details/gtcipxoeou.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvftxcldo.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yongpay.top/Article/details/gtiuivzqnl.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.vqdsnc.cn/Article/details/gtdenglomd.html

Ruby: rand(1..100)
来源：http://dali.yongpay.top/Article/details/gtfualiutp.html

C#:   new Random().Next(1, 101)
来源：http://dali.aizwys.cn/Article/details/gtntvwnkgp.html

[A11] 条件表达式（三元）
来源：http://dali.meibo888.top/Article/details/gtnealkybl.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.nwbrower.top/Article/details/gtexztlxzp.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.tanke756.top/Article/details/gtebqpecll.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jyoumei.cn/Article/details/gtwxljphxg.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.birdmap.top/Article/details/gthijmlmpk.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yueranfly.top/Article/details/gtxaosxfvb.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.nanxinkj.top/Article/details/gtlctvnrfn.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.wangdashe.top/Article/details/gtphxdfkge.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.birdmap.top/Article/details/gtkiohemdq.html

[A12] 字符串插值 / 格式化
来源：http://dali.hywenlv.cn/Article/details/gtdxqegtxv.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jqgufenzy.top/Article/details/gtaqrqaxsg.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.hnxiangtu.top/Article/details/gtizrjalzg.html

JS:   `Hello, ${name}!`
来源：http://dali.jinqigufen.top/Article/details/gtufijbskr.html

TS:   `Hello, ${name}!`
来源：http://dali.aizwys.cn/Article/details/gtirgiyjpx.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yj20258888.top/Article/details/gthgsiddsf.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.ybcxt.top/Article/details/gtwwnvlaog.html

Ruby: "Hello, #{name}!"
来源：http://dali.zycfv.cn/Article/details/gtpxpnxydl.html

C#:   $"Hello, {name}!"
来源：http://dali.guannengcc.top/Article/details/gtyezkygyx.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.sufxvd.cn/Article/details/gtxaxhvkfb.html

Py:   "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gtobcthcxs.html

PHP:  "第一行\n第二行"
来源：http://dali.mhx1999.top/Article/details/gtfbkuxten.html

JS:   "第一行\n第二行"
来源：http://dali.dianchejie.cn/Article/details/gteodfigzk.html

TS:   "第一行\n第二行"
来源：http://dali.c1oappe.top/Article/details/gtiimphrot.html

Java: "第一行\n第二行"
来源：http://dali.yuanzhike.top/Article/details/gtnyoarqyg.html

Go:   "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbtmbdye.html

Ruby: "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gtfbkaqqfh.html

C#:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gtexnwamoh.html

[A14] 注释写法
来源：http://dali.zhengqikj.top/Article/details/gtawmcltgi.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yanxiufei.cn/Article/details/gtkyeftynu.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.cheryme.top/Article/details/gtbdnrtilu.html

JS:   // 单行；/* 多行 */
来源：http://dali.cucudq.cn/Article/details/gtmfdhymjw.html

TS:   // 单行；/* 多行 */
来源：http://dali.yonumen.top/Article/details/gtjgjafgba.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.meibo888.top/Article/details/gtaoissftr.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gtywdanhkp.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.ybcxt.top/Article/details/gtuzfwhqgk.html

C#:   // 单行；/* 多行 */
来源：http://dali.daxiang520.top/Article/details/gtrwixuhvj.html

[A15] 空值判断与默认值
来源：http://dali.0kj1m.cn/Article/details/gtbeazeroe.html

Py:   value = data or "默认值"
来源：http://dali.pycfn.com/Article/details/gtxzrdpswo.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.hammf.cn/Article/details/gtlrxkqhjr.html

JS:   const value = data ?? "默认值";
来源：http://dali.jqgfzy.top/Article/details/gtlreqdmdh.html

TS:   const value = data ?? "默认值";
来源：http://dali.chenjidiqi.icu/Article/details/gtbvabwdlu.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jianghu66.top/Article/details/gtstxklgay.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.gaohongyu789.top/Article/details/gtmazwnnmo.html


<!-- 参考信息 -->