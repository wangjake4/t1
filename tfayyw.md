代发 wailian999

[U89] JS：数组去重
来源：http://dali.hysaishi.cn/Article/details/gtexifeuta.html

[...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gtefdvogzz.html

[U90] JS：数字数组排序
来源：http://dali.zhoulong.xyz/Article/details/gtakqwiluy.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gtnknqezhi.html

[U91] JS：对象键值遍历
来源：http://dali.tianlin.xyz/Article/details/gthrfhdwfi.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.9152youxi.cn/Article/details/gtrqoczbee.html

[U92] JS：深拷贝
来源：http://dali.tianlin.xyz/Article/details/gtdxphkxen.html

structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gtkncparws.html

[U93] JS：模板字符串
来源：http://dali.yvedp.cn/Article/details/gtyybjzqxe.html

`共 ${n} 条`
来源：http://dali.haohaochexian.top/Article/details/gtoemihnsy.html

[U94] JS：箭头函数
来源：http://dali.meibo888.top/Article/details/gtgneiywnl.html

const double = x => x * 2;
来源：http://dali.zhixingplan.top/Article/details/gtojztnpiw.html

[U95] JS：Promise 包装
来源：http://dali.redwolf501.top/Article/details/gtzyqcmxzg.html

new Promise((resolve, reject) => {})
来源：http://dali.zhoulong.xyz/Article/details/gtrucqzlrd.html

[U96] JS：async/await 与异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtoedupsqc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtbaeqoewl.html

[U97] JS：并发请求
来源：http://dali.hywenlv.cn/Article/details/gtofcrzxtk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gtbaqkqlpn.html

[U98] JS：fetch 带 JSON
来源：http://dali.yvedp.cn/Article/details/gtzffrsenq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hnxiangtu.top/Article/details/gtthoplglh.html

[U99] JS：事件监听
来源：http://dali.pengpengdd.cyou/Article/details/gtskidyjla.html

el.addEventListener("click", e => {})
来源：http://dali.aizwys.cn/Article/details/gtzgflmlss.html

[U100] JS：DOM 查询
来源：http://dali.tanke756.top/Article/details/gtsdniyyrl.html

document.querySelector(".item")
来源：http://dali.sysykeji.top/Article/details/gtcaoeiluv.html

[U101] JS：classList 操作
来源：http://dali.yj202588.top/Article/details/gtzinhxfth.html

el.classList.toggle("active")
来源：http://dali.yj20258888.top/Article/details/gtjomgvjub.html

[U102] JS：本地存储
来源：http://dali.xinyue.icu/Article/details/gtwjjxazuj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.tianlin.xyz/Article/details/gtbbugwmea.html

[U103] JS：定时器
来源：http://dali.ivvv.top/Article/details/gtnvjmogqz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yj20258.top/Article/details/gteihahkvf.html

[U104] JS：防抖
来源：http://dali.cdnleiting.top/Article/details/gtbfyyvlst.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gtbqprefmt.html

[U105] JS：节流
来源：http://dali.sufxvd.cn/Article/details/gtimwyukim.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtuagvlaga.html

[U106] JS：日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtqlntlfuh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yj20258.top/Article/details/gtdqwplsnt.html

[U107] JS：数字千分位
来源：http://dali.jlsjyb.cn/Article/details/gtkmhdbejh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ppjwa.cn/Article/details/gtaniktgvw.html

[U108] JS：随机整数
来源：http://dali.wangshuangyany.cn/Article/details/gtxogajfdz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.snrcjt.cn/Article/details/gtngyezxzc.html

[U109] JS：数组分组
来源：http://dali.0kj1m.cn/Article/details/gtyaaqrorx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.tianlin.xyz/Article/details/gtntedvgej.html

[U110] JS：数组分块
来源：http://dali.chenjidiqi.icu/Article/details/gtgeaxsyoa.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jyoumei.cn/Article/details/gtgiwwkexg.html

[U111] JS：对象转 Map
来源：http://dali.mhx1999.top/Article/details/gtdcdvlxvs.html

new Map(Object.entries(obj))
来源：http://dali.daxiang520.top/Article/details/gtavxyhngc.html

[U112] JS：字符串补位
来源：http://dali.zhixingplan.top/Article/details/gtysiskuml.html

"7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtgqceafrc.html

[U113] JS：正则替换全部
来源：http://dali.cucudq.cn/Article/details/gtpinzohoi.html

s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtrzucorzy.html

[U114] JS：JSON 深比较
来源：http://dali.sweek.top/Article/details/gtkfrozesk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgfzy.top/Article/details/gttqjmnpuo.html

[U115] JS：生成 UUID
来源：http://dali.hywenlv.cn/Article/details/gtkwsawsox.html

crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gtljdnnvqe.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.pycfn.com/Article/details/gtnlmvhkik.html

/** @param {string} name */ function f(name) {}
来源：http://dali.9152youxi.cn/Article/details/gtuivkfrty.html

[U117] JS：单元测试
来源：http://dali.daria6918.cn/Article/details/gtskwsdhuf.html

npm i -D vitest;  npx vitest
来源：http://dali.zycfv.cn/Article/details/gtguxtfodx.html

[U118] JS：开发服务器
来源：http://dali.ivvv.top/Article/details/gttixipjlz.html

npm i -D vite;  npx vite
来源：http://dali.jinqigufen.top/Article/details/gtchluyiay.html

[U119] JS：生产构建
来源：http://dali.aizwys.cn/Article/details/gtvlcffiky.html

npx vite build
来源：http://dali.tianlin.xyz/Article/details/gtvoxvjqln.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhoulong.xyz/Article/details/gtsmwcnryd.html

import.meta.env.VITE_API_URL
来源：http://dali.jinqigfzy.top/Article/details/gtrmzzydsl.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtrifxbwda.html

统计汇总
来源：http://dali.gotoacloud.top/Article/details/gtvxcdlgeb.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtitydrctc.html

按语言统计（条）：
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwmyvlnk.html

Python ......... 252
来源：http://dali.xinyue.icu/Article/details/gtgadokvfc.html

PHP ............ 252
来源：http://dali.jyoumei.cn/Article/details/gtorveenox.html

JavaScript ..... 252
来源：http://dali.dashuyun.cn/Article/details/gtlaukaswy.html

TypeScript ..... 212
来源：http://dali.xylfe.cn/Article/details/gtnacawmuk.html

Java ........... 212
来源：http://dali.xuanzx.com/Article/details/gtuskotnsc.html

Go ............. 212
来源：http://dali.zhixingplan.top/Article/details/gtkfcqmloa.html

Ruby ........... 212
来源：http://dali.tanke756.top/Article/details/gtbrtsulfy.html

C# ............. 212
来源：http://dali.jinqigfzy.top/Article/details/gtopslziem.html

C .............. 30
来源：http://dali.aibaodan.cn/Article/details/gtdzsgtzbr.html

C++ ............ 30
来源：http://dali.yueranfly.top/Article/details/gtjixgkkzr.html

SQL ............ 90
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtwqnokv.html

Bash ........... 80
来源：http://dali.bjfxy.top/Article/details/gtukanbeug.html

Kotlin ......... 15
来源：http://dali.guannengcc.top/Article/details/gtkchskagf.html

Swift .......... 15
来源：http://dali.daxiang520.top/Article/details/gtemunrvbe.html

Lua ............ 10
来源：http://dali.jqgufenzy.top/Article/details/gtywiurpky.html

Perl ........... 10
来源：http://dali.yj20258.top/Article/details/gtydkihmbm.html

Scala .......... 10
来源：http://dali.jinqigufen.top/Article/details/gtcamgtwok.html

------------------------------------
来源：http://dali.ivvv.top/Article/details/gtupwgxxym.html

合计 ........... 2106 条
来源：http://dali.xuanzx.com/Article/details/gtmjmsmhmu.html

按章节统计：
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmltzwtjt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.andypj.xyz/Article/details/gtkaghykxb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkqalhdk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.gotoacloud.top/Article/details/gthagbmbzn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jlsjyb.cn/Article/details/gtxnmdjgtj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xinyue.icu/Article/details/gtxrjxghcw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hfpthk.cn/Article/details/gtvluhdayd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gtdwlkmihg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yanxiufei.cn/Article/details/gtvciluwgb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gtopmmtdff.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.kuanghao11.cn/Article/details/gtgostwotx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gtfmrivgja.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gtissrzjna.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gtxclvdnfz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.kuanghao11.cn/Article/details/gtoypfntjp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ybcxt.top/Article/details/gtspjfgeff.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.iojbl.cn/Article/details/gtsmftwdli.html

Q SQL 专题                              90
来源：http://dali.c1oappe.top/Article/details/gtpmidxsel.html

R Bash 专题                             80
来源：http://dali.jlsjyb.cn/Article/details/gtlmikxsqu.html

S C / C++ 专题                          60
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarylhamp.html

T 其他语言补充                          60
来源：http://dali.yuanzhike.top/Article/details/gtkwgakuro.html

U 高频实用片段                         120
来源：http://dali.sxryk.cn/Article/details/gtiysxjbti.html

------------------------------------
来源：http://dali.bjfxy.top/Article/details/gtqonmietw.html

合计                                  2106 条
来源：http://dali.fzhhl.top/Article/details/gtclzfxkuz.html

--------------------------------------------------------------------------------
来源：http://dali.iojbl.cn/Article/details/gtptpunhmq.html

使用提醒
来源：http://dali.chenlongwang.top/Article/details/gtgpdhzygr.html

--------------------------------------------------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gtwkmildls.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xylfe.cn/Article/details/gtgnolanbr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.smart0.xyz/Article/details/gtomxlifbk.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xylfe.cn/Article/details/gtkxpaolzj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.tanke756.top/Article/details/gtcwqqwqup.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.iojbl.cn/Article/details/gtmxtxvdmf.html

—— 文件结束 ——
来源：http://dali.havefunace.top/Article/details/gtolsgsqer.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtnephrcuv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqgsevih.html

Common Programming Examples Cheat Book
来源：http://dali.sweek.top/Article/details/gtkivnxiyg.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtnsuafnvs.html

【收录内容】
来源：http://dali.zhiwuduotai.top/Article/details/gtmftsmcht.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.gogol.net.cn/Article/details/gtzmglbuqq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.pengpengdd.cyou/Article/details/gtwgenlvgf.html

SQL · Bash · C · C++
来源：http://dali.meibo888.top/Article/details/gtsyosvsfs.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ehwqpu.com/Article/details/gtzjibjqfr.html

【使用说明】
来源：http://dali.xylfe.cn/Article/details/gtevedbtug.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.smart0.xyz/Article/details/gtwpqausfq.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yuxming.cn/Article/details/gthiltwvty.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jinqigufen.top/Article/details/gthucpfxaj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jqgfzy.top/Article/details/gtonunwztj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.iojbl.cn/Article/details/gtjricbymf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhongyouzk.top/Article/details/gtpbnsbvhz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.0kj1m.cn/Article/details/gtrfkjoshy.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cashguo.top/Article/details/gtofriqokf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhoulong.xyz/Article/details/gttnqetssw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shuidangran.top/Article/details/gtobwxaqop.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.birdmap.top/Article/details/gtozvdqnly.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkwvigsy.html

【文件统计】
来源：http://dali.yangfankeji.com/Article/details/gtivktyfgj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.cashguo.top/Article/details/gtarbmqszb.html

--------------------------------------------------------------------------------
来源：http://dali.xylfe.cn/Article/details/gtdydymjdr.html

目  录
来源：http://dali.iojbl.cn/Article/details/gtxmyxpebn.html

--------------------------------------------------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gtorcoxmjx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtwbwlfepm.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hnxiangtu.top/Article/details/gtviaeukyd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.quarkkingdee.top/Article/details/gtehntxsif.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhongyouzk.top/Article/details/gtmrmcgljq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.daria6918.cn/Article/details/gthdbdsxet.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.svipenyu.cn/Article/details/gtbsfzswnd.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.fzhhl.top/Article/details/gthbhosplo.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yongpay.top/Article/details/gtjuxpdvzc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhengqikj.top/Article/details/gtykxyguaa.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jqgfzy.top/Article/details/gtxgfqhzda.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jlsjyb.cn/Article/details/gtduzmnwdz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gttvwhueyk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hysaishi.cn/Article/details/gtnykkzoth.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yueranfly.top/Article/details/gtzjlakohm.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xylfe.cn/Article/details/gtxuuymxmp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yanxiufei.cn/Article/details/gtdrviqdgx.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yvedp.cn/Article/details/gtzykifkfx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jinqigufen.top/Article/details/gtoebviqdb.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jianghu66.top/Article/details/gtirezjovb.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pycfn.com/Article/details/gtvbbcfaou.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.tanke756.top/Article/details/gtgojijxwj.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtdidfpkth.html

A. 基础语法与类型
来源：http://dali.yj20258888.top/Article/details/gtlbesokdo.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtxlwsexst.html

[A01] Hello World
来源：http://dali.tian-w.cn/Article/details/gtpmmqepqo.html

Py:   print("Hello, World!")
来源：http://dali.jiagoushi.top/Article/details/gtlyzdkfgf.html

PHP:  echo "Hello, World!";
来源：http://dali.xuanzx.com/Article/details/gtaqyyrzrk.html

JS:   console.log("Hello, World!");
来源：http://dali.hammf.cn/Article/details/gtthmxgoki.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yangfankeji.com/Article/details/gtswhbvrtq.html

Java: System.out.println("Hello, World!");
来源：http://dali.pengpengdd.cyou/Article/details/gtxlyyizoc.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ehwqpu.com/Article/details/gtctjyqeug.html

Ruby: puts "Hello, World!"
来源：http://dali.nanxuanxn.top/Article/details/gtrfhhrgxl.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xuetiantiany.cn/Article/details/gtzbqgnhtl.html

[A02] 变量声明与赋值
来源：http://dali.hnqzz.top/Article/details/gtcwsumbnc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cheryme.top/Article/details/gtrtztwuye.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.cheryme.top/Article/details/gtsisoqwtw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jyoumei.cn/Article/details/gttgbetixk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gtqvmyxktm.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.shangyingyoupin.top/Article/details/gtdchwxsgc.html

Go:   name := "Alex"; age := 20
来源：http://dali.hongshengwenyu.top/Article/details/gtnwkyjani.html

Ruby: name = "Alex"; age = 20
来源：http://dali.sufxvd.cn/Article/details/gtfxwiznnp.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.gogol.net.cn/Article/details/gtqfdjvzsn.html

[A03] 常量定义
来源：http://dali.hfpthk.cn/Article/details/gtgzjicchr.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.fzhhl.top/Article/details/gteemmzcso.html

PHP:  const PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtwbxvpmxy.html

JS:   const PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtpimzwwum.html

TS:   const PI: number = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsraxqgv.html

Java: static final double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtfymrrtsb.html

Go:   const PI = 3.14159
来源：http://dali.316326.xyz/Article/details/gtgalppnvu.html

Ruby: PI = 3.14159
来源：http://dali.tanke756.top/Article/details/gtyucknvjn.html

C#:   const double PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtmvgmpkad.html

[A04] 判断变量类型
来源：http://dali.jianghu66.top/Article/details/gtzhhtdero.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jyoumei.cn/Article/details/gtjafasafw.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.xinyue.icu/Article/details/gtlowszqqs.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zdqjudy.top/Article/details/gtiprgwmqm.html

TS:   typeof x; x instanceof Date
来源：http://dali.yangfankeji.com/Article/details/gtwhninrlv.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ehwqpu.com/Article/details/gtrqfbioxp.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.tianlin.xyz/Article/details/gtpsynkbkr.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjybgnzcx.html

C#:   x.GetType().Name; x is int
来源：http://dali.9152youxi.cn/Article/details/gtvdddkxtv.html

[A05] 整数除法与取模
来源：http://dali.ybcxt.top/Article/details/gtyusdokvk.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.nanxinkj.top/Article/details/gtmbmlemev.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtyzfgdmpc.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtltomcmag.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yonumen.top/Article/details/gtpyyydcfz.html

Java: 7 / 2; 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gtwlugjdtl.html

Go:   7 / 2; 7 % 2
来源：http://dali.fzhhl.top/Article/details/gtdqyafdfk.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gtdygbyjvs.html

C#:   7 / 2; 7 % 2
来源：http://dali.yj20258888.top/Article/details/gtqhcakasf.html

[A06] 字符串转数字
来源：http://dali.yvedp.cn/Article/details/gtjvmvnepx.html

Py:   int("42"); float("3.14")
来源：http://dali.jlsjyb.cn/Article/details/gtvppaygjd.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.sysykeji.top/Article/details/gtwsqcttjj.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.xinyue.icu/Article/details/gtablgupdk.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.kuanghao11.cn/Article/details/gtjqwbgvxq.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.gogol.net.cn/Article/details/gtqajxewlo.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.meibo888.top/Article/details/gtjtppqdnv.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.cqqwz.cn/Article/details/gtddnzgxlf.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.redwolf501.top/Article/details/gtqmqtttfl.html

[A07] 数字转字符串
来源：http://dali.chenlongwang.top/Article/details/gtmlqooinx.html

Py:   str(42)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjjgzuad.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gtwtqmpjau.html

JS:   String(42); (42).toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwjwjucx.html

TS:   String(42)
来源：http://dali.yuanzhike.top/Article/details/gtgbqcukpm.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jlsjyb.cn/Article/details/gtzdytiyba.html

Go:   strconv.Itoa(42)
来源：http://dali.jqgufenzy.top/Article/details/gtskroagpd.html

Ruby: 42.to_s
来源：http://dali.shzxlz.cn/Article/details/gtdtbegwyb.html

C#:   42.ToString()
来源：http://dali.zhoulong.xyz/Article/details/gtmtdjvuas.html

[A08] 取整与四舍五入
来源：http://dali.sweek.top/Article/details/gtmcuqvcpp.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yuxming.cn/Article/details/gtlrdqqdbw.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.sweek.top/Article/details/gtynyikigi.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gtipxncdtf.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shzxlz.cn/Article/details/gtmuxvskam.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.aizwys.cn/Article/details/gtmxxemtuv.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.pycfn.com/Article/details/gtqlwvncdb.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.bjfxy.top/Article/details/gtsvobcsgb.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.mhx1999.top/Article/details/gtbfbqhgox.html

[A09] 绝对值与最大最小值
来源：http://dali.hfpthk.cn/Article/details/gtnjciktom.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtiyansuqj.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.birdmap.top/Article/details/gtzlyrwunx.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.daxiang520.top/Article/details/gtkwadekhg.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtxpczuuvp.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gtdfhxhayr.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.havefunace.top/Article/details/gtntizwgyi.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.hnqzz.top/Article/details/gtaoviujsc.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtinvrcxgh.html

[A10] 生成随机数
来源：http://dali.c1oappe.top/Article/details/gtrazhhxga.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yanxiufei.cn/Article/details/gtkavrmbkp.html

PHP:  random_int(1, 100);
来源：http://dali.shuidangran.top/Article/details/gtgebfngaz.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ehwqpu.com/Article/details/gtbcimsqku.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.andypj.xyz/Article/details/gtscddfjrr.html

Java: new Random().nextInt(100) + 1
来源：http://dali.xinyue.icu/Article/details/gtwsatotwa.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.tanke756.top/Article/details/gtjsbzpsls.html

Ruby: rand(1..100)
来源：http://dali.quarkkingdee.top/Article/details/gtdniucpff.html

C#:   new Random().Next(1, 101)
来源：http://dali.nanxinkj.top/Article/details/gtnbvwhfpw.html

[A11] 条件表达式（三元）
来源：http://dali.yonumen.top/Article/details/gtzffuisod.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jlsjyb.cn/Article/details/gtkowafpej.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gtyguysmqd.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.hywenlv.cn/Article/details/gtejypvloi.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.bjfxy.top/Article/details/gtvzhxaxtf.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.sweek.top/Article/details/gtqthccpnv.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.nanxinkj.top/Article/details/gtvrfmvvcw.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.9152youxi.cn/Article/details/gtcibcouic.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.xuetiantiany.cn/Article/details/gtqhsjwhbc.html

[A12] 字符串插值 / 格式化
来源：http://dali.vqdsnc.cn/Article/details/gtufrnipcf.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.hywenlv.cn/Article/details/gtywmhnrsb.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.hysaishi.cn/Article/details/gtyiwlxzve.html

JS:   `Hello, ${name}!`
来源：http://dali.jlsjyb.cn/Article/details/gttwjfjjmm.html

TS:   `Hello, ${name}!`
来源：http://dali.zhaomingkeji.xyz/Article/details/gtslpmiuyb.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.andypj.xyz/Article/details/gtjwgdqdyo.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.aibaodan.cn/Article/details/gtqwsrecfz.html

Ruby: "Hello, #{name}!"
来源：http://dali.jqgufenzy.top/Article/details/gtgcnfwilg.html

C#:   $"Hello, {name}!"
来源：http://dali.hfpthk.cn/Article/details/gtgosxzxvu.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.smart0.xyz/Article/details/gtboafoxgi.html

Py:   "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gtkbvqkbwh.html

PHP:  "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gtqzmqkwux.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gtfkaljqcm.html

TS:   "第一行\n第二行"
来源：http://dali.iojbl.cn/Article/details/gtcbzybksw.html

Java: "第一行\n第二行"
来源：http://dali.zhoulong.xyz/Article/details/gtpplpvtln.html

Go:   "第一行\n第二行"
来源：http://dali.sufxvd.cn/Article/details/gtnmfoankr.html

Ruby: "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gtibgwkgsr.html

C#:   "第一行\n第二行"
来源：http://dali.yuanzhike.top/Article/details/gtsjxojywc.html

[A14] 注释写法
来源：http://dali.dashuyun.cn/Article/details/gtafnngaam.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhoulong.xyz/Article/details/gtefhkzypb.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.iojbl.cn/Article/details/gtppfpmthp.html

JS:   // 单行；/* 多行 */
来源：http://dali.tanke756.top/Article/details/gthtnkccdf.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhoulong.xyz/Article/details/gtubjjfbex.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.wangdashe.top/Article/details/gtxuwyqxwp.html

Go:   // 单行；/* 多行 */
来源：http://dali.wangdashe.top/Article/details/gtmaoqjjqb.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdbiwhhc.html

C#:   // 单行；/* 多行 */
来源：http://dali.ppjwa.cn/Article/details/gtkxzqkmfm.html

[A15] 空值判断与默认值
来源：http://dali.9152youxi.cn/Article/details/gtpqssnfmm.html

Py:   value = data or "默认值"
来源：http://dali.316326.xyz/Article/details/gtpmhzjqdt.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.cqqwz.cn/Article/details/gtdrhlojtg.html


<!-- 参考信息 -->