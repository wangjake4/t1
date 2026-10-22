代发 wailian999

[U99] JS：事件监听
来源：http://dali.wangshuangyany.cn/Article/details/gt2xadglvwa.html

el.addEventListener("click", e => {})
来源：http://dali.fzhhl.top/Article/details/gt2wlmremdf.html

[U100] JS：DOM 查询
来源：http://dali.0kj1m.cn/Article/details/gt2ipwsjjyg.html

document.querySelector(".item")
来源：http://dali.jinqigfzy.top/Article/details/gt2qkbtpila.html

[U101] JS：classList 操作
来源：http://dali.xinyue.icu/Article/details/gt2siythoko.html

el.classList.toggle("active")
来源：http://dali.zycfv.cn/Article/details/gt2funxmujd.html

[U102] JS：本地存储
来源：http://dali.aizwys.cn/Article/details/gt2kzhqtbyk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hnxiangtu.top/Article/details/gt2swqyjtpv.html

[U103] JS：定时器
来源：http://dali.sysykeji.top/Article/details/gt2foaaqbfr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.9152youxi.cn/Article/details/gt2qtfbyibb.html

[U104] JS：防抖
来源：http://dali.pengpengdd.cyou/Article/details/gt2ixosaomd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gt2cmpajvpe.html

[U105] JS：节流
来源：http://dali.snrcjt.cn/Article/details/gt2tgvxjvhk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cqqwz.cn/Article/details/gt2moutweyh.html

[U106] JS：日期格式化
来源：http://dali.tian-w.cn/Article/details/gt2xezfqeve.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.sysykeji.top/Article/details/gt2lmcwqtdz.html

[U107] JS：数字千分位
来源：http://dali.meibo888.top/Article/details/gt2xbnsaqtg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gt2rbnuemgl.html

[U108] JS：随机整数
来源：http://dali.daria6918.cn/Article/details/gt2focgveib.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yj20258.top/Article/details/gt2ldwkleqf.html

[U109] JS：数组分组
来源：http://dali.birdmap.top/Article/details/gt2mynpzzec.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sxryk.cn/Article/details/gt2fvzihtiq.html

[U110] JS：数组分块
来源：http://dali.xylfe.cn/Article/details/gt2gnykywwu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xylfe.cn/Article/details/gt2klzyldux.html

[U111] JS：对象转 Map
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wbakbkxj.html

new Map(Object.entries(obj))
来源：http://dali.cqqwz.cn/Article/details/gt2dkorxoae.html

[U112] JS：字符串补位
来源：http://dali.birdmap.top/Article/details/gt2hdeqwbux.html

"7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lpgwdobu.html

[U113] JS：正则替换全部
来源：http://dali.yueranfly.top/Article/details/gt2zoozdodg.html

s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2dnvqolmi.html

[U114] JS：JSON 深比较
来源：http://dali.jqgfzy.top/Article/details/gt2gurmajxc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.316326.xyz/Article/details/gt2wtjkesrg.html

[U115] JS：生成 UUID
来源：http://dali.fzhhl.top/Article/details/gt2xvkcyuvy.html

crypto.randomUUID()
来源：http://dali.jlsjyb.cn/Article/details/gt2ageeawvm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cdnleiting.top/Article/details/gt2udkzgppc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jianghu66.top/Article/details/gt2ezxluttl.html

[U117] JS：单元测试
来源：http://dali.gaohongyu789.top/Article/details/gt2rpqcsrpp.html

npm i -D vitest;  npx vitest
来源：http://dali.ppjwa.cn/Article/details/gt2wnxcbytw.html

[U118] JS：开发服务器
来源：http://dali.xuanzx.com/Article/details/gt2jeekkray.html

npm i -D vite;  npx vite
来源：http://dali.zhixingplan.top/Article/details/gt2gpijjnqg.html

[U119] JS：生产构建
来源：http://dali.hfpthk.cn/Article/details/gt2sdcgnpex.html

npx vite build
来源：http://dali.vqdsnc.cn/Article/details/gt2fhlqmfoy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.tanke756.top/Article/details/gt2rtpjybhd.html

import.meta.env.VITE_API_URL
来源：http://dali.aizwys.cn/Article/details/gt2xvidzqol.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2ztycevnx.html

统计汇总
来源：http://dali.9152youxi.cn/Article/details/gt2sglweeov.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2fdzynjhu.html

按语言统计（条）：
来源：http://dali.tanke756.top/Article/details/gt2nzfgoeeq.html

Python ......... 252
来源：http://dali.chenzaomai.com/Article/details/gt2excztadw.html

PHP ............ 252
来源：http://dali.redwolf501.top/Article/details/gt2kdvqbhva.html

JavaScript ..... 252
来源：http://dali.yongpay.top/Article/details/gt2apfvgpmz.html

TypeScript ..... 212
来源：http://dali.yj20258.top/Article/details/gt2xisemina.html

Java ........... 212
来源：http://dali.yj20258888.top/Article/details/gt2btutvdag.html

Go ............. 212
来源：http://dali.yj20258888.top/Article/details/gt2hmiykyiv.html

Ruby ........... 212
来源：http://dali.jinqigufen.top/Article/details/gt2ncjfumrk.html

C# ............. 212
来源：http://dali.birdmap.top/Article/details/gt2qzpjkwxw.html

C .............. 30
来源：http://dali.haohaochexian.top/Article/details/gt2ukacgype.html

C++ ............ 30
来源：http://dali.316326.xyz/Article/details/gt2xazrgzma.html

SQL ............ 90
来源：http://dali.sxryk.cn/Article/details/gt2psbinvbw.html

Bash ........... 80
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2smgmfprn.html

Kotlin ......... 15
来源：http://dali.yueranfly.top/Article/details/gt2eamawvgx.html

Swift .......... 15
来源：http://dali.daria6918.cn/Article/details/gt2vbugfmly.html

Lua ............ 10
来源：http://dali.yj202588.top/Article/details/gt2zdiwdxch.html

Perl ........... 10
来源：http://dali.316326.xyz/Article/details/gt2jjwgidlj.html

Scala .......... 10
来源：http://dali.cdnleiting.top/Article/details/gt2cjgpwaoq.html

------------------------------------
来源：http://dali.havefunace.top/Article/details/gt2vfndihbh.html

合计 ........... 2106 条
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kscmypjs.html

按章节统计：
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2seuzgwih.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cdnleiting.top/Article/details/gt2yyjxnjpn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.guowangkeji.top/Article/details/gt2bizrllez.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.daria6918.cn/Article/details/gt2vbbgclbc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jqgfzy.top/Article/details/gt2yrzoauwp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ybcxt.top/Article/details/gt2lleqkfro.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jianghu66.top/Article/details/gt2bqtopwbw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gt2vaexdyqy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hfpthk.cn/Article/details/gt2afgnjuer.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gt2usewfpss.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinqigufen.top/Article/details/gt2suqepjir.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gt2mlisblhj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gt2ojbeoojl.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gt2pcjxnbqr.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.chenlongwang.top/Article/details/gt2xqsnsoyk.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhoulong.xyz/Article/details/gt2lnumrmxy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gt2qpigcfzc.html

Q SQL 专题                              90
来源：http://dali.gogol.net.cn/Article/details/gt2lxxprure.html

R Bash 专题                             80
来源：http://dali.guannengcc.top/Article/details/gt2yjhwozbf.html

S C / C++ 专题                          60
来源：http://dali.aibaodan.cn/Article/details/gt2jjzhraoc.html

T 其他语言补充                          60
来源：http://dali.zhoulong.xyz/Article/details/gt2fxxhgyrw.html

U 高频实用片段                         120
来源：http://dali.gzhubu.top/Article/details/gt2mhbdrskm.html

------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gt2wdrirjss.html

合计                                  2106 条
来源：http://dali.jqgfzy.top/Article/details/gt2mlkbruxb.html

--------------------------------------------------------------------------------
来源：http://dali.hammf.cn/Article/details/gt2iuvwiqku.html

使用提醒
来源：http://dali.hysaishi.cn/Article/details/gt2rkjwahmm.html

--------------------------------------------------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gt2qgzuyrua.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hnxiangtu.top/Article/details/gt2rsttprrm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hywenlv.cn/Article/details/gt2hsspydhc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.gzhubu.top/Article/details/gt2sdnodbvu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gyhpxbib.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yj202588.top/Article/details/gt2dezizntl.html

—— 文件结束 ——
来源：http://dali.daxiang520.top/Article/details/gt2ptvryjyp.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2ijyttvgh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.daria6918.cn/Article/details/gt2ojlqfkkr.html

Common Programming Examples Cheat Book
来源：http://dali.birdmap.top/Article/details/gt2xsacigml.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2txgwdgmu.html

【收录内容】
来源：http://dali.birdmap.top/Article/details/gt2ydxjibxu.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhixingplan.top/Article/details/gt2lkxsdrbu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yuanzhike.top/Article/details/gt2mdyylsoq.html

SQL · Bash · C · C++
来源：http://dali.redwolf501.top/Article/details/gt2zmngnzfz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.gogol.net.cn/Article/details/gt2phiegpqk.html

【使用说明】
来源：http://dali.ybcxt.top/Article/details/gt2xhtshqtc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.meibo888.top/Article/details/gt2zapbvvkq.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.cashguo.top/Article/details/gt2sxoxcrxg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hysaishi.cn/Article/details/gt2dbmqqmeh.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yonumen.top/Article/details/gt2mmhtusvy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.guowangkeji.top/Article/details/gt2fylcwvyd.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhoulong.xyz/Article/details/gt2tkdwnlga.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.quarkkingdee.top/Article/details/gt2komwyjba.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yvedp.cn/Article/details/gt2bzakmdzv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.gaohongyu789.top/Article/details/gt2zdgpvidv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.havefunace.top/Article/details/gt2lxvcfutb.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jqgufenzy.top/Article/details/gt2fxqwqqvc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.9152youxi.cn/Article/details/gt2cfjmqjip.html

【文件统计】
来源：http://dali.yangfankeji.com/Article/details/gt2bkcyzjbk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.chenlongwang.top/Article/details/gt2fljdssqb.html

--------------------------------------------------------------------------------
来源：http://dali.jianghu66.top/Article/details/gt2culbkjhn.html

目  录
来源：http://dali.cqqwz.cn/Article/details/gt2lnpnmvss.html

--------------------------------------------------------------------------------
来源：http://dali.havefunace.top/Article/details/gt2hsokclaw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ybcxt.top/Article/details/gt2sozdbkfx.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.nwbrower.top/Article/details/gt2shoqvkwd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cheryme.top/Article/details/gt2pxcxhxcw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zlotnebq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.chenlongwang.top/Article/details/gt2ugaggerr.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hysaishi.cn/Article/details/gt2vgmoumsf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.guannengcc.top/Article/details/gt2tuqhgvzh.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.havefunace.top/Article/details/gt2bglmlcoc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.nwbrower.top/Article/details/gt2bbyrwvnl.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2izdudwty.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gt2medtepso.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2dakvyxhz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2uzqajkkn.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.bjfxy.top/Article/details/gt2okryttgt.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2jncatdeh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gt2lvsbqwil.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.sysykeji.top/Article/details/gt2nvixhcfw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhengqikj.top/Article/details/gt2audmmfem.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.tian-w.cn/Article/details/gt2qnesrmrz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fengsongda.top/Article/details/gt2smuepttw.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2jlwuibqu.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2fwyprgnw.html

A. 基础语法与类型
来源：http://dali.wangdashe.top/Article/details/gt2vcwpbxqo.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2srqmkmng.html

[A01] Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2txeoyfwu.html

Py:   print("Hello, World!")
来源：http://dali.xinyue.icu/Article/details/gt2nvwfsyvc.html

PHP:  echo "Hello, World!";
来源：http://dali.wangshuangyany.cn/Article/details/gt2mvkxmpig.html

JS:   console.log("Hello, World!");
来源：http://dali.xuanzx.com/Article/details/gt2vkqigeqy.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jqgfzy.top/Article/details/gt2rswrpqzi.html

Java: System.out.println("Hello, World!");
来源：http://dali.iojbl.cn/Article/details/gt2mqfdjdpm.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xuanzx.com/Article/details/gt2xtaifjak.html

Ruby: puts "Hello, World!"
来源：http://dali.yangfankeji.com/Article/details/gt2mzmdzaeg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.fzhhl.top/Article/details/gt2thltpkkh.html

[A02] 变量声明与赋值
来源：http://dali.sufxvd.cn/Article/details/gt2zimpdboz.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shzxlz.cn/Article/details/gt2ljxzyzxe.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.chenjidiqi.icu/Article/details/gt2dlekdzut.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.sysykeji.top/Article/details/gt2hrwrgztr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cqqwz.cn/Article/details/gt2tphxxzfq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zycfv.cn/Article/details/gt2gomcwjzk.html

Go:   name := "Alex"; age := 20
来源：http://dali.yueranfly.top/Article/details/gt2iymtowwz.html

Ruby: name = "Alex"; age = 20
来源：http://dali.c1oappe.top/Article/details/gt2zmzeulag.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yuanzhike.top/Article/details/gt2txtmmpwv.html

[A03] 常量定义
来源：http://dali.svipenyu.cn/Article/details/gt2dxdisuab.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhiwuduotai.top/Article/details/gt2efgixnnp.html

PHP:  const PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gt2mklartxb.html

JS:   const PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gt2altsctof.html

TS:   const PI: number = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gt2hywvsocg.html

Java: static final double PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nvlvyanp.html

Go:   const PI = 3.14159
来源：http://dali.dashuyun.cn/Article/details/gt2ldliugsm.html

Ruby: PI = 3.14159
来源：http://dali.birdmap.top/Article/details/gt2whgfnzja.html

C#:   const double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gt2rchumufy.html

[A04] 判断变量类型
来源：http://dali.zycfv.cn/Article/details/gt2jmlijvjw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.nanxinkj.top/Article/details/gt2ixucmhwo.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ezdzjjam.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oggidgpe.html

TS:   typeof x; x instanceof Date
来源：http://dali.mhx1999.top/Article/details/gt2syeksali.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.sweek.top/Article/details/gt2xambpknm.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.haohaochexian.top/Article/details/gt2wxjjxfui.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.iojbl.cn/Article/details/gt2mnumxqws.html

C#:   x.GetType().Name; x is int
来源：http://dali.fengsongda.top/Article/details/gt2olgrxafl.html

[A05] 整数除法与取模
来源：http://dali.zhengqikj.top/Article/details/gt2vmzufmgj.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yj202588.top/Article/details/gt2cnvfqejv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gt2mfnvuyoi.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aizwys.cn/Article/details/gt2zjxsfmmw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tian-w.cn/Article/details/gt2fbfccsex.html

Java: 7 / 2; 7 % 2
来源：http://dali.guowangkeji.top/Article/details/gt2kpxlrusi.html

Go:   7 / 2; 7 % 2
来源：http://dali.yj202588.top/Article/details/gt2tbacvcsd.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gt2ymzkjkha.html

C#:   7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gt2msvdnhac.html

[A06] 字符串转数字
来源：http://dali.birdmap.top/Article/details/gt2yvwitvep.html

Py:   int("42"); float("3.14")
来源：http://dali.ybcxt.top/Article/details/gt2ayiveawz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.ppjwa.cn/Article/details/gt2tqpstyrc.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2slytzaqr.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.quarkkingdee.top/Article/details/gt2vwruslai.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.andypj.xyz/Article/details/gt2bweokbfy.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hysaishi.cn/Article/details/gt2dtsbrcsl.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.birdmap.top/Article/details/gt2mbftsbdt.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.chenjidiqi.icu/Article/details/gt2qblbmcnj.html

[A07] 数字转字符串
来源：http://dali.ppjwa.cn/Article/details/gt2ouhkdlxi.html

Py:   str(42)
来源：http://dali.ivvv.top/Article/details/gt2lennteux.html

PHP:  (string) 42; strval(42)
来源：http://dali.jinqigufen.top/Article/details/gt2anjwstgz.html

JS:   String(42); (42).toString()
来源：http://dali.gogol.net.cn/Article/details/gt2zinemidu.html

TS:   String(42)
来源：http://dali.smart0.xyz/Article/details/gt2jkebmnyg.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zdqjudy.top/Article/details/gt2nhcrwktn.html

Go:   strconv.Itoa(42)
来源：http://dali.zycfv.cn/Article/details/gt2wxlubsee.html

Ruby: 42.to_s
来源：http://dali.tianlin.xyz/Article/details/gt2nyxnhzah.html

C#:   42.ToString()
来源：http://dali.zdqjudy.top/Article/details/gt2dikbvfix.html

[A08] 取整与四舍五入
来源：http://dali.cashguo.top/Article/details/gt2yfuqrzmf.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2maxvskxw.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhongyouzk.top/Article/details/gt2qriurpvx.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.redwolf501.top/Article/details/gt2egzlwqmn.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jqgfzy.top/Article/details/gt2ktewsqvg.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.svipenyu.cn/Article/details/gt2qjsxhptd.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.shzxlz.cn/Article/details/gt2btpnfanv.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.gzhubu.top/Article/details/gt2viorvdnb.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.snrcjt.cn/Article/details/gt2nnstcucu.html

[A09] 绝对值与最大最小值
来源：http://dali.kuanghao11.cn/Article/details/gt2zvjmatzi.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2myxmvwol.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.smart0.xyz/Article/details/gt2fbwfoihv.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gt2sxonlyku.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gt2vxtqgvug.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.sysykeji.top/Article/details/gt2pyhmwmpm.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.quarkkingdee.top/Article/details/gt2yhexxszl.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.redwolf501.top/Article/details/gt2zdxulxea.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.meibo888.top/Article/details/gt2hdkwtlor.html

[A10] 生成随机数
来源：http://dali.jyoumei.cn/Article/details/gt2aafxbbqx.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhengqikj.top/Article/details/gt2ilpryjrz.html

PHP:  random_int(1, 100);
来源：http://dali.tianlin.xyz/Article/details/gt2hghtvixu.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.pycfn.com/Article/details/gt2opyfulsr.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.guowangkeji.top/Article/details/gt2cawosecf.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yj20258888.top/Article/details/gt2lvsqgiiy.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.cucudq.cn/Article/details/gt2xfopqzju.html

Ruby: rand(1..100)
来源：http://dali.gogol.net.cn/Article/details/gt2deikudeh.html

C#:   new Random().Next(1, 101)
来源：http://dali.cdnleiting.top/Article/details/gt2okiqqyyp.html

[A11] 条件表达式（三元）
来源：http://dali.xinyue.icu/Article/details/gt2kzfsstle.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhixingplan.top/Article/details/gt2qohxqxno.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.feifeiyinyue.top/Article/details/gt2ilwemapl.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zdqjudy.top/Article/details/gt2hkrtjbyf.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhengqikj.top/Article/details/gt2mccfhjei.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhongyouzk.top/Article/details/gt2vnyoszqt.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.tianlin.xyz/Article/details/gt2argskydy.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.sysykeji.top/Article/details/gt2gvkycqcm.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.pengpengdd.cyou/Article/details/gt2rqjaqpdg.html

[A12] 字符串插值 / 格式化
来源：http://dali.tianlin.xyz/Article/details/gt2osuqfxau.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.meibo888.top/Article/details/gt2lnigjbuv.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zdqjudy.top/Article/details/gt2vyrhebjo.html

JS:   `Hello, ${name}!`
来源：http://dali.vqdsnc.cn/Article/details/gt2avaisimx.html

TS:   `Hello, ${name}!`
来源：http://dali.xuanzx.com/Article/details/gt2gopxhhfc.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.cqqwz.cn/Article/details/gt2dwxakmhl.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yj20258888.top/Article/details/gt2juznmqpn.html

Ruby: "Hello, #{name}!"
来源：http://dali.jiagoushi.top/Article/details/gt2eymhrahr.html

C#:   $"Hello, {name}!"
来源：http://dali.andypj.xyz/Article/details/gt2yoikdtyg.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.sysykeji.top/Article/details/gt2ojvltmml.html

Py:   "第一行\n第二行"
来源：http://dali.shzxlz.cn/Article/details/gt2grtwaurm.html

PHP:  "第一行\n第二行"
来源：http://dali.ivvv.top/Article/details/gt2xqejxumu.html

JS:   "第一行\n第二行"
来源：http://dali.ehwqpu.com/Article/details/gt2mxldtdpz.html

TS:   "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gt2mvnpazxg.html

Java: "第一行\n第二行"
来源：http://dali.zhongyouzk.top/Article/details/gt2xwraxepu.html

Go:   "第一行\n第二行"
来源：http://dali.shzxlz.cn/Article/details/gt2ckkhgyxc.html

Ruby: "第一行\n第二行"
来源：http://dali.xinyue.icu/Article/details/gt2ilhibubs.html

C#:   "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cngolkas.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2uyecppsi.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.xinyue.icu/Article/details/gt2ffzqtlvf.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.pycfn.com/Article/details/gt2bnxmaesw.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhongyouzk.top/Article/details/gt2sgjyijlt.html

TS:   // 单行；/* 多行 */
来源：http://dali.kuanghao11.cn/Article/details/gt2oyjmzyon.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yangfankeji.com/Article/details/gt2zxffbpru.html

Go:   // 单行；/* 多行 */
来源：http://dali.hfpthk.cn/Article/details/gt2lafpnntb.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hammf.cn/Article/details/gt2udjehqpe.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhiwuduotai.top/Article/details/gt2nmwkkrpz.html

[A15] 空值判断与默认值
来源：http://dali.pycfn.com/Article/details/gt2vwfltubd.html

Py:   value = data or "默认值"
来源：http://dali.yvedp.cn/Article/details/gt2qjrnwpcu.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.316326.xyz/Article/details/gt2futrlrsi.html

JS:   const value = data ?? "默认值";
来源：http://dali.chenlongwang.top/Article/details/gt2crbmnayl.html

TS:   const value = data ?? "默认值";
来源：http://dali.aizwys.cn/Article/details/gt2gpzfmvdk.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.birdmap.top/Article/details/gt2dggbjkgf.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shzxlz.cn/Article/details/gt2bqhviigc.html

Ruby: value = data || "默认值"
来源：http://dali.mhx1999.top/Article/details/gt2iyasowom.html

C#:   var value = data ?? "默认值";
来源：http://dali.chenzaomai.com/Article/details/gt2nnggjpse.html

[A16] 真假值判断规则
来源：http://dali.jyoumei.cn/Article/details/gt2dqmnwfqh.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.gotoacloud.top/Article/details/gt2hdjmjast.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xuetiantiany.cn/Article/details/gt2fyumovwi.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.nanxuanxn.top/Article/details/gt2rwygehdi.html

TS:   if (!x) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2aokgqnkj.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2aoegoqud.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.0kj1m.cn/Article/details/gt2dnnsvkck.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhixingplan.top/Article/details/gt2msxoimyo.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jianghu66.top/Article/details/gt2aqfplnzm.html

[A17] 位运算
来源：http://dali.cdnleiting.top/Article/details/gt2frxarobz.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgufenzy.top/Article/details/gt2ylubyvmo.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.havefunace.top/Article/details/gt2evjeftgy.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gt2rutzvkek.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2axsbndxu.html


<!-- 参考信息 -->