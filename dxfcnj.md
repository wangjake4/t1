代发 wailian999

[U89] JS：数组去重
来源：http://dali.meibo888.top/Article/details/gtlcmrrtcf.html

[...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gtkwmflbuj.html

[U90] JS：数字数组排序
来源：http://dali.jiagoushi.top/Article/details/gtccwxflli.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gtsyzfneca.html

[U91] JS：对象键值遍历
来源：http://dali.hywenlv.cn/Article/details/gtgolgzubc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gzhubu.top/Article/details/gttpksawnz.html

[U92] JS：深拷贝
来源：http://dali.meibo888.top/Article/details/gtygbhulhh.html

structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtouadsmai.html

[U93] JS：模板字符串
来源：http://dali.aibaodan.cn/Article/details/gtfnmngosw.html

`共 ${n} 条`
来源：http://dali.cqqwz.cn/Article/details/gtsdquvqlp.html

[U94] JS：箭头函数
来源：http://dali.haohaochexian.top/Article/details/gtvtxswnrd.html

const double = x => x * 2;
来源：http://dali.xuetiantiany.cn/Article/details/gtzdctoqxk.html

[U95] JS：Promise 包装
来源：http://dali.tianlin.xyz/Article/details/gtfzfnhcgg.html

new Promise((resolve, reject) => {})
来源：http://dali.yangfankeji.com/Article/details/gtawozmgmb.html

[U96] JS：async/await 与异常
来源：http://dali.0kj1m.cn/Article/details/gtimvcwoxp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasgvdsmx.html

[U97] JS：并发请求
来源：http://dali.jiagoushi.top/Article/details/gtgajrnule.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gttqclzmql.html

[U98] JS：fetch 带 JSON
来源：http://dali.cashguo.top/Article/details/gtgpgjyshl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtenuqzccv.html

[U99] JS：事件监听
来源：http://dali.zhoulong.xyz/Article/details/gtmsbdwwza.html

el.addEventListener("click", e => {})
来源：http://dali.nwbrower.top/Article/details/gtxppwhenl.html

[U100] JS：DOM 查询
来源：http://dali.gotoacloud.top/Article/details/gtoacqsbfg.html

document.querySelector(".item")
来源：http://dali.jqgufenzy.top/Article/details/gtawreqocj.html

[U101] JS：classList 操作
来源：http://dali.andypj.xyz/Article/details/gtqskrwiuu.html

el.classList.toggle("active")
来源：http://dali.sysykeji.top/Article/details/gtewtgcmsw.html

[U102] JS：本地存储
来源：http://dali.jqgfzy.top/Article/details/gtmqjekunk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yanxiufei.cn/Article/details/gtcvtxgguv.html

[U103] JS：定时器
来源：http://dali.jqgufenzy.top/Article/details/gtdkbfsnst.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.havefunace.top/Article/details/gtympbxnhw.html

[U104] JS：防抖
来源：http://dali.dashuyun.cn/Article/details/gtikexbksb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigfzy.top/Article/details/gteuhguqyl.html

[U105] JS：节流
来源：http://dali.yanxiufei.cn/Article/details/gtgigaxmpc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.smart0.xyz/Article/details/gtywoqpgjp.html

[U106] JS：日期格式化
来源：http://dali.0kj1m.cn/Article/details/gtnzgqdydm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.aizwys.cn/Article/details/gtanwenlqz.html

[U107] JS：数字千分位
来源：http://dali.jqgufenzy.top/Article/details/gtofoisfhm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.tanke756.top/Article/details/gtpdeabuzj.html

[U108] JS：随机整数
来源：http://dali.dashuyun.cn/Article/details/gtfholmcux.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cqqwz.cn/Article/details/gtgczcgjkz.html

[U109] JS：数组分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsakbpclc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cucudq.cn/Article/details/gtvjfkofrl.html

[U110] JS：数组分块
来源：http://dali.tianlin.xyz/Article/details/gthlibjhzw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.quarkkingdee.top/Article/details/gtjdkzmkrw.html

[U111] JS：对象转 Map
来源：http://dali.sysykeji.top/Article/details/gtggavhque.html

new Map(Object.entries(obj))
来源：http://dali.jianghu66.top/Article/details/gtwlouqeoy.html

[U112] JS：字符串补位
来源：http://dali.ppjwa.cn/Article/details/gtstweibgf.html

"7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gthvufrjhj.html

[U113] JS：正则替换全部
来源：http://dali.daxiang520.top/Article/details/gtzbyhtxus.html

s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlheeakm.html

[U114] JS：JSON 深比较
来源：http://dali.ehwqpu.com/Article/details/gteafmizmd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjotmskrq.html

[U115] JS：生成 UUID
来源：http://dali.chenlongwang.top/Article/details/gtbhsdyxpd.html

crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gtubqqvrug.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.wangdashe.top/Article/details/gttfjdmqea.html

/** @param {string} name */ function f(name) {}
来源：http://dali.fzhhl.top/Article/details/gtfgyssjtc.html

[U117] JS：单元测试
来源：http://dali.fengsongda.top/Article/details/gtgypyfkpz.html

npm i -D vitest;  npx vitest
来源：http://dali.chenjidiqi.icu/Article/details/gtiscmwrct.html

[U118] JS：开发服务器
来源：http://dali.birdmap.top/Article/details/gtcmarvinp.html

npm i -D vite;  npx vite
来源：http://dali.zhiwuduotai.top/Article/details/gtbuyngmdi.html

[U119] JS：生产构建
来源：http://dali.hongshengwenyu.top/Article/details/gtjdbmiuvk.html

npx vite build
来源：http://dali.nanxinkj.top/Article/details/gtgsxfvsjl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.guowangkeji.top/Article/details/gtbjzoxtmp.html

import.meta.env.VITE_API_URL
来源：http://dali.pycfn.com/Article/details/gtkazdkrna.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtaiekukrk.html

统计汇总
来源：http://dali.shuidangran.top/Article/details/gtkaoiphfd.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtouknxptv.html

按语言统计（条）：
来源：http://dali.c1oappe.top/Article/details/gtqizvxiiv.html

Python ......... 252
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtseqvbmtl.html

PHP ............ 252
来源：http://dali.9152youxi.cn/Article/details/gtnlulzlzf.html

JavaScript ..... 252
来源：http://dali.haohaochexian.top/Article/details/gtvuyzhoze.html

TypeScript ..... 212
来源：http://dali.gogol.net.cn/Article/details/gtgvmaoxvf.html

Java ........... 212
来源：http://dali.hysaishi.cn/Article/details/gtvxvuphjo.html

Go ............. 212
来源：http://dali.daxiang520.top/Article/details/gtnjunzcak.html

Ruby ........... 212
来源：http://dali.feifeiyinyue.top/Article/details/gtiasywpvt.html

C# ............. 212
来源：http://dali.yonumen.top/Article/details/gttzlfxyhd.html

C .............. 30
来源：http://dali.jinqigfzy.top/Article/details/gtwxzpeurq.html

C++ ............ 30
来源：http://dali.yj20258888.top/Article/details/gtxauxooek.html

SQL ............ 90
来源：http://dali.dashuyun.cn/Article/details/gtwwpvhcao.html

Bash ........... 80
来源：http://dali.wangshuangyany.cn/Article/details/gthcrmrfji.html

Kotlin ......... 15
来源：http://dali.haohaochexian.top/Article/details/gtmubtlmth.html

Swift .......... 15
来源：http://dali.zdqjudy.top/Article/details/gtspefhcjv.html

Lua ............ 10
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogpnrbjs.html

Perl ........... 10
来源：http://dali.jqgufenzy.top/Article/details/gtzvhjcdjr.html

Scala .......... 10
来源：http://dali.sxryk.cn/Article/details/gtagzktiuv.html

------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gtyqfikjow.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gtoaoplppc.html

按章节统计：
来源：http://dali.feifeiyinyue.top/Article/details/gtycqwjukr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zycfv.cn/Article/details/gtzayzexjj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cucudq.cn/Article/details/gtyjdtvuxy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hammf.cn/Article/details/gtoutwopki.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zycfv.cn/Article/details/gtsjrqdgrv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.0kj1m.cn/Article/details/gtrwwmbwwi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.wangdashe.top/Article/details/gtzpwnoaed.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.0kj1m.cn/Article/details/gtkmuydaid.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.svipenyu.cn/Article/details/gtjgqahyac.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gtzpojbqby.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.0kj1m.cn/Article/details/gtxcjkjxci.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gtifkaunlm.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gtnkpdqexf.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jyoumei.cn/Article/details/gtbpqoouyc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xylfe.cn/Article/details/gthfobadkh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yangfankeji.com/Article/details/gtawxhfuko.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gtpzubwdlv.html

Q SQL 专题                              90
来源：http://dali.meibo888.top/Article/details/gtmlgvzjnu.html

R Bash 专题                             80
来源：http://dali.ppjwa.cn/Article/details/gtjgxglqsr.html

S C / C++ 专题                          60
来源：http://dali.yuxming.cn/Article/details/gtmovhrxfc.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gtbnynxnnt.html

U 高频实用片段                         120
来源：http://dali.xinyue.icu/Article/details/gtfidxbmty.html

------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gtvtkqcxpv.html

合计                                  2106 条
来源：http://dali.xuetiantiany.cn/Article/details/gtensnuujv.html

--------------------------------------------------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtbfxapwmr.html

使用提醒
来源：http://dali.hywenlv.cn/Article/details/gtivzptudv.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigfzy.top/Article/details/gtamzahhbb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cucudq.cn/Article/details/gtwhndalaj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.tanke756.top/Article/details/gttgvnmkqr.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.chenlongwang.top/Article/details/gtbotsktdq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqzpbflx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggjfywaf.html

—— 文件结束 ——
来源：http://dali.316326.xyz/Article/details/gtwstvtgtq.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtusedfvtv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yj20258888.top/Article/details/gtwrniueyx.html

Common Programming Examples Cheat Book
来源：http://dali.dashuyun.cn/Article/details/gttendfeww.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtdcydclvc.html

【收录内容】
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdlsfiiq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cucudq.cn/Article/details/gtbvaefxyf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yj20258888.top/Article/details/gtkbplyowb.html

SQL · Bash · C · C++
来源：http://dali.jqgfzy.top/Article/details/gtimnpjxry.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ivvv.top/Article/details/gttvvrtsvi.html

【使用说明】
来源：http://dali.xziqi.cn/Article/details/gteboweaad.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zdqjudy.top/Article/details/gtzclydenl.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.chenlongwang.top/Article/details/gturnmtmak.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hongshengwenyu.top/Article/details/gtybjogmzn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yangfankeji.com/Article/details/gteabtirwm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.fengsongda.top/Article/details/gtpktawhhi.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.redwolf501.top/Article/details/gtqhsjtctx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.dashuyun.cn/Article/details/gtyewzrets.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yj20258.top/Article/details/gtgvipccwn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.sweek.top/Article/details/gtvusfwohe.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.feifeiyinyue.top/Article/details/gtwsbhmcrp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yj20258.top/Article/details/gtsqicqtgr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jqgfzy.top/Article/details/gtphmcgjtu.html

【文件统计】
来源：http://dali.mhx1999.top/Article/details/gtuopndzds.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xylfe.cn/Article/details/gtmnucjzzo.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtvzbkarox.html

目  录
来源：http://dali.aizwys.cn/Article/details/gttdakrxpt.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtqoohioeb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.snrcjt.cn/Article/details/gtpfgcbbhi.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhiqjdbz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpziftvt.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtshjtvxer.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hnqzz.top/Article/details/gtzktxsfua.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.shuidangran.top/Article/details/gtiwqlkelo.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.chenlongwang.top/Article/details/gtcqzaggyk.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hnqzz.top/Article/details/gtbejddplm.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.birdmap.top/Article/details/gtoxjwtqti.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.meibo888.top/Article/details/gtcmxikifr.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gtltoeqcct.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.birdmap.top/Article/details/gtageioocu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.kuanghao11.cn/Article/details/gtcqulppjv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hammf.cn/Article/details/gtpewyfpqp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhongyouzk.top/Article/details/gttfhrxlgp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.gaohongyu789.top/Article/details/gtjjjkkect.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hammf.cn/Article/details/gtaglvscdq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhixingplan.top/Article/details/gtqdfdyzum.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yangfankeji.com/Article/details/gtzcycetjp.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gtmegmkhla.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.vqdsnc.cn/Article/details/gtldtntiiz.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtwezaopnj.html

A. 基础语法与类型
来源：http://dali.ppjwa.cn/Article/details/gtjlwachad.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtehsxmrxd.html

[A01] Hello World
来源：http://dali.chenlongwang.top/Article/details/gtogrqyehg.html

Py:   print("Hello, World!")
来源：http://dali.sysykeji.top/Article/details/gtndslckjx.html

PHP:  echo "Hello, World!";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcaxvozzi.html

JS:   console.log("Hello, World!");
来源：http://dali.fengsongda.top/Article/details/gtpenowlcf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegxskrcf.html

Java: System.out.println("Hello, World!");
来源：http://dali.yanxiufei.cn/Article/details/gtdmigrxwi.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.feifeiyinyue.top/Article/details/gtrmcntich.html

Ruby: puts "Hello, World!"
来源：http://dali.daria6918.cn/Article/details/gtsvbtkkvq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.iojbl.cn/Article/details/gthkhqreuj.html

[A02] 变量声明与赋值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfigruhkg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yongpay.top/Article/details/gtmgbszmus.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.nanxinkj.top/Article/details/gtokfujapg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.fzhhl.top/Article/details/gtmclmouup.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.0kj1m.cn/Article/details/gtxcomaena.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xylfe.cn/Article/details/gtxqozpuqt.html

Go:   name := "Alex"; age := 20
来源：http://dali.nwbrower.top/Article/details/gtmstdeafp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.quarkkingdee.top/Article/details/gtdhbctwls.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yonumen.top/Article/details/gtopqkionp.html

[A03] 常量定义
来源：http://dali.hnxiangtu.top/Article/details/gtlvtdodxa.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikqdwiij.html

PHP:  const PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtarlkbepp.html

JS:   const PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtvnsswjut.html

TS:   const PI: number = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtvobxsend.html

Java: static final double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtgjsqpqha.html

Go:   const PI = 3.14159
来源：http://dali.daxiang520.top/Article/details/gtwegwdgbg.html

Ruby: PI = 3.14159
来源：http://dali.ydzc1.top/Article/details/gtazyelmgy.html

C#:   const double PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtwwualuwg.html

[A04] 判断变量类型
来源：http://dali.yj20258.top/Article/details/gtibogzadm.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.tian-w.cn/Article/details/gtxusnwbyq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.sufxvd.cn/Article/details/gtuscykldl.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.daria6918.cn/Article/details/gtzhylwuky.html

TS:   typeof x; x instanceof Date
来源：http://dali.316326.xyz/Article/details/gtzdloumum.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jianghu66.top/Article/details/gtfubechpk.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.snrcjt.cn/Article/details/gtkzieduqx.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.316326.xyz/Article/details/gtygezqhyb.html

C#:   x.GetType().Name; x is int
来源：http://dali.fengsongda.top/Article/details/gtxnxgxexs.html

[A05] 整数除法与取模
来源：http://dali.zhoulong.xyz/Article/details/gtbrvwadns.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.smart0.xyz/Article/details/gtnbfkrhgi.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.iojbl.cn/Article/details/gttqlonvjr.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtkmkhztly.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.c1oappe.top/Article/details/gtevfzxfrg.html

Java: 7 / 2; 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gtkordkrpw.html

Go:   7 / 2; 7 % 2
来源：http://dali.yj202588.top/Article/details/gtsabrgnwd.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xylfe.cn/Article/details/gtplaotylq.html

C#:   7 / 2; 7 % 2
来源：http://dali.sysykeji.top/Article/details/gtyqkgsdpr.html

[A06] 字符串转数字
来源：http://dali.shuidangran.top/Article/details/gtcxwqwklc.html

Py:   int("42"); float("3.14")
来源：http://dali.ydzc1.top/Article/details/gtqofmudhg.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.dashuyun.cn/Article/details/gtojuiqhpi.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.wangshuangyany.cn/Article/details/gtqwprthtz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.fengsongda.top/Article/details/gtzpreujdj.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cheryme.top/Article/details/gtzxexsmzf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhengqikj.top/Article/details/gtjzawqrqd.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yj202588.top/Article/details/gtxmyhavaj.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.chenzaomai.com/Article/details/gtpouynriy.html

[A07] 数字转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtigorfjsv.html

Py:   str(42)
来源：http://dali.cashguo.top/Article/details/gthrbpwfbc.html

PHP:  (string) 42; strval(42)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdveazjd.html

JS:   String(42); (42).toString()
来源：http://dali.yj202588.top/Article/details/gtcbrvbvxh.html

TS:   String(42)
来源：http://dali.sufxvd.cn/Article/details/gtjwhfvmsv.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.snrcjt.cn/Article/details/gttlesaybv.html

Go:   strconv.Itoa(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydojmckk.html

Ruby: 42.to_s
来源：http://dali.ybcxt.top/Article/details/gtwgmvermc.html

C#:   42.ToString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkrwlrpo.html

[A08] 取整与四舍五入
来源：http://dali.xuanzx.com/Article/details/gtqbrjowoq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.tian-w.cn/Article/details/gtdceongoq.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.cucudq.cn/Article/details/gtuxernhbm.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yuxming.cn/Article/details/gtvzxnsxqt.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjvgiryw.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.pycfn.com/Article/details/gtwdcbwkxf.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.dashuyun.cn/Article/details/gtqcbxzydq.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.haohaochexian.top/Article/details/gtgqnowgtr.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.316326.xyz/Article/details/gtptzlujfm.html

[A09] 绝对值与最大最小值
来源：http://dali.yangfankeji.com/Article/details/gtfuxxjflo.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gtpgqhikxp.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.c1oappe.top/Article/details/gtzrnpsgrb.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.xuanzx.com/Article/details/gtgylwygnz.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yvedp.cn/Article/details/gtnkvnwuit.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yueranfly.top/Article/details/gtuxccxceu.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hnxiangtu.top/Article/details/gtiwuaqdnq.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.cashguo.top/Article/details/gtagzlnlws.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gtlgclfhaf.html

[A10] 生成随机数
来源：http://dali.ppjwa.cn/Article/details/gtdxefcdoi.html

Py:   import random; random.randint(1, 100)
来源：http://dali.snrcjt.cn/Article/details/gtohuuurys.html

PHP:  random_int(1, 100);
来源：http://dali.yuxming.cn/Article/details/gtdifrdqaq.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ppjwa.cn/Article/details/gtsrespetg.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdmjtwfx.html

Java: new Random().nextInt(100) + 1
来源：http://dali.gogol.net.cn/Article/details/gtibzuvxog.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.pengpengdd.cyou/Article/details/gtbyemzmox.html

Ruby: rand(1..100)
来源：http://dali.daxiang520.top/Article/details/gtituvectk.html

C#:   new Random().Next(1, 101)
来源：http://dali.wangdashe.top/Article/details/gtlcowqntr.html

[A11] 条件表达式（三元）
来源：http://dali.pycfn.com/Article/details/gtyotpvart.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjexvvav.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hammf.cn/Article/details/gtuappqgbh.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.havefunace.top/Article/details/gtudojvdqe.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.ehwqpu.com/Article/details/gtlvapnwxw.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xziqi.cn/Article/details/gtvxnwwztf.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.guowangkeji.top/Article/details/gtpqytutrq.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.quarkkingdee.top/Article/details/gtasxnombj.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.0kj1m.cn/Article/details/gtrohjnccg.html

[A12] 字符串插值 / 格式化
来源：http://dali.jqgufenzy.top/Article/details/gtvopiuczp.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.wangdashe.top/Article/details/gtcmhdbchk.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.sysykeji.top/Article/details/gtdrcwubzz.html

JS:   `Hello, ${name}!`
来源：http://dali.xylfe.cn/Article/details/gtiawtwhnj.html

TS:   `Hello, ${name}!`
来源：http://dali.0kj1m.cn/Article/details/gtlzktkisn.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.hfpthk.cn/Article/details/gthwwfkods.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.guowangkeji.top/Article/details/gtyefdpidp.html

Ruby: "Hello, #{name}!"
来源：http://dali.yonumen.top/Article/details/gtofjxqtpc.html

C#:   $"Hello, {name}!"
来源：http://dali.jqgfzy.top/Article/details/gtxjjgheqy.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.hnxiangtu.top/Article/details/gtlazjrerq.html

Py:   "第一行\n第二行"
来源：http://dali.sufxvd.cn/Article/details/gthtyzuajp.html

PHP:  "第一行\n第二行"
来源：http://dali.jinqigfzy.top/Article/details/gtbwcywuye.html

JS:   "第一行\n第二行"
来源：http://dali.ivvv.top/Article/details/gtrlhqdjar.html

TS:   "第一行\n第二行"
来源：http://dali.316326.xyz/Article/details/gtqmklibqw.html

Java: "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gtprjodczz.html

Go:   "第一行\n第二行"
来源：http://dali.cashguo.top/Article/details/gtcmuenbys.html

Ruby: "第一行\n第二行"
来源：http://dali.gaohongyu789.top/Article/details/gtokrwmotx.html

C#:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gtzdqpvhau.html

[A14] 注释写法
来源：http://dali.jinqigufen.top/Article/details/gtxxcqzeuj.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jqgfzy.top/Article/details/gtehuzpkgr.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yuanzhike.top/Article/details/gtfamlcloe.html

JS:   // 单行；/* 多行 */
来源：http://dali.wangshuangyany.cn/Article/details/gtfkgbmkdc.html

TS:   // 单行；/* 多行 */
来源：http://dali.316326.xyz/Article/details/gtvukibfjf.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.meibo888.top/Article/details/gtllgomscm.html

Go:   // 单行；/* 多行 */
来源：http://dali.jyoumei.cn/Article/details/gtriuvdscg.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yvedp.cn/Article/details/gtkcqwknkx.html

C#:   // 单行；/* 多行 */
来源：http://dali.ppjwa.cn/Article/details/gteqrojklg.html

[A15] 空值判断与默认值
来源：http://dali.cucudq.cn/Article/details/gtepwuokit.html

Py:   value = data or "默认值"
来源：http://dali.zhiwuduotai.top/Article/details/gtrnssquxo.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.haohaochexian.top/Article/details/gtaalphawy.html


<!-- 参考信息 -->