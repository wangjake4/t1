代发 wailian999

[U79] PHP：静态分析
来源：http://dali.havefunace.top/Article/details/gteharpcgp.html

composer require --dev phpstan/phpstan
来源：http://dali.zhoulong.xyz/Article/details/gtfvhsabcv.html

[U80] PHP：代码规范修复
来源：http://dali.guannengcc.top/Article/details/gtrupozvzt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jinqigufen.top/Article/details/gtmhchaokl.html

[U81] JS：初始化项目
来源：http://dali.tian-w.cn/Article/details/gtmxooczjx.html

npm init -y;  npm i express
来源：http://dali.feifeiyinyue.top/Article/details/gtffcukdpi.html

[U82] JS：package.json 脚本
来源：http://dali.vqdsnc.cn/Article/details/gtwxdzptij.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jqgfzy.top/Article/details/gtktiqttlj.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhengqikj.top/Article/details/gtzlpxwjop.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.cashguo.top/Article/details/gtdpivnhnh.html

[U84] JS：CommonJS 写法
来源：http://dali.zhixingplan.top/Article/details/gtlrxilvft.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwkmdetg.html

[U85] JS：可选链
来源：http://dali.aizwys.cn/Article/details/gtsjoadcew.html

a?.b?.c
来源：http://dali.smart0.xyz/Article/details/gtaxbynjep.html

[U86] JS：空值合并
来源：http://dali.shanyushiyangtech.top/Article/details/gtaoavrihc.html

a ?? b
来源：http://dali.yueranfly.top/Article/details/gtfjmpkeav.html

[U87] JS：解构默认值
来源：http://dali.yueranfly.top/Article/details/gtzksneime.html

const { a = 1, b = 2 } = obj;
来源：http://dali.chenjidiqi.icu/Article/details/gtxabawgzx.html

[U88] JS：对象展开合并
来源：http://dali.redwolf501.top/Article/details/gtpinsuqvv.html

{ ...a, ...b }
来源：http://dali.316326.xyz/Article/details/gtoifrgbxl.html

[U89] JS：数组去重
来源：http://dali.9152youxi.cn/Article/details/gtlozxvbly.html

[...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gtyyijpgnb.html

[U90] JS：数字数组排序
来源：http://dali.wangshuangyany.cn/Article/details/gtxwjrenlo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gthievjxan.html

[U91] JS：对象键值遍历
来源：http://dali.jiagoushi.top/Article/details/gtepqyjrzm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.pengpengdd.cyou/Article/details/gtzkghyjen.html

[U92] JS：深拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtpayryzok.html

structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtmvwvjvxw.html

[U93] JS：模板字符串
来源：http://dali.tian-w.cn/Article/details/gtnviuiyoq.html

`共 ${n} 条`
来源：http://dali.shuidangran.top/Article/details/gtmimpxlrm.html

[U94] JS：箭头函数
来源：http://dali.ivvv.top/Article/details/gtfdderinm.html

const double = x => x * 2;
来源：http://dali.nanxuanxn.top/Article/details/gttmosdsio.html

[U95] JS：Promise 包装
来源：http://dali.shzxlz.cn/Article/details/gtguyhruue.html

new Promise((resolve, reject) => {})
来源：http://dali.nanxinkj.top/Article/details/gtgrdtygon.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gtgfvrhkxe.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gtqoxwrwuy.html

[U97] JS：并发请求
来源：http://dali.guowangkeji.top/Article/details/gtqizzbzuh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gtgojtqtfs.html

[U98] JS：fetch 带 JSON
来源：http://dali.vqdsnc.cn/Article/details/gtslugwzgt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.gaohongyu789.top/Article/details/gtpfqhaubl.html

[U99] JS：事件监听
来源：http://dali.yangfankeji.com/Article/details/gthwvjsett.html

el.addEventListener("click", e => {})
来源：http://dali.yonumen.top/Article/details/gtdfohtpzo.html

[U100] JS：DOM 查询
来源：http://dali.fzhhl.top/Article/details/gtpwcseqgp.html

document.querySelector(".item")
来源：http://dali.cheryme.top/Article/details/gtvpyyfhey.html

[U101] JS：classList 操作
来源：http://dali.meibo888.top/Article/details/gtreeqoikr.html

el.classList.toggle("active")
来源：http://dali.zdqjudy.top/Article/details/gtmxsbxwji.html

[U102] JS：本地存储
来源：http://dali.ehwqpu.com/Article/details/gtvkimhamn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hfpthk.cn/Article/details/gtuwdoceji.html

[U103] JS：定时器
来源：http://dali.havefunace.top/Article/details/gtsvcdygpr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.9152youxi.cn/Article/details/gtypwmxjpr.html

[U104] JS：防抖
来源：http://dali.aibaodan.cn/Article/details/gtdvovmnim.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gtlgntmsnl.html

[U105] JS：节流
来源：http://dali.zhiwuduotai.top/Article/details/gtdjoxzsnj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cqqwz.cn/Article/details/gtmosfnivx.html

[U106] JS：日期格式化
来源：http://dali.birdmap.top/Article/details/gtbvyjlqkz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.pycfn.com/Article/details/gtchllcsmh.html

[U107] JS：数字千分位
来源：http://dali.hysaishi.cn/Article/details/gttymdmoyr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.redwolf501.top/Article/details/gtaqayaquv.html

[U108] JS：随机整数
来源：http://dali.zhiwuduotai.top/Article/details/gtcppaxyvw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xuetiantiany.cn/Article/details/gtlpdqthdz.html

[U109] JS：数组分组
来源：http://dali.zhiwuduotai.top/Article/details/gtmvapxmxk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258888.top/Article/details/gtybxifwqr.html

[U110] JS：数组分块
来源：http://dali.shzxlz.cn/Article/details/gtxcankonk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.wangdashe.top/Article/details/gtqlqgcvla.html

[U111] JS：对象转 Map
来源：http://dali.guowangkeji.top/Article/details/gtzffslazz.html

new Map(Object.entries(obj))
来源：http://dali.bjfxy.top/Article/details/gtwkoibpbz.html

[U112] JS：字符串补位
来源：http://dali.aibaodan.cn/Article/details/gtylvcsmnf.html

"7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gthfqhyolf.html

[U113] JS：正则替换全部
来源：http://dali.wangshuangyany.cn/Article/details/gttlbmgbgo.html

s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtshrvlywt.html

[U114] JS：JSON 深比较
来源：http://dali.gogol.net.cn/Article/details/gtjbmdbbta.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daxiang520.top/Article/details/gtmymydsar.html

[U115] JS：生成 UUID
来源：http://dali.sysykeji.top/Article/details/gtigzfadvt.html

crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtnnbqtzhm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gaohongyu789.top/Article/details/gtcibnimhl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yj202588.top/Article/details/gtfackafeb.html

[U117] JS：单元测试
来源：http://dali.shzxlz.cn/Article/details/gtzodlcdjd.html

npm i -D vitest;  npx vitest
来源：http://dali.feifeiyinyue.top/Article/details/gtyakdqoww.html

[U118] JS：开发服务器
来源：http://dali.yonumen.top/Article/details/gtrervgbnx.html

npm i -D vite;  npx vite
来源：http://dali.haohaochexian.top/Article/details/gtywryryys.html

[U119] JS：生产构建
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvcnndpt.html

npx vite build
来源：http://dali.sufxvd.cn/Article/details/gtwwvnshyv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hnqzz.top/Article/details/gtledjqxoq.html

import.meta.env.VITE_API_URL
来源：http://dali.snrcjt.cn/Article/details/gtljnocoim.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtdwjqsgqg.html

统计汇总
来源：http://dali.sxryk.cn/Article/details/gtxsakzvfj.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtqgduixhq.html

按语言统计（条）：
来源：http://dali.jinqigufen.top/Article/details/gteptsjigp.html

Python ......... 252
来源：http://dali.jinqigfzy.top/Article/details/gtesqlqpzx.html

PHP ............ 252
来源：http://dali.guannengcc.top/Article/details/gtxklaptog.html

JavaScript ..... 252
来源：http://dali.andypj.xyz/Article/details/gtezaklyuz.html

TypeScript ..... 212
来源：http://dali.nanxinkj.top/Article/details/gtdeerciie.html

Java ........... 212
来源：http://dali.chenlongwang.top/Article/details/gtssbnkgqz.html

Go ............. 212
来源：http://dali.dashuyun.cn/Article/details/gtjqgytfyh.html

Ruby ........... 212
来源：http://dali.yj20258.top/Article/details/gtstnojxam.html

C# ............. 212
来源：http://dali.chenzaomai.com/Article/details/gtaonopmfb.html

C .............. 30
来源：http://dali.yj20258888.top/Article/details/gtilvdojri.html

C++ ............ 30
来源：http://dali.wangdashe.top/Article/details/gtphblcoqo.html

SQL ............ 90
来源：http://dali.zhongyouzk.top/Article/details/gtncfuclyp.html

Bash ........... 80
来源：http://dali.316326.xyz/Article/details/gtruqrivqz.html

Kotlin ......... 15
来源：http://dali.sufxvd.cn/Article/details/gtrrdnveph.html

Swift .......... 15
来源：http://dali.sufxvd.cn/Article/details/gtvgcucpjl.html

Lua ............ 10
来源：http://dali.quarkkingdee.top/Article/details/gtzzqxipgc.html

Perl ........... 10
来源：http://dali.meibo888.top/Article/details/gtsgabbijg.html

Scala .......... 10
来源：http://dali.mhx1999.top/Article/details/gtftstqrca.html

------------------------------------
来源：http://dali.xuanzx.com/Article/details/gtbbxwwubt.html

合计 ........... 2106 条
来源：http://dali.sufxvd.cn/Article/details/gtvjkfnrvv.html

按章节统计：
来源：http://dali.dashuyun.cn/Article/details/gthrzgccce.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xinyue.icu/Article/details/gtouaxlfep.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgsoomsz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gtjbhkzwyq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jianghu66.top/Article/details/gtjqbpmufj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.gzhubu.top/Article/details/gtmqkzqncf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.mhx1999.top/Article/details/gtqjopybii.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.fzhhl.top/Article/details/gtapipvjrf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yj20258888.top/Article/details/gtvuukimud.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gterwnijpm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.fengsongda.top/Article/details/gtnjeyzqgn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gtgpwoauqe.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gtvoqrrzlt.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gttpuvqwwe.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.0kj1m.cn/Article/details/gtsmfekabs.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.nanxuanxn.top/Article/details/gtrtedrobz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhiwuduotai.top/Article/details/gthbbtbbcz.html

Q SQL 专题                              90
来源：http://dali.fzhhl.top/Article/details/gtsgzywafr.html

R Bash 专题                             80
来源：http://dali.cashguo.top/Article/details/gtydcpvukh.html

S C / C++ 专题                          60
来源：http://dali.daria6918.cn/Article/details/gtqzjwkrdl.html

T 其他语言补充                          60
来源：http://dali.shuidangran.top/Article/details/gtnzjpkmad.html

U 高频实用片段                         120
来源：http://dali.wangshuangyany.cn/Article/details/gtjcnpyxbn.html

------------------------------------
来源：http://dali.iojbl.cn/Article/details/gtsbcmhznh.html

合计                                  2106 条
来源：http://dali.hongshengwenyu.top/Article/details/gtotjquicd.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhtnfmye.html

使用提醒
来源：http://dali.yanxiufei.cn/Article/details/gtoczonnsy.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gtmkgfsuvr.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.bjfxy.top/Article/details/gtbpavmjlb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cheryme.top/Article/details/gtfofmigxz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.quarkkingdee.top/Article/details/gtstimspqb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yongpay.top/Article/details/gtimnjdplu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ybcxt.top/Article/details/gtrhtdyxap.html

—— 文件结束 ——
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcavdjuig.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtqqctqdhq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjwnwoclk.html

Common Programming Examples Cheat Book
来源：http://dali.haohaochexian.top/Article/details/gtdaecozsc.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtxftjxpae.html

【收录内容】
来源：http://dali.zhongyouzk.top/Article/details/gtpfgpfixj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.sysykeji.top/Article/details/gtndmswvez.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.shuidangran.top/Article/details/gtaxwewolg.html

SQL · Bash · C · C++
来源：http://dali.jqgufenzy.top/Article/details/gtfvisradl.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.dianchejie.cn/Article/details/gtjqwvukio.html

【使用说明】
来源：http://dali.meibo888.top/Article/details/gtpduwnbpj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hfpthk.cn/Article/details/gtdalkmsjo.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.tanke756.top/Article/details/gtztaklrvh.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.dianchejie.cn/Article/details/gtdjzathda.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhongyouzk.top/Article/details/gtuemidlie.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hammf.cn/Article/details/gtvyowxacp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.smart0.xyz/Article/details/gtmbzlqotd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.aibaodan.cn/Article/details/gtbpvnrdxo.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.pycfn.com/Article/details/gtbfkahnvb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yj20258888.top/Article/details/gtdyjeyutp.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.feifeiyinyue.top/Article/details/gtajvgycsm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gtbbphbffn.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cucudq.cn/Article/details/gtobpgtoiq.html

【文件统计】
来源：http://dali.tanke756.top/Article/details/gtnvopoxkj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.nwbrower.top/Article/details/gtikohpsfg.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtkrwnoksv.html

目  录
来源：http://dali.cashguo.top/Article/details/gtwunqzsic.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtsmunopbn.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xylfe.cn/Article/details/gtcuxijitk.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hfpthk.cn/Article/details/gtgbgvnaqz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jinqigufen.top/Article/details/gtqltesafg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhengqikj.top/Article/details/gthcsizulh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.nwbrower.top/Article/details/gtgzazpxes.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jyoumei.cn/Article/details/gtvzcszahk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.sxryk.cn/Article/details/gtwpnohlbv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yj20258.top/Article/details/gttspxamsc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gtnjgihuvj.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yvedp.cn/Article/details/gtizvdmngj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gtzsnmvgea.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.wangdashe.top/Article/details/gtopoovxrv.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jqgufenzy.top/Article/details/gthfmxexcd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.tianlin.xyz/Article/details/gtzkqescvo.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.fengsongda.top/Article/details/gtrjzommqj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.cdnleiting.top/Article/details/gtsjsemjmc.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gtgjbijnsx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.chenzaomai.com/Article/details/gtxxggarev.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhoulong.xyz/Article/details/gtxcknvdjm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinghuilouyu.cn/Article/details/gtkiehubmz.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258888.top/Article/details/gtgwxvutwu.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtihqikdgp.html

A. 基础语法与类型
来源：http://dali.jinqigufen.top/Article/details/gtwdszsluk.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtjebdidsr.html

[A01] Hello World
来源：http://dali.hnqzz.top/Article/details/gtmudlpzft.html

Py:   print("Hello, World!")
来源：http://dali.ivvv.top/Article/details/gtqpiurahv.html

PHP:  echo "Hello, World!";
来源：http://dali.yuxming.cn/Article/details/gtyoqieadm.html

JS:   console.log("Hello, World!");
来源：http://dali.andypj.xyz/Article/details/gtllfsemaw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.316326.xyz/Article/details/gtfztildlc.html

Java: System.out.println("Hello, World!");
来源：http://dali.9152youxi.cn/Article/details/gtmguhptzf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cdnleiting.top/Article/details/gtlflnluhj.html

Ruby: puts "Hello, World!"
来源：http://dali.jqgufenzy.top/Article/details/gttusrtgeq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.andypj.xyz/Article/details/gthqtzywft.html

[A02] 变量声明与赋值
来源：http://dali.yj202588.top/Article/details/gtbunbeskb.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.c1oappe.top/Article/details/gtlvxmzfig.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jinqigufen.top/Article/details/gtniqmqfjl.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gtkjbuuids.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xylfe.cn/Article/details/gtgwzdtyaj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yj20258888.top/Article/details/gtskkhzbxb.html

Go:   name := "Alex"; age := 20
来源：http://dali.xuetiantiany.cn/Article/details/gtbqxoxvkt.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoasjcihu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.cdnleiting.top/Article/details/gtvlylxkpa.html

[A03] 常量定义
来源：http://dali.cheryme.top/Article/details/gtbcqcdbxi.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hywenlv.cn/Article/details/gtuskhknpi.html

PHP:  const PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtwfgezxfv.html

JS:   const PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtzyidmukr.html

TS:   const PI: number = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtreovtare.html

Java: static final double PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtkucikjqj.html

Go:   const PI = 3.14159
来源：http://dali.chenzaomai.com/Article/details/gtefnpmyim.html

Ruby: PI = 3.14159
来源：http://dali.jiagoushi.top/Article/details/gtcuurhfcw.html

C#:   const double PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtdastfkkr.html

[A04] 判断变量类型
来源：http://dali.nanxuanxn.top/Article/details/gtvqcxwuah.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ppjwa.cn/Article/details/gtwxwzgjxk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.svipenyu.cn/Article/details/gtojrmzpio.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.guowangkeji.top/Article/details/gtqvjvzeqd.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhoulong.xyz/Article/details/gtykbllrmj.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.0kj1m.cn/Article/details/gtmapqbsdn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shuidangran.top/Article/details/gtrceoqobq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.316326.xyz/Article/details/gtposumzyi.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhengqikj.top/Article/details/gtovcwwxpl.html

[A05] 整数除法与取模
来源：http://dali.hysaishi.cn/Article/details/gtggesbfrd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cqqwz.cn/Article/details/gtmvbljzuq.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtufzccxxl.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.fzhhl.top/Article/details/gtjeqnuxdz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gtqymfosks.html

Java: 7 / 2; 7 % 2
来源：http://dali.ivvv.top/Article/details/gtxjsqatij.html

Go:   7 / 2; 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gtxksbmvsa.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gtfqsrsdup.html

C#:   7 / 2; 7 % 2
来源：http://dali.xinyue.icu/Article/details/gtgyvuoqwm.html

[A06] 字符串转数字
来源：http://dali.jiagoushi.top/Article/details/gtnwlwessc.html

Py:   int("42"); float("3.14")
来源：http://dali.pengpengdd.cyou/Article/details/gthvgxuwok.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.gogol.net.cn/Article/details/gtxooyvolv.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.redwolf501.top/Article/details/gtqhkbczsb.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yongpay.top/Article/details/gtooiqpszr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cqqwz.cn/Article/details/gtititihra.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.nanxuanxn.top/Article/details/gtgjcahlsl.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.svipenyu.cn/Article/details/gtvjrzqcgu.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yvedp.cn/Article/details/gtgdqvcqwb.html

[A07] 数字转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtrihzkiuu.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gtqzwqaruk.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gtrengkmop.html

JS:   String(42); (42).toString()
来源：http://dali.bjfxy.top/Article/details/gtkbcxwsmq.html

TS:   String(42)
来源：http://dali.gogol.net.cn/Article/details/gtljsmwujy.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.xuanzx.com/Article/details/gtoqvcxzcr.html

Go:   strconv.Itoa(42)
来源：http://dali.sweek.top/Article/details/gtguarzkxv.html

Ruby: 42.to_s
来源：http://dali.gogol.net.cn/Article/details/gtgjqlbxlh.html

C#:   42.ToString()
来源：http://dali.tianlin.xyz/Article/details/gtzgwpjbwf.html

[A08] 取整与四舍五入
来源：http://dali.c1oappe.top/Article/details/gtscankxbq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ehwqpu.com/Article/details/gtzcxbqmnj.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhiwuduotai.top/Article/details/gttbdfxnef.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.pengpengdd.cyou/Article/details/gtfdwtbxkj.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmshphxfu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.andypj.xyz/Article/details/gtejfywyhg.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.cqqwz.cn/Article/details/gtmitzdkwr.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.shuidangran.top/Article/details/gtzpdyxhzq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhxevhsk.html

[A09] 绝对值与最大最小值
来源：http://dali.hywenlv.cn/Article/details/gtyfbpfxnj.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtxoniwbzo.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jqgfzy.top/Article/details/gtyircctfk.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtxyfudwjw.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtzasnsidq.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkolaiiya.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.shzxlz.cn/Article/details/gtjruxvchm.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yj202588.top/Article/details/gtxnzoukyv.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.redwolf501.top/Article/details/gtyxfryzow.html

[A10] 生成随机数
来源：http://dali.fzhhl.top/Article/details/gtlkoqxqrj.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zycfv.cn/Article/details/gtadvzvuep.html

PHP:  random_int(1, 100);
来源：http://dali.chenjidiqi.icu/Article/details/gtwsajaogc.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhongyouzk.top/Article/details/gtypwzogte.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ehwqpu.com/Article/details/gtubhepiqe.html

Java: new Random().nextInt(100) + 1
来源：http://dali.hysaishi.cn/Article/details/gtefcpqemb.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.pycfn.com/Article/details/gtejeorpqo.html

Ruby: rand(1..100)
来源：http://dali.snrcjt.cn/Article/details/gtshkiqyxb.html

C#:   new Random().Next(1, 101)
来源：http://dali.dianchejie.cn/Article/details/gtacamwwgv.html

[A11] 条件表达式（三元）
来源：http://dali.guowangkeji.top/Article/details/gtupmmrmsq.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.guowangkeji.top/Article/details/gtupkkfzwb.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.cucudq.cn/Article/details/gtmmnwgdtl.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yanxiufei.cn/Article/details/gtdliatfsr.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.shangyingyoupin.top/Article/details/gtuwkyqehv.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhiwuduotai.top/Article/details/gtpoyuhlev.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jinqigufen.top/Article/details/gtrakpeeos.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.316326.xyz/Article/details/gtfpkfjnff.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jinqigufen.top/Article/details/gtszgnzufd.html

[A12] 字符串插值 / 格式化
来源：http://dali.cqqwz.cn/Article/details/gtnonrzzkf.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.xinyue.icu/Article/details/gtgrjwunpc.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yj202588.top/Article/details/gtccehxhzv.html

JS:   `Hello, ${name}!`
来源：http://dali.yangfankeji.com/Article/details/gtusyhhueq.html

TS:   `Hello, ${name}!`
来源：http://dali.zhengqikj.top/Article/details/gtdbxnhhex.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.mhx1999.top/Article/details/gtqnhnpqsm.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtivrmjrdo.html

Ruby: "Hello, #{name}!"
来源：http://dali.jqgufenzy.top/Article/details/gtktxhycwn.html

C#:   $"Hello, {name}!"
来源：http://dali.jyoumei.cn/Article/details/gtwljcenqd.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhengqikj.top/Article/details/gtrwuypqiu.html


<!-- 参考信息 -->