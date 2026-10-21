代发 wailian999

[U93] JS：模板字符串
来源：http://dali.cheryme.top/Article/details/gtqzrsgwfz.html

`共 ${n} 条`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmbymlzy.html

[U94] JS：箭头函数
来源：http://dali.shangyingyoupin.top/Article/details/gtrznomktv.html

const double = x => x * 2;
来源：http://dali.ivvv.top/Article/details/gtxujuiodu.html

[U95] JS：Promise 包装
来源：http://dali.haohaochexian.top/Article/details/gtpgnapeyi.html

new Promise((resolve, reject) => {})
来源：http://dali.gotoacloud.top/Article/details/gtmtkuczxs.html

[U96] JS：async/await 与异常
来源：http://dali.gzhubu.top/Article/details/gtdltueyrk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gtjyqbzxeu.html

[U97] JS：并发请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlzczhkv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gtsmxqtjqy.html

[U98] JS：fetch 带 JSON
来源：http://dali.daxiang520.top/Article/details/gtsrnhsoce.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.0kj1m.cn/Article/details/gtmotgdmra.html

[U99] JS：事件监听
来源：http://dali.smart0.xyz/Article/details/gtyqeycvgi.html

el.addEventListener("click", e => {})
来源：http://dali.bjfxy.top/Article/details/gtdtizpwqq.html

[U100] JS：DOM 查询
来源：http://dali.jiagoushi.top/Article/details/gtzdunwead.html

document.querySelector(".item")
来源：http://dali.zhixingplan.top/Article/details/gteaiqrcmv.html

[U101] JS：classList 操作
来源：http://dali.hnqzz.top/Article/details/gtqadodnln.html

el.classList.toggle("active")
来源：http://dali.shzxlz.cn/Article/details/gtapozytuc.html

[U102] JS：本地存储
来源：http://dali.guannengcc.top/Article/details/gtqkhufhsa.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.tianlin.xyz/Article/details/gtjvicbfqi.html

[U103] JS：定时器
来源：http://dali.tian-w.cn/Article/details/gtolzpmcsx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.redwolf501.top/Article/details/gtugtammzz.html

[U104] JS：防抖
来源：http://dali.wangdashe.top/Article/details/gtroaoolnf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gtwjoobrai.html

[U105] JS：节流
来源：http://dali.feifeiyinyue.top/Article/details/gtczlxmuzp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yonumen.top/Article/details/gtdvayxgzd.html

[U106] JS：日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpqyjbeyg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hongshengwenyu.top/Article/details/gtelbvuiyg.html

[U107] JS：数字千分位
来源：http://dali.zdqjudy.top/Article/details/gtxtqarymd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cashguo.top/Article/details/gtbquxvyhc.html

[U108] JS：随机整数
来源：http://dali.chenlongwang.top/Article/details/gtkmyjrhwx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hongshengwenyu.top/Article/details/gtyuooswvt.html

[U109] JS：数组分组
来源：http://dali.birdmap.top/Article/details/gteeuxzdae.html

Object.groupBy(arr, x => x.type)
来源：http://dali.iojbl.cn/Article/details/gtmgqrcepq.html

[U110] JS：数组分块
来源：http://dali.jiagoushi.top/Article/details/gtkwxmloku.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.feifeiyinyue.top/Article/details/gtivxcnstj.html

[U111] JS：对象转 Map
来源：http://dali.zhengqikj.top/Article/details/gtlsmafdjb.html

new Map(Object.entries(obj))
来源：http://dali.ivvv.top/Article/details/gtxjemrhwr.html

[U112] JS：字符串补位
来源：http://dali.sysykeji.top/Article/details/gtwbyhyjef.html

"7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gtnkkprtyt.html

[U113] JS：正则替换全部
来源：http://dali.tanke756.top/Article/details/gtjeodmtzl.html

s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtrpxjiedl.html

[U114] JS：JSON 深比较
来源：http://dali.nwbrower.top/Article/details/gtbqqdiuix.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tianlin.xyz/Article/details/gtscigmqbc.html

[U115] JS：生成 UUID
来源：http://dali.sweek.top/Article/details/gtexqvkrwz.html

crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwhfeuuy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gzhubu.top/Article/details/gtffgbffob.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yueranfly.top/Article/details/gtxxmrpbva.html

[U117] JS：单元测试
来源：http://dali.iojbl.cn/Article/details/gtuylxsfee.html

npm i -D vitest;  npx vitest
来源：http://dali.guowangkeji.top/Article/details/gtivkvjdcj.html

[U118] JS：开发服务器
来源：http://dali.hfpthk.cn/Article/details/gtvqqvbqqv.html

npm i -D vite;  npx vite
来源：http://dali.hongshengwenyu.top/Article/details/gtajlujgno.html

[U119] JS：生产构建
来源：http://dali.zhongyouzk.top/Article/details/gtseraofry.html

npx vite build
来源：http://dali.tanke756.top/Article/details/gtkoyhyoaq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.nanxinkj.top/Article/details/gtbxfgxqfi.html

import.meta.env.VITE_API_URL
来源：http://dali.gzhubu.top/Article/details/gthdllxgxv.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtpaxnhkcb.html

统计汇总
来源：http://dali.yonumen.top/Article/details/gtacckytkm.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtaicyxoiw.html

按语言统计（条）：
来源：http://dali.hammf.cn/Article/details/gtfrsjizii.html

Python ......... 252
来源：http://dali.gaohongyu789.top/Article/details/gtehzrhmhj.html

PHP ............ 252
来源：http://dali.sysykeji.top/Article/details/gtigncgpye.html

JavaScript ..... 252
来源：http://dali.bjfxy.top/Article/details/gtcidmivmi.html

TypeScript ..... 212
来源：http://dali.xylfe.cn/Article/details/gtrwgpxaih.html

Java ........... 212
来源：http://dali.yj20258.top/Article/details/gtgsjtzbml.html

Go ............. 212
来源：http://dali.haohaochexian.top/Article/details/gtrlwlhxpz.html

Ruby ........... 212
来源：http://dali.cashguo.top/Article/details/gtrjpaylff.html

C# ............. 212
来源：http://dali.daxiang520.top/Article/details/gthgdgqmuk.html

C .............. 30
来源：http://dali.dashuyun.cn/Article/details/gtuoqxkopc.html

C++ ............ 30
来源：http://dali.dianchejie.cn/Article/details/gtuefxcefg.html

SQL ............ 90
来源：http://dali.pycfn.com/Article/details/gtpdxcboos.html

Bash ........... 80
来源：http://dali.birdmap.top/Article/details/gthemlbhna.html

Kotlin ......... 15
来源：http://dali.quarkkingdee.top/Article/details/gtwhtcxcoy.html

Swift .......... 15
来源：http://dali.dianchejie.cn/Article/details/gtznivlhvj.html

Lua ............ 10
来源：http://dali.pycfn.com/Article/details/gtrwroktpk.html

Perl ........... 10
来源：http://dali.cucudq.cn/Article/details/gtvwhbwykb.html

Scala .......... 10
来源：http://dali.xziqi.cn/Article/details/gtvcndfdap.html

------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gtixeijirh.html

合计 ........... 2106 条
来源：http://dali.hywenlv.cn/Article/details/gttkfxwvyf.html

按章节统计：
来源：http://dali.guowangkeji.top/Article/details/gtzerkejdy.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zycfv.cn/Article/details/gtlbmsqwhb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zdqjudy.top/Article/details/gtxmvwkkaj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ivvv.top/Article/details/gtesnbqdef.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jianghu66.top/Article/details/gtdipvynfl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.nanxuanxn.top/Article/details/gtcusnrvvo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.dianchejie.cn/Article/details/gtjqaxjtvk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ydzc1.top/Article/details/gtplpwtqwc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhoulong.xyz/Article/details/gtcclworzq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.iojbl.cn/Article/details/gtwqrdqhlk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shangyingyoupin.top/Article/details/gtbnasxqhd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.kuanghao11.cn/Article/details/gtnngnjqlh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.iojbl.cn/Article/details/gtsdjllgiz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gtrhnwqghj.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhongyouzk.top/Article/details/gtkrstblis.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.iojbl.cn/Article/details/gtzgehywjp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gtjkgeupcx.html

Q SQL 专题                              90
来源：http://dali.mhx1999.top/Article/details/gtajnfjszs.html

R Bash 专题                             80
来源：http://dali.aizwys.cn/Article/details/gtdrwxgagl.html

S C / C++ 专题                          60
来源：http://dali.gzhubu.top/Article/details/gtcnfobybw.html

T 其他语言补充                          60
来源：http://dali.pycfn.com/Article/details/gtnjhojpgk.html

U 高频实用片段                         120
来源：http://dali.fengsongda.top/Article/details/gtetqcvwxq.html

------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gtbemnssib.html

合计                                  2106 条
来源：http://dali.meibo888.top/Article/details/gtjpifwmvw.html

--------------------------------------------------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gtfbikosjn.html

使用提醒
来源：http://dali.jinqigfzy.top/Article/details/gtakcotzqu.html

--------------------------------------------------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gtgngphaex.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.aibaodan.cn/Article/details/gteaaiqkrr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jyoumei.cn/Article/details/gtzdtxxtiw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yj20258.top/Article/details/gtbbwecskm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.dashuyun.cn/Article/details/gtdtybaaap.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.nwbrower.top/Article/details/gtummooltd.html

—— 文件结束 ——
来源：http://dali.redwolf501.top/Article/details/gtbhlodxmv.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gthcdsacfv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shuidangran.top/Article/details/gtlxxosylo.html

Common Programming Examples Cheat Book
来源：http://dali.aizwys.cn/Article/details/gtwbmdtuvm.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtfvllmgik.html

【收录内容】
来源：http://dali.0kj1m.cn/Article/details/gtvwsyoqqf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.fzhhl.top/Article/details/gtitwrgzjk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.c1oappe.top/Article/details/gtpolospfe.html

SQL · Bash · C · C++
来源：http://dali.snrcjt.cn/Article/details/gtxoavbfch.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.nanxuanxn.top/Article/details/gtiyhpdogp.html

【使用说明】
来源：http://dali.redwolf501.top/Article/details/gtjbkcwwpv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.wangshuangyany.cn/Article/details/gtbycouuap.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhaomingkeji.xyz/Article/details/gticezdiys.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.dashuyun.cn/Article/details/gtibkxjlpk.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hnqzz.top/Article/details/gtgplszisf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xziqi.cn/Article/details/gtayqnazac.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yvedp.cn/Article/details/gtshugwjgc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.tian-w.cn/Article/details/gtinllgrxs.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhixingplan.top/Article/details/gtzxwvsvkh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.wangshuangyany.cn/Article/details/gtfnahmjhu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqljtzqy.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jqgufenzy.top/Article/details/gtjebxbtjp.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.tian-w.cn/Article/details/gtfmrpzyve.html

【文件统计】
来源：http://dali.zdqjudy.top/Article/details/gtaenvyvmf.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jinqigfzy.top/Article/details/gtcouugksg.html

--------------------------------------------------------------------------------
来源：http://dali.xziqi.cn/Article/details/gtqovffyuu.html

目  录
来源：http://dali.wangshuangyany.cn/Article/details/gttpksiazb.html

--------------------------------------------------------------------------------
来源：http://dali.bjfxy.top/Article/details/gtrqqmqxcq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.nanxuanxn.top/Article/details/gtvqpalict.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yvedp.cn/Article/details/gtduobpyez.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yvedp.cn/Article/details/gtpzywpwpe.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.gzhubu.top/Article/details/gtnqppukka.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hammf.cn/Article/details/gttmzftugw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yuanzhike.top/Article/details/gthalgghqa.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhengqikj.top/Article/details/gtwoyxspvz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.vqdsnc.cn/Article/details/gtbjgzwhfh.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.aizwys.cn/Article/details/gtnklpumjy.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.guowangkeji.top/Article/details/gtvykubzxr.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ybcxt.top/Article/details/gtzsxnwmft.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.chenzaomai.com/Article/details/gtvngwneje.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.chenlongwang.top/Article/details/gtyqdgscrw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.chenjidiqi.icu/Article/details/gttcqpafes.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwpomgxy.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gtubpuwybn.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtnrrazxgp.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yj202588.top/Article/details/gtkhjmtowg.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.havefunace.top/Article/details/gtmsicfnkl.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shangyingyoupin.top/Article/details/gtyecdzvtj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigfzy.top/Article/details/gtfpajzggw.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtjqtfbmxb.html

A. 基础语法与类型
来源：http://dali.xylfe.cn/Article/details/gtbhguhyqv.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtrmutpoqj.html

[A01] Hello World
来源：http://dali.cheryme.top/Article/details/gtcyvatqjv.html

Py:   print("Hello, World!")
来源：http://dali.yvedp.cn/Article/details/gtkgpynals.html

PHP:  echo "Hello, World!";
来源：http://dali.ybcxt.top/Article/details/gtzevqjpjk.html

JS:   console.log("Hello, World!");
来源：http://dali.ivvv.top/Article/details/gthxuzpjek.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.shangyingyoupin.top/Article/details/gttmrtnqzl.html

Java: System.out.println("Hello, World!");
来源：http://dali.smart0.xyz/Article/details/gtytvetssm.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.316326.xyz/Article/details/gtljbqkiwu.html

Ruby: puts "Hello, World!"
来源：http://dali.yanxiufei.cn/Article/details/gtbxkjeyii.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hywenlv.cn/Article/details/gtpvgonzgk.html

[A02] 变量声明与赋值
来源：http://dali.yuxming.cn/Article/details/gtuwxurblj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.bjfxy.top/Article/details/gtvothgerv.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.shuidangran.top/Article/details/gtxdaltunh.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.gzhubu.top/Article/details/gtqgmqccrd.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yuxming.cn/Article/details/gtqpunzzit.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yanxiufei.cn/Article/details/gtavzegoxf.html

Go:   name := "Alex"; age := 20
来源：http://dali.yuanzhike.top/Article/details/gtgxcansbn.html

Ruby: name = "Alex"; age = 20
来源：http://dali.havefunace.top/Article/details/gtqcwazkdw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.birdmap.top/Article/details/gtnesfzrrq.html

[A03] 常量定义
来源：http://dali.ybcxt.top/Article/details/gtqxdzxuqo.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.chenjidiqi.icu/Article/details/gtsklfbrnt.html

PHP:  const PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtxqmzcrab.html

JS:   const PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtoblwcyqy.html

TS:   const PI: number = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtmwtduuvj.html

Java: static final double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtfkrguppo.html

Go:   const PI = 3.14159
来源：http://dali.cqqwz.cn/Article/details/gtskhqsyll.html

Ruby: PI = 3.14159
来源：http://dali.kuanghao11.cn/Article/details/gtodrndkty.html

C#:   const double PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtesuisagi.html

[A04] 判断变量类型
来源：http://dali.yuanzhike.top/Article/details/gtfpikfbsm.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jiagoushi.top/Article/details/gtvkokjhnv.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.dashuyun.cn/Article/details/gtyevbqlrj.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.birdmap.top/Article/details/gtkxbhlwop.html

TS:   typeof x; x instanceof Date
来源：http://dali.jinghuilouyu.cn/Article/details/gtueauppbh.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.fengsongda.top/Article/details/gtgkqmgtte.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.wangshuangyany.cn/Article/details/gtyrkvkcoj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yuanzhike.top/Article/details/gtxwlnfksz.html

C#:   x.GetType().Name; x is int
来源：http://dali.sxryk.cn/Article/details/gtosotzwam.html

[A05] 整数除法与取模
来源：http://dali.sufxvd.cn/Article/details/gtdkpdjpji.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.tian-w.cn/Article/details/gturzmorlk.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gtiykiwmpw.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cucudq.cn/Article/details/gthoqbibjz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shuidangran.top/Article/details/gtmhbqtunp.html

Java: 7 / 2; 7 % 2
来源：http://dali.ivvv.top/Article/details/gtmkiyyaxz.html

Go:   7 / 2; 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gtpsremmxu.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gtjolwirbx.html

C#:   7 / 2; 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtlmjzqlfb.html

[A06] 字符串转数字
来源：http://dali.gogol.net.cn/Article/details/gtqnlmyduw.html

Py:   int("42"); float("3.14")
来源：http://dali.yuxming.cn/Article/details/gthxxienpo.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.fzhhl.top/Article/details/gtrcfqioes.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.birdmap.top/Article/details/gtsjdtraqx.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hongshengwenyu.top/Article/details/gthuuccnwz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.feifeiyinyue.top/Article/details/gtbtcpsjbt.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmepaseiu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jyoumei.cn/Article/details/gtgjekfxeq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xinyue.icu/Article/details/gtphbetilj.html

[A07] 数字转字符串
来源：http://dali.dianchejie.cn/Article/details/gtyznrdyfn.html

Py:   str(42)
来源：http://dali.pengpengdd.cyou/Article/details/gteuajmbqo.html

PHP:  (string) 42; strval(42)
来源：http://dali.xinyue.icu/Article/details/gttwxbqwpq.html

JS:   String(42); (42).toString()
来源：http://dali.ppjwa.cn/Article/details/gtsfmjhvop.html

TS:   String(42)
来源：http://dali.sxryk.cn/Article/details/gtkxyeeyzf.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zycfv.cn/Article/details/gtddtdyrsg.html

Go:   strconv.Itoa(42)
来源：http://dali.zdqjudy.top/Article/details/gtbphtvfbo.html

Ruby: 42.to_s
来源：http://dali.redwolf501.top/Article/details/gtggjxfwyw.html

C#:   42.ToString()
来源：http://dali.9152youxi.cn/Article/details/gtclyfxtnq.html

[A08] 取整与四舍五入
来源：http://dali.fengsongda.top/Article/details/gtahpgsfqk.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.nwbrower.top/Article/details/gtqvehvxkh.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.quarkkingdee.top/Article/details/gtyobcqezh.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.birdmap.top/Article/details/gtddbmgtkq.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yuanzhike.top/Article/details/gtxbvvetfp.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.aibaodan.cn/Article/details/gtgpfadthh.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.bjfxy.top/Article/details/gttbtxrrwd.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.shzxlz.cn/Article/details/gtriumjxwv.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.sxryk.cn/Article/details/gtuvnpjdew.html

[A09] 绝对值与最大最小值
来源：http://dali.hnqzz.top/Article/details/gtdqlbyojq.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtpqmphdkg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gtzfpsjwcw.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtwbpuihqp.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yonumen.top/Article/details/gtimjexbls.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.aizwys.cn/Article/details/gtpotlqtlx.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhixingplan.top/Article/details/gtcrrsnarr.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.redwolf501.top/Article/details/gtlkhrryjn.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.tanke756.top/Article/details/gteuzngnag.html

[A10] 生成随机数
来源：http://dali.yonumen.top/Article/details/gtezpuvqig.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jqgfzy.top/Article/details/gtgzsfzqlf.html

PHP:  random_int(1, 100);
来源：http://dali.feifeiyinyue.top/Article/details/gtajtxaeei.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnlubhipa.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jinqigfzy.top/Article/details/gtuznacdbm.html

Java: new Random().nextInt(100) + 1
来源：http://dali.daxiang520.top/Article/details/gtmsebjoji.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.pycfn.com/Article/details/gtmqckpdpc.html

Ruby: rand(1..100)
来源：http://dali.meibo888.top/Article/details/gtjylmklhw.html

C#:   new Random().Next(1, 101)
来源：http://dali.yanxiufei.cn/Article/details/gtidrfjfai.html

[A11] 条件表达式（三元）
来源：http://dali.sweek.top/Article/details/gtpyfodfad.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.shangyingyoupin.top/Article/details/gtmfunskvw.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.gaohongyu789.top/Article/details/gtymvbglku.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.cucudq.cn/Article/details/gtohvyvlcv.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxpqyrkkh.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yuanzhike.top/Article/details/gthvsxsjnd.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jqgfzy.top/Article/details/gtwteyfgxi.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.cdnleiting.top/Article/details/gtljowixta.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.9152youxi.cn/Article/details/gtdvywmzmo.html

[A12] 字符串插值 / 格式化
来源：http://dali.xinyue.icu/Article/details/gtoqrbdsub.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkfsxrzy.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.pengpengdd.cyou/Article/details/gtyiwzkyur.html

JS:   `Hello, ${name}!`
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpgihuyy.html

TS:   `Hello, ${name}!`
来源：http://dali.svipenyu.cn/Article/details/gtllvosqhp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jyoumei.cn/Article/details/gtgmjczomk.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.hnxiangtu.top/Article/details/gtgyreupvm.html

Ruby: "Hello, #{name}!"
来源：http://dali.hnqzz.top/Article/details/gtbycekjvb.html

C#:   $"Hello, {name}!"
来源：http://dali.gogol.net.cn/Article/details/gthbzfieus.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.shangyingyoupin.top/Article/details/gtehceiejp.html

Py:   "第一行\n第二行"
来源：http://dali.yj20258888.top/Article/details/gtenvtdgbf.html

PHP:  "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gtpqbumeoh.html

JS:   "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gtwosuhtir.html

TS:   "第一行\n第二行"
来源：http://dali.ivvv.top/Article/details/gtibcurevd.html

Java: "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gtxdehudll.html

Go:   "第一行\n第二行"
来源：http://dali.chenjidiqi.icu/Article/details/gtqcoztcog.html

Ruby: "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gtvhrespjp.html

C#:   "第一行\n第二行"
来源：http://dali.ivvv.top/Article/details/gtpqevyqoi.html

[A14] 注释写法
来源：http://dali.yangfankeji.com/Article/details/gtlzpwpaka.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.hywenlv.cn/Article/details/gtmvkioyvm.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.feifeiyinyue.top/Article/details/gtbewoiyzh.html

JS:   // 单行；/* 多行 */
来源：http://dali.quarkkingdee.top/Article/details/gtaupjmcbv.html

TS:   // 单行；/* 多行 */
来源：http://dali.9152youxi.cn/Article/details/gttnhxawtj.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.xylfe.cn/Article/details/gtgsqtnizk.html

Go:   // 单行；/* 多行 */
来源：http://dali.hnqzz.top/Article/details/gtmxyzggsa.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jyoumei.cn/Article/details/gtzcmaettu.html

C#:   // 单行；/* 多行 */
来源：http://dali.iojbl.cn/Article/details/gtvvhwqowf.html

[A15] 空值判断与默认值
来源：http://dali.chenjidiqi.icu/Article/details/gtuopowvsq.html

Py:   value = data or "默认值"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedptlvsl.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.gzhubu.top/Article/details/gtxwrzvvbm.html

JS:   const value = data ?? "默认值";
来源：http://dali.meibo888.top/Article/details/gtdownhxen.html

TS:   const value = data ?? "默认值";
来源：http://dali.cheryme.top/Article/details/gtjqwxqxbo.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ydzc1.top/Article/details/gtprdfbhco.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.fzhhl.top/Article/details/gtuobkykdq.html

Ruby: value = data || "默认值"
来源：http://dali.sweek.top/Article/details/gtxuugarrr.html

C#:   var value = data ?? "默认值";
来源：http://dali.zycfv.cn/Article/details/gtkhbaxlxj.html

[A16] 真假值判断规则
来源：http://dali.guannengcc.top/Article/details/gtvfptglvj.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.hammf.cn/Article/details/gtlyuepswz.html


<!-- 参考信息 -->