代发 wailian999

[U89] JS：数组去重
来源：http://dali.meibo888.top/Article/details/gtivqaayzs.html

[...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gtgfzcuqnd.html

[U90] JS：数字数组排序
来源：http://dali.birdmap.top/Article/details/gtmtxzrera.html

[...arr].sort((a, b) => a - b)
来源：http://dali.svipenyu.cn/Article/details/gtwieywmwb.html

[U91] JS：对象键值遍历
来源：http://dali.guowangkeji.top/Article/details/gtooenjfbu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zycfv.cn/Article/details/gtuiadqicl.html

[U92] JS：深拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gthopubmwb.html

structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gtpasxogpc.html

[U93] JS：模板字符串
来源：http://dali.xuanzx.com/Article/details/gtqymaggoc.html

`共 ${n} 条`
来源：http://dali.316326.xyz/Article/details/gttgmugxqu.html

[U94] JS：箭头函数
来源：http://dali.jqgufenzy.top/Article/details/gtnsmongjx.html

const double = x => x * 2;
来源：http://dali.quarkkingdee.top/Article/details/gtzmagmczy.html

[U95] JS：Promise 包装
来源：http://dali.svipenyu.cn/Article/details/gtxvgdazuj.html

new Promise((resolve, reject) => {})
来源：http://dali.yj202588.top/Article/details/gtdclpoaec.html

[U96] JS：async/await 与异常
来源：http://dali.havefunace.top/Article/details/gtgycmjaxs.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gtsomsyulh.html

[U97] JS：并发请求
来源：http://dali.0kj1m.cn/Article/details/gtvhsvzgha.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtbvetnqcq.html

[U98] JS：fetch 带 JSON
来源：http://dali.andypj.xyz/Article/details/gtnjdusoco.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.chenlongwang.top/Article/details/gtjjqprjzy.html

[U99] JS：事件监听
来源：http://dali.birdmap.top/Article/details/gtpsjlzjxx.html

el.addEventListener("click", e => {})
来源：http://dali.mhx1999.top/Article/details/gtlcidnylz.html

[U100] JS：DOM 查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivespdly.html

document.querySelector(".item")
来源：http://dali.guannengcc.top/Article/details/gtmflwaqly.html

[U101] JS：classList 操作
来源：http://dali.dianchejie.cn/Article/details/gtsopcjycu.html

el.classList.toggle("active")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqrpylof.html

[U102] JS：本地存储
来源：http://dali.hysaishi.cn/Article/details/gtwajptwcr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sysykeji.top/Article/details/gtjflrmcsj.html

[U103] JS：定时器
来源：http://dali.jqgfzy.top/Article/details/gtunuqeoul.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.tian-w.cn/Article/details/gtouqyokdc.html

[U104] JS：防抖
来源：http://dali.yueranfly.top/Article/details/gtofvkubpn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtvlyrbxpt.html

[U105] JS：节流
来源：http://dali.aibaodan.cn/Article/details/gtvacxddfj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yj20258888.top/Article/details/gtirojymwe.html

[U106] JS：日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gtbncjklwg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.chenjidiqi.icu/Article/details/gtuzpculmt.html

[U107] JS：数字千分位
来源：http://dali.tian-w.cn/Article/details/gtwsjzscml.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sxryk.cn/Article/details/gtbqalqasd.html

[U108] JS：随机整数
来源：http://dali.pengpengdd.cyou/Article/details/gtoqgtxspi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.fengsongda.top/Article/details/gtxkefucvt.html

[U109] JS：数组分组
来源：http://dali.zhongyouzk.top/Article/details/gtypcivhzo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.birdmap.top/Article/details/gtalczszio.html

[U110] JS：数组分块
来源：http://dali.daxiang520.top/Article/details/gtloffuxdg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.pycfn.com/Article/details/gtmxmawevn.html

[U111] JS：对象转 Map
来源：http://dali.gaohongyu789.top/Article/details/gtivnmlfim.html

new Map(Object.entries(obj))
来源：http://dali.shanyushiyangtech.top/Article/details/gtmdexmwxe.html

[U112] JS：字符串补位
来源：http://dali.xziqi.cn/Article/details/gtnxeyrnpg.html

"7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gtjkzujhjx.html

[U113] JS：正则替换全部
来源：http://dali.xylfe.cn/Article/details/gtdimugkhm.html

s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtzmqnwniw.html

[U114] JS：JSON 深比较
来源：http://dali.cucudq.cn/Article/details/gtxwvdzesu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.mhx1999.top/Article/details/gtgiakkqdd.html

[U115] JS：生成 UUID
来源：http://dali.shuidangran.top/Article/details/gtaqhoylca.html

crypto.randomUUID()
来源：http://dali.jinqigfzy.top/Article/details/gtzvbtaipz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jianghu66.top/Article/details/gtqiapfsyt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yueranfly.top/Article/details/gtucjdgasr.html

[U117] JS：单元测试
来源：http://dali.jyoumei.cn/Article/details/gtbsgjltav.html

npm i -D vitest;  npx vitest
来源：http://dali.guannengcc.top/Article/details/gtzkfegaio.html

[U118] JS：开发服务器
来源：http://dali.jiagoushi.top/Article/details/gtzdtddtca.html

npm i -D vite;  npx vite
来源：http://dali.nwbrower.top/Article/details/gtgobihegx.html

[U119] JS：生产构建
来源：http://dali.ehwqpu.com/Article/details/gtsfkjqyli.html

npx vite build
来源：http://dali.hammf.cn/Article/details/gtlbqnnkzh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hnxiangtu.top/Article/details/gtabioeslg.html

import.meta.env.VITE_API_URL
来源：http://dali.quarkkingdee.top/Article/details/gtsffjngzu.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtxitqlykl.html

统计汇总
来源：http://dali.yuanzhike.top/Article/details/gtptrghbde.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtfnipwqan.html

按语言统计（条）：
来源：http://dali.hnqzz.top/Article/details/gtjpojdter.html

Python ......... 252
来源：http://dali.meibo888.top/Article/details/gtxmcernnj.html

PHP ............ 252
来源：http://dali.hnxiangtu.top/Article/details/gtayirjwxc.html

JavaScript ..... 252
来源：http://dali.xuetiantiany.cn/Article/details/gtjnyvxwco.html

TypeScript ..... 212
来源：http://dali.zhixingplan.top/Article/details/gtmxtmhhkd.html

Java ........... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyloykdbo.html

Go ............. 212
来源：http://dali.wangdashe.top/Article/details/gtqelpjhpm.html

Ruby ........... 212
来源：http://dali.jyoumei.cn/Article/details/gtlnkwhgwv.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gtmsgxsnka.html

C .............. 30
来源：http://dali.hammf.cn/Article/details/gtiaisdzjj.html

C++ ............ 30
来源：http://dali.jqgfzy.top/Article/details/gtawshqebe.html

SQL ............ 90
来源：http://dali.gzhubu.top/Article/details/gtrpxoqing.html

Bash ........... 80
来源：http://dali.daxiang520.top/Article/details/gtiliysaqj.html

Kotlin ......... 15
来源：http://dali.vqdsnc.cn/Article/details/gtyaztttzb.html

Swift .......... 15
来源：http://dali.hywenlv.cn/Article/details/gtsuuelzod.html

Lua ............ 10
来源：http://dali.kuanghao11.cn/Article/details/gtrwwljyhh.html

Perl ........... 10
来源：http://dali.yuxming.cn/Article/details/gtjihhwnoz.html

Scala .......... 10
来源：http://dali.sufxvd.cn/Article/details/gtnsmvyfne.html

------------------------------------
来源：http://dali.316326.xyz/Article/details/gtfosjnwll.html

合计 ........... 2106 条
来源：http://dali.yj20258888.top/Article/details/gtjxjufwxs.html

按章节统计：
来源：http://dali.guowangkeji.top/Article/details/gteysapfdt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.birdmap.top/Article/details/gtwruhxoot.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yvedp.cn/Article/details/gteghpuvqp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yueranfly.top/Article/details/gtmejhzmku.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.chenlongwang.top/Article/details/gtbnqswnwo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ivvv.top/Article/details/gtctrgzygx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhongyouzk.top/Article/details/gtpjuollup.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.nanxinkj.top/Article/details/gtcjjecnzh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.snrcjt.cn/Article/details/gtssfvttsb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhixingplan.top/Article/details/gtgmbwencf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.316326.xyz/Article/details/gtkbgebmsu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jiagoushi.top/Article/details/gtdkpuzsjc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gtssuubtzw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gtjfvkofsl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hammf.cn/Article/details/gtdydjpwjy.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xylfe.cn/Article/details/gtlhwcimoy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjwnqlpq.html

Q SQL 专题                              90
来源：http://dali.snrcjt.cn/Article/details/gtppaaquwc.html

R Bash 专题                             80
来源：http://dali.tanke756.top/Article/details/gtcidcbxpe.html

S C / C++ 专题                          60
来源：http://dali.sufxvd.cn/Article/details/gtnwncwlmp.html

T 其他语言补充                          60
来源：http://dali.haohaochexian.top/Article/details/gtmwsejexv.html

U 高频实用片段                         120
来源：http://dali.tianlin.xyz/Article/details/gtvdbwkteh.html

------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gtevpetsya.html

合计                                  2106 条
来源：http://dali.316326.xyz/Article/details/gtwhpqcvqv.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gtiivygguc.html

使用提醒
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbcvoxsc.html

--------------------------------------------------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gtzgalpmps.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.tanke756.top/Article/details/gtljsinmoa.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zdqjudy.top/Article/details/gtleocfwlx.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.chenzaomai.com/Article/details/gturdupidg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.guowangkeji.top/Article/details/gtiryjoeca.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.fzhhl.top/Article/details/gttzjmezsu.html

—— 文件结束 ——
来源：http://dali.gzhubu.top/Article/details/gtwdaglzof.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtgnbjfykz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.andypj.xyz/Article/details/gtrepmwrgv.html

Common Programming Examples Cheat Book
来源：http://dali.vqdsnc.cn/Article/details/gtahxvhcnr.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtdlcksdsg.html

【收录内容】
来源：http://dali.zhengqikj.top/Article/details/gtjekrfnmn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.tanke756.top/Article/details/gtzvunqsrv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cqqwz.cn/Article/details/gtwqhtosdd.html

SQL · Bash · C · C++
来源：http://dali.wangshuangyany.cn/Article/details/gtcexkcvgi.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.fzhhl.top/Article/details/gtgacjryvb.html

【使用说明】
来源：http://dali.yj20258888.top/Article/details/gtevfarlzz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.gogol.net.cn/Article/details/gtnkdrrunz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hywenlv.cn/Article/details/gtiiobqfyl.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjyoiztqx.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xylfe.cn/Article/details/gthgykufjv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.smart0.xyz/Article/details/gtojidwgbc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yongpay.top/Article/details/gtwuqlrqpf.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.andypj.xyz/Article/details/gtmscnhxcu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.nwbrower.top/Article/details/gtcplhckxd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.mhx1999.top/Article/details/gtxrnevoaz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hongshengwenyu.top/Article/details/gtbkwgrnzv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.cashguo.top/Article/details/gtewvjdfzo.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobgqooqh.html

【文件统计】
来源：http://dali.yj20258888.top/Article/details/gtwpsoixjp.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtodctloor.html

--------------------------------------------------------------------------------
来源：http://dali.daria6918.cn/Article/details/gtwzkzmfeh.html

目  录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfesxbax.html

--------------------------------------------------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gtbyjutofp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jlsjyb.cn/Article/details/gtujvhkixh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtseaytaix.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hammf.cn/Article/details/gtppthtocp.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhongyouzk.top/Article/details/gtyrhhabpu.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.bjfxy.top/Article/details/gtoulfufnc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hfpthk.cn/Article/details/gtmilcushs.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cashguo.top/Article/details/gtafllcvkv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.bjfxy.top/Article/details/gtawqglldc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gtofcwaheg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.tian-w.cn/Article/details/gtphqgkubx.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.wangdashe.top/Article/details/gtgrmzpbin.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gthjftedpu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.gaohongyu789.top/Article/details/gtnifyceah.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xziqi.cn/Article/details/gtbojpvgkr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yongpay.top/Article/details/gtimymihsi.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gtyilktouq.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtgbbigaez.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yvedp.cn/Article/details/gtewlwitcr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtafmtozba.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.quarkkingdee.top/Article/details/gthnahqouh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangdashe.top/Article/details/gtqkjuxhad.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtqbsczpjx.html

A. 基础语法与类型
来源：http://dali.jianghu66.top/Article/details/gtoxtlqnsp.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtloqvrjyt.html

[A01] Hello World
来源：http://dali.zhixingplan.top/Article/details/gtsjgolbpv.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gtgfqwqmby.html

PHP:  echo "Hello, World!";
来源：http://dali.feifeiyinyue.top/Article/details/gtmgxrbdfp.html

JS:   console.log("Hello, World!");
来源：http://dali.jianghu66.top/Article/details/gtgcsliwqb.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ydzc1.top/Article/details/gtjxmndkxe.html

Java: System.out.println("Hello, World!");
来源：http://dali.guowangkeji.top/Article/details/gthfppldrx.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.shzxlz.cn/Article/details/gtmcqxfomh.html

Ruby: puts "Hello, World!"
来源：http://dali.wangshuangyany.cn/Article/details/gtkdlentcz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.guowangkeji.top/Article/details/gtlbujrtjk.html

[A02] 变量声明与赋值
来源：http://dali.jinqigfzy.top/Article/details/gtclyuccrs.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yuanzhike.top/Article/details/gtnfqyhqbo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ivvv.top/Article/details/gtstryinxk.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.havefunace.top/Article/details/gtgzrexrmo.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gogol.net.cn/Article/details/gtutqiqnrq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylampwgz.html

Go:   name := "Alex"; age := 20
来源：http://dali.guowangkeji.top/Article/details/gtvqexmqrn.html

Ruby: name = "Alex"; age = 20
来源：http://dali.pengpengdd.cyou/Article/details/gtjgzvkcxy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yj202588.top/Article/details/gtaymobhiz.html

[A03] 常量定义
来源：http://dali.yj20258.top/Article/details/gttcocppft.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jyoumei.cn/Article/details/gtkcgeefif.html

PHP:  const PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gtrdckkqum.html

JS:   const PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbsorgvus.html

TS:   const PI: number = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gtifiiouby.html

Java: static final double PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gtsngadqzo.html

Go:   const PI = 3.14159
来源：http://dali.tian-w.cn/Article/details/gtviyrqukv.html

Ruby: PI = 3.14159
来源：http://dali.snrcjt.cn/Article/details/gtwomaizhe.html

C#:   const double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtiomrkczo.html

[A04] 判断变量类型
来源：http://dali.sufxvd.cn/Article/details/gtokiwypxv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.nwbrower.top/Article/details/gtwivyhgwz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hongshengwenyu.top/Article/details/gtjlupwyyj.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yuanzhike.top/Article/details/gtvfoosxtx.html

TS:   typeof x; x instanceof Date
来源：http://dali.hongshengwenyu.top/Article/details/gthaepcsbv.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jlsjyb.cn/Article/details/gtimlbggre.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.smart0.xyz/Article/details/gtqmhjifpr.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jqgfzy.top/Article/details/gtoahvyrxb.html

C#:   x.GetType().Name; x is int
来源：http://dali.shangyingyoupin.top/Article/details/gtrsggjmax.html

[A05] 整数除法与取模
来源：http://dali.shanyushiyangtech.top/Article/details/gtlruxgfmt.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.daxiang520.top/Article/details/gtwvjzfkbp.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.cheryme.top/Article/details/gtyxsovtkv.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.havefunace.top/Article/details/gtotutaffy.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gtelrvaklc.html

Java: 7 / 2; 7 % 2
来源：http://dali.cashguo.top/Article/details/gtxnszylgi.html

Go:   7 / 2; 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gtqrrhczoh.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gtpzuivdvr.html

C#:   7 / 2; 7 % 2
来源：http://dali.cucudq.cn/Article/details/gtdmtpehwx.html

[A06] 字符串转数字
来源：http://dali.zhongyouzk.top/Article/details/gtivuqphoz.html

Py:   int("42"); float("3.14")
来源：http://dali.shangyingyoupin.top/Article/details/gtokcoxgmp.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.wangshuangyany.cn/Article/details/gtdgshlohf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zdqjudy.top/Article/details/gtbugruvaa.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.cdnleiting.top/Article/details/gtsanxpiwj.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.ppjwa.cn/Article/details/gtccrrcboe.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shzxlz.cn/Article/details/gtwrihhjdq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.pycfn.com/Article/details/gthvrmrihi.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.vqdsnc.cn/Article/details/gtlxybgqgi.html

[A07] 数字转字符串
来源：http://dali.zhengqikj.top/Article/details/gtkqjlciuq.html

Py:   str(42)
来源：http://dali.snrcjt.cn/Article/details/gtmtljappi.html

PHP:  (string) 42; strval(42)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdyjpwdje.html

JS:   String(42); (42).toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtgmigwqke.html

TS:   String(42)
来源：http://dali.shuidangran.top/Article/details/gtgdohjaak.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.xylfe.cn/Article/details/gtoibgogqs.html

Go:   strconv.Itoa(42)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxuodxhcu.html

Ruby: 42.to_s
来源：http://dali.wangdashe.top/Article/details/gtlquawipz.html

C#:   42.ToString()
来源：http://dali.guowangkeji.top/Article/details/gtcsosexza.html

[A08] 取整与四舍五入
来源：http://dali.cheryme.top/Article/details/gtippjffrb.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.tanke756.top/Article/details/gtiqmfvjui.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtusvfjlrg.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmtkmike.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.sweek.top/Article/details/gtaifssvzr.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhoulong.xyz/Article/details/gtumyhfeox.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.sxryk.cn/Article/details/gtdnykqqbq.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yuxming.cn/Article/details/gtuejwniwe.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yvedp.cn/Article/details/gtkdpqregn.html

[A09] 绝对值与最大最小值
来源：http://dali.aibaodan.cn/Article/details/gtcsysloem.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsvbmogxk.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gtrvnidpbr.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gtzqpqczpx.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtongnyywc.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.ydzc1.top/Article/details/gtosizhkre.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jiagoushi.top/Article/details/gtvrduzefe.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.nanxinkj.top/Article/details/gtnpqenqao.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gtstcleave.html

[A10] 生成随机数
来源：http://dali.shuidangran.top/Article/details/gtrfjztzyv.html

Py:   import random; random.randint(1, 100)
来源：http://dali.ehwqpu.com/Article/details/gtzuinbpcc.html

PHP:  random_int(1, 100);
来源：http://dali.vqdsnc.cn/Article/details/gtttckxyik.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yvedp.cn/Article/details/gtzvhybcht.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.gaohongyu789.top/Article/details/gtfmtrkcgi.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yonumen.top/Article/details/gtubqavkri.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yj20258.top/Article/details/gtsttbekxa.html

Ruby: rand(1..100)
来源：http://dali.snrcjt.cn/Article/details/gttkpchxuf.html

C#:   new Random().Next(1, 101)
来源：http://dali.bjfxy.top/Article/details/gtxmjwvqic.html

[A11] 条件表达式（三元）
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwqrvosm.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.hysaishi.cn/Article/details/gtliulklhc.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yangfankeji.com/Article/details/gtbeyrtdag.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yonumen.top/Article/details/gtuqhxnffi.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.nanxinkj.top/Article/details/gtncpzdbox.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xinyue.icu/Article/details/gtrfuceqqr.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zdqjudy.top/Article/details/gtqrevbnqj.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.iojbl.cn/Article/details/gtntvdxlkx.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.chenlongwang.top/Article/details/gtovxowdwx.html

[A12] 字符串插值 / 格式化
来源：http://dali.fengsongda.top/Article/details/gtthzenefj.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyikoopsp.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jiagoushi.top/Article/details/gtmswwxzhe.html

JS:   `Hello, ${name}!`
来源：http://dali.sufxvd.cn/Article/details/gtgbsmndhg.html

TS:   `Hello, ${name}!`
来源：http://dali.fengsongda.top/Article/details/gtaiolmbhn.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhiwuduotai.top/Article/details/gtokbrtjtn.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.nanxuanxn.top/Article/details/gtndtzdxxq.html

Ruby: "Hello, #{name}!"
来源：http://dali.cheryme.top/Article/details/gttilsnnvv.html

C#:   $"Hello, {name}!"
来源：http://dali.hammf.cn/Article/details/gtjbjcahct.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.nwbrower.top/Article/details/gtofzemwnz.html

Py:   "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazvyoryv.html

PHP:  "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gtcsiwogzt.html

JS:   "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gtknhrkoee.html

TS:   "第一行\n第二行"
来源：http://dali.nanxinkj.top/Article/details/gtvrfaabmo.html

Java: "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gtfrcllkgh.html

Go:   "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gtbkzzyzjy.html

Ruby: "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gtvluballm.html

C#:   "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gtfyxkxpwp.html

[A14] 注释写法
来源：http://dali.zycfv.cn/Article/details/gtmgwqfwyw.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkixuqqu.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yj20258.top/Article/details/gtuckxuqxf.html

JS:   // 单行；/* 多行 */
来源：http://dali.kuanghao11.cn/Article/details/gtjybsywol.html

TS:   // 单行；/* 多行 */
来源：http://dali.xylfe.cn/Article/details/gtarimibxs.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhengqikj.top/Article/details/gtxjcervph.html

Go:   // 单行；/* 多行 */
来源：http://dali.dianchejie.cn/Article/details/gtmqszbrrm.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.havefunace.top/Article/details/gtaftjpsxq.html

C#:   // 单行；/* 多行 */
来源：http://dali.wangshuangyany.cn/Article/details/gtfbwydtuk.html

[A15] 空值判断与默认值
来源：http://dali.wangdashe.top/Article/details/gtmshfnuor.html

Py:   value = data or "默认值"
来源：http://dali.mhx1999.top/Article/details/gtefrpiyvy.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhongyouzk.top/Article/details/gtocqkedig.html


<!-- 参考信息 -->