代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.ivvv.top/Article/details/gt2xdcktrgk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gzhubu.top/Article/details/gt2lexdpwzc.html

[U92] JS：深拷贝
来源：http://dali.havefunace.top/Article/details/gt2dunykdsc.html

structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2cvfefwsw.html

[U93] JS：模板字符串
来源：http://dali.cashguo.top/Article/details/gt2bngmkxkd.html

`共 ${n} 条`
来源：http://dali.kuanghao11.cn/Article/details/gt2geyvjcth.html

[U94] JS：箭头函数
来源：http://dali.shuidangran.top/Article/details/gt2swnxgubq.html

const double = x => x * 2;
来源：http://dali.gotoacloud.top/Article/details/gt2aucqwncg.html

[U95] JS：Promise 包装
来源：http://dali.nanxuanxn.top/Article/details/gt2vwtnsxbh.html

new Promise((resolve, reject) => {})
来源：http://dali.jiagoushi.top/Article/details/gt2kkwhlcsg.html

[U96] JS：async/await 与异常
来源：http://dali.yuanzhike.top/Article/details/gt2hdjtgtlt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gt2cbbaluqm.html

[U97] JS：并发请求
来源：http://dali.yj20258888.top/Article/details/gt2zuvilelf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gt2mddtnacz.html

[U98] JS：fetch 带 JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uiurfmol.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yvedp.cn/Article/details/gt2oomoiwiy.html

[U99] JS：事件监听
来源：http://dali.sufxvd.cn/Article/details/gt2pqlgwrdy.html

el.addEventListener("click", e => {})
来源：http://dali.mhx1999.top/Article/details/gt2jkemunii.html

[U100] JS：DOM 查询
来源：http://dali.guowangkeji.top/Article/details/gt2xjrjsfrn.html

document.querySelector(".item")
来源：http://dali.ppjwa.cn/Article/details/gt2lrhwysll.html

[U101] JS：classList 操作
来源：http://dali.cqqwz.cn/Article/details/gt2ynhpquaa.html

el.classList.toggle("active")
来源：http://dali.gotoacloud.top/Article/details/gt2ilulhoth.html

[U102] JS：本地存储
来源：http://dali.ppjwa.cn/Article/details/gt2roizofdg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.cdnleiting.top/Article/details/gt2dadeuwzs.html

[U103] JS：定时器
来源：http://dali.yuxming.cn/Article/details/gt2iqwpwtyg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhixingplan.top/Article/details/gt2humvrkkn.html

[U104] JS：防抖
来源：http://dali.haohaochexian.top/Article/details/gt2hgtdnbjb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gt2xdobovvc.html

[U105] JS：节流
来源：http://dali.cdnleiting.top/Article/details/gt2bbkkdauy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xuanzx.com/Article/details/gt2kiohofwc.html

[U106] JS：日期格式化
来源：http://dali.chenzaomai.com/Article/details/gt2qsjrximm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xuetiantiany.cn/Article/details/gt2bcqpwywl.html

[U107] JS：数字千分位
来源：http://dali.jyoumei.cn/Article/details/gt2jrtdnqby.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.havefunace.top/Article/details/gt2wukrhkbh.html

[U108] JS：随机整数
来源：http://dali.zhiwuduotai.top/Article/details/gt2yypcrfin.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yonumen.top/Article/details/gt2wazrlwzm.html

[U109] JS：数组分组
来源：http://dali.c1oappe.top/Article/details/gt2ohxouale.html

Object.groupBy(arr, x => x.type)
来源：http://dali.meibo888.top/Article/details/gt2qeivvnut.html

[U110] JS：数组分块
来源：http://dali.havefunace.top/Article/details/gt2fqkfpite.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.chenjidiqi.icu/Article/details/gt2ombpurqm.html

[U111] JS：对象转 Map
来源：http://dali.jlsjyb.cn/Article/details/gt2zdvotwug.html

new Map(Object.entries(obj))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ucyidnhx.html

[U112] JS：字符串补位
来源：http://dali.gogol.net.cn/Article/details/gt2atpxdozb.html

"7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gt2giizfizm.html

[U113] JS：正则替换全部
来源：http://dali.ivvv.top/Article/details/gt2smskoerz.html

s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gt2fqpjwjzi.html

[U114] JS：JSON 深比较
来源：http://dali.jyoumei.cn/Article/details/gt2brjkzqsp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2evxdfriw.html

[U115] JS：生成 UUID
来源：http://dali.chenzaomai.com/Article/details/gt2swoiirql.html

crypto.randomUUID()
来源：http://dali.vqdsnc.cn/Article/details/gt2eohgbgax.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shzxlz.cn/Article/details/gt2jlnsmhok.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shzxlz.cn/Article/details/gt2vemciwvc.html

[U117] JS：单元测试
来源：http://dali.hammf.cn/Article/details/gt2oxwhoegf.html

npm i -D vitest;  npx vitest
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2myhlcxfp.html

[U118] JS：开发服务器
来源：http://dali.nanxinkj.top/Article/details/gt2hvdrncrr.html

npm i -D vite;  npx vite
来源：http://dali.ydzc1.top/Article/details/gt2jhiazrug.html

[U119] JS：生产构建
来源：http://dali.yongpay.top/Article/details/gt2mkjpuxll.html

npx vite build
来源：http://dali.svipenyu.cn/Article/details/gt2yiqgetsv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jqgfzy.top/Article/details/gt2zorpfmka.html

import.meta.env.VITE_API_URL
来源：http://dali.xylfe.cn/Article/details/gt2hhqyxqih.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2kqioadzw.html

统计汇总
来源：http://dali.hnqzz.top/Article/details/gt2tzhrcpyy.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2jlwzzjbb.html

按语言统计（条）：
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kumpmqvd.html

Python ......... 252
来源：http://dali.yonumen.top/Article/details/gt2ahcbxjpv.html

PHP ............ 252
来源：http://dali.feifeiyinyue.top/Article/details/gt2cqdvxvdp.html

JavaScript ..... 252
来源：http://dali.wangdashe.top/Article/details/gt2qsnafqie.html

TypeScript ..... 212
来源：http://dali.mhx1999.top/Article/details/gt2jcuhtgdc.html

Java ........... 212
来源：http://dali.0kj1m.cn/Article/details/gt2wffqvwds.html

Go ............. 212
来源：http://dali.gogol.net.cn/Article/details/gt2bktwixhx.html

Ruby ........... 212
来源：http://dali.svipenyu.cn/Article/details/gt2ugfjukfp.html

C# ............. 212
来源：http://dali.cdnleiting.top/Article/details/gt2asbmpnfm.html

C .............. 30
来源：http://dali.hywenlv.cn/Article/details/gt2ydjykwnk.html

C++ ............ 30
来源：http://dali.9152youxi.cn/Article/details/gt2hiepgomc.html

SQL ............ 90
来源：http://dali.jinqigufen.top/Article/details/gt2iktzkaat.html

Bash ........... 80
来源：http://dali.sysykeji.top/Article/details/gt2vjwiawjt.html

Kotlin ......... 15
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uzlcwqkq.html

Swift .......... 15
来源：http://dali.zhoulong.xyz/Article/details/gt2ryykxfrm.html

Lua ............ 10
来源：http://dali.gaohongyu789.top/Article/details/gt2ryqyanyi.html

Perl ........... 10
来源：http://dali.jianghu66.top/Article/details/gt2jlxsminf.html

Scala .......... 10
来源：http://dali.nanxuanxn.top/Article/details/gt2wqtdsnwx.html

------------------------------------
来源：http://dali.cashguo.top/Article/details/gt2jqnjezhz.html

合计 ........... 2106 条
来源：http://dali.yangfankeji.com/Article/details/gt2gtyoaksc.html

按章节统计：
来源：http://dali.hysaishi.cn/Article/details/gt2wukkuyti.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.snrcjt.cn/Article/details/gt2zcuxawtr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xyuqlspr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.sweek.top/Article/details/gt2akaxznuy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.chenjidiqi.icu/Article/details/gt2djgcrjge.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.iojbl.cn/Article/details/gt2jdnybzko.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2rgeblkwz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.nanxinkj.top/Article/details/gt2ugzgxwgg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ivvv.top/Article/details/gt2njpcbkqq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gt2thewjzdh.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zycfv.cn/Article/details/gt2otqsbiby.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gt2ngxowxrt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gt2bmbpqvja.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gt2iimxskpz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hysaishi.cn/Article/details/gt2mhxsqoko.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.birdmap.top/Article/details/gt2cpqqmrga.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gt2wlpfjwgi.html

Q SQL 专题                              90
来源：http://dali.chenlongwang.top/Article/details/gt2zchrxxhs.html

R Bash 专题                             80
来源：http://dali.hfpthk.cn/Article/details/gt2laqhkqlu.html

S C / C++ 专题                          60
来源：http://dali.xuanzx.com/Article/details/gt2rlvpbtbh.html

T 其他语言补充                          60
来源：http://dali.chenlongwang.top/Article/details/gt2nxyrvafn.html

U 高频实用片段                         120
来源：http://dali.zhixingplan.top/Article/details/gt2zqtcxsup.html

------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gt2jahkrmrd.html

合计                                  2106 条
来源：http://dali.hfpthk.cn/Article/details/gt2kzyxrmte.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gt2qwqreeer.html

使用提醒
来源：http://dali.yj202588.top/Article/details/gt2lisrkosq.html

--------------------------------------------------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gt2yzgldjlo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.kuanghao11.cn/Article/details/gt2rgnzzypd.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cdnleiting.top/Article/details/gt2qyjhwjwe.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.gzhubu.top/Article/details/gt2zgfosbnt.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.daxiang520.top/Article/details/gt2hczrsgaq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xziqi.cn/Article/details/gt2tiuneatq.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2aerjrqcl.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2bivcxpfi.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.chenlongwang.top/Article/details/gt2vlzhjmit.html

Common Programming Examples Cheat Book
来源：http://dali.chenlongwang.top/Article/details/gt2fzjamgms.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2nexcagmo.html

【收录内容】
来源：http://dali.pengpengdd.cyou/Article/details/gt2kvajmgam.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.tianlin.xyz/Article/details/gt2toftuyhl.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.ivvv.top/Article/details/gt2gzgtnhla.html

SQL · Bash · C · C++
来源：http://dali.andypj.xyz/Article/details/gt2maaqxshn.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yj20258888.top/Article/details/gt2lplmgbbn.html

【使用说明】
来源：http://dali.hnxiangtu.top/Article/details/gt2zhkderch.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yuanzhike.top/Article/details/gt2pvkzfuel.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.chenjidiqi.icu/Article/details/gt2mrohuwud.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.gotoacloud.top/Article/details/gt2xgczanla.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.birdmap.top/Article/details/gt2gzecbpno.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.guowangkeji.top/Article/details/gt2muixadnh.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.smart0.xyz/Article/details/gt2hovkokmm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zdqjudy.top/Article/details/gt2btknsvkn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hnqzz.top/Article/details/gt2wabqqssm.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hongshengwenyu.top/Article/details/gt2dfaixtso.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xziqi.cn/Article/details/gt2qywzogld.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.wangdashe.top/Article/details/gt2jpowcftu.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.tianlin.xyz/Article/details/gt2okzfqekz.html

【文件统计】
来源：http://dali.tian-w.cn/Article/details/gt2ooucnpdt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yonumen.top/Article/details/gt2zhabythm.html

--------------------------------------------------------------------------------
来源：http://dali.smart0.xyz/Article/details/gt2lmbjeuqz.html

目  录
来源：http://dali.sweek.top/Article/details/gt2lpqdgoba.html

--------------------------------------------------------------------------------
来源：http://dali.yvedp.cn/Article/details/gt2nlvajxbh.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ppmucboy.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.xuanzx.com/Article/details/gt2ssljoehk.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xuanzx.com/Article/details/gt2fjbjnzvu.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yj202588.top/Article/details/gt2kfoczcbf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.tianlin.xyz/Article/details/gt2pqyatooc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.316326.xyz/Article/details/gt2umzraoow.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2nakncvya.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.shuidangran.top/Article/details/gt2edckdadx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ydzc1.top/Article/details/gt2frsakykq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.fengsongda.top/Article/details/gt2fbzlqtmz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gt2rnfshsoh.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhixingplan.top/Article/details/gt2lzmscvvg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.ivvv.top/Article/details/gt2xhibkuvx.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.sxryk.cn/Article/details/gt2uyrrnsdc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zdqjudy.top/Article/details/gt2brtbkkbz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zycfv.cn/Article/details/gt2ucfrprts.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2plgwcqer.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yuanzhike.top/Article/details/gt2ptobkqgb.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2pdyuznpx.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuanzx.com/Article/details/gt2fasfbyka.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.havefunace.top/Article/details/gt2kwdieqno.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2uclcactj.html

A. 基础语法与类型
来源：http://dali.0kj1m.cn/Article/details/gt2uiirczae.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2fjjmxwkj.html

[A01] Hello World
来源：http://dali.zhengqikj.top/Article/details/gt2qxtpctnn.html

Py:   print("Hello, World!")
来源：http://dali.bjfxy.top/Article/details/gt2jymzdcqj.html

PHP:  echo "Hello, World!";
来源：http://dali.yvedp.cn/Article/details/gt2klywlhgn.html

JS:   console.log("Hello, World!");
来源：http://dali.zhiwuduotai.top/Article/details/gt2ndmemghr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.c1oappe.top/Article/details/gt2txjiqihv.html

Java: System.out.println("Hello, World!");
来源：http://dali.haohaochexian.top/Article/details/gt2dhoxaxdn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xziqi.cn/Article/details/gt2cqburvfb.html

Ruby: puts "Hello, World!"
来源：http://dali.tian-w.cn/Article/details/gt2bfbbfezw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yuanzhike.top/Article/details/gt2eimxjgmp.html

[A02] 变量声明与赋值
来源：http://dali.xylfe.cn/Article/details/gt2wnumctwj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.gzhubu.top/Article/details/gt2apdcrkpo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jinqigfzy.top/Article/details/gt2bbhkjwiq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.aibaodan.cn/Article/details/gt2wuwhzdyc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.guowangkeji.top/Article/details/gt2wtzzjtmf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hammf.cn/Article/details/gt2ukiopwvj.html

Go:   name := "Alex"; age := 20
来源：http://dali.tian-w.cn/Article/details/gt2umjuvfyx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gotoacloud.top/Article/details/gt2xsdqyjde.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ybcxt.top/Article/details/gt2meouiofy.html

[A03] 常量定义
来源：http://dali.zhongyouzk.top/Article/details/gt2rrvvhemx.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.sweek.top/Article/details/gt2yqdersxl.html

PHP:  const PI = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gt2qdzgetmg.html

JS:   const PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gt2epoutffv.html

TS:   const PI: number = 3.14159;
来源：http://dali.316326.xyz/Article/details/gt2supygfqw.html

Java: static final double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gt2ebvamvzk.html

Go:   const PI = 3.14159
来源：http://dali.0kj1m.cn/Article/details/gt2ecdypdcx.html

Ruby: PI = 3.14159
来源：http://dali.tianlin.xyz/Article/details/gt2aysfxkqj.html

C#:   const double PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gt2qqmjiuio.html

[A04] 判断变量类型
来源：http://dali.tian-w.cn/Article/details/gt2zqhkxrja.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.daxiang520.top/Article/details/gt2geyywtwa.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jlsjyb.cn/Article/details/gt2hmejfvcb.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.kuanghao11.cn/Article/details/gt2peuruzfy.html

TS:   typeof x; x instanceof Date
来源：http://dali.yvedp.cn/Article/details/gt2igcwtyvc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yj20258.top/Article/details/gt2wvugvyyr.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.cdnleiting.top/Article/details/gt2hjiagvwn.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.fengsongda.top/Article/details/gt2bzikbmer.html

C#:   x.GetType().Name; x is int
来源：http://dali.daxiang520.top/Article/details/gt2ageqdlro.html

[A05] 整数除法与取模
来源：http://dali.nanxuanxn.top/Article/details/gt2bbzgnxfn.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2gcsyiwoz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.316326.xyz/Article/details/gt2djhzuyxe.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tnridjpx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2xnjyglvd.html

Java: 7 / 2; 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gt2mskmxggf.html

Go:   7 / 2; 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gt2tpkohpqb.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.cucudq.cn/Article/details/gt2ydclhaiv.html

C#:   7 / 2; 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gt2ruzhogcn.html

[A06] 字符串转数字
来源：http://dali.0kj1m.cn/Article/details/gt2xhoumeyd.html

Py:   int("42"); float("3.14")
来源：http://dali.fzhhl.top/Article/details/gt2svfgrbga.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ayaojybz.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yanxiufei.cn/Article/details/gt2konnowmf.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iwertrub.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.quarkkingdee.top/Article/details/gt2dkpvrlos.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.0kj1m.cn/Article/details/gt2djvjneqx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.gogol.net.cn/Article/details/gt2cluqxhsx.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.shangyingyoupin.top/Article/details/gt2eifcdnrr.html

[A07] 数字转字符串
来源：http://dali.xziqi.cn/Article/details/gt2prbailre.html

Py:   str(42)
来源：http://dali.jinqigufen.top/Article/details/gt2avoezdbd.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhengqikj.top/Article/details/gt2psqeadxy.html

JS:   String(42); (42).toString()
来源：http://dali.hysaishi.cn/Article/details/gt2wpxjgobw.html

TS:   String(42)
来源：http://dali.316326.xyz/Article/details/gt2eqtbdlrq.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.hnxiangtu.top/Article/details/gt2inqibzag.html

Go:   strconv.Itoa(42)
来源：http://dali.nwbrower.top/Article/details/gt2qbvnaovv.html

Ruby: 42.to_s
来源：http://dali.xuanzx.com/Article/details/gt2twqances.html

C#:   42.ToString()
来源：http://dali.gotoacloud.top/Article/details/gt2wqhdirlb.html

[A08] 取整与四舍五入
来源：http://dali.jyoumei.cn/Article/details/gt2vcmscnkb.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhixingplan.top/Article/details/gt2mdvvfbbb.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhongyouzk.top/Article/details/gt2sxltrbhq.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xunqqbzm.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hysaishi.cn/Article/details/gt2ecqxcagx.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yongpay.top/Article/details/gt2ezkxvqrk.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gt2pfhnwbyz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sbkffceq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tnaxwlun.html

[A09] 绝对值与最大最小值
来源：http://dali.zhixingplan.top/Article/details/gt2gzefegab.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sxryk.cn/Article/details/gt2npcciqmf.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.tanke756.top/Article/details/gt2waudzmgv.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yueranfly.top/Article/details/gt2facabypw.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gt2rmmwnlhl.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gt2lhfstsqw.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.cqqwz.cn/Article/details/gt2fcuhvozo.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.0kj1m.cn/Article/details/gt2srxgdgkw.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yuxming.cn/Article/details/gt2mzrgwgjs.html

[A10] 生成随机数
来源：http://dali.svipenyu.cn/Article/details/gt2wyaiwtpg.html

Py:   import random; random.randint(1, 100)
来源：http://dali.ybcxt.top/Article/details/gt2mwuwdwyo.html

PHP:  random_int(1, 100);
来源：http://dali.chenzaomai.com/Article/details/gt2wtjpzapk.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.nanxuanxn.top/Article/details/gt2gkekkfzl.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhixingplan.top/Article/details/gt2ksszoszp.html

Java: new Random().nextInt(100) + 1
来源：http://dali.daxiang520.top/Article/details/gt2qsbnzobl.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.cashguo.top/Article/details/gt2zjpxlysn.html

Ruby: rand(1..100)
来源：http://dali.jinqigfzy.top/Article/details/gt2hwjqppev.html

C#:   new Random().Next(1, 101)
来源：http://dali.guowangkeji.top/Article/details/gt2qaiqhljh.html

[A11] 条件表达式（三元）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ffsutyqz.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zycfv.cn/Article/details/gt2kdbokzit.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.c1oappe.top/Article/details/gt2mghgooqw.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.hfpthk.cn/Article/details/gt2rqlnefeq.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.tianlin.xyz/Article/details/gt2mboexhhj.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.cqqwz.cn/Article/details/gt2tfmfhbya.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.c1oappe.top/Article/details/gt2owytduig.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yj202588.top/Article/details/gt2ezqzrulg.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jqgufenzy.top/Article/details/gt2livurisw.html

[A12] 字符串插值 / 格式化
来源：http://dali.tianlin.xyz/Article/details/gt2ajjkisgv.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.chenzaomai.com/Article/details/gt2fbytmjam.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.fzhhl.top/Article/details/gt2ughnvuqy.html

JS:   `Hello, ${name}!`
来源：http://dali.yj202588.top/Article/details/gt2czagezgz.html

TS:   `Hello, ${name}!`
来源：http://dali.hywenlv.cn/Article/details/gt2jitglajf.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iyesikrp.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jianghu66.top/Article/details/gt2vdflyujl.html

Ruby: "Hello, #{name}!"
来源：http://dali.pycfn.com/Article/details/gt2wzbfvcoi.html

C#:   $"Hello, {name}!"
来源：http://dali.svipenyu.cn/Article/details/gt2cxmvirtk.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yvedp.cn/Article/details/gt2vsiscowj.html

Py:   "第一行\n第二行"
来源：http://dali.sysykeji.top/Article/details/gt2kpcpfbji.html

PHP:  "第一行\n第二行"
来源：http://dali.yangfankeji.com/Article/details/gt2gzlhetdk.html

JS:   "第一行\n第二行"
来源：http://dali.c1oappe.top/Article/details/gt2nrlbwogj.html

TS:   "第一行\n第二行"
来源：http://dali.guowangkeji.top/Article/details/gt2ykjpoiha.html

Java: "第一行\n第二行"
来源：http://dali.nanxinkj.top/Article/details/gt2jcyrhupk.html

Go:   "第一行\n第二行"
来源：http://dali.yvedp.cn/Article/details/gt2gtpwuufe.html

Ruby: "第一行\n第二行"
来源：http://dali.ppjwa.cn/Article/details/gt2sbaegtdc.html

C#:   "第一行\n第二行"
来源：http://dali.zhixingplan.top/Article/details/gt2gfssudug.html

[A14] 注释写法
来源：http://dali.jinqigfzy.top/Article/details/gt2jlhjydlq.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.svipenyu.cn/Article/details/gt2hpraokgt.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.hysaishi.cn/Article/details/gt2darivkbw.html

JS:   // 单行；/* 多行 */
来源：http://dali.316326.xyz/Article/details/gt2ijnexvkc.html

TS:   // 单行；/* 多行 */
来源：http://dali.vqdsnc.cn/Article/details/gt2avcpkziv.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.dianchejie.cn/Article/details/gt2frjuzbxe.html

Go:   // 单行；/* 多行 */
来源：http://dali.chenzaomai.com/Article/details/gt2lbhikoko.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.daria6918.cn/Article/details/gt2xrjkjxle.html

C#:   // 单行；/* 多行 */
来源：http://dali.yj20258888.top/Article/details/gt2qoprwuni.html

[A15] 空值判断与默认值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jcvnpsns.html

Py:   value = data or "默认值"
来源：http://dali.xylfe.cn/Article/details/gt2weqkceyt.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.xinyue.icu/Article/details/gt2svplfcsv.html

JS:   const value = data ?? "默认值";
来源：http://dali.ivvv.top/Article/details/gt2asasmdyu.html

TS:   const value = data ?? "默认值";
来源：http://dali.xziqi.cn/Article/details/gt2vjshpkeq.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.hywenlv.cn/Article/details/gt2jghthzly.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fwuesaeh.html


<!-- 参考信息 -->