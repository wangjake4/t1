代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtjiofmrod.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hnqzz.top/Article/details/gtdowimwvy.html

[U92] JS：深拷贝
来源：http://dali.nanxuanxn.top/Article/details/gtgbekbmyk.html

structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtjiwjcefe.html

[U93] JS：模板字符串
来源：http://dali.0kj1m.cn/Article/details/gtatsmvmhm.html

`共 ${n} 条`
来源：http://dali.daxiang520.top/Article/details/gtzngyaowa.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gtyfwgpkyn.html

const double = x => x * 2;
来源：http://dali.zhongyouzk.top/Article/details/gteugmfxtu.html

[U95] JS：Promise 包装
来源：http://dali.0kj1m.cn/Article/details/gthvcfdblx.html

new Promise((resolve, reject) => {})
来源：http://dali.gogol.net.cn/Article/details/gtazpmtgjj.html

[U96] JS：async/await 与异常
来源：http://dali.hfpthk.cn/Article/details/gtscjvqjhr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtrintpqux.html

[U97] JS：并发请求
来源：http://dali.tian-w.cn/Article/details/gtcrmqmdqm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtiphcaduh.html

[U98] JS：fetch 带 JSON
来源：http://dali.hywenlv.cn/Article/details/gtffcwkogl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yj20258.top/Article/details/gthemfnrho.html

[U99] JS：事件监听
来源：http://dali.shzxlz.cn/Article/details/gtdicmtokl.html

el.addEventListener("click", e => {})
来源：http://dali.yanxiufei.cn/Article/details/gtmbijfppn.html

[U100] JS：DOM 查询
来源：http://dali.xuanzx.com/Article/details/gtrtabnwcw.html

document.querySelector(".item")
来源：http://dali.ivvv.top/Article/details/gtfmnrcsjz.html

[U101] JS：classList 操作
来源：http://dali.0kj1m.cn/Article/details/gttdwezkro.html

el.classList.toggle("active")
来源：http://dali.ivvv.top/Article/details/gtqzdjcegr.html

[U102] JS：本地存储
来源：http://dali.yj20258888.top/Article/details/gtemnfuhha.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.pengpengdd.cyou/Article/details/gteuwerutl.html

[U103] JS：定时器
来源：http://dali.yj20258888.top/Article/details/gterveirlt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.kuanghao11.cn/Article/details/gttbrphkia.html

[U104] JS：防抖
来源：http://dali.gaohongyu789.top/Article/details/gtbetllptt.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gtprfthavt.html

[U105] JS：节流
来源：http://dali.iojbl.cn/Article/details/gtayudzrvo.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.nwbrower.top/Article/details/gtqjkvtush.html

[U106] JS：日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gtffztftcj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.sufxvd.cn/Article/details/gtxemxfukz.html

[U107] JS：数字千分位
来源：http://dali.wangdashe.top/Article/details/gtoqibturj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hnqzz.top/Article/details/gtcracdxyt.html

[U108] JS：随机整数
来源：http://dali.xziqi.cn/Article/details/gtmxmkgkat.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jlsjyb.cn/Article/details/gtqcsmwlwk.html

[U109] JS：数组分组
来源：http://dali.svipenyu.cn/Article/details/gtqcizixqg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.gogol.net.cn/Article/details/gteyscijww.html

[U110] JS：数组分块
来源：http://dali.yj20258.top/Article/details/gttdyafigp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.bjfxy.top/Article/details/gtcepygzit.html

[U111] JS：对象转 Map
来源：http://dali.jyoumei.cn/Article/details/gtgzbgaois.html

new Map(Object.entries(obj))
来源：http://dali.zdqjudy.top/Article/details/gtjmryccdg.html

[U112] JS：字符串补位
来源：http://dali.fengsongda.top/Article/details/gtoxehflkr.html

"7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtnjnvrmqc.html

[U113] JS：正则替换全部
来源：http://dali.zhiwuduotai.top/Article/details/gtvjuowwbe.html

s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtuerspcfj.html

[U114] JS：JSON 深比较
来源：http://dali.nwbrower.top/Article/details/gtaddjhkfv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.feifeiyinyue.top/Article/details/gthxkvffmt.html

[U115] JS：生成 UUID
来源：http://dali.shzxlz.cn/Article/details/gtohikvemr.html

crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gtyajjioeb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ppjwa.cn/Article/details/gthzpgolaj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cucudq.cn/Article/details/gtbtrhbtty.html

[U117] JS：单元测试
来源：http://dali.nwbrower.top/Article/details/gtronmapgk.html

npm i -D vitest;  npx vitest
来源：http://dali.wangdashe.top/Article/details/gtkkgvuarn.html

[U118] JS：开发服务器
来源：http://dali.quarkkingdee.top/Article/details/gtljfctimr.html

npm i -D vite;  npx vite
来源：http://dali.tanke756.top/Article/details/gtlvfmtefe.html

[U119] JS：生产构建
来源：http://dali.jyoumei.cn/Article/details/gtxtihluab.html

npx vite build
来源：http://dali.gaohongyu789.top/Article/details/gtxgbytlkw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.haohaochexian.top/Article/details/gtbapwfppi.html

import.meta.env.VITE_API_URL
来源：http://dali.yueranfly.top/Article/details/gtlsyxzjaw.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gthhclchhu.html

统计汇总
来源：http://dali.aibaodan.cn/Article/details/gtgdjfvwqn.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtvdymcsnr.html

按语言统计（条）：
来源：http://dali.316326.xyz/Article/details/gtjxjfjwds.html

Python ......... 252
来源：http://dali.yanxiufei.cn/Article/details/gtybgcrtmz.html

PHP ............ 252
来源：http://dali.cashguo.top/Article/details/gtxiwricho.html

JavaScript ..... 252
来源：http://dali.gzhubu.top/Article/details/gtophllgmm.html

TypeScript ..... 212
来源：http://dali.meibo888.top/Article/details/gturgvycxe.html

Java ........... 212
来源：http://dali.tianlin.xyz/Article/details/gtnapwqubm.html

Go ............. 212
来源：http://dali.daria6918.cn/Article/details/gtdgpfjgne.html

Ruby ........... 212
来源：http://dali.yvedp.cn/Article/details/gtainwepfu.html

C# ............. 212
来源：http://dali.shanyushiyangtech.top/Article/details/gtporcsxla.html

C .............. 30
来源：http://dali.yongpay.top/Article/details/gtjuwpaury.html

C++ ............ 30
来源：http://dali.ivvv.top/Article/details/gttgpmkiuc.html

SQL ............ 90
来源：http://dali.daria6918.cn/Article/details/gtuzhjopqq.html

Bash ........... 80
来源：http://dali.iojbl.cn/Article/details/gtvlkhioaq.html

Kotlin ......... 15
来源：http://dali.ppjwa.cn/Article/details/gtcxgmlmam.html

Swift .......... 15
来源：http://dali.nanxuanxn.top/Article/details/gtrpxllrfk.html

Lua ............ 10
来源：http://dali.snrcjt.cn/Article/details/gtcmrmfhbk.html

Perl ........... 10
来源：http://dali.yangfankeji.com/Article/details/gtmclmaztg.html

Scala .......... 10
来源：http://dali.dianchejie.cn/Article/details/gtplhuaens.html

------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gtjboqgfvm.html

合计 ........... 2106 条
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrsrajfwo.html

按章节统计：
来源：http://dali.gaohongyu789.top/Article/details/gtmkykgpvt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yj20258.top/Article/details/gtwuuvlcns.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yj202588.top/Article/details/gtxiilktal.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gttcrpssly.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.0kj1m.cn/Article/details/gtazqxvqsd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.haohaochexian.top/Article/details/gtdedtkflb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.gzhubu.top/Article/details/gtajpuinel.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hywenlv.cn/Article/details/gtkvbmcutt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jqgfzy.top/Article/details/gtjqghrurm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gtmpgvuxls.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.pycfn.com/Article/details/gtpzotvhrl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gthaetyqsj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gtiviiexlj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gtgsrhcbkt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.dianchejie.cn/Article/details/gtukubxgsb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.nanxuanxn.top/Article/details/gtyvxuzkca.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gtrmzdpdqu.html

Q SQL 专题                              90
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgbsxcwz.html

R Bash 专题                             80
来源：http://dali.jinqigufen.top/Article/details/gtrhpjsgnc.html

S C / C++ 专题                          60
来源：http://dali.yueranfly.top/Article/details/gtkenbgxhh.html

T 其他语言补充                          60
来源：http://dali.jinqigfzy.top/Article/details/gtelyntqrk.html

U 高频实用片段                         120
来源：http://dali.tanke756.top/Article/details/gtjpphkcxa.html

------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gtukexvebd.html

合计                                  2106 条
来源：http://dali.cucudq.cn/Article/details/gteitziczz.html

--------------------------------------------------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gttbnktpec.html

使用提醒
来源：http://dali.daxiang520.top/Article/details/gtizhuqgmw.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdokfmxnq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.svipenyu.cn/Article/details/gtqocgoicj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.gzhubu.top/Article/details/gthciwzstl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.snrcjt.cn/Article/details/gtklxzegfq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.shzxlz.cn/Article/details/gttctjzvuo.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gtnjtmitje.html

—— 文件结束 ——
来源：http://dali.yangfankeji.com/Article/details/gtckgcbfeh.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtnikciluc.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cqqwz.cn/Article/details/gtvxwkuibz.html

Common Programming Examples Cheat Book
来源：http://dali.gogol.net.cn/Article/details/gtjzcmfnfv.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtuduylpvs.html

【收录内容】
来源：http://dali.dianchejie.cn/Article/details/gtjwlhtgzc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.tanke756.top/Article/details/gtbkeeiylg.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hnqzz.top/Article/details/gtpfvihvpz.html

SQL · Bash · C · C++
来源：http://dali.yuanzhike.top/Article/details/gtfaxibqcm.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yj20258.top/Article/details/gtfxmgauly.html

【使用说明】
来源：http://dali.fzhhl.top/Article/details/gtdiwmoikg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cashguo.top/Article/details/gtjrpkakmu.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hammf.cn/Article/details/gtngrkiipb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jianghu66.top/Article/details/gtitfmrzqi.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jyoumei.cn/Article/details/gtdsrcvxpq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xylfe.cn/Article/details/gtjtvffydv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.tanke756.top/Article/details/gtslrohltu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zdqjudy.top/Article/details/gtthqmcqwl.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhiwuduotai.top/Article/details/gttadewqwl.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.smart0.xyz/Article/details/gtrtqolhrl.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.c1oappe.top/Article/details/gtuwmnhrvi.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhengqikj.top/Article/details/gtgajtnpmd.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.ehwqpu.com/Article/details/gtqsrgcaxw.html

【文件统计】
来源：http://dali.ydzc1.top/Article/details/gtphcxnjgt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.redwolf501.top/Article/details/gtyildzjqq.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gtwlqqmheg.html

目  录
来源：http://dali.sysykeji.top/Article/details/gthknjrsbr.html

--------------------------------------------------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtuiiipida.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.c1oappe.top/Article/details/gtfubeiiwo.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.chenzaomai.com/Article/details/gtxypxpcze.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.ppjwa.cn/Article/details/gtxhlkrqzv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.wangdashe.top/Article/details/gtgqujlyir.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.nanxinkj.top/Article/details/gtdpohxikx.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.tian-w.cn/Article/details/gtaevuuppk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yongpay.top/Article/details/gtqdxqspyl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.mhx1999.top/Article/details/gtyneatpxi.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gtimwqcmlm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxipxewvt.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.sxryk.cn/Article/details/gtlfglcyxs.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkknqeykt.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.shzxlz.cn/Article/details/gtgtoxslpe.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtcxdaxsjn.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xylfe.cn/Article/details/gtsqgqscjy.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zycfv.cn/Article/details/gtjbrzgnqq.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yangfankeji.com/Article/details/gtrboaxtva.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yj20258888.top/Article/details/gtmsuygkmt.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.nanxuanxn.top/Article/details/gtygryhqqj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.redwolf501.top/Article/details/gtczazfokm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.nanxuanxn.top/Article/details/gtflkczxbq.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtagxwixmm.html

A. 基础语法与类型
来源：http://dali.dashuyun.cn/Article/details/gtyihfmygf.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtjdzotjhg.html

[A01] Hello World
来源：http://dali.ehwqpu.com/Article/details/gtscyvsqep.html

Py:   print("Hello, World!")
来源：http://dali.meibo888.top/Article/details/gtvwbgonlw.html

PHP:  echo "Hello, World!";
来源：http://dali.chenlongwang.top/Article/details/gtvoxsbjak.html

JS:   console.log("Hello, World!");
来源：http://dali.daria6918.cn/Article/details/gtsklzssci.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yangfankeji.com/Article/details/gtdwdowukt.html

Java: System.out.println("Hello, World!");
来源：http://dali.havefunace.top/Article/details/gtrhqwceew.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzsytjdl.html

Ruby: puts "Hello, World!"
来源：http://dali.yangfankeji.com/Article/details/gtmprmqbij.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hongshengwenyu.top/Article/details/gtfxhotlhh.html

[A02] 变量声明与赋值
来源：http://dali.hammf.cn/Article/details/gteunaplzv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yanxiufei.cn/Article/details/gtnukbcgor.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jqgufenzy.top/Article/details/gtdmmcfxay.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.wangdashe.top/Article/details/gtxihvsfkj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.mhx1999.top/Article/details/gtripsoqtj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hnqzz.top/Article/details/gtjdbrpusy.html

Go:   name := "Alex"; age := 20
来源：http://dali.nwbrower.top/Article/details/gtfujemmyd.html

Ruby: name = "Alex"; age = 20
来源：http://dali.wangdashe.top/Article/details/gtmcffhver.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yongpay.top/Article/details/gtcgofmfzf.html

[A03] 常量定义
来源：http://dali.hnqzz.top/Article/details/gtnohhccwr.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jinghuilouyu.cn/Article/details/gttbahwmvn.html

PHP:  const PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtpcjgalpo.html

JS:   const PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gtlmhcbedd.html

TS:   const PI: number = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtoiplylpq.html

Java: static final double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtuacsjnek.html

Go:   const PI = 3.14159
来源：http://dali.sysykeji.top/Article/details/gtdktkmvnz.html

Ruby: PI = 3.14159
来源：http://dali.jyoumei.cn/Article/details/gtetpxtebu.html

C#:   const double PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtakgpvqpb.html

[A04] 判断变量类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpxotavw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.fengsongda.top/Article/details/gtcenyheqb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ivvv.top/Article/details/gtsxyycaya.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.gogol.net.cn/Article/details/gtcdpxxcie.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhongyouzk.top/Article/details/gttdmfeaym.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.cdnleiting.top/Article/details/gtapqoskxs.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jqgufenzy.top/Article/details/gtkahiadtm.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.vqdsnc.cn/Article/details/gtdjeulxnq.html

C#:   x.GetType().Name; x is int
来源：http://dali.gotoacloud.top/Article/details/gtpkywqqrg.html

[A05] 整数除法与取模
来源：http://dali.yanxiufei.cn/Article/details/gtlyyjsqkg.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cdnleiting.top/Article/details/gtsnbucmmg.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gtiunhmudy.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gtcgnpirap.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cheryme.top/Article/details/gtjkrwjzjr.html

Java: 7 / 2; 7 % 2
来源：http://dali.daxiang520.top/Article/details/gtaqzixgkl.html

Go:   7 / 2; 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gtfjfblzwy.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtqkyxlfot.html

C#:   7 / 2; 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gtcmukxbzg.html

[A06] 字符串转数字
来源：http://dali.xuetiantiany.cn/Article/details/gtijjzstts.html

Py:   int("42"); float("3.14")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkzgixml.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.tanke756.top/Article/details/gtmmwqvcfo.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jyoumei.cn/Article/details/gtdeejtvqz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.kuanghao11.cn/Article/details/gtnkzjgaij.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.xylfe.cn/Article/details/gtxwzsfmgi.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.chenlongwang.top/Article/details/gtndrgjplj.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yuxming.cn/Article/details/gtwmjghyoi.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.316326.xyz/Article/details/gthvedxlva.html

[A07] 数字转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmbftuwu.html

Py:   str(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwcqephog.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogmvcbot.html

JS:   String(42); (42).toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtsodicueo.html

TS:   String(42)
来源：http://dali.sysykeji.top/Article/details/gtbcgamtkf.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jqgfzy.top/Article/details/gtbntpzxmv.html

Go:   strconv.Itoa(42)
来源：http://dali.yongpay.top/Article/details/gtbslkpkme.html

Ruby: 42.to_s
来源：http://dali.jyoumei.cn/Article/details/gtagewoyti.html

C#:   42.ToString()
来源：http://dali.zycfv.cn/Article/details/gtsztcghbd.html

[A08] 取整与四舍五入
来源：http://dali.yj202588.top/Article/details/gtbmzlgpul.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.feifeiyinyue.top/Article/details/gthsfcvxqj.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.guowangkeji.top/Article/details/gtxapnlfhd.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiadzqjoz.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jyoumei.cn/Article/details/gtpnbhljdr.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yvedp.cn/Article/details/gtioiyqequ.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jqgfzy.top/Article/details/gtgpwsfujq.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.shangyingyoupin.top/Article/details/gtihdpxixp.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.snrcjt.cn/Article/details/gtuiuuhxmn.html

[A09] 绝对值与最大最小值
来源：http://dali.vqdsnc.cn/Article/details/gtejgkmyca.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sxryk.cn/Article/details/gttcbnanhm.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxqgflgt.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtmyajnqos.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yuanzhike.top/Article/details/gtvmjerpyg.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtsilkyvdn.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.sysykeji.top/Article/details/gtjddaxmln.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.sysykeji.top/Article/details/gtwhwlkcoy.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.xinyue.icu/Article/details/gtqllhgshk.html

[A10] 生成随机数
来源：http://dali.tanke756.top/Article/details/gtnxgjhnqk.html

Py:   import random; random.randint(1, 100)
来源：http://dali.dashuyun.cn/Article/details/gtrkwlpzsv.html

PHP:  random_int(1, 100);
来源：http://dali.feifeiyinyue.top/Article/details/gtummnouja.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjqabbgf.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.chenjidiqi.icu/Article/details/gtszqxuwnp.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yj20258.top/Article/details/gtiorpizsl.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hammf.cn/Article/details/gtbcfmpbku.html

Ruby: rand(1..100)
来源：http://dali.9152youxi.cn/Article/details/gtbwwilpvb.html

C#:   new Random().Next(1, 101)
来源：http://dali.xuetiantiany.cn/Article/details/gtgnewfkcu.html

[A11] 条件表达式（三元）
来源：http://dali.xziqi.cn/Article/details/gthvyhnysf.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.xziqi.cn/Article/details/gticjahjfr.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yuxming.cn/Article/details/gtbcpegqdo.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.dianchejie.cn/Article/details/gtjxottfxt.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.shuidangran.top/Article/details/gtthjroqea.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.fengsongda.top/Article/details/gtraysivkm.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jlsjyb.cn/Article/details/gtdbbeuerq.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.dashuyun.cn/Article/details/gtgtxfkgss.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.dianchejie.cn/Article/details/gtugucqsyc.html

[A12] 字符串插值 / 格式化
来源：http://dali.yonumen.top/Article/details/gtmqpjyzav.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.gogol.net.cn/Article/details/gtficzwomr.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jianghu66.top/Article/details/gtlyvgtkib.html

JS:   `Hello, ${name}!`
来源：http://dali.jiagoushi.top/Article/details/gtzhjajjzt.html

TS:   `Hello, ${name}!`
来源：http://dali.jlsjyb.cn/Article/details/gtihozanfz.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.gogol.net.cn/Article/details/gtqzcmhqjl.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yongpay.top/Article/details/gtrtzjxwoc.html

Ruby: "Hello, #{name}!"
来源：http://dali.wangdashe.top/Article/details/gtmuyfrbsu.html

C#:   $"Hello, {name}!"
来源：http://dali.andypj.xyz/Article/details/gtvspldkcz.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.nwbrower.top/Article/details/gtjtwiktbs.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gtbyjhxerl.html

PHP:  "第一行\n第二行"
来源：http://dali.shuidangran.top/Article/details/gtbkuocrbh.html

JS:   "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gtctgeupre.html

TS:   "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gtjgccmbfw.html

Java: "第一行\n第二行"
来源：http://dali.9152youxi.cn/Article/details/gtvjifzjcg.html

Go:   "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gttsxwvbib.html

Ruby: "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gtozpvdnww.html

C#:   "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gtzpygspoz.html

[A14] 注释写法
来源：http://dali.wangdashe.top/Article/details/gthmtlzppg.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.wangshuangyany.cn/Article/details/gttsjabldn.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowhcnnse.html

JS:   // 单行；/* 多行 */
来源：http://dali.yangfankeji.com/Article/details/gtjcdbfdec.html

TS:   // 单行；/* 多行 */
来源：http://dali.yangfankeji.com/Article/details/gtfpopcnfg.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.vqdsnc.cn/Article/details/gtysqkggdr.html

Go:   // 单行；/* 多行 */
来源：http://dali.yj20258888.top/Article/details/gtqgcisifz.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.tianlin.xyz/Article/details/gtsngmmqqp.html

C#:   // 单行；/* 多行 */
来源：http://dali.quarkkingdee.top/Article/details/gtqgalmsax.html

[A15] 空值判断与默认值
来源：http://dali.chenjidiqi.icu/Article/details/gtyokembuw.html

Py:   value = data or "默认值"
来源：http://dali.gaohongyu789.top/Article/details/gtutxalido.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.wangdashe.top/Article/details/gtlccfihwy.html

JS:   const value = data ?? "默认值";
来源：http://dali.jiagoushi.top/Article/details/gtdnjkyysy.html

TS:   const value = data ?? "默认值";
来源：http://dali.cucudq.cn/Article/details/gtxieptcaq.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhiwuduotai.top/Article/details/gtbfembeuf.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.ydzc1.top/Article/details/gthacdlunz.html


<!-- 参考信息 -->