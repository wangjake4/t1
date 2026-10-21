代发 wailian999

[U87] JS：解构默认值
来源：http://dali.yvedp.cn/Article/details/gtiekfuoha.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hammf.cn/Article/details/gtsoipwmke.html

[U88] JS：对象展开合并
来源：http://dali.hnqzz.top/Article/details/gtpsmqcute.html

{ ...a, ...b }
来源：http://dali.vqdsnc.cn/Article/details/gtnthriima.html

[U89] JS：数组去重
来源：http://dali.hfpthk.cn/Article/details/gteevhqnuc.html

[...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gtbmzabint.html

[U90] JS：数字数组排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtclwqiurz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtvkzhtqdr.html

[U91] JS：对象键值遍历
来源：http://dali.tian-w.cn/Article/details/gttdblczca.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xinyue.icu/Article/details/gtezielbmw.html

[U92] JS：深拷贝
来源：http://dali.xziqi.cn/Article/details/gtianwdbje.html

structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtugjjotoi.html

[U93] JS：模板字符串
来源：http://dali.yuxming.cn/Article/details/gtavdbtlnm.html

`共 ${n} 条`
来源：http://dali.xuetiantiany.cn/Article/details/gtliwqoyeq.html

[U94] JS：箭头函数
来源：http://dali.daria6918.cn/Article/details/gtkbombjdu.html

const double = x => x * 2;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjffbfmsy.html

[U95] JS：Promise 包装
来源：http://dali.kuanghao11.cn/Article/details/gtrzdgtsqd.html

new Promise((resolve, reject) => {})
来源：http://dali.0kj1m.cn/Article/details/gthydjrfrt.html

[U96] JS：async/await 与异常
来源：http://dali.zhiwuduotai.top/Article/details/gttrosfqkq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gtgwivuzpn.html

[U97] JS：并发请求
来源：http://dali.jlsjyb.cn/Article/details/gtxurdygeb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gtxwlqrlem.html

[U98] JS：fetch 带 JSON
来源：http://dali.jinqigfzy.top/Article/details/gttjksdvlv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.vqdsnc.cn/Article/details/gtloxoaxzm.html

[U99] JS：事件监听
来源：http://dali.c1oappe.top/Article/details/gtjvxmcllt.html

el.addEventListener("click", e => {})
来源：http://dali.jinqigufen.top/Article/details/gtxwstxoqq.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gtvifthsjl.html

document.querySelector(".item")
来源：http://dali.hywenlv.cn/Article/details/gtnnhwcnne.html

[U101] JS：classList 操作
来源：http://dali.yangfankeji.com/Article/details/gtstqxgnld.html

el.classList.toggle("active")
来源：http://dali.quarkkingdee.top/Article/details/gtqfseujln.html

[U102] JS：本地存储
来源：http://dali.pengpengdd.cyou/Article/details/gtzbaseiiu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.fzhhl.top/Article/details/gtibpumbag.html

[U103] JS：定时器
来源：http://dali.c1oappe.top/Article/details/gtsbjotbqn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yuxming.cn/Article/details/gtmxprxwuo.html

[U104] JS：防抖
来源：http://dali.shuidangran.top/Article/details/gtmmbgjocd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gtjtzfvowu.html

[U105] JS：节流
来源：http://dali.sufxvd.cn/Article/details/gtnvvggfhk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gtdzrxwldg.html

[U106] JS：日期格式化
来源：http://dali.zhengqikj.top/Article/details/gtepqinvbf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cqqwz.cn/Article/details/gtpqcfbiww.html

[U107] JS：数字千分位
来源：http://dali.birdmap.top/Article/details/gtfcqzkrxw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gturvyqoge.html

[U108] JS：随机整数
来源：http://dali.jinqigfzy.top/Article/details/gtkgzwsvgo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlugmzmdl.html

[U109] JS：数组分组
来源：http://dali.fzhhl.top/Article/details/gtreydrqkh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhiwuduotai.top/Article/details/gtwcqwmkqt.html

[U110] JS：数组分块
来源：http://dali.316326.xyz/Article/details/gtivitmxvu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.aibaodan.cn/Article/details/gtucrfzwuu.html

[U111] JS：对象转 Map
来源：http://dali.vqdsnc.cn/Article/details/gtnorachlu.html

new Map(Object.entries(obj))
来源：http://dali.haohaochexian.top/Article/details/gtqkffrkmc.html

[U112] JS：字符串补位
来源：http://dali.chenzaomai.com/Article/details/gtaebrbwil.html

"7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtwwnjnxdu.html

[U113] JS：正则替换全部
来源：http://dali.zhiwuduotai.top/Article/details/gtluwsxwfj.html

s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtcldavjnp.html

[U114] JS：JSON 深比较
来源：http://dali.feifeiyinyue.top/Article/details/gtrjwvecfk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fengsongda.top/Article/details/gttytuzigd.html

[U115] JS：生成 UUID
来源：http://dali.hfpthk.cn/Article/details/gtrdjsiolp.html

crypto.randomUUID()
来源：http://dali.jinqigfzy.top/Article/details/gttzagbnvj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbjhgull.html

/** @param {string} name */ function f(name) {}
来源：http://dali.sxryk.cn/Article/details/gtgaburxfk.html

[U117] JS：单元测试
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbbobpkcr.html

npm i -D vitest;  npx vitest
来源：http://dali.sufxvd.cn/Article/details/gtstuvxlnq.html

[U118] JS：开发服务器
来源：http://dali.yangfankeji.com/Article/details/gtxbrqjtou.html

npm i -D vite;  npx vite
来源：http://dali.ppjwa.cn/Article/details/gtibaqrzrs.html

[U119] JS：生产构建
来源：http://dali.yanxiufei.cn/Article/details/gtjvzkxwhq.html

npx vite build
来源：http://dali.dashuyun.cn/Article/details/gtbrbirime.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.fengsongda.top/Article/details/gttisgetbz.html

import.meta.env.VITE_API_URL
来源：http://dali.cheryme.top/Article/details/gtgtdqqfoc.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtgzfnclnl.html

统计汇总
来源：http://dali.smart0.xyz/Article/details/gtkzjgtpfz.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtfagsqnna.html

按语言统计（条）：
来源：http://dali.feifeiyinyue.top/Article/details/gtwwgwqyiv.html

Python ......... 252
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwirhuutn.html

PHP ............ 252
来源：http://dali.dianchejie.cn/Article/details/gtyvoamwzg.html

JavaScript ..... 252
来源：http://dali.hnxiangtu.top/Article/details/gttdrvzixy.html

TypeScript ..... 212
来源：http://dali.jinqigfzy.top/Article/details/gtwaebawiw.html

Java ........... 212
来源：http://dali.nanxinkj.top/Article/details/gtgruppwmg.html

Go ............. 212
来源：http://dali.hnxiangtu.top/Article/details/gtmpzvzzjf.html

Ruby ........... 212
来源：http://dali.fzhhl.top/Article/details/gtsfohkadm.html

C# ............. 212
来源：http://dali.wangdashe.top/Article/details/gtzjlhwoeh.html

C .............. 30
来源：http://dali.haohaochexian.top/Article/details/gtttidhtkf.html

C++ ............ 30
来源：http://dali.yanxiufei.cn/Article/details/gtgtnybxsk.html

SQL ............ 90
来源：http://dali.dashuyun.cn/Article/details/gtrrqehkki.html

Bash ........... 80
来源：http://dali.316326.xyz/Article/details/gtbuydptdt.html

Kotlin ......... 15
来源：http://dali.andypj.xyz/Article/details/gtuydpeytf.html

Swift .......... 15
来源：http://dali.jlsjyb.cn/Article/details/gtnzmbyxnk.html

Lua ............ 10
来源：http://dali.hysaishi.cn/Article/details/gtfyepwldf.html

Perl ........... 10
来源：http://dali.xylfe.cn/Article/details/gtezlvggic.html

Scala .......... 10
来源：http://dali.ybcxt.top/Article/details/gteyjaswqs.html

------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gtvbmdwbab.html

合计 ........... 2106 条
来源：http://dali.havefunace.top/Article/details/gtpnekoqfh.html

按章节统计：
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsriikch.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.wangdashe.top/Article/details/gtagucdodw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ybcxt.top/Article/details/gtnatsnavl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gtigvhkovd.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yj202588.top/Article/details/gtijkvxhnd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yj20258.top/Article/details/gtszkytjnm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xuetiantiany.cn/Article/details/gtsmuuesep.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gtbxiaxpdg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.chenjidiqi.icu/Article/details/gttsigaryp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gthlguguxe.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.andypj.xyz/Article/details/gttkwqfqgb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gtytbgnddj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gtucthprhp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gtoklgvpwp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yueranfly.top/Article/details/gtgjflsjmf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hongshengwenyu.top/Article/details/gtlluymrtr.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gtqccawxfw.html

Q SQL 专题                              90
来源：http://dali.xuanzx.com/Article/details/gtinfvqhov.html

R Bash 专题                             80
来源：http://dali.xuetiantiany.cn/Article/details/gtcqpyfqww.html

S C / C++ 专题                          60
来源：http://dali.cashguo.top/Article/details/gtpknfwpmx.html

T 其他语言补充                          60
来源：http://dali.ydzc1.top/Article/details/gtbqelkukk.html

U 高频实用片段                         120
来源：http://dali.jianghu66.top/Article/details/gtegswuegk.html

------------------------------------
来源：http://dali.yuxming.cn/Article/details/gtmwlltjhw.html

合计                                  2106 条
来源：http://dali.nanxuanxn.top/Article/details/gtagwzlhnd.html

--------------------------------------------------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtyihzclkv.html

使用提醒
来源：http://dali.quarkkingdee.top/Article/details/gtnltsgvfr.html

--------------------------------------------------------------------------------
来源：http://dali.guannengcc.top/Article/details/gtlglkphcj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.gogol.net.cn/Article/details/gtbzpghhud.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.nwbrower.top/Article/details/gtmxymgyax.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.cucudq.cn/Article/details/gthtjhtekx.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.pycfn.com/Article/details/gtbncvmhgr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cashguo.top/Article/details/gtzcatmmhf.html

—— 文件结束 ——
来源：http://dali.pengpengdd.cyou/Article/details/gtnkhkgxuj.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtubnkaehz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cashguo.top/Article/details/gtyyvjzlox.html

Common Programming Examples Cheat Book
来源：http://dali.guowangkeji.top/Article/details/gtyflovsng.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtalqocigt.html

【收录内容】
来源：http://dali.9152youxi.cn/Article/details/gthyakhfhb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xinyue.icu/Article/details/gtimytokly.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.quarkkingdee.top/Article/details/gtothzwbyx.html

SQL · Bash · C · C++
来源：http://dali.xuetiantiany.cn/Article/details/gtsnxlakyp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hnqzz.top/Article/details/gtrhgtskvq.html

【使用说明】
来源：http://dali.feifeiyinyue.top/Article/details/gtigwmakga.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shzxlz.cn/Article/details/gtqkbaworc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xziqi.cn/Article/details/gtisqhezmf.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yj20258888.top/Article/details/gtckcpxciv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ybcxt.top/Article/details/gttgdufmyz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.vqdsnc.cn/Article/details/gtwezhbzhp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cheryme.top/Article/details/gtgyyjsbdd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jiagoushi.top/Article/details/gtmimkmihu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.smart0.xyz/Article/details/gttrvarltf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.dashuyun.cn/Article/details/gtmcozurly.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xuetiantiany.cn/Article/details/gtvxxfymbx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.guowangkeji.top/Article/details/gtsdzmuwvi.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jiagoushi.top/Article/details/gtxfieonmp.html

【文件统计】
来源：http://dali.daria6918.cn/Article/details/gtsceegnez.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gtddmgxlxh.html

--------------------------------------------------------------------------------
来源：http://dali.bjfxy.top/Article/details/gtgxtovsbt.html

目  录
来源：http://dali.cashguo.top/Article/details/gtdajedmxt.html

--------------------------------------------------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gtatcmfugh.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xylfe.cn/Article/details/gtphxdtltj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hysaishi.cn/Article/details/gtnamgbtrt.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yueranfly.top/Article/details/gtvmbsgyrs.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.redwolf501.top/Article/details/gtxszhkphv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xuanzx.com/Article/details/gtzkbeczfu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.snrcjt.cn/Article/details/gtttiperfb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hnxiangtu.top/Article/details/gtovgfrtvg.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.gzhubu.top/Article/details/gtixjxxpqu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.dashuyun.cn/Article/details/gtfdufbsbw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xuanzx.com/Article/details/gtouywcixn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shzxlz.cn/Article/details/gtqsmgbrqo.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtjcvbopoo.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtgrmghkcv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.redwolf501.top/Article/details/gtqfdqgqvi.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.tian-w.cn/Article/details/gtjulraozk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gttrbbysjn.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhongyouzk.top/Article/details/gtewdfklyi.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.dianchejie.cn/Article/details/gtcbuumgjs.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkjyampn.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.vqdsnc.cn/Article/details/gtzoiawqgr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.shzxlz.cn/Article/details/gtsnxtcams.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtucmfdgbw.html

A. 基础语法与类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpuadpzz.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtowonkunb.html

[A01] Hello World
来源：http://dali.dianchejie.cn/Article/details/gtfspadwgs.html

Py:   print("Hello, World!")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmluddmk.html

PHP:  echo "Hello, World!";
来源：http://dali.sufxvd.cn/Article/details/gtenkdvkeh.html

JS:   console.log("Hello, World!");
来源：http://dali.jinqigfzy.top/Article/details/gtupavhzcb.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.shzxlz.cn/Article/details/gtyiaahyzw.html

Java: System.out.println("Hello, World!");
来源：http://dali.gaohongyu789.top/Article/details/gtshzqshor.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jyoumei.cn/Article/details/gtckspneib.html

Ruby: puts "Hello, World!"
来源：http://dali.gzhubu.top/Article/details/gthczikxbg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ppjwa.cn/Article/details/gtyccljhyd.html

[A02] 变量声明与赋值
来源：http://dali.chenlongwang.top/Article/details/gtrstkyriw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhengqikj.top/Article/details/gtjowrezde.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.meibo888.top/Article/details/gtbarybvzy.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.gaohongyu789.top/Article/details/gtnieitsgw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cashguo.top/Article/details/gtwvzxpkpi.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.snrcjt.cn/Article/details/gtphljalmk.html

Go:   name := "Alex"; age := 20
来源：http://dali.jlsjyb.cn/Article/details/gtyktomwyy.html

Ruby: name = "Alex"; age = 20
来源：http://dali.chenlongwang.top/Article/details/gtiqroxjms.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynwtwmji.html

[A03] 常量定义
来源：http://dali.ppjwa.cn/Article/details/gtkhwqruea.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.daxiang520.top/Article/details/gtwcyotkzp.html

PHP:  const PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtifezabzf.html

JS:   const PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtpicxphci.html

TS:   const PI: number = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gtipyeykzj.html

Java: static final double PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtatdhlaun.html

Go:   const PI = 3.14159
来源：http://dali.meibo888.top/Article/details/gtehoqomwa.html

Ruby: PI = 3.14159
来源：http://dali.xinyue.icu/Article/details/gtfjzvctxr.html

C#:   const double PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtqrlpgijo.html

[A04] 判断变量类型
来源：http://dali.9152youxi.cn/Article/details/gttrrprudb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ydzc1.top/Article/details/gtohzonfuk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hongshengwenyu.top/Article/details/gtaxwpmjvr.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.nwbrower.top/Article/details/gtggagrwlh.html

TS:   typeof x; x instanceof Date
来源：http://dali.yuxming.cn/Article/details/gtbruhglud.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.guowangkeji.top/Article/details/gtruwsdtiy.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.nanxuanxn.top/Article/details/gtmvqlwjob.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxoqfdwv.html

C#:   x.GetType().Name; x is int
来源：http://dali.kuanghao11.cn/Article/details/gtbknbhoaq.html

[A05] 整数除法与取模
来源：http://dali.jqgufenzy.top/Article/details/gtwuhrrmmy.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yueranfly.top/Article/details/gtcfincjhf.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.cucudq.cn/Article/details/gtwerstkah.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ybcxt.top/Article/details/gtroajbcbc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.redwolf501.top/Article/details/gttjybzoek.html

Java: 7 / 2; 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gtkwvwgzuo.html

Go:   7 / 2; 7 % 2
来源：http://dali.yvedp.cn/Article/details/gtckglbpad.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gthkgtanjv.html

C#:   7 / 2; 7 % 2
来源：http://dali.xziqi.cn/Article/details/gtewubzgbg.html

[A06] 字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gtbpitnbdn.html

Py:   int("42"); float("3.14")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrtsaojw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gtretwxgtb.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ydzc1.top/Article/details/gtiuqpqmxq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.shuidangran.top/Article/details/gtiihpfhcr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.tanke756.top/Article/details/gtppgmgsma.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shangyingyoupin.top/Article/details/gtynxbidxq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.xylfe.cn/Article/details/gtchgewyjd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.cqqwz.cn/Article/details/gtucxynaeu.html

[A07] 数字转字符串
来源：http://dali.jqgfzy.top/Article/details/gtfsfteetu.html

Py:   str(42)
来源：http://dali.zycfv.cn/Article/details/gtnwxlokhr.html

PHP:  (string) 42; strval(42)
来源：http://dali.hysaishi.cn/Article/details/gtajlsjerv.html

JS:   String(42); (42).toString()
来源：http://dali.quarkkingdee.top/Article/details/gtxactavqw.html

TS:   String(42)
来源：http://dali.hfpthk.cn/Article/details/gtxrmvnkfo.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yvedp.cn/Article/details/gtvpyzejwu.html

Go:   strconv.Itoa(42)
来源：http://dali.yonumen.top/Article/details/gtjrrogqgh.html

Ruby: 42.to_s
来源：http://dali.ydzc1.top/Article/details/gtpzoqodki.html

C#:   42.ToString()
来源：http://dali.jyoumei.cn/Article/details/gtgeyvfrfs.html

[A08] 取整与四舍五入
来源：http://dali.hnxiangtu.top/Article/details/gtjoglrhsm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yj20258.top/Article/details/gtrarxatow.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhengqikj.top/Article/details/gthlnwyhyg.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.ivvv.top/Article/details/gtrpmfyrgt.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.wangdashe.top/Article/details/gtpubceaja.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhoulong.xyz/Article/details/gtnawlpzdb.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.hywenlv.cn/Article/details/gtgistkfip.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.daxiang520.top/Article/details/gturrftlaq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.kuanghao11.cn/Article/details/gtmrnjvfko.html

[A09] 绝对值与最大最小值
来源：http://dali.nanxinkj.top/Article/details/gtixygibbe.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zycfv.cn/Article/details/gtcfogjwdx.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gtmhfocaiq.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gtwhydjqqz.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtcmtzxjzw.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gtrfthxhtn.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.cqqwz.cn/Article/details/gtsuqfgpji.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zycfv.cn/Article/details/gtlrztvikg.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gtcejxqaqg.html

[A10] 生成随机数
来源：http://dali.guannengcc.top/Article/details/gtijknijkr.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jqgufenzy.top/Article/details/gtwiebvrky.html

PHP:  random_int(1, 100);
来源：http://dali.hysaishi.cn/Article/details/gtqciscmlz.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gteaupcicr.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cashguo.top/Article/details/gtbcnptisz.html

Java: new Random().nextInt(100) + 1
来源：http://dali.wangdashe.top/Article/details/gtoumemykl.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.wangdashe.top/Article/details/gtwkbbymjg.html

Ruby: rand(1..100)
来源：http://dali.cucudq.cn/Article/details/gtnkklfejb.html

C#:   new Random().Next(1, 101)
来源：http://dali.cqqwz.cn/Article/details/gtvinkounr.html

[A11] 条件表达式（三元）
来源：http://dali.tanke756.top/Article/details/gtcjpgzdnh.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqfvkurnr.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hammf.cn/Article/details/gtegkonxxw.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhengqikj.top/Article/details/gtfcwxxvhb.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezpwwqzx.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.cucudq.cn/Article/details/gtjrqlrclh.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.0kj1m.cn/Article/details/gtxlphfvat.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhongyouzk.top/Article/details/gttsdxpbml.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.hfpthk.cn/Article/details/gthlenihkt.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhoulong.xyz/Article/details/gtpjevrflk.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yj202588.top/Article/details/gtvedrcwhx.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.hammf.cn/Article/details/gtorpayqhn.html

JS:   `Hello, ${name}!`
来源：http://dali.316326.xyz/Article/details/gtoidnslvi.html

TS:   `Hello, ${name}!`
来源：http://dali.tanke756.top/Article/details/gtuvldxprg.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.sufxvd.cn/Article/details/gtydedmvaz.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.daxiang520.top/Article/details/gtuejotivq.html

Ruby: "Hello, #{name}!"
来源：http://dali.cdnleiting.top/Article/details/gtnfyiiynf.html

C#:   $"Hello, {name}!"
来源：http://dali.havefunace.top/Article/details/gtmgltudnp.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.shanyushiyangtech.top/Article/details/gtbinxxvbm.html

Py:   "第一行\n第二行"
来源：http://dali.pengpengdd.cyou/Article/details/gtxuifkntd.html

PHP:  "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gthkziynsq.html

JS:   "第一行\n第二行"
来源：http://dali.xuanzx.com/Article/details/gtkhtrltgz.html

TS:   "第一行\n第二行"
来源：http://dali.jqgfzy.top/Article/details/gtsbuwglkv.html

Java: "第一行\n第二行"
来源：http://dali.tianlin.xyz/Article/details/gtlehpmucr.html

Go:   "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gtvbvprffv.html

Ruby: "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gtxlzvnnop.html

C#:   "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gtpuyvmukl.html

[A14] 注释写法
来源：http://dali.zhiwuduotai.top/Article/details/gtxcystelq.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.gzhubu.top/Article/details/gtvgzlkrlz.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.nanxinkj.top/Article/details/gthjqjvdci.html

JS:   // 单行；/* 多行 */
来源：http://dali.hnxiangtu.top/Article/details/gtnsuidnik.html

TS:   // 单行；/* 多行 */
来源：http://dali.yj20258.top/Article/details/gtsmcgbgir.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.nanxuanxn.top/Article/details/gtkddubmtg.html

Go:   // 单行；/* 多行 */
来源：http://dali.316326.xyz/Article/details/gtmvedzbfb.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfvmkwhx.html


<!-- 参考信息 -->