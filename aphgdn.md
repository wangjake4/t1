代发 wailian999

[U93] JS：模板字符串
来源：http://dali.havefunace.top/Article/details/gtriswooti.html

`共 ${n} 条`
来源：http://dali.andypj.xyz/Article/details/gtboakvjwb.html

[U94] JS：箭头函数
来源：http://dali.jyoumei.cn/Article/details/gtkqwdjiul.html

const double = x => x * 2;
来源：http://dali.jqgufenzy.top/Article/details/gtkvldvdcg.html

[U95] JS：Promise 包装
来源：http://dali.havefunace.top/Article/details/gtihifcphz.html

new Promise((resolve, reject) => {})
来源：http://dali.cashguo.top/Article/details/gtgksbdzkx.html

[U96] JS：async/await 与异常
来源：http://dali.jqgufenzy.top/Article/details/gtqmcpokzj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gtzxauhhae.html

[U97] JS：并发请求
来源：http://dali.bjfxy.top/Article/details/gtwhrjzqjk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtinbitill.html

[U98] JS：fetch 带 JSON
来源：http://dali.mhx1999.top/Article/details/gtiaiebpjg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.daria6918.cn/Article/details/gtaxwcvhnf.html

[U99] JS：事件监听
来源：http://dali.sweek.top/Article/details/gtcgfodggm.html

el.addEventListener("click", e => {})
来源：http://dali.316326.xyz/Article/details/gtnpsbbxaa.html

[U100] JS：DOM 查询
来源：http://dali.daria6918.cn/Article/details/gtyumxkaev.html

document.querySelector(".item")
来源：http://dali.chenzaomai.com/Article/details/gteydktvfw.html

[U101] JS：classList 操作
来源：http://dali.cucudq.cn/Article/details/gtndyuezqh.html

el.classList.toggle("active")
来源：http://dali.316326.xyz/Article/details/gthatzinkx.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gtoucixjqd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.tianlin.xyz/Article/details/gthpaxxkkn.html

[U103] JS：定时器
来源：http://dali.jyoumei.cn/Article/details/gtsjzvokqo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.pycfn.com/Article/details/gtrgjghbxw.html

[U104] JS：防抖
来源：http://dali.hnxiangtu.top/Article/details/gtdhiuddww.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gtexcmgnzj.html

[U105] JS：节流
来源：http://dali.yuxming.cn/Article/details/gtbkkmhiqb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xylfe.cn/Article/details/gtjbpazxjx.html

[U106] JS：日期格式化
来源：http://dali.birdmap.top/Article/details/gtmrnbdsmn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.nanxuanxn.top/Article/details/gtpqnqdekn.html

[U107] JS：数字千分位
来源：http://dali.cdnleiting.top/Article/details/gtvhoxtkga.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shzxlz.cn/Article/details/gtopcbptly.html

[U108] JS：随机整数
来源：http://dali.xinyue.icu/Article/details/gtfqwzrjtl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jqgufenzy.top/Article/details/gtvgrhjyrl.html

[U109] JS：数组分组
来源：http://dali.nanxinkj.top/Article/details/gtwmpsuuyb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hammf.cn/Article/details/gtzqggzmrr.html

[U110] JS：数组分块
来源：http://dali.cqqwz.cn/Article/details/gtnzofocwj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zdqjudy.top/Article/details/gtvqiupaza.html

[U111] JS：对象转 Map
来源：http://dali.andypj.xyz/Article/details/gteawkauff.html

new Map(Object.entries(obj))
来源：http://dali.vqdsnc.cn/Article/details/gtyugmzhfq.html

[U112] JS：字符串补位
来源：http://dali.dashuyun.cn/Article/details/gtguswffml.html

"7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtnaxfxiee.html

[U113] JS：正则替换全部
来源：http://dali.cucudq.cn/Article/details/gtdyjwauwn.html

s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtdtwntwlr.html

[U114] JS：JSON 深比较
来源：http://dali.yj20258888.top/Article/details/gtomazherq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gogol.net.cn/Article/details/gtzgzjinug.html

[U115] JS：生成 UUID
来源：http://dali.gzhubu.top/Article/details/gtdmqzzufa.html

crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtrlbdwtbz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.snrcjt.cn/Article/details/gtibawsotd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhongyouzk.top/Article/details/gtncdrijbm.html

[U117] JS：单元测试
来源：http://dali.havefunace.top/Article/details/gtwlljcsyy.html

npm i -D vitest;  npx vitest
来源：http://dali.zhengqikj.top/Article/details/gtredpwbwt.html

[U118] JS：开发服务器
来源：http://dali.iojbl.cn/Article/details/gtlypfghxh.html

npm i -D vite;  npx vite
来源：http://dali.cdnleiting.top/Article/details/gttbqbdjcd.html

[U119] JS：生产构建
来源：http://dali.zdqjudy.top/Article/details/gtuccladll.html

npx vite build
来源：http://dali.0kj1m.cn/Article/details/gtcvjuzufl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.birdmap.top/Article/details/gtqpxcphee.html

import.meta.env.VITE_API_URL
来源：http://dali.fengsongda.top/Article/details/gtbsossivh.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtzijyzxom.html

统计汇总
来源：http://dali.yonumen.top/Article/details/gtvyvnbxqh.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtbxwutcpm.html

按语言统计（条）：
来源：http://dali.ydzc1.top/Article/details/gtqysjehgp.html

Python ......... 252
来源：http://dali.hammf.cn/Article/details/gtzeqjjcoy.html

PHP ............ 252
来源：http://dali.aizwys.cn/Article/details/gtzpozkzto.html

JavaScript ..... 252
来源：http://dali.snrcjt.cn/Article/details/gtmyaurhid.html

TypeScript ..... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gtppfastwg.html

Java ........... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzrqmxuw.html

Go ............. 212
来源：http://dali.aizwys.cn/Article/details/gtkuamiden.html

Ruby ........... 212
来源：http://dali.xuetiantiany.cn/Article/details/gtdyuutgtt.html

C# ............. 212
来源：http://dali.chenjidiqi.icu/Article/details/gtunxscthn.html

C .............. 30
来源：http://dali.fzhhl.top/Article/details/gtbzzjqowd.html

C++ ............ 30
来源：http://dali.cucudq.cn/Article/details/gtecjaleif.html

SQL ............ 90
来源：http://dali.jqgfzy.top/Article/details/gtovnnqnpb.html

Bash ........... 80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowgjhoui.html

Kotlin ......... 15
来源：http://dali.guowangkeji.top/Article/details/gtryfxuood.html

Swift .......... 15
来源：http://dali.gaohongyu789.top/Article/details/gtopsjwhcs.html

Lua ............ 10
来源：http://dali.sysykeji.top/Article/details/gtooxqwbys.html

Perl ........... 10
来源：http://dali.birdmap.top/Article/details/gtxbfxlihm.html

Scala .......... 10
来源：http://dali.yangfankeji.com/Article/details/gtjesfvnzb.html

------------------------------------
来源：http://dali.ivvv.top/Article/details/gtskthvbyt.html

合计 ........... 2106 条
来源：http://dali.gaohongyu789.top/Article/details/gtprukxcqk.html

按章节统计：
来源：http://dali.aibaodan.cn/Article/details/gtferutsyl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shanyushiyangkeji.top/Article/details/gtelxbaccb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.0kj1m.cn/Article/details/gtyzmkjdkj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yvedp.cn/Article/details/gtnopvrbwg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gotoacloud.top/Article/details/gtqmvkigke.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xinyue.icu/Article/details/gtsaxxvmpz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jianghu66.top/Article/details/gtqtygfypg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yonumen.top/Article/details/gtxterinsu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gttzmkjfsz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gtmbcfwccp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gotoacloud.top/Article/details/gtiyrtsnvw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gtbmbwmqhd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtvsvknnmz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gtajioxojh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.daxiang520.top/Article/details/gtsmphnewm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yanxiufei.cn/Article/details/gttpxrbdmx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gtbspatdno.html

Q SQL 专题                              90
来源：http://dali.gzhubu.top/Article/details/gtebfktuqy.html

R Bash 专题                             80
来源：http://dali.316326.xyz/Article/details/gtmnnasvpi.html

S C / C++ 专题                          60
来源：http://dali.yanxiufei.cn/Article/details/gthxebtvop.html

T 其他语言补充                          60
来源：http://dali.nwbrower.top/Article/details/gthzmssish.html

U 高频实用片段                         120
来源：http://dali.hongshengwenyu.top/Article/details/gtewdkovge.html

------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gtqotyrfgh.html

合计                                  2106 条
来源：http://dali.zhiwuduotai.top/Article/details/gtbehsewko.html

--------------------------------------------------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gtxpuyxcbr.html

使用提醒
来源：http://dali.dianchejie.cn/Article/details/gtbhbofnrs.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gtmcuiondj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.bjfxy.top/Article/details/gtovzngcim.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.meibo888.top/Article/details/gtyvguovog.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.iojbl.cn/Article/details/gtwxmmoogq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jyoumei.cn/Article/details/gtuwewlwle.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.tanke756.top/Article/details/gtbzltxpjk.html

—— 文件结束 ——
来源：http://dali.zycfv.cn/Article/details/gtgqhezwbg.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtgymjeres.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.guowangkeji.top/Article/details/gtasitaujp.html

Common Programming Examples Cheat Book
来源：http://dali.svipenyu.cn/Article/details/gtwigbvwro.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtzgrbuaru.html

【收录内容】
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqctlhopm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.chenlongwang.top/Article/details/gtpuvxkgpi.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.bjfxy.top/Article/details/gtpltnebxn.html

SQL · Bash · C · C++
来源：http://dali.jyoumei.cn/Article/details/gtdeylkmij.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.gaohongyu789.top/Article/details/gtmzvanbdg.html

【使用说明】
来源：http://dali.jinqigfzy.top/Article/details/gtwwrtbrar.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hnxiangtu.top/Article/details/gtnfndfysg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.iojbl.cn/Article/details/gtyvabzonn.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.gzhubu.top/Article/details/gtavemmmnf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmiwmyyo.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhoulong.xyz/Article/details/gtrsyynyin.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ppjwa.cn/Article/details/gtgnzkiwpn.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.nanxuanxn.top/Article/details/gtgivarqfy.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.andypj.xyz/Article/details/gtbwcjsted.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.gaohongyu789.top/Article/details/gtlpzdbgze.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yuxming.cn/Article/details/gtmedvzbfn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.nwbrower.top/Article/details/gttjuzyyoc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cqqwz.cn/Article/details/gtknqrfpjz.html

【文件统计】
来源：http://dali.cheryme.top/Article/details/gtmuhkfigq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jianghu66.top/Article/details/gtnfhvfpmr.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtfgxpgzkc.html

目  录
来源：http://dali.yj20258888.top/Article/details/gtcdqqqdgc.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcuovpwa.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hywenlv.cn/Article/details/gtkuqlkhpv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.xylfe.cn/Article/details/gtzbjfzyqn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yuxming.cn/Article/details/gtennivndp.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ivvv.top/Article/details/gtwgznpygv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtjmfoeect.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqhryrnc.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jyoumei.cn/Article/details/gttlwenxjs.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yvedp.cn/Article/details/gthjqyefuh.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gtfjihyefb.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvhuxonh.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gtocrqiqit.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gtjjzlapal.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvufjuek.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.nwbrower.top/Article/details/gtdfzathit.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.gzhubu.top/Article/details/gtpaoidiop.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gtuaeywcao.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cdnleiting.top/Article/details/gttpzyjoms.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.meibo888.top/Article/details/gthydeeaov.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yuanzhike.top/Article/details/gtejwtqnam.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gtpdexuhuh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhixingplan.top/Article/details/gthqbjdsss.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtdpnhhydc.html

A. 基础语法与类型
来源：http://dali.jiagoushi.top/Article/details/gtfmmohofw.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtypqehsul.html

[A01] Hello World
来源：http://dali.hammf.cn/Article/details/gteaauechf.html

Py:   print("Hello, World!")
来源：http://dali.cucudq.cn/Article/details/gtiklnlula.html

PHP:  echo "Hello, World!";
来源：http://dali.sufxvd.cn/Article/details/gtpidvmwyg.html

JS:   console.log("Hello, World!");
来源：http://dali.daxiang520.top/Article/details/gtmkrcysbn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jqgufenzy.top/Article/details/gttpnyyzej.html

Java: System.out.println("Hello, World!");
来源：http://dali.hongshengwenyu.top/Article/details/gtvttngddi.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jqgfzy.top/Article/details/gtqssdkony.html

Ruby: puts "Hello, World!"
来源：http://dali.smart0.xyz/Article/details/gtauqosfem.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.sufxvd.cn/Article/details/gtkbsgmios.html

[A02] 变量声明与赋值
来源：http://dali.tanke756.top/Article/details/gtsfncrcso.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.0kj1m.cn/Article/details/gtjrbflgob.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.snrcjt.cn/Article/details/gttyozmncf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yj20258888.top/Article/details/gtitrjhssh.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ydzc1.top/Article/details/gtziquppqq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yongpay.top/Article/details/gtwhewiqrh.html

Go:   name := "Alex"; age := 20
来源：http://dali.tianlin.xyz/Article/details/gtwuumjwam.html

Ruby: name = "Alex"; age = 20
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrscqzlsy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jianghu66.top/Article/details/gtmbilbhut.html

[A03] 常量定义
来源：http://dali.yueranfly.top/Article/details/gtyiwnznla.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.gzhubu.top/Article/details/gtkyfsyvdj.html

PHP:  const PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtjhqdkcvp.html

JS:   const PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtycvjkbak.html

TS:   const PI: number = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gtwwjxeycw.html

Java: static final double PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtxnvzguua.html

Go:   const PI = 3.14159
来源：http://dali.yj202588.top/Article/details/gtxmdalngl.html

Ruby: PI = 3.14159
来源：http://dali.daria6918.cn/Article/details/gtqconijvi.html

C#:   const double PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtsbcdfjws.html

[A04] 判断变量类型
来源：http://dali.xuanzx.com/Article/details/gtcdsxdkps.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jlsjyb.cn/Article/details/gtljhpnuwq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gogol.net.cn/Article/details/gtooanyjub.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yj20258.top/Article/details/gtumycnxhr.html

TS:   typeof x; x instanceof Date
来源：http://dali.snrcjt.cn/Article/details/gtiolhdfnx.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhaomingkeji.xyz/Article/details/gtictuabby.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.gotoacloud.top/Article/details/gttbgfhahs.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yonumen.top/Article/details/gtanmfcyny.html

C#:   x.GetType().Name; x is int
来源：http://dali.sufxvd.cn/Article/details/gtqirfgyse.html

[A05] 整数除法与取模
来源：http://dali.bjfxy.top/Article/details/gtxvhpoapg.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.wangshuangyany.cn/Article/details/gthokxvtma.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.wangdashe.top/Article/details/gtqneqetda.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cucudq.cn/Article/details/gtkrnylhke.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.birdmap.top/Article/details/gtrgiduagl.html

Java: 7 / 2; 7 % 2
来源：http://dali.fzhhl.top/Article/details/gtzeftaewo.html

Go:   7 / 2; 7 % 2
来源：http://dali.yuxming.cn/Article/details/gtnlghnhzj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.wangdashe.top/Article/details/gtykuvwfgs.html

C#:   7 / 2; 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtmjugfnoy.html

[A06] 字符串转数字
来源：http://dali.snrcjt.cn/Article/details/gttfbayyea.html

Py:   int("42"); float("3.14")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfkamaraz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zycfv.cn/Article/details/gtmoopvfgf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.xuetiantiany.cn/Article/details/gtavmxjahs.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.chenjidiqi.icu/Article/details/gtkeloepth.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yongpay.top/Article/details/gtddxhadcc.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.9152youxi.cn/Article/details/gtxpmszuyh.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.tianlin.xyz/Article/details/gtgblqqatd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.chenlongwang.top/Article/details/gtmmbrbcoq.html

[A07] 数字转字符串
来源：http://dali.jinqigfzy.top/Article/details/gticzhpkxq.html

Py:   str(42)
来源：http://dali.birdmap.top/Article/details/gtqvvzthye.html

PHP:  (string) 42; strval(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcvvmkhb.html

JS:   String(42); (42).toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgtinvyhh.html

TS:   String(42)
来源：http://dali.yuxming.cn/Article/details/gtcmjmnesr.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.hongshengwenyu.top/Article/details/gtefiarevo.html

Go:   strconv.Itoa(42)
来源：http://dali.zhoulong.xyz/Article/details/gtewskdyhl.html

Ruby: 42.to_s
来源：http://dali.zhengqikj.top/Article/details/gttkxzotts.html

C#:   42.ToString()
来源：http://dali.hywenlv.cn/Article/details/gtvrborcrh.html

[A08] 取整与四舍五入
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvfgiscn.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hnxiangtu.top/Article/details/gtoxbaqure.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.xinyue.icu/Article/details/gtikpmzwyj.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhtwuyei.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhiwuduotai.top/Article/details/gtzluydjaa.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.snrcjt.cn/Article/details/gttrsqqtnx.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.birdmap.top/Article/details/gtklixojfp.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.wangshuangyany.cn/Article/details/gtohxkxbip.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.snrcjt.cn/Article/details/gtwspzajpa.html

[A09] 绝对值与最大最小值
来源：http://dali.hnxiangtu.top/Article/details/gtiswaciey.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ydzc1.top/Article/details/gtgnyjpkot.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.tanke756.top/Article/details/gtoueuuyrd.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.redwolf501.top/Article/details/gtwpyqqcul.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zycfv.cn/Article/details/gtfhdjkvzt.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtpquvoani.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhongyouzk.top/Article/details/gtsyhtspyv.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.pengpengdd.cyou/Article/details/gtosszkdid.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtdysourau.html

[A10] 生成随机数
来源：http://dali.yongpay.top/Article/details/gtyrgydaay.html

Py:   import random; random.randint(1, 100)
来源：http://dali.cucudq.cn/Article/details/gtvqznuhsu.html

PHP:  random_int(1, 100);
来源：http://dali.smart0.xyz/Article/details/gtfncypmhh.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.fengsongda.top/Article/details/gtooegkivr.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hysaishi.cn/Article/details/gtitcybqcc.html

Java: new Random().nextInt(100) + 1
来源：http://dali.hysaishi.cn/Article/details/gtlmvevkpw.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.redwolf501.top/Article/details/gtewrjutjc.html

Ruby: rand(1..100)
来源：http://dali.jinqigfzy.top/Article/details/gtyecmqkqo.html

C#:   new Random().Next(1, 101)
来源：http://dali.mhx1999.top/Article/details/gtutezdmfp.html

[A11] 条件表达式（三元）
来源：http://dali.meibo888.top/Article/details/gtsfdlmvbw.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.cdnleiting.top/Article/details/gtdvfqjxat.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.andypj.xyz/Article/details/gteljnwygf.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yangfankeji.com/Article/details/gtgvzjctcw.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yj202588.top/Article/details/gtocsseryy.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.shuidangran.top/Article/details/gtkccrjmbo.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.birdmap.top/Article/details/gtkxcxyzpk.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.iojbl.cn/Article/details/gtioyltzzl.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.cqqwz.cn/Article/details/gtdleomljl.html

[A12] 字符串插值 / 格式化
来源：http://dali.guowangkeji.top/Article/details/gtzahvpwxx.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yj20258888.top/Article/details/gthiusvjrn.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.sxryk.cn/Article/details/gtcqbynasw.html

JS:   `Hello, ${name}!`
来源：http://dali.tanke756.top/Article/details/gtqzvlaeqb.html

TS:   `Hello, ${name}!`
来源：http://dali.jyoumei.cn/Article/details/gtrckockyq.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jlsjyb.cn/Article/details/gtezibhvbj.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.hysaishi.cn/Article/details/gtdnfgutlu.html

Ruby: "Hello, #{name}!"
来源：http://dali.9152youxi.cn/Article/details/gtrqlvuwdj.html

C#:   $"Hello, {name}!"
来源：http://dali.yj202588.top/Article/details/gtrrgovwae.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.feifeiyinyue.top/Article/details/gtmzjrynfo.html

Py:   "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gtukpctfuu.html

PHP:  "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gtivxyuxme.html

JS:   "第一行\n第二行"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkpuhbsh.html

TS:   "第一行\n第二行"
来源：http://dali.gaohongyu789.top/Article/details/gtylitetxx.html

Java: "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxdvmhqu.html

Go:   "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gtqhfguvka.html

Ruby: "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gtwgsisebr.html

C#:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gtvealjunh.html

[A14] 注释写法
来源：http://dali.yonumen.top/Article/details/gtifljgjsd.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.ehwqpu.com/Article/details/gtoiawidta.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.kuanghao11.cn/Article/details/gtwiwjkcpf.html

JS:   // 单行；/* 多行 */
来源：http://dali.feifeiyinyue.top/Article/details/gtgdwihrko.html

TS:   // 单行；/* 多行 */
来源：http://dali.jqgufenzy.top/Article/details/gtmroytrby.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.ydzc1.top/Article/details/gtxkbzeaqz.html

Go:   // 单行；/* 多行 */
来源：http://dali.ehwqpu.com/Article/details/gtkqtfjcdv.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.cqqwz.cn/Article/details/gtwsexmbme.html

C#:   // 单行；/* 多行 */
来源：http://dali.aibaodan.cn/Article/details/gtdmytjrnq.html

[A15] 空值判断与默认值
来源：http://dali.yueranfly.top/Article/details/gtpuouhfvk.html

Py:   value = data or "默认值"
来源：http://dali.jinqigfzy.top/Article/details/gtefqnqerp.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yueranfly.top/Article/details/gtrxygnclw.html

JS:   const value = data ?? "默认值";
来源：http://dali.vqdsnc.cn/Article/details/gteovwwdem.html

TS:   const value = data ?? "默认值";
来源：http://dali.ppjwa.cn/Article/details/gtkcprxxfr.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.chenzaomai.com/Article/details/gtkolhkltq.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.ydzc1.top/Article/details/gtfnxkfxam.html

Ruby: value = data || "默认值"
来源：http://dali.iojbl.cn/Article/details/gtayricxhv.html

C#:   var value = data ?? "默认值";
来源：http://dali.jiagoushi.top/Article/details/gtapajxtwp.html

[A16] 真假值判断规则
来源：http://dali.ydzc1.top/Article/details/gtjaalouvm.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.316326.xyz/Article/details/gtwyynqxbs.html


<!-- 参考信息 -->