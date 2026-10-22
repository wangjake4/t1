代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.fzhhl.top/Article/details/gtdpompofe.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hysaishi.cn/Article/details/gtfgimppzl.html

[U92] JS：深拷贝
来源：http://dali.tanke756.top/Article/details/gtgwkzyzmd.html

structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gtbygruvhg.html

[U93] JS：模板字符串
来源：http://dali.jqgufenzy.top/Article/details/gtfczdxayb.html

`共 ${n} 条`
来源：http://dali.xuanzx.com/Article/details/gtqruabjoz.html

[U94] JS：箭头函数
来源：http://dali.nwbrower.top/Article/details/gtwqsrayzh.html

const double = x => x * 2;
来源：http://dali.gotoacloud.top/Article/details/gtlqhgbzhu.html

[U95] JS：Promise 包装
来源：http://dali.ydzc1.top/Article/details/gtgcpvfqpi.html

new Promise((resolve, reject) => {})
来源：http://dali.shanyushiyangtech.top/Article/details/gtmdaiubpk.html

[U96] JS：async/await 与异常
来源：http://dali.vqdsnc.cn/Article/details/gtnxikamfs.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gtopxijjeb.html

[U97] JS：并发请求
来源：http://dali.gotoacloud.top/Article/details/gtxjfivisr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gtzyfkfass.html

[U98] JS：fetch 带 JSON
来源：http://dali.fzhhl.top/Article/details/gtgkmzjnyj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.aibaodan.cn/Article/details/gtrbymjuag.html

[U99] JS：事件监听
来源：http://dali.ppjwa.cn/Article/details/gtjptyfxyy.html

el.addEventListener("click", e => {})
来源：http://dali.hysaishi.cn/Article/details/gtqcgdjcve.html

[U100] JS：DOM 查询
来源：http://dali.yvedp.cn/Article/details/gtyxlspexp.html

document.querySelector(".item")
来源：http://dali.pengpengdd.cyou/Article/details/gthqjzfcfz.html

[U101] JS：classList 操作
来源：http://dali.hfpthk.cn/Article/details/gtfyvpcqrw.html

el.classList.toggle("active")
来源：http://dali.fengsongda.top/Article/details/gtkwoytpmr.html

[U102] JS：本地存储
来源：http://dali.ehwqpu.com/Article/details/gtoyhjfzar.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.cashguo.top/Article/details/gtosgjeiud.html

[U103] JS：定时器
来源：http://dali.shuidangran.top/Article/details/gtwelohlrs.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jyoumei.cn/Article/details/gtkbsbfrcf.html

[U104] JS：防抖
来源：http://dali.cheryme.top/Article/details/gtibgqrfpp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gtdhdhwbkw.html

[U105] JS：节流
来源：http://dali.havefunace.top/Article/details/gtwjbsrlhs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.feifeiyinyue.top/Article/details/gtkulfemou.html

[U106] JS：日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gtyfsvjqvd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gteiwunzim.html

[U107] JS：数字千分位
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqxwtjsn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.svipenyu.cn/Article/details/gtwbodxtzq.html

[U108] JS：随机整数
来源：http://dali.iojbl.cn/Article/details/gtojulbxxu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hfpthk.cn/Article/details/gtsavfctps.html

[U109] JS：数组分组
来源：http://dali.jinqigfzy.top/Article/details/gtggrdgbqf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yj202588.top/Article/details/gttyybahqt.html

[U110] JS：数组分块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdrranor.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yuxming.cn/Article/details/gtddmcxlrh.html

[U111] JS：对象转 Map
来源：http://dali.zhengqikj.top/Article/details/gtjtzqciuy.html

new Map(Object.entries(obj))
来源：http://dali.yj202588.top/Article/details/gtzkulkvvn.html

[U112] JS：字符串补位
来源：http://dali.jinghuilouyu.cn/Article/details/gtbaorrrgl.html

"7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtmxgqyguc.html

[U113] JS：正则替换全部
来源：http://dali.cheryme.top/Article/details/gtvsmhitzo.html

s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtldkftvrp.html

[U114] JS：JSON 深比较
来源：http://dali.hysaishi.cn/Article/details/gtpewxdzao.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwrqguth.html

[U115] JS：生成 UUID
来源：http://dali.0kj1m.cn/Article/details/gtlkzuqjvc.html

crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gtaxheunqb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gogol.net.cn/Article/details/gtyzmlrnzu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yuanzhike.top/Article/details/gtzxvrlofh.html

[U117] JS：单元测试
来源：http://dali.hfpthk.cn/Article/details/gtmamivzqu.html

npm i -D vitest;  npx vitest
来源：http://dali.shanyushiyangtech.top/Article/details/gtimcumrpu.html

[U118] JS：开发服务器
来源：http://dali.jianghu66.top/Article/details/gtqusatfrc.html

npm i -D vite;  npx vite
来源：http://dali.haohaochexian.top/Article/details/gthgpuxxaw.html

[U119] JS：生产构建
来源：http://dali.316326.xyz/Article/details/gtzhlssqdo.html

npx vite build
来源：http://dali.zhengqikj.top/Article/details/gtdyehwotr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shzxlz.cn/Article/details/gtnwjzkvba.html

import.meta.env.VITE_API_URL
来源：http://dali.cqqwz.cn/Article/details/gtkbrmmwww.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhesdipq.html

统计汇总
来源：http://dali.yj20258.top/Article/details/gtayhizdgn.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtjszsaatm.html

按语言统计（条）：
来源：http://dali.fengsongda.top/Article/details/gttmzlhfam.html

Python ......... 252
来源：http://dali.daria6918.cn/Article/details/gtqnbiuxuj.html

PHP ............ 252
来源：http://dali.chenzaomai.com/Article/details/gtmgpjdgcb.html

JavaScript ..... 252
来源：http://dali.jyoumei.cn/Article/details/gtryvrlwfy.html

TypeScript ..... 212
来源：http://dali.smart0.xyz/Article/details/gtqfjcpmrl.html

Java ........... 212
来源：http://dali.svipenyu.cn/Article/details/gthnotttzg.html

Go ............. 212
来源：http://dali.jlsjyb.cn/Article/details/gtgyqycfkl.html

Ruby ........... 212
来源：http://dali.yanxiufei.cn/Article/details/gtlmfumyrs.html

C# ............. 212
来源：http://dali.chenzaomai.com/Article/details/gtskkznzim.html

C .............. 30
来源：http://dali.cashguo.top/Article/details/gtizlxwcah.html

C++ ............ 30
来源：http://dali.daria6918.cn/Article/details/gtclmumzxk.html

SQL ............ 90
来源：http://dali.svipenyu.cn/Article/details/gtlxwgnlbi.html

Bash ........... 80
来源：http://dali.hnxiangtu.top/Article/details/gthzbpvupd.html

Kotlin ......... 15
来源：http://dali.ybcxt.top/Article/details/gtzqxhwjul.html

Swift .......... 15
来源：http://dali.cdnleiting.top/Article/details/gthdvmdhrw.html

Lua ............ 10
来源：http://dali.haohaochexian.top/Article/details/gtoljzehsp.html

Perl ........... 10
来源：http://dali.yuxming.cn/Article/details/gtztafkteq.html

Scala .......... 10
来源：http://dali.jiagoushi.top/Article/details/gtwmzwrkdg.html

------------------------------------
来源：http://dali.yvedp.cn/Article/details/gtjbwvssao.html

合计 ........... 2106 条
来源：http://dali.sysykeji.top/Article/details/gtejzqjylv.html

按章节统计：
来源：http://dali.jiagoushi.top/Article/details/gtshllzrtd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yuxming.cn/Article/details/gtuqftsmus.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuipvmeij.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hnxiangtu.top/Article/details/gtsdexxkgw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.mhx1999.top/Article/details/gtbfydcygg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.pycfn.com/Article/details/gtnioshdee.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xziqi.cn/Article/details/gtsrihmxlr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.mhx1999.top/Article/details/gtcriovtxl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shuidangran.top/Article/details/gtakycgjta.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gtutvhtkgd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jlsjyb.cn/Article/details/gthifqjdmf.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gtjsvcoxni.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gtmvgidwdz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xuanzx.com/Article/details/gtzcbaphhg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yonumen.top/Article/details/gtkqntruyy.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.pycfn.com/Article/details/gtvqrzctjw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gtslyrurow.html

Q SQL 专题                              90
来源：http://dali.vqdsnc.cn/Article/details/gtutwexqjb.html

R Bash 专题                             80
来源：http://dali.sweek.top/Article/details/gtdphdppld.html

S C / C++ 专题                          60
来源：http://dali.yj202588.top/Article/details/gtsaysqcsa.html

T 其他语言补充                          60
来源：http://dali.chenlongwang.top/Article/details/gtedzfjhfp.html

U 高频实用片段                         120
来源：http://dali.guowangkeji.top/Article/details/gtgycbxscv.html

------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gtbeboukly.html

合计                                  2106 条
来源：http://dali.yuxming.cn/Article/details/gtrvhmrono.html

--------------------------------------------------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gtnisbblcq.html

使用提醒
来源：http://dali.xinyue.icu/Article/details/gtgdnlqlzs.html

--------------------------------------------------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtiofhntii.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jinqigfzy.top/Article/details/gtoxakrdoe.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zdqjudy.top/Article/details/gtjsorrtlj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hnqzz.top/Article/details/gtrqzqilai.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhongyouzk.top/Article/details/gtxbpknffc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.kuanghao11.cn/Article/details/gtssjlyaak.html

—— 文件结束 ——
来源：http://dali.shzxlz.cn/Article/details/gthaltnqvl.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtffabiyex.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.kuanghao11.cn/Article/details/gtcnwplfar.html

Common Programming Examples Cheat Book
来源：http://dali.316326.xyz/Article/details/gtnbsfmtzp.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtjmexlxws.html

【收录内容】
来源：http://dali.zhoulong.xyz/Article/details/gtkkrlxgrv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.wangshuangyany.cn/Article/details/gtauumjdux.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xziqi.cn/Article/details/gtqothrxpd.html

SQL · Bash · C · C++
来源：http://dali.daria6918.cn/Article/details/gtillxwpha.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xuanzx.com/Article/details/gtrflhqwro.html

【使用说明】
来源：http://dali.vqdsnc.cn/Article/details/gtgnnmditj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.nanxinkj.top/Article/details/gtqfyuohyn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinqigufen.top/Article/details/gthxblkbsh.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yvedp.cn/Article/details/gtsndhwdwi.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yueranfly.top/Article/details/gtbjwwnevw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.quarkkingdee.top/Article/details/gtqjfixyoc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cqqwz.cn/Article/details/gtfticwztd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.tianlin.xyz/Article/details/gtqrbdfkpt.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xuetiantiany.cn/Article/details/gttwtuqocf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhongyouzk.top/Article/details/gthsvyeijx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shangyingyoupin.top/Article/details/gtkrlpvsmd.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jqgfzy.top/Article/details/gtklrradoi.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hammf.cn/Article/details/gtitatwbav.html

【文件统计】
来源：http://dali.iojbl.cn/Article/details/gtmdehywbs.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ehwqpu.com/Article/details/gtjedthxeh.html

--------------------------------------------------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gthonjiijv.html

目  录
来源：http://dali.yj20258888.top/Article/details/gtmywuhwel.html

--------------------------------------------------------------------------------
来源：http://dali.bjfxy.top/Article/details/gtitruwjek.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.birdmap.top/Article/details/gtvqrpjkgg.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.kuanghao11.cn/Article/details/gthnjruaqk.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cheryme.top/Article/details/gtbsiqpdod.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.daria6918.cn/Article/details/gtxbcorzgp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.quarkkingdee.top/Article/details/gtgekacyel.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.cashguo.top/Article/details/gtzdekrptm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xylfe.cn/Article/details/gtngsrjopa.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtgcngsesk.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdkkycrm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.fzhhl.top/Article/details/gtzumuihil.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxvrvror.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.guannengcc.top/Article/details/gtciprfdod.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.bjfxy.top/Article/details/gtfuzinqlz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gaohongyu789.top/Article/details/gtmdhstezr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yuxming.cn/Article/details/gtesforupt.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.mhx1999.top/Article/details/gtkjunudvm.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.wangdashe.top/Article/details/gtpbkogcrw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jqgufenzy.top/Article/details/gtknutokqg.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.cheryme.top/Article/details/gtjwcppjef.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zycfv.cn/Article/details/gtrdglsnyl.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtkyrzvpll.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtfgrzxxag.html

A. 基础语法与类型
来源：http://dali.chenzaomai.com/Article/details/gtdyzpsttp.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtxfeaomhr.html

[A01] Hello World
来源：http://dali.chenzaomai.com/Article/details/gtgaqmhumq.html

Py:   print("Hello, World!")
来源：http://dali.guowangkeji.top/Article/details/gtovkcqpyy.html

PHP:  echo "Hello, World!";
来源：http://dali.ppjwa.cn/Article/details/gttqayqiuo.html

JS:   console.log("Hello, World!");
来源：http://dali.pycfn.com/Article/details/gtektexscj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yonumen.top/Article/details/gtluedcjpj.html

Java: System.out.println("Hello, World!");
来源：http://dali.kuanghao11.cn/Article/details/gtyqnmfpim.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cucudq.cn/Article/details/gtzkndxclf.html

Ruby: puts "Hello, World!"
来源：http://dali.ybcxt.top/Article/details/gtyyavexon.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yanxiufei.cn/Article/details/gtotmweaab.html

[A02] 变量声明与赋值
来源：http://dali.cashguo.top/Article/details/gtnmbrtzfw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zycfv.cn/Article/details/gtpzyyrpno.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xuanzx.com/Article/details/gtwoyvjgag.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jqgufenzy.top/Article/details/gtcrllrvyk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ydzc1.top/Article/details/gtyyddvxxc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ehwqpu.com/Article/details/gtapurinqe.html

Go:   name := "Alex"; age := 20
来源：http://dali.pengpengdd.cyou/Article/details/gtdjqufnsw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkszddgij.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ehwqpu.com/Article/details/gtlukmfosg.html

[A03] 常量定义
来源：http://dali.fengsongda.top/Article/details/gttfkzzggb.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hywenlv.cn/Article/details/gtixvwgowc.html

PHP:  const PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtlouccpuo.html

JS:   const PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtpfupbvxa.html

TS:   const PI: number = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtwmnrezcs.html

Java: static final double PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtrfcxqesq.html

Go:   const PI = 3.14159
来源：http://dali.jiagoushi.top/Article/details/gtpdhqevdn.html

Ruby: PI = 3.14159
来源：http://dali.guowangkeji.top/Article/details/gtncsgjiul.html

C#:   const double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtblzgdpky.html

[A04] 判断变量类型
来源：http://dali.yj20258.top/Article/details/gtvbdnswdz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.quarkkingdee.top/Article/details/gtovlkaums.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.dashuyun.cn/Article/details/gtyljlnfnn.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yongpay.top/Article/details/gtvhywlfcg.html

TS:   typeof x; x instanceof Date
来源：http://dali.birdmap.top/Article/details/gtpfkbttrk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ehwqpu.com/Article/details/gtuyilfrbv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hammf.cn/Article/details/gtvgmgonox.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.hfpthk.cn/Article/details/gtwbbjxlqr.html

C#:   x.GetType().Name; x is int
来源：http://dali.ybcxt.top/Article/details/gtmvjrpugk.html

[A05] 整数除法与取模
来源：http://dali.jqgufenzy.top/Article/details/gtzawfpoaz.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xuetiantiany.cn/Article/details/gtxcyuzpkm.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.gzhubu.top/Article/details/gtdmedmrvp.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.birdmap.top/Article/details/gtklbkyghv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yvedp.cn/Article/details/gtqapvtutg.html

Java: 7 / 2; 7 % 2
来源：http://dali.hammf.cn/Article/details/gtizmukvso.html

Go:   7 / 2; 7 % 2
来源：http://dali.sxryk.cn/Article/details/gtdxufdply.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.mhx1999.top/Article/details/gthkggxquo.html

C#:   7 / 2; 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gtmrcefgkw.html

[A06] 字符串转数字
来源：http://dali.ydzc1.top/Article/details/gtlmfrojso.html

Py:   int("42"); float("3.14")
来源：http://dali.guannengcc.top/Article/details/gtudalamye.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrsgkosvs.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.aizwys.cn/Article/details/gtzdknsmuw.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ppjwa.cn/Article/details/gtwwpejayb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.tian-w.cn/Article/details/gtugfuwwmu.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.xinyue.icu/Article/details/gtlthuvogc.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.sweek.top/Article/details/gtczdsqaro.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncvjtwtl.html

[A07] 数字转字符串
来源：http://dali.zhongyouzk.top/Article/details/gtgsrfezbt.html

Py:   str(42)
来源：http://dali.yj20258.top/Article/details/gtikwgbmfi.html

PHP:  (string) 42; strval(42)
来源：http://dali.guowangkeji.top/Article/details/gtetzjitxg.html

JS:   String(42); (42).toString()
来源：http://dali.meibo888.top/Article/details/gtkhhzxkfg.html

TS:   String(42)
来源：http://dali.cheryme.top/Article/details/gtumtsunxt.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.cqqwz.cn/Article/details/gtowbqycyt.html

Go:   strconv.Itoa(42)
来源：http://dali.jinqigufen.top/Article/details/gtkrkaapid.html

Ruby: 42.to_s
来源：http://dali.nwbrower.top/Article/details/gtjpwkomdu.html

C#:   42.ToString()
来源：http://dali.jiagoushi.top/Article/details/gtgeelwevw.html

[A08] 取整与四舍五入
来源：http://dali.ehwqpu.com/Article/details/gtyketihoi.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.gotoacloud.top/Article/details/gtdtssacdi.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yuanzhike.top/Article/details/gturdlupkc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.redwolf501.top/Article/details/gtukngpfrn.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.sweek.top/Article/details/gtsmzrqbql.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.xziqi.cn/Article/details/gtizsjyyik.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yvedp.cn/Article/details/gtztxdkzbe.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.daria6918.cn/Article/details/gtdnjaggyb.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmckrzzhj.html

[A09] 绝对值与最大最小值
来源：http://dali.svipenyu.cn/Article/details/gtxtukndfq.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.fzhhl.top/Article/details/gtzhusctxx.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtxxxzbvtc.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yj20258.top/Article/details/gtqzyxmkar.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.havefunace.top/Article/details/gtcfzhnhtc.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtjzqzilvl.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yj20258888.top/Article/details/gtptfgyyvn.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.nanxuanxn.top/Article/details/gtwzouypfz.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gtkxdkplcm.html

[A10] 生成随机数
来源：http://dali.bjfxy.top/Article/details/gtnbloptrt.html

Py:   import random; random.randint(1, 100)
来源：http://dali.ivvv.top/Article/details/gtkmeanxta.html

PHP:  random_int(1, 100);
来源：http://dali.gaohongyu789.top/Article/details/gthppyiomb.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yj20258888.top/Article/details/gtpwybbkhw.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.wangdashe.top/Article/details/gtbdshdkla.html

Java: new Random().nextInt(100) + 1
来源：http://dali.sufxvd.cn/Article/details/gtpuujxfjw.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jinqigfzy.top/Article/details/gtpncocjwu.html

Ruby: rand(1..100)
来源：http://dali.zdqjudy.top/Article/details/gtxajgyffx.html

C#:   new Random().Next(1, 101)
来源：http://dali.gzhubu.top/Article/details/gtdiqphdss.html

[A11] 条件表达式（三元）
来源：http://dali.ydzc1.top/Article/details/gttgenoudr.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.gotoacloud.top/Article/details/gthbfiwkoi.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.fengsongda.top/Article/details/gttnrsggwv.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.xuanzx.com/Article/details/gtheqegvwh.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.shzxlz.cn/Article/details/gtwbotleer.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.cdnleiting.top/Article/details/gtlwefacfx.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yj20258.top/Article/details/gtbbtffmkm.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jqgfzy.top/Article/details/gtiecyleyu.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jqgfzy.top/Article/details/gtohcevezp.html

[A12] 字符串插值 / 格式化
来源：http://dali.ehwqpu.com/Article/details/gtffabjlfn.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.smart0.xyz/Article/details/gtdmrbodhd.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.tian-w.cn/Article/details/gtvsmslwmp.html

JS:   `Hello, ${name}!`
来源：http://dali.fengsongda.top/Article/details/gtidpskpyk.html

TS:   `Hello, ${name}!`
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkumulrqc.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.tanke756.top/Article/details/gtqoxooxue.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.gzhubu.top/Article/details/gtfcscqktr.html

Ruby: "Hello, #{name}!"
来源：http://dali.yanxiufei.cn/Article/details/gtbuanihoy.html

C#:   $"Hello, {name}!"
来源：http://dali.zhiwuduotai.top/Article/details/gtncmdysmw.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.hfpthk.cn/Article/details/gtgyxjnqbp.html

Py:   "第一行\n第二行"
来源：http://dali.dashuyun.cn/Article/details/gtwjoepnpp.html

PHP:  "第一行\n第二行"
来源：http://dali.tianlin.xyz/Article/details/gtkhprqcjg.html

JS:   "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gtoeuhxhpb.html

TS:   "第一行\n第二行"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiriipnro.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gtsodldlpo.html

Go:   "第一行\n第二行"
来源：http://dali.xylfe.cn/Article/details/gtjkokjdnl.html

Ruby: "第一行\n第二行"
来源：http://dali.guowangkeji.top/Article/details/gtjtvylddi.html

C#:   "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gtarclugwp.html

[A14] 注释写法
来源：http://dali.yanxiufei.cn/Article/details/gtqpyfwpfk.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yj20258.top/Article/details/gtmbmdpcbh.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yanxiufei.cn/Article/details/gtysimfixp.html

JS:   // 单行；/* 多行 */
来源：http://dali.jyoumei.cn/Article/details/gtmijmfiwy.html

TS:   // 单行；/* 多行 */
来源：http://dali.316326.xyz/Article/details/gttnwxrudw.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hfpthk.cn/Article/details/gtlbreorse.html

Go:   // 单行；/* 多行 */
来源：http://dali.yuxming.cn/Article/details/gtamfnzfgl.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.c1oappe.top/Article/details/gtislapdpq.html

C#:   // 单行；/* 多行 */
来源：http://dali.birdmap.top/Article/details/gtnzxhljto.html

[A15] 空值判断与默认值
来源：http://dali.fengsongda.top/Article/details/gtkxesnxoj.html

Py:   value = data or "默认值"
来源：http://dali.shangyingyoupin.top/Article/details/gtseclwnny.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.hammf.cn/Article/details/gtbjxffipz.html

JS:   const value = data ?? "默认值";
来源：http://dali.daxiang520.top/Article/details/gtsrubachf.html

TS:   const value = data ?? "默认值";
来源：http://dali.shanyushiyangtech.top/Article/details/gtnntzrllv.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.aizwys.cn/Article/details/gtjnmucnlu.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jqgfzy.top/Article/details/gtmtlnudyd.html


<!-- 参考信息 -->