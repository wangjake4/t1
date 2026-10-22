代发 wailian999

[U85] JS：可选链
来源：http://dali.xuanzx.com/Article/details/gthzxitydi.html

a?.b?.c
来源：http://dali.yangfankeji.com/Article/details/gtrtjsysjm.html

[U86] JS：空值合并
来源：http://dali.dianchejie.cn/Article/details/gtchnvjeow.html

a ?? b
来源：http://dali.gotoacloud.top/Article/details/gtidqwkfye.html

[U87] JS：解构默认值
来源：http://dali.ehwqpu.com/Article/details/gtjvkbrnpy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.aizwys.cn/Article/details/gtsolprnyc.html

[U88] JS：对象展开合并
来源：http://dali.ppjwa.cn/Article/details/gthvabhscy.html

{ ...a, ...b }
来源：http://dali.birdmap.top/Article/details/gtbkuzzulj.html

[U89] JS：数组去重
来源：http://dali.ybcxt.top/Article/details/gtaeluiyhb.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gtzttmqlzu.html

[U90] JS：数字数组排序
来源：http://dali.wangshuangyany.cn/Article/details/gtuikumbdj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gtdemorraq.html

[U91] JS：对象键值遍历
来源：http://dali.yuanzhike.top/Article/details/gtpmqolumu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.vqdsnc.cn/Article/details/gtyiisuopt.html

[U92] JS：深拷贝
来源：http://dali.havefunace.top/Article/details/gtjjmnfibs.html

structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjwsvdce.html

[U93] JS：模板字符串
来源：http://dali.yongpay.top/Article/details/gthzkffcsn.html

`共 ${n} 条`
来源：http://dali.jyoumei.cn/Article/details/gtkghvozkt.html

[U94] JS：箭头函数
来源：http://dali.yangfankeji.com/Article/details/gtaqrkyhcq.html

const double = x => x * 2;
来源：http://dali.gogol.net.cn/Article/details/gtiirlgvsi.html

[U95] JS：Promise 包装
来源：http://dali.cucudq.cn/Article/details/gtpbjfubtc.html

new Promise((resolve, reject) => {})
来源：http://dali.zhongyouzk.top/Article/details/gtsbsyxgld.html

[U96] JS：async/await 与异常
来源：http://dali.hfpthk.cn/Article/details/gtwvanvxoj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gthaggufcl.html

[U97] JS：并发请求
来源：http://dali.ybcxt.top/Article/details/gtmtqwonwm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gtyjwzkeer.html

[U98] JS：fetch 带 JSON
来源：http://dali.dianchejie.cn/Article/details/gtkkfcsnaz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.sxryk.cn/Article/details/gtgnfyhism.html

[U99] JS：事件监听
来源：http://dali.cashguo.top/Article/details/gtdoohgopb.html

el.addEventListener("click", e => {})
来源：http://dali.yongpay.top/Article/details/gtaajffbfp.html

[U100] JS：DOM 查询
来源：http://dali.havefunace.top/Article/details/gttiznvela.html

document.querySelector(".item")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlyvtxhkf.html

[U101] JS：classList 操作
来源：http://dali.daxiang520.top/Article/details/gtqrgjyltq.html

el.classList.toggle("active")
来源：http://dali.hnxiangtu.top/Article/details/gtnpuyymsd.html

[U102] JS：本地存储
来源：http://dali.pycfn.com/Article/details/gtvbydovcl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sweek.top/Article/details/gtabbdnruy.html

[U103] JS：定时器
来源：http://dali.ydzc1.top/Article/details/gtlfcfdptz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xuanzx.com/Article/details/gthntkkbdc.html

[U104] JS：防抖
来源：http://dali.xinyue.icu/Article/details/gtjtwgypdr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gtlrxylvrv.html

[U105] JS：节流
来源：http://dali.hongshengwenyu.top/Article/details/gtkwjzztpi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.aizwys.cn/Article/details/gtnjipydvc.html

[U106] JS：日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gtvypbqngh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.dashuyun.cn/Article/details/gtfeurzngy.html

[U107] JS：数字千分位
来源：http://dali.havefunace.top/Article/details/gtlfonimbw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.snrcjt.cn/Article/details/gttpqxkxeq.html

[U108] JS：随机整数
来源：http://dali.hywenlv.cn/Article/details/gtorbdingz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.fengsongda.top/Article/details/gtjbmzdbzy.html

[U109] JS：数组分组
来源：http://dali.nwbrower.top/Article/details/gtmzvhjiuf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jqgfzy.top/Article/details/gtozlrmaka.html

[U110] JS：数组分块
来源：http://dali.dashuyun.cn/Article/details/gtwjamxkkv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jiagoushi.top/Article/details/gtvgndszrb.html

[U111] JS：对象转 Map
来源：http://dali.nwbrower.top/Article/details/gtvihqoins.html

new Map(Object.entries(obj))
来源：http://dali.daxiang520.top/Article/details/gtuttcflls.html

[U112] JS：字符串补位
来源：http://dali.c1oappe.top/Article/details/gtoeepmcxo.html

"7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gtgwuwzbpl.html

[U113] JS：正则替换全部
来源：http://dali.9152youxi.cn/Article/details/gtykaohxdy.html

s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gtnmwvyhyr.html

[U114] JS：JSON 深比较
来源：http://dali.nwbrower.top/Article/details/gtsqbvitto.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgfzy.top/Article/details/gtgmjypdrl.html

[U115] JS：生成 UUID
来源：http://dali.ppjwa.cn/Article/details/gthwbbynhe.html

crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gtrhvyxxip.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gaohongyu789.top/Article/details/gtdhonxgqp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.dianchejie.cn/Article/details/gtvsptheyh.html

[U117] JS：单元测试
来源：http://dali.hongshengwenyu.top/Article/details/gtuvlmdvum.html

npm i -D vitest;  npx vitest
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdsfdeeiu.html

[U118] JS：开发服务器
来源：http://dali.jyoumei.cn/Article/details/gtlnpgmnbj.html

npm i -D vite;  npx vite
来源：http://dali.zhoulong.xyz/Article/details/gtdsrcnngo.html

[U119] JS：生产构建
来源：http://dali.redwolf501.top/Article/details/gtnrzigxbj.html

npx vite build
来源：http://dali.jqgfzy.top/Article/details/gtnixckpvz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xuetiantiany.cn/Article/details/gttjsnpduj.html

import.meta.env.VITE_API_URL
来源：http://dali.gaohongyu789.top/Article/details/gtrjftauub.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtowsbxolm.html

统计汇总
来源：http://dali.nanxuanxn.top/Article/details/gtvkwekwqy.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtddvwywxw.html

按语言统计（条）：
来源：http://dali.nanxinkj.top/Article/details/gtfmfqjxyn.html

Python ......... 252
来源：http://dali.jinqigufen.top/Article/details/gtaisnbnmg.html

PHP ............ 252
来源：http://dali.zhongyouzk.top/Article/details/gtdfaympdh.html

JavaScript ..... 252
来源：http://dali.ivvv.top/Article/details/gtriauhewi.html

TypeScript ..... 212
来源：http://dali.nanxinkj.top/Article/details/gtvqedcwls.html

Java ........... 212
来源：http://dali.zhiwuduotai.top/Article/details/gtkfctokpx.html

Go ............. 212
来源：http://dali.ybcxt.top/Article/details/gthewvjakz.html

Ruby ........... 212
来源：http://dali.yongpay.top/Article/details/gtgicavuia.html

C# ............. 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgercppwi.html

C .............. 30
来源：http://dali.jinqigufen.top/Article/details/gtirbeizof.html

C++ ............ 30
来源：http://dali.tian-w.cn/Article/details/gtzbicxycl.html

SQL ............ 90
来源：http://dali.birdmap.top/Article/details/gttocochyp.html

Bash ........... 80
来源：http://dali.gotoacloud.top/Article/details/gtqbrcdzgr.html

Kotlin ......... 15
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxcykzrg.html

Swift .......... 15
来源：http://dali.feifeiyinyue.top/Article/details/gtzgapsspz.html

Lua ............ 10
来源：http://dali.sxryk.cn/Article/details/gtsbreuwxh.html

Perl ........... 10
来源：http://dali.fengsongda.top/Article/details/gtspvrlxbi.html

Scala .......... 10
来源：http://dali.nwbrower.top/Article/details/gtgxehomhk.html

------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gtisvnbpxg.html

合计 ........... 2106 条
来源：http://dali.yangfankeji.com/Article/details/gtaporsufk.html

按章节统计：
来源：http://dali.yonumen.top/Article/details/gtinklnujb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cashguo.top/Article/details/gtowkgdxvt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gaohongyu789.top/Article/details/gtwclujrus.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jyoumei.cn/Article/details/gtznlumfne.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sweek.top/Article/details/gtqphstrhq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yueranfly.top/Article/details/gtqffmltrf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.0kj1m.cn/Article/details/gtyvagzmvm.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gogol.net.cn/Article/details/gtwocivcza.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxycoitox.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gtimsxwyhe.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.iojbl.cn/Article/details/gtcstlbekw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gtsfoyqfwn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gtfaqqbpzx.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gthbavxuld.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yuxming.cn/Article/details/gtdorijfrs.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.smart0.xyz/Article/details/gtkwshinyg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gtepxjyhrq.html

Q SQL 专题                              90
来源：http://dali.cqqwz.cn/Article/details/gthyqwyhti.html

R Bash 专题                             80
来源：http://dali.nanxinkj.top/Article/details/gtjbjinreo.html

S C / C++ 专题                          60
来源：http://dali.gzhubu.top/Article/details/gtvozednto.html

T 其他语言补充                          60
来源：http://dali.vqdsnc.cn/Article/details/gtixnerdnk.html

U 高频实用片段                         120
来源：http://dali.tianlin.xyz/Article/details/gtgljkpsos.html

------------------------------------
来源：http://dali.yvedp.cn/Article/details/gtimquyfam.html

合计                                  2106 条
来源：http://dali.yvedp.cn/Article/details/gttbolgosh.html

--------------------------------------------------------------------------------
来源：http://dali.hammf.cn/Article/details/gturjijlpw.html

使用提醒
来源：http://dali.jqgufenzy.top/Article/details/gtgietdnjn.html

--------------------------------------------------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gtfptswfnz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.9152youxi.cn/Article/details/gtvskixgwz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gtumqugdnq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.gaohongyu789.top/Article/details/gtsvfacnej.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.tanke756.top/Article/details/gtoenzpggs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hnqzz.top/Article/details/gtvbtglwhy.html

—— 文件结束 ——
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgsvpukb.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtqyrzxgml.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.dianchejie.cn/Article/details/gtvlxuuiqh.html

Common Programming Examples Cheat Book
来源：http://dali.gzhubu.top/Article/details/gtcuorwtkp.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtrzxoiwfp.html

【收录内容】
来源：http://dali.jqgufenzy.top/Article/details/gthxqelpew.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.birdmap.top/Article/details/gtvrmpdguf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.snrcjt.cn/Article/details/gtihdjxhps.html

SQL · Bash · C · C++
来源：http://dali.bjfxy.top/Article/details/gtrpglapao.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yangfankeji.com/Article/details/gturyinkhi.html

【使用说明】
来源：http://dali.yongpay.top/Article/details/gtismjtrvy.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.chenlongwang.top/Article/details/gtmfovbifj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yj20258.top/Article/details/gtxywhqjhb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqnzubqb.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.andypj.xyz/Article/details/gttcyrejmv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yuanzhike.top/Article/details/gtkolrqsue.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.tanke756.top/Article/details/gtamezxdyd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yj20258.top/Article/details/gtmpdmkiud.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.wangshuangyany.cn/Article/details/gtxauabojx.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hfpthk.cn/Article/details/gtvbokbnkw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.aizwys.cn/Article/details/gtfyeuxzfv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.0kj1m.cn/Article/details/gtbbosbhtl.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.sxryk.cn/Article/details/gtxkuwpftm.html

【文件统计】
来源：http://dali.iojbl.cn/Article/details/gthlbjhdeq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.sweek.top/Article/details/gtukuhjggs.html

--------------------------------------------------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gtvugsbyph.html

目  录
来源：http://dali.yanxiufei.cn/Article/details/gtdhbffisz.html

--------------------------------------------------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gtndvfljaj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jiagoushi.top/Article/details/gtgouoyqlz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.cdnleiting.top/Article/details/gtnvinmhsj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.9152youxi.cn/Article/details/gtdmoprhnp.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xziqi.cn/Article/details/gtsrkygdwr.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.0kj1m.cn/Article/details/gtcatydenh.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.cheryme.top/Article/details/gtiaxtvnor.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hywenlv.cn/Article/details/gtpiawwkjj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jyoumei.cn/Article/details/gtolkmbzcs.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gtoofeichc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.0kj1m.cn/Article/details/gtsgjkodux.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.0kj1m.cn/Article/details/gttwghibus.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gtgvtrnhih.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.daria6918.cn/Article/details/gtoeyktxwp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.iojbl.cn/Article/details/gtjxmjnlyr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.chenzaomai.com/Article/details/gtlqswuroz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jyoumei.cn/Article/details/gtopzfkvtj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yvedp.cn/Article/details/gtmohlhesa.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ppjwa.cn/Article/details/gtpwovqggh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xziqi.cn/Article/details/gtorepidfn.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yueranfly.top/Article/details/gtufxskavr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.nanxuanxn.top/Article/details/gthhcpfvra.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtptgmevrk.html

A. 基础语法与类型
来源：http://dali.fzhhl.top/Article/details/gtlferrviv.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtbvhplxqi.html

[A01] Hello World
来源：http://dali.ppjwa.cn/Article/details/gtyntntivf.html

Py:   print("Hello, World!")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvwqedxbe.html

PHP:  echo "Hello, World!";
来源：http://dali.vqdsnc.cn/Article/details/gtvaxpchfo.html

JS:   console.log("Hello, World!");
来源：http://dali.fzhhl.top/Article/details/gtvawlsyfs.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.haohaochexian.top/Article/details/gtbnbcrqie.html

Java: System.out.println("Hello, World!");
来源：http://dali.jqgfzy.top/Article/details/gtpfalxrsy.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xinyue.icu/Article/details/gtdencguwl.html

Ruby: puts "Hello, World!"
来源：http://dali.daxiang520.top/Article/details/gtqphodfls.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xinyue.icu/Article/details/gtahcmxxhw.html

[A02] 变量声明与赋值
来源：http://dali.hfpthk.cn/Article/details/gtgpkpedim.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.meibo888.top/Article/details/gtzvwizvti.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.gaohongyu789.top/Article/details/gtyhzaxhkb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.bjfxy.top/Article/details/gtbebkiloy.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cdnleiting.top/Article/details/gtwqhpiqct.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhongyouzk.top/Article/details/gtgfvmosjt.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzitvjvgp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.haohaochexian.top/Article/details/gtxkbmbtwe.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqsbnlwc.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gtlizmhtfh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.tian-w.cn/Article/details/gtibkwjooz.html

PHP:  const PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtqqndpgmh.html

JS:   const PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtmylrluho.html

TS:   const PI: number = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtqundjjbm.html

Java: static final double PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtfbvnbhlh.html

Go:   const PI = 3.14159
来源：http://dali.nwbrower.top/Article/details/gtftphimzd.html

Ruby: PI = 3.14159
来源：http://dali.9152youxi.cn/Article/details/gtqmcpmval.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gthkkkvcga.html

[A04] 判断变量类型
来源：http://dali.jlsjyb.cn/Article/details/gtmzvhjaaq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.havefunace.top/Article/details/gtoyusheij.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.sxryk.cn/Article/details/gtlcysegkg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.daxiang520.top/Article/details/gtsrnzllax.html

TS:   typeof x; x instanceof Date
来源：http://dali.fengsongda.top/Article/details/gtybhrscyp.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xuanzx.com/Article/details/gtdwoelruw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.smart0.xyz/Article/details/gtuwnxxvbc.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ivvv.top/Article/details/gtibnnvnzl.html

C#:   x.GetType().Name; x is int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtascounea.html

[A05] 整数除法与取模
来源：http://dali.ybcxt.top/Article/details/gtnfuwfllb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.ivvv.top/Article/details/gtxiwbqtzg.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yuxming.cn/Article/details/gtruoorxjv.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gtmhoshjfz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cashguo.top/Article/details/gtysruoxnw.html

Java: 7 / 2; 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqaxxmvx.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzyicwcqs.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gtspatpypz.html

C#:   7 / 2; 7 % 2
来源：http://dali.nanxuanxn.top/Article/details/gtvvoxrcgh.html

[A06] 字符串转数字
来源：http://dali.yonumen.top/Article/details/gtkzptbbln.html

Py:   int("42"); float("3.14")
来源：http://dali.gotoacloud.top/Article/details/gtjkihcefk.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.haohaochexian.top/Article/details/gtxkxtshgv.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.gzhubu.top/Article/details/gtwivtdqps.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.sufxvd.cn/Article/details/gtomdchymd.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jinqigfzy.top/Article/details/gttjwbiitt.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.cdnleiting.top/Article/details/gtngxvhamb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.chenlongwang.top/Article/details/gtdqhdivba.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.wangshuangyany.cn/Article/details/gtajhzttxc.html

[A07] 数字转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtanbljgkd.html

Py:   str(42)
来源：http://dali.zhoulong.xyz/Article/details/gttcfxqaxe.html

PHP:  (string) 42; strval(42)
来源：http://dali.ydzc1.top/Article/details/gtfqirckqa.html

JS:   String(42); (42).toString()
来源：http://dali.haohaochexian.top/Article/details/gtbqbixpxx.html

TS:   String(42)
来源：http://dali.tanke756.top/Article/details/gtfzazheaq.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.aibaodan.cn/Article/details/gtlyikdgnu.html

Go:   strconv.Itoa(42)
来源：http://dali.tianlin.xyz/Article/details/gtjhijuttl.html

Ruby: 42.to_s
来源：http://dali.wangshuangyany.cn/Article/details/gtbnbuelum.html

C#:   42.ToString()
来源：http://dali.hnqzz.top/Article/details/gtrsvjbwbs.html

[A08] 取整与四舍五入
来源：http://dali.cucudq.cn/Article/details/gtzcuuwcre.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.tanke756.top/Article/details/gtywbpztrp.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yueranfly.top/Article/details/gtgsblexvf.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhoulong.xyz/Article/details/gtjdjychyl.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hnxiangtu.top/Article/details/gtajjttoev.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.nanxuanxn.top/Article/details/gtxtjnbifv.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.gzhubu.top/Article/details/gtxfufgauq.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jinqigfzy.top/Article/details/gtjwaartzd.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hysaishi.cn/Article/details/gtqeszjlkz.html

[A09] 绝对值与最大最小值
来源：http://dali.wangdashe.top/Article/details/gtpoooxdej.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtmexfomup.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jianghu66.top/Article/details/gtircblthc.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gtoqwgbzwq.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.sweek.top/Article/details/gthnzyluon.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.havefunace.top/Article/details/gtzphjfxwr.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.iojbl.cn/Article/details/gtzasakmtz.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.wangdashe.top/Article/details/gtbpfaagrp.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtzxqcmixx.html

[A10] 生成随机数
来源：http://dali.yuanzhike.top/Article/details/gtyrwkcmmq.html

Py:   import random; random.randint(1, 100)
来源：http://dali.cheryme.top/Article/details/gtrmdhfazs.html

PHP:  random_int(1, 100);
来源：http://dali.xuetiantiany.cn/Article/details/gtrcnfnjmj.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.svipenyu.cn/Article/details/gttoyepzxt.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hywenlv.cn/Article/details/gtuzltxurr.html

Java: new Random().nextInt(100) + 1
来源：http://dali.xuanzx.com/Article/details/gtweifiued.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jinqigfzy.top/Article/details/gtjewzgbtc.html

Ruby: rand(1..100)
来源：http://dali.meibo888.top/Article/details/gthxkdfcpk.html

C#:   new Random().Next(1, 101)
来源：http://dali.yongpay.top/Article/details/gtyhzqusvm.html

[A11] 条件表达式（三元）
来源：http://dali.jianghu66.top/Article/details/gtdljwscyg.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.daria6918.cn/Article/details/gtwvvhwrxe.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.cdnleiting.top/Article/details/gttoavekto.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.shzxlz.cn/Article/details/gtsdpmpizh.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.daxiang520.top/Article/details/gtyxghgcuw.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.tian-w.cn/Article/details/gtkgptynln.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.xinyue.icu/Article/details/gtgsafjddt.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.birdmap.top/Article/details/gtebfspsye.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.wangdashe.top/Article/details/gtpojuiaqp.html

[A12] 字符串插值 / 格式化
来源：http://dali.dashuyun.cn/Article/details/gtfnhklvpe.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.chenzaomai.com/Article/details/gtfsmymfrv.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.ppjwa.cn/Article/details/gtojauzjlp.html

JS:   `Hello, ${name}!`
来源：http://dali.zhongyouzk.top/Article/details/gtlrcbrmru.html

TS:   `Hello, ${name}!`
来源：http://dali.xuanzx.com/Article/details/gtjynddgrt.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zycfv.cn/Article/details/gtzvvxcgbo.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtylbuvcnh.html

Ruby: "Hello, #{name}!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvnzzvjv.html

C#:   $"Hello, {name}!"
来源：http://dali.dashuyun.cn/Article/details/gtndaefvnd.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.316326.xyz/Article/details/gttpqlpiow.html

Py:   "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gttcjuobya.html

PHP:  "第一行\n第二行"
来源：http://dali.yj20258888.top/Article/details/gtwqihgeor.html

JS:   "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gtkfifdzez.html

TS:   "第一行\n第二行"
来源：http://dali.gotoacloud.top/Article/details/gtmawbpqdn.html

Java: "第一行\n第二行"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxoptsye.html

Go:   "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gtzsqmbony.html

Ruby: "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gtegyfxpjz.html

C#:   "第一行\n第二行"
来源：http://dali.hammf.cn/Article/details/gttvuvzujq.html

[A14] 注释写法
来源：http://dali.gaohongyu789.top/Article/details/gtshxdavwf.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.hammf.cn/Article/details/gtiaxdtsni.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.gzhubu.top/Article/details/gtbvspvunp.html

JS:   // 单行；/* 多行 */
来源：http://dali.daxiang520.top/Article/details/gtmehpaoam.html


<!-- 参考信息 -->