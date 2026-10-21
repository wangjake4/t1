代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gtrlleutpm.html

composer require psr/container
来源：http://dali.quarkkingdee.top/Article/details/gtqbtddqnz.html

[U76] PHP：简单路由
来源：http://dali.hysaishi.cn/Article/details/gtcsqoqclo.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.c1oappe.top/Article/details/gtcflajhlp.html

[U77] PHP：模板渲染
来源：http://dali.havefunace.top/Article/details/gttrihovrk.html

composer require twig/twig
来源：http://dali.birdmap.top/Article/details/gtvhbdldos.html

[U78] PHP：单元测试
来源：http://dali.chenjidiqi.icu/Article/details/gtkjpyiziu.html

composer require --dev phpunit/phpunit
来源：http://dali.cashguo.top/Article/details/gtkxpssrnl.html

[U79] PHP：静态分析
来源：http://dali.sweek.top/Article/details/gtpunufwnd.html

composer require --dev phpstan/phpstan
来源：http://dali.zhongyouzk.top/Article/details/gtlvbiyxpm.html

[U80] PHP：代码规范修复
来源：http://dali.chenlongwang.top/Article/details/gtssfxftxg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhiwuduotai.top/Article/details/gteduczaxj.html

[U81] JS：初始化项目
来源：http://dali.0kj1m.cn/Article/details/gtwsubklry.html

npm init -y;  npm i express
来源：http://dali.xinyue.icu/Article/details/gtczwlcnze.html

[U82] JS：package.json 脚本
来源：http://dali.hnqzz.top/Article/details/gttfarxpaa.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yj20258888.top/Article/details/gtrpkdetdv.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhongyouzk.top/Article/details/gtpmqtvbum.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.gaohongyu789.top/Article/details/gtmsqssmdj.html

[U84] JS：CommonJS 写法
来源：http://dali.jlsjyb.cn/Article/details/gtjfuyatdp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.sufxvd.cn/Article/details/gtuepiymre.html

[U85] JS：可选链
来源：http://dali.yuanzhike.top/Article/details/gtvdvctfxi.html

a?.b?.c
来源：http://dali.yonumen.top/Article/details/gtvhywksif.html

[U86] JS：空值合并
来源：http://dali.jinqigfzy.top/Article/details/gtdtetrajf.html

a ?? b
来源：http://dali.fzhhl.top/Article/details/gtlkispgxb.html

[U87] JS：解构默认值
来源：http://dali.0kj1m.cn/Article/details/gtnxrxlhrz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.havefunace.top/Article/details/gtzhqqgqny.html

[U88] JS：对象展开合并
来源：http://dali.nanxinkj.top/Article/details/gtzqrrhgxy.html

{ ...a, ...b }
来源：http://dali.yuxming.cn/Article/details/gtlpykdxom.html

[U89] JS：数组去重
来源：http://dali.ybcxt.top/Article/details/gtcnkgvaxy.html

[...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gtuqdoqszj.html

[U90] JS：数字数组排序
来源：http://dali.cqqwz.cn/Article/details/gttxjgrdlk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gtzxntodyy.html

[U91] JS：对象键值遍历
来源：http://dali.hfpthk.cn/Article/details/gtdgsvoosb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.dianchejie.cn/Article/details/gtywcjyfph.html

[U92] JS：深拷贝
来源：http://dali.xuanzx.com/Article/details/gtfxcvrmoh.html

structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gtvidhedlr.html

[U93] JS：模板字符串
来源：http://dali.pycfn.com/Article/details/gtwfrcxerh.html

`共 ${n} 条`
来源：http://dali.zycfv.cn/Article/details/gtqfzxqxks.html

[U94] JS：箭头函数
来源：http://dali.xziqi.cn/Article/details/gtsumkqfzt.html

const double = x => x * 2;
来源：http://dali.iojbl.cn/Article/details/gtaucvqqew.html

[U95] JS：Promise 包装
来源：http://dali.quarkkingdee.top/Article/details/gtvtjrgybk.html

new Promise((resolve, reject) => {})
来源：http://dali.ppjwa.cn/Article/details/gtigihvjda.html

[U96] JS：async/await 与异常
来源：http://dali.zhiwuduotai.top/Article/details/gtgcscixkj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtrwtjfxof.html

[U97] JS：并发请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvrtpzhn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gtecriplre.html

[U98] JS：fetch 带 JSON
来源：http://dali.kuanghao11.cn/Article/details/gtzgkeqlwo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yuanzhike.top/Article/details/gtpscmjtqa.html

[U99] JS：事件监听
来源：http://dali.hfpthk.cn/Article/details/gthvgcfkzh.html

el.addEventListener("click", e => {})
来源：http://dali.pycfn.com/Article/details/gtposhxqar.html

[U100] JS：DOM 查询
来源：http://dali.snrcjt.cn/Article/details/gtyktsvrsy.html

document.querySelector(".item")
来源：http://dali.cheryme.top/Article/details/gthokakkay.html

[U101] JS：classList 操作
来源：http://dali.gotoacloud.top/Article/details/gtkmrfcdfx.html

el.classList.toggle("active")
来源：http://dali.ydzc1.top/Article/details/gthuoyzzws.html

[U102] JS：本地存储
来源：http://dali.jiagoushi.top/Article/details/gtasbeiuve.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.316326.xyz/Article/details/gtewyyjzkl.html

[U103] JS：定时器
来源：http://dali.iojbl.cn/Article/details/gtnigvmbid.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ehwqpu.com/Article/details/gtmesggqsc.html

[U104] JS：防抖
来源：http://dali.c1oappe.top/Article/details/gtcsxgfwpq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cheryme.top/Article/details/gtmiglivgt.html

[U105] JS：节流
来源：http://dali.guannengcc.top/Article/details/gtrpplxrnh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.daxiang520.top/Article/details/gtquhbwlro.html

[U106] JS：日期格式化
来源：http://dali.birdmap.top/Article/details/gtwjdqpwwz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cqqwz.cn/Article/details/gttvsalmqi.html

[U107] JS：数字千分位
来源：http://dali.aibaodan.cn/Article/details/gtnarsmkft.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gzhubu.top/Article/details/gtfahjxycw.html

[U108] JS：随机整数
来源：http://dali.havefunace.top/Article/details/gtugyqtdmk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hywenlv.cn/Article/details/gtlsaufrhc.html

[U109] JS：数组分组
来源：http://dali.daxiang520.top/Article/details/gtfcmfrfej.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gtvhwvtlcn.html

[U110] JS：数组分块
来源：http://dali.haohaochexian.top/Article/details/gtminxxkpy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yj20258888.top/Article/details/gtauiwsilj.html

[U111] JS：对象转 Map
来源：http://dali.sysykeji.top/Article/details/gtbcqxopze.html

new Map(Object.entries(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gtootdjzdg.html

[U112] JS：字符串补位
来源：http://dali.c1oappe.top/Article/details/gtnlgccygr.html

"7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gttalfqmxl.html

[U113] JS：正则替换全部
来源：http://dali.smart0.xyz/Article/details/gtxorstdsx.html

s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtgtzfhqul.html

[U114] JS：JSON 深比较
来源：http://dali.jinqigfzy.top/Article/details/gtjatslajq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ppjwa.cn/Article/details/gtygeirjgg.html

[U115] JS：生成 UUID
来源：http://dali.jlsjyb.cn/Article/details/gtmlngrgwq.html

crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gtreuhdbee.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.guannengcc.top/Article/details/gtqfjdkfps.html

/** @param {string} name */ function f(name) {}
来源：http://dali.vqdsnc.cn/Article/details/gtrhovdmko.html

[U117] JS：单元测试
来源：http://dali.pengpengdd.cyou/Article/details/gtlkjqjumg.html

npm i -D vitest;  npx vitest
来源：http://dali.yvedp.cn/Article/details/gtmqmayftg.html

[U118] JS：开发服务器
来源：http://dali.xziqi.cn/Article/details/gtjeowzyuc.html

npm i -D vite;  npx vite
来源：http://dali.hfpthk.cn/Article/details/gtdmcyynfx.html

[U119] JS：生产构建
来源：http://dali.birdmap.top/Article/details/gtioaquqsq.html

npx vite build
来源：http://dali.yueranfly.top/Article/details/gtljifsmfd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.haohaochexian.top/Article/details/gtgidnjmdh.html

import.meta.env.VITE_API_URL
来源：http://dali.sysykeji.top/Article/details/gtyltjtnzs.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtealqzkxd.html

统计汇总
来源：http://dali.chenlongwang.top/Article/details/gtgrdtodru.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtskxefdfm.html

按语言统计（条）：
来源：http://dali.yanxiufei.cn/Article/details/gtwtgkrsol.html

Python ......... 252
来源：http://dali.tanke756.top/Article/details/gtlcufvyiv.html

PHP ............ 252
来源：http://dali.yanxiufei.cn/Article/details/gtrkgzemoa.html

JavaScript ..... 252
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpftcqbhe.html

TypeScript ..... 212
来源：http://dali.daria6918.cn/Article/details/gtttsqmzli.html

Java ........... 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdweiplk.html

Go ............. 212
来源：http://dali.chenlongwang.top/Article/details/gtmujopedd.html

Ruby ........... 212
来源：http://dali.vqdsnc.cn/Article/details/gtswlvufqb.html

C# ............. 212
来源：http://dali.zhongyouzk.top/Article/details/gtdfjtppts.html

C .............. 30
来源：http://dali.gzhubu.top/Article/details/gtfxsxznuu.html

C++ ............ 30
来源：http://dali.smart0.xyz/Article/details/gtkzhcvuhq.html

SQL ............ 90
来源：http://dali.cdnleiting.top/Article/details/gtqtxllkew.html

Bash ........... 80
来源：http://dali.wangdashe.top/Article/details/gtpphtekjx.html

Kotlin ......... 15
来源：http://dali.cqqwz.cn/Article/details/gtcycfwvlw.html

Swift .......... 15
来源：http://dali.vqdsnc.cn/Article/details/gtwamzpgen.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gtlbsqzxus.html

Perl ........... 10
来源：http://dali.gotoacloud.top/Article/details/gtrksjgovq.html

Scala .......... 10
来源：http://dali.hysaishi.cn/Article/details/gtwqjvqnms.html

------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gtlulzwddo.html

合计 ........... 2106 条
来源：http://dali.vqdsnc.cn/Article/details/gtogygbasa.html

按章节统计：
来源：http://dali.wangshuangyany.cn/Article/details/gtyjqlccap.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhixingplan.top/Article/details/gtzbsnqvtw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.tianlin.xyz/Article/details/gtuinpdowd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.mhx1999.top/Article/details/gtpgqidnnq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ppjwa.cn/Article/details/gtdhtoxzsq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hfpthk.cn/Article/details/gthwozdded.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hysaishi.cn/Article/details/gtlfbsmeby.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gzhubu.top/Article/details/gttkgdaiem.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xuetiantiany.cn/Article/details/gtgokisgqa.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xuanzx.com/Article/details/gthtzuxfnj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gzhubu.top/Article/details/gtyfvtcqga.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gthmoznbub.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gtwflmykbz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gtjofeaatz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.tanke756.top/Article/details/gtlezzdrxr.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yj202588.top/Article/details/gtrufrwubw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gtpionthco.html

Q SQL 专题                              90
来源：http://dali.hammf.cn/Article/details/gtrawmpddj.html

R Bash 专题                             80
来源：http://dali.havefunace.top/Article/details/gthrzxgywn.html

S C / C++ 专题                          60
来源：http://dali.cqqwz.cn/Article/details/gtsfsetfyy.html

T 其他语言补充                          60
来源：http://dali.tanke756.top/Article/details/gtdqmjgfgh.html

U 高频实用片段                         120
来源：http://dali.chenjidiqi.icu/Article/details/gtjhzcukan.html

------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtnbjsaqan.html

合计                                  2106 条
来源：http://dali.ehwqpu.com/Article/details/gtjtvyulvs.html

--------------------------------------------------------------------------------
来源：http://dali.xylfe.cn/Article/details/gtczyixjhx.html

使用提醒
来源：http://dali.yangfankeji.com/Article/details/gtipwqshqt.html

--------------------------------------------------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gtjvsxgnzr.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.gzhubu.top/Article/details/gtqoekvcsc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ydzc1.top/Article/details/gtbditqsrq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhengqikj.top/Article/details/gtnemylwpz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cdnleiting.top/Article/details/gtyezuwcrz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yuanzhike.top/Article/details/gtvmzpeihc.html

—— 文件结束 ——
来源：http://dali.wangdashe.top/Article/details/gtnduzseeo.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtavocjita.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xziqi.cn/Article/details/gtbdgaydcq.html

Common Programming Examples Cheat Book
来源：http://dali.yuanzhike.top/Article/details/gtckiixvcq.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtbotkshue.html

【收录内容】
来源：http://dali.chenjidiqi.icu/Article/details/gtjvwfnybk.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.dashuyun.cn/Article/details/gtwvleyhwy.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yj202588.top/Article/details/gtjcvzlmoc.html

SQL · Bash · C · C++
来源：http://dali.chenzaomai.com/Article/details/gtjydhgrtn.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.sweek.top/Article/details/gtcghcitdj.html

【使用说明】
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrtuaunr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cheryme.top/Article/details/gtycpygoku.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.wangdashe.top/Article/details/gtrpzkzbmh.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfeqxzjx.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.snrcjt.cn/Article/details/gtrwutlezp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yj20258888.top/Article/details/gtjssjxnov.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.nwbrower.top/Article/details/gtjycceozw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hywenlv.cn/Article/details/gtfhttvjcg.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.sxryk.cn/Article/details/gtbdmrsqxr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.sufxvd.cn/Article/details/gtfmyfwxds.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hongshengwenyu.top/Article/details/gttqjbavgp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.pengpengdd.cyou/Article/details/gtkkbsczlh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.shanyushiyangtech.top/Article/details/gtlalggzac.html

【文件统计】
来源：http://dali.wangshuangyany.cn/Article/details/gtarvmitel.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhengqikj.top/Article/details/gtikvpigpg.html

--------------------------------------------------------------------------------
来源：http://dali.shuidangran.top/Article/details/gtmfgshpkc.html

目  录
来源：http://dali.andypj.xyz/Article/details/gtiljgpdic.html

--------------------------------------------------------------------------------
来源：http://dali.316326.xyz/Article/details/gtumztbqcf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.c1oappe.top/Article/details/gteaxwmudj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.fzhhl.top/Article/details/gtdzdzoirz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cucudq.cn/Article/details/gteuhiimcj.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jqgfzy.top/Article/details/gtuybcjfwo.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hywenlv.cn/Article/details/gtvqdegaaj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yanxiufei.cn/Article/details/gtllkcifwb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtpkquituc.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.andypj.xyz/Article/details/gtpunxfalt.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.birdmap.top/Article/details/gtcwabdhbm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.316326.xyz/Article/details/gtaaitibhc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gtcymoxytf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gtakncmmmd.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.daria6918.cn/Article/details/gtuygsxpkt.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jqgufenzy.top/Article/details/gtsavcngab.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.kuanghao11.cn/Article/details/gtkrguiumw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gtjcovfkvf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.sweek.top/Article/details/gtjhpgiavj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hnxiangtu.top/Article/details/gtlypohcxs.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.sxryk.cn/Article/details/gtcwwmvsqn.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.kuanghao11.cn/Article/details/gtsjzvmolu.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.shzxlz.cn/Article/details/gtuoaqxzwz.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtjnwubmca.html

A. 基础语法与类型
来源：http://dali.ppjwa.cn/Article/details/gtsyowidlc.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtywwazurl.html

[A01] Hello World
来源：http://dali.cdnleiting.top/Article/details/gtabgigahu.html

Py:   print("Hello, World!")
来源：http://dali.dashuyun.cn/Article/details/gtuvotwchz.html

PHP:  echo "Hello, World!";
来源：http://dali.cashguo.top/Article/details/gtyzgydtwz.html

JS:   console.log("Hello, World!");
来源：http://dali.snrcjt.cn/Article/details/gtshnrblpe.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.gzhubu.top/Article/details/gtscpkoqqw.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhongyouzk.top/Article/details/gtgbcaakoz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cdnleiting.top/Article/details/gtvqzoedab.html

Ruby: puts "Hello, World!"
来源：http://dali.9152youxi.cn/Article/details/gthegfldzw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.0kj1m.cn/Article/details/gtmwilvvnx.html

[A02] 变量声明与赋值
来源：http://dali.havefunace.top/Article/details/gtzuzxekkx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xuetiantiany.cn/Article/details/gthwaaxzrn.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jinqigufen.top/Article/details/gtvsvqcufb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.redwolf501.top/Article/details/gtfuxfyorg.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.havefunace.top/Article/details/gtoccxvhsv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gtypqzsgen.html

Go:   name := "Alex"; age := 20
来源：http://dali.smart0.xyz/Article/details/gtbfvaifxj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hnxiangtu.top/Article/details/gttfiywrmm.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgpazlqe.html

[A03] 常量定义
来源：http://dali.9152youxi.cn/Article/details/gtfrlmgbqg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.fzhhl.top/Article/details/gtghyfqtcb.html

PHP:  const PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gtnlmrcbhs.html

JS:   const PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtquintzib.html

TS:   const PI: number = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxmqhtqo.html

Java: static final double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtyywdsgtp.html

Go:   const PI = 3.14159
来源：http://dali.shzxlz.cn/Article/details/gtldvfxaqw.html

Ruby: PI = 3.14159
来源：http://dali.jinqigufen.top/Article/details/gtxiqnkdxa.html

C#:   const double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtyvpapseo.html

[A04] 判断变量类型
来源：http://dali.guannengcc.top/Article/details/gtflybcnoz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zycfv.cn/Article/details/gtuogaspln.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yj202588.top/Article/details/gtlalzmlyz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hammf.cn/Article/details/gtchineylt.html

TS:   typeof x; x instanceof Date
来源：http://dali.yj20258888.top/Article/details/gtitcymksl.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.sxryk.cn/Article/details/gtczsiufub.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jqgufenzy.top/Article/details/gtukoctevz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yangfankeji.com/Article/details/gtwbfglqka.html

C#:   x.GetType().Name; x is int
来源：http://dali.daria6918.cn/Article/details/gthqbgfmqf.html

[A05] 整数除法与取模
来源：http://dali.ybcxt.top/Article/details/gthuozgbuj.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.meibo888.top/Article/details/gtswjuuyqs.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yuxming.cn/Article/details/gturfrtlnk.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gtudeysppq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.daria6918.cn/Article/details/gtuakfblnu.html

Java: 7 / 2; 7 % 2
来源：http://dali.yongpay.top/Article/details/gtyuqvafsf.html

Go:   7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gtjgsgktte.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.smart0.xyz/Article/details/gtryebjkjj.html

C#:   7 / 2; 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gttppnjjqs.html

[A06] 字符串转数字
来源：http://dali.guannengcc.top/Article/details/gtcygdkwth.html

Py:   int("42"); float("3.14")
来源：http://dali.jinqigufen.top/Article/details/gtpzevzehk.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.meibo888.top/Article/details/gtflpfeqij.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ybcxt.top/Article/details/gtdgyzspcq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.chenzaomai.com/Article/details/gtuukwfccd.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.nwbrower.top/Article/details/gtdiwoacko.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.daxiang520.top/Article/details/gtdihknskc.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jyoumei.cn/Article/details/gtxvqkibgd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hnxiangtu.top/Article/details/gtfrdxxifu.html

[A07] 数字转字符串
来源：http://dali.hnqzz.top/Article/details/gtgfjpqxie.html

Py:   str(42)
来源：http://dali.sysykeji.top/Article/details/gttzpiazjf.html

PHP:  (string) 42; strval(42)
来源：http://dali.meibo888.top/Article/details/gtdchczahj.html

JS:   String(42); (42).toString()
来源：http://dali.daxiang520.top/Article/details/gtonspmrzt.html

TS:   String(42)
来源：http://dali.dashuyun.cn/Article/details/gtebxxmhkg.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.iojbl.cn/Article/details/gtxecqaucx.html

Go:   strconv.Itoa(42)
来源：http://dali.jlsjyb.cn/Article/details/gtdobhavjc.html

Ruby: 42.to_s
来源：http://dali.pengpengdd.cyou/Article/details/gtmxenxkef.html

C#:   42.ToString()
来源：http://dali.sweek.top/Article/details/gtsnvihwzf.html

[A08] 取整与四舍五入
来源：http://dali.andypj.xyz/Article/details/gtrhyqyggx.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gtcjykssfy.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.fzhhl.top/Article/details/gtbeppmouo.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.316326.xyz/Article/details/gtuzvonpjj.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.guowangkeji.top/Article/details/gtbjnguavs.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yj20258.top/Article/details/gtqoyfdjnx.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.redwolf501.top/Article/details/gtlgwywtdv.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yj202588.top/Article/details/gtdzsptuqt.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.fengsongda.top/Article/details/gtcwrnjuih.html

[A09] 绝对值与最大最小值
来源：http://dali.jianghu66.top/Article/details/gtlmmjzpea.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gtmfawcihi.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gtrglthejm.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtlgdmxnhn.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yj20258.top/Article/details/gtbadrzgaz.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtzdjwvkha.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.daxiang520.top/Article/details/gtmysfzomf.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpdoqpwez.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmhayjcf.html

[A10] 生成随机数
来源：http://dali.jqgfzy.top/Article/details/gtojxdpdfw.html

Py:   import random; random.randint(1, 100)
来源：http://dali.ydzc1.top/Article/details/gtwasrwxwk.html

PHP:  random_int(1, 100);
来源：http://dali.0kj1m.cn/Article/details/gtztuzztxo.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gtmqtdigqu.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sysykeji.top/Article/details/gtbxtvnxci.html

Java: new Random().nextInt(100) + 1
来源：http://dali.dashuyun.cn/Article/details/gtknyffcyu.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.ivvv.top/Article/details/gtlxbnnapr.html

Ruby: rand(1..100)
来源：http://dali.ehwqpu.com/Article/details/gtehfqsvzz.html

C#:   new Random().Next(1, 101)
来源：http://dali.aibaodan.cn/Article/details/gtootjphve.html

[A11] 条件表达式（三元）
来源：http://dali.shzxlz.cn/Article/details/gtycoqicxs.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.cdnleiting.top/Article/details/gtssfdbbyp.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gtgseafyrw.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhixingplan.top/Article/details/gttqeiflnx.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.shuidangran.top/Article/details/gtlokmhhcx.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.havefunace.top/Article/details/gtpfkuembi.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.andypj.xyz/Article/details/gtskmxxayi.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.fengsongda.top/Article/details/gtmogaidae.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.meibo888.top/Article/details/gtqsmqauzf.html

[A12] 字符串插值 / 格式化
来源：http://dali.ppjwa.cn/Article/details/gtezhwxeyj.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.daxiang520.top/Article/details/gtemjjalfd.html


<!-- 参考信息 -->