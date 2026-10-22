代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.quarkkingdee.top/Article/details/gtyvvyghmn.html

composer require psr/container
来源：http://dali.svipenyu.cn/Article/details/gtuycyjjir.html

[U76] PHP：简单路由
来源：http://dali.hnxiangtu.top/Article/details/gtgthdofkw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgkenzaj.html

[U77] PHP：模板渲染
来源：http://dali.gotoacloud.top/Article/details/gttxnwytgc.html

composer require twig/twig
来源：http://dali.fzhhl.top/Article/details/gtfnjnyicz.html

[U78] PHP：单元测试
来源：http://dali.xinyue.icu/Article/details/gtrpqzhlzd.html

composer require --dev phpunit/phpunit
来源：http://dali.zhixingplan.top/Article/details/gtpivfvaaq.html

[U79] PHP：静态分析
来源：http://dali.hnxiangtu.top/Article/details/gtkokdfwvg.html

composer require --dev phpstan/phpstan
来源：http://dali.svipenyu.cn/Article/details/gtlvtvsiuv.html

[U80] PHP：代码规范修复
来源：http://dali.hnqzz.top/Article/details/gthiindyri.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ehwqpu.com/Article/details/gtgliwingj.html

[U81] JS：初始化项目
来源：http://dali.daria6918.cn/Article/details/gtkeprpzfi.html

npm init -y;  npm i express
来源：http://dali.jinyuanbaomall.cn/Article/details/gtredzlzft.html

[U82] JS：package.json 脚本
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtorzcbger.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.wangshuangyany.cn/Article/details/gtocjdcnbk.html

[U83] JS：ES Module 导入导出
来源：http://dali.jyoumei.cn/Article/details/gtcybrwzld.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jlsjyb.cn/Article/details/gtapgcuyed.html

[U84] JS：CommonJS 写法
来源：http://dali.jinqigufen.top/Article/details/gtuaycynwg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cdnleiting.top/Article/details/gtzijntfnx.html

[U85] JS：可选链
来源：http://dali.nanxinkj.top/Article/details/gtbuvvzjmy.html

a?.b?.c
来源：http://dali.jqgfzy.top/Article/details/gtjlasobtq.html

[U86] JS：空值合并
来源：http://dali.tian-w.cn/Article/details/gtquuappep.html

a ?? b
来源：http://dali.cashguo.top/Article/details/gtlkyfhunx.html

[U87] JS：解构默认值
来源：http://dali.tian-w.cn/Article/details/gtemtbezvw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yuxming.cn/Article/details/gtxntksbeg.html

[U88] JS：对象展开合并
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrogvmpw.html

{ ...a, ...b }
来源：http://dali.cqqwz.cn/Article/details/gtmycevrtu.html

[U89] JS：数组去重
来源：http://dali.fengsongda.top/Article/details/gttawdmweg.html

[...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gtjjzlbrco.html

[U90] JS：数字数组排序
来源：http://dali.c1oappe.top/Article/details/gtxnogltxt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gtfzcxmjgn.html

[U91] JS：对象键值遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsikrzfjg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.havefunace.top/Article/details/gtuqlcamof.html

[U92] JS：深拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtmyxgjzee.html

structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gtmtxsrlji.html

[U93] JS：模板字符串
来源：http://dali.yonumen.top/Article/details/gtnofwpzqd.html

`共 ${n} 条`
来源：http://dali.shzxlz.cn/Article/details/gtcdrpnyiu.html

[U94] JS：箭头函数
来源：http://dali.pengpengdd.cyou/Article/details/gtzwjdbuul.html

const double = x => x * 2;
来源：http://dali.jqgufenzy.top/Article/details/gtoapehimj.html

[U95] JS：Promise 包装
来源：http://dali.chenlongwang.top/Article/details/gtdehbkoom.html

new Promise((resolve, reject) => {})
来源：http://dali.316326.xyz/Article/details/gtxbfjeadd.html

[U96] JS：async/await 与异常
来源：http://dali.quarkkingdee.top/Article/details/gtvgfpwzll.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gtneuzsaje.html

[U97] JS：并发请求
来源：http://dali.haohaochexian.top/Article/details/gtflidjoyb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gtpjqmfbiv.html

[U98] JS：fetch 带 JSON
来源：http://dali.xziqi.cn/Article/details/gtawbpiwzt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.ehwqpu.com/Article/details/gtsfemvbih.html

[U99] JS：事件监听
来源：http://dali.yj20258888.top/Article/details/gthuoexkqd.html

el.addEventListener("click", e => {})
来源：http://dali.jqgfzy.top/Article/details/gtplpodrbk.html

[U100] JS：DOM 查询
来源：http://dali.svipenyu.cn/Article/details/gtuwteddlu.html

document.querySelector(".item")
来源：http://dali.nwbrower.top/Article/details/gtdiavuxav.html

[U101] JS：classList 操作
来源：http://dali.gotoacloud.top/Article/details/gthogzeevs.html

el.classList.toggle("active")
来源：http://dali.xylfe.cn/Article/details/gtfhfkbldw.html

[U102] JS：本地存储
来源：http://dali.gotoacloud.top/Article/details/gtqvaawwvw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hongshengwenyu.top/Article/details/gtaykgcfcf.html

[U103] JS：定时器
来源：http://dali.zhongyouzk.top/Article/details/gtfbpmkboy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.iojbl.cn/Article/details/gtgdtvcmbk.html

[U104] JS：防抖
来源：http://dali.ydzc1.top/Article/details/gtorkeawwd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gtildmrfow.html

[U105] JS：节流
来源：http://dali.yueranfly.top/Article/details/gtqowxegbj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zdqjudy.top/Article/details/gtwnownrzy.html

[U106] JS：日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gtbitgjdxk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shanyushiyangtech.top/Article/details/gtagqozmkk.html

[U107] JS：数字千分位
来源：http://dali.yonumen.top/Article/details/gtgwghyomx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.quarkkingdee.top/Article/details/gtgmdjjfxi.html

[U108] JS：随机整数
来源：http://dali.dashuyun.cn/Article/details/gtqanandut.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.gogol.net.cn/Article/details/gtumjhaxez.html

[U109] JS：数组分组
来源：http://dali.nanxuanxn.top/Article/details/gtpbotkosn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shangyingyoupin.top/Article/details/gtxvkccoad.html

[U110] JS：数组分块
来源：http://dali.yangfankeji.com/Article/details/gttrnmvlcb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.meibo888.top/Article/details/gtjsnhlewv.html

[U111] JS：对象转 Map
来源：http://dali.nanxuanxn.top/Article/details/gtwrvqgaae.html

new Map(Object.entries(obj))
来源：http://dali.shzxlz.cn/Article/details/gtutpmjnse.html

[U112] JS：字符串补位
来源：http://dali.havefunace.top/Article/details/gtzdwhdncm.html

"7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtxthgemtz.html

[U113] JS：正则替换全部
来源：http://dali.birdmap.top/Article/details/gtcumvlibl.html

s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gthdacyrme.html

[U114] JS：JSON 深比较
来源：http://dali.jlsjyb.cn/Article/details/gtkbimxhcd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guannengcc.top/Article/details/gtiypabefm.html

[U115] JS：生成 UUID
来源：http://dali.haohaochexian.top/Article/details/gtouqqkchi.html

crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gtgjdhegiz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.guowangkeji.top/Article/details/gthhicvpea.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yueranfly.top/Article/details/gtxsemmwcy.html

[U117] JS：单元测试
来源：http://dali.yongpay.top/Article/details/gtfmflptax.html

npm i -D vitest;  npx vitest
来源：http://dali.nanxinkj.top/Article/details/gttxkssgwp.html

[U118] JS：开发服务器
来源：http://dali.zhiwuduotai.top/Article/details/gtphkpjenp.html

npm i -D vite;  npx vite
来源：http://dali.andypj.xyz/Article/details/gtfbqpysmk.html

[U119] JS：生产构建
来源：http://dali.gotoacloud.top/Article/details/gtqecmbeic.html

npx vite build
来源：http://dali.ppjwa.cn/Article/details/gtkpbkmosh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cqqwz.cn/Article/details/gtnhbfbjvo.html

import.meta.env.VITE_API_URL
来源：http://dali.jqgfzy.top/Article/details/gtrlinndky.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujdssviw.html

统计汇总
来源：http://dali.gogol.net.cn/Article/details/gtnlkpnlms.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtfdmnhxmh.html

按语言统计（条）：
来源：http://dali.9152youxi.cn/Article/details/gtcxckmxah.html

Python ......... 252
来源：http://dali.xinyue.icu/Article/details/gtydjqbfwg.html

PHP ............ 252
来源：http://dali.gzhubu.top/Article/details/gtqwzfpkvy.html

JavaScript ..... 252
来源：http://dali.dianchejie.cn/Article/details/gtqyqjgfva.html

TypeScript ..... 212
来源：http://dali.shanyushiyangtech.top/Article/details/gttrcvzutt.html

Java ........... 212
来源：http://dali.yj202588.top/Article/details/gtqnkxvjve.html

Go ............. 212
来源：http://dali.wangshuangyany.cn/Article/details/gtmibbiaoa.html

Ruby ........... 212
来源：http://dali.jyoumei.cn/Article/details/gtzcpuneax.html

C# ............. 212
来源：http://dali.hnqzz.top/Article/details/gtvldysvrs.html

C .............. 30
来源：http://dali.xziqi.cn/Article/details/gtnvripcay.html

C++ ............ 30
来源：http://dali.dianchejie.cn/Article/details/gtophfggpt.html

SQL ............ 90
来源：http://dali.jiagoushi.top/Article/details/gtjmzmuyju.html

Bash ........... 80
来源：http://dali.gaohongyu789.top/Article/details/gtfwjtcwze.html

Kotlin ......... 15
来源：http://dali.tian-w.cn/Article/details/gtdivcugsr.html

Swift .......... 15
来源：http://dali.smart0.xyz/Article/details/gtqbucvrjm.html

Lua ............ 10
来源：http://dali.haohaochexian.top/Article/details/gtskmwxfyx.html

Perl ........... 10
来源：http://dali.haohaochexian.top/Article/details/gtnxdebglu.html

Scala .......... 10
来源：http://dali.9152youxi.cn/Article/details/gtnzqrxsgg.html

------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gtmgwefkkn.html

合计 ........... 2106 条
来源：http://dali.xziqi.cn/Article/details/gttfjenqek.html

按章节统计：
来源：http://dali.redwolf501.top/Article/details/gtemlidzld.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.mhx1999.top/Article/details/gtnnyhmqyq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.meibo888.top/Article/details/gthlrroksw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.chenjidiqi.icu/Article/details/gttdfjsvdg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedisqiaq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hfpthk.cn/Article/details/gtasezeglu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.chenjidiqi.icu/Article/details/gtvhoeqapz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.haohaochexian.top/Article/details/gtrmmwzvvd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hongshengwenyu.top/Article/details/gtzqtiedlq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gtfudiuvoc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hongshengwenyu.top/Article/details/gtbadglmuq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gtvsbuevrh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gtgfvpqhnu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yj20258888.top/Article/details/gtgvhnwght.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ppjwa.cn/Article/details/gthrbwrejh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.dianchejie.cn/Article/details/gtgvdbxobw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gtkxjaiwvl.html

Q SQL 专题                              90
来源：http://dali.andypj.xyz/Article/details/gtyplxffbw.html

R Bash 专题                             80
来源：http://dali.daria6918.cn/Article/details/gtpeggjwak.html

S C / C++ 专题                          60
来源：http://dali.mhx1999.top/Article/details/gtpffrzrnm.html

T 其他语言补充                          60
来源：http://dali.tian-w.cn/Article/details/gtopfvztfk.html

U 高频实用片段                         120
来源：http://dali.zycfv.cn/Article/details/gtiuspqpvm.html

------------------------------------
来源：http://dali.cheryme.top/Article/details/gtkgbarkmk.html

合计                                  2106 条
来源：http://dali.shzxlz.cn/Article/details/gtncfasref.html

--------------------------------------------------------------------------------
来源：http://dali.daria6918.cn/Article/details/gtrubomrko.html

使用提醒
来源：http://dali.jinqigfzy.top/Article/details/gtovdvoilq.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gtliczswag.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhengqikj.top/Article/details/gtqshykfvf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.gaohongyu789.top/Article/details/gtfnazjuxo.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhndavrm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.pycfn.com/Article/details/gtbmhqzcwi.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.sxryk.cn/Article/details/gtcrsotzbd.html

—— 文件结束 ——
来源：http://dali.316326.xyz/Article/details/gtgjcanrsl.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtinpwekbe.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cashguo.top/Article/details/gtyfsylmni.html

Common Programming Examples Cheat Book
来源：http://dali.jlsjyb.cn/Article/details/gtafenqifg.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gthcsonkpo.html

【收录内容】
来源：http://dali.aizwys.cn/Article/details/gtvdcvwjwq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yj20258.top/Article/details/gttpwhffzd.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.tian-w.cn/Article/details/gtighvkxcr.html

SQL · Bash · C · C++
来源：http://dali.yj202588.top/Article/details/gtgddhvxog.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jinghuilouyu.cn/Article/details/gtrthdanyu.html

【使用说明】
来源：http://dali.fzhhl.top/Article/details/gtitgrlbsr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jinghuilouyu.cn/Article/details/gtfyegfayc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yj20258.top/Article/details/gttmihakpv.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.quarkkingdee.top/Article/details/gtisspimro.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxcshldhd.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.nwbrower.top/Article/details/gtwstlldfe.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhengqikj.top/Article/details/gtzbdonvdv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jlsjyb.cn/Article/details/gtvjqtxqet.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.aibaodan.cn/Article/details/gtcespfxmg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.gzhubu.top/Article/details/gtwtoiemqk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xziqi.cn/Article/details/gthboysbkn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.cdnleiting.top/Article/details/gtxrhoqnya.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yongpay.top/Article/details/gtumtdwkvf.html

【文件统计】
来源：http://dali.ppjwa.cn/Article/details/gtksemjefo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.cashguo.top/Article/details/gtbduguoqd.html

--------------------------------------------------------------------------------
来源：http://dali.gaohongyu789.top/Article/details/gtjkkarnpt.html

目  录
来源：http://dali.daria6918.cn/Article/details/gtroxkwspx.html

--------------------------------------------------------------------------------
来源：http://dali.xinyue.icu/Article/details/gtcbvlaqft.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.bjfxy.top/Article/details/gthajkduac.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ybcxt.top/Article/details/gtamjesone.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.gaohongyu789.top/Article/details/gtcmopptft.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xuanzx.com/Article/details/gtowwhzdob.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.tianlin.xyz/Article/details/gtjbwfcxzb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.cucudq.cn/Article/details/gtnynaurws.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hfpthk.cn/Article/details/gtaizjukkr.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jianghu66.top/Article/details/gtmqyxpjuy.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.0kj1m.cn/Article/details/gttyomdrqa.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.sysykeji.top/Article/details/gtiwwxovig.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jqgufenzy.top/Article/details/gtnijdfoyx.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.bjfxy.top/Article/details/gtwdiektxd.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gtwuurqcbz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.sxryk.cn/Article/details/gtsnuhmuzz.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.vqdsnc.cn/Article/details/gtptlxyacz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gtlkhscwej.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ehwqpu.com/Article/details/gtlfvqxzzl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.bjfxy.top/Article/details/gtqwqqsnqq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.mhx1999.top/Article/details/gtrqkmlypt.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gtzgxjjcun.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ybcxt.top/Article/details/gtwxahscsc.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gthntsicqz.html

A. 基础语法与类型
来源：http://dali.jiagoushi.top/Article/details/gtkeojezyj.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtefuxidrb.html

[A01] Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtnlbqtasl.html

Py:   print("Hello, World!")
来源：http://dali.gotoacloud.top/Article/details/gtpxhttxtk.html

PHP:  echo "Hello, World!";
来源：http://dali.zhixingplan.top/Article/details/gttcimapji.html

JS:   console.log("Hello, World!");
来源：http://dali.wangdashe.top/Article/details/gtpukupgdm.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.havefunace.top/Article/details/gtdfbrlngo.html

Java: System.out.println("Hello, World!");
来源：http://dali.hywenlv.cn/Article/details/gtbhubnkjs.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.nwbrower.top/Article/details/gtpclzvhsy.html

Ruby: puts "Hello, World!"
来源：http://dali.tanke756.top/Article/details/gtcwkztydc.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.daxiang520.top/Article/details/gtpsdzgogb.html

[A02] 变量声明与赋值
来源：http://dali.yuxming.cn/Article/details/gtxqezthof.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hongshengwenyu.top/Article/details/gtyrehvtyo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hnxiangtu.top/Article/details/gthpebatof.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.gzhubu.top/Article/details/gtcyvtrfpa.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gotoacloud.top/Article/details/gtwarrzfsg.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.chenjidiqi.icu/Article/details/gtshpgrebb.html

Go:   name := "Alex"; age := 20
来源：http://dali.hammf.cn/Article/details/gtwmgwaxvd.html

Ruby: name = "Alex"; age = 20
来源：http://dali.sysykeji.top/Article/details/gtzforgiki.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.shuidangran.top/Article/details/gtyrnfoacm.html

[A03] 常量定义
来源：http://dali.kuanghao11.cn/Article/details/gtiicektua.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.xuetiantiany.cn/Article/details/gtlacnobty.html

PHP:  const PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtjelfqkor.html

JS:   const PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgzwotyf.html

TS:   const PI: number = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtuxzizqbj.html

Java: static final double PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtrmngnmkq.html

Go:   const PI = 3.14159
来源：http://dali.ydzc1.top/Article/details/gtkwpqmrcb.html

Ruby: PI = 3.14159
来源：http://dali.tianlin.xyz/Article/details/gtbbeqefwr.html

C#:   const double PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtykswlzna.html

[A04] 判断变量类型
来源：http://dali.iojbl.cn/Article/details/gtwnlbotkp.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhixingplan.top/Article/details/gtkhjfueoh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cucudq.cn/Article/details/gtdtmtdzrh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.svipenyu.cn/Article/details/gtcasfkkdb.html

TS:   typeof x; x instanceof Date
来源：http://dali.zdqjudy.top/Article/details/gtlatwrjhj.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.cqqwz.cn/Article/details/gtluhfptxp.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.iojbl.cn/Article/details/gtjgtboqks.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jinqigfzy.top/Article/details/gtnealobih.html

C#:   x.GetType().Name; x is int
来源：http://dali.aizwys.cn/Article/details/gtjohpwjnr.html

[A05] 整数除法与取模
来源：http://dali.guannengcc.top/Article/details/gtabprewkt.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zdqjudy.top/Article/details/gtzmsorbmf.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gtpfukewdw.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.daria6918.cn/Article/details/gtmssesflb.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdaxidffk.html

Java: 7 / 2; 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gtdhjiyerf.html

Go:   7 / 2; 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtlqjcyioz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hammf.cn/Article/details/gtbcbgkgsa.html

C#:   7 / 2; 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycsjeagt.html

[A06] 字符串转数字
来源：http://dali.iojbl.cn/Article/details/gtatcgdako.html

Py:   int("42"); float("3.14")
来源：http://dali.daria6918.cn/Article/details/gtppatqqjr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gtctrhfrkg.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.bjfxy.top/Article/details/gthaaaxkdg.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jqgufenzy.top/Article/details/gtxgnsmhuq.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cheryme.top/Article/details/gtlwqxqtjw.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.fengsongda.top/Article/details/gtdvpxifil.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.mhx1999.top/Article/details/gtgnapqglt.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jqgufenzy.top/Article/details/gtqnjroqlz.html

[A07] 数字转字符串
来源：http://dali.sufxvd.cn/Article/details/gtkbjicevq.html

Py:   str(42)
来源：http://dali.daria6918.cn/Article/details/gtpjauipoq.html

PHP:  (string) 42; strval(42)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwjjkyqi.html

JS:   String(42); (42).toString()
来源：http://dali.sufxvd.cn/Article/details/gtztbxbhdu.html

TS:   String(42)
来源：http://dali.yuxming.cn/Article/details/gtygnyfqkv.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.andypj.xyz/Article/details/gtynapnwqw.html

Go:   strconv.Itoa(42)
来源：http://dali.zhixingplan.top/Article/details/gtavvqmyjw.html

Ruby: 42.to_s
来源：http://dali.zycfv.cn/Article/details/gtkqdrsgyt.html

C#:   42.ToString()
来源：http://dali.xylfe.cn/Article/details/gtnqspkxyn.html

[A08] 取整与四舍五入
来源：http://dali.jyoumei.cn/Article/details/gtejhtklgk.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.havefunace.top/Article/details/gtupkkgtgl.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.guannengcc.top/Article/details/gtuhnvfiuh.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yanxiufei.cn/Article/details/gtrzoraiho.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxsnjvvf.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.chenjidiqi.icu/Article/details/gtyeglqikh.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.wangshuangyany.cn/Article/details/gtwtcxlkoe.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.nwbrower.top/Article/details/gtikubnnjp.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.havefunace.top/Article/details/gttbcdftyk.html

[A09] 绝对值与最大最小值
来源：http://dali.sweek.top/Article/details/gtexsztaml.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.bjfxy.top/Article/details/gtpwvyjlji.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.iojbl.cn/Article/details/gthoxyflwj.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtsfbmcltm.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtkowiqueq.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.daria6918.cn/Article/details/gtuywwkgxg.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hywenlv.cn/Article/details/gtgdndkqeq.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.andypj.xyz/Article/details/gtpjvlabil.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtzwkdxbxy.html

[A10] 生成随机数
来源：http://dali.cashguo.top/Article/details/gtmdhntova.html

Py:   import random; random.randint(1, 100)
来源：http://dali.wangdashe.top/Article/details/gttyltpcip.html

PHP:  random_int(1, 100);
来源：http://dali.zhiwuduotai.top/Article/details/gtmaaxivjt.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.chenjidiqi.icu/Article/details/gtilcgswbr.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shuidangran.top/Article/details/gthxzfqsfc.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhongyouzk.top/Article/details/gtztfemjjm.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.redwolf501.top/Article/details/gtcmhcxjql.html

Ruby: rand(1..100)
来源：http://dali.svipenyu.cn/Article/details/gtuelrdact.html

C#:   new Random().Next(1, 101)
来源：http://dali.wangdashe.top/Article/details/gtxpptcesg.html

[A11] 条件表达式（三元）
来源：http://dali.cucudq.cn/Article/details/gthkpalwlh.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yuanzhike.top/Article/details/gtadvizvsv.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhiwuduotai.top/Article/details/gtawopuypl.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.cashguo.top/Article/details/gtiqgfphum.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gtdssuwhoe.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhiwuduotai.top/Article/details/gtmbaheeqa.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.havefunace.top/Article/details/gtsvzyjaiq.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.9152youxi.cn/Article/details/gtrhhztbdn.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yanxiufei.cn/Article/details/gtqrhrddiv.html

[A12] 字符串插值 / 格式化
来源：http://dali.xinyue.icu/Article/details/gtftjluvca.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.hammf.cn/Article/details/gtuhmvrygm.html


<!-- 参考信息 -->