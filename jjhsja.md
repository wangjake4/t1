代发 wailian999

[U99] JS：事件监听
来源：http://dali.xylfe.cn/Article/details/gt2lufynwju.html

el.addEventListener("click", e => {})
来源：http://dali.wangshuangyany.cn/Article/details/gt2nqttdnfu.html

[U100] JS：DOM 查询
来源：http://dali.sxryk.cn/Article/details/gt2zdtszzux.html

document.querySelector(".item")
来源：http://dali.jyoumei.cn/Article/details/gt2hbhytbwj.html

[U101] JS：classList 操作
来源：http://dali.c1oappe.top/Article/details/gt2xtoixyhm.html

el.classList.toggle("active")
来源：http://dali.guowangkeji.top/Article/details/gt2mwuwuqrc.html

[U102] JS：本地存储
来源：http://dali.jinghuilouyu.cn/Article/details/gt2snnimerq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.bjfxy.top/Article/details/gt2vonjxchz.html

[U103] JS：定时器
来源：http://dali.aizwys.cn/Article/details/gt2aefgjbuu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.feifeiyinyue.top/Article/details/gt2taapxjds.html

[U104] JS：防抖
来源：http://dali.sweek.top/Article/details/gt2wnsohdjy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gt2nbmyjhrb.html

[U105] JS：节流
来源：http://dali.iojbl.cn/Article/details/gt2wpcknlll.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gzhubu.top/Article/details/gt2omtufaay.html

[U106] JS：日期格式化
来源：http://dali.aizwys.cn/Article/details/gt2zfcxhwrv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.vqdsnc.cn/Article/details/gt2mkgksjdj.html

[U107] JS：数字千分位
来源：http://dali.yonumen.top/Article/details/gt2xgjiybxs.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gotoacloud.top/Article/details/gt2rtjpttcy.html

[U108] JS：随机整数
来源：http://dali.pengpengdd.cyou/Article/details/gt2mufmzxmo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.quarkkingdee.top/Article/details/gt2cvuqdkus.html

[U109] JS：数组分组
来源：http://dali.gaohongyu789.top/Article/details/gt2qukybsxg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gt2varmzntu.html

[U110] JS：数组分块
来源：http://dali.kuanghao11.cn/Article/details/gt2dcipwgmo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gogol.net.cn/Article/details/gt2xgyapmlv.html

[U111] JS：对象转 Map
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fmelclbb.html

new Map(Object.entries(obj))
来源：http://dali.tian-w.cn/Article/details/gt2tboutzcs.html

[U112] JS：字符串补位
来源：http://dali.tian-w.cn/Article/details/gt2looyhwuh.html

"7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gt2iwfbvijn.html

[U113] JS：正则替换全部
来源：http://dali.shzxlz.cn/Article/details/gt2lsdfxiia.html

s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2morowzsb.html

[U114] JS：JSON 深比较
来源：http://dali.vqdsnc.cn/Article/details/gt2iocyognj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xziqi.cn/Article/details/gt2sefmyzmb.html

[U115] JS：生成 UUID
来源：http://dali.daxiang520.top/Article/details/gt2lamnmqpr.html

crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gt2ypoverih.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhoulong.xyz/Article/details/gt2wroxopbp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zycfv.cn/Article/details/gt2foetyylk.html

[U117] JS：单元测试
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hdrfxpnb.html

npm i -D vitest;  npx vitest
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rztnsphn.html

[U118] JS：开发服务器
来源：http://dali.zdqjudy.top/Article/details/gt2ublryqgw.html

npm i -D vite;  npx vite
来源：http://dali.xylfe.cn/Article/details/gt2envvqnwd.html

[U119] JS：生产构建
来源：http://dali.hnxiangtu.top/Article/details/gt2wrvgomjh.html

npx vite build
来源：http://dali.cashguo.top/Article/details/gt2esbejkba.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.daxiang520.top/Article/details/gt2dydzqbms.html

import.meta.env.VITE_API_URL
来源：http://dali.nanxuanxn.top/Article/details/gt2jqzdkqzd.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2nfplnbso.html

统计汇总
来源：http://dali.sweek.top/Article/details/gt2ixneocqu.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2bkeobsdm.html

按语言统计（条）：
来源：http://dali.yj20258.top/Article/details/gt2prkwepgo.html

Python ......... 252
来源：http://dali.zhengqikj.top/Article/details/gt2bvxvsvyt.html

PHP ............ 252
来源：http://dali.pycfn.com/Article/details/gt2qzgwhshk.html

JavaScript ..... 252
来源：http://dali.yj20258888.top/Article/details/gt2crscnqow.html

TypeScript ..... 212
来源：http://dali.fengsongda.top/Article/details/gt2qelfuyyo.html

Java ........... 212
来源：http://dali.gaohongyu789.top/Article/details/gt2zirmsjpj.html

Go ............. 212
来源：http://dali.9152youxi.cn/Article/details/gt2kthcethw.html

Ruby ........... 212
来源：http://dali.ppjwa.cn/Article/details/gt2sxudqadc.html

C# ............. 212
来源：http://dali.sweek.top/Article/details/gt2qqklhnea.html

C .............. 30
来源：http://dali.chenzaomai.com/Article/details/gt2edyuxdgm.html

C++ ............ 30
来源：http://dali.c1oappe.top/Article/details/gt2jvbfakrc.html

SQL ............ 90
来源：http://dali.hfpthk.cn/Article/details/gt2naslzpam.html

Bash ........... 80
来源：http://dali.yuanzhike.top/Article/details/gt2mdsbfynm.html

Kotlin ......... 15
来源：http://dali.hongshengwenyu.top/Article/details/gt2ysftquer.html

Swift .......... 15
来源：http://dali.jiagoushi.top/Article/details/gt2couzjkqz.html

Lua ............ 10
来源：http://dali.zhengqikj.top/Article/details/gt2fidklssa.html

Perl ........... 10
来源：http://dali.aibaodan.cn/Article/details/gt2yyuuabgo.html

Scala .......... 10
来源：http://dali.ybcxt.top/Article/details/gt2bohvvnoq.html

------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gt2hxmgbkvw.html

合计 ........... 2106 条
来源：http://dali.jyoumei.cn/Article/details/gt2iezdpdtu.html

按章节统计：
来源：http://dali.yj202588.top/Article/details/gt2lnglwqgv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.chenzaomai.com/Article/details/gt2xcizfmvg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gt2tgfxndxz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hnqzz.top/Article/details/gt2apqjljfo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yongpay.top/Article/details/gt2qdmeaipd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.kuanghao11.cn/Article/details/gt2owvblxes.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jinqigfzy.top/Article/details/gt2hqdtgfzp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xuetiantiany.cn/Article/details/gt2twiwrvch.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yueranfly.top/Article/details/gt2hdhwmqfl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rizsomud.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinqigufen.top/Article/details/gt2efnfjvgw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gt2jlxkwvio.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jiagoushi.top/Article/details/gt2yzefhqbs.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.dianchejie.cn/Article/details/gt2ldxecffp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xuetiantiany.cn/Article/details/gt2lwlcckhx.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uffsdejl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gt2gqhuprhn.html

Q SQL 专题                              90
来源：http://dali.zhoulong.xyz/Article/details/gt2moydudyf.html

R Bash 专题                             80
来源：http://dali.nanxuanxn.top/Article/details/gt2zykxwsxh.html

S C / C++ 专题                          60
来源：http://dali.redwolf501.top/Article/details/gt2wcnevqjl.html

T 其他语言补充                          60
来源：http://dali.ppjwa.cn/Article/details/gt2nhjirwlk.html

U 高频实用片段                         120
来源：http://dali.xuetiantiany.cn/Article/details/gt2dyzvvatr.html

------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gt2jwouibey.html

合计                                  2106 条
来源：http://dali.ybcxt.top/Article/details/gt2firvxhxu.html

--------------------------------------------------------------------------------
来源：http://dali.xylfe.cn/Article/details/gt2rxfcohcp.html

使用提醒
来源：http://dali.pengpengdd.cyou/Article/details/gt2bbwfnfru.html

--------------------------------------------------------------------------------
来源：http://dali.ydzc1.top/Article/details/gt2lbusxwku.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hysaishi.cn/Article/details/gt2hokrlppw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.dianchejie.cn/Article/details/gt2bofcijld.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jinqigufen.top/Article/details/gt2emiwmtfa.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.tian-w.cn/Article/details/gt2dizqwmxj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhengqikj.top/Article/details/gt2yyeudvec.html

—— 文件结束 ——
来源：http://dali.aibaodan.cn/Article/details/gt2zxoafcxb.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2fkazlvcg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhixingplan.top/Article/details/gt2rjfxfbku.html

Common Programming Examples Cheat Book
来源：http://dali.redwolf501.top/Article/details/gt2keituthu.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2uemabbsb.html

【收录内容】
来源：http://dali.daria6918.cn/Article/details/gt2fknhslhq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hnxiangtu.top/Article/details/gt2srjvpvdu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yj20258.top/Article/details/gt2czafhdkd.html

SQL · Bash · C · C++
来源：http://dali.ppjwa.cn/Article/details/gt2galuhuik.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.c1oappe.top/Article/details/gt2dwxusorr.html

【使用说明】
来源：http://dali.yangfankeji.com/Article/details/gt2zxjlhwuk.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ubqifwmy.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.mhx1999.top/Article/details/gt2bdsztrbf.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.316326.xyz/Article/details/gt2nondygik.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hnxiangtu.top/Article/details/gt2lipcabbc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jianghu66.top/Article/details/gt2yxznhpvf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.sysykeji.top/Article/details/gt2ehombmdg.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ihpvnxjm.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xinyue.icu/Article/details/gt2emzugijl.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hnqzz.top/Article/details/gt2ebhakhty.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.nanxuanxn.top/Article/details/gt2vxiaqbpt.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.fzhhl.top/Article/details/gt2bunawvln.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.redwolf501.top/Article/details/gt2qhktkjox.html

【文件统计】
来源：http://dali.gotoacloud.top/Article/details/gt2ubshlchi.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.chenjidiqi.icu/Article/details/gt2phqiksga.html

--------------------------------------------------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gt2wlaspfkd.html

目  录
来源：http://dali.ivvv.top/Article/details/gt2mjyfcodt.html

--------------------------------------------------------------------------------
来源：http://dali.xylfe.cn/Article/details/gt2iepkgulr.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yj20258.top/Article/details/gt2fgztdsqz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.guannengcc.top/Article/details/gt2hepquyut.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2bfwtixva.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.guowangkeji.top/Article/details/gt2urbgoimk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2euanlyle.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2qvgtgvhq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.nwbrower.top/Article/details/gt2feabbxxb.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xuanzx.com/Article/details/gt2twxqpjtx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mddiaibo.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yueranfly.top/Article/details/gt2yatbotvf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izxmnbcu.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xylfe.cn/Article/details/gt2fqtuxsrr.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2jrspegst.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhixingplan.top/Article/details/gt2cwsxpffw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xylfe.cn/Article/details/gt2yngvqpqv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.svipenyu.cn/Article/details/gt2veswbhmr.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2ayhpmyek.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2xgwdzwhj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.c1oappe.top/Article/details/gt2kbylvzca.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aizwys.cn/Article/details/gt2qrzzwlwn.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2cyizqaqo.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2itqrworg.html

A. 基础语法与类型
来源：http://dali.wangdashe.top/Article/details/gt2rumbjipx.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xyfxpsnc.html

[A01] Hello World
来源：http://dali.iojbl.cn/Article/details/gt2xjarhcgf.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2oguvppvy.html

PHP:  echo "Hello, World!";
来源：http://dali.tianlin.xyz/Article/details/gt2klxlymow.html

JS:   console.log("Hello, World!");
来源：http://dali.wangdashe.top/Article/details/gt2qmyhhavv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.nanxuanxn.top/Article/details/gt2vsinjehq.html

Java: System.out.println("Hello, World!");
来源：http://dali.hammf.cn/Article/details/gt2igzqcfzx.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.andypj.xyz/Article/details/gt2sikrkjex.html

Ruby: puts "Hello, World!"
来源：http://dali.vqdsnc.cn/Article/details/gt2fxjoskhs.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yuanzhike.top/Article/details/gt2jneotsjv.html

[A02] 变量声明与赋值
来源：http://dali.yanxiufei.cn/Article/details/gt2teokkwnb.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.bjfxy.top/Article/details/gt2xbyllkia.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ppjwa.cn/Article/details/gt2gyvbvnow.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.0kj1m.cn/Article/details/gt2ubpfikfv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yonumen.top/Article/details/gt2sbiesuaa.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.mhx1999.top/Article/details/gt2otseznja.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhoulong.xyz/Article/details/gt2yjzksqpf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.snrcjt.cn/Article/details/gt2xtyergiv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bqptgnch.html

[A03] 常量定义
来源：http://dali.pengpengdd.cyou/Article/details/gt2zspiztak.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.meibo888.top/Article/details/gt2lszdfgxb.html

PHP:  const PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gt2zjtcmvrr.html

JS:   const PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gt2dicdxqvs.html

TS:   const PI: number = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gt2ueawmmlb.html

Java: static final double PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gt2enbxsylt.html

Go:   const PI = 3.14159
来源：http://dali.yj202588.top/Article/details/gt2hbumspwe.html

Ruby: PI = 3.14159
来源：http://dali.jinqigfzy.top/Article/details/gt2pfzuxqhq.html

C#:   const double PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gt2yetoegnl.html

[A04] 判断变量类型
来源：http://dali.xziqi.cn/Article/details/gt2tqdubtgl.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.iojbl.cn/Article/details/gt2dpmefink.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rdwirjut.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhoulong.xyz/Article/details/gt2hrlcwuha.html

TS:   typeof x; x instanceof Date
来源：http://dali.guowangkeji.top/Article/details/gt2xpcbjxqs.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.svipenyu.cn/Article/details/gt2szkwxotf.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xuetiantiany.cn/Article/details/gt2wmlukmpe.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.guowangkeji.top/Article/details/gt2gfgirtoq.html

C#:   x.GetType().Name; x is int
来源：http://dali.fzhhl.top/Article/details/gt2biwkqurp.html

[A05] 整数除法与取模
来源：http://dali.hnxiangtu.top/Article/details/gt2qskmqjtd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.ydzc1.top/Article/details/gt2equzdthk.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yongpay.top/Article/details/gt2oofxzgqk.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ybcxt.top/Article/details/gt2okwhdiza.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gt2okwxkzdj.html

Java: 7 / 2; 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gt2dsoywfua.html

Go:   7 / 2; 7 % 2
来源：http://dali.daria6918.cn/Article/details/gt2nclmqkex.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gt2yohnuans.html

C#:   7 / 2; 7 % 2
来源：http://dali.pycfn.com/Article/details/gt2inranfwg.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjuqdzs.html

Py:   int("42"); float("3.14")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2owrxymzh.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hnxiangtu.top/Article/details/gt2gwjxmjae.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.gogol.net.cn/Article/details/gt2ubmkcdlx.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ppjwa.cn/Article/details/gt2xydynkop.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zdqjudy.top/Article/details/gt2qmurzhmo.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.daxiang520.top/Article/details/gt2osctfklm.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dfrsbjvd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.haohaochexian.top/Article/details/gt2wdycfwaa.html

[A07] 数字转字符串
来源：http://dali.nanxinkj.top/Article/details/gt2bmsqokeb.html

Py:   str(42)
来源：http://dali.pycfn.com/Article/details/gt2mzuempex.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zmjijdgz.html

JS:   String(42); (42).toString()
来源：http://dali.cqqwz.cn/Article/details/gt2aucmemws.html

TS:   String(42)
来源：http://dali.daxiang520.top/Article/details/gt2pbxjupar.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yangfankeji.com/Article/details/gt2xfpvislx.html

Go:   strconv.Itoa(42)
来源：http://dali.yanxiufei.cn/Article/details/gt2fdlxxalw.html

Ruby: 42.to_s
来源：http://dali.guannengcc.top/Article/details/gt2isalqzmn.html

C#:   42.ToString()
来源：http://dali.nwbrower.top/Article/details/gt2yvjefzex.html

[A08] 取整与四舍五入
来源：http://dali.hammf.cn/Article/details/gt2pmfofboz.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hnxiangtu.top/Article/details/gt2nyozofgt.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.bjfxy.top/Article/details/gt2mhhfwtap.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.ivvv.top/Article/details/gt2agxwkbju.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.cucudq.cn/Article/details/gt2ueddtjer.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yuanzhike.top/Article/details/gt2ygqfzwrz.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.wangdashe.top/Article/details/gt2lihiyvxv.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhongyouzk.top/Article/details/gt2nsiivtnz.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yonumen.top/Article/details/gt2rholpijr.html

[A09] 绝对值与最大最小值
来源：http://dali.chenzaomai.com/Article/details/gt2brmocsji.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.andypj.xyz/Article/details/gt2yirdgpyj.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2znycsyew.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gt2vkbhrhmp.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.ybcxt.top/Article/details/gt2xuuovevm.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dxlzqpfp.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yangfankeji.com/Article/details/gt2iyaueuor.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.kuanghao11.cn/Article/details/gt2gccppgvh.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hrbmxesm.html

[A10] 生成随机数
来源：http://dali.sysykeji.top/Article/details/gt2ljswwmvg.html

Py:   import random; random.randint(1, 100)
来源：http://dali.guowangkeji.top/Article/details/gt2reaeszqy.html

PHP:  random_int(1, 100);
来源：http://dali.xziqi.cn/Article/details/gt2dhrwbwhp.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shuidangran.top/Article/details/gt2yeysfbnj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yonumen.top/Article/details/gt2zcebbspi.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zdqjudy.top/Article/details/gt2xagsbqvq.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jlsjyb.cn/Article/details/gt2mcxymwgm.html

Ruby: rand(1..100)
来源：http://dali.nwbrower.top/Article/details/gt2raptappp.html

C#:   new Random().Next(1, 101)
来源：http://dali.c1oappe.top/Article/details/gt2srvthure.html

[A11] 条件表达式（三元）
来源：http://dali.sxryk.cn/Article/details/gt2kkdsmwwl.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.smart0.xyz/Article/details/gt2aaumroae.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.cashguo.top/Article/details/gt2upywrgui.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.gzhubu.top/Article/details/gt2npknrgxo.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.daria6918.cn/Article/details/gt2wycafuhp.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.shzxlz.cn/Article/details/gt2hskcmhnn.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.sweek.top/Article/details/gt2hjowards.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.ppjwa.cn/Article/details/gt2sckidwpk.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yueranfly.top/Article/details/gt2fibftzwg.html

[A12] 字符串插值 / 格式化
来源：http://dali.gotoacloud.top/Article/details/gt2gcixgzxz.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhengqikj.top/Article/details/gt2sejxysrq.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2obkpuxbt.html

JS:   `Hello, ${name}!`
来源：http://dali.havefunace.top/Article/details/gt2vuzmppkr.html

TS:   `Hello, ${name}!`
来源：http://dali.jqgufenzy.top/Article/details/gt2vnxvtbfm.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eagvhopi.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.gogol.net.cn/Article/details/gt2irvibket.html

Ruby: "Hello, #{name}!"
来源：http://dali.ydzc1.top/Article/details/gt2ytptifyr.html

C#:   $"Hello, {name}!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tamhwblt.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.dianchejie.cn/Article/details/gt2lgkfiwgw.html

Py:   "第一行\n第二行"
来源：http://dali.c1oappe.top/Article/details/gt2nxdozdll.html

PHP:  "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gt2yynhepxa.html

JS:   "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gt2cwyjjrih.html

TS:   "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qnfwywxl.html

Java: "第一行\n第二行"
来源：http://dali.daria6918.cn/Article/details/gt2qaxmmjxp.html

Go:   "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gt2szwhtbjx.html

Ruby: "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yzgssiak.html

C#:   "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gt2ngflzezl.html

[A14] 注释写法
来源：http://dali.jqgfzy.top/Article/details/gt2dobpbgum.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.quarkkingdee.top/Article/details/gt2zyvlbfhp.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yangfankeji.com/Article/details/gt2rowswrnf.html

JS:   // 单行；/* 多行 */
来源：http://dali.chenjidiqi.icu/Article/details/gt2jgltquos.html

TS:   // 单行；/* 多行 */
来源：http://dali.guannengcc.top/Article/details/gt2cqogxfik.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yangfankeji.com/Article/details/gt2lqylatfi.html

Go:   // 单行；/* 多行 */
来源：http://dali.iojbl.cn/Article/details/gt2gfwusayu.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jqgufenzy.top/Article/details/gt2gqgueebt.html

C#:   // 单行；/* 多行 */
来源：http://dali.cdnleiting.top/Article/details/gt2fxfwuffh.html

[A15] 空值判断与默认值
来源：http://dali.fengsongda.top/Article/details/gt2wgxjnvmx.html

Py:   value = data or "默认值"
来源：http://dali.sysykeji.top/Article/details/gt2zrhwabzt.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.guannengcc.top/Article/details/gt2gnrbubbn.html

JS:   const value = data ?? "默认值";
来源：http://dali.snrcjt.cn/Article/details/gt2romhaabz.html

TS:   const value = data ?? "默认值";
来源：http://dali.xuetiantiany.cn/Article/details/gt2xbfrabez.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.tanke756.top/Article/details/gt2blchiqgs.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shzxlz.cn/Article/details/gt2mkrbosvz.html

Ruby: value = data || "默认值"
来源：http://dali.zhongyouzk.top/Article/details/gt2pdexqkra.html

C#:   var value = data ?? "默认值";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yasbjnlx.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsxbpcr.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.shangyingyoupin.top/Article/details/gt2qqfukcev.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.shangyingyoupin.top/Article/details/gt2rdyuveog.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.ybcxt.top/Article/details/gt2unpccnio.html

TS:   if (!x) {}
来源：http://dali.ydzc1.top/Article/details/gt2ycwonpgf.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.hysaishi.cn/Article/details/gt2zukwckpd.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yanxiufei.cn/Article/details/gt2adubvxjp.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.gzhubu.top/Article/details/gt2fsmxylgd.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.shuidangran.top/Article/details/gt2psptcbty.html

[A17] 位运算
来源：http://dali.nanxuanxn.top/Article/details/gt2wbjlgamn.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gt2nuzglocl.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.nwbrower.top/Article/details/gt2spekgdpa.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.meibo888.top/Article/details/gt2ngjlxxry.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bzhxtiwh.html


<!-- 参考信息 -->