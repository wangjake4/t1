代发 wailian999

[U95] JS：Promise 包装
来源：http://dali.dashuyun.cn/Article/details/gt2qkqkzpaz.html

new Promise((resolve, reject) => {})
来源：http://dali.jiagoushi.top/Article/details/gt2txuawiku.html

[U96] JS：async/await 与异常
来源：http://dali.xylfe.cn/Article/details/gt2vptbzgha.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gt2ypsalkeo.html

[U97] JS：并发请求
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lcfkucfc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gt2apdjxneu.html

[U98] JS：fetch 带 JSON
来源：http://dali.gotoacloud.top/Article/details/gt2cfvcgugq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hammf.cn/Article/details/gt2atdioumm.html

[U99] JS：事件监听
来源：http://dali.chenlongwang.top/Article/details/gt2tdwkcdft.html

el.addEventListener("click", e => {})
来源：http://dali.316326.xyz/Article/details/gt2fokpxten.html

[U100] JS：DOM 查询
来源：http://dali.dashuyun.cn/Article/details/gt2oiuimipx.html

document.querySelector(".item")
来源：http://dali.daxiang520.top/Article/details/gt2xewnxedu.html

[U101] JS：classList 操作
来源：http://dali.hywenlv.cn/Article/details/gt2psvoztwk.html

el.classList.toggle("active")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nvsrbzwy.html

[U102] JS：本地存储
来源：http://dali.sufxvd.cn/Article/details/gt2mgdrpkdc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.kuanghao11.cn/Article/details/gt2nxkuouwn.html

[U103] JS：定时器
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lyneypgz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.316326.xyz/Article/details/gt2kvoqiprm.html

[U104] JS：防抖
来源：http://dali.yuanzhike.top/Article/details/gt2vzfcwjld.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gt2mxelmgwe.html

[U105] JS：节流
来源：http://dali.daria6918.cn/Article/details/gt2oitagrqf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.smart0.xyz/Article/details/gt2wovodnco.html

[U106] JS：日期格式化
来源：http://dali.aibaodan.cn/Article/details/gt2fviyfpri.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.havefunace.top/Article/details/gt2zarvxabc.html

[U107] JS：数字千分位
来源：http://dali.nanxinkj.top/Article/details/gt2htkigkok.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yongpay.top/Article/details/gt2ifoqqhoz.html

[U108] JS：随机整数
来源：http://dali.hywenlv.cn/Article/details/gt2orjuftmt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zycfv.cn/Article/details/gt2pdfnhuhu.html

[U109] JS：数组分组
来源：http://dali.hnqzz.top/Article/details/gt2gfljazar.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gt2xayqvinw.html

[U110] JS：数组分块
来源：http://dali.yongpay.top/Article/details/gt2qfwrnvsn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.guowangkeji.top/Article/details/gt2hdlnerzs.html

[U111] JS：对象转 Map
来源：http://dali.wangshuangyany.cn/Article/details/gt2ggrnwgyx.html

new Map(Object.entries(obj))
来源：http://dali.sxryk.cn/Article/details/gt2cpicnzra.html

[U112] JS：字符串补位
来源：http://dali.daria6918.cn/Article/details/gt2nbdwjkvv.html

"7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gt2smghyjcu.html

[U113] JS：正则替换全部
来源：http://dali.dianchejie.cn/Article/details/gt2qpcquuko.html

s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gt2tjqauxlu.html

[U114] JS：JSON 深比较
来源：http://dali.daria6918.cn/Article/details/gt2avwmygdb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guowangkeji.top/Article/details/gt2rweufoks.html

[U115] JS：生成 UUID
来源：http://dali.daria6918.cn/Article/details/gt2tfsitfej.html

crypto.randomUUID()
来源：http://dali.sufxvd.cn/Article/details/gt2chqggnqj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.guannengcc.top/Article/details/gt2qdafslvp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ybcxt.top/Article/details/gt2gygjztve.html

[U117] JS：单元测试
来源：http://dali.cashguo.top/Article/details/gt2sqfgbrqs.html

npm i -D vitest;  npx vitest
来源：http://dali.nwbrower.top/Article/details/gt2cvqcdnko.html

[U118] JS：开发服务器
来源：http://dali.bjfxy.top/Article/details/gt2jvukktkq.html

npm i -D vite;  npx vite
来源：http://dali.fzhhl.top/Article/details/gt2bzeyizjq.html

[U119] JS：生产构建
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ownblvat.html

npx vite build
来源：http://dali.yj20258888.top/Article/details/gt2wxzwnlci.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2zslsgnec.html

import.meta.env.VITE_API_URL
来源：http://dali.gaohongyu789.top/Article/details/gt2jkofsary.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vykzkpey.html

统计汇总
来源：http://dali.zhoulong.xyz/Article/details/gt2dnfnxdce.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2xamsfwfg.html

按语言统计（条）：
来源：http://dali.nwbrower.top/Article/details/gt2xdovvhva.html

Python ......... 252
来源：http://dali.sysykeji.top/Article/details/gt2rbqsrcvk.html

PHP ............ 252
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hpypyzpt.html

JavaScript ..... 252
来源：http://dali.svipenyu.cn/Article/details/gt2lssuszgs.html

TypeScript ..... 212
来源：http://dali.jiagoushi.top/Article/details/gt2gsoewiog.html

Java ........... 212
来源：http://dali.ivvv.top/Article/details/gt2pjgvzsyg.html

Go ............. 212
来源：http://dali.nwbrower.top/Article/details/gt2xwncfahe.html

Ruby ........... 212
来源：http://dali.chenjidiqi.icu/Article/details/gt2xeqigjob.html

C# ............. 212
来源：http://dali.vqdsnc.cn/Article/details/gt2matzzurm.html

C .............. 30
来源：http://dali.ehwqpu.com/Article/details/gt2mqcwwoaz.html

C++ ............ 30
来源：http://dali.cqqwz.cn/Article/details/gt2bhfovdpf.html

SQL ............ 90
来源：http://dali.chenlongwang.top/Article/details/gt2jnmcpgbl.html

Bash ........... 80
来源：http://dali.xinyue.icu/Article/details/gt2cobisglm.html

Kotlin ......... 15
来源：http://dali.ivvv.top/Article/details/gt2emvbkado.html

Swift .......... 15
来源：http://dali.gogol.net.cn/Article/details/gt2ghaguczi.html

Lua ............ 10
来源：http://dali.haohaochexian.top/Article/details/gt2umfzlsqb.html

Perl ........... 10
来源：http://dali.hongshengwenyu.top/Article/details/gt2zvtrxxna.html

Scala .......... 10
来源：http://dali.chenjidiqi.icu/Article/details/gt2loimtspx.html

------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gt2ygefnole.html

合计 ........... 2106 条
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hrhbifvm.html

按章节统计：
来源：http://dali.cheryme.top/Article/details/gt2huiwkvwq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yueranfly.top/Article/details/gt2wglcmytf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhiwuduotai.top/Article/details/gt2wxqpevtc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ydzc1.top/Article/details/gt2kppbjinq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cucudq.cn/Article/details/gt2kkynnswv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.wangdashe.top/Article/details/gt2eirpqekb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.wangshuangyany.cn/Article/details/gt2iqpnicsv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.andypj.xyz/Article/details/gt2rgsxpifj.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.fengsongda.top/Article/details/gt2zcejuuvc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gt2xeszohcr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tvqdxruy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gt2kjkrlbgj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gt2tjsnigbr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gt2ggrkbmck.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jiagoushi.top/Article/details/gt2xvxrzbtm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.pycfn.com/Article/details/gt2wsmxefwy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tzhajxks.html

Q SQL 专题                              90
来源：http://dali.wangdashe.top/Article/details/gt2zksscbch.html

R Bash 专题                             80
来源：http://dali.svipenyu.cn/Article/details/gt2ywudwing.html

S C / C++ 专题                          60
来源：http://dali.yuanzhike.top/Article/details/gt2yvuxxxyc.html

T 其他语言补充                          60
来源：http://dali.yonumen.top/Article/details/gt2srfgzmsi.html

U 高频实用片段                         120
来源：http://dali.aizwys.cn/Article/details/gt2zkemjmra.html

------------------------------------
来源：http://dali.sweek.top/Article/details/gt2hxzcyujq.html

合计                                  2106 条
来源：http://dali.jlsjyb.cn/Article/details/gt2oqgggxlz.html

--------------------------------------------------------------------------------
来源：http://dali.jianghu66.top/Article/details/gt2bzexrqwg.html

使用提醒
来源：http://dali.haohaochexian.top/Article/details/gt2orsbxyni.html

--------------------------------------------------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gt2mfkupryg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.0kj1m.cn/Article/details/gt2qvuydtzl.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.shangyingyoupin.top/Article/details/gt2bctqoaso.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.vqdsnc.cn/Article/details/gt2owknegum.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yj20258888.top/Article/details/gt2shrfvuzq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.nanxinkj.top/Article/details/gt2bslnkkam.html

—— 文件结束 ——
来源：http://dali.jqgufenzy.top/Article/details/gt2huekmlpa.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2gpgsgdiz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.sweek.top/Article/details/gt2zbmnhnhb.html

Common Programming Examples Cheat Book
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pnpmkcmf.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2okbqrmuw.html

【收录内容】
来源：http://dali.yuxming.cn/Article/details/gt2mepifxrx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.smart0.xyz/Article/details/gt2hmvicigb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.vqdsnc.cn/Article/details/gt2lhaaqnby.html

SQL · Bash · C · C++
来源：http://dali.smart0.xyz/Article/details/gt2hwknavxs.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2jyajyqjd.html

【使用说明】
来源：http://dali.zhoulong.xyz/Article/details/gt2felgqtvf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhongyouzk.top/Article/details/gt2eaeggcop.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lczophdp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xuetiantiany.cn/Article/details/gt2xqilrltf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.daxiang520.top/Article/details/gt2medrpixo.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.sysykeji.top/Article/details/gt2kivhzxde.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yvedp.cn/Article/details/gt2pqrqvrxa.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.aibaodan.cn/Article/details/gt2bmxpznzh.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgxccjv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shzxlz.cn/Article/details/gt2bgoaqwcs.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.kuanghao11.cn/Article/details/gt2osdfugky.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yueranfly.top/Article/details/gt2jkwbuwwr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.chenlongwang.top/Article/details/gt2uvqvnmex.html

【文件统计】
来源：http://dali.iojbl.cn/Article/details/gt2aaushiyh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.birdmap.top/Article/details/gt2uyyiyrwy.html

--------------------------------------------------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gt2csamscex.html

目  录
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wpgojgre.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gt2yfkuvixb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yueranfly.top/Article/details/gt2tbpavipg.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.aizwys.cn/Article/details/gt2towlfucm.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2ogqclxbn.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iiuttdmz.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2dtfahvgs.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.cqqwz.cn/Article/details/gt2wtokxcrl.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2ukbclnlk.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yonumen.top/Article/details/gt2gtdcotav.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gt2gxbggyfo.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.aibaodan.cn/Article/details/gt2vtcjotkn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.cdnleiting.top/Article/details/gt2msjivwrh.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gt2kcjlhbeb.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gt2drteijyq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hnqzz.top/Article/details/gt2dmaqkwuq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2lhnscnfw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.bjfxy.top/Article/details/gt2iprqhute.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ivvv.top/Article/details/gt2ldxlqiws.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.tian-w.cn/Article/details/gt2wekpncwt.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.tanke756.top/Article/details/gt2zeijxqwx.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yangfankeji.com/Article/details/gt2huumekif.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.mhx1999.top/Article/details/gt2cmthptev.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2vlhndwea.html

A. 基础语法与类型
来源：http://dali.yanxiufei.cn/Article/details/gt2kknvpyzt.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2zyjgehgf.html

[A01] Hello World
来源：http://dali.xylfe.cn/Article/details/gt2jcbbujda.html

Py:   print("Hello, World!")
来源：http://dali.ivvv.top/Article/details/gt2szzqyazy.html

PHP:  echo "Hello, World!";
来源：http://dali.yuxming.cn/Article/details/gt2mqfzgxlw.html

JS:   console.log("Hello, World!");
来源：http://dali.daria6918.cn/Article/details/gt2xpzqlesj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.c1oappe.top/Article/details/gt2tdctkxyq.html

Java: System.out.println("Hello, World!");
来源：http://dali.ybcxt.top/Article/details/gt2rlznhgvf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xylfe.cn/Article/details/gt2tzvwzird.html

Ruby: puts "Hello, World!"
来源：http://dali.hnxiangtu.top/Article/details/gt2ldkoifjt.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.sufxvd.cn/Article/details/gt2rfshxqck.html

[A02] 变量声明与赋值
来源：http://dali.zycfv.cn/Article/details/gt2sennqhqk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.nwbrower.top/Article/details/gt2bllztfan.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yuxming.cn/Article/details/gt2ssetawye.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ejztvsqw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhongyouzk.top/Article/details/gt2payfnqvm.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.redwolf501.top/Article/details/gt2gntrajur.html

Go:   name := "Alex"; age := 20
来源：http://dali.xuetiantiany.cn/Article/details/gt2hsumknnk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.tianlin.xyz/Article/details/gt2ozlsqoqa.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hnqzz.top/Article/details/gt2nyuzjase.html

[A03] 常量定义
来源：http://dali.svipenyu.cn/Article/details/gt2hzumarnv.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhoulong.xyz/Article/details/gt2ugwnjnpt.html

PHP:  const PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cimmxmyv.html

JS:   const PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gt2uowfagkr.html

TS:   const PI: number = 3.14159;
来源：http://dali.yj202588.top/Article/details/gt2kywjkkch.html

Java: static final double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gt2ulbbcidt.html

Go:   const PI = 3.14159
来源：http://dali.snrcjt.cn/Article/details/gt2bnrmorvd.html

Ruby: PI = 3.14159
来源：http://dali.fzhhl.top/Article/details/gt2vjswcyfp.html

C#:   const double PI = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gt2tebnfkdy.html

[A04] 判断变量类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2juzpfsea.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xuanzx.com/Article/details/gt2pllhiuyz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yj20258.top/Article/details/gt2iswcftkn.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.tanke756.top/Article/details/gt2lrcocqpj.html

TS:   typeof x; x instanceof Date
来源：http://dali.cheryme.top/Article/details/gt2tibdrkml.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jqgufenzy.top/Article/details/gt2trnppacd.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.redwolf501.top/Article/details/gt2qttqnlat.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.snrcjt.cn/Article/details/gt2qinntfqa.html

C#:   x.GetType().Name; x is int
来源：http://dali.pycfn.com/Article/details/gt2setvoitj.html

[A05] 整数除法与取模
来源：http://dali.cashguo.top/Article/details/gt2bkhketuk.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cucudq.cn/Article/details/gt2tzvlhcno.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.guowangkeji.top/Article/details/gt2zkvtjrtz.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.mhx1999.top/Article/details/gt2owlggnsw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cucudq.cn/Article/details/gt2ihnilkyd.html

Java: 7 / 2; 7 % 2
来源：http://dali.bjfxy.top/Article/details/gt2mzlfevzy.html

Go:   7 / 2; 7 % 2
来源：http://dali.guannengcc.top/Article/details/gt2zxwahtci.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yonumen.top/Article/details/gt2iziajvnz.html

C#:   7 / 2; 7 % 2
来源：http://dali.sysykeji.top/Article/details/gt2oedcibbc.html

[A06] 字符串转数字
来源：http://dali.zycfv.cn/Article/details/gt2abbgtosc.html

Py:   int("42"); float("3.14")
来源：http://dali.zhongyouzk.top/Article/details/gt2zzgdnxcf.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yj20258.top/Article/details/gt2wsxjbetn.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hammf.cn/Article/details/gt2ipdyfbvp.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.guowangkeji.top/Article/details/gt2nxuqocmh.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jiagoushi.top/Article/details/gt2ujvnubuj.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kqdpxdkn.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.guowangkeji.top/Article/details/gt2oojijgrp.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.chenlongwang.top/Article/details/gt2dnihtufr.html

[A07] 数字转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wgximigu.html

Py:   str(42)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2puukzhoq.html

PHP:  (string) 42; strval(42)
来源：http://dali.shuidangran.top/Article/details/gt2fnuiewog.html

JS:   String(42); (42).toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ynzqrevt.html

TS:   String(42)
来源：http://dali.andypj.xyz/Article/details/gt2vrpkutqi.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.pycfn.com/Article/details/gt2cdobiset.html

Go:   strconv.Itoa(42)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zaegvpjx.html

Ruby: 42.to_s
来源：http://dali.ydzc1.top/Article/details/gt2ndjkduwt.html

C#:   42.ToString()
来源：http://dali.yongpay.top/Article/details/gt2cjgwwuls.html

[A08] 取整与四舍五入
来源：http://dali.9152youxi.cn/Article/details/gt2vwxcufer.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.haohaochexian.top/Article/details/gt2gbuytvwo.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.redwolf501.top/Article/details/gt2dpiqmmzn.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.snrcjt.cn/Article/details/gt2jombeekh.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yvedp.cn/Article/details/gt2vzcfdjzs.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.wangdashe.top/Article/details/gt2utbawqqp.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.birdmap.top/Article/details/gt2ehfznwho.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jinqigfzy.top/Article/details/gt2bbesdbgi.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jinqigufen.top/Article/details/gt2qqgtshhh.html

[A09] 绝对值与最大最小值
来源：http://dali.hywenlv.cn/Article/details/gt2kzyaypit.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2mokxwwsn.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wkzgsoas.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.gzhubu.top/Article/details/gt2lvnnzmvb.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.bjfxy.top/Article/details/gt2bbublkex.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2enetbqqp.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhengqikj.top/Article/details/gt2cplluqos.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.wangdashe.top/Article/details/gt2rqsdcgbs.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2wevxzjwc.html

[A10] 生成随机数
来源：http://dali.sweek.top/Article/details/gt2qfslacdf.html

Py:   import random; random.randint(1, 100)
来源：http://dali.gzhubu.top/Article/details/gt2dpnhxuww.html

PHP:  random_int(1, 100);
来源：http://dali.yj20258.top/Article/details/gt2blvskmaj.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2euyempda.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.tanke756.top/Article/details/gt2ntcogjoj.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zdqjudy.top/Article/details/gt2xcmpibti.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhongyouzk.top/Article/details/gt2ufnpgikt.html

Ruby: rand(1..100)
来源：http://dali.cheryme.top/Article/details/gt2hhzegzyd.html

C#:   new Random().Next(1, 101)
来源：http://dali.xuanzx.com/Article/details/gt2celvhjaa.html

[A11] 条件表达式（三元）
来源：http://dali.pengpengdd.cyou/Article/details/gt2etocxuef.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vilewksz.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.andypj.xyz/Article/details/gt2jwpjvmby.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.hywenlv.cn/Article/details/gt2ivozrdff.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.gzhubu.top/Article/details/gt2jvuvcrzj.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.tianlin.xyz/Article/details/gt2xaiboapo.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.fengsongda.top/Article/details/gt2zdofvqew.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.shangyingyoupin.top/Article/details/gt2orppzvlu.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.sweek.top/Article/details/gt2owxlvcdk.html

[A12] 字符串插值 / 格式化
来源：http://dali.tianlin.xyz/Article/details/gt2opvitccr.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.birdmap.top/Article/details/gt2wnrrbqwz.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.dashuyun.cn/Article/details/gt2grnffkjm.html

JS:   `Hello, ${name}!`
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ksqgxvrc.html

TS:   `Hello, ${name}!`
来源：http://dali.bjfxy.top/Article/details/gt2rxarxgxc.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.gzhubu.top/Article/details/gt2wsbgklbg.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xeurnmct.html

Ruby: "Hello, #{name}!"
来源：http://dali.mhx1999.top/Article/details/gt2jksewgid.html

C#:   $"Hello, {name}!"
来源：http://dali.tianlin.xyz/Article/details/gt2wviftwdl.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.hongshengwenyu.top/Article/details/gt2mdfdlrjq.html

Py:   "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gt2flipdpzx.html

PHP:  "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gt2tlhufapn.html

JS:   "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gt2ynatgxgu.html

TS:   "第一行\n第二行"
来源：http://dali.xziqi.cn/Article/details/gt2qnsxogmt.html

Java: "第一行\n第二行"
来源：http://dali.wangdashe.top/Article/details/gt2bzjpuoht.html

Go:   "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gt2zrowtmbz.html

Ruby: "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gt2mvccgefn.html

C#:   "第一行\n第二行"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ayhujgjm.html

[A14] 注释写法
来源：http://dali.0kj1m.cn/Article/details/gt2sybxullz.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.cucudq.cn/Article/details/gt2eghaoctk.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jqgfzy.top/Article/details/gt2wumxzajv.html

JS:   // 单行；/* 多行 */
来源：http://dali.yongpay.top/Article/details/gt2nzzoppsz.html

TS:   // 单行；/* 多行 */
来源：http://dali.cashguo.top/Article/details/gt2flmwmbmd.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hongshengwenyu.top/Article/details/gt2wrqrpcbq.html

Go:   // 单行；/* 多行 */
来源：http://dali.pycfn.com/Article/details/gt2pgfhqpsb.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.shuidangran.top/Article/details/gt2ordbxrsr.html

C#:   // 单行；/* 多行 */
来源：http://dali.yonumen.top/Article/details/gt2aeitesjb.html

[A15] 空值判断与默认值
来源：http://dali.shzxlz.cn/Article/details/gt2jnzadxrb.html

Py:   value = data or "默认值"
来源：http://dali.xinyue.icu/Article/details/gt2rjjzsqwk.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.cqqwz.cn/Article/details/gt2rmfqbuht.html

JS:   const value = data ?? "默认值";
来源：http://dali.chenjidiqi.icu/Article/details/gt2qlwoliip.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhixingplan.top/Article/details/gt2jxbxxtah.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.gaohongyu789.top/Article/details/gt2iknhnvka.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.ehwqpu.com/Article/details/gt2vikmbdmr.html

Ruby: value = data || "默认值"
来源：http://dali.fengsongda.top/Article/details/gt2jiajwgee.html

C#:   var value = data ?? "默认值";
来源：http://dali.hywenlv.cn/Article/details/gt2adeowrwz.html

[A16] 真假值判断规则
来源：http://dali.sweek.top/Article/details/gt2fptuaquf.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.xuanzx.com/Article/details/gt2vuvmlptb.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhiwuduotai.top/Article/details/gt2nqjbuiph.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.ydzc1.top/Article/details/gt2ualnxspj.html

TS:   if (!x) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2gstmmkjl.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2etqumvbf.html


<!-- 参考信息 -->