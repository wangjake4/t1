代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.cashguo.top/Article/details/gtrzngjxto.html

composer require psr/container
来源：http://dali.nanxinkj.top/Article/details/gttwobvhja.html

[U76] PHP：简单路由
来源：http://dali.iojbl.cn/Article/details/gtdeazlqie.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.wangdashe.top/Article/details/gtxcsydnnp.html

[U77] PHP：模板渲染
来源：http://dali.jqgufenzy.top/Article/details/gtuasdjgye.html

composer require twig/twig
来源：http://dali.cheryme.top/Article/details/gtuzoepkmb.html

[U78] PHP：单元测试
来源：http://dali.svipenyu.cn/Article/details/gtfiwlygmh.html

composer require --dev phpunit/phpunit
来源：http://dali.jyoumei.cn/Article/details/gttiuzayrt.html

[U79] PHP：静态分析
来源：http://dali.chenlongwang.top/Article/details/gtotvujilx.html

composer require --dev phpstan/phpstan
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmnsqevql.html

[U80] PHP：代码规范修复
来源：http://dali.yuanzhike.top/Article/details/gtzqfurpch.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shanyushiyangtech.top/Article/details/gtnktwsxqe.html

[U81] JS：初始化项目
来源：http://dali.cheryme.top/Article/details/gtufyzunxk.html

npm init -y;  npm i express
来源：http://dali.xuetiantiany.cn/Article/details/gtosxjlbye.html

[U82] JS：package.json 脚本
来源：http://dali.bjfxy.top/Article/details/gtrfjgmnsj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.ppjwa.cn/Article/details/gtdhyfxyyp.html

[U83] JS：ES Module 导入导出
来源：http://dali.ehwqpu.com/Article/details/gtyxaknrxv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.fengsongda.top/Article/details/gtttylvwak.html

[U84] JS：CommonJS 写法
来源：http://dali.daxiang520.top/Article/details/gtfagaeajx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.andypj.xyz/Article/details/gtfhynrybm.html

[U85] JS：可选链
来源：http://dali.smart0.xyz/Article/details/gtdmuuljrk.html

a?.b?.c
来源：http://dali.jyoumei.cn/Article/details/gtxvfnfups.html

[U86] JS：空值合并
来源：http://dali.dashuyun.cn/Article/details/gtteilqsyd.html

a ?? b
来源：http://dali.c1oappe.top/Article/details/gtxzkulzdr.html

[U87] JS：解构默认值
来源：http://dali.yj20258888.top/Article/details/gtegtimfwn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxidgjsc.html

[U88] JS：对象展开合并
来源：http://dali.birdmap.top/Article/details/gtuhubdtti.html

{ ...a, ...b }
来源：http://dali.gogol.net.cn/Article/details/gtvitoazrb.html

[U89] JS：数组去重
来源：http://dali.dianchejie.cn/Article/details/gtyxaijwuv.html

[...new Set(arr)]
来源：http://dali.xuetiantiany.cn/Article/details/gtysulanbx.html

[U90] JS：数字数组排序
来源：http://dali.daria6918.cn/Article/details/gttqkyjvma.html

[...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gtiginirgq.html

[U91] JS：对象键值遍历
来源：http://dali.yanxiufei.cn/Article/details/gtzzrpcrmj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.mhx1999.top/Article/details/gtazzffuou.html

[U92] JS：深拷贝
来源：http://dali.jqgfzy.top/Article/details/gtrposcvop.html

structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gtnybjrubb.html

[U93] JS：模板字符串
来源：http://dali.gotoacloud.top/Article/details/gttbyscxjz.html

`共 ${n} 条`
来源：http://dali.daria6918.cn/Article/details/gtnwofkyhx.html

[U94] JS：箭头函数
来源：http://dali.daria6918.cn/Article/details/gtrtjrfbub.html

const double = x => x * 2;
来源：http://dali.havefunace.top/Article/details/gtvlogpbat.html

[U95] JS：Promise 包装
来源：http://dali.jinqigfzy.top/Article/details/gtzxnkksbk.html

new Promise((resolve, reject) => {})
来源：http://dali.zhoulong.xyz/Article/details/gtezaayvby.html

[U96] JS：async/await 与异常
来源：http://dali.jyoumei.cn/Article/details/gtkudthkvz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtcithmwfs.html

[U97] JS：并发请求
来源：http://dali.zhongyouzk.top/Article/details/gtasqtgwvs.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdcbvlfoq.html

[U98] JS：fetch 带 JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtjiasievo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yanxiufei.cn/Article/details/gtobzhbsub.html

[U99] JS：事件监听
来源：http://dali.bjfxy.top/Article/details/gtctvatqxu.html

el.addEventListener("click", e => {})
来源：http://dali.hywenlv.cn/Article/details/gteuowcucm.html

[U100] JS：DOM 查询
来源：http://dali.xziqi.cn/Article/details/gtoyxjhnkj.html

document.querySelector(".item")
来源：http://dali.ivvv.top/Article/details/gttmnbmcrq.html

[U101] JS：classList 操作
来源：http://dali.jqgfzy.top/Article/details/gtxmfyklqm.html

el.classList.toggle("active")
来源：http://dali.yj202588.top/Article/details/gtoofatxga.html

[U102] JS：本地存储
来源：http://dali.cqqwz.cn/Article/details/gtxyrvsevq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yueranfly.top/Article/details/gterikiamr.html

[U103] JS：定时器
来源：http://dali.hnqzz.top/Article/details/gtjqsaszvj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yonumen.top/Article/details/gtvkqyuald.html

[U104] JS：防抖
来源：http://dali.yanxiufei.cn/Article/details/gtfjizhpmb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpxphdix.html

[U105] JS：节流
来源：http://dali.yueranfly.top/Article/details/gticyyszxd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhengqikj.top/Article/details/gtuuiuvxcg.html

[U106] JS：日期格式化
来源：http://dali.smart0.xyz/Article/details/gtfgwcpeim.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.chenlongwang.top/Article/details/gtmfhoalsm.html

[U107] JS：数字千分位
来源：http://dali.zhoulong.xyz/Article/details/gtqyaqulqs.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cashguo.top/Article/details/gtafdweewn.html

[U108] JS：随机整数
来源：http://dali.chenlongwang.top/Article/details/gtxtqoqudk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfrqelsa.html

[U109] JS：数组分组
来源：http://dali.iojbl.cn/Article/details/gtqobwyunx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhixingplan.top/Article/details/gtgdjfbkcb.html

[U110] JS：数组分块
来源：http://dali.hammf.cn/Article/details/gtcdmrztur.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoislqccf.html

[U111] JS：对象转 Map
来源：http://dali.hysaishi.cn/Article/details/gtagysaacm.html

new Map(Object.entries(obj))
来源：http://dali.shanyushiyangtech.top/Article/details/gtsildvvlk.html

[U112] JS：字符串补位
来源：http://dali.gzhubu.top/Article/details/gtzwbbzomn.html

"7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtkunnmzhr.html

[U113] JS：正则替换全部
来源：http://dali.guowangkeji.top/Article/details/gtzrsnbreq.html

s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtiiucqdtw.html

[U114] JS：JSON 深比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtlsnrnqvp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.havefunace.top/Article/details/gtfqkfftts.html

[U115] JS：生成 UUID
来源：http://dali.hongshengwenyu.top/Article/details/gtpmuvafuu.html

crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtcwexjbcg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.tianlin.xyz/Article/details/gtflambosp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.dashuyun.cn/Article/details/gtsycepjod.html

[U117] JS：单元测试
来源：http://dali.nanxuanxn.top/Article/details/gtawoufday.html

npm i -D vitest;  npx vitest
来源：http://dali.daxiang520.top/Article/details/gtlpirkglj.html

[U118] JS：开发服务器
来源：http://dali.nanxinkj.top/Article/details/gtictperih.html

npm i -D vite;  npx vite
来源：http://dali.xuanzx.com/Article/details/gtrcznehyt.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gtblrjyher.html

npx vite build
来源：http://dali.jianghu66.top/Article/details/gtnmdwqtbs.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.0kj1m.cn/Article/details/gtbwovvmna.html

import.meta.env.VITE_API_URL
来源：http://dali.redwolf501.top/Article/details/gtwbryetld.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtjxbbberv.html

统计汇总
来源：http://dali.xuetiantiany.cn/Article/details/gtudumaafb.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtyrznnshk.html

按语言统计（条）：
来源：http://dali.ybcxt.top/Article/details/gthiyeaybf.html

Python ......... 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gtysmwknwt.html

PHP ............ 252
来源：http://dali.jlsjyb.cn/Article/details/gtstbrdotn.html

JavaScript ..... 252
来源：http://dali.snrcjt.cn/Article/details/gtxhrzwtkp.html

TypeScript ..... 212
来源：http://dali.xylfe.cn/Article/details/gtnfwwydym.html

Java ........... 212
来源：http://dali.yonumen.top/Article/details/gtjxptrsfs.html

Go ............. 212
来源：http://dali.ydzc1.top/Article/details/gtrfamrzic.html

Ruby ........... 212
来源：http://dali.ehwqpu.com/Article/details/gtwdtuhwdd.html

C# ............. 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhisbeht.html

C .............. 30
来源：http://dali.zhongyouzk.top/Article/details/gtargreuqp.html

C++ ............ 30
来源：http://dali.jyoumei.cn/Article/details/gtmkjecrxk.html

SQL ............ 90
来源：http://dali.gaohongyu789.top/Article/details/gtixzvpabo.html

Bash ........... 80
来源：http://dali.redwolf501.top/Article/details/gtvkcjxugm.html

Kotlin ......... 15
来源：http://dali.9152youxi.cn/Article/details/gtiyhdzcig.html

Swift .......... 15
来源：http://dali.cqqwz.cn/Article/details/gtoirgxokt.html

Lua ............ 10
来源：http://dali.guannengcc.top/Article/details/gtdfvsicqm.html

Perl ........... 10
来源：http://dali.smart0.xyz/Article/details/gtshbeeobq.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gtzvsvnmha.html

------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gtlpnxoyeh.html

合计 ........... 2106 条
来源：http://dali.andypj.xyz/Article/details/gtenpvcqgm.html

按章节统计：
来源：http://dali.cucudq.cn/Article/details/gtigitpech.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shzxlz.cn/Article/details/gtqkpfinwn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.mhx1999.top/Article/details/gtanvowogb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shzxlz.cn/Article/details/gtlisgmcbn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfncvoci.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.tian-w.cn/Article/details/gtgbfeccqp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hysaishi.cn/Article/details/gtkwsfilrz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jqgufenzy.top/Article/details/gtvtljeppc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhengqikj.top/Article/details/gtlvxzqliy.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihtpmwng.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yuxming.cn/Article/details/gtdugoalqf.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gterlxykfi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gtfnxzyvzb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gtgfjcfzky.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.gotoacloud.top/Article/details/gtkzadaxzz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.nanxuanxn.top/Article/details/gtovceiual.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gtgfoflkwj.html

Q SQL 专题                              90
来源：http://dali.cucudq.cn/Article/details/gtummtvvxj.html

R Bash 专题                             80
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjkwqvzbh.html

S C / C++ 专题                          60
来源：http://dali.nanxinkj.top/Article/details/gtrkialnyd.html

T 其他语言补充                          60
来源：http://dali.sxryk.cn/Article/details/gtijvqbniq.html

U 高频实用片段                         120
来源：http://dali.tanke756.top/Article/details/gtiggqxvma.html

------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gtfmaetqhx.html

合计                                  2106 条
来源：http://dali.ehwqpu.com/Article/details/gtsqyvtzlo.html

--------------------------------------------------------------------------------
来源：http://dali.yvedp.cn/Article/details/gtcwftoigq.html

使用提醒
来源：http://dali.svipenyu.cn/Article/details/gtppdlovqf.html

--------------------------------------------------------------------------------
来源：http://dali.316326.xyz/Article/details/gtwsiyenwo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.shanyushiyangtech.top/Article/details/gtdauejupu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yuanzhike.top/Article/details/gtwzpycknf.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.shangyingyoupin.top/Article/details/gtfpocunnk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.shanyushiyangtech.top/Article/details/gtxptwwbmb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.dianchejie.cn/Article/details/gtvwxmzjza.html

—— 文件结束 ——
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwbotwiq.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtcffpltqa.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.quarkkingdee.top/Article/details/gtqhufmuki.html

Common Programming Examples Cheat Book
来源：http://dali.wangdashe.top/Article/details/gtsjfqjsup.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtszutolrf.html

【收录内容】
来源：http://dali.cucudq.cn/Article/details/gtfrnktqwo.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xziqi.cn/Article/details/gtsfiuizks.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yj20258.top/Article/details/gtyjdpccbi.html

SQL · Bash · C · C++
来源：http://dali.guowangkeji.top/Article/details/gthsjwfvct.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.tianlin.xyz/Article/details/gtrblvches.html

【使用说明】
来源：http://dali.zhengqikj.top/Article/details/gtusjlmjdh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.chenzaomai.com/Article/details/gtccuhdfjs.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jqgfzy.top/Article/details/gtbmwkdytg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.chenzaomai.com/Article/details/gtxqylkuzl.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.cheryme.top/Article/details/gttxkmpphe.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jiagoushi.top/Article/details/gtkhwvbief.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.shanyushiyangtech.top/Article/details/gtxkplycvi.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.tanke756.top/Article/details/gtmshjirmj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yj202588.top/Article/details/gtwwlhflky.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xziqi.cn/Article/details/gttsrszter.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.aibaodan.cn/Article/details/gtjzgcltpa.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhiwuduotai.top/Article/details/gtmwexeqvb.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.gaohongyu789.top/Article/details/gtzywnwigt.html

【文件统计】
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkkjkcgr.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.wangshuangyany.cn/Article/details/gtnhoihkhj.html

--------------------------------------------------------------------------------
来源：http://dali.xziqi.cn/Article/details/gtszjpsows.html

目  录
来源：http://dali.tianlin.xyz/Article/details/gtitjwyhmj.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gtehbfidoa.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cheryme.top/Article/details/gtwraagpwl.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.iojbl.cn/Article/details/gtxyzzmtgl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.havefunace.top/Article/details/gtsreonqzk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.bjfxy.top/Article/details/gtkewyctyc.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ivvv.top/Article/details/gtpyecfmzk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.daria6918.cn/Article/details/gtluheglff.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcgkuxij.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ppjwa.cn/Article/details/gtuieqkmzo.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gtsxigdiph.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shuidangran.top/Article/details/gtmuapyxgo.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gtvcfrnlxb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.guannengcc.top/Article/details/gtvvdyivym.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gtiovndmox.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hnxiangtu.top/Article/details/gtypmwvbub.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.aibaodan.cn/Article/details/gtzmcoiuba.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gtvepqgprw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.kuanghao11.cn/Article/details/gtifpwdwgi.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zycfv.cn/Article/details/gtgxezzheu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hnqzz.top/Article/details/gtaxazaqmh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgufenzy.top/Article/details/gtdrwbgsii.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yangfankeji.com/Article/details/gtozdatjjt.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtwfchycej.html

A. 基础语法与类型
来源：http://dali.birdmap.top/Article/details/gtltvqpulp.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtlyubtyei.html

[A01] Hello World
来源：http://dali.gaohongyu789.top/Article/details/gthydmerso.html

Py:   print("Hello, World!")
来源：http://dali.yvedp.cn/Article/details/gtgcmwterw.html

PHP:  echo "Hello, World!";
来源：http://dali.ybcxt.top/Article/details/gteodicnrc.html

JS:   console.log("Hello, World!");
来源：http://dali.cucudq.cn/Article/details/gtvttwksms.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpuervzf.html

Java: System.out.println("Hello, World!");
来源：http://dali.chenjidiqi.icu/Article/details/gtkpkxluch.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sweek.top/Article/details/gtmjbsjozy.html

Ruby: puts "Hello, World!"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfphosgo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.316326.xyz/Article/details/gtxlhsmzrg.html

[A02] 变量声明与赋值
来源：http://dali.pycfn.com/Article/details/gtjzhxarzy.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.quarkkingdee.top/Article/details/gtgrdxochg.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gtqiskendz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.redwolf501.top/Article/details/gtmvdndfza.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.smart0.xyz/Article/details/gtlepbvboh.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.bjfxy.top/Article/details/gthbxgdntg.html

Go:   name := "Alex"; age := 20
来源：http://dali.sweek.top/Article/details/gtdulcendp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.0kj1m.cn/Article/details/gtdtvuhukw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.dianchejie.cn/Article/details/gtflskmlad.html

[A03] 常量定义
来源：http://dali.birdmap.top/Article/details/gttcvbieqc.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamcnfpwx.html

PHP:  const PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtzmzjyogh.html

JS:   const PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtpogeforn.html

TS:   const PI: number = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtuvpmptll.html

Java: static final double PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtjwzbwtxv.html

Go:   const PI = 3.14159
来源：http://dali.hywenlv.cn/Article/details/gtzpzyjrzf.html

Ruby: PI = 3.14159
来源：http://dali.sweek.top/Article/details/gtvlkcciya.html

C#:   const double PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtczzebime.html

[A04] 判断变量类型
来源：http://dali.xuanzx.com/Article/details/gtcgilhxbr.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jinqigfzy.top/Article/details/gtaxhbqdel.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hnxiangtu.top/Article/details/gtvamznhgg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zycfv.cn/Article/details/gtcqfjuett.html

TS:   typeof x; x instanceof Date
来源：http://dali.ybcxt.top/Article/details/gtmfqeeemk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xylfe.cn/Article/details/gtjufjtwfu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jqgfzy.top/Article/details/gtdtujwfjs.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.sweek.top/Article/details/gtwmyuxtdx.html

C#:   x.GetType().Name; x is int
来源：http://dali.jqgufenzy.top/Article/details/gtapubhoxb.html

[A05] 整数除法与取模
来源：http://dali.meibo888.top/Article/details/gtsjvlnmfb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.316326.xyz/Article/details/gtyptuazip.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ydzc1.top/Article/details/gtftbburjl.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gzhubu.top/Article/details/gtkxuqqjuv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hnqzz.top/Article/details/gtaqzbccpu.html

Java: 7 / 2; 7 % 2
来源：http://dali.yvedp.cn/Article/details/gtaikyislh.html

Go:   7 / 2; 7 % 2
来源：http://dali.dashuyun.cn/Article/details/gtpszghuwi.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gttupmxyqa.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxujhzmy.html

[A06] 字符串转数字
来源：http://dali.zhoulong.xyz/Article/details/gtbgxdbydb.html

Py:   int("42"); float("3.14")
来源：http://dali.sweek.top/Article/details/gtdlpzwzxa.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yuanzhike.top/Article/details/gtqtzmcxmf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhengqikj.top/Article/details/gthmoxkfmg.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.chenjidiqi.icu/Article/details/gtynlkavkr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.aibaodan.cn/Article/details/gtrhlcbnsg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.xylfe.cn/Article/details/gtbiixdsqi.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.fengsongda.top/Article/details/gtvwlunibz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhongyouzk.top/Article/details/gtonlucndf.html

[A07] 数字转字符串
来源：http://dali.kuanghao11.cn/Article/details/gthzcbzlpp.html

Py:   str(42)
来源：http://dali.jinqigufen.top/Article/details/gtgxzcwuxm.html

PHP:  (string) 42; strval(42)
来源：http://dali.vqdsnc.cn/Article/details/gthevlobcs.html

JS:   String(42); (42).toString()
来源：http://dali.iojbl.cn/Article/details/gtjmmyauap.html

TS:   String(42)
来源：http://dali.jianghu66.top/Article/details/gtkdorqrun.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yongpay.top/Article/details/gternwmioo.html

Go:   strconv.Itoa(42)
来源：http://dali.xziqi.cn/Article/details/gtsibfzmlw.html

Ruby: 42.to_s
来源：http://dali.cdnleiting.top/Article/details/gtfgdodmjk.html

C#:   42.ToString()
来源：http://dali.yonumen.top/Article/details/gtdlqcwsro.html

[A08] 取整与四舍五入
来源：http://dali.shangyingyoupin.top/Article/details/gtjcazldzc.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.smart0.xyz/Article/details/gttrrojjup.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.mhx1999.top/Article/details/gtgleonmdz.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.hysaishi.cn/Article/details/gtjvfminmr.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.9152youxi.cn/Article/details/gtaluulvyi.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yvedp.cn/Article/details/gtsgkgszpg.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.sysykeji.top/Article/details/gtgsqudole.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.mhx1999.top/Article/details/gtmznihtan.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdnwkjygt.html

[A09] 绝对值与最大最小值
来源：http://dali.cucudq.cn/Article/details/gtlptthfkh.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxiawhssn.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.iojbl.cn/Article/details/gtnbtymxcs.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.redwolf501.top/Article/details/gtjhxsruji.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjyvxvje.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.c1oappe.top/Article/details/gtywbylqpn.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yueranfly.top/Article/details/gtmmwfbdaf.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.sysykeji.top/Article/details/gtxdbtouif.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtgyepuqkl.html

[A10] 生成随机数
来源：http://dali.zhoulong.xyz/Article/details/gtouqitrfi.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jianghu66.top/Article/details/gtolbdgmgr.html

PHP:  random_int(1, 100);
来源：http://dali.chenjidiqi.icu/Article/details/gtwcwehjki.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zycfv.cn/Article/details/gtdpkljxmv.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.meibo888.top/Article/details/gtfxckntjg.html

Java: new Random().nextInt(100) + 1
来源：http://dali.cdnleiting.top/Article/details/gtwtlmohes.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hnxiangtu.top/Article/details/gtltcjpxsj.html

Ruby: rand(1..100)
来源：http://dali.gogol.net.cn/Article/details/gtyyggshgq.html

C#:   new Random().Next(1, 101)
来源：http://dali.andypj.xyz/Article/details/gtdayaftaw.html

[A11] 条件表达式（三元）
来源：http://dali.chenlongwang.top/Article/details/gtjzkvecql.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.pycfn.com/Article/details/gthxopkpqd.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.tian-w.cn/Article/details/gtdsxrldno.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.nanxuanxn.top/Article/details/gtmcppkcoa.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yongpay.top/Article/details/gtlfzlmuyu.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.hongshengwenyu.top/Article/details/gtoidfuajx.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhcbwmyk.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.quarkkingdee.top/Article/details/gttdafqbic.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.xziqi.cn/Article/details/gtxefexrbv.html

[A12] 字符串插值 / 格式化
来源：http://dali.andypj.xyz/Article/details/gtksjvkdbp.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.cucudq.cn/Article/details/gtvwvmmwtz.html


<!-- 参考信息 -->