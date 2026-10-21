代发 wailian999

[U93] JS：模板字符串
来源：http://dali.xylfe.cn/Article/details/gtvxlyqnrp.html

`共 ${n} 条`
来源：http://dali.nanxuanxn.top/Article/details/gtmdlvqerz.html

[U94] JS：箭头函数
来源：http://dali.ehwqpu.com/Article/details/gtimswlsrf.html

const double = x => x * 2;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnizvplcy.html

[U95] JS：Promise 包装
来源：http://dali.chenzaomai.com/Article/details/gtadscutgj.html

new Promise((resolve, reject) => {})
来源：http://dali.chenzaomai.com/Article/details/gtawopwkvq.html

[U96] JS：async/await 与异常
来源：http://dali.gotoacloud.top/Article/details/gtmtictbxi.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxmrylvl.html

[U97] JS：并发请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjaeuefzl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gtofohsklh.html

[U98] JS：fetch 带 JSON
来源：http://dali.jqgufenzy.top/Article/details/gtfeaqgyim.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.svipenyu.cn/Article/details/gtmrbnhjgx.html

[U99] JS：事件监听
来源：http://dali.tianlin.xyz/Article/details/gtkbsvsual.html

el.addEventListener("click", e => {})
来源：http://dali.yuanzhike.top/Article/details/gtbxdukpuh.html

[U100] JS：DOM 查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefegodiz.html

document.querySelector(".item")
来源：http://dali.sweek.top/Article/details/gtlwawqdry.html

[U101] JS：classList 操作
来源：http://dali.bjfxy.top/Article/details/gtyuogqryg.html

el.classList.toggle("active")
来源：http://dali.hywenlv.cn/Article/details/gtyzwxsqyv.html

[U102] JS：本地存储
来源：http://dali.xuetiantiany.cn/Article/details/gtaputrsaa.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.gaohongyu789.top/Article/details/gtcurhinsf.html

[U103] JS：定时器
来源：http://dali.sysykeji.top/Article/details/gtahauomqw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hysaishi.cn/Article/details/gtkmjnevtx.html

[U104] JS：防抖
来源：http://dali.gzhubu.top/Article/details/gtqtqaaiqs.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gtlefbzvod.html

[U105] JS：节流
来源：http://dali.zhixingplan.top/Article/details/gtavwztkqc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhengqikj.top/Article/details/gtneezyazi.html

[U106] JS：日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gthijzvogo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.guannengcc.top/Article/details/gtdbebnlzt.html

[U107] JS：数字千分位
来源：http://dali.guannengcc.top/Article/details/gtftnxlpyb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ivvv.top/Article/details/gtfdhljjzz.html

[U108] JS：随机整数
来源：http://dali.meibo888.top/Article/details/gtiqeirslv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.pycfn.com/Article/details/gteddynsvs.html

[U109] JS：数组分组
来源：http://dali.hnqzz.top/Article/details/gtxrzuxkvv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cucudq.cn/Article/details/gtalkxiulk.html

[U110] JS：数组分块
来源：http://dali.yuxming.cn/Article/details/gtfbxonzli.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sufxvd.cn/Article/details/gtmfwyclhn.html

[U111] JS：对象转 Map
来源：http://dali.nanxuanxn.top/Article/details/gtemonlnzs.html

new Map(Object.entries(obj))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyuruvly.html

[U112] JS：字符串补位
来源：http://dali.iojbl.cn/Article/details/gtjikpmbar.html

"7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtycivcuut.html

[U113] JS：正则替换全部
来源：http://dali.tanke756.top/Article/details/gtsilpzcwb.html

s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gthizbfyis.html

[U114] JS：JSON 深比较
来源：http://dali.dashuyun.cn/Article/details/gtexigsdtm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigfzy.top/Article/details/gteftoqoof.html

[U115] JS：生成 UUID
来源：http://dali.hnxiangtu.top/Article/details/gtglzfpsiw.html

crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtvndxmdpc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zdqjudy.top/Article/details/gtzsanybwj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hywenlv.cn/Article/details/gtlwuiydcc.html

[U117] JS：单元测试
来源：http://dali.daxiang520.top/Article/details/gtamltwgms.html

npm i -D vitest;  npx vitest
来源：http://dali.aizwys.cn/Article/details/gtxqaydhnl.html

[U118] JS：开发服务器
来源：http://dali.hnxiangtu.top/Article/details/gtilitarmr.html

npm i -D vite;  npx vite
来源：http://dali.jlsjyb.cn/Article/details/gtnoncponf.html

[U119] JS：生产构建
来源：http://dali.bjfxy.top/Article/details/gtkuxxqdvi.html

npx vite build
来源：http://dali.ivvv.top/Article/details/gtubymaerk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhengqikj.top/Article/details/gtzgqgwugd.html

import.meta.env.VITE_API_URL
来源：http://dali.mhx1999.top/Article/details/gtbvqmdpzp.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gteguyamsr.html

统计汇总
来源：http://dali.xylfe.cn/Article/details/gtyuajdzor.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtipairvsy.html

按语言统计（条）：
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwconpcr.html

Python ......... 252
来源：http://dali.xuanzx.com/Article/details/gtxpovehla.html

PHP ............ 252
来源：http://dali.zhiwuduotai.top/Article/details/gtkpjqcrdc.html

JavaScript ..... 252
来源：http://dali.gotoacloud.top/Article/details/gtofqotigr.html

TypeScript ..... 212
来源：http://dali.aizwys.cn/Article/details/gtvdfhpvdc.html

Java ........... 212
来源：http://dali.cqqwz.cn/Article/details/gtpghzrygp.html

Go ............. 212
来源：http://dali.jianghu66.top/Article/details/gttnzztegv.html

Ruby ........... 212
来源：http://dali.shzxlz.cn/Article/details/gtfhvdmfkp.html

C# ............. 212
来源：http://dali.jiagoushi.top/Article/details/gtzxaywxok.html

C .............. 30
来源：http://dali.chenjidiqi.icu/Article/details/gtynhgyety.html

C++ ............ 30
来源：http://dali.aibaodan.cn/Article/details/gtrltyunkr.html

SQL ............ 90
来源：http://dali.hnqzz.top/Article/details/gtsbosgfrb.html

Bash ........... 80
来源：http://dali.yuxming.cn/Article/details/gtfsvnqitg.html

Kotlin ......... 15
来源：http://dali.zhongyouzk.top/Article/details/gtquuzwohr.html

Swift .......... 15
来源：http://dali.yj20258.top/Article/details/gtwkhlfqqv.html

Lua ............ 10
来源：http://dali.cashguo.top/Article/details/gttkifmemh.html

Perl ........... 10
来源：http://dali.yvedp.cn/Article/details/gtqekjalgk.html

Scala .......... 10
来源：http://dali.yongpay.top/Article/details/gtlykdlevt.html

------------------------------------
来源：http://dali.cashguo.top/Article/details/gtntngsege.html

合计 ........... 2106 条
来源：http://dali.vqdsnc.cn/Article/details/gtrdsvkawz.html

按章节统计：
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipvavoyz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shzxlz.cn/Article/details/gtzpynfdyv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhengqikj.top/Article/details/gtidgwzzlt.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ehwqpu.com/Article/details/gtxgdqfzwx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.c1oappe.top/Article/details/gtshfxnvdk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yj20258888.top/Article/details/gteyfkatie.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yuxming.cn/Article/details/gtynexydmv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yj202588.top/Article/details/gttdqrqmvi.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.gogol.net.cn/Article/details/gtrsharnut.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gtrepgihtk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cucudq.cn/Article/details/gtdonfsiby.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqwaxmcq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zdqjudy.top/Article/details/gtrbprbkvr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gtxbvbpaic.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cashguo.top/Article/details/gtdcpldblx.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shanyushiyangkeji.top/Article/details/gtekhblwwb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gtcvlxujmi.html

Q SQL 专题                              90
来源：http://dali.havefunace.top/Article/details/gttnysiuhs.html

R Bash 专题                             80
来源：http://dali.yueranfly.top/Article/details/gttllvelsi.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gtfrdrngxx.html

T 其他语言补充                          60
来源：http://dali.hnqzz.top/Article/details/gtekxvpapa.html

U 高频实用片段                         120
来源：http://dali.gzhubu.top/Article/details/gteeanthcg.html

------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gtksouzmvc.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gtziaezlqs.html

--------------------------------------------------------------------------------
来源：http://dali.xziqi.cn/Article/details/gtmqxpkhjy.html

使用提醒
来源：http://dali.havefunace.top/Article/details/gtomxsoxzn.html

--------------------------------------------------------------------------------
来源：http://dali.xinyue.icu/Article/details/gtdliyrtjm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.316326.xyz/Article/details/gtrhchiaex.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hammf.cn/Article/details/gtqbttijha.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.tianlin.xyz/Article/details/gtuqlsgqvw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.sysykeji.top/Article/details/gtinyxidxk.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xuetiantiany.cn/Article/details/gtpoespmny.html

—— 文件结束 ——
来源：http://dali.hfpthk.cn/Article/details/gtawowsjgp.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtgerlawwi.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.snrcjt.cn/Article/details/gteovactdy.html

Common Programming Examples Cheat Book
来源：http://dali.yuxming.cn/Article/details/gtvuutvycg.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtzezuqhrl.html

【收录内容】
来源：http://dali.cdnleiting.top/Article/details/gtkwelylyb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.9152youxi.cn/Article/details/gttgdfhvrs.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.pycfn.com/Article/details/gtojfgaufa.html

SQL · Bash · C · C++
来源：http://dali.jqgfzy.top/Article/details/gtguvoklnd.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.nanxuanxn.top/Article/details/gtnvnbopwj.html

【使用说明】
来源：http://dali.dianchejie.cn/Article/details/gtduivlkqy.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.iojbl.cn/Article/details/gthtbxvlsd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.smart0.xyz/Article/details/gttdutmzot.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yj20258.top/Article/details/gtzbnujeon.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yangfankeji.com/Article/details/gtkrgfgndv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.bjfxy.top/Article/details/gthjlksnms.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhixingplan.top/Article/details/gtbdxmkrxp.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.shzxlz.cn/Article/details/gthfscogth.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.tanke756.top/Article/details/gtlvfygsxm.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.0kj1m.cn/Article/details/gtsxsaltfn.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.sweek.top/Article/details/gtkguuictx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hywenlv.cn/Article/details/gtmdmabgux.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.shanyushiyangtech.top/Article/details/gtopqrltto.html

【文件统计】
来源：http://dali.0kj1m.cn/Article/details/gtjzpupxgy.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hnxiangtu.top/Article/details/gtbizwyitm.html

--------------------------------------------------------------------------------
来源：http://dali.sweek.top/Article/details/gtmrhywgek.html

目  录
来源：http://dali.ybcxt.top/Article/details/gtaqwdebkr.html

--------------------------------------------------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gtcwpyivhf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xuanzx.com/Article/details/gttmktbxgm.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.sysykeji.top/Article/details/gtnnrjqsrr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.nwbrower.top/Article/details/gtaevnjxlh.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xziqi.cn/Article/details/gtglgiispl.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.mhx1999.top/Article/details/gtnwepqfcg.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.iojbl.cn/Article/details/gtzulfdswn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.nanxinkj.top/Article/details/gtnetbgcwe.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.cashguo.top/Article/details/gthanmmaai.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.fengsongda.top/Article/details/gtbjbolkij.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtrpnwypsl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhoulong.xyz/Article/details/gtaaoudnlm.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.shzxlz.cn/Article/details/gtwzxbbgzs.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gtwjcgbhkd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xuanzx.com/Article/details/gthwxdwcap.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yvedp.cn/Article/details/gtmjxkydtr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.0kj1m.cn/Article/details/gtytkoeruf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.sufxvd.cn/Article/details/gtunaagqwj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.vqdsnc.cn/Article/details/gttvolmdqu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xuanzx.com/Article/details/gtizklmnqg.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.birdmap.top/Article/details/gtwvnlxjny.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sysykeji.top/Article/details/gtufjiqcaz.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtvkafanwr.html

A. 基础语法与类型
来源：http://dali.jinqigufen.top/Article/details/gtwiffjndj.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtbftokosl.html

[A01] Hello World
来源：http://dali.jianghu66.top/Article/details/gtrbbdswtx.html

Py:   print("Hello, World!")
来源：http://dali.ydzc1.top/Article/details/gtvdgscfwh.html

PHP:  echo "Hello, World!";
来源：http://dali.ybcxt.top/Article/details/gtfybcofgw.html

JS:   console.log("Hello, World!");
来源：http://dali.sxryk.cn/Article/details/gtmrxwiqot.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jiagoushi.top/Article/details/gtvkabvukc.html

Java: System.out.println("Hello, World!");
来源：http://dali.dianchejie.cn/Article/details/gtswxmwitb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jqgfzy.top/Article/details/gtidmndqcd.html

Ruby: puts "Hello, World!"
来源：http://dali.jqgfzy.top/Article/details/gtcjrujrlc.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.nwbrower.top/Article/details/gthhewgwgd.html

[A02] 变量声明与赋值
来源：http://dali.0kj1m.cn/Article/details/gtzubjrdxs.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.tanke756.top/Article/details/gtrnjqjmhj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.shangyingyoupin.top/Article/details/gteolxkuov.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.0kj1m.cn/Article/details/gtxnfgtrtw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jinqigufen.top/Article/details/gthezdqhfe.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.sysykeji.top/Article/details/gtxccvavew.html

Go:   name := "Alex"; age := 20
来源：http://dali.mhx1999.top/Article/details/gtpzkovlip.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hnxiangtu.top/Article/details/gttwavcwhw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.pycfn.com/Article/details/gtwrwapcfc.html

[A03] 常量定义
来源：http://dali.jinqigufen.top/Article/details/gtgaibvzpr.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.iojbl.cn/Article/details/gthpdsmibo.html

PHP:  const PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtnhqjqkkq.html

JS:   const PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtxvkyvogl.html

TS:   const PI: number = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gthnhzrldu.html

Java: static final double PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtizgyjueb.html

Go:   const PI = 3.14159
来源：http://dali.ehwqpu.com/Article/details/gtuujmdqgv.html

Ruby: PI = 3.14159
来源：http://dali.pengpengdd.cyou/Article/details/gtxoapdirm.html

C#:   const double PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtzmplxkcr.html

[A04] 判断变量类型
来源：http://dali.cucudq.cn/Article/details/gtldfcqeae.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.bjfxy.top/Article/details/gtvttmiqlb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jinqigfzy.top/Article/details/gtcihtgiyu.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.pycfn.com/Article/details/gtlbaypgta.html

TS:   typeof x; x instanceof Date
来源：http://dali.pengpengdd.cyou/Article/details/gtypnmmlxa.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hnqzz.top/Article/details/gtyzokuwkn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.smart0.xyz/Article/details/gtgnrzgafy.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jqgufenzy.top/Article/details/gtszasfexh.html

C#:   x.GetType().Name; x is int
来源：http://dali.daxiang520.top/Article/details/gtelsthknl.html

[A05] 整数除法与取模
来源：http://dali.havefunace.top/Article/details/gtjyqwxdcr.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yanxiufei.cn/Article/details/gtujstuawv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabrydwfo.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gtisvhoclr.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tanke756.top/Article/details/gtunlpjwak.html

Java: 7 / 2; 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gtwqowjale.html

Go:   7 / 2; 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtigevgqen.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ybcxt.top/Article/details/gtfkpykzwv.html

C#:   7 / 2; 7 % 2
来源：http://dali.316326.xyz/Article/details/gtaxwwdanb.html

[A06] 字符串转数字
来源：http://dali.chenlongwang.top/Article/details/gtpvahdobx.html

Py:   int("42"); float("3.14")
来源：http://dali.svipenyu.cn/Article/details/gttoxygquf.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.smart0.xyz/Article/details/gttulckzgf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnycahznp.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.dashuyun.cn/Article/details/gtpwbnzpjp.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.hongshengwenyu.top/Article/details/gtkktsoxwt.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jlsjyb.cn/Article/details/gtnwnkwwdb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.pengpengdd.cyou/Article/details/gtdjugtxch.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gtmymdqfsn.html

[A07] 数字转字符串
来源：http://dali.guannengcc.top/Article/details/gtjldcqfai.html

Py:   str(42)
来源：http://dali.dashuyun.cn/Article/details/gtqxlmwelr.html

PHP:  (string) 42; strval(42)
来源：http://dali.pycfn.com/Article/details/gtwuvahevj.html

JS:   String(42); (42).toString()
来源：http://dali.aizwys.cn/Article/details/gtwlvucrez.html

TS:   String(42)
来源：http://dali.kuanghao11.cn/Article/details/gtbvqwvzfk.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.haohaochexian.top/Article/details/gtnprsgfay.html

Go:   strconv.Itoa(42)
来源：http://dali.yonumen.top/Article/details/gtwxtpepvc.html

Ruby: 42.to_s
来源：http://dali.chenlongwang.top/Article/details/gtvgxnhmij.html

C#:   42.ToString()
来源：http://dali.fengsongda.top/Article/details/gtqeuxcwbf.html

[A08] 取整与四舍五入
来源：http://dali.xziqi.cn/Article/details/gteodwgjsb.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.cdnleiting.top/Article/details/gttvsfglrn.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.feifeiyinyue.top/Article/details/gtncduxekf.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.vqdsnc.cn/Article/details/gttogtimso.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zycfv.cn/Article/details/gtcmrzaouy.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.cheryme.top/Article/details/gtuidinxxo.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.pengpengdd.cyou/Article/details/gtlnodnqvr.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.birdmap.top/Article/details/gtdwhbwidf.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.wangshuangyany.cn/Article/details/gtodwpuntp.html

[A09] 绝对值与最大最小值
来源：http://dali.zhixingplan.top/Article/details/gtoqiwxxil.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gtevevktks.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gtxolsmoqf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gtwtycfpqx.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.xinyue.icu/Article/details/gtyogtrfrl.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gtbxlcreoq.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.cheryme.top/Article/details/gtwdevjgxv.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.ivvv.top/Article/details/gtbgjnxgue.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gtswblovtt.html

[A10] 生成随机数
来源：http://dali.gotoacloud.top/Article/details/gtvjyzffrj.html

Py:   import random; random.randint(1, 100)
来源：http://dali.smart0.xyz/Article/details/gtwuxmydto.html

PHP:  random_int(1, 100);
来源：http://dali.daxiang520.top/Article/details/gtumgwtobo.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jqgufenzy.top/Article/details/gtgikxhjpu.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.daxiang520.top/Article/details/gtyhdsnncj.html

Java: new Random().nextInt(100) + 1
来源：http://dali.cheryme.top/Article/details/gttfciprpy.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jlsjyb.cn/Article/details/gtcqqndswp.html

Ruby: rand(1..100)
来源：http://dali.yj20258888.top/Article/details/gtfejmymxk.html

C#:   new Random().Next(1, 101)
来源：http://dali.daxiang520.top/Article/details/gtrldfacsf.html

[A11] 条件表达式（三元）
来源：http://dali.ivvv.top/Article/details/gtvkgcephe.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.pycfn.com/Article/details/gtcaekcltd.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.cashguo.top/Article/details/gtxyygzopd.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.hysaishi.cn/Article/details/gtrogvfvad.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gtmfdxjffx.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.dashuyun.cn/Article/details/gtpmmjajgy.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.daxiang520.top/Article/details/gtdshqeplj.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.redwolf501.top/Article/details/gtvvvifdhv.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yvedp.cn/Article/details/gtkbwyzdgs.html

[A12] 字符串插值 / 格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvuxxquuo.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.gotoacloud.top/Article/details/gtrzjoutvl.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.hfpthk.cn/Article/details/gtstyoyhub.html

JS:   `Hello, ${name}!`
来源：http://dali.sufxvd.cn/Article/details/gtcekmkqwx.html

TS:   `Hello, ${name}!`
来源：http://dali.iojbl.cn/Article/details/gtwrllozew.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.ybcxt.top/Article/details/gtwfxeukes.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.nanxuanxn.top/Article/details/gtiepjborm.html

Ruby: "Hello, #{name}!"
来源：http://dali.smart0.xyz/Article/details/gtfzynuzpl.html

C#:   $"Hello, {name}!"
来源：http://dali.vqdsnc.cn/Article/details/gtqjhwwlhy.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.ppjwa.cn/Article/details/gtynkxfzjh.html

Py:   "第一行\n第二行"
来源：http://dali.haohaochexian.top/Article/details/gtyfflrygy.html

PHP:  "第一行\n第二行"
来源：http://dali.zhongyouzk.top/Article/details/gtyrktuvnh.html

JS:   "第一行\n第二行"
来源：http://dali.mhx1999.top/Article/details/gtzaiqtmfj.html

TS:   "第一行\n第二行"
来源：http://dali.daria6918.cn/Article/details/gtskrrzkca.html

Java: "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gtldiawtsn.html

Go:   "第一行\n第二行"
来源：http://dali.ppjwa.cn/Article/details/gtfjfsojpe.html

Ruby: "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gtvzdaiaff.html

C#:   "第一行\n第二行"
来源：http://dali.sxryk.cn/Article/details/gtkomyrkrk.html

[A14] 注释写法
来源：http://dali.quarkkingdee.top/Article/details/gtfftgrrqj.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.chenjidiqi.icu/Article/details/gtlxkmuzkp.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.ivvv.top/Article/details/gtujrvlfcs.html

JS:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangtech.top/Article/details/gtopxfcogv.html

TS:   // 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gtceyvndvw.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.quarkkingdee.top/Article/details/gtqjharjtk.html

Go:   // 单行；/* 多行 */
来源：http://dali.0kj1m.cn/Article/details/gthutsisoc.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.daria6918.cn/Article/details/gttgmflseg.html

C#:   // 单行；/* 多行 */
来源：http://dali.daxiang520.top/Article/details/gtzacfczdj.html

[A15] 空值判断与默认值
来源：http://dali.sysykeji.top/Article/details/gtbriqhjkq.html

Py:   value = data or "默认值"
来源：http://dali.ivvv.top/Article/details/gtusqhragc.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.vqdsnc.cn/Article/details/gtyofbwejc.html

JS:   const value = data ?? "默认值";
来源：http://dali.redwolf501.top/Article/details/gtrwejtccg.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gtsncifhbe.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.hysaishi.cn/Article/details/gtxefezugf.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.xziqi.cn/Article/details/gtpkjtswxu.html

Ruby: value = data || "默认值"
来源：http://dali.jqgfzy.top/Article/details/gtnggnpnfn.html

C#:   var value = data ?? "默认值";
来源：http://dali.hfpthk.cn/Article/details/gtpmzxwzho.html

[A16] 真假值判断规则
来源：http://dali.yueranfly.top/Article/details/gtgzvnkrkw.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.pycfn.com/Article/details/gtjivlrifd.html


<!-- 参考信息 -->