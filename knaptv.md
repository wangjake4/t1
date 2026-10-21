代发 wailian999

[U93] JS：模板字符串
来源：http://dali.nanxinkj.top/Article/details/gthkzaylho.html

`共 ${n} 条`
来源：http://dali.cheryme.top/Article/details/gtnmrngfyh.html

[U94] JS：箭头函数
来源：http://dali.fengsongda.top/Article/details/gtfnfchequ.html

const double = x => x * 2;
来源：http://dali.316326.xyz/Article/details/gtlkfxofor.html

[U95] JS：Promise 包装
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiaewytgg.html

new Promise((resolve, reject) => {})
来源：http://dali.gotoacloud.top/Article/details/gtztsnxmhn.html

[U96] JS：async/await 与异常
来源：http://dali.hysaishi.cn/Article/details/gttwopxwdv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gthznyjxov.html

[U97] JS：并发请求
来源：http://dali.gotoacloud.top/Article/details/gtezczrebb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gtcwvxgnef.html

[U98] JS：fetch 带 JSON
来源：http://dali.yvedp.cn/Article/details/gtfigvkrbm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.wangdashe.top/Article/details/gtambgrfgx.html

[U99] JS：事件监听
来源：http://dali.aizwys.cn/Article/details/gttyarquzd.html

el.addEventListener("click", e => {})
来源：http://dali.daxiang520.top/Article/details/gtgvivmtrd.html

[U100] JS：DOM 查询
来源：http://dali.jinqigufen.top/Article/details/gtfdtksnna.html

document.querySelector(".item")
来源：http://dali.daria6918.cn/Article/details/gtblttdqjw.html

[U101] JS：classList 操作
来源：http://dali.chenzaomai.com/Article/details/gtxgytbszd.html

el.classList.toggle("active")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlcjwfdyd.html

[U102] JS：本地存储
来源：http://dali.xylfe.cn/Article/details/gtxfotsrmz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.quarkkingdee.top/Article/details/gtzelpifge.html

[U103] JS：定时器
来源：http://dali.hywenlv.cn/Article/details/gtmkxypqal.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cashguo.top/Article/details/gtjpexolcd.html

[U104] JS：防抖
来源：http://dali.fzhhl.top/Article/details/gtejbhompw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtyauhajjo.html

[U105] JS：节流
来源：http://dali.svipenyu.cn/Article/details/gttruitwia.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yuxming.cn/Article/details/gtcanesgqt.html

[U106] JS：日期格式化
来源：http://dali.yvedp.cn/Article/details/gteljxwkqs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.fengsongda.top/Article/details/gtqtbrimkv.html

[U107] JS：数字千分位
来源：http://dali.kuanghao11.cn/Article/details/gtzdvrzckx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gogol.net.cn/Article/details/gtmgavixcy.html

[U108] JS：随机整数
来源：http://dali.andypj.xyz/Article/details/gtbzrcrdlp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhongyouzk.top/Article/details/gtpleiogml.html

[U109] JS：数组分组
来源：http://dali.andypj.xyz/Article/details/gtobzsykcs.html

Object.groupBy(arr, x => x.type)
来源：http://dali.tanke756.top/Article/details/gtujlagvvt.html

[U110] JS：数组分块
来源：http://dali.vqdsnc.cn/Article/details/gtmdzdzuml.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ppjwa.cn/Article/details/gtqdhiprai.html

[U111] JS：对象转 Map
来源：http://dali.ydzc1.top/Article/details/gtjudbemhm.html

new Map(Object.entries(obj))
来源：http://dali.zhongyouzk.top/Article/details/gtdcusxurk.html

[U112] JS：字符串补位
来源：http://dali.redwolf501.top/Article/details/gtsqbsgopn.html

"7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gtlhrsbaqe.html

[U113] JS：正则替换全部
来源：http://dali.aizwys.cn/Article/details/gtopfmqgdd.html

s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtkbslkvvc.html

[U114] JS：JSON 深比较
来源：http://dali.dianchejie.cn/Article/details/gtaxrmrudz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shzxlz.cn/Article/details/gtvdjyohyj.html

[U115] JS：生成 UUID
来源：http://dali.sysykeji.top/Article/details/gtkbxzjgzx.html

crypto.randomUUID()
来源：http://dali.xziqi.cn/Article/details/gtafckccvr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yuanzhike.top/Article/details/gtrflkoltl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ydzc1.top/Article/details/gtirezafyn.html

[U117] JS：单元测试
来源：http://dali.chenlongwang.top/Article/details/gtwbcubovf.html

npm i -D vitest;  npx vitest
来源：http://dali.birdmap.top/Article/details/gthxgtimln.html

[U118] JS：开发服务器
来源：http://dali.yj20258888.top/Article/details/gtyykowaol.html

npm i -D vite;  npx vite
来源：http://dali.hnxiangtu.top/Article/details/gtlscsldul.html

[U119] JS：生产构建
来源：http://dali.yuanzhike.top/Article/details/gtgqkgcfxx.html

npx vite build
来源：http://dali.yj20258.top/Article/details/gtyyzizyit.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.tanke756.top/Article/details/gtujmdyxzh.html

import.meta.env.VITE_API_URL
来源：http://dali.zycfv.cn/Article/details/gtqvxtkpxm.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtdtoyqbql.html

统计汇总
来源：http://dali.wangdashe.top/Article/details/gtkhgiprme.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttinoicob.html

按语言统计（条）：
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqarvtof.html

Python ......... 252
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxpzbwsn.html

PHP ............ 252
来源：http://dali.pycfn.com/Article/details/gthywzddnf.html

JavaScript ..... 252
来源：http://dali.haohaochexian.top/Article/details/gtcmbrvwdh.html

TypeScript ..... 212
来源：http://dali.chenlongwang.top/Article/details/gtbrooswgc.html

Java ........... 212
来源：http://dali.svipenyu.cn/Article/details/gtuezqgdgj.html

Go ............. 212
来源：http://dali.nanxuanxn.top/Article/details/gtoeiqdbsc.html

Ruby ........... 212
来源：http://dali.pycfn.com/Article/details/gtmgjamwdq.html

C# ............. 212
来源：http://dali.gaohongyu789.top/Article/details/gtcnbgzzse.html

C .............. 30
来源：http://dali.tian-w.cn/Article/details/gtqydqcdik.html

C++ ............ 30
来源：http://dali.nanxinkj.top/Article/details/gtbkyyumlj.html

SQL ............ 90
来源：http://dali.zhongyouzk.top/Article/details/gtxompzvyu.html

Bash ........... 80
来源：http://dali.ivvv.top/Article/details/gtddkmxhyd.html

Kotlin ......... 15
来源：http://dali.nwbrower.top/Article/details/gtpiaqargz.html

Swift .......... 15
来源：http://dali.0kj1m.cn/Article/details/gtrnwctbzp.html

Lua ............ 10
来源：http://dali.nanxinkj.top/Article/details/gtghqkhogo.html

Perl ........... 10
来源：http://dali.xinyue.icu/Article/details/gtofwifpht.html

Scala .......... 10
来源：http://dali.ivvv.top/Article/details/gtlfirfuqb.html

------------------------------------
来源：http://dali.tian-w.cn/Article/details/gthlzlswip.html

合计 ........... 2106 条
来源：http://dali.zycfv.cn/Article/details/gtclxpfvtv.html

按章节统计：
来源：http://dali.c1oappe.top/Article/details/gtlyztrejk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yj20258888.top/Article/details/gtvqucmahj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.andypj.xyz/Article/details/gtgnftjujx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gtyvfxmajg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yanxiufei.cn/Article/details/gtiovvbxlb.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yuxming.cn/Article/details/gtbpteghxj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.birdmap.top/Article/details/gtkvwekilk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gtzmxivydk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jiagoushi.top/Article/details/gtgzacavco.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gtevpqsxtx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yvedp.cn/Article/details/gtqmvarnzb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jiagoushi.top/Article/details/gthxpajtur.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gtvanrmokd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gtarcmdwbq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.sufxvd.cn/Article/details/gtwzfrromf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yj20258888.top/Article/details/gtzuaxuynj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gtvlongedq.html

Q SQL 专题                              90
来源：http://dali.birdmap.top/Article/details/gtbawiumaz.html

R Bash 专题                             80
来源：http://dali.jlsjyb.cn/Article/details/gtqxmenvzs.html

S C / C++ 专题                          60
来源：http://dali.yongpay.top/Article/details/gtvehmztqp.html

T 其他语言补充                          60
来源：http://dali.daria6918.cn/Article/details/gtobetimhn.html

U 高频实用片段                         120
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkgfqnbn.html

------------------------------------
来源：http://dali.yuxming.cn/Article/details/gtmyevusqs.html

合计                                  2106 条
来源：http://dali.jlsjyb.cn/Article/details/gtvbigwhcj.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gtwmyxquqp.html

使用提醒
来源：http://dali.cheryme.top/Article/details/gtyhfhwkbd.html

--------------------------------------------------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxdnozut.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xuanzx.com/Article/details/gtnyquvkdn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jinghuilouyu.cn/Article/details/gteklagmhs.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhixingplan.top/Article/details/gtrdwfjalq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.c1oappe.top/Article/details/gtkswoahaw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yj202588.top/Article/details/gtewazznxm.html

—— 文件结束 ——
来源：http://dali.fzhhl.top/Article/details/gtinkcjtdp.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtiirhsuxl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.tianlin.xyz/Article/details/gtichevuhj.html

Common Programming Examples Cheat Book
来源：http://dali.gzhubu.top/Article/details/gtzqfzkdsr.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtuumcarnw.html

【收录内容】
来源：http://dali.hongshengwenyu.top/Article/details/gtctpmxymt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvgpsmuc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yuanzhike.top/Article/details/gtvwbfhloo.html

SQL · Bash · C · C++
来源：http://dali.gogol.net.cn/Article/details/gtgcezbapp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.iojbl.cn/Article/details/gttzrwjbrc.html

【使用说明】
来源：http://dali.c1oappe.top/Article/details/gtfwxbgbvv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.9152youxi.cn/Article/details/gtmjjmucfy.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.guannengcc.top/Article/details/gtokdlrlcn.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.sysykeji.top/Article/details/gtalnqjbbf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hammf.cn/Article/details/gttmnzajsj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.aizwys.cn/Article/details/gtvbqfkzry.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenjidiqi.icu/Article/details/gtfuucpfxr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.ehwqpu.com/Article/details/gtyvkdsqih.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.andypj.xyz/Article/details/gtqdqutger.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.vqdsnc.cn/Article/details/gtbgchnmko.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwihanjts.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.sxryk.cn/Article/details/gtyupbyqux.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.aibaodan.cn/Article/details/gtlkeyhtnj.html

【文件统计】
来源：http://dali.mhx1999.top/Article/details/gtycgzxbsr.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.quarkkingdee.top/Article/details/gtbehrqdfj.html

--------------------------------------------------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvswrngmf.html

目  录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbejllbnj.html

--------------------------------------------------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gtqsvmplai.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ivvv.top/Article/details/gtbmdnhkry.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.cucudq.cn/Article/details/gttmexqtah.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdrxymhx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.redwolf501.top/Article/details/gtqsnukkkt.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.0kj1m.cn/Article/details/gtumlvewql.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yuxming.cn/Article/details/gtzrxnrdov.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.316326.xyz/Article/details/gtqivrimvs.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jianghu66.top/Article/details/gttjtoudhc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.wangdashe.top/Article/details/gtohkrstgw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yj20258888.top/Article/details/gtexcpxzqu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yj20258888.top/Article/details/gtgzrmmguj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtgazbvcky.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.sysykeji.top/Article/details/gtxigblbaf.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jqgfzy.top/Article/details/gtssanmmyw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shuidangran.top/Article/details/gteompuclq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.gaohongyu789.top/Article/details/gtoztrzkmx.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.316326.xyz/Article/details/gtqqzogyub.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jqgfzy.top/Article/details/gttwnmodge.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xuanzx.com/Article/details/gtkcsrmnrt.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfhynjpjj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtdmiyqbyc.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtprlnnsot.html

A. 基础语法与类型
来源：http://dali.chenlongwang.top/Article/details/gtoxzcjqfu.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtvxecehyi.html

[A01] Hello World
来源：http://dali.cheryme.top/Article/details/gtqkppqbfv.html

Py:   print("Hello, World!")
来源：http://dali.birdmap.top/Article/details/gtobwkvyqt.html

PHP:  echo "Hello, World!";
来源：http://dali.xinyue.icu/Article/details/gtogmjsdky.html

JS:   console.log("Hello, World!");
来源：http://dali.nanxuanxn.top/Article/details/gtelcjeekx.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.sxryk.cn/Article/details/gttczpavsh.html

Java: System.out.println("Hello, World!");
来源：http://dali.jlsjyb.cn/Article/details/gtlzdqmxtj.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hongshengwenyu.top/Article/details/gtrtsenqqw.html

Ruby: puts "Hello, World!"
来源：http://dali.bjfxy.top/Article/details/gtfposyiqs.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.dianchejie.cn/Article/details/gtxhxbmbmj.html

[A02] 变量声明与赋值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkgacywbw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvzpkglr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.9152youxi.cn/Article/details/gtlbqcxedy.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gtmwzlywmo.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yvedp.cn/Article/details/gtfirzzfky.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.wangdashe.top/Article/details/gtphddrwjf.html

Go:   name := "Alex"; age := 20
来源：http://dali.hywenlv.cn/Article/details/gtltnuqoko.html

Ruby: name = "Alex"; age = 20
来源：http://dali.shuidangran.top/Article/details/gtgovsxkel.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zdqjudy.top/Article/details/gtdjxavrob.html

[A03] 常量定义
来源：http://dali.hnxiangtu.top/Article/details/gtzgybpkyl.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.mhx1999.top/Article/details/gtclfanufo.html

PHP:  const PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtrkoqrxtp.html

JS:   const PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtiivujrhk.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtliqsbmyp.html

Java: static final double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtspigehpj.html

Go:   const PI = 3.14159
来源：http://dali.guannengcc.top/Article/details/gthknkzmuw.html

Ruby: PI = 3.14159
来源：http://dali.redwolf501.top/Article/details/gtcjptyrga.html

C#:   const double PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtanvqanul.html

[A04] 判断变量类型
来源：http://dali.zhengqikj.top/Article/details/gtgufshmap.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.shanyushiyangtech.top/Article/details/gthjkhdivb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jyoumei.cn/Article/details/gtbzyxxkmj.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.gzhubu.top/Article/details/gtrvaeipqy.html

TS:   typeof x; x instanceof Date
来源：http://dali.yueranfly.top/Article/details/gtvvablzgb.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqljzgjo.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hysaishi.cn/Article/details/gtzyjjuazn.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.sweek.top/Article/details/gtmgljkxkq.html

C#:   x.GetType().Name; x is int
来源：http://dali.yj202588.top/Article/details/gtbyeeahqr.html

[A05] 整数除法与取模
来源：http://dali.zycfv.cn/Article/details/gtgyxzikvm.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.c1oappe.top/Article/details/gtpmgmzynn.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtqqcpbvrm.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gtcuykijxt.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gtpaedchmv.html

Java: 7 / 2; 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gtiruigrtv.html

Go:   7 / 2; 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gtagajfzun.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gtrzohodmd.html

C#:   7 / 2; 7 % 2
来源：http://dali.ydzc1.top/Article/details/gtzbzluiqr.html

[A06] 字符串转数字
来源：http://dali.gotoacloud.top/Article/details/gtnelfnoer.html

Py:   int("42"); float("3.14")
来源：http://dali.wangshuangyany.cn/Article/details/gtbyvcrfla.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.haohaochexian.top/Article/details/gtrtyhpiyw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwotyasav.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.chenlongwang.top/Article/details/gttdjvibkz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cdnleiting.top/Article/details/gtxungrlio.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yj202588.top/Article/details/gtlryqwtre.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhengqikj.top/Article/details/gtqcditdks.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zycfv.cn/Article/details/gtrobyyyjj.html

[A07] 数字转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtnxswkwqj.html

Py:   str(42)
来源：http://dali.ppjwa.cn/Article/details/gtlbyxvoas.html

PHP:  (string) 42; strval(42)
来源：http://dali.c1oappe.top/Article/details/gtinmcqbou.html

JS:   String(42); (42).toString()
来源：http://dali.jlsjyb.cn/Article/details/gtntmwdtoa.html

TS:   String(42)
来源：http://dali.svipenyu.cn/Article/details/gtrihdplsx.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.chenzaomai.com/Article/details/gtxwsnjdbr.html

Go:   strconv.Itoa(42)
来源：http://dali.pycfn.com/Article/details/gtragxrdob.html

Ruby: 42.to_s
来源：http://dali.yonumen.top/Article/details/gtgnzllasw.html

C#:   42.ToString()
来源：http://dali.fzhhl.top/Article/details/gtgsqofthb.html

[A08] 取整与四舍五入
来源：http://dali.hnqzz.top/Article/details/gtptyvwnre.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.cdnleiting.top/Article/details/gteccyvbee.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yanxiufei.cn/Article/details/gtydigfrjx.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.sysykeji.top/Article/details/gtrtqzlgcz.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkftkwnb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjfrfkgx.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.fengsongda.top/Article/details/gtqvmgekhc.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.bjfxy.top/Article/details/gtemhrwuan.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.redwolf501.top/Article/details/gtwcikpywy.html

[A09] 绝对值与最大最小值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtceddrsde.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gtpcgszjpw.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtfienolam.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbpvtgysw.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gtfjtrwxyz.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtfxrovpgp.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhixingplan.top/Article/details/gtdpacuofl.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.gogol.net.cn/Article/details/gtpgkdqluf.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.cheryme.top/Article/details/gtqkkrbshe.html

[A10] 生成随机数
来源：http://dali.mhx1999.top/Article/details/gtqndowjfu.html

Py:   import random; random.randint(1, 100)
来源：http://dali.birdmap.top/Article/details/gtnllumysk.html

PHP:  random_int(1, 100);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcburcjn.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.tianlin.xyz/Article/details/gtvvkvagts.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yangfankeji.com/Article/details/gtsdqjulbe.html

Java: new Random().nextInt(100) + 1
来源：http://dali.cheryme.top/Article/details/gtxbjvival.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkdsznac.html

Ruby: rand(1..100)
来源：http://dali.fzhhl.top/Article/details/gtjsjkdutn.html

C#:   new Random().Next(1, 101)
来源：http://dali.sufxvd.cn/Article/details/gtbxcnzjsl.html

[A11] 条件表达式（三元）
来源：http://dali.jianghu66.top/Article/details/gtfofgbbvz.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.chenlongwang.top/Article/details/gtclyhpaev.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.c1oappe.top/Article/details/gtkthorlqm.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.cqqwz.cn/Article/details/gtbehbnyny.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtepozsoqi.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jqgufenzy.top/Article/details/gtllgivdba.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.snrcjt.cn/Article/details/gtjaalzvnm.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yuanzhike.top/Article/details/gtttthucyh.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.c1oappe.top/Article/details/gtswtlycie.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhiwuduotai.top/Article/details/gttvwfglbu.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.ppjwa.cn/Article/details/gtkeeuzbgx.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yj20258888.top/Article/details/gtfgwdeqnw.html

JS:   `Hello, ${name}!`
来源：http://dali.cucudq.cn/Article/details/gtnjnhptdf.html

TS:   `Hello, ${name}!`
来源：http://dali.redwolf501.top/Article/details/gtpofstcmb.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.hongshengwenyu.top/Article/details/gtutzbfkpa.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.hongshengwenyu.top/Article/details/gttmorrasf.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhengqikj.top/Article/details/gtsjkgumzw.html

C#:   $"Hello, {name}!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgatckqu.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.gaohongyu789.top/Article/details/gtkuyozykt.html

Py:   "第一行\n第二行"
来源：http://dali.tanke756.top/Article/details/gtcizukven.html

PHP:  "第一行\n第二行"
来源：http://dali.cdnleiting.top/Article/details/gtkzxoffrc.html

JS:   "第一行\n第二行"
来源：http://dali.cdnleiting.top/Article/details/gticwopclj.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gtmgngdbax.html

Java: "第一行\n第二行"
来源：http://dali.jinqigfzy.top/Article/details/gtybcqgpdj.html

Go:   "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gtxmbjippb.html

Ruby: "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gtgkblnilw.html

C#:   "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gtjdmvnkco.html

[A14] 注释写法
来源：http://dali.iojbl.cn/Article/details/gthoxbfjak.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.ybcxt.top/Article/details/gtpafgecgn.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jqgfzy.top/Article/details/gtnorrvqhr.html

JS:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudgkgndu.html

TS:   // 单行；/* 多行 */
来源：http://dali.pengpengdd.cyou/Article/details/gtrobjnwje.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.tianlin.xyz/Article/details/gtiqtjjale.html

Go:   // 单行；/* 多行 */
来源：http://dali.yanxiufei.cn/Article/details/gtvfsiadql.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.shanyushiyangtech.top/Article/details/gtrynbdmey.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhoulong.xyz/Article/details/gtuqdvhzqs.html

[A15] 空值判断与默认值
来源：http://dali.yuanzhike.top/Article/details/gtaoyzmamq.html

Py:   value = data or "默认值"
来源：http://dali.chenlongwang.top/Article/details/gtmaczkbro.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.nwbrower.top/Article/details/gtuxzntdxn.html

JS:   const value = data ?? "默认值";
来源：http://dali.nanxinkj.top/Article/details/gtrgitnhmt.html

TS:   const value = data ?? "默认值";
来源：http://dali.yanxiufei.cn/Article/details/gtnsttopou.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.redwolf501.top/Article/details/gtpigsbmce.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shzxlz.cn/Article/details/gtnsbdrbda.html

Ruby: value = data || "默认值"
来源：http://dali.zhongyouzk.top/Article/details/gtqcvxygbm.html

C#:   var value = data ?? "默认值";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxihozaq.html

[A16] 真假值判断规则
来源：http://dali.yongpay.top/Article/details/gtbrfggslw.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.havefunace.top/Article/details/gtsmsmrkkt.html


<!-- 参考信息 -->