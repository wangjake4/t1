代发 wailian999

[U89] JS：数组去重
来源：http://dali.cucudq.cn/Article/details/gticjspifk.html

[...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gtfqyntqgk.html

[U90] JS：数字数组排序
来源：http://dali.wangshuangyany.cn/Article/details/gtphspceas.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gttyldjsnk.html

[U91] JS：对象键值遍历
来源：http://dali.jqgfzy.top/Article/details/gtuwiosswo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ybcxt.top/Article/details/gtgfpwnkth.html

[U92] JS：深拷贝
来源：http://dali.aibaodan.cn/Article/details/gttckkxkbf.html

structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gtgfgbyblz.html

[U93] JS：模板字符串
来源：http://dali.hnqzz.top/Article/details/gtbszmwzoo.html

`共 ${n} 条`
来源：http://dali.yj20258.top/Article/details/gtzdodgztb.html

[U94] JS：箭头函数
来源：http://dali.yonumen.top/Article/details/gtdjwxvdrd.html

const double = x => x * 2;
来源：http://dali.tianlin.xyz/Article/details/gtrzcheutt.html

[U95] JS：Promise 包装
来源：http://dali.chenlongwang.top/Article/details/gtjwvkhchb.html

new Promise((resolve, reject) => {})
来源：http://dali.yonumen.top/Article/details/gtenolqenq.html

[U96] JS：async/await 与异常
来源：http://dali.nanxinkj.top/Article/details/gtatudbxbw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtvjegmkzm.html

[U97] JS：并发请求
来源：http://dali.daxiang520.top/Article/details/gtwdhjmohi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gtojnlwhgv.html

[U98] JS：fetch 带 JSON
来源：http://dali.gogol.net.cn/Article/details/gtvnycwcte.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.tianlin.xyz/Article/details/gtwerhzeuf.html

[U99] JS：事件监听
来源：http://dali.chenjidiqi.icu/Article/details/gtmuhphyrz.html

el.addEventListener("click", e => {})
来源：http://dali.cqqwz.cn/Article/details/gtqpvtlhaw.html

[U100] JS：DOM 查询
来源：http://dali.cheryme.top/Article/details/gtwvfevlkc.html

document.querySelector(".item")
来源：http://dali.andypj.xyz/Article/details/gtjzpgrxjt.html

[U101] JS：classList 操作
来源：http://dali.yueranfly.top/Article/details/gtahwtqzsu.html

el.classList.toggle("active")
来源：http://dali.jyoumei.cn/Article/details/gthlwgddxt.html

[U102] JS：本地存储
来源：http://dali.zycfv.cn/Article/details/gtkvkomzoz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jlsjyb.cn/Article/details/gttmotlgzl.html

[U103] JS：定时器
来源：http://dali.yangfankeji.com/Article/details/gtqxjwocxw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.chenjidiqi.icu/Article/details/gtayvgndwg.html

[U104] JS：防抖
来源：http://dali.gotoacloud.top/Article/details/gtgagmelyq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gtniheaygr.html

[U105] JS：节流
来源：http://dali.yanxiufei.cn/Article/details/gtovdnminj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.dashuyun.cn/Article/details/gtvdvwtwrp.html

[U106] JS：日期格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzyzvbtn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.quarkkingdee.top/Article/details/gtjhvsjvxx.html

[U107] JS：数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gtzngcxlvo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gotoacloud.top/Article/details/gtjstfmwpz.html

[U108] JS：随机整数
来源：http://dali.jianghu66.top/Article/details/gtjpegtcwx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cqqwz.cn/Article/details/gtbsmjtpjf.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gtdysjqdyc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cqqwz.cn/Article/details/gtsqkumsbm.html

[U110] JS：数组分块
来源：http://dali.nwbrower.top/Article/details/gtpocuqnie.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zdqjudy.top/Article/details/gtmpadidrb.html

[U111] JS：对象转 Map
来源：http://dali.jianghu66.top/Article/details/gtqydaguva.html

new Map(Object.entries(obj))
来源：http://dali.fengsongda.top/Article/details/gtxajbakun.html

[U112] JS：字符串补位
来源：http://dali.zycfv.cn/Article/details/gtfgumypbs.html

"7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gtqucfuoon.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gtrswxmdtb.html

s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtoixduefk.html

[U114] JS：JSON 深比较
来源：http://dali.zdqjudy.top/Article/details/gtzombihyk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj202588.top/Article/details/gtqoiyhzos.html

[U115] JS：生成 UUID
来源：http://dali.pycfn.com/Article/details/gtfajyxcse.html

crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gtsmjfzuix.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.nwbrower.top/Article/details/gthqhnldgx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ehwqpu.com/Article/details/gtiyobafyo.html

[U117] JS：单元测试
来源：http://dali.hongshengwenyu.top/Article/details/gthsyyyyxh.html

npm i -D vitest;  npx vitest
来源：http://dali.feifeiyinyue.top/Article/details/gtotbmezud.html

[U118] JS：开发服务器
来源：http://dali.dianchejie.cn/Article/details/gtcoeeubft.html

npm i -D vite;  npx vite
来源：http://dali.cucudq.cn/Article/details/gteuuqdbwt.html

[U119] JS：生产构建
来源：http://dali.chenjidiqi.icu/Article/details/gtbbcwpisc.html

npx vite build
来源：http://dali.sweek.top/Article/details/gtjijicvrt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.guannengcc.top/Article/details/gtsnflnuoi.html

import.meta.env.VITE_API_URL
来源：http://dali.sweek.top/Article/details/gtiwhhetwy.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtdxspefzk.html

统计汇总
来源：http://dali.316326.xyz/Article/details/gtnhfxcqmb.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtjfndiepf.html

按语言统计（条）：
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjqsqmpv.html

Python ......... 252
来源：http://dali.shzxlz.cn/Article/details/gtxmfvktda.html

PHP ............ 252
来源：http://dali.chenzaomai.com/Article/details/gttjlhhyzd.html

JavaScript ..... 252
来源：http://dali.xziqi.cn/Article/details/gtmvppfunk.html

TypeScript ..... 212
来源：http://dali.yonumen.top/Article/details/gtexcmlqll.html

Java ........... 212
来源：http://dali.jianghu66.top/Article/details/gtknxagsor.html

Go ............. 212
来源：http://dali.cqqwz.cn/Article/details/gtyowudzvt.html

Ruby ........... 212
来源：http://dali.shangyingyoupin.top/Article/details/gtwosncaht.html

C# ............. 212
来源：http://dali.mhx1999.top/Article/details/gtmlscptbr.html

C .............. 30
来源：http://dali.xuanzx.com/Article/details/gthxexhnnq.html

C++ ............ 30
来源：http://dali.daria6918.cn/Article/details/gtfcwwqpvu.html

SQL ............ 90
来源：http://dali.quarkkingdee.top/Article/details/gtgoyamjmk.html

Bash ........... 80
来源：http://dali.redwolf501.top/Article/details/gtkspwaliq.html

Kotlin ......... 15
来源：http://dali.gaohongyu789.top/Article/details/gtukwgghvt.html

Swift .......... 15
来源：http://dali.nanxinkj.top/Article/details/gtvlagkofu.html

Lua ............ 10
来源：http://dali.aibaodan.cn/Article/details/gtvzeujspi.html

Perl ........... 10
来源：http://dali.haohaochexian.top/Article/details/gtdupceyyv.html

Scala .......... 10
来源：http://dali.hysaishi.cn/Article/details/gtchsnmxwp.html

------------------------------------
来源：http://dali.fzhhl.top/Article/details/gtnfhhcjot.html

合计 ........... 2106 条
来源：http://dali.zhiwuduotai.top/Article/details/gtmkiikacl.html

按章节统计：
来源：http://dali.316326.xyz/Article/details/gtbuygcmob.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.havefunace.top/Article/details/gtgfiejpkx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gotoacloud.top/Article/details/gtjmrsjedk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhoulong.xyz/Article/details/gtbvkcaocb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.chenjidiqi.icu/Article/details/gtnlbxhvli.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jinghuilouyu.cn/Article/details/gthabsbxjq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.fengsongda.top/Article/details/gtwtaswwbr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gtunwyxdmt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hnxiangtu.top/Article/details/gtawmtawlw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gtiqkmwmwc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.tanke756.top/Article/details/gtvrveycml.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gtybeinaev.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gtgnklnlpp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gtsbjagtcp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shangyingyoupin.top/Article/details/gtdvdmhtmb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.chenjidiqi.icu/Article/details/gtscdwksjx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gtdqrlcewg.html

Q SQL 专题                              90
来源：http://dali.hfpthk.cn/Article/details/gtehyqlqef.html

R Bash 专题                             80
来源：http://dali.chenjidiqi.icu/Article/details/gtmtgtzkqx.html

S C / C++ 专题                          60
来源：http://dali.fzhhl.top/Article/details/gtxrydqxex.html

T 其他语言补充                          60
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubdbrkcu.html

U 高频实用片段                         120
来源：http://dali.jqgfzy.top/Article/details/gtzxlcyonj.html

------------------------------------
来源：http://dali.tian-w.cn/Article/details/gtvubwasrk.html

合计                                  2106 条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmjynzjf.html

--------------------------------------------------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gtxtljuxil.html

使用提醒
来源：http://dali.yj20258.top/Article/details/gtbtlgzcnu.html

--------------------------------------------------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gteeypephh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhoulong.xyz/Article/details/gtqxnmwbka.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.andypj.xyz/Article/details/gtiqjgiscm.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.bjfxy.top/Article/details/gtzkbveniv.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.0kj1m.cn/Article/details/gtnftcejnj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jianghu66.top/Article/details/gtzanfexuc.html

—— 文件结束 ——
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmohnnpgh.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtnuljdizh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.daxiang520.top/Article/details/gtqjirmwjm.html

Common Programming Examples Cheat Book
来源：http://dali.cqqwz.cn/Article/details/gteujzuhwx.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtsxwmjhev.html

【收录内容】
来源：http://dali.yuanzhike.top/Article/details/gtwktyupzq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cucudq.cn/Article/details/gtcnaqlvjs.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.wangshuangyany.cn/Article/details/gtravzilaf.html

SQL · Bash · C · C++
来源：http://dali.fzhhl.top/Article/details/gtvmfodkyn.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.andypj.xyz/Article/details/gtyqhssngu.html

【使用说明】
来源：http://dali.jiagoushi.top/Article/details/gtrdyerxpm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ybcxt.top/Article/details/gtvjgpinta.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.pengpengdd.cyou/Article/details/gtouywgxhw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jyoumei.cn/Article/details/gtpxeadgpn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ivvv.top/Article/details/gtecriyhhx.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xylfe.cn/Article/details/gtgscfrlwx.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenzaomai.com/Article/details/gtewzcucpk.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cheryme.top/Article/details/gtjapwrnbe.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zycfv.cn/Article/details/gtulzzcein.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shanyushiyangtech.top/Article/details/gtasgtmnhv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhiwuduotai.top/Article/details/gtomeciqre.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yongpay.top/Article/details/gtdxiznhnr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hfpthk.cn/Article/details/gtwvjlndrg.html

【文件统计】
来源：http://dali.aizwys.cn/Article/details/gtvqraghsh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yuxming.cn/Article/details/gttwkkidlw.html

--------------------------------------------------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gtyodufzjb.html

目  录
来源：http://dali.zhongyouzk.top/Article/details/gtckebdfdm.html

--------------------------------------------------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gtvrerlnjy.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.guowangkeji.top/Article/details/gtshuswaqa.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yj202588.top/Article/details/gtbsaljpcg.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxailxwk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.dianchejie.cn/Article/details/gtmltznjwb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.smart0.xyz/Article/details/gtxqepsdky.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.cqqwz.cn/Article/details/gtdolpmcrv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cqqwz.cn/Article/details/gtmiqdmybu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ydzc1.top/Article/details/gtfebdbxpr.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmdjixtz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtxffycvus.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtixxzqxvm.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gtzixisoqd.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gtvexmbisc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.daria6918.cn/Article/details/gtiwznobpb.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.bjfxy.top/Article/details/gtajpzvixd.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gtcfprzqtu.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jianghu66.top/Article/details/gtgwsvwuox.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtporfnsxo.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.gaohongyu789.top/Article/details/gtvyohsjhd.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgfzy.top/Article/details/gtgyyyzadt.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.tianlin.xyz/Article/details/gtrtwnpeml.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gteulihdjp.html

A. 基础语法与类型
来源：http://dali.nanxuanxn.top/Article/details/gtwtloyxhf.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtsmskkyoo.html

[A01] Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtihietcnd.html

Py:   print("Hello, World!")
来源：http://dali.hnqzz.top/Article/details/gtqrlhpmmh.html

PHP:  echo "Hello, World!";
来源：http://dali.nanxinkj.top/Article/details/gtfakldlmx.html

JS:   console.log("Hello, World!");
来源：http://dali.0kj1m.cn/Article/details/gtgqhimrcm.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xylfe.cn/Article/details/gtpiqsmcre.html

Java: System.out.println("Hello, World!");
来源：http://dali.ppjwa.cn/Article/details/gterzqiguj.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.svipenyu.cn/Article/details/gtmyhciaxq.html

Ruby: puts "Hello, World!"
来源：http://dali.redwolf501.top/Article/details/gtxldqaocq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.c1oappe.top/Article/details/gtjvkaykwt.html

[A02] 变量声明与赋值
来源：http://dali.ppjwa.cn/Article/details/gtmqgwexkt.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shuidangran.top/Article/details/gtsaazaedy.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ppjwa.cn/Article/details/gtiojwusfh.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gtnbxwctiz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jinqigufen.top/Article/details/gtditqpays.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgsxalsen.html

Go:   name := "Alex"; age := 20
来源：http://dali.shuidangran.top/Article/details/gtwywdhotj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhosfqrk.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.tian-w.cn/Article/details/gtlmxlkzhn.html

[A03] 常量定义
来源：http://dali.zhixingplan.top/Article/details/gtnzkudcxa.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shanyushiyangtech.top/Article/details/gttjjntgiv.html

PHP:  const PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtzxrwpxfo.html

JS:   const PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtdznubjlh.html

TS:   const PI: number = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpojeodb.html

Java: static final double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtfmakirrg.html

Go:   const PI = 3.14159
来源：http://dali.chenlongwang.top/Article/details/gthdctlsvw.html

Ruby: PI = 3.14159
来源：http://dali.zhongyouzk.top/Article/details/gtgyuhptub.html

C#:   const double PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtcrviohhn.html

[A04] 判断变量类型
来源：http://dali.guannengcc.top/Article/details/gtyibhzsxy.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jqgufenzy.top/Article/details/gtqyhbjbqm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.havefunace.top/Article/details/gtngwoeouy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.pengpengdd.cyou/Article/details/gtmuydjfoe.html

TS:   typeof x; x instanceof Date
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcctwauph.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jiagoushi.top/Article/details/gtwsyhvxpt.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.chenzaomai.com/Article/details/gtulwixiwa.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.guannengcc.top/Article/details/gtqlpgeouk.html

C#:   x.GetType().Name; x is int
来源：http://dali.fengsongda.top/Article/details/gtpfarcuwm.html

[A05] 整数除法与取模
来源：http://dali.yj202588.top/Article/details/gthodraokb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.hongshengwenyu.top/Article/details/gtsgpfbhrg.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xziqi.cn/Article/details/gtqoqjxjvj.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gtadcirtgq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shuidangran.top/Article/details/gtjodrdsag.html

Java: 7 / 2; 7 % 2
来源：http://dali.cucudq.cn/Article/details/gtznuhbsws.html

Go:   7 / 2; 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gtawxqqkhc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.iojbl.cn/Article/details/gtavuoxtyk.html

C#:   7 / 2; 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gtwmujayjf.html

[A06] 字符串转数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtskavazcj.html

Py:   int("42"); float("3.14")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcoiaygv.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yj20258.top/Article/details/gtaomgjyir.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.haohaochexian.top/Article/details/gtwhmevmpf.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.sxryk.cn/Article/details/gtmcnfpazu.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gtqnbbofls.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jyoumei.cn/Article/details/gtsggqjizc.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jianghu66.top/Article/details/gtoaogkfka.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.c1oappe.top/Article/details/gtxzrlohgz.html

[A07] 数字转字符串
来源：http://dali.ppjwa.cn/Article/details/gtcghgbzhw.html

Py:   str(42)
来源：http://dali.jiagoushi.top/Article/details/gtdgrgjsju.html

PHP:  (string) 42; strval(42)
来源：http://dali.redwolf501.top/Article/details/gttuebojll.html

JS:   String(42); (42).toString()
来源：http://dali.jinqigfzy.top/Article/details/gtmbdymmez.html

TS:   String(42)
来源：http://dali.snrcjt.cn/Article/details/gtwcydpdew.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.gogol.net.cn/Article/details/gtwmfkvkcf.html

Go:   strconv.Itoa(42)
来源：http://dali.shangyingyoupin.top/Article/details/gtqktzdgnv.html

Ruby: 42.to_s
来源：http://dali.kuanghao11.cn/Article/details/gtwrjxrrpy.html

C#:   42.ToString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtexlsxfhw.html

[A08] 取整与四舍五入
来源：http://dali.yonumen.top/Article/details/gtmavdpzmd.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ybcxt.top/Article/details/gtrjpsixmx.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.dianchejie.cn/Article/details/gtwaraljhv.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhiwuduotai.top/Article/details/gtvaogwetf.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.chenlongwang.top/Article/details/gtrhsvniwo.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.xinyue.icu/Article/details/gtxovpnayp.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.nanxuanxn.top/Article/details/gtglamamqe.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.hfpthk.cn/Article/details/gtgvvfbwsl.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jinqigufen.top/Article/details/gtzimiqmvi.html

[A09] 绝对值与最大最小值
来源：http://dali.yvedp.cn/Article/details/gtydzesyhs.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xuanzx.com/Article/details/gtvxjiuhpq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yongpay.top/Article/details/gthuxpmikx.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtnoebrcxw.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gtpsfnptke.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.meibo888.top/Article/details/gtvysxrwcn.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yvedp.cn/Article/details/gtaoychkvw.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.xinyue.icu/Article/details/gtivjmbqne.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gteyfdlhcr.html

[A10] 生成随机数
来源：http://dali.ivvv.top/Article/details/gtaxkaghgx.html

Py:   import random; random.randint(1, 100)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcfonxzz.html

PHP:  random_int(1, 100);
来源：http://dali.316326.xyz/Article/details/gtwzoquyaj.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ppjwa.cn/Article/details/gtxxfeimkq.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.haohaochexian.top/Article/details/gtzxpkmhkd.html

Java: new Random().nextInt(100) + 1
来源：http://dali.redwolf501.top/Article/details/gtqjuijxlq.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.nwbrower.top/Article/details/gtvjwrxngq.html

Ruby: rand(1..100)
来源：http://dali.zhongyouzk.top/Article/details/gtbiaahsjq.html

C#:   new Random().Next(1, 101)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqgfspua.html

[A11] 条件表达式（三元）
来源：http://dali.sysykeji.top/Article/details/gtcsclvoue.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.aibaodan.cn/Article/details/gtmtmexgyg.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.jqgfzy.top/Article/details/gtmwmvlxem.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.pycfn.com/Article/details/gthupcnqvr.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yonumen.top/Article/details/gtawsgnupi.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.kuanghao11.cn/Article/details/gtaqjnsieh.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yangfankeji.com/Article/details/gtkcbefyrp.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.tian-w.cn/Article/details/gtiwunmqhu.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhixingplan.top/Article/details/gtvjnnppja.html

[A12] 字符串插值 / 格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtujclrckv.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.ppjwa.cn/Article/details/gtyqjsehvn.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.dashuyun.cn/Article/details/gtolhgjbyj.html

JS:   `Hello, ${name}!`
来源：http://dali.wangdashe.top/Article/details/gtvrnjvpuv.html

TS:   `Hello, ${name}!`
来源：http://dali.jinqigfzy.top/Article/details/gtnlfruwhn.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.ppjwa.cn/Article/details/gttxswbznc.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.snrcjt.cn/Article/details/gtijbutscc.html

Ruby: "Hello, #{name}!"
来源：http://dali.chenzaomai.com/Article/details/gttbjwdigd.html

C#:   $"Hello, {name}!"
来源：http://dali.c1oappe.top/Article/details/gtrbbjgcvc.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.chenlongwang.top/Article/details/gtglfhvmzb.html

Py:   "第一行\n第二行"
来源：http://dali.guowangkeji.top/Article/details/gtdaqfqeda.html

PHP:  "第一行\n第二行"
来源：http://dali.xinyue.icu/Article/details/gtzkcpuusu.html

JS:   "第一行\n第二行"
来源：http://dali.guowangkeji.top/Article/details/gtzudnublx.html

TS:   "第一行\n第二行"
来源：http://dali.zhengqikj.top/Article/details/gtaruixsuz.html

Java: "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gtigxdsyzn.html

Go:   "第一行\n第二行"
来源：http://dali.guowangkeji.top/Article/details/gtvaqrazpy.html

Ruby: "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gtqesekyjg.html

C#:   "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gtdfifgcoq.html

[A14] 注释写法
来源：http://dali.cqqwz.cn/Article/details/gtikoqmnxc.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.sufxvd.cn/Article/details/gtyewkzpje.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.hnxiangtu.top/Article/details/gtshzvfoyy.html

JS:   // 单行；/* 多行 */
来源：http://dali.smart0.xyz/Article/details/gtiqkrdmnk.html

TS:   // 单行；/* 多行 */
来源：http://dali.aibaodan.cn/Article/details/gttpjmzdgw.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.iojbl.cn/Article/details/gtuxrzdghg.html

Go:   // 单行；/* 多行 */
来源：http://dali.hammf.cn/Article/details/gtyzsikcnr.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.9152youxi.cn/Article/details/gtyzdlqxor.html

C#:   // 单行；/* 多行 */
来源：http://dali.jinqigufen.top/Article/details/gtkvnlonuz.html

[A15] 空值判断与默认值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkwcbogq.html

Py:   value = data or "默认值"
来源：http://dali.hnqzz.top/Article/details/gtkjsleqfz.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jinqigfzy.top/Article/details/gtxduodqts.html


<!-- 参考信息 -->