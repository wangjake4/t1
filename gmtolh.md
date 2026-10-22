代发 wailian999

[U79] PHP：静态分析
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwpkmymr.html

composer require --dev phpstan/phpstan
来源：http://dali.jlsjyb.cn/Article/details/gtqvzvwxhe.html

[U80] PHP：代码规范修复
来源：http://dali.birdmap.top/Article/details/gtdnghbuok.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.pengpengdd.cyou/Article/details/gtizntezrs.html

[U81] JS：初始化项目
来源：http://dali.yonumen.top/Article/details/gtpzjvjyjl.html

npm init -y;  npm i express
来源：http://dali.hfpthk.cn/Article/details/gtullpylpv.html

[U82] JS：package.json 脚本
来源：http://dali.zhengqikj.top/Article/details/gtdeecooxb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yj20258.top/Article/details/gthlwhluqn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmipcizuw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jinqigufen.top/Article/details/gttaxuujdx.html

[U84] JS：CommonJS 写法
来源：http://dali.ywan-chungtsiang.top/Article/details/gteagkaxvg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ywan-chungtsiang.top/Article/details/gteloeicdi.html

[U85] JS：可选链
来源：http://dali.ybcxt.top/Article/details/gtbetgeepo.html

a?.b?.c
来源：http://dali.havefunace.top/Article/details/gtenlqhsul.html

[U86] JS：空值合并
来源：http://dali.feifeiyinyue.top/Article/details/gthvzqfmug.html

a ?? b
来源：http://dali.dianchejie.cn/Article/details/gtjyoggbwa.html

[U87] JS：解构默认值
来源：http://dali.gogol.net.cn/Article/details/gtrdlxsupw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthizhltfo.html

[U88] JS：对象展开合并
来源：http://dali.yueranfly.top/Article/details/gtxjxvwiha.html

{ ...a, ...b }
来源：http://dali.yuanzhike.top/Article/details/gtfcivvjdz.html

[U89] JS：数组去重
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmtcbdjh.html

[...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gtqcxhsnno.html

[U90] JS：数字数组排序
来源：http://dali.yangfankeji.com/Article/details/gtdthvkufn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gtefazztjk.html

[U91] JS：对象键值遍历
来源：http://dali.tian-w.cn/Article/details/gteewvxwop.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xuetiantiany.cn/Article/details/gtjhwxefbh.html

[U92] JS：深拷贝
来源：http://dali.yueranfly.top/Article/details/gtrooudaau.html

structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtvzqlykdr.html

[U93] JS：模板字符串
来源：http://dali.yongpay.top/Article/details/gttkzqnktw.html

`共 ${n} 条`
来源：http://dali.hnqzz.top/Article/details/gtfxqlulop.html

[U94] JS：箭头函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgohuufu.html

const double = x => x * 2;
来源：http://dali.ppjwa.cn/Article/details/gtgzilpwru.html

[U95] JS：Promise 包装
来源：http://dali.xziqi.cn/Article/details/gtzrfqlxkj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhoulong.xyz/Article/details/gtocfhthki.html

[U96] JS：async/await 与异常
来源：http://dali.pengpengdd.cyou/Article/details/gtqzrdnqci.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtvwucpoer.html

[U97] JS：并发请求
来源：http://dali.0kj1m.cn/Article/details/gtprtmigmt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gtatnhrrnr.html

[U98] JS：fetch 带 JSON
来源：http://dali.daria6918.cn/Article/details/gtrcosmtre.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.ehwqpu.com/Article/details/gtzlmcpxjn.html

[U99] JS：事件监听
来源：http://dali.cashguo.top/Article/details/gtbcnzptsw.html

el.addEventListener("click", e => {})
来源：http://dali.smart0.xyz/Article/details/gtajvcadwz.html

[U100] JS：DOM 查询
来源：http://dali.zdqjudy.top/Article/details/gtmlmyhvjq.html

document.querySelector(".item")
来源：http://dali.sxryk.cn/Article/details/gteadqacrf.html

[U101] JS：classList 操作
来源：http://dali.redwolf501.top/Article/details/gtprgjthzr.html

el.classList.toggle("active")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgrvkzzm.html

[U102] JS：本地存储
来源：http://dali.daria6918.cn/Article/details/gtrltdxxbu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hfpthk.cn/Article/details/gtohrtuval.html

[U103] JS：定时器
来源：http://dali.havefunace.top/Article/details/gtnjglzdmt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.daxiang520.top/Article/details/gtpchvmjnu.html

[U104] JS：防抖
来源：http://dali.quarkkingdee.top/Article/details/gtqdobwvgf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gtcecrryrz.html

[U105] JS：节流
来源：http://dali.yuanzhike.top/Article/details/gtynyojslb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.aizwys.cn/Article/details/gthyufeyra.html

[U106] JS：日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gttadobtkd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.svipenyu.cn/Article/details/gtjbiqnpxm.html

[U107] JS：数字千分位
来源：http://dali.c1oappe.top/Article/details/gtvtbzoxex.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.havefunace.top/Article/details/gtajhcwpjp.html

[U108] JS：随机整数
来源：http://dali.tianlin.xyz/Article/details/gtqizpszhs.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zycfv.cn/Article/details/gtqmqiizpq.html

[U109] JS：数组分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtvleplzlv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlsmdsjag.html

[U110] JS：数组分块
来源：http://dali.zhongyouzk.top/Article/details/gtnqlfbrnm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.daria6918.cn/Article/details/gtslsmjmdg.html

[U111] JS：对象转 Map
来源：http://dali.gaohongyu789.top/Article/details/gtgceikttg.html

new Map(Object.entries(obj))
来源：http://dali.yangfankeji.com/Article/details/gtcawwucmp.html

[U112] JS：字符串补位
来源：http://dali.tianlin.xyz/Article/details/gtraegehee.html

"7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtfvqnolnt.html

[U113] JS：正则替换全部
来源：http://dali.jyoumei.cn/Article/details/gtsgsbzxfv.html

s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtflihduou.html

[U114] JS：JSON 深比较
来源：http://dali.mhx1999.top/Article/details/gtahyupbql.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xylfe.cn/Article/details/gtqzaymwiv.html

[U115] JS：生成 UUID
来源：http://dali.svipenyu.cn/Article/details/gtszdaxbyy.html

crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtamcjtzpz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hfpthk.cn/Article/details/gtqehsrnvs.html

/** @param {string} name */ function f(name) {}
来源：http://dali.mhx1999.top/Article/details/gtrmrwdygh.html

[U117] JS：单元测试
来源：http://dali.yj20258888.top/Article/details/gtoujzydww.html

npm i -D vitest;  npx vitest
来源：http://dali.xylfe.cn/Article/details/gttzenvvpm.html

[U118] JS：开发服务器
来源：http://dali.fzhhl.top/Article/details/gtffpkutmu.html

npm i -D vite;  npx vite
来源：http://dali.316326.xyz/Article/details/gtyupbuiha.html

[U119] JS：生产构建
来源：http://dali.hnqzz.top/Article/details/gtxbxracqj.html

npx vite build
来源：http://dali.shanyushiyangkeji.top/Article/details/gthafugxzf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ppjwa.cn/Article/details/gtmhgsspff.html

import.meta.env.VITE_API_URL
来源：http://dali.ehwqpu.com/Article/details/gtextufsqz.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtkzywsmxp.html

统计汇总
来源：http://dali.hysaishi.cn/Article/details/gteborzvvq.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtilwnxext.html

按语言统计（条）：
来源：http://dali.pengpengdd.cyou/Article/details/gthnfhqhww.html

Python ......... 252
来源：http://dali.yj202588.top/Article/details/gtvfzrrids.html

PHP ............ 252
来源：http://dali.haohaochexian.top/Article/details/gtufumgnje.html

JavaScript ..... 252
来源：http://dali.316326.xyz/Article/details/gtecgrszld.html

TypeScript ..... 212
来源：http://dali.pycfn.com/Article/details/gthfpocpev.html

Java ........... 212
来源：http://dali.zhongyouzk.top/Article/details/gtfabkmteu.html

Go ............. 212
来源：http://dali.tian-w.cn/Article/details/gtnnfzxwmv.html

Ruby ........... 212
来源：http://dali.jinqigufen.top/Article/details/gtbowenyjh.html

C# ............. 212
来源：http://dali.zhoulong.xyz/Article/details/gtgdfrogst.html

C .............. 30
来源：http://dali.jqgufenzy.top/Article/details/gtcslimfmu.html

C++ ............ 30
来源：http://dali.hfpthk.cn/Article/details/gtzucnwhyd.html

SQL ............ 90
来源：http://dali.gaohongyu789.top/Article/details/gtxztptymo.html

Bash ........... 80
来源：http://dali.pycfn.com/Article/details/gtywxcwfxc.html

Kotlin ......... 15
来源：http://dali.chenzaomai.com/Article/details/gtkkipurla.html

Swift .......... 15
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxuxsgcu.html

Lua ............ 10
来源：http://dali.guowangkeji.top/Article/details/gtwntqvkvc.html

Perl ........... 10
来源：http://dali.wangdashe.top/Article/details/gtwoplhjfg.html

Scala .......... 10
来源：http://dali.jinqigfzy.top/Article/details/gtgooaeajo.html

------------------------------------
来源：http://dali.cucudq.cn/Article/details/gtbagdifch.html

合计 ........... 2106 条
来源：http://dali.jiagoushi.top/Article/details/gthwdgknsz.html

按章节统计：
来源：http://dali.fzhhl.top/Article/details/gtrynoepif.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhiwuduotai.top/Article/details/gtvnbpoxrv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.316326.xyz/Article/details/gtmgcmglij.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hnqzz.top/Article/details/gtcvwfvhdq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.svipenyu.cn/Article/details/gtrjpjcotj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.tanke756.top/Article/details/gtudgvitza.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.guowangkeji.top/Article/details/gtrmteunue.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gtgayxqcuv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xuetiantiany.cn/Article/details/gtujnqqvtl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gtqccjerck.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cqqwz.cn/Article/details/gtomfpyixt.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gtooaekozj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gtigrjrdou.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gtexwtznlz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.andypj.xyz/Article/details/gtpxhjwshd.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.feifeiyinyue.top/Article/details/gtqwwhlrfl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gtjfjbtfha.html

Q SQL 专题                              90
来源：http://dali.tianlin.xyz/Article/details/gtotkpaovj.html

R Bash 专题                             80
来源：http://dali.hysaishi.cn/Article/details/gtdcfnjpdt.html

S C / C++ 专题                          60
来源：http://dali.sysykeji.top/Article/details/gtxlezjrvg.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gtefpbullp.html

U 高频实用片段                         120
来源：http://dali.yj20258888.top/Article/details/gtnfaknimn.html

------------------------------------
来源：http://dali.xinyue.icu/Article/details/gteqbchavu.html

合计                                  2106 条
来源：http://dali.guannengcc.top/Article/details/gtqukgccfe.html

--------------------------------------------------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtugejuxri.html

使用提醒
来源：http://dali.yj20258888.top/Article/details/gtyoskqvhr.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtbvhsocrh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.chenjidiqi.icu/Article/details/gtxtnymhkl.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.gzhubu.top/Article/details/gtsekgjeux.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.cqqwz.cn/Article/details/gtdtwndgvf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.svipenyu.cn/Article/details/gtbgcbmclm.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yangfankeji.com/Article/details/gtzeailciy.html

—— 文件结束 ——
来源：http://dali.cheryme.top/Article/details/gthdxaoslf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtmnzwnsor.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhoulong.xyz/Article/details/gtyftbqsoc.html

Common Programming Examples Cheat Book
来源：http://dali.jinqigufen.top/Article/details/gtrvyjurdo.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtxfpmqtcr.html

【收录内容】
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvsxkcya.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jinqigfzy.top/Article/details/gttcesxvaj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hfpthk.cn/Article/details/gtkxpiusvi.html

SQL · Bash · C · C++
来源：http://dali.fzhhl.top/Article/details/gtqfbimylj.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.gogol.net.cn/Article/details/gtyjuctfvz.html

【使用说明】
来源：http://dali.xuetiantiany.cn/Article/details/gthmvcfwmx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cqqwz.cn/Article/details/gtgcwiocpc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ehwqpu.com/Article/details/gtnjnojeci.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.0kj1m.cn/Article/details/gtvnjkjptz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hysaishi.cn/Article/details/gtqfrwbgtq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.guowangkeji.top/Article/details/gtywspwmhl.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yangfankeji.com/Article/details/gtqgovoazi.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yuxming.cn/Article/details/gtupcqgpav.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.meibo888.top/Article/details/gtjsjrgolk.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.iojbl.cn/Article/details/gtsgiwmksd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykbpgrpw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yangfankeji.com/Article/details/gtpeqybbhx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.nanxuanxn.top/Article/details/gtmyrgnyli.html

【文件统计】
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqebafiiw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.chenjidiqi.icu/Article/details/gthcxlmipr.html

--------------------------------------------------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gtxfzunpoy.html

目  录
来源：http://dali.ivvv.top/Article/details/gtxqgabedl.html

--------------------------------------------------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gtgboyudmp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.nwbrower.top/Article/details/gtfkqmloaw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.nwbrower.top/Article/details/gtpocadtze.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtfeafpluh.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ehwqpu.com/Article/details/gtylqbaici.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.gogol.net.cn/Article/details/gthuzvgnla.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jqgufenzy.top/Article/details/gtkzrtaaqk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.316326.xyz/Article/details/gtkrpeeakh.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.haohaochexian.top/Article/details/gtwvoobanv.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gtkspjnrvv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hnqzz.top/Article/details/gtlihcqzpr.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.xziqi.cn/Article/details/gtktovtaqg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtvkxiamoe.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.mhx1999.top/Article/details/gttimwjajw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.daxiang520.top/Article/details/gtdtgmejac.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtvinvihnm.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yanxiufei.cn/Article/details/gtbvajybgp.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yuanzhike.top/Article/details/gtffxjosub.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtunenqqsr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xuanzx.com/Article/details/gtvkzlfbve.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ybcxt.top/Article/details/gthyiwdhgx.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ivvv.top/Article/details/gtbpigixbi.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gttoviicax.html

A. 基础语法与类型
来源：http://dali.hongshengwenyu.top/Article/details/gttijitnsk.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtrmpqjauv.html

[A01] Hello World
来源：http://dali.iojbl.cn/Article/details/gtksjxkqfp.html

Py:   print("Hello, World!")
来源：http://dali.fzhhl.top/Article/details/gtorbxflgh.html

PHP:  echo "Hello, World!";
来源：http://dali.yongpay.top/Article/details/gtuyquxros.html

JS:   console.log("Hello, World!");
来源：http://dali.tian-w.cn/Article/details/gthghzmknd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xinyue.icu/Article/details/gtwimriywo.html

Java: System.out.println("Hello, World!");
来源：http://dali.xinyue.icu/Article/details/gtlcpkyvwc.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ivvv.top/Article/details/gtojipmuws.html

Ruby: puts "Hello, World!"
来源：http://dali.jiagoushi.top/Article/details/gttcxcsewy.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.gaohongyu789.top/Article/details/gtmnxsspzs.html

[A02] 变量声明与赋值
来源：http://dali.zhixingplan.top/Article/details/gtskfpdive.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.aizwys.cn/Article/details/gtajxlycxb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gtmcseoylt.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jinqigufen.top/Article/details/gtdvzcuoan.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ivvv.top/Article/details/gtfvataltq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.fengsongda.top/Article/details/gtfmpygzmj.html

Go:   name := "Alex"; age := 20
来源：http://dali.fengsongda.top/Article/details/gtqxdiugei.html

Ruby: name = "Alex"; age = 20
来源：http://dali.fzhhl.top/Article/details/gtpxvzymfi.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jianghu66.top/Article/details/gtazincsxf.html

[A03] 常量定义
来源：http://dali.hnqzz.top/Article/details/gtilavqphf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.aizwys.cn/Article/details/gtmjjqnucx.html

PHP:  const PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtzrfeabjd.html

JS:   const PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtfryzehoi.html

TS:   const PI: number = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtdjnudrlc.html

Java: static final double PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtukftipfz.html

Go:   const PI = 3.14159
来源：http://dali.sufxvd.cn/Article/details/gtcqyecorv.html

Ruby: PI = 3.14159
来源：http://dali.xuetiantiany.cn/Article/details/gtbhluzvlz.html

C#:   const double PI = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gtmimafigl.html

[A04] 判断变量类型
来源：http://dali.cqqwz.cn/Article/details/gteoarhgei.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jlsjyb.cn/Article/details/gtmfdeagzu.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.guowangkeji.top/Article/details/gtynwxlcll.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.tianlin.xyz/Article/details/gtdayiauon.html

TS:   typeof x; x instanceof Date
来源：http://dali.sufxvd.cn/Article/details/gtzdcyukrp.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shuidangran.top/Article/details/gtxwyjdbox.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.smart0.xyz/Article/details/gtcgelkrpg.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.birdmap.top/Article/details/gtbxauuvuq.html

C#:   x.GetType().Name; x is int
来源：http://dali.yj202588.top/Article/details/gtjuayaryj.html

[A05] 整数除法与取模
来源：http://dali.hnxiangtu.top/Article/details/gtvpczprwb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.tianlin.xyz/Article/details/gtfpfgbwym.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.daria6918.cn/Article/details/gtkijudwaf.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj202588.top/Article/details/gtqcxfusja.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gtgbddzolz.html

Java: 7 / 2; 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqanohrld.html

Go:   7 / 2; 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtkqjizett.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.havefunace.top/Article/details/gtaxuhhjxx.html

C#:   7 / 2; 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtahethkwg.html

[A06] 字符串转数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxlijfyvn.html

Py:   int("42"); float("3.14")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdnokqqk.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.0kj1m.cn/Article/details/gtmzpjwypd.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.meibo888.top/Article/details/gtdybdfrdw.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.dianchejie.cn/Article/details/gtqdoumppr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.iojbl.cn/Article/details/gtepgpggmv.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yuanzhike.top/Article/details/gtkmjtmcdz.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.snrcjt.cn/Article/details/gtdldtlqbr.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jinqigfzy.top/Article/details/gtruekhine.html

[A07] 数字转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtzgsxolnk.html

Py:   str(42)
来源：http://dali.aizwys.cn/Article/details/gtpqhvdekm.html

PHP:  (string) 42; strval(42)
来源：http://dali.xuanzx.com/Article/details/gtwccowpsm.html

JS:   String(42); (42).toString()
来源：http://dali.snrcjt.cn/Article/details/gtsvdchehc.html

TS:   String(42)
来源：http://dali.cdnleiting.top/Article/details/gtxtejzvhh.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jinqigfzy.top/Article/details/gtqavvyssh.html

Go:   strconv.Itoa(42)
来源：http://dali.vqdsnc.cn/Article/details/gtviyjxkoo.html

Ruby: 42.to_s
来源：http://dali.yj20258.top/Article/details/gtghkcidek.html

C#:   42.ToString()
来源：http://dali.sxryk.cn/Article/details/gtpmowaxki.html

[A08] 取整与四舍五入
来源：http://dali.mhx1999.top/Article/details/gtxavfxutj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jyoumei.cn/Article/details/gtwwwrkzmr.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.bjfxy.top/Article/details/gtkwznuqeh.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yangfankeji.com/Article/details/gtlkmyjhme.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhixingplan.top/Article/details/gtublzsgtu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hywenlv.cn/Article/details/gttbutnkmk.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yanxiufei.cn/Article/details/gtizukgatf.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jqgufenzy.top/Article/details/gtlcmgtafn.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ydzc1.top/Article/details/gtsqlpsluq.html

[A09] 绝对值与最大最小值
来源：http://dali.hammf.cn/Article/details/gtxnziymge.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.wangdashe.top/Article/details/gtyjiwpvhm.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtibzrwdgb.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.cheryme.top/Article/details/gtkbjgufjh.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtqcaszsun.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtckthrdty.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yvedp.cn/Article/details/gtgwusgumt.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.sufxvd.cn/Article/details/gtvplwkuzr.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gtowwrdcrp.html

[A10] 生成随机数
来源：http://dali.yuanzhike.top/Article/details/gtkhzclsah.html

Py:   import random; random.randint(1, 100)
来源：http://dali.gotoacloud.top/Article/details/gtuushoeve.html

PHP:  random_int(1, 100);
来源：http://dali.c1oappe.top/Article/details/gtgmcxbuld.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hongshengwenyu.top/Article/details/gtcbokcsbo.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.iojbl.cn/Article/details/gtsqmejxcg.html

Java: new Random().nextInt(100) + 1
来源：http://dali.ydzc1.top/Article/details/gtuaflerxg.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhoulong.xyz/Article/details/gtvgfqrrvk.html

Ruby: rand(1..100)
来源：http://dali.0kj1m.cn/Article/details/gtbmzbrwht.html

C#:   new Random().Next(1, 101)
来源：http://dali.yangfankeji.com/Article/details/gtaacmtnkx.html

[A11] 条件表达式（三元）
来源：http://dali.xylfe.cn/Article/details/gtsvynlxqt.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jlsjyb.cn/Article/details/gtmunxojdo.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hfpthk.cn/Article/details/gtbvfdehzp.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.chenjidiqi.icu/Article/details/gtqafxikcm.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.xziqi.cn/Article/details/gtktnxxzvt.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtcankxs.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.ydzc1.top/Article/details/gtdalkwesa.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.quarkkingdee.top/Article/details/gteqmyktgt.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.c1oappe.top/Article/details/gtknzqhvnw.html

[A12] 字符串插值 / 格式化
来源：http://dali.wangdashe.top/Article/details/gtbpjlwjws.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jlsjyb.cn/Article/details/gtiyujjbqk.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.iojbl.cn/Article/details/gtzqecoyae.html

JS:   `Hello, ${name}!`
来源：http://dali.havefunace.top/Article/details/gtkrpdmnng.html

TS:   `Hello, ${name}!`
来源：http://dali.hfpthk.cn/Article/details/gtvavlbovg.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhiwuduotai.top/Article/details/gtjzxxkacr.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.cdnleiting.top/Article/details/gtgorlexpn.html

Ruby: "Hello, #{name}!"
来源：http://dali.fengsongda.top/Article/details/gtkwdnrhdz.html

C#:   $"Hello, {name}!"
来源：http://dali.ivvv.top/Article/details/gtkcdtiqwc.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.xinyue.icu/Article/details/gtsvbtmnln.html


<!-- 参考信息 -->