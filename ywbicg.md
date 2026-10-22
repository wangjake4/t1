代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.zycfv.cn/Article/details/gt2bpmeyhek.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hnxiangtu.top/Article/details/gt2eqobytqp.html

[U92] JS：深拷贝
来源：http://dali.guannengcc.top/Article/details/gt2cbzsfdtf.html

structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2vwlhsvqh.html

[U93] JS：模板字符串
来源：http://dali.shzxlz.cn/Article/details/gt2rorqymnv.html

`共 ${n} 条`
来源：http://dali.wangdashe.top/Article/details/gt2ueqjfnql.html

[U94] JS：箭头函数
来源：http://dali.zdqjudy.top/Article/details/gt2kxfotmtt.html

const double = x => x * 2;
来源：http://dali.316326.xyz/Article/details/gt2rgiicoca.html

[U95] JS：Promise 包装
来源：http://dali.gogol.net.cn/Article/details/gt2esunbvmi.html

new Promise((resolve, reject) => {})
来源：http://dali.jyoumei.cn/Article/details/gt2mtkxzkyx.html

[U96] JS：async/await 与异常
来源：http://dali.svipenyu.cn/Article/details/gt2dvlemjsw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gt2eoprqyjl.html

[U97] JS：并发请求
来源：http://dali.chenlongwang.top/Article/details/gt2nmzsbbsj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gt2ntfqbgtb.html

[U98] JS：fetch 带 JSON
来源：http://dali.hfpthk.cn/Article/details/gt2pnulluqi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cqqwz.cn/Article/details/gt2sdoesihg.html

[U99] JS：事件监听
来源：http://dali.gotoacloud.top/Article/details/gt2vzaasugi.html

el.addEventListener("click", e => {})
来源：http://dali.zhoulong.xyz/Article/details/gt2yevkbfcm.html

[U100] JS：DOM 查询
来源：http://dali.jyoumei.cn/Article/details/gt2xlymaivw.html

document.querySelector(".item")
来源：http://dali.shzxlz.cn/Article/details/gt2gngzuhzd.html

[U101] JS：classList 操作
来源：http://dali.cashguo.top/Article/details/gt2zritxlzn.html

el.classList.toggle("active")
来源：http://dali.tian-w.cn/Article/details/gt2juuljpzt.html

[U102] JS：本地存储
来源：http://dali.zhongyouzk.top/Article/details/gt2qmboaorm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.haohaochexian.top/Article/details/gt2rhsttvot.html

[U103] JS：定时器
来源：http://dali.tanke756.top/Article/details/gt2ykenlwlp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yueranfly.top/Article/details/gt2oiqvsycr.html

[U104] JS：防抖
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bygmehzz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gt2deqnhxsa.html

[U105] JS：节流
来源：http://dali.cqqwz.cn/Article/details/gt2narowxeb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.9152youxi.cn/Article/details/gt2prpwlixt.html

[U106] JS：日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gt2dpkqtatk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yvedp.cn/Article/details/gt2bldgyuqo.html

[U107] JS：数字千分位
来源：http://dali.cheryme.top/Article/details/gt2lxllrhnd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hywenlv.cn/Article/details/gt2cnropzyw.html

[U108] JS：随机整数
来源：http://dali.yj20258888.top/Article/details/gt2milicoye.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.gotoacloud.top/Article/details/gt2kfctkadm.html

[U109] JS：数组分组
来源：http://dali.smart0.xyz/Article/details/gt2xbrfaplv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sweek.top/Article/details/gt2dqdqqojo.html

[U110] JS：数组分块
来源：http://dali.hfpthk.cn/Article/details/gt2gupiewkv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cucudq.cn/Article/details/gt2ibrjhbpb.html

[U111] JS：对象转 Map
来源：http://dali.andypj.xyz/Article/details/gt2kzxohlri.html

new Map(Object.entries(obj))
来源：http://dali.chenlongwang.top/Article/details/gt2cgyjbsci.html

[U112] JS：字符串补位
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2quxvmbdw.html

"7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gt2hhezmijz.html

[U113] JS：正则替换全部
来源：http://dali.guannengcc.top/Article/details/gt2eamiqcil.html

s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2nynhhptt.html

[U114] JS：JSON 深比较
来源：http://dali.cucudq.cn/Article/details/gt2zwswgrst.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigfzy.top/Article/details/gt2gxehnlen.html

[U115] JS：生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gt2ebejkdxj.html

crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gt2fxlmbaez.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.kuanghao11.cn/Article/details/gt2xykhvfwv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jyoumei.cn/Article/details/gt2bsxqdfnl.html

[U117] JS：单元测试
来源：http://dali.haohaochexian.top/Article/details/gt2xsuqfosk.html

npm i -D vitest;  npx vitest
来源：http://dali.guannengcc.top/Article/details/gt2einojhlb.html

[U118] JS：开发服务器
来源：http://dali.aibaodan.cn/Article/details/gt2rznrbnzv.html

npm i -D vite;  npx vite
来源：http://dali.hongshengwenyu.top/Article/details/gt2nnimerhg.html

[U119] JS：生产构建
来源：http://dali.sysykeji.top/Article/details/gt2qezipjsl.html

npx vite build
来源：http://dali.andypj.xyz/Article/details/gt2qpwswaez.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.chenzaomai.com/Article/details/gt2sjrsgjkc.html

import.meta.env.VITE_API_URL
来源：http://dali.dashuyun.cn/Article/details/gt2eymdahrk.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2mnqznjdw.html

统计汇总
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2etaejfsi.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2pqwmkyml.html

按语言统计（条）：
来源：http://dali.vqdsnc.cn/Article/details/gt2arxkcdrr.html

Python ......... 252
来源：http://dali.yanxiufei.cn/Article/details/gt2sgkjzyju.html

PHP ............ 252
来源：http://dali.guowangkeji.top/Article/details/gt2uyaozzse.html

JavaScript ..... 252
来源：http://dali.yongpay.top/Article/details/gt2wrfxgqtd.html

TypeScript ..... 212
来源：http://dali.ivvv.top/Article/details/gt2nincirrr.html

Java ........... 212
来源：http://dali.ehwqpu.com/Article/details/gt2fjceybws.html

Go ............. 212
来源：http://dali.jiagoushi.top/Article/details/gt2rudcxzto.html

Ruby ........... 212
来源：http://dali.yvedp.cn/Article/details/gt2npchdwsy.html

C# ............. 212
来源：http://dali.ybcxt.top/Article/details/gt2qsbsbwus.html

C .............. 30
来源：http://dali.jlsjyb.cn/Article/details/gt2orhrlwgw.html

C++ ............ 30
来源：http://dali.yj202588.top/Article/details/gt2qhvlybff.html

SQL ............ 90
来源：http://dali.nanxuanxn.top/Article/details/gt2mwvanjsi.html

Bash ........... 80
来源：http://dali.ehwqpu.com/Article/details/gt2yuzcssbt.html

Kotlin ......... 15
来源：http://dali.jqgufenzy.top/Article/details/gt2njualjzb.html

Swift .......... 15
来源：http://dali.nanxuanxn.top/Article/details/gt2ojrwnemt.html

Lua ............ 10
来源：http://dali.c1oappe.top/Article/details/gt2ihsbmrwo.html

Perl ........... 10
来源：http://dali.jinqigufen.top/Article/details/gt2plwijmqm.html

Scala .......... 10
来源：http://dali.pycfn.com/Article/details/gt2jaggppoy.html

------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gt2hvqafrdz.html

合计 ........... 2106 条
来源：http://dali.zhiwuduotai.top/Article/details/gt2nqvkqtvf.html

按章节统计：
来源：http://dali.hnqzz.top/Article/details/gt2bdioeqve.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.nwbrower.top/Article/details/gt2hzjqguuv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.bjfxy.top/Article/details/gt2rulbvgal.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xylfe.cn/Article/details/gt2mioqyiaj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.nanxinkj.top/Article/details/gt2jfkqchxa.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jyoumei.cn/Article/details/gt2fucsccvl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jyoumei.cn/Article/details/gt2mznniqjy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gt2vgcdkqpv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.wangshuangyany.cn/Article/details/gt2cjeglyvg.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gt2bhhqzpxo.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cashguo.top/Article/details/gt2tzzdpeda.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gt2faxiowgt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gt2hwsvasyi.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gt2rsmmrdxm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.gogol.net.cn/Article/details/gt2cycojxct.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xinyue.icu/Article/details/gt2sfdjmptr.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gt2uehloozh.html

Q SQL 专题                              90
来源：http://dali.mhx1999.top/Article/details/gt2jygudahl.html

R Bash 专题                             80
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yygrhmzj.html

S C / C++ 专题                          60
来源：http://dali.andypj.xyz/Article/details/gt2dmzwekwh.html

T 其他语言补充                          60
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2srzzrmse.html

U 高频实用片段                         120
来源：http://dali.ydzc1.top/Article/details/gt2jeuvzwpj.html

------------------------------------
来源：http://dali.c1oappe.top/Article/details/gt2vhtecish.html

合计                                  2106 条
来源：http://dali.chenzaomai.com/Article/details/gt2xqzcxyyg.html

--------------------------------------------------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gt2iwulbyxc.html

使用提醒
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tmzlpgqy.html

--------------------------------------------------------------------------------
来源：http://dali.guannengcc.top/Article/details/gt2xcozoctv.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.nanxinkj.top/Article/details/gt2grzjycmz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pfbioswv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yj20258.top/Article/details/gt2nvnkunvd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yonumen.top/Article/details/gt2escldbzb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.tian-w.cn/Article/details/gt2fyunoolb.html

—— 文件结束 ——
来源：http://dali.gogol.net.cn/Article/details/gt2rbtvybmi.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2sgvyzlxe.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.pengpengdd.cyou/Article/details/gt2dhlhaxui.html

Common Programming Examples Cheat Book
来源：http://dali.pengpengdd.cyou/Article/details/gt2chhofejq.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2iykgewmt.html

【收录内容】
来源：http://dali.jqgfzy.top/Article/details/gt2rdekmwgn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.wangshuangyany.cn/Article/details/gt2vquxyqad.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.chenlongwang.top/Article/details/gt2snnawhew.html

SQL · Bash · C · C++
来源：http://dali.9152youxi.cn/Article/details/gt2nqzuynll.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.gotoacloud.top/Article/details/gt2uyseuwfj.html

【使用说明】
来源：http://dali.hysaishi.cn/Article/details/gt2dnzmbykv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yj202588.top/Article/details/gt2ivcjesed.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.cashguo.top/Article/details/gt2wyhtcopx.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.chenzaomai.com/Article/details/gt2cepaevzx.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.cdnleiting.top/Article/details/gt2uwrcjsgm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jyoumei.cn/Article/details/gt2edrzmfbl.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.daxiang520.top/Article/details/gt2qzwwxcbt.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.daxiang520.top/Article/details/gt2jqispdlo.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cheryme.top/Article/details/gt2lggxutbz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xylfe.cn/Article/details/gt2iticyrhl.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tgehuccp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.tian-w.cn/Article/details/gt2enbtulop.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.ivvv.top/Article/details/gt2fjgpvepr.html

【文件统计】
来源：http://dali.nanxinkj.top/Article/details/gt2oaqnldgc.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yj20258.top/Article/details/gt2afngnuga.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gt2tekqquyg.html

目  录
来源：http://dali.havefunace.top/Article/details/gt2ndbltczt.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gt2ceihifzm.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.haohaochexian.top/Article/details/gt2qidrtltu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shzxlz.cn/Article/details/gt2lnbbkcjk.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.tanke756.top/Article/details/gt2fqdfjwyv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2pymspsil.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhixingplan.top/Article/details/gt2suvoebun.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.nanxinkj.top/Article/details/gt2svyrctgb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ybcxt.top/Article/details/gt2cfhgbrbt.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2womepvam.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yangfankeji.com/Article/details/gt2zxhjzcnc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.cheryme.top/Article/details/gt2poszxfbi.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gt2obuvtirz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.ydzc1.top/Article/details/gt2ptznucmu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gt2dpydlvlk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2ejrohleh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.guowangkeji.top/Article/details/gt2nvitnqeo.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yueranfly.top/Article/details/gt2ajlsvfrs.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yj20258888.top/Article/details/gt2yfnrtkcm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jinqigufen.top/Article/details/gt2cyggrnyw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.chenlongwang.top/Article/details/gt2eqjvrfwa.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.iojbl.cn/Article/details/gt2eazlfoui.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.nanxinkj.top/Article/details/gt2ylqkqvbr.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ippppcvb.html

A. 基础语法与类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2foahlvld.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2gmnasrvo.html

[A01] Hello World
来源：http://dali.9152youxi.cn/Article/details/gt2lwwbxyxi.html

Py:   print("Hello, World!")
来源：http://dali.havefunace.top/Article/details/gt2bvzceang.html

PHP:  echo "Hello, World!";
来源：http://dali.ybcxt.top/Article/details/gt2wwwzsrnb.html

JS:   console.log("Hello, World!");
来源：http://dali.shuidangran.top/Article/details/gt2tqbaxdyg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.sxryk.cn/Article/details/gt2hcvxqeyw.html

Java: System.out.println("Hello, World!");
来源：http://dali.chenjidiqi.icu/Article/details/gt2ejpczhsh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jiagoushi.top/Article/details/gt2svccaidw.html

Ruby: puts "Hello, World!"
来源：http://dali.xuanzx.com/Article/details/gt2qcxkacet.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.sweek.top/Article/details/gt2rimycaze.html

[A02] 变量声明与赋值
来源：http://dali.yvedp.cn/Article/details/gt2vsyloyfo.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.dianchejie.cn/Article/details/gt2tolxwsit.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.meibo888.top/Article/details/gt2osikudcb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ppjwa.cn/Article/details/gt2ikjwydcf.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cucudq.cn/Article/details/gt2pjbsqann.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.tian-w.cn/Article/details/gt2efqudqhq.html

Go:   name := "Alex"; age := 20
来源：http://dali.sweek.top/Article/details/gt2qywzgdqi.html

Ruby: name = "Alex"; age = 20
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pnahcolq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.9152youxi.cn/Article/details/gt2vdtfnzic.html

[A03] 常量定义
来源：http://dali.iojbl.cn/Article/details/gt2vlmdqtom.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.daria6918.cn/Article/details/gt2orepkfsq.html

PHP:  const PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gt2ubyfacjp.html

JS:   const PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ejinzwlg.html

TS:   const PI: number = 3.14159;
来源：http://dali.pycfn.com/Article/details/gt2zteociov.html

Java: static final double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gt2vduvfpkq.html

Go:   const PI = 3.14159
来源：http://dali.shangyingyoupin.top/Article/details/gt2ovtzlrjp.html

Ruby: PI = 3.14159
来源：http://dali.hysaishi.cn/Article/details/gt2pgygpemn.html

C#:   const double PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gt2fbirjvpd.html

[A04] 判断变量类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wrfyebld.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jlsjyb.cn/Article/details/gt2diptzoom.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hywenlv.cn/Article/details/gt2djlfojyr.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yueranfly.top/Article/details/gt2ycdryqin.html

TS:   typeof x; x instanceof Date
来源：http://dali.kuanghao11.cn/Article/details/gt2ldezkkpo.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xuanzx.com/Article/details/gt2gvcgmkjv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.feifeiyinyue.top/Article/details/gt2rukxybnd.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nzuhlnwq.html

C#:   x.GetType().Name; x is int
来源：http://dali.jlsjyb.cn/Article/details/gt2ovhvnmpm.html

[A05] 整数除法与取模
来源：http://dali.chenlongwang.top/Article/details/gt2qubnudba.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2njuxphen.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gt2xdrxxmlt.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xziqi.cn/Article/details/gt2xlhfumcw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhoulong.xyz/Article/details/gt2judtgwsh.html

Java: 7 / 2; 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gt2bvlenzvv.html

Go:   7 / 2; 7 % 2
来源：http://dali.sysykeji.top/Article/details/gt2vafcoxgt.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.mhx1999.top/Article/details/gt2earmcweh.html

C#:   7 / 2; 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gt2ntsqfaws.html

[A06] 字符串转数字
来源：http://dali.ybcxt.top/Article/details/gt2cbrwmnco.html

Py:   int("42"); float("3.14")
来源：http://dali.xuetiantiany.cn/Article/details/gt2pxdwtabq.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cashguo.top/Article/details/gt2besoyach.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.kuanghao11.cn/Article/details/gt2kvfuurno.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ubcflnyb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.guannengcc.top/Article/details/gt2rsldnyxc.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hnxiangtu.top/Article/details/gt2swnkfxbq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhengqikj.top/Article/details/gt2dzcjcvvk.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.tanke756.top/Article/details/gt2qamptldi.html

[A07] 数字转字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2dcidttju.html

Py:   str(42)
来源：http://dali.chenzaomai.com/Article/details/gt2glzcmkjc.html

PHP:  (string) 42; strval(42)
来源：http://dali.hywenlv.cn/Article/details/gt2hyzznrqy.html

JS:   String(42); (42).toString()
来源：http://dali.jiagoushi.top/Article/details/gt2zmevxbio.html

TS:   String(42)
来源：http://dali.yonumen.top/Article/details/gt2kkewutzp.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jqgfzy.top/Article/details/gt2dfylbgxj.html

Go:   strconv.Itoa(42)
来源：http://dali.0kj1m.cn/Article/details/gt2emczepgh.html

Ruby: 42.to_s
来源：http://dali.haohaochexian.top/Article/details/gt2haokiich.html

C#:   42.ToString()
来源：http://dali.kuanghao11.cn/Article/details/gt2pmyopral.html

[A08] 取整与四舍五入
来源：http://dali.aibaodan.cn/Article/details/gt2dibnduxh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.daria6918.cn/Article/details/gt2dfofyvkv.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yvedp.cn/Article/details/gt2grmwiger.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.mhx1999.top/Article/details/gt2gyfhidry.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.cqqwz.cn/Article/details/gt2mfzdokvg.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jlsjyb.cn/Article/details/gt2ttqqvdbc.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.ehwqpu.com/Article/details/gt2saawximh.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.birdmap.top/Article/details/gt2zidauzds.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uldhsigi.html

[A09] 绝对值与最大最小值
来源：http://dali.gogol.net.cn/Article/details/gt2vdqloywd.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.aizwys.cn/Article/details/gt2djdqffto.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gt2klwubkma.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yueranfly.top/Article/details/gt2bwxngrws.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yuxming.cn/Article/details/gt2btbayofp.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yueranfly.top/Article/details/gt2bpukspnq.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhixingplan.top/Article/details/gt2xddxcfxr.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zycfv.cn/Article/details/gt2oquqmekl.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.ybcxt.top/Article/details/gt2kdiwbaci.html

[A10] 生成随机数
来源：http://dali.hnqzz.top/Article/details/gt2iwttluug.html

Py:   import random; random.randint(1, 100)
来源：http://dali.cashguo.top/Article/details/gt2wiwzfiqo.html

PHP:  random_int(1, 100);
来源：http://dali.svipenyu.cn/Article/details/gt2vfpakizh.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ehwqpu.com/Article/details/gt2awdtnzbg.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zdqjudy.top/Article/details/gt2dkyrslqx.html

Java: new Random().nextInt(100) + 1
来源：http://dali.hammf.cn/Article/details/gt2bipaogdp.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.nanxuanxn.top/Article/details/gt2ttgdcuwv.html

Ruby: rand(1..100)
来源：http://dali.yj20258888.top/Article/details/gt2dsncccrb.html

C#:   new Random().Next(1, 101)
来源：http://dali.cucudq.cn/Article/details/gt2jaoezmum.html

[A11] 条件表达式（三元）
来源：http://dali.gogol.net.cn/Article/details/gt2mzkurhmu.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.gaohongyu789.top/Article/details/gt2ogmzubwn.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.jianghu66.top/Article/details/gt2esmvmftw.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.shuidangran.top/Article/details/gt2ixpwlvga.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zdqjudy.top/Article/details/gt2wzprrfuk.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.hnqzz.top/Article/details/gt2hrfyqwqa.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.xuetiantiany.cn/Article/details/gt2raqmuqpa.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.guowangkeji.top/Article/details/gt2czmmikti.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.cheryme.top/Article/details/gt2jciohddp.html

[A12] 字符串插值 / 格式化
来源：http://dali.zdqjudy.top/Article/details/gt2sxhseagf.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.xinyue.icu/Article/details/gt2finmzypk.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.gaohongyu789.top/Article/details/gt2swqxhbqt.html

JS:   `Hello, ${name}!`
来源：http://dali.fengsongda.top/Article/details/gt2dlxheogh.html

TS:   `Hello, ${name}!`
来源：http://dali.9152youxi.cn/Article/details/gt2bylsjdln.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zycfv.cn/Article/details/gt2whugmyjp.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.hysaishi.cn/Article/details/gt2honnhsdd.html

Ruby: "Hello, #{name}!"
来源：http://dali.pengpengdd.cyou/Article/details/gt2zovsehwm.html

C#:   $"Hello, {name}!"
来源：http://dali.sxryk.cn/Article/details/gt2kyslfjkv.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zycfv.cn/Article/details/gt2pcnipxlz.html

Py:   "第一行\n第二行"
来源：http://dali.meibo888.top/Article/details/gt2btyxcfxk.html

PHP:  "第一行\n第二行"
来源：http://dali.gaohongyu789.top/Article/details/gt2vnutadcf.html

JS:   "第一行\n第二行"
来源：http://dali.xinyue.icu/Article/details/gt2qwzspojl.html

TS:   "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fivnuuzs.html

Java: "第一行\n第二行"
来源：http://dali.c1oappe.top/Article/details/gt2ketecnsv.html

Go:   "第一行\n第二行"
来源：http://dali.hysaishi.cn/Article/details/gt2qxydcfbh.html

Ruby: "第一行\n第二行"
来源：http://dali.gotoacloud.top/Article/details/gt2eofhcpst.html

C#:   "第一行\n第二行"
来源：http://dali.birdmap.top/Article/details/gt2aohywwhf.html

[A14] 注释写法
来源：http://dali.fengsongda.top/Article/details/gt2ckrxbttd.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.hnqzz.top/Article/details/gt2iiifogvc.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.ydzc1.top/Article/details/gt2mjmyzbvl.html

JS:   // 单行；/* 多行 */
来源：http://dali.hywenlv.cn/Article/details/gt2doqukopi.html

TS:   // 单行；/* 多行 */
来源：http://dali.wangshuangyany.cn/Article/details/gt2opwxvxsg.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.xylfe.cn/Article/details/gt2ngiutpsn.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhoulong.xyz/Article/details/gt2vdtmdmai.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.tian-w.cn/Article/details/gt2djtuqnkh.html

C#:   // 单行；/* 多行 */
来源：http://dali.jinqigufen.top/Article/details/gt2agrgxecg.html

[A15] 空值判断与默认值
来源：http://dali.pengpengdd.cyou/Article/details/gt2amgfurpm.html

Py:   value = data or "默认值"
来源：http://dali.mhx1999.top/Article/details/gt2afbugqun.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zycfv.cn/Article/details/gt2ahhnprcd.html

JS:   const value = data ?? "默认值";
来源：http://dali.sufxvd.cn/Article/details/gt2mgmfdfkn.html

TS:   const value = data ?? "默认值";
来源：http://dali.tanke756.top/Article/details/gt2dxhfrfvr.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yj20258.top/Article/details/gt2etigxfng.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.dashuyun.cn/Article/details/gt2ogxnchjj.html


<!-- 参考信息 -->