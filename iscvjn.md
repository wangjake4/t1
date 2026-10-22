代发 wailian999

[U89] JS：数组去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyattgobw.html

[...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtuyroscwv.html

[U90] JS：数字数组排序
来源：http://dali.nanxuanxn.top/Article/details/gtsiqerudo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gtvwtfrmxm.html

[U91] JS：对象键值遍历
来源：http://dali.pycfn.com/Article/details/gtpqvqvbvt.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.kuanghao11.cn/Article/details/gtmamaoxva.html

[U92] JS：深拷贝
来源：http://dali.hnqzz.top/Article/details/gtcyjvociq.html

structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gtaejxhsfq.html

[U93] JS：模板字符串
来源：http://dali.dianchejie.cn/Article/details/gtvdtfulpj.html

`共 ${n} 条`
来源：http://dali.gzhubu.top/Article/details/gtpogqeulp.html

[U94] JS：箭头函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteinyuzmy.html

const double = x => x * 2;
来源：http://dali.yj202588.top/Article/details/gttjwkdmmb.html

[U95] JS：Promise 包装
来源：http://dali.havefunace.top/Article/details/gtaqktltvn.html

new Promise((resolve, reject) => {})
来源：http://dali.xziqi.cn/Article/details/gtmycwirrw.html

[U96] JS：async/await 与异常
来源：http://dali.tian-w.cn/Article/details/gtmyxmkngw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gtrirhszji.html

[U97] JS：并发请求
来源：http://dali.nwbrower.top/Article/details/gtmsfwexnd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gtkocbbecx.html

[U98] JS：fetch 带 JSON
来源：http://dali.cheryme.top/Article/details/gtzikywniq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cucudq.cn/Article/details/gtkhmlvdks.html

[U99] JS：事件监听
来源：http://dali.daria6918.cn/Article/details/gtymjrseuh.html

el.addEventListener("click", e => {})
来源：http://dali.ivvv.top/Article/details/gtblapincn.html

[U100] JS：DOM 查询
来源：http://dali.nanxuanxn.top/Article/details/gtyspverol.html

document.querySelector(".item")
来源：http://dali.chenjidiqi.icu/Article/details/gtzsraejte.html

[U101] JS：classList 操作
来源：http://dali.yj20258.top/Article/details/gtbvjfpjae.html

el.classList.toggle("active")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmqfteip.html

[U102] JS：本地存储
来源：http://dali.sweek.top/Article/details/gtpqgpnhxs.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sweek.top/Article/details/gtswcjymeb.html

[U103] JS：定时器
来源：http://dali.cheryme.top/Article/details/gtjfwmezgg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.redwolf501.top/Article/details/gtxrjlruae.html

[U104] JS：防抖
来源：http://dali.hnxiangtu.top/Article/details/gthdewxiqg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gtzhmwwlbg.html

[U105] JS：节流
来源：http://dali.yangfankeji.com/Article/details/gtgrgeiegb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gotoacloud.top/Article/details/gtkeyjyyde.html

[U106] JS：日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gthyxuqxsj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hfpthk.cn/Article/details/gteermffte.html

[U107] JS：数字千分位
来源：http://dali.sweek.top/Article/details/gtkeldreke.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.nanxinkj.top/Article/details/gtjsdvjqmw.html

[U108] JS：随机整数
来源：http://dali.fzhhl.top/Article/details/gtxydhbnns.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ybcxt.top/Article/details/gtxffpvuvq.html

[U109] JS：数组分组
来源：http://dali.havefunace.top/Article/details/gtcfjdamfg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgagftfwv.html

[U110] JS：数组分块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwzxswrk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xziqi.cn/Article/details/gtyxnpglxx.html

[U111] JS：对象转 Map
来源：http://dali.gotoacloud.top/Article/details/gtgysdaitg.html

new Map(Object.entries(obj))
来源：http://dali.gzhubu.top/Article/details/gtguplmbdf.html

[U112] JS：字符串补位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzhqnfel.html

"7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxufspxim.html

[U113] JS：正则替换全部
来源：http://dali.yueranfly.top/Article/details/gttfvoeyvo.html

s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtawnflisz.html

[U114] JS：JSON 深比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqhchpkt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ydzc1.top/Article/details/gtdglnbslq.html

[U115] JS：生成 UUID
来源：http://dali.316326.xyz/Article/details/gtmyihiexe.html

crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmrzvvdb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yuxming.cn/Article/details/gtglwxbbfe.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jinqigufen.top/Article/details/gtkdsiudiu.html

[U117] JS：单元测试
来源：http://dali.cashguo.top/Article/details/gtkawnyieg.html

npm i -D vitest;  npx vitest
来源：http://dali.guannengcc.top/Article/details/gtltaajjkf.html

[U118] JS：开发服务器
来源：http://dali.jqgufenzy.top/Article/details/gthgbvqyuk.html

npm i -D vite;  npx vite
来源：http://dali.tianlin.xyz/Article/details/gtfaufsszh.html

[U119] JS：生产构建
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzwwaqvy.html

npx vite build
来源：http://dali.svipenyu.cn/Article/details/gtxhejokoe.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gzhubu.top/Article/details/gtidcfmuci.html

import.meta.env.VITE_API_URL
来源：http://dali.yonumen.top/Article/details/gtubdaytaf.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtwhazorzy.html

统计汇总
来源：http://dali.9152youxi.cn/Article/details/gtutlnsvaf.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxfkxufk.html

按语言统计（条）：
来源：http://dali.shzxlz.cn/Article/details/gtzgdolkjg.html

Python ......... 252
来源：http://dali.nanxuanxn.top/Article/details/gtrtxadlsp.html

PHP ............ 252
来源：http://dali.sweek.top/Article/details/gtclodwxlw.html

JavaScript ..... 252
来源：http://dali.tianlin.xyz/Article/details/gtjzgpndtf.html

TypeScript ..... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfvgcocc.html

Java ........... 212
来源：http://dali.hysaishi.cn/Article/details/gturqnnmbe.html

Go ............. 212
来源：http://dali.shuidangran.top/Article/details/gtqhgbpuel.html

Ruby ........... 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gtigxyrgzt.html

C# ............. 212
来源：http://dali.snrcjt.cn/Article/details/gtszirkrzt.html

C .............. 30
来源：http://dali.gzhubu.top/Article/details/gthafnniox.html

C++ ............ 30
来源：http://dali.daxiang520.top/Article/details/gtppsiuhrz.html

SQL ............ 90
来源：http://dali.0kj1m.cn/Article/details/gtxrrzzvmk.html

Bash ........... 80
来源：http://dali.ydzc1.top/Article/details/gtsozfxbyo.html

Kotlin ......... 15
来源：http://dali.jiagoushi.top/Article/details/gtxkqjhckf.html

Swift .......... 15
来源：http://dali.sweek.top/Article/details/gtgrgpiozt.html

Lua ............ 10
来源：http://dali.hnqzz.top/Article/details/gtmukiilde.html

Perl ........... 10
来源：http://dali.birdmap.top/Article/details/gtyztaxgud.html

Scala .......... 10
来源：http://dali.9152youxi.cn/Article/details/gtcxguywey.html

------------------------------------
来源：http://dali.daria6918.cn/Article/details/gtbrejqniw.html

合计 ........... 2106 条
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjonqdbyl.html

按章节统计：
来源：http://dali.jlsjyb.cn/Article/details/gtmaclcuxr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.dianchejie.cn/Article/details/gthppwlfhu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sxryk.cn/Article/details/gtiikkjptp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.c1oappe.top/Article/details/gtwmptwmxl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cdnleiting.top/Article/details/gtbhcmxqxg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xuetiantiany.cn/Article/details/gtzfiskyxl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.havefunace.top/Article/details/gtvckgawhp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jqgufenzy.top/Article/details/gtebqwvkfq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.sysykeji.top/Article/details/gtxgctqdex.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gtoxdiaqsu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.fengsongda.top/Article/details/gtpcqudtyw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gtixjdfjbj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yj20258888.top/Article/details/gtvtqbiive.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gtwqlvlxpa.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.chenzaomai.com/Article/details/gtqpewnvvo.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.bjfxy.top/Article/details/gtyslebjio.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtgljbejhh.html

Q SQL 专题                              90
来源：http://dali.hammf.cn/Article/details/gtczjsimwh.html

R Bash 专题                             80
来源：http://dali.hysaishi.cn/Article/details/gtyvauhndi.html

S C / C++ 专题                          60
来源：http://dali.xziqi.cn/Article/details/gtkrktoliv.html

T 其他语言补充                          60
来源：http://dali.chenlongwang.top/Article/details/gtwfariiby.html

U 高频实用片段                         120
来源：http://dali.yonumen.top/Article/details/gtrsirdzbb.html

------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gtderpnlkl.html

合计                                  2106 条
来源：http://dali.sufxvd.cn/Article/details/gtymnulbon.html

--------------------------------------------------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqacdccjc.html

使用提醒
来源：http://dali.hnqzz.top/Article/details/gtiwlsnfss.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmuxoqlir.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jyoumei.cn/Article/details/gtnquybtgs.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yangfankeji.com/Article/details/gtppougqxx.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.pycfn.com/Article/details/gtfnhdggiw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.chenlongwang.top/Article/details/gtdxxfpwht.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhengqikj.top/Article/details/gtgcauxnxg.html

—— 文件结束 ——
来源：http://dali.jyoumei.cn/Article/details/gtujdrxoxu.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtnvqvobze.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.dashuyun.cn/Article/details/gtrcqixvbu.html

Common Programming Examples Cheat Book
来源：http://dali.sweek.top/Article/details/gtheujwgqs.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtlfbulngb.html

【收录内容】
来源：http://dali.xziqi.cn/Article/details/gtrscysopq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jiagoushi.top/Article/details/gtafufrnwm.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.pengpengdd.cyou/Article/details/gtbjnucapx.html

SQL · Bash · C · C++
来源：http://dali.svipenyu.cn/Article/details/gtmsthhsea.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.mhx1999.top/Article/details/gtxecrgyqq.html

【使用说明】
来源：http://dali.svipenyu.cn/Article/details/gtzsmotort.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.mhx1999.top/Article/details/gtxwqsmjqa.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ivvv.top/Article/details/gtjodwslpr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yuanzhike.top/Article/details/gtznyyohqc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.0kj1m.cn/Article/details/gttapxmeez.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.fzhhl.top/Article/details/gtkyqnzrrb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.gotoacloud.top/Article/details/gttdphxuqc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cdnleiting.top/Article/details/gtchmrwjef.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.fengsongda.top/Article/details/gtjfcsermt.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.gzhubu.top/Article/details/gtoxsxntlm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cashguo.top/Article/details/gtgkiofulh.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.wangshuangyany.cn/Article/details/gtqjwocbqa.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.wangshuangyany.cn/Article/details/gterpbfuop.html

【文件统计】
来源：http://dali.hnxiangtu.top/Article/details/gtmkrselut.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.bjfxy.top/Article/details/gtpnnjyzwh.html

--------------------------------------------------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gteyqwbbnr.html

目  录
来源：http://dali.pycfn.com/Article/details/gtqgurjcax.html

--------------------------------------------------------------------------------
来源：http://dali.hnqzz.top/Article/details/gtrtesgaah.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxlkyyrme.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.xylfe.cn/Article/details/gtxtwnmawn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.ivvv.top/Article/details/gtetggdrwt.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.quarkkingdee.top/Article/details/gtsnllfdgn.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.chenlongwang.top/Article/details/gtrwyugsvs.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.cqqwz.cn/Article/details/gtcayvftkm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.vqdsnc.cn/Article/details/gtwzrufhbe.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.bjfxy.top/Article/details/gtwzqxtofz.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shuidangran.top/Article/details/gtjsevqiti.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpiawoqp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gtocfmqzyz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnikcmkv.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.0kj1m.cn/Article/details/gthpfyjhex.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gtfgpzbafx.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hongshengwenyu.top/Article/details/gthtlzncgb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.sxryk.cn/Article/details/gtfchxvprh.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.tianlin.xyz/Article/details/gtvexnyaxa.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.fengsongda.top/Article/details/gtccsatpde.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jiagoushi.top/Article/details/gtxssrzvtm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hfpthk.cn/Article/details/gtnprvwrkb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ybcxt.top/Article/details/gtedbhpivu.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtorroimqd.html

A. 基础语法与类型
来源：http://dali.sufxvd.cn/Article/details/gtcgmqzhco.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtssdrwzzf.html

[A01] Hello World
来源：http://dali.zhixingplan.top/Article/details/gtmkrpnrfi.html

Py:   print("Hello, World!")
来源：http://dali.iojbl.cn/Article/details/gtccgdcbol.html

PHP:  echo "Hello, World!";
来源：http://dali.cheryme.top/Article/details/gtiliwegfo.html

JS:   console.log("Hello, World!");
来源：http://dali.nwbrower.top/Article/details/gtzrgeizgy.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhongyouzk.top/Article/details/gtkkpucedl.html

Java: System.out.println("Hello, World!");
来源：http://dali.smart0.xyz/Article/details/gthifgojxr.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sxryk.cn/Article/details/gtzmdtypan.html

Ruby: puts "Hello, World!"
来源：http://dali.zhoulong.xyz/Article/details/gtgsdmywbn.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ydzc1.top/Article/details/gtgpvgxvfp.html

[A02] 变量声明与赋值
来源：http://dali.ydzc1.top/Article/details/gtetpuifzc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.fzhhl.top/Article/details/gtvrscdomx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.daria6918.cn/Article/details/gtzpayyyme.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hywenlv.cn/Article/details/gtxvmjrrvf.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yongpay.top/Article/details/gtirzwmzbb.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zdqjudy.top/Article/details/gtbezkefph.html

Go:   name := "Alex"; age := 20
来源：http://dali.yuanzhike.top/Article/details/gtfacvquex.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhengqikj.top/Article/details/gtshomonln.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.gaohongyu789.top/Article/details/gtiktgmylt.html

[A03] 常量定义
来源：http://dali.jlsjyb.cn/Article/details/gtfeffvwlo.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwnougln.html

PHP:  const PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtftbvsywx.html

JS:   const PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtbnguhqjo.html

TS:   const PI: number = 3.14159;
来源：http://dali.cheryme.top/Article/details/gtyrknfrkw.html

Java: static final double PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtkicxsvet.html

Go:   const PI = 3.14159
来源：http://dali.pengpengdd.cyou/Article/details/gthjdnkkdb.html

Ruby: PI = 3.14159
来源：http://dali.zhongyouzk.top/Article/details/gtesfvgaec.html

C#:   const double PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtvcznqben.html

[A04] 判断变量类型
来源：http://dali.jqgufenzy.top/Article/details/gtejerlhpa.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.guowangkeji.top/Article/details/gtigpkvmaz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gaohongyu789.top/Article/details/gtyjvpeysm.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.cqqwz.cn/Article/details/gtxguebahl.html

TS:   typeof x; x instanceof Date
来源：http://dali.jyoumei.cn/Article/details/gtbybihcao.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbblomll.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.wangshuangyany.cn/Article/details/gtfyfrlxie.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jqgufenzy.top/Article/details/gtiprxxhjv.html

C#:   x.GetType().Name; x is int
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvqoqvxv.html

[A05] 整数除法与取模
来源：http://dali.cucudq.cn/Article/details/gtlpzfqxko.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zycfv.cn/Article/details/gtxcgywxes.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ydzc1.top/Article/details/gtvvlhbdmg.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cashguo.top/Article/details/gtfgudpdwn.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gtkundxyza.html

Java: 7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gtfdekgopx.html

Go:   7 / 2; 7 % 2
来源：http://dali.shuidangran.top/Article/details/gttmzcqghw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gtdyddtmvx.html

C#:   7 / 2; 7 % 2
来源：http://dali.hammf.cn/Article/details/gtbiwtnubp.html

[A06] 字符串转数字
来源：http://dali.yanxiufei.cn/Article/details/gtsquegofh.html

Py:   int("42"); float("3.14")
来源：http://dali.hnxiangtu.top/Article/details/gtvmnnyueu.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hnxiangtu.top/Article/details/gteolooezt.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ybcxt.top/Article/details/gtrclpltvh.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.havefunace.top/Article/details/gtyqhuzjby.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jyoumei.cn/Article/details/gtrcqdrhcd.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhixingplan.top/Article/details/gtbpsochdy.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jqgfzy.top/Article/details/gtepiqfsgb.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.shangyingyoupin.top/Article/details/gtewfgxuuj.html

[A07] 数字转字符串
来源：http://dali.yvedp.cn/Article/details/gtkqxrvrwf.html

Py:   str(42)
来源：http://dali.hnqzz.top/Article/details/gtyzehwmvw.html

PHP:  (string) 42; strval(42)
来源：http://dali.snrcjt.cn/Article/details/gtstofhqnp.html

JS:   String(42); (42).toString()
来源：http://dali.cashguo.top/Article/details/gtlxdxucgs.html

TS:   String(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexlntndb.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijilzdjm.html

Go:   strconv.Itoa(42)
来源：http://dali.svipenyu.cn/Article/details/gtntfctelu.html

Ruby: 42.to_s
来源：http://dali.zhixingplan.top/Article/details/gtjusuijlm.html

C#:   42.ToString()
来源：http://dali.snrcjt.cn/Article/details/gtfiiaxowy.html

[A08] 取整与四舍五入
来源：http://dali.fengsongda.top/Article/details/gtcppifssb.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hfpthk.cn/Article/details/gtdjzwmnjq.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yongpay.top/Article/details/gtxxofhncf.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.316326.xyz/Article/details/gttxormzle.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.gaohongyu789.top/Article/details/gtbmxmhsyi.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.gaohongyu789.top/Article/details/gtavwohpte.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.xinyue.icu/Article/details/gtwgmfwnxz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.hongshengwenyu.top/Article/details/gtltjjxhml.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.sysykeji.top/Article/details/gtxmmwcazm.html

[A09] 绝对值与最大最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaezefqgk.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gtrkzcelkl.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtqcbjudoe.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gtooeppxhx.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.tanke756.top/Article/details/gtugtuwqbr.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtronmjuov.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jqgfzy.top/Article/details/gtdrvrmkgb.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yangfankeji.com/Article/details/gtiutdaexj.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gtvnzrudhq.html

[A10] 生成随机数
来源：http://dali.gotoacloud.top/Article/details/gtwkrcrinv.html

Py:   import random; random.randint(1, 100)
来源：http://dali.bjfxy.top/Article/details/gtjjremehk.html

PHP:  random_int(1, 100);
来源：http://dali.haohaochexian.top/Article/details/gtpgwthrpp.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ivvv.top/Article/details/gtmkfsnkej.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.0kj1m.cn/Article/details/gtptepsfta.html

Java: new Random().nextInt(100) + 1
来源：http://dali.shuidangran.top/Article/details/gtezakqyup.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.sufxvd.cn/Article/details/gtmogvdpmi.html

Ruby: rand(1..100)
来源：http://dali.316326.xyz/Article/details/gthjlupkph.html

C#:   new Random().Next(1, 101)
来源：http://dali.cdnleiting.top/Article/details/gtgwwhfrtm.html

[A11] 条件表达式（三元）
来源：http://dali.zhengqikj.top/Article/details/gtnamkzzxf.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbiypgule.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.bjfxy.top/Article/details/gthjhbgbiu.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.bjfxy.top/Article/details/gthunjoyot.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidddhxmg.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.hammf.cn/Article/details/gtvueaditr.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.sweek.top/Article/details/gtdjngvwec.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.ivvv.top/Article/details/gtiikldsql.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhiwuduotai.top/Article/details/gttepddvbu.html

[A12] 字符串插值 / 格式化
来源：http://dali.jqgfzy.top/Article/details/gtswavzowp.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.chenlongwang.top/Article/details/gtzaqjiyjq.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.pengpengdd.cyou/Article/details/gtonfmypga.html

JS:   `Hello, ${name}!`
来源：http://dali.andypj.xyz/Article/details/gthgyusuyr.html

TS:   `Hello, ${name}!`
来源：http://dali.ybcxt.top/Article/details/gtwvvdpbew.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.redwolf501.top/Article/details/gtxmklymof.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jlsjyb.cn/Article/details/gtqafdheqc.html

Ruby: "Hello, #{name}!"
来源：http://dali.ybcxt.top/Article/details/gtzyyhkbiz.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gtonhxarky.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.ehwqpu.com/Article/details/gtqyjqapud.html

Py:   "第一行\n第二行"
来源：http://dali.shzxlz.cn/Article/details/gtxhuxgkuk.html

PHP:  "第一行\n第二行"
来源：http://dali.birdmap.top/Article/details/gthzbjddxm.html

JS:   "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gtmlmpdxnc.html

TS:   "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gtfjfcwxul.html

Java: "第一行\n第二行"
来源：http://dali.tianlin.xyz/Article/details/gtwjpdvwku.html

Go:   "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gtnvjvdrnr.html

Ruby: "第一行\n第二行"
来源：http://dali.dashuyun.cn/Article/details/gtlclizmhb.html

C#:   "第一行\n第二行"
来源：http://dali.guowangkeji.top/Article/details/gttwzpdnds.html

[A14] 注释写法
来源：http://dali.zhoulong.xyz/Article/details/gtpiezzfhw.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.shzxlz.cn/Article/details/gteomhqrni.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.pycfn.com/Article/details/gtfdfqprnu.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhongyouzk.top/Article/details/gtspgdxitl.html

TS:   // 单行；/* 多行 */
来源：http://dali.jinqigfzy.top/Article/details/gtmijwabwc.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jqgfzy.top/Article/details/gtklhtcqma.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhengqikj.top/Article/details/gtlirsdxpx.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.mhx1999.top/Article/details/gtauwpnyvz.html

C#:   // 单行；/* 多行 */
来源：http://dali.vqdsnc.cn/Article/details/gtkkgkmmis.html

[A15] 空值判断与默认值
来源：http://dali.tanke756.top/Article/details/gtrkpwxtbb.html

Py:   value = data or "默认值"
来源：http://dali.sufxvd.cn/Article/details/gtdcgfafeo.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.ybcxt.top/Article/details/gtrpvkapmq.html


<!-- 参考信息 -->