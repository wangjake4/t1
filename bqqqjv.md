代发 wailian999

[U97] JS：并发请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mcmidpqe.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gt2jqvzsesb.html

[U98] JS：fetch 带 JSON
来源：http://dali.yongpay.top/Article/details/gt2dclxtuks.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.dashuyun.cn/Article/details/gt2umzpbwqc.html

[U99] JS：事件监听
来源：http://dali.wangshuangyany.cn/Article/details/gt2xwujujzb.html

el.addEventListener("click", e => {})
来源：http://dali.zhongyouzk.top/Article/details/gt2uocejbiu.html

[U100] JS：DOM 查询
来源：http://dali.hnqzz.top/Article/details/gt2ludwxegs.html

document.querySelector(".item")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ovenlaon.html

[U101] JS：classList 操作
来源：http://dali.meibo888.top/Article/details/gt2vljifhrn.html

el.classList.toggle("active")
来源：http://dali.ehwqpu.com/Article/details/gt2nhvviuxh.html

[U102] JS：本地存储
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2svbyfqbp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.vqdsnc.cn/Article/details/gt2sdvlbypw.html

[U103] JS：定时器
来源：http://dali.yj202588.top/Article/details/gt2igtqlrvw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.nanxinkj.top/Article/details/gt2erkfurhh.html

[U104] JS：防抖
来源：http://dali.ydzc1.top/Article/details/gt2jfldwbyi.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2czajbgmn.html

[U105] JS：节流
来源：http://dali.daria6918.cn/Article/details/gt2yrzfjuib.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ppjwa.cn/Article/details/gt2swloxwij.html

[U106] JS：日期格式化
来源：http://dali.sufxvd.cn/Article/details/gt2zzhrtegd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.9152youxi.cn/Article/details/gt2uevwigsu.html

[U107] JS：数字千分位
来源：http://dali.wangdashe.top/Article/details/gt2euslovnw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.chenzaomai.com/Article/details/gt2sjduoxyu.html

[U108] JS：随机整数
来源：http://dali.ivvv.top/Article/details/gt2qnwkwhdp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xuetiantiany.cn/Article/details/gt2nojxxzfm.html

[U109] JS：数组分组
来源：http://dali.yangfankeji.com/Article/details/gt2ntsgvrcu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xuanzx.com/Article/details/gt2uacajgsc.html

[U110] JS：数组分块
来源：http://dali.kuanghao11.cn/Article/details/gt2xhcbjiuc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gaohongyu789.top/Article/details/gt2puqykbtr.html

[U111] JS：对象转 Map
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gclfzwfd.html

new Map(Object.entries(obj))
来源：http://dali.shzxlz.cn/Article/details/gt2lxdvhcdg.html

[U112] JS：字符串补位
来源：http://dali.tianlin.xyz/Article/details/gt2yqudktyb.html

"7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gt2jbuunocd.html

[U113] JS：正则替换全部
来源：http://dali.dianchejie.cn/Article/details/gt2mkpahjua.html

s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2ybjapdvf.html

[U114] JS：JSON 深比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2xnfaesww.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.smart0.xyz/Article/details/gt2fxtoegmt.html

[U115] JS：生成 UUID
来源：http://dali.zhiwuduotai.top/Article/details/gt2wfandapb.html

crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gt2tjftodxl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.dianchejie.cn/Article/details/gt2mdtjodso.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jyoumei.cn/Article/details/gt2aprwjphx.html

[U117] JS：单元测试
来源：http://dali.birdmap.top/Article/details/gt2tdwgqlgu.html

npm i -D vitest;  npx vitest
来源：http://dali.quarkkingdee.top/Article/details/gt2lgogcofc.html

[U118] JS：开发服务器
来源：http://dali.guannengcc.top/Article/details/gt2bzcwvxmz.html

npm i -D vite;  npx vite
来源：http://dali.wangdashe.top/Article/details/gt2gvfybcgf.html

[U119] JS：生产构建
来源：http://dali.jqgufenzy.top/Article/details/gt2duevtruz.html

npx vite build
来源：http://dali.gogol.net.cn/Article/details/gt2jerqscdm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jqgfzy.top/Article/details/gt2hidebeht.html

import.meta.env.VITE_API_URL
来源：http://dali.yvedp.cn/Article/details/gt2ghrpabhk.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2pofaczlf.html

统计汇总
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jzofhyyj.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2cqnmrhwi.html

按语言统计（条）：
来源：http://dali.andypj.xyz/Article/details/gt2jxevrdpc.html

Python ......... 252
来源：http://dali.jyoumei.cn/Article/details/gt2rcswxhpu.html

PHP ............ 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pgewxfat.html

JavaScript ..... 252
来源：http://dali.tian-w.cn/Article/details/gt2tmfbusqg.html

TypeScript ..... 212
来源：http://dali.quarkkingdee.top/Article/details/gt2vfvhqrkk.html

Java ........... 212
来源：http://dali.ppjwa.cn/Article/details/gt2wtaiugtm.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlmmcfy.html

Ruby ........... 212
来源：http://dali.aibaodan.cn/Article/details/gt2ximmiwoi.html

C# ............. 212
来源：http://dali.havefunace.top/Article/details/gt2ewogjgre.html

C .............. 30
来源：http://dali.shzxlz.cn/Article/details/gt2macsgskw.html

C++ ............ 30
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mmgsxdkt.html

SQL ............ 90
来源：http://dali.yvedp.cn/Article/details/gt2tikityws.html

Bash ........... 80
来源：http://dali.quarkkingdee.top/Article/details/gt2snxbbtpq.html

Kotlin ......... 15
来源：http://dali.cheryme.top/Article/details/gt2knbmnwtz.html

Swift .......... 15
来源：http://dali.yangfankeji.com/Article/details/gt2bjqeoqaj.html

Lua ............ 10
来源：http://dali.vqdsnc.cn/Article/details/gt2pcuqzevq.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrfrdbt.html

Scala .......... 10
来源：http://dali.jyoumei.cn/Article/details/gt2olpuhxik.html

------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gt2rcenlqvg.html

合计 ........... 2106 条
来源：http://dali.ppjwa.cn/Article/details/gt2eyzswmcb.html

按章节统计：
来源：http://dali.cucudq.cn/Article/details/gt2dzyqapli.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.dashuyun.cn/Article/details/gt2tvdlfaqi.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ehwqpu.com/Article/details/gt2lrekqsqx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.nanxuanxn.top/Article/details/gt2ubrawtha.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yanxiufei.cn/Article/details/gt2rafvsbas.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cashguo.top/Article/details/gt2nsrxdwrj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.nanxinkj.top/Article/details/gt2uqcipvgs.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gogol.net.cn/Article/details/gt2qchtmsyh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yj20258888.top/Article/details/gt2afntmjmd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gt2ohkblzeb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhoulong.xyz/Article/details/gt2salivked.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gt2pcqkqqvq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gt2fqlptwdn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.feifeiyinyue.top/Article/details/gt2vezkpmej.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.guowangkeji.top/Article/details/gt2nzzoosig.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cdnleiting.top/Article/details/gt2fcwgpnhs.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hrcmhzjt.html

Q SQL 专题                              90
来源：http://dali.jlsjyb.cn/Article/details/gt2ifbosrts.html

R Bash 专题                             80
来源：http://dali.tanke756.top/Article/details/gt2skvrakds.html

S C / C++ 专题                          60
来源：http://dali.zhengqikj.top/Article/details/gt2gojpkhmk.html

T 其他语言补充                          60
来源：http://dali.yonumen.top/Article/details/gt2usiembqp.html

U 高频实用片段                         120
来源：http://dali.cheryme.top/Article/details/gt2dklxucay.html

------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gt2qfivltak.html

合计                                  2106 条
来源：http://dali.hongshengwenyu.top/Article/details/gt2mgwbrgyy.html

--------------------------------------------------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gt2hfbmsvbx.html

使用提醒
来源：http://dali.zdqjudy.top/Article/details/gt2psexfquh.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gt2trqqiiav.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.smart0.xyz/Article/details/gt2ciryjfvg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.havefunace.top/Article/details/gt2lefvtaur.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yueranfly.top/Article/details/gt2cafzdszd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jlsjyb.cn/Article/details/gt2ftcjdwsv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.chenzaomai.com/Article/details/gt2thkexicz.html

—— 文件结束 ——
来源：http://dali.sufxvd.cn/Article/details/gt2ikzwhklq.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2nthgaygq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.bjfxy.top/Article/details/gt2zyomciaj.html

Common Programming Examples Cheat Book
来源：http://dali.nanxinkj.top/Article/details/gt2cjmmzhby.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2aeftyjkb.html

【收录内容】
来源：http://dali.meibo888.top/Article/details/gt2wltyknrm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.guannengcc.top/Article/details/gt2ftdxhnlh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.redwolf501.top/Article/details/gt2hdfmhhsw.html

SQL · Bash · C · C++
来源：http://dali.zycfv.cn/Article/details/gt2bykssmby.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xgsshwhu.html

【使用说明】
来源：http://dali.cheryme.top/Article/details/gt2lciqvtac.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.pycfn.com/Article/details/gt2pqmkfhvf.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.quarkkingdee.top/Article/details/gt2rhlvohzi.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yvedp.cn/Article/details/gt2hyvvvgje.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xziqi.cn/Article/details/gt2kfneqbrk.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.gogol.net.cn/Article/details/gt2ojaggqrg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jiagoushi.top/Article/details/gt2tborejpz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.daria6918.cn/Article/details/gt2dxnewcwm.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xylfe.cn/Article/details/gt2fmuibshd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.316326.xyz/Article/details/gt2sazdgubu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cqqwz.cn/Article/details/gt2thrqbfst.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yongpay.top/Article/details/gt2cwqudedt.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.smart0.xyz/Article/details/gt2glhljojq.html

【文件统计】
来源：http://dali.hnqzz.top/Article/details/gt2faqbwarb.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jinqigfzy.top/Article/details/gt2mjwfsnke.html

--------------------------------------------------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gt2vzjobain.html

目  录
来源：http://dali.tianlin.xyz/Article/details/gt2bfkcomqz.html

--------------------------------------------------------------------------------
来源：http://dali.daria6918.cn/Article/details/gt2jhbriuce.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2giobfelq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.316326.xyz/Article/details/gt2ygucvecz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.gotoacloud.top/Article/details/gt2abbrptdk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wfpkoyhf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.daria6918.cn/Article/details/gt2uoloyjhu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xuanzx.com/Article/details/gt2rqvqyagz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.sxryk.cn/Article/details/gt2addwvadp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ybcxt.top/Article/details/gt2dwtqztku.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gt2eutecmzl.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.fengsongda.top/Article/details/gt2pztkokkg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gt2howjntqy.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.gotoacloud.top/Article/details/gt2ytcwowta.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vagpjift.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.nanxinkj.top/Article/details/gt2ijrallmr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yonumen.top/Article/details/gt2mvuhuxih.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2bvuabogi.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.nanxinkj.top/Article/details/gt2vwlmrarw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.nanxinkj.top/Article/details/gt2jsrlnssk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yongpay.top/Article/details/gt2ukrsnmgr.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cqqwz.cn/Article/details/gt2yghtgxkw.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sysykeji.top/Article/details/gt2dysmndsk.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2vcdehfxe.html

A. 基础语法与类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2bpodjfrc.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2gqquipov.html

[A01] Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ticvrxur.html

Py:   print("Hello, World!")
来源：http://dali.c1oappe.top/Article/details/gt2jmbwvgnr.html

PHP:  echo "Hello, World!";
来源：http://dali.yuxming.cn/Article/details/gt2ivvketal.html

JS:   console.log("Hello, World!");
来源：http://dali.nanxinkj.top/Article/details/gt2ebvwxhch.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.fengsongda.top/Article/details/gt2bwfspboo.html

Java: System.out.println("Hello, World!");
来源：http://dali.gzhubu.top/Article/details/gt2hgnmdzsy.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sweek.top/Article/details/gt2mzoqoyxo.html

Ruby: puts "Hello, World!"
来源：http://dali.daxiang520.top/Article/details/gt2tjktyjhz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.shuidangran.top/Article/details/gt2sgaubwqf.html

[A02] 变量声明与赋值
来源：http://dali.haohaochexian.top/Article/details/gt2vruclywz.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cucudq.cn/Article/details/gt2rvyobvrx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yueranfly.top/Article/details/gt2lykihzld.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvhidjaa.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.haohaochexian.top/Article/details/gt2eywherym.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.nanxinkj.top/Article/details/gt2nntjvpii.html

Go:   name := "Alex"; age := 20
来源：http://dali.nanxinkj.top/Article/details/gt2otolaszt.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gotoacloud.top/Article/details/gt2obcrdkaa.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.kuanghao11.cn/Article/details/gt2knjkglmd.html

[A03] 常量定义
来源：http://dali.pycfn.com/Article/details/gt2ywwzvfvj.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.pengpengdd.cyou/Article/details/gt2aardrxdw.html

PHP:  const PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gt2fniffjyl.html

JS:   const PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gt2pvzolqwi.html

TS:   const PI: number = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gt2kevfunil.html

Java: static final double PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gt2tddharhi.html

Go:   const PI = 3.14159
来源：http://dali.dianchejie.cn/Article/details/gt2zaejorlt.html

Ruby: PI = 3.14159
来源：http://dali.yangfankeji.com/Article/details/gt2fxgjmxvw.html

C#:   const double PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gt2epqzpdsp.html

[A04] 判断变量类型
来源：http://dali.redwolf501.top/Article/details/gt2orsonzyp.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yuanzhike.top/Article/details/gt2tjuweygx.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yanxiufei.cn/Article/details/gt2hgrphesf.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.aibaodan.cn/Article/details/gt2mcalxwvk.html

TS:   typeof x; x instanceof Date
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nrmqjprc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yj20258888.top/Article/details/gt2phbawnqg.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rtpzkpuc.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jqgufenzy.top/Article/details/gt2lwvaczon.html

C#:   x.GetType().Name; x is int
来源：http://dali.xuetiantiany.cn/Article/details/gt2ivrovkye.html

[A05] 整数除法与取模
来源：http://dali.sxryk.cn/Article/details/gt2dwfquagz.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.gzhubu.top/Article/details/gt2nuecdoem.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.cashguo.top/Article/details/gt2gtjpjpfi.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uvunqdtt.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sysykeji.top/Article/details/gt2zfbqkptq.html

Java: 7 / 2; 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2scsicxzv.html

Go:   7 / 2; 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gt2vovaubie.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.wangdashe.top/Article/details/gt2wphfwtus.html

C#:   7 / 2; 7 % 2
来源：http://dali.fengsongda.top/Article/details/gt2blrghyoh.html

[A06] 字符串转数字
来源：http://dali.sufxvd.cn/Article/details/gt2oupmnkgo.html

Py:   int("42"); float("3.14")
来源：http://dali.yanxiufei.cn/Article/details/gt2iplfeizr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.mhx1999.top/Article/details/gt2cnhbvlvl.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ivvv.top/Article/details/gt2wqaszjed.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.chenzaomai.com/Article/details/gt2qprofrbz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.meibo888.top/Article/details/gt2mhwaqpgn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.xziqi.cn/Article/details/gt2afyxggtb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.xinyue.icu/Article/details/gt2nfizgkrt.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hywenlv.cn/Article/details/gt2ysdnotkv.html

[A07] 数字转字符串
来源：http://dali.tanke756.top/Article/details/gt2mvypmolo.html

Py:   str(42)
来源：http://dali.yj202588.top/Article/details/gt2hvvlabkf.html

PHP:  (string) 42; strval(42)
来源：http://dali.chenzaomai.com/Article/details/gt2gxsrufyn.html

JS:   String(42); (42).toString()
来源：http://dali.sufxvd.cn/Article/details/gt2xppkdgks.html

TS:   String(42)
来源：http://dali.yj20258.top/Article/details/gt2ayberrou.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jiagoushi.top/Article/details/gt2wcurgqog.html

Go:   strconv.Itoa(42)
来源：http://dali.sufxvd.cn/Article/details/gt2tykvhqls.html

Ruby: 42.to_s
来源：http://dali.nanxuanxn.top/Article/details/gt2vvwfurey.html

C#:   42.ToString()
来源：http://dali.yueranfly.top/Article/details/gt2bqcmxwpt.html

[A08] 取整与四舍五入
来源：http://dali.xziqi.cn/Article/details/gt2ulssxhxb.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ivvv.top/Article/details/gt2mhyndbuw.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zolfwedg.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2voponltw.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.cqqwz.cn/Article/details/gt2ydqmwulm.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.gogol.net.cn/Article/details/gt2zssqunzt.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yongpay.top/Article/details/gt2vwwzhtnn.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qdgobyhe.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gt2ebdjvpvh.html

[A09] 绝对值与最大最小值
来源：http://dali.nanxuanxn.top/Article/details/gt2cduxwtjh.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2qwluwrkb.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.fengsongda.top/Article/details/gt2gjdlaksq.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.wangdashe.top/Article/details/gt2wicuaiua.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2aqtgvial.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.tian-w.cn/Article/details/gt2rxnczrza.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.nwbrower.top/Article/details/gt2nhxgyhzm.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.vqdsnc.cn/Article/details/gt2dmwhrgtm.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.andypj.xyz/Article/details/gt2nbfoxhro.html

[A10] 生成随机数
来源：http://dali.vqdsnc.cn/Article/details/gt2ggrsljvj.html

Py:   import random; random.randint(1, 100)
来源：http://dali.chenjidiqi.icu/Article/details/gt2iyukuiaa.html

PHP:  random_int(1, 100);
来源：http://dali.hnqzz.top/Article/details/gt2kdsdxcso.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.9152youxi.cn/Article/details/gt2mvcwvobb.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.daria6918.cn/Article/details/gt2tlatnrnl.html

Java: new Random().nextInt(100) + 1
来源：http://dali.0kj1m.cn/Article/details/gt2nhftltul.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jlsjyb.cn/Article/details/gt2xwuvlvox.html

Ruby: rand(1..100)
来源：http://dali.hnxiangtu.top/Article/details/gt2xpvsshtb.html

C#:   new Random().Next(1, 101)
来源：http://dali.yongpay.top/Article/details/gt2nzkqxmsg.html

[A11] 条件表达式（三元）
来源：http://dali.hfpthk.cn/Article/details/gt2znebhiwq.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.ydzc1.top/Article/details/gt2nqeyphaq.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.xuetiantiany.cn/Article/details/gt2atcufevx.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhixingplan.top/Article/details/gt2epcvulyo.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.havefunace.top/Article/details/gt2mskrurmx.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.meibo888.top/Article/details/gt2cvuixzqg.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.aibaodan.cn/Article/details/gt2iprxtxsq.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jqgfzy.top/Article/details/gt2jfxvmaug.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.sysykeji.top/Article/details/gt2laobfuzw.html

[A12] 字符串插值 / 格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mhznzpzd.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.ydzc1.top/Article/details/gt2nnfnamqy.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.c1oappe.top/Article/details/gt2jeoppnlb.html

JS:   `Hello, ${name}!`
来源：http://dali.nwbrower.top/Article/details/gt2qqzxpbvq.html

TS:   `Hello, ${name}!`
来源：http://dali.xylfe.cn/Article/details/gt2jfiesilq.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.shuidangran.top/Article/details/gt2njhgpomv.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.svipenyu.cn/Article/details/gt2ddgzblrc.html

Ruby: "Hello, #{name}!"
来源：http://dali.chenlongwang.top/Article/details/gt2vfvghmlr.html

C#:   $"Hello, {name}!"
来源：http://dali.gotoacloud.top/Article/details/gt2erhgyifx.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.ybcxt.top/Article/details/gt2tzlaxyky.html

Py:   "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gt2fowrijcv.html

PHP:  "第一行\n第二行"
来源：http://dali.c1oappe.top/Article/details/gt2ctmigmzr.html

JS:   "第一行\n第二行"
来源：http://dali.wangdashe.top/Article/details/gt2vcbwtuqr.html

TS:   "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gt2xbhhtxyv.html

Java: "第一行\n第二行"
来源：http://dali.fzhhl.top/Article/details/gt2ibpxybxe.html

Go:   "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gt2lszrjarg.html

Ruby: "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gt2yuorgmvf.html

C#:   "第一行\n第二行"
来源：http://dali.jqgfzy.top/Article/details/gt2pevhweda.html

[A14] 注释写法
来源：http://dali.jinqigufen.top/Article/details/gt2hmcvovtj.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yvedp.cn/Article/details/gt2hxlfolfh.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.gotoacloud.top/Article/details/gt2pieprqed.html

JS:   // 单行；/* 多行 */
来源：http://dali.jinqigufen.top/Article/details/gt2zppuygud.html

TS:   // 单行；/* 多行 */
来源：http://dali.pengpengdd.cyou/Article/details/gt2vhblduza.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.tian-w.cn/Article/details/gt2kzsxeipx.html

Go:   // 单行；/* 多行 */
来源：http://dali.c1oappe.top/Article/details/gt2rpofkiuk.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.ybcxt.top/Article/details/gt2incxoidm.html

C#:   // 单行；/* 多行 */
来源：http://dali.cdnleiting.top/Article/details/gt2jntpkhal.html

[A15] 空值判断与默认值
来源：http://dali.cqqwz.cn/Article/details/gt2gcjkjtfs.html

Py:   value = data or "默认值"
来源：http://dali.yuanzhike.top/Article/details/gt2yxonxfcl.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.pycfn.com/Article/details/gt2bijkcwjq.html

JS:   const value = data ?? "默认值";
来源：http://dali.gogol.net.cn/Article/details/gt2pxetvzig.html

TS:   const value = data ?? "默认值";
来源：http://dali.cucudq.cn/Article/details/gt2lvoecevb.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.hysaishi.cn/Article/details/gt2ywqovalv.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jinqigufen.top/Article/details/gt2eulbyfxs.html

Ruby: value = data || "默认值"
来源：http://dali.jiagoushi.top/Article/details/gt2hwvtrzqw.html

C#:   var value = data ?? "默认值";
来源：http://dali.nanxinkj.top/Article/details/gt2hhdfdyrh.html

[A16] 真假值判断规则
来源：http://dali.chenzaomai.com/Article/details/gt2xckklulb.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.nwbrower.top/Article/details/gt2sbzwzksn.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.shzxlz.cn/Article/details/gt2ylivimoi.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.shuidangran.top/Article/details/gt2qqleqspv.html

TS:   if (!x) {}
来源：http://dali.havefunace.top/Article/details/gt2jmrnjrgv.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yangfankeji.com/Article/details/gt2zftrcelg.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.hnqzz.top/Article/details/gt2qhjovzyn.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.hnxiangtu.top/Article/details/gt2xrewlfyb.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yuxming.cn/Article/details/gt2fedulovu.html

[A17] 位运算
来源：http://dali.haohaochexian.top/Article/details/gt2pvfagzsl.html


<!-- 参考信息 -->