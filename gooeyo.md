代发 wailian999

[U95] JS：Promise 包装
来源：http://dali.svipenyu.cn/Article/details/gtvdwsuayk.html

new Promise((resolve, reject) => {})
来源：http://dali.iojbl.cn/Article/details/gtcxuysgsh.html

[U96] JS：async/await 与异常
来源：http://dali.zdqjudy.top/Article/details/gtzlklzdwy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtjbcbarzc.html

[U97] JS：并发请求
来源：http://dali.ppjwa.cn/Article/details/gtlhzgqawh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gtwlkakvqa.html

[U98] JS：fetch 带 JSON
来源：http://dali.hnxiangtu.top/Article/details/gtbvbjkgcg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrjyvunda.html

[U99] JS：事件监听
来源：http://dali.havefunace.top/Article/details/gtigqxhouf.html

el.addEventListener("click", e => {})
来源：http://dali.daxiang520.top/Article/details/gtcbtsincb.html

[U100] JS：DOM 查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtprwsksea.html

document.querySelector(".item")
来源：http://dali.yj20258888.top/Article/details/gtieqlrgok.html

[U101] JS：classList 操作
来源：http://dali.hnxiangtu.top/Article/details/gtxkkfqexp.html

el.classList.toggle("active")
来源：http://dali.yvedp.cn/Article/details/gtnjlcunoj.html

[U102] JS：本地存储
来源：http://dali.yuanzhike.top/Article/details/gtmdwnpsjs.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jyoumei.cn/Article/details/gtnytieaoi.html

[U103] JS：定时器
来源：http://dali.nwbrower.top/Article/details/gtwslpzpsr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xuetiantiany.cn/Article/details/gtjpgdplmb.html

[U104] JS：防抖
来源：http://dali.birdmap.top/Article/details/gtvjzazacb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gtqgsnywai.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gtgtrvynmx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnczanfb.html

[U106] JS：日期格式化
来源：http://dali.andypj.xyz/Article/details/gtstdfpqrh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cashguo.top/Article/details/gtbbnxcwtj.html

[U107] JS：数字千分位
来源：http://dali.hywenlv.cn/Article/details/gtzhtjgdxh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.316326.xyz/Article/details/gtvwpmsyln.html

[U108] JS：随机整数
来源：http://dali.zhengqikj.top/Article/details/gtpuhkeptg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.pycfn.com/Article/details/gteeicbwvr.html

[U109] JS：数组分组
来源：http://dali.shangyingyoupin.top/Article/details/gtevsvyauy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthpucliom.html

[U110] JS：数组分块
来源：http://dali.jinqigfzy.top/Article/details/gtptrkykhd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cqqwz.cn/Article/details/gtkmpnbodh.html

[U111] JS：对象转 Map
来源：http://dali.ydzc1.top/Article/details/gtyemqmdyk.html

new Map(Object.entries(obj))
来源：http://dali.daxiang520.top/Article/details/gtmlkwxlsd.html

[U112] JS：字符串补位
来源：http://dali.chenlongwang.top/Article/details/gtnpvminsq.html

"7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonmgfsfv.html

[U113] JS：正则替换全部
来源：http://dali.daria6918.cn/Article/details/gtvdtgqjxu.html

s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtqypcdtpu.html

[U114] JS：JSON 深比较
来源：http://dali.hnqzz.top/Article/details/gtbjgcgqjj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.c1oappe.top/Article/details/gtmncodkzl.html

[U115] JS：生成 UUID
来源：http://dali.hammf.cn/Article/details/gtysyxomui.html

crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gteiwbtjpf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.havefunace.top/Article/details/gtsqdinphu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.sweek.top/Article/details/gthzegxyij.html

[U117] JS：单元测试
来源：http://dali.jianghu66.top/Article/details/gtxnmhxdon.html

npm i -D vitest;  npx vitest
来源：http://dali.guowangkeji.top/Article/details/gtaplnpevb.html

[U118] JS：开发服务器
来源：http://dali.shuidangran.top/Article/details/gtnvzornwe.html

npm i -D vite;  npx vite
来源：http://dali.yvedp.cn/Article/details/gtwjcbqgyl.html

[U119] JS：生产构建
来源：http://dali.meibo888.top/Article/details/gtasfrelqz.html

npx vite build
来源：http://dali.wangdashe.top/Article/details/gttgvvkvso.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.redwolf501.top/Article/details/gtmjwfxidx.html

import.meta.env.VITE_API_URL
来源：http://dali.mhx1999.top/Article/details/gtyugkcfdz.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtuprtkxpj.html

统计汇总
来源：http://dali.chenlongwang.top/Article/details/gtfgowracz.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtutmizncw.html

按语言统计（条）：
来源：http://dali.jqgufenzy.top/Article/details/gtyfhfrdwv.html

Python ......... 252
来源：http://dali.hysaishi.cn/Article/details/gtaqbiinyd.html

PHP ............ 252
来源：http://dali.c1oappe.top/Article/details/gtmnepsdry.html

JavaScript ..... 252
来源：http://dali.ydzc1.top/Article/details/gtpnstgkko.html

TypeScript ..... 212
来源：http://dali.nanxinkj.top/Article/details/gtzpngzpgn.html

Java ........... 212
来源：http://dali.cucudq.cn/Article/details/gtytmcmldi.html

Go ............. 212
来源：http://dali.feifeiyinyue.top/Article/details/gtbqdxhncn.html

Ruby ........... 212
来源：http://dali.mhx1999.top/Article/details/gtbpszfxuv.html

C# ............. 212
来源：http://dali.jinqigufen.top/Article/details/gtflbezsst.html

C .............. 30
来源：http://dali.shanyushiyangtech.top/Article/details/gtvhjiowlk.html

C++ ............ 30
来源：http://dali.zhongyouzk.top/Article/details/gtkjfrcors.html

SQL ............ 90
来源：http://dali.zycfv.cn/Article/details/gtxleoyndk.html

Bash ........... 80
来源：http://dali.zhixingplan.top/Article/details/gttnaerxam.html

Kotlin ......... 15
来源：http://dali.zhixingplan.top/Article/details/gtubbbhkpa.html

Swift .......... 15
来源：http://dali.ehwqpu.com/Article/details/gtrabugcct.html

Lua ............ 10
来源：http://dali.zhixingplan.top/Article/details/gtanseozak.html

Perl ........... 10
来源：http://dali.wangdashe.top/Article/details/gtpviejyvo.html

Scala .......... 10
来源：http://dali.hywenlv.cn/Article/details/gtujmprrbr.html

------------------------------------
来源：http://dali.hammf.cn/Article/details/gtaeuqgmsr.html

合计 ........... 2106 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxwjyodj.html

按章节统计：
来源：http://dali.tianlin.xyz/Article/details/gtwtszytbe.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.quarkkingdee.top/Article/details/gtidqpexqs.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gaohongyu789.top/Article/details/gteoozsifz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.dianchejie.cn/Article/details/gtrubutyrx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gaohongyu789.top/Article/details/gtceavdcqk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jinqigfzy.top/Article/details/gtqsebruum.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zycfv.cn/Article/details/gtsgmvrhno.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.fzhhl.top/Article/details/gtcovmtgav.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.tanke756.top/Article/details/gtnlxrahxl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gtdkfkdvrj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gzhubu.top/Article/details/gtkcehpjdn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gteplczkcr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gtncpnyyxj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gteovvyymm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yanxiufei.cn/Article/details/gtdhbpnotb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.gaohongyu789.top/Article/details/gtirqmkmzf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gtsuewrgcx.html

Q SQL 专题                              90
来源：http://dali.chenlongwang.top/Article/details/gtwumdgfzq.html

R Bash 专题                             80
来源：http://dali.gaohongyu789.top/Article/details/gtlckivfls.html

S C / C++ 专题                          60
来源：http://dali.xziqi.cn/Article/details/gtzeswrpzi.html

T 其他语言补充                          60
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbozkejl.html

U 高频实用片段                         120
来源：http://dali.ybcxt.top/Article/details/gtbhpasjpv.html

------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gtldpqhykj.html

合计                                  2106 条
来源：http://dali.jqgfzy.top/Article/details/gtksadehax.html

--------------------------------------------------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gtjzxyqbcc.html

使用提醒
来源：http://dali.zhoulong.xyz/Article/details/gtsmgnqvkz.html

--------------------------------------------------------------------------------
来源：http://dali.xylfe.cn/Article/details/gteaioqqop.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.smart0.xyz/Article/details/gtoprzvmsd.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yangfankeji.com/Article/details/gtgarclpep.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.fengsongda.top/Article/details/gtvgzowizf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xinyue.icu/Article/details/gtnxubtoqz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.kuanghao11.cn/Article/details/gteaxxqkwc.html

—— 文件结束 ——
来源：http://dali.shangyingyoupin.top/Article/details/gtxqcjvkpk.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtfmyybilz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zycfv.cn/Article/details/gtfrvngssy.html

Common Programming Examples Cheat Book
来源：http://dali.0kj1m.cn/Article/details/gtjcsuhejh.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtqwslocyw.html

【收录内容】
来源：http://dali.guannengcc.top/Article/details/gtrrtolajv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zycfv.cn/Article/details/gtrnqdqjim.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hongshengwenyu.top/Article/details/gtcymclynj.html

SQL · Bash · C · C++
来源：http://dali.hfpthk.cn/Article/details/gtntwxahtp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.aizwys.cn/Article/details/gtnvtktloa.html

【使用说明】
来源：http://dali.tanke756.top/Article/details/gtgdagnutg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.guannengcc.top/Article/details/gtkvvgtovo.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.guowangkeji.top/Article/details/gtytrdodyp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.cheryme.top/Article/details/gtqobekupq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.feifeiyinyue.top/Article/details/gtjkxbmazv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hnqzz.top/Article/details/gtaxpbnwpm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.shangyingyoupin.top/Article/details/gtfesqvrsh.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.snrcjt.cn/Article/details/gtwkknsrws.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.chenjidiqi.icu/Article/details/gtxmhxipfj.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zdqjudy.top/Article/details/gtelcnmayu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmsetqxj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.shangyingyoupin.top/Article/details/gtsuqphjqi.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jyoumei.cn/Article/details/gtopvydlpi.html

【文件统计】
来源：http://dali.havefunace.top/Article/details/gtqdgnmmnv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yueranfly.top/Article/details/gtajgfufte.html

--------------------------------------------------------------------------------
来源：http://dali.xylfe.cn/Article/details/gtfipgovva.html

目  录
来源：http://dali.yueranfly.top/Article/details/gtwdurpazm.html

--------------------------------------------------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gtqbcqkoqp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.c1oappe.top/Article/details/gtfcsqmaqc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.bjfxy.top/Article/details/gtszhmdltk.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.sufxvd.cn/Article/details/gtbcczskwo.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtsyucdinf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldbhbqhh.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yangfankeji.com/Article/details/gtujxglugp.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jqgfzy.top/Article/details/gtxnvwhusy.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.0kj1m.cn/Article/details/gtfjpturrs.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zycfv.cn/Article/details/gtcksuqeoa.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.gzhubu.top/Article/details/gtxatkpwbd.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gtctpkgdbd.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtishevmul.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.dashuyun.cn/Article/details/gtrwddpaky.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yongpay.top/Article/details/gtfrwojmvl.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhixingplan.top/Article/details/gtmsvislyw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gtwrbmdqfq.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.mhx1999.top/Article/details/gtasbiaqrb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.guannengcc.top/Article/details/gtvmaqzeoe.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yanxiufei.cn/Article/details/gtwvuzmglt.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hfpthk.cn/Article/details/gtxgycznsr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jianghu66.top/Article/details/gtaoemxnad.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtastafopg.html

A. 基础语法与类型
来源：http://dali.yj202588.top/Article/details/gtfracheww.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtkaxcdgqn.html

[A01] Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgffrirzu.html

Py:   print("Hello, World!")
来源：http://dali.feifeiyinyue.top/Article/details/gtwddhniop.html

PHP:  echo "Hello, World!";
来源：http://dali.kuanghao11.cn/Article/details/gtjimxmlol.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gtfbmzgaon.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.kuanghao11.cn/Article/details/gtzyojolbz.html

Java: System.out.println("Hello, World!");
来源：http://dali.316326.xyz/Article/details/gtxhozgesd.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcbmwfhk.html

Ruby: puts "Hello, World!"
来源：http://dali.cheryme.top/Article/details/gtodvdclqg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.redwolf501.top/Article/details/gtnsfjxknx.html

[A02] 变量声明与赋值
来源：http://dali.yuxming.cn/Article/details/gtsneblpqm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ydzc1.top/Article/details/gtoklsohru.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jiagoushi.top/Article/details/gtsljmvhsu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hammf.cn/Article/details/gtfzvbzazu.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.havefunace.top/Article/details/gtkocyypks.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.tanke756.top/Article/details/gtkjwhduno.html

Go:   name := "Alex"; age := 20
来源：http://dali.sweek.top/Article/details/gtzhwpuoth.html

Ruby: name = "Alex"; age = 20
来源：http://dali.sufxvd.cn/Article/details/gtsigwizpn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yanxiufei.cn/Article/details/gtdwkcsvrx.html

[A03] 常量定义
来源：http://dali.zdqjudy.top/Article/details/gtqplaputc.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.smart0.xyz/Article/details/gtxmmtfqoc.html

PHP:  const PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gthnsmissx.html

JS:   const PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtclsvegwj.html

TS:   const PI: number = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtolgfklvx.html

Java: static final double PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtbzijoeti.html

Go:   const PI = 3.14159
来源：http://dali.jqgufenzy.top/Article/details/gttgfddmlt.html

Ruby: PI = 3.14159
来源：http://dali.jqgfzy.top/Article/details/gtcywprmdl.html

C#:   const double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gttagomzky.html

[A04] 判断变量类型
来源：http://dali.jianghu66.top/Article/details/gteutogakh.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhiwuduotai.top/Article/details/gtfurerass.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yvedp.cn/Article/details/gtlhnvwwmt.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.bjfxy.top/Article/details/gtpeacakoz.html

TS:   typeof x; x instanceof Date
来源：http://dali.hongshengwenyu.top/Article/details/gtutgftxbm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhongyouzk.top/Article/details/gtvnfmapqq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.fengsongda.top/Article/details/gtjczjrbnr.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.gotoacloud.top/Article/details/gtiqnrlrmv.html

C#:   x.GetType().Name; x is int
来源：http://dali.mhx1999.top/Article/details/gtolkeesnb.html

[A05] 整数除法与取模
来源：http://dali.jiagoushi.top/Article/details/gtlzztyaan.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yuxming.cn/Article/details/gtfomiclkk.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtqbtdosnw.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gthlqnrkfq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcbekejo.html

Java: 7 / 2; 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gtzaianugm.html

Go:   7 / 2; 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gtmcqssefe.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtxsfmpjsh.html

C#:   7 / 2; 7 % 2
来源：http://dali.yj20258888.top/Article/details/gtlrfacdtp.html

[A06] 字符串转数字
来源：http://dali.shanyushiyangtech.top/Article/details/gtcnwmxqbm.html

Py:   int("42"); float("3.14")
来源：http://dali.zdqjudy.top/Article/details/gthsrcfwqk.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.ydzc1.top/Article/details/gtjvrcljcl.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.wangdashe.top/Article/details/gtegnxziwu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.xuanzx.com/Article/details/gthvhhccwo.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.hfpthk.cn/Article/details/gtmkyualgs.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ivvv.top/Article/details/gtwzjjwezq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.feifeiyinyue.top/Article/details/gtqqnirtcu.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.feifeiyinyue.top/Article/details/gtiadzvrzy.html

[A07] 数字转字符串
来源：http://dali.zdqjudy.top/Article/details/gtzdiyxptp.html

Py:   str(42)
来源：http://dali.shuidangran.top/Article/details/gtslxircsg.html

PHP:  (string) 42; strval(42)
来源：http://dali.chenzaomai.com/Article/details/gtmwilgwdx.html

JS:   String(42); (42).toString()
来源：http://dali.chenzaomai.com/Article/details/gtdcqzfywp.html

TS:   String(42)
来源：http://dali.ppjwa.cn/Article/details/gtwgufudko.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.xinyue.icu/Article/details/gtbssxkzkp.html

Go:   strconv.Itoa(42)
来源：http://dali.xuetiantiany.cn/Article/details/gtxnhasxxa.html

Ruby: 42.to_s
来源：http://dali.dianchejie.cn/Article/details/gtitezybjy.html

C#:   42.ToString()
来源：http://dali.sxryk.cn/Article/details/gtvixxhfxo.html

[A08] 取整与四舍五入
来源：http://dali.jinqigufen.top/Article/details/gtvgspyrop.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.xylfe.cn/Article/details/gtvflhenwu.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.birdmap.top/Article/details/gtkhbezqlr.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhengqikj.top/Article/details/gtlqeidqfx.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.ivvv.top/Article/details/gtyygofwpb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.guannengcc.top/Article/details/gtewqxrvcf.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.pengpengdd.cyou/Article/details/gtroyqetwx.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.quarkkingdee.top/Article/details/gtqrufipbf.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yuanzhike.top/Article/details/gthjfaspxn.html

[A09] 绝对值与最大最小值
来源：http://dali.pycfn.com/Article/details/gtacnffggt.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xuanzx.com/Article/details/gtoqjskrut.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtzxukhnhy.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwhyvjru.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gttjsbawcq.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtdrucrgcm.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zdqjudy.top/Article/details/gtqozmheho.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.pengpengdd.cyou/Article/details/gtlsmlvqux.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yj202588.top/Article/details/gtbjesctkg.html

[A10] 生成随机数
来源：http://dali.zhiwuduotai.top/Article/details/gtyytjktcb.html

Py:   import random; random.randint(1, 100)
来源：http://dali.bjfxy.top/Article/details/gtkuwtkcfu.html

PHP:  random_int(1, 100);
来源：http://dali.jqgufenzy.top/Article/details/gtyhqgfuyf.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sufxvd.cn/Article/details/gtemdpkqev.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.havefunace.top/Article/details/gtntycgphu.html

Java: new Random().nextInt(100) + 1
来源：http://dali.kuanghao11.cn/Article/details/gtpjoljxjv.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hongshengwenyu.top/Article/details/gtjbyegrme.html

Ruby: rand(1..100)
来源：http://dali.sufxvd.cn/Article/details/gtlquukvqp.html

C#:   new Random().Next(1, 101)
来源：http://dali.sysykeji.top/Article/details/gtqskcdfki.html

[A11] 条件表达式（三元）
来源：http://dali.haohaochexian.top/Article/details/gtxzmyqmuj.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.daria6918.cn/Article/details/gtplttelcl.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.smart0.xyz/Article/details/gtizzildpq.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.nwbrower.top/Article/details/gtsbgynzap.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.shangyingyoupin.top/Article/details/gtvdpspytt.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.ybcxt.top/Article/details/gtjwptxkov.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.xylfe.cn/Article/details/gtbakynlrg.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yj202588.top/Article/details/gtnnepuyth.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.xuanzx.com/Article/details/gtbwrtfvxt.html

[A12] 字符串插值 / 格式化
来源：http://dali.hnqzz.top/Article/details/gtjkzildnv.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jqgfzy.top/Article/details/gtvsospwpz.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.xinyue.icu/Article/details/gtppyvhwpz.html

JS:   `Hello, ${name}!`
来源：http://dali.wangdashe.top/Article/details/gtzdsutkic.html

TS:   `Hello, ${name}!`
来源：http://dali.shangyingyoupin.top/Article/details/gtonjyzugn.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xuanzx.com/Article/details/gttcirmees.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.daria6918.cn/Article/details/gtdzdlynux.html

Ruby: "Hello, #{name}!"
来源：http://dali.316326.xyz/Article/details/gtkgbibtao.html

C#:   $"Hello, {name}!"
来源：http://dali.sufxvd.cn/Article/details/gtqvucvstl.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.hfpthk.cn/Article/details/gtuvpkkknv.html

Py:   "第一行\n第二行"
来源：http://dali.xylfe.cn/Article/details/gtoxdrouiy.html

PHP:  "第一行\n第二行"
来源：http://dali.zhongyouzk.top/Article/details/gtfkygpuih.html

JS:   "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gtdofnfmif.html

TS:   "第一行\n第二行"
来源：http://dali.zhiwuduotai.top/Article/details/gtqdesqcbr.html

Java: "第一行\n第二行"
来源：http://dali.xinyue.icu/Article/details/gtxgnruexa.html

Go:   "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gtgcgpfmkq.html

Ruby: "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gtcsnkggyj.html

C#:   "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gtbvxngdtc.html

[A14] 注释写法
来源：http://dali.svipenyu.cn/Article/details/gtvvbhjter.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.0kj1m.cn/Article/details/gtegirmzxd.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.guowangkeji.top/Article/details/gtfwbjzyqo.html

JS:   // 单行；/* 多行 */
来源：http://dali.ppjwa.cn/Article/details/gtrucprgkz.html

TS:   // 单行；/* 多行 */
来源：http://dali.jinqigufen.top/Article/details/gtcoqhoxov.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.guowangkeji.top/Article/details/gtgjyjzvue.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhiwuduotai.top/Article/details/gtnpamsezp.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.nanxuanxn.top/Article/details/gtygempkss.html

C#:   // 单行；/* 多行 */
来源：http://dali.tanke756.top/Article/details/gtxrjikohg.html

[A15] 空值判断与默认值
来源：http://dali.tian-w.cn/Article/details/gttlpxtxbp.html

Py:   value = data or "默认值"
来源：http://dali.c1oappe.top/Article/details/gtuxxqwpyz.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.iojbl.cn/Article/details/gtocpyyweg.html

JS:   const value = data ?? "默认值";
来源：http://dali.fzhhl.top/Article/details/gtgqaapptl.html

TS:   const value = data ?? "默认值";
来源：http://dali.sufxvd.cn/Article/details/gtwzohlyam.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.hfpthk.cn/Article/details/gthztimdiu.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.smart0.xyz/Article/details/gtkowzkqvo.html

Ruby: value = data || "默认值"
来源：http://dali.ehwqpu.com/Article/details/gtumyfmeug.html

C#:   var value = data ?? "默认值";
来源：http://dali.nanxuanxn.top/Article/details/gtwixwpyco.html

[A16] 真假值判断规则
来源：http://dali.fengsongda.top/Article/details/gtvlfxidnv.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.xylfe.cn/Article/details/gtdvsglbar.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xziqi.cn/Article/details/gtfhvrqgwp.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.gogol.net.cn/Article/details/gtzucjknzb.html

TS:   if (!x) {}
来源：http://dali.sysykeji.top/Article/details/gtuvbfnopx.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yuxming.cn/Article/details/gtvxqoerfl.html


<!-- 参考信息 -->