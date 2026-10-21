代发 wailian999

[U97] JS：并发请求
来源：http://dali.snrcjt.cn/Article/details/gtebxrmzno.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gtexjsxvci.html

[U98] JS：fetch 带 JSON
来源：http://dali.shuidangran.top/Article/details/gtmyukgkrc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.0kj1m.cn/Article/details/gtsdubqolw.html

[U99] JS：事件监听
来源：http://dali.jyoumei.cn/Article/details/gtopgtxnfv.html

el.addEventListener("click", e => {})
来源：http://dali.wangdashe.top/Article/details/gtzbwzwuph.html

[U100] JS：DOM 查询
来源：http://dali.zdqjudy.top/Article/details/gtcvagfvvt.html

document.querySelector(".item")
来源：http://dali.yanxiufei.cn/Article/details/gtimobppni.html

[U101] JS：classList 操作
来源：http://dali.sufxvd.cn/Article/details/gtkfkjvohy.html

el.classList.toggle("active")
来源：http://dali.pengpengdd.cyou/Article/details/gtsfhaahkv.html

[U102] JS：本地存储
来源：http://dali.guannengcc.top/Article/details/gtakoyjvuu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.c1oappe.top/Article/details/gtpvxqeiim.html

[U103] JS：定时器
来源：http://dali.daxiang520.top/Article/details/gtvonlzmgy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.aibaodan.cn/Article/details/gtgyyxnheq.html

[U104] JS：防抖
来源：http://dali.ppjwa.cn/Article/details/gtvmckgyvp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gtwpkjvsdb.html

[U105] JS：节流
来源：http://dali.cdnleiting.top/Article/details/gtpcgahkki.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.wangdashe.top/Article/details/gteowjgszy.html

[U106] JS：日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtcvhnnmic.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhoulong.xyz/Article/details/gtgsmewsid.html

[U107] JS：数字千分位
来源：http://dali.jlsjyb.cn/Article/details/gtavferqdh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.wangdashe.top/Article/details/gtqtpeijwh.html

[U108] JS：随机整数
来源：http://dali.yangfankeji.com/Article/details/gtdelpuhsg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.feifeiyinyue.top/Article/details/gtnnhffpwa.html

[U109] JS：数组分组
来源：http://dali.zhoulong.xyz/Article/details/gtdhhbxgic.html

Object.groupBy(arr, x => x.type)
来源：http://dali.aibaodan.cn/Article/details/gttmdeodsr.html

[U110] JS：数组分块
来源：http://dali.316326.xyz/Article/details/gtefgithqu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinqigfzy.top/Article/details/gtdglmpnag.html

[U111] JS：对象转 Map
来源：http://dali.jiagoushi.top/Article/details/gtijnwnfpo.html

new Map(Object.entries(obj))
来源：http://dali.sweek.top/Article/details/gttxbtbcaj.html

[U112] JS：字符串补位
来源：http://dali.ivvv.top/Article/details/gtbffmjvcp.html

"7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtlsesqfzf.html

[U113] JS：正则替换全部
来源：http://dali.jianghu66.top/Article/details/gtmsxszhgb.html

s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtkjvuvekx.html

[U114] JS：JSON 深比较
来源：http://dali.sweek.top/Article/details/gtgkeiwqlg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yueranfly.top/Article/details/gtdavgqcpu.html

[U115] JS：生成 UUID
来源：http://dali.c1oappe.top/Article/details/gtfiyhagdk.html

crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gtibkxpruy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gzhubu.top/Article/details/gtjjspoolf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.0kj1m.cn/Article/details/gtvokurvbk.html

[U117] JS：单元测试
来源：http://dali.jlsjyb.cn/Article/details/gtbvjefhiq.html

npm i -D vitest;  npx vitest
来源：http://dali.tianlin.xyz/Article/details/gtsmcapujq.html

[U118] JS：开发服务器
来源：http://dali.gogol.net.cn/Article/details/gtzxtoghpz.html

npm i -D vite;  npx vite
来源：http://dali.birdmap.top/Article/details/gtzwrolivp.html

[U119] JS：生产构建
来源：http://dali.fengsongda.top/Article/details/gtuktpsdcl.html

npx vite build
来源：http://dali.yuxming.cn/Article/details/gthpuhcoed.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.redwolf501.top/Article/details/gtvognyain.html

import.meta.env.VITE_API_URL
来源：http://dali.tanke756.top/Article/details/gtqlwgpkas.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtfykglyay.html

统计汇总
来源：http://dali.c1oappe.top/Article/details/gtmdrszuaz.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gttgjlqria.html

按语言统计（条）：
来源：http://dali.wangshuangyany.cn/Article/details/gtqgzbsukk.html

Python ......... 252
来源：http://dali.hfpthk.cn/Article/details/gtwufuganv.html

PHP ............ 252
来源：http://dali.sweek.top/Article/details/gtyntxsqrr.html

JavaScript ..... 252
来源：http://dali.yj20258.top/Article/details/gtdqipowgj.html

TypeScript ..... 212
来源：http://dali.zhiwuduotai.top/Article/details/gtpupburye.html

Java ........... 212
来源：http://dali.zhiwuduotai.top/Article/details/gtdgllqpna.html

Go ............. 212
来源：http://dali.fengsongda.top/Article/details/gtudvusbhq.html

Ruby ........... 212
来源：http://dali.zhixingplan.top/Article/details/gtayulngpg.html

C# ............. 212
来源：http://dali.svipenyu.cn/Article/details/gtckvqypau.html

C .............. 30
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoxvgncon.html

C++ ............ 30
来源：http://dali.snrcjt.cn/Article/details/gtftmvgrws.html

SQL ............ 90
来源：http://dali.iojbl.cn/Article/details/gtlhwtdtvo.html

Bash ........... 80
来源：http://dali.mhx1999.top/Article/details/gtzugfzbzz.html

Kotlin ......... 15
来源：http://dali.nwbrower.top/Article/details/gtmmfgowjs.html

Swift .......... 15
来源：http://dali.zhiwuduotai.top/Article/details/gtvmdjpjqn.html

Lua ............ 10
来源：http://dali.svipenyu.cn/Article/details/gtlnnwrxzt.html

Perl ........... 10
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdctsgfo.html

Scala .......... 10
来源：http://dali.pycfn.com/Article/details/gtjsmahdzs.html

------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gtspohmbys.html

合计 ........... 2106 条
来源：http://dali.zhongyouzk.top/Article/details/gtptwrclaq.html

按章节统计：
来源：http://dali.bjfxy.top/Article/details/gtxcpokbck.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.316326.xyz/Article/details/gtpcorqjfy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.guowangkeji.top/Article/details/gtrbydtvbg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xylfe.cn/Article/details/gtyzezgmqq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.wangdashe.top/Article/details/gtxovpkkwk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jlsjyb.cn/Article/details/gttvinqspk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.chenlongwang.top/Article/details/gteyrdimxj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ppjwa.cn/Article/details/gtiagzjjsx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xinyue.icu/Article/details/gtepiiorzi.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gtnqmwokui.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinqigufen.top/Article/details/gtsjtdsfrb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gtvbyakfxd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gtqwrqxnth.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gtpfvgfwrf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ivvv.top/Article/details/gttayhjqvm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhoulong.xyz/Article/details/gthiorlsop.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gtntonafvk.html

Q SQL 专题                              90
来源：http://dali.birdmap.top/Article/details/gtabwjslpa.html

R Bash 专题                             80
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvinjxqd.html

S C / C++ 专题                          60
来源：http://dali.xylfe.cn/Article/details/gticexmaee.html

T 其他语言补充                          60
来源：http://dali.iojbl.cn/Article/details/gtqmujwdlx.html

U 高频实用片段                         120
来源：http://dali.ehwqpu.com/Article/details/gtcrssufwf.html

------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gtmkeqfrhb.html

合计                                  2106 条
来源：http://dali.jinqigufen.top/Article/details/gtuuqkjdcx.html

--------------------------------------------------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gtmgcdksjh.html

使用提醒
来源：http://dali.shuidangran.top/Article/details/gtpbzmtgsd.html

--------------------------------------------------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gtdawwvbvc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.aizwys.cn/Article/details/gtehdyageg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yuanzhike.top/Article/details/gtthtyuhud.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.shanyushiyangtech.top/Article/details/gtscvobmau.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.shzxlz.cn/Article/details/gtpiullqlp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.nanxuanxn.top/Article/details/gtvgwtjrbm.html

—— 文件结束 ——
来源：http://dali.shzxlz.cn/Article/details/gtcmlrnigz.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtxvapyzqs.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.sysykeji.top/Article/details/gtwsfhmroj.html

Common Programming Examples Cheat Book
来源：http://dali.zhongyouzk.top/Article/details/gtatrnopbt.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtvcbhears.html

【收录内容】
来源：http://dali.aizwys.cn/Article/details/gtskkikcss.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.sxryk.cn/Article/details/gtuksnuxcu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.guannengcc.top/Article/details/gtdzdvbfph.html

SQL · Bash · C · C++
来源：http://dali.hysaishi.cn/Article/details/gtmanpfslh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yj20258.top/Article/details/gtggqcrwdq.html

【使用说明】
来源：http://dali.hywenlv.cn/Article/details/gtlfeuiiww.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yueranfly.top/Article/details/gtxhftynjk.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ehwqpu.com/Article/details/gtjvinqswa.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.iojbl.cn/Article/details/gtfxfmkaar.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gtjeptztks.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yuxming.cn/Article/details/gtkpheiedp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hnxiangtu.top/Article/details/gtmithilpy.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jlsjyb.cn/Article/details/gtfektxvpv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.chenlongwang.top/Article/details/gtaqaixxqu.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.fengsongda.top/Article/details/gtvdclybid.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.tianlin.xyz/Article/details/gtiielcftp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.chenzaomai.com/Article/details/gtvxuaqxsl.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.wangshuangyany.cn/Article/details/gtphfwujyc.html

【文件统计】
来源：http://dali.jqgufenzy.top/Article/details/gtummkxmcw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.snrcjt.cn/Article/details/gtfmrintmh.html

--------------------------------------------------------------------------------
来源：http://dali.shuidangran.top/Article/details/gtcptgqwwl.html

目  录
来源：http://dali.redwolf501.top/Article/details/gtidfbqtlu.html

--------------------------------------------------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gtvqgtrmzb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ivvv.top/Article/details/gtbcamgxpj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.haohaochexian.top/Article/details/gtdjhbteob.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shuidangran.top/Article/details/gtznqywayd.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.fzhhl.top/Article/details/gtkwdxdurb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.havefunace.top/Article/details/gtjeljzjue.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.ppjwa.cn/Article/details/gtfantlhji.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.sysykeji.top/Article/details/gtxagdslvv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.haohaochexian.top/Article/details/gtoqczzeck.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtryouqsjw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhengqikj.top/Article/details/gtkqpsevex.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.daxiang520.top/Article/details/gtwhvmtvpw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.0kj1m.cn/Article/details/gtclpfhewl.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtworuktjp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yueranfly.top/Article/details/gtzdbsfpbl.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.nwbrower.top/Article/details/gtelyvgbwh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.gotoacloud.top/Article/details/gthwdbuxpz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.fzhhl.top/Article/details/gtijznsaxl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymgtuyzr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtcqjxbeet.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aibaodan.cn/Article/details/gthmeqitic.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.gzhubu.top/Article/details/gtbwuwdzrc.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtuuixwhsf.html

A. 基础语法与类型
来源：http://dali.gzhubu.top/Article/details/gtvbxiexfe.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtfwiouhem.html

[A01] Hello World
来源：http://dali.shzxlz.cn/Article/details/gtewfiegnz.html

Py:   print("Hello, World!")
来源：http://dali.redwolf501.top/Article/details/gtwanjpnop.html

PHP:  echo "Hello, World!";
来源：http://dali.cucudq.cn/Article/details/gtwoweuhic.html

JS:   console.log("Hello, World!");
来源：http://dali.vqdsnc.cn/Article/details/gtukhnjzqk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jianghu66.top/Article/details/gtxnpasfmv.html

Java: System.out.println("Hello, World!");
来源：http://dali.quarkkingdee.top/Article/details/gtnlowjuzl.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xuanzx.com/Article/details/gthzdqviuv.html

Ruby: puts "Hello, World!"
来源：http://dali.hammf.cn/Article/details/gtspgkcyer.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yuanzhike.top/Article/details/gtaikshqsu.html

[A02] 变量声明与赋值
来源：http://dali.zhiwuduotai.top/Article/details/gtzsytumwh.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.nwbrower.top/Article/details/gtjsttyxnm.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yj20258888.top/Article/details/gttkogbfad.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.chenjidiqi.icu/Article/details/gtlnxidgdf.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gotoacloud.top/Article/details/gtfktwmjdh.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gtpzfgsiuy.html

Go:   name := "Alex"; age := 20
来源：http://dali.pengpengdd.cyou/Article/details/gttbayzbbi.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hongshengwenyu.top/Article/details/gtuhxxhikh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.mhx1999.top/Article/details/gtohkvzivs.html

[A03] 常量定义
来源：http://dali.jyoumei.cn/Article/details/gtuydbiiqm.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.andypj.xyz/Article/details/gtqxflbolg.html

PHP:  const PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtqwjmstrm.html

JS:   const PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtszxgarfc.html

TS:   const PI: number = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gttvvuepfl.html

Java: static final double PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtgfiudxch.html

Go:   const PI = 3.14159
来源：http://dali.feifeiyinyue.top/Article/details/gthoecnvny.html

Ruby: PI = 3.14159
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvatoyfe.html

C#:   const double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gteqjmcpxk.html

[A04] 判断变量类型
来源：http://dali.yangfankeji.com/Article/details/gtvednnrlm.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.gogol.net.cn/Article/details/gtsplklwju.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.daria6918.cn/Article/details/gtquktdvot.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.ybcxt.top/Article/details/gtsiioqnct.html

TS:   typeof x; x instanceof Date
来源：http://dali.hysaishi.cn/Article/details/gtshrmgwtm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.tian-w.cn/Article/details/gtrshonoce.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zdqjudy.top/Article/details/gtrtebvrdk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.sxryk.cn/Article/details/gtkpyykcxo.html

C#:   x.GetType().Name; x is int
来源：http://dali.shangyingyoupin.top/Article/details/gtrichahex.html

[A05] 整数除法与取模
来源：http://dali.zdqjudy.top/Article/details/gtwbrwkhuq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xuanzx.com/Article/details/gtbmlpgjnz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gthikwblqw.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtgixpakta.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtlhlmsytv.html

Java: 7 / 2; 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gtleuqgukv.html

Go:   7 / 2; 7 % 2
来源：http://dali.shuidangran.top/Article/details/gtnmzlomfi.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gtgmjxcvcv.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqlcukqrr.html

[A06] 字符串转数字
来源：http://dali.haohaochexian.top/Article/details/gtoifqaplf.html

Py:   int("42"); float("3.14")
来源：http://dali.zhoulong.xyz/Article/details/gtvuuryuel.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jianghu66.top/Article/details/gtibqnmneb.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhengqikj.top/Article/details/gtvmgcjrrm.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jyoumei.cn/Article/details/gtqsbojesf.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cheryme.top/Article/details/gtedwfklle.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hysaishi.cn/Article/details/gtntxdcovb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.svipenyu.cn/Article/details/gtsikpfzkv.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xylfe.cn/Article/details/gtzqaqutzz.html

[A07] 数字转字符串
来源：http://dali.yueranfly.top/Article/details/gtqnrgdbhz.html

Py:   str(42)
来源：http://dali.yuanzhike.top/Article/details/gtqxrxmamz.html

PHP:  (string) 42; strval(42)
来源：http://dali.tanke756.top/Article/details/gtruypjomh.html

JS:   String(42); (42).toString()
来源：http://dali.daria6918.cn/Article/details/gtnsnojbrc.html

TS:   String(42)
来源：http://dali.sxryk.cn/Article/details/gthnawyapa.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.xuetiantiany.cn/Article/details/gtmwqizesh.html

Go:   strconv.Itoa(42)
来源：http://dali.aibaodan.cn/Article/details/gtiuzekrbr.html

Ruby: 42.to_s
来源：http://dali.havefunace.top/Article/details/gtxwwjptbm.html

C#:   42.ToString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjhkaxya.html

[A08] 取整与四舍五入
来源：http://dali.tian-w.cn/Article/details/gtvgkgzjxx.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhpzwbcm.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jinqigufen.top/Article/details/gtkskxdvzo.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.chenlongwang.top/Article/details/gtyuasfqfx.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.xylfe.cn/Article/details/gtbhxkrcpe.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.chenlongwang.top/Article/details/gtbpeiahpy.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.feifeiyinyue.top/Article/details/gtxmyoiwyz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhixingplan.top/Article/details/gtudyrnryt.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jqgufenzy.top/Article/details/gtpcqemnjs.html

[A09] 绝对值与最大最小值
来源：http://dali.svipenyu.cn/Article/details/gtgcqgphcd.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yueranfly.top/Article/details/gtjqvvkgyx.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gtdrfgsvhk.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.havefunace.top/Article/details/gtziievydo.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.tanke756.top/Article/details/gtwsdoncbk.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtswrvpbtb.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.haohaochexian.top/Article/details/gtsyubsebn.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.quarkkingdee.top/Article/details/gtkqbgtxay.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.c1oappe.top/Article/details/gtymxcyfbu.html

[A10] 生成随机数
来源：http://dali.fzhhl.top/Article/details/gtfyggfjdq.html

Py:   import random; random.randint(1, 100)
来源：http://dali.gogol.net.cn/Article/details/gtfotdapul.html

PHP:  random_int(1, 100);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmoyuultq.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cheryme.top/Article/details/gtayvpeuzi.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hnqzz.top/Article/details/gtxnjkalzx.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodcdlkfl.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jqgufenzy.top/Article/details/gtrgzmrsfz.html

Ruby: rand(1..100)
来源：http://dali.nanxinkj.top/Article/details/gtlrorhqnk.html

C#:   new Random().Next(1, 101)
来源：http://dali.hnxiangtu.top/Article/details/gtohtpwzyv.html

[A11] 条件表达式（三元）
来源：http://dali.gogol.net.cn/Article/details/gtmurcjuqs.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.ehwqpu.com/Article/details/gtygbsxsxg.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.jinqigfzy.top/Article/details/gtsreworza.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.dianchejie.cn/Article/details/gtmdmxlvlm.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yuanzhike.top/Article/details/gtqeeygvxp.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jqgfzy.top/Article/details/gtnsxcvkbu.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yueranfly.top/Article/details/gtkdpqzuyc.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jinqigfzy.top/Article/details/gtkpaczqfb.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.gzhubu.top/Article/details/gtjezmwqty.html

[A12] 字符串插值 / 格式化
来源：http://dali.havefunace.top/Article/details/gtrejwmmvl.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.havefunace.top/Article/details/gtunckqddp.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.sysykeji.top/Article/details/gtavovrkni.html

JS:   `Hello, ${name}!`
来源：http://dali.shzxlz.cn/Article/details/gtulzyapvt.html

TS:   `Hello, ${name}!`
来源：http://dali.cheryme.top/Article/details/gtdegjufsm.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.9152youxi.cn/Article/details/gtqdvgnrzq.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.feifeiyinyue.top/Article/details/gthpnorbgz.html

Ruby: "Hello, #{name}!"
来源：http://dali.hfpthk.cn/Article/details/gtmzqbetfu.html

C#:   $"Hello, {name}!"
来源：http://dali.svipenyu.cn/Article/details/gtxjowjswy.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.feifeiyinyue.top/Article/details/gtuviifgwp.html

Py:   "第一行\n第二行"
来源：http://dali.zhongyouzk.top/Article/details/gtctlimdmu.html

PHP:  "第一行\n第二行"
来源：http://dali.xuanzx.com/Article/details/gtwsnxjhca.html

JS:   "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gtmloiewvj.html

TS:   "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gteiaqjrnv.html

Java: "第一行\n第二行"
来源：http://dali.xinyue.icu/Article/details/gtqzpqdmpt.html

Go:   "第一行\n第二行"
来源：http://dali.xziqi.cn/Article/details/gtltbfmwpl.html

Ruby: "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gtjmkahatn.html

C#:   "第一行\n第二行"
来源：http://dali.yangfankeji.com/Article/details/gtpqaswxgw.html

[A14] 注释写法
来源：http://dali.shangyingyoupin.top/Article/details/gtdthxtkor.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.ybcxt.top/Article/details/gtyweroksl.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yangfankeji.com/Article/details/gtcllyxrjn.html

JS:   // 单行；/* 多行 */
来源：http://dali.pengpengdd.cyou/Article/details/gtohvstcwf.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhixingplan.top/Article/details/gttdrgixot.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.wangdashe.top/Article/details/gtywazcsxx.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkensscs.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhixingplan.top/Article/details/gtgguxhptz.html

C#:   // 单行；/* 多行 */
来源：http://dali.wangdashe.top/Article/details/gtclthhifx.html

[A15] 空值判断与默认值
来源：http://dali.aibaodan.cn/Article/details/gtvfwdrfda.html

Py:   value = data or "默认值"
来源：http://dali.dianchejie.cn/Article/details/gtdtrbjjgw.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yanxiufei.cn/Article/details/gtwjwseqmj.html

JS:   const value = data ?? "默认值";
来源：http://dali.ehwqpu.com/Article/details/gtnnidbdxd.html

TS:   const value = data ?? "默认值";
来源：http://dali.hysaishi.cn/Article/details/gtvtevvjgu.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.pengpengdd.cyou/Article/details/gtfxkschxa.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.cucudq.cn/Article/details/gtbjlmzjmu.html

Ruby: value = data || "默认值"
来源：http://dali.xinyue.icu/Article/details/gtwwxasoka.html

C#:   var value = data ?? "默认值";
来源：http://dali.9152youxi.cn/Article/details/gthpuwsbmb.html

[A16] 真假值判断规则
来源：http://dali.havefunace.top/Article/details/gtlbxewuuy.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.sysykeji.top/Article/details/gteecbbqdi.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hnxiangtu.top/Article/details/gtpgloypdr.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.quarkkingdee.top/Article/details/gtzxtfqcjy.html

TS:   if (!x) {}
来源：http://dali.xylfe.cn/Article/details/gtjxrjdpuq.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.guannengcc.top/Article/details/gtgjjtmbtg.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.0kj1m.cn/Article/details/gtxlunfbyr.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.wangdashe.top/Article/details/gtreelvtmt.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.guannengcc.top/Article/details/gtrbbbymon.html

[A17] 位运算
来源：http://dali.hfpthk.cn/Article/details/gtpjezyyaf.html


<!-- 参考信息 -->