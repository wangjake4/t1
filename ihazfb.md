代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.pycfn.com/Article/details/gt2fwzquuaz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.9152youxi.cn/Article/details/gt2ejshvtbr.html

[U92] JS：深拷贝
来源：http://dali.hammf.cn/Article/details/gt2evmoufeo.html

structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gt2ojymjsvj.html

[U93] JS：模板字符串
来源：http://dali.tian-w.cn/Article/details/gt2liswdvdf.html

`共 ${n} 条`
来源：http://dali.jqgfzy.top/Article/details/gt2punvjxnc.html

[U94] JS：箭头函数
来源：http://dali.zycfv.cn/Article/details/gt2xuuxabhr.html

const double = x => x * 2;
来源：http://dali.andypj.xyz/Article/details/gt2ixjldxrn.html

[U95] JS：Promise 包装
来源：http://dali.pycfn.com/Article/details/gt2nmmbikiq.html

new Promise((resolve, reject) => {})
来源：http://dali.daria6918.cn/Article/details/gt2tdjzatrz.html

[U96] JS：async/await 与异常
来源：http://dali.jinqigufen.top/Article/details/gt2feredypm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gt2hketgcxg.html

[U97] JS：并发请求
来源：http://dali.gaohongyu789.top/Article/details/gt2larzpzzv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gt2wlgdditd.html

[U98] JS：fetch 带 JSON
来源：http://dali.jinqigufen.top/Article/details/gt2trlkwqpe.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgbdwto.html

[U99] JS：事件监听
来源：http://dali.0kj1m.cn/Article/details/gt2raisljub.html

el.addEventListener("click", e => {})
来源：http://dali.pycfn.com/Article/details/gt2zznfultz.html

[U100] JS：DOM 查询
来源：http://dali.yueranfly.top/Article/details/gt2ivyfdmlz.html

document.querySelector(".item")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ruphuaqm.html

[U101] JS：classList 操作
来源：http://dali.cqqwz.cn/Article/details/gt2gbthpeze.html

el.classList.toggle("active")
来源：http://dali.meibo888.top/Article/details/gt2ozvugmyv.html

[U102] JS：本地存储
来源：http://dali.sxryk.cn/Article/details/gt2avxbxxjf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.havefunace.top/Article/details/gt2qnoxtsuy.html

[U103] JS：定时器
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2timteotr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yuxming.cn/Article/details/gt2oojproth.html

[U104] JS：防抖
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2axzfvjyd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangshuangyany.cn/Article/details/gt2shfmtdiv.html

[U105] JS：节流
来源：http://dali.yj20258.top/Article/details/gt2dmnoovaw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.kuanghao11.cn/Article/details/gt2htbtekhd.html

[U106] JS：日期格式化
来源：http://dali.ivvv.top/Article/details/gt2xfhypwmp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.chenlongwang.top/Article/details/gt2duqffoet.html

[U107] JS：数字千分位
来源：http://dali.chenzaomai.com/Article/details/gt2luptuots.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kbsvjrqc.html

[U108] JS：随机整数
来源：http://dali.kuanghao11.cn/Article/details/gt2akqsydjr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.wangdashe.top/Article/details/gt2ficiffmt.html

[U109] JS：数组分组
来源：http://dali.shzxlz.cn/Article/details/gt2vnntsatq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.0kj1m.cn/Article/details/gt2zbxpdvvb.html

[U110] JS：数组分块
来源：http://dali.hnxiangtu.top/Article/details/gt2ejphkljs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.daria6918.cn/Article/details/gt2mjgftnyg.html

[U111] JS：对象转 Map
来源：http://dali.havefunace.top/Article/details/gt2tjwljgma.html

new Map(Object.entries(obj))
来源：http://dali.cheryme.top/Article/details/gt2aenmstyr.html

[U112] JS：字符串补位
来源：http://dali.tanke756.top/Article/details/gt2pasbwmzl.html

"7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xmbbyapt.html

[U113] JS：正则替换全部
来源：http://dali.pycfn.com/Article/details/gt2ojcmvddu.html

s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gtijbzfk.html

[U114] JS：JSON 深比较
来源：http://dali.cashguo.top/Article/details/gt2wjgcvkon.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhixingplan.top/Article/details/gt2cbdvubrf.html

[U115] JS：生成 UUID
来源：http://dali.mhx1999.top/Article/details/gt2alkcmauz.html

crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gt2naemytyn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.svipenyu.cn/Article/details/gt2ppqeihhr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hfpthk.cn/Article/details/gt2ymqbrxat.html

[U117] JS：单元测试
来源：http://dali.cashguo.top/Article/details/gt2abutxgxy.html

npm i -D vitest;  npx vitest
来源：http://dali.hysaishi.cn/Article/details/gt2fqzakxqi.html

[U118] JS：开发服务器
来源：http://dali.cdnleiting.top/Article/details/gt2kudcmxwz.html

npm i -D vite;  npx vite
来源：http://dali.chenlongwang.top/Article/details/gt2ybermomt.html

[U119] JS：生产构建
来源：http://dali.hywenlv.cn/Article/details/gt2ssknoqev.html

npx vite build
来源：http://dali.aibaodan.cn/Article/details/gt2fazowbtl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.daria6918.cn/Article/details/gt2fapfivlp.html

import.meta.env.VITE_API_URL
来源：http://dali.chenlongwang.top/Article/details/gt2puobpgqz.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2mhspupof.html

统计汇总
来源：http://dali.kuanghao11.cn/Article/details/gt2skhtkhze.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2trkpsnlx.html

按语言统计（条）：
来源：http://dali.jinqigfzy.top/Article/details/gt2ntkqzeyb.html

Python ......... 252
来源：http://dali.andypj.xyz/Article/details/gt2bkdwphko.html

PHP ............ 252
来源：http://dali.snrcjt.cn/Article/details/gt2hebvzjgx.html

JavaScript ..... 252
来源：http://dali.yongpay.top/Article/details/gt2vmtmyxrf.html

TypeScript ..... 212
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hmwlzhqg.html

Java ........... 212
来源：http://dali.andypj.xyz/Article/details/gt2oefkkcxr.html

Go ............. 212
来源：http://dali.hnqzz.top/Article/details/gt2dneqijpw.html

Ruby ........... 212
来源：http://dali.nanxinkj.top/Article/details/gt2bhjkwqur.html

C# ............. 212
来源：http://dali.0kj1m.cn/Article/details/gt2ynxkolbr.html

C .............. 30
来源：http://dali.xuanzx.com/Article/details/gt2hjtfruvo.html

C++ ............ 30
来源：http://dali.tian-w.cn/Article/details/gt2myubehsd.html

SQL ............ 90
来源：http://dali.yvedp.cn/Article/details/gt2jtomonai.html

Bash ........... 80
来源：http://dali.feifeiyinyue.top/Article/details/gt2plhntylt.html

Kotlin ......... 15
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zufgohva.html

Swift .......... 15
来源：http://dali.yj202588.top/Article/details/gt2sewuvgrb.html

Lua ............ 10
来源：http://dali.iojbl.cn/Article/details/gt2tdgmkthi.html

Perl ........... 10
来源：http://dali.xuanzx.com/Article/details/gt2asxmmidx.html

Scala .......... 10
来源：http://dali.cashguo.top/Article/details/gt2tsxxgtbg.html

------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gt2psmvwzgs.html

合计 ........... 2106 条
来源：http://dali.hnqzz.top/Article/details/gt2leemlkvt.html

按章节统计：
来源：http://dali.yj20258.top/Article/details/gt2uxysrkwp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.vqdsnc.cn/Article/details/gt2dpricutc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ofkqbbca.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.nanxinkj.top/Article/details/gt2ovvknctv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.chenzaomai.com/Article/details/gt2uidctuqo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.gaohongyu789.top/Article/details/gt2mkbqeiep.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jqgufenzy.top/Article/details/gt2vemxftgx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.cashguo.top/Article/details/gt2amincmkm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zycfv.cn/Article/details/gt2zzpazvip.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gt2ywrflvst.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jlsjyb.cn/Article/details/gt2esiudkhy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gt2qwxqfbkg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gt2pstqsszw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gt2vtzojius.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.svipenyu.cn/Article/details/gt2izrlfpgy.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.sufxvd.cn/Article/details/gt2hltddeev.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gt2lbknniiz.html

Q SQL 专题                              90
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2izmaomkb.html

R Bash 专题                             80
来源：http://dali.cashguo.top/Article/details/gt2fdjkolkg.html

S C / C++ 专题                          60
来源：http://dali.zhoulong.xyz/Article/details/gt2nhjroqsl.html

T 其他语言补充                          60
来源：http://dali.zhoulong.xyz/Article/details/gt2bhnfswor.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2vsoiogmr.html

------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gt2elfkixdd.html

合计                                  2106 条
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zzvfhspt.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gt2wybybqfo.html

使用提醒
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vrtyndef.html

--------------------------------------------------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ttlopqzs.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cashguo.top/Article/details/gt2hdjoyjmg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yvedp.cn/Article/details/gt2avnybzdl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ehwqpu.com/Article/details/gt2nfxnhrzf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.meibo888.top/Article/details/gt2biogjuwp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.aibaodan.cn/Article/details/gt2oovwlszu.html

—— 文件结束 ——
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sxufwrgr.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2rkqvtlbi.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cqieawpa.html

Common Programming Examples Cheat Book
来源：http://dali.cqqwz.cn/Article/details/gt2egprbzvd.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2kzzlifcs.html

【收录内容】
来源：http://dali.mhx1999.top/Article/details/gt2hpaaqunf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jinqigfzy.top/Article/details/gt2zaonmhjg.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.guannengcc.top/Article/details/gt2nwsurybp.html

SQL · Bash · C · C++
来源：http://dali.iojbl.cn/Article/details/gt2nuimiard.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hysaishi.cn/Article/details/gt2eqtuowhc.html

【使用说明】
来源：http://dali.nanxuanxn.top/Article/details/gt2hffzepwo.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.gzhubu.top/Article/details/gt2cvtndkua.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.andypj.xyz/Article/details/gt2djximlld.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.sweek.top/Article/details/gt2bzoumukj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2czbrvxrj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yonumen.top/Article/details/gt2lxbpjwjw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gnewknlo.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.dianchejie.cn/Article/details/gt2ucuyvgox.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.svipenyu.cn/Article/details/gt2bqlsgfel.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.bjfxy.top/Article/details/gt2ahvorgho.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yongpay.top/Article/details/gt2oqixeyjn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jqgfzy.top/Article/details/gt2tspwiojm.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.shangyingyoupin.top/Article/details/gt2fjujcabn.html

【文件统计】
来源：http://dali.sysykeji.top/Article/details/gt2cxeovhqq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.mhx1999.top/Article/details/gt2exxggvnp.html

--------------------------------------------------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gt2ebtvunyb.html

目  录
来源：http://dali.quarkkingdee.top/Article/details/gt2cokisuwu.html

--------------------------------------------------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2psblqtgk.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yvedp.cn/Article/details/gt2xsnbxouv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yvedp.cn/Article/details/gt2gmmdnjgt.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xxvjohwl.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.aibaodan.cn/Article/details/gt2gvxfvhuw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yueranfly.top/Article/details/gt2jhxfqmmw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hnqzz.top/Article/details/gt2ayhdlqwa.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2fsqubizm.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ivvv.top/Article/details/gt2qsephrqy.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gt2vaogvquc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.haohaochexian.top/Article/details/gt2qqrobnbt.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yvedp.cn/Article/details/gt2vzgopidj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gt2tpqgnphd.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gt2piapnxvu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yuxming.cn/Article/details/gt2hhszcyce.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2zmaajwzy.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yj20258888.top/Article/details/gt2ezmxrrxb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cashguo.top/Article/details/gt2gfzjpqrk.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2tvrsdtvc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yj20258888.top/Article/details/gt2svvkmmfh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xziqi.cn/Article/details/gt2pugospvo.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ebsustxu.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wfewlvqi.html

A. 基础语法与类型
来源：http://dali.nanxuanxn.top/Article/details/gt2mpmdkyww.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2fqbderft.html

[A01] Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2hzhszirk.html

Py:   print("Hello, World!")
来源：http://dali.tianlin.xyz/Article/details/gt2wvzsnapz.html

PHP:  echo "Hello, World!";
来源：http://dali.mhx1999.top/Article/details/gt2tgypncqg.html

JS:   console.log("Hello, World!");
来源：http://dali.haohaochexian.top/Article/details/gt2ezvcxnrt.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.smart0.xyz/Article/details/gt2jfdetjdt.html

Java: System.out.println("Hello, World!");
来源：http://dali.yj20258888.top/Article/details/gt2mjfalqqz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sweek.top/Article/details/gt2qsuwqaih.html

Ruby: puts "Hello, World!"
来源：http://dali.pycfn.com/Article/details/gt2mjlrwmcw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.nanxinkj.top/Article/details/gt2gznfgiiu.html

[A02] 变量声明与赋值
来源：http://dali.sxryk.cn/Article/details/gt2dqiwgqew.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yj20258.top/Article/details/gt2lnusbvui.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kxlxjsmr.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.iojbl.cn/Article/details/gt2iybkzrax.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.kuanghao11.cn/Article/details/gt2txdxxdic.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hnluqygs.html

Go:   name := "Alex"; age := 20
来源：http://dali.cucudq.cn/Article/details/gt2mynbsxbs.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xuanzx.com/Article/details/gt2rhzuyerx.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.meibo888.top/Article/details/gt2fwenuelf.html

[A03] 常量定义
来源：http://dali.316326.xyz/Article/details/gt2qglzjmor.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.nanxinkj.top/Article/details/gt2yasbbrme.html

PHP:  const PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gt2udgickwj.html

JS:   const PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gt2knfyyhyr.html

TS:   const PI: number = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gt2bqhudezp.html

Java: static final double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gt2cyfyjoyl.html

Go:   const PI = 3.14159
来源：http://dali.daria6918.cn/Article/details/gt2qsvjoxdz.html

Ruby: PI = 3.14159
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kjekwxzw.html

C#:   const double PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gt2ziwcfgfr.html

[A04] 判断变量类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2ovecpccb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jgtfmssc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.guannengcc.top/Article/details/gt2bzhvwjut.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jinqigfzy.top/Article/details/gt2atefolyc.html

TS:   typeof x; x instanceof Date
来源：http://dali.jianghu66.top/Article/details/gt2gbeqyrcc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.pengpengdd.cyou/Article/details/gt2dukktdby.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.tian-w.cn/Article/details/gt2qjkdslnp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.hammf.cn/Article/details/gt2rbfmymqt.html

C#:   x.GetType().Name; x is int
来源：http://dali.andypj.xyz/Article/details/gt2pafxyhth.html

[A05] 整数除法与取模
来源：http://dali.hongshengwenyu.top/Article/details/gt2emysraqg.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.wangdashe.top/Article/details/gt2lnzzcmbl.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yuxming.cn/Article/details/gt2tomnwosu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.meibo888.top/Article/details/gt2xfwlnjis.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zycfv.cn/Article/details/gt2nxljjmok.html

Java: 7 / 2; 7 % 2
来源：http://dali.hammf.cn/Article/details/gt2mwgmyutp.html

Go:   7 / 2; 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iligungd.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.nanxuanxn.top/Article/details/gt2lkccdwnz.html

C#:   7 / 2; 7 % 2
来源：http://dali.daria6918.cn/Article/details/gt2lonrwhgv.html

[A06] 字符串转数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cuejgmts.html

Py:   int("42"); float("3.14")
来源：http://dali.yonumen.top/Article/details/gt2luipvirj.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cashguo.top/Article/details/gt2uoluxjya.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zycfv.cn/Article/details/gt2lqlduonj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.nanxuanxn.top/Article/details/gt2igaerdoq.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zycfv.cn/Article/details/gt2bizubsrf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ybcxt.top/Article/details/gt2kivqayib.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.pengpengdd.cyou/Article/details/gt2fnikandj.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhiwuduotai.top/Article/details/gt2mjxmdiek.html

[A07] 数字转字符串
来源：http://dali.chenzaomai.com/Article/details/gt2rbvcyhfo.html

Py:   str(42)
来源：http://dali.ivvv.top/Article/details/gt2behpervw.html

PHP:  (string) 42; strval(42)
来源：http://dali.nanxinkj.top/Article/details/gt2gmkzaola.html

JS:   String(42); (42).toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aznusdqa.html

TS:   String(42)
来源：http://dali.hysaishi.cn/Article/details/gt2sygifwbg.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.hongshengwenyu.top/Article/details/gt2iknswkgt.html

Go:   strconv.Itoa(42)
来源：http://dali.andypj.xyz/Article/details/gt2nuaivtkk.html

Ruby: 42.to_s
来源：http://dali.smart0.xyz/Article/details/gt2beitxcfb.html

C#:   42.ToString()
来源：http://dali.fzhhl.top/Article/details/gt2lkzietuv.html

[A08] 取整与四舍五入
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pemgzkzc.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hfpthk.cn/Article/details/gt2blvvtqeh.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2omdyqswa.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.meibo888.top/Article/details/gt2ksoituwe.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.nanxinkj.top/Article/details/gt2tkzkyfsa.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jyoumei.cn/Article/details/gt2buwfjjqd.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yongpay.top/Article/details/gt2sfjnspwv.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhengqikj.top/Article/details/gt2ycelmypb.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hammf.cn/Article/details/gt2lxxvyqkk.html

[A09] 绝对值与最大最小值
来源：http://dali.xziqi.cn/Article/details/gt2sbeeucqf.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xuanzx.com/Article/details/gt2vhbjevbs.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gt2bpsemypy.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.shuidangran.top/Article/details/gt2jcagtzhi.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.daxiang520.top/Article/details/gt2sktoutnh.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gt2segkdomj.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.cdnleiting.top/Article/details/gt2wbsqtjam.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.xuetiantiany.cn/Article/details/gt2qwqwwrju.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.tian-w.cn/Article/details/gt2rvvecrvi.html

[A10] 生成随机数
来源：http://dali.yueranfly.top/Article/details/gt2argrouyz.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jqgfzy.top/Article/details/gt2qgurhhbk.html

PHP:  random_int(1, 100);
来源：http://dali.316326.xyz/Article/details/gt2mttbpebm.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jiagoushi.top/Article/details/gt2gnuuhdmp.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.gzhubu.top/Article/details/gt2jexbtvdx.html

Java: new Random().nextInt(100) + 1
来源：http://dali.snrcjt.cn/Article/details/gt2kmvxsasp.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hywenlv.cn/Article/details/gt2noqthvnc.html

Ruby: rand(1..100)
来源：http://dali.xuanzx.com/Article/details/gt2ysakhinb.html

C#:   new Random().Next(1, 101)
来源：http://dali.bjfxy.top/Article/details/gt2tgceqvqh.html

[A11] 条件表达式（三元）
来源：http://dali.chenlongwang.top/Article/details/gt2aeziknft.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eiosdnkn.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.andypj.xyz/Article/details/gt2zxrcuzbl.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jinqigufen.top/Article/details/gt2rdkausuw.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.tian-w.cn/Article/details/gt2zipthkim.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.cashguo.top/Article/details/gt2byxxjeld.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.shangyingyoupin.top/Article/details/gt2zfhvwgol.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.c1oappe.top/Article/details/gt2niuowacd.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.dashuyun.cn/Article/details/gt2jtijmtvj.html

[A12] 字符串插值 / 格式化
来源：http://dali.pengpengdd.cyou/Article/details/gt2xjtjcemm.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.nwbrower.top/Article/details/gt2cwfnxyng.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mzoapvwl.html

JS:   `Hello, ${name}!`
来源：http://dali.hywenlv.cn/Article/details/gt2myfxbuhk.html

TS:   `Hello, ${name}!`
来源：http://dali.hammf.cn/Article/details/gt2kzawowow.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bkjgcdry.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jqgfzy.top/Article/details/gt2qgyazqhl.html

Ruby: "Hello, #{name}!"
来源：http://dali.chenjidiqi.icu/Article/details/gt2toeobuat.html

C#:   $"Hello, {name}!"
来源：http://dali.yj20258888.top/Article/details/gt2euainazj.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.quarkkingdee.top/Article/details/gt2mngpqyfg.html

Py:   "第一行\n第二行"
来源：http://dali.yj20258888.top/Article/details/gt2sspstasd.html

PHP:  "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gt2rmrqxrwg.html

JS:   "第一行\n第二行"
来源：http://dali.gaohongyu789.top/Article/details/gt2llalabof.html

TS:   "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ylvhfxhp.html

Java: "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gt2deyvyswv.html

Go:   "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gt2fgpydhqo.html

Ruby: "第一行\n第二行"
来源：http://dali.daxiang520.top/Article/details/gt2ocmnwfme.html

C#:   "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gt2kgrhymdj.html

[A14] 注释写法
来源：http://dali.fengsongda.top/Article/details/gt2twlhgayk.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.ydzc1.top/Article/details/gt2avjjbfis.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.smart0.xyz/Article/details/gt2cuefkmlx.html

JS:   // 单行；/* 多行 */
来源：http://dali.xinyue.icu/Article/details/gt2utnqifxz.html

TS:   // 单行；/* 多行 */
来源：http://dali.aizwys.cn/Article/details/gt2bdgbvspw.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.9152youxi.cn/Article/details/gt2pcumzgua.html

Go:   // 单行；/* 多行 */
来源：http://dali.jqgfzy.top/Article/details/gt2rpqeiofs.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yj20258888.top/Article/details/gt2xdwvnlsa.html

C#:   // 单行；/* 多行 */
来源：http://dali.shangyingyoupin.top/Article/details/gt2pjzfzkvt.html

[A15] 空值判断与默认值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vppoorfe.html

Py:   value = data or "默认值"
来源：http://dali.nanxinkj.top/Article/details/gt2nrugrhpy.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.hysaishi.cn/Article/details/gt2vonozhpa.html

JS:   const value = data ?? "默认值";
来源：http://dali.fengsongda.top/Article/details/gt2aizpjesy.html

TS:   const value = data ?? "默认值";
来源：http://dali.ybcxt.top/Article/details/gt2zuczwpfj.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.hnxiangtu.top/Article/details/gt2suqlcdlo.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.xziqi.cn/Article/details/gt2uxiyybdm.html


<!-- 参考信息 -->