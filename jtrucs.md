代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.jianghu66.top/Article/details/gt2bvdwgtsi.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.birdmap.top/Article/details/gt2uwmaycmm.html

[U92] JS：深拷贝
来源：http://dali.yanxiufei.cn/Article/details/gt2jyhmcwzx.html

structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gt2aosimgys.html

[U93] JS：模板字符串
来源：http://dali.9152youxi.cn/Article/details/gt2tgarptlm.html

`共 ${n} 条`
来源：http://dali.nanxinkj.top/Article/details/gt2wtcgbarc.html

[U94] JS：箭头函数
来源：http://dali.chenzaomai.com/Article/details/gt2iuksczrw.html

const double = x => x * 2;
来源：http://dali.hywenlv.cn/Article/details/gt2lgytmese.html

[U95] JS：Promise 包装
来源：http://dali.aibaodan.cn/Article/details/gt2idyknnxo.html

new Promise((resolve, reject) => {})
来源：http://dali.chenjidiqi.icu/Article/details/gt2eybfyeyz.html

[U96] JS：async/await 与异常
来源：http://dali.cdnleiting.top/Article/details/gt2iiyndpuk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gt2tuhdeyjs.html

[U97] JS：并发请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qhquqnku.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dxtqukkh.html

[U98] JS：fetch 带 JSON
来源：http://dali.tianlin.xyz/Article/details/gt2oefjtxxm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.tanke756.top/Article/details/gt2mavcizmc.html

[U99] JS：事件监听
来源：http://dali.havefunace.top/Article/details/gt2hgyoqsar.html

el.addEventListener("click", e => {})
来源：http://dali.sweek.top/Article/details/gt2klsntdhs.html

[U100] JS：DOM 查询
来源：http://dali.jinqigufen.top/Article/details/gt2ghddcddc.html

document.querySelector(".item")
来源：http://dali.gaohongyu789.top/Article/details/gt2lvcnjdfj.html

[U101] JS：classList 操作
来源：http://dali.guannengcc.top/Article/details/gt2qyudmfdx.html

el.classList.toggle("active")
来源：http://dali.9152youxi.cn/Article/details/gt2fovsjhdk.html

[U102] JS：本地存储
来源：http://dali.snrcjt.cn/Article/details/gt2xtqsuwxg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jqgfzy.top/Article/details/gt2ftamijhw.html

[U103] JS：定时器
来源：http://dali.snrcjt.cn/Article/details/gt2uunpgkqf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shuidangran.top/Article/details/gt2njlrvqdm.html

[U104] JS：防抖
来源：http://dali.316326.xyz/Article/details/gt2rhdsagmx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yangfankeji.com/Article/details/gt2lqabmmsz.html

[U105] JS：节流
来源：http://dali.birdmap.top/Article/details/gt2phprltua.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.fzhhl.top/Article/details/gt2tnwmhabp.html

[U106] JS：日期格式化
来源：http://dali.9152youxi.cn/Article/details/gt2wdbhijyi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.tian-w.cn/Article/details/gt2jgtdhcfw.html

[U107] JS：数字千分位
来源：http://dali.hywenlv.cn/Article/details/gt2esbapmtb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.nanxuanxn.top/Article/details/gt2alqdanao.html

[U108] JS：随机整数
来源：http://dali.chenlongwang.top/Article/details/gt2mvzipvgx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cucudq.cn/Article/details/gt2ndoxrjie.html

[U109] JS：数组分组
来源：http://dali.svipenyu.cn/Article/details/gt2vwrkijju.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gt2rcebcqke.html

[U110] JS：数组分块
来源：http://dali.kuanghao11.cn/Article/details/gt2yakrkbec.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gaohongyu789.top/Article/details/gt2ibopfihd.html

[U111] JS：对象转 Map
来源：http://dali.ivvv.top/Article/details/gt2wymnzijh.html

new Map(Object.entries(obj))
来源：http://dali.smart0.xyz/Article/details/gt2inntcasq.html

[U112] JS：字符串补位
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ukpazngh.html

"7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gt2uqtqlpxr.html

[U113] JS：正则替换全部
来源：http://dali.daxiang520.top/Article/details/gt2krqwbjnj.html

s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2jfhqpugg.html

[U114] JS：JSON 深比较
来源：http://dali.316326.xyz/Article/details/gt2kscmceer.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.smart0.xyz/Article/details/gt2tzxrqujs.html

[U115] JS：生成 UUID
来源：http://dali.yj20258.top/Article/details/gt2yergarpj.html

crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gt2hpshsirn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xziqi.cn/Article/details/gt2rdherjsz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2gkzdnwmo.html

[U117] JS：单元测试
来源：http://dali.cashguo.top/Article/details/gt2ieuehtmg.html

npm i -D vitest;  npx vitest
来源：http://dali.zycfv.cn/Article/details/gt2gavptaei.html

[U118] JS：开发服务器
来源：http://dali.zhoulong.xyz/Article/details/gt2bnffnzuz.html

npm i -D vite;  npx vite
来源：http://dali.dashuyun.cn/Article/details/gt2inusoqkp.html

[U119] JS：生产构建
来源：http://dali.yanxiufei.cn/Article/details/gt2jbncpubv.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsyzelm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhixingplan.top/Article/details/gt2svevleow.html

import.meta.env.VITE_API_URL
来源：http://dali.jqgufenzy.top/Article/details/gt2dtpcwgug.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2zazngxmu.html

统计汇总
来源：http://dali.fengsongda.top/Article/details/gt2apxmrmex.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2ovxznopn.html

按语言统计（条）：
来源：http://dali.chenjidiqi.icu/Article/details/gt2vjcoovts.html

Python ......... 252
来源：http://dali.ybcxt.top/Article/details/gt2tcgqfeik.html

PHP ............ 252
来源：http://dali.hnxiangtu.top/Article/details/gt2dkreqqxf.html

JavaScript ..... 252
来源：http://dali.cdnleiting.top/Article/details/gt2tdkomitp.html

TypeScript ..... 212
来源：http://dali.snrcjt.cn/Article/details/gt2fvwtrgwa.html

Java ........... 212
来源：http://dali.jiagoushi.top/Article/details/gt2eokkvggw.html

Go ............. 212
来源：http://dali.yonumen.top/Article/details/gt2gwxivajw.html

Ruby ........... 212
来源：http://dali.gotoacloud.top/Article/details/gt2sctpmsgh.html

C# ............. 212
来源：http://dali.mhx1999.top/Article/details/gt2tqgumpje.html

C .............. 30
来源：http://dali.ivvv.top/Article/details/gt2knvkvtmx.html

C++ ............ 30
来源：http://dali.cashguo.top/Article/details/gt2hhodrqmq.html

SQL ............ 90
来源：http://dali.redwolf501.top/Article/details/gt2kifbzfvu.html

Bash ........... 80
来源：http://dali.ivvv.top/Article/details/gt2wlhsaldf.html

Kotlin ......... 15
来源：http://dali.shzxlz.cn/Article/details/gt2tdmslgbt.html

Swift .......... 15
来源：http://dali.cdnleiting.top/Article/details/gt2wjcrjejd.html

Lua ............ 10
来源：http://dali.nanxuanxn.top/Article/details/gt2mgwuzosn.html

Perl ........... 10
来源：http://dali.9152youxi.cn/Article/details/gt2psehxrpn.html

Scala .......... 10
来源：http://dali.hnxiangtu.top/Article/details/gt2cxjvtomz.html

------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gt2gghlwmbt.html

合计 ........... 2106 条
来源：http://dali.ydzc1.top/Article/details/gt2mjqckgac.html

按章节统计：
来源：http://dali.zhoulong.xyz/Article/details/gt2mzuavqyn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.smart0.xyz/Article/details/gt2thszgrzr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sweek.top/Article/details/gt2lapiaodv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yj20258.top/Article/details/gt2yotqytrf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.wangdashe.top/Article/details/gt2muiofeat.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.haohaochexian.top/Article/details/gt2wadizban.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.316326.xyz/Article/details/gt2soqxlirw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.nanxuanxn.top/Article/details/gt2uxfmhuhw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yanxiufei.cn/Article/details/gt2rbmlvsue.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gt2wukptwkv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shangyingyoupin.top/Article/details/gt2dxvfoaib.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xuanzx.com/Article/details/gt2wtzlapup.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.kuanghao11.cn/Article/details/gt2lrrvpxqa.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gt2gapomaoq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jlsjyb.cn/Article/details/gt2inewzrjn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.pycfn.com/Article/details/gt2tyjzgngg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gt2nfmjqhsm.html

Q SQL 专题                              90
来源：http://dali.xuanzx.com/Article/details/gt2hanmkylu.html

R Bash 专题                             80
来源：http://dali.dianchejie.cn/Article/details/gt2dpojixlq.html

S C / C++ 专题                          60
来源：http://dali.chenzaomai.com/Article/details/gt2ygfmauud.html

T 其他语言补充                          60
来源：http://dali.zdqjudy.top/Article/details/gt2pwuhaelk.html

U 高频实用片段                         120
来源：http://dali.havefunace.top/Article/details/gt2biplowpr.html

------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gt2yivojtsr.html

合计                                  2106 条
来源：http://dali.snrcjt.cn/Article/details/gt2qxpbmyfm.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gt2kmjbigtu.html

使用提醒
来源：http://dali.yanxiufei.cn/Article/details/gt2gukvyslx.html

--------------------------------------------------------------------------------
来源：http://dali.ydzc1.top/Article/details/gt2fipystyy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cashguo.top/Article/details/gt2vliomekz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zycfv.cn/Article/details/gt2zvoyojvq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.daria6918.cn/Article/details/gt2umgsteyc.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.nanxinkj.top/Article/details/gt2cibrgrfh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hongshengwenyu.top/Article/details/gt2pxajsgfl.html

—— 文件结束 ——
来源：http://dali.guannengcc.top/Article/details/gt2aysweapw.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2lwgyblbh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.quarkkingdee.top/Article/details/gt2uhcilyjd.html

Common Programming Examples Cheat Book
来源：http://dali.zdqjudy.top/Article/details/gt2ckjgukpe.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2dioouvvn.html

【收录内容】
来源：http://dali.guannengcc.top/Article/details/gt2xmlxanhh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.havefunace.top/Article/details/gt2pealqzrv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yangfankeji.com/Article/details/gt2drdipnsa.html

SQL · Bash · C · C++
来源：http://dali.hysaishi.cn/Article/details/gt2pnziyhrs.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2czdbrwpz.html

【使用说明】
来源：http://dali.svipenyu.cn/Article/details/gt2xkdmetwm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.daria6918.cn/Article/details/gt2wppoxdpr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.meibo888.top/Article/details/gt2ovnhxhpw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.nanxuanxn.top/Article/details/gt2olmcgvxe.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.sufxvd.cn/Article/details/gt2uxoeazmg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hysaishi.cn/Article/details/gt2xzpsdabv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jinqigfzy.top/Article/details/gt2fabdohxd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gaohongyu789.top/Article/details/gt2wdpatquq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.dashuyun.cn/Article/details/gt2apxivchw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhengqikj.top/Article/details/gt2lobolbjd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hywenlv.cn/Article/details/gt2lhvwwaxu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yj20258.top/Article/details/gt2wxtfvfni.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhiwuduotai.top/Article/details/gt2whdipvaf.html

【文件统计】
来源：http://dali.sxryk.cn/Article/details/gt2xzmkelwh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.vqdsnc.cn/Article/details/gt2dzkxvvdj.html

--------------------------------------------------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gt2mqllwznz.html

目  录
来源：http://dali.c1oappe.top/Article/details/gt2igmqsjvu.html

--------------------------------------------------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gt2pmqnglol.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2jqefsntp.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.daxiang520.top/Article/details/gt2tbngknkh.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.meibo888.top/Article/details/gt2xhhclmad.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.andypj.xyz/Article/details/gt2sfdjbawd.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2irqbqyxa.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.9152youxi.cn/Article/details/gt2ytnmrunb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.dashuyun.cn/Article/details/gt2qbtkbkll.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.pengpengdd.cyou/Article/details/gt2zjmcaiup.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.chenzaomai.com/Article/details/gt2ihjhsuas.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zdqjudy.top/Article/details/gt2frrafcpt.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gt2ocvusqda.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gt2ddkfrjnu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gt2idgqmpak.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yvedp.cn/Article/details/gt2nqfonmgp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.c1oappe.top/Article/details/gt2jzfaqpnh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2siqlhtuf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.0kj1m.cn/Article/details/gt2lwjkufao.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.nwbrower.top/Article/details/gt2zpptbokv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.c1oappe.top/Article/details/gt2jjnenovi.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cucudq.cn/Article/details/gt2qpoheknj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.dianchejie.cn/Article/details/gt2fryzjrso.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2lfsmgpik.html

A. 基础语法与类型
来源：http://dali.xuanzx.com/Article/details/gt2mjwoabpd.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2xsayirri.html

[A01] Hello World
来源：http://dali.gzhubu.top/Article/details/gt2wksfcmzx.html

Py:   print("Hello, World!")
来源：http://dali.sysykeji.top/Article/details/gt2jysvfmrt.html

PHP:  echo "Hello, World!";
来源：http://dali.yj20258888.top/Article/details/gt2dpgimiiy.html

JS:   console.log("Hello, World!");
来源：http://dali.tanke756.top/Article/details/gt2grdabtyn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhongyouzk.top/Article/details/gt2jmqdlecr.html

Java: System.out.println("Hello, World!");
来源：http://dali.yuxming.cn/Article/details/gt2yvxjoqre.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.haohaochexian.top/Article/details/gt2bhwzynwm.html

Ruby: puts "Hello, World!"
来源：http://dali.shzxlz.cn/Article/details/gt2ljfeyocq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.andypj.xyz/Article/details/gt2hhpcovwr.html

[A02] 变量声明与赋值
来源：http://dali.aibaodan.cn/Article/details/gt2grpdwhjc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.wangshuangyany.cn/Article/details/gt2cjssoxxe.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xuanzx.com/Article/details/gt2wwthsnxu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gt2hgvaujvs.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ivvv.top/Article/details/gt2pbsbsqpx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gt2pgrvmneo.html

Go:   name := "Alex"; age := 20
来源：http://dali.shuidangran.top/Article/details/gt2nceztrrf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jqgfzy.top/Article/details/gt2rcvnrqbx.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.gotoacloud.top/Article/details/gt2aefqyizu.html

[A03] 常量定义
来源：http://dali.wangdashe.top/Article/details/gt2jrkyfiel.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.gogol.net.cn/Article/details/gt2xghgldwr.html

PHP:  const PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gt2kwovhpfd.html

JS:   const PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rkfsgtsw.html

TS:   const PI: number = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gt2qotzwywb.html

Java: static final double PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gt2gosutiwg.html

Go:   const PI = 3.14159
来源：http://dali.xuetiantiany.cn/Article/details/gt2gisvzwvi.html

Ruby: PI = 3.14159
来源：http://dali.guowangkeji.top/Article/details/gt2mbftewjr.html

C#:   const double PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gt2qrdwsnsv.html

[A04] 判断变量类型
来源：http://dali.snrcjt.cn/Article/details/gt2nryxlfiu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yuanzhike.top/Article/details/gt2qlppygbd.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shuidangran.top/Article/details/gt2hgigfkmw.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.aizwys.cn/Article/details/gt2jxbrcxrl.html

TS:   typeof x; x instanceof Date
来源：http://dali.ydzc1.top/Article/details/gt2jzgsecgo.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xuanzx.com/Article/details/gt2ffqiilkv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.svipenyu.cn/Article/details/gt2jwbplpdu.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.cheryme.top/Article/details/gt2yedwhlgj.html

C#:   x.GetType().Name; x is int
来源：http://dali.quarkkingdee.top/Article/details/gt2nwhaxldi.html

[A05] 整数除法与取模
来源：http://dali.chenjidiqi.icu/Article/details/gt2eqefesex.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.gogol.net.cn/Article/details/gt2okcgaurj.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.nanxuanxn.top/Article/details/gt2nqiagheg.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aizwys.cn/Article/details/gt2dxykukgz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gt2zoxcgicu.html

Java: 7 / 2; 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gt2abydvqcy.html

Go:   7 / 2; 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gt2eogwxvnf.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gt2tnutokys.html

C#:   7 / 2; 7 % 2
来源：http://dali.birdmap.top/Article/details/gt2nepomzwa.html

[A06] 字符串转数字
来源：http://dali.nanxinkj.top/Article/details/gt2gnazhpin.html

Py:   int("42"); float("3.14")
来源：http://dali.wangshuangyany.cn/Article/details/gt2mjguundb.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.sxryk.cn/Article/details/gt2ejqxnpmh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.pycfn.com/Article/details/gt2drnfuzkg.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.9152youxi.cn/Article/details/gt2xdzgmzbp.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.shangyingyoupin.top/Article/details/gt2lteoyfsx.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.sxryk.cn/Article/details/gt2iypnywzg.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.havefunace.top/Article/details/gt2vjcycszh.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.feifeiyinyue.top/Article/details/gt2svvpoktg.html

[A07] 数字转字符串
来源：http://dali.havefunace.top/Article/details/gt2nideaanz.html

Py:   str(42)
来源：http://dali.jiagoushi.top/Article/details/gt2nofmxhqa.html

PHP:  (string) 42; strval(42)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bgmyrutm.html

JS:   String(42); (42).toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fvaydgmm.html

TS:   String(42)
来源：http://dali.chenjidiqi.icu/Article/details/gt2oofujxee.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.tanke756.top/Article/details/gt2vmtfguth.html

Go:   strconv.Itoa(42)
来源：http://dali.chenlongwang.top/Article/details/gt2flzulvcl.html

Ruby: 42.to_s
来源：http://dali.birdmap.top/Article/details/gt2fdinyhoc.html

C#:   42.ToString()
来源：http://dali.sysykeji.top/Article/details/gt2zxiutdjn.html

[A08] 取整与四舍五入
来源：http://dali.zhixingplan.top/Article/details/gt2avzwuubv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.wangdashe.top/Article/details/gt2kcmlyeco.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ppjwa.cn/Article/details/gt2xhyxdret.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.316326.xyz/Article/details/gt2mdjcvyqn.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yj20258.top/Article/details/gt2ambtyfuj.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.mhx1999.top/Article/details/gt2fekhvjmo.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yongpay.top/Article/details/gt2kfftdwdm.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.iojbl.cn/Article/details/gt2ishmobgo.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.andypj.xyz/Article/details/gt2movxiydy.html

[A09] 绝对值与最大最小值
来源：http://dali.hongshengwenyu.top/Article/details/gt2caatdwnk.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zycfv.cn/Article/details/gt2bwpcktzo.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2gszustfx.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gt2pikzhmie.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2qjkljcsa.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gt2pcmatpvi.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.shangyingyoupin.top/Article/details/gt2zmjvybuu.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.gogol.net.cn/Article/details/gt2oznuolvi.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gt2bwfqjsop.html

[A10] 生成随机数
来源：http://dali.fengsongda.top/Article/details/gt2joleyxzt.html

Py:   import random; random.randint(1, 100)
来源：http://dali.wangdashe.top/Article/details/gt2vdpnmsoh.html

PHP:  random_int(1, 100);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tyjrnkxb.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zdqjudy.top/Article/details/gt2pgfzwbkn.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yj20258888.top/Article/details/gt2wpfpjbkx.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jyoumei.cn/Article/details/gt2akoicxas.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.sysykeji.top/Article/details/gt2djmbizjw.html

Ruby: rand(1..100)
来源：http://dali.svipenyu.cn/Article/details/gt2dwbaorns.html

C#:   new Random().Next(1, 101)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wjwwbwpd.html

[A11] 条件表达式（三元）
来源：http://dali.kuanghao11.cn/Article/details/gt2xmnzjkik.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jinqigufen.top/Article/details/gt2voumklrz.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qaeljsgm.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.vqdsnc.cn/Article/details/gt2dxaxfmpn.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.chenzaomai.com/Article/details/gt2owcvpfmi.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.hammf.cn/Article/details/gt2xoeddbss.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.ybcxt.top/Article/details/gt2ksaqxnie.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.quarkkingdee.top/Article/details/gt2brcmhbki.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yangfankeji.com/Article/details/gt2jwxwloak.html

[A12] 字符串插值 / 格式化
来源：http://dali.hongshengwenyu.top/Article/details/gt2arqewfjk.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.svipenyu.cn/Article/details/gt2qqlgwtwv.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.sxryk.cn/Article/details/gt2tvsnrqtn.html

JS:   `Hello, ${name}!`
来源：http://dali.yangfankeji.com/Article/details/gt2svpdkgni.html

TS:   `Hello, ${name}!`
来源：http://dali.cheryme.top/Article/details/gt2ltefqwgm.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.c1oappe.top/Article/details/gt2zdsrhmcy.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yj202588.top/Article/details/gt2twayzcpp.html

Ruby: "Hello, #{name}!"
来源：http://dali.ivvv.top/Article/details/gt2fdgycgel.html

C#:   $"Hello, {name}!"
来源：http://dali.sysykeji.top/Article/details/gt2gzqfhacj.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.nwbrower.top/Article/details/gt2znxulyje.html

Py:   "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gt2ddjgfgme.html

PHP:  "第一行\n第二行"
来源：http://dali.9152youxi.cn/Article/details/gt2praabnfn.html

JS:   "第一行\n第二行"
来源：http://dali.ehwqpu.com/Article/details/gt2fvzkxcmd.html

TS:   "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gt2puszqhrq.html

Java: "第一行\n第二行"
来源：http://dali.sysykeji.top/Article/details/gt2lquxbirt.html

Go:   "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gt2zimttwhj.html

Ruby: "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gt2pvgpreij.html

C#:   "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gt2iesxpmzo.html

[A14] 注释写法
来源：http://dali.jqgfzy.top/Article/details/gt2kxasatyk.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.mhx1999.top/Article/details/gt2xzsfxriy.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.feifeiyinyue.top/Article/details/gt2eyxckpkl.html

JS:   // 单行；/* 多行 */
来源：http://dali.hysaishi.cn/Article/details/gt2cimweuhl.html

TS:   // 单行；/* 多行 */
来源：http://dali.shuidangran.top/Article/details/gt2bhyfiiyt.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmvkmop.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2stdnvwdx.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhongyouzk.top/Article/details/gt2hftfdtqd.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhoulong.xyz/Article/details/gt2gdqczfgj.html

[A15] 空值判断与默认值
来源：http://dali.sweek.top/Article/details/gt2pfpdengs.html

Py:   value = data or "默认值"
来源：http://dali.zycfv.cn/Article/details/gt2pmcfazze.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.haohaochexian.top/Article/details/gt2ujxzuope.html

JS:   const value = data ?? "默认值";
来源：http://dali.hammf.cn/Article/details/gt2jahkxgqd.html

TS:   const value = data ?? "默认值";
来源：http://dali.hywenlv.cn/Article/details/gt2itnvezmf.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.sxryk.cn/Article/details/gt2uzmyesvm.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yvedp.cn/Article/details/gt2zyakorlc.html


<!-- 参考信息 -->