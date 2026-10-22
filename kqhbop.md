代发 wailian999

[U85] JS：可选链
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iouirsun.html

a?.b?.c
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ybqkujmj.html

[U86] JS：空值合并
来源：http://dali.xuetiantiany.cn/Article/details/gt2tmjwifil.html

a ?? b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hqagrvsw.html

[U87] JS：解构默认值
来源：http://dali.havefunace.top/Article/details/gt2msfnmwpn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhengqikj.top/Article/details/gt2itifmwza.html

[U88] JS：对象展开合并
来源：http://dali.zycfv.cn/Article/details/gt2yvcbpasa.html

{ ...a, ...b }
来源：http://dali.zhoulong.xyz/Article/details/gt2ygkhuxvt.html

[U89] JS：数组去重
来源：http://dali.quarkkingdee.top/Article/details/gt2uuwlggjl.html

[...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gt2zimmsyhc.html

[U90] JS：数字数组排序
来源：http://dali.yuanzhike.top/Article/details/gt2rumgspov.html

[...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gt2sfwzuwzd.html

[U91] JS：对象键值遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zgixtalc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ehwqpu.com/Article/details/gt2usehuoyx.html

[U92] JS：深拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gt2xveoyqns.html

structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qjfbaohk.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcccili.html

`共 ${n} 条`
来源：http://dali.bjfxy.top/Article/details/gt2zzckuhfa.html

[U94] JS：箭头函数
来源：http://dali.quarkkingdee.top/Article/details/gt2uphoidzt.html

const double = x => x * 2;
来源：http://dali.yuanzhike.top/Article/details/gt2vmupjeke.html

[U95] JS：Promise 包装
来源：http://dali.nanxuanxn.top/Article/details/gt2nfakajou.html

new Promise((resolve, reject) => {})
来源：http://dali.quarkkingdee.top/Article/details/gt2mszkdvej.html

[U96] JS：async/await 与异常
来源：http://dali.yj20258888.top/Article/details/gt2wigrvekw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2yvsemsyd.html

[U97] JS：并发请求
来源：http://dali.yueranfly.top/Article/details/gt2rpegpoxh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gt2tlgdxwzr.html

[U98] JS：fetch 带 JSON
来源：http://dali.chenzaomai.com/Article/details/gt2xclmfsgq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xziqi.cn/Article/details/gt2lajtungl.html

[U99] JS：事件监听
来源：http://dali.birdmap.top/Article/details/gt2pcbiscth.html

el.addEventListener("click", e => {})
来源：http://dali.bjfxy.top/Article/details/gt2ncqiypiv.html

[U100] JS：DOM 查询
来源：http://dali.jlsjyb.cn/Article/details/gt2rfdltkkd.html

document.querySelector(".item")
来源：http://dali.dianchejie.cn/Article/details/gt2ceqckxzy.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2boprnkys.html

el.classList.toggle("active")
来源：http://dali.yuanzhike.top/Article/details/gt2wuwrfwrr.html

[U102] JS：本地存储
来源：http://dali.yj20258.top/Article/details/gt2uwwhqfix.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.chenjidiqi.icu/Article/details/gt2rpvbgguv.html

[U103] JS：定时器
来源：http://dali.haohaochexian.top/Article/details/gt2txhlxske.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xuetiantiany.cn/Article/details/gt2rrfvzwvh.html

[U104] JS：防抖
来源：http://dali.smart0.xyz/Article/details/gt2ssghnkmo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gt2ubcazxjc.html

[U105] JS：节流
来源：http://dali.chenlongwang.top/Article/details/gt2bflnpdsj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jinqigfzy.top/Article/details/gt2gzjlstyw.html

[U106] JS：日期格式化
来源：http://dali.tanke756.top/Article/details/gt2bbbwuvvr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.havefunace.top/Article/details/gt2nqqhuhgb.html

[U107] JS：数字千分位
来源：http://dali.dashuyun.cn/Article/details/gt2noncfifb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinqigfzy.top/Article/details/gt2zqfvljuj.html

[U108] JS：随机整数
来源：http://dali.fengsongda.top/Article/details/gt2raejenmg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hywenlv.cn/Article/details/gt2znzbcypp.html

[U109] JS：数组分组
来源：http://dali.yanxiufei.cn/Article/details/gt2sfotiixl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.kuanghao11.cn/Article/details/gt2ztguzkrh.html

[U110] JS：数组分块
来源：http://dali.pycfn.com/Article/details/gt2euhdbvjn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yuxming.cn/Article/details/gt2rqxximre.html

[U111] JS：对象转 Map
来源：http://dali.pengpengdd.cyou/Article/details/gt2sjfbzyky.html

new Map(Object.entries(obj))
来源：http://dali.jlsjyb.cn/Article/details/gt2jpfsgmwc.html

[U112] JS：字符串补位
来源：http://dali.meibo888.top/Article/details/gt2ckbotcgt.html

"7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gt2nchqbltb.html

[U113] JS：正则替换全部
来源：http://dali.wangdashe.top/Article/details/gt2mcfsqdrt.html

s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ppbtgrum.html

[U114] JS：JSON 深比较
来源：http://dali.jiagoushi.top/Article/details/gt2xmjmlzol.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ybcxt.top/Article/details/gt2ljocwvwy.html

[U115] JS：生成 UUID
来源：http://dali.nanxuanxn.top/Article/details/gt2jyuzxspp.html

crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gt2pnwvajta.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shuidangran.top/Article/details/gt2nalmpvji.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gzhubu.top/Article/details/gt2ccmeqrtv.html

[U117] JS：单元测试
来源：http://dali.jqgufenzy.top/Article/details/gt2wiqkxppc.html

npm i -D vitest;  npx vitest
来源：http://dali.zhixingplan.top/Article/details/gt2yfzhojbj.html

[U118] JS：开发服务器
来源：http://dali.meibo888.top/Article/details/gt2meyyhnvm.html

npm i -D vite;  npx vite
来源：http://dali.wangshuangyany.cn/Article/details/gt2blgpiosw.html

[U119] JS：生产构建
来源：http://dali.yueranfly.top/Article/details/gt2wtafxqgf.html

npx vite build
来源：http://dali.jianghu66.top/Article/details/gt2texntlck.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cucudq.cn/Article/details/gt2dnzjjssr.html

import.meta.env.VITE_API_URL
来源：http://dali.vqdsnc.cn/Article/details/gt2dqpfqped.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2esgucmxb.html

统计汇总
来源：http://dali.gaohongyu789.top/Article/details/gt2haiglnue.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2gxijingu.html

按语言统计（条）：
来源：http://dali.dashuyun.cn/Article/details/gt2fsstdaob.html

Python ......... 252
来源：http://dali.jqgufenzy.top/Article/details/gt2mnxqrmva.html

PHP ............ 252
来源：http://dali.zycfv.cn/Article/details/gt2auvbqkij.html

JavaScript ..... 252
来源：http://dali.ppjwa.cn/Article/details/gt2vragjssn.html

TypeScript ..... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qzmxahuh.html

Java ........... 212
来源：http://dali.ivvv.top/Article/details/gt2udrkgjul.html

Go ............. 212
来源：http://dali.sxryk.cn/Article/details/gt2lwdrpcgu.html

Ruby ........... 212
来源：http://dali.316326.xyz/Article/details/gt2xprbrhxa.html

C# ............. 212
来源：http://dali.316326.xyz/Article/details/gt2wkflaivr.html

C .............. 30
来源：http://dali.nwbrower.top/Article/details/gt2oyqapohg.html

C++ ............ 30
来源：http://dali.yj20258.top/Article/details/gt2txfemgwk.html

SQL ............ 90
来源：http://dali.havefunace.top/Article/details/gt2pmkqyumd.html

Bash ........... 80
来源：http://dali.yangfankeji.com/Article/details/gt2kkbyrynj.html

Kotlin ......... 15
来源：http://dali.yonumen.top/Article/details/gt2faukatdq.html

Swift .......... 15
来源：http://dali.yuanzhike.top/Article/details/gt2ymcnqzld.html

Lua ............ 10
来源：http://dali.nwbrower.top/Article/details/gt2vxqcqeex.html

Perl ........... 10
来源：http://dali.jinqigufen.top/Article/details/gt2kakdzbgi.html

Scala .......... 10
来源：http://dali.tanke756.top/Article/details/gt2kfymgxdu.html

------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gt2zyvgbtwo.html

合计 ........... 2106 条
来源：http://dali.xinyue.icu/Article/details/gt2oadlcnio.html

按章节统计：
来源：http://dali.9152youxi.cn/Article/details/gt2rgqfuhbg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.chenjidiqi.icu/Article/details/gt2wozcjpsc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gt2llbryyho.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jlsjyb.cn/Article/details/gt2rxofrsyy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ydzc1.top/Article/details/gt2yyktbtpq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.c1oappe.top/Article/details/gt2zimixmky.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhixingplan.top/Article/details/gt2cvssbvnw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shzxlz.cn/Article/details/gt2bxxmdvrt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhiwuduotai.top/Article/details/gt2fbhvxrqb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gt2kfwuptkr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2upnjzlid.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zhmgneii.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gt2vxcsbybv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gt2wedmiuqi.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.kuanghao11.cn/Article/details/gt2yjhjmsjv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.gogol.net.cn/Article/details/gt2bxqmluui.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gt2utgaykam.html

Q SQL 专题                              90
来源：http://dali.yj202588.top/Article/details/gt2csnwziwf.html

R Bash 专题                             80
来源：http://dali.nwbrower.top/Article/details/gt2hgeertiq.html

S C / C++ 专题                          60
来源：http://dali.pycfn.com/Article/details/gt2plznydvw.html

T 其他语言补充                          60
来源：http://dali.xziqi.cn/Article/details/gt2zxoftqhk.html

U 高频实用片段                         120
来源：http://dali.jinqigfzy.top/Article/details/gt2nznbpslc.html

------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gt2vxfwfspe.html

合计                                  2106 条
来源：http://dali.fengsongda.top/Article/details/gt2xhzzgxuv.html

--------------------------------------------------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gt2hpzodhcz.html

使用提醒
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wwbwzkco.html

--------------------------------------------------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gt2dcoavcxo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jqgfzy.top/Article/details/gt2mzyifyze.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.andypj.xyz/Article/details/gt2imnuviov.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.shuidangran.top/Article/details/gt2exkqwqbw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uxhhrxru.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.smart0.xyz/Article/details/gt2wenqgdyn.html

—— 文件结束 ——
来源：http://dali.tanke756.top/Article/details/gt2zgmeeqbk.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2iburyzlo.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2awsdmaff.html

Common Programming Examples Cheat Book
来源：http://dali.yongpay.top/Article/details/gt2egebgdje.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ivmkohbv.html

【收录内容】
来源：http://dali.hammf.cn/Article/details/gt2dfcdzwws.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ivvv.top/Article/details/gt2yhmoufcf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.daxiang520.top/Article/details/gt2ugmqklvy.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpppamw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.vqdsnc.cn/Article/details/gt2uvivvder.html

【使用说明】
来源：http://dali.feifeiyinyue.top/Article/details/gt2junsclei.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.xziqi.cn/Article/details/gt2zjwlwrrx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mzbpzxoh.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.dashuyun.cn/Article/details/gt2bcapwcdw.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.cheryme.top/Article/details/gt2lrwnhwkv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.tian-w.cn/Article/details/gt2bsnextqz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cashguo.top/Article/details/gt2zunigzme.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gogol.net.cn/Article/details/gt2vxdkcgcf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhiwuduotai.top/Article/details/gt2lhpbghrn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.pycfn.com/Article/details/gt2otnkherz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.daria6918.cn/Article/details/gt2njntnubt.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yueranfly.top/Article/details/gt2ommmugsb.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hnqzz.top/Article/details/gt2xlsveugz.html

【文件统计】
来源：http://dali.xuetiantiany.cn/Article/details/gt2tzrmsuox.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ppjwa.cn/Article/details/gt2bcgpdlgx.html

--------------------------------------------------------------------------------
来源：http://dali.yuxming.cn/Article/details/gt2xgqiwrny.html

目  录
来源：http://dali.chenzaomai.com/Article/details/gt2bbqdizua.html

--------------------------------------------------------------------------------
来源：http://dali.redwolf501.top/Article/details/gt2oydiylrh.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2npnkauld.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.tian-w.cn/Article/details/gt2ljkvlmxi.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2wamuljjv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jianghu66.top/Article/details/gt2orwoiuzo.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zrooaija.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yuxming.cn/Article/details/gt2zsbbfktv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hammf.cn/Article/details/gt2qwrzefyb.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2fbpovhyp.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gt2cyaejqbq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2pdvinbnl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2fxzhiplr.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xinyue.icu/Article/details/gt2ybjokfrf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.birdmap.top/Article/details/gt2mtyixgky.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xinyue.icu/Article/details/gt2wjdgtsbq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jyoumei.cn/Article/details/gt2zxyrwvkm.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2gwqrpsky.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.haohaochexian.top/Article/details/gt2jifdmfal.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.wangdashe.top/Article/details/gt2xltublxs.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.0kj1m.cn/Article/details/gt2tohpwdfm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yongpay.top/Article/details/gt2nolkegtp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenlongwang.top/Article/details/gt2kgvndyup.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2fvsruwmr.html

A. 基础语法与类型
来源：http://dali.cheryme.top/Article/details/gt2hcvlgcta.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2qouohiki.html

[A01] Hello World
来源：http://dali.yongpay.top/Article/details/gt2htluttxe.html

Py:   print("Hello, World!")
来源：http://dali.fzhhl.top/Article/details/gt2mlquugkb.html

PHP:  echo "Hello, World!";
来源：http://dali.aizwys.cn/Article/details/gt2txlljcbj.html

JS:   console.log("Hello, World!");
来源：http://dali.wangdashe.top/Article/details/gt2jwevfzut.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.guowangkeji.top/Article/details/gt2musycggw.html

Java: System.out.println("Hello, World!");
来源：http://dali.cqqwz.cn/Article/details/gt2cdtbrocv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yuanzhike.top/Article/details/gt2tgbnqomd.html

Ruby: puts "Hello, World!"
来源：http://dali.zhongyouzk.top/Article/details/gt2mpeigclj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jlsjyb.cn/Article/details/gt2brqxuntu.html

[A02] 变量声明与赋值
来源：http://dali.dashuyun.cn/Article/details/gt2lxcsojjt.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.fzhhl.top/Article/details/gt2ziuygqxb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iqyuwxqj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jyoumei.cn/Article/details/gt2zmtkprpf.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.sxryk.cn/Article/details/gt2dvvblgpg.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ehwqpu.com/Article/details/gt2rwcmtpeu.html

Go:   name := "Alex"; age := 20
来源：http://dali.guowangkeji.top/Article/details/gt2eznpiaol.html

Ruby: name = "Alex"; age = 20
来源：http://dali.daria6918.cn/Article/details/gt2coiaiuln.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jyoumei.cn/Article/details/gt2uexomyml.html

[A03] 常量定义
来源：http://dali.yj202588.top/Article/details/gt2lcjxuzbk.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.sweek.top/Article/details/gt2gvrnvkci.html

PHP:  const PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gt2irwfqtok.html

JS:   const PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gt2sncikykn.html

TS:   const PI: number = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gt2snpivcqn.html

Java: static final double PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gt2zeeynudo.html

Go:   const PI = 3.14159
来源：http://dali.yj202588.top/Article/details/gt2brochbnd.html

Ruby: PI = 3.14159
来源：http://dali.yuxming.cn/Article/details/gt2dznjckxs.html

C#:   const double PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gt2kumnxblh.html

[A04] 判断变量类型
来源：http://dali.jqgufenzy.top/Article/details/gt2agxhalac.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.nanxuanxn.top/Article/details/gt2tfbfsldy.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hnxiangtu.top/Article/details/gt2yygrkbkb.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jiagoushi.top/Article/details/gt2jfypekai.html

TS:   typeof x; x instanceof Date
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bjqqmkic.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.guannengcc.top/Article/details/gt2tpsgvxkb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.iojbl.cn/Article/details/gt2njbvvqtx.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yanxiufei.cn/Article/details/gt2orhjbvha.html

C#:   x.GetType().Name; x is int
来源：http://dali.ybcxt.top/Article/details/gt2jvmmrncp.html

[A05] 整数除法与取模
来源：http://dali.smart0.xyz/Article/details/gt2avxchhft.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.mhx1999.top/Article/details/gt2skasoodl.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.cashguo.top/Article/details/gt2wujqeatk.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jxfhhati.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.fengsongda.top/Article/details/gt2lweculgd.html

Java: 7 / 2; 7 % 2
来源：http://dali.ydzc1.top/Article/details/gt2wjvzavzx.html

Go:   7 / 2; 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2umbridrz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.meibo888.top/Article/details/gt2ziemxgbb.html

C#:   7 / 2; 7 % 2
来源：http://dali.yvedp.cn/Article/details/gt2tjxbwocu.html

[A06] 字符串转数字
来源：http://dali.yanxiufei.cn/Article/details/gt2xrrwzvun.html

Py:   int("42"); float("3.14")
来源：http://dali.gaohongyu789.top/Article/details/gt2nyncqlbs.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhongyouzk.top/Article/details/gt2xrfoqedg.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.havefunace.top/Article/details/gt2gcpdcyno.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2abzijkvu.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yueranfly.top/Article/details/gt2esjgmyld.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.mhx1999.top/Article/details/gt2vnffnjew.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jlsjyb.cn/Article/details/gt2dcjvjgry.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.wangdashe.top/Article/details/gt2gzwtenkj.html

[A07] 数字转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2ypchkmln.html

Py:   str(42)
来源：http://dali.nanxuanxn.top/Article/details/gt2hnpkudag.html

PHP:  (string) 42; strval(42)
来源：http://dali.chenlongwang.top/Article/details/gt2vhadlnlk.html

JS:   String(42); (42).toString()
来源：http://dali.yj20258888.top/Article/details/gt2eognkunw.html

TS:   String(42)
来源：http://dali.yuxming.cn/Article/details/gt2fcbnixpo.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.9152youxi.cn/Article/details/gt2loyvnvke.html

Go:   strconv.Itoa(42)
来源：http://dali.ivvv.top/Article/details/gt2pqgbrems.html

Ruby: 42.to_s
来源：http://dali.aibaodan.cn/Article/details/gt2zlmgclbm.html

C#:   42.ToString()
来源：http://dali.snrcjt.cn/Article/details/gt2vyguqfod.html

[A08] 取整与四舍五入
来源：http://dali.nwbrower.top/Article/details/gt2qvlykgol.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zdqjudy.top/Article/details/gt2gvimolwh.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.mhx1999.top/Article/details/gt2itqufenx.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jinqigufen.top/Article/details/gt2eobpmgvz.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shuidangran.top/Article/details/gt2gnwowxqf.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mozvncar.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhoulong.xyz/Article/details/gt2gqtnxozk.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.hnqzz.top/Article/details/gt2ogwnlqyd.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.snrcjt.cn/Article/details/gt2wocgcrsb.html

[A09] 绝对值与最大最小值
来源：http://dali.xuanzx.com/Article/details/gt2ibwwznsy.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ohaeoxwt.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xziqi.cn/Article/details/gt2dgowducm.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2poubrfwe.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.sysykeji.top/Article/details/gt2odhbswcl.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2lvvbapao.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.gaohongyu789.top/Article/details/gt2ylsmsgtl.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yuxming.cn/Article/details/gt2jsvjvzvg.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.hnqzz.top/Article/details/gt2porrzdqd.html

[A10] 生成随机数
来源：http://dali.daria6918.cn/Article/details/gt2ckjdufcd.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhengqikj.top/Article/details/gt2xzoczwax.html

PHP:  random_int(1, 100);
来源：http://dali.nanxuanxn.top/Article/details/gt2qwvnidgw.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sweek.top/Article/details/gt2uirfacch.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yangfankeji.com/Article/details/gt2lctlqmgg.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zdqjudy.top/Article/details/gt2zhyykxoz.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hysaishi.cn/Article/details/gt2pyvgxumk.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2yymngxtp.html

C#:   new Random().Next(1, 101)
来源：http://dali.jqgufenzy.top/Article/details/gt2bupnscmo.html

[A11] 条件表达式（三元）
来源：http://dali.sufxvd.cn/Article/details/gt2dhqxjysn.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jinqigfzy.top/Article/details/gt2xmkedgwa.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhoulong.xyz/Article/details/gt2mrvzqeyy.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gt2hrodzkev.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.xinyue.icu/Article/details/gt2ufowlrdy.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yvedp.cn/Article/details/gt2ahhqguha.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.xziqi.cn/Article/details/gt2aclikzkz.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.vqdsnc.cn/Article/details/gt2opdxvdbx.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.andypj.xyz/Article/details/gt2ndqdnket.html

[A12] 字符串插值 / 格式化
来源：http://dali.fengsongda.top/Article/details/gt2ekoehzey.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.tanke756.top/Article/details/gt2vmpqjtvx.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.shzxlz.cn/Article/details/gt2fdgxgknh.html

JS:   `Hello, ${name}!`
来源：http://dali.snrcjt.cn/Article/details/gt2rbmjzuss.html

TS:   `Hello, ${name}!`
来源：http://dali.kuanghao11.cn/Article/details/gt2dqkonjdg.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.gotoacloud.top/Article/details/gt2ngegfprr.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.hnxiangtu.top/Article/details/gt2jlexmzxh.html

Ruby: "Hello, #{name}!"
来源：http://dali.shuidangran.top/Article/details/gt2pwabmtnt.html

C#:   $"Hello, {name}!"
来源：http://dali.pycfn.com/Article/details/gt2hhphwwoq.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.hnxiangtu.top/Article/details/gt2umbhuwxn.html

Py:   "第一行\n第二行"
来源：http://dali.ivvv.top/Article/details/gt2hyqhlfdf.html

PHP:  "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gt2errcwlds.html

JS:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gt2vhamwxmd.html

TS:   "第一行\n第二行"
来源：http://dali.dashuyun.cn/Article/details/gt2krqkuwew.html

Java: "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gt2rnnsidqd.html

Go:   "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gt2yygofokm.html

Ruby: "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gt2gtktzqie.html

C#:   "第一行\n第二行"
来源：http://dali.dianchejie.cn/Article/details/gt2chvvmndg.html

[A14] 注释写法
来源：http://dali.ivvv.top/Article/details/gt2xmqgluqt.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jfkriuuj.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.snrcjt.cn/Article/details/gt2ugjzstqt.html

JS:   // 单行；/* 多行 */
来源：http://dali.yongpay.top/Article/details/gt2mhdkgtvv.html


<!-- 参考信息 -->