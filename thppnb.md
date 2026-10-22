代发 wailian999

[U97] JS：并发请求
来源：http://dali.nanxinkj.top/Article/details/gtbmdkgtdm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.mhx1999.top/Article/details/gtbtgwzzra.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gtwumczdbe.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jianghu66.top/Article/details/gtxmqebidh.html

[U99] JS：事件监听
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnszrtufz.html

el.addEventListener("click", e => {})
来源：http://dali.mhx1999.top/Article/details/gtggbpbcda.html

[U100] JS：DOM 查询
来源：http://dali.mhx1999.top/Article/details/gtgbnponla.html

document.querySelector(".item")
来源：http://dali.daria6918.cn/Article/details/gtbdbnyokr.html

[U101] JS：classList 操作
来源：http://dali.gogol.net.cn/Article/details/gtwqxseohs.html

el.classList.toggle("active")
来源：http://dali.yuxming.cn/Article/details/gtvkmywill.html

[U102] JS：本地存储
来源：http://dali.jinqigfzy.top/Article/details/gthevurrev.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfcsidine.html

[U103] JS：定时器
来源：http://dali.0kj1m.cn/Article/details/gtuczlpzhz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpydliiyy.html

[U104] JS：防抖
来源：http://dali.cashguo.top/Article/details/gtepevfsfb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtncoylpvz.html

[U105] JS：节流
来源：http://dali.zhiwuduotai.top/Article/details/gtvlizsknj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jinqigufen.top/Article/details/gtiptmregy.html

[U106] JS：日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gtitorzmtq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hnqzz.top/Article/details/gtltywrdnt.html

[U107] JS：数字千分位
来源：http://dali.9152youxi.cn/Article/details/gtivdlwewy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinqigufen.top/Article/details/gtmtwhpyuc.html

[U108] JS：随机整数
来源：http://dali.hysaishi.cn/Article/details/gthforwndi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.tian-w.cn/Article/details/gtndlsgstp.html

[U109] JS：数组分组
来源：http://dali.guowangkeji.top/Article/details/gtcahimptf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gtabqgaldu.html

[U110] JS：数组分块
来源：http://dali.ehwqpu.com/Article/details/gtvrxvbaxo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yuxming.cn/Article/details/gtwupovzki.html

[U111] JS：对象转 Map
来源：http://dali.yongpay.top/Article/details/gtwvihtewm.html

new Map(Object.entries(obj))
来源：http://dali.yj202588.top/Article/details/gtubwkqsyu.html

[U112] JS：字符串补位
来源：http://dali.kuanghao11.cn/Article/details/gtjqwvlkmq.html

"7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtojswibbu.html

[U113] JS：正则替换全部
来源：http://dali.zhixingplan.top/Article/details/gtunkjaxbr.html

s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtidnyrbcc.html

[U114] JS：JSON 深比较
来源：http://dali.dashuyun.cn/Article/details/gtgseoiqxg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangdashe.top/Article/details/gtamwrnryk.html

[U115] JS：生成 UUID
来源：http://dali.redwolf501.top/Article/details/gtuczkvovu.html

crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gtaqrcdojl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhengqikj.top/Article/details/gtxcdieglv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jianghu66.top/Article/details/gtqsyppnoh.html

[U117] JS：单元测试
来源：http://dali.hongshengwenyu.top/Article/details/gtgxallqfh.html

npm i -D vitest;  npx vitest
来源：http://dali.ybcxt.top/Article/details/gtoykcnniq.html

[U118] JS：开发服务器
来源：http://dali.cqqwz.cn/Article/details/gtyzuymjen.html

npm i -D vite;  npx vite
来源：http://dali.redwolf501.top/Article/details/gtzafbezwe.html

[U119] JS：生产构建
来源：http://dali.guowangkeji.top/Article/details/gtyifxqrmy.html

npx vite build
来源：http://dali.chenjidiqi.icu/Article/details/gteudpmzyd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jiagoushi.top/Article/details/gtfnzslqsk.html

import.meta.env.VITE_API_URL
来源：http://dali.cheryme.top/Article/details/gtljgpmcgx.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtbwqxxadg.html

统计汇总
来源：http://dali.gzhubu.top/Article/details/gtoxykqbof.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtscbbsdij.html

按语言统计（条）：
来源：http://dali.shangyingyoupin.top/Article/details/gtmeneuhza.html

Python ......... 252
来源：http://dali.zycfv.cn/Article/details/gtgvsuxzhf.html

PHP ............ 252
来源：http://dali.zhoulong.xyz/Article/details/gtwomhirnt.html

JavaScript ..... 252
来源：http://dali.hammf.cn/Article/details/gtbegovvez.html

TypeScript ..... 212
来源：http://dali.cqqwz.cn/Article/details/gtawcdgwuo.html

Java ........... 212
来源：http://dali.gotoacloud.top/Article/details/gtmtzsohoz.html

Go ............. 212
来源：http://dali.hnxiangtu.top/Article/details/gtwdxluegp.html

Ruby ........... 212
来源：http://dali.shuidangran.top/Article/details/gtyknymwpw.html

C# ............. 212
来源：http://dali.chenzaomai.com/Article/details/gtdylrccft.html

C .............. 30
来源：http://dali.vqdsnc.cn/Article/details/gtyvwctxmb.html

C++ ............ 30
来源：http://dali.nwbrower.top/Article/details/gtonechxoz.html

SQL ............ 90
来源：http://dali.iojbl.cn/Article/details/gtgtxuaxan.html

Bash ........... 80
来源：http://dali.aizwys.cn/Article/details/gtyassbbrb.html

Kotlin ......... 15
来源：http://dali.jqgfzy.top/Article/details/gtljuwnffv.html

Swift .......... 15
来源：http://dali.yuxming.cn/Article/details/gtmdoagthy.html

Lua ............ 10
来源：http://dali.hfpthk.cn/Article/details/gtymhepulq.html

Perl ........... 10
来源：http://dali.xziqi.cn/Article/details/gtlvgzqqjf.html

Scala .......... 10
来源：http://dali.xziqi.cn/Article/details/gtpdaejitp.html

------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gtysdfkoqt.html

合计 ........... 2106 条
来源：http://dali.chenzaomai.com/Article/details/gtsycgdoha.html

按章节统计：
来源：http://dali.zdqjudy.top/Article/details/gtirpcrafg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zdqjudy.top/Article/details/gtpnojyblf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jqgfzy.top/Article/details/gtewuxcbmj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.sufxvd.cn/Article/details/gtftkxidpo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sweek.top/Article/details/gtuxctswav.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jinqigfzy.top/Article/details/gtyrrpjiwc.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hnxiangtu.top/Article/details/gtmwdzgouq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gtajhgbgye.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.kuanghao11.cn/Article/details/gtjwvkjhub.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sweek.top/Article/details/gtqlhjagrn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cdnleiting.top/Article/details/gtuqgcdzbr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jiagoushi.top/Article/details/gtptavqctb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gthacobhle.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gtvpsgsvvv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zycfv.cn/Article/details/gtrvzkxolt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.fzhhl.top/Article/details/gtlluxgaxz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gtshkjvhss.html

Q SQL 专题                              90
来源：http://dali.daria6918.cn/Article/details/gtymbwdjcj.html

R Bash 专题                             80
来源：http://dali.wangdashe.top/Article/details/gtaaxqjzrp.html

S C / C++ 专题                          60
来源：http://dali.0kj1m.cn/Article/details/gtbmleggkk.html

T 其他语言补充                          60
来源：http://dali.hywenlv.cn/Article/details/gtxemlynqc.html

U 高频实用片段                         120
来源：http://dali.0kj1m.cn/Article/details/gtyofxvqev.html

------------------------------------
来源：http://dali.hnqzz.top/Article/details/gtuempemop.html

合计                                  2106 条
来源：http://dali.gotoacloud.top/Article/details/gtuttddzbs.html

--------------------------------------------------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gtxwqasbii.html

使用提醒
来源：http://dali.ivvv.top/Article/details/gtqxewzywt.html

--------------------------------------------------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gtsjfnlrpi.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.kuanghao11.cn/Article/details/gtolwuehqy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zdqjudy.top/Article/details/gtaqrgjrxg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.9152youxi.cn/Article/details/gttkoyzpaj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.sweek.top/Article/details/gtadfvfedt.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yj20258.top/Article/details/gtktlkleeh.html

—— 文件结束 ——
来源：http://dali.shangyingyoupin.top/Article/details/gtxwcatqwq.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtlivxvrso.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.gzhubu.top/Article/details/gttaxgkvgu.html

Common Programming Examples Cheat Book
来源：http://dali.sweek.top/Article/details/gtnmspyzda.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtzqkrliwr.html

【收录内容】
来源：http://dali.chenzaomai.com/Article/details/gtznrpkofy.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cdnleiting.top/Article/details/gtxrkvvdeo.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.kuanghao11.cn/Article/details/gtwdfxpisw.html

SQL · Bash · C · C++
来源：http://dali.jlsjyb.cn/Article/details/gtfqiftnvk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.cucudq.cn/Article/details/gtglsawjaz.html

【使用说明】
来源：http://dali.sufxvd.cn/Article/details/gtsxoyrblv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yangfankeji.com/Article/details/gtfspymhzm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.kuanghao11.cn/Article/details/gtfuetztay.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhengqikj.top/Article/details/gtyumrkexj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jianghu66.top/Article/details/gturzjresu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.chenlongwang.top/Article/details/gtjpwtvvsm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbtkcscc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yuanzhike.top/Article/details/gtlgrabgyd.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.shuidangran.top/Article/details/gtbovkfslm.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yuxming.cn/Article/details/gtgvnnrmxy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqpqasgsd.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.kuanghao11.cn/Article/details/gtqjorvauz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yj20258888.top/Article/details/gtszsuzjap.html

【文件统计】
来源：http://dali.nanxuanxn.top/Article/details/gtcgrxoyil.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.fengsongda.top/Article/details/gtjsqouqag.html

--------------------------------------------------------------------------------
来源：http://dali.daria6918.cn/Article/details/gtcilwuhhm.html

目  录
来源：http://dali.ppjwa.cn/Article/details/gtjgmyapxy.html

--------------------------------------------------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gtovsscdfx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.gotoacloud.top/Article/details/gtaiezewjp.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.andypj.xyz/Article/details/gtcysitlhr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zycfv.cn/Article/details/gtmxqrvnqm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.aibaodan.cn/Article/details/gtwyxmdryp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.andypj.xyz/Article/details/gtehdwidfd.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.tian-w.cn/Article/details/gthrpofjsd.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jiagoushi.top/Article/details/gtyowtoayi.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yueranfly.top/Article/details/gtyniihouj.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqnuadcf.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.316326.xyz/Article/details/gtfqokeyxk.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gtunhkroxp.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwlihxbc.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gtpcdhctus.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gtdqlzdbbq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.aizwys.cn/Article/details/gtuyjuzfok.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gttesatuzb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jqgfzy.top/Article/details/gtjzofjqib.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.sxryk.cn/Article/details/gteezyvpit.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.9152youxi.cn/Article/details/gtyuybpqtm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhongyouzk.top/Article/details/gthlmnpmqv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuxming.cn/Article/details/gtjezwmdzc.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtxifpiitf.html

A. 基础语法与类型
来源：http://dali.ydzc1.top/Article/details/gtclfqyzxt.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtakhvifao.html

[A01] Hello World
来源：http://dali.sufxvd.cn/Article/details/gtmawzaxqm.html

Py:   print("Hello, World!")
来源：http://dali.zhongyouzk.top/Article/details/gteswpbmog.html

PHP:  echo "Hello, World!";
来源：http://dali.dashuyun.cn/Article/details/gtktqhanwm.html

JS:   console.log("Hello, World!");
来源：http://dali.nwbrower.top/Article/details/gtzskxaixx.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.kuanghao11.cn/Article/details/gtxbjsyoou.html

Java: System.out.println("Hello, World!");
来源：http://dali.sysykeji.top/Article/details/gtzmbmffpf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.gotoacloud.top/Article/details/gttwuausgf.html

Ruby: puts "Hello, World!"
来源：http://dali.tanke756.top/Article/details/gtfpthsbrb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hammf.cn/Article/details/gtdqionlre.html

[A02] 变量声明与赋值
来源：http://dali.gogol.net.cn/Article/details/gthuztixtt.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sweek.top/Article/details/gtxzonejpl.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gtzrgzyids.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xylfe.cn/Article/details/gtpzjstvdt.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxignnuk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxushftdg.html

Go:   name := "Alex"; age := 20
来源：http://dali.aizwys.cn/Article/details/gtctqdcpdv.html

Ruby: name = "Alex"; age = 20
来源：http://dali.redwolf501.top/Article/details/gtyqitmakg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.snrcjt.cn/Article/details/gtpmytasbc.html

[A03] 常量定义
来源：http://dali.c1oappe.top/Article/details/gtjkmcfeot.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.0kj1m.cn/Article/details/gtwgwbnicf.html

PHP:  const PI = 3.14159;
来源：http://dali.havefunace.top/Article/details/gtajxyrcdr.html

JS:   const PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtusvsgxzr.html

TS:   const PI: number = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtaqaorjsj.html

Java: static final double PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gttlfegrpk.html

Go:   const PI = 3.14159
来源：http://dali.hnxiangtu.top/Article/details/gtrdekkljo.html

Ruby: PI = 3.14159
来源：http://dali.jianghu66.top/Article/details/gtwunsuvjh.html

C#:   const double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtdajqhvus.html

[A04] 判断变量类型
来源：http://dali.jiagoushi.top/Article/details/gteitddsgb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zdqjudy.top/Article/details/gtxpzogymo.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.guowangkeji.top/Article/details/gtsbelzsnk.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.shangyingyoupin.top/Article/details/gtlgijcvhw.html

TS:   typeof x; x instanceof Date
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknavyivw.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.fzhhl.top/Article/details/gtobnlxffo.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yongpay.top/Article/details/gtenzebbrh.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhiwuduotai.top/Article/details/gtfszhjsxa.html

C#:   x.GetType().Name; x is int
来源：http://dali.hnxiangtu.top/Article/details/gtseitskjv.html

[A05] 整数除法与取模
来源：http://dali.tanke756.top/Article/details/gtnmxxmabr.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.aizwys.cn/Article/details/gtujocwyde.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.sweek.top/Article/details/gtfaschfyo.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.redwolf501.top/Article/details/gtigsgloqy.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cheryme.top/Article/details/gtnxukfcfx.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqnfxiaz.html

Go:   7 / 2; 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gtgpwewgjj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.dashuyun.cn/Article/details/gtwjubxhdi.html

C#:   7 / 2; 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiuwaecli.html

[A06] 字符串转数字
来源：http://dali.guannengcc.top/Article/details/gtnafrhkui.html

Py:   int("42"); float("3.14")
来源：http://dali.hnxiangtu.top/Article/details/gtyeucdylh.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.ybcxt.top/Article/details/gtpzxuwedr.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.snrcjt.cn/Article/details/gtnnlqfrba.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.c1oappe.top/Article/details/gtwddueqxc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.meibo888.top/Article/details/gttlgjsirz.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shangyingyoupin.top/Article/details/gtjzjwnzbe.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.wangdashe.top/Article/details/gtxrfoggjj.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yuxming.cn/Article/details/gtzgcrpmia.html

[A07] 数字转字符串
来源：http://dali.yj202588.top/Article/details/gtbdbjkwwp.html

Py:   str(42)
来源：http://dali.zhoulong.xyz/Article/details/gtdqmuvlqb.html

PHP:  (string) 42; strval(42)
来源：http://dali.cashguo.top/Article/details/gtrfxwwfnh.html

JS:   String(42); (42).toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtnunzayvh.html

TS:   String(42)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwvqxbhp.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yanxiufei.cn/Article/details/gtcqnkwbsh.html

Go:   strconv.Itoa(42)
来源：http://dali.cucudq.cn/Article/details/gtqhfvdxaz.html

Ruby: 42.to_s
来源：http://dali.shangyingyoupin.top/Article/details/gtqqikxwsc.html

C#:   42.ToString()
来源：http://dali.zdqjudy.top/Article/details/gtxhdcetjx.html

[A08] 取整与四舍五入
来源：http://dali.nanxinkj.top/Article/details/gtedmmheli.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.bjfxy.top/Article/details/gtcmikwvyt.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.tanke756.top/Article/details/gttghiwfzp.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.316326.xyz/Article/details/gtsqofmrqt.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.fzhhl.top/Article/details/gtpxqoeeoj.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gtigzwmmch.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.shuidangran.top/Article/details/gtxmkcvtan.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhixingplan.top/Article/details/gtwvyfiisn.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.xuanzx.com/Article/details/gtlktnkvmn.html

[A09] 绝对值与最大最小值
来源：http://dali.nanxuanxn.top/Article/details/gtyulraika.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yj20258888.top/Article/details/gtcyvizxkj.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtyjxvgzqo.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gtccshfpca.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hnqzz.top/Article/details/gtwweqjues.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtculzefzg.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.wangdashe.top/Article/details/gtphdzqjsu.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.cdnleiting.top/Article/details/gtgpiawxlo.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtmguiolyk.html

[A10] 生成随机数
来源：http://dali.chenjidiqi.icu/Article/details/gtpppmeiga.html

Py:   import random; random.randint(1, 100)
来源：http://dali.tian-w.cn/Article/details/gtswzcyreo.html

PHP:  random_int(1, 100);
来源：http://dali.c1oappe.top/Article/details/gteeaehzua.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhoulong.xyz/Article/details/gtkdpteppf.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xuetiantiany.cn/Article/details/gtahfrtbgi.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yj20258888.top/Article/details/gttxmxdbtt.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zdqjudy.top/Article/details/gtvrpdkmgu.html

Ruby: rand(1..100)
来源：http://dali.mhx1999.top/Article/details/gtksipngse.html

C#:   new Random().Next(1, 101)
来源：http://dali.svipenyu.cn/Article/details/gtpyrddpaw.html

[A11] 条件表达式（三元）
来源：http://dali.xuetiantiany.cn/Article/details/gtkjseazcc.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.hysaishi.cn/Article/details/gtxtmgfeym.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yj20258888.top/Article/details/gtgvcqaoop.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.havefunace.top/Article/details/gtgoxzuzke.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.birdmap.top/Article/details/gtphpvtxij.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.chenlongwang.top/Article/details/gtdadbvbcp.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.redwolf501.top/Article/details/gtmixyhkbn.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jyoumei.cn/Article/details/gtdpmfxfuu.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.shanyushiyangkeji.top/Article/details/gteilxryri.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtiapaflnd.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yj20258888.top/Article/details/gtffjerncl.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhengqikj.top/Article/details/gtajuepzwg.html

JS:   `Hello, ${name}!`
来源：http://dali.chenlongwang.top/Article/details/gtnplwguja.html

TS:   `Hello, ${name}!`
来源：http://dali.svipenyu.cn/Article/details/gtonpxypqv.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.guannengcc.top/Article/details/gtjweltumu.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.tianlin.xyz/Article/details/gtwufxawto.html

Ruby: "Hello, #{name}!"
来源：http://dali.daria6918.cn/Article/details/gtcxhajqwy.html

C#:   $"Hello, {name}!"
来源：http://dali.gogol.net.cn/Article/details/gtfvbendpa.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.sysykeji.top/Article/details/gtgafjcorv.html

Py:   "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gtekrnbcwc.html

PHP:  "第一行\n第二行"
来源：http://dali.nanxinkj.top/Article/details/gthljatrfp.html

JS:   "第一行\n第二行"
来源：http://dali.gaohongyu789.top/Article/details/gtoltybchn.html

TS:   "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gtjesflqmz.html

Java: "第一行\n第二行"
来源：http://dali.shanyushiyangtech.top/Article/details/gtjytvytmg.html

Go:   "第一行\n第二行"
来源：http://dali.quarkkingdee.top/Article/details/gtyeydwvlp.html

Ruby: "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gtovjuztum.html

C#:   "第一行\n第二行"
来源：http://dali.hnqzz.top/Article/details/gtzcdpzoyo.html

[A14] 注释写法
来源：http://dali.jianghu66.top/Article/details/gtomunylyx.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.svipenyu.cn/Article/details/gtjtmvuebm.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.bjfxy.top/Article/details/gtgoefuyie.html

JS:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangtech.top/Article/details/gtxryfifwa.html

TS:   // 单行；/* 多行 */
来源：http://dali.hywenlv.cn/Article/details/gtketqlvqb.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.aizwys.cn/Article/details/gtyicscgbs.html

Go:   // 单行；/* 多行 */
来源：http://dali.ybcxt.top/Article/details/gtnuaiifjf.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.aibaodan.cn/Article/details/gtcbrwsuvd.html

C#:   // 单行；/* 多行 */
来源：http://dali.yuanzhike.top/Article/details/gtredwgxyv.html

[A15] 空值判断与默认值
来源：http://dali.gogol.net.cn/Article/details/gtivwqcvla.html

Py:   value = data or "默认值"
来源：http://dali.guowangkeji.top/Article/details/gtiuwbehdt.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.chenlongwang.top/Article/details/gtzzlvfcdn.html

JS:   const value = data ?? "默认值";
来源：http://dali.xinyue.icu/Article/details/gtoewlxkne.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvwfnvfx.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.snrcjt.cn/Article/details/gtageklqtv.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yueranfly.top/Article/details/gtvxhheoyx.html

Ruby: value = data || "默认值"
来源：http://dali.xziqi.cn/Article/details/gtitaihulc.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gtixgljybl.html

[A16] 真假值判断规则
来源：http://dali.sufxvd.cn/Article/details/gtpuqkvnfw.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.fzhhl.top/Article/details/gtargpuhbr.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.nanxinkj.top/Article/details/gtvdfjnodi.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yanxiufei.cn/Article/details/gtqxhhyicq.html

TS:   if (!x) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtimzwhqup.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtwrmlahyu.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.ydzc1.top/Article/details/gtecxkwhma.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.snrcjt.cn/Article/details/gthciubsvt.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.cdnleiting.top/Article/details/gthirgmeru.html

[A17] 位运算
来源：http://dali.haohaochexian.top/Article/details/gtxfntzqek.html


<!-- 参考信息 -->