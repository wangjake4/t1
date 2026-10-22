代发 wailian999

[U99] JS：事件监听
来源：http://dali.yj20258888.top/Article/details/gt2lvmpdelr.html

el.addEventListener("click", e => {})
来源：http://dali.hnxiangtu.top/Article/details/gt2pkkmcxpa.html

[U100] JS：DOM 查询
来源：http://dali.jinqigufen.top/Article/details/gt2jnmxnjyc.html

document.querySelector(".item")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rqkcdqey.html

[U101] JS：classList 操作
来源：http://dali.iojbl.cn/Article/details/gt2nrclfolk.html

el.classList.toggle("active")
来源：http://dali.hysaishi.cn/Article/details/gt2pyzjnmjc.html

[U102] JS：本地存储
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hkhzphfg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yongpay.top/Article/details/gt2dqzboxuv.html

[U103] JS：定时器
来源：http://dali.cqqwz.cn/Article/details/gt2wbibjeez.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.dianchejie.cn/Article/details/gt2gtbmuaft.html

[U104] JS：防抖
来源：http://dali.sweek.top/Article/details/gt2tpnswfwn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cdnleiting.top/Article/details/gt2mjstoane.html

[U105] JS：节流
来源：http://dali.quarkkingdee.top/Article/details/gt2resseaty.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.birdmap.top/Article/details/gt2izvmzgsw.html

[U106] JS：日期格式化
来源：http://dali.redwolf501.top/Article/details/gt2eiiocfzl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.316326.xyz/Article/details/gt2andrunto.html

[U107] JS：数字千分位
来源：http://dali.yanxiufei.cn/Article/details/gt2gkkcprke.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gt2birepvrl.html

[U108] JS：随机整数
来源：http://dali.xinyue.icu/Article/details/gt2ghersfcn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.snrcjt.cn/Article/details/gt2chwfpvyd.html

[U109] JS：数组分组
来源：http://dali.cucudq.cn/Article/details/gt2czeiyesz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ydzc1.top/Article/details/gt2yocaabcw.html

[U110] JS：数组分块
来源：http://dali.chenlongwang.top/Article/details/gt2lwgyrizu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.guowangkeji.top/Article/details/gt2ibzlfsyy.html

[U111] JS：对象转 Map
来源：http://dali.yanxiufei.cn/Article/details/gt2cycbdwhr.html

new Map(Object.entries(obj))
来源：http://dali.redwolf501.top/Article/details/gt2pkxowhct.html

[U112] JS：字符串补位
来源：http://dali.jianghu66.top/Article/details/gt2ypzfkrqj.html

"7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gt2vjqwzjyp.html

[U113] JS：正则替换全部
来源：http://dali.zhengqikj.top/Article/details/gt2uotejulq.html

s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2khaczara.html

[U114] JS：JSON 深比较
来源：http://dali.jyoumei.cn/Article/details/gt2xfuwuysj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cqqwz.cn/Article/details/gt2dsbehejw.html

[U115] JS：生成 UUID
来源：http://dali.jlsjyb.cn/Article/details/gt2ufmntnyc.html

crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gt2yhpdgckd.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.9152youxi.cn/Article/details/gt2aveiqdnl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zycfv.cn/Article/details/gt2sulcvtmn.html

[U117] JS：单元测试
来源：http://dali.jinqigufen.top/Article/details/gt2bcvuqrmb.html

npm i -D vitest;  npx vitest
来源：http://dali.zycfv.cn/Article/details/gt2lgzqnjex.html

[U118] JS：开发服务器
来源：http://dali.hongshengwenyu.top/Article/details/gt2bnvxiifp.html

npm i -D vite;  npx vite
来源：http://dali.hfpthk.cn/Article/details/gt2bgqsefve.html

[U119] JS：生产构建
来源：http://dali.redwolf501.top/Article/details/gt2tsznjucs.html

npx vite build
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pimiihjs.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hfpthk.cn/Article/details/gt2htpajyoh.html

import.meta.env.VITE_API_URL
来源：http://dali.ydzc1.top/Article/details/gt2fiywgblq.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2kkgunopt.html

统计汇总
来源：http://dali.cucudq.cn/Article/details/gt2sutmetdw.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2hrzagljh.html

按语言统计（条）：
来源：http://dali.haohaochexian.top/Article/details/gt2yzweuszo.html

Python ......... 252
来源：http://dali.aibaodan.cn/Article/details/gt2fmxwdqst.html

PHP ............ 252
来源：http://dali.xuanzx.com/Article/details/gt2ayggrhfc.html

JavaScript ..... 252
来源：http://dali.havefunace.top/Article/details/gt2fydpdigc.html

TypeScript ..... 212
来源：http://dali.haohaochexian.top/Article/details/gt2juepztxi.html

Java ........... 212
来源：http://dali.316326.xyz/Article/details/gt2qkrxprlw.html

Go ............. 212
来源：http://dali.zhongyouzk.top/Article/details/gt2ndluwnkj.html

Ruby ........... 212
来源：http://dali.shanyushiyangtech.top/Article/details/gt2epazrdjt.html

C# ............. 212
来源：http://dali.cqqwz.cn/Article/details/gt2kqcyevxx.html

C .............. 30
来源：http://dali.fengsongda.top/Article/details/gt2abtznnhz.html

C++ ............ 30
来源：http://dali.zhiwuduotai.top/Article/details/gt2dvcszsvt.html

SQL ............ 90
来源：http://dali.ivvv.top/Article/details/gt2fogdwqpk.html

Bash ........... 80
来源：http://dali.xziqi.cn/Article/details/gt2ljxffqvv.html

Kotlin ......... 15
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rclmnhqu.html

Swift .......... 15
来源：http://dali.pycfn.com/Article/details/gt2vtvswlkh.html

Lua ............ 10
来源：http://dali.gzhubu.top/Article/details/gt2jyvnzmcq.html

Perl ........... 10
来源：http://dali.tian-w.cn/Article/details/gt2svtweljd.html

Scala .......... 10
来源：http://dali.gaohongyu789.top/Article/details/gt2dzvzajdc.html

------------------------------------
来源：http://dali.ivvv.top/Article/details/gt2tvjcbtkw.html

合计 ........... 2106 条
来源：http://dali.ehwqpu.com/Article/details/gt2rokfliku.html

按章节统计：
来源：http://dali.fzhhl.top/Article/details/gt2oybhsqya.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ivvv.top/Article/details/gt2yzqbftio.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.quarkkingdee.top/Article/details/gt2jhhgjedz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gt2qyjzyhvt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.0kj1m.cn/Article/details/gt2verexcqi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.kuanghao11.cn/Article/details/gt2fgkgjbqi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jinqigfzy.top/Article/details/gt2xrccoeey.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vtndtgug.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xfgpgfpd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gt2uwmpjkpb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hysaishi.cn/Article/details/gt2anibbjov.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gt2ilfghoza.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gt2mczbiiyu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gt2hkadzrkw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hfpthk.cn/Article/details/gt2dxihpytp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lvfhpoei.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xuanzx.com/Article/details/gt2gtzgpizo.html

Q SQL 专题                              90
来源：http://dali.tanke756.top/Article/details/gt2kwqvpdwp.html

R Bash 专题                             80
来源：http://dali.yongpay.top/Article/details/gt2jtvosung.html

S C / C++ 专题                          60
来源：http://dali.pengpengdd.cyou/Article/details/gt2zsqgpxod.html

T 其他语言补充                          60
来源：http://dali.nanxuanxn.top/Article/details/gt2rqgvaurl.html

U 高频实用片段                         120
来源：http://dali.andypj.xyz/Article/details/gt2xxbtlmek.html

------------------------------------
来源：http://dali.c1oappe.top/Article/details/gt2bwajmsig.html

合计                                  2106 条
来源：http://dali.pycfn.com/Article/details/gt2btbsltie.html

--------------------------------------------------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gt2njrruqym.html

使用提醒
来源：http://dali.tianlin.xyz/Article/details/gt2bwvtdvfl.html

--------------------------------------------------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gt2wqifvfde.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.guowangkeji.top/Article/details/gt2agjwmbdr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.gotoacloud.top/Article/details/gt2mgglqsgo.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.sufxvd.cn/Article/details/gt2bepsysaf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jiagoushi.top/Article/details/gt2wrqghunp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.sufxvd.cn/Article/details/gt2shfgzbmo.html

—— 文件结束 ——
来源：http://dali.tian-w.cn/Article/details/gt2xeyzrrhz.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2zttglvdq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2esyvigvr.html

Common Programming Examples Cheat Book
来源：http://dali.mhx1999.top/Article/details/gt2zqfunbmf.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sdynsxya.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwcbyzd.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhiwuduotai.top/Article/details/gt2yysaklai.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xziqi.cn/Article/details/gt2cgulqswb.html

SQL · Bash · C · C++
来源：http://dali.bjfxy.top/Article/details/gt2wxfzofsh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.smart0.xyz/Article/details/gt2rpeadbnd.html

【使用说明】
来源：http://dali.yvedp.cn/Article/details/gt2lzvpsqee.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.daria6918.cn/Article/details/gt2vubyrhjc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yanxiufei.cn/Article/details/gt2cuglxkfe.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.sufxvd.cn/Article/details/gt2boqybpdz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shangyingyoupin.top/Article/details/gt2trgnilub.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jianghu66.top/Article/details/gt2vhimyohk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hywenlv.cn/Article/details/gt2hgntmqhd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.iojbl.cn/Article/details/gt2rpqmqujy.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jqgfzy.top/Article/details/gt2amdsgzeg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.dashuyun.cn/Article/details/gt2qcbqqbcj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.gaohongyu789.top/Article/details/gt2rsmtodzg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ehwqpu.com/Article/details/gt2vfylgxev.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tvtucept.html

【文件统计】
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lgzrbegf.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.snrcjt.cn/Article/details/gt2pdnqjonj.html

--------------------------------------------------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zgmgzyje.html

目  录
来源：http://dali.xziqi.cn/Article/details/gt2fygtfidc.html

--------------------------------------------------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gt2rxzofmac.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yuxming.cn/Article/details/gt2rvdwjogb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.c1oappe.top/Article/details/gt2pbnfdnhc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ipvtazjf.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2hltoywyb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jianghu66.top/Article/details/gt2vokppvfm.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.sufxvd.cn/Article/details/gt2ownfoxte.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.c1oappe.top/Article/details/gt2vnlljswq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jqgfzy.top/Article/details/gt2yrrajyio.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xylfe.cn/Article/details/gt2lsqxosla.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.tanke756.top/Article/details/gt2qnqfazmg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.pycfn.com/Article/details/gt2zjjuscgn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gt2pdikvnfx.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gt2ajjvzftv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.tianlin.xyz/Article/details/gt2skgrlvgv.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.redwolf501.top/Article/details/gt2umuwfezi.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gt2escivkxt.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hammf.cn/Article/details/gt2cxipjcyb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.svipenyu.cn/Article/details/gt2govnmlty.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.mhx1999.top/Article/details/gt2yuxgcsuy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aizwys.cn/Article/details/gt2uuosvpta.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2bibgtcqs.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2zwpnydfv.html

A. 基础语法与类型
来源：http://dali.quarkkingdee.top/Article/details/gt2kjztaopn.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2qmjgslcg.html

[A01] Hello World
来源：http://dali.birdmap.top/Article/details/gt2uhcoazdu.html

Py:   print("Hello, World!")
来源：http://dali.cqqwz.cn/Article/details/gt2mmyuugnp.html

PHP:  echo "Hello, World!";
来源：http://dali.hammf.cn/Article/details/gt2ydvafmll.html

JS:   console.log("Hello, World!");
来源：http://dali.haohaochexian.top/Article/details/gt2oovdgjdp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.gaohongyu789.top/Article/details/gt2gtifiabf.html

Java: System.out.println("Hello, World!");
来源：http://dali.jiagoushi.top/Article/details/gt2byaahcvq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hnxiangtu.top/Article/details/gt2vkceaqei.html

Ruby: puts "Hello, World!"
来源：http://dali.jianghu66.top/Article/details/gt2ruwmrczx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.sufxvd.cn/Article/details/gt2pbmocycj.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkqbieb.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yj20258.top/Article/details/gt2bubpeblw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.kuanghao11.cn/Article/details/gt2rsahmnkc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xylfe.cn/Article/details/gt2tptezbud.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yuanzhike.top/Article/details/gt2echmrezp.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xinyue.icu/Article/details/gt2xedefrly.html

Go:   name := "Alex"; age := 20
来源：http://dali.yonumen.top/Article/details/gt2nykgwdac.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gogol.net.cn/Article/details/gt2hothhovw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zycfv.cn/Article/details/gt2lgsbsapf.html

[A03] 常量定义
来源：http://dali.gotoacloud.top/Article/details/gt2zfxkzdcd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.meibo888.top/Article/details/gt2dogbybgu.html

PHP:  const PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gt2hspybbig.html

JS:   const PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gt2zamntqfg.html

TS:   const PI: number = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gt2ftocrnqg.html

Java: static final double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gt2gsdqhqmy.html

Go:   const PI = 3.14159
来源：http://dali.wangdashe.top/Article/details/gt2mfduvabm.html

Ruby: PI = 3.14159
来源：http://dali.wangshuangyany.cn/Article/details/gt2ktajirxb.html

C#:   const double PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gt2firgrnal.html

[A04] 判断变量类型
来源：http://dali.havefunace.top/Article/details/gt2vtjeenlr.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.snrcjt.cn/Article/details/gt2lgmnjcma.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.svipenyu.cn/Article/details/gt2lmtdwxul.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yuxming.cn/Article/details/gt2epieoppn.html

TS:   typeof x; x instanceof Date
来源：http://dali.chenzaomai.com/Article/details/gt2ilmtlsgm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.birdmap.top/Article/details/gt2lbxktznb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.nanxinkj.top/Article/details/gt2wternbtm.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yueranfly.top/Article/details/gt2ufawlnlo.html

C#:   x.GetType().Name; x is int
来源：http://dali.redwolf501.top/Article/details/gt2twxsmmzn.html

[A05] 整数除法与取模
来源：http://dali.jinqigufen.top/Article/details/gt2scusrbps.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhengqikj.top/Article/details/gt2nblzmufs.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.gogol.net.cn/Article/details/gt2lzfxxhae.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.fengsongda.top/Article/details/gt2kzqcxnur.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gt2xwexpyif.html

Java: 7 / 2; 7 % 2
来源：http://dali.wangdashe.top/Article/details/gt2oastfehl.html

Go:   7 / 2; 7 % 2
来源：http://dali.yj202588.top/Article/details/gt2hqlyduqn.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gt2ljaqihzv.html

C#:   7 / 2; 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gt2jlhwpisx.html

[A06] 字符串转数字
来源：http://dali.birdmap.top/Article/details/gt2eahlbxgm.html

Py:   int("42"); float("3.14")
来源：http://dali.yueranfly.top/Article/details/gt2ieigksfx.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.gotoacloud.top/Article/details/gt2eoedkzxw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.sysykeji.top/Article/details/gt2cdiolrkr.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.gogol.net.cn/Article/details/gt2zrdednmq.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yuxming.cn/Article/details/gt2xjqogwnh.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.kuanghao11.cn/Article/details/gt2eevnpiej.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.chenzaomai.com/Article/details/gt2fijtekma.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jianghu66.top/Article/details/gt2vredmbpz.html

[A07] 数字转字符串
来源：http://dali.jinqigufen.top/Article/details/gt2ktjfnwza.html

Py:   str(42)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pelnwbxo.html

PHP:  (string) 42; strval(42)
来源：http://dali.fzhhl.top/Article/details/gt2ibgyteuo.html

JS:   String(42); (42).toString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2jpatkcgu.html

TS:   String(42)
来源：http://dali.aizwys.cn/Article/details/gt2pykiaqec.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jinqigufen.top/Article/details/gt2zqnsqevh.html

Go:   strconv.Itoa(42)
来源：http://dali.ppjwa.cn/Article/details/gt2bxfvbydz.html

Ruby: 42.to_s
来源：http://dali.feifeiyinyue.top/Article/details/gt2wrxjdfiy.html

C#:   42.ToString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2rfxtgyzi.html

[A08] 取整与四舍五入
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2owzhkgbj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.shzxlz.cn/Article/details/gt2qdnnysxc.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.kuanghao11.cn/Article/details/gt2kganzyfj.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.redwolf501.top/Article/details/gt2usbmkxxz.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yanxiufei.cn/Article/details/gt2yzndkpbc.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.redwolf501.top/Article/details/gt2iicszocg.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.pengpengdd.cyou/Article/details/gt2suasgeef.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cvimdnbk.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.redwolf501.top/Article/details/gt2aefqhypg.html

[A09] 绝对值与最大最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2brndbcmy.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ivvv.top/Article/details/gt2qpyjvvfe.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hfpthk.cn/Article/details/gt2nejovnyd.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gt2zrlffiwv.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2ttmwimyd.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.aizwys.cn/Article/details/gt2zarafbjm.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.meibo888.top/Article/details/gt2vhdovyqr.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.vqdsnc.cn/Article/details/gt2qogxsebr.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tuzlbuls.html

[A10] 生成随机数
来源：http://dali.vqdsnc.cn/Article/details/gt2mefzizyb.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jianghu66.top/Article/details/gt2qpwooodc.html

PHP:  random_int(1, 100);
来源：http://dali.nanxuanxn.top/Article/details/gt2upcqnuib.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.gzhubu.top/Article/details/gt2wacjbnyc.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hysaishi.cn/Article/details/gt2tbosxpkm.html

Java: new Random().nextInt(100) + 1
来源：http://dali.svipenyu.cn/Article/details/gt2xngrzfbl.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yj202588.top/Article/details/gt2gtefifsr.html

Ruby: rand(1..100)
来源：http://dali.quarkkingdee.top/Article/details/gt2evqmfdso.html

C#:   new Random().Next(1, 101)
来源：http://dali.yj20258888.top/Article/details/gt2bbkckmxn.html

[A11] 条件表达式（三元）
来源：http://dali.yvedp.cn/Article/details/gt2yfxvqeop.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.pengpengdd.cyou/Article/details/gt2lvqmmldg.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.iojbl.cn/Article/details/gt2hncssqtv.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.nanxuanxn.top/Article/details/gt2lqvizfji.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.fzhhl.top/Article/details/gt2hjdeqrdw.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yanxiufei.cn/Article/details/gt2okkodepz.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.xinyue.icu/Article/details/gt2skebdrge.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.hfpthk.cn/Article/details/gt2awtuhoex.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2donfuofe.html

[A12] 字符串插值 / 格式化
来源：http://dali.cheryme.top/Article/details/gt2rxinwmax.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.mhx1999.top/Article/details/gt2gblfxtms.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.daxiang520.top/Article/details/gt2lnlybaiz.html

JS:   `Hello, ${name}!`
来源：http://dali.jlsjyb.cn/Article/details/gt2qpstmppr.html

TS:   `Hello, ${name}!`
来源：http://dali.hammf.cn/Article/details/gt2xcihwupi.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jyoumei.cn/Article/details/gt2etduueir.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.vqdsnc.cn/Article/details/gt2jrypoixu.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yazlcizh.html

C#:   $"Hello, {name}!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wjcpbatd.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.cucudq.cn/Article/details/gt2spqtvwaz.html

Py:   "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oajatgac.html

PHP:  "第一行\n第二行"
来源：http://dali.xuanzx.com/Article/details/gt2alsqmawb.html

JS:   "第一行\n第二行"
来源：http://dali.sxryk.cn/Article/details/gt2pwuhpvot.html

TS:   "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gt2tdlraawr.html

Java: "第一行\n第二行"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hvbcihvp.html

Go:   "第一行\n第二行"
来源：http://dali.gaohongyu789.top/Article/details/gt2htszwzmp.html

Ruby: "第一行\n第二行"
来源：http://dali.guowangkeji.top/Article/details/gt2rverulwb.html

C#:   "第一行\n第二行"
来源：http://dali.yangfankeji.com/Article/details/gt2fegjcdmi.html

[A14] 注释写法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vzmgmiyj.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.shuidangran.top/Article/details/gt2xpzqqwgd.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jyoumei.cn/Article/details/gt2lxovduvz.html

JS:   // 单行；/* 多行 */
来源：http://dali.xinyue.icu/Article/details/gt2bpfhhlse.html

TS:   // 单行；/* 多行 */
来源：http://dali.xylfe.cn/Article/details/gt2ukupvqig.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hongshengwenyu.top/Article/details/gt2seysxukg.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhoulong.xyz/Article/details/gt2gravpxgd.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.vqdsnc.cn/Article/details/gt2wbevjihc.html

C#:   // 单行；/* 多行 */
来源：http://dali.mhx1999.top/Article/details/gt2efwqolcd.html

[A15] 空值判断与默认值
来源：http://dali.tanke756.top/Article/details/gt2apcesjaq.html

Py:   value = data or "默认值"
来源：http://dali.yuanzhike.top/Article/details/gt2nyvfsdti.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhengqikj.top/Article/details/gt2hwdejphk.html

JS:   const value = data ?? "默认值";
来源：http://dali.daxiang520.top/Article/details/gt2cqjcghek.html

TS:   const value = data ?? "默认值";
来源：http://dali.jianghu66.top/Article/details/gt2omyrxtkv.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.cashguo.top/Article/details/gt2zwjjykzp.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.ivvv.top/Article/details/gt2ojasmxcw.html

Ruby: value = data || "默认值"
来源：http://dali.9152youxi.cn/Article/details/gt2kvnlmahk.html

C#:   var value = data ?? "默认值";
来源：http://dali.birdmap.top/Article/details/gt2dgjwhccj.html

[A16] 真假值判断规则
来源：http://dali.tianlin.xyz/Article/details/gt2waniivgm.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.haohaochexian.top/Article/details/gt2sxmllccp.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zycfv.cn/Article/details/gt2aiqwtzqg.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.bjfxy.top/Article/details/gt2enzadugy.html

TS:   if (!x) {}
来源：http://dali.guannengcc.top/Article/details/gt2lmsuvxpx.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.nanxinkj.top/Article/details/gt2oorqdscp.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.nanxuanxn.top/Article/details/gt2gtxjsbqm.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.tianlin.xyz/Article/details/gt2fptglqhs.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.haohaochexian.top/Article/details/gt2pncwbkte.html

[A17] 位运算
来源：http://dali.cdnleiting.top/Article/details/gt2abifsbin.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gt2enzzucaj.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.cheryme.top/Article/details/gt2lskcjjpx.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yangfankeji.com/Article/details/gt2dcnectvg.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ycxrbkdd.html


<!-- 参考信息 -->