代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.9152youxi.cn/Article/details/gtutkvqeig.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.fzhhl.top/Article/details/gtpfaeuiko.html

[U92] JS：深拷贝
来源：http://dali.sxryk.cn/Article/details/gttvzvlzdl.html

structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gtpqnceqiv.html

[U93] JS：模板字符串
来源：http://dali.zhoulong.xyz/Article/details/gtpteyrznr.html

`共 ${n} 条`
来源：http://dali.hysaishi.cn/Article/details/gtrllxqpdk.html

[U94] JS：箭头函数
来源：http://dali.guowangkeji.top/Article/details/gtnikhisxk.html

const double = x => x * 2;
来源：http://dali.xziqi.cn/Article/details/gthyfxfhyi.html

[U95] JS：Promise 包装
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvuwdinyc.html

new Promise((resolve, reject) => {})
来源：http://dali.yuanzhike.top/Article/details/gtzhfctlgj.html

[U96] JS：async/await 与异常
来源：http://dali.shzxlz.cn/Article/details/gtavobbnmy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtsomtjbnh.html

[U97] JS：并发请求
来源：http://dali.birdmap.top/Article/details/gtcrdooake.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gtsambhsxc.html

[U98] JS：fetch 带 JSON
来源：http://dali.dashuyun.cn/Article/details/gtcyekzydr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.ybcxt.top/Article/details/gtgifqylmw.html

[U99] JS：事件监听
来源：http://dali.yj20258888.top/Article/details/gtkrodudci.html

el.addEventListener("click", e => {})
来源：http://dali.zhiwuduotai.top/Article/details/gtmruvmxiz.html

[U100] JS：DOM 查询
来源：http://dali.chenlongwang.top/Article/details/gtbdeubols.html

document.querySelector(".item")
来源：http://dali.gogol.net.cn/Article/details/gtfpcejtvn.html

[U101] JS：classList 操作
来源：http://dali.jqgfzy.top/Article/details/gtgddrhpui.html

el.classList.toggle("active")
来源：http://dali.yongpay.top/Article/details/gtmrdfmikl.html

[U102] JS：本地存储
来源：http://dali.quarkkingdee.top/Article/details/gtiycktnje.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.wangshuangyany.cn/Article/details/gtavrkovgu.html

[U103] JS：定时器
来源：http://dali.havefunace.top/Article/details/gtqxzrugwy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gogol.net.cn/Article/details/gtbicelutx.html

[U104] JS：防抖
来源：http://dali.cashguo.top/Article/details/gtwehjswqt.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gtulrbzmcv.html

[U105] JS：节流
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudjqkzfw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtyqwwxmcp.html

[U106] JS：日期格式化
来源：http://dali.xziqi.cn/Article/details/gtbkqalpmq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.kuanghao11.cn/Article/details/gtgjrytrwk.html

[U107] JS：数字千分位
来源：http://dali.hywenlv.cn/Article/details/gtnabygakr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yangfankeji.com/Article/details/gtqpmxkjra.html

[U108] JS：随机整数
来源：http://dali.snrcjt.cn/Article/details/gtxlonbaqu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.wangdashe.top/Article/details/gtuzoqihts.html

[U109] JS：数组分组
来源：http://dali.wangshuangyany.cn/Article/details/gtwjtxfuzc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.svipenyu.cn/Article/details/gtkydafkgb.html

[U110] JS：数组分块
来源：http://dali.quarkkingdee.top/Article/details/gtjdqmfojg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.guannengcc.top/Article/details/gtfkwcgwai.html

[U111] JS：对象转 Map
来源：http://dali.svipenyu.cn/Article/details/gtaekqybii.html

new Map(Object.entries(obj))
来源：http://dali.jianghu66.top/Article/details/gtaqzybsdj.html

[U112] JS：字符串补位
来源：http://dali.yueranfly.top/Article/details/gtufiojtpo.html

"7".padStart(3, "0")
来源：http://dali.fzhhl.top/Article/details/gtidouyzgj.html

[U113] JS：正则替换全部
来源：http://dali.yvedp.cn/Article/details/gtlkazwbjl.html

s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gthjxeupda.html

[U114] JS：JSON 深比较
来源：http://dali.gotoacloud.top/Article/details/gtjaqgzyhk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ydzc1.top/Article/details/gtngzjrggy.html

[U115] JS：生成 UUID
来源：http://dali.yuanzhike.top/Article/details/gtgaugoyyo.html

crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gtwrcamltr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.nwbrower.top/Article/details/gtpcdedidp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zdqjudy.top/Article/details/gtwbmdhjro.html

[U117] JS：单元测试
来源：http://dali.gogol.net.cn/Article/details/gtuijdrsxf.html

npm i -D vitest;  npx vitest
来源：http://dali.yueranfly.top/Article/details/gtdjdbinwr.html

[U118] JS：开发服务器
来源：http://dali.zhiwuduotai.top/Article/details/gtpbattbde.html

npm i -D vite;  npx vite
来源：http://dali.chenlongwang.top/Article/details/gtjypvrnei.html

[U119] JS：生产构建
来源：http://dali.c1oappe.top/Article/details/gtbwirxzzu.html

npx vite build
来源：http://dali.fzhhl.top/Article/details/gtxobqotpa.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hysaishi.cn/Article/details/gtzxxcxmsn.html

import.meta.env.VITE_API_URL
来源：http://dali.yuanzhike.top/Article/details/gtuizbkfpa.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gttmkrehjt.html

统计汇总
来源：http://dali.aizwys.cn/Article/details/gteqjouogz.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtojjfpyat.html

按语言统计（条）：
来源：http://dali.9152youxi.cn/Article/details/gtmkyiliym.html

Python ......... 252
来源：http://dali.shzxlz.cn/Article/details/gtypnceymb.html

PHP ............ 252
来源：http://dali.yj20258888.top/Article/details/gtanrcnwyu.html

JavaScript ..... 252
来源：http://dali.cucudq.cn/Article/details/gtohagasrn.html

TypeScript ..... 212
来源：http://dali.birdmap.top/Article/details/gtsofckwrj.html

Java ........... 212
来源：http://dali.fzhhl.top/Article/details/gtvyqfazwm.html

Go ............. 212
来源：http://dali.yanxiufei.cn/Article/details/gtoqivfyvp.html

Ruby ........... 212
来源：http://dali.xylfe.cn/Article/details/gtgkgmmgcv.html

C# ............. 212
来源：http://dali.cqqwz.cn/Article/details/gtnbqoqqed.html

C .............. 30
来源：http://dali.ywan-chungtsiang.top/Article/details/gtepyfwlej.html

C++ ............ 30
来源：http://dali.cdnleiting.top/Article/details/gtjmgvpqlz.html

SQL ............ 90
来源：http://dali.0kj1m.cn/Article/details/gtxxausjrv.html

Bash ........... 80
来源：http://dali.dianchejie.cn/Article/details/gtltsmnhnu.html

Kotlin ......... 15
来源：http://dali.chenjidiqi.icu/Article/details/gtppjbhpfv.html

Swift .......... 15
来源：http://dali.cdnleiting.top/Article/details/gtnwepfmot.html

Lua ............ 10
来源：http://dali.pengpengdd.cyou/Article/details/gtzobyqkzp.html

Perl ........... 10
来源：http://dali.jiagoushi.top/Article/details/gtushcayew.html

Scala .......... 10
来源：http://dali.birdmap.top/Article/details/gtyqomtuyn.html

------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gtookycczp.html

合计 ........... 2106 条
来源：http://dali.guannengcc.top/Article/details/gtglqhboyz.html

按章节统计：
来源：http://dali.chenjidiqi.icu/Article/details/gtndpswyqz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yvedp.cn/Article/details/gtvreiboes.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gtqurobvig.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ppjwa.cn/Article/details/gtodtloogc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jiagoushi.top/Article/details/gtuejhvekq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.birdmap.top/Article/details/gtrhljvtmf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jianghu66.top/Article/details/gtpoebrnef.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gtxodbayjv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.chenlongwang.top/Article/details/gtqhjxctku.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gtgcdueahq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shangyingyoupin.top/Article/details/gtrecgbyfy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gtmknytqdj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmzzspums.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gtlolupzby.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.guannengcc.top/Article/details/gtdkwhvwdi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.meibo888.top/Article/details/gtsdukrqhp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gteownyjmz.html

Q SQL 专题                              90
来源：http://dali.gzhubu.top/Article/details/gtpordbncj.html

R Bash 专题                             80
来源：http://dali.c1oappe.top/Article/details/gthlvtwwyp.html

S C / C++ 专题                          60
来源：http://dali.yonumen.top/Article/details/gtlwmejjxn.html

T 其他语言补充                          60
来源：http://dali.hysaishi.cn/Article/details/gtrkuqectr.html

U 高频实用片段                         120
来源：http://dali.zhixingplan.top/Article/details/gthxmqpbwu.html

------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtdtstlqwq.html

合计                                  2106 条
来源：http://dali.birdmap.top/Article/details/gtnpzwhmsz.html

--------------------------------------------------------------------------------
来源：http://dali.fengsongda.top/Article/details/gtkmtqwsgi.html

使用提醒
来源：http://dali.cashguo.top/Article/details/gtbseoaomx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gtretwkxfa.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jiagoushi.top/Article/details/gtxcengzrk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.sysykeji.top/Article/details/gthowtsbmu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xuetiantiany.cn/Article/details/gtschnzeaz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xylfe.cn/Article/details/gtrfmhzvnt.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hnxiangtu.top/Article/details/gtyrzqmzfr.html

—— 文件结束 ——
来源：http://dali.cqqwz.cn/Article/details/gtjxokhkzl.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtpngfgcmp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.havefunace.top/Article/details/gtpomxdxhi.html

Common Programming Examples Cheat Book
来源：http://dali.zhongyouzk.top/Article/details/gteschnstm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtdorbkhlp.html

【收录内容】
来源：http://dali.jinqigufen.top/Article/details/gtoirnrmpx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cdnleiting.top/Article/details/gtbrzluslw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jiagoushi.top/Article/details/gtgxqemoml.html

SQL · Bash · C · C++
来源：http://dali.yanxiufei.cn/Article/details/gtibqlalzh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.sweek.top/Article/details/gtpfqgayfd.html

【使用说明】
来源：http://dali.cdnleiting.top/Article/details/gtzjnezmec.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.mhx1999.top/Article/details/gtaqsqrcup.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jiagoushi.top/Article/details/gtklompykb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gtufgauzes.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.nwbrower.top/Article/details/gtjvhzdzsx.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jyoumei.cn/Article/details/gtdjilkpfy.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yvedp.cn/Article/details/gtgtzpifao.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jianghu66.top/Article/details/gtzagbksha.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.sweek.top/Article/details/gtroclrhej.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.aizwys.cn/Article/details/gtwlfwowwn.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ybcxt.top/Article/details/gtnjwlogwp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yj202588.top/Article/details/gtckbjaffs.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.gaohongyu789.top/Article/details/gtvekqhmwq.html

【文件统计】
来源：http://dali.jinqigfzy.top/Article/details/gttcqrgagw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.kuanghao11.cn/Article/details/gtcirgaoxx.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtffrqqenx.html

目  录
来源：http://dali.ivvv.top/Article/details/gtjplqyawn.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258.top/Article/details/gtasoidghw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hywenlv.cn/Article/details/gtkqtqlanl.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.gaohongyu789.top/Article/details/gtokwukvej.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.ehwqpu.com/Article/details/gtxqlhuzhz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtoglrkgvs.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yj20258.top/Article/details/gtxyivdrif.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.c1oappe.top/Article/details/gtqrccbctt.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cqqwz.cn/Article/details/gtqcjpfzhx.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.fengsongda.top/Article/details/gtkgntvsop.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gtazdjyzlp.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jyoumei.cn/Article/details/gtkcewkyca.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ybcxt.top/Article/details/gtjmcqivuc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xylfe.cn/Article/details/gtgblpazrg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gtnfcnkqfy.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.nanxinkj.top/Article/details/gtkczcrhhj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtkddjpqbt.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gttfialurk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.dianchejie.cn/Article/details/gtepgwwhli.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.shzxlz.cn/Article/details/gtqoqxjohy.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwkatxiff.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hysaishi.cn/Article/details/gtmvwuyivj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jyoumei.cn/Article/details/gtqegtlcak.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtmmafkylj.html

A. 基础语法与类型
来源：http://dali.tanke756.top/Article/details/gtruonbjwh.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtxtwjehnk.html

[A01] Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtaukljmuz.html

Py:   print("Hello, World!")
来源：http://dali.yj20258888.top/Article/details/gtfftcvcxy.html

PHP:  echo "Hello, World!";
来源：http://dali.wangshuangyany.cn/Article/details/gttqosgisu.html

JS:   console.log("Hello, World!");
来源：http://dali.pengpengdd.cyou/Article/details/gtszosksvo.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.dianchejie.cn/Article/details/gtquocclrq.html

Java: System.out.println("Hello, World!");
来源：http://dali.ivvv.top/Article/details/gtodjjlqof.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.wangshuangyany.cn/Article/details/gtzcdzxuzc.html

Ruby: puts "Hello, World!"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngbogqxz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.kuanghao11.cn/Article/details/gtesfzcrca.html

[A02] 变量声明与赋值
来源：http://dali.dianchejie.cn/Article/details/gtmqctqgtw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.tianlin.xyz/Article/details/gtfkdfvkuy.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvjpkwbg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hywenlv.cn/Article/details/gtbnmcygeb.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cdnleiting.top/Article/details/gtxtqlxnob.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.redwolf501.top/Article/details/gtrwssyoem.html

Go:   name := "Alex"; age := 20
来源：http://dali.xuanzx.com/Article/details/gtydfqdllk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.aibaodan.cn/Article/details/gtyjgdkzps.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.sufxvd.cn/Article/details/gtkycjwfck.html

[A03] 常量定义
来源：http://dali.cqqwz.cn/Article/details/gtiejvlrha.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.gotoacloud.top/Article/details/gtflqjheve.html

PHP:  const PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwngoeqd.html

JS:   const PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gttodtatox.html

TS:   const PI: number = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtzvficynj.html

Java: static final double PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtbvunvwfm.html

Go:   const PI = 3.14159
来源：http://dali.zhixingplan.top/Article/details/gtvqollovz.html

Ruby: PI = 3.14159
来源：http://dali.yonumen.top/Article/details/gtjsxipdkm.html

C#:   const double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtqermkpmi.html

[A04] 判断变量类型
来源：http://dali.svipenyu.cn/Article/details/gtlpnxensv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.kuanghao11.cn/Article/details/gttvztafkw.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yj202588.top/Article/details/gtyxmxkavz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hnqzz.top/Article/details/gtbiwacuho.html

TS:   typeof x; x instanceof Date
来源：http://dali.cheryme.top/Article/details/gtgiczvnem.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.andypj.xyz/Article/details/gttjfdstjf.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gtsmzdwcht.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.snrcjt.cn/Article/details/gtwmbdomwf.html

C#:   x.GetType().Name; x is int
来源：http://dali.mhx1999.top/Article/details/gttwzqpxpi.html

[A05] 整数除法与取模
来源：http://dali.c1oappe.top/Article/details/gtvbhfymtd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xziqi.cn/Article/details/gtsvpzvbkg.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.gogol.net.cn/Article/details/gthgxpywvt.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gzhubu.top/Article/details/gtwyrfdkfr.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xylfe.cn/Article/details/gtsuwbbysv.html

Java: 7 / 2; 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gtgcrhfphz.html

Go:   7 / 2; 7 % 2
来源：http://dali.dashuyun.cn/Article/details/gtqxujznxx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yj20258888.top/Article/details/gtkmslootr.html

C#:   7 / 2; 7 % 2
来源：http://dali.c1oappe.top/Article/details/gtraazsjdl.html

[A06] 字符串转数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlulfmiqc.html

Py:   int("42"); float("3.14")
来源：http://dali.guowangkeji.top/Article/details/gtvpzszkaq.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.ehwqpu.com/Article/details/gtqdgrnkdb.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.9152youxi.cn/Article/details/gtmqyuzajz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.xuanzx.com/Article/details/gtfiotbwwo.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.aibaodan.cn/Article/details/gtaihjhaea.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.vqdsnc.cn/Article/details/gtkvedvcnu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.shangyingyoupin.top/Article/details/gtanjxewui.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yongpay.top/Article/details/gtxnfcxklc.html

[A07] 数字转字符串
来源：http://dali.snrcjt.cn/Article/details/gtzqzokofq.html

Py:   str(42)
来源：http://dali.zhoulong.xyz/Article/details/gtlvbxpkxv.html

PHP:  (string) 42; strval(42)
来源：http://dali.jqgfzy.top/Article/details/gtkbtwoudj.html

JS:   String(42); (42).toString()
来源：http://dali.nwbrower.top/Article/details/gtkhjzyokl.html

TS:   String(42)
来源：http://dali.shzxlz.cn/Article/details/gtrsdpcqdv.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpyjagmv.html

Go:   strconv.Itoa(42)
来源：http://dali.fengsongda.top/Article/details/gtgrqebgmt.html

Ruby: 42.to_s
来源：http://dali.ivvv.top/Article/details/gtlawfvxkp.html

C#:   42.ToString()
来源：http://dali.birdmap.top/Article/details/gtiwdctxwz.html

[A08] 取整与四舍五入
来源：http://dali.daxiang520.top/Article/details/gtghxaioov.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhixingplan.top/Article/details/gtzhhxhgke.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.xinyue.icu/Article/details/gtwmdkmeaz.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.shangyingyoupin.top/Article/details/gthddowqkh.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.gzhubu.top/Article/details/gtwheaeuhz.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.daxiang520.top/Article/details/gtvicczpvi.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.cdnleiting.top/Article/details/gtiqeboliy.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.gzhubu.top/Article/details/gtcubvxcua.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.sxryk.cn/Article/details/gtejmdrafv.html

[A09] 绝对值与最大最小值
来源：http://dali.xziqi.cn/Article/details/gthwxkmkiu.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtfeozshci.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gtrvbvtrqg.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtpbqdyevr.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gtyynjsuig.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.fzhhl.top/Article/details/gtxbjxhfds.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhiwuduotai.top/Article/details/gtixbbqpyg.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.ehwqpu.com/Article/details/gtbyzmynzx.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.wangdashe.top/Article/details/gthofoxnki.html

[A10] 生成随机数
来源：http://dali.shuidangran.top/Article/details/gtskbycose.html

Py:   import random; random.randint(1, 100)
来源：http://dali.pengpengdd.cyou/Article/details/gtyrnkczvu.html

PHP:  random_int(1, 100);
来源：http://dali.sufxvd.cn/Article/details/gtfqiaovtv.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhixingplan.top/Article/details/gtycfxtizg.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ydzc1.top/Article/details/gtviiwwstt.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zdqjudy.top/Article/details/gtfjtehqew.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.pycfn.com/Article/details/gtjptmabdk.html

Ruby: rand(1..100)
来源：http://dali.gzhubu.top/Article/details/gthodcfodz.html

C#:   new Random().Next(1, 101)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzvfcgms.html

[A11] 条件表达式（三元）
来源：http://dali.jiagoushi.top/Article/details/gtwodykbhb.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.cqqwz.cn/Article/details/gtkxrwhgzv.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.guannengcc.top/Article/details/gtiwxouamp.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gtxdbickfb.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.tian-w.cn/Article/details/gtxurmykgg.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.nanxinkj.top/Article/details/gtvsvazbhj.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.fengsongda.top/Article/details/gttwvcwlir.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jinqigfzy.top/Article/details/gtnkecpeok.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.ivvv.top/Article/details/gtxzvtdtrr.html

[A12] 字符串插值 / 格式化
来源：http://dali.hywenlv.cn/Article/details/gtfbgedmno.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.hongshengwenyu.top/Article/details/gtyjfhmenu.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.daria6918.cn/Article/details/gtzarrqwlc.html

JS:   `Hello, ${name}!`
来源：http://dali.dianchejie.cn/Article/details/gtsafoputx.html

TS:   `Hello, ${name}!`
来源：http://dali.hongshengwenyu.top/Article/details/gtuqflvhou.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.snrcjt.cn/Article/details/gtobdoqewy.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gtqpudjzki.html

Ruby: "Hello, #{name}!"
来源：http://dali.shangyingyoupin.top/Article/details/gtzcciydch.html

C#:   $"Hello, {name}!"
来源：http://dali.sweek.top/Article/details/gtrfglqbii.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.daria6918.cn/Article/details/gtiykonwpr.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gtontwmgsc.html

PHP:  "第一行\n第二行"
来源：http://dali.ppjwa.cn/Article/details/gtkjrfyzdf.html

JS:   "第一行\n第二行"
来源：http://dali.sysykeji.top/Article/details/gtncjnvfwi.html

TS:   "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gtxgtifjbq.html

Java: "第一行\n第二行"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqqchpwv.html

Go:   "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gtevovszqa.html

Ruby: "第一行\n第二行"
来源：http://dali.fzhhl.top/Article/details/gtwgaubmcp.html

C#:   "第一行\n第二行"
来源：http://dali.zhiwuduotai.top/Article/details/gtapssdvyi.html

[A14] 注释写法
来源：http://dali.yj20258.top/Article/details/gtrxjslxba.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.guowangkeji.top/Article/details/gtpnuboolb.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yanxiufei.cn/Article/details/gtxnjkiknh.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjlziuef.html

TS:   // 单行；/* 多行 */
来源：http://dali.jinghuilouyu.cn/Article/details/gtotldafiv.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjanzpyxr.html

Go:   // 单行；/* 多行 */
来源：http://dali.sysykeji.top/Article/details/gtlcxbfxlt.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jinqigufen.top/Article/details/gtwqgbkdll.html

C#:   // 单行；/* 多行 */
来源：http://dali.9152youxi.cn/Article/details/gtgnkonkna.html

[A15] 空值判断与默认值
来源：http://dali.zdqjudy.top/Article/details/gtwdkkhubt.html

Py:   value = data or "默认值"
来源：http://dali.cheryme.top/Article/details/gtkktqszvt.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.nanxuanxn.top/Article/details/gtzrkyrexs.html

JS:   const value = data ?? "默认值";
来源：http://dali.gogol.net.cn/Article/details/gtetagjpsl.html

TS:   const value = data ?? "默认值";
来源：http://dali.yj20258.top/Article/details/gtpdcipxia.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zycfv.cn/Article/details/gtuitcchak.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.hysaishi.cn/Article/details/gttjzagvfr.html


<!-- 参考信息 -->