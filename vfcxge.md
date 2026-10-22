代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.zhixingplan.top/Article/details/gttpqjogem.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.chenzaomai.com/Article/details/gtuhqeorws.html

[U92] JS：深拷贝
来源：http://dali.redwolf501.top/Article/details/gtvmuelnqk.html

structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gtpbwvhkiz.html

[U93] JS：模板字符串
来源：http://dali.fzhhl.top/Article/details/gtvhnxphcx.html

`共 ${n} 条`
来源：http://dali.xuetiantiany.cn/Article/details/gttpusqoqf.html

[U94] JS：箭头函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwfanrcb.html

const double = x => x * 2;
来源：http://dali.yonumen.top/Article/details/gtqsvzywge.html

[U95] JS：Promise 包装
来源：http://dali.ydzc1.top/Article/details/gtbnbriygi.html

new Promise((resolve, reject) => {})
来源：http://dali.gzhubu.top/Article/details/gtnerisopq.html

[U96] JS：async/await 与异常
来源：http://dali.jqgfzy.top/Article/details/gtyxrshwex.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtusfqgrkw.html

[U97] JS：并发请求
来源：http://dali.xziqi.cn/Article/details/gtpwxpindu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtdrcjxbek.html

[U98] JS：fetch 带 JSON
来源：http://dali.ivvv.top/Article/details/gtemiwauba.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zycfv.cn/Article/details/gtjiyhwfhe.html

[U99] JS：事件监听
来源：http://dali.nanxuanxn.top/Article/details/gthsgctkcn.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gtrrzswoqb.html

[U100] JS：DOM 查询
来源：http://dali.svipenyu.cn/Article/details/gtbtmiglvr.html

document.querySelector(".item")
来源：http://dali.yj202588.top/Article/details/gtsehspxgf.html

[U101] JS：classList 操作
来源：http://dali.jinqigufen.top/Article/details/gtwkimszer.html

el.classList.toggle("active")
来源：http://dali.nanxuanxn.top/Article/details/gtntokptdb.html

[U102] JS：本地存储
来源：http://dali.birdmap.top/Article/details/gtqlgxanoc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.quarkkingdee.top/Article/details/gtpmzyrobf.html

[U103] JS：定时器
来源：http://dali.hammf.cn/Article/details/gtvslpdncr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xinyue.icu/Article/details/gtasedrsxk.html

[U104] JS：防抖
来源：http://dali.birdmap.top/Article/details/gtyaqjbrmk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gtntdzlqay.html

[U105] JS：节流
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuhdvpbox.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yonumen.top/Article/details/gtedcjfhlj.html

[U106] JS：日期格式化
来源：http://dali.dianchejie.cn/Article/details/gtlndqhgob.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hongshengwenyu.top/Article/details/gtcvwjzwls.html

[U107] JS：数字千分位
来源：http://dali.daria6918.cn/Article/details/gtcklglusd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.nanxinkj.top/Article/details/gtitqzqfvt.html

[U108] JS：随机整数
来源：http://dali.guannengcc.top/Article/details/gtcyclfgrq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xuetiantiany.cn/Article/details/gtzcyffkkp.html

[U109] JS：数组分组
来源：http://dali.yuanzhike.top/Article/details/gtddwrysug.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xinyue.icu/Article/details/gtmegycmyj.html

[U110] JS：数组分块
来源：http://dali.yuxming.cn/Article/details/gtkscyfypq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ybcxt.top/Article/details/gtizvvbqwm.html

[U111] JS：对象转 Map
来源：http://dali.yvedp.cn/Article/details/gtdtktkezw.html

new Map(Object.entries(obj))
来源：http://dali.smart0.xyz/Article/details/gtcxrapngx.html

[U112] JS：字符串补位
来源：http://dali.shzxlz.cn/Article/details/gtchiiccfg.html

"7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gticglwusy.html

[U113] JS：正则替换全部
来源：http://dali.havefunace.top/Article/details/gtohngmapd.html

s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwnpgplc.html

[U114] JS：JSON 深比较
来源：http://dali.bjfxy.top/Article/details/gtwytbzmil.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yangfankeji.com/Article/details/gtotyhxjoa.html

[U115] JS：生成 UUID
来源：http://dali.yangfankeji.com/Article/details/gtqpkapygb.html

crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gtulzugtil.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.c1oappe.top/Article/details/gtheklktyj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xylfe.cn/Article/details/gtcwwrwwzk.html

[U117] JS：单元测试
来源：http://dali.jianghu66.top/Article/details/gtdnjqgmfx.html

npm i -D vitest;  npx vitest
来源：http://dali.tanke756.top/Article/details/gtoknetqfo.html

[U118] JS：开发服务器
来源：http://dali.zhoulong.xyz/Article/details/gtmojqqmwl.html

npm i -D vite;  npx vite
来源：http://dali.guannengcc.top/Article/details/gtdgudmish.html

[U119] JS：生产构建
来源：http://dali.zhengqikj.top/Article/details/gtrfxmtntg.html

npx vite build
来源：http://dali.nanxuanxn.top/Article/details/gtouhuarkj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.dianchejie.cn/Article/details/gtucadxjuy.html

import.meta.env.VITE_API_URL
来源：http://dali.dianchejie.cn/Article/details/gtqocuirjp.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtbrwopzyk.html

统计汇总
来源：http://dali.sweek.top/Article/details/gtjvdptpqm.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtfmdquyup.html

按语言统计（条）：
来源：http://dali.zhiwuduotai.top/Article/details/gtlwjghuko.html

Python ......... 252
来源：http://dali.shangyingyoupin.top/Article/details/gtbpvgcotv.html

PHP ............ 252
来源：http://dali.yuanzhike.top/Article/details/gtpkhwqnsb.html

JavaScript ..... 252
来源：http://dali.gaohongyu789.top/Article/details/gtesghfqso.html

TypeScript ..... 212
来源：http://dali.dashuyun.cn/Article/details/gtyfvvoppo.html

Java ........... 212
来源：http://dali.haohaochexian.top/Article/details/gtandvjhmq.html

Go ............. 212
来源：http://dali.fengsongda.top/Article/details/gtizhplghd.html

Ruby ........... 212
来源：http://dali.ehwqpu.com/Article/details/gteovyqkxl.html

C# ............. 212
来源：http://dali.hnxiangtu.top/Article/details/gtpdnwyagn.html

C .............. 30
来源：http://dali.cheryme.top/Article/details/gteiedrkcs.html

C++ ............ 30
来源：http://dali.redwolf501.top/Article/details/gtxgiprotk.html

SQL ............ 90
来源：http://dali.nanxuanxn.top/Article/details/gtpgacanbm.html

Bash ........... 80
来源：http://dali.hnqzz.top/Article/details/gtnzglrrad.html

Kotlin ......... 15
来源：http://dali.tianlin.xyz/Article/details/gtezmanbsa.html

Swift .......... 15
来源：http://dali.nanxinkj.top/Article/details/gtwmuhwagi.html

Lua ............ 10
来源：http://dali.fzhhl.top/Article/details/gtivyxwbfc.html

Perl ........... 10
来源：http://dali.pycfn.com/Article/details/gtzymrytjt.html

Scala .......... 10
来源：http://dali.hnqzz.top/Article/details/gtrsbmwaqv.html

------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtpwjpdebi.html

合计 ........... 2106 条
来源：http://dali.jyoumei.cn/Article/details/gtjamcfkjr.html

按章节统计：
来源：http://dali.yj20258.top/Article/details/gtqpaflfej.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.meibo888.top/Article/details/gtwqzoakhj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hywenlv.cn/Article/details/gttxuagsxv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinqigfzy.top/Article/details/gtpwypjtzv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.dianchejie.cn/Article/details/gtidmbiigb.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shuidangran.top/Article/details/gtxiipfbpq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhiwuduotai.top/Article/details/gtbornzbxn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yuanzhike.top/Article/details/gtzdnssajm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jiagoushi.top/Article/details/gtgdcucfog.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gtdcaeiylw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ybcxt.top/Article/details/gtdcdelhgw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gtlecvyvdp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gttymdstcg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhiwuduotai.top/Article/details/gticcfhmgh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xinyue.icu/Article/details/gthmbjshig.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zdqjudy.top/Article/details/gtxymetcah.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gtfpmlabte.html

Q SQL 专题                              90
来源：http://dali.sxryk.cn/Article/details/gtfmklzkyg.html

R Bash 专题                             80
来源：http://dali.ivvv.top/Article/details/gtckiknmal.html

S C / C++ 专题                          60
来源：http://dali.bjfxy.top/Article/details/gtejdjeqoi.html

T 其他语言补充                          60
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjzcbhsr.html

U 高频实用片段                         120
来源：http://dali.shzxlz.cn/Article/details/gtqopaywlj.html

------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gtscrbbsfq.html

合计                                  2106 条
来源：http://dali.jinqigfzy.top/Article/details/gtadjvmrod.html

--------------------------------------------------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gtfodusivk.html

使用提醒
来源：http://dali.hywenlv.cn/Article/details/gteranuzcs.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gthizuwjhp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.smart0.xyz/Article/details/gtdzkplpip.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.gotoacloud.top/Article/details/gtzjhymnlv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ppjwa.cn/Article/details/gtekpeoauq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.pycfn.com/Article/details/gthsjguboy.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hammf.cn/Article/details/gtzagalvxa.html

—— 文件结束 ——
来源：http://dali.kuanghao11.cn/Article/details/gtitbhopqh.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtgrifxzhn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hfpthk.cn/Article/details/gtxhifyxff.html

Common Programming Examples Cheat Book
来源：http://dali.gogol.net.cn/Article/details/gthdqhxxzf.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtuiruttfs.html

【收录内容】
来源：http://dali.hnqzz.top/Article/details/gtwcpmxykt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.gogol.net.cn/Article/details/gtbtyojdef.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.pengpengdd.cyou/Article/details/gtsuserbvb.html

SQL · Bash · C · C++
来源：http://dali.vqdsnc.cn/Article/details/gtrkuplwsj.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.andypj.xyz/Article/details/gtzpecvuzi.html

【使用说明】
来源：http://dali.nwbrower.top/Article/details/gttpofapmt.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hysaishi.cn/Article/details/gtcangfbzr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gtvzrzanvw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hywenlv.cn/Article/details/gtzwqjfpzd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yueranfly.top/Article/details/gtxfgedxiw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hnqzz.top/Article/details/gtepocygqm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenzaomai.com/Article/details/gtaujahamq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.shangyingyoupin.top/Article/details/gtplpvwcnn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yueranfly.top/Article/details/gtulkridjk.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.guowangkeji.top/Article/details/gtvhdvofzm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hammf.cn/Article/details/gtjfzhhime.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ydzc1.top/Article/details/gtgjixtvcq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.smart0.xyz/Article/details/gtwmozcxqw.html

【文件统计】
来源：http://dali.jinghuilouyu.cn/Article/details/gtdijuqyxf.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.tianlin.xyz/Article/details/gtfpeyytxf.html

--------------------------------------------------------------------------------
来源：http://dali.yuxming.cn/Article/details/gtabjvjdcx.html

目  录
来源：http://dali.meibo888.top/Article/details/gthlvufnvf.html

--------------------------------------------------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gtkunwolro.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.fzhhl.top/Article/details/gtjphtxzaz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.vqdsnc.cn/Article/details/gttgbbnvmr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.ydzc1.top/Article/details/gtsphyyhxv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zdqjudy.top/Article/details/gtoinxsrqj.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtymltssop.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jqgufenzy.top/Article/details/gtotxngrqn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ydzc1.top/Article/details/gtwjriftdk.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.birdmap.top/Article/details/gtugfztlfu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.fengsongda.top/Article/details/gtpgiyjrdl.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.haohaochexian.top/Article/details/gtofhjqtxw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gtcvnlbtbp.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxblnhnir.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gtzsvhfetv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.sxryk.cn/Article/details/gtrjuwqpef.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.havefunace.top/Article/details/gtpdasijck.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gtloogftwf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.nwbrower.top/Article/details/gtqkvykgmq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yanxiufei.cn/Article/details/gtiurdtsit.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtwotjsmth.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnqzz.top/Article/details/gtlkgrjkxi.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj202588.top/Article/details/gttnopcodu.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gteyighwdv.html

A. 基础语法与类型
来源：http://dali.andypj.xyz/Article/details/gtifskbxxf.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtpnnebmsm.html

[A01] Hello World
来源：http://dali.0kj1m.cn/Article/details/gtyjzunqng.html

Py:   print("Hello, World!")
来源：http://dali.cdnleiting.top/Article/details/gtgcipxdmf.html

PHP:  echo "Hello, World!";
来源：http://dali.ppjwa.cn/Article/details/gtoeiqujvr.html

JS:   console.log("Hello, World!");
来源：http://dali.sxryk.cn/Article/details/gtksovqibh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.havefunace.top/Article/details/gtcmtbtlzc.html

Java: System.out.println("Hello, World!");
来源：http://dali.xziqi.cn/Article/details/gtdnftlprw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.andypj.xyz/Article/details/gtgkxxoczn.html

Ruby: puts "Hello, World!"
来源：http://dali.cdnleiting.top/Article/details/gtjlyibzhz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.nwbrower.top/Article/details/gtikizgtqq.html

[A02] 变量声明与赋值
来源：http://dali.zdqjudy.top/Article/details/gtpqnmzpae.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ybcxt.top/Article/details/gtucmhrfiv.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hfpthk.cn/Article/details/gtujvvcfeb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gttyadlmrz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jinqigufen.top/Article/details/gtfvlxhbig.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.gogol.net.cn/Article/details/gtsrwawcuh.html

Go:   name := "Alex"; age := 20
来源：http://dali.hysaishi.cn/Article/details/gtxkolhspv.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yonumen.top/Article/details/gtrbakapah.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.sweek.top/Article/details/gtrcwzelvr.html

[A03] 常量定义
来源：http://dali.iojbl.cn/Article/details/gtwujtvuio.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhiwuduotai.top/Article/details/gthgkzypid.html

PHP:  const PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtfswyknch.html

JS:   const PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxfamxmw.html

TS:   const PI: number = 3.14159;
来源：http://dali.yonumen.top/Article/details/gtnhndbvwu.html

Java: static final double PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtmksiosbq.html

Go:   const PI = 3.14159
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrtvoknc.html

Ruby: PI = 3.14159
来源：http://dali.redwolf501.top/Article/details/gtylhrnjvk.html

C#:   const double PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkyzjaoqv.html

[A04] 判断变量类型
来源：http://dali.cashguo.top/Article/details/gtoclcesho.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.iojbl.cn/Article/details/gtqgrcajzt.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jqgfzy.top/Article/details/gtsygbpphr.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.shzxlz.cn/Article/details/gttwqcrcpz.html

TS:   typeof x; x instanceof Date
来源：http://dali.cdnleiting.top/Article/details/gtlioifgud.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhoulong.xyz/Article/details/gtkceupvkw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjcjgjjs.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.andypj.xyz/Article/details/gtqbyclwgj.html

C#:   x.GetType().Name; x is int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtksspnfsz.html

[A05] 整数除法与取模
来源：http://dali.zhixingplan.top/Article/details/gtdwllhxot.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.haohaochexian.top/Article/details/gtupxyznrw.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gtrpupmjkc.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yonumen.top/Article/details/gtqfickjwt.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtgzfigkov.html

Java: 7 / 2; 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gtwqarqvqw.html

Go:   7 / 2; 7 % 2
来源：http://dali.316326.xyz/Article/details/gtagkizaxf.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gtgfcxkzda.html

C#:   7 / 2; 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtxlpnfnma.html

[A06] 字符串转数字
来源：http://dali.yj20258.top/Article/details/gtzstozdkl.html

Py:   int("42"); float("3.14")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwhiibgf.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.ppjwa.cn/Article/details/gtiqkjtqvu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yangfankeji.com/Article/details/gtsktdeuvx.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gtghsfwuwp.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yj202588.top/Article/details/gtfltpwbod.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hywenlv.cn/Article/details/gtigjrzcrc.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hongshengwenyu.top/Article/details/gtyhsbfxvt.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jlsjyb.cn/Article/details/gtdpdawvve.html

[A07] 数字转字符串
来源：http://dali.shzxlz.cn/Article/details/gtozbaqzdu.html

Py:   str(42)
来源：http://dali.sufxvd.cn/Article/details/gttnlvsdwd.html

PHP:  (string) 42; strval(42)
来源：http://dali.shzxlz.cn/Article/details/gtoqiecypp.html

JS:   String(42); (42).toString()
来源：http://dali.shzxlz.cn/Article/details/gttkinldeu.html

TS:   String(42)
来源：http://dali.mhx1999.top/Article/details/gtimaxjedc.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.hysaishi.cn/Article/details/gtgeutdmie.html

Go:   strconv.Itoa(42)
来源：http://dali.ppjwa.cn/Article/details/gtdgdeybef.html

Ruby: 42.to_s
来源：http://dali.jqgfzy.top/Article/details/gtkvclzhlx.html

C#:   42.ToString()
来源：http://dali.daria6918.cn/Article/details/gtijpnujlr.html

[A08] 取整与四舍五入
来源：http://dali.xziqi.cn/Article/details/gtquhwkhbp.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.redwolf501.top/Article/details/gtvbzckqel.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ppjwa.cn/Article/details/gtcvzmbhwv.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.hnqzz.top/Article/details/gtqhbzslcc.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yanxiufei.cn/Article/details/gttxwagbcl.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.vqdsnc.cn/Article/details/gttapjhcwd.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.chenzaomai.com/Article/details/gtzqapwkqg.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.ybcxt.top/Article/details/gtxkfwmirn.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yuxming.cn/Article/details/gtmoavfkvd.html

[A09] 绝对值与最大最小值
来源：http://dali.ydzc1.top/Article/details/gtvsmcwgvg.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsolvtpa.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtaeaxecfo.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.316326.xyz/Article/details/gtovummhnk.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yonumen.top/Article/details/gtqmjkqwgz.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gtxmnfrybc.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.kuanghao11.cn/Article/details/gthnlzryyy.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhoulong.xyz/Article/details/gtfaylmkhd.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gthahckjsl.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gtdtktycvx.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zycfv.cn/Article/details/gthakxkbwt.html

PHP:  random_int(1, 100);
来源：http://dali.316326.xyz/Article/details/gtyifhbzls.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hongshengwenyu.top/Article/details/gtpbblslvn.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.c1oappe.top/Article/details/gtjkogwbaf.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jqgfzy.top/Article/details/gtkyrnbkvr.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfphzaysw.html

Ruby: rand(1..100)
来源：http://dali.guannengcc.top/Article/details/gtzkzvisld.html

C#:   new Random().Next(1, 101)
来源：http://dali.smart0.xyz/Article/details/gtvoqxrlyi.html

[A11] 条件表达式（三元）
来源：http://dali.ehwqpu.com/Article/details/gtzlugbuvy.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytwogqbh.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.shzxlz.cn/Article/details/gtpmvbjxxj.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhixingplan.top/Article/details/gtnhgtjsbq.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhixingplan.top/Article/details/gtwvylgaqn.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yj20258.top/Article/details/gtbhynbmbc.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhengqikj.top/Article/details/gtsfnikryv.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.xziqi.cn/Article/details/gtwzkqpgvg.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.ehwqpu.com/Article/details/gtgnqmvzfu.html

[A12] 字符串插值 / 格式化
来源：http://dali.jinqigfzy.top/Article/details/gtqesiobvr.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.sxryk.cn/Article/details/gtscknbzas.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.gzhubu.top/Article/details/gtcpqcwxym.html

JS:   `Hello, ${name}!`
来源：http://dali.yj20258.top/Article/details/gtwhvbzgso.html

TS:   `Hello, ${name}!`
来源：http://dali.yj20258888.top/Article/details/gtnmehjylx.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jianghu66.top/Article/details/gtazbsrrfh.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtokgzjaxz.html

Ruby: "Hello, #{name}!"
来源：http://dali.yj202588.top/Article/details/gtkoamihgc.html

C#:   $"Hello, {name}!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegzavkyw.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.chenlongwang.top/Article/details/gtedaoebrn.html

Py:   "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gtrbrvyglx.html

PHP:  "第一行\n第二行"
来源：http://dali.haohaochexian.top/Article/details/gtqszreywf.html

JS:   "第一行\n第二行"
来源：http://dali.yangfankeji.com/Article/details/gtovlhzxpg.html

TS:   "第一行\n第二行"
来源：http://dali.c1oappe.top/Article/details/gtlcijosxf.html

Java: "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gtlrnkiyfm.html

Go:   "第一行\n第二行"
来源：http://dali.zhiwuduotai.top/Article/details/gtnbfctjlv.html

Ruby: "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gtrvbiaytx.html

C#:   "第一行\n第二行"
来源：http://dali.chenlongwang.top/Article/details/gtxbsfsncb.html

[A14] 注释写法
来源：http://dali.iojbl.cn/Article/details/gtplterqrc.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.meibo888.top/Article/details/gtouudptuv.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.haohaochexian.top/Article/details/gtulcofjme.html

JS:   // 单行；/* 多行 */
来源：http://dali.yongpay.top/Article/details/gtiiseihbl.html

TS:   // 单行；/* 多行 */
来源：http://dali.daria6918.cn/Article/details/gtrxsqivnq.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.gogol.net.cn/Article/details/gtxnqljhul.html

Go:   // 单行；/* 多行 */
来源：http://dali.havefunace.top/Article/details/gtinvwypnd.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.bjfxy.top/Article/details/gthbspyuum.html

C#:   // 单行；/* 多行 */
来源：http://dali.iojbl.cn/Article/details/gtanpktili.html

[A15] 空值判断与默认值
来源：http://dali.yueranfly.top/Article/details/gtyfkpzhbl.html

Py:   value = data or "默认值"
来源：http://dali.birdmap.top/Article/details/gtqfxepikd.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.shuidangran.top/Article/details/gtrlzjogwz.html

JS:   const value = data ?? "默认值";
来源：http://dali.daria6918.cn/Article/details/gtidkrnrzu.html

TS:   const value = data ?? "默认值";
来源：http://dali.guowangkeji.top/Article/details/gtlanaqywo.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.birdmap.top/Article/details/gtqslirthv.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.gaohongyu789.top/Article/details/gtupucztfn.html


<!-- 参考信息 -->